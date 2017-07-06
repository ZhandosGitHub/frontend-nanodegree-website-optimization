# Project Title

This is "Website Optimization" Project, as part of Udacity's "Front End Developer Nanodegree Program."

# Running

* To see online - see [demo version](https://zhandosgithub.github.io/Website%20Optimization/index.html) of "Website Optimization" project
* To see locally - clone the "Website Optimization" project [repository](https://github.com/ZhandosGitHub/frontend-nanodegree-website-optimization) from GitHub and run Index.html



# Optimizations to Ensure a Minimum PageSpeed Insights Score of 90 for index.html

### Changes to index.html

* Minified style.css and inlined within index.html
* added media="print" attribute to link tag to external print styles sheet
* moved scripts to end of body
* Removed  Google Web Font Loader script at the end of body
* Resized and optimized images


* Optimizations to Ensure a Consistent Frame Rate of 60 FPS

### Changes to views/js/main.js

* Replaced querySelector with getElementById for better performance
* Replaced querySelectorAll with getelementsbyclassname for better performance
* Moved elems, items, itemLenth and phase,pizzasDiv out of for loop to remove unnessary repeagted initializations
* Moved calcaulation out of for loop (in var scrollingTopBy1250)
* Reduced number of pizzas to 40 from 200
* Got read of determineDx function by refactoring within existing function
* Got read of col and s values, by specifying values directly  - In function changePizzaSizes(size) {
* Applied transformX to sliding pizzas

# Authors

* **Zhandos Ashirbayev** - [LinkedIn Profile](https://www.linkedin.com/in/zhandosashirbayev/)

# Acknowledgments

The following images were used from other resources
* Image for "Online Resume" Project - [Link to image on Pixabay.com](https://pixabay.com/en/resume-bio-data-job-employment-1799952/)
* Image for "Arcade Game" Project - [Link to image on Pixabay.com](https://pixabay.com/en/pinball-videogame-arcade-games-179631/)
