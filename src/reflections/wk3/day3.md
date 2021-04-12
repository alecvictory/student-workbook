# Day 3 Forms & Templates

## Daily Journal

Morning Challenge 
---------------------------------------------------------------------------
function factorize(n) {
    let factors = []
    // Check every number starting at 1 -> the number
    for (let i = 1; i <= n; i++) {
        // if the number is a multiple : perfectly divisible into the number (aka no remainder)
        if (n % i == 0) {
            // add to array
            factors.push(i)
        }
    }
    return factors
}
// OUTPUT: array of numbers
console.log(12, factorize(12));
console.log(100, factorize(100));
console.log(123456, factorize(123456));
------------------------------------------------------------------------

Afternoon Challenge - https://alecvictory.github.io/spring21-gregslist/

Read Advancing with JS > An Intro to Javascript Proxy Objects and answer the following questions

What are the two common operations that we will set in the handler?

get 
set

What do you have to make sure you are doing with every Get to insure the value does not become undefined?

you need to use two parameters. the object itself and the property being accessed.

What are some of the benefits of the proxy object that we are using in our structure for applications?

you can use the proxy to change properties and get notified of the changes