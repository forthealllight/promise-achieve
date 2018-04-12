# promise-achieve
a funcion named myPromise to achieve Promise/A+ Standard
## Use ##

the myPromise.js is a function that achieves Promise/A+

    var myPromise=require("./myPromise.js");
    var p=new myPromise(function(resolve,reject){
    });
    
## Test ##

if you want to test myPromise satisfy the Promise/A+ or not

    npm install -g promises-aplus-tests 
    
after that,

    promises-aplus-tests  myPromise.js
    
    
