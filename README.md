# 🐍 Python Data Structures & Fundamentals
---

## 📚 Topics Covered

This repository currently covers the following fundamental topics:
* **Data Structures:** Lists, Dictionaries, Strings, Tuples, and Sets
* **Control Flow:** Conditional Statements (`if`, `elif`, `else`)

---

## 📝 Python Lists
A list is an **ordered** and **mutable** collection of elements. Lists can be modified after creation.

### Core List Operations
* **Creation & Modification:** List creation, adding elements, inserting elements, extending lists
* **Removal:** Removing elements, popping elements
* **Ordering:** Sorting lists, reversing a list
* **Math & Access:** Finding maximum and minimum values, calculating the sum of elements, list indexing, list slicing

---

## 📖 Python Dictionaries
A dictionary stores data using **key-value pairs**. They are useful when information needs to be associated with a unique identifier.

### Core Dictionary Operations
* **Access & Mutation:** Dictionary creation, accessing values using keys, adding new key-value pairs, updating existing values
* **Dictionary Methods:** Using `keys()`, using `values()`, using `items()`

---

## 🧵 Python Strings
A string is an **ordered**, **immutable** sequence of characters enclosed within single or double quotes.

### Core String Operations
* String concatenation
* String indexing
* String slicing
* Reversing a string

### 🛠️ Built-in String Methods
* `upper()` — Converts text to uppercase
* `lower()` — Converts text to lowercase
* `capitalize()` — Capitalizes the first character
* `count()` — Counts occurrences of a character or substring
* `replace()` — Replaces part of a string with another value

---

## 📦 Python Tuples
A tuple is an **ordered** collection of elements. Tuples are **immutable**, meaning their values cannot be changed directly after creation.

### Core Tuple Operations
* Tuple creation
* Tuple concatenation
* Tuple repetition
* Tuple indexing
* Tuple slicing

---

## 🔢 Python Sets
A set is an **unordered** collection of **unique** elements. Sets automatically remove duplicate values.

### Core Set Operations
* Set creation
* Understanding uniqueness
* Mathematical operations: Union, Intersection

> ⚠️ **Set Indexing Warning:** Sets do not support indexing because they are unordered collections. Attempting to access a set using an index results in a `TypeError`.

---

## 🔀 Conditional Statements
Conditional statements are used to make decisions in Python based on specific conditions.

### Core Syntax
* `if`
* `elif`
* `else`

## 📊 Python Data Structures — Comparison

Understanding the differences between Python's built-in data structures makes it easier to choose the right one for a particular task.

| Feature | List | Tuple | Set | Dictionary | String |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Ordered** | Yes | Yes | No\* | Yes\*\* | Yes |
| **Mutable** | Yes | No | Yes | Yes | No |
| **Allows Duplicates** | Yes | Yes | No | Keys: No / Values: Yes | Yes |
| **Indexing** | Yes | Yes | No | By key | Yes |
| **Slicing** | Yes | Yes | No | No | Yes |
| **Data Type** | Any data type | Any data type | Any hashable type | Key-value pairs | Characters |
| **Syntax** | `[ ]` | `( )` | `{ }` | `{key: value}` | `' '` or `" "` |
| **Main Use** | Changeable items | Fixed items | Unique items | Key-value data | Text / Characters |

*\* Sets are unordered collections and do not support indexing or slicing.*  
*\*\* Dictionaries preserve insertion order in modern Python versions, but they are accessed by keys rather than numerical indexes.*

---

## 🧠 Quick Summary

* **📝 List:** Ordered | Mutable | Allows duplicates | Supports indexing/slicing. Suitable for collections that change.
* **📦 Tuple:** Ordered | Immutable | Allows duplicates | Supports indexing/slicing. Suitable for protected/fixed collections.
* **🔢 Set:** Unordered | Mutable | Unique values only | No indexing/slicing. Useful for uniqueness checks and set math.
* **📖 Dictionary:** Key-Value | Mutable | Unique keys | Key-indexed. Useful for paired/related data.
* **🧵 String:** Ordered Characters | Immutable | Allows duplicate characters | Supports indexing/slicing. Used for text.

---

## 🔑 Important Concepts to Remember

* **Mutable:** The object can be changed after creation.
* **Immutable:** The object cannot be changed after creation.
* **Ordered:** Elements maintain a defined order.
* **Indexing:** Elements can be accessed using numerical positions.
* **Slicing:** A portion of a sequence can be accessed using a range of indexes.
* **Unique:** Duplicate values are not stored.
* **Key-Value Pair:** Data is stored using a key associated with a value.
