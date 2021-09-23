<html><head>
    <meta charset="utf-8">
    <title>Web Portfolio</title>
    
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.8.1/css/all.css" integrity="sha384-50oBUHEmvpQ+1lW4y57PTFmhCaXp0ML5d60M1M7uH2+nqUivzIebhndOJK28anvf" crossorigin="anonymous">
</head>

<body>
    <div class="all">
        <div class="home">
            <div class="nav">
                <h1>Web Portfolio</h1>
                <div class="btns">
                    <a href="#edu"><button>Education</button></a>
                    <a href="#work"><button>Work</button></a>
                    
                </div>
                
                <div id="mySidenav" class="sidenav">
                    <a href="javascript:void(0)" class="closebtn" onclick="closeNav()">×</a>
                    <a href="#edu" onclick="closeNav()">Education</a>
                    <a href="#work" onclick="closeNav()">Work</a>
                    
                </div>
                
                <div class="io">
                    <button onclick="openNav()"><span><i class="fa fa-bars" aria-hidden="true"></i></span></button>
                </div>
            </div>
        
            <div class="text">
                <h1>Senura Iraj Perera</h1>
                <h2>Web Designer | Programmer | Graphic designer</h2>
                <br>
                <a href="https://github.com/senura-47802"><button>Github</button></a>
            </div>
        </div>
    
        <div class="about">
            <h1 style="color: darkblue;">About Me</h1>
            <div class="p">
                <p>I'm Senura Perera. I'm 12 years old and I'm a grade 8 student in Ananda College. I live in Raddolugama. I have been doing Web designing  about 3 years and I have been learning graphic desgning and Programming about 1 year.</p>
                <a href="https://github.com/senura-47802"><button><i class="fab fa-github"></i></button></a>
                <a href="https://www.youtube.com/channel/UCAnhCTtFbBqSG8x9vXb_EdA"><button><i class="fab fa-youtube"></i></button></a>
            </div>
        </div>
    
        <div class="skills">
            <h1>Skills</h1>
            <a href="https://en.wikipedia.org/wiki/HTML"><button>HTML</button></a>
            <a href="https://en.wikipedia.org/wiki/Cascading_Style_Sheets"><button>CSS</button></a>
            <a href="https://en.wikipedia.org/wiki/JavaScript"><button>Javascript</button></a>
            <a href="https://en.wikipedia.org/wiki/Python_(programming_language)"><button>Python</button></a>
            <a href="https://en.wikipedia.org/wiki/C%2B%2B"><button>C++</button></a>
            <a href="https://en.wikipedia.org/wiki/PHP"><button>PHP</button></a>
        </div>
        
        <div class="edu" id="edu">
            <h1>Education</h1>
            
            <div class="schl">
                <img src="data:image/png;base64,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" class="ac">
                <div class="content">
                    <h2>Ananda College</h2>
                    <br>
                    <p>Ananda College is a Buddhist school for Sri Lankan boys, with classes from primary to secondary, on a campus of 10 acres in Maradana, Colombo.</p>
                </div>
            </div>
        </div>
        
        <div class="work" id="work">
            <h1>Work</h1>
            <div class="works">
                <div class="work1">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQBICPHJ86kQ-y6p2-Z9K_ibEbYmVmo6Eda-w&usqp=CAU">
                    <h2>Calculator</h2>
                    <p>This is my first project to uploaded to github.</p>
                    <a href="https://github.com/senura-47802/CALCULATOR"><button>View</button></a>
                </div>
                <div class="work1">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQBICPHJ86kQ-y6p2-Z9K_ibEbYmVmo6Eda-w&usqp=CAU">
                    <h2>Full Application</h2>
                    <p>Full application with C# and SQL to company.</p>
                    <a href="https://github.com/senura-47802/APPLICATION"><button>View</button></a>
                </div>
                <div class="work1">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQBICPHJ86kQ-y6p2-Z9K_ibEbYmVmo6Eda-w&usqp=CAU">
                    <h2>Web dashboard</h2>
                    <p>Beautiful web dashboard with HTML and CSS.</p>
                    <a href="https://github.com/senura-47802/web-dashboard"><button>View</button></a>
                </div>
            </div>
        </div>
        
        <div class="copy">
            <h3>CopyRight © Senura Perera for BITS.</h3>
        </div>
    </div>
    <JS
    function openNav() {
        document.getElementById("mySidenav").style.width = "100%";
       }
  
      function closeNav() {
       document.getElementById("mySidenav").style.width = "0";
       }></JS>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Raleway:wght@200&display=swap');

