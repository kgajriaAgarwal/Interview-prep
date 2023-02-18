var string1= "Hello , karishma here !!";

var string2 = new String("Hello , how are you doing");

console.log(typeof string1);
console.log(typeof string2);

#### Character access
- To access individual character
```
/* let chAt6 = string1.charAt(6);
console.log("chAt6:", chAt6); */

/* let  chAt6 = string1[6]; */
string1[6] = "!"
console.log("string1:", string1);
```
**When using bracket notation for character access, attempting to delete or assign a value to these properties will not succeed. The properties involved are neither writable nor configurable. (See Object.defineProperty() for more information.)**

##### Comapring Strings
```
var string1= "Hello , karishma here !!";

/* var string2 = new String("Hello , how are you doing"); */
var string2 = "Time ??"

console.log(string1 <string2);
```

h comes first in dictoray , so true 