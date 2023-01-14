<template>
    <div>
        <link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=IBM+Plex+Mono&family=IBM+Plex+Sans&display=swap" rel="stylesheet">

        <h1>Jennifer Chiu</h1>

        <h2>Hello!</h2>
        <p>
            I'm a student and storyteller at Columbia University studying computer
            science and linguistics.
        </p>

        <p>
            <i class="fa-solid fa-lightbulb"></i> Korean, Cantonese, Java, HTML, CSS, Excel, Figma, InDesign, Photoshop
        </p>

        <p>
            <i class="fa-solid fa-heart"></i> language learning, crochet, design, nostalgia, urban exploration
        </p>

        <p id="icons">
            <a href="https://github.com/jenniferrchiu" class="fa-brands fa-github"></a>
            <a href="https://www.linkedin.com/in/jennifer-chiu-a9b29122b/" class="fa-brands fa-linkedin"></a>
            <a href="https://open.spotify.com/user/gzat0l69l6uw6941u2hskrv78?si=54d06867daf241c1" class="fa-brands fa-spotify"></a>
            <a href= "mailto:jennifer.chiu@columbia.edu"><i class="fa-solid fa-envelope"></i></a>
        </p>
    </div>
</template>

<style>
    h1 {
        font-size:36px; 
        font-family: 'IBM Plex Sans', sans-serif;
    }
</style>

<script>
    export default{
        head(){
            return{
                script: [
                    {src: 'https://kit.fontawesome.com/a866f90196.js', crossorigin: 'anonymous'}
                ]
            }
        }
    }
</script>