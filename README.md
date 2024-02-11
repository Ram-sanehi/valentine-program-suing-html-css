# valentine-program-suing-html-css
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>valentine day card by raj</title>
    <style>
        #container{
            display:flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background-color: rgb(238,144,255);
        }
        .book{
            position: relative;
            border-radius: 10px;
            width: 210px;
            height: 300px;
            background-image: url();
            background-size: cover;
            background-position: center;
            background-size: 97%;
            -webkit-shadow:1px 1px 12px black;
            box-shadow: 1px 1px 12px black;
            -webkit-transform: preserve-3d;
            transform: preserve-3d;
            -webkit-perspective: 2000px;
            perspective: 2000px;
        }
        .cover{
            top:0;
            position:absolute;
            background-color: lightgray;
            background-image: linear-gradient(40deg,red);
            background-position: center;
            width: 100%;
            height:100px ;
            border-radius: 10px;
            cursor: pointer;
            -webkit-transition:all 0.5s;
            transition: all 0.5s;
            -webkit-transform-origin: 0;
            -ms-transform-origin: 0;
            transform-origin: 0;
            -webkit-box-shadow:1px 1px 12px black;
            box-shadow: 1px 1px 12px black;

        }
        .book:hover .cover{
            -webkit-transition: all 0.5s;
            transition: all 0.5s;
            -webkit-transform: rotatey(-85deg);
            -ms-transform: rotateY(-85deg);
            transform: rotatey(-95deg);
        }
        .heart{
            position: relative;
            background-color: #e60303;
            height: 60px;
            width: 60px;
            top: 180px;
            left: 75px;
            transform: rotate(-45deg);
            animation:.8s beat infinite;
        }
       

        .notes:before{
            content: "valentine's";
            top: 30px;
            color: #d04e4e;
            font-family: 'Protest Riot',sans-serif;
        }
        .notes:after{
            content:"day!";
            top: 60px;
            font-family:'Protest Riot',sans-serif ;

        }
    </style>
</head>
<body>
    <div id="container">
        <div class="book">
            <div class="cover">
                <div class="notes">Happy
                </div>
                <div class="heart"></div>
                <div class="smile"></div>
                <div class="eyes"></div>
            </div>
        </div>
    </div>
</body>
</html>
