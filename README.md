# Theater-CMS
CMS website for a theater group.

## Introduction
After completing courses in HTML/CSS, JavaScript, SQL, Python and C#/.NET at The Tech Academy, I had the opportunity to participate in their "C#/.NET Live Project" with a team of instructors and students.  Using Azure DevOps for project management and following the Agile management approach, students worked together to build a CMS website for a theater company project using the .NET Framework.  The project included checking out stories to complete, working with others in a large-project environment using a version control system, conforming to project conventions, daily stand-up meetings, and code retrospectives.  My contribution to the project was creating and styling the About Page and a series of pages for managing rental request data. What follows is a summary of some of the highlights and lessons learned from this experience.

## Creating the About Us Page
Following a mock-up and images created by designers and pulling content from the theater company's outdated website, I created the About Us page for the site using HTML/CSS and Boostrap4. The style was kept consistent with the rest of the site including staying within the color scheme and creating DOM tag IDs and classes consistent with the guidelines for the larger site. After review, the page was finalized by addressing requests for improvements and the changes were pulled into the remote master.

## Rental Request Data Management Pages
The project was created using the Entity Framework Code-First template, so in order to enable CRUD capabilities via a database, the model had to be constructed first.  After creating the model, the constructor was expanded, methods were added to the model and controller, and view templates modified using Razor so that rental requests were displayed in an accordion matching a specific design format and displaying the amount of time until the rental started or ended, as appropriate.  Then additional methods were added so users could see rental requests in order of the request date and toggle between current and expired requests.  The latter funcationality was created using JavaScript to occur dynamically within the page rather than requiring a page reload. 

## Skills Acquired
* Working with a group of developers to collaborate on a larger project, implementing a project management system and the Agile managment approach.
* Checking files out in a version control system, following proper procedures for maintaining the integrity of branches and the master while merging changes, following project conventions, and creating pull requests.
* Creating forms and widgets and rendering views in .NET, using Razor, JavaScript, HTML and CSS. 
* Increasing familiarity with Bootstrap4.
* Propertly setting up unique url routing and following naming conventions within .NET for a larger project.
* Using references to color variables in CSS to ensure consistency in design across a website. 
