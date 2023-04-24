## Silverstripe CMS reporting tools recipe

[![CI](https://github.com/silverstripe/recipe-reporting-tools/actions/workflows/ci.yml/badge.svg)](https://github.com/silverstripe/recipe-reporting-tools/actions/workflows/ci.yml)
[![Silverstripe supported module](https://img.shields.io/badge/silverstripe-supported-0071C4.svg)](https://www.silverstripe.org/software/addons/silverstripe-commercially-supported-module-list/)

This includes the following core Silverstripe modules:

 * [silverstripe/recipe-cms](https://github.com/silverstripe/recipe-cms): Recipe containing CMS, versioned, asset-admin, etc
 * [silverstripe/externallinks](https://github.com/silverstripe/silverstripe-externallinks): Module which tracks
   external broken links in Silverstripe CMS pages
 * [silverstripe/reports](https://github.com/silverstripe/silverstripe-reports): API for creating backend reports in
   the Silverstripe Framework
 * [silverstripe/securityreport](https://github.com/silverstripe/silverstripe-securityreport): "Users, Groups and
   Permissions" report in Silverstripe CMS
 * [silverstripe/sitewidecontent-report](https://github.com/silverstripe/silverstripe-sitewidecontent-report): Report
   of all pages and files across all the project, including subsites
 * [bringyourownideas/silverstripe-maintenance](https://github.com/bringyourownideas/silverstripe-maintenance): Report
   of all Silverstripe modules installed in the project
 * [bringyourownideas/silverstripe-composer-update-checker](https://github.com/bringyourownideas/silverstripe-composer-update-checker): 
    Adds columns to the installed modules report indicating newer versions of installed modules that are available
   
    
This can be either added to an existing project or used as a project base for creating a basic CWP install.

## Installation

```sh
composer create-project silverstripe/recipe-reporting-tools ./myproject
```

## More information

See the [recipe plugin](https://github.com/silverstripe/recipe-plugin) page for instructions on how
Silverstripe recipes work.
