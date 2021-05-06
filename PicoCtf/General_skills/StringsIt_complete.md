# strings it

#generalskills #100points


## Description

Can you find the flag in file without running it?
file. link(https://jupiter.challenges.picoctf.org/static/fae9ac5267cd6e44124e559b901df177/strings)

hint1 : https://linux.die.net/man/1/strings

process:
    - wget https://jupiter.challenges.picoctf.org/static/fae9ac5267cd6e44124e559b901df177/strings
    - strings strings   #use string to read strings file.
      - result: too much content 
    - strings -n 2 strings
      - still too much content.
    - strings strings | less
      -  still too much content.
    - strings.o | less
      -  still too much content.
    - https://www.thegeekstuff.com/2010/11/strings-command-examples/
    - strings -n 2 strings | grep picoCTF   #grep to search for picoctf
      - result bingo:  picoCTF{5tRIng5_1T_7f766a23}
    - strings strings | grep picoCTF
      - Result : picoCTF{5tRIng5_1T_7f766a23}

flag: picoCTF{5tRIng5_1T_7f766a23}

