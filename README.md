# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Aiswariya Suresh

Time spent: 3.5 hours spent in total

Link to project: https://glitch.com/edit/#!/wax-clover-brand?path=README.md%3A9%3A81

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

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
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

Losing Game: https://cdn.glitch.com/a3039daa-d947-4ba3-b092-d530939ce2f6%2Flosinggame.gif?v=1616534322285

Winning Game: https://cdn.glitch.com/a3039daa-d947-4ba3-b092-d530939ce2f6%2Fwinninggame.gif?v=1616534337628


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[YOUR ANSWER HERE]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
In making this submission, I thought I had finished the program and began to test my code. However, I realized when testing my code that 
the sound of each button was not playing when I pressed them. This was really weird because when I first created the buttons and added 
the "onmousedown" and "onmouseup" attributes, they were working fine. Since I knew this was the case, I realized that the issue had to 
be when I added in the "guess(btn)" attribute, which was where I implemented the game logic. So, knowing the issue was with the game logic, 
I deleted my code, went through each of the cases, and rewrote the section of code again. After that, I tested each case of the nested if 
in the game and saw that they all worked!

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
* What other tools do web developers use to bring in more aesthetic to their websites?
* How do web developers store information that users may put into their websites (ie: accounts)?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
I would try to play around by adding more buttons and pitches until I could have the game recreate a small song that everyone would know, like the Avengers theme song. Also, I would try to make the game more 
aesthetic by putting more though into the colors combinations. In addition, I think adding in a time limit to recreate the pattern put on by the program would add a nice and fun competitive edge!



## License

    Copyright [Aiswariya Suresh]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.