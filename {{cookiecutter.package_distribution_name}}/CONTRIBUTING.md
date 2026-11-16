# Contributing to {{ cookiecutter.package_distribution_name }}

## Set up for development
Use Python 3.11 or later, create and activate a virtual environment, then run:
```sh
python -m pip install -e .
```

## Run the tests
```sh
python -c "from {{ cookiecutter.package_import_name }} import greet; print(greet('Hee'))"
```
Expected output: `Hello, Hee!`

## Send a change
Start from `main` and create a branch: `git switch main`, then `git switch -c add-usage`.
Make your change, then commit: `git add README.md` and `git commit -m "Add usage example"`.
Push the branch: `git push -u origin add-usage`.
On GitHub, open a pull request from `add-usage` into `main` and describe the change.
