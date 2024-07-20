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


      
