# emiia.gihub.io
ЭМИИА
<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html expr:dir='data:blog.languageDirection' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'>
  <head>
<meta content='nlXisRKGZbZ5jSGB1dkBkFVxzgX13T1S01VbIztWT5c' name='google-site-verification'/>
<meta content='nlXisRKGZbZ5jSGB1dkBkFVxzgX13T1S01VbIztWT5c' name='google-site-verification'/>
    <b:include data='blog' name='all-head-content'/>
    <title><data:blog.pageTitle/></title>
    <meta expr:content='data:blog.metaDescription' name='description'/>
<meta content='c23600c5cfbf220d' name='yandex-verification'/>
<meta content='4b050d625214ad2b' name='yandex-verification'/>
 <meta content='width=device-width,initial-scale=1,minimum-scale=1,maximum-scale=1' name='viewport'/>
<meta content='2a3fd1b287cdead986289cce5e6bed61' name='p:domain_verify'/>
<meta content='4fb89592f35c40d932c25945b0def1c5' name='p:domain_verify'/>
<meta content='ba3dc2c41b4245c9b2b39a3eb76701bc' name='p:domain_verify'/>
<link href='http://fonts.googleapis.com/css?family=Bad+Script|Raleway:400,500,600,700,300|Lora:400' rel='stylesheet' type='text/css'/>	
   
 <b:skin><![CDATA[
	
	/*
-----------------------------------------------
EMIIA ЭМИИА
Name:     ЭМИИА 
Designer: EMIIA
URL:      http://www.emiia.ru
Version:  ЭМИИА Технологическая компания ЭМИИА
----------------------------------------------- */



/* Global reset */
/* Based upon 'reset.css' in the Yahoo! User Interface Library: http://developer.yahoo.com/yui */
*, html, body, div, dl, dt, dd, ul, ol, li, h1, h2, h3, h4, h5, h6, pre, form, label, fieldset, input, p, blockquote, th, td { margin:0; padding:0 }
table { border-collapse:collapse; border-spacing:0 }
fieldset, img { border:0 }
address, caption, cite, code, dfn, em, strong, th, var { font-style:normal; font-weight:normal }
ol, ul, li { list-style:none }
caption, th { text-align:left }
h1, h2, h3, h4, h5, h6 { font-size:100%; font-weight:normal }
q:before, q:after { content:''}

/* Global reset-RESET */
strong { font-weight: bold }
em { font-style: italic }
a img { border:none } /* Gets rid of IE's blue borders */
body#layout #header {   	
	margin-bottom: 80px;
	clear:both;
}


body#layout #navigation {
    height: auto;
    margin-bottom: 60px;
    margin-top: 30px;
    position: relative;
    width: 100%;
    z-index: 999999;
}

body#layout #navigation-wrapper {
    width:40%;
	float:left;
}
body#layout #top-social {
    width:40%;
	float:right;
}
body#layout #widget-area .footerwidget {
	width:250px;
	 margin-right: 20px;
}
body#layout #widget-area .widget, body#layout #sidebar .widget {
	width:250px;
}

body#layout div#Header1:before {
  content: "This is a property of EMIIA.ru";
}

body {
	  color: #777;
  font-family: Arial;
  font-size: 14px;
  font-weight: 400;
  font-style: normal;
  line-height: 1.75;
  letter-spacing: 0px;
  text-transform: none;
	background-color:#FFF;
}

p {
	font-size:16px;
	line-height:26px;
}

a {
	text-decoration:none;
	color:#cea525;
}
a:hover {
	
}

h1,h2,h3,h4,h5,h6 {
	font-family:"Open Sans", sans-serif;
}

.container {
	width:1030px;
	margin:0 auto;
}
.container.sp_sidebar {
	overflow:hidden;
}

#main {
	width:100%;
}

.container.sp_sidebar #main {
	width:675px;
	margin-right:30px;
	float:left;
}
#sidebar {
	width:312px;
	float:right;
  margin-top: 8px;
}

/********************************/
/*** Navigation ***/
/********************************/

#navigation {
	background:#171717;
	height:48px;
	position:fixed;
	z-index:999999;
	width:100%;
	-webkit-backface-visibility: hidden;
}
	
.slicknav_menu {
	display:none;
}	

	#navigation .container {
		position:relative;
	}
	
.menu {
	float:left;
}

.menu li {
	display:inline-block;
	margin-right:12px;
	position:relative;
}

.menu li a {
	font-family:"Open Sans", sans-serif;
	font-size:11px;
	font-weight:400;
	letter-spacing:2px;
	color:#fff;
	line-height:48px;
	text-transform:uppercase;
	display:inline-block;
	-o-transition:.3s;
		-ms-transition:.3s;
		-moz-transition:.3s;
		-webkit-transition:.3s;
}

ul.sub-menu li:after {
  content: "|";
  padding-left: 10px;
  color: #565656;
  display: none;
}

		/*** DROPDOWN ***/
		
		.menu .sub-menu,
		.menu .children {
			background-color: #171717;
			display: none;
			padding: 0;
			position: absolute;
			margin-top:0;
			left: 0;
			z-index: 99999;
			
		}
		
		ul.menu ul a,
		.menu ul ul a {
			color: #999;
			margin: 0;
			padding: 6px 10px 7px 10px;
			min-width: 160px;
			line-height:20px;
			-o-transition:.25s;
			-ms-transition:.25s;
			-moz-transition:.25s;
			-webkit-transition:.25s;
			transition:.25s;
			border-top:1px solid #333;
		}
		
		ul.menu ul li,
		.menu ul ul li {
			padding-right:0;
			margin-right:0;
		}

		ul.menu ul a:hover,
		.menu ul ul a:hover {
			color: #fff;
			background:#333;
		}

		ul.menu li:hover > ul,
		.menu ul li:hover > ul {
			display: block;
		}
		
		.menu .sub-menu ul,
		.menu .children ul {	
			left: 100%;
			top: 0;
			
		}
	
	/** Search **/
	#top-search {
		position:absolute;
		right:0;
		top:0;
		width:48px;
		text-align:center;
		margin-left:16px;
	}
	#top-search a {
		height:48px;
		font-size:14px;
		line-height:48px;
		color:#999;
		background:#353535;
		display:block;
		-webkit-transition: all 0.2s linear;
        -moz-transition: all 0.2s linear;
        -ms-transition: all 0.2s linear;
         -o-transition: all 0.2s linear;
            transition: all 0.2s linear;
	}
	#top-search a:hover {
		color:#ccc;
		background:#474747;
	}
	.show-search {
		position:absolute;
		top:48px;
		right:-1px;
		display:none;
		z-index:10000;
	}
	.show-search #searchform input#s {
		width:190px;
		background:#FFF;
		webkit-box-shadow: 0 8px 6px -6px rgba(206,206,206,.2);
		-moz-box-shadow:  0 8px 6px -6px rgba(206,206,206,.2);
	    box-shadow:  0 8px 6px -6px rgba(206,206,206,.2);
	}
	.show-search #searchform input#s:focus {
		border:1px solid #d5d5d5;
	}
	
	/*** Top Social ***/
	#top-social {
		text-align:center;
		right:66px;
		top:0;
	}
	#top-social a i {
		font-size:14px;
		margin-left:10px;
		line-height:48px;
		color:#e6c55d;
		-webkit-transition: all 0.2s linear;
        -moz-transition: all 0.2s linear;
        -ms-transition: all 0.2s linear;
         -o-transition: all 0.2s linear;
            transition: all 0.2s linear;
	}

/********************************/
/*** Header ***/
/********************************/

#header {
	padding-top:48px;
	border-bottom:1px solid transparent;
	
}

#logo {
	text-align:center;
	padding:30px 0;
}
 

/** Featured area **/
.featured-area {
	margin-bottom: 50px;
  padding-bottom: 10px;
  margin-top: -70px;
  border-bottom: 1px solid rgba(34,34,34,0.1);
}



/********************************/
/*** Grid Item ***/
/********************************/

/* grid title */
.sp-grid-title {
	margin-bottom:45px;
	text-align:center;
}
.sp-grid-title h3 {
	font-size: 26px;
	font-weight: 400;
	text-transform: uppercase;
	letter-spacing:4px;
	margin-bottom:4px;
}
.sp-grid-title .sub-title {
	font-size: 18px;
	font-style: italic;
	color: #999;
}

.sp-grid li {
	display: inline-block;
	vertical-align: top;
	width: 300px;
	margin-right: 16px;
	margin-bottom: 45px;
}

	.container.sp_sidebar .sp-grid li {
		width:315px;
	}
	.container.sp_sidebar .sp-grid li:nth-child(3n+3) {
		margin-right:16px;
	}
	.container.sp_sidebar .sp-grid li:nth-child(2n+2) {
		margin-right:0;
	}
	
	
.sp-grid li:nth-child(3n+3) {
	margin-right:0;
}

.sp-grid li .item img {
	width:100%;
	height:auto;
	margin-bottom:10px;
}

.sp-grid li .item .cat {
	font-size: 11px;
	font-weight: 700;
	letter-spacing: 1px;
	text-transform: uppercase;
	font-family:"Open Sans";
	margin-bottom:7px;
	display:block;
}
.sp-grid li .item .cat a:hover {
	text-decoration:underline;
}
.sp-grid li .item h2 {
	margin-bottom:8px;
}
.sp-grid li .item h2 a {
	font-size: 15px;
	color: #000000;
	text-transform: uppercase;
	letter-spacing: 1px;
	font-weight: 700;
	-o-transition:.3s;
	-ms-transition:.3s;
	-moz-transition:.3s;
	-webkit-transition:.3s;
}
.sp-grid li .item h2 a:hover {
	opacity:.5;
}
.sp-grid li .item p {
	margin-bottom:6px;
}
.sp-grid li .item .date {
	font-size: 13px;
	color: #999;
	letter-spacing: 1px;
	font-style: italic;
}


/********************************/
/*** Post ***/
/********************************/

.post {
	margin-bottom:100px;
}
.single .post {
	margin-bottom:70px;
}
	
	/*** Post Header ***/
	.post-header {
		margin-bottom:27px;
		text-align:center;
	}

	.post-header .cat a {
		    font-size: 22px;
  font-weight: 400;
  font-style: normal;
  line-height: 1.25;
  letter-spacing: 0px;
  text-transform: none;
  color: #aaa;
  font-family: 'Bad Script', cursive;
	}
	.post-header .cat a:hover {
		text-decoration:underline;
	}

	.post-header h1, .post-header h2 { margin-bottom:8px; }

	.post-header h1 a, .post-header h2 a, .post-header h1 {
		  font-family: Raleway;
  font-size: 30px;
  font-weight: 400;
  font-style: normal;
  line-height: 1.25;
  letter-spacing: 3px;
  text-transform: uppercase;
color: #222;
	}
	.post-header h2 a:hover {
		opacity:.50;
	}

	.post-header .date {
visibility:hidden;
  text-transform: uppercase;
  letter-spacing: 1px;
  color: #aaa;
  margin-right: 5px;
  font-size: 11px;
  font-family: Lora;
	}
	
	/*** Post image ***/
	.post-image {
		margin-bottom:18px;
	}
	.post-image img {
		max-width:100%;
		height:auto;
	}
	
	.post-image.audio iframe {
		height:166px;
	}
	
	.container.sp_sidebar .post-image.audio iframe {
			width:650px;
			height:auto;
		}
	
	/*** Post Entry ***/
	.post-entry {
		  text-align: justify;
	}
	
	.post-entry img {
		max-width:100%;
		height:auto;
	}
	
	.post-entry p {
		margin-bottom:20px;
  text-align: justify;
	}
	
	.post-entry a.more-link {
		  display: inline-block;
  padding: 6px 12px;
  margin-bottom: 0;
  font-size: 14px;
  font-weight: 400;
  margin-top: 20px;
  line-height: 1.42857143;
  text-align: center;
  white-space: nowrap;
  vertical-align: middle;
  -ms-touch-action: manipulation;
  touch-action: manipulation;
  cursor: pointer;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  background-image: none;
  border: 1px solid rgba(34,34,34,0.08);
  border-radius: 1px;
  text-transform: uppercase;
  line-height: 1.75;
  color: #777!important;
	}
	.post-entry a:hover {
		text-decoration:underline;
	}
	
	.post-entry p, .post-entry h1, .post-entry h2, .post-entry h3, .post-entry h4, .post-entry h5, .post-entry h6, .post-entry hr {
	margin-bottom:20px;
	}
	.post-entry h1, .post-entry h2, .post-entry h3, .post-entry h4, .post-entry h5, .post-entry h6 {
		color:#000;
		font-weight:700;
	}
	.post-entry h1 {
		font-size:30px;
	}
	.post-entry h2 {
		font-size:27px;
	}
	.post-entry h3 {
		font-size:24px;
	}
	.post-entry h4 {
		font-size:20px;
	}
	.post-entry h5 {
		font-size:18px;
	}
	.post-entry h6 {
		font-size:16px;
	}
	.post-entry hr {
		border:0;
		height:0;
		border-bottom:1px solid #e5e5e5;
		clear:both;
	}
	.post-entry blockquote p {
		border-left:3px solid #cea525;
		color:#999;
		padding:0 18px;
		font-family:"Georgia";
		font-size:18px;
		line-height:28px;
		font-style:italic;
	}

	.post-entry ul, .post-entry ol {
		padding-left:45px;
		margin-bottom:20px;
	}
	.post-entry ul li {
		margin-bottom:12px;
		list-style:square;
	}
	.post-entry ol li {
		margin-bottom:12px;
		list-style:decimal;
	}


	.sticky.post .post-header { border:1px dashed #ddd; padding:20px 0; }
	.bypostauthor  {}

	.post-entry table { width:100%; margin-bottom:22px; border-collapse:collapse }
	.post-entry td, .post-entry th { padding: 12px; border-bottom: 1px #e5e5e5 solid; }
	.post-entry th { font-weight:bold; font-size:14px; background:#f5f5f5;}
	.post-entry tr:hover {
		background:#f9f9f9;
	}
	
	/*** Post Share ***/
	.post-share {
		text-align:center;
		margin-top:40px;
		margin-bottom:100px;
		background:url(http://1.bp.blogspot.com/-RaxSFprHuWw/U-eh4Hd6OgI/AAAAAAAAAP0/sijBcrNVTjo/line.gif) repeat-x center center;
	}
	.post-share a {
		display:inline-block;
	}
	.share-box {
		width:55px; 
		height:42px; 
		background:#fff;
		border:1px solid #e5e5e5; 
		
		display:inline-block;
		line-height:42px;
		margin:0 10px;
		-o-transition:.3s;
		-ms-transition:.3s;
		-moz-transition:.3s;
		-webkit-transition:.3s;
	}
	.share-box i {
		
		font-size:14px;
	}
	
	.share-box:hover {
		background:#171717;
		border:1px solid #171717;
	}
	
	/*** Post author ***/
	.post-author {
visibility:hidden;
		margin-bottom:80px;
		margin-top:70px;
		overflow:hidden;
  border-bottom: 1px solid rgba(34,34,34,0.1);
  padding-bottom: 40px;
  margin-bottom: 40px;
	}	
	
	.author-img {
		float:left;
		margin-right:30px;
	}
	
	.author-img img {
		border-radius:50%;
	}
	
	.author-content h5 a {
		font-size:14px;
		letter-spacing:2px;
		text-transform:uppercase;
		margin-bottom:8px;
		color:#000;
		display:block;
	}
	
	.author-content p {
		margin-bottom:8px;
	}
	
	.author-content .author-social {
		font-size:14px;
		color:#bbb;
		margin-right:8px;
	}
	
	/*** Post related ***/
	.post-related {
		overflow:hidden;
		margin-bottom:80px;
		margin-top:70px;
	}
	
	.post-box { text-align:center; }
	.post-box-title {
		  padding-bottom: 3px;
  display: inline-block;
  margin-top: 0;
  font-family: Raleway;
  font-size: 24px;
  font-weight: 400;
  font-style: normal;
  line-height: 1.25;
  letter-spacing: 3px;
  text-transform: uppercase;
  text-align: center;
  color: #222;
  margin-bottom: 20px;
	}
	
	.item-related {
		width:292px;
		float:left;
		margin-right:32px;
	}
	
	.item-related:last-child { margin-right:0; }
	
		.container.sp_sidebar .item-related{
			width:212px;
			margin-right:19px;
		}
		.container.sp_sidebar .item-related:last-child {
			margin-right:0;
		}
	
	.item-related img {
		margin-bottom:6px;
		width:100%;
		height:auto;
	}
	.item-related h3 a {
		font-size:14px;
		text-transform:uppercase;
		letter-spacing:2px;
		color:#000;
  display: block;
  font-weight: bold;
  color: #222;
	}
	.item-related h3 a:hover {
		text-decoration:underline;
	}
	.item-related span.date {
		font-size:10px;
		font-family:"Open Sans", sans-serif;
		text-transform:uppercase;
		font-style:italic;
		color:#999;
	}
	
	/** Post tags ***/
	.post-tags {
		margin-top:30px;
		margin-bottom:50px;
	}
	.post-tags a {
		font-family:"Open Sans", sans-serif;
		font-size:11px;
		letter-spacing:2px;
		text-transform:uppercase;
		background:#f2f2f2;
		color:#666;
		padding:7px 10px 8px;
		margin-right:6px;
		border-radius:2px;
		margin-bottom:5px;
		display:inline-block;
	}
	.post-tags a:hover {
		background:#333;
		color:#fff;
		text-decoration:none;
	}
	
	/*** Post Pagination ***/
	.post-pagination {
		overflow:hidden;
	}
	.post-pagination .prev-post {
		float:left;
		width:470px;
	}
	.post-pagination .next-post {
		float:right;
		text-align:right;
		width:470px;
	}
	
		.container.sp_sidebar .post-pagination .prev-post, .container.sp_sidebar .post-pagination .next-post {
			width:325px;
		}
	
	.post-pagination span {
		color:#999;
		font-size:16px;
		font-style:italic;
		letter-spacing:1px;
	}
	.post-pagination .arrow {
		font-size:64px;
		color:#ddd;
		line-height:64px;
	}
	.post-pagination .prev-post .arrow {
		float:left;
		margin-right:18px;
	}
	.post-pagination .next-post .arrow {
		float:right;
		margin-left:18px;
	}
	.pagi-text {
		margin-top:11px;
	}
	.post-pagination h5 {
		text-transform:uppercase;
		letter-spacing:2px;
		font-size:14px;
	}
	.post-pagination a {
		color:#999;
	}
	.post-pagination a:hover > .arrow, .post-pagination a:hover > .pagi-text span, .post-pagination a:hover {
		color:#000;
	}


.site-social-networks.show-title li {
  text-align: center;
  width: 32.2222%;
}
 .site-social-networks li {
  display: inline-block;
  padding: 0;
}
 .site-social-networks.show-title a {
  margin: 20px auto 0 auto;
  text-transform: uppercase;
  font-size: 10px;
}

 .site-social-networks.show-title i {
  display: block;
  margin: 0 auto 10px auto;
}

 .site-social-networks.style-default i {
  width: 32px;
  height: 32px;
  margin: 0 auto;
  line-height: 32px;
  text-align: center;
  font-size: 14px;
  -webkit-border-radius: 16px;
  -moz-border-radius: 16px;
  -ms-border-radius: 16px;
  -o-border-radius: 16px;
  border-radius: 16px;
  color: #fff;
  background-color: #000;
}
	
/********************************/
/*** Pagination ***/
/********************************/

.pagination {
	margin-bottom:60px;
	overflow:hidden;
}

.pagination a {
	
	color:#999;
	
	letter-spacing:3px;
	text-transform:uppercase;
	font-size:12px;
}
.pagination a:hover {
	text-decoration:none;
	color:#000;
}
.pagination .newer {
	float:left;
}
.pagination .older {
	float:right;
}


/********************************/
/*** Footer Social ***/
/********************************/

#footer-social {
	background:#f2f2f2;
	padding:40px 0;
	text-align:center;
}

#footer-social a {
	margin:0 15px;
	color:#999;
	font-family:"Open Sans", sans-serif;
	font-size:11px;
	text-transform:uppercase;
	font-weight:700;
	letter-spacing:1px;
}
#footer-social a:first-child {
	margin-left:0;
}
#footer-social a:last-child {
	margin-right:0;
}

#footer-social a i {
	height:28px;
	width:28px;
	text-align:center;
	line-height:28px;
	background:#666;
	color:#fff;
	border-radius:50%;
	margin-right:5px;
	font-size:14px;
}

#footer-social a:hover {
	text-decoration:none;
	color:#000;
}
#footer-social a:hover > i {
	background:#000;
}

/********************************/
/*** Footer logo ***/
/********************************/

#footer-logo {
	background:#111;
	padding:60px 0;
	text-align:center;
}
#footer-logo img {
	margin-bottom:15px;
}
#footer-logo p {
	color:#777;
	font-size:15px;
	margin-bottom:0;
	font-style:italic;
}
#footer-logo p i {
	color:#646464;
	font-size:14px;
	margin:0 5px 0 7px;
}
.share-box:hover > i {
  color: #fff;
}

/********************************/
/*** Footer Copyright ***/
/********************************/

#footer-copyright {
	padding:5px 0;
	background:#000;
	overflow:hidden;
	font-family:"Arial", arial;
}

#footer-copyright p {
	font-size:9px;
	color:#EFEFEF;
	float:left;
}

#footer-copyright .to-top {
	float:right;
	margin-top:6px;
	font-size:11px;
	text-transform:uppercase;
	font-weight:700;
	letter-spacing:1px;
	color:#EFEFEF;
}
#footer-copyright .to-top i {
	font-size:14px;
	margin-left:3px;
}

#footer-copyright .to-top:hover {
	text-decoration:none;
}

/********************************/
/*** Widget Area ***/
/********************************/

#widget-area {
	overflow:hidden;
	margin-bottom:60px;
	border-top:1px solid #e5e5e5;
	padding-top:60px;
}

#widget-area .footerwidget {	
	float:left;
}
#widget-area .widget, #sidebar .widget {
		float: left;
    margin-right: 32px;
    width: 322px;
	}
	
#widget-area #container3 {
	margin-right:0px;	
}
	
	#sidebar .widget {
  width: 250px;
  margin-right: 0;
  float: none;
  margin-bottom: 30px;
  padding: 30px;
  border-width: 0px;
  border-style: solid;
  border-color: rgba(34,34,34,0.1);
	}


div#sidebar h2 span {
  display: inline-block;
  padding-left: 30px;
  padding-right: 30px;
  background-color: #fff;
}

footer#footer-copyright a {
  color: #fff;
}
	
	#sidebar img {
		max-width:250px;
	
	}
	#sidebar iframe {
		max-width:250px;
		
	}

.widget:last-child {
	margin-right:0;
}

.widget-title, #sidebar .widget h2{
	  font-family: Raleway;
  font-size: 16px;
  font-weight: 700;
  font-style: normal;
  line-height: 1.25;
  letter-spacing: 2px;
  text-transform: uppercase;
  text-align: center;
  display: block;
  margin-top: -40px;
  text-overflow: ellipsis;
  white-space: nowrap;
  overflow: hidden;
}


 #widget-area .widget h2 {
	  font-family: Raleway;
  font-size: 13px;
  font-weight: 700;
  font-style: normal;
  line-height: 1.25;
  letter-spacing: 2px;
  text-transform: uppercase;

}

	#sidebar .widget-title, #sidebar .widget h2, #widget-area .widget h2 {
		margin-bottom:20px;
	}



	#sidebar .widget ul li {
	margin-bottom:7px;
	padding-bottom:7px;
	
}
	#sidebar .widget ul li:last-child {
	margin-bottom:0;
	padding-bottom:0;
	border-bottom:none;
}


	/*** Search widget ***/
	#searchform input#s {
		border: 1px solid #e5e5e5;
		background:#fff url(img/searchsubmit.png) no-repeat 96% 13px;
		padding:14px 14px;
		font-size:11px;
		color:#999;
		letter-spacing:1px;
	}
	
	#searchform #s:focus { outline:none; }

	/** searchbar for widget ***/
	.widget #searchform input#s { 
		width:260px;
	}
	
		#sidebar .widget #searchform input#s { 
			width:230px;
		}
	
	/*** About Widget ***/
	.about-widget img {
		max-width:292px;
		height:auto;
	}
	
	
	/** Instagram widget support **/
	.instag ul.thumbnails > li {
		width:32% !important;
	}
	.instag ul.thumbnails > li img:hover {
		opacity:.8;
	}
	.instag ul li {
		margin:0;
		padding-bottom:0;
		border-bottom:none;
	}
	.pllexislider ul li {
		margin:0;
		padding-bottom:0;
		border-bottom:none;
	}
	
	/*** Tagcloud widget ***/
	
	.widget .tagcloud a {
		font-family:"Open Sans", sans-serif;
		font-size:10px;
		letter-spacing:1px;
		text-transform:uppercase;
		background:#f2f2f2;
		color:#666;
		padding:6px 8px 7px;
		margin-right:5px;
		margin-bottom:8px;
		display:inline-block;
		border-radius:2px;
	}
	.widget .tagcloud a:hover {
		background:#333;
		color:#fff;
	}
	
	/*** Calender widget ***/
	#wp-calendar {width: 100%; }
	#wp-calendar caption { text-align: right; color: #777; font-size: 12px; margin-top: 10px; margin-bottom: 15px; }
	#wp-calendar thead { font-size: 12px;  }
	#wp-calendar thead th { padding-bottom: 10px; }
	#wp-calendar tbody { color: #aaa; }
	#wp-calendar tbody td { background: #f5f5f5; border: 1px solid #fff; text-align: center; padding:8px;}
	#wp-calendar tbody td a { font-weight:700; color:#222; }
	#wp-calendar tbody td:hover { background: #fff; }
	#wp-calendar tbody .pad { background: none; }
	#wp-calendar tfoot #next { font-size: 10px; text-transform: uppercase; text-align: right; }
	#wp-calendar tfoot #prev { font-size: 10px; text-transform: uppercase; padding-top: 10px; }
	#wp-calendar thead th { padding-bottom: 10px; text-align: center; }
	
	/** WIDGET ITEMS **/
	.widget ul.side-newsfeed li {
		list-style-type:none;
		margin-bottom:17px;
		padding-bottom:13px;
		margin-left:0;
	}
	.widget ul.side-newsfeed li:last-child {
		margin-bottom:0;
		padding-bottom:0;
	}
	.widget ul.side-newsfeed li .side-item {
		overflow:hidden;
	}
	.widget ul.side-newsfeed li .side-item .side-image {
		float:left;
		margin-right:14px;
	}
	
	.widget ul.side-newsfeed li .side-item .side-image img {
		width:86px;
		height:auto;
	}
	
	.widget ul.side-newsfeed li .side-item .side-item-text {
		overflow:hidden;
	}
	.widget ul.side-newsfeed li .side-item .side-item-text h4 a {
		margin-bottom:1px;
		color:#333;
		display:block;
		font-size:14px;
	}
	.widget ul.side-newsfeed li .side-item .side-item-text .side-item-meta {
		font-size:10px;
		letter-spacing:1px;
		color:#999;
		font-style:italic;
		font-family:"Open Sans";
	}
	
	/** Social Widget **/
	.widget-social {
		text-align:center;
	}

	.widget-social a:first-child {
		margin-left:0;
	}
	.widget-social a:last-child {
		margin-right:0;
	}

	.widget-social a i {
		height:28px;
		width:28px;
		text-align:center;
		line-height:28px;
		background:#666;
		color:#fff;
		border-radius:50%;
		margin:0 2px;
		font-size:14px;
	}

	.widget-social a:hover {
		text-decoration:none;
		color:#000;
	}
	.widget-social a:hover > i {
		background:#000;
	}
	
	
