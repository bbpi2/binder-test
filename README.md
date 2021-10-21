# binder-test
 testing the binder function of cloud hosting notebooks

We are testing two types of files:

1. Jupyter Notebooks
2. R notebooks

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/bbpi2/binder-test/HEAD)



### If `pip freeze` doesn't work

`pip freeze` can lead to [direct references](https://stackoverflow.com/questions/62885911/pip-freeze-creates-some-weird-path-instead-of-the-package-version), use the following to create `requirements.txt` instead:

`pip list --format=freeze > requirements.txt`

