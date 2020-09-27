### Setup

#### Python

This project uses [pipenv](https://pipenv-fork.readthedocs.io/en/latest/) to manage python venvs and dependencies.

##### MacOS
Use the following to install pipenv.
```
brew install pipenv
```

##### Windows
Follow the instructions listed at the pipenv website.


Once pipenv is installed, run the following to set up a Python venv and install the needed dependencies.
```
pipenv install --dev
```
To use this environment, just run
```
pipenv shell
```

#### Database
By default, this tooling is configured to connect to a Postgres database running on localhost. There is a docker-compose.yaml file
in this directory that will start a postgres server with the proper configuration.
