# Java-Script-All-basic-
This the basic of Java Script - 1

 
 //------------------------------------------------------------Notes--------------------------------------------------------------------------------------------
// Two data-types 
// 1 . permitive --> Number , string , boolean , Null , undefined , symbol
// 2. Non - permitive --> object

//Let keyword //cont keyword // var keywords---------------------------------------------------------------------------------------

//  let gogo = 777 // block-scoped. // let ,  does not allow to redeclare variables.// but it can be updated
//  console.log(gogo) 

//  gogo = 2210
//  console.log(gogo)

//  const pi = 3.14 //The scope of a const variable is block scope. //It cannot be updated or re-declared into the scope.
//  console.log(pi)

// //  pi = 4.24
// //  console.log(pi) // it will give error bcoz it can be changed

// var hello = hello
// var hello = gogo
// console.log(hello) // var is function scoped. // var allows to redeclare variables.

// //closure :- // A closure gives you access to an outer function's scope from an inner function.

// //Hosting :- Basically, it gives us an advantage that no matter where functions and variables are declared, 
// //           they are moved to the top of their scope regardless of whether their scope is global or local.


//  // convert number into string--------------------------------------------------------------------------
// let name = 22
// console.log(typeof name); // number

// console.log(typeof (name +"")) // string

// let age = 123
// age = String(age);
// console.log(typeof age) // string

// // convert string into number

// let myStr = +"22"
// console.log(typeof myStr) // number

// let age1 = "123"
// age = Number(age1);
// console.log(typeof age1) // number

// //string concatenation----------------------------------------------------------------------

// let string1 = "17"
// let string2 = "19"
// console.log(string1 + string2) // 1719 

// console.log(+string1 + +string2) // 36 

// //templet string ----------------------------------------------------------------------

// let firstName = "Govind Lowanshi"
// let age3 = 24

// console.log(`My name is ${firstName} and my age is ${age3}`)  // Myname is Govind and my age is 24


// //Undefined ------------------------------------------------------------------------------------

// let lastName;
// console.log(lastName ) // undefined

// lastName = "lovanshi"
// console.log(typeof lastName , lastName) //string lovanshi

// //Null ------------------------------------------------------------------------------------

// let varable = null
// console.log(varable) // null

// console.log(typeof null , null)//object null // object is bug 

// //BigInt ------------------------------------------------------------------------------------
// let Num = BigInt(35)
// console.log(typeof Num , Num) //bigint 35n

// let Num1 = 100n
// console.log(typeof Num1 , Num1) //bigint 100n

// let Num2 = 132
// console.log(Num + Num1); //135n // only bignt add to bunt

// // console.log(Num2 + Num1) // error b coz BigNt and number cant be added...! 

// //booleans  and comparsion -------------------------------------------------------------------------------------------------------
// let num1 = 7 // number
// let num2 = 7 // number
// let num3 = "7" //string

// console.log(num1 == num2) // true

// console.log(num2 == num3) // true

// console.log(num2 === num3) // flase

// console.log(num2 !== num3) // true

// console.log(num2 != num3) // false

// //if else condition -------------------------------------------------------------------------------------------------------

// let number = 18

// if(number > 18){
//     console.log("even")
// }
// else{
//     console.log("odd")
// }




// //false value -------------------------------------------------------------------------------------------------------

// // flase
// //null
// //undefined
// //""
// // 0

// let myNameis = false // 

// if(myNameis){
//     console.log(myNameis)
// }
// else{
//     console.log("not definde ")
// }

// //truly
// // abs 
// //1 or -1 (but not zero)

// let myNamei = -1

// if(myNamei){
//     console.log(myNamei)
// }
// else{
//     console.log("not definded ")
// }

// //ternary opertator -------------------------------------------------------------------------------------------------------

// let userAge = 5
// let drink = userAge < 18 ? "milk" : "beer"
// console.log(drink)

// let marks = 35;
// let result = marks >= 35 ? "Pass" : "False"
// console.log(result)

// //and or operator -------------------------------------------------------------------------------------------------------

let firstName = "G"
let age1 = 19

// if(firstName == "G" && age1 > 18){                   //And
//     console.log("both the condition are true")
// }
// else {
//     console.log("both condition is not true")
// }

// if(firstName == "G" || age1 > 18){                    //OR
//     console.log("one the condition are true")
// }
// else {
//     console.log("one condition is not true")
// }

// //nested loop -------------------------------------------------------------------------------------------------------

// //winning Number
// // 19 is perfect
// //20 is too high 
// // 17 is too low

// let age7 = 19

// if(age7 > 18){ // 18
//     if(age7 > 20){ // 20
//         console.log("This is too high")
//     }
//     else{ //19
//         console.log("this is perfect")
//     }
// }
// else{ // 
//     console.log("this is too low")
// }

// //if else statment -------------------------------------------------------------------------------------------------------

// let wetherInDegree = 45

// if(wetherInDegree == 0){
//     console.log("its Zero  Degree , so cold outside")
// }
// else if(wetherInDegree <= 10 || wetherInDegree >= 15){
//     console.log("still the wether is 15 outside , too cold")
// }
// else if(wetherInDegree <= 25 || wetherInDegree>= 30  ){
//     console.log("the wether between 25 Degree - 30 Degree")
// }
// else if(wetherInDegree =< 31 | wetherInDegree>= 45){
//     console.log("can you Turn on Ac")
// }
// else if (wetherInDegree == 50){
//     console.log("Its time to leave the Plannet")
// }

// //Switch statment -------------------------------------------------------------------------------------------------------

// let day = 5

// switch(day){
//     case 0:
//         console.log("Sunday")
//         break;
//     case 1:
//         console.log("Monday");
//         break;;
//     case 2:
//         console.log("Tuesady")
//         break
//     case 3:
//         console.log("WednesDay")
//         break
//     case 4:
//         console.log('Thrusday')
//         break;
//     case 5:
//         console.log('Friday')
//         break;
//     case 6:
//         console.log("SaturDay")
//         break;
//     default:
//         console.log("Invalid Day  bro------------------------------------- switch case")
// }

// //while Loop -------------------------------------------------------------------------------------------------------
// // dry -- dont repeat Yourself---------------

// //0 - 9 print

// i =0
// while(i<=5){
//     console.log(`this is the value ${i}`)
//     i++
// }
// console.log(`This is Current value of i :- ${i} ( that come outside of loop)`)
// console.log(`This is While Loop----------------------------------------------------`)

// let sum = 0
// let j = 0
// while(j <= 3){
//     sum +=j
//     j++ 
// }
// console.log(sum)

// //Formula type
// console.log(`This is formula for sum of natural Numbers......`)

// let num =5
// let total = (num*(num+1))/2; 
// console.log(total)

// //ForLoop -------------------------------------------------------------------------------------------------------

// for(i = 0 ; i <=9;i++){
//     console.log(i)
// }

// sum = 0
// for(let i =1 ; i<= 10 ;i++){
//     // console.log(`Right now the value of ${i}`)
//     sum += i;
//     console.log(`Right now the value of ${sum}`)
// }
// console.log(`This is For loop......`,sum)

// //break and Continue Keywords -------------------------------------------------------------------------------------------------------

// for(let i = 0 ;i < 10 ; i++){
//     if(i==5){
//         break;
//     }
//     console.log(i)
// }

