# Command_Line_To_Do_App

#In this project, I learned how to:

1-Build a to-do application with Python and Typer.
2-Add commands, arguments, and options to the to-do application using Typer.
3-Test the to-do application using Typer’s CliRunner and pytest in Python.
4-Practicing some additional skills, such as working with JSON files using Python’s json module and managing configuration files with Python’s configparser module.

# How to use The Application

1-Download the application's source code to Command_Line_To_Do_App-master/ directory.
2-Open the CLI and cd to the above directory.
3-Create a Python virtual environment and activate it through the following commands:

On Linux:
```bash
$ cd Command_Line_To_Do_App-master/
$ python -m venv ./venv
$ source venv/bin/activate
(venv) $
```
On Windows:
```bash
c:\> cd Command_Line_To_Do_App-master/
c:\> python -m venv venv
c:\> venv\Scripts\activate.bat
```
4- Install the dependencies:
```bash
(venv) $ python -m pip install -r requirements.txt
```
5-Initialize the application:
```bash
(venv) $ python -m rptodo init
```

##Usage
Once you've downloaded the source code and run the installation steps, you can run the following command to access the application's usage description:
```bash
$ python -m rptodo --help
Usage: rptodo [OPTIONS] COMMAND [ARGS]...

Options:
  -v, --version         Show the application's version and exit.
  --help                Show this message and exit.

Commands:
  add       Add a new to-do with a DESCRIPTION.
  clear     Remove all to-dos.
  complete  Complete a to-do by setting it as done using its TODO_ID.
  init      Initialize the to-do database.
  list      List all to-dos.
  remove    Remove a to-do using its TODO_ID.
```

