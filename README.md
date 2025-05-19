It is important to keep the files in this folder in sync with the GitHub repo

To initialize git submodule after the repo has been cloned:
```shell
git submodule update --init --recursive
```

To update submodule to latest from root repo:
```shell
git submodule update --remote --merge --recursive
```

Then you can cd into the submodule, and from there it will act as a normal github project, 
where you can push pull etc