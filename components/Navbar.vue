<template>
  <div class="wrapper">
    <div class='nav'>
        <h2>Portfolio</h2>
        <div class='links'>
            <a href='/' class='navbar-item'>Home</a>
            <a href='/' class='navbar-item'>About</a>
            <a href='/' class='navbar-item'>Projects</a>
            <a href='/' class='navbar-item'>Contact</a>
        </div>
    </div>
  </div>
</template>

<style scoped>

    .wrapper{
        position: sticky;
        top: 0;
    }
    
    .nav{
        display: flex;
        justify-content: space-between;
        align-items: center;
        background: #303030ed;
        padding: 0 100px;
    }

    .nav > h2{
        color: white;
        font-size: 1.9em;
        font-weight: 500;
    }

    .links{
        display:flex;
        justify-content: space-around;
    }

    .links > a{
        text-decoration: none;
        color: white;
        display: block;
        padding: 30px 15px;
        font-size: 0.9em;
    }

    .links > a:hover{
        background:#1d1d1d;
    }
</style>