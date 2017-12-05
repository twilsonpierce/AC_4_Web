# Practice Assignment 1

## Keyowrds

* AJAX
* Fetch / XMLHTTPRequest
* Object.keys
* Event Listeners

## Instructions

Create a filterable list of emojis using the following emoji dictionary: [https://s3.amazonaws.com/c4q/emojis.json](https://s3.amazonaws.com/c4q/emojis.json)

![screenshot 1](assets/practice_0.png?raw=true)

### Level 1

When the document loads, make an AJAX request (using Fetch or XMLHTTPRequest) to the URL above to get all the emojis.  The response will be an object where each key is the name of an emoji and each value is the emoji's URL. Parse the response to display the emoji names and images like in the screenshot above.

**hint**: you may use `Object.keys` to get an array of all the property names contained within an object.
You could then use the property names to access the values.

### Level 2

As the user inputs text into the search field, only those emojis whose name contains the inputted string should be displayed.

![screenshot 2](assets/practice_1.png?raw=true)

**hint** there is no need for additional ajax requests. After making the inital request, you can save the response to a variable(s).

**hint** it is fine to erase the list and recreate it from scratch on every change to the input.