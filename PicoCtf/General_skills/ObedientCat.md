# Obedient Cat

#general skills]] #5points

## Description

This file has a flag in plain sight (aka "in-the-clear"). 
Download flag ( https://mercury.picoctf.net/static/217686fc11d733b80be62dcfcfca6c75/flag ).

hint 1: Any hints about entering a command into the Terminal (such as the next one), will start with a '$'... everything after the dollar sign will be typed (or copy and pasted) into your Terminal.

hint 2: To get the file accessible in your shell, enter the following in the Terminal prompt: 
$ wget https://mercury.picoctf.net/static/217686fc11d733b80be62dcfcfca6c75/flag

hint 3: $ man cat

Solution:
    1. Download content using webshell
        - wget https://mercury.picoctf.net/static/217686fc11d733b80be62dcfcfca6c75/flag

    2. open using cat on file. #cat is used to open and read file        
        - cat flag.
        - flag: picoCTF{s4n1ty_v3r1f13d_b5aeb3dd}