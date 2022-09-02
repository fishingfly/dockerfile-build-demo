# Build From Git Repository
we can streamline this docker build process by building directly from the Git repository.
```
docker build -t automatron https://github.com/fishingfly/dockerfile-build-demo.git#main
```
`#mian` is used to specify the branch of remote repository