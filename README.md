### Setting Up the Virtual Environment for Wetland Project Repository

To set up the virtual environment for this project:

1. Navigate to the project directory. </br>
cd path_to_the_wetlands_repository

2. **Create virtual environment**.</br>
python3 -m venv venv

3. **Activate the virtual environment.**</br>
source venv/bin/activate

4. **Install the required dependencies using the requirements file.** </br>
pip install -r requirements.txt

5. **Update requirements.** </br>
pip freeze > requirements.txt

6. **Remove the existing venv directory.**</b>
rm -rf venv

•	rm: This command stands for “remove.” It is used to delete files and directories in Unix-based systems like macOS and Linux.</b>
•	-r: This flag stands for “recursive.” It tells the rm command to delete directories and their contents, including all files and subdirectories inside.</b>
•	-f: This flag stands for “force.” It tells the rm command to remove files without prompting for confirmation, even if the files are write-protected.</b>

7. **Deactivate the virtual environment.**</br>
deactivate