### DataTypes in Js

"Js is a scripting language"

##### What is Data Type ?
It defines the type of data variable can hold.

#### Primitive data types
- Primitive data types in js are data types are refer to single value.
- eg: var a = 5;

There are 7 types of primitive data types:
1. undefined
2. Null
3. Symbol
4. Number
5. BigInt
6. String
7. Boolean

##### Non-Primitive data types 
- Non-Primitive data types in js are called reference data types, as they refer to objects.

- eg: var person ={name:"Karishma"};

Non-primitive data types include
- Arrays
- Objects etc.

##### Difference between Primitive and Non-Primitive data types
- The fundamental difference between primitives and non-primitive is that primitives are immutable and non-primitive are mutable.

**Immutable in primitives doesn't mean values can't be changed. It means the current value can't be modified.**

```
let sample = 'immutable'
console.log(sample)
sample[0] = 'V' //changing the first letter to V
console.log(sample)
sample = 'mutable'
console.log(sample)
```

```
output:
immuatable
immuatable
mutable
```

- From the example, we can understand that the primitive data types can't be modified but can be changed completely.

- When the value is changed, it is stored in a new address in memory and the previous memory address is automatically freed(deleted) by a memory manager called garbage collector in javascript.

<!-- [text](https://scaler.com/topics/images/example-of-immutable-objects-in-js.webp) -->

##### Refernces:
- https://www.edureka.co/blog/data-types-in-javascript/
- https://www.scaler.com/topics/what-are-the-primitive-data-types-in-javascript/