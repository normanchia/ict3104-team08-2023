# ICT3104 Team 08 Project

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/normanchia/ict3104-team08-2023/blob/main/ict3104_team08.ipynb){:target="_blank"}

<a href="https://colab.research.google.com/github/normanchia/ict3104-team08-2023/blob/main/ict3104_team08.ipynb" target="_blank">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

This is the implementation of our ICT3104 Team Project done by:
| Student | Student ID |
| ------------- |:-------------:|
|Fabian Chua |2101506|
|Norman Chia |2100686|
|Pang Ka Ho |2102047|
|Shaun Sartra Varghese | 2102172 |
|Wang Qixian |2101751|

This repository includes the Jupyter notebook and instructions to run it. The project runs on Python 3.x.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Environment Setup](#environment-setup)
- [File Structure](#file-structure)
- [Updating Requirements](#updating-requirements)

## Installation

1. **Clone the Repository**:

    ```bash
    git clone https://github.com/normanchia/ict3104-team08-2023.git
    ```

2. **Install Requirements**:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Activate the Virtual Environment**:

    - On MacOS and Linux:

        ```bash
        source ict3104-venv/bin/activate
        ```

    - On Windows:

        ```bash
        .\ict3104-venv\Scripts\activate
        ```

2. **Start Jupyter Notebook**:

    ```bash
    jupyter notebook
    ```

3. **Open `ict3104_team08.ipynb`**: You can now navigate to the file in the Jupyter Notebook web interface and start using it.

## Environment Setup

The Jupyter Notebook contains commands to set up the environment. These commands are idempotent, meaning running them multiple times won't cause issues.

1. **Check Python Version**: Ensures you're running Python 3.x.
2. **Create and Activate Virtual Environment**: Isolates your project dependencies.
3. **Add venv to Jupyter**: Allows Jupyter to recognize your virtual environment.
4. **Install Requirements**: Installs packages from `requirements.txt`.
5. **Update Requirements**: You can freeze the current state of environment packages to `requirements.txt`.

## File Structure

- `README.md`: This file.
- `ict3104_team08.ipynb`: The main Jupyter Notebook.
- `ict3104-venv`: Directory for the virtual environment.
- `input_data`: Directory for input data (if any).
- `requirements.txt`: Required packages.

## Updating Requirements

If you install additional packages and want to update `requirements.txt`:

```bash
pip freeze > requirements.txt
```
