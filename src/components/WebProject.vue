<template>
    <div id="home" class="container-fluid">
        <div class="row">
            <!-- NAVBAR -->
            <nav class="navbar navbar-expand-lg sticky-top p-3">
                    <div class="container-fluid mt-3">
                        <a class="navbar-brand fs-4 ms-5 " href="#home">
                            <img src="home.png" alt="logo" height="40" class="me-2">
                            <span style="font-family: monospace;">Dungog's Portfolio</span>
                        </a>
                        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                            <span class="navbar-toggler-icon"></span>
                        </button>
                        <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
                            <ul class="navbar-nav">

                                <li class="nav-item">
                                    <a class="nav-link fs-5 contact-link me-3" href="#about">About</a>
                                </li>
                            </ul>
                        </div>
                    </div>
            </nav>

            <div class="col-md-6">
                <!-- Description -->
                <div class="p-5 mt-5 description-text" style="line-height: 2.40rem;">
                    <div class="text-start mb-3">
                        <h4 class="mb-0 pt-5 mt-5">
                            <!-- NAME -->
                            <a class="text-dark fw-bold text-decoration-none" href="https://web.facebook.com/dungog.bernie15" target="_blank">Bernie Dungog</a>
                        </h4>
                        <!-- Subtitle -->
                        <p class="text-muted mb-0">Bachelor of Science in Information Technology (BSIT) Student, Majoring in Programming</p> <!-- Subtitle -->
                    </div>
                    <div>
                        <p class="mb-0 mt-5 p-5 text-start" style="font-size: 1.3rem; line-height: 1.6;">
                            I am deeply passionate about my studies in computer science at 
                            <a class="text-dark fw-bold text-decoration-none" href="https://www.facebook.com/cpcofficial2005" target="_blank">Cordova Public College</a>
                            , where I am focused on innovation and leveraging technology to drive progress. 
                            My enthusiasm extends to exploring diverse programming languages and confidently working with hardware. 
                            I thrive on collaborative endeavors that nurture creativity, constantly seeking to broaden my expertise 
                            to excel in the dynamic landscape of the tech industry.
                        </p>
                    </div>

                    <span class="contact-phrase">Contact me on this following accounts</span> <!-- Contact phrase -->
                    
                    <!-- Facebook -->
                        <div class="social-icon-wrapper zoom-in-effect">
                            <a href="https://www.facebook.com/dungog.bernie15" target="_blank">
                                <img src="facebook.png" alt="Facebook" class="social-icon">
                            </a>
                        </div>
                        <!-- Gmail -->
                        <div class="social-icon-wrapper zoom-in-effect">
                            <a href="mailto:berniedungog5@gmail.com" target="_blank">
                                <img src="gmail.png" alt="Gmail" class="social-icon">
                            </a>
                        </div>
                        <!-- Instagram -->
                        <div class="social-icon-wrapper zoom-in-effect">
                            <a href="https://www.instagram.com/unggoy142/" target="_blank">
                                <img src="instagram.png" alt="Instagram" class="social-icon">
                            </a>
                        </div>
                        <!-- Telephone -->
                        <div class="social-icon-wrapper zoom-in-effect">
                            <img src="phone-call.png" alt="Telephone" class="social-icon">
                            <span class="telephone-number fw-bold">0922-612-2408</span>
                        </div>

                </div>
            </div>

            <div class="col-md-6 p-0 ">
                <!-- Image with background color -->
                <div class="image-container position-relative">
                    <img class="image-content" src="/profile.jpg" alt="Portrait">

                    <div class="social-icon-wrapper mt-5 zoom-in-effect">
                        <a class="text-decoration-none" href="https://github.com/Beeeernie/Images" target="_blank">
                            <img src="layers.png" alt="Github" class="social-icon">
                            <span class="dont-monospace fw-bold mt-5 mt-5">My Projects</span>
                        </a>
                    </div>
                </div>
            </div>

        </div>
    </div>

    <div id="about">

        <div class="container-fluid">
            
            <div class="row p-5 mb-5">
                
                <!-- Header -->
                <div class="col-md-12 mb-3 text-center mb-5 mt-3">
                    
                    <h3 style="font-family: Arial, sans-serif; font-size: 30px; font-weight: bold; color: #333; text-transform: uppercase; letter-spacing: 1px; text-align: center; margin-bottom: 30px;">
                        About Me
                    </h3>

                </div>

                <!-- About Me -->
                <div class="col-md-6">
                    
                    <div class="card p-5 mt-3 shadow-lg" style="background-color: rgb(20, 19, 1);">
                        <div class="card-body">
                            <!-- DOT DESIGN -->
                            <img src="ellipsis.png" class="pin-icon" alt="Pin" style="position: absolute; top: 40px; left: 63px; width: 40px;">
                        
                            <!-- PORTFOLIO DESCRIPTION -->
                            <div class="about-me-text text-start mt-3 text-white">
                                <p style="font-family: monospace; line-height: 1.8; font-size: 1.4rem;">

                                    Greetings! I'm Bernie Dungog, a computer studies enthusiast living in Canjulao,Lapu-Lapu City. 
                                    My drive stems from a profound enthusiasm for technology and its endless possibilities.
                                    <br><br> 
                                    Embracing the spirit of exploration, I dive into various realms, mastering PHP, JavaScript, and 
                                    C language, while my true forte lies in hardware, particularly Arduino.
                                    <br><br>
                                    Determined to overcome challenges, I engage in collaborative ventures, delivering innovative 
                                    solutions with finesse. My adaptability ensures seamless navigation through dynamic environments, 
                                    where I eagerly seize new opportunities.
                                    <br><br> 
                                    My journey in technology has sculpted my capabilities, priming me to make impactful contributions 
                                    to any project or team. With a steadfast commitment to excellence and an eye for detail, I endeavor 
                                    to exceed expectations, crafting solutions that resonate with user needs. 
                                    <br><br>
                                    In search of reliability, innovation, and a proactive mindset? Your search ends here with Bernie Dungog!
                                
                                </p>
                            </div>
                        </div>
                    </div>
                </div>


                <!-- My Skills -->
                <div class="col-md-6 text-center">
                    <div class="container">
                        <div class="row justify-content-evenly" style="margin-top:240px;">
                            <h3 class="text-center mb-4">Services Offered</h3>
                            <div class="col-lg-4 col-md-4 text-center py-5 my-3">

                                <div class="img-container zoom-in-effect">
                                    <img src="html-5.png" width="60%" max-width="150px" title="HTML" class=" mx-auto">
                                </div>
                            </div>
                            <div class="col-lg-4 col-md-4 text-center py-5">
                                <div class="img-container zoom-in-effect">                                    
                                    <img src="css-3.png" width="60%" max-width="150px" title="CSS" class=" mx-auto">
                                </div>
                            </div>
                            <div class="col-lg-4 col-md-4 text-center py-5 my-3">
                                <div class="img-container zoom-in-effect">
                                    <img src="java-script.png" width="60%" max-width="150px" title="Javascript" class=" mx-auto">
                                </div>
                            </div>
                            <div class="col-lg-4 col-md-4 text-center py-5 my-3">
                                <div class="img-container zoom-in-effect">
                                    <img src="php.png" width="60%" max-width="150px" title="PHP" class=" mx-auto">
                                </div>
                            </div>
                            <div class="col-lg-4 col-md-4 text-center py-5 my-3">
                                <div class="img-container zoom-in-effect">
                                    <img src="motherboard.png" width="60%" max-width="150px" title="Arduino" class=" mx-auto">
                                </div>
                            </div>
                            <div class="col-lg-4 col-md-4 text-center py-5 my-3">
                                <div class="img-container zoom-in-effect">
                                    <img src="letter-c.png" width="60%" max-width="150px" title="C" class=" mx-auto">
                                </div>
                            </div>
                        </div>

                    </div>
                </div>
            </div>

        </div>

    </div>

