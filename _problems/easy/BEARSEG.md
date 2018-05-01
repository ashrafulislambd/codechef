---
category_name: easy
problem_code: BEARSEG
problem_name: 'Bear and Segments'
languages_supported:
    - ADA
    - ASM
    - BASH
    - BF
    - C
    - 'C99 strict'
    - CAML
    - CLOJ
    - CLPS
    - 'CPP 4.3.2'
    - 'CPP 4.9.2'
    - CPP14
    - CS2
    - D
    - ERL
    - FORT
    - FS
    - GO
    - HASK
    - ICK
    - ICON
    - JAVA
    - JS
    - 'LISP clisp'
    - 'LISP sbcl'
    - LUA
    - NEM
    - NICE
    - NODEJS
    - 'PAS fpc'
    - 'PAS gpc'
    - PERL
    - PERL6
    - PHP
    - PIKE
    - PRLG
    - PYPY
    - PYTH
    - 'PYTH 3.4'
    - RUBY
    - SCALA
    - 'SCM chicken'
    - 'SCM guile'
    - 'SCM qobi'
    - ST
    - TCL
    - TEXT
    - WSPC
max_timelimit: '2'
source_sizelimit: '50000'
problem_author: admin2
problem_tester: lg5293
date_added: 29-04-2017
tags:
    - admin2
    - bst
    - easy
    - ltime47
    - partial
time:
    view_start_date: 1493485200
    submit_start_date: 1493485200
    visible_start_date: 1493485200
    end_date: 1735669800
    current: 1497284055
layout: problem
---
All submissions for this problem are available.###  Read problems statements in [Mandarin Chinese](http://www.codechef.com/download/translated/LTIME47/mandarin/BEARSEG.pdf), [Russian](http://www.codechef.com/download/translated/LTIME47/russian/BEARSEG.pdf) and [Vietnamese](http://www.codechef.com/download/translated/LTIME47/vietnamese/BEARSEG.pdf) as well.

Bear Limak has a sequence of **N** non-negative integers **A**1, **A**2, ..., **AN**. He defines the score of a segment (consecutive subsequence) as its sum of elements modulo **P** (not necessarily prime). Find the maximum score of a non-empty segment, and also find the number of segments with this maximum score.

### Input

First line of the input contains an integer **T** denoting the number of test cases. The description of **T** test cases follows.

For each test case, the first line of the input contains two space separated integers, **N** and **P**.

The second line contains **N** space separated integers denoting the sequence.

### Output

For each test case, output two space separated integers denoting the maximum score of a segment and the number of segments with the score, respectively.

### Constraints

- 1 ≤ **T** ≤ 10
- 1 ≤ **N** ≤ 105
- 1 ≤ **P** ≤ 109
- 0 ≤ **A**i ≤ 109

**Subtask #1: (25 points)**

- 1 ≤ **N** ≤ 100

**Subtask #2: (25 points)**

- 1 ≤ **N** ≤ 1000

**Subtask #3: (50 points)**

- original constraints

### Example

<pre><b>Input:</b>
4
2 3
1 2
3 5
2 4 3
3 100
1 3 5
4 3
1 2 3 4

<b>Output:</b>
2 1
4 2
9 1
2 2
</pre>### Explanation

**Example case 1.** There are three segments - \[1\], \[2\] and \[1, 2\]. Sum of these segments are 1, 2 and 3 respectively. Sum of these segments modulo 3 will be 1, 2 and 0. Maximum score among these is 2. There is also only one segment with this score.

**Example case 2.** There are six segments - \[2\], \[4\], \[3\], \[2, 4\], \[4, 3\] and \[2, 4, 3\]. Sum of these segments are 2, 4, 3, 6, 7, 9 respectively. Sum of these segments modulo 5 will be 2, 4, 3, 1, 2, 4. Maximum score among these is 4. And there are two segments with this score.