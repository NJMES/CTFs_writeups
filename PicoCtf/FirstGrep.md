# First Grep

#generalskills #100points

## Description

Can you find the flag in file? (file)[https://jupiter.challenges.picoctf.org/static/515f19f3612bfd97cd3f0c0ba32bd864/file]
This would be really tedious to look through manually, 
something tells me there is a better way.

hint 1: grep tutorial
link: https://ryanstutorials.net/linuxtutorial/grep.php

process: 
    - wget https://jupiter.challenges.picoctf.org/static/515f19f3612bfd97cd3f0c0ba32bd864/file
    - cat file
      - result: chunks of text.
    - cat file | grep pico
      - result: picoCTF{grep_is_good_to_find_things_5af9d829}

flag: picoCTF{grep_is_good_to_find_things_5af9d829}
