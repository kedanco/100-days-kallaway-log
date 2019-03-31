# 100 Days Of Code (Round 3) - Log

## Tech/Projects from Round 2

- TicTacToe Game
- React Node Course
- Node API Course
- FreeCodeCamp Sections + Projects
- React 2D RPG Game
- Advanced Web Developer Bootcamp (on-going)
- Tetris Game (on-going)
- CS50 Lectures (on-going)

### Objectives of Round 3

1. To explore, build and create 3 variations of MERN Stack apps.

   1. BookTracker

2. To create at least _5_ full-fledged, quality personal projects

   1. Tetris
   2. Tic Tac Toe
   3. BookTracker

3. To follow lesser guides and tutorials, and spend more time creating my own projects.

### Day 1: 24th February Sunday, 2019

**Today's Progress:** CS50

**Thoughts:** Finished lesson 6 of CS50, talking about Python. It was mostly focused on the syntax, but serves as a good introduction! Also tried a bit of Flask. Seeing Jinja inside Flask reminds me of Ruby on Rails.

**Link to work:**

### Day 2: 25th February Monday, 2019

**Today's Progress:** CS50, Adv Dev Bootcamp

**Thoughts:** Finished lesson 7 of CS50, covering Web Programming. Combining JS and python to create a web app with basic routes and validation serves as a easier,simpler version of a mern stack.

**Link to work:**

### Day 3: 26th February Tuesday, 2019

**Today's Progress:** Tetris

**Thoughts:** Added Danger animation into my Tetris! Not the nicest yet, still have things to improve on.

**Link to work:**

### Day 4: 27th February Wednesday, 2019

**Today's Progress:** Tetris

**Thoughts:** Fixed the Danger and bonus animations! So happy to have these 2 animations working, finally feel the game being more interactive.

Added main menu and restart buttons to Pause Overlay but can't get it to work properly yet.

**Link to work:**

### Day 5: 28th February Thursday, 2019

**Today's Progress:** CS50

**Thoughts:** Continued with Lesson 8 of CS50, covering SQL! Good refresher for the Poly days. Back then everything was varchar(255) but now I understand the different data types better.

**Link to work:**

### Day 6: 1st March Friday, 2019

**Today's Progress:** Finished CS50!

**Thoughts:** The last video of CS50 wrapped up with a quick revision across the topics, and also important was the assurance about how:

- You're not supposed to understand and remember everything, no one is capable of that
- You'll find that the more you learn, the more you won't understand
- Basics and understanding of programming and computational thinking will be constantly helpful despite the language you go into

All in all, the course was very informative in the essential concepts a software engineer should have! Shall start on another CS resource after I'm done with my current projects!

**Link to work:**

### Day 7: 2nd March Saturday, 2019

**Today's Progress:** Flappy Bird, BookTracker App

**Thoughts:** Followed CodingTeacher tutorial on FlappyBird and finally got this game up! Much things to add on, like a score and maybe add some challenges too? Though it seems kinda difficult to do.

Started on my personal BookTracker app. Kinda challenging to NOT look at any tutorial videos and try setting up a MERN Stack myself. Having multiple ways to structure your files has made me kinda confused, but I guess as I do more projects I'll start to understand when to use certain ways.

Learning Points:

- Not advisable to size/style canvas with CSS! Results in inaccurate sizes.

**Link to work:**

### Day 8: 3rd March Sunday, 2019

**Today's Progress:** Tetris

**Thoughts:** Spent some time solving git errors. Reverted from a complicated design and just removed the restart and main menu buttons from pause.

**Link to work:**

### Missed A Day: 4th March Monday, 2019

### Day 9: 5th March Tuesday, 2019

**Today's Progress:** Adv Dev Bootcamp

**Thoughts:** Attempted to continue with dev bootcamp but still can't understand SVG and D3 section. Maybe I should pause this for awhile and try out FCC's curriculum on this.

**Link to work:**

### Day 10: 6th March Wednesday, 2019

**Today's Progress:** Tetris

**Thoughts:** Completed the 2 remaining features in my Tetris project - displaying the next upcoming tetris block, and also updating and displaying user's high scores.

It's been a long time and I'm finally completing this game! Not everything is perfect but I'm proud of what I've done. The most important thing is I've come up with my own ideas, and implemented them myself, without following a tutorial.

That said, no major libraries and frameworks were used, and I wonder what kind of vanillajS project I'll work on next time.

**Link to work:**

### Day 11: 7th March Thursday, 2019

**Today's Progress:** BookTracker

**Thoughts:** Setup the backend of the new BookTracker app, finally proud of this Mongo-Express-Node backend that I created with some referencing.

Can't wait to start on the front-end and get a working skeleton out of this app!

**Link to work:**

### Missed A Day: 8th March Friday, 2019

### Day 12: 9th March Saturday, 2019

**Today's Progress:** BookTracker

**Thoughts:** Spent a lot of time figuring out the structure when adding react. Spent another load of time figuring out why my component wasn't re-rendering. Wasn't a problem with setState or Arrow functions but maybe how nesting components within each other kinda screwed that up.

