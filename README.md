# cover_bot
A repository containing code developped for the course project of CISC 856: Reinforcement Learning - Winter 2022
Moving from a private repository to the submission code.


### Virtual Environment Setup
piptools - used to modify requirements.txt without dependency hassles.

```setup
pip install pip-tools
```

Steps: 

1. (Optional) To generate new requirements (after adding new requirement to requirements.in): 
*Note*: This requires that you install pip-tools, if you haven't installed pip-tools then 
please do `pip install pip-tools` to use the command below.

```sh
pip-compile
```

2. To setup virtual environment: 

```sh
python -m venv .venv
```

3. To activate virtual environment (unix): 
   
```sh
source .venv/bin/activate
```

4. To install requirements:

```sh
pip install -r requirements.txt
```

5. To deactivate virtual environment (unix):
```sh
deactivate
```


