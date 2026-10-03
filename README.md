Wrapper for `vrc-py` AUR package with plans on becoming a standalone VRChat chatbox manager.

CLI implementing a message queue with persistent storage.

```
Usage: vrc-py_wrapper [-v] [-vv|--verbose] [-p|--prune] [ OPERATION [SWITCH] args ]

A CLI for managing and cycling VRChat OSC chat box messages.

replace [--purge] MESSAGE MESSAGE ...
  Disable (or delete) all enabled message entries with new entries.

disable (a|all) | ENTRY ENTRY ...
  Disable message entries.

delete (a|all) | (disabled|enabled) | ENTRY ENTRY ...
  Delete message entries.

enable (a|all) | ENTRY ENTRY ...
  Enable message entries.

append MESSAGE MESSAGE ...
  Append message entries to config.

print [enabled|disabled]
  Print message entries.

clear
  Wipe config

init
  Initialize a new config file with example uses.


-p|--purge
  Purge disabled message entries.

-v
  Print message changes to stdout

-vv|--verbose
  Print current timeout and message changes.

--help
  Print this message.

```
