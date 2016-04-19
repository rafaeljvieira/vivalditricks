![enter image description here](https://vivaldi.net/media/kunena/attachments/25229/roundedtabs.png)

To use a rounded address bar

   

     /****[Address Bar]****/
    .addressfield, .searchfield {
    	margin: 5px;
    	height: 24px;
    	border: 1px solid;
    }
    .addressfield, .searchfield, .addressfield:after, .searchfield:after {
    	border-radius: 4px;
    }
    .addressfield .addressfield-siteinfo, .addressfield .addressfield-siteinfo:before {
    	/**[round the site-info/ssl button]**/
    	border-radius: 3px 0 0 3px;
    }
    .addressfield form input.url {
    	box-shadow: none;
    }

***Author:*** [Hekel](https://vivaldi.net/en-US/easysocial-dashboard/profile/72659)

***Source:*** https://vivaldi.net/en-US/forum/all/3073-vivaldi-ui-customisations?start=320#55305
