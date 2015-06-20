![angular-express-header](https://cloud.githubusercontent.com/assets/1859381/8266502/d94e93ce-1731-11e5-9b9d-9b9e58c5369f.png)

## Custom Bootstrap 3

[AngularJS Express](https://github.com/angular-express/angular-express) component to include a custom Bootstrap 3 stylesheet.

## Installation

To install the component:

```bash
$ ngx install less-custom-bootstrap3
```

By default, the component is configured to include LESS files from a jspm installed Bootstrap.

So you should either run:

```bash
$ jspm install bootstrap-less
```

or update the `@bootstrap-path-to-less-files` variable in `_bootstrap.less` to make it point to the folder with LESS files.

No clue what the `ngx` command line tool is? Learn more about [AngularJS Express](https://github.com/angular-express/angular-express).

## How to use

Edit the LESS files to your liking:

- `_bootstrap.less`:
    - comment/uncomment the modules you wish to include
    - set `@bootstrap-path-to-less-files` to the path of the Bootstrap less files
- `_variables.less`:
    - configure the Bootstrap variables to fit your needs
- `styles.less`:
    - add styles
    - import styles from other components
    
and then include the styles in your markup:

```javascript
link(rel="stylesheet", type="text/css", href="components/less-custom-bootstrap3/styles.css")
```

`styles.less` is automatically preprocessed, minified and autoprefixed by Angular Express to `styles.css`.

## License

[MIT](_LICENSE)