// for(let i = 0 ;i <10 ; i++){
//     if(i==5){
//         continue;
//     }
//     console.log(i)
// }

// //Do While -------------------------------------------------------------------------------------------------------
// console.log("do while ----------------------------")

// i=10
// do{
//     console.log(i);
//     i++
//     console.log(`it will Execute---> then it will check condition!`)
// }
// while(i<=9);
// console.log(`checking while condition ------> opps the condtion is not satsfied!!`)

// //--------------------------------------------------------------------Array------------------------------------------------------------------------------

// //  
// // In array we can store any Data Types
// //It is mutatable --> so we can change
// //Refrence Type --> Object.

// //how to create array:-

// let fruits = ["apple" , "mango" , "grapes"]
// console.log(fruits)

// let numbers = [1,2,3,4,7,8,5,9]
// console.log(numbers)

// let mixed = [ 1 ,"Gogo" , 1.5458 , true]
// console.log(mixed)

// // array indexing-------------------------------------------------------------------------------------------------------------

// console.log(fruits[0])
// console.log(fruits[1])


// fruits = ["apple" , "mango" , "grapes"]
// console.log(fruits)

// fruits[0] = "banana"
// console.log(fruits)

// console.log(typeof fruits) //----------------its showing object!

// //to check is Array is Array --->
// console.log(Array.isArray(fruits)) // this is use for more sepecific

// //----------------------------------*********--------Array---> push , pop , shift , unshift <-------***********------------------------------------------------------
// console.log("push , pop , shift , unshift-----------------------------------------------")



// fruits = ["apple" , "mango" , "grapes"]
// console.log(fruits)

// //push ---> add in the last------------------------------------>
// fruits.push("banana")
// console.log(fruits)

// //pop --> remove last element ------------------------------------>

// console.log(fruits , "This is pop function")
// fruits.pop()
// console.log(fruits)

// let poppedFunction = fruits.pop()
// console.log("This is Popped Value---------->" , poppedFunction )

// //unshit --> it will add in starting
// console.log("unshit and shift Function----------------------->")

// fruits.unshift("cherry")
// console.log(fruits) 

// //shift --> we remove from starting ------------------------------------>

// console.log(fruits)
// let Firstremoved = fruits.shift()
// console.log(Firstremoved)

//Note 
//push and pop are fast then shift and unshift 

//----------------------------------------------> premitive and reference data - Type<------------------------------------------------------------------
//premitive Type
//its value store in stack
// num1 = 7
// num2 = num1
// console.log('this is number1 value' , num1)
// console.log('this is number2 value' , num2)
// num1++;
// console.log('after Increment')
// console.log('this is number1 value' , num1)
// console.log('this is number2 value' , num2)

//------------------------------------------------Refrence Type--------------------------------------------------------------------------------------------------------------------

//its array1 store in stack in which array1 & array2 have same refrence number thats goes to heap...

// let array1 = ["array1" , "array2", 'array3'] // it store in stack 
// let array2 = array1 // store in heap
// console.log('This is the Value of array 1',array1)
// console.log('This is the Value of array 2',array2)
// console.log("after push in array1")

// // array.push("array4")
// console.log('This is the Value of array 1',array)
// console.log('This is the Value of array 2',array9)

// //How to clone array 
// array0 = ["array1" , "array2", 'array3'] //
// array0 = array2
// console.log(array1 === array2) // true qki wo ek memory store 

// //this is not not a right way to clone (what if their is 100 items)

// array3 = ["array1" , "array2", 'array3']   // array1
// array4 =  ["array1" , "array2", 'array3']  // array 2 aage momory store hua han..

// array0.push("array4")

// console.log('This is the Value of array 0',array0)
// console.log('This is the Value of array 2',array2)

// console.log(array3 == array4)

// // This is right way to clone any array --------------------------------------------------------------

// array1 = array2.splice(0) // this is right way to clone 
// console.log(array1 == array2)


// //-----------------------------------------------------------> concate <-----------------------------------------------------------------------------------------------------------------------------------

// array1 = [].concat(array2);

// // // seprate operator 

// array1 = [...array2]
// console.log(array1)

//--------------------------------------------------------------------------------------------------------------------
// array1 = ["item1","item2","item3"]
// let array5 = array1.splice(0).concat(["item4","item5","item6"])
// console.log(array5);

// let oneMoreArray = ["A" , "B" ,"C", "D"]

// let array6 = [...array5 , ...oneMoreArray];
// console.log(array6)

//---------------------------------------------------------->    for loop   <----------------------------------------------------------------------------------------

// let arr = ["apple ", " graps ", " gogo ", "kamna"]
// console.log(arr.length)
// console.log(arr[arr.length-1])


// for(i=0 ; i < arr.length ;i++){
//     console.log(arr[i].toUpperCase())
// }

// let fruits = []
// for(i=0;i<arr.length ; i++){
//     fruits.push(arr[i].toLocaleLowerCase())
// }
// console.log(fruits)

// use const for creating array------------------------------------------------------------------------------------------------------------------

//heap memory - ["apple" , "mango"]
// const fruits = ["apple" , "mango"]
// fruits.push("graps", "pineapple")
// console.log(fruits)

// fruits[0] = "kela"
// console.log(fruits)

//while loop------------------------------------------------------------------------------------------------

// let i = 0
// while(i<fruits.length){
//     console.log(fruits[i])
//     i++
// }

//---------------------------------------------------> For of loop in array <------------------------------------------------------------------------------

// let fruits = ["apple" , "mango" , "graps", "pineapple"]

// for(let fruit of fruits ){ // it give value under other loop
//     console.log(fruit)
// }

//---------------------------------for in  loop in array -----------------------------------------------------------

// fruits = ["apple" , "mango" , "graps", "pineapple"]

// for(index in fruits){ // its give you only index
//     console.log(index)
// }

//---------------------------------for in  loop in array -----------------------------------------------------------

// let fruits = ["apple" , "mango" , "graps", "pineapple"]

// for(let index in fruits){ // its give you only index
//     console.log(fruits[index]);
// }

// let fruits = ["apple" , "mango" , "graps", "pineapple"]

// for(let index in fruits){ // its give you only index
//     console.log(...index ,fruits[index]);
// }

// the out put with index---------------------------------
// 0 apple
// 1 mango
// 2 graps
// 3 pineapple
//
//---------------------------------array destructuring -----------------------------------------------------------

// const value = ["value1" , "value2" , "value3", "value4" , "value5"]

// let myvar1 = value[0]
// let myvar2 = value[1]

// let [myvar1 , myvar2 ,myvar3] = value
// console.log(myvar1)
// console.log(myvar2)
// console.log(myvar3)// myvar4 hota toh uski value value4 hoti 

// let [myvar1, , myvar2] = value // skipping the 2 val bcoz it has space
// // console.log(myvar1)
// // console.log(myvar2)

// let myNewArray = value.slice(2)
// console.log(myNewArray)

// let [myvar1, , myvar2 ,...myNewArray] = value
// console.log(value)
// console.log(myNewArray)

//----------------------------------------------------OBJECT----------------------------------------------------------------------------------------

// OBJECT IS REFRENCE TYPE 
// ARRAY ARE NOT GOT AND SUFFICIENT
// FOR REAL WORLD DATA
// OBJECT STORE IN KEY VALUE PAIR
// OBJECT DONT HAVE INDEX

