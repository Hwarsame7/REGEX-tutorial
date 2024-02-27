**Regular Expressions (Regex) Tutorial**

Welcome to the Regex Tutorial! This guide will introduce you to the basics of regular expressions, a powerful tool for pattern matching and text manipulation.

**What is a Regular Expression?**

A regular expression, often abbreviated as regex, is a sequence of characters that define a search pattern. It's commonly used for tasks such as searching, matching, and replacing text based on patterns.

**Basic Syntax**

Literal Characters
Most characters in a regular expression simply match themselves. For example, the regex hello matches the string "hello" in the text.

**Metacharacters**

Certain characters have special meanings in regex. For example:

. (dot): Matches any single character except newline.
^: Matches the start of a string.
$: Matches the end of a string.
\: Escape character, used to escape special characters.
[]: Character class, matches any character inside the brackets.
|: Alternation, matches either the expression before or after the pipe.

**Basic Examples**

Matching a Word: The regex /hello/ matches the word "hello" in a text.
Matching a Digit: The regex /[0-9]/ matches any digit from 0 to 9.
Matching an Email: The regex /^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}$/ matches a valid email address.
Regex Quantifiers

*: Matches zero or more occurrences of the preceding character or group.
+: Matches one or more occurrences of the preceding character or group.
?: Matches zero or one occurrence of the preceding character or group.
{n}: Matches exactly n occurrences of the preceding character or group.
{n,}: Matches n or more occurrences of the preceding character or group.
{n,m}: Matches between n and m occurrences of the preceding character or group.
Using Regex

Testing Regex Online: Websites like regex101.com allow you to test and experiment with regex patterns.
Regex in Programming: Most programming languages have built-in support for regular expressions. You can use regex functions in libraries like Python's re module or JavaScript's RegExp object.
Regex in Text Editors: Many text editors and IDEs support regex search and replace, allowing you to find and manipulate text based on regex patterns.
Example

Suppose you want to extract all email addresses from a text file. You can use the following regex pattern:

**[A-ZA-Z0-9._%+-]+@[A-ZA-Z0-9.-]+\.[A-ZA-Z]{2,}
THIS PATTERN MATCHES MOST STANDARD EMAIL ADDRESSES. HERE'S AN EXPLANATION OF THE PATTERN:**

[A-Za-z0-9._%+-]+: Matches one or more alphanumeric characters, dots, underscores, percent signs, plus signs, or hyphens before the "@" symbol.
@: Matches the "@" symbol.
[A-Za-z0-9.-]+: Matches one or more alphanumeric characters, dots, or hyphens after the "@" symbol.
\.: Matches a dot (escaped with a backslash).
[A-Za-z]{2,}: Matches two or more alphabetic characters for the top-level domain (e.g., com, net).
You can use this pattern with a regex tool or in your programming language of choice to extract email addresses from the text.

**Conclusion**

Regular expressions are a powerful tool for pattern matching and text manipulation. While they may seem complex at first, learning regex can greatly enhance your ability to work with text data in various contexts. Practice and experimentation are key to mastering regex.

