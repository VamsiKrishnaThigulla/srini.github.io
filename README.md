<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Welcome To D.O.T.S.</title>

<!--  # Importing Font's #  -->
    <link href="https://fonts.googleapis.com/css?family=Bangers&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css?family=Josefin+Sans&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css?family=Lobster&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css?family=Sigmar+One&display=swap" rel="stylesheet">
	<link rel="stylesheet" href="slider_style.css">

<!--    #################################################################################################     -->

<!--  # Importing StyleSheet Style.css #  -->
	<link rel="stylesheet" type="text/css" href="style.css">
	<link rel="stylesheet" type="text/css" href="popup.css">

<!--  #######################################################################################################  -->

<!--  # Importing Font Awesome Icon's #  -->
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

<!--    ####################################################################################################    -->

    <!--  # Importing JavScript Files #  -->
	<script src="https://code.jquery.com/jquery-3.4.1.js"></script>
    <script src="http://ajax.googleapis.com/ajax/libs/jquery/1.12.0/jquery.min.js"></script>
	<script>window.jQuery || document.write('<script src="js/vendor/jquery-1.12.1.min.js"><\\/script>')</script>

<!--  ########################################################################################################  -->

<!--    OnScroll JavaScript Function-->
    <script type="text/javascript">
  	$(window).on('scroll', function(){
  		if($(window).scrollTop()){
  			$('nav').addClass('black');
  			$('header').addClass('scrolled');
  		}
  		else
        {
  			$('nav').removeClass('black');
  			$('header').removeClass('scrolled');
  		}
  	})
  </script>
</head>

<!--  ################   *************** The Body section of the Main Page ***************   ###################    -->

<body>
	<header>
		<div class="Login">
			<a href="Login/newlogin/login-new/login.html">
				Login
			</a>
		</div>
		<div class="Signup">
			<a href="Signup/signup.html">
				Sign up
			</a>
		</div>
		<div class="container">
			<nav>
				<h1 class="Logo-name"><a href="index.html">D<span>O</span>tS</a></h1>
				<h1 class="Logo-name1"><a href="index.html">H<span>om</span>e</a></h1>
				<ul class="FullScreen" id="dropDownClick">
					<li class="navitms">
                        <a href="index.html">Home</a>
                    </li>
					<li class="navitms">
                        <a href="page-not-found/index.html">Services</a>
                    </li>
					<li class="navitms">
                        <a href="page-not-found/index.html">Contacts</a>
                    </li>
					<li class="navitms">
                        <a href="page-not-found/index.html">About</a>
                    </li>
					<li class="navico">
                        <a href="javascript: void(0)" onclick="dropDownMenu()">
				            <i class="fa fa-bars" aria-hidden="true" style="font-size:20px;"></i>
                        </a>
                    </li>
				</ul>
			</nav>
		</div>
		<!-- Change class fullscreen to FullScreen.Mobile_view when fa-bars is clicked -->
		<script>
			function dropDownMenu(){
				var x = document.getElementById("dropDownClick");
				if (x.className === "FullScreen") {
				    x.className += " Mobile_view";
				}
				else {
					x.className = "FullScreen";
				}
			}
		</script>
	</header>

<!--  ##########################################################################################################  -->

	<!-- Slideshow container
        <div class="slideshow-container">
   Full-width images with number and caption text
            <div class="mySlides fade">
            <div class="numbertext">1 / 8</div>
            <img class="images" src="dist/slideshow-Images/ball_smile_2560x1080.jpg">
                <div class="text">
                    <h1>Danielle Rose Russel <span>Aka </span><span>Hope Andera Mikaelson</span></h1>
                    <h2>
                    Danielle is one of the most talented actresses of the century and also
                    she is one of my favourite persons on this planet,
                    not because of how beautiful her appearance is but because how beautiful
                    she is from the inside.
                    She's one of those persons who've been through their worst times yet
                    they choose to never gave up because they knew that they weren't made of giving up.
                </h2>
                </div>
            </div>
            <div class="mySlides fade">
                <div class="numbertext">2 / 8</div>
                <img class="images" src="dist/slideshow-Images/abstraction1_2560x1080.jpg">
                <div class="text">
                    <h3>
                        Hope Andrea Mikaelson is a main character in Legacies, she was a former
                        major recurring character in The Originals before being promoted to a
                        main character in the fifth season. Hope is the tribrid daughter of
                        Niklaus Mikaelson and Hayley Marshall-Kenner. She is the granddaughter
                        of Ansel, Esther Mikaelson and two unnamed werewolves, as well as the
                        step-granddaughter of Mikael. She is also the niece of Freya, Finn,
                        Elijah, Kol, Rebekah, and Henrik Mikaelson, and the grand-niece of
                        Dahlia. She is also a distant relative of Lana, Eve, and Cary. She is
                        the adoptive younger sister of Marcel Gerard via her father. Due to his
                        marriage to Hayley, Jackson Kenner was her step-father for almost a
                        year, until he was killed by Tristan de Martel.
                    </h3>
                </div>
            </div>
            <div class="mySlides fade">
                <div class="numbertext">3 / 8</div>
                <img class="images" src="dist/slideshow-Images/biggest_diamond_in_the_world-wallpaper-2560x1080.jpg">
                <div class="text">Caption Two</div>
            </div>
            <div class="mySlides fade">
                <div class="numbertext">4 / 8</div>
                <img class="images" src="dist/slideshow-Images/beautiful_girl_painting-wallpaper-2560x1080.jpg">
                <div class="text">Caption</div>
            </div>
            <div class="mySlides fade">
                <div class="numbertext">5 / 8</div>
                <img class="images" src="dist/slideshow-Images/hourglass_stones_blur_2560x1080.jpg">
                <div class="text">Caption</div>
            </div>
            <div class="mySlides fade">
                <div class="numbertext">6 / 8</div>
                <img class="images" src="dist/slideshow-Images/need_for_speed_heat_lamborghini-wallpaper-2560x1080.jpg" >
                <div class="text">Caption Two</div>
            </div>
            <div class="mySlides fade">
                <div class="numbertext">7 / 8</div>
                <img class="images" src="dist/slideshow-Images/razer_snakes_slime_background-wallpaper-2560x1080.jpg">
                <div class="text">Caption Two</div>
            </div>
            <div class="mySlides fade">
                <div class="numbertext">8 / 8</div>
                <img class="images" src="dist/slideshow-Images/legacies.png" style="background:#000;">
                <div class="text">Caption Two</div>
            </div>
   Next and previous buttons
            <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
            <a class="next" onclick="plusSlides(1)">&#10095;</a>
        </div>
	-->
