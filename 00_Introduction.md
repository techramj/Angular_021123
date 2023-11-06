# JavaScript

1. Front end
2. Back end
3. Mobile
4. Desktop

## Front end java script
1. Angular
2. React
3. Vue


JQuery: It is the popular library of JS. Simplifies HTML Dom manupulation , event handling, network request and many more.

Vanilla JS: java script without any libraries.

## Backend
  Node JS

# Mobile
    React native
    native script

# JS feature:
    1. Js is an interpreted language (executed without compiling)
    2. JS is dynamically and weakly typed

    var a = 10;  //js  
    typeof a;
    a = "apple";
    typeof a


    var b;

    int a = 10;  //c prog/java
    a = "apple";

    int b;

## diff between var and let.
       var  => function scope
       let  => block scope


       function foo(){
        if(true){
            var a = 10; //function
            let b  = 10; //block
            c= 30; //global
        }

        console.log('a = ',a);
        //console.log('b =', b);
        console.log('c =', c);
      }

## datatype
1. Number
            let natural = 100;
            let decimal = 100.1;
            let hex = 0XA;
            let binary = 0b111;
            let octal = 0o73;
            let tenLakhs = 10e6;

            NaN & Infinity is specail type of number


2. String
        let singleQuote = 'stirng';
        let doubleQoute = "string";
        let backTick = `string`;  //below esc keypad

3. Boolean
        true and false are two value.
        falsely value
            false
            0
            0n
            '', "", ``
            null
            NaN
            undefined

4. undefined
    let a;
    value of a and type of a is undefined

5. Object
   JS objects are different compare to other language(c++, java, dot.net)
   js object are assiged by reference

    let person = {
            name: "Jack", age:35
        };

    //access to properties
    person.name
    person['name']

    ## Null is an object
        let a = null;
        console.log(typeof a); //object



6. Bigint
        //bigint


        let x = 12345678912345;
        console.log(x); // 12345678912345

        let y =  12345678912345678912;
        console.log(y); //12345678912345680000

        let z = 123456789123456789123456789n;
        console.log(z); //123456789123456789123456789n
        console.log(typeof z); //bigint

        let p = 1n;
        let q  = p + BigInt(2);
        console.log(q, typeof q);


7. Symbol
    let a = Symbol(10);
    let b = Symbol(10);
    console.log(a, typeof a, a==b);


8. function





git branch -M main
git remote add origin https://github.com/techramj/Angular_021123.git
git push -u origin main







