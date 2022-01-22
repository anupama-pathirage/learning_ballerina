# Float

- The `float` type corresponds to IEEE 754-2008 64-bit binary (radix 2) floating point numbers. 
- This is same as `double` in Java.
- No implicit conversions between `int` and `float` are allowed. Need to use `<T>` for explicit conversions. 
- Literal uses the suffix `f`. 

#### Sample

```go
import ballerina/io;

public function main() {
    float f1 = 1.67;

    int i1 = 5;

    // Use `<T>` for explicit conversions.
    float f2 = f1 + <float>i1;
    io:println(f2);

    //Use ballerina/lang.float function.
    float f3 =f1.round();
    io:println(f3);   
}

```


#### Output

```
6.67
2.0
```