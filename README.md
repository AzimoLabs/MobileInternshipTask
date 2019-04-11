# Internship task
The goal of this programming task is to check how comfortable you are with Android or iOS code. Please keep in mind that this is not only for us to review your experience and skills, but also for you. We firmly believe that the ability to create described application will be useful when looking for a future job as an Android or iOS developer.

Code which you will create covers some basic skills which are useful in mobile software developer:

* Networking, connecting with REST API
* Dealing with data: caching it (optional), processing, displaying it in the user interface
* Navigation between screens
* Code/project structure, design/architectural patterns
* You will get extra points for automate tests checking your project (unit tests or any of user-interface tests).

During the review process, **we won’t pay much attention to UI/UX** (until you ask otherwise). Feel free to use system components without additional styling. Please keep your user interface readable. 

## How to submit your code
1. Fork this project,
2. Work on the code on your repository,
3. When it’s ready, just send us a link or create Pull Request via Github interface.

If you don’t want to share your code publicly, send us the entire project as a zip file via email.

We’ll wait for your response until May 4th. Feel free to ask any questions at mirek@azimo.com.

# Task

## Github API client

Please create Github client app which connects to public Github REST API available here: https://developer.github.com/v3/. None of the requested methods require authentication. 
*It is also ok if you decide to build simple REST client for any other API you pick (can be your personal project).

App has 3 screens:
1. "Select user" screen (containing text field and button). User is able to type Github nickname.
    1. If nickname exists in Github API, move forward to screen 2.
    2. If nickname doesn’t exist, show an error.
2. "List of repositories" screen where we can see all repos for given nickname.
    1. When user clicks on list item, app opens repository details screen.
3. "Repository details" screen. Shows some data about given repository. 


