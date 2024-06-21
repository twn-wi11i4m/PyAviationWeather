# Developer Note

Last update: 2024-06-21

## Create set_up

```
python3 setup.py sdist bdist_wheel
```

```
python3 setup.py bdist_wheel
```

## install the package locally
```
python setup.py develop
```

## Upload the package to PyPi
```
pip install --upgrade twine
```

```
twine upload dist/*
```



