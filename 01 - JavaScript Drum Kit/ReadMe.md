
## New Things I've Learned

**When using attribute selectors  the value property must be a string**: so simply wrap your value into quotes should fix the issue:


```js

 document.addEventListener("keydown", (event) => {
      
        document.querySelectorAll("audio").forEach((item) => {
          if (item.getAttribute("data-key") == event.keyCode) {
            item.currentTime=0
            item.play();
        // document.querySelector(`[data-key=${event.keyCode}]`); // Error Here*
            document.querySelector(`[data-key="${event.keyCode}"]`)// True way
          }
        });
      });
```

if we hit the same key more than one time it's gonna plays once every  so often and that's because the audio take 3 or 2 second to get to the end and  if we call the .play() on audio element that already playing it won't play it again.  so to solve this problem we will restart it from the beginning before we run .play() and that why we added `item.currentTime = 0`


using the code like I did using for loops is not the best way cause it give more processing to the browser to do  the best way to caputre the elements is by using **CSS Selectors** here  we used **CSS Attribute Selector** and **Template String** from js ES6




> 'This'  is always equal to the whatever got called against it 