# adr.github.io

This is the source code of <https://adr.github.io>.
It is based on the [Chirpy](https://chirpy.cotes.page/) theme.

## Development

### Updating the theme

1. `git remote add chirpy-starter git@github.com:cotes2020/chirpy-starter.git`
2. `get fetch chirpy-starter`
3. `git merge chirpy-starter/main`

### Icons missing

Check if `assets/lib` is empty.
If it is, execute `git submodule init` and then `git submodule update`.

### Running jekyll via Docker

1. `docker run --rm -it -p 4000:4000 -v "C:\git-repositories\adr.github.io\adr.github.io:/tmp/adr" mcr.microsoft.com/devcontainers/jekyll:2-bullseye /bin/bash`
2. `gem install bundler && bundle install`
3. `bundle exec jekyll serve -H 0.0.0.0 -t`
4. Open web browser at <http://localhost:4000/>.
