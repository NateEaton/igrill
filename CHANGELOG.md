## 2021-01-06 - Release 2.1

### Summary

- Added support for publishing device state (on, off) events
- On device state off, publish zero temperature for all probes
- Updated mqtt publish for battery and device state topics to enable retain

## 2019-08-18 - Release 2.0

### Summary

- Python 3 support (support for Python 2 will be dropped in the next release)
- Removed the need for pycrypto (https://github.com/bendikwa/igrill/issues/7)
- Updated dependencies
- General cleanup

## 2018-09-23 - Release 1.0

### Summary

- Removed unused files/functionality

## 2018-09-23 - Release 0.9

### Summary

- Added support for iGrill3
- Added support for multiple devices
- Separate therad for each device
- Added support for config files
