# Social-API

## Description


It is an API for a social network web application where users can share their thoughts, react to friends’ thoughts, and create a friend list. You’ll use Express.js for routing, a MongoDB database, and the Mongoose ODM. In addition to using the [Express.js](https://www.npmjs.com/package/express) and [Mongoose](https://www.npmjs.com/package/mongoose) packages, you may also optionally use a JavaScript date library of your choice or the native JavaScript `Date` object to format timestamps.

## User Story

```md
AS A social media startup
I WANT an API for my social network that uses a NoSQL database
SO THAT my website can handle large amounts of unstructured data
```

## Acceptance Criteria

```md
GIVEN a social network API
WHEN I enter the command to invoke the application
THEN my server is started and the Mongoose models are synced to the MongoDB database
WHEN I open API GET routes in Insomnia for users and thoughts
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete users and thoughts in my database
WHEN I test API POST and DELETE routes in Insomnia
THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list
```

## Mock Up

The following animations show examples of the application's API routes being tested in Insomnia.

The following animation shows GET routes to return all users and all thoughts being tested in Insomnia:

[Demo of GET routes to return all users and all thoughts being tested in Insomnia.](https://watch.screencastify.com/v/ZxjCTf9XqkMCVun4C397)

The following animation shows GET routes to return a single user and a single thought being tested in Insomnia:

[Demo that shows GET routes to return a single user and a single thought being tested in Insomnia.](https://watch.screencastify.com/v/ha9I4UujTUUiFnOF2WZk)

The following animation shows the POST, PUT, and DELETE routes for users being tested in Insomnia:

[Demo that shows the POST, PUT, and DELETE routes for users being tested in Insomnia.](https://watch.screencastify.com/v/7L3tDe2jpzc9KbnDHbN7)

The following animation shows the POST, PUT, and DELETE routes for thoughts being tested in Insomnia:

[Demo that shows the POST, PUT, and DELETE routes for thoughts being tested in Insomnia.](https://watch.screencastify.com/v/Bo8YfLIDTUwOnpO7kk5B)

In addition to this, your walkthrough video should show the POST, PUT, and DELETE routes for thoughts being tested in Insomnia.

The following animation shows the POST and DELETE routes for a user’s friend list being tested in Insomnia:

[Demo that shows the POST and DELETE routes for a user’s friend list being tested in Insomnia.](https://watch.screencastify.com/v/NbihwMOLlOXahV3liuFa)

[walkthrough video to POST and DELETE routes for reactions to thoughts being tested in Insomnia.](https://watch.screencastify.com/v/yXV18LbvjMkHT9shznDb)

## Getting Started

Be sure to have MongoDB installed on your machine. Follow the [MongoDB installation guide on The Full-Stack Blog](https://coding-boot-camp.github.io/full-stack/mongodb/how-to-install-mongodb) to install MongoDB locally.


##Review
[URL of GITHUB repo](https://github.com/PROGRAMER122223/Social-API.git)