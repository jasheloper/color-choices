## Demo 
(wip) https://jasheloper.github.io/color-choices/

##  Objective

In this example, you are going to take the ternary operator example we saw earlier and convert the ternary operator into a switch statement to allow us to apply more choices to the simple website.

Look at the `<select>` — this time you'll see that it has not two theme options, but five. 

- <b>MDN Link:</b> https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals#active_learning_more_color_choices


## Instructions 

You need to add a switch statement just underneath the `// ADD SWITCH STATEMENT comment`:

- It should accept the `choice` variable as its input expression.

- For each case, the choice should equal one of the possible `<option>` values that can be selected, that is, `white`, `black`, `purple`, `yellow`, or `psychedelic`.

- For each case, the `update()` function should be run, and be passed two color values, the first one for the background color, and the second one for the text color. Remember that color values are strings, so they need to be wrapped in quotes.