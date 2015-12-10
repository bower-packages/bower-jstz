bower-jstz
==========

Bower repository for JS TimezoneDetect. http://pellepim.bitbucket.org/jstz

This version takes care of updating index.html when dependency is declared in bower.json. The original bower package has a defect and is not picked up by wiredep.

In order for it to be picked up by wiredep when automating injection of dependencies via gulp task

To pull this version

``` 
bower info hygieia-jstz-detect
bower hygieia-jstz-detect#*     cached git://github.com/amitmawkin/bower-jstz.git#1.0.5
bower hygieia-jstz-detect#*   validate 1.0.5 against git://github.com/amitmawkin/bower-jstz.git#*

{
  name: 'hygieia-bower-jstz',
  homepage: 'https://github.com/amitmawkin/bower-jstz',
  version: '1.0.5'
}

Available versions:
  - 1.0.5
You can request info for a specific version with 'bower info hygieia-jstz-detect#<version>'
```
