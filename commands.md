install

venv
``
sudo apt install python3.10-venv
python3 -m venv ~/.venvs/llm
source ~/.venvs/llm/bin/activate
``

or pyenv
``
pyenv virtualenv 3.13.5 llm-learn
pyenv global llm-learn
``

libs
``
pip install tqdm notebook==7.1.2 openai elasticsearch==8.13.0 pandas scikit-learn ipywidgets
pip install minsearch
```

up/down
``
./elastic-up.sh
./elastic-down.sh
``
