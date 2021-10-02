Andy Xie

This repo is a clone of https://github.com/nelaturuk/education_pathways.

Activity 1 Screenshot of Docker installation and version check.
![Activity 1](/screenshots/activity_1_docker_install.png)

Activity 2 Screenshot of the cloned Educational Pathways repo.
![Activity 2](/screenshots/activity_1_screenshot.png)

Activity 3 Screenshot of the docker build.
![Activity 3](/screenshots/activity_3_docker_build.png)

Activity 4 Screenshot of Educational Pathways running on localhost:5000 and the docker image for it.
![Activity 4](/screenshots/activity_4_localhost.png)
![Activity 4](/screenshots/activity_4_running.png)

# CARTE Education Pathways

## Description
Welcome to CARTE's in-development tool for course selection at UofT. Education Pathways allows for more intelligent course searching, by matching not just the terms you search, but ones relevant to them. The more terms you search for, the more relevant your results will be! Even try searching across disciplines for the courses that best cover each.

Whatever year you are looking for, Education Pathways will also suggest courses in earlier years that will best help you to prepare. To get the most out of this, try searching for courses in a later year and see what is suggested for your current one.

We are looking for feedback to improve Education Pathways and make it more useful for students. If you have ideas or suggestions, please email us!

## Setup Instructions

### With Docker



## Repository files:

`./Procfile ./wsgi.py` *tells gunicorn how to run the program*

`./environment.yml  ./requirements.txt` *specifies python requirements for anaconda and pip respectively*

`./__init__.py` *main flask code*

`./readme.md` *this file*

`./resources:` *contains datasets used in the program*

`course_vectorizer.pickle df_processed.pickle`

`course_vectors.npz       graph.pickle`

`./static:` *contains any static elements of the webpage, in this case just the CARTE logo*
`CARTE_logo.jpg`

`./templates:` *contains flask templates for rendering HTML*

`_formhelpers.html course.html       index.html        results.html`
