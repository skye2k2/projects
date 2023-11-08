# Historical timeline of Clif's projects

in reverse-chronological order (Christmas at the top). A high-level overview of past projects, where each entry can be expanded for additional detail.

<!--- 

LINKS FOR STATS:

Package count (filter to @fs/zion): https://www.familysearch.org/frontier/dashboard/package (does not include individual counts of all zion-ui components)
Build time: https://www.familysearch.org/frontier/dashboard/zion-builds

--->


## 2023

- Location: Remote, treeweb-blue
	- Dumped onto tw-blue team, in an attempt to share team culture and engineering best practices to a half of the team without balance in their development habits.
- RootsTech back to in-person, but also online (3.6M web participants, 14.5k in-person, 128k hrs of viewed content).
- Active React migrations of the remainder of treeweb code halted to begin immediate development of family group and community edit trees, and the supporting sibling pedigree view (Ancestry.com clone).
- Manage pedigree Community feedback forum and persist React Landscape/Portrait Pedigree Views.
- LLS mode added to pedigree view for Search team.

Organization-wide restructure.

<details>
<summary>Technologies</summary>

- All babylon components moved to zion.
- Zion: GitHub monorepo of 131 (+104 zion-ui) components with 50-minute build time (v13)
    - React, Storybook, Yarn, Linaria, Lerna, Babel, Jest, Cypress, NX (not really), ESLint8, Prettier, Travis CI, node 20
- Heroku, moving next year to pure AWS machines
- Akamai
- JavaScript: React (Polymer = deprecated)
- CloudBees (formerly ElectricFlow), moving next year to pure GitHub action builds
- SauceLabs
- Slack + Microsoft Teams
- Convert from VersionOne project management to JIRA, with some significant drawbacks

</details>

## 2022

- Location: Remote, treeweb-gold
- Second year of purely online RootsTech Connect Conference (3.1M web participants, 22k hrs of viewed content).
- Create a tree onboarding experience, with registration changing to require minimal information.
- Hand off Conclusion component to tw-blue for phase 2 development for the person page.
- Release React First Ancestor Pedigree View.
- Release React Landscape/Portrait Pedigree Views.

<details>
<summary>Technologies</summary>

- Zion: GitHub monorepo of 113 (+60 zion-ui) components with 60-minute build time (v12)
    - React, Storybook, Yarn, Linaria, Lerna, Babel, Jest, NX, ESLint7, Prettier, Travis CI, node 16, terrible MFA SSO

</details>

<details>
<summary>Shared components</summary>

- React: Forms AddFindFlow, Pedigree View
- Polymer: birch-standards-picker, birch-typeahead, fs-add-person, fs-cache, fs-change-summary, fs-collapsable-card, fs-copy-pid, fs-couple-renderer, fs-decorated-text, fs-demo, fs-descendancy, fs-dialog, fs-duplicate-not-a-match, fs-family-members, fs-fanchart, fs-find-page, fs-helplet, fs-horizontal-scroller, fs-indicators, fs-life-events, fs-list-page, fs-more-less, fs-pedigree, fs-pedigree-data-service, fs-permissions, fs-person-card, fs-person-data-service, fs-person-notes, fs-person-page, fs-person-summary, fs-person-tile, fs-person-timeline, fs-prompt, fs-relationship-calc, fs-research-help-page, fs-research-help-service, fs-reservations, fs-soft-launch, fs-temple, fs-test-component, fs-todo-list, fs-tree-changelog, fs-tree-common-routing, fs-tree-conclusion, fs-tree-is-authorized, fs-tree-name-template, fs-tree-navigation, fs-tree-onboarding-flow, fs-tree-person-ordinances, fs-tree-person-renderer, fs-tree-recents, fs-user-preferences-service, fs-user-service, fs-walkme, fs-watch, inert, resettable-properties-behavior, styles-wc, tree-data-handler, wc-i18n

</details>

<details>
<summary>Christmas (barely given time)</summary>

- Create React Descendancy view (recursive node, initial styling, connector lines, hover, expansion, collapse, data fetching)

</details>

## 2021

- Location: Remote, treeweb-gold
- Organization restructure into geographically-focused projects--lose significant number ? of Tree developers, temporarily and permanently.
- First year of purely online RootsTech Connect Conference (1.5M web participants).
- Migrate off of SalesForce to Brightspot + JIRA.