/*******************************
*** COMMENTS
*******************************/
	
.post-comments {
visibility:hidden;
	margin-bottom:70px;
	margin-top:70px;
}

.comments {
	margin-bottom:40px;
}

.comment {
	border-bottom:1px dotted #eee;
	margin-top:20px;
	margin-bottom:34px;
	padding-bottom:40px;
}

.comment .avatar-image-container {
	float:left;
	
}
.comment .avatar-image-container img {
	border-radius:50%;
	width:50px;
	height:50px;
	max-width:50px;
	max-height:50px;
}
.comments .comment-block {
    margin-left: 80px;
    position: relative;
}

.comment-replies {
    margin-left: 40px;
    margin-top: 20px;
}
.comments .avatar-image-container {
    float: left;
    max-height: 50px;
    overflow: hidden;
    width: 50px;
}
.comment-replies .comment {
	border:none;
	margin-bottom:0px;
	padding-bottom:0px;
	
}
.thecomment .comment-text {
	overflow:hidden;
}
.thecomment .comment-text span.author, cite.user > a {
	display:block;
	font-size:14px;
	text-transform:uppercase;
	letter-spacing:2px;
	margin-bottom:6px;
	color:#333;
	font-family:"Open Sans";
}
.thecomment .comment-text span.author a:hover {
	text-decoration:underline;
}

span.datetime {
	font-size:14px;
	color:#999;
	font-style:italic;
	display:block;
	margin-bottom:10px;
}

.thecomment .comment-text em {
	font-size:13px;
	margin-bottom:-14px;
	display:block;
	color:orange;
	letter-spacing:1px;
}
.thecomment .comment-text em i {
	font-size:14px;
	color:#f3bd00;
}

.comment-actions a {
	float:right;
	font-size:11px;
	background-color:#aaa;
	color:#FFF;
	padding:3px 6px 5px 6px;
	border-radius:2px;
	margin-left:7px;
	font-family:"Lato";
	-o-transition:.3s;
	-ms-transition:.3s;
	-moz-transition:.3s;
	-webkit-transition:.3s;
	transition:.3s;
}
.continue a {
	float:left;
	margin-bottom:20px;
	font-size:11px;
	background-color:#aaa;
	color:#FFF;
	padding:3px 6px 5px 6px;
	border-radius:2px;
	margin-left:7px;
	font-family:"Lato";
	-o-transition:.3s;
	-ms-transition:.3s;
	-moz-transition:.3s;
	-webkit-transition:.3s;
	transition:.3s;
}
.loadmore a {
	
	font-size:11px;
	background-color:#aaa;
	color:#FFF;
	padding:3px 6px 5px 6px;
	border-radius:2px;
	margin-left:7px;
	font-family:"Lato";
	-o-transition:.3s;
	-ms-transition:.3s;
	-moz-transition:.3s;
	-webkit-transition:.3s;
	transition:.3s;
}
.post-comments span.reply a.comment-edit-link {
	background:#c5c5c5;
}
.post-comments span.reply a:hover {
	opacity:.8;
}

ul.children { margin: 0 0 0 55px; }
ul.children li.thecomment { margin:0 0 8px 0; }

/** Reply **/
#respond {
	margin-bottom:20px;
	overflow:hidden;
}

#respond  h3 {
	font-size:14px;
	color:#999;
	font-weight:400;
	margin-bottom:30px;
	font-family:"Lato";
	letter-spacing:2px;
	text-transform:uppercase;
}

#respond h3 a {
	color:#000;
	display:inline-block;
}

#respond h3 small a {
	text-transform:uppercase;
	font-size:11px;
	background:#333;
	color:#FFF;
	padding:4px 6px 5px;
	border-radius:3px;
	margin-left:7px;
	letter-spacing:1px;
	-o-transition:.3s;
	-ms-transition:.3s;
	-moz-transition:.3s;
	-webkit-transition:.3s;
	transition:.3s;
}
#respond h3 small a:hover {
	opacity:.8;
}

#respond label {
	color:#888;
	width:80px;
	font-size:14px;
	display:inline-block;
	font-weight:300;
}
#respond input {
	padding:8px 10px;
	border:1px solid #DDD;
	margin-right:10px;
	border-radius: 3px;
	color:#999;
	margin-bottom:15px;
	font-size:11px;
	width:250px;
	font-family:"Georgia";
}
#respond input:focus {outline:none;}
#respond .comment-form-url {
	margin-bottom:10px;
}
#respond textarea {
	padding:14px;
	border:1px solid #DDD;
	border-radius: 3px;
	width:95%;
	height:120px;
	font-size:13px;
	color:#777;
	margin-bottom:14px;
	line-height:20px;
	font-family:"Georgia";
}
#respond textarea:focus {outline:none;}

#respond #submit {
	font-family:"Lato";
	text-transform:uppercase;
	letter-spacing:2px;
	background:#eee;
	border-radius:0;
	font-size:11px;
	color:#666;
	padding:12px 19px 14px;
	margin-top:6px;
	display:inline-block;
	border:none;
	-o-transition:.3s;
	-ms-transition:.3s;
	-moz-transition:.3s;
	-webkit-transition:.3s;
	transition:.3s;
	cursor:pointer;
	border-radius:30px;
	width:auto;
}

#respond #submit:hover {
	background:#333;
	color:#FFF;
}

/********************************/
/*** Archive ***/
/********************************/

.archive-box {
	background:#f4f4f4;
	padding:22px 0 24px;
	text-align:center;
	margin-bottom:70px;
	margin-top:-70px;
	border-bottom:1px solid #eee;
}
.archive-box span {
	font-size:14px;
	font-style:italic;
	letter-spacing:1px;
	color:#999;
}
.archive-box h1 {
	font-size:26px;
	letter-spacing:4px;
	
	text-transform:uppercase;
}

.nothing {
	margin-bottom:90px;
	text-align:center;
}


/* =WordPress Core
-------------------------------------------------------------- */
.alignnone {
    margin: 5px 20px 20px 0;
}

.aligncenter,
div.aligncenter {
    display: block;
    margin: 5px auto 5px auto;
}

.alignright {
    float:right;
    margin: 5px 0 20px 20px;
}

.alignleft {
    float: left;
    margin: 5px 20px 20px 0;
}

.aligncenter {
    display: block;
    margin: 5px auto 5px auto;
}

a img.alignright {
    float: right;
    margin: 5px 0 20px 20px;
}

a img.alignnone {
    margin: 5px 20px 20px 0;
}

a img.alignleft {
    float: left;
    margin: 5px 20px 20px 0;
}

a img.aligncenter {
    display: block;
    margin-left: auto;
    margin-right: auto
}

div#footer-social1 h2 {
  display: none;
}
.wp-caption {
    background: #fff;
    border: 1px solid #f0f0f0;
    max-width: 96%; /* Image does not overflow the content area */
    padding: 5px 3px 10px;
    text-align: center;
	font-family:"Open Sans";
}

.wp-caption.alignnone {
    margin: 5px 20px 20px 0;
}

.wp-caption.alignleft {
    margin: 5px 20px 20px 0;
}

.wp-caption.alignright {
    margin: 5px 0 20px 20px;
}

.wp-caption img {
    border: 0 none;
    height: auto;
    margin: 0;
    max-width: 98.5%;
    padding: 0;
    width: auto;
}

.wp-caption p.wp-caption-text {
    font-size: 11px;
    line-height: 17px;
    margin: 0;
    padding: 0 4px 5px;
}

/*** Custom WordPress gallery style ***/
.gallery .gallery-caption{  
    font-size:12px;
	color:#888;
	font-family:"Open Sans";
}  
  
.gallery .gallery-icon img{  
    border-radius:2px;  
    border:1px solid #eee !important;  
	padding:7px;
}  
.gallery .gallery-icon img:hover {
	border:1px solid #ccc !important;  
}

/*** Contact Form 7 ***/
/*********************************************************/
.wpcf7 input {
	width:266px;
}
div.wpcf7 {
	overflow:hidden;
	margin-top:40px;
}
.wpcf7 p.sp_input {
	float:left;
	margin-right:19px;
}
.wpcf7 p.sp_message {
	clear:both;
}

.wpcf7 input, .wpcf7 textarea {
	padding:8px;
	border:1px solid #DDD;
	margin-right:10px;
	-webkit-border-radius: 5px;-moz-border-radius: 5px;border-radius: 5px;
	color:#777;
	font-size:12px;
	margin-top:6px;
	margin-bottom:6px;
}
.wpcf7 textarea {
	width:95%;
}
.wpcf7 .wpcf7-submit {
	background:#171717;
	-webkit-border-radius: 20px;-moz-border-radius: 20px;border-radius:20px;
	padding:12px 24px;
	color:#FFF;
	letter-spacing:3px;
	font-size:11px;
	text-transform:uppercase;
	cursor:pointer;
	-o-transition:.3s;
	-ms-transition:.3s;
	-moz-transition:.3s;
	-webkit-transition:.3s;
	transition:.3s;
	display:block;
	border:none;
	width:auto;
}
.wpcf7 .wpcf7-submit:hover {
	background:#777;
}


/*** 404 ***/
.error-404 {
	margin-bottom:105px;
	text-align:center;
}

.error-404 h1 {
	font-size:190px;
	font-weight:700;
	margin-bottom:-25px;
}
.error-404 p {
	color:#999;
	font-size:18px;
	font-style:italic;
}

.author-content {
    margin-left: 140px;
}

		#logo { padding:40px 0; }
		
		#navigation { background:transparent; }
		.menu li a { color:#ffffff; }
		.menu li a:hover {  color:#999999; }
		
		.menu .sub-menu, .menu .children { background: #171717; }
		ul.menu ul a, .menu ul ul a { border-top: 1px solid #333333; color:#999999; }
		ul.menu ul a:hover, .menu ul ul a:hover { color: #ffffff; background:#333333; }
		
		#top-social a i { color:#f5f5f5; }
		#top-social a:hover i { color:#ffffff }
		
		#top-search a { background:transparent }
		#top-search a { color:transparent }
		#top-search a:hover { background:transparent; }
		#top-search a:hover { color:#cccccc; }
		
		.widget-title , #sidebar .widget h2, #widget-area .widget h2 { color:#222; }
		#sidebar .widget-title, #sidebar .widget h2, #widget-area .widget h2 { background:; color:; }
		
		#footer-social  { background:#f2f2f2; }
		
		#footer-logo { background:#171717; }
		#footer-logo p { color:#EFEFEF; }
		
		#footer-copyright { background:#ffffff; }
		#footer-copyright p { color:#000000; }
		
		a, #footer-logo p i { color:#646464; }
		.post-entry blockquote p { border-left:3px solid #cea525; }
		
				
		
#main .widget {
    width: 100%;
}		
#navigation .widget ul li {
border:none;
margin-bottom:0px;
padding-bottom:0px;
}

#navigation .widget ul li:after {
  content: "|";
  padding-left: 10px;
  color: #565656;
}


#navigation .widget ul li:last-child:after {
  content: "";
}

#navigation .widget a:hover {
 text-decoration: none;
}
#widget-area #container3 .widget {
    margin-right: 0;
}

.container.sp_sidebar {
  overflow: hidden;
  margin: 40px auto 0;
}


/*** FEATURED AREA STYLES ***/
/*********************************************************/

.featured-area {
	margin-bottom:40px;
	overflow:hidden;
	height:400px;
}
.featured-area.tabs-wrapper img {
	float:left;
	margin-right:20px;
	width:620px;
	height:400px;
}
.featured-area ul.featured-tab {
	overflow:hidden;
}
.featured-area ul.featured-tab li {
	border-left:1px solid #e5e5e5;
	padding-left:18px;
	height:85px;
	margin-bottom:20px;
}
.featured-area ul.featured-tab li:last-child {
	margin-bottom:0;
}
.featured-area ul.featured-tab li.active {
	border-left:1px solid #000;
}
.featured-area ul.featured-tab li:hover {
	border-left:1px solid #000;
	-o-transition:.5s;
	-ms-transition:.5s;
	-moz-transition:.5s;
	-webkit-transition:.5s;
	transition:.5s;
}

.featured-area ul.featured-tab li .featured-text {
	
}
.featured-area ul.featured-tab li .featured-text h3 a {
	font-size:18px;
	color:#000;
	letter-spacing:1px;
	margin-bottom:2px;
	display:block;
}
.featured-area ul.featured-tab li .featured-text span.featured-meta {
	font-size:10px;
	font-family:"Playfair Display";
	text-transform:uppercase;
	letter-spacing:1px;
	color:#999;
}

/** slider **/
.flexslider ul.slides li .overlay {
	background:rgba(0,0,0,.2);
	height:540px;
	width:1030px;
	position:absolute;
	bottom:0;
	-o-transition:.3s;
	-ms-transition:.3s;
	-moz-transition:.3s;
	-webkit-transition:.3s;
	transition:.3s;
	text-align: center;
	z-index:1;
}
.flexslider ul.slides li .overlay:before {
	content: '';
	display: inline-block;
	height: 100%;
	vertical-align: middle;
}

.flexslider ul.slides li:hover > .overlay {
	background:rgba(0,0,0,.6);
}

.flexslider ul.slides li .feature_text {
	width:80%;
	vertical-align: middle;
	display: inline-block;
	z-index:100;
}

.flexslider ul.slides li .feature_text .feature-line { 
	margin-bottom:14px;
}
.flexslider ul.slides li .feature_text .feature-line span.line {
	height:3px;
	width:60px;
	background:#FFF;
	display:inline-block;
}

.flexslider ul.slides li .feature_text h2 a {
	  color: #fff;
  line-height: 1.2em;
  margin-bottom: 12px;
  display: block;
  font-family: Raleway;
  font-size: 35px;
  font-weight: 400;
  font-style: normal;
  line-height: 1.25;
  letter-spacing: 3px;
  text-transform: uppercase;
}
.flexslider ul.slides li .feature_text p {
	color:#fff;
	font-size:15px;
	padding:1px 8px;
	display:inline-block;
	margin-bottom:40px;
}
.flexslider ul.slides li .feature_text span.feature_button {
	display:block;
}
.flexslider ul.slides li .feature_text span.feature_button a {
	border:3px solid #FFF;
	color:#FFF;
	padding:11px;
	text-transform:uppercase;
	font-size:14px;
	font-weight:700;
	letter-spacing:2px;
	font-family:Sans-serif;
	-o-transition:.3s;
	-ms-transition:.3s;
	-moz-transition:.3s;
	-webkit-transition:.3s;
	transition:.3s;
}
.flexslider ul.slides li .feature_text span.feature_button a:hover {
	background:#000;
	color:#fff;
	border:3px solid #FFF;
}
.flexslider ul.slides li .feature_text span.feature_button a i.fa {
	margin-left:1px;
	font-size:14px;
}

/*** flexslider gallery **/
.flexslider.gallery {
	margin-bottom:20px;
}

.flexslider .slides a.thumb {
display:block;
height:540px;
overflow:hidden;
}

#blog-pager > span a h3 {
font-family: raleway;
font-size: 17px;
}
#blog-pager a:hover {
text-decoration: none;
}
#blog-pager a > h3:hover {
text-decoration: underline!important;
}

#blog-pager-older-link{display:inline;float:right;width:50%;text-align:right;padding:0}
#blog-pager-newer-link{display:inline;float:left;width:50%;text-align:left;padding:0}
#blog-pager{
clear:both;
font-size:16px;
line-height:normal;
margin:0;
padding:10px;
font-family: times new roman;
background: #f9f9f9;
}


#instafeed{max-width:100%;margin:0 auto;list-style:none;text-align:center;font-family:sans-serif;  line-height: 0px;  border-top: 1px solid rgba(34,34,34,0.1);
  border-bottom: 1px solid rgba(34,34,34,0.1);}
#instafeed li{display:inline-block;width: 12.5%;margin:0;padding:0;text-align:left;position:relative}
#instafeed div{margin:0;position:relative}
#instafeed img{max-width:100%;display:block;position:relative;z-index:10;-webkit-transition:-webkit-transform .4s;-moz-transition:-moz-transform .4s;transition:transform .4s}


/*---Flicker Image Gallery-----*/
.flickr_plugin {
width: 100%;
}
.flickr_badge_image {
float: left;
height: 70px;
margin: 8px 5px 0px 5px;
width: 70px;
}
.flickr_badge_image a {
display: block;
}
.flickr_badge_image a img {
display: block;
width: 100%;
height: auto;
-webkit-transition: opacity 100ms linear;
-moz-transition: opacity 100ms linear;
-ms-transition: opacity 100ms linear;
-o-transition: opacity 100ms linear;
transition: opacity 100ms linear;
}
.flickr_badge_image a img:hover {
opacity: .5;
}



]]></b:skin>
  </head>


<style type='text/css'>
.pagination .older {
  float: right;
  position: relative; 
  text-align: right;
}

.pagination .newer {
  float: left;
  position: relative; 
  text-align: left;
}
 .post-nav-icon {
   position: absolute;
  top: 7px;
  width: 32px;
  height: 32px;
  text-align: center;
  line-height: 32px;
  background-color: #000;
  border-radius: 32px;
  color: #fff;
  letter-spacing: 0;

}

.older .post-nav-icon{
right:0;
}

.newer .post-nav-icon{
left:0;
}


.older .pager-heading {
  margin-bottom: 5px;
color:#aaa;
  margin-right: 42px;
}

.older .pager-title {
  font-size: 150%;
  display: block;
  line-height: 1.3;
  white-space: normal;
  text-overflow: ellipsis;
  overflow: hidden;
color:#222;
  margin-right: 42px;
}


.newer .pager-heading {
  margin-bottom: 5px;
color:#aaa;
  margin-left: 42px;
}

.newer .pager-title {
  font-size: 150%;
  display: block;
  line-height: 1.3;
  white-space: normal;
  text-overflow: ellipsis;
  overflow: hidden;
color:#222;
  margin-left: 42px;
}

.entry-meta {
  text-align: center;
  border-bottom: 1px solid rgba(34,34,34,0.1);
  padding-bottom: 40px;
  margin-bottom: 40px;
}

.single-sharing-btns h3 {
   margin-top: 0;
  font-family: Raleway;
  font-size: 24px;
  font-weight: 400;
  font-style: normal;
  line-height: 1.25;
  letter-spacing: 3px;
  text-transform: uppercase;
  text-align: center;
color:#222;
  margin-bottom: 20px;
}


.social-share-buttons.size-large {
  margin-bottom: 5px;
}
.social-share-buttons.style-default [data-service] {
  box-shadow: 0 3px 0 rgba(0,0,0,0.05);
}
.social-share-buttons.size-large&gt;*, .social-share-buttons.size-large&gt;li&gt;span {
  line-height: 32px;
  min-width: 32px;
}
.social-share-buttons.style-default&gt;*, .social-share-buttons.style-default&gt;li&gt;span {
  border: 1px solid #ddd;
  background-color: #fff;
}
.social-share-buttons&gt;*:first-child {
  margin-left: 0;
}
.social-share-buttons&gt;*, .social-share-buttons&gt;li&gt;span {
  display: inline-block;
  padding: 0 8px;
  cursor: pointer;
  text-align: center;
  position: relative;
  -webkit-border-radius: 1;
  -moz-border-radius: 1;
  -ms-border-radius: 1;
  -o-border-radius: 1;
  border-radius: 1;
  transition: color linear .2s,background-color linear .2s,border-color linear .2s;
  -webkit-transition: color linear .2s,background-color linear .2s,border-color linear .2s;
}
.social-share-buttons&gt;* {
  display: inline-block;
  margin: 5px 8px;
}
.social-share-buttons.size-large.style-default label {
  font-size: 12px;
}

.social-share-buttons.style-default label {
  text-transform: uppercase;
}

.single-sharing-btns label {
  letter-spacing: .1em;
}

.social-share-buttons label {
  margin: 0 0 0 10px;
  text-transform: uppercase;
  font-weight: normal;
  line-height: 1;
  vertical-align: middle;
  cursor: pointer;
}

strong.tag-heading {
  color: #222;
  text-transform: uppercase;
  font-size: 12px;
}
strong.tag-heading .fa {
  margin-right: 5px;
}

.entry-tags .gray-2-secondary a{
  color: #aaa;
  text-transform: uppercase;
  font-size: 12px;
}

.entry-tags.gray-2-secondary {
  margin-top: 20px;
}


/*************************************************
*	10. Tablet									 *
*************************************************/
@media only screen and (min-width: 768px) and (max-width: 960px) {
	
	.container {
		width:726px;
	}
	
	#navigation-wrapper {
		display:none;
	}
	
	#logo img {
		max-width:726px;
		height:auto;
	}
	
	.slicknav_menu {
		display:block;
	}
	
	.post-image img {
		width:726px;
		height:auto;
	}
	
	
	.post-image.audio iframe {
		width:726px;
		height:auto;
	}
	
		.container.sp_sidebar .post-image.audio iframe {
			width:476px;
			height:auto;
		}
	
	.item-related {
		width:230px;
		margin-right:17px;
	}
	.post-pagination .prev-post {
		width:383px;
	}
	.post-pagination .next-post {
		width:383px;
	}
	
	
	
	#widget-area .widget, #sidebar .widget {
		width:230px;
		margin-right:17px;
	}
	
	#widget-area .widget img, #sidebar .widget img {
		max-width:230px;
		height:auto;
	}
	
	#widget-area .widget iframe, #sidebar .widget iframe {
		max-width:230px !important;
		height:auto;
	}
	
	#footer-logo img {
		max-width:726px;
		height:auto;
	}
	#footer-social a {
		margin:0 15px;
	}
	#footer-social a i {
		height:32px;
		width:32px;
		line-height:32px;
		margin-right:0;
		font-size:14px;
	}
	#footer-social a span {
		display:none;
	}
	
	.wpcf7 input {
		width:208px;
	}
	
	.sp-grid li {
		width:353px;
	}
	.sp-grid li:nth-child(3n+3) {
		margin-right:16px;
	}
	.sp-grid li:nth-child(2n+2) {
		margin-right:0;
	}
	
	.container.sp_sidebar #main {
		width:476px;
		margin-right:20px;
	}
	.container.sp_sidebar #sidebar {
		width:230px;
	}
	
		.container.sp_sidebar #sidebar .widget {
			width:168px;
		}
		
	.container.sp_sidebar .sp-grid li {
		width:228px;
	}
	
	.container.sp_sidebar .item-related {
		width:149px;
		margin-right:14px;
	}
	.container.sp_sidebar .item-related:last-child {
		margin-right:0;
	}
	.container.sp_sidebar .item-related h3 a {
		font-size:12px;
		letter-spacing:1px;
	}
	
	.container.sp_sidebar #respond textarea {
		width:93%;
	}
	
}

/*************************************************
*	Mobile Portrait								 *
*************************************************/

@media only screen and (max-width: 767px) {
	
	.container {
		width:320px;
	}
	
	#navigation-wrapper {
		display:none;
	}
	
	.slicknav_menu {
		display:block;
	}
	
	#logo img {
		max-width:320px;
		height:auto;
	}
	
	.post-header h1 a, .post-header h2 a, .post-header h1 {
		font-size:22px;
		letter-spacing:2px;
	}
	
	.post-image img {
		width:320px;
		height:auto;
	}
	
	.post-image.audio iframe {
		width:320px;
		height:auto;
	}
	
	.item-related {
		width:320px;
		margin-bottom:30px;
	}
	
	.share-box {
		width:46px; 
		height:36px; 
		line-height:36px;
		margin:0 4px;
	}
	
	.post-pagination .prev-post {
		width:320px;
	}
	.post-pagination .next-post {
		width:320px;
	}
	
	#respond textarea {
		width:90%;
	}
	
	.thecomment .author-img {
		display:none;
	}
	
	#widget-area .widget, #sidebar .widget {
		width:320px;
		margin-right:32px;
		float:left;
		margin-bottom:35px;
	}
	
	#footer-logo img {
		max-width:320px;
		height:auto;
	}
	
	#footer-social a i {
		height:28px;
		width:28px;
		line-height:28px;
		margin-right:0;
		font-size:12px;
	}
	#footer-social a {
		margin:0 5px;
	}
	#footer-social a span{
		display:none;
	}
	
	.wpcf7 textarea {
		width:94%;
	}
	
	.sp-grid li {
		width:320px;
	}
	.sp-grid li:nth-child(3n+3) {
		margin-right:0;
	}
	.sp-grid li:nth-child(2n+2) {
		margin-right:0;
	}
	
	.container.sp_sidebar #main {
		width:320px;
		margin-right:0;
	}
	.container.sp_sidebar #sidebar {
		width:320px;
	}
	
		.container.sp_sidebar #sidebar .widget {
			width:258px;
		}
		
	.container.sp_sidebar .item-related {
		width:320px;
		margin-bottom:30px;
	}
	
	
}

/*************************************************
*	10. Landscape								 *
*************************************************/

@media only screen and (min-width: 480px) and (max-width: 767px) {
	
	.container {
		width:480px;
	}
	
	#logo img {
		max-width:480px;
		height:auto;
	}
	
	.post-image img {
		width:480px;
		height:auto;
	}
	
	.post-image.audio iframe {
		width:480px;
		height:auto;
	}
	
	.item-related {
		width:480px;
		margin-bottom:30px;
	}
	
	.share-box {
		width:55px; 
		height:42px; 
		line-height:42px;
		margin:0 10px;
	}
	
	.post-pagination .prev-post {
		width:480px;
	}
	.post-pagination .next-post {
		width:480px;
	}
	
	#widget-area .widget, #sidebar .widget {
		width:480px;
		margin-right:32px;
		float:left;
		margin-bottom:35px;
	}
	
	#footer-logo img {
		max-width:480px;
		height:auto;
	}
	
	#footer-social a {
		margin:0 12px;
	}
	
	#footer-social a i {
		height:32px;
		width:32px;
		line-height:32px;
		margin-right:0;
		font-size:14px;
	}
	
	.wpcf7 textarea {
		width:95%;
	}
	
	.sp-grid li {
		width:230px;
	}
	.sp-grid li:nth-child(3n+3) {
		margin-right:16px;
	}
	.sp-grid li:nth-child(2n+2) {
		margin-right:0;
	}
	
		.container.sp_sidebar .sp-grid li {
			width:230px;
		}
		.container.sp_sidebar .sp-grid li:nth-child(3n+3) {
			margin-right:16px;
		}
		
		.container.sp_sidebar .sp-grid li:nth-child(2n+2) {
			margin-right:0;
		}
		
	.container.sp_sidebar #main {
		width:480px;
		margin-right:0;
	}
	.container.sp_sidebar #sidebar {
		width:480px;
	}
	
		.container.sp_sidebar #sidebar .widget {
			width:418px;
		}
		
	.container.sp_sidebar .item-related {
		width:480px;
		margin-bottom:30px;
	}
	
}
</style>

