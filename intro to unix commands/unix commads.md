## Unix Hello Word! is cd
Change directory cd => to move to a directory of your choice
```sh
[options] => directory_name
	  => path/to/directory 
	  => ..   #to move to the parent directory of the current working directory 
	  => /    #to move to the root

$ cd [option or file_path/to the/dir/you want]
```

## ls => Display a list of all files and directories in the current working directory 
```sh
[options] => --version    #shows the version of the cmmd
	  => ~      #show a list of files and dir on the home dir on a unix sys
	  => -a     #show all files and dir
	  => -d     #list all the dir in the current working dir
	  => -R     #display the files of subdirectories

$ ls [options]
```


## echo => used to print strings
```sh
[options] => \b   #for backspace
	  => \t   #for horzontal tab space
	  => \v   #for vertical tab space
	  => \n   #line break

$ echo -e "your sentence should [option] go here"
you can also use the * with the echo cmmd to print the files and dir in a directory 
```

## history => displays all previously used commands
```sh
$ history 
```

## clear => to clear the terminal
```sh
$ clear 
```

## pwd => show the path of the working directory 
```sh
$ pwd 
```

## mkdir => to create dir's
```sh
[options] => --version
	  => -v     #to return a created message alert
	  => -p     #creates the dir in the parent format as given eg: dir/dir1/../dirn
	  => --help

$ mkdir [options] foldername
```

## rmdir => remove a dir
```sh
[options] => --version
	  => -v
	  => -p     #removes the child and parent dir eg: -p parent_dir/dir2
	  => --help

$ rmdir [options] directory_name
```

## cp => used to copy files and dir from one location to another
```sh
[option] => -i   #gives you a warning before overwriting
	 => --backup
	 => -R   #copies all files in source

	=> souceFile  destinationFile
	=> souceFile1 souceFile2 ...  souceFileN destinationDirectory    #move files to a dir
	=> *  destinationDirectory      #(*means all files)

$ cp [option] source/_path  destination/_path
```

## mv => to move files and dir form source to destination or rename a file or dir
```sh
$ mv source_filename  new_filename

$ mv source/_path  destination/_path
```

## touch => create empty file if not exist
```sh
[option] => can create multiple file eg: touch file file1 ... fileN
	 => --version
	 => -a    #to change access time of a file. use <stat filename> to check 
	 => -m    #to change modification time of a file
$ touch [option] filename
```

## cat => displays content of a file or multiple files
```sh
	=> source_file > destination_file    #copy content of one file into another file
	=> source_file  >> destination_file    #append content

[option] => -n   #show the text with the line number
	 => -E   #displays a $ at the end of each line

$  cat [option] filename
```

## tac => display file content in reverse
```sh
eg: 
$ tac filename
```


## date => display current date
```sh
$ date 
```

## whoami => display current user
```sh
$ whoami 
```

## passwd => used to change user account password
```sh
$ passwd 
```

## uname => shows the machine name
```sh
[option] => -a   #display all sys info
	 => -s   #display kernel name
	 => -n   #display hostname of network node
	 => -v   #display kernel version
	 => -p   #display type of processor the machine has
$ uname [option]
```