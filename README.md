# Uncommon Scala Bug: Improper Exception Handling in Setter Method

This repository demonstrates a subtle bug related to exception handling in Scala setter methods.  The `MyClass` example shows a setter for the `age` property.  While the code correctly throws an `IllegalArgumentException` when a negative age is attempted, it lacks proper error handling which may lead to unexpected program crashes for user's inputs.

## How to Reproduce
1. Clone this repository.
2. Compile and run the `Main` object in the `MyClass.scala` file.
3. Observe the exception thrown when attempting to set a negative age for the `myObj` instance.

## Solution
The solution demonstrates improved exception handling, allowing for more robust error management.