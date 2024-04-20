# Asyncronous
```javascript
//This code run one by one synchronous way
console.log("task1")
console.log("task2")
console.log("task3")
console.log("task4")
//Block process i.e Asynchronous process
console.log("task1")
console.log("task2")
for(let i=0;i<10000;i+++)
{
    console.log("Loop started")
}
console.log("task3")
console.log("task4")

/// For Asynchronous important 
1.Setinterval
2.settimeout
3.localstorage
4.fetch

// Promises
promise is simple object in js
there are three state
pending
fullfilled
reject
//how to create promise

const xyz= new Promise((resolve,reject)=>{

    resolve("get drink")

    //if reject then
    reject("not available")
})

console.log(xyz)

//fetch API
let a=fetch("url")
console.log(a)  // return promises

fetch("url").then((res)=>res.json))
.then((data)=>console.log(data))
.catch((err)=>console)
```