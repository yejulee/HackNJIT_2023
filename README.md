# HackNJIT_2023 - WeBubble
YeJu Lee, Steven Packard

## Inspiration
We honestly didn't come up with an idea until 30 minutes after the Hackathon started. YeJu wanted to create a website that resembled something like the university's "missed connections", and we just went from there.

## What it does
It sends out a message to the server, casting a bubble underneath the textbox. The text floats for a bit and disappears 9 messages. It also attempts to filter out censored words.

## How we built it
* HTML to format the base of the website and CSS to design the website and its elements
* JavaScript to filter out bad words using library.
* Used Heroku for database

### Library used:
* https://www.npmjs.com/package/bad-words
* Node.js
* express.js
* mongodb
* socket.io

## Challenges we ran into
* Learning from scratch: Though YeJu had dabbled in HTML years before, she had to relearn from the beginning. She also taught herself CSS during the 25 hours of the Hackathon.
* Issues with picture: easily fixed with "background-size = cover"
* Difference in pixel size: use percentages instead of pixel
* Linking database to the code
* Learning socket.io

## Accomplishments that we're proud of
* Learning HTML and CSS and utilizing it in four hours
* Getting this far in the first hackathon (for YeJu at least)
* Figuring out how to make animations on websites
* Actually setting up the database

## What we learned
* Web sockets, connecting databases, deploying websites online
* HTML and CSS are not that difficult to learn
* Maybe not have homework due the next day

## What's next for WeBubble
* Have bubbles that were from earlier texts rise as you pop a recent bubble

## Links Used: 
* GoDaddy
* Heroku
  
### Learning:
* https://youtu.be/G3e-cpL7ofc?si=-pswVS44zxxiCWBf
* https://www.w3schools.com/css/default.asp

### Troubleshooting:
* https://stackoverflow.com/questions/20565736/my-background-image-get-cut-off-at-the-bottom
