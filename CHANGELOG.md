# Change Log
All notable changes to this project will be documented in this file.

## [V0.0.1] - 8-May-2019

### Added
- README.md for information, setups, and instructions
- The popupInit function has numberOfCards parameter which developers can change to display out the desired minimum number of cards. The default for numberOfCards is 5
- Popup should not fade away/disappear if there is mouse over

### Changed
- For popup layout consistency, the image style width is set to 100px
- Removed the need for calculation between the interval and duration. The interval is called after the popup fades away instead of before the popup fades away
- For promo code popup, show promo code instead of the merchant name

### Fixed
- Fixed the bug where the popup shows the undefined timestamp for product
- Fixed the bug where the user is unable to close the popup
