# Python Wrangling

#generalskill #10points

## Description

Python scripts are invoked kind of like programs in the Terminal... 
Can you run this Python script: link(https://mercury.picoctf.net/static/8e33ede04d02f3765b8c6a6e24d72733/ende.py)
using this password: link(https://mercury.picoctf.net/static/8e33ede04d02f3765b8c6a6e24d72733/pw.txt)
to get the flag? link(https://mercury.picoctf.net/static/8e33ede04d02f3765b8c6a6e24d72733/flag.txt.en)

hint 1: Get the Python script accessible in your shell by entering the following command in the Terminal prompt: 
$ wget https://mercury.picoctf.net/static/8e33ede04d02f3765b8c6a6e24d72733/ende.py

hint 2: $ man python #python manual.

Process:
    - python ende.py. 
      - result:  ende.py (-e/-d) [file] #what is -e and -d?
    - man python 
      - #-d    Turn on parser debugging output (for expert only, depending on compilation options).
      - #-e    Not found. not sure what is this for.
    - cat pw.txt
      - result: aa821c16aa821c16aa821c16aa821c16 #password key?
    - python ende.py -e flag.txt.en
      - prompt password. enter: aa821c16aa821c16aa821c16aa821c16 #failed.
    - python ende.py -d flag.txt.en
      - prompt for pass. enter: aa821c16aa821c16aa821c16aa821c16 #sucess

flag: picoCTF{4p0110_1n_7h3_h0us3_aa821c16}