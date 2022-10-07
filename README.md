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
- cp file.txt copy_file.txt (Copy all contents of file.txt to copy_file.txt)
- mv names.txt random (move names.txt inside random)
- mv file.txt newName.txt (Rename file.txt to newname.txt)
- rm copy_file.txt (Permanently remove copy_file.txt)
- rm -R test (Remove all subdirectories as well) → rm -rf test (Remove forcefully)
- cp -R test random (Copy everything from test folder to random folder)
- du -h (Disk usage of current directory)
- vi total.txt (Write into total.txt file from terminal)
- head total.txt (display first 10 lines of total.txt)
- head -n 5 total.txt (Only display first 5)
- tail total.txt (Display from last)
- diff total.txt new.txt (See the differences btw these 2 files line by line)
- locate “*.txt” (Locate all .txt files)
- find random (Show all files + hidden files)
- find . -type d (Only find the folders/directories inside the current directory)
- find . -type f (Find all files)
- find . -type f -name “*.txt”
- find . -type f -iname “two*” (Ignore Case sensitivity while finding)
- find . -type f -mmin +2 -mmin -10 (Find all files that were modified more than 2 min ago and less than 10 min ago)
- find . -type f -maxdepth 1 (Only show files in the current dir not recursively)
- find . -size +1k (Size of files more than 1Kb)
- find . -type f -name “*.txt” -exec rm -rf {} +  (Remove all files recursively from the find)
- whoami (Checking Logged in user)
- grep -win “Rajib” names.txt (w: word, i:ignorecase, n:linenumber / Searching inside a file with regular expression)
- grep -win “Rajib” ./*.txt
- grep -rwin “Rajib” . (Check inside directory recursively)
- sort -r companies.txt (Sort in reverse order)

### Environment Variables

- echo $PATH (Display Path Environment Variable)
- export MY_NAME=”Rajib” (Creating own environmental variable). → echo $MY_NAME → Rajib

### Terminal Shortcuts

- CTRL + A (Move cursor to beginning)
- CTRL + E (Move cursor to end)
- CTRL + K (Remove everything after the cursor pointer)
- CTRL + U (Remove complete line)
- git add .;git commit -m “message”; git push origin main (Running multiple commands in single Line)
- cat file.txt \ (Write a long command in multiple lines without executing)
- Setting up aliases in ~/zprofile or ~/zshrc (For permanent setup)

### Commands for System/OS

- df (Check Disk/Drive Space Usage)
- history (Display history of all commands we are using)
- top (display system processes)
- kill {process_id} (Get process_id from top → It kill that process)
- uname (Check the OS Kernel)
- zip files.zip companies.txt names.txt
- unzip files.zip
