# Day 2 Encapsulation

## Daily Journal

Morning Challenge 
---------------------------------------------------------------------------
function mostCommonLetter(str) {
    let mostCommon = ''

    let letters = {}
    for (let i = 0; i < str.length; i++) {
        let char = str[i]
        letters[char] = letters[char] || 0
        letters[char]++
    }

    let max = 0
    let largestChar = ''

    for (let char in letters) {
        if (letters[char] > largest) {
            largest = letters[char]
            largestChar = char
        }
    }

    return mostCommon
}
-----------------------------------------------------------------------
Afternoon Challenge - https://alecvictory.github.io/spring21-gregslist/

Read Advancing with JS > Encapsulation in JavaScript and answer the following questions

What is the purpose of Encapsulation?

The purpose is for bundling data and the methods that work that have access to the data from outside the bundle.

What were some of the problems with closures and the underscore prefix?

breaking changes - 
changes frequently happen to code and using closures and underscore prefix calls on the API directly. If the API gets deleted then the closure is broken

closures are fine for arrays but break streams

closures do not support self-documenting code

How do we create private variables in a ES6 Class? Why would you do this?

its available using babel with stage-3 feature enabled