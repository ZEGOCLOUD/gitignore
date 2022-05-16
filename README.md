# For new project

Download the file which match your project and rename the file to `.gitignore`, then put it into your project root directory.

# For existing project

If you want to remove some file already tracked by git, you need to follow the steps:
1. remove the file from disk
```bash
$ rm path_to_file
```
2. remove the file from git
```bash
$ git rm --cache path_to_file
```
3. put path_to_file to your `.gitignore` file
4. commit and push