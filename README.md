# Random Quote Machine

Welcome to Random Quote Machine.  The purpose of this project is to have a functionality similar to this:
https://codepen.io/freeCodeCamp/full/qRZeGZ

## UX

Information Architecture - Quote is structured into text and author.

### User Stories

User Stories taken from https://www.freecodecamp.org/learn/front-end-libraries/front-end-libraries-projects/build-a-random-quote-machine

As a user, I can see a wrapper element with corresponding id="quote-box" 

As a user, within #quote-box, I can see an element with id="text"

As a user, within #quote-box, I can see an element with id="author"

As a user, within #quote-box, I can see a clickable a element with id="tweet-quote"

As a user, on first load, my quote machine displays a random quote in the element with id=text.

As a user, on first load, my quote machine displays the random quote's author in the element with id=author.

As a user, when the #new-quote button is clicked, my quote machine should fetch a new quote and display it in the #text element.

As a user, when the #new-quote button is clicked, my quote machine should fetch a new author and display it in the #author element.

As a user, I can tweet the current quote by clicking on the #tweet-quote a element.  This a element should include the "twitter.com/intent/tweet" path 
in its href attribute to tweet the current quote.

As a user, I expect the #quote-box wrapper to be horizontally centered.  Run tests with zoom level of 100% and page maximized.  Set height equal to width and the margin
to auto.

## Deployment

Initial Set Up

    git init
    git config --global user.name "Your Name"
    git config --global user.email you@example.com

Check Status at git status.

Remote Set Up and Initial Push

    git remote add origin https://github.com/derektypist/random-quote-machine
    git push --set-upstream origin master
    

    