<!--Once backend is implemented, relevant images will be placed in slideshow -->
<!--	NEW SlideShow Container With Js Jssor    -->
	<div>
		<!-- #region Jssor Slider Begin -->
		<!-- Generator: Jssor Slider Composer -->
		<!-- Source: https://www.jssor.com/demos/image-slider.slider/=edit -->
		<script src="js/jssor.slider-28.0.0.min.js" type="text/javascript"></script>
		<script src="effect.js" type="text/javascript"></script>
			<div id="jssor_1" style="position:relative;margin:30px auto;top:0px;left:0px;width:980px;height:380px;overflow:hidden;visibility:hidden;">
				<div data-u="slides" style="cursor:default;position:relative;top:0px;left:0px;width:980px;height:380px;overflow:hidden;border-radius: 20px;">
					<div style="background-color:#000000;">
						<img data-u="image" style="opacity:0.5;" src="img/px-action-athlete-athletes-848618-image.jpg" />
					</div>
					<div>
						<img data-u="image" src="img/px-beach-daylight-fun-1430675-image.jpg" />
					</div>
					<div>
						<img data-u="image" src="dist/slideshow-Images/abstraction1_2560x1080.jpg" />
					</div>
					<div>
						<img data-u="image" src="dist/slideshow-Images/ball_smile_2560x1080.jpg" />
					</div>
					<div>
						<img data-u="image" src="dist/slideshow-Images/beautiful_amber_heard-wallpaper-2560x1080.jpg" />
					</div>
					<div>
						<img data-u="image" src="dist/slideshow-Images/beautiful_girl_painting-wallpaper-2560x1080.jpg" />
					</div>
					<div>
						<img data-u="image" src="dist/slideshow-Images/biggest_diamond_in_the_world-wallpaper-2560x1080.jpg" />
					</div>
					<div>
						<img data-u="image" src="dist/slideshow-Images/hourglass_stones_blur_2560x1080.jpg" />
					</div>
					<div>
						<img data-u="image" src="dist/slideshow-Images/img_lights_wide.jpg" />
					</div>
					<div style="background-color:#000000;">
						<img data-u="image" style="opacity:0.5;" src="img/faded-monaco-scenery-evening-dark-picjumbo-com-image.jpg" />
					</div>
					<div>
						<img data-u="image" src="img/px-bloom-blossom-flora-65219-image.jpg" />
					</div>

			</div>
				<a data-scale="0" href="https://www.jssor.com" style="display:none;position:absolute;">slider html</a>
			<!-- Bullet Navigator -->
			<div data-u="navigator" class="jssorb031" style="position:absolute;bottom:16px;right:16px;" data-autocenter="1" data-scale="0.5" data-scale-bottom="0.75">
				<div data-u="prototype" class="i" style="width:13px;height:13px;">
					<svg viewbox="0 0 16000 16000" style="position:absolute;top:0;left:0;width:100%;height:100%;">
						<circle class="b" cx="8000" cy="8000" r="5800"></circle>
					</svg>
				</div>
			</div>
			<!-- Arrow Navigator -->
			<div data-u="arrowleft" class="jssora051" style="width:55px;height:55px;top:0px;left:25px;" data-autocenter="2" data-scale="0.75" data-scale-left="0.75">
				<svg viewbox="0 0 16000 16000" style="position:absolute;top:0;left:0;width:100%;height:100%;">
					<polyline class="a" points="11040,1920 4960,8000 11040,14080 "></polyline>
				</svg>
			</div>
			<div data-u="arrowright" class="jssora051" style="width:55px;height:55px;top:0px;right:25px;" data-autocenter="2" data-scale="0.75" data-scale-right="0.75">
				<svg viewbox="0 0 16000 16000" style="position:absolute;top:0;left:0;width:100%;height:100%;">
					<polyline class="a" points="4960,1920 11040,8000 4960,14080 "></polyline>
				</svg>
			</div>

		</div>
		<script type="text/javascript">jssor_1_slider_init();
		</script>
	</div>

        <br>
