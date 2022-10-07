### Basic Commands

- where python3 (Gives the location of python executable file installed on machine)
- open . *OR* open {filename} (Open that directory in file explorer)
- mkdir {foldername} (Create new folder)
- touch names.txt (Create a new file)
- cd {foldername} (Change Directory)
- ls (Show list of items in current directory)
- ls {foldername}
- ls -a (Show all hidden files as well)
- ls -R (Show all files recursively inside them as well)
- cat {filename} (Display the content present in that file)
- pwd (Print working directory)
- cat > Hello.txt (Create hello file) → Then write the content inside Hello file
- cat file.txt hello.txt > total.txt (Merge content of 2 files to total.txt)
- echo “Hello World” > file.txt (Overwrite content of file.txt)
- man echo (View description of command)
- cat file.txt | tr a-z A-Z > upper.txt (Translate content of file.txt to uppercase and store it in upper.txt)
- cat file.txt \ (Write a long command in multiple lines without executing)
- cp file.txt copy_file.txt (Copy all contents of file.txt to copy_file.txt)
- mv names.txt random (move names.txt inside random)
- mv file.txt newName.txt (Rename file.txt to newname.txt)
- rm copy_file.txt (Permanently remove copy_file.txt)
- rm -R test (Remove all subdirectories as well) → rm -rf test (Remove forcefully)
- cp -R test random (Copy everything from test folder to random folder)
- df (Check Disk/Drive Space Usage)
- du -h (Disk usage of current directory)

### Environment Variables

- echo $PATH (Display Path Environment Variable)
- export MY_NAME=”Rajib” (Creating own environmental variable). → echo $MY_NAME → Rajib
