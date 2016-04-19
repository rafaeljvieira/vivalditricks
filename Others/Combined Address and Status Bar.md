![enter image description here](https://i.imgur.com/bZQHd7z.png)

To have a combined address and status bar, as seen above:

    /* hide panel toggle */
    .paneltogglefooter {display: none !important;}
    
    /* statusbar inside toolbar */
    .addressfield {margin-right: 325px !important;}
    #footer {
        position: absolute;
        right: 7px;
        bottom: 7px;
        width: 325px;}
    .callout:before, .callout:after {display: none !important;}
    
    /* status_info inside addressfield */
    #footer #status_info {display: block !important;}
    #footer #status_info span{
        bottom: 1px !important;
        left: 26px !important;
        margin: 7px !important;
        width: 925px !important;
        font-size: 15px !important;
        font-weight: 500 !important;
        color: #f1f1f1 !important;
        background-color: #454545 !important;
        border: 0 !important;
        overflow: hidden !important;
        white-space: nowrap !important;
        text-overflow: ellipsis !important;
        position: fixed !important;
        z-index: 50 !important;}
    #footer #status_info span:empty {display: none !important;}

***Author:*** [gh0st](https://vivaldi.net/en-US/easysocial-dashboard/profile/18619)

***Source:*** https://vivaldi.net/en-US/forum/all/3073-vivaldi-ui-customisations?start=180#36999
