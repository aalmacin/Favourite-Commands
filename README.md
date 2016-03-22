# Favourite-Commands
A list which contains some of my favourite shell terminal commands

## grep (<b>g</b>lobally search a <b>r</b>egular <b>e</b>xpression and <b>p</b>rint)

Used to search for the files containing the regular expression passed as an argument.

### Favourite application

Recursively search for files in the current directory which contains the regular expression.

```sh
grep '[REGEX]' . -R
```

## find

Used to search for a files.

### Favourite application

Search for files with the name matching the regular expression

```sh
find . -name '[REGEX]'
```
Search for directories.

```sh
find . -type d
```

## Setting up postgresql

Install postgresql

```sh
npm install -g postgresql
```

Creates a new database cluster

```sh
initdb [DATABASE_NAME]
```

Start the database cluster

```sh
pg_ctl -D [DATABASE_NAME] -l [DATABASE_NAME]/[LOGFILE_NAME].log start
```
