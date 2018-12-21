# p2p-social : the social network powered by your phone

## Why ?
The recent changes on tumblr have highlighted a number of problems with centralised social networks : they operate for profit. Despite this, the progress of decentralised, mostly federated networks like mastadon and diaspora have stalled. People seem to struggle with the idea of a federal network and can't get behind them, in addition to this, due to people overcrowding single instances, operating costs for the hosts of these federated networks are growing incessantly.

## What ?
A new, hybrid network, powered by p2p and coordinated by servers, which has the advantages of a traditional network like tumblr without the excessive operating costs.

## How ?
The biggest barrier to launching a new social network is capacity : With 72 million posts today, networks like tumblr require large scale storage to cope with demand, but what is ironic is that a social network in its very essence would function better as a peer to peer network.

The issue with this is that an always-on device is required to serve the content, except there are already 4.5 billion devices like  this on earth, and we all have one : our phones. When we plug them in to charge at night they sit idle, the combined storage potential of these devices could be incredible.

However, the network cannot operate using mobile devices alone, servers would be required to coordinate identities and help users discover content. This whitepaper aims to imagine a comprehensive vision of such a network, with the technical details required to build it, where possible, using existing technologies. It also aims to  set out a structure allowing for the management of the community based on a system of basic values.

## An invitation :
Thank you for taking the time to read this Introduction, The most important part of this project is your input : Everyone can contribute something, with no technical knowledge required, we will discuss the technical implementability of any ideas proposed here, The format of this repository is also up for discussion, Please feel free to open Issues concerning the layout or any of the aspects mentioned in the project, and pull requests with your ideas !

## Table of Contents

### The Client
[Posts](client/posts.md)

[p2p architecture](client/p2p.md)

[Reblogging & Liking](client/repost_like.md)

[User Identities on the Network](client/id.md)

### The Servers
[Identity Server](server/identity.md)

[Discover Servers](server/discovery.md)

### The Community
[Rewarding p2p contribution](community/reward.md)

[Moderation in the Community](community/mods.md)

[Stewardship and Operating Costs](community/stewardship.md)
