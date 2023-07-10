# AnagramFinder 

Anagram Finder Using Binary Search Trees in Java


Introduction
An anagram is a word made by rearranging the letters of another word. For instance, the words "dearer", "reader", "reared", and "reread" are anagrams of each other, as are "present", "repents", and "serpent". The objective of this project is to develop a Java program that identifies all sets of anagrams from a text file of English words. The algorithm behind this program leverages binary search trees, ensuring efficient processing times even for large text files.

For instance, Leo Tolstoy’s War and Peace, one of the longest published novels ever written, contains over a thousand pages and more than half a million words. A program using this algorithm can read the text of this novel in about half a second, finding 793 sets of anagrams.

Theory
Problem with Obvious Algorithms
Comparing each word with every other word to test for anagrams is inefficient and time-consuming. This would require O(N²) time, which is too slow for large files. Furthermore, generating all possible rearrangements of one word and then testing if any of them are equal to the other word also takes an impractical amount of time. To speed up this process, we use a variant of the string comparison algorithm and binary search trees.
