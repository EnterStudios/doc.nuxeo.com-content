---
title: Application Definition
review:
    comment: ''
    date: '2018-03-29'
    status: ok
confluence:
    ajs-parent-page-id: '12911781'
    ajs-parent-page-title: Working in Studio
    ajs-space-key: Studio
    ajs-space-name: Nuxeo Online Services
    canonical: Application+Dependencies
    canonical_source: 'https://doc.nuxeo.com/display/Studio/Application+Dependencies'
    page_id: '23364231'
    shortlink: h4JkAQ
    shortlink_source: 'https://doc.nuxeo.com/x/h4JkAQ'
    source_link: /display/Studio/Application+Dependencies
tree_item_index: 1400
history:
    -
        author: Manon Lumeau
        date: '2016-03-18 11:06'
        message: ''
        version: '7'
    -
        author: Manon Lumeau
        date: '2015-08-07 16:20'
        message: ''
        version: '6'
    -
        author: Solen Guitter
        date: '2015-01-12 14:11'
        message: Add some details
        version: '5'
    -
        author: Manon Lumeau
        date: '2015-01-09 16:00'
        message: ''
        version: '4'
    -
        author: Manon Lumeau
        date: '2014-12-31 14:47'
        message: ''
        version: '3'
    -
        author: Manon Lumeau
        date: '2014-12-31 14:20'
        message: ''
        version: '2'
    -
        author: Manon Lumeau
        date: '2014-12-31 14:18'
        message: ''
        version: '1'

---
The Application Definition page enables you to manage the requirements of your Nuxeo Studio project and your application.

![]({{file name='application-definition.png'}} ?w=438,border=true)

{{#> callout type='info' heading='Nuxeo University'}}
Watch the related courses on Nuxeo University
- [Video on a simple Nuxeo Project Creation](https://university.nuxeo.com/learn/public/course/view/elearning/144/nuxeo-platform-quickstart-creation-of-a-simple-nuxeo-studio-project)
![]({{file name='university-quickstart-studio-project.png' page='nxdoc/university'}} ?w=450,border=true)
{{/callout}}

## Main Options

*   **Nuxeo Server Version:** Studio will generate valid configuration for this Nuxeo Server version.
*   **Packages to Install:** The list of additional dependencies needed to make your application work. Selected dependencies will be automatically installed when you deploy your Nuxeo Studio configuration on your server.

Any Nuxeo public addon or [private addon you uploaded]({{page page='delivering-a-customization-package-through-the-nuxeo-marketplace'}}) in the <a href="https://marketplace.nuxeo.com" target="_blank">Nuxeo Marketplace</a> can be selected here: type a character to start filtering them. Options are shown with their title and description.
![]({{file name='addons-list.png'}} ?w=378,border=true)

Addons that display a `Studio` tag bring additional options into Studio like new screens or options, making their configuration easier.
![]({{file name='studio-tag.png'}} ?w=301,border=true)

Addons that display a `Private` tag mean they have been uploaded on the marketplace through the [private channel]({{page page='delivering-a-customization-package-through-the-nuxeo-marketplace'}}). Note that it is not yet possible to choose which version of a private package you want to depend on. Application definition will always add a dependency to the latest available version on the marketplace every time you save your changes.

No change is kept until you manually press the save button, and pending changes are shown so that you can tell what will be added or removed and undo it if necessary.
![]({{file name='pending-modifications.png'}} ?w=394,border=true)

## Upgrading to a Newer Nuxeo Server version

When upgrading to a newer Nuxeo Version, Nuxeo Studio will automatically adapt the configuration to it. Some exceptions requiring a manual change may still happen and are listed in the [specific upgrade instructions]({{page page='specific-upgrade-instructions'}}) page.

When a previously selected package is not available for your newer Nuxeo Server version, Nuxeo Studio will list it in the pending changes and warn you about it.
![]({{file name='removal-notice.png'}} ?w=417,border=true)

<div class="row" data-equalizer data-equalize-on="medium"><div class="column medium-6">{{#> panel heading='Related Documentation'}}

- [Specific Upgrade Instructions]({{page page='specific-upgrade-instructions'}})
- [Update the Version of Your Target Platform]({{page page='update-the-version-of-your-target-platform'}})

{{/panel}}</div><div class="column medium-6">
</div></div>