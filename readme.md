
It is recommended to add venv folder into .gitignore

Go to directory where you want to create virtual environment [venv_dir]
> Create virtual env:

    python -m venv [venv_dir]

> Activate the environment:

    .[venv_dir]\Scripts\activate

> while inside the venv, install all dependencies from requirement.txt:

    pip install --upgrade pip
    pip install -r [venv_dir]\requirements.txt

Reference: https://morioh.com/p/88d6fc714f52
