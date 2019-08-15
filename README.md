# PCY-Multistage-Algorithm
Implementation of PCY algorithm in python

Implementing the Multi-Stage algorithm to generate frequent itemsets. There are two stages using two different hashing functions for finding frequent itemsets of each size. Usng hashing functions which are independent of each other. Both the hashes will have the same number of buckets..

Executing code

python multistage.py input2.txt 2 20

Sample Output

memory for item counts: 48

memory for hash table 1 counts for size 2 itemsets: 80

{0: 0, 1: 2, 2: 0, 3: 2, 4: 2, 5: 3, 6: 2, 7: 1, 8: 1, 9: 0, 10: 0, 11: 0, 12: 0, 13: 0, 14: 0, 15: 0, 16: 0, 17: 0, 18: 0, 19: 0}

Frequent itemsets of size 1 : [['a'], ['d'], ['e']]

memory for frequent itemsets of size 1 : 24

bitmap 1 size: 20

memory for hash table 2 counts for size 2 itemsets: 80

{0: 0, 1: 2, 2: 0, 3: 2, 4: 2, 5: 3, 6: 2, 7: 1, 8: 1, 9: 0, 10: 0, 11: 0, 12: 0, 13: 0, 14: 0, 15: 0, 16: 0, 17: 0, 18: 0, 19: 0}

bitmap 2 size: 20

memory for candidates counts of size 2 : 36

memory for hash table 1 counts for size 3 itemsets: 80

{0: 0, 1: 0, 2: 0, 3: 0, 4: 1, 5: 0, 6: 2, 7: 1, 8: 2, 9: 2, 10: 0, 11: 0, 12: 0, 13: 0, 14: 0, 15: 0, 16: 0, 17: 0, 18: 0, 19: 0}

Frequent itemsets of size 2 : [['a', 'e'], ['d', 'e']]

memory for frequent itemsets of size 2 : 24

bitmap 1 size: 20

memory for hash table 2 counts for size 3 itemsets: 80

{0: 0, 1: 0, 2: 0, 3: 0, 4: 1, 5: 0, 6: 2, 7: 1, 8: 2, 9: 2, 10: 0, 11: 0, 12: 0, 13: 0, 14: 0, 15: 0, 16: 0, 17: 0, 18: 0, 19: 0}

bitmap 2 size: 20

memory for candidates counts of size 3 : 0

memory for hash table 1 counts for size 4 itemsets: 80

{0: 0, 1: 0, 2: 0, 3: 0, 4: 0, 5: 0, 6: 0, 7: 0, 8: 0, 9: 1, 10: 1, 11: 0, 12: 0, 13: 0, 14: 0, 15: 0, 16: 0, 17: 0, 18: 0, 19: 0}
