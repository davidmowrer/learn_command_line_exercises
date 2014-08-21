Do More
Unix: Make a directory, change to it, and then make a file in it. Then change
one level up and run the rmdir command in this directory.  directory.
You should get an error. Try to understand why you got this error. 

workspace/davinci_coders_t2_2014/learn_command_line_exercises/chapter_9/tmp
mkdir testdir
cd testdir
touch myfile.txt
cd ..
rmdir testdir
Error: Directory is not empty.  The directory testdir has an empty file in it,
myfile.  You can't delete(remove) a directory that has content in it like a file
or another directory.

Alternative "english" ways of asking you to create a file:

Can you touch blah.txt?
cd tmp
touch blah.txt
This creates an empty file blah.txt in the tmp directory.

Let's create foo.txt?
cd tmp
touch foo.txt
This creates an empty file foo.txt in the tmp directory.
