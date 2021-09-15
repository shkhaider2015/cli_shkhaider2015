shkhaider2015
=============

a command line tool

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g shkhaider2015
$ shkhaider2015 COMMAND
running command...
$ shkhaider2015 (-v|--version|version)
shkhaider2015/0.0.0 win32-x64 node-v14.17.1
$ shkhaider2015 --help [COMMAND]
USAGE
  $ shkhaider2015 COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`shkhaider2015 add [TODO]`](#shkhaider2015-add-todo)
* [`shkhaider2015 hello [FILE]`](#shkhaider2015-hello-file)
* [`shkhaider2015 help [COMMAND]`](#shkhaider2015-help-command)
* [`shkhaider2015 list`](#shkhaider2015-list)
* [`shkhaider2015 remove [INDEX]`](#shkhaider2015-remove-index)

## `shkhaider2015 add [TODO]`

Add new todo to list

```
USAGE
  $ shkhaider2015 add [TODO]
```

_See code: [src/commands/add.ts](https://github.com/shkhaider2015/cli_shkhaider2015/blob/v0.0.0/src/commands/add.ts)_

## `shkhaider2015 hello [FILE]`

describe the command here

```
USAGE
  $ shkhaider2015 hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ shkhaider2015 hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/shkhaider2015/cli_shkhaider2015/blob/v0.0.0/src/commands/hello.ts)_

## `shkhaider2015 help [COMMAND]`

display help for shkhaider2015

```
USAGE
  $ shkhaider2015 help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.3/src/commands/help.ts)_

## `shkhaider2015 list`

Print out all todos

```
USAGE
  $ shkhaider2015 list
```

_See code: [src/commands/list.ts](https://github.com/shkhaider2015/cli_shkhaider2015/blob/v0.0.0/src/commands/list.ts)_

## `shkhaider2015 remove [INDEX]`

Remove a todo from list

```
USAGE
  $ shkhaider2015 remove [INDEX]
```

_See code: [src/commands/remove.ts](https://github.com/shkhaider2015/cli_shkhaider2015/blob/v0.0.0/src/commands/remove.ts)_
<!-- commandsstop -->
