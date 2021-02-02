# ansible-playbook-skeleton

## Install

```
pip install -r requirements.txt
ansible-galaxy install -r requirements.yml
```

## Test

```
yamllint .
ansible-lint site.yml
```

## Run

```
ansible-playbook site.yml
```
