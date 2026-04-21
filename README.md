Step 1:
```bash
pip install nbdime
```
```bash
pip install nbstripout
```


Step 2:
```bash
nbdime config-git --enable
```
```bash
nbstripout --install
```

Trying out a nonlocal version. use `--global` in the command above to set globally.

For push authorization one needs
a) being added as a collaborator to the respective github repository
b) a (personal authentification token)  PAT set up on github:
https://github.com/settings/personal-access-tokens
c) use the PAT as password for the first git push
