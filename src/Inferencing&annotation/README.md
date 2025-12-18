# Type Inference & Annotation
## What is inference & Annotation ?
 ### Inference:- type inference is when the TypeScript compiler automatically determines the type based on the value assigned or context of use

 ### Annotation:- Type annotation involves explicitly telling TypeScript the type a variable or function should have


 ## Example :-
 ### Inferencing :-
 ```bash
#It detects type based on context or assigned value

 let drink = "water"

 # When hover on drink it showes data type which string which it infer from drink
 ```

# Types in Annotations :-

## Built-in Basic Types
TypeScript extends JavaScript's fundamental data types. These are often the types you explicitly annotate for simple variables. 

- number: For all numeric values (integers and floating-point).
- string: For textual data.
- boolean: For true or false values.
- null: Represents the intentional absence of any object value.
- undefined: Represents a variable that has been declared but not assigned a value. 

## Special Types
### These provide flexibility in certain scenarios. 
- any: Opts out of type checking for a variable, allowing it to be any type.
- unknown: A type-safe counterpart to any, requiring type checks or assertions before use.
- void: Used for functions that do not return a value.
- never: Represents the type of values that never occur, such as the return type of a function that always throws an error or never returns.  