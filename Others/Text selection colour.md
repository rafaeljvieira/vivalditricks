You can, for example, change the colour of the selection in any text box, like the address and search boxes:

    ::selection {
      background-color: #464646;
      color: white;
    }

And if you want to make it use the same background-color of the coloured tab option, you also add this to your custom.css:

    .is-mail ::selection, .is-startpage ::selection {
    	background-color: #ef3939 !important
    }
    .isblurred:not(.linux) ::selection {
    	background-color: #b3b3b3 !important
    }

And add this in the bundle.js:

Search for:

    var i=t+"-"+n+" {"+n+":"+e+"!important;}\n";

And replace with:

    var i=t+"-"+n+" {"+n+":"+e+"!important;}\n";if(n==="background-color")y.insertRule("::selection{"+n+":"+e+"}", 0);