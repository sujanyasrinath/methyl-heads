# methyl-heads

# to check the speed of the algorithm

'''if __name__=='__main__':
    from timeit import Timer
     t = Timer("test()", "from __main__ import test")
     print t.timeit()'''
    
# to check the time complexity of the algorithm

# you can determine the time complexity by analyzing the program’s statements

Big O notation is a framework to analyze and compare algorithms.
Amount of work the CPU has to do (time complexity) as the input size grows (towards infinity).
Big O = Big Order function. Drop constants and lower order terms. E.g. O(3*n^2 + 10n + 10) becomes O(n^2).
Big O notation cares about the worst-case scenario. E.g., when you want to sort and elements in the array are in reverse order for some sorting algorithms.
For instance, if you have a function that takes an array as an input, if you increase the number of elements in the collection, you still perform the same operations; you have a constant runtime. On the other hand, if the CPU’s work grows proportionally to the input array size, you have a linear runtime O(n).

- Wu Manber Algorithm: complexity of O(tk) where t is the length of the text string and k the number of errors allowed
- Hidden Markov Model: O(LxLz), where Lx and Lz are the lengths of x and z where x and z are the lengths of the dna sequences to be swequenced
- Iterative Algorithm: These algorithms have time requirements that are at worst O(N3) as they involve at most 2N2 profile alignments each of which is O(N). However in practice the complexity is often much lower.
- Consistency algorithm: O(k.L2)
--k is the number of sequences.
--L is the length of the longest sequence
