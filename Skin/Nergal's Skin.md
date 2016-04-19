The background color of the tabs is the windows theme color - static
Not active tab font color set to white
Added white separator between tabs
On hover the tab background is white with opacity
Trash, new tab and window buttons also changed to white
Vivadi button is red and bigger
The color of the private window is a bit darker


    /* CHROME */
    .ui-light.color-behind-tabs-off.ui-tabcolor-off#browser.ui-light #header{background:hsl(206,67%,48%);padding-top:2px;}
    .private.ui-light.color-behind-tabs-off.ui-tabcolor-off#browser.ui-light #header{background:hsl(206,67%,30%);}
    .tabs-at-edge.maximized#browser.win.win10.tabs-top #header #titlebar .window-buttongroup button{height: 32px;fill:#fff;}
    /* TABS */
    .ui-light.ui-tabcolor-off .tab-position .tab:hover:not(.active){background-color:rgba(255,255,255,.7);box-shadow:none;}
    .ui-light.ui-tabcolor-off.color-behind-tabs-off .tab-position .tab{background-color: hsla(0,0%,100%,0.0);}
    .tab-position .tab.active{border-top-right-radius:4px;border-top-left-radius:4px;}
    .tab-position .tab.active .tab-header .favicon{background-color:transparent;box-shadow:none;}
    .tab-position .tab:not(.active) .title{color: #fff;}
    .tab-position:first-child .tab{border-left:1px solid rgba(255,255,255,0.1);}
    .tab-position .tab{border-right:1px solid rgba(255,255,255,0.1);}
    /* NEW TAB, TRASH */
    #tabs-container .newtab svg, #tabs-container .toggle-trash svg{fill:#fff;}
    /* SPEEDDIAL */
    .speeddial .dial .dial-image{height:125px;}
    .speeddial .dial{height:126px;}
    .dials .dial:hover{height:132px;}
    .speeddial.cols6 .dial:nth-of-type(1n+7){top:200px;}
    .speeddial.cols5 .dial:nth-of-type(1n+6){top:200px;}
    .speeddial.cols4 .dial:nth-of-type(1n+5){top:200px;}
    .speeddial.cols3 .dial:nth-of-type(1n+4){top:200px;}
    .speeddial.cols3 .dial:nth-of-type(1n+7){top:400px;}
    .speeddial.cols3 .dial:nth-of-type(1n+10){top:600px;}
    .speeddial.cols2 .dial:nth-of-type(1n+3){top:200px;}
    .speeddial.cols2 .dial:nth-of-type(1n+5){top:400px;}
    .speeddial.cols2 .dial:nth-of-type(1n+7){top:600px;}
    .speeddial.cols1 .dial:nth-of-type(1n+2){top:200px;}
    .speeddial.cols1 .dial:nth-of-type(1n+3){top:400px;}
    .speeddial.cols1 .dial:nth-of-type(1n+4){top:600px;}
    .speeddial.cols1 .dial:nth-of-type(1n+5){top:800px;}
    .speeddial.cols1 .dial:nth-of-type(1n+6){top:1000px;}
    .speeddial.cols1 .dial:nth-of-type(1n+7){top:1200px;}
    /* SIDEPANEL */
    #panels-container{position:absolute;top:34px;bottom:0;left:0;z-index:4;}
    .normal #main>.inner, .maximized #main>.inner{padding-left:34px;}
    /* LOGO */
    .vivaldi svg rect[id^=vivrect]{opacity: 0;}
    .vivaldi svg path{fill:#F33;}
    #browser.tabs-top .vivaldi svg{margin-left:-3px;margin-top:-6px;width:40px;height:40px;}

***Author:*** [Nergal11](https://vivaldi.net/en-US/easysocial-dashboard/profile/74894)

***Source:*** https://vivaldi.net/en-US/forum/all/3073-vivaldi-ui-customisations?start=300#50104
