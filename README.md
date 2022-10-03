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

- The challenge numbers in black/white lines are part of the original challenge and are expressed in [base 10](https://en.wikipedia.org/wiki/Base_10), while the challenge numbers in yellow lines are part of the 2001 expansion and are expressed in [base 2](https://en.wikipedia.org/wiki/Base_2)

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
|[RSA-160](https://en.wikipedia.org/wiki/RSA-160 | 160 | 530 |	---     | April 1, 2003 | [Jens Franke](https://en.wikipedia.org/wiki/Jens_Franke)., [University of Bonn](https://en.wikipedia.org/wiki/University_of_Bonn)|
|[RSA-170](https://en.wikipedia.org/wiki/RSA-170 | 170 | 563 |  ---     | December 29, 2009 | D. Bonenberger and M. Krone|
```diff
|- [RSA-576](https://en.wikipedia.org/wiki/RSA-576 | 174 |576 | US$10,000 | December 3, 2003 |[Jens Franke](https://en.wikipedia.org/wiki/Jens_Franke)., [University of Bonn](https://en.wikipedia.org/wiki/University_of_Bonn)|
``` 
## See also
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
