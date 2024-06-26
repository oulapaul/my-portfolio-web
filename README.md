<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="description" content="Fidel Molday's Portfolio, which depicts his impressive repertoire of skills at a young age.">
    <meta name="keywords" content="Fidel Ouma Molday, FrontEnd Web Developer, Developer, Student Developer, Web Developer, Web Designer,  Programmer, Computer Science Student, Junior Developer, Google Developer Student Clubs Lead, Microsoft Learn Student Ambassador, Postman Student Leader, Angular, Frontend Engineer">
    <meta name="author" content="Fidel Ouma">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>oula paul Portfolio Website</title>
    <!-- Link to FontAwesome Icons online -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@5.15.4/css/fontawesome.min.css" integrity="sha384-jLKHWM3JRmfMU0A5x5AkjWkw/EYfGUAGagvnfryNV3F9VqM98XiIH7VBGVoxVSc7" crossorigin="anonymous">
    <script src="https://kit.fontawesome.com/03f6c6393a.js" crossorigin="anonymous"></script> 
    <!-- Link to AOS -->
    <link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />
    <!-- Custom CSS -->
    <link rel="stylesheet" href="style.css">
    <!-- Favicon Image -->
    <link rel="icon" type="image/x-icon" href="">
    <!-- jQuery CDN link-->
    <script src="https://code.jquery.com/jquery-3.3.1.min.js"></script>