// HOW TO CREATE 
// const person = {
//     name : "gogo" ,
//      age : 24,
//      "person hobbies":[ "cricket" , "football","swimming"]
//     }

// // how to access
// console.log(person.hobbies);
// console.log(person.name) // we use dot 
// console.log(person["name"]) // other way to accesss

// console.log(person["person hobbies"])

// // how to upadte 
// person.gender= "male"
// console.log(person)

// //dot and bracket notation ---------------------------------------------------

// const key = "email"
// person[key] = "govind.lowanshi@gmail.com"
// console.log(person);

// //how to iterate object

// for(let key in person){ // this will give only name - n all 
//     console.log(key)
// }

// for(let key in person){ // this will give key n value 
//     console.log(person[key])
// }

// // object.keys

// // console.log(Object.keys(person))  //[ 'name', 'age', 'person hobbies', 'gender', 'email' ]
// // console.log( typeof (Object.keys(person))) //object

// let val = Array.isArray((Object.keys(person)))
// console.log(val)

// for(let key of Object.keys(person)){
//     console.log(person[key]) // it will iterate with keys 
// }

// computed properties

// const key1 = "name" 
// const key2 = "age"

// const value1 = "gogo"
// const value2 = 24

// const obj = {}
//     obj[key1] = value1
//     obj[key2] = value2

// console.log(obj)

//------------------------------------------------------------------- spread operator---------------------------------------------------------------------------------------

// let array1 = [1,2,3]

// let array2 = [5,6,7]

// let newArray = [...array1 , ...array2 ,69]
// console.log(newArray)

// let newArray = [..."abc"]  // only strings can be spread not a number 
// console.log(newArray)  //[ 'a', 'b', 'c' ]

//--------------------------------------------------------------------------object spread --------------------------------------------------------

// const obj1 = {
//     key1 : "value1",
//     key2 : "value2"

// };
// const obj2 = {
//     key3 : "value3",
//     key4 : "value4"

// };
// const newObj = {...obj1 , ...obj2} //{ key1: 'value1', key2: 'value2', key3: 'value3', key4: 'value4' }
// console.log(newObj)

// const newObj1 = {..."abc"} //{ '0': 'a', '1': 'b', '2': 'c' }
// console.log(newObj1)

// const newObj2 = {...["item2" , "item2"]} //{ '0': 'item2', '1': 'item2' }
// console.log(newObj2)

// object destructure----------------------------------------------------------------------------------------------

// const band = {
//     bandName : "Linkin Park",
//     famousSong : "Numb",
//     year : 1967,
//     anotherfamousSong : "KingOFTheWorld",
// }
// const {bandName,famousSong} = band// we have make const so we can not change the vairable inside it
// console.log(band)

// const {bandName : var1 ,famousSong : var2} = band// we can change the variable name like this
// console.log(bandName) // now this will not print

// console.log(var1) //Linkin Park// this will print 

// const {bandName,famousSong , ...resProps} = band
// console.log( resProps)  //{ year: 1967, anotherfamousSong: 'KingOFTheWorld' } // it will rest property which is not include 

//----------------------------------------------object inside array ------------------------------------------------------------------------------

// object inside array
// very usefull in real world application 

// const users =[
//     {Userid: 1 ,firstName: "gogo" , gender:"Male"},
//     {Userid: 2,firstName:  "Govind" , gender:"Male"},
//     {Userid: 3 ,firstName: "Kamal" , gender:"Male"},
//     {Userid: 4 ,firstName: "Pinky" , gender:"Female"}
// ]
// for(let user of users){
//     console.log(user.Userid)
// }

// for(let user of users){
//     console.log(user.firstName)
// }
// for(let user of users){
//     console.log(user.gender)
// }
// console.log(users)

//-----------------------------------------------nested distructuring------------------------------------------------------------------------------------

// const users =[
//     {Userid: 1 ,firstName: "gogo" , gender:"Male"},
//     {Userid: 2,firstName:  "Govind" , gender:"Male"},
//     {Userid: 3 ,firstName: "Kamal" , gender:"Male"},
//     {Userid: 4 ,firstName: "Pinky" , gender:"Female"}
// ]
// const [{Userid}, ,{firstName} , {gender}] = users
// console.log(Userid)
// console.log(firstName)
// console.log(gender)


// const [{Userid:userids}, ,{firstName :UserFirstname} , {gender : UserGender}] = users
// console.log(userids)
// console.log(UserFirstname)
// console.log(UserGender)

//-------------------------------------------function-------------------------------------------------------------------------------------------
// function delcration ----

// let input = "Govind"

// function firstSting(input){
//     return input[0]
// }
// console.log(firstSting(input))

// let input = [2 , 3 , 4 , 5 , 6 , 7 , 8 , 9]
// function tragetNumber(input,taget){
//     for(i=0;i<input.length;i++){
//         if(input[i] == taget){
//             return i
//         }
//         else{
//             console.log("Go fuck off!!!")
//         }
//     }
// }
// console.log(tragetNumber(input, 99))
 
// function expression ----------------------------------------------------

// let input = [2 , 3 , 4 , 5 , 6 , 7 , 8 , 9]

// const tragetNumber = function tragetNumber(input,taget){
//     for(i=0;i<input.length;i++){
//         if(input[i] == taget){
//             return i
//         }
//         else{
//             return ("Go fuck off!!!")
//         }
//     }
// }

// console.log(tragetNumber(input, 99))

//Array Function----------------------------------------------------------------------------------

// const add = (a ,b ,c) =>{
//     let sum = a + b + c
//     return sum
// }
// console.log(add(2,3,8))

// const sub = (a , b) =>{
//     let sub = b-a
//     return sub
// }
// console.log(sub(3,6))

// let input = [2 , 3 , 4 , 5 , 6 , 7 , 8 , 9]

// const evenOdd = (input)=>{
//     let even = []
//     let odd = []
//     for(i=0 ;i <input.length ;i++){
//         if(input[i] % 2 == 0){
//             even.push(input[i])
            
//         }
//         else{
//             odd.push(input[i])
            
//         }     
//     }
//     console.log(even);
//     console.log(odd)
// }
// console.log(evenOdd(input))

//hosting--------------------------------------------------------------------

// function delcration -----------------------------
// hello();
// function hello(){
//     console.log("hello world")
// }

// function expression (you cant print in function expression or in arrow function)
// const hello = function(){
//     console.log("hello gogo")
// }

//(you cant write hellow world in let but you can do this in var)
// console.log(hello)
// let hello="hellow world"

//function indside function--------------------------------------------------

// function app  () {
//     const myfunction = () => {
//         console.log("hello from my function")
//     }
    
//     const addtwo = (num1 , num2) =>{
//         return num1 + num2
//     }
//     const mul = (num1 ,num2) => num1 * num2;
//     console.log("inside function")

//     myfunction();
//     console.log(addtwo(2 ,3))
//     console.log(mul(2 ,3))
// }
// app();

// lexical  scope ---------------------------------------------------------------------
// const myvar = "value59" // it is in global 

// function myApp(){
//     // const myvar = "value1"

//     function myfun(){
//         const myfunc2 = () =>{
//             console.log("inside myFun2" , myvar);
//         }
//        myfunc2(); // second call

//     }
//     // const myfunc3 = () => {}

//     console.log(myvar)
//     myfun();
// }
// myApp(); // first call 

//------------------------------------------------------------------------------------------------------------

