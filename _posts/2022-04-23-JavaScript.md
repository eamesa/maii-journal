---
layout: post
title: JavaScript
---

Change html dinamicaly using JS

Js is funtion oriented, so it uses callbacks. The callbacks work like ruby uses blocks.
<script>
          
</script>

## Variables and strings
-JavaScript uses camelCase
-// 1) names only contain letters, numbers, symbol $ _
- // 2) first character must not be a number
- Boolean variables: isVariable
- SHOUTING_SNAKE_CASE when a constant holds a value not to be changed

var / cons / let: declare the intention of the variable you are creating and minimize errors by using the correct type of declaration

String interpolation: similar to Ruby's #{string} but it uses ${string}. 

## Types and conditionals

```
if (boolean) {
 //block of code that runs if boolean = true
} elseif (boolean2 === 'condition') {
 //block that ruins if boolean2 = true
 }
} else {
 //block that ruins if boolean = false
 }
 
 switch (condition){
   case "condition1":
    //block of code that runs if condition = condition1
    break;
   case "condition2":
    //block of code that runs if condition = condition2
    ;break
   default "condition1":
    //block of code that runs if no conditions are met
    }
```

Any value provided to a conditional is converted to true or false. Falsey values are false, 0, null, '', undefined, NaN.

## Functions

```
let greeting = "Hola"

function greet(name, ) {
   console.log("${greeting} ${name}!"); 
}

greet(Harry)
"Hola Harry!"
```
# AJAX & Javascript for Rails delevopers 


