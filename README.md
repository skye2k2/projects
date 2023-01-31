# Historical timeline of Clif's projects

in reverse-chronological order (Christmas at the top). A high-level overview of past projects, where each entry can be expanded for additional detail.


## 2023

- Location: Remote
- RootsTech back to in-person, but also online (??? participants).
- _In-progress: Read-Only Mode for Pedigree View, Descendancy Pedigree View, Fanchart Pedigree View, Private Groups, Community Edit Trees_

<details>
<summary>Technologies</summary>

- Zion: GitHub monorepo of ??+ components with ??-minute build time (v??)
    - React, Storybook, Yarn, Linaria, Lerna, Babel, Jest, Cypress, NX, ESLint8, Prettier

</details>

## 2022

- Location: Remote
- Second year of purely online RootsTech Connect Conference (??? participants).
- Create a tree onboarding experience, with registration changing to require minimal information.
- Hand off Conclusion component to tw-blue for phase 2 development.
- Release React First Ancestor Pedigree View.
- Release React Landscape/Portrait Pedigree Views.

<details>
<summary>Technologies</summary>

- Zion: GitHub monorepo of 130+ components with 60-minute build time (v12)
    - React, Storybook, Yarn, Linaria, Lerna, Babel, Jest, NX, ESLint7, Prettier, terrible MFA SSO

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

- Location: Remote
- Organization restructure into geographically-focused projects--lose significant number - of Tree developers, temporarily and permanently.
- First year of purely online RootsTech Connect Conference (500,000? participants).
- Migrate off of SalesForce to Brightspot + JIRA.

<details>
<summary>Technologies</summary>

- Zion: GitHub monorepo of 100+ components with 50-minute build time (v10)
    - React, Storybook, Yarn, Linaria, Lerna, Babel, Jest

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

- Location: Family Search Building, Thanksgiving Point, Lehi
- The first year of the organization-wide conversion to React. Begin development of complicated, highly shared components (person and add flow).

<details>
<summary>Technologies</summary>

- Zion: GitHub monorepo of ~50 components with 20-minute build time (v9)
    - React, Storybook, Yarn, Emotion, Lerna, Babel, Jest, ESLint6
- Heroku
- Akamai
- JavaScript: React (Polymer = deprecated)
- CloudBees (formerly ElectricFlow)
- SauceLabs
- Slack + Microsoft Teams

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

- Location: Family Search Building, Thanksgiving Point, Lehi

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

- Location: Family Search Building, Thanksgiving Point, Lehi

<details>
<summary>Technologies</summary>

- fs-components
    - Polymer, native web components, Web Component Tester, Sauce, ESLint, Code Climate
- Heroku
- Akamai
- JavaScript: Polymer (Angular = deprecated)
- ElectricFlow
- SauceLabs
- Slack + Cisco Webex

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

- Location: Old Word Perfect Campus, Orem

<details>
<summary>Technologies</summary>

- ng-shared-components
    - Angular, Karma, Mocha, Chai, Sinon, PhantomJS, Code Climate
- Heroku
- Akamai
- JavaScript: Angular (gadgets = deprecated)
- ElectricFlow
- SauceLabs
- HipChat + Cisco Webex

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

- Location: Old Word Perfect Campus, Orem
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

- Location: Joseph Smith Memorial Building, Salt Lake City

<details>
<summary>Christmas: Re-orderable person page</summary>

- Re-orderable person page + UX-requested openness redesign
- Movie picker [source](https://github.com/skye2k2/movie-picker)

</details>

## 2014

- Location: Joseph Smith Memorial Building, Salt Lake City

<details>
<summary>Christmas: Portrait pedigree enhancements</summary>

- Portrait pedigree flyout auto-scroll functionality
- Portrait pedigree restyle
    - Implement restyle as per UX
    - Add gradient bars, descendant handlebar, and update connector lines
    - Add daybreak theme

</details>

## 2013

- Location: Joseph Smith Memorial Building, Salt Lake City
- Start in August. Get up to speed

<details>
<summary>Christmas: Integration test help</summary>

- On-premise machines used for integration acceptance testing regularly fail--schedule a daily restart to have each machine ready for each day

</details>
