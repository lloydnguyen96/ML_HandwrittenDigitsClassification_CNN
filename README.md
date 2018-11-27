# Step 1: Create python virtual environment
python -m venv env
# Step 2: Activate python virtual environment
env\Scripts\activate
# Step 3: Install ipykernel library in env environment
pip install ipykernel
# Step 4: Create ipykernel kernel to run jupyter from env environment
ipython kernel install --user --name=projectname
# Step 5: Install all dependencies
pip install -r requirements.txt
# Step 6: Open cmd, type
jupyter notebook
# Step 7: Open .ipynb files with ipykernel
# Anywhere you update or install new packages, please update the requirements.txt file
# End!!!
