# 50.005 2022 Programming Assignment 1

Type your answer in the spaces provided in each file, labeled as `BEGIN ANSWER`. 
1.  <span style="color:#f7007f;"><b>DO NOT</b></span> modify any `makefile`
2.  <span style="color:#f7007f;"><b>DO NOT</b></span> create more scripts other than what's given in the starter code
3.  <span style="color:#f7007f;"><b>DO NOT</b></span> modify any interface (keep original functions as-is)
4.  <span style="color:#f7007f;"><b>DO NOT</b></span> print <span style="color:#f7007f;"><b>anything</b></span> to the console, other than the provided print statements. Any print statements you used for debugging must be deleted. 

## Build and run
```
make
./cseshell
```

## Test results
Use testing branch for tests.

### test_readline_stdin
```
test 123
The fetched line is : test 123
```

### test_tokenize_line_stdin
```
a b c d e
The fetched line is : a b c d e
 
found a
found b
found c
found d
found e
```

### test_process_command
```
Shell Run successful. Running now: 
find .txt         
The fetched line is : find .txt
 
The first token is find 
The second token is .txt 
Current working dir: /home/ruien/pa1
./files/intermediate.txt
./files/combined.txt
./files/lorem_ipsum.txt
./files/file1.txt
./files/file2.txt
./files/oneline.txt
./files/paragraph.txt
```