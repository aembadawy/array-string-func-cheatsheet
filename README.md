# array-string-func-cheatsheet

### String
Using components(separatedBy:) to split a string into an array of substrings based on a delimiter.

 ```
let paragraph = "This is some words on a screen, this is just practice text for learning string functions in swift, some words will be repeated; and other wont."

let arrOfWords = paragraph.components(separatedBy: " ")

print(arrOfWords)
```
|Output: ["This", "is", "some", "words", "on", "a", "screen,", "this", "is", "just", "practice", "text", "for", "learning", "string", "functions", "in", "swift,", "some", "words", "will", "be", "repeated;", "and", "other", "wont."] 
