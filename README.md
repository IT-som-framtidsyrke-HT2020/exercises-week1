# exercises-week1
### Exercises for each code along lesson of week 1
In this file you will find exercises for all of the sections we have been going through during code alongs.

## Exercises WEEK1

### Values and Variables:
1. Declare variables called "myName", "myCity" and "myAge" and assign values accordning to your ows name, city you live and your age. 
2. Log the values to the console. You can log each variable or all together.

### Data types:
1. Declare a variable called "isOfLegalAge" and set it's value according to your age (18 is the legal age).
2. Declare a variable called "language" but dont asign it any value.
3. Log "isOfLegalAge", '"myName", "myCity" and "myAge" to the console.

### let, const and var
1. Set the value of language to your native language.
2. Think about which bariables should be **const**? Which variables might change and which wont? Then change the appropriate variables to **const**.
3. Try to change on of the variables you changed to **const** and observe what happens.

### Basic operators
1. If you split the city you live in ("myCity") into half and let half live in each half how many would that be? (google amount of people living in your city or just make something up).
2. Increase the population of your city by 1. Log the result to the console.
3. Gothenburg has the population of 578 327, does your city have more people living there?
4. Based on the variables you created, create a ne one called 'description' whish conatins a string with this format:
"Gotheburg is a city in Sweden and most of the 578 327 living there speaks swedish"

### Strings & template literals
1. Recreate the 'description' variable from the last exercise but this time using template literal syntax.

### Taking decisions with if/else statement
1. If your city has more than 500 000 people living there log a string like this to the console: 
"xx's population is above Gothenburgs population." Otherwise log a string like this: 
"xx's population is below Gothenburgs population."
2. After the result change the population to for example 16 and see the different result. Set the variable back to it's original value after that.

### Type conversion and coercion
1. Predict the result of these 5 operations without executing them:
'9' - '5';
'19' - '13' + '17';
'19' - '13' + 17;
'123' < 57;
5 + 6 + '4' + 9 -4 -2;
2. Execute the operations to see if you where right.

### Equality operators
1. Declare a variable 'numOfNeighbours' based on a prompt input like this:
propmt('How many neighbours do you have?');
2. If there is only 1 neighbour log to the console 'only 1 neighbour!' use loose equality for now.
3. Use an else-if block to log 'More than 1 neighbour' in case 'numOfNeighbours' is greater than 1.
4. Use and else block to log 'No neighbours'. This block will be executed only if 'numOfNeighbours' is 0 or any other value.
5. Test the code with different values of 'numOfNeighbours' including 1 and 0.
6. Change == to strict === and test the code again with the same values of 'numOfNeighbours'. Notice what happens when there is exactly 1 neighbour. Why is this happening?
7. Now convert 'numOfNeighbours' to a number and watch what hppens now when you input 1
8. Reflect pn why we should use the === operator and type conversion in this situation

### Logical operators
1. If you are in the same file as the previous exercise comment that code out before moving on.
2. Let's say Anna is looking for a new car. She wants a red car that is not manually driven and costs under 450.000:-.
3. Write an if statement to help Anna figure out if any of these cars will match what Anna wants:
const colorA = 'red';
const isManualA = true;
const costA = 500000;

const colorB = 'blue';
const isManualB = false;
const costB = 420000;

const colorC = 'red';
const isManualC = false;
const costC = 400000;

Copy the code above and compare each of A, B and C values to see if one of them meet Annas critertias.
You will need to write a condition that accounts for all of the criterias so take your time.
4. If one of the above is true output to the console "This is your car go buy it!" and if not output "This i not the car for you..."

### The switch statement
1. Use a switch statement to log the follwing string for the given 'webDevelopment':
**javascript:** 'One of the core technologies of web development.'
**html:** 'Defines and describes the structure of a website.'
**css:** 'Describes how HTML elements are to be displayed on screen, paper, or in other media.'
**react:** 'A JavaScript library used in web development to build interactive elements on websites.'
**node:** 'Node allows developers to write JavaScript code that runs directly in a computer process itself instead of in a browser.'
For all other simply log 'That is not a part of web development.'

### The conditional (Ternary) operator
1. If your country's population is greater than 33 million, use the ternary operator
to log a string like this to the console: 'Portugal's population is above average'.
Otherwise, simply log 'Portugal's population is below average'. Notice how only
one word changes between these two sentences!

2. After checking the result, change the population temporarily to 13 and then to
130. See the different results, and set the population back to original

## CHALLENGE 1
### The temperature converter
1. Declare a variabled called "celsius" and assign it a value that represents a temperature.
2. Convert it to Farenheit (google the celsius to farenheit formula) and log it to the console like this:
"NN°C is NN°F"
3. Now declare a variable called "farenheit" and assign it a value that represents a temperature.
4. Convert it to celsius and log it to the console like this:
"NN°F is NN°C"

## CHALLENGE 2 
### Lifetime supply calculator
Have you ever wondered how much "a lifetime supply" of your favourite snack is? Wonder no more! :)
1. Declare a variable called myAge and assign it to your current age.
2. Declare a variable called maximumAge and assign it to a max age - let's say 95!
3. Declare a variable called amountPerDay and assign a value of an estimated amount per day.
4. Now calculate how many you would eat per day for the rest of your life.
5. Log the result to the console like this:
"You will need NN to last you until the ripe old age of X"

