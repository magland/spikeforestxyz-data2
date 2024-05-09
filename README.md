# spikeforestxyz-data2

## This datalad repo was configured as follows

```
datalad create --force .
git add README.md .gitignore .flake8
git commit -m "initial"
```

To remove stuff (e.g. all recordings):

```
datalad drop recordings/*
datalad remove recordings/*
```

Note that there are still remnants in the git-annex branch. Need to figure out
how to remedy this.
