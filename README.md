<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aditya's Portfolio</title>
    <link rel="stylesheet" href="portfolio.css">
    <script src="https://kit.fontawesome.com/583cc4612d.js" crossorigin="anonymous"></script>
</head>
<body>
    <div id="header"> 
        <div class="container">
            <nav>
                
                <h1><span class="adi">ADITYA'S</span><span class="adii"> PORTFOLIO</span></h1>
                <ul id="sidemenu">
                    
                    <li><a href="#header">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#portfolio">Portfolio</a></li>
                    <li><a href="#contact">Contact</a></li>
                    <i class="fas fa-times" onclick = "closemenu()"></i>
                </ul>
                <i class="fas fa-bars" onclick = "openmenu()"></i>

            </nav>
            <div class="header-text">
                <p> FULL STACK WEB DEVELOPER</p>
                <H1>Hi, I am<span class="yes"> Aditya</span> Gupta<br> From <span class="no"> In</span>d<span class="noo">ia</span></H1>
            </div>
        </div>
    </div>
    <!-- about section -->
    <div id="about">
        <div class="container">
            <div class="row">
                <div class="about-col-1">
                    <img src="images/new.png">
                    </div>
                    <div class="about-col-2">
                        <h1 class="sub-title">About Me</h1>
                        <p>Aditya Gupta is a skilled and innovative web developer who brings 
                            creativity and technical expertise to every project he undertakes. 
                            With a passion for coding and a keen eye for design, Aditya excels
                             in developing dynamic and user-friendly websites. His proficiency 
                            in various programming languages and frameworks allows him to create
                             seamless and responsive web applications. Aditya is dedicated to staying
                              updated on the latest industry trends and technologies, ensuring that his
                               work reflects the cutting edge of web development. Whether it's building 
                               a robust e-commerce platform or crafting an engaging portfolio site, 
                               Aditya Gupta is committed to delivering high-quality and visually appealing
                                web solutions tailored to meet the unique needs of his clients.</p>
                                <div class="tab-titles">
                                    <p class="tab-links active-link" onclick="opentab('skills')">Skills</p>
                                    <p class="tab-links" onclick="opentab('experience')">Experience</p>
                                    <p class="tab-links" onclick="opentab('education')">Education</p>

                                </div>
                                <div class="tab-contents active-tab" id="skills" >
                                    <ul>
                                        <li><Span>HTML/CSS</Span><BR>Designing and Structuring of websites</li>
                                            <li><Span>Node JS</Span><BR>Complete Backend of website</li>
                                                <li><Span>Mongo DB</Span><BR>Managing Databases</li>
                                    </ul>
                                </div>
                                <div class="tab-contents" id="experience">
                                    <ul>
                                        <li><Span>2023-current</Span><BR>Full stack web developer at Amazon</li>
                                            <li><Span>2020-2023</Span><BR>Backend Manager at AMdocs</li>
                                                
                                                <li><Span>2019-2020</Span><BR>Frontend Developer at Netflix </li>
                                    </ul>
                                </div>
                                <div class="tab-contents" id="education">
                                    <ul>
                                        <li><Span>Graduation(2014-2018)</Span><BR>ABES ENGINEERING COLLEGE</li>
                                            <li><Span>Intermediate(2013-14)</Span><BR>Blue Birds International School</li>
                                                <li><Span>High School(2011-12)</Span><BR>Blue Birds International School </li>
                                    </ul>
                                </div>
                    </div>
                </div>
            </div>
        </div>  
    </div>
    <!-- services -->
    <div id="services">
        <div class="container">
            <h1 class="sub-title">My Services</h1>
            <div class="services-list">
                <div>
                    <i class="fa-solid fa-code"></i>
                    <h2>WEB DEVELOPER</h2>
                    <p> I am a master in creating and enhancing websites and making them more attractive
                        reliable
                    </p>
                    <a href="#">Learn more</a>
                </div>
                <div>
                    <i class="fa-solid fa-crop-simple"></i>
                    <h2>UI/UX DESIGNER</h2>
                    <p> I am a master in creating and enhancing graphics and making them more attractive
                        reliable
                    </p>
                    <a href="#">Learn more</a>
                </div>
                <div>
                    <i class="fa-brands fa-app-store-ios"></i>
                    <h2>APP DEVELOPER</h2>
                    <p> I am a master in creating and enhancing apps and making them more attractive
                        reliable
                    </p>
                    <a href="#">Learn more</a>
                </div>
            </div>
        </div>
    </div>
    <!-- portfolio -->
    <div id="portfolio">
        <div class="container">
            <div class="sub-title">My Work</div>
            <div class="work-list">
                <div class="work">
                    <img src="images/work-1.png">
                    <div class="layer">
                        <h3>BudgetBuddy Website</h3>
                        <p>It helps you to manage your budget efficiently and keep a real time record of 
                            your budget and it also provides a function of collabrative budgeting
                        </p>
                        <a href="#"><i class="fa-solid fa-up-right-from-square"></i></a>

                    </div>
                </div>
                <div class="work">
                    <img src="images/work-2.png">
                    <div class="layer">
                        <h3>Music app</h3>
                        <p>The app provides you with all the trendy music and pre made playlists and you can listen 
                            music online also by diwnloading it and keep it in list
                        </p>
                        <a href="#"><i class="fa-solid fa-up-right-from-square"></i></a>
                        </div>
                </div>
                <div class="work">
                    <img src="images/work-3.png">
                    <div class="layer">
                        <h3>E-commerce website</h3>
                        <p>It provides you to purchase different different things online from a single platform and
                            saves your time and money also by giving offers and deals
                        </p>
                        <a href="#"><i class="fa-solid fa-up-right-from-square"></i></a>
                        </div>
                </div>
            </div>
            <a href="" class="btn">See More</a>

        </div>
    </div>
    <!-- contact -->
    <div id="contact">
        <div class="container">
            <div class="row">
                <div class="contact-left">
                    <h1 class="sub-title">Contact Me</h1>
                    <p><i class="fa-solid fa-envelope"></i>AdityaGupta99826@gmail.com</p>
                    <p><i class="fa-solid fa-phone"></i><a href="tel:+917451090313" class="phone">7451090313</a></p>
                   
                
                    <div class="social-icons">
                        <a href="https://www.facebook.com/adityaxxgupta?mibextid=ZbWKwL"><i class="fa-brands fa-square-facebook"></i></a>
                        <a href="https://www.instagram.com/adityaxguptaa?igsh=eTVqbzk0Mnh1bDZi"><i class="fa-brands fa-instagram"></i></a>
                        <a href=""><i class="fa-brands fa-square-x-twitter"></i></a>
                        <a href="https://www.linkedin.com/in/aditya-gupta-508720280?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app"><i class="fa-brands fa-linkedin"></i></a>
                    </div>
                    <a href="images/mycv.pdf" download class="btn btn2">Download CV</a>
                </div>
                <div class="contact-right">
                    <form name="submit-to-google-sheet">
                        <input type="text" name="Name" placeholder="Your Name" required>
                        <input type="text" name="E-mail" placeholder="Your E-mail" required>
                        <textarea name="Message" rows="6" placeholder="Your Message"></textarea> 
                        <button type="submit" class="btn btn2">Submit</button>                  
                    </form>
                    <span id="msg"></span>
                </div>
            </div>
        </div>
        <div class="copyright">
            <p>Copyright © Aditya Portfolio Made with <i class="fa-solid fa-heart"></i> By Aditya Gupta 
            </p>
        </div>

    </div>
    <script>
        var tablinks = document.getElementsByClassName("tab-links");
        var tabcontents = document.getElementsByClassName("tab-contents");

        function opentab(tabname){
            for(tablink of tablinks){
                tablink.classList.remove("active-link");
            }
            for(tabcontent of tabcontents){
                tabcontent.classList.remove("active-tab");
            }
            event.currentTarget.classList.add("active-link");
            document.getElementById(tabname).classList.add("active-tab");
        }
    </script>
    <script>
         var sidemeu = document.getElementById("sidemenu");
         function openmenu(){
            sidemeu.style.right = "0";
         }
         function closemenu(){
            sidemeu.style.right = "-200px";
         }
    </script>
    <script>
        const scriptURL = 'https://script.google.com/macros/s/AKfycbyJh6hGA6h4VWs9IkKAvUXnlKL2NtFxF2jCKk1KL1sDI-A8aklIlUAgDNPV7T280YQK/exec'
        const form = document.forms['submit-to-google-sheet']
        const msg = document.getElementById("msg")
      
        form.addEventListener('submit', e => {
          e.preventDefault()
          fetch(scriptURL, { method: 'POST', body: new FormData(form)})
            .then(response => {
                msg.innerHTML = "Message Sent Successfully"
                setTimeout(function(){
                    msg.innerHTML = ""
                },5000)
                form.reset()
                })
            
            .catch(error => console.error('Error!', error.message))
        })
      </script>
<script>
    document.addEventListener('scroll', function () {
        let scrollPosition = window.scrollY;
        let header = document.getElementById('header');
        header.style.backgroundPositionY = -scrollPosition * 0.5 + 'px';
    });
</script>


</body>
</html> 
