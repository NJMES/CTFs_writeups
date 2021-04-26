# Based

#generalskills #200points

## Description

To get truly 1337, you must understand different data encodings, such as hexadecimal or binary. 
Can you get the flag from this program to prove you are on the way to becoming 1337? 
Connect with nc jupiter.challenges.picoctf.org 29956.

hint1: I hear python can convert things.
hint2: It might help to have multiple windows open.

process: 
    - nc jupiter.challenges.picoctf.org 29956
    - question: 
Please give the 01110000 01101001 01100101 as a word.
...
you have 45 seconds.....
    - Binary to Ascii converter : https://www.binaryhexconverter.com/binary-to-ascii-text-converter
      - result: pie
    - question:
Please give me the  154 141 155 160 as a word.
    - Octal to Ascii : https://onlineasciitools.com/convert-octal-to-ascii
      - result: lamp
Please give me the 6c616d70 as a word.
    - hex to Ascii convertor: https://onlinehextools.com/convert-hex-to-ascii
      - result: lamp
      - 
You've beaten the challenge

flag: picoCTF{learning_about_converting_values_b375bb16}