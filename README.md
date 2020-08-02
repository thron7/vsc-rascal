# rascal-basic README

VSCode extension for the [Rascal metaprogramming language](https://www.rascal-mpl.org/).

## Features

- Syntax highlighting (incomplete)

## Helpful commands

- `npx js-yaml syntaxes/rascal.tmLanguage.yml > syntaxes/rascal.tmLanguage1.json` -- create the .json from the .yml (VSCode needs Json, but Yaml is supposed to be easier to maintain)
    - (works the same the other way round if you flip the input/output files)
    - always re-create the .yml file from the .json before you are going to edit the .yml file (not guarantied to be always on level with the .json file)
- `vsce package` -- create the .vsix package for this extension
- `code --install-extension rascal-basic-0.0.1.vsix` -- install locally

## Release Notes

No releases yet.

### 0.0.1

No releases yet.
