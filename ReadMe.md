<h1>fran-web-dev-bootcamp-project-3.netlify.app </h1>
<h2> Project 3 - ohmyfood </h2>
<h3>Abstract</h3>
<p>'ohmyfood' is the third web development project I completed during this bootcamp. This was produced to integrate Sass animations with the HTML and CSS skills acquired from the previous project. The primary aim of this was to develop these skills by completing the course material and to apply them by producing a webpage for a gourmet restaurant app with various animations created using CSS (Sass). This project was versioned using GitHub and was created by converting the mockup of the webpage into a mobile-first web application. This mockup was provided in Figma and problem-solving sessions were conducted for this project during mentoring sessions and webinars included as part of the bootcamp. This was finally assessed in a 15-minute oral presentation conducted on the OpenClassrooms platform. </p>
</p>





<p>
├── Bootcamp Course Notes by Fran_Panteli
│   ├── 1 Set Up Your Front-End Development Environment.pdf
│   ├── 2 Build Your First Web Pages With HTML and CSS.pdf
│   ├── 3 Design a Mock-up for Web Development With Figma.pdf
│   ├── 4i Create Web Page Layouts With CSS.pdf
│   ├── 4ii Create Web Page Layouts With CSS.pdf
│   ├── 5i Break Down and Integrate a Mockup.pdf
│   ├── 5ii Break Down and Integrate a Mockup.pdf
│   ├── 5iii Break Down and Integrate a Mockup.pdf
│   ├── 6 Manage Your Code Project With Git and GitHub.pdf
│   ├── 7i Produce Maintainable CSS With Sass.pdf
│   ├── 7ii Produce Maintainable CSS With Sass.pdf
│   ├── 7iii Produce Maintainable CSS With Sass.pdf
│   ├── 8i Create Modern CSS Animations.pdf
│   ├── 8ii Create Modern CSS Animations.pdf
│   ├── 8iii Create Modern CSS Animations.pdf
│   └── 8iv Create Modern CSS Animations.pdf
├── ReadMe.md
├── assets
│   └── images
│       └── restaurants
│           ├── circle-dish-with-hand.jpg
│           ├── circle-from-above-dish.jpg
│           ├── circle-from-the-side-dish.jpg
│           └── rectangle-dish.jpg
├── index.html
├── main.css.map
├── main.scss
├── restaurants
│   ├── Elderflower.html
│   ├── Kitchen-West-template-menu.html
│   ├── Shoreditch-Canteen.html
│   ├── The–Bay-Leaf.html
├── sass
│   ├── base
│   │   └── _root.scss
│   ├── components
│   │   ├── _more_potential_animation_files.scss
│   │   └── _restaurant_cards.scss
│   ├── layouts
│   │   ├── _footer.scss
│   │   ├── _header.scss
│   │   ├── _loading_animations.scss
│   │   └── _pages.scss
│   └── utils
│       ├── _keyframes.scss
│       ├── _mixins.scss
│       └── _variables.scss
├── styles.css
└── styles.css.map
</p>
<h3>Project file tree extended</h3>
<p>This is the same project file tree, in more depth. These annotations explain what each section does and the thought processes behind structuring the project using this approach.</p>
<p>
├── Bootcamp Course Notes by Fran_Panteli  *<u> <- a directory of my notes on the bootcamp course material covered on the OpenClassrooms platform</u>*
│   ├── 1 Set Up Your Front-End Development Environment.pdf  *<u> <- courses in the first bootcamp project (Riding Cities)</u>*
│   ├── 2 Build Your First Web Pages With HTML and CSS.pdf
│   ├── 3 Design a Mock-up for Web Development With Figma.pdf
│   ├── 4i Create Web Page Layouts With CSS.pdf 
│   ├── 4ii Create Web Page Layouts With CSS.pdf
│   ├── 5i Break Down and Integrate a Mockup.pdf  *<u> <- courses in the second bootcamp project (Booki)</u>*
│   ├── 5ii Break Down and Integrate a Mockup.pdf
│   ├── 5iii Break Down and Integrate a Mockup.pdf
│   ├── 6 Manage Your Code Project With Git and GitHub.pdf *<u> <- courses in the third bootcamp project (ohmyfood)</u>*
│   ├── 7i Produce Maintainable CSS With Sass.pdf
│   ├── 7ii Produce Maintainable CSS With Sass.pdf
│   ├── 7iii Produce Maintainable CSS With Sass.pdf
│   ├── 8i Create Modern CSS Animations.pdf
│   ├── 8ii Create Modern CSS Animations.pdf
│   ├── 8iii Create Modern CSS Animations.pdf
│   └── 8iv Create Modern CSS Animations.pdf
├── ReadMe.md *<u> <- this ReadMe file, produced in the GitHub MEditor.md UI</u>*
├── assets *<u> <- images for the project, these files were provided on the OpenClassrooms platform and renamed here based on their contents</u>*
│   └── images
│       └── restaurants
│           ├── circle-dish-with-hand.jpg
│           ├── circle-from-above-dish.jpg
│           ├── circle-from-the-side-dish.jpg
│           └── rectangle-dish.jpg
├── index.html *<u> <- this contains the html for the project homepage. This has in-depth comments which explain the thought processes and problem-solving approaches used to produce this</u>*
├── main.css.map  *<u> <- files produced from compiling the Sass partials into CSS</u>*
├── main.scss  *<u> <- this imports the Sass partials into the main Sass file, importing them in the order listed in the course notes for the project </u>*
├── restaurants *<u> <- there are four restaurant pages and a main homepage for the project. Each of these restaurant pages is an html file in this directory, and each is named after the restaurant it represents </u>*
│   ├── Elderflower.html
│   ├── Kitchen-West-template-menu.html  *<u> <- this was used as the template for the other four menu pages. There were four menu pages and a homepage. This contains in depth comments explaing the thought processes and approaches used to produce these menu pages</u>*
│   ├── Shoreditch-Canteen.html
│   ├── The–Bay-Leaf.html
├── sass *<u> <- this is the file which contains the partials for the Sass. These partials are structured according to the 7:1 file structure explored in the course material found in my notes from parts 7i to 7iii of the course</u>*
│   ├── base *<u> <- this contains the files that define the foundation of the site, such as the typography etc which are applied site-wide (all of the html files in the webpage have these in common)</u>*
│   │   └── _root.scss
│   ├── components *<u> <- this is where Sass for BEM blocks that are more self-contained is stored -> such as Sass for buttons</u>*
│   │   ├── _more_potential_animation_files.scss
│   │   └── _restaurant_cards.scss
│   ├── layouts *<u> <- is where BEM blocks which contain reusable elements for the webpage are stored -> e.g a form or header for large layouts</u>*
│   │   ├── _footer.scss
│   │   ├── _header.scss
│   │   ├── _loading_animations.scss
│   │   └── _pages.scss
│   └── utils *<u> <- this is where variables, functions, mixins, and %placeholders for extensions are stored, if used. The order of @imports for the files this directory contains in comparison to the one the main directory contains has to be -> variables, functions, mixins, placeholders</u>*
│       ├── _keyframes.scss
│       ├── _mixins.scss
│       └── _variables.scss
├── styles.css *<u> <- this file contains the compiled css. All five of the html pages for the project link back to this same. This was produced by from compiling the Sass using the terminal functionality in VSCode</u>*
└── styles.css.map *<u> <- file contains the compiled CSS. All five of the html pages for the project link back to this same fuke. This was produced by compiling the Sass using the terminal functionality in VSCode</u>*
</p>