<!-- The dots/circles -->
<!--
        <div style="text-align:center">
            <span class="dot" onclick="currentSlide(1)"></span>
            <span class="dot" onclick="currentSlide(2)"></span>
            <span class="dot" onclick="currentSlide(3)"></span>
            <span class="dot" onclick="currentSlide(4)"></span>
            <span class="dot" onclick="currentSlide(5)"></span>
            <span class="dot" onclick="currentSlide(6)"></span>
            <span class="dot" onclick="currentSlide(7)"></span>
            <span class="dot" onclick="currentSlide(8)"></span>
        </div>
 Script for changing the slides
        <script>
            var slideIndex = 1;
            var clicked = 1;
            showSlides(slideIndex);
            function plusSlides(n) {
                showSlides(slideIndex += n);
                clicked ++;
            }
            function currentSlide(n) {
                showSlides(slideIndex = n);
            }
            function showSlides(n) {
                var i;
                var slides = document.getElementsByClassName("mySlides");
                var dots = document.getElementsByClassName("dot");
                if (n > slides.length) {slideIndex = 1}
                if (n < 1) {slideIndex = slides.length}
                for (i = 0; i < slides.length; i++) {
                    slides[i].style.display = "none";
                }
                for (i = 0; i < dots.length; i++) {
                    dots[i].className = dots[i].className.replace(" active", "");
                }
                if(clicked > 1){
                    slideIndex = slideIndex-1;
                    clicked = 1;
                }
                slides[slideIndex-1].style.display = "block";
                dots[slideIndex-1].className += " active";
                setTimeout(function(){showSlides(slideIndex += 1)},3000);
            }
        </script>
-->

<!--  ###########################################################################################################  -->

<!-- Sections of the page -->

    <!--    # Section Involving Subjects & Departments #    -->
    <div class="rows">
        <div class="col-4" onclick="window.location.href='index.html'">
            <div class="box">
                <div>
                    <img class="box-icon" src="dist/images/departments/computer-science-icon.png">
                </div>
                <label>Computer Science</label>
                <p>"Once backend is implemented, proper text and images relevant will be displayed </p>
            </div>
        </div>
        <div class="col-4" onclick="window.location.href='index.html'">
            <div class="box">
                <div>
                    <img class="box-icon" src="dist/images/departments/electronics-512.png">
                </div>
                <label>Electronics</label>
                <p>"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore </p>
            </div>
        </div>
        <div class="col-4" onclick="window.location.href='index.html'">
            <div class="box">
                <div>
                    <img class="box-icon" src="dist/images/departments/mech.png">
                </div>
                <label>Mechanical</label>
                <p>"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore </p>
            </div>
        </div>
    </div>

    <br>
    <hr>

<!--    ###### Script for Generating a pop up ######     -->

<!--  ###########################################################################################################  -->

<!--    #########   3D Hover Effect Images  ##########    -->
    <div class="site-content">
		<div class="demo demo-1">
            <h1>HOT Topics</h1>
			<div class="project-list">
				<div class="project">
					<div class="project__card">
						<a href="" class="project__image"><img src="dist/background_imgs/indexbg.jpg" width=600 height=400 alt=""></a>
						<div class="project__detail">
							<h2 class="project__title"><a href="#">Topic Name</a></h2>
							<small class="project__category"><a href="#">Contents</a></small>
						</div>
					</div>
				</div>

				<div class="project">
					<div class="project__card">
						<a href="" class="project__image"><img src="dist/images/3D_Hover_Images/21f18460a5e9af762f7baf84a380f178.jpg" width=600 height=400 alt=""></a>
						<div class="project__detail">
							<h2 class="project__title"><a href="#">Topic Name</a></h2>
							<small class="project__category"><a href="#">Contents</a></small>
						</div>
					</div>
				</div>

				<div class="project">
					<div class="project__card">
						<a href="" class="project__image"><img src="dist/images/3D_Hover_Images/water-4785991_1920.jpg" width=600 height=400 alt=""></a>
						<div class="project__detail">
							<h2 class="project__title"><a href="#">Topic Name</a></h2>
							<small class="project__category"><a href="#">Contents</a></small>
						</div>
					</div>
				</div>

				<div class="project">
					<div class="project__card">
						<a href="" class="project__image"><img src="dist/images/3D_Hover_Images/lighthouse-3361704.jpg" width=600 height=400 alt=""></a>
						<div class="project__detail">
							<h2 class="project__title"><a href="#">Topic Name</a></h2>
							<small class="project__category"><a href="#">Contents</a></small>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>

