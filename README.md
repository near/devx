# Welcome to DevX at NEAR!

This is the place to find out what we're adding to our developer tools and experiences, see how you can contribute, and see who on the core team is a good person to ask questions to.

## What am I looking at?

This is where DevX for the NEAR collective is managed. You'll want [ZenHub](https://www.zenhub.com/) (A project management extension for GitHub issues) to see the overall epics. You can view what's in progress in the issues without it. If you have ideas for what you'd like to see specific to your experience as a developer, this is a great place to suggest.

## How do I use this repo?

You can submit an issue like any other repo. These are automatically added to the `icebox` and we review these each Tuesday at 9am PST in sync. We also watch this outside of that time.

## DevX Sync | 9-Jun-2020

### Agenda/Notes

* Contributions
  * Have a clear set of instructions with a clear end goal
  * Self-service contributions where people pick up issues.
    * Lack context
  * Peter and Sherif set up a call DM
  * Internal presentation on how to contribute DevX
    * Best practices
    * Form
    * External docs contributors
  * Suggestion: Scope the time we spend on this
* Addressing external issues SLA
  * Default assignees in the issues
* Issues submitted across repos
  * Transfer issue!
  * "Can we fix the issue with transferring issues to nearcore?"
  * Submit to devx repo if it's a vertical slice across multiple modules.
* We need someone to do a presentation on stuff
  * TBD
* GitCoin Hackathon next week Requirements
  * 1 workshop, 30min
  * Support from 15th - 29th
* Batch transactions
  * Timeline: Need to write more tests and publish. End of week.

## DevX Sync | 2-Jun-2020

### Agenda/Notes

