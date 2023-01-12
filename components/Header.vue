<template>
    <div>
        <link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">

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
        </p>
    </div>
</template>

<style>
    /*@import url('https://fonts.googleapis.com/css2?family=IBM+Plex+Mono&family=IBM+Plex+Sans&display=swap');*/
    h1 {
        font-size:36px; 
        font-family: 'IBM Plex Sans', sans-serif;
    }
    @font-face {
        font-family: 'IBM Plex Mono';
        font-style: normal;
        font-weight: 400;
        src: url(http://fonts.gstatic.com/s/ibmplexmono/v15/-F63fjptAgt5VM-kVkqdyU8n1i8q131nj-o.woff2) format('woff2');
        unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
    }

    @font-face {
        font-family: 'IBM Plex Sans';
        font-style: normal;
        font-weight: 400;
        src: url(http://fonts.gstatic.com/s/ibmplexsans/v14/zYXgKVElMYYaJe8bpLHnCwDKhdHeFaxOedc.woff2) format('woff2');
        unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
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