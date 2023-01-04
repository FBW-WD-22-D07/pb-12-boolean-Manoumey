# Programming Basics: Logical Operators
[![Status overview badge](../../blob/badges/.github/badges/main/badge.svg)](#-results)

# True or False? 

### Instructions
- work in `solution.js`
#### 1. What type? 
* Check whether `3` is equal to `"3"` using loose comparison. Then, check whether they are equal while using strict comparison. 
**Questions: Print out the number of the correct answer in the Terminal (one by one)** 
* Which of the following is used to compare the VALUE of two variables/values?
1.  =         
2.  ==          
3.  ===
4.  all of the above 
* Which of the following is used to compare the VALUE and TYPE of two variables/values?
5.  =         
6.  ==          
7.  ===         
8.  none of the above 
* Which of the following is used to ASSIGN a value to a variable?
9.  =         
10.  ==          
11.  ===         
12.  const 

#### 2. Not
* Complete the following ternary code to print out 'good evening' using 'myVar':
```javascript
let myVar = true;

console.log( .............. ? 'good morning' : 'good evening' );
```

#### 3. Short Circuit
* Complete the following code by filling the spaces with '&&' or '||' to get the value that fits the variable's name:
(PS: these values will always return false: `false` , `0`, `''`)

```javascript

let firstName = '' .... 'John' .... 0
let emptyStr  = '' .... false .... 'Hello World'
let zero  = '' .... false .... 0
let seven = 75 .... 'nine' .... 7

console.log(firstName,zero,emptyStr,seven);
```

[//]: # (autograding info start)
# <img src="https://github.com/DCI-EdTech/autograding-setup/raw/main/assets/bot-large.svg" alt="" data-canonical-src="https://github.com/DCI-EdTech/autograding-setup/raw/main/assets/bot-large.svg" height="31" /> Results
> ⌛ Give it a minute. As long as you see the orange dot ![processing](https://raw.githubusercontent.com/DCI-EdTech/autograding-setup/main/assets/processing.svg) on top, CodeBuddy is still processing. Refresh this page to see it's current status.
>
> This is what CodeBuddy found when running your code. It is to show you what you have achieved and to give you hints on how to complete the exercise.


### 1. What type

|                 Status                  | Check                                                                                    |
| :-------------------------------------: | :--------------------------------------------------------------------------------------- |
| ![Status](../../blob/badges/.github/badges/main/status0.svg) | loose and strict comparison between 3 and "3" |
| ![Status](../../blob/badges/.github/badges/main/status1.svg) | Which is used to compare the VALUE |
| ![Status](../../blob/badges/.github/badges/main/status2.svg) | Which is used to compare the VALUE and TYPE |
| ![Status](../../blob/badges/.github/badges/main/status3.svg) | Which is used to ASSIGN a value |

### 2. Not

|                 Status                  | Check                                                                                    |
| :-------------------------------------: | :--------------------------------------------------------------------------------------- |
| ![Status](../../blob/badges/.github/badges/main/status4.svg) | Code was changed to print "good evening" |

### 3. Short Circuit

|                 Status                  | Check                                                                                    |
| :-------------------------------------: | :--------------------------------------------------------------------------------------- |
| ![Status](../../blob/badges/.github/badges/main/status5.svg) | `firstName` must be "John" |
| ![Status](../../blob/badges/.github/badges/main/status6.svg) | `emptyStr` must be "" |
| ![Status](../../blob/badges/.github/badges/main/status7.svg) | `zero` must be `0` |
| ![Status](../../blob/badges/.github/badges/main/status8.svg) | `seven` must be `7` |



[🔬 Results Details](../../actions)
[🐞 Tips on Debugging](https://github.com/DCI-EdTech/autograding-setup/wiki/How-to-work-with-CodeBuddy)
[📢 Report Problem](https://docs.google.com/forms/d/e/1FAIpQLSfS8wPh6bCMTLF2wmjiE5_UhPiOEnubEwwPLN_M8zTCjx5qbg/viewform?usp=pp_url&entry.652569746=PB-language-boolean)


[//]: # (autograding info end)