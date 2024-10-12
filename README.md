### Setting Up the Virtual Environment for Wetland Project Repository

To set up the virtual environment for this project:

1. Navigate to the project directory:
```terminal
   cd path_to_the_wetlands_repository

2. Create virtual environment
    python3 -m venv venv

3. Activate the virtual environment
    source venv/bin/activate

4. Install the required dependencies using the requirements.txt file.
    pip install -r requirements.txt

5. Update requirements.txt 
    pip freeze > requirements.txt

### Deactivating the Virtual Environment

Once you're finished working in the virtual environment, deactivate it by running:

```terminal
deactivate