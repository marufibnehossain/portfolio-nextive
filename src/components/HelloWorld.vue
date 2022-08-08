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
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
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
      <section id="clients" class="clients">

        <div class="container" data-aos="fade-up">
  
          <header class="section-header">
            <h2>Our Clients</h2>
            <p>Lorem ipsum dolor sit.</p>
          </header>
        </div>
  

  
      </section>
  </body>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.navbar .container-fluid{
    padding: 0rem 5rem 0rem 5rem;
}
.navbar .container-fluid a{
    padding: 1rem;
}
.navbar .container-fluid .collapse ul li a{
     padding: 1.3rem 2.5rem 1.3rem 2.5rem;
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



</style>

