#### Test (Fail) 113351851 Build Logs


```


```

```
Already up-to-date.

From https://github.com/thaliproject/Thali_CordovaPlugin
   6826b5a..bdf46e2  master_jareksl_ci_test -> origin/master_jareksl_ci_test

```

```
Your branch is up-to-date with 'origin/master'.
Your branch is up-to-date with 'origin/master'.
Merge made by the 'recursive' strategy.
 src/ios/AppContext.swift                           |  24 ++-
 src/ios/JXcoreExtension.m                          |   2 +-
 src/ios/Testing/AppContextTests.swift              |   6 +-
 .../jxcore/bv_tests/testPouchDBCheckpointPlugin.js |  21 +-
 test/www/jxcore/bv_tests/testSSDPServer.js         |  42 ++--
 test/www/jxcore/bv_tests/testTests.js              |  49 ++++-
 test/www/jxcore/bv_tests/testThaliManager.js       |  43 ++--
 test/www/jxcore/bv_tests/testThaliMobile.js        | 156 +++++++--------
 .../bv_tests/testThaliMobileNativeWrapper.js       |  32 ++-
 .../jxcore/bv_tests/testThaliNotificationAction.js | 221 +++++++++++----------
 .../jxcore/bv_tests/testThaliNotificationClient.js | 182 ++++++++---------
 .../jxcore/bv_tests/testThaliNotificationLocal.js  | 140 ++++++-------
 .../jxcore/bv_tests/testThaliNotificationServer.js |   2 +
 test/www/jxcore/bv_tests/testThaliPeerAction.js    |  59 +++---
 .../www/jxcore/bv_tests/testThaliPeerDictionary.js |   8 +-
 .../jxcore/bv_tests/testThaliPeerPoolInterface.js  |   7 +-
 .../jxcore/bv_tests/testThaliPeerPoolOneAtATime.js |  32 +--
 .../testThaliPullReplicationFromNotification.js    |  28 +--
 .../testThaliSendNotificationBasedOnReplication.js |  98 ++++-----
 .../jxcore/bv_tests/testThaliWifiInfrastructure.js | 149 +++++++-------
 test/www/jxcore/lib/CoordinatedClient.js           |   2 +-
 test/www/jxcore/lib/sinonTest.js                   |  31 +++
 test/www/jxcore/lib/thaliTape.js                   |   3 +-
 test/www/jxcore/runTests.js                        |   6 +
 thali/NextGeneration/thaliMobile.js                |   6 +-
 thali/package.json                                 |   2 +-
 26 files changed, 694 insertions(+), 657 deletions(-)
 create mode 100644 test/www/jxcore/lib/sinonTest.js

Already on 'master'
Already on 'master'
Note: checking out 'bdf46e2'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at bdf46e2... rerun, temporary turn off desktop tests

```

