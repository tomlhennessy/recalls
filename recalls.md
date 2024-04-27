# Primitive Data Types in Depth

* Primitive Data Types:
    Immutability:
        - Primitive types in JavaScript are immutable, meaning they cannot be changed
        - This immutability extends not only to reassignment but also the inability to define new methods on primitive types

* Data Types in JavaScript:
    Primitive Types:
        - Boolean, Null, Undefined, Number, String, Symbol, BigInt
        - Each with specific characteristics
    Reference Type:
        - Object, comprising properties and methods

* Methods and Object Type:
    Definition:
        Method: A function that belongs to an object
    Object Type:
        - Only data type with methods in JavaScript
        - Primitive types cannot have methods since they are not objects

* Primitives with Object Wrappers:
    Implementation:
        - Although primitive types don't have methods, JavaScript provides object wrappers for some, like strings
        - These wrappers facilitate method calls on primitives by acting as objects

* Example:
    String Type:
    - Calling methods like 'toUpperCase()' on strings works due to underlying String objects
    Example:

    ```javascript
    let str1 = "apple";
    let str2 = str1.toUpperCase(); // returns APPLE

    console.log(str1); // prints apple
    console.log(str2); // prints APPLE
    ```

    Explanation:
        - Methods like 'toUpperCase()' operate on the String object, not the primitive itself
        - Primitive types remain immutable; methods return new values or representations

* Summary:
    __Primitive Data Types:__
    - Not objects, hence no methods
    - Immutability ensures consistency
    __Object Types:__
    - Sole type with methods in JavaScript
    - Wrappers facilitate method calls on primitives

* Key Takeaway:
    - Primitive data types in JavaScript lack methods because they are not objects
