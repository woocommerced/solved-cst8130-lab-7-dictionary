Download Link: https://assignmentchef.com/product/solved-cst8130-lab-7-dictionary
<br>
In this lab,  you will write a program which builds a tree “dictionary” of words that were found in a piece of text and keep track of how many times each of the words occurred.

<strong><em>Basic Requirements:</em></strong>

<ol>

 <li>You must have a menu in your main method with the following options:</li>

</ol>

<ul>

 <li>Reset the tree to empty</li>

 <li>Read a string of text from the keyboard and add to the dictionary (**optional)</li>

 <li>Read text from a file add to the dictionary (**optional)</li>

 <li>Search for a word and show how many times it occurred in the text</li>

 <li>Display the number of nodes in the dictionary</li>

 <li>Exit</li>

</ul>

<strong><em>**  you must implement either from file or from keyboard – bonus marks if you do both!!</em></strong>

<ol start="2">

 <li><strong>You must use the collection class TreeMap to implement this assignment</strong>. A description of the  methods available in that class can be found in the Java documentation.   Efficient use of the class will factor in the assignment marking.</li>

 <li>Hint: you should put all the “words” that you read into either uppercase or lowercase to make sure that the words “there” and “There” count as the same.   You should also remove non-alphabetic characters using the String method word.replaceAll(“^\s”,””); which replaces basically all non-characters with nothing.</li>

 <li>I have given you a .txt file of the book Oliver Twist called oliver.txt. I have used that in my sample output.</li>

</ol>




<strong><em>Sample Output:</em></strong>

Enter 1 to clear dictionary,

2 to add text from keyboard,

3 to add text from a file,

4 to search for a word count,

5 to display number of nodes,

6 to quit

3




Enter name of file to process: c:oliver.txt




Enter 1 to clear dictionary,

2 to add text from keyboard,

3 to add text from a file,

4 to search for a word count,

5 to display number of nodes,

6 to quit

4

Enter word to search for:

the

the occurs 9635 times




Enter 1 to clear dictionary,

2 to add text from keyboard,

3 to add text from a file,

4 to search for a word count,

5 to display number of nodes,

6 to quit

4

Enter word to search for:

oliver

oliver occurs 747 times




Enter 1 to clear dictionary,

2 to add text from keyboard,

3 to add text from a file,

4 to search for a word count,

5 to display number of nodes,

6 to quit

4

Enter word to search for:

twist

twist occurs 57 times




Enter 1 to clear dictionary,

2 to add text from keyboard,

3 to add text from a file,

4 to search for a word count,

5 to display number of nodes,

6 to quit

5

There are 11670 nodes


