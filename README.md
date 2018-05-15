## Installation

1. Run installation command
2. Restart you bash/terminal instance 
3. Run ``eiger help`` to see a list of commands

Installation Command
```
curl -s https://raw.githubusercontent.com/zimosworld/eiger/master/eiger-installer | bash
```

## Usage

#### Help

List available commands

```
eiger help
```

#### Initialize eiger on a project. 

Creates a `.eiger` file project specific configs are saved for use with eiger commands (e.g composer). You add this file to source control.

```
eiger init
```

#### Create a docker environment file

Creates a `.docker.env` file that hold local setting specific to the local machine. DO NOT add this file to source control.

This is used with docker containers based off from https://github.com/zimosworld/php-dev
```
eiger dei
```

#### Update

Command to update eiger

```
eiger-update
```