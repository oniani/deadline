# Nero
[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/oniani/Nero/blob/master/LICENSE/)
![python 3_+](https://img.shields.io/badge/Python-3+-green.svg)

## Few words about Nero
**Nero** is a tiny app which runs in the terminal and helps organize tasks. It is copyright and cost free and is built using nothing but **Python**.

## Why another task management app?
Terminal is the core app for the software development. In theory, one could do virtually anything using nothing other than a *UNIX terminal* or *Windows Powershell*. We all have some tasks while programming or working at the computer. Most of people use apps like *Trello*, *Todoist*, etc. which help them manage tasks. Yet, these apps require opening browser or some sort of app store and installing them. Then one has to register and share his/her data with the company which created the app. Finally, none of them run in terminal and switching between windows is usually very discomforting (not to mention the fact that one still has to pay for most of them).

## Getting started
Since **Nero** is not a package, it is not available on [PyPI](https://pypi.org/). Yet, installation is still very simple and straightforward. The best way to have **Nero** set up is to download it from the **source**. Open the terminal and run the following commands:

```sh
cd
git clone https://github.com/oniani/nero.git
```

After cloning the repository, run the app by executing the following commands:

```sh
cd nero
python3 nero.py
```

## Nero philosophy
**Nero** is based on a simple philosophy: *where there is a task, there also is a deadline*.

## Usage and functionality
**Nero** has a very simple interface which is just a list of tasks with corresponding deadlines.

This is the list of available functionalities:
- `help` - shows a manual for the commands
- `license` - shows the license of the app
- `ls` - list all tasks
- `ls --ttl` - list titles only
- `ls --ddl` - list deadlines only
- `add` - add a task
- `rm` - remove a task by its index
- `clear` - clear the terminal window
- `h` - show command history for the current session
- `q` - quit and save my edits
- `!q` - quit and DO NOT save my edits
- `FULL CLEAR` - erase all the tasks, this is the irreversible nuclear option

## How does it work?
**Nero** has a simple logic. Every task is stored in `CSV` file and the app either reads or writes to the file, depending on the command.

## Dependencies
**None** but **Python**
