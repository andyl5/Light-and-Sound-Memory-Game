# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Andy Leon**

Time spent: **4** hours spent in total

Link to project: https://glitch.com/edit/#!/morning-guttural-vicuna?path=README.md%3A1%3A0

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

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![ezgif com-gif-maker](https://user-images.githubusercontent.com/81489476/161143736-28aa9c9f-7776-4a08-8924-fc5e420b7e2b.gif)
![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/81489476/161143998-d7cc36f4-ed16-42ad-9dd0-3fd43019977b.gif)
![ezgif com-gif-maker (2)](https://user-images.githubusercontent.com/81489476/161146010-a1aaa518-79e4-4683-96f2-f4e71c8984aa.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
- https://www.w3schools.com/js/
- https://www.w3schools.com/js/js_loop_for.asp
- https://www.youtube.com/watch?v=s9wW2PpJsmQ
- https://www.w3schools.com/jsref/jsref_push.asp
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random
- https://stackoverflow.com/questions/12237529/count-how-many-elements-in-a-div

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
- One challenge I encountered in creating this submission was familiarizing myself with JavaScript’s syntax and built-in methods. I come from a Python background where code is visually neater because there are fewer syntactical rules to keep track of. Often I would forget to enclose a function or statements with {}, wondering why my code was not working properly. Although optional, I also forgot to add ; at the end of my lines of code. When I was trying to add the random pattern feature that would pick a random button as the next sequence, I expected JavaScript to have a built-in function that returns an integer within a range, but it didn’t so I referred to the official Javascript documentation where it showed me exactly how to code it. Another challenge I encountered when building this feature was implementing a for loop to assign all 8 sequences randomly. After searching the correct syntax to create a for loop, I learned that in JavaScript, there are 3 expressions you must declare: an initial expression, a condition and an incremental expression. While these situations initially proved to be a challenge, I used W3schools and Stack Overflow to familiarize myself with the proper syntax and rules of JavaScript. As a result, I successfully implemented the features I wanted to while also building upon my previous knowledge of JavaScript.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
- After completing the pre-work assignment, I understand the basics of a webpage’s programmatic layout and structure (HTML, CSS, JavaScript). What I’m curious about is how websites like Google or Facebook look great on both a computer and a mobile device. Front-end developers obviously don’t create a new HTML file for every device size so I’m curious how web frameworks tackle this issue. I’m also curious about how a dynamic web page communicates between a server and its client. How does the server know what content to show on my Facebook feed? How does my sent email reach my professor’s email? I’d love to learn more about these concepts and how I could implement them into my own web pages.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
- If I had a few more hours to work on this project, I would add additional features to the game. Firstly, instead of the game ending after 8 sequences, I would let the game continue indefinitely by using a while statement that checks if the user has made no errors yet. I would also display the user’s current score and the high score, which updates every time the user correctly guesses the next sequence, and when the user’s current score is greater than the highest score, respectively. A stylistic improvement I would make is having all the buttons take up the entire screen. This way, the game's contents are the main focus and there is less unused space. If I had even more time, I would turn this game into a mobile app aimed at toddlers. It is a simple to use and simple to understand game that would challenge their memorization and pattern recognition skills. All these improvements would provide a cleaner and more fun user experience.



## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


## License

    Copyright [Andy Leon]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
