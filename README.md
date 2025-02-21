# JavaScript Loose Equality Bug: Unexpected NaN with Null and Undefined

This repository demonstrates a common JavaScript pitfall: unexpected behavior when using loose equality (==) to compare null and undefined.

## The Bug
The `foo` function intends to handle null input gracefully by returning 0. However, it fails to explicitly handle undefined, leading to NaN when undefined is passed in.

## The Solution
The solution uses strict equality (===) to differentiate between null and undefined, providing more predictable behavior. 