<!--  ###########################################################################################################  -->


    <div class="next-section">
        <h1>Important Information</h1>
        <div class="container">
            <h2>Topic Name</h2>
            <p class="topic-info">
                hello world  lorem. .    .   .   .    . . . . . . . . . . .  .  . . . . . . . . . . . . . . . .
                Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.
            </p>
            <a class="hover-effected">All the extra details to be shown when the mouse is hovered over the container is to be submitted here and will be displayed only when mouse is hovered over the container. to view the content as usual , you need to disbale the hover effect in the css file "Style.css" at line no 497 stated as '.next-section .container:hover h2, .next-section .container:hover .Post'</a>
            <div class="Post">
                <p class="information">Content to be written</p>
                <div class="images">
                    <img src="blue-and-purple-cosmic-sky-956999.jpg">
                    <img src="Hope-And-Landon.jpg">
                    <img src="legacies-5d0b2ccb582c7.jpg">
                </div>
            </div>
        </div>
    </div>

<!--  # Video files Contents #  -->
    <div class="vid-sec">
        <video id="slider" autoplay muted loop controls>
            <source src="dist/videos/James%20Bond%20007%20Skyfall%20by%20Adele%20%5BOFFICIAL%20FULL%20MUSIC%20VIDEO%5D.mp4" type="video/mp4">
        </video>
        <ul class="vid-navigation">
            <li onclick="videoUrl('dist/videos/James%20Bond%20007%20Skyfall%20by%20Adele%20%5BOFFICIAL%20FULL%20MUSIC%20VIDEO%5D.mp4')"><img src="dist/images/thumbnails/video/james-bond-skyfall-adele.jpeg"></li>
            <li onclick="videoUrl('dist/videos/Bebe%20Rexha%20-%20Meant%20to%20Be%20(feat.%20Florida%20Georgia%20Line)%20%5BOfficial%20Music%20Video%5D.mp4')"><img src="dist/images/thumbnails/video/bebe-rexha-meant-to-be.jpeg"></li>
            <li onclick="videoUrl('dist/videos/Bom%20Diggy%20Vs%20Mi%20Gente%20-%20DJ%20Kevin%20J%20Mashup.mp4')"><img src="dist/images/thumbnails/video/boom-diggy-jasmin-walia-zack-knight.jpeg"></li>
            <li onclick="videoUrl('dist/videos/Rachel%20Platten%20-%20Fight%20Song%20(Official%20Video).mp4')"><img src="dist/images/thumbnails/video/rachael-platten-flight-song.jpeg"></li>
            <li onclick="videoUrl('dist/videos/My%20Video1.mp4')"><img src="dist/images/thumbnails/video/intro-video.jpeg"></li>
        </ul>
    </div>

<!--    Script to Switch Video Url When Clicked -->
    <script type="text/javascript">
        function videoUrl(new_vid){
            document.getElementById("slider").src = new_vid;
        }
    </script>


<!--  ###########################################################################################################  -->

<!--        Wavy Body Contents          -->
    <div class="Wavy_body">
        <div class="Wavy_text">
            <div class="Wavy_box">
                <div class="Wavy_content">
                    <h2>Block Contents to be written in the box.</h2>
                    <p>
                    Sample lorem ipsum text which is a dummy text written so as to make website look like it contains stuff which isn't the content of the website. it is all the dummy text written all over the page is all useless.
                    </p>
                </div>
            </div>
        </div>
        <div class="Wavy_text">
            <div class="Wavy_box">
                <div class="Wavy_content">
                    <h2>Block Contents to be written in the box.</h2>
                    <p>
                    Sampl elorem ipsum text which is a dummy text written so as to make website look like it contains stuff which isn't the content of the website. it is all the dummy text written all over the page is all useless.
                    </p>
                </div>
            </div>
        </div>
        <div class="Wavy_text">
            <div class="Wavy_box">
                <div class="Wavy_content">
                    <h2>Block Contents to be written in the box.</h2>
                    <p>
                    Sampl elorem ipsum text which is a dummy text written so as to make website look like it contains stuff which isn't the content of the website. it is all the dummy text written all over the page is all useless.
                    </p>
                </div>
            </div>
        </div>
    </div>
    <svg>
        <filter id="wavy">
            <feTurbulence x="0" y="0" baseFrequency="0.02" numOctaves="10" seed="5">
                <animate attributeName="baseFrequency" dur="60s" values="0.02;0.05;0.02" repeatCount="indefinite"/>
            </feTurbulence>
            <feDisplacementMap in="SourceGraphic" scale="30"></feDisplacementMap>
        </filter>
    </svg>


<!--  ###########################################################################################################  -->

