# Historical timeline of Clif's projects

in reverse-chronological order (Christmas at the top). A high-level overview of past projects, where each entry can be expanded for additional detail.


## 2020

The first year of the organization-wide conversion to React.

<details>
<summary>Technologies</summary>

* Heroku
* JavaScript: React (Polymer = deprecated)
* CloudBees (formerly ElectricFlow)
* Slack + Microsoft Teams

</details>

<details>
<summary>Christmas: ???</summary>
</details>

<details>
<summary>Shared components</summary>

* AddFindFlow
* Person (Couple, Name, PersonOverlay, PersonService)
* RelationshipViewer

</details>

<details>
<summary>Tree overview page</summary>

* Publicly-searchable and -indexable landing page to provide basic information, replacing the search records page that currently is the top result.

</details>

<details>
<summary>Personal: triple triad implementation</summary>
</details>

## 2019

<details>
<summary>Christmas: Common build config</summary>

* fs-common-build-scripts & eslint-config-tree updates
    * Add importable Travis CI configuration files to simplify maintenance across 60+ repositories
    * Update and add new linting plugins
    * Write unit tests for rules we care about

</details>

## 2018

<details>
<summary>Christmas: To-do list</summary>

* Home's To-do List moved to a shared component, improved, and tested
    * Extricate web component-based code and related service
    * Create repo with Code Climate, Travis CI, ESLint, and Lingoport integrations
    * Organize code, add significant unit tests, and clean up linting infractions
    * Update to fs-styles, fs-checkbox, & fs-icon
    * Add functionality:
        * Add a button component that uses fs-styles .fs-subnav__item and launches the todo list in a flyout, for use on any page
        * Save on loss of focus, to keep from losing data or editing multiple items at once
        * Cancel and close edit mode on escape key
        * Add useful autofocus after opening in flyout mode or editing a todo item
        * Show warning message if we won't be able to retrieve user data
        * Allow editing of completed items (otherwise, they need to uncomplete, edit, and recomplete)
        * Add ability to delete tasks on mobile--always show remove buttons, for now
        * Add analytics tracking via fs-metrics
        * Add data-test attributes
* Books read list Google Book API (1,000/day rate limit) data splicer for ISBN and page count

</details>

<details>
<summary>Personal: mustard seed comparison</summary>
</details>

## 2017

<details>
<summary>Christmas: Misc.</summary>

* Decrease V8 client manifest filesize (25kB-->5kB)
* Fully dynamic fs-icon demo page
* Convert to HF-provided /version page route I helped author
* V8 Pedigree > 480: Add fullscreen button
* User preference: Pedigree background image
* Help TreeWeb Blue with blueprint 1.0 conversion (scripts, Heroku add-ons & configuration)
* gitmanage.sh script branch summary option
* Disable splunk-logger while we triage dyno performance
* Skills app: animated HTTP status cats

</details>

## 2016

<details>
<summary>Christmas: Build optimizations</summary>

* Add auto semver release tagging to Travis builds
* Speed up Travis CI builds (remove unnecessary system install) ~3:00 --> ~1:45
* Help search/indexing integrate Code Climate
* Create free disk space script and add to developer tips & tricks
* Create repository update script and add to developer tips & tricks
* Custom Travis CI error/warning Slack alerts (contain failure reason/last lines of log/additional detail)

</details>

## 2015

<details>
<summary>Christmas: Re-orderable person page</summary>

* Re-orderable person page + UX-requested openness redesign
* Movie picker: https://github.com/skye2k2/movie-picker

</details>

## 2014

<details>
<summary>Christmas: Portrait pedigree enhancements</summary>

* Portrait pedigree flyout auto-scroll functionality
* Portrait pedigree restyle
    * Implement restyle as per UX
    * Add gradient bars, descendant handlebar, and update connector lines
    * Add daybreak theme

</details>

## 2013

<details>
<summary></summary>
</details>
