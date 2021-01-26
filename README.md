# Project 0

ENGO 551 - Adv. Topics on Geospatial Technologies


My project is a personal webpage about myself. I have a home page with three additional tabs, About me, My Photography, and Social. 
The About Me tab provides a description about myself and a few of my interests, along with a couple pictures pf myself. 
The My Photography tab displays a few of my photographs that I’ve taken. They are displayed in a small gallery and can be enlarged, 
while also adjusting the number of photos in each row based on the screen size. The Social tab provides a picture of my Instagram account 
and a card that has a link to Instagram. This is for those that would like to see more of my photos.


At the top of all .html files, there is a section for links to bootstrap 4 and stylesheets. 
In addition there is also a section that creates the header so other webpages can be accessed. 
Index.html:
In addition to what is mentioned above, there is also a text box section for the home page’s text.


About Me.html:
This file has a sequence of code that adds two images and textboxes beside the images for the text 
about myself. In addition, these images and textboxes are designed to adjust how much of the webpage 
they occupy based on the size of the browser window. The last textbox also has a table incorporated inside it. 


My Photography.html:
This file has a table at the top that’s used to display the equipment used to capture the images found 
in the gallery below. There is a section of code that is dedicated to the creation of the photo gallery. 
In addition, this gallery changes from four images per row to two images per row if the browser max size is 800px. 
In addition, at the bottom, there is a function that is used to enlarge an image from the gallery when it is clicked.


Social.html:
This file uses the bootstrap 4 card component to create a brief image, description, and link to my Instagram account. 
In addition, there is an additional image of my Instagram account placed beside the card. 


Picture.css:
This file is used as a stylesheet for the image gallery. Inside the file, there is a section of code that is 
used to determine the browser screen size and then it will adjust the number of images per row accordingly. 
There are also sections of the code, within the file, that are used to create an effect when hovering over an 
image in the gallery, organize the images in rows, and provide a close button for when an image is clicked. 


SCSS.scss and SCSS.css
The SCSS.scss file is used to create the SCSS variable, nesting, and inheritance. This file creates a variable 
for the color of the components within the div{} and uses inheritance to obtain the desired style for the text. 
All of this is nested within the file. The SCSS.css file is the .css version of the .scss file so that the .scss file can be used.


Stylesheet.css
This file contains areas where the style of multiple headings, paragraphs, and textboxes are created. 
In addition, there is an ID used for a table and a section where the background is changed from bootstrap’s default background. 
