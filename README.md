# react-logo
 A freecodecamp.org CSS practice tutorial, create the REACT.JS logo

Practice CSS by following a tutorial from freecodecamp.org
tutorial link: https://www.freecodecamp.org/news/learn-css-create-the-react-logo/

1 / 18 / 2023

1st
    - Created starter files for the project index.html and style.css

    - index.html
        : created an html 5 starter code
        : link the external css to style.css
    
    - style.css
        : added the general styling
___________________________________________________

2nd
    - index.html
        : added div containers for different parts of the logo
        : .ball 
        : .ellipse and .ellipse1-3

___________________________________________________

3rd 
    - style.css
        : added styling for the center ball of the logo

___________________________________________________

4th
    - style.css
        : created the ellipses for the logo
        : added styling for .ellipse and .ellipse1-3

___________________________________________________

5th and Last

    - style.css
        : added styling for ellipses to rotate

<-- End -->

Things I learned: 

    - position: absolute;
        : element will be removed from the web page's normal flow
        : it will first find another 'position'ed parent (must be non-static), if none are found then it will follow the viewport
            "thank you Bro Code"
            https://www.youtube.com/watch?v=Pp7UXS3P6jY

    - vw (viewport width) and vh (viewport height)
        : vw will set an elements's size to 1% of the viewport's width
            ex. 20vw = 20% of the viewports vwidth
        : vh will set an elements's size to 1% of the viewport's height
            ex. 80vh = 80% of the viewports height
    
    - viewport
        : it is the user's visible screen of the web page
            "thank you w3schools" 
            https://www.w3schools.com/css/css_rwd_viewport.asp

    - @keyframes animationname {
        from: {}
        to: {}
    }
        : to use the animation = animation: name duration timing-function delay iteration
        : a neat css trick to create animations