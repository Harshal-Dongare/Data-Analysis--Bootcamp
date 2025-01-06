## Command to set up vs code environment

```bash
conda create -p venv python==3.12.8
```

> Note: <font color="Yellow">This command will only work if you have checked the **Environment Variables** option while installing Anaconda.</font>

-   venv : name of environment
-   python : version of python
-   -p : path of environment

> After running above command **`venv`** folder will be created in the directory.

## To activate an environment run below command

```bash
conda activate venv/
```

## To run a code in notebook run below command

```bash
pip install ipykernel
```
