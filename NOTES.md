## Creating a Release (just some notes for me)

### Requirements

`python -m pip install build`
`python -m pip install twine`

### Creating a dist package

`python -m build`

### Uploading the dist package

`python -m twine upload dist/*`