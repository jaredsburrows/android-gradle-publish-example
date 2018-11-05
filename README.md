# Publish to Google Play on Successful Builds

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0)
[![TravisCI  Build](https://img.shields.io/travis/jaredsburrows/android-gif-example/master.svg)](https://travis-ci.org/jaredsburrows/android-gradle-publish-example)
[![Twitter Follow](https://img.shields.io/twitter/follow/jaredsburrows.svg?style=social)](https://twitter.com/jaredsburrows)

Basic example of auto publishing APKs to Google Play as Alpha builds. This is similar to publishing
"snapshots" to Maven or Jcenter's Snapshot repository.

**Publish Builds:**

    gradlew publishApkRelease -Ptrack=production

## License

    Copyright (C) 2018 Jared Burrows

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
