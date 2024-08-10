## New Things that i have Learned

### From mySolution

- i didn't know that there is `type="color"` for input

- Another JavaScript event that that i didnt' know and is quite similar to onchange is oninput. The difference is that oninput is triggered every time the value of an element changes even while it still is in focus.

**After watching the video**

> CSS variables can be updated with JS and the meaning of that when we update a variable in CSS every where on the page that variable is referenced will update itself

<!-- with SASS we define them at compile time and the it gets compiled so we cannot change it -->

### From mySolution2

The first refactor did it from solution 1 is instead of listening the all Document just listening for the inputs

and changing the Css Values instead of change the img element style properties using `if,else`

and instead of using `event` using [`this`](https://www.freecodecamp.org/news/the-this-keyword-in-javascript/)

querySelectorAll will return some thing called `NodeList` to us.
`NodeList` is looks like an array it's got square brackets it has index items it has a length but it's not an `array`

**The differences between NodeList & Array**

is that an array has all kind of methods for dealing with an array like(map,reduce,etc) but if we open the prototype for the NodeList we not gonna find those

> the data attribute is just an attribute that you've made up  you just have to prefix it with `data-SomeThing` and all these made up data will find in `element.dataset`  which is an object that will contain all the data attributes from that specific element

> we don't need to use any attribute selector from dataset object it will just take everything that has `data-` on that elemnt and put it on object for us 