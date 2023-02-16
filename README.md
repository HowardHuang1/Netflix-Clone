# Neflix Clone

Netflix Clone is a duplicate of the Netflix movie and TV show streaming app Netflix. It supports functionality for movies in 8 categories: Netflix Originals, Trending Now, Top Rated, Action, Comedy, Horror, Romance, and Documentaries. Netflix Clone also displays trailers for each movie.

![UI](https://github.com/HowardHuang1/Netflix-Clone/blob/main/Netflix%20UI.png)

The app primarily consists of a React frontend which makes calls to a TMBD API that provides the banner image, movie images, movie names, and trailers.

# How To Use

To clone and run this application, you'll need [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
$ git clone https://github.com/HowardHuang1/Netflix-Clone.git
# Go into the repository
$ cd Netflix-Clone
# Install dependencies
$ npm install
# Run the app
$ npm start
```

Packages and presets will be loaded automatically from `package.json`.

This will fully render the Netflix-Clone website with a random movie with its description displayed in the banner. When the user clicks on a movie, a request will be sent to the TMBD API and the corresponding trailer will be returned to be displayed on the UI.
