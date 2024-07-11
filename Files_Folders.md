# Files & Folders I/O
1. [File modes](https://github.com/vutran-space/Python_Note/blob/main/Files_Folders.md#file-modes)
2. [Reading a file line-by-line](https://github.com/vutran-space/Python_Note/blob/main/Files_Folders.md#file-modes)
3. [Iterate files (recursively)](https://github.com/vutran-space/Python_Note/blob/main/Files_Folders.md#file-modes)
4. Getting the full contents of a file
5. Writing to a file
6. Check whether a file or path exist
7. Replacing text in a file
8. Checking if a file is empty
9. Read a file between a range of lines
10. Copy a directory tree
11. Copying contents of one file to a dierent file


# File modes

```python
with open(filename, 'r') as f:
     f.read()
with open(filename, 'w') as f:
    f.write(filedata)
with open(filename, 'a') as f:
    f.write('\\n' + newdata)
````

```python
try:
	with open("fname", "r") as fout:
		# Work with your open file
except FileExistsError:
		# Your error handling goes here
````
# Reading a file line-by-line
```python
# Open the file for reading
with open('example.txt', 'r') as file:
    # Read each line in the file
    for line in file:
        print(line.strip())  # Use strip() to remove any leading/trailing whitespace
````
```python
try:
    # Open the file for reading
    with open('example.txt', 'r') as file:
        # Read each line in the file
        for line in file:
            print(line.strip())  # Use strip() to remove any leading/trailing whitespace
except FileNotFoundError:
    print("Error: The file was not found.")
except PermissionError:
    print("Error: You do not have permission to read the file.")
except Exception as e:
    print(f"An unexpected error occurred: {e}")
````

# Iterate files (recursively)

# Getting the full contents of a file

# Writing to a file

# Check whether a file or path exists

# Replacing text in a file

# Checking if a file is empty

# Read a file between a range of lines

# Copy a directory tree

#Copying contents of one file to a dierent file
