# JS-concepts-theory
Some important JavaScript concepts covered in QnA format

1. **What are the primitive data types in JS?**  
 In JavaScript, a **primitive** (primitive value, primitive data type) is data that is not an object and has no methods. There are 6 primitive data types:
   * **string**
   * **number**
   * **bigint**
   * **boolean**
   * **undefined**
   * **symbol**  
   There is also **null**, which is seemingly primitive, but indeed is a special case for every Object.  
 All primitives are **immutable**, i.e. they cannot be altered. It is important not to confuse a primitive itself with a variable assigned a primitive value. The variable may be reassigned a new value, but the existing value can not be changed in the ways that objects, arrays and functions can be altered.

 2. **What's the difference between a variable that is: null, undefined or undeclared?**
   * **undefined** is a _variable that has been declared but no value exists_ and is a type of itself _undefined_. We can think of undefined as variables which have no value at all.
   * **null** is a value of a variable and is a type of _object_. One way to think about null is a _variable which has a value, but that value is void (empty space)_.  
   * One small caveat to consider with null & undefined values:  
     ```
     let a = null;
     let b;
     console.log(a == b); // prints true
     console.log(a === b); // prints false
     ```  
     This happens because both the variables don't have any value but their data types differ. 
   * **undeclared** variable is a situation which occurs when we try to access any variable that is not initialized or declared earlier using the let/const/var keywords.  
      ```
      c = 43;
      console.log(c);
      // ReferenceError: c is not defined
      ```
