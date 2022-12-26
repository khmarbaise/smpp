[SoEBeS](https://www.soebes.de) Maven Parent POM
=======================

This pom defines the defaults which are used within [my](https://www.soebes.com) projects.

[![Apache License, Version 2.0, January 2004](https://img.shields.io/github/license/khmarbaise/smpp.svg?label=License)](https://www.apache.org/licenses/)
[![Maven Central](https://img.shields.io/maven-central/v/com.soebes.smpp/smpp.svg?label=Maven%20Central)](https://search.maven.org/#search%7Cga%7C1%7Ccom.soebes.smpp)
[![JDKBuilds](https://github.com/khmarbaise/smpp/workflows/JDKBuilds/badge.svg)][jdkbuilds]
[![Main](https://github.com/khmarbaise/smpp/workflows/Main/badge.svg)][mainbuilds]
[![Site](https://github.com/khmarbaise/smpp/workflows/SitePublishing/badge.svg)][published-site]
[![Issues](https://img.shields.io/github/issues/khmarbaise/smpp)](https://github.com/khmarbaise/smpp/issues)
[![Issues Closed](https://img.shields.io/github/issues-closed/khmarbaise/smpp)](https://github.com/khmarbaise/smpp/issues?q=is%3Aissue+is%3Aclosed)

Homepage
--------

* The Maven Site for the current release [https://khmarbaise.github.io/smpp/](https://khmarbaise.github.io/smpp/)

* The Maven Site for the current SNAPSHOT [https://khmarbaise.github.io/smpp/snapshot](https://khmarbaise.github.io/smpp/snapshot)

Status
------
 * productive version.

Create Issues
-------------

Issues can simply being created via gh command line client via:
```
gh issue create --label dependency-upgrade -m 5.3.11 -a "@me" --body '' --title "Upgrade maven-install-plugin to 3.1.0"
```
The `-m` defines the milestone while the given `--body ''` is needed to make the rest of the call non interactive.
 
TODOs
-----

 * See issue tracker https://github.com/khmarbaise/smpp/issues

[jdkbuilds]: https://github.com/khmarbaise/smpp/actions?query=workflow%3AJDKBuilds
[mainbuilds]: https://github.com/khmarbaise/smpp/actions?query=workflow%3AMain
[published-site]: https://khmarbaise.github.io/smpp/
