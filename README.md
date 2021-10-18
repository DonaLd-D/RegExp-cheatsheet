### Using the Test Method
```js
let myString = "Hello, World!";
let myRegex = /Hello/;
let result = myRegex.test(myString);
```

### Match Literal Strings
```js
let waldoIsHiding = "Somewhere Waldo is hiding in this text.";
let waldoRegex = /Waldo/; // Change this line
let result = waldoRegex.test(waldoIsHiding);
```

### Match a Literal String with Different Possibilities
```js
let petString = "James has a pet cat.";
let petRegex = /dog|cat|bird|fish/; // Change this line
let result = petRegex.test(petString);
```

### Ignore Case While Matching
```js
let myString = "freeCodeCamp";
let fccRegex = /freecodecamp/i; // Change this line
let result = fccRegex.test(myString);
```

### Extract Matches
```js
let extractStr = "Extract the word 'coding' from this string.";
let codingRegex = /coding/; // Change this line
let result = extractStr.match(codingRegex); // Change this line
```

### Find More Than the First Match
```js
let twinkleStar = "Twinkle, twinkle, little star";
let starRegex = /twinkle/gi; // Change this line
let result = twinkleStar.match(starRegex); // Change this line
```

### Match Anything with Wildcard Period
```js
let exampleStr = "Let's have fun with regular expressions!";
let unRegex = /.un/g; // Change this line
let result = unRegex.test(exampleStr);
```

### Match Single Character with Multiple Possibilities
```js
let quoteSample = "Beware of bugs in the above code; I have only proved it correct, not tried it.";
let vowelRegex = /[aeiou]/gi; // Change this line
let result = quoteSample.match(vowelRegex); // Change this line
```

### Match Letters of the Alphabet
```js
let quoteSample = "The quick brown fox jumps over the lazy dog.";
let alphabetRegex = /[a-z]/ig; // Change this line
let result = quoteSample.match(alphabetRegex); // Change this line
```

### Match Numbers and Letters of the Alphabet
```js
let quoteSample = "Blueberry 3.141592653s are delicious.";
let myRegex = /[h-s2-6]/gi; // Change this line
let result = quoteSample.match(myRegex); // Change this line
```

### Match Single Characters Not Specified
```js
let quoteSample = "3 blind mice.";
let myRegex = /[^aeiuo0-9]/gi; // Change this line
let result = quoteSample.match(myRegex); // Change this line
```

### Match Characters that Occur One or More Times
```js
let difficultSpelling = "Mississippi";
let myRegex = /s+/gi; // Change this line
let result = difficultSpelling.match(myRegex);
```

### Match Characters that Occur Zero or More Times
```js
// Only change code below this line
let chewieRegex = /Aa*/g; // Change this line
// Only change code above this line

let result = chewieQuote.match(chewieRegex);
```

### Find Characters with Lazy Matching
```js
let text = "<h1>Winter is coming</h1>";
let myRegex = /<.*?>/; // Change this line
let result = text.match(myRegex);
```

### Find One or More Criminals in a Hunt
```js
let reCriminals = /C+/g; // Change this line
```

### Match Beginning String Patterns
```js
let rickyAndCal = "Cal and Ricky both like racing.";
let calRegex = /^Cal/; // Change this line
let result = calRegex.test(rickyAndCal);
```

### Match Ending String Patterns
```js
let caboose = "The last car on a train is the caboose";
let lastRegex = /caboose$/; // Change this line
let result = lastRegex.test(caboose);
```

### Match All Letters and Numbers
```js
let quoteSample = "The five boxing wizards jump quickly.";
let alphabetRegexV2 = /\w/g; // Change this line
let result = quoteSample.match(alphabetRegexV2).length;
```

### Match Everything But Letters and Numbers
```js
let quoteSample = "The five boxing wizards jump quickly.";
let nonAlphabetRegex = /\W/g; // Change this line
let result = quoteSample.match(nonAlphabetRegex).length;
```

### Match All Numbers
```js
let movieName = "2001: A Space Odyssey";
let numRegex = /\d/g; // Change this line
let result = movieName.match(numRegex).length;
```

### Match All Non-Numbers
```js
let movieName = "2001: A Space Odyssey";
let noNumRegex = /\D/g; // Change this line
let result = movieName.match(noNumRegex).length;
```

### Restrict Possible Usernames
```js
let username = "JackOfAllTrades";
let userCheck = /^[a-z][a-z]+\d*$|^[a-z][0-9]+\d+$/i; // Change this line
let result = userCheck.test(username);
```

### Match Whitespace
```js
let sample = "Whitespace is important in separating words";
let countWhiteSpace = /\s/g; // Change this line
let result = sample.match(countWhiteSpace);
```

### Match Non-Whitespace Characters
```js
let sample = "Whitespace is important in separating words";
let countNonWhiteSpace = /\S/g; // Change this line
let result = sample.match(countNonWhiteSpace);
```

### Specify Upper and Lower Number of Matches
```js
let ohStr = "Ohhh no";
let ohRegex = /Oh{3,6}\sno/g; // Change this line
let result = ohRegex.test(ohStr);
```

### Specify Only the Lower Number of Matches
```js

```