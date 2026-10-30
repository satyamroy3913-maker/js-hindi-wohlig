var a =10;
let b  = 20;
const c = 30;

b = 100;
a  = 200;
// c = 300;

console.log(a+b+c);
if(a ==200){
    console.log("This is if condition");
}else{
    console.log("This is else condition");
}

function fruit(item){
    console.log("this is" + item);
}
console.log("banana");
console.log("apple");

for(var a = 0;a<=10;a++){
    console.log(a);
}
var a = 0;
while(a<=10){
    console.log(a);
    a++;
}

 var users = ["anil","sam","peter","bruce"];

 for(var a = 0;a<users.length;a++){
    console.log(user[a]);

 }
 var user ={
    name: 'anil',
    city: 'delhi',
    age:29
 }
 console.log(user.age);
