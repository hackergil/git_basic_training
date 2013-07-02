# Branch strategy



## A strategy, why?

* Unblocks production releases
* Unblocks the development team
* Allows features to unblock releases
* Standardizes branch management


## Main branches

* Master (Production Code)
* Develop ( Code for next release)


## Supporting branches

* Feature branches
* Release branches
* Hotfix branches 


## Feature branches

* May branch off from: develop
* Must merge back into: develop
* Any name except master, develop, release-*
* Must be deleted once feature is done and integrated
* PDP, FieryFuchsia


## Release branches

* May branch off from: develop
* Must merge back into: develop and master
* Branch naming convention: release-*
* Created when develop is stable
* Only bugs are checked in


## Hotfix branches

* May branch off from: master
* Must merge back into: develop and master
* Branch naming convention: hotfix-*
* Unplanned production release
