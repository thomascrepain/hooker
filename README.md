# Hooker
A set of git hooks I use on PHP projects

## Installation

1. Copy the contents of the repo in .git/hooks
2. Make every script executable `chmod -R a+x`
3. Run `composer install`

## Usage

For every available hook there is an entry script, this will run every script in the folder `./git/hooks/hookname-scripts`. These scripts will run in numerical order. 
Start every scriptname with a number to alter the order of execution.

The available git hooks can be found here: 
[https://www.kernel.org/pub/software/scm/git/docs/githooks.html](https://www.kernel.org/pub/software/scm/git/docs/githooks.html)