# Reflection

## Question 1 (50 words)
#### When and why should you use a function like `carefulSubract` rather than `subtract`? 
## Careful Subtract prevents a possible error that would occur if the function subtract is used. It makes sure that both inputs are integers and prevents an error.

## Question 2 (100 words)
#### What are `data types`, and how does data typing work in JavaScript? Name at least 4 built-in data JS data types. 
## 4 built in JS Data types: String,number, array, boolean
### Data type is an attribute of data which tells the compiler how the programmer wants to use the data.


## Question 3 (100 words)
#### What is the advantage to storing information as an object (`{firstName: 'Italo', lastName: 'Calvino', profession: 'novelist' }`) rather than as an array (`['Italo', 'Calvino', 'novelist']`)? Are there any disadvantages?
### An object and its components help us identify the kind of data that is being entered. For example: we understand and can access a firstname by accessing a property of the object instead of using a number that represents the position in an array.s

## Question 4 (150 words)
#### The function `sentences` transforms a data structure (in this case, a list of object literals) into a sequence of sentences. If the data structure were less predictable (e.g., if some properties of each object were occasionally missing, or if their data type was not always the same), what programming techniques could you use to ensure that your function produced a coherent output? Also, can you think of a more interesting "transform" that could be done with the same data structure?
