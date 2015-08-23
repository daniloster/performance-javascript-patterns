# performance-javascript-patterns
It is a quick performance test about patterns, declaration and execution

These are just a few tests, but I will add more tests at the next weekend.

## Running on Chrome
- Version: 44.0.2403.157 (64-bit)

// local declaration outside loop; 
variable[i] = 'variable ' + i + ' <br />'; 
[strong]1314ms[/strong]

// local declaration inside loop; 
var variable = 'variable ' + i + ' <br />';  
[strong]491ms[/strong]

// local declaration of the function as anonymuous; 
function() { return 'variable ' + i + ' <br />'; }  
[strong]468ms[/strong]

// local declaration of the function as named; 
function showTestMessage() { return 'variable ' + i + ' <br />'; }
[strong]371ms[/strong]

// local execution of all the function as named; 
[strong]201ms[/strong]

// local execution of all the function as anonymuous; 
[strong]448ms[/strong]

## Running on Firefox
- Version: 35.0.1

// local declaration outside loop; 
variable[i] = 'variable ' + i + ' <br />'; 
[strong]481ms[/strong]

// local declaration inside loop; 
var variable = 'variable ' + i + ' <br />';  
[strong]177ms[/strong]

// local declaration of the function as anonymuous; 
function() { return 'variable ' + i + ' <br />'; }  
[strong]186ms[/strong]

// local declaration of the function as named; 
function showTestMessage() { return 'variable ' + i + ' <br />'; }
[strong]124ms[/strong]

// local execution of all the function as named; 
[strong]138ms[/strong]

// local execution of all the function as anonymuous; 
[strong]184ms[/strong]


## Running on Safari
- Version: 8.0.7 (10600.7.12)

// local declaration outside loop; 
variable[i] = 'variable ' + i + ' <br />'; 
[strong]627ms[/strong]

// local declaration inside loop; 
var variable = 'variable ' + i + ' <br />';  
[strong]246ms[/strong]

// local declaration of the function as anonymuous; 
function() { return 'variable ' + i + ' <br />'; }  
[strong]292ms[/strong]

// local declaration of the function as named; 
function showTestMessage() { return 'variable ' + i + ' <br />'; }
[strong]186ms[/strong]

// local execution of all the function as named; 
[strong]398ms[/strong]

// local execution of all the function as anonymuous; 
[strong]278ms[/strong]



## I realy hope you guys enjoyed and share! Let's collaborate! If everybody knows how to improve performance on the web, we will have a better UX while using some websites/webapp.

# Cheers
