# GIF Bot from scratch!

The goal of this tutorial is to make a Messenger Chatbot that can parse and respond to a user using GIFS and text. The code will be written from scratch; no shortcuts will be used to do NLU and other stuff.

Alternatively, you can fork this repo and run using from step 00.

## Pre-requisites
- [ ] Knowledge of JavaScript
- [ ] an (Openshift)[https://www.openshift.com/] account.
- [ ] A Giphy API Key or get the public one from [here](https://github.com/Giphy/GiphyAPI)

### Warning
I encourage the use of Openshift just because they allow you to run an app for absolutely no cost at all. Azure app services is a good alternative as they are free, but requires you to input your credit card details and might be limiting for people who do not have one. Heroku is another alternative; however, their apps only run for 20 hours a day.

## How do I follow along with the tutorial?

Code will be written in the `./code/` directory. `index.js` and `package.json` will be in the root folder to enable easy deployment.  The tutorial text is placed in `./tutorial/`. It is numbered as follows:

* README - Accounts checklist.
* 00 - Setting up your repository with boilerplate code
* 01 - Setting up your Openshift app
* 02 - Setting up a connection to Facebook Messenger
* 03 - Hello world: Parsing user input
* 04 - GIF world: Sending users GIFs!
* 05 - NLP world: Extracting important words from user input
* 06 - GIF + NLP world: Sending relevant GIFS to your users
* 07 - Future work