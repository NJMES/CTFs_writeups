# plumbing

#generalskills #200points


## Description

Sometimes you need to handle process data outside of a file. Can you find a way to keep the output from this program and search for the flag? Connect to jupiter.challenges.picoctf.org 4427.

hint 1: Remember the flag format is picoCTF{XXXX}

hint 2: What's a pipe? No not that kind of pipe... This kind
link: http://www.linfo.org/pipes.html

progress: 
    - nc jupiter.challenges.picoctf.org 4427
      - result:  too much text. 
    - nc jupiter.challenges.picoctf.org 4427 | grep pico
      - result: picoCTF{digital_plumb3r_5ea1fbd7}

flag: picoCTF{digital_plumb3r_5ea1fbd7}
