# Soda example

## Prerequisite
* Make sure to have python 3.8 or greater installed

## Setting up a virtual environment and installing Soda

```bash
    python -m venv .venv
    source .venv/bin/activate
    pip install --upgrade pip
    pip install -i https://pypi.cloud.soda.io soda-core-snowflake

```

## Execution

Go to config.yml and change the user_name and account_number

```bash
    soda scan -d my_data_source -c config.yml checks.yml
```