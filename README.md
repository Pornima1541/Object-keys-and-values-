// object : 

// key : value 


//  userData -> object name : 
let userData = {
   // key value pairs 
   name:"pornima",
   age:20,
   branch:"CSE DS",
   student: true,
   hobby: "Coding",
   address: {
     city: "kolhapur",
     pincode: 12345
   },
   marks:[90,70,30],
   greet : function (){
    console.log(" hello JavaScript ");
    
   }
}

console.log(userData.address.city);
console.log(userData.marks);


console.log(userData.greet());




numbers = [10,20,30,40,50]

let num1 = numbers[0]

const[a,b,c,d,e] = numbers


console.log( "a : ",a);
console.log( "b: ",b);





// destructuring : 



//  object : 


const demoObj = {
    name: "abc",
    email: "abc12@gmail.com",
    pass: "1234"
}

console.log(demoObj);


const {name , email, pass} = demoObj;

console.log(name , email , pass);


// function

let i=0;
function function_name(){
    console.log("hello JavaScript ",i)
    i++;
}

function parameterized_function(a){
    console.log(a)
}


function default_parameterized_function(a="default params"){
    console.log(a)
}

default_parameterized_function()
default_parameterized_function("abc")







// parameterized_function("hello")
// function_name()



function addition(input1 , input2){
    let sum = input1+input2;
    console.log(" sum is : ",sum);
    
}




addition(10,20)
addition(100,32)l
