`example` orb for CircleCI
--------------------------

This orb provides a set of commands and jobs for [`example`](https://example.com) in CircleCI workflows. Commands include 

### Usage

### Development

This orb has been developed in *unpacked* form. You may view its packed source with
```shell
$ circleci orb pack src/
```
#### `pre-commit`

This repository uses `pre-commit` to uphold certain code styling and standards. You may install the hooks listed in [`.pre-commit-config`](.pre-commit-config) with
```shell
$ pre-commit install
```
