# Lets Warm Up

#generalskills #50points

## Description

If I told you a word started with 0x70 in hexadecimal, what would it start with in ASCII? 

    - 0x70 = p #hex to ascii
    - http://www.asciitable.com/

hint1: Submit your answer in our flag format. For example, if your answer was 'hello', you would submit 'picoCTF{hello}' as the flag.

process: 
    - convert from ascii to hex. #picoCTF{hello} to hex
        - # https://www.rapidtables.com/convert/number/ascii-to-hex.html
    - enter: 0x70 0x69 0x63 0x6f 0x43 0x54 0x46 0x7b 0x68 0x65 0x6c 0x6c 0x6f 0x7d #failed
    - convert hello to hex
        -68 65 6c 6c 6f
    - picoCTF{68 65 6c 6c 6f} #failed.
    - picoCTF{0x68 0x65 0x6c 0x6c 0x6f} // picoCTF{0x680x650x6c0x6c0x6f} #failed.
    - picoCTF{p} #sucess.

I overthinked the solution. #refer to line '9'

flag: picoCTF{p}

