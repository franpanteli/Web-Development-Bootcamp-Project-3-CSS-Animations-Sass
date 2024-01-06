<h1>fran-web-dev-bootcamp-project-3.netlify.app </h1>
<h2> Project 3 - ohmyfood </h2>
<h3>3i ohmyfood Course Notes</h3>
<p>'ohmyfood' is the third web development project I completed during this bootcamp. This was produced to integrate Sass animations with the HTML and CSS skills building from the previous project. The primary aim of this was to develop these skills by completing the course material and apply them by [INSERT START] , using GitHub, using GitHub, using GitHub, using GitHubconverting the mockup of a travel agency called Booki into a webpage. This mockup was provided in Figma. [INSERT END] </p>
<p>
<p>
This was used as the template for the menu pages of the project. The kitchen West menu was -> and it's loaded with comments which explain the various parts 
</p>
For this, three further courses were first completed on the OpenClassrooms platform. My notes from these may be found in the folder called '3i ohmyfood Course Notes by Fran_Panteli.' Further information about these courses is detailed below.

  <ul>
  <li><strong>Manage Your Code Project With Git and GitHub </strong> - the first course was a 6-hour long course on Git and GitHub. This was taught by Max Wardeh and covered Git commands, branching systems, using Git Reset and troubleshooting</li>
  <li><strong>Produce Maintainable CSS With Sass</strong> - the second was a 15-hour long course which included 7-1 file patterning, BEM selectors, specificity, CSS Preprocessors, Sass variables / extensions / functions, mixins, conditionals, advanced Sass data types, loops, breakpoints, and Autoprefixer. This course was produced by Pat Gerke</li>

  <li><strong>Create Modern CSS Animations</strong> - this was a 15-hour-long course covering CSS transitions / transformations, the 12 principles of animation, timing functions, opacity, anchor points using transform-origin, Chrome DevTools, CSS keyframes and Chrome's Animation tool. This course was also produced by Pat Gerke</li>
  </ul> 
<h3> 3ii ohmyfood Website</h3>
<p><strong>ohmyfood: </strong> the third project this bootcamp entailed was ohmyfood. This was a six-week project, with the aim of developing and applying skills in SaaS, GitHub and applying animations to webpages.</p>
<h1>Ohmyfood</h1>
<ul>
	<li> index.html <- this is the html for the main webpage 
	<li> assets <- this is the directory which contains the assets (the CSS file and images for the page)
	<li> Sass <- this is the directory which contains the Sass files for the project. This contains seven directories, listed below. The Sass file names within these take the format of '_variables.scss' and are prefixed with an underscore because they are partials included as part of a larger codebase 
	<ol>	
		<li>Base <- this contains the files that define the foundation of the site, such as the typography etc which are applied site-wide (all of the html files in the webpage have these in common) </li>
		<li>Utils <- is where variables, functions, mixins, and %placeholders for extensions are stored, if used. The order of @imports for the files this directory contains in comparison to the one the main directory contains has to be -> variables, functions, mixins, placeholders </li>
		<li>Layout <- is where BEM blocks which contain reusable elements for the webpage are stored -> e.g a form or header for large layouts</li>
		<li>Components <- this is where Sass for BEM blocks that are more self-contained is stored -> such as Sass for buttons</li>
		<li>Pages <- this contains blocks of code that only apply to a single page. E.g if the homepage has an element on it which does not apply elsewhere to the page -> elements which are unique to one of the pages on the site</li>
		<li>Themes <- this is where code which styles the webpage e.g for different holiday themes is stored -> these styles are defined in this directory, and then applied at the required times</li>
		<li>Vendors <- this contains Sass from third party vendors which is used in the project. These vendors include libaries such as Bootstrap or jquery UI -> essentially  any CSS that has originated from outside of the project, which is used to speed up the site creation</li>
	</ol>
	<li> restaurants <- this is the directory which contains the html files for the restaurant pages in the project (ohmyfood is a site where clients can order food from restauraunts, four different ones in this case and one for the desktop version)
<ul>

In VSCode 
<ul>
	<li>To open the terminal -> command shift p -> create new terminal</li>
	<li><u>To open a file using the terminal (in VSCode)</u> -> cd into that directory with the file, then <u> 'open file_name' </u><- chatGPT says to use 'code file_name' for this,  but it doesn't work -> the suggestion which does is 'open file_name''</li>
</ul>

The assets folder 
<ul>
	<li>This file contains the styles.css file, and the styles.map file which is produced when this is compiled from the main.scss file</li>
	<li>This also includes the images for the project and the ohmyfood logo</li>
</ul>