```

start build.sh

-- Environment:
Cordova version: 6.4.0
Node version: v6.9.1
JXcore version: v0.3.1.10
JXcore engine: Google V8 v3.14.5.9
xcodebuild version: Xcode 8.2.1


start setUpDesktop.sh

start preparing TestServer
thali-test-server@0.0.1 /Users/thali/Github/Thali_CordovaPlugin/test/TestServer
├── bluebird@3.4.6 
├─┬ express@4.13.3 
│ ├─┬ accepts@1.2.13 
│ │ ├─┬ mime-types@2.1.15 
│ │ │ └── mime-db@1.27.0 
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
│ ├─┬ type-is@1.6.15 
│ │ └── media-typer@0.3.0 
│ ├── utils-merge@1.0.0 
│ └── vary@1.0.1 
├─┬ fs-extra-promise@0.2.0 
│ ├── bluebird@2.11.0 
│ └─┬ fs-extra@0.21.0 
│   ├── graceful-fs@4.1.11 
│   ├── jsonfile@2.4.0 
│   └─┬ rimraf@2.6.1 
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
[33mPreparing NPM for JXcore (v0.3.1.10) for the first run[39m
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
├── forever-agent@0.6.1  (git+https://github.com/thaliproject/forever-agent.git#f9a92c7a1b7ce4da849beca32b0ec2aeb855e0fd)
│   HTTP Agent that keeps socket connections alive between keep-alive requests. Formerly part of mikeal/request, now a standalone module.
│   git+https://github.com/mikeal/forever-agent.git
│   https://github.com/mikeal/forever-agent#readme
│   git+https://github.com/thaliproject/forever-agent.git#f9a92c7a1b7ce4da849beca32b0ec2aeb855e0fd
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
├── long@3.0.3 
│   A Long class for representing a 64-bit two's-complement integer value.
│   git+https://github.com/dcodeIO/long.js.git
│   https://github.com/dcodeIO/long.js#readme
├── multiplex@6.7.0 
│   A binary stream multiplexer. Stream multiple streams of binary data over a single binary stream.
│   git+https://github.com/maxogden/multiplex.git
│   https://github.com/maxogden/multiplex
├── node-ssdp@2.6.5  (git+https://github.com/thaliproject/node-ssdp.git#3a5909e201aee401f48965e378eb2ff0e2f9e027)
│   A node.js SSDP client and server library.
│   git+ssh://git@github.com/diversario/node-ssdp.git
│   https://github.com/diversario/node-ssdp#readme
│   git+https://github.com/thaliproject/node-ssdp.git#3a5909e201aee401f48965e378eb2ff0e2f9e027
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
│ └── q@1.5.0 
├── end-with@1.0.2 
├── findit@2.0.0 
├─┬ fs-extra-promise@0.2.0 
│ ├── bluebird@2.11.0 
│ └─┬ fs-extra@0.21.0 
│   ├── graceful-fs@4.1.11 
│   ├── jsonfile@2.4.0 
│   └─┬ rimraf@2.6.1 
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
│ ├── aws4@1.6.0 
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
│ │ └─┬ async@2.3.0 
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
│ │ ├─┬ is-my-json-valid@2.16.0 
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
│ │ ├─┬ jsprim@1.4.0 
│ │ │ ├── assert-plus@1.0.0 
│ │ │ ├── extsprintf@1.0.2 
│ │ │ ├── json-schema@0.2.3 
│ │ │ └── verror@1.3.6 
│ │ └─┬ sshpk@1.11.0 
│ │   ├── asn1@0.2.3 
│ │   ├── assert-plus@1.0.0 
│ │   ├─┬ dashdash@1.14.1 
│ │   │ └── assert-plus@1.0.0 
│ │   └─┬ getpass@0.1.6 
│ │     └── assert-plus@1.0.0 
│ ├── is-typedarray@1.0.0 
│ ├── isstream@0.1.2 
│ ├── json-stringify-safe@5.0.1 
│ ├─┬ mime-types@2.1.15 
│ │ └── mime-db@1.27.0 
│ ├── oauth-sign@0.8.2 
│ ├── qs@6.2.3 
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
└─┬ xcode@0.9.0  (git+https://github.com/alunny/node-xcode.git#4cca2f6225c391b63324e6eb53421560649d4f98)
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
├── forever-agent@0.6.1  (git+https://github.com/thaliproject/forever-agent.git#f9a92c7a1b7ce4da849beca32b0ec2aeb855e0fd)
│   HTTP Agent that keeps socket connections alive between keep-alive requests. Formerly part of mikeal/request, now a standalone module.
│   git+https://github.com/mikeal/forever-agent.git
│   https://github.com/mikeal/forever-agent#readme
│   git+https://github.com/thaliproject/forever-agent.git#f9a92c7a1b7ce4da849beca32b0ec2aeb855e0fd
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
├── node-ssdp@2.6.5  (git+https://github.com/thaliproject/node-ssdp.git#3a5909e201aee401f48965e378eb2ff0e2f9e027)
│   A node.js SSDP client and server library.
│   git+ssh://git@github.com/diversario/node-ssdp.git
│   https://github.com/diversario/node-ssdp#readme
│   git+https://github.com/thaliproject/node-ssdp.git#3a5909e201aee401f48965e378eb2ff0e2f9e027
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
end desktop tests


remove the previous build result (if any) to start from a clean state.

start setUpTests.sh

start preparing ThaliTest Cordova project
install@0.0.1 /Users/thali/Github/testBuild/thali/install
├── bluebird@3.4.6 
├─┬ child-process-promise@1.1.0 
│ └── q@1.5.0 
├── end-with@1.0.2 
├── findit@2.0.0 
├─┬ fs-extra-promise@0.2.0 
│ ├── bluebird@2.11.0 
│ └─┬ fs-extra@0.21.0 
│   ├── graceful-fs@4.1.11 
│   ├── jsonfile@2.4.0 
│   └─┬ rimraf@2.6.1 
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
│ ├── aws4@1.6.0 
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
│ │ └─┬ async@2.3.0 
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
│ │ ├─┬ is-my-json-valid@2.16.0 
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
│ │ ├─┬ jsprim@1.4.0 
│ │ │ ├── assert-plus@1.0.0 
│ │ │ ├── extsprintf@1.0.2 
│ │ │ ├── json-schema@0.2.3 
│ │ │ └── verror@1.3.6 
│ │ └─┬ sshpk@1.11.0 
│ │   ├── asn1@0.2.3 
│ │   ├── assert-plus@1.0.0 
│ │   ├─┬ dashdash@1.14.1 
│ │   │ └── assert-plus@1.0.0 
│ │   └─┬ getpass@0.1.6 
│ │     └── assert-plus@1.0.0 
│ ├── is-typedarray@1.0.0 
│ ├── isstream@0.1.2 
│ ├── json-stringify-safe@5.0.1 
│ ├─┬ mime-types@2.1.15 
│ │ └── mime-db@1.27.0 
│ ├── oauth-sign@0.8.2 
│ ├── qs@6.2.3 
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
└─┬ xcode@0.9.0  (git+https://github.com/alunny/node-xcode.git#4cca2f6225c391b63324e6eb53421560649d4f98)
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
thali-test-server@0.0.1 /Users/thali/Github/testBuild/test/TestServer
├── bluebird@3.4.6 
├─┬ express@4.13.3 
│ ├─┬ accepts@1.2.13 
│ │ ├─┬ mime-types@2.1.15 
│ │ │ └── mime-db@1.27.0 
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
│ ├─┬ type-is@1.6.15 
│ │ └── media-typer@0.3.0 
│ ├── utils-merge@1.0.0 
│ └── vary@1.0.1 
├─┬ fs-extra-promise@0.2.0 
│ ├── bluebird@2.11.0 
│ └─┬ fs-extra@0.21.0 
│   ├── graceful-fs@4.1.11 
│   ├── jsonfile@2.4.0 
│   └─┬ rimraf@2.6.1 
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

Using detached cordova-create
Creating a new cordova project.
start installing SSDPReplacer
SSDPReplacer@0.0.1 /Users/thali/Github/testBuild/thali/install/SSDPReplacer
├── bluebird@3.4.6 
├── end-with@1.0.2 
├── findit@2.0.0 
├─┬ fs-extra-promise@0.2.0 
│ ├── bluebird@2.11.0 
│ └─┬ fs-extra@0.21.0 
│   ├── graceful-fs@4.1.11 
│   ├── jsonfile@2.4.0 
│   └─┬ rimraf@2.6.1 
│     └─┬ glob@7.1.1 
│       ├── fs.realpath@1.0.0 
│       ├─┬ inflight@1.0.6 
│       │ └── wrappy@1.0.2 
│       ├── inherits@2.0.3 
│       ├─┬ minimatch@3.0.3 
│       │ └─┬ brace-expansion@1.1.6 
│       │   ├── balanced-match@0.4.2 
│       │   └── concat-map@0.0.1 
│       ├── once@1.4.0 
│       └── path-is-absolute@1.0.1 
├── node-uuid@1.4.7 
└─┬ randomstring@1.1.5 
  └── array-uniq@1.0.2 

end installing SSDPReplacer

end preparing ThaliTest Cordova project


start adding Android platform into ThaliTest
Adding android project...
Creating Cordova project for the Android platform:
	Path: platforms/android
	Package: com.rockwellautomation.thalitest
	Name: ThaliTest
	Activity: MainActivity
	Android target: android-24
Subproject Path: CordovaLib
Android project created with cordova-android@6.0.0
Installing "ssdp-replacer-hook" for android
ANDROID_HOME=/Users/thali/Library/Android/sdk
JAVA_HOME=/Library/Java/JavaVirtualMachines/jdk1.8.0_102.jdk/Contents/Home
Subproject Path: CordovaLib
Starting a new Gradle Daemon for this build (subsequent builds will be faster).
Incremental java compilation is an incubating feature.
:clean
:CordovaLib:clean

BUILD SUCCESSFUL

Total time: 13.719 secs
Discovered plugin "cordova-plugin-whitelist" in config.xml. Adding it to the project
Fetching plugin "cordova-plugin-whitelist@1" via npm
Installing "cordova-plugin-whitelist" for android
ANDROID_HOME=/Users/thali/Library/Android/sdk
JAVA_HOME=/Library/Java/JavaVirtualMachines/jdk1.8.0_102.jdk/Contents/Home
Subproject Path: CordovaLib
Incremental java compilation is an incubating feature.
:clean
:CordovaLib:clean

BUILD SUCCESSFUL

Total time: 2.264 secs

               This plugin is only applicable for versions of cordova-android greater than 4.0. If you have a previous platform version, you do *not* need this plugin since the whitelist will be built in.
          
end adding Android platform


start adding iOS platform into ThaliTest
Adding ios project...
Creating Cordova project for the iOS platform:
	Path: platforms/ios
	Package: com.rockwellautomation.thalitest
	Name: ThaliTest
iOS project created with cordova-ios@4.3.1
Installing "cordova-plugin-whitelist" for ios
Installing "ssdp-replacer-hook" for ios
end adding iOS platform


start installing Thali into ThaliTest

> thali@2.1.0 prepublish /Users/thali/Github/testBuild/thali
> "/usr/local/bin/jx" install/prePublishThaliCordovaPlugin.js


> thali@2.1.0 postinstall /Users/thali/Github/ThaliTest/www/jxcore/node_modules/thali
> "/usr/local/bin/jx" installCordovaPlugin.js

Collecting Data...



Node version: v6.9.1

Cordova version: 6.4.0

Config.xml file: 

<?xml version='1.0' encoding='utf-8'?>
<widget id="com.rockwellautomation.thalitest" version="1.0.0" xmlns="http://www.w3.org/ns/widgets" xmlns:cdv="http://cordova.apache.org/ns/1.0">
    <name>ThaliTest</name>
    <description>
        A sample Apache Cordova application that responds to the deviceready event.
    </description>
    <author email="dev@cordova.apache.org" href="http://cordova.io">
        Apache Cordova Team
    </author>
    <content src="index.html" />
    <plugin name="cordova-plugin-whitelist" spec="1" />
    <access origin="*" />
    <allow-intent href="http://*/*" />
    <allow-intent href="https://*/*" />
    <allow-intent href="tel:*" />
    <allow-intent href="sms:*" />
    <allow-intent href="mailto:*" />
    <allow-intent href="geo:*" />
    <platform name="android">
        <allow-intent href="market:*" />
    </platform>
    <platform name="ios">
        <allow-intent href="itms:*" />
        <allow-intent href="itms-apps:*" />
    </platform>
</widget>


Plugins: 

cordova-plugin-whitelist,ssdp-replacer-hook

Android platform:

Available Android targets:
----------
id: 1 or "android-16"
     Name: Android 4.1.2
     Type: Platform
     API level: 16
     Revision: 5
     Skins: HVGA, QVGA, WQVGA400, WQVGA432, WSVGA, WVGA800 (default), WVGA854, WXGA720, WXGA800, WXGA800-7in
 Tag/ABIs : no ABIs.
----------
id: 2 or "android-17"
     Name: Android 4.2.2
     Type: Platform
     API level: 17
     Revision: 3
     Skins: HVGA, QVGA, WQVGA400, WQVGA432, WSVGA, WVGA800 (default), WVGA854, WXGA720, WXGA800, WXGA800-7in
 Tag/ABIs : no ABIs.
----------
id: 3 or "android-18"
     Name: Android 4.3.1
     Type: Platform
     API level: 18
     Revision: 3
     Skins: HVGA, QVGA, WQVGA400, WQVGA432, WSVGA, WVGA800 (default), WVGA854, WXGA720, WXGA800, WXGA800-7in
 Tag/ABIs : no ABIs.
----------
id: 4 or "android-19"
     Name: Android 4.4.2
     Type: Platform
     API level: 19
     Revision: 4
     Skins: HVGA, QVGA, WQVGA400, WQVGA432, WSVGA, WVGA800 (default), WVGA854, WXGA720, WXGA800, WXGA800-7in
 Tag/ABIs : no ABIs.
----------
id: 5 or "android-20"
     Name: Android 4.4W.2
     Type: Platform
     API level: 20
     Revision: 2
     Skins: HVGA, QVGA, WQVGA400, WQVGA432, WSVGA, WVGA800 (default), WVGA854, WXGA720, WXGA800, WXGA800-7in
 Tag/ABIs : no ABIs.
----------
id: 6 or "android-21"
     Name: Android 5.0.1
     Type: Platform
     API level: 21
     Revision: 2
     Skins: HVGA, QVGA, WQVGA400, WQVGA432, WSVGA, WVGA800 (default), WVGA854, WXGA720, WXGA800, WXGA800-7in
 Tag/ABIs : no ABIs.
----------
id: 7 or "android-22"
     Name: Android 5.1.1
     Type: Platform
     API level: 22
     Revision: 2
     Skins: HVGA, QVGA, WQVGA400, WQVGA432, WSVGA, WVGA800 (default), WVGA854, WXGA720, WXGA800, WXGA800-7in
 Tag/ABIs : no ABIs.
----------
id: 8 or "android-23"
     Name: Android 6.0
     Type: Platform
     API level: 23
     Revision: 3
     Skins: HVGA, QVGA, WQVGA400, WQVGA432, WSVGA, WVGA800 (default), WVGA854, WXGA720, WXGA800, WXGA800-7in
 Tag/ABIs : no ABIs.
----------
id: 9 or "android-24"
     Name: Android 7.0
     Type: Platform
     API level: 24
     Revision: 2
     Skins: HVGA, QVGA, WQVGA400, WQVGA432, WSVGA, WVGA800 (default), WVGA854, WXGA720, WXGA800, WXGA800-7in
 Tag/ABIs : no ABIs.
----------
id: 10 or "android-25"
     Name: Android 7.1.1
     Type: Platform
     API level: 25
     Revision: 3
     Skins: HVGA, QVGA, WQVGA400, WQVGA432, WSVGA, WVGA800 (default), WVGA854, WXGA720, WXGA800, WXGA800-7in
 Tag/ABIs : no ABIs.
----------
id: 11 or "Google Inc.:Google APIs:23"
     Name: Google APIs
     Type: Add-On
     Vendor: Google Inc.
     Revision: 1
     Description: Android + Google APIs
     Based on Android 6.0 (API level 23)
     Libraries:
      * com.android.future.usb.accessory (usb.jar)
          API for USB Accessories
      * com.google.android.media.effects (effects.jar)
          Collection of video effects
      * com.google.android.maps (maps.jar)
          API for Google Maps
     Skins: HVGA, QVGA, WQVGA400, WQVGA432, WSVGA, WVGA800 (default), WVGA854, WXGA720, WXGA800, WXGA800-7in
 Tag/ABIs : no ABIs.

iOS platform:

Xcode 8.2.1
Build version 8C1002



npm
 http request
 GET http://192.168.1.100:4873/end-with

npm http request GET http://192.168.1.100:4873/bluebird

npm
 http request GET http://192.168.1.100:4873/findit
npm http request GET http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/child-process-promise
npm http request GET http://192.168.1.100:4873/fs-extra-promise

npm http request GET http://192.168.1.100:4873/jxc

npm http request
 GET http://192.168.1.100:4873/lie

npm http request GET http://192.168.1.100:4873/request

npm http
 request GET http://192.168.1.100:4873/unzip

npm http 
request GET http://192.168.1.100:4873/node-uuid

npm http 304 http://192.168.1.100:4873/child-process-promise

npm
 http 304 http://192.168.1.100:4873/randomstring

npm http 304
 http://192.168.1.100:4873/end-with

npm 
http 304 http://192.168.1.100:4873/findit

npm http 304 http://192.168.1.100:4873/lie

npm http
 304 http://192.168.1.100:4873/unzip

npm http 304 http://192.168.1.100:4873/request

npm http 304 http://192.168.1.100:4873/fs-extra-promise

npm http 304 http://192.168.1.100:4873/node-uuid

npm http 304 http://192.168.1.100:4873/jxc

npm http 304 http://192.168.1.100:4873/bluebird

npm http request
 GET http://192.168.1.100:4873/q

npm
 
http
 
304
 http://192.168.1.100:4873/q

npm http request
 GET http://192.168.1.100:4873/fs-extra

npm http 304 http://192.168.1.100:4873/fs-extra

npm 
http request GET http://192.168.1.100:4873/graceful-fs

npm http request GET http://192.168.1.100:4873/jsonfile

npm http 
request GET http://192.168.1.100:4873/rimraf

npm
 http 304 http://192.168.1.100:4873/graceful-fs

npm http 304 http://192.168.1.100:4873/jsonfile

npm http 304 http://192.168.1.100:4873/rimraf

npm http request GET http://192.168.1.100:4873/glob

npm http 304 http://192.168.1.100:4873/glob

npm 
http request GET http://192.168.1.100:4873/fs.realpath

npm http request
 GET http://192.168.1.100:4873/inherits

npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/path-is-absolute

npm http request GET http://192.168.1.100:4873/once

npm http 304 http://192.168.1.100:4873/inherits

npm http 304 http://192.168.1.100:4873/fs.realpath

npm http 
304 http://192.168.1.100:4873/minimatch

npm http 304 http://192.168.1.100:4873/inflight
npm http 304 http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/once

npm http
 request GET http://192.168.1.100:4873/wrappy

npm http 304 http://192.168.1.100:4873/wrappy

npm http
 request GET http://192.168.1.100:4873/brace-expansion

npm http 304
 http://192.168.1.100:4873/brace-expansion

npm http request GET http://192.168.1.100:4873/balanced-match

npm http
 request GET http://192.168.1.100:4873/concat-map

npm http 304
 http://192.168.1.100:4873/balanced-match

npm http
 304 http://192.168.1.100:4873/concat-map

npm http request GET http://192.168.1.100:4873/adm-zip
npm http request GET http://192.168.1.100:4873/progress

npm http 304 http://192.168.1.100:4873/adm-zip

npm 
http 304 http://192.168.1.100:4873/progress

npm
 
http request GET http://192.168.1.100:4873/immediate

npm http 304 http://192.168.1.100:4873/immediate

npm http
 
request
 GET http://192.168.1.100:4873/array-uniq

npm http 304 http://192.168.1.100:4873/array-uniq

npm 
http request GET http://192.168.1.100:4873/aws-sign2

npm http request GET http://192.168.1.100:4873/aws4

npm
 http request GET http://192.168.1.100:4873/bl

npm 
http request GET http://192.168.1.100:4873/caseless

npm http request GET http://192.168.1.100:4873/combined-stream

npm
 http request GET http://192.168.1.100:4873/extend

npm http request GET http://192.168.1.100:4873/forever-agent

npm http request
 GET http://192.168.1.100:4873/form-data

npm http request GET http://192.168.1.100:4873/har-validator

npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/is-typedarray
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/json-stringify-safe

npm http request GET http://192.168.1.100:4873/mime-types

npm http request GET http://192.168.1.100:4873/oauth-sign

npm http request GET http://192.168.1.100:4873/qs

npm http request GET http://192.168.1.100:4873/stringstream

npm
 
http
 
request
 GET http://192.168.1.100:4873/tough-cookie

npm
 http request GET http://192.168.1.100:4873/tunnel-agent

npm http
 304 http://192.168.1.100:4873/aws-sign2

npm http
 304 http://192.168.1.100:4873/aws4

npm 
http 304 http://192.168.1.100:4873/caseless

npm http 304 http://192.168.1.100:4873/bl

npm http 304 http://192.168.1.100:4873/forever-agent

npm http 304 http://192.168.1.100:4873/combined-stream

npm http 304 http://192.168.1.100:4873/http-signature

npm http 304 http://192.168.1.100:4873/har-validator

npm
 http 304 http://192.168.1.100:4873/is-typedarray

npm http 304 http://192.168.1.100:4873/extend

npm http 304 http://192.168.1.100:4873/isstream

npm http 304 http://192.168.1.100:4873/form-data

npm http 304 http://192.168.1.100:4873/hawk

npm http 304 http://192.168.1.100:4873/mime-types

npm http
 304 http://192.168.1.100:4873/oauth-sign

npm http
 304 http://192.168.1.100:4873/stringstream

npm http
 304 http://192.168.1.100:4873/qs

npm http
 304 http://192.168.1.100:4873/tunnel-agent

npm http 304 http://192.168.1.100:4873/tough-cookie

npm http 304 http://192.168.1.100:4873/json-stringify-safe

npm http fetch GET http://192.168.1.100:4873/forever-agent/-/forever-agent-0.6.1.tgz

npm http fetch 200 http://192.168.1.100:4873/forever-agent/-/forever-agent-0.6.1.tgz

npm
 http request GET http://192.168.1.100:4873/readable-stream

npm
 
http
 
304
 http://192.168.1.100:4873/readable-stream

npm http request
 GET http://192.168.1.100:4873/core-util-is

npm
 http request GET http://192.168.1.100:4873/isarray

npm 
http request GET http://192.168.1.100:4873/process-nextick-args

npm http 
request GET http://192.168.1.100:4873/string_decoder

npm
 http request GET http://192.168.1.100:4873/util-deprecate

npm http
 304 http://192.168.1.100:4873/core-util-is

npm http 304 http://192.168.1.100:4873/isarray

npm
 http 304
 http://192.168.1.100:4873/process-nextick-args

npm
 http 304 http://192.168.1.100:4873/string_decoder

npm 
http 304 http://192.168.1.100:4873/util-deprecate

npm http
 request GET http://192.168.1.100:4873/delayed-stream

npm http
 304 http://192.168.1.100:4873/delayed-stream

npm http request GET http://192.168.1.100:4873/async

npm
 
http
 
304
 http://192.168.1.100:4873/async

npm
 
http
 request GET http://192.168.1.100:4873/lodash

npm
 
http
 
304
 http://192.168.1.100:4873/lodash

npm http
 request GET http://192.168.1.100:4873/mime-db

npm http 304 http://192.168.1.100:4873/mime-db

npm 
http request GET http://192.168.1.100:4873/chalk

npm
 http request GET http://192.168.1.100:4873/is-my-json-valid

npm http request GET http://192.168.1.100:4873/commander

npm http 
request GET http://192.168.1.100:4873/pinkie-promise

npm http 304 http://192.168.1.100:4873/chalk

npm http 
304 http://192.168.1.100:4873/is-my-json-valid

npm http 304 http://192.168.1.100:4873/commander

npm http 304 http://192.168.1.100:4873/pinkie-promise

npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi

npm
 http request GET http://192.168.1.100:4873/strip-ansi

npm http
 request GET http://192.168.1.100:4873/supports-color

npm http 304 http://192.168.1.100:4873/ansi-styles

npm http 304 http://192.168.1.100:4873/escape-string-regexp

npm http 304 http://192.168.1.100:4873/strip-ansi

npm 
http 304 http://192.168.1.100:4873/has-ansi

npm http 304 http://192.168.1.100:4873/supports-color

npm http request GET http://192.168.1.100:4873/ansi-regex

npm http 304 http://192.168.1.100:4873/ansi-regex

npm http request GET http://192.168.1.100:4873/graceful-readlink

npm http 304 http://192.168.1.100:4873/graceful-readlink

npm http request GET http://192.168.1.100:4873/generate-function

npm http request GET http://192.168.1.100:4873/generate-object-property

npm http request GET http://192.168.1.100:4873/jsonpointer

npm
 http request GET http://192.168.1.100:4873/xtend

npm http 304 http://192.168.1.100:4873/generate-function

npm http 304 http://192.168.1.100:4873/generate-object-property

npm http 304 http://192.168.1.100:4873/jsonpointer

npm http 304 http://192.168.1.100:4873/xtend

npm http request GET http://192.168.1.100:4873/is-property

npm http 304 http://192.168.1.100:4873/is-property

npm http request GET http://192.168.1.100:4873/pinkie

npm http 304 http://192.168.1.100:4873/pinkie

npm http request GET http://192.168.1.100:4873/hoek

npm
 http request GET http://192.168.1.100:4873/cryptiles

npm http request GET http://192.168.1.100:4873/sntp

npm http request GET http://192.168.1.100:4873/boom

npm http 304 http://192.168.1.100:4873/hoek

npm http 304 http://192.168.1.100:4873/sntp

npm
 
http
 
304 http://192.168.1.100:4873/cryptiles

npm http 304 http://192.168.1.100:4873/boom

npm 
http request GET http://192.168.1.100:4873/assert-plus

npm 
http request GET http://192.168.1.100:4873/jsprim

npm http request GET http://192.168.1.100:4873/sshpk

npm http 304 http://192.168.1.100:4873/assert-plus

npm http 304 http://192.168.1.100:4873/jsprim

npm http 304 http://192.168.1.100:4873/sshpk

npm http request GET http://192.168.1.100:4873/json-schema

npm http
 request GET http://192.168.1.100:4873/verror

npm
 http request GET http://192.168.1.100:4873/extsprintf

npm http
 304 http://192.168.1.100:4873/json-schema

npm http
 304 http://192.168.1.100:4873/extsprintf

npm http
 304 http://192.168.1.100:4873/verror

npm http request GET http://192.168.1.100:4873/asn1

npm http 
request GET http://192.168.1.100:4873/dashdash

npm http
 request GET http://192.168.1.100:4873/getpass

npm http 304 http://192.168.1.100:4873/getpass

npm 
http 304 http://192.168.1.100:4873/asn1

npm http 304 http://192.168.1.100:4873/dashdash

npm http
 request GET http://192.168.1.100:4873/punycode

npm http 304 http://192.168.1.100:4873/punycode

npm http
 request GET http://192.168.1.100:4873/pullstream

npm 
http request GET http://192.168.1.100:4873/fstream

npm http request GET http://192.168.1.100:4873/binary

npm
 
http request GET http://192.168.1.100:4873/setimmediate

npm
 
http
 
request GET http://192.168.1.100:4873/match-stream

npm http 304 http://192.168.1.100:4873/pullstream

npm
 
http 304
 http://192.168.1.100:4873/fstream

npm http 304 http://192.168.1.100:4873/binary

npm
 http 304 http://192.168.1.100:4873/setimmediate

npm
 
http
 
304
 http://192.168.1.100:4873/match-stream

npm 
http
 request
 GET http://192.168.1.100:4873/chainsaw

npm
 
http 
request GET http://192.168.1.100:4873/buffers

npm
 
http
 
304
 http://192.168.1.100:4873/chainsaw

npm
 
http
 
304 http://192.168.1.100:4873/buffers

npm
 
http
 
request
 GET http://192.168.1.100:4873/traverse

npm http 304 http://192.168.1.100:4873/traverse

npm http request GET http://192.168.1.100:4873/mkdirp

npm http 
304 http://192.168.1.100:4873/mkdirp

npm http request GET http://192.168.1.100:4873/natives

npm http 
304 http://192.168.1.100:4873/natives

npm http request GET http://192.168.1.100:4873/minimist

npm http 304 http://192.168.1.100:4873/minimist

npm http request GET http://192.168.1.100:4873/over

npm http
 request GET http://192.168.1.100:4873/slice-stream

npm http 304 http://192.168.1.100:4873/over

npm
 http 304 http://192.168.1.100:4873/slice-stream

npm http request GET http://192.168.1.100:4873/pegjs

npm http request GET http://192.168.1.100:4873/simple-plist

npm http 304 http://192.168.1.100:4873/pegjs

npm http
 304 http://192.168.1.100:4873/simple-plist

npm http request GET http://192.168.1.100:4873/plist

npm http request GET http://192.168.1.100:4873/bplist-parser

npm http request GET http://192.168.1.100:4873/bplist-creator

npm http 304 http://192.168.1.100:4873/plist

npm http 304 http://192.168.1.100:4873/bplist-parser
npm http 304 http://192.168.1.100:4873/bplist-creator

npm http request
 GET http://192.168.1.100:4873/stream-buffers

npm http 304 http://192.168.1.100:4873/stream-buffers

npm http request GET http://192.168.1.100:4873/base64-js

npm http request GET http://192.168.1.100:4873/xmldom
npm http request GET http://192.168.1.100:4873/xmlbuilder

npm 
http 304 http://192.168.1.100:4873/base64-js

npm http
 304 http://192.168.1.100:4873/xmlbuilder

npm http 304
 http://192.168.1.100:4873/xmldom

install@0.0.1
│ /Users/thali/Github/ThaliTest/www/jxcore/node_modules/thali/install
│ Used to handle installing the Thali NPM package correctly into Cordova
├── bluebird@3.4.6 
│   Full featured Promises/A+ implementation with exceptionally good performance
│   git://github.com/petkaantonov/bluebird.git
│   https://github.com/petkaantonov/bluebird
├─┬ child-process-promise@1.1.0 
│ │ Simple wrapper around the "child_process" module that makes use of promises
│ │ git+https://github.com/patrick-steele-idem/child-process-promise.git
│ │ https://github.com/patrick-steele-idem/child-process-promise
│ └── q@1.5.0 
│     A library for promises (CommonJS/Promises/A,B,D)
│     git://github.com/kriskowal/q.git
│     https://github.com/kriskowal/q
├── end-with@1.0.2 
│   Determines whether a string ends with the characters of another string.
│   git+https://github.com/gearcase/end-with.git
│   https://github.com/gearcase/end-with#readme
├── findit@2.0.0 
│   walk a directory tree recursively with events
│   git+ssh://git@github.com/substack/node-findit.git
│   https://github.com/substack/node-findit
├─┬ fs-extra-promise@0.2.0 
│ │ Node file system library and fs-extra module promisified with bluebird
│ │ git+https://github.com/overlookmotel/fs-extra-promise.git
│ │ https://github.com/overlookmotel/fs-extra-promise
│ ├── bluebird@2.11.0 
│ │   Full featured Promises/A+ implementation with exceptionally good performance
│ │   git://github.com/petkaantonov/bluebird.git
│ │   https://github.com/petkaantonov/bluebird
│ └─┬ fs-extra@0.21.0 
│   │ fs-extra contains methods that aren't included in the vanilla Node.js fs package. Such as mkdir -p, cp -r, and rm -rf.
│   │ git+https://github.com/jprichardson/node-fs-extra.git
│   │ https://github.com/jprichardson/node-fs-extra
│   ├── graceful-fs@4.1.11 
│   │   A drop-in replacement for fs, making various improvements.
│   │   git+https://github.com/isaacs/node-graceful-fs.git
│   │   https://github.com/isaacs/node-graceful-fs#readme
│   ├─┬ jsonfile@2.4.0 
│   │ │ Easily read/write JSON files.
│   │ │ git+ssh://git@github.com/jprichardson/node-jsonfile.git
│   │ │ https://github.com/jprichardson/node-jsonfile#readme
│   │ └── graceful-fs@4.1.11 
│   │     A drop-in replacement for fs, making various improvements.
│   │     git+https://github.com/isaacs/node-graceful-fs.git
│   │     https://github.com/isaacs/node-graceful-fs#readme
│   └─┬ rimraf@2.6.1 
│     │ A deep deletion module for node (like `rm -rf`)
│     │ git://github.com/isaacs/rimraf.git
│     │ https://github.com/isaacs/rimraf#readme
│     └─┬ glob@7.1.1 
│       │ a little globber
│       │ git://github.com/isaacs/node-glob.git
│       │ https://github.com/isaacs/node-glob#readme
│       ├── fs.realpath@1.0.0 
│       │   Use node's fs.realpath, but fall back to the JS implementation if the native one fails
│       │   git+https://github.com/isaacs/fs.realpath.git
│       │   https://github.com/isaacs/fs.realpath#readme
│       ├─┬ inflight@1.0.6 
│       │ │ Add callbacks to requests in flight to avoid async duplication
│       │ │ git+https://github.com/npm/inflight.git
│       │ │ https://github.com/isaacs/inflight
│       │ ├── once@1.4.0 
│       │ │   Run a function exactly one time
│       │ │   git://github.com/isaacs/once.git
│       │ │   https://github.com/isaacs/once#readme
│       │ └── wrappy@1.0.2 
│       │     Callback wrapping utility
│       │     git+https://github.com/npm/wrappy.git
│       │     https://github.com/npm/wrappy
│       ├── inherits@2.0.3 
│       │   Browser-friendly inheritance fully compatible with standard node.js inherits()
│       │   git://github.com/isaacs/inherits.git
│       │   https://github.com/isaacs/inherits#readme
│       ├─┬ minimatch@3.0.3 
│       │ │ a glob matcher in javascript
│       │ │ git://github.com/isaacs/minimatch.git
│       │ │ https://github.com/isaacs/minimatch#readme
│       │ └─┬ brace-expansion@1.1.6 
│       │   │ Brace expansion as known from sh/bash
│       │   │ git://github.com/juliangruber/brace-expansion.git
│       │   │ https://github.com/juliangruber/brace-expansion
│       │   ├── balanced-match@0.4.2 
│       │   │   Match balanced character pairs, like "{" and "}"
│       │   │   git://github.com/juliangruber/balanced-match.git
│       │   │   https://github.com/juliangruber/balanced-match
│       │   └── concat-map@0.0.1 
│       │       concatenative mapdashery
│       │       git://github.com/substack/node-concat-map.git
│       │       https://github.com/substack/node-concat-map
│       ├─┬ once@1.4.0 
│       │ │ Run a function exactly one time
│       │ │ git://github.com/isaacs/once.git
│       │ │ https://github.com/isaacs/once#readme
│       │ └── wrappy@1.0.2 
│       │     Callback wrapping utility
│       │     git+https://github.com/npm/wrappy.git
│       │     https://github.com/npm/wrappy
│       └── path-is-absolute@1.0.1 
│           Node.js 0.12 path.isAbsolute() ponyfill
│           git+https://github.com/sindresorhus/path-is-absolute.git
│           https://github.com/sindresorhus/path-is-absolute#readme
├─┬ jxc@1.0.14 
│ │ JXcore-cordova plugin helper
│ │ git+https://github.com/jxcore/jxc.git
│ │ https://github.com/jxcore/jxc#readme
│ └─┬ jxtools@0.0.4  (git+https://github.com/ktrzeciaknubisa/jxtools.git#644cf31ea259cb65a97e5c3ed5ea1236dba298a3)
│   │ JXcore Tools
│   │ git+https://github.com/ktrzeciaknubisa/jxtools.git
│   │ https://github.com/ktrzeciaknubisa/jxtools
│   │ git+https://github.com/ktrzeciaknubisa/jxtools.git
│   ├── adm-zip@0.4.7 
│   │   A Javascript implementation of zip for nodejs. Allows user to create or extract zip files both in memory or to/from disk
│   │   git+https://github.com/cthackers/adm-zip.git
│   │   http://github.com/cthackers/adm-zip
│   └── progress@1.1.8 
│       Flexible ascii progress bar
│       git://github.com/visionmedia/node-progress.git
│       https://github.com/visionmedia/node-progress
├─┬ lie@3.1.0 
│ │ A basic but performant promise implementation
│ │ git+https://github.com/calvinmetcalf/lie.git
│ │ https://github.com/calvinmetcalf/lie#readme
│ └── immediate@3.0.6 
│     A cross browser microtask library
│     git://github.com/calvinmetcalf/immediate.git
│     https://github.com/calvinmetcalf/immediate#readme
├── node-uuid@1.4.7 
│   Rigorous implementation of RFC4122 (v1 and v4) UUIDs.
│   git+https://github.com/broofa/node-uuid.git
│   https://github.com/broofa/node-uuid
├─┬ randomstring@1.1.5 
│ │ A module for generating random strings
│ │ git://github.com/klughammer/node-randomstring.git
│ │ https://github.com/klughammer/node-randomstring
│ └── array-uniq@1.0.2 
│     Create an array without duplicates
│     git+https://github.com/sindresorhus/array-uniq.git
│     https://github.com/sindresorhus/array-uniq
├─┬ request@2.74.0 
│ │ Simplified HTTP request client.
│ │ git+https://github.com/request/request.git
│ │ https://github.com/request/request#readme
│ ├── aws-sign2@0.6.0 
│ │   AWS signing. Originally pulled from LearnBoost/knox, maintained as vendor in request, now a standalone module.
│ │   git+https://github.com/mikeal/aws-sign.git
│ │   https://github.com/mikeal/aws-sign#readme
│ ├── aws4@1.6.0 
│ │   Signs and prepares requests using AWS Signature Version 4
│ │   git+https://github.com/mhart/aws4.git
│ │   https://github.com/mhart/aws4#readme
│ ├─┬ bl@1.1.2 
│ │ │ Buffer List: collect buffers and access with a standard readable Buffer interface, 
npm WARN install@0.0.1 No repository field.

streamable too!
│ │ │ git+https://github.com/rvagg/bl.git
│ │ │ https://github.com/rvagg/bl
│ │ └─┬ readable-stream@2.0.6 
│ │   │ Streams3, a user-land copy of the stream library from Node.js
│ │   │ git://github.com/nodejs/readable-stream.git
│ │   │ https://github.com/nodejs/readable-stream#readme
│ │   ├── core-util-is@1.0.2 
│ │   │   The `util.is*` functions introduced in Node v0.12.
│ │   │   git://github.com/isaacs/core-util-is.git
│ │   │   https://github.com/isaacs/core-util-is#readme
│ │   ├── inherits@2.0.3 
│ │   │   Browser-friendly inheritance fully compatible with standard node.js inherits()
│ │   │   git://github.com/isaacs/inherits.git
│ │   │   https://github.com/isaacs/inherits#readme
│ │   ├── isarray@1.0.0 
│ │   │   Array#isArray for older browsers
│ │   │   git://github.com/juliangruber/isarray.git
│ │   │   https://github.com/juliangruber/isarray
│ │   ├── process-nextick-args@1.0.7 
│ │   │   process.nextTick but always with args
│ │   │   git+https://github.com/calvinmetcalf/process-nextick-args.git
│ │   │   https://github.com/calvinmetcalf/process-nextick-args
│ │   ├── string_decoder@0.10.31 
│ │   │   The string_decoder module from Node core
│ │   │   git://github.com/rvagg/string_decoder.git
│ │   │   https://github.com/rvagg/string_decoder
│ │   └── util-deprecate@1.0.2 
│ │       The Node.js `util.deprecate()` function with browser support
│ │       git://github.com/TooTallNate/util-deprecate.git
│ │       https://github.com/TooTallNate/util-deprecate
│ ├── caseless@0.11.0 
│ │   Caseless object set/get/has, very useful when working with HTTP headers.
│ │   git+https://github.com/mikeal/caseless.git
│ │   https://github.com/mikeal/caseless#readme
│ ├─┬ combined-stream@1.0.5 
│ │ │ A stream that emits multiple other streams one after another.
│ │ │ git://github.com/felixge/node-combined-stream.git
│ │ │ https://github.com/felixge/node-combined-stream
│ │ └── delayed-stream@1.0.0 
│ │     Buffers events from a stream until you are ready to handle them.
│ │     git://github.com/felixge/node-delayed-stream.git
│ │     https://github.com/felixge/node-delayed-stream
│ ├── extend@3.0.0 
│ │   Port of jQuery.extend for node.js and the browser
│ │   git+https://github.com/justmoon/node-extend.git
│ │   https://github.com/justmoon/node-extend#readme
│ ├── forever-agent@0.6.1 
│ │   HTTP Agent that keeps socket connections alive between keep-alive requests. Formerly part of mikeal/request, now a standalone module.
│ │   git+https://github.com/mikeal/forever-agent.git
│ │   https://github.com/mikeal/forever-agent
│ ├─┬ form-data@1.0.1 
│ │ │ A library to create readable "multipart/form-data" streams. Can be used to submit forms and file uploads to other web applications.
│ │ │ git://github.com/form-data/form-data.git
│ │ │ https://github.com/form-data/form-data#readme
│ │ ├─┬ async@2.3.0 
│ │ │ │ Higher-order functions and common patterns for asynchronous code
│ │ │ │ git+https://github.com/caolan/async.git
│ │ │ │ https://github.com/caolan/async#readme
│ │ │ └── lodash@4.17.4 
│ │ │     Lodash modular utilities.
│ │ │     git+https://github.com/lodash/lodash.git
│ │ │     https://lodash.com/
│ │ ├── combined-stream@1.0.5 
│ │ │   A stream that emits multiple other streams one after another.
│ │ │   git://github.com/felixge/node-combined-stream.git
│ │ │   https://github.com/felixge/node-combined-stream
│ │ └── mime-types@2.1.15 
│ │     The ultimate javascript content-type utility.
│ │     git+https://github.com/jshttp/mime-types.git
│ │     https://github.com/jshttp/mime-types#readme
│ ├─┬ har-validator@2.0.6 
│ │ │ Extremely fast HTTP Archive (HAR) validator using JSON Schema
│ │ │ git+https://github.com/ahmadnassri/har-validator.git
│ │ │ https://github.com/ahmadnassri/har-validator
│ │ ├─┬ chalk@1.1.3 
│ │ │ │ Terminal string styling done right. Much color.
│ │ │ │ git+https://github.com/chalk/chalk.git
│ │ │ │ https://github.com/chalk/chalk#readme
│ │ │ ├── ansi-styles@2.2.1 
│ │ │ │   ANSI escape codes for styling strings in the terminal
│ │ │ │   git+https://github.com/chalk/ansi-styles.git
│ │ │ │   https://github.com/chalk/ansi-styles#readme
│ │ │ ├── escape-string-regexp@1.0.5 
│ │ │ │   Escape RegExp special characters
│ │ │ │   git+https://github.com/sindresorhus/escape-string-regexp.git
│ │ │ │   https://github.com/sindresorhus/escape-string-regexp
│ │ │ ├─┬ has-ansi@2.0.0 
│ │ │ │ │ Check if a string has ANSI escape codes
│ │ │ │ │ git+https://github.com/sindresorhus/has-ansi.git
│ │ │ │ │ https://github.com/sindresorhus/has-ansi
│ │ │ │ └── ansi-regex@2.1.1 
│ │ │ │     Regular expression for matching ANSI escape codes
│ │ │ │     git+https://github.com/chalk/ansi-regex.git
│ │ │ │     https://github.com/chalk/ansi-regex#readme
│ │ │ ├─┬ strip-ansi@3.0.1 
│ │ │ │ │ Strip ANSI escape codes
│ │ │ │ │ git+https://github.com/chalk/strip-ansi.git
│ │ │ │ │ https://github.com/chalk/strip-ansi
│ │ │ │ └── ansi-regex@2.1.1 
│ │ │ │     Regular expression for matching ANSI escape codes
│ │ │ │     git+https://github.com/chalk/ansi-regex.git
│ │ │ │     https://github.com/chalk/ansi-regex#readme
│ │ │ └── supports-color@2.0.0 
│ │ │     Detect whether a terminal supports color
│ │ │     git+https://github.com/chalk/supports-color.git
│ │ │     https://github.com/chalk/supports-color
│ │ ├─┬ commander@2.9.0 
│ │ │ │ the complete solution for node.js command-line programs
│ │ │ │ git+https://github.com/tj/commander.js.git
│ │ │ │ https://github.com/tj/commander.js#readme
│ │ │ └── graceful-readlink@1.0.1 
│ │ │     graceful fs.readlink
│ │ │     git://github.com/zhiyelee/graceful-readlink.git
│ │ │     https://github.com/zhiyelee/graceful-readlink
│ │ ├─┬ is-my-json-valid@2.16.0 
│ │ │ │ A JSONSchema validator that uses code generation to be extremely fast
│ │ │ │ git+https://github.com/mafintosh/is-my-json-valid.git
│ │ │ │ https://github.com/mafintosh/is-my-json-valid
│ │ │ ├── generate-function@2.0.0 
│ │ │ │   Module that helps you write generated functions in Node
│ │ │ │   git+https://github.com/mafintosh/generate-function.git
│ │ │ │   https://github.com/mafintosh/generate-function
│ │ │ ├─┬ generate-object-property@1.2.0 
│ │ │ │ │ Generate safe JS code that can used to reference a object property
│ │ │ │ │ git+https://github.com/mafintosh/generate-object-property.git
│ │ │ │ │ https://github.com/mafintosh/generate-object-property
│ │ │ │ └── is-property@1.0.2 
│ │ │ │     Tests if a JSON property can be accessed using . syntax
│ │ │ │     git://github.com/mikolalysenko/is-property.git
│ │ │ │     https://github.com/mikolalysenko/is-property
│ │ │ ├── jsonpointer@4.0.1 
│ │ │ │   Simple JSON Addressing.
│ │ │ │   git+ssh://git@github.com/janl/node-jsonpointer.git
│ │ │ │   https://github.com/janl/node-jsonpointer#readme
│ │ │ └── xtend@4.0.1 
│ │ │     extend like a boss
│ │ │     git://github.com/Raynos/xtend.git
│ │ │     https://github.com/Raynos/xtend
│ │ └─┬ pinkie-promise@2.0.1 
│ │   │ ES2015 Promise ponyfill
│ │   │ git+https://github.com/floatdrop/pinkie-promise.git
│ │   │ https://github.com/floatdrop/pinkie-promise
│ │   └─
─ pinkie@2.0.4 
│ │       Itty bitty little widdle twinkie pinkie ES2015 Promise implementation
│ │       git+https://github.com/floatdrop/pinkie.git
│ │       https://github.com/floatdrop/pinkie
│ ├─┬ hawk@3.1.3 
│ │ │ HTTP Hawk Authentication Scheme
│ │ │ git://github.com/hueniverse/hawk.git
│ │ │ https://github.com/hueniverse/hawk#readme
│ │ ├─┬ boom@2.10.1 
│ │ │ │ HTTP-friendly error objects
│ │ │ │ git://github.com/hapijs/boom.git
│ │ │ │ https://github.com/hapijs/boom#readme
│ │ │ └── hoek@2.16.3 
│ │ │     General purpose node utilities
│ │ │     git://github.com/hapijs/hoek.git
│ │ │     https://github.com/hapijs/hoek#readme
│ │ ├─┬ cryptiles@2.0.5 
│ │ │ │ General purpose crypto utilities
│ │ │ │ git://github.com/hapijs/cryptiles.git
│ │ │ │ https://github.com/hapijs/cryptiles#readme
│ │ │ └── boom@2.10.1 
│ │ │     HTTP-friendly error objects
│ │ │     git://github.com/hapijs/boom.git
│ │ │     https://github.com/hapijs/boom#readme
│ │ ├── hoek@2.16.3 
│ │ │   General purpose node utilities
│ │ │   git://github.com/hapijs/hoek.git
│ │ │   https://github.com/hapijs/hoek#readme
│ │ └─┬ sntp@1.0.9 
│ │   │ SNTP Client
│ │   │ git://github.com/hueniverse/sntp.git
│ │   │ https://github.com/hueniverse/sntp
│ │   └── hoek@2.16.3 
│ │       General purpose node utilities
│ │       git://github.com/hapijs/hoek.git
│ │       https://github.com/hapijs/hoek#readme
│ ├─┬ http-signature@1.1.1 
│ │ │ Reference implementation of Joyent's HTTP Signature scheme.
│ │ │ git://github.com/joyent/node-http-signature.git
│ │ │ https://github.com/joyent/node-http-signature/
│ │ ├── assert-plus@0.2.0 
│ │ │   Extra assertions on top of node's assert module
│ │ │   git+https://github.com/mcavage/node-assert-plus.git
│ │ │   https://github.com/mcavage/node-assert-plus#readme
│ │ ├─┬ jsprim@1.4.0 
│ │ │ │ utilities for primitive JavaScript types
│ │ │ │ git://github.com/joyent/node-jsprim.git
│ │ │ │ https://github.com/joyent/node-jsprim#readme
│ │ │ ├── assert-plus@1.0.0 
│ │ │ │   Extra assertions on top of node's assert module
│ │ │ │   git+https://github.com/mcavage/node-assert-plus.git
│ │ │ │   https://github.com/mcavage/node-assert-plus#readme
│ │ │ ├── extsprintf@1.0.2 
│ │ │ │   extended POSIX-style sprintf
│ │ │ │   git://github.com/davepacheco/node-extsprintf.git
│ │ │ │   https://github.com/davepacheco/node-extsprintf#readme
│ │ │ ├── json-schema@0.2.3 
│ │ │ │   JSON Schema validation and specifications
│ │ │ │   git+ssh://git@github.com/kriszyp/json-schema.git
│ │ │ │   https://github.com/kriszyp/json-schema#readme
│ │ │ └─┬ verror@1.3.6 
│ │ │   │ richer JavaScript errors
│ │ │   │ git://github.com/davepacheco/node-verror.git
│ │ │   │ https://github.com/davepacheco/node-verror#readme
│ │ │   └── extsprintf@1.0.2 
│ │ │       extended POSIX-style sprintf
│ │ │       git://github.com/davepacheco/node-extsprintf.git
│ │ │       https://github.com/davepacheco/node-extsprintf#readme
│ │ └─┬ sshpk@1.11.0 
│ │   │ A library for finding and using SSH public keys
│ │   │ git+https://github.com/arekinath/node-sshpk.git
│ │   │ https://github.com/arekinath/node-sshpk#readme
│ │   ├── asn1@0.2.3 
│ │   │   Contains parsers and serializers for ASN.1 (currently BER only)
│ │   │   git://github.com/mcavage/node-asn1.git
│ │   │   https://github.com/mcavage/node-asn1
│ │   ├── assert-plus@1.0.0 
│ │   │   Extra assertions on top of node's assert module
│ │   │   git+https://github.com/mcavage/node-assert-plus.git
│ │   │   https://github.com/mcavage/node-assert-plus#readme
│ │   ├─┬ dashdash@1.14.1 
│ │   │ │ A light, featureful and explicit option parsing library.
│ │   │ │ git://github.com/trentm/node-dashdash.git
│ │   │ │ https://github.com/trentm/node-dashdash#readme
│ │   │ └── assert-plus@1.0.0 
│ │   │     Extra assertions on top of node's assert module
│ │   │     git+https://github.com/mcavage/node-assert-plus.git
│ │   │     https://github.com/mcavage/node-assert-plus#readme
│ │   └─┬ getpass@0.1.6 
│ │     │ getpass for node.js
│ │     │ git+https://github.com/arekinath/node-getpass.git
│ │     │ https://github.com/arekinath/node-getpass#readme
│ │     └── assert-plus@1.0.0 
│ │         Extra assertions on top of node's assert module
│ │         git+https://github.com/mcavage/node-assert-plus.git
│ │         https://github.com/mcavage/node-assert-plus#readme
│ ├── is-typedarray@1.0.0 
│ │   Detect whether or not an object is a Typed Array
│ │   git://github.com/hughsk/is-typedarray.git
│ │   https://github.com/hughsk/is-typedarray
│ ├── isstream@0.1.2 
│ │   Determine if an object is a Stream
│ │   git+https://github.com/rvagg/isstream.git
│ │   https://github.com/rvagg/isstream
│ ├── json-stringify-safe@5.0.1 
│ │   Like JSON.stringify, but doesn't blow up on circular refs.
│ │   git://github.com/isaacs/json-stringify-safe.git
│ │   https://github.com/isaacs/json-stringify-safe
│ ├─┬ mime-types@2.1.15 
│ │ │ The ultimate javascript content-type utility.
│ │ │ git+https://github.com/jshttp/mime-types.git
│ │ │ https://github.com/jshttp/mime-types#readme
│ │ └── mime-db@1.27.0 
│ │     Media Type Database
│ │     git+https://github.com/jshttp/mime-db.git
│ │     https://github.com/jshttp/mime-db#readme
│ ├── node-uuid@1.4.7 
│ │   Rigorous implementation of RFC4122 (v1 and v4) UUIDs.
│ │   git+https://github.com/broofa/node-uuid.git
│ │   https://github.com/broofa/node-uuid
│ ├── oauth-sign@0.8.2 
│ │   OAuth 1 signing. Formerly a vendor lib in mikeal/request, now a standalone module.
│ │   git+https://github.com/mikeal/oauth-sign.git
│ │   https://github.com/mikeal/oauth-sign#readme
│ ├── qs@6.2.3 
│ │   A querystring parser that supports nesting and arrays, with a depth limit
│ │   git+https://github.com/ljharb/qs.git
│ │   https://github.com/ljharb/qs
│ ├── stringstream@0.0.5 
│ │   Encode and decode streams into string streams
│ │   git+https://github.com/mhart/StringStream.git
│ │   https://github.com/mhart/StringStream#readme
│ ├─┬ tough-cookie@2.3.2 
│ │ │ RFC6265 Cookies and Cookie Jar for node.js
│ │ │ git://github.com/salesforce/tough-cookie.git
│ │ │ https://github.com/salesforce/tough-cookie
│ │ └── punycode@1.4.1 
│ │     A robust Punycode converter that fully complies to RFC 3492 and RFC 5891, and works on nearly all JavaScript platforms.
│ │     git+https://github.com/bestiejs/punycode.js.git
│ │     https://mths.be/punycode
│ └── tunnel-agent@0.4.3 
│     HTTP proxy tunneling agent. Formerly part of mikeal/request, now a standalone module.
│     git+https://github.com/mikeal/tunnel-agent.git
│     https://github.com/mikeal/tunnel-agent#readme
├─┬ unzip@0.1.11 
│ │ Unzip cross-platform streaming API compatible with fstream and fs.ReadStream
│ │ git+https://github.com/EvanOxfeld/node-unzip.git
│ │ https://github.com/EvanOxfeld/node-unzip
│ ├─┬ binary@0.3.0 
│ │ │ Unpack multibyte binary values from buffers
│ │ │ git://github.com/substack/node-binary.git
│ │ │ https://github.com/substack/node-binary#readme
│ │ ├── buffers@0.1.1 
│ │ │   Treat a collection of Buffers as a single contiguous partially mutable Buffer.
│ │ │   git://github.com/substack/node-buffers.git
│ │ │   https://github.com/substack/node-buffers#readme
│ 
│ └─┬ chainsaw@0.1.0 
│ │   │ Build chainable fluent interfaces the easy way... with a freakin' chainsaw!
│ │   │ git://github.com/substack/node-chainsaw.git
│ │   │ https://github.com/substack/node-chainsaw#readme
│ │   └── traverse@0.3.9 
│ │       Traverse and transform objects by visiting every node on a recursive walk
│ │       git://github.com/substack/js-traverse.git
│ │       https://github.com/substack/js-traverse#readme
│ ├─┬ fstream@0.1.31 
│ │ │ Advanced file system stream things
│ │ │ git://github.com/isaacs/fstream.git
│ │ │ https://github.com/isaacs/fstream
│ │ ├─┬ graceful-fs@3.0.11 
│ │ │ │ A drop-in replacement for fs, making various improvements.
│ │ │ │ git://github.com/isaacs/node-graceful-fs.git
│ │ │ │ https://github.com/isaacs/node-graceful-fs#readme
│ │ │ └── natives@1.1.0 
│ │ │     Do stuff with Node.js's native JavaScript modules
│ │ │     git+https://github.com/isaacs/natives.git
│ │ │     https://github.com/isaacs/natives#readme
│ │ ├── inherits@2.0.3 
│ │ │   Browser-friendly inheritance fully compatible with standard node.js inherits()
│ │ │   git://github.com/isaacs/inherits.git
│ │ │   https://github.com/isaacs/inherits#readme
│ │ ├─┬ mkdirp@0.5.1 
│ │ │ │ Recursively mkdir, like `mkdir -p`
│ │ │ │ git+https://github.com/substack/node-mkdirp.git
│ │ │ │ https://github.com/substack/node-mkdirp#readme
│ │ │ └── minimist@0.0.8 
│ │ │     parse argument options
│ │ │     git://github.com/substack/minimist.git
│ │ │     https://github.com/substack/minimist
│ │ └── rimraf@2.6.1 
│ │     A deep deletion module for node (like `rm -rf`)
│ │     git://github.com/isaacs/rimraf.git
│ │     https://github.com/isaacs/rimraf#readme
│ ├─┬ match-stream@0.0.2 
│ │ │ Match a pattern within a stream
│ │ │ git+https://github.com/EvanOxfeld/match-stream.git
│ │ │ https://github.com/EvanOxfeld/match-stream#readme
│ │ ├── buffers@0.1.1 
│ │ │   Treat a collection of Buffers as a single contiguous partially mutable Buffer.
│ │ │   git://github.com/substack/node-buffers.git
│ │ │   https://github.com/substack/node-buffers#readme
│ │ └─┬ readable-stream@1.0.34 
│ │   │ Streams2, a user-land copy of the stream library from Node.js v0.10.x
│ │   │ git://github.com/isaacs/readable-stream.git
│ │   │ https://github.com/isaacs/readable-stream#readme
│ │   ├── core-util-is@1.0.2 
│ │   │   The `util.is*` functions introduced in Node v0.12.
│ │   │   git://github.com/isaacs/core-util-is.git
│ │   │   https://github.com/isaacs/core-util-is#readme
│ │   ├── inherits@2.0.3 
│ │   │   Browser-friendly inheritance fully compatible with standard node.js inherits()
│ │   │   git://github.com/isaacs/inherits.git
│ │   │   https://github.com/isaacs/inherits#readme
│ │   ├── isarray@0.0.1 
│ │   │   Array#isArray for older browsers
│ │   │   git://github.com/juliangruber/isarray.git
│ │   │   https://github.com/juliangruber/isarray
│ │   └── string_decoder@0.10.31 
│ │       The string_decoder module from Node core
│ │       git://github.com/rvagg/string_decoder.git
│ │       https://github.com/rvagg/string_decoder
│ ├─┬ pullstream@0.4.1 
│ │ │ A stream you can pull data from.
│ │ │ git+https://github.com/nearinfinity/node-pullstream.git
│ │ │ https://github.com/nearinfinity/node-pullstream
│ │ ├── over@0.0.5 
│ │ │   JavaScript function overloading framework.
│ │ │   git+https://github.com/nearinfinity/node-over.git
│ │ │   https://github.com/nearinfinity/node-over#readme
│ │ ├─┬ readable-stream@1.0.34 
│ │ │ │ Streams2, a user-land copy of the stream library from Node.js v0.10.x
│ │ │ │ git://github.com/isaacs/readable-stream.git
│ │ │ │ https://github.com/isaacs/readable-stream#readme
│ │ │ ├── core-util-is@1.0.2 
│ │ │ │   The `util.is*` functions introduced in Node v0.12.
│ │ │ │   git://github.com/isaacs/core-util-is.git
│ │ │ │   https://github.com/isaacs/core-util-is#readme
│ │ │ ├── inherits@2.0.3 
│ │ │ │   Browser-friendly inheritance fully compatible with standard node.js inherits()
│ │ │ │   git://github.com/isaacs/inherits.git
│ │ │ │   https://github.com/isaacs/inherits#readme
│ │ │ ├── isarray@0.0.1 
│ │ │ │   Array#isArray for older browsers
│ │ │ │   git://github.com/juliangruber/isarray.git
│ │ │ │   https://github.com/juliangruber/isarray
│ │ │ └── string_decoder@0.10.31 
│ │ │     The string_decoder module from Node core
│ │ │     git://github.com/rvagg/string_decoder.git
│ │ │     https://github.com/rvagg/string_decoder
│ │ ├── setimmediate@1.0.5 
│ │ │   A shim for the setImmediate efficient script yielding API
│ │ │   git+https://github.com/yuzujs/setImmediate.git
│ │ │   https://github.com/yuzujs/setImmediate#readme
│ │ └─┬ slice-stream@1.0.0 
│ │   │ Pipe data through a stream until some fixed length is reached, then callback.
│ │   │ git+https://github.com/EvanOxfeld/slice-stream.git
│ │   │ https://github.com/EvanOxfeld/slice-stream
│ │   └─┬ readable-stream@1.0.34 
│ │     │ Streams2, a user-land copy of the stream library from Node.js v0.10.x
│ │     │ git://github.com/isaacs/readable-stream.git
│ │     │ https://github.com/isaacs/readable-stream#readme
│ │     ├── core-util-is@1.0.2 
│ │     │   The `util.is*` functions introduced in Node v0.12.
│ │     │   git://github.com/isaacs/core-util-is.git
│ │     │   https://github.com/isaacs/core-util-is#readme
│ │     ├── inherits@2.0.3 
│ │     │   Browser-friendly inheritance fully compatible with standard node.js inherits()
│ │     │   git://github.com/isaacs/inherits.git
│ │     │   https://github.com/isaacs/inherits#readme
│ │     ├── isarray@0.0.1 
│ │     │   Array#isArray for older browsers
│ │     │   git://github.com/juliangruber/isarray.git
│ │     │   https://github.com/juliangruber/isarray
│ │     └── string_decoder@0.10.31 
│ │         The string_decoder module from Node core
│ │         git://github.com/rvagg/string_decoder.git
│ │         https://github.com/rvagg/string_decoder
│ ├─┬ readable-stream@1.0.34 
│ │ │ Streams2, a user-land copy of the stream library from Node.js v0.10.x
│ │ │ git://github.com/isaacs/readable-stream.git
│ │ │ https://github.com/isaacs/readable-stream#readme
│ │ ├── core-util-is@1.0.2 
│ │ │   The `util.is*` functions introduced in Node v0.12.
│ │ │   git://github.com/isaacs/core-util-is.git
│ │ │   https://github.com/isaacs/core-util-is#readme
│ │ ├── inherits@2.0.3 
│ │ │   Browser-friendly inheritance fully compatible with standard node.js inherits()
│ │ │   git://github.com/isaacs/inherits.git
│ │ │   https://github.com/isaacs/inherits#readme
│ │ ├── isarray@0.0.1 
│ │ │   Array#isArray for older browsers
│ │ │   git://github.com/juliangruber/isarray.git
│ │ │   https://github.com/juliangruber/isarray
│ │ └── string_decoder@0.10.31 
│ │     The string_decoder module from Node core
│ │     git://github.com/rvagg/string_decoder.git
│ │     https://github.com/rvagg/string_decoder
│ └── setimmediate@1.0.5 
│     A shim for the setImmediate efficient script yielding API
│     git+https://github.com/yuzujs/setImmediate.git
│     https://github.com/yuzujs/setImmediate#readme
└─┬ xcode@0.9.0  (git+https://github.com/alunny/node-xcode.git#4cca2f6225c391b63324e6eb53421560649d4f98)
  │ parser for xcodeproj/project.pbxproj files
  │ git+https://
github.com/alunny/node-xcode.git
  │ https://github.com/alunny/node-xcode#readme
  │ git+https://github.com/alunny/node-xcode.git#4cca2f6225c391b63324e6eb53421560649d4f98
  ├── node-uuid@1.4.7 
  │   Rigorous implementation of RFC4122 (v1 and v4) UUIDs.
  │   git+https://github.com/broofa/node-uuid.git
  │   https://github.com/broofa/node-uuid
  ├── pegjs@0.9.0 
  │   Parser generator for JavaScript
  │   git+ssh://git@github.com/pegjs/pegjs.git
  │   http://pegjs.org/
  └─┬ simple-plist@0.1.4 
    │ A wrapper utility for interacting with plist data.
    │ git+https://github.com/wollardj/node-simple-plist.git
    │ https://github.com/wollardj/node-simple-plist.git
    ├─┬ bplist-creator@0.0.4 
    │ │ Binary Mac OS X Plist (property list) creator.
    │ │ git+https://github.com/nearinfinity/node-bplist-creator.git
    │ │ https://github.com/nearinfinity/node-bplist-creator
    │ └── stream-buffers@0.2.6 
    │     Buffer-backed Streams for reading and writing.
    │     git+https://github.com/samcday/node-stream-buffer.git
    │     https://github.com/samcday/node-stream-buffer
    ├── bplist-parser@0.0.6 
    │   Binary plist parser.
    │   git+https://github.com/nearinfinity/node-bplist-parser.git
    │   https://github.com/nearinfinity/node-bplist-parser
    └─┬ plist@1.2.0 
      │ Mac OS X Plist parser/builder for Node.js and browsers
      │ git://github.com/TooTallNate/node-plist.git
      │ https://github.com/TooTallNate/node-plist#readme
      ├── base64-js@0.0.8 
      │   Base64 encoding/decoding in pure JS
      │   git://github.com/beatgammit/base64-js.git
      │   https://github.com/beatgammit/base64-js
      ├── util-deprecate@1.0.2 
      │   The Node.js `util.deprecate()` function with browser support
      │   git://github.com/TooTallNate/util-deprecate.git
      │   https://github.com/TooTallNate/util-deprecate
      ├─┬ xmlbuilder@4.0.0 
      │ │ An XML builder for node.js
      │ │ git://github.com/oozcitak/xmlbuilder-js.git
      │ │ http://github.com/oozcitak/xmlbuilder-js
      │ └── lodash@3.10.1 
      │     The modern build of lodash modular utilities.
      │     git+https://github.com/lodash/lodash.git
      │     https://lodash.com/
      └── xmldom@0.1.27 
          A W3C Standard XML DOM(Level2 CORE) implementation and parser(DOMParser/XMLSerializer).
          git://github.com/jindw/xmldom.git
          https://github.com/jindw/xmldom


Trying to install jxcore-cordova version: 0.1.10
[36mDownloading:[39m [32mhttp://jxcore.azureedge.net/jxcore-cordova/0.1.10/release/io.jxcore.node.jx
[39m

[1A[KAttempt 1 / 3

[1A[K


[1A[K
[36mProgress:[39m [32mDone[39m

[32mExtracting plugin package...[39m

[32mDone.[39m

[32mRemoving plugin from project...[39m

[1A[K
[31mRemoving plugin from project...[39m

[32mAdding plugin to project...[39m

[32mCleaning up...[39m

[32mDone.[39m

Copying files from /Users/thali/Github/Thali_CordovaPlugin to /Users/thali/Github/ThaliTest/thaliDontCheckIn/Thali_CordovaPlugin-iOS
start adding Thali Cordova plugin from: /Users/thali/Github/ThaliTest/thaliDontCheckIn/Thali_CordovaPlugin-iOS
Installing "org.thaliproject.p2p" for android


ANDROID_HOME=/Users/thali/Library/Android/sdk

JAVA_HOME=/Library/Java/JavaVirtualMachines/jdk1.8.0_102.jdk/Contents/Home

Subproject Path: CordovaLib

Incremental java compilation is an incubating feature.


:clean


:CordovaLib:clean




BUILD SUCCESSFUL




Total time: 2.424 secs


Subproject Path: CordovaLib

Preparing UT test environment

Removing UT flag

Installing "org.thaliproject.p2p" for ios


Updating JXcoreExtension.m

Removing UT flag

Checkouting ThaliCore and its dependencies

Checkouting done!
Building in debug mode
Building ThaliCore.framework
Build command:
set -o pipefail && xcodebuild -project "/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/Carthage/Checkouts/thali-ios/ThaliCore.xcodeproj" -scheme "ThaliCoreCITests" -configuration Debug -sdk iphoneos ONLY_ACTIVE_ARCH=NO  IPHONEOS_DEPLOYMENT_TARGET=10.0 BUILD_DIR="/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/Carthage/Checkouts/thali-ios/build" clean build

end adding Thali Cordova plugin
thali-cordova-plugin-jxcore@1.0.0
│ /Users/thali/Github/ThaliTest/www/jxcore
│ Thali Cordova Plugin JXCore
├── fs-extra-promise@0.4.0
│   Node file system library and fs-extra module promisified with bluebird
│   git+https://github.com/overlookmotel/fs-extra-promise.git
│   https://github.com/overlookmotel/fs-extra-promise#readme
├── lie@3.0.4
│   A basic but performant promise implementation
│   git+https://github.com/calvinmetcalf/lie.git
│   https://github.com/calvinmetcalf/lie#readme
└── thali@2.1.0 
    Thali Cordova Plugin
    git+https://github.com/thaliproject/Thali_CordovaPlugin.git
    https://github.com/thaliproject/Thali_CordovaPlugin/tree/story_00#readme


run supertest for Android

> leveldown@1.5.0 install /Users/thali/Github/ThaliTest/www/jxcore/node_modules/leveldown
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

> leveldown-mobile@1.1.1 install /Users/thali/Github/ThaliTest/www/jxcore/node_modules/leveldown-mobile
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
│ /Users/thali/Github/ThaliTest/www/jxcore
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
├── forever-agent@0.6.1  (git+https://github.com/thaliproject/forever-agent.git#f9a92c7a1b7ce4da849beca32b0ec2aeb855e0fd)
│   HTTP Agent that keeps socket connections alive between keep-alive requests. Formerly part of mikeal/request, now a standalone module.
│   git+https://github.com/mikeal/forever-agent.git
│   https://github.com/mikeal/forever-agent#readme
│   git+https://github.com/thaliproject/forever-agent.git#f9a92c7a1b7ce4da849beca32b0ec2aeb855e0fd
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
├── node-ssdp@2.6.5  (git+https://github.com/thaliproject/node-ssdp.git#3a5909e201aee401f48965e378eb2ff0e2f9e027)
│   A node.js SSDP client and server library.
│   git+ssh://git@github.com/diversario/node-ssdp.git
│   https://github.com/diversario/node-ssdp#readme
│   git+https://github.com/thaliproject/node-ssdp.git#3a5909e201aee401f48965e378eb2ff0e2f9e027
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

copying app.js
UnitTest_app.js -> app.js
end installing Thali


start building ThaliTest Android app
We have replaced hardcoded ids with random values.
ANDROID_HOME=/Users/thali/Library/Android/sdk
JAVA_HOME=/Library/Java/JavaVirtualMachines/jdk1.8.0_102.jdk/Contents/Home
Subproject Path: CordovaLib
Incremental java compilation is an incubating feature.
:preBuild UP-TO-DATE
:preReleaseBuild UP-TO-DATE
:checkReleaseManifest
:CordovaLib:preBuild UP-TO-DATE
:CordovaLib:preReleaseBuild UP-TO-DATE
:CordovaLib:checkReleaseManifest
:CordovaLib:prepareReleaseDependencies
:CordovaLib:compileReleaseAidl
:CordovaLib:compileReleaseNdk UP-TO-DATE
:CordovaLib:compileLint
:CordovaLib:copyReleaseLint UP-TO-DATE
:CordovaLib:mergeReleaseShaders
:CordovaLib:compileReleaseShaders
:CordovaLib:generateReleaseAssets
:CordovaLib:mergeReleaseAssets
:CordovaLib:mergeReleaseProguardFiles
:CordovaLib:packageReleaseRenderscript UP-TO-DATE
:CordovaLib:compileReleaseRenderscript
:CordovaLib:generateReleaseResValues
:CordovaLib:generateReleaseResources
:CordovaLib:packageReleaseResources
:CordovaLib:processReleaseManifest
:CordovaLib:generateReleaseBuildConfig
:CordovaLib:processReleaseResources
:CordovaLib:generateReleaseSources
:CordovaLib:incrementalReleaseJavaCompilationSafeguard
:CordovaLib:compileReleaseJavaWithJavac
:CordovaLib:compileReleaseJavaWithJavac - is not incremental (e.g. outputs have changed, no previous execution, etc.).
:CordovaLib:processReleaseJavaRes UP-TO-DATE
:CordovaLib:transformResourcesWithMergeJavaResForRelease
:CordovaLib:transformClassesAndResourcesWithSyncLibJarsForRelease
:CordovaLib:mergeReleaseJniLibFolders
:CordovaLib:transformNative_libsWithMergeJniLibsForRelease
:CordovaLib:transformNative_libsWithSyncJniLibsForRelease
:CordovaLib:bundleRelease
:prepareAndroidCordovaLibUnspecifiedReleaseLibrary
:preDebugBuild UP-TO-DATE
:CordovaLib:preDebugBuild UP-TO-DATE
:CordovaLib:checkDebugManifest
:CordovaLib:prepareDebugDependencies
:CordovaLib:compileDebugAidl
:CordovaLib:compileDebugNdk UP-TO-DATE
:CordovaLib:copyDebugLint UP-TO-DATE
:CordovaLib:mergeDebugShaders
:CordovaLib:compileDebugShaders
:CordovaLib:generateDebugAssets
:CordovaLib:mergeDebugAssets
:CordovaLib:mergeDebugProguardFiles
:CordovaLib:packageDebugRenderscript UP-TO-DATE
:CordovaLib:compileDebugRenderscript
:CordovaLib:generateDebugResValues
:CordovaLib:generateDebugResources
:CordovaLib:packageDebugResources
:CordovaLib:processDebugManifest
:CordovaLib:generateDebugBuildConfig
:CordovaLib:processDebugResources
:CordovaLib:generateDebugSources
:CordovaLib:incrementalDebugJavaCompilationSafeguard
:CordovaLib:compileDebugJavaWithJavac
:CordovaLib:compileDebugJavaWithJavac - is not incremental (e.g. outputs have changed, no previous execution, etc.).
:CordovaLib:processDebugJavaRes UP-TO-DATE
:CordovaLib:transformResourcesWithMergeJavaResForDebug
:CordovaLib:transformClassesAndResourcesWithSyncLibJarsForDebug
:CordovaLib:mergeDebugJniLibFolders
:CordovaLib:transformNative_libsWithMergeJniLibsForDebug
:CordovaLib:transformNative_libsWithSyncJniLibsForDebug
:CordovaLib:bundleDebug
:prepareComAndroidSupportAppcompatV72220Library
:prepareComAndroidSupportSupportV42220Library
:prepareComAndroidSupportTestEspressoEspressoCore22Library
:prepareComAndroidSupportTestEspressoEspressoIdlingResource22Library
:prepareComAndroidSupportTestExposedInstrumentationApiPublish03Library
:prepareComAndroidSupportTestRules03Library
:prepareComAndroidSupportTestRunner03Library
:prepareOrgThaliprojectP2pBtconnectorlibBtconnectorlib2039Library
:prepareReleaseDependencies
:compileReleaseAidl
:compileReleaseRenderscript
:generateReleaseBuildConfig
:generateReleaseResValues
:generateReleaseResources
:mergeReleaseResources
:processReleaseManifest
:processReleaseResources
:generateReleaseSources
:incrementalReleaseJavaCompilationSafeguard
:compileReleaseJavaWithJavac
:compileReleaseJavaWithJavac - is not incremental (e.g. outputs have changed, no previous execution, etc.).
:compileReleaseNdk UP-TO-DATE
:compileReleaseSources
:lintVitalRelease
:mergeReleaseShaders
:compileReleaseShaders
:generateReleaseAssets
:mergeReleaseAssets
:transformClassesWithDexForRelease
:mergeReleaseJniLibFolders
:transformNative_libsWithMergeJniLibsForRelease
:processReleaseJavaRes UP-TO-DATE
:transformResourcesWithMergeJavaResForRelease
:packageRelease
:assembleRelease
:cdvBuildRelease

BUILD SUCCESSFUL

Total time: 1 mins 57.418 secs
Built the following apk(s): 
	/Users/thali/Github/ThaliTest/platforms/android/build/outputs/apk/android-release-unsigned.apk
end building ThaliTest Android app


start building ThaliTest iOS app
Build settings from command line:
    CONFIGURATION_BUILD_DIR = /Users/thali/Github/testBuild/../ThaliTest/platforms/ios/build/device
    DEVELOPMENT_TEAM = YVE8Q53U9A
    SDKROOT = iphoneos10.2
    SHARED_PRECOMPS_DIR = /Users/thali/Github/testBuild/../ThaliTest/platforms/ios/build/sharedpch

Build settings from configuration file '/Users/thali/Github/testBuild/thali/install/ios/build-ci.xcconfig':
    CLANG_ALLOW_NON_MODULAR_INCLUDES_IN_FRAMEWORK_MODULES = YES
    CODE_SIGN_IDENTITY = iPhone Developer
    EMBEDDED_CONTENT_CONTAINS_SWIFT = YES
    ENABLE_BITCODE = NO
    GCC_PREPROCESSOR_DEFINITIONS = $(inherited) DEBUG=1 TEST=1
    HEADER_SEARCH_PATHS = "$(TARGET_BUILD_DIR)/usr/local/lib/include" "$(OBJROOT)/UninstalledProducts/include" "$(OBJROOT)/UninstalledProducts/$(PLATFORM_NAME)/include" "$(BUILT_PRODUCTS_DIR)"
    IPHONEOS_DEPLOYMENT_TARGET = 10.0
    LD_RUNPATH_SEARCH_PATHS = $(inherited) @executable_path/Frameworks
    ONLY_ACTIVE_ARCH = NO
    OTHER_LDFLAGS = -ObjC
    OTHER_SWIFT_FLAGS = $(inherited) '-DTEST'
    SWIFT_OBJC_BRIDGING_HEADER = $(PROJECT_DIR)/$(PROJECT_NAME)/Bridging-Header.h
    SWIFT_VERSION = 3.0
    TARGETED_DEVICE_FAMILY = 1,2

=== BUILD TARGET CordovaLib OF PROJECT CordovaLib WITH CONFIGURATION Debug ===

Check dependencies
Not running swift-stdlib-tool: ALWAYS_EMBED_SWIFT_STANDARD_LIBRARIES is enabled, but the product type 'Static Library' is not a wrapper type.

Write auxiliary files
/bin/mkdir -p /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-ggataxlbeiubftcsgtuizgehugsd
write-file /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-ggataxlbeiubftcsgtuizgehugsd/CordovaLib_Prefix.pch.pch.hash-criteria
write-file /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova.hmap
/bin/mkdir -p /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-gndultymibmclyaifbpnxmplhikv
write-file /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-gndultymibmclyaifbpnxmplhikv/CordovaLib_Prefix.pch.pch.hash-criteria
write-file /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap
write-file /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap
write-file /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap
/bin/mkdir -p /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7
write-file /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/Cordova.LinkFileList
write-file /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap
/bin/mkdir -p /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64
write-file /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/Cordova.LinkFileList
write-file /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-non-framework-target-headers.hmap

CpHeader Classes/Public/CDVScreenOrientationDelegate.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova/CDVScreenOrientationDelegate.h
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVScreenOrientationDelegate.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova

CpHeader Classes/Public/CDVWebViewEngineProtocol.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova/CDVWebViewEngineProtocol.h
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVWebViewEngineProtocol.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova

CpHeader Classes/Public/CDVCommandDelegateImpl.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova/CDVCommandDelegateImpl.h
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVCommandDelegateImpl.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova

CpHeader Classes/Public/CDV.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova/CDV.h
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDV.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova

CpHeader Classes/Public/CDVCommandQueue.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova/CDVCommandQueue.h
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVCommandQueue.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova

CpHeader Classes/Public/CDVWhitelist.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova/CDVWhitelist.h
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVWhitelist.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova

CpHeader Classes/Public/CDVAppDelegate.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova/CDVAppDelegate.h
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVAppDelegate.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova

CpHeader Classes/Public/CDVPlugin+Resources.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova/CDVPlugin+Resources.h
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVPlugin+Resources.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova

CpHeader Classes/Public/CDVAvailability.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova/CDVAvailability.h
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVAvailability.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova

CpHeader Classes/Private/Plugins/CDVUIWebViewEngine/CDVUIWebViewDelegate.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova/CDVUIWebViewDelegate.h
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Private/Plugins/CDVUIWebViewEngine/CDVUIWebViewDelegate.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova

CpHeader Classes/Public/CDVPluginResult.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova/CDVPluginResult.h
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVPluginResult.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova

CpHeader Classes/Public/NSMutableArray+QueueAdditions.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova/NSMutableArray+QueueAdditions.h
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/NSMutableArray+QueueAdditions.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova

CpHeader Classes/Public/CDVInvokedUrlCommand.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova/CDVInvokedUrlCommand.h
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVInvokedUrlCommand.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova

CpHeader Classes/Public/NSDictionary+CordovaPreferences.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova/NSDictionary+CordovaPreferences.h
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/NSDictionary+CordovaPreferences.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova

CpHeader Classes/Public/CDVPlugin.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova/CDVPlugin.h
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVPlugin.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova

CpHeader Classes/Public/CDVURLProtocol.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova/CDVURLProtocol.h
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova

CpHeader Classes/Public/CDVCommandDelegate.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova/CDVCommandDelegate.h
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVCommandDelegate.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova

CpHeader Classes/Public/CDVAvailabilityDeprecated.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova/CDVAvailabilityDeprecated.h
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVAvailabilityDeprecated.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova

CpHeader Classes/Public/CDVUserAgentUtil.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova/CDVUserAgentUtil.h
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVUserAgentUtil.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova

CpHeader Classes/Public/CDVTimer.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova/CDVTimer.h
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVTimer.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova

CpHeader Classes/Public/CDVConfigParser.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova/CDVConfigParser.h
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVConfigParser.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova

CpHeader Classes/Public/CDVViewController.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova/CDVViewController.h
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVViewController.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova

ProcessPCH /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-gndultymibmclyaifbpnxmplhikv/CordovaLib_Prefix.pch.pch CordovaLib_Prefix.pch normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c-header -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -MD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-gndultymibmclyaifbpnxmplhikv/CordovaLib_Prefix.pch.d -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/CordovaLib_Prefix.pch -o /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-gndultymibmclyaifbpnxmplhikv/CordovaLib_Prefix.pch.pch --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-gndultymibmclyaifbpnxmplhikv/CordovaLib_Prefix.pch.dia

ProcessPCH /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-ggataxlbeiubftcsgtuizgehugsd/CordovaLib_Prefix.pch.pch CordovaLib_Prefix.pch normal arm64 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c-header -arch arm64 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wshorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/arm64 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -MD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-ggataxlbeiubftcsgtuizgehugsd/CordovaLib_Prefix.pch.d -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/CordovaLib_Prefix.pch -o /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-ggataxlbeiubftcsgtuizgehugsd/CordovaLib_Prefix.pch.pch --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-ggataxlbeiubftcsgtuizgehugsd/CordovaLib_Prefix.pch.dia

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVViewController.o Classes/Public/CDVViewController.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-gndultymibmclyaifbpnxmplhikv/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVViewController.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVViewController.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVViewController.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVViewController.o
/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVViewController.m:335:99: warning: 'stringByAddingPercentEscapesUsingEncoding:' is deprecated: first deprecated in iOS 9.0 - Use -stringByAddingPercentEncodingWithAllowedCharacters: instead, which always uses the recommended UTF-8 encoding, and which encodes for a specific URL component or subcomponent since each URL component or subcomponent has different rules for what characters are valid. [-Wdeprecated-declarations]
                errorUrl = [NSURL URLWithString:[NSString stringWithFormat:@"?error=%@", [loadErr stringByAddingPercentEscapesUsingEncoding:NSUTF8StringEncoding]] relativeToURL:errorUrl];
                                                                                                  ^
In module 'Foundation' imported from /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVAppDelegate.h:20:
/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk/System/Library/Frameworks/Foundation.framework/Headers/NSURL.h:541:1: note: 'stringByAddingPercentEscapesUsingEncoding:' has been explicitly marked deprecated here
- (nullable NSString *)stringByAddingPercentEscapesUsingEncoding:(NSStringEncoding)enc NS_DEPRECATED(10_0, 10_11, 2_0, 9_0, "Use -stringByAddingPercentEncodingWithAllowedCharacters: instead, which always uses the recommended UTF-8 encoding, and which encodes for a specific URL component or subcomponent since each URL component or subcomponent has different rules for what characters are valid.");
^
1 warning generated.

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/NSDictionary+CordovaPreferences.o Classes/Public/NSDictionary+CordovaPreferences.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-gndultymibmclyaifbpnxmplhikv/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/NSDictionary+CordovaPreferences.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/NSDictionary+CordovaPreferences.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/NSDictionary+CordovaPreferences.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/NSDictionary+CordovaPreferences.o

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVAppDelegate.o Classes/Public/CDVAppDelegate.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-gndultymibmclyaifbpnxmplhikv/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVAppDelegate.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVAppDelegate.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVAppDelegate.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVAppDelegate.o

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVUIWebViewDelegate.o Classes/Private/Plugins/CDVUIWebViewEngine/CDVUIWebViewDelegate.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-gndultymibmclyaifbpnxmplhikv/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVUIWebViewDelegate.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVUIWebViewDelegate.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Private/Plugins/CDVUIWebViewEngine/CDVUIWebViewDelegate.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVUIWebViewDelegate.o

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVCommandDelegateImpl.o Classes/Public/CDVCommandDelegateImpl.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-gndultymibmclyaifbpnxmplhikv/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVCommandDelegateImpl.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVCommandDelegateImpl.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVCommandDelegateImpl.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVCommandDelegateImpl.o

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVJSON_private.o Classes/Private/CDVJSON_private.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-gndultymibmclyaifbpnxmplhikv/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVJSON_private.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVJSON_private.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Private/CDVJSON_private.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVJSON_private.o

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVWhitelist.o Classes/Public/CDVWhitelist.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-gndultymibmclyaifbpnxmplhikv/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVWhitelist.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVWhitelist.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVWhitelist.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVWhitelist.o
/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVWhitelist.m:259:134: warning: 'stringByAddingPercentEscapesUsingEncoding:' is deprecated: first deprecated in iOS 9.0 - Use -stringByAddingPercentEncodingWithAllowedCharacters: instead, which always uses the recommended UTF-8 encoding, and which encodes for a specific URL component or subcomponent since each URL component or subcomponent has different rules for what characters are valid. [-Wdeprecated-declarations]
        NSURL* newUrl = [NSURL URLWithString:[NSString stringWithFormat:@"%@://%@%@", kCDVDefaultSchemeName, [url host], [[url path] stringByAddingPercentEscapesUsingEncoding:NSUTF8StringEncoding]]];
                                                                                                                                     ^
In module 'Foundation' imported from /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVWhitelist.h:20:
/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk/System/Library/Frameworks/Foundation.framework/Headers/NSURL.h:541:1: note: 'stringByAddingPercentEscapesUsingEncoding:' has been explicitly marked deprecated here
- (nullable NSString *)stringByAddingPercentEscapesUsingEncoding:(NSStringEncoding)enc NS_DEPRECATED(10_0, 10_11, 2_0, 9_0, "Use -stringByAddingPercentEncodingWithAllowedCharacters: instead, which always uses the recommended UTF-8 encoding, and which encodes for a specific URL component or subcomponent since each URL component or subcomponent has different rules for what characters are valid.");
^
1 warning generated.

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVInvokedUrlCommand.o Classes/Public/CDVInvokedUrlCommand.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-gndultymibmclyaifbpnxmplhikv/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVInvokedUrlCommand.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVInvokedUrlCommand.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVInvokedUrlCommand.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVInvokedUrlCommand.o

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVTimer.o Classes/Public/CDVTimer.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-gndultymibmclyaifbpnxmplhikv/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVTimer.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVTimer.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVTimer.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVTimer.o

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVUserAgentUtil.o Classes/Public/CDVUserAgentUtil.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-gndultymibmclyaifbpnxmplhikv/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVUserAgentUtil.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVUserAgentUtil.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVUserAgentUtil.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVUserAgentUtil.o

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVConfigParser.o Classes/Public/CDVConfigParser.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-gndultymibmclyaifbpnxmplhikv/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVConfigParser.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVConfigParser.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVConfigParser.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVConfigParser.o

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVGestureHandler.o Classes/Private/Plugins/CDVGestureHandler/CDVGestureHandler.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-gndultymibmclyaifbpnxmplhikv/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVGestureHandler.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVGestureHandler.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Private/Plugins/CDVGestureHandler/CDVGestureHandler.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVGestureHandler.o

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVHandleOpenURL.o Classes/Private/Plugins/CDVHandleOpenURL/CDVHandleOpenURL.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-gndultymibmclyaifbpnxmplhikv/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVHandleOpenURL.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVHandleOpenURL.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Private/Plugins/CDVHandleOpenURL/CDVHandleOpenURL.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVHandleOpenURL.o

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVUIWebViewNavigationDelegate.o Classes/Private/Plugins/CDVUIWebViewEngine/CDVUIWebViewNavigationDelegate.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-gndultymibmclyaifbpnxmplhikv/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVUIWebViewNavigationDelegate.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVUIWebViewNavigationDelegate.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Private/Plugins/CDVUIWebViewEngine/CDVUIWebViewNavigationDelegate.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVUIWebViewNavigationDelegate.o
/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Private/Plugins/CDVUIWebViewEngine/CDVUIWebViewNavigationDelegate.m:81:91: warning: 'stringByAddingPercentEscapesUsingEncoding:' is deprecated: first deprecated in iOS 9.0 - Use -stringByAddingPercentEncodingWithAllowedCharacters: instead, which always uses the recommended UTF-8 encoding, and which encodes for a specific URL component or subcomponent since each URL component or subcomponent has different rules for what characters are valid. [-Wdeprecated-declarations]
        errorUrl = [NSURL URLWithString:[NSString stringWithFormat:@"?error=%@", [message stringByAddingPercentEscapesUsingEncoding:NSUTF8StringEncoding]] relativeToURL:errorUrl];
                                                                                          ^
In module 'Foundation' imported from /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVPlugin.h:20:
/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk/System/Library/Frameworks/Foundation.framework/Headers/NSURL.h:541:1: note: 'stringByAddingPercentEscapesUsingEncoding:' has been explicitly marked deprecated here
- (nullable NSString *)stringByAddingPercentEscapesUsingEncoding:(NSStringEncoding)enc NS_DEPRECATED(10_0, 10_11, 2_0, 9_0, "Use -stringByAddingPercentEncodingWithAllowedCharacters: instead, which always uses the recommended UTF-8 encoding, and which encodes for a specific URL component or subcomponent since each URL component or subcomponent has different rules for what characters are valid.");
^
1 warning generated.

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/NSMutableArray+QueueAdditions.o Classes/Public/NSMutableArray+QueueAdditions.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-gndultymibmclyaifbpnxmplhikv/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/NSMutableArray+QueueAdditions.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/NSMutableArray+QueueAdditions.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/NSMutableArray+QueueAdditions.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/NSMutableArray+QueueAdditions.o

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVCommandQueue.o Classes/Public/CDVCommandQueue.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-gndultymibmclyaifbpnxmplhikv/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVCommandQueue.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVCommandQueue.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVCommandQueue.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVCommandQueue.o

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVPluginResult.o Classes/Public/CDVPluginResult.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-gndultymibmclyaifbpnxmplhikv/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVPluginResult.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVPluginResult.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVPluginResult.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVPluginResult.o

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVPlugin+Resources.o Classes/Public/CDVPlugin+Resources.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-gndultymibmclyaifbpnxmplhikv/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVPlugin+Resources.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVPlugin+Resources.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVPlugin+Resources.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVPlugin+Resources.o

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVURLProtocol.o Classes/Public/CDVURLProtocol.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-gndultymibmclyaifbpnxmplhikv/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVURLProtocol.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVURLProtocol.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVURLProtocol.o
/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:60:9: warning: 'ALAssetsLibraryAssetForURLResultBlock' is deprecated: first deprecated in iOS 9.0 - Use fetchAssetsWithLocalIdentifiers:options: on PHAsset to fetch assets by local identifier (or to lookup PHAssets by a previously known ALAssetPropertyAssetURL use fetchAssetsWithALAssetURLs:options:) from the Photos framework instead [-Wdeprecated-declarations]
        ALAssetsLibraryAssetForURLResultBlock resultBlock = ^(ALAsset* asset) {
        ^
In module 'AssetsLibrary' imported from /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:20:
/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk/System/Library/Frameworks/AssetsLibrary.framework/Headers/ALAssetsLibrary.h:64:16: note: 'ALAssetsLibraryAssetForURLResultBlock' has been explicitly marked deprecated here
typedef void (^ALAssetsLibraryAssetForURLResultBlock)(ALAsset *asset) NS_DEPRECATED_IOS(4_0, 9_0, "Use fetchAssetsWithLocalIdentifiers:options: on PHAsset to fetch assets by local identifier (or to lookup PHAssets by a previously known ALAssetPropertyAssetURL use fetchAssetsWithALAssetURLs:options:) from the Photos framework instead");
               ^
/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:63:69: warning: 'defaultRepresentation' is deprecated: first deprecated in iOS 9.0 - Use PHImageRequestOptions with the PHImageManager from the Photos framework instead [-Wdeprecated-declarations]
                ALAssetRepresentation* assetRepresentation = [asset defaultRepresentation];
                                                                    ^
In module 'AssetsLibrary' imported from /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:20:
/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk/System/Library/Frameworks/AssetsLibrary.framework/Headers/ALAsset.h:51:1: note: 'defaultRepresentation' has been explicitly marked deprecated here
- (ALAssetRepresentation *)defaultRepresentation NS_DEPRECATED_IOS(4_0, 9_0, "Use PHImageRequestOptions with the PHImageManager from the Photos framework instead");
^
/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:64:142: warning: 'UTI' is deprecated: first deprecated in iOS 9.0 - Use requestImageDataForAsset:options:resultHandler: on PHImageManager for a PHAsset to request image data from the Photos framework and check the dataUTI passed to your result handler instead [-Wdeprecated-declarations]
                NSString* MIMEType = (__bridge_transfer NSString*)UTTypeCopyPreferredTagWithClass((__bridge CFStringRef)[assetRepresentation UTI], kUTTagClassMIMEType);
                                                                                                                                             ^
In module 'AssetsLibrary' imported from /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:20:
/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk/System/Library/Frameworks/AssetsLibrary.framework/Headers/ALAssetRepresentation.h:28:1: note: 'UTI' has been explicitly marked deprecated here
- (NSString *)UTI NS_DEPRECATED_IOS(4_0, 9_0, "Use requestImageDataForAsset:options:resultHandler: on PHImageManager for a PHAsset to request image data from the Photos framework and check the dataUTI passed to your result handler instead");
^
/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:65:82: warning: 'size' is deprecated: first deprecated in iOS 9.0 - Use requestImageDataForAsset:options:resultHandler: on PHImageManager to request image data for a PHAsset from the Photos framework instead [-Wdeprecated-declarations]
                Byte* buffer = (Byte*)malloc((unsigned long)[assetRepresentation size]);
                                                                                 ^
In module 'AssetsLibrary' imported from /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:20:
/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk/System/Library/Frameworks/AssetsLibrary.framework/Headers/ALAssetRepresentation.h:34:1: note: 'size' has been explicitly marked deprecated here
- (long long)size NS_DEPRECATED_IOS(4_0, 9_0, "Use requestImageDataForAsset:options:resultHandler: on PHImageManager to request image data for a PHAsset from the Photos framework instead");
^
/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:66:133: warning: 'size' is deprecated: first deprecated in iOS 9.0 - Use requestImageDataForAsset:options:resultHandler: on PHImageManager to request image data for a PHAsset from the Photos framework instead [-Wdeprecated-declarations]
                NSUInteger bufferSize = [assetRepresentation getBytes:buffer fromOffset:0.0 length:(NSUInteger)[assetRepresentation size] error:nil];
                                                                                                                                    ^
In module 'AssetsLibrary' imported from /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:20:
/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk/System/Library/Frameworks/AssetsLibrary.framework/Headers/ALAssetRepresentation.h:34:1: note: 'size' has been explicitly marked deprecated here
- (long long)size NS_DEPRECATED_IOS(4_0, 9_0, "Use requestImageDataForAsset:options:resultHandler: on PHImageManager to request image data for a PHAsset from the Photos framework instead");
^
/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:66:62: warning: 'getBytes:fromOffset:length:error:' is deprecated: first deprecated in iOS 9.0 - Use requestImageDataForAsset:options:resultHandler: on PHImageManager to request image data for a PHAsset from the Photos framework instead [-Wdeprecated-declarations]
                NSUInteger bufferSize = [assetRepresentation getBytes:buffer fromOffset:0.0 length:(NSUInteger)[assetRepresentation size] error:nil];
                                                             ^
In module 'AssetsLibrary' imported from /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:20:
/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk/System/Library/Frameworks/AssetsLibrary.framework/Headers/ALAssetRepresentation.h:40:1: note: 'getBytes:fromOffset:length:error:' has been explicitly marked deprecated here
- (NSUInteger)getBytes:(uint8_t *)buffer fromOffset:(long long)offset length:(NSUInteger)length error:(NSError **)error NS_DEPRECATED_IOS(4_0, 9_0, "Use requestImageDataForAsset:options:resultHandler: on PHImageManager to request image data for a PHAsset from the Photos framework instead");
^
/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:60:63: warning: 'ALAsset' is deprecated: first deprecated in iOS 9.0 - Use PHAsset from the Photos framework instead [-Wdeprecated-declarations]
        ALAssetsLibraryAssetForURLResultBlock resultBlock = ^(ALAsset* asset) {
                                                              ^
In module 'AssetsLibrary' imported from /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:20:
/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk/System/Library/Frameworks/AssetsLibrary.framework/Headers/ALAsset.h:42:12: note: 'ALAsset' has been explicitly marked deprecated here
@interface ALAsset : NSObject {
           ^
/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:63:17: warning: 'ALAssetRepresentation' is deprecated: first deprecated in iOS 9.0 - Use PHImageRequestOptions with the PHImageManager from the Photos framework instead [-Wdeprecated-declarations]
                ALAssetRepresentation* assetRepresentation = [asset defaultRepresentation];
                ^
In module 'AssetsLibrary' imported from /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:20:
/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk/System/Library/Frameworks/AssetsLibrary.framework/Headers/ALAssetRepresentation.h:22:12: note: 'ALAssetRepresentation' has been explicitly marked deprecated here
@interface ALAssetRepresentation : NSObject {
           ^
/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:74:9: warning: 'ALAssetsLibraryAccessFailureBlock' is deprecated: first deprecated in iOS 9.0 - Use the Photos framework instead [-Wdeprecated-declarations]
        ALAssetsLibraryAccessFailureBlock failureBlock = ^(NSError* error) {
        ^
In module 'AssetsLibrary' imported from /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:20:
/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk/System/Library/Frameworks/AssetsLibrary.framework/Headers/ALAssetsLibrary.h:71:16: note: 'ALAssetsLibraryAccessFailureBlock' has been explicitly marked deprecated here
typedef void (^ALAssetsLibraryAccessFailureBlock)(NSError *error) NS_DEPRECATED_IOS(4_0, 9_0, "Use the Photos framework instead");
               ^
/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:79:9: warning: 'ALAssetsLibrary' is deprecated: first deprecated in iOS 9.0 - Use PHPhotoLibrary from the Photos framework instead [-Wdeprecated-declarations]
        ALAssetsLibrary* assetsLibrary = [[ALAssetsLibrary alloc] init];
        ^
In module 'AssetsLibrary' imported from /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:20:
/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk/System/Library/Frameworks/AssetsLibrary.framework/Headers/ALAssetsLibrary.h:80:12: note: 'ALAssetsLibrary' has been explicitly marked deprecated here
@interface ALAssetsLibrary : NSObject {
           ^
/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:79:60: warning: 'ALAssetsLibrary' is deprecated: first deprecated in iOS 9.0 - Use PHPhotoLibrary from the Photos framework instead [-Wdeprecated-declarations]
        ALAssetsLibrary* assetsLibrary = [[ALAssetsLibrary alloc] init];
                                                           ^
In module 'AssetsLibrary' imported from /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:20:
/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk/System/Library/Frameworks/AssetsLibrary.framework/Headers/ALAssetsLibrary.h:80:12: note: 'ALAssetsLibrary' has been explicitly marked deprecated here
@interface ALAssetsLibrary : NSObject {
           ^
/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:80:24: warning: 'assetForURL:resultBlock:failureBlock:' is deprecated: first deprecated in iOS 9.0 - Use fetchAssetsWithLocalIdentifiers:options: on PHAsset to fetch assets by local identifier (or to lookup PHAssets by a previously known ALAssetPropertyAssetURL use fetchAssetsWithALAssetURLs:options:) from the Photos framework instead [-Wdeprecated-declarations]
        [assetsLibrary assetForURL:url resultBlock:resultBlock failureBlock:failureBlock];
                       ^
In module 'AssetsLibrary' imported from /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:20:
/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk/System/Library/Frameworks/AssetsLibrary.framework/Headers/ALAssetsLibrary.h:95:1: note: 'assetForURL:resultBlock:failureBlock:' has been explicitly marked deprecated here
- (void)assetForURL:(NSURL *)assetURL resultBlock:(ALAssetsLibraryAssetForURLResultBlock)resultBlock failureBlock:(ALAssetsLibraryAccessFailureBlock)failureBlock NS_DEPRECATED_IOS(4_0, 9_0, "Use fetchAssetsWithLocalIdentifiers:options: on PHAsset to fetch assets by local identifier (or to lookup PHAssets by a previously known ALAssetPropertyAssetURL use fetchAssetsWithALAssetURLs:options:) from the Photos framework instead");
^
12 warnings generated.

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVUIWebViewEngine.o Classes/Private/Plugins/CDVUIWebViewEngine/CDVUIWebViewEngine.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-gndultymibmclyaifbpnxmplhikv/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVUIWebViewEngine.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVUIWebViewEngine.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Private/Plugins/CDVUIWebViewEngine/CDVUIWebViewEngine.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVUIWebViewEngine.o

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVPlugin.o Classes/Public/CDVPlugin.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-gndultymibmclyaifbpnxmplhikv/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVPlugin.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVPlugin.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVPlugin.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVPlugin.o

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVLocalStorage.o Classes/Private/Plugins/CDVLocalStorage/CDVLocalStorage.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-gndultymibmclyaifbpnxmplhikv/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVLocalStorage.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVLocalStorage.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Private/Plugins/CDVLocalStorage/CDVLocalStorage.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVLocalStorage.o

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVIntentAndNavigationFilter.o Classes/Private/Plugins/CDVIntentAndNavigationFilter/CDVIntentAndNavigationFilter.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-gndultymibmclyaifbpnxmplhikv/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVIntentAndNavigationFilter.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVIntentAndNavigationFilter.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Private/Plugins/CDVIntentAndNavigationFilter/CDVIntentAndNavigationFilter.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVIntentAndNavigationFilter.o
/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Private/Plugins/CDVIntentAndNavigationFilter/CDVIntentAndNavigationFilter.m:121:52: warning: 'openURL:' is deprecated: first deprecated in iOS 10.0 - Please use openURL:options:completionHandler: instead [-Wdeprecated-declarations]
                [[UIApplication sharedApplication] openURL:url];
                                                   ^
In module 'UIKit' imported from /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVPlugin.h:21:
/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk/System/Library/Frameworks/UIKit.framework/Headers/UIApplication.h:125:1: note: 'openURL:' has been explicitly marked deprecated here
- (BOOL)openURL:(NSURL*)url NS_DEPRECATED_IOS(2_0, 10_0, "Please use openURL:options:completionHandler: instead") NS_EXTENSION_UNAVAILABLE_IOS("");
^
1 warning generated.

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVViewController.o Classes/Public/CDVViewController.m normal arm64 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch arm64 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wshorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/arm64 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-ggataxlbeiubftcsgtuizgehugsd/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVViewController.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVViewController.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVViewController.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVViewController.o
/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVViewController.m:335:99: warning: 'stringByAddingPercentEscapesUsingEncoding:' is deprecated: first deprecated in iOS 9.0 - Use -stringByAddingPercentEncodingWithAllowedCharacters: instead, which always uses the recommended UTF-8 encoding, and which encodes for a specific URL component or subcomponent since each URL component or subcomponent has different rules for what characters are valid. [-Wdeprecated-declarations]
                errorUrl = [NSURL URLWithString:[NSString stringWithFormat:@"?error=%@", [loadErr stringByAddingPercentEscapesUsingEncoding:NSUTF8StringEncoding]] relativeToURL:errorUrl];
                                                                                                  ^
In module 'Foundation' imported from /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVAppDelegate.h:20:
/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk/System/Library/Frameworks/Foundation.framework/Headers/NSURL.h:541:1: note: 'stringByAddingPercentEscapesUsingEncoding:' has been explicitly marked deprecated here
- (nullable NSString *)stringByAddingPercentEscapesUsingEncoding:(NSStringEncoding)enc NS_DEPRECATED(10_0, 10_11, 2_0, 9_0, "Use -stringByAddingPercentEncodingWithAllowedCharacters: instead, which always uses the recommended UTF-8 encoding, and which encodes for a specific URL component or subcomponent since each URL component or subcomponent has different rules for what characters are valid.");
^
1 warning generated.

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/NSDictionary+CordovaPreferences.o Classes/Public/NSDictionary+CordovaPreferences.m normal arm64 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch arm64 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wshorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/arm64 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-ggataxlbeiubftcsgtuizgehugsd/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/NSDictionary+CordovaPreferences.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/NSDictionary+CordovaPreferences.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/NSDictionary+CordovaPreferences.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/NSDictionary+CordovaPreferences.o

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVAppDelegate.o Classes/Public/CDVAppDelegate.m normal arm64 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch arm64 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wshorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/arm64 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-ggataxlbeiubftcsgtuizgehugsd/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVAppDelegate.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVAppDelegate.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVAppDelegate.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVAppDelegate.o

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVUIWebViewDelegate.o Classes/Private/Plugins/CDVUIWebViewEngine/CDVUIWebViewDelegate.m normal arm64 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch arm64 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wshorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/arm64 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-ggataxlbeiubftcsgtuizgehugsd/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVUIWebViewDelegate.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVUIWebViewDelegate.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Private/Plugins/CDVUIWebViewEngine/CDVUIWebViewDelegate.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVUIWebViewDelegate.o

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVCommandDelegateImpl.o Classes/Public/CDVCommandDelegateImpl.m normal arm64 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch arm64 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wshorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/arm64 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-ggataxlbeiubftcsgtuizgehugsd/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVCommandDelegateImpl.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVCommandDelegateImpl.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVCommandDelegateImpl.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVCommandDelegateImpl.o

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVJSON_private.o Classes/Private/CDVJSON_private.m normal arm64 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch arm64 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wshorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/arm64 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-ggataxlbeiubftcsgtuizgehugsd/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVJSON_private.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVJSON_private.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Private/CDVJSON_private.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVJSON_private.o

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVWhitelist.o Classes/Public/CDVWhitelist.m normal arm64 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch arm64 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wshorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/arm64 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-ggataxlbeiubftcsgtuizgehugsd/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVWhitelist.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVWhitelist.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVWhitelist.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVWhitelist.o
/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVWhitelist.m:259:134: warning: 'stringByAddingPercentEscapesUsingEncoding:' is deprecated: first deprecated in iOS 9.0 - Use -stringByAddingPercentEncodingWithAllowedCharacters: instead, which always uses the recommended UTF-8 encoding, and which encodes for a specific URL component or subcomponent since each URL component or subcomponent has different rules for what characters are valid. [-Wdeprecated-declarations]
        NSURL* newUrl = [NSURL URLWithString:[NSString stringWithFormat:@"%@://%@%@", kCDVDefaultSchemeName, [url host], [[url path] stringByAddingPercentEscapesUsingEncoding:NSUTF8StringEncoding]]];
                                                                                                                                     ^
In module 'Foundation' imported from /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVWhitelist.h:20:
/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk/System/Library/Frameworks/Foundation.framework/Headers/NSURL.h:541:1: note: 'stringByAddingPercentEscapesUsingEncoding:' has been explicitly marked deprecated here
- (nullable NSString *)stringByAddingPercentEscapesUsingEncoding:(NSStringEncoding)enc NS_DEPRECATED(10_0, 10_11, 2_0, 9_0, "Use -stringByAddingPercentEncodingWithAllowedCharacters: instead, which always uses the recommended UTF-8 encoding, and which encodes for a specific URL component or subcomponent since each URL component or subcomponent has different rules for what characters are valid.");
^
1 warning generated.

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVInvokedUrlCommand.o Classes/Public/CDVInvokedUrlCommand.m normal arm64 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch arm64 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wshorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/arm64 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-ggataxlbeiubftcsgtuizgehugsd/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVInvokedUrlCommand.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVInvokedUrlCommand.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVInvokedUrlCommand.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVInvokedUrlCommand.o

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVTimer.o Classes/Public/CDVTimer.m normal arm64 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch arm64 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wshorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/arm64 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-ggataxlbeiubftcsgtuizgehugsd/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVTimer.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVTimer.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVTimer.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVTimer.o

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVUserAgentUtil.o Classes/Public/CDVUserAgentUtil.m normal arm64 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch arm64 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wshorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/arm64 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-ggataxlbeiubftcsgtuizgehugsd/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVUserAgentUtil.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVUserAgentUtil.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVUserAgentUtil.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVUserAgentUtil.o

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVConfigParser.o Classes/Public/CDVConfigParser.m normal arm64 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch arm64 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wshorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/arm64 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-ggataxlbeiubftcsgtuizgehugsd/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVConfigParser.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVConfigParser.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVConfigParser.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVConfigParser.o

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVGestureHandler.o Classes/Private/Plugins/CDVGestureHandler/CDVGestureHandler.m normal arm64 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch arm64 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wshorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/arm64 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-ggataxlbeiubftcsgtuizgehugsd/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVGestureHandler.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVGestureHandler.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Private/Plugins/CDVGestureHandler/CDVGestureHandler.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVGestureHandler.o

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVHandleOpenURL.o Classes/Private/Plugins/CDVHandleOpenURL/CDVHandleOpenURL.m normal arm64 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch arm64 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wshorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/arm64 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-ggataxlbeiubftcsgtuizgehugsd/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVHandleOpenURL.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVHandleOpenURL.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Private/Plugins/CDVHandleOpenURL/CDVHandleOpenURL.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVHandleOpenURL.o

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVUIWebViewNavigationDelegate.o Classes/Private/Plugins/CDVUIWebViewEngine/CDVUIWebViewNavigationDelegate.m normal arm64 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch arm64 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wshorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/arm64 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-ggataxlbeiubftcsgtuizgehugsd/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVUIWebViewNavigationDelegate.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVUIWebViewNavigationDelegate.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Private/Plugins/CDVUIWebViewEngine/CDVUIWebViewNavigationDelegate.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVUIWebViewNavigationDelegate.o
/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Private/Plugins/CDVUIWebViewEngine/CDVUIWebViewNavigationDelegate.m:81:91: warning: 'stringByAddingPercentEscapesUsingEncoding:' is deprecated: first deprecated in iOS 9.0 - Use -stringByAddingPercentEncodingWithAllowedCharacters: instead, which always uses the recommended UTF-8 encoding, and which encodes for a specific URL component or subcomponent since each URL component or subcomponent has different rules for what characters are valid. [-Wdeprecated-declarations]
        errorUrl = [NSURL URLWithString:[NSString stringWithFormat:@"?error=%@", [message stringByAddingPercentEscapesUsingEncoding:NSUTF8StringEncoding]] relativeToURL:errorUrl];
                                                                                          ^
In module 'Foundation' imported from /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVPlugin.h:20:
/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk/System/Library/Frameworks/Foundation.framework/Headers/NSURL.h:541:1: note: 'stringByAddingPercentEscapesUsingEncoding:' has been explicitly marked deprecated here
- (nullable NSString *)stringByAddingPercentEscapesUsingEncoding:(NSStringEncoding)enc NS_DEPRECATED(10_0, 10_11, 2_0, 9_0, "Use -stringByAddingPercentEncodingWithAllowedCharacters: instead, which always uses the recommended UTF-8 encoding, and which encodes for a specific URL component or subcomponent since each URL component or subcomponent has different rules for what characters are valid.");
^
1 warning generated.

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/NSMutableArray+QueueAdditions.o Classes/Public/NSMutableArray+QueueAdditions.m normal arm64 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch arm64 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wshorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/arm64 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-ggataxlbeiubftcsgtuizgehugsd/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/NSMutableArray+QueueAdditions.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/NSMutableArray+QueueAdditions.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/NSMutableArray+QueueAdditions.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/NSMutableArray+QueueAdditions.o

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVCommandQueue.o Classes/Public/CDVCommandQueue.m normal arm64 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch arm64 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wshorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/arm64 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-ggataxlbeiubftcsgtuizgehugsd/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVCommandQueue.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVCommandQueue.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVCommandQueue.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVCommandQueue.o

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVPluginResult.o Classes/Public/CDVPluginResult.m normal arm64 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch arm64 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wshorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/arm64 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-ggataxlbeiubftcsgtuizgehugsd/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVPluginResult.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVPluginResult.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVPluginResult.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVPluginResult.o

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVPlugin+Resources.o Classes/Public/CDVPlugin+Resources.m normal arm64 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch arm64 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wshorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/arm64 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-ggataxlbeiubftcsgtuizgehugsd/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVPlugin+Resources.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVPlugin+Resources.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVPlugin+Resources.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVPlugin+Resources.o

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVURLProtocol.o Classes/Public/CDVURLProtocol.m normal arm64 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch arm64 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wshorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/arm64 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-ggataxlbeiubftcsgtuizgehugsd/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVURLProtocol.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVURLProtocol.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVURLProtocol.o
/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:60:9: warning: 'ALAssetsLibraryAssetForURLResultBlock' is deprecated: first deprecated in iOS 9.0 - Use fetchAssetsWithLocalIdentifiers:options: on PHAsset to fetch assets by local identifier (or to lookup PHAssets by a previously known ALAssetPropertyAssetURL use fetchAssetsWithALAssetURLs:options:) from the Photos framework instead [-Wdeprecated-declarations]
        ALAssetsLibraryAssetForURLResultBlock resultBlock = ^(ALAsset* asset) {
        ^
In module 'AssetsLibrary' imported from /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:20:
/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk/System/Library/Frameworks/AssetsLibrary.framework/Headers/ALAssetsLibrary.h:64:16: note: 'ALAssetsLibraryAssetForURLResultBlock' has been explicitly marked deprecated here
typedef void (^ALAssetsLibraryAssetForURLResultBlock)(ALAsset *asset) NS_DEPRECATED_IOS(4_0, 9_0, "Use fetchAssetsWithLocalIdentifiers:options: on PHAsset to fetch assets by local identifier (or to lookup PHAssets by a previously known ALAssetPropertyAssetURL use fetchAssetsWithALAssetURLs:options:) from the Photos framework instead");
               ^
/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:63:69: warning: 'defaultRepresentation' is deprecated: first deprecated in iOS 9.0 - Use PHImageRequestOptions with the PHImageManager from the Photos framework instead [-Wdeprecated-declarations]
                ALAssetRepresentation* assetRepresentation = [asset defaultRepresentation];
                                                                    ^
In module 'AssetsLibrary' imported from /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:20:
/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk/System/Library/Frameworks/AssetsLibrary.framework/Headers/ALAsset.h:51:1: note: 'defaultRepresentation' has been explicitly marked deprecated here
- (ALAssetRepresentation *)defaultRepresentation NS_DEPRECATED_IOS(4_0, 9_0, "Use PHImageRequestOptions with the PHImageManager from the Photos framework instead");
^
/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:64:142: warning: 'UTI' is deprecated: first deprecated in iOS 9.0 - Use requestImageDataForAsset:options:resultHandler: on PHImageManager for a PHAsset to request image data from the Photos framework and check the dataUTI passed to your result handler instead [-Wdeprecated-declarations]
                NSString* MIMEType = (__bridge_transfer NSString*)UTTypeCopyPreferredTagWithClass((__bridge CFStringRef)[assetRepresentation UTI], kUTTagClassMIMEType);
                                                                                                                                             ^
In module 'AssetsLibrary' imported from /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:20:
/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk/System/Library/Frameworks/AssetsLibrary.framework/Headers/ALAssetRepresentation.h:28:1: note: 'UTI' has been explicitly marked deprecated here
- (NSString *)UTI NS_DEPRECATED_IOS(4_0, 9_0, "Use requestImageDataForAsset:options:resultHandler: on PHImageManager for a PHAsset to request image data from the Photos framework and check the dataUTI passed to your result handler instead");
^
/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:65:82: warning: 'size' is deprecated: first deprecated in iOS 9.0 - Use requestImageDataForAsset:options:resultHandler: on PHImageManager to request image data for a PHAsset from the Photos framework instead [-Wdeprecated-declarations]
                Byte* buffer = (Byte*)malloc((unsigned long)[assetRepresentation size]);
                                                                                 ^
In module 'AssetsLibrary' imported from /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:20:
/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk/System/Library/Frameworks/AssetsLibrary.framework/Headers/ALAssetRepresentation.h:34:1: note: 'size' has been explicitly marked deprecated here
- (long long)size NS_DEPRECATED_IOS(4_0, 9_0, "Use requestImageDataForAsset:options:resultHandler: on PHImageManager to request image data for a PHAsset from the Photos framework instead");
^
/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:66:133: warning: 'size' is deprecated: first deprecated in iOS 9.0 - Use requestImageDataForAsset:options:resultHandler: on PHImageManager to request image data for a PHAsset from the Photos framework instead [-Wdeprecated-declarations]
                NSUInteger bufferSize = [assetRepresentation getBytes:buffer fromOffset:0.0 length:(NSUInteger)[assetRepresentation size] error:nil];
                                                                                                                                    ^
In module 'AssetsLibrary' imported from /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:20:
/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk/System/Library/Frameworks/AssetsLibrary.framework/Headers/ALAssetRepresentation.h:34:1: note: 'size' has been explicitly marked deprecated here
- (long long)size NS_DEPRECATED_IOS(4_0, 9_0, "Use requestImageDataForAsset:options:resultHandler: on PHImageManager to request image data for a PHAsset from the Photos framework instead");
^
/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:66:62: warning: 'getBytes:fromOffset:length:error:' is deprecated: first deprecated in iOS 9.0 - Use requestImageDataForAsset:options:resultHandler: on PHImageManager to request image data for a PHAsset from the Photos framework instead [-Wdeprecated-declarations]
                NSUInteger bufferSize = [assetRepresentation getBytes:buffer fromOffset:0.0 length:(NSUInteger)[assetRepresentation size] error:nil];
                                                             ^
In module 'AssetsLibrary' imported from /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:20:
/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk/System/Library/Frameworks/AssetsLibrary.framework/Headers/ALAssetRepresentation.h:40:1: note: 'getBytes:fromOffset:length:error:' has been explicitly marked deprecated here
- (NSUInteger)getBytes:(uint8_t *)buffer fromOffset:(long long)offset length:(NSUInteger)length error:(NSError **)error NS_DEPRECATED_IOS(4_0, 9_0, "Use requestImageDataForAsset:options:resultHandler: on PHImageManager to request image data for a PHAsset from the Photos framework instead");
^
/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:60:63: warning: 'ALAsset' is deprecated: first deprecated in iOS 9.0 - Use PHAsset from the Photos framework instead [-Wdeprecated-declarations]
        ALAssetsLibraryAssetForURLResultBlock resultBlock = ^(ALAsset* asset) {
                                                              ^
In module 'AssetsLibrary' imported from /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:20:
/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk/System/Library/Frameworks/AssetsLibrary.framework/Headers/ALAsset.h:42:12: note: 'ALAsset' has been explicitly marked deprecated here
@interface ALAsset : NSObject {
           ^
/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:63:17: warning: 'ALAssetRepresentation' is deprecated: first deprecated in iOS 9.0 - Use PHImageRequestOptions with the PHImageManager from the Photos framework instead [-Wdeprecated-declarations]
                ALAssetRepresentation* assetRepresentation = [asset defaultRepresentation];
                ^
In module 'AssetsLibrary' imported from /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:20:
/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk/System/Library/Frameworks/AssetsLibrary.framework/Headers/ALAssetRepresentation.h:22:12: note: 'ALAssetRepresentation' has been explicitly marked deprecated here
@interface ALAssetRepresentation : NSObject {
           ^
/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:74:9: warning: 'ALAssetsLibraryAccessFailureBlock' is deprecated: first deprecated in iOS 9.0 - Use the Photos framework instead [-Wdeprecated-declarations]
        ALAssetsLibraryAccessFailureBlock failureBlock = ^(NSError* error) {
        ^
In module 'AssetsLibrary' imported from /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:20:
/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk/System/Library/Frameworks/AssetsLibrary.framework/Headers/ALAssetsLibrary.h:71:16: note: 'ALAssetsLibraryAccessFailureBlock' has been explicitly marked deprecated here
typedef void (^ALAssetsLibraryAccessFailureBlock)(NSError *error) NS_DEPRECATED_IOS(4_0, 9_0, "Use the Photos framework instead");
               ^
/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:79:9: warning: 'ALAssetsLibrary' is deprecated: first deprecated in iOS 9.0 - Use PHPhotoLibrary from the Photos framework instead [-Wdeprecated-declarations]
        ALAssetsLibrary* assetsLibrary = [[ALAssetsLibrary alloc] init];
        ^
In module 'AssetsLibrary' imported from /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:20:
/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk/System/Library/Frameworks/AssetsLibrary.framework/Headers/ALAssetsLibrary.h:80:12: note: 'ALAssetsLibrary' has been explicitly marked deprecated here
@interface ALAssetsLibrary : NSObject {
           ^
/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:79:60: warning: 'ALAssetsLibrary' is deprecated: first deprecated in iOS 9.0 - Use PHPhotoLibrary from the Photos framework instead [-Wdeprecated-declarations]
        ALAssetsLibrary* assetsLibrary = [[ALAssetsLibrary alloc] init];
                                                           ^
In module 'AssetsLibrary' imported from /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:20:
/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk/System/Library/Frameworks/AssetsLibrary.framework/Headers/ALAssetsLibrary.h:80:12: note: 'ALAssetsLibrary' has been explicitly marked deprecated here
@interface ALAssetsLibrary : NSObject {
           ^
/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:80:24: warning: 'assetForURL:resultBlock:failureBlock:' is deprecated: first deprecated in iOS 9.0 - Use fetchAssetsWithLocalIdentifiers:options: on PHAsset to fetch assets by local identifier (or to lookup PHAssets by a previously known ALAssetPropertyAssetURL use fetchAssetsWithALAssetURLs:options:) from the Photos framework instead [-Wdeprecated-declarations]
        [assetsLibrary assetForURL:url resultBlock:resultBlock failureBlock:failureBlock];
                       ^
In module 'AssetsLibrary' imported from /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m:20:
/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk/System/Library/Frameworks/AssetsLibrary.framework/Headers/ALAssetsLibrary.h:95:1: note: 'assetForURL:resultBlock:failureBlock:' has been explicitly marked deprecated here
- (void)assetForURL:(NSURL *)assetURL resultBlock:(ALAssetsLibraryAssetForURLResultBlock)resultBlock failureBlock:(ALAssetsLibraryAccessFailureBlock)failureBlock NS_DEPRECATED_IOS(4_0, 9_0, "Use fetchAssetsWithLocalIdentifiers:options: on PHAsset to fetch assets by local identifier (or to lookup PHAssets by a previously known ALAssetPropertyAssetURL use fetchAssetsWithALAssetURLs:options:) from the Photos framework instead");
^
12 warnings generated.

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVUIWebViewEngine.o Classes/Private/Plugins/CDVUIWebViewEngine/CDVUIWebViewEngine.m normal arm64 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch arm64 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wshorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/arm64 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-ggataxlbeiubftcsgtuizgehugsd/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVUIWebViewEngine.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVUIWebViewEngine.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Private/Plugins/CDVUIWebViewEngine/CDVUIWebViewEngine.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVUIWebViewEngine.o

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVPlugin.o Classes/Public/CDVPlugin.m normal arm64 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch arm64 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wshorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/arm64 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-ggataxlbeiubftcsgtuizgehugsd/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVPlugin.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVPlugin.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVPlugin.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVPlugin.o

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVLocalStorage.o Classes/Private/Plugins/CDVLocalStorage/CDVLocalStorage.m normal arm64 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch arm64 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wshorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/arm64 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-ggataxlbeiubftcsgtuizgehugsd/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVLocalStorage.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVLocalStorage.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Private/Plugins/CDVLocalStorage/CDVLocalStorage.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVLocalStorage.o

CompileC /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVIntentAndNavigationFilter.o Classes/Private/Plugins/CDVIntentAndNavigationFilter/CDVIntentAndNavigationFilter.m normal arm64 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch arm64 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -fmodules-cache-path=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wshorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -DTEST=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=10.0 -g -Wno-sign-conversion -Wno-infinite-recursion -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/arm64 -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-ggataxlbeiubftcsgtuizgehugsd/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVIntentAndNavigationFilter.d --serialize-diagnostics /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVIntentAndNavigationFilter.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Private/Plugins/CDVIntentAndNavigationFilter/CDVIntentAndNavigationFilter.m -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/CDVIntentAndNavigationFilter.o
/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Private/Plugins/CDVIntentAndNavigationFilter/CDVIntentAndNavigationFilter.m:121:52: warning: 'openURL:' is deprecated: first deprecated in iOS 10.0 - Please use openURL:options:completionHandler: instead [-Wdeprecated-declarations]
                [[UIApplication sharedApplication] openURL:url];
                                                   ^
In module 'UIKit' imported from /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVPlugin.h:21:
/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk/System/Library/Frameworks/UIKit.framework/Headers/UIApplication.h:125:1: note: 'openURL:' has been explicitly marked deprecated here
- (BOOL)openURL:(NSURL*)url NS_DEPRECATED_IOS(2_0, 10_0, "Please use openURL:options:completionHandler: instead") NS_EXTENSION_UNAVAILABLE_IOS("");
^
1 warning generated.

Libtool /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/libCordova.a normal armv7
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export IPHONEOS_DEPLOYMENT_TARGET=10.0
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/libtool -static -arch_only armv7 -syslibroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -L/Users/thali/Github/ThaliTest/platforms/ios/build/device -filelist /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/Cordova.LinkFileList -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/libCordova.a

Libtool /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/libCordova.a normal arm64
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export IPHONEOS_DEPLOYMENT_TARGET=10.0
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/libtool -static -arch_only arm64 -syslibroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -L/Users/thali/Github/ThaliTest/platforms/ios/build/device -filelist /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/Cordova.LinkFileList -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/libCordova.a

CreateUniversalBinary /Users/thali/Github/ThaliTest/platforms/ios/build/device/libCordova.a normal armv7\ arm64
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/libtool -static /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/libCordova.a /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/arm64/libCordova.a -o /Users/thali/Github/ThaliTest/platforms/ios/build/device/libCordova.a

=== BUILD TARGET ThaliTest OF PROJECT ThaliTest WITH CONFIGURATION Debug ===

Check dependencies

Write auxiliary files
write-file /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-project-headers.hmap
/bin/mkdir -p /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7
write-file /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/ThaliTest-OutputFileMap.json
/bin/mkdir -p /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/ThaliTest-Prefix-fzwjddmwpmlrzxbhghclurntkccb
write-file /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/ThaliTest-Prefix-fzwjddmwpmlrzxbhghclurntkccb/ThaliTest-Prefix.pch.pch.hash-criteria
write-file /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-all-target-headers.hmap
write-file /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-all-non-framework-target-headers.hmap
write-file /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-own-target-headers.hmap
write-file /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-generated-files.hmap
/bin/mkdir -p /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/arm64
write-file /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/arm64/ThaliTest-OutputFileMap.json
write-file /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/ThaliTest.LinkFileList
write-file /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/arm64/ThaliTest.LinkFileList
write-file /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest.hmap
/bin/mkdir -p /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/ThaliTest-Prefix-fegdbktnohaxcsglsintahmmbfra
write-file /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/ThaliTest-Prefix-fegdbktnohaxcsglsintahmmbfra/ThaliTest-Prefix.pch.pch.hash-criteria
write-file /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Script-304B58A110DAC018002A0835.sh
chmod 0755 /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Script-304B58A110DAC018002A0835.sh
write-file /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/swift-overrides.hmap

Create product structure
/bin/mkdir -p /Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app

PhaseScriptExecution Copy\ www\ directory /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Script-304B58A110DAC018002A0835.sh
    cd /Users/thali/Github/ThaliTest/platforms/ios
    /bin/sh -c /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Script-304B58A110DAC018002A0835.sh

CpResource ThaliTest/Resources/jxcore_cordova.js build/device/ThaliTest.app/jxcore_cordova.js
    cd /Users/thali/Github/ThaliTest/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Resources/jxcore_cordova.js /Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app

CompileXIB ThaliTest/Classes/MainViewController.xib
    cd /Users/thali/Github/ThaliTest/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    export XCODE_DEVELOPER_USR_PATH=/Applications/Xcode.app/Contents/Developer/usr/bin/..
    /Applications/Xcode.app/Contents/Developer/usr/bin/ibtool --errors --warnings --notices --module ThaliTest --output-partial-info-plist /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/MainViewController-PartialInfo.plist --auto-activate-custom-fonts --target-device iphone --target-device ipad --minimum-deployment-target 10.0 --output-format human-readable-text --compile /Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/MainViewController.nib /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Classes/MainViewController.xib

CompileStoryboard ThaliTest/CDVLaunchScreen.storyboard
    cd /Users/thali/Github/ThaliTest/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    export XCODE_DEVELOPER_USR_PATH=/Applications/Xcode.app/Contents/Developer/usr/bin/..
    /Applications/Xcode.app/Contents/Developer/usr/bin/ibtool --errors --warnings --notices --module ThaliTest --output-partial-info-plist /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/CDVLaunchScreen-SBPartialInfo.plist --auto-activate-custom-fonts --target-device iphone --target-device ipad --minimum-deployment-target 10.0 --output-format human-readable-text --compilation-directory /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/CDVLaunchScreen.storyboard

CompileAssetCatalog build/device/ThaliTest.app ThaliTest/Images.xcassets
    cd /Users/thali/Github/ThaliTest/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    /Applications/Xcode.app/Contents/Developer/usr/bin/actool --output-format human-readable-text --notices --warnings --export-dependency-info /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/assetcatalog_dependencies --output-partial-info-plist /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/assetcatalog_generated_info.plist --app-icon AppIcon --launch-image LaunchImage --compress-pngs --enable-on-demand-resources YES --sticker-pack-identifier-prefix .sticker-pack. --target-device iphone --target-device ipad --minimum-deployment-target 10.0 --platform iphoneos --product-type com.apple.product-type.application --compile /Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Images.xcassets
/* com.apple.actool.document.notices */
/Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Images.xcassets:./AppIcon.appiconset/[][iphone][57x57][][][1x]: notice: 57x57 app icons only apply to iPhone apps targeting releases of iOS prior to 7.0
/Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Images.xcassets:./AppIcon.appiconset/[][iphone][57x57][][][2x]: notice: 57x57@2x app icons only apply to iPhone apps targeting releases of iOS prior to 7.0
/Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Images.xcassets:./AppIcon.appiconset/[][ipad][50x50][][][1x]: notice: 50x50 iPad spotlight icons only apply to iPad apps targeting releases of iOS prior to 7.0
/Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Images.xcassets:./AppIcon.appiconset/[][ipad][50x50][][][2x]: notice: 50x50 iPad spotlight icons only apply to iPad apps targeting releases of iOS prior to 7.0
/Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Images.xcassets:./AppIcon.appiconset/[][ipad][72x72][][][1x]: notice: 72x72 app icons only apply to iPad apps targeting releases of iOS prior to 7.0
/Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Images.xcassets:./AppIcon.appiconset/[][ipad][72x72][][][2x]: notice: 72x72@2x app icons only apply to iPad apps targeting releases of iOS prior to 7.0
/Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Images.xcassets:./AppIcon.appiconset/[][ipad][76x76][][][1x]: notice: (null)
/Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Images.xcassets:./LaunchImage.launchimage/[iphone][][1x][portrait][full-screen][]: notice: This launch image only applies to iOS 6.x and prior but the minimum deployment is 7.0 or later.
/Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Images.xcassets:./LaunchImage.launchimage/[iphone][][2x][portrait][full-screen][]: notice: This launch image only applies to iOS 6.x and prior but the minimum deployment is 7.0 or later.
/Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Images.xcassets:./LaunchImage.launchimage/[iphone][retina4][2x][portrait][full-screen][]: notice: This launch image only applies to iOS 6.x and prior but the minimum deployment is 7.0 or later.
/Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Images.xcassets:./LaunchImage.launchimage/[ipad][][1x][portrait][full-screen][]: notice: This launch image only applies to iOS 6.x and prior but the minimum deployment is 7.0 or later.
/Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Images.xcassets:./LaunchImage.launchimage/[ipad][][2x][portrait][full-screen][]: notice: This launch image only applies to iOS 6.x and prior but the minimum deployment is 7.0 or later.
/Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Images.xcassets:./LaunchImage.launchimage/[iphone][736h][3x][portrait][full-screen][8.0]: notice: This launch image only applies to iOS 6.x and prior but the minimum deployment is 7.0 or later.
/Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Images.xcassets:./LaunchImage.launchimage/[iphone][736h][3x][landscape][full-screen][8.0]: notice: This launch image only applies to iOS 6.x and prior but the minimum deployment is 7.0 or later.
/Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Images.xcassets:./LaunchImage.launchimage/[iphone][667h][2x][portrait][full-screen][8.0]: notice: This launch image only applies to iOS 6.x and prior but the minimum deployment is 7.0 or later.
/* com.apple.actool.compilation-results */
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/AppIcon29x29.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/AppIcon29x29@2x.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/AppIcon29x29@3x.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/AppIcon40x40@2x.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/AppIcon40x40@3x.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/AppIcon57x57.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/AppIcon57x57@2x.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/AppIcon60x60@2x.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/AppIcon60x60@3x.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/AppIcon29x29~ipad.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/AppIcon29x29@2x~ipad.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/AppIcon40x40~ipad.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/AppIcon40x40@2x~ipad.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/AppIcon50x50~ipad.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/AppIcon50x50@2x~ipad.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/AppIcon72x72~ipad.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/AppIcon72x72@2x~ipad.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/AppIcon76x76~ipad.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/AppIcon76x76@2x~ipad.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/AppIcon83.5x83.5@2x~ipad.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/LaunchImage.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/LaunchImage@2x.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/LaunchImage-568h@2x.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/LaunchImage-Portrait~ipad.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/LaunchImage-Portrait@2x~ipad.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/LaunchImage-800-Portrait-736h@3x.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/LaunchImage-800-Landscape-736h@3x.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/LaunchImage-800-667h@2x.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/LaunchImage-700@2x.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/LaunchImage-700-568h@2x.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/LaunchImage-700-Portrait~ipad.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/LaunchImage-700-Landscape~ipad.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/LaunchImage-700-Portrait@2x~ipad.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/LaunchImage-700-Landscape@2x~ipad.png
/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/assetcatalog_generated_info.plist


ProcessInfoPlistFile build/device/ThaliTest.app/Info.plist ThaliTest/ThaliTest-Info.plist
    cd /Users/thali/Github/ThaliTest/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    builtin-infoPlistUtility /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/ThaliTest-Info.plist -genpkginfo /Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/PkgInfo -expandbuildsettings -format binary -platform iphoneos -additionalcontentfile /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/MainViewController-PartialInfo.plist -additionalcontentfile /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/CDVLaunchScreen-SBPartialInfo.plist -additionalcontentfile /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/assetcatalog_generated_info.plist -o /Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/Info.plist

LinkStoryboards
    cd /Users/thali/Github/ThaliTest/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    export XCODE_DEVELOPER_USR_PATH=/Applications/Xcode.app/Contents/Developer/usr/bin/..
    /Applications/Xcode.app/Contents/Developer/usr/bin/ibtool --errors --warnings --notices --module ThaliTest --target-device iphone --target-device ipad --minimum-deployment-target 10.0 --output-format human-readable-text --link /Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/CDVLaunchScreen.storyboardc

CompileSwiftSources normal arm64 com.apple.xcode.tools.swift.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios
    export DEVELOPER_DIR=/Applications/Xcode.app/Contents/Developer
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/.rvm/gems/ruby-2.3.0/bin:/Users/thali/.rvm/gems/ruby-2.3.0@global/bin:/Users/thali/.rvm/rubies/ruby-2.3.0/bin:/Users/thali/Library/Android/sdk/build-tools/25.0.0:/usr/local/bin:/Users/thali/Library/Android/sdk/tools:/usr/bin:/bin:/usr/sbin:/sbin:/Users/thali/.rvm/bin"
    export SDKROOT=/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk
    export TOOLCHAINS=com.apple.dt.toolchain.XcodeDefault
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/swiftc -incremental -module-name ThaliTest -O -DTEST -sdk /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -target arm64-apple-ios10.0 -g -module-cache-path /Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -Xfrontend -serialize-debugging-options -I /Users/thali/Github/ThaliTest/platforms/ios/build/device -F /Users/thali/Github/ThaliTest/platforms/ios/build/device -parse-as-library -c -j2 /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/org.thaliproject.p2p/AppContext.swift -output-file-map /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/arm64/ThaliTest-OutputFileMap.json -parseable-output -serialize-diagnostics -emit-dependencies -emit-module -emit-module-path /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/arm64/ThaliTest.swiftmodule -Xcc -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/swift-overrides.hmap -Xcc -iquote -Xcc /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-generated-files.hmap -Xcc -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-own-target-headers.hmap -Xcc -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-all-target-headers.hmap -Xcc -iquote -Xcc /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-project-headers.hmap -Xcc -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -Xcc -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -Xcc -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -Xcc -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -Xcc -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -Xcc -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources/arm64 -Xcc -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources -Xcc -DDEBUG=1 -Xcc -DDEBUG=1 -Xcc -DTEST=1 -emit-objc-header -emit-objc-header-path /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/arm64/ThaliTest-Swift.h -import-objc-header /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Bridging-Header.h -Xcc -working-directory/Users/thali/Github/ThaliTest/platforms/ios

CompileSwift normal arm64 /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/org.thaliproject.p2p/AppContext.swift
    cd /Users/thali/Github/ThaliTest/platforms/ios
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/swift -frontend -c -primary-file /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/org.thaliproject.p2p/AppContext.swift -target arm64-apple-ios10.0 -Xllvm -aarch64-use-tbi -enable-objc-interop -sdk /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS10.2.sdk -I /Users/thali/Github/ThaliTest/platforms/ios/build/device -F /Users/thali/Github/ThaliTest/platforms/ios/build/device -g -import-objc-header /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Bridging-Header.h -module-cache-path /Users/thali/Library/Developer/Xcode/DerivedData/ModuleCache -D TEST -serialize-debugging-options -Xcc -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/swift-overrides.hmap -Xcc -iquote -Xcc /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-generated-files.hmap -Xcc -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-own-target-headers.hmap -Xcc -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-all-target-headers.hmap -Xcc -iquote -Xcc /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-project-headers.hmap -Xcc -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -Xcc -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -Xcc -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/include -Xcc -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/UninstalledProducts/iphoneos/include -Xcc -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -Xcc -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources/arm64 -Xcc -I/Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources -Xcc -DDEBUG=1 -Xcc -DDEBUG=1 -Xcc -DTEST=1 -Xcc -working-directory/Users/thali/Github/ThaliTest/platforms/ios -emit-module-doc-path /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/arm64/AppContext~partial.swiftdoc -O -parse-as-library -module-name ThaliTest -emit-module-path /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/arm64/AppContext~partial.swiftmodule -serialize-diagnostics-path /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/arm64/AppContext.dia -emit-dependencies-path /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/arm64/AppContext.d -emit-reference-dependencies-path /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/arm64/AppContext.swiftdeps -o /Users/thali/Library/Developer/Xcode/DerivedData/ThaliTest-azwxutkmiicvjcgtlbsxxcywrljp/Build/Intermediates/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/arm64/AppContext.o
/Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/org.thaliproject.p2p/AppContext.swift:12:8: error: no such module 'ThaliCore'
import ThaliCore
       ^


[0;31merror: command 'thali/install/setUpTests.sh $TEST_TYPE $SERVER_ADDRESS' failed with code 1, file 'build.sh' on line 93[0m
./build.sh CI FAILED - build.sh failure[0m

npm WARN thali-test-server@0.0.1 No repository field.
npm WARN thali-test-server@0.0.1 No license field.
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/javascript-state-machine
npm http request GET http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-leveldb-core
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/winston
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/javascript-state-machine
npm http 200 http://192.168.1.100:4873/ip
npm http 304 http://192.168.1.100:4873/lie
npm http 304 http://192.168.1.100:4873/multiplex
npm http 304 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/urlsafe-base64
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-leveldb-core
npm http 200 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/uuid
npm http 200 http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/content-type
npm http 200 http://192.168.1.100:4873/bytes
npm http 304 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/type-is
npm http 200 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/http-errors
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
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/send
npm http 304 http://192.168.1.100:4873/serve-static
npm http 304 http://192.168.1.100:4873/utils-merge
npm http 304 http://192.168.1.100:4873/vary
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
npm http 304 http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/varint
npm http 304 http://192.168.1.100:4873/duplexify
npm http 304 http://192.168.1.100:4873/xtend
npm http 200 http://192.168.1.100:4873/readable-stream
npm http fetch GET http://192.168.1.100:4873/readable-stream/-/readable-stream-2.2.6.tgz
npm http fetch 200 http://192.168.1.100:4873/readable-stream/-/readable-stream-2.2.6.tgz
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
npm http request GET http://192.168.1.100:4873/string_decoder
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http 304 http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/buffer-shims
npm http 304 http://192.168.1.100:4873/string_decoder
npm http 304 http://192.168.1.100:4873/util-deprecate
npm http 200 http://192.168.1.100:4873/core-util-is
npm http 304 http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/argsarray
npm http request GET http://192.168.1.100:4873/buffer-from
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/pouchdb-md5
npm http request GET http://192.168.1.100:4873/pouchdb-merge
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-utils
npm http request GET http://192.168.1.100:4873/pouchdb-binary-utils
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/pouchdb-errors
npm http request GET http://192.168.1.100:4873/pouchdb-json
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/pouchdb-utils
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/through2
npm http 304 http://192.168.1.100:4873/buffer-from
npm http 200 http://192.168.1.100:4873/argsarray
npm http 304 http://192.168.1.100:4873/pouchdb-md5
npm http 304 http://192.168.1.100:4873/double-ended-queue
npm http 304 http://192.168.1.100:4873/pouchdb-merge
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-utils
npm http 304 http://192.168.1.100:4873/pouchdb-binary-utils
npm http 304 http://192.168.1.100:4873/pouchdb-errors
npm http 304 http://192.168.1.100:4873/pouchdb-collections
npm http 304 http://192.168.1.100:4873/pouchdb-json
npm http 304 http://192.168.1.100:4873/pouchdb-utils
npm http 304 http://192.168.1.100:4873/sublevel-pouchdb
npm http 200 http://192.168.1.100:4873/pouchdb-promise
npm http 200 http://192.168.1.100:4873/through2
npm http 200 http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/is-array-buffer-x
npm http 200 http://192.168.1.100:4873/is-array-buffer-x
npm http fetch GET http://192.168.1.100:4873/is-array-buffer-x/-/is-array-buffer-x-1.2.1.tgz
npm http fetch 200 http://192.168.1.100:4873/is-array-buffer-x/-/is-array-buffer-x-1.2.1.tgz
npm http request GET http://192.168.1.100:4873/is-object-like-x
npm http request GET http://192.168.1.100:4873/to-string-tag-x
npm http request GET http://192.168.1.100:4873/has-to-string-tag-x
npm http 200 http://192.168.1.100:4873/is-object-like-x
npm http 200 http://192.168.1.100:4873/to-string-tag-x
npm http 200 http://192.168.1.100:4873/has-to-string-tag-x
npm http fetch GET http://192.168.1.100:4873/has-to-string-tag-x/-/has-to-string-tag-x-1.2.0.tgz
npm http fetch GET http://192.168.1.100:4873/is-object-like-x/-/is-object-like-x-1.2.0.tgz
npm http fetch GET http://192.168.1.100:4873/to-string-tag-x/-/to-string-tag-x-1.2.0.tgz
npm http fetch 200 http://192.168.1.100:4873/has-to-string-tag-x/-/has-to-string-tag-x-1.2.0.tgz
npm http fetch 200 http://192.168.1.100:4873/is-object-like-x/-/is-object-like-x-1.2.0.tgz
npm http fetch 200 http://192.168.1.100:4873/to-string-tag-x/-/to-string-tag-x-1.2.0.tgz
npm http request GET http://192.168.1.100:4873/has-symbol-support-x
npm http 200 http://192.168.1.100:4873/has-symbol-support-x
npm http fetch GET http://192.168.1.100:4873/has-symbol-support-x/-/has-symbol-support-x-1.2.0.tgz
npm http fetch 200 http://192.168.1.100:4873/has-symbol-support-x/-/has-symbol-support-x-1.2.0.tgz
npm http request GET http://192.168.1.100:4873/is-function-x
npm http request GET http://192.168.1.100:4873/is-primitive
npm http 304 http://192.168.1.100:4873/is-primitive
npm http 200 http://192.168.1.100:4873/is-function-x
npm http fetch GET http://192.168.1.100:4873/is-function-x/-/is-function-x-1.2.0.tgz
npm http fetch 200 http://192.168.1.100:4873/is-function-x/-/is-function-x-1.2.0.tgz
npm http request GET http://192.168.1.100:4873/lodash.isnull
npm http request GET http://192.168.1.100:4873/validate.io-undefined
npm http 304 http://192.168.1.100:4873/validate.io-undefined
npm http 304 http://192.168.1.100:4873/lodash.isnull
npm http request GET http://192.168.1.100:4873/deferred-leveldown
npm http request GET http://192.168.1.100:4873/level-errors
npm http request GET http://192.168.1.100:4873/level-codec
npm http request GET http://192.168.1.100:4873/level-iterator-stream
npm http request GET http://192.168.1.100:4873/prr
npm http request GET http://192.168.1.100:4873/semver
npm http 304 http://192.168.1.100:4873/deferred-leveldown
npm http 304 http://192.168.1.100:4873/level-errors
npm http 304 http://192.168.1.100:4873/level-codec
npm http 304 http://192.168.1.100:4873/level-iterator-stream
npm http 304 http://192.168.1.100:4873/prr
npm http 200 http://192.168.1.100:4873/semver
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http 304 http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/errno
npm http 304 http://192.168.1.100:4873/errno
npm http request GET http://192.168.1.100:4873/spark-md5
npm http 304 http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/clone-buffer
npm http 304 http://192.168.1.100:4873/clone-buffer
npm http request GET http://192.168.1.100:4873/vuvuzela
npm http 304 http://192.168.1.100:4873/vuvuzela
npm http request GET http://192.168.1.100:4873/ltgt
npm http 200 http://192.168.1.100:4873/ltgt
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/caseless
npm http 200 http://192.168.1.100:4873/bl
npm http 200 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/form-data
npm WARN deprecated node-uuid@1.4.8: Use uuid module instead
npm http fetch GET http://192.168.1.100:4873/node-uuid/-/node-uuid-1.4.8.tgz
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 200 http://192.168.1.100:4873/tunnel-agent
npm http 200 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/combined-stream
npm http fetch 200 http://192.168.1.100:4873/node-uuid/-/node-uuid-1.4.8.tgz
npm http 200 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 200 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http fetch GET http://192.168.1.100:4873/async/-/async-2.3.0.tgz
npm http fetch 200 http://192.168.1.100:4873/async/-/async-2.3.0.tgz
npm http request GET http://192.168.1.100:4873/lodash
npm http 200 http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/is-my-json-valid
npm http 200 http://192.168.1.100:4873/chalk
npm http 200 http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 200 http://192.168.1.100:4873/ansi-styles
npm http 200 http://192.168.1.100:4873/strip-ansi
npm http 200 http://192.168.1.100:4873/has-ansi
npm http 200 http://192.168.1.100:4873/supports-color
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 200 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http 304 http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-function
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http request GET http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/boom
npm http 200 http://192.168.1.100:4873/cryptiles
npm http 200 http://192.168.1.100:4873/sntp
npm http 200 http://192.168.1.100:4873/boom
npm http 200 http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/asn1
npm http 200 http://192.168.1.100:4873/assert-plus
npm http 304 http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/punycode
npm http 200 http://192.168.1.100:4873/punycode
npm http request GET http://192.168.1.100:4873/jsonschema
npm http 200 http://192.168.1.100:4873/jsonschema
npm http request GET http://192.168.1.100:4873/colors
npm http request GET http://192.168.1.100:4873/cycle
npm http request GET http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/pkginfo
npm http request GET http://192.168.1.100:4873/stack-trace
npm http 304 http://192.168.1.100:4873/colors
npm http 304 http://192.168.1.100:4873/cycle
npm http 304 http://192.168.1.100:4873/eyes
npm http 304 http://192.168.1.100:4873/stack-trace
npm http 304 http://192.168.1.100:4873/pkginfo
npm http request GET http://192.168.1.100:4873/jsdoc
npm http request GET http://192.168.1.100:4873/eslint
npm http 200 http://192.168.1.100:4873/jsdoc
npm http 200 http://192.168.1.100:4873/eslint
npm http request GET http://192.168.1.100:4873/babel-code-frame
npm http request GET http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/doctrine
npm http request GET http://192.168.1.100:4873/escope
npm http request GET http://192.168.1.100:4873/espree
npm http request GET http://192.168.1.100:4873/estraverse
npm http request GET http://192.168.1.100:4873/esutils
npm http request GET http://192.168.1.100:4873/file-entry-cache
npm http request GET http://192.168.1.100:4873/globals
npm http request GET http://192.168.1.100:4873/ignore
npm http request GET http://192.168.1.100:4873/imurmurhash
npm http request GET http://192.168.1.100:4873/inquirer
npm http request GET http://192.168.1.100:4873/is-resolvable
npm http request GET http://192.168.1.100:4873/js-yaml
npm http request GET http://192.168.1.100:4873/json-stable-stringify
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/natural-compare
npm http request GET http://192.168.1.100:4873/optionator
npm http request GET http://192.168.1.100:4873/levn
npm http request GET http://192.168.1.100:4873/path-is-inside
npm http request GET http://192.168.1.100:4873/progress
npm http request GET http://192.168.1.100:4873/pluralize
npm http request GET http://192.168.1.100:4873/require-uncached
npm http request GET http://192.168.1.100:4873/shelljs
npm http request GET http://192.168.1.100:4873/strip-bom
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/text-table
npm http request GET http://192.168.1.100:4873/table
npm http request GET http://192.168.1.100:4873/user-home
npm http 200 http://192.168.1.100:4873/concat-stream
npm http 200 http://192.168.1.100:4873/babel-code-frame
npm http 304 http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/doctrine
npm http 200 http://192.168.1.100:4873/escope
npm http 304 http://192.168.1.100:4873/estraverse
npm http 304 http://192.168.1.100:4873/esutils
npm http 304 http://192.168.1.100:4873/file-entry-cache
npm http 200 http://192.168.1.100:4873/globals
npm http 200 http://192.168.1.100:4873/espree
npm http 304 http://192.168.1.100:4873/imurmurhash
npm http 304 http://192.168.1.100:4873/is-resolvable
npm http 200 http://192.168.1.100:4873/ignore
npm http fetch GET http://192.168.1.100:4873/globals/-/globals-9.17.0.tgz
npm http fetch GET http://192.168.1.100:4873/espree/-/espree-3.4.1.tgz
npm http 200 http://192.168.1.100:4873/js-yaml
npm http 200 http://192.168.1.100:4873/inquirer
npm http 304 http://192.168.1.100:4873/json-stable-stringify
npm http 304 http://192.168.1.100:4873/natural-compare
npm http 304 http://192.168.1.100:4873/levn
npm http 200 http://192.168.1.100:4873/mkdirp
npm http 200 http://192.168.1.100:4873/optionator
npm http fetch GET http://192.168.1.100:4873/ignore/-/ignore-3.2.6.tgz
npm http 304 http://192.168.1.100:4873/path-is-inside
npm http fetch GET http://192.168.1.100:4873/js-yaml/-/js-yaml-3.8.2.tgz
npm http 200 http://192.168.1.100:4873/progress
npm http 200 http://192.168.1.100:4873/require-uncached
npm http 200 http://192.168.1.100:4873/pluralize
npm http 200 http://192.168.1.100:4873/shelljs
npm http 304 http://192.168.1.100:4873/strip-bom
npm http 304 http://192.168.1.100:4873/user-home
npm http fetch 200 http://192.168.1.100:4873/globals/-/globals-9.17.0.tgz
npm http fetch 200 http://192.168.1.100:4873/ignore/-/ignore-3.2.6.tgz
npm http fetch 200 http://192.168.1.100:4873/espree/-/espree-3.4.1.tgz
npm http 200 http://192.168.1.100:4873/strip-json-comments
npm http 200 http://192.168.1.100:4873/text-table
npm http fetch 200 http://192.168.1.100:4873/js-yaml/-/js-yaml-3.8.2.tgz
npm http 200 http://192.168.1.100:4873/table
npm http fetch GET http://192.168.1.100:4873/shelljs/-/shelljs-0.7.7.tgz
npm http fetch 200 http://192.168.1.100:4873/shelljs/-/shelljs-0.7.7.tgz
npm http request GET http://192.168.1.100:4873/js-tokens
npm http 304 http://192.168.1.100:4873/js-tokens
npm http request GET http://192.168.1.100:4873/typedarray
npm http 304 http://192.168.1.100:4873/typedarray
npm http request GET http://192.168.1.100:4873/es6-map
npm http request GET http://192.168.1.100:4873/es6-weak-map
npm http request GET http://192.168.1.100:4873/esrecurse
npm http 304 http://192.168.1.100:4873/esrecurse
npm http 200 http://192.168.1.100:4873/es6-map
npm http 200 http://192.168.1.100:4873/es6-weak-map
npm http fetch GET http://192.168.1.100:4873/es6-map/-/es6-map-0.1.5.tgz
npm http fetch 200 http://192.168.1.100:4873/es6-map/-/es6-map-0.1.5.tgz
npm http fetch GET http://192.168.1.100:4873/es6-weak-map/-/es6-weak-map-2.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/es6-weak-map/-/es6-weak-map-2.0.2.tgz
npm http request GET http://192.168.1.100:4873/d
npm http request GET http://192.168.1.100:4873/es6-iterator
npm http request GET http://192.168.1.100:4873/es5-ext
npm http request GET http://192.168.1.100:4873/es6-set
npm http request GET http://192.168.1.100:4873/es6-symbol
npm http request GET http://192.168.1.100:4873/event-emitter
npm http 200 http://192.168.1.100:4873/d
npm http 200 http://192.168.1.100:4873/es6-iterator
npm http 200 http://192.168.1.100:4873/es6-set
npm http fetch GET http://192.168.1.100:4873/d/-/d-1.0.0.tgz
npm http 200 http://192.168.1.100:4873/es6-symbol
npm http 200 http://192.168.1.100:4873/es5-ext
npm http fetch GET http://192.168.1.100:4873/es6-iterator/-/es6-iterator-2.0.1.tgz
npm http fetch 200 http://192.168.1.100:4873/d/-/d-1.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/es6-iterator/-/es6-iterator-2.0.1.tgz
npm http fetch GET http://192.168.1.100:4873/es6-set/-/es6-set-0.1.5.tgz
npm http fetch GET http://192.168.1.100:4873/es6-symbol/-/es6-symbol-3.1.1.tgz
npm http 200 http://192.168.1.100:4873/event-emitter
npm http fetch GET http://192.168.1.100:4873/es5-ext/-/es5-ext-0.10.15.tgz
npm http fetch 200 http://192.168.1.100:4873/es6-set/-/es6-set-0.1.5.tgz
npm http fetch 200 http://192.168.1.100:4873/es6-symbol/-/es6-symbol-3.1.1.tgz
npm http fetch 200 http://192.168.1.100:4873/es5-ext/-/es5-ext-0.10.15.tgz
npm http fetch GET http://192.168.1.100:4873/event-emitter/-/event-emitter-0.3.5.tgz
npm http fetch 200 http://192.168.1.100:4873/event-emitter/-/event-emitter-0.3.5.tgz
npm http request GET http://192.168.1.100:4873/acorn-jsx
npm http request GET http://192.168.1.100:4873/acorn
npm http 304 http://192.168.1.100:4873/acorn-jsx
npm http 200 http://192.168.1.100:4873/acorn
npm http fetch GET http://192.168.1.100:4873/acorn/-/acorn-5.0.3.tgz
npm http fetch 200 http://192.168.1.100:4873/acorn/-/acorn-5.0.3.tgz
npm http request GET http://192.168.1.100:4873/flat-cache
npm http 304 http://192.168.1.100:4873/flat-cache
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/circular-json
npm http request GET http://192.168.1.100:4873/del
npm http request GET http://192.168.1.100:4873/write
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http 200 http://192.168.1.100:4873/circular-json
npm http 200 http://192.168.1.100:4873/del
npm http 200 http://192.168.1.100:4873/write
npm http request GET http://192.168.1.100:4873/rimraf
npm http request GET http://192.168.1.100:4873/is-path-cwd
npm http request GET http://192.168.1.100:4873/is-path-in-cwd
npm http request GET http://192.168.1.100:4873/pinkie-promise
npm http request GET http://192.168.1.100:4873/globby
npm http request GET http://192.168.1.100:4873/pify
npm http 304 http://192.168.1.100:4873/rimraf
npm http 304 http://192.168.1.100:4873/is-path-cwd
npm http 304 http://192.168.1.100:4873/is-path-in-cwd
npm http 304 http://192.168.1.100:4873/pinkie-promise
npm http 200 http://192.168.1.100:4873/globby
npm http 200 http://192.168.1.100:4873/pify
npm http request GET http://192.168.1.100:4873/array-union
npm http request GET http://192.168.1.100:4873/arrify
npm http 200 http://192.168.1.100:4873/array-union
npm http 200 http://192.168.1.100:4873/arrify
npm http request GET http://192.168.1.100:4873/array-uniq
npm http 200 http://192.168.1.100:4873/array-uniq
npm http request GET http://192.168.1.100:4873/fs.realpath
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/fs.realpath
npm http 304 http://192.168.1.100:4873/inflight
npm http 304 http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 304 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/pinkie
npm http 304 http://192.168.1.100:4873/pinkie
npm http request GET http://192.168.1.100:4873/is-path-inside
npm http 304 http://192.168.1.100:4873/is-path-inside
npm http request GET http://192.168.1.100:4873/minimist
npm http 200 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/ansi-escapes
npm http request GET http://192.168.1.100:4873/cli-width
npm http request GET http://192.168.1.100:4873/cli-cursor
npm http request GET http://192.168.1.100:4873/readline2
npm http request GET http://192.168.1.100:4873/figures
npm http request GET http://192.168.1.100:4873/run-async
npm http request GET http://192.168.1.100:4873/rx-lite
npm http request GET http://192.168.1.100:4873/string-width
npm http request GET http://192.168.1.100:4873/through
npm http 304 http://192.168.1.100:4873/ansi-escapes
npm http 304 http://192.168.1.100:4873/cli-width
npm http 304 http://192.168.1.100:4873/cli-cursor
npm http 304 http://192.168.1.100:4873/readline2
npm http 304 http://192.168.1.100:4873/figures
npm http 304 http://192.168.1.100:4873/run-async
npm http 200 http://192.168.1.100:4873/string-width
npm http 200 http://192.168.1.100:4873/through
npm http 200 http://192.168.1.100:4873/rx-lite
npm http request GET http://192.168.1.100:4873/restore-cursor
npm http 304 http://192.168.1.100:4873/restore-cursor
npm http request GET http://192.168.1.100:4873/exit-hook
npm http request GET http://192.168.1.100:4873/onetime
npm http 304 http://192.168.1.100:4873/exit-hook
npm http 200 http://192.168.1.100:4873/onetime
npm http request GET http://192.168.1.100:4873/code-point-at
npm http request GET http://192.168.1.100:4873/is-fullwidth-code-point
npm http request GET http://192.168.1.100:4873/mute-stream
npm http 304 http://192.168.1.100:4873/is-fullwidth-code-point
npm http 304 http://192.168.1.100:4873/code-point-at
npm http 304 http://192.168.1.100:4873/mute-stream
npm http request GET http://192.168.1.100:4873/number-is-nan
npm http 200 http://192.168.1.100:4873/number-is-nan
npm http request GET http://192.168.1.100:4873/tryit
npm http 304 http://192.168.1.100:4873/tryit
npm http request GET http://192.168.1.100:4873/argparse
npm http request GET http://192.168.1.100:4873/esprima
npm http 304 http://192.168.1.100:4873/argparse
npm http 200 http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/sprintf-js
npm http 200 http://192.168.1.100:4873/sprintf-js
npm http request GET http://192.168.1.100:4873/jsonify
npm http 304 http://192.168.1.100:4873/jsonify
npm http request GET http://192.168.1.100:4873/prelude-ls
npm http request GET http://192.168.1.100:4873/type-check
npm http 304 http://192.168.1.100:4873/prelude-ls
npm http 304 http://192.168.1.100:4873/type-check
npm http request GET http://192.168.1.100:4873/deep-is
npm http request GET http://192.168.1.100:4873/wordwrap
npm http request GET http://192.168.1.100:4873/fast-levenshtein
npm http 304 http://192.168.1.100:4873/deep-is
npm http 304 http://192.168.1.100:4873/fast-levenshtein
npm http 200 http://192.168.1.100:4873/wordwrap
npm http request GET http://192.168.1.100:4873/caller-path
npm http request GET http://192.168.1.100:4873/resolve-from
npm http 304 http://192.168.1.100:4873/caller-path
npm http 304 http://192.168.1.100:4873/resolve-from
npm http request GET http://192.168.1.100:4873/callsites
npm http 304 http://192.168.1.100:4873/callsites
npm http request GET http://192.168.1.100:4873/interpret
npm http request GET http://192.168.1.100:4873/rechoir
npm http 304 http://192.168.1.100:4873/rechoir
npm http 200 http://192.168.1.100:4873/interpret
npm http fetch GET http://192.168.1.100:4873/interpret/-/interpret-1.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/interpret/-/interpret-1.0.2.tgz
npm http request GET http://192.168.1.100:4873/resolve
npm http 304 http://192.168.1.100:4873/resolve
npm http request GET http://192.168.1.100:4873/path-parse
npm http 304 http://192.168.1.100:4873/path-parse
npm http request GET http://192.168.1.100:4873/slice-ansi
npm http request GET http://192.168.1.100:4873/ajv-keywords
npm http request GET http://192.168.1.100:4873/ajv
npm http 304 http://192.168.1.100:4873/slice-ansi
npm http 200 http://192.168.1.100:4873/ajv-keywords
npm http 200 http://192.168.1.100:4873/ajv
npm http fetch GET http://192.168.1.100:4873/ajv/-/ajv-4.11.5.tgz
npm http fetch 200 http://192.168.1.100:4873/ajv/-/ajv-4.11.5.tgz
npm http request GET http://192.168.1.100:4873/co
npm http 200 http://192.168.1.100:4873/co
npm http request GET http://192.168.1.100:4873/os-homedir
npm http 304 http://192.168.1.100:4873/os-homedir
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/js2xmlparser
npm http request GET http://192.168.1.100:4873/catharsis
npm http request GET http://192.168.1.100:4873/marked
npm http request GET http://192.168.1.100:4873/underscore
npm http request GET http://192.168.1.100:4873/requizzle
npm http request GET http://192.168.1.100:4873/wrench
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 304 http://192.168.1.100:4873/catharsis
npm http 304 http://192.168.1.100:4873/async
npm http 200 http://192.168.1.100:4873/marked
npm http 200 http://192.168.1.100:4873/js2xmlparser
npm http 200 http://192.168.1.100:4873/underscore
npm http 304 http://192.168.1.100:4873/wrench
npm http 200 http://192.168.1.100:4873/requizzle
npm WARN deprecated wrench@1.5.9: wrench.js is deprecated! You should check out fs-extra (https://github.com/jprichardson/node-fs-extra) for any operations you were using wrench for. Thanks for all the usage over the years.
npm http fetch 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http request GET http://192.168.1.100:4873/underscore-contrib
npm http 200 http://192.168.1.100:4873/underscore-contrib
npm WARN prefer global marked@0.3.6 should be installed with -g
npm WARN install@0.0.1 No repository field.
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/child-process-promise
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/bn.js
npm http request GET http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/express-pouchdb
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/leveldown-mobile
npm http request GET http://192.168.1.100:4873/nock
npm http request GET http://192.168.1.100:4873/pouchdb
npm http request GET http://192.168.1.100:4873/pouchdb-size
npm http request GET http://192.168.1.100:4873/proxyquire
npm http request GET http://192.168.1.100:4873/request-promise
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/stacky
npm http request GET http://192.168.1.100:4873/supertest
npm http request GET http://192.168.1.100:4873/supertest-as-promised
npm http request GET http://192.168.1.100:4873/sinon
npm http request GET http://192.168.1.100:4873/tape-catch
npm http request GET http://192.168.1.100:4873/tape
npm http request GET http://192.168.1.100:4873/tmp
npm http request GET http://192.168.1.100:4873/uuid-validate
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/child-process-promise
npm http 304 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/minimist
npm http 304 http://192.168.1.100:4873/multiplex
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/randomstring
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/socket.io-client
npm http 304 http://192.168.1.100:4873/js-extend
npm http 304 http://192.168.1.100:4873/leveldown-mobile
npm http 200 http://192.168.1.100:4873/bn.js
npm http 200 http://192.168.1.100:4873/express-pouchdb
npm http 304 http://192.168.1.100:4873/pouchdb-size
npm http 304 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/proxyquire
npm http 304 http://192.168.1.100:4873/uuid
npm http 304 http://192.168.1.100:4873/stacky
npm http 304 http://192.168.1.100:4873/supertest-as-promised
npm http 200 http://192.168.1.100:4873/request-promise
npm http 200 http://192.168.1.100:4873/supertest
npm http 304 http://192.168.1.100:4873/tape-catch
npm http 304 http://192.168.1.100:4873/uuid-validate
npm http 200 http://192.168.1.100:4873/pouchdb
npm http 200 http://192.168.1.100:4873/tmp
npm http 200 http://192.168.1.100:4873/tape
npm http 200 http://192.168.1.100:4873/sinon
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
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/iconv-lite
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
npm http request GET http://192.168.1.100:4873/proxy-addr
npm http request GET http://192.168.1.100:4873/range-parser
npm http request GET http://192.168.1.100:4873/send
npm http request GET http://192.168.1.100:4873/path-to-regexp
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
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/send
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/serve-static
npm http 304 http://192.168.1.100:4873/utils-merge
npm http 304 http://192.168.1.100:4873/vary
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
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/compression
npm http request GET http://192.168.1.100:4873/cookie-parser
npm http request GET http://192.168.1.100:4873/header-case-normalizer
npm http request GET http://192.168.1.100:4873/multiparty
npm http request GET http://192.168.1.100:4873/pouchdb-all-dbs
npm http request GET http://192.168.1.100:4873/pouchdb-auth
npm http request GET http://192.168.1.100:4873/pouchdb-find
npm http request GET http://192.168.1.100:4873/pouchdb-list
npm http request GET http://192.168.1.100:4873/pouchdb-replicator
npm http request GET http://192.168.1.100:4873/pouchdb-security
npm http request GET http://192.168.1.100:4873/pouchdb-rewrite
npm http request GET http://192.168.1.100:4873/pouchdb-show
npm http request GET http://192.168.1.100:4873/pouchdb-update
npm http request GET http://192.168.1.100:4873/pouchdb-validation
npm http request GET http://192.168.1.100:4873/pouchdb-vhost
npm http request GET http://192.168.1.100:4873/pouchdb-wrappers
npm http 304 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/cookie-parser
npm http 304 http://192.168.1.100:4873/header-case-normalizer
npm http 200 http://192.168.1.100:4873/basic-auth
npm http 200 http://192.168.1.100:4873/compression
npm http 304 http://192.168.1.100:4873/pouchdb-all-dbs
npm http 200 http://192.168.1.100:4873/multiparty
npm http 304 http://192.168.1.100:4873/pouchdb-find
npm http 304 http://192.168.1.100:4873/pouchdb-auth
npm http 304 http://192.168.1.100:4873/pouchdb-list
npm http 304 http://192.168.1.100:4873/pouchdb-rewrite
npm http 304 http://192.168.1.100:4873/pouchdb-show
npm http 200 http://192.168.1.100:4873/pouchdb-replicator
npm http 304 http://192.168.1.100:4873/pouchdb-update
npm http 200 http://192.168.1.100:4873/pouchdb-security
npm http 304 http://192.168.1.100:4873/pouchdb-validation
npm http 304 http://192.168.1.100:4873/pouchdb-vhost
npm http 304 http://192.168.1.100:4873/pouchdb-wrappers
npm http request GET http://192.168.1.100:4873/setprototypeof
npm http 200 http://192.168.1.100:4873/setprototypeof
npm http request GET http://192.168.1.100:4873/compressible
npm http request GET http://192.168.1.100:4873/on-headers
npm http fetch GET http://192.168.1.100:4873/vary/-/vary-1.1.1.tgz
npm http fetch 200 http://192.168.1.100:4873/vary/-/vary-1.1.1.tgz
npm http 200 http://192.168.1.100:4873/on-headers
npm http 200 http://192.168.1.100:4873/compressible
npm http fetch GET http://192.168.1.100:4873/compressible/-/compressible-2.0.10.tgz
npm http fetch 200 http://192.168.1.100:4873/compressible/-/compressible-2.0.10.tgz
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/stream-counter
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/stream-counter
npm http request GET http://192.168.1.100:4873/argsarray
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/tiny-queue
npm http 304 http://192.168.1.100:4873/argsarray
npm http 304 http://192.168.1.100:4873/es3ify
npm http 304 http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/tiny-queue
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/base64url
npm http request GET http://192.168.1.100:4873/couchdb-calculate-session-id
npm http request GET http://192.168.1.100:4873/crypto-lite
npm http request GET http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http request GET http://192.168.1.100:4873/pouchdb-plugin-error
npm http request GET http://192.168.1.100:4873/pouchdb-req-http-query
npm http request GET http://192.168.1.100:4873/pouchdb-system-db
npm http request GET http://192.168.1.100:4873/promise-nodify
npm http request GET http://192.168.1.100:4873/secure-random
npm http 200 http://192.168.1.100:4873/base64url
npm http 304 http://192.168.1.100:4873/crypto-lite
npm http 304 http://192.168.1.100:4873/pouchdb-plugin-error
npm http 304 http://192.168.1.100:4873/couchdb-calculate-session-id
npm http 304 http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http 304 http://192.168.1.100:4873/pouchdb-req-http-query
npm http 304 http://192.168.1.100:4873/promise-nodify
npm http 304 http://192.168.1.100:4873/pouchdb-system-db
npm http 304 http://192.168.1.100:4873/secure-random
npm http request GET http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/meow
npm http 304 http://192.168.1.100:4873/concat-stream
npm http 200 http://192.168.1.100:4873/meow
npm http request GET http://192.168.1.100:4873/typedarray
npm http 304 http://192.168.1.100:4873/typedarray
npm http request GET http://192.168.1.100:4873/camelcase-keys
npm http request GET http://192.168.1.100:4873/indent-string
npm http 304 http://192.168.1.100:4873/indent-string
npm http 200 http://192.168.1.100:4873/camelcase-keys
npm http request GET http://192.168.1.100:4873/camelcase
npm http request GET http://192.168.1.100:4873/map-obj
npm http 304 http://192.168.1.100:4873/map-obj
npm http 200 http://192.168.1.100:4873/camelcase
npm http request GET http://192.168.1.100:4873/get-stdin
npm http request GET http://192.168.1.100:4873/repeating
npm http 304 http://192.168.1.100:4873/get-stdin
npm http 200 http://192.168.1.100:4873/repeating
npm http request GET http://192.168.1.100:4873/is-finite
npm http 304 http://192.168.1.100:4873/is-finite
npm http request GET http://192.168.1.100:4873/number-is-nan
npm http 304 http://192.168.1.100:4873/number-is-nan
npm http request GET http://192.168.1.100:4873/aproba
npm http 304 http://192.168.1.100:4873/aproba
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/vuvuzela
npm http request GET http://192.168.1.100:4873/level-write-stream
npm http request GET http://192.168.1.100:4873/es6-promise-pool
npm http request GET http://192.168.1.100:4873/fruitdown
npm http request GET http://192.168.1.100:4873/localstorage-down
npm http request GET http://192.168.1.100:4873/memdown
npm http request GET http://192.168.1.100:4873/pouchdb-collate
npm http request GET http://192.168.1.100:4873/scope-eval
npm http 304 http://192.168.1.100:4873/double-ended-queue
npm http 304 http://192.168.1.100:4873/levelup
npm http 304 http://192.168.1.100:4873/spark-md5
npm http 304 http://192.168.1.100:4873/pouchdb-collections
npm http 304 http://192.168.1.100:4873/through2
npm http 304 http://192.168.1.100:4873/vuvuzela
npm http 304 http://192.168.1.100:4873/level-write-stream
npm http 304 http://192.168.1.100:4873/memdown
npm http 304 http://192.168.1.100:4873/pouchdb-collate
npm http 304 http://192.168.1.100:4873/scope-eval
npm http 304 http://192.168.1.100:4873/sublevel-pouchdb
npm http 200 http://192.168.1.100:4873/es6-promise-pool
npm http 304 http://192.168.1.100:4873/fruitdown
npm http 304 http://192.168.1.100:4873/localstorage-down
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/d64
npm http 304 http://192.168.1.100:4873/abstract-leveldown
npm http 304 http://192.168.1.100:4873/d64
npm http request GET http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/end-stream
npm http 304 http://192.168.1.100:4873/end-stream
npm http request GET http://192.168.1.100:4873/write-stream
npm http 304 http://192.168.1.100:4873/write-stream
npm http request GET http://192.168.1.100:4873/deferred-leveldown
npm http request GET http://192.168.1.100:4873/level-codec
npm http request GET http://192.168.1.100:4873/level-errors
npm http request GET http://192.168.1.100:4873/level-iterator-stream
npm http request GET http://192.168.1.100:4873/prr
npm http request GET http://192.168.1.100:4873/semver
npm http 304 http://192.168.1.100:4873/deferred-leveldown
npm http 304 http://192.168.1.100:4873/level-codec
npm http 304 http://192.168.1.100:4873/prr
npm http 304 http://192.168.1.100:4873/level-errors
npm http 304 http://192.168.1.100:4873/level-iterator-stream
npm http 304 http://192.168.1.100:4873/semver
npm http request GET http://192.168.1.100:4873/errno
npm http 304 http://192.168.1.100:4873/errno
npm http request GET http://192.168.1.100:4873/humble-localstorage
npm http 304 http://192.168.1.100:4873/humble-localstorage
npm http request GET http://192.168.1.100:4873/localstorage-memory
npm http request GET http://192.168.1.100:4873/has-localstorage
npm http 304 http://192.168.1.100:4873/localstorage-memory
npm http 304 http://192.168.1.100:4873/has-localstorage
npm http request GET http://192.168.1.100:4873/ltgt
npm http request GET http://192.168.1.100:4873/functional-red-black-tree
npm http 304 http://192.168.1.100:4873/ltgt
npm http 304 http://192.168.1.100:4873/functional-red-black-tree
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
npm http fetch GET http://192.168.1.100:4873/qs/-/qs-6.1.2.tgz
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/aws4
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/is-typedarray
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/stringstream
npm http fetch 200 http://192.168.1.100:4873/qs/-/qs-6.1.2.tgz
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm WARN deprecated tough-cookie@2.2.2: ReDoS vulnerability parsing Set-Cookie https://nodesecurity.io/advisories/130
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
npm http 304 http://192.168.1.100:4873/chalk
npm http 304 http://192.168.1.100:4873/pinkie-promise
npm http 304 http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/ansi-styles
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
npm http 304 http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/boom
npm http 304 http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/jsprim
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/sshpk
npm http 304 http://192.168.1.100:4873/jsprim
npm http 304 http://192.168.1.100:4873/assert-plus
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
npm http 304 http://192.168.1.100:4873/dashdash
npm http 304 http://192.168.1.100:4873/getpass
npm http request GET http://192.168.1.100:4873/pull-stream
npm http 304 http://192.168.1.100:4873/pull-stream
npm http request GET http://192.168.1.100:4873/pull-core
npm http 304 http://192.168.1.100:4873/pull-core
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/lie
npm http 304 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/xmlhttprequest-cookie
npm http 304 http://192.168.1.100:4873/xmlhttprequest-cookie
npm http request GET http://192.168.1.100:4873/xmlhttprequest
npm http 304 http://192.168.1.100:4873/xmlhttprequest
npm http request GET http://192.168.1.100:4873/pouchdb-changeslike-wrapper
npm http 304 http://192.168.1.100:4873/pouchdb-changeslike-wrapper
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/couchdb-eval
npm http request GET http://192.168.1.100:4873/random-uuid-v4
npm http request GET http://192.168.1.100:4873/couchdb-objects
npm http 304 http://192.168.1.100:4873/couchdb-objects
npm http 304 http://192.168.1.100:4873/random-uuid-v4
npm http 304 http://192.168.1.100:4873/couchdb-eval
npm http request GET http://192.168.1.100:4873/is-empty
npm http 304 http://192.168.1.100:4873/is-empty
npm http request GET http://192.168.1.100:4873/is-array
npm http request GET http://192.168.1.100:4873/pouchdb-extend
npm http request GET http://192.168.1.100:4873/pouchdb-upsert
npm http 304 http://192.168.1.100:4873/is-array
npm http 304 http://192.168.1.100:4873/pouchdb-extend
npm http 200 http://192.168.1.100:4873/pouchdb-upsert
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 304 http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/recast
npm http request GET http://192.168.1.100:4873/ast-types
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/ast-types
npm http 304 http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/couchdb-render
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/couchdb-render
npm http request GET http://192.168.1.100:4873/couchdb-resp-completer
npm http 304 http://192.168.1.100:4873/couchdb-resp-completer
npm http request GET http://192.168.1.100:4873/equals
npm http 304 http://192.168.1.100:4873/equals
npm http request GET http://192.168.1.100:4873/jkroso-type
npm http 304 http://192.168.1.100:4873/jkroso-type
npm http request GET http://192.168.1.100:4873/pouchdb-route
npm http 304 http://192.168.1.100:4873/pouchdb-route
npm http request GET http://192.168.1.100:4873/get-folder-size
npm http 304 http://192.168.1.100:4873/get-folder-size
npm http request GET http://192.168.1.100:4873/minimist
npm http 304 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/fast-future
npm http 304 http://192.168.1.100:4873/bindings
npm http 304 http://192.168.1.100:4873/fast-future
npm http 304 http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/duplexify
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/stream-shift
npm http 304 http://192.168.1.100:4873/end-of-stream
npm http 304 http://192.168.1.100:4873/stream-shift
npm http request GET http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http 304 http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/debug
npm WARN deprecated lodash@2.4.1: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
npm http request GET http://192.168.1.100:4873/chai
npm http request GET http://192.168.1.100:4873/propagate
npm http request GET http://192.168.1.100:4873/deep-equal
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/propagate
npm http 200 http://192.168.1.100:4873/deep-equal
npm http 200 http://192.168.1.100:4873/chai
npm http request GET http://192.168.1.100:4873/assertion-error
npm http request GET http://192.168.1.100:4873/deep-eql
npm http request GET http://192.168.1.100:4873/type-detect
npm http 304 http://192.168.1.100:4873/assertion-error
npm http 304 http://192.168.1.100:4873/type-detect
npm http 200 http://192.168.1.100:4873/deep-eql
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/ip
npm http 304 http://192.168.1.100:4873/ip
npm http fetch GET http://192.168.1.100:4873/ip/-/ip-1.1.5.tgz
npm http fetch 200 http://192.168.1.100:4873/ip/-/ip-1.1.5.tgz
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
npm http 304 http://192.168.1.100:4873/double-ended-queue
npm http 304 http://192.168.1.100:4873/clone-buffer
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/level-codec
npm http 304 http://192.168.1.100:4873/levelup
npm http 304 http://192.168.1.100:4873/ltgt
npm http 304 http://192.168.1.100:4873/spark-md5
npm http 304 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/leveldown
npm http request GET http://192.168.1.100:4873/is-array-buffer-x
npm http 304 http://192.168.1.100:4873/is-array-buffer-x
npm http request GET http://192.168.1.100:4873/is-object-like-x
npm http request GET http://192.168.1.100:4873/to-string-tag-x
npm http request GET http://192.168.1.100:4873/has-to-string-tag-x
npm http 304 http://192.168.1.100:4873/to-string-tag-x
npm http 304 http://192.168.1.100:4873/is-object-like-x
npm http 304 http://192.168.1.100:4873/has-to-string-tag-x
npm http request GET http://192.168.1.100:4873/has-symbol-support-x
npm http 304 http://192.168.1.100:4873/has-symbol-support-x
npm http request GET http://192.168.1.100:4873/is-function-x
npm http request GET http://192.168.1.100:4873/is-primitive
npm http 304 http://192.168.1.100:4873/is-primitive
npm http 304 http://192.168.1.100:4873/is-function-x
npm http request GET http://192.168.1.100:4873/lodash.isnull
npm http request GET http://192.168.1.100:4873/validate.io-undefined
npm http 304 http://192.168.1.100:4873/lodash.isnull
npm http 304 http://192.168.1.100:4873/validate.io-undefined
npm http request GET http://192.168.1.100:4873/nan
npm http request GET http://192.168.1.100:4873/prebuild
npm http 200 http://192.168.1.100:4873/nan
npm http 200 http://192.168.1.100:4873/prebuild
npm http request GET http://192.168.1.100:4873/execspawn
npm http request GET http://192.168.1.100:4873/os-homedir
npm http request GET http://192.168.1.100:4873/expand-template
npm http request GET http://192.168.1.100:4873/ghreleases
npm http request GET http://192.168.1.100:4873/github-from-package
npm http request GET http://192.168.1.100:4873/node-ninja
npm http request GET http://192.168.1.100:4873/noop-logger
npm http request GET http://192.168.1.100:4873/npmlog
npm http request GET http://192.168.1.100:4873/node-gyp
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/rc
npm http request GET http://192.168.1.100:4873/pump
npm http request GET http://192.168.1.100:4873/simple-get
npm http request GET http://192.168.1.100:4873/tar-fs
npm http request GET http://192.168.1.100:4873/tar-stream
npm http 304 http://192.168.1.100:4873/execspawn
npm http 304 http://192.168.1.100:4873/os-homedir
npm http 304 http://192.168.1.100:4873/expand-template
npm http 304 http://192.168.1.100:4873/github-from-package
npm http 304 http://192.168.1.100:4873/ghreleases
npm http 304 http://192.168.1.100:4873/node-ninja
npm http 304 http://192.168.1.100:4873/noop-logger
npm http 304 http://192.168.1.100:4873/npmlog
npm http 304 http://192.168.1.100:4873/async
npm http 200 http://192.168.1.100:4873/rc
npm http 304 http://192.168.1.100:4873/tar-stream
npm http 200 http://192.168.1.100:4873/node-gyp
npm http 200 http://192.168.1.100:4873/pump
npm http 200 http://192.168.1.100:4873/simple-get
npm http 200 http://192.168.1.100:4873/tar-fs
npm http fetch GET http://192.168.1.100:4873/rc/-/rc-1.2.1.tgz
npm http fetch 200 http://192.168.1.100:4873/rc/-/rc-1.2.1.tgz
npm http fetch GET http://192.168.1.100:4873/node-gyp/-/node-gyp-3.6.0.tgz
npm http fetch 200 http://192.168.1.100:4873/node-gyp/-/node-gyp-3.6.0.tgz
npm http fetch GET http://192.168.1.100:4873/tar-fs/-/tar-fs-1.15.2.tgz
npm http fetch 200 http://192.168.1.100:4873/tar-fs/-/tar-fs-1.15.2.tgz
npm http request GET http://192.168.1.100:4873/util-extend
npm http 304 http://192.168.1.100:4873/util-extend
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/ghrepos
npm http request GET http://192.168.1.100:4873/simple-mime
npm http request GET http://192.168.1.100:4873/ghutils
npm http request GET http://192.168.1.100:4873/url-template
npm http 304 http://192.168.1.100:4873/ghrepos
npm http 304 http://192.168.1.100:4873/after
npm http 304 http://192.168.1.100:4873/simple-mime
npm http 304 http://192.168.1.100:4873/url-template
npm http 304 http://192.168.1.100:4873/ghutils
npm http request GET http://192.168.1.100:4873/jsonist
npm http 304 http://192.168.1.100:4873/jsonist
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/hyperquest
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/hyperquest
npm http request GET http://192.168.1.100:4873/duplexer2
npm http 304 http://192.168.1.100:4873/duplexer2
npm http request GET http://192.168.1.100:4873/fstream
npm http request GET http://192.168.1.100:4873/semver
npm http request GET http://192.168.1.100:4873/nopt
npm http request GET http://192.168.1.100:4873/osenv
npm http request GET http://192.168.1.100:4873/tar
npm http request GET http://192.168.1.100:4873/which
npm http 304 http://192.168.1.100:4873/fstream
npm http 304 http://192.168.1.100:4873/semver
npm http 304 http://192.168.1.100:4873/nopt
npm http 304 http://192.168.1.100:4873/tar
npm http 200 http://192.168.1.100:4873/osenv
npm http fetch GET http://192.168.1.100:4873/fstream/-/fstream-1.0.11.tgz
npm http fetch 200 http://192.168.1.100:4873/fstream/-/fstream-1.0.11.tgz
npm http 200 http://192.168.1.100:4873/which
npm http fetch GET http://192.168.1.100:4873/which/-/which-1.2.14.tgz
npm http fetch 200 http://192.168.1.100:4873/which/-/which-1.2.14.tgz
npm http request GET http://192.168.1.100:4873/abbrev
npm http 200 http://192.168.1.100:4873/abbrev
npm http request GET http://192.168.1.100:4873/are-we-there-yet
npm http request GET http://192.168.1.100:4873/ansi
npm http request GET http://192.168.1.100:4873/gauge
npm http 304 http://192.168.1.100:4873/are-we-there-yet
npm http 304 http://192.168.1.100:4873/ansi
npm http 304 http://192.168.1.100:4873/gauge
npm http request GET http://192.168.1.100:4873/delegates
npm http 200 http://192.168.1.100:4873/delegates
npm http request GET http://192.168.1.100:4873/has-unicode
npm http request GET http://192.168.1.100:4873/lodash.pad
npm http request GET http://192.168.1.100:4873/lodash.padend
npm http request GET http://192.168.1.100:4873/lodash.padstart
npm http 304 http://192.168.1.100:4873/has-unicode
npm http 304 http://192.168.1.100:4873/lodash.pad
npm http 304 http://192.168.1.100:4873/lodash.padstart
npm http 304 http://192.168.1.100:4873/lodash.padend
npm http request GET http://192.168.1.100:4873/os-tmpdir
npm http 304 http://192.168.1.100:4873/os-tmpdir
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 304 http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/block-stream
npm http 304 http://192.168.1.100:4873/block-stream
npm http request GET http://192.168.1.100:4873/isexe
npm http 200 http://192.168.1.100:4873/isexe
npm http fetch GET http://192.168.1.100:4873/isexe/-/isexe-2.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/isexe/-/isexe-2.0.0.tgz
npm http request GET http://192.168.1.100:4873/path-array
npm http 304 http://192.168.1.100:4873/path-array
npm http request GET http://192.168.1.100:4873/array-index
npm http 304 http://192.168.1.100:4873/array-index
npm http request GET http://192.168.1.100:4873/es6-symbol
npm http 304 http://192.168.1.100:4873/es6-symbol
npm http request GET http://192.168.1.100:4873/d
npm http request GET http://192.168.1.100:4873/es5-ext
npm http 304 http://192.168.1.100:4873/d
npm http 304 http://192.168.1.100:4873/es5-ext
npm http request GET http://192.168.1.100:4873/es6-iterator
npm http 304 http://192.168.1.100:4873/es6-iterator
npm http fetch GET http://192.168.1.100:4873/end-of-stream/-/end-of-stream-1.4.0.tgz
npm http fetch 200 http://192.168.1.100:4873/end-of-stream/-/end-of-stream-1.4.0.tgz
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/ini
npm http request GET http://192.168.1.100:4873/deep-extend
npm http 304 http://192.168.1.100:4873/strip-json-comments
npm http 304 http://192.168.1.100:4873/deep-extend
npm http 200 http://192.168.1.100:4873/ini
npm http request GET http://192.168.1.100:4873/unzip-response
npm http 200 http://192.168.1.100:4873/unzip-response
npm http request GET http://192.168.1.100:4873/chownr
npm http 304 http://192.168.1.100:4873/chownr
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/uuid
npm http fetch GET http://192.168.1.100:4873/qs/-/qs-6.3.2.tgz
npm http fetch 200 http://192.168.1.100:4873/qs/-/qs-6.3.2.tgz
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/asynckit
npm http 304 http://192.168.1.100:4873/asynckit
npm http request GET http://192.168.1.100:4873/punycode
npm http 304 http://192.168.1.100:4873/punycode
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/fill-keys
npm http request GET http://192.168.1.100:4873/module-not-found-error
npm http 304 http://192.168.1.100:4873/module-not-found-error
npm http 304 http://192.168.1.100:4873/fill-keys
npm http request GET http://192.168.1.100:4873/is-object
npm http 304 http://192.168.1.100:4873/is-object
npm http request GET http://192.168.1.100:4873/array-uniq
npm http 304 http://192.168.1.100:4873/array-uniq
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/jsonschema
npm http 304 http://192.168.1.100:4873/jsonschema
npm http request GET http://192.168.1.100:4873/util
npm http request GET http://192.168.1.100:4873/formatio
npm http request GET http://192.168.1.100:4873/lolex
npm http request GET http://192.168.1.100:4873/samsam
npm http 304 http://192.168.1.100:4873/formatio
npm http 200 http://192.168.1.100:4873/util
npm http 304 http://192.168.1.100:4873/lolex
npm http 304 http://192.168.1.100:4873/samsam
npm http request GET http://192.168.1.100:4873/component-bind
npm http request GET http://192.168.1.100:4873/engine.io-client
npm http request GET http://192.168.1.100:4873/component-emitter
npm http request GET http://192.168.1.100:4873/object-component
npm http request GET http://192.168.1.100:4873/socket.io-parser
npm http request GET http://192.168.1.100:4873/has-binary
npm http request GET http://192.168.1.100:4873/indexof
npm http request GET http://192.168.1.100:4873/parseuri
npm http request GET http://192.168.1.100:4873/to-array
npm http request GET http://192.168.1.100:4873/backo2
npm http 304 http://192.168.1.100:4873/engine.io-client
npm http 304 http://192.168.1.100:4873/component-bind
npm http 304 http://192.168.1.100:4873/component-emitter
npm http 304 http://192.168.1.100:4873/object-component
npm http 304 http://192.168.1.100:4873/socket.io-parser
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
npm http 304 http://192.168.1.100:4873/base64-arraybuffer
npm http 304 http://192.168.1.100:4873/blob
npm http 304 http://192.168.1.100:4873/utf8
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
npm http request GET http://192.168.1.100:4873/formidable
npm http request GET http://192.168.1.100:4873/cookiejar
npm http request GET http://192.168.1.100:4873/reduce-component
npm http request GET http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/cookiejar
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/reduce-component
npm http 200 http://192.168.1.100:4873/formidable
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/mime-db
npm http 304 http://192.168.1.100:4873/mime-db
npm http request GET http://192.168.1.100:4873/defined
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/object-inspect
npm http request GET http://192.168.1.100:4873/resumer
npm http 304 http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/defined
npm http 304 http://192.168.1.100:4873/resumer
npm http 200 http://192.168.1.100:4873/object-inspect
npm WARN prefer global node-ninja@1.0.2 should be installed with -g
npm WARN prefer global node-gyp@3.6.0 should be installed with -g
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
clang: warning: libstdc++ is deprecated; move to libc++ with a minimum deployment target of OS X 10.9
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
clang: warning: libstdc++ is deprecated; move to libc++ with a minimum deployment target of OS X 10.9
npm WARN EPACKAGEJSON thali-cordova-plugin-jxcore@1.0.0 No repository field.
npm WARN install@0.0.1 No repository field.
npm WARN thali-test-server@0.0.1 No repository field.
npm WARN thali-test-server@0.0.1 No license field.
npm WARN SSDPReplacer@0.0.1 No repository field.
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/javascript-state-machine
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-leveldb-core
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/winston
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/ip
npm http 304 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/lie
npm http 304 http://192.168.1.100:4873/javascript-state-machine
npm http 304 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/multiplex
npm http 304 http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-leveldb-core
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/uuid
npm http 304 http://192.168.1.100:4873/urlsafe-base64
npm http 304 http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/raw-body
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/type-is
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/bytes
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/type-is
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
npm http 304 http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/media-typer
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
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/send
npm http 304 http://192.168.1.100:4873/serve-static
npm http 304 http://192.168.1.100:4873/utils-merge
npm http 304 http://192.168.1.100:4873/vary
npm http request GET http://192.168.1.100:4873/negotiator
npm http 304 http://192.168.1.100:4873/negotiator
npm http request GET http://192.168.1.100:4873/forwarded
npm http request GET http://192.168.1.100:4873/ipaddr.js
npm http 304 http://192.168.1.100:4873/forwarded
npm http 304 http://192.168.1.100:4873/ipaddr.js
npm http request GET http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/mime
npm http 304 http://192.168.1.100:4873/mime
npm http 304 http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/varint
npm http 304 http://192.168.1.100:4873/duplexify
npm http 304 http://192.168.1.100:4873/varint
npm http 304 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/stream-shift
npm http 304 http://192.168.1.100:4873/stream-shift
npm http 304 http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/buffer-shims
npm http 304 http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/argsarray
npm http request GET http://192.168.1.100:4873/buffer-from
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-utils
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/pouchdb-binary-utils
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/pouchdb-errors
npm http request GET http://192.168.1.100:4873/pouchdb-json
npm http request GET http://192.168.1.100:4873/pouchdb-md5
npm http request GET http://192.168.1.100:4873/pouchdb-merge
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/pouchdb-utils
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/through2
npm http 304 http://192.168.1.100:4873/argsarray
npm http 304 http://192.168.1.100:4873/buffer-from
npm http 304 http://192.168.1.100:4873/double-ended-queue
npm http 304 http://192.168.1.100:4873/levelup
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-utils
npm http 304 http://192.168.1.100:4873/pouchdb-binary-utils
npm http 304 http://192.168.1.100:4873/pouchdb-errors
npm http 304 http://192.168.1.100:4873/pouchdb-collections
npm http 304 http://192.168.1.100:4873/pouchdb-json
npm http 304 http://192.168.1.100:4873/pouchdb-md5
npm http 304 http://192.168.1.100:4873/pouchdb-merge
npm http 304 http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/pouchdb-utils
npm http 304 http://192.168.1.100:4873/sublevel-pouchdb
npm http 304 http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/is-array-buffer-x
npm http 304 http://192.168.1.100:4873/is-array-buffer-x
npm http request GET http://192.168.1.100:4873/to-string-tag-x
npm http request GET http://192.168.1.100:4873/is-object-like-x
npm http request GET http://192.168.1.100:4873/has-to-string-tag-x
npm http 304 http://192.168.1.100:4873/to-string-tag-x
npm http 304 http://192.168.1.100:4873/is-object-like-x
npm http 304 http://192.168.1.100:4873/has-to-string-tag-x
npm http request GET http://192.168.1.100:4873/has-symbol-support-x
npm http 304 http://192.168.1.100:4873/has-symbol-support-x
npm http request GET http://192.168.1.100:4873/is-function-x
npm http request GET http://192.168.1.100:4873/is-primitive
npm http 304 http://192.168.1.100:4873/is-primitive
npm http 304 http://192.168.1.100:4873/is-function-x
npm http request GET http://192.168.1.100:4873/lodash.isnull
npm http request GET http://192.168.1.100:4873/validate.io-undefined
npm http 304 http://192.168.1.100:4873/lodash.isnull
npm http 304 http://192.168.1.100:4873/validate.io-undefined
npm http request GET http://192.168.1.100:4873/deferred-leveldown
npm http request GET http://192.168.1.100:4873/level-errors
npm http request GET http://192.168.1.100:4873/level-iterator-stream
npm http request GET http://192.168.1.100:4873/prr
npm http request GET http://192.168.1.100:4873/level-codec
npm http request GET http://192.168.1.100:4873/semver
npm http 304 http://192.168.1.100:4873/level-errors
npm http 304 http://192.168.1.100:4873/deferred-leveldown
npm http 304 http://192.168.1.100:4873/prr
npm http 304 http://192.168.1.100:4873/level-codec
npm http 304 http://192.168.1.100:4873/level-iterator-stream
npm http 304 http://192.168.1.100:4873/semver
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http 304 http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/errno
npm http 304 http://192.168.1.100:4873/errno
npm http request GET http://192.168.1.100:4873/spark-md5
npm http 304 http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/clone-buffer
npm http 304 http://192.168.1.100:4873/clone-buffer
npm http request GET http://192.168.1.100:4873/vuvuzela
npm http 304 http://192.168.1.100:4873/vuvuzela
npm http request GET http://192.168.1.100:4873/ltgt
npm http 304 http://192.168.1.100:4873/ltgt
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/oauth-sign
npm WARN deprecated node-uuid@1.4.8: Use uuid module instead
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http 304 http://192.168.1.100:4873/chalk
npm http 304 http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/ansi-styles
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http 304 http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http request GET http://192.168.1.100:4873/generate-function
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/hoek
npm http 304 http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/cryptiles
npm http 304 http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 304 http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/punycode
npm http 304 http://192.168.1.100:4873/punycode
npm http request GET http://192.168.1.100:4873/jsonschema
npm http 304 http://192.168.1.100:4873/jsonschema
npm http request GET http://192.168.1.100:4873/colors
npm http request GET http://192.168.1.100:4873/cycle
npm http request GET http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/pkginfo
npm http request GET http://192.168.1.100:4873/stack-trace
npm http 304 http://192.168.1.100:4873/colors
npm http 304 http://192.168.1.100:4873/pkginfo
npm http 304 http://192.168.1.100:4873/eyes
npm http 304 http://192.168.1.100:4873/cycle
npm http 304 http://192.168.1.100:4873/stack-trace
npm WARN EPACKAGEJSON thali-cordova-plugin-jxcore@1.0.0 No repository field.
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/bn.js
npm http request GET http://192.168.1.100:4873/child-process-promise
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/express-pouchdb
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/leveldown-mobile
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/nock
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/pouchdb-size
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/pouchdb
npm http request GET http://192.168.1.100:4873/proxyquire
npm http request GET http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/request-promise
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/sinon
npm http request GET http://192.168.1.100:4873/stacky
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/supertest
npm http request GET http://192.168.1.100:4873/supertest-as-promised
npm http request GET http://192.168.1.100:4873/tape-catch
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/tape
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/tmp
npm http request GET http://192.168.1.100:4873/uuid-validate
npm http 304 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/bn.js
npm http 304 http://192.168.1.100:4873/child-process-promise
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/express-pouchdb
npm http 304 http://192.168.1.100:4873/leveldown-mobile
npm http 304 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/js-extend
npm http 304 http://192.168.1.100:4873/minimist
npm http 304 http://192.168.1.100:4873/multiplex
npm http 304 http://192.168.1.100:4873/nock
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/pouchdb-size
npm http 304 http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/pouchdb
npm http 304 http://192.168.1.100:4873/randomstring
npm http 304 http://192.168.1.100:4873/proxyquire
npm http 304 http://192.168.1.100:4873/request-promise
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/stacky
npm http 304 http://192.168.1.100:4873/sinon
npm http 304 http://192.168.1.100:4873/socket.io-client
npm http 304 http://192.168.1.100:4873/supertest
npm http 304 http://192.168.1.100:4873/supertest-as-promised
npm http 304 http://192.168.1.100:4873/tape-catch
npm http 304 http://192.168.1.100:4873/urlsafe-base64
npm http 304 http://192.168.1.100:4873/tape
npm http 304 http://192.168.1.100:4873/uuid
npm http 304 http://192.168.1.100:4873/tmp
npm http 304 http://192.168.1.100:4873/uuid-validate
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/basic-auth
npm http request GET http://192.168.1.100:4873/cookie-parser
npm http request GET http://192.168.1.100:4873/header-case-normalizer
npm http request GET http://192.168.1.100:4873/compression
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/multiparty
npm http request GET http://192.168.1.100:4873/pouchdb-all-dbs
npm http request GET http://192.168.1.100:4873/pouchdb-auth
npm http request GET http://192.168.1.100:4873/pouchdb-show
npm http request GET http://192.168.1.100:4873/pouchdb-list
npm http request GET http://192.168.1.100:4873/pouchdb-replicator
npm http request GET http://192.168.1.100:4873/pouchdb-rewrite
npm http request GET http://192.168.1.100:4873/pouchdb-security
npm http request GET http://192.168.1.100:4873/pouchdb-find
npm http request GET http://192.168.1.100:4873/pouchdb-update
npm http request GET http://192.168.1.100:4873/pouchdb-validation
npm http request GET http://192.168.1.100:4873/pouchdb-vhost
npm http request GET http://192.168.1.100:4873/pouchdb-wrappers
npm http 304 http://192.168.1.100:4873/basic-auth
npm http 304 http://192.168.1.100:4873/cookie-parser
npm http 304 http://192.168.1.100:4873/header-case-normalizer
npm http 304 http://192.168.1.100:4873/compression
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/multiparty
npm http 304 http://192.168.1.100:4873/pouchdb-all-dbs
npm http 304 http://192.168.1.100:4873/pouchdb-auth
npm http 304 http://192.168.1.100:4873/pouchdb-list
npm http 304 http://192.168.1.100:4873/pouchdb-show
npm http 304 http://192.168.1.100:4873/pouchdb-replicator
npm http 304 http://192.168.1.100:4873/pouchdb-rewrite
npm http 304 http://192.168.1.100:4873/pouchdb-security
npm http 304 http://192.168.1.100:4873/pouchdb-find
npm http 304 http://192.168.1.100:4873/pouchdb-update
npm http 304 http://192.168.1.100:4873/pouchdb-validation
npm http 304 http://192.168.1.100:4873/pouchdb-vhost
npm http 304 http://192.168.1.100:4873/pouchdb-wrappers
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/bytes
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/setprototypeof
npm http 304 http://192.168.1.100:4873/setprototypeof
npm http request GET http://192.168.1.100:4873/accepts
npm http request GET http://192.168.1.100:4873/vary
npm http request GET http://192.168.1.100:4873/on-headers
npm http request GET http://192.168.1.100:4873/compressible
npm http 304 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/on-headers
npm http 304 http://192.168.1.100:4873/vary
npm http 304 http://192.168.1.100:4873/compressible
npm http request GET http://192.168.1.100:4873/negotiator
npm http 304 http://192.168.1.100:4873/negotiator
npm http request GET http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/cookie
npm http request GET http://192.168.1.100:4873/stream-counter
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/stream-counter
npm http 304 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/tiny-queue
npm http 304 http://192.168.1.100:4873/es3ify
npm http 304 http://192.168.1.100:4873/tiny-queue
npm http 304 http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/base62
npm http 304 http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/base64url
npm http request GET http://192.168.1.100:4873/pouchdb-plugin-error
npm http request GET http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http request GET http://192.168.1.100:4873/couchdb-calculate-session-id
npm http request GET http://192.168.1.100:4873/pouchdb-req-http-query
npm http request GET http://192.168.1.100:4873/pouchdb-system-db
npm http request GET http://192.168.1.100:4873/crypto-lite
npm http request GET http://192.168.1.100:4873/promise-nodify
npm http request GET http://192.168.1.100:4873/secure-random
npm http fetch GET http://192.168.1.100:4873/pouchdb-promise/-/pouchdb-promise-5.4.5.tgz
npm http 304 http://192.168.1.100:4873/base64url
npm http 304 http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http 304 http://192.168.1.100:4873/pouchdb-req-http-query
npm http 304 http://192.168.1.100:4873/couchdb-calculate-session-id
npm http 304 http://192.168.1.100:4873/pouchdb-system-db
npm http fetch 200 http://192.168.1.100:4873/pouchdb-promise/-/pouchdb-promise-5.4.5.tgz
npm http 304 http://192.168.1.100:4873/crypto-lite
npm http 304 http://192.168.1.100:4873/secure-random
npm http 304 http://192.168.1.100:4873/promise-nodify
npm http 304 http://192.168.1.100:4873/pouchdb-plugin-error
npm http request GET http://192.168.1.100:4873/meow
npm http request GET http://192.168.1.100:4873/concat-stream
npm http 304 http://192.168.1.100:4873/meow
npm http 304 http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/typedarray
npm http 304 http://192.168.1.100:4873/typedarray
npm http request GET http://192.168.1.100:4873/camelcase-keys
npm http request GET http://192.168.1.100:4873/indent-string
npm http 304 http://192.168.1.100:4873/camelcase-keys
npm http 304 http://192.168.1.100:4873/indent-string
npm http request GET http://192.168.1.100:4873/map-obj
npm http request GET http://192.168.1.100:4873/camelcase
npm http 304 http://192.168.1.100:4873/map-obj
npm http 304 http://192.168.1.100:4873/camelcase
npm http request GET http://192.168.1.100:4873/get-stdin
npm http request GET http://192.168.1.100:4873/repeating
npm http 304 http://192.168.1.100:4873/get-stdin
npm http 304 http://192.168.1.100:4873/repeating
npm http request GET http://192.168.1.100:4873/is-finite
npm http 304 http://192.168.1.100:4873/is-finite
npm http request GET http://192.168.1.100:4873/number-is-nan
npm http 304 http://192.168.1.100:4873/number-is-nan
npm http request GET http://192.168.1.100:4873/aproba
npm http 304 http://192.168.1.100:4873/aproba
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/fruitdown
npm http request GET http://192.168.1.100:4873/es6-promise-pool
npm http request GET http://192.168.1.100:4873/level-write-stream
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/localstorage-down
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/memdown
npm http request GET http://192.168.1.100:4873/pouchdb-collate
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/scope-eval
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/through2
npm http 304 http://192.168.1.100:4873/double-ended-queue
npm http 304 http://192.168.1.100:4873/levelup
npm http 304 http://192.168.1.100:4873/js-extend
npm http 304 http://192.168.1.100:4873/fruitdown
npm http 304 http://192.168.1.100:4873/level-write-stream
npm http 304 http://192.168.1.100:4873/memdown
npm http 304 http://192.168.1.100:4873/localstorage-down
npm http 304 http://192.168.1.100:4873/pouchdb-collections
npm http 304 http://192.168.1.100:4873/es6-promise-pool
npm http 304 http://192.168.1.100:4873/scope-eval
npm http 304 http://192.168.1.100:4873/spark-md5
npm http 304 http://192.168.1.100:4873/sublevel-pouchdb
npm http 304 http://192.168.1.100:4873/through2
npm http 304 http://192.168.1.100:4873/pouchdb-collate
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/d64
npm http 304 http://192.168.1.100:4873/d64
npm http 304 http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/end-stream
npm http 304 http://192.168.1.100:4873/end-stream
npm http request GET http://192.168.1.100:4873/write-stream
npm http 304 http://192.168.1.100:4873/write-stream
npm http request GET http://192.168.1.100:4873/humble-localstorage
npm http 304 http://192.168.1.100:4873/humble-localstorage
npm http request GET http://192.168.1.100:4873/has-localstorage
npm http request GET http://192.168.1.100:4873/localstorage-memory
npm http 304 http://192.168.1.100:4873/has-localstorage
npm http 304 http://192.168.1.100:4873/localstorage-memory
npm http request GET http://192.168.1.100:4873/ltgt
npm http request GET http://192.168.1.100:4873/functional-red-black-tree
npm http 304 http://192.168.1.100:4873/ltgt
npm http 304 http://192.168.1.100:4873/functional-red-black-tree
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/aws4
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/is-typedarray
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/aws4
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/is-typedarray
npm http 304 http://192.168.1.100:4873/tough-cookie
npm WARN deprecated tough-cookie@2.2.2: ReDoS vulnerability parsing Set-Cookie https://nodesecurity.io/advisories/130
npm http request GET http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/pinkie-promise
npm http 304 http://192.168.1.100:4873/pinkie-promise
npm http request GET http://192.168.1.100:4873/pinkie
npm http 304 http://192.168.1.100:4873/pinkie
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
npm http 304 http://192.168.1.100:4873/verror
npm http 304 http://192.168.1.100:4873/json-schema
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/dashdash
npm http request GET http://192.168.1.100:4873/getpass
npm http 304 http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/dashdash
npm http 304 http://192.168.1.100:4873/getpass
npm http request GET http://192.168.1.100:4873/pull-stream
npm http 304 http://192.168.1.100:4873/pull-stream
npm http request GET http://192.168.1.100:4873/pull-core
npm http 304 http://192.168.1.100:4873/pull-core
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/lie
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/xmlhttprequest-cookie
npm http 304 http://192.168.1.100:4873/xmlhttprequest-cookie
npm http request GET http://192.168.1.100:4873/xmlhttprequest
npm http 304 http://192.168.1.100:4873/xmlhttprequest
npm http request GET http://192.168.1.100:4873/pouchdb-changeslike-wrapper
npm http 304 http://192.168.1.100:4873/pouchdb-changeslike-wrapper
npm http request GET http://192.168.1.100:4873/couchdb-objects
npm http request GET http://192.168.1.100:4873/couchdb-eval
npm http request GET http://192.168.1.100:4873/random-uuid-v4
npm http 304 http://192.168.1.100:4873/couchdb-eval
npm http 304 http://192.168.1.100:4873/couchdb-objects
npm http 304 http://192.168.1.100:4873/random-uuid-v4
npm http request GET http://192.168.1.100:4873/is-empty
npm http 304 http://192.168.1.100:4873/is-empty
npm http request GET http://192.168.1.100:4873/is-array
npm http request GET http://192.168.1.100:4873/pouchdb-extend
npm http request GET http://192.168.1.100:4873/pouchdb-upsert
npm http 304 http://192.168.1.100:4873/is-array
npm http 304 http://192.168.1.100:4873/pouchdb-extend
npm http 304 http://192.168.1.100:4873/pouchdb-upsert
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 304 http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/recast
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/ast-types
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/ast-types
npm http request GET http://192.168.1.100:4873/couchdb-render
npm http 304 http://192.168.1.100:4873/couchdb-render
npm http request GET http://192.168.1.100:4873/couchdb-resp-completer
npm http 304 http://192.168.1.100:4873/couchdb-resp-completer
npm http request GET http://192.168.1.100:4873/equals
npm http 304 http://192.168.1.100:4873/equals
npm http request GET http://192.168.1.100:4873/jkroso-type
npm http 304 http://192.168.1.100:4873/jkroso-type
npm http request GET http://192.168.1.100:4873/pouchdb-route
npm http 304 http://192.168.1.100:4873/pouchdb-route
npm http request GET http://192.168.1.100:4873/get-folder-size
npm http 304 http://192.168.1.100:4873/get-folder-size
npm http request GET http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/minimist
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/fast-future
npm http 304 http://192.168.1.100:4873/fast-future
npm http 304 http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/propagate
npm http request GET http://192.168.1.100:4873/chai
npm http request GET http://192.168.1.100:4873/deep-equal
npm http request GET http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/propagate
npm http 304 http://192.168.1.100:4873/deep-equal
npm http 304 http://192.168.1.100:4873/chai
npm http 304 http://192.168.1.100:4873/debug
npm WARN deprecated lodash@2.4.1: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
npm http request GET http://192.168.1.100:4873/assertion-error
npm http request GET http://192.168.1.100:4873/deep-eql
npm http request GET http://192.168.1.100:4873/type-detect
npm http 304 http://192.168.1.100:4873/assertion-error
npm http 304 http://192.168.1.100:4873/deep-eql
npm http 304 http://192.168.1.100:4873/type-detect
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/level-codec
npm http request GET http://192.168.1.100:4873/leveldown
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/level-codec
npm http 304 http://192.168.1.100:4873/leveldown
npm http request GET http://192.168.1.100:4873/nan
npm http request GET http://192.168.1.100:4873/prebuild
npm http 304 http://192.168.1.100:4873/nan
npm http 304 http://192.168.1.100:4873/prebuild
npm http request GET http://192.168.1.100:4873/execspawn
npm http request GET http://192.168.1.100:4873/expand-template
npm http request GET http://192.168.1.100:4873/github-from-package
npm http request GET http://192.168.1.100:4873/noop-logger
npm http request GET http://192.168.1.100:4873/node-ninja
npm http request GET http://192.168.1.100:4873/ghreleases
npm http request GET http://192.168.1.100:4873/npmlog
npm http request GET http://192.168.1.100:4873/os-homedir
npm http request GET http://192.168.1.100:4873/node-gyp
npm http request GET http://192.168.1.100:4873/pump
npm http request GET http://192.168.1.100:4873/rc
npm http request GET http://192.168.1.100:4873/simple-get
npm http request GET http://192.168.1.100:4873/tar-fs
npm http request GET http://192.168.1.100:4873/tar-stream
npm http 304 http://192.168.1.100:4873/execspawn
npm http 304 http://192.168.1.100:4873/github-from-package
npm http 304 http://192.168.1.100:4873/expand-template
npm http 304 http://192.168.1.100:4873/noop-logger
npm http 304 http://192.168.1.100:4873/node-ninja
npm http 304 http://192.168.1.100:4873/ghreleases
npm http 304 http://192.168.1.100:4873/npmlog
npm http 304 http://192.168.1.100:4873/os-homedir
npm http 304 http://192.168.1.100:4873/pump
npm http 304 http://192.168.1.100:4873/node-gyp
npm http 304 http://192.168.1.100:4873/rc
npm http 304 http://192.168.1.100:4873/simple-get
npm http 304 http://192.168.1.100:4873/tar-fs
npm http 304 http://192.168.1.100:4873/tar-stream
npm http request GET http://192.168.1.100:4873/util-extend
npm http 304 http://192.168.1.100:4873/util-extend
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/ghutils
npm http request GET http://192.168.1.100:4873/simple-mime
npm http request GET http://192.168.1.100:4873/ghrepos
npm http request GET http://192.168.1.100:4873/url-template
npm http 304 http://192.168.1.100:4873/after
npm http 304 http://192.168.1.100:4873/ghutils
npm http 304 http://192.168.1.100:4873/simple-mime
npm http 304 http://192.168.1.100:4873/url-template
npm http 304 http://192.168.1.100:4873/ghrepos
npm http request GET http://192.168.1.100:4873/jsonist
npm http 304 http://192.168.1.100:4873/jsonist
npm http request GET http://192.168.1.100:4873/hyperquest
npm http 304 http://192.168.1.100:4873/hyperquest
npm http request GET http://192.168.1.100:4873/duplexer2
npm http 304 http://192.168.1.100:4873/duplexer2
npm http request GET http://192.168.1.100:4873/fstream
npm http request GET http://192.168.1.100:4873/osenv
npm http request GET http://192.168.1.100:4873/nopt
npm http request GET http://192.168.1.100:4873/tar
npm http request GET http://192.168.1.100:4873/which
npm http request GET http://192.168.1.100:4873/semver
npm http 304 http://192.168.1.100:4873/fstream
npm http 304 http://192.168.1.100:4873/osenv
npm http 304 http://192.168.1.100:4873/nopt
npm http 304 http://192.168.1.100:4873/tar
npm http 304 http://192.168.1.100:4873/which
npm http 304 http://192.168.1.100:4873/semver
npm http request GET http://192.168.1.100:4873/abbrev
npm http 304 http://192.168.1.100:4873/abbrev
npm http request GET http://192.168.1.100:4873/ansi
npm http request GET http://192.168.1.100:4873/are-we-there-yet
npm http request GET http://192.168.1.100:4873/gauge
npm http 304 http://192.168.1.100:4873/ansi
npm http 304 http://192.168.1.100:4873/gauge
npm http 304 http://192.168.1.100:4873/are-we-there-yet
npm http request GET http://192.168.1.100:4873/delegates
npm http 304 http://192.168.1.100:4873/delegates
npm http request GET http://192.168.1.100:4873/has-unicode
npm http request GET http://192.168.1.100:4873/lodash.pad
npm http request GET http://192.168.1.100:4873/lodash.padend
npm http request GET http://192.168.1.100:4873/lodash.padstart
npm http 304 http://192.168.1.100:4873/has-unicode
npm http 304 http://192.168.1.100:4873/lodash.pad
npm http 304 http://192.168.1.100:4873/lodash.padend
npm http 304 http://192.168.1.100:4873/lodash.padstart
npm http request GET http://192.168.1.100:4873/os-tmpdir
npm http 304 http://192.168.1.100:4873/os-tmpdir
npm http request GET http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/block-stream
npm http 304 http://192.168.1.100:4873/block-stream
npm http request GET http://192.168.1.100:4873/isexe
npm http 304 http://192.168.1.100:4873/isexe
npm http request GET http://192.168.1.100:4873/path-array
npm http 304 http://192.168.1.100:4873/path-array
npm http request GET http://192.168.1.100:4873/array-index
npm http 304 http://192.168.1.100:4873/array-index
npm http request GET http://192.168.1.100:4873/es6-symbol
npm http 304 http://192.168.1.100:4873/es6-symbol
npm http request GET http://192.168.1.100:4873/d
npm http request GET http://192.168.1.100:4873/es5-ext
npm http 304 http://192.168.1.100:4873/es5-ext
npm http 304 http://192.168.1.100:4873/d
npm http request GET http://192.168.1.100:4873/es6-iterator
npm http 304 http://192.168.1.100:4873/es6-iterator
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http 304 http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/deep-extend
npm http request GET http://192.168.1.100:4873/ini
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http 304 http://192.168.1.100:4873/deep-extend
npm http 304 http://192.168.1.100:4873/strip-json-comments
npm http 304 http://192.168.1.100:4873/ini
npm http request GET http://192.168.1.100:4873/unzip-response
npm http 304 http://192.168.1.100:4873/unzip-response
npm http request GET http://192.168.1.100:4873/chownr
npm http 304 http://192.168.1.100:4873/chownr
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/asynckit
npm http 304 http://192.168.1.100:4873/asynckit
npm http request GET http://192.168.1.100:4873/fill-keys
npm http request GET http://192.168.1.100:4873/module-not-found-error
npm http 304 http://192.168.1.100:4873/fill-keys
npm http 304 http://192.168.1.100:4873/module-not-found-error
npm http request GET http://192.168.1.100:4873/is-object
npm http 304 http://192.168.1.100:4873/is-object
npm http request GET http://192.168.1.100:4873/array-uniq
npm http 304 http://192.168.1.100:4873/array-uniq
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/formatio
npm http request GET http://192.168.1.100:4873/util
npm http request GET http://192.168.1.100:4873/lolex
npm http request GET http://192.168.1.100:4873/samsam
npm http 304 http://192.168.1.100:4873/formatio
npm http 304 http://192.168.1.100:4873/util
npm http 304 http://192.168.1.100:4873/lolex
npm http 304 http://192.168.1.100:4873/samsam
npm http request GET http://192.168.1.100:4873/component-bind
npm http request GET http://192.168.1.100:4873/engine.io-client
npm http request GET http://192.168.1.100:4873/component-emitter
npm http request GET http://192.168.1.100:4873/object-component
npm http request GET http://192.168.1.100:4873/has-binary
npm http request GET http://192.168.1.100:4873/socket.io-parser
npm http request GET http://192.168.1.100:4873/indexof
npm http request GET http://192.168.1.100:4873/parseuri
npm http request GET http://192.168.1.100:4873/backo2
npm http request GET http://192.168.1.100:4873/to-array
npm http 304 http://192.168.1.100:4873/component-bind
npm http 304 http://192.168.1.100:4873/component-emitter
npm http 304 http://192.168.1.100:4873/engine.io-client
npm http 304 http://192.168.1.100:4873/object-component
npm http 304 http://192.168.1.100:4873/has-binary
npm http 304 http://192.168.1.100:4873/socket.io-parser
npm http 304 http://192.168.1.100:4873/indexof
npm http 304 http://192.168.1.100:4873/backo2
npm http 304 http://192.168.1.100:4873/parseuri
npm http 304 http://192.168.1.100:4873/to-array
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/xmlhttprequest-ssl
npm http request GET http://192.168.1.100:4873/ws
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/parseqs
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/yeast
npm http 304 http://192.168.1.100:4873/has-cors
npm http 304 http://192.168.1.100:4873/xmlhttprequest-ssl
npm http 304 http://192.168.1.100:4873/ws
npm http 304 http://192.168.1.100:4873/parsejson
npm http 304 http://192.168.1.100:4873/engine.io-parser
npm http 304 http://192.168.1.100:4873/parseqs
npm http 304 http://192.168.1.100:4873/component-inherit
npm http 304 http://192.168.1.100:4873/yeast
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/utf8
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/blob
npm http 304 http://192.168.1.100:4873/base64-arraybuffer
npm http 304 http://192.168.1.100:4873/utf8
npm http 304 http://192.168.1.100:4873/arraybuffer.slice
npm http 304 http://192.168.1.100:4873/blob
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
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/superagent
npm http 304 http://192.168.1.100:4873/superagent
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/formidable
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/cookiejar
npm http request GET http://192.168.1.100:4873/reduce-component
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/formidable
npm http 304 http://192.168.1.100:4873/cookiejar
npm http 304 http://192.168.1.100:4873/reduce-component
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/mime-types
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
npm http 304 http://192.168.1.100:4873/resumer
npm http 304 http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/object-inspect
npm WARN prefer global node-ninja@1.0.2 should be installed with -g
npm WARN prefer global node-gyp@3.6.0 should be installed with -g
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
clang: warning: libstdc++ is deprecated; move to libc++ with a minimum deployment target of OS X 10.9
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
clang: warning: libstdc++ is deprecated; move to libc++ with a minimum deployment target of OS X 10.9
npm WARN EPACKAGEJSON thali-cordova-plugin-jxcore@1.0.0 No repository field.
Note: Some input files use or override a deprecated API.
Note: Recompile with -Xlint:deprecation for details.
Note: Some input files use or override a deprecated API.
Note: Recompile with -Xlint:deprecation for details.
Note: Some input files use or override a deprecated API.
Note: Recompile with -Xlint:deprecation for details.
/Users/thali/Github/ThaliTest/platforms/android/assets/www/jxcore/node_modules/node-gyp/test/fixtures/server.key: Error: The fixtures/server.key file seems to be a private key file. Please make sure not to embed this in your APK file. [PackagedPrivateKey]
/Users/thali/Github/ThaliTest/platforms/android/assets/www/jxcore/node_modules/node-ninja/test/fixtures/server.key: Error: The fixtures/server.key file seems to be a private key file. Please make sure not to embed this in your APK file. [PackagedPrivateKey]

   Explanation for issues of type "PackagedPrivateKey":
   In general, you should not package private key files inside your app.

2 errors, 0 warnings
** BUILD FAILED **


The following build commands failed:
	CompileSwift normal arm64 /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/org.thaliproject.p2p/AppContext.swift
	CompileSwiftSources normal arm64 com.apple.xcode.tools.swift.compiler
(2 failures)

```

