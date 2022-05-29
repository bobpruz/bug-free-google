# RegEx Explination

Developers write code, but they also write about code.

## Summary

A regex, which is short for regular expression, is a sequence of characters that defines a specific search pattern. When included in code or search algorithms, regular expressions can be used to find certain patterns of characters within a string, or to find and replace a character or sequence of characters within a string. They are also frequently used to validate input. The following will explain some of the components.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

### Anchors

The anchors function is top match the location in the string. Some examples are the start of the string, the end of the string or at a line break.

### Quantifiers

Quantifiers do just what the word emplies. It will cause a match based on things like character counts of characters, groupings of words as in the following, does the letter "t" appear more than x times in a word. 

### OR Operator

OR is a simple operator that will allow for dynamically matching multiple characters or words from a grouping/list.  

### Character Classes

This is a list of characters that tell the regex engine to match one of the charaters in words. One example is fr[ae]y which will match both "fray" and "frey".

### Flags

Flags, to which there are 6 that can be thought of as options. Two instances are -i for "ignore case" and m for "multiline".

### Grouping and Capturing

When capturing matches in redex the whole match is returned as group0. By using parentheses in you search you can create sub groups to return subsets of the whole match. The subsets are matched and returned from left to right of the whole match. So the total match is 0, the next left to right match is 1 and so on.

### Bracket Expressions

This function matches any characters or range of characters in square brackets. 

### Greedy and Lazy Match

This really means strict and loose matching. with strict matching for quotes and replacing with '...' using the "." in the sentance The "quick" brown "dog" you would expect 'quick' and 'dog' but you would really get 'quick brown dog'. Yoiu would want to use loose matching to get 'quick' and 'dog'.

### Boundaries

Word boundaries are useful when you want to match a sequence of lettersor numbers on their own, or to ensure that they occur at the beginning or the end of a sequence of characters.

### Back-references

Back references are used to match the same text previously matched by a capturing group. This both helps in reusing previous parts of your pattern and in ensuring two pieces of a string match.

### Look-ahead and Look-behind

Look ahead and look behind are exactly what they state. Look behind would look at what you have placed into brackets"()" and retun what follows in the patten specified. also look aread would do the same thing but in reverse. 

## Author

Robert Prusinowski is a student in the BootCampSpot program learning full stack development. 

<a href="mailto:bobpruz@gmail.com">Email: Robert Prusinowski</a>

<a href="https://github.com/bobpruz">Robert's Github</a>