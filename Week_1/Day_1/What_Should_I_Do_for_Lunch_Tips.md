## Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript
const whatToDoForLunch = function(hungry, availableTime) {
  if(hungry === false) {
    console.log("Go back to work");
  }
  else {
    if(availableTime <= 20) {
      console.log('Pick up something and eat it in lab.')
    }
    else if(availableTime > 20 && availableTime <= 30 ) {
      console.log("Try a place nearby.");
    }
    else {
      console.log("We want to remind ourselves that we're in a bootcamp and that we should reconsider how much time we actually have to spare.")
    }
  }
}```