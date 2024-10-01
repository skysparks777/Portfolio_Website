# Portfolio_Website
Created this website with the help of HTML, CSS and java script 



ASSIGNMENT- 1 


Name- Prashita Kalsotra
Roll no.- 231103042 
SEM- 3rd 
Branch- CSE
Course no.- CST3303
Course title- Web Technology  



**Q1. Build Web Pages (CO2)**
Website Overview: 
The website I designed, accessible at https://prashita.kalsotra.com/, is a multi-page portfolio focused on showcasing my skills and projects in digital art, photography, and coding. The goal of this website is to provide visitors with an engaging way to explore my work, learn about my background, and connect with me professionally. It includes sections like an art gallery, Photography, and Tech Me page.

Purpose: 
The website aims to serve as a personal portfolio and online presence. It showcases a collection of my work, including digital artwork, photography, and coding projects. The website is also intended to demonstrate my ability to design clean, responsive web pages while providing users with an aesthetic and easy-to-navigate experience.

Key HTML Elements:
1. Structural Elements:
These elements define the structure and layout of the web page.
html: The root element that contains all other HTML elements.
head: Contains meta-information about the webpage (e.g., title, metadata).
body: Holds the main content of the web page.
header: Represents the header section of a webpage or a section.
footer: Represents the footer section of a webpage or a section.
section: Defines thematic grouping of content.
div: A generic container used to group content for styling or layout purposes.
nav: Used for navigation links.

2. Text Formatting Elements:
These elements help format and display text in various ways.
<h1> to <h6>: Heading elements, where <h1> is the largest and <h6> is the smallest.
<p>: Defines a paragraph.
<hr>: Creates a horizontal rule (divider).
<blockquote>: Used for long quotations.

3. List Elements:
These elements create lists.
ul: Defines an unordered (bulleted) list.
li: Represents a list item (used inside <ul> or <ol>).

5. Media Elements:
These elements are used to embed media like images, videos, and audio.
img: Embeds an image.

6. Linking and Navigation Elements:
These elements handle linking and navigation.
a: Defines a hyperlink to link to other pages or resources.
link: Links external resources, such as CSS files.
nav: Represents a section containing navigation links.
7. Metadata Elements:
These elements provide metadata or additional information about the webpage.
title: Defines the title of the webpage.
style: Embeds CSS directly within an HTML file.
script: Embeds or references external JavaScript files.

Key CSS Techniques:
Flexbox (display: flex): Implemented to create flexible layouts, aligning items in the navigation bar and making certain sections responsive across different screen sizes.
Grid (display: grid): Used in the art gallery section to arrange images in a grid layout for a clean, structured appearance.
Colors and Fonts: Custom fonts were chosen to enhance the aesthetics of the website, and a well-balanced color scheme was applied. The color palette includes subtle greys for the background and a mix of complementary colors to highlight different sections.
Hover Effects: Applied on buttons and images to enhance interactivity when users hover over certain elements, giving the website a modern and dynamic feel.
By focusing on usability, aesthetics, and functionality, the website meets the objectives of providing a well-rounded user experience.



**Q2. Content Structure and Styling (CO3)**
Website Content Structure:
The website is structured in a clean and intuitive layout, designed to be easy for users to navigate. The structure includes:
Header:
The header section contains the website’s title and the main navigation menu.
The navigation bar includes links to different sections of the site, such as Home, Digital Art, Photography, and Tech me.
Main Sections:
Homepage: An introduction to who I am and what I do, featuring a brief summary of my work, skills, and purpose.
Digital Art Gallery: Displays a collection of my artwork, organized in a grid layout for visual clarity and ease of browsing.
Photography:Displays a collection of my landscapes , organized in the core nature.
TechMe: Contains contact information and links to my professional social media profiles. It also includes a simple contact form.
Footer:
The footer contains a Connect with me bar with Social links like GITHUB, INSTAGRAM, DISCORD and  YOUTUBE.
CSS Techniques for Layout:
Flexbox (display: flex):
Flexbox was extensively used to create a responsive and flexible layout. For instance, the header navigation uses Flexbox to align the menu items horizontally while maintaining responsiveness for smaller screen sizes.
The footer also employs Flexbox to evenly space the content and make it adaptable to various screen widths.
Grid (display: grid):
The Digital Art gallery section is designed using CSS Grid to display the artwork in a multi-column layout. This allows for easy control of image placement and makes the layout responsive, adjusting the number of columns based on the screen size.
Media Queries:
CSS media queries are used to ensure responsiveness across different devices, including desktops, tablets, and mobile phones. The layout and font sizes adjust based on the screen size to enhance readability and usability.

Typography:
Fonts:
I selected a modern, sans-serif font for the main body text to ensure readability, while a decorative font was chosen for headings to give the website a distinct, creative feel.
Font sizes were defined to create a clear hierarchy of content, with larger fonts for titles and headings and smaller but easily readable fonts for body text.
Font Weights and Line Heights:
CSS properties such as font-weight and line-height were used to improve the readability of text. I applied bold styles to headings to make them stand out and adjusted the line height for better legibility, particularly in paragraphs.
Color Scheme:
Background and Text Colors:
The overall color scheme is subtle and minimalistic, with a light grey background to provide a neutral canvas. Text is mainly Yellow for high contrast and readability.
Accent Colors:
Accent colors were chosen to links, and key sections, providing visual interest without overwhelming the user. These colors are applied to hover effects and navigation items to create a dynamic user experience.
Hover and Active States:
I implemented hover effects using :hover pseudo-class in CSS. In my code I used this function for my gallery to give it more dynamics and responsiveness.



**Q3. Fundamentals of the Web (CO1)**
Steps to Upload and Deploy the Project:
Uploading the Project to GitHub:
First, I created a new GitHub repository for the website project.
I initialized the repository locally using the following commands in the terminal:


git init
git add .
git commit -m "Initial commit of website project"
git branch -M main

Then, I linked the local repository to the GitHub remote repository by using the following commands:
git remote add origin https://github.com/skysparks777/Portfolio_Website.git
git push -u origin main

This uploaded all the website files, including HTML, CSS, and assets (images), to the GitHub repository.
Deploying the Website Online:
I pushed my website files to a GitHub repository.
I signed in to Cloudflare Pages and clicked Create a project.
I connected my GitHub account to Cloudflare and selected the repository where my website code is stored.
Cloudflare automatically detected my project settings (since it’s just HTML/CSS, no build configuration was required).
I selected the branch I wanted to deploy (e.g., main) and clicked Deploy.
Cloudflare built and deployed my website, making it live on a Cloudflare-provided URL.
To use a custom domain, I went to Domain settings, added my domain, and updated my DNS settings as per Cloudflare’s instructions.
After the DNS changes propagate, my website was accessible via my custom domain.


LINKS

GitHub Repository URL: https://github.com/skysparks777/Portfolio_Website.git
Live Website URL:   https://prashita.kalsotra.com/



