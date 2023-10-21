this is a simple html css project
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio website</title>
</head>
<nav class="navbar">
    <div class="max-width">
 <div class="logo"><a href="#" class="logo">Mold<span>ays</span></a></div>
 <ul class="menu">
    <li><a href="#">Home</a></li>
   <li><a href="#">About me</a></li>
    <li><a href="#">Services</a></li>
    <li><a href="#">My Skills</a></li>
 </ul>
 <div class="menu-btn">=</div>
    </div>
 </nav>
<section class="home">
    <div class="home-content">
        <h3>Get ready to start work</h3>
        <h1>I ` m Developer<br />
            Molday Fidel</h1>
        <p>I ` m a frontend- developer with an experience in open source programming</p>
        <button class="btn">LEARN MORE</button>    
    </div>
</section>
<section class="about" id = "about">
    <div class="max-width">
        <h2 class="title">About me</h2>
        <div class="about-content">
            <div class="column left">
                <img src="" alt="">
            </div>
            <div class="column right">
                <div class="text">
                    I am a UI/UX Designer and Frontend website developer</div>
                    <p>Hire me in your next project</p>
                    <a href="#">Hire Me</a>
                </div>
            </div>
        </div>
    </div>
</section>
       <section class="Services" id="services">
        <div class="max-width">
            <h2 class="title">My Services</h2>
            <div class="ser-content">
                <div class="card">
                    <div class="box">
                        <div class="text">Web Design</div>
                        <p>Am both a front-end and a back-end developer</p>
                    </div>
                </div>
                <div class="card">
                    <div class="box">
                        <div class="text">Advertising</div>
                        <p>I do business advertisement through adds and other advertising websites</p>
                    </div>
                </div>
                <div class="card">
                    <div class="box">
                        <div class="text">App Design</div>
                        <p>Am an experienced android and website app designer</p>
                    </div>
                </div>
            </div>
        </div>
       </section>
          <section class="skills" id="skills">
            <div class="max-width">
                <h2 class="title">My Skills</h2>
                <div class="skills-content">
                    <div class="column-left">
                        <div class="text">My creative skills & experiences</div>
                        <p>Welcome to my skills in terms of programming languages</p>
                        <a href="#">Read more</a>
                    </div>
                    <div class="column-right">
                        <div class="bars">
                            <div class="info">
                                <span>HTML</span>
                                <span>90%</span>
                            </div>
                            <div class="line html"></div>
                        </div>
                        <div class="bar">
                            <div class="info">
                                <span>CSS</span>
                                <span>70%</span>
                            </div>
                            <div class="line css"></div>
                        </div>
                        <div class="bars">
                            <div class="info">
                                <span>JavaScript</span>
                                <span>75%</span>
                            </div>
                            <div class="line js"></div>
                        </div>
                        <div class="bars">
                            <div class="info">
                                <span>PHP</span>
                                <span>50%</span>
                            </div>
                            <div class="line php"></div>
                        </div>
                        <div class="bars">
                            <div class="info">
                                <span>MySQL</span>
                                <span>70%</span>
                            </div>
                            <div class="line mysql"></div>
                        </div>
                    </div>
                </div>
            </div>
          </section>
          <footer>
            <span>Created By: MOLDAY OUMA FIDEL</span>
            <span>2023 All rights reserved.</span>
          </footer>
          <style>
            * {
                margin: 0;
                padding: 0;
                box-sizing: border-box;
                text-decoration: none;
            }
            html{
                scroll-behavior: smooth;
            }
            ::-webkit-scrollbar{
                width: 10px;
            }
            ::-webkit-scrollbar-track{
                background: #f1f1f1;
            }
            ::-webkit-scrollbar-thumb{
                background: #888;
            }
            ::-webkit-scrollbar-thumb:hover{
                background: #555;
            }
            section{
                padding: 100px 0;
            }
            .max-width{
                max-width: 1300px;
                padding: 0 80px;
                margin: auto;
            }
            .about,.services,.skills,footer{
                font-family: 'poppins', sans-serif;
            }
            .about .about-content,
            .services .serv-content,
            .skills .skills-content{
                display: flex;
                flex-wrap: wrap;
                align-items: center;
                justify-content: space-between;
            }
            section .title{
                position: relative;
                text-align: center;
                font-size: 40px;
                font-weight: 500;
                margin-bottom: 60px;
                padding-bottom: 20px;
                font-family: 'Ubuntu',sans-serif;
            }
            section .title ::before{
                content: "";
                position: absolute;
                bottom: 0px;
                left: 50%;
                width: 180px;
                height: 3px;
                background: #111;
                transform: translateX(-50%);
            }
            section .title::after{
                 position: absolute;
                 bottom: -8px;
                 left: 50%;
                 font-size: 20px;
                 color: crimson;
                 padding: 0 5px ;
                 background: #fff;
                 transform: translateX(-50%);
            }
            .navbar{
                position: fixed;
                width: 100%;
                z-index: 999;
                padding: 30px 0;
                font-family: 'Ubuntu', sans-serif;
                transition: all 0.3s ease;
            }
            .navbar .skicky{
                padding: 15px 0;
                background: crimson;
            }
            .navbar .max-width{
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .navbar .logo a{
                color: #111;
                font-size: 35px;
                font-weight: 600;
            }
            .navbar .logo a span{
                color: crimson;
                transition: all 0.3s ease;
            }
            .navbar .menu li{
                list-style: none;
                display: inline-block;
            }
            .navbar .menu li a{
                display: block;
                color: #38ad;
                font-size: 18px;
                font-weight: 500;
                margin-left: 25px;
                transition: color 0.3s ease;
            }
            .navbar .menu li a:hover{
                color: crimson;
            }
            .navbar .skicky .menu li a:hover{
                color: #fff;
            }
            .menu-btn {
                color: #fff;
                font-size: 23px;
                cursor: pointer;
                display: none;
            }
            .scroll-up-btn {
                position: fixed;
                height: 45px;
                width: 42px;
                background: crimson;
                right: 30px;
                bottom: 10px;
                text-align: center;
                line-height: 45px;
                color: #a890fe;
                z-index: 9999;
                font-size: 30px;
                border-radius: 6px;
                transition: all 0.3s ease;
                border-bottom-width: 2px ;
                cursor: pointer;
                opacity: 0;
                pointer-events: none;
            }
            .scroll-up-btn.show {
                bottom: 30px;
                opacity: 1;
                pointer-events: auto;
            }
            .scroll-up-btn:hover{
                filter: brightness(90%);
            }
            .home{
                display: flex;
                background: #aaa;
                height: 100vh;
                color: blueviolet;
                min-height: 500px;
                background-size: cover;
                background-attachment: fixed;
                font-family: 'Ubuntu', sans-serif;
            }
            .home .max-width{
                width: 100%;
                display: flex;
            }
            .home .max-width .row{
                margin-right: 0;
            }
            .home .home-content .text-1{
                font-size: 27px;
            }
            .home.home-content .text-2{
                font-size: 75px;
                font-weight: 600;
                margin-left: -3px;
            }
            .home.home-content .text-3{
                font-size: 40px;
                margin: 5px 0;
            }
            .home.home-content .text-3 span{
                color: crimson;
                font-weight: 500;
            }
            .home.home-content a{
                display: inline-block;
                background: crimson;
                color: #fff;
                font-size: 25px;
                padding: 12px 36px;
                margin-top: 20px;
                font-weight: 400;
                border-radius: 6px;
                border: 2px solid crimson;
                transition: all 0.3s ease;
            }
            .home.home-content a:hover {
                color: crimson;
                background: none;
            }
            .about.title::after{
                content: "who i am";
            }
             .about.about-content.left{
                width: 45%;
             }
             .about.about-content.right{
                width: 55%;
             }
             .about.about-content.right.text{
                font-size: 25px;
                font-weight: 600;
                margin-bottom: 10px;
             }
             .about.about-content.right.text span{
                color: crimson;
             }
             .about.about-content.right.p{
                text-align: justify;
             }
             .about.about-content.right.a{
                display: inline-block;
                background: crimson;
                color: #fff;
                font-size: 20px;
                font-weight: 500;
                padding: 10px 30px;
                margin-top: 20px;
                border-radius: 6px;
                border: 2px solid crimson;
                transition: all 0.3s ease;
             }
             .about.about-content.right.a:hover{
                color: crimson;
                background: none;
             }
             .services{
                color: #fff;
                background: #111;
             }
             .services .title::before{
                 background: #fff;
             }
             .services .title::after{
                background: #111;
                content: "what i provide";
             }
             .services .serv-content .card{
                width: calc(33% -20px);
                background: #222;
                text-align: center;
                border-radius: 6px;
                padding: 50px 25px;
                cursor: pointer;
                transition: all 0.3s ease;
             }
             .services .serv-content .card:hover{
                background: crimson;
             }
             .services .serv-content .card .box{
                transition: all 0.3s ease;
             }
             .services .serv-content .card:hover .box{
                transform: scale(1.05);
             }
             .services .serv-content.card i{
                font-size: 50px;
                color: crimson;
                transition: color 0.3s ease;
             }
              .services .serv-content .card:hover i{
                  color: #fff;
              }
              .services.serv-content.card .text{
                font-size: 25px;
                font-weight: 500;
                margin: 10px 0 7px 0;
              }
              

          </style>
<body>
    
</body>
</html>
