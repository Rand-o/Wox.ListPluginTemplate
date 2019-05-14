# Wox.ListPluginTemplate
This is a template for making a simple list plugin

This make_list.py takes the List.csv and creates a config.json file to create a simple Wox plugin.

Simply create the list you would like in the csv, run the make_list.py, and you will have a config file for a plugin that will search your list. Hitting enter on the result will copy it to clipboard.

You could modify main.py to open a url or any other action instead of copying to clipboard.

Dependency: pyperclip
