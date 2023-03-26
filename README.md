# Quadratic Formula Calculator

The JavaScript function for solving a quadratic equation.

## Install

`$ npm install quadratic-roots-function`

## Usage

```javascript
import {solveEquation} from 'quadratic-roots-function';

solveEquation(1, -3, -4);
// [4.0, -1.0]

solveEquation(1, 2, 1);
// [-1.0]

solveEquation(2, 4, 6);
// []
```

## API

```javascript
import {solveEquation} from 'quadratic-roots-function';

solveEquation(a, b, c);
```

### Parameters 

| Parameter | Type | Required | Description |
| --- | --- | --- | --- |
| a | Number | Yes |  The quadratic coefficient |
| b | Number | Yes |  The linear coefficient |
| c | Number | Yes |  The constant |

### Returns 
- when both roots are real, returns an array with two roots;
- when only one root is real, returns an array with one root; 
- when both roots are imaginary, returns an empty array.
