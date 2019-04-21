# techexcellence-site

[techexcellence.dev](https://techexcellence.dev) website for the Tech Excellence events.



## Developing the site

### Site structure

#### Directory structure

- `src`
  - Source data for the website contents
- `docs`
  - Output directory (automatically generated by Eleventy)
  - Don't put anything to `docs` directory manually, as it will be overwritten.
- `scripts`
  - Helper tools for local development


### Getting started

- Install Node.js (if you don't already have it on your computer)
- Install dependencies with npm by running following commands:

```sh
npm install
```

#### Development environment

```sh
npm run dev
```



#### Build output

```sh
npm run build
```


#### Trying Netlify locally

Netlify CLI allows testing of local development environment
with similar features as in hosted environment on Netlify.

```sh
netlify dev
```

More details:

- [Command Line Tools \| Netlify](https://www.netlify.com/docs/cli/)



## Dependencies

- [Node.js](https://nodejs.org/en/) (environment for running JavaScript-based tools)
- [Eleventy](https://www.11ty.io) (static site generator)


_Optional dependencies:_

- [netlify-cli](https://www.netlify.com/docs/cli/) for running Netlify tools locally


### npm dependencies

- [npm-run-all](https://github.com/mysticatea/npm-run-all) package
  - "A CLI tool to run multiple npm-scripts in parallel or sequential."
    - Motivation for the usage:
      - Simplify running multiple commands.
      - Cross platform support for running parallel tasks.
  - Documentation
    - [`npm-run-all`](https://github.com/mysticatea/npm-run-all/blob/master/docs/npm-run-all.md) command
    - [`npm-run-all`](https://github.com/mysticatea/npm-run-all/blob/master/docs/run-s.md) command to run given npm-scripts sequentially.
    - [`npm-run-all`](https://github.com/mysticatea/npm-run-all/blob/master/docs/run-p.md) command to run given npm-scripts in parallel.
- [cross-env](https://github.com/kentcdodds/cross-env)
  - Allow running scripts that set and use environment variables, across most platforms.
  - [Documentation](https://github.com/kentcdodds/cross-env#usage) about `cross-env` usage.
