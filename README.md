# Debugging in JavaScript

Debugging is hard. And frustrating. Debugging web application is even harder because
errors could occur in either the front end or the back end.

Various version of this adage can be found online:

```
The five stages of debugging:

Denial: What do you mean broken, it's worked forever.

Anger: I can't believe how stupid programming is!

Bargaining: Hmm, maybe if I hack this bit that will fix it...

Depression: It’s unfixable, I should be a farmer.

Acceptance: I can't believe I made that mistake. How did it ever work in the first place?
```

This is a great piece of advice, from [Rob Napier](https://twitter.com/cocoaphony/status/1224364439429881856):

```
When debugging, you must first accept that something you believe is true is
not true. If everything you believed about this system were true, it would work.
It doesn't, so you're wrong about something.

This is a surprisingly common stumbling block for devs.
```

## Learning

This short exercise will give you some advice and practice when debugging JavaScript.
I would recommend watching these two videos, which introduce you to some good practices.

<iframe width="560" height="315" src="https://www.youtube.com/embed/ABlaMXkUwzY" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/H0XScE08hy8" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

For the video from Google, you should access a demo in the video description and follow
along to practice using the Chrome DevTools to debug JavaScript.


## Practice

This repository contains a broken Javascript program. Clone the repo and run a
local web browser:

```
python3 -m http.server
python2 -m SimpleHTTPServer
```

Then, use the Developer Tools in your browser of choice to debug the program, using
breakpoints and examining the code as it runs. Do NOT insert console.log statements!
Follow the best practices described in the video above.

This code calls a [Numbers API](http://numbersapi.com/). You'll want to be familiar
with the URL structure at the link above.

Solve all the bugs and modify the code so that it works.

## Closing Advice

This is a great quote from [Brian Kernighan](https://www.cs.princeton.edu/~bwk/), a co-author on the first book about the C programming language:

```
Debugging is twice as hard as writing the code in the first place. Therefore, if you write the code as cleverly as possible, you are, by definition, not smart enough to debug it.
```

Strive to write clear, simple, maintainable code and debugging will be far easier.