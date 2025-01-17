# Release History

## Version 0.2.7 (Unreleased)
Updated version to regenerate all reviews using Python 3.9

## Version 0.2.6 (Unreleased)
Updated type parsing to properly handle cases in which type
  info wraps onto a second line.
Fixed issue where ivar type was not properly parsed from
  the docstring.
Fixed issue where typehint parsing was too strict and required
  spaces.

## Version 0.2.5 (Unreleased)
Fixed bug in which kwargs were duplicated in certain instances.
Fix issue where non-async methods were erroneously marked async.
Fixed but where, in some instances, return types were truncated.

## Version 0.2.2 (Unreleased)
Bug fixes in type hint parser

## Version 0.2.1 (Unreleased)
Added package name in review node

## Version 0.2.0 (Unreleased)
Added support for packages with non-azure root namespace

## Version 0.0.1 (Unreleased)
Initial version of API stub generator for Azure SDK API view tool