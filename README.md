Android Open Pwn Project
========================

## Getting Started

Please refer to the [Downloading and Building Requirements](https://source.android.com/source/requirements.html) before proceeding.

## Downloading the Source

Please refer to [Downloading the Source](https://source.android.com/source/downloading.html) before proceeding.

To initialize a local repository using this source tree, use the command:

    repo init -u git@github.com:aopp/android_platform.git -b px-0.1

Then to sync the repository, use:

    repo sync

## Building

Please refer to [Building the System](https://source.android.com/source/building.html) before proceeding.

To initialize the build environment after the repo sync, use the command:

    . build/envsetup.sh

Then to choose a build target, use:

    brunch

Or to specify a target, use:

    brunch <device>
