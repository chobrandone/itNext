<template>
  <div id="app">
  
    <Home/>
  </div>
</template>

<script>
import Home from './components/home.vue'

export default {
  name: 'App',
  components: {
    Home
  }
}
</script>

<style>

/*------------------------------------------------------------------
		1. IMPORT FONTS
	-------------------------------------------------------------------*/

@import url(https://fonts.googleapis.com/css?family=Source+Sans+Pro:300,400,400i,600,700,900);
@import url('https://fonts.googleapis.com/css?family=Raleway:100,100i,200,200i,300,300i,400,400i,500,500i,600,600i,700,700i,800,800i,900,900i');
@import url('https://fonts.googleapis.com/css?family=Poppins:100,100i,200,200i,300,300i,400,400i,500,500i,600,600i,700,700i,800,800i,900,900i');
@import url(https://fonts.googleapis.com/css?family=Roboto:300,400,400i,500,500i,700,700i);
@import url(https://fonts.googleapis.com/css?family=Arvo:400,400i,700,700i);

/*------------------------------------------------------------------
		2. IMPORT FILES
	-------------------------------------------------------------------*/


@import url("../src/assets/css/animate.css");
@import url("../src/assets/css/font-awesome.min.css");

/*------------------------------------------------------------------
		3. BASIC
	-------------------------------------------------------------------*/

* {
	margin: 0;
	padding: 0;
	outline: none !important;
	box-sizing: border-box;
}

html,
body {
	color: #898989;
	font-size: 15px;
	font-family: 'Raleway', sans-serif;
	line-height: normal;
	font-weight: 400;
	overflow-x: hidden;
}

body {
	overflow-x: hidden;
}



body.demos .section-title img {
	max-width: 280px;
	display: block;
	margin: 10px auto;
}

body.demos .service-widget h3 {
	border-bottom: 1px solid #ededed;
	font-size: 18px;
	padding: 20px 0;
	background-color: #ffffff;
}

body.demos .service-widget {
	margin: 0 0 30px;
	padding: 30px;
	background-color: #fff
}

body.demos .container-fluid {
	max-width: 1080px
}

a {
	color: #1f1f1f;
	text-decoration: none !important;
	outline: none !important;
	-webkit-transition: all .3s ease-in-out;
	-moz-transition: all .3s ease-in-out;
	-ms-transition: all .3s ease-in-out;
	-o-transition: all .3s ease-in-out;
	transition: all .3s ease-in-out;
}

h1,
h2,
h3,
h4,
h5,
h6 {
	letter-spacing: 0;
	font-weight: normal;
	position: relative;
	padding: 0;
	font-weight: normal;
	line-height: normal;
	color: #1f1f1f;
	margin: 0
}

h6 {
	font-size: 14px;
	margin-bottom: 10px;
}

h1 {
	font-size: 24px
}

.small_heading.main-heading h2 {
	font-size: 21px;
}

.small_heading.main-heading::after {
	top: 18px;
}

.small_heading.main-heading {
	margin-bottom: 20px;
	width: 100%;
}

h3 {
	font-size: 18px
}

h4 {
	font-size: 16px
}

h5 {
	font-size: 14px
}

h1 a,
h2 a,
h3 a,
h4 a,
h5 a,
h6 a {
	color: #212121;
	text-decoration: none!important;
	opacity: 1
}

ol,
ul {
	list-style: none;
	margin: 0;
}

a {
	color: #000;
	text-decoration: none;
	outline: none;
}

a,
.btn {
	text-decoration: none !important;
	outline: none !important;
	-webkit-transition: all .3s ease-in-out;
	-moz-transition: all .3s ease-in-out;
	-ms-transition: all .3s ease-in-out;
	-o-transition: all .3s ease-in-out;
	transition: all .3s ease-in-out;
}

.btn-custom {
	margin-top: 20px;
	background-color: transparent;
	border: 2px solid #ddd;
	padding: 12px 40px;
	font-size: 16px;
}

.button_section {
	float: left;
	width: 100%;
}

a.btn,
button.btn {
	min-width: 170px;
	height: 50px;
	border-radius: 100px;
	padding: 0;
	text-align: center;
	line-height: 52px;
	font-size: 14px;
	font-weight: 600;
	text-transform: uppercase;
	margin-top: 10px;
	color: #fff;
	border: solid transform 1px;
	text-shadow: 1px 1px 3px rgba(0, 0, 0, .5);
	position: relative;
	font-family: 'Poppins', sans-serif;
}

.btn.dark_gray_bt {
	background: #252525;
}

a.btn.border_btn {
	border: solid transparent 1px;
	background: transparent;
}

a.btn:hover,
button.btn:hover,
a.btn:focus,
button.btn:focus {
	background: #252525;
	color: #fff;
}

button.btn.white_btn,
a.btn.white_btnbutton.btn.white_btn,
a.btn.white_btn {
	background: #fff;
	padding: 0 50px;
}

.btn.sqaure_bt i {
	margin-left: 8px;
	font-weight: 600;
	top: -1px;
	position: relative;
}

.bottom_info .btn.sqaure_bt {
	margin: 0;
}

.bottom_info .pull-right {
	margin-top: 17px !important;
}

.blog_grid .bottom_info .pull-right {
	margin-top: 0 !important;
}

.padding-bottom_0 {
	padding-bottom: 0 !important;
}

.padding-top_0 {
	padding-top: 0 !important;
}

.padding-bottom_1 {
	padding-bottom: 10px !important;
}

.padding-bottom_2 {
	padding-bottom: 20px !important;
}

.padding-bottom_3 {
	padding-bottom: 30px !important;
}

.padding-bottom_4 {
	padding-bottom: 40px !important;
}

.padding-bottom_5 {
	padding-bottom: 50px !important;
}

.pull-right {
	float: right !important;
}

.pull-left {
	float: left !important;
}

.img-responsive {
	max-width: 100%;
}

.color_black p,
.color_black ul,
.color_black ul li {
	color: #000;
}

.black_color {
	color: #000;
}

.semi_bold {
	font-weight: 600;
}

.lead {
	font-size: 18px;
	line-height: 30px;
	color: #767676;
	margin: 0;
	padding: 0;
}

blockquote {
	margin: 20px 0 20px;
	padding: 30px;
}

.margin_0 {
	margin: 0 !important;
}

.padding_0 {
	padding: 0 !important;
}

h2 {
	font-size: 35px;
	color: #000;
	line-height: 36px;
	font-weight: 600;
	position: relative;
	margin-bottom: 15px;
	text-transform: uppercase;
	margin-top: 15px;
}

h3 {
	font-size: 24px;
	color: #000;
	line-height: normal;
	font-weight: 500;
	text-transform: none;
	margin-bottom: 20px;
	font-weight: 600;
}

h4 {
	font-size: 18px;
	color: #000;
	line-height: 21px;
	font-weight: 600;
	text-transform: none;
	margin: 30px 0 20px 0;
}

h5 {
	font-size: 15px;
	font-weight: 700;
	text-transform: uppercase;
	margin: 0;
	line-height: normal;
	color: #000;
}

p {
	color: #707070;
	font-size: 15px;
	line-height: 21px;
}

p.large {
	color: #898989;
	font-size: 20px;
	font-weight: 400;
	margin: 0 0 10px 0;
}

p.large_2 {
	font-weight: 500;
	font-size: 18px;
	color: #898989;
}

button,
input,
select,
textarea,
option {
	font-family: 'Poppins', sans-serif;
}

a#submit {
	z-index: 1;
}

a:hover,
a:focus {
	color: #000;
	text-decoration: none;
}

.span1,
.span2,
.span3,
.span4,
.span5,
.span6,
.span7,
.span8,
.span9,
.span10 {
	padding: 0 15px;
	float: left;
	min-height: 25px;
}

.border_radius_0 {
	border-radius: 0 !important;
}

.span1 {
	width: 10%;
}

.span2 {
	width: 20%;
}

.span3 {
	width: 30%;
}

.span4 {
	width: 40%;
}

.span5 {
	width: 50%;
}

.span6 {
	width: 60%;
}

.span7 {
	width: 70%;
}

.span8 {
	width: 80%;
}

.span9 {
	width: 90%;
}

.span10 {
	width: 100%;
}

.container {
	width: 1200px;
	max-width: 1200px;
}

.section_padding {
	padding: 80px 0 100px;
}

.layout_2_padding {
	padding: 100px 0 80px;
}

.full {
	width: 100%;
	float: left;
	margin: 0;
	padding: 0;
}

.top_80 {
	top: 80px;
}

.vertical-center {
	display: flex;
	align-items: center;
	height: 100%;
	width: 100%;
}

.right_side {
	float: right;
}

.text_align_right {
	text-align: right;
}

.left_side {
	float: left;
}

.text_align_left {
	text-align: left;
}

.text_align_center {
	text-align: center;
}

.center {
	width: 100%;
	display: flex;
	justify-content: center;
}

.modal-backdrop.show {
	opacity: 1;
}

.border_dotted_circle {
	border: dotted #e1e1e1 3px;
	width: 170px;
	height: 170px;
	border-radius: 100%;
	display: flex;
	justify-content: center;
	align-items: center;
	position: relative;
	z-index: 1;
}

.border_dotted_circle:hover,
.border_dotted_circle:focus {
	border: dotted #e1e1e1 3px;
	animation-name: rotate;
	animation-duration: 2s;
	animation-iteration-count: infinite;
	animation-timing-function: linear;
	-webkit-animation-name: rotate;
	-webkit-animation-duration: 2s;
	-webkit-animation-iteration-count: infinite;
	-webkit-animation-timing-function: linear;
	-moz-animation-name: rotate;
	-moz-animation-duration: 2s;
	-moz-animation-iteration-count: infinite;
	-moz-animation-timing-function: linear;
	-ms-animation-name: rotate;
	-ms-animation-duration: 5s;
	-ms-animation-iteration-count: infinite;
	-ms-animation-timing-function: linear;
	-o-animation-name: rotate;
	-o-animation-duration: 2s;
	-o-animation-iteration-count: infinite;
	-o-animation-timing-function: linear;
}

@-webkit-keyframes rotate {
	from {
		-webkit-transform: rotate(0deg);
		-moz-transform: rotate(0deg);
		-ms-transform: rotate(0deg);
		-o-transform: rotate(0deg);
		transform: rotate(0deg);
	}
	to {
		-webkit-transform: rotate(360deg);
		-moz-transform: rotate(360deg);
		-ms-transform: rotate(360deg);
		-o-transform: rotate(360deg);
		transform: rotate(360deg);
	}
}

@-moz-keyframes rotate {
	from {
		-moz-transform: rotate(0deg);
	}
	to {
		-moz-transform: rotate(360deg);
	}
}

.white_fonts p,
.white_fonts h1,
.white_fonts h2,
.white_fonts h3,
.white_fonts h4,
.white_fonts h5,
.white_fonts h6,
.white_fonts ul,
.white_fonts ul li,
.white_fonts ul li a,
.white_fonts ul i,
.white_fonts .post_info i,
.white_fonts div,
.white_fonts a.read_more {
	color: #fff !important;
}

.light_silver_fonts p,
.light_silver_fonts h1,
.light_silver_fonts h2,
.light_silver_fonts h3,
.light_silver_fonts h4,
.light_silver_fonts h5,
.light_silver_fonts h6,
.light_silver_fonts ul,
.light_silver_fonts ul li,
.light_silver_fonts ul li a,
.light_silver_fonts ul i,
.light_silver_fonts .post_info i,
.light_silver_fonts div,
.light_silver_fonts a.read_more {
	color: #ccc !important;
}


/** icon **/

.iconsmind-Over-Time2::before {
	content: "\eb2e";
}

.iconsmind-Money-2::before {
	content: "\eac6";
}

.iconsmind-People-onCloud::before {
	content: "\eb52";
}

.iconsmind-Wallet-2::before {
	content: "\ede5";
}

.iconsmind-Shield::before {
	content: "\ec4f";
}

.iconsmind-Ribbon-2::before {
	content: "\ebf5";
}


/** end icon **/

section.background_bg_bottom {
	background-repeat: repeat-x !important;
	background-position: bottom center !important;
}

.parallax_bg {
	background-repeat: no-repeat;
	background-position: center center;
	background-size: cover;
}

.dark_gray {
	background-color: #111;
	min-height: 400px;
}

.dark_gray.white_fonts h2 {
	color: #17a5e9 !important;
}

.dark_gray.light_silver_fonts h2 {
	color: #fff !important;
}

.list_style_1 {
	font-size: 14px;
	font-weight: 500;
	margin: 20px 0 15px;
}

.list_style_1 i {
	float: left;
	margin: 3px 16px 0 0;
}

.light_silver {
	background: #f8f8f8;
}

.light_silver_2 {
	background: #f8f8f8 !important;
}

.padding-bottom_5 {
	padding-bottom: 50px !important;
}

hr.dottad_border {
	border-top: dotted 3px;
	margin: 80px 0;
}

.margin_bottom_30_all {
	margin-bottom: 30px;
}

.margin_bottom_50_all {
	margin-bottom: 50px;
}

.margin_bottom_20_all {
	margin-bottom: 20px;
}

.margin_bottom_0 {
	margin-bottom: 0px !important;
}

.section {
	float: left;
	width: 100%;
}

.pagination>li.active a {
	color: #fff;
}

.contant_section {
	float: left;
	width: 100%;
}

.blog_feature_img img {
	width: 100%;
}

.main_heading {
	position: relative;
	margin-bottom: 65px;
}

.main_heading::after {
	content: "";
	display: block;
	margin: 20px auto 0;
	width: 80px;
	height: 5px;
	background: #17a5e9;
}

.main_heading.text_align_left::after {
	margin-left: 0;
}

.main_heading.text_align_right::after {
	margin-right: 0;
}

.icon img {
	width: 100px;
}



#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
