## 2.5.5
* Added some usage information to the README

## 2.5.4
* Tests code cleanup
* Raise minimal compatible Atom version to 1.0.0
* Wrap all changes into a single undo transaction

## 2.5.3
* Ignore common zero-width unicode characters for cell width (#17)

## 2.5.2
* Bogus release (no changes)

## 2.5.1
* Fix #16

## 2.5.0

* Removed unnecessary comments
* Code format
* Add possible EOF at table body end will allow for capturing tables that are at end of file w/o trailing newline
* Extra newline removed
* Fix typo
* Add testcases for Chinese and Russian tables
* Use wcwidth
* Small regex format update
* Extend selections to whole tables
* Only auto-select document if all ranges are empty
* Only extend ranges when not empty or not ASED (auto-select entire document


## 2.4.2
* Update specs to check more cases
* Put all extra content into last cell
* Correct CJK character width counting


## 2.4.1

* Fix #11
* Settings are now handled via fields to facilitate easier testing
* Update specs


## 2.4.0

* Fixed stray `if` from #7

I'm very sorry for this bug. I didn't tested because today was my first day at work after my vacation. Things were a little crazy. I promisse I'll be more careful from now on.


## 2.3.0

* Merged changes from #7 and #8
* **Now the package is ready for Atom API 1.0**


## 2.2.0

* Merge branch 'lierdakil-newregex' lierdakil@08374da6c9ec2bb35d35bc666c0408929448fe37


## 2.1.1

* Fix for bug #3 "Insertion Point Lost On Save"


## 2.1.0

* Fix for keeping document auto selected


## 2.0.1

* Fix a regression where a table wouldn't be recognized


## 2.0.0

* Added option to choose if first and last pipes should be kept
* Added option to choose the padding of the cells
* Added support for latest config api
* Added specs to package
* Changed regex to identify pipeless tables
* Changed requirements to atom >= 0.135.0
* Removed deprecated APIs to observe text editors


## 1.0.2

* Sorry to anyone using my package, had some troubles with git and remote tags. Hope this fixes everything.


## 1.0.1

* Added option to restore selections (default: false)
* Fixed incorrect trimming of selected tables
* Auto-select entire document if selection is empty (default: true)
* Added a fix in the regex to consider spaces at the end of each line


## 0.1.2

* Bug fixes


## 0.1.1

* Bug fixes


## 0.1.0

* Every feature added
