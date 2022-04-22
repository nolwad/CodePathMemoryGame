# Pre-work - Variable Length Memory Game

**Variable Length Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: **Nolan Ward**

Time spent: **about 4** hours spent in total

Link to project: https://glitch.com/edit/#!/radial-polar-washer

## Required Functionality

The following **required** functionality is complete:

- [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
- [x] "Start" button toggles between "Start" and "Stop" when clicked.
- [x] Game buttons each light up and play a sound when clicked.
- [x] Computer plays back sequence of clues including sound and visual cue for each button
- [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess.
- [x] User wins the game after guessing a complete pattern
- [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

- [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
- [x] Buttons use a pitch (frequency) other than the ones in the tutorial (button 4 only)
- [ ] More than 4 functional game buttons
- [ ] Playback speeds up on each turn
- [x] Computer picks a different pattern each time the game is played
- [ ] Player only loses after 3 mistakes (instead of on the first mistake)
- [x] Game button appearance change goes beyond color (e.g. add an image) - did game win and lose animations
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [x] Added a functionality to choose the length of the randomized sequence (e.g. 4 terms, 5 terms, etc.,)
- [x] After the game ends, a winning or losing if appears, depending on the result.

## Video Walkthrough (GIF)
If you recorded multiple GIFs for all the implemented featurss, you can add them here:
![gifgif1](https://user-images.githubusercontent.com/65985935/163764584-7f497df4-a696-4fa3-a20a-d3cdd159ce16.gif)
![gifgif2](https://user-images.githubusercontent.com/65985935/163764594-d25f30df-c171-43d0-ace4-182874e801d9.gif)

## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.

   I used Mozilla's Javascript documentation for help with loops and syntax.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)

   The toughest challenge that I faced in this project was allowing the user to choose the length of the sequence, and having the be randomized.
   I had trouble initially even getting the pop-up to ask for user input, but after that I ran into a handful of snags.
   For one, getting my function that randomizes the sequence to depend on the number chosen by the player was difficult, because I kept running into issues with randomizing decimals, rather than integers. I found help for that on the Mozilla documentation.
   I also couldn't quite figure out how to get a user input box to appear as a popup and how to get the number input as an integer rather than a string. I referred to the documentation once again to fix that.
   Inputting the integer to my randomizer code wasn’t too difficult, as was turning the random numbers into a list, but I did have some trouble trying to figure out how to make the randomizer work the exact number of times, rather than one less than the number of times.
   That was simply remembering whether or not the bounds would be inclusive or not.
   Things got even trickier when I thought that my code worked, but in testing realized that each time the player restarted the game the new sequence of buttons was being added to the previous list of numbers. Just using my experience with python, I knew to change where I had the series initialized to an empty list, but I wasn't testing the project correctly, as I was using the refresh button to clean up the console.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)

   I would like to know how websites with more functionality are made. I have some knowledge of Angular, and know how React or other framewares would help, but I still don't know how an entire website could be made.
   I also wanted to try to mess around with making my project open other tabs on the page, but that was out of my depth almost immediately. I remember a little from trying to learn html a few years back, but I don't remember and I remember it being much sloppier than websites that I use daily.
   What exactly are the benefits to coding a website instead of using a website creator, such as wix? In my mind, I think that they would lack specialized functionalities, but for a basic website or a forum, or even stores they seem like they are easier and faster than coding.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)

   If I had more time to work on this project I'd try to make it prettier like a website that I would go to. I'd also try to get the game winning and game losing gifs onto the popup, rather than showing up on the page afterwards.
   As for functionality, I'd try to make it so that the user can only input a natural number, or that it would at least reprompt them to. I also would have liked to include a slider for speed, and a score counter, which would display a user's highest score.
   There's a few small things that I thought about implementing as well, but felt like were 'take it or leave it' functionalities, that I wouldn't miss not being there, such as a little tune for winning and another for losing.
   

## Interview Recording URL Link

[My 5-minute Interview Recording](https://youtu.be/fjef0GixKdM)

## License

    Copyright Nolan Ward

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
