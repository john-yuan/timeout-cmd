# README

A command to sleep for specified time.

## Usage

```bash
# sleep 2 seconds
npx timeout-cmd 2

# sleep 3 second
npx timeout-cmd 3s

# sleep 100 milliseconds
npx timeout-cmd 100ms
```

## Options

```text
COMMAND
  timeout-cmd <time>

EXAMPLES
  # sleep 2 seconds
  timeout-cmd 2
  # sleep 3 second
  timeout-cmd 3s
  # sleep 100 milliseconds
  timeout-cmd 100ms

  Note: The unit can be "s" or "ms" and it is optional.
        The default unit is "s".

OPTIONS
  --help, -h       Print this message.
```
