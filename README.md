partial-install
===============

Subset `package.json` based on the needs of a specific entry point file.

Installation
------------

```sh
npm install --global partial-install
```

Documentation
-------------

The tool takes an entry point file and an output directory as arguments. It
will analyze the dependency tree of the entry point file, and subset
`package.json` and `package-lock.json` from the current directory, and store
them in the ouput directory.

Contribute
----------

- Issue Tracker: [github.com/balena-io-modules/partial-install/issues][issues]
- Source Code: [github.com/balena-io-modules/partial-install][source]

License
-------

The project is licensed under the Apache 2.0 license.

[issues]: https://github.com/balena-io-modules/partial-install/issues
[source]: https://github.com/balena-io-modules/partial-install
