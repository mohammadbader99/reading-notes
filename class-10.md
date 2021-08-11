# JS Debugging

You need to understand the *execution context*s and *staks* to find if there is an error in your code.

There are three execution contexts:
* **GLOBAL CONTEXT:** the code that is in the script and not in any function, and there is only one global context in a single page.

* **FUNCTION CONTEXT:** the code that is typed in a function.

* **EVAL CONTEXT** 

**Debugging** is the procedure of finding and fixing current and potential errors (usually called "bugs") in software code that might cause it to behave abnormally or crash.

The console will help you to detect the area that the error is located in, so you will find the error easily.

![Debugging](https://cdn.lynda.com/course/112414/112414-636410882080313019-16x9.jpg)

If you know that your code may has an error you can handle it using `try, catch, finally` statments, for example:

```
try {
  nonExistentFunction();
} catch (error) {
  console.error(error);
}

```

```
try {
  tryCode - Block of code to try
}
catch(err) {
  catchCode - Block of code to handle errors
}
finally {
  finallyCode - Block of code to be executed regardless of the try / catch result
}
```