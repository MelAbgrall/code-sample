# bash & batch


**about installing git (*windows*)**

git is somehow installed without case sensitive flag, run this command to change it:
```batch
git config core.ignorecase false
```
not doing this can lead to troubles (eg node not recognising the names of the modules)

aditionally windows shortcomings can be mitigated by using this command on the folder (in administrator mode)
```batch
fsutil.exe file SetCaseSensitiveInfo "C:\path" enable
```
