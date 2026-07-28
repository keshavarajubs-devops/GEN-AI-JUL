Git --> local
Github --> Remote repo

In local repo

1. We need to create a local repo with the help of git init.

2. After which an empty repo will be created.

3. After creating your files, we need to start tracking them so they can be added to Git. We use:
   git add <file_name>
   or
   git add .
   (to add multiple files)

4. In order to check the status of each file, we use the command:
   git status

5. After starting to track a local file, we need to save it by creating a commit using:
   git commit -m "message"
   Here, `-m` is the flag used to specify the commit message.