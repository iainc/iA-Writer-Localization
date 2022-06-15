# iA Writer Localization

This repository contains iA Writer localization files.

## Corrections

We’ve used an app localization service to translate the apps into the languages we don’t speak. It’s difficult to translate apps well, and there are likely mistakes. We’d appreciate pull requests with corrections.

## New Languages

We know how exciting localizing your favorite app to your language can be (we’ve done a few bootleg translations back in the day). However, every language requires support and maintenance, and we must carefully consider whether we can commit to this on a case-by-case basis. Please [contact us][w+l] before adding new languages.

[w+l]: mailto:writer+localization@ia.net

## File Formats

### Apple Platforms

Strings files use a simple key-value structure:

```
/* Localization comment. */
"Key" = "Value";
```
    
Stringsdict file format is described in [Apple’s guide][stringsdict]. For the plural categories and rules for each language, see [CLDR Language Plural Rules][CLDR].

[stringsdict]: https://developer.apple.com/library/content/documentation/MacOSX/Conceptual/BPInternational/StringsdictFileFormat/StringsdictFileFormat.html
[CLDR]: http://www.unicode.org/cldr/charts/latest/supplemental/language_plural_rules.html

## Version Control

This repository uses [`git-flow`][git-flow]. Currently shipping versions are on `main`, and localizations in progress are on `develop`.

[git-flow]: https://danielkummer.github.io/git-flow-cheatsheet/

### Pull Requests

Please rebase pull requests on latest `develop` when sent.
