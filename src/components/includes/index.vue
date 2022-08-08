<template>
  

  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="style.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.9.1/font/bootstrap-icons.css">
    <title>Hello, world!</title>
  </head>
  <body>
    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: Bootstrap Bundle with Popper -->
    
    

    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light fixed-top">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">Navbar</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNavDropdown">
            <ul class="navbar-nav ms-auto">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#">HOME</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">ABOUT</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">PROJECTS</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">CONTACT</a>
              </li>
            </ul>
          </div>
        </div>
      </nav>

      <!-- introduction -->
      <section id="intro" class="d-flex align-items-center">
        <div class="container" data-aos="zoom-out" data-aos-delay="100">
          <div class="row">
            <div class="col">
              <h1> Hey, I am Maruf Ibne Hossain</h1>
              <div class="content1"><p class="content">A Frontend focused Web Developer building the Frontend of Websites and Web Applications that leads to the success of the overall product</p></div>
              <div class="btn1"><a href="#about" class="btn2 btn-get-started scrollto">PROJECTS</a></div>
            </div>
          </div>
        </div>
        <div class="social">
            <a href="https://twitter.com/marufibnhossain"><i class="bi bi-twitter"></i></a>
            <a href="https://www.facebook.com/marufibnehossain"><i class="bi bi-facebook"></i></a>
            <a href="https://github.com/marufibnehossain"><i class="bi bi-github"></i></a>
            <a href="https://www.linkedin.com/in/marufibnhossain"><i class="bi bi-linkedin"></i></a>
        </div>
        <div class="mouse-cont"><div class="mouse"><div class="dot"></div></div></div>
    
      </section>


      <!-- about us -->
      <!-- about us -->
      <section id="about" class="aboutme mt-5 mb-5 py-3">
        <div class="container mt-5">
          <div class="section-title">
            <h2 class="sec-title text-center text-uppercase text text-dark"><span>about</span></h2>
            <p class="text-center">Here you will find more information about me, what I do, and my current skills mostly in terms of programming and technology</p>
          </div>
          <div class="row">
            <div class="col-xl-6">
              <h3 class="title p-3">Get to know me!</h3>
              <div class="about-details">
                <p class="top-50 pe-3">
                  I'm a <strong>Frontend Web Developer</strong> building the
                  Front-end of Websites and Web Applications that leads to the
                  success of the overall product. Check out some of my work in the
                  <strong>Projects</strong> section.
                </p>
                <p class="top-50 pe-3">
                  I also like sharing content related to the stuff that I have
                  learned over the years in <strong>Web Development</strong> so it
                  can help other people of the Dev Community. Feel free to Connect
                  or Follow me on my
                  <a rel="noreferrer" href="https://www.linkedin.com/in/marufibnhossain" target="_blank">Linkedin</a>
                  where I post useful content related to Web Development and
                  Programming
                </p>
                <p class="top-50 pe-3">
                  I'm open to <strong>Job</strong> opportunities where I can
                  contribute, learn and grow. If you have a good opportunity that
                  matches my skills and experience then don't hesitate to
                  <strong>contact</strong> me.
                </p>
              </div>
              <a href="./#contact" class="btn3 ps-3 pe-3 mt-3">Contact</a>
            </div>
            <div class="col-xl-6">
              <h3 class="title p-3">My Skills</h3>
              <div class="skills p-3">
                <div class="skills_skill">HTML</div>
                <div class="skills_skill">CSS</div>
                <div class="skills_skill">JavaScript</div>
                <div class="skills_skill">vue.js</div>
                <div class="skills_skill">Python</div>
                <div class="skills_skill">GIT</div>
                <div class="skills_skill">Github</div>
                <div class="skills_skill">Responsive Design</div>
                <div class="skills_skill">SQL Basics</div>
              </div>
            </div>
          </div>
        </div>
      </section>


      <section class="works mt-5 mb-5 py-3" id="works">
        <div class="container">
            <div class="section-title mt-5">
                <h2 class="sec-title text-center text-uppercase text text-dark"><span>Projects</span></h2>
                <p class="text-center">Here you will find some of the personal and clients projects that I created with each project containing its own case study</p>
            </div>
            <div class="row mt-5">
                <div class="col-7">
                    <img class="img ms-5" src="./images/Myproject-2.png" alt="">
                </div>
                <div class="col-5">
                    <h2 class="mt-5 mb-3 ms-3">Voyager</h2>
                    <p class="mt-3 mb-3 ms-3">I re-created the frontend of Airbnb official web app because I got attracted to their beautiful UI. It was a great experience for me to build the entire frontend.</p>
                    <a href="" class="btn3 ps-2 pe-2 mt-3 ms-3">Case Study</a>
                </div>
            </div>
            <div class="row mt-5">
                <div class="col-7">
                    <img class="img ms-5" src="./images/Myproject-3.png" alt="">
                </div>
                <div class="col-5">
                    <h2 class="mt-5 mb-3 ms-3">Flicks</h2>
                    <p class="mt-3 mb-3 ms-3">Yubter is a platform that I created where people can join and watch their favorite movies.</p>
                    <a href="" class="btn3 ps-2 pe-2 mt-3 ms-3">Case Study</a>
                </div>
            </div>
        </div>
      </section>


      <section class="contact mt-5 mb-5 py-5" id="contact">
        <div class="container">
            <div class="section-title mt-5">
                <h2 class="sec-title text-center text-uppercase text text-dark"><span>Contact</span></h2>
                <p class="text-center">Feel free to Contact me by submitting the form below and I will get back to you as soon as possible</p>
            </div>
            <div class="form">
                <form action="">
                    <label for="Name">Name</label><br>
                    <input class="py-3 w-100 rounded-3" type="text" placeholder="Enter your Name"><br><br>
                    <label for="Email">Email</label><br>
                    <input class="py-3 w-100 rounded-3" type="text" placeholder="Email"><br><br>
                    <label for="Message">Message</label><br>
                    <input class="py-5 w-100 rounded-3" type="text" placeholder="Enter your Message"><br><br>
                    <a href="" class="btn3 px-3 mt-3">Submit</a>
                </form>
            </div>
            
        </div>
      </section>

      <footer class="foot py-5 bg-dark" id="foot">
        <div class="container py-5 bg-dark">
            <div class="row">
                <div class="my-3 text-light col-lg-8">
                    <div class="w-50">
                        <h2>Maruf Ibne Hossain</h2>
                        <p class="mt-3">A Frontend focused Web Developer building the Frontend of Websites and Web Applications that leads to the success of the overall product</p>
                    </div>
                </div>  
                <div class="col-lg-4 text-light">
                  <div class="ms-5">
                    <h2  class="mt-3">Social</h2>
                    <div class="social3"><a href="https://twitter.com/marufibnhossain"><i class="bi bi-twitter"></i></a></div>
                    <div class="social3"><a href="https://www.facebook.com/marufibnehossain"><i class="bi bi-facebook"></i></a></div>
                    <div class="social3"><a href="https://github.com/marufibnehossain"><i class="bi bi-github"></i></a></div>
                    <div class="social3"><a href="https://www.linkedin.com/in/marufibnhossain"><i class="bi bi-linkedin"></i></a></div>       
                  </div>
                </div>
            </div>                  
        </div>
      </footer>
  </body>