body::-webkit-scrollbar {
  width: 8px;  
}
body::-webkit-scrollbar-track {
  background: rgba(0,0,0,0.8) ;
}
body::-webkit-scrollbar-thumb {
  background-color: rgba(255,255,255,0.336) ; 
  border-radius: 20px; 
}

*{
    margin: 0px;
    scroll-behavior: smooth;
}

.all{
    width: 100%px;
    min-height: 100%;
    background-image: url(Pics/all_bg.jpg);
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-position: center;
    background-size: cover;
}

.home{
    width: 100%px;
    height: 100%;
    background-image: linear-gradient(black, black), url(Pics/bg.png);
    background-size: cover;
    background-position: center;
}

.nav{
    padding: 10px;
    width: 80%;
    height: auto;
    display: flex;
    justify-content: space-between;
    margin-left: auto;
    margin-right: auto;
    border-bottom-left-radius: 10px;
    border-bottom-right-radius: 10px;
    background: rgba(255,255,255,0.2);
    box-shadow: 0 0 10px black;
    color: white;
}

.nav h1{
    font-family: 'Raleway';
}

.btns{
    align-self: center;
    display: block;
}

.btns button{
    background-color: transparent;
    border: none;
    font-family: 'Raleway';
    font-weight: bold;
    padding: 10px;
    font-size: 15px;
    border-radius: 10px;
    color: white;
    transition: .4s;
}

.btns button:hover{
    background: rgba(0,0,0,0.3);
    transition: .4s;
    cursor: pointer;
}

.text{
    position: absolute;
    top: 50%;
    left: 50%;
    -ms-transform: translate(-50%, -50%);
    transform: translate(-50%, -50%);
    text-align: center;
    text-shadow: 0 0 20px black;
    width: 85%;
    padding: 20px;
}

.text h1{
    font-family: 'Raleway';
    font-size: 60px;
    color: white;
}

.text h2{
    font-family: 'Raleway';
    color: white;
}

.text button{
    background: transparent;
    border: none;
    font-family: 'Raleway';
    font-weight: bold;
    padding: 10px;
    font-size: 15px;
    border-radius: 10px; 
    font-size: 20px;
    color: white;
    border: 1px solid white;
    transition: .4s;
}

.text button:hover{
    background: rgba(255,255,255,0.2);
    box-shadow:0 10px 20px rgba(0,0,0,0.19),0 6px 6px rgba(0,0,0,0.23);
    transition: .4s;
    cursor: pointer;
}

.about{
    padding-top: 50px;
    padding-bottom: 50px;
    padding-left: 20px;
    padding-right: 20px;
    width: 100%px;
    height: auto;
    display: flex;
    justify-content: center;
    color: black;
    background: gray;
    flex-wrap: wrap;
}

.about h1{
    font-family: 'Raleway';
    align-self: center;
    font-size: 50px;
}

.p{
    margin: 10px;
}

.p p{
    max-width: 400px;
    font-family: 'Raleway';
    font-weight: bold;
    font-size: 15px;
}

.p button{
    background: rgba(0,0,0,0.2);
    border: none;
    font-family: 'Raleway';
    padding: 5;
    margin-top: 10px;
    border-radius: 10px; 
    font-size: 20px;
    color: white;
    border: 1px solid white;
    transition: .4s;
}

.p button:hover{
    background: rgba(0,0,0,0.4);
    box-shadow: 0 10px 20px rgba(0,0,0,0.19),0 6px 6px rgba(0,0,0,0.23);
    transition: .4s;
    cursor: pointer;
}

.skills{
    padding-top: 50px;
    padding-bottom: 50px;
    padding-left: 20px;
    padding-right: 20px;
    width: 100%px;
    height: auto;
    color: purple;
    text-align: center;
    background-color: lightblue;
}

.skills h1{
    font-family: 'Raleway';
    align-self: center;
    font-size: 50px;
}

.skills button{
    background-color: darkolivegreen;
    background-color: aqua;
    border: none;
    font-family: 'Raleway';
    font-weight: bold;
    padding: 10px;
    font-size: 15px;
    border-radius: 10px; 
    font-size: 20px;
    color: red;
    margin-top: 5px;
    transition: .4s;
    border: 1px solid red;
}

