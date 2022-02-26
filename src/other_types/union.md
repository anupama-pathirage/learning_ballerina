# union

- A union type describes a value that can be one of several types.
- Why union types?
    - Union is useful when the program expects a value to be either a many   different types.  e.g., : A  parameter  to the function or  return value  can be either  `int` or `float` etc.     
    - In traditional object-oriented code, we have to abstract over the two types by creating a hierarchy of types to achieve this.
- `T1|T2|T3` represent a union of the  sets  `T1`, `T2` and `T3`. 
    - e.g., The type `int|float|string` can hold either `int`, `float` or `string`.
- The  `is` operator is  used to check whether the value  belongs to a specific type.   The type will be narrowed  with the use of `is` operator. Narrowing occurs when Ballerina can deduce a more specific type for a value based on the structure of the code.
- `T1|()` can be written as `T?` as  well.

#### Sample

<!-- MARKDOWN-AUTO-DOCS:START (CODE:src=./../../code/boolean.bal) -->
<!-- The below code snippet is automatically added from ./../../code/boolean.bal -->
<!-- MARKDOWN-AUTO-DOCS:END -->

#### Output

<!-- MARKDOWN-AUTO-DOCS:START (CODE:src=./../../code/boolean.bash) -->
<!-- The below code snippet is automatically added from ./../../code/boolean.bash -->
<!-- MARKDOWN-AUTO-DOCS:END -->


