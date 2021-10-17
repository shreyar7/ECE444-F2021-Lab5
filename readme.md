# CARTE Education Pathways



## ECE444 Lab 5 Steps

Name: Shreya Rajendran

This repo is a clone of https://github.com/nelaturuk/education_pathways.

### Activity 1 - Screenshot of cloned repo:

![image](https://user-images.githubusercontent.com/90438521/137572037-6436e14c-94b0-4ac8-93dd-34cca2ebf35f.png)


### Activity 2-5 - Screenshot of Home page:

![index page](https://user-images.githubusercontent.com/90438521/137638685-4c3f46e7-ae34-4c32-a4c4-b005907da344.PNG)


### Activity 2-5 - Screenshot of Results page Form:

![search page form](https://user-images.githubusercontent.com/90438521/137638714-c3a03e7d-897e-4f53-9a5a-537f57aed22e.PNG)


### Activity 2-5 - Screenshot of Results page Table:

![search table](https://user-images.githubusercontent.com/90438521/137638739-1514fa89-441a-4557-83d0-5c542deeb0bb.PNG)


### Activity 6 - Comparison of old UI and new styled UI:

In the old table pre-styling, the columns weren't clearly indicated by lines so, it was not very easy to read. However, in the new table, colors matching the overall scheme of the page have been used to clearly show borders and the header row with appropriate font color having a good contrast with the background color. Additionally, making the header row position sticky is also very helpful for scrolling through a large number of results, thus improving the UI/UX.


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
