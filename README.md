# Basic JSON - JavaScript Object Notation

## Whats is JSON

JSON was originaly created to hold structured data to used in JS.

## JSON uses

- It s used for data for all  kinds of applications.
- It is the most popular way of sending data for web APIs

## Basic Data Types

- String: text enclosed in double quantation
- Numebers: integeror or decimal, positive or negative.
- Booleans:  true or false, no quotation marks.
- NUll: means "nothing", no quotation marks.

## Arrays

- Arays are list.
- In square brackets.
- Comma separated.
- Can mix data types.

### Examples

- [4,6,23.1,-4,0,56]
- ["red", "green", "blue"]
- [65, "toast", true, 21, null, 100]

## Objects

- Objects are JSON´s dictionaries.
- They are enclosed in curly brackets.
- Keys and values are separated by a colon.
- Pairs are separated by commas.
- Keys and values can be any data type.

### Object Examples

- {"red": 205, "green": 123, "blue": 53}
- {
	"firstName": "Peter",
	"lastName": "Gruenbaum",
	"employed": true
}

## Nesting

- Nesting involves putting arrays and object inside each other.
- You can put arrays inside objects, objects inside arrays, arrays inside arrays, etc.

## White Space and Formatting

- "White space" means spaces, new lines, etc.
- White space doesn´t matter, unless it´s inside quotation marks.
- Good JSON formatting
- In general, add an indent for every new level of brackets.

## Caveat

- There is no one way to document JSON files.
- You should get approval from your team before writing all of the documentation.

## Two ways to handle nesting

- Best for cases where objects are not reused.
- Takes up more space.
- Takes up less space.

## Table for each object type
- Best for cases where objects are reused.

## Documenting JSON requests

- What is the one column that you need for a request that you don't need for a response? Required
- The cells in the Required column should be either "Required" or "Optional" .
- A default value means When an element is optional and not provided, then the default value is used.
