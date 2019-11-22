# drepl
A [Dart](https://dart.dev) REPL for local exploration.

## Requirements
* [Dart SDK](https://dart.dev/tools/sdk): `which dart`
* [filewatcher](https://github.com/filewatcher/filewatcher) (or any similar file watcher)
* [tmux](https://github.com/tmux/tmux) and [Tmuxinator](https://github.com/tmuxinator/tmuxinator) are optional (but certainly make things easy)

## Usage
* Clone this repo, and within its directory, run your filewatcher (there really is no magic to see here). Have fun!
* With filewatcher: `filewatcher '**/*.dart' 'dart main.dart'`

## Usage (with filewatcher and Tmuxinator)
* Create a symlink to `drepl.yml` in your Tmuxinator configuration directory, or copy it over.
* Run `tmuxinator start drepl`.