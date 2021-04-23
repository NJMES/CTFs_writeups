# Nice netcat

#generalskills #15points

## Description

There is a nice program that you can talk to by using this command in a shell: 
$ nc mercury.picoctf.net 43239, but it doesn't speak English...

hint 1: You can practice using netcat with this picoGym problem: 
    - what's a netcat? link(https://play.picoctf.org/practice/challenge/34)

hint 2: You can practice reading and writing ASCII with this picoGym problem: 
    - Let's Warm Up! link(https://play.picoctf.org/practice/challenge/22)

process:
    - nc mercury.picoctf.net 43239
    - result:
112 105 99 111 67 84 70 123 103 48 48 100 95 107 49 116 116 121 33  95  110 49 
99 51 95 107 49 116 116 121 33 95 55 99 48 56 50 49 102 53 125 10  
    - # use ASCII table. # decimal to Ascii. # https://www.prepostseo.com/tool/decimal-to-ascii

flag : picoCTF{g00d_k1tty!_n1c3_k1tty!_7c0821f5}