* StakeX
  * "How and why we designed near-shell, nearup etc." - Designed for designers
    * Need: Automation for what's happening on nodes
    * Headless ("The less interaction from a human, the better")
      * launch a node
      * login
      * "Scripts that people can deploy, and parse the output for success or failure without needing to sit there and type in commands"
    * See [the epic here](https://github.com/near/devx/issues/169)
    * On the node, we're short on memory and storage.
      * Request: offline RPC
        * E.g. not every node needs to have an open json PRC, some nodes are just network nodes.
        * Connected to Prometheus
    * **Need: Set of docs to describe these actions**
      * Low level operations
        * Generate, update, backup keys
        * E.g. "How can I use the same key across multiple shells"
      * See the [stake wars repo for examples of challenges to update](https://github.com/nearprotocol/stakewars).
* Embedding
  * "Removes guesswork from hypotheses"
    * After a meeting with Flux, issues were created directly from input with them.
  * Basic project management has been helpful as well
  * "We should do more of this"
  * Next week: "How long are we going to do this with Flux?"
    * Intuition: June Launch coordination
* Metrics discussion
  * There's a [new epic](https://github.com/near/devx/issues/193) from a lack of granularity
* Shaping vs instant implementation
  * We going to do more of this.
* Docs
  * Presenting on calendar about new process on Monday.
  * Google Drive --> "All Hands"
  * Repo has been groomed
  * DevX team: "Pick an epic, you're responsible for closing it within 10 business days."
    * Each epic is a collection of related issues.
    * Suggestion: "Everyone on the DevX team pick and own (within 24 hours) it until completion"
* Board
  * Clean up finished tasks
  * "We need a set way of setting this up"
* We should do an example cleanup and round 2 sprinteroo
* Embedding reports
  * Ends at the end of this week.
  * Follow up meetings

## DevX Sync | 27-May-2020

### Agenda/Notes

* Hot Topics
  * Migration process
    * We have 4 apps in deployed. These need process for deploying to MainNet
    * As a developer on NEAR, I want to deploy to MainNet.
    * Timeline: defined by projects.
    * Requirements: We will get the scope of the project and define what we need to accomplish a migration.
  * Embedded Engineers: Starts this week
    * Full time?
      * ~1.5 weeks
    * It needs to be top down.
    * OWC side of Flux
      * Embedding was really good learning
    * Mike focusing on value to the Near repos
    * We may need a formal agreement for embedding
  * Activity in StakeX
    * Priotitize higher
  * Requests
    * Rev
      * Rec: If we spend time on this, we capture the output
      * Async on this
  * Hackathon Update
    * 90 people signed up
    * 11 projects
    * "It was awesome"
  * Docs rotation
    * Get presentation on All hands
  * Tokens
    * NFT
      * Rust - README in flight
        * (Here's how to build, here's how to test)
      * AS - Done
    * FunToken
      * Rust - README
      * AS - Draft

## DevX Sync | 19-May-2020

### Agenda/Notes

* Hot Topics
  * Requests
    * Rev hackathon mini sessions
      * Volunteers
        * Peter: Intro
        * Jane: Idea Review
        * Sherif: AS Workshop
        * Mike?
    * UW Hackathon workshops
      * 24th = Judging
      * Two on Fri
      * Two hours
        * Near-api-js (1pm PST Chad)
        * Intro to rust (Mike)
    * Access Keys
  * BD: Embedded Engineers
    * Next three months
    * StarDust would want this
    * Flux: Starting project
      * Sasha, Mike, Flux, Me.
      * Set up embedded engineer kick off
        * Set expectations for scope of work
          * Can we record stuff?
          * Are they open source?
        * Agree on a task
  * Marketing: Smoke Tests on ideas
    * Market first
    * Peter aggregates ideas worth testing
      * Set up process for this
    * Lifecycle
      * Test Value Prop for conversion rate
      * Use for testing language for apps already building. Link to "case studies" from our home page.
        * Put case studies on our website and A/B test the language.
  * Working with other teams/cross team dependencies
    * How are we going to address this?
    * As a team, it would be helpful to have a heads up.
  * Metrics
    * Needs calibration
  * NFT and FunToken status (Punted)
  * Docs Rotation (Discussing later)
  * Interactive Demo (Project Poke Bowl)

## DevX Sync | 12-May-2020

### Agenda

* Hot Topics
  * Oracle Contracts ~happy path = 2 weeks knocked out
    * nLINK needs work
    * Some of the parts are unknown unknowns
  * What's next
    * Examples and Partner stuff
    * MultiSig
      * Clean up
    * Fungible Token Example
    * Clean NFT
    * Key Value Store
    * Research tasks: Multi contract apps (and how to manage them)
    * Upgrade and Migration Example/Guide
      * These are multiple examples
        * E.g. one contract vs multiple contract
      * "I myself have problems update delegation contract" this happens every three days.
      * Research: Proxy Contract Methods and Functionality
  * Something Pokeable
    * Corgiland, corgimarket.
    * "These are the killer features of NEAR"
    * "Our MainNet is not a ghost town, here's what you can do with NEAR."
    * Design meeting:
      * Project Poke Bowl - *Real Apps for Real Shit®*
* Board

* **Delegator App**
  * Smart Contract is done
  * Needs Frontend from @Matt
  * A first pass = Example app where someone delegates to a hardcoded delegator

### Retro

* Good
  * RL1 = awesome!!!!
  * Mike creating a bunch of tickets was awesome
  * Creating tickets is a good on-demand tool for a bunch of small things
  * Tests are green
  * Dependabot is good
  * Workshops were great
  * Sherif and Willem's workshop work has permanent staying power
  * Stress can begalvanizing
* Bad
  * Timeouts
  * There is so much stuff to get across in a workshop, it's hard to not rush
  * Slack
  * We have an aligning conversation, then it's every man for themselves
* Improve
  * Make sure we don't drift into ambiguous territory
  * Workshops should be longer! 1.5 hrs
  * Our issues list keeps growing. Needs to be processed.
    * Projects that we are owning needs a process for cleaninng out the issues queue
  * Scoping and estimation
  * Align more: "Have a conversation as a team about what tech stack we want to use"
  * Making sure we know what the experience is like on the developer side. Dogfooding.
  * We haven't approved NEP for shell, but we're cherry picking features.

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
