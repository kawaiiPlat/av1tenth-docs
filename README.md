# AV 1/tenth Documentation
[![Documentation Status](https://readthedocs.org/projects/av1tenth-docs/badge/?version=latest)](https://av1tenth-docs.readthedocs.io/en/latest/?badge=latest)

## Documentation
The [documentation website](https://av1tenth-docs.readthedocs.io/en/latest/) can be accessed from the link.

## File Types
The documentation can be written using either markdown (.md) or restructured text (.rst) formats.

## Notes
* It is important that any new files created for the documentation are included in a toctree specified in a .rst file. You can use the existing documentation as an example.

## Build
You can build the documentation by being in the root of the repository e.g. ``` ~/av1tenth-docs``` and typing the command:
```bash
./scripts/build_docs.sh
```
You can then view the documentation locally in your default browser with:
```bash
./scripts/view_docs.sh
```
## Notes
Run the command below in the docs folder of the repo if the built documentation is not updating.
```bash
make clean
```
This will remove all built files so the build will regenerate everything.