</template>

<script>

</script>


<style>
.container-fluid {
      display: flex;
      justify-content: center;
      
    }
  
    .row {
      display: flex;
      flex-direction: row;
    }

    /* CSS for the image container */
    .image-container {
    background-color: rgb(183, 181, 179);
    padding: 200px;
    border-bottom: 3px solid black;
    }

    /* CSS for the image inside the container */
    .image-content {
    width: 90%;
    }
    
    .container {
    margin-left: 10px;
    margin-right: 10px;
    }

    .nav-link:hover {
    font-family: monospace;
    font-weight: bold;
    }

    .navbar{
        background-color: rgb(229, 231, 230);
        border-bottom: 3px solid black;
    }

    .description-text strong{
        font-family: 'Arial', sans-serif;
        font-size: 1.2rem;
        line-height: 1.6;
        font-weight: bold;
    }

    .contact-link {
    transition: all 0.3s ease;
    }

    .contact-link:hover {
        background-color: rgb(184, 12, 9); /* Bootstrap danger color */
        color: white;
        padding: 0.5rem 1rem;
        border-radius: 20px; /* Adjust the value to change the roundness */
    }
    .social-icons {
        position: absolute;
        top: 85%;
        left: 50%;
        transform: translate(-50%, -50%);
        display: flex;
        flex-direction: row;
        justify-content: center; /* Center horizontally */
        align-items: center; /* Center vertically */
        gap: 10px;
    }

    .social-icon {
        width: 40px;
        height: auto;
        margin: 15px; /* Adjust the margin as needed */
    }

    .contact-phrase {
        display: block;
        text-align: center;
        font-family: monospace;
        color: rgb(12, 12, 12);
        margin-top: 35px; /* Adjust as needed */
    }
</style>
