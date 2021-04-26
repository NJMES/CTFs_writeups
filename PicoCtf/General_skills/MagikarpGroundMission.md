# Magikarp Ground Mission

#generalskills #30points

## Description

Do you know how to move between directories and read files in the shell? Start the container, `ssh` to it, and then `ls` once connected to begin. Login via `ssh` as `ctf-player` with the password, `6d448c9c`

debug info: [u:79889 e: p: c:189 i:1055]

hint 1: Finding a cheatsheet for bash would be really helpful!

process:
    -njm3s-picoctf@webshell:~$ ssh ctf-player@venus.picoctf.net -p 51198
The authenticity of host '[venus.picoctf.net]:51198 ([3.131.124.143]:51198)' can't be established.
ECDSA key fingerprint is SHA256:NrQkIxNEQQho/GA7jE0WlIa7Jh4VF9sAvC5awkbuj1Q.
Are you sure you want to continue connecting (yes/no/[fingerprint])?

    -enter: SHA256:NrQkIxNEQQho/GA7jE0WlIa7Jh4VF9sAvC5awkbuj1Q.
    -Please type 'yes', 'no' or the fingerprint: 
    -enter: yes
Warning: Permanently added '[venus.picoctf.net]:51198,[3.131.124.143]:51198' (ECDSA) to the list of known hosts.
ctf-player@venus.picoctf.net's password: 
    - enter: 6d448c9c
  
    - ctf-player@pico-chall$ ls
    - shown: 1of3.flag.txt  instructions-to-2of3.txt
    - cat 1of3.flag.txt
      - reads: picoCTF{xxsh_
    - cat instructions-to-2of3.txt 
      - reads: Next, go to the root of all things, more succinctly `/`
    - enter: cd /       #go to root.
      - reads: ctf-player@pico-chall$ #nothing changed?
    - enter: pwd
      - reads: /  #shows root.
    - enter: ls
      - shown: 2of3.flag.txt  bin  boot  dev  etc  home  instructions-to-3of3.txt  lib ....
      - cat 2of3.flag.txt : 0ut_0f_\/\/4t3r_
      - cat instructions-to-3of3.txt : Lastly, ctf-player, go home... more succinctly `~` 
    - cd ~              #go to home.
    - ls : 3of3.flag.txt  drop-in
    - cat 3of3.flag.txt  : 5190b070}

Flag: picoCTF{xxsh_0ut_0f_\/\/4t3r_5190b070}