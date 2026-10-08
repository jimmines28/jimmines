<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-9ndCyUaIbzAi2FUVXJi0CjmCapSmO7SnpJef0486qhLnuZ2cdeRhO02iuK6FUUVM" crossorigin="anonymous">
    <link rel="stylesheet" href="style.css">
</head>
<body>
<div id="content">
    <!-- navigation bar --> 
    <header class="p-2 text-bg-dark fixed-top" role="navigation">
        
            <div class="d-flex flex-wrap align-items-center justify-content-center justify-content-lg-start"> 
                  <a href="#index.html" class="d-flex align-items-center mb-2 mb-lg-0 text-white text-decoration-none"> 
                <img src="./images/JIM.png" alt="Logo" width="40" height="32" class="me-2">
                  </a>
                    <ul class="nav col-auto col-lg-auto me-lg-auto mb-2 justify-content-center mb-md-0"> 
                        <li><a href="#index.html" class="nav-link px-2 text-secondary">Home</a></li> 
                        <li><a href="#about.html" class="nav-link px-2 text-white">About</a></li> 
                        <li><a href="#features.html" class="nav-link px-2 text-white">Features</a></li> 
                        <li><a href="#contact.html" class="nav-link px-2 text-white">Contact</a></li>
                    </ul>
            </div> 
       
    </header>

                <!-- hero section --> 
    <main class="p-5 text-center" id="index.html"> 
        <div class="px-4 pt-5 my-5 text-center border-bottom"> 
            <span id="j">J</span><span id="i">I</span><span id="m">M</span>
            <div class="col-lg-6 mx-auto"> 
                <p class="lead mb-4 swap">
                    <span id="orig" class="original">I am a web developer, passionate about creating responsive and user-friendly websites..</span>
                    <span id="rep" class="replacement">I want to develop more websites.</span>
                </p> 
                <div class="d-grid gap-2 d-sm-flex justify-content-sm-center mb-5"> 
                    <button type="button" class="btn btn-primary btn-lg px-4 me-sm-3">My Projects</button> 
                    <button type="button" class="btn btn-outline-secondary btn-lg px-4">Get A Quote</button> 
                </div> 
            </div> 
            <div class="overflow-hidden" style="max-height: 80vh;"> 
                <div class="container px-5"> 
                    <img src="./images/16fab612-33d3-47ab-be89-edaf36108ccf.jpg" class="img-fluid border rounded-5 shadow-lg mb-4" alt="Example image" width="700" height="1000" loading="lazy"> 
                </div> 
            </div> 
        </div>
    </main>

    <about class="p-5 text-center" id="about.html"> 
        <div class="px-4 pt-5 my-5 text-center border-bottom"> 
            <h1 class="display-4 fw-bold">About Me</h1> 
            <div class="col-lg-6 mx-auto"> 
                <p class="lead mb-4">I am a web developer with a passion for creating responsive and user-friendly websites. I have experience in HTML, CSS, JavaScript, and various web development frameworks. My goal is to deliver high-quality web solutions that meet the needs of clients and users.</p> 
            </div> 
        </div>
    </about>
    <section class="p-5 text-center" id="features.html"> 
        <div class="px-4 pt-5 my-5 text-center border-bottom"> 
            <h1 class="display-4 fw-bold">My Projects</h1> 
            <div class="col-lg-6 mx-auto"> 
                <p class="lead mb-4">Here are some of the projects I have worked on. Each project showcases my skills in web development and design.</p> 
            </div> 
        </div>
    </section>
    <section class="p-5 text-center" id="contact.html"> 
        <div class="px-4 pt-5 my-5 text-center border-bottom"> 
            <h1 class="display-4 fw-bold">Contact Me</h1> 
            <div class="col-lg-6 mx-auto"> 
                <p class="lead mb-4">If you would like to get in touch with me for any inquiries or collaborations, please feel free to reach out through the contact form below.</p> 
            </div> 
        </div>
        <footer class="py-1 my-1 text-bg-dark"> 
            <ul class="nav justify-content-center border-bottom pb-3 mb-3"> 
                 <li><a href="#index.html" class="nav-link px-2 text-secondary">Home</a></li> 
                        <li><a href="#about.html" class="nav-link px-2 text-white">About</a></li>
                        <li><a href="#features.html" class="nav-link px-2 text-white">Features</a></li>
                        <li><a href="#contact.html" class="nav-link px-2 text-white">Contact</a></li>
                </ul> 
                <p class="text-center text-body-light">© 2025 Company, Inc</p> 
            </footer>
</body>
</html>