# Bootcamp Course Notes by Fran_Panteli



## Directory Structure
<h3>Web development bootcamp notes (extension)</h3>
<p>Three new courses were covered as part of this project. These are detailed below and were provided on the OpenClassrooms platform to develop Sass, versioning and animation skills with CSS.Their contents are described below</p>
<ul>
  <li><strong>Manage Your Code Project With Git and GitHub </strong> - the first course was a 6-hour long course on Git and GitHub. This was taught by Max Wardeh and covered Git commands, branching systems, using Git Reset and troubleshooting</li>
  <li><strong>Produce Maintainable CSS With Sass</strong> - the second was a 15-hour long course which included 7-1 file patterning, BEM selectors, specificity, CSS Preprocessors, Sass variables / extensions / functions, mixins, conditionals, advanced Sass data types, loops, breakpoints, and Autoprefixer. This course was produced by Pat Gerke</li>

  <li><strong>Create Modern CSS Animations</strong> - this was a 15-hour-long course covering CSS transitions / transformations, the 12 principles of animation, timing functions, opacity, anchor points using transform-origin, Chrome DevTools, CSS keyframes and Chrome's Animation tool. This course was also produced by Pat Gerke</li>
</ul> 
The full contents of my notes from this bootcamp is below 
# Bootcamp Course Notes by Fran_Panteli

