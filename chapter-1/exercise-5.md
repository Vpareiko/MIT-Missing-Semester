** Run the command by explicitly starting the sh interpreter, and giving it the file semester as the first argument,
i.e. sh semester. Why does this work, while ./semester didn’t? **
* `sh semester` -> good response - the './semester' script doesn't worked, cause I don't have access rights:
* in the 'missing' directory: `ls -l` -> `rw-r--r-- 1 vlad vlad 61 Aug 15 13:37 semester`