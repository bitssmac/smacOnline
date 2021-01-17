# Blog Home html:
* add a slide
* add a pagination icon

# adding images to slideshow:
* add the images to custom.js inside the folder of that blog, not custom.js in home directory js folder. For Example:
```html

$(document).ready(function() {

  /* Home Slideshow Vegas
  -----------------------------------------------*/
  $(function() {
    $('body').vegas({
        slides: [
            { src: 'images/slides/slide-1.jpg' },
            { src: 'images/slides/slide-2.jfif' },
            { src: 'images/slides/slide-3.jpg' }
        ],
        timer: false,
        transition: [ 'zoomOut', ]
    });
  });
  ```

  note: the relative address specified is the relative address wrt the blog html file, not the js file.


  # blog html page
  * add the title and subtitle in the home-section
  * add the info in the "contact" section along with the animation delays