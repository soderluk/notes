# Notes
Just a minimal notes script written in Python for quickly scribbling down notes.

The script saves the notes in a Markdown file, with the current date "Y-m-d.md" in the ~/.notes folder.

You can quickly start by typing `notes` in the command line. This will create/open the current date's notes in vim.

You can list all the existing notes with `notes --list`, and open a specific note by entering the index of the file (from the --list output), e.g. `notes --open 2`.

`notes --help` will show you the available options.

