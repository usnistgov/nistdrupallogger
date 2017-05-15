# THIS GIT REPOSITORY IS NO LONGER MAINTAINED.

Please see [FIPS Logger](https://github.com/usnistgov/fips_logger) for further information about a FIPS compliant logging module for Drupal.

## ALL DEVELOPMENT IN THIS REPOSITORY WILL STOP.

### Old Synopsis

Requirements are derived from:
[Department of Commerce
Information Technology Security Program Policy](https://connection.commerce.gov/sites/connection.commerce.gov/files/2014_doc_itspp.pdf).

See section 4.5 (starting on page 38) of the DoC IT Security Program Policy (ITSPP) for the basic information.

Drupals' base line logging covers most of the FIPS requirements, failed login attempts, role changes, user deletions, user creation, content submission, critical errors and Apache covers the web server errors. What was missing was:

* content changes to menu's
* changes to fields
* changes to modules

Those have been incorporated into this logger.


### Installation

Disable database logging and enable system logging and this module. Thats it. No other configuration is needed.

