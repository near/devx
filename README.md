# Welcome to DevX at NEAR!

This is the place to find out what we're adding to our developer tools and experiences, see how you can contribute, and see who on the core team is a good person to ask questions to.

## What am I looking at?

This is where DevX for the NEAR collective is managed. You'll want [ZenHub](https://www.zenhub.com/) (A project management extension for GitHub issues) to see the overall epics. You can view what's in progress in the issues without it. If you have ideas for what you'd like to see specific to your experience as a developer, this is a great place to suggest.

## How do I use this repo?

You can submit an issue like any other repo. These are automatically added to the `icebox` and we review these each Tuesday at 9am PST in sync. We also watch this outside of that time.

## DevX Sync | 28-Apr-2020

### Agenda

* Hot topics
  * Ask for resources from DevX
    * Features: Included in the upcoming releases
    * Needs for NodeX and staking
    * Answer: Add an epic and issues to the DevX board. Communicate their priority to the team.
  * Metrics (Where they at?)
    * (Shell metrics are landing now)
    * Next step: Testing in mixpanel
  * URL change
    * It was going to happen, but it's blocked on hours (maybe minutes) scale.
  * RL1/MainNet Prep
* Board
* Gotta get done
  * Fix awesome-near Gatsby setup #141
  * Fix config.js in Guest Book example #144
  * Update Cargo.toml for Rust Status Message example #145
  * Update Wallet Example's config.js #146
  * Proof of Work faucet example #147
  * Token contract AS work #148
  * Counter example fixes #149
  * Fix examples nightly CI #150
  * High level cross contract example needs integration tests #142
  * Rust fungible token integration test #143
  * Workshops Epic
  * Bug Bash
    * Schedule bug bash Peter

### Deliverables

* Metrics @potatodepaulo runs point on testing in Mixpanel.
  * TODO: Error handling
  * Erik wants a weekly update on returning active users.
  * Anais wants community-oriented goals.
    * Several devs ask: "Where can I go to get started?"
    * Response from devx varies.
* URL Change from nearprotocol.com --> near.org (Punting to after RL1)
  * Full on redirects for everything.
    * Except: helper, rpc and wallet
    * Communicate to developers
      * rpc.testnet.near.org
      * wallet.testnet.near.org
* Workshops
  * In progress and will be done before RL1
  * Needs final polish
  * Scheduled in RL1
* Cleanup Sherif

## DevX Sync | 21-Apr-2020

### Agenda

* Retro
* Board
  * Planning doc
* Hot topics
  * Trying things and getting punished for it
    * [Principle of Charity](https://en.wikipedia.org/wiki/Principle_of_charity)
  * RL1 Hackathon
  * Checklist: RL1 issues and mainnet needs
    * Needs swarming
  * BD + DevX process
    * Let's start on bigger companies
    * Needs devx help
  * DAOjam Hack @Peter sets up task force for collecting feedback.
  * Friday hackathon
    * Collect devx feedback
    * Pull out actionable
    * Rust cross-contract doesn't work
    * Talk to Amos about platform
    * Talk to Alexandra

### Deliverables

* Workshops @amgando
  * Propogate the form for submitting broadly
  * All submitted by Thursday
  * Tested and ready to go by May 6th
* Automated Docs
  * Needs: "The docs are in these locations" √ @chadoh
  * Next step: "Link to them in docs" @amgando
* Zero to Hero Tutorial
  * Backlogged: "Finish the new example (needs UI)" @janedegtiareva
* Gas Estimates
  * Needs: "runtime --> wasm"
  * Next steps: "wrap CLI, user flow and example code"
* Shell 
  * NEP fleshed out @mikedotexe
  * Immediate needs
  * Metrics: PR in for flow of logging in mixpanel on one shell command
    * Next steps: @vgrichina and @kendall draft PR for logging NEAR Shell logins
* TLD Epic
  * @janedegtiareva: https://github.com/nearprotocol/near-shell/issues/307
  * @chadoh: https://github.com/nearprotocol/nearcore/issues/2292
* RL1 Hackathon @SkidanovAlex
  * Do things people know
  * Prizes: long tail not winners
  * Platforms on NEAR have their own track where you can get a prize from NEAR collective
* BD + DevX process (Two week timeline) @potatodepaulo
  * **Needs**
    * Two pieces
      * Requests - needs a communication cycle
      * Larger companies that should/want to build on NEAR
    * Top of funnel
      * Root the pitches in good engineering

### Retro

* Good
  * Friday hackathon was good to have
    * Led to a list of things that went right/wrong
  * Enjoyed writing some Rust stuff for the Oracle
    * Good case where we use the examples for coding
  * Stefano's buddy is going to pick up some contract stuff
* Bad
  * We're not there on Rust support
    * Assumption: people don't know Rust
  * Miscommunication
    * We don't need to write an oracle? Do we.
  * Competing priorities
* Improve
  * More examples and docs for Rust^

## DevX Sync | 14-Apr-2020

### Agenda

* retro
* board
* hot topics
  * Hackathons
    * A discussion next week
    * @potatodepaulo to send notes on Dao jam
  * Status Check
    * Zero to Hero tut/workshop (and oracles)
    * Template for workshops (Haven't seen one)
  * Reports
  * Ready Layer One Prep

### Retro

* Good
  * We had explicit conversations about priorities
  * Time to work on content
  * Focused on one theme with workshops during the week.
  * Docs are coming along.
  * Sherif's flow for the workshops was good. Ownership of an epic is good. Pointing out where someone can get involved is helpful.

* Bad
  * First attempt at priority: the situation with back and forth priorirty is distracting.
  * Oracle priority changed, which took time away from other focus
  * Still working in isolation.
  * Most of my work was in the wrong direction. It would have been alleviated up front.

* Improve
  * We're not fully in the loop with RL1. We should
  * More early signal on shared tasks. "I want to predict waht someone is focused on at a high level".
    * Try: add more structure to standup.
  * Whenever we notice something coming up, pull in one other person.
  * Increase ownership of epics and delegation for subtasks.

### Notes

* Workshops
  * [Example for Workshops E.g. ](https://docs.google.com/document/d/1yfj_VkJa4uoUCK9SKglL29b32a47grlYuaT6JiHg7jo/edit#heading=h.4ic8dx4l8lvo)
  * This looks good, but it's totally untested
    * TODO: Test the workshops.
      * @AnaisUrlichs: test the workshops by thurs.
        * Testing: Sync with Sherif on confidence that this is going to fly. Monday, the results are due. (Preferably with a demo in All hands meeting)
  * Commitment to workshops **3**
    * Ownership: @amdando holds 2, @mikedotexe holds 1, @janedegtiareva holds 1.
    * Unkown: How much is needed from me in order for you to make the workshops?
    * Unkown: Process with templates
* Automated Docs | finished by end of week
  * @chadoh circling back
  * comments/documentation still progress
* Cleaning Stuff Up @potatodepaulo meeting
* Estimate gas usage
  * Gas Estimate communication POC in progress. https://github.com/near/devx/issues/46
* Metrics
  * @janedegtiareva owns shell side.
    * First priority for the week.
  * @vlad owns wallet side implementation.
  * @kendall owns PMing for wallet side metrics
