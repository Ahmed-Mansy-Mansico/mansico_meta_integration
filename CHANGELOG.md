# Changelog

## [Unreleased]

## [1.2.0]
### Added
- **Support Facebook Fields Datatypes**
- Bug fixes and improvements.

## [1.1.0] - 2025-02-09
- **Dynamic Lead Field Mapping**: Introduced dynamic mapping in the `create_lead` method. Now, you can customize which form fields are mapped to lead fields. This adds flexibility when dealing with different field names.
- **No Mandatory `email_id` for Lead**: Removed the mandatory requirement for `email_id` when creating a Lead. Only `first_name` is now required to create a Lead.
- **Improved Error Handling**: Refined error handling logic to provide better error reporting and debugging capabilities during integration.

### Fixed
- **Bug Fixes**: Fixed various issues related to lead processing and integration logic.

## [1.0.0] - 2025-02-01
### Added
- **Initial Release**: Launched the first version of Mansico Meta Integration, which includes support for importing leads from Facebook via the Facebook Lead Ads API.
