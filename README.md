### Setting Up the Virtual Environment for Wetland Project Repository

To set up the virtual environment for this project:

1. Navigate to the project directory: </br>
cd path_to_the_wetlands_repository

2. Create virtual environment</br>
python3 -m venv venv

3. Activate the virtual environment </br>
source venv/bin/activate

4. Install the required dependencies using the requirements.txt file.</br>
pip install -r requirements.txt

5. Update requirements.txt </br>
pip freeze > requirements.txt

6. Remove the existing venv directory</b>
rm -rf venv

### Deactivating the Virtual Environment

Once you're finished working in the virtual environment, deactivate it by running:</br>
deactivate