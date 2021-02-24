# Reverse-String
A simple reverse string app

const readline = require('readline').createInterface({
    input: process.stdin,
    output: process.stdout
  })
  
  readline.question(`Enter a string to reverse it: `, (number) => {
    var reversedNumber = number.toString().split("").reverse().join("");
    // var reversedNumber = parseInt(number.toString().split("").reverse().join(""));
    console.log(reversedNumber);
    readline.close()
  })
