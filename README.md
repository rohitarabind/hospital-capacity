# Initial Readme

# Installing dependencies using `pipenv`

URL:
https://packaging.python.org/tutorials/managing-dependencies/
https://towardsdatascience.com/how-to-use-pipenv-with-jupyter-and-vscode-ae0e970df486

commands run:
`$ pip install --user pipenv`

## Initial install process (what I did)

1. First, create a Pipenv environment.
2. Make sure to navigate into the correct directory.
3. Use `pipenv install <packages>` to install all your packages.
4. Then use `pipenv shell` to activate your shell.
5. Then use `pipenv install jupyter` and afterward `pipenv run jupyter notebook`.

specifically:

1. `$ pipenv install simpy`
2. `$ pipenv install pandas`
3. `$ pipenv install matplotlib`
4. `$ pipenv install jupyter`

`pandas` is huge so the pipfile takes a while to lock.

## What you have to do to use this

These steps above generate the `Pipfile` and `Pipfile.lock`. When they're set up already, all you have to do is
to navigate to the folder and run:
`$ pipenv install`
and it'll run everything.

From that point, you'll want to run the `pipenv`-controlled Jupyter Notebook, and not your own environment's
Jupyter notebook.
