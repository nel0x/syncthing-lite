# Releasing

- do tests
- update translations using ``tx pull -af`` (as extra merge request or branch for the case it does not build correctly)
- update the version name and version code of the app [here](https://github.com/syncthing/syncthing-lite/blob/master/app/build.gradle)
- update the changelog at [app/src/main/play/en-GB/whatsnew](https://github.com/syncthing/syncthing-lite/blob/master/app/src/main/play/en-GB/whatsnew)
- create a tag/ release in GitHub with an changelog; The tag name should be the version number
- trigger a release at <https://build.syncthing.net/> to publish the release to google play
- F-Droid picks up the release by the tag
