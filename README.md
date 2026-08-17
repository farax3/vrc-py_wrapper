Wrapper for `vrc-py` AUR package with plans on becoming a standalone VRChat chatbox manager.

CLI implementing a message queue with persistent storage.

```
Usage: vrc-py_wrapper [-v] [ OPERATION [SWITCH] args ]

A CLI for managing and cycling VRChat OSC chatbox messages.

replace MESSAGE MESSAGE ...
  Replace all enabled message entries in config file with new entries.

disable ENTRY ENTRY ...
  Disable message entries.

delete ENTRY ENTRY ...
  Delete message entries.

enable ENTRY ENTRY ...
  Enable message entries.

append MESSAGE MESSAGE ...
  Append message entries to config.


--purge-entries
  Purge disabled message entries.

--print-config
  Print config file.

--print-enabled|--print-entries
  Print enabled message entries.

--print-disabled
  Print disabled message entries.

--init-config
  Initializes a new config file with example uses.

--verbose|-v
  Prints current timeout and message.

--help
  Print this message.

```
