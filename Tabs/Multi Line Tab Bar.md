In order to have a multi-line tab bar like in Opera Presto:

    #tabs-container.top #tabs, #tabs-container.bottom #tabs {
      height: auto !important;
      display: block !important;
    }
    #tabs-container.bottom #tabs .tab, #tabs-container.top #tabs .tab {
      max-width: 150px !important;
      min-width: 150px;
      display: inline-block !important;
      float: left;
    }
    #tabs .tab .tab-thumb {
      display: none;
    }
    #tabs .newtab {
      margin-top: -9px; 
    }
    #tabs .trash {
      display: inline-block !important;
      float: right;
    }

***Author:*** [An_dz](https://vivaldi.net/en-US/easysocial-dashboard/profile/15939)
***Source:*** https://vivaldi.net/en-US/forum/all/3073-vivaldi-ui-customisations?start=40#25337
