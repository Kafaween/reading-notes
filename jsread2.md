 # Bitwise logical operators
 
 The operands are converted to thirty-two-bit integers and expressed by a series of bits (zeros and ones).
 Numbers with more than 32 bits get their most significant bits discarded. 
 For example, the following integer with more than 32 bits will be converted to a 32 bit integer:
 Before: 1110 0110 1111 1010 0000 0000 0000 0110 0000 0000 0001
After:               1010 0000 0000 0000 0110 0000 0000 0001


# Bitwise shift operators
The bitwise shift operators take two operands: the first is a quantity to be shifted,
and the second specifies the number of bit positions by which the first operand is to be shifted. 
The direction of the shift operation is controlled by the operator used.

# Logical operators
ogical operators are typically used with Boolean (logical) values; when they are, they return a Boolean value. However, 
the && and || operators actually return the value of one of the specified operands,
so if these operators are used with non-Boolean values,they may return a non-Boolean value. The logical operators are described in the following table.

var a1 =  true && true;     // t && t returns true
var a2 =  true && false;    // t && f returns false
var a3 = false && true;     // f && t returns false

var o1 =  true || true;     // t || t returns true
var o2 = false || true;     // f || t returns true
var o3 =  true || false;    // t || f returns true

# String operators
In addition to the comparison operators, which can be used on string values, the concatenation operator (+) concatenates two string values together, returning another string that is the union of the two operand strings.

For example,
console.log('my ' + 'string'); // console logs the string "my string".

# For loop
A for loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.
A for statement looks as follows:
for ([initialExpression]; [conditionExpression]; [incrementExpression])
  statement
  
  for example:
  for (let i = 0; i < 5; i++) {
     consol.log(i) 
     }
     
     
# A while statement executes its statements as long as a specified condition evaluates to true. A while statement looks as follows:

while (condition)
  statement
  
  for example:
  
  let n = 0;
let x = 0;
while (n < 3) {
  n++;
  x += n;
}


// Infinite loops are bad!
while (true) {
  console.log('Hello, world!');
}
      
      
