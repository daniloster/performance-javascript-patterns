# performance-javascript-patterns
It is a quick performance test about patterns, declaration and execution

These are just a few tests, but I will add more tests at the next weekend.

## Running on Chrome
- Version: 44.0.2403.157 (64-bit)

// local declaration outside loop;  <br/>
variable[i] = 'variable ' + i + ' &lt;br /&gt;'; 
#### 1314ms

// local declaration inside loop; <br/>
var variable = 'variable ' + i + ' &lt;br /&gt;';  
#### 491ms

// local declaration of the function as anonymuous; <br/>
function() { return 'variable ' + i + ' &lt;br /&gt;'; }  
#### 468ms

// local declaration of the function as named; <br/>
function showTestMessage() { return 'variable ' + i + ' &lt;br /&gt;'; }
#### 371ms

// local execution of all the function as anonymuous; 
#### 201ms

// local execution of all the function as named; 
#### 448ms

## Running on Firefox
- Version: 35.0.1

// local declaration outside loop; <br/>
variable[i] = 'variable ' + i + ' &lt;br /&gt;'; 
#### 481ms

// local declaration inside loop; <br/>
var variable = 'variable ' + i + ' &lt;br /&gt;';  
#### 177ms

// local declaration of the function as anonymuous; <br/>
function() { return 'variable ' + i + ' &lt;br /&gt;'; }  
#### 186ms

// local declaration of the function as named; <br/>
function showTestMessage() { return 'variable ' + i + ' &lt;br /&gt;'; }
#### 124ms

// local execution of all the function as anonymuous; 
#### 138ms

// local execution of all the function as named; 
#### 184ms


## Running on Safari
- Version: 8.0.7 (10600.7.12)

// local declaration outside loop; <br/>
variable[i] = 'variable ' + i + ' &lt;br /&gt;'; 
#### 627ms

// local declaration inside loop; <br/>
var variable = 'variable ' + i + ' &lt;br /&gt;';  
#### 246ms

// local declaration of the function as anonymuous; <br/>
function() { return 'variable ' + i + ' &lt;br /&gt;'; }  
#### 292ms

// local declaration of the function as named; <br/>
function showTestMessage() { return 'variable ' + i + ' &lt;br /&gt;'; }
#### 186ms

// local execution of all the function as anonymuous; 
#### 398ms

// local execution of all the function as named; 
#### 278ms



### I really hope you guys enjoyed and, please, share it! Let's collaborate! If everybody knows how to improve performance on the web, we will have a better UX while using some websites/webapp.

### Cheers
