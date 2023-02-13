# bintodec

Converts Binary to Decimal

```
import { getDecimal } from "bintodec";

let numA = getDecimal("1010.11");
console.log(numA.success && numA.message);    //10.5

let numB = getDecimal("Number");
console.log(numB.success && numB.message);    //false

```
