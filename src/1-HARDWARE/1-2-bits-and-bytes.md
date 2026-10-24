# 1.2 Bits and bytes

Author: Matashev Ariet 1820262363 | Reviewed by: Benslima Khalid 1820262152 | Status: checked

Read 1.1 first.

## After this section you can

- explain what a bit and a byte are
- turn a small binary number into a normal number, and back
- explain how a computer stores text as numbers

## Start with light switches

A light switch has two states: off or on. Let's write off as 0 and on as 1.

- With 1 switch you can make 2 patterns: 0, 1
- With 2 switches you can make 4 patterns: 00, 01, 10, 11
- With 3 switches you can make 8 patterns: 000, 001, 010, 011, 100, 101, 110, 111

Every switch you add doubles the number of patterns.

Inside a computer there are billions of tiny electronic switches, and each one is either off (0) or on (1). One of these 0-or-1 values is called a **bit** (short for binary digit). A group of 8 bits is called a **byte**. With 8 bits you get 2 × 2 × 2 × 2 × 2 × 2 × 2 × 2 = 256 different patterns, so one byte can store 256 different values (0 to 255).

Numbers written only with 0s and 1s are called **binary** numbers.

## How binary numbers work

In normal (decimal) numbers, each place is worth 10 times the one to its right: ones, tens, hundreds. In binary, each place is worth **2 times** the one to its right.

Here are the place values for one byte:

| 128 | 64 | 32 | 16 | 8 | 4 | 2 | 1 |
| --- | --- | --- | --- | --- | --- | --- | --- |

*Figure 1.2.1: Place values in one byte. The rightmost place is worth 1, and each place to the left is worth double.*

## Worked example 1: binary to decimal

What is binary 1101 as a normal number?

Write it under the last four place values:

| 8 | 4 | 2 | 1 |
| --- | --- | --- | --- |
| 1 | 1 | 0 | 1 |

Add up the place values that have a 1 under them:

8 + 4 + 1 = 13

So binary 1101 = 13.

## Worked example 2: decimal to binary

How do we write 13 in binary? Go through the place values from the biggest one that fits, and subtract as you go.

1. Does 8 fit into 13? Yes. Write 1. 13 - 8 = 5 left.
2. Does 4 fit into 5? Yes. Write 1. 5 - 4 = 1 left.
3. Does 2 fit into 1? No. Write 0.
4. Does 1 fit into 1? Yes. Write 1. Nothing left.

Answer: 1101. As a full byte, we fill the empty places on the left with zeros: 00001101.

## How text is stored

A computer can only store 0s and 1s, so text has to be turned into numbers first. Everyone agrees on a code that gives each character a number. The basic code for English letters is called **ASCII**:

- "A" is 65, "B" is 66, "C" is 67, and so on up to "Z", which is 90.
- Lowercase "a" is 97.
- Even a space has a number: 32.

So when you type "A", the computer stores 65, which in binary is 01000001.

ASCII only covers English letters, digits and basic symbols. To store Russian, Chinese, Arabic or emoji, computers use a bigger code called **Unicode**, which has a number for almost every character in every language. Many of these characters need more than one byte.

## How big is a file?

- 1 **kilobyte** (KB) is about a thousand bytes
- 1 **megabyte** (MB) is about a million bytes
- 1 **gigabyte** (GB) is about a billion bytes

(Some computers count 1 KB as 1024 bytes instead of 1000, which is why sizes sometimes look slightly different on different devices.)

## Try it yourself

**Q1.** Turn these binary numbers into normal numbers: a) 1010  b) 11111111

**Q2.** Turn these numbers into binary: a) 6  b) 20

**Q3.** Decode this message. Each byte is one ASCII letter. Use the rule "A is 65, B is 66, and so on".

01001000 01001001

**Q4.** Why can't one byte store the number 300?

## Answers

**Q1.**

a) 1010 = 8 + 2 = **10**

b) 11111111 = 128 + 64 + 32 + 16 + 8 + 4 + 2 + 1 = **255**. This is the biggest number one byte can hold.

**Q2.**

a) 6: 4 fits (6 - 4 = 2 left), 2 fits (2 - 2 = 0 left), 1 doesn't fit. Answer: **110**

b) 20: 16 fits (20 - 16 = 4 left), 8 doesn't fit, 4 fits (0 left), 2 doesn't fit, 1 doesn't fit. Answer: **10100**

**Q3.** 01001000 = 64 + 8 = 72. 01001001 = 64 + 8 + 1 = 73. Counting from A = 65: 72 is H and 73 is I. The message is **HI**.

**Q4.** The biggest number one byte can hold is 255 (all eight bits set to 1). 300 is bigger than that, so it needs at least 9 bits, which means a computer uses 2 bytes for it.

## Common mistakes

- **Reading the place values from the wrong end.** The rightmost place is always worth 1.
- **Skipping the zeros.** In 10100 the zeros matter: they show which places are empty. Dropping them gives a different number.
- **Mixing up bits and bytes.** 1 byte = 8 bits. Internet speed is usually given in bits per second (Mbps), file size in bytes (MB), so a 100 Mbps connection downloads about 12.5 MB per second, not 100.

## Sources

1. Brookshear, J. G., & Brylow, D. (2019). *Computer Science: An Overview* (13th ed.). Pearson. Chapter 1, "Data Storage".
2. Wikipedia. "ASCII." https://en.wikipedia.org/wiki/ASCII (accessed 23 Oct 2026)