- [1 Set Up Your Front-End Development Environment.pdf](./Bootcamp%20Course%20Notes%20by%20Fran_Panteli/1%20Set%20Up%20Your%20Front-End%20Development%20Environment.pdf)
- [2 Build Your First Web Pages With HTML and CSS.pdf](./Bootcamp%20Course%20Notes%20by%20Fran_Panteli/2%20Build%20Your%20First%20Web%20Pages%20With%20HTML%20and%20CSS.pdf)
- [3 Design a Mock-up for Web Development With Figma.pdf](./Bootcamp%20Course%20Notes%20by%20Fran_Panteli/3%20Design%20a%20Mock-up%20for%20Web%20Development%20With%20Figma.pdf)
- [4i Create Web Page Layouts With CSS.pdf](./Bootcamp%20Course%20Notes%20by%20Fran_Panteli/4i%20Create%20Web%20Page%20Layouts%20With%20CSS.pdf)
- [4ii Create Web Page Layouts With CSS.pdf](./Bootcamp%20Course%20Notes%20by%20Fran_Panteli/4ii%20Create%20Web%20Page%20Layouts%20With%20CSS.pdf)
- [5i Break Down and Integrate a Mockup.pdf](./Bootcamp%20Course%20Notes%20by%20Fran_Panteli/5i%20Break%20Down%20and%20Integrate%20a%20Mockup.pdf)
- [5ii Break Down and Integrate a Mockup.pdf](./Bootcamp%20Course%20Notes%20by%20Fran_Panteli/5ii%20Break%20Down%20and%20Integrate%20a%20Mockup.pdf)
- [5iii Break Down and Integrate a Mockup.pdf](./Bootcamp%20Course%20Notes%20by%20Fran_Panteli/5iii%20Break%20Down%20and%20Integrate%20a%20Mockup.pdf)
- [6 Manage Your Code Project With Git and GitHub.pdf](./Bootcamp%20Course%20Notes%20by%20Fran_Panteli/6%20Manage%20Your%20Code%20Project%20With%20Git%20and%20GitHub.pdf)
- [7i Produce Maintainable CSS With Sass.pdf](./Bootcamp%20Course%20Notes%20by%20Fran_Panteli/7i%20Produce%20Maintainable%20CSS%20With%20Sass.pdf)
- [7ii Produce Maintainable CSS With Sass.pdf](./Bootcamp%20Course%20Notes%20by%20Fran_Panteli/7ii%20Produce%20Maintainable%20CSS%20With%20Sass.pdf)
- [7iii Produce Maintainable CSS With Sass.pdf](./Bootcamp%20Course%20Notes%20by%20Fran_Panteli/7iii%20Produce%20Maintainable%20CSS%20With%20Sass.pdf)
- [8i Create Modern CSS Animations.pdf](./Bootcamp%20Course%20Notes%20by%20Fran_Panteli/8i%20Create%20Modern%20CSS%20Animations.pdf)
- [8ii Create Modern CSS Animations.pdf](./Bootcamp%20Course%20Notes%20by%20Fran_Panteli/8ii%20Create%20Modern%20CSS%20Animations.pdf)
- [8iii Create Modern CSS Animations.pdf](./Bootcamp%20Course%20Notes%20by%20Fran_Panteli/8iii%20Create%20Modern%20CSS%20Animations.pdf)
- [8iv Create Modern CSS Animations.pdf](./Bootcamp%20Course%20Notes%20by%20Fran_Panteli/8iv%20Create%20Modern%20CSS%20Animations.pdf)




