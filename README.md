Eiger is an aliasing tool, allowing you to run common developer related commands inside containers instead of a locally. 

This allows you to run different versions of commands in different directories without the hassles of managing multiple installations of the same command.

## Installation

1. Run installation command
2. Restart you bash/terminal instance 
3. Run ``eiger help`` to see a list of commands and confirm installation was successful

Installation Command
```
curl -s https://raw.githubusercontent.com/zimosworld/eiger/master/eiger-installer | bash
```

## Requirements

1. Docker
2. Git
3. Terminal for Mac/Linux or GitBash for Windows

## Usage

* [Aliases](#aliases)
* [Aws](#aws)
* [Composer](#composer)
* [Docker](#docker)
* [Docker environment file](#dei)
* [Helm](#helm)
* [Help](#help)
* [Kubernetes cli client](#kubectl)
* [Init](#init)
* [Mysql](#mysql)
* [Node](#node)
* [NPM](#npm)
* [Plugin](#plugin)
* [Terraform](#terraform)
* [Update](#update)

<a name="aliases"/>

#### Aliases

Manage aliases for eiger plugins allowing you to run them without `eiger` in prefixed.

```
eiger aliases
```

<a name="aws"/>

#### AWS

AWS CLI is a unified tool that provides a consistent interface for interacting with all parts of AWS.

```
eiger aws
```

<a name="composer"/>

#### Composer

A application-level package manager for the PHP.

```
eiger composer
```

<a name="docker"/>

#### Docker

Docker shortcuts to starting, stopping, setting up and managing containers.

NOTE: This command can not be aliased as it will conflict with docker.

```
eiger docker
```

<a name="dei"/>

#### Create a docker environment file

Creates `.docker.env` with settings based on system OS. DO NOT add this file to source control.

This is used with docker containers based off from https://github.com/zimosworld/php-dev
```
eiger dei
```

<a name="helm"/>

#### Helm

Helm is a tool for managing Kubernetes charts.

```
eiger helm
```

<a name="help"/>

#### Help

List all available commands with brief description.

```
eiger help
```

<a name="kubectl"/>

#### Kubernetes CLI Client

Kubernetes CLI client

```
eiger kubectl
```

<a name="init"/>

#### Initialize eiger on a project. 

Creates a `.eiger` file in the directory the command is run, storing project specific configs for use with eiger commands (e.g composer). This file is best to be added to source control so everyone running the project will use the same configs.

```
eiger init
```

<a name="mysql"/>

#### MySQL

A simple SQL shell with input line editing capabilities.

```
eiger mysql
```

<a name="node"/>

#### Node

Node is a JavaScript runtime built on Chrome's V8 JavaScript engine.

```
eiger node
```

<a name="npm"/>

#### NPM

npm is a package manager for the JavaScript programming language.

```
eiger npm
```

<a name="plugin"/>

#### Plugin

Install and update third party plugins.

```
eiger plugin
```

<a name="terraform"/>

#### Terraform

Terraform is a tool for building, changing, and versioning infrastructure safely and efficiently.

```
eiger terraform
```

<a name="update"/>

#### Update

Update Eiger to the latest stable version.

```
eiger update
```

<a name="yarn"/>

#### Yarn

Yarn is a new package manager that replaces the existing workflow for the npm client or other package managers while remaining compatible with the npm registry.

```
eiger yarn
```