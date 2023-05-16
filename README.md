### Hello there, welcome to Jay Revolinsky's CSCI 630 Profile!

## Contributions

### Highlights

* Coordinated the SKU Lookup Feature with code contributions - ChicoState/PantryNode#174 - Responsible for [research](https://github.com/ChicoState/PantryNode/discussions/37#discussioncomment-5186509), [planning](https://github.com/ChicoState/PantryNode/issues/25), [design](https://github.com/ChicoState/PantryNode/pull/176#issuecomment-1524696301), [coordination](https://github.com/ChicoState/PantryNode/pull/176), and major portions of [implementation](https://github.com/ChicoState/PantryNode/pull/176/commits/fde6c2de41c2d4f0bcbd0da04340a62d23ba6e53) which originally involved using the Proxy design pattern to lazy load the [OpenFoodFacts API](https://github.com/ChicoState/PantryNode/discussions/37#discussioncomment-5745127) and implementing the PLU codes into the Database based on which was relevant for the user. Updated implementation simplified but similar to Proxy.
* Coordinated design and pair programmed for major portions of DonorLookup feature: https://github.com/ChicoState/PantryNode/issues/193#issue-1682051340 with detailed breakdowns for advanced search, scanner, and edit functionality: [Issue 232](https://github.com/ChicoState/PantryNode/issues/232), [Issue 233](https://github.com/ChicoState/PantryNode/issues/233), [Issue 234](https://github.com/ChicoState/PantryNode/issues/234)
* Programmed the backend for the On-Demand Report Feature: [PR 226](https://github.com/ChicoState/PantryNode/pull/226), which involved updates to the database, dummy data, route authentication, and additional Sequelize functions for total donations, total checkouts, and unique checkouts.

#### Note: Many of the rows marked as 'Design' are tied to issues generated for 'Bug Logging' to improve visibility to other contributors. Something that I call 'Design' is also effectively 'Bug Logging'.

### PantryNode

| Type       | Link                     | Notes                                      |
|------------|--------------------------|--------------------------------------------|
| Dev Ops     | ChicoState/PantryNode#41 | Assisted with research and programming that enabled build step on push to main.        | 
| Dev Ops     | ChicoState/PantryNode#47 | Added README instructions to run ESLint locally.    | 
| Feature    | ChicoState/PantryNode#25 | Research for SKU lookup feature.                      | 
| Pair Programming  | ChicoState/PantryNode#40 | Troubleshooting/Programming with [reembot](https://github.com/reembot) to get the linter running locally.  |
| Pair Programming| [Assisted SKU Feature](https://github.com/ChicoState/PantryNode/pull/132)| Assisted development and programming of Initial SKU Feature with [Yashvi](https://github.com/ysiddhapura) |
| Pair Programming| [Donor Lookup Feature](https://github.com/ChicoState/PantryNode/issues/193)| Pair Programming w/ [Yashvi](https://github.com/ysiddhapura) on Frontend and assisted with Full-Stack components of Donor Lookup Feature  |
| Programming| [Integrated Frontend Linter](https://github.com/ChicoState/PantryNode/pull/150)| Assisted Frontend Team with Linter Configuration and Debugging. |
| Programming| [SKU Feature](https://github.com/ChicoState/PantryNode/pull/176)| Design, Programming, Coordination of the SKU Feature w/ [Yashvi](https://github.com/ysiddhapura), [reembot](https://github.com/reembot), [Parth](https://github.com/parthpandey1), [Jooms](https://github.com/Jooms), [Anoushka](https://github.com/Anoushka444) |
| Programming| [On-Demand Report Backend](https://github.com/ChicoState/PantryNode/pull/226)| Implemented Sequelize functions to return all donations, checkouts and unique donations. Programming and troubleshooting w/ [reembot](https://github.com/reembot) on handling dummy data to update functions properly, updated routes to have proper authentication. |
| Code Review | ChicoState/PantryNode#35 | Enable build step for all PRs.             |
| Code Review | ChicoState/PantryNode#53 | Resolved linter semicolon issues w/ [Anoushka](https://github.com/Anoushka444).          |
| Code Review | [ReadMe updates](https://github.com/ChicoState/PantryNode/pull/163)| Better Backend Instructions |
| Code Review | [Stock routes for inventory](https://github.com/ChicoState/PantryNode/pull/154)| Views for handling stock routes/models|
| Code Review | [Docker Fix](https://github.com/ChicoState/PantryNode/pull/149)| Assisted in resolving docker issues, found root cause of problem thanks to [Shubham](https://github.com/shubhamlatkar), worked with [briswells](https://github.com/briswells) and [Hardik](https://github.com/hardikpatil) to get PantryNode running properly.  |
| Code Review | [Linter Overrides Fix](https://github.com/ChicoState/PantryNode/pull/103)| Reviewed and assisted with linter overrides w/ [Reema](https://github.com/reembot), [Jooms](https://github.com/Jooms), [Anoushka](https://github.com/Anoushka444) |
| Code Review | [Route Authentication](https://github.com/ChicoState/PantryNode/pull/239)| Reviewed route authentication fix|
| Research   | [SKU Feature Discussion#37](https://github.com/ChicoState/PantryNode/discussions/37) | Research on SKU Feature, that determined [Quagga](https://github.com/ericblade/quagga2) would be a better option for our initial purposes than [ZXing](https://github.com/zxing/zxing).                     |
| Research   | [Linter Frontend Build Error](https://github.com/ChicoState/PantryNode/issues/181#issuecomment-1520646559)| Frontend Build w/ Linter Investigation, found that there were two possible options to alleviate problem where linter on 'let vs. var' caused build options to fail. Choose to enforce strict standards to avoid future problems. |
| Discussion | [Game Plan Discussion#71](https://github.com/ChicoState/PantryNode/discussions/71) | Game Plan Discussion, started with baseline update from CI team to provide reference for other teams to get up-to-speed on finished CI/CD deployment.                     |
| Discussion | [Future Feature Discussion#54](https://github.com/ChicoState/PantryNode/discussions/54) | Future Feature Discussion, started the SKU Lookup feature discussion here.                 |
| Discussion | [SKU Updates discussion](https://github.com/ChicoState/PantryNode/discussions/37#discussioncomment-5665000)| Discussed updated design for SKU |
| Discussion | [Original Project Requirements discussion](https://github.com/ChicoState/PantryNode/discussions/65#discussioncomment-5654791)| Discussed the current project design and how it related to the original project's design, updated the list to include links to appropriate issues and discussions. Determined that [complete backend updates](https://github.com/ChicoState/PantryNode/discussions/65#discussioncomment-5775245) were not necessary to build the same high-level functionality in this project as the original project. |
| Design     | ChicoState/PantryNode#227 | Item Quantity and Availability lookup feature, came up with tasks necessary to bring feature up-to-par with original project.                 |
| Design     | ChicoState/PantryNode#193 | Donor Lookup Feature Design w/ [Yashvi](https://github.com/ysiddhapura), [Parth](https://github.com/parthpandey1), [Anoushka](https://github.com/Anoushka444)                 |
| Design     | ChicoState/PantryNode#25 | SKU Design and subtask creation w/ [Jooms](https://github.com/Jooms), created an ER diagram to simplify functionality implementation.                |
| Design     | [223](https://github.com/ChicoState/PantryNode/issues/223#issuecomment-1530092191)| On-Demand Report generation design w/ [Parth](https://github.com/parthpandey1), determined that there was a significant amount of overlap between the Summary frontend and initial On-Demand Report Design.
| Design     | [Issue #232](https://github.com/ChicoState/PantryNode/issues/232) | LookupDonor Search Functionality Design, generated an issue and designed the implementation of a foundational search functionality for the donor lookup feature into a modular design that can be built upon to include more advanced features.              |
| Design     | [Issue #233](https://github.com/ChicoState/PantryNode/issues/233) | LookupDonor Edit Functionality, similar to the search functionality except considered advanced features for modular design, like the possibility of a memento to allow users to easily edit their donations.               |
| Design     | [Issue #234](https://github.com/ChicoState/PantryNode/issues/234) | LookupDonor Scanner Functionality, generated an issue and designed the implementation of a foundational scanner functionality for the donor lookup feature that integrates the current work from the SKU feature into a modular design that can be built upon to include more advanced features.               |
| Design and Programming | https://github.com/ChicoState/PantryNode/issues/174 | Built SKU Lookup feature backend w/ [briswells](https://github.com/briswells)               |
| Design and Programming | https://github.com/ChicoState/PantryNode/issues/193 | Donor Lookup Feature w/ [Yashvi](https://github.com/ysiddhapura), [Parth](https://github.com/parthpandey1), [Anoushka](https://github.com/Anoushka444) created an ER diagram for easy reference that was progressively updated.       |


### Timeline

* Sprint #1 - Started Feb 27th, 2023
  - DC - ChicoState/PantryNode#25 
  - CR - ChicoState/PantryNode#35 
  - PR - ChicoState/PantryNode#40 
  - PR - ChicoState/PantryNode#41 
  - PR - ChicoState/PantryNode#47 
* Sprint #2 - Started Mar 21st, 2023
  - CR - ChicoState/PantryNode#53
  - DC - https://github.com/ChicoState/PantryNode/discussions/37
  - DC - https://github.com/ChicoState/PantryNode/discussions/71
  - DC - https://github.com/ChicoState/PantryNode/discussions/54
  - DS - https://github.com/ChicoState/PantryNode/issues/25#issuecomment-1481816313
* Sprint #3 - Started April 4th, 2023
  - PR - https://github.com/ChicoState/PantryNode/pull/150
  - PR - https://github.com/ChicoState/PantryNode/pull/132
  - CR - https://github.com/ChicoState/PantryNode/pull/163
  - CR - https://github.com/ChicoState/PantryNode/pull/154
  - CR - https://github.com/ChicoState/PantryNode/pull/149
  - CR - https://github.com/ChicoState/PantryNode/pull/103
  - DC - https://github.com/ChicoState/PantryNode/discussions/37#discussioncomment-5665000 , https://github.com/ChicoState/PantryNode/discussions/37#discussioncomment-5665052
  - BL - https://github.com/ChicoState/PantryNode/issues/174
  - BL - https://github.com/ChicoState/PantryNode/issues/193
* Sprint #4 - Started April 18th, 2023
  - PR - https://github.com/ChicoState/PantryNode/pull/176
  - PR - https://github.com/ChicoState/PantryNode/pull/221
  - PR - https://github.com/ChicoState/PantryNode/pull/226
  - DS - https://github.com/ChicoState/PantryNode/pull/176#issuecomment-1524696301
  - DS - https://github.com/ChicoState/PantryNode/issues/193#issue-1682051340
  - DC - https://github.com/ChicoState/PantryNode/issues/181#issuecomment-1520646559
* Sprint #5 - Started May 2nd, 2023
  - BL/DS - https://github.com/ChicoState/PantryNode/issues/175
  - BL/DS - https://github.com/ChicoState/PantryNode/issues/232
  - BL/DS - https://github.com/ChicoState/PantryNode/issues/233
  - BL/DS - https://github.com/ChicoState/PantryNode/issues/234
  - DC - https://github.com/ChicoState/PantryNode/discussions/65#discussioncomment-5775245
  - PR - https://github.com/ChicoState/PantryNode/pull/226
  - CR - https://github.com/ChicoState/PantryNode/pull/239

**Key:**

- **PR** - PullRequest - I contributed code.
- **CR** - CodeReview - I reviewed someone's change.
- **BL** - BugLogging - I filed a GitHub Issue.
- **DS** - Design - I designed a solution to an Issue.
- **DC** - Discussion - I started a discussion or discussed a topic relevant to the project

