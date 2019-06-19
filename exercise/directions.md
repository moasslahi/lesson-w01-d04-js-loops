

# Exercises: JavaScript loops

Paste your answers into this file.

<br>

## Print every number from 0 to 10

```

var count = 0;
while (count <=10){
console.log(count);
count = count +1;
}


```

<br>

## Print every number from 10 to 0

```
var count = 10;
while (count >=0){
console.log(count);
count = count -1;
}

```

<br>

## Print every number from 4 to -16

```
var count = 4;
while (count >=-15){
console.log(count);
count = count -1;
}

```

<br>

## Print every fifth number from 8 to 41

```
var count = 8;
while (count <=48){
console.log(count);
count = count +5;
}

```

<br>

## The classic Fizzbuzz Program

For every `number` between 1 and 100...

If the `number` is evenly divisible by 3, print "Fizz"

If the `number` is evenly divisible by 5, print "Buzz"

If the `number` is evenly divisible by 3 AND evenly divisible by 5, print "Fizzbuzz"


```
var count = 0;
while (count <=100){
	if (count %3==0){
		console.log("fizz")}
		count = count +1;
	if (count %5==0){
		console.log("buzz")}
		count = count +1;
	if (count %3==0 && count %5==0){
		console.log("fizzbuzz")}
		count = count +1;
	
	}

```

<br>


## The even/odd reporter

Write a for loop that will iterate from 0 to 20. For each iteration, it will check if the current number is even or odd, and report that to the screen (e.g. "2 is even").

```
var count = 0;
while (count <=20){
	if (count %2===0){
		console.log('even')}
		count = count +1;
	if (count %1===0){
		console.log('odd')}
		count = count +1;
	
	}
```

<br>

## Multiplication Tables

Write a for loop that will iterate from 0 to 10. For each iteration of the for loop, it will multiply the number by 9 and log the result (e.g. "2 * 9 = 18").

Bonus: Use a nested for loop to show the tables for every multiplier from 1 to 10 (100 results total).


```
var count = 0;
while (count <=10){
	console.log(count * 2);
	count = count +1;
```

<br>

## The Grade Assigner

Check the results for every value from 60 to 100 - so your log should show "For 89, you got a B. For 90, you got an A.", etc.

```
function assigngrade(counter) {
  if (counter >=90) {
    return "A"; 
  } else if (counter >=80) {
    return "B";
  } else if (counter >=70) {
    return "C";
  } else if (counter >=60) {
    return "D";
  } else {
    return "F";
  }
}

for (i = 60; i <=100;i++) {
  console.log("for" + i + ", you got a " + assingrade(i))
}




}

```
