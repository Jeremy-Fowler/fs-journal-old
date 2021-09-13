# Callback Hell

## What are some of the signs and causes of Callback Hell?

Some of the sign of Callback Hell are writing multiple functions within the same block of code.

## What does the asynchronous mean and how are callbacks involved?

Async means "will hopefully happen in the future", or "might take some time". Callbacks take time to fire, but async functions await respones before firing.

## Summarize the 3 ways to avoid / fix Callback Hell

1.Keep your code shallow:
Break up your code instead of writing multiple functions within one codeblock.

2.Modularize:
Put resueable code in it's own file and export it to other files to use as neccesary.

3.Handle every single error:
Use the try/catch method to log errors as they pop up, and to keep track of where they pop up.