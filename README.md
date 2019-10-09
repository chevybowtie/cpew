# What does this do?

All eclipse workspace settings are saved as a plain text in the workspace directory. So if you want to create new workspace, this will help.

## Linux version

To use the script, save it somewhere, make it executable (`chmod +x new-workspace.sh`) and run it either in interactive mode

`./new-workspace.sh -i`

where it will ask you the details, or with paths to your workspaces (the new workspace directory will be created for you, just specify the path)

`./new-workspace.sh old-workspace new-workspace`

The script will create new workspace directory and copy the relevant settings from your old workspace.
