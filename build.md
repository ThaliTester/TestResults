#### Test (Fail) 102446911 Build Logs


```


```

```
Already up-to-date.

From https://github.com/thaliproject/Thali_CordovaPlugin
 * [new branch]      iOS_chapko_1734 -> origin/iOS_chapko_1734

```

```
Your branch is up-to-date with 'origin/master'.
Branch iOS set up to track remote branch iOS from origin.
Already up-to-date.

Already on 'master'
Switched to a new branch 'iOS'
Note: checking out '8b10a27'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at 8b10a27... Fix race conditions in the pouchDBCheckpointsPlugin

```

```

start build.sh

-- Environment:
Cordova version: 6.4.0
Node version: v6.9.1
JXcore version: v0.3.1.8
JXcore engine: Google V8 v3.14.5.9
xcodebuild version: Xcode 7.3.1


start setUpDesktop.sh

start preparing TestServer
thali-test-server@0.0.1 /Users/thali/Github/Thali_CordovaPlugin/test/TestServer
├── bluebird@3.4.6 
├─┬ express@4.13.3 
│ ├─┬ accepts@1.2.13 
│ │ ├─┬ mime-types@2.1.14 
│ │ │ └── mime-db@1.26.0 
│ │ └── negotiator@0.5.3 
│ ├── array-flatten@1.1.1 
│ ├── content-disposition@0.5.0 
│ ├── content-type@1.0.2 
│ ├── cookie@0.1.3 
│ ├── cookie-signature@1.0.6 
│ ├─┬ debug@2.2.0 
│ │ └── ms@0.7.1 
│ ├── depd@1.0.1 
│ ├── escape-html@1.0.2 
│ ├── etag@1.7.0 
│ ├─┬ finalhandler@0.4.0 
│ │ └── unpipe@1.0.0 
│ ├── fresh@0.3.0 
│ ├── merge-descriptors@1.0.0 
│ ├── methods@1.1.2 
│ ├─┬ on-finished@2.3.0 
│ │ └── ee-first@1.1.1 
│ ├── parseurl@1.3.1 
│ ├── path-to-regexp@0.1.7 
│ ├─┬ proxy-addr@1.0.10 
│ │ ├── forwarded@0.1.0 
│ │ └── ipaddr.js@1.0.5 
│ ├── qs@4.0.0 
│ ├── range-parser@1.0.3 
│ ├─┬ send@0.13.0 
│ │ ├── destroy@1.0.3 
│ │ ├─┬ http-errors@1.3.1 
│ │ │ └── inherits@2.0.3 
│ │ ├── mime@1.3.4 
│ │ └── statuses@1.2.1 
│ ├─┬ serve-static@1.10.3 
│ │ ├── escape-html@1.0.3 
│ │ └─┬ send@0.13.2 
│ │   ├── depd@1.1.0 
│ │   └── destroy@1.0.4 
│ ├─┬ type-is@1.6.14 
│ │ └── media-typer@0.3.0 
│ ├── utils-merge@1.0.0 
│ └── vary@1.0.1 
├─┬ fs-extra-promise@0.2.0 
│ ├── bluebird@2.11.0 
│ └─┬ fs-extra@0.21.0 
│   ├── graceful-fs@4.1.11 
│   ├── jsonfile@2.4.0 
│   └─┬ rimraf@2.5.4 
│     └─┬ glob@7.1.1 
│       ├── fs.realpath@1.0.0 
│       ├─┬ inflight@1.0.6 
│       │ └── wrappy@1.0.2 
│       ├─┬ minimatch@3.0.3 
│       │ └─┬ brace-expansion@1.1.6 
│       │   ├── balanced-match@0.4.2 
│       │   └── concat-map@0.0.1 
│       ├── once@1.4.0 
│       └── path-is-absolute@1.0.1 
├── node-uuid@1.4.7 
├── object-assign@4.1.0 
├─┬ socket.io@1.4.8 
│ ├─┬ engine.io@1.6.11 
│ │ ├─┬ accepts@1.1.4 
│ │ │ ├─┬ mime-types@2.0.14 
│ │ │ │ └── mime-db@1.12.0 
│ │ │ └── negotiator@0.4.9 
│ │ ├── base64id@0.1.0 
│ │ ├─┬ engine.io-parser@1.2.4 
│ │ │ ├── after@0.8.1 
│ │ │ ├── arraybuffer.slice@0.0.6 
│ │ │ ├── base64-arraybuffer@0.1.2 
│ │ │ ├── blob@0.0.4 
│ │ │ ├── has-binary@0.1.6 
│ │ │ └── utf8@2.1.0 
│ │ └─┬ ws@1.1.0 
│ │   ├── options@0.0.6 
│ │   └── ultron@1.0.2 
│ ├─┬ has-binary@0.1.7 
│ │ └── isarray@0.0.1 
│ ├─┬ socket.io-adapter@0.4.0 
│ │ └─┬ socket.io-parser@2.2.2 
│ │   ├── debug@0.7.4 
│ │   └── json3@3.2.6 
│ ├─┬ socket.io-client@1.4.8 
│ │ ├── backo2@1.0.2 
│ │ ├── component-bind@1.0.0 
│ │ ├── component-emitter@1.2.0 
│ │ ├─┬ engine.io-client@1.6.11 
│ │ │ ├── component-inherit@0.0.3 
│ │ │ ├── has-cors@1.1.0 
│ │ │ ├── parsejson@0.0.1 
│ │ │ ├── parseqs@0.0.2 
│ │ │ ├── ws@1.0.1 
│ │ │ ├── xmlhttprequest-ssl@1.5.1 
│ │ │ └── yeast@0.1.2 
│ │ ├── indexof@0.0.1 
│ │ ├── object-component@0.0.3 
│ │ ├─┬ parseuri@0.0.4 
│ │ │ └─┬ better-assert@1.0.2 
│ │ │   └── callsite@1.0.0 
│ │ └── to-array@0.1.4 
│ └─┬ socket.io-parser@2.2.6 
│   ├── benchmark@1.0.0 
│   ├── component-emitter@1.1.2 
│   └── json3@3.3.2 
└─┬ winston@2.2.0 
  ├── async@1.0.0 
  ├── colors@1.0.3 
  ├── cycle@1.0.3 
  ├── eyes@0.1.8 
  ├── isstream@0.1.2 
  ├── pkginfo@0.3.1 
  └── stack-trace@0.0.9 

end preparing TestServer


start installing Thali root
[33mPreparing NPM for JXcore (v0.3.1.8) for the first run[39m
[33mDownloading NPM for JXcore[39m
...
[33mextracting /Users/thali/.jx/npm.tar.gz[39m
NPM for JX is ready.
executing... please wait.

> thali@2.1.0 postinstall /Users/thali/Github/Thali_CordovaPlugin/thali
> "/usr/local/bin/jx" installCordovaPlugin.js

We believe we are in a clone of the GitHub Repo so we will not install Cordova dependencies

> thali@2.1.0 prepublish /Users/thali/Github/Thali_CordovaPlugin/thali
> "/usr/local/bin/jx" install/prePublishThaliCordovaPlugin.js

thali@2.1.0
│ /Users/thali/Github/Thali_CordovaPlugin/thali
│ Thali Cordova Plugin
│ git+https://github.com/thaliproject/Thali_CordovaPlugin.git
│ https://github.com/thaliproject/Thali_CordovaPlugin/tree/story_00#readme
├── bluebird@3.4.6 
│   Full featured Promises/A+ implementation with exceptionally good performance
│   git://github.com/petkaantonov/bluebird.git
│   https://github.com/petkaantonov/bluebird
├── body-parser@1.13.3 
│   Node.js body parsing middleware
│   git+https://github.com/expressjs/body-parser.git
│   https://github.com/expressjs/body-parser
├── eslint@3.11.1 
│   An AST-based pattern checker for JavaScript.
│   git+https://github.com/eslint/eslint.git
│   http://eslint.org
├── express@4.13.3 
│   Fast, unopinionated, minimalist web framework
│   git+https://github.com/strongloop/express.git
│   http://expressjs.com/
├── forever-agent@0.6.1  (git+https://github.com/thaliproject/forever-agent.git#f1078b5095dfe00ad0d80779eba75e563b54608b)
│   HTTP Agent that keeps socket connections alive between keep-alive requests. Formerly part of mikeal/request, now a standalone module.
│   git+https://github.com/mikeal/forever-agent.git
│   https://github.com/mikeal/forever-agent#readme
│   git+https://github.com/thaliproject/forever-agent.git#f1078b5095dfe00ad0d80779eba75e563b54608b
├── ip@1.0.1 
│   IP address utilities for node.js
│   git+ssh://git@github.com/indutny/node-ip.git
│   https://github.com/indutny/node-ip
├── javascript-state-machine@2.3.5 
│   A simple finite state machine library
│   git://github.com/jakesgordon/javascript-state-machine.git
│   https://github.com/jakesgordon/javascript-state-machine
├── jsdoc@3.3.3 
│   An API documentation generator for JavaScript.
│   git+https://github.com/jsdoc3/jsdoc.git
│   https://github.com/jsdoc3/jsdoc#readme
├── lie@3.1.0 
│   A basic but performant promise implementation
│   git+https://github.com/calvinmetcalf/lie.git
│   https://github.com/calvinmetcalf/lie#readme
├── lodash.throttle@4.1.1 
│   The lodash method `_.throttle` exported as a module.
│   git+https://github.com/lodash/lodash.git
│   https://lodash.com/
├── long@3.0.3 
│   A Long class for representing a 64-bit two's-complement integer value.
│   git+https://github.com/dcodeIO/long.js.git
│   https://github.com/dcodeIO/long.js#readme
├── multiplex@6.7.0 
│   A binary stream multiplexer. Stream multiple streams of binary data over a single binary stream.
│   git+https://github.com/maxogden/multiplex.git
│   https://github.com/maxogden/multiplex
├── node-ssdp@2.6.5  (git+https://github.com/thaliproject/node-ssdp.git#8feabedb80d054d354ea1fc6bd55045df65fd18f)
│   A node.js SSDP client and server library.
│   git+ssh://git@github.com/diversario/node-ssdp.git
│   https://github.com/diversario/node-ssdp#readme
│   git+https://github.com/thaliproject/node-ssdp.git#8feabedb80d054d354ea1fc6bd55045df65fd18f
├── object-assign@4.1.0 
│   ES2015 Object.assign() ponyfill
│   git+https://github.com/sindresorhus/object-assign.git
│   https://github.com/sindresorhus/object-assign#readme
├── pouchdb-adapter-leveldb-core@6.1.1 
│   Core PouchDB adapter code for LevelDOWN-based adapters
│   git+https://github.com/pouchdb/pouchdb.git
│   https://github.com/pouchdb/pouchdb#readme
├── request@2.64.0 
│   Simplified HTTP request client.
│   git+https://github.com/request/request.git
│   https://github.com/request/request#readme
├── salti@0.2.1  (git+https://github.com/thaliproject/salti.git#5182ec528e6c121aa16ab3ee8eb4a1e45f3d3822)
│   Simple Authentication and Authorization for Thali IoT
│   git+https://github.com/thaliproject/salti.git
│   https://github.com/thaliproject/salti#readme
│   git+https://github.com/thaliproject/salti.git#master
├── urlsafe-base64@1.0.0 
│   URL Safe Base64 encoding
│   git+ssh://git@github.com/RGBboy/urlsafe-base64.git
│   https://github.com/RGBboy/urlsafe-base64
├── uuid@2.0.2 
│   Rigorous implementation of RFC4122 (v1 and v4) UUIDs.
│   git+https://github.com/shtylman/node-uuid.git
│   https://github.com/shtylman/node-uuid#readme
└── winston@2.2.0 
    A multi-transport async logging library for Node.js
    git+https://github.com/winstonjs/winston.git
    https://github.com/winstonjs/winston#readme


> thali@2.1.0 postinstall /Users/thali/Github/Thali_CordovaPlugin/thali
> node installCordovaPlugin.js

We believe we are in a clone of the GitHub Repo so we will not install Cordova dependencies

> thali@2.1.0 prepublish /Users/thali/Github/Thali_CordovaPlugin/thali
> node install/prePublishThaliCordovaPlugin.js

/usr/local/lib/node_modules/thali -> /Users/thali/Github/Thali_CordovaPlugin/thali
end installing Thali root


start installing Thali install
install@0.0.1 /Users/thali/Github/Thali_CordovaPlugin/thali/install
├── bluebird@3.4.6 
├─┬ child-process-promise@1.1.0 
│ └── q@1.4.1 
├── end-with@1.0.2 
├── findit@2.0.0 
├─┬ fs-extra-promise@0.2.0 
│ ├── bluebird@2.11.0 
│ └─┬ fs-extra@0.21.0 
│   ├── graceful-fs@4.1.11 
│   ├── jsonfile@2.4.0 
│   └─┬ rimraf@2.5.4 
│     └─┬ glob@7.1.1 
│       ├── fs.realpath@1.0.0 
│       ├─┬ inflight@1.0.6 
│       │ └── wrappy@1.0.2 
│       ├─┬ minimatch@3.0.3 
│       │ └─┬ brace-expansion@1.1.6 
│       │   ├── balanced-match@0.4.2 
│       │   └── concat-map@0.0.1 
│       ├── once@1.4.0 
│       └── path-is-absolute@1.0.1 
├─┬ jxc@1.0.14 
│ └─┬ jxtools@0.0.4  (git+https://github.com/ktrzeciaknubisa/jxtools.git#644cf31ea259cb65a97e5c3ed5ea1236dba298a3)
│   ├── adm-zip@0.4.7 
│   └── progress@1.1.8 
├─┬ lie@3.1.0 
│ └── immediate@3.0.6 
├── node-uuid@1.4.7 
├─┬ randomstring@1.1.5 
│ └── array-uniq@1.0.2 
├─┬ request@2.74.0 
│ ├── aws-sign2@0.6.0 
│ ├── aws4@1.5.0 
│ ├─┬ bl@1.1.2 
│ │ └─┬ readable-stream@2.0.6 
│ │   ├── isarray@1.0.0 
│ │   ├── process-nextick-args@1.0.7 
│ │   └── util-deprecate@1.0.2 
│ ├── caseless@0.11.0 
│ ├─┬ combined-stream@1.0.5 
│ │ └── delayed-stream@1.0.0 
│ ├── extend@3.0.0 
│ ├── forever-agent@0.6.1 
│ ├─┬ form-data@1.0.1 
│ │ └─┬ async@2.1.4 
│ │   └── lodash@4.17.4 
│ ├─┬ har-validator@2.0.6 
│ │ ├─┬ chalk@1.1.3 
│ │ │ ├── ansi-styles@2.2.1 
│ │ │ ├── escape-string-regexp@1.0.5 
│ │ │ ├─┬ has-ansi@2.0.0 
│ │ │ │ └── ansi-regex@2.1.1 
│ │ │ ├── strip-ansi@3.0.1 
│ │ │ └── supports-color@2.0.0 
│ │ ├─┬ commander@2.9.0 
│ │ │ └── graceful-readlink@1.0.1 
│ │ ├─┬ is-my-json-valid@2.15.0 
│ │ │ ├── generate-function@2.0.0 
│ │ │ ├─┬ generate-object-property@1.2.0 
│ │ │ │ └── is-property@1.0.2 
│ │ │ ├── jsonpointer@4.0.1 
│ │ │ └── xtend@4.0.1 
│ │ └─┬ pinkie-promise@2.0.1 
│ │   └── pinkie@2.0.4 
│ ├─┬ hawk@3.1.3 
│ │ ├── boom@2.10.1 
│ │ ├── cryptiles@2.0.5 
│ │ ├── hoek@2.16.3 
│ │ └── sntp@1.0.9 
│ ├─┬ http-signature@1.1.1 
│ │ ├── assert-plus@0.2.0 
│ │ ├─┬ jsprim@1.3.1 
│ │ │ ├── extsprintf@1.0.2 
│ │ │ ├── json-schema@0.2.3 
│ │ │ └── verror@1.3.6 
│ │ └─┬ sshpk@1.10.2 
│ │   ├── asn1@0.2.3 
│ │   ├── assert-plus@1.0.0 
│ │   ├─┬ dashdash@1.14.1 
│ │   │ └── assert-plus@1.0.0 
│ │   └─┬ getpass@0.1.6 
│ │     └── assert-plus@1.0.0 
│ ├── is-typedarray@1.0.0 
│ ├── isstream@0.1.2 
│ ├── json-stringify-safe@5.0.1 
│ ├─┬ mime-types@2.1.14 
│ │ └── mime-db@1.26.0 
│ ├── oauth-sign@0.8.2 
│ ├── qs@6.2.1 
│ ├── stringstream@0.0.5 
│ ├─┬ tough-cookie@2.3.2 
│ │ └── punycode@1.4.1 
│ └── tunnel-agent@0.4.3 
├─┬ unzip@0.1.11 
│ ├─┬ binary@0.3.0 
│ │ ├── buffers@0.1.1 
│ │ └─┬ chainsaw@0.1.0 
│ │   └── traverse@0.3.9 
│ ├─┬ fstream@0.1.31 
│ │ ├─┬ graceful-fs@3.0.11 
│ │ │ └── natives@1.1.0 
│ │ ├── inherits@2.0.3 
│ │ └─┬ mkdirp@0.5.1 
│ │   └── minimist@0.0.8 
│ ├─┬ match-stream@0.0.2 
│ │ └─┬ readable-stream@1.0.34 
│ │   └── isarray@0.0.1 
│ ├─┬ pullstream@0.4.1 
│ │ ├── over@0.0.5 
│ │ ├─┬ readable-stream@1.0.34 
│ │ │ └── isarray@0.0.1 
│ │ └─┬ slice-stream@1.0.0 
│ │   └─┬ readable-stream@1.0.34 
│ │     └── isarray@0.0.1 
│ ├─┬ readable-stream@1.0.34 
│ │ ├── core-util-is@1.0.2 
│ │ ├── isarray@0.0.1 
│ │ └── string_decoder@0.10.31 
│ └── setimmediate@1.0.5 
└─┬ xcode@0.8.9 
  ├── pegjs@0.9.0 
  └─┬ simple-plist@0.1.4 
    ├─┬ bplist-creator@0.0.4 
    │ └── stream-buffers@0.2.6 
    ├── bplist-parser@0.0.6 
    └─┬ plist@1.2.0 
      ├── base64-js@0.0.8 
      ├─┬ xmlbuilder@4.0.0 
      │ └── lodash@3.10.1 
      └── xmldom@0.1.27 

Environment validated
end installing Thali install


start preparing 'test/www/jxcore'
/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/thali -> /usr/local/lib/node_modules/thali -> /Users/thali/Github/Thali_CordovaPlugin/thali

> leveldown@1.5.0 install /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/leveldown
> "/usr/local/bin/jx" /Users/thali/.jx/npm/node_modules/node-gyp/bin/node-gyp.js rebuild

Target arch x64
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.19/db/builder.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.19/db/db_impl.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.19/db/db_iter.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.19/db/filename.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.19/db/dbformat.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.19/db/log_reader.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.19/db/log_writer.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.19/db/memtable.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.19/db/repair.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.19/db/table_cache.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.19/db/version_edit.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.19/db/version_set.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.19/db/write_batch.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.19/helpers/memenv/memenv.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.19/table/block.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.19/table/block_builder.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.19/table/filter_block.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.19/table/format.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.19/table/iterator.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.19/table/merger.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.19/table/table.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.19/table/table_builder.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.19/table/two_level_iterator.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.19/util/arena.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.19/util/bloom.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.19/util/cache.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.19/util/coding.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.19/util/comparator.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.19/util/crc32c.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.19/util/env.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.19/util/filter_policy.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.19/util/hash.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.19/util/logging.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.19/util/options.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.19/util/status.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.19/port/port_posix.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.19/util/env_posix.o
  LIBTOOL-STATIC Release/leveldb.a
  CXX(target) Release/obj.target/snappy/deps/snappy/snappy-1.1.1/snappy-sinksource.o
  CXX(target) Release/obj.target/snappy/deps/snappy/snappy-1.1.1/snappy-stubs-internal.o
  CXX(target) Release/obj.target/snappy/deps/snappy/snappy-1.1.1/snappy.o
  LIBTOOL-STATIC Release/snappy.a
  CXX(target) Release/obj.target/leveldown/src/batch.o
  CXX(target) Release/obj.target/leveldown/src/batch_async.o
  CXX(target) Release/obj.target/leveldown/src/database.o
  CXX(target) Release/obj.target/leveldown/src/database_async.o
  CXX(target) Release/obj.target/leveldown/src/iterator.o
  CXX(target) Release/obj.target/leveldown/src/iterator_async.o
  CXX(target) Release/obj.target/leveldown/src/leveldown.o
  CXX(target) Release/obj.target/leveldown/src/leveldown_async.o
  SOLINK_MODULE(target) Release/leveldown.node

> leveldown-mobile@1.1.1 install /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/leveldown-mobile
> "/usr/local/bin/jx" /Users/thali/.jx/npm/node_modules/node-gyp/bin/node-gyp.js rebuild

Target arch x64
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/db/builder.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/db/db_impl.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/db/db_iter.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/db/filename.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/db/dbformat.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/db/log_reader.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/db/log_writer.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/db/memtable.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/db/repair.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/db/table_cache.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/db/version_edit.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/db/version_set.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/db/write_batch.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/helpers/memenv/memenv.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/table/block.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/table/block_builder.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/table/filter_block.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/table/format.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/table/iterator.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/table/merger.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/table/table.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/table/table_builder.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/table/two_level_iterator.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/util/arena.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/util/bloom.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/util/cache.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/util/coding.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/util/comparator.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/util/crc32c.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/util/env.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/util/filter_policy.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/util/hash.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/util/logging.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/util/options.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/util/status.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/port/port_posix.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/util/env_posix.o
  LIBTOOL-STATIC Release/leveldb.a
  CXX(target) Release/obj.target/snappy/deps/snappy/snappy-1.1.1/snappy-sinksource.o
  CXX(target) Release/obj.target/snappy/deps/snappy/snappy-1.1.1/snappy-stubs-internal.o
  CXX(target) Release/obj.target/snappy/deps/snappy/snappy-1.1.1/snappy.o
  LIBTOOL-STATIC Release/snappy.a
  CXX(target) Release/obj.target/leveldown/src/batch.o
  CXX(target) Release/obj.target/leveldown/src/batch_async.o
  CXX(target) Release/obj.target/leveldown/src/database.o
  CXX(target) Release/obj.target/leveldown/src/database_async.o
  CXX(target) Release/obj.target/leveldown/src/iterator.o
  CXX(target) Release/obj.target/leveldown/src/iterator_async.o
  CXX(target) Release/obj.target/leveldown/src/leveldown.o
  CXX(target) Release/obj.target/leveldown/src/leveldown_async.o
  SOLINK_MODULE(target) Release/leveldown.node
thali-cordova-plugin-jxcore@1.0.0
│ /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore
│ Thali Cordova Plugin JXCore
├── balanced-match@0.2.0 
│   Match balanced character pairs, like "{" and "}"
│   git://github.com/juliangruber/balanced-match.git
│   https://github.com/juliangruber/balanced-match
├── bluebird@3.4.6 
│   Full featured Promises/A+ implementation with exceptionally good performance
│   git://github.com/petkaantonov/bluebird.git
│   https://github.com/petkaantonov/bluebird
├── bn.js@4.10.0 
│   Big number implementation in pure javascript
│   git+ssh://git@github.com/indutny/bn.js.git
│   https://github.com/indutny/bn.js
├── body-parser@1.13.3 
│   Node.js body parsing middleware
│   git+https://github.com/expressjs/body-parser.git
│   https://github.com/expressjs/body-parser
├── child-process-promise@1.1.0 
│   Simple wrapper around the "child_process" module that makes use of promises
│   git+https://github.com/patrick-steele-idem/child-process-promise.git
│   https://github.com/patrick-steele-idem/child-process-promise
├── concat-map@0.0.1 
│   concatenative mapdashery
│   git://github.com/substack/node-concat-map.git
│   https://github.com/substack/node-concat-map
├── express@4.13.3 
│   Fast, unopinionated, minimalist web framework
│   git+https://github.com/strongloop/express.git
│   http://expressjs.com/
├── express-pouchdb@1.0.6-thali 
│   Express submodule with a CouchDB style REST interface to PouchDB.
│   git://github.com/pouchdb/express-pouchdb.git
│   https://github.com/pouchdb/express-pouchdb
├── forever-agent@0.6.1  (git+https://github.com/thaliproject/forever-agent.git#f1078b5095dfe00ad0d80779eba75e563b54608b)
│   HTTP Agent that keeps socket connections alive between keep-alive requests. Formerly part of mikeal/request, now a standalone module.
│   git+https://github.com/mikeal/forever-agent.git
│   https://github.com/mikeal/forever-agent#readme
│   git+https://github.com/thaliproject/forever-agent.git#f1078b5095dfe00ad0d80779eba75e563b54608b
├── fs-extra-promise@0.4.0
│   Node file system library and fs-extra module promisified with bluebird
│   git+https://github.com/overlookmotel/fs-extra-promise.git
│   https://github.com/overlookmotel/fs-extra-promise#readme
├── inherits@2.0.1 
│   Browser-friendly inheritance fully compatible with standard node.js inherits()
│   git://github.com/isaacs/inherits.git
│   https://github.com/isaacs/inherits#readme
├── is-property@1.0.2 
│   Tests if a JSON property can be accessed using . syntax
│   git://github.com/mikolalysenko/is-property.git
│   https://github.com/mikolalysenko/is-property
├── js-extend@1.0.1 
│   A simple extend function based on underscore
│   git://github.com/vmattos/js-extend.git
│   https://github.com/vmattos/js-extend
├── leveldown-mobile@1.1.1 
│   A Node.js LevelDB binding for Android, iOS and Windows UWP, primary backend for LevelUP
│   git+https://github.com/level/leveldown-mobile.git
│   https://github.com/level/leveldown-mobile
├── lie@3.0.4 
│   A basic but performant promise implementation
│   git+https://github.com/calvinmetcalf/lie.git
│   https://github.com/calvinmetcalf/lie#readme
├── long@3.0.3 
│   A Long class for representing a 64-bit two's-complement integer value.
│   git+https://github.com/dcodeIO/long.js.git
│   https://github.com/dcodeIO/long.js#readme
├── minimist@1.2.0 
│   parse argument options
│   git://github.com/substack/minimist.git
│   https://github.com/substack/minimist
├── multiplex@6.7.0 
│   A binary stream multiplexer. Stream multiple streams of binary data over a single binary stream.
│   git+https://github.com/maxogden/multiplex.git
│   https://github.com/maxogden/multiplex
├── nock@2.12.0 
│   HTTP Server mocking for Node.js
│   git+ssh://git@github.com/pgte/nock.git
│   https://github.com/pgte/nock
├── node-ssdp@2.6.5  (git+https://github.com/thaliproject/node-ssdp.git#caf1a75aa54fb47a9e51b72bf4c902c366536cbd)
│   A node.js SSDP client and server library.
│   git+ssh://git@github.com/diversario/node-ssdp.git
│   https://github.com/diversario/node-ssdp#readme
│   git+https://github.com/thaliproject/node-ssdp.git#caf1a75aa54fb47a9e51b72bf4c902c366536cbd
├── node-uuid@1.4.7 
│   Rigorous implementation of RFC4122 (v1 and v4) UUIDs.
│   git+https://github.com/broofa/node-uuid.git
│   https://github.com/broofa/node-uuid
├── object-assign@4.1.0 
│   ES2015 Object.assign() ponyfill
│   git+https://github.com/sindresorhus/object-assign.git
│   https://github.com/sindresorhus/object-assign#readme
├── pouchdb@6.1.1 
│   PouchDB is a pocket-sized database
│   git+https://github.com/pouchdb/pouchdb.git
│   https://github.com/pouchdb/pouchdb#readme
├── pouchdb-size@1.2.2 
│   Adds disk_size to info()'s output for your leveldown backed PouchDB's.
│   git+https://github.com/marten-de-vries/pouchdb-size.git
│   https://github.com/marten-de-vries/pouchdb-size#readme
├── proxyquire@1.7.4 
│   Proxies nodejs require in order to allow overriding dependencies during testing.
│   git+https://github.com/thlorenz/proxyquire.git
│   https://github.com/thlorenz/proxyquire#readme
├── randomstring@1.1.5 
│   A module for generating random strings
│   git://github.com/klughammer/node-randomstring.git
│   https://github.com/klughammer/node-randomstring
├── request@2.64.0 
│   Simplified HTTP request client.
│   git+https://github.com/request/request.git
│   https://github.com/request/request#readme
├── request-promise@0.4.3 
│   The world-famous HTTP client 'Request' now Promises/A+ compliant. Powered by Bluebird.
│   git+https://github.com/request/request-promise.git
│   https://github.com/request/request-promise
├── salti@0.2.1  (git+https://github.com/thaliproject/salti.git#5182ec528e6c121aa16ab3ee8eb4a1e45f3d3822)
│   Simple Authentication and Authorization for Thali IoT
│   git+https://github.com/thaliproject/salti.git
│   https://github.com/thaliproject/salti#readme
│   git+https://github.com/thaliproject/salti.git#master
├── sinon@1.17.3 
│   JavaScript test spies, stubs and mocks.
│   git+ssh://git@github.com/cjohansen/Sinon.JS.git
│   http://sinonjs.org/
├── socket.io-client@1.4.8 
│   [![Build Status](https://secure.travis-ci.org/socketio/socket.io-client.svg)](http://travis-ci.org/socketio/socket.io-client) [![Dependency Status](https://david-dm.org/socketio/socket.io-client.svg)](https://david-dm.org/socketio/socket.io-client) [![dev
│   git+https://github.com/Automattic/socket.io-client.git
│   https://github.com/Automattic/socket.io-client#readme
├── stacky@1.3.1 
│   Stacky parses stack traces from various sources, and formats them in readable ways.
│   git+https://github.com/PolymerLabs/stacky.git
│   https://github.com/PolymerLabs/stacky
├── supertest@1.1.0 
│   Super-agent driven library for testing HTTP servers
│   git+https://github.com/visionmedia/supertest.git
│   https://github.com/visionmedia/supertest#readme
├── supertest-as-promised@2.0.2 
│   Supercharge supertest with a promise interface
│   git://github.com/WhoopInc/supertest-as-promised.git
│   https://github.com/WhoopInc/supertest-as-promised
├── tape@4.0.0 
│   tap-producing test harness for node and browsers
│   git://github.com/substack/tape.git
│   https://github.com/substack/tape
├── tape-catch@1.0.4 
│   a wrapper around tape that catches and reports exceptions
│   git+https://github.com/michaelrhodes/tape-catch.git
│   https://github.com/michaelrhodes/tape-catch
├── thali@2.1.0 -> /Users/thali/Github/Thali_CordovaPlugin/thali
│   Thali Cordova Plugin
│   git+https://github.com/thaliproject/Thali_CordovaPlugin.git
│   https://github.com/thaliproject/Thali_CordovaPlugin/tree/story_00#readme
├── tmp@0.0.28 
│   Temporary file and directory creator
│   git://github.com/raszi/node-tmp.git
│   http://github.com/raszi/node-tmp
├── urlsafe-base64@1.0.0 
│   URL Safe Base64 encoding
│   git+ssh://git@github.com/RGBboy/urlsafe-base64.git
│   https://github.com/RGBboy/urlsafe-base64
├── uuid@2.0.0 
│   Rigorous implementation of RFC4122 (v1 and v4) UUIDs.
│   git+https://github.com/shtylman/node-uuid.git
│   https://github.com/shtylman/node-uuid
└── uuid-validate@0.0.2 
    Javascript validator for UUID versions 1 through 5
    git+https://github.com/MCProHosting/uuid-validate.git
    https://github.com/MCProHosting/uuid-validate

end prepating 'test/www/jxcore'

end setUpDesktop.sh


run desktop tests
2017-01-20 11:39:34 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
2017-01-20 11:39:34 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
2017-01-20 11:39:34 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
2017-01-20 11:39:34 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBGenerator.js'
2017-01-20 11:39:34 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPromiseQueue.js'
2017-01-20 11:39:34 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testTests.js'
2017-01-20 11:39:34 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testUsn.js'
2017-01-20 11:39:34 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testNativeMethod.js'
2017-01-20 11:39:34 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNative.js'
2017-01-20 11:39:34 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
2017-01-20 11:39:34 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
2017-01-20 11:39:34 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
2017-01-20 11:39:34 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreateNativeListener.js'
2017-01-20 11:39:35 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js'
2017-01-20 11:39:35 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliTcpServersManager.js'
2017-01-20 11:39:35 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
2017-01-20 11:39:35 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
2017-01-20 11:39:35 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js'
2017-01-20 11:39:35 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerAction.js'
2017-01-20 11:39:35 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerDictionary.js'
2017-01-20 11:39:35 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
2017-01-20 11:39:35 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
2017-01-20 11:39:35 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
2017-01-20 11:39:35 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotification.js'
2017-01-20 11:39:35 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationAction.js'
2017-01-20 11:39:35 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
2017-01-20 11:39:35 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationClient.js'
2017-01-20 11:39:35 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationLocal.js'
2017-01-20 11:39:35 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationServer.js'
2017-01-20 11:39:35 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
2017-01-20 11:39:35 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
2017-01-20 11:39:35 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
2017-01-20 11:39:35 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
2017-01-20 11:39:35 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
2017-01-20 11:39:35 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
2017-01-20 11:39:35 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js'
2017-01-20 11:39:35 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
2017-01-20 11:39:35 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManager.js'
2017-01-20 11:39:35 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
2017-01-20 11:39:35 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testSSDPServer.js'
2017-01-20 11:39:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-01-20 11:39:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-01-20 11:39:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2017-01-20 11:39:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-01-20 11:39:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-01-20 11:39:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
TAP version 13
# setup
# closeAll can close even when connections open
2017-01-20 11:39:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 1 not possible to connect to the server anymore
# teardown
# setup
# closeAll with promise
2017-01-20 11:39:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
# teardown
# setup
# closeAll properly throws when closing a non open server with eatNotRunning set to false
2017-01-20 11:39:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
# teardown
# setup
# closeAll works even with a server that is not listening yet witheatNotRunning set to true
2017-01-20 11:39:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
# setup
# Call of onCheckpointReached handler on a single db change
# teardown
# setup
# Call of multiple onCheckpointReached handlers on a single db change
# teardown
# setup
# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
ok 4 the checkpointReached handler should be called once. Called 1 time(s)
# teardown
# setup
# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
# teardown
# setup
# Can safely destroy db in the middle of the checkpoint delay interval
ok 5 checkpoint callback should not be called
ok 6 db should be destroyed
# teardown
# setup
# Can safely destroy db in the middle of its size calculating
2017-01-20 11:39:38 - DEBUG pouchDBCheckpointsPlugin: 'Database has been destroyed in the middle of the size calculating'
ok 7 checkpoint callback should not be called
ok 8 db should be destroyed
# teardown
# setup
# test defaultDirectory
ok 9 should be equal
ok 10 should be equal
ok 11 should be equal
# teardown
# setup
# test defaultAdapter
ok 12 should be equal
ok 13 should be equal
ok 14 should be equal
ok 15 should be equal
ok 16 should be equal
ok 17 should be equal
ok 18 should be equal
ok 19 should be equal
# teardown
# setup
# enqueue and run in order
ok 20 firstPromise setTimeout
ok 21 firstPromise result
ok 22 firstPromise testValue
ok 23 secondPromise setTimeout
ok 24 secondPromise result
ok 25 secondPromise testValue
ok 26 thirdPromise in promise
ok 27 thirdPromise result
ok 28 thirdPromise testValue
# teardown
# setup
# enqueueAtTop and run backwards
ok 29 thirdPromise - first to run
ok 30 thirdPromise - in resolve
ok 31 secondPromise - second to run
ok 32 secondPromise - in catch
ok 33 firstPromise - third to run
ok 34 firstPromise - in then
ok 35 testing promises
# teardown
# setup
# mix enqueue and enqueueAtTop
ok 36 fourth
ok 37 fourth
ok 38 second
ok 39 secondPromise - in then
ok 40 first
ok 41 firstPromise - in catch
ok 42 third
ok 43 thirdPromise - in then
ok 44 testingPromises
# teardown
# setup
# queues handled independently
ok 45 all short operations completed before the long resolves
# teardown
# setup
# basic
ok 46 sane
# teardown
# setup
# another
ok 47 sane
# teardown
# setup
# Correctly parses/stringifies USN
ok 48 correctly parses USN string
ok 49 throws if usn has invalid prefix
ok 50 throws if usn has invalid identifier format
ok 51 throws if usn has invalid generation
ok 52 correctly stringifies peer
# teardown
# setup
# onPeerLost calls jxcore
2017-01-20 11:39:38 - DEBUG SimpleThaliTape: 'test was skipped, name: 'onPeerLost calls jxcore''
# teardown
# setup
# onPeerDiscovered calls jxcore
2017-01-20 11:39:38 - DEBUG SimpleThaliTape: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
2017-01-20 11:39:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-01-20 11:39:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-01-20 11:39:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2017-01-20 11:39:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-01-20 11:39:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-01-20 11:39:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
# setup
# cannot call connect when start listening for advertisements is not active
2017-01-20 11:39:38 - DEBUG SimpleThaliTape: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
2017-01-20 11:39:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-01-20 11:39:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-01-20 11:39:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2017-01-20 11:39:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-01-20 11:39:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-01-20 11:39:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 53 Should be able to call stopListeningForAdvertisements in teardown
ok 54 Should be able to call stopAdvertisingAndListening in teardown
# setup
# calling createNativeListener directly rejects
2017-01-20 11:39:38 - DEBUG createNativeListener: 'Creating Native Server'
2017-01-20 11:39:38 - DEBUG createNativeListener: 'listening 49974'
ok 55 Should throw
# teardown
2017-01-20 11:39:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:38 - DEBUG createNativeListener: 'Native Server - close'
# setup
# emits incomingConnectionState
2017-01-20 11:39:38 - DEBUG createNativeListener: 'Creating Native Server'
2017-01-20 11:39:38 - DEBUG createNativeListener: 'listening 49976'
2017-01-20 11:39:38 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-01-20 11:39:38 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 56 initial connection state should be CONNECTED
2017-01-20 11:39:38 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 57 final connection state should be DISCONNECTED
# teardown
2017-01-20 11:39:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:38 - DEBUG createNativeListener: 'Native Server - close'
# setup
# emits routerPortConnectionFailed
2017-01-20 11:39:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:38 - DEBUG createNativeListener: 'Creating Native Server'
2017-01-20 11:39:38 - DEBUG createNativeListener: 'listening 49979'
2017-01-20 11:39:38 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-01-20 11:39:38 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-01-20 11:39:38 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2017-01-20 11:39:38 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
ok 58 tried to connect to right port
ok 59 failed due to refused connection
ok 60 routerPortConnectionFailed is emitted
# teardown
2017-01-20 11:39:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:38 - DEBUG createNativeListener: 'Native Server - close'
2017-01-20 11:39:38 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-01-20 11:39:38 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-01-20 11:39:38 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-01-20 11:39:38 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# setup
# native server connections all up
2017-01-20 11:39:38 - DEBUG createNativeListener: 'Creating Native Server'
2017-01-20 11:39:38 - DEBUG createNativeListener: 'listening 49983'
2017-01-20 11:39:38 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-01-20 11:39:38 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-01-20 11:39:38 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2017-01-20 11:39:38 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
ok 61 Send/recvd #1 should be equal length
ok 62 Send/recvd #1 should be same
ok 63 Send/recvd #2 should be equal length
ok 64 Send/recvd #2 should be same
ok 65 Should be exactly 2 client sockets
# teardown
2017-01-20 11:39:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:38 - DEBUG createNativeListener: 'Native Server - close'
2017-01-20 11:39:38 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-01-20 11:39:38 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
2017-01-20 11:39:38 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-01-20 11:39:38 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-01-20 11:39:38 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
2017-01-20 11:39:38 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# setup
# native server - closing incoming stream cleans outgoing socket
2017-01-20 11:39:38 - DEBUG createNativeListener: 'Creating Native Server'
2017-01-20 11:39:38 - DEBUG createNativeListener: 'listening 49988'
2017-01-20 11:39:38 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-01-20 11:39:38 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-01-20 11:39:38 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2017-01-20 11:39:38 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2017-01-20 11:39:38 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
ok 66 socket shouldn't close until after stream
ok 67 incoming remains open
# teardown
2017-01-20 11:39:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:38 - DEBUG createNativeListener: 'Native Server - close'
2017-01-20 11:39:38 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-01-20 11:39:38 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# setup
2017-01-20 11:39:38 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# native server - closing incoming connection cleans outgoing socket
2017-01-20 11:39:38 - DEBUG createNativeListener: 'Creating Native Server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'listening 49992'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 68 we should not have gotten an error
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 69 socket shouldn't close until after incoming
ok 70 incoming is cleaned up
# teardown
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - close'
# setup
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# native server - closing outgoing socket cleans associated mux stream
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Creating Native Server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'listening 49996'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
ok 71 stream was closed
ok 72 incoming should survive
ok 73 mux should have no streams
# teardown
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# setup
# native server - closing the whole server cleans everything up
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Creating Native Server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'listening 50000'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 74 we should not have gotten an error
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 75 Buffers are identical
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 76 native server is nulled out
ok 77 native server should be closed
ok 78 incoming has been removed
ok 79 Incoming should be done
ok 80 The mux object should be closed
ok 81 The mux stream should be closed
2017-01-20 11:39:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# teardown
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# setup
# native server - we can get a ton of connections and data through and still clean up the server completely
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Creating Native Server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'listening 50004'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
ok 82 native server is nulled out
ok 83 native server should be closed
ok 84 incoming has been removed
2017-01-20 11:39:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# teardown
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# native server - simulate mux failure, make sure everything is cleaned up
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Creating Native Server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'listening 50056'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 85 we should not have gotten an error
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 86 Buffers are identical
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 87 server should be fine
ok 88 server should be open
ok 89 incoming has been removed
ok 90 The mux object should be closed
ok 91 The mux stream should be closed
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# teardown
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - close'
# setup
# native server - timing out the incoming connection cleans everything up
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Creating Native Server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'listening 50060'
ok 92 we should not have gotten an error
2017-01-20 11:39:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 93 Buffers are identical
2017-01-20 11:39:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 94 server should be fine
ok 95 server should be open
ok 96 incoming has been removed
ok 97 The mux object should be closed
ok 98 The mux stream should be closed
# teardown
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - close'
# setup
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# calling createPeerListener without calling start produces error
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Creating Native Server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'listening 50065'
# teardown
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - close'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# calling createPeerListener after calling stop produces error
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Creating Native Server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'listening 50068'
# teardown
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - close'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# can call createPeerListener
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Creating Native Server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'listening 50071'
2017-01-20 11:39:39 - DEBUG createPeerListener: 'creating new server for peerId'
2017-01-20 11:39:39 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peerId listening on 50072'
ok 99 port must be in range
# teardown
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - close'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# calling createPeerListener twice with same peerIdentifier should return the same port
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Creating Native Server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'listening 50075'
2017-01-20 11:39:39 - DEBUG createPeerListener: 'creating new server for peer1'
2017-01-20 11:39:39 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50076'
ok 100 port values should be the same
# teardown
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - close'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - closing connection to native listener closes everything and triggers new listener
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Creating Native Server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'listening 50079'
2017-01-20 11:39:39 - DEBUG createPeerListener: 'creating new server for peer2'
2017-01-20 11:39:39 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 50080'
2017-01-20 11:39:39 - DEBUG createPeerListener: 'Issuing callNative for peer2'
2017-01-20 11:39:39 - DEBUG createPeerListener: 'callNative for peer2 connected'
2017-01-20 11:39:39 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer2'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 101 Data should be of same length and content
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG createPeerListener: 'We are emitting failedConnection with error "Error: Outgoing closed, recreating connection" and peerIdentifier "peer2"'
2017-01-20 11:39:39 - DEBUG createPeerListener: 'Will try to recreate server for peer2'
2017-01-20 11:39:39 - DEBUG createPeerListener: 'creating new server for peer2'
2017-01-20 11:39:39 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 50085'
2017-01-20 11:39:39 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer2 and portNumber 50085'
ok 102 same peer ID
ok 103 different ports
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
# teardown
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - close'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# createPeerListener - closing mux closes listener and triggers a new listener
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Creating Native Server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'listening 50088'
2017-01-20 11:39:39 - DEBUG createPeerListener: 'creating new server for peer2'
2017-01-20 11:39:39 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 50089'
2017-01-20 11:39:39 - DEBUG createPeerListener: 'Issuing callNative for peer2'
2017-01-20 11:39:39 - DEBUG createPeerListener: 'callNative for peer2 connected'
2017-01-20 11:39:39 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer2'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 104 Data should be of same length and content
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG createPeerListener: 'We are emitting failedConnection with error "Error: Outgoing closed, recreating connection" and peerIdentifier "peer2"'
2017-01-20 11:39:39 - DEBUG createPeerListener: 'Will try to recreate server for peer2'
2017-01-20 11:39:39 - DEBUG createPeerListener: 'creating new server for peer2'
2017-01-20 11:39:39 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 50094'
2017-01-20 11:39:39 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer2 and portNumber 50094'
ok 105 same peer ID
ok 106 different ports
# teardown
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - close'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# peerListener - no native server
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Creating Native Server'
ok 107 Can call startUpdateAdvertisingAndListening without error
ok 108 Can call startListeningForAdvertisements without error
2017-01-20 11:39:39 - DEBUG createPeerListener: 'creating new server for peer1'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'listening 50097'
2017-01-20 11:39:39 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50098'
ok 109 peerPort should not be nativePort
2017-01-20 11:39:39 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2017-01-20 11:39:39 - DEBUG createPeerListener: 'callNative for peer1 connected'
2017-01-20 11:39:39 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG createPeerListener: 'We are emitting failedConnection with error "Error: Cannot Connect To Peer" and peerIdentifier "peer1"'
ok 110 Should not get event until connection is made
ok 111 reason should be as expected
2017-01-20 11:39:39 - DEBUG createPeerListener: 'Will try to recreate server for peer1'
2017-01-20 11:39:39 - DEBUG createPeerListener: 'creating new server for peer1'
2017-01-20 11:39:39 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50101'
2017-01-20 11:39:39 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer1 and portNumber 50101'
# teardown
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - close'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# peerListener - with native server
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Creating Native Server'
ok 112 Can call startUpdateAdvertisingAndListening without error
ok 113 Can call startListeningForAdvertisements without error
2017-01-20 11:39:39 - DEBUG createPeerListener: 'creating new server for peer1'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'listening 50104'
2017-01-20 11:39:39 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50105'
ok 114 peerPort != nativePort
2017-01-20 11:39:39 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2017-01-20 11:39:39 - DEBUG createPeerListener: 'callNative for peer1 connected'
2017-01-20 11:39:39 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
ok 115 Should not get unexpected connection
# teardown
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - close'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# peerListener - with native server and data transfer
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Creating Native Server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'listening 50110'
2017-01-20 11:39:39 - DEBUG createPeerListener: 'creating new server for peer1'
2017-01-20 11:39:39 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50111'
2017-01-20 11:39:39 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2017-01-20 11:39:39 - DEBUG createPeerListener: 'callNative for peer1 connected'
2017-01-20 11:39:39 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 116 Data should be of same length and content
ok 117 Data should be of same length and content
# teardown
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - close'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-01-20 11:39:39 - WARN createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 -  error Error: read ECONNRESET'
# setup
2017-01-20 11:39:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# createPeerListener is idempotent
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Creating Native Server'
ok 118 Can call startUpdateAdvertisingAndListening without error
ok 119 Can call startListeningForAdvertisements without error
2017-01-20 11:39:39 - DEBUG createPeerListener: 'creating new server for peer1'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'listening 50117'
2017-01-20 11:39:39 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50118'
ok 120 Second call to existing peerListener returns existing port
# teardown
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - close'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - ask for new peer when we are at maximum and make sure we remove the right existing listener
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Creating Native Server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'listening 50121'
# teardown
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - close'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - ask for a new peer when we are not at maximum peers and make sure we do not remove any existing listeners
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Creating Native Server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'listening 50124'
# teardown
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - close'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - test timeout
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Creating Native Server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'listening 50127'
# teardown
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - close'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - multiple connections out
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Creating Native Server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'listening 50130'
# teardown
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - close'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - multiple bi-directional connections
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Creating Native Server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'listening 50133'
# teardown
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - close'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - multiple parallel calls
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Creating Native Server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'listening 50136'
# teardown
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - close'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - we shouldn't create a dead pipe
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Creating Native Server'
ok 121 Can call startUpdateAdvertisingAndListening without error
ok 122 Can call startListeningForAdvertisements without error
2017-01-20 11:39:39 - DEBUG createPeerListener: 'creating new server for peer1'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'listening 50139'
2017-01-20 11:39:39 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50140'
ok 123 peerPort != nativePort
2017-01-20 11:39:39 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2017-01-20 11:39:39 - DEBUG createPeerListener: 'callNative for peer1 connected'
2017-01-20 11:39:39 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
ok 124 Should not get unexpected connection
2017-01-20 11:39:39 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID peer1 with port 50140'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client - is already closed'
ok 125 passed
# teardown
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - close'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# can create servers manager
ok 126 serversManager must not be null
ok 127 serversManager must be an object
# teardown
# setup
# calling stop without start causes error
ok 128 We need to call start first
# teardown
# setup
# can start/stop servers manager
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Creating Native Server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'listening 50143'
ok 129 port must be in range
# teardown
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - close'
# setup
# starting twice resolves with listening port
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Creating Native Server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'listening 50144'
ok 130 second start should return same port
# teardown
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - close'
# setup
# terminateIncomingConnection will terminate a connection
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Creating Native Server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'listening 50146'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 131 we should be connected
2017-01-20 11:39:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 132 now we are disconnected
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG createNativeListener: 'Native Server - close'
# setup
# terminate an Outgoing connection
2017-01-20 11:39:39 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
ok 133 Passed bogus id
2017-01-20 11:39:39 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
ok 134 Passed good id but bogus port
2017-01-20 11:39:39 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
ok 135 Passed right context
ok 136 Right server
ok 137 No error should be set
ok 138 Retry should be false
ok 139 We called close server
# teardown
# setup
ok 140 should be in started state
# After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
2017-01-20 11:39:39 - INFO nodeSSDPClientLogger: '{ address: 'http://0.0.0.0:1900' } 'SSDP listening''
2017-01-20 11:39:39 - INFO nodeSSDPClientLogger: 'Socket bound'
2017-01-20 11:39:39 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"74effee8-a256-4131-9507-073d12556f5c","generation":0,"hostAddress":"8df35247","portNumber":8080}'
ok 141 peer identifier should match
ok 142 generation should be 0
ok 143 host address should match
ok 144 port should match
2017-01-20 11:39:39 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"74effee8-a256-4131-9507-073d12556f5c","generation":0,"portNumber":null,"hostAddress":null}'
ok 145 generation should be 0
ok 146 host address should be null
ok 147 port should should be null
# teardown
ok 148 should not be in started state
# setup
ok 149 should be in started state
# #startUpdateAdvertisingAndListening correctly updates USN
2017-01-20 11:39:39 - DEBUG thaliWifiInfrastructure: 'listening 50148'
2017-01-20 11:39:39 - INFO nodeSSDPServerLogger: '{ address: 'http://0.0.0.0:1900' } 'SSDP listening''
2017-01-20 11:39:39 - INFO nodeSSDPServerLogger: 'UDP socket bound'
2017-01-20 11:39:39 - INFO nodeSSDPServerLogger: 'Socket bound'
ok 150 first invocation sets 0 generation
2017-01-20 11:39:39 - INFO nodeSSDPServerLogger: '{ address: 'http://0.0.0.0:1900' } 'SSDP listening''
2017-01-20 11:39:39 - INFO nodeSSDPServerLogger: 'UDP socket bound'
2017-01-20 11:39:39 - INFO nodeSSDPServerLogger: 'Socket bound'
ok 151 second invocation doesn’t change UUID but increments generation
2017-01-20 11:39:39 - INFO nodeSSDPServerLogger: '{ address: 'http://0.0.0.0:1900' } 'SSDP listening''
2017-01-20 11:39:39 - INFO nodeSSDPServerLogger: 'UDP socket bound'
2017-01-20 11:39:39 - INFO nodeSSDPServerLogger: 'Socket bound'
ok 152 third invocation doesn’t change UUID but increments generation
# teardown
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 153 should not be in started state
# setup
ok 154 should be in started state
# #startUpdateAdvertisingAndListening generates new peerIdentifier after #stopAdvertisingAndListening has been called
2017-01-20 11:39:39 - DEBUG thaliWifiInfrastructure: 'listening 50149'
2017-01-20 11:39:39 - INFO nodeSSDPServerLogger: '{ address: 'http://0.0.0.0:1900' } 'SSDP listening''
2017-01-20 11:39:39 - INFO nodeSSDPServerLogger: 'UDP socket bound'
2017-01-20 11:39:39 - INFO nodeSSDPServerLogger: 'Socket bound'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG thaliWifiInfrastructure: 'listening 50150'
2017-01-20 11:39:39 - INFO nodeSSDPServerLogger: '{ address: 'http://0.0.0.0:1900' } 'SSDP listening''
2017-01-20 11:39:39 - INFO nodeSSDPServerLogger: 'UDP socket bound'
2017-01-20 11:39:39 - INFO nodeSSDPServerLogger: 'Socket bound'
ok 155 new UUID after advertising is stopped
# teardown
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 156 should not be in started state
# setup
ok 157 should be in started state
# #startUpdateAdvertisingAndListening sends correct requests
2017-01-20 11:39:39 - DEBUG thaliWifiInfrastructure: 'listening 50151'
2017-01-20 11:39:39 - INFO nodeSSDPServerLogger: '{ address: 'http://0.0.0.0:1900' } 'SSDP listening''
2017-01-20 11:39:39 - INFO nodeSSDPServerLogger: 'UDP socket bound'
2017-01-20 11:39:39 - INFO nodeSSDPServerLogger: 'Socket bound'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 158 advertise-alive fired with expected usn
ok 159 advertise-bye fired with expected usn
# teardown
ok 160 should not be in started state
# setup
ok 161 should be in started state
# messages with invalid location or USN should be ignored
2017-01-20 11:39:39 - WARN thaliWifiInfrastructure: 'Failed to parse a valid port number from location: http://foo.bar:90000'
ok 162 should not have emitted with invalid port
2017-01-20 11:39:39 - WARN thaliWifiInfrastructure: 'Invalid USN (expected "data:" prefix): foobar'
ok 163 should not have emitted with invalid USN
# teardown
ok 164 should not be in started state
# setup
ok 165 should be in started state
# Delayed own message are still ignored after advertisement has been toggled on and off several times
2017-01-20 11:39:39 - DEBUG thaliWifiInfrastructure: 'listening 50152'
2017-01-20 11:39:39 - INFO nodeSSDPServerLogger: '{ address: 'http://0.0.0.0:1900' } 'SSDP listening''
2017-01-20 11:39:39 - INFO nodeSSDPServerLogger: 'UDP socket bound'
2017-01-20 11:39:39 - INFO nodeSSDPServerLogger: 'Socket bound'
2017-01-20 11:39:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:39 - DEBUG thaliWifiInfrastructure: 'listening 50153'
2017-01-20 11:39:39 - INFO nodeSSDPServerLogger: '{ address: 'http://0.0.0.0:1900' } 'SSDP listening''
2017-01-20 11:39:39 - WARN nodeSSDPServerLogger: '{ [Error: addMembership ENOMEM] code: 'ENOMEM', errno: 'ENOMEM', syscall: 'addMembership' } 'Not enough free memory to add multicast group membership. Scheduling a retry.''
2017-01-20 11:39:39 - INFO nodeSSDPServerLogger: 'Socket bound'
2017-01-20 11:39:40 - INFO nodeSSDPServerLogger: 'UDP socket bound'
2017-01-20 11:39:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:40 - DEBUG thaliWifiInfrastructure: 'listening 50154'
2017-01-20 11:39:40 - INFO nodeSSDPServerLogger: '{ address: 'http://0.0.0.0:1900' } 'SSDP listening''
2017-01-20 11:39:40 - INFO nodeSSDPServerLogger: 'UDP socket bound'
2017-01-20 11:39:40 - INFO nodeSSDPServerLogger: 'Socket bound'
2017-01-20 11:39:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:40 - DEBUG thaliWifiInfrastructure: 'listening 50155'
2017-01-20 11:39:40 - INFO nodeSSDPServerLogger: '{ address: 'http://0.0.0.0:1900' } 'SSDP listening''
2017-01-20 11:39:40 - INFO nodeSSDPServerLogger: 'UDP socket bound'
2017-01-20 11:39:40 - INFO nodeSSDPServerLogger: 'Socket bound'
ok 166 all captured messages are not handled
# teardown
2017-01-20 11:39:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 167 should not be in started state
# setup
ok 168 should be in started state
# verify that Thali-specific messages are filtered correctly
ok 169 messages with irrelevant NT should be ignored
ok 170 relevant messages should not be ignored
# teardown
ok 171 should not be in started state
# setup
ok 172 should be in started state
# #startListeningForAdvertisements should fail if start not called
ok 173 specific error should be returned
# teardown
ok 174 should not be in started state
# setup
ok 175 should be in started state
# #startUpdateAdvertisingAndListening should fail if start not called
ok 176 specific error should be returned
# teardown
ok 177 should not be in started state
# setup
ok 178 should be in started state
# #start should fail if called twice in a row
ok 179 specific error should be received
# teardown
ok 180 should not be in started state
# setup
ok 181 should be in started state
# should not be started after stop is called
ok 182 should not be started
ok 183 should not be listening
ok 184 should not target listening
ok 185 should not be advertising
ok 186 should not target advertising
# teardown
ok 187 should not be in started state
# setup
ok 188 should be in started state
# #startUpdateAdvertisingAndListening should fail invalid router has been passed
2017-01-20 11:39:40 - ERROR thaliWifiInfrastructure: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 189 specific error should be received
# teardown
ok 190 should not be in started state
# setup
ok 191 should be in started state
# #startUpdateAdvertisingAndListening should fail if router server starting fails
2017-01-20 11:39:40 - ERROR thaliWifiInfrastructure: 'Router server emitted an error: Error: listen EADDRINUSE'
ok 192 specific error expected
# teardown
ok 193 should not be in started state
# setup
ok 194 should be in started state
# #startUpdateAdvertisingAndListening should start hosting given router object
2017-01-20 11:39:40 - DEBUG thaliWifiInfrastructure: 'listening 50157'
2017-01-20 11:39:40 - INFO nodeSSDPServerLogger: '{ address: 'http://0.0.0.0:1900' } 'SSDP listening''
2017-01-20 11:39:40 - INFO nodeSSDPServerLogger: 'UDP socket bound'
2017-01-20 11:39:40 - INFO nodeSSDPServerLogger: 'Socket bound'
ok 195 server should respond with code 200
# teardown
2017-01-20 11:39:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 196 should not be in started state
# setup
ok 197 should be in started state
# #startUpdateAdvertisingAndListening bad psk should be rejected object
2017-01-20 11:39:40 - DEBUG thaliWifiInfrastructure: 'listening 50159'
2017-01-20 11:39:40 - INFO nodeSSDPServerLogger: '{ address: 'http://0.0.0.0:1900' } 'SSDP listening''
2017-01-20 11:39:40 - INFO nodeSSDPServerLogger: 'UDP socket bound'
2017-01-20 11:39:40 - INFO nodeSSDPServerLogger: 'Socket bound'
ok 198 Connection should be rejected
# teardown
2017-01-20 11:39:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 199 should not be in started state
# setup
ok 200 should be in started state
# #stop can be called multiple times in a row
ok 201 should be in stopped state
ok 202 should still be in stopped state
# teardown
ok 203 should not be in started state
# setup
ok 204 should be in started state
# #startListeningForAdvertisements can be called multiple times in a row
2017-01-20 11:39:40 - INFO nodeSSDPClientLogger: '{ address: 'http://0.0.0.0:1900' } 'SSDP listening''
2017-01-20 11:39:40 - INFO nodeSSDPClientLogger: 'Socket bound'
ok 205 should be in listening state
ok 206 should still be in listening state
# teardown
ok 207 should not be in started state
# setup
ok 208 should be in started state
# #stopListeningForAdvertisements can be called multiple times in a row
ok 209 should not be in listening state
ok 210 should still not be in listening state
# teardown
ok 211 should not be in started state
# setup
ok 212 should be in started state
# #stopAdvertisingAndListening can be called multiple times in a row
ok 213 should not be in advertising state
ok 214 should still not be in advertising state
# teardown
ok 215 should not be in started state
# setup
ok 216 should be in started state
# functions are run from a queue in the right order
2017-01-20 11:39:40 - DEBUG thaliWifiInfrastructure: 'listening 50161'
2017-01-20 11:39:40 - INFO nodeSSDPServerLogger: '{ address: 'http://0.0.0.0:1900' } 'SSDP listening''
2017-01-20 11:39:40 - INFO nodeSSDPServerLogger: 'UDP socket bound'
2017-01-20 11:39:40 - INFO nodeSSDPServerLogger: 'Socket bound'
2017-01-20 11:39:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 217 call order must match
# teardown
ok 218 should not be in started state
# setup
ok 219 should be in started state
# does not get peer changes from self
2017-01-20 11:39:40 - INFO nodeSSDPClientLogger: '{ address: 'http://0.0.0.0:1900' } 'SSDP listening''
2017-01-20 11:39:40 - INFO nodeSSDPClientLogger: 'Socket bound'
2017-01-20 11:39:40 - DEBUG thaliWifiInfrastructure: 'listening 50162'
2017-01-20 11:39:40 - INFO nodeSSDPServerLogger: '{ address: 'http://0.0.0.0:1900' } 'SSDP listening''
2017-01-20 11:39:40 - INFO nodeSSDPServerLogger: 'UDP socket bound'
2017-01-20 11:39:40 - INFO nodeSSDPServerLogger: 'Socket bound'
2017-01-20 11:39:41 - INFO nodeSSDPServerLogger: '{ address: 'http://0.0.0.0:1900' } 'SSDP listening''
2017-01-20 11:39:41 - INFO nodeSSDPServerLogger: 'UDP socket bound'
2017-01-20 11:39:41 - INFO nodeSSDPServerLogger: 'Socket bound'
# teardown
2017-01-20 11:39:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 220 should not be in started state
# setup
ok 221 should be in started state
# Make sure we turn on and off the Android multicast locks
2017-01-20 11:39:42 - INFO nodeSSDPClientLogger: '{ address: 'http://0.0.0.0:1900' } 'SSDP listening''
2017-01-20 11:39:42 - INFO nodeSSDPClientLogger: 'Socket bound'
ok 222 We have locked
ok 223 We have not unlocked
ok 224 No new locks
ok 225 We unlocked
# teardown
ok 226 should not be in started state
# setup
ok 227 should be in started state
# Make sure we do not use Android locks when we are not on Android
2017-01-20 11:39:42 - DEBUG SimpleThaliTape: 'test was skipped, name: 'Make sure we do not use Android locks when we are not on Android''
# teardown
ok 228 should not be in started state
# setup
ok 229 should be in started state
# network changes are ignored while stopping
2017-01-20 11:39:42 - INFO nodeSSDPClientLogger: '{ address: 'http://0.0.0.0:1900' } 'SSDP listening''
2017-01-20 11:39:42 - INFO nodeSSDPClientLogger: 'Socket bound'
2017-01-20 11:39:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":null,"ssidName":null}'
2017-01-20 11:39:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-01-20 11:39:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2017-01-20 11:39:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
ok 230 should not be called
# teardown
ok 231 should not be in started state
# setup
ok 232 should be in started state
# #startListeningForAdvertisements returns error if wifi is off and fires event when on
2017-01-20 11:39:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":null,"ssidName":null}'
2017-01-20 11:39:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
ok 233 wifi should be off
ok 234 specific error expected
2017-01-20 11:39:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2017-01-20 11:39:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-01-20 11:39:42 - INFO nodeSSDPClientLogger: '{ address: 'http://0.0.0.0:1900' } 'SSDP listening''
ok 235 discoveryActive should be true
2017-01-20 11:39:42 - INFO nodeSSDPClientLogger: 'Socket bound'
# teardown
ok 236 should not be in started state
# setup
ok 237 should be in started state
# #startUpdateAdvertisingAndListening returns error if wifi is off and fires event when on
2017-01-20 11:39:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":null,"ssidName":null}'
2017-01-20 11:39:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
ok 238 wifi should be off
ok 239 specific error expected
2017-01-20 11:39:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2017-01-20 11:39:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-01-20 11:39:42 - DEBUG thaliWifiInfrastructure: 'listening 50163'
2017-01-20 11:39:42 - INFO nodeSSDPServerLogger: '{ address: 'http://0.0.0.0:1900' } 'SSDP listening''
2017-01-20 11:39:42 - INFO nodeSSDPServerLogger: 'UDP socket bound'
ok 240 advertisingActive should be true
2017-01-20 11:39:42 - INFO nodeSSDPServerLogger: 'Socket bound'
# teardown
2017-01-20 11:39:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 241 should not be in started state
# setup
ok 242 should be in started state
# when wifi is enabled discovery is activated and peers become available
2017-01-20 11:39:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":null,"ssidName":null}'
2017-01-20 11:39:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
ok 243 wifi should be off
ok 244 specific error expected
2017-01-20 11:39:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2017-01-20 11:39:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-01-20 11:39:42 - INFO nodeSSDPClientLogger: '{ address: 'http://0.0.0.0:1900' } 'SSDP listening''
2017-01-20 11:39:42 - INFO nodeSSDPClientLogger: 'Socket bound'
2017-01-20 11:39:43 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"fb4fe1f5-ce24-4e8b-abac-77b97aa8a691","generation":0,"hostAddress":"8df35247","portNumber":8080}'
ok 245 peer identifier should match
ok 246 host address should match
ok 247 port should match
# teardown
ok 248 should not be in started state
# setup
# #startListeningForAdvertisements should fail if start not called
ok 249 specific error should be returned
# teardown
ok 250 error should be null
ok 251 error should be null
# setup
# #startUpdateAdvertisingAndListening should fail if start not called
ok 252 specific error should be returned
# teardown
ok 253 error should be null
ok 254 error should be null
# setup
# should be able to call #stopListeningForAdvertisements many times
ok 255 error should be null
ok 256 error should be null
ok 257 error should be null
ok 258 error should be null
# teardown
ok 259 error should be null
ok 260 error should be null
# setup
# should be able to call #startListeningForAdvertisements many times
2017-01-20 11:39:43 - INFO nodeSSDPClientLogger: '{ address: 'http://0.0.0.0:1900' } 'SSDP listening''
2017-01-20 11:39:43 - INFO nodeSSDPClientLogger: 'Socket bound'
ok 261 error should be null
ok 262 error should be null
ok 263 error should be null
ok 264 error should be null
# teardown
2017-01-20 11:39:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 265 error should be null
ok 266 error should be null
# setup
# should be able to call #startUpdateAdvertisingAndListening many times
2017-01-20 11:39:43 - DEBUG thaliWifiInfrastructure: 'listening 50164'
2017-01-20 11:39:43 - INFO nodeSSDPServerLogger: '{ address: 'http://0.0.0.0:1900' } 'SSDP listening''
2017-01-20 11:39:43 - INFO nodeSSDPServerLogger: 'UDP socket bound'
2017-01-20 11:39:43 - INFO nodeSSDPServerLogger: 'Socket bound'
ok 267 error should be null
ok 268 error should be null
2017-01-20 11:39:43 - INFO nodeSSDPServerLogger: '{ address: 'http://0.0.0.0:1900' } 'SSDP listening''
2017-01-20 11:39:43 - INFO nodeSSDPServerLogger: 'UDP socket bound'
2017-01-20 11:39:43 - INFO nodeSSDPServerLogger: 'Socket bound'
ok 269 error should be null
ok 270 error should be null
# teardown
2017-01-20 11:39:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 271 error should be null
ok 272 error should be null
# setup
# should be able to call #stopAdvertisingAndListening many times
ok 273 error should be null
ok 274 error should be null
ok 275 error should be null
ok 276 error should be null
# teardown
ok 277 error should be null
ok 278 error should be null
# setup
# #start - Causing native or wifi to fail will cause a promise reject 
2017-01-20 11:39:43 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
ok 279 This should not cause wifi to fail
ok 280 native router should be bad
# teardown
ok 281 error should be null
ok 282 error should be null
# setup
# #start should fail if called twice in a row
ok 283 first call should succeed
ok 284 first call should succeed
ok 285 specific error should be returned
# teardown
ok 286 error should be null
ok 287 error should be null
# setup
# #stop should clear watchers and change peers
2017-01-20 11:39:43 - DEBUG thaliMobileNativeWrapper: 'listening 50165'
2017-01-20 11:39:43 - DEBUG createNativeListener: 'Creating Native Server'
2017-01-20 11:39:43 - DEBUG createNativeListener: 'listening 50166'
2017-01-20 11:39:43 - INFO nodeSSDPClientLogger: '{ address: 'http://0.0.0.0:1900' } 'SSDP listening''
2017-01-20 11:39:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-01-20 11:39:43 - INFO nodeSSDPClientLogger: 'Socket bound'
2017-01-20 11:39:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"urn:uuid:755e2168-614b-441d-93a0-ec9491931a56","peerAvailable":true}'
2017-01-20 11:39:43 - DEBUG createPeerListener: 'creating new server for urn:uuid:755e2168-614b-441d-93a0-ec9491931a56'
2017-01-20 11:39:43 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for urn:uuid:755e2168-614b-441d-93a0-ec9491931a56 listening on 50167'
2017-01-20 11:39:43 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"urn:uuid:755e2168-614b-441d-93a0-ec9491931a56","peerAvailable":true,"portNumber":50167}'
2017-01-20 11:39:43 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"urn:uuid:755e2168-614b-441d-93a0-ec9491931a56","connectionType":"AndroidBluetooth","peerAvailable":true,"newAddressPort":false}'
ok 288 Watchers have one entry for our connection type
ok 289 Peer availabilities has one entry for our connection type
2017-01-20 11:39:43 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"urn:uuid:755e2168-614b-441d-93a0-ec9491931a56","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-01-20 11:39:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-01-20 11:39:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-01-20 11:39:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:43 - DEBUG createNativeListener: 'Native Server - close'
2017-01-20 11:39:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 290 No watchers
ok 291 No peers
ok 292 No watchers
ok 293 No peers
ok 294 No watchers
ok 295 No peers
# teardown
ok 296 error should be null
ok 297 error should be null
# setup
# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
2017-01-20 11:39:43 - DEBUG SimpleThaliTape: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
# teardown
ok 298 error should be null
ok 299 error should be null
# setup
# does not emit duplicate discoveryAdvertisingStateUpdate
2017-01-20 11:39:43 - INFO nodeSSDPClientLogger: '{ address: 'http://0.0.0.0:1900' } 'SSDP listening''
2017-01-20 11:39:43 - INFO nodeSSDPClientLogger: 'Socket bound'
2017-01-20 11:39:43 - DEBUG thaliWifiInfrastructure: 'listening 50168'
2017-01-20 11:39:43 - INFO nodeSSDPServerLogger: '{ address: 'http://0.0.0.0:1900' } 'SSDP listening''
2017-01-20 11:39:43 - INFO nodeSSDPServerLogger: 'UDP socket bound'
2017-01-20 11:39:43 - INFO nodeSSDPServerLogger: 'Socket bound'
ok 300 called only once
ok 301 discovery state matches
ok 302 advertising state matches
# teardown
2017-01-20 11:39:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-01-20 11:39:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-01-20 11:39:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-01-20 11:39:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 303 error should be null
ok 304 error should be null
# setup
# does not send duplicate availability changes
2017-01-20 11:39:43 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"33f5ab72-9023-42d4-9d7d-7527e549e970","connectionType":"AndroidBluetooth","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 305 should be called once
ok 306 should not have been called more than once
# teardown
2017-01-20 11:39:43 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"33f5ab72-9023-42d4-9d7d-7527e549e970","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 307 error should be null
ok 308 error should be null
# setup
# can get the network status
ok 309 network status should have certain non-empty properties
# teardown
ok 310 error should be null
ok 311 error should be null
# setup
# wifi peer is marked unavailable if announcements stop
2017-01-20 11:39:43 - INFO nodeSSDPClientLogger: '{ address: 'http://0.0.0.0:1900' } 'SSDP listening''
2017-01-20 11:39:43 - INFO nodeSSDPClientLogger: 'Socket bound'
2017-01-20 11:39:43 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"9cd9ee6d-f32e-4a36-a515-959c200029b8","generation":0,"hostAddress":"4a63316d","portNumber":8080}'
2017-01-20 11:39:43 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9cd9ee6d-f32e-4a36-a515-959c200029b8","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 312 peer should be available
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9cd9ee6d-f32e-4a36-a515-959c200029b8","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 313 peer should become unavailable
# teardown
2017-01-20 11:39:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 314 error should be null
ok 315 error should be null
# setup
# native peer should be removed if no availability updates were received during availability timeout
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e3a92bd4-4dd3-436c-af6e-32cf62b88ece","connectionType":"AndroidBluetooth","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 316 peer is available
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"e3a92bd4-4dd3-436c-af6e-32cf62b88ece","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 317 peer is not availabel because it was too silent
# teardown
ok 318 error should be null
ok 319 error should be null
# setup
# peerAvailabilityChanged - peer added/removed to/from cache (native)
ok 320 we have not added peer to the cache yet
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"01536682-603f-4da0-aa57-b709ddd9df37","connectionType":"AndroidBluetooth","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 321 peer should be available
ok 322 cache contains native peer
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"01536682-603f-4da0-aa57-b709ddd9df37","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 323 peer should be unavailable
ok 324 peer has been removed from cache
# teardown
ok 325 error should be null
ok 326 error should be null
# setup
# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
ok 327 we have not added peer to the cache yet
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"eb16e9d3-82da-4fb5-bbd3-4b4a94b6c178","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 328 peer should be available
ok 329 cache contains wifi peer
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"eb16e9d3-82da-4fb5-bbd3-4b4a94b6c178","connectionType":"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 330 peer should be unavailable
ok 331 peer has been removed from cache
# teardown
ok 332 error should be null
ok 333 error should be null
# setup
# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"94ea98af-73ce-4c71-a02e-77f6e6c9e2e4","connectionType":"AndroidBluetooth","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 334 first peer is available
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"323a54ee-4e0c-485c-8276-3b79f922915c","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 335 second peer is available
ok 336 first and second peers are different
# teardown
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"94ea98af-73ce-4c71-a02e-77f6e6c9e2e4","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"323a54ee-4e0c-485c-8276-3b79f922915c","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 337 error should be null
ok 338 error should be null
# setup
# native available - new peer is cached
ok 339 should not be in cache at start
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"20033c05-54ac-44bc-91f3-207bbf31257d","connectionType":"AndroidBluetooth","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 340 peer is available
# teardown
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"20033c05-54ac-44bc-91f3-207bbf31257d","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 341 error should be null
ok 342 error should be null
# setup
# native available - peer with same port and different generation is cached (BLUETOOTH)
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7eba4cff-c574-4f2d-a0d1-b4adf1fe9659","connectionType":"AndroidBluetooth","peerAvailable":true,"generation":2,"newAddressPort":false}'
ok 343 peer should be available
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7eba4cff-c574-4f2d-a0d1-b4adf1fe9659","connectionType":"AndroidBluetooth","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 344 peer should be available
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7eba4cff-c574-4f2d-a0d1-b4adf1fe9659","connectionType":"AndroidBluetooth","peerAvailable":true,"generation":1,"newAddressPort":false}'
ok 345 peer should be available
# teardown
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"7eba4cff-c574-4f2d-a0d1-b4adf1fe9659","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 346 error should be null
ok 347 error should be null
# setup
# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a2831598-0f65-4ffe-b937-3ccef1abf9a8","connectionType":"AndroidBluetooth","peerAvailable":true,"generation":2,"newAddressPort":false}'
ok 348 peer should be available
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a2831598-0f65-4ffe-b937-3ccef1abf9a8","connectionType":"AndroidBluetooth","peerAvailable":true,"generation":2,"newAddressPort":false}'
ok 349 peer should be available
# teardown
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"a2831598-0f65-4ffe-b937-3ccef1abf9a8","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 350 error should be null
ok 351 error should be null
# setup
# native available - peer with greater generation is cached (MPCF)
2017-01-20 11:39:44 - DEBUG SimpleThaliTape: 'test was skipped, name: 'native available - peer with greater generation is cached (MPCF)''
# teardown
ok 352 error should be null
ok 353 error should be null
# setup
# native available - peer with same or older generation is ignored (MPCF)
2017-01-20 11:39:44 - DEBUG SimpleThaliTape: 'test was skipped, name: 'native available - peer with same or older generation is ignored (MPCF)''
# teardown
ok 354 error should be null
ok 355 error should be null
# setup
# native unavailable - new peer is ignored
ok 356 NOT IMPLEMENTED # SKIP
# teardown
ok 357 error should be null
ok 358 error should be null
# setup
# native unavailable - cached peer is removed
ok 359 NOT IMPLEMENTED # SKIP
# teardown
ok 360 error should be null
ok 361 error should be null
# setup
# networkChanged - fires peerAvailabilityChanged event for wifi peers
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6b85c6da-bd88-4ea0-aad8-c90c58f1f5f6","connectionType":"AndroidBluetooth","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 362 first peer is expected to be available
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1f29cd5e-549d-4fcd-92c0-7aaa8b53213a","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 363 second peer is expected to be available
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1f29cd5e-549d-4fcd-92c0-7aaa8b53213a","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 364 peer became unavailable
ok 365 it was wifi peer
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1f29cd5e-549d-4fcd-92c0-7aaa8b53213a","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 366 we found peer again
ok 367 it was wifi peer
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1f29cd5e-549d-4fcd-92c0-7aaa8b53213a","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 368 peer became unavailable
ok 369 it was wifi peer
# teardown
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"6b85c6da-bd88-4ea0-aad8-c90c58f1f5f6","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 370 error should be null
ok 371 error should be null
# setup
# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b9f223c3-ef78-40aa-9f31-7bab59c6dd51","connectionType":"AndroidBluetooth","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 372 first peer is expected to be available
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8585eb71-4cca-4696-aebc-890711f4c03f","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 373 second peer is expected to be available
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b9f223c3-ef78-40aa-9f31-7bab59c6dd51","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 374 peer became unavailable
ok 375 it was a native peer
# teardown
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8585eb71-4cca-4696-aebc-890711f4c03f","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 376 error should be null
ok 377 error should be null
# setup
# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
2017-01-20 11:39:44 - DEBUG SimpleThaliTape: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''
# teardown
ok 378 error should be null
ok 379 error should be null
# setup
# multiconnect failure - new peer is ignored (MPCF)
2017-01-20 11:39:44 - DEBUG SimpleThaliTape: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
# teardown
ok 380 error should be null
ok 381 error should be null
# setup
# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
2017-01-20 11:39:44 - DEBUG SimpleThaliTape: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
# teardown
ok 382 error should be null
ok 383 error should be null
# setup
# newAddressPort field (TCP_NATIVE)
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"66806b1f-3e03-4d2f-a78c-2993f18e939a","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 384 peer discovered first time does not have new address
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"66806b1f-3e03-4d2f-a78c-2993f18e939a","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":false}'
ok 385 address has not been changed
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"66806b1f-3e03-4d2f-a78c-2993f18e939a","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
ok 386 new port handled correctly
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"66806b1f-3e03-4d2f-a78c-2993f18e939a","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
ok 387 new host handled correctly
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"66806b1f-3e03-4d2f-a78c-2993f18e939a","connectionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
ok 388 newAddressPort is null for unavailable peers
# teardown
ok 389 error should be null
ok 390 error should be null
# setup
# newAddressPort field (BLUETOOTH)
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4c867d69-7d12-47aa-b6bb-9d99c25a8b37","connectionType":"AndroidBluetooth","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 391 peer discovered first time does not have new address
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4c867d69-7d12-47aa-b6bb-9d99c25a8b37","connectionType":"AndroidBluetooth","peerAvailable":true,"generation":20,"newAddressPort":false}'
ok 392 address has not been changed
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4c867d69-7d12-47aa-b6bb-9d99c25a8b37","connectionType":"AndroidBluetooth","peerAvailable":true,"generation":20,"newAddressPort":true}'
ok 393 new port handled correctly
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4c867d69-7d12-47aa-b6bb-9d99c25a8b37","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":20,"newAddressPort":null}'
ok 394 newAddressPort is null for unavailable peers
# teardown
ok 395 error should be null
ok 396 error should be null
# setup
# newAddressPort field (MPCF)
2017-01-20 11:39:44 - DEBUG SimpleThaliTape: 'test was skipped, name: 'newAddressPort field (MPCF)''
# teardown
ok 397 error should be null
ok 398 error should be null
# setup
# newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)
ok 399 NOT IMPLEMENTED # SKIP
# teardown
ok 400 error should be null
ok 401 error should be null
# setup
# #getPeerHostInfo - error when peer has not been discovered yet
ok 402 should be equal
# teardown
ok 403 error should be null
ok 404 error should be null
# setup
# #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"AndroidBluetooth","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 405 contains expected properties
ok 406 the same hostAddress
ok 407 the same portNumber
# teardown
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 408 error should be null
ok 409 error should be null
# setup
# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
2017-01-20 11:39:44 - DEBUG SimpleThaliTape: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)''
# teardown
ok 410 error should be null
ok 411 error should be null
# setup
# #getPeerHostInfo - returns discovered cached wifi peer
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 412 contains expected properties
ok 413 the same hostAddress
ok 414 the same portNumber
# teardown
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 415 error should be null
ok 416 error should be null
# setup
# #disconnect fails on wifi peers
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"44648644-c832-4017-8a3a-b8e87b8648ff","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 417 Got specific error message
# teardown
2017-01-20 11:39:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"44648644-c832-4017-8a3a-b8e87b8648ff","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 418 error should be null
ok 419 error should be null
# setup
# #disconnect delegates native peers to the native wrapper
2017-01-20 11:39:44 - DEBUG SimpleThaliTape: 'test was skipped, name: '#disconnect delegates native peers to the native wrapper''
# teardown
ok 420 error should be null
ok 421 error should be null
# setup
# network changes emitted correctly
2017-01-20 11:39:44 - DEBUG SimpleThaliTape: 'test was skipped, name: 'network changes emitted correctly''
# teardown
ok 422 error should be null
ok 423 error should be null
# setup
# network changes not emitted in started state
2017-01-20 11:39:44 - DEBUG SimpleThaliTape: 'test was skipped, name: 'network changes not emitted in started state''
# teardown
ok 424 error should be null
ok 425 error should be null
# setup
# network changes not emitted in stopped state
2017-01-20 11:39:44 - DEBUG SimpleThaliTape: 'test was skipped, name: 'network changes not emitted in stopped state''
# teardown
ok 426 error should be null
ok 427 error should be null
# setup
# calls correct starts when network changes
2017-01-20 11:39:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":null,"ssidName":null}'
ok 428 specific error expected
ok 429 specific error expected
2017-01-20 11:39:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2017-01-20 11:39:44 - INFO nodeSSDPClientLogger: '{ address: 'http://0.0.0.0:1900' } 'SSDP listening''
2017-01-20 11:39:44 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":true,"listening":true,"advertising":true,"networkType":"WIFI","startArguments":{}})'
2017-01-20 11:39:44 - INFO nodeSSDPClientLogger: 'Socket bound'
not ok 430 startListeningForAdvertisements should have been called
  ---
    operator: equal
    expected: 1
    actual:   0
    at: Array.0 (/Users/thali/Github/Thali_CordovaPlugin/thali/node_modules/lie/lib/index.js:88:21)
  ...
not ok 431 startUpdateAdvertisingAndListening should have been called
  ---
    operator: equal
    expected: 1
    actual:   0
    at: Array.0 (/Users/thali/Github/Thali_CordovaPlugin/thali/node_modules/lie/lib/index.js:88:21)
  ...
2017-01-20 11:39:44 - ERROR SimpleThaliTape: 'test failed, name: 'calls correct starts when network changes''
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - closeAll with promise'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - closeAll works even with a server that is not listening yet witheatNotRunning set to true'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Call of onCheckpointReached handler on a single db change'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Call of multiple onCheckpointReached handlers on a single db change'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Can safely destroy db in the middle of the checkpoint delay interval'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Can safely destroy db in the middle of its size calculating'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - enqueue and run in order'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - queues handled independently'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - basic'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - another'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - emits incomingConnectionState'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - native server connections all up'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - calling createPeerListener without calling start produces error'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - calling createPeerListener after calling stop produces error'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - can call createPeerListener'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - calling createPeerListener twice with same peerIdentifier should return the same port'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - createPeerListener - closing connection to native listener closes everything and triggers new listener'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - createPeerListener - closing mux closes listener and triggers a new listener'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - peerListener - no native server'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - peerListener - with native server'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - peerListener - with native server and data transfer'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - createPeerListener is idempotent'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - createPeerListener - ask for new peer when we are at maximum and make sure we remove the right existing listener'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - createPeerListener - ask for a new peer when we are not at maximum peers and make sure we do not remove any existing listeners'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - createPeerListener - test timeout'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - createPeerListener - multiple connections out'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - createPeerListener - multiple bi-directional connections'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - createPeerListener - multiple parallel calls'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - createPeerListener - we shouldn't create a dead pipe'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - can create servers manager'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - calling stop without start causes error'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - can start/stop servers manager'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening correctly updates USN'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening generates new peerIdentifier after #stopAdvertisingAndListening has been called'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening sends correct requests'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - messages with invalid location or USN should be ignored'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Delayed own message are still ignored after advertisement has been toggled on and off several times'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - verify that Thali-specific messages are filtered correctly'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #start should fail if called twice in a row'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - should not be started after stop is called'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail invalid router has been passed'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if router server starting fails'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should start hosting given router object'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening bad psk should be rejected object'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #stop can be called multiple times in a row'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #startListeningForAdvertisements can be called multiple times in a row'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #stopListeningForAdvertisements can be called multiple times in a row'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #stopAdvertisingAndListening can be called multiple times in a row'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - functions are run from a queue in the right order'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - does not get peer changes from self'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Make sure we turn on and off the Android multicast locks'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - Make sure we do not use Android locks when we are not on Android'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - network changes are ignored while stopping'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #startListeningForAdvertisements returns error if wifi is off and fires event when on'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening returns error if wifi is off and fires event when on'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - when wifi is enabled discovery is activated and peers become available'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #start - Causing native or wifi to fail will cause a promise reject '
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #start should fail if called twice in a row'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #stop should clear watchers and change peers'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - does not emit duplicate discoveryAdvertisingStateUpdate'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - does not send duplicate availability changes'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - can get the network status'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - wifi peer is marked unavailable if announcements stop'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - native peer should be removed if no availability updates were received during availability timeout'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (native)'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (wifi)'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - native available - new peer is cached'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - native available - peer with same port and different generation is cached (BLUETOOTH)'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - native available - peer with greater generation is cached (MPCF)'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - native available - peer with same or older generation is ignored (MPCF)'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - native unavailable - new peer is ignored'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - native unavailable - cached peer is removed'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for wifi peers'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - multiconnect failure - new peer is ignored (MPCF)'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - newAddressPort field (TCP_NATIVE)'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - newAddressPort field (BLUETOOTH)'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - newAddressPort field (MPCF)'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #getPeerHostInfo - error when peer has not been discovered yet'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached wifi peer'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #disconnect fails on wifi peers'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - #disconnect delegates native peers to the native wrapper'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - network changes emitted correctly'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - network changes not emitted in started state'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - network changes not emitted in stopped state'
2017-01-20 11:39:44 - INFO SimpleThaliTape: '***TEST_LOGGER result: failed - calls correct starts when network changes, error: 'Error: test failed, name: 'calls correct starts when network changes'', stack: 'Error: test failed, name: 'calls correct starts when network changes'
    at Test.endHandler (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/SimpleTape.js:143:16)
    at Test.g (events.js:160:16)
    at Test.emit (events.js:98:20)
    at Test.bound [as emit] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:62:32)
    at Test._end (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:145:27)
    at Test.bound [as _end] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:62:32)
    at Test.end (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:133:10)
    at Test.bound [as end] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:62:32)
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js:1713:13
    at Array.0 (/Users/thali/Github/Thali_CordovaPlugin/thali/node_modules/lie/lib/index.js:88:21)
    at nextTick (/Users/thali/Github/Thali_CordovaPlugin/thali/node_modules/immediate/lib/index.js:61:18)
    at process._tickCallback (node.js:924:13)''
2017-01-20 11:39:44 - ERROR SimpleThaliTape: 'failed to run unit tests, platformName: 'android''
2017-01-20 11:39:44 - DEBUG SimpleThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
2017-01-20 11:39:44 - DEBUG thaliWifiInfrastructure: 'listening 50169'
2017-01-20 11:39:44 - INFO nodeSSDPServerLogger: '{ address: 'http://0.0.0.0:1900' } 'SSDP listening''
2017-01-20 11:39:44 - INFO nodeSSDPServerLogger: 'UDP socket bound'
2017-01-20 11:39:44 - INFO nodeSSDPServerLogger: 'Socket bound'
2017-01-20 11:39:44 - ERROR runTests: 'test failed, name: 'calls correct starts when network changes'
Error: test failed, name: 'calls correct starts when network changes'
    at Test.endHandler (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/SimpleTape.js:143:16)
    at Test.g (events.js:160:16)
    at Test.emit (events.js:98:20)
    at Test.bound [as emit] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:62:32)
    at Test._end (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:145:27)
    at Test.bound [as _end] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:62:32)
    at Test.end (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:133:10)
    at Test.bound [as end] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:62:32)
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js:1713:13
    at Array.0 (/Users/thali/Github/Thali_CordovaPlugin/thali/node_modules/lie/lib/index.js:88:21)
    at nextTick (/Users/thali/Github/Thali_CordovaPlugin/thali/node_modules/immediate/lib/index.js:61:18)
    at process._tickCallback (node.js:924:13)'

[0;31merror: command 'jx runTests.js --networkType WIFI' failed with code 1, file 'build.sh' on line 62[0m
./build.sh CI FAILED - build.sh failure[0m

npm WARN thali-test-server@0.0.1 No repository field.
npm WARN thali-test-server@0.0.1 No license field.
npm http request GET http://192.168.1.100:4873/lodash.throttle
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/javascript-state-machine
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-leveldb-core
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/bluebird
npm http 200 http://192.168.1.100:4873/ip
npm http 200 http://192.168.1.100:4873/javascript-state-machine
npm http 200 http://192.168.1.100:4873/lodash.throttle
npm http 200 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/long
npm http 200 http://192.168.1.100:4873/pouchdb-adapter-leveldb-core
npm http fetch GET http://192.168.1.100:4873/lodash.throttle/-/lodash.throttle-4.1.1.tgz
npm http 200 http://192.168.1.100:4873/lie
npm http 200 http://192.168.1.100:4873/uuid
npm http 200 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/multiplex
npm http fetch 200 http://192.168.1.100:4873/lodash.throttle/-/lodash.throttle-4.1.1.tgz
npm http fetch GET http://192.168.1.100:4873/pouchdb-adapter-leveldb-core/-/pouchdb-adapter-leveldb-core-6.1.1.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-adapter-leveldb-core/-/pouchdb-adapter-leveldb-core-6.1.1.tgz
npm http 200 http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/on-finished
npm http 200 http://192.168.1.100:4873/bytes
npm http 200 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/type-is
npm http 200 http://192.168.1.100:4873/raw-body
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/statuses
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/statuses
npm http request GET http://192.168.1.100:4873/ee-first
npm http 304 http://192.168.1.100:4873/ee-first
npm http request GET http://192.168.1.100:4873/unpipe
npm http 304 http://192.168.1.100:4873/unpipe
npm http request GET http://192.168.1.100:4873/media-typer
npm http request GET http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/media-typer
npm http 304 http://192.168.1.100:4873/mime-types
npm http request GET http://192.168.1.100:4873/mime-db
npm http 304 http://192.168.1.100:4873/mime-db
npm http request GET http://192.168.1.100:4873/array-flatten
npm http request GET http://192.168.1.100:4873/content-disposition
npm http request GET http://192.168.1.100:4873/cookie
npm http request GET http://192.168.1.100:4873/cookie-signature
npm http request GET http://192.168.1.100:4873/escape-html
npm http request GET http://192.168.1.100:4873/etag
npm http request GET http://192.168.1.100:4873/finalhandler
npm http request GET http://192.168.1.100:4873/fresh
npm http request GET http://192.168.1.100:4873/merge-descriptors
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/accepts
npm http request GET http://192.168.1.100:4873/parseurl
npm http request GET http://192.168.1.100:4873/path-to-regexp
npm http request GET http://192.168.1.100:4873/proxy-addr
npm http request GET http://192.168.1.100:4873/range-parser
npm http request GET http://192.168.1.100:4873/serve-static
npm http request GET http://192.168.1.100:4873/utils-merge
npm http request GET http://192.168.1.100:4873/vary
npm http request GET http://192.168.1.100:4873/send
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/serve-static
npm http 304 http://192.168.1.100:4873/utils-merge
npm http 304 http://192.168.1.100:4873/vary
npm http 304 http://192.168.1.100:4873/send
npm http request GET http://192.168.1.100:4873/negotiator
npm http 304 http://192.168.1.100:4873/negotiator
npm http request GET http://192.168.1.100:4873/forwarded
npm http request GET http://192.168.1.100:4873/ipaddr.js
npm http 304 http://192.168.1.100:4873/forwarded
npm http 304 http://192.168.1.100:4873/ipaddr.js
npm http request GET http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/mime
npm http 304 http://192.168.1.100:4873/destroy
npm http 304 http://192.168.1.100:4873/mime
npm http request GET http://192.168.1.100:4873/immediate
npm http 200 http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/duplexify
npm http 200 http://192.168.1.100:4873/xtend
npm http 200 http://192.168.1.100:4873/varint
npm http 200 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/stream-shift
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http 304 http://192.168.1.100:4873/stream-shift
npm http 200 http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/wrappy
npm http 304 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/core-util-is
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/string_decoder
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/buffer-shims
npm http 304 http://192.168.1.100:4873/process-nextick-args
npm http 304 http://192.168.1.100:4873/string_decoder
npm http 304 http://192.168.1.100:4873/core-util-is
npm http 304 http://192.168.1.100:4873/util-deprecate
npm http request GET http://192.168.1.100:4873/buffer-from
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/pouchdb-json
npm http request GET http://192.168.1.100:4873/pouchdb-md5
npm http request GET http://192.168.1.100:4873/argsarray
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-utils
npm http request GET http://192.168.1.100:4873/pouchdb-merge
npm http request GET http://192.168.1.100:4873/pouchdb-binary-utils
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/pouchdb-errors
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/pouchdb-utils
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/through2
npm http 200 http://192.168.1.100:4873/buffer-from
npm http 200 http://192.168.1.100:4873/argsarray
npm http 200 http://192.168.1.100:4873/pouchdb-json
npm http fetch GET http://192.168.1.100:4873/buffer-from/-/buffer-from-0.1.1.tgz
npm http 200 http://192.168.1.100:4873/pouchdb-md5
npm http 200 http://192.168.1.100:4873/double-ended-queue
npm http fetch GET http://192.168.1.100:4873/pouchdb-json/-/pouchdb-json-6.1.1.tgz
npm http fetch GET http://192.168.1.100:4873/pouchdb-md5/-/pouchdb-md5-6.1.1.tgz
npm http 200 http://192.168.1.100:4873/pouchdb-adapter-utils
npm http 200 http://192.168.1.100:4873/pouchdb-merge
npm http 200 http://192.168.1.100:4873/levelup
npm http 200 http://192.168.1.100:4873/pouchdb-binary-utils
npm http 200 http://192.168.1.100:4873/pouchdb-collections
npm http 200 http://192.168.1.100:4873/pouchdb-errors
npm http fetch 200 http://192.168.1.100:4873/buffer-from/-/buffer-from-0.1.1.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-json/-/pouchdb-json-6.1.1.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-md5/-/pouchdb-md5-6.1.1.tgz
npm http 200 http://192.168.1.100:4873/sublevel-pouchdb
npm http 200 http://192.168.1.100:4873/pouchdb-utils
npm http 200 http://192.168.1.100:4873/pouchdb-promise
npm http fetch GET http://192.168.1.100:4873/double-ended-queue/-/double-ended-queue-2.1.0-0.tgz
npm http 200 http://192.168.1.100:4873/through2
npm http fetch 200 http://192.168.1.100:4873/double-ended-queue/-/double-ended-queue-2.1.0-0.tgz
npm http fetch GET http://192.168.1.100:4873/levelup/-/levelup-1.3.3.tgz
npm http fetch GET http://192.168.1.100:4873/pouchdb-errors/-/pouchdb-errors-6.1.1.tgz
npm http fetch GET http://192.168.1.100:4873/pouchdb-binary-utils/-/pouchdb-binary-utils-6.1.1.tgz
npm http fetch GET http://192.168.1.100:4873/pouchdb-merge/-/pouchdb-merge-6.1.1.tgz
npm http fetch GET http://192.168.1.100:4873/pouchdb-collections/-/pouchdb-collections-6.1.1.tgz
npm http fetch GET http://192.168.1.100:4873/pouchdb-adapter-utils/-/pouchdb-adapter-utils-6.1.1.tgz
npm http fetch 200 http://192.168.1.100:4873/levelup/-/levelup-1.3.3.tgz
npm http fetch GET http://192.168.1.100:4873/sublevel-pouchdb/-/sublevel-pouchdb-6.1.1.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-errors/-/pouchdb-errors-6.1.1.tgz
npm http fetch GET http://192.168.1.100:4873/pouchdb-utils/-/pouchdb-utils-6.1.1.tgz
npm http fetch GET http://192.168.1.100:4873/pouchdb-promise/-/pouchdb-promise-6.1.1.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-binary-utils/-/pouchdb-binary-utils-6.1.1.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-merge/-/pouchdb-merge-6.1.1.tgz
npm http fetch 200 http://192.168.1.100:4873/sublevel-pouchdb/-/sublevel-pouchdb-6.1.1.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-adapter-utils/-/pouchdb-adapter-utils-6.1.1.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-collections/-/pouchdb-collections-6.1.1.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-utils/-/pouchdb-utils-6.1.1.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-promise/-/pouchdb-promise-6.1.1.tgz
npm http request GET http://192.168.1.100:4873/is-array-buffer-x
npm http 200 http://192.168.1.100:4873/is-array-buffer-x
npm http fetch GET http://192.168.1.100:4873/is-array-buffer-x/-/is-array-buffer-x-1.0.13.tgz
npm http fetch 200 http://192.168.1.100:4873/is-array-buffer-x/-/is-array-buffer-x-1.0.13.tgz
npm http request GET http://192.168.1.100:4873/is-object-like-x
npm http request GET http://192.168.1.100:4873/to-string-tag-x
npm http request GET http://192.168.1.100:4873/has-to-string-tag-x
npm http 200 http://192.168.1.100:4873/is-object-like-x
npm http 200 http://192.168.1.100:4873/has-to-string-tag-x
npm http 200 http://192.168.1.100:4873/to-string-tag-x
npm http fetch GET http://192.168.1.100:4873/is-object-like-x/-/is-object-like-x-1.0.11.tgz
npm http fetch 200 http://192.168.1.100:4873/is-object-like-x/-/is-object-like-x-1.0.11.tgz
npm http fetch GET http://192.168.1.100:4873/has-to-string-tag-x/-/has-to-string-tag-x-1.0.10.tgz
npm http fetch GET http://192.168.1.100:4873/to-string-tag-x/-/to-string-tag-x-1.0.11.tgz
npm http fetch 200 http://192.168.1.100:4873/has-to-string-tag-x/-/has-to-string-tag-x-1.0.10.tgz
npm http fetch 200 http://192.168.1.100:4873/to-string-tag-x/-/to-string-tag-x-1.0.11.tgz
npm http request GET http://192.168.1.100:4873/has-symbol-support-x
npm http 200 http://192.168.1.100:4873/has-symbol-support-x
npm http fetch GET http://192.168.1.100:4873/has-symbol-support-x/-/has-symbol-support-x-1.0.11.tgz
npm http fetch 200 http://192.168.1.100:4873/has-symbol-support-x/-/has-symbol-support-x-1.0.11.tgz
npm http request GET http://192.168.1.100:4873/is-function-x
npm http request GET http://192.168.1.100:4873/is-primitive
npm http 200 http://192.168.1.100:4873/is-function-x
npm http 200 http://192.168.1.100:4873/is-primitive
npm http fetch GET http://192.168.1.100:4873/is-function-x/-/is-function-x-1.0.6.tgz
npm http fetch GET http://192.168.1.100:4873/is-primitive/-/is-primitive-2.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/is-primitive/-/is-primitive-2.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/is-function-x/-/is-function-x-1.0.6.tgz
npm http request GET http://192.168.1.100:4873/lodash.isnull
npm http request GET http://192.168.1.100:4873/validate.io-undefined
npm http 200 http://192.168.1.100:4873/lodash.isnull
npm http 200 http://192.168.1.100:4873/validate.io-undefined
npm http fetch GET http://192.168.1.100:4873/lodash.isnull/-/lodash.isnull-3.0.0.tgz
npm http fetch GET http://192.168.1.100:4873/validate.io-undefined/-/validate.io-undefined-1.0.3.tgz
npm http fetch 200 http://192.168.1.100:4873/lodash.isnull/-/lodash.isnull-3.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/validate.io-undefined/-/validate.io-undefined-1.0.3.tgz
npm http request GET http://192.168.1.100:4873/level-iterator-stream
npm http request GET http://192.168.1.100:4873/level-errors
npm http request GET http://192.168.1.100:4873/deferred-leveldown
npm http request GET http://192.168.1.100:4873/prr
npm http request GET http://192.168.1.100:4873/level-codec
npm http request GET http://192.168.1.100:4873/semver
npm http 200 http://192.168.1.100:4873/level-errors
npm http 200 http://192.168.1.100:4873/level-iterator-stream
npm http 200 http://192.168.1.100:4873/prr
npm http 200 http://192.168.1.100:4873/level-codec
npm http 200 http://192.168.1.100:4873/deferred-leveldown
npm http 200 http://192.168.1.100:4873/semver
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http 200 http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/errno
npm http 200 http://192.168.1.100:4873/errno
npm http request GET http://192.168.1.100:4873/spark-md5
npm http 200 http://192.168.1.100:4873/spark-md5
npm http fetch GET http://192.168.1.100:4873/spark-md5/-/spark-md5-3.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/spark-md5/-/spark-md5-3.0.0.tgz
npm http request GET http://192.168.1.100:4873/clone-buffer
npm http fetch GET http://192.168.1.100:4873/debug/-/debug-2.6.0.tgz
npm http fetch 200 http://192.168.1.100:4873/debug/-/debug-2.6.0.tgz
npm http 200 http://192.168.1.100:4873/clone-buffer
npm http fetch GET http://192.168.1.100:4873/clone-buffer/-/clone-buffer-1.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/clone-buffer/-/clone-buffer-1.0.0.tgz
npm http fetch GET http://192.168.1.100:4873/ms/-/ms-0.7.2.tgz
npm http fetch 200 http://192.168.1.100:4873/ms/-/ms-0.7.2.tgz
npm http request GET http://192.168.1.100:4873/vuvuzela
npm http 200 http://192.168.1.100:4873/vuvuzela
npm http request GET http://192.168.1.100:4873/ltgt
npm http fetch GET http://192.168.1.100:4873/level-codec/-/level-codec-6.2.0.tgz
npm http fetch 200 http://192.168.1.100:4873/level-codec/-/level-codec-6.2.0.tgz
npm http 200 http://192.168.1.100:4873/ltgt
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/hawk
npm http 200 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/caseless
npm http 200 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/bl
npm http 200 http://192.168.1.100:4873/tunnel-agent
npm http 200 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 200 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/stringstream
npm http 200 http://192.168.1.100:4873/combined-stream
npm http 200 http://192.168.1.100:4873/har-validator
npm http 200 http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http fetch GET http://192.168.1.100:4873/async/-/async-2.1.4.tgz
npm http fetch 200 http://192.168.1.100:4873/async/-/async-2.1.4.tgz
npm http request GET http://192.168.1.100:4873/lodash
npm http 200 http://192.168.1.100:4873/lodash
npm http fetch GET http://192.168.1.100:4873/lodash/-/lodash-4.17.4.tgz
npm http fetch 200 http://192.168.1.100:4873/lodash/-/lodash-4.17.4.tgz
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/bluebird
npm http 200 http://192.168.1.100:4873/is-my-json-valid
npm http 200 http://192.168.1.100:4873/chalk
npm http 200 http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http 200 http://192.168.1.100:4873/escape-string-regexp
npm http 200 http://192.168.1.100:4873/has-ansi
npm http 200 http://192.168.1.100:4873/ansi-styles
npm http 200 http://192.168.1.100:4873/supports-color
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 200 http://192.168.1.100:4873/ansi-regex
npm http fetch GET http://192.168.1.100:4873/ansi-regex/-/ansi-regex-2.1.1.tgz
npm http fetch 200 http://192.168.1.100:4873/ansi-regex/-/ansi-regex-2.1.1.tgz
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http 200 http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-function
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http 200 http://192.168.1.100:4873/jsonpointer
npm http fetch GET http://192.168.1.100:4873/jsonpointer/-/jsonpointer-4.0.1.tgz
npm http fetch 200 http://192.168.1.100:4873/jsonpointer/-/jsonpointer-4.0.1.tgz
npm http request GET http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/sntp
npm http 200 http://192.168.1.100:4873/cryptiles
npm http 200 http://192.168.1.100:4873/sntp
npm http 200 http://192.168.1.100:4873/boom
npm http 200 http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/ctype
npm http 200 http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/punycode
npm http 200 http://192.168.1.100:4873/punycode
npm http request GET http://192.168.1.100:4873/jsonschema
npm http 200 http://192.168.1.100:4873/jsonschema
npm http fetch GET http://192.168.1.100:4873/jsonschema/-/jsonschema-1.1.1.tgz
npm http fetch 200 http://192.168.1.100:4873/jsonschema/-/jsonschema-1.1.1.tgz
npm http request GET http://192.168.1.100:4873/colors
npm http request GET http://192.168.1.100:4873/cycle
npm http request GET http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/pkginfo
npm http request GET http://192.168.1.100:4873/stack-trace
npm http 304 http://192.168.1.100:4873/colors
npm http 304 http://192.168.1.100:4873/cycle
npm http 304 http://192.168.1.100:4873/eyes
npm http 304 http://192.168.1.100:4873/pkginfo
npm http 304 http://192.168.1.100:4873/stack-trace
npm http request GET http://192.168.1.100:4873/eslint
npm http request GET http://192.168.1.100:4873/jsdoc
npm http 200 http://192.168.1.100:4873/jsdoc
npm http 200 http://192.168.1.100:4873/eslint
npm http fetch GET http://192.168.1.100:4873/eslint/-/eslint-3.11.1.tgz
npm http fetch 200 http://192.168.1.100:4873/eslint/-/eslint-3.11.1.tgz
npm http request GET http://192.168.1.100:4873/babel-code-frame
npm http request GET http://192.168.1.100:4873/doctrine
npm http request GET http://192.168.1.100:4873/escope
npm http request GET http://192.168.1.100:4873/estraverse
npm http request GET http://192.168.1.100:4873/esutils
npm http request GET http://192.168.1.100:4873/file-entry-cache
npm http request GET http://192.168.1.100:4873/globals
npm http request GET http://192.168.1.100:4873/ignore
npm http request GET http://192.168.1.100:4873/is-resolvable
npm http request GET http://192.168.1.100:4873/js-yaml
npm http request GET http://192.168.1.100:4873/levn
npm http request GET http://192.168.1.100:4873/natural-compare
npm http request GET http://192.168.1.100:4873/optionator
npm http request GET http://192.168.1.100:4873/path-is-inside
npm http request GET http://192.168.1.100:4873/pluralize
npm http request GET http://192.168.1.100:4873/require-uncached
npm http request GET http://192.168.1.100:4873/strip-bom
npm http request GET http://192.168.1.100:4873/table
npm http request GET http://192.168.1.100:4873/text-table
npm http request GET http://192.168.1.100:4873/user-home
npm http request GET http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/imurmurhash
npm http request GET http://192.168.1.100:4873/espree
npm http request GET http://192.168.1.100:4873/json-stable-stringify
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/progress
npm http request GET http://192.168.1.100:4873/inquirer
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/shelljs
npm http 200 http://192.168.1.100:4873/doctrine
npm http 200 http://192.168.1.100:4873/escope
npm http 200 http://192.168.1.100:4873/babel-code-frame
npm http 200 http://192.168.1.100:4873/esutils
npm http 200 http://192.168.1.100:4873/estraverse
npm http fetch GET http://192.168.1.100:4873/doctrine/-/doctrine-1.5.0.tgz
npm http fetch GET http://192.168.1.100:4873/escope/-/escope-3.6.0.tgz
npm http 200 http://192.168.1.100:4873/file-entry-cache
npm http 200 http://192.168.1.100:4873/globals
npm http fetch GET http://192.168.1.100:4873/babel-code-frame/-/babel-code-frame-6.22.0.tgz
npm http 200 http://192.168.1.100:4873/ignore
npm http 200 http://192.168.1.100:4873/is-resolvable
npm http fetch GET http://192.168.1.100:4873/esutils/-/esutils-2.0.2.tgz
npm http fetch GET http://192.168.1.100:4873/estraverse/-/estraverse-4.2.0.tgz
npm http 200 http://192.168.1.100:4873/js-yaml
npm http 200 http://192.168.1.100:4873/levn
npm http fetch GET http://192.168.1.100:4873/globals/-/globals-9.14.0.tgz
npm http fetch GET http://192.168.1.100:4873/file-entry-cache/-/file-entry-cache-2.0.0.tgz
npm http 200 http://192.168.1.100:4873/natural-compare
npm http fetch GET http://192.168.1.100:4873/ignore/-/ignore-3.2.0.tgz
npm http 200 http://192.168.1.100:4873/optionator
npm http 200 http://192.168.1.100:4873/path-is-inside
npm http fetch GET http://192.168.1.100:4873/is-resolvable/-/is-resolvable-1.0.0.tgz
npm http 200 http://192.168.1.100:4873/pluralize
npm http 200 http://192.168.1.100:4873/require-uncached
npm http 200 http://192.168.1.100:4873/strip-bom
npm http fetch GET http://192.168.1.100:4873/levn/-/levn-0.3.0.tgz
npm http fetch GET http://192.168.1.100:4873/js-yaml/-/js-yaml-3.7.0.tgz
npm http 200 http://192.168.1.100:4873/table
npm http fetch GET http://192.168.1.100:4873/natural-compare/-/natural-compare-1.4.0.tgz
npm http 200 http://192.168.1.100:4873/user-home
npm http 200 http://192.168.1.100:4873/text-table
npm http 304 http://192.168.1.100:4873/glob
npm http fetch GET http://192.168.1.100:4873/optionator/-/optionator-0.8.2.tgz
npm http 200 http://192.168.1.100:4873/concat-stream
npm http 304 http://192.168.1.100:4873/imurmurhash
npm http fetch GET http://192.168.1.100:4873/path-is-inside/-/path-is-inside-1.0.2.tgz
npm http fetch GET http://192.168.1.100:4873/pluralize/-/pluralize-1.2.1.tgz
npm http fetch GET http://192.168.1.100:4873/require-uncached/-/require-uncached-1.0.3.tgz
npm http 304 http://192.168.1.100:4873/json-stable-stringify
npm http fetch GET http://192.168.1.100:4873/strip-bom/-/strip-bom-3.0.0.tgz
npm http 200 http://192.168.1.100:4873/mkdirp
npm http fetch GET http://192.168.1.100:4873/table/-/table-3.8.3.tgz
npm http fetch 200 http://192.168.1.100:4873/doctrine/-/doctrine-1.5.0.tgz
npm http fetch GET http://192.168.1.100:4873/user-home/-/user-home-2.0.0.tgz
npm http fetch GET http://192.168.1.100:4873/text-table/-/text-table-0.2.0.tgz
npm http fetch GET http://192.168.1.100:4873/concat-stream/-/concat-stream-1.6.0.tgz
npm http fetch 200 http://192.168.1.100:4873/escope/-/escope-3.6.0.tgz
npm http 200 http://192.168.1.100:4873/espree
npm http 200 http://192.168.1.100:4873/progress
npm http 200 http://192.168.1.100:4873/strip-json-comments
npm http fetch GET http://192.168.1.100:4873/json-stable-stringify/-/json-stable-stringify-1.0.1.tgz
npm http fetch 200 http://192.168.1.100:4873/esutils/-/esutils-2.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/estraverse/-/estraverse-4.2.0.tgz
npm http fetch 200 http://192.168.1.100:4873/globals/-/globals-9.14.0.tgz
npm http fetch 200 http://192.168.1.100:4873/file-entry-cache/-/file-entry-cache-2.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/ignore/-/ignore-3.2.0.tgz
npm http fetch 200 http://192.168.1.100:4873/is-resolvable/-/is-resolvable-1.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/levn/-/levn-0.3.0.tgz
npm http fetch 200 http://192.168.1.100:4873/js-yaml/-/js-yaml-3.7.0.tgz
npm http fetch 200 http://192.168.1.100:4873/path-is-inside/-/path-is-inside-1.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/natural-compare/-/natural-compare-1.4.0.tgz
npm http fetch 200 http://192.168.1.100:4873/optionator/-/optionator-0.8.2.tgz
npm http fetch 200 http://192.168.1.100:4873/babel-code-frame/-/babel-code-frame-6.22.0.tgz
npm http fetch 200 http://192.168.1.100:4873/pluralize/-/pluralize-1.2.1.tgz
npm http 200 http://192.168.1.100:4873/shelljs
npm http fetch GET http://192.168.1.100:4873/espree/-/espree-3.3.2.tgz
npm http fetch 200 http://192.168.1.100:4873/strip-bom/-/strip-bom-3.0.0.tgz
npm http 200 http://192.168.1.100:4873/inquirer
npm http fetch 200 http://192.168.1.100:4873/require-uncached/-/require-uncached-1.0.3.tgz
npm http fetch 200 http://192.168.1.100:4873/table/-/table-3.8.3.tgz
npm http fetch 200 http://192.168.1.100:4873/user-home/-/user-home-2.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/text-table/-/text-table-0.2.0.tgz
npm http fetch 200 http://192.168.1.100:4873/json-stable-stringify/-/json-stable-stringify-1.0.1.tgz
npm http fetch 200 http://192.168.1.100:4873/concat-stream/-/concat-stream-1.6.0.tgz
npm http fetch 200 http://192.168.1.100:4873/espree/-/espree-3.3.2.tgz
npm http fetch GET http://192.168.1.100:4873/shelljs/-/shelljs-0.7.6.tgz
npm http fetch GET http://192.168.1.100:4873/inquirer/-/inquirer-0.12.0.tgz
npm http fetch 200 http://192.168.1.100:4873/shelljs/-/shelljs-0.7.6.tgz
npm http fetch 200 http://192.168.1.100:4873/inquirer/-/inquirer-0.12.0.tgz
npm http request GET http://192.168.1.100:4873/js-tokens
npm http 200 http://192.168.1.100:4873/js-tokens
npm http fetch GET http://192.168.1.100:4873/js-tokens/-/js-tokens-3.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/js-tokens/-/js-tokens-3.0.0.tgz
npm http request GET http://192.168.1.100:4873/typedarray
npm http 304 http://192.168.1.100:4873/typedarray
npm http request GET http://192.168.1.100:4873/es6-map
npm http request GET http://192.168.1.100:4873/es6-weak-map
npm http request GET http://192.168.1.100:4873/esrecurse
npm http 200 http://192.168.1.100:4873/es6-map
npm http 200 http://192.168.1.100:4873/es6-weak-map
npm http 200 http://192.168.1.100:4873/esrecurse
npm http fetch GET http://192.168.1.100:4873/esrecurse/-/esrecurse-4.1.0.tgz
npm http fetch GET http://192.168.1.100:4873/es6-weak-map/-/es6-weak-map-2.0.1.tgz
npm http fetch GET http://192.168.1.100:4873/es6-map/-/es6-map-0.1.4.tgz
npm http fetch 200 http://192.168.1.100:4873/esrecurse/-/esrecurse-4.1.0.tgz
npm http fetch 200 http://192.168.1.100:4873/es6-map/-/es6-map-0.1.4.tgz
npm http fetch 200 http://192.168.1.100:4873/es6-weak-map/-/es6-weak-map-2.0.1.tgz
npm http request GET http://192.168.1.100:4873/es6-set
npm http request GET http://192.168.1.100:4873/event-emitter
npm http request GET http://192.168.1.100:4873/d
npm http request GET http://192.168.1.100:4873/es6-symbol
npm http request GET http://192.168.1.100:4873/es6-iterator
npm http request GET http://192.168.1.100:4873/es5-ext
npm http 200 http://192.168.1.100:4873/es6-set
npm http fetch GET http://192.168.1.100:4873/es6-set/-/es6-set-0.1.4.tgz
npm http 200 http://192.168.1.100:4873/d
npm http 200 http://192.168.1.100:4873/event-emitter
npm http fetch 200 http://192.168.1.100:4873/es6-set/-/es6-set-0.1.4.tgz
npm http 200 http://192.168.1.100:4873/es6-symbol
npm http 200 http://192.168.1.100:4873/es6-iterator
npm http fetch GET http://192.168.1.100:4873/event-emitter/-/event-emitter-0.3.4.tgz
npm http fetch 200 http://192.168.1.100:4873/event-emitter/-/event-emitter-0.3.4.tgz
npm http 200 http://192.168.1.100:4873/es5-ext
npm http fetch GET http://192.168.1.100:4873/estraverse/-/estraverse-4.1.1.tgz
npm http fetch 200 http://192.168.1.100:4873/estraverse/-/estraverse-4.1.1.tgz
npm http request GET http://192.168.1.100:4873/acorn-jsx
npm http request GET http://192.168.1.100:4873/acorn
npm http 200 http://192.168.1.100:4873/acorn-jsx
npm http fetch GET http://192.168.1.100:4873/acorn-jsx/-/acorn-jsx-3.0.1.tgz
npm http 200 http://192.168.1.100:4873/acorn
npm http fetch 200 http://192.168.1.100:4873/acorn-jsx/-/acorn-jsx-3.0.1.tgz
npm http fetch GET http://192.168.1.100:4873/acorn/-/acorn-4.0.4.tgz
npm http fetch 200 http://192.168.1.100:4873/acorn/-/acorn-4.0.4.tgz
npm http request GET http://192.168.1.100:4873/flat-cache
npm http 200 http://192.168.1.100:4873/flat-cache
npm http fetch GET http://192.168.1.100:4873/flat-cache/-/flat-cache-1.2.2.tgz
npm http fetch 200 http://192.168.1.100:4873/flat-cache/-/flat-cache-1.2.2.tgz
npm http request GET http://192.168.1.100:4873/circular-json
npm http request GET http://192.168.1.100:4873/del
npm http request GET http://192.168.1.100:4873/write
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http 200 http://192.168.1.100:4873/circular-json
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http 200 http://192.168.1.100:4873/write
npm http 200 http://192.168.1.100:4873/del
npm http fetch GET http://192.168.1.100:4873/circular-json/-/circular-json-0.3.1.tgz
npm http fetch GET http://192.168.1.100:4873/write/-/write-0.2.1.tgz
npm http fetch GET http://192.168.1.100:4873/del/-/del-2.2.2.tgz
npm http fetch 200 http://192.168.1.100:4873/circular-json/-/circular-json-0.3.1.tgz
npm http fetch 200 http://192.168.1.100:4873/write/-/write-0.2.1.tgz
npm http fetch 200 http://192.168.1.100:4873/del/-/del-2.2.2.tgz
npm http request GET http://192.168.1.100:4873/globby
npm http request GET http://192.168.1.100:4873/is-path-cwd
npm http request GET http://192.168.1.100:4873/is-path-in-cwd
npm http request GET http://192.168.1.100:4873/pify
npm http request GET http://192.168.1.100:4873/rimraf
npm http request GET http://192.168.1.100:4873/pinkie-promise
npm http 304 http://192.168.1.100:4873/rimraf
npm http 200 http://192.168.1.100:4873/is-path-in-cwd
npm http 200 http://192.168.1.100:4873/pify
npm http 200 http://192.168.1.100:4873/is-path-cwd
npm http 200 http://192.168.1.100:4873/globby
npm http 200 http://192.168.1.100:4873/pinkie-promise
npm http fetch GET http://192.168.1.100:4873/is-path-in-cwd/-/is-path-in-cwd-1.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/is-path-in-cwd/-/is-path-in-cwd-1.0.0.tgz
npm http fetch GET http://192.168.1.100:4873/pify/-/pify-2.3.0.tgz
npm http fetch GET http://192.168.1.100:4873/is-path-cwd/-/is-path-cwd-1.0.0.tgz
npm http fetch GET http://192.168.1.100:4873/globby/-/globby-5.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/pify/-/pify-2.3.0.tgz
npm http fetch 200 http://192.168.1.100:4873/is-path-cwd/-/is-path-cwd-1.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/globby/-/globby-5.0.0.tgz
npm http request GET http://192.168.1.100:4873/array-union
npm http request GET http://192.168.1.100:4873/arrify
npm http 200 http://192.168.1.100:4873/arrify
npm http 200 http://192.168.1.100:4873/array-union
npm http fetch GET http://192.168.1.100:4873/array-union/-/array-union-1.0.2.tgz
npm http fetch GET http://192.168.1.100:4873/arrify/-/arrify-1.0.1.tgz
npm http fetch 200 http://192.168.1.100:4873/array-union/-/array-union-1.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/arrify/-/arrify-1.0.1.tgz
npm http request GET http://192.168.1.100:4873/array-uniq
npm http 200 http://192.168.1.100:4873/array-uniq
npm http fetch GET http://192.168.1.100:4873/array-uniq/-/array-uniq-1.0.3.tgz
npm http fetch 200 http://192.168.1.100:4873/array-uniq/-/array-uniq-1.0.3.tgz
npm http request GET http://192.168.1.100:4873/fs.realpath
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/fs.realpath
npm http 304 http://192.168.1.100:4873/inflight
npm http 304 http://192.168.1.100:4873/minimatch
npm http 304 http://192.168.1.100:4873/path-is-absolute
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 304 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/pinkie
npm http 304 http://192.168.1.100:4873/pinkie
npm http request GET http://192.168.1.100:4873/is-path-inside
npm http 200 http://192.168.1.100:4873/is-path-inside
npm http fetch GET http://192.168.1.100:4873/is-path-inside/-/is-path-inside-1.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/is-path-inside/-/is-path-inside-1.0.0.tgz
npm http request GET http://192.168.1.100:4873/minimist
npm http 200 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/string-width
npm http request GET http://192.168.1.100:4873/cli-width
npm http request GET http://192.168.1.100:4873/figures
npm http request GET http://192.168.1.100:4873/run-async
npm http request GET http://192.168.1.100:4873/ansi-escapes
npm http request GET http://192.168.1.100:4873/cli-cursor
npm http request GET http://192.168.1.100:4873/readline2
npm http request GET http://192.168.1.100:4873/through
npm http request GET http://192.168.1.100:4873/rx-lite
npm http 200 http://192.168.1.100:4873/string-width
npm http fetch GET http://192.168.1.100:4873/string-width/-/string-width-1.0.2.tgz
npm http 304 http://192.168.1.100:4873/cli-width
npm http fetch GET http://192.168.1.100:4873/cli-width/-/cli-width-2.1.0.tgz
npm http 200 http://192.168.1.100:4873/ansi-escapes
npm http 200 http://192.168.1.100:4873/run-async
npm http 200 http://192.168.1.100:4873/figures
npm http fetch 200 http://192.168.1.100:4873/string-width/-/string-width-1.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/cli-width/-/cli-width-2.1.0.tgz
npm http 304 http://192.168.1.100:4873/readline2
npm http 200 http://192.168.1.100:4873/cli-cursor
npm http 304 http://192.168.1.100:4873/rx-lite
npm http 200 http://192.168.1.100:4873/through
npm http request GET http://192.168.1.100:4873/restore-cursor
npm http 200 http://192.168.1.100:4873/restore-cursor
npm http request GET http://192.168.1.100:4873/exit-hook
npm http request GET http://192.168.1.100:4873/onetime
npm http 304 http://192.168.1.100:4873/exit-hook
npm http 304 http://192.168.1.100:4873/onetime
npm http request GET http://192.168.1.100:4873/code-point-at
npm http request GET http://192.168.1.100:4873/is-fullwidth-code-point
npm http request GET http://192.168.1.100:4873/mute-stream
npm http 304 http://192.168.1.100:4873/code-point-at
npm http 304 http://192.168.1.100:4873/is-fullwidth-code-point
npm http 200 http://192.168.1.100:4873/mute-stream
npm http request GET http://192.168.1.100:4873/number-is-nan
npm http 304 http://192.168.1.100:4873/number-is-nan
npm http request GET http://192.168.1.100:4873/tryit
npm http 200 http://192.168.1.100:4873/tryit
npm http fetch GET http://192.168.1.100:4873/tryit/-/tryit-1.0.3.tgz
npm http fetch 200 http://192.168.1.100:4873/tryit/-/tryit-1.0.3.tgz
npm http request GET http://192.168.1.100:4873/argparse
npm http request GET http://192.168.1.100:4873/esprima
npm http 200 http://192.168.1.100:4873/argparse
npm http 200 http://192.168.1.100:4873/esprima
npm http fetch GET http://192.168.1.100:4873/argparse/-/argparse-1.0.9.tgz
npm http fetch 200 http://192.168.1.100:4873/argparse/-/argparse-1.0.9.tgz
npm http request GET http://192.168.1.100:4873/sprintf-js
npm http 200 http://192.168.1.100:4873/sprintf-js
npm http fetch GET http://192.168.1.100:4873/sprintf-js/-/sprintf-js-1.0.3.tgz
npm http fetch 200 http://192.168.1.100:4873/sprintf-js/-/sprintf-js-1.0.3.tgz
npm http request GET http://192.168.1.100:4873/jsonify
npm http 304 http://192.168.1.100:4873/jsonify
npm http request GET http://192.168.1.100:4873/prelude-ls
npm http request GET http://192.168.1.100:4873/type-check
npm http 200 http://192.168.1.100:4873/prelude-ls
npm http 200 http://192.168.1.100:4873/type-check
npm http fetch GET http://192.168.1.100:4873/prelude-ls/-/prelude-ls-1.1.2.tgz
npm http fetch 200 http://192.168.1.100:4873/prelude-ls/-/prelude-ls-1.1.2.tgz
npm http fetch GET http://192.168.1.100:4873/type-check/-/type-check-0.3.2.tgz
npm http fetch 200 http://192.168.1.100:4873/type-check/-/type-check-0.3.2.tgz
npm http request GET http://192.168.1.100:4873/deep-is
npm http request GET http://192.168.1.100:4873/wordwrap
npm http request GET http://192.168.1.100:4873/fast-levenshtein
npm http 200 http://192.168.1.100:4873/wordwrap
npm http 200 http://192.168.1.100:4873/deep-is
npm http 200 http://192.168.1.100:4873/fast-levenshtein
npm http fetch GET http://192.168.1.100:4873/fast-levenshtein/-/fast-levenshtein-2.0.6.tgz
npm http fetch GET http://192.168.1.100:4873/wordwrap/-/wordwrap-1.0.0.tgz
npm http fetch GET http://192.168.1.100:4873/deep-is/-/deep-is-0.1.3.tgz
npm http fetch 200 http://192.168.1.100:4873/fast-levenshtein/-/fast-levenshtein-2.0.6.tgz
npm http fetch 200 http://192.168.1.100:4873/wordwrap/-/wordwrap-1.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/deep-is/-/deep-is-0.1.3.tgz
npm http request GET http://192.168.1.100:4873/caller-path
npm http request GET http://192.168.1.100:4873/resolve-from
npm http 200 http://192.168.1.100:4873/resolve-from
npm http 200 http://192.168.1.100:4873/caller-path
npm http fetch GET http://192.168.1.100:4873/caller-path/-/caller-path-0.1.0.tgz
npm http fetch GET http://192.168.1.100:4873/resolve-from/-/resolve-from-1.0.1.tgz
npm http fetch 200 http://192.168.1.100:4873/resolve-from/-/resolve-from-1.0.1.tgz
npm http fetch 200 http://192.168.1.100:4873/caller-path/-/caller-path-0.1.0.tgz
npm http request GET http://192.168.1.100:4873/callsites
npm http 200 http://192.168.1.100:4873/callsites
npm http fetch GET http://192.168.1.100:4873/callsites/-/callsites-0.2.0.tgz
npm http fetch 200 http://192.168.1.100:4873/callsites/-/callsites-0.2.0.tgz
npm http request GET http://192.168.1.100:4873/interpret
npm http request GET http://192.168.1.100:4873/rechoir
npm http 200 http://192.168.1.100:4873/interpret
npm http 304 http://192.168.1.100:4873/rechoir
npm http request GET http://192.168.1.100:4873/resolve
npm http 200 http://192.168.1.100:4873/resolve
npm http fetch GET http://192.168.1.100:4873/resolve/-/resolve-1.2.0.tgz
npm http fetch 200 http://192.168.1.100:4873/resolve/-/resolve-1.2.0.tgz
npm http request GET http://192.168.1.100:4873/ajv
npm http request GET http://192.168.1.100:4873/ajv-keywords
npm http request GET http://192.168.1.100:4873/slice-ansi
npm http fetch GET http://192.168.1.100:4873/string-width/-/string-width-2.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/string-width/-/string-width-2.0.0.tgz
npm http 200 http://192.168.1.100:4873/slice-ansi
npm http 200 http://192.168.1.100:4873/ajv-keywords
npm http 200 http://192.168.1.100:4873/ajv
npm http fetch GET http://192.168.1.100:4873/slice-ansi/-/slice-ansi-0.0.4.tgz
npm http fetch GET http://192.168.1.100:4873/ajv-keywords/-/ajv-keywords-1.5.0.tgz
npm http fetch 200 http://192.168.1.100:4873/slice-ansi/-/slice-ansi-0.0.4.tgz
npm http fetch GET http://192.168.1.100:4873/ajv/-/ajv-4.10.4.tgz
npm http fetch 200 http://192.168.1.100:4873/ajv-keywords/-/ajv-keywords-1.5.0.tgz
npm http fetch 200 http://192.168.1.100:4873/ajv/-/ajv-4.10.4.tgz
npm http request GET http://192.168.1.100:4873/co
npm http 200 http://192.168.1.100:4873/co
npm http fetch GET http://192.168.1.100:4873/co/-/co-4.6.0.tgz
npm http fetch 200 http://192.168.1.100:4873/co/-/co-4.6.0.tgz
npm http fetch GET http://192.168.1.100:4873/is-fullwidth-code-point/-/is-fullwidth-code-point-2.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/is-fullwidth-code-point/-/is-fullwidth-code-point-2.0.0.tgz
npm http request GET http://192.168.1.100:4873/os-homedir
npm http 304 http://192.168.1.100:4873/os-homedir
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/catharsis
npm http request GET http://192.168.1.100:4873/wrench
npm http request GET http://192.168.1.100:4873/underscore
npm http request GET http://192.168.1.100:4873/js2xmlparser
npm http request GET http://192.168.1.100:4873/marked
npm http request GET http://192.168.1.100:4873/requizzle
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 304 http://192.168.1.100:4873/async
npm http 200 http://192.168.1.100:4873/catharsis
npm http 200 http://192.168.1.100:4873/underscore
npm http 200 http://192.168.1.100:4873/wrench
npm http 200 http://192.168.1.100:4873/js2xmlparser
npm WARN deprecated wrench@1.5.9: wrench.js is deprecated! You should check out fs-extra (https://github.com/jprichardson/node-fs-extra) for any operations you were using wrench for. Thanks for all the usage over the years.
npm http 200 http://192.168.1.100:4873/marked
npm http 200 http://192.168.1.100:4873/requizzle
npm http fetch 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http request GET http://192.168.1.100:4873/underscore-contrib
npm http 200 http://192.168.1.100:4873/underscore-contrib
npm WARN prefer global marked@0.3.6 should be installed with -g
npm WARN install@0.0.1 No repository field.
npm http request GET http://192.168.1.100:4873/stacky
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/child-process-promise
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/bn.js
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/leveldown-mobile
npm http request GET http://192.168.1.100:4873/express-pouchdb
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/pouchdb
npm http request GET http://192.168.1.100:4873/pouchdb-size
npm http request GET http://192.168.1.100:4873/proxyquire
npm http request GET http://192.168.1.100:4873/request-promise
npm http request GET http://192.168.1.100:4873/sinon
npm http request GET http://192.168.1.100:4873/nock
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/supertest
npm http request GET http://192.168.1.100:4873/supertest-as-promised
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/tmp
npm http request GET http://192.168.1.100:4873/tape-catch
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/uuid-validate
npm http request GET http://192.168.1.100:4873/tape
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/body-parser
npm http 200 http://192.168.1.100:4873/stacky
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/child-process-promise
npm http 304 http://192.168.1.100:4873/concat-map
npm http fetch GET http://192.168.1.100:4873/stacky/-/stacky-1.3.1.tgz
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/is-property
npm http 200 http://192.168.1.100:4873/js-extend
npm http 304 http://192.168.1.100:4873/minimist
npm http 200 http://192.168.1.100:4873/bn.js
npm http 200 http://192.168.1.100:4873/express-pouchdb
npm http 304 http://192.168.1.100:4873/multiplex
npm http 304 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/randomstring
npm http 304 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/leveldown-mobile
npm http 200 http://192.168.1.100:4873/pouchdb-size
npm http 200 http://192.168.1.100:4873/proxyquire
npm http 304 http://192.168.1.100:4873/socket.io-client
npm http fetch GET http://192.168.1.100:4873/express-pouchdb/-/express-pouchdb-1.0.6-thali.tgz
npm http 200 http://192.168.1.100:4873/pouchdb
npm http 200 http://192.168.1.100:4873/supertest
npm http 304 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/request-promise
npm http 304 http://192.168.1.100:4873/uuid
npm http 200 http://192.168.1.100:4873/supertest-as-promised
npm http fetch 200 http://192.168.1.100:4873/stacky/-/stacky-1.3.1.tgz
npm http fetch 200 http://192.168.1.100:4873/express-pouchdb/-/express-pouchdb-1.0.6-thali.tgz
npm http 200 http://192.168.1.100:4873/tape-catch
npm http 200 http://192.168.1.100:4873/tmp
npm http 200 http://192.168.1.100:4873/uuid-validate
npm http fetch GET http://192.168.1.100:4873/pouchdb/-/pouchdb-6.1.1.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb/-/pouchdb-6.1.1.tgz
npm http 200 http://192.168.1.100:4873/sinon
npm http 200 http://192.168.1.100:4873/tape
npm http 200 http://192.168.1.100:4873/nock
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/raw-body
npm http request GET http://192.168.1.100:4873/type-is
npm http 304 http://192.168.1.100:4873/bytes
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/statuses
npm http 304 http://192.168.1.100:4873/statuses
npm http request GET http://192.168.1.100:4873/ee-first
npm http 304 http://192.168.1.100:4873/ee-first
npm http request GET http://192.168.1.100:4873/unpipe
npm http 304 http://192.168.1.100:4873/unpipe
npm http request GET http://192.168.1.100:4873/media-typer
npm http request GET http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/media-typer
npm http 304 http://192.168.1.100:4873/mime-types
npm http request GET http://192.168.1.100:4873/mime-db
npm http 304 http://192.168.1.100:4873/mime-db
npm http request GET http://192.168.1.100:4873/accepts
npm http request GET http://192.168.1.100:4873/array-flatten
npm http request GET http://192.168.1.100:4873/content-disposition
npm http request GET http://192.168.1.100:4873/cookie
npm http request GET http://192.168.1.100:4873/cookie-signature
npm http request GET http://192.168.1.100:4873/escape-html
npm http request GET http://192.168.1.100:4873/etag
npm http request GET http://192.168.1.100:4873/finalhandler
npm http request GET http://192.168.1.100:4873/fresh
npm http request GET http://192.168.1.100:4873/merge-descriptors
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/parseurl
npm http request GET http://192.168.1.100:4873/path-to-regexp
npm http request GET http://192.168.1.100:4873/proxy-addr
npm http request GET http://192.168.1.100:4873/range-parser
npm http request GET http://192.168.1.100:4873/send
npm http request GET http://192.168.1.100:4873/serve-static
npm http request GET http://192.168.1.100:4873/utils-merge
npm http request GET http://192.168.1.100:4873/vary
npm http 304 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/vary
npm http 304 http://192.168.1.100:4873/serve-static
npm http 304 http://192.168.1.100:4873/utils-merge
npm http 304 http://192.168.1.100:4873/send
npm http request GET http://192.168.1.100:4873/negotiator
npm http 304 http://192.168.1.100:4873/negotiator
npm http request GET http://192.168.1.100:4873/forwarded
npm http request GET http://192.168.1.100:4873/ipaddr.js
npm http 304 http://192.168.1.100:4873/forwarded
npm http 304 http://192.168.1.100:4873/ipaddr.js
npm http request GET http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/mime
npm http 304 http://192.168.1.100:4873/destroy
npm http 304 http://192.168.1.100:4873/mime
npm http request GET http://192.168.1.100:4873/basic-auth
npm http request GET http://192.168.1.100:4873/compression
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/cookie-parser
npm http request GET http://192.168.1.100:4873/header-case-normalizer
npm http request GET http://192.168.1.100:4873/multiparty
npm http request GET http://192.168.1.100:4873/pouchdb-all-dbs
npm http request GET http://192.168.1.100:4873/pouchdb-auth
npm http request GET http://192.168.1.100:4873/pouchdb-find
npm http request GET http://192.168.1.100:4873/pouchdb-list
npm http request GET http://192.168.1.100:4873/pouchdb-replicator
npm http request GET http://192.168.1.100:4873/pouchdb-security
npm http request GET http://192.168.1.100:4873/pouchdb-validation
npm http request GET http://192.168.1.100:4873/pouchdb-vhost
npm http request GET http://192.168.1.100:4873/pouchdb-rewrite
npm http request GET http://192.168.1.100:4873/pouchdb-wrappers
npm http request GET http://192.168.1.100:4873/pouchdb-show
npm http request GET http://192.168.1.100:4873/pouchdb-update
npm http 200 http://192.168.1.100:4873/basic-auth
npm http 304 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/header-case-normalizer
npm http 200 http://192.168.1.100:4873/compression
npm http 200 http://192.168.1.100:4873/cookie-parser
npm http 200 http://192.168.1.100:4873/multiparty
npm http 200 http://192.168.1.100:4873/pouchdb-all-dbs
npm http 200 http://192.168.1.100:4873/pouchdb-list
npm http 200 http://192.168.1.100:4873/pouchdb-auth
npm http 200 http://192.168.1.100:4873/pouchdb-find
npm http 200 http://192.168.1.100:4873/pouchdb-replicator
npm http 200 http://192.168.1.100:4873/pouchdb-security
npm http 200 http://192.168.1.100:4873/pouchdb-rewrite
npm http 200 http://192.168.1.100:4873/pouchdb-vhost
npm http 200 http://192.168.1.100:4873/pouchdb-validation
npm http 200 http://192.168.1.100:4873/pouchdb-wrappers
npm http 200 http://192.168.1.100:4873/pouchdb-show
npm http 200 http://192.168.1.100:4873/pouchdb-update
npm http request GET http://192.168.1.100:4873/setprototypeof
npm http 304 http://192.168.1.100:4873/setprototypeof
npm http request GET http://192.168.1.100:4873/on-headers
npm http request GET http://192.168.1.100:4873/compressible
npm http 304 http://192.168.1.100:4873/on-headers
npm http 200 http://192.168.1.100:4873/compressible
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/stream-counter
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 200 http://192.168.1.100:4873/stream-counter
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/argsarray
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/tiny-queue
npm http 304 http://192.168.1.100:4873/es3ify
npm http 304 http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/argsarray
npm http 200 http://192.168.1.100:4873/tiny-queue
npm http request GET http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/base62
npm http 304 http://192.168.1.100:4873/base62
npm http 304 http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http request GET http://192.168.1.100:4873/crypto-lite
npm http request GET http://192.168.1.100:4873/pouchdb-system-db
npm http request GET http://192.168.1.100:4873/pouchdb-req-http-query
npm http request GET http://192.168.1.100:4873/secure-random
npm http request GET http://192.168.1.100:4873/base64url
npm http request GET http://192.168.1.100:4873/couchdb-calculate-session-id
npm http request GET http://192.168.1.100:4873/pouchdb-plugin-error
npm http request GET http://192.168.1.100:4873/promise-nodify
npm http 200 http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http 200 http://192.168.1.100:4873/pouchdb-system-db
npm http 200 http://192.168.1.100:4873/secure-random
npm http 200 http://192.168.1.100:4873/crypto-lite
npm http 200 http://192.168.1.100:4873/pouchdb-req-http-query
npm http 200 http://192.168.1.100:4873/base64url
npm http 200 http://192.168.1.100:4873/couchdb-calculate-session-id
npm http 200 http://192.168.1.100:4873/promise-nodify
npm http 200 http://192.168.1.100:4873/pouchdb-plugin-error
npm http request GET http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/meow
npm http 304 http://192.168.1.100:4873/concat-stream
npm http 200 http://192.168.1.100:4873/meow
npm http request GET http://192.168.1.100:4873/typedarray
npm http 304 http://192.168.1.100:4873/typedarray
npm http request GET http://192.168.1.100:4873/camelcase-keys
npm http request GET http://192.168.1.100:4873/indent-string
npm http 200 http://192.168.1.100:4873/camelcase-keys
npm http 200 http://192.168.1.100:4873/indent-string
npm http request GET http://192.168.1.100:4873/map-obj
npm http request GET http://192.168.1.100:4873/camelcase
npm http 200 http://192.168.1.100:4873/map-obj
npm http 200 http://192.168.1.100:4873/camelcase
npm http request GET http://192.168.1.100:4873/get-stdin
npm http request GET http://192.168.1.100:4873/repeating
npm http 304 http://192.168.1.100:4873/repeating
npm http 200 http://192.168.1.100:4873/get-stdin
npm http request GET http://192.168.1.100:4873/is-finite
npm http 304 http://192.168.1.100:4873/is-finite
npm http request GET http://192.168.1.100:4873/number-is-nan
npm http 304 http://192.168.1.100:4873/number-is-nan
npm http request GET http://192.168.1.100:4873/aproba
npm http 200 http://192.168.1.100:4873/aproba
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/es6-promise-pool
npm http request GET http://192.168.1.100:4873/fruitdown
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/memdown
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/pouchdb-collate
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/vuvuzela
npm http request GET http://192.168.1.100:4873/level-write-stream
npm http request GET http://192.168.1.100:4873/localstorage-down
npm http request GET http://192.168.1.100:4873/scope-eval
npm http 304 http://192.168.1.100:4873/double-ended-queue
npm http 304 http://192.168.1.100:4873/levelup
npm http 200 http://192.168.1.100:4873/fruitdown
npm http 200 http://192.168.1.100:4873/es6-promise-pool
npm http 200 http://192.168.1.100:4873/memdown
npm http 304 http://192.168.1.100:4873/pouchdb-collections
npm http 304 http://192.168.1.100:4873/sublevel-pouchdb
npm http 304 http://192.168.1.100:4873/spark-md5
npm http 304 http://192.168.1.100:4873/through2
npm http 200 http://192.168.1.100:4873/pouchdb-collate
npm http 304 http://192.168.1.100:4873/js-extend
npm http 304 http://192.168.1.100:4873/vuvuzela
npm http 200 http://192.168.1.100:4873/level-write-stream
npm http 200 http://192.168.1.100:4873/scope-eval
npm http 200 http://192.168.1.100:4873/localstorage-down
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/d64
npm http 304 http://192.168.1.100:4873/abstract-leveldown
npm http 200 http://192.168.1.100:4873/d64
npm http request GET http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/end-stream
npm http 200 http://192.168.1.100:4873/end-stream
npm http request GET http://192.168.1.100:4873/write-stream
npm http 200 http://192.168.1.100:4873/write-stream
npm http request GET http://192.168.1.100:4873/deferred-leveldown
npm http request GET http://192.168.1.100:4873/level-codec
npm http request GET http://192.168.1.100:4873/level-errors
npm http request GET http://192.168.1.100:4873/level-iterator-stream
npm http request GET http://192.168.1.100:4873/prr
npm http request GET http://192.168.1.100:4873/semver
npm http 304 http://192.168.1.100:4873/deferred-leveldown
npm http 304 http://192.168.1.100:4873/level-codec
npm http 304 http://192.168.1.100:4873/level-errors
npm http 304 http://192.168.1.100:4873/level-iterator-stream
npm http 304 http://192.168.1.100:4873/prr
npm http 304 http://192.168.1.100:4873/semver
npm http request GET http://192.168.1.100:4873/errno
npm http 304 http://192.168.1.100:4873/errno
npm http request GET http://192.168.1.100:4873/humble-localstorage
npm http 200 http://192.168.1.100:4873/humble-localstorage
npm http request GET http://192.168.1.100:4873/has-localstorage
npm http request GET http://192.168.1.100:4873/localstorage-memory
npm http 200 http://192.168.1.100:4873/localstorage-memory
npm http 200 http://192.168.1.100:4873/has-localstorage
npm http request GET http://192.168.1.100:4873/ltgt
npm http request GET http://192.168.1.100:4873/functional-red-black-tree
npm http 304 http://192.168.1.100:4873/ltgt
npm http 200 http://192.168.1.100:4873/functional-red-black-tree
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/aws4
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/is-typedarray
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/aws4
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/is-typedarray
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/tough-cookie
npm WARN deprecated tough-cookie@2.2.2: ReDoS vulnerability parsing Set-Cookie https://nodesecurity.io/advisories/130
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 304 http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/process-nextick-args
npm http 304 http://192.168.1.100:4873/util-deprecate
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/pinkie-promise
npm http 304 http://192.168.1.100:4873/is-my-json-valid
npm http 304 http://192.168.1.100:4873/pinkie-promise
npm http 304 http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/ansi-styles
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http 304 http://192.168.1.100:4873/supports-color
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-function
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http request GET http://192.168.1.100:4873/pinkie
npm http 304 http://192.168.1.100:4873/pinkie
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/hoek
npm http 304 http://192.168.1.100:4873/boom
npm http 304 http://192.168.1.100:4873/cryptiles
npm http 304 http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/jsprim
npm http request GET http://192.168.1.100:4873/sshpk
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 304 http://192.168.1.100:4873/jsprim
npm http 304 http://192.168.1.100:4873/sshpk
npm http request GET http://192.168.1.100:4873/extsprintf
npm http request GET http://192.168.1.100:4873/json-schema
npm http request GET http://192.168.1.100:4873/verror
npm http 304 http://192.168.1.100:4873/extsprintf
npm http 304 http://192.168.1.100:4873/json-schema
npm http 304 http://192.168.1.100:4873/verror
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/dashdash
npm http request GET http://192.168.1.100:4873/getpass
npm http 304 http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/getpass
npm http 304 http://192.168.1.100:4873/dashdash
npm http request GET http://192.168.1.100:4873/pull-stream
npm http 200 http://192.168.1.100:4873/pull-stream
npm http request GET http://192.168.1.100:4873/pull-core
npm http 200 http://192.168.1.100:4873/pull-core
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/lie
npm http 304 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/xmlhttprequest-cookie
npm http 200 http://192.168.1.100:4873/xmlhttprequest-cookie
npm http request GET http://192.168.1.100:4873/xmlhttprequest
npm http 200 http://192.168.1.100:4873/xmlhttprequest
npm http request GET http://192.168.1.100:4873/pouchdb-changeslike-wrapper
npm http 200 http://192.168.1.100:4873/pouchdb-changeslike-wrapper
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/random-uuid-v4
npm http request GET http://192.168.1.100:4873/couchdb-eval
npm http request GET http://192.168.1.100:4873/couchdb-objects
npm http 200 http://192.168.1.100:4873/random-uuid-v4
npm http 200 http://192.168.1.100:4873/couchdb-eval
npm http 200 http://192.168.1.100:4873/couchdb-objects
npm http request GET http://192.168.1.100:4873/is-empty
npm http 200 http://192.168.1.100:4873/is-empty
npm http request GET http://192.168.1.100:4873/is-array
npm http request GET http://192.168.1.100:4873/pouchdb-extend
npm http request GET http://192.168.1.100:4873/pouchdb-upsert
npm http 200 http://192.168.1.100:4873/pouchdb-extend
npm http 200 http://192.168.1.100:4873/is-array
npm http 200 http://192.168.1.100:4873/pouchdb-upsert
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 304 http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/recast
npm http request GET http://192.168.1.100:4873/ast-types
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/ast-types
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/couchdb-render
npm http 304 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/couchdb-render
npm http request GET http://192.168.1.100:4873/couchdb-resp-completer
npm http 200 http://192.168.1.100:4873/couchdb-resp-completer
npm http request GET http://192.168.1.100:4873/equals
npm http 200 http://192.168.1.100:4873/equals
npm http request GET http://192.168.1.100:4873/jkroso-type
npm http 200 http://192.168.1.100:4873/jkroso-type
npm http request GET http://192.168.1.100:4873/pouchdb-route
npm http 200 http://192.168.1.100:4873/pouchdb-route
npm http request GET http://192.168.1.100:4873/get-folder-size
npm http 200 http://192.168.1.100:4873/get-folder-size
npm http request GET http://192.168.1.100:4873/minimist
npm http 304 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/fast-future
npm http 304 http://192.168.1.100:4873/abstract-leveldown
npm http 200 http://192.168.1.100:4873/fast-future
npm http 200 http://192.168.1.100:4873/bindings
npm http fetch GET http://192.168.1.100:4873/fast-future/-/fast-future-1.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/fast-future/-/fast-future-1.0.2.tgz
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/duplexify
npm http 304 http://192.168.1.100:4873/varint
npm http 304 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/stream-shift
npm http 304 http://192.168.1.100:4873/end-of-stream
npm http 304 http://192.168.1.100:4873/stream-shift
npm http request GET http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http 304 http://192.168.1.100:4873/buffer-shims
npm WARN deprecated lodash@2.4.1: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/chai
npm http request GET http://192.168.1.100:4873/propagate
npm http request GET http://192.168.1.100:4873/deep-equal
npm http 304 http://192.168.1.100:4873/debug
npm http 200 http://192.168.1.100:4873/propagate
npm http 200 http://192.168.1.100:4873/deep-equal
npm http 200 http://192.168.1.100:4873/chai
npm http request GET http://192.168.1.100:4873/assertion-error
npm http request GET http://192.168.1.100:4873/deep-eql
npm http request GET http://192.168.1.100:4873/type-detect
npm http 200 http://192.168.1.100:4873/assertion-error
npm http 200 http://192.168.1.100:4873/deep-eql
npm http 200 http://192.168.1.100:4873/type-detect
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/ip
npm http 304 http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/buffer-from
npm http request GET http://192.168.1.100:4873/clone-buffer
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/level-codec
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/ltgt
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/leveldown
npm http 304 http://192.168.1.100:4873/buffer-from
npm http 304 http://192.168.1.100:4873/clone-buffer
npm http 304 http://192.168.1.100:4873/double-ended-queue
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/level-codec
npm http 304 http://192.168.1.100:4873/levelup
npm http 304 http://192.168.1.100:4873/ltgt
npm http 304 http://192.168.1.100:4873/spark-md5
npm http 304 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/leveldown
npm http fetch GET http://192.168.1.100:4873/leveldown/-/leveldown-1.5.0.tgz
npm http fetch 200 http://192.168.1.100:4873/leveldown/-/leveldown-1.5.0.tgz
npm http request GET http://192.168.1.100:4873/is-array-buffer-x
npm http 304 http://192.168.1.100:4873/is-array-buffer-x
npm http request GET http://192.168.1.100:4873/to-string-tag-x
npm http request GET http://192.168.1.100:4873/is-object-like-x
npm http request GET http://192.168.1.100:4873/has-to-string-tag-x
npm http 304 http://192.168.1.100:4873/has-to-string-tag-x
npm http 304 http://192.168.1.100:4873/is-object-like-x
npm http 304 http://192.168.1.100:4873/to-string-tag-x
npm http request GET http://192.168.1.100:4873/has-symbol-support-x
npm http 304 http://192.168.1.100:4873/has-symbol-support-x
npm http request GET http://192.168.1.100:4873/is-function-x
npm http request GET http://192.168.1.100:4873/is-primitive
npm http 304 http://192.168.1.100:4873/is-function-x
npm http 304 http://192.168.1.100:4873/is-primitive
npm http request GET http://192.168.1.100:4873/lodash.isnull
npm http request GET http://192.168.1.100:4873/validate.io-undefined
npm http 304 http://192.168.1.100:4873/lodash.isnull
npm http 304 http://192.168.1.100:4873/validate.io-undefined
npm http request GET http://192.168.1.100:4873/nan
npm http request GET http://192.168.1.100:4873/prebuild
npm http 200 http://192.168.1.100:4873/nan
npm http 200 http://192.168.1.100:4873/prebuild
npm http fetch GET http://192.168.1.100:4873/prebuild/-/prebuild-4.5.0.tgz
npm http fetch 200 http://192.168.1.100:4873/prebuild/-/prebuild-4.5.0.tgz
npm http request GET http://192.168.1.100:4873/execspawn
npm http request GET http://192.168.1.100:4873/ghreleases
npm http request GET http://192.168.1.100:4873/expand-template
npm http request GET http://192.168.1.100:4873/github-from-package
npm http request GET http://192.168.1.100:4873/node-ninja
npm http request GET http://192.168.1.100:4873/os-homedir
npm http request GET http://192.168.1.100:4873/noop-logger
npm http request GET http://192.168.1.100:4873/npmlog
npm http request GET http://192.168.1.100:4873/node-gyp
npm http request GET http://192.168.1.100:4873/pump
npm http request GET http://192.168.1.100:4873/rc
npm http request GET http://192.168.1.100:4873/simple-get
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/tar-fs
npm http request GET http://192.168.1.100:4873/tar-stream
npm http 200 http://192.168.1.100:4873/execspawn
npm http 200 http://192.168.1.100:4873/ghreleases
npm http 200 http://192.168.1.100:4873/github-from-package
npm http 200 http://192.168.1.100:4873/expand-template
npm http 200 http://192.168.1.100:4873/node-ninja
npm http fetch GET http://192.168.1.100:4873/execspawn/-/execspawn-1.0.1.tgz
npm http fetch GET http://192.168.1.100:4873/expand-template/-/expand-template-1.0.3.tgz
npm http 304 http://192.168.1.100:4873/os-homedir
npm http 200 http://192.168.1.100:4873/noop-logger
npm http 200 http://192.168.1.100:4873/npmlog
npm http 200 http://192.168.1.100:4873/pump
npm http 200 http://192.168.1.100:4873/node-gyp
npm http fetch GET http://192.168.1.100:4873/pump/-/pump-1.0.2.tgz
npm http 200 http://192.168.1.100:4873/rc
npm http 200 http://192.168.1.100:4873/simple-get
npm http fetch 200 http://192.168.1.100:4873/expand-template/-/expand-template-1.0.3.tgz
npm http fetch 200 http://192.168.1.100:4873/execspawn/-/execspawn-1.0.1.tgz
npm http 304 http://192.168.1.100:4873/async
npm http fetch 200 http://192.168.1.100:4873/pump/-/pump-1.0.2.tgz
npm http 200 http://192.168.1.100:4873/tar-fs
npm http fetch GET http://192.168.1.100:4873/node-gyp/-/node-gyp-3.5.0.tgz
npm http 200 http://192.168.1.100:4873/tar-stream
npm http fetch 200 http://192.168.1.100:4873/node-gyp/-/node-gyp-3.5.0.tgz
npm http fetch GET http://192.168.1.100:4873/tar-fs/-/tar-fs-1.15.0.tgz
npm http fetch 200 http://192.168.1.100:4873/tar-fs/-/tar-fs-1.15.0.tgz
npm http request GET http://192.168.1.100:4873/util-extend
npm http 200 http://192.168.1.100:4873/util-extend
npm http fetch GET http://192.168.1.100:4873/util-extend/-/util-extend-1.0.3.tgz
npm http fetch 200 http://192.168.1.100:4873/util-extend/-/util-extend-1.0.3.tgz
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/ghutils
npm http request GET http://192.168.1.100:4873/url-template
npm http request GET http://192.168.1.100:4873/simple-mime
npm http request GET http://192.168.1.100:4873/ghrepos
npm http 304 http://192.168.1.100:4873/after
npm http 200 http://192.168.1.100:4873/ghutils
npm http 200 http://192.168.1.100:4873/url-template
npm http 200 http://192.168.1.100:4873/simple-mime
npm http 200 http://192.168.1.100:4873/ghrepos
npm http fetch GET http://192.168.1.100:4873/after/-/after-0.8.2.tgz
npm http fetch GET http://192.168.1.100:4873/ghutils/-/ghutils-3.2.1.tgz
npm http fetch 200 http://192.168.1.100:4873/after/-/after-0.8.2.tgz
npm http fetch 200 http://192.168.1.100:4873/ghutils/-/ghutils-3.2.1.tgz
npm http request GET http://192.168.1.100:4873/jsonist
npm http 200 http://192.168.1.100:4873/jsonist
npm http fetch GET http://192.168.1.100:4873/jsonist/-/jsonist-1.3.0.tgz
npm http fetch 200 http://192.168.1.100:4873/jsonist/-/jsonist-1.3.0.tgz
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/hyperquest
npm http 304 http://192.168.1.100:4873/bl
npm http 200 http://192.168.1.100:4873/hyperquest
npm http request GET http://192.168.1.100:4873/duplexer2
npm http 304 http://192.168.1.100:4873/duplexer2
npm http request GET http://192.168.1.100:4873/fstream
npm http request GET http://192.168.1.100:4873/osenv
npm http request GET http://192.168.1.100:4873/nopt
npm http request GET http://192.168.1.100:4873/tar
npm http request GET http://192.168.1.100:4873/which
npm http 304 http://192.168.1.100:4873/fstream
npm http 200 http://192.168.1.100:4873/osenv
npm http 304 http://192.168.1.100:4873/tar
npm http 200 http://192.168.1.100:4873/nopt
npm http 200 http://192.168.1.100:4873/which
npm http fetch GET http://192.168.1.100:4873/osenv/-/osenv-0.1.4.tgz
npm http fetch 200 http://192.168.1.100:4873/osenv/-/osenv-0.1.4.tgz
npm http fetch GET http://192.168.1.100:4873/which/-/which-1.2.12.tgz
npm http fetch 200 http://192.168.1.100:4873/which/-/which-1.2.12.tgz
npm http request GET http://192.168.1.100:4873/abbrev
npm http 304 http://192.168.1.100:4873/abbrev
npm http request GET http://192.168.1.100:4873/ansi
npm http request GET http://192.168.1.100:4873/are-we-there-yet
npm http request GET http://192.168.1.100:4873/gauge
npm http 304 http://192.168.1.100:4873/ansi
npm http 200 http://192.168.1.100:4873/are-we-there-yet
npm http 200 http://192.168.1.100:4873/gauge
npm http request GET http://192.168.1.100:4873/delegates
npm http 200 http://192.168.1.100:4873/delegates
npm http request GET http://192.168.1.100:4873/lodash.padend
npm http request GET http://192.168.1.100:4873/has-unicode
npm http request GET http://192.168.1.100:4873/lodash.padstart
npm http request GET http://192.168.1.100:4873/lodash.pad
npm http 200 http://192.168.1.100:4873/has-unicode
npm http 200 http://192.168.1.100:4873/lodash.padend
npm http 200 http://192.168.1.100:4873/lodash.padstart
npm http 200 http://192.168.1.100:4873/lodash.pad
npm http fetch GET http://192.168.1.100:4873/lodash.padend/-/lodash.padend-4.6.1.tgz
npm http fetch GET http://192.168.1.100:4873/lodash.padstart/-/lodash.padstart-4.6.1.tgz
npm http fetch GET http://192.168.1.100:4873/lodash.pad/-/lodash.pad-4.5.1.tgz
npm http fetch 200 http://192.168.1.100:4873/lodash.padend/-/lodash.padend-4.6.1.tgz
npm http fetch 200 http://192.168.1.100:4873/lodash.padstart/-/lodash.padstart-4.6.1.tgz
npm http fetch 200 http://192.168.1.100:4873/lodash.pad/-/lodash.pad-4.5.1.tgz
npm http request GET http://192.168.1.100:4873/os-tmpdir
npm http 304 http://192.168.1.100:4873/os-tmpdir
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/block-stream
npm http 304 http://192.168.1.100:4873/block-stream
npm http request GET http://192.168.1.100:4873/isexe
npm http 200 http://192.168.1.100:4873/isexe
npm http request GET http://192.168.1.100:4873/path-array
npm http 200 http://192.168.1.100:4873/path-array
npm http request GET http://192.168.1.100:4873/array-index
npm http 200 http://192.168.1.100:4873/array-index
npm http request GET http://192.168.1.100:4873/es6-symbol
npm http 304 http://192.168.1.100:4873/es6-symbol
npm http request GET http://192.168.1.100:4873/d
npm http request GET http://192.168.1.100:4873/es5-ext
npm http 304 http://192.168.1.100:4873/d
npm http 304 http://192.168.1.100:4873/es5-ext
npm http request GET http://192.168.1.100:4873/es6-iterator
npm http 304 http://192.168.1.100:4873/es6-iterator
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http 304 http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/ini
npm http request GET http://192.168.1.100:4873/deep-extend
npm http 304 http://192.168.1.100:4873/ini
npm http 304 http://192.168.1.100:4873/strip-json-comments
npm http 200 http://192.168.1.100:4873/deep-extend
npm http request GET http://192.168.1.100:4873/unzip-response
npm http 200 http://192.168.1.100:4873/unzip-response
npm http fetch GET http://192.168.1.100:4873/unzip-response/-/unzip-response-1.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/unzip-response/-/unzip-response-1.0.2.tgz
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/uuid
npm http 304 http://192.168.1.100:4873/uuid
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/form-data
npm http fetch GET http://192.168.1.100:4873/uuid/-/uuid-3.0.1.tgz
npm http fetch 200 http://192.168.1.100:4873/uuid/-/uuid-3.0.1.tgz
npm http request GET http://192.168.1.100:4873/asynckit
npm http 304 http://192.168.1.100:4873/asynckit
npm http request GET http://192.168.1.100:4873/punycode
npm http 304 http://192.168.1.100:4873/punycode
npm http request GET http://192.168.1.100:4873/fill-keys
npm http request GET http://192.168.1.100:4873/module-not-found-error
npm http 200 http://192.168.1.100:4873/module-not-found-error
npm http 200 http://192.168.1.100:4873/fill-keys
npm http request GET http://192.168.1.100:4873/is-object
npm http 200 http://192.168.1.100:4873/is-object
npm http request GET http://192.168.1.100:4873/array-uniq
npm http 304 http://192.168.1.100:4873/array-uniq
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/jsonschema
npm http 304 http://192.168.1.100:4873/jsonschema
npm http request GET http://192.168.1.100:4873/samsam
npm http request GET http://192.168.1.100:4873/util
npm http request GET http://192.168.1.100:4873/formatio
npm http request GET http://192.168.1.100:4873/lolex
npm http 200 http://192.168.1.100:4873/samsam
npm http 304 http://192.168.1.100:4873/util
npm http 200 http://192.168.1.100:4873/formatio
npm http 200 http://192.168.1.100:4873/lolex
npm http request GET http://192.168.1.100:4873/engine.io-client
npm http request GET http://192.168.1.100:4873/component-bind
npm http request GET http://192.168.1.100:4873/component-emitter
npm http request GET http://192.168.1.100:4873/object-component
npm http request GET http://192.168.1.100:4873/socket.io-parser
npm http request GET http://192.168.1.100:4873/has-binary
npm http request GET http://192.168.1.100:4873/indexof
npm http request GET http://192.168.1.100:4873/parseuri
npm http request GET http://192.168.1.100:4873/to-array
npm http request GET http://192.168.1.100:4873/backo2
npm http 304 http://192.168.1.100:4873/component-bind
npm http 304 http://192.168.1.100:4873/engine.io-client
npm http 304 http://192.168.1.100:4873/component-emitter
npm http 304 http://192.168.1.100:4873/socket.io-parser
npm http 304 http://192.168.1.100:4873/object-component
npm http 304 http://192.168.1.100:4873/has-binary
npm http 304 http://192.168.1.100:4873/indexof
npm http 304 http://192.168.1.100:4873/parseuri
npm http 304 http://192.168.1.100:4873/to-array
npm http 304 http://192.168.1.100:4873/backo2
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/ws
npm http request GET http://192.168.1.100:4873/xmlhttprequest-ssl
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/parseqs
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/yeast
npm http 304 http://192.168.1.100:4873/has-cors
npm http 304 http://192.168.1.100:4873/ws
npm http 304 http://192.168.1.100:4873/xmlhttprequest-ssl
npm http 304 http://192.168.1.100:4873/parsejson
npm http 304 http://192.168.1.100:4873/engine.io-parser
npm http 304 http://192.168.1.100:4873/parseqs
npm http 304 http://192.168.1.100:4873/component-inherit
npm http 304 http://192.168.1.100:4873/yeast
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/utf8
npm http 304 http://192.168.1.100:4873/arraybuffer.slice
npm http 304 http://192.168.1.100:4873/blob
npm http 304 http://192.168.1.100:4873/utf8
npm http 304 http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/better-assert
npm http 304 http://192.168.1.100:4873/better-assert
npm http request GET http://192.168.1.100:4873/callsite
npm http 304 http://192.168.1.100:4873/callsite
npm http request GET http://192.168.1.100:4873/options
npm http request GET http://192.168.1.100:4873/ultron
npm http 304 http://192.168.1.100:4873/options
npm http 304 http://192.168.1.100:4873/ultron
npm http request GET http://192.168.1.100:4873/json3
npm http request GET http://192.168.1.100:4873/benchmark
npm http 304 http://192.168.1.100:4873/json3
npm http 304 http://192.168.1.100:4873/benchmark
npm http request GET http://192.168.1.100:4873/superagent
npm http 200 http://192.168.1.100:4873/superagent
npm http request GET http://192.168.1.100:4873/reduce-component
npm http request GET http://192.168.1.100:4873/cookiejar
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/formidable
npm http 304 http://192.168.1.100:4873/methods
npm http 200 http://192.168.1.100:4873/reduce-component
npm http 200 http://192.168.1.100:4873/cookiejar
npm http 200 http://192.168.1.100:4873/formidable
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/mime-types
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/mime-db
npm http 304 http://192.168.1.100:4873/mime-db
npm http request GET http://192.168.1.100:4873/defined
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/resumer
npm http request GET http://192.168.1.100:4873/object-inspect
npm http 304 http://192.168.1.100:4873/defined
npm http 304 http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/resumer
npm http 200 http://192.168.1.100:4873/object-inspect
npm WARN prefer global node-ninja@1.0.2 should be installed with -g
npm WARN prefer global node-gyp@3.5.0 should be installed with -g
gyp JXcore NODE-GYP Using node-gyp bundled in npm coming from JXcore
gyp http GET https://jxcore.azureedge.net/jxb311.tar.gz
gyp http 200 https://jxcore.azureedge.net/jxb311.tar.gz
In file included from ../src/batch.cc:2:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
1 warning generated.
In file included from ../src/batch_async.cc:8:
In file included from ../src/batch.h:9:
In file included from ../src/database.h:16:
In file included from ../../nan/nan.h:48:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
1 warning generated.
In file included from ../src/database.cc:7:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
1 warning generated.
In file included from ../src/database_async.cc:7:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
1 warning generated.
In file included from ../src/iterator.cc:7:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
1 warning generated.
In file included from ../src/iterator_async.cc:7:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
1 warning generated.
In file included from ../src/leveldown.cc:8:
In file included from ../src/leveldown.h:9:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
1 warning generated.
In file included from ../src/leveldown_async.cc:8:
In file included from ../src/leveldown.h:9:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
1 warning generated.
gyp JXcore NODE-GYP Using node-gyp bundled in npm coming from JXcore
In file included from ../src/batch.cc:4:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:7:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:17:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:7:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:7:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:8:
In file included from ../src/batch_async.h:15:
../src/batch.h:20:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Batch, Batch) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
../src/batch.cc:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  JS_DEFINE_STATE_MARKER(com);
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
../src/batch.cc:118:1: warning: unused variable '__contextORisolate' [-Wunused-variable]
JS_METHOD(Batch, Clear) {
^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:54:3: note: expanded from macro 'JS_METHOD'
  __JS_METHOD_BEGIN_COM()
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:47:3: note: expanded from macro '__JS_METHOD_BEGIN_COM'
  JS_DEFINE_STATE_MARKER_(p___args.GetIsolate()); \
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:94:53: note: expanded from macro 'JS_DEFINE_STATE_MARKER_'
#define JS_DEFINE_STATE_MARKER_(x) JS_ENGINE_MARKER __contextORisolate = x
                                                    ^
15 warnings generated.
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:19:
In file included from ../src/leveldown.h:11:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:17:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
../src/batch.h:20:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Batch, Batch) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:19:
../src/leveldown.h:51:13: warning: unused function 'DisposeStringOrBufferFromSlice' [-Wunused-function]
static void DisposeStringOrBufferFromSlice(JS_LOCAL_VALUE handle,
            ^
14 warnings generated.
In file included from ../src/database.cc:9:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:17:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:18:
../src/batch.h:20:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Batch, Batch) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
../src/database.cc:118:1: warning: unused variable '__contextORisolate' [-Wunused-variable]
JS_METHOD(Database, New) {
^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:54:3: note: expanded from macro 'JS_METHOD'
  __JS_METHOD_BEGIN_COM()
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:47:3: note: expanded from macro '__JS_METHOD_BEGIN_COM'
  JS_DEFINE_STATE_MARKER_(p___args.GetIsolate()); \
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:94:53: note: expanded from macro 'JS_DEFINE_STATE_MARKER_'
#define JS_DEFINE_STATE_MARKER_(x) JS_ENGINE_MARKER __contextORisolate = x
                                                    ^
../src/database.cc:130:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  JS_DEFINE_STATE_MARKER(com);
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
15 warnings generated.
In file included from ../src/database_async.cc:9:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:17:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:15:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:15:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
12 warnings generated.
In file included from ../src/iterator.cc:9:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:17:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
../src/iterator.cc:178:1: warning: unused variable '__contextORisolate' [-Wunused-variable]
JS_METHOD(Iterator, Next) {
^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:54:3: note: expanded from macro 'JS_METHOD'
  __JS_METHOD_BEGIN_COM()
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:47:3: note: expanded from macro '__JS_METHOD_BEGIN_COM'
  JS_DEFINE_STATE_MARKER_(p___args.GetIsolate()); \
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:94:53: note: expanded from macro 'JS_DEFINE_STATE_MARKER_'
#define JS_DEFINE_STATE_MARKER_(x) JS_ENGINE_MARKER __contextORisolate = x
                                                    ^
../src/iterator.cc:195:1: warning: unused variable '__contextORisolate' [-Wunused-variable]
JS_METHOD(Iterator, End) {
^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:54:3: note: expanded from macro 'JS_METHOD'
  __JS_METHOD_BEGIN_COM()
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:47:3: note: expanded from macro '__JS_METHOD_BEGIN_COM'
  JS_DEFINE_STATE_MARKER_(p___args.GetIsolate()); \
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:94:53: note: expanded from macro 'JS_DEFINE_STATE_MARKER_'
#define JS_DEFINE_STATE_MARKER_(x) JS_ENGINE_MARKER __contextORisolate = x
                                                    ^
../src/iterator.cc:222:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  JS_DEFINE_STATE_MARKER(com);
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:19:
../src/leveldown.h:51:13: warning: unused function 'DisposeStringOrBufferFromSlice' [-Wunused-function]
static void DisposeStringOrBufferFromSlice(JS_LOCAL_VALUE handle,
            ^
16 warnings generated.
In file included from ../src/iterator_async.cc:9:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:17:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:19:
../src/leveldown.h:51:13: warning: unused function 'DisposeStringOrBufferFromSlice' [-Wunused-function]
static void DisposeStringOrBufferFromSlice(JS_LOCAL_VALUE handle,
            ^
13 warnings generated.
In file included from ../src/leveldown.cc:10:
In file included from ../src/leveldown.h:11:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:17:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:13:
../src/batch.h:20:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Batch, Batch) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
../src/leveldown.cc:59:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(leveldown, LeveldownWrap) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
../src/leveldown.cc:70:1: warning: unused variable '__contextORisolate' [-Wunused-variable]
JS_METHOD(LeveldownWrap, New) {
^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:54:3: note: expanded from macro 'JS_METHOD'
  __JS_METHOD_BEGIN_COM()
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:47:3: note: expanded from macro '__JS_METHOD_BEGIN_COM'
  JS_DEFINE_STATE_MARKER_(p___args.GetIsolate()); \
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:94:53: note: expanded from macro 'JS_DEFINE_STATE_MARKER_'
#define JS_DEFINE_STATE_MARKER_(x) JS_ENGINE_MARKER __contextORisolate = x
                                                    ^
In file included from ../src/leveldown.cc:10:
../src/leveldown.h:51:13: warning: unused function 'DisposeStringOrBufferFromSlice' [-Wunused-function]
static void DisposeStringOrBufferFromSlice(JS_LOCAL_VALUE handle,
            ^
16 warnings generated.
In file included from ../src/leveldown_async.cc:10:
In file included from ../src/leveldown.h:11:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:13:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:13:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:10:
../src/leveldown.h:51:13: warning: unused function 'DisposeStringOrBufferFromSlice' [-Wunused-function]
static void DisposeStringOrBufferFromSlice(JS_LOCAL_VALUE handle,
            ^
13 warnings generated.
npm WARN EPACKAGEJSON thali-cordova-plugin-jxcore@1.0.0 No repository field.

```

