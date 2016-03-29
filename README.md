# Reverse-Dictionary-Using-Hadoop-MapReduce
To retrieve the related words when a description or meaning is given by using Hadoop – Map Reduce.
Unlike a traditional forward dictionary, which maps from words to their definitions, a reverse dictionary takes a user input phrase describing the desired concept, and returns a set of candidate words that satisfy the input phrase.
Reverse dictionary system is based on the notion that a phrase that conceptually describes a word should resemble the word’s actual definition, if not matching the exact words, then at least conceptually similar.
HDFS is designed to store very large files across machines in a large cluster.

Data file Format:
  Dictionary file must in below format
      Word-Meaning of the word
