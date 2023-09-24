# This plugin for FlowLauncher is a simple calculator using the default Python expressions evaluator

## Fractions:
Use doubles slashes for fractions. Ex: 1//2+3//7 = 13/14

## Integer factorization:
Use factor(n) to get the prime factorization of n. Ex: factor(123456789) = 3 · 3 · 3 607 · 3 803

## Base conversions:
Use simple notations to convert to decimal: 0b for binary, 0o for octal, 0x for hexadecimal.
Ex: 0b1010 = 10, 0xDDA55 = 907861
To specify bases manually, use suffixes (one letter for starting base and one letter for ending base).
Ex: 1485do = 2715 (decimal to octal)
Ex: 1010bh = A (binary to hexadecimal)

## Authorized math functions:
pi, cos, sin, tan, abs, log, log10, log2, exp, sqrt, acos, asin, atan, atan2, ceil,
floor, degrees, radians, trunc, round, factorial, gcd, pow, !, sha1, sha256

## Unique Identifiers:
You can enter one of the following keywords to generate a unique ID:
- uuid
- ulid
- cuid (identifier using a timestamp to be sortable, in base 36)
- sulid (short version of ulid converted to base 62)

Press enter to copy the generated ID to the clipboard

## Hashes:
You can enter one of the following keywords to generate a hash:
- md5 <text>
- sha1 <text>
- sha256 <text>
- sha3_256 <text>
- sha3_512 <text>
- blake <text>
