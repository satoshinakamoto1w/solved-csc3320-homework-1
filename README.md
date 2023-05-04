Download Link: https://assignmentchef.com/product/solved-csc3320-homework-1
<br>
<span class="kksr-muted">Rate this product</span>

PART 1

Answer the following questions briefly. Provide clear and succinct reasoning.

Points per question = 5

1. Tell the differences between Unix and Linux. Then please list some operating systems (at least three) which belong to Unix but not Linux.

2. What is the pipe mechanism in UNIX? And show one command using pipe and explain how the pipe works in it?

3. In a Linux system, you can issue the command ls / to check the sub directories under root. Please describe the meanings of directory /bin, /dev, /boot, /usr, /etc, /mnt, /sbin, /var separately. For example, you can say that /bin contains binary executable files.

4. What is the meaning of Multitask and Multi-user in a Unix system?

5. What does -rwxr-xr-x mean in terms of permissions for a file? What is the exact unix command (with the octal representation) for changing the permissions to this setting?

6. In class, you have learned the meaning of read, write and execute permission for regular files. However, these permissions are also applied to directories. So please describe the meaning of read, write, and execute permission for directory.

Part II-a

Regular ExpressionFind outcomes for each given basic/extended regular expression (maybe multiple correct answers)

Points per question: 2.5

Note: 7) to 10) are basic regexes; Note: 11) to 18) are extended regexes. 7) ‘a[ab]*a’8) ‘a(bc)?’9) ‘.[ind]*’

10) ‘[a-z]+[a-z]’11) ‘[a-z] (+[a-z])+’

12) ‘a.[bc]+’13) ‘a.[0-9]’14) ‘[a-z]+[.?!]’15) ‘[a-z]+[.?!]s*[A-Z]’16) ‘(very )+(cool )?(good|bad) weather’ 17) ‘-?[0-9]+’18) ‘-?[0-9]*.?[0-9]*’

Part II-b

Example:‘ab+a’ (extended regex)

Answer: aba , abba ; Pattern : The matched string should begin and end with ‘a’ and ‘b’ occurs at least once between leading and ending ‘a’)

Regular ExpressionWrite down the extended regular expression for following questions. E.g. Social security number in the format of 999-99-9999. Answer: [0- 9]{3}-[0-9]{2}-[0-9]{4}

Points per question: 5

19) Valid URL beginning with “http://” and ending with “.edu” (e.g. http://cs.gsu.edu, http://gsu.edu)

20) Non-negative integers. (e.g. 0, +1, 3320)

21) A valid absolute pathname in Unix (e.g. /home/ylong4, /test/try.c)

22) Identifiers which can be between 1 and 10 characters long, must start with a letter or an underscore. The following characters can be letters or underscores or digits. (e.g. number, _name1, isOK).

23) Phone number in any of the following format: 9999999999,999-999- 9999, (999)-999-9999. (Note: all of these formats should be matched by a single regular expression)

Part III

ProgrammingPoints per question: 15