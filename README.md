# astrowind-patched

## About

This is a patched version of the original [`onwidget/astrowind`][upstream]
repository. It contains patches sourced from (hopefully) yet to be accepted PRs.

## Current base

Usually based off the latest state of the [`main` branch][main-branch] of the
[`onwidget/astrowind`][upstream] repository.

Currently based off of commit [`3de3a1e`][base-commit].

## Included pull requests

* [#613: Update to Tailwind v4][pr-613]
* [#614: Fix imports from '../ui/' to '~/components/ui/'][pr-614]
* [#615: Implement properties for `Note` component][pr-615]
* [#616: Use `Item` type definition for `items` property of `Steps` type][pr-616]
* [#617: Remove extraneous references to non-existing `highlight` css class][pr-617]

## ~~Setting remotes~~

The `upstream` remote is used for pulling updates from the original
[`onwidget/astrowind`][upstream] repository, while the `origin` remote is used
for pushing changes back to the forked repository.

```bash
# Official upstream:
git remote add upstream https://github.com/onwidget/astrowind.git

# For PR #613:
git remote add keithce https://github.com/keithce/astrowind-tailwindv4.git

# For PR #614, #615, #616 and #617:
git remote add romainpi https://github.com/romainpi/astrowind-tailwindv4.git
```

## Checking out PRs with `github-cli`

```bash
gh pr checkout https://github.com/onwidget/astrowind/pull/613
gh pr checkout https://github.com/onwidget/astrowind/pull/614
gh pr checkout https://github.com/onwidget/astrowind/pull/615
gh pr checkout https://github.com/onwidget/astrowind/pull/616
gh pr checkout https://github.com/onwidget/astrowind/pull/617
```

## Original README.md

Can be found [here](README.astrowind.md).

[upstream]: https://github.com/onwidget/astrowind
[main-branch]: https://github.com/onwidget/astrowind/tree/main
[base-commit]: https://github.com/onwidget/astrowind/commit/3de3a1e68623f0ce8f5a4ed7f0b245f5646c9e47
[pr-613]: https://github.com/onwidget/astrowind/pull/613
[pr-614]: https://github.com/onwidget/astrowind/pull/614
[pr-615]: https://github.com/onwidget/astrowind/pull/615
[pr-616]: https://github.com/onwidget/astrowind/pull/616
[pr-617]: https://github.com/onwidget/astrowind/pull/617

