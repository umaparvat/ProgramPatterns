Rolling Hash pattern -> leetcode
1.	https://leetcode.com/problems/longest-duplicate-substring/
    https://leetcode.com/problems/longest-repeating-substring/
    https://leetcode.com/problems/longest-common-subpath/ ( here rolling hash for arrays of list)

         Binary Search+ Rabin Karb ( Here string has to be sliced as 1, 2,3, 4…len(s) ) the efficient way to use binary search for slice length and find out whether hash exists for the length

2.	https://leetcode.com/problems/longest-repeating-substring/
    https://leetcode.com/problems/longest-happy-prefix/
       Two rolling hash from front and back . and check front hash matched with back hash.

3.	https://leetcode.com/problems/check-if-a-string-contains-all-binary-codes-of-size-k/
       Rolling hash with bits. Here we need to left shift the hash and unset right most significant bit then add the new number ( hash<<1&all_one|num[i])

4.	https://leetcode.com/problems/strings-differ-by-one-character/
        use rolling hash on a set of strings to check whether their hashes match

5.	https://leetcode.com/problems/number-of-distinct-substrings-in-a-string/
    https://leetcode.com/problems/distinct-echo-substrings/ 
           count distinct length substring
  	
7.	https://leetcode.com/problems/maximum-product-of-the-length-of-two-palindromic-substrings/
           Manchester algorithm
  	
9.	https://leetcode.com/problems/unique-substrings-with-equal-digit-frequency/
    https://leetcode.com/problems/k-divisible-elements-subarrays/ 
        counter +rolling hash
  	
10.	https://leetcode.com/problems/find-substring-with-given-hash-value/
          rolling hash from reverse string
   	
11.	https://leetcode.com/problems/sum-of-scores-of-built-strings/
      Z-algorithm
   	
12.	https://leetcode.com/problems/repeated-dna-sequences/ 
        Normal Rabin karp algo
