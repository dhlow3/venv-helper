# venv-helper

> Simple helper script for activating a python virtualenv.

## Tested On
Ubuntu 16.04.2 LTS

## Requirements
* virtualenv: create virtual Python instances

## Setup
1. place venv in ~/bin or other directory in $PATH
2. sudo chmod 755 venv
3. mkdir ~/.virtualenvs
4. set up Python virtual environments in ~/.virtualenvs

## Usage
1. type ". venv environment_name" to activate said virtual environment
2. once virtual environment is active, type deactivate to deactivate

## Notes
* this script assumes you will be using ~/.virtualenvs for creating virtualenvs; change ~/.virtualenvs in script to preferred directory if needed
