# Stanford Docster

Looking for an easy way to write and host documentation on github pages? [Research Applications Docster](https://researchapps.github.io/template-jekyll-github) can get you up and running quickly, because you only need a Github account and an ability to write markdown text files.

## Features
* Nice syntax highlighting
* dynamic multi-level navigation

## QuickStart
Clone, make changes to files in [_entries](_entries) and [_config.yml](_config.yml) and push to Github! More specifically:


      git clone https://github.com/stanford-rc/template-jekyll-github
      cd template-jekyll-github


1. Option 1: Docker

Download [docker](https://docs.docker.com/engine/installation/), download the template to a folder, and run a container:


      docker run --label=jekyll --volume=$(pwd):/srv/jekyll -it -p 127.0.0.1:4000:4000 jekyll/jekyll


Then go to `127.0.0.1:4000` in your browser to see the site! Make changes, add the files to your github folder (either the `master` branch of your user or organization repo (a repo named in the format `myusername.github.io`) or the `gh-pages` branch of another repo, which will appear at `myusername.github.io/reponame`.

2. Option 2: Run Locally


Install [Jekyll](https://jekyllrb.com/docs/installation/) and then run with:


      jekyll serve


### Documentation
Check out the [demo](https://researchapps.github.io/template-jekyll-github) for complete documentation, and for feature requests please submit an [issue](https://github.com/researchapps/template-jekyll-github/issues).