// function scope vs function scope 

// let and const are block scope 

// var is function scope 

// {
//     let firstName = "Govind"; //you cant access boz block scope 
// }
// console.log(firstName)
// you cant access with let n const 

// {
//     let firstName = "Gogo"; //// you can access this boc it is inside the scope
//     console.log(firstName)
// }

// const firstName = "kamna"
// console.log(firstName)

// {
//     var firstName ="Govind Lowanshi" // bcoz its a function scope
// }
//  console.log(firstName)

// function myApp(){
//     if(true){
//         let firstName = "gogo"; 
//     console.log(firstName)
//    }
//    console.log(firstName); // here it will give us error bcoz its block scope! 
// }
// myApp();
    

// function myApp(){
//     if(true){
//         var firstName = "gogo";
//     console.log(firstName)
//    }
//    console.log(firstName); // it will give you answer bcoz we use function scope 
// }
// myApp();

// function myApp(){
//     if(true){
//         var firstName = "gogo";
//     console.log(firstName)
//     }
//     if(true){
//      var firstName = "gogo";
//      console.log(firstName)
// }
// }
// myApp();


// default prametrs -----------------------------------------------------------------------------------------

// before ES-6 modle  ------------------------------

// function addtwo(a,b){
//     if(typeof b ==="undefined")
//     b=3
//     return a+b
// }
// const ans = addtwo(4)
// console.log(ans)

// After---------------------------- 

// function addtwo(a,b=0){
//     return a+b
// }
// const ans = addtwo(4,5)
// console.log(ans)

// rest prameters -----------------------------------------------------------------------------------------------------------------

// function myFunc (a,b,c){
//     console.log( `a is ${a}`)
//     console.log( `a is ${b}`)
//     console.log( `a is ${c}`)
// }
// myFunc(1,2,3,4,5,6,7,8,9,)

// function myFunc (a,b,...c){ // rest prameters
//     console.log( `a is ${a}`)
//     console.log( `b is ${b}`)
//     console.log( `c is ${c}`)
// }
// myFunc(1,2,3,4,5,6,7,8,9,);


// function addAll(...numbers){
//     let total = 0;
//     for(let number of numbers){ // we use this bcoz we have to iterate 
//         total = total + number;
//     }
//     return total;
// }
// const ans = addAll(4,5,6,7,8,9)
// console.log(ans)
 

 // param destructureing

 //object
 // react

//  const person1 = {
//     firstname: "gogo",
//     gender:"male"
//  }

 //obj ---------------------------------------------------------------------------------------------------------------------

// function printDetails(obj){
//     console.log(obj.firstname);
//     console.log(obj.gender);
// }

//react -----------------------------------------------------------------------------------------------------------------------------
// function printDetails(firstname ,gender , age){
//     console.log(firstname);
//     console.log(gender);
// }

// printDetails(person1);

// call back function --------high order function---------------------------------------------------------------------------------------------------

// function myFunc(name){
//     console.log("inside my Func 2")
//     console.log(`your name is ${name}`)
// }

// function myFunc2(callback){
//     console.log("hello there I am a func and I can ...")
//     callback("Gogo")
// }

// myFunc2(myFunc);

// function returing funcition -----------higer order function---------------------------------------------------------------

// function myFunc(){
//     return "a";
// }

// const ans = myFunc();
// console.log(ans)

// function myFunc(){
//     return {name :"gogo" , age : 25};
// }
// const ans = myFunc();
// console.log(ans)

// function myFunc(){
//     function hello(){
//         console.log("hello i am hello function")
//     }
//     return hello;
// }
// const ans = myFunc();
// ans()

// ----------------------------------------Important methods in array -----------------------------------------------------------------

// forEach
// map
// Filter
// reduce

// const number = [4,5,,2,6,8];

// function multiplyby2(number , index){
//     console.log(`index is ${index} , number is ${number}`)
//     console.log(number*2)
// }

// // multiplyby2(array[0] , 0);
// // multiplyby2(array[1] , 1);

// for(let i=0 ; i<number.length ;i++){
//     // console.log(i)
//     multiplyby2(number[i] , i);
// }

//forEach----------------------------------------------
// it will not give new array

// const number = [4,5,,2,6,8];

// function multiplyby2(number , index){
//     console.log(`index is ${index} , number is ${number}`)
//     console.log(number*2)
// }

// number.forEach(multiplyby2);

// const num = [7,2,5,9,8,7,1,2,3,6,4,7]

// function add(num){ 
//     if(num > 5){
//         console.log(num * 5)
//     }
//     else{
//         console.log(num + 5)
//     }
// }
// num.forEach(add)

// const users = [
//     {firstName:"Gogo" , age :25},
//     {firstName:"Mohit" , age :20},
//     {firstName:"Rohit" , age :23},
//     {firstName:"Pagal" , age :26},
// ]

// users.forEach(function(users){
//     console.log(users.firstName)
// })

// for(let names of users){
//     console.log(names.firstName);
// }

// users.forEach((users ,index)=>{
//     console.log(users.firstName ,index)
// })

//---------------------------------------------------Map Method-----------------------------------------------------------------------------------------------------

//Map
//its give new array 

// const numbers = [3,4,6,8,10];

// const square = function(numbers){
//     return numbers * numbers;
// }

// const squareNumber = numbers.map(square)
// console.log(squareNumber)


// const squareNumber= numbers.map((number , index)=>{
//     return `index ${index} : ${number*number}`;
// })
// console.log(squareNumber);


// const users = [
//     {firstName:"Gogo" , age :25},
//     {firstName:"Mohit" , age :20},
//     {firstName:"Rohit" , age :23},
//     {firstName:"Pagal" , age :26},
// ]

// const userNames = users.map((user)=>{
//     return user.firstName;
// })
// console.log(userNames)

//-------------------------------------------------------------------------- Filter -----------------------------------------------------------------------------------------------------------------------

// filter Method
//its a call back function 
//it return boolean  value

// const number = [1,2,3,4,5,6,8];

// const isEven = function(number){
//     return number%2===0;

// }
// const evenNUmbers = number.filter(isEven)
// console.log(evenNUmbers);


// const isOdd = function(number){
//     return number%2!==0;
// }

// const oddNUmbers = number.filter(isOdd)
// console.log(oddNUmbers);

// const oddNumber = number.filter((number)=>{
//     return number % 2 !==0;
// });
// console.log(oddNumber);

// const events=[1,2,3,4,4,6,6];
// const differentNo =events.filter((a,b)=>{
//     return a-b!==0;
// });
// console.log(differentNo)

//------------------------------------------------Reduce ----------------------------------------------------------------------------------------

//aim : sum all the numbers in array

// const numbers = [1,2,3,4,5,10];

// const sum = numbers.reduce((accumalator , currentValue)=>{
//     return accumalator + currentValue
// });
// console.log(sum)

// const usercart = [
//     {productId : 1 , productName : "mobile"  ,price : 12000},
//     {productId : 2 , productName : "Tv"  ,price : 40000},
//     {productId : 3 , productName : "Laptop"  ,price : 58000},
//     {productId : 4 , productName : "earPods"  ,price : 18000}]

// const totalAmount = usercart.reduce((totalprice , currentProduct)=>{
//     return totalprice + currentProduct.price;
// } , 0)
// console.log(totalAmount);

//----------------------------------------------- Sort-----------------------------------------------------------------------------------------------------

