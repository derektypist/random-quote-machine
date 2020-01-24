# Random Quote Machine

Welcome to Random Quote Machine.  The purpose of this project is to have a functionality similar to this:
https://codepen.io/freeCodeCamp/full/qRZeGZ

## UX

Information Architecture - Quote is structured into text and author.

    Text                                                        Author
    "Hope smiles from the threshold of the year to come,        Alfred Lord Tennyson
    whispering.  It will be happier."
    "O, wind, if winter comes, can spring be far behind?"       Percy Bysshe Shelley
    "Spring is nature's way of saying, 'Let's Party!'""         Robin Williams
    "Sweet April showers do spring May flowers."                Thomas Tusser
    "As full of spirit as the month of May, and as              William Shakespeare
    gorgeous as the sun in Midsummer."
    "There are two seasons in Scotland: June and Winter."       Billy Connolly
    "People don't notice whether it's winter or summer          Anton Chekhov
    when they're happy."
    "Summer Afternoon---summer afternoon; to me those have      Henry James
    always been the two most beautiful words in the English
    language."
    "Autumn is a second spring when every leaf is a flower."    Albert Camus
    "In seed time learn, in harvest teach, in winter enjoy."    William Blake
    "Winter is the time for comfort, for good food and
    warmth, for the touch of a friendly hand and for a talk     Edith Sitwell
    beside the fire: it is time for home."
    "Thank you for your kind words"                             Daphne Pink
    "It looks as though you had a great time Derek"             Andrea Harrison
    


    






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
    

    

