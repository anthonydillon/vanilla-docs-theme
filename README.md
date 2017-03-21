# Vanilla Docs Theme

A Sass theme for documentation websites, based on [vanilla-framework](http://vanilla-framework.io).

## Local development

First, [install Docker](https://docs.docker.com/engine/installation/). Then run one of:

```bash
./run build  # Build the CSS
./run watch  # Auto-build the CSS when Sass files change
./run test   # Check the Sass files for syntax & style errors
./run clean  # Clean up generated files
```

### Using a local version of vanilla-framework

You can use the `./run` script to use NPM modules from a local folder on a one-time basis, instead of the modules declared in `package.json`.

This mechanism will allow you to, for example, use a local version of `vanilla-framework`:

``` bash
./run --node-module $HOME/project/vanilla-framework watch  # Build CSS dynamically, using a local version of vanilla-framework
```

