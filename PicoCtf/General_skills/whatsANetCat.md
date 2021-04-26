# what's a net cat?

#generalskills #100points

## Description

Using netcat (nc) is going to be pretty important. 
Can you connect to jupiter.challenges.picoctf.org at port 41120 to get the flag?

hint 1: netcat tutorial
https://linux.die.net/man/1/nc
    - nc - arbitrary TCP and UDP connections and 'listens' 

process:
    - what is port 41120 ??
      - https://www.speedguide.net/port.php?port=41120      #'port 41112-41120 	tcp,udp 		Unassigned.'
    - nc jupiter.challenges.picoctf.org 41120
      - result: You're on your way to becoming the net cat master picoCTF{nEtCat_Mast3ry_3214be47}

flag: picoCTF{nEtCat_Mast3ry_3214be47}