# Matryoshka doll
#forensics #30point 

## Description

Matryoshka dolls are a set of wooden dolls of decreasing size placed one inside another.
What's the final one? Image: this (https://mercury.picoctf.net/static/5ef2e9103d55972d975437f68175b9ab/dolls.jpg)

hint 1: Wait, you can hide files inside files? But how do you find them?
hint 2: Make sure to submit the flag as picoCTF{XXXXX}

---
## process:
- wget:(https://mercury.picoctf.net/static/5ef2e9103d55972d975437f68175b9ab/dolls.jpg)
- exiftool dolls.jpg nothing.
- foremost dolls.jpg [[foremost]] #foremost-to-extract-file
- extracted dolls.jpg--> output folder
	- go in output/
		- cat audit.txt --> tells me zip folder contains 00000532.zip - 370 KB
			- cd zip/
				- unzip 00000532.zip
					- base_image/
						- 2_c.jpg
							- foremost 2_c.jpg --> output/ folder
								- repeated steps ..... till 4_c.jpg
									- cd zip/ ... unzip 00000155.zip
											-  cat flag.txt
			
**FLAG**: picoCTF{e3f378fe6c1ea7f6bc5ac2c3d6801c1f}