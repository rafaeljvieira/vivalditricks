To hide the address bar:

    .toolbar-addressbar {
    	visibility: hidden;
    	position: fixed;
    	width: 100%;
    	opacity: 0;
    	z-index: 2;
    	transition: opacity .3s linear .7s, visibility 0s linear 1s;
    }
    #header:hover ~ #main .toolbar-addressbar, .toolbar-addressbar:hover {
    	visibility: visible;
    	opacity: 1;
    	transition-delay: 0s;
    }

***Author:*** [hekel](https://vivaldi.net/en-US/easysocial-dashboard/profile/72659)

***Source:*** https://vivaldi.net/en-US/forum/all/3073-vivaldi-ui-customisations?start=300#50208
