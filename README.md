# Project for TBuilder: Common packages

This is a repository used to build common packages for community
Sailfish OS ports by [TBuilder](https://github.com/rinigus/tbuilder).
To be able to build the packages:

- create RPMS/`target_name` . For example,
  RPMS/SailfishOS-4.0.1.48-aarch64. It is recommended to use a "clean"
  target without droid-hal packages installed, in contrast to the one
  normally used for porting.

Here, the following convention is used:

- packages are added submodules under `src`
- their SPECs are linked from `spec`

To add new submodules, use `add_repo` script from TBuilder.

To compile, run `tbuilder .` in this directory.
