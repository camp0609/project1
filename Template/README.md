Add your project details as mentioned in Section Deliverables.
The purpose of my program is to get the word count for a given file and output
the count to a text file.

The code company can be compiled using the Makefile in Template.

The program first forks and creates child processes that execute the mapper.
The mapper will take a chunk of text and count how many times the word appears
and store that in nested linked list, and then outputs each word and the number
of times it appear into a text file. The mapreduce will wait for the mapper
forks to finish executing. Mapreduce then shuffles the partitioned files for the
reducer. Mapreduce then forks and creates reducer processes that will read from
the given text files and get the word count, outputting the final word count
into a text file. Mapreduce waits for reducer children to finishing executing
and then the program is done.

Collin Campbell camp0609
Clara Huang  huan2089
Hunter Bahl bahlx038

Mapreduce -all contributed 
mapper -all contributed
reducer -all contributed
