### Setting Up the Virtual Environment for Wetland Project Repository

To set up the virtual environment for this project:

1. **Navigate to the project directory.** 
cd path_to_the_wetlands_repository

2. **Create virtual environment**.
python3 -m venv venv

3. **Activate the virtual environment.**
source venv/brin/activate

4. **Install the required dependencies using the requirements file.** 
pip install -r requirements.txt

5. **Update requirements.** 
pip freeze > requirements.txt

6. **Remove the existing venv directory.**
rm -rf venv </br>

•	rm: This command stands for “remove.” It is used to delete files and directories in Unix-based systems like macOS and Linux.</br>
•	-r: This flag stands for “recursive.” It tells the rm command to delete directories and their contents, including all files and subdirectories inside.</br>
•	-f: This flag stands for “force.” It tells the rm command to remove files without prompting for confirmation, even if the files are write-protected.</br>

7. **Deactivate the virtual environment.**
deactivate