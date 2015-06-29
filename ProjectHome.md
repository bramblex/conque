Conque is a Vim plugin which allows you to run interactive programs, such as bash on linux or powershell.exe on Windows, inside a Vim buffer. In other words it is a terminal emulator which uses a Vim buffer to display the program output.

# Updates #

**Version 2.3 released (2011-09-02)**

Bugfix release.

<a href='http://code.google.com/p/conque/downloads/list'>Conque 2.3</a> available for download.


# Installation #

[Full installation instructions](Usage.md)

# Usage #

Type `:ConqueTerm <command>` to run your command in vim, for example:

```
:ConqueTerm bash
:ConqueTermSplit mysql -h localhost -u joe -p sock_collection
:ConqueTermTab Powershell.exe
:ConqueTermVSplit C:\Python27\python.exe
```

[Full manual](Usage.md)

# Screenshots #

<a href='http://Conque.googlecode.com/svn/wiki/screenshot/unix.jpg'><img src='http://Conque.googlecode.com/svn/wiki/screenshot/unix.jpg' width='250' /></a>

<a href='http://Conque.googlecode.com/svn/wiki/screenshot/windows.jpg'><img src='http://Conque.googlecode.com/svn/wiki/screenshot/windows.jpg' width='250' /></a>


# Contact #

For questions or comments email `nicoraffo at gmail.com`.