# The Carpentries Workbench Test Translation

This lesson is a test of translating a [The Carpentries Workbench][workbench] lesson using [crowdin].

The crowdin project is located at <https://crowdin.com/project/crowdin-rmd-test>. It is a public project, so anybody can contribute to translations.

## Rendering the translated lesson

There is currently only one language being translated, Japanese.

To render the translated lesson, first switch to the `l10n_main` branch:

`git switch l10n_main`

Then start R and use `{sandpaper}` to build the lesson:

```r
library(sandpaper)
build_lesson("ja")
```

The rendered lesson will appear in `ja/site/`.

[workbench]: https://carpentries.github.io/sandpaper-docs/
