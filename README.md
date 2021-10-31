# gisborne-child-digiphil
Child theme repo for Gisborne at DigiPhil



Additional Custom CSS for the theme editor:

/*Hide Top Bar */
.top-bar-area{display: none;}

/* Footer - to fit on lower size screens*/

.footer-area .container .row {
	    margin-right: -25px;
    margin-left: -25px;
}

/* Counter on front page*/

.fact-counter-area .fact-counter {
    background: #2f2f2f;
    width: 50%;
    height: 249px;
    float: left;
}

.fact-counter-area .fact-counter.right {
    background: #3a3a3a;
    position: relative;
}


/*Header szöveg*/
.breadcrumb-area .breadcrumbs h1 {
    color: #ffffff;
    font-size: 42px;
    font-weight: 500;
    line-height: 60px;
    text-transform: none;
    text-align: center;
}

/*Header image*/

.breadcrumb-area {
background-image: url(http://digiphil.dev.peterteszary.com/wp-content/uploads/2021/10/digi-phil-header-green.png)!important;
}

/*mobile-menu*/
/*border*/

.main-menu .navbar-collapse > .navigation > li > ul > li > ul > li{
	border-top: 1px solid #000000 !important;}
	 
.main-menu .navbar-collapse > .navigation > li:last-child,
.main-menu .navbar-collapse > .navigation > li > ul > li:last-child,
.main-menu .navbar-collapse > .navigation > li > ul > li > ul > li:last-child{
	border-top: 1px solid #000000 !important;}


/*footer*/

.footer-area {
    background: #000000;
    padding-top: 80px;
    padding-bottom: 120px;
    padding-left: 25px!important;
    padding-right: 25px!important;
}


.add-comment-box {
	display: none;
}

/*Hírek*/
.col-md-4 {
	height: 500px;
	margin-bottom: 100px;
}

/*kutatók*/

.team-area .single-team-member {
    margin-bottom: 35px;
    display: block;
    height: 400px!important;
}

/*partnerek carusel nyíl*/
.testimonial-carousel .owl-nav .owl-prev:hover, .owl-carousel .owl-nav .owl-next:hover {
	background: transparent;}

.main-menu .navbar-collapse > .navigation > li:last-child, .main-menu .navbar-collapse > .navigation > li > ul > li:last-child, .main-menu .navbar-collapse > .navigation > li > ul > li > ul > li:last-child {
    border-top: 0px!important;
}

.kc-flip-container .flipper {
    
    height: 210px;
   
}
