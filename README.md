# Hooker
A set of git hooks I use on PHP projects

## Installation

1. Copy the contents of the repo in .git/hooks
2. Make every script executable `chmod -R a+x`

## Usage

For every available hook there is an entry script, this will run every script in the folder `./git/hooks/hookname-scripts`. These scripts will run in numerical order. Start every scriptname with a number to alter the order of execution.
