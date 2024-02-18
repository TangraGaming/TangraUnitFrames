# Tangra Unit Frames

This is an addon based on [Shadowed Unit Frames](https://github.com/Nevcairiel/ShadowedUnitFrames). Originally created as the parent seemed to be unmantained.

# Release
This addon uses the [BigWigs packager](https://github.com/BigWigsMods/packager) to create the final release, as there are some dependencies needed.

## Manual Release
If you want to build locally you ca can follow the instructions from BigWigs: [Building locally](https://github.com/BigWigsMods/packager?tab=readme-ov-file#building-locally)

The directory `.release` is already on .gitignore. Use curl to download the shell file. You can use the command `curl --create-dirs --output-dir .release -sO https://raw.githubusercontent.com/BigWigsMods/packager/master/release.sh` to download the latest version, creating the folder if not present.

Then, you should be able to call `.release/release.sh` to create a new release