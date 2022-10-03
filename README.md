# About
## RSA Factoring Challenge
From [Wikipedia](https://en.wikipedia.org/wiki/RSA_Factoring_Challenge)

The ``RSA Factoring Challenge`` was a challenge put forward by [RSA Laboratories](https://en.wikipedia.org/wiki/RSA_Laboratories) on March 18, 1991 to encourage research into [computational number theory](https://en.wikipedia.org/wiki/Computational_number_theory) and the practical difficulty of [factoring](https://en.wikipedia.org/wiki/Factorization) large [integers](https://en.wikipedia.org/wiki/Integer) and cracking [RSA](https://en.wikipedia.org/wiki/RSA_(algorithm)) keys used in [cryptography](https://en.wikipedia.org/wiki/Cryptography). They published a list of [semiprimes](https://en.wikipedia.org/wiki/Semiprime) (numbers with exactly two [prime factors](https://en.wikipedia.org/wiki/Prime_factor) ) known as the [RSA numbers](https://en.wikipedia.org/wiki/RSA_numbers), with a cash prize for the successful factorization of some of them. The smallest of them, a 100-decimal digit number called [RSA-100](https://en.wikipedia.org/wiki/RSA-100) was factored by April 1, 1991. Many of the bigger numbers have still not been factored and are expected to remain unfactored for quite some time, however advances in [quantum computers](https://en.wikipedia.org/wiki/Quantum_computer) make this prediction uncertain due to [Shor's algorithm.](https://en.wikipedia.org/wiki/Shor%27s_algorithm)

In 2001, RSA Laboratories expanded the factoring challenge and offered prizes ranging from $10,000 to $200,000 for factoring numbers from 576 bits up to 2048 bits.

The RSA Factoring Challenges ended in 2007. RSA Laboratories stated: "Now that the industry has a considerably more advanced understanding of the cryptanalytic strength of common [symmetric-key](https://en.wikipedia.org/wiki/Symmetric_key_algorithm) and [public-key algorithms](https://en.wikipedia.org/wiki/Public_key_algorithm), these challenges are no longer active." When the challenge ended in 2007, only RSA-576 and RSA-640 had been factored from the 2001 challenge numbers.

The factoring challenge was intended to track the cutting edge in integer factorization. A primary application is for choosing the [key length](https://en.wikipedia.org/wiki/Key_length) of the [RSA](https://en.wikipedia.org/wiki/RSA_(algorithm)) [public-key encryption](https://en.wikipedia.org/wiki/Public-key_encryption) scheme. Progress in this challenge should give an insight into which [key sizes](https://en.wikipedia.org/wiki/Key_size) are still safe and for how long. As RSA Laboratories is a provider of RSA-based products, the challenge was used by them as an incentive for the academic community to attack the core of their solutions — in order to prove its strength.

The RSA numbers were generated on a computer with no network connection of any kind. The computer's hard drive was subsequently destroyed so that no record would exist, anywhere, of the solution to the factoring challenge.

The first RSA numbers generated, RSA-100 to RSA-500 and RSA-617, were labeled according to their number of [decimal](https://en.wikipedia.org/wiki/Decimal) digits; the other RSA numbers (beginning with RSA-576) were generated later and labelled according to their number of [binary](https://en.wikipedia.org/wiki/Binary_numeral_system) digits. The numbers in the table below are listed in increasing order despite this shift from decimal to binary.

### Content:
1. [The mathematics](https://github.com/Joshdb-18/RSA-Factoring-Challenge#the-mathematics)
2. [The prizes and records](https://github.com/Joshdb-18/RSA-Factoring-Challenge#the-prizes-and-records)
3. [See also](https://github.com/Joshdb-18/RSA-Factoring-Challenge#see-also)

## The mathematics
RSA Laboratories states that: for each RSA number n, there exists prime numbers p and q such that:

`` n = p x q``

The problem is to find these two primes, given only n

## The prizes and records
The following table gives an overview over all RSA numbers. Note that the RSA Factoring Challenge ended in 2007 and no further prizes will be awarded for factoring the higher numbers.

- All the challenge numbers are part of the original challenge and are expressed in [base 10](https://en.wikipedia.org/wiki/Base_10), while the other challenge numbers``(RSA-576, RSA-640, RSA-704, RSA-768, RSA-896, RSA-1024, RSA-1536 and RSA-2048)`` are part of the 2001 expansion and are expressed in [base 2](https://en.wikipedia.org/wiki/Base_2)

| RSA number | Decimal digits | Binary digits | Cash prize offered | Factored on | Factored by |
| --- | --- | --- | --- | --- | --- |
|[RSA-100](https://en.wikipedia.org/wiki/RSA-100)| 100 | 330 | US$1,000 | April, 1 1991 | [Arjen K. Lenstra](https://en.wikipedia.org/wiki/Arjen_K._Lenstra)|
|[RSA-110](https://en.wikipedia.org/wiki/RSA-110)| 110 | 364 | US$2,429 | April 14, 1992 | [Arjen K. Lenstra](https://en.wikipedia.org/wiki/Arjen_K._Lenstra) and M.S. Manasse |
|[RSA-120](https://en.wikipedia.org/wiki/RSA-120)| 120 | 397 | US$5,898 | July 9, 1993 | T. Denny |
|[RSA-129](https://en.wikipedia.org/wiki/RSA-129)| 129 | 426 | US$100 | April 26, 1994 | [Arjen K. Lenstra](https://en.wikipedia.org/wiki/Arjen_K._Lenstra)|
|[RSA-130](https://en.wikipedia.org/wiki/RSA-130)| 130 | 430 | US$14,527 | April 10, 1996 | [Arjen K. Lenstr](https://en.wikipedia.org/wiki/Arjen_K._Lenstra)|
|[RSA-140](https://en.wikipedia.org/wiki/RSA-140)| 140 | 463 | US$17,226 | February 2, 1999 | [Herman te Riele](https://en.wikipedia.org/wiki/Herman_te_Riele)|
|[RSA-150](https://en.wikipedia.org/wiki/RSA-150)| 150 | 496 |	---     | April 16, 2004 | [Kazumaro Aoki](https://en.wikipedia.org/wiki/Kazumaro_Aoki)|
|[RSA-155](https://en.wikipedia.org/wiki/RSA-155)| 155 | 512 | US$9,383 | August 22, 1999 | [Herman te Riele](https://en.wikipedia.org/wiki/Herman_te_Riele)|
|[RSA-160](https://en.wikipedia.org/wiki/RSA-160)| 160 | 530 |	---     | April 1, 2003 | [Jens Franke](https://en.wikipedia.org/wiki/Jens_Franke)., [University of Bonn](https://en.wikipedia.org/wiki/University_of_Bonn)|
|[RSA-170](https://en.wikipedia.org/wiki/RSA-170)| 170 | 563 |  ---     | December 29, 2009 | D. Bonenberger and M. Krone|
|[RSA-576](https://en.wikipedia.org/wiki/RSA-576)| 174 | 576 | US$10,000 | December 3, 2003 |[Jens Franke](https://en.wikipedia.org/wiki/Jens_Franke)., [University of Bonn](https://en.wikipedia.org/wiki/University_of_Bonn)| 
|[RSA-180](https://en.wikipedia.org/wiki/RSA-180)| 180 | 596 |  ---     | May 8, 2010 | S.A Danilov and I.A Popovyan, [Mosco State University](https://en.wikipedia.org/wiki/Moscow_State_University)|
|[RSA-190](https://en.wikipedia.org/wiki/RSA-190)| 190 | 629 |  ---	|November 8, 2010 | A. Timofeev and I. A. Popovyan|
|[RSA-640](https://en.wikipedia.org/wiki/RSA-640)| 193 | 640 | US$20,000 | November 2, 2005 | [Jens Franke](https://en.wikipedia.org/wiki/Jens_Franke)., [University of Bonn](https://en.wikipedia.org/wiki/University_of_Bonn)|
|[RSA-200](https://en.wikipedia.org/wiki/RSA-200)| 200 | 663 |  ---     | May 9, 2005 | [Jens Franke et al](https://en.wikipedia.org/wiki/Jens_Franke), [University of Bonn](https://en.wikipedia.org/wiki/University_of_Bonn)|
|[RSA-210](https://en.wikipedia.org/wiki/RSA-210)| 210 | 696 |  ---     | September 26, 2013 | Ryan Propper|
|[RSA-704](https://en.wikipedia.org/wiki/RSA-704)| 212 | 704 | US$30,000 | July 2, 2012| Shi Bai, Emmanuel Thomé and [Paul Zimmermann](https://en.wikipedia.org/wiki/Paul_Zimmermann_(mathematician))|
|[RSA-220](https://en.wikipedia.org/wiki/RSA-220)| 220 | 729 |  ---     | May 13, 2016 | S. Bai, P. Gaudry, A. Kruppa, E. Thomé and P. Zimmermann|
|[RSA-230](https://en.wikipedia.org/wiki/RSA-230)| 230 | 762 |  ---     | August 15, 2018 | Samuel S. Gross, [Noblis, Inc.](https://noblis.org/)|
|[RSA-232](https://en.wikipedia.org/wiki/RSA-232)| 232 | 768 |  ---     | February 17, 2020 | N. L. Zamarashkin, D. A. Zheltkov and S. A. Matveev.|
|[RSA-768](https://en.wikipedia.org/wiki/RSA-768)| 232 | 768 | US$50,000 | December 12, 2009 | Thorsten Kleinjung|
|[RSA-240](https://en.wikipedia.org/wiki/RSA-240)| 240 | 795 |  ---     |Dec 2, 2019 | F. Boudot, P. Gaudry, A. Guillevic, N. Heninger, E. Thomé and P. Zimmermann|
|[RSA-250](https://en.wikipedia.org/wiki/RSA-250)| 250 | 829 |  ---     | Feb 28, 2020 | F. Boudot, P. Gaudry, A. Guillevic, N. Heninger, E. Thomé and P. Zimmermann|
|[RSA-260](https://en.wikipedia.org/wiki/RSA-260)| 260 | 862 |  ---     | --- | --- |	
|[RSA-270](https://en.wikipedia.org/wiki/RSA-270)| --- | --- | ---      | --- | --- |
|[RSA-896](https://en.wikipedia.org/wiki/RSA-896)| 270 | 896 | US$75,000 | ---| --- |
|[RSA-280](https://en.wikipedia.org/wiki/RSA-280)| 280 | 928 |	---     | --- | --- |
|[RSA-290](https://en.wikipedia.org/wiki/RSA-290)| 290 | 962 |	---     | --- |	--- |
|[RSA-300](https://en.wikipedia.org/wiki/RSA-300)| 300 | 995 |	---     | --- |	--- |
|[RSA-309](https://en.wikipedia.org/wiki/RSA-309)| 309 | 1024 |	---     | --- |	--- |
|[RSA-1024](https://en.wikipedia.org/wiki/RSA-1024)| 309 | 1024 | US$100,000 | --- |--- |		
|[RSA-310](https://en.wikipedia.org/wiki/RSA-310)| 310 | 1028 |	---     | --- | --- |
|[RSA-320](https://en.wikipedia.org/wiki/RSA-320)| 320 | 1061 | ---	| --- |	--- |
|[RSA-330](https://en.wikipedia.org/wiki/RSA-330)| 330 | 1094 |	--- 	| --- |	--- |
|[RSA-340](https://en.wikipedia.org/wiki/RSA-340)| 340 | 1128 |	---	| --- |	--- |
|[RSA-350](https://en.wikipedia.org/wiki/RSA-350)| 350 | 1161 |	--- 	| --- |	--- |
|[RSA-360](https://en.wikipedia.org/wiki/RSA-360)| 360 | 1194 |	--- 	| --- |	--- |
|[RSA-370](https://en.wikipedia.org/wiki/RSA-370)| 370 | 1227 |	--- 	| --- |	--- |
|[RSA-380](https://en.wikipedia.org/wiki/RSA-380)| 380 | 1261 |	--- 	| --- |	--- |
|[RSA-390](https://en.wikipedia.org/wiki/RSA-390)| 390 | 1294 |	--- 	| --- |	--- |
|[RSA-400](https://en.wikipedia.org/wiki/RSA-400)| 400 | 1327 |	--- 	| --- |	--- |
|[RSA-410](https://en.wikipedia.org/wiki/RSA-410)| 410 | 1360 |	--- 	| --- |	--- |
|[RSA-420](https://en.wikipedia.org/wiki/RSA-420)| 420 | 1393 |	--- 	| --- |	--- |
|[RSA-430](https://en.wikipedia.org/wiki/RSA-430)| 430 | 1427 |	--- 	| --- |	--- |
|[RSA-440](https://en.wikipedia.org/wiki/RSA-440)| 440 | 1460 |	--- 	| --- |	--- |
|[RSA-450](https://en.wikipedia.org/wiki/RSA-450)| 450 | 1493 |	--- 	| --- |	--- |
|[RSA-460](https://en.wikipedia.org/wiki/RSA-460)| 460 | 1526 |	--- 	| --- |	--- |
|[RSA-1536](https://en.wikipedia.org/wiki/RSA-1536)| 463 | 1536 | US$150,000 |--- | --- |		
|[RSA-470](https://en.wikipedia.org/wiki/RSA-470)| 470 | 1559 |	---	| --- | --- |
|[RSA-480](https://en.wikipedia.org/wiki/RSA-480)| 480 | 1593 |	--- 	| --- |	--- |
|[RSA-490](https://en.wikipedia.org/wiki/RSA-490)| 490 | 1626 |	--- 	| --- |	--- |
|[RSA-500](https://en.wikipedia.org/wiki/RSA-500)| 500 | 1659 |	--- 	| --- |	--- |
|[RSA-617](https://en.wikipedia.org/wiki/RSA-617)| 617 | 2048 |	--- 	| --- |	--- |
|[RSA-2048](https://en.wikipedia.org/wiki/RSA-2048)| 617 | 2048 | US$200,000 | --- | --- |		

```diff
! RSA-129 was not part of the RSA Factoring Challenge, but was related to a column by Matrin Gardner in [Scientific American](https://en.wikipedia.org/wiki/Scientific_American).
! The number was factored after the challenge ended.
! RSA-170 was also independently factored by S.A Danilov and I.A Popovyan two days later.                            
! The challenge ended before the prize was awarded
```

## See also
- [RSA numbers](https://en.wikipedia.org/wiki/RSA_numbers), decimal expansions of the numbers and known factorizations
- [LCS35](https://en.wikipedia.org/wiki/LCS35)
- [The Magic Words are Squeamish Ossifrage](https://en.wikipedia.org/wiki/The_Magic_Words_are_Squeamish_Ossifrage), the solution found in 1993 to another RSA challenge posed in 1977
- [RSA Secret-Key Challenge](https://en.wikipedia.org/wiki/RSA_Secret-Key_Challenge)
- [Integer factorization records](https://en.wikipedia.org/wiki/Integer_factorization_records)

## Background Context

We have sniffed an unsecured network and found numbers that are used to encrypt very important documents. It seems that those numbers are not always generated using large enough prime numbers. Your mission should you choose to accept it, is to factorize these numbers as fast as possible before the target fixes this bug on their server - so that we can decode the encrypted documents.

## Resources
### Read or watch:

- [RSA](https://alx-intranet.hbtn.io/rltoken/VvijGiyWnPt8LDZjICgl1w)
- [How does HTTPS provide security?](https://alx-intranet.hbtn.io/rltoken/vNd9XWDEu1mgexyIGDMaXQ)
- [Prime Factorization](https://alx-intranet.hbtn.io/rltoken/kYixcru2uFRtLzb29NjiHg)

## Requirements
### General

- You can choose the language of your choice
- OS needs to be Standard Ubuntu 20.04 LTS/

## Tasks
### 0. Factorize all the things
Factorize as many numbers as possible into a product of two smaller numbers

- Usage: ``factors <file>``
	- where ``<file>`` is a file containing natural numbers to factor
	- One number per line
	- You can assume that all lines will be valid natural numbers greater than 1
	- You can assume that there will be no empty line, and no space before and after the valid number
	- The file will always end with a new line
- Output format: ``n=p*q``
	- One factorization per line
	- p and q don't have to be prime numbers
	- See example
- You can work on the numbers of the file in the order of your choice
- Your program should run without any dependency: You will not be able to install anything on the machine we will run your program on
- Time limit: Your program will be killed after 5 seconds if it hasn't finish
- Push all your scripts, source code, etc... to your repository
- we will only run your executable ``factors``

```
julien@ubuntu:~/factors$ cat tests/test00 
4
12
34
128
1024
4958
1718944270642558716715
9
99
999
9999
9797973
49
239809320265259
julien@ubuntu:~/factors$ time ./factors tests/test00
4=2*2
12=6*2
34=17*2
128=64*2
1024=512*2
4958=2479*2
1718944270642558716715=343788854128511743343*5
9=3*3
99=33*3
999=333*3
9999=3333*3
9797973=3265991*3
49=7*7
239809320265259=15485783*15485773

real    0m0.009s
user    0m0.008s
sys 0m0.001s
julien@ubuntu:~/factors$
```
### 1.RSA Factoring Challenge
RSA Laboratories states that: for each RSA number ``n``, there exist prime numbers ``p`` and ``q`` such that ``n = p x q.`` 
The problem is to find these two primes, given only ``n``

This task is the same as task 0, except:
```
p and q are always prime numbers
There is only one number in the files
```
How far can you go in less than 5 seconds?
- Read: [RSA Factoring Challenge](https://alx-intranet.hbtn.io/rltoken/Cn9Lq_kKNpNx4dmvFMuwgQ)
```
julien@ubuntu:~/RSA Factoring Challenge$ cat tests/rsa-1
6
julien@ubuntu:~/RSA Factoring Challenge$ ./rsa tests/rsa-1
6=3*2
julien@ubuntu:~/RSA Factoring Challenge$ cat tests/rsa-2
77
julien@ubuntu:~/RSA Factoring Challenge$ ./rsa tests/rsa-2
77=11*7
julien@ubuntu:~/RSA Factoring Challenge$ [...]  
julien@ubuntu:~/RSA Factoring Challenge$ cat tests/rsa-15
239821585064027
julien@ubuntu:~/RSA Factoring Challenge$ ./rsa tests/rsa-15 
239821585064027=15486481*15485867
julien@ubuntu:~/RSA Factoring Challenge$ cat tests/rsa-16
2497885147362973
julien@ubuntu:~/RSA Factoring Challenge$ ./rsa tests/rsa-16
2497885147362973=49979141*49978553
julien@ubuntu:~/RSA Factoring Challenge$ [...]
```
