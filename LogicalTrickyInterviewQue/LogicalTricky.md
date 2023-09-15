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
