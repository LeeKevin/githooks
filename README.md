# githooks
Some handy git hooks

## checkTodos
A pre-commit hook that will search changed files in the working branch for instances of TODO. Line number and line that match will be printed. The user will be prompted to skip (or not) each file. If all files are skipped, then the commit will proceed. If no files contain an instance of TODO, the commit proceeds normally.
