A repository that demonstrates several separate Gradle builds that produce and consume outputs that are zipped into an archive, and how these can be used in a composite Gradle build.

There are 3 separate builds, in separate directories:

- producer1, produces a zip archive
- producer2, produces a zip archive
- consumer, consumes the zip archives from both producers and unpacks these to use the contents

There is also a composite build in the root directory that includes each of these.
