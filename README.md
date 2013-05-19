typelevel-activator
===================

All the [typelevel.scala](http://typelevel.org/) stack ([scalaz](https://github.com/scalaz/scalaz), [shapeless](https://github.com/milessabin/shapeless), [spire](https://github.com/non/spire)) and their contrib libraries at your fingertips.

Installation
------------

**Prerequisites:** sbt, git, sed.

```sh
$ cd
$ mkdir bin
$ cd bin
$ git clone git://github.com/folone/typelevel-activator.git
$ echo export TYPELEVEL_HOME=~/bin/typelevel-activator >> ~/.bashrc # or .zshrc or .whateveryouareusingrc
$ echo export PATH=$PATH:$TYPELEVEL_HOME >> ~/.bashrc
$ cd
$ source .bashrc # .againwhateverrc
$ typelevel # ready for using
$ typelevel upgrade # to fetch the latest changes
```

Usage
-----

```sh
$ typelevel #start
  > usage # list available commands
  > init projectname org.myorganization # creates a new project
  > exit
```
