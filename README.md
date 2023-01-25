[Clippy.JS] Easy Access
=========
Add Clippy or his friends to any website for instant nostalgia.  

![image](https://user-images.githubusercontent.com/28036018/214212339-2c0f636f-4b68-42e4-986b-cc149e549e40.png)


Usage:

Go to this site, https://download-directory.github.io/, enter https://github.com/djbritt/ClippyJS_EasyAccess.github.io/tree/main/clippy to download the project. Run index.html

--------------
All the agent actions are queued and executed by order, so you could stack them.

```javascript
// play a given animation
agent.play('Searching');

// play a random animation
agent.animate();

// get a list of all the animations
agent.animations();
// => ["MoveLeft", "Congratulate", "Hide", "Pleased", "Acknowledge", ...]

// Show text balloon
agent.speak('When all else fails, bind some paper together. My name is Clippy.');

// move to the given point, use animation if available, I updated the js to use jquery.animate
agent.moveTo(300,400);

// gesture at a given point (if gesture animation is available)
agent.gestureAt(200,200);

// stop the current action in the queue
agent.stopCurrent();

// stop all actions in the queue and go back to idle mode
agent.stop();
```

ORIGINAL CODE CREATED BY: [https://github.com/pi0/clippyjs](https://github.com/clippyjs/clippy.js)
Thank you for the work on this Smore. https://www.smore.com/clippy-js
