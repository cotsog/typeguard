Version history
===============

1.1.0
-----

- Eliminated the need to pass a reference to the currently executing function to
  ``check_argument_types()``


1.0.2
-----

- Fixed types of default argument values not being considered as valid for the argument


1.0.1
-----

- Fixed type hints retrieval being done for the wrong callable in cases where the callable was
  wrapped with one or more decorators


1.0.0
-----

- Initial release