# NerdFinder

by Rich Budek 03/23/2018

Project location for files   [richbu.github.io](https://github.com/RichBu/FriendFinder)
on-line view location for viewing   [heroku](https://ancient-crag-39294.herokuapp.com/)

Description:
This is an demonstration of using Node.js as a backend, linking to a frontend.  These pages are
send from the server to the client's browser.  The user's answers are stored in a JSON object
that is temporarily stored on the session's public folder.

In addition, there is code to demonstrate the usage of bringing in live video on the page.

There is input validation on the user name and the photo name.

Starting up, simply move to the website:
The web page opens with an intro page:
![Opening Screen](/app/assets/screen_caps/NF_main.png)

Hitting the survey button brings the user to the next page.
![Starting the Survey](/app/assets/screen_caps/Nerd-Quest_01.png)

The user should type in their user name.  if the user has a local image file, it can
be selected:
![Inquirer menu](/app/assets/screen_caps/Nerd-Quest_01.png)

To view live video inside of the browser, the user can click the camera
button and live video will be shown in the pop-up window.  Because of
current hosting plan, the images are NOT uploaded and it is for
demonstration purposes only.
![Inquirer menu](/app/assets/screen_caps/NF-Video.png)

After a match is found, a matching nerd is displayed.
![Inquirer menu](/app/assets/screen_caps/NF-Match.png)


Technolgies used:
1. Node.JS
2. Javascript for program functions on the backend
3. node-express to establish routing for the survey, home page, and the posting
4. Materialize for the CSS of the front end web page.

Internal design
1. Web pages are served up from the NODE.js program running on the server.
2. The current hosting plan does not allow uploading of images for free.

Left to do:
1. Host on a web page that allows image uploading.



