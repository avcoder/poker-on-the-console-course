# ES6+: Template literals

[Watch this 3 minute video](https://www.linkedin.com/learning/javascript-essential-training-3/how-do-i-write-strings-in-es2015) to review/learn about writing strings using either the addition operator, or the newer ES6 template literals

### Additional resources 

- https://wanago.io/2018/10/22/concatenating-strings-with-template-literals-tagged-templates/a
- https://www.pokerapi.dev/ - This api shows how you can pass in it your current poker table, and it will output who the winner(s) are.

## Step 1: Description

Create a new string using template literals that mixes 3 strings into an already existing string. The 3 strings you will be given are:
```js
var communityCards = "AC,KD,QH,JS,7C";
var player1 = "10S,8C";
var player2 = "QS,JH"
```
Your goal is to produce a string that looks like:
```
'https://api.pokerapi.dev/v1/winner/texas_holdem?cc=AC,KD,QH,JS,7C&pc[]=10S,8C&pc[]=3S,2C&pc[]=QS,JH'
``` 
Notice how each of the 3 values above are incorporated inside the string.

### :keyboard: Activity: Specific description

1. Given the following JS code:
  ```js
  var communityCards = "AC,KD,QH,JS,7C";
  var player1 = "10S,8C";
  var player2 = "QS,JH";
  var url = 
  ```
1. Complete the last line of code **using template literals** so that url's value would be:
```
'https://api.pokerapi.dev/v1/winner/texas_holdem?cc=AC,KD,QH,JS,7C&pc[]=10S,8C&pc[]=3S,2C&pc[]=QS,JH'
``` 



<hr>
<h3 align="center">Watch below this comment for my response</h3>

> _Sometimes I respond too fast for the page to update! If you perform an expected action and don't see a response from me, wait a few seconds and refresh the page for your next steps._
