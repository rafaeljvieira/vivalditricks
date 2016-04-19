![enter image description here](http://s20.postimg.org/y9bdl9op9/screenshot.jpg)

To have Vivaldi show full-width tabs on bottom and the status bar on top (as seen above):

    /*    Stretch tabs width    */
    #tabs-container.bottom #tabs .tab, #tabs-container.top #tabs .tab {
    	width: 100% !important;
    	max-width: 100% !important;
    }
    
    /*    Change how full screen info bubble looked    */
    .fullscreeninfobubble {
    	left: 0% !important;
    	width: 100% !important;
    	top: 48% !important;
    	background-color: rgba(239, 57, 57, 1) !important;
    	border-radius: 0px !important;
    	border-width: 0px !important;
    	transition: opacity .3s, visibility .3s !important;
    }
    .fullscreeninfobubble.show {
    	opacity: 1 !important;
    	visibility: visible !important;
    	transition: opacity .3s, visibility .3s !important;
    }
    
    /*    Remove close tab button    */
    #tabs .tab .tab-header .close {
    	display: none !important;
    }
    
    /*    Grayscale inactive tabs (Credit goes to widget)    */
    #tabs .tab:not(.active){
    	-webkit-filter: grayscale(1);
    }
    
    /*    Put the status bar on top    */
    #footer {
    	border-bottom: 1px solid #dbdbdb;
    	position: absolute;
    	top: 59px;
    	width: 100%;
    	z-index: 0 !important;
    }
    .normal #main>.inner, .maximized #main>

***Author:*** [ekydetik](https://vivaldi.net/en-US/easysocial-dashboard/profile/20833)

***Source:*** https://vivaldi.net/en-US/forum/all/3073-vivaldi-ui-customisations?start=60#26795
