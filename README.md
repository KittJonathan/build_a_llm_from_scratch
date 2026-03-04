# Set up the code environment

+ [Link to video](https://www.youtube.com/watch?v=yAcWnfsZhzo&list=PLTKMiZHVd_2IIEsoJrWACkIxLRdfMlw11&index=1)
+ [Link to github repo](https://github.com/rasbt/LLMs-from-scratch/tree/main/setup/01_optional-python-setup-preferences)

Check Python version on system: `python --version`

## Set up uv

`pip install uv`

Create the virtual environment
`uv venv --python=python3.10`

Activate the virtual environment
`source .venv/bin/activate`

Install package in virtual environment
`uv pip install torch`

Install all packages at once
`uv pip install -r requirements.txt`