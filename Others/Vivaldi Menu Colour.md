This will give you a grey box with a white V:

    .vivaldi {
        -webkit-filter: grayscale(100%) !important;
    }

You can also darken the grey by adjusting brightness:

    .vivaldi {
        -webkit-filter: grayscale(100%) brightness(50%) !important;
    }
    
You can choose other colours, like sepia:

    .vivaldi {
        -webkit-filter: sepia(100%) hue-rotate(24deg) saturate(9) brightness(90%) !important;
    }
    
Furthermore, you can use a transparent rectangle:

    .vivaldi svg rect[id^=vivrect] {
    	opacity: 0;
    }

And colour the V:

    .vivaldi svg path {
    	fill:#F33;
    }

***Author:*** sjudenim & [hekel](https://vivaldi.net/en-US/easysocial-dashboard/profile/72659)

***Source:*** https://vivaldi.net/en-US/forum/all/3073-vivaldi-ui-customisations?start=260#46081; https://vivaldi.net/en-US/forum/all/3073-vivaldi-ui-customisations?start=280#49378
