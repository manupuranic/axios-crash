# Axios Crash Course

> These are the files for the YouTube Axios crash course.

"start.js" is just the event listeners and empty functions. "main.js" is the completed code

// Assignment questions
why do we need headers?

Headers have the information that needs to be sent to the servers everytime we make a request. For example, content-type, authorization tokens etc.

What is axios?

Axios is a javascript library that helps in establishing communication between the frontend and the backend (servers).

Common problems faced when making a network call:

1. baseurl is either wrong or expired

2. route mentioned is not found in the server (404)

3. payload (body) is either sent in the wrong way or shouldn't have been sent.

4. errors are not caught and addressed.

To solve them:

1. use post man to check if the url is correct.

2. always catch the errors while making the request

3. check if the body is not stringified and is in json format.
