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

Anchors include symbols like a caret and a dollar sign at the end of the string or \A letter to describe word boundaries or lack thereof. The \letter means being a or end of a string.
About anchors, an example of an anchor would be a carrot a $. Anchors or a way of telling you where you are at, so basically, is it that start or the end? \A refers to the start of a string.
It is probably important to note as we start to talk about anything to do with regex that regex can vary a little bit depending on which language you are looking at. Some characters are the same across multiple languages and have the same meaning, but that is not true for all of them, so it is to find good references. In the documentation I looked at, some symbols or characters or tokens had notes with them saying all engines except JavaScript, or this except for Ruby or all of these are the same depending on the language, so it is important to watch out for that.
Quantifiers
Examples of regular expressions quantifiers are *, +, ?, {3}, {4,7}, {5,}.

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
An example of character class would be a-z or A-Z -
when you see this in a regular expression, it is not just talking about finding a time frame see it is saying find anything, or you can look through anything that falls in the alphabet, so anything between A-to-Z could be any one of those characters you could use this A-to-Z, or you could also think about numbers, that is a possibility with numbers as well



## Author

abdallahnass

Github: <https://github.com/abdallahnasseruoftdevop>

