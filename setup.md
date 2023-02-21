```bash
$ conda install twine

$ python setup.py sdist bdist_wheel

# python setup.py sdist upload
$ twine upload dist/*
```