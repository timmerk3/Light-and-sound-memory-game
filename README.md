# Pre-work - _Memory Game_

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: Kenneth Timmer

Time spent: 2 hours spent in total

Link to project: (https://interesting-hickory-delphinium.glitch.me)

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

- [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
- [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
- [ ] More than 4 functional game buttons
- [ ] Playback speeds up on each turn
- [ ] Computer picks a different pattern each time the game is played
- [ ] Player only loses after 3 mistakes (instead of on the first mistake)
- [ ] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

![](https://cdn.glitch.global/31d5fcf7-0a85-4119-b186-39a375198280/prework.gif?v=1650665373415)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](gif1-link-here)
![](gif2-link-here)
![](gif3-link-here)
![](gif4-link-here)

## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.

Didn't use any outside resources!

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)

A challenge I encountered while creating this submission was understanding the syntax of html, css, and javascript.
I understand the big picture between all those 3, html is the structure of the webpage, css is the rules and style, and
javascript is the backend side of things. Javascript is definitely the most familar-looking to me, as I have coded in
C++ and this is object-oriented programming. html and css and hard to understand as I've never seen them before. CSS uses
"rules" and they look like classes/structs to me. The document provided helps me understand it more, it's a combination
of a selector and declaration block. It's very interesting how inside the declaration block, it holds properties that css can
intepret. That took some time getting used to but just looking at the code and trying my best to understand it helped so much.
And of course, looking at and understand html file for the first time is quite difficult. But again, the tips provided in the
document helped me overcome my confusion. I initally messed up on the open and close tages, not understanding the close
tag signals the end of the content. I orignally put the welcome message's close tag after the all of the buttons. I was confused,
but then i started looking at the indenting/nesting structure of the code and realized my error. The syntax in html looks
very foreign, but I can bridge the gap in my understanding of how html works with my experience in C++. Nesting is a concept
that carries over from object-oriented programming so that helps me understand what I'm seeing with html.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)

I've always been very curious what "frameworks" are and how to use them. I've heard of django, Angular,
and Node.js amongst others. I've also extemely intrigued by how websites can pull data from outside sources and
display them/manipulate them automatically. This is where I feel web development can be super powerful and you can
acheive some pretty amazing things. Specifically, things like tracking the stock prices and using a streaming algorithim
to find the best time to buy and best time to sell a certain stock. Or, getting live data from an ongoing sports game
and using the data to display probabilities of certain outcomes or track statistics and graph them throughout a match.
I've heard of techniques like web scraping, and have a vague idea of what an "API" is and how it can be used to interact
with other websites/sources of data.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)

If I had a few more hours, I would make the game more customizable for the user. I think i'd add options for the user to
choose how many buttons there are, how long the pattern is, and how fast the sequence will play for. There would be
difficulty presets like easy, medium, hard, and expert. I'd also implement different levels for the user to play through,
each time they complete a level, the difficulty scales accordingly. It would keep track of your highest level you
acheived as a global variable and display it in one of the corners. You'd have 3 chances at each level, otherwise you'd return to the first level.
And finally, I also think i'd look to implement some sort of multiplayer option, where 2 people would each have
their seperate game going on. They'd alternate taking turns and see who can go the longest without failing.

## Interview Recording URL Link

[My 5-minute Interview Recording](https://www.loom.com/share/ba19fbb24d834827be738a1ce9396cf3)

## License

    Copyright Kenneth Timmer

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
