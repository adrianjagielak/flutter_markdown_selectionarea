# flutter_markdown_selectionarea
[![pub package](https://img.shields.io/pub/v/flutter_markdown_selectionarea.svg)](https://pub.dartlang.org/packages/flutter_markdown_selectionarea)


A fork of [flutter_markdown](https://pub.dev/packages/flutter_markdown) package with added support for SelectionArea (see issue: [Support selecting text using SelectionArea #107073](https://github.com/flutter/flutter/issues/107073)).

## Installation

Add the following to your `pubspec.yaml` file:

```yaml
dependencies:
  flutter_markdown_selectionarea: any
```

Then, run 'pub get' to install the package.

## Getting Started

Using the Markdown widget is simple, just pass in the source markdown as a
string:

    Markdown(data: markdownSource);

If you do not want the padding or scrolling behavior, use the MarkdownBody
instead:

    MarkdownBody(data: markdownSource);

By default, Markdown uses the formatting from the current material design theme,
but it's possible to create your own custom styling. Use the MarkdownStyle class
to pass in your own style. If you don't want to use Markdown outside of material
design, use the MarkdownRaw class.
