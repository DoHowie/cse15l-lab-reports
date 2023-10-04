**for the command cd**

![Image](cd_examples.png)
![Image](cd_examples2.png)

```
1. Share an example of using the command with no arguments.
In the screenshot, the working directory starts with the home directory. If we use the command cd with no arguments,
meaning if we just type "cd" into the command line, it will do nothing and stays at the home directory, this is not
an error because there is nothing to change for the directory, you are in the home directory which is like the base
of the directory. However if we are in other directory, then using the command cd with no arguments will return back
to the home directory. For instance, after we change directory into lecture1, we type cd to get back to the home
directory.
```
```
2. Share an example of using the command with a path to a directory as an argument.
Using the example from above, start with the home directory, when I type "cd /home/lecture1", which "/home/lecvture1"
is a path to the "lecture1" directory, the terminal directed me to the lecture1 directory, which contains Hello.class,
Hello.java, messages directory, and README. This is not an error.
```
```
3. Share an Example of using the command with a path to a file as an argument.
Again, using the same screenshot for the cd example, when I type "cd Hello.java" while in the lecture1 directory,
which means I'm trying to change my directory to this java file called Hello, the terminal return an error of
"bash: cd: Hello.java: Not a directory" because Hello.java is not a directory, so cd, which stands for change
directory, won't work.
```
**for the command ls**
![Image](ls_examples.png)

```
1. Share an example of using the command with no arguments.
In the example provided on the top, the working directory starts with the home directory. If we use the command ls
with no arguments, meaning if we just type "ls" into the command prompt, the terminal will output all the elements
in the current directory. In this case of the home directory, the only element is the directory lecture1. This is not
an error.
```
```
2. Share an example of using the command with a path to a directory as an argument.
When I type "ls /home/lecture1" into the command prompt at the starting directory as the home directory, which
"/home/lecture1" is the path to the "lecture1" directory, the terminal will output all the elements from that
directory, which in this case the directory "lecture1" have Hello.class, Hello.java, messages directory, and
README. This is not an error.
```
```
3. Share an Example of using the command with a path to a file as an argument.
The starting directory is the lecture1 directory, if I type in "ls Hello.java", "ls Hello.class", "ls README",
which all of them are files, then it will just repeat the name of the file. The terminal did not return an error
to this problem because the only elements in these files that the terminal can "list" is the file itself.
ls stands for list by the way.
```
**for the command cat**
![Image](cat_examples1.png)
![Image](cat_examples2.png)
```
1. Share an example of using the command with no arguments.
The starting directory of the first picture is the messages directory which contains lot of txt files. If I
just use cat command with no arguments, it will wait for an user input, so that's why in the picture after
the cat command there are couple newlines, it's the terminal waiting for the user to enter something. The
cat command will simply repeat what you have input in the user input. The cat command without arguments
is not an error.
```
```
2. Share an example of using the command with a path to a directory as an argument.
For presenting this example, look at picture one the 7th line that contains code (I don't really know how
much whitespace/ newlines there are). The starting directory of this example is the home directory. By
using cat command onto the lecture1 directory, being "cat lecture1". the terminal returns an message,
"cat: lecture1: Is a directory". The cat command here simply prints out the directory name that it
read. And this is not an error.
```
```
3. Share an Example of using the command with a path to a file as an argument.
Please refer to both picture 1 and picture 2 for this example. For picture 1, the starting directory of
the example is the message directory, which contains a lot of txt files. By running "cat en-us.txt" for
example, it will print out the content inside en-us.txt, being "Hello World!".
However for picture 2, the starting directory is the lecture1 directory, which contains other types of
files, by entering "cat Hello.java", it will also just prints out the code inside Hello.java.
So for files that contain codes inside, the cat command will prints the code for the user to preview.
```
