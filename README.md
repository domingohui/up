## Script that serves my extremly niched need - Change directory to the root directory of a git (or any) project

Inspired by [z](https://github.com/rupa/z).

### How to use

Copy [```u```](https://github.com/domingohui/up/blob/master/u) to ```/bin/```, ```/usr/local/bin``` or one of the folders for binary files in the ```$PATH```

To run, within a project (sub)folders,

```
. u
```

Since the script itself runs in a subshell, we need to source it (hack) to change the working directory of the parent process. 

#### TODO
- [ ] Detect if current directory is 'outside of' ```$HOME```
- [ ] Use keywords other than ```.git```
- [ ] Set up script
