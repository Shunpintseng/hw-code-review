# hw-code-review

This is a code review of Horiseon website. The main goals for this exercise are:

-Update semantic tags in html to comply with the accessibility standards
-Clean up the existing code
-Remove redundant code lines
-Provide logical organization of each section.

Following are the rules when reviewing the html code:

1. All tags are assigned with appropriate name following accessiblity standards. 
2. <!-- --> indicates the comments and changes made in the code.
3. All containers are shown with break lines in html code for clarity.
4. Avoid using generic <div> tag when possible to avoid confusion
5. HTML elements are organized as follow: 
	<header>
	<nav>
	<section>
	<article>
	<aside>
	<footer>
6. HTML code is written from top to bottom and left to right order on the website. 

Following are the rules when reviewing css code:

1. The css code is organized as following order: type > class > id.
2. /* */ indicates the comments and changes made in the code.
3. #id is avoided whenever possible.
4. headings are the following order: h1 > h2 > h3 > h4
5. All linked images are moved to html to keep css only describ the style.
6. Redundant classes are removed and consolidate for clarity.
 