<!--    # Group Members Section #    -->

    <div class="rows">
        <div class="col-12">
            <h1>Group Members</h1>
            <h1>AKA Developers</h1>
        </div>
    </div>
    <div class="members-contents">
        <div class="contents-container">
            <div class="cards">
                <div class="member-container">
                    <a href="" class="member_image"><img src="dist/images/members/profiles/vamsi.jpg"></a>
                    <div class="member-details">
                        <h2 class="member-name" >
                            <a href="javascript:void(0)"id="Vamsi">Vamsi Krishna</a>
                        </h2>
                        <small class="extra-details">
                            <a href="javascript:void(0)">Writer</a>
                        </small>
                    </div>
                </div>
				<div class="popup" id="Vamsi-writer">
			<div class="popup-box">
				<div class="profile-context">
					<div class="profile-img">
						<img class="social-img" src="dist/images/members/profiles/vamsi.jpg">
					</div>
					<div class="Profile-Vid" style="padding:10px;background:#0bc;border-radius: 10px;width:540px height:50%;margin:0 auto;overflow:hidden;">
						<iframe width="520" height="250" src="https://www.youtube.com/embed/SK7aTWf81DY" frameborder="0" allow="accelerometer; autoplay = 1; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
					</div>
				</div>
				<div class="inner-part">
					<ul class="Social-links">
						<li>
							<p>
								<a class="facebook" href="https://www.facebook.com/vamsi.thigulla"><i class="fa fa-facebook" aria-hidden="true"></i><h5>Facebook</h5></a>
							</p>
						</li>
						<li>
							<p>
								<a class="quora" href="https://www.quora.com/profile/Vamsi-Krishna-Thigulla"><i class="fa fa-quora" aria-hidden="true"></i><h5>Quora</h5></a>
							</p>
						</li>
						<li>
							<p>
								<a href="https://www.fanfiction.net/u/8597347/"><img src="fanfiction.png" style="width: 30px"><h5>Fanfiction</h5></a>
							</p>
						</li>
					</ul>
					<hr style="margin-top: 20px;">
					<div class="about-details">
						<h1 style="margin:10px;">About Me</h1>
						<ul class="about">
							<li>
								<p>Name : <span>Vamsi krishna Thigulla</span></p>
							</li>
							<li>
								<p>Roll No : <span>COE18B056</span> </p>
							</li>
							<li>
								<p>Department : Computer Science</p>
							</li>
							<li>
								<p>Hobby : Writing</p>
							</li>
						</ul>
					</div>
					<div class="about-contents">
						<br>
						<h2>Something You want to Say about Yourself.</h2>
						<br>
						<p>I'm interested in simply improving myself in different fields. Other interests of mine include reading different works, writing, and watching anime.
						</p>
					</div>
				</div>
			</div>
        	<a class="close-btn"><i class="fa fa-close"></i></a>
        </div>
        		<script>
        	document.getElementById("Vamsi").addEventListener("click", function(){
                document.getElementById("Vamsi-writer").style.display = "block";
            })
        document.querySelector(".close-btn").addEventListener("click", function(){
                document.getElementById("Vamsi-writer").style.display = "none";
            })
        		</script>
            </div>
            <div class="cards">
                <div class="member-container">
                    <a href="" class="member_image"><img src="dist/images/members/profiles/srini.JPEG"></a>
                    <div class="member-details">
                        <h2 class="member-name" >
                            <a href="javascript:void(0)" id="Srini">Srinivasan Sharma</a>
                        </h2>
                        <small class="extra-details">
                            <a href="javascript:void(0)">Doraemon</a>
                        </small>
                    </div>
                </div>
				<div class="popup" id="Srini-Doraemon">
			<div class="popup-box">
				<div class="profile-context">
					<div class="profile-img">
						<img class="social-img" src="dist/images/members/profiles/srini.JPEG">
					</div>
					<div class="Profile-Vid" style="padding:10px;background:#0bc;border-radius: 10px;width:540px height:50%;margin:0 auto;overflow:hidden;">
						<iframe width="520" height="250" src="https://www.youtube.com/embed/1_AbhgbnjkA" frameborder="0" allow="accelerometer; autoplay = 1; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
					</div>
				</div>
				<div class="inner-part">
					<ul class="Social-links">
						<li>
							<p>
								<a class="facebook" href="https://www.facebook.com/vamsi.thigulla"><i class="fa fa-facebook" aria-hidden="true"></i><h5>Facebook</h5></a>
							</p>
						</li>
						<li>
							<p>
								<a class="quora" href="https://www.quora.com/profile/Vamsi-Krishna-Thigulla"><i class="fa fa-quora" aria-hidden="true"></i><h5>Quora</h5></a>
							</p>
						</li>
						<li>
							<p>
								<a href="https://www.fanfiction.net/u/8597347/"><i class="fa fa-linkedin-square"></i><h5>LinkedIn</h5></a>
							</p>
						</li>
					</ul>
					<hr style="margin-top: 20px;">
					<div class="about-details">
						<h1 style="margin:10px;">About Me</h1>
						<ul class="about">
							<li>
								<p>Name : <span>Srinivasan R Sharma</span></p>
							</li>
							<li>
								<p>Roll No : <span>COE18B065</span> </p>
							</li>
							<li>
								<p>Department : Computer Science</p>
							</li>
							<li>
								<p>Hobby : Watching Anime and Coding</p>
							</li>
						</ul>
					</div>
					<div class="about-contents">
						<br>
						<h2>About Myself</h2>
						<br>
						<p>I'm a Computer Science student who's interested in all branches in CS. I'm interested in trying to solve new and innovative problems. Other interests include watching anime, reading novels.
						</p>
					</div>
				</div>
			</div>
        	<a class="close-btn1"><i class="fa fa-close"></i></a>
        </div>
        		<script>
        	document.getElementById("Srini").addEventListener("click", function(){
                document.getElementById("Srini-Doraemon").style.display = "block";
            })
        document.querySelector(".close-btn1").addEventListener("click", function(){
                document.getElementById("Srini-Doraemon").style.display = "none";
            })
        		</script>
            </div>
            <div class="cards">
                <div class="member-container">
                    <a href="" class="member_image"><img src="dist/images/members/profiles/Vijay.jpg"></a>
                    <div class="member-details">
                        <h2 class="member-name" >
                            <a href="javascript:void(0)" id="Vijay">Vijay Meena</a>
                        </h2>
                        <small class="extra-details">
                            <a href="javascript:void(0)" id="Vijay">Gamer Boy</a>
                        </small>
                    </div>
					<div class="popup" id="Vijay-Gamer">
			<div class="popup-box">
				<div class="profile-context">
					<div class="profile-img">
						<img class="social-img" src="dist/images/members/profiles/Vijay.jpg">
					</div>
					<div class="Profile-Vid" style="padding:10px;background:#0bc;border-radius: 10px;width:540px height:50%;margin:0 auto;overflow:hidden;">
						<iframe width="520" height="250" src="https://www.youtube.com/embed/oAd4K_UyTpM" frameborder="0" allow="accelerometer; autoplay = 1; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
					</div>
				</div>
				<div class="inner-part">
					<ul class="Social-links">
						<li>
							<p>
								<a class="facebook" href="https://www.facebook.com/VijayMeena001"><i class="fa fa-facebook" aria-hidden="true"></i><h5>Facebook</h5></a>
							</p>
						</li>
						<li>
							<p>
								<a class="quora" href="https://www.quora.com/profile/Vijay-Meena-46"><i class="fa fa-quora" aria-hidden="true"></i><h5>Quora</h5></a>
							</p>
						</li>
						<li>
							<p>
								<a href="https://www.linkedin.com/in/vijay-meena-02920a17a/"><i class="fa fa-linkedin-square"></i><h5>LinkedIn</h5></a>
							</p>
						</li>
					</ul>
					<hr style="margin-top: 20px;">
					<div class="about-details">
						<h1 style="margin:10px;">About Me</h1>
						<ul class="about">
							<li>
								<p>Name : <span>Vijay Meena</span></p>
							</li>
							<li>
								<p>Roll No : <span>CED18I057</span> </p>
							</li>
							<li>
								<p>Department : Computer Science</p>
							</li>
							<li>
								<p>Hobby : Gaming, Coding, Sketching</p>
							</li>
						</ul>
					</div>
					<div class="about-contents">
						<br>
						<h2>A Tech Enthusiast Interested in Computers.</h2>
						<br>
						<p>I'm interested in coding. I like drawing portraits. I am also a skilled gamer.
						</p>
					</div>
				</div>
			</div>
        	<a class="close-btn2"><i class="fa fa-close"></i></a>
        </div>
        		<script>
        document.getElementById("Vijay").addEventListener("click", function(){
                document.getElementById("Vijay-Gamer").style.display = "block";
            })
        document.querySelector(".close-btn2").addEventListener("click", function(){
                document.getElementById("Vijay-Gamer").style.display = "none";
            })
        </script>
                </div>
            </div>
            <div class="cards">
                <div class="member-container">
                    <a href="" class="member_image"><img src="dist/images/members/profiles/rishi.jpg"></a>
                    <div class="member-details">
                        <h2 class="member-name" >
                            <a href="javascript:void(0)" id="Hrishikesh">Hrishikesh</a>
                        </h2>
                        <small class="extra-details">
                            <a href="javascript:void(0)" id="Hrishikesh">Ninja/Artist</a>
                        </small>
                    </div>
                </div>
				<div class="popup" id="Hrishikesh-Ninja">
			<div class="popup-box">
				<div class="profile-context">
					<div class="profile-img">
						<img class="social-img" src="dist/images/members/profiles/rishi.jpg">
					</div>
					<div class="Profile-Vid" style="padding:10px;background:#0bc;border-radius: 10px;width:540px height:50%;margin:0 auto;overflow:hidden;">
						<iframe width="520" height="250" src="https://www.youtube.com/embed/mpD3OM5Um8M" frameborder="0" allow="accelerometer; autoplay = 1; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
					</div>
				</div>
				<div class="inner-part">
					<ul class="Social-links">
						<li>
							<p>
								<a class="facebook" href="https://steamcommunity.com/id/NINJATYR"><i class="fa fa-steam" aria-hidden="true" style="color: #00adee"></i><h5>Steam</h5></a>
							</p>
						</li>
						<li>
							<p>
								<a class="quora" href="https://www.instagram.com/hrishikeshrajeshmenon"><i class="fa fa-instagram" style="color:magenta"></i><h5>Instagram</h5></a>
							</p>
						</li>
						<li>
							<p>
								<a href="https://www.linkedin.com/in/hrishikesh-rajesh-menon-16020917a"><i class="fa fa-linkedin-square"></i><h5>LinkedIn</h5></a>
							</p>
						</li>
					</ul>
					<hr style="margin-top: 20px;">
					<div class="about-details">
						<h1 style="margin:10px;">About Me</h1>
						<ul class="about">
							<li>
								<p>Name : <span>Hrishikesh Rajesh Menon</span></p>
							</li>
							<li>
								<p>Roll No : <span>COE18B024</span> </p>
							</li>
							<li>
								<p>Department : Computer Science</p>
							</li>
							<li>
								<p>Hobby : Digital Art and Game design</p>
							</li>
						</ul>
					</div>
					<div class="about-contents">
						<br>
						<h2>I love working in the field of tech.</h2>
						<br>
						<p>Ever since I was young , I've always loved working with technology, started with my love of playing video games. And I've always had a bit of a creative side so art and animation we're fun and interesting to learn. Hence why I got into the world of game design.
						</p>
					</div>
				</div>
			</div>
        	<a class="close-btn3"><i class="fa fa-close"></i></a>
        </div>
        		<script>
        document.getElementById("Hrishikesh").addEventListener("click", function(){
                document.getElementById("Hrishikesh-Ninja").style.display = "block";
            })
        document.querySelector(".close-btn3").addEventListener("click", function(){
                document.getElementById("Hrishikesh-Ninja").style.display = "none";
            })
        </script>
            </div>
            <div class="cards">
                <div class="member-container">
                    <a href="" class="member_image"><img src="dist/images/members/profiles/shashank.jpg"></a>
                    <div class="member-details">
                        <h2 class="member-name" >
                            <a href="javascript:void(0)" id="Shashank">Shashank</a>
                        </h2>
                        <small class="extra-details">
                            <a href="javascript:void(0)">Nobita</a>
                        </small>
                    </div>
                </div>
				<div class="popup" id="Shashank-Nobita">
			<div class="popup-box">
				<div class="profile-context">
					<div class="profile-img">
						<img class="social-img" src="dist/images/members/profiles/shashank.jpg">
					</div>
					<div class="Profile-Vid" style="padding:10px;background:#0bc;border-radius: 10px;width:540px height:50%;margin:0 auto;overflow:hidden;">
						<iframe width="520" height="250" src="https://www.youtube.com/embed/K3Kyd-mAYOA" frameborder="0" allow="accelerometer; autoplay = 1; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
					</div>
				</div>
				<div class="inner-part">
					<ul class="Social-links">
						<li>
							<p>
								<a class="facebook" href="https://www.facebook.com/sashankdk"><i class="fa fa-facebook" aria-hidden="true"></i><h5>Facebook</h5></a>
							</p>
						</li>
						<li>
							<p>
								<a class="quora" href="https://www.instagram.com/sashankdk/"><i class="fa fa-instagram" style="color:red"></i><h5>Instagram</h5></a>
							</p>
						</li>
						<li>
							<p>
								<a href="https://www.linkedin.com/in/shashank-dokania-bbb9b1190/"><i class="fa fa-linkedin-square"></i><h5>LinkedIn</h5></a>
							</p>
						</li>
					</ul>
					<hr style="margin-top: 20px;">
					<div class="about-details">
						<h1 style="margin:10px;">About Me</h1>
						<ul class="about">
							<li>
								<p>Name : <span>Shashank D.K.</span></p>
							</li>
							<li>
								<p>Roll No : <span>COE18B067</span> </p>
							</li>
							<li>
								<p>Department : Computer Science</p>
							</li>
							<li>
								<p>Hobby : likes to read novels and manga.</p>
							</li>
						</ul>
					</div>
					<div class="about-contents">
						<br>
						<h2>The Most studious Guy you'll Ever meet.</h2>
						<br>
						<p> I Love Sports, Watching Anime And Reading Manga.
						</p>
					</div>
				</div>
			</div>
        	<a class="close-btn4"><i class="fa fa-close"></i></a>
        </div>
        		<script>
        document.getElementById("Shashank").addEventListener("click", function(){
                document.getElementById("Shashank-Nobita").style.display = "block";
            })
        document.querySelector(".close-btn4").addEventListener("click", function(){
                document.getElementById("Shashank-Nobita").style.display = "none";
            })
        </script>
            </div>
        </div>
    </div>

