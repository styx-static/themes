# Styx themes

This repository tracks all the styx themes and is used to perform maintenance tasks:

- Updating themes screenshots: `scripts/themes`
- Updating themes demo sites:  `scripts/demo-sites`

## Updating all the themes

```
$ git submodule update --recursive --remote --force 
```

## Adding a new theme

```
$ THEME=showcase git submodule add git@github.com:styx-static/styx-theme-${THEME}.git themes/${THEME}
```
