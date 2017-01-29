# workshop-APIs

In this workshop we'll be using the GitHub API in order to practise:
- Making HTTP Get requests
- Callbacks
- Working with large amounts of JSON-formatted data
- DOM manipulation

## Remember

We are using browser-friendly vanilla JavaScript. No promises, and no ES6 syntax!

## Getting started

1. Clone this repo and open in your text editor

2. Open index.html in your browser. You'll find a template with space for some info which you can find on your GitHub profile. Your job is to fill it with data using the GitHub API :)


## GitHub API

You can find the API docs [here](https://developer.github.com/v3/).

You can make calls to the GitHub API without an API key. However, the rate limit for _unauthorized_ requests is quite low at 60 calls per hour (per IP address).

To increase your rate limit you can [create an access token](https://help.github.com/articles/creating-an-access-token-for-command-line-use/). **Note that this is NOT good practice: access tokens (which are not the same as API keys) should always be kept private and never, ever pushed up to GitHub! Use your access token for this workshop only and do not share with anyone else**.

Try and complete Task 1 with at least 2 tests. That's the most important part of today's workshop. The other parts should be treated as extra challenges.

## Task 1

Use everything you've learned about APIs and callbacks to make a call to the GitHub API that gets details of _your_ GitHub repos.

Use the response to populate your HTML template down to the horizontal line.

You don't have to stick to the template I've prepared for you. By all means, you can choose to show different data from the API and to present it any way you like.

Try and write a couple of tests. A tests folder with a link to QUnit is set up for you.


-----


## Challenge 1.0: make another API call

Go back to ```index.html``` and remove the commented-out part of the page. This is for showing of details of one of your repos. It can be the first repo in your list, the last, the most popular, or whichever one you like.

How could you go about getting the relevant data from the GitHub API?

How might you have to adapt your code from the first exercise?

What different ways can you think of structuring your code?

Try and at least come up with an **idea** of how you might do this. It will be very useful when you come to your end-of-week project!

## Challenge 1.2: even more API calls

What other data might you want your application to show and what API calls would you need to make?

Does the structure of your code (after challenge 1.0) allow for you to easily accommodate these changes?

What problems can you foresee?

## Challenge 2: adapt your app for different purposes

At the moment, your app is just getting data about one GitHub user. But what if you wanted to use it to compare everyone from Founders and Coders? Or to get data about a custom GitHub user? How might you adapt your application for this purpose?


## Challenge 3: 100% code coverage

How could you test your API calls? Try and write some tests for the different parts of your application. Aim for full test coverage.

-----

## Solution!

There are many ways to go about this challenge. To see a working solution (to part 1 + challenge 1) pull down the branch "solution" and check out solution.js (and the tests!).
