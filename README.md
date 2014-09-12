# profanity

A small tool to search for profanity in your directory or repository changes.

## Usage
profanity searches for words inside the currently uncommitted changes of your repository.
The words are defined inside a dictionary file, where they are separated by new lines.

Alternatively profanity can check every text file in the current directory if the `-a` flag was set.

With the `-c` it is possible to force profanity to colorize found word in the output.

    profanity: [-c] [-a] [-h] <dictionary>
         -c      force color output.
         -a      check the all files recursively.
         -h      print this message.
    <dictionary> the dictionary with the profanity.


## Examples dictionaries
[Profanity example](examples/profanity.txt "Profanity example")
[Release example](examples/release.txt "Release example")
