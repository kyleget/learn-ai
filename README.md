# AI Experimentation Project

This project is designed for experimenting with various AI techniques and models, using Python as the primary language. Dependency management is handled through `poetry`.

## Prerequisites

To ensure a clean and isolated environment, we recommend using `pyenv` to manage Python versions, and `pipx` to install Poetry globally. Since I'm developing on a Mac I will provide my preferred way.

### Step 1: Install XCode Command Line Tools
```
xcode-select --install
```

### Step 2: Install HomeBrew
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

brew update
brew upgrade
```

### Step 3: Install `pyenv` and `pyenv-virtualenv`

```bash
brew install pyenv pyenv-virtualenv
```

### Step 4: Install Python v3.12.0
```
pyenv install 3.12.0
```

### Step 5: Clone this repo
```
git clone git@github.com:kyleget/learn-ai.git
```

### Step 6: Create the virtualenv and install dependencies
```
pyenv virtualenv 3.12.0 learn-ai
poetry install
```

## Running the Script

Currently I am using Replicate to test some AI models.

```bash
python src/main.py
```
