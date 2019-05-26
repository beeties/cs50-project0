# Project 0

Web Programming with Python and JavaScript

25th of May 2019
Jean Sebastien Cormier
jeansebcormier@hotmail.com


Index.html
The first page index.html is where I started.
The basic structure of the whole site was created here and then copied as a starting template for all of the other pages.

In the header I've included a viewport line in order to interact with the client screen size.
The styling of all of the pages are specified in the sassystyle.css and/or style.css files that are linked in the header.
The header of every page also includes a link to Bootstrap.

I created a menu with links to the other pages and made sure it is responsive for mobile devices (see style.css)
An unordered list was used to make the smaller screen size menu.
It only appears when the screen is of a smaller specified width and is made possible by the use of some @media code.
The display inline option was added in order to display the menu list items in a line.

In the body of this page I have put 1 row with 4 bootstrap columns. 
The two outer columns are used for layout purposes and the middle two for content.
The second column has a picture of me and the third column some site descriptive text.
I have also added the md option on each column throughout the site to rearrange the columns when the screen gets smaller.

All of the text links of the website have hover response except for the text on the left of the top menu.


Interest
This page is to show a few of my interests.
The body of this page includes 4 rows with 4 colomns each using the Bootstrap grid.
Each second column has a picture and the third columns have some descriptive text.
Some of the descriptive texts also include a link to some of my websites.


Resume
The top portion of this page has 3 rows with 3 colomns each using Bootstrap.
The first two rows have content in the middle with two exterior rows that are there for layout purposes.
The first row has some text and the second row has a table showing my training.
The last row has 3 pictures that are also links to some websites that I have created.


Contact
The body of this page has 3 rows and the content is in the center row.
The content is a Bootstrap component card that includes a botton which I've linked to a mailto and a page redirection action. 
When someone presses on the botton it opens their default mail application and puts my email address in the To section. 
The second action opens the thanks.html web page.


Thanks
This is a hidden page that only opens when the email button from the contact
page is activated but it has all of the menu links to all of the other pages.
It has 4 bootstrap columns like the home page with two used for layout purposes. 
There is a picture of me in the second column and some text in the third column thanking the visitors for their visit.


style.css
There is a lot of styling in this css file but some of the most note worthy ones are:
- The @media that takes care of displaying the menu differently when on smaller screens. It hides the big screen menu and shows the smaller screen menu.
- All of the styling for the top menu, footer, columns, Resumé table.
- The table and contact card shadows have been defined here.
- The Bootstrap component card Input actions for the contact page.
- There are many classes and a few identifiers (main-container, main-body, name-text-top-menu and column-margin-left).
- The text link hover actions have been specified in this file.


sassystyle.scss / sassystyle.css
Here I have a variable called $menu-color that specifies the color of the top menu and footer.
A nested Div that provides text color for the text in the Divs of the whole site as well as specifications for the H3 and H4 text shadow in all of the Divs.
The %message inheritance code takes care of some redundant code that is used in three of the .polaroid shadow classes. 


I could have continued working on this site to try and perfect it but at some point I had to stop. For now.


JSC

