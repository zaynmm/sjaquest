# sjaquest

html {
	background:#505D6E url(../images/body4.jpg) no-repeat center center fixed; 
	min-height:100%;
	-webkit-background-size: cover;
	   -moz-background-size: cover;
	     -o-background-size: cover;
	        background-size: cover;
}

body {
	background:transparent;
	min-height:100%; 	
	-webkit-font-smoothing: antialiased;
	-webkit-overflow-scrolling: touch;
	line-height: 1.5em;
	font-size:14px;
	font-family: Helvetica, Arial, sans-serif;
	color:#fff;
	color:rgba(255,255,255,.8); 
	font-weight: normal;
}


/********************************************************/
/*                    Navigation bar                    */
/********************************************************/
.mainmenu { z-index: 999999; width:100%;  padding: 30px 0 0 0;}
@media (min-width: 768px) {
	.mainmenu { position: fixed; }
}

.navbar-toggle {
	position:relative;
	float:left;
	display:block;
	padding: 9px 10px;
	background: rgba(255, 255, 255, 0.2);
	background-image: none;
	border: 0 none;
	top:0px; 
	-webkit-border-radius: 2px;
	   -moz-border-radius: 2px;
	        border-radius: 2px;
	outline: 0;
	opacity: 1;
	-webkit-transition: all .45s;
	   -moz-transition: all .45s;
	        transition: all .45s;
	        float: left;
}
.navbar-toggle .icon-bar {
  display: block;
  width: 22px;
  height: 2px;
  background: #fff;
}
.navbar-toggle .icon-bar + .icon-bar {
	margin-top: 4px;
}
.open .navbar-toggle { 
	top:-70px; 
	opacity: 0;  
}
.mainmenu .dropdown-menu {
	top: -14em;
	left: 0px;
	font-size: 13px;
	padding:0;
	background:none;
	border:0 none;
	border-radius: 2px;
	-webkit-box-shadow: none;
	box-shadow: none;
	display:block;
	opacity:0;
	-webkit-transition: all .45s;
	   -moz-transition: all .45s;
	        transition: all .45s;
}
.mainmenu .dropdown-menu .active { 
	font-weight:bold;
}
.mainmenu .open .dropdown-menu { 
	top:2px;
	opacity:1;
}
.mainmenu .dropdown-menu a { 
	padding:10px 10px;
	margin:0;
	color:white;
	text-decoration: none;
	-webkit-border-radius: 2px;
	   -moz-border-radius: 2px;
	        border-radius: 2px;
}
.mainmenu .dropdown-menu a:hover { 
	background:rgba(255,255,255,.1);
	color:white;
	padding:10px 8px 10px 12px;
}



/********************************************************/
/*             Sections - universal classes             */
/********************************************************/
.section { 
	z-index: 1;
	min-height:420px;
	width: 100%; 
	overflow:auto;
	height:100%;
	padding-top:100px;
	padding-bottom:50px; 
	display:none;
	top:0;
} 
@media (min-width: 768px) {
	.section { padding-top:160px;}
}

/* Show one of sections */
#head { 
	display: block;
}


/********************************************************/
/*                      Typography                      */
/********************************************************/
a { color:#fff; text-decoration: none; }
a:hover, a:active { color:#fff; text-decoration: underline; }
.lead { 
	font-weight:normal;
	font-size:1.5em;
	line-height:1.2em;
}

.title,
.subtitle { 
	font-family: 'Wire One', Helvetica, Arial, sans-serif;
	font-weight:normal;
	font-size:7em;
	margin-bottom:15px; 
	color:#FDF9F4; 
	line-height:1em;
}
.subtitle { 
	line-height:.9em;
	font-size:5.5em;
	margin-top:0;
	margin-bottom:40px; 
}
.tagline { 
	font-size:1.4em;
	line-height:1.3em;
	font-weight:normal;
	margin-bottom:75px;
}

@media (max-width: 767px) {
	.lead { 
		font-size:1.3em;
	}
}


/********************************************************/
/*                   UI - Buttons                       */
/********************************************************/
.btn{
	color:#333;
	text-shadow: none;
	text-decoration: none;
	-webkit-border-radius: 3px;
	-moz-border-radius: 3px;
	border-radius: 3px;
	border:0 none;
}
.btn:hover {
	color:#000;
}
.btn-lg { 
	padding:16px 30px;
	font-size:inherit;
}

.btn-link {
	color:rgba(255,255,255,.8);
}
.btn-link:hover, .btn-link:focus, .btn-link:active {
	color:#fff
}
.btn-default {
	background: rgba(255,255,255,.5);
}
.btn-default:hover, .btn-default:focus, .btn-default:active, .btn-default.active {
	background: rgba(255,255,255,.8);
}
.btn-primary {
	background: rgba(255,255,255,.2);
}
.btn-primary:hover, .btn-primary:focus, .btn-primary:active, .btn-primary:active {
	background: rgba(255,255,255,.5);
}



/********************************************************/
/*                 UI - Thumbnails                      */
/********************************************************/
.thumbnail {
	background-color: rgba(255,255,255,.2);
	border: 0 none;
	padding:10px;
	-webkit-border-radius: 2px;
	   -moz-border-radius: 2px;
	        border-radius: 2px;
}
.thumbnail .caption {
	color: inherit;
}



/********************************************************/
/*                 Everything else                      */
/********************************************************/

.list-social .btn { 
	font-size:1.3em; 
}
.list-social .btn:hover, .list-social .btn:active, .list-social .btn:focus { 
	text-decoration: none; 
}


/* Social buttons in the footer */
#social { 
	margin-top:50px;
	margin-bottom:50px;
}
#social .wrapper { 
	width:340px; 
	margin:0 auto;
}