//sorting
//it will change original array
//5,9,1200,4,3000 -->4,5,9,1200,3000 (expected)asscending number

// const num = [5,9,1200,4,3000]

// num.sort();
// console.log(num);

// num.sort((a,b)=> a-b)
// console.log(num)

// a-b ----> ascending order -1 0 1
// b-a ----> descending order 1 0 -1

// const product = [
//     {product :1 , productName :"p1" , price:3000},
//     {product :2 , productName :"p2" , price:7000},
//     {product :3 , productName :"p3" , price:2500},
//     {product :4 , productName :"p4" , price:300}
// ]

// low to high---------------

// product.sort((a,b)=> {
//     return a.price -b.price
// });
// console.log(product);

//high to low--------------

// const highToLow = product.slice(0).sort((a,b)=> {
//     return b.price - a.price
// });
// console.log(highToLow);

// we use slice method bcoz it will create new array and it will not change the og

//Find method--------------------------------------------------------------------------------------------------------------

// const myNewArray = ["hello" , "gogog" , "you" , "Awsome"]

// function isLength3(string){
//     return string.length ===3
// }
// const ans = myNewArray.find(isLength3)
// console.log(ans)

// const users =[
//     {userId :1 , userName :"gogo"},
//     {userId :2 , userName :"shivani"},
//     {userId :3 , userName :"aditi"},
//     {userId :4 , userName :"rashmi"},
//     {userId :4 , userName :"Ram"},
//     {userId :4 , userName :"Happy"},
    
// ]

// const myUser = users.find((users)=>users.userId===3)
// console.log(myUser);

// -----------------------------------------------------------every Method---------------------------------------------------------------------------------------------------------

//call back function  ---> true /false (boolean)
// every method -- > true /false(boolean)

//it will check every element and then give true or false

// const numbers = [2,4,5,6,8,10] // in every method it will check every element with given condition ifin the middle it get satsfied it will give false

// const ans = numbers.every((number)=>number%2===0)
// console.log(ans)


// function isEven(numbers){
//     return numbers%2===0
// }
// const ans = numbers.every(isEven)
// console.log(ans)

// const userCart = [
//     {product :1 , productName :"p1" , price:3000},
//     {product :2 , productName :"p2" , price:7000},
//     {product :3 , productName :"p3" , price:2500},
//     {product :4 , productName :"p4" , price:300}
// ]

// const ans =userCart.every((CartItem) => CartItem.price < 2500);
// console.log(ans)

//-----------------------------------------------------------------some method---------------------------------------------------------------------------
// it will true when any one condition satsfied
// kya ek bhi nummber esa hai jo even han 
// true ==> if find any one number that divide by 2
//flase only when not getting any number

// const number = [3,5,8,9]

// const ans = number.some((number)=>number%2==0)
// console.log(ans)

// const userCart = [
//     {product :1 , productName :"p1" , price:3000},
//     {product :2 , productName :"p2" , price:7000},
//     {product :3 , productName :"p3" , price:2500},
//     {product :4 , productName :"p4" , price:300}
// ]

// const oye = userCart.some((userCart)=>userCart.price < 2000)
// console.log(oye)

//---------------------------------------------------------------------fill method-------------------------------------------------------------------------------------------------------
//value , start , end

// const myArray = new Array(10).fill(0);
// console.log(myArray)

// const myArray2 = [3,5,8,9,5,7,8,9,4,5,6]
// myArray2.fill(-1,2,5)
// console.log(myArray2)

//------------------------------------------------------------------------splice method-------------------------------------------------------------------------------------------------

// Start , Delete , Insert 

// const myArray2 = ["item1", "item2","item3","item4"]

//delete
//start index you have to delete and how much you want to delete

// let deleted =  myArray2.splice(1,2)
// console.log("deleted item" ,myArray2)

//insert

//in which uh want to insert , hiw much you want to delete , inserted item

// myArray2.splice(1,0,'inserted item')
// console.log(myArray2)


//insert and delete together
//start , delet how item , inserted item1 , inserted item2

// const deletedItem = myArray2.splice(1,2,"insterd item2" , "insterd item2")
// console.log("insterd item" , deletedItem)

//------------------------------------------------------------- iterable // array like object--------------------------------------------------------------------------------------------------------

//jispe  hum for of loop laga sakte 
//strating , array are iterable
// string and array 

// let name = "govind"
// for(let char of name){
//     console.log(char)
// }

// const item = ["item1", "item2","item3","item4"]
// for(let item of items){
//     console.log(item)
// }


// array like object 
//jiske pas length property hoti han
// aur jiko hum index se access kar sakte hai 
// example : - string

//array list object
// const name = "govind"
// console.log(name.length);
// console.log(name[2]);

//------------------------------------------------------- Sets ------------------------------------------------------------------------------

// sets (it is iterable)
// store data - every data Types
// sets also have its own methods
// no index- based access--
// order is not gaurantee
// uniquness items only (no duplicates allowed)
// it do not allowerd duplicate


// const numbers = new Set([1,2,2,3,3]);
// numbers.add(5)
// numbers.add(6)
// numbers.add(7)
// numbers.add(8)
// numbers.add(9)
// numbers.add(10)
// numbers.add(11)
// numbers.add(12)
// numbers.add(['item2','item3']) // it will add becoz they are store in diffrent memory 
// numbers.add(['item2','item3'])
// console.log(numbers)

// const numbers2 = new Set(["abc"]);
// console.log(numbers2)

// if(numbers.has(1)){
//     console.log("1 is present")
// }else{
//     console.log("not present")
// }

// for(number of numbers){ // its iterable
//     console.log(number)
// }

// const ids = [1,2,4,4,5,6,5,6,1];
// const uniqueElement = new Set(ids);
// console.log(uniqueElement)
// console.log(ids) // it will not change original

// let length = 0;
// for(let element of uniqueElement){
//     length++;
// }
// console.log(length)

// --------------------------------------------------------------------------- Maps - Object ------------------------------------------------------------------------------------------------------

//map is an iterable

// store data in another fashion

//store key value pair(like object)
//duplicate keys are not allowed like object

// diffrent between maps and objects

//object can only have string or symbol
//as key

// in maps you can use anything as key
//like array , number , string

//in this we can use for of loop 
//but in object we dont use for of we can use for in loop

//object literals
// keys --> string --> 99.9%
//key -- > sybmol --> 1%

// const person = {
//     firstName: "gogo",
//     age:7,
//     1:"one"
// }
// console.log(person.firstName)
// console.log(person.age)

// for(let key in person){ // it convert everything into string
//     console.log(typeof key);
// }

// key value pair---------------------------------------------------

// const person = new Map(); // how to create

// person.set('firstname' , 'Gogo')
// person.set('age' , 7)
// person.set(1 , 'one')

// console.log(person)

// console.log(person.get('firstname')) // this is way to access the value 

// console.log(person.keys()); //  { 'firstname', 'age', 1 } // acess foe keys
// console.log(person.values()); //   { 'Gogo', 7, 'one' } // access for value

// for(let key of person.keys()){  // this is how to iterate for value n key 
//     console.log(key , typeof key)
// }

//for of loop

// for(let key of person){ 
//     console.log(typeof key); // object
// }

// for(let key of person){ 
//     console.log(Array.isArray (key)); // true
// }

// for(let [key , value] of person){
//     console.log(key , value)
// }

