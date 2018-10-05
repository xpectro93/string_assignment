# String Exercises

1. console.log the first character of a string.

let stringg = "First";

console.log(stringg[0])

2. console.log the length of a string.

let lengthOf = "Length of a string";

console.log(lengthOf.length);

3. console.log the last character of any string.

let lastChar ="The last letter is Z";

console.log(lastChar[lastChar.length-1])

4. Create a code block that takes a single string variable, and returns a copy of the string with the last letter capitalized. For example:

```js
'jimmy'
// => 'jimmY'
```

let original ="original";
let copy = "";

copy =original.slice(0,7) + original[7].toUpperCase();

console.log(copy);


5. Create a drEvil code block that will take a single number varaible, and log the '<variablbeAmount> dollars',
your code block should add '(pinky)' at the end of the amount if it's 1 million. For example:

```js
let amount = 10
// => 10 dollars
let amount = 1000000
// =>  1000000 dollars (pinky)
```
let aNumero = 1000000;

if (aNumero === 1000000){
  console.log(`${aNumero} dollars (pinky) `);
} else if(aNumero === 1){
  console.log(`${aNumero} dollar`);
}else if (aNumero < 1){
  console.log("No dollar");
}else{
  console.log(`${aNumero} dollars`)
}


6. Create a `verbing` code block. It should take a single string variable. If its length is at least 3, it should add 'ing' to its end, unless it already ends in 'ing', in which case it should add 'ly' instead. If the string length is less than 3, it should leave it unchanged.
For example:

```js
verbing('box')
// => 'boxing'
verbing('train')
// => 'training'
verbing('swimming')
// =>  'swimmingly'
verbing('go')
// =>  'go'
```
let verbing ="boxingly";

if(verbing.slice((verbing.length-5))=== "ingly"){
  console.log(`${verbing}`)
}else if(verbing.slice((verbing.length-3))=== "ing"){
  console.log(`${verbing}ly`)
}else if( verbing.length>=3){
  console.log(`${verbing}ing`)
}else{
  console.log(`${verbing}`)
}


7. Create a `withoutLast` code block that takes a single string variable, and returns a copy of the string without the  last

let woLast="Example";
let copyLast = "";
copyLast = woLast.slice(0,(woLast.length-1))
console.log(copyLast);