Error: Command failed: npm WARN thali-test-server@0.0.1 No repository field.
npm WARN thali-test-server@0.0.1 No license field.
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/javascript-state-machine
npm http request GET http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-leveldb-core
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/winston
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/javascript-state-machine
npm http 200 http://192.168.1.100:4873/ip
npm http 304 http://192.168.1.100:4873/lie
npm http 304 http://192.168.1.100:4873/multiplex
npm http 304 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/urlsafe-base64
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-leveldb-core
npm http 200 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/uuid
npm http 200 http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/content-type
npm http 200 http://192.168.1.100:4873/bytes
npm http 304 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/type-is
npm http 200 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/http-errors
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
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/send
npm http 304 http://192.168.1.100:4873/serve-static
npm http 304 http://192.168.1.100:4873/utils-merge
npm http 304 http://192.168.1.100:4873/vary
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
npm http 304 http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/varint
npm http 304 http://192.168.1.100:4873/duplexify
npm http 304 http://192.168.1.100:4873/xtend
npm http 200 http://192.168.1.100:4873/readable-stream
npm http fetch GET http://192.168.1.100:4873/readable-stream/-/readable-stream-2.2.6.tgz
npm http fetch 200 http://192.168.1.100:4873/readable-stream/-/readable-stream-2.2.6.tgz
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
npm http request GET http://192.168.1.100:4873/string_decoder
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http 304 http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/buffer-shims
npm http 304 http://192.168.1.100:4873/string_decoder
npm http 304 http://192.168.1.100:4873/util-deprecate
npm http 200 http://192.168.1.100:4873/core-util-is
npm http 304 http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/argsarray
npm http request GET http://192.168.1.100:4873/buffer-from
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/pouchdb-md5
npm http request GET http://192.168.1.100:4873/pouchdb-merge
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-utils
npm http request GET http://192.168.1.100:4873/pouchdb-binary-utils
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/pouchdb-errors
npm http request GET http://192.168.1.100:4873/pouchdb-json
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/pouchdb-utils
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/through2
npm http 304 http://192.168.1.100:4873/buffer-from
npm http 200 http://192.168.1.100:4873/argsarray
npm http 304 http://192.168.1.100:4873/pouchdb-md5
npm http 304 http://192.168.1.100:4873/double-ended-queue
npm http 304 http://192.168.1.100:4873/pouchdb-merge
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-utils
npm http 304 http://192.168.1.100:4873/pouchdb-binary-utils
npm http 304 http://192.168.1.100:4873/pouchdb-errors
npm http 304 http://192.168.1.100:4873/pouchdb-collections
npm http 304 http://192.168.1.100:4873/pouchdb-json
npm http 304 http://192.168.1.100:4873/pouchdb-utils
npm http 304 http://192.168.1.100:4873/sublevel-pouchdb
npm http 200 http://192.168.1.100:4873/pouchdb-promise
npm http 200 http://192.168.1.100:4873/through2
npm http 200 http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/is-array-buffer-x
npm http 200 http://192.168.1.100:4873/is-array-buffer-x
npm http fetch GET http://192.168.1.100:4873/is-array-buffer-x/-/is-array-buffer-x-1.2.1.tgz
npm http fetch 200 http://192.168.1.100:4873/is-array-buffer-x/-/is-array-buffer-x-1.2.1.tgz
npm http request GET http://192.168.1.100:4873/is-object-like-x
npm http request GET http://192.168.1.100:4873/to-string-tag-x
npm http request GET http://192.168.1.100:4873/has-to-string-tag-x
npm http 200 http://192.168.1.100:4873/is-object-like-x
npm http 200 http://192.168.1.100:4873/to-string-tag-x
npm http 200 http://192.168.1.100:4873/has-to-string-tag-x
npm http fetch GET http://192.168.1.100:4873/has-to-string-tag-x/-/has-to-string-tag-x-1.2.0.tgz
npm http fetch GET http://192.168.1.100:4873/is-object-like-x/-/is-object-like-x-1.2.0.tgz
npm http fetch GET http://192.168.1.100:4873/to-string-tag-x/-/to-string-tag-x-1.2.0.tgz
npm http fetch 200 http://192.168.1.100:4873/has-to-string-tag-x/-/has-to-string-tag-x-1.2.0.tgz
npm http fetch 200 http://192.168.1.100:4873/is-object-like-x/-/is-object-like-x-1.2.0.tgz
npm http fetch 200 http://192.168.1.100:4873/to-string-tag-x/-/to-string-tag-x-1.2.0.tgz
npm http request GET http://192.168.1.100:4873/has-symbol-support-x
npm http 200 http://192.168.1.100:4873/has-symbol-support-x
npm http fetch GET http://192.168.1.100:4873/has-symbol-support-x/-/has-symbol-support-x-1.2.0.tgz
npm http fetch 200 http://192.168.1.100:4873/has-symbol-support-x/-/has-symbol-support-x-1.2.0.tgz
npm http request GET http://192.168.1.100:4873/is-function-x
npm http request GET http://192.168.1.100:4873/is-primitive
npm http 304 http://192.168.1.100:4873/is-primitive
npm http 200 http://192.168.1.100:4873/is-function-x
npm http fetch GET http://192.168.1.100:4873/is-function-x/-/is-function-x-1.2.0.tgz
npm http fetch 200 http://192.168.1.100:4873/is-function-x/-/is-function-x-1.2.0.tgz
npm http request GET http://192.168.1.100:4873/lodash.isnull
npm http request GET http://192.168.1.100:4873/validate.io-undefined
npm http 304 http://192.168.1.100:4873/validate.io-undefined
npm http 304 http://192.168.1.100:4873/lodash.isnull
npm http request GET http://192.168.1.100:4873/deferred-leveldown
npm http request GET http://192.168.1.100:4873/level-errors
npm http request GET http://192.168.1.100:4873/level-codec
npm http request GET http://192.168.1.100:4873/level-iterator-stream
npm http request GET http://192.168.1.100:4873/prr
npm http request GET http://192.168.1.100:4873/semver
npm http 304 http://192.168.1.100:4873/deferred-leveldown
npm http 304 http://192.168.1.100:4873/level-errors
npm http 304 http://192.168.1.100:4873/level-codec
npm http 304 http://192.168.1.100:4873/level-iterator-stream
npm http 304 http://192.168.1.100:4873/prr
npm http 200 http://192.168.1.100:4873/semver
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http 304 http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/errno
npm http 304 http://192.168.1.100:4873/errno
npm http request GET http://192.168.1.100:4873/spark-md5
npm http 304 http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/clone-buffer
npm http 304 http://192.168.1.100:4873/clone-buffer
npm http request GET http://192.168.1.100:4873/vuvuzela
npm http 304 http://192.168.1.100:4873/vuvuzela
npm http request GET http://192.168.1.100:4873/ltgt
npm http 200 http://192.168.1.100:4873/ltgt
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/caseless
npm http 200 http://192.168.1.100:4873/bl
npm http 200 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/form-data
npm WARN deprecated node-uuid@1.4.8: Use uuid module instead
npm http fetch GET http://192.168.1.100:4873/node-uuid/-/node-uuid-1.4.8.tgz
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 200 http://192.168.1.100:4873/tunnel-agent
npm http 200 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/combined-stream
npm http fetch 200 http://192.168.1.100:4873/node-uuid/-/node-uuid-1.4.8.tgz
npm http 200 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 200 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http fetch GET http://192.168.1.100:4873/async/-/async-2.3.0.tgz
npm http fetch 200 http://192.168.1.100:4873/async/-/async-2.3.0.tgz
npm http request GET http://192.168.1.100:4873/lodash
npm http 200 http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/is-my-json-valid
npm http 200 http://192.168.1.100:4873/chalk
npm http 200 http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 200 http://192.168.1.100:4873/ansi-styles
npm http 200 http://192.168.1.100:4873/strip-ansi
npm http 200 http://192.168.1.100:4873/has-ansi
npm http 200 http://192.168.1.100:4873/supports-color
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 200 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http 304 http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-function
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http request GET http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/boom
npm http 200 http://192.168.1.100:4873/cryptiles
npm http 200 http://192.168.1.100:4873/sntp
npm http 200 http://192.168.1.100:4873/boom
npm http 200 http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/asn1
npm http 200 http://192.168.1.100:4873/assert-plus
npm http 304 http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/punycode
npm http 200 http://192.168.1.100:4873/punycode
npm http request GET http://192.168.1.100:4873/jsonschema
npm http 200 http://192.168.1.100:4873/jsonschema
npm http request GET http://192.168.1.100:4873/colors
npm http request GET http://192.168.1.100:4873/cycle
npm http request GET http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/pkginfo
npm http request GET http://192.168.1.100:4873/stack-trace
npm http 304 http://192.168.1.100:4873/colors
npm http 304 http://192.168.1.100:4873/cycle
npm http 304 http://192.168.1.100:4873/eyes
npm http 304 http://192.168.1.100:4873/stack-trace
npm http 304 http://192.168.1.100:4873/pkginfo
npm http request GET http://192.168.1.100:4873/jsdoc
npm http request GET http://192.168.1.100:4873/eslint
npm http 200 http://192.168.1.100:4873/jsdoc
npm http 200 http://192.168.1.100:4873/eslint
npm http request GET http://192.168.1.100:4873/babel-code-frame
npm http request GET http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/doctrine
npm http request GET http://192.168.1.100:4873/escope
npm http request GET http://192.168.1.100:4873/espree
npm http request GET http://192.168.1.100:4873/estraverse
npm http request GET http://192.168.1.100:4873/esutils
npm http request GET http://192.168.1.100:4873/file-entry-cache
npm http request GET http://192.168.1.100:4873/globals
npm http request GET http://192.168.1.100:4873/ignore
npm http request GET http://192.168.1.100:4873/imurmurhash
npm http request GET http://192.168.1.100:4873/inquirer
npm http request GET http://192.168.1.100:4873/is-resolvable
npm http request GET http://192.168.1.100:4873/js-yaml
npm http request GET http://192.168.1.100:4873/json-stable-stringify
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/natural-compare
npm http request GET http://192.168.1.100:4873/optionator
npm http request GET http://192.168.1.100:4873/levn
npm http request GET http://192.168.1.100:4873/path-is-inside
npm http request GET http://192.168.1.100:4873/progress
npm http request GET http://192.168.1.100:4873/pluralize
npm http request GET http://192.168.1.100:4873/require-uncached
npm http request GET http://192.168.1.100:4873/shelljs
npm http request GET http://192.168.1.100:4873/strip-bom
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/text-table
npm http request GET http://192.168.1.100:4873/table
npm http request GET http://192.168.1.100:4873/user-home
npm http 200 http://192.168.1.100:4873/concat-stream
npm http 200 http://192.168.1.100:4873/babel-code-frame
npm http 304 http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/doctrine
npm http 200 http://192.168.1.100:4873/escope
npm http 304 http://192.168.1.100:4873/estraverse
npm http 304 http://192.168.1.100:4873/esutils
npm http 304 http://192.168.1.100:4873/file-entry-cache
npm http 200 http://192.168.1.100:4873/globals
npm http 200 http://192.168.1.100:4873/espree
npm http 304 http://192.168.1.100:4873/imurmurhash
npm http 304 http://192.168.1.100:4873/is-resolvable
npm http 200 http://192.168.1.100:4873/ignore
npm http fetch GET http://192.168.1.100:4873/globals/-/globals-9.17.0.tgz
npm http fetch GET http://192.168.1.100:4873/espree/-/espree-3.4.1.tgz
npm http 200 http://192.168.1.100:4873/js-yaml
npm http 200 http://192.168.1.100:4873/inquirer
npm http 304 http://192.168.1.100:4873/json-stable-stringify
npm http 304 http://192.168.1.100:4873/natural-compare
npm http 304 http://192.168.1.100:4873/levn
npm http 200 http://192.168.1.100:4873/mkdirp
npm http 200 http://192.168.1.100:4873/optionator
npm http fetch GET http://192.168.1.100:4873/ignore/-/ignore-3.2.6.tgz
npm http 304 http://192.168.1.100:4873/path-is-inside
npm http fetch GET http://192.168.1.100:4873/js-yaml/-/js-yaml-3.8.2.tgz
npm http 200 http://192.168.1.100:4873/progress
npm http 200 http://192.168.1.100:4873/require-uncached
npm http 200 http://192.168.1.100:4873/pluralize
npm http 200 http://192.168.1.100:4873/shelljs
npm http 304 http://192.168.1.100:4873/strip-bom
npm http 304 http://192.168.1.100:4873/user-home
npm http fetch 200 http://192.168.1.100:4873/globals/-/globals-9.17.0.tgz
npm http fetch 200 http://192.168.1.100:4873/ignore/-/ignore-3.2.6.tgz
npm http fetch 200 http://192.168.1.100:4873/espree/-/espree-3.4.1.tgz
npm http 200 http://192.168.1.100:4873/strip-json-comments
npm http 200 http://192.168.1.100:4873/text-table
npm http fetch 200 http://192.168.1.100:4873/js-yaml/-/js-yaml-3.8.2.tgz
npm http 200 http://192.168.1.100:4873/table
npm http fetch GET http://192.168.1.100:4873/shelljs/-/shelljs-0.7.7.tgz
npm http fetch 200 http://192.168.1.100:4873/shelljs/-/shelljs-0.7.7.tgz
npm http request GET http://192.168.1.100:4873/js-tokens
npm http 304 http://192.168.1.100:4873/js-tokens
npm http request GET http://192.168.1.100:4873/typedarray
npm http 304 http://192.168.1.100:4873/typedarray
npm http request GET http://192.168.1.100:4873/es6-map
npm http request GET http://192.168.1.100:4873/es6-weak-map
npm http request GET http://192.168.1.100:4873/esrecurse
npm http 304 http://192.168.1.100:4873/esrecurse
npm http 200 http://192.168.1.100:4873/es6-map
npm http 200 http://192.168.1.100:4873/es6-weak-map
npm http fetch GET http://192.168.1.100:4873/es6-map/-/es6-map-0.1.5.tgz
npm http fetch 200 http://192.168.1.100:4873/es6-map/-/es6-map-0.1.5.tgz
npm http fetch GET http://192.168.1.100:4873/es6-weak-map/-/es6-weak-map-2.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/es6-weak-map/-/es6-weak-map-2.0.2.tgz
npm http request GET http://192.168.1.100:4873/d
npm http request GET http://192.168.1.100:4873/es6-iterator
npm http request GET http://192.168.1.100:4873/es5-ext
npm http request GET http://192.168.1.100:4873/es6-set
npm http request GET http://192.168.1.100:4873/es6-symbol
npm http request GET http://192.168.1.100:4873/event-emitter
npm http 200 http://192.168.1.100:4873/d
npm http 200 http://192.168.1.100:4873/es6-iterator
npm http 200 http://192.168.1.100:4873/es6-set
npm http fetch GET http://192.168.1.100:4873/d/-/d-1.0.0.tgz
npm http 200 http://192.168.1.100:4873/es6-symbol
npm http 200 http://192.168.1.100:4873/es5-ext
npm http fetch GET http://192.168.1.100:4873/es6-iterator/-/es6-iterator-2.0.1.tgz
npm http fetch 200 http://192.168.1.100:4873/d/-/d-1.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/es6-iterator/-/es6-iterator-2.0.1.tgz
npm http fetch GET http://192.168.1.100:4873/es6-set/-/es6-set-0.1.5.tgz
npm http fetch GET http://192.168.1.100:4873/es6-symbol/-/es6-symbol-3.1.1.tgz
npm http 200 http://192.168.1.100:4873/event-emitter
npm http fetch GET http://192.168.1.100:4873/es5-ext/-/es5-ext-0.10.15.tgz
npm http fetch 200 http://192.168.1.100:4873/es6-set/-/es6-set-0.1.5.tgz
npm http fetch 200 http://192.168.1.100:4873/es6-symbol/-/es6-symbol-3.1.1.tgz
npm http fetch 200 http://192.168.1.100:4873/es5-ext/-/es5-ext-0.10.15.tgz
npm http fetch GET http://192.168.1.100:4873/event-emitter/-/event-emitter-0.3.5.tgz
npm http fetch 200 http://192.168.1.100:4873/event-emitter/-/event-emitter-0.3.5.tgz
npm http request GET http://192.168.1.100:4873/acorn-jsx
npm http request GET http://192.168.1.100:4873/acorn
npm http 304 http://192.168.1.100:4873/acorn-jsx
npm http 200 http://192.168.1.100:4873/acorn
npm http fetch GET http://192.168.1.100:4873/acorn/-/acorn-5.0.3.tgz
npm http fetch 200 http://192.168.1.100:4873/acorn/-/acorn-5.0.3.tgz
npm http request GET http://192.168.1.100:4873/flat-cache
npm http 304 http://192.168.1.100:4873/flat-cache
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/circular-json
npm http request GET http://192.168.1.100:4873/del
npm http request GET http://192.168.1.100:4873/write
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http 200 http://192.168.1.100:4873/circular-json
npm http 200 http://192.168.1.100:4873/del
npm http 200 http://192.168.1.100:4873/write
npm http request GET http://192.168.1.100:4873/rimraf
npm http request GET http://192.168.1.100:4873/is-path-cwd
npm http request GET http://192.168.1.100:4873/is-path-in-cwd
npm http request GET http://192.168.1.100:4873/pinkie-promise
npm http request GET http://192.168.1.100:4873/globby
npm http request GET http://192.168.1.100:4873/pify
npm http 304 http://192.168.1.100:4873/rimraf
npm http 304 http://192.168.1.100:4873/is-path-cwd
npm http 304 http://192.168.1.100:4873/is-path-in-cwd
npm http 304 http://192.168.1.100:4873/pinkie-promise
npm http 200 http://192.168.1.100:4873/globby
npm http 200 http://192.168.1.100:4873/pify
npm http request GET http://192.168.1.100:4873/array-union
npm http request GET http://192.168.1.100:4873/arrify
npm http 200 http://192.168.1.100:4873/array-union
npm http 200 http://192.168.1.100:4873/arrify
npm http request GET http://192.168.1.100:4873/array-uniq
npm http 200 http://192.168.1.100:4873/array-uniq
npm http request GET http://192.168.1.100:4873/fs.realpath
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/fs.realpath
npm http 304 http://192.168.1.100:4873/inflight
npm http 304 http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 304 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/pinkie
npm http 304 http://192.168.1.100:4873/pinkie
npm http request GET http://192.168.1.100:4873/is-path-inside
npm http 304 http://192.168.1.100:4873/is-path-inside
npm http request GET http://192.168.1.100:4873/minimist
npm http 200 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/ansi-escapes
npm http request GET http://192.168.1.100:4873/cli-width
npm http request GET http://192.168.1.100:4873/cli-cursor
npm http request GET http://192.168.1.100:4873/readline2
npm http request GET http://192.168.1.100:4873/figures
npm http request GET http://192.168.1.100:4873/run-async
npm http request GET http://192.168.1.100:4873/rx-lite
npm http request GET http://192.168.1.100:4873/string-width
npm http request GET http://192.168.1.100:4873/through
npm http 304 http://192.168.1.100:4873/ansi-escapes
npm http 304 http://192.168.1.100:4873/cli-width
npm http 304 http://192.168.1.100:4873/cli-cursor
npm http 304 http://192.168.1.100:4873/readline2
npm http 304 http://192.168.1.100:4873/figures
npm http 304 http://192.168.1.100:4873/run-async
npm http 200 http://192.168.1.100:4873/string-width
npm http 200 http://192.168.1.100:4873/through
npm http 200 http://192.168.1.100:4873/rx-lite
npm http request GET http://192.168.1.100:4873/restore-cursor
npm http 304 http://192.168.1.100:4873/restore-cursor
npm http request GET http://192.168.1.100:4873/exit-hook
npm http request GET http://192.168.1.100:4873/onetime
npm http 304 http://192.168.1.100:4873/exit-hook
npm http 200 http://192.168.1.100:4873/onetime
npm http request GET http://192.168.1.100:4873/code-point-at
npm http request GET http://192.168.1.100:4873/is-fullwidth-code-point
npm http request GET http://192.168.1.100:4873/mute-stream
npm http 304 http://192.168.1.100:4873/is-fullwidth-code-point
npm http 304 http://192.168.1.100:4873/code-point-at
npm http 304 http://192.168.1.100:4873/mute-stream
npm http request GET http://192.168.1.100:4873/number-is-nan
npm http 200 http://192.168.1.100:4873/number-is-nan
npm http request GET http://192.168.1.100:4873/tryit
npm http 304 http://192.168.1.100:4873/tryit
npm http request GET http://192.168.1.100:4873/argparse
npm http request GET http://192.168.1.100:4873/esprima
npm http 304 http://192.168.1.100:4873/argparse
npm http 200 http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/sprintf-js
npm http 200 http://192.168.1.100:4873/sprintf-js
npm http request GET http://192.168.1.100:4873/jsonify
npm http 304 http://192.168.1.100:4873/jsonify
npm http request GET http://192.168.1.100:4873/prelude-ls
npm http request GET http://192.168.1.100:4873/type-check
npm http 304 http://192.168.1.100:4873/prelude-ls
npm http 304 http://192.168.1.100:4873/type-check
npm http request GET http://192.168.1.100:4873/deep-is
npm http request GET http://192.168.1.100:4873/wordwrap
npm http request GET http://192.168.1.100:4873/fast-levenshtein
npm http 304 http://192.168.1.100:4873/deep-is
npm http 304 http://192.168.1.100:4873/fast-levenshtein
npm http 200 http://192.168.1.100:4873/wordwrap
npm http request GET http://192.168.1.100:4873/caller-path
npm http request GET http://192.168.1.100:4873/resolve-from
npm http 304 http://192.168.1.100:4873/caller-path
npm http 304 http://192.168.1.100:4873/resolve-from
npm http request GET http://192.168.1.100:4873/callsites
npm http 304 http://192.168.1.100:4873/callsites
npm http request GET http://192.168.1.100:4873/interpret
npm http request GET http://192.168.1.100:4873/rechoir
npm http 304 http://192.168.1.100:4873/rechoir
npm http 200 http://192.168.1.100:4873/interpret
npm http fetch GET http://192.168.1.100:4873/interpret/-/interpret-1.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/interpret/-/interpret-1.0.2.tgz
npm http request GET http://192.168.1.100:4873/resolve
npm http 304 http://192.168.1.100:4873/resolve
npm http request GET http://192.168.1.100:4873/path-parse
npm http 304 http://192.168.1.100:4873/path-parse
npm http request GET http://192.168.1.100:4873/slice-ansi
npm http request GET http://192.168.1.100:4873/ajv-keywords
npm http request GET http://192.168.1.100:4873/ajv
npm http 304 http://192.168.1.100:4873/slice-ansi
npm http 200 http://192.168.1.100:4873/ajv-keywords
npm http 200 http://192.168.1.100:4873/ajv
npm http fetch GET http://192.168.1.100:4873/ajv/-/ajv-4.11.5.tgz
npm http fetch 200 http://192.168.1.100:4873/ajv/-/ajv-4.11.5.tgz
npm http request GET http://192.168.1.100:4873/co
npm http 200 http://192.168.1.100:4873/co
npm http request GET http://192.168.1.100:4873/os-homedir
npm http 304 http://192.168.1.100:4873/os-homedir
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/js2xmlparser
npm http request GET http://192.168.1.100:4873/catharsis
npm http request GET http://192.168.1.100:4873/marked
npm http request GET http://192.168.1.100:4873/underscore
npm http request GET http://192.168.1.100:4873/requizzle
npm http request GET http://192.168.1.100:4873/wrench
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 304 http://192.168.1.100:4873/catharsis
npm http 304 http://192.168.1.100:4873/async
npm http 200 http://192.168.1.100:4873/marked
npm http 200 http://192.168.1.100:4873/js2xmlparser
npm http 200 http://192.168.1.100:4873/underscore
npm http 304 http://192.168.1.100:4873/wrench
npm http 200 http://192.168.1.100:4873/requizzle
npm WARN deprecated wrench@1.5.9: wrench.js is deprecated! You should check out fs-extra (https://github.com/jprichardson/node-fs-extra) for any operations you were using wrench for. Thanks for all the usage over the years.
npm http fetch 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http request GET http://192.168.1.100:4873/underscore-contrib
npm http 200 http://192.168.1.100:4873/underscore-contrib
npm WARN prefer global marked@0.3.6 should be installed with -g
npm WARN install@0.0.1 No repository field.
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/child-process-promise
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/bn.js
npm http request GET http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/express-pouchdb
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/leveldown-mobile
npm http request GET http://192.168.1.100:4873/nock
npm http request GET http://192.168.1.100:4873/pouchdb
npm http request GET http://192.168.1.100:4873/pouchdb-size
npm http request GET http://192.168.1.100:4873/proxyquire
npm http request GET http://192.168.1.100:4873/request-promise
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/stacky
npm http request GET http://192.168.1.100:4873/supertest
npm http request GET http://192.168.1.100:4873/supertest-as-promised
npm http request GET http://192.168.1.100:4873/sinon
npm http request GET http://192.168.1.100:4873/tape-catch
npm http request GET http://192.168.1.100:4873/tape
npm http request GET http://192.168.1.100:4873/tmp
npm http request GET http://192.168.1.100:4873/uuid-validate
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/child-process-promise
npm http 304 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/minimist
npm http 304 http://192.168.1.100:4873/multiplex
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/randomstring
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/socket.io-client
npm http 304 http://192.168.1.100:4873/js-extend
npm http 304 http://192.168.1.100:4873/leveldown-mobile
npm http 200 http://192.168.1.100:4873/bn.js
npm http 200 http://192.168.1.100:4873/express-pouchdb
npm http 304 http://192.168.1.100:4873/pouchdb-size
npm http 304 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/proxyquire
npm http 304 http://192.168.1.100:4873/uuid
npm http 304 http://192.168.1.100:4873/stacky
npm http 304 http://192.168.1.100:4873/supertest-as-promised
npm http 200 http://192.168.1.100:4873/request-promise
npm http 200 http://192.168.1.100:4873/supertest
npm http 304 http://192.168.1.100:4873/tape-catch
npm http 304 http://192.168.1.100:4873/uuid-validate
npm http 200 http://192.168.1.100:4873/pouchdb
npm http 200 http://192.168.1.100:4873/tmp
npm http 200 http://192.168.1.100:4873/tape
npm http 200 http://192.168.1.100:4873/sinon
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
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/iconv-lite
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
npm http request GET http://192.168.1.100:4873/proxy-addr
npm http request GET http://192.168.1.100:4873/range-parser
npm http request GET http://192.168.1.100:4873/send
npm http request GET http://192.168.1.100:4873/path-to-regexp
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
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/send
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/serve-static
npm http 304 http://192.168.1.100:4873/utils-merge
npm http 304 http://192.168.1.100:4873/vary
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
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/compression
npm http request GET http://192.168.1.100:4873/cookie-parser
npm http request GET http://192.168.1.100:4873/header-case-normalizer
npm http request GET http://192.168.1.100:4873/multiparty
npm http request GET http://192.168.1.100:4873/pouchdb-all-dbs
npm http request GET http://192.168.1.100:4873/pouchdb-auth
npm http request GET http://192.168.1.100:4873/pouchdb-find
npm http request GET http://192.168.1.100:4873/pouchdb-list
npm http request GET http://192.168.1.100:4873/pouchdb-replicator
npm http request GET http://192.168.1.100:4873/pouchdb-security
npm http request GET http://192.168.1.100:4873/pouchdb-rewrite
npm http request GET http://192.168.1.100:4873/pouchdb-show
npm http request GET http://192.168.1.100:4873/pouchdb-update
npm http request GET http://192.168.1.100:4873/pouchdb-validation
npm http request GET http://192.168.1.100:4873/pouchdb-vhost
npm http request GET http://192.168.1.100:4873/pouchdb-wrappers
npm http 304 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/cookie-parser
npm http 304 http://192.168.1.100:4873/header-case-normalizer
npm http 200 http://192.168.1.100:4873/basic-auth
npm http 200 http://192.168.1.100:4873/compression
npm http 304 http://192.168.1.100:4873/pouchdb-all-dbs
npm http 200 http://192.168.1.100:4873/multiparty
npm http 304 http://192.168.1.100:4873/pouchdb-find
npm http 304 http://192.168.1.100:4873/pouchdb-auth
npm http 304 http://192.168.1.100:4873/pouchdb-list
npm http 304 http://192.168.1.100:4873/pouchdb-rewrite
npm http 304 http://192.168.1.100:4873/pouchdb-show
npm http 200 http://192.168.1.100:4873/pouchdb-replicator
npm http 304 http://192.168.1.100:4873/pouchdb-update
npm http 200 http://192.168.1.100:4873/pouchdb-security
npm http 304 http://192.168.1.100:4873/pouchdb-validation
npm http 304 http://192.168.1.100:4873/pouchdb-vhost
npm http 304 http://192.168.1.100:4873/pouchdb-wrappers
npm http request GET http://192.168.1.100:4873/setprototypeof
npm http 200 http://192.168.1.100:4873/setprototypeof
npm http request GET http://192.168.1.100:4873/compressible
npm http request GET http://192.168.1.100:4873/on-headers
npm http fetch GET http://192.168.1.100:4873/vary/-/vary-1.1.1.tgz
npm http fetch 200 http://192.168.1.100:4873/vary/-/vary-1.1.1.tgz
npm http 200 http://192.168.1.100:4873/on-headers
npm http 200 http://192.168.1.100:4873/compressible
npm http fetch GET http://192.168.1.100:4873/compressible/-/compressible-2.0.10.tgz
npm http fetch 200 http://192.168.1.100:4873/compressible/-/compressible-2.0.10.tgz
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/stream-counter
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/stream-counter
npm http request GET http://192.168.1.100:4873/argsarray
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/tiny-queue
npm http 304 http://192.168.1.100:4873/argsarray
npm http 304 http://192.168.1.100:4873/es3ify
npm http 304 http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/tiny-queue
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/base64url
npm http request GET http://192.168.1.100:4873/couchdb-calculate-session-id
npm http request GET http://192.168.1.100:4873/crypto-lite
npm http request GET http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http request GET http://192.168.1.100:4873/pouchdb-plugin-error
npm http request GET http://192.168.1.100:4873/pouchdb-req-http-query
npm http request GET http://192.168.1.100:4873/pouchdb-system-db
npm http request GET http://192.168.1.100:4873/promise-nodify
npm http request GET http://192.168.1.100:4873/secure-random
npm http 200 http://192.168.1.100:4873/base64url
npm http 304 http://192.168.1.100:4873/crypto-lite
npm http 304 http://192.168.1.100:4873/pouchdb-plugin-error
npm http 304 http://192.168.1.100:4873/couchdb-calculate-session-id
npm http 304 http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http 304 http://192.168.1.100:4873/pouchdb-req-http-query
npm http 304 http://192.168.1.100:4873/promise-nodify
npm http 304 http://192.168.1.100:4873/pouchdb-system-db
npm http 304 http://192.168.1.100:4873/secure-random
npm http request GET http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/meow
npm http 304 http://192.168.1.100:4873/concat-stream
npm http 200 http://192.168.1.100:4873/meow
npm http request GET http://192.168.1.100:4873/typedarray
npm http 304 http://192.168.1.100:4873/typedarray
npm http request GET http://192.168.1.100:4873/camelcase-keys
npm http request GET http://192.168.1.100:4873/indent-string
npm http 304 http://192.168.1.100:4873/indent-string
npm http 200 http://192.168.1.100:4873/camelcase-keys
npm http request GET http://192.168.1.100:4873/camelcase
npm http request GET http://192.168.1.100:4873/map-obj
npm http 304 http://192.168.1.100:4873/map-obj
npm http 200 http://192.168.1.100:4873/camelcase
npm http request GET http://192.168.1.100:4873/get-stdin
npm http request GET http://192.168.1.100:4873/repeating
npm http 304 http://192.168.1.100:4873/get-stdin
npm http 200 http://192.168.1.100:4873/repeating
npm http request GET http://192.168.1.100:4873/is-finite
npm http 304 http://192.168.1.100:4873/is-finite
npm http request GET http://192.168.1.100:4873/number-is-nan
npm http 304 http://192.168.1.100:4873/number-is-nan
npm http request GET http://192.168.1.100:4873/aproba
npm http 304 http://192.168.1.100:4873/aproba
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/vuvuzela
npm http request GET http://192.168.1.100:4873/level-write-stream
npm http request GET http://192.168.1.100:4873/es6-promise-pool
npm http request GET http://192.168.1.100:4873/fruitdown
npm http request GET http://192.168.1.100:4873/localstorage-down
npm http request GET http://192.168.1.100:4873/memdown
npm http request GET http://192.168.1.100:4873/pouchdb-collate
npm http request GET http://192.168.1.100:4873/scope-eval
npm http 304 http://192.168.1.100:4873/double-ended-queue
npm http 304 http://192.168.1.100:4873/levelup
npm http 304 http://192.168.1.100:4873/spark-md5
npm http 304 http://192.168.1.100:4873/pouchdb-collections
npm http 304 http://192.168.1.100:4873/through2
npm http 304 http://192.168.1.100:4873/vuvuzela
npm http 304 http://192.168.1.100:4873/level-write-stream
npm http 304 http://192.168.1.100:4873/memdown
npm http 304 http://192.168.1.100:4873/pouchdb-collate
npm http 304 http://192.168.1.100:4873/scope-eval
npm http 304 http://192.168.1.100:4873/sublevel-pouchdb
npm http 200 http://192.168.1.100:4873/es6-promise-pool
npm http 304 http://192.168.1.100:4873/fruitdown
npm http 304 http://192.168.1.100:4873/localstorage-down
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/d64
npm http 304 http://192.168.1.100:4873/abstract-leveldown
npm http 304 http://192.168.1.100:4873/d64
npm http request GET http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/end-stream
npm http 304 http://192.168.1.100:4873/end-stream
npm http request GET http://192.168.1.100:4873/write-stream
npm http 304 http://192.168.1.100:4873/write-stream
npm http request GET http://192.168.1.100:4873/deferred-leveldown
npm http request GET http://192.168.1.100:4873/level-codec
npm http request GET http://192.168.1.100:4873/level-errors
npm http request GET http://192.168.1.100:4873/level-iterator-stream
npm http request GET http://192.168.1.100:4873/prr
npm http request GET http://192.168.1.100:4873/semver
npm http 304 http://192.168.1.100:4873/deferred-leveldown
npm http 304 http://192.168.1.100:4873/level-codec
npm http 304 http://192.168.1.100:4873/prr
npm http 304 http://192.168.1.100:4873/level-errors
npm http 304 http://192.168.1.100:4873/level-iterator-stream
npm http 304 http://192.168.1.100:4873/semver
npm http request GET http://192.168.1.100:4873/errno
npm http 304 http://192.168.1.100:4873/errno
npm http request GET http://192.168.1.100:4873/humble-localstorage
npm http 304 http://192.168.1.100:4873/humble-localstorage
npm http request GET http://192.168.1.100:4873/localstorage-memory
npm http request GET http://192.168.1.100:4873/has-localstorage
npm http 304 http://192.168.1.100:4873/localstorage-memory
npm http 304 http://192.168.1.100:4873/has-localstorage
npm http request GET http://192.168.1.100:4873/ltgt
npm http request GET http://192.168.1.100:4873/functional-red-black-tree
npm http 304 http://192.168.1.100:4873/ltgt
npm http 304 http://192.168.1.100:4873/functional-red-black-tree
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
npm http fetch GET http://192.168.1.100:4873/qs/-/qs-6.1.2.tgz
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/aws4
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/is-typedarray
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/stringstream
npm http fetch 200 http://192.168.1.100:4873/qs/-/qs-6.1.2.tgz
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm WARN deprecated tough-cookie@2.2.2: ReDoS vulnerability parsing Set-Cookie https://nodesecurity.io/advisories/130
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
npm http 304 http://192.168.1.100:4873/chalk
npm http 304 http://192.168.1.100:4873/pinkie-promise
npm http 304 http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/ansi-styles
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
npm http 304 http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/boom
npm http 304 http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/jsprim
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/sshpk
npm http 304 http://192.168.1.100:4873/jsprim
npm http 304 http://192.168.1.100:4873/assert-plus
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
npm http 304 http://192.168.1.100:4873/dashdash
npm http 304 http://192.168.1.100:4873/getpass
npm http request GET http://192.168.1.100:4873/pull-stream
npm http 304 http://192.168.1.100:4873/pull-stream
npm http request GET http://192.168.1.100:4873/pull-core
npm http 304 http://192.168.1.100:4873/pull-core
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/lie
npm http 304 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/xmlhttprequest-cookie
npm http 304 http://192.168.1.100:4873/xmlhttprequest-cookie
npm http request GET http://192.168.1.100:4873/xmlhttprequest
npm http 304 http://192.168.1.100:4873/xmlhttprequest
npm http request GET http://192.168.1.100:4873/pouchdb-changeslike-wrapper
npm http 304 http://192.168.1.100:4873/pouchdb-changeslike-wrapper
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/couchdb-eval
npm http request GET http://192.168.1.100:4873/random-uuid-v4
npm http request GET http://192.168.1.100:4873/couchdb-objects
npm http 304 http://192.168.1.100:4873/couchdb-objects
npm http 304 http://192.168.1.100:4873/random-uuid-v4
npm http 304 http://192.168.1.100:4873/couchdb-eval
npm http request GET http://192.168.1.100:4873/is-empty
npm http 304 http://192.168.1.100:4873/is-empty
npm http request GET http://192.168.1.100:4873/is-array
npm http request GET http://192.168.1.100:4873/pouchdb-extend
npm http request GET http://192.168.1.100:4873/pouchdb-upsert
npm http 304 http://192.168.1.100:4873/is-array
npm http 304 http://192.168.1.100:4873/pouchdb-extend
npm http 200 http://192.168.1.100:4873/pouchdb-upsert
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 304 http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/recast
npm http request GET http://192.168.1.100:4873/ast-types
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/ast-types
npm http 304 http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/couchdb-render
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/couchdb-render
npm http request GET http://192.168.1.100:4873/couchdb-resp-completer
npm http 304 http://192.168.1.100:4873/couchdb-resp-completer
npm http request GET http://192.168.1.100:4873/equals
npm http 304 http://192.168.1.100:4873/equals
npm http request GET http://192.168.1.100:4873/jkroso-type
npm http 304 http://192.168.1.100:4873/jkroso-type
npm http request GET http://192.168.1.100:4873/pouchdb-route
npm http 304 http://192.168.1.100:4873/pouchdb-route
npm http request GET http://192.168.1.100:4873/get-folder-size
npm http 304 http://192.168.1.100:4873/get-folder-size
npm http request GET http://192.168.1.100:4873/minimist
npm http 304 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/fast-future
npm http 304 http://192.168.1.100:4873/bindings
npm http 304 http://192.168.1.100:4873/fast-future
npm http 304 http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/duplexify
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/stream-shift
npm http 304 http://192.168.1.100:4873/end-of-stream
npm http 304 http://192.168.1.100:4873/stream-shift
npm http request GET http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http 304 http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/debug
npm WARN deprecated lodash@2.4.1: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
npm http request GET http://192.168.1.100:4873/chai
npm http request GET http://192.168.1.100:4873/propagate
npm http request GET http://192.168.1.100:4873/deep-equal
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/propagate
npm http 200 http://192.168.1.100:4873/deep-equal
npm http 200 http://192.168.1.100:4873/chai
npm http request GET http://192.168.1.100:4873/assertion-error
npm http request GET http://192.168.1.100:4873/deep-eql
npm http request GET http://192.168.1.100:4873/type-detect
npm http 304 http://192.168.1.100:4873/assertion-error
npm http 304 http://192.168.1.100:4873/type-detect
npm http 200 http://192.168.1.100:4873/deep-eql
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/ip
npm http 304 http://192.168.1.100:4873/ip
npm http fetch GET http://192.168.1.100:4873/ip/-/ip-1.1.5.tgz
npm http fetch 200 http://192.168.1.100:4873/ip/-/ip-1.1.5.tgz
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
npm http 304 http://192.168.1.100:4873/double-ended-queue
npm http 304 http://192.168.1.100:4873/clone-buffer
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/level-codec
npm http 304 http://192.168.1.100:4873/levelup
npm http 304 http://192.168.1.100:4873/ltgt
npm http 304 http://192.168.1.100:4873/spark-md5
npm http 304 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/leveldown
npm http request GET http://192.168.1.100:4873/is-array-buffer-x
npm http 304 http://192.168.1.100:4873/is-array-buffer-x
npm http request GET http://192.168.1.100:4873/is-object-like-x
npm http request GET http://192.168.1.100:4873/to-string-tag-x
npm http request GET http://192.168.1.100:4873/has-to-string-tag-x
npm http 304 http://192.168.1.100:4873/to-string-tag-x
npm http 304 http://192.168.1.100:4873/is-object-like-x
npm http 304 http://192.168.1.100:4873/has-to-string-tag-x
npm http request GET http://192.168.1.100:4873/has-symbol-support-x
npm http 304 http://192.168.1.100:4873/has-symbol-support-x
npm http request GET http://192.168.1.100:4873/is-function-x
npm http request GET http://192.168.1.100:4873/is-primitive
npm http 304 http://192.168.1.100:4873/is-primitive
npm http 304 http://192.168.1.100:4873/is-function-x
npm http request GET http://192.168.1.100:4873/lodash.isnull
npm http request GET http://192.168.1.100:4873/validate.io-undefined
npm http 304 http://192.168.1.100:4873/lodash.isnull
npm http 304 http://192.168.1.100:4873/validate.io-undefined
npm http request GET http://192.168.1.100:4873/nan
npm http request GET http://192.168.1.100:4873/prebuild
npm http 200 http://192.168.1.100:4873/nan
npm http 200 http://192.168.1.100:4873/prebuild
npm http request GET http://192.168.1.100:4873/execspawn
npm http request GET http://192.168.1.100:4873/os-homedir
npm http request GET http://192.168.1.100:4873/expand-template
npm http request GET http://192.168.1.100:4873/ghreleases
npm http request GET http://192.168.1.100:4873/github-from-package
npm http request GET http://192.168.1.100:4873/node-ninja
npm http request GET http://192.168.1.100:4873/noop-logger
npm http request GET http://192.168.1.100:4873/npmlog
npm http request GET http://192.168.1.100:4873/node-gyp
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/rc
npm http request GET http://192.168.1.100:4873/pump
npm http request GET http://192.168.1.100:4873/simple-get
npm http request GET http://192.168.1.100:4873/tar-fs
npm http request GET http://192.168.1.100:4873/tar-stream
npm http 304 http://192.168.1.100:4873/execspawn
npm http 304 http://192.168.1.100:4873/os-homedir
npm http 304 http://192.168.1.100:4873/expand-template
npm http 304 http://192.168.1.100:4873/github-from-package
npm http 304 http://192.168.1.100:4873/ghreleases
npm http 304 http://192.168.1.100:4873/node-ninja
npm http 304 http://192.168.1.100:4873/noop-logger
npm http 304 http://192.168.1.100:4873/npmlog
npm http 304 http://192.168.1.100:4873/async
npm http 200 http://192.168.1.100:4873/rc
npm http 304 http://192.168.1.100:4873/tar-stream
npm http 200 http://192.168.1.100:4873/node-gyp
npm http 200 http://192.168.1.100:4873/pump
npm http 200 http://192.168.1.100:4873/simple-get
npm http 200 http://192.168.1.100:4873/tar-fs
npm http fetch GET http://192.168.1.100:4873/rc/-/rc-1.2.1.tgz
npm http fetch 200 http://192.168.1.100:4873/rc/-/rc-1.2.1.tgz
npm http fetch GET http://192.168.1.100:4873/node-gyp/-/node-gyp-3.6.0.tgz
npm http fetch 200 http://192.168.1.100:4873/node-gyp/-/node-gyp-3.6.0.tgz
npm http fetch GET http://192.168.1.100:4873/tar-fs/-/tar-fs-1.15.2.tgz
npm http fetch 200 http://192.168.1.100:4873/tar-fs/-/tar-fs-1.15.2.tgz
npm http request GET http://192.168.1.100:4873/util-extend
npm http 304 http://192.168.1.100:4873/util-extend
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/ghrepos
npm http request GET http://192.168.1.100:4873/simple-mime
npm http request GET http://192.168.1.100:4873/ghutils
npm http request GET http://192.168.1.100:4873/url-template
npm http 304 http://192.168.1.100:4873/ghrepos
npm http 304 http://192.168.1.100:4873/after
npm http 304 http://192.168.1.100:4873/simple-mime
npm http 304 http://192.168.1.100:4873/url-template
npm http 304 http://192.168.1.100:4873/ghutils
npm http request GET http://192.168.1.100:4873/jsonist
npm http 304 http://192.168.1.100:4873/jsonist
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/hyperquest
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/hyperquest
npm http request GET http://192.168.1.100:4873/duplexer2
npm http 304 http://192.168.1.100:4873/duplexer2
npm http request GET http://192.168.1.100:4873/fstream
npm http request GET http://192.168.1.100:4873/semver
npm http request GET http://192.168.1.100:4873/nopt
npm http request GET http://192.168.1.100:4873/osenv
npm http request GET http://192.168.1.100:4873/tar
npm http request GET http://192.168.1.100:4873/which
npm http 304 http://192.168.1.100:4873/fstream
npm http 304 http://192.168.1.100:4873/semver
npm http 304 http://192.168.1.100:4873/nopt
npm http 304 http://192.168.1.100:4873/tar
npm http 200 http://192.168.1.100:4873/osenv
npm http fetch GET http://192.168.1.100:4873/fstream/-/fstream-1.0.11.tgz
npm http fetch 200 http://192.168.1.100:4873/fstream/-/fstream-1.0.11.tgz
npm http 200 http://192.168.1.100:4873/which
npm http fetch GET http://192.168.1.100:4873/which/-/which-1.2.14.tgz
npm http fetch 200 http://192.168.1.100:4873/which/-/which-1.2.14.tgz
npm http request GET http://192.168.1.100:4873/abbrev
npm http 200 http://192.168.1.100:4873/abbrev
npm http request GET http://192.168.1.100:4873/are-we-there-yet
npm http request GET http://192.168.1.100:4873/ansi
npm http request GET http://192.168.1.100:4873/gauge
npm http 304 http://192.168.1.100:4873/are-we-there-yet
npm http 304 http://192.168.1.100:4873/ansi
npm http 304 http://192.168.1.100:4873/gauge
npm http request GET http://192.168.1.100:4873/delegates
npm http 200 http://192.168.1.100:4873/delegates
npm http request GET http://192.168.1.100:4873/has-unicode
npm http request GET http://192.168.1.100:4873/lodash.pad
npm http request GET http://192.168.1.100:4873/lodash.padend
npm http request GET http://192.168.1.100:4873/lodash.padstart
npm http 304 http://192.168.1.100:4873/has-unicode
npm http 304 http://192.168.1.100:4873/lodash.pad
npm http 304 http://192.168.1.100:4873/lodash.padstart
npm http 304 http://192.168.1.100:4873/lodash.padend
npm http request GET http://192.168.1.100:4873/os-tmpdir
npm http 304 http://192.168.1.100:4873/os-tmpdir
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 304 http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/block-stream
npm http 304 http://192.168.1.100:4873/block-stream
npm http request GET http://192.168.1.100:4873/isexe
npm http 200 http://192.168.1.100:4873/isexe
npm http fetch GET http://192.168.1.100:4873/isexe/-/isexe-2.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/isexe/-/isexe-2.0.0.tgz
npm http request GET http://192.168.1.100:4873/path-array
npm http 304 http://192.168.1.100:4873/path-array
npm http request GET http://192.168.1.100:4873/array-index
npm http 304 http://192.168.1.100:4873/array-index
npm http request GET http://192.168.1.100:4873/es6-symbol
npm http 304 http://192.168.1.100:4873/es6-symbol
npm http request GET http://192.168.1.100:4873/d
npm http request GET http://192.168.1.100:4873/es5-ext
npm http 304 http://192.168.1.100:4873/d
npm http 304 http://192.168.1.100:4873/es5-ext
npm http request GET http://192.168.1.100:4873/es6-iterator
npm http 304 http://192.168.1.100:4873/es6-iterator
npm http fetch GET http://192.168.1.100:4873/end-of-stream/-/end-of-stream-1.4.0.tgz
npm http fetch 200 http://192.168.1.100:4873/end-of-stream/-/end-of-stream-1.4.0.tgz
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/ini
npm http request GET http://192.168.1.100:4873/deep-extend
npm http 304 http://192.168.1.100:4873/strip-json-comments
npm http 304 http://192.168.1.100:4873/deep-extend
npm http 200 http://192.168.1.100:4873/ini
npm http request GET http://192.168.1.100:4873/unzip-response
npm http 200 http://192.168.1.100:4873/unzip-response
npm http request GET http://192.168.1.100:4873/chownr
npm http 304 http://192.168.1.100:4873/chownr
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/uuid
npm http fetch GET http://192.168.1.100:4873/qs/-/qs-6.3.2.tgz
npm http fetch 200 http://192.168.1.100:4873/qs/-/qs-6.3.2.tgz
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/asynckit
npm http 304 http://192.168.1.100:4873/asynckit
npm http request GET http://192.168.1.100:4873/punycode
npm http 304 http://192.168.1.100:4873/punycode
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/fill-keys
npm http request GET http://192.168.1.100:4873/module-not-found-error
npm http 304 http://192.168.1.100:4873/module-not-found-error
npm http 304 http://192.168.1.100:4873/fill-keys
npm http request GET http://192.168.1.100:4873/is-object
npm http 304 http://192.168.1.100:4873/is-object
npm http request GET http://192.168.1.100:4873/array-uniq
npm http 304 http://192.168.1.100:4873/array-uniq
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/jsonschema
npm http 304 http://192.168.1.100:4873/jsonschema
npm http request GET http://192.168.1.100:4873/util
npm http request GET http://192.168.1.100:4873/formatio
npm http request GET http://192.168.1.100:4873/lolex
npm http request GET http://192.168.1.100:4873/samsam
npm http 304 http://192.168.1.100:4873/formatio
npm http 200 http://192.168.1.100:4873/util
npm http 304 http://192.168.1.100:4873/lolex
npm http 304 http://192.168.1.100:4873/samsam
npm http request GET http://192.168.1.100:4873/component-bind
npm http request GET http://192.168.1.100:4873/engine.io-client
npm http request GET http://192.168.1.100:4873/component-emitter
npm http request GET http://192.168.1.100:4873/object-component
npm http request GET http://192.168.1.100:4873/socket.io-parser
npm http request GET http://192.168.1.100:4873/has-binary
npm http request GET http://192.168.1.100:4873/indexof
npm http request GET http://192.168.1.100:4873/parseuri
npm http request GET http://192.168.1.100:4873/to-array
npm http request GET http://192.168.1.100:4873/backo2
npm http 304 http://192.168.1.100:4873/engine.io-client
npm http 304 http://192.168.1.100:4873/component-bind
npm http 304 http://192.168.1.100:4873/component-emitter
npm http 304 http://192.168.1.100:4873/object-component
npm http 304 http://192.168.1.100:4873/socket.io-parser
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
npm http 304 http://192.168.1.100:4873/base64-arraybuffer
npm http 304 http://192.168.1.100:4873/blob
npm http 304 http://192.168.1.100:4873/utf8
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
npm http request GET http://192.168.1.100:4873/formidable
npm http request GET http://192.168.1.100:4873/cookiejar
npm http request GET http://192.168.1.100:4873/reduce-component
npm http request GET http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/cookiejar
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/reduce-component
npm http 200 http://192.168.1.100:4873/formidable
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/mime-db
npm http 304 http://192.168.1.100:4873/mime-db
npm http request GET http://192.168.1.100:4873/defined
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/object-inspect
npm http request GET http://192.168.1.100:4873/resumer
npm http 304 http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/defined
npm http 304 http://192.168.1.100:4873/resumer
npm http 200 http://192.168.1.100:4873/object-inspect
npm WARN prefer global node-ninja@1.0.2 should be installed with -g
npm WARN prefer global node-gyp@3.6.0 should be installed with -g
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
clang: warning: libstdc++ is deprecated; move to libc++ with a minimum deployment target of OS X 10.9
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
clang: warning: libstdc++ is deprecated; move to libc++ with a minimum deployment target of OS X 10.9
npm WARN EPACKAGEJSON thali-cordova-plugin-jxcore@1.0.0 No repository field.
npm WARN install@0.0.1 No repository field.
npm WARN thali-test-server@0.0.1 No repository field.
npm WARN thali-test-server@0.0.1 No license field.
npm WARN SSDPReplacer@0.0.1 No repository field.
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/javascript-state-machine
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-leveldb-core
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/winston
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/ip
npm http 304 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/lie
npm http 304 http://192.168.1.100:4873/javascript-state-machine
npm http 304 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/multiplex
npm http 304 http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-leveldb-core
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/uuid
npm http 304 http://192.168.1.100:4873/urlsafe-base64
npm http 304 http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/raw-body
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/type-is
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/bytes
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/type-is
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
npm http 304 http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/media-typer
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
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/send
npm http 304 http://192.168.1.100:4873/serve-static
npm http 304 http://192.168.1.100:4873/utils-merge
npm http 304 http://192.168.1.100:4873/vary
npm http request GET http://192.168.1.100:4873/negotiator
npm http 304 http://192.168.1.100:4873/negotiator
npm http request GET http://192.168.1.100:4873/forwarded
npm http request GET http://192.168.1.100:4873/ipaddr.js
npm http 304 http://192.168.1.100:4873/forwarded
npm http 304 http://192.168.1.100:4873/ipaddr.js
npm http request GET http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/mime
npm http 304 http://192.168.1.100:4873/mime
npm http 304 http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/varint
npm http 304 http://192.168.1.100:4873/duplexify
npm http 304 http://192.168.1.100:4873/varint
npm http 304 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/stream-shift
npm http 304 http://192.168.1.100:4873/stream-shift
npm http 304 http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/buffer-shims
npm http 304 http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/argsarray
npm http request GET http://192.168.1.100:4873/buffer-from
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-utils
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/pouchdb-binary-utils
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/pouchdb-errors
npm http request GET http://192.168.1.100:4873/pouchdb-json
npm http request GET http://192.168.1.100:4873/pouchdb-md5
npm http request GET http://192.168.1.100:4873/pouchdb-merge
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/pouchdb-utils
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/through2
npm http 304 http://192.168.1.100:4873/argsarray
npm http 304 http://192.168.1.100:4873/buffer-from
npm http 304 http://192.168.1.100:4873/double-ended-queue
npm http 304 http://192.168.1.100:4873/levelup
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-utils
npm http 304 http://192.168.1.100:4873/pouchdb-binary-utils
npm http 304 http://192.168.1.100:4873/pouchdb-errors
npm http 304 http://192.168.1.100:4873/pouchdb-collections
npm http 304 http://192.168.1.100:4873/pouchdb-json
npm http 304 http://192.168.1.100:4873/pouchdb-md5
npm http 304 http://192.168.1.100:4873/pouchdb-merge
npm http 304 http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/pouchdb-utils
npm http 304 http://192.168.1.100:4873/sublevel-pouchdb
npm http 304 http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/is-array-buffer-x
npm http 304 http://192.168.1.100:4873/is-array-buffer-x
npm http request GET http://192.168.1.100:4873/to-string-tag-x
npm http request GET http://192.168.1.100:4873/is-object-like-x
npm http request GET http://192.168.1.100:4873/has-to-string-tag-x
npm http 304 http://192.168.1.100:4873/to-string-tag-x
npm http 304 http://192.168.1.100:4873/is-object-like-x
npm http 304 http://192.168.1.100:4873/has-to-string-tag-x
npm http request GET http://192.168.1.100:4873/has-symbol-support-x
npm http 304 http://192.168.1.100:4873/has-symbol-support-x
npm http request GET http://192.168.1.100:4873/is-function-x
npm http request GET http://192.168.1.100:4873/is-primitive
npm http 304 http://192.168.1.100:4873/is-primitive
npm http 304 http://192.168.1.100:4873/is-function-x
npm http request GET http://192.168.1.100:4873/lodash.isnull
npm http request GET http://192.168.1.100:4873/validate.io-undefined
npm http 304 http://192.168.1.100:4873/lodash.isnull
npm http 304 http://192.168.1.100:4873/validate.io-undefined
npm http request GET http://192.168.1.100:4873/deferred-leveldown
npm http request GET http://192.168.1.100:4873/level-errors
npm http request GET http://192.168.1.100:4873/level-iterator-stream
npm http request GET http://192.168.1.100:4873/prr
npm http request GET http://192.168.1.100:4873/level-codec
npm http request GET http://192.168.1.100:4873/semver
npm http 304 http://192.168.1.100:4873/level-errors
npm http 304 http://192.168.1.100:4873/deferred-leveldown
npm http 304 http://192.168.1.100:4873/prr
npm http 304 http://192.168.1.100:4873/level-codec
npm http 304 http://192.168.1.100:4873/level-iterator-stream
npm http 304 http://192.168.1.100:4873/semver
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http 304 http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/errno
npm http 304 http://192.168.1.100:4873/errno
npm http request GET http://192.168.1.100:4873/spark-md5
npm http 304 http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/clone-buffer
npm http 304 http://192.168.1.100:4873/clone-buffer
npm http request GET http://192.168.1.100:4873/vuvuzela
npm http 304 http://192.168.1.100:4873/vuvuzela
npm http request GET http://192.168.1.100:4873/ltgt
npm http 304 http://192.168.1.100:4873/ltgt
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/oauth-sign
npm WARN deprecated node-uuid@1.4.8: Use uuid module instead
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http 304 http://192.168.1.100:4873/chalk
npm http 304 http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/ansi-styles
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http 304 http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http request GET http://192.168.1.100:4873/generate-function
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/hoek
npm http 304 http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/cryptiles
npm http 304 http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 304 http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/punycode
npm http 304 http://192.168.1.100:4873/punycode
npm http request GET http://192.168.1.100:4873/jsonschema
npm http 304 http://192.168.1.100:4873/jsonschema
npm http request GET http://192.168.1.100:4873/colors
npm http request GET http://192.168.1.100:4873/cycle
npm http request GET http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/pkginfo
npm http request GET http://192.168.1.100:4873/stack-trace
npm http 304 http://192.168.1.100:4873/colors
npm http 304 http://192.168.1.100:4873/pkginfo
npm http 304 http://192.168.1.100:4873/eyes
npm http 304 http://192.168.1.100:4873/cycle
npm http 304 http://192.168.1.100:4873/stack-trace
npm WARN EPACKAGEJSON thali-cordova-plugin-jxcore@1.0.0 No repository field.
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/bn.js
npm http request GET http://192.168.1.100:4873/child-process-promise
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/express-pouchdb
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/leveldown-mobile
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/nock
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/pouchdb-size
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/pouchdb
npm http request GET http://192.168.1.100:4873/proxyquire
npm http request GET http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/request-promise
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/sinon
npm http request GET http://192.168.1.100:4873/stacky
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/supertest
npm http request GET http://192.168.1.100:4873/supertest-as-promised
npm http request GET http://192.168.1.100:4873/tape-catch
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/tape
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/tmp
npm http request GET http://192.168.1.100:4873/uuid-validate
npm http 304 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/bn.js
npm http 304 http://192.168.1.100:4873/child-process-promise
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/express-pouchdb
npm http 304 http://192.168.1.100:4873/leveldown-mobile
npm http 304 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/js-extend
npm http 304 http://192.168.1.100:4873/minimist
npm http 304 http://192.168.1.100:4873/multiplex
npm http 304 http://192.168.1.100:4873/nock
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/pouchdb-size
npm http 304 http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/pouchdb
npm http 304 http://192.168.1.100:4873/randomstring
npm http 304 http://192.168.1.100:4873/proxyquire
npm http 304 http://192.168.1.100:4873/request-promise
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/stacky
npm http 304 http://192.168.1.100:4873/sinon
npm http 304 http://192.168.1.100:4873/socket.io-client
npm http 304 http://192.168.1.100:4873/supertest
npm http 304 http://192.168.1.100:4873/supertest-as-promised
npm http 304 http://192.168.1.100:4873/tape-catch
npm http 304 http://192.168.1.100:4873/urlsafe-base64
npm http 304 http://192.168.1.100:4873/tape
npm http 304 http://192.168.1.100:4873/uuid
npm http 304 http://192.168.1.100:4873/tmp
npm http 304 http://192.168.1.100:4873/uuid-validate
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/basic-auth
npm http request GET http://192.168.1.100:4873/cookie-parser
npm http request GET http://192.168.1.100:4873/header-case-normalizer
npm http request GET http://192.168.1.100:4873/compression
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/multiparty
npm http request GET http://192.168.1.100:4873/pouchdb-all-dbs
npm http request GET http://192.168.1.100:4873/pouchdb-auth
npm http request GET http://192.168.1.100:4873/pouchdb-show
npm http request GET http://192.168.1.100:4873/pouchdb-list
npm http request GET http://192.168.1.100:4873/pouchdb-replicator
npm http request GET http://192.168.1.100:4873/pouchdb-rewrite
npm http request GET http://192.168.1.100:4873/pouchdb-security
npm http request GET http://192.168.1.100:4873/pouchdb-find
npm http request GET http://192.168.1.100:4873/pouchdb-update
npm http request GET http://192.168.1.100:4873/pouchdb-validation
npm http request GET http://192.168.1.100:4873/pouchdb-vhost
npm http request GET http://192.168.1.100:4873/pouchdb-wrappers
npm http 304 http://192.168.1.100:4873/basic-auth
npm http 304 http://192.168.1.100:4873/cookie-parser
npm http 304 http://192.168.1.100:4873/header-case-normalizer
npm http 304 http://192.168.1.100:4873/compression
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/multiparty
npm http 304 http://192.168.1.100:4873/pouchdb-all-dbs
npm http 304 http://192.168.1.100:4873/pouchdb-auth
npm http 304 http://192.168.1.100:4873/pouchdb-list
npm http 304 http://192.168.1.100:4873/pouchdb-show
npm http 304 http://192.168.1.100:4873/pouchdb-replicator
npm http 304 http://192.168.1.100:4873/pouchdb-rewrite
npm http 304 http://192.168.1.100:4873/pouchdb-security
npm http 304 http://192.168.1.100:4873/pouchdb-find
npm http 304 http://192.168.1.100:4873/pouchdb-update
npm http 304 http://192.168.1.100:4873/pouchdb-validation
npm http 304 http://192.168.1.100:4873/pouchdb-vhost
npm http 304 http://192.168.1.100:4873/pouchdb-wrappers
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/bytes
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/setprototypeof
npm http 304 http://192.168.1.100:4873/setprototypeof
npm http request GET http://192.168.1.100:4873/accepts
npm http request GET http://192.168.1.100:4873/vary
npm http request GET http://192.168.1.100:4873/on-headers
npm http request GET http://192.168.1.100:4873/compressible
npm http 304 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/on-headers
npm http 304 http://192.168.1.100:4873/vary
npm http 304 http://192.168.1.100:4873/compressible
npm http request GET http://192.168.1.100:4873/negotiator
npm http 304 http://192.168.1.100:4873/negotiator
npm http request GET http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/cookie
npm http request GET http://192.168.1.100:4873/stream-counter
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/stream-counter
npm http 304 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/tiny-queue
npm http 304 http://192.168.1.100:4873/es3ify
npm http 304 http://192.168.1.100:4873/tiny-queue
npm http 304 http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/base62
npm http 304 http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/base64url
npm http request GET http://192.168.1.100:4873/pouchdb-plugin-error
npm http request GET http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http request GET http://192.168.1.100:4873/couchdb-calculate-session-id
npm http request GET http://192.168.1.100:4873/pouchdb-req-http-query
npm http request GET http://192.168.1.100:4873/pouchdb-system-db
npm http request GET http://192.168.1.100:4873/crypto-lite
npm http request GET http://192.168.1.100:4873/promise-nodify
npm http request GET http://192.168.1.100:4873/secure-random
npm http fetch GET http://192.168.1.100:4873/pouchdb-promise/-/pouchdb-promise-5.4.5.tgz
npm http 304 http://192.168.1.100:4873/base64url
npm http 304 http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http 304 http://192.168.1.100:4873/pouchdb-req-http-query
npm http 304 http://192.168.1.100:4873/couchdb-calculate-session-id
npm http 304 http://192.168.1.100:4873/pouchdb-system-db
npm http fetch 200 http://192.168.1.100:4873/pouchdb-promise/-/pouchdb-promise-5.4.5.tgz
npm http 304 http://192.168.1.100:4873/crypto-lite
npm http 304 http://192.168.1.100:4873/secure-random
npm http 304 http://192.168.1.100:4873/promise-nodify
npm http 304 http://192.168.1.100:4873/pouchdb-plugin-error
npm http request GET http://192.168.1.100:4873/meow
npm http request GET http://192.168.1.100:4873/concat-stream
npm http 304 http://192.168.1.100:4873/meow
npm http 304 http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/typedarray
npm http 304 http://192.168.1.100:4873/typedarray
npm http request GET http://192.168.1.100:4873/camelcase-keys
npm http request GET http://192.168.1.100:4873/indent-string
npm http 304 http://192.168.1.100:4873/camelcase-keys
npm http 304 http://192.168.1.100:4873/indent-string
npm http request GET http://192.168.1.100:4873/map-obj
npm http request GET http://192.168.1.100:4873/camelcase
npm http 304 http://192.168.1.100:4873/map-obj
npm http 304 http://192.168.1.100:4873/camelcase
npm http request GET http://192.168.1.100:4873/get-stdin
npm http request GET http://192.168.1.100:4873/repeating
npm http 304 http://192.168.1.100:4873/get-stdin
npm http 304 http://192.168.1.100:4873/repeating
npm http request GET http://192.168.1.100:4873/is-finite
npm http 304 http://192.168.1.100:4873/is-finite
npm http request GET http://192.168.1.100:4873/number-is-nan
npm http 304 http://192.168.1.100:4873/number-is-nan
npm http request GET http://192.168.1.100:4873/aproba
npm http 304 http://192.168.1.100:4873/aproba
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/fruitdown
npm http request GET http://192.168.1.100:4873/es6-promise-pool
npm http request GET http://192.168.1.100:4873/level-write-stream
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/localstorage-down
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/memdown
npm http request GET http://192.168.1.100:4873/pouchdb-collate
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/scope-eval
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/through2
npm http 304 http://192.168.1.100:4873/double-ended-queue
npm http 304 http://192.168.1.100:4873/levelup
npm http 304 http://192.168.1.100:4873/js-extend
npm http 304 http://192.168.1.100:4873/fruitdown
npm http 304 http://192.168.1.100:4873/level-write-stream
npm http 304 http://192.168.1.100:4873/memdown
npm http 304 http://192.168.1.100:4873/localstorage-down
npm http 304 http://192.168.1.100:4873/pouchdb-collections
npm http 304 http://192.168.1.100:4873/es6-promise-pool
npm http 304 http://192.168.1.100:4873/scope-eval
npm http 304 http://192.168.1.100:4873/spark-md5
npm http 304 http://192.168.1.100:4873/sublevel-pouchdb
npm http 304 http://192.168.1.100:4873/through2
npm http 304 http://192.168.1.100:4873/pouchdb-collate
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/d64
npm http 304 http://192.168.1.100:4873/d64
npm http 304 http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/end-stream
npm http 304 http://192.168.1.100:4873/end-stream
npm http request GET http://192.168.1.100:4873/write-stream
npm http 304 http://192.168.1.100:4873/write-stream
npm http request GET http://192.168.1.100:4873/humble-localstorage
npm http 304 http://192.168.1.100:4873/humble-localstorage
npm http request GET http://192.168.1.100:4873/has-localstorage
npm http request GET http://192.168.1.100:4873/localstorage-memory
npm http 304 http://192.168.1.100:4873/has-localstorage
npm http 304 http://192.168.1.100:4873/localstorage-memory
npm http request GET http://192.168.1.100:4873/ltgt
npm http request GET http://192.168.1.100:4873/functional-red-black-tree
npm http 304 http://192.168.1.100:4873/ltgt
npm http 304 http://192.168.1.100:4873/functional-red-black-tree
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/aws4
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/is-typedarray
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/aws4
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/is-typedarray
npm http 304 http://192.168.1.100:4873/tough-cookie
npm WARN deprecated tough-cookie@2.2.2: ReDoS vulnerability parsing Set-Cookie https://nodesecurity.io/advisories/130
npm http request GET http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/pinkie-promise
npm http 304 http://192.168.1.100:4873/pinkie-promise
npm http request GET http://192.168.1.100:4873/pinkie
npm http 304 http://192.168.1.100:4873/pinkie
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
npm http 304 http://192.168.1.100:4873/verror
npm http 304 http://192.168.1.100:4873/json-schema
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/dashdash
npm http request GET http://192.168.1.100:4873/getpass
npm http 304 http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/dashdash
npm http 304 http://192.168.1.100:4873/getpass
npm http request GET http://192.168.1.100:4873/pull-stream
npm http 304 http://192.168.1.100:4873/pull-stream
npm http request GET http://192.168.1.100:4873/pull-core
npm http 304 http://192.168.1.100:4873/pull-core
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/lie
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/xmlhttprequest-cookie
npm http 304 http://192.168.1.100:4873/xmlhttprequest-cookie
npm http request GET http://192.168.1.100:4873/xmlhttprequest
npm http 304 http://192.168.1.100:4873/xmlhttprequest
npm http request GET http://192.168.1.100:4873/pouchdb-changeslike-wrapper
npm http 304 http://192.168.1.100:4873/pouchdb-changeslike-wrapper
npm http request GET http://192.168.1.100:4873/couchdb-objects
npm http request GET http://192.168.1.100:4873/couchdb-eval
npm http request GET http://192.168.1.100:4873/random-uuid-v4
npm http 304 http://192.168.1.100:4873/couchdb-eval
npm http 304 http://192.168.1.100:4873/couchdb-objects
npm http 304 http://192.168.1.100:4873/random-uuid-v4
npm http request GET http://192.168.1.100:4873/is-empty
npm http 304 http://192.168.1.100:4873/is-empty
npm http request GET http://192.168.1.100:4873/is-array
npm http request GET http://192.168.1.100:4873/pouchdb-extend
npm http request GET http://192.168.1.100:4873/pouchdb-upsert
npm http 304 http://192.168.1.100:4873/is-array
npm http 304 http://192.168.1.100:4873/pouchdb-extend
npm http 304 http://192.168.1.100:4873/pouchdb-upsert
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 304 http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/recast
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/ast-types
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/ast-types
npm http request GET http://192.168.1.100:4873/couchdb-render
npm http 304 http://192.168.1.100:4873/couchdb-render
npm http request GET http://192.168.1.100:4873/couchdb-resp-completer
npm http 304 http://192.168.1.100:4873/couchdb-resp-completer
npm http request GET http://192.168.1.100:4873/equals
npm http 304 http://192.168.1.100:4873/equals
npm http request GET http://192.168.1.100:4873/jkroso-type
npm http 304 http://192.168.1.100:4873/jkroso-type
npm http request GET http://192.168.1.100:4873/pouchdb-route
npm http 304 http://192.168.1.100:4873/pouchdb-route
npm http request GET http://192.168.1.100:4873/get-folder-size
npm http 304 http://192.168.1.100:4873/get-folder-size
npm http request GET http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/minimist
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/fast-future
npm http 304 http://192.168.1.100:4873/fast-future
npm http 304 http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/propagate
npm http request GET http://192.168.1.100:4873/chai
npm http request GET http://192.168.1.100:4873/deep-equal
npm http request GET http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/propagate
npm http 304 http://192.168.1.100:4873/deep-equal
npm http 304 http://192.168.1.100:4873/chai
npm http 304 http://192.168.1.100:4873/debug
npm WARN deprecated lodash@2.4.1: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
npm http request GET http://192.168.1.100:4873/assertion-error
npm http request GET http://192.168.1.100:4873/deep-eql
npm http request GET http://192.168.1.100:4873/type-detect
npm http 304 http://192.168.1.100:4873/assertion-error
npm http 304 http://192.168.1.100:4873/deep-eql
npm http 304 http://192.168.1.100:4873/type-detect
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/level-codec
npm http request GET http://192.168.1.100:4873/leveldown
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/level-codec
npm http 304 http://192.168.1.100:4873/leveldown
npm http request GET http://192.168.1.100:4873/nan
npm http request GET http://192.168.1.100:4873/prebuild
npm http 304 http://192.168.1.100:4873/nan
npm http 304 http://192.168.1.100:4873/prebuild
npm http request GET http://192.168.1.100:4873/execspawn
npm http request GET http://192.168.1.100:4873/expand-template
npm http request GET http://192.168.1.100:4873/github-from-package
npm http request GET http://192.168.1.100:4873/noop-logger
npm http request GET http://192.168.1.100:4873/node-ninja
npm http request GET http://192.168.1.100:4873/ghreleases
npm http request GET http://192.168.1.100:4873/npmlog
npm http request GET http://192.168.1.100:4873/os-homedir
npm http request GET http://192.168.1.100:4873/node-gyp
npm http request GET http://192.168.1.100:4873/pump
npm http request GET http://192.168.1.100:4873/rc
npm http request GET http://192.168.1.100:4873/simple-get
npm http request GET http://192.168.1.100:4873/tar-fs
npm http request GET http://192.168.1.100:4873/tar-stream
npm http 304 http://192.168.1.100:4873/execspawn
npm http 304 http://192.168.1.100:4873/github-from-package
npm http 304 http://192.168.1.100:4873/expand-template
npm http 304 http://192.168.1.100:4873/noop-logger
npm http 304 http://192.168.1.100:4873/node-ninja
npm http 304 http://192.168.1.100:4873/ghreleases
npm http 304 http://192.168.1.100:4873/npmlog
npm http 304 http://192.168.1.100:4873/os-homedir
npm http 304 http://192.168.1.100:4873/pump
npm http 304 http://192.168.1.100:4873/node-gyp
npm http 304 http://192.168.1.100:4873/rc
npm http 304 http://192.168.1.100:4873/simple-get
npm http 304 http://192.168.1.100:4873/tar-fs
npm http 304 http://192.168.1.100:4873/tar-stream
npm http request GET http://192.168.1.100:4873/util-extend
npm http 304 http://192.168.1.100:4873/util-extend
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/ghutils
npm http request GET http://192.168.1.100:4873/simple-mime
npm http request GET http://192.168.1.100:4873/ghrepos
npm http request GET http://192.168.1.100:4873/url-template
npm http 304 http://192.168.1.100:4873/after
npm http 304 http://192.168.1.100:4873/ghutils
npm http 304 http://192.168.1.100:4873/simple-mime
npm http 304 http://192.168.1.100:4873/url-template
npm http 304 http://192.168.1.100:4873/ghrepos
npm http request GET http://192.168.1.100:4873/jsonist
npm http 304 http://192.168.1.100:4873/jsonist
npm http request GET http://192.168.1.100:4873/hyperquest
npm http 304 http://192.168.1.100:4873/hyperquest
npm http request GET http://192.168.1.100:4873/duplexer2
npm http 304 http://192.168.1.100:4873/duplexer2
npm http request GET http://192.168.1.100:4873/fstream
npm http request GET http://192.168.1.100:4873/osenv
npm http request GET http://192.168.1.100:4873/nopt
npm http request GET http://192.168.1.100:4873/tar
npm http request GET http://192.168.1.100:4873/which
npm http request GET http://192.168.1.100:4873/semver
npm http 304 http://192.168.1.100:4873/fstream
npm http 304 http://192.168.1.100:4873/osenv
npm http 304 http://192.168.1.100:4873/nopt
npm http 304 http://192.168.1.100:4873/tar
npm http 304 http://192.168.1.100:4873/which
npm http 304 http://192.168.1.100:4873/semver
npm http request GET http://192.168.1.100:4873/abbrev
npm http 304 http://192.168.1.100:4873/abbrev
npm http request GET http://192.168.1.100:4873/ansi
npm http request GET http://192.168.1.100:4873/are-we-there-yet
npm http request GET http://192.168.1.100:4873/gauge
npm http 304 http://192.168.1.100:4873/ansi
npm http 304 http://192.168.1.100:4873/gauge
npm http 304 http://192.168.1.100:4873/are-we-there-yet
npm http request GET http://192.168.1.100:4873/delegates
npm http 304 http://192.168.1.100:4873/delegates
npm http request GET http://192.168.1.100:4873/has-unicode
npm http request GET http://192.168.1.100:4873/lodash.pad
npm http request GET http://192.168.1.100:4873/lodash.padend
npm http request GET http://192.168.1.100:4873/lodash.padstart
npm http 304 http://192.168.1.100:4873/has-unicode
npm http 304 http://192.168.1.100:4873/lodash.pad
npm http 304 http://192.168.1.100:4873/lodash.padend
npm http 304 http://192.168.1.100:4873/lodash.padstart
npm http request GET http://192.168.1.100:4873/os-tmpdir
npm http 304 http://192.168.1.100:4873/os-tmpdir
npm http request GET http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/block-stream
npm http 304 http://192.168.1.100:4873/block-stream
npm http request GET http://192.168.1.100:4873/isexe
npm http 304 http://192.168.1.100:4873/isexe
npm http request GET http://192.168.1.100:4873/path-array
npm http 304 http://192.168.1.100:4873/path-array
npm http request GET http://192.168.1.100:4873/array-index
npm http 304 http://192.168.1.100:4873/array-index
npm http request GET http://192.168.1.100:4873/es6-symbol
npm http 304 http://192.168.1.100:4873/es6-symbol
npm http request GET http://192.168.1.100:4873/d
npm http request GET http://192.168.1.100:4873/es5-ext
npm http 304 http://192.168.1.100:4873/es5-ext
npm http 304 http://192.168.1.100:4873/d
npm http request GET http://192.168.1.100:4873/es6-iterator
npm http 304 http://192.168.1.100:4873/es6-iterator
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http 304 http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/deep-extend
npm http request GET http://192.168.1.100:4873/ini
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http 304 http://192.168.1.100:4873/deep-extend
npm http 304 http://192.168.1.100:4873/strip-json-comments
npm http 304 http://192.168.1.100:4873/ini
npm http request GET http://192.168.1.100:4873/unzip-response
npm http 304 http://192.168.1.100:4873/unzip-response
npm http request GET http://192.168.1.100:4873/chownr
npm http 304 http://192.168.1.100:4873/chownr
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/asynckit
npm http 304 http://192.168.1.100:4873/asynckit
npm http request GET http://192.168.1.100:4873/fill-keys
npm http request GET http://192.168.1.100:4873/module-not-found-error
npm http 304 http://192.168.1.100:4873/fill-keys
npm http 304 http://192.168.1.100:4873/module-not-found-error
npm http request GET http://192.168.1.100:4873/is-object
npm http 304 http://192.168.1.100:4873/is-object
npm http request GET http://192.168.1.100:4873/array-uniq
npm http 304 http://192.168.1.100:4873/array-uniq
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/formatio
npm http request GET http://192.168.1.100:4873/util
npm http request GET http://192.168.1.100:4873/lolex
npm http request GET http://192.168.1.100:4873/samsam
npm http 304 http://192.168.1.100:4873/formatio
npm http 304 http://192.168.1.100:4873/util
npm http 304 http://192.168.1.100:4873/lolex
npm http 304 http://192.168.1.100:4873/samsam
npm http request GET http://192.168.1.100:4873/component-bind
npm http request GET http://192.168.1.100:4873/engine.io-client
npm http request GET http://192.168.1.100:4873/component-emitter
npm http request GET http://192.168.1.100:4873/object-component
npm http request GET http://192.168.1.100:4873/has-binary
npm http request GET http://192.168.1.100:4873/socket.io-parser
npm http request GET http://192.168.1.100:4873/indexof
npm http request GET http://192.168.1.100:4873/parseuri
npm http request GET http://192.168.1.100:4873/backo2
npm http request GET http://192.168.1.100:4873/to-array
npm http 304 http://192.168.1.100:4873/component-bind
npm http 304 http://192.168.1.100:4873/component-emitter
npm http 304 http://192.168.1.100:4873/engine.io-client
npm http 304 http://192.168.1.100:4873/object-component
npm http 304 http://192.168.1.100:4873/has-binary
npm http 304 http://192.168.1.100:4873/socket.io-parser
npm http 304 http://192.168.1.100:4873/indexof
npm http 304 http://192.168.1.100:4873/backo2
npm http 304 http://192.168.1.100:4873/parseuri
npm http 304 http://192.168.1.100:4873/to-array
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/xmlhttprequest-ssl
npm http request GET http://192.168.1.100:4873/ws
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/parseqs
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/yeast
npm http 304 http://192.168.1.100:4873/has-cors
npm http 304 http://192.168.1.100:4873/xmlhttprequest-ssl
npm http 304 http://192.168.1.100:4873/ws
npm http 304 http://192.168.1.100:4873/parsejson
npm http 304 http://192.168.1.100:4873/engine.io-parser
npm http 304 http://192.168.1.100:4873/parseqs
npm http 304 http://192.168.1.100:4873/component-inherit
npm http 304 http://192.168.1.100:4873/yeast
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/utf8
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/blob
npm http 304 http://192.168.1.100:4873/base64-arraybuffer
npm http 304 http://192.168.1.100:4873/utf8
npm http 304 http://192.168.1.100:4873/arraybuffer.slice
npm http 304 http://192.168.1.100:4873/blob
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
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/superagent
npm http 304 http://192.168.1.100:4873/superagent
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/formidable
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/cookiejar
npm http request GET http://192.168.1.100:4873/reduce-component
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/formidable
npm http 304 http://192.168.1.100:4873/cookiejar
npm http 304 http://192.168.1.100:4873/reduce-component
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/mime-types
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
npm http 304 http://192.168.1.100:4873/resumer
npm http 304 http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/object-inspect
npm WARN prefer global node-ninja@1.0.2 should be installed with -g
npm WARN prefer global node-gyp@3.6.0 should be installed with -g
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
clang: warning: libstdc++ is deprecated; move to libc++ with a minimum deployment target of OS X 10.9
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
clang: warning: libstdc++ is deprecated; move to libc++ with a minimum deployment target of OS X 10.9
npm WARN EPACKAGEJSON thali-cordova-plugin-jxcore@1.0.0 No repository field.
Note: Some input files use or override a deprecated API.
Note: Recompile with -Xlint:deprecation for details.
Note: Some input files use or override a deprecated API.
Note: Recompile with -Xlint:deprecation for details.
Note: Some input files use or override a deprecated API.
Note: Recompile with -Xlint:deprecation for details.
/Users/thali/Github/ThaliTest/platforms/android/assets/www/jxcore/node_modules/node-gyp/test/fixtures/server.key: Error: The fixtures/server.key file seems to be a private key file. Please make sure not to embed this in your APK file. [PackagedPrivateKey]
/Users/thali/Github/ThaliTest/platforms/android/assets/www/jxcore/node_modules/node-ninja/test/fixtures/server.key: Error: The fixtures/server.key file seems to be a private key file. Please make sure not to embed this in your APK file. [PackagedPrivateKey]

   Explanation for issues of type "PackagedPrivateKey":
   In general, you should not package private key files inside your app.

2 errors, 0 warnings
** BUILD FAILED **


The following build commands failed:
	CompileSwift normal arm64 /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/org.thaliproject.p2p/AppContext.swift
	CompileSwiftSources normal arm64 com.apple.xcode.tools.swift.compiler
(2 failures)
