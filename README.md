# Impure-functions
 
let obj = { a: 0 }
const impure = (input) => {
 // Modifies input.a
 input.a = input.a + 1;
 return input.a;
}
let b = impure(obj)
console.log(obj) // Logs { "a": 1 }
console.log(b) // Logs 1
