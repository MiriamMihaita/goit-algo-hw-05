"# goit-algo-hw-05"


Conclusions on the Speed ​​of Substring Search Algorithms Text: Example Article For the example text used, the execution times of the Boyer-Moore, Knuth-Morris-Pratt and Rabin-Karp algorithms for existing and non-existing substrings were analyzed. Here are the detailed findings:

Existing Substrings Boyer-Moore:

Execution time: 0.00169 s Remarks: The algorithm has been shown to be efficient in finding substrings, benefiting from the ability to skip large sections of text when it finds no partial matches. Knuth-Morris-Pratt (KMP):

Execution time: 0.00131 s Remarks: It was the fastest of the algorithms tested for existing substrings due to the efficient construction of the LPS table, which reduces the number of comparisons. Rabin-Karp:

Execution time: 0.00202 s Remarks: It was the slowest of the three, probably due to the overhead of calculating and comparing the hash values. Nonexistent Substrings Boyer-Moore:

Execution time: 0.00219 s Remarks: It continued to be effective, showing a reasonable increase in execution time, but remaining faster than the other methods. Knuth-Morris-Pratt:

Execution time: 0.00261 s Remarks: It was slower than Boyer-Moore but faster than Rabin-Karp, efficiently handling cases where there are no matches. Rabin-Karp:

Execution time: 0.00337 s Remarks: It was again the slowest, especially for nonexistent substrings, due to the full check of all possible positions. General Conclusions Knuth-Morris-Pratt is preferred for searching existing substrings due to its speed, being ideal for large texts and cases where substrings are frequently present. Boyer-Moore is very efficient for searching for nonexistent substrings as well as existing substrings, with a good trade-off between execution speed and the number of comparisons required. Rabin-Karp, while more versatile in applicability, including for searching multiple substrings at once, is less efficient in general cases due to the extra time required to handle hash collisions and final checking. In conclusion, the choice of the optimal algorithm depends on the nature of the search (existing or non-existent) and the specific characteristics of the text and substring. Boyer-Moore and Knuth-Morris-Pratt are generally the fastest and most efficient options.



Task 3
Conclusions on the Speed ​​of Substring Search Algorithms
Text: Example Article
For the example text used, the execution times of the Boyer-Moore, Knuth-Morris-Pratt and Rabin-Karp algorithms for existing and non-existing substrings were analyzed. Here are the detailed findings:

Existing Substrings
Boyer-Moore:

Execution time: 0.00169 s
Remarks: The algorithm has been shown to be efficient in finding substrings, benefiting from the ability to skip large sections of text when it finds no partial matches.
Knuth-Morris-Pratt (KMP):

Execution time: 0.00131 s
Remarks: It was the fastest of the algorithms tested for existing substrings due to the efficient construction of the LPS table, which reduces the number of comparisons.
Rabin-Karp:

Execution time: 0.00202 s
Remarks: It was the slowest of the three, probably due to the overhead of calculating and comparing the hash values.
Nonexistent Substrings
Boyer-Moore:

Execution time: 0.00219 s
Remarks: It continued to be effective, showing a reasonable increase in execution time, but remaining faster than the other methods.
Knuth-Morris-Pratt:

Execution time: 0.00261 s
Remarks: It was slower than Boyer-Moore but faster than Rabin-Karp, efficiently handling cases where there are no matches.
Rabin-Karp:

Execution time: 0.00337 s
Remarks: It was again the slowest, especially for nonexistent substrings, due to the full check of all possible positions.
General Conclusions
Knuth-Morris-Pratt is preferred for searching existing substrings due to its speed, being ideal for large texts and cases where substrings are frequently present.
Boyer-Moore is very efficient for searching for nonexistent substrings as well as existing substrings, with a good trade-off between execution speed and the number of comparisons required.
Rabin-Karp, while more versatile in applicability, including for searching multiple substrings at once, is less efficient in general cases due to the extra time required to handle hash collisions and final checking.
In conclusion, the choice of the optimal algorithm depends on the nature of the search (existing or non-existent) and the specific characteristics of the text and substring. Boyer-Moore and Knuth-Morris-Pratt are generally the fastest and most efficient options.





