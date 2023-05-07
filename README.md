# Social Food

## Git Hooks Setup
### Required
```shell
$ cp -R git-hooks/* .git/hooks
$ chmod ug+x .git/hooks/*
```

### Optional
If you want to colorized console, execute below.
```shell
$ sudo gem install colorize 
$ sudo gem install win32console  # For Windows only
```
If not, delete colorized sentence/word in `git-hooks`
