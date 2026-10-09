# npm-mirror

A pinned set of npm packages, published so that it can be scanned for known vulnerabilities before
anything installs it.

`package-lock.json` lists each package with its version, its registry.npmjs.org tarball and its
integrity hash. A lockfile can hold one version of a name, so further versions of the same package
are in `more/<n>/package-lock.json`. Only packages published on registry.npmjs.org appear here, and
only those facts.

Commits are automated. Issues and pull requests are not monitored.
