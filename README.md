# VVV ES6 site template

For when you just need the nginx server and practically no PHP. Although PHP
is included for having AJAX or REST related stuff. Also a database is created
in case you need to do something sassy.

This is a good way to run your JS apps from the same vagrant as your VVV without
installing WordPress.

Instead of WordPress we install a simple PHP [directory lister](https://github.com/halgatewood/file-directory-list).

## Configuration

**Only configuration required**

```yaml
es6:
  repo: https://github.com/WPQuark/vvv-es6
  hosts:
    - es6.test
```

Then provision the box and you are done.

## Configuration Options

```
hosts:
    - foo.test
    - bar.test
    - baz.test
```
Defines the domains and hosts for VVV to listen on.
The first domain in this list is your sites primary domain.

```
custom:
    db_name: super_secet_db_name
```
Defines the DB name for the installation.

