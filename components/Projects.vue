<template>
    <div id="projects">
        <h1>Take a look at our recent work!</h1>
        <div id="project_div">
            <div class="project_card">
                <h1>bestpet.tech</h1>
                    <a href='https://bestpet.tech/'>
                        <img class="project_image" src='./Images/bestpet.png' >
                    </a>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat</p>
            </div>
            <div class="project_card">
                <h1>ServiceDash</h1>
                <a href='http://service-dash.com/'>
                    <img class="project_image" src='./Images/service-dash.png'>
                </a>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat</p>
            </div>
        </div>
    </div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css?family=Pontano+Sans');

    #projects {
        height: 100vh;
        display: flex;
        align-items: center;
        flex-direction: column;
        justify-content: space-evenly;
    }
    #project_div{
        width: 100vw;
        display: flex;
        flex-direction: row;
        align-items: center;
        justify-content: space-evenly;
        margin-bottom: 20vh;
    }
    .project_card{
        display: flex;
        flex-direction: column;
        justify-content: space-around;
        align-items: center;
        width: 40vw;
        height: 60vh;
        box-shadow: 6px 4px 8px 0 rgba(0,0,0,0.2), -6px -2px 8px 0 rgba(0,0,0,0.2);

    }
    p{
        width: 35vw;
    }
    h1{
        font-family: 'Pontano Sans', sans-serif;
        font-size: 200%;
    }
    .project_image{
        width: 35vw;
    }
</style>
