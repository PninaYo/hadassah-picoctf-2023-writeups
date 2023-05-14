# HideToSee
This is the write-up for the challenge "HideToSee" challenge in PicoCTF

# The challenge
## Description
How about some hide and seek heh?
Look at this image here.

![](Img/1.png)

The image:

![](Img/2.png)

## Hint
Download the image and try to extract it.

# How to solve it
I attempted to decode the hidden message within the photo using a Steganography Online tool. However, the resulting message was not clear or easily decipherable.
![](Img/3.png)
![](Img/4.png)

To further investigate, I then tried a different tool called Steganographic Decoder and uploaded the same image.
![](Img/5.png)

After successfully decoding the hidden message using a steganographic decoder, I obtained the flag. However, the flag was encrypted, so I proceeded to decrypt it using the Cipher Chef website with the Atbash Cipher. 

![](Img/6.png)
![](Img/7.png)

The flag is: picoCTF{atbash_crack_1f84d779}

:))
