# Create virtual environment

```
pyenv virtualenv 3.11.7 deep-learning-in-python
echo "deep-learning-in-python" > .python-version
```

# Install dependencies

Install pytorch following the instructions from https://pipenv.pypa.io/en/latest/indexes.html:
```
pip install pipenv
pipenv install numpy
pipenv install torch torchvision torchaudio --index=pytorch
```