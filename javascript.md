# Primitive Data types and data structures

## Primitive Data types

Next six types are considered to be primitives. A primitive is not an object and has not methods of its own. All primitives are immutables.

1. Boolean: true or false
2. Null: No value
3. Undefined: a declared value but has not been given a value
4. Number: integers, floats ... etc
5. String: an array of characters i.e words
6. Symbol: a unique value that's not equal to any other value

```javascript
    typeof true // true
    typeof null // object
    typeof undefined // undefined
    typeof 1.5 // number
    typeof 'a' // string
    typeof Symbol('a') // symbol
    Symbol('a') === Symbol('a') // false
```

Everything else is an Object type.

## Data structures

There are two main data structure:

* Object
* Array 

There are many other objects too, just to list a few:

* Function
* Boolean
* Symbol
* Error
* Number
* String
* RegExp
* Math
* Set

```javascript

    // array
    const arr = [1, 2, 4, 5]
    const arr = new Array(4) // for empty items
    typeof arr // object

    // literal objects
    const dog = {
        name: 'keita',
        age: 2
    }

    typeof dog //  object
    typeof Math // object

```

# Function

