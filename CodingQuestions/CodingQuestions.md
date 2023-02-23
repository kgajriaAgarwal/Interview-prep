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
