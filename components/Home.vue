<template>
    <div>
        <h2><i class="fas fa-record-vinyl"></i> Current Playing...</h2>
        <p>
            Learning Korean, planning Columbia University's DevFest, researching syntax
        </p>
        <h2><i class="material-icons">playlist_play</i> Experience</h2>
                <ul>
                    <div class="backgroundhover"><li>Committee member for DevFest, Columbia University's
                        spring hackathon, hosted by Application Development Initiative (ADI)</li> </div>
                    <div class="backgroundhover"><li>Founding team member at Inlet <a href="https://inlet.space">
                        (x)</a>, a multimedia collage-based moodboard making app</li></div>
                    <div class="backgroundhover"><li>Studied in Seoul, South Korea for 7 weeks through a
                        fully-funded merit scholarship from the National Language Security Initiative (NSLI-Y),
                        run by the US State Department.</li></div>
                </ul>
        <h2><i class="material-icons">playlist_play</i> Projects</h2>
            <p>
                Coming soon!
            </p>
        <h2><i class="material-icons">playlist_play</i> Writing</h2>
            <ul>
                <div class="backgroundhover">
                    <li>"Heritage Unwound," Rust + Moth <a href="https://rustandmoth.com/work/heritage-unwound/">(x)</a></li>
                </div>
                <div class="backgroundhover"><li>"Maps," Pidgeonholes <a href="http://pidgeonholes.com/2021/03/maps/">(x)</a></li></div>
                <div class="backgroundhover">
                    <li>"Time Lapse," wildness <a href="https://readwildness.com/26/chiu-time">(x)</a></li>
                </div>
                <div class="backgroundhover">
                    <li>"Supermarket Peaches," Hobart Pulp <a href="https://www.hobartpulp.com/web_features/crunchy-peaches">(x)</a></li>
                </div>
                <div class="backgroundhover">
                    <li>editor at [sub]liminal Magazine <a href="https://readsubliminal.wixsite.com/readsubliminal">(x)</a></li>
                </div>
                <div class="backgroundhover">
                    <li>editor at Dishsoap Quarterly <a href="https://dishsoapquarterly.com">(x)</a></li>
                </div>
            </ul>
        <h2><i class="material-icons">playlist_play</i> Recognition</h2>
            <ul>
                <div class="backgroundhover">
                    <li>4x National Gold Medalist @ Scholastic Art and Writing (Best Teen Writing 2020)</li>
                </div>
                <div class="backgroundhover">
                    <li>4x YoungArts Winner in Writing (2022 Finalist in Short Story, 2022 Honorable Mention in Creative Nonfiction,
                        2022 Merit Winner in Poetry, 2021 Merit Winner in Short Story)</li>
                </div>
            </ul>
    </div>
</template>

<style>
    .backgroundhover{
        margin-left: -40px;
        padding-left: 40px;
    }
    .backgroundhover:hover{
        background-color:#818a9c/*#818da8*/;
    }
    body {
        background-color:#737C91;
        color:#DED1C6;
        font-family: "IBM Plex Mono", monospace;
        font-size: 13px;
    }

    h2 {
        font-family:"IBM Plex Sans",sans-serif;
        font-size:20px;
        margin-bottom:-3px;
    }

    a, a:visited {
        color: inherit;
        text-decoration:none;
    }

    a:hover {
        color:#9bcdbb;
        text-decoration: underline;
    }
    #icons {
        font-size:30px;
        text-decoration: none;
    }

    li {
        list-style-type: decimal;
        padding-top: 3px;
        padding-bottom: 3px;
        margin-left:-8px;
    }

    li:hover{
        list-style-type:none;
    }

    li:hover:before {
        float: left;
        margin-left: -28px;
        content: "\f04b";
        font-family: "Font Awesome 5 Free";
        padding-right:10px;
    }

    i {
        vertical-align: middle;
    }

    ::selection {
        background:#84b0ab;
    }
</style>