`ecl-protos` is a Git repo hosting shared proto files, designed to be included as a Git submodule in downstream projects. It is important to keep the files in this folder in sync with the GitHub repo.

To initialize git submodule after the repo has been cloned:
```shell
git submodule update --init --recursive
```

To update submodule to latest from root project repo:
```shell
git pull --recurse-submodules
```

Then you can cd into the submodule, and from there it will act as a normal github project, 
where you can push pull etc
