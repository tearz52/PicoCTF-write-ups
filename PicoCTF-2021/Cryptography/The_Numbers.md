# The Numbers

## Description
The numbers... what do they mean?
numbers.png

## Hints
The flag is in the format PICOCTF{CTF}

## Solution
Downloading the png file and opening it gives us a series of numbers in the form of a flag.

**16 9 3 15 3 15 3 20 6 { 20 8 5 14 21 13 2 5 18 19 13 1 19 15 14 }**

From what we can see, we can assume that it is a cipher encoded with Letter Number Cipher.

Let's try to decode it using a Letter Number decoder via CyberChef and see what we get.

**picococtf{thenumbersmason}**

The above string is what we get in the form of plaintext.

From the hint, we know that the flag has to be in the form of picoCTF{}.

Thus, lets remove the extra words in the plaintext and voila, we found our answer!

**flag:** picoctf{thenumbersmason}