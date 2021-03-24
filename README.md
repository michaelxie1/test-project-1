# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Michael Xie**

Time spent: **4.75** hours spent in total

Link to project: https://glitch.com/edit/#!/noon-fluff-appalachiosaurus

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
* [ ] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough
<b>Required Functionality: </b> <br>
User Losing:<br>
<img src = "http://g.recordit.co/hKwc1O0KOq.gif" width=250><br>
User Winning: <br>
<img src = "http://g.recordit.co/sxsN7z9cIK.gif" width=250><br>

<b>Additional features</b><br>
User Losing:<br>
<img src = "http://g.recordit.co/MzGu55EW1j.gif" width=250><br>
User Winning: <br>
<img src = "http://g.recordit.co/46eQevQnaj.gif" width=250><br>

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
For some of the syntax regarding both CSS and JavaScript I referred to websites such as W3Schools and TutorialsPoint. I also referred to StackOverFlow when 
I came across some issues regarding my console, so I would also paste my code into Visual Studio Code and run it whenever the simulation from Glitch did not work out.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
One of the challenges that I faced within this project would be understanding some of the JavaScript code within the file. Regarding the creation of the conditional statements that analyzed the user's guess, I had trouble setting up the actual condition that was necessary in order to actually record what the user had inputted. I understood the solution code to be a group of nested conditionals and further researched the iterations through the array given. For any other issues, I found that missing small things such as a semi-colon or adding extra characters such as hyphens would make the code unreadable within the console. I made it easier by putting it in an actual IDE so that the error lines would show up and tell me which lines needed to be fixed in order for the code to run appropriately. Furthermore, I would run into server issues with Glitch and was unsure of whether or not the issue was within my code itself or just within the server. I found that recopying and repasting the code was the fastest way to see if my code could be implemented with the Glitch website IDE.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
With web developments, I feel that I understand most of the basic concepts and how this website overall works. I am still a bit confused regarding the javascript element of the website. I understand the concepts of functions and conditional statements, but I was still confused about the method calls and what elements were associated with each of their corresponding HTML elements. I still need to get a stronger foundation in object oriented programming while also understanding certain nuances within HTML and CSS. Factors such as the ways to express color elements and what numbers correspond to frequencies are also things that I should familiarize myself more with.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
To improve this project, I would want to implement a case to which the game ends automatically if the user begins to press the buttons before the pattern is finished being outputted by the code. I would also like to add a seperate HTML page that the user is taken to if they fail/ win the game. Rather than have an icon show up on top of the users browser, taking the user to a page that tells them they either won or lost would be much more normal if it were an actual game being implemented. Although it was possible to somewhat randomize the function, I was still unable to randomize the pattern for each instance of the game. Another feature that could be implemented would be some sort of notification that the user gets the correct pattern, as towards the end of the game it gets harder to keep track of whether you entered the correct numbers. The pattern repeated itself as long as the user was entering the correct results. The last element that I wanted to incorporate would be changing the button to display "replay/retry" after the user either fails or wins their game. The website does not explicitly factor in whether or not it's the users first attempt to playing them game.


## License

    Copyright [Michael Xie]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
