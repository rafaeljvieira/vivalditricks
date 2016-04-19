![enter image description here](http://i.imgur.com/pHMh9ZB.png)
![enter image description here](http://i.imgur.com/Gyv92Uk.png)

It's a nice prank, but I wouldn't use it to browse the web (unless you are a masochist):

    @keyframes viv {
    0% { transform: translate(20px, 10px) rotate(20deg); }
    10% { transform: translate(-10px, -20px) rotate(-20deg); }
    20% { transform: translate(-30px, 0px) rotate(20deg); }
    30% { transform: translate(0px, 20px) rotate(0deg); }
    40% { transform: translate(10px, -10px) rotate(20deg); }
    50% { transform: translate(-10px, 20px) rotate(-20deg); }
    60% { transform: translate(-30px, 10px) rotate(0deg); }
    70% { transform: translate(20px, 10px) rotate(-20deg); }
    80% { transform: translate(-10px, -10px) rotate(20deg); }
    90% { transform: translate(20px, 20px) rotate(0deg); }
    100% { transform: translate(-20px, -10px) rotate(-20deg); }
    }
    body {
    animation-name: viv;
    animation-duration: 5s;
    transform-origin: 175% 175%;
    animation-iteration-count: infinite;
    animation-timing-function: linear;
    }

***Author:*** [Doomer](https://vivaldi.net/en-US/easysocial-dashboard/profile/60389)

***Source:*** https://vivaldi.net/en-US/forum/all/3073-vivaldi-ui-customisations?start=180#38776