// const person ={
//     'firstName' : 'gogo' ,
//      'age': 7}
// const person2  ={
//     'firstName' : 'govind' ,
//      'age': 10}
// const userInfo =  new Map();
// userInfo.set(person ,{age:8 , gender :"male"})
// userInfo.set(person2 ,{age:10 , gender :"female"})
// console.log(userInfo)

//Map(1) { { firstName: 'gogo', age: 7 } => { age: 8, gender: 'male' } } --> answer


// console.log(person.age)
// console.log(person2.age)
// console.log(userInfo.get(person).gender);
// console.log(userInfo.get(person2).gender);

// clone using object.assign

//memory (heap)

// const obj = {
//     key1 : "value1" ,
//     key2 : "value2"
// }

// const obj2 =obj;
// obj.key3 ="value3";
// console.log(obj);
// console.log(obj2);// same answer becoz the memory is store in heap 

// const obj2 = {...obj}
// obj.key3 ="value3";
// console.log(obj) // it will not be same becoz the we have done cloning in right way 
// console.log(obj2)

//--------------------------------------------------------------------optional chaing-------------------------------------------------------------------------------------------------------

// const user ={
//     'firstName' : 'gogo' ,
//     //  'address': {houseNumber :'1234'}
// }

// console.log(user?.firstName);
// console.log(user?.address?.houseNumber) // -- > ?. agar exist karte han toh value de nhi toh undefined de but errror nhi

//------------------------------------------------------------------- Methods ------------------------------------------------------------------------------------------------------------------------

// function inside object 

// const person = {
//     firstName : "Gogo",
//     age : "25" ,
//     about: function(){
//         console.log("person name is GOgo and person is 25")
//     }
// }
// console.log(person.about) // give you function 
// person.about() // it will give answer

// const person = {
//     firstName : "goooo", // now uh can change here any thing 
//     age : "25" ,
//     about: function(){
//         console.log(`person name is ${this.firstName} and age is ${this.age}`) // here we used this for accessing 
//     }
// }
// this -- > wo object han iss function ko call kar raha han han method and function ke andar --> imp

// person.about();

// 2---->

// function personInfo(){
//     console.log(`person name is ${this.firstName} and age is ${this.Age2}`)
// }

// const person1 = {
//     firstName : "Krsna",
//      Age2 : 95 ,
//      about : personInfo // uppar wala function idhar set han 

// }
// const person2 = {
//     firstName : "Kamna",
//      Age2 : 18 ,
//      about : personInfo

// }
// const person3 = {
//     firstName : "Krish",
//      Age2 : 35 ,
//      about : personInfo

// }
// personInfo() // it will give undefined
// person1.about(); // it will give value with person1  // abb wo this yea person hoga jo call kiya
// person2.about();
// person3.about();

//--------------------------------------------------------------------------- this ------------------------------------------------------------

// console.log(this); // it will give you window
// console.log(window); // it will give you window

// "use strict" // The purpose of "use strict" is to indicate that the code should be executed in "strict mode". With strict mode, you can not, for example, use undeclared variables. The numbers in the table specify the first browser version that fully supports the directive. 
//              //You can use strict mode in all your programs. 

// function myFunc(){
    
//     console.log(this);
// }
// window.myFunc();

//--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

//call
//apply
//blind

// function hello(){
//     console.log("hello world")
// }
// hello.call();

// const user1 = {
//     firstName : "Gogo",
//     age : 25,
//     about : function (hobby , favMusicican){
//         console.log(this.firstName , this.age , hobby , favMusicican)
//     }
// }

// const user2 = {
//     firstName : "Govind",
//     age : 29,
    
// }
// user1.about.call(user2) // we can call user 1 function to user2 by the help of call

// user1.about.call() // it will give undefined
// user1.about.call(user1) // it will give value


// user1.about.call(user2 , "guitar" , "moazrt") // it will give value

//2 <-----------this is secound method ------------>

// function about  (hobby , favMusicican){
//     console.log(this.firstName , this.age , hobby , favMusicican)
// }
// const user1 = {
//     firstName : "Gogo",
//     age : 25,
   
// }
// const user2 = {
//     firstName : "Govind",
//     age : 29,
    
// }
// about.call(user2 , "guitar" , "moazrt")

// apply ------------------------------------------------------------------------->

// function about  (hobby , favMusicican){
//     console.log(this.firstName , this.age , hobby , favMusicican)
// }
// const user1 = {
//     firstName : "Gogo",
//     age : 25,
   
// }
// const user2 = {
//     firstName : "Govind",
//     age : 29,
    
// }
// about.apply(user2 , ["guitar" , "moazrt"]) // we just want to apply in array thats it

// Bind----------------------------------------------------------------------------------->

// function about  (hobby , favMusicican){
//     console.log(this.firstName , this.age , hobby , favMusicican)
// }
// const user1 = {
//     firstName : "Gogo",
//     age : 25,
   
// }
// const user2 = {
//     firstName : "Govind",
//     age : 29,
    
// }
// const func = about.bind(user2 , "guitar" , "moazrt"); // it will give function only so uh can use
// func();

//-----------------------------------------------small warning-----------------------------------------------------------------------------------------------------------------------------

// const user1 = {
//     firstName : "gogo",
//     age : 8 ,
//     about : function (){
//         console.log(this.firstName , this.age)
//     }
// }
// dont do this mistake


//user1.about();
// const myFunc = user1.about; // it will give uh error bcoz its will not calling
// myFunc();

// const myFunc = user1.about.bind(user1) // it will give value by using bind 
// myFunc();

// ----------------------------------------------------------------------------------------arrow function --------------------------------------------------------------------------------------------------------
//arrow function dont have this
// he take value from its surrounding


// const user1 = { // while arrow function it will will not give value wo this ek lever uppar se leta han 
//     firstName : "gogo",
//     age : 8 ,
//     about :  () => {
//         console.log(this.firstName , this.age)
//     }
// }
// user1.about(user1); // undefined undefined

//------------------------------------------------------------------------short syntax ---------------------------------------------------------------------------------------------------

//this function and upper function are both the equavlent

// const user1 = { 
//     firstName : "gogo",
//     age : 8 ,
//     about (){ // method
//         console.log(this.firstName , this.age)
//     }
// }
// user1.about();

//------------------------------------------------------------------------create function to create multiple objects -------------------------------------------------------------------------------------------------------------

// const user = {
//     firstName : 'gogo',
//     lastName : "lowanshi",
//     email : "gogo@gmail.com",
//     age : 29,
//     address : "202 , gauri mauli",
//     about : function (){
//         return `${this.firstName} is ${this.age} years`
//     },
//     is18 : function(){
//         return this.age >=18;
//     }
// }
// function (that fucntion create object)
// 2. add key value pair
//3.object ko return krega

// function createUser(firstName , lastName ,email,age,address){
//     const user={};
//     user.firstName = firstName;
//     user.lastName = lastName;
//     user.email = email;
//     user.age = age;
//     user.address = address
//     user.about = function (){
//         return `${this.firstName} is ${this.age} years`
//     },
//     user.is18 =  function(){
//         return this.age >=18;
//     }
//     return  user;

// }
// updating everything in upper function 

// const user1 = createUser("naman", "sadh ", "nama@gmail.com" , 3 , "khopoli")
// console.log(user1);

