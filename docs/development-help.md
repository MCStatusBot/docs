# development help


## general info 

### modals

modals custom ids have the format `<command name>_<sub command name>_<dynmic info>`
this helps us redirect the modal to the related command or sub command file


## file structure 
### comand files

each command will have two main functions `chatInputCommand` (for slash commands) and `modalSubmit`

`chatInputCommand` is triggered when the base slash command has the same name as the command file

`modalSubmit` is triggered when its custom id following the format <command name> is the same as that command file name 


if a command has sub commands we will make a folder in ./subcomands with the same name as the command then each subcommand file will be put in that folder with the same name of the sub command then .js


