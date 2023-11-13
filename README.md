## Sample CLI in python
Sample CLI in python to print information user

### Check current user for example
```bash
id
```

### Install package
```bash
pip install --user -e .
```


### Uninstall package
```bash
pip uninstall hr
```

### Use the CLI
```bash
hr --format=csv --path=./users.csv
hr --path=./users.json
hr
[
    {
        "name": "zulfikar4568",
        "id": 501,
        "home": "/Users/zulfikar4568",
        "shell": "/bin/zsh"
    }
]
hr --format=csv
name,id,home,shell
zulfikar4568,501,/Users/zulfikar4568,/bin/zsh
```