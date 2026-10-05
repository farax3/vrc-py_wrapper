Wrapper for `vrc-py` AUR package with plans on becoming a standalone VRChat chatbox manager.

CLI implementing a message queue with persistent storage.

```
Usage: vrc-py_wrapper [-v] [-vv|--verbose] [-p|--prune] [ OPERATION [SWITCH] args ]

A CLI for managing and cycling VRChat OSC chat box messages.

r[eplace] [--purge] MESSAGE MESSAGE ...
  Disable (or delete) all enabled message entries with new entries.

d[isable] (a|all) | ENTRY ENTRY ...
  Disable message entries.

de[lete] (a|all) | (disabled|enabled) | ENTRY ENTRY ...
  Delete message entries.

e[nable] (a|all) | ENTRY ENTRY ...
  Enable message entries.

a[ppend] MESSAGE MESSAGE ...
  Append message entries to config.

p[rint] [enabled|disabled]
  Print message entries.

c[lear]
  Wipe config

i[nit]
  Initialize a new config file with example uses.


-p|--purge
  Purge disabled message entries.

-v
  Print message changes to stdout

-vv|--verbose
  Print current timeout and message changes.

h|-h|--help
  Print this message.

```
