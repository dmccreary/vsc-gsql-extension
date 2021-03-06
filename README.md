# VSC GSQL Extension

This extensions provides syntax highlighting capabilities for TigerGraph's GSQL. This is mostly hacked together from:
* [alejandropoveda/atom-language-gsql](https://github.com/alejandropoveda/atom-language-gsql)
* [jmeekhof/gsql-vim](https://github.com/jmeekhof/gsql-vim)
* [fjblau/gsql-sublime](https://github.com/fjblau/gsql-sublime)

NOTE! This is still in development and has quite a bit of work and testing to do

## Features

Planned features are linting and auto-formatting. So far we have basic syntax highlighting working.

### Syntax Highlighting

![ConnComp Syntax ](./images/conn_comp_file.png)

![feature X](./images/pageRank_file.png)

`syntaxes/gsql.tmLanguage.json` contains a ported version of [alejandropoveda/atom-language-gsql](https://github.com/alejandropoveda/atom-language-gsql)'s specification of GSQL's language spec.

### Linting

TODO: Implement GSQL linting TypeScript from GraphStudio code given to me by @jonherke

## Release Notes

### 0.0.2

- Simplified accumulator regex to fix matching whole accumulator with type parameter
- Lowered required VSCode version to ^1.3.0
- Updated description to match README on the repository

### 0.0.1

- Initial release
- Basic syntax highlighting ported across from the Atom extension