.skills button:hover{
    background: rgba(255,255,255,0.2);
    box-shadow:0 10px 20px rgba(0,0,0,0.19),0 6px 6px rgba(0,0,0,0.23);
    transition: .4s;
    cursor: pointer;
}

.edu{
    padding-top: 50px;
    padding-bottom: 50px;
    padding-left: 20px;
    padding-right: 20px;
    width: 100%px;
    height: auto;
    color: white;
    background:pink;
}

.edu h1{
    font-family: 'Raleway';
    text-align: center;
    font-size: 50px;
    color: darkred;
}

.schl{
    padding: 20px;
    background: black;
    border-radius: 10px;
    margin: 10px;
    max-width: 700px;
    margin-left: auto;
    margin-right: auto;
    display: flex;
    transition: transform .3s;
    text-align: center;
    justify-content: center;
    flex-wrap: wrap;
}

.sc{
    width: 250px;
    height: auto;
}

.ac{
    width: 200px;
    height: auto;
}

.content{
    margin: 10px;
    font-family: 'Raleway';
    align-self: center;
}

.content h2{
    font-size: 30px;
}

.content p{
    max-width: 400px;
    font-weight: bold;
    font-size: 15px;
}

.schl:hover{
    transform: scale(1.02);
    background: rgba(0,0,0,0.8);
}

.work{
    padding-top: 50px;
    padding-bottom: 50px;
    padding-left: 20px;
    padding-right: 20px;
    width: 100%px;
    height: auto;
    color: darkblue;
    background-color: brown;
}

.work h1{
    font-family: 'Raleway';
    text-align: center;
    font-size: 50px;
}

.works{
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
}

.work1{
    padding: 10px;
    margin: 8px;
    background: rgba(255,255,255,0.1);
    width: 250px;
    border-radius: 10px;
    height: auto;
    font-family: 'Raleway';
    text-align: center;
    transition: transform .5s;
}

.work1:hover{
    transform: scale(1.04);
}

.work1 img{
    width: 250px;
    border-radius: 10px;
}

.work1 h2{
    margin-top: 10px;
    font-size: 25px;
}

.work1 p{
    font-weight: bold;
    font-size: 15px;
    margin-top: 5px;
}

.work1 button{
    background: rgba(0,0,0,0.2);
    border: none;
    font-family: 'Raleway';
    font-weight: bold;
    padding: 5px;
    font-size: 15px;
    border-radius: 10px; 
    font-size: 20px;
    color: white;
    margin-top: 10px;
    width: 100%;
    transition: .4s;
    border: 1px solid white;
}

.work1 button:hover{
    background: rgba(255,255,255,0.1);
    box-shadow:0 10px 20px rgba(0,0,0,0.19),0 6px 6px rgba(0,0,0,0.23);
    transition: .4s;
    cursor: pointer;
}



.copy{
    padding: 20px;
    background: rgba(0,0,0,0.7);
}

.copy h3{
    font-family: 'Raleway';
    text-align: center;
    color: white;
}

.sidenav{
    display: none;
}

.io{
    display: none;
}

@media only screen and (max-width: 685px) {
    .nav h1{
        align-self: center;
    }
    
    .io button{
        padding: 10px;
        background-color: transparent;
        border: 1px solid grey;
        border-radius: 5px;
        color: white;
        font-size: 20px;
    }
    
    .io{
        display: block;
    }
    
    .sidenav {
       height: 100%;
       width: 0; 
       position: fixed; 
       z-index: 1;
       top: 0; 
       left: 0;
       background: #1d1d1d; 
       overflow-x: hidden; 
       padding-top: 60px; 
       transition: 0.5s; 
       display: block;
    }

   .sidenav a {
       text-decoration: none;
       font-family: 'Raleway';
       color: white;
       font-weight: 700;
       transition: 0.5s;
       display: block;
       font-size: 20px;
       text-align: center;
       padding-top: 16px;
       padding-bottom: 32px;
    }

   .sidenav a:hover {
       color:royalblue;
       transition: 0.5s;
    }
    
   .sidenav .closebtn {
       position: absolute;
       top: 0;
       right: 25px;
       font-size: 36px;
       margin-left: 50px;
    }
    
    .btns{
        display: none;
    }
    
    .about{
        text-align: center;
    }
}

    </style>

</body></html>
