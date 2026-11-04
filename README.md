# James

Captain hook's hooks.

## Installation

Add to `composer.json`

```json lines
"repositories": [
    {
        "type": "vcs",
        "url":  "git@github.com:mlbrgn/james.git"
    }
],
```

Then `composer require --dev mlbrgn/james:dev-main`

And add also
```json lines
"post-update-cmd": [
  "vendor/mlbrgn/james"
],
```
