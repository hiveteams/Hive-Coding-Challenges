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
to providing our users with unexpected delights and easter eggs.

With this challenge, we want you to go wild with whatever
your "specialty" is. Front-end whiz? Let's see some impressive functional
animations and responsive css. Obsessed with back-end scalability? Show us why your app works
the same at 2 users as it does at 20,000.

Take what you feel you're most skilled at and let it shine through with whatever
personal flair you want on this challenge.


### Functional spec

The features of the app should include:
* User registration and login
* Upon registration, user should be added to "global" room
* Users should be able to "direct message" any other registered user
* UI should have a basic message box for chatting
* UI should be responsive (mobile-friendly)

**The front-end UI and UX is totally up to you**. Get creative here. Add any features
you feel might be useful or cool to have as a user. Don't hold back at all - the idea behind this exercise is to give you freedom to build cool/unique features on top of a simple concept.


Technical spec
--------------

At Hive we use [Meteor](docs.meteor.com/#/full/) - for this challenge you'll be using it as well. Even if you're
not familiar with it, we feel it's important to be able to pick up on new technologies quickly - and Meteor
is pretty easy to get up & running with. Also it comes with Accounts for users baked in, so it'll make the challenge
a bit easier.

The [Meteor guide](http://guide.meteor.com/) is an **excellent** source of Meteor best practices and information as well.

If you're entirely new to Meteor, try [creating your first app](https://www.meteor.com/tutorials/blaze/creating-an-app) to get a hang of things before moving on.

### Back-end
Meteor includes all you'll really need for back-end. If your focus/specialty is back-end, make sure your app is secure, performant and follows best practices. Meteor is built on node.js and utilizes [fibers for a synchronous code style](https://www.eventedmind.com/feed/nodejs-introducing-fibers).

### Front-end
Hive is built using Blaze. We don't have a preference on what front-end library you use here, so stick with whatever is most comfortable for you, or challenge yourself if you're up for it.

##### Blaze (Handlebars-style templating)
Meteor uses [Blaze](https://www.meteor.com/blaze) by default; Blaze is essentially a Meteor-flavored version of Handlebars templating. It's great for quickly building/prototyping, but requires a bit of discipline to keep clean.

##### React
[React](https://facebook.github.io/react/) is supported as a front-end library with Meteor. Meteor provides a basic example of using [React with Meteor](https://www.meteor.com/tutorials/react/creating-an-app) if you're not familiar with it already.

##### Angular
As of Meteor 1.2, Angular is also supported. While this is our least preferred option, it is acceptable - [check out a sample Meteor app + tutorial](https://www.meteor.com/tutorials/angular/creating-an-app) if you need help getting started.

#### Styling
Feel free to use one of the popular CSS frameworks for styling if you'd like, but if your specialty is creating beautiful html/css then don't limit yourself to a framework!

Host it!
--------

Meteor used to provide free hosting for Meteor apps, but now you'll need to do a bit more work to get it live. You can use [Meteor Up] (https://github.com/zodern/meteor-up) to host it on any box (e.g. on AWS, Heroku, Modulus).
