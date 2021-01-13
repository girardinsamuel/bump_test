# Demo of GitHub release to bump commit

Based on https://github.com/peritus/bumpversion package, this repo shows how to configure a GitHub workflow to auto-bump code upon release creation.

1. Create (manually) a release in GitHub e.g. `v1.0.1`

A workflow will be started to automatically:

2. edit all files where version number should be bumped
3. commit those changes
4. push the changes

Configuration inside `.bumpversion.cfg` :
- edit commit message
- edit list of files needed to be changes
- a lot of things (cf doc of bumpversion)
