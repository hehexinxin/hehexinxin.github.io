
<!doctype html>
<html lang="zh-CN">
<head>
<meta charset="utf-8">
<meta name="Description" content="" >
<meta name="Keywords" content="" >
<title>hexingerenzan</title>
<link href="css/index.css" rel="stylesheet" type="text/css" />
<link href="css/wow.css" rel="stylesheet" type="text/css" />
<script src="js/wow.js"></script>
<script src="js/jquery-1.11.0.min.js"></script>
<script src="js/index.js"></script>
<script src="js/snap.svg-min.js"></script>
<link rel="stylesheet" type="text/css" href="css/component.css" />



	<script>
        $().ready(function(){
            $(window).scroll(function(){
                var top = $("#carousel").offset().top;
                var scrollTop = $(window).scrollTop();
                if(scrollTop > top){
                    $(".navbar").addClass("active");
                }else{
                    $(".navbar").removeClass("active");
 
                }
 
            })
        })
</script>
</head>

<body>
	<header class="navbar">
		<nav>
			<ul class="clear">
				<li><a href="#carousel">网站首页<span>Home</span></a></li>
				<li><a href="#geren">个人简介<span>Profile</span></a></li>
				<li><a href="#zuopin">作品展示<span>Works</span></a></li>
				<li><a href="#lianxi">请联系我<span>Contact</span></a></li>
			</ul>
		</nav>
	</header>
	<section class="banner contentmin" id="carousel">
		<div class="content">
		<article>
		<header>
		<p class="wow bounceInLeft" data-wow-delay=".2s">如果你有个梦想就必须去捍卫它</p>
		<div class="wow lightSpeedIn" data-wow-delay=".7s"><span>You got a dream,you gotta<br>protect it.</span></div>
		</header>
		<img src="images/jiantou.png" alt="" width="71" height="60" class="wow bounceInDown" data-wow-delay="1s" data-wow-duration="1s" >
		</article>
		</div>
	</section>
	<!-- banner end -->
	<div id="geren">
	<section>
		<div class="aboutme clear">
		<article class="wow bounceInLeft"><img src="images/about.png" alt="" width="100%"></article>
		<article class="wow bounceInRight">
				<ul class="clear">
					<li><img src="images/genren.png" alt="" width="" height="" ></li>
					<li><p>何新</p></li>
				</ul>
				<ul class="clear">
					<li><img src="images/zhiwei.png" alt="" width="" height="" ></li>
					<li><p>求职UI设计师</p></li>
				</ul>
				<ul class="clear">
					<li><img src="images/dianhua.png" alt="" width="" height="" ></li>
					<li><p>13164627050</p></li>
				</ul>
				<ul class="clear">
					<li><img src="images/qq.png" alt="" width="" height="" ></li>
					<li><p>1205529960</p></li>
				</ul>
		</article>
		</div>
	</section>
    <!-- aboutme end -->
	<section class="ditu" id="ditu">
		<img src="images/ditu.jpg" alt="" width="100%" id="image">
	</section>
    <div class="wenan">
		<h3>职业技能</h3>
		<p>熟悉整个网站的制作流程，能独立设计完成中小型网站，敏锐的市场洞察力。<br>活跃的设计思维，创新意识强。</p>
		<p>具备良好的设计、审美能力。能独立设计不同风格，美观大方的界面。<br>擅长网页设计和app设计。</p>
		<p>熟练操作Photoshop、Illustrator、Dreamweaver等设计软件，<br>熟练DIV、CSS排版。</p>
		<p>具备良好的团队精神和协作精神，良好的沟通及协作能力，工作认真、责任心强、<br>勤奋踏实、吃苦耐劳、能快速完成各项工作任务。<br>与时俱进，不断创新，不求做的最好，只求做的更好。</p>
	</div>
	</div>
	<div id="zuopin">
     <section class="zuoping">
		 <h3>作品展示</h3>
		</section>
			<section id="grid" class="grid clear">
				<a href="#" data-path-hover="m 0,0 0,47.7775 c 24.580441,3.12569 55.897012,-8.199417 90,-8.199417 34.10299,0 65.41956,11.325107 90,8.199417 L 180,0 z">
					<figure>
						<img src="img/2.png" />
						<svg viewBox="0 0 180 320" preserveAspectRatio="none"><path d="m 0,0 0,171.14385 c 24.580441,15.47138 55.897012,24.75772 90,24.75772 34.10299,0 65.41956,-9.28634 90,-24.75772 L 180,0 0,0 z"/></svg>
						<figcaption>
							<h2>Crystalline</h2>
							<p>Soko radicchio bunya nuts gram dulse.</p>
							<button>View</button>
						</figcaption>
					</figure>
				</a>
				<a href="#" data-path-hover="m 0,0 0,47.7775 c 24.580441,3.12569 55.897012,-8.199417 90,-8.199417 34.10299,0 65.41956,11.325107 90,8.199417 L 180,0 z">
					<figure>
						<img src="img/4.png" />
						<svg viewBox="0 0 180 320" preserveAspectRatio="none"><path d="m 0,0 0,171.14385 c 24.580441,15.47138 55.897012,24.75772 90,24.75772 34.10299,0 65.41956,-9.28634 90,-24.75772 L 180,0 0,0 z"/></svg>
						<figcaption>
							<h2>Cacophony</h2>
							<p>Two greens tigernut soybean radish artichoke.</p>
							<button>View</button>
						</figcaption>
					</figure>
				</a>
				<a href="#" data-path-hover="m 0,0 0,47.7775 c 24.580441,3.12569 55.897012,-8.199417 90,-8.199417 34.10299,0 65.41956,11.325107 90,8.199417 L 180,0 z">
					<figure>
						<img src="img/6.png" />
						<svg viewBox="0 0 180 320" preserveAspectRatio="none"><path d="m 0,0 0,171.14385 c 24.580441,15.47138 55.897012,24.75772 90,24.75772 34.10299,0 65.41956,-9.28634 90,-24.75772 L 180,0 0,0 z"/></svg>
						<figcaption>
							<h2>Languid</h2>
							<p>Beetroot water spinach okra water chestnut.</p>
							<button>View</button>
						</figcaption>
					</figure>
				</a>
				<a href="#" data-path-hover="m 0,0 0,47.7775 c 24.580441,3.12569 55.897012,-8.199417 90,-8.199417 34.10299,0 65.41956,11.325107 90,8.199417 L 180,0 z">
					<figure>
						<img src="img/8.png" />
						<svg viewBox="0 0 180 320" preserveAspectRatio="none"><path d="m 0,0 0,171.14385 c 24.580441,15.47138 55.897012,24.75772 90,24.75772 34.10299,0 65.41956,-9.28634 90,-24.75772 L 180,0 0,0 z"/></svg>
						<figcaption>
							<h2>Serene</h2>
							<p>Water spinach arugula pea tatsoi.</p>
							<button>View</button>
						</figcaption>
					</figure>
				</a>
				<a href="#" data-path-hover="m 0,0 0,47.7775 c 24.580441,3.12569 55.897012,-8.199417 90,-8.199417 34.10299,0 65.41956,11.325107 90,8.199417 L 180,0 z">
					<figure>
						<img src="img/1.png" />
						<svg viewBox="0 0 180 320" preserveAspectRatio="none"><path d="m 0,0 0,171.14385 c 24.580441,15.47138 55.897012,24.75772 90,24.75772 34.10299,0 65.41956,-9.28634 90,-24.75772 L 180,0 0,0 z"/></svg>
						<figcaption>
							<h2>Nebulous</h2>
							<p>Pea horseradish azuki bean lettuce.</p>
							<button>View</button>
						</figcaption>
					</figure>
				</a>
				<a href="#" data-path-hover="m 0,0 0,47.7775 c 24.580441,3.12569 55.897012,-8.199417 90,-8.199417 34.10299,0 65.41956,11.325107 90,8.199417 L 180,0 z">
					<figure>
						<img src="img/3.png" />
						<svg viewBox="0 0 180 320" preserveAspectRatio="none"><path d="m 0,0 0,171.14385 c 24.580441,15.47138 55.897012,24.75772 90,24.75772 34.10299,0 65.41956,-9.28634 90,-24.75772 L 180,0 0,0 z"/></svg>
						<figcaption>
							<h2>Iridescent</h2>
							<p>A grape silver beet watercress potato.</p>
							<button>View</button>
						</figcaption>
					</figure>
				</a>
				<a href="#" data-path-hover="m 0,0 0,47.7775 c 24.580441,3.12569 55.897012,-8.199417 90,-8.199417 34.10299,0 65.41956,11.325107 90,8.199417 L 180,0 z">
					<figure>
						<img src="img/5.png" />
						<svg viewBox="0 0 180 320" preserveAspectRatio="none"><path d="m 0,0 0,171.14385 c 24.580441,15.47138 55.897012,24.75772 90,24.75772 34.10299,0 65.41956,-9.28634 90,-24.75772 L 180,0 0,0 z"/></svg>
						<figcaption>
							<h2>Resonant</h2>
							<p>Chickweed okra pea winter purslane.</p>
							<button>View</button>
						</figcaption>
					</figure>
				</a>
				<a href="#" data-path-hover="m 0,0 0,47.7775 c 24.580441,3.12569 55.897012,-8.199417 90,-8.199417 34.10299,0 65.41956,11.325107 90,8.199417 L 180,0 z">
					<figure>
						<img src="img/7.png" />
						<svg viewBox="0 0 180 320" preserveAspectRatio="none"><path d="m 0,0 0,171.14385 c 24.580441,15.47138 55.897012,24.75772 90,24.75772 34.10299,0 65.41956,-9.28634 90,-24.75772 L 180,0 0,0 z"/></svg>
						<figcaption>
							<h2>Zenith</h2>
							<p>Salsify taro catsear garlic gram.</p>
							<button>View</button>
						</figcaption>
					</figure>
				</a>
			</section>
