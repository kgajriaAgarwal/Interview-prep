##### Coding Questions

```
/* Write a program from to find the char occurence in give string?
input : 'React has a powerful composition model, and we recommend using it.'
output: { i: 3, n: 2, d: 1, ..etc } */


function charOccourances(str){
  const newStr = str.toLowerCase();
  const strArr = newStr.split("");
  console.log("strArr:", strArr);
  const res = strArr.reduce((acc, cval)=>{
  	if(!acc[cval]){
    	acc[cval] = 1;
    }else{
    	acc[cval] = acc[cval] +1;
    }
    return acc;
  }, {})
  return res;
}

console.log("charOccourances:", charOccourances('React has a powerful composition model, and we recommend using it.'));
```
