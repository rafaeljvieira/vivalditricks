![enter image description here](http://i.imgur.com/3EMH13C.png)

If you want to try it out for yourself, save the css code below as tabs.css in C:\Users\<youraccount>\AppData\Local\Vivaldi\Application\1.0.83.38\resources\vivaldi\style
(where common.css is also located)

    #tabs .tab .tab-header {
      display: flex;
      min-height: 30px;
      flex: 0;
      position: absolute;
      top:0;
      left:0;
      right:0;
      z-index:1;
    }
    
    #tabs .tab {
      color:#000;
      text-shadow:0 0 1px #fff,0 0 4px #fff,0 0 5px #fff, 0 0 7px #fff,0 0 9px #fff,0 0 9px #fff,0 0 11px #fff,0 0 11px #fff; 
      border:1px solid #aaa;
      background-color: transparent!important;
      background-image: transparent!important;
      font-weight:500;
    }
    
    #tabs .tab.active {  
      color: #000;
      border:1px solid #000!important;
      z-index: 2;
      font-weight:700;
    }
    #tabs .tab .tab-thumb {
      flex: 1;
      background-size: 100% auto;
      background-repeat: no-repeat;
      background-position: 0 0;
      margin-left: 0px;
      margin-right: 0px;
      z-index:0;
    }
    
    #tabs .tab:not(.active) .tab-thumb {
      -webkit-filter: blur(1px)!important;
    }
    
    #tabs .tab.active .tab-thumb {
      -webkit-filter: contrast(110%) brightness(110%)!important;
    }
    #tabs .tab .tab-header .title {
    	padding:2px 3px;
    }
    #tabs .tab.active .tab-header .title {
    	background:rgba(255,255,255,0.9);	
    	box-shadow:0 0 5px rgba(255,255,255,1);	
    }
    
    #tabs .tab:not(.active) {
      background-color: #transparent!important;
      color: #000;
    }
    
    #tabs .tab:not(.active):hover {
      background-color: #transparent!important;
    }
    
    #tabs .tab:not(.active):active {
      background-color: #transparent!important;
    }

Open browser.html in resources\vivaldi and insert below

    <link rel="stylesheet" href="style/common.css" />

this line:

    <link rel="stylesheet" href="style/tabs.css" />

If you want to revert the changes, you can simply remove this line again.
Now (re)start vivaldi.

***Author:*** [AlexRuppert](https://vivaldi.net/easysocial-dashboard/profile/24494)

***Source:*** https://vivaldi.net/forum/all/1368-some-experimentation-with-tab-thumbnails-skin-customization
