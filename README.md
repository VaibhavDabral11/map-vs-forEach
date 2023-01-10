# map-vs-forEach
```
let data = [1,2,3,4,5,6];

let result = data.map((item)=> item*100)
/*let result = data.map((item)=>{
    return item*10
})*/

let result1 = data.forEach((item)=> item*100)
/*let result1 = data.forEach((item)=>{
    return item*10
})*/

console.log(result1)
console.log(result)
```
### Output
```
undefined
[ 10, 20, 30, 40, 50, 60 ]

```
```
console.log("This is tutorial 43");

async function harry(){
    console.log('Inside harry function');
    const response = await fetch('https://api.github.com/users'); //fetch api 
    console.log('before response');
    const users = await response.json();
    console.log('users resolved')
    return users;

    // return "harry";
}

console.log("Before calling harry")
let a = harry();
console.log("After calling harry")
console.log(a);
a.then(data => console.log(data))
console.log("Last line of this js file")
```
### Output  
```

```
