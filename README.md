# single-line-commands
This repository basically lists commands that can be executed with only one line of input.

## Function: Displays files and directories hierarchies expressed in tab characters.
### Command
```
tree -F|sed -e "s/[ │├──└]/ /g" |sed -e "s/    /\t/g; s/\*//g">../tree.txt
```
### Example
* Output text content

![Example: Output text content](images/tree_txt_image.png)

### Notes
* This can be used on Linux/Unix systems.
* The tree command must be installed beforehand.
  
