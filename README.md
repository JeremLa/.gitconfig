Linux aliases
===========

list of basics but useful aliases to gain time.
One advise, never forget original command, you gain time ponctually but if you are brought to work without them, you must to remember originals of them.

How to use it :
------------

You will need to past the content of the file in you aliase file in linux.

For Ubuntu, bashrc prompt :

 1. find this lines in your `.bashrc` and uncomment it if necessary or past what following in it if is missing.

```bash
# ~/.bashrc

if [ -f ~/.bash_aliases ]; then
    . ~/.bash_aliases
fi
```

2. find file `.bash_aliases`, normaly it's in the same folder than `.bashrc`. If you don't find it, create it.
If you create it, becarefull to the owner, the owner of `.bashrc` file must have permission to execute the content of this file.

3. past the list of aliases to this `.bash_aliases` file.

4. reload file to take care of new changes.

```bahrc

> . ~/.bashrc

# or

> source ~/.bashrc

```

You will may be need some adjustement depend on your linux.

Usage 
-------------

These aliases can be used like any linux aliases.
If you are not in symfony for concerned aliases, an exeption will be thrown.

Tips 
-------------

* You can create new aliases, of course, be careful for new symfony one. All of mine use the alias pbc. If you want use it to, create your new alias after the pbc declaration.

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
    git --global user.name=<your name>
```

**email**
``` bash
    git --global user.email=<your email>
```

All commands are usable with prefix git

```bash
    git ls
    git ll
```

Some of them needs additionals informations

```bash
    git flu <file name>
```
