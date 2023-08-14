# sujan<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sujan-Developer PortFolio</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,600;1,300&display=swap" rel="stylesheet">
    <style>
        *{
            margin: 0;
            padding: 0;
          
        }
        body{
            background-color:rgb(13, 9, 28) ;
            color: white;
            font-family: 'Poppins',sans-serif;
        }
        nav{
          display: flex; 
          justify-content:space-around;
          align-items: center; 
          height: 80px;
          background-color: rgb(26, 9, 76);
        }
        nav ul{
            display:flex;
            justify-content: center;
        }
        nav ul li{
            list-style: none ;
            margin: 0 23px;
        }
        nav ul li a{
           text-decoration: none ;
           color:white ;

        }
        nav ul li a:hover{
            color:rgb(85, 85, 131) ;
            font-size: 1.01rem;
        }
        main hr{
            border: 0;
            background: rgb(48, 48, 85);
            height: 1.2px;
            margin: 60px,80px;
        }
        .left{
            font-size: 1.5rem;
        }
        .firstSection{
            display: flex;
            justify-content: space-around;
            align-items: center;
            margin: 125px 0;
        }
        .firstSection >div{
            width: 30%;
        }
        .leftSection{
            
            font-size: 2rem;
            /* margin: 70px 0;
             */

        }
        .rightSection img{
            width: 80%;
            
        }
        .purple{
            color: rgb(170, 107, 228);
        }
        #element{
            color: rgb(170, 107, 228);
        }
        .text-gray{
            color: gray;

        }
        .secondSection{
            max-width: 80vw;
            margin: auto;
        }
        .secondSection h1{
            font-size: 1.6rem;
        }
        

    </style>
</head>
<body><a ></a>
    <header>
        <nav>
            <div class="left"> Sujan's Portfolio</div>
            <div class="right">
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Services</a></li>
                    <li><a href="#">Project</a></li>
                    <li><a href="#">contact me</a></li>
                </ul>
            </div>
        </nav>
    </header>
    <main>
        <section class="firstSection">
            <div class="leftSection">Hi! My name is <span class="purple">Sujan</span>  
                <div>and I am a passionate</div>
                <!-- Element to contain animated typing -->
                <span id="element"></span>
            </div>
            <div class="rightSection">
                <img src="bg.png" alt="" srcset="">
            </div>
        </section>
        <hr>
        <section class="secondSection">
            <span class="text-gray">What I have done so far</span>
            <h1>Work Experience</h1>
            

                </div>
                
        </section>
    </main>
    <!-- Load library from the CDN -->
  <script src="https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js"></script>
    <!-- Setup and start animation! -->
  <script>
    var typed = new Typed('#element', {
      strings: ['Web Developer.', 'Graphics designer.','Web Designer.','video Editor.'],
      typeSpeed: 50,
    });
  </script>
</body>
</body>
</html>
