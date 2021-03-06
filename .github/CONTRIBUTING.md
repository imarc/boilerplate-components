# Contributing to Boilerplate

## Bugs, Ideas, & Requests

Please [open issues](https://github.com/imarc/boilerplate-components/issues) on GitHub.

* When reporting bugs, please try to provide the browser, browser version, and your platform with the report.
* When submitting ideas or requests, be as specific as you can, as well as why it should be included within Boilerplate.

As with other GitHub projects, don't submit an issue for support requests and check for existing issues.

## Working on Boilerplate Locally

To work on Boilerplate locally,

1. Clone this repository.
2. Run `npm install` to install its dependencies.
3. Run `npm run watch` to run the front-end build and watch for file changes.
4. Additionally (in a separate terminal) run `npm run fractal start` to use Fractal's dev server and view the components within your browser.

While running like this, any changes made to source files will be picked up immediately. If you add new scss files, you will need to restart `npm run watch` but will not need to restart Fractal.


## Creating Pull Requests

Fork off of the appropriate branch:

* For work on the current, stable version of Boilerplate, fork off of `master`.
* For work on the upcoming or beta version of Boilerplate, fork off of `next`.

Submit a pull request and describe what your code is meant to do and why it should be included in Boilerplate; even better if you can reference articles or reasons for the change.


## Follow Code Conventions

Boilerplate follows [its own conventions](https://imarc-boilerplate.netlify.app/pattern-library/docs/abem.html) as closely as it can; make sure any code you submit does too. If there's areas you're not sure, fallback to Vue style guidelines and ABEM or BEM conventions, or [Imarc's Handbook.](https://handbook.imarc.com/)


## Versioning

The project loosely follows Semver - however defining what counts as a backwards-incompatible change in a front-end framework is somewhat ambiguous and left to the team's judgement.
