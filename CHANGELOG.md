# Change Log
### Version 0.1.8
- improve compatibility
- optimize hook proguard
- add checkIncrementalInDebug
- fix npe cased by refer-checker
- 
### Version 0.1.7
- Optimize incremental build and fix bugs
- Fix memory leak in plugins
- Support multi variants build

### Version 0.1.6
- Upgrade AGP 3.5.3
- Fix memory leak in HookProguard
- Run refer-check-plugin in single flow in order to check any issues producted by bytex'plugin
- Unified threadpool and run pipleline lifecycles in parallel

### Version 0.1.5
- Fix bugs with getter-setter-inline plugins

### Version 0.1.4
- Fixed a bug caused by incorrectly processing removed input file.
- Optimize graph cache reading and writing efficiency and  size
- More efficient and convenient way for creating a [incremental](wiki/ByteX-Developer-API-en.md#incremental-plugin) plugin 

### Version 0.1.3
- shrink styleable(shrink 500KB+ on douyin)
- RFileKnife(fix R.java code to large)
- ButterKnifeCheck(detect exceptions caused by cross-module use of ButterKnife)
- optimize graph cache and html log
- fix bug(fd leak)

### Version 0.1.2
- fix memory leak
- optional html log、optional graph cache for incremental build

### Version 0.1.1

- Removed some code in GradleToolKit and add `booster-android-gradle-api` as dependencies.

### Version 0.1.0

Initial release