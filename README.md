# 📜 Dart Quill Delta

An unofficial Dart port of [quill-js-delta](https://github.com/quilljs/delta/), originally written in TypeScript.

This package provides a Dart implementation of the [Quill Delta](https://www.npmjs.com/package/quill-delta) format, which is a JSON-based data structure used to describe rich-text documents. For more details, refer to the official [Quill Delta documentation](https://quilljs.com/docs/delta/).

## 📖 Background

Previously, this package was part of the [flutter_quill](https://pub.dev/packages/flutter_quill) package, but it has since been separated into its own package. It maintains the same versioning as `flutter_quill`. The [Flutter Quill](http://github.com/singerdmx/flutter-quill) project forked this package from [quill_delta](https://pub.dev/packages/quill_delta).

## ⚠️ Future Plans

While this package is currently stable and does not have any significant issues, there have been discussions about introducing a **breaking change** release. This would enhance type safety and enforce the use of standard Quill Delta attributes, unless custom attributes are explicitly included. Currently, we have no plans to implement this change, but if introduced, it may be released as a separate package.

## 🛠️ Supported Projects

The following projects support or use this package:

- [flutter_quill_to_pdf](https://pub.dev/packages/flutter_quill_to_pdf)
- [flutter_quill_delta_from_html](https://pub.dev/packages/flutter_quill_delta_from_html)
- [flutter_quill_delta_easy_parser](https://pub.dev/packages/flutter_quill_delta_easy_parser)
- [flutter_quill](https://pub.dev/packages/flutter_quill)
- [markdown_quill](https://pub.dev/packages/markdown_quill)
- [quill_markdown](https://pub.dev/packages/quill_markdown)
- [delta_markdown](https://pub.dev/packages/delta_markdown)
- [super_editor_quill](https://pub.dev/packages/super_editor_quill)

## 📚 Documentation

For detailed usage and API references, refer to the official [Quill Delta documentation](https://quilljs.com/docs/delta/).

## 📜 Acknowledgments

* The original package [quill_delta](https://pub.dev/packages/quill_delta)
* [Delta Delta](https://github.com/slab/delta)