├── Bootcamp Course Notes by Fran_Panteli
│   ├── 1 Set Up Your Front-End Development Environment.pdf
│   ├── 2 Build Your First Web Pages With HTML and CSS.pdf
│   ├── 3 Design a Mock-up for Web Development With Figma.pdf
│   ├── 4i Create Web Page Layouts With CSS.pdf
│   ├── 4ii Create Web Page Layouts With CSS.pdf
│   ├── 5i Break Down and Integrate a Mockup.pdf
│   ├── 5ii Break Down and Integrate a Mockup.pdf
│   ├── 5iii Break Down and Integrate a Mockup.pdf
│   ├── 6 Manage Your Code Project With Git and GitHub.pdf
│   ├── 7i Produce Maintainable CSS With Sass.pdf
│   ├── 7ii Produce Maintainable CSS With Sass.pdf
│   ├── 7iii Produce Maintainable CSS With Sass.pdf
│   ├── 8i Create Modern CSS Animations.pdf
│   ├── 8ii Create Modern CSS Animations.pdf
│   ├── 8iii Create Modern CSS Animations.pdf
│   └── 8iv Create Modern CSS Animations.pdf
├── ReadMe.md
├── assets
│   └── images
│       └── restaurants
│           ├── circle-dish-with-hand.jpg
│           ├── circle-from-above-dish.jpg
│           ├── circle-from-the-side-dish.jpg
│           └── rectangle-dish.jpg
├── index.html
├── main.css.map
├── main.scss
├── restaurants
│   ├── Elderflower.html
│   ├── Kitchen-West-template-menu.html
│   ├── Shoreditch-Canteen.html
│   └── The–Bay-Leaf.html
├── sass
│   ├── base
│   │   └── _root.scss
│   ├── components
│   │   ├── _more_potential_animation_files.scss
│   │   └── _restaurant_cards.scss
│   ├── layouts
│   │   ├── _footer.scss
│   │   ├── _header.scss
│   │   ├── _loading_animations.scss
│   │   └── _pages.scss
│   └── utils
│       ├── _keyframes.scss
│       ├── _mixins.scss
│       └── _variables.scss
├── styles.css
└── styles.css.map

<h3>Raw project file tree </h3>

<p>The file tree for this project is below and was included as an extension to the project. The second project in the bootcamp included basic starter files, although this did not. This was the solution for the file tree which was devised for this project. This was produced by studying the course material and project milestone guide. This was a more complex problem to solve for this project, given that it introduced Sass and versioning with git in tandem here.</p>






<h3>Raw project file tree </h3>

<p>The file tree for this project is below and was included as an extension to the project. The second project in the bootcamp included basic starter files, although this did not. This was the solution for the file tree which was devised for this project. This was produced by studying the course material and project milestone guide. This was a more complex problem to solve for this project, given that it introduced Sass and versioning with git in tandem here.</p>

