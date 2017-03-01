# commandLineTools
A laundry list of useful command line tools and usage

1. clush - cluster shell
   Cluster shell is a vital tool for simultaneously executing bash commands on
   several configured server machines.

   Configuration


   Example usage -
   1. clush -l root -w lnode1,lnode2,cluster-[1-8] hostname
      -l --> supplies the user to run the command as
      -w --> supplies the nodes to run the command
      hostname --> command to be executed

1. pwd - print working directory

2. hostname - my computers network name

3. mkdir - make directory
   mkdir -p /tmp/hello/world
   --p --> this creates immediate directories as required. In this case it creates hello before creating world as well.

4. cd - change directory

5. ls - list directory
   -a --> display filenames starting with "."
   -l --> list filenames in long format with size and privileges
   -h --> print sizes in megabytes, gigabytes etc

6. rmdir - remove directory

7. pushd - push directory

8. popd - pop directory

9. cp - copy a file or directory

10. mv - move a file or directory

11. less - page through a file
    Forward Search
    / --> search for a pattern in the file and take you to the next occurrence
    n --> next match forward
    N --> previous match backward

    Backward Search
    ? --> search for a pattern in the file and take you to the previous occurrence
    n --> next match backward
    N --> previous match in the forward direction

    Screen Navigation
    ctrl + f --> forward one window
    ctrl + b --> backward one window
    ctrl + d --> forward half window
    ctrl + u --> backward half window

    Line Navigation
    j --> one line forward
    10j --> 10 lines forward
    k --> one line backward
    10K --> 10 lines backward

    Other Navigation
    G --> go to the end of the file
    g --> go to the start of the file


12. cat - print the whole file

13. xargs - execute arguments

14. find - find files

15. grep - find things inside files
