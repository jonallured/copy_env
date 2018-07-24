# copy\_env

A simple script to automate the pattern of:

* copy `.env.example` to `.env`
* grab config from Heroku or Hokusai staging
* replace values in `.env` with Heroku or Hokusai values

## Install

The easiest way to install is via homebrew:

```
$ brew tap artsy/formulas
$ brew install copy_env
```

But as a simple script, it's also easy to just grab it and add to your PATH as
you see fit.
