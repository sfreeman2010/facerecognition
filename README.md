# facerecognition
Face Recognition Front End - React app which detects faces in image url's

https://facerecog-smart-brain.herokuapp.com

This React App uses a PostgreSQL database to store user login, encrypted passwords and the amount of times they have used the face detection software.  See the backend for more details (uses NodeJS)

Once logged in, the user can then place a URL of an image.  The face detection software will then use an API call to Clairfai to detect the faces, returning the coordinates in the picture for us to use.  Parsing the JSON, we draw a box around the detected face and increment in our database the amount of faces detected by the user.

App was deployed to Heroku
