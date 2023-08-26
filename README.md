```
conda create -p venv python==3.8 -y
```

```
git init
```

```
touch .gitignore
```

```
pip install -r requirements.txt
```

```
dvc init
```

```
dvc repro
```

```
dvc dag
```

```
dvc add data/
```

```
git add data.dvc && git commit -m "add data file"
```

```
dvc remote add -d myremote /tmp/dvcstore
```

```
dvc push or dvc push -r myremote
```

```
https://dvc.org/doc
```