# 0x11. C - printf Group Project

Group Project completed as part of the **full-stack Software Engineering program** at **ALX SE** to gain a comprehensive understanding of the **printf function** in the C programming language.

---

## Workshop Development
## Tasks

### 0. I'm not going anywhere. You can print that wherever you want to. I'm here, and I'm a Spur for life

Write a function that produces output according to a format.

- Prototype: int _printf(const char *format, ...);
- Returns: the number of characters printed (excluding the null byte used to end output to strings).
- Writes output to stdout, the standard output stream.
- The format is a character string composed of zero or more directives. You need to handle the following conversion specifiers:
  - s
  - c
  - %

### 1. Education is when you read the fine print. Experience is what you get if you don't

Write a function that prints numbers, followed by a new line.

- Handle the following conversion specifiers:
  - d
  - i

### 2. With a face like mine, I do better in print

Handle the following custom conversion specifier:

- b: The unsigned int argument is converted to binary.

### 3. What one has not experienced, one will never understand in print

Handle the following conversion specifiers:

- u
- o
- x
- X

### 4. Nothing in fine print is ever good news

Use a local buffer of 1024 chars to call write as little as possible.

### 5. My weakness is wearing too much leopard print

Handle the following custom conversion specifier:

- S: Prints the string.
- Non-printable characters (0 < ASCII value < 32 or >= 127) are printed this way: \x, followed by the ASCII code value in hexadecimal (uppercase - always 2 characters).

### 6. How is the world ruled and led to war? Diplomats lie to journalists and believe these lies when they see them in print

Handle the following conversion specifier:

- p

### 7. The big print gives and the small print takes away

Handle the following flag characters for non-custom conversion specifiers:

- +
- space
- #

### 8. Sarcasm is lost in print

Handle the following length modifiers for non-custom conversion specifiers:

- l
- h

### 9. Print some money and give it to us for the rainforests

Handle the field width for non-custom conversion specifiers.

### 10. The negative is the equivalent of the composer's score, and the print the performance

Handle the precision for non-custom conversion specifiers.

### 11. It's depressing when you're still around and your albums are out of print

Handle the 0 flag character for non-custom conversion specifiers.

### 12. Every time that I wanted to give up, if I saw an interesting textile, print whatever, suddenly I would see a collection

Handle the - flag character for non-custom conversion specifiers.

### 13. Print is the sharpest and the strongest weapon of our party

Handle the following custom conversion specifier:

- r: Prints the reversed string

### 14. The flood of print has turned reading into a process of gulping rather than savoring

Handle the following custom conversion specifier:

- R: Prints the rot13'ed string

### 15. All the above options work well together.

## Contributors
- [Claudia Ageha](https://github.com/Claudia-O-A) - Initial work
- [Meshack Bwire](https://github.com/BM-Ghost) - Initial work
---
[Repo](https://github.com/Claudia-O-A/printf)