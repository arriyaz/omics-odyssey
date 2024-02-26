# Linux Basic Commands

## `ls`: lists the contents of a directory

`ls` can used to list the contents of any directory.

To view contents of current directory:

```bash
ls
```

To view contents of other directories, after `ls` command add directory path. For example:

```bash
ls /bin
```

```bash
ls /
```

Here, `/` means root directory.

In command line, each command has several options/flags which are generally denoted by `-` sign. 

Common flags/options for ls command:

- `-l` : uses long listing format
- `-1` : forces output to be one entry per line
- `-t` : sorts output based on file modification date
- `-S` : sorts output by size
- `-r` : reverse-sorts the output
- `-R` : recursively lists output of all directories below current level
- `-p` : puts / indicator to directories

You can combine more than one flags together, For example:

```bash
 ls -1trp
```

## Man (manual) Pages

To view help or manual for the **default commands** of linux you can use `man` command.

For example, to view the manual of `ld` command:

```bas
man ls
```

You can use mouse scroll or following shortcut keys to navigate through man page.

- `space bar`: to scroll down a page
- `b` : to go back a page
- `q` : to quit manual page.

## `pwd` : prints current working directory

```bash
pwd
```

## `mkdir` : makes new directory

```bash
mkdir dirName
```

You can create more that one directory together:

```bash
mkdir dir-1 dir-2 dir-3
```

> Note: Don't use **space** in directory or filename. Because spaces in file/directory name can cause trouble in your codes. It's always good practice to use `-` or `_` to separate words in file/directory names.

- An important flag for `mkdir` command:
  - `-p` : no error if a directory already exists and make parent directories if needed.

## `cd` : to change directory

```bash
cd dirName
```

You can also navigate several directories in one step:

```bash
cd dirName/subDir/subSubDir/
```

Here, `/` is directory separator.

> Sometimes you may see: `cd ./dirName/subDir/subSubDir/`, here, the dot (`.`)at the beginning of the path means **current directory**.

To navigate to home directory:

```bash
cd
```

Or,

```bash
cd ~
```

In command line, tilde (`~`) sign means home directory

To go one step upward or back:

```bash
cd ..
```

To go two step back/upward

```bash
cd ../..
```

etc.....etc...etc...

## Absolute and Relative Path

