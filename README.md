Wrapper for `vrc-py` AUR package.

CLI implementing a message queue with persistent storage.

```
Usage: vrc-py_wrapper [-v] [OPERATION args]

An ENTRY is a line containing a message

replace|--replace-messages MESSAGE MESSAGE ...
  Replace all enabled message entries in config file with new entries.

append|--append-messages MESSAGE MESSAGE ...
  Append message entries to config.

disable|--disable-entries [--delete] ENTRY ENTRY ...
  Disable or delete message entries.

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
