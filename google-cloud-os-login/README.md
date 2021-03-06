Google Cloud Java Client for OS Login
=====================================

Java idiomatic client for [Google Cloud OS Login][cloud-os-login].

[![CircleCI](https://circleci.com/gh/GoogleCloudPlatform/google-cloud-java/tree/master.svg?style=shield)](https://circleci.com/gh/GoogleCloudPlatform/google-cloud-java/tree/master)
[![Coverage Status](https://coveralls.io/repos/GoogleCloudPlatform/google-cloud-java/badge.svg?branch=master)](https://coveralls.io/r/GoogleCloudPlatform/google-cloud-java?branch=master)
[![Maven](https://img.shields.io/maven-central/v/com.google.cloud/google-cloud-os-login.svg)]( https://img.shields.io/maven-central/v/com.google.cloud/google-cloud-os-login.svg)
[![Codacy Badge](https://api.codacy.com/project/badge/grade/9da006ad7c3a4fe1abd142e77c003917)](https://www.codacy.com/app/mziccard/google-cloud-java)
[![Dependency Status](https://www.versioneye.com/user/projects/58fe4c8d6ac171426c414772/badge.svg?style=flat)](https://www.versioneye.com/user/projects/58fe4c8d6ac171426c414772)

- [Product Documentation][cloud-os-login]
- [Client Library Documentation][os-login-client-lib-docs]

> Note: This client is a work-in-progress, and may occasionally
> make backwards-incompatible changes.

Quickstart
----------

[//]: # ({x-version-update-start:google-cloud-os-login:released})
Add this to your pom.xml file
```xml
<dependency>
  <groupId>com.google.cloud</groupId>
  <artifactId>google-cloud-os-login</artifactId>
  <version>0.43.0-alpha</version>
</dependency>
```
If you are using Gradle, add this to your dependencies
```Groovy
compile 'com.google.cloud:google-cloud-os-login:0.43.0-alpha'
```
If you are using SBT, add this to your dependencies
```Scala
libraryDependencies += "com.google.cloud" % "google-cloud-os-login" % "0.43.0-alpha"
```
[//]: # ({x-version-update-end})

Authentication
--------------

See the [Authentication](https://github.com/GoogleCloudPlatform/google-cloud-java#authentication) section in the base directory's README.

About Google Cloud OS Login
---------------------------

[Google Cloud OS Login][cloud-os-login] manages OS login configuration for Directory API users.

See the [OS Login client library docs][os-login-client-lib-docs] to learn how to interact with the
Cloud OS Login using this Client Library.

Getting Started
---------------
#### Prerequisites
For this tutorial, you will need a
[Google Developers Console](https://console.developers.google.com/) project with the OS Login API
enabled. You will need to [enable billing](https://support.google.com/cloud/answer/6158867?hl=en) to
use Google Cloud OS Login.
[Follow these instructions](https://cloud.google.com/docs/authentication#preparation) to get your
project set up. [Set up authentication with a service account][auth] so you can access the
API from your local workstation.

#### Installation and setup
You'll need to obtain the `google-cloud-os-login` library.  See the [Quickstart](#quickstart) section
to add `google-cloud-os-login` as a dependency in your code.

Transport
---------
OS Login uses gRPC for the transport layer.

Java Versions
-------------

Java 7 or above is required for using this client.

Testing
-------
See [TESTING] to read more about testing.

Versioning
----------

This library follows [Semantic Versioning](http://semver.org/).

It is currently in major version zero (``0.y.z``), which means that anything
may change at any time and the public API should not be considered
stable.

Contributing
------------

Contributions to this library are always welcome and highly encouraged.

See `google-cloud`'s [CONTRIBUTING] documentation and the [shared documentation](https://github.com/GoogleCloudPlatform/gcloud-common/blob/master/contributing/readme.md#how-to-contribute-to-gcloud) for more information on how to get started.

Please note that this project is released with a Contributor Code of Conduct. By participating in this project you agree to abide by its terms. See [Code of Conduct][code-of-conduct] for more information.

License
-------

Apache 2.0 - See [LICENSE] for more information.


[CONTRIBUTING]:https://github.com/GoogleCloudPlatform/google-cloud-java/blob/master/CONTRIBUTING.md
[code-of-conduct]:https://github.com/GoogleCloudPlatform/google-cloud-java/blob/master/CODE_OF_CONDUCT.md#contributor-code-of-conduct
[LICENSE]: https://github.com/GoogleCloudPlatform/google-cloud-java/blob/master/LICENSE
[TESTING]: https://github.com/GoogleCloudPlatform/google-cloud-java/blob/master/TESTING.md

[cloud-os-login]: https://cloud.google.com/compute/docs/oslogin/rest/
[os-login-client-lib-docs]: https://googlecloudplatform.github.io/google-cloud-java/latest/apidocs/index.html?com/google/cloud/oslogin/v1/package-summary.html
[auth]: https://cloud.google.com/docs/authentication/getting-started
