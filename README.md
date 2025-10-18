## Setup
```bash
# ensure pyenv is installed, see https://github.com/pyenv/pyenv#installation

# install and activate Python with pyenv
pyenv install 3.14.0 -s
pyenv local 3.14.0

# verify Python version
python --version

# setup virtual environment
pyenv exec python -m venv .venv
source .venv/bin/activate

# upgrade packaging tools
pip install --upgrade pip setuptools wheel

# install packages
pip install -r requirements.txt
```

## Citation
If you found this code useful, please cite:
```bibtex
@article{wu,
  title={},
  author={},
  year={},
  journal={}
}
```

## License
This project is released under the MIT License (see `LICENSE`).

