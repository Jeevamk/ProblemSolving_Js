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
      
