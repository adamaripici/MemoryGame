# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Ada Pici**

Time spent: **12** hours spent in total

Link to project: (https://glitch.com/edit/#!/obvious-yielding-ellipse)

## Required Functionality

The following **required** functionality is complete:

* [X] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [X] "Start" button toggles between "Start" and "Stop" when clicked. 
* [X] Game buttons each light up and play a sound when clicked. 
* [X] Computer plays back sequence of clues including sound and visual cue for each button
* [X] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [X] User wins the game after guessing a complete pattern
* [X] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [X] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [X] Buttons use a pitch (frequency) other than the ones in the tutorial
* [X] More than 4 functional game buttons
* [X] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [X] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)
![]![](https://i.imgur.com/TwhTLU0.gif)


If you recorded multiple GIFs for all the implemented features, you can add them here:
![](gif1-link-here)
![](gif2-link-here)
![](gif3-link-here)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
https://www.w3schools.com/js/js_htmldom_css.asp
https://www.w3schools.com/howto/howto_js_countdown.asp
https://www.w3schools.com/jsref/met_win_clearinterval.asp

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)    
        My biggest challenge in the creation of the Memory Game was developing the timer. In order to implement the timer, I simplified the problem into small steps. I started by diagramming what goes into creating a timer and what variables I would potentially need. I knew I needed variables for the minutes, seconds, the timer and a variable for the amount of time left. I then wrote down pseudocode for 3 functions- one function for the count down, one that displays that the countdown is over, and one to display the time.  Then I began coding, but since I didn't understand how to display the minutes and seconds on the screen, I looked up some examples online. I found a few examples, but I really wanted to create my own timer, so I challenged myself to use my own ideas and whenever I got stuck I referred back to the tutorial. This helped become comfortable with the javascript syntax and functions. In javascript, I learned about the floor function, which I utilized for the minutes and seconds. I also discovered the innerHTML method, which allowed me to connect the javascript code and display it on the screen game. Adding photos to the buttons was another issue I encountered. Initially, I attempted to incorporate the photos into the css file by downloading and submitting the images to glitch. Unfortunately, this resulted in a blank screen, so I googled my issue and came upon an example on glitch's website. I followed along and discovered a url function that made things easier without having to download anything.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)  
        As I have completed my submission, I feel that I have learned a lot, but I still have so much more to learn. Some questions about web development are how are websites with lots of web pages organized? In the memory game, we only had one css file, one html, and one javascript file. But what if we had to create 10 web pages? I am interested in how a big web development project can be developed. Another question I had was how can you incorporate other languages and data into web development? For example, if you wanted to build a social media web page how would you retrieve a user's data onto the web page? And how can you use programming languages like C++, Java or Python to program a web page? My last question is what other languages can you use for web development? Is javascript, html, css the only languages you need to make a web development project?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
        If I had more time to work on this project I would make the game more engaging. I would implement a complex tone by using popular songs as the beat you have to repeat. As well as adding a leaderboard, I would like to add an account system where users can save their highest scores. Ideally, there should be levels added so each time a song is completed, you can go to a harder level. One last feature I would add to the game is the ability to compete with someone, whether a  stranger or a friend. I believe these features would enhance the game's fun factor. 



## Interview Recording URL Link

[My 5-minute Interview Recording](https://drive.google.com/file/d/1aR2AB4owhi3xh_-dXO07WvKxhjYA2fh_/view)


## License

    Copyright [Ada Pici]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
