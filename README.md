The never type in TypeScript is a
special type that 
represents values that can never be reached. 
This type is typically used to
represent errors or exceptions.
For example, the following
function will always throw an error, 
so its return type is never : function
divideByZero(x: number) { return x / 0; }
