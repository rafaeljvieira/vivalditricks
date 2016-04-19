To have your tabs numbered:

    #tabs-container {  counter-reset: tab; }
    #tabs-container .tab .tab-header .title:before {
     counter-increment:tab;
      content:counter(tab);
      padding:0 6px 0 0;
      font-weight:bold;
    }

***Author:*** [gaspar_schott](https://vivaldi.net/en-US/easysocial-dashboard/profile/51289)

***Source:*** https://vivaldi.net/en-US/forum/all/3073-vivaldi-ui-customisations?start=160#33719
