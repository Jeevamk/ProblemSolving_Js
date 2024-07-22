# JavaScript Problem-Solving Exercises ✨

## Table of Contents
1. [Reverse a String](#reverse-a-string)
2. [Find the Largest Number in an Array](#find-the-largest-number-in-an-array)
3. [Sum of All Numbers in an Array](#sum-of-all-numbers-in-an-array)
4. [Count the Number of Vowels in a String](#count-the-number-of-vowels-in-a-string)
5. [Prime Number or Not](#prime-number-or-not)
6. [Palindrome](#palindrome)
7. [Sort an Array](#sort-an-array)
8. [Factorial](#factorial)

## Reverse a String

### Method 1
```javascript
a) let name = 'jeeva mk';
console.log(name.split("").reverse().join(""));

b) str = 'hello world'
 reversed = ''
 for(let c of str) {
  reversed = c+reversed;
  }
 console.log(reversed)

c) str  = "hello world"
   reversed = ''
   for (i=str.length-1;i>=0;i--) {
      reversed += str[i]
   }
console.log(reversed)

# Find the Largest Number in an Array
arr = [2,4,1,5,4,3]
// large = arr.sort((a,b)=>b-a)
// console.log(large[0])

largest = arr[0]
for(i=0;i<=arr.length;i++) {
    if(arr[i] > largest) {
        largest = arr[i]
    }
}
console.log(largest)

# Sum of All Numbers in an Array
arr =[2,3,6,5,4]
sum = 0
for(i=0;i<arr.length;i++){
    sum +=arr[i]
}
console.log(sum)

# Count the Number of Vowels in a String
let str = 'hello world'
let vowels = 'aeiouAEIOU'
count = 0
for(i=0;i<str.length;i++){
    if(vowels.includes(str[i])){
        count++
    }
    
}
console.log(count)

# Prime number or not
let number = 7
let prime = true;
for ( i=2 ; i<number ; i++ ){
    if (number % i == 0){
        prime = false
    }
}
console.log(prime?"Prime Number":"Not a prime number")

# Palindrom
// input = "assa"
// output = "its palindrome"
// -------------------------------------------
const input = "asspa"
let str = ''
for ( i=input.length-1 ; i >= 0 ; i-- ){
    str += ${input[i]}
}
console.log(input === str ? 'its palindrome' : 'its not palindrome')
// -------------------------------------------

# Sort
const arr = [3,2,5,4,1]
for ( i=0 ; i<arr.length ; i++ ){
    for (j=i+1 ; j<arr.length ; j++){
        if(arr[i]>arr[j]){
            temp = arr[i];
            arr[i] = arr[j];
            arr [j] = temp
        }
    }
}
console.log(arr)

# factorial
// input = 5
// output = 120 (5*4*3*2*1)
// -------------------------------------------

let fact = 1
let input = 5
for ( i=1 ; i <= input ; i++ ){
    fact *= i  
}
console.log(fact)
// -------------------------------------------

function fac (n){
    if (n === 0||n===1){
        return 1
    }else{
        return n*fac(n-1)
    }
}
let facto = fac(6) 
console.log(facto)
//-----------------------------------------------


