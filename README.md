# mernstackonst name = "sherlock";
console.log(name);
const greet = (name) => {
console.log('hello,${name}');
}
greet('bahubali');
greet('kattappa');
global.setTimeout(() =>{
    console.log('in the timeout');
},5000);
const int = setInterval(() =>{
    console.log('In the every interval');
},2000);
setTimeout(() =>{
    console.log('In the timeout');
    clearInterval(int)
},5000);
