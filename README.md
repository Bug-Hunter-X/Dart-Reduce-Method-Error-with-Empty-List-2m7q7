# Dart Reduce Method and Empty Lists

This repository demonstrates a common error encountered when using the `reduce` method in Dart with an empty list. The `reduce` method requires at least one element to perform its operation; otherwise, it throws an exception.

## The Bug
The `bug.dart` file contains code that attempts to use `reduce` on an empty list, resulting in an error.  The error is a `StateError` indicating that the list is empty and reduction cannot be performed.

## The Solution
The `bugSolution.dart` file provides a solution to this problem by first checking if the list is empty before attempting to use `reduce`.  A conditional check prevents the error by handling the empty case explicitly, returning a default value (0 in this example) when the list is empty.