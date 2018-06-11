# Project Overview

In this project is given a web-based application that reads RSS feeds. The original developer of this application clearly saw the value in testing, they've already included [Jasmine](http://jasmine.github.io/) and even started writing their first test suite! Unfortunately, they decided to move on to start their own company and we're now left with an application with an incomplete test suite. That's where you come in.

## Why this Project?

Testing is an important part of the development process and many organizations practice a standard of development known as "test-driven development". This is when developers write tests first, before they ever start developing their application. All the tests initially fail and then they start writing application code to make these tests pass.

Whether you work in an organization that uses test-driven development or in an organization that uses tests to make sure future feature development doesn't break existing features, it's an important skill to have!

## What will I learn?

I will learn how to use Jasmine to write a number of tests against a pre-existing application. These will test the underlying business logic of the application as well as the event handling and DOM manipulation.

# The tests:

1.  Loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty.
2.  Loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty.
3.  Write a new test suite named `"The menu"`.
4.  Ensure the menu element is hidden by default. You'll have to analyze the HTML and the CSS to determine how we're performing the hiding/showing of the menu element.
5.  ensure the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.
6.  Write a test suite named `"Initial Entries"`.
7.  Ensure when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.
8.  Write a test suite named `"New Feed Selection"`.
9.  Ensure when a new feed is loaded by the `loadFeed` function that the content actually changes.

- No test should be dependent on the results of another.
- Callbacks should be used to ensure that feeds are loaded before they are tested.
- When complete - all of tests should pass.

# How to run the Project

- Clone the repository using `git clone https://github.com/Galiant/feed-reader-testing.git`
- Open index.html in your browser.
- Once loaded, test results should be displayed at the bottom of the page.

# Technologies Used

- Jasmine
- jQuery
- HTML5/CSS3
