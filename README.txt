Downloaded wordshop.py from what we covered back when I was learning Python. 

Imported re

Define getWordsFromFile module to fit the importing of the file and the first two for loops:
Create words as an empty list
Open/import Story.txt to be read as iFile and set all the words in the file as uppercase for ease of use with finding occurences.
Create for loop to loop through the lines in the file,
then add an a for loop inside the first to loop through each individual word in the line and strip any special charcters from the story.
Close iFile at the bottom of the last for loop, dedented once.
Return words from the file.


Define main module:
Create usedWords as an empty list.
Open new oFile as WorkShopList.txt and set to write.
Write the header "Word" and "Number of Occurences" into the file.
Create a separator between the header and the occurences with dashes (-).

Create wordList equal to the getWordsFromFile module
Sort wordList

Make a for loop to find words in wordList
If statement that finds if a word had been used.  If so, then it won't precede and will continue to the top of the loop
else it will append it to the used words
Write the individual words and their matching count number to oFile
Write to go to newline after every input
Close oFile

Run main to start the program


*TROUBLESHOOTING:
Had trouble figuring out how to get the words to only occur once.
Asked a friend for some helpful knowledge and he/she/it delivered
SOLVED *thumbs up emoji*
