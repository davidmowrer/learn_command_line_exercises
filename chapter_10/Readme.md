Alternative "english" ways of asking you to copy a file:

1. Can you copy the foo.txt file to slash temp? (Create foo.txt first...)
 touch foo.txt
 cp foo.txt ~/tmp

2. Can you copy .bash_profile in your home directory to the current directory?
  cp .bash_profile ~/workspace
  
Do More:
  
1. Use the cp -r command to copy more directories with files in them.

  mkdir dirfiles
  cd dirfiles
  touch text1.txt
  touch text2.txt
  cd ..
  cp -r dirfiles ~/tmp

2. Copy a file to your home directory or desktop.

  touch test3.txt
  cp test3.txt ~/desktop
