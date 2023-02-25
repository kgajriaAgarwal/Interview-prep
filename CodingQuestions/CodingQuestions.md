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


________________________________________________________

Remove duplicates
var arr = [{id:1,name:"abc"},
						{id:2, name:"xyz"}, 
            {id:4, name:"pqr"}, 
            {id:4, name:"lms"}, 
            {id:5, name: "kkk"},
             {id:6, name:"pqr"}, 
            {id:3, name:"pqr"}, 
            {id:7, name: "kkk"}

_________________________________________________________________

Find the longest word in the sentence "React has a powerful composition model and we recommend using it"

/* Find the longest word in the sentence "React has a powerful composition model and we recommend using it" */
```
const str = "React has a powerful composition model and we recommend using it";

function longestString(){
	const strArr = str.split(' ')
  console.log("strArr:", strArr);
  
  let longestWord= strArr[0];
  console.log("longestWord:", longestWord);
	for(let i=1;i< strArr.length;i++){
		if(strArr[i].length > longestWord.length) {
    	longestWord = 	strArr[i];
      }
  }
  return longestWord;
    
}

console.log("longestString:", longestString());
```
______________________________________________________________________________________

/* -1,10,0,-5,8,7,"hello",8,50,20,11,0,0,"world", 44, 33, 50, 10, "Bye", -1 */

/* remove string
make them sorted in ascending order
sum of uniquie elements */

```
const arr = [-1,10,0,-5,8,7,"hello",8,50,20,11,0,0,"world", 44, 33, 50, 10, "Bye", -1]
```

### 1. remove string
```
function removeString(){
  const result =[];
  for(let i=0;i<arr.length;i++){
    if(typeof arr[i] !== "string") result.push(arr[i]);
  }
  return result;
}

console.log("removeString:", removeString());
```

### 2.make them sorted in ascending order
```
function sortArr(){
  var resultArr = removeString();
  console.log("resultArr:", resultArr);
  return  resultArr.sort(function(a, b) {
    return a - b;
  });
}

console.log("sortArr:", sortArr());
```

### 3.sum of uniquie elements
```
function sumOfUnique(){
	var resultArr = removeString();
  const uniqueArr = resultArr.reduce((acc, cval)=>{
  	if(acc.indexOf(cval) == -1){
    	acc.push(cval)
    }
    return acc;
  }, [])
  
  const sum = uniqueArr.reduce((acc, cval) => acc += cval, 0)
  return sum;
}

console.log("sumOfUnique:", sumOfUnique());
```

______________________________________________________________________________________

React Questions

ques 1.
https://codesandbox.io/s/unruffled-northcutt-jui2pi?file=/src/App.js:0-715

```
import "./styles.css";
import {useState} from 'react';

export default function App() {

  const [input1, setInput1] = useState('')
  const [input2, setInput2] = useState('')
  const [arr, setArr] = useState([10,20,30,40]);
  return (
    <div className="App">
      <h1>Hello CodeSandbox</h1>
      <input type="text" value = {input1} onChange={(e)=> setInput1(e.target.value)}/>
      <input type="text" value = {input2} />
      <button onClick={()=> setInput2(input1)}>click me!!</button>
      {arr.length?
        arr.map((num, indx)=><ul>
            <li key={indx}>{num}</li>
          </ul>
        )
      :""}
      <button onClick={()=> setArr([...arr, 50])}>Click for action</button>
    </div>
  );
}
```
