
## Usage
For generating the documents locally use commands below from the root folder. 

```shell
# install dependencies
cd dragonfly_iesve
pip install -r dev-requirements.txt

# generate rst files for modules
sphinx-apidoc -f -e -d 4 -o ./docs ./dragonfly_iesve
# build the documentation under _build/docs folder
sphinx-build -b html ./docs ./docs/_build/docs
```