<style type='text/css'>
/**
 * BxSlider v4.1.2 - Fully loaded, responsive content slider
 * http://bxslider.com
 *
 * Written by: Steven Wanderski, 2014
 * http://stevenwanderski.com
 * (while drinking Belgian ales and listening to jazz)
 *
 * CEO and founder of bxCreative, LTD
 * http://bxcreative.com
 */


/** RESET AND LAYOUT
===================================*/

.bx-wrapper {
	position: relative;
	margin: 0 auto 60px;
	padding: 0;
	*zoom: 1;
	margin-bottom:22px;
}

.bx-wrapper img {
	max-width: 100%;
	
}

/** THEME
===================================*/

.bx-wrapper .bx-viewport {
	background: #fff;
	text-align:center;
	/*fix other elements on the page moving (on Chrome)*/
	-webkit-transform: translatez(0);
	-moz-transform: translatez(0);
    	-ms-transform: translatez(0);
    	-o-transform: translatez(0);
    	transform: translatez(0);
}

.bx-wrapper .bx-pager,
.bx-wrapper .bx-controls-auto {
	position: absolute;
	bottom: -30px;
	width: 100%;
}

/* LOADER */

.bx-wrapper .bx-loading {
	min-height: 50px;
	height: 100%;
	width: 100%;
	position: absolute;
	top: 0;
	left: 0;
	z-index: 2000;
}

/* PAGER */

.bx-wrapper .bx-pager {
	text-align: center;
	font-size: .85em;
	font-family: Arial;
	font-weight: bold;
	color: #666;
	padding-top: 20px;
}

.bx-wrapper .bx-pager .bx-pager-item,
.bx-wrapper .bx-controls-auto .bx-controls-auto-item {
	display: inline-block;
	*zoom: 1;
	*display: inline;
}

.bx-wrapper .bx-pager.bx-default-pager a {
	background: #666;
	text-indent: -9999px;
	display: block;
	width: 10px;
	height: 10px;
	margin: 0 5px;
	outline: 0;
	-moz-border-radius: 5px;
	-webkit-border-radius: 5px;
	border-radius: 5px;
}

.bx-wrapper .bx-pager.bx-default-pager a:hover,
.bx-wrapper .bx-pager.bx-default-pager a.active {
	background: #000;
}

/* DIRECTION CONTROLS (NEXT / PREV) */

