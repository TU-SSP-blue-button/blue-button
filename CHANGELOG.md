# Log of all changes

# Dependencies

- Used `npm audit` to find issues with dependencies
- Used `npm outdated` to find packages with newer versions
- Updated the packages listed in `npm outdated` and `npm audit` whenever those packages had new fixes released

# Testing

# Windows Compatibility

- Updated code that failed testing only on Windows to work with all OS: added line in lib/sense.js to normalize all whitespaces
