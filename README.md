Alpine Linux docker image with Node JS set up with "node" as entrypoint.

```bash
$ docker run --rm -it -v $(pwd):/data jimlei/alpine-nodejs -v
```

#### Alias
Add to `~/.bashrc`
```bash
alias node='docker run --rm -it -v $(pwd):/data jimlei/alpine-nodejs'
```

Load the changes
```bash
$ source ~/.bashrc
```

Usage
```bash
$ node -v
```
