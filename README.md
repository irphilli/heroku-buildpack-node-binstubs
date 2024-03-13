# Heroku Buildpack: Node Binstubs
Stubs Node binaries

## Description
The [Ruby Buildpack](https://github.com/heroku/heroku-buildpack-ruby) will install Node and Yarn binaries when they are not pre-installed. Following advice in [this PR](https://github.com/heroku/heroku-buildpack-ruby/pull/1405), this PR stubs `node` and `yarn` so that the Ruby buildpack can skip installation. This is useful if your project uses a different JavaScript runtime (i.e. bun) or you pull precompiled assets during the build process.

## License
Licensed under the MIT License. See [LICENSE.md](LICENSE.md) file.
