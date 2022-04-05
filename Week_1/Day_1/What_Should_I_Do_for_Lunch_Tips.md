### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

### Codes

``` const whatToDoForLunch = function(hungry, availableTime) {
  if (hungry === true && availableTime < 20) {
    console.log('grab some food or snack!');
  } else if (hungry === true && availableTime >= 20 && availableTime < 30) {
    console.log('Take a break and cook some food for yourself!');
  } else if (hungry === true && availableTime > 30) {
    console.log('Maybe eat later! ');
  } else {
    console.log("I don't know what to do!");
  }
}
  ;
```