// // const user2 = createUser("kj", "sadh ", "nama@gmail.com" , 3 , "khopoli")
// // console.log(user2);

// // const user3 = createUser("pooja", "sadh ", "nama@gmail.com" , 3 , "khopoli")
// // console.log(user3);

// const is18 = user.is18(); // calling method 
// console.log(is18)

//2 type ---->
// this method also have problem

// const userMethods = {
//     about : function (){
//         return `${this.firstName} is ${this.age} years`
//     },
//    is18 :  function(){
//         return this.age >=18;
//     }
// }

// function createUser(firstName , lastName ,email,age,address){
//     const user={};
//     user.firstName = firstName;
//     user.lastName = lastName;
//     user.email = email;
//     user.age = age;
//     user.address = address;
//     user.about = userMethods.about; // we are writing refrence here so we can here
//     user.about = userMethods.is18;
//     return  user;

// }

// const user1 = createUser("naman", "sadh ", "nama@gmail.com" , 19 , "khopoli")
// console.log(user1);

// const user2 = createUser("kj", "sadh ", "nama@gmail.com" , 21 , "khopoli")
// console.log(user2);

// const user3 = createUser("pooja", "sadh ", "nama@gmail.com" , 3 , "khopoli")
// console.log(user3);

// console.log(user1.about()) // to check refrence method we are used here
// console.log(user3.about())


// type---> 3 ------------------------------------->

// const userMethods = {
//     about : function (){
//         return `${this.firstName} is ${this.age} years`
//     },
//    is18 :  function(){
//         return this.age >=18;
//     },
//     sign : function(){
//         return 'toon na na na na '
//     }
// }

// function createUser(firstName , lastName ,email,age,address){
//     const user={};
//     user.firstName = firstName;
//     user.lastName = lastName;
//     user.email = email;
//     user.age = age;
//     user.address = address;
//     user.about = userMethods.about; // we are writing refrence here so we can here call n it will not repeat 
//     user.about = userMethods.is18;
//     return  user;

// }

// const user1 = createUser("naman", "sadh ", "nama@gmail.com" , 19 , "khopoli")
// console.log(user1);

// const user2 = createUser("kj", "sadh ", "nama@gmail.com" , 21 , "khopoli")
// console.log(user2);

// const user3 = createUser("pooja", "sadh ", "nama@gmail.com" , 3 , "khopoli")
// console.log(user3);

// console.log(user1.about()) // to check refrence method we are used here
// console.log(user3.about())

//------------------------------------------------- soln using object create ---------------------------------------------------------------------------------------------------------------------------------

// const obj1 = {
//     key1 : "value1",
//     key2 : "value2",
//     key3 : "value3"
// }

// const obj2 = Object.create(obj1); // it is protype of obj2 in obj1 

// obj2.key3 = "value3";
// obj2.key2 = "unique" // if this is not their then it check in obj1

// console.log(obj2);

//------------------------------------------------------__proto__----------------------------------------------------------------------------------------------------------------------------------------------

//Refrence

// offical ecmascript documetation

// [[prototype]] , __proto --> same

// prototype --> this is not same 


// const obj1 = {
//     key1 : "value1",
//     key2 : "value2",
//     key3 : "value3"
// }

// const obj2 = Object.create(obj1); // it is protype of obj2 in obj1 
// obj2.key3 = "value3";
// obj2.key2 = "unique" // if this is not their then it check in obj1

// console.log(obj2);

// console.log(obj2.__proto__);

//-----------------------------------> type 2

// const userMethods = {
//     about : function (){
//         return `${this.firstName} is ${this.age} years`
//     },
//    is18 :  function(){
//         return this.age >=18;
//     },
//     sign : function(){
//         return 'toon na na na na '
//     }
// }

// function createUser(firstName , lastName ,email,age,address){
//     const user= Object.create(userMethods);
//     user.firstName = firstName;
//     user.lastName = lastName;
//     user.email = email;
//     user.age = age;
//     user.address = address;
//     return  user;

// }

// const user1 = createUser("naman", "sadh ", "nama@gmail.com" , 19 , "khopoli")
// console.log(user1.is18)
// console.log(user1.about())
// console.log(user1.__proto__); // checking prototype

//----------------------------------------------------------------------------prototype-------------------------------------------------------------------------------

// its a object // free space

// function hello1(){
//     console.log("hello...")
// }

//javascript function  ===> function + object

// console.log(hello1.name);

// you can add your own properties

// hello1.myOwnProprties = "very unique value";
// console.log(myOwnProprties)

// name property -- > tells function name;

// function provides more usefull properties,

//console.log(hello.prototype); // {}

//only function provides prototype property // it will not work on object and array

// if(hello1.prototype){
//     console.log("prototype is present")
// }
// else{
//     console.log("prototype is not present")
// }

// function hello1(){
//         console.log("hello...")
//     }

// hello1.prototype.abc="hi babe";
// hello1.prototype.cde="yup";
// hello1.prototype = function hero(){
//     console.log("i love me")
// }
// console.log(hello1.prototype)//{ abc: 'hi babe', cde: 'yup' }

//--------------------------> type 3 prototype

// const userMethods = {
//     about : function (){
//         return `${this.firstName} is ${this.age} years`
//     },
//    is18 :  function(){
//         return this.age >=18;
//     },
//     sign : function(){
//         return 'toon na na na na '
//     }
// }

// function createUser(firstName , lastName ,email,age,address){
//     const user= Object.create(createUser.prototype);
//     user.firstName = firstName;
//     user.lastName = lastName;
//     user.email = email;
//     user.age = age;
//     user.address = address;
//     return  user;
// }
// createUser.prototype.about =  function (){
//             return `${this.firstName} is ${this.age} years`
// }
// createUser.prototype.is18 =  function(){
//             return this.age >=18;
//  }
// createUser.prototype.sign =  function(){
//     return 'toon na na na na '
// }

// const user1 = createUser("naman", "sadh", "nama@gmail.com" , 19 , "khopoli")
// console.log(user1);
// console.log(user1.about());
// console.log(user1.is18())

//-------------------------------------------------- NEW -----------------------------------------------------------------------------------------
// New Keyword

// 1. empty object --> this = {}
// 2. retrun --> this
// 3. Object.create(createUser.prototype);
// constructor function 

// function creatUser(firstName , age){
//     this.firstName = firstName;
//     this.age = age;
// }
// creatUser.prototype.about = function(){
//     console.log(this.firstName , this.age)
// }
// const user1 = new creatUser("gogo" , 20); // if this value is not getting in this user toh protype tak proto lekar jayega
// console.log(user1);

// type 2 --> 


// __proto__ --> offical ecmascript --> [[prototype ]] is written like this.

// function createUser(firstName , lastName ,email,age,address){
//     this.firstName = firstName;
//     this.lastName = lastName;
//     this.email = email;
//     this.age = age;
//     this.address = address;
    
// }
// createUser.prototype.about =  function (){
//             return `${this.firstName} is ${this.age} years`
// }
// createUser.prototype.is18 =  function(){
//             return this.age >=18;
//  }
// createUser.prototype.sign =  function(){
//     return 'toon na na na na '
// }

// const user1 = new createUser("naman", "sadh", "nama@gmail.com" , 19 , "khopoli")
// console.log(user1);
// console.log(user1.is18());
// console.log(user1.about());

//--------------------> type 3 using C --> constructor method

