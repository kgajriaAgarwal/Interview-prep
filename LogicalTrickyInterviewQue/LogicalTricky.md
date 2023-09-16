#### Here are the logical tricky and output based questions

**Code step by step - Karishma**

***Guess the output for Code - 01***
```
function details(){
  console.log("name:", name);
  console.log("occupation:", occupation);
  
  var name = "Karishma";
  let occupation = "SDE"
}

console.log("details:", details());
```
***output***
![Alt text](image-1.png)

***Explanation***
- Here Javascript hoisting rule is applied
- ***Hoisting - It is  a mechnaism in js, where variable and function declaration are move to the top of their scope, before the code execution***
- Whenever we are declaring any variable in hoisting, it allows us to use that variable before declaring. Here we are using the variable , then declaring it 
- Hoisting rule is applied on var, but not applied on let and const variables, 
- so, ***let occupation = "SDE"***, will show refernce error
- While ***var name = "Karishma";***, will show undefined becuase of variable hoisting rule, which says, "for each variable( variable declaration ) a property is created in the varible object, which is then set to "undefined"
 
____________________________________________________________________________________________________

***Guess the output for Code - 02***

```
for(var i=0; i<3; i++){
  setTimeout(()=> console.log("i:", i), 1);
}
```
***output***
![Alt text](image-2.png)

***Explanation***
- Here the concept of closures is used
- Here literal i is declared using var, Here i has global scope, As setTimeout will take some time to provide the oputput and before loop is finished of setTimeout
- So here basically 'i' value in global scope is basically 3 , and after that setTimeout will basically do console.log("i:", i) -> 3 times , and at that time ***'i'***
has value ***'3'*** in the global scope, that's why it will set its value 3 there, for all the cases

***Closures***
- Closures in action, inner function have access to outer function variables and global variables

- **A closure is the combination ofa function and the lexical enviornmnet within which the function was declared.**
____________________________________________________________________________________________________

***Guess the output for Code - 03***

```
for(let i=0; i<3; i++){
  setTimeout(()=> console.log("i:", i), 1);
}
```
***output***
![Alt text](image-3.png)

***Explanation***
- Here the concept of closures is used
- Here literal **i is declared using let, Here i doesn't has global scope, it has only block scope, It will only run in this particular block, so for every setTimeout it has a different value, ***var***  has global scope that's why it has the same value, as mentioned in abv example**

***Closures***
- Closures in action, inner function have access to outer function variables and global variables

- **A closure is the combination ofa function and the lexical enviornmnet within which the function was declared.**
____________________________________________________________________________________________________

***Guess the output for Code - 04***

```
console.warn("+true :", +true);
console.warn("typeof +true :", typeof +true);
```
***output***
![Alt text](image-4.png)

***Explanation***
- Here the **console.warn("+true :", +true);** is 1, beacuse if we are using + sign before any boolean value and string value, it will conver it into the number value and the value of true is 1, so it will console 1
- Here the **console.warn("+true :", +true);** is number, beacuse the type of 1 is number, so it will console number.



