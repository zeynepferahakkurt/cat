# cat
	
cat is one of the most frequently used commands on Unix-like operating systems. It has three related functions with regard to text files: displaying them, combining copies of them and creating new ones.

cat's general syntax is

  cat [options] [filenames] [-] [filenames]

Read/write without option
-----------------------------------------------------
Example:
1.reads the file1.txt-------cat file1.txt

cat file1.txt > file2.txt		//copy file1.txt to file2.txt

cat file1.txt ">"			//ERROR

cat ">" file1.txt			//takes input and write it in file1.txt
  
Read/write with option
-----------------------------------------------------

option 1 : -b puts a number every line with characters.

option 2 : -n puts a number every line.

option 3 : -h explain how to use this program

Example:

cat -b file1.txt file2.txt	

cat -b ">" file1.txt    	//takes an input and write it with numbers in file1.txt

cat -n file1.txt ">" file2.txt

cat -h .


 
