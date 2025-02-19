Changelog
=========

1.4.0
-----

* Update handling of non-finite numbers to match the behaviour jq 1.6.
  Specifically, NaN is outputted as None, Inf is outputted as DBL_MAX,
  and -Inf is outputted as DBL_MIN.

1.3.0
-----

* The jq and oniguruma libraries that these Python bindings rely on are now
  included in the source distribution, instead of being downloaded.

1.2.3
-----

* Add support for Python 3.11.

1.2.2
-----

* Include support for more wheels, including aarch64 on Linux.

1.2.1
-----

* Drop support for Python 2.7 and Python 3.4.

1.2.0 (Unreleased)
------------------

* Return integers larger than 32 bits as ints.

1.1.3
-----

* Include LICENSE in sdist.

1.1.2
-----

* Handle MACOSX_DEPLOYMENT_TARGET being an integer to improve macOS Big Sur support.

1.1.1
-----

* Update cibuildwheel to 1.6.2 to fix building of OS X wheels.

1.1.0
-----

* Add support for predefined variables.
