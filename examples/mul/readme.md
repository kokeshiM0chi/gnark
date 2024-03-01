# Overview

circom example

## Detail

This package provide the same example as that of circom

https://docs.circom.io/getting-started/writing-circuits/

```circom
pragma circom 2.0.0;

/*This circuit template checks that c is the multiplication of a and b.*/  

template Multiplier2 () {  

   // Declaration of signals.  
   signal input a;  
   signal input b;  
   signal output c;  

   // Constraints.  
   c <== a * b;  
}
```
