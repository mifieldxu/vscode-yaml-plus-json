# YAML plus JSON

Easily convert YAML to JSON or vice versa. Conversion can be done by each individual file or by all files in a folder.

Any good ideas or feature requests? Please, do not hesitate to open [a new issue](https://github.com/hilleer/vscode-yaml-plus-json/issues/new)!

## Features and usage

* Convert individual files.
	* Convert a YAML file to JSON by right clicking it and selecting `Convert to JSON`.
	* Convert a YAML file to JSON by changing file extension to `.json`.
	* Convert a JSON file to YAML by right clicking it and selecting `Convert to YAML`.
	* Convert a JSON file to YAML by changing file extension to `.yaml` or `.yml`.
* Convert text selection.
	* Convert YAML selection by using command `Convert selection to JSON` - _does not_ change file extension.
	* Convert JSON selection by using command `Convert selection to YAML` - _does not_ change file extension.
* Converting multiple files in a directory
	* Convert a selection of JSON files to YAML by right clicking one of the selected files and selecting `Convert selected files to YAML`.
	* Convert a selection of YAML files to JSON by right clicking one of the selected files and selecting `Convert selected files to JSON`.
	* Convert YAML files in a directory to JSON by right clicking the directory and selecting `Convert YAML files to JSON`.
	* Convert JSON files in a directory to YAML by right clicking the directory and selecting `Convert JSON files to YAML`.

## Config

| id                             | description                       | type    | default | example |
|--------------------------------|-----------------------------------|---------|---------|---------|
| yaml-plus-json.convertOnRename | Convert YAML/JSON files on rename | boolean | true    | true    |
