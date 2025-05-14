# Install uv
pip install uv

# Create project
uv init langchain_projects

# Create virtual environment
uv venv

# Activate virtual environment
.venv\Scripts\activate

# Deactivate virtual environment
deactivate

# Add packages to virtual environment
uv add <package_name>

# Remove packages from virtual environment
uv remove <package_name>

# List packages in virtual environment
uv list

# Create a virtual environment named .venv in the current directory
uv venv

# Now install your packages
uv pip install -r requirements.txt
