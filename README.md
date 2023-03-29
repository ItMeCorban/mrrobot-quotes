Forked from sudofox/shell-mommy https://github.com/sudofox/shell-mommy

Replacing 'mommy' quotes with Mr Robot quotes.


## Installation

Source the `mrrobot-quotes.sh` script in your current shell or add it to your `~/.bashrc` file to have it available every time you open a new terminal.

```
. /path/to/mrrobot-quotes.sh
```

If you'd like it to always show a message after each command, you can define a custom `PROMPT_COMMAND` like so:

```
export PROMPT_COMMAND="mommy \\$\\(exit \$?\\); $PROMPT_COMMAND"
```
