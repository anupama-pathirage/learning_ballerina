# Object

#### Why Objects?

-  Object encapsulates data with functions that operate on the data.

#### Introduction
- An object consists of named members, 
    - field -  stores a value
    - method - a function that can be invoked on the object
- When a method is invoked on an object, the function can access the object using the `self` variable.
- It is not possible for an object to have a field and a method with the same name.   
- Need to use the `new` operator with a `class` to get an object. 
- There are three visibility levels.
    - private - only visible within the object and its functions.
    - public - visible to any module.
    - protected - visible only within the same module.


#### Init Function

- The `init` method in the class initializes the object. 
- Arguments to `new` are passed as arguments to `init`.
- The return type of `init` must be a subtype of `error?`. 
    - If `init` returns `()`: The `new` returns the newly constructed object. 
    - If `init` returns an `error` : The `new` returns that error. 
    - If `init` does not specify a return type: 
        - the return type defaults to `()`.
        - Then `new` will never return an error.


#### Sample

<!-- MARKDOWN-AUTO-DOCS:START (CODE:src=./../../code/object.bal) -->
<!-- The below code snippet is automatically added from ./../../code/object.bal -->
<!-- MARKDOWN-AUTO-DOCS:END -->

#### Output

<!-- MARKDOWN-AUTO-DOCS:START (CODE:src=./../../code/object.bash) -->
<!-- The below code snippet is automatically added from ./../../code/object.bash -->
<!-- MARKDOWN-AUTO-DOCS:END -->