# Location Server


## Running

You must have [npm](https://www.npmjs.org/) installed.
From the root project directory run these commands from the command line:

	npm install

This will install all dependencies.

To build the project, first run this command:

	npm start

This will perform an initial build and start a watcher process that will update bundle.js with any changes you wish to make.
This watcher is based on [Browserify](http://browserify.org/) and [Watchify](https://github.com/substack/watchify).
It transforms React's JSX syntax into standard JavaScript with [Reactify](https://github.com/andreypopp/reactify).

To run the app in your browser, start the web server

	node server.js

Go to [http://localhost:8080](http://localhost:8080)


## Configure
 
 Go to `Settings->url` and set it to `http://<server.ip.address>:8080/locations`.


## Testing purposes only (unavailable in release version)

If you wish to prevent autoSync from being recorded to the server (using cell service).
	Set `Settings->autoSync` to `false`.

Once you are on back wi-fi, click the **[Sync]** button on the `Settings` screen to upload the cached locations to the **Location Aware** server.


## Author

 Stacy E. Webb

