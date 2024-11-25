# BagBag  
<!doctype html>
<html lang=en>
<head>
<meta charset=UTF-8>
<meta name=viewport content="width=device-width,initial-scale=1">
<title>Portfolio</title>
<link rel=stylesheet href=style.css>
<link rel=stylesheet href=https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.1/css/all.min.css integrity="sha512-5Hs3dF2AEPkpNAR7UiOHba+lRSJNeM2ECkwxUIxC1Q/FLycGTbNapWXB4tP889k5T5Ju8fs4b1P5z/iB4nMfSQ==" crossorigin=anonymous referrerpolicy=no-referrer>
<link rel=stylesheet href=responsive.css>
<link rel=stylesheet href=https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css>
</head>
<style>html{scroll-behavior:smooth}
*{margin:0;padding:0;box-sizing:border-box;font-family:'Times New Roman',Times,serif}.nav-bar.blur{filter:blur(9%);pointer-events:none}
section{margin-top:60px}
body{background-color:#11071F}
a{color:white;text-decoration:none}.nav-bar{position:fixed;left:0;top:0;width:100%;padding:10px 3%;display:flex;flex-wrap:wrap;justify-content:space-between;align-items:center;z-index:100;background-color:#000}.nav-bar.logo{margin-left:-5px;font-size:30px;font-weight:700;font-size:50px;margin-top:10px}.nav-bar ul{display:flex}.logo{margin-top:30px}.nav-bar ul li{list-style:none;margin-left:35px}.nav-bar ul li a{font-size:20px;font-weight:500;transition:0.5s}.nav-bar ul li:hover a{color:#7cf03d}.container.icon{display:none}.container.icon:hover{color:#fff}.home{display:flex;align-items:center;gap:50px;height:100vh;padding:60px 9%0;color:#fff}.home-info h1{font-size:55px}.home-info h2{font-size:32px;margin-top:-10px}.home-info h2 span{display:inline-block;color:transparent;-webkit-text-stroke:0.7px #7cf03d;animation:display-text 2s linear infinite}.home-info p{font-size:16px;margin:10px 0 25px}.btn{display:inline-block;padding:10px 30px;background-color:#7cf03d;border:2px solid #7cf03d;border-radius:40px;box-shadow:0 0 10px #7cf03d;font-size:16px;font-weight:600;color:#1f242d;transition:0.5s}.btn:hover{background-color:transparent;box-shadow:none;color:#7cf03d}.home-img.img-box{position:relative;height:32vw;width:32vw;border-radius:50%;padding:5px;display:flex;flex-wrap:wrap;justify-content:center;align-items:center;overflow:hidden}.home-img.img-box.img-item{position:relative;height:100%;width:100%;border-radius:50%;display:flex;flex-wrap:wrap;justify-content:center;align-items:center;overflow:hidden}.home-img.img-box.img-item img{position:absolute;width:85%;object-fit:cover;z-index:5;mix-blend-mode:lighten}.home-img.img-box::before,.home-img.img-box::after{content:'';position:absolute;top:0;left:0;width:32vw;height:32vw;border-radius:50%;border:5px solid transparent;border-left-color:#7cf03d;transform:rotate(-45deg);transform:rotate(0deg);animation:rotate-border 10s linear infinite;z-index:2}.home-img.img-box::after{animation-delay:-5s}
@keyframes rotate-border{100%{transform:rotate(360deg)}}.bodyy{margin-top:50px;font-family:Arial,sans-serif;background-color:#11071F;display:flex;flex-wrap:wrap;flex-direction:column;align-items:flex-start;justify-content:center;min-height:100vh;background-image:url(img/Gradient.svg);background-position:center;background-repeat:no-repeat}.services-section{display:flex;flex-wrap:wrap;gap:50px;padding:20px;flex-wrap:wrap;justify-content:center}.card{border-radius:20px;width:320px;background:linear-gradient(145deg,#2e1035,#1d0721);box-shadow:5px 5px 10px rgba(0,0,0,0.5),-5px-5px 10px rgba(79,34,141,0.5);padding:20px;text-align:center;margin-top:30px;color:#fff;transition:transform 0.3s ease,box-shadow 0.3s ease;transform:0.3s ease,box-shadow 0.3s ease;width:47%;transform:translateZ(0)scale(1)}.card:hover{transform:perspective(1000px)rotateX(0deg)rotateY(0deg)scale3d(1,1,1);transform:perspective(1000px)rotateX(6deg)rotateY(12deg)scale3d(1,1,1);box-shadow:0 10px 20px rgba(0,0,0,0.3)}.card.icon{margin-bottom:15px}.card.icon img{margin-top:20px;width:30%;height:30%;align-items:left;float:left}.card h3{font-size:30px;margin-bottom:10px}.card p{font-size:16px;line-height:1.5;margin-bottom:20px;text-align:center}.explore-btn{display:inline-block;padding:10px 20px;border-radius:20px;color:#fff;font-size:14px;font-weight:bold;text-decoration:none;transition:0.3s ease;box-shadow:#11071F;-webkit-text-stroke:#7cf03d;background-color:transparent;border:2px solid #1d0721;border-radius:20px;box-shadow:0 0 20px #11071F}.explore-btn:hover{background-color:#7cf03d;box-shadow:none;color:#fff}.bodyy h1{color:#fff;margin-left:50px;margin-bottom:10px;font-size:50px;margin-top:60px}.flip-card{background-color:transparent;overflow:hidden;width:40%;align-items:center;display:flex;flex-wrap:wrap;flex-direction:column;margin-right:30px}.work{background-color:#11071F;padding:50px 20px;display:flex;flex-wrap:wrap;flex-direction:column}.work-h{font-size:48px;color:#fff;font-family:'Georgia',serif;font-weight:bold;margin-bottom:20px;text-align:left}.flip-card-container{display:flex;gap:50px;justify-content:center;align-items:center;flex-wrap:wrap;margin:0 auto}.flip-card{background-color:transparent;width:300px;height:300px;perspective:1000px;box-shadow:5px 5px 10px rgba(0,0,0,0.5),-5px-5px 10px rgba(79,34,141,0.5);border-radius:50%;border:2px double #7cf03d}.flip-card-inner{position:relative;width:100%;height:100%;text-align:center;transition:transform 0.8s;transform-style:preserve-3d}.flip-card:hover.flip-card-inner{transform:rotateY(180deg)}.flip-card-front,.flip-card-back{position:absolute;width:100%;height:100%;-webkit-backface-visibility:hidden;backface-visibility:hidden;display:flex;flex-wrap:wrap;justify-content:center;align-items:center;border-radius:50%}.flip-card-front{background-color:#f4f4f4;color:black;overflow:hidden}.flip-card-front img{width:100%;height:100%;object-fit:cover;border-radius:10px}.flip-card-back{color:white;transform:rotateY(180deg);flex-direction:column;border-radius:10px}.flip-card-back h3{font-size:22px;margin-bottom:20px;border-radius:10px;background:linear-gradient(145deg,#2e1035,#1d0721);box-shadow:5px 5px 10px rgba(0,0,0,0.5),-5px-5px 10px rgba(79,34,141,0.5);transition:0.3s ease}.flip-card-back:hover h3{border:2px solid #7cf03d;color:#7cf03d;padding:5px}.flip-card-back p{font-size:18px;border-radius:10px;background:linear-gradient(145deg,#2e1035,#1d0721);box-shadow:5px 5px 10px rgba(0,0,0,0.5),-5px-5px 10px rgba(79,34,141,0.5);transition:0.3s ease}.flip-card-back:hover p{padding:5px;color:#7cf03d;border:2px solid #7cf03d}.arrow-container{height:30vh;width:100%;background-color:#11071F;display:flex;justify-content:center;align-items:center;flex-wrap:wrap;position:relative}.arrow{margin-top:-140px;width:20px;height:20px;border-left:5px solid #7cf03d;border-bottom:5px solid #7cf03d;transform:rotate(-45deg);animation:moveDown 1.5s infinite ease-in-out;opacity:0;position:absolute}.arrow:nth-child(1){animation-delay:0s}.arrow:nth-child(2){animation-delay:0.2s}.arrow:nth-child(3){animation-delay:0.4s}
@keyframes moveDown{0%{transform:translateY(-20px)rotate(-45deg);opacity:0}
50%{opacity:1}
100%{transform:translateY(20px)rotate(-45deg);opacity:0}}.contact{color:#fff;text-align:left;margin-bottom:20px;padding-left:30px;padding-top:10px}.foam{width:100%;background-color:#11071F;padding:10px;border-radius:10px;margin-top:-20px}.contact h1{font-size:50px;margin:0}.login{width:100%}.form-row{display:flex;flex-wrap:wrap;justify-content:space-between;gap:2rem;margin:10px;padding:10px}.form-column{width:45%;margin:10px;padding:10px}.text-area{margin-top:-20px;text-align:center;align-items:center;margin-left:40px;justify-content:center;height:50px;padding-right:40px}.text-area label{float:left}.login label{color:#fff;font-size:18px}
#login{width:200px;border:1px solid rgb(79,34,141)}.login input,textarea{margin-top:5px;outline:none;border:1px solid rgb(79,34,141);background-image:linear-gradient(rgb(56,18,109)57%,rgb(25,6,52)100%);border-radius:14px;color:white;padding:10px 15px;width:100%;font-size:17px}
textarea{height:100px}
input[type="submit"]{margin-top:10px;padding:10px 20px;border:none;border-radius:10px;background-color:rgb(79,34,141);color:white;font-size:18px;cursor:pointer}
input[type="submit"]:hover{background-color:rgb(100,50,170)}
footer{height:100%;width:100%;background-color:rgb(44,18,80);display:flex;justify-content:center;margin-top:150px;padding-top:90px;flex-wrap:wrap;align-items:center}.logo{height:80px;display:flex;flex-wrap:wrap;gap:10px;margin-left:220px;padding-top:7px;justify-content:left}.logo img{height:100px;width:100px;align-self:center}.logo h3{color:#fff;justify-content:center;padding-top:16px;gap:5px;font-size:34px;font-style:italic;background:linear-gradient(to top,rgb(196,113,245)0%,rgb(250,113,205)100%)text;-webkit-text-fill-color:transparent}.nav-link{display:flex;flex-wrap:wrap;justify-content:center;margin-left:20px;margin-top:20px}.nav-link ul{list-style:none;display:flex;flex-wrap:wrap;gap:3rem;padding:0;margin:0}.nav-link ul li a{text-decoration:none;color:#11071F;font-size:24px;transition:color 0.3s ease;color:#fff}.nav-link ul li a:hover{color:#fff}.para{max-width:710px;text-align:center;width:100%;margin-top:30px;color:#fff}.social-logo{display:flex;flex-wrap:wrap;justify-content:center;margin-top:20px;gap:20px}.social-logo img{width:40px;height:40px}.copy-rignt{display:flex;flex-wrap:wrap;justify-content:center;margin-top:20px}.copy-rignt p{color:#fff;font-size:24px}.container-box{display:flex;flex-wrap:wrap;justify-content:space-between;width:100%;margin-top:30px}.left-box{width:60%;height:60px;background-color:rgb(79,34,141);display:flex;flex-wrap:wrap;justify-content:space-between;float:left;border-radius:10px 10px 0 0;box-shadow:0 4px 6px rgba(0,0,0,0.1);margin-left:-315px}.right-box{width:60%;height:60px;background-color:rgb(79,34,141);margin-right:-315px;display:flex;flex-wrap:wrap;justify-content:space-between;float:right;border-radius:10px 10px 0 0;box-shadow:0 4px 6px rgba(0,0,0,0.1)}

</style>
<body>
<div class=container>
<div class=nav-bar>
<a href=# class=logo>Portfolio</a>
<ul id=menu>
<li class=active><a href=#>Home</a></li>
<li><a href=#About>About</a></li>
<li><a href=#Service>Service</a></li>
<li><a href=#work>Work</a></li>
<li><a href=#contact>Contact</a></li>
</ul>
<a href=javascript:void(0); class=icon onclick=toggleMenu()>
<i class="fa fa-bars"></i>
</a>
</div>
</div>
<section class=home>
<div id=About class=home-info>
<h1>Sahir Shiraz</h1>
<h2>I'am
<span>Front-End Developer</span>
</h2>
<p>Dynamic and skilled web developer with completed DISM (Diploma in Information System Management) And CISPM (Certified Information Systems Project Manager) Courses, equipped with comprehensive knowledge ins Web development. Seeking to apply my expertise in creating Robust and user-friendly web solutions while continuously Expanding my skills and contributing to the success of Innovative projects
</p>
<div class=btn-sci>
<a href=# class=btn>Download Resume</a>
</div>
</div>
<div class=home-img>
<div class=img-box>
<div class=img-item>
<img src=WhatsApp_Image_2024-11-16_at_7.13.48_AM-removebg-preview.png alt="">
</div>
</div>
</div>
</section>
<div id=Service class=bodyy>
<div class=services><h1>Services</h1></div>
<div class=services-section>
<div class=card>
<div class=icon>
<img src=img/Wordpress.png alt="WordPress Icon">
</div>
<h3>WordPress</h3>
<p>Offering professional WordPress development services, specializing in creating fully responsive and customized websites. From theme customization to plugin integration, delivering user-friendly and SEO-optimized solutions to help businesses grow their online presence..</p>
<a href=# class=explore-btn>Explore More</a>
</div>
<div class=card>
<div class=icon>
<img src="img/html icon.png" alt="Design Icon">
</div>
<h3>Front-End Developer</h3>
<p>Offering professional front-end development services, specializing in crafting responsive and visually appealing websites. Expert in HTML and CSS, delivering clean, efficient code and user-friendly designs to enhance user experience and bring your ideas to life.</p>
<a href=# class=explore-btn>Explore More</a>
</div>
<div class=card>
<div class=icon>
<img src=img/phitishop.webp alt="Design Icon">
</div>
<h3>Photoshop</h3>
<p>Offering professional Photoshop services, specializing in creating stunning visuals and designs. From photo retouching to custom graphics, delivering high-quality, creative solutions tailored to your needs.</p>
<a href=# class=explore-btn>Explore More</a>
</div>
<div class=card>
<div class=icon>
<img src=img/illustrator-removebg-preview.png alt="Design Icon">
</div>
<h3>Illustrator</h3>
<p>Providing expert Adobe Illustrator services, focusing on crafting unique vector designs, logos, and illustrations. From branding to intricate artwork, delivering precision and creativity to bring your ideas to life.</p>
<a href=# class=explore-btn>Explore More</a>
</div>
</div>
</div>
<div class=work>
<div id=work class=work-h>
<h2>Projects</h2>
</div>
<div class=flip-card-container>
<div class=flip-card>
<div class=flip-card-inner>
<div class=flip-card-front>
<img src=img/tour.png alt=Avatar style=width:300px;height:300px>
</div>
<div class=flip-card-back>
<a href=https://github.com/sahiraly786/Tour.git><h3>Get Code</h3></a>
<a href=https://tourstype.netlify.app/ ><p>Live Demo</p></a>
</div>
</div>
</div>
<div class=flip-card>
<div class=flip-card-inner>
<div class=flip-card-front>
<img src=img/covid.png alt=Avatar style=width:300px;height:300px>
</div>
<div class=flip-card-back>
<a href=https://github.com/sahiraly786/covid.git><h3>Get Code</h3></a>
<a href=https://covidvacc.netlify.app/ ><p>Live Demo</p></a>
</div>
</div>
</div>
<div class=flip-card>
<div class=flip-card-inner>
<div class=flip-card-front>
<img src=img/bag.png alt=Avatar style=width:300px;height:300px>
</div>
<div class=flip-card-back>
<a href=https://github.com/sahiraly786/covid.git><h3>Get Code</h3></a>
<a href=https://bagsbags.netlify.app/ ><p>Live Demo</p></a>
</div>
</div>
</div>
</div>
</div>
<div class=arrow-container>
<div class=arrow></div>
<div class=arrow></div>
<div class=arrow></div>
</div>
<div class=content>
<div id=contact class=foam>
<div class=contact>
<h1>Contact Us</h1>
</div>
<form action=https://api.web3forms.com/submit method=POST class=login>
<div class=form-row>
<div class=form-column>
<input type=hidden name=access_key value=f38e26ba-4a40-44ca-81e9-3edb1c330da7>
<label for=Firstname>First Name</label><br>
<input name=Firstname placeholder="Enter Your First Name"><br><br>
<label for=Email>Email</label><br>
<input type=email name=Email placeholder="Enter Your Email"><br><br>
</div>
<div class=form-column>
<label for=Lastname>Last Name</label><br>
<input name=Lastname placeholder="Enter Your Last Name"><br><br>
<label for=Phone>Phone Number</label><br>
<input type=number name=Phone placeholder="Enter Your Number"><br><br>
</div>
</div>
<div class=text-area>
<label for=Message>Details</label><br>
<textarea id=text name=Message placeholder="Enter Your Text"></textarea><br>
<input id=login type=submit value=Submit>
</div>
</form>
</div>
</div>

<footer>
<div class=end>
<div class=logo>
<img src=img/logo.svg alt="">
<h3>Expert corder</h3>
</div>
<div class=nav-link>
<ul>
<li><a href=#>Home</a></li>
<li><a href=#>About</a></li>
<li><a href=#>Services</a></li>
<li><a href=#>Work</a></li>
<li><a href=#>Contact</a></li>
</ul>
</div>
<div class=para>
<p>Passionate Front-End Developer skilled in HTML, CSS, JavaScript, and React. Crafting seamless user experiences and visually stunning websites. Expert in creating professional email signatures that leave a lasting impression.</p>
</div>
<div class=social-logo>
<a href=https://www.linkedin.com/in/sahir-aly/ ><img src=img/link.webp alt=""></a>
<a href=https://github.com/sahiraly786><img src=img/github.png alt=""></a>
</div>
<div class=copy-rignt>
<p>Made By Sahir >>> Copy Right &#169;</p>
</div>
<div class=container-box>
<div class=left-box></div>
<div class=right-box></div>
</div>
</div>
</footer>
<script>function toggleMenu(){document.getElementById("menu").classList.toggle("active")}</script>
</body>
</html>
