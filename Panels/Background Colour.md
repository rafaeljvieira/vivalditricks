To change the background colour of the webpanels to dark (you can edit the colour code):

1) Find

    #switch .webpanelsgroup button.webviewbtn,#switch .webpanelsgroup button.webviewbtn:active,#switch .webpanelsgroup button.webviewbtn:hover{background-color:#fff!important}

in the common.css

2) Remove

    !important

3) Open custom.css

4) Add this

    button.webviewbtn {
        background-color: #373737 !important;
    }

***Author:*** [Tiamarth](https://vivaldi.net/en-US/easysocial-dashboard/profile/16277)
***Source:*** https://vivaldi.net/en-US/forum/all/3073-vivaldi-ui-customisations?start=160#33290
