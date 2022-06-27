# Linux-str_replace

## Notes

**I dont' support this anymore.**

This perl script will enable you to do literal search and replace in files (in place) and in STDIN

No messing with regular expression anymore. No more `sed` or `awk` or `perl -pie`. This handy script written in perl will replace text exactly as you want, No matter it has the so-called special characters or not. Just like `str_replace` PHP function.

The file is loaded fully in memory before processing!

# Usage
```bash
str_replace Search Replace File # replace in File in place 
```
## OR 
```bash
STDIN | str_replace Search Replace # to STDOUT
```

# install
Execute this line in your linux server
```bash
wget https://raw.githubusercontent.com/Samer-Al-iraqi/Linux-str_replace/master/str_replace.pl \
-O /usr/local/str_replace && \
chmod a+x /usr/local/bin/str_replace
```

Notes:
* Search and replace always case-sensitive 
* Always do global Search and replace
* Don't care about lines.
* It may work in Windows as well.
* tested with unicode (I suprised it worked correctly!)

Hope it will help. Thanks
