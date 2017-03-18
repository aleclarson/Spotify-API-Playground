# Spotify API Playground


These examples cover:

* Successful OAuth
* Fetching and displaying user profile data
* Fetching and displaying users top tracks
* Fetch and display current users top tracks


## Installation


#### Spotify 
You must have a Spotify account (free or premium)

#### Node.js Setup
These examples run on Node.js. On [its website](http://www.nodejs.org/download/) you can find instructions on how to install it. You can also follow [this gist](https://gist.github.com/isaacs/579814) for a quick and easy way to install Node.js and npm.

Once installed, clone the repository and install its dependencies running:

    $ npm install

	
## Running the Playground
In order to run the Playground, CD to the the 'API Playground' directory in the folder you cloned to and run app.js with node

    $ cd c:/API-PG/API Playground
    $ node app.js

Then, open `http://localhost:8888` in a browser.

### Using your own credentials
The examples contains a working client ID and secret key. Note, however, that they might be rate limited if they are used frequently. If you are planning to create an application, it is recommend you register your app and get your own credentials instead of using the ones in this project.

Go to [My Applications on Spotify Developer](https://developer.spotify.com/my-applications) and create your application. For the examples, we registered these Redirect URIs:

* http://localhost:8888 (needed for the implicit grant flow)
* http://localhost:8888/callback

Once you have created your app, replace the `client_id`, `redirect_uri` and `client_secret` in the examples with the ones you get from My Applications.
