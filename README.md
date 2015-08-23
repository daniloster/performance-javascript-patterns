# performance-javascript-patterns
It is a quick performance test about patterns, declaration and execution

These are just a few tests, but I will add more tests at the next weekend.

## Running on Chrome
- Version: 44.0.2403.157 (64-bit)

// local declaration outside loop; 
variable[i] = 'variable ' + i + ' <br />'; 
#### 1314ms

// local declaration inside loop; 
var variable = 'variable ' + i + ' <br />';  
#### 491ms

// local declaration of the function as anonymuous; 
function() { return 'variable ' + i + ' <br />'; }  
#### 468ms

// local declaration of the function as named; 
function showTestMessage() { return 'variable ' + i + ' <br />'; }
#### 371ms

// local execution of all the function as named; 
#### 201ms

// local execution of all the function as anonymuous; 
#### 448ms

## Running on Firefox
- Version: 35.0.1

// local declaration outside loop; 
variable[i] = 'variable ' + i + ' <br />'; 
#### 481ms

// local declaration inside loop; 
var variable = 'variable ' + i + ' <br />';  
#### 177ms

// local declaration of the function as anonymuous; 
function() { return 'variable ' + i + ' <br />'; }  
#### 186ms

// local declaration of the function as named; 
function showTestMessage() { return 'variable ' + i + ' <br />'; }
#### 124ms

// local execution of all the function as named; 
#### 138ms

// local execution of all the function as anonymuous; 
#### 184ms


## Running on Safari
- Version: 8.0.7 (10600.7.12)

// local declaration outside loop; 
variable[i] = 'variable ' + i + ' <br />'; 
#### 627ms

// local declaration inside loop; 
var variable = 'variable ' + i + ' <br />';  
#### 246ms

// local declaration of the function as anonymuous; 
function() { return 'variable ' + i + ' <br />'; }  
#### 292ms

// local declaration of the function as named; 
function showTestMessage() { return 'variable ' + i + ' <br />'; }
#### 186ms

// local execution of all the function as named; 
#### 398ms

// local execution of all the function as anonymuous; 
#### 278ms



### I realy hope you guys enjoyed and share! Let's collaborate! If everybody knows how to improve performance on the web, we will have a better UX while using some websites/webapp.

## Cheers