// function CreateUser(firstName , lastName ,email,age,address){
//     this.firstName = firstName;
//     this.lastName = lastName;
//     this.email = email;
//     this.age = age;
//     this.address = address;
    
// }
// CreateUser.prototype.about =  function (){
//             return `${this.firstName} is ${this.age} years`
// }
// CreateUser.prototype.is18 =  function(){
//             return this.age >=18;
//  }
// CreateUser.prototype.sign =  function(){
//     return 'toon na na na na '
// }

// const user1 = new CreateUser("naman", "sadh", "nama@gmail.com" , 19 , "khopoli")
// using capital  C here for constructor
// console.log(user1);
// console.log(user1.is18());
// console.log(user1.about());

// ------------------------------------------------------------------------ hasOwnProperty --------------------------------------------------------------------------------------

// function CreateUser(firstName , lastName ,email,age,address){
//         this.firstName = firstName;
//         this.lastName = lastName;
//         this.email = email;
//         this.age = age;
//         this.address = address;
        
//     }
//     CreateUser.prototype.about =  function (){
//                 return `${this.firstName} is ${this.age} years`
//     }
//     CreateUser.prototype.is18 =  function(){
//                 return this.age >=18;
//      }
//     CreateUser.prototype.sign =  function(){
//         return 'toon na na na na '
//     }
    
//     const user1 = new CreateUser("naman", "sadh", "nama@gmail.com" , 19 , "khopoli")
//     // using capital  C here for constructor
   
//     // if you want to print CreateUser only 

//     for(let key in user1){
//         if(user1.hasOwnProperty(key)){
//             console.log(key);
//         }
//     }

//answer 

// firstName
// lastName
// email
// age
// address

//-----------------------------------------------------------more about prototype ----------------------------------------------------------------------------------------

// let number = [1,2,3]
// number 

// console.log(number)

//----------------------------------------------------------------class---------------------------------------------------------------------------------
//2015 --> /es6 (class has came)
//class keyword
//class are fake
//class make easy 

// class CreateUser{
//     constructor(firstName , lastName ,email,age,address){ // it will create object
//         console.log("constructor called")
//             this.firstName = firstName;
//             this.lastName = lastName;
//             this.email = email;
//             this.age = age;
//             this.address = address;

//      }
//     about(){
//         return `${this.firstName} is ${this.age} years`
//     }
//     is18(){
//         return this.age >= 18;
//     }
//     sing(){
//         return 'toon na na na na '
//     }
//     func(a){
//         console.log(a);

//     }
// }
// const user1 = new CreateUser("naman", "sadh", "nama@gmail.com" , 19 , "khopoli")
// // without new can't call contructor
// console.log(user1.is18()) // calling method inside class!
// console.log(user1.about())

// // how to check prototype
// console.log(Object.getPrototypeOf(user1));

// user1.func("gogo")

//---------------------------------------------------> class practice and extend keywords---------------------------------------------------------------->

// class Animal{
//     constructor(name ,age){
//         this.name =name;
//         this.age =age;
//     }
//     eat(){
//         return `${this.name} is eating`
//     }

//     isSuper(){
//         return this.age <= 1;
//     }

//     isCute(){
//         return true;
//     }
// }

// simple class type 1------------------------------->
// const animial1 = new Animal("Tom" , 2)
// console.log(animial1);
// console.log(animial1.eat());
// console.log(animial1.isSuper());

// class Dog{
//     constructor(name ,age){
//         this.name =name;
//         this.age =age;
//     }
//     eat(){
//         return `${this.name} is eating`
//     }

//     isSuper(){
//         return this.age <= 1;
//     }

//     isCute(){
//         return true;
//     }

// }
// const tommy = new Dog("toy" , 3)
// console.log(tommy.eat());


// in this we have inheritance the class  from animals to dog!
// dog is sub class of animlas while using extends!

// class Dog extends Animal{

// }
// const tommy      =   new Dog("tommy" , 3)
//this is object   //here i am calling constructor
// console.log(tommy.isCute())

// Type 2------------------------------------------------>
// object / instances are same

//same method in base class:-

// class Animal{
//     constructor(name ,age){
//         this.name =name;
//         this.age =age;
//     }
//     eat(){
//         return `${this.name} is eating`
//     }

//     isSuper(){
//         return this.age <= 1;
//     }

//     isCute(){
//         return true;
//     }
// }

// class Dog extends Animal{
//     constructor(name , age , speed){
//         super(name,age); // using super will ihertiance from upper class
//         this.speed = speed
//     }
//     eat(){ // if he will not find here then it will so upper class to check
//         return `Modified Eat : you know he dont this much so dont ask him to eat`
//     }
//     run(){
//         return `${this.name} is running at this speed of ${this.speed}`
//     }  
// }
// const tommy = new Dog("baccha" , 3 ,45);
// console.log(tommy)
// console.log(tommy.run())
// console.log(tommy.eat())

//------------------------------------------------------getters / setters

// class Person{
//     constructor(firstName , lastName , age){
//         this.firstName = firstName;
//         this.lastName = lastName;
//         this.age =age
//     }
//     get fullName(){ // after getter
//         return `${this.firstName} ${this.lastName}`
//     }

//     // for setter
//     setName(firstName ,lastName){
//         this.firstName = firstName;
//         this.lastName = lastName;
//     }
// }
    
// const person1 = new Person("gogo" , "lownashi" ,25)
// console.log(person1.fullName());

// using like property
// using get n set // in upper function 

// console.log(person1.firstName) // while using get we dont need to use () like uh did in above
// console.log(person1.fullName)

//setters

// console.log(person1.firstName)
// console.log(person1.fullName)

// person1.setName("mohit" , "rai") // changed then name while using set

// console.log(person1.firstName) 
// console.log(person1.fullName)

//-----------------------------------------------Type - 2 ---------------------------------------------------------------------------------->


// class Person{
//     constructor(firstName , lastName , age){
//         this.firstName = firstName;
//         this.lastName = lastName;
//         this.age =age
//     }
//     get fullName(){ // after getter
//         return `${this.firstName} ${this.lastName}`
//     }

//     // for setter
//     set fullName(fullName){
//         const[firstName , LastName] = fullName.split(" ")
//         this.firstName = this.firstName;
//         this.lastName = this.lastName
//     }
//     }

// const person1 =new Person("gogo" , "kapoor" , 7)
// person1.fullName = "Govind Lowanshi";
// console.log(person1);

//-------------------------------------------------------------------static method and properties ------------------------------------------------------------------------------------->

class Person{
    constructor(firstName , lastName , age){
        this.firstName = firstName;
        this.lastName = lastName;
        this.age =age
    }
    static classInfo(){
        return `this parent class`
    }
    static desc = "oye its a static property"
    get fullName(){ // after getter
        return `${this.firstName} ${this.lastName}`
    }

    // for setter
    set fullName(fullName){
        const[firstName , LastName] = fullName.split(" ")
        this.firstName = this.firstName;
        this.lastName = this.lastName
    }

    eat(){
             return `${this.name} is eating`
            }
        
    isSuper(){
                return this.age <= 1;
            }
        
    isCute(){
                return true;
            }
    }


const person1 = new Person("Gogooo" , "krsna" , 9)
console.log(person1.firstName) // here you can call any function

const ans = Person.classInfo(); // if it is static uh can call only with parents call 
console.log(ans)

console.log( Person.desc) // this is how you call static property.

