# python-nvim

Docker with fisadev nvim configuration (lot of python, autocompletition, fuzzy finder, debugger, ...)

Configuration from [fisadev/fisa-nvim-config](https://github.com/fisadev/fisa-nvim-config "fisa-nvim-config"), a nvim configuration for the modern pythonista.

![](https://raw.githubusercontent.com/FedeG/python-nvim/gh-pages/images/demo.gif)

## Installation and documentation
- [Documentation](https://fedeg.github.io/python-nvim/ "github page").
- [Image in docker hub](https://hub.docker.com/r/fedeg/python-nvim/ "docker hub").

### Badges

##### Python 3 (latest, 3, 3.5, 3.6.3):
[![](https://images.microbadger.com/badges/version/fedeg/python-nvim:latest.svg)](http://microbadger.com/images/fedeg/python-nvim:latest "Get your own version badge on microbadger.com")  [![](https://images.microbadger.com/badges/image/fedeg/python-nvim:latest.svg)](http://microbadger.com/images/fedeg/python-nvim:latest "Get your own image badge on microbadger.com")

##### Python 2 (2, 2.7, 2.7.12):
[![](https://images.microbadger.com/badges/version/fedeg/python-nvim:2.7.12.svg)](http://microbadger.com/images/fedeg/python-nvim:2.7.12 "Get your own version badge on microbadger.com")  [![](https://images.microbadger.com/badges/image/fedeg/python-nvim:2.7.12.svg)](http://microbadger.com/images/fedeg/python-nvim:2.7.12 "Get your own image badge on microbadger.com")

### Installation instructions:
A simple bash alias
```bash
alias python-nvim='docker run -it --rm -v $(pwd):/src --workdir /src fedeg/python-nvim:latest'
```

### Install for specific python version:
Change docker image tag

#####  Python 3 (latest, 3, 3.6, 3.6.3):
```bash
alias python-nvim='docker run -it --rm -v $(pwd):/src --workdir /src fedeg/python-nvim:3'
```

### Use instructions:
```bash
python-nvim
```
