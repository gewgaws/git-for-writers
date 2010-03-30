The css folder is where you store all of the .css files for your website.

There are currently five CSS files in this folder; two you do not need to edit:

--reset.css:
	CSS written by Yahoo! that removes default web browser CSS
--base.css:
	Restores styles removed by reset.css, like bold and italics. The
	contents of this file appear at the top of screen.css and print.css.

And three that you will need to edit to design your site:

--screen.css:
	Where you write all of the styles for screen views of your pages
	(screen.css also imports the reset.css and base.css files)

--screen-ie.css: 
	A conditional CSS file where you write any style fixes, if necessary, 
	for Internet Explorer 7 or earlier. 
	
--print.css
	Where you write styles that determine how your pages will appear when 
	they are printed.

Any additional CSS files that you add (such as an iphone.css file for iPhones)
should also appear in the css folder.

The gfx sub-folder is where you should save all of your design images for
your site (see gfx/gfx-readme.txt).

