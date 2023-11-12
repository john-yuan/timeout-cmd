# README

[![npm version](https://img.shields.io/npm/v/timeout-cmd)](https://www.npmjs.com/package/timeout-cmd)
[![install size](https://packagephobia.now.sh/badge?p=timeout-cmd)](https://packagephobia.now.sh/result?p=timeout-cmd)
[![npm downloads](https://img.shields.io/npm/dm/timeout-cmd.svg)](https://npm-stat.com/charts.html?package=timeout-cmd)

A command to sleep for specified time.

```bash
npm i timeout-cmd --save-dev
```

## Usage

```bash
# sleep 2 seconds
npx timeout-cmd 2

# sleep 3 seconds
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
  # sleep 3 seconds
  timeout-cmd 3s
  # sleep 100 milliseconds
  timeout-cmd 100ms

  Note: The unit can be "s" or "ms" and it is optional.
        The default unit is "s".

OPTIONS
  --help, -h       Print this message.
```

## License

[MIT](./LICENSE)