</template>

<script>
export default {
  name: 'indexNav',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
body {
    box-sizing: border-box;
    position: relative;
    line-height: 1.5;
    font-family: sans-serif;
    overflow-x: hidden;
    overflow-y: scroll;
    font-family: sans-serif;
}
.navbar .container-fluid{
    padding: 0rem 5rem 0rem 5rem;
}
.navbar .container-fluid a{
    padding: 1rem;
    font-weight: 700;
}
.navbar .container-fluid .collapse ul li a{
     padding: 1.3rem 2.5rem 1.3rem 2.5rem;
     font-weight: 700;
}
#intro{
    width: 100%;
  height: 100vh;
  background: url("./images/bg(2).webp") top center no-repeat;
  background-size: cover;
  position: relative;
  padding-top: 82px;
  text-align: center;
}

#intro .col h1{
    font-size: 2.5rem;
    text-transform: uppercase;
    letter-spacing: 3px;
    text-align: center;
    color: #111;
    font-weight: 500;
}
#intro .col .content1{
    margin: 3rem auto 0 auto;
    max-width: 80rem;
}
#intro .col .content{
    color: #333;
    font-size: 1.5rem;
    text-align: center;
    width: 100%;
    line-height: 1.6;
}

#intro .col .btn1 {
    margin-top: 2rem;
    text-align: center;
}
#intro .col .btn2{
    background: #facf0f;
    color: #333;
    text-transform: uppercase;
    letter-spacing: 1px;
    display: inline-block;
    font-weight: 700;
    border-radius: 5px;
    transition: transform .3s;
    padding: 0.8rem 4rem;
    font-size: 1.5rem;
    text-decoration: none;
} 
.btn2:hover {
    transform: translateY(-3px);
}

