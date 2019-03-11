<template>
    <div id='about'>
        <h1>About Us</h1>
        <div id="info_box_div">
            <div class="info_box">
                <img id="lee" src="./Images/lee.jpg"/>
                <h1>Lee</h1>
                <p class='info'>Doggo ipsum floofs dat tungg tho maximum borkdrive, most angery pupper I have ever seen. Doge shibe boofers pats pupperino ur givin me a spook, very taste wow floofs pupperino. Doge bork snoot yapper dat tungg tho, clouds very hand that feed shibe. Big ol pupper vvv yapper vvv waggy wags, mlem doggo very jealous pupper. Porgo length boy heckin good boys big ol pupper h*ck lotsa pats wrinkler, clouds long woofer what a nice floof pupperino.
                </p>
            </div>
            <div class="info_box">
                <img id="harry" src="./Images/harry.jpg"/>
                <h1>Harry</h1>
                <p class='info'>Ruff pupperino clouds boof, long water shoob heckin big ol, boofers clouds. Puggo fluffer he made many woofs long water shoob borking doggo, borkf noodle horse clouds smol borking doggo with a long snoot for pats shibe, corgo heckin good boys stop it fren. Clouds borkf many pats very taste wow you are doin me a concern woofer, smol what a nice floof very hand that feed shibe. You are doing me a frighten many pats borkf wow such tempt vvv, doggo many pats. Wow such tempt he made many woofs pats, borkf.
                </p>
            </div>
        </div>
    </div>
</template>


<style scoped>
#about{
    height: 100vh;
    width: 100vw;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-around;
}
#info_box_div{
    width: 100vw;
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    align-items: center;
}
#harry{
    transform: rotate(-90deg);
    width: 40vh;
    /* width: 75%; */
    margin-top: 7vh;
    margin-bottom: 10vh
}
#lee{
    height: 40vh;
    /* width: 75%; */
    margin-bottom: 5vh;
}
.info_box{
    display: flex;
    flex-direction: column;
    width: 38vw;
    height: 80vh;
    padding: 5vw;
    align-items: center;
    box-shadow: 6px 4px 8px 0 rgba(0,0,0,0.2), -6px -2px 8px 0 rgba(0,0,0,0.2);
}
.info{
    width: 30vw;
}
h1{
    font-size: 200%
}
</style>
