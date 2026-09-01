## 🐍 Python Strings & Tuples — Quick Reference Notes

## 🧵 Python Strings
A string is a sequence of characters enclosed within single or double quotes.

## ⚙️ Core String Operations

* String Concatenation
* Purpose: Used to join two or more strings together.
   * Syntax: string1 + string2
* String Indexing
* Purpose: Used to access individual characters. Indexing starts from 0.
   * Syntax: string[index]
* String Slicing
* Purpose: Used to extract a part of a string.
   * Syntax: string[start:end]
* Reverse a String
* Purpose: Used to display a string in reverse order.
   * Syntax: string[::-1]

## 🛠️ Built-in String Methods

* Uppercase
* Purpose: Converts all characters to uppercase.
   * Syntax: string.upper()
* Lowercase
* Purpose: Converts all characters to lowercase.
   * Syntax: string.lower()
* Capitalize
* Purpose: Converts the first character of a string to uppercase.
   * Syntax: string.capitalize()
* Count
* Purpose: Counts the number of occurrences of a character or substring.
   * Syntax: string.count(value)
* Replace
* Purpose: Replaces a specified value with another value.
   * Syntax: string.replace(old, new)

------------------------------
## 📦 Python Tuples
A tuple is an ordered collection of elements. Tuples are immutable, meaning their values cannot be changed after creation.

## ⚙️ Core Tuple Operations

* Tuple Creation
* Purpose: Used to create a tuple containing multiple values.
   * Syntax: tuple_name = (value1, value2, value3)
* Tuple Concatenation
* Purpose: Used to combine two or more tuples.
   * Syntax: tuple1 + tuple2
* Tuple Repetition
* Purpose: Repeats the elements of a tuple a specified number of times.
   * Syntax: tuple_name * number
* Tuple Indexing
* Purpose: Used to access an individual element from a tuple.
   * Syntax: tuple_name[index]
* Tuple Slicing
* Purpose: Used to access a specific range of elements.
   * Syntax: tuple_name[start:end]

------------------------------
## 🧠 Key Summary Points

## 🎯 Shared Features

* Indexing & Slicing: Both strings and tuples support zero-based indexing and range-based slicing.
* Immutability: Both data types are immutable and cannot be altered directly after creation.

## ⚖️ Differences Overview

| Feature | Strings | Tuples |
|---|---|---|
| Element Type | Sequence of text characters only | Ordered collection of any data types |
| Syntax | Enclosed in single (' ') or double (" ") quotes | Enclosed in parentheses (( )) |
| Repetition Operator | Not highlighted in base operations | Directly supports the * multiplier operator |

