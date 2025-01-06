<h1>Import & Parse a Text File Using Python</h1>

<h2>Description</h2>
Security logs are often stored in text files. To analyze the security logs in these files, security analysts have to import and parse these files. Python has some functions that come in handy for these tasks, allowing analysts to efficiently access information from text files. <br/>
<br/>
In this lab, you'll practice using functions and other syntax in Python to import and parse text files.
<br />

<h2>Scenario</h2>
In this lab, you're working as a security analyst. You're responsible for preparing a security log file for analysis and creating a text file with IP addresses that are allowed to access restricted information.
<br />

<h2>Languages and Utilities Used</h2>

- <b>Python</b>

<h2>Environments Used </h2>

- <b>Python Jupyter Notebook</b>

<h2>Program Walk-Through:</h2>

<h3>Task 1</h3>

<p>
In this task, you'll import a security log text file and store it as a string to prepare it for analysis.

In Python, a with statement is often used in file handling to open a file and then automatically close the file after reading it.

You're given a variable named import_file that contains the name of the log file that you want to import. Start by writing the first line of the with statement in the following code cell. Use the open() function, setting the second parameter to "r". Note that running this code will produce an error because it will only contain the first line of the with statement; you'll complete this with statement in the task after this.
</p>

<h3>Task 2</h3>

<p>
Now, you'll use the .read() method to read the imported file, and you'll store the result in a variable named text. Afterwards, display the text and explore what it contains by running the cell.
</p>

<h3>Task 3</h3>

<p>
The output in the previous step is one big string. In this task, you'll explore how you can split the string that contains the entire imported log file into a list of strings, one string per line.

Use the .split() method to perform this split and then display the result. Be sure to replace the ### YOUR CODE HERE ### with your own code before you run the following cell.

Note that displaying .split() doesn’t change what is stored in the text variable. Variable reassignment would be necessary if you want to store the result after splitting.
</p>

<h3>Task 4</h3>

<p>

</p>

<h3>Task 2</h3>

<p>

</p>

<h3>Task 2</h3>

<p>

</p>

<h3>Task 2</h3>

<p>

</p>

<h3>Task 2</h3>

<p>

</p>

<h3>Task 2</h3>

<p>

</p>

<h3>Task 2</h3>

<p>

</p>






