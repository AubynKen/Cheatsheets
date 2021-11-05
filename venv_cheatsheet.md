## creating a venv

```shell
python3 -m venv [vertual environment name]
```

This creates a folder with the specified name in the current path. By convention, the virtual environment name is simply "venv".

```shell
python3 -m venv venv
```

## activating the venv

```shell
source ./venv/bin/activate
```

## Printing the current dependencies of the project

```shell
pip3 freeze
```

## writing the current dependencies of the project into a requirement file

```shell
pip3 freeze > [path_to_requirement]
```

eg.

```shell
pip3 freeze > requirement.txt
```

## deactivating the virtual environment

```shell
deactivate
```

## install the requirements

When you clone a project, the dependencies are usually not on git. If a requirement files is included, you may ask pip to install the requirments for you.

```shell
pip3 install -r requirements.txt
```

