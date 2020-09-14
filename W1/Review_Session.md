# Review Session for Section 1 - 6

## Correction and Clarification
- In Component 29 of Section 4, actually all the errors mentioned here are commonly referred to as Syntax errors. While semantic errors are usually used interchangebly with Logic errors (Section 4 Component 33)
- In Component 48 of Section 6, you don't need to use 
```cpp
#include <climits>
```
in order to use 

```cpp
sizeof()

```
function. ``` sizeof()``` function is a build-in function of C++. However, you need to include ```<climits>``` or ```<cfloat>``` if you want to have access to constants like INT_MIN, LONG_MAX	and so forth. 

Just want to clarify this since this section seemingly implies that you must include those external libraries in order to use ```sizeof()```, which is in fact not the case.

## Review Questions

Q1. 
