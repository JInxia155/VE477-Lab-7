Download Link : https://programming.engineering/product/ve477-lab-7/

# VE477-Lab-7
VE477 Lab 7

Unless specified otherwise, all the programs are expected to be completed in Python or O’caml.

In this lab we want to compare three search algorithms. Let A be an array of size n and k be a value to find in A.

    The first algorithm, RandomSearch, consists in randomly searching A for k. One simply selects a random index i and test if A[i ] = k. If true, then the algorithm returns i and otherwise randomly chooses a new i until either all the indices have been explored or k has been found. In this algorithm a same index can be generated more than once.

        Implement RandomSearch.

        Determine the average number of indices that are picked if:

            There is no index i such that A[i ] = k.

            There is exactly one index i such that A[i ] = k.

            There is more than one index i such that A[i ] = k.

    The second algorithm, LinearSearch, consists in performing a linear search on A, i.e. testing if k is in A[1], · · · , A[n], and either return i , the index where k is stored in A, or exit if k is not found.

        Implement LinearSearch.

        Determine the average-case and worst-case running times if:

            There is no index i such that A[i ] = k.

            There is exactly one index i such that A[i ] = k.

            There is more than one index i such that A[i ] = k.

    The third algorithm, ScrambleSearch, consists in randomly permuting A into A′ and then run the

LinearSearch algorithm on A′ .

        Implement ScrambleSearch.

        Determine average-case and worst-case running times if:

            There is no index i such that A[i ] = k.

            There is exactly one index i such that A[i ] = k.

            There is more than one index i such that A[i ] = k.

    From the previous complexities which algorithm seems to be the best.

    Generate A, a random array of one million elements, and time each of the previous algorithms searching a random k on it. Repeat the process one thousand times, keeping track of the previous runs.

        Which algorithm performs best in practice?

        Discuss the result by comparing to your expected result in item 4.

