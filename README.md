# Travis CI Android Example [![Build Status](https://travis-ci.org/kwoolytech/Travis-CI-Android-Example.svg?branch=master)](https://travis-ci.org/kwoolytech/Travis-CI-Android-Example)

Simple Travis CI example for a Android project.

 - Sign up for [Travis CI](https://travis-ci.org/getting_started).
  - Need to specify the repo you want it to be monitored.  
 - Configure not to abort on Lint error.
  - Open app/build.gradle and add following in the ```android``` section.
    ```
    lintOptions {
        abortOnError false
    }
    ```
 - Update versions in the ```.travis.yml``` to be matched with the project.
 - Test if ```gradle build``` runs on the local 
 - Push the changes

## Reference
 - [How to embed build status to Github](https://docs.travis-ci.com/user/status-images)
