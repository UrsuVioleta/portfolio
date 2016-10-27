# portfolio
<!DOCUMENT html>
<html lang="ru">
	<head>
		<meta charset="utf-8">
		<meta name="description" content="My portfolio front-end developer">
		<meta name="keywords" content="portfolio,front-end,developer">
		<title>Front-end developer</title>
		<link rel="stylesheet" href="css/index.css">
		<link rel="stylesheet" href="css/reset.scss">
		<link rel="stylesheet" href="css/animate.min.css"/>
		<script type="text/javascript" src="js/wow.min.js"></script>
		<!-- Подключение jquery библиотеки -->
		<script src="http://ajax.googleapis.com/ajax/libs/jquery/1/jquery.min.js"></script>
		<!-- test-->
		<script>
			$(document).ready(function(){
				$("#my-test2").addClass("rotateInDownLeft");
				$(window).scroll(function(){
					if($(this).scrollTop()>200){
						$("#my-test2").removeClass("rotateInDownLeft");
						$("#my-test2").addClass("rotateOutUpLeft");
					}
					else{
						$("#my-test2").removeClass("rotateOutUpLeft");
						$("#my-test2").addClass("rotateInDownLeft");
					};
					if($(this).scrollBottom()>200){
						$("#my-test2").removeClass("rotateInDownLeft");
						$("#my-test2").addClass("rotateOutUpLeft");
					}
					else{
						$("#my-test2").removeClass("rotateOutUpLeft");
						$("#my-test2").addClass("rotateInDownLeft");
					};
				});
			});
		</script>
	</head>
	<body>
		<div id="my-portfolio">
			<header>
				<div id="border-top"></div>
			</header>
			<div>
				<div id="background-video">
					<video id="media" width="100%" height="auto" preload autoplay loop>
						<source src="video/sea.mp4"></source>
						<source src="video/sea2.ogv"></source>
					</video>	
				</div>
				<div id="fon">
				<!-- wow rotateInDownLeft--><!--wow rotateOutUpLeft" data-wow-offset="300"-->
					<div class="wrapper">
						<div id="my-test"><!--class="wow rotateInDownLeft"-->
							<div id="my-test2" class="wow">
							<div id="home-content">
								<div id="title-name">
									<div id="div-top"><p id="online"><a href="#">Online/</a><a href="#">Offline</a></p>
							</div>
								<div id="me-photo">
									<img src="img/me2.jpg" alt=""/>
								</div>
								<div id="name">
									<p>Violeta Ursu</p>
									<div class="border-for-name"></div>
									<a href="#"><p>Front-end Developer</p></a>
								</div>
							</div>
							<div id="double">
							<aside id="works-menu">
									<div id="menu">
										<div id="top-blocks">
											<a href="#"><img src="img/proects2.png" alt=""/></a>
											<a href="#"><img src="img/cv1.png" alt=""/></a>
										</div>
										<div id="bottom-blocks">
											<a href="#"><img src="img/new1.png" alt=""/></a>
											<a href="#"><img src="img/contacts1.png" alt=""/></a>
										</div>
									</div>
									<div id="block0">
								<div id="block"></div>
								<div id="block1"></div>
								</div>
							</aside>
							<div id="content-text">
								<section id="hello">
									<div>
										<h1>Hello!</h1>
										<p>Давно выяснено, что при оценке дизайна 
										и композиции читаемый текст мешает 
										сосредоточиться. Lorem Ipsum используют 
										потому, что тот обеспечивает более или 
										менее стандартное заполнение шаблона, а 
										также реальное распределение букв и пробелов
										в абзацах, которое не получается при простой 
										дубликации "Здесь ваш текст.. Здесь ваш текст.. 
										Здесь ваш текст.."</p>
									</div>
								</section>
							</div>
							</div>
							</div>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
		<div id="my-works">
		<div id="point-works">
			<ul class="point">
			<a href="#"><li>Home</li></a>
			<a href="#"><li>Works</li></a>
			<a href="#"><li>CV</li></a>
			<a href="#"><li id="last">Contacts</li></a>
			</ul>
		</div>
		<div class="container">
			<div id="top-block-works">
				<div><a href="#"><img class="only" src="img/me2.jpg" alt=""/></a></div>
				<div class="double">
					<div><a href="#"><img src="img/me2.jpg" alt=""/></a></div>
					<div><a href="#"><img src="img/me2.jpg" alt=""/></a></div>
				</div>
			</div>
			<div id="bottom-block-works">
				<div><a href="#"><img class="only" src="img/me2.jpg" alt=""/></a></div>
				<div class="double">
					<div><a href="#"><img src="img/me2.jpg" alt=""/></a></div>
					<div><a href="#"><img src="img/me2.jpg" alt=""/></a></div>
				</div>
			</div>
		</div>
		</div>
		<div id="footer-bottom">
			<footer> copiright</footer>
		</div>
		<script type="text/javascript">
			new WOW().init();
		</script>
	</body>
</html>
