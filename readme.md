# Linux and GIT Command Cheat Sheet 
## Linux Command 1: `ls`

- **Description:** List files and directories.
- **Options:**
  * -l: Long format listing.
  * -a: Include hidden files hidden ones
  * -h: Human-readable file sizes.
- **Usage:**
``` bash 
ls
 ```

## Linux Command 2: `cd`

- **Description:** Change directory
- **Usage:**
``` bash
cd/path/to/directory
 ```

## Linux Command 3: `pwd`

- **Description:** Print current working directory 
- **Usage:**
``` bash
pwd 
 ```

## Linux Command 4: `mkdir`

- **Description:** Create a new directory 
- **Usage:**
``` bash
mkdir my_directory
 ```

## Linux Command 5: 'rm'

- **Description:** Remove files and directories 
- **Options:**
  * -r: Remove directory recursively
  * -f: force removal wihout confirmation
- **Usage:**
``` bash
rm -option removeDirectory
 ```

## Linux Command 6: `cp`

- **Description:** Copy files and directories
- **Options:**
  * -r: Copy directories recursively 
- **Usage:**
``` bash
cp file.txt destination
 ```

## Linux Command 7: `mv`

- **Description:** Move/rename files and directories
- **Usage:**
``` bash
mv file.txt newname.txt
mv file.txt directory
 ```

## Linux Command 8: `touch`

- **Description:** Create an empty file or update file timestamps
- **Usage:**
``` bash
touch file.txt
 ```

## Linux Command 9: `cat`

- **Description:** View all contents of a file
- **Usage:**
``` bash
cat file.txt
 ```

## Linux Command 10: `head`

- **Description:** Display the first few lines of a file 
- **Options:**
  * -n: specify the numbers of lines to display
- **Usage:**
``` bash
head file.txt
head -n (number) file.txt
 ```

## Git  Command 1: `status`

- **Description:** show modified files in working directory, staged for your next commit
- **Usage:**
``` bash
git status 
 ```

## Git  Command 2: `add`

- **Description:** add a file as it looks now to your next commit
- **Usage:**
``` bash
git add [file]
 ```

## Git  Command 3: `diff`

- **Description:** diff of what changed but not staged
- **Usage:**
``` bash
git diff
 ```

## Git  Command 4: `branch`

- **Description:** list your branches. a * will appear next to the currently active branch
- **Usage:**
``` bash
git branch
 ```


## Git  Command 5: `checkout`

- **Description:** switch to another branch and check it out into your working directory
- **Usage:**
``` bash
git checkout 
 ```

