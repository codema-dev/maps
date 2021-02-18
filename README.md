# Dublin Energy Webmaps

Source files for "Dublin Energy Webmaps" - a website containing interactive Dublin energy-related webmaps.

Available at: https://codema-dev.github.io/dublin-energy-webmaps/

This website was created by the [codema-dev](https://github.com/codema-dev/) team as part of the SEAI RD&D funded [Dublin Region Energy Masterplan project](https://www.codema.ie/projects/local-projects/dublin-region-energy-master-plan/).

<a href="https://www.codema.ie/">
  <img src="docs/img/logos/codema.png" width="250px" style="padding-right:30px">
</a>

<a href="https://www.seai.ie">
    <img src="docs/img/logos/seai.png" width="275px"> 
</a> 


---


## Local Development

To setup `mkdocs-material` locally:

```bash
git clone https://github.com/codema-dev/dublin-energy-webmaps
cd dublin-energy-webmaps
```

and ...
### a. Docker

- Install [docker](https://www.docker.com/get-started)

- From your terminal run:

```bash
docker run --rm -it -p 8000:8000 -v ${PWD}:/docs squidfunk/mkdocs-material
```

or ...
### b. Pip

- Install Python via [miniconda](https://docs.conda.io/en/latest/miniconda.html) (recommended) or from [python.org](https://www.python.org/downloads/)

- From your terminal run:

```bash
pip install mkdocs-material
```