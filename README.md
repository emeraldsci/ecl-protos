`ecl-protos` is a Git repo hosting shared proto files, designed to be included as a Git submodule in ECL codebases.

To initialize the git submodule after the upstream repo has been cloned:
```shell
git submodule update --init --recursive
```

To update the git submodule to latest from the upstream repo:
```shell
git pull --recurse-submodules
```

Then you can cd into the submodule, and from there it will act as a normal github project, 
where you can push pull etc
