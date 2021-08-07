# Problem Domain, Objects, and the DOM

## Problem Domain
A **problem domain** refers to the area of expertise or application that must be examined in order to address an issue. A problem domain is essentially a set of subjects that a person is interested in and excludes anything else.

![Problem Domain](https://www.tivix.com/wp-content/uploads/2019/07/ng_communication.jpg)

## Objects
**Objects** are a series of *functions* and *variables* that represents things around you.

* **Variables** are known as objects properties:
  * *Variables* in ***JavaScript*** can save numbers values like 54 and text values like "Mohammad", text values are called strings.
Also it can save more data types, but lets just give an example about numbers and strings:
    * Number
      * `var age = 18`
      * `var sum = 2 + 5`
    * String
      * `var name = "Mohammad"`
      * `var text = '5'`
* **Functions** are objects methods:
  * *Function* is a block of code that performes a specific task, and it is not excuted until you call it.

```
function square(number) {
  return number * number;
}
```

## DOM (Document Object Model)
**DOM trees** are used to represent pages on the browser, and they has four types of nodes:
* Document nodes
* Element nodes
* Attribute nodes
* Text nodes