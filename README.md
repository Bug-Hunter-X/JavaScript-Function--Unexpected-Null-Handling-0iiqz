# JavaScript Function: Unexpected Null Handling

This repository demonstrates a common error in JavaScript functions involving null handling. The function `foo` is designed to add two numbers but unexpectedly returns `null` when one or both arguments are `null`. This is problematic, as it might lead to unexpected behavior in applications using this function. The solution file provides improved handling of `null` values.

## Bug

The original `foo` function immediately returns `null` if either argument is `null`, without attempting alternative handling such as defaulting to zero or throwing an error. This behavior might be unexpected or undesirable.

## Solution

The solution involves checking for `null` values and providing a more sensible alternative.  Instead of returning `null`, the improved function defaults to zero for null arguments.