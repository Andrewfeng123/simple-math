# Definition of Whole Numbers
The set of whole numbers is defined as follows:
* $0$ is a whole number
* $1$ is a whole number
* $2$ is a whole number

and so on ...

(does this make sense? maybe? idk)

Key points:
* The definition of whole numbers is independent of the numeral system (decimal, binary, unary) we are using. But we usually write out numbers in some fixed numeral system *by convention* and *for convenience*.
* For example, the following is the same definition of whole numbers, just written in binary (aka base 2):
    > The set of whole numbers is defined as follows:
    > * $0$ is a whole number
    > * $1$ is a whole number
    > * $10$ is a whole number
    > 
    > and so on ...

# Reading Numbers
From now on, we use the decimal numeral system. In decimal, the digits of a number give a decomposition of it into smaller numbers:
* $1034 = 1\times 10^3 + 0\times 10^2 + 3\times 10^1 + 4\times 10^0$.

We have a list of numbers with names:

| Number | Name |
| ------ | ---- |
| $1$ | one |
| $10$ | ten |
| $100$ | hundred |
| $1\;000$ | thousand |
| $1\;000\;000$ | million |
| $1\;000\;000\;000$ | billion |

These numbers and the decomposition give a systematic way of reading numbers:
* $987$ is "nine hundred eighty seven"
* $907$ is "nine hundred *and* seven"
* $1987$ is "one thousand nine hunderd eighty seven"
* $1087$ is "one thousand *and* eighty seven"
* $1007$ is "one thousand *and* seven"

# Comparing Numbers
Two whole numbers can be compared using the following algorithm:
* remove any extra zeros in the representation (e.g $0154$ should just be written as $154$)
* if one number is longer than the other number, then that number is larger (e.g $154 > 89$)
* otherwise: find the first digit (from left to right) at which they differ, the number with the larger digit is larger (e.g $1\;945\;957 > 1\;945\;946$ because $5 > 4$)

# Rounding
Rounding a number ...