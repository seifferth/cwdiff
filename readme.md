# cwdiff

Yet another [wdiff](https://www.gnu.org/software/wdiff/) wrapper. `wdiff`
is a `diff`-like program that operates on words, rather than lines. Its
output can be a little hard to process visually, though. `cwdiff` takes
care of colouring the output produced by `wdiff` and of collapsing
unmodified sections.

## Installing

Simply add the two scripts to the `PATH` and make sure they are marked
as executable.

## Using

Showing the diff between two files:

    cwdiff filename_one filename_two

Using with git:

    git cwdiff HEAD~5
