<!DOCTYPE html>
<html>
    <style>
        details {
            background-color: #777;
            color: white;
            cursor: pointer;
            padding: 25px;
            width: 100%;
            border: none;
            text-align: left;
            outline: none;
            font-size: 15px;
            max-width: 100%;
        }

        .sub {
            background-color: darkgray;
            font-size: 15px;
            color:#777;
            position:absolute;                 
            bottom:0;                         
            right:0;
            left:0;
            text-align: center;
        }

        .image {
            position: relative;
            left: 0;
            right: 0;
            /*width: 300px;
            height: 300px;*/
            background-color: black;
        }    
    </style>
    <link href="C:/HTML/styles.css" rel="stylesheet">
    <head>
        <meta name="viewport" content="width=device-width">
        <title>Totally Legit Website</title>
    </head>

    <div class="image">
    <center><IMG SRC="data:image/jpeg;base64,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"> </center>
    </div>

    <body>
        <h1>Welcome to Totally Legit Website</h1>   

        <details>
            <summary>About Us</summary>
        
            <p>
                This is a website made by an absolute genious as a way to discover the secrets of the multiverse and not at all by a 14 year old with two much time on their hands.
                <br>
                The information gathered thus far has been insurmountable in terms of value and we plan on continuing our exploration of infinite knowledge further
            </p>
        </details>

        <h1>
            Utilities:
        </h1>
        <ul>
            <li><a href="https://www.youtube.com/watch?v=lpiB2wMc49g">Hitch hikers guide to the universe</a></li>
            <p style="font-size:7px">(courtesy of contributor: Ulric Wolfgang von Schnetlage)</p>
            <li><a href="https://www.youtube.com/watch?v=GJDNkVDGM_s">Winnie the pooh<a></li>
            <li><a href="http://www.script-o-rama.com/movie_scripts/a1/bee-movie-script-transcript-seinfeld.html">Kang the conqueror<a></li>
        </ul>

        <div class="sub">
            <p>
                Copyright 2022. All rights reserved.                
            </p>
        </div>
    </body>
</html>
