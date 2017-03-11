# Website Optimization Project

### About The Project

This project is based on Website Performance Optimization. It consists of two parts
```
1. PageSpeedInsights Score
2. 60 fps Project

```
The first part of the project optimizes a webpage's initial load time whereas the second part of the project focuses on optimizing the animations
to run smoothly at 60fps. This project emphasizes on the concept of reducing the critical rendering path and doing away with unncessary blocks of
code which affect performance. Get ready to optimize!!

### Getting Started
Clone this repository, perform a pull request or just simply download the zip file to access the content.Learn more about making pull requests [here.](https://help.github.com/articles/about-pull-requests/)

### Going into the Deep Stuff !
To analyse the PageSpeedScore of index.html for initial load times which covers the first part of the project you should obtain a URL.This can be done by setting up a simple HTTP server using python or hosting the website on github pages.Refer to the following links for detailed information on both of these methods

1. [Setting up a simple HTTP Python server](http://www.pythonforbeginners.com/modules-in-python/how-to-use-simplehttpserver/)
2. [Hosting a webpage using github pages](https://help.github.com/categories/github-pages-basics/)
3. [As an alternative, you can also use ngrok to test your webpage](https://www.sitepoint.com/use-ngrok-test-local-site/)

For the second part of the project where you have to analyse the animation time of the webpage (60fps), simply open up the pizza.html in the views folder. The main purpose of the project is to optimize the javascript for animations which is contained in the main.js file in the views/js directory.Now, that you have the code and the webpage opened up on chrome, pop open chrome dev tools and start analysing!! To learn more about Chrome Dev Tools [click here.](https://developers.google.com/web/tools/chrome-devtools/)

### Notes

Since this webpage has been optimized on the chrome browser, I recommend you to use the same for further testing, reviewing and optimisation

### How I Optimized the Code

1. For the first part of the project, I had to improve the initial load time. The best way to do that is to optimize the critical rendering path.
 There are a number of methods to do this:

* Inlining the css
* Optimizing the Images using task runners (I used ImageOptim :))
* Using media queries for files that are used only in certain cases
and many others ...which you will see in the code..

2. Optimizing the javascript

* Caching the elements in the loop that remain constant outside the loop.
* Optimizing event isteners and animations by using requestAnimationFrame or other API's.
* Keeping elements that render on the screen and getting rid of the ones that don't.
* Using methods and properties that don't cause layout thrashing.
* Many more........explained in comments

#### Some more links for reference

 https://csstriggers.com/
 https://developers.google.com/web/fundamentals/performance/critical-rendering-path/
 https://developer.mozilla.org/en-US/docs/Web/API/window/requestAnimationFrame
 https://css-tricks.com/css-triggers/

#### Tools Used
1. Bootstrap CSS
2. ImageOptim
3. Udacity's Starter Code