</div>
<footer class="footer" id="lianxi">
		     <section>
				 <article>
				 <h3><span>CONTACT</span>FOR ME</h3>
				 <p>QQ:1205529960 &nbsp;TEL:13164627050</p>
				 </article>
				 <img src="images/weixin.png" alt="微信" width="60" height="60">
			</section>
           <p>版权所有 &copy; 2019 何新个人网站  鄂ICP备10076703号-2  </p>
	</footer>
		<script>
if (!(/msie [6|7|8|9]/i.test(navigator.userAgent))){
	new WOW().init();
};
</script>
	<script>
			(function() {
	
				function init() {
					var speed = 330,
						easing = mina.backout;

					[].slice.call ( document.querySelectorAll( '#grid > a' ) ).forEach( function( el ) {
						var s = Snap( el.querySelector( 'svg' ) ), path = s.select( 'path' ),
							pathConfig = {
								from : path.attr( 'd' ),
								to : el.getAttribute( 'data-path-hover' )
							};

						el.addEventListener( 'mouseenter', function() {
							path.animate( { 'path' : pathConfig.to }, speed, easing );
						} );

						el.addEventListener( 'mouseleave', function() {
							path.animate( { 'path' : pathConfig.from }, speed, easing );
						} );
					} );
				}

				init();

			})();
		</script>
