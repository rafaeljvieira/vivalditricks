To hide the panels:

    #panels-container {
    	position: fixed;
    	height: 100%;
    	max-width: 0vw;
    	opacity: 0;
    	z-index: 1;
    	transition: max-width .5s cubic-bezier(0.18, 0.89, 0.32, 1.28), opacity .2s linear .2s;
    }
    #panels-container:hover {
    	max-width: 99vw;
    	opacity: 1;
    	transition-delay: 0s;
    }

***Author:*** [hekel](https://vivaldi.net/en-US/easysocial-dashboard/profile/72659)

***Source:*** https://vivaldi.net/en-US/forum/all/3073-vivaldi-ui-customisations?start=300#50208
