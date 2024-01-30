<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aditya's Portfolio</title>
    <link rel="stylesheet" href="portfolio.css">
    <script src="https://kit.fontawesome.com/583cc4612d.js" crossorigin="anonymous"></script>
</head>
<body>
    <style>
        *{
    margin: 0;
    padding: 0;
    font-family: 'poppins',sans-serif;
    box-sizing: border-box;
}
body
{
    background-color: #080808;
    color: #fff;
}
html{
    scroll-behavior: smooth;
    transition: transform cubic-bezier(0.215, 0.610, 0.355, 1)
}
#header
{
    width: 100%;
    height: 100vh;
    background-image: url(Untitled\ design.png);
    background-size: cover;
    background-position: center;
    overflow: hidden;
    background-repeat: no-repeat;
    position: relative;
    z-index: 4;
}
.iq
{
    color: white;
}

.container
{
    padding: 10px 10%;
}
nav{
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap
}
.logo
{
    width: 140px;
}
nav h1{
    margin-right: 100px;
  
}

nav ul li 
{
    display: inline-block;
    list-style: none;
    margin: 10px 40px;
}
nav ul li a{
    text-decoration: none;
    color: #fff;
    font-size: 18px;
    position: relative;
}
nav ul li a::after{
    content: '';
    width: 0%;
    height: 3px;
    background: #ff0404;
    position: absolute;
    left: 0;
    bottom: -6px;
    transition: 0.5s;

}
nav ul li a:hover::after
{
    width: 100%;
}
.header-text{
    margin-top: 20%;
    font-size: 30px;
    z-index: 2;
}
.header-text h1{
    margin-top: 20px;
    font-size: 50px;
}
.adi
{
    color: red;
}
.yes
{
    color: red;
}
.no
{
    color: orange;
}
.noo
{
    color: rgb(32, 193, 32);
}
/* about */
 
#about
{
    padding: 80px 0;
    color: #ababab;
}
.row
{
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
}
.about-col-1{
    flex-basis: 35%;
}
.about-col-1 img
{
    border-radius: 15px;
    width: 100%;
}
.about-col-2{
    flex-basis: 60%;
}
.sub-title
{
    font-size: 60px;
    font-weight: 600;
    text-decoration: none;
    color: bisque;


}

.tab-titles
{
    display: flex;
    margin: 20px 0 40px;
}
.tab-links
{
    margin-right: 15px;
    font-size: 18px;
    font-weight: 500;
    cursor: pointer;
    position: relative;
}
.tab-links::after
{
    content: '';
    width: 0;
    height: 3px;
    background: #ff004f;
    position: absolute;
    left: 0;
    bottom: -8px;
    transition: 0.5s;
}
.tab-links.active-link::after
{
    width: 50%;
}
.tab-contents ul li{
    list-style: none;
    margin: 10px 0;

}
.tab-contents ul li span{
    color: #b54769;
    font-size: 14px;
}
.tab-contents
{
    display: none;
}
.tab-contents.active-tab
        { 
            display: block;
        }
        /* services */
