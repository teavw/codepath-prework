# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Te'a Washington**

Time spent: **8** hours spent in total

Link to project: https://glitch.com/edit/#!/peridot-handsome-climb

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
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](https://cdn.glitch.com/da6b470e-71fd-4482-a1f8-51547829baba%2Fdemonstration.gif?v=1616608426386)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
* https://www.w3schools.com/js/js_random.asp
* https://www.w3schools.com/tags/tag_img.asp
* https://www.w3schools.com/cssref/pr_background-image.asp

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

The main challenge that I encountered creating this submission was trying to understand how to incorporate the images. I was confused on whether to 
include the img tag inside of the button or to include it in the file leave it separately. I tried both methods and found that it was easier to keep the images 
separate from the buttons for readability. I also had trouble resizing the image in the html file. I eventually realized that the images were not affected by the 
sizes I gave them in the html file because they automatically fit the size of the buttons when I included them in the css file. Additionally, after testing out the 
additional features I added, I noticed that the game continued to speed up even after a new game was started. If I didn't test out the game I wouldn't have noticed 
that I needed to reset the clueHoldTime after every game. Lastly, I think it was a lot easier to make mistakes while adding the optional features because unlike the
instructions for the required features, the tutorial did not really go in-depth on how to implement them. However, the lack of specific instructions for the optional 
features made the experience more challenging and fun, and the sources provided for most of the optional features were useful. Overall, I found the tutorial easy to 
follow and informational for beginners using web development technologies for the first time. 


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
After completing my submission, one question I have about web development is how long does a web development project 
take to finish? To me, using three different languages to develop a website from scratch seems difficult and time-consuming. 
Another question I have is which language is actually the most intricate? HTML looks like the most challenging language to me 
because it’s unlike any other programming language I’ve seen. I wonder if JavaScript and CSS are more difficult for others and 
how they go about handling them. The last question I have is, what are good resources to learn web development? To create a web 
application, knowledge of all three languages are needed. I would like to know which one should I start with and if it’s better 
to learn all of them at the same time to see how they work together or if it’s suggested to learn them separately.


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I had more time I would  add easy, medium, and hard modes. In the startGame() function the user would be be given the option to select their difficulty. The easy mode would be the default tutorial code, the medium
mode would have increasing speeds per level completed successfully, and hard mode would incorporate increasing speed and more buttons added every few levels. I feel that this feature would satisfy users and allow them 
to enjoy challenging themselves by playing on higher difficulties. Another feature I would add is a display of  how many mistakes the user has left before game is over. I think the users would find this helpful to space 
out the amount of guesses they can make before losing. An additional feature that could be useful to the user is allowing them to use a hint, or potentially replay the pattern if they are stuck. This feature would be 
most useful to new users, or those who are on the more difficult levels of the game. I think an infinite mode that would go beyond the maximum eight tones in the default game would be a fun experience for the users to 
challenge themselves. I think that adding a multiplayer mode would open up the opportunity for many more features. The option to select multiplayer mode would appear in the startGame() function as well, and it would allow
to players to . Some features that could appear in multiplayer mode are live games, where the user is able to invite friends with a link. During the game the game each user would be given a pattern of the same difficulty 
and a chance to guess it. Whoever makes the least amount of mistakes would win or there would be a tie. 




## License

    Copyright [YOUR NAME]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.