<script></script>

<template>
    <div class="main-area center-text" style="background-image:url(assets/pexels-gdtography-277628-911738.jpg);">
		<div class="display-table">
			<div class="display-table-cell">
				
				<h1 class="title font-white"><b>Hi! I'm Veronique</b></h1>
				<p class="desc font-white">I am currently a sr. software engineer at <a style="font-weight: 700;" href="https://research.ibm.com/people/veronique-demers" target="_blank">IBM Research</a>, in the MIT-IBM Watson AI Lab.</p>
				<p class="desc font-white">On my day to day, I work on cool problems with the best people. 
                    I develop applications and systems that empower others to focus on their work, not on the noise. 
                    I also work with researchers to create prototypes showing how research can be apply to industry.
                </p>
				<p class="desc font-white">When I'm not working, I like beautiful buildings and rocky hillsides.</p>
								
				<ul class="social-btn font-white">
					<li><a href="https://github.com/vedem1192" target="_blank">github</a></li>
					<li><a href="https://www.linkedin.com/in/vedemers/" target="_blank">linkedin</a></li>
				</ul>
			</div>
		</div>
	</div>
</template>

<style scoped>


/* Screens Resolution : 992px
-------------------------------------------------------------------------- */
@media only screen and (max-width: 1200px) {

}

/* Screens Resolution : 992px
-------------------------------------------------------------------------- */
@media only screen and (max-width: 992px) {
	
	

}


/* Screens Resolution : 767px
-------------------------------------------------------------------------- */
@media only screen and (max-width: 767px) {
	
	/* ---------------------------------
	1. PRIMARY STYLES
	--------------------------------- */

	p{ line-height: 1.4; }

	h1{ font-size: 2.8em; line-height: 1; }
	h2{ font-size: 2.2em; line-height: 1.1; }
	h3{ font-size: 1.8em; }
		
	
	
}

/* Screens Resolution : 479px
-------------------------------------------------------------------------- */
@media only screen and (max-width: 479px) {

	/* ---------------------------------
	1. PRIMARY STYLES
	--------------------------------- */

	body{ font-size: 12px; }
	
}

/* Screens Resolution : 359px
-------------------------------------------------------------------------- */
@media only screen and (max-width: 359px) {
	
	
}

/* Screens Resolution : 290px
-------------------------------------------------------------------------- */
@media only screen and (max-width: 290px) {
	
	
}


html{ font-size: 100%; height: 100%; width: 100%; overflow-x: hidden; margin: 0px;  padding: 0px; touch-action: manipulation; }


body{ font-size: 16px; font-family: 'Open Sans', sans-serif; width: 100%; height: 100%; margin: 0; font-weight: 400;
	-webkit-font-smoothing: antialiased; -moz-osx-font-smoothing: grayscale; word-wrap: break-word; overflow-x: hidden; 
	color: #333; }

h1, h2, h3, h4, h5, h6, p, a, ul, span, li, img, inpot, button{ margin: 0; padding: 0; }

h1,h2,h3,h4,h5,h6{ line-height: 1.5; font-weight: inherit; }

h1,h2,h3{ font-family: 'Poppins', sans-serif; }

p{ line-height: 1.6; font-size: 1.05em; font-weight: 400; color: #555; }

h1{ font-size: 3.5em; line-height: 1; }
h2{ font-size: 3em; line-height: 1.1; }
h3{ font-size: 2.5em; }
h4{ font-size: 1.5em; }
h5{ font-size: 1.2em; }
h6{ font-size: .9em; letter-spacing: 1px; }

a, button{ display: inline-block; text-decoration: none; color: inherit; transition: all .3s; line-height: 1; }

a:focus, a:active, a:hover,
button:focus, button:active, button:hover,
a b.light-color:hover{ text-decoration: none; color: #E45F74; }

b{ font-weight: 500; }

img{ width: 100%; }

li{ list-style: none; display: inline-block; }

span{ display: inline-block; }

button{ outline: 0; border: 0; background: none; cursor: pointer; }

b.light-color{ color: #444; }

.icon{ font-size: 1.1em; display: inline-block; line-height: inherit; }

[class^="icon-"]:before, [class*=" icon-"]:before{ line-height: inherit; }

*, *::before, *::after {
    -webkit-box-sizing: inherit;
    box-sizing: inherit;
}

*, *::before, *::after {
    -webkit-box-sizing: inherit;
	box-sizing: inherit;} 

	
/* ---------------------------------
2. COMMONS FOR PAGE DESIGN
--------------------------------- */

.center-text{ text-align: center; } 

.display-table{ display: table; height: 100%; width: 100%; }

.display-table-cell{ display: table-cell; vertical-align: middle; }



::-webkit-input-placeholder { font-size: .9em; letter-spacing: 1px; }

::-moz-placeholder { font-size: .9em; letter-spacing: 1px; }

:-ms-input-placeholder { font-size: .9em; letter-spacing: 1px; }

:-moz-placeholder { font-size: .9em; letter-spacing: 1px; }


.full-height{ height: 100%; }

.position-static{ position: static; }

.font-white{ color: #fff; }


/* ---------------------------------
3. MAIN SECTION
--------------------------------- */

.main-area{ 
    position: relative; 
    height: 100vh; 
    z-index: 1; 
    padding: 0 20px; 
    background-size: cover; 
    background-position: center top;
    color: #fff; 
}

.main-area:after{ content:''; position: absolute; top: 0; bottom: 0;left: 0; right: 0; z-index: -1;  
	opacity: .4; background: #000; }

.main-area .desc{ margin: 20px auto; max-width: 500px; }
	
.main-area .notify-btn{ padding: 13px 35px; border-radius: 50px; border: 2px solid #F84982;
	color: #fff; background: #F84982; }

.main-area .notify-btn:hover{ background: none; }

.main-area .social-btn{ position: absolute; bottom: 40px; width: 100%; left: 50%; transform: translateX(-50%); }

.main-area .social-btn > li > a{ margin: 0 10px; padding-bottom: 7px; position: relative; overflow: hidden; }

.main-area .social-btn > li > a:after{ content:''; position: absolute; bottom: 0; left: 0; right: 0; 
	transition: all .2s; height: 2px; background: #F84982; }

	
.main-area .social-btn > li > a:hover:after{ transform: translateX(100%); }


</style>