# Exercise: Upload to PyPi

you'll practice uploading a package to PyPi.

The Python package is located in the folder 5_exercise_upload_to_pypi.

You need to create three files:

- setup.cfg

- README.md

- license.txt

- You also need to create accounts for the pypi test repository and pypi repository.

## Commands to upload to the PyPi test repository

```

twine upload --repository-url https://test.pypi.org/legacy/ dist/*

pip install --index-url https://test.pypi.org/simple/ distributions


```

## Command to upload to the PyPi repository

```

twine upload dist/*

pip install distributions

```