# Responsive-Portfolio
This homework assignment is the development of my first responsive portfolio page.

# Project Purpose
This homework assignment demonstrates comprehension of utilizing Bootstrap for the CSS framework. Bootstrap provides a fast and flexible framework on which to build my portfolio website. My favorite feature is the built-in mobile responsiveness which makes my HTML website automatically adjust the content to the screen size. This helps my website to maintain a professional appearance no matter what the screen size is on the user's device.

# Project Images
In the Instructions folder, there is a folder of images that was provided as the basis for this project.

Images used in the deployed website page are contained in the Assets/Images folder.

# Project Learnings
While the concept of using a wireframe seemed simple, this was a challenging task for me to visualize the layers and grid of the wireframe. After completing this project, I can see where the use of Bootstrap will allow me to more easily control the uniformity of my website pages.

Creating the index.html file first with the link to the CSS style sheet and the navbar links to the contact and portfolio html files was pretty straight forward and easy to accomplish. Setting up the bones of the page allowed for easy copy and paste of the code into the contact and portfolio pages. I then just needed to adjust the li class with the active attribute and the span tag for current emphasis.

The next part was pretty hard. I had to carefully plan the layout of each page in consideration of the content and readability. 

I developed the index page using a container to hold the rows but did not use any columns so that I could have the text float around the images as the screen size changes. I especially enjoyed finding the inset border style (I thought it was pretty cool looking)!

The portfolio page was pretty simple as I used one container to hold four rows with two columns each. I then inserted placeholders for the image links as representation of future projects. Since I used a container instead of a card, I had to place a break between the navbar and the container for easy separation.

For the contact page, I created a container that held one row and two columns which each held a card. The contact me card contained a form with a submit button, and the contact information card contained a table with links to my personal accounts on Gmail, LinkedIn, and GitHub.

My hardest thing to figure out was creating a responsive image on the index.html file, or About Me page. I tried several different approaches to fixing this issue while searching for a solution in forums online. After watching numerous videos and reading several forum posts, I decided to manually adjust the h1 tag with inline styling for the bottom margin and padding as well as aligning the text to the top and left.

I also had to do some digging to find out how to move the links on the navigation bar to the right side. My GoogleFu was strong on this one, so I did not have to look long to find a video demonstration of how the navbar works in Bootstrap 4. This is the video created by CodeTime that I used to find my answer at time 6:18 [linked website](https://codetime.io/series/how-to-create-navbars-with-bootstrap-4/episode/creating-a-navbar-with-right-aligned-links). I inserted the ml-auto into the ul class to force the links as far to the right as they would go on the screen when they were not collapsed into the hamburger.

My biggest lesson came when I doubled checked my deployed website. The website did not load my images correctly and some of the formatting was off. I check several things, but ultimately received help from someone much more skilled than I. But, I have now learned my lesson! Be consistent in using case types...don't change to naming folders in Pascal case when trying to keep consistent lowercase. While Windows may not care, Linux sure does! I will always be appreciative for the eyes and knowledge of others!

As time is always a factor in any project, I stop the development of this project despite wanting to change a few more things. I plan to revisit this project to further develop the section backgrounds that are currently white and possibly change the font family.

## Deployed Website

![Deployed website screenshot](./Assets/Images/frontPage.PNG)