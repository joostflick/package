# Package
You can use this package to censor a specified string using special characters or grawlix (%$#!@).
This could be used to censor cursewords.

## Usage
This package has 3 functions, all 3 used to censor/block out certain words.

The first function can receive a string and replaces the vowels with an asterisk, or another specified character.

``` js
censor.vowel('butt') 
```
Would output b&ast;tt, and
``` js
censor.vowel('butt', #) 
```
would output b#tt.

The second function replaces all words between the first and last char of a word, with specified characters or asterixes just like the first one.

``` js
censor.inner('butt', &)
```
would ouput b&&t.

The last function replaces all characters of a string with grawlix.

``` js
censor.grawlix('butt')
```
would output @#$%.
