### 0.0.5 (in progress)
* Added the ability to check all addons for update in a single command.
* WoWInterface installs will now automatically fix the addon name if it's been entered stupidly by the user.

### 0.0.4
* Fix broken caching, use `--no-cache` to disable and `--cache` to ensure enabled.
* Added WoWInterface support
* Improved outdated help message
* Added version info in help and `wow version`

### 0.0.3
* Now caches downloaded files in $WOWPATH/Interface/ZipFiles, making for faster reinstalls and makes downgrades possible with TukUI addons. Can be bypassed with `--no-cache`
* Find out which addon created that folder using `wow blame`


### 0.0.2
* Added detection to prevent a shared folder getting removed when only one of the addons is removed
* Fix crash when $WOWPATH/.addons.json is not present.
* Better addon update checking

### 0.0.1
* Inital Release