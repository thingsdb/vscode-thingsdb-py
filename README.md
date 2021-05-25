# Python string ThingsDB

We write Python Code with embedded ThingsDB code. Syntax highlighting for ThingsDB Code makes this a lot easier.

## Release Notes

### 0.0.1

Initial release.

## Installation

As the extension is in development, installation is only possible manually.

Install [node.js](https://nodejs.org/) and then then install the [vsce](https://www.npmjs.com/package/vsce) package:

```
npm install --global vsce
```

Clone the repository and open a terminal at the project root and execute the following command:

```
vsce package
```

The resulting `.vsix` file can be installed via the VSCode GUI.

## Usage

### Currently:

ThingsDB hilighting starts after adding the comment `//ti` at the start of multi-line string.
![example](images/example_highlight.png)

## Acknowledgements

This project was cloned from Mark Wibrow project [python-string-sql](https://github.com/mwibrow/python-string-sql), that was was adpated from [es6-string-html](https://github.com/hanjingboo/es6-string-html).

## Contribution

Currently, only contributors to the Mark's Wibrow's project and me have contributed. If anybody would like to contribute, just create a pull request and/or issue. Thank you!