<details>
<summary>Technologies</summary>

- Zion: GitHub monorepo of 100+ components with 50-minute build time (v10)
    - React, Storybook, Yarn, Linaria, Lerna, Babel, Jest, Travis CI, node 14

</details>

<details>
<summary>Shared components</summary>

- Forms (complete performance overhaul conversion from Formik to react-hook-form)
- React: AddFindFlow, Conclusion, First Ancestor Pedigree View
- Polymer: birch-standards-picker, birch-typeahead, fs-add-person, fs-cache, fs-change-summary, fs-collapsable-card, fs-copy-pid, fs-couple-renderer, fs-decorated-text, fs-demo, fs-descendancy, fs-dialog, fs-duplicate-not-a-match, fs-family-members, fs-fanchart, fs-find-page, fs-helplet, fs-horizontal-scroller, fs-indicators, fs-life-events, fs-list-page, fs-more-less, fs-pedigree, fs-pedigree-data-service, fs-permissions, fs-person-card, fs-person-data-service, fs-person-notes, fs-person-page, fs-person-summary, fs-person-tile, fs-person-timeline, fs-prompt, fs-relationship-calc, fs-research-help-page, fs-research-help-service, fs-reservations, fs-soft-launch, fs-temple, fs-test-component, fs-todo-list, fs-tree-changelog, fs-tree-common-routing, fs-tree-conclusion, fs-tree-is-authorized, fs-tree-name-template, fs-tree-navigation, fs-tree-onboarding-flow, fs-tree-person-ordinances, fs-tree-person-renderer, fs-tree-recents, fs-user-preferences-service, fs-user-service, fs-walkme, fs-watch, inert, resettable-properties-behavior, styles-wc, tree-data-handler, wc-i18n

</details>

<details>
<summary>Christmas (sick)</summary>

- (Early) Organization-wide /version pages added to react branch of snow
- Stryker mutator update

</details>

## 2020

- Location: Family Search Building, Thanksgiving Point, Lehi, treeweb-gold
- The first year of the organization-wide conversion to React. Begin development of complicated, highly shared components (person and add flow).

<details>
<summary>Technologies</summary>

- Zion: GitHub monorepo of ~50 components with 20-minute build time (v9)
    - React, Storybook, Yarn, Emotion, Lerna, Babel, Jest, ESLint6, Travis CI, node 14
- Heroku
- Akamai
- JavaScript: React (Polymer = deprecated)
- CloudBees (formerly ElectricFlow)
- SauceLabs
- Slack + Microsoft Teams
- VersionOne

</details>

<details>
<summary>Christmas (sick)</summary>

- Stryker mutator integration

</details>

<details>
<summary>Shared components</summary>

- React: Person (Couple, Name, PersonOverlay, PersonService), RelationshipViewer

</details>

<details>
<summary>Tree overview page</summary>

- Publicly-searchable and -indexable landing page to provide basic information, replacing the search records page that currently is the top result.

</details>

- app-status-dashboard enhancement: historical build information & rollup coverage numbers.

<details>
<summary>Personal: triple triad implementation</summary>

