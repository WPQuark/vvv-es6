# VVV ES6 site template

For when you just need the nginx server and practically no PHP. Although PHP
is included for having AJAX or REST related stuff.

This is a good way to run your JS apps from the same vagrant as your VVV without
installing WordPress.

## Configuration

**Only configuration required**

```yaml
es6:
  repo: https://github.com/Varying-Vagrant-Vagrants/custom-site-template
  hosts:
    - es6.test
```

Then provision the box and you are done.
