# Inventures

The fourth incarnation of the Inventures website.

The Inventures website is a responsive static website hosted on Github Pages and lives at http://inventures.fund. It has some general information about the Inventures I and II funds.

## Limitations

- We can't use SSL on Github Pages when using a custom domain.
- We can't use HAML since Github Pages does not support extensions.

## clone the repo
```bash
git clone git@github.com:spreds/inventures.git
```

## Ruby version
2.3.1

```bash
rbenv install 2.3.1
rbenv local 2.3.1
```

## Get started

```bash
gem install jekyll bundler
bundle install
bundle exec jekyll serve
```
