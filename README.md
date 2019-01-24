[//]: # ($FrauBSD: jail_build/README.md 2019-01-24 12:05:27 -0800 freebsdfrau $)

# Welcome to [FrauBSD.org/jail\_build](https://fraubsd.org/jail_build)!

Build FreeBSD jails from binary distributions

## Foreword

The following is required before using `git commit` in this project.

> `$ .git-hooks/install.sh`

This will ensure the FrauBSD keyword is expanded/updated for each commit.

## About

`jail_build` is a script:

+ Be a single-script solution
+ Have zero dependencies outside of FreeBSD base OS
+ Work on any FreeBSD host (4.x minimum)
+ Work with any FreeBSD distribution set (1.x minimum)
+ Be completely scriptable
+ Use `dialog` for human interactions
