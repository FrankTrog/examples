This code example is for the Google Sticky Footer.

Basic Explanation
The Sticky Footer relies on setting the html, body and a main container to height 100% and then subtracting the footers height from the main container and adding the height back to the last container within the main container. In this example #wrapper is the main container.

Steps
1. Ensure there is a main container holding all content except footer.
2. Ensure footer exists and is in body element under main container.
3. Set html/body to height 100%
4. Set following properties for main container.
  a. min-height:100%;
  b. height: auto !important;
  c. height: 100%;
  d. margin-bottom: -41px; /* 41 px is the height of our footer */
5. Set footer height.
6. Add padding to bottom of last container within main container equal to height of the footer.

Youtube Video Explanation
https://www.youtube.com/watch?v=AauSut346lM

Resources
https://code.google.com/p/cleanstickyfooter/