Error: Command failed: npm WARN thali-test-server@0.0.1 No repository field.
npm WARN thali-test-server@0.0.1 No license field.
npm http request GET http://192.168.1.100:4873/lodash.throttle
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/javascript-state-machine
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-leveldb-core
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/bluebird
npm http 200 http://192.168.1.100:4873/ip
npm http 200 http://192.168.1.100:4873/javascript-state-machine
npm http 200 http://192.168.1.100:4873/lodash.throttle
npm http 200 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/long
npm http 200 http://192.168.1.100:4873/pouchdb-adapter-leveldb-core
npm http fetch GET http://192.168.1.100:4873/lodash.throttle/-/lodash.throttle-4.1.1.tgz
npm http 200 http://192.168.1.100:4873/lie
npm http 200 http://192.168.1.100:4873/uuid
npm http 200 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/multiplex
npm http fetch 200 http://192.168.1.100:4873/lodash.throttle/-/lodash.throttle-4.1.1.tgz
npm http fetch GET http://192.168.1.100:4873/pouchdb-adapter-leveldb-core/-/pouchdb-adapter-leveldb-core-6.1.1.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-adapter-leveldb-core/-/pouchdb-adapter-leveldb-core-6.1.1.tgz
npm http 200 http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/on-finished
npm http 200 http://192.168.1.100:4873/bytes
npm http 200 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/type-is
npm http 200 http://192.168.1.100:4873/raw-body
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/statuses
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/statuses
npm http request GET http://192.168.1.100:4873/ee-first
npm http 304 http://192.168.1.100:4873/ee-first
npm http request GET http://192.168.1.100:4873/unpipe
npm http 304 http://192.168.1.100:4873/unpipe
npm http request GET http://192.168.1.100:4873/media-typer
npm http request GET http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/media-typer
npm http 304 http://192.168.1.100:4873/mime-types
npm http request GET http://192.168.1.100:4873/mime-db
npm http 304 http://192.168.1.100:4873/mime-db
npm http request GET http://192.168.1.100:4873/array-flatten
npm http request GET http://192.168.1.100:4873/content-disposition
npm http request GET http://192.168.1.100:4873/cookie
npm http request GET http://192.168.1.100:4873/cookie-signature
npm http request GET http://192.168.1.100:4873/escape-html
npm http request GET http://192.168.1.100:4873/etag
npm http request GET http://192.168.1.100:4873/finalhandler
npm http request GET http://192.168.1.100:4873/fresh
npm http request GET http://192.168.1.100:4873/merge-descriptors
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/accepts
npm http request GET http://192.168.1.100:4873/parseurl
npm http request GET http://192.168.1.100:4873/path-to-regexp
npm http request GET http://192.168.1.100:4873/proxy-addr
npm http request GET http://192.168.1.100:4873/range-parser
npm http request GET http://192.168.1.100:4873/serve-static
npm http request GET http://192.168.1.100:4873/utils-merge
npm http request GET http://192.168.1.100:4873/vary
npm http request GET http://192.168.1.100:4873/send
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/serve-static
npm http 304 http://192.168.1.100:4873/utils-merge
npm http 304 http://192.168.1.100:4873/vary
npm http 304 http://192.168.1.100:4873/send
npm http request GET http://192.168.1.100:4873/negotiator
npm http 304 http://192.168.1.100:4873/negotiator
npm http request GET http://192.168.1.100:4873/forwarded
npm http request GET http://192.168.1.100:4873/ipaddr.js
npm http 304 http://192.168.1.100:4873/forwarded
npm http 304 http://192.168.1.100:4873/ipaddr.js
npm http request GET http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/mime
npm http 304 http://192.168.1.100:4873/destroy
npm http 304 http://192.168.1.100:4873/mime
npm http request GET http://192.168.1.100:4873/immediate
npm http 200 http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/duplexify
npm http 200 http://192.168.1.100:4873/xtend
npm http 200 http://192.168.1.100:4873/varint
npm http 200 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/stream-shift
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http 304 http://192.168.1.100:4873/stream-shift
npm http 200 http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/wrappy
npm http 304 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/core-util-is
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/string_decoder
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/buffer-shims
npm http 304 http://192.168.1.100:4873/process-nextick-args
npm http 304 http://192.168.1.100:4873/string_decoder
npm http 304 http://192.168.1.100:4873/core-util-is
npm http 304 http://192.168.1.100:4873/util-deprecate
npm http request GET http://192.168.1.100:4873/buffer-from
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/pouchdb-json
npm http request GET http://192.168.1.100:4873/pouchdb-md5
npm http request GET http://192.168.1.100:4873/argsarray
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-utils
npm http request GET http://192.168.1.100:4873/pouchdb-merge
npm http request GET http://192.168.1.100:4873/pouchdb-binary-utils
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/pouchdb-errors
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/pouchdb-utils
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/through2
npm http 200 http://192.168.1.100:4873/buffer-from
npm http 200 http://192.168.1.100:4873/argsarray
npm http 200 http://192.168.1.100:4873/pouchdb-json
npm http fetch GET http://192.168.1.100:4873/buffer-from/-/buffer-from-0.1.1.tgz
npm http 200 http://192.168.1.100:4873/pouchdb-md5
npm http 200 http://192.168.1.100:4873/double-ended-queue
npm http fetch GET http://192.168.1.100:4873/pouchdb-json/-/pouchdb-json-6.1.1.tgz
npm http fetch GET http://192.168.1.100:4873/pouchdb-md5/-/pouchdb-md5-6.1.1.tgz
npm http 200 http://192.168.1.100:4873/pouchdb-adapter-utils
npm http 200 http://192.168.1.100:4873/pouchdb-merge
npm http 200 http://192.168.1.100:4873/levelup
npm http 200 http://192.168.1.100:4873/pouchdb-binary-utils
npm http 200 http://192.168.1.100:4873/pouchdb-collections
npm http 200 http://192.168.1.100:4873/pouchdb-errors
npm http fetch 200 http://192.168.1.100:4873/buffer-from/-/buffer-from-0.1.1.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-json/-/pouchdb-json-6.1.1.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-md5/-/pouchdb-md5-6.1.1.tgz
npm http 200 http://192.168.1.100:4873/sublevel-pouchdb
npm http 200 http://192.168.1.100:4873/pouchdb-utils
npm http 200 http://192.168.1.100:4873/pouchdb-promise
npm http fetch GET http://192.168.1.100:4873/double-ended-queue/-/double-ended-queue-2.1.0-0.tgz
npm http 200 http://192.168.1.100:4873/through2
npm http fetch 200 http://192.168.1.100:4873/double-ended-queue/-/double-ended-queue-2.1.0-0.tgz
npm http fetch GET http://192.168.1.100:4873/levelup/-/levelup-1.3.3.tgz
npm http fetch GET http://192.168.1.100:4873/pouchdb-errors/-/pouchdb-errors-6.1.1.tgz
npm http fetch GET http://192.168.1.100:4873/pouchdb-binary-utils/-/pouchdb-binary-utils-6.1.1.tgz
npm http fetch GET http://192.168.1.100:4873/pouchdb-merge/-/pouchdb-merge-6.1.1.tgz
npm http fetch GET http://192.168.1.100:4873/pouchdb-collections/-/pouchdb-collections-6.1.1.tgz
npm http fetch GET http://192.168.1.100:4873/pouchdb-adapter-utils/-/pouchdb-adapter-utils-6.1.1.tgz
npm http fetch 200 http://192.168.1.100:4873/levelup/-/levelup-1.3.3.tgz
npm http fetch GET http://192.168.1.100:4873/sublevel-pouchdb/-/sublevel-pouchdb-6.1.1.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-errors/-/pouchdb-errors-6.1.1.tgz
npm http fetch GET http://192.168.1.100:4873/pouchdb-utils/-/pouchdb-utils-6.1.1.tgz
npm http fetch GET http://192.168.1.100:4873/pouchdb-promise/-/pouchdb-promise-6.1.1.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-binary-utils/-/pouchdb-binary-utils-6.1.1.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-merge/-/pouchdb-merge-6.1.1.tgz
npm http fetch 200 http://192.168.1.100:4873/sublevel-pouchdb/-/sublevel-pouchdb-6.1.1.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-adapter-utils/-/pouchdb-adapter-utils-6.1.1.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-collections/-/pouchdb-collections-6.1.1.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-utils/-/pouchdb-utils-6.1.1.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-promise/-/pouchdb-promise-6.1.1.tgz
npm http request GET http://192.168.1.100:4873/is-array-buffer-x
npm http 200 http://192.168.1.100:4873/is-array-buffer-x
npm http fetch GET http://192.168.1.100:4873/is-array-buffer-x/-/is-array-buffer-x-1.0.13.tgz
npm http fetch 200 http://192.168.1.100:4873/is-array-buffer-x/-/is-array-buffer-x-1.0.13.tgz
npm http request GET http://192.168.1.100:4873/is-object-like-x
npm http request GET http://192.168.1.100:4873/to-string-tag-x
npm http request GET http://192.168.1.100:4873/has-to-string-tag-x
npm http 200 http://192.168.1.100:4873/is-object-like-x
npm http 200 http://192.168.1.100:4873/has-to-string-tag-x
npm http 200 http://192.168.1.100:4873/to-string-tag-x
npm http fetch GET http://192.168.1.100:4873/is-object-like-x/-/is-object-like-x-1.0.11.tgz
npm http fetch 200 http://192.168.1.100:4873/is-object-like-x/-/is-object-like-x-1.0.11.tgz
npm http fetch GET http://192.168.1.100:4873/has-to-string-tag-x/-/has-to-string-tag-x-1.0.10.tgz
npm http fetch GET http://192.168.1.100:4873/to-string-tag-x/-/to-string-tag-x-1.0.11.tgz
npm http fetch 200 http://192.168.1.100:4873/has-to-string-tag-x/-/has-to-string-tag-x-1.0.10.tgz
npm http fetch 200 http://192.168.1.100:4873/to-string-tag-x/-/to-string-tag-x-1.0.11.tgz
npm http request GET http://192.168.1.100:4873/has-symbol-support-x
npm http 200 http://192.168.1.100:4873/has-symbol-support-x
npm http fetch GET http://192.168.1.100:4873/has-symbol-support-x/-/has-symbol-support-x-1.0.11.tgz
npm http fetch 200 http://192.168.1.100:4873/has-symbol-support-x/-/has-symbol-support-x-1.0.11.tgz
npm http request GET http://192.168.1.100:4873/is-function-x
npm http request GET http://192.168.1.100:4873/is-primitive
npm http 200 http://192.168.1.100:4873/is-function-x
npm http 200 http://192.168.1.100:4873/is-primitive
npm http fetch GET http://192.168.1.100:4873/is-function-x/-/is-function-x-1.0.6.tgz
npm http fetch GET http://192.168.1.100:4873/is-primitive/-/is-primitive-2.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/is-primitive/-/is-primitive-2.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/is-function-x/-/is-function-x-1.0.6.tgz
npm http request GET http://192.168.1.100:4873/lodash.isnull
npm http request GET http://192.168.1.100:4873/validate.io-undefined
npm http 200 http://192.168.1.100:4873/lodash.isnull
npm http 200 http://192.168.1.100:4873/validate.io-undefined
npm http fetch GET http://192.168.1.100:4873/lodash.isnull/-/lodash.isnull-3.0.0.tgz
npm http fetch GET http://192.168.1.100:4873/validate.io-undefined/-/validate.io-undefined-1.0.3.tgz
npm http fetch 200 http://192.168.1.100:4873/lodash.isnull/-/lodash.isnull-3.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/validate.io-undefined/-/validate.io-undefined-1.0.3.tgz
npm http request GET http://192.168.1.100:4873/level-iterator-stream
npm http request GET http://192.168.1.100:4873/level-errors
npm http request GET http://192.168.1.100:4873/deferred-leveldown
npm http request GET http://192.168.1.100:4873/prr
npm http request GET http://192.168.1.100:4873/level-codec
npm http request GET http://192.168.1.100:4873/semver
npm http 200 http://192.168.1.100:4873/level-errors
npm http 200 http://192.168.1.100:4873/level-iterator-stream
npm http 200 http://192.168.1.100:4873/prr
npm http 200 http://192.168.1.100:4873/level-codec
npm http 200 http://192.168.1.100:4873/deferred-leveldown
npm http 200 http://192.168.1.100:4873/semver
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http 200 http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/errno
npm http 200 http://192.168.1.100:4873/errno
npm http request GET http://192.168.1.100:4873/spark-md5
npm http 200 http://192.168.1.100:4873/spark-md5
npm http fetch GET http://192.168.1.100:4873/spark-md5/-/spark-md5-3.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/spark-md5/-/spark-md5-3.0.0.tgz
npm http request GET http://192.168.1.100:4873/clone-buffer
npm http fetch GET http://192.168.1.100:4873/debug/-/debug-2.6.0.tgz
npm http fetch 200 http://192.168.1.100:4873/debug/-/debug-2.6.0.tgz
npm http 200 http://192.168.1.100:4873/clone-buffer
npm http fetch GET http://192.168.1.100:4873/clone-buffer/-/clone-buffer-1.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/clone-buffer/-/clone-buffer-1.0.0.tgz
npm http fetch GET http://192.168.1.100:4873/ms/-/ms-0.7.2.tgz
npm http fetch 200 http://192.168.1.100:4873/ms/-/ms-0.7.2.tgz
npm http request GET http://192.168.1.100:4873/vuvuzela
npm http 200 http://192.168.1.100:4873/vuvuzela
npm http request GET http://192.168.1.100:4873/ltgt
npm http fetch GET http://192.168.1.100:4873/level-codec/-/level-codec-6.2.0.tgz
npm http fetch 200 http://192.168.1.100:4873/level-codec/-/level-codec-6.2.0.tgz
npm http 200 http://192.168.1.100:4873/ltgt
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/hawk
npm http 200 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/caseless
npm http 200 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/bl
npm http 200 http://192.168.1.100:4873/tunnel-agent
npm http 200 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 200 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/stringstream
npm http 200 http://192.168.1.100:4873/combined-stream
npm http 200 http://192.168.1.100:4873/har-validator
npm http 200 http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http fetch GET http://192.168.1.100:4873/async/-/async-2.1.4.tgz
npm http fetch 200 http://192.168.1.100:4873/async/-/async-2.1.4.tgz
npm http request GET http://192.168.1.100:4873/lodash
npm http 200 http://192.168.1.100:4873/lodash
npm http fetch GET http://192.168.1.100:4873/lodash/-/lodash-4.17.4.tgz
npm http fetch 200 http://192.168.1.100:4873/lodash/-/lodash-4.17.4.tgz
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/bluebird
npm http 200 http://192.168.1.100:4873/is-my-json-valid
npm http 200 http://192.168.1.100:4873/chalk
npm http 200 http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http 200 http://192.168.1.100:4873/escape-string-regexp
npm http 200 http://192.168.1.100:4873/has-ansi
npm http 200 http://192.168.1.100:4873/ansi-styles
npm http 200 http://192.168.1.100:4873/supports-color
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 200 http://192.168.1.100:4873/ansi-regex
npm http fetch GET http://192.168.1.100:4873/ansi-regex/-/ansi-regex-2.1.1.tgz
npm http fetch 200 http://192.168.1.100:4873/ansi-regex/-/ansi-regex-2.1.1.tgz
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http 200 http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-function
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http 200 http://192.168.1.100:4873/jsonpointer
npm http fetch GET http://192.168.1.100:4873/jsonpointer/-/jsonpointer-4.0.1.tgz
npm http fetch 200 http://192.168.1.100:4873/jsonpointer/-/jsonpointer-4.0.1.tgz
npm http request GET http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/sntp
npm http 200 http://192.168.1.100:4873/cryptiles
npm http 200 http://192.168.1.100:4873/sntp
npm http 200 http://192.168.1.100:4873/boom
npm http 200 http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/ctype
npm http 200 http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/punycode
npm http 200 http://192.168.1.100:4873/punycode
npm http request GET http://192.168.1.100:4873/jsonschema
npm http 200 http://192.168.1.100:4873/jsonschema
npm http fetch GET http://192.168.1.100:4873/jsonschema/-/jsonschema-1.1.1.tgz
npm http fetch 200 http://192.168.1.100:4873/jsonschema/-/jsonschema-1.1.1.tgz
npm http request GET http://192.168.1.100:4873/colors
npm http request GET http://192.168.1.100:4873/cycle
npm http request GET http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/pkginfo
npm http request GET http://192.168.1.100:4873/stack-trace
npm http 304 http://192.168.1.100:4873/colors
npm http 304 http://192.168.1.100:4873/cycle
npm http 304 http://192.168.1.100:4873/eyes
npm http 304 http://192.168.1.100:4873/pkginfo
npm http 304 http://192.168.1.100:4873/stack-trace
npm http request GET http://192.168.1.100:4873/eslint
npm http request GET http://192.168.1.100:4873/jsdoc
npm http 200 http://192.168.1.100:4873/jsdoc
npm http 200 http://192.168.1.100:4873/eslint
npm http fetch GET http://192.168.1.100:4873/eslint/-/eslint-3.11.1.tgz
npm http fetch 200 http://192.168.1.100:4873/eslint/-/eslint-3.11.1.tgz
npm http request GET http://192.168.1.100:4873/babel-code-frame
npm http request GET http://192.168.1.100:4873/doctrine
npm http request GET http://192.168.1.100:4873/escope
npm http request GET http://192.168.1.100:4873/estraverse
npm http request GET http://192.168.1.100:4873/esutils
npm http request GET http://192.168.1.100:4873/file-entry-cache
npm http request GET http://192.168.1.100:4873/globals
npm http request GET http://192.168.1.100:4873/ignore
npm http request GET http://192.168.1.100:4873/is-resolvable
npm http request GET http://192.168.1.100:4873/js-yaml
npm http request GET http://192.168.1.100:4873/levn
npm http request GET http://192.168.1.100:4873/natural-compare
npm http request GET http://192.168.1.100:4873/optionator
npm http request GET http://192.168.1.100:4873/path-is-inside
npm http request GET http://192.168.1.100:4873/pluralize
npm http request GET http://192.168.1.100:4873/require-uncached
npm http request GET http://192.168.1.100:4873/strip-bom
npm http request GET http://192.168.1.100:4873/table
npm http request GET http://192.168.1.100:4873/text-table
npm http request GET http://192.168.1.100:4873/user-home
npm http request GET http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/imurmurhash
npm http request GET http://192.168.1.100:4873/espree
npm http request GET http://192.168.1.100:4873/json-stable-stringify
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/progress
npm http request GET http://192.168.1.100:4873/inquirer
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/shelljs
npm http 200 http://192.168.1.100:4873/doctrine
npm http 200 http://192.168.1.100:4873/escope
npm http 200 http://192.168.1.100:4873/babel-code-frame
npm http 200 http://192.168.1.100:4873/esutils
npm http 200 http://192.168.1.100:4873/estraverse
npm http fetch GET http://192.168.1.100:4873/doctrine/-/doctrine-1.5.0.tgz
npm http fetch GET http://192.168.1.100:4873/escope/-/escope-3.6.0.tgz
npm http 200 http://192.168.1.100:4873/file-entry-cache
npm http 200 http://192.168.1.100:4873/globals
npm http fetch GET http://192.168.1.100:4873/babel-code-frame/-/babel-code-frame-6.22.0.tgz
npm http 200 http://192.168.1.100:4873/ignore
npm http 200 http://192.168.1.100:4873/is-resolvable
npm http fetch GET http://192.168.1.100:4873/esutils/-/esutils-2.0.2.tgz
npm http fetch GET http://192.168.1.100:4873/estraverse/-/estraverse-4.2.0.tgz
npm http 200 http://192.168.1.100:4873/js-yaml
npm http 200 http://192.168.1.100:4873/levn
npm http fetch GET http://192.168.1.100:4873/globals/-/globals-9.14.0.tgz
npm http fetch GET http://192.168.1.100:4873/file-entry-cache/-/file-entry-cache-2.0.0.tgz
npm http 200 http://192.168.1.100:4873/natural-compare
npm http fetch GET http://192.168.1.100:4873/ignore/-/ignore-3.2.0.tgz
npm http 200 http://192.168.1.100:4873/optionator
npm http 200 http://192.168.1.100:4873/path-is-inside
npm http fetch GET http://192.168.1.100:4873/is-resolvable/-/is-resolvable-1.0.0.tgz
npm http 200 http://192.168.1.100:4873/pluralize
npm http 200 http://192.168.1.100:4873/require-uncached
npm http 200 http://192.168.1.100:4873/strip-bom
npm http fetch GET http://192.168.1.100:4873/levn/-/levn-0.3.0.tgz
npm http fetch GET http://192.168.1.100:4873/js-yaml/-/js-yaml-3.7.0.tgz
npm http 200 http://192.168.1.100:4873/table
npm http fetch GET http://192.168.1.100:4873/natural-compare/-/natural-compare-1.4.0.tgz
npm http 200 http://192.168.1.100:4873/user-home
npm http 200 http://192.168.1.100:4873/text-table
npm http 304 http://192.168.1.100:4873/glob
npm http fetch GET http://192.168.1.100:4873/optionator/-/optionator-0.8.2.tgz
npm http 200 http://192.168.1.100:4873/concat-stream
npm http 304 http://192.168.1.100:4873/imurmurhash
npm http fetch GET http://192.168.1.100:4873/path-is-inside/-/path-is-inside-1.0.2.tgz
npm http fetch GET http://192.168.1.100:4873/pluralize/-/pluralize-1.2.1.tgz
npm http fetch GET http://192.168.1.100:4873/require-uncached/-/require-uncached-1.0.3.tgz
npm http 304 http://192.168.1.100:4873/json-stable-stringify
npm http fetch GET http://192.168.1.100:4873/strip-bom/-/strip-bom-3.0.0.tgz
npm http 200 http://192.168.1.100:4873/mkdirp
npm http fetch GET http://192.168.1.100:4873/table/-/table-3.8.3.tgz
npm http fetch 200 http://192.168.1.100:4873/doctrine/-/doctrine-1.5.0.tgz
npm http fetch GET http://192.168.1.100:4873/user-home/-/user-home-2.0.0.tgz
npm http fetch GET http://192.168.1.100:4873/text-table/-/text-table-0.2.0.tgz
npm http fetch GET http://192.168.1.100:4873/concat-stream/-/concat-stream-1.6.0.tgz
npm http fetch 200 http://192.168.1.100:4873/escope/-/escope-3.6.0.tgz
npm http 200 http://192.168.1.100:4873/espree
npm http 200 http://192.168.1.100:4873/progress
npm http 200 http://192.168.1.100:4873/strip-json-comments
npm http fetch GET http://192.168.1.100:4873/json-stable-stringify/-/json-stable-stringify-1.0.1.tgz
npm http fetch 200 http://192.168.1.100:4873/esutils/-/esutils-2.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/estraverse/-/estraverse-4.2.0.tgz
npm http fetch 200 http://192.168.1.100:4873/globals/-/globals-9.14.0.tgz
npm http fetch 200 http://192.168.1.100:4873/file-entry-cache/-/file-entry-cache-2.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/ignore/-/ignore-3.2.0.tgz
npm http fetch 200 http://192.168.1.100:4873/is-resolvable/-/is-resolvable-1.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/levn/-/levn-0.3.0.tgz
npm http fetch 200 http://192.168.1.100:4873/js-yaml/-/js-yaml-3.7.0.tgz
npm http fetch 200 http://192.168.1.100:4873/path-is-inside/-/path-is-inside-1.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/natural-compare/-/natural-compare-1.4.0.tgz
npm http fetch 200 http://192.168.1.100:4873/optionator/-/optionator-0.8.2.tgz
npm http fetch 200 http://192.168.1.100:4873/babel-code-frame/-/babel-code-frame-6.22.0.tgz
npm http fetch 200 http://192.168.1.100:4873/pluralize/-/pluralize-1.2.1.tgz
npm http 200 http://192.168.1.100:4873/shelljs
npm http fetch GET http://192.168.1.100:4873/espree/-/espree-3.3.2.tgz
npm http fetch 200 http://192.168.1.100:4873/strip-bom/-/strip-bom-3.0.0.tgz
npm http 200 http://192.168.1.100:4873/inquirer
npm http fetch 200 http://192.168.1.100:4873/require-uncached/-/require-uncached-1.0.3.tgz
npm http fetch 200 http://192.168.1.100:4873/table/-/table-3.8.3.tgz
npm http fetch 200 http://192.168.1.100:4873/user-home/-/user-home-2.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/text-table/-/text-table-0.2.0.tgz
npm http fetch 200 http://192.168.1.100:4873/json-stable-stringify/-/json-stable-stringify-1.0.1.tgz
npm http fetch 200 http://192.168.1.100:4873/concat-stream/-/concat-stream-1.6.0.tgz
npm http fetch 200 http://192.168.1.100:4873/espree/-/espree-3.3.2.tgz
npm http fetch GET http://192.168.1.100:4873/shelljs/-/shelljs-0.7.6.tgz
npm http fetch GET http://192.168.1.100:4873/inquirer/-/inquirer-0.12.0.tgz
npm http fetch 200 http://192.168.1.100:4873/shelljs/-/shelljs-0.7.6.tgz
npm http fetch 200 http://192.168.1.100:4873/inquirer/-/inquirer-0.12.0.tgz
npm http request GET http://192.168.1.100:4873/js-tokens
npm http 200 http://192.168.1.100:4873/js-tokens
npm http fetch GET http://192.168.1.100:4873/js-tokens/-/js-tokens-3.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/js-tokens/-/js-tokens-3.0.0.tgz
npm http request GET http://192.168.1.100:4873/typedarray
npm http 304 http://192.168.1.100:4873/typedarray
npm http request GET http://192.168.1.100:4873/es6-map
npm http request GET http://192.168.1.100:4873/es6-weak-map
npm http request GET http://192.168.1.100:4873/esrecurse
npm http 200 http://192.168.1.100:4873/es6-map
npm http 200 http://192.168.1.100:4873/es6-weak-map
npm http 200 http://192.168.1.100:4873/esrecurse
npm http fetch GET http://192.168.1.100:4873/esrecurse/-/esrecurse-4.1.0.tgz
npm http fetch GET http://192.168.1.100:4873/es6-weak-map/-/es6-weak-map-2.0.1.tgz
npm http fetch GET http://192.168.1.100:4873/es6-map/-/es6-map-0.1.4.tgz
npm http fetch 200 http://192.168.1.100:4873/esrecurse/-/esrecurse-4.1.0.tgz
npm http fetch 200 http://192.168.1.100:4873/es6-map/-/es6-map-0.1.4.tgz
npm http fetch 200 http://192.168.1.100:4873/es6-weak-map/-/es6-weak-map-2.0.1.tgz
npm http request GET http://192.168.1.100:4873/es6-set
npm http request GET http://192.168.1.100:4873/event-emitter
npm http request GET http://192.168.1.100:4873/d
npm http request GET http://192.168.1.100:4873/es6-symbol
npm http request GET http://192.168.1.100:4873/es6-iterator
npm http request GET http://192.168.1.100:4873/es5-ext
npm http 200 http://192.168.1.100:4873/es6-set
npm http fetch GET http://192.168.1.100:4873/es6-set/-/es6-set-0.1.4.tgz
npm http 200 http://192.168.1.100:4873/d
npm http 200 http://192.168.1.100:4873/event-emitter
npm http fetch 200 http://192.168.1.100:4873/es6-set/-/es6-set-0.1.4.tgz
npm http 200 http://192.168.1.100:4873/es6-symbol
npm http 200 http://192.168.1.100:4873/es6-iterator
npm http fetch GET http://192.168.1.100:4873/event-emitter/-/event-emitter-0.3.4.tgz
npm http fetch 200 http://192.168.1.100:4873/event-emitter/-/event-emitter-0.3.4.tgz
npm http 200 http://192.168.1.100:4873/es5-ext
npm http fetch GET http://192.168.1.100:4873/estraverse/-/estraverse-4.1.1.tgz
npm http fetch 200 http://192.168.1.100:4873/estraverse/-/estraverse-4.1.1.tgz
npm http request GET http://192.168.1.100:4873/acorn-jsx
npm http request GET http://192.168.1.100:4873/acorn
npm http 200 http://192.168.1.100:4873/acorn-jsx
npm http fetch GET http://192.168.1.100:4873/acorn-jsx/-/acorn-jsx-3.0.1.tgz
npm http 200 http://192.168.1.100:4873/acorn
npm http fetch 200 http://192.168.1.100:4873/acorn-jsx/-/acorn-jsx-3.0.1.tgz
npm http fetch GET http://192.168.1.100:4873/acorn/-/acorn-4.0.4.tgz
npm http fetch 200 http://192.168.1.100:4873/acorn/-/acorn-4.0.4.tgz
npm http request GET http://192.168.1.100:4873/flat-cache
npm http 200 http://192.168.1.100:4873/flat-cache
npm http fetch GET http://192.168.1.100:4873/flat-cache/-/flat-cache-1.2.2.tgz
npm http fetch 200 http://192.168.1.100:4873/flat-cache/-/flat-cache-1.2.2.tgz
npm http request GET http://192.168.1.100:4873/circular-json
npm http request GET http://192.168.1.100:4873/del
npm http request GET http://192.168.1.100:4873/write
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http 200 http://192.168.1.100:4873/circular-json
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http 200 http://192.168.1.100:4873/write
npm http 200 http://192.168.1.100:4873/del
npm http fetch GET http://192.168.1.100:4873/circular-json/-/circular-json-0.3.1.tgz
npm http fetch GET http://192.168.1.100:4873/write/-/write-0.2.1.tgz
npm http fetch GET http://192.168.1.100:4873/del/-/del-2.2.2.tgz
npm http fetch 200 http://192.168.1.100:4873/circular-json/-/circular-json-0.3.1.tgz
npm http fetch 200 http://192.168.1.100:4873/write/-/write-0.2.1.tgz
npm http fetch 200 http://192.168.1.100:4873/del/-/del-2.2.2.tgz
npm http request GET http://192.168.1.100:4873/globby
npm http request GET http://192.168.1.100:4873/is-path-cwd
npm http request GET http://192.168.1.100:4873/is-path-in-cwd
npm http request GET http://192.168.1.100:4873/pify
npm http request GET http://192.168.1.100:4873/rimraf
npm http request GET http://192.168.1.100:4873/pinkie-promise
npm http 304 http://192.168.1.100:4873/rimraf
npm http 200 http://192.168.1.100:4873/is-path-in-cwd
npm http 200 http://192.168.1.100:4873/pify
npm http 200 http://192.168.1.100:4873/is-path-cwd
npm http 200 http://192.168.1.100:4873/globby
npm http 200 http://192.168.1.100:4873/pinkie-promise
npm http fetch GET http://192.168.1.100:4873/is-path-in-cwd/-/is-path-in-cwd-1.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/is-path-in-cwd/-/is-path-in-cwd-1.0.0.tgz
npm http fetch GET http://192.168.1.100:4873/pify/-/pify-2.3.0.tgz
npm http fetch GET http://192.168.1.100:4873/is-path-cwd/-/is-path-cwd-1.0.0.tgz
npm http fetch GET http://192.168.1.100:4873/globby/-/globby-5.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/pify/-/pify-2.3.0.tgz
npm http fetch 200 http://192.168.1.100:4873/is-path-cwd/-/is-path-cwd-1.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/globby/-/globby-5.0.0.tgz
npm http request GET http://192.168.1.100:4873/array-union
npm http request GET http://192.168.1.100:4873/arrify
npm http 200 http://192.168.1.100:4873/arrify
npm http 200 http://192.168.1.100:4873/array-union
npm http fetch GET http://192.168.1.100:4873/array-union/-/array-union-1.0.2.tgz
npm http fetch GET http://192.168.1.100:4873/arrify/-/arrify-1.0.1.tgz
npm http fetch 200 http://192.168.1.100:4873/array-union/-/array-union-1.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/arrify/-/arrify-1.0.1.tgz
npm http request GET http://192.168.1.100:4873/array-uniq
npm http 200 http://192.168.1.100:4873/array-uniq
npm http fetch GET http://192.168.1.100:4873/array-uniq/-/array-uniq-1.0.3.tgz
npm http fetch 200 http://192.168.1.100:4873/array-uniq/-/array-uniq-1.0.3.tgz
npm http request GET http://192.168.1.100:4873/fs.realpath
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/fs.realpath
npm http 304 http://192.168.1.100:4873/inflight
npm http 304 http://192.168.1.100:4873/minimatch
npm http 304 http://192.168.1.100:4873/path-is-absolute
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 304 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/pinkie
npm http 304 http://192.168.1.100:4873/pinkie
npm http request GET http://192.168.1.100:4873/is-path-inside
npm http 200 http://192.168.1.100:4873/is-path-inside
npm http fetch GET http://192.168.1.100:4873/is-path-inside/-/is-path-inside-1.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/is-path-inside/-/is-path-inside-1.0.0.tgz
npm http request GET http://192.168.1.100:4873/minimist
npm http 200 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/string-width
npm http request GET http://192.168.1.100:4873/cli-width
npm http request GET http://192.168.1.100:4873/figures
npm http request GET http://192.168.1.100:4873/run-async
npm http request GET http://192.168.1.100:4873/ansi-escapes
npm http request GET http://192.168.1.100:4873/cli-cursor
npm http request GET http://192.168.1.100:4873/readline2
npm http request GET http://192.168.1.100:4873/through
npm http request GET http://192.168.1.100:4873/rx-lite
npm http 200 http://192.168.1.100:4873/string-width
npm http fetch GET http://192.168.1.100:4873/string-width/-/string-width-1.0.2.tgz
npm http 304 http://192.168.1.100:4873/cli-width
npm http fetch GET http://192.168.1.100:4873/cli-width/-/cli-width-2.1.0.tgz
npm http 200 http://192.168.1.100:4873/ansi-escapes
npm http 200 http://192.168.1.100:4873/run-async
npm http 200 http://192.168.1.100:4873/figures
npm http fetch 200 http://192.168.1.100:4873/string-width/-/string-width-1.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/cli-width/-/cli-width-2.1.0.tgz
npm http 304 http://192.168.1.100:4873/readline2
npm http 200 http://192.168.1.100:4873/cli-cursor
npm http 304 http://192.168.1.100:4873/rx-lite
npm http 200 http://192.168.1.100:4873/through
npm http request GET http://192.168.1.100:4873/restore-cursor
npm http 200 http://192.168.1.100:4873/restore-cursor
npm http request GET http://192.168.1.100:4873/exit-hook
npm http request GET http://192.168.1.100:4873/onetime
npm http 304 http://192.168.1.100:4873/exit-hook
npm http 304 http://192.168.1.100:4873/onetime
npm http request GET http://192.168.1.100:4873/code-point-at
npm http request GET http://192.168.1.100:4873/is-fullwidth-code-point
npm http request GET http://192.168.1.100:4873/mute-stream
npm http 304 http://192.168.1.100:4873/code-point-at
npm http 304 http://192.168.1.100:4873/is-fullwidth-code-point
npm http 200 http://192.168.1.100:4873/mute-stream
npm http request GET http://192.168.1.100:4873/number-is-nan
npm http 304 http://192.168.1.100:4873/number-is-nan
npm http request GET http://192.168.1.100:4873/tryit
npm http 200 http://192.168.1.100:4873/tryit
npm http fetch GET http://192.168.1.100:4873/tryit/-/tryit-1.0.3.tgz
npm http fetch 200 http://192.168.1.100:4873/tryit/-/tryit-1.0.3.tgz
npm http request GET http://192.168.1.100:4873/argparse
npm http request GET http://192.168.1.100:4873/esprima
npm http 200 http://192.168.1.100:4873/argparse
npm http 200 http://192.168.1.100:4873/esprima
npm http fetch GET http://192.168.1.100:4873/argparse/-/argparse-1.0.9.tgz
npm http fetch 200 http://192.168.1.100:4873/argparse/-/argparse-1.0.9.tgz
npm http request GET http://192.168.1.100:4873/sprintf-js
npm http 200 http://192.168.1.100:4873/sprintf-js
npm http fetch GET http://192.168.1.100:4873/sprintf-js/-/sprintf-js-1.0.3.tgz
npm http fetch 200 http://192.168.1.100:4873/sprintf-js/-/sprintf-js-1.0.3.tgz
npm http request GET http://192.168.1.100:4873/jsonify
npm http 304 http://192.168.1.100:4873/jsonify
npm http request GET http://192.168.1.100:4873/prelude-ls
npm http request GET http://192.168.1.100:4873/type-check
npm http 200 http://192.168.1.100:4873/prelude-ls
npm http 200 http://192.168.1.100:4873/type-check
npm http fetch GET http://192.168.1.100:4873/prelude-ls/-/prelude-ls-1.1.2.tgz
npm http fetch 200 http://192.168.1.100:4873/prelude-ls/-/prelude-ls-1.1.2.tgz
npm http fetch GET http://192.168.1.100:4873/type-check/-/type-check-0.3.2.tgz
npm http fetch 200 http://192.168.1.100:4873/type-check/-/type-check-0.3.2.tgz
npm http request GET http://192.168.1.100:4873/deep-is
npm http request GET http://192.168.1.100:4873/wordwrap
npm http request GET http://192.168.1.100:4873/fast-levenshtein
npm http 200 http://192.168.1.100:4873/wordwrap
npm http 200 http://192.168.1.100:4873/deep-is
npm http 200 http://192.168.1.100:4873/fast-levenshtein
npm http fetch GET http://192.168.1.100:4873/fast-levenshtein/-/fast-levenshtein-2.0.6.tgz
npm http fetch GET http://192.168.1.100:4873/wordwrap/-/wordwrap-1.0.0.tgz
npm http fetch GET http://192.168.1.100:4873/deep-is/-/deep-is-0.1.3.tgz
npm http fetch 200 http://192.168.1.100:4873/fast-levenshtein/-/fast-levenshtein-2.0.6.tgz
npm http fetch 200 http://192.168.1.100:4873/wordwrap/-/wordwrap-1.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/deep-is/-/deep-is-0.1.3.tgz
npm http request GET http://192.168.1.100:4873/caller-path
npm http request GET http://192.168.1.100:4873/resolve-from
npm http 200 http://192.168.1.100:4873/resolve-from
npm http 200 http://192.168.1.100:4873/caller-path
npm http fetch GET http://192.168.1.100:4873/caller-path/-/caller-path-0.1.0.tgz
npm http fetch GET http://192.168.1.100:4873/resolve-from/-/resolve-from-1.0.1.tgz
npm http fetch 200 http://192.168.1.100:4873/resolve-from/-/resolve-from-1.0.1.tgz
npm http fetch 200 http://192.168.1.100:4873/caller-path/-/caller-path-0.1.0.tgz
npm http request GET http://192.168.1.100:4873/callsites
npm http 200 http://192.168.1.100:4873/callsites
npm http fetch GET http://192.168.1.100:4873/callsites/-/callsites-0.2.0.tgz
npm http fetch 200 http://192.168.1.100:4873/callsites/-/callsites-0.2.0.tgz
npm http request GET http://192.168.1.100:4873/interpret
npm http request GET http://192.168.1.100:4873/rechoir
npm http 200 http://192.168.1.100:4873/interpret
npm http 304 http://192.168.1.100:4873/rechoir
npm http request GET http://192.168.1.100:4873/resolve
npm http 200 http://192.168.1.100:4873/resolve
npm http fetch GET http://192.168.1.100:4873/resolve/-/resolve-1.2.0.tgz
npm http fetch 200 http://192.168.1.100:4873/resolve/-/resolve-1.2.0.tgz
npm http request GET http://192.168.1.100:4873/ajv
npm http request GET http://192.168.1.100:4873/ajv-keywords
npm http request GET http://192.168.1.100:4873/slice-ansi
npm http fetch GET http://192.168.1.100:4873/string-width/-/string-width-2.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/string-width/-/string-width-2.0.0.tgz
npm http 200 http://192.168.1.100:4873/slice-ansi
npm http 200 http://192.168.1.100:4873/ajv-keywords
npm http 200 http://192.168.1.100:4873/ajv
npm http fetch GET http://192.168.1.100:4873/slice-ansi/-/slice-ansi-0.0.4.tgz
npm http fetch GET http://192.168.1.100:4873/ajv-keywords/-/ajv-keywords-1.5.0.tgz
npm http fetch 200 http://192.168.1.100:4873/slice-ansi/-/slice-ansi-0.0.4.tgz
npm http fetch GET http://192.168.1.100:4873/ajv/-/ajv-4.10.4.tgz
npm http fetch 200 http://192.168.1.100:4873/ajv-keywords/-/ajv-keywords-1.5.0.tgz
npm http fetch 200 http://192.168.1.100:4873/ajv/-/ajv-4.10.4.tgz
npm http request GET http://192.168.1.100:4873/co
npm http 200 http://192.168.1.100:4873/co
npm http fetch GET http://192.168.1.100:4873/co/-/co-4.6.0.tgz
npm http fetch 200 http://192.168.1.100:4873/co/-/co-4.6.0.tgz
npm http fetch GET http://192.168.1.100:4873/is-fullwidth-code-point/-/is-fullwidth-code-point-2.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/is-fullwidth-code-point/-/is-fullwidth-code-point-2.0.0.tgz
npm http request GET http://192.168.1.100:4873/os-homedir
npm http 304 http://192.168.1.100:4873/os-homedir
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/catharsis
npm http request GET http://192.168.1.100:4873/wrench
npm http request GET http://192.168.1.100:4873/underscore
npm http request GET http://192.168.1.100:4873/js2xmlparser
npm http request GET http://192.168.1.100:4873/marked
npm http request GET http://192.168.1.100:4873/requizzle
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 304 http://192.168.1.100:4873/async
npm http 200 http://192.168.1.100:4873/catharsis
npm http 200 http://192.168.1.100:4873/underscore
npm http 200 http://192.168.1.100:4873/wrench
npm http 200 http://192.168.1.100:4873/js2xmlparser
npm WARN deprecated wrench@1.5.9: wrench.js is deprecated! You should check out fs-extra (https://github.com/jprichardson/node-fs-extra) for any operations you were using wrench for. Thanks for all the usage over the years.
npm http 200 http://192.168.1.100:4873/marked
npm http 200 http://192.168.1.100:4873/requizzle
npm http fetch 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http request GET http://192.168.1.100:4873/underscore-contrib
npm http 200 http://192.168.1.100:4873/underscore-contrib
npm WARN prefer global marked@0.3.6 should be installed with -g
npm WARN install@0.0.1 No repository field.
npm http request GET http://192.168.1.100:4873/stacky
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/child-process-promise
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/bn.js
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/leveldown-mobile
npm http request GET http://192.168.1.100:4873/express-pouchdb
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/pouchdb
npm http request GET http://192.168.1.100:4873/pouchdb-size
npm http request GET http://192.168.1.100:4873/proxyquire
npm http request GET http://192.168.1.100:4873/request-promise
npm http request GET http://192.168.1.100:4873/sinon
npm http request GET http://192.168.1.100:4873/nock
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/supertest
npm http request GET http://192.168.1.100:4873/supertest-as-promised
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/tmp
npm http request GET http://192.168.1.100:4873/tape-catch
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/uuid-validate
npm http request GET http://192.168.1.100:4873/tape
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/body-parser
npm http 200 http://192.168.1.100:4873/stacky
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/child-process-promise
npm http 304 http://192.168.1.100:4873/concat-map
npm http fetch GET http://192.168.1.100:4873/stacky/-/stacky-1.3.1.tgz
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/is-property
npm http 200 http://192.168.1.100:4873/js-extend
npm http 304 http://192.168.1.100:4873/minimist
npm http 200 http://192.168.1.100:4873/bn.js
npm http 200 http://192.168.1.100:4873/express-pouchdb
npm http 304 http://192.168.1.100:4873/multiplex
npm http 304 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/randomstring
npm http 304 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/leveldown-mobile
npm http 200 http://192.168.1.100:4873/pouchdb-size
npm http 200 http://192.168.1.100:4873/proxyquire
npm http 304 http://192.168.1.100:4873/socket.io-client
npm http fetch GET http://192.168.1.100:4873/express-pouchdb/-/express-pouchdb-1.0.6-thali.tgz
npm http 200 http://192.168.1.100:4873/pouchdb
npm http 200 http://192.168.1.100:4873/supertest
npm http 304 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/request-promise
npm http 304 http://192.168.1.100:4873/uuid
npm http 200 http://192.168.1.100:4873/supertest-as-promised
npm http fetch 200 http://192.168.1.100:4873/stacky/-/stacky-1.3.1.tgz
npm http fetch 200 http://192.168.1.100:4873/express-pouchdb/-/express-pouchdb-1.0.6-thali.tgz
npm http 200 http://192.168.1.100:4873/tape-catch
npm http 200 http://192.168.1.100:4873/tmp
npm http 200 http://192.168.1.100:4873/uuid-validate
npm http fetch GET http://192.168.1.100:4873/pouchdb/-/pouchdb-6.1.1.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb/-/pouchdb-6.1.1.tgz
npm http 200 http://192.168.1.100:4873/sinon
npm http 200 http://192.168.1.100:4873/tape
npm http 200 http://192.168.1.100:4873/nock
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/raw-body
npm http request GET http://192.168.1.100:4873/type-is
npm http 304 http://192.168.1.100:4873/bytes
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/statuses
npm http 304 http://192.168.1.100:4873/statuses
npm http request GET http://192.168.1.100:4873/ee-first
npm http 304 http://192.168.1.100:4873/ee-first
npm http request GET http://192.168.1.100:4873/unpipe
npm http 304 http://192.168.1.100:4873/unpipe
npm http request GET http://192.168.1.100:4873/media-typer
npm http request GET http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/media-typer
npm http 304 http://192.168.1.100:4873/mime-types
npm http request GET http://192.168.1.100:4873/mime-db
npm http 304 http://192.168.1.100:4873/mime-db
npm http request GET http://192.168.1.100:4873/accepts
npm http request GET http://192.168.1.100:4873/array-flatten
npm http request GET http://192.168.1.100:4873/content-disposition
npm http request GET http://192.168.1.100:4873/cookie
npm http request GET http://192.168.1.100:4873/cookie-signature
npm http request GET http://192.168.1.100:4873/escape-html
npm http request GET http://192.168.1.100:4873/etag
npm http request GET http://192.168.1.100:4873/finalhandler
npm http request GET http://192.168.1.100:4873/fresh
npm http request GET http://192.168.1.100:4873/merge-descriptors
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/parseurl
npm http request GET http://192.168.1.100:4873/path-to-regexp
npm http request GET http://192.168.1.100:4873/proxy-addr
npm http request GET http://192.168.1.100:4873/range-parser
npm http request GET http://192.168.1.100:4873/send
npm http request GET http://192.168.1.100:4873/serve-static
npm http request GET http://192.168.1.100:4873/utils-merge
npm http request GET http://192.168.1.100:4873/vary
npm http 304 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/vary
npm http 304 http://192.168.1.100:4873/serve-static
npm http 304 http://192.168.1.100:4873/utils-merge
npm http 304 http://192.168.1.100:4873/send
npm http request GET http://192.168.1.100:4873/negotiator
npm http 304 http://192.168.1.100:4873/negotiator
npm http request GET http://192.168.1.100:4873/forwarded
npm http request GET http://192.168.1.100:4873/ipaddr.js
npm http 304 http://192.168.1.100:4873/forwarded
npm http 304 http://192.168.1.100:4873/ipaddr.js
npm http request GET http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/mime
npm http 304 http://192.168.1.100:4873/destroy
npm http 304 http://192.168.1.100:4873/mime
npm http request GET http://192.168.1.100:4873/basic-auth
npm http request GET http://192.168.1.100:4873/compression
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/cookie-parser
npm http request GET http://192.168.1.100:4873/header-case-normalizer
npm http request GET http://192.168.1.100:4873/multiparty
npm http request GET http://192.168.1.100:4873/pouchdb-all-dbs
npm http request GET http://192.168.1.100:4873/pouchdb-auth
npm http request GET http://192.168.1.100:4873/pouchdb-find
npm http request GET http://192.168.1.100:4873/pouchdb-list
npm http request GET http://192.168.1.100:4873/pouchdb-replicator
npm http request GET http://192.168.1.100:4873/pouchdb-security
npm http request GET http://192.168.1.100:4873/pouchdb-validation
npm http request GET http://192.168.1.100:4873/pouchdb-vhost
npm http request GET http://192.168.1.100:4873/pouchdb-rewrite
npm http request GET http://192.168.1.100:4873/pouchdb-wrappers
npm http request GET http://192.168.1.100:4873/pouchdb-show
npm http request GET http://192.168.1.100:4873/pouchdb-update
npm http 200 http://192.168.1.100:4873/basic-auth
npm http 304 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/header-case-normalizer
npm http 200 http://192.168.1.100:4873/compression
npm http 200 http://192.168.1.100:4873/cookie-parser
npm http 200 http://192.168.1.100:4873/multiparty
npm http 200 http://192.168.1.100:4873/pouchdb-all-dbs
npm http 200 http://192.168.1.100:4873/pouchdb-list
npm http 200 http://192.168.1.100:4873/pouchdb-auth
npm http 200 http://192.168.1.100:4873/pouchdb-find
npm http 200 http://192.168.1.100:4873/pouchdb-replicator
npm http 200 http://192.168.1.100:4873/pouchdb-security
npm http 200 http://192.168.1.100:4873/pouchdb-rewrite
npm http 200 http://192.168.1.100:4873/pouchdb-vhost
npm http 200 http://192.168.1.100:4873/pouchdb-validation
npm http 200 http://192.168.1.100:4873/pouchdb-wrappers
npm http 200 http://192.168.1.100:4873/pouchdb-show
npm http 200 http://192.168.1.100:4873/pouchdb-update
npm http request GET http://192.168.1.100:4873/setprototypeof
npm http 304 http://192.168.1.100:4873/setprototypeof
npm http request GET http://192.168.1.100:4873/on-headers
npm http request GET http://192.168.1.100:4873/compressible
npm http 304 http://192.168.1.100:4873/on-headers
npm http 200 http://192.168.1.100:4873/compressible
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/stream-counter
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 200 http://192.168.1.100:4873/stream-counter
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/argsarray
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/tiny-queue
npm http 304 http://192.168.1.100:4873/es3ify
npm http 304 http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/argsarray
npm http 200 http://192.168.1.100:4873/tiny-queue
npm http request GET http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/base62
npm http 304 http://192.168.1.100:4873/base62
npm http 304 http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http request GET http://192.168.1.100:4873/crypto-lite
npm http request GET http://192.168.1.100:4873/pouchdb-system-db
npm http request GET http://192.168.1.100:4873/pouchdb-req-http-query
npm http request GET http://192.168.1.100:4873/secure-random
npm http request GET http://192.168.1.100:4873/base64url
npm http request GET http://192.168.1.100:4873/couchdb-calculate-session-id
npm http request GET http://192.168.1.100:4873/pouchdb-plugin-error
npm http request GET http://192.168.1.100:4873/promise-nodify
npm http 200 http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http 200 http://192.168.1.100:4873/pouchdb-system-db
npm http 200 http://192.168.1.100:4873/secure-random
npm http 200 http://192.168.1.100:4873/crypto-lite
npm http 200 http://192.168.1.100:4873/pouchdb-req-http-query
npm http 200 http://192.168.1.100:4873/base64url
npm http 200 http://192.168.1.100:4873/couchdb-calculate-session-id
npm http 200 http://192.168.1.100:4873/promise-nodify
npm http 200 http://192.168.1.100:4873/pouchdb-plugin-error
npm http request GET http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/meow
npm http 304 http://192.168.1.100:4873/concat-stream
npm http 200 http://192.168.1.100:4873/meow
npm http request GET http://192.168.1.100:4873/typedarray
npm http 304 http://192.168.1.100:4873/typedarray
npm http request GET http://192.168.1.100:4873/camelcase-keys
npm http request GET http://192.168.1.100:4873/indent-string
npm http 200 http://192.168.1.100:4873/camelcase-keys
npm http 200 http://192.168.1.100:4873/indent-string
npm http request GET http://192.168.1.100:4873/map-obj
npm http request GET http://192.168.1.100:4873/camelcase
npm http 200 http://192.168.1.100:4873/map-obj
npm http 200 http://192.168.1.100:4873/camelcase
npm http request GET http://192.168.1.100:4873/get-stdin
npm http request GET http://192.168.1.100:4873/repeating
npm http 304 http://192.168.1.100:4873/repeating
npm http 200 http://192.168.1.100:4873/get-stdin
npm http request GET http://192.168.1.100:4873/is-finite
npm http 304 http://192.168.1.100:4873/is-finite
npm http request GET http://192.168.1.100:4873/number-is-nan
npm http 304 http://192.168.1.100:4873/number-is-nan
npm http request GET http://192.168.1.100:4873/aproba
npm http 200 http://192.168.1.100:4873/aproba
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/es6-promise-pool
npm http request GET http://192.168.1.100:4873/fruitdown
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/memdown
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/pouchdb-collate
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/vuvuzela
npm http request GET http://192.168.1.100:4873/level-write-stream
npm http request GET http://192.168.1.100:4873/localstorage-down
npm http request GET http://192.168.1.100:4873/scope-eval
npm http 304 http://192.168.1.100:4873/double-ended-queue
npm http 304 http://192.168.1.100:4873/levelup
npm http 200 http://192.168.1.100:4873/fruitdown
npm http 200 http://192.168.1.100:4873/es6-promise-pool
npm http 200 http://192.168.1.100:4873/memdown
npm http 304 http://192.168.1.100:4873/pouchdb-collections
npm http 304 http://192.168.1.100:4873/sublevel-pouchdb
npm http 304 http://192.168.1.100:4873/spark-md5
npm http 304 http://192.168.1.100:4873/through2
npm http 200 http://192.168.1.100:4873/pouchdb-collate
npm http 304 http://192.168.1.100:4873/js-extend
npm http 304 http://192.168.1.100:4873/vuvuzela
npm http 200 http://192.168.1.100:4873/level-write-stream
npm http 200 http://192.168.1.100:4873/scope-eval
npm http 200 http://192.168.1.100:4873/localstorage-down
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/d64
npm http 304 http://192.168.1.100:4873/abstract-leveldown
npm http 200 http://192.168.1.100:4873/d64
npm http request GET http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/end-stream
npm http 200 http://192.168.1.100:4873/end-stream
npm http request GET http://192.168.1.100:4873/write-stream
npm http 200 http://192.168.1.100:4873/write-stream
npm http request GET http://192.168.1.100:4873/deferred-leveldown
npm http request GET http://192.168.1.100:4873/level-codec
npm http request GET http://192.168.1.100:4873/level-errors
npm http request GET http://192.168.1.100:4873/level-iterator-stream
npm http request GET http://192.168.1.100:4873/prr
npm http request GET http://192.168.1.100:4873/semver
npm http 304 http://192.168.1.100:4873/deferred-leveldown
npm http 304 http://192.168.1.100:4873/level-codec
npm http 304 http://192.168.1.100:4873/level-errors
npm http 304 http://192.168.1.100:4873/level-iterator-stream
npm http 304 http://192.168.1.100:4873/prr
npm http 304 http://192.168.1.100:4873/semver
npm http request GET http://192.168.1.100:4873/errno
npm http 304 http://192.168.1.100:4873/errno
npm http request GET http://192.168.1.100:4873/humble-localstorage
npm http 200 http://192.168.1.100:4873/humble-localstorage
npm http request GET http://192.168.1.100:4873/has-localstorage
npm http request GET http://192.168.1.100:4873/localstorage-memory
npm http 200 http://192.168.1.100:4873/localstorage-memory
npm http 200 http://192.168.1.100:4873/has-localstorage
npm http request GET http://192.168.1.100:4873/ltgt
npm http request GET http://192.168.1.100:4873/functional-red-black-tree
npm http 304 http://192.168.1.100:4873/ltgt
npm http 200 http://192.168.1.100:4873/functional-red-black-tree
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/aws4
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/is-typedarray
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/aws4
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/is-typedarray
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/tough-cookie
npm WARN deprecated tough-cookie@2.2.2: ReDoS vulnerability parsing Set-Cookie https://nodesecurity.io/advisories/130
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 304 http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/process-nextick-args
npm http 304 http://192.168.1.100:4873/util-deprecate
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/pinkie-promise
npm http 304 http://192.168.1.100:4873/is-my-json-valid
npm http 304 http://192.168.1.100:4873/pinkie-promise
npm http 304 http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/ansi-styles
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http 304 http://192.168.1.100:4873/supports-color
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-function
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http request GET http://192.168.1.100:4873/pinkie
npm http 304 http://192.168.1.100:4873/pinkie
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/hoek
npm http 304 http://192.168.1.100:4873/boom
npm http 304 http://192.168.1.100:4873/cryptiles
npm http 304 http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/jsprim
npm http request GET http://192.168.1.100:4873/sshpk
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 304 http://192.168.1.100:4873/jsprim
npm http 304 http://192.168.1.100:4873/sshpk
npm http request GET http://192.168.1.100:4873/extsprintf
npm http request GET http://192.168.1.100:4873/json-schema
npm http request GET http://192.168.1.100:4873/verror
npm http 304 http://192.168.1.100:4873/extsprintf
npm http 304 http://192.168.1.100:4873/json-schema
npm http 304 http://192.168.1.100:4873/verror
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/dashdash
npm http request GET http://192.168.1.100:4873/getpass
npm http 304 http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/getpass
npm http 304 http://192.168.1.100:4873/dashdash
npm http request GET http://192.168.1.100:4873/pull-stream
npm http 200 http://192.168.1.100:4873/pull-stream
npm http request GET http://192.168.1.100:4873/pull-core
npm http 200 http://192.168.1.100:4873/pull-core
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/lie
npm http 304 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/xmlhttprequest-cookie
npm http 200 http://192.168.1.100:4873/xmlhttprequest-cookie
npm http request GET http://192.168.1.100:4873/xmlhttprequest
npm http 200 http://192.168.1.100:4873/xmlhttprequest
npm http request GET http://192.168.1.100:4873/pouchdb-changeslike-wrapper
npm http 200 http://192.168.1.100:4873/pouchdb-changeslike-wrapper
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/random-uuid-v4
npm http request GET http://192.168.1.100:4873/couchdb-eval
npm http request GET http://192.168.1.100:4873/couchdb-objects
npm http 200 http://192.168.1.100:4873/random-uuid-v4
npm http 200 http://192.168.1.100:4873/couchdb-eval
npm http 200 http://192.168.1.100:4873/couchdb-objects
npm http request GET http://192.168.1.100:4873/is-empty
npm http 200 http://192.168.1.100:4873/is-empty
npm http request GET http://192.168.1.100:4873/is-array
npm http request GET http://192.168.1.100:4873/pouchdb-extend
npm http request GET http://192.168.1.100:4873/pouchdb-upsert
npm http 200 http://192.168.1.100:4873/pouchdb-extend
npm http 200 http://192.168.1.100:4873/is-array
npm http 200 http://192.168.1.100:4873/pouchdb-upsert
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 304 http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/recast
npm http request GET http://192.168.1.100:4873/ast-types
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/ast-types
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/couchdb-render
npm http 304 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/couchdb-render
npm http request GET http://192.168.1.100:4873/couchdb-resp-completer
npm http 200 http://192.168.1.100:4873/couchdb-resp-completer
npm http request GET http://192.168.1.100:4873/equals
npm http 200 http://192.168.1.100:4873/equals
npm http request GET http://192.168.1.100:4873/jkroso-type
npm http 200 http://192.168.1.100:4873/jkroso-type
npm http request GET http://192.168.1.100:4873/pouchdb-route
npm http 200 http://192.168.1.100:4873/pouchdb-route
npm http request GET http://192.168.1.100:4873/get-folder-size
npm http 200 http://192.168.1.100:4873/get-folder-size
npm http request GET http://192.168.1.100:4873/minimist
npm http 304 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/fast-future
npm http 304 http://192.168.1.100:4873/abstract-leveldown
npm http 200 http://192.168.1.100:4873/fast-future
npm http 200 http://192.168.1.100:4873/bindings
npm http fetch GET http://192.168.1.100:4873/fast-future/-/fast-future-1.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/fast-future/-/fast-future-1.0.2.tgz
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/duplexify
npm http 304 http://192.168.1.100:4873/varint
npm http 304 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/stream-shift
npm http 304 http://192.168.1.100:4873/end-of-stream
npm http 304 http://192.168.1.100:4873/stream-shift
npm http request GET http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http 304 http://192.168.1.100:4873/buffer-shims
npm WARN deprecated lodash@2.4.1: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/chai
npm http request GET http://192.168.1.100:4873/propagate
npm http request GET http://192.168.1.100:4873/deep-equal
npm http 304 http://192.168.1.100:4873/debug
npm http 200 http://192.168.1.100:4873/propagate
npm http 200 http://192.168.1.100:4873/deep-equal
npm http 200 http://192.168.1.100:4873/chai
npm http request GET http://192.168.1.100:4873/assertion-error
npm http request GET http://192.168.1.100:4873/deep-eql
npm http request GET http://192.168.1.100:4873/type-detect
npm http 200 http://192.168.1.100:4873/assertion-error
npm http 200 http://192.168.1.100:4873/deep-eql
npm http 200 http://192.168.1.100:4873/type-detect
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/ip
npm http 304 http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/buffer-from
npm http request GET http://192.168.1.100:4873/clone-buffer
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/level-codec
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/ltgt
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/leveldown
npm http 304 http://192.168.1.100:4873/buffer-from
npm http 304 http://192.168.1.100:4873/clone-buffer
npm http 304 http://192.168.1.100:4873/double-ended-queue
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/level-codec
npm http 304 http://192.168.1.100:4873/levelup
npm http 304 http://192.168.1.100:4873/ltgt
npm http 304 http://192.168.1.100:4873/spark-md5
npm http 304 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/leveldown
npm http fetch GET http://192.168.1.100:4873/leveldown/-/leveldown-1.5.0.tgz
npm http fetch 200 http://192.168.1.100:4873/leveldown/-/leveldown-1.5.0.tgz
npm http request GET http://192.168.1.100:4873/is-array-buffer-x
npm http 304 http://192.168.1.100:4873/is-array-buffer-x
npm http request GET http://192.168.1.100:4873/to-string-tag-x
npm http request GET http://192.168.1.100:4873/is-object-like-x
npm http request GET http://192.168.1.100:4873/has-to-string-tag-x
npm http 304 http://192.168.1.100:4873/has-to-string-tag-x
npm http 304 http://192.168.1.100:4873/is-object-like-x
npm http 304 http://192.168.1.100:4873/to-string-tag-x
npm http request GET http://192.168.1.100:4873/has-symbol-support-x
npm http 304 http://192.168.1.100:4873/has-symbol-support-x
npm http request GET http://192.168.1.100:4873/is-function-x
npm http request GET http://192.168.1.100:4873/is-primitive
npm http 304 http://192.168.1.100:4873/is-function-x
npm http 304 http://192.168.1.100:4873/is-primitive
npm http request GET http://192.168.1.100:4873/lodash.isnull
npm http request GET http://192.168.1.100:4873/validate.io-undefined
npm http 304 http://192.168.1.100:4873/lodash.isnull
npm http 304 http://192.168.1.100:4873/validate.io-undefined
npm http request GET http://192.168.1.100:4873/nan
npm http request GET http://192.168.1.100:4873/prebuild
npm http 200 http://192.168.1.100:4873/nan
npm http 200 http://192.168.1.100:4873/prebuild
npm http fetch GET http://192.168.1.100:4873/prebuild/-/prebuild-4.5.0.tgz
npm http fetch 200 http://192.168.1.100:4873/prebuild/-/prebuild-4.5.0.tgz
npm http request GET http://192.168.1.100:4873/execspawn
npm http request GET http://192.168.1.100:4873/ghreleases
npm http request GET http://192.168.1.100:4873/expand-template
npm http request GET http://192.168.1.100:4873/github-from-package
npm http request GET http://192.168.1.100:4873/node-ninja
npm http request GET http://192.168.1.100:4873/os-homedir
npm http request GET http://192.168.1.100:4873/noop-logger
npm http request GET http://192.168.1.100:4873/npmlog
npm http request GET http://192.168.1.100:4873/node-gyp
npm http request GET http://192.168.1.100:4873/pump
npm http request GET http://192.168.1.100:4873/rc
npm http request GET http://192.168.1.100:4873/simple-get
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/tar-fs
npm http request GET http://192.168.1.100:4873/tar-stream
npm http 200 http://192.168.1.100:4873/execspawn
npm http 200 http://192.168.1.100:4873/ghreleases
npm http 200 http://192.168.1.100:4873/github-from-package
npm http 200 http://192.168.1.100:4873/expand-template
npm http 200 http://192.168.1.100:4873/node-ninja
npm http fetch GET http://192.168.1.100:4873/execspawn/-/execspawn-1.0.1.tgz
npm http fetch GET http://192.168.1.100:4873/expand-template/-/expand-template-1.0.3.tgz
npm http 304 http://192.168.1.100:4873/os-homedir
npm http 200 http://192.168.1.100:4873/noop-logger
npm http 200 http://192.168.1.100:4873/npmlog
npm http 200 http://192.168.1.100:4873/pump
npm http 200 http://192.168.1.100:4873/node-gyp
npm http fetch GET http://192.168.1.100:4873/pump/-/pump-1.0.2.tgz
npm http 200 http://192.168.1.100:4873/rc
npm http 200 http://192.168.1.100:4873/simple-get
npm http fetch 200 http://192.168.1.100:4873/expand-template/-/expand-template-1.0.3.tgz
npm http fetch 200 http://192.168.1.100:4873/execspawn/-/execspawn-1.0.1.tgz
npm http 304 http://192.168.1.100:4873/async
npm http fetch 200 http://192.168.1.100:4873/pump/-/pump-1.0.2.tgz
npm http 200 http://192.168.1.100:4873/tar-fs
npm http fetch GET http://192.168.1.100:4873/node-gyp/-/node-gyp-3.5.0.tgz
npm http 200 http://192.168.1.100:4873/tar-stream
npm http fetch 200 http://192.168.1.100:4873/node-gyp/-/node-gyp-3.5.0.tgz
npm http fetch GET http://192.168.1.100:4873/tar-fs/-/tar-fs-1.15.0.tgz
npm http fetch 200 http://192.168.1.100:4873/tar-fs/-/tar-fs-1.15.0.tgz
npm http request GET http://192.168.1.100:4873/util-extend
npm http 200 http://192.168.1.100:4873/util-extend
npm http fetch GET http://192.168.1.100:4873/util-extend/-/util-extend-1.0.3.tgz
npm http fetch 200 http://192.168.1.100:4873/util-extend/-/util-extend-1.0.3.tgz
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/ghutils
npm http request GET http://192.168.1.100:4873/url-template
npm http request GET http://192.168.1.100:4873/simple-mime
npm http request GET http://192.168.1.100:4873/ghrepos
npm http 304 http://192.168.1.100:4873/after
npm http 200 http://192.168.1.100:4873/ghutils
npm http 200 http://192.168.1.100:4873/url-template
npm http 200 http://192.168.1.100:4873/simple-mime
npm http 200 http://192.168.1.100:4873/ghrepos
npm http fetch GET http://192.168.1.100:4873/after/-/after-0.8.2.tgz
npm http fetch GET http://192.168.1.100:4873/ghutils/-/ghutils-3.2.1.tgz
npm http fetch 200 http://192.168.1.100:4873/after/-/after-0.8.2.tgz
npm http fetch 200 http://192.168.1.100:4873/ghutils/-/ghutils-3.2.1.tgz
npm http request GET http://192.168.1.100:4873/jsonist
npm http 200 http://192.168.1.100:4873/jsonist
npm http fetch GET http://192.168.1.100:4873/jsonist/-/jsonist-1.3.0.tgz
npm http fetch 200 http://192.168.1.100:4873/jsonist/-/jsonist-1.3.0.tgz
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/hyperquest
npm http 304 http://192.168.1.100:4873/bl
npm http 200 http://192.168.1.100:4873/hyperquest
npm http request GET http://192.168.1.100:4873/duplexer2
npm http 304 http://192.168.1.100:4873/duplexer2
npm http request GET http://192.168.1.100:4873/fstream
npm http request GET http://192.168.1.100:4873/osenv
npm http request GET http://192.168.1.100:4873/nopt
npm http request GET http://192.168.1.100:4873/tar
npm http request GET http://192.168.1.100:4873/which
npm http 304 http://192.168.1.100:4873/fstream
npm http 200 http://192.168.1.100:4873/osenv
npm http 304 http://192.168.1.100:4873/tar
npm http 200 http://192.168.1.100:4873/nopt
npm http 200 http://192.168.1.100:4873/which
npm http fetch GET http://192.168.1.100:4873/osenv/-/osenv-0.1.4.tgz
npm http fetch 200 http://192.168.1.100:4873/osenv/-/osenv-0.1.4.tgz
npm http fetch GET http://192.168.1.100:4873/which/-/which-1.2.12.tgz
npm http fetch 200 http://192.168.1.100:4873/which/-/which-1.2.12.tgz
npm http request GET http://192.168.1.100:4873/abbrev
npm http 304 http://192.168.1.100:4873/abbrev
npm http request GET http://192.168.1.100:4873/ansi
npm http request GET http://192.168.1.100:4873/are-we-there-yet
npm http request GET http://192.168.1.100:4873/gauge
npm http 304 http://192.168.1.100:4873/ansi
npm http 200 http://192.168.1.100:4873/are-we-there-yet
npm http 200 http://192.168.1.100:4873/gauge
npm http request GET http://192.168.1.100:4873/delegates
npm http 200 http://192.168.1.100:4873/delegates
npm http request GET http://192.168.1.100:4873/lodash.padend
npm http request GET http://192.168.1.100:4873/has-unicode
npm http request GET http://192.168.1.100:4873/lodash.padstart
npm http request GET http://192.168.1.100:4873/lodash.pad
npm http 200 http://192.168.1.100:4873/has-unicode
npm http 200 http://192.168.1.100:4873/lodash.padend
npm http 200 http://192.168.1.100:4873/lodash.padstart
npm http 200 http://192.168.1.100:4873/lodash.pad
npm http fetch GET http://192.168.1.100:4873/lodash.padend/-/lodash.padend-4.6.1.tgz
npm http fetch GET http://192.168.1.100:4873/lodash.padstart/-/lodash.padstart-4.6.1.tgz
npm http fetch GET http://192.168.1.100:4873/lodash.pad/-/lodash.pad-4.5.1.tgz
npm http fetch 200 http://192.168.1.100:4873/lodash.padend/-/lodash.padend-4.6.1.tgz
npm http fetch 200 http://192.168.1.100:4873/lodash.padstart/-/lodash.padstart-4.6.1.tgz
npm http fetch 200 http://192.168.1.100:4873/lodash.pad/-/lodash.pad-4.5.1.tgz
npm http request GET http://192.168.1.100:4873/os-tmpdir
npm http 304 http://192.168.1.100:4873/os-tmpdir
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/block-stream
npm http 304 http://192.168.1.100:4873/block-stream
npm http request GET http://192.168.1.100:4873/isexe
npm http 200 http://192.168.1.100:4873/isexe
npm http request GET http://192.168.1.100:4873/path-array
npm http 200 http://192.168.1.100:4873/path-array
npm http request GET http://192.168.1.100:4873/array-index
npm http 200 http://192.168.1.100:4873/array-index
npm http request GET http://192.168.1.100:4873/es6-symbol
npm http 304 http://192.168.1.100:4873/es6-symbol
npm http request GET http://192.168.1.100:4873/d
npm http request GET http://192.168.1.100:4873/es5-ext
npm http 304 http://192.168.1.100:4873/d
npm http 304 http://192.168.1.100:4873/es5-ext
npm http request GET http://192.168.1.100:4873/es6-iterator
npm http 304 http://192.168.1.100:4873/es6-iterator
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http 304 http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/ini
npm http request GET http://192.168.1.100:4873/deep-extend
npm http 304 http://192.168.1.100:4873/ini
npm http 304 http://192.168.1.100:4873/strip-json-comments
npm http 200 http://192.168.1.100:4873/deep-extend
npm http request GET http://192.168.1.100:4873/unzip-response
npm http 200 http://192.168.1.100:4873/unzip-response
npm http fetch GET http://192.168.1.100:4873/unzip-response/-/unzip-response-1.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/unzip-response/-/unzip-response-1.0.2.tgz
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/uuid
npm http 304 http://192.168.1.100:4873/uuid
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/form-data
npm http fetch GET http://192.168.1.100:4873/uuid/-/uuid-3.0.1.tgz
npm http fetch 200 http://192.168.1.100:4873/uuid/-/uuid-3.0.1.tgz
npm http request GET http://192.168.1.100:4873/asynckit
npm http 304 http://192.168.1.100:4873/asynckit
npm http request GET http://192.168.1.100:4873/punycode
npm http 304 http://192.168.1.100:4873/punycode
npm http request GET http://192.168.1.100:4873/fill-keys
npm http request GET http://192.168.1.100:4873/module-not-found-error
npm http 200 http://192.168.1.100:4873/module-not-found-error
npm http 200 http://192.168.1.100:4873/fill-keys
npm http request GET http://192.168.1.100:4873/is-object
npm http 200 http://192.168.1.100:4873/is-object
npm http request GET http://192.168.1.100:4873/array-uniq
npm http 304 http://192.168.1.100:4873/array-uniq
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/jsonschema
npm http 304 http://192.168.1.100:4873/jsonschema
npm http request GET http://192.168.1.100:4873/samsam
npm http request GET http://192.168.1.100:4873/util
npm http request GET http://192.168.1.100:4873/formatio
npm http request GET http://192.168.1.100:4873/lolex
npm http 200 http://192.168.1.100:4873/samsam
npm http 304 http://192.168.1.100:4873/util
npm http 200 http://192.168.1.100:4873/formatio
npm http 200 http://192.168.1.100:4873/lolex
npm http request GET http://192.168.1.100:4873/engine.io-client
npm http request GET http://192.168.1.100:4873/component-bind
npm http request GET http://192.168.1.100:4873/component-emitter
npm http request GET http://192.168.1.100:4873/object-component
npm http request GET http://192.168.1.100:4873/socket.io-parser
npm http request GET http://192.168.1.100:4873/has-binary
npm http request GET http://192.168.1.100:4873/indexof
npm http request GET http://192.168.1.100:4873/parseuri
npm http request GET http://192.168.1.100:4873/to-array
npm http request GET http://192.168.1.100:4873/backo2
npm http 304 http://192.168.1.100:4873/component-bind
npm http 304 http://192.168.1.100:4873/engine.io-client
npm http 304 http://192.168.1.100:4873/component-emitter
npm http 304 http://192.168.1.100:4873/socket.io-parser
npm http 304 http://192.168.1.100:4873/object-component
npm http 304 http://192.168.1.100:4873/has-binary
npm http 304 http://192.168.1.100:4873/indexof
npm http 304 http://192.168.1.100:4873/parseuri
npm http 304 http://192.168.1.100:4873/to-array
npm http 304 http://192.168.1.100:4873/backo2
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/ws
npm http request GET http://192.168.1.100:4873/xmlhttprequest-ssl
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/parseqs
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/yeast
npm http 304 http://192.168.1.100:4873/has-cors
npm http 304 http://192.168.1.100:4873/ws
npm http 304 http://192.168.1.100:4873/xmlhttprequest-ssl
npm http 304 http://192.168.1.100:4873/parsejson
npm http 304 http://192.168.1.100:4873/engine.io-parser
npm http 304 http://192.168.1.100:4873/parseqs
npm http 304 http://192.168.1.100:4873/component-inherit
npm http 304 http://192.168.1.100:4873/yeast
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/utf8
npm http 304 http://192.168.1.100:4873/arraybuffer.slice
npm http 304 http://192.168.1.100:4873/blob
npm http 304 http://192.168.1.100:4873/utf8
npm http 304 http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/better-assert
npm http 304 http://192.168.1.100:4873/better-assert
npm http request GET http://192.168.1.100:4873/callsite
npm http 304 http://192.168.1.100:4873/callsite
npm http request GET http://192.168.1.100:4873/options
npm http request GET http://192.168.1.100:4873/ultron
npm http 304 http://192.168.1.100:4873/options
npm http 304 http://192.168.1.100:4873/ultron
npm http request GET http://192.168.1.100:4873/json3
npm http request GET http://192.168.1.100:4873/benchmark
npm http 304 http://192.168.1.100:4873/json3
npm http 304 http://192.168.1.100:4873/benchmark
npm http request GET http://192.168.1.100:4873/superagent
npm http 200 http://192.168.1.100:4873/superagent
npm http request GET http://192.168.1.100:4873/reduce-component
npm http request GET http://192.168.1.100:4873/cookiejar
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/formidable
npm http 304 http://192.168.1.100:4873/methods
npm http 200 http://192.168.1.100:4873/reduce-component
npm http 200 http://192.168.1.100:4873/cookiejar
npm http 200 http://192.168.1.100:4873/formidable
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/mime-types
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/mime-db
npm http 304 http://192.168.1.100:4873/mime-db
npm http request GET http://192.168.1.100:4873/defined
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/resumer
npm http request GET http://192.168.1.100:4873/object-inspect
npm http 304 http://192.168.1.100:4873/defined
npm http 304 http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/resumer
npm http 200 http://192.168.1.100:4873/object-inspect
npm WARN prefer global node-ninja@1.0.2 should be installed with -g
npm WARN prefer global node-gyp@3.5.0 should be installed with -g
gyp JXcore NODE-GYP Using node-gyp bundled in npm coming from JXcore
gyp http GET https://jxcore.azureedge.net/jxb311.tar.gz
gyp http 200 https://jxcore.azureedge.net/jxb311.tar.gz
In file included from ../src/batch.cc:2:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
1 warning generated.
In file included from ../src/batch_async.cc:8:
In file included from ../src/batch.h:9:
In file included from ../src/database.h:16:
In file included from ../../nan/nan.h:48:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
1 warning generated.
In file included from ../src/database.cc:7:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
1 warning generated.
In file included from ../src/database_async.cc:7:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
1 warning generated.
In file included from ../src/iterator.cc:7:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
1 warning generated.
In file included from ../src/iterator_async.cc:7:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
1 warning generated.
In file included from ../src/leveldown.cc:8:
In file included from ../src/leveldown.h:9:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
1 warning generated.
In file included from ../src/leveldown_async.cc:8:
In file included from ../src/leveldown.h:9:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
1 warning generated.
gyp JXcore NODE-GYP Using node-gyp bundled in npm coming from JXcore
In file included from ../src/batch.cc:4:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:7:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:17:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:7:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:7:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:8:
In file included from ../src/batch_async.h:15:
../src/batch.h:20:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Batch, Batch) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
../src/batch.cc:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  JS_DEFINE_STATE_MARKER(com);
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
../src/batch.cc:118:1: warning: unused variable '__contextORisolate' [-Wunused-variable]
JS_METHOD(Batch, Clear) {
^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:54:3: note: expanded from macro 'JS_METHOD'
  __JS_METHOD_BEGIN_COM()
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:47:3: note: expanded from macro '__JS_METHOD_BEGIN_COM'
  JS_DEFINE_STATE_MARKER_(p___args.GetIsolate()); \
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:94:53: note: expanded from macro 'JS_DEFINE_STATE_MARKER_'
#define JS_DEFINE_STATE_MARKER_(x) JS_ENGINE_MARKER __contextORisolate = x
                                                    ^
15 warnings generated.
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:19:
In file included from ../src/leveldown.h:11:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:17:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
../src/batch.h:20:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Batch, Batch) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:19:
../src/leveldown.h:51:13: warning: unused function 'DisposeStringOrBufferFromSlice' [-Wunused-function]
static void DisposeStringOrBufferFromSlice(JS_LOCAL_VALUE handle,
            ^
14 warnings generated.
In file included from ../src/database.cc:9:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:17:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:18:
../src/batch.h:20:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Batch, Batch) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
../src/database.cc:118:1: warning: unused variable '__contextORisolate' [-Wunused-variable]
JS_METHOD(Database, New) {
^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:54:3: note: expanded from macro 'JS_METHOD'
  __JS_METHOD_BEGIN_COM()
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:47:3: note: expanded from macro '__JS_METHOD_BEGIN_COM'
  JS_DEFINE_STATE_MARKER_(p___args.GetIsolate()); \
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:94:53: note: expanded from macro 'JS_DEFINE_STATE_MARKER_'
#define JS_DEFINE_STATE_MARKER_(x) JS_ENGINE_MARKER __contextORisolate = x
                                                    ^
../src/database.cc:130:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  JS_DEFINE_STATE_MARKER(com);
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
15 warnings generated.
In file included from ../src/database_async.cc:9:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:17:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:15:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:15:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
12 warnings generated.
In file included from ../src/iterator.cc:9:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:17:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
../src/iterator.cc:178:1: warning: unused variable '__contextORisolate' [-Wunused-variable]
JS_METHOD(Iterator, Next) {
^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:54:3: note: expanded from macro 'JS_METHOD'
  __JS_METHOD_BEGIN_COM()
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:47:3: note: expanded from macro '__JS_METHOD_BEGIN_COM'
  JS_DEFINE_STATE_MARKER_(p___args.GetIsolate()); \
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:94:53: note: expanded from macro 'JS_DEFINE_STATE_MARKER_'
#define JS_DEFINE_STATE_MARKER_(x) JS_ENGINE_MARKER __contextORisolate = x
                                                    ^
../src/iterator.cc:195:1: warning: unused variable '__contextORisolate' [-Wunused-variable]
JS_METHOD(Iterator, End) {
^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:54:3: note: expanded from macro 'JS_METHOD'
  __JS_METHOD_BEGIN_COM()
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:47:3: note: expanded from macro '__JS_METHOD_BEGIN_COM'
  JS_DEFINE_STATE_MARKER_(p___args.GetIsolate()); \
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:94:53: note: expanded from macro 'JS_DEFINE_STATE_MARKER_'
#define JS_DEFINE_STATE_MARKER_(x) JS_ENGINE_MARKER __contextORisolate = x
                                                    ^
../src/iterator.cc:222:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  JS_DEFINE_STATE_MARKER(com);
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:19:
../src/leveldown.h:51:13: warning: unused function 'DisposeStringOrBufferFromSlice' [-Wunused-function]
static void DisposeStringOrBufferFromSlice(JS_LOCAL_VALUE handle,
            ^
16 warnings generated.
In file included from ../src/iterator_async.cc:9:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:17:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:19:
../src/leveldown.h:51:13: warning: unused function 'DisposeStringOrBufferFromSlice' [-Wunused-function]
static void DisposeStringOrBufferFromSlice(JS_LOCAL_VALUE handle,
            ^
13 warnings generated.
In file included from ../src/leveldown.cc:10:
In file included from ../src/leveldown.h:11:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:17:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:13:
../src/batch.h:20:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Batch, Batch) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
../src/leveldown.cc:59:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(leveldown, LeveldownWrap) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
../src/leveldown.cc:70:1: warning: unused variable '__contextORisolate' [-Wunused-variable]
JS_METHOD(LeveldownWrap, New) {
^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:54:3: note: expanded from macro 'JS_METHOD'
  __JS_METHOD_BEGIN_COM()
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:47:3: note: expanded from macro '__JS_METHOD_BEGIN_COM'
  JS_DEFINE_STATE_MARKER_(p___args.GetIsolate()); \
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:94:53: note: expanded from macro 'JS_DEFINE_STATE_MARKER_'
#define JS_DEFINE_STATE_MARKER_(x) JS_ENGINE_MARKER __contextORisolate = x
                                                    ^
In file included from ../src/leveldown.cc:10:
../src/leveldown.h:51:13: warning: unused function 'DisposeStringOrBufferFromSlice' [-Wunused-function]
static void DisposeStringOrBufferFromSlice(JS_LOCAL_VALUE handle,
            ^
16 warnings generated.
In file included from ../src/leveldown_async.cc:10:
In file included from ../src/leveldown.h:11:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:13:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:13:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:10:
../src/leveldown.h:51:13: warning: unused function 'DisposeStringOrBufferFromSlice' [-Wunused-function]
static void DisposeStringOrBufferFromSlice(JS_LOCAL_VALUE handle,
            ^
13 warnings generated.
npm WARN EPACKAGEJSON thali-cordova-plugin-jxcore@1.0.0 No repository field.
