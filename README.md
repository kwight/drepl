# drepl
A [Dart](https://dart.dev) REPL for local exploration, using Tmuxinator, filewatcher, and Vim.

To be clear, there's no magic here; you can use any filewatcher that calls the Dart compiler with your Dart code as the entry. If you believe in the Internet, you can also just use [DartPad](https://dartpad.dev), or go sign up for [Repl.it](https://repl.it) (but those are _suuuuper_ easy).

## Requirements
* [Dart SDK](https://dart.dev/tools/sdk)
* [filewatcher-cli](https://github.com/filewatcher/filewatcher-cli)
* [tmux](https://github.com/tmux/tmux)
* [Tmuxinator](https://github.com/tmuxinator/tmuxinator)

## Usage
* Create a symlink to `drepl.yml` in your Tmuxinator configuration directory, or copy it over.
* Run `tmuxinator start drepl`.
