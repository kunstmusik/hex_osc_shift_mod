# Shift

This section involves techniques related to bitwise operations, namely:

* left-shift
* right-shift (arithmetic, logical)
* bitwise-AND 
* bitwise-OR
* bitwise-XOR (exclusive or)

While there are other operations working with bits (bitwise-NOT, rotations, etc.), I have not yet mapped out usage of these operations. This document will be updated once they have been explored further.

## Source Signals

* Powers of 2 rule bit sequences

* Rate of change, dealing with powers of 2 for change
* Modulus constrains
  * modulus by power of two will give very static output sequences
  * churn by using non-power of two

## Bitwise-and, Bitwise-or

bitwise-and 

p4 & 0x7 
constrain

p4 & 0x7 == 0x7
mask equals (contains exact set of bits)  ; every

p4 & 0x7 > 0
mask -> greater (contains some part of set of bits)   ; some 