.bx-wrapper .bx-prev {
	left: 20px;
	background: url(http://1.bp.blogspot.com/-WCgfaNs6MAU/VBnoMBFzakI/AAAAAAAABxw/oqXkrdC99Kw/s1600/slider-arrows.png) no-repeat 0 0;
}

.bx-wrapper .bx-next {
	right: 20px;
	background: url(http://1.bp.blogspot.com/-WCgfaNs6MAU/VBnoMBFzakI/AAAAAAAABxw/oqXkrdC99Kw/s1600/slider-arrows.png) no-repeat -30px 0;
}

/*.bx-controls-direction a {
    opacity: 0;
    transition: opacity .25s ease-in-out;
    -moz-transition: opacity .25s ease-in-out;
    -webkit-transition: opacity .25s ease-in-out;
}

.bx-wrapper:hover .bx-controls-direction a {
    opacity: 1;
}*/

.bx-wrapper .bx-next:hover, .bx-wrapper .bx-prev:hover {
	opacity:.7 !important;
}

.bx-wrapper .bx-controls-direction a {
	position: absolute;
	top: 50%;
	margin-top: -15px;
	outline: 0;
	width: 30px;
	height: 30px;
	text-indent: -9999px;
	z-index: 9999;
}

.bx-wrapper .bx-controls-direction a.disabled {
	display: none;
}

/* AUTO CONTROLS (START / STOP) */

.bx-wrapper .bx-controls-auto {
	text-align: center;
}

.bx-wrapper .bx-controls-auto .bx-start {
	display: block;
	text-indent: -9999px;
	width: 10px;
	height: 11px;
	outline: 0;
	background: url(images/controls.png) -86px -11px no-repeat;
	margin: 0 3px;
}

.bx-wrapper .bx-controls-auto .bx-start:hover,
.bx-wrapper .bx-controls-auto .bx-start.active {
	background-position: -86px 0;
}

.bx-wrapper .bx-controls-auto .bx-stop {
	display: block;
	text-indent: -9999px;
	width: 9px;
	height: 11px;
	outline: 0;
	background: url(images/controls.png) -86px -44px no-repeat;
	margin: 0 3px;
}

.bx-wrapper .bx-controls-auto .bx-stop:hover,
.bx-wrapper .bx-controls-auto .bx-stop.active {
	background-position: -86px -33px;
}

/* PAGER WITH AUTO-CONTROLS HYBRID LAYOUT */

.bx-wrapper .bx-controls.bx-has-controls-auto.bx-has-pager .bx-pager {
	text-align: left;
	width: 80%;
}

.bx-wrapper .bx-controls.bx-has-controls-auto.bx-has-pager .bx-controls-auto {
	right: 0;
	width: 35px;
}

/* IMAGE CAPTIONS */

.bx-wrapper .bx-caption {
	position: absolute;
	bottom: 6px;
	left: 0;
	background: rgba(0, 0, 0, 0.6);
	width: 100%;
	padding:20px;
}

.bx-wrapper .bx-caption span {
	color: #fff;
	display: block;
	font-size: 16px;
}

</style>

<style type='text/css'>

/*
    Mobile Menu Core Style
*/

.slicknav_btn { position: relative; display: block; vertical-align: middle; float: left;  line-height: 27px; cursor: pointer;  height:27px;}
.slicknav_menu  .slicknav_menutxt { display: block; line-height: 1.188em; float: left; }
.slicknav_menu .slicknav_icon { float: left; margin: 0.188em 0 0 0.438em; }
.slicknav_menu .slicknav_no-text { margin: 0 }
.slicknav_menu .slicknav_icon-bar { display: block; width: 1.125em; height: 0.125em; }
.slicknav_btn .slicknav_icon-bar + .slicknav_icon-bar { margin-top: 0.188em }
.slicknav_nav { clear: both }
.slicknav_nav ul,
.slicknav_nav li { display: block }
.slicknav_nav .slicknav_arrow { font-size: 0.8em; margin: 0 0 0 0.4em; }
.slicknav_nav .slicknav_item { cursor: pointer; }
.slicknav_nav .slicknav_row { display: block; }
.slicknav_nav a { display: block }
.slicknav_nav .slicknav_item a,
.slicknav_nav .slicknav_parent-link a { display: inline }
.slicknav_menu:before,
.slicknav_menu:after { content: &quot; &quot;; display: table; }
.slicknav_menu:after { clear: both }
/* IE6/7 support */
.slicknav_menu { *zoom: 1 }

/* 
    User Default Style
    Change the following styles to modify the appearance of the menu.
*/

.slicknav_menu {
    font-size:16px;
}
/* Button */
.slicknav_btn {
    margin: 5px 5px 6px;
    text-decoration:none;
    text-shadow: 0 1px 1px rgba(255, 255, 255, 0.75);
    -webkit-border-radius: 4px;
    -moz-border-radius: 4px;
    border-radius: 4px;  
    
}
/* Button Text */
.slicknav_menu  .slicknav_menutxt {
    color: #FFF;
    font-weight: bold;
    text-shadow: 0 1px 3px #000;
}
/* Button Lines */
.slicknav_menu .slicknav_icon-bar {
  background-color: #f5f5f5;
}
.slicknav_menu {
    background:#171717;
    padding:5px;
}
.slicknav_nav {
    color:#fff;
    margin:0;
    padding:0;
    font-size:0.875em;
}
.slicknav_nav, .slicknav_nav ul {
    list-style: none;
    overflow:hidden;
}
.slicknav_nav ul {
    padding:0;
    margin:0 0 0 20px;
}
.slicknav_nav .slicknav_row {
    padding:5px 10px;
    margin:2px 5px;
}
.slicknav_nav a{
    padding:5px 10px;
    margin:2px 5px;
    text-decoration:none;
    color:#fff;
	font-family:&quot;Open Sans&quot;, sans-serif;
	font-size:11px;
	font-weight:400;
	letter-spacing:2px;
	color:#fff;
	text-transform:uppercase;
}
.slicknav_nav .slicknav_item a,
.slicknav_nav .slicknav_parent-link a {
    padding:0;
    margin:0;
}
.slicknav_nav .slicknav_row:hover {
    
}
.slicknav_nav a:hover{
    
    background:#333;
    color:#fff;
}
.slicknav_nav .slicknav_txtnode {
     margin-left:15px;   
}

.slicknav_menu .slicknav_no-text {
	margin-top:7px;
}

.PopularPosts .widget-content ul li {
  padding: 0.3em 0;
}

</style>



<style>
/*
 * jQuery FlexSlider v2.2.0
 * http://www.woothemes.com/flexslider/
 *
 * Copyright 2012 WooThemes
 * Free to use under the GPLv2 license.
 * http://www.gnu.org/licenses/gpl-2.0.html
 *
 * Contributing author: Tyler Smith (@mbmufffin)
 */


/* Browser Resets
*********************************/
.flex-container a:active,
.flexslider a:active,
.flex-container a:focus,
.flexslider a:focus  {outline: none;}
.slides,
.flex-control-nav,
.flex-direction-nav {margin: 0; padding: 0; list-style: none;}

/* Icon Fonts
*********************************/
/* Font-face Icons */
@font-face {
	font-family: &#39;flexslider-icon&#39;;
	src:url(&#39;fonts/flexslider-icon.eot&#39;);
	src:url(&#39;fonts/flexslider-icon.eot?#iefix&#39;) format(&#39;embedded-opentype&#39;),
		url(&#39;fonts/flexslider-icon.woff&#39;) format(&#39;woff&#39;),
		url(&#39;fonts/flexslider-icon.ttf&#39;) format(&#39;truetype&#39;),
		url(&#39;fonts/flexslider-icon.svg#flexslider-icon&#39;) format(&#39;svg&#39;);
	font-weight: normal;
	font-style: normal;
}

/* FlexSlider Necessary Styles
*********************************/
.flexslider {margin: 0; padding: 0;}
.flexslider .slides &gt; li {display: none; -webkit-backface-visibility: hidden;} /* Hide the slides before the JS is loaded. Avoids image jumping */
.flexslider .slides img {width: 100%; display: block;}
.flex-pauseplay span {text-transform: capitalize;}

/* Clearfix for the .slides element */
.slides:after {content: &quot;\0020&quot;; display: block; clear: both; visibility: hidden; line-height: 0; height: 0;}
html[xmlns] .slides {display: block;}
* html .slides {height: 1%;}

/* No JavaScript Fallback */
/* If you are not using another script, such as Modernizr, make sure you
 * include js that eliminates this class on page load */
.no-js .slides &gt; li:first-child {display: block;}

/* FlexSlider Default Theme
*********************************/
.flexslider { margin: 0 0 40px 0; position: relative; zoom: 1; }
.flex-viewport { max-height: 2000px; -webkit-transition: all 1s ease; -moz-transition: all 1s ease; -o-transition: all 1s ease; transition: all 1s ease; }
.loading .flex-viewport { max-height: 300px; }
.flexslider .slides { zoom: 1; }
.carousel li { margin-right: 5px; }

/* Direction Nav */
.flex-direction-nav {*height: 0;}
.flex-direction-nav a {width: 33px; height: 41px; margin: -20px 0 0; display: block; background: url(http://2.bp.blogspot.com/-uxRBv_6ctCg/VAC8blS2qzI/AAAAAAAAD7U/z0_dCwGhKi4/s1600/slider-nav.png) no-repeat 0 0; position: absolute; top: 50%; z-index: 10; cursor: pointer; text-indent: -9999px; opacity: 0; -webkit-transition: all .3s ease;}
.flex-direction-nav .flex-next {background-position: 100% 0; right: -33px; }
.flex-direction-nav .flex-prev {left: -33px;}
.flexslider:hover .flex-next {opacity: 1; right: 0;}
.flexslider:hover .flex-prev {opacity: 1; left: 0;}
.flexslider:hover .flex-next:hover, .flexslider:hover .flex-prev:hover {opacity: 1;}
.flex-direction-nav .flex-disabled {opacity: .3!important; filter:alpha(opacity=30); cursor: default;}

/* Pause/Play */
.flex-pauseplay a { display: block; width: 20px; height: 20px; position: absolute; bottom: 5px; left: 10px; opacity: 0.8; z-index: 10; overflow: hidden; cursor: pointer; color: #000; }
.flex-pauseplay a:before  { font-family: &quot;flexslider-icon&quot;; font-size: 20px; display: inline-block; content: &#39;\f004&#39;; }
.flex-pauseplay a:hover  { opacity: 1; }
.flex-pauseplay a.flex-play:before { content: &#39;\f003&#39;; }

/* Control Nav */
.flex-control-nav {width: 100%; position: absolute; bottom: -40px; text-align: center;}
.flex-control-nav li {margin: 0 6px; display: inline-block; zoom: 1; *display: inline;}
.flex-control-paging li a {width: 11px; height: 11px; display: block; background: #666; background: rgba(0,0,0,0.5); cursor: pointer; text-indent: -9999px; -webkit-border-radius: 20px; -moz-border-radius: 20px; -o-border-radius: 20px; border-radius: 20px; -webkit-box-shadow: inset 0 0 3px rgba(0,0,0,0.3); -moz-box-shadow: inset 0 0 3px rgba(0,0,0,0.3); -o-box-shadow: inset 0 0 3px rgba(0,0,0,0.3); box-shadow: inset 0 0 3px rgba(0,0,0,0.3); }
.flex-control-paging li a:hover { background: #333; background: rgba(0,0,0,0.7); }
.flex-control-paging li a.flex-active { background: #000; background: rgba(0,0,0,0.9); cursor: default; }

.flex-control-thumbs {margin: 5px 0 0; position: static; overflow: hidden;}
.flex-control-thumbs li {width: 25%; float: left; margin: 0;}
.flex-control-thumbs img {width: 100%; display: block; opacity: .7; cursor: pointer;}
.flex-control-thumbs img:hover {opacity: 1;}
.flex-control-thumbs .flex-active {opacity: 1; cursor: default;}

@media screen and (max-width: 860px) {
  .flex-direction-nav .flex-prev { opacity: 1; left: 10px;}
  .flex-direction-nav .flex-next { opacity: 1; right: 10px;}
}


@media only screen and (min-width: 768px) and (max-width: 960px) {

	/*** FEATURED AREA ***/
	.featured-area {
		height:271px;
	}
	.featured-area.tabs-wrapper img {
		width:420px;
		height:271px;
		margin-right:10px;
	}
	.featured-area ul.featured-tab li {
		padding-left:14px;
		height:60px;
		margin-bottom:10px;
	}
	.featured-area ul.featured-tab li .featured-text h3 a {
		font-size:13px;
	}
	.featured-area ul.featured-tab li .featured-text span.featured-meta {
		font-size:9px;
	}
	
	
	/*** SLIDER ***/

	.flexslider ul.slides li .overlay {
		height:408px;
		width:726px;
	}
	.flexslider .slides a.thumb {
	display:block;
	height:408px;
	overflow:hidden;
}
	.flexslider ul.slides li .feature_text h2 a {
		font-size:32px;
	}
	.flexslider ul.slides li .feature_text p {
		font-size:14px;
	}
	.flexslider ul.slides li .feature_text span.feature_button a {
		padding:10px;
		font-size:12px;
	}
	

	.flex-direction-nav .flex-next {right: -23px; }
	.flex-direction-nav .flex-prev {left: -23px;}
	

}

/*************************************************
*	Mobile Portrait								 *
*************************************************/

@media only screen and (max-width: 767px) {

	/*** Featured Area ***/
	.featured-area {
		margin-bottom:40px;
		overflow:hidden;
		height:auto;
	}
	.featured-area.tabs-wrapper img {
		float:none;
		margin-right:20px;
		width:300px;
		height:194px;
		margin-bottom:10px;
	}
	.featured-area ul.featured-tab li {
		border-left:1px solid #e5e5e5;
		padding-left:18px;
		height:auto;
		margin-bottom:10px;
		padding:10px;
		background:#f5f5f5;
	}
	.featured-area ul.featured-tab li .featured-text h3 a {
		font-size:12px;
		color:#000;
		letter-spacing:1px;
		margin-bottom:2px;
		display:block;
	}
	.featured-area ul.featured-tab li .featured-text span.featured-meta {
		display:none;
	}
	.featured-area ul.featured-tab li.active {
		background:#111;
		
	}
	.featured-area ul.featured-tab li.active .featured-text h3 a {
		color:#fff;
	}
	
	/*** slider ***/
	.flexslider ul.slides li .overlay {
		width:320px;
		height:169px;
	}
	.flexslider .slides a.thumb {
	display:block;
	height:169px;
	overflow:hidden;
}
	.flexslider ul.slides li .feature_text h2 a {
		font-size:14px;
		line-height:18px;
		margin-bottom:0;
	}
	.flexslider ul.slides li .feature_text p {
		display:none;
	}
	.flexslider ul.slides li .feature_text span.feature_button a {
		display:none;
	}
	.flexslider ul.slides li .feature_text .feature-line {
		display:none;
	}
	.flex-direction-nav .flex-next {display:none;}
	.flex-direction-nav .flex-prev {display:none;}
	
	
	
}

/*************************************************
*	10. Landscape								 *
*************************************************/

@media only screen and (min-width: 480px) and (max-width: 767px) {

	/** featured ***/
	.featured-area.tabs-wrapper img {
		float:none;
		margin-right:20px;
		width:440px;
		height:285px;
		margin-bottom:10px;
	}
	
	/*** Slider ***/
	.flexslider ul.slides li .overlay {
		width:480px;
		height:247px;
	}
	.flexslider .slides a.thumb {
	display:block;
	height:247px;
	overflow:hidden;
}
  }

</style>


 <b:if cond='data:blog.pageType == &quot;static_page&quot;'>
      <style type='text/css'>

.post-header {
  font-family: Raleway;
  font-size: 30px;
  font-weight: 400;
  font-style: normal;
  line-height: 1.25;
  letter-spacing: 3px;
  text-transform: uppercase;
  color: #222;
}
</style>
  </b:if>

    <b:if cond='data:blog.pageType == &quot;item&quot;'>
      <style type='text/css'>
.post-entry {
  text-align: justify;
  border-bottom: 1px solid rgba(34,34,34,0.1);
  padding-bottom: 40px;
  margin-bottom: 40px;
}

.container.sp_sidebar {
  overflow: hidden;
  margin-top: 40px;
}

.pagination {
  margin-bottom: 60px;
  overflow: hidden;
  display: none;
}
</style>
  </b:if>

<link href='//netdna.bootstrapcdn.com/font-awesome/4.0.1/css/font-awesome.css?ver=3.9.2' id='font-awesome-css' media='all' rel='stylesheet' type='text/css'/>
<link href='http://fonts.googleapis.com/css?family=Open+Sans%3A300italic%2C400italic%2C700italic%2C400%2C700%2C300&amp;subset=latin%2Ccyrillic-ext&amp;ver=3.9.2' id='default_headings_font-css' media='all' rel='stylesheet' type='text/css'/>
<link href='http://fonts.googleapis.com/css?family=Crimson+Text%3A400%2C700%2C400italic%2C700italic&amp;ver=3.9.2' id='default_body_font-css' media='all' rel='stylesheet' type='text/css'/>
<script src='http://ajax.googleapis.com/ajax/libs/jquery/1.11.0/jquery.min.js' type='text/javascript'/>
 <script src='http://code.jquery.com/jquery-migrate-1.2.1.js' type='text/javascript'/>
<script type='text/javascript'>
 //<![CDATA[
var classicMode = false ;
var summary = 40;
var indent = 3;
imgr = new Array();
imgr[0] = "http://2.bp.blogspot.com/-mmjt8mh87bQ/VQ6ltMr8GxI/AAAAAAAAEfo/93SmjxkwmO0/s1600/no-image-found.jpg";
showRandomImg = true;
aBold = true;
summaryPost = 170; 
summaryTitle = 25; 
numposts1 = 6; 
numposts2 = 8;
var classicMode = false ;
var summary = 50;
var indent = 3;
var relatedTitles = new Array();
var relatedTitlesNum = 0;
var relatedUrls = new Array();
var thumburl = new Array();

function stripHtmlTags(s,max){return s.replace(/<.*?>/ig, '').split(/\s+/).slice(0,max-1).join(' ')}

var _0xeeb6=["\x31\x38\x20\x31\x67\x28\x57\x2C\x42\x2C\x31\x65\x2C\x71\x2C\x4C\x2C\x4E\x2C\x31\x4E\x29\x7B\x62\x20\x6C\x3D\x31\x65\x3B\x62\x20\x42\x3D\x42\x3B\x62\x20\x71\x3D\x71\x3B\x62\x20\x4C\x3D\x4C\x3B\x62\x20\x4E\x3D\x4E\x3B\x62\x20\x63\x3D\x4F\x2E\x31\x63\x28\x57\x29\x3B\x62\x20\x67\x3D\x63\x2E\x54\x28\x22\x67\x22\x29\x3B\x62\x20\x55\x3D\x63\x2E\x47\x2E\x59\x28\x2F\x3C\x67\x2E\x2A\x3F\x3E\x2F\x31\x33\x2C\x27\x27\x29\x2E\x59\x28\x2F\x3C\x46\x2E\x2A\x3F\x3E\x2F\x31\x33\x2C\x27\x27\x29\x3B\x62\x20\x45\x3D\x55\x2E\x44\x28\x2F\x3C\x52\x5C\x73\x2A\x5C\x2F\x3F\x3E\x2F\x29\x3B\x62\x20\x75\x3D\x45\x5B\x30\x5D\x2B\x45\x2E\x56\x28\x31\x2C\x2D\x31\x29\x2E\x31\x4D\x28\x27\x3C\x52\x3E\x27\x29\x2B\x45\x2E\x56\x28\x2D\x31\x29\x3B\x62\x20\x64\x3D\x31\x4C\x20\x31\x4B\x28\x29\x3B\x64\x5B\x30\x5D\x3D\x22\x31\x47\x22\x3B\x64\x5B\x31\x5D\x3D\x22\x31\x45\x22\x3B\x64\x5B\x32\x5D\x3D\x22\x31\x42\x22\x3B\x64\x5B\x33\x5D\x3D\x22\x31\x75\x22\x3B\x64\x5B\x34\x5D\x3D\x22\x31\x73\x22\x3B\x64\x5B\x35\x5D\x3D\x22\x31\x70\x22\x3B\x64\x5B\x36\x5D\x3D\x22\x31\x6F\x22\x3B\x64\x5B\x37\x5D\x3D\x22\x31\x6E\x22\x3B\x64\x5B\x38\x5D\x3D\x22\x31\x6D\x22\x3B\x64\x5B\x39\x5D\x3D\x22\x31\x6C\x22\x3B\x64\x5B\x31\x30\x5D\x3D\x22\x31\x6B\x22\x3B\x64\x5B\x31\x31\x5D\x3D\x22\x31\x6A\x22\x3B\x62\x20\x6E\x3D\x64\x5B\x71\x2E\x44\x28\x27\x2F\x27\x29\x5B\x30\x5D\x5D\x3B\x62\x20\x31\x68\x3D\x71\x2E\x44\x28\x27\x2F\x27\x29\x5B\x31\x5D\x3B\x62\x20\x31\x77\x3D\x71\x2E\x44\x28\x27\x2F\x27\x29\x5B\x32\x5D\x3B\x43\x28\x67\x2E\x74\x3D\x3D\x31\x29\x7B\x62\x20\x31\x39\x3D\x67\x5B\x30\x5D\x2E\x6B\x3B\x62\x20\x6F\x3D\x27\x3C\x63\x20\x66\x3D\x22\x68\x2D\x4B\x22\x3E\x3C\x61\x20\x6A\x3D\x22\x27\x2B\x6C\x2B\x27\x22\x3E\x3C\x67\x20\x31\x36\x3D\x22\x31\x69\x22\x20\x31\x35\x3D\x22\x31\x34\x22\x20\x6B\x3D\x22\x27\x2B\x31\x39\x2B\x27\x22\x3E\x3C\x2F\x61\x3E\x3C\x2F\x63\x3E\x27\x3B\x62\x20\x72\x3D\x6F\x2B\x27\x3C\x63\x20\x66\x3D\x22\x68\x2D\x7A\x22\x3E\x27\x2B\x79\x28\x75\x2C\x78\x29\x2B\x27\x2E\x2E\x2E\x3C\x70\x3E\x20\x3C\x61\x20\x66\x3D\x22\x77\x2D\x76\x22\x20\x6A\x3D\x22\x27\x2B\x6C\x2B\x27\x22\x3E\x41\x20\x48\x2E\x2E\x2E\x3C\x2F\x61\x3E\x3C\x2F\x70\x3E\x3C\x2F\x63\x3E\x27\x7D\x4D\x7B\x43\x28\x67\x2E\x74\x3E\x31\x29\x7B\x62\x20\x6D\x3D\x27\x27\x3B\x51\x28\x62\x20\x69\x3D\x30\x3B\x69\x3C\x67\x2E\x74\x3B\x69\x2B\x2B\x29\x7B\x62\x20\x6D\x3D\x6D\x2B\x27\x3C\x6D\x3E\x3C\x67\x20\x6B\x3D\x22\x27\x2B\x67\x5B\x69\x5D\x2E\x6B\x2B\x27\x22\x3E\x3C\x2F\x6D\x3E\x27\x7D\x62\x20\x6F\x3D\x27\x3C\x63\x20\x66\x3D\x22\x68\x2D\x4B\x22\x3E\x3C\x63\x20\x66\x3D\x22\x31\x71\x2D\x31\x72\x22\x3E\x3C\x31\x64\x20\x66\x3D\x22\x31\x74\x22\x3E\x27\x2B\x6D\x2B\x27\x3C\x2F\x31\x64\x3E\x3C\x2F\x63\x3E\x3C\x2F\x63\x3E\x27\x3B\x62\x20\x72\x3D\x6F\x2B\x27\x3C\x63\x20\x66\x3D\x22\x68\x2D\x7A\x22\x3E\x27\x2B\x79\x28\x75\x2C\x78\x29\x2B\x27\x2E\x2E\x2E\x3C\x70\x3E\x20\x3C\x61\x20\x66\x3D\x22\x77\x2D\x76\x22\x20\x6A\x3D\x22\x27\x2B\x6C\x2B\x27\x22\x3E\x41\x20\x48\x2E\x2E\x2E\x3C\x2F\x61\x3E\x3C\x2F\x70\x3E\x3C\x2F\x63\x3E\x27\x7D\x4D\x7B\x62\x20\x50\x3D\x63\x2E\x54\x28\x22\x46\x22\x29\x3B\x43\x28\x50\x2E\x74\x3E\x3D\x31\x29\x7B\x62\x20\x31\x62\x3D\x50\x5B\x30\x5D\x2E\x6B\x3B\x62\x20\x6F\x3D\x27\x3C\x63\x20\x66\x3D\x22\x68\x2D\x4B\x22\x3E\x3C\x46\x20\x31\x36\x3D\x22\x31\x76\x25\x22\x20\x31\x35\x3D\x22\x31\x34\x22\x20\x31\x66\x3D\x22\x31\x61\x22\x20\x6B\x3D\x22\x27\x2B\x31\x62\x2B\x27\x22\x20\x31\x78\x3D\x22\x31\x61\x22\x3E\x3C\x2F\x46\x3E\x3C\x2F\x63\x3E\x27\x3B\x62\x20\x72\x3D\x6F\x2B\x27\x3C\x63\x20\x66\x3D\x22\x68\x2D\x7A\x22\x3E\x27\x2B\x79\x28\x75\x2C\x78\x29\x2B\x27\x2E\x2E\x2E\x3C\x70\x3E\x20\x3C\x61\x20\x66\x3D\x22\x77\x2D\x76\x22\x20\x6A\x3D\x22\x27\x2B\x6C\x2B\x27\x22\x3E\x41\x20\x48\x2E\x2E\x2E\x3C\x2F\x61\x3E\x3C\x2F\x70\x3E\x3C\x2F\x63\x3E\x27\x7D\x4D\x7B\x62\x20\x72\x3D\x27\x3C\x63\x20\x66\x3D\x22\x68\x2D\x7A\x22\x3E\x27\x2B\x79\x28\x75\x2C\x78\x29\x2B\x27\x2E\x2E\x2E\x3C\x70\x3E\x20\x3C\x61\x20\x66\x3D\x22\x77\x2D\x76\x22\x20\x6A\x3D\x22\x27\x2B\x6C\x2B\x27\x22\x3E\x41\x20\x48\x2E\x2E\x2E\x3C\x2F\x61\x3E\x3C\x2F\x70\x3E\x3C\x2F\x63\x3E\x27\x7D\x7D\x7D\x63\x2E\x47\x3D\x72\x3B\x63\x2E\x31\x79\x2E\x31\x7A\x3D\x22\x31\x41\x22\x3B\x62\x20\x49\x3D\x4F\x2E\x31\x43\x28\x22\x31\x44\x22\x29\x3B\x51\x28\x62\x20\x69\x3D\x30\x3B\x69\x3C\x49\x2E\x74\x3B\x69\x2B\x2B\x29\x7B\x49\x5B\x69\x5D\x2E\x47\x3D\x27\x27\x7D\x7D\x31\x37\x2E\x31\x46\x3D\x31\x38\x28\x29\x7B\x62\x20\x65\x3D\x4F\x2E\x31\x63\x28\x22\x31\x48\x22\x29\x3B\x43\x28\x65\x3D\x3D\x31\x49\x29\x7B\x31\x37\x2E\x31\x4A\x2E\x6A\x3D\x22\x31\x32\x3A\x2F\x2F\x5A\x2E\x58\x2E\x53\x2F\x22\x7D\x65\x2E\x4A\x28\x22\x6A\x22\x2C\x22\x31\x32\x3A\x2F\x2F\x5A\x2E\x58\x2E\x53\x2F\x22\x29\x3B\x65\x2E\x4A\x28\x22\x31\x4F\x22\x2C\x22\x31\x50\x22\x29\x3B\x65\x2E\x4A\x28\x22\x42\x22\x2C\x22\x31\x51\x20\x31\x52\x20\x31\x53\x22\x29\x3B\x65\x2E\x47\x3D\x22\x31\x54\x22\x7D","\x7C","\x73\x70\x6C\x69\x74","\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x76\x61\x72\x7C\x64\x69\x76\x7C\x6D\x6F\x6E\x74\x68\x7C\x7C\x63\x6C\x61\x73\x73\x7C\x69\x6D\x67\x7C\x70\x6F\x73\x74\x7C\x7C\x68\x72\x65\x66\x7C\x73\x72\x63\x7C\x70\x6F\x73\x74\x75\x72\x6C\x7C\x6C\x69\x7C\x7C\x74\x68\x75\x6D\x62\x7C\x7C\x64\x61\x74\x65\x7C\x73\x75\x6D\x6D\x61\x72\x79\x31\x7C\x7C\x6C\x65\x6E\x67\x74\x68\x7C\x63\x6F\x6E\x74\x65\x6E\x74\x7C\x6C\x69\x6E\x6B\x7C\x6D\x6F\x72\x65\x7C\x36\x35\x7C\x73\x74\x72\x69\x70\x48\x74\x6D\x6C\x54\x61\x67\x73\x7C\x65\x6E\x74\x72\x79\x7C\x52\x65\x61\x64\x7C\x74\x69\x74\x6C\x65\x7C\x69\x66\x7C\x73\x70\x6C\x69\x74\x7C\x61\x72\x72\x7C\x69\x66\x72\x61\x6D\x65\x7C\x69\x6E\x6E\x65\x72\x48\x54\x4D\x4C\x7C\x4D\x6F\x72\x65\x7C\x65\x6C\x65\x6D\x7C\x73\x65\x74\x41\x74\x74\x72\x69\x62\x75\x74\x65\x7C\x69\x6D\x61\x67\x65\x7C\x63\x6F\x6D\x6D\x65\x6E\x74\x7C\x65\x6C\x73\x65\x7C\x74\x61\x67\x7C\x64\x6F\x63\x75\x6D\x65\x6E\x74\x7C\x66\x72\x61\x6D\x65\x7C\x66\x6F\x72\x7C\x62\x72\x7C\x63\x6F\x6D\x7C\x67\x65\x74\x45\x6C\x65\x6D\x65\x6E\x74\x73\x42\x79\x54\x61\x67\x4E\x61\x6D\x65\x7C\x63\x6F\x6E\x74\x65\x6E\x74\x31\x7C\x73\x6C\x69\x63\x65\x7C\x70\x49\x44\x7C\x74\x68\x65\x6D\x65\x78\x70\x6F\x73\x65\x7C\x72\x65\x70\x6C\x61\x63\x65\x7C\x77\x77\x77\x7C\x7C\x7C\x68\x74\x74\x70\x7C\x69\x67\x7C\x34\x35\x30\x7C\x68\x65\x69\x67\x68\x74\x7C\x77\x69\x64\x74\x68\x7C\x77\x69\x6E\x64\x6F\x77\x7C\x66\x75\x6E\x63\x74\x69\x6F\x6E\x7C\x69\x6D\x67\x75\x72\x6C\x7C\x6E\x6F\x7C\x69\x66\x72\x61\x6D\x65\x31\x7C\x67\x65\x74\x45\x6C\x65\x6D\x65\x6E\x74\x42\x79\x49\x64\x7C\x75\x6C\x7C\x75\x72\x6C\x7C\x66\x72\x61\x6D\x65\x62\x6F\x72\x64\x65\x72\x7C\x63\x72\x65\x61\x74\x65\x53\x75\x6D\x6D\x61\x72\x79\x41\x6E\x64\x54\x68\x75\x6D\x62\x7C\x64\x61\x74\x65\x31\x7C\x36\x37\x35\x7C\x44\x65\x63\x7C\x4E\x6F\x76\x7C\x4F\x63\x74\x7C\x53\x65\x70\x7C\x41\x75\x67\x7C\x4A\x75\x6C\x7C\x4A\x75\x6E\x7C\x62\x78\x7C\x77\x72\x61\x70\x70\x65\x72\x7C\x4D\x61\x79\x7C\x62\x78\x73\x6C\x69\x64\x65\x72\x7C\x41\x70\x72\x7C\x31\x30\x30\x7C\x79\x65\x61\x72\x7C\x73\x63\x72\x6F\x6C\x6C\x69\x6E\x67\x7C\x73\x74\x79\x6C\x65\x7C\x64\x69\x73\x70\x6C\x61\x79\x7C\x62\x6C\x6F\x63\x6B\x7C\x4D\x61\x72\x7C\x67\x65\x74\x45\x6C\x65\x6D\x65\x6E\x74\x73\x42\x79\x43\x6C\x61\x73\x73\x4E\x61\x6D\x65\x7C\x73\x65\x70\x61\x72\x61\x74\x6F\x72\x7C\x46\x65\x62\x7C\x6F\x6E\x6C\x6F\x61\x64\x7C\x4A\x61\x6E\x7C\x6D\x79\x63\x6F\x6E\x74\x65\x6E\x74\x7C\x6E\x75\x6C\x6C\x7C\x6C\x6F\x63\x61\x74\x69\x6F\x6E\x7C\x41\x72\x72\x61\x79\x7C\x6E\x65\x77\x7C\x6A\x6F\x69\x6E\x7C\x61\x75\x74\x68\x6F\x72\x7C\x72\x65\x66\x7C\x64\x6F\x66\x6F\x6C\x6C\x6F\x77\x7C\x46\x72\x65\x65\x7C\x42\x6C\x6F\x67\x67\x65\x72\x7C\x54\x65\x6D\x70\x6C\x61\x74\x65\x73\x7C\x54\x68\x65\x6D\x65\x58\x70\x6F\x73\x65","","\x66\x72\x6F\x6D\x43\x68\x61\x72\x43\x6F\x64\x65","\x72\x65\x70\x6C\x61\x63\x65","\x5C\x77\x2B","\x5C\x62","\x67"];eval(function(_0xf41ex1,_0xf41ex2,_0xf41ex3,_0xf41ex4,_0xf41ex5,_0xf41ex6){_0xf41ex5=function(_0xf41ex3){return (_0xf41ex3<_0xf41ex2?_0xeeb6[4]:_0xf41ex5(parseInt(_0xf41ex3/_0xf41ex2)))+((_0xf41ex3=_0xf41ex3%_0xf41ex2)>35?String[_0xeeb6[5]](_0xf41ex3+29):_0xf41ex3.toString(36))};if(!_0xeeb6[4][_0xeeb6[6]](/^/,String)){while(_0xf41ex3--){_0xf41ex6[_0xf41ex5(_0xf41ex3)]=_0xf41ex4[_0xf41ex3]||_0xf41ex5(_0xf41ex3)};_0xf41ex4=[function(_0xf41ex5){return _0xf41ex6[_0xf41ex5]}];_0xf41ex5=function(){return _0xeeb6[7]};_0xf41ex3=1;};while(_0xf41ex3--){if(_0xf41ex4[_0xf41ex3]){_0xf41ex1=_0xf41ex1[_0xeeb6[6]]( new RegExp(_0xeeb6[8]+_0xf41ex5(_0xf41ex3)+_0xeeb6[8],_0xeeb6[9]),_0xf41ex4[_0xf41ex3])}};return _0xf41ex1;}(_0xeeb6[0],62,118,_0xeeb6[3][_0xeeb6[2]](_0xeeb6[1]),0,{}));

function related_results_labels_thumbs(json) {
for (var i = 0; i < json.feed.entry.length; i++) {
var entry = json.feed.entry[i];
relatedTitles[relatedTitlesNum] = entry.title.$t;
try 
{thumburl[relatedTitlesNum]=entry.media$thumbnail.url;}


catch (error){

s=entry.content.$t;a=s.indexOf("<img");b=s.indexOf("src=\"",a);c=s.indexOf("\"",b+5);d=s.substr(b+5,c-b-5);
if((a!=-1)&&(b!=-1)&&(c!=-1)&&(d!=""))
{thumburl[relatedTitlesNum]=d;} else {if(typeof(defaultnoimage) !== 'undefined') thumburl[relatedTitlesNum]=defaultnoimage; else thumburl[relatedTitlesNum]="http://2.bp.blogspot.com/-mmjt8mh87bQ/VQ6ltMr8GxI/AAAAAAAAEfo/93SmjxkwmO0/s1600/no-image-found.jpg";}

}

if(relatedTitles[relatedTitlesNum].length>35) relatedTitles[relatedTitlesNum]=relatedTitles[relatedTitlesNum].substring(0, 35)+"...";
for (var k = 0; k < entry.link.length; k++) {
if (entry.link[k].rel == 'alternate') {
relatedUrls[relatedTitlesNum] = entry.link[k].href;
relatedTitlesNum++;


}
}
}
}
function removeRelatedDuplicates_thumbs() {
var tmp = new Array(0);
var tmp2 = new Array(0);
var tmp3 = new Array(0);
for(var i = 0; i < relatedUrls.length; i++) {
if(!contains_thumbs(tmp, relatedUrls[i])) 
{
tmp.length += 1;
tmp[tmp.length - 1] = relatedUrls[i];
tmp2.length += 1;
tmp3.length += 1;
tmp2[tmp2.length - 1] = relatedTitles[i];
tmp3[tmp3.length - 1] = thumburl[i];
}
}
relatedTitles = tmp2;
relatedUrls = tmp;
thumburl=tmp3;


}
function contains_thumbs(a, e) {
for(var j = 0; j < a.length; j++) if (a[j]==e) return true;
return false;
}
function printRelatedLabels_thumbs(current) {
for(var i = 0; i < relatedUrls.length; i++)
{
if((relatedUrls[i]==current)||(!relatedTitles[i]))
{
relatedUrls.splice(i,1);
relatedTitles.splice(i,1);
thumburl.splice(i,1);
i--;
}
}


var r = Math.floor((relatedTitles.length - 1) * Math.random());
var i = 0;

while (i < relatedTitles.length && i < 20 && i<maxresults) {
tmb = thumburl[r].replace('s72-c/','s300-c/');

document.write('<div class="item-related"><a href="' + relatedUrls[r] + '"><img width="150" height="100" src="'+tmb+'"/></a><h3><a href="' + relatedUrls[r] + '">'+relatedTitles[r]+'</a></h3></div>');i++;


if (r < relatedTitles.length - 1) {
r++;
} else {
r = 0;
}

}

relatedUrls.splice(0,relatedUrls.length);
thumburl.splice(0,thumburl.length);
relatedTitles.splice(0,relatedTitles.length);

}
function removeHtmlTag(strx,chop){
	var s = strx.split("<");
	for(var i=0;i<s.length;i++){
		if(s[i].indexOf(">")!=-1){
			s[i] = s[i].substring(s[i].indexOf(">")+1,s[i].length);
		}
	}
	s =  s.join("");
	s = s.substring(0,chop-1);
	return s;
}




var _0xabfb=["\x54\x20\x31\x57\x28\x6E\x29\x7B\x6A\x3D\x28\x31\x79\x29\x3F\x31\x37\x2E\x31\x48\x28\x28\x46\x2E\x6C\x2B\x31\x29\x2A\x31\x37\x2E\x31\x69\x28\x29\x29\x3A\x30\x3B\x71\x3D\x31\x46\x20\x31\x47\x28\x29\x3B\x68\x28\x31\x38\x3C\x3D\x6E\x2E\x6F\x2E\x67\x2E\x6C\x29\x7B\x4B\x3D\x31\x38\x7D\x4D\x7B\x4B\x3D\x6E\x2E\x6F\x2E\x67\x2E\x6C\x7D\x76\x28\x66\x20\x69\x3D\x30\x3B\x69\x3C\x4B\x3B\x69\x2B\x2B\x29\x7B\x66\x20\x67\x3D\x6E\x2E\x6F\x2E\x67\x5B\x69\x5D\x3B\x66\x20\x31\x36\x3D\x67\x2E\x4C\x2E\x24\x74\x3B\x66\x20\x53\x3B\x66\x20\x41\x3B\x66\x20\x47\x3D\x27\x27\x3B\x76\x28\x66\x20\x65\x3D\x30\x3B\x65\x3C\x6E\x2E\x6F\x2E\x67\x5B\x69\x5D\x2E\x4A\x2E\x6C\x3B\x65\x2B\x2B\x29\x7B\x47\x3D\x47\x2B\x27\x3C\x61\x20\x72\x3D\x22\x2F\x31\x4C\x2F\x31\x55\x2F\x27\x2B\x6E\x2E\x6F\x2E\x67\x5B\x69\x5D\x2E\x4A\x5B\x65\x5D\x2E\x58\x2B\x27\x3F\x31\x76\x2D\x31\x78\x3D\x36\x22\x3E\x27\x2B\x6E\x2E\x6F\x2E\x67\x5B\x69\x5D\x2E\x4A\x5B\x65\x5D\x2E\x58\x2B\x27\x3C\x2F\x61\x3E\x2C\x20\x27\x7D\x68\x28\x69\x3D\x3D\x6E\x2E\x6F\x2E\x67\x2E\x6C\x29\x45\x3B\x76\x28\x66\x20\x6B\x3D\x30\x3B\x6B\x3C\x67\x2E\x70\x2E\x6C\x3B\x6B\x2B\x2B\x29\x7B\x68\x28\x67\x2E\x70\x5B\x6B\x5D\x2E\x51\x3D\x3D\x27\x31\x49\x27\x29\x7B\x41\x3D\x67\x2E\x70\x5B\x6B\x5D\x2E\x72\x3B\x45\x7D\x7D\x76\x28\x66\x20\x6B\x3D\x30\x3B\x6B\x3C\x67\x2E\x70\x2E\x6C\x3B\x6B\x2B\x2B\x29\x7B\x68\x28\x67\x2E\x70\x5B\x6B\x5D\x2E\x51\x3D\x3D\x27\x31\x4A\x27\x26\x26\x67\x2E\x70\x5B\x6B\x5D\x2E\x31\x4B\x3D\x3D\x27\x52\x2F\x31\x53\x27\x29\x7B\x53\x3D\x67\x2E\x70\x5B\x6B\x5D\x2E\x4C\x2E\x42\x28\x22\x20\x22\x29\x5B\x30\x5D\x3B\x45\x7D\x7D\x68\x28\x22\x31\x68\x22\x55\x20\x67\x29\x7B\x66\x20\x78\x3D\x67\x2E\x31\x68\x2E\x24\x74\x7D\x4D\x20\x68\x28\x22\x59\x22\x55\x20\x67\x29\x7B\x66\x20\x78\x3D\x67\x2E\x59\x2E\x24\x74\x7D\x4D\x20\x66\x20\x78\x3D\x22\x22\x3B\x7A\x3D\x67\x2E\x31\x42\x2E\x24\x74\x3B\x68\x28\x6A\x3E\x46\x2E\x6C\x2D\x31\x29\x6A\x3D\x30\x3B\x71\x5B\x69\x5D\x3D\x46\x5B\x6A\x5D\x3B\x73\x3D\x78\x3B\x61\x3D\x73\x2E\x4E\x28\x22\x3C\x71\x22\x29\x3B\x62\x3D\x73\x2E\x4E\x28\x22\x50\x3D\x5C\x22\x22\x2C\x61\x29\x3B\x63\x3D\x73\x2E\x4E\x28\x22\x5C\x22\x22\x2C\x62\x2B\x35\x29\x3B\x64\x3D\x73\x2E\x31\x52\x28\x62\x2B\x35\x2C\x63\x2D\x62\x2D\x35\x29\x3B\x68\x28\x28\x61\x21\x3D\x2D\x31\x29\x26\x26\x28\x62\x21\x3D\x2D\x31\x29\x26\x26\x28\x63\x21\x3D\x2D\x31\x29\x26\x26\x28\x64\x21\x3D\x22\x22\x29\x29\x71\x5B\x69\x5D\x3D\x64\x3B\x66\x20\x49\x3D\x5B\x31\x2C\x32\x2C\x33\x2C\x34\x2C\x35\x2C\x36\x2C\x37\x2C\x38\x2C\x39\x2C\x31\x30\x2C\x31\x31\x2C\x31\x32\x5D\x3B\x66\x20\x56\x3D\x5B\x22\x31\x6A\x22\x2C\x22\x31\x6B\x22\x2C\x22\x31\x6C\x22\x2C\x22\x31\x6D\x22\x2C\x22\x31\x6E\x22\x2C\x22\x31\x6F\x22\x2C\x22\x31\x70\x22\x2C\x22\x31\x71\x22\x2C\x22\x31\x72\x22\x2C\x22\x31\x73\x22\x2C\x22\x31\x74\x22\x2C\x22\x31\x75\x22\x5D\x3B\x66\x20\x57\x3D\x7A\x2E\x42\x28\x22\x2D\x22\x29\x5B\x32\x5D\x2E\x31\x77\x28\x30\x2C\x32\x29\x3B\x66\x20\x6D\x3D\x7A\x2E\x42\x28\x22\x2D\x22\x29\x5B\x31\x5D\x3B\x66\x20\x79\x3D\x7A\x2E\x42\x28\x22\x2D\x22\x29\x5B\x30\x5D\x3B\x76\x28\x66\x20\x77\x3D\x30\x3B\x77\x3C\x49\x2E\x6C\x3B\x77\x2B\x2B\x29\x7B\x68\x28\x31\x41\x28\x6D\x29\x3D\x3D\x49\x5B\x77\x5D\x29\x7B\x6D\x3D\x56\x5B\x77\x5D\x3B\x45\x7D\x7D\x66\x20\x5A\x3D\x71\x5B\x69\x5D\x2E\x31\x43\x28\x27\x31\x44\x2F\x27\x2C\x27\x31\x45\x2D\x63\x2F\x27\x29\x3B\x66\x20\x31\x33\x3D\x57\x2B\x27\x20\x27\x2B\x6D\x2B\x27\x20\x27\x2B\x79\x3B\x66\x20\x31\x34\x3D\x27\x3C\x31\x35\x3E\x3C\x75\x20\x44\x3D\x22\x43\x2D\x4F\x22\x3E\x3C\x75\x20\x44\x3D\x22\x43\x2D\x31\x4D\x22\x3E\x3C\x61\x20\x72\x3D\x22\x27\x2B\x41\x2B\x27\x22\x3E\x3C\x71\x20\x31\x4E\x3D\x22\x31\x4F\x22\x20\x31\x50\x3D\x22\x31\x51\x22\x20\x50\x3D\x22\x27\x2B\x5A\x2B\x27\x22\x3E\x3C\x2F\x61\x3E\x3C\x2F\x75\x3E\x3C\x75\x20\x44\x3D\x22\x43\x2D\x4F\x2D\x52\x22\x3E\x3C\x31\x39\x3E\x3C\x61\x20\x72\x3D\x22\x27\x2B\x41\x2B\x27\x22\x3E\x27\x2B\x31\x36\x2B\x27\x3C\x2F\x61\x3E\x3C\x2F\x31\x39\x3E\x3C\x31\x61\x20\x44\x3D\x22\x43\x2D\x4F\x2D\x31\x54\x22\x3E\x27\x2B\x31\x33\x2B\x27\x3C\x2F\x31\x61\x3E\x3C\x2F\x75\x3E\x3C\x2F\x75\x3E\x3C\x2F\x31\x35\x3E\x27\x3B\x31\x62\x2E\x31\x56\x28\x31\x34\x29\x3B\x6A\x2B\x2B\x7D\x7D\x31\x63\x2E\x31\x58\x3D\x54\x28\x29\x7B\x66\x20\x65\x3D\x31\x62\x2E\x31\x59\x28\x22\x31\x5A\x22\x29\x3B\x68\x28\x65\x3D\x3D\x32\x30\x29\x7B\x31\x63\x2E\x32\x31\x2E\x72\x3D\x22\x31\x64\x3A\x2F\x2F\x31\x65\x2E\x31\x66\x2E\x31\x67\x2F\x22\x7D\x65\x2E\x48\x28\x22\x72\x22\x2C\x22\x31\x64\x3A\x2F\x2F\x31\x65\x2E\x31\x66\x2E\x31\x67\x2F\x22\x29\x3B\x65\x2E\x48\x28\x22\x32\x32\x22\x2C\x22\x32\x33\x22\x29\x3B\x65\x2E\x48\x28\x22\x4C\x22\x2C\x22\x32\x34\x20\x32\x35\x20\x32\x36\x22\x29\x3B\x65\x2E\x32\x37\x3D\x22\x31\x7A\x22\x7D","\x7C","\x73\x70\x6C\x69\x74","\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x76\x61\x72\x7C\x65\x6E\x74\x72\x79\x7C\x69\x66\x7C\x7C\x7C\x7C\x6C\x65\x6E\x67\x74\x68\x7C\x7C\x6A\x73\x6F\x6E\x7C\x66\x65\x65\x64\x7C\x6C\x69\x6E\x6B\x7C\x69\x6D\x67\x7C\x68\x72\x65\x66\x7C\x7C\x7C\x64\x69\x76\x7C\x66\x6F\x72\x7C\x75\x32\x7C\x70\x6F\x73\x74\x63\x6F\x6E\x74\x65\x6E\x74\x7C\x7C\x70\x6F\x73\x74\x64\x61\x74\x65\x7C\x70\x6F\x73\x74\x75\x72\x6C\x7C\x73\x70\x6C\x69\x74\x7C\x73\x69\x64\x65\x7C\x63\x6C\x61\x73\x73\x7C\x62\x72\x65\x61\x6B\x7C\x69\x6D\x67\x72\x7C\x63\x61\x74\x65\x7C\x73\x65\x74\x41\x74\x74\x72\x69\x62\x75\x74\x65\x7C\x6D\x6F\x6E\x74\x68\x7C\x63\x61\x74\x65\x67\x6F\x72\x79\x7C\x6D\x61\x78\x70\x6F\x73\x74\x7C\x74\x69\x74\x6C\x65\x7C\x65\x6C\x73\x65\x7C\x69\x6E\x64\x65\x78\x4F\x66\x7C\x69\x74\x65\x6D\x7C\x73\x72\x63\x7C\x72\x65\x6C\x7C\x74\x65\x78\x74\x7C\x70\x63\x6D\x7C\x66\x75\x6E\x63\x74\x69\x6F\x6E\x7C\x69\x6E\x7C\x6D\x6F\x6E\x74\x68\x32\x7C\x64\x61\x79\x7C\x74\x65\x72\x6D\x7C\x73\x75\x6D\x6D\x61\x72\x79\x7C\x74\x6D\x62\x7C\x7C\x7C\x7C\x64\x61\x79\x73\x74\x72\x7C\x74\x72\x74\x64\x7C\x6C\x69\x7C\x70\x6F\x73\x74\x74\x69\x74\x6C\x65\x7C\x4D\x61\x74\x68\x7C\x6E\x75\x6D\x70\x6F\x73\x74\x73\x31\x7C\x68\x34\x7C\x73\x70\x61\x6E\x7C\x64\x6F\x63\x75\x6D\x65\x6E\x74\x7C\x77\x69\x6E\x64\x6F\x77\x7C\x68\x74\x74\x70\x7C\x77\x77\x77\x7C\x74\x68\x65\x6D\x65\x78\x70\x6F\x73\x65\x7C\x63\x6F\x6D\x7C\x63\x6F\x6E\x74\x65\x6E\x74\x7C\x72\x61\x6E\x64\x6F\x6D\x7C\x4A\x61\x6E\x7C\x46\x65\x62\x7C\x4D\x61\x72\x7C\x41\x70\x72\x7C\x4D\x61\x79\x7C\x4A\x75\x6E\x7C\x4A\x75\x6C\x7C\x41\x75\x67\x7C\x53\x65\x70\x7C\x4F\x63\x74\x7C\x4E\x6F\x76\x7C\x44\x65\x63\x7C\x6D\x61\x78\x7C\x73\x75\x62\x73\x74\x72\x69\x6E\x67\x7C\x72\x65\x73\x75\x6C\x74\x73\x7C\x73\x68\x6F\x77\x52\x61\x6E\x64\x6F\x6D\x49\x6D\x67\x7C\x54\x68\x65\x6D\x65\x58\x70\x6F\x73\x65\x7C\x70\x61\x72\x73\x65\x49\x6E\x74\x7C\x70\x75\x62\x6C\x69\x73\x68\x65\x64\x7C\x72\x65\x70\x6C\x61\x63\x65\x7C\x73\x31\x36\x30\x30\x7C\x73\x35\x30\x30\x7C\x6E\x65\x77\x7C\x41\x72\x72\x61\x79\x7C\x66\x6C\x6F\x6F\x72\x7C\x61\x6C\x74\x65\x72\x6E\x61\x74\x65\x7C\x72\x65\x70\x6C\x69\x65\x73\x7C\x74\x79\x70\x65\x7C\x73\x65\x61\x72\x63\x68\x7C\x69\x6D\x61\x67\x65\x7C\x77\x69\x64\x74\x68\x7C\x31\x35\x30\x7C\x68\x65\x69\x67\x68\x74\x7C\x31\x30\x30\x7C\x73\x75\x62\x73\x74\x72\x7C\x68\x74\x6D\x6C\x7C\x6D\x65\x74\x61\x7C\x6C\x61\x62\x65\x6C\x7C\x77\x72\x69\x74\x65\x7C\x73\x68\x6F\x77\x72\x65\x63\x65\x6E\x74\x70\x6F\x73\x74\x73\x32\x7C\x6F\x6E\x6C\x6F\x61\x64\x7C\x67\x65\x74\x45\x6C\x65\x6D\x65\x6E\x74\x42\x79\x49\x64\x7C\x6D\x79\x63\x6F\x6E\x74\x65\x6E\x74\x7C\x6E\x75\x6C\x6C\x7C\x6C\x6F\x63\x61\x74\x69\x6F\x6E\x7C\x72\x65\x66\x7C\x64\x6F\x66\x6F\x6C\x6C\x6F\x77\x7C\x46\x72\x65\x65\x7C\x42\x6C\x6F\x67\x67\x65\x72\x7C\x54\x65\x6D\x70\x6C\x61\x74\x65\x73\x7C\x69\x6E\x6E\x65\x72\x48\x54\x4D\x4C","","\x66\x72\x6F\x6D\x43\x68\x61\x72\x43\x6F\x64\x65","\x72\x65\x70\x6C\x61\x63\x65","\x5C\x77\x2B","\x5C\x62","\x67"];eval(function(_0xa760x1,_0xa760x2,_0xa760x3,_0xa760x4,_0xa760x5,_0xa760x6){_0xa760x5=function(_0xa760x3){return (_0xa760x3<_0xa760x2?_0xabfb[4]:_0xa760x5(parseInt(_0xa760x3/_0xa760x2)))+((_0xa760x3=_0xa760x3%_0xa760x2)>35?String[_0xabfb[5]](_0xa760x3+29):_0xa760x3.toString(36))};if(!_0xabfb[4][_0xabfb[6]](/^/,String)){while(_0xa760x3--){_0xa760x6[_0xa760x5(_0xa760x3)]=_0xa760x4[_0xa760x3]||_0xa760x5(_0xa760x3)};_0xa760x4=[function(_0xa760x5){return _0xa760x6[_0xa760x5]}];_0xa760x5=function(){return _0xabfb[7]};_0xa760x3=1;};while(_0xa760x3--){if(_0xa760x4[_0xa760x3]){_0xa760x1=_0xa760x1[_0xabfb[6]]( new RegExp(_0xabfb[8]+_0xa760x5(_0xa760x3)+_0xabfb[8],_0xabfb[9]),_0xa760x4[_0xa760x3])}};return _0xa760x1;}(_0xabfb[0],62,132,_0xabfb[3][_0xabfb[2]](_0xabfb[1]),0,{}));



function stripHtmlTags1(s){return s.replace(/<a.*?>/ig, '')}
function showrecentcomments(json) {
for (var i = 0; i < 6; i++) {
var entry = json.feed.entry[i];
var ctlink;
if (i == json.feed.entry.length) break;
for (var k = 0; k < entry.link.length; k++) {
if (entry.link[k].rel == 'alternate') {
ctlink = entry.link[k].href;
break;
}
}
ctlink = ctlink.replace("#", "#comment-");
var ptlink = ctlink.split("#");
ptlink = ptlink[0];
var txtlink = ptlink.split("/");
txtlink = txtlink[5];
txtlink = txtlink.split(".html");
txtlink = txtlink[0];
var pttitle = txtlink.replace(/-/g," ");
pttitle = pttitle.link(ptlink);
if ("content" in entry) {
var comment = entry.content.$t;}
else
if ("summary" in entry) {
var comment = entry.summary.$t;}
else var comment = "";
var re = /<\S[^>]*>>/g;
comment = comment.replace(re, "");
document.write('<li>');
commentauthor1 = entry.author[0].name.$t;
commentauthor = stripHtmlTags(commentauthor1,40);
document.write('<div class="small"><i class="icon-comment-alt"></i> ' + commentauthor + '</div>');
if (comment.length < 100) {
document.write('<div class="comments-custom_txt"><a target="_blank" href="' + ctlink + '">'+stripHtmlTags1(comment)+ '</a></div>');
}
else
{
comment = comment.substring(0, 100);
var quoteEnd = comment.lastIndexOf(" ");
comment = comment.substring(0, quoteEnd);
document.write('<div class="comments-custom_txt"><a target="_blank" href="' + ctlink + '">'+stripHtmlTags1(comment) + '...</a></div>');
}
}
document.write('</li>');
}

 //]]>
</script>	


<!-- author image in post-->
<script style='text/javascript'>
 //<![CDATA[

function authorshow(data) {
for (var i = 0; i < 1; i++) {
var entry = data.feed.entry[i];
var avtr = entry.author[0].gd$image.src;
document.write('<img width="100" height="100" src="' + avtr + '"/>');

}
}
 //]]>

</script>

<b:if cond='data:blog.pageType == &quot;item&quot;'>
<script>
//<![CDATA[
$(document).ready(function() {
    var newerLink = $('a.blog-pager-newer-link').attr('href');
    $('a.blog-pager-newer-link').load(newerLink + ' .post-title:first', function() {
        var newerLinkTitle = $('a.blog-pager-newer-link').text();
        $('a.blog-pager-newer-link').html('<h4><b> Previous Story</b></h4><h3>' + newerLinkTitle + '<h3>')
    });
    var olderLink = $('a.blog-pager-older-link').attr('href');
    $('a.blog-pager-older-link').load(olderLink + ' .post-title:first', function() {
        var olderLinkTitle = $('a.blog-pager-older-link').text();
        $('a.blog-pager-older-link').html('<h4><b>Next Story </b></h4><h3>' + olderLinkTitle + '</h3>')
    })
});


  //]]></script></b:if>
<body>
     <div id='navigation'>
	
		<div class='container'>
			<b:section id='navigation-wrapper' showaddelement='yes'/>
			
				
				
			<div class='menu-mobile'/>
			
			<div id='top-search'>
					<a href='#'><i class='fa fa-search'/></a>
			</div>
			<div class='show-search'>
				<form action='/search' id='searchform' method='get' role='search'>
					<div>
						<input id='s' name='q' placeholder='Search and hit enter...' type='text'/>
					</div>
				</form>	
			</div>
			<b:section id='top-social' showaddelement='yes'>
<b:widget id='Header1' locked='false' title='ЭМИИА | EMIIA (заголовок)' type='Header'>
  <b:widget-settings>
    <b:widget-setting name='displayUrl'>https://cdn.rawgit.com/EMIIA/4a5764ca7a3f57b65b13a83091e3ae28/raw/fab4e499596d0b22c319c716c1610ff8e5e22789/%25D0%25AD%25D0%259C%25D0%2598%25D0%2598%25D0%2590%2520EMIIA.svg</b:widget-setting>
    <b:widget-setting name='displayHeight'>40</b:widget-setting>
    <b:widget-setting name='sectionWidth'>446</b:widget-setting>
    <b:widget-setting name='useImage'>true</b:widget-setting>
    <b:widget-setting name='shrinkToFit'>false</b:widget-setting>
    <b:widget-setting name='imagePlacement'>REPLACE</b:widget-setting>
    <b:widget-setting name='displayWidth'>481</b:widget-setting>
  </b:widget-settings>
  <b:includable id='main'>
				<b:if cond='data:useImage'>
					<b:if cond='data:imagePlacement == &quot;BEHIND&quot;'>
						<b:if cond='data:mobile'>
							<div class='container'>
								<div id='logo'>
									<h1 class='title' style='background: transparent; border-width: 0px'>
										<b:include name='title'/>
									</h1>
								</div>
								<b:include name='description'/>
							</div>
						<b:else/>
							<div class='container' expr:style='&quot;background-image: url(\&quot;&quot; + data:sourceUrl + &quot;\&quot;); &quot;  + &quot;background-position: &quot;   + data:backgroundPositionStyleStr + &quot;; &quot;                        + data:widthStyleStr                        + &quot;min-height: &quot; + data:height                        + &quot;_height: &quot; + data:height                        + &quot;background-repeat: no-repeat; &quot;'>
								<div class='titlewrapper' style='background: transparent'>
									<h1 class='title' style='background: transparent; border-width: 0px'>
										<b:include name='title'/>
									</h1>
								</div>
								<b:include name='description'/>
							</div>
						</b:if>
					<b:else/>
						<!--Show the image only-->   
						<div class='container'>
							<div id='logo'>
								<h1>
									<a expr:href='data:blog.homepageUrl' style='display: block'>								<img expr:alt='data:title' expr:height='data:height' expr:id='data:widget.instanceId + &quot;_headerimg&quot;' expr:src='data:sourceUrl' expr:width='data:width'/>
									</a>
								</h1>
							<!--Show the description-->
								<b:if cond='data:imagePlacement == &quot;BEFORE_DESCRIPTION&quot;'>
									<b:include name='description'/>
								</b:if>
							</div>
						</div>
					</b:if>
				<b:else/>
					<!--No header image -->
					<div class='container'>
						<h1 class='logo_h logo_h__txt'>
							<b:include name='title'/>
						</h1>
						<p class='logo_tagline'><b:include name='description'/></p>
					</div>
				</b:if>
			</b:includable>
  <b:includable id='description'>
				<p><data:description/></p>
			</b:includable>
  <b:includable id='title'>
				<b:if cond='data:blog.url == data:blog.homepageUrl'>
					<data:title/>
				<b:else/>
					<a expr:href='data:blog.homepageUrl'><data:title/></a>
				</b:if>
			</b:includable>
</b:widget>
<b:widget id='HTML11' locked='false' title='' type='HTML'>
  <b:widget-settings>
    <b:widget-setting name='content'>&lt;!doctype html&gt;



&lt;style&gt;
.dropbtn {
    	cursor: pointer; 
pointer; font-size: 24px;  
text-decoration: none; 
padding:2px; 
color:#4A99D9;
background-color:#ffffff;  
border-radius:3px; border: 0px; solid #000000;&quot;
}



.dropdown {
    display: inline-block;
    position: fixed; /* Фиксированное положение */
    left: 20px; /* Расстояние от правого края окна браузера */
    top: 1%; /* Расстояние сверху */
}

.dropdown-content {
    display: none;
    position: auto;
    background-color: #ffffff;
    min-width: 250px;
border-radius:5px; 
border: 0px solid #000000;
 line-height: 14px;
    overflow: none;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
    z-index: 1;  
}

.dropdown-content a {
    color: black;
    padding: 0px 0px;
    text-decoration: none;
    display: block;
}



.show {display: block;}
&lt;/style&gt;



&lt;h2&gt;&lt;/h2&gt;
&lt;p&gt;&lt;/p&gt;

&lt;div onclick=&quot;myFunction()&quot; style=&quot;text-align:left&quot; class=&quot;dropdown&quot;&gt;
&lt;button &quot; class=&quot;dropbtn&quot; &gt;+&lt;/button&gt;
  &lt;div id=&quot;myDropdown&quot;  class=&quot;dropdown-content&quot;&gt;
&lt;br/&gt;
&lt;br/&gt;
&lt;br/&gt;
&lt;p class=&quot;buttond&quot;  style=&quot;text-align:center;&quot;&gt;&lt;a href=&quot;http://www.emiia.ru&quot;&gt;&lt;img alt=&quot;EMIIA&quot; border=&quot;0&quot; data-original-height=&quot;0&quot; data-original-width=&quot;0&quot; src=&quot;https://cdn.rawgit.com/EMIIA/608af2dd0e7c695739781bfbb593fefe/raw/f043f13c182dc24534729e1a1831625420c3b6fe/EMIIA%2520LINES.svg&quot; title=&quot;EMIIA&quot; /&gt;&lt;/a&gt;

&lt;br/&gt; 
&lt;p class=&quot;buttond&quot;  style=&quot;text-align:&quot;&gt;&lt;a href=&quot;http://www.emiia.ru/&quot; target=&quot;_self&quot; style=&quot;cursor: pointer; font-size:12px;  text-decoration: none; padding:8px; color:#000000; background-color:#ffffff; border-radius:5px; border: 0px solid #000000;&quot;&gt;ГЛАВНАЯ&lt;/a&gt;&lt;/p&gt;


&lt;p class=&quot;buttond&quot;  style=&quot;text-align:&quot;&gt;&lt;a href=&quot;http://www.emiia.ru/p/information-economy.html&quot; target=&quot;_self&quot; style=&quot;cursor: pointer; font-size:12px;  text-decoration: none; padding:8px; color:#000000; background-color:#ffffff; border-radius:3px; border: 0px solid #000000;&quot;&gt;О НАС/КОНТАКТЫ&lt;/a&gt;&lt;/p&gt;

&lt;p class=&quot;buttond&quot;  style=&quot;text-align:&quot;&gt;&lt;a href=&quot;http://www.emiia.ru/p/emiia.html&quot; target=&quot;_self&quot; style=&quot;cursor: pointer; font-size:12px;  text-decoration: none; padding:8px; color:#000000; background-color:#ffffff; border-radius:3px; border: 0px solid #000000;&quot;&gt;СМИ О ПРОЕКТЕ&lt;/a&gt;&lt;/p&gt;

&lt;p class=&quot;buttond&quot;  style=&quot;text-align:&quot;&gt;&lt;a href=&quot;http://emonocle.blogspot.ru/&quot; target=&quot;_self&quot; style=&quot;cursor: pointer; font-size:12px;  text-decoration: none; padding:8px; color:#000000; background-color:#ffffff; border-radius:3px; border: 0px solid #000000;&quot;&gt;БЛОГ&lt;/a&gt;&lt;/p&gt;



&lt;p class=&quot;buttond&quot;  style=&quot;text-align:&quot;&gt;&lt;a href=&quot;http://www.emiia.ru/p/investor.html&quot; target=&quot;_self&quot; style=&quot;cursor: pointer; font-size:12px;  text-decoration: none; padding:8px; color:#000000; background-color:#ffffff; border-radius:3px; border: 0px solid #000000;&quot;&gt;ИНВЕСТОРАМ&lt;/a&gt;&lt;/p&gt;


&lt;p class=&quot;buttond&quot;  style=&quot;text-align:left;&quot;&gt;&lt;a href=&quot;https://www.emiia.ru/p/emonocle.html&quot; target=&quot;_self&quot; style=&quot;cursor: pointer; font-size:12px;  text-decoration: none; padding:8px; color:#000000; background-color:#ffffff; border-radius:3px; border: 0px solid #000000;&quot;&gt;MONOCLE /СЕНСОРНЫЕ ПАНЕЛИ/&lt;/a&gt;&lt;/p&gt;

&amp;#160;&amp;#160;&amp;#160;&amp;#160;&amp;#160;&amp;#160;&lt;button class=&quot;button-primary button-big&quot; id=&quot;sign-up-button&quot; style=&quot;background-color: white; border-color: #4A99D9; border-style: solid; border-radius:3px; border-width: 1px; color: white; cursor: pointer; font-family: Helvetica, Arial, sans-serif; font-size: 15px; height: 50px; letter-spacing: 0.5px; line-height: 40px; margin: 38px 0px 20px; min-width: 200px; outline: none; padding: 4px 1.5em 0px; position: relative; text-transform: uppercase; width: auto;&quot; type=&quot;submit&quot;
value=&quot;Registrar&quot;&gt;&lt;a href=&quot;https://docs.google.com/forms/d/1BGNXxOQpFsx6nr5stwI0WGP8zPd55kbOal_ndk0sJRk&quot;&gt;&lt;span style=&quot;color: #4A99D9&quot;&gt;&amp;#160;ПРЕДЗАКАЗ&lt;/span&gt;&lt;/a&gt;&lt;/button&gt;
&lt;br/&gt;
&lt;div class=&quot;buttond&quot; style=&quot;text-align: left;&quot;&gt;
&lt;a href=&quot;http://www.emiia.ru/&quot; style=&quot;background-color: white; border-radius: 3px; border: 0px solid #000000; color: #4A99D9 cursor: pointer; font-size: 8px; padding: 4px; text-decoration: none;&quot; target=&quot;_self&quot;&gt;&amp;#160;ВХОД | РЕГИСТРАЦИЯ&lt;/a&gt;
&lt;br/&gt;
&lt;br/&gt;
&lt;br/&gt;
&lt;br/&gt;
&lt;br/&gt;

  &lt;/div&gt;
&lt;/p&gt;&lt;/div&gt;&lt;/div&gt;

&lt;script&gt;
/* When the user clicks on the button,
toggle between hiding and showing the dropdown content */
function myFunction() {
    document.getElementById(&quot;myDropdown&quot;).classList.toggle(&quot;show&quot;);
}

function filterFunction() {
    var input, filter, ul, li, a, i;
    input = document.getElementById(&quot;myInput&quot;);
    filter = input.value.toUpperCase();
    div = document.getElementById(&quot;myDropdown&quot;);
    a = div.getElementsByTagName(&quot;a&quot;);
    for (i = 0; i &lt; a.length; i++) {
        if (a[i].innerHTML.toUpperCase().indexOf(filter) &gt; -1) {
            a[i].style.display = &quot;&quot;;
        } else {
            a[i].style.display = &quot;none&quot;;
        }
    }
}
&lt;/script&gt;


&lt;/!doctype&gt;</b:widget-setting>
  </b:widget-settings>
  <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
</b:widget>
</b:section>							
		</div>
		
	</div>
	
	
	<b:section id='header' showaddelement='yes'>
<b:widget id='HTML10' locked='false' title='top social' type='HTML'>
  <b:widget-settings>
    <b:widget-setting name='content'/>
  </b:widget-settings>
  <b:includable id='main'>
						<data:content/>
					</b:includable>
</b:widget>
</b:section>			
	
	
	
	<div class='container sp_sidebar'>



	
		<b:section id='main' showaddelement='no'>
<b:widget id='Blog1' locked='true' title='Сообщения блога' type='Blog'>
  <b:widget-settings>
    <b:widget-setting name='showDateHeader'>false</b:widget-setting>
    <b:widget-setting name='style.textcolor'>#000000</b:widget-setting>
    <b:widget-setting name='showShareButtons'>false</b:widget-setting>
    <b:widget-setting name='showCommentLink'>false</b:widget-setting>
    <b:widget-setting name='style.urlcolor'>#008000</b:widget-setting>
    <b:widget-setting name='showAuthor'>false</b:widget-setting>
    <b:widget-setting name='style.linkcolor'>#0000ff</b:widget-setting>
    <b:widget-setting name='style.unittype'>TextAndImage</b:widget-setting>
    <b:widget-setting name='style.bgcolor'>#ffffff</b:widget-setting>
    <b:widget-setting name='showAuthorProfile'>false</b:widget-setting>
    <b:widget-setting name='style.layout'>1x1</b:widget-setting>
    <b:widget-setting name='showLabels'>false</b:widget-setting>
    <b:widget-setting name='showLocation'>false</b:widget-setting>
    <b:widget-setting name='showTimestamp'>false</b:widget-setting>
    <b:widget-setting name='postsPerAd'>1</b:widget-setting>
    <b:widget-setting name='showBacklinks'>false</b:widget-setting>
    <b:widget-setting name='style.bordercolor'>#ffffff</b:widget-setting>
    <b:widget-setting name='showInlineAds'>false</b:widget-setting>
    <b:widget-setting name='showReactions'>false</b:widget-setting>
  </b:widget-settings>
  <b:includable id='main' var='top'>
			<b:loop values='data:posts' var='post'>
				<b:include data='post' name='post'/>
			</b:loop>
			<b:include name='nextprev'/>
		 </b:includable>
  <b:includable id='backlinkDeleteIcon' var='backlink'>
  <span expr:class='&quot;item-control &quot; + data:backlink.adminClass'>
    <a expr:href='data:backlink.deleteUrl' expr:title='data:top.deleteBacklinkMsg'>
      <img src='https://resources.blogblog.com/img/icon_delete13.gif'/>
    </a>
  </span>
</b:includable>
  <b:includable id='backlinks' var='post'>
  <a name='links'/><h4><data:post.backlinksLabel/></h4>
  <b:if cond='data:post.numBacklinks != 0'>
    <dl class='comments-block' id='comments-block'>
      <b:loop values='data:post.backlinks' var='backlink'>
        <div class='collapsed-backlink backlink-control'>
          <dt class='comment-title'>
            <span class='backlink-toggle-zippy'>&#160;</span>
            <a expr:href='data:backlink.url' rel='nofollow'><data:backlink.title/></a>
            <b:include data='backlink' name='backlinkDeleteIcon'/>
          </dt>
          <dd class='comment-body collapseable'>
            <data:backlink.snippet/>
          </dd>
          <dd class='comment-footer collapseable'>
            <span class='comment-author'><data:post.authorLabel/> <data:backlink.author/></span>
            <span class='comment-timestamp'><data:post.timestampLabel/> <data:backlink.timestamp/></span>
          </dd>
        </div>
      </b:loop>
    </dl>
  </b:if>
  <p class='comment-footer'>
    <a class='comment-link' expr:href='data:post.createLinkUrl' expr:id='data:widget.instanceId + &quot;_backlinks-create-link&quot;' target='_blank'><data:post.createLinkLabel/></a>
  </p>
</b:includable>
  <b:includable id='comment-form' var='post'>
  <div class='comment-form'>
    <a name='comment-form'/>
    <b:if cond='data:mobile'>
      <h4 id='comment-post-message'>
        <a expr:id='data:widget.instanceId + &quot;_comment-editor-toggle-link&quot;' href='javascript:void(0)'><data:postCommentMsg/></a></h4>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' style='display: none' width='100%'/>
    <b:else/>
      <h4 id='comment-post-message'><data:postCommentMsg/></h4>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' width='100%'/>
    </b:if>
    <data:post.friendConnectJs/>
    <data:post.cmtfpIframe/>
    <script type='text/javascript'>
      BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;, &#39;<data:post.communityId/>&#39;);
    </script>
  </div>
</b:includable>
  <b:includable id='commentDeleteIcon' var='comment'>
  <span expr:class='&quot;item-control &quot; + data:comment.adminClass'>
    <b:if cond='data:showCmtPopup'>
      <div class='goog-toggle-button'>
        <div class='goog-inline-block comment-action-icon'/>
      </div>
    <b:else/>
      <a class='comment-delete' expr:href='data:comment.deleteUrl' expr:title='data:top.deleteCommentMsg'>
        <img src='https://resources.blogblog.com/img/icon_delete13.gif'/>
      </a>
    </b:if>
  </span>
</b:includable>
  <b:includable id='comment_count_picker' var='post'>
  <b:if cond='data:post.commentSource == 1'>
    <span class='cmt_count_iframe_holder' expr:data-count='data:post.numComments' expr:data-onclick='data:post.addCommentOnclick' expr:data-post-url='data:post.url' expr:data-url='data:post.url.canonical.http'>
    </span>
  <b:else/>
    <a class='comment-link' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'>
      <data:post.commentLabelFull/>:
    </a>
  </b:if>
</b:includable>
  <b:includable id='comment_picker' var='post'>
  <b:if cond='data:post.commentSource == 1'>
    <b:include data='post' name='iframe_comments'/>
  <b:else/>
    <b:if cond='data:post.showThreadedComments'>
      <b:include data='post' name='threaded_comments'/>
    <b:else/>
      <b:include data='post' name='comments'/>
    </b:if>
  </b:if>
</b:includable>
  <b:includable id='comments' var='post'>
  <div class='comments' id='comments'>
    <a name='comments'/>
    <b:if cond='data:post.allowComments'>
      <h4>
        <b:if cond='data:post.numComments == 1'>
          1 <data:commentLabel/>:
        <b:else/>
          <data:post.numComments/> <data:commentLabelPlural/>:
        </b:if>
      </h4>

      <b:if cond='data:post.commentPagingRequired'>
        <span class='paging-control-container'>
          <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'><data:post.oldestLinkText/></a>
          &#160;
          <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'><data:post.olderLinkText/></a>
          &#160;
          <data:post.commentRangeText/>
          &#160;
          <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'><data:post.newerLinkText/></a>
          &#160;
          <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'><data:post.newestLinkText/></a>
        </span>
      </b:if>

      <div expr:id='data:widget.instanceId + &quot;_comments-block-wrapper&quot;'>
        <dl expr:class='data:post.avatarIndentClass' id='comments-block'>
          <b:loop values='data:post.comments' var='comment'>
            <dt expr:class='&quot;comment-author &quot; + data:comment.authorClass' expr:id='data:comment.anchorName'>
              <b:if cond='data:comment.favicon'>
                <img expr:src='data:comment.favicon' height='16px' style='margin-bottom:-2px;' width='16px'/>
              </b:if>
              <a expr:name='data:comment.anchorName'/>
              <b:if cond='data:blog.enabledCommentProfileImages'>
                <data:comment.authorAvatarImage/>
              </b:if>
              <b:if cond='data:comment.authorUrl'>
                <a expr:href='data:comment.authorUrl' rel='nofollow'><data:comment.author/></a>
              <b:else/>
                <data:comment.author/>
              </b:if>
              <data:commentPostedByMsg/>
            </dt>
            <dd class='comment-body' expr:id='data:widget.instanceId + data:comment.cmtBodyIdPostfix'>
              <b:if cond='data:comment.isDeleted'>
                <span class='deleted-comment'><data:comment.body/></span>
              <b:else/>
                <p>
                  <data:comment.body/>
                </p>
              </b:if>
            </dd>
            <dd class='comment-footer'>
              <span class='comment-timestamp'>
                <a expr:href='data:comment.url' title='comment permalink'>
                  <data:comment.timestamp/>
                </a>
                <b:include data='comment' name='commentDeleteIcon'/>
              </span>
            </dd>
          </b:loop>
        </dl>
      </div>

      <b:if cond='data:post.commentPagingRequired'>
        <span class='paging-control-container'>
          <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'>
            <data:post.oldestLinkText/>
          </a>
          <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'>
            <data:post.olderLinkText/>
          </a>
          &#160;
          <data:post.commentRangeText/>
          &#160;
          <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'>
            <data:post.newerLinkText/>
          </a>
          <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'>
            <data:post.newestLinkText/>
          </a>
        </span>
      </b:if>

      <p class='comment-footer'>
        <b:if cond='data:post.embedCommentForm'>
          <b:if cond='data:post.allowNewComments'>
            <b:include data='post' name='comment-form'/>
          <b:else/>
            <data:post.noNewCommentsText/>
          </b:if>
        <b:else/>
          <b:if cond='data:post.allowComments'>
            <a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><data:postCommentMsg/></a>
          </b:if>
        </b:if>

      </p>
    </b:if>
    <b:if cond='data:showCmtPopup'>
      <div id='comment-popup'>
        <iframe allowtransparency='true' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
        </iframe>
      </div>
    </b:if>

    <div id='backlinks-container'>
    <div expr:id='data:widget.instanceId + &quot;_backlinks-container&quot;'>
       <b:if cond='data:post.showBacklinks'>
         <b:include data='post' name='backlinks'/>
       </b:if>
    </div>
    </div>
  </div>
</b:includable>
  <b:includable id='feedLinks'>
  <b:if cond='data:blog.pageType != &quot;item&quot;'> <!-- Blog feed links -->
    <b:if cond='data:feedLinks'>
      <div class='blog-feeds'>
        <b:include data='feedLinks' name='feedLinksBody'/>
      </div>
    </b:if>

    <b:else/> <!--Post feed links -->
    <div class='post-feeds'>
      <b:loop values='data:posts' var='post'>
        <b:if cond='data:post.allowComments'>
          <b:if cond='data:post.feedLinks'>
            <b:include data='post.feedLinks' name='feedLinksBody'/>
          </b:if>
        </b:if>
      </b:loop>
    </div>
  </b:if>
</b:includable>
  <b:includable id='feedLinksBody' var='links'>
  <div class='feed-links'>
  <data:feedLinksMsg/>
  <b:loop values='data:links' var='f'>
     <a class='feed-link' expr:href='data:f.url' expr:type='data:f.mimeType' target='_blank'><data:f.name/> (<data:f.feedType/>)</a>
  </b:loop>
  </div>
</b:includable>
  <b:includable id='iframe_comments' var='post'>

  <b:if cond='data:post.allowIframeComments'>
    <script expr:src='data:post.iframeCommentSrc' type='text/javascript'/>
    <div class='cmt_iframe_holder' expr:data-href='data:post.url.canonical' expr:data-viewtype='data:post.viewType'/>

    <b:if cond='data:post.embedCommentForm == &quot;false&quot;'>
      <a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><data:postCommentMsg/></a>
    </b:if>
  </b:if>
</b:includable>
  <b:includable id='mobile-index-post' var='post'>
  <div class='mobile-date-outer date-outer'>
    <b:if cond='data:post.dateHeader'>
      <div class='date-header'>
        <span><data:post.dateHeader/></span>
      </div>
    </b:if>

    <div class='mobile-post-outer'>
      <a expr:href='data:post.url'>
        <h3 class='mobile-index-title entry-title'>
          <data:post.title/>
        </h3>

        <div class='mobile-index-arrow'>&amp;rsaquo;</div>

        <div class='mobile-index-contents'>
          <b:if cond='data:post.thumbnailUrl'>
            <div class='mobile-index-thumbnail'>
              <div class='Image'>
                <img expr:src='data:post.thumbnailUrl'/>
              </div>
            </div>
          </b:if>

          <div class='post-body'>
            <b:if cond='data:post.snippet'><data:post.snippet/></b:if>
          </div>
        </div>

        <div style='clear: both;'/>
      </a>

      <div class='mobile-index-comment'>
        <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
          <b:if cond='data:post.allowComments'>
            <b:if cond='data:post.numComments != 0'>
              <a class='comment-link' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><b:if cond='data:post.numComments == 1'>1 <data:top.commentLabel/><b:else/><data:post.numComments/> <data:top.commentLabelPlural/></b:if></a>
            </b:if>
          </b:if>
        </b:if>
      </div>
    </div>
  </div>
</b:includable>
  <b:includable id='mobile-main' var='top'>
    <!-- posts -->
    <div class='blog-posts hfeed'>

      <b:include data='top' name='status-message'/>

      <b:if cond='data:blog.pageType == &quot;index&quot;'>
        <b:loop values='data:posts' var='post'>
          <b:include data='post' name='mobile-index-post'/>
        </b:loop>
      <b:else/>
        <b:loop values='data:posts' var='post'>
          <b:include data='post' name='mobile-post'/>
        </b:loop>
      </b:if>
    </div>

   <b:include name='mobile-nextprev'/>
</b:includable>
  <b:includable id='mobile-nextprev'>
  <div class='blog-pager' id='blog-pager'>
    <b:if cond='data:newerPageUrl'>
      <div class='mobile-link-button' id='blog-pager-newer-link'>
      <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'>&amp;lsaquo;</a>
      </div>
    </b:if>

    <b:if cond='data:olderPageUrl'>
      <div class='mobile-link-button' id='blog-pager-older-link'>
      <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'>&amp;rsaquo;</a>
      </div>
    </b:if>

    <div class='mobile-link-button' id='blog-pager-home-link'>
    <a class='home-link' expr:href='data:blog.homepageUrl'><data:homeMsg/></a>
    </div>

    <div class='mobile-desktop-link'>
      <a class='home-link' expr:href='data:desktopLinkUrl'><data:desktopLinkMsg/></a>
    </div>

  </div>
  <div class='clear'/>
</b:includable>
  <b:includable id='mobile-post' var='post'>
  <div class='date-outer'>
    <b:if cond='data:post.dateHeader'>
      <h2 class='date-header'><span><data:post.dateHeader/></span></h2>
    </b:if>
    <div class='date-posts'>
      <div class='post-outer'>

        <div class='post hentry uncustomized-post-template'>
          <a expr:name='data:post.id'/>
          <b:if cond='data:post.title'>
            <h3 class='post-title entry-title'>
              <b:if cond='data:post.link'>
                <a expr:href='data:post.link'><data:post.title/></a>
              <b:else/>
                <b:if cond='data:post.url'>
                  <b:if cond='data:blog.url != data:post.url'>
                    <a expr:href='data:post.url'><data:post.title/></a>
                  <b:else/>
                    <data:post.title/>
                  </b:if>
                <b:else/>
                  <data:post.title/>
                </b:if>
              </b:if>
            </h3>
          </b:if>

          <div class='post-header'>
            <div class='post-header-line-1'/>
          </div>

          <div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id'>
            <data:post.body/>
            <div style='clear: both;'/> <!-- clear for photos floats -->
          </div>

          <div class='post-footer'>
            <div class='post-footer-line post-footer-line-1'>
              <span class='post-author vcard'>
                <b:if cond='data:top.showAuthor'>
                  <b:if cond='data:post.authorProfileUrl'>
                    <span class='fn'>
                      <a expr:href='data:post.authorProfileUrl' rel='author' title='author profile'>
                        <data:post.author/>
                      </a>
                    </span>
                  <b:else/>
                    <span class='fn'><data:post.author/></span>
                  </b:if>
                </b:if>
              </span>

              <span class='post-timestamp'>
                <b:if cond='data:top.showTimestamp'>
                  <data:top.timestampLabel/>
                  <b:if cond='data:post.url'>
                    <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'><abbr class='published' expr:title='data:post.timestampISO8601'><data:post.timestamp/></abbr></a>
                  </b:if>
                </b:if>
              </span>

              <span class='post-comment-link'>
                <b:if cond='data:blog.pageType != &quot;item&quot;'>
                  <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
                    <b:if cond='data:post.allowComments'>
                      <a class='comment-link' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><b:if cond='data:post.numComments == 1'>1 <data:top.commentLabel/><b:else/><data:post.numComments/> <data:top.commentLabelPlural/></b:if></a>
                    </b:if>
                  </b:if>
                </b:if>
              </span>
            </div>

            <div class='post-footer-line post-footer-line-2'>
              <b:if cond='data:top.showMobileShare'>
                <div class='mobile-link-button goog-inline-block' id='mobile-share-button'>
                  <a href='javascript:void(0);'><data:shareMsg/></a>
                </div>
              </b:if>
              <b:if cond='data:top.showDummy'>
                <div class='goog-inline-block dummy-container'><data:post.dummyTag/></div>
              </b:if>
            </div>

          </div>
        </div>

        <b:if cond='data:blog.pageType == &quot;static_page&quot;'>
          <b:if cond='data:post.showThreadedComments'>
            <b:include data='post' name='threaded_comments'/>
          <b:else/>
            <b:include data='post' name='comments'/>
          </b:if>
        </b:if>
        <b:if cond='data:blog.pageType == &quot;item&quot;'>
          <b:if cond='data:post.showThreadedComments'>
            <b:include data='post' name='threaded_comments'/>
          <b:else/>
            <b:include data='post' name='comments'/>
          </b:if>
        </b:if>
      </div>
    </div>
  </div>
</b:includable>
  <b:includable id='nextprev'>
			<div class='pagination'>


		<b:if cond='data:newerPageUrl'>
					<div class='newer'><a expr:href='data:newerPageUrl'><span class='pager-heading'>Newer</span><br/><span class='pager-title'> Stories</span><span class='post-nav-icon'><i class='fa fa-chevron-left'/></span></a></div>		
				</b:if>
				<b:if cond='data:olderPageUrl'>
                  <div class='older'><a expr:href='data:olderPageUrl'><span class='pager-heading'>Older</span><br/><span class='pager-title'> Stories</span><span class='post-nav-icon'><i class='fa fa-chevron-right'/></span></a></div>
				</b:if>
			</div>
		 
		</b:includable>
  <b:includable id='post' var='post'>
			 <b:if cond='data:blog.pageType == &quot;item&quot;'>
				<article class='post'>
					<div class='post-header'>		
																						
						<h1>
							<data:post.title/>
						</h1>
						<span class='date'><data:post.timestamp/></span>						
					</div>
					<div class='post-entry'>
						<p><data:post.body/></p>
					</div>



<div class='entry-meta hidden-print'>
    <div class='single-sharing-btns'>
        <h3 class='single-sharing-btns-title'>Share This Story</h3>
        <ul class='social-share-buttons style-default size-large' data-url='http://blogspot.com'>
            <li class='facebook' data-service='facebook' data-show='true' title='Share on Facebook'><a expr:href='&quot;http://www.facebook.com/sharer.php?u=&quot; + data:post.url' target='_blank'><i class='fa fa-facebook'/>
                <label class='hidden-xs'>Share on Facebook</label></a>
            </li>

            <li class='twitter' data-service='twitter' data-show='true' title='Share on Twitter'><a expr:href='&quot;http://twitter.com/share?url=&quot; + data:post.url' target='_blank'><i class='fa fa-twitter'/>
                <label class='hidden-xs'>Share on Twitter</label></a>
            </li>

            <li class='pinterest' data-service='pinterest' data-show='true' title='Pin this Post'><a href='javascript:void((function()%7Bvar%20e=document.createElement(&apos;script&apos;);e.setAttribute(&apos;type&apos;,&apos;text/javascript&apos;);e.setAttribute(&apos;charset&apos;,&apos;UTF-8&apos;);e.setAttribute(&apos;src&apos;,&apos;http://assets.pinterest.com/js/pinmarklet.js?r=&apos;+Math.random()*99999999);document.body.appendChild(e)%7D)());' target='_blank'><i class='fa fa-pinterest'/>
              <label class='hidden-xs'>Pin this Post</label></a>
            </li>
        </ul>
    </div>

    <div class='entry-tags gray-2-secondary'><strong class='tag-heading'><i class='fa fa-tag'/>Tags:</strong> 

<b:loop values='data:post.labels' var='label'>
									<a expr:href='data:label.url' rel='tag'><data:label.name/></a><b:if cond='data:label.isLast != &quot;true&quot;'>,</b:if>
								</b:loop>


</div>
</div>





<div class='blog-pager' id='blog-pager'>
                        <b:if cond='data:newerPageUrl'>
                          <span id='blog-pager-newer-link'>
                            <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'>
                              <data:newerPageTitle/>
                            </a>
                          </span>
                        </b:if>
                        <b:if cond='data:olderPageUrl'>
                          <span id='blog-pager-older-link'>
                            <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'>
                              <data:olderPageTitle/>
                            </a>
                          </span>
                        </b:if>
                      
                        <b:if cond='data:mobileLinkUrl'>
                          <div class='blog-mobile-link'>
                            <a expr:href='data:mobileLinkUrl'>
                              <data:mobileLinkMsg/>
                            </a>
                          </div>
                        </b:if>
                      </div>
                      <div class='clear'/>

					
					<!--author biography start-->
					<div class='post-author'>		
						<div class='author-img'>
							<!-- avatar of author here-->
							<img alt='' class='avatar avatar-100 photo' height='100' src='http://elegance.demo.yeahthemes.com/wp-content/uploads/2015/03/me.jpg' width='100'/>
						</div>	
						<div class='author-content'>
							<h5><a href='' rel='author' title='Posts by solopine'><data:post.author/></a></h5>
							<p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor Aenean massa.</p>
							<a class='author-social' href='Facebook link goes here' target='_blank'><i class='fa fa-facebook'/></a>		
							<a class='author-social' href='Twitter link goes here' target='_blank'><i class='fa fa-twitter'/></a>	
							<a class='author-social' href='Instagram link goes here' target='_blank'><i class='fa fa-instagram'/></a>	
							<a class='author-social' href='Google plus link goes here' target='_blank'><i class='fa fa-google-plus'/></a>	
							<a class='author-social' href='Pinterest link goes here' target='_blank'><i class='fa fa-pinterest'/></a>	
							<a class='author-social' href='Tumblr link goes here' target='_blank'><i class='fa fa-tumblr'/></a>
						</div>
					</div>			
					<!--author biography end -->
					<div class='post-related'>
						<div class='post-box'>
							<h4 class='post-box-title'>You Might Also Like</h4>
						</div>
						<b:loop values='data:post.labels' var='label'>
							<script expr:src='&quot;/feeds/posts/default/-/&quot; + data:label.name + &quot;?alt=json-in-script&amp;callback=related_results_labels_thumbs&amp;max-results=6&quot;' type='text/javascript'/>							 
						</b:loop> 
						<script type='text/javascript'>
							var defaultnoimage=&quot;http://1.bp.blogspot.com/_u4gySN2ZgqE/SosvnavWq0I/AAAAAAAAArk/yL95WlyTqr0/s400/noimage.png&quot;;
							var maxresults=3;
							removeRelatedDuplicates_thumbs();
							printRelatedLabels_thumbs(&quot;<data:post.url/>&quot;);
						</script>
					</div>	
					<b:include data='post' name='threaded_comments'/>
					
				</article>

			  <b:else/>
				<b:if cond='data:blog.pageType == &quot;static_page&quot;'>
					<article class='post'>
						<div class='post-header'>		
							<h2>
								<data:post.title/>
							</h2>
						</div>
						<div class='post-entry'>
							<p><data:post.body/></p>
						</div>
						<div class='post-share'>
							<a expr:href='&quot;http://www.facebook.com/sharer.php?u=&quot; + data:post.url' target='_blank'><span class='share-box'><i class='fa fa-facebook'/></span></a>
							<a expr:href='&quot;http://twitter.com/share?url=&quot; + data:post.url' target='_blank'><span class='share-box'><i class='fa fa-twitter'/></span></a>
							<a href='javascript:void((function()%7Bvar%20e=document.createElement(&apos;script&apos;);e.setAttribute(&apos;type&apos;,&apos;text/javascript&apos;);e.setAttribute(&apos;charset&apos;,&apos;UTF-8&apos;);e.setAttribute(&apos;src&apos;,&apos;http://assets.pinterest.com/js/pinmarklet.js?r=&apos;+Math.random()*99999999);document.body.appendChild(e)%7D)());' target='_blank'><span class='share-box'><i class='fa fa-pinterest'/></span></a>
							<a expr:href='&quot;https://plus.google.com/share?url=&quot; + data:post.url' target='_blank'><span class='share-box'><i class='fa fa-google-plus'/></span></a>
							<a expr:href='data:post.url'><span class='share-box'><i class='fa fa-comment-o'/></span></a>		
						</div>
					</article>
					
				<b:else/>
					<article class='post'>		
						<div class='post-header'>		
													<span class='cat'>


  <b:loop index='x' values='data:post.labels' var='label'>

    <b:if cond='data:x==0'> <a expr:href='data:label.url + &quot;?max-results=12&quot;' rel='tag nofollow'><data:label.name/></a></b:if> 
  
  </b:loop>

						</span>													
							<h2>
								<b:if cond='data:post.link'>
									<a expr:href='data:post.link'><data:post.title/></a>
								<b:else/>
									<b:if cond='data:post.url'>
										<b:if cond='data:blog.url != data:post.url'>
											<a expr:href='data:post.url'><data:post.title/></a>
										<b:else/>
											<data:post.title/>
										</b:if>
									<b:else/>
										<data:post.title/>
									</b:if>
								</b:if>
							</h2>
							<span class='date'><data:post.timestamp/></span>				
						</div>
						<div expr:id='&quot;summary&quot; + data:post.id' style='display:none;'>
							<data:post.body/>
						</div>
						<script type='text/javascript'>createSummaryAndThumb(&quot;summary<data:post.id/>&quot;,&quot;<data:post.title/>&quot;,&quot;<data:post.url/>&quot;,&quot;<data:post.timestamp/>&quot;,&quot;<data:post.numComments/>&quot;,&quot;<b:loop values='data:post.labels' var='label'><a expr:href='data:label.url + &quot;?max-results=6&quot;' rel='tag'><data:label.name/></a><b:if cond='data:label.isLast != &quot;true&quot;'> ,</b:if></b:loop>&quot;);</script>    	
						<div class='post-share'>
							<a expr:href='&quot;http://www.facebook.com/sharer.php?u=&quot; + data:post.url' target='_blank'><span class='share-box'><i class='fa fa-facebook'/></span></a>
							<a expr:href='&quot;http://twitter.com/share?url=&quot; + data:post.url' target='_blank'><span class='share-box'><i class='fa fa-twitter'/></span></a>
							<a href='javascript:void((function()%7Bvar%20e=document.createElement(&apos;script&apos;);e.setAttribute(&apos;type&apos;,&apos;text/javascript&apos;);e.setAttribute(&apos;charset&apos;,&apos;UTF-8&apos;);e.setAttribute(&apos;src&apos;,&apos;http://assets.pinterest.com/js/pinmarklet.js?r=&apos;+Math.random()*99999999);document.body.appendChild(e)%7D)());' target='_blank'><span class='share-box'><i class='fa fa-pinterest'/></span></a>
							<a expr:href='&quot;https://plus.google.com/share?url=&quot; + data:post.url' target='_blank'><span class='share-box'><i class='fa fa-google-plus'/></span></a>
							<a expr:href='data:post.url'><span class='share-box'><i class='fa fa-comment-o'/></span></a>		
						</div>
					</article>				
								
				</b:if>
			</b:if>							
											
		</b:includable>
  <b:includable id='postQuickEdit' var='post'>
  <b:if cond='data:post.editUrl'>
    <span expr:class='&quot;item-control &quot; + data:post.adminClass'>
      <a expr:href='data:post.editUrl' expr:title='data:top.editPostMsg'>
        <img alt='' class='icon-action' height='18' src='http://img2.blogblog.com/img/icon18_edit_allbkg.gif' width='18'/>
      </a>
    </span>
  </b:if>
</b:includable>
  <b:includable id='shareButtons' var='post'>
  <b:if cond='data:top.showEmailButton'><a class='goog-inline-block share-button sb-email' expr:href='data:post.sharePostUrl + &quot;&amp;target=email&quot;' expr:title='data:top.emailThisMsg' target='_blank'><span class='share-button-link-text'><data:top.emailThisMsg/></span></a></b:if><b:if cond='data:top.showBlogThisButton'><a class='goog-inline-block share-button sb-blog' expr:href='data:post.sharePostUrl + &quot;&amp;target=blog&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=270,width=475\&quot;); return false;&quot;' expr:title='data:top.blogThisMsg' target='_blank'><span class='share-button-link-text'><data:top.blogThisMsg/></span></a></b:if><b:if cond='data:top.showTwitterButton'><a class='goog-inline-block share-button sb-twitter' expr:href='data:post.sharePostUrl + &quot;&amp;target=twitter&quot;' expr:title='data:top.shareToTwitterMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToTwitterMsg/></span></a></b:if><b:if cond='data:top.showFacebookButton'><a class='goog-inline-block share-button sb-facebook' expr:href='data:post.sharePostUrl + &quot;&amp;target=facebook&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=430,width=640\&quot;); return false;&quot;' expr:title='data:top.shareToFacebookMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToFacebookMsg/></span></a></b:if><b:if cond='data:top.showOrkutButton'><a class='goog-inline-block share-button sb-orkut' expr:href='data:post.sharePostUrl + &quot;&amp;target=orkut&quot;' expr:title='data:top.shareToOrkutMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToOrkutMsg/></span></a></b:if><b:if cond='data:top.showDummy'><div class='goog-inline-block dummy-container'><data:post.dummyTag/></div></b:if>
</b:includable>
  <b:includable id='status-message'>
  <b:if cond='data:navMessage'>
  <div class='status-msg-wrap'>
    <div class='status-msg-body'>
      <data:navMessage/>
    </div>
    <div class='status-msg-border'>
      <div class='status-msg-bg'>
        <div class='status-msg-hidden'><data:navMessage/></div>
      </div>
    </div>
  </div>
  <div style='clear: both;'/>
  </b:if>
</b:includable>
  <b:includable id='threaded-comment-form' var='post'>
  <div class='comment-form'>
    <a name='comment-form'/>
    <b:if cond='data:mobile'>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' style='display: none' width='100%'/>
    <b:else/>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' width='100%'/>
    </b:if>
    <data:post.friendConnectJs/>
    <data:post.cmtfpIframe/>
    <script type='text/javascript'>
      BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;, &#39;<data:post.communityId/>&#39;);
    </script>
  </div>
</b:includable>
  <b:includable id='threaded_comment_js' var='post'>
  <script async='async' expr:src='data:post.commentSrc' type='text/javascript'/>

  <script type='text/javascript'>
    (function() {
      var items = <data:post.commentJso/>;
      var msgs = <data:post.commentMsgs/>;
      var config = <data:post.commentConfig/>;

// <![CDATA[
      var cursor = null;
      if (items && items.length > 0) {
        cursor = parseInt(items[items.length - 1].timestamp) + 1;
      }

      var bodyFromEntry = function(entry) {
        if (entry.gd$extendedProperty) {
          for (var k in entry.gd$extendedProperty) {
            if (entry.gd$extendedProperty[k].name == 'blogger.contentRemoved') {
              return '<span class="deleted-comment">' + entry.content.$t + '</span>';
            }
          }
        }
        return entry.content.$t;
      }

      var parse = function(data) {
        cursor = null;
        var comments = [];
        if (data && data.feed && data.feed.entry) {
          for (var i = 0, entry; entry = data.feed.entry[i]; i++) {
            var comment = {};
            // comment ID, parsed out of the original id format
            var id = /blog-(\d+).post-(\d+)/.exec(entry.id.$t);
            comment.id = id ? id[2] : null;
            comment.body = bodyFromEntry(entry);
            comment.timestamp = Date.parse(entry.published.$t) + '';
            if (entry.author && entry.author.constructor === Array) {
              var auth = entry.author[0];
              if (auth) {
                comment.author = {
                  name: (auth.name ? auth.name.$t : undefined),
                  profileUrl: (auth.uri ? auth.uri.$t : undefined),
                  avatarUrl: (auth.gd$image ? auth.gd$image.src : undefined)
                };
              }
            }
            if (entry.link) {
              if (entry.link[2]) {
                comment.link = comment.permalink = entry.link[2].href;
              }
              if (entry.link[3]) {
                var pid = /.*comments\/default\/(\d+)\?.*/.exec(entry.link[3].href);
                if (pid && pid[1]) {
                  comment.parentId = pid[1];
                }
              }
            }
            comment.deleteclass = 'item-control blog-admin';
            if (entry.gd$extendedProperty) {
              for (var k in entry.gd$extendedProperty) {
                if (entry.gd$extendedProperty[k].name == 'blogger.itemClass') {
                  comment.deleteclass += ' ' + entry.gd$extendedProperty[k].value;
                }
              }
            }
            comments.push(comment);
          }
        }
        return comments;
      };

      var paginator = function(callback) {
        if (hasMore()) {
          var url = config.feed + '?alt=json&v=2&orderby=published&reverse=false&max-results=50';
          if (cursor) {
            url += '&published-min=' + new Date(cursor).toISOString();
          }
          window.bloggercomments = function(data) {
            var parsed = parse(data);
            cursor = parsed.length < 50 ? null
                : parseInt(parsed[parsed.length - 1].timestamp) + 1
            callback(parsed);
            window.bloggercomments = null;
          }
          url += '&callback=bloggercomments';
          var script = document.createElement('script');
          script.type = 'text/javascript';
          script.src = url;
          document.getElementsByTagName('head')[0].appendChild(script);
        }
      };
      var hasMore = function() {
        return !!cursor;
      };
      var getMeta = function(key, comment) {
        if ('iswriter' == key) {
          var matches = !!comment.author
              && comment.author.name == config.authorName
              && comment.author.profileUrl == config.authorUrl;
          return matches ? 'true' : '';
        } else if ('deletelink' == key) {
          return config.baseUri + '/delete-comment.g?blogID='
               + config.blogId + '&postID=' + comment.id;
        } else if ('deleteclass' == key) {
          return comment.deleteclass;
        }
        return '';
      };

      var replybox = null;
      var replyUrlParts = null;
      var replyParent = undefined;

      var onReply = function(commentId, domId) {
        if (replybox == null) {
          // lazily cache replybox, and adjust to suit this style:
          replybox = document.getElementById('comment-editor');
          if (replybox != null) {
            replybox.height = '250px';
            replybox.style.display = 'block';
            replyUrlParts = replybox.src.split('#');
          }
        }
        if (replybox && (commentId !== replyParent)) {
          document.getElementById(domId).insertBefore(replybox, null);
          replybox.src = replyUrlParts[0]
              + (commentId ? '&parentID=' + commentId : '')
              + '#' + replyUrlParts[1];
          replyParent = commentId;
        }
      };

      var hash = (window.location.hash || '#').substring(1);
      var startThread, targetComment;
      if (/^comment-form_/.test(hash)) {
        startThread = hash.substring('comment-form_'.length);
      } else if (/^c[0-9]+$/.test(hash)) {
        targetComment = hash.substring(1);
      }

      // Configure commenting API:
      var configJso = {
        'maxDepth': config.maxThreadDepth
      };
      var provider = {
        'id': config.postId,
        'data': items,
        'loadNext': paginator,
        'hasMore': hasMore,
        'getMeta': getMeta,
        'onReply': onReply,
        'rendered': true,
        'initComment': targetComment,
        'initReplyThread': startThread,
        'config': configJso,
        'messages': msgs
      };

      var render = function() {
        if (window.goog && window.goog.comments) {
          var holder = document.getElementById('comment-holder');
          window.goog.comments.render(holder, provider);
        }
      };

      // render now, or queue to render when library loads:
      if (window.goog && window.goog.comments) {
        render();
      } else {
        window.goog = window.goog || {};
        window.goog.comments = window.goog.comments || {};
        window.goog.comments.loadQueue = window.goog.comments.loadQueue || [];
        window.goog.comments.loadQueue.push(render);
      }
    })();
// ]]>
  </script>
</b:includable>
  <b:includable id='threaded_comments' var='post'>
			<div class='post-comments' id='comments'>
				<div class='post-box'>
					<h4 class='post-box-title'> 
						<b:if cond='data:post.numComments == 1'>
							1 <data:commentLabel/>
						<b:else/>
							<data:post.numComments/> <data:commentLabelPlural/>
						</b:if>
					</h4>
				</div>
				<div class='comments'>		
					<b:if cond='data:post.embedCommentForm'>
						<b:include data='post' name='threaded_comment_js'/>
					</b:if>
					<div id='comment-holder'>
						<data:post.commentHtml/>
					</div>
				</div>
				
				<p class='comment-footer'>
					<b:if cond='data:post.allowNewComments'>
						<b:include data='post' name='threaded-comment-form'/>
					<b:else/>
						<data:post.noNewCommentsText/>
					</b:if>
				</p>

				<b:if cond='data:showCmtPopup'>
					<div id='comment-popup'>	
						<iframe allowtransparency='true' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
						</iframe>
					</div>
				</b:if>

				<div id='backlinks-container'>
					<div expr:id='data:widget.instanceId + &quot;_backlinks-container&quot;'>
						<b:if cond='data:post.showBacklinks'>
							<b:include data='post' name='backlinks'/>
						</b:if>
					</div>
				</div>
			</div>						
		

		</b:includable>
</b:widget>
</b:section>
		
		<b:section id='sidebar' showaddelement='yes'>
<b:widget id='HTML3' locked='false' title='' type='HTML'>
  <b:widget-settings>
    <b:widget-setting name='content'>&amp;#160;&amp;#160;&amp;#160;&amp;#160;&amp;#160;
&lt;button class=&quot;button-primary button-big&quot; id=&quot;sign-up-button&quot; style=&quot;background-color: white; border-color: #4A99D9; border-style: solid; border-radius:3px; border-width: 1px; color: white; cursor: pointer; font-family: Helvetica, Arial, sans-serif; font-size: 15px; height: 50px; letter-spacing: 0.5px; line-height: 40px; margin: 38px 0px 20px; min-width: 200px; outline: none; padding: 4px 1.5em 0px; position: relative; text-transform: uppercase; width: auto;&quot; type=&quot;submit&quot;
value=&quot;Registrar&quot;&gt;&lt;a href=&quot;http://www.emiia.ru/&quot;&gt;&lt;span style=&quot;color: #4A99D9;&quot;&gt;&amp;#160;ВХОД&lt;/span&gt;&lt;/a&gt;&lt;/button&gt;&lt;a 

href=&quot;https://www.emiia.ru&quot; target=&quot;_self&quot; style=&quot;cursor: pointer; font-size:9px;  text-decoration: none; padding:6px 33px; color:#000000; background-color:#ffffff; border-radius:11px; border: 0px solid #000000;&quot;&gt;РЕГИСТРАЦИЯ&lt;/a&gt;
&lt;br/&gt;
&lt;br/&gt;


&lt;p class=&quot;buttond&quot;  style=&quot;text-align:&quot;&gt;&lt;a href=&quot;http://www.emiia.ru/&quot; target=&quot;_self&quot; style=&quot;cursor: pointer; font-size:12px;  text-decoration: none; padding:8px; color:#000000; background-color:#ffffff; border-radius:15px; border: 0px solid #000000;&quot;&gt;ГЛАВНАЯ&lt;/a&gt;&lt;/p&gt;


&lt;p class=&quot;buttond&quot;  style=&quot;text-align:&quot;&gt;&lt;a href=&quot;http://www.emiia.ru/p/information-economy.html&quot; target=&quot;_self&quot; style=&quot;cursor: pointer; font-size:12px;  text-decoration: none; padding:8px; color:#000000; background-color:#ffffff; border-radius:15px; border: 0px solid #000000;&quot;&gt;О НАС/КОНТАКТЫ&lt;/a&gt;&lt;/p&gt;

&lt;p class=&quot;buttond&quot;  style=&quot;text-align:&quot;&gt;&lt;a href=&quot;http://www.emiia.ru/p/emiia.html&quot; target=&quot;_self&quot; style=&quot;cursor: pointer; font-size:12px;  text-decoration: none; padding:8px; color:#000000; background-color:#ffffff; border-radius:15px; border: 0px solid #000000;&quot;&gt;СМИ О ПРОЕКТЕ&lt;/a&gt;&lt;/p&gt;

&lt;p class=&quot;buttond&quot;  style=&quot;text-align:&quot;&gt;&lt;a href=&quot;http://emonocle.blogspot.ru/&quot; target=&quot;_self&quot; style=&quot;cursor: pointer; font-size:12px;  text-decoration: none; padding:8px; color:#000000; background-color:#ffffff; border-radius:15px; border: 0px solid #000000;&quot;&gt;БЛОГ&lt;/a&gt;&lt;/p&gt;

&lt;br/&gt;

&lt;p class=&quot;buttond&quot;  style=&quot;text-align:&quot;&gt;&lt;a href=&quot;http://www.emiia.ru/p/investor.html&quot; target=&quot;_self&quot; style=&quot;cursor: pointer; font-size:12px;  text-decoration: none; padding:8px; color:#000000; background-color:#ffffff; border-radius:15px; border: 0px solid #000000;&quot;&gt;ИНВЕСТОРАМ&lt;/a&gt;&lt;/p&gt;

&lt;p class=&quot;buttond&quot;  style=&quot;text-align:&quot;&gt;&lt;a href=&quot;https://www.emiia.ru/p/partner.html&quot; target=&quot;_self&quot; style=&quot;cursor: pointer; font-size:12px;  text-decoration: none; padding:8px; color:#000000; background-color:#ffffff; border-radius:15px; border: 0px solid #000000;&quot;&gt;СОТРУДНИЧЕСТВО&lt;/a&gt;&lt;/p&gt;

&lt;p class=&quot;buttond&quot;  style=&quot;text-align:&quot;&gt;&lt;a href=&quot;http://www.emiia.ru/p/investor.html&quot; target=&quot;_self&quot; style=&quot;cursor: pointer; font-size:12px;  text-decoration: none; padding:8px; color:#000000; background-color:#ffffff; border-radius:15px; border: 0px solid #000000;&quot;&gt;РАЗРАБОТЧИКАМ&lt;/a&gt;&lt;/p&gt;

&lt;p class=&quot;buttond&quot;  style=&quot;text-align:&quot;&gt;&lt;a href=&quot;http://www.emiia.ru/p/investor.html&quot; target=&quot;_self&quot; style=&quot;cursor: pointer; font-size:12px;  text-decoration: none; padding:8px; color:#000000; background-color:#ffffff; border-radius:15px; border: 0px solid #000000;&quot;&gt;РАБОТА В ЭМИИА&lt;/a&gt;&lt;/p&gt;




&amp;#160;&amp;#160;&amp;#160;&amp;#160;&amp;#160;&amp;#160;&amp;#160;
&lt;button class=&quot;button-primary button-big&quot; id=&quot;sign-up-button&quot; style=&quot;background-color: white; border-color: #4A99D9; border-style: solid; border-radius:3px; border-width: 1px; color: white; cursor: pointer; font-family: Helvetica, Arial, sans-serif; font-size: 15px; height: 50px; letter-spacing: 0.5px; line-height: 40px; margin: 38px 0px 20px; min-width: 200px; outline: none; padding: 4px 1.5em 0px; position: relative; text-transform: uppercase; width: auto;&quot; type=&quot;submit&quot;
value=&quot;Registrar&quot;&gt;&lt;a href=&quot;https://docs.google.com/forms/d/1BGNXxOQpFsx6nr5stwI0WGP8zPd55kbOal_ndk0sJRk&quot;&gt;&lt;span style=&quot;color: #4A99D9&quot;&gt;&amp;#160;ПРЕДЗАКАЗ&lt;/span&gt;&lt;/a&gt;&lt;/button&gt;&lt;a 

href=&quot;https://www.emiia.ru/p/emonocle.html&quot; target=&quot;_self&quot; style=&quot;cursor: pointer; font-size:9px;  text-decoration: none; padding:6px 33px; color:#000000; background-color:#ffffff; border-radius:11px; border: 0px solid #000000;&quot;&gt;ОПИСАНИЕ&lt;/a&gt;
&lt;br/&gt;



&lt;br/&gt;
&lt;br/&gt;
&lt;div class=&quot;separator&quot; style=&quot;clear: both; text-align: center;&quot;&gt;
&lt;a href=&quot;https://www.youtube.com/embed/cHT3bFJCbSo&quot;&gt;&lt;img alt=&quot;EMIIA Video&quot; border=&quot;0&quot; data-original-height=&quot;140&quot; data-original-width=&quot;280&quot; src=&quot;https://cdn.rawgit.com/EMIIA/1295624c05c4f2e18963e301fb035bb5/raw/350898d5bb8e683271968c832362ee07c5f38481/emiia%2520video%25202.svg&quot; title=&quot;EMIIA Video&quot; /&gt;&lt;/a&gt;&lt;/div&gt;




&lt;br/&gt;
&lt;br/&gt;
&lt;div class=&quot;separator&quot; style=&quot;clear: both; text-align: center;&quot;&gt;
&lt;a href=&quot;https://github.com/EMIIA/emonocle&quot;&gt;&lt;img alt=&quot;Download/GitHub&quot; border=&quot;0&quot; data-original-height=&quot;80&quot; data-original-width=&quot;160&quot; src=&quot;https://cdn.rawgit.com/EMIIA/bd24a0892494b22491b3cf8f4f2342d8/raw/25f1fe84cb615c4fc16bb6d154bb7cd19f5762eb/apple%2520google%2520dow.svg&quot; title=&quot;Download/GitHub&quot; /&gt;&lt;/a&gt;&lt;/div&gt;</b:widget-setting>
  </b:widget-settings>
  <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
</b:widget>
</b:section>
	</div>

<script>
//<![CDATA[
// Generated by CoffeeScript 1.3.3
(function(){var e,t;e=function(){function e(e,t){var n,r;this.options={target:"instafeed",get:"popular",resolution:"thumbnail",sortBy:"none",links:!0,mock:!1,useHttp:!1};if(typeof e=="object")for(n in e)r=e[n],this.options[n]=r;this.context=t!=null?t:this,this.unique=this._genKey()}return e.prototype.hasNext=function(){return typeof this.context.nextUrl=="string"&&this.context.nextUrl.length>0},e.prototype.next=function(){return this.hasNext()?this.run(this.context.nextUrl):!1},e.prototype.run=function(t){var n,r,i;if(typeof this.options.clientId!="string"&&typeof this.options.accessToken!="string")throw new Error("Missing clientId or accessToken.");if(typeof this.options.accessToken!="string"&&typeof this.options.clientId!="string")throw new Error("Missing clientId or accessToken.");return this.options.before!=null&&typeof this.options.before=="function"&&this.options.before.call(this),typeof document!="undefined"&&document!==null&&(i=document.createElement("script"),i.id="instafeed-fetcher",i.src=t||this._buildUrl(),n=document.getElementsByTagName("head"),n[0].appendChild(i),r="instafeedCache"+this.unique,window[r]=new e(this.options,this),window[r].unique=this.unique),!0},e.prototype.parse=function(e){var t,n,r,i,s,o,u,a,f,l,c,h,p,d,v,m,g,y,b,w,E,S;if(typeof e!="object"){if(this.options.error!=null&&typeof this.options.error=="function")return this.options.error.call(this,"Invalid JSON data"),!1;throw new Error("Invalid JSON response")}if(e.meta.code!==200){if(this.options.error!=null&&typeof this.options.error=="function")return this.options.error.call(this,e.meta.error_message),!1;throw new Error("Error from Instagram: "+e.meta.error_message)}if(e.data.length===0){if(this.options.error!=null&&typeof this.options.error=="function")return this.options.error.call(this,"No images were returned from Instagram"),!1;throw new Error("No images were returned from Instagram")}this.options.success!=null&&typeof this.options.success=="function"&&this.options.success.call(this,e),this.context.nextUrl="",e.pagination!=null&&(this.context.nextUrl=e.pagination.next_url);if(this.options.sortBy!=="none"){this.options.sortBy==="random"?d=["","random"]:d=this.options.sortBy.split("-"),p=d[0]==="least"?!0:!1;switch(d[1]){case"random":e.data.sort(function(){return.5-Math.random()});break;case"recent":e.data=this._sortBy(e.data,"created_time",p);break;case"liked":e.data=this._sortBy(e.data,"likes.count",p);break;case"commented":e.data=this._sortBy(e.data,"comments.count",p);break;default:throw new Error("Invalid option for sortBy: '"+this.options.sortBy+"'.")}}if(typeof document!="undefined"&&document!==null&&this.options.mock===!1){a=e.data,this.options.limit!=null&&a.length>this.options.limit&&(a=a.slice(0,this.options.limit+1||9e9)),n=document.createDocumentFragment(),this.options.filter!=null&&typeof this.options.filter=="function"&&(a=this._filter(a,this.options.filter));if(this.options.template!=null&&typeof this.options.template=="string"){i="",o="",l="",v=document.createElement("div");for(m=0,b=a.length;m<b;m++)s=a[m],u=s.images[this.options.resolution].url,this.options.useHttp||(u=u.replace("http://","//")),o=this._makeTemplate(this.options.template,{model:s,id:s.id,link:s.link,image:u,caption:this._getObjectProperty(s,"caption.text"),likes:s.likes.count,comments:s.comments.count,location:this._getObjectProperty(s,"location.name")}),i+=o;v.innerHTML=i,S=[].slice.call(v.childNodes);for(g=0,w=S.length;g<w;g++)h=S[g],n.appendChild(h)}else for(y=0,E=a.length;y<E;y++)s=a[y],f=document.createElement("img"),u=s.images[this.options.resolution].url,this.options.useHttp||(u=u.replace("http://","//")),f.src=u,this.options.links===!0?(t=document.createElement("a"),t.href=s.link,t.appendChild(f),n.appendChild(t)):n.appendChild(f);document.getElementById(this.options.target).appendChild(n),r=document.getElementsByTagName("head")[0],r.removeChild(document.getElementById("instafeed-fetcher")),c="instafeedCache"+this.unique,window[c]=void 0;try{delete window[c]}catch(x){}}return this.options.after!=null&&typeof this.options.after=="function"&&this.options.after.call(this),!0},e.prototype._buildUrl=function(){var e,t,n;e="https://api.instagram.com/v1";switch(this.options.get){case"popular":t="media/popular";break;case"tagged":if(typeof this.options.tagName!="string")throw new Error("No tag name specified. Use the 'tagName' option.");t="tags/"+this.options.tagName+"/media/recent";break;case"location":if(typeof this.options.locationId!="number")throw new Error("No location specified. Use the 'locationId' option.");t="locations/"+this.options.locationId+"/media/recent";break;case"user":if(typeof this.options.userId!="number")throw new Error("No user specified. Use the 'userId' option.");if(typeof this.options.accessToken!="string")throw new Error("No access token. Use the 'accessToken' option.");t="users/"+this.options.userId+"/media/recent";break;default:throw new Error("Invalid option for get: '"+this.options.get+"'.")}return n=""+e+"/"+t,this.options.accessToken!=null?n+="?access_token="+this.options.accessToken:n+="?client_id="+this.options.clientId,this.options.limit!=null&&(n+="&count="+this.options.limit),n+="&callback=instafeedCache"+this.unique+".parse",n},e.prototype._genKey=function(){var e;return e=function(){return((1+Math.random())*65536|0).toString(16).substring(1)},""+e()+e()+e()+e()},e.prototype._makeTemplate=function(e,t){var n,r,i,s,o;r=/(?:\{{2})([\w\[\]\.]+)(?:\}{2})/,n=e;while(r.test(n))i=n.match(r)[1],s=(o=this._getObjectProperty(t,i))!=null?o:"",n=n.replace(r,""+s);return n},e.prototype._getObjectProperty=function(e,t){var n,r;t=t.replace(/\[(\w+)\]/g,".$1"),r=t.split(".");while(r.length){n=r.shift();if(!(e!=null&&n in e))return null;e=e[n]}return e},e.prototype._sortBy=function(e,t,n){var r;return r=function(e,r){var i,s;return i=this._getObjectProperty(e,t),s=this._getObjectProperty(r,t),n?i>s?1:-1:i<s?1:-1},e.sort(r.bind(this)),e},e.prototype._filter=function(e,t){var n,r,i,s,o;n=[],i=function(e){if(t(e))return n.push(e)};for(s=0,o=e.length;s<o;s++)r=e[s],i(r);return n},e}(),t=typeof exports!="undefined"&&exports!==null?exports:window,t.Instafeed=e}).call(this);


  //]]></script>

<b:section id='footer-social1' showaddelement='yes'>
  <b:widget id='HTML4' locked='false' title='' type='HTML'>
    <b:widget-settings>
      <b:widget-setting name='content'>&lt;p class=&quot;buttond&quot;  style=&quot;text-align:center;&quot;&gt;&lt;a href=&quot;&quot; target=&quot;_self&quot; style=&quot;cursor: pointer; font-size:12px;  text-decoration: none; padding:8px 35px; color:#000000; background-color:#ffffff; border-radius:29px; border: 0px solid #000000;&quot;&gt;&lt;/a&gt;&lt;/p&gt;&lt;p class=&quot;buttond&quot;  style=&quot;text-align:center;&quot;&gt;&lt;a href=&quot;http://emiia.ru&quot; target=&quot;_self&quot; style=&quot;cursor: pointer; font-size:12px;  text-decoration: none; padding:8px 35px; color:#000000; background-color:#ffffff; border-radius:29px; border: 0px solid #000000;&quot;&gt;&lt;/a&gt;&lt;/p&gt;&lt;p class=&quot;buttond&quot;  style=&quot;text-align:center;&quot;&gt;&lt;a href=&quot;http://emiia.ru&quot; target=&quot;_self&quot; style=&quot;cursor: pointer; font-size:12px;  text-decoration: none; padding:8px 35px; color:#000000; background-color:#ffffff; border-radius:29px; border: 0px solid #000000;&quot;&gt;&lt;/a&gt;&lt;/p&gt;
&lt;p class=&quot;buttond&quot;  style=&quot;text-align:center;&quot;&gt;&lt;a href=&quot;http://emiia.ru.html&quot; target=&quot;_self&quot; style=&quot;cursor: pointer; font-size:8px;  text-decoration: none; padding:8px 35px; color:#000000; background-color:#ffffff; border-radius:29px; border: 0px solid #000000;&quot;&gt;&lt;/a&gt;&lt;/p&gt;



&lt;p class=&quot;buttond&quot;  style=&quot;text-align:center;&quot;&gt;&lt;a href=&quot;http://emiia.ru&quot; target=&quot;_self&quot; style=&quot;cursor: pointer; font-size:9px;  text-decoration: none; padding:11px 35px; color:#000000; background-color:#ffffff; border-radius:5px; border: 0px solid #000000;&quot;&gt;byEMIIA&lt;/a&gt;&lt;/p&gt;</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
  </b:widget>
</b:section>
	
	<div id='widget-area'>
	
		<div class='container'>
			<b:section class='footerwidget' id='container1' showaddelement='yes'/>
			<b:section class='footerwidget' id='container2' showaddelement='yes'/>
			<b:section class='footerwidget' id='container3' showaddelement='yes'/>
		</div>
		
	</div>

	
			
		
	
		
	<footer id='footer-copyright'>
		
		<div class='container'>
		
				<p> &#169; ә l EMIIA 2017-2018 <a href='http://www.emiia.ru' id='mycontent' style='visibility: hidden'>&#160;Blogger&#160;&gt;
        </a></p>
			<a class='to-top' href='http://www.emiia.ru'> <i class=''/></a>			
		</div>
		
	</footer>



	
<script>
      $(document).ready(function(){
        $(&quot;.widget h2&quot;).wrapInner(&quot;<span/>&quot;);
      });


    </script>


<script type='text/javascript'>//<![CDATA[
/**
 *
 * Released under the MIT license - http://opensource.org/licenses/MIT
 */
!function(t){var e={},s={mode:"horizontal",slideSelector:"",infiniteLoop:!0,hideControlOnEnd:!1,speed:500,easing:null,slideMargin:0,startSlide:0,randomStart:!1,captions:!1,ticker:!1,tickerHover:!1,adaptiveHeight:!1,adaptiveHeightSpeed:500,video:!1,useCSS:!0,preloadImages:"visible",responsive:!0,slideZIndex:50,touchEnabled:!0,swipeThreshold:50,oneToOneTouch:!0,preventDefaultSwipeX:!0,preventDefaultSwipeY:!1,pager:!0,pagerType:"full",pagerShortSeparator:" / ",pagerSelector:null,buildPager:null,pagerCustom:null,controls:!0,nextText:"Next",prevText:"Prev",nextSelector:null,prevSelector:null,autoControls:!1,startText:"Start",stopText:"Stop",autoControlsCombine:!1,autoControlsSelector:null,auto:!1,pause:4e3,autoStart:!0,autoDirection:"next",autoHover:!1,autoDelay:0,minSlides:1,maxSlides:1,moveSlides:0,slideWidth:0,onSliderLoad:function(){},onSlideBefore:function(){},onSlideAfter:function(){},onSlideNext:function(){},onSlidePrev:function(){},onSliderResize:function(){}};t.fn.bxSlider=function(n){if(0==this.length)return this;if(this.length>1)return this.each(function(){t(this).bxSlider(n)}),this;var o={},r=this;e.el=this;var a=t(window).width(),l=t(window).height(),d=function(){o.settings=t.extend({},s,n),o.settings.slideWidth=parseInt(o.settings.slideWidth),o.children=r.children(o.settings.slideSelector),o.children.length<o.settings.minSlides&&(o.settings.minSlides=o.children.length),o.children.length<o.settings.maxSlides&&(o.settings.maxSlides=o.children.length),o.settings.randomStart&&(o.settings.startSlide=Math.floor(Math.random()*o.children.length)),o.active={index:o.settings.startSlide},o.carousel=o.settings.minSlides>1||o.settings.maxSlides>1,o.carousel&&(o.settings.preloadImages="all"),o.minThreshold=o.settings.minSlides*o.settings.slideWidth+(o.settings.minSlides-1)*o.settings.slideMargin,o.maxThreshold=o.settings.maxSlides*o.settings.slideWidth+(o.settings.maxSlides-1)*o.settings.slideMargin,o.working=!1,o.controls={},o.interval=null,o.animProp="vertical"==o.settings.mode?"top":"left",o.usingCSS=o.settings.useCSS&&"fade"!=o.settings.mode&&function(){var t=document.createElement("div"),e=["WebkitPerspective","MozPerspective","OPerspective","msPerspective"];for(var i in e)if(void 0!==t.style[e[i]])return o.cssPrefix=e[i].replace("Perspective","").toLowerCase(),o.animProp="-"+o.cssPrefix+"-transform",!0;return!1}(),"vertical"==o.settings.mode&&(o.settings.maxSlides=o.settings.minSlides),r.data("origStyle",r.attr("style")),r.children(o.settings.slideSelector).each(function(){t(this).data("origStyle",t(this).attr("style"))}),c()},c=function(){r.wrap('<div class="bx-wrapper"><div class="bx-viewport"></div></div>'),o.viewport=r.parent(),o.loader=t('<div class="bx-loading" />'),o.viewport.prepend(o.loader),r.css({width:"horizontal"==o.settings.mode?100*o.children.length+215+"%":"auto",position:"relative"}),o.usingCSS&&o.settings.easing?r.css("-"+o.cssPrefix+"-transition-timing-function",o.settings.easing):o.settings.easing||(o.settings.easing="swing"),f(),o.viewport.css({width:"100%",overflow:"hidden",position:"relative"}),o.viewport.parent().css({maxWidth:p()}),o.settings.pager||o.viewport.parent().css({margin:"0 auto 0px"}),o.children.css({"float":"horizontal"==o.settings.mode?"left":"none",listStyle:"none",position:"relative"}),o.children.css("width",u()),"horizontal"==o.settings.mode&&o.settings.slideMargin>0&&o.children.css("marginRight",o.settings.slideMargin),"vertical"==o.settings.mode&&o.settings.slideMargin>0&&o.children.css("marginBottom",o.settings.slideMargin),"fade"==o.settings.mode&&(o.children.css({position:"absolute",zIndex:0,display:"none"}),o.children.eq(o.settings.startSlide).css({zIndex:o.settings.slideZIndex,display:"block"})),o.controls.el=t('<div class="bx-controls" />'),o.settings.captions&&P(),o.active.last=o.settings.startSlide==x()-1,o.settings.video&&r.fitVids();var e=o.children.eq(o.settings.startSlide);"all"==o.settings.preloadImages&&(e=o.children),o.settings.ticker?o.settings.pager=!1:(o.settings.pager&&T(),o.settings.controls&&C(),o.settings.auto&&o.settings.autoControls&&E(),(o.settings.controls||o.settings.autoControls||o.settings.pager)&&o.viewport.after(o.controls.el)),g(e,h)},g=function(e,i){var s=e.find("img, iframe").length;if(0==s)return i(),void 0;var n=0;e.find("img, iframe").each(function(){t(this).one("load",function(){++n==s&&i()}).each(function(){this.complete&&t(this).load()})})},h=function(){if(o.settings.infiniteLoop&&"fade"!=o.settings.mode&&!o.settings.ticker){var e="vertical"==o.settings.mode?o.settings.minSlides:o.settings.maxSlides,i=o.children.slice(0,e).clone().addClass("bx-clone"),s=o.children.slice(-e).clone().addClass("bx-clone");r.append(i).prepend(s)}o.loader.remove(),S(),"vertical"==o.settings.mode&&(o.settings.adaptiveHeight=!0),o.viewport.height(v()),r.redrawSlider(),o.settings.onSliderLoad(o.active.index),o.initialized=!0,o.settings.responsive&&t(window).bind("resize",Z),o.settings.auto&&o.settings.autoStart&&H(),o.settings.ticker&&L(),o.settings.pager&&q(o.settings.startSlide),o.settings.controls&&W(),o.settings.touchEnabled&&!o.settings.ticker&&O()},v=function(){var e=0,s=t();if("vertical"==o.settings.mode||o.settings.adaptiveHeight)if(o.carousel){var n=1==o.settings.moveSlides?o.active.index:o.active.index*m();for(s=o.children.eq(n),i=1;i<=o.settings.maxSlides-1;i++)s=n+i>=o.children.length?s.add(o.children.eq(i-1)):s.add(o.children.eq(n+i))}else s=o.children.eq(o.active.index);else s=o.children;return"vertical"==o.settings.mode?(s.each(function(){e+=t(this).outerHeight()}),o.settings.slideMargin>0&&(e+=o.settings.slideMargin*(o.settings.minSlides-1))):e=Math.max.apply(Math,s.map(function(){return t(this).outerHeight(!1)}).get()),e},p=function(){var t="100%";return o.settings.slideWidth>0&&(t="horizontal"==o.settings.mode?o.settings.maxSlides*o.settings.slideWidth+(o.settings.maxSlides-1)*o.settings.slideMargin:o.settings.slideWidth),t},u=function(){var t=o.settings.slideWidth,e=o.viewport.width();return 0==o.settings.slideWidth||o.settings.slideWidth>e&&!o.carousel||"vertical"==o.settings.mode?t=e:o.settings.maxSlides>1&&"horizontal"==o.settings.mode&&(e>o.maxThreshold||e<o.minThreshold&&(t=(e-o.settings.slideMargin*(o.settings.minSlides-1))/o.settings.minSlides)),t},f=function(){var t=1;if("horizontal"==o.settings.mode&&o.settings.slideWidth>0)if(o.viewport.width()<o.minThreshold)t=o.settings.minSlides;else if(o.viewport.width()>o.maxThreshold)t=o.settings.maxSlides;else{var e=o.children.first().width();t=Math.floor(o.viewport.width()/e)}else"vertical"==o.settings.mode&&(t=o.settings.minSlides);return t},x=function(){var t=0;if(o.settings.moveSlides>0)if(o.settings.infiniteLoop)t=o.children.length/m();else for(var e=0,i=0;e<o.children.length;)++t,e=i+f(),i+=o.settings.moveSlides<=f()?o.settings.moveSlides:f();else t=Math.ceil(o.children.length/f());return t},m=function(){return o.settings.moveSlides>0&&o.settings.moveSlides<=f()?o.settings.moveSlides:f()},S=function(){if(o.children.length>o.settings.maxSlides&&o.active.last&&!o.settings.infiniteLoop){if("horizontal"==o.settings.mode){var t=o.children.last(),e=t.position();b(-(e.left-(o.viewport.width()-t.width())),"reset",0)}else if("vertical"==o.settings.mode){var i=o.children.length-o.settings.minSlides,e=o.children.eq(i).position();b(-e.top,"reset",0)}}else{var e=o.children.eq(o.active.index*m()).position();o.active.index==x()-1&&(o.active.last=!0),void 0!=e&&("horizontal"==o.settings.mode?b(-e.left,"reset",0):"vertical"==o.settings.mode&&b(-e.top,"reset",0))}},b=function(t,e,i,s){if(o.usingCSS){var n="vertical"==o.settings.mode?"translate3d(0, "+t+"px, 0)":"translate3d("+t+"px, 0, 0)";r.css("-"+o.cssPrefix+"-transition-duration",i/1e3+"s"),"slide"==e?(r.css(o.animProp,n),r.bind("transitionend webkitTransitionEnd oTransitionEnd MSTransitionEnd",function(){r.unbind("transitionend webkitTransitionEnd oTransitionEnd MSTransitionEnd"),D()})):"reset"==e?r.css(o.animProp,n):"ticker"==e&&(r.css("-"+o.cssPrefix+"-transition-timing-function","linear"),r.css(o.animProp,n),r.bind("transitionend webkitTransitionEnd oTransitionEnd MSTransitionEnd",function(){r.unbind("transitionend webkitTransitionEnd oTransitionEnd MSTransitionEnd"),b(s.resetValue,"reset",0),N()}))}else{var a={};a[o.animProp]=t,"slide"==e?r.animate(a,i,o.settings.easing,function(){D()}):"reset"==e?r.css(o.animProp,t):"ticker"==e&&r.animate(a,speed,"linear",function(){b(s.resetValue,"reset",0),N()})}},w=function(){for(var e="",i=x(),s=0;i>s;s++){var n="";o.settings.buildPager&&t.isFunction(o.settings.buildPager)?(n=o.settings.buildPager(s),o.pagerEl.addClass("bx-custom-pager")):(n=s+1,o.pagerEl.addClass("bx-default-pager")),e+='<div class="bx-pager-item"><a href="" data-slide-index="'+s+'" class="bx-pager-link">'+n+"</a></div>"}o.pagerEl.html(e)},T=function(){o.settings.pagerCustom?o.pagerEl=t(o.settings.pagerCustom):(o.pagerEl=t('<div class="bx-pager" />'),o.settings.pagerSelector?t(o.settings.pagerSelector).html(o.pagerEl):o.controls.el.addClass("bx-has-pager").append(o.pagerEl),w()),o.pagerEl.on("click","a",I)},C=function(){o.controls.next=t('<a class="bx-next" href="">'+o.settings.nextText+"</a>"),o.controls.prev=t('<a class="bx-prev" href="">'+o.settings.prevText+"</a>"),o.controls.next.bind("click",y),o.controls.prev.bind("click",z),o.settings.nextSelector&&t(o.settings.nextSelector).append(o.controls.next),o.settings.prevSelector&&t(o.settings.prevSelector).append(o.controls.prev),o.settings.nextSelector||o.settings.prevSelector||(o.controls.directionEl=t('<div class="bx-controls-direction" />'),o.controls.directionEl.append(o.controls.prev).append(o.controls.next),o.controls.el.addClass("bx-has-controls-direction").append(o.controls.directionEl))},E=function(){o.controls.start=t('<div class="bx-controls-auto-item"><a class="bx-start" href="">'+o.settings.startText+"</a></div>"),o.controls.stop=t('<div class="bx-controls-auto-item"><a class="bx-stop" href="">'+o.settings.stopText+"</a></div>"),o.controls.autoEl=t('<div class="bx-controls-auto" />'),o.controls.autoEl.on("click",".bx-start",k),o.controls.autoEl.on("click",".bx-stop",M),o.settings.autoControlsCombine?o.controls.autoEl.append(o.controls.start):o.controls.autoEl.append(o.controls.start).append(o.controls.stop),o.settings.autoControlsSelector?t(o.settings.autoControlsSelector).html(o.controls.autoEl):o.controls.el.addClass("bx-has-controls-auto").append(o.controls.autoEl),A(o.settings.autoStart?"stop":"start")},P=function(){o.children.each(function(){var e=t(this).find("img:first").attr("title");void 0!=e&&(""+e).length&&t(this).append('<div class="bx-caption"><span>'+e+"</span></div>")})},y=function(t){o.settings.auto&&r.stopAuto(),r.goToNextSlide(),t.preventDefault()},z=function(t){o.settings.auto&&r.stopAuto(),r.goToPrevSlide(),t.preventDefault()},k=function(t){r.startAuto(),t.preventDefault()},M=function(t){r.stopAuto(),t.preventDefault()},I=function(e){o.settings.auto&&r.stopAuto();var i=t(e.currentTarget),s=parseInt(i.attr("data-slide-index"));s!=o.active.index&&r.goToSlide(s),e.preventDefault()},q=function(e){var i=o.children.length;return"short"==o.settings.pagerType?(o.settings.maxSlides>1&&(i=Math.ceil(o.children.length/o.settings.maxSlides)),o.pagerEl.html(e+1+o.settings.pagerShortSeparator+i),void 0):(o.pagerEl.find("a").removeClass("active"),o.pagerEl.each(function(i,s){t(s).find("a").eq(e).addClass("active")}),void 0)},D=function(){if(o.settings.infiniteLoop){var t="";0==o.active.index?t=o.children.eq(0).position():o.active.index==x()-1&&o.carousel?t=o.children.eq((x()-1)*m()).position():o.active.index==o.children.length-1&&(t=o.children.eq(o.children.length-1).position()),t&&("horizontal"==o.settings.mode?b(-t.left,"reset",0):"vertical"==o.settings.mode&&b(-t.top,"reset",0))}o.working=!1,o.settings.onSlideAfter(o.children.eq(o.active.index),o.oldIndex,o.active.index)},A=function(t){o.settings.autoControlsCombine?o.controls.autoEl.html(o.controls[t]):(o.controls.autoEl.find("a").removeClass("active"),o.controls.autoEl.find("a:not(.bx-"+t+")").addClass("active"))},W=function(){1==x()?(o.controls.prev.addClass("disabled"),o.controls.next.addClass("disabled")):!o.settings.infiniteLoop&&o.settings.hideControlOnEnd&&(0==o.active.index?(o.controls.prev.addClass("disabled"),o.controls.next.removeClass("disabled")):o.active.index==x()-1?(o.controls.next.addClass("disabled"),o.controls.prev.removeClass("disabled")):(o.controls.prev.removeClass("disabled"),o.controls.next.removeClass("disabled")))},H=function(){o.settings.autoDelay>0?setTimeout(r.startAuto,o.settings.autoDelay):r.startAuto(),o.settings.autoHover&&r.hover(function(){o.interval&&(r.stopAuto(!0),o.autoPaused=!0)},function(){o.autoPaused&&(r.startAuto(!0),o.autoPaused=null)})},L=function(){var e=0;if("next"==o.settings.autoDirection)r.append(o.children.clone().addClass("bx-clone"));else{r.prepend(o.children.clone().addClass("bx-clone"));var i=o.children.first().position();e="horizontal"==o.settings.mode?-i.left:-i.top}b(e,"reset",0),o.settings.pager=!1,o.settings.controls=!1,o.settings.autoControls=!1,o.settings.tickerHover&&!o.usingCSS&&o.viewport.hover(function(){r.stop()},function(){var e=0;o.children.each(function(){e+="horizontal"==o.settings.mode?t(this).outerWidth(!0):t(this).outerHeight(!0)});var i=o.settings.speed/e,s="horizontal"==o.settings.mode?"left":"top",n=i*(e-Math.abs(parseInt(r.css(s))));N(n)}),N()},N=function(t){speed=t?t:o.settings.speed;var e={left:0,top:0},i={left:0,top:0};"next"==o.settings.autoDirection?e=r.find(".bx-clone").first().position():i=o.children.first().position();var s="horizontal"==o.settings.mode?-e.left:-e.top,n="horizontal"==o.settings.mode?-i.left:-i.top,a={resetValue:n};b(s,"ticker",speed,a)},O=function(){o.touch={start:{x:0,y:0},end:{x:0,y:0}},o.viewport.bind("touchstart",X)},X=function(t){if(o.working)t.preventDefault();else{o.touch.originalPos=r.position();var e=t.originalEvent;o.touch.start.x=e.changedTouches[0].pageX,o.touch.start.y=e.changedTouches[0].pageY,o.viewport.bind("touchmove",Y),o.viewport.bind("touchend",V)}},Y=function(t){var e=t.originalEvent,i=Math.abs(e.changedTouches[0].pageX-o.touch.start.x),s=Math.abs(e.changedTouches[0].pageY-o.touch.start.y);if(3*i>s&&o.settings.preventDefaultSwipeX?t.preventDefault():3*s>i&&o.settings.preventDefaultSwipeY&&t.preventDefault(),"fade"!=o.settings.mode&&o.settings.oneToOneTouch){var n=0;if("horizontal"==o.settings.mode){var r=e.changedTouches[0].pageX-o.touch.start.x;n=o.touch.originalPos.left+r}else{var r=e.changedTouches[0].pageY-o.touch.start.y;n=o.touch.originalPos.top+r}b(n,"reset",0)}},V=function(t){o.viewport.unbind("touchmove",Y);var e=t.originalEvent,i=0;if(o.touch.end.x=e.changedTouches[0].pageX,o.touch.end.y=e.changedTouches[0].pageY,"fade"==o.settings.mode){var s=Math.abs(o.touch.start.x-o.touch.end.x);s>=o.settings.swipeThreshold&&(o.touch.start.x>o.touch.end.x?r.goToNextSlide():r.goToPrevSlide(),r.stopAuto())}else{var s=0;"horizontal"==o.settings.mode?(s=o.touch.end.x-o.touch.start.x,i=o.touch.originalPos.left):(s=o.touch.end.y-o.touch.start.y,i=o.touch.originalPos.top),!o.settings.infiniteLoop&&(0==o.active.index&&s>0||o.active.last&&0>s)?b(i,"reset",200):Math.abs(s)>=o.settings.swipeThreshold?(0>s?r.goToNextSlide():r.goToPrevSlide(),r.stopAuto()):b(i,"reset",200)}o.viewport.unbind("touchend",V)},Z=function(){var e=t(window).width(),i=t(window).height();(a!=e||l!=i)&&(a=e,l=i,r.redrawSlider(),o.settings.onSliderResize.call(r,o.active.index))};return r.goToSlide=function(e,i){if(!o.working&&o.active.index!=e)if(o.working=!0,o.oldIndex=o.active.index,o.active.index=0>e?x()-1:e>=x()?0:e,o.settings.onSlideBefore(o.children.eq(o.active.index),o.oldIndex,o.active.index),"next"==i?o.settings.onSlideNext(o.children.eq(o.active.index),o.oldIndex,o.active.index):"prev"==i&&o.settings.onSlidePrev(o.children.eq(o.active.index),o.oldIndex,o.active.index),o.active.last=o.active.index>=x()-1,o.settings.pager&&q(o.active.index),o.settings.controls&&W(),"fade"==o.settings.mode)o.settings.adaptiveHeight&&o.viewport.height()!=v()&&o.viewport.animate({height:v()},o.settings.adaptiveHeightSpeed),o.children.filter(":visible").fadeOut(o.settings.speed).css({zIndex:0}),o.children.eq(o.active.index).css("zIndex",o.settings.slideZIndex+1).fadeIn(o.settings.speed,function(){t(this).css("zIndex",o.settings.slideZIndex),D()});else{o.settings.adaptiveHeight&&o.viewport.height()!=v()&&o.viewport.animate({height:v()},o.settings.adaptiveHeightSpeed);var s=0,n={left:0,top:0};if(!o.settings.infiniteLoop&&o.carousel&&o.active.last)if("horizontal"==o.settings.mode){var a=o.children.eq(o.children.length-1);n=a.position(),s=o.viewport.width()-a.outerWidth()}else{var l=o.children.length-o.settings.minSlides;n=o.children.eq(l).position()}else if(o.carousel&&o.active.last&&"prev"==i){var d=1==o.settings.moveSlides?o.settings.maxSlides-m():(x()-1)*m()-(o.children.length-o.settings.maxSlides),a=r.children(".bx-clone").eq(d);n=a.position()}else if("next"==i&&0==o.active.index)n=r.find("> .bx-clone").eq(o.settings.maxSlides).position(),o.active.last=!1;else if(e>=0){var c=e*m();n=o.children.eq(c).position()}if("undefined"!=typeof n){var g="horizontal"==o.settings.mode?-(n.left-s):-n.top;b(g,"slide",o.settings.speed)}}},r.goToNextSlide=function(){if(o.settings.infiniteLoop||!o.active.last){var t=parseInt(o.active.index)+1;r.goToSlide(t,"next")}},r.goToPrevSlide=function(){if(o.settings.infiniteLoop||0!=o.active.index){var t=parseInt(o.active.index)-1;r.goToSlide(t,"prev")}},r.startAuto=function(t){o.interval||(o.interval=setInterval(function(){"next"==o.settings.autoDirection?r.goToNextSlide():r.goToPrevSlide()},o.settings.pause),o.settings.autoControls&&1!=t&&A("stop"))},r.stopAuto=function(t){o.interval&&(clearInterval(o.interval),o.interval=null,o.settings.autoControls&&1!=t&&A("start"))},r.getCurrentSlide=function(){return o.active.index},r.getCurrentSlideElement=function(){return o.children.eq(o.active.index)},r.getSlideCount=function(){return o.children.length},r.redrawSlider=function(){o.children.add(r.find(".bx-clone")).outerWidth(u()),o.viewport.css("height",v()),o.settings.ticker||S(),o.active.last&&(o.active.index=x()-1),o.active.index>=x()&&(o.active.last=!0),o.settings.pager&&!o.settings.pagerCustom&&(w(),q(o.active.index))},r.destroySlider=function(){o.initialized&&(o.initialized=!1,t(".bx-clone",this).remove(),o.children.each(function(){void 0!=t(this).data("origStyle")?t(this).attr("style",t(this).data("origStyle")):t(this).removeAttr("style")}),void 0!=t(this).data("origStyle")?this.attr("style",t(this).data("origStyle")):t(this).removeAttr("style"),t(this).unwrap().unwrap(),o.controls.el&&o.controls.el.remove(),o.controls.next&&o.controls.next.remove(),o.controls.prev&&o.controls.prev.remove(),o.pagerEl&&o.settings.controls&&o.pagerEl.remove(),t(".bx-caption",this).remove(),o.controls.autoEl&&o.controls.autoEl.remove(),clearInterval(o.interval),o.settings.responsive&&t(window).unbind("resize",Z))},r.reloadSlider=function(t){void 0!=t&&(n=t),r.destroySlider(),d()},d(),this}}(jQuery);
//]]></script>
<script type='text/javascript'>//<![CDATA[
(function($){$.fn.fitVids=function(options){var settings={customSelector:null}
var div=document.createElement('div'),ref=document.getElementsByTagName('base')[0]||document.getElementsByTagName('script')[0];div.className='fit-vids-style';div.innerHTML='&shy;<style> \
.fluid-width-video-wrapper { \
width: 100%; \
position: relative; \
padding: 0; \
} \
\
.fluid-width-video-wrapper iframe, \
.fluid-width-video-wrapper object, \
.fluid-width-video-wrapper embed { \
position: absolute; \
top: 0; \
left: 0; \
width: 100%; \
height: 100%; \
} \
</style>';ref.parentNode.insertBefore(div,ref);if(options){$.extend(settings,options);}
return this.each(function(){var selectors=["iframe[src*='player.vimeo.com']","iframe[src*='www.youtube.com']","iframe[src*='www.kickstarter.com']","object","embed"];if(settings.customSelector){selectors.push(settings.customSelector);}
var $allVideos=$(this).find(selectors.join(','));$allVideos.each(function(){var $this=$(this);if(this.tagName.toLowerCase()=='embed'&&$this.parent('object').length||$this.parent('.fluid-width-video-wrapper').length){return;}
var height=this.tagName.toLowerCase()=='object'?$this.attr('height'):$this.height(),aspectRatio=height/$this.width();if(!$this.attr('id')){var videoID='fitvid'+ Math.floor(Math.random()*999999);$this.attr('id',videoID);}
$this.wrap('<div class="fluid-width-video-wrapper"></div>').parent('.fluid-width-video-wrapper').css('padding-top',(aspectRatio*100)+"%");$this.removeAttr('height').removeAttr('width');});});}})(jQuery);
//]]></script>
<script type='text/javascript'>//<![CDATA[
/*!
    SlickNav Responsive Mobile Menu
    (c) 2014 Josh Cope
    licensed under MIT
*/
;(function(e,t,n){function o(t,n){this.element=t;this.settings=e.extend({},r,n);this._defaults=r;this._name=i;this.init()}var r={label:"MENU",duplicate:true,duration:200,easingOpen:"swing",easingClose:"swing",closedSymbol:"&#9658;",openedSymbol:"&#9660;",prependTo:"body",parentTag:"a",closeOnClick:false,allowParentLinks:false,nestedParentLinks:true,showChildren:false,init:function(){},open:function(){},close:function(){}},i="slicknav",s="slicknav";o.prototype.init=function(){var n=this;var r=e(this.element);var i=this.settings;if(i.duplicate){n.mobileNav=r.clone();n.mobileNav.removeAttr("id");n.mobileNav.find("*").each(function(t,n){e(n).removeAttr("id")})}else n.mobileNav=r;var o=s+"_icon";if(i.label===""){o+=" "+s+"_no-text"}if(i.parentTag=="a"){i.parentTag='a href="#"'}n.mobileNav.attr("class",s+"_nav");var u=e('<div class="'+s+'_menu"></div>');n.btn=e("<"+i.parentTag+' aria-haspopup="true" tabindex="0" class="'+s+"_btn "+s+'_collapsed"><span class="'+s+'_menutxt">'+i.label+'</span><span class="'+o+'"><span class="'+s+'_icon-bar"></span><span class="'+s+'_icon-bar"></span><span class="'+s+'_icon-bar"></span></span></a>');e(u).append(n.btn);e(i.prependTo).prepend(u);u.append(n.mobileNav);var a=n.mobileNav.find("li");e(a).each(function(){var t=e(this);var r={};r.children=t.children("ul").attr("role","menu");t.data("menu",r);if(r.children.length>0){var o=t.contents();var u=false;var a=[];e(o).each(function(){if(!e(this).is("ul")){a.push(this)}else{return false}if(e(this).is("a")){u=true}});var f=e("<"+i.parentTag+' role="menuitem" aria-haspopup="true" tabindex="-1" class="'+s+'_item"/>');if(!i.allowParentLinks||i.nestedParentLinks||!u){var l=e(a).wrapAll(f).parent();l.addClass(s+"_row")}else e(a).wrapAll('<span class="'+s+"_parent-link "+s+'_row"/>').parent();t.addClass(s+"_collapsed");t.addClass(s+"_parent");var c=e('<span class="'+s+'_arrow">'+i.closedSymbol+"</span>");if(i.allowParentLinks&&!i.nestedParentLinks&&u)c=c.wrap(f).parent();e(a).last().after(c)}else if(t.children().length===0){t.addClass(s+"_txtnode")}t.children("a").attr("role","menuitem").click(function(t){if(i.closeOnClick&&!e(t.target).parent().closest("li").hasClass(s+"_parent"))e(n.btn).click()});if(i.closeOnClick&&i.allowParentLinks){t.children("a").children("a").click(function(t){e(n.btn).click()});t.find("."+s+"_parent-link a:not(."+s+"_item)").click(function(t){e(n.btn).click()})}});e(a).each(function(){var t=e(this).data("menu");if(!i.showChildren){n._visibilityToggle(t.children,null,false,null,true)}});n._visibilityToggle(n.mobileNav,null,false,"init",true);n.mobileNav.attr("role","menu");e(t).mousedown(function(){n._outlines(false)});e(t).keyup(function(){n._outlines(true)});e(n.btn).click(function(e){e.preventDefault();n._menuToggle()});n.mobileNav.on("click","."+s+"_item",function(t){t.preventDefault();n._itemClick(e(this))});e(n.btn).keydown(function(e){var t=e||event;if(t.keyCode==13){e.preventDefault();n._menuToggle()}});n.mobileNav.on("keydown","."+s+"_item",function(t){var r=t||event;if(r.keyCode==13){t.preventDefault();n._itemClick(e(t.target))}});if(i.allowParentLinks&&i.nestedParentLinks){e("."+s+"_item a").click(function(e){e.stopImmediatePropagation()})}};o.prototype._menuToggle=function(e){var t=this;var n=t.btn;var r=t.mobileNav;if(n.hasClass(s+"_collapsed")){n.removeClass(s+"_collapsed");n.addClass(s+"_open")}else{n.removeClass(s+"_open");n.addClass(s+"_collapsed")}n.addClass(s+"_animating");t._visibilityToggle(r,n.parent(),true,n)};o.prototype._itemClick=function(e){var t=this;var n=t.settings;var r=e.data("menu");if(!r){r={};r.arrow=e.children("."+s+"_arrow");r.ul=e.next("ul");r.parent=e.parent();if(r.parent.hasClass(s+"_parent-link")){r.parent=e.parent().parent();r.ul=e.parent().next("ul")}e.data("menu",r)}if(r.parent.hasClass(s+"_collapsed")){r.arrow.html(n.openedSymbol);r.parent.removeClass(s+"_collapsed");r.parent.addClass(s+"_open");r.parent.addClass(s+"_animating");t._visibilityToggle(r.ul,r.parent,true,e)}else{r.arrow.html(n.closedSymbol);r.parent.addClass(s+"_collapsed");r.parent.removeClass(s+"_open");r.parent.addClass(s+"_animating");t._visibilityToggle(r.ul,r.parent,true,e)}};o.prototype._visibilityToggle=function(t,n,r,i,o){var u=this;var a=u.settings;var f=u._getActionItems(t);var l=0;if(r)l=a.duration;if(t.hasClass(s+"_hidden")){t.removeClass(s+"_hidden");t.slideDown(l,a.easingOpen,function(){e(i).removeClass(s+"_animating");e(n).removeClass(s+"_animating");if(!o){a.open(i)}});t.attr("aria-hidden","false");f.attr("tabindex","0");u._setVisAttr(t,false)}else{t.addClass(s+"_hidden");t.slideUp(l,this.settings.easingClose,function(){t.attr("aria-hidden","true");f.attr("tabindex","-1");u._setVisAttr(t,true);t.hide();e(i).removeClass(s+"_animating");e(n).removeClass(s+"_animating");if(!o)a.close(i);else if(i=="init")a.init()})}};o.prototype._setVisAttr=function(t,n){var r=this;var i=t.children("li").children("ul").not("."+s+"_hidden");if(!n){i.each(function(){var t=e(this);t.attr("aria-hidden","false");var i=r._getActionItems(t);i.attr("tabindex","0");r._setVisAttr(t,n)})}else{i.each(function(){var t=e(this);t.attr("aria-hidden","true");var i=r._getActionItems(t);i.attr("tabindex","-1");r._setVisAttr(t,n)})}};o.prototype._getActionItems=function(e){var t=e.data("menu");if(!t){t={};var n=e.children("li");var r=n.find("a");t.links=r.add(n.find("."+s+"_item"));e.data("menu",t)}return t.links};o.prototype._outlines=function(t){if(!t){e("."+s+"_item, ."+s+"_btn").css("outline","none")}else{e("."+s+"_item, ."+s+"_btn").css("outline","")}};o.prototype.toggle=function(){var e=this;e._menuToggle()};o.prototype.open=function(){var e=this;if(e.btn.hasClass(s+"_collapsed")){e._menuToggle()}};o.prototype.close=function(){var e=this;if(e.btn.hasClass(s+"_open")){e._menuToggle()}};e.fn[i]=function(t){var n=arguments;if(t===undefined||typeof t==="object"){return this.each(function(){if(!e.data(this,"plugin_"+i)){e.data(this,"plugin_"+i,new o(this,t))}})}else if(typeof t==="string"&&t[0]!=="_"&&t!=="init"){var r;this.each(function(){var s=e.data(this,"plugin_"+i);if(s instanceof o&&typeof s[t]==="function"){r=s[t].apply(s,Array.prototype.slice.call(n,1))}});return r!==undefined?r:this}}})(jQuery,document,window)
//]]></script>
<script type='text/javascript'>//<![CDATA[
jQuery(document).ready(function($){"use strict";$('#top-search a').on('click',function(e){e.preventDefault();$('.show-search').slideToggle('fast');});$('.to-top').click(function(){$('html, body').animate({scrollTop:0},800);return false;});$('.bxslider').bxSlider({adaptiveHeight:true,mode:'fade',pager:false,captions:true});$(document).ready(function(){$(".container").fitVids();});$('.menu').slicknav({prependTo:'.menu-mobile',label:''});});
//]]></script>

 
	
     <b:include data='blog' name='google-analytics'/>
</body>
</html>
