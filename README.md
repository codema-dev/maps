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

To setup Jekyll locally via Docker run:

```bash
docker run --rm -it --entrypoint /bin/bash -v $(pwd):/srv/jekyll -p 4000:4000 jekyll/jekyll
bundle install
jekyll serve
```

