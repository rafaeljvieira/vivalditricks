A Chrome-like status bar. It only works if Vivaldi's native status bar is disabled.

    #footer.disabled{
    	display:block !important;
    	position:static !important;
    	padding:0 !important;
    	height:0 !important;
    	width:0 !important;
    }
    
    #footer.disabled > *{
    	display:none !important;
    }
    #footer.disabled #status_info{
    	display:block !important;
    }
    
    #footer.disabled #status_info span{
    	position:fixed !important;
    	bottom:0 !important;
    	left:0 !important;
    	margin:0 !important;
    	color:#333 !important;
    	background-color:#FEFEFE !important;
    	padding:2px 5px !important;
    	border:#9E9E9E solid 0 !important;
    	border-width:1px 1px 0 0 !important;
    	max-width:50% !important;
    	overflow: hidden !important;
    	white-space: nowrap !important;
    	text-overflow: ellipsis !important;
    	z-index:50 !important;
    }
    
    #footer.disabled #status_info span:empty{
    	display:none !important;
    }
    
***Author:*** [kotoro](https://vivaldi.net/en-US/easysocial-dashboard/profile/46634)

***Source:*** https://vivaldi.net/en-US/forum/all/3073-vivaldi-ui-customisations?start=100#28369