<!--  ###########################################################################################################  -->

<!--    # Back to top Button #    -->
    <div>
        <a class="backto-top" href="#"><i class="fa fa-chevron-up" aria-hidden="true"></i></a>
    </div>

<!--  ###########################################################################################################  -->

<!-- Footer of the page   -->
        <div class="footer-main-div">
		<!-- Footer icons -->
            <div class="footer-social-icons">
                <ul>
				    <li> <a class="facebook" href="#" target="_blank"> <i class="fa fa-facebook-square"></i> </a> </li>
				    <li> <a class="twitter" href="#" target="_blank"> <i class="fa fa-twitter"></i> </a> </li>
				    <li> <a class="instagram" href="#" target="_blank"> <i class="fa fa-instagram"></i> </a> </li>
				    <li> <a class="snapchat" href="#" target="_blank"> <i class="fa fa-snapchat-ghost"></i> </a> </li>
				    <li> <a class="quora" href="#" target="_blank"> <i class="fa fa-quora"></i> </a> </li>
				    <li> <a class="linked-in" href="#" target="_blank"> <i class="fa fa-linkedin-square"></i> </a> </li>
				    <li> <a class="reddit" href="#" target="_blank"> <i class="fa fa-reddit-alien"></i> </a> </li>
				    <li> <a class="whatsapp" href="#" target="_blank"> <i class="fa fa-whatsapp"></i> </a> </li>
				    <li> <a class="youtube" href="#" target="_blank"> <i class="fa fa-youtube-play"></i> </a> </li>
                </ul>
            </div>
