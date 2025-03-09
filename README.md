# Workshop on Robot Meets GNSS

This repository is powered by the template for CodeRefinery workshops.


### How to customize this template after you have created the repository

- Adapt `config.toml`:
  - adapt `base_url` (it should contain a trailing slash)
  - adapt `title`
  - adapt settings below `[extra]`
- Adapt schedule in `content/schedule.yaml`. Use times in UTC. The times and
  dates are automatically displayed in the local time zone of the browser.
- Check texts, e.g. communication page, that they represent the setup of the current workshop


### How this template works

This template is based on the [Zola](https://www.getzola.org/) static site engine.

To install Zola, follow:
- https://www.getzola.org/documentation/getting-started/installation/
- https://snapcraft.io/zola can be used for system that are not supported by default
- But you can also download the binary directly from [here](https://github.com/getzola/zola/releases)

Check that Zola is installed with `$ zola --version`.


### Local preview

```
$ zola serve --open
```
This will open in your default browser a rendered version of the template.
