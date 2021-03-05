# cmdchallenge
One-line shell challenges

Q1: Your first challenge is to print "hello world" on the terminal in a single command.

Hint: There are many ways to print text on the command line, one way is with the 'echo' command. Try it below and good luck!
A1:  echo "hello world" 
O1: hello world

Q2: Print the current working directory.
A2: pwd
O2: /var/challenges/current_working_directory

Q3: List names of all the files in the current directory, one file per line.
A3: ls
O3: 01-take.txt02-the.txt03-command.txt04-challenge.txt

Q4: There is a file named access.log in the current directory. Print the contents.
A4: cat access.log
O4: 163.56.115.58 - - [09/Jan/2017:22:29:57 +0100] "GET /posts/2/display HTTP/1.0" 200 324075.113.188.234 - - [09/Jan/2017:22:30:43 +0100] "GET /posts/foo?appID=xxxx HTTP/1.0" 200 111669.16.40.148 - - [09/Jan/2017:22:34:33 +0100] "GET /pages/create HTTP/1.0" 500 3471225.219.54.140 - - [09/Jan/2017:22:35:30 +0100] "GET /posts/foo?appID=xxxx HTTP/1.0" 500 2477207.243.19.2 - - [09/Jan/2017:22:38:03 +0100] "GET /bar/create HTTP/1.0" 200 1116199.37.62.156 - - [09/Jan/2017:22:42:18 +0100] "GET /posts/1/display HTTP/1.0" 200 247755.74.240.123 - - [09/Jan/2017:22:44:25 +0100] "POST /posts/1/display HTTP/1.0" 200 3471251.111.109.143 - - [09/Jan/2017:22:49:02 +0100] "GET /posts/foo?appID=xxxx HTTP/1.0" 200 2477101.163.230.250 - - [09/Jan/2017:22:52:31 +0100] "DELETE /posts/2/display HTTP/1.0" 404 2477200.19.168.148 - - [09/Jan/2017:22:57:11 +0100] "GET /posts/foo?appID=xxxx HTTP/1.0" 200 3471

Q5: Print the last 5 lines of "access.log".
A5: tail -5 access.log
O5: 199.37.62.156 - - [09/Jan/2017:22:42:18 +0100] "GET /posts/1/display HTTP/1.0" 200 247755.74.240.123 - - [09/Jan/2017:22:44:25 +0100] "POST /posts/1/display HTTP/1.0" 200 3471251.111.109.143 - - [09/Jan/2017:22:49:02 +0100] "GET /posts/foo?appID=xxxx HTTP/1.0" 200 2477101.163.230.250 - - [09/Jan/2017:22:52:31 +0100] "DELETE /posts/2/display HTTP/1.0" 404 2477200.19.168.148 - - [09/Jan/2017:22:57:11 +0100] "GET /posts/foo?appID=xxxx HTTP/1.0" 200 3471

Q6: Create an empty file named take-the-command-challenge in the current working directory.
A6: touch take-the-command-challenge

Q7: Create a directory named tmp/files in the current working directory
A7: mkdir tmp && cd tmp && mkdir files 

Q8: Copy the file named take-the-command-challenge to the directory tmp/files
A8: cp take-the-command-challenge tmp/files 

Q9: Move the file named take-the-command-challenge to the directory tmp/files
A9: mv take-the-command-challenge tmp/files

