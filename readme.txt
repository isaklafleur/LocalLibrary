Then run the application.
On Windows, use this command:
SET DEBUG=LocalLibrary:* & npm start
SET DEBUG=LocalLibrary:* & npm run devstart // with nodemon
On Mac OS X or Linux, use this command:
DEBUG=express-locallibrary-tutorial:* npm start
Then load http://localhost:3000/ in your browser to access the app.

Note: You could also start the app just using the npm start command. Specifying the DEBUG variable as shown enables console logging/debugging. For example, when you visit the above page you'll see debug output like this

Fortsätt här: https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Displaying_data