# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Jenny Yang**

Time spent: **2.5** hours spent in total

Link to project: https://glitch.com/edit/#!/spiritual-iris-find

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
* [x] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)
<img src = "http://g.recordit.co/We9T3LbpwY.gif" width=500><br>
http://g.recordit.co/We9T3LbpwY.gif

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](gif1-link-here)
![](gif2-link-here)
![](gif3-link-here)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
https://www.geeksforgeeks.org/java-math-random-method-examples/  
https://www.w3schools.com/jsref/prop_node_textcontent.asp  
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Text_formatting

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)  
A specific challenge that I encountered while creating this submission was with displaying the strike count for on the page. Because I had no experience with Javascript, I had to consult online resources in order to create it. This prework did teach me some aspects of Javascript and HTML (such as tags and ids), but I was still unsure of how to display a changing variable. Initially, I tried using a heading tag and displaying the text like so: ???Strike Count: + strikeCount???. Of course, this did not work and I had to look for a different method. I decided to go with the div tag since it is very versatile and easily implementable with anything. I noticed that the start and stop button were accessible by the command ???document.getElementById()??? with the id as the parameter input. I added an id ???strike??? to the div tag. For easier access, I decided to set a variable for the getElementById command. I did not know where to go from here so I decided to search up a method to display variable values. One of the tabs that appeared from the search engine was about the property textContent which is able to set or return the text content of the specified element. I knew I would be able to set the contents to the strike counter, but I was also unaware of how text formats in Javascript worked. Looking up the syntax for the format, I was able to display the strike counter using ???strike.textContent = `Strike Count: ${strikeCount}`.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)  
This submission has taught me that web development can be rather difficult and that there is a lot more to it than meets the eye. I have a general idea of how websites are constructed using HTML, Javascript, and CSS. One specific question I have about using HTML is how a developer would format text that is side to side (similar to reading an article or textbook; the text does not go to the end of the page but stops at a certain point then goes to the next line). I can only think of using the tab key but that method seems quite ineffective. Another question I had was about the variety of tags available in HTML. The pre work has only exposed me to a certain amount of tags and I wonder if there are any more tags for different interactive uses besides buttons.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)  
    There are many more functions that I would add, such as different game difficulties (easy,medium, and hard). The user could click on the buttons corresponding to the difficulty levels and the game would adjust its speed, strike count, and the length of the sequence to make it easier or harder for the user to win. The easy difficulty would not speed up at all as the sequence gets longer, along with having three strike counts and the total sequence being of length 7. The medium difficulty would have the sequence speed up by 50ms, have two strikes, and the length of the sequence will be 9. The hard difficulty would have the sequence speed up by 75ms, have only one strike (no mistakes can be made), and the sequence length will be 11. This way, the game would have a bit more dimension and a variety of users will be able to win (ranging from those with bad memory to those with exceptional memory). 



## Interview Recording URL Link

https://youtu.be/WN6LAYGZcNg


## License

    Copyright Jenny Yang

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
