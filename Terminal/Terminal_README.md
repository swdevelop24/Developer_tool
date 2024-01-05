## Useful Course for basic Terminal Commands 
 - [Udemy :Dr. Angela Yu Web Development Bootcamp] - https://www.udemy.com/course/the-complete-web-development-bootcamp/


 ## Summary of the Dr. Angela Yu course - : Command Line section

 **Navigating directories and Files**

- ~(tilda : user/root directory)
- ls (list)
- cd(change directory)
- up/down button (cycle back/forward)
- cd .. (parent folder- takes back one level : ex) drag & drop folder to terminal
- at the front/end of the current terminal line :
  ⇒ Ctrl +A / Ctrl +E (For specific position: alt → monitor shows + ⇒ click to that position /) 
- Ctrl + U (clear)

**Creating, Opening, and Removing Files**

- mkdir : make directory
- touch  apple.txt : make a text file
- start/code apple.txt : open a text file using a default app
- rm text1.txt : remove a text1 file
- pwd: print working directory
- rm * : remove all the files inside the current directory
- check the current directory before removing files/directory
- rm -r  Angela : remove all the folder and files inside the Angela folder
- cf) serverfault websites (network admin)


** additional command from the following resources
 ## Useful Link for basic Terminal Commands 

 - man (manual page for linux command)
 - mv lab1/original lab2/original
 - cp lab1/original lab2/duplicate 
 - cat [file]

- [UC Berkeley 61B course - terminal part] - https://fa23.datastructur.es/materials/lab/lab01/terminal.html
- [kinsta blog - most used linux command ] - https://kinsta.com/blog/linux-commands/
- [Stack Exchange] - https://unix.stackexchange.com/questions/395182/delete-the-parent-folder-keeping-all-content

 - $ cp -Rp . ../;cd ../;rm -rf nested
> cp -Rp . ../ - This will copy all files including directory, nested directory and hidden files. Where,
>-R flag is used for "copy directories recursively"
>-p is to "preserve the specified attributes (default: mode,ownership,timestamps), if possible additional attributes: context, links, xattr, all",
>. is for indicating of current directory as source
>.. indicating as parent directory as destination.
> cd ../ - This will move you from current to parent directory
> rm -rf nested - This will remove all the files including directories, nested directories and hidden files.












