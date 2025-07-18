# Historical timeline of Clif's projects

in reverse-chronological order. A high-level overview of past projects, where entries can be expanded for additional detail.

<!---

LINKS FOR STATS:

Package count (filter to @fs/zion): https://www.familysearch.org/frontier/dashboard/package (does not include individual counts of all zion-ui components)
Build time: https://www.familysearch.org/frontier/dashboard/zion-builds

--->


## 2025

- Location: Hybrid (1 in-office, 4 remote), treeweb-webdev
- RootsTech in-person & online (9M web participants (235 countries), 17.3k in-person (46 countries).
- Massive organization-wide effort to achieve full compliance with the European Accessibility Act of 2025 (our team's code was already fully compliant (yay!), and just received some minor modifications to improve the overall experience).
- Actually release shared family groups and community trees with a positive impact?
- Actually release data quality improvement efforts?

<details>
<summary>Technologies</summary>

- Zion: GitHub monorepo of 274 (+106 zion-ui) components with 40-minute build time (v13)
    - React, Storybook, Yarn, Linaria, Lerna, Babel, Jest, Cypress, NX (not really), ESLint8, Prettier, node 20
- Sonar Qube (Code Climate --> qlty, and refused to keep current, dropped)
- Heroku, moving next year to pure AWS machines
- Akamai
- Dynatrace
- JavaScript: React
- Split.io feature release management (662 active flags)
- GitHub Action-based application builds
- SauceLabs
- Slack + Microsoft Teams
- MASSIVE hype-laden push from management to "AI", with zero functional direction, since we were _already_ utilizing AI resources in our day-to-day development, analysis, and communication.

</details>

<details>
<summary>Footprint</summary>

**Apps owned by tree:**

<!--CONSIDER: Adding requests per hour and unique users per hour metrics from our right-sizing pages, and make sure that those metrics exclude monitoring like they should -->

* ancestors-r9
* group-management
* temple-r9
* tree-import-r9
* tree-lite (abandoned in August, despite being the only way that more than 800 unique patrons use FamilySearch, reserve 50 ordinances, and add 200 people to the tree each month, at a server cost of about $50)
* tree-person-r9
* tree-r9

**Shared components owned by tree (35):**

form (77 apps, 34 packages), person (32 apps, 33 packages), person-service (19 apps, 23 packages), pid (10 apps, 13 packages), add-find-flow (4 apps, 9 packages), attribution, click-to-copy, conclusion, error-page, gender-band, group-management, memory-tile, name-template, ordinances-reserve, ordinances-status, person-band, person-quality-score, relationship-viewer, research-help, search-partners, soft-launch, storage-sync, story-cache, story-recent-pids, suggested-reasons, tree-converter, tree-discussion, tree-groups, tree-pedigree, tree-person-info-cards, tree-pubsub, tree-recents, tree-route, tree-subnav-legacy, tree-types

</details>

## 2024

*Organization-wide restructure: Creation of engineering lead position; shuffling of directs; reallocation of engineers; combining of the two tree teams into one; new product owner; formalized process for originating story work; "new" 30-page proces for software development lifecycle; a mandated return to business casual and in-the-office one day a week for engineering; tons of extra reporting and paperwork; unrelenting pressure to deliver on stale deadlines, resulting in the temporary loaning of personnel from other teams for a month or two at a time, with very little positive impact.*

- Location: Hybrid (1 in-office, 4 remote), treeweb-webdev
	- We lost another two headcount on the tree team (one dev, one qa), leaving me the webdev on the team with the most experience with our codebase.
	- Tons of temp help assigned to our team for ~two-month stints, with very little impact on our true velocity (never more productive than typical interns), because our problem space is large and complicated (upper management also attempt near-shoring for three of our headcount).
	- Fortunately, we were also able to decommission or send off applications to other more appropriate teams (tree-import-r9, tree-place-standardizer).
- RootsTech in-person & online (4.8M web participants (232 countries), 16k in-person (43 countries), 2.1M participated in Relatives at Rootstech, with 5.9M relationships viewed and 420k chats sent to cousins).
- Spend the entire year writing and re-writing exceptions and extensions to support shared family groups and community trees.
- Migrate from CloudBees Flow to GitHub actions for application builds.
- Ryan write the sibling pedigree view by himself.
- Migrate last two remaining pedigree views from Polymer to React (descendancy & fanchart).
- Me:
  - Enhance Tyler's barebones imlpementation of a GitHub --> Slack notifier to include all necessary logic and features and security enhancements to fully replace my previous implementation made obsolete by moving from CloudBees Flow to GitHub Actions for our CICD pipeline (a dozen+ notifications every day).
  - Customize GitHub Action-based CICD configuration for all of our applications to work correctly and more efficiently.
  - Create `taskmaster` bash script that utilizes the Jira API to manage the tedium of adding labels, epic designations, hours, assignees, and rankings when adding active defects and recurring engineering maintenance stories to our sprints (18 maintenance tasks across two stories and ~20 defects every sprint). Shared with other teams.
  - Provide engineering expertise to QA by rewriting, adding intelligence to, streamlining logging from, testing, and documenting the `click()` function in `qa-shared-base`. Also help with linting and other integrations.
  - Create `release:translations {team-name}` script for zion monorepo, providing the ability to instantly draft package releases for those packages owned by a team with unreleased translation changes.
  - Enhance recents list to have a temporary stash for helper mode.

<details>
<summary>Technologies</summary>

- Zion: GitHub monorepo of 274 (+106 zion-ui) components with 40-minute build time (v13)
    - React, Storybook, Yarn, Linaria, Lerna, Babel, Jest, Cypress, NX (not really), ESLint8, Prettier, Travis CI (deprecated), node 20
- Code Climate
- Heroku, moving soon to pure AWS machines
- Akamai
- Dynatrace
- JavaScript: React (Polymer = deprecated)
- Split.io feature release management (662 active flags)
- SauceLabs
- Slack + Microsoft Teams
- GitHub Action-based application builds (CloudBees & Travis CI deprecated, with significant loss of features)
- Convert from VersionOne project management to Jira Cloud, with some significant hangups and drawbacks

</details>

<details>
<summary>Footprint</summary>

**Apps owned by tree:**

* ancestors-r9
* group-management
* temple-r9
* tree (deprecated)
* tree-import-r9
* tree-lite (iced)
* tree-person-r9
* tree-r9

**Shared components owned by tree (35):**

form (77 apps, 34 packages), person (32 apps, 33 packages), person-service (19 apps, 23 packages), pid (10 apps, 13 packages), add-find-flow (4 apps, 9 packages), attribution, click-to-copy, conclusion, error-page, gender-band, group-management, memory-tile, name-template, ordinances-reserve, ordinances-status, person-band, person-quality-score, relationship-viewer, research-help, search-partners, soft-launch, storage-sync, story-cache, story-recent-pids, suggested-reasons, tree-converter, tree-discussion, tree-groups, tree-pedigree, tree-person-info-cards, tree-pubsub, tree-recents, tree-route, tree-subnav-legacy, tree-types

</details>

<details>
<summary>Christmas (technically given time, but only allowed to work on approved items...)</summary>

- Fix the pieces of the `taskmaster` Jira maintenance script that were broken by the Jira Cloud migration.
- Fix the build history dashboard to handle new notification format, add helpful logging and comments, and update HOWTO instructions for synthesizing new data.

</details>

## 2023

- Location: Remote, treeweb-blue
	- Dumped onto tw-blue team, in an attempt to share team culture and engineering best practices to a half of the team without balance in their development habits.
- RootsTech back to in-person, but also online (3.6M web participants, 14.5k in-person, 128k hrs of viewed content).
- Active React migrations of the remainder of treeweb code halted to begin immediate development of family group and community edit trees, and the supporting sibling pedigree view (Ancestry.com clone).
- LLS mode added to React pedigree view for Search team.
- Me:
  - Share my build notification scripts with multiple teams and assist them in initial configuration: china, oral-genealogies, relatives-at-events, discovery, discovery-kids, shared-image-viewer, rootstech.
  - Manage pedigree Community feedback forum and persist React Landscape/Portrait Pedigree Views.
  - Create a Storybook entry that allows for viewing and filtering of all active Split flags, and quick links to search fs-webdev for usages for during the persisting process.

<details>
<summary>Technologies</summary>

- All babylon components moved to zion.
- Zion: GitHub monorepo of 131 (+104 zion-ui) components with 50-minute build time (v13)
    - React, Storybook, Yarn, Linaria, Lerna, Babel, Jest, Cypress, NX (not really), ESLint8, Prettier, Travis CI, node 20
- Code Climate
- Heroku, moving soon to pure AWS machines
- Akamai
- Dynatrace
- JavaScript: React (Polymer = deprecated)
- Split.io feature release management (479 active flags)
- CloudBees (formerly ElectricFlow), moving next year to pure GitHub action builds
- SauceLabs
- Slack + Microsoft Teams
- Travis CI
- Convert from VersionOne project management to JIRA, with some significant hangups and drawbacks

</details>

<details>
<summary>Footprint</summary>

**Apps owned by tree:**

* ancestors-r9
* app-status-dashboard
* group-management
* info-radiator
* temple-admin (deprecated)
* temple-r9
* tree (deprecated)
* tree-import-r9
* tree-lite (iced)
* tree-person-r9
* tree-place-standardizer (deprecated)
* tree-r9

**Shared components owned by tree (38):**

add-find-flow, ancestor-card, attribution, click-to-copy, conclusion, controlled-edit-trees, error-page, form, gender-band, group-management, memory-tile, name-template, ordinances-reserve, ordinances-status, performance-helpers, person, person-band, person-quality-score, person-service, person-summary, pid, relationship-viewer, research-help, search-partners, soft-launch, storage-sync, story-cache, story-recent-pids, suggested-reasons, tree-discussion, tree-groups, tree-pedigree, tree-person-info-card, tree-pubsub, tree-recents, tree-route, tree-subnav-legacy

</details>

<details>
<summary>Christmas (barely given time)</summary>

- Restructure GitHub team configuration and subscriptions as a precursor to combining the Tree teams.

</details>

## 2022

- Location: Remote, treeweb-gold
- Second year of purely online RootsTech Connect Conference (3.1M web participants, 22k hrs of viewed content).
- Create a tree onboarding experience, with registration changing to no longer require gender information.
- Hand off Conclusion component to tw-blue for phase 2 development for the person page.
- Release React First Ancestor Pedigree View.
- Release React Landscape/Portrait Pedigree Views.

<details>
<summary>Technologies</summary>

- Zion: GitHub monorepo of 113 (+60 zion-ui) components with 60-minute build time (v12)
    - React, Storybook, Yarn, Linaria, Lerna, Babel, Jest, NX, ESLint7, Prettier, Travis CI, node 16, terrible MFA SSO
- Code Climate
- Heroku, moving soon to pure AWS machines
- Akamai
- Dynatrace
- CloudBees (formerly ElectricFlow)
- SauceLabs

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

*Organization-wide restructure into geographically-focused projects--lose significant number ? of Tree developers, temporarily and permanently. These geo teams now have carte blanche for their activities and top priority on demanding resources or support for their efforts, and the remaining engineering teams must simply get more done with less.*

- Location: Remote, treeweb-gold
- First year of purely online RootsTech Connect Conference (1.5M web participants).
- Migrate off of SalesForce to Brightspot + JIRA.
- Create React-based person page and landscape/portrait pedigree views.

<details>
<summary>Technologies</summary>

- Zion: GitHub monorepo of 100+ components with 50-minute build time (v10)
    - React, Storybook, Yarn, Linaria, Lerna, Babel, Jest, Travis CI, node 14
- Code Climate
- Heroku, moving soon to pure AWS machines
- Akamai
- Dynatrace
- CloudBees (formerly ElectricFlow)
- SauceLabs

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
- Shift to remote after March.
- The first year of the organization-wide conversion to React. Begin development of complicated, highly shared components (person and add flow).

<details>
<summary>Technologies</summary>

- Zion: GitHub monorepo of ~50 components with 20-minute build time (v9)
    - React, Storybook, Yarn, Emotion, Lerna, Babel, Jest, ESLint6, Travis CI, node 14
- Code Climate
- Heroku
- Akamai
- Dynatrace
- JavaScript: React (Polymer = deprecated)
- CloudBees (formerly ElectricFlow)
- SauceLabs
- Slack + Microsoft Teams
- VersionOne

</details>

<details>
<summary>Christmas (sick)</summary>

- Stryker mutator integration with our babylon monorepo to identify true code coverage

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
- CODEOWNERS adopted through the organization to facilitate better automatic code review request management and explicit code ownership.

<details>
<summary>Technologies</summary>

- Heroku
- Akamai
- JavaScript: Polymer
- CloudBees (formerly ElectricFlow)
- SauceLabs
- Slack + Microsoft Teams
- VersionOne

</details>

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

- On-premise machines used for integration acceptance testing regularly fail because of test leftovers--schedule a daily restart to have each machine ready for each day, resulting in ~25% increase in build pass rate

</details>


## 2009

- Convert to GitHub for version control management.
