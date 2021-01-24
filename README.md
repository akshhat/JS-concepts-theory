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