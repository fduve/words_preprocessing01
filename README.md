# words_preprocessing01
For the next code's improvements, it is on mind that it will take the word's frequencies and perform some preliminar processing to get some first insights about the corpus to work.

v0.01: After uploading the first version, noticed that forgot to delete the line for importing a custom library, so, in order for it to work,
just delete the custom import line.

v0.10: Implements the use of pandas and numpy to get an array with frequencies, and optionally, the name of the word which is getting the frequency of, useful for a first approach to data examination.


The scripts works by selecting a text file, both in the same folder. If the text file fulfill the following requierement: (1) All lines are
separated from each other by a ('\n') or a jump line, then it is ready to work.
The script is going to ask you for a file's name, write it. Then it is going to work and pre-process the text inside.


