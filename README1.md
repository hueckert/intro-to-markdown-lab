# Creating a file in Terminal

## Click on your Terminal icon and it should open to the starting "~" prompt.
* for General Assembly students use:

     ```cd ~/code/ga/labs```

## Make sure you are in a directory to create files in.
* creating a directory requires using "mkdir" on terninal.

* for example if we were making a directory called "markdown-lab" we would use:

``` mkdir markdown-lab```

## Before we make the file we have to be in the directory we made by using the "cd" command which will put us in the directory.

```cd markdown-lab```

* once in the directory you can begin creating files for that directory.

## Creating the file in the directory.
* to create a file in the directory use the "touch" command.

```touch index.html```

* You can also add mulitple files such as:

```touch index.html app.js```

##### note: "index.html" and "app.js" are seprate files.

------------------------------------

### If you make a mistake need to change the name of a file:
* use the "mv" command

```mv oldnamefile newnamefile```
* Keep in mind you must put the old file first then the new file after.

### If you need to delete the file:
* use the "rm" command

```rm file.txt```
* this will delete the file and there is no getting it back.