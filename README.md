# Strojno učenje - project

## Contributors
```sh
Mislav Kocijan
Ivan Leverić
Mateo Martinjak 
```
## Instructions

1. Create and run virtual env (on Windows)

```sh
py -m venv env_ml
.\env_ml\Scripts\activate
```

2. Install requirements

```sh
pip install -r requirements.txt
```
3. Run notebook
```sh
jupyter notebook
```
4. Deactivate virtual env on the end (optional)
```sh
deactivate
```
* Small script for auto activate and run notebook (save it as .bat)
```sh
@echo off
cmd /k "cd /d .\env_ml\Scripts\ & activate & cd /d    ../../ & jupyter notebook"
```
