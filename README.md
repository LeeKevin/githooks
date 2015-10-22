# githooks
Some handy git hooks

## Usage
Copy the desired hook into your project's `.git/hooks` directory as its extension. 

Example: `checkTodos.pre-commit` will be copied as `.git/hooks/pre-commit`.

You'll need to edit the files yourself if you want to combine them. Feel free to add the combined file back to this repo if you do.

## Hook descriptions

### checkTodos
A pre-commit hook that will search changed files in the working branch for instances of TODO. Line number and line that match will be printed. The user will be prompted to skip (or not) each file. If all files are skipped, then the commit will proceed. If no files contain an instance of TODO, the commit proceeds normally.
