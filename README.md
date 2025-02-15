# Objective-C: Handling nil and Missing Property Access

This repository demonstrates a common Objective-C error: attempting to access a non-existent property or send a message to a `nil` object.  This often leads to crashes.  The example showcases the problem and provides a robust solution using nil checks and optional chaining.

## Bug Description

The `bug.m` file contains code that attempts to access a property of an object that might not exist, or send a message to a `nil` object. This leads to an exception and application crash. 

## Solution

The `bugSolution.m` file offers a solution by incorporating thorough nil checks using `if` statements and optional chaining where applicable to prevent crashes.  This approach provides a more robust and error-tolerant way to handle potential issues in Objective-C. 
