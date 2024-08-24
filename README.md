# In Week 1 Main.py you want to follow the following instructions:
Write a program for Covid Testing Pre-Screening.  Use a While loop to make a menu with the choices:

### 1. Temperature

### 2. Have you traveled recently?

### 3. Have you been around someone who has tested positive?

### 4. Results

### 5. Exit

If they choose temperature, ask the user for their temperature and store in a variable.  
For 2 and 3, ask the user yes or no and store in a variable.  
For Results, if at least 2 of the choices were met (Temperature >=99, yes for 2, yes for 3), 
tell them to take the Covid test.  Exit will close the program.

# In Week 1 Secondary.py you want to follow the following instructions:

Pick one of the three following challenges to complete, and put the solving code in this file.
The codewars link is included if you would like to use their 
testing system to verify your answer, and read discussions and see 
other solutions after you completed it.
When using codewars or doing these solutions make sure to use a function and return a value. Contact me if you are unsure what I mean.
Feel free to do all three if you would like.


## Number 1 source: https://www.codewars.com/kata/546e2562b03326a88e000020/python
Welcome. In this kata, you are asked to square every digit of a number and concatenate them.
For example, if we run 9119 through the function, 811181 will come out, because 92 is 81 and 12 is 1. (81-1-1-81)
Example #2: An input of 765 will/should return 493625 because 72 is 49, 62 is 36, and 52 is 25. (49-36-25)
Note: The function accepts an integer and returns an integer.
Happy Coding!

## Number 2 source: https://www.codewars.com/kata/554e4a2f232cdd87d9000038/train/python
Deoxyribonucleic acid (DNA) is a chemical found in the nucleus of cells and carries the "instructions" for the development and functioning of living organisms.
If you want to know more: http://en.wikipedia.org/wiki/DNA
In DNA strings, symbols "A" and "T" are complements of each other, as "C" and "G". Your function receives one side of the DNA (string, except for Haskell); you need to return the other complementary side. DNA strand is never empty or there is no DNA at all (again, except for Haskell).
More similar exercise are found here: http://rosalind.info/problems/list-view/ (source)

## Number 3 source: https://www.codewars.com/kata/57aa3927e298a757820000a8
Introduction
Back then when the internet was coming up, most search functionalities simply looked for keywords in text to show relevant documents. Hackers weren't very keen on having their information displayed on websites, bulletin boards, newsgroups or any other place, so they started to replace certain letters in words. It started out with simple vowel substitutions like a 4 instead of an A, or a 3 instead of an E. This meant that topics like cracking or hacking remained undetected.

Here we will use a reduced version of the Leet Speak alphabet, but you can find more information here or at Wikipedia.

Task
You will receive a string composed by English words, string. You will have to return a cyphered version of that string.

The numbers corresponding to each letter are represented at the table below. Notice that different letters can share the same number. In those cases, one letter will be upper case and the other one lower case.

            1	2	3	4	5	6	7	8	9	0
Upper case	I	R	E	A	S	G	T	B		O
Lower case	l	z	e	a	s	b	t		g	o

Any character that is not at the table, does not change when cyphered.

Examples
Input: "Hello World". Output: "H3110 W0r1d"
Input: "I am your father". Output: "1 4m y0ur f47h3r"
Input: "I do not know what else I can test. Be cool. Good luck". Output: "1 d0 n07 kn0w wh47 3153 1 c4n 7357. 83 c001. 600d 1uck"