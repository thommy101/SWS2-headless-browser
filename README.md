This is the headless browser as used in the course Software and Web Securtiy 2.
The exercise is for the students to steal the administrator cookie.
This script acts as the administrator.
The password to pass this level can be passed in as well as a URL submitted by the student.
The URL contains an XSS attack that redirects to a cookiestealing script made by the student.
If the student did so correctly, this script will indeed visit the correct link.

This headless browser runs on NodeJS with the ZombieJS library.
Install NodeJS and NPM first.
Then "npm install zombie"
Then "node headless-browser"

You can pass in arguments using a socket.
The script outputs links that it visits.

If you have any improvements, feel free to do a pull request.