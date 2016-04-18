**Author:** [An_dz](https://vivaldi.net/en-US/easysocial-dashboard/profile/15939)

**Source:** https://vivaldi.net/en-US/forum/all/3073-vivaldi-ui-customisations#24533

Here's how you can set a maximum of Speed Dial thumbs. Vivaldi maximum number is 6 right now.

Since the CSS must be different for each number of columns, I'll try to explain how to adapt the strips for the number you want.
In all strips C is number of columns you want. J may be read kind like C! it must start as 1 and end as C, it's like a for().

The selectors, which are the first line of the strips, must remove the numbers from C and below. For example, if you want C=3 you should remove **.speeddial.cols2**, **.speeddial.cols3** in the first strip, and this should follow on all strips.

Whatever inside brackets {} should become a number without brackets, so {220+[250*(C-1)} for C=2 must be 470.

This sets the width of the holder of the dials:

    .speeddial.cols2, .speeddial.cols3, .speeddial.cols4, .speeddial.cols5, .speeddial.cols6 {
    	width: {220+[250*(C-1)]}px !important;
    }

This is to set the left position of the dials, you should do this for each J, so if you want three columns you should add this strip for J=1, J=2 and J=3. For programmers read this as for(int J=1; J<=C; J++)

    .speeddial.cols2 .dial:nth-of-type({C}n+{J}), .speeddial.cols3 .dial:nth-of-type({C}n+{J}), .speeddial.cols4 .dial:nth-of-type({C}n+{J}), .speeddial.cols5 .dial:nth-of-type({C}n+{J}), .speeddial.cols6 .dial:nth-of-type({C}n+{J}) {
    	left: {0+(250*J)}px !important;
    }

This is to set the top position of the dials, again do for every J, but here you might want to go slightly more, add as much as needed until all lines are ok. Remember J starts as 1.

    .speeddial.cols2 .dial:nth-of-type({C}n+{(C*J)+1}), .speeddial.cols3 .dial:nth-of-type({C}n+{(C*J)+1}), .speeddial.cols4 .dial:nth-of-type({C}n+{(C*J)+1}), .speeddial.cols5 .dial:nth-of-type({C}n+{(C*J)+1}), .speeddial.cols6 .dial:nth-of-type({C}n+{(C*J)+1}) {
    	top: {240*J}px !important;
    }
