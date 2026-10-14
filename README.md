# Base Converter

Base Converter is a small web app that converts numbers between decimal, binary, hex and octal. Type in any box and the other three update instantly. A 32-bit row of lights shows the binary value, and you can tap a light to flip that bit.

Live demo: https://rajshrestha-07.github.io/Base-Converter/

Built with: HTML, CSS and JavaScript.

What this project shows: A number can be written in different bases, but the value stays the same. Computers store everything in base 2, programmers often write it in base 16 because each hex digit equals exactly 4 bits, and people use base 10. The app also has shift buttons: shifting bits left multiplies by 2, and shifting right divides by 2. It shows the ASCII character for the number too, and the signed 32-bit value, which is how a computer reads the top bit as a negative sign.

What I'm learning from it: I'm studying how the code uses `parseInt(text, base)` to read a number and `number.toString(base)` to write it in another base, and how it checks that each box only accepts valid digits.
