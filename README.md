<img width="1915" height="958" alt="image" src="https://github.com/user-attachments/assets/ab3fce2e-f923-4d99-96aa-ed763f0e41ea" /># Task13

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .progress{
            background-color: red;
            height: 3px;
            animation: load 1s ease-in-out 1;
        }
        *{
            margin: 0;
            padding: 0;
        }
        header{
            height: 122px;
            background-color: black;
        }
        main{
            height: 122px;
            background-color: blue;
        }
        @keyframes load {
            0%{
                width: 0;
            }
            70%{
                width: 48vw;
            }
            100%{
                width: 100vw;
            }
        }
        @keyframes slide1 {
            0%{
                transform: translate(-8vw)
            }
            100%{
                transform: translate(-8vw)
            }
        }
          @keyframes slide2{
            0%{
                 transform: translate(0vw)
            }
            100%{
                transform: translate(92vw)
            }
        }
        /* img{
            animation: rotate 0.5s ease-in infinite;
        } */
         .slider{
            background-color: aqua;
            height: 100vh;
            width: 100vw;
            margin: auto;
            overflow: hidden;
            display:block;
            display: flex;
            justify-content: center;
         }
         .img1{
            transform: translate(-8vw);
            animation: slide1 1s forwards;
         }
         .img2{
            transform: translate(0vw);
            animation: slide2 1s forwards;
         }
         .img3{
            transform: translate(-8w);
         }
        
    </style>
</head>
<body>
    <div class="progress"></div>
    <header></header>
    <main>
        <!-- <img src="istockphoto-1159980027-612x612.jpg" alt="" height="120vh" width="120vw"> -->
        <div class="slider">
           <img class="img1" src="istockphoto-1159980027-612x612.jpg" alt="">
           <img class="img2" src="istockphoto-1159980027-612x612.jpg" alt="">
           <img class="img3" src="istockphoto-1159980027-612x612.jpg" alt="">
        </div>

    </main>
</body>
</html>