<!-- Footer menu -->
            <div class="footer-menu-one" id="staticMenu">
				<ul>
					<li class="footerhome">
                        <a href="index.html">
                            <span class="change-icon">
                                <i id="icons_nested" class="fa">Home</i>
                                <i class="fa fa-home"></i>
                            </span>
                        </a>
                    </li>
					<li class="footerAboutUs">
                        <a href="#">
                            <span class="change-icon">
                                <i id="icons_nested" class="fa">About Us</i>
                               <i class="fa fa-info-circle" aria-hidden="true"></i>
                            </span>
                        </a>
                    </li>
					<li class="footerServices">
                        <a href="#">
                            <span class="change-icon">
                                <i id="icons_nested" class="fa">Services</i>
                                <i class="fa fa-headphones" aria-hidden="true"></i>
                            </span>
                        </a>
                    </li>
					<li class="footerProducts">
                        <a href="#">
                            <span class="change-icon">
                                <i id="icons_nested" class="fa">Products</i>
                                <i class="fa fa-product-hunt" aria-hidden="true"></i>
                            </span>
                        </a>
                    </li>
					<li class="footerContactUs">
                        <a href="#">
                            <span class="change-icon">
                                <i id="icons_nested" class="fa">Contact Us</i>
                                <i class="fa fa-volume-control-phone" aria-hidden="true"></i>
                            </span>
                        </a>
                    </li>
				</ul>
            </div>
		<!-- Footer Menu two -->
            <div class="footer-menu-two">
				<ul>
					<li> <a href="#">Blog</a> </li>
					<li> <a href="#">News</a> </li>
					<li> <a href="#">Gallery</a> </li>
					<li> <a href="#">Media</a> </li>
				</ul>
            </div>
        </div>
        <div class="footer-bottom">
            <p> Designed by : <a href="https://www.instagram.com/viju_meena/">Group Members</a> </p>
            <h1><i class="fa fa-copyright" aria-hidden="true"></i>ZeusHunter Corp</h1>
            <h1>Dedicated to J.K.</h1>
        </div>