- Websocket-based, highly-cached webpage and game management and AI server implementation. ([source](https://github.com/skye2k2/triple-triad))

</details>

## 2019

- Location: Family Search Building, Thanksgiving Point, Lehi, treeweb-gold

<details>
<summary>Christmas: Common build config</summary>

- fs-common-build-scripts & eslint-config-tree updates
    - Add importable Travis CI configuration files to simplify maintenance across 60+ repositories
    - Update and add new linting plugins
    - Write unit tests for rules we care about

</details>

<details>
<summary>Daily pull request notifications</summary>

Enhance https://github.com/skye2k2/pr-police/branches in order to provide better functionality, including day and holiday exclusion, scheduled run times, tag exclusion, and better environment variable support. [pull request](https://github.com/Talkdesk/pr-police/pull/8)

</details>

## 2018

- Location: Family Search Building, Thanksgiving Point, Lehi, treeweb-gold

<details>
<summary>Technologies</summary>

- fs-components
    - Polymer, native web components, Web Component Tester, Sauce, ESLint, Code Climate, Travis CI, 
- Heroku
- Akamai
- JavaScript: Polymer (Angular = deprecated)
- ElectricFlow
- SauceLabs
- Slack + Cisco Webex
- VersionOne

</details>

<details>
<summary>Christmas: To-do list</summary>

- Home's To-do List moved to a shared component, improved, and tested [pull request](https://github.com/fs-webdev/fs-todo-list/pull/1)
    - Extricate web component-based code and related service
    - Create repo with Code Climate, Travis CI, ESLint, and Lingoport integrations
    - Organize code, add significant unit tests, and clean up linting infractions
    - Update to fs-styles, fs-checkbox, & fs-icon
    - Add functionality:
        - Add a button component that uses fs-styles .fs-subnav__item and launches the todo list in a flyout, for use on any page
        - Save on loss of focus, to keep from losing data or editing multiple items at once
        - Cancel and close edit mode on escape key
        - Add useful autofocus after opening in flyout mode or editing a todo item
        - Show warning message if we won't be able to retrieve user data
        - Allow editing of completed items (otherwise, they need to uncomplete, edit, and recomplete)
        - Add ability to delete tasks on mobile--always show remove buttons, for now
        - Add analytics tracking via fs-metrics
        - Add data-test attributes
- Books read list Google Book API (1,000/day rate limit) data splicer for ISBN and page count
- Add Konami cheat code support to fs-globals [pull request](https://github.com/fs-webdev/fs-globals/pull/70)

</details>

<details>
<summary>Personal: mustard seed comparison</summary>

- Minimal JavaScript and CSS image scaling implementation. ([source](https://github.com/skye2k2/mustard-seed-comparison))

</details>

## 2017

- Location: Old Word Perfect Campus, Orem, tree-teflon

<details>
<summary>Technologies</summary>

- ng-shared-components
    - Angular, Karma, Mocha, Chai, Sinon, PhantomJS, Code Climate, Travis CI
- Heroku
- Akamai
- JavaScript: Angular (gadgets = deprecated)
- ElectricFlow
- SauceLabs
- HipChat + Cisco Webex
- VersionOne

</details>

<details>
<summary>Christmas: Misc.</summary>

- Decrease V8 client manifest filesize (25kB-->5kB)
- Fully dynamic fs-icon demo page
- Convert to HF-provided /version page route I helped author
- V8 Pedigree > 480: Add fullscreen button
- User preference: Pedigree background image
- Help TreeWeb Blue with blueprint 1.0 conversion (scripts, Heroku add-ons & configuration)
- gitmanage.sh script branch summary option
- Disable splunk-logger while we triage dyno performance
- Skills app: animated HTTP status cats [source](https://github.com/skye2k2/skills)

</details>

## 2016

- Location: Old Word Perfect Campus, Orem, tree-teflon
- MIGRATE OFF OF ORACLE TO CASSANDRA?

<details>
<summary>Christmas: Build optimizations</summary>

- Add auto semver release tagging to Travis builds
- Speed up Travis CI builds (remove unnecessary system install) ~3:00 --> ~1:45
- Help search/indexing integrate Code Climate
- Create free disk space script and add to developer tips & tricks
- Create repository update script and add to developer tips & tricks
- Custom Travis CI error/warning Slack alerts (contain failure reason/last lines of log/additional detail)

</details>

## 2015

- Location: Joseph Smith Memorial Building, Salt Lake City, tree-teflon

<details>
<summary>Christmas: Re-orderable person page</summary>

- Re-orderable person page + UX-requested openness redesign
- Movie picker [source](https://github.com/skye2k2/movie-picker)

</details>

## 2014

- Location: Joseph Smith Memorial Building, Salt Lake City, tree-teflon

<details>
<summary>Christmas: Portrait pedigree enhancements</summary>

- Portrait pedigree flyout auto-scroll functionality
- Portrait pedigree restyle
    - Implement restyle as per UX
    - Add gradient bars, descendant handlebar, and update connector lines
    - Add daybreak theme

</details>

## 2013

- Location: Joseph Smith Memorial Building, Salt Lake City, tree-teflon
- Start in August. Get up to speed

<details>
<summary>Christmas: Integration test help</summary>

- On-premise machines used for integration acceptance testing regularly fail--schedule a daily restart to have each machine ready for each day

</details>
