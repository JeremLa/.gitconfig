GitConfig
===========

simple and basic .gitConfig file. This one contains global params.

How to use it :
------------

The simpliest way to use it is to copy / past content in your .gitConfig.

By default you will find it at `~/.gitConfig` on linux and at `C:\Documents and Settings\All Users\Application Data\Git\config` for Windows XP or at `C:\ProgramData\Git\config` on vista and newer.

Usage 
-------------

In first, you have to change default user informations directly in file or with next commmand line :

**name**
``` bash
:~$ git --global user.name=<your name>
```

**email**
``` bash
:~$ git --global user.email=<your email>
```

All commands are usable with prefix git

```bash
:~$ git ls
:~$ git ll
```

Some of them needs additionals informations

```bash
:~$ git flu <file name>
```
