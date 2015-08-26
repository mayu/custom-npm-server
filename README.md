# custom-npm-server

# Goal
I'd like to have a private npm repository system for non javascript packages. This would mean two things: 

1. A npm like rest api system
2. An node.js command line prompt to communicate to the rest api (similar to the npm command).


If the code checks out, I'd love to open source it and show you as the primary coder!

# Specifics
Since I want all of npm's current functionality without connect to the real npm, I'm thinking perhaps using something like the npm module `sinopia` with some massaging to prevent attempts to connect to the real npm could be all we need. Do some research on other private npm systems, like sinopia, or even perhaps Atom's 'apm'.

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