<!--  ###########################################################################################################  -->

<!--   ##############    Pre-Loader Initialization and Development class & script     ###############     -->
    <div id="extra" class="loader-wrapper">
        <div class="loader"></div>
        <div class="loaderImage">
            <img class="loaderImage" src="imageedit_1_8135409332.png">
        </div>
    </div>

<!--##### Generating preloader class & Disabling scroll when loading #####-->
    <script>
        $(window).on("load", function(){
            $('body').css('overflowY','hidden');
            setTimeout(function(){
                $(".loader-wrapper").fadeOut(4000);
                $('body').css('overflowY','auto');
            },6500);
        })
    </script>
<!--##### End of preloader class Generation Script #####-->

<!--  ###########################################################################################################  -->

<!--  Script to Generate 3D Hover Effect    -->
	<script>window.twttr = (function(d, s, id) {
	  var js, fjs = d.getElementsByTagName(s)[0],
	    t = window.twttr || {};
	  if (d.getElementById(id)) return t;
	  js = d.createElement(s);
	  js.id = id;
	  js.src = "https://platform.twitter.com/widgets.js";
	  fjs.parentNode.insertBefore(js, fjs);

	  t._e = [];
	  t.ready = function(f) {
	    t._e.push(f);
	  };

	  return t;
	}(document, "script", "twitter-wjs"));</script>
	<script src="dist/js/jquery.hover3d.js" ></script>
	<script>
		$(document).ready(function(){
			$(".project").hover3d({
				selector: ".project__card",
                shine: false,
				sensitivity: 8,
			});
		});

	</script>
<!--   ## End of Query for 3D Effect. ##   -->

</body>
</html>

