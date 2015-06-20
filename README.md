![angular-express-header](https://cloud.githubusercontent.com/assets/1859381/8266502/d94e93ce-1731-11e5-9b9d-9b9e58c5369f.png)

## Custom Bootstrap 3

[AngularJS Express](https://github.com/angular-express/angular-express) component to include a custom Bootstrap 3 stylesheet.

## Installation

To install the component:

```bash
$ ngx install less-custom-bootstrap3
```

No clue what the `ngx` command line tool is? Learn more about [AngularJS Express](https://github.com/angular-express/angular-express).

## How to use

- `_bootstrap.less`:
    - comment/uncomment the modules you wish to include
    - set `@bootstrap-path-to-less-files` to the path of the Bootstrap less files
- `_variables.less`:
    - configure the Bootstrap variables to fit your needs
- `styles.less`:
    - include `styles.css` as your stylesheet in your application
    - is automatically preprocessed, minified and autoprefixed by Angular Express

## License

[MIT](_LICENSE)