Still, glad I connected the backend API with the front-end React! First time connecting a MERN app without following a video tutorial.

**Link to work:**

### Day 13: 10th March Sunday, 2019

**Today's Progress:** BookTracker

**Thoughts:** Spent too much time configuring a default HTML5 Form, so I searched around and added in Metro4 Form with some basic CSS. Tag-adding wasn't very friendly but everything else saved me a chunk of time.

**Link to work:**

### Day 14: 11th March Monday, 2019

**Today's Progress:** BookTracker

**Thoughts:** Tried to solve an issue where I couldn't create and save the book. Adjusted routes and settings etc, but made little progress.

**Link to work:**

### Day 15: 12th March Tuesday, 2019

**Today's Progress:** BookTracker

**Thoughts:** Thought everything was a proxy problem when it was just a logic issue with checking for duplicates.

**Link to work:**

### Day 16: 13th March Wednesday, 2019

**Today's Progress:** BookTracker

**Thoughts:** Today was a breakthrough. What started out as a (assumed) proxy issue was actually inaccurate displaying of information from `fetch` callbacks. There were multiple keys to solving these issues, and the keys involve knowing:

- That `return`ing a value does not actually wait for the value to be calculated, it returns a premature value if a previous async function is not completed.
- We have 2 `.then()` in a fetch request because
  - The first request serves as a header, getting network resource and resolves to `Response` once done
  - The second request which takes the `Response Stream` and resolves it to a `json object` once done.
- And the last one, that we'll face weird errors trying to `json()` the hell out of the response `Body` (See MDN docs) when the backend request isn't even returning a JSON object to begin with!

Also got more used to async/await and try/catch syntax compared to chaining `.then()`. Working on understand error-handling with Express and async/await.

**Link to work:**

### Day 17: 14th March Thursday, 2019

**Today's Progress:** BookTracker

**Thoughts:** Edited the routes, and spiced up the html and css of the page with Grid and Flexbox. Also added wishlist into the display

**Link to work:**

### Day 18: 15th March Friday, 2019

**Today's Progress:** BookTracker

**Thoughts:** Followed a tutorial adding my UserModel in along with JWT for login validation. Makes me wonder why I didn't add this first as Books needed to depend on User. (Book belongs to User)

**Link to work:**

### Day 19: 16th March Saturday, 2019

**Today's Progress:** Adv Dev Bootcamp

**Thoughts:** Continued with Intermediate D3 and SVG. Intermediate level is not kidding at all, because I can't keep up with the method chaining, flipping sides, scaling of data etc.

I'll probably have to return to this section again once this course is done, or find a better-paced tutorial on this.

**Link to work:**

### Day 20: 17th March Sunday, 2019

**Today's Progress:** BookTracker

**Thoughts:** Continued with adding PassportJS into app for User Model addition and validation. Also edited Book Model to reference Users, and had to remove the existing records in the database. Faced an error I could not solve -> having an error adding a new User. Can't seem to add a new entry using Postman, which was what the tutorial did..

**Link to work:**

### Day 21: 18th March Monday, 2019

**Today's Progress:** Adv Dev Bootcamp

**Thoughts:** Tried continuing with Histogram today. So many chaining methods that I can't remember what's for what, and had to really follow previous examples' code in order to figure out what to do. Still can't get a working example by myself yet, shall resign to following the tutorial to get through this section.

**Link to work:**

### Missed A Day: 19th March Tuesday, 2019

### Missed A Day: 20th March Wednesday, 2019

### Missed A Day: 21st March Thursday, 2019

### Missed A Day: 22nd March Friday, 2019

### Missed A Day: 23rd March Saturday, 2019

### Missed A Day: 24th March Sunday, 2019

### Day 22: 25th March Monday, 2019

**Today's Progress:** Adv Dev Bootcamp

**Thoughts:** Skipped the remaining of D3js and went into introduction videos for React. Since I already understood most of the stuff, I just forwarded until just before props.

Tried moving forward with user side of BookTracker app but no progress.

**Link to work:**

### Day 23: 26th March Tuesday, 2019

**Today's Progress:** Adv Dev Bootcamp

**Thoughts:** Continued with the props section of React in Adv Dev Bootcamp. Still pretty basic React code but I got reminded about using `defaultProps` which serves as good error prevention.

**Link to work:**

### Missed A Day: 27th March Wednesday, 2019

### Missed A Day: 28th March Thursday, 2019

### Day 24: 29th March Friday, 2019

**Today's Progress:** BookTracker

**Thoughts:** Removed the user authentication part of the code. Was spending too much time on it and errors just keep coming. Edited BookItem CSS.

**Link to work:**

### Day 25: 30th March Saturday, 2019

**Today's Progress:** BookTracker

**Thoughts:** Started on Update function, replicated add book form to be used for editing form!

**Link to work:**

### Day 26: 31st March Sunday, 2019

**Today's Progress:** BookTracker

**Thoughts:** With the update function done, CRUD is now completed! Moving on to the next to-do!

**Link to work:**
