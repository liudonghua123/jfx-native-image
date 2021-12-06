# jfx-native-image

## What is it

This is a simple JavaFx app which integrated with [Graalvm](https://www.graalvm.org/)'s [native-image](https://www.graalvm.org/reference-manual/native-image/), only minimal tools are included. All the three desktop prebuilt binaries are build and deployed using github actions. 

You can also try [hello-gluon-ci](https://github.com/gluonhq/hello-gluon-ci) which use `gluonfx-maven-plugin`, a more sophisticated and powerful maven plugin to do the `native-image` job.

## Some helpful references

- https://openjfx.io/openjfx-docs/#introduction
- https://www.graalvm.org/reference-manual/native-image/
- https://docs.gluonhq.com/
- https://docs.gluonhq.com/#platforms_windows
- https://github.com/gluonhq/hello-gluon-ci
- https://github.com/oracle/graal/issues/403#issuecomment-985385284
- https://stackoverflow.com/questions/67854139/javafx-warning-unsupported-javafx-configuration-classes-were-loaded-from-unna
- https://github.com/openjfx/samples/issues/17#issuecomment-983339369
- http://mail.openjdk.java.net/pipermail/openjfx-dev/2018-June/021977.html


## LICENSE

MIT License

Copyright (c) 2021 liudonghua