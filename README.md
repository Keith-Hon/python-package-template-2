### python-package-template

## install build tools
pip install twine build

## build for distribution
python -m build

## create .pypirc for private repo

## upload to repo
twine upload -r private ./dist/* --config-file ./.pypirc
