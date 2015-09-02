Go to  http://ntibbs.github.io/udportfolio to view the page

to get the page above a score of 90 in pagespeen insights i did the following

Minified HTML, CSS, and JS
resized pizzaria amd compresssed
compressed profile picture
made style.css internal
added media="print" to print.css to keep from render blocking

to get main.js to perform over 60fps and the slide bar to change pizzas in under 5ms i did the following

changed document.querySelectorAll(".randomPizzaContainer") to document.getElementsByClassName() in multiple places
moved multiple variables out of loops so the DOM would be touched in ever itteration of the loop
changed the numbers sliding pizzas on the page from 200 to 40