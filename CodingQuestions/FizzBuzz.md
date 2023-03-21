
## FizzBuzz Problem

##### Traditional approach using for loop - using If-else
- solution 1
```
function fizzbuzz1(n) {
    for(let i = 1; i<=n ; i++){
      if(i%3 ==0 && i %5==0){
        console.log('fizzbuzz')
      }
      else if( i%5 == 0){
        console.log('buzz')
      }
      else if( i%3 == 0){
        console.log('fizz')
      }
      else console.log(i)
    }
 } 

fizzbuzz1(100); 
``` 
- solution 2
##### Using If 
```
  function fizzbuzz2(n) {
    for(let i = 1; i<=n ; i++){
      if(i%3 !=0 && i %5!=0){
        console.log(i)
        continue;
      } 
      if(i%3 ==0 && i %5==0){
        console.log('fizzbuzz')
        continue
      }    
       if( i%3 == 0){
        console.log('fizz')
        continue
      }
      if( i%5 == 0){
        console.log('buzz')
        continue
      }
    }
} 
fizzbuzz2(100);
```

##### using ternary
- solution 3
```
function fizzbuzz(input1, input2, n){
	let arr = [];
  for(let i=1;i<=n;i++){
  	arr[i-1] = ((i%input1 ==0 ? 'Fizz' : '') + (i%input2 ==0 ? 'Buzz' : '') ||i)
  }
  return arr;
}


console.log(fizzbuzz(3,5,100));
```