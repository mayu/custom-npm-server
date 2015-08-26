# custom-npm

# Goal
This project is designed to make it easy for people to create their own npm style package repositories, including non javascript files (like markdown).

This would mean two things: 

1. A npm like rest api system that installs easily on heroku, docker, or any other quick install system
2. A command line prompt to communicate to the rest api (similar to the npm command) (use node.js to build this tool).

# Specifics
Since we need all of npm's current functionality without connecting to the real npm, we can perhaps use something like the npm module `sinopia` with some massaging to prevent attempts to connect to the real npm could be all we need. Do some research on other private npm systems, like sinopia, or even perhaps Atom's 'apm'.

# Usage

## Terminal

```

// make your own terminal prefix easily
bpm install 2015-remix-tracklist --save

// Have the ability to login to this repository
bpm login djduo

// Have the ability to publish to this repository
bpm publish remixer

// Have the ability to search this repository
bpm search remixer
