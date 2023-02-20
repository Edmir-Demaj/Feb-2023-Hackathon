# Feb 2023 hackathon

# Friends of Earth
![Screenshot of the hero section](documentation/readme-images/hero-section.png)

# Project Documentation
## Welcome to [Friends of Earth](https://feb-2023-hackathon.herokuapp.com/)

## Mission
The mission of our website is to act as an NGO directory, where users can find information about many different NGOs worldwide, and be directed to more information about each one if they choose. It is easy it is simple, all in one website. The present documentation will provide information to understanding the core design principles that enabled the development of the project. More specifically, details regarding the UX/UI development, application testing and deployment, bug fixes and the planned future features for the project.

## [Link to website](https://feb-2023-hackathon.herokuapp.com/)
---
# Table of Contents

- [The Story](#the-story)
- [Scrum Master](#scrum-master)
- [User Experience (UX)](#user-experience-ux)
    - [Target audiance](#target-audiance)
    - [User Stories](#user-stories)
- [Wireframes](#wireframes)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Design choices](#design-choices)
    - [Colour palette](#colour-palette)
    - [Font](#font)
- [Deployment](#deployment)
- [Bugs](#bugs)
- [Testing](#testing)
- [Credits](#credits)

# The story

This project is part of the Code Institute February 2023 Hackathon. We researched World NGO Day and found that it aims to appreciate different NGOs across the world, and so decided that having a directory where users can browse different NGOs, would help users to find more specific information or bring awareness to different NGOs. It can also help users to find NGOs which they would like to be a part of or contribute towards.

**Repository:** [https://github.com/AdamBoley/Feb-2023-Hackathon](https://github.com/AdamBoley/Feb-2023-Hackathon)

**Final website:** [https://feb-2023-hackathon.herokuapp.com/](https://feb-2023-hackathon.herokuapp.com/)

# Scrum Master

As a Scrum Master our team had [Edmir Demaj](https://www.linkedin.com/in/edmir-demaj-42a501196/). As a Scrum Master my duties are:
- Work on Project idea together with the team.
- Plan how team members will work on this project.
- Keep notes for any suggestions, ideas, and changes on the project. 
- Find out which technologies will be used on this project to involve the whole team.
- Organise meetings via Slack for the team at suitable times for everyone.
- Provide a summary after each call on our Slack channel.
- Create and assign tasks to team members.
- Check the progress of each one at the end of day.
- Check the progress of the project to deploy before the deadline.
- Create a sprint goal for user stories, create To Do tasks and check their progress.
- Assist in any problems during project development.
- Make sure the product achieves its final goals.

Since this project is part of Hackathon February 2023 and the time is very limited to have a detailed plan, progress and final report all I could do is to implement all duties mentioned above. Below find the project board built on GitHub and the Sprint Goal made for user stories.

<details><summary>Project board on GitHub</summary>
<img src="static/project-img/project-board.png">
</details>
<details><summary>Sprint Goal</summary>
<img src="static/project-img/scrum-board.png">
</details>

---

# User Experience UX

## Target Audiance

This project is aimed at anyone who wants to know more about NGOs worldwide. If the user wants to find out more or contribute directly to a specific NGO, they can find the link to take them directly to the NGO website itself.

## User Stories

- To immediately determine the purpose of the site, so can quickly decide whether or not to stay.
- To be able to see a clear contrast between foreground and background.
- To be able to easily access the site on a variety of devices - desktop, tablet, mobile.
- To be able to browse a variety of different NGOs in one place.
- To be able to read an overview of each NGO, e.g., purpose, founder and date it was founded, current director, location, etc.
- To be able to visit each NGO's website directly (opens in new tab).
- To be able to get random NGO's if i dont know what to search for.
- To find out information about World NGO day and when it is.
- To be able to search by name an NGO.
- To be able to contact someone from team if i would like more detailed inormation.
- To be able to leave my message or inquiries might have as user.
- To be able to understand what is about this site.
- To be able to easily access contact details or social pages.

# Wireframes

Created using [Figma](https://www.figma.com/) (click to expand)

<details><summary>Homepage</summary>

![Homepage wireframe](documentation/wireframes/homepage.png)
</details>

<details><summary>About page</summary>

![About page wireframe](documentation/wireframes/about-page.png)
</details>

<details><summary>NGOs page</summary>

![NGOs page wireframe](documentation/wireframes/ngos-page.png)
</details>

<details><summary>Contact page</summary>

![Contact page wireframe](documentation/wireframes/contact-page.png)
</details>

# Features

### Logo

- Features an image of the Earth above the site name, 'Friends of Earth'.
- Uses green colours in-keeping with the site colour scheme and tying to nature and the Earth.

![Logo](documentation/design/logo.png)

### Navigation menu

- At the top of every page allows for easy site navigation.
-  Makes it clear to the user how they can access different pages or to return to a previous page without relying on browser forward/back buttons.

### Search bar

- Allows users to search for a specific element on the website, e.g., if they are looking for information on a particular NGO.

### Homepage

- Displays a slideshow of three random NGOs from the directory, above a button to check out more NGOs which takes the user to the directory page. This is above the fold so it is the first thing a user will see when visiting the site.
- Slideshow is over a hero image of a landscape, which clearly relates to the site name 'Friends of Earth' and also to environmental NGOs.
- It also features a short explanation of World NGO Day - when it is and what NGOs are.

### Directory (NGOs) page

- Each page features a brief overview of six different NGOs, including:
    - Name
    - Logo
    - Brief description
    - Internal link to more information on our site
    - External link to the NGO's site (opens in a new tab so the user can easily navigate back to our site)
- The user can navigate between the directory pages by using the 'first', 'previous', 'next' and 'last' buttons at the bottom of the screen.

### Contact page

- Features a short description of reasons a user might want to get in touch with us.
- Provides various contact details - phone number, email address and Google Maps location, as well as links to social media sites.
- User can fill out a form with their contact details and message, which will go to our database and allows us to get in touch with them to reply.
- Contact details and form are over a hero image of the Earth as seen from space, again relating to the site name 'Friends of Earth' but a different take on it, to provide variety and also to focus more on the worldwide/global aspect of the site.

### Random page

- Takes the user to a page with information about a random NGO in our database.

### About us page

- Explains who we are and why our website was created, along with images relating to different types of NGO.

### Footer

- Features Copyright, team name and social media links to feature at the bottom of every page.

### Favicon

- Favicon is generated using favicon.io.



# Function



This section documents how Django was used to set up the project

# Technologies Used

### Languages:
  * Python, for basic Django framework, database management
  * HTML structure of the site.
  * CSS style site


### Tools and Frameworks
  * GitHub, host platform and version control
  * Gitpod, IDE write and edit code
  * Django, Python Framework
  * Bootstrap, CSS framework
  * Figma, create wireframes

# Design choices

## Colour palette

The chosen colour palette is symbolic of the Earth and uses complementing blues, green, grey and white:
![Colour palette](documentation/design/colour-palette.png)

## Font
The chosen font is Jomolhari & Montserrat. Jomolhari is used for Nav links and MOntserrat for content.
The font is white over the darker background of the header and footer, and dark over white and light backgrounds in the main body of each page to make sure it is accessible and can be easily read by users.

# Deployment
- This site was developed in IDE (Gitpod)[https://www.gitpod.io/] and deployed to (Heroku)(https://www.heroku.com/)]
- GitHub is used for version control and hosting platform for the site.
- It was built using the Django framework.
- The site was developed by previewing the site in the browser through Port 8000 in Gitpod by running the command `python3 manage.py runserver` in the terminal.

Changes and entries to the workspace were then committed and pushed to this Github repository.
### Setting up the project in Gitpod workspace:
1. Install django by running the following command `pip3 install Django`
2. Install gunicorn for running the deployed website `pip3 install gunicorn`
3. To install postgres to support the database `pip3 install dj_database_url pyscopg2`
4. Install any other required libraries by running similar commands and add them to a requirements.txt file so that Heroku will install them at deployment. This is done by running `pip3 freeze --local > requirements` in the terminal and can be run again when necessary to add further libraries.
5. Create your Django project by entering the following command: `django-admin startproject < YOUR PROJECT NAME >`
6. To create a django app, run `python manage.py startapp < YOUR APP NAME >`
7. Add the name of the newly created app to "INSTALLED_APPS" in settings.py.
8. Development of apps can begin from here.
### Deploying to Heroku
1. Once logged into Heroku, choose the option 'Create App'.
2. Attach the database in the Resources tab in Add-ons. Search for 'Heroku Postgres' and add.
3. In your workspace, create an env.py file which will store environment variable and add it to .gitignore so as not to expose any sensitive information publicly in Github.
4. Store your 'SECRET_KEY' and 'DATABASE_URL' here and import into settings.py
5. In Heroku, under settings, choose 'Reveal Config Vars and add your 'SECRET_KEY' and 'DATABASE_URL'.
6. Migrate to the database in Gitpod using `python manage.py makemigrations` followed by `python manage.py migrate`
7. Add your Heroku app URL to "ALLOWED_HOSTS" in settings.py.
8. Create a Procfile in the top level of the directory and add `web: gunicorn projectname.wsgi` so Heroku knows how to run the project.
### Initial deployment:
1. Push any changes to Github after connecting your Heroku app to your repository.
2. Add DISABLE_COLLECTSTATIC with a value of 1 to Heroku config vars.
3. Select Github in Deployment method and choose 'Deploy branch' under Manual Deploy, ensuring your main branch is chosen.
### Subsequent deployments:
1. For subsequent deployments, I chose to 'Enable Automatic Deploys' which meant that anytime changes were pushed to my main Github branch, the Heroku project redeployed.
2. For the final deployment, ensure you have a dependency to handle your static files. I used whitenoise, install with `pip install whitenoise` and add to MIDDLEWARE in settings.py and change STATIC_FILES_STORAGE variable to `STATICFILES_STORAGE = 'whitenoise.storage.CompressedStaticFilesStorage'`
3. Remove DISABLE_COLLECTSTATIC config var.
4. Change DEBUG to False in settings.py
5. Push changes and deploy.

# Bugs
All bugs are fixed, there are no bugs left to fix. 

# Testing
A number of manual tests were carried out on this porject:
- All nav links on nav bar work.
- Search bar works showing the results.
- External links work.
- Data from database is provided to user.
- Contact form send data to database.
- Website has been tested with google lighthouse and the result is as below.

![Google lighthouse testing](documentation/readme-images/testing.png)

# Credits

- All images were taken using free copyrights sites [Pexels](https://www.pexels.com/) and [Unsplash](https://unsplash.com/)
- Content on home page was taken from [National Today](https://nationaltoday.com/world-ngo-day/)
- Data to populate database with NGOs was taken from [Google](https://www.google.com/)

# Acknowledgements

- Thank you to all the team member for the hard work and cooperation.
  - Edmir Demaj - [GitHub Link](https://github.com/Edmir-Demaj)
  - Maria Jones - [GitHub Link](https://github.com/mariacjones1)
  - Adam Boley - [GitHub Link](https://github.com/AdamBoley)
  - Alexander Glemme - [GitHub Link](https://github.com/alexanderglemme)
  - Maximiliane Kaempffer - [GitHub Link](https://github.com/Maximiliane-K)
  - Liam Pewton - [Github Link](https://github.com/lpewton)
  - Linus Berger - [GitHub Link](https://github.com/Linber93)


# Thank you !
 [Back to Top](#table-of-contents)
 
  