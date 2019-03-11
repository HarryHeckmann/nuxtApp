<template>
    <div class="showcase">
        <div class="showcase-title">
            <h2>Harry & Lee</h2>
            <h3>Developing Websites Since Literally Yesterday</h3>
            <button>Our Projects</button>
        </div>
    </div>
</template>

<style scoped>
    .showcase{
        display:flex;
        justify-content: center;
        align-items: center;
        height: 85vh;
    }

    .showcase::after{
        background-image: url('https://images.pexels.com/photos/160107/pexels-photo-160107.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260');
        background-position:  center;
        content: "";
        opacity: 0.9;
        top: 0;
        left: 0;
        bottom: 0;
        right: 0;
        position: absolute;
        z-index: -1;
        overflow: hidden;
    }

    .showcase-title{
        text-align: center;
    }

    h2{
        font-size: 3.5em;
        color: white;
        text-shadow: 1px 2px 3px black;
        font-weight: 600;
    }

    h3{
        font-size: 2em;
        padding-top: 10px;
        font-weight: 400;
        color: white;
        text-shadow: 1px 2px 3px black;
    }
    
    button{
        padding: 20px 55px;
        color: white;
        background: #2f2f2f;
        font-size: 1.2em;
        font-weight: thin;
        border: none;
        margin-top: 10px;
        cursor: pointer;
    }

    button:hover{
        background: #1d1d1d;
    }
</style>
