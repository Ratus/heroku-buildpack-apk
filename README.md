# heroku-buildpack-apk

Add support for apk-based dependencies during both compile and runtime.

Added ability to also specify custom repositories through **:repo:** in `Apkfile` (see example below).

## Usage

This buildpack is not meant to be used on its own, and instead should be in used in combination with Heroku's [multiple buildpack support](https://devcenter.heroku.com/articles/using-multiple-buildpacks-for-an-app).

Include a list of apt package names to be installed in a file named `Apkfile`

