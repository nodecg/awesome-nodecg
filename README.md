# Awesome NodeCG [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of [NodeCG](http://nodecg.com) bundles and resources.

*Looking for bundles for an older version of NodeCG?
Check the [`old-versions`](https://github.com/nodecg/awesome-nodecg/blob/master/old-versions) folder.*

*Inspired by the [awesome](https://github.com/sindresorhus/awesome) list project.*

*Please read the [contribution guidelines](contributing.md) before contributing.*

## What is [NodeCG](http://nodecg.com)?
NodeCG is a broadcast graphics framework and application. It provides an API and structure for making dynamic graphical assets for broadcast use. NodeCG graphics packages are called "bundles". NodeCG is primarily aimed at [Twitch](http://www.twitch.tv/) broadcasters using [Open Broadcaster Software](https://obsproject.com/), but is usable in any environment that can render HTML, including [CasparCG](http://casparcg.com/).

Still not clear on what NodeCG is and what it is used for? These videos go over some of the more prominent uses of NodeCG:
 - [Tip of the Hats 2015 Graphics Overview](https://www.youtube.com/watch?v=Z4-qaya5-0Y)
 - [Awesome Games Done Quick 2016 Graphics Overview](https://www.youtube.com/watch?v=oAzj9Zddogs)

Want to suggest a bundle for inclusion? Open a PR!


## Table of Contents
- [Service Integrations](#service-integrations)
  - [Twitch](#twitch)
  - [Beam](#beam)
  - [Stream Tip](#stream-tip)
- [Media](#media)
- [Misc](#misc)
- [Dashboard Polymer Elements](#dashboard-polymer-elements)
- [Complete Systems](#complete-systems)
  - [Full Systems](#full-systems)

## Service Integrations

### Twitch
* [lfg-twichapi](https://github.com/SupportClass/lfg-twitchapi) - Lets other bundles easily query the Twitch API on behalf of a logged in user.
* [nodecg-twitch-chat](https://github.com/denolfe/nodecg-twitch-chat) - NodeCG bundle which loads Twitch chat as a dashboard panel.
* [nodecg-dashboard](https://github.com/denolfe/nodecg-dashboard) - NodeCG bundle showing viewers, followers, uptime, and stream title.

### Beam
* [nodecg-beam](https://github.com/rfox90/nodecg-beam) - Hooks into beam api and sends out Follower & Sub Events.

### Stream Tip
* [lfg-streamtip](https://github.com/SupportClass/lfg-streamtip) - Exposes a simple API for StreamTip integration.

## Media

* [lfg-sounds](https://github.com/SupportClass/lfg-sounds) - Manage and play sounds.
* [mmcn-google-tts](https://github.com/MattMcNam/mmcn-google-tts) - Provides an API to Google TTS.

## Misc

* [lfg-omega13](https://github.com/SupportClass/lfg-omega13) - Places a button on the dashboard that users can press to send a notification to an administrator's phone.
* [lfg-hypetrain](https://github.com/SupportClass/lfg-hypetrain) - Provides an API for tracking "hype trains", chains of events occuring one after another such as a series of subscription events on a Twitch channel.
* [lfg-filter](https://github.com/SupportClass/lfg-filter) - Filter words and email addresses based on a user-editable blacklist.

## Dashboard Polymer Elements
These are [Polymer](https://www.polymer-project.org/1.0/) elements meant to be used as part of a dashboard panel.
Think of them as building blocks that can be used to speed up development time of a panel.
* [nodecg-toggle](https://github.com/NodeCGElements/nodecg-toggle) - Toggles the boolean state of a Replicant.
* [nodecg-toast](https://github.com/NodeCGElements/nodecg-toast) - An implementation of paper-toast designed to work well in NodeCG dashboard panels.
* [nodecg-replicant-input](https://github.com/NodeCGElements/nodecg-replicant-input) - A [`<paper-input>`](https://github.com/PolymerElements/paper-input) element that has two-way binding with a Replicant.
* [nodecg-corner-select](https://github.com/NodeCGElements/nodecg-corner-select) - A UI element for selecting one of four corners, useful when making graphics that the user may need to reposition.
* [nodecg-replicant](https://github.com/NodeCGElements/nodecg-replicant) - A declarative way of using Replicants, best used as part of other Polymer elements.

## Complete Systems
* [agdq16-layouts](https://github.com/GamesDoneQuick/agdq16-layouts) - The on-stream graphics used during Awesome Games Done Quick 2016.
* [nodecg-for-smash](https://github.com/mparkms/nodecg-for-smash) - A set of components targets at Super Smash Bros. Melee.
* [nodecg-speedcontrol](https://github.com/charleon/nodecg-speedcontrol) - Fully fledged speedrun marathon overlay system automating otherwise time-consuming tasks

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the NodeCG team has waived all copyright and related or neighboring rights to this work.
