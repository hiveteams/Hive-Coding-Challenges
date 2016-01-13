Hive Coding Challenge
===========================

The Hive Coding Challenge is meant to be an exercise in understanding your workflow
through a small sample app. Please write and document code as if it were production
code and send us a link to the live application and a link to the Github (or Bitbucket, etc.) repository.


Messaging Application
---------------

Create a basic messaging/chat web app. The app should consist of one
"global" chat room and a series of "direct message" chats for
one to one chat between users registered on the app.

#### Not your average messaging app
Anyone can crank out a basic messaging app, but at
Hive we face challenges that range from giving our users
a good looking and responsive interface to being able to scale
to providing our users with unexpected delights or easter eggs.

With this messaging app, we want you to go wild with whatever
your "specialty" is! Front-end whiz? Let's see some impressive functional
animations. Obsessed with back-end scalability? Show us why your app works
the same at 2 users as it does at 20,000.

Whatever you feel you're most skilled at, let it shine through with whatever
personal flair you have on the messaging app.


### Functional spec

The features of the app should include:
* User registration and login
* Upon registration, user should be added to "global" room
* Users should be able to "direct message" any other registered user
* UI should (obviously) have a basic message box for chatting
* Chat rooms should have infinite scroll so a user can see message history
* Messages UI should have sender information, date/time information and message
text

The front-end UI and UX is totally up to you. Get creative here! Add any features
you feel might be useful or cool to have as a user.


Technical spec
--------------

At Hive we use [Meteor](docs.meteor.com/#/full/) - for this challenge you'll be using it as well.
It comes with Accounts for users baked in and is generally very quick to get started with.

The [Meteor guide](http://guide.meteor.com/) is an **excellent** source of Meteor best practices and information as well.

### Back-end
Meteor includes all you'll really need for back-end. If your focus/specialty is back-end, make sure your app is secure, performant and follows best practices

### Front-end
We recommend using [React](https://facebook.github.io/react/) as a framework on the front-end with Meteor. Meteor provides a basic example of using [React with Meteor](https://www.meteor.com/tutorials/react/creating-an-app) if you're not familiar with it already.
#### Styling
Feel free to use one of the popular CSS frameworks for styling if you'd like, but if your specialty is creating beautiful html/css then don't limit yourself to a framework!

Host it!
--------

When you’re done, host it somewhere. Using Meteor, you can [easily deploy it for free](https://www.meteor.com/tutorials/blaze/deploying-your-app). If you'd like to host elsewhere (e.g. on AWS, Heroku, Modulus, Google AppEngine, etc.) that's fine too.
