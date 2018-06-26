octomap_mapping
===============

This is the fork of original octomap_mapping with added parameters for using only defined ranges of dynamic point cloud to update octomap.

### Usage

- **~updatecloud_[min|max]_z** (float, default: -/+ infinity)

Minimum and maximum height of points to consider for insertion in the callback. Any point outside of this intervall in point cloud at each instant will be discarded before running any insertion or ground plane filtering.

ROS stack for mapping with OctoMap, contains the octomap_server package.

The `master` branch tracks the latest (stable) releases. Please send pull requests against the latest development branch, e.g. `indigo-devel`.

Imported from SVN, see https://code.google.com/p/alufr-ros-pkg/ for the previous versions.
