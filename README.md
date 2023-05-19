# Python for Javascript Programmers


# Comments
Javascript
```javascript
// Line comment

/*
Block Comment
*/
```
Python
```python
# Line comment

'''
Block Comment
'''
```

# Types



|Javascript                     | Python
|-------------------------------|-----------------------------|
|`object`                       | `dictionary (dict)`         |
|`string           `            | `str`                       |
|`number`                       | `int` `float`               |
|`array `                       | `list`                      |

## Convert Types
Javascript
```javascript
// number to string
String(1)
// string to number
Number('1')
```
Python
```python
# int to string
str(1)
# string to number
int('1')
```



# Declaring Variables
Javascript
```javascript
const aNumber = 1
const anArray = [1,2,3,4]
const anObject = {id: 1, name:"test"}
const aSet = new Set()
```

Python
```python
an_int = 1
a_list = [1,2,3,4]
a_dict = {'id': 1, "name":'test'}
a_set = set()
```

# Defining Functions

## Named
Javascript
```javascript
function add(x, y){
	return x + y
}
```
Python
```python
def add(x, y):
	return x + y

```
## Anonymous
Javascript
```javascript
(x, y) => x + y
```
Python
```python
lambda x,y: x + y
```

# Conditionals
Javascript
```javascript
if(x > 2 && y < 5 || z !== 1){
	//if body 
}else if(x % 2 === 0){
  //else if body
}else{
  //else body
} 
```
Python
```python
if x > 2 and y < 5 or z != 1:
    # if body
elif x % 2 == 0:
    # elif body
else:
    # else body
```



# Iteration

## For loop (numbers)
Javascript
```javascript
//compute the sum of numList 
const numList = [1,2,3,4]
let total = 0
for(let i = 0; i < numList.length; i++){
    total = total + numList[i]
}
```
Python
```python
num_list = [1,2,3,4]
total = 0
for i in range(0,len(num_list)):
    total = total + num_list[i]
```
## For loop (items)
Javascript
```javascript
const numList = [1,2,3,4]
let total = 0
for(let num of numList){
    total = total + num
}
```
Python
```python
num_list = [1,2,3,4]
total = 0
for num in num_list:
    total = total + num
```
## While loop
Javascript
```javascript
const numList = [1,2,3,4]
let total = 0
let i = 0
while(i < numList.length){
    total = total + numList[i]
    i++
}

```
Python
```python
num_list = [1,2,3,4]
total = 0
i = 0
while i < len(num_list):
    total = total + num_list[i]
    i = i + 1
```

# Map
Javascript
```javascript
const numList = [1,2,3,4]
const squaredList = numList.map(num => num**2)

```
Python
```python
num_list = [1,2,3,4]

# List comprehension
squaredList = [num**2 for num in num_list]

# Filter function
squaredList = list(map(lambda num: num**2, num_list))
```
# Filter
Javascript
```javascript
const numList = [1,2,3,4]
const odds = numList.filter(num => num % 2 !== 0)

```
Python
```python
num_list = [1,2,3,4]

# List comprehension
odds = [num for num in num_list if num % 2 != 0]

# Filter function
odds = list(filter(lambda num: num % 2 != 0, num_list))
```
# Printing to Console
Javascript
```javascript
console.log("test")

```
Python
```python
print("test")
```
# String Operations

## Building
Javascript
```javascript
let x = 5
let concatenated = "x = " + x
let interpolated = `x = ${x}`

```
Python
```python
x = 5
concatenated = "x = " + str(x)
interpolated1 = "x = {}".format(x)
interpolated2 = f"x = {x}"
```

## Split to list
Javascript
```javascript
"Split me on spaces".split(' ')

```
Python
```python
"Split me on spaces".split(' ')
```


