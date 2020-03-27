# science-responds.github.io-source

![CI](https://github.com/science-responds/science-responds.github.io-source/workflows/CI/badge.svg)

To contribute, make a PR to this repository.

## Setup for local development

Visit [this page](https://jekyllrb.com/docs/installation/) for information about installing Ruby. 

<details><summary><h3> Docker setup (click to expand) </h3></summary>
If you use docker, the following line will build and serve the site locally:

```bash
docker run --rm -v "$PWD:/srv/jekyll" -p 4000:4000 -it jekyll/jekyll:3.8 jekyll serve
```

If you want to enable LiveReload (pages automatically reload when jekyll rebuilds after detecting changes), then use this instead:

```bash
docker run --rm -v "$PWD:/srv/jekyll" \
           -p 4000:4000 -p 35729:35729 \
           -it jekyll/jekyll:3.8 \
           jekyll serve --livereload
```
</details>

<details><summary><h3> RbEnv setup (recommended) (click to expand) </h3></summary>

You can and should use rbenv to manage multiple ruby versions. On macOS with homebrew, you'll want:

```bash
brew install rbenv
```

On other systems, you can usually find an easy way to install rbenv. This keeps your system Ruby clean. You'll need to run:

```bash
rbenv init
# Prints out instructions
```

and follow the instructions for your current shell. After you've installed rbenv on your system, use:

```bash
rbenv install 2.6.5
```

to get a current version of ruby. Then, inside the main website directory, run:

```bash
rbenv local 2.6.5
```

This will run the Ruby you just built whenever you enter this directory.


You'll want to install bundler too:

```bash
gem install bundle
```

(You may want to add `--user-install` here if you are not using rbenv. And if
you don't have permission to install, and you are using rbenv, this means you
forgot to set it up with `rbenv init`.)

</details>

### Running locally

The site is built with Jekyll, and is easy to run locally if you have Ruby.

To set up a "bundle" (local virtual environment in Python terms):

```bash
bundle install
```

Now, you can use `bundle exec` to run a command in the new environment you just created, such as:

```bash
bundle exec jeykyll serve
```

This will incrementally rebuild if anything changes in your directory. Exit with Control-C.

## Adding content

### Adding projects

The projects are in `_data/projects`.

The yaml format is:

```yaml
title: "The title"
description: |
  A multiline description with markdown syntax, indented two spaces.
resources:
  - "A yaml list of resources, with double quotes for safty (starting with a markdown link is not valid yaml without quotes)"
needs: |
  A multiline description with markdown syntax, indented two spaces.
tags:
  - ad
  - ds
  - dv
  - ml
  - other
  - wd
involve:
  A multiline description with markdown syntax, indented two spaces. Often a markdown list.
```

### Adding publications and articles

The publications are in `_data/publications`, and articles are in `_data/articles`.

The yaml format is:

```yaml
title: "Something Interesting"
link: https://www.biorxiv.org/content/10.1101/2020.01.31.929547v1
date: 2020-01-31
type: publication
authors: F. Lastname et al
```

The name should start with the date, followed by an underscore and the author name or source, such as `20200131_lastname.yml`.

### Adding events

The events are in `_data/events`

The yaml format is:

```yaml
type: hackathon
link: https://www.google.com
date: 2020-01-31
title: My Title
```

Types are `hackathon`, `conference`.
