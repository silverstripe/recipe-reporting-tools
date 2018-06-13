## SilverStripe CMS reporting tools recipe

[![Build Status](https://travis-ci.org/silverstripe/recipe-reporting-tools.svg?branch=master)](https://travis-ci.org/silverstripe/recipe-reporting-tools)

This includes the following core SilverStripe modules:

 * [silverstripe/recipe-cms](https://github.com/silverstripe/recipe-cms): Recipe containing CMS, versioned, asset-admin, etc
 * [silverstripe/externallinks](https://github.com/silverstripe/silverstripe-externallinks): Module which tracks
   external broken links in SilverStripe CMS pages
 * [silverstripe/reports](https://github.com/silverstripe/silverstripe-reports): API for creating backend reports in
   the SilverStripe Framework
 * [silverstripe/securityreport](https://github.com/silverstripe/silverstripe-securityreport): "Users, Groups and
   Permissions" report in Silverstripe CMS
 * [silverstripe/sitewidecontent-report](https://github.com/silverstripe/silverstripe-sitewidecontent-report): Report
   of all pages and files across all the project, including subsites
 * [bringyourownideas/silverstripe-maintenance](https://github.com/bringyourownideas/silverstripe-maintenance): Report
   of all SilverStripe modules installed in the project
 * [bringyourownideas/silverstripe-composer-update-checker](https://github.com/bringyourownideas/silverstripe-composer-update-checker): 
    Adds columns to the installed modules report indicating newer versions of installed modules that are available
 * [bringyourownideas/silverstripe-composer-security-checker](https://github.com/bringyourownideas/silverstripe-composer-security-checker): 
    Adds warnings to the installed modules report against any modules that might have reported security vulnerabilities
   
    
This can be either added to an existing project or used as a project base for creating a basic CWP install.

## Get started

You can create a project using Composer:

```
composer create-project silverstripe/recipe-reporting-tools ./myproject ^1
```

## More information

See the [recipe plugin](https://github.com/silverstripe/recipe-plugin) page for instructions on how
SilverStripe recipes work.
