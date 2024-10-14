# Transformer-based Translation Model

This project implements a transformer-based translation model using PyTorch. It can be configured to translate between different language pairs.

## Setup

This project uses Poetry for dependency management. To get started:

1. Install Poetry if you haven't already:

    ```bash 
   curl -sSL https://install.python-poetry.org | python3 - 
    ```

2. Clone the repository and navigate to the project directory:

    ```bash 
    git clone <repository-url>
    cd <project-directory>
    ```
3. Install the project dependencies:

    ```bash 
    poetry install
    ```
4. Activate the virtual environment:

    ```bash 
    poetry shell
    ```



## Configuration

The project uses a configuration file to set various parameters, including the source and target languages. To modify the configuration:

1. Open the config.py file.

2. Locate the get_config() function.

3. Modify the configuration dictionary as needed. For example, to change the language pair:
    ```bash 
    config = {
        "lang_src": "en",
        "lang_tgt": "fr",
        # ... other configuration options ...
    }
    ```

## Training

```bash 
poetry run python train.py
```
