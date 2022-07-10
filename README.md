<!doctype html>
<html lang="en">
  <head>

    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.3.1/dist/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
    
    
    <title>NIFA: Fine Art Classes, Hobby Classes, Art Institite Delhi, Professional BFA Course and NID</title>
    <link rel="stylesheet" href="css2/style.css">
  </head>
  <style>
    
    *{
        margin: 0px;
        padding: 0px;
    
    }
    
    /* CSS Variables */
    :root {
        --navbar-height: 50px;
    
    }
    
    /* Navigation Bar */
    #navbar {
        display: flex;
        align-items: center;
        position: relative;
    }
    
    /* Navigation Bar: Logo and Image */
    
    #logo {
        margin: 0px 2px;
    
    }
    
    #logo img {
        height: 76px;
        margin: 4px 43px 13px;
        padding: 0px 23px;
    }
    
    /* Navigation Bar: List Styling */
    #navbar ul {
        display: flex;
        /*font-family: 'Baloo Bhai 2', cursive;*/
        padding: 10px;
    }
    
    #navbar::before {
        content: "";
        background-color: white;
        position: absolute;
        height: 100%;
        width: 100%;
        z-index: -1;
        opacity: 0.8;
    }
    
    #home {
        display: flex;
        flex-direction: column;
        padding: 100px;
        justify-content: center;
        align-items: center;
    
    }
    
    #navbar ul li {
    
        /* color: white; */
        list-style: none;
        font-size: 1rem;
    }
    
    #navbar ul li a {
        color: rgb(0, 0, 0);
        display: block;
        margin: 2px;
        padding: 6px 16px;
        border-radius: 25px;
        text-decoration: none;
        margin-top: 28px;
    }
    
    #navbar ul li a:hover {
        color: white;
        /*background-color: rgb(0, 0, 0);*/
        /*background: linear-gradient(90deg, rgba(177, 30, 111, 1) 0%, rgba(74, 14, 192, 1) 100%);*/
        background-color: #ff1787;
    }
    
    /* Home Section */
    #home {
        display: flex;
        flex-direction: column;
        padding: 20px 200px;
        justify-content: center;
        align-items: center;
    
    }
    
    #home::before {
        content: "";
        position: absolute;
        background: url('../banner1.jpg'); 
        width: 80%;
        padding: 200%;
        height: 50%;
        z-index: -1;
        opacity: 0;
    
    }
    
    #home h1 {
        color: black;
        text-align: center;
        /*font-family: 'Baloo Bhai 2', cursive; */
        font-weight: bolder;
    }
    
    #home h5 {
        font-size: 1.2rem;
        text-align: center;
        font-weight: bolder;
    }
    
    #home p {
        color: rgb(0, 0, 0);
        text-align: center;
        font-size: 1.3rem;
        /*font-family: 'Baloo Bhai 2', cursive; */
    }
    
    /* Utility Classes */
    .h-primary {
    
        font-size: 3rem;
        padding: 17px;
        margin: 5rem -114px -4px;
    }
    
    .btn {
        padding: 6px 20px;
        border-radius: 25px;
        font-family: 'Quicksand', sans-serif;
        /*box-shadow: 5px 5px 20px rgb(196, 196, 196); */
        color: white;
        margin: 26px;
        margin-left: -2px;
        font-size: 1.4rem;
        border-color: white;
        background: linear-gradient(90deg, rgba(177, 30, 111, 1) 0%, rgba(74, 14, 192, 1) 100%);
    }
    
    .btn:hover {
        color: white;
        background-color: white;
        border: white;
    }
    .container-fluid {
        padding-right: 15px;
        padding-left: 15px;
        margin-right: auto;
        margin-left: auto;
    }
    .container {
        width: 1191px;
        margin: auto;
        padding: 10px -9px;
    }
    .lmore-content p{
        color: #fff !important;
        text-align: none;
        font-size: 22px;
        margin-right: -155px;
    }
    div h2{
        font-size: 40px;
        padding: 3px;
        margin-inline: 0px;
    }
    .row {
        margin-right: -15px;
        margin-left: -15px;
    }
    .lmore-content .nfothed {
        margin-top: 1rem;
    }
    
    .downapp {
        background: linear-gradient(100deg, rgba(0, 0, 0, 1), rgba(35, 31, 32, 0.6)), url('../img/banner3.jpg') no-repeat center;
        background-size: cover;
        background-attachment: fixed;
        font-family: 'Quicksand', sans-serif;
        height: 40rem;
        width: 100px 50px;
        padding: 55px 5px;
        color: #fff;
    }
    ol, ul {
        margin-top: -24px;
        margin-bottom: 9px;
    }
    a {
        background-color: transparent;
    }
    a {
        color: #337ab7;
        text-decoration: none;
    }
    a {
        color: #fff;
        text-decoration: none;
    }
    
    .carousel-inner>.item>a>img, .carousel-inner>.item>img, .img-responsive, .thumbnail a>img, .thumbnail>img {
        display: block;
        max-width: 100%;
        
        height: auto;
    }
    
    section img, .masonrysec img {
        /*width: 27%; */
        cursor: pointer;
        border-radius: 0px;
        margin-inline: 6px;
    }
    iframe[Attributes-Style] {
        border-top-width: 40px;
        border-right-width: 50px;
        border-bottom-width: 10px;
        border-left-width: 70px;
    }
    iframe {
        border-width: 2px;
        border-style: inset;
        border-top-style: inset;
        border-right-style: inset;
        border-bottom-style: inset;
        border-left-style: inset;
        border-color: initial;
        border-top-color: initial;
        border-right-color: initial;
        border-bottom-color: initial;
        border-left-color: initial;
        border-image: initial;
        border-image-source: initial;
        border-image-slice: initial;
        border-image-width: initial;
        border-image-outset: initial;
        border-image-repeat: initial;
        position: absolute;
        top: 1448px;
        margin-inline: 762px;
        width: 551px;
        height: 450px;
    }
    .embed-responsive .embed-responsive-item, .embed-responsive embed, .embed-responsive iframe, .embed-responsive object, .embed-responsive video {
        position: absolute;
        top: 0;
        bottom: 0;
        left: -761px;
        width: 100%;
        height: 100%;
        border: 0;
    }
    .embed-responsive {
        position: relative;
        display: block;
        width: 81%;
        padding: 9px;
        /* overflow: hidden; */
        margin-inline: 167px;
        top: 75px;
        border: white;
    }
    @media (min-width: 992px) {
    .col-lg-1, .col-lg-10, .col-lg-11, .col-lg-12, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-8, .col-lg-9, .col-md-1, .col-md-10, .col-md-11, .col-md-12, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-8, .col-md-9, .col-sm-1, .col-sm-10, .col-sm-11, .col-sm-12, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-xs-1, .col-xs-10, .col-xs-11, .col-xs-12, .col-xs-2, .col-xs-3, .col-xs-4, .col-xs-5, .col-xs-6, .col-xs-7, .col-xs-8, .col-xs-9 {
        position: relative;
        min-height: 4px;
        padding-right: 2rem;
        padding-left: 3px;
        box-sizing: border-box;
        width: 23;
    }
    }
    @media (min-width: 992px) {
    .col-lg-7{
        position: relative;
        min-height: 4px;
        padding-right: 100%;
        padding-left: 30px;
        box-sizing: border-box;
        float: right;
        }
    }
    
    .fa, .fab, .fad, .fal, .far, .fas {
        -moz-osx-font-smoothing: grayscale;
        -webkit-font-smoothing: antialiased;
        display: inline-block;
        font-style: normal;
        font-variant: normal;
        text-rendering: auto;
        line-height: 1;
    }
    .header-top {
        background: linear-gradient(90deg, #812868 0%, #f954a4 100%);
        background-image: linear-gradient(90deg, rgb(129, 40, 104) 0%, rgb(249, 84, 164) 100%);
        background-position-x: initial;
        background-position-y: initial;
        background-size: initial;
        background :repeat-x initial;
        background :repeat-y initial;
        background-attachment: initial;
        background-origin: initial;
        background-clip: initial;
        background-color: initial;
        color: rgb(255, 254, 254);
        padding: 2px 5px;
        width: 90rem;
    }
    /*div {
        display: block; 
    } */
    body {
        font-family: "Helvetica Neue",Helvetica,Arial,sans-serif;
        font-size: 25px;
        line-height: 1.42857143;
        color: #333;
        background-color: #fff;
    }
    /*#banner img {
        width: 86rem;
        height: 100%;
       margin-top: -75px;
    }*/
    .callbacks img {
        display: block;
        position: relative;
        z-index: 1;
        height: auto;
        width: 100% !important;
        border: 0;
    }
    img {
        vertical-align: middle;
        padding: 0px;
    }
    /*{
        -webkit-box-sizing: border-box;
        -moz-box-sizing: border-box;
        box-sizing: border-box; */
    
    article, aside, details, figcaption, figure, footer, header, hgroup, main, menu, nav, section, summary {
        display: block;
    }
    .btn-group-vertical>.btn-group:after, .btn-group-vertical>.btn-group:before, .btn-toolbar:after, .btn-toolbar:before, .clearfix:after, .clearfix:before, .container-fluid:after, .container-fluid:before, .container:after, .container:before, .dl-horizontal dd:after, .dl-horizontal dd:before, .form-horizontal .form-group:after, .form-horizontal .form-group:before, .modal-footer:after, .modal-footer:before, .modal-header:after, .modal-header:before, .nav:after, .nav:before, .navbar-collapse:after, .navbar-collapse:before, .navbar-header:after, .navbar-header:before, .navbar:after, .navbar:before, .pager:after, .pager:before, .panel-body:after, .panel-body:before, .row:after, .row:before {
        display: table;
        content: " ";
    }
    #course-program-container .left-container #head {
        width: 100%;
        text-align: center;
        display: inline-block;
        margin: -22px auto;
    }
    .pac-col4 div p {
        font-weight: 500;
    }
    p {
        margin: 0 0 10px;
    }
    p {
        font-size: 15px;
        color: #000;
        line-height: 23px;
        font-weight: normal;
        text-align: justify;
        margin: 3px 8px 2px 0px;
    }
    .pacbt {
        text-align: center;
        cursor: pointer;
        background: linear-gradient( 90deg, rgba(177, 30, 111, 1) 0%, rgba(74, 14, 192, 1) 100%) !important;
        border: 0;
        transition: 0.2s;
        color: #fff;
        font-weight: 500;
        padding: 8px 16px;
        margin-top: 2rem;
        border-radius: 30px;
        box-shadow: 0 5px 10px 0 rgb(0 0 0 / 10%);
    }
    .pac-col4 div {
        color: #000;
        padding: 45px 16px;
        text-decoration: none;
        border-bottom-left-radius: 4px;
        border-bottom-right-radius: 4px;
    }
    .pac-col4 {
        border-radius: 4px;
        background: #fff;
        box-shadow: 0 2px 19px 0 rgb(180, 180, 180);
        margin-bottom: 4rem;
        text-align: center;
    }
    .pac-col4 img {
        border-top-left-radius: 4px;
        border-top-right-radius: 4px;
      
    }
    .equal {
        display: flex;
        flex-wrap: wrap;
    }
    .equal>[class*="col-"] {
        display: flex;
        flex-direction: row;
    }
    @media (min-width: 992px) {
    .col-md-3 {
        width: 17%;
    }
    }
    @media (min-width: 992px) {
    .col-md-1, .col-md-10, .col-md-11, .col-md-12, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-8, .col-md-9 {
        float: left;
    }
    }
    
    /*:after, :before {
        -webkit-box-sizing: border-box;
        -moz-box-sizing: border-box;
        box-sizing: border-box; 
    }*/
    .nappimg img {
        width: 150px;
    } 
    #gallery-container {
        width: 100%;
        height: auto;
        position: relative;
        display: block;
       /* text-align: center; */
        padding: 50px 0;
        
    }
    #gallery-container #head {
        width: auto;
        display: inline-block;
        margin: 10px auto;
        margin-bottom: 30px;
    }
    #gallery-container #head h2 {
        display: inline-block;
        text-align: center;
        position: relative;
    }
    #head h2 {
        margin: 69px !important;
        padding: 0 !important;
        font-weight: bolder;
    }
    .h2, h2 {
        font-size: 30px;
    }
    #gallery-container .container {
        height: auto;
        width: 100% !important;
        display: inline-block;
        /* padding: 20px 0; */
    }
    .galul {
        display: flex;
        flex-wrap: wrap;
        /* margin: 2vmin; */
    }
    .galul li {
        height: 40vh;
        flex-grow: 1;
        margin: 1vmin;
        list-style: none;
    }
    .galul img {
        max-height: 100%;
        min-width: 100%;
        object-fit: cover;
        vertical-align: bottom;
        border-radius: 1vmin;
    }
    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');
    body{
        line-height: 1.5;
        /*font-family: 'Baloo Bhai 2', cursive; */
        font-size: 20px; 
    }
    *{
        margin:0;
        padding:0;
        box-sizing: border-box;
    }
    /*.container{
        max-width: 1170px;
        margin:auto; */
    
    .row{
        display: flex;
        flex-wrap: wrap;
    }
    ul{
        list-style: none;
    }
    .footer{
        /*background-color: #24262b;*/
        padding: 52px 21px;
        background: url('../img2/fotbg2.jpeg');
        margin-inline: -122px;
        background-size: cover;
    }
    .footer-col{
       width: 25%;
       padding: 0 15px;
    }
    .footer-col h4{
        font-size: 18px;
        color: #000000;
        text-transform: capitalize;
        margin-bottom: 35px;
        font-weight: 500;
        position: relative;
    }
    .footer-col h4::before{
        content: '';
        position: absolute;
        left:0;
        bottom: -10px;
        background-color: #e91e63;
        height: 2px;
        box-sizing: border-box;
        width: 50px;
    }
    .footer-col ul li:not(:last-child){
        margin-bottom: 10px;
    }
    .footer-col ul li a{
        font-size: 16px;
        text-transform: capitalize;
        color: #000000;
        text-decoration: none;
        font-weight: 300;
        color: #000000;
        display: block;
        transition: all 0.3s ease;
    }
    .footer-col ul li a:hover{
        color: #000000;
        padding-left: 8px;
    }
    .footer-col .social-links a{
        display: inline-block;
        height: 40px;
        width: 40px;
        background-color: rgba(8, 8, 8, 0.2);
        margin:0 10px 10px 0;
        text-align: center;
        line-height: 40px;
        border-radius: 50%;
        color: #000000;
        transition: all 0.5s ease;
    }
    .footer-col .social-links a:hover{
        color: #24262b;
        background-color: #000000;
    }
    
    /*responsive */
    @media(max-width: 767px){
      .footer-col{
        width: 50%;
        margin-bottom: 30px;
    }
    }
    @media(max-width: 574px){
      .footer-col{
        width: 100%;
    }
    }
  </style>
  <body>
    <nav id="navbar">
        <div id="logo">
            <img src="img/newlogo.png" alt="">

        </div>
        <ul>
            <li class="item"><a href="#">Home</a></li>
            <li class="item"><a href="#">About</a></li>
            <li class="item"><a href="#">Courses</a></li>
            <li class="item"><a href="#">Activities</a></li>
            <li class="item"><a href="#">Admission</a></li>
            <li class="item"><a href="#">Art Gallery</a></li>
            <li class="item"><a href="#">Franchise</a></li>
            <li class="item"><a href="#">Online Class</a></li>
            <li class="item"><a href="#">Video</a></li>
            <li class="item"><a href="#">Contact</a></li>
        </ul>
    </nav>
    <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
        <ol class="carousel-indicators">
          <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
          <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
          <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
        </ol>
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="img/banner1.jpg" class="d-block w-100" alt="...">
          </div>
          <div class="carousel-item">
            <img src="img/banner4.jpg" class="d-block w-100" alt="...">
          </div>
          <div class="carousel-item">
            <img src="img/banner5.jpg" class="d-block w-100" alt="...">
          </div>
        </div>
        <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="sr-only">Next</span>
        </a>
      </div>

    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.14.7/dist/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.3.1/dist/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
    
    <section id="home">
        <h1 class="h-primary">Welcome To National Institute of Fine Arts</h1>
        <p>National Institute of Fine Arts (NIFA) is a national center for education in arts, fostering the excellence
            of emerging and established artists and advancing art to create a more human world. National Institute of
            Fine Arts (NIFA) was established by MRS RENU KHERA in Delhi and NCR of Delhi on July 2005. Institute
            established another unit in Panna (M.P) which is affiliated to Raja Mansingh Music and Arts University
            (Gwalior). Its aim is to provide education and training to students on a wide spectrum of Fine Arts.</p>
        <p>National Institute of Fine Arts is a place where the creative expression of individuals is nurtured and a
            sense of community flourishes. We seek to shape the global future of arts with an emphasis on excellence
            that allows its members to reach for the highest artistic standards as individuals while recognizing that
            the Art is one of the foundations of a healthy and creative society. This is a place where national and
            international leaders in the arts gather, teach, show and perform their work. The institute prides itself on
            its openness and on creating an environment that is safe, welcoming, and built on mutual respect.</p>
        <p></p>
        <h5>National Institute of Fine Arts is a place where the creative expression of individuals is nurtured and a
            sense of community flourishes.</h5>
        <button class="btn">Read More</button>
    </section>
    <section class="container-fluid downapp">
        <div class="container">
            <div class="row onclassec">
                <div class="col-md-5">
                    <div class="lmore-content">
                        <h2>Online Classes</h2>
                        <p>Dear Students/Parents, Nifa presents its Learning App for your regular art practice in which
                            we have added many amazing features Like: Step-by-step recorded demo videos prepared by your
                            faculty members. Regular assessment of your practise through assignment section. Live class
                            section from same app. Attendance, payment invoice, art news, announcements, important
                            information and direct connect with the management team are some more features. So hurry up
                            n join now to experience personalised coaching by experts sitting at your home.</p>
                        <p>We wish u Happy Learning. Stay Safe n Healthy.</p>
                        <p><button type="button" class="btn btn-outline"
                                onclick="window.location.href='download-mobile-app.php'">Read More</button></p>


                        <p class="nfothed">Download the app</p>
                        <ul class="list-inline nappimg">
                            <li class="list-inline-item">
                                <a href="https://play.google.com/store/apps/details?id=co.thanos fljvr"><img
                                        src="img/gplay.png" class="img-responsive"></a>
                            </li>
                        </ul>
                    </div>
                </div>

                <div class="col-md-7">
                    <div class="embed-responsive embed-responsive-16by9">
                        <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/-9cJjaLXKqE?rel=0"
                            frameborder="0" allowfullscreen=""></iframe>
                    </div>

                </div>
            </div>
        </div>

    </section>
    <div id="course-program-container" class="coursec">
        <div class="container">
            <div class="left-container">
                <div id="head">
                    <h2>Our Courses</h2>
                </div>

                <div class="package-cont">
                    <div class="row equal">
                        <div class="col-md-3">
                            <div class="pac-col4">
                                <img src="img/monkey.jpg" class="img-responsive">
                                <div>
                                    <p>6 Months Diploma in Sketching &amp; Oil Painting - Regular/Part time</p>
                                    <button type="button" onclick="window.location.href='course.php?id=12'"
                                        class="pacbt">Know More</button>
                                </div>
                            </div>
                        </div>

                        <div class="col-md-3">
                            <div class="pac-col4">
                                <img src="img/paint.jpg" class="img-responsive">
                                <div>
                                    <p>1 to 3 Months Certificate Hobby Course (Regular and Weekend)</p>
                                    <button type="button" onclick="window.location.href='course.php?id=30'"
                                        class="pacbt">Know More</button>
                                </div>
                            </div>
                        </div>

                        <div class="col-md-3">
                            <div class="pac-col4">
                                <img src="img/eye.jpg" class="img-responsive">
                                <div>
                                    <p>One Year Diploma in Fine Arts-Regular/Part Time-Level-3</p>
                                    <button type="button" onclick="window.location.href='course.php?id=29'"
                                        class="pacbt">Know More</button>
                                </div>
                            </div>
                        </div>

                        <div class="col-md-3">
                            <div class="pac-col4">
                                <img src="img/orngpaint.jpg" class="img-responsive">
                                <div>
                                    <p>Two years Advance Diploma in Fine Arts - Regular/Part time</p>
                                    <button type="button" onclick="window.location.href='course.php?id=24'"
                                        class="pacbt">Know More</button>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="row equal">
                        <div class="col-md-3">
                            <div class="pac-col4">
                                <img src="img/pen.jpg" class="img-responsive">
                                <div>
                                    <p>Entrance Preparation For N.I.D</p>
                                    <button type="button" onclick="window.location.href='course.php?id=35'"
                                        class="pacbt">Know More</button>
                                </div>
                            </div>
                        </div>

                        <div class="col-md-3">
                            <div class="pac-col4">
                                <img src="img/girl.jpg" class="img-responsive">
                                <div>
                                    <p>B.F.A from UGC Recognised University</p>
                                    <button type="button" onclick="window.location.href='course.php?id=38'"
                                        class="pacbt">Know More</button>
                                </div>
                            </div>
                        </div>

                        <div class="col-md-3">
                            <div class="pac-col4">
                                <img src="img/ma.jpg" class="img-responsive">
                                <div>
                                    <p>M.A in Painting from UGC Recognised University</p>
                                    <button type="button" onclick="window.location.href='course.php?id=40'"
                                        class="pacbt">Know More</button>
                                </div>
                            </div>
                        </div>

                        <div class="col-md-3">
                            <div class="pac-col4">
                                <img src="img/entrance-prepration3.jpg" class="img-responsive">
                                <div>
                                    <p>Entrance preparation for B.F.A</p>
                                    <button type="button" onclick="window.location.href='course.php?id=16'"
                                        class="pacbt">Know More</button>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="row equal ccard-lrow">
                        <div class="col-md-3">
                            <div class="pac-col4">
                                <img src="img/kidl1.jpg" class="img-responsive">
                                <div>
                                    <p>Kids 1 year Diploma (Level-1)</p>
                                    <button type="button" onclick="window.location.href='course.php?id=39'"
                                        class="pacbt">Know More</button>
                                </div>
                            </div>
                        </div>

                        <div class="col-md-3">
                            <div class="pac-col4">
                                <img src="img/kidl2.jpg" class="img-responsive">
                                <div>
                                    <p>Kids 1 year Diploma (Level-2)</p>
                                    <button type="button" onclick="window.location.href='course.php?id=31'"
                                        class="pacbt">Know More</button>
                                </div>
                            </div>
                        </div>

                        <div class="col-md-3">
                            <div class="pac-col4">
                                <img src="img/entrance-prepration2.jpg" class="img-responsive">
                                <div>
                                    <p>Entrance Preparation for NIFT</p>
                                    <button type="button" onclick="window.location.href='course.php?id=32'"
                                        class="pacbt">Know More</button>
                                </div>
                            </div>
                        </div>

                        <div class="col-md-3">
                            <div class="pac-col4">
                                <img src="img/hccfk.jpg" class="img-responsive">
                                <div>
                                    <p>3 Months Hobby Certificate Course For Kids</p>
                                    <button type="button" onclick="window.location.href='course.php?id=36'"
                                        class="pacbt">Know More</button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="container-fluid">
                    <div id="gallery-container" class="container">
                                    <div id="head"><h2>Students Work</h2></div>
                            <div class="container">
                                <div class="row">
                                    <ul class="galul">
                                    <li class="gallery-item"><a href="img2/img1.jpg" data-fancybox="images"><img src="img2/img1.jpg"></a></li>
                                    <li class="gallery-item"><a href="img2/img2.jpg" data-fancybox="images"><img src="img2/img2.jpg"></a></li>
                                    <li class="gallery-item"><a href="img2/img3.jpg" data-fancybox="images"><img src="img2/img3.jpg"></a></li>
                                    <li class="gallery-item"><a href="img2/img4.jpg" data-fancybox="images"><img src="img2/img4.jpg"></a></li>
                                    <li class="gallery-item"><a href="img2/img5.JPG" data-fancybox="images"><img src="img2/img5.JPG"></a></li>
                                    <li class="gallery-item"><a href="img2/img6.JPG" data-fancybox="images"><img src="img2/img6.JPG"></a></li>
                                    <li class="gallery-item"><a href="img2/img7.jpg" data-fancybox="images"><img src="img2/img7.jpg"></a></li>
                                    <li class="gallery-item"><a href="img2/img8.jpg" data-fancybox="images"><img src="img2/img8.jpg"></a></li>
                                    <li class="gallery-item"><a href="img2/img9.jpg" data-fancybox="images"><img src="img2/img9.jpg"></a></li>
                                    <li class="gallery-item"><a href="img2/img10.jpg" data-fancybox="images"><img src="img2/img10.jpg"></a></li>
                                    <li class="gallery-item"><a href="img2/img11.jpg" data-fancybox="images"><img src="img2/img11.jpg"></a></li>
                                    <li class="gallery-item"><a href="img2/img12.jpg" data-fancybox="images"><img src="img2/img12.jpg"></a></li>
                                    <li class="gallery-item"><a href="img2/img13.jpg" data-fancybox="images"><img src="img2/img13.jpg"></a></li>
                                    <li class="gallery-item"><a href="img2/img14.jpeg" data-fancybox="images"><img src="img2/img14.jpeg"></a></li>
                                    <li class="gallery-item"><a href="img2/img15.jpeg" data-fancybox="images"><img src="img2/img15.jpeg"></a></li>
                                    <li class="gallery-item"><a href="img2/img16.jpeg" data-fancybox="images"><img src="img2/img16.jpeg"></a></li>
                                    <li class="gallery-item"><a href="img2/img17.jpg" data-fancybox="images"><img src="img2/img17.jpg"></a></li>
                                    <li class="gallery-item"><a href="img2/img18.jpeg" data-fancybox="images"><img src="img2/img18.jpeg"></a></li>
                                    <li class="gallery-item"><a href="img2/img19.jpg" data-fancybox="images"><img src="img2/img19.jpg"></a></li>
                                    <li class="gallery-item"><a href="img2/img20.jpeg" data-fancybox="images"><img src="img2/img20.jpeg"></a></li>
                                    <li class="gallery-item"><a href="img2/img21.jpeg" data-fancybox="images"><img src="img2/img21.jpeg"></a></li>
                                    <li class="gallery-item"><a href="img2/img22.jpg" data-fancybox="images"><img src="img2/img22.jpg"></a></li>
                                    </ul>
                                </div>
                            </div>
                    </div>
                </div>
                <footer class="footer">
                    <div class="container">
                        <div class="row">
                            <div class="footer-col">
                                <h4>Company</h4>
                                <ul>
                                    <li><a href="#">About us</a></li>
                                    <li><a href="#">Facilities</a></li>
                                    <li><a href="#">Career</a></li>
                                    <li><a href="#">Contact Us</a></li>
                                    <li><a href="#">Terms & Conditions</a></li>
                                    <li><a href="#">Refund policy</a></li>
                                </ul>
                            </div>
                            <div class="footer-col">
                                <h4>Activities</h4>
                                <ul>
                                    <li><a href="#">Art Gallery</a></li>
                                    <li><a href="#">Workshops</a></li>
                                    <li><a href="#">Outdoor Activities</a></li>
                                    <li><a href="#">Media Coverage</a></li>
                                    <li><a href="#">Art Events</a></li>
                                    <li><a href="#">Exhibition</a></li>
                                    <li><a href="#">Daily Activities</a></li>
                                </ul>
                            </div>
                            <div class="footer-col">
                                <h4>Popular Course</h4>
                                <ul>
                                    <li><a href="#">Diploma In Fine Arts</a></li>
                                    <li><a href="#">Certificate Hobby Course</a></li>
                                    <li><a href="#">Entrance Preparation</a></li>
                                    <li><a href="#">BFA</a></li>
                                    <li><a href="#">Animation Sketching</a></li>
                                    <li><a href="#">Kids Diploma</a>
                                </ul>
                            </div>
                           
                            <div class="footer-col">
                                <h4>Follow Us</h4>
                                <div class="social-links">
                                    <a href="#"><i class="fab fa-facebook-f"></i></a>
                                    <a href="#"><i class="fab fa-twitter"></i></a>
                                    <a href="#"><i class="fab fa-instagram"></i></a>
                                    <a href="#"><i class="fab fa-linkedin-in"></i></a>
                                </div>
                            </div>
                            
                </footer>            

  </body>
</html>
