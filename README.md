# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Joyce Fang**

Time spent: **4** hours spent in total

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
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](https://i.imgur.com/itf93ay.gif)
![](https://i.imgur.com/iOj2kO4.gif)

<img src='http://i.imgur.com/link/to/your/gif/file.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

    * canva.com for the logo
  
    * https://webgradients.com/ for the gradient background

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

    One of the main challenges I had was getting the on click events to work for the start and the stop buttons. 
Originally, when I tried to include the onclick attributes in the HTML file, it was not working. What I decided 
to do was to get the element by id in the script.js so that I could call the function directly in the JavaScript.
Another challenge was getting the logic of handling guesses correct. I had to use console.log to help debug and I
found that guessCounter had to be incremented in one part. Something else that I still can't quite figure out was why
the sound wasn't playing. At one point when I was developing the tone was working, but now when I inspect the page
and go to console it says, "The AudioContext was not allowed to start. It must be resumed (or created) after a 
user gesture on the page. https://goo.gl/7K7WLu" Update: the sound seems to work only certain times and not others.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

      I have had some web development experience from school and from being a Girls Who Code Teaching Assistant, but
one of my questions is about window.onload and why it's necessary. Another question is about placement of script.js.
From my understanding, the script.js is supposed to be placed after the body tag? It's sometimes confusing to me 
about why that is. Another question that I have relates to question 2: what is a better method of handling onclick
events? Placing it in the HTML file or in the JavaScript file?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

      If I had a few more hours to work on the project, I would add a a high score feature where the user can see how many
correct guesses they have made. If they do better, then the high score would be set to the "best" score. I would also 
try to incorporate more responsive design using Bootstrap so that the application would work better on mobile devices.
Another feature I would incorporate would be allowing the user to adjust settings and change what the buttons look
like or sound like.



## License

    Copyright Joyce Fang

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.