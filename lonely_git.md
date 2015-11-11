# Lonely Git
Git functions well as a VCS with simply a local repository

## Recording Changes to a Local Repository

* [File Status Life Cycle](https://git-scm.com/book/en/v2/Git-Basics-Recording-Changes-to-the-Repository)

committing changes with one-line messages
``` shell
git commit -m "Add(TappanTree.py): implement TappanTree object"
```

committing changes in text-editor of choice
``` shell
git commit
```

## Ignoring Files
under git project root directory:
``` shell
$ touch .gitignore
```

example .gitignore from [gitignore.io](https://www.gitignore.io)
```
# Created by https://www.gitignore.io/api/java

### Java ###
*.class

# Mobile Tools for Java (J2ME)
.mtj.tmp/

# Package Files #
*.jar
*.war
*.ear

# virtual machine crash logs, see http://www.java.com/en/download/help/error_hotspot.xml
hs_err_pid*
```

## Branching
``` shell
$ git branch
$ git branch tappan_square
$ git checkout tappan_square
```

## Merging
``` shell
$ git checkout master
$ git merge tappan_square
```

## Viewing Logs
``` shell
$ git log
$ git log --graph --oneline --decorate --all
```

