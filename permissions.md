# permissions and chmod

'chmod' changes the permissons on a file or folder. The three numbers stand for owner, group and others, in that order. Each number is made by adding read(4), write(3), and execute(1).
## chmod 644

"chmod 644 notes.txt'

6 = 4 + 2, so the ownder can read and write. 4 = read only for the group, and 4 = read only for others. The result is 'rw-r--r--'. This is a normal setting for a text file: you can edit it, everyone else can only read it.

## chmod 755

'chmod 755 hello.py'

7 = 4 + 2 + 1, so the owner can read, wrtie and execute. 5 = 4 + 1, so the group and others can read and execute, but not write the result is 'rwxr-xr-x'. This is a normal setting for a script: you can change and run it, everyone else can run it but not change it.
