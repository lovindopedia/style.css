# style.css
audio:not([controls]) { display: none; height: 0px; }
html { font-size: 100%; }
html, button, input, select, textarea { font-family: sans-serif; }
body { margin: 0px; }
a:focus { outline: thin dotted; }
a:active, a:hover { outline: 0px none; }
p, pre { margin: 1em 0px; }
dl, menu, ol, ul { margin: 1em 0px; }
menu, ol, ul { padding: 0px 0px 0px 40px; }
img { border: 0px none; }
svg:not(:root) { overflow: hidden; }
button::-moz-focus-inner, input::-moz-focus-inner { border: 0px none; padding: 0px; }

html, button, input, select, textarea { color: rgb(34, 34, 34); }
body { font-size: 1em; line-height: 1.4; }
*::-moz-selection { background: none repeat scroll 0% 0% rgb(179, 212, 252); text-shadow: none; }
img { vertical-align: middle; }
body { font: 16px/26px Helvetica,Helvetica Neue,Arial; background: none repeat scroll 0% 0% #EFEFEF; margin-top: 10px }

.wrapper { margin: 0px auto; position: relative; width: 320px; padding: 0px 0px 100px; }
.wrapper:after { clear: both; content: ""; display: block; }
.left { float: none; width: 320px; text-align: center; }
.right { float: none; width: 320px; }
.girl img { border: 5px solid rgb(255, 255, 255); box-shadow: 0px 0px 7px rgb(183, 180, 180); height: 303px; margin: 10px auto 5px; position: relative; width: 202px; }
.content { padding: 17px 0px 0px; }

h1 { color: rgb(122, 122, 122); font-size: 28px; font-weight: normal; line-height: 28px; text-align: center; margin: 10px 0; }
h2 { color: rgb(191, 0, 0); font-size: 22px; font-weight: bold; line-height: 23px; margin: 0px; text-align: center;}
h2 span { color: rgb(0, 0, 0); font-size: 20px; font-weight: normal; line-height: 19px; }
h3 {color: rgb(191, 0, 0); font-size: 22px; font-weight: bold; line-height: 23px; margin: 10px 0; text-align: center;}
h3 span { color: rgb(0, 0, 0); font-size: 20px; font-weight: normal; line-height: 19px; }

.content p { color: rgb(0, 0, 0); font-size: 16px; line-height: 23px; padding: 8px 0px 5px; margin: 0px; }
.question {font-weight: bold;}
.step1, .step2, .step3 {text-align: center;}
.step1 h2, .step2 h2, .step3 h2 { padding: 12px 0px; }
.step1 h2 { padding: 12px 0px 60px; }
.step2 h2 { padding: 12px 0px 45px; }
.step3 h2 { padding: 12px 0px; }
.step3 h2 span { line-height: 29px; }

.done_marker { list-style: none outside none; }
.done_marker li { background: transparent url(../img/check.png) no-repeat scroll left center; color: rgb(89, 89, 89); font-family: trebuchet ms,tahoma; font-size: 15px; line-height: 17px; padding: 6px 5px 6px 30px; }
.step_button, .agree { background: linear-gradient(to bottom, rgb(172, 172, 172) 0%, rgb(127, 124, 124) 100%) repeat scroll 0% 0% transparent; border: 0px none; color: rgb(255, 255, 255); cursor: pointer; display: inline-block; font-family: trebuchet ms,tahoma; font-size: 36px; height: 70px; line-height: 70px; outline: 0px none; text-align: center; text-decoration: none; width: 300px; }
.step_button_2 { margin: 10px 0px 0px; }
.show_end .agree, .step_button:hover { background: linear-gradient(to bottom, rgb(73, 194, 1) 0%, rgb(36, 150, 0) 100%) repeat scroll 0% 0% transparent; }
.step2 { display: none; }
.step4 .agree_label { color: rgb(126, 126, 126); font-size: 11px; line-height: 14px; padding: 5px 0px 14px; text-align: center; }
.agree { background-position: 0px -140px; }
.agree:hover, .agree:active { background-position: 0px -210px; }
.show_end { display: none; }
@media only screen and (min-width: 480px) {
	.wrapper { margin: 0px auto; position: relative; width: 480px; padding: 0px 0px 100px; }
	.left { float: none; width: 460px; }
	.right { float: none; width: 460px; }
}
@media only screen and (min-width: 768px) {
	.wrapper { margin: 0px auto; position: relative; width: 1000px; padding: 0px 0px 100px; }
	.left { float: left; width: 500px; }
	.right { float: right; width: 500px; }
	.girl img { border: 10px solid rgb(255, 255, 255); box-shadow: 0px 0px 7px rgb(183, 180, 180); height: 607px; margin: 20px 10px 9px 0px; position: relative; width: 404px; }
	h1 { color: rgb(122, 122, 122); font-size: 38px; font-weight: normal; line-height: 48px; text-align: center; text-transform: uppercase; margin: 0px; }
	h2 { color: rgb(191, 0, 0); font-size: 35px; font-weight: bold; line-height: 47px; margin: 0px; }
	h2 span { color: rgb(0, 0, 0); font-family: trebuchet ms,tahoma; font-size: 27px; font-weight: normal; line-height: 19px; }
	.step_button, .agree, select.select_age { width: 500px; }
}
@media only screen and (min-width: 1140px) {
}

