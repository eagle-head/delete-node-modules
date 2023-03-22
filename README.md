# Delete Node Modules Script

This Shell script is designed to find and delete `node_modules` folders within the specified directory and its subdirectories. Once a `node_modules` folder is found and deleted, the script will not search deeper within that folder.

## Requirements

- Bash (Available on Linux and macOS by default, or use Git Bash on Windows)

## Usage

1. Clone this repository or download the `delete_node_modules.sh` script to your local machine.

2. Open a terminal and navigate to the directory containing the `delete_node_modules.sh` script.

3. Make the script executable by running the following command:

```bash
chmod +x delete_node_modules.sh
```

4. Run the script by providing the path to the folder you want to search:

```bash
./delete_node_modules.sh /path/to/your/folder
```

5. The script will search for node_modules folders and delete them. At the end of the execution, it will print a list of absolute paths where the node_modules folders were deleted.

## Disclaimer

Please use this script at your own risk. It is recommended to create a backup of your files before running the script to avoid any data loss in case of unexpected issues.
