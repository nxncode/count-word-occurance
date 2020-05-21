##count-words-occurance
Count words occurance is an npm package that would count the number of words that are passed as a string.  For Instance, if you pass in the string "Hello World", it would return a result as below:

    { 
	  totalWords: 2,
      uniqueWords: [ 'Hello', 'World' ],
      uniqueWordsCount: 2,
      wordsCount: { 
	  	Hello: 1, 
		World: 1 
		}
	}

##How to Install

    npm install count-words-occurance --save

##How to Use

    const wordscount = require("count-words-occurance");
	console.log(wordscount("Hello World, true));

##Parameters
There are one compulsary parameters and an optinal parameter that may be passed to the function.
The **first parameter** is the **string** itself of which the count has to be generated. 
Second is a **boolean** value which determines if the **count** is to be generated taking into consideration **casesensitivity**.
Possible Values - 
**true** - means words would be counted as case sensitive.
**false** - *default* - means words would be counted without case sensitivity.

##Result
The result would be an object which contains the below key value pairs
**totalWords** - total number of words in the string.
**uniqueWords** - unique words in the string.
**uniqueWordsCount** - count of the unique words in the string. 
**wordsCount** - count with the occurance of each word. 

GitHub Repo :[ https://github.com/nxncode/count-words-occurance](https://github.com/nxncode/count-words-occurance " https://github.com/nxncode/count-words-occurance")
