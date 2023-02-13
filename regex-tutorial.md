# Regex Tutorial

Matching an Email &ndash; `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`
Regular expressions are a powerful tool that can greatly simplify string validation tasks, such as email address validation. This example will show you how to create a regular expression pattern to match an email address and will then break down the different components that make up the pattern. With a deeper understanding of regular expressions, you can handle complex string manipulation tasks with ease.

## Table of Contents

  - [Table of Contents](#table-of-contents)
  
  - [Summary](#summary)

  - [Regex Components](#regex-components)
    - [Anchors](#anchors)
    - [Quantifiers](#quantifiers)
    - [OR Operator](#or-operator)
    - [Character Classes](#character-classes)
  
  

- [Author](#author)





## Regex Components

### Anchors
The anchor is what starts and ends the regular expression. In the matching email code,

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/,

the anchors are the ^ and the $. This code specifically is saying that we are looking for something that starts with

^([a-z0-9_\.-]+)

we will define what everything inside the parentheses later in this tutorial, but what the anchor means is that if we are to find a match it has follow those initial guidelines. It also has to end with

.([a-z\.]{2,6})$.

So, it must start and end with the given parameters within the code. If it does not, then it is not a match.

### Quantifiers

Quantifiers in regex include ?,*, +, and then items within curly braces/brackets.
With quantifiers, you are basically trying to find how many times something happens or how many of certain things there are. In my research, I found that Quantifiers can also be eager reluctant possessive depending on how characters are placed together.
As you hover over those different parts of the expression, it will tell you the purpose of those sets of letters or characters to help make up a particular expression. Then at the bottom of the page, they also have a nice little cheat sheet.
For quantifiers, if you look at W3 schools, almost or all of the descriptions for what quantifiers start with “matches any string with” or “matches any string that.” And then in each of the examples they provide, it says more specifics, for example, matches any string with and end at the end of it or that is for the n $ example.
Or it could say matches any string that is followed by a specific string, and that would be if you had a? Equals n. Basically, quantifiers tell you what to look for to match
OR Operator

### OR Operator

Alternation is actually a simple OR, which is exhibited or declared with a vertical line, so for example, if you wanted to find three different things, a cat, a dog, and a bird, you would put cat|dog|bird.
this would make it so that you were requesting to look for all three of those different items are groups at the same time yeah also individually
<https://javascript.info/regexp-alternation>

### Character Classes

Character Classes
\d is present in the given matching email code and what it will match a single letter character, a-z, after the @ sign in the email address. Basically ensuring that a letter is matched after the @ in the email and not a number or special character.


## Author

abdallahnass

Github: <https://github.com/abdallahnasseruoftdevop>

