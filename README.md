# mysite
Usage:
To open this page, go to settings in the github repository, and click on the link under github pages. The site will offer the user several 
functionalities, such as viewing tour dates, discography, band info, quotes about the band, and liking the band. 

Design:
The homepage was designed with a z-pattern in mind. The user's eye is drawn from the logo in the top left corner to the info bar, then down 
through the middle of the page to the concert photo, then back across the bottom to like the band. The subpages were desinged with the
f-pattern in mind used for displaying text heavy pages. This was the best way to concisely display the info for tour dates and songs etc 
without overloading the users senses. The header and footer that are on every page give the user some consistency for knowing how
to navigate between pages so that they are never lost, and allow them to perform the like function no matter where they are in the site.

Challenge:
The biggest way I challenged myself was to try to learn from real active websites. I studied the code for bowdoins homepage to design the 
animation that shrinks the photo and reveals text. On bowdoins homepage, there are two overlapping images, and one image has its width set 
based on the postion of the mouse, creating a slider effect. I couldn't figure out how to do this slider with the mouse, but I figured out 
how to change the style of an element based on mouse hover, which is what I used to resize the picture and display the text. Another 
website I learned from was Kahoot, which had a changing color background. Their site used a built in linear function within their
css sheets that varied the background color at a constant rate between an array of specified colors. I wanted to do the same thing but get some practice
implementing funcitons with js, so I used a js funciton that would allow me to loop through an array of colors. My goal with the like
function was to have a js variable that could be changed from any page in the site, giving a cumulative like count. I tried to 
accomplish this by setting the like count as a global variable on local storage, but this did not end up working. 
Another challenge was that I was unable to get the proper system permissions on my pc to install jekyll, so I used another library to
help me import headers and footers to create a layout of sorts. For this I used jquery to load separate html files into my index file.

Credits:
StackOverflow and W3schools for coding snippets
EventBrite blog for concert photo
