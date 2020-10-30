local-cli
=========



[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/local-cli.svg)](https://npmjs.org/package/local-cli)
[![Downloads/week](https://img.shields.io/npm/dw/local-cli.svg)](https://npmjs.org/package/local-cli)
[![License](https://img.shields.io/npm/l/local-cli.svg)](https://github.com/getflywheel/local-cli/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g @getflywheel/local-cli
$ local-cli COMMAND
running command...
$ local-cli (-v|--version|version)
@getflywheel/local-cli/0.0.0 darwin-x64 node-v12.13.0
$ local-cli --help [COMMAND]
USAGE
  $ local-cli COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`local-cli help [COMMAND]`](#local-cli-help-command)
* [`local-cli list-sites`](#local-cli-list-sites)
* [`local-cli start-site SITEID`](#local-cli-start-site-siteid)
* [`local-cli stop-site SITEID`](#local-cli-stop-site-siteid)

## `local-cli help [COMMAND]`

display help for local-cli

```
USAGE
  $ local-cli help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.0/src/commands/help.ts)_

## `local-cli list-sites`

list all Local sites

```
USAGE
  $ local-cli list-sites

EXAMPLE
  $ local-cli list
```

_See code: [src/commands/list-sites.ts](https://github.com/getflywheel/local-cli/blob/v0.0.0/src/commands/list-sites.ts)_

## `local-cli start-site SITEID`

start a Local site and all of its services

```
USAGE
  $ local-cli start-site SITEID

EXAMPLE
  $ local-cli start-site 6mC6PsMCh
```

_See code: [src/commands/start-site.ts](https://github.com/getflywheel/local-cli/blob/v0.0.0/src/commands/start-site.ts)_

## `local-cli stop-site SITEID`

stop a Local site and all of its services

```
USAGE
  $ local-cli stop-site SITEID

OPTIONS
  -h, --help  show CLI help
```

_See code: [src/commands/stop-site.ts](https://github.com/getflywheel/local-cli/blob/v0.0.0/src/commands/stop-site.ts)_
<!-- commandsstop -->