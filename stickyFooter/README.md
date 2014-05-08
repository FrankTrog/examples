This code example is for the Google Sticky Footer.

Basic Explanation
The Sticky Footer relies on setting the html, body and a main container to height 100% and then subtracting the footers height from the main container and adding the height back to the last container within the main container. In this example #wrapper is the main container.

Steps
<ol>
    <li>Ensure there is a main container holding all content except footer.</li>
    <li>Ensure footer exists and is in body element under main container.</li>
    <li>Set html/body to height 100%</li>
    <li>Set following properties for main container.
        <ul>
            <li>min-height:100%;</li>
            <li>height: auto !important;</li>
            <li>height: 100%;</li>
            <li>margin-bottom: -41px; /* 41 px is the height of our footer */</li>
        </ul>
    </li>
    <li>Set footer height.</li>
    <li>Add padding to bottom of last container within main container equal to height of the footer.</li>
</ol>

Youtube Video Explanation
https://www.youtube.com/watch?v=AauSut346lM

Resources
https://code.google.com/p/cleanstickyfooter/