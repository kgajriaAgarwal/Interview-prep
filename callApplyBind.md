### Call Apply and Bind


```
const employee1 = {
	name:"Karishma",
  age:"31"
}

const employee2 = {
	name:"neha",
  age:"50"
}

function printdata(city, country){
	console.log(`Hello! ${this.name} , is ${this.age} years old and live in ${city}, ${country}`);
}
```

#### call : Invokes a function with a given this value , arguments provided one by one.

```
printdata.call(employee1,"indore", "mp");
printdata.call(employee2,"indore", "mp.");
```

#### Apply : Invokes a function with a given this value , allows you to pass arguments as an array.

printdata.apply(employee1,["indore", "mp."]);

#### Bind : Returns  a new function , allowing you to pass any number of argumnets.

const res = printdata.bind(employee1);
 res("finland", "europe");

