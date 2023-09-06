## Lab 01

- Name: Emmanuel Gutierrez Rivera
- Email: gutierrezrivera.2@wright.edu

## Part 1 Answers

1.
    PROMPT: Create a directory called DirA
    
    ANSWER: 'mkdir DirA'
    
    
2.
    PROMPT: Create a directory called Dir B
    
    ANSWER: 'mkdir Dir B'


3.
    QUESTION: How do you go into the Dir B directory?
    
    ANSWER: You can't, the command 'mkdir Dir B' created two different directories 'Dir' and 'B'. You would need to navigate to both directories separately. 'cd Dir' or 'cd B'.


4.
    QUESTION: Which of these directories, DirA or Dir B uses a better naming convention, and why?
    
    ANSWER: The better convention is 'DirA' because if the intention is to just create ONE directory to put data (or anything else) it is better to not use a space when creating a new directory, so it does not create 2 directories when you only wanted one.


5.
    PROMPT: Rename Dir B to DirB
    
    ANSWER: I used the following commands 'mv "Dir B" DirB', and i kept getting the error of "mv: rename Dir B to DirB: No such file or directory"
        so I decided to rename "Dir" to "DirB" and just delete the directory "B" with the following commands: 
            'mv "Dir" DirB' 
            'rm -r B'
    

## Part 2 Answers

1.
    PROMPT: In DirA, create a file called test.txt
    
    ANSWER: 'cd DirA' -> touch test.txt
    
    
2. File contents:
    COMMANDS: 'vim test.txt'
    
```
**file contents here**
    One line of text
    Two lines of text
    Three lines of text
    ~
    ~ 
```

## Part 3 Answers

1.
    PROMPT: Make a copy of test.txt inside DirA named .hiddentext.txt
    
    ANSWER: 'cp test.txt .hiddentext.txt'
    
2. To see '.hiddentext.txt' file, i used the following commands: 'vim .hiddentext.text' or 'ls -a'  '

## Part 4 Answers

1. SSH command to sign in to your AWS instance:

```
ssh-keygen
Downloads
cd Downloads
cp labsuser.pem ~/.ssh/
ssh -i labsuser.pem ubuntu@54.209.213.248
```

## Part 5 Answers

1. Command to clone your GitHub repository:

```
git clone https://github.com/EmmanuelGR02/ceg2350.git
```