#intro .social{
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    background: #fff;
    box-shadow: rgb(100 100 111 / 20%) 0 7px 29px 0;
    padding: .5rem;
}

#intro .social a{
    width: 100%;
    display: block;
    padding: 5px;
    transition: .3s;
    border-radius: 5px;
    color: black;
}
#intro .social a:hover{
    color: rgba(1, 41, 112, 0.8);
}
#intro .social i{
    font-size: 25px;
}
.mouse-cont{
    position: absolute;
    bottom: 3%;
    left: 50%;
    transform: translateX(-50%);
}
.mouse{
    width: 25px;
    height: 40px;
    border: 2px solid #333;
    border-radius: 60px;
    position: relative;
    overflow: hidden;
}
.mouse .dot {
    width: 5px;
    height: 5px;
    position: relative;
    top: 6px;
    left: 50%;
    transform: translateX(-50%);
    background-color: #333;
    border-radius: 50%;
    opacity: 1;
    animation-name: dot;
    animation-duration: 1s;
    animation-iteration-count: infinite;
    animation-direction: normal;
}

@keyframes dot {
  0%   {background-color:#333; top:6px; opacity: 2;}
  100% {background-color:#333; top:26px; opacity: 0;}
}

.sec-title{
    display: block;
    font-size: 3rem;
    letter-spacing: 1px;
    margin-bottom: 2.5rem;
    position: relative;
    color: #111;
}
.sec-title::after{
    content: '';
    position: absolute;
    top: calc(100% + 0.5rem);
    height: 5px;
    width: 3rem;
    background: #facf0f;
    left: 50%;
    transform: translateX(-50%);
    border-radius: 5px;
}
.about-details{
    text-align: justify;
}
.btn3{
    background: #facf0f;
    color: #333;
    text-transform: uppercase;
    letter-spacing: 1px;
    display: inline-block;
    font-weight: 700;
    border-radius: 5px;
    box-shadow: 0 5px 15px 0 rgb(0 0 0 / 15%);
    transition: transform .3s;
    padding: 0.7rem 1.5rem;
    font-size: 1.2rem;
    text-decoration: none;
}
.btn3:hover {
    transform: translateY(-3px);
}

.skills{
    display: flex;
    flex-wrap: wrap;
}
.skills_skill{
    padding: 0.5rem 1rem;
    margin-bottom: 1.5rem;
    margin-right: 1.5rem;
    font-size: 1.2rem;
    background: rgba(153,153,153,.2);
    border-radius: 5px;
    font-weight: 500;
    color: #666;
}
.works .img{
    width: 40rem;
    height: auto;
}

.contact{
    width: 100%;
  height: auto;
  background: url("./images/bg(2).webp") top center no-repeat;
  background-size: cover;
  position: relative;
}
.form{
    align-items: center;
    padding: 3vw 13vw;
}
.form label{
    font-size: 1rem;
    font-family: sans-serif;
    font-weight: 700;
    padding: 10px;
}

.social3{
    position: relative;
    box-shadow: rgb(100 100 111 / 20%) 0 7px 29px 0;
    padding: 5px;
}
.social3{
    float: left;
}
.social3 a{
    width: 100%;
    display: block;
    padding: 5px;
    transition: .3s;
    border-radius: 5px;
    color: white;
}
.social3 i{
    font-size: 25px;
}

</style>

