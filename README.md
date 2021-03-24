# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Ethan Vaughan**

Time spent: **6** hours spent in total

Link to project: (https://sneaky-futuristic-birth.glitch.me)

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
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!
- [x] Refresh the page after a win or loss to reset the game

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![x](https://cdn.glitch.com/668311da-5685-401f-9ce8-c22146c6c500%2FSITE-prework.gif?v=1616607071907)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.  
www.w3schools.com - To see the implementation of certian JavaScript methods.  
developers.google.com - To fix an audio problem.  
paletton.com - To find the hex code for specific colors that look nice together.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
  
A challenge that I encountered was a problem with the audio. I continuously got an error in the console saying that the AudioContext was not allowed to start. There was a 
suggested link to the google developers page along with the error. I read about why the error was occurring and how it could be fixed. In Google's example the queryselector 
method was used, so to understand how to add it to my code I went to the w3schools page to learn how to correctly implement it. I added a button to index.html that would start the
audio when the user pressed it. This is also nice if the user wants to play the game without audio, but doesn't want to turn their speakers off if they're listening to music.
  
  
3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
  
I had known previously that the combination of HTML, CSS, and JavaScript can be a powerful tool, but I had never used them together in this way.
The code for this webpage seemed so simple, which makes me wonder what other web page functions can be made to create elegant and powerful websites.
I've never been very interested in game development, but making this was quite enjoyable. I wonder what other web games can be made with only 3 files and 273 lines of code.
I was also trying to decde if I should use bootstrap for this project, but it seemed just as easy to make it without bootstrap as it would have been with it. That 
leads me to ask, in what cases should bootstrap (or some other open-source library) be used and when should the styling and scripting be written explicitly.
  

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
  
If I had a bit more time on this project I would have liked to make the number of clues continue going for as long as the user guessed correctly. To do that a new clues would have to be added to the array
every time the user reached the end. There would be no way to win in this case, but a score tracker could be added to the index.html page so that every round the progress could be displayed. The loseGame function 
could also be updated to show if the user beat their previous high score or not.




## License

    Copyright [Ethan Vaughan]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.