# Awesome Ranvier

## What this is

`awesome-ranvier` is a repository for quality community-made content around the [Ranvier MUD engine](https://ranviermud.com/).
If you know of a community fork, bundle, or other content that is not listed here, feel free to submit an issue or pull request to add it.

### Contributing

If you add a resource, please do so in the following format:

### Category Name (if not already present) should be a 3rd level subheading

- [Link text should be the name of the content, e.g. "RanvierMUD website".](https://ranviermud.com) (compatible Ranvier version info if applicable, e.g. version 3.x) A short description of the content should be included as part of the same list item.

## Categories

Legend:
:construction: - Under construction or Looking for development help.
:warning: - Unmaintained or Deprecated

### Bundles

- [axon-olc](https://github.com/nelsonsbrian/axon-olc) (v3.x) Ranvier in-game entity editor
- [myelin-quests](https://github.com/seanohue/myelin-quests) (v2.x) A bundle with custom QuestGoals and quest-related behaviors. :warning:
- [Community Bundles](https://ranviermud.com/community_bundles/) (v3.x) List of community bundles in the Ranvier documentation.

### Building Tools

- [Axolemma](https://github.com/seanohue/axolemma) (v2.x or 3.x, examples are in 2.x) A CLI tool and library leveraging [ROT-js](https://ondras.github.io/rot.js/) to procedurally generate areas for Ranvier games.
- [Soma](https://github.com/RanvierMUD/soma) (2.x) Electron-based building tool. :warning:
- [ranvier-webhooks](https://github.com/azigler/ranvier-webhooks) (3.x). This bundle comes with a webhook that handles GitHub events so you can trigger an automatic rebuild and relaunch of your Ranvier instance when committing to your public repository.
- [ranvier-zpanel](https://github.com/azigler/ranvier-zpanel) (3.x) Web-based control panel and building client for Ranvier :warning:

### Core Engine Forks & Versions

- [RanvierMUD 3.1](https://github.com/RanvierMUD/core/tree/3.1-preview) (v3.1) Experimental alpha branch of the core engine. :construction: :warning:
- [Ranvier-TS](https://github.com/Ranvier-TS/core-ts) (v3.1+) A fork of Ranvier that converts the entire engine to TypeScript, with some additional enhancements. :construction:
- [Pinwheel MUD Engine](https://github.com/azigler/pinwheel) (2.x) Pinwheel is a rewrite of the Ranvier MUD engine and its bundles into a highly opinionated format. The engine makes decisions about world persistence and core features so you can focus on building your world and community. :warning:

### Clients

- [Neuro](https://github.com/RanvierMUD/neuro) (2.x, 3.x) Electron websockets client. The original.

### DataSources

 - [datasource-file](https://github.com/RanvierMUD/datasource-file) (3.x) YAML and JSON DataSources for the Ranvier game engine
 - [ranvier-mongodb-datasource](https://www.npmjs.com/package/ranvier-mongodb-datasource) (3.x) DataSources to store entities in MongoDB.
 - [ranvier-datasource-sqlite](https://www.npmjs.com/package/ranvier-datasource-sqlite) (3.x) SQLite DataSource.
 - [ranvier-datasource-couchdb](https://github.com/azigler/ranvier-datasource-couchdb) (3.x) CouchDB DataSource

### Games

- [Myelin: Escape the Spire](http://myelin.space) ([Itch](https://muscarian.itch.io/myelin-escape-the-spire)) (v2.x) A procedurally-generated sci-fi dungeon crawl. :warning:
- [Enceladus](http://https://enceladusgame.io/play) (v3.x) An experimental crypto rpg

### Libraries

- [Fantasy Time Crunch](https://github.com/seanohue/fantasy-time-crunch) (v2.x or v3.x) A library for handling arbitrary units of time and time-related "tick" events, made to plug into a Ranvier bundle easily. :construction:
- [Lobus](https://github.com/seanohue/lobus) (v2.x or 3.x) A library for handling event-based menus, made for creating Ranvier input-event menus. :construction:
- [ranvier-tracery](https://github.com/azigler/ranvier-tracery) (3.x) Generate and manipulate text in Ranvier with Tracery
- [Magic-Symbols](https://github.com/Sakeran/magic-symbols) (v2.x or v3.x) Color syntax and parser for ANSI and Xterm256 colors

## Contact

If you'd like to contact the maintainer of this site or folks in the Ranvier community, either submit an issue to the `awesome-ranvier` repository or check out the [community Slack](https://join.slack.com/t/ranviermud/shared_invite/enQtODA1NTI4MTc5MjgyLWU1OTI2YTYxMTcwYTBjNmIyMzhmMWZmNTQ3ZmFiMWEwYjQ5N2MyYWQzODFhZDUwNmZiODE1ODVlNWE5NTlmYzU).
