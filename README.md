# jevsto

[jevsto](https://github.com/manuelp/jevsto) implementation using [EventStore](http://geteventstore.com/).

## Changelog

    TBD

## Install

Artifacts can be found on [JitPack](https://jitpack.io/#manuelp/jevsto-es). 
[Basically](https://jitpack.io/docs/), you just need to add JitPack repo and add the dependency. 
Using [Gradle](http://gradle.org/) as an example:

```groovy
allprojects {
  repositories { 
    jcenter()
      maven { url "https://jitpack.io" }
  }
}

dependencies {
  compile 'com.github.manuelp:jevsto-es:<VERSION>'
1}
```
