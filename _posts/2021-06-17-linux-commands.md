---
layout: post
category: linux
---

This is a list of Linux commands you should know to manage your Linux servers

## ls

It lists the content of a directory.

#### Usage

ls <directory or file>

#### Useful options

-a: Lists hidden content
-l: Lists the content as a list
-h: Lists the content in a human readable way

## cp 

This command allows you to copy files

#### Usage

cp <file to copy> <destination>

## rm

Deletes files or directories

#### Usage

rm <file to delete>

#### Useful options

-r: Recursive deletion
-f: Force deletion

## mv

Moves files and directories

#### Usage

mv <file or directory to move> <destination>

## rsync

Synchronizes files or directories. It can be useful to copy multiple files at once. It is also useful for backups.

#### Usage

## rsync (options) <source> <destination>

#### Useful options

-a: Archive mode
-v: Verbose

## touch

Creates an emtpy file

#### Usage

touch <name of file>

## du

Shows the disk usage

#### Usage

## du (options) <directory>

#### Useful options

-s: Sum the amount of disk usage
-h: Show output in human readable format
  
## stat

Shows information about a file

#### Usage

stat <file>

## zip

File or directory compression

#### Usage

zip (options) <file of the compressed file> <file or directory to compress>

#### Useful options

-r: Recursive

## zipinfo

Shows the content of the zipped file

#### Usage

zipinfo <file>

## tree

Shows a tree structure of a directory

#### Usage

tree <directory>

## find

Searches for a file or directory

#### Usage

find <directory where we want to find> (options)

#### Examples

find . -mtime +2 # Searches for the files and directories that are older than 2 days
find . -iname '*.log' # Searches for all files in the current directory that have a .log extension

## ps 

Shows the running processes

#### Options

ax: See all processes
f: Shows the output as a hierarchy

## kill

Kills a process by name or process id

#### Usage

kill <name|process id> 

## cat 

Shows the content of a file

#### Usage

cat <file>

## grep

Filters the content of the text based on a given pattern

#### Usage

grep <pattern> <file>

#### Useful options

-v: Inverted grep

## dh

Shows the available disk space

#### Usage

dh (options) <directory>

#### Useful options

-h: Shows the output in human readable format

## top

Shows the process running and the resource usage
