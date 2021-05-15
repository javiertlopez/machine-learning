# machine-learning

## Dependencies

### Create an environment

```bash
python3 -m venv venv
```

### Activate an environment

```bash
. venv/bin/activate
```

### Install dependencies
```bash
pip3 install -r requirements.txt
```
### Upgrade dependencies
```bash
pip3 list --outdated --format=freeze | grep -v '^\-e' | cut -d = -f 1 | xargs -n1 pip3 install -U 
```

### Freeze requirements

```bash
pip3 freeze > requirements.txt
```

