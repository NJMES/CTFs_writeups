# mus1c

#generalskills #300points

## Description

I wrote you a song. link(https://jupiter.challenges.picoctf.org/static/0e21e3ca94779f56b122296424e879f8/lyrics.txt)
Put it in the picoCTF{} flag format.

hint1: Do you think you can master rockstar?

process:
    - wget https://jupiter.challenges.picoctf.org/static/0e21e3ca94779f56b122296424e879f8/lyrics.txt
      - cat lyrics.txt
      - result:
Pico's a CTFFFFFFF
my mind is waitin
It's waitin

Put my mind of Pico into This
my flag is not found
put This into my flag
put my flag into Pico


shout Pico
shout Pico
shout Pico

My song's something
put Pico into This

Knock This down, down, down
put This into CTF

shout CTF
my lyric is nothing
Put This without my song into my lyric
Knock my lyric down, down, down

shout my lyric

Put my lyric into This
Put my song with This into my lyric
Knock my lyric down

shout my lyric

Build my lyric up, up ,up

shout my lyric
shout Pico
shout It

Pico CTF is fun
security is important
Fun is fun
Put security with fun into Pico CTF
Build Fun up
shout fun times Pico CTF
put fun times Pico CTF into my song

build it up

shout it
shout it

build it up, up
shout it
shout Pico

    - rockstar decoder : https://codewithrockstar.com/online
      - input the lyrics
      - output: 1337
    - enter: picoCTF{1337} : failed.
    - input lyrics as programme - leave the input blank.
      - output: 
114
114
114
111
99
107
110
114
110
48
49
49
51
114
Program completed in 368 ms
    - translate octal to ascii : failed.
    - translate decimal to ascii. : sucess!!! 
      - rrrocknrn0113r

flag: picoCTF{rrrocknrn0113r}