#services
{
    padding: 30px 0;

}
.services-list
{
    display: grid;
    grid-template-columns: repeat(auto-fit , minmax(250px,1fr));
    grid-gap: 40px;
    margin-top: 50px;
}
.services-list div{
    background: #262626;
    padding: 40px;
    font-size: 13px;
    font-weight: 300;
    border-radius: 10px;
    transition: background 0.5s, transform 0.5s;
}
.services-list div i{
    font-size: 50px;
    margin-bottom: 30px;
}
.services-list div h2{
    font-size: 30px;
    font-weight: 500;
    margin-bottom: 15px;
}
.services-list div a{
    text-decoration: none;
    color: #fff;
    font-size: 12px;
    margin-top: 20px;
    display: inline-block;
}
.services-list div:hover{
    background: #ff004f;
    transform: translateY(-10px);
}
/* portfolio */
#portfolio
{
    padding: 50px 0;
}
.work-list
{
    display: grid;
    grid-template-columns: repeat(auto-fit , minmax(250px,1fr));
    grid-gap: 40px;
    margin-top: 50px;
}
.work
{
    border-radius: 10px;
    position: relative;
    overflow: hidden;
}
.work img
{
    width: 100%;

    border-radius: 10px;
    display: block;
    transition: transform 0.5s;
}
.layer
{
    width: 100%;
    height: 0;
    background: linear-gradient(rgba(0,0,0,0.6),#ff004f);
    border-radius: 10px;
    position: absolute;
    left: 0;
    bottom: 0;
    overflow: hidden;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    padding: 0 40px;
    text-align: center;
    font-size: 14px;
    transition: height 0.5s;
}
.layer h3{
    font-weight: 1000;
    margin-bottom: 20px;
    
}
.layer a{
    margin-top: 20px;
    color: #ff004f;
    font-size: 18px;
    line-height: 60px;
    background: white;
    width: 60px;
    height: 60px;
    border-radius: 50%;
    text-align: center;
    text-decoration: none;
}
.work:hover img{
    transform: scale(1.1);
}
.work:hover .layer{
    height: 100%;
}
.btn 
{
display: block;
margin: 50px auto;
width: fit-content;
border: 1px solid #ff004f;
padding: 14px 50px;
border-radius: 6px;
text-decoration: none;
color: #fff;
transition: background 0.5s;
}
.btn:hover{
    background: #ff0404;
}
/* contact */
.contact-left
{
    flex-basis: 35%;
}
.contact-right
{
    flex-basis: 60%;
}
.contact-left p{
    margin-top: 30px;
    

}
.contact-left p i{
    color: #ff004f;
    margin-right: 15px;
    font-size: 25px;
    
}
.social-icons
{
    margin-top: 30px;
}
.social-icons a{
    text-decoration: none;
    font-size: 30px;
    margin-right: 15px;
    color: #ababab;
    display: inline-block;
    transition: transform 1s;
}
.social-icons a:hover{
    color: #ff004f;
    transform: rotate(360deg);
}
.btn.btn2
{
    display: inline-block;
    background: #ff004f;
}
.contact-right form{
    width: 100%;
}
form input , form textarea{
    width: 100%;
    border: 0;
    outline: none;
    background: #262626;
    padding: 15px;
    margin: 15px 0;
    color: #fff;
    font-size: 18px;
    border-radius: 6px;
}
form .btn2{
    padding: 14px 60px;
    font-size: 18px;
    margin-top: 20px;
    cursor: pointer;
}
.copyright
{
    width: 100%;
    text-align: center;
    padding: 25px 0;
    background: #262626;
    font-weight: 500;
    margin-top: 20px;
}
.copyright i{
    color: #ff0404;
}
nav .fas{
    display: none;
}
/* css for small screen */
@media only screen and (max-width: 320px){
    #header
    {
        background-image: url(new.png);
    }
    .header-text
    {
        margin-top: 100%;
        font-size: 16px;
    }
    .header-text h1{
        font-size: 30px;
    }
    nav .fas{
        display: block;
        font-size: 25px;
    }
    nav ul{
        background: #ff0404;
        position: fixed;
        top: 0;
        right: -200px;
        width: 200px;
        height: 100vh;
        padding-top: 50px;
        z-index: 2;
        transition: right 0.5s;
    }
    nav ul li{
        display: block;
        margin: 25px;
    }
    nav ul .fas{
        position: absolute;
        top: 25px;
        left: 25px;
        cursor: pointer;

    }
    .header-text h1{
        margin-top: 10px;
        font-size: 50px;
        box-sizing: content-box;
        border: 10px solid #ababab;
        background-color: rgba(0,0,0,0.6);
        opacity: 10;
    }
    .header-text{
        margin-top: 70px;
        font-size: 30px;
       
    }
    .sub-title {
        font-size: 40px;
    }
    .about-col-1 , .about-col-2{
        flex-basis: 100%;
    }
    .about-col-1
    {
        margin-bottom: 30px;
    }
    .about-col-2{
        font-size: 14px;
    }
    .tab-links{
        font-size: 16px;
        margin-right: 20px;
    }
    .contact-left , .contact-right{
        flex-basis: 100%;
    }
    .copyright{
        font-size: 14px;
    }
}
#msg{
    color: #61b752;
    margin-top: -40px;
    display: block;
    font-style: italic;
  
}
    </style>
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
                    <img src="new.png">
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
                    <img src="work-1.png">
                    <div class="layer">
                        <h3>BudgetBuddy Website</h3>
                        <p>It helps you to manage your budget efficiently and keep a real time record of 
                            your budget and it also provides a function of collabrative budgeting
                        </p>
                        <a href="#"><i class="fa-solid fa-up-right-from-square"></i></a>

                    </div>
                </div>
                <div class="work">
                    <img src="work-2.png">
                    <div class="layer">
                        <h3>Music app</h3>
                        <p>The app provides you with all the trendy music and pre made playlists and you can listen 
                            music online also by diwnloading it and keep it in list
                        </p>
                        <a href="#"><i class="fa-solid fa-up-right-from-square"></i></a>
                        </div>
                </div>
                <div class="work">
                    <img src="work-3.png">
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
