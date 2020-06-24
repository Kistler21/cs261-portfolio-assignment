# cs261-porfolio-project
The purpose of the Portfolio Assignment is to showcase your programming skills to potential employers and colleagues. This is the only assignment in this course that is allowed to be publicly posted online (e.g. GitHub, personal website, etc. …). While this is a great opportunity to publicize your work, it is not required that you post the assignment online.

There are two parts to this assignment. In the first part, you will complete the implementation of a hash map. In the second part, you will implement a concordance program. A concordance counts the number of occurrences of each word in a document, i.e. a word counter.  Your word counter will rely on your hash map implementation. For this assignment, you are allowed to use the string library. 

## Part 1: Hash Map
First, complete the hash map implementation by using the skeleton code provided below. This hash map uses a hash table of buckets, each containing a linked list of hash links. Each hash link stores the key-value pair (string and integer in this case) and a pointer to the next link in the list. See the Programming Assignment 5 Guidelines for additional method descriptions. Use the provided unit tests to help debug any failing test cases on GradeScope. You are encouraged to write additional unit tests, however, you are not permitted to share any additional tests with other students. 

## Part 2: Concordance
Once you have your hash map working properly, you can start to build your concordance program. Word_count.py takes an input document, computes the number of times each word was used in the document, and returns the top X words and associated counts. We have provided you with the code to take an input document and read in each word. From there, you must store each word in a hash table and keep track of how many times the word appears.

Top_words() should return a list of tuples: [(top word, count), (next top word, count)]. See the skeleton code and  input document below to get started. 

Use the provided unit tests to help debug any failing test cases on GradeScope.
