# Alternate Solution 1 
```
repeatedStringArr <- []
stringRepeat (string, number)
```for an amount of times = number
    push string to repeatedStringArr
repeatedString <- repeatedStringArr.join

---

### Solution Explained:

Function which uses a for loop to create an array with as many elements as provided in the function's given argument (passed). The content of the element will be the string itself. Then group back all elements of the created array into a new larger string by using .join


### Language Feature:

* for loop
* array function push()
* array function .join


# Alternate Solution 2
---

repeatedString <-string
stringRepeat (string, number)
  for an amount of times = number
  repeatedString += string

---

### Solution Explained:

Use for loop  and concatenate the string with +=

Implementing solution 2 for I believe it to be the simplest and easiest to maintain


___

### Language Feature:

for loop
string concatenation +=

# Alternate Solution 3
```
stringSize <- string.length
newStringSize <- stringSize * number
newString <- string
stringRepeat (string, number)
  while newString.lenght < newStringSize
  newString += string

---

### Solution Explained:

Detect string lenght and calculate the length of the string we want to create by multiplying the string length by the given number. Then use a while loop  to concatenate the string with += until the length of the new string has not yet reached the intended size.




___

### Language Feature:

.length
multiplication
while loop
string concatenation +=


___
___
### <a href="http://elewa.education/blog" target="_blank"><img src="https://user-images.githubusercontent.com/18554853/34921062-506450ae-f97d-11e7-875f-6feeb26ad72d.png" width="100" height="40"/></a>

