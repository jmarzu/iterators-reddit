#Iterators with Reddit

Similar to the Google Shopping deliverable, we'll be analyzing data using a real dataset from the subreddit `/r/javascript`.

You can view the live version here:
http://www.reddit.com/r/javascript.json

##Getting Started

* Fork and clone this repository
* Run `npm install` to install dependencies
* Create your solutions under `src/js/reddit.js`
* Run `node src/js/reddit.js` to run the file
* Run `npm run lint:js` to lint your code

## Deliverables

Obtain the following data by using the four array iterators.

1. `forEach` -  `console.log` all post titles
2. `map` - Print an array of permalinks, append `http://reddit.com` to each so that they contain full `http://` path to reddit
3. `filter` - Filter the posts that contain actual text in the `selftext` key
4. `reduce` - Use reduce to obtain the sum of all the `score` values across all posts in the dataset
