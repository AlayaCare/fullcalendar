# Alayacare Fullcalendar v3.10.0
This is a fork of fullcalendar's repo that we use to publish on our Nexus our own package. This is needed because inside webapp we use v4 and Family Portal uses v3.

The base branch we use is v3.10, you should never use master because otherwise you will use the v4 of fullcalendar. We did not change anything in the code, we only publish the package under another name, `@alayacare/fullcalendar`, so that we can have both v3 and v4 running in webapp.

## Publish
If you need to make any changes, heres how you do it:

1. build: `npm run clean && npm run dist`
2. login to publish `npm login --registry https://nexus.alayacare.net/repository/npm-alayacare/`
3. publish `npm publish`


# FullCalendar [![Build Status](https://travis-ci.org/fullcalendar/fullcalendar.svg?branch=master)](https://travis-ci.org/fullcalendar/fullcalendar)

A full-sized drag & drop event calendar (jQuery plugin).

- [Project website and demos](http://fullcalendar.io/)
- [Documentation](http://fullcalendar.io/docs)
- [Support](http://fullcalendar.io/support)
- [Contributing](CONTRIBUTING.md)
- [Changelog](CHANGELOG.md)
- [License](LICENSE.txt)
