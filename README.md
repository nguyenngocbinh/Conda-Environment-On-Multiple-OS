# Conda-Environment-on-RedHat8.6

In this workflow:

    - It triggers on every push to your repository.
    - It sets up Miniconda.
    - It creates the Conda environment using the environment.yml file.
    - It activates the Conda environment.
    - If you have additional dependencies to install, you can do so using conda install.
    - it runs your Python script (replace your_script.py with the actual script you want to execute).
    - Finally, save the environment specification to another branch (e.g., "environment-branch")
