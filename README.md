# Non-Regex-Text-Search-and-Replace-for-Linux

This perl script will enable you to do literal search and replace in files (in place) and in STDIN

No missing with regular expression. No more sed or awk or perl -pie. This handy script written in perl will replace text exactly what you want, if it has the so-called special characters or not. Just like str_replace PHP function.

#Usage
```bash
str_replace Search Replace File # replace in File in place 
```
##OR 
```bash
STDIN | str_replace Search Replace # to STDOUT
```

Notes:
1- Search and replace always case-sensitive 
2- Always do global Search and replace
3- Don't care about lines.
4- tested with unicode (I suprised it worked correctly!)

Hope it will help. Thanks
