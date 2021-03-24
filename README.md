# Pre-work - *Pokémon Memory Game*

**Pokémon Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Nicholas de Souza**

Time spent: **12** hours spent in total

Link to project: (https://glitch.com/edit/#!/eight-cyclic-lantern?path=index.html%3A1%3A0)

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x] More than 4 functional game buttons
* [x] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [x] Player only loses after 3 mistakes (instead of on the first mistake)
* [x] Game button appearance change goes beyond color (e.g. add an image)
* [x] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [x] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [x] Added intro song that plays after clicking the "Start" button
- [x] Clue hold time is random each game
- [x] Each game button has it's own custom sound 
- [x] Each button moves when clicked

## Video Walkthrough

Here's a walkthrough of implemented user stories:

![https://recordit.co/tzd12sRhA2]

![Shows player losing after 3 mistakes]https://recordit.co/jz2X6947aS

![Shows what happens when time runs out]https://recordit.co/arsGwGJJ0P


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[Timeout in JavaScript - https://www.sitepoint.com/delay-sleep-pause-wait/]

[https://programminghead.com/how-to-play-audio-in-html-using-javascript/]

[Pokemon sounds - https://forums.pokemmo.eu/index.php?/topic/59823-mod-anime-sounds-and-cries-soundpacktv/]

[Pokemon intro - https://www.myinstants.com/instant/whos-that-pokemon-90928/]

[General information for HTML, CSS, JavaScript - https://www.w3schools.com/]

[https://developer.mozilla.org/en-US/docs/web/javascript/reference/global_objects/math/random]

[https://www.w3schools.com/jsref/met_win_setinterval.asp]

[https://www.w3schools.com/jsref/met_win_clearinterval.asp]

[Resume audiocontext - https://developer.mozilla.org/en-US/docs/Web/API/AudioContext]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

[There were multiple challenges I encountered, one of them being the audio context. Whenever I would load the page, none of my audio would play until I "refreshed" it by changing a line of code. I wasn't sure what it was, and it frustrated me until I learned more about AudioContext. I looked up the documentation and implemented the resume method in my code. These few lines of code helped tremendously as I was stuck at this point; without it, I wouldn’t have been able to successfully present my game. Another challenge was getting used to the CSS classes and using them in tandem with HTML. I had not used CSS in a few months and so I ran into small roadblocks while trying to style how the buttons worked. I would frequently move back-and-forth between the files including the script.js file, making sure that everything lined up correctly. This led to the next problem I had which was implementing the timer. Styling it correctly and placing it on the right-hand side wasn’t too much of an issue, but the logic needed for it to work took some time. I had never used clearInterval or even setInterval before, so they were completely foreign to me and even trying to show how much time was left was difficult for me to figure out. Getting the HTML element and adding the countDown variable to it was new to me as I had never used both facets like that before. Personally, I found looking up my problems or even the methods and how to use them on the internet to be extremely helpful; the examples online would sometimes lead me to having a “oh I know what to do now” moment multiple times over the course of this assignment.]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

[After working on this assignment, I started to really see how JavaScript can interact with CSS and HTML. Before, I had only worked with JavaScript by itself, not using it in tandem with HTML and CSS. Some questions I have about web development would be the capabilities of JavaScript with different frameworks. I know that React and node.js are popular frameworks for JavaScript but what makes them different from the other frameworks used, specifically differences between Angular and React? Another question is, how do all of these frameworks come together to create a single project, one with a database that can be accessed and used to show data to the user in real time? The database is something that interests me specifically for this project.]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

[If I had a few more hours to work on this project, I would have implemented a way for the Pokémon in the game to be randomized from a database each time. Along with that, they would have to also come with their own custom audio; this would automatically increase the challenge of the game. I’m guessing that keys would be involved so that the whole process for that would be easier to do. Something else I would have liked to have done is have a shaded version of the Pokémon be used like how it’s presented in the show where only the silhouette and sound is given. Maybe even an extra feature would be having to type out the names of the Pokémon instead of clicking on each of their boxes so that it can test both the user’s knowledge of the Pokémon and their typing speed.]



## License

    Copyright [Nicholas de Souza]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
