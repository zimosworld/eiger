## Installation

1. Run installation command
2. Restart you bash/terminal instance 
3. Run ``eiger help`` to see a list of commands

Installation Command
```
curl -s https://raw.githubusercontent.com/zimosworld/eiger/master/eiger-installer | bash
```

## Usage

#### Help (List available commands)

```
eiger help
```

#### Initialize eiger on a project. 

This creates a .eiger file where the command is run that hold project specific configs. You add this file to source control.
```
eiger init
```

#### Create a docker environment file

This creates a .docker.env file that hold local setting specific to that machine. DO NOT add this file to source control.

This is used with containers created from https://github.com/zimosworld/php-dev
```
eiger dei
```

#### Update

```
eiger-update
```