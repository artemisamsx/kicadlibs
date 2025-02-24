# Artemisa MSX - KiCad libraries

This repository contains the KiCad libraries used by Artemisa MSX components.

## Install

- Go to [GitHub releases page][1] and download the ZIP package of the latest release.
- In Kicad, open "Plugin and Content Manager" and click the "Install from file..." button above.
- Select the ZIP package downloaded from GitHub.
- Continue with the instructions

## Release

### Version bump

The library version is encoded in the `metadata.json` file. Just set the appropriate version number
for the new release.


### Create the ZIP package

Just create a ZIP package named `artemisa-kicadlibs_X.Y.Z` (where X, Y and Z are the elements of the
semantic version number) containing the following repository items:

- `3dmodels`
- `footprints`
- `symbols`
- `metadata.json`


### Test the release

Following the install instructions above with the generated ZIP package. Abort the release if you
find any issue.


### Upload to GitHub

- Create and push a new tag with the form `vX.Y.Z`.
- Create [a new release in GitHub][1] associated with the new tag, attaching the ZIP package.


[1]: https://github.com/artemisamsx/kicadlibs/releases
