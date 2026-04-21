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
b) an ssh login for github, following the instructions:
   https://github.com/Weber-Group/How-To-Git-SLAC
