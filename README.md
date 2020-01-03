# bc-homework-1
Extension bootcamp homework 1

This example portoflio was designed according to project specs given out as a homework assignment. Below are the CSS techniques I utilized in my layout. 

Header:
I used floats to move the title to the left and the navbar to the right. I then used flexbox to horizontally align the navbar links. I utilized the psuedoclass :hover to emphasize the navbar links upon hover.

Portfolio: 
Initially I used flexbox with a wrap to layout the images in 
the portfolio but after learning CSS grid I decided to use 
that instead. For the banners across each image card I used divs with paragraphs at the start. Later I switched these to pseudo elements to avoid unecessary markup. 

Contact Form:
I didn't like the look of the blue outline on the inputs on focus so I used to :focus pseudoclass to change it to a border. 

Footer:
To ensure that the body took up at least the entire screen, I set the min-height to 100vh. To make the footer sticky I put a display: flex; on the body with a flex-direction: column;. I then set margin-top on the footer to auto to ensure that it stayed at the bottom. 

