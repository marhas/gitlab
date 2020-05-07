fastlane documentation
================
# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```
xcode-select --install
```

Install _fastlane_ using
```
[sudo] gem install fastlane -NV
```
or alternatively using `brew cask install fastlane`

# Available Actions
## iOS
### ios bump_and_branch
```
fastlane ios bump_and_branch
```
Creates a release branch from the current master and then bumps the minor number of the master branch and finally comits and pushes the changes.
### ios show_project_version
```
fastlane ios show_project_version
```
Displays the current project version number
### ios bump_project_version
```
fastlane ios bump_project_version
```
Bumps the project version number. Defaults to bumping the patch number, use 'type:minor' or 'type:major' to override. Use version parameter to set the version number explicitly, eg: version: 12.1.2. If version parameter is used, type is ignored.

----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
