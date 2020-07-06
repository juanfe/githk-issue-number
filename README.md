# Git hook to add the issue number at the beggining of a commit mesage

Puth the hook commit-msg in the directory .git/hook. If you are working on a branch
of an issue that have the format whatever/ABCDE-123, before commit this hook will
add to the message the prefix ABCDE-123:

Example:

If you are working on a feature/ETP-865, or in a hotfix/ETP-865, it will add the
message prefix "EPT-865:", after do the commit.

## Windows users

Remove the first line of the hook commit-msg and the first \# in the second line.

'''python
#!C:\Python Files\Python37\pyton.exe
'''
