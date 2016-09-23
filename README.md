#jquery-overlay
{
	position: absolute;
	top: 0;
	left: 0;
	z-index: 90;
	width: 100%;
	height: 500px;
}
#jquery-lightbox
{
	position: absolute;
	top: 0;
	left: 0;
	width: 100%;
	z-index: 100;
	text-align: center;
	line-height: 0;
}
#jquery-lightbox a img
{
	border: none;
}
#lightbox-container-image-box-top
{
	width: 100%;
}
#lightbox-container-image-box-top-left
{
	width: 10%;
	height: 1px;
	position: relative;
	margin: 0 auto;
	float: left;
	z-index: 10;
	display: inline;
	text-align: left;
}
#lightbox-container-image-box-top-middle
{
	width: 80%;
	padding-top: 5px;
	height: 5px;
	position: relative;
	margin: 0 auto 0 0px;
	float: left;
	z-index: 5;
	display: inline;
}
#lightbox-container-image-box-top-middle div.progress
{
	width: 80%;
	padding-top: 5px;
	height: 5px;
	position: relative;
	margin: 0 auto 0 0px;
	float: left;
	background-color: #e4e4e4;
	z-index: 5;
	display: inline;
}
#lightbox-container-image-box-top-right
{
	width: 10%;
	height: 1px;
	position: relative;
	margin: 0 auto;
	float: right;
	text-align: right;
	z-index: 10;
	display: inline;
}
#lightbox-container-image-box
{
	position: relative;
	background-color: #fff;
	width: 250px;
	height: 250px;
	margin: 0 auto;
}
#lightbox-container-image
{
	height: 100%;
	padding: 10px;
}
#lightbox-loading
{
	position: absolute;
	top: 40%;
	left: 0%;
	height: 25%;
	width: 100%;
	text-align: center;
	line-height: 0;
}
#lightbox-nav
{
	position: absolute;
	top: 32px;
	left: 0;
	height: 100%;
	width: 100%;
	z-index: 10;
}
#lightbox-container-image-box > #lightbox-nav
{
	left: 0;
}
#lightbox-nav a
{
	outline: none;
}
#lightbox-nav-btnPrev, #lightbox-nav-btnNext
{
	width: 49%;
	height: 100%;
	zoom: 1;
	display: block;
}
#lightbox-nav-btnPrev
{
	left: 0;
	float: left;
}
#lightbox-nav-btnNext
{
	right: 0;
	float: right;
}
#lightbox-container-image-data-box
{
	font: 10px Verdana, Helvetica, sans-serif;
	background-color: #fff;
	margin: 0 auto;
	line-height: 1.4em;
	overflow: auto;
	width: 100%;
	padding: 0 10px 0;
	text-align: left;
}
#lightbox-container-image-data #lightbox-image-details
{
	width: 70%;
	float: left;
	text-align: left;
}
#lightbox-image-details-caption
{
	font-weight: bold;
	display: block;
	height: 25px;
	line-height: 25px;
	vertical-align: middle;
}
#lightbox-image-details-currentNumber
{
	display: block;
	clear: left;
	padding-bottom: 1.0em;
	display: inline;
	height: 16px;
	line-height: 16px;
	vertical-align: middle;
}
#lightbox-image-details-previous-image, #lightbox-image-details-previous-text, #lightbox-image-details-next-image, #lightbox-image-details-next-text
{
	display: inline;
	height: 25px;
	line-height: 25px;
	vertical-align: middle;
	cursor: pointer;
	cursor: hand;
}
