# Create virtual environment

```
pyenv virtualenv 3.11.7 deep-learning-in-python
echo "deep-learning-in-python" > .python-version
```

# Install dependencies

Install pytorch following the instructions from https://pipenv.pypa.io/en/latest/indexes.html:
```
pip install pipenv
pipenv install numpy pandas
pipenv install torch torchvision torchaudio torchtext --index=pytorch
pipenv install torchmetrics
pipenv install matplotlib
pipenv install pillow
pipenv install nltk
pipenv install scikit-learn
pipenv install transformers sentencepiece
```