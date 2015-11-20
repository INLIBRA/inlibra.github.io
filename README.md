## Website Performance Optimization portfolio project
Assets for this project were taken from www.udacity.com Frontend Development Program.

Optimizations were performed for index.html and achieved a PageSpeed score 97 for desktop and 96 for mobile:

1. style.css was inlined and minified
2. use async attribute on scripts to unblock rendering
3. Use media "print" on print.css to unblock rendering


Optimizations were performed ensuring a consistent frame rate at 60fps when scrolling pizza.html and time to resize pizzas only 3 ms were reached.

for views/js/main.js

Optimized JavaScript code (eliminate iteration though elements, number of elements, take calculations out of the loop and so on)

for views/css/style.css

Added a separate layer for moving elements.
