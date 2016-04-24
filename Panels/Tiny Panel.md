![enter image description here](http://i.imgur.com/Hwyg2fa.gif)

If you want the sidepanel occupying less space (as seen above), use the following code:

    #panels-container{
    	position:absolute !important;
    	top: 0px !important;
    	z-index: 100 !important;
    	overflow:hidden !important;
    	height: 34px !important;
    	-webkit-transition: height 250ms, width 250ms  !important;
    	display:block !important;
    }
    
    .toolbar{
    	Margin-left: 30px !important;
    }
    
    #panels-container:hover{
    	bottom: -34px !important;
    	-webkit-transition: height 250ms, opacity 250ms !important;
    	opacity: 1 !important;
    	height:300px !important;
    }
    
    /* replace favicons 
    
    
    .trash{
    	display:none !important;
    	background: url("./mail3.png") center no-repeat, url("./tv.png") center no-repeat, url("./notebook.png") center no-repeat !important;
    }
    
    .webviewbtn[title="Gmail\a http://m.gmail.com"]{
    background-image: url("mail3.png") !important;
    background-repeat:  no-repeat !important;
    background-position:  center !important;
    }
    
    .webviewbtn[title="tvcountdown.com\a http://tvcountdown.com"]{
    background-image: url("tv.png") !important;
    background-repeat:  no-repeat !important;
    background-position:  center !important;
    }
    
    .webviewbtn[title="Google Keep\a https://keep.google.com"]{
    background-image: url("notebook.png")!important;
    background-repeat:  no-repeat !important;
    background-position:  center !important;
    }
    
    .webviewbtn[title="Gmail\a http://m.gmail.com"] img, .webviewbtn[title="tvcountdown.com\a http://tvcountdown.com"] img, .webviewbtn[title="Google Keep\a https://keep.google.com"] img{	
    display:none;
    }
    
    .webviewbtn img{
    	border:0!important;
    	background: none !important;
    	background-color: none !important;
    	border-image-width:0 !important;
    }
    */

***Author:*** [ProteinPankkaka](https://www.reddit.com/user/ProteinPannkaka)
***Source:*** https://www.reddit.com/r/vivaldibrowser/comments/4g7tz9/tiny_panel_custom_css/
