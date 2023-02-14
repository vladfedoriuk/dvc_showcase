- [Tutorial](https://www.youtube.com/playlist?list=PL7WG7YrwYcnDb0qdPl9-KEStsL-3oaEjg)

### Setup

- Repo init: 
```bash
git init
- ```
- Install dvc with pip:
```bash
pip install dvc
```

- DVC repo init:
```bash
dvc init
```

- Add some data to the repo:
```bash
mkdir data
# Add a large file to the data directory
ls -lh data
```

- Add the data to the dvc repo:
```bash
dvc add data
```
