# To clone the repository and run the example pipeline

```bash
git clone --recurse-submodules git@github.com:denisrosset/yarara-test.git
cd yarara-test
cd Python
python -m venv .venv
poetry install
poetry run python trigger_yarara_harpn.py -b 1 -e 14
```
