# polynomial
This is a professional polynomial calculator and analyzer python module.

## Example of how to use:

```
>>> p = polynomial([3, 2, -1], [0, 1, 2])
>>> p
3 + 2x + -x^2
>>> q = polynomial([3, 1], [0, 3])
>>> q
3 + x^3
>>> p + q
6 + 2x + -x^2 + x^3
>>> p * q
-x^5 + -3x^2 + 2x^4 + 6x + 3x^3 + 9

```
