# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Added
- Add the fc stubs from nutanix/terraform-provider-nutanix
- Add the foundation stubs from nutanix/terraform-provider-nutanix
- Add the karbon stubs from nutanix/terraform-provider-nutanix
- Added GetCurrentLoggedInUser in pkg/nutanix/v3/v3_service.go

### Changed
- Updated the http client with the latest from github.com/nutanix/terraform-provider-nutanix
- Updated the v3 stubs with the latest from github.com/nutanix/terraform-provider-nutanix
- Updated the utils package with the latest from github.com/nutanix/terraform-provider-nutanix

### Removed
- Remove the compiled binary for the client from the source code
- Remove debug logs from pkg/nutanix/client.go


## [0.1.0] - 2022-06-08
### Added
- Initial copy of the v3 stubs and http client by [@vnephologist](https://github.com/vnephologist).

### Changed
- Change MessageResource.Details type from `map[string]string` and `map[string]interface{}` to `interface{}`

