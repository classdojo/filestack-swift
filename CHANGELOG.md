Change Log
==========

Version 1.1 *(2017-11-03)*

- Added support for store options to uploads functionality.
- Improved upload error reporting.

Version 1.0.2 *(2017-11-01)*

- Disabled new Xcode build system to prevent issues with Carthage builds.
- Updated Arcane dependency to version 1.0.
- Updated Alamofire dependency to version 4.5.1.

Version 1.0.1 *(2017-10-31)*
----------------------------

- Added `startUploadImmediately` argument and turning `localURL` into an optional argument in `Client` `multipartUpload` function.
- Declared `MultipartUpload` `uploadFile()` function public.
- Added `StorageOptions` class.

Version 1.0 *(2017-08-23)*
----------------------------

Initial release.