<script>


		// --------------------------------------------------
		/*!
		* FitText.js 1.1
		*
		* Copyright 2011, Dave Rupert http://daverupert.com
		* Released under the WTFPL license
		* http://sam.zoy.org/wtfpl/
		*
		* Date: Thu May 05 14:23:00 2011 -0600
		*/

		(function( $ ){

			$.fn.fitText = function( kompressor, options ) {

				// Setup options
				var compressor = kompressor || 1,
				settings = $.extend({
					'minFontSize' : Number.NEGATIVE_INFINITY,
					'maxFontSize' : Number.POSITIVE_INFINITY
					}, options);

				return this.each(function(){

					// Store the object
					var $this = $(this);

					// Resizer() resizes items based on the object width divided by the compressor * 10
					var resizer = function () {
						$this.css('font-size', Math.max(Math.min($this.width() / (compressor*10), parseFloat(settings.maxFontSize)), parseFloat(settings.minFontSize)));
					};

					// Call once to set.
					setTimeout( function(){ resizer(); } , 250 );

					// Call on resize. Opera debounces their resize by default.
					$(window).on('resize.fittext orientationchange.fittext', resizer);

				});

			};

		})( jQuery );

		// --------------------------------------------------
		// FitText init + animate to hash

		$( document ).ready( function()
		{
			// Set FitText for main heading

			$( '.fittext' ).fitText( 0.45 );

			// Scroll to hash animation

			$( function()
			{
				$( 'a[href*=#]:not([href=#])' ).click( function()
				{
					if( location.pathname.replace( /^\// , '' ) == this.pathname.replace( /^\// , '' ) && location.hostname == this.hostname )
					{
						var target = $( this.hash );
						target = target.length ? target : $( '[name='+this.hash.slice( 1 )+']' );
						if( target.length )
						{
							$( 'html,body' ).stop().animate(
							{
								scrollTop:target.offset().top - 120
							} , 1000 );
							return false;
						}
					}
				});
			});

		});

		// --------------------------------------------------

	</script>

</body>
</html>
