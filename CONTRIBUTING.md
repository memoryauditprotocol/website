# Contributing

Thanks for your interest in the Memory Audit Protocol website.

## How to contribute

Fork this repository, make your changes on a branch, and open a pull request. You do not need write access to this repository. All changes to `main` go through pull request review by a project maintainer.

The site is a single self-contained `index.html` with no build step and no dependencies. Please keep it that way: no external scripts, stylesheets, fonts, or trackers.

## Linting and formatting

This repo has dev-only tooling (Prettier, Stylelint, HTMLHint) to check and format `index.html`. It has no effect on the deployed site — it's just for contributors, and requires Node.js.

```sh
npm install
npm run lint      # HTMLHint + Stylelint
npm run format    # reformat index.html with Prettier
```

Please run `npm run format && npm run lint` before opening a pull request.

## Licensing of contributions

By opening a pull request you agree that your contribution is licensed under the [Apache License 2.0](LICENSE), the same license as this repository.

If you are contributing on behalf of an employer, please make sure you have the authority to license the work under those terms.

## Trademarks

The Apache License 2.0 grants no rights to the "Memory Audit Protocol" name or marks. Contributing does not grant any right to use them.
