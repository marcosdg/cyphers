# cyphers

## A reasoning system built in OTTER (theorem prover) solving the "ciphers" problem


I used [OTTER] (http://www.mcs.anl.gov/research/projects/AR/otter/) to build a Reasoning System that is
able to solve the following problem within the context of Search-Space problems:

"Given a set of *k* numbers: *n_1, n_2, ..., n_k* and a *target* number *t*. Find the appropiate combinations of 
basic arithmetic operations such as: sum, minus, product and division that reach the target number. 
Having in mind the following restrictions: 
  
  1. We only can subtract  *m* from *n*, that is *n-m*, if and only if n > m.
  2. Division is only possible if the *remainder* is equal to zero. In other words, the denominator
     is a *divisor* of the numerator."

### How to load the file: cyphers

1. We should have installed OTTER (you can find the source code in thet web page I indicated previously).
2. Copy the "cypher" file in the directory you want.
3. Open your favourite terminal and go to such directory.
4. To give OTTER our file as input we can use 'redirection' as follows:
    `otter < cyphers`
    
   If we want the **output result in a separate file**, enter the following:
    `otter < cyphers > some_output_file_name`

---
#### Note

cyphers file also contains documentation.
  
