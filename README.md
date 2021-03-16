# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Lucheng Qing**

Time spent: **3** hours spent in total

Link to project: (insert your link here, should start with https://glitch.com...)

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

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [x] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [X] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
<img src='https://github.com/q815101630/colorSoundGame/blob/main/1.gif' />
<img src='https://github.com/q815101630/colorSoundGame/blob/main/2.gif' />
<img src='https://github.com/q815101630/colorSoundGame/blob/main/3.gif' />


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
No external resources except some javascript syntax lookup:
https://stackoverflow.com/questions/4959975/generate-random-number-between-two-numbers-in-javascript

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

  ​    Firstly, I am intrigued of the way of creating sounds. The way I understood the overall flow of that part is by going through each function separately, and trying to connect them from two, to three, and more. 

  ​	It is very interesting to understand the way of cooperation between JavaScript, CSS, and html. It is very helpful to know the core concept of selector in CSS, in which it is a new piece of knowledge that I do not know before. After doing some practices in this training, I become much more comfortable to  look at CSS and JavaScript codes.

  ​	My first challenge is to figure out the hidden logic for the `guess()` function. It took me some time to understand the workflow of this game. It is important to note that there are two variables that control the flow of the game: `progress`, `guessCounter`. `progress` records the overall progress of the game, and `guessCounter` refers to the specific number of guess the player is making. Once I understood the relationship between `guessCounter` and the position of  `pattern` .It became much more clearer on implementing `guess()` then.

  ​     

1. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

  * How does the backend be involved in the general web development such as in this game? I know that we can create a database for different players to record their higher scores by database for the instance of this game, but how can we link it with JavaScript? 

  * How will some popular JS framework such as Vue.js, React.js help in our development? I often hear about them, but I barely know them very well. 

  * Will we always have one JS file for each html file? 

  * Will we always have one CSS file for each html file? 

    

2. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

  I would like to try make the user interface more modern and beautiful such as a webpage that  people always like to visit.  Because this game is concise enough, the components that I would like to add include better styled font, size, background for the whole webpage. Also, if possible, I am interested to create another html file for introduction usage, playing the role of index. Instead, the game page is another specific page linked from the index page. By doing so, the player can understand the rule of the game,  watch some video about this game (by embedding Youtube or html video player). 

  Also, I would like to add a timer to time the total time the player spend to win. If possible, I can also add different difficulty levels for player to choose. The implementation is not difficult because it is simply to having more number of clues in a pattern list. The part of choose can be implemented by adding a series of buttons  to indicate the difficulty.     

## License

    Copyright Lucheng Qing
    
    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at
    
        http://www.apache.org/licenses/LICENSE-2.0
    
    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
