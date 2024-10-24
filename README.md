# DVC (Data Version Control)

## Initialize workspace

```bash
git init
dvc init
```

## first register data

```bash
dvc add {directory or file}
git add {directory or file}.dvc .gitignore
git commit -m "commit message"
```

## update data

```bash
dvc add {directory or file}
git add {directory or file}.dvc
git commit -m "commit message"
```

## change data version

```bash
git checkout {commit}
dvc checkout
```

## add remote storage

```bash
git remote add -d {storage name} {storage path}
dvc push
```

## pull remote storage

```bash
git clone {git url}
dvc pull
```
