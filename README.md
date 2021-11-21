# using-github-actions

## Steps

- Create a virtual environment

```bash
python3 -m venv .venv
```

- Activate the virtual environment

```bash
source .venv/bin/activate
```

- Install the requirements

```bash
pip install -r requirements.txt
```

- Run the code

```bash
flask run
```

- A GitHub actions pipeline has been set up, so on pushing the code, a CI/CD pipeline is triggered.
  