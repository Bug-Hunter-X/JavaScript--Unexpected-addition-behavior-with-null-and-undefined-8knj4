# JavaScript: Unexpected Addition Behavior with null and undefined

This repository demonstrates an unexpected behavior in JavaScript when performing addition with `null` and `undefined` values.

## Problem

The behavior differs when using `null` and `undefined` in arithmetic operations:

* `undefined` results in `NaN` (Not a Number) when added to a number.
* `null` is treated as `0` when added to a number.

This inconsistent behavior can lead to unexpected results and potential bugs if not carefully handled.

## Solution

The solution involves explicitly handling `null` and `undefined` values before performing the addition. This can be done using a conditional check or a helper function to ensure consistent behavior.