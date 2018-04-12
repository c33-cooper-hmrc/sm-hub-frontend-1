[![Apache-2.0 license](http://img.shields.io/badge/license-Apache-brightgreen.svg)](http://www.apache.org/licenses/LICENSE-2.0.html)

sm-hub-frontend
================================

How to run
==========

```````````````
sbt run
```````````````

This will start the application on port **1024**

You also need to provide the path to your service manager config and workspace using a -D arg
```sbtshell
sbt -DsmPath=/path/ -Dworkspace=/workspace/ run
```


