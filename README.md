# Mastering Your Inbox with the Gmail JavaScript API

Example of how to use the Gmail API in JavaScript.
Code to accompany the following article: http://www.sitepoint.com/mastering-your-inbox-with-gmail-javascript-api/

This example might be a starting point for those who want to integrate Gmail into their own web apps.


## Features

- Display summary of last 10 messages received by the user
- Open a modal to view a specific email
- Client templating with Mustache.js
- Format dates with Moment.js

## Use

- Run `bower install` to download mustache.js
- Put your own Gmail `clientId` and `APIKey` to config.js
- Run the http server or load `index.html` from the filesystem

### Roadmap

- Implement pagination
- Display attachments and preview
- Implement search, compose, reply, forward, trash
