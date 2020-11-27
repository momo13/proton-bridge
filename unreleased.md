# ProtonMail Bridge and Import-Export app Changelog

Changelog [format](http://keepachangelog.com/en/1.0.0/)

## Unreleased

### Added

### Changed

### Removed
* GODT-651 Build creates proper binary names.
* GODT-148 Allow import (using the Import-Export app) of already encrypted messages as is.
* GODT-202 Update to latest go-smtp.

### Fixed
* GODT-135 Support parameters in SMTP `FROM MAIL` command, such as `BODY=7BIT`, or empty value `FROM MAIL:<>` used by some clients.
* GODT-338 GODT-781 GODT-857 GODT-866 Flaky tests.