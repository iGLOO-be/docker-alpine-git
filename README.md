
# alpine-git

Simple container for `git` based on `alpine:3.4`. Automated build: [`igloo/alpine-git`](https://hub.docker.com/r/loicmahieu/alpine-git/).

```sh
docker run --rm -v $(pwd):/git igloo/alpine-git status
```

Or even...
```sh
alias git="docker run -ti --rm -v $(pwd):/git igloo/alpine-git"
git status
```
