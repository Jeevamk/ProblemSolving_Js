# ProblemSolving_Js ✨

# Reverse a String ,
a) name = 'jeeva mk'
   console.log(name.split("").reverse().join(""))

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

      
