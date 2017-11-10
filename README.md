## Scripts ##

Bunch of scripts for different purpose.

### camo  ###
Find all commits per developers in a specific directory inside a git repository, greping a parameter (either a developer name or a developer email). Place into the commiters.txt file.

Usage

Go to directory with a .git, then:
```
camo -d sub/project sub/another/project -g "sergeybrin@google.com"
```

### lns ###
Create a relative symlink of some file (abandones dirs) to the `/home/username/bin` directory and make it executable.

Usage:
```
lns superscript
```

### rebuildrpm ###
Finds a `.spec` file, gets an `.rpm` package's name and builds an `.rpm` and a `.src.rpm`.

Usage

Go to directory with the `.spec` and sources, then:
```
rebuildrpm
```

It will build `.rpm`s to the `/home/username/rpmbuild` directory.

You can specify a custom path for output using:
```
export RPM_ROOT=path/to/dir
```

### scriptisch ###

Dummy script for macOS, which imitates a dialog with you in German language.

### svim ###

Find a file and open it in vim, case insensitive and can take only part of a file name.

Usage:
```
svim Systemserver
```

Assuming we have a SystemServer.java file. The command above will find and open it.

### chports ###

The script for changing ports of a git remote urls for all projects.

Usage:
```
chport <port_old> <port_new> <dir one> <dir two> ...
```
