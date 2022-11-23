# tiled

USAXS tiled data server: databroker and /share1 directory.


## Goals

- [x] Identify NeXus/HDF5 files with arbitrary names.
- [x] Identify SPEC data files with arbitrary names and read them.
- [x] Read `.jpg` (and other image format) files.
- [x] Read the [synApps MDA format](https://github.com/epics-modules/sscan/blob/master/documentation/saveData_fileFormat.txt) ([Python support](https://github.com/EPICS-synApps/utils/blob/master/mdaPythonUtils/INSTALL.md))
- [x] Write a custom data file identifier.
- [x] Write a custom data file loader.
- [ ] Authentication
- [x] Learn how to ignore files such as `.xml` (without startup comments).

## Links

- <https://github.com/bluesky/tiled/issues/175>
- <https://blueskyproject.io/tiled/how-to/read-custom-formats.html#case-2-no-file-extension>
