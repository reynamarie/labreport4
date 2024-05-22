# CSE 15L Lab Report 4 - Vim 

## Step 4

![Image](loginieng6.jpg)

Keys pressed: `ssh<space>rmaharaj@ieng6.ucsd.edu<enter>`
The  command  `ssh` allows me to log into the remote server ieng6.ucsd.edu using my username after pressing `<enter>`. I do this to edit my files in the command lines on the ieng6 server. 


## Step 5
![Image](ieng6clone.jpg)

Keys pressed: `git<space>clone<space>git@github.com:ucsd-cse15l-s24/lab7.git<enter>`
This command clones the lab7 repository that I forked from GitHub into ieng6 server.  The `<space>` key specifies that `<clone>` is an argument of `<git>`. The other `<space>` key  separates the previous commands from the repository URL so that it is recognized as an argument. The `<enter>` executes  the command, which produces the effect of me having access to edit and work on the files in lab7 in the command line. 


## Step 6
![Image](iengfail.jpg)

Keys pressed: `bash<space>test.sh<enter>`
The command bash<space>test.sh<enter> runs the bash script `test.sh`. The effect of this is to compile and run the tests. This shows that two tests ran and one of them failed. The `<space>` key  is used to separate the different parts of the command line.  The `<enter>` key is used to run the tests.


## Step 7
![Image](newpasstest.jpg)

Keys pressed: `vim<space>ListExamples.java<enter>``<i><k><k><k><k><k><k><l><l><l><l><l><l><l><delete>2` `:wq!<enter>`
The  `vim<space>ListExamples.java<enter>` command allows us to edit the code in `ListExamples.java` in vim, using just the command line in the terminal. 
This command fixes the bug in the `merge function` that was given to us in step 6 by changing the code to increment by `index2` instead of by `index1`. This effect was having the code increment correctly so that our test pass. The effect of `<i>` in vim is so that we are in insert mode and can edit the code. The effect of `<k>` in vim allows our cursor to go up one line with each `<k>` key pressed. The effect of `<l>` in vim allows our cursor to go right. Then I used the key `<delete>` and then pressed `2` so that the code correctly incremented.  Since the bug is fixed, I typed `:wq!` to save the changes we made and quit. 

## Step 8
![Image](logieng6.jpg)
Keys pressed: `bash<space>test.sh<enter>`
This command runs my tests again. This time the tests pass. The `<space>` key separates `bash` from its argument. The `<enter>` key executes the tests. 

## Step 9
![Image](commitandpush.jpg)
Keys pressed: `git<space>add<space>.` `git<space>commit<space>-m<space>" hi there "` `git<space>push` 
The `git<space>add<space>.` command prepares the files to be altered with the following `commit` command. The command `git<space>commit<space>-m<space>` commits my change to the working directory, with my new message, hi there. The `git push` command updates via pushing the command line message to the local repository and then updates it to the remote repository, which will allow for these changes to be seen. The `<space>` keys separate all of the other parts of the command line. The effect of using the `<enter>` key is that it executes the command.  

