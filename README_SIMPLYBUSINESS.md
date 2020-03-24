## Create and Publish new version

After making moifications, you can publish a new version by doing

- Change version in `setup.py`

Then:

```bash
python setup.py bdist_wheel
twine upload --repository-url https://test.pypi.org/legacy/ dist/*
```