```plaintext


```plaintext
├── Bootcamp Course Notes by Fran_Panteli <- a directory of my notes on the bootcamp course material covered on the OpenClassrooms platform
│   ├── 1 Set Up Your Front-End Development Environment.pdf <- courses in the first bootcamp project (Riding Cities)
│   ├── 2 Build Your First Web Pages With HTML and CSS.pdf
│   ├── 3 Design a Mock-up for Web Development With Figma.pdf
│   ├── 4i Create Web Page Layouts With CSS.pdf 
│   ├── 4ii Create Web Page Layouts With CSS.pdf
│   ├── 5i Break Down and Integrate a Mockup.pdf <- courses in the second bootcamp project (Booki)
│   ├── 5ii Break Down and Integrate a Mockup.pdf
│   ├── 5iii Break Down and Integrate a Mockup.pdf
│   ├── 6 Manage Your Code Project With Git and GitHub.pdf <- courses in the third bootcamp project (ohmyfood)
│   ├── 7i Produce Maintainable CSS With Sass.pdf
│   ├── 7ii Produce Maintainable CSS With Sass.pdf
│   ├── 7iii Produce Maintainable CSS With Sass.pdf
│   ├── 8i Create Modern CSS Animations.pdf
│   ├── 8ii Create Modern CSS Animations.pdf
│   ├── 8iii Create Modern CSS Animations.pdf
│   └── 8iv Create Modern CSS Animations.pdf
├── ReadMe.md <- this ReadMe file, produced in the GitHub MEditor.md UI
├── assets <- images for the project, these files were provided on the OpenClassrooms platform and renamed here based on their contents
│   └── images
│       └── restaurants
│           ├── circle-dish-with-hand.jpg
│           ├── circle-from-above-dish.jpg
│           ├── circle-from-the-side-dish.jpg
│           └── rectangle-dish.jpg
├── index.html <- this contains the html for the project homepage. This has in-depth comments which explain the thought processes and problem-solving approaches used to produce this
├── main.css.map <- files produced from compiling the Sass partials into CSS
├── main.scss <- this imports the Sass partials into the main Sass file, importing them in the order listed in the course notes for the project
├── restaurants <- there are four restaurant pages and a main homepage for the project. Each of these restaurant pages is an html file in this directory, and each is named after the restaurant it represents
│   ├── Elderflower.html
│   ├── Kitchen-West-template-menu.html <- this was used as the template for the other four menu pages. There were four menu pages and a homepage. This contains in depth comments explaing the thought processes and approaches used to produce these menu pages
│   ├── Shoreditch-Canteen.html
│   ├── The–Bay-Leaf.html
├── sass *<u> <- this is the file which contains the partials for the Sass. These partials are structured according to the 7:1 file structure explored in the course material found in my notes from parts 7i to 7iii of the course
│   ├── base <- this contains the files that define the foundation of the site, such as the typography etc which are applied site-wide (all of the html files in the webpage have these in common)
│   │   └── _root.scss
│   ├── components <- this is where Sass for BEM blocks that are more self-contained is stored -> such as Sass for buttons
│   │   ├── _more_potential_animation_files.scss
│   │   └── _restaurant_cards.scss
│   ├── layouts <- is where BEM blocks which contain reusable elements for the webpage are stored -> e.g a form or header for large layouts
│   │   ├── _footer.scss
│   │   ├── _header.scss
│   │   ├── _loading_animations.scss
│   │   └── _pages.scss
│   └── utils <- this is where variables, functions, mixins, and %placeholders for extensions are stored, if used. The order of @imports for the files this directory contains in comparison to the one the main directory contains has to be -> variables, functions, mixins, placeholders
│       ├── _keyframes.scss
│       ├── _mixins.scss
│       └── _variables.scss
├── styles.css <- this file contains the compiled css. All five of the html pages for the project link back to this same. This was produced by from compiling the Sass using the terminal functionality in VSCode
└── styles.css.map <- file contains the compiled CSS. All five of the html pages for the project link back to this same fuke. This was produced by compiling the Sass using the terminal functionality in VSCode
