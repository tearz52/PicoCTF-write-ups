# interencdec

## **Description**: 
Can you get the real meaning from this file.
Download the file here

## **Hints**:
Engaging in various decoding processes is of utmost importance

## **Solution**:
Opening the downloaded file in Notepad gives us the string below

**YidkM0JxZGtwQlRYdHFhR3g2YUhsZmF6TnFlVGwzWVROclh6ZzVNR3N5TXpjNWZRPT0nCg==**

Judging from the string ending with "==", we can assume that the provided string is in Base64 format. 

So, lets try to decode this in a Base64 Decoder and see what we get.

**b'd3BqdkpBTXtqaGx6aHlfazNqeTl3YTNrXzg5MGsyMzc5fQ=='**

The above string is what we get after decoding the Base64 string.

However, we can still see that the string still seems to be in Base64. Let's try to remove "b''" from the string and decode it again.

**wpjvJAM{jhlzhy_k3jy9wa3k_890k2379}**

The above is the result after decoding it again. 

As we can see, we managed to find a string that seems to resemble a flag format.

Looks like we can use the **caesar cipher** to decode it!

After using the caesar cipher, we get:

**picoCTF{caesar_d3cr9pt3d_890d2379}**

That's it!