</head>
<body>
    <div id="preloader"></div> 
    <header>
        <!-- Menu Tab and Logo at top Using HTML -->
        <a href="#" class="logo">Portfolio</a>
        <div class="toggle" onclick="toggleMenu()"></div>
        <ul class="menu">
            <li class="nav-item"><a href="#home" class="nav-link" onclick="toggleMenu()">Home</a></li>
            <li class="nav-item"><a href="#about" class="nav-link" onclick="toggleMenu()">About</a></li>
            <li class="nav-item"><a href="#services" class="nav-link" onclick="toggleMenu()">Services</a></li>
            <li class="nav-item"><a href="#work" class="nav-link" onclick="toggleMenu()">Work</a></li>
            <li class="nav-item"><a href="#testimonials" class="nav-link" onclick="toggleMenu()">Testimonials</a></li>
            <li class="nav-item"><a href="#contact" class="nav-link" onclick="toggleMenu()">Contact</a></li>
        </ul>
    </header>
    
    <main>
        <!-- Banner Layout in HTML -->
        <section class="banner" id="home">
            <div class="textBx">
                <h2><span>Hello, I'm oula paul.</span><br> <i class="auto-input"></i></h2>
                <a href="#about" class="abt btn">About Me</a>
            </div>
        </section>
        <!-- Creating About Me Layout in HTML -->
    <section class="about" id="about">
        <div class="heading">
            <p>Get to Know me</p>
            <h2>About Me</h2>
        </div>
        <div class="content">
            <div class="w50">
                <img src="https://1drv.ms/i/c/8ebae0334a0ab4af/EcNGcCxHm6BDrMg105QOLeIBS9G_9Tx3gQF1RrMTLjBWHQ?e=0wZtgB" alt="" class="proPic" data-aos="fade-up" data-aos-offset="10" data-aos-easing="ease-in-sine">
            </div>
            <div class="contentBx w50" data-aos="fade-up" data-aos-duration="1000">
                <h3>Who am i?</h3>
                <h2><b id="myName"><b>I'm oula paul<span class="auto-text"></span></h2>
                <p>
                I am a code enthusiast, love seeing my code working as intended and actually building something altogether. I sometimes listen to music to let off steam or get myself in a mood suitable for a certain activity. I am open to learning, about things and people.<br> <br>
                I am also freelancer from KENYA and i have been building noteworthy UX/UI designs and websites for months now, which comply with the latest design trends. I help convert a vision and an idea into meaningful and useful products. Having a sharp eye for product evolution helps me prioritize tasks, iterate fast and deliver faster.
                </p>
                <h2 id="hdSkills"><b>Skills</b></h2>
                <p>
                    <div id="skills">
                        <ul class="firstRow">
                            <li>HTML5 and CSS3</li>
                            <li>JavaScript</li>
                            <li>Bootstrap4</li>
                            <li>Git</li>
                            <li>C</li>
                            <li>Python</li>
                        </ul>
                        <ul class="secondRow">
                            <li>SQL</li>
                            <li>Flask</li>
                            <li>Angular</li>
                            <li>Typescript</li>
                            <li>PostgreSQL</li>
                            <li>React</li>
                        </ul>
                        <!--
                        <ul>
                            <li></li>
                            <li></li>
                            <li></li>
                            <li></li>
                            <li></li>
                        </ul> -->
                    </div>
                </p>
                <div class="heading bottom">
                    <div class="bt">
                        <b><i class="fa fa-book-reader"></i> Study:</b> University of Eldoret.<br>
                        <b><i class="fa fa-calendar"></i> Age:</b> 20 <br>
                    </div>
                    <div class="bt">
                        <b><i class="fa fa-envelope"></i> Email:</b> oulapaulinda2004@gmail.com<br>
                        <b><i class="fa fa-map-marker"></i> Location:</b> KENYA
                    </div>
                    <a href="#messageMe"><span class="btn round">Get CV</span></a>
                </div>
            </div>
        </div>
    </section>
        <!-- Creating Services Layout in HTML -->
        <section class="services" id="services">
            <div class="heading white">
                <h2>My Services</h2>
                <p>Services I offer to my clients</p>
            </div>
            <div class="content">
                <div class="servicesBx" data-aos="flip-left" data-aos-easing="linear"
                        data-aos-duration="2000">
                    <i class="fa fa-desktop fa-4x"></i>
                    <h3>Web Development</h3>
                    <p>I am skilled in developing websites, I've done some projects and I can safely say that I know my way around it.</p>
                </div>
                <div class="servicesBx" data-aos="flip-left" data-aos-easing="linear"
                        data-aos-duration="2000">
                    <i class="fa fa-lightbulb-o fa-4x"></i>
                    <h3>Creative Web Design</h3>
                    <p>I create interesting and creative website designs that have a modern feel to it, that would best suit the client.</p>
                </div>
                <div class="servicesBx" data-aos="flip-left" data-aos-easing="linear"
                        data-aos-duration="2000">
                    <i class="fa fa-css3 fa-4x"></i>
                    <h3>Responsive Web Design</h3>
                    <p>I can develop websites to fit in all screen sizes, thus having a fluid design across multiple devices.</p>
                </div>
                <div class="servicesBx" data-aos="flip-left" data-aos-easing="linear"
                        data-aos-duration="2000">
                    <i class="fa fa-picture-o fa-4x"></i>
                    <h3>Graphic Design</h3>
                    <p>Manipulating the style and look of images is among my skill set. It is quite useful especially in this field.</p>
                </div>
                <div class="servicesBx" data-aos="flip-left" data-aos-easing="linear"
                        data-aos-duration="2000">
                    <i class="fa fa-underline fa-4x"></i>
                    <h3>User Interface Design</h3>
                    <p>I create interesting and creative UI designs that have a modern feel to it, that would best suit the client.</p>
                </div>
                <div class="servicesBx" data-aos="flip-left" data-aos-easing="ease-out-cubic"
                        data-aos-duration="2000">
                    <i class="fa fa-gamepad fa-4x"></i>
                    <h3>App Development</h3>
                    <p>Also, I can create apps using the tried and tested durable coding language 'C'. </p>
                </div>
            </div>
        </section>

            <!-- Creating Work Layout in HTML -->
        <section class="work" id="work">
            <div class="heading">
                <h2>My Latest Work</h2>
                <p>Showcasing some of my <b>Projects</b> </p>
            </div>
            <div class="content">
                <div class="workBx">
                    <a href="https://bootstrap4-neon.vercel.app/" target="_blank" title="Project Fashiongram">
                        <img src="images/fashion.jfif" alt="" data-aos="fade-up" data-aos-duration="1500">
                        <p>Project Fashiongram</p>
                    </a>
                </div>
                <div class="workBx">
                    <a href="https://quiz-app-roan-rho.vercel.app/" target="_blank" title="HTML, CSS and JavaScript Quiz App">
                        <img src="images/quiz.jfif" alt="" data-aos="fade-up" data-aos-duration="1500">
                        <p>Quiz App</p>
                    </a>
                </div>
                <div class="workBx">
                    <a href="https://order-pizza-steel.vercel.app/" target="_blank" title="Order Pizza Simulation">
                        <img src="https://cdn.pixabay.com/photo/2020/05/17/04/22/pizza-5179939_960_720.jpg" alt="" data-aos="fade-up" data-aos-duration="1500">
                        <p>Order Pizza Simulation</p>
                    </a>
                </div>
                <div class="workBx">
                    <a href="https://ohms-law-calculator.vercel.app/" target="_blank" title="Ohm's Law Calculator">
                        <img src="images/multimeter.jfif" alt="" data-aos="fade-up" data-aos-duration="1500">
                        <p>Ohm's Law Calculator</p>
                    </a>
                </div>
                <div class="workBx">
                    <a href="https://survey-jet.vercel.app/" target="_blank" title="Survey Form Project">
                        <img src="images/survey.jfif" alt="" data-aos="fade-up" data-aos-duration="1500">
                        <p>My Survey Form Project</p>
                    </a>
                </div>
                <div class="workBx">
                    <a href="https://my-booklist-app-mu.vercel.app/" target="_blank" title="A book list app coded in vanilla js">
                        <img src="images/books.jpg" alt="" data-aos="fade-up" data-aos-duration="1500">
                        <p>A book list app</p>
                    </a>
                </div>
                <div class="heading">
                    <a href="https://github.com/grand-rick001" class="btn">View All My Projects</a>
                </div>
            </div>
        </section>

         <!-- Creating Testimonial Layout in HTML -->
    <section class="testimonial" id="testimonials">
        <div class="heading white">
            <h2>Testimonial</h2>
            <p>What my clients think about me</p>
        </div>
        <div class="content">
            <div class="testimonialBx" data-aos="fade-up" data-aos-duration="1000">
                <p>I have had the pleasure of mentoring Patrick in their journey as a Frontend developer specializing in Angular. Patrick has consistently impressed me with their unwavering passion for crafting exceptional user experiences. Their ability to swiftly grasp intricate concepts and translate them into elegant solutions is remarkable. Patrick's commitment to code quality, paired with their collaborative nature and effective communication skills, make them a standout developer. I wholeheartedly recommend Patrick as a dedicated and adept Frontend developer who will undoubtedly contribute positively to any project or team.</p>
                <h3>Anselemo Flavian<br>Software Engineer.</h3>
            </div>
            <div class="testimonialBx" data-aos="fade-up" data-aos-duration="1000">
                <p>His expertise in Web Development is truly impressive, and it's clear that he has a deep understanding of the field.

                    What stood out to me about Patrick is his ability to communicate complex technical concepts in a way that is easy to understand for those without a technical background. This is a rare skill that is incredibly valuable in today's tech landscape, where effective communication is essential for success.
                    
                    In addition to his technical skills,Patrick also has strong leadership qualities. He has a proven track record of leading successful projects and teams, and his ability to motivate and inspire his colleagues is second to none</p>
                <h3>Samuel Njau<br>Electronic and Computer Engineer</h3>
            </div>
        </div>
    </section>

    <!-- Creating Contact Layout in HTML -->
    <section class="contact" id="contact">
        <div class="heading white">
            <p>Feel free to contact me anytime</p>
            <h2>Get in Touch</h2>
        </div>
        <div class="content">
            <div class="contactInfo" data-aos="fade-up" data-aos-duration="1000">
                <h3>Contact Info</h3>
                <p>Always available for freelance work if the right project<br> comes along, Feel free to contact me!</p>
                <div class="contactInfoBx">
                    <div class="box">
                        <div class="icon">
                            <i class="fa fa-map-marker"></i>
                        </div>
                        <div class="text">
                            <h3>Address</h3>
                            <p>106 kadongo</p>
                        </div>
                    </div>
                    <div class="box">
                        <div class="icon">
                            <i class="fa fa-phone"></i>
                        </div>
                        <div class="text">
                            <h3>Phone no :</h3>
                            <p>0790214083</p>
                        </div>
                    </div>
                    <div class="box">
                        <div class="icon">
                            <i class="fa fa-envelope-o"></i>
                        </div>
                        <div class="text">
                            <h3>Email Address</h3>
                            <p>oulapaulinda2004@gmail.com</p>
                        </div>
                    </div>
                    <br>
                    <h3>Social Connect</h3>
                    <div class="boxSocial">
                        <div class="icon">
                            <a href="https://www.facebook.com/patrickkabuga097/" target="_blank">
                                <i class="fa fa-facebook-square"></i>
                            </a>
                        </div>
                        <div class="icon">
                            <a href="https://twitter.com/patrick_murimi_" target="_blank">
                                <i class="fa fa-twitter-square"></i>
                            </a>
                        </div>
                        <div class="icon">
                            <a href="https://www.linkedin.com/in/patrick-murimi" target="_blank">
                                <i class="fa fa-linkedin-square"></i>
                            </a>
                        </div>
                        <div class="icon">
                            <a href="https://github.com/oula junior" target="_blank">
                                <i class="fa fa-github-square"></i>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
            <div class="formBx" id="messageMe" data-aos="fade-up" data-aos-duration="1000">
                <form action="https://formspree.io/f/xyyalqol" method="post">
                    <h3>Message Me</h3>
                    <input type="text" placeholder="Full Name" name="fullName" required>
                    <input type="email" placeholder="Email" name="email" required>
                    <textarea rows="6" id="textarea" placeholder="Your Message" name="message" required></textarea>
                    <input type="submit" value="Send Message">
                </form>
            </div>
        </div>
    </section>
    </main>
    <a href="#home" class="move-top">
        <img src="images/arrow-up-icon.png" alt="move to top icon">
    </a>
    <!-- Creating Footer Layout in HTML -->
    <footer class="copyright">
        <p>&copy;2024 | oula Junior | All rights reserved.</p>
    </footer>
<script src="ext.js" language = "javascript"></script> <!--//My Customized Script-->
<script src="https://cdn.jsdelivr.net/npm/typed.js@2.0.12"></script> <!--//Auto-typing Script-->
<script src="typed.js"></script> <!--//Auto-typing Customized Script-->
<script src="https://unpkg.com/aos@next/dist/aos.js"></script> <!--//AOS Library Script-->
<script>
    // Customizing the AOS Library Script
AOS.init({
            offset: 150,
            delay: 300,
            duration: 500,
            mirror: false,
            once: true
        });

</script>
</body>
</html>
