# CKAN Extensions Monitor

This is a monitor that twice a week runs the test suite of main CKAN extensions against CKAN core master branch.

## Status

| Extension | Repo |
| --------- | ---- |
| [![ckanext-admin-panel](https://github.com/ckan/ckan-extensions-monitor/workflows/ckanext-admin-panel/badge.svg)](https://github.com/ckan/ckan-extensions-monitor/actions/workflows/.ckanext-admin-panel.yml) | [ckanext-admin-panel](https://github.com/mutantsan/ckanext-admin-panel)
| [![ckanext-announcements](https://github.com/ckan/ckan-extensions-monitor/workflows/ckanext-announcements/badge.svg)](https://github.com/ckan/ckan-extensions-monitor/actions/workflows/.ckanext-announcements.yml) | [ckanext-announcements](https://github.com/okfn/ckanext-announcements)
| [![ckanext-archiver](https://github.com/ckan/ckan-extensions-monitor/workflows/ckanext-archiver/badge.svg)](https://github.com/ckan/ckan-extensions-monitor/actions/workflows/.ckanext-archiver.yml) | [ckanext-archiver](https://github.com/ckan/ckanext-archiver)
| [![ckanext-dcat](https://github.com/ckan/ckan-extensions-monitor/workflows/ckanext-dcat/badge.svg)](https://github.com/ckan/ckan-extensions-monitor/actions/workflows/.ckanext-dcat.yml) | [ckanext-dcat](https://github.com/ckan/ckanext-dcat)
| [![ckanext-fluent](https://github.com/ckan/ckan-extensions-monitor/workflows/ckanext-fluent/badge.svg)](https://github.com/ckan/ckan-extensions-monitor/actions/workflows/.ckanext-fluent.yml) | [ckanext-fluent](https://github.com/ckan/ckanext-fluent)
| [![ckanext-geoview](https://github.com/ckan/ckan-extensions-monitor/workflows/ckanext-geoview/badge.svg)](https://github.com/ckan/ckan-extensions-monitor/actions/workflows/.ckanext-geoview.yml) | [ckanext-geoview](https://github.com/ckan/ckanext-geoview)
| [![ckanext-googleanalytics](https://github.com/ckan/ckan-extensions-monitor/workflows/ckanext-googleanalytics/badge.svg)](https://github.com/ckan/ckan-extensions-monitor/actions/workflows/.ckanext-googleanalytics.yml) | [ckanext-googleanalytics](https://github.com/ckan/ckanext-googleanalytics)
| [![ckanext-harvest](https://github.com/ckan/ckan-extensions-monitor/workflows/ckanext-harvest/badge.svg)](https://github.com/ckan/ckan-extensions-monitor/actions/workflows/.ckanext-harvest.yml) | [ckanext-harvest](https://github.com/ckan/ckanext-harvest)
| [![ckanext-hierarchy](https://github.com/ckan/ckan-extensions-monitor/workflows/ckanext-hierarchy/badge.svg)](https://github.com/ckan/ckan-extensions-monitor/actions/workflows/.ckanext-hierarchy.yml) | [ckanext-hierarchy](https://github.com/ckan/ckanext-hierarchy)
| [![ckanext-pages](https://github.com/ckan/ckan-extensions-monitor/workflows/ckanext-pages/badge.svg)](https://github.com/ckan/ckan-extensions-monitor/actions/workflows/.ckanext-pages.yml) | [ckanext-pages](https://github.com/ckan/ckanext-pages)
| [![ckanext-pdfview](https://github.com/ckan/ckan-extensions-monitor/workflows/ckanext-pdfview/badge.svg)](https://github.com/ckan/ckan-extensions-monitor/actions/workflows/.ckanext-pdfview.yml) | [ckanext-pdfview](https://github.com/ckan/ckanext-pdfview)
| [![ckanext-saml2auth](https://github.com/ckan/ckan-extensions-monitor/workflows/ckanext-saml2auth/badge.svg)](https://github.com/ckan/ckan-extensions-monitor/actions/workflows/.ckanext-saml2auth.yml) | [ckanext-saml2auth](https://github.com/keitaroinc/ckanext-saml2auth)
| [![ckanext-scheming](https://github.com/ckan/ckan-extensions-monitor/workflows/ckanext-scheming/badge.svg)](https://github.com/ckan/ckan-extensions-monitor/actions/workflows/.ckanext-scheming.yml) | [ckanext-scheming](https://github.com/ckan/ckanext-scheming)
| [![ckanext-showcase](https://github.com/ckan/ckan-extensions-monitor/workflows/ckanext-showcase/badge.svg)](https://github.com/ckan/ckan-extensions-monitor/actions/workflows/.ckanext-showcase.yml) | [ckanext-showcase](https://github.com/ckan/ckanext-showcase)
| [![ckanext-sitesearch](https://github.com/ckan/ckan-extensions-monitor/workflows/ckanext-sitesearch/badge.svg)](https://github.com/ckan/ckan-extensions-monitor/actions/workflows/.ckanext-sitesearch.yml) | [ckanext-sitesearch](https://github.com/okfn/ckanext-sitesearch)
| [![ckanext-spatial](https://github.com/ckan/ckan-extensions-monitor/workflows/ckanext-spatial/badge.svg)](https://github.com/ckan/ckan-extensions-monitor/actions/workflows/.ckanext-spatial.yml) | [ckanext-spatial](https://github.com/ckan/ckanext-spatial)
| [![ckanext-xloader](https://github.com/ckan/ckan-extensions-monitor/workflows/ckanext-xloader/badge.svg)](https://github.com/ckan/ckan-extensions-monitor/actions/workflows/.ckanext-xloader.yml) | [ckanext-xloader](https://github.com/ckan/ckanext-xloader)


## Notes

The main goal is to keep track if the most common CKAN extensions are working as expected against CKAN core latest development branch. This can be used to easily detect breaking changes on CKAN core.

Tests are run At 12:00am on Tuesday and Thursday (`0 0 * * 2,4`) to have a fresh run before CKAN's [Tech Meetings](https://github.com/ckan/ckan/wiki/Weekly-Developer-Meetings).

## Contributing

To add a new extension just submit a PR with a specific workflow for the extension. You can take a look at [at this commit](542e0b27e659b93415b157ca013d302d4209db16) for reference on how to create a workflow.
