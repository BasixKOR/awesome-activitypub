# Awesome ActivityPub [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![License: CC0](https://img.shields.io/badge/License-CC0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/) ![Status: WIP](https://img.shields.io/badge/status-WIP-red.svg)

[<img src="https://rawgit.com/BasixKOR/awesome-activitypub/master/ActivityPub-logo.svg" align="right" width="400">](https://activitypub.rocks/)

> Curated list of ActivityPub-based Projects!

[ActivityPub](https://www.w3.org/TR/activitypub/) is W3C standard, decentralized social networking protocol.

Note: This list is outdated. Please see [delightful fediverse apps](https://codeberg.org/fediverse/delightful-fediverse-apps) for latest information.

## Contents
* [Specifications](#specifications)
* [Services](#services)
* [Implementations](#implementations)
* [Libraries](#libraries)
* [Bridges](#bridges)
* [Community and Advocacy Groups](#community)

## Specifications
Information for developers and implementers.

* [ActivityPub Website](https://activitypub.rocks/) - The official website of ActivityPub protocol.
* [W3C ActivityPub Standard](https://www.w3.org/TR/activitypub/) - The standard document of ActivityPub.
* [ForgeFed](https://forgefed.peers.community/) - Federation protocol for interoperable project management and source code hosting services (aka: forges).

## Services
Services supporting ActivityPub federation.

* [Dokieli](https://dokie.li/#introduction) - A clientside editor for decentralised article publishing, annotations and social interactions.
* [Funkwhale](https://funkwhale.audio/) - A modern, self-hosted, free and open-source music server.
* [Hubzilla](https://project.hubzilla.org) - Macroblogging social network supports Zot, OStatus, diaspora, ActivityPub.
* [Mastodon](https://joinmastodon.org/) - Microblogging service based on ActivityPub and OStatus protocol.
* [Misskey](https://github.com/syuilo/misskey) - Microblogging service based on ActivityPub.
* [PeerTube](https://github.com/Chocobozzz/PeerTube) - Video streaming platform with ActivityPub and WebTorrent.
* [BookWyrm](https://joinbookwyrm.com/) - A social network for tracking your reading and talking about books.
* [PixelFed](https://pixelfed.org/) - Federated Image Sharing.
* [Pleroma](https://pleroma.social/) - Lightweight microblogging service based on ActivityPub and OStatus protocol.
* [Plume](https://github.com/Plume-org/Plume) - Federated blogging engine with ActivityPub.
* [Prismo](https://gitlab.com/mbajur/prismo) - Federated link aggregation powered by ActivityPub.
* [Rustodon](https://github.com/rustodon/rustodon) - A Mastodon-compatible, ActivityPub-speaking server in Rust.
* [anancus](https://gitlab.com/tuxether/anancus) - Self-hosted and federated social link aggregation.
* [anfora](https://github.com/anforaProject/anfora) - Self-hosted photo gallery social network.
* [distbin](https://distbin.com/about) - Distributed Pastebin, support ActivityPub and Micropub.
* [microblog.pub](https://microblog.pub/) - A self-hosted, single-user, ActivityPub powered microblog.
* [write.as](https://write.as/about) - A distraction-free writing space with ActivityPub support.
* [Nextcloud Social](https://github.com/nextcloud/social) - Federated social network application on Nextcloud.
* [ActivityPub for WordPress](https://wordpress.org/plugins/activitypub/) - An ActivityPub plugin for WordPress.
* [ActivityPub for Drupal](https://www.drupal.org/project/activitypub) - An ActivityPub module for the Drupal open-source digital experience platform.
* [Mobilizon](https://joinmobilizon.org/en/) - A federated organization and mobilization platform.
* [Socialhome](https://socialhome.network/) - A federated personal profile with social networking functionality. 
* [Lemmy](https://github.com/dessalines/lemmy) - Building a federated alternative to reddit in rust.
* [NodeBB](https://nodebb.org) - Self-hosted Node.js based community forum software.
* [lotide](https://sr.ht/~vpzom/lotide/) - Federated forum / link aggregator using ActivityPub.
* [castling.club](https://castling.club/) - Chess over ActivityPub.
* [GoToSocial](https://github.com/superseriousbusiness/gotosocial) - A ActivityPub social network server, written in Golang.
* [Gancio](https://gancio.org) - A federating event server focusing on content.
* [Castopod](https://castopod.org) - Specialiced for podcasts.
* [Mbin](https://github.com/MbinOrg/mbin) - A federated content aggregator, content rating, dissussion and microblogging platform
* [Postmarks](https://github.com/ckolderup/postmarks) - A single-user bookmarking server for the Fediverse.
* [Shuttlecraft](https://github.com/benbrown/shuttlecraft) - A single-user ActivityPub server.
* [Social Inbox](https://github.com/hyphacoop/social.distributed.press) - Social Inbox API enables your website to receive followers and their comments from the Fediverse
* [Social Reader](https://github.com/hyphacoop/reader.distributed.press) - A peer-to-peer, offline ActivityPub client for reading and following microblogs on the Fediverse.
* [Takahē](https://github.com/jointakahe/takahe) - a multi-domain ActivityPub social network server, written in Python.
* [NeoDB](https://github.com/neodb-social/neodb) - an ActivityPub server tracking and review what you read/watch/listen/play.
* [Firefish](https://firefish.dev/firefish/firefish) - a popular Misskey fork with many additional features
* [Akkoma](https://akkoma.dev/AkkomaGang/akkoma/) - a popular Pleroma fork with many additional features
* [Bonfire](https://github.com/bonfire-networks/bonfire-app) - a federated digital spaces, written in Elixir
* [Hollo](https://hollo.social/) - A federated single-user microblogging software.

## Implementations
Simple example of implementing ActivityPub.

* [ActivityPub Example](https://github.com/tOkeshu/activitypub-example) - An example of ActivityPub server implementation written in Python.
* [dsblank/activitypub](https://github.com/dsblank/activitypub) - Prototyping a Python ActivityPub distributed server in Tornado.
* [pylodon](https://github.com/rowanlupton/pylodon) - Flask-based ActivityPub server implementation.
* [dariusk/express-activitypub](https://github.com/dariusk/express-activitypub) - A very simple reference implementation of an ActivityPub server using Express.js.

## Libraries
A little help for implementing ActivityPub.

* [Fedify](https://fedify.dev/) - An ActivityPub server framework in TypeScript.
* [Go-ActivityPub](https://github.com/go-ap) - A suite of packages to help in creating ActivityPub applications using the Go programming language.

## Bridges
Connecting the ActivityPub federation with another federation.

* [Bridgy Fed](https://github.com/snarfed/bridgy-fed) - A bridge between IndieWeb and ActivityPub, OStatus.
* [GNU social ActivityPub Plugin](https://notabug.org/diogo/gnu-social/src/nightly/plugins/ActivityPub) - Plugin for GNU social to add ActivityPub support.
* [Hatsu](https://hatsu.cli.rs/) - A self-hosted bridge that interacts with fediverse on behalf of your static site.
* [RSS to ActivityPub](https://github.com/dariusk/rss-to-activitypub) - An RSS to ActivityPub converter. 

## Community and Advocacy Groups

* [SocialHub](https://socialhub.activitypub.rocks/) - Forum for ActivityPub-related projects.
* [fediverse.party](https://fediverse.party/) - A quick look into Fediverse networks.
* [We Distibute](https://wedistribute.org/) - a publication dedicated to Free Software, decentralized communication technologies, and sustainability.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
