---
layout: post
title: Client Side Database
category: DB
tags: [web, db, client, offline]
---

# Top client side DB

## Target
Webkit

## Native
https://wiki.whatwg.org/wiki/Storage#API
**Existing APIs**
|These APIs need to be (re)written in terms of the new low-level storage primitives so that they have a common grounding.
Cookies
localStorage
sessionStorage
Indexed DB
Cache API (from service workers, to be clear)
History API
Notifications API
Appcache (legacy)
Filesystem (legacy, might make a comeback)
WebSQL (legacy)

|HTTP cache is probably distinct.

SQLite


## Frameworks and wrappers
PouchDB - https://github.com/pouchdb (https://github.com/LoicMahieu/awesome-pouchdb)
Alasql.js - https://github.com/agershun/alasql
RxDB - https://github.com/pubkey/rxdb
jSQL - https://github.com/Pamblam/jSQL
js-xlsx - https://github.com/SheetJS/js-xlsx
Alax.js - lightweight JavaScript OLAP server for Node.js
https://github.com/share/sharedb

### Usefull Links
http://offlinefirst.org/
https://developer.chrome.com/apps/offline_apps
https://storage.spec.whatwg.org/
http://www.slideshare.net/moscowjs/02-alasql
https://raw.githubusercontent.com/wiki/agershun/alasql/Similar-Projects.md
