# Mission 5 - Numbers and Data

## Task 5.1 - Manual Number Conversions

| Conversion | Answer |
|---|---|
| Decimal 13 to binary | 1101 |
| Decimal 25 to binary | 11001 |
| Binary 1010 to decimal | 10 |
| Binary 1101 to decimal | 13 |
| Hexadecimal A to decimal | 10 |
| Hexadecimal 1F to decimal | 31 |
| Binary 1111 to hexadecimal | F |

## Task 5.2 - Python Verification

I used Python built-in functions to verify the conversions.

| Code | Result |
|---|---|
| bin(13) | 0b1101 |
| bin(25) | 0b11001 |
| int("1010", 2) | 10 |
| int("1101", 2) | 13 |
| int("A", 16) | 10 |
| int("1F", 16) | 31 |
| hex(int("1111", 2)) | 0xf |

## Task 5.3 - Number Converter

I created a Python program called number_converter.py.

```python
number = int(input("Enter a decimal number: "))
print("Binary:", bin(number)[2:])
print("Hexadecimal:", hex(number)[2:].upper())
```

The program takes a decimal number as input and displays its binary and hexadecimal representations.

### Test Results

| Input | Binary | Hexadecimal |
|---|---|---|
| 13 | 1101 | D |
| 25 | 11001 | 19 |
| 31 | 11111 | 1F |

## Task 5.4 - ASCII and UTF-8

ASCII is a character encoding standard that assigns numerical values to basic English characters, digits and symbols.

| Character | ASCII Value |
|---|---|
| A | 65 |
| a | 97 |

UTF-8 is an encoding standard capable of representing characters from many languages, symbols and emoji. It is compatible with ASCII for basic characters.

## Learning

I learned how to convert numbers between decimal, binary and hexadecimal, verify conversions using Python, create a number converter program, and understand ASCII and UTF-8 character encoding.
