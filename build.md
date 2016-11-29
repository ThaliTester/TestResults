#### Test (Fail) 95541073 Build Logs


```
Your branch is up-to-date with 'origin/master'.
Your branch is up-to-date with 'origin/master'.
Merge made by the 'recursive' strategy.
 build.sh                                           |  2 +-
 .../java/io/jxcore/node/IncomingSocketThread.java  | 16 ++++----
 .../java/io/jxcore/node/OutgoingSocketThread.java  | 15 ++++---
 .../java/io/jxcore/node/SocketThreadBase.java      | 46 +++++++++++++++++-----
 4 files changed, 54 insertions(+), 25 deletions(-)

Already on 'master'
Already on 'master'
Note: checking out '6d1bb28'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at 6d1bb28... Merge branch 'master' of github.com:thaliproject/Thali_CordovaPlugin into aaladev_1574

```

```
Cordova version:
6.4.0
Start setUpDesktop.sh
Setup TestServer
thali-test-server@0.0.1 /Users/thali/Github/Thali_CordovaPlugin/test/TestServer
├── bluebird@3.4.6 
├─┬ express@4.13.3 
│ ├─┬ accepts@1.2.13 
│ │ ├─┬ mime-types@2.1.13 
│ │ │ └── mime-db@1.25.0 
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

Install Thali Root
[33mPreparing NPM for JXcore (v0.3.1.7) for the first run[39m
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
├── js-extend@1.0.1 
│   A simple extend function based on underscore
│   git://github.com/vmattos/js-extend.git
│   https://github.com/vmattos/js-extend
├── jsdoc@3.3.3 
│   An API documentation generator for JavaScript.
│   git+https://github.com/jsdoc3/jsdoc.git
│   https://github.com/jsdoc3/jsdoc#readme
├── lie@3.0.4 
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
├── node-ssdp@2.6.5  (git+https://github.com/thaliproject/node-ssdp.git#caf1a75aa54fb47a9e51b72bf4c902c366536cbd)
│   A node.js SSDP client and server library.
│   git+ssh://git@github.com/diversario/node-ssdp.git
│   https://github.com/diversario/node-ssdp#readme
│   git+https://github.com/thaliproject/node-ssdp.git#caf1a75aa54fb47a9e51b72bf4c902c366536cbd
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
Install Thali Install Directory
install@0.0.1 /Users/thali/Github/Thali_CordovaPlugin/thali/install
├── bluebird@3.4.6 
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
├─┬ lie@3.0.4 
│ ├─┬ es3ify@0.2.2 
│ │ ├── esprima@2.7.3 
│ │ ├─┬ jstransform@11.0.3 
│ │ │ ├── base62@1.1.2 
│ │ │ ├─┬ commoner@0.10.8 
│ │ │ │ ├─┬ detective@4.3.2 
│ │ │ │ │ ├── acorn@3.3.0 
│ │ │ │ │ └── defined@1.0.0 
│ │ │ │ ├── glob@5.0.15 
│ │ │ │ ├── iconv-lite@0.4.15 
│ │ │ │ ├── q@1.4.1 
│ │ │ │ └─┬ recast@0.11.18 
│ │ │ │   ├── ast-types@0.9.2 
│ │ │ │   ├── esprima@3.1.2 
│ │ │ │   └── source-map@0.5.6 
│ │ │ ├── esprima-fb@15001.1.0-dev-harmony-fb 
│ │ │ ├── object-assign@2.1.1 
│ │ │ └─┬ source-map@0.4.4 
│ │ │   └── amdefine@1.0.1 
│ │ └── through@2.3.8 
│ ├── immediate@3.0.6 
│ ├─┬ inline-process-browser@1.0.0 
│ │ ├─┬ falafel@1.2.0 
│ │ │ ├── acorn@1.2.2 
│ │ │ ├── foreach@2.0.5 
│ │ │ └── object-keys@1.0.11 
│ │ └─┬ through2@0.6.5 
│ │   └── xtend@4.0.1 
│ └─┬ unreachable-branch-transform@0.3.0 
│   ├── esmangle-evaluator@1.0.1 
│   └─┬ recast@0.10.43 
│     ├── ast-types@0.8.15 
│     ├── esprima-fb@15001.1001.0-dev-harmony-fb 
│     ├── private@0.1.6 
│     └── source-map@0.5.6 
├── node-uuid@1.4.7 
├─┬ randomstring@1.1.5 
│ └── array-uniq@1.0.2 
├─┬ request@2.64.0 
│ ├── aws-sign2@0.5.0 
│ ├─┬ bl@1.0.3 
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
│ │   └── lodash@4.17.2 
│ ├─┬ har-validator@1.8.0 
│ │ ├── bluebird@2.11.0 
│ │ ├─┬ chalk@1.1.3 
│ │ │ ├── ansi-styles@2.2.1 
│ │ │ ├── escape-string-regexp@1.0.5 
│ │ │ ├─┬ has-ansi@2.0.0 
│ │ │ │ └── ansi-regex@2.0.0 
│ │ │ ├── strip-ansi@3.0.1 
│ │ │ └── supports-color@2.0.0 
│ │ ├─┬ commander@2.9.0 
│ │ │ └── graceful-readlink@1.0.1 
│ │ └─┬ is-my-json-valid@2.15.0 
│ │   ├── generate-function@2.0.0 
│ │   ├─┬ generate-object-property@1.2.0 
│ │   │ └── is-property@1.0.2 
│ │   └── jsonpointer@4.0.0 
│ ├─┬ hawk@3.1.3 
│ │ ├── boom@2.10.1 
│ │ ├── cryptiles@2.0.5 
│ │ ├── hoek@2.16.3 
│ │ └── sntp@1.0.9 
│ ├─┬ http-signature@0.11.0 
│ │ ├── asn1@0.1.11 
│ │ ├── assert-plus@0.1.5 
│ │ └── ctype@0.5.3 
│ ├── isstream@0.1.2 
│ ├── json-stringify-safe@5.0.1 
│ ├─┬ mime-types@2.1.13 
│ │ └── mime-db@1.25.0 
│ ├── oauth-sign@0.8.2 
│ ├── qs@5.1.0 
│ ├── stringstream@0.0.5 
│ ├─┬ tough-cookie@2.3.2 
│ │ └── punycode@1.4.1 
│ └── tunnel-agent@0.4.3 
└─┬ unzip@0.1.11 
  ├─┬ binary@0.3.0 
  │ ├── buffers@0.1.1 
  │ └─┬ chainsaw@0.1.0 
  │   └── traverse@0.3.9 
  ├─┬ fstream@0.1.31 
  │ ├─┬ graceful-fs@3.0.11 
  │ │ └── natives@1.1.0 
  │ ├── inherits@2.0.3 
  │ └─┬ mkdirp@0.5.1 
  │   └── minimist@0.0.8 
  ├── match-stream@0.0.2 
  ├─┬ pullstream@0.4.1 
  │ ├── over@0.0.5 
  │ └── slice-stream@1.0.0 
  ├─┬ readable-stream@1.0.34 
  │ ├── core-util-is@1.0.2 
  │ ├── isarray@0.0.1 
  │ └── string_decoder@0.10.31 
  └── setimmediate@1.0.5 

Final Desktop Step
/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/thali -> /usr/local/lib/node_modules/thali -> /Users/thali/Github/Thali_CordovaPlugin/thali

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
├── pouchdb@5.4.5 
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

End setUpDesktop.sh
2016-11-29 12:23:56 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
2016-11-29 12:23:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreateNativeListener.js'
2016-11-29 12:23:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js'
2016-11-29 12:23:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js'
2016-11-29 12:23:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
2016-11-29 12:23:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
2016-11-29 12:23:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testNativeMethod.js'
2016-11-29 12:23:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
2016-11-29 12:23:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBGenerator.js'
2016-11-29 12:23:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPromiseQueue.js'
2016-11-29 12:23:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testSSDPServer.js'
2016-11-29 12:23:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testTests.js'
2016-11-29 12:23:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManager.js'
2016-11-29 12:23:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
2016-11-29 12:23:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js'
2016-11-29 12:23:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNative.js'
2016-11-29 12:23:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
2016-11-29 12:23:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
2016-11-29 12:23:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotification.js'
2016-11-29 12:23:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationAction.js'
2016-11-29 12:23:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
2016-11-29 12:23:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationClient.js'
2016-11-29 12:23:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationLocal.js'
2016-11-29 12:23:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationServer.js'
2016-11-29 12:23:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerAction.js'
2016-11-29 12:23:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerDictionary.js'
2016-11-29 12:23:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
2016-11-29 12:23:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
2016-11-29 12:23:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
2016-11-29 12:23:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
2016-11-29 12:23:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
2016-11-29 12:23:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
2016-11-29 12:23:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
2016-11-29 12:23:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
2016-11-29 12:23:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
2016-11-29 12:23:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliTcpServersManager.js'
2016-11-29 12:23:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
2016-11-29 12:23:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-29 12:23:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-29 12:23:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:23:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-29 12:23:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
TAP version 13
# setup
# calling createNativeListener directly rejects
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'listening 49658'
ok 1 Should throw
# teardown
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Native Server - close'
# setup
# emits incomingConnectionState
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'listening 49660'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 2 initial connection state should be CONNECTED
2016-11-29 12:23:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 3 final connection state should be DISCONNECTED
# teardown
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Native Server - close'
# setup
# emits routerPortConnectionFailed
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'listening 49663'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
ok 4 tried to connect to right port
ok 5 failed due to refused connection
ok 6 routerPortConnectionFailed is emitted
# teardown
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# setup
# native server connections all up
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'listening 49667'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
ok 7 Send/recvd #1 should be equal length
ok 8 Send/recvd #1 should be same
ok 9 Send/recvd #2 should be equal length
ok 10 Send/recvd #2 should be same
ok 11 Should be exactly 2 client sockets
# teardown
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# setup
# native server - closing incoming stream cleans outgoing socket
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'listening 49672'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
ok 12 socket shouldn't close until after stream
ok 13 incoming remains open
# teardown
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# setup
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# native server - closing incoming connection cleans outgoing socket
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'listening 49676'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 14 we should not have gotten an error
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 15 socket shouldn't close until after incoming
ok 16 incoming is cleaned up
# teardown
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Native Server - close'
# setup
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# native server - closing outgoing socket cleans associated mux stream
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'listening 49680'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
ok 17 stream was closed
ok 18 incoming should survive
ok 19 mux should have no streams
# teardown
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# setup
# native server - closing the whole server cleans everything up
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'listening 49684'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 20 we should not have gotten an error
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 21 Buffers are identical
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 22 native server is nulled out
ok 23 native server should be closed
ok 24 incoming has been removed
ok 25 Incoming should be done
ok 26 The mux object should be closed
ok 27 The mux stream should be closed
2016-11-29 12:23:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# teardown
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# setup
# native server - we can get a ton of connections and data through and still clean up the server completely
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'listening 49688'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
ok 28 native server is nulled out
ok 29 native server should be closed
ok 30 incoming has been removed
2016-11-29 12:23:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# teardown
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# native server - simulate mux failure, make sure everything is cleaned up
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'listening 49740'
ok 31 we should not have gotten an error
2016-11-29 12:23:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 32 Buffers are identical
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 33 server should be fine
ok 34 server should be open
ok 35 incoming has been removed
ok 36 The mux object should be closed
ok 37 The mux stream should be closed
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# teardown
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Native Server - close'
# setup
# native server - timing out the incoming connection cleans everything up
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'listening 49744'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 38 we should not have gotten an error
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 39 Buffers are identical
2016-11-29 12:23:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 40 server should be fine
ok 41 server should be open
ok 42 incoming has been removed
ok 43 The mux object should be closed
ok 44 The mux stream should be closed
# teardown
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Native Server - close'
# setup
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# calling createPeerListener without calling start produces error
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'listening 49749'
# teardown
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# calling createPeerListener after calling stop produces error
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'listening 49752'
# teardown
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# can call createPeerListener
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'listening 49755'
2016-11-29 12:23:56 - DEBUG createPeerListener: 'creating new server for peerId'
2016-11-29 12:23:56 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peerId listening on 49756'
ok 45 port must be in range
# teardown
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:23:56 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peerId'
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# calling createPeerListener twice with same peerIdentifier should return the same port
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'listening 49759'
2016-11-29 12:23:56 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-29 12:23:56 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49760'
ok 46 port values should be the same
# teardown
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:23:56 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - closing connection to native listener closes everything and triggers new listener
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'listening 49763'
2016-11-29 12:23:56 - DEBUG createPeerListener: 'creating new server for peer2'
2016-11-29 12:23:56 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 49764'
2016-11-29 12:23:56 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer2 - 0 - got a new incoming connection'
2016-11-29 12:23:56 - DEBUG createPeerListener: 'Issuing callNative for peer2'
2016-11-29 12:23:56 - DEBUG createPeerListener: 'callNative for peer2 connected'
2016-11-29 12:23:56 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer2'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 47 Data should be of same length and content
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:56 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer2 - finish'
2016-11-29 12:23:56 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer2 - 0 - close'
2016-11-29 12:23:56 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer2 - finish'
2016-11-29 12:23:56 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer2 - 0 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:56 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer2 - close'
2016-11-29 12:23:56 - DEBUG createPeerListener: 'We are emitting failedConnection with error Error: Outgoing closed, recreating connection and peerIdentifier peer2'
2016-11-29 12:23:56 - DEBUG createPeerListener: 'Will try to recreate server for peer2'
2016-11-29 12:23:56 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer2 - close'
2016-11-29 12:23:56 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer2'
2016-11-29 12:23:56 - DEBUG createPeerListener: 'creating new server for peer2'
2016-11-29 12:23:56 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 49769'
2016-11-29 12:23:56 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer2 and portNumber 49769'
ok 48 same peer ID
ok 49 different ports
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
# teardown
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:23:56 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer2'
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# createPeerListener - closing mux closes listener and triggers a new listener
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'listening 49772'
2016-11-29 12:23:56 - DEBUG createPeerListener: 'creating new server for peer2'
2016-11-29 12:23:56 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 49773'
2016-11-29 12:23:56 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer2 - 0 - got a new incoming connection'
2016-11-29 12:23:56 - DEBUG createPeerListener: 'Issuing callNative for peer2'
2016-11-29 12:23:56 - DEBUG createPeerListener: 'callNative for peer2 connected'
2016-11-29 12:23:56 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer2'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 50 Data should be of same length and content
2016-11-29 12:23:56 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer2 - 0 - close'
2016-11-29 12:23:56 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer2 - close'
2016-11-29 12:23:56 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer2 - finish'
2016-11-29 12:23:56 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer2 - finish'
2016-11-29 12:23:56 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer2 - 0 - close'
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:56 - DEBUG createPeerListener: 'We are emitting failedConnection with error Error: Outgoing closed, recreating connection and peerIdentifier peer2'
2016-11-29 12:23:56 - DEBUG createPeerListener: 'Will try to recreate server for peer2'
2016-11-29 12:23:56 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer2 - close'
2016-11-29 12:23:56 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer2'
2016-11-29 12:23:56 - DEBUG createPeerListener: 'creating new server for peer2'
2016-11-29 12:23:56 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 49778'
2016-11-29 12:23:56 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer2 and portNumber 49778'
ok 51 same peer ID
ok 52 different ports
# teardown
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:23:56 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer2'
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:23:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# setup
# peerListener - no native server
2016-11-29 12:23:56 - DEBUG createNativeListener: 'Creating Native Server'
ok 53 Can call startUpdateAdvertisingAndListening without error
ok 54 Can call startListeningForAdvertisements without error
2016-11-29 12:23:57 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-29 12:23:57 - DEBUG createNativeListener: 'listening 49781'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49782'
ok 55 peerPort should not be nativePort
2016-11-29 12:23:57 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - finish'
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'We are emitting failedConnection with error Error: Cannot Connect To Peer and peerIdentifier peer1'
ok 56 Should not get event until connection is made
ok 57 reason should be as expected
2016-11-29 12:23:57 - DEBUG createPeerListener: 'Will try to recreate server for peer1'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49785'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer1 and portNumber 49785'
# teardown
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:57 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
# setup
# peerListener - with native server
2016-11-29 12:23:57 - DEBUG createNativeListener: 'Creating Native Server'
ok 58 Can call startUpdateAdvertisingAndListening without error
ok 59 Can call startListeningForAdvertisements without error
2016-11-29 12:23:57 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-29 12:23:57 - DEBUG createNativeListener: 'listening 49788'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49789'
ok 60 peerPort != nativePort
2016-11-29 12:23:57 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
ok 61 Should not get unexpected connection
# teardown
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:57 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer1 - 0 - close'
# setup
2016-11-29 12:23:57 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# peerListener - with native server and data transfer
2016-11-29 12:23:57 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:23:57 - DEBUG createNativeListener: 'listening 49794'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49795'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer1 - close'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - close'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
2016-11-29 12:23:57 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:23:57 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:23:57 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 62 Data should be of same length and content
ok 63 Data should be of same length and content
# teardown
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:57 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:23:57 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-29 12:23:57 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer1 - 0 - close'
2016-11-29 12:23:57 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:23:57 - WARN createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 -  error Error: read ECONNRESET'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - close'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# setup
2016-11-29 12:23:57 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer1 - close'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# createPeerListener is idempotent
2016-11-29 12:23:57 - DEBUG createNativeListener: 'Creating Native Server'
ok 64 Can call startUpdateAdvertisingAndListening without error
ok 65 Can call startListeningForAdvertisements without error
2016-11-29 12:23:57 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-29 12:23:57 - DEBUG createNativeListener: 'listening 49801'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49802'
ok 66 Second call to existing peerListener returns existing port
# teardown
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:57 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - ask for new peer when we are at maximum and make sure we remove the right existing listener
2016-11-29 12:23:57 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:23:57 - DEBUG createNativeListener: 'listening 49805'
# teardown
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:57 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - ask for a new peer when we are not at maximum peers and make sure we do not remove any existing listeners
2016-11-29 12:23:57 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:23:57 - DEBUG createNativeListener: 'listening 49808'
# teardown
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:57 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - test timeout
2016-11-29 12:23:57 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:23:57 - DEBUG createNativeListener: 'listening 49811'
# teardown
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:57 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - multiple connections out
2016-11-29 12:23:57 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:23:57 - DEBUG createNativeListener: 'listening 49814'
# teardown
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:57 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - multiple bi-directional connections
2016-11-29 12:23:57 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:23:57 - DEBUG createNativeListener: 'listening 49817'
# teardown
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:57 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - multiple parallel calls
2016-11-29 12:23:57 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:23:57 - DEBUG createNativeListener: 'listening 49820'
# teardown
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:57 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - we shouldn't create a dead pipe
2016-11-29 12:23:57 - DEBUG createNativeListener: 'Creating Native Server'
ok 67 Can call startUpdateAdvertisingAndListening without error
ok 68 Can call startListeningForAdvertisements without error
2016-11-29 12:23:57 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-29 12:23:57 - DEBUG createNativeListener: 'listening 49823'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49824'
ok 69 peerPort != nativePort
2016-11-29 12:23:57 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
ok 70 Should not get unexpected connection
2016-11-29 12:23:57 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID peer1 with port 49824'
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client - is already closed'
ok 71 passed
2016-11-29 12:23:57 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
# teardown
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:57 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# setup
# #_doImmediateSeqUpdate - server is not there
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer1 - close'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - close'
2016-11-29 12:23:57 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
2016-11-29 12:23:57 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
ok 72 Got right error
# teardown
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - server accepts & closes connection
2016-11-29 12:23:57 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
ok 73 Got socket hang up
# teardown
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - server always returns 500
2016-11-29 12:23:57 - DEBUG localSeqManager: 'Got an error trying to update seq []'
ok 74 Got 500 as expected
# teardown
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - create new seq doc
ok 75 should be equal
ok 76 revs are equal
# teardown
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - doc exists, need to get rev and update
ok 77 should be equal
ok 78 revs are equal
# teardown
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - update seq three times
ok 79 should be equal
ok 80 revs are equal
ok 81 should be equal
ok 82 revs are equal
ok 83 should be equal
ok 84 revs are equal
# teardown
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - rev got changed under us
2016-11-29 12:23:57 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
ok 85 Our rev is old so we should fail
# teardown
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - fail if stop is called
ok 86 confirm stop caused failure
# teardown
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - stop after get but before put fails right
2016-11-29 12:23:57 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
ok 87 stop caused us to fail
ok 88 We specifically failed on a stop before put
# teardown
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - fail if stop is called
ok 89 failed due to stop
ok 90 failed due to stop
# teardown
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - set seq for first time
ok 91 should be equal
# teardown
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - Fail on bad seq value
2016-11-29 12:23:57 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
ok 92 Expected bad seq error
# teardown
2016-11-29 12:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - do we cancel timer properly on an immediate?
ok 93 Different promises
ok 94 Timer was cancelled
ok 95 should be equal
# teardown
2016-11-29 12:23:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - do we wait for blocked update
ok 96 One go and one blocked
ok 97 All blocked
ok 98 Still blocked
ok 99 should be equal
# teardown
2016-11-29 12:23:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - test that we wait long enough
ok 100 We waited long enough
ok 101 should be equal
# teardown
2016-11-29 12:23:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - test that we pick up new sequences while we wait
ok 102 Should have gotten same timer promise
ok 103 Still same timer promise
ok 104 We waited long enough
ok 105 should be equal
# teardown
2016-11-29 12:24:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# closeAll can close even when connections open
2016-11-29 12:24:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 106 not possible to connect to the server anymore
# teardown
# setup
# closeAll with promise
2016-11-29 12:24:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 107 not possible to connect to the server anymore
# teardown
# setup
# closeAll properly throws when closing a non open server with eatNotRunning set to false
2016-11-29 12:24:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 108 Got the right error
# teardown
# setup
# closeAll works even with a server that is not listening yet witheatNotRunning set to true
2016-11-29 12:24:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
# setup
# Call of onCheckpointReached handler on a single db change
# teardown
# setup
# Call of multiple onCheckpointReached handlers on a single db change
# teardown
# setup
# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
ok 109 the checkpointReached handler should be called once. Called 1 time(s)
# teardown
# setup
# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
# teardown
# setup
# test defaultDirectory
ok 110 should be equal
ok 111 should be equal
ok 112 should be equal
# teardown
# setup
# test defaultAdapter
ok 113 should be equal
ok 114 should be equal
ok 115 should be equal
ok 116 should be equal
ok 117 should be equal
ok 118 should be equal
ok 119 should be equal
ok 120 should be equal
# teardown
# setup
# enqueue and run in order
ok 121 firstPromise setTimeout
ok 122 firstPromise result
ok 123 firstPromise testValue
ok 124 secondPromise setTimeout
ok 125 secondPromise result
ok 126 secondPromise testValue
ok 127 thirdPromise in promise
ok 128 thirdPromise result
ok 129 thirdPromise testValue
# teardown
# setup
# enqueueAtTop and run backwards
ok 130 thirdPromise - first to run
ok 131 thirdPromise - in resolve
ok 132 secondPromise - second to run
ok 133 secondPromise - in catch
ok 134 firstPromise - third to run
ok 135 firstPromise - in then
ok 136 testing promises
# teardown
# setup
# mix enqueue and enqueueAtTop
ok 137 fourth
ok 138 fourth
ok 139 second
ok 140 secondPromise - in then
ok 141 first
ok 142 firstPromise - in catch
ok 143 third
ok 144 thirdPromise - in then
ok 145 testingPromises
# teardown
# setup
# queues handled independently
ok 146 all short operations completed before the long resolves
# teardown
# setup
# ssdp server should be restarted when wifi toggled
ok 147 should be in started state
2016-11-29 12:24:03 - DEBUG thaliWifiInfrastructure: 'listening 49902'
ok 148 server start should be called once
ok 149 server stop should not be called
2016-11-29 12:24:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:03 - DEBUG thaliWifiInfrastructure: 'listening 49903'
ok 150 server start should be called twice
ok 151 server stop should be called once
2016-11-29 12:24:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 152 server stop should be called twice
ok 153 should not be in started state
# teardown
# setup
# basic
ok 154 sane
# teardown
# setup
# another
ok 155 sane
# teardown
# setup
# test thali manager spies
2016-11-29 12:24:03 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
2016-11-29 12:24:03 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
2016-11-29 12:24:03 - DEBUG thaliManager: 'creating express pouchdb instance'
ok 156 expressPouchDB was called once
ok 157 expressPouchDB was called with 2 arguments
ok 158 expressPouchDB was called with 'PouchDB' as 1-st argument
ok 159 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
ok 160 PouchDB was called once
ok 161 PouchDB was called with 1 arguments
ok 162 PouchDB was called with 'dbName' as 1-st argument
ok 163 ThaliSendNotificationBasedOnReplication was called once
ok 164 ThaliSendNotificationBasedOnReplication was called with 4 arguments
ok 165 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
ok 166 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
ok 167 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
ok 168 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
ok 169 ThaliPullReplicationFromNotification was called once
ok 170 ThaliPullReplicationFromNotification was called with 4 arguments
ok 171 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
ok 172 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
ok 173 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
ok 174 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
ok 175 Salti was called once
ok 176 Salti was called with 4 arguments
ok 177 Salti was called with 'dbName' as 1-st argument
ok 178 Salti was called with 'acl' as 2-st argument
ok 179 Salti was called with 'thaliIdCallback' as 3-st argument
ok 180 Salti was called with 'options' as 4-st argument
2016-11-29 12:24:03 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-29 12:24:03 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-29 12:24:03 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-29 12:24:03 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-29 12:24:03 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-29 12:24:03 - DEBUG thaliWifiInfrastructure: 'listening 49904'
2016-11-29 12:24:03 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
ok 181 ThaliMobile.start was called once
ok 182 ThaliMobile.start was called with 3 arguments
ok 183 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
ok 184 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
ok 185 ThaliMobile.start was called with 'networkType' as 3-st argument
ok 186 ThaliMobile.startListeningForAdvertisements was called once
ok 187 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
ok 188 ThaliMobile.startUpdateAdvertisingAndListening was called once
ok 189 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
ok 190 ThaliSendNotificationBasedOnReplication.prototype.start was called once
ok 191 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
ok 192 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
ok 193 ThaliPullReplicationFromNotification.prototype.start was called once
ok 194 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
ok 195 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
2016-11-29 12:24:03 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-29 12:24:03 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-29 12:24:03 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-29 12:24:03 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-29 12:24:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:03 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-29 12:24:03 - DEBUG thaliManager: 'stopping ThaliMobile'
ok 196 ThaliMobile.stop was called once
ok 197 ThaliMobile.stop was called with 0 arguments
ok 198 ThaliMobile.stopListeningForAdvertisements was called once
ok 199 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
ok 200 ThaliMobile.stopAdvertisingAndListening was called once
ok 201 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
ok 202 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
ok 203 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
ok 204 ThaliPullReplicationFromNotification.prototype.stop was called once
ok 205 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
# teardown
# setup
# test thali manager multiple starts and stops
2016-11-29 12:24:03 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
2016-11-29 12:24:03 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
2016-11-29 12:24:03 - DEBUG thaliManager: 'creating express pouchdb instance'
ok 206 expressPouchDB was called once
ok 207 expressPouchDB was called with 2 arguments
ok 208 expressPouchDB was called with 'PouchDB' as 1-st argument
ok 209 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
ok 210 PouchDB was called once
ok 211 PouchDB was called with 1 arguments
ok 212 PouchDB was called with 'dbName' as 1-st argument
ok 213 ThaliSendNotificationBasedOnReplication was called once
ok 214 ThaliSendNotificationBasedOnReplication was called with 4 arguments
ok 215 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
ok 216 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
ok 217 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
ok 218 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
ok 219 ThaliPullReplicationFromNotification was called once
ok 220 ThaliPullReplicationFromNotification was called with 4 arguments
ok 221 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
ok 222 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
ok 223 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
ok 224 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
ok 225 Salti was called once
ok 226 Salti was called with 4 arguments
ok 227 Salti was called with 'dbName' as 1-st argument
ok 228 Salti was called with 'acl' as 2-st argument
ok 229 Salti was called with 'thaliIdCallback' as 3-st argument
ok 230 Salti was called with 'options' as 4-st argument
2016-11-29 12:24:03 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-29 12:24:03 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-29 12:24:03 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-29 12:24:03 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-29 12:24:03 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-29 12:24:03 - DEBUG thaliWifiInfrastructure: 'listening 49905'
2016-11-29 12:24:03 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
ok 231 ThaliMobile.start was called once
ok 232 ThaliMobile.start was called with 3 arguments
ok 233 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
ok 234 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
ok 235 ThaliMobile.start was called with 'networkType' as 3-st argument
ok 236 ThaliMobile.startListeningForAdvertisements was called once
ok 237 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
ok 238 ThaliMobile.startUpdateAdvertisingAndListening was called once
ok 239 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
ok 240 ThaliSendNotificationBasedOnReplication.prototype.start was called once
ok 241 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
ok 242 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
ok 243 ThaliPullReplicationFromNotification.prototype.start was called once
ok 244 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
ok 245 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
2016-11-29 12:24:03 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-29 12:24:03 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-29 12:24:03 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-29 12:24:03 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-29 12:24:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:03 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-29 12:24:03 - DEBUG thaliManager: 'stopping ThaliMobile'
ok 246 ThaliMobile.stop was called once
ok 247 ThaliMobile.stop was called with 0 arguments
ok 248 ThaliMobile.stopListeningForAdvertisements was called once
ok 249 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
ok 250 ThaliMobile.stopAdvertisingAndListening was called once
ok 251 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
ok 252 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
ok 253 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
ok 254 ThaliPullReplicationFromNotification.prototype.stop was called once
ok 255 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
2016-11-29 12:24:03 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-29 12:24:03 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-29 12:24:03 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-29 12:24:03 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-29 12:24:03 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-29 12:24:03 - DEBUG thaliWifiInfrastructure: 'listening 49906'
2016-11-29 12:24:03 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
2016-11-29 12:24:03 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-29 12:24:03 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-29 12:24:03 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-29 12:24:03 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-29 12:24:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:03 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-29 12:24:03 - DEBUG thaliManager: 'stopping ThaliMobile'
2016-11-29 12:24:03 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-29 12:24:03 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-29 12:24:03 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-29 12:24:03 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-29 12:24:03 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-29 12:24:03 - DEBUG thaliWifiInfrastructure: 'listening 49907'
2016-11-29 12:24:03 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
2016-11-29 12:24:03 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-29 12:24:03 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-29 12:24:03 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-29 12:24:03 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-29 12:24:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:03 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-29 12:24:03 - DEBUG thaliManager: 'stopping ThaliMobile'
2016-11-29 12:24:03 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-29 12:24:03 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-29 12:24:03 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-29 12:24:03 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-29 12:24:03 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-29 12:24:03 - DEBUG thaliWifiInfrastructure: 'listening 49908'
2016-11-29 12:24:03 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
ok 256 ThaliMobile.start was called once
ok 257 ThaliMobile.start was called with 3 arguments
ok 258 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
ok 259 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
ok 260 ThaliMobile.start was called with 'networkType' as 3-st argument
ok 261 ThaliMobile.startListeningForAdvertisements was called once
ok 262 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
ok 263 ThaliMobile.startUpdateAdvertisingAndListening was called once
ok 264 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
ok 265 ThaliSendNotificationBasedOnReplication.prototype.start was called once
ok 266 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
ok 267 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
ok 268 ThaliPullReplicationFromNotification.prototype.start was called once
ok 269 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
ok 270 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
2016-11-29 12:24:03 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-29 12:24:03 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-29 12:24:03 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-29 12:24:03 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-29 12:24:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:03 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-29 12:24:03 - DEBUG thaliManager: 'stopping ThaliMobile'
# teardown
# setup
# #startListeningForAdvertisements should fail if start not called
ok 271 specific error should be returned
# teardown
ok 272 error should be null
ok 273 error should be null
# setup
# #startUpdateAdvertisingAndListening should fail if start not called
ok 274 specific error should be returned
# teardown
ok 275 error should be null
ok 276 error should be null
# setup
# should be able to call #stopListeningForAdvertisements many times
ok 277 error should be null
ok 278 error should be null
ok 279 error should be null
ok 280 error should be null
# teardown
ok 281 error should be null
ok 282 error should be null
# setup
# should be able to call #startListeningForAdvertisements many times
ok 283 error should be null
ok 284 error should be null
ok 285 error should be null
ok 286 error should be null
# teardown
2016-11-29 12:24:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 287 error should be null
ok 288 error should be null
# setup
# should be able to call #startUpdateAdvertisingAndListening many times
2016-11-29 12:24:03 - DEBUG thaliWifiInfrastructure: 'listening 49909'
ok 289 error should be null
ok 290 error should be null
ok 291 error should be null
ok 292 error should be null
# teardown
2016-11-29 12:24:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 293 error should be null
ok 294 error should be null
# setup
# should be able to call #stopAdvertisingAndListening many times
ok 295 error should be null
ok 296 error should be null
ok 297 error should be null
ok 298 error should be null
# teardown
ok 299 error should be null
ok 300 error should be null
# setup
# #start should fail if called twice in a row
ok 301 first call should succeed
ok 302 first call should succeed
ok 303 specific error should be returned
# teardown
ok 304 error should be null
ok 305 error should be null
# setup
# #stop should clear watchers and change peers
2016-11-29 12:24:04 - DEBUG thaliMobileNativeWrapper: 'listening 49910'
2016-11-29 12:24:04 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:04 - DEBUG createNativeListener: 'listening 49911'
2016-11-29 12:24:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:24:04 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"urn:uuid:3e23f636-e940-4777-882a-d6ff5f8c1efc","peerAvailable":true}'
2016-11-29 12:24:04 - DEBUG createPeerListener: 'creating new server for urn:uuid:3e23f636-e940-4777-882a-d6ff5f8c1efc'
2016-11-29 12:24:04 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for urn:uuid:3e23f636-e940-4777-882a-d6ff5f8c1efc listening on 49912'
2016-11-29 12:24:04 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"urn:uuid:3e23f636-e940-4777-882a-d6ff5f8c1efc","portNumber":49912}'
2016-11-29 12:24:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"urn:uuid:3e23f636-e940-4777-882a-d6ff5f8c1efc","hostAddress":"127.0.0.1","portNumber":49912,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
ok 306 Watchers have one entry for our connection type
ok 307 Peer availabilities has one entry for our connection type
2016-11-29 12:24:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"urn:uuid:3e23f636-e940-4777-882a-d6ff5f8c1efc","hostAddress":null,"portNumber":null,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:24:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:24:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:24:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:04 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:04 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for urn:uuid:3e23f636-e940-4777-882a-d6ff5f8c1efc'
2016-11-29 12:24:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 308 No watchers
ok 309 No peers
ok 310 No watchers
ok 311 No peers
ok 312 No watchers
ok 313 No peers
# teardown
ok 314 error should be null
ok 315 error should be null
# setup
# does not emit duplicate discoveryAdvertisingStateUpdate
2016-11-29 12:24:04 - DEBUG thaliWifiInfrastructure: 'listening 49913'
ok 316 called only once
ok 317 discovery state matches
ok 318 advertising state matches
# teardown
2016-11-29 12:24:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-29 12:24:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:24:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 319 error should be null
ok 320 error should be null
# setup
# does not send duplicate availability changes
2016-11-29 12:24:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"dummy","hostAddress":"127.0.0.1","portNumber":8080,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
ok 321 should be called once
ok 322 should not have been called more than once
# teardown
2016-11-29 12:24:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"dummy","hostAddress":null,"portNumber":null,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
ok 323 error should be null
ok 324 error should be null
# setup
# can get the network status
ok 325 network status should have certain non-empty properties
# teardown
ok 326 error should be null
ok 327 error should be null
# setup
# wifi peer is marked unavailable if announcements stop
2016-11-29 12:24:04 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:cab82908-c03c-47d8-840b-dfef4c64e071","hostAddress":"adaf0938","portNumber":8080}'
2016-11-29 12:24:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"urn:uuid:cab82908-c03c-47d8-840b-dfef4c64e071","hostAddress":"adaf0938","portNumber":8080,"connectionType":"tcp","suggestedTCPTimeout":1000}'
ok 328 host address should match
ok 329 port should match
2016-11-29 12:24:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"urn:uuid:cab82908-c03c-47d8-840b-dfef4c64e071","hostAddress":null,"portNumber":null,"connectionType":"tcp","suggestedTCPTimeout":1000}'
ok 330 host address should be null
ok 331 port should should be null
# teardown
2016-11-29 12:24:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 332 error should be null
ok 333 error should be null
# setup
# network changes emitted correctly
2016-11-29 12:24:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":null,"ssidName":null}'
ok 334 wifi should be off
ok 335 bssid should be null
ok 336 ssid should be null
2016-11-29 12:24:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
ok 337 wifi should be on
ok 338 bssid should be valid
ok 339 ssid should exist
# teardown
ok 340 error should be null
ok 341 error should be null
# setup
# network changes not emitted in started state
ok 342 event should not be emitted
# teardown
ok 343 error should be null
ok 344 error should be null
# setup
# network changes not emitted in stopped state
2016-11-29 12:24:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":null,"ssidName":null}'
ok 345 event should not be emitted
2016-11-29 12:24:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
# teardown
ok 346 error should be null
ok 347 error should be null
# setup
# calls correct starts when network changes
2016-11-29 12:24:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":null,"ssidName":null}'
ok 348 specific error expected
ok 349 specific error expected
2016-11-29 12:24:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:24:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":true,"listening":true,"advertising":true,"networkType":"WIFI"})'
2016-11-29 12:24:05 - DEBUG thaliWifiInfrastructure: 'listening 49914'
ok 350 startListeningForAdvertisements should have been called
ok 351 startUpdateAdvertisingAndListening should have been called
# teardown
2016-11-29 12:24:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-29 12:24:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:24:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 352 error should be null
ok 353 error should be null
# setup
# peer is marked unavailable if port number changes
2016-11-29 12:24:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"urn:uuid:5e7b5269-44e0-4e58-a17f-34bae16d9d39","hostAddress":"127.0.0.1","portNumber":8080,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
ok 354 peer should have a non-empty identifier
ok 355 peer should have a non-empty host address
ok 356 peer should have port number
ok 357 peer should have suggested timeout
ok 358 peer should have a connection type
ok 359 connection type should match one of the pre-defined types
2016-11-29 12:24:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"urn:uuid:5e7b5269-44e0-4e58-a17f-34bae16d9d39","hostAddress":null,"portNumber":null,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
ok 360 peer should have a non-empty identifier
ok 361 host address should be null
ok 362 port number should be null
ok 363 peer should have suggested timeout
ok 364 peer should have a connection type
ok 365 connection type should match one of the pre-defined types
2016-11-29 12:24:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"urn:uuid:5e7b5269-44e0-4e58-a17f-34bae16d9d39","hostAddress":"127.0.0.1","portNumber":8081,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
ok 366 port number must match
ok 367 peer should have a non-empty identifier
ok 368 peer should have a non-empty host address
ok 369 peer should have port number
ok 370 peer should have suggested timeout
ok 371 peer should have a connection type
ok 372 connection type should match one of the pre-defined types
# teardown
2016-11-29 12:24:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"urn:uuid:5e7b5269-44e0-4e58-a17f-34bae16d9d39","hostAddress":null,"portNumber":null,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
ok 373 error should be null
ok 374 error should be null
# setup
# when network connection is lost a peer should be marked unavailable
2016-11-29 12:24:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"urn:uuid:3550d67d-c5f7-4e8e-9de1-9800be9b9b29","hostAddress":"127.0.0.1","portNumber":8080,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:24:05 - INFO testUtils: 'Toggling radios to: false'
2016-11-29 12:24:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:24:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"off","bluetoothLowEnergy":"on","cellular":"on","bssidName":null,"ssidName":null}'
2016-11-29 12:24:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"urn:uuid:3550d67d-c5f7-4e8e-9de1-9800be9b9b29","hostAddress":null,"portNumber":null,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
ok 375 peer should have a non-empty identifier
ok 376 host address should be null
ok 377 port number should be null
ok 378 peer should have suggested timeout
ok 379 peer should have a connection type
ok 380 connection type should match one of the pre-defined types
2016-11-29 12:24:05 - INFO testUtils: 'Toggling radios to: true'
2016-11-29 12:24:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":null,"ssidName":null}'
# teardown
ok 381 error should be null
ok 382 error should be null
2016-11-29 12:24:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
# setup
# We properly fire peer unavailable and then available when connection fails
2016-11-29 12:24:05 - DEBUG thaliMobileNativeWrapper: 'listening 49915'
2016-11-29 12:24:05 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:05 - DEBUG createNativeListener: 'listening 49916'
2016-11-29 12:24:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:24:05 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"urn:uuid:d4c32eed-cdad-4e11-9ff3-d3821f0e653d","peerAvailable":true}'
2016-11-29 12:24:05 - DEBUG createPeerListener: 'creating new server for urn:uuid:d4c32eed-cdad-4e11-9ff3-d3821f0e653d'
2016-11-29 12:24:05 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for urn:uuid:d4c32eed-cdad-4e11-9ff3-d3821f0e653d listening on 49917'
2016-11-29 12:24:05 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"urn:uuid:d4c32eed-cdad-4e11-9ff3-d3821f0e653d","portNumber":49917}'
2016-11-29 12:24:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"urn:uuid:d4c32eed-cdad-4e11-9ff3-d3821f0e653d","hostAddress":"127.0.0.1","portNumber":49917,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
ok 383 peerIds match
ok 384 peer has a portNumber
ok 385 peer has a host address
2016-11-29 12:24:05 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - urn:uuid:d4c32eed-cdad-4e11-9ff3-d3821f0e653d - 0 - got a new incoming connection'
2016-11-29 12:24:05 - DEBUG createPeerListener: 'Issuing callNative for urn:uuid:d4c32eed-cdad-4e11-9ff3-d3821f0e653d'
ok 386 We should have connected
2016-11-29 12:24:05 - WARN createPeerListener: 'callNative for urn:uuid:d4c32eed-cdad-4e11-9ff3-d3821f0e653d failed with Connection could not be established'
2016-11-29 12:24:05 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - urn:uuid:d4c32eed-cdad-4e11-9ff3-d3821f0e653d - 0 - finish'
2016-11-29 12:24:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:05 - DEBUG createPeerListener: 'We are emitting failedConnection with error Error: Connection could not be established and peerIdentifier urn:uuid:d4c32eed-cdad-4e11-9ff3-d3821f0e653d'
2016-11-29 12:24:05 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"urn:uuid:d4c32eed-cdad-4e11-9ff3-d3821f0e653d","portNumber":null,"recreated":true}'
ok 387 Failed on right peer
ok 388 Marked as recreated
2016-11-29 12:24:05 - DEBUG createPeerListener: 'Will try to recreate server for urn:uuid:d4c32eed-cdad-4e11-9ff3-d3821f0e653d'
2016-11-29 12:24:05 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for urn:uuid:d4c32eed-cdad-4e11-9ff3-d3821f0e653d'
2016-11-29 12:24:05 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"urn:uuid:d4c32eed-cdad-4e11-9ff3-d3821f0e653d","portNumber":null,"recreated":true}'
2016-11-29 12:24:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"urn:uuid:d4c32eed-cdad-4e11-9ff3-d3821f0e653d","hostAddress":null,"portNumber":null,"connectionType":"MPCF","suggestedTCPTimeout":5000,"recreated":true}'
ok 389 still same peer IDs
ok 390 peer should not have a portNumber
ok 391 peer should not have a host address
2016-11-29 12:24:05 - DEBUG createPeerListener: 'creating new server for urn:uuid:d4c32eed-cdad-4e11-9ff3-d3821f0e653d'
2016-11-29 12:24:05 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for urn:uuid:d4c32eed-cdad-4e11-9ff3-d3821f0e653d listening on 49919'
2016-11-29 12:24:05 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier urn:uuid:d4c32eed-cdad-4e11-9ff3-d3821f0e653d and portNumber 49919'
2016-11-29 12:24:05 - DEBUG thaliMobileNativeWrapper: 'listenerRecreatedAfterFailureHandler - We are emitting nonTCPPeerAvailabilityChangedEvent with peerIdentifier urn:uuid:d4c32eed-cdad-4e11-9ff3-d3821f0e653d and portNumber 49919'
2016-11-29 12:24:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"urn:uuid:d4c32eed-cdad-4e11-9ff3-d3821f0e653d","hostAddress":"127.0.0.1","portNumber":49919,"connectionType":"MPCF","suggestedTCPTimeout":5000,"recreated":true}'
ok 392 peerIds match again
ok 393 peer has a portNumber again
ok 394 peer has a host address again
ok 395 We got the error we expected
2016-11-29 12:24:05 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - urn:uuid:d4c32eed-cdad-4e11-9ff3-d3821f0e653d - 0 - close'
# teardown
2016-11-29 12:24:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"urn:uuid:d4c32eed-cdad-4e11-9ff3-d3821f0e653d","hostAddress":null,"portNumber":null,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:24:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:24:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:24:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:05 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:05 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for urn:uuid:d4c32eed-cdad-4e11-9ff3-d3821f0e653d'
2016-11-29 12:24:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 396 error should be null
ok 397 error should be null
# setup
# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
2016-11-29 12:24:05 - DEBUG thaliMobileNativeWrapper: 'listening 49920'
2016-11-29 12:24:05 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:05 - DEBUG createNativeListener: 'listening 49921'
2016-11-29 12:24:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:24:05 - DEBUG createPeerListener: 'creating new server for urn:uuid:952af022-423d-4c46-a24a-0dc7db1d7889'
2016-11-29 12:24:05 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for urn:uuid:952af022-423d-4c46-a24a-0dc7db1d7889 listening on 49922'
ok 398 We should have connected
2016-11-29 12:24:05 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - urn:uuid:952af022-423d-4c46-a24a-0dc7db1d7889 - 0 - got a new incoming connection'
2016-11-29 12:24:05 - DEBUG createPeerListener: 'Issuing callNative for urn:uuid:952af022-423d-4c46-a24a-0dc7db1d7889'
2016-11-29 12:24:05 - WARN createPeerListener: 'callNative for urn:uuid:952af022-423d-4c46-a24a-0dc7db1d7889 failed with Connection could not be established'
2016-11-29 12:24:05 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - urn:uuid:952af022-423d-4c46-a24a-0dc7db1d7889 - 0 - finish'
2016-11-29 12:24:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:05 - DEBUG createPeerListener: 'We are emitting failedConnection with error Error: Connection could not be established and peerIdentifier urn:uuid:952af022-423d-4c46-a24a-0dc7db1d7889'
2016-11-29 12:24:05 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"urn:uuid:952af022-423d-4c46-a24a-0dc7db1d7889","portNumber":null,"recreated":true}'
ok 399 Failed on right peer
ok 400 Marked as recreated
2016-11-29 12:24:05 - DEBUG createPeerListener: 'Will try to recreate server for urn:uuid:952af022-423d-4c46-a24a-0dc7db1d7889'
2016-11-29 12:24:05 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for urn:uuid:952af022-423d-4c46-a24a-0dc7db1d7889'
2016-11-29 12:24:05 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"urn:uuid:952af022-423d-4c46-a24a-0dc7db1d7889","portNumber":null,"recreated":true}'
2016-11-29 12:24:05 - DEBUG createPeerListener: 'creating new server for urn:uuid:952af022-423d-4c46-a24a-0dc7db1d7889'
2016-11-29 12:24:05 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for urn:uuid:952af022-423d-4c46-a24a-0dc7db1d7889 listening on 49924'
2016-11-29 12:24:05 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier urn:uuid:952af022-423d-4c46-a24a-0dc7db1d7889 and portNumber 49924'
2016-11-29 12:24:05 - DEBUG thaliMobileNativeWrapper: 'listenerRecreatedAfterFailureHandler - We are emitting nonTCPPeerAvailabilityChangedEvent with peerIdentifier urn:uuid:952af022-423d-4c46-a24a-0dc7db1d7889 and portNumber 49924'
ok 401 Peer still matches
ok 402 We got the connection error
2016-11-29 12:24:05 - WARN createPeerListener: 'Got error trying to restart listener for peer urn:uuid:952af022-423d-4c46-a24a-0dc7db1d7889 after failure TypeError: Cannot call method 'catch' of undefined'
2016-11-29 12:24:05 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - urn:uuid:952af022-423d-4c46-a24a-0dc7db1d7889 - 0 - close'
# teardown
2016-11-29 12:24:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:24:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:24:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:05 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:05 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for urn:uuid:952af022-423d-4c46-a24a-0dc7db1d7889'
2016-11-29 12:24:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 403 error should be null
ok 404 error should be null
# setup
# Test BEACONS_RETRIEVED_AND_PARSED locally
ok 405 peerIdentifier should be identifier
ok 406 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 407 good beacon
ok 408 good preAmble
ok 409 public keys match!
ok 410 must return null after successful call
ok 411 Once start returns the action should be in KILLED state
# teardown
2016-11-29 12:24:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test HTTP_BAD_RESPONSE locally
ok 412 Response should be HTTP_BAD_RESPONSE
ok 413 must return null after successful call
# teardown
2016-11-29 12:24:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test NETWORK_PROBLEM locally
ok 414 Response should be NETWORK_PROBLEM
ok 415 reject reason should be: Could not establish TCP connection
# teardown
2016-11-29 12:24:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Call the start two times
ok 416 Call start once
ok 417 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 418 must return null after successful call.
# teardown
2016-11-29 12:24:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Call the kill before calling the start
ok 419 Should be Killed
ok 420 Start after killed
# teardown
2016-11-29 12:24:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Call the kill immediately after the start
ok 421 Should be KILLED
ok 422 must return null after successful kill
# teardown
2016-11-29 12:24:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Call the kill while waiting a response from the server
ok 423 Should be KILLED
ok 424 must return null after successful kill
# teardown
2016-11-29 12:24:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test to exceed the max content size locally
ok 425 HTTP_BAD_RESPONSE should be response when content size is exceeded
ok 426 must return null after successful call
# teardown
2016-11-29 12:24:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Close the server socket while the client is waiting a response from the server. Local test.
2016-11-29 12:24:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 427 Should be NETWORK_PROBLEM caused closing server socket
ok 428 Should be Could not establish TCP connection
# teardown
# setup
# Close the client socket while the client is waiting a response from the server. Local test.
ok 429 Should be NETWORK_PROBLEM caused closing client socket
ok 430 Should be Could not establish TCP connection
# teardown
2016-11-29 12:24:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #generatePreambleAndBeacons bad args
ok 431 publicKeysToNotify cannot be null
ok 432 ecdh for local device cannot be null
ok 433 milliseconds cannot be less than 0
ok 434 milliseconds cannot be 0
ok 435 milliseconds cannot be greater than one_day
# teardown
# setup
# #generatePreambleAndBeacons empty keys to notify
ok 436 should be equal
# teardown
# setup
# #generatePreambleAndBeacons multiple keys to notify
ok 437 should be equal
ok 438 should be equal
ok 439 (unnamed assert)
ok 440 should be equal
# teardown
# setup
# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
ok 441 should throw
# teardown
# setup
# #parseBeacons invalid expiration in beaconStreamWithPreAmble
ok 442 Preamble expiration must be a 64 bit integer
# teardown
# setup
# #parseBeacons expiration out of range lower
ok 443 Expiration out of range
# teardown
# setup
# #parseBeacons expiration out of range lower
ok 444 Expiration out of range
# teardown
# setup
# #parseBeacons no beacons returns null
ok 445 should be equal
# teardown
# setup
# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
ok 446 Malformed encrypted beacon key ID
# teardown
# setup
# #parseBeacons addressBookCallback fails decrypt
ok 447 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns no matches
ok 448 should be equal
ok 449 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns spurious match
ok 450 should be equal
ok 451 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns public key
ok 452 right number of calls to address book
ok 453 good preAmble
ok 454 good unencryptedKeyId
ok 455 good beacon
# teardown
# setup
# validate generatePskIdentityField
ok 456 decoded buffers match
# teardown
# setup
# validate generatePskSecret
ok 457 secrets match
# teardown
# setup
# validate generatePskSecrets
ok 458 Matching numbers
ok 459 We have an entry!
ok 460 keys match
ok 461 secrets match
ok 462 We have an entry!
ok 463 keys match
ok 464 secrets match
ok 465 We have an entry!
ok 466 keys match
ok 467 secrets match
# teardown
# setup
# validate generateBeaconStreamAndSecrets
ok 468 Streams have same length
ok 469 matching size
ok 470 keys match
ok 471 secrets match
# teardown
# setup
# Add two Peers.
ok 472 should be equal
ok 473 should be equal
ok 474 should be equal
ok 475 should be equal
ok 476 should be equal
# teardown
2016-11-29 12:24:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# TCP_NATIVE peer loses DNS
ok 477 should be equal
ok 478 should be equal
# teardown
2016-11-29 12:24:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Received beacons with no values for us
ok 479 entry exists
ok 480 entry is resolved
# teardown
2016-11-29 12:24:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Notification action killed with a superseded
ok 481 Action should be killed
ok 482 should be equal
# teardown
2016-11-29 12:24:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Resolves an action locally
ok 483 Host address must match
ok 484 suggestedTCPTimeout must match
ok 485 connectionType must match
ok 486 portNumber must match
ok 487 peerIDs must match
# teardown
2016-11-29 12:24:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Resolves an action locally using ThaliPeerPoolDefault
ok 488 Host address must match
ok 489 suggestedTCPTimeout must match
ok 490 connectionType must match
ok 491 portNumber must match
ok 492 peerIds must match
# teardown
2016-11-29 12:24:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Action fails because of a bad hostname.
2016-11-29 12:24:12 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 493 action should be resolved with NETWORK_PROBLEM error
2016-11-29 12:24:12 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 494 action should be resolved with NETWORK_PROBLEM error
2016-11-29 12:24:12 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 495 action should be resolved with NETWORK_PROBLEM error
2016-11-29 12:24:13 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 496 action should be resolved with NETWORK_PROBLEM error
ok 497 correct number of requests
ok 498 correct number of failures
ok 499 correct final peer state
# teardown
2016-11-29 12:24:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# hostaddress is removed when the action is running. 
2016-11-29 12:24:15 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 500 should be equal
# teardown
2016-11-29 12:24:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Client to server request locally
ok 501 secrets are equal
ok 502 Public key matches with the server key
ok 503 Host address must match
ok 504 suggestedTCPTimeout must match
ok 505 connectionType must match
ok 506 portNumber must match
# teardown
2016-11-29 12:24:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test ThaliPskMapCache clean and expiration
ok 507 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
ok 508 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
ok 509 All entries should be expired after 1 second
# teardown
2016-11-29 12:24:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test ThaliPskMapCache getSecret and getPublic
ok 510 All keys need to be available in the cache
ok 511 All entries should be expired after 1 second
# teardown
2016-11-29 12:24:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test ThaliPskMapCache multiple entries
ok 512 Size of the cache should be 2
ok 513 Cache doesn't contain dictionary1
ok 514 Size of the cache should be 1
ok 515 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
2016-11-29 12:24:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Start and stop ThaliNotificationServer
ok 516 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
ok 517 ThaliMobile.StopAdvertisingAndListeningshould be called once
# teardown
2016-11-29 12:24:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Pass an empty array to ThaliNotificationServer.start
ok 518 StartUpdateAdvertisingAndListening should not be called
ok 519 ThaliMobile.StopAdvertisingAndListening should be called once
ok 520 no error
ok 521 should be 204
# teardown
2016-11-29 12:24:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Pass a string to ThaliNotificationServer.start
ok 522 StartUpdateAdvertisingAndListening should not be called
# teardown
2016-11-29 12:24:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Pass an empty parameter to ThaliNotificationServer.start
ok 523 StartUpdateAdvertisingAndListening should not be called
# teardown
2016-11-29 12:24:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make an HTTP request to /NotificationBeacons
ok 524 no error
ok 525 should be 200
ok 526 should be equal
ok 527 should be equal
ok 528 (unnamed assert)
ok 529 no error
ok 530 should be 204
# teardown
2016-11-29 12:24:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make an HTTP request to /NotificationBeacons (no keys)
ok 531 error should be null
ok 532 should be 204
# teardown
2016-11-29 12:24:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make an HTTP request to /NotificationBeaconsbefore calling start
ok 533 should be 404
# teardown
2016-11-29 12:24:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #testThaliPeerAction - test getters
ok 534 getPeerIdentifier
ok 535 getConnectionType
ok 536 getActionType
ok 537 getActionState
ok 538 getPskIdentity
ok 539 getPskKey
# teardown
# setup
# #testThaliPeerAction - start and kill
ok 540 initial state
ok 541 after start
2016-11-29 12:24:19 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 542 after kill
# teardown
# setup
# #testThaliPeerAction - double start
ok 543 should be equal
# teardown
# setup
# #testThaliPeerAction - start after kill
2016-11-29 12:24:19 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 544 clean kill
ok 545 should be equal
# teardown
# setup
# #testThaliPeerAction - make sure ids are unique
ok 546 should not be equal
# teardown
# setup
# #testThaliPeerAction - check that forever agent can be destroyed
ok 547 forever agent should have it's own destroy method
ok 548 agent's destroy should be called
ok 549 agent's destroy should not be called again
ok 550 agent is destroyed
# teardown
# setup
# Test PeerConnectionInformation basics
ok 551 connection type works
ok 552 getHostAddress works
ok 553 getPortNumber works
ok 554 getSuggestedTCPTimeout works
# teardown
# setup
# Test PeerDictionary basic functionality
ok 555 Entry counter must be 1
ok 556 Size must be 1
ok 557 Entry counter must be 2
ok 558 Size must be 2
ok 559 Entry2 should not be found
ok 560 Size must be 1
ok 561 Size must be 0
# teardown
# setup
# Test PeerDictionary with multiple entries.
ok 562 Size must be100
ok 563 Entries between 20 and MAXSIZE + 20 should exist
ok 564 WAITING state entry should not be removed
# teardown
# setup
# RESOLVED entries are removed before WAITING state entry.
ok 565 Entries between 6 and MAXSIZE + 4 should exist
ok 566 Size should be MAXSIZE
ok 567 Size should be MAXSIZE+6
# teardown
# setup
# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
ok 568 WAITING state entry should not be removed
ok 569 Waiting entries between 6 and MAXSIZE + 4 should exist
ok 570 Size should be MAXSIZE
ok 571 entryCounter should be MAXSIZE+6
# teardown
# setup
# When CONTROLLED_BY_POOL entry is removed and kill is called.
ok 572 Kill should be called once
ok 573 Size should be 100
# teardown
# setup
# #ThaliPeerPoolDefault - single action
ok 574 is an agent
ok 575 enqueue is fine
ok 576 Everything should be off the queue
# teardown
# setup
# #ThaliPeerPoolDefault - multiple actions
ok 577 is an agent
ok 578 first enqueue is fine
ok 579 is an agent
ok 580 second enqueue is fine
ok 581 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 582 Queue is empty
# teardown
# setup
# #ThaliPeerPoolDefault - PSK Pool works
ok 583 is an agent
ok 584 good enqueue
ok 585 Identity should match
2016-11-29 12:24:20 - DEBUG testUtils: 'Got response data'
2016-11-29 12:24:20 - DEBUG testUtils: 'Got end'
ok 586 Got expected response
ok 587 Got psk call back
# teardown
2016-11-29 12:24:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #ThaliPeerPoolDefault - stop
ok 588 is an agent
ok 589 enqueue worked
ok 590 is an agent
ok 591 enqueue 2 worked
ok 592 enqueue is not available when stopped
ok 593 start action is killed
ok 594 killed action is still killed
ok 595 inQueue is empty
# teardown
# setup
# #ThaliPeerPoolInterface - make sure that start verifies queue length
ok 596 good start
ok 597 good enqueue
ok 598 queue is not empty
# teardown
# setup
# #ThaliPeerPoolInterface - bad enqueues
ok 599 null arg
ok 600 wrong arg type
ok 601 wrong arg type
# teardown
# setup
# #ThaliPeerPoolInterface - do not allow same object type
ok 602 good enqueue
ok 603 already enqueued
# teardown
# setup
# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
ok 604 good enqueue
ok 605 2nd good enqueue
ok 606 we are in the pool
ok 607 We are out of the pool
ok 608 Action was killed
ok 609 The original kill was called too
ok 610 second item is still in queue
# teardown
# setup
# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
ok 611 good enqueue
ok 612 first kill
ok 613 second NOOP kill
# teardown
# setup
# #ThaliPeerPoolInterface - make sure that stop removes all actions
ok 614 1st good enqueue
ok 615 2nd good enqueue
ok 616 1st action is in the pool
ok 617 2nd action is in the pool
ok 618 1st action is out of the pool
ok 619 2st action is out of the pool
ok 620 pool is empty
# teardown
# setup
# We reject unrecognized connection type
2016-11-29 12:24:20 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 621 Got right error
ok 622 Start should not be called
ok 623 Kill should have been called at least once
# teardown
# setup
# We reject unrecognized action type
2016-11-29 12:24:20 - DEBUG SimpleThaliTape: 'test was skipped, name: 'We reject unrecognized action type''
# teardown
# setup
# One action on bluetooth
2016-11-29 12:24:20 - DEBUG SimpleThaliTape: 'test was skipped, name: 'One action on bluetooth''
# teardown
# setup
# Two notification actions
2016-11-29 12:24:20 - DEBUG SimpleThaliTape: 'test was skipped, name: 'Two notification actions''
# teardown
# setup
# replicateThroughProblems
2016-11-29 12:24:20 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
2016-11-29 12:24:20 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
2016-11-29 12:24:20 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
ok 624 should have gotten null
2016-11-29 12:24:20 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
2016-11-29 12:24:20 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
ok 625 Should have stopped nicely
2016-11-29 12:24:20 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
2016-11-29 12:24:20 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
ok 626 Still looking for null
2016-11-29 12:24:20 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
2016-11-29 12:24:20 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
2016-11-29 12:24:20 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
2016-11-29 12:24:20 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
2016-11-29 12:24:20 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
2016-11-29 12:24:20 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
ok 627 Yup, another null
ok 628 We cloned!
# teardown
# setup
# Replication goes first
2016-11-29 12:24:20 - DEBUG SimpleThaliTape: 'test was skipped, name: 'Replication goes first''
# teardown
# setup
# wifi allows many parallel non-replication actions
2016-11-29 12:24:20 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2016-11-29 12:24:20 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 606, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
ok 629 is an agent
ok 630 First null
2016-11-29 12:24:20 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 607, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
ok 631 is an agent
ok 632 Second null
2016-11-29 12:24:20 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 607, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
truetruefalsetrue
2016-11-29 12:24:20 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 606, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
truetruetruetrue
# teardown
# setup
# wifi allows no more than 2 simultaneous replication actions for same peerID
2016-11-29 12:24:20 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2016-11-29 12:24:20 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 608, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
ok 633 is an agent
ok 634 First null
2016-11-29 12:24:20 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 609, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
ok 635 is an agent
ok 636 second null
ok 637 third null
2016-11-29 12:24:20 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 608, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
2016-11-29 12:24:20 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 609, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
2016-11-29 12:24:20 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
2016-11-29 12:24:20 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
# teardown
# setup
# Make sure peerDictionaryKey is reasonable
ok 638 equal keys
ok 639 not equal connection type
ok 640 same connection type, different buffer
# teardown
# setup
# Make sure start works
2016-11-29 12:24:20 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 641 First start and on called correctly
# teardown
# setup
# Make sure stop works
ok 642 second cleared dictionary
2016-11-29 12:24:20 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 643 First start and on called correctly
ok 644 First stop and removeListener called correctly
ok 645 first action kill called
ok 646 second action kill called
ok 647 first cleared dictionary
ok 648 first cleared pool
ok 649 second cleared dictionary
ok 650 second cleared pool
# teardown
# setup
# Simple peer event
2016-11-29 12:24:20 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 651 listener has been set
ok 652 peer dictionary has expected number of entries
ok 653 Dictionary and pool have same action
ok 654 ads match
ok 655 PouchDB matches
ok 656 DB Names match
ok 657 public keys match
ok 658 peer dictionary has expected number of entries
ok 659 Dictionary and pool have same action
ok 660 ads match
ok 661 PouchDB matches
ok 662 DB Names match
ok 663 public keys match
2016-11-29 12:24:20 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
ok 664 start called once
ok 665 One entry left
ok 666 Dictionary and pool have same action
ok 667 Start never called
ok 668 Kill called once
ok 669 no entries left
ok 670 Third action is dead
ok 671 peer dictionary has expected number of entries
ok 672 Dictionary and pool have same action
ok 673 ads match
ok 674 PouchDB matches
ok 675 DB Names match
ok 676 public keys match
# teardown
# setup
# Server is not there
2016-11-29 12:24:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:20 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
2016-11-29 12:24:20 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: connect ECONNREFUSED  and it caused us to complete'
ok 677 right error
# teardown
2016-11-29 12:24:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Server accepts & closes connection
2016-11-29 12:24:20 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
2016-11-29 12:24:20 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
ok 678 right error
# teardown
2016-11-29 12:24:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Server always returns 500
2016-11-29 12:24:20 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
2016-11-29 12:24:20 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
ok 679 Got error as expected
# teardown
2016-11-29 12:24:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Server always returns 401
2016-11-29 12:24:20 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
2016-11-29 12:24:20 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
ok 680 Got error as expected
# teardown
2016-11-29 12:24:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Server always returns 403
2016-11-29 12:24:20 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
2016-11-29 12:24:20 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
ok 681 Got error as expected
# teardown
2016-11-29 12:24:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make sure docs replicate
2016-11-29 12:24:20 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
2016-11-29 12:24:20 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
2016-11-29 12:24:21 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
ok 682 should be equal
ok 683 All tests passed!
# teardown
2016-11-29 12:24:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Do nothing and make sure we time out
2016-11-29 12:24:21 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
2016-11-29 12:24:23 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2016-11-29 12:24:23 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
ok 684 action should be killed
ok 685 Error should be timed out
ok 686 No doc found
# teardown
2016-11-29 12:24:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Do something and make sure we time out
2016-11-29 12:24:23 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
2016-11-29 12:24:23 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
ok 687 should be equal
2016-11-29 12:24:25 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2016-11-29 12:24:25 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
ok 688 action should be killed
ok 689 Error should be timed out
# teardown
2016-11-29 12:24:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Start replicating and then catch error when server goes
ok 690 socket hung up
# teardown
2016-11-29 12:24:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make sure clone works
ok 691 same getPeerAdvertisesDataForUs
ok 692 Same pouchdB
ok 693 same dbName
ok 694 Same public key
# teardown
# setup
# compareBufferArrays
ok 695 should throw
ok 696 should throw
ok 697 (unnamed assert)
ok 698 (unnamed assert)
ok 699 (unnamed assert)
ok 700 (unnamed assert)
ok 701 (unnamed assert)
# teardown
# setup
# Call start twice and get error
ok 702 should throw
# teardown
# setup
# Start and make sure it runs
# teardown
# setup
# Make sure getTimeWhenRun is right after start
ok 703 (unnamed assert)
# teardown
# setup
# Make sure getTimeWhenRun is -1 after function is called
ok 704 should be equal
# teardown
# setup
# Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
ok 705 should be equal
ok 706 should be equal
ok 707 should throw
# teardown
# setup
# Test TransientState
ok 708 should throw
ok 709 should throw
ok 710 should be equal
ok 711 should be equal
ok 712 should be equal
ok 713 should be equal
ok 714 (unnamed assert)
ok 715 (unnamed assert)
# teardown
# setup
# No peers and empty database
ok 716 verify failed
ok 717 constructor called once
ok 718 constructor called with right args
ok 719 match start arg
ok 720 start called once
ok 721 stop called once
ok 722 stop after start
# teardown
# setup
# One peer and empty DB
ok 723 verify failed
ok 724 constructor called once
ok 725 constructor called with right args
ok 726 match start arg
ok 727 start called once
ok 728 stop called once
ok 729 stop after start
2016-11-29 12:24:25 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# One peer with _Local set behind current seq
ok 730 verify failed
ok 731 constructor called once
ok 732 constructor called with right args
ok 733 match start arg
ok 734 start called once
ok 735 stop called once
ok 736 stop after start
2016-11-29 12:24:25 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# One peer with _Local set equal to current seq
ok 737 verify failed
ok 738 constructor called once
ok 739 constructor called with right args
ok 740 match start arg
ok 741 start called once
ok 742 stop called once
ok 743 stop after start
2016-11-29 12:24:25 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# One peer with _Local set ahead of current seq (and no this should not happen)
ok 744 verify failed
ok 745 constructor called once
ok 746 constructor called with right args
ok 747 match start arg
ok 748 start called once
ok 749 stop called once
ok 750 stop after start
2016-11-29 12:24:25 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# Three peers, one not in DB, one behind and one ahead
ok 751 verify failed
ok 752 constructor called once
ok 753 constructor called with right args
ok 754 match start arg
ok 755 start called once
ok 756 stop called once
ok 757 stop after start
2016-11-29 12:24:25 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# More than maximum peers, make sure we only send maximum allowed
ok 758 verify failed
ok 759 constructor called once
ok 760 constructor called with right args
ok 761 match start arg
ok 762 start called once
ok 763 stop called once
ok 764 stop after start
2016-11-29 12:24:25 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# two peers with empty DB, update the doc
2016-11-29 12:24:25 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 765 verify failed
ok 766 constructor called once
ok 767 constructor called with right args
ok 768 last start before stop
ok 769 empty first start
ok 770 full second start
ok 771 only 2 timers
2016-11-29 12:24:25 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# add doc and make sure tokens refresh when they expire
2016-11-29 12:24:25 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
2016-11-29 12:24:26 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 772 verify failed
ok 773 constructor called once
ok 774 constructor called with right args
ok 775 start before stop
ok 776 We got at least 3 calls to start
ok 777 at least 3
ok 778 default 1
ok 779 1 run
ok 780 default 2
ok 781 2 run
ok 782 default 3
2016-11-29 12:24:26 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# start and stop and start and stop
ok 783 start out null
ok 784 back to null
2016-11-29 12:24:26 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 785 still null
ok 786 verify failed
ok 787 constructor called once
ok 788 constructor called with right args
ok 789 first start before first stop
ok 790 first stop before second start
ok 791 second start before second stop
2016-11-29 12:24:26 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# two identical starts in a row
ok 792 verify failed
ok 793 constructor called once
ok 794 constructor called with right args
ok 795 (unnamed assert)
2016-11-29 12:24:26 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# two different starts in a row
2016-11-29 12:24:26 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 796 verify failed
ok 797 constructor called once
ok 798 constructor called with right args
ok 799 (unnamed assert)
ok 800 (unnamed assert)
# teardown
# setup
# two stops and a start and two stops
ok 801 verify failed
ok 802 constructor called once
ok 803 constructor called with right args
ok 804 start before stop
2016-11-29 12:24:26 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# we properly enqueue requests so no then needed
2016-11-29 12:24:26 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 805 verify failed
ok 806 constructor called once
ok 807 constructor called with right args
ok 808 start before stop
# teardown
# setup
# test calculateSeqPointKeyId
ok 809 should be equal
ok 810 should be equal
# teardown
# setup
# can create servers manager
ok 811 serversManager must not be null
ok 812 serversManager must be an object
# teardown
# setup
# calling stop without start causes error
ok 813 We need to call start first
# teardown
# setup
# can start/stop servers manager
2016-11-29 12:24:26 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:26 - DEBUG createNativeListener: 'listening 50039'
ok 814 port must be in range
# teardown
2016-11-29 12:24:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:26 - DEBUG createNativeListener: 'Native Server - close'
# setup
# starting twice resolves with listening port
2016-11-29 12:24:26 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:26 - DEBUG createNativeListener: 'listening 50040'
ok 815 second start should return same port
# teardown
2016-11-29 12:24:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:26 - DEBUG createNativeListener: 'Native Server - close'
# setup
# terminateIncomingConnection will terminate a connection
2016-11-29 12:24:26 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:26 - DEBUG createNativeListener: 'listening 50042'
2016-11-29 12:24:26 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:24:26 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 816 we should be connected
2016-11-29 12:24:26 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 817 now we are disconnected
2016-11-29 12:24:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
2016-11-29 12:24:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:26 - DEBUG createNativeListener: 'Native Server - close'
# setup
# terminate an Outgoing connection
2016-11-29 12:24:26 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
ok 818 Passed bogus id
2016-11-29 12:24:26 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
ok 819 Passed good id but bogus port
2016-11-29 12:24:26 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
ok 820 Passed right context
ok 821 Right server
ok 822 No error should be set
ok 823 Retry should be false
ok 824 We called close server
# teardown
# setup
ok 825 should be in started state
# After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
2016-11-29 12:24:26 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:e6f572bd-a1e4-4bf6-86cd-4a165647b8cc","hostAddress":"1d52eef5","portNumber":8080}'
ok 826 peer identifier should match
ok 827 host address should match
ok 828 port should match
2016-11-29 12:24:26 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:e6f572bd-a1e4-4bf6-86cd-4a165647b8cc","portNumber":null,"hostAddress":null}'
ok 829 host address should be null
ok 830 port should should be null
# teardown
ok 831 should not be in started state
# setup
ok 832 should be in started state
# #startUpdateAdvertisingAndListening should use different USN after every invocation
2016-11-29 12:24:26 - DEBUG thaliWifiInfrastructure: 'listening 50044'
ok 833 USN should have changed from the first one
2016-11-29 12:24:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 834 when receiving the second byebye, the first USN should be already set
# teardown
ok 835 should not be in started state
# setup
ok 836 should be in started state
# messages with invalid location or USN should be ignored
2016-11-29 12:24:26 - WARN thaliWifiInfrastructure: 'Failed to parse a valid port number from location: http://foo.bar:90000'
ok 837 should not have emitted with invalid port
2016-11-29 12:24:26 - WARN thaliWifiInfrastructure: 'Received an invalid USN value: '
ok 838 should not have emitted with invalid USN
# teardown
ok 839 should not be in started state
# setup
ok 840 should be in started state
# verify that Thali-specific messages are filtered correctly
ok 841 irrelevant messages should be ignored
ok 842 relevant messages should not be ignored
ok 843 messages from this device should be ignored
# teardown
ok 844 should not be in started state
# setup
ok 845 should be in started state
# #startListeningForAdvertisements should fail if start not called
ok 846 specific error should be returned
# teardown
ok 847 should not be in started state
# setup
ok 848 should be in started state
# #startUpdateAdvertisingAndListening should fail if start not called
ok 849 specific error should be returned
# teardown
ok 850 should not be in started state
# setup
ok 851 should be in started state
# #start should fail if called twice in a row
ok 852 specific error should be received
# teardown
ok 853 should not be in started state
# setup
ok 854 should be in started state
# should not be started after stop is called
ok 855 should not be started
ok 856 should not be listening
ok 857 should not target listening
ok 858 should not be advertising
ok 859 should not target advertising
# teardown
ok 860 should not be in started state
# setup
ok 861 should be in started state
# #startUpdateAdvertisingAndListening should fail invalid router has been passed
2016-11-29 12:24:26 - ERROR thaliWifiInfrastructure: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 862 specific error should be received
# teardown
ok 863 should not be in started state
# setup
ok 864 should be in started state
# #startUpdateAdvertisingAndListening should fail if router server starting fails
2016-11-29 12:24:26 - ERROR thaliWifiInfrastructure: 'Router server emitted an error: Error: listen EADDRINUSE'
ok 865 specific error expected
# teardown
ok 866 should not be in started state
# setup
ok 867 should be in started state
# #startUpdateAdvertisingAndListening should start hosting given router object
2016-11-29 12:24:26 - DEBUG thaliWifiInfrastructure: 'listening 50046'
ok 868 server should respond with code 200
# teardown
2016-11-29 12:24:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 869 should not be in started state
# setup
ok 870 should be in started state
# #startUpdateAdvertisingAndListening bad psk should be rejected object
2016-11-29 12:24:26 - DEBUG thaliWifiInfrastructure: 'listening 50048'
ok 871 Connection should be rejected
# teardown
2016-11-29 12:24:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 872 should not be in started state
# setup
ok 873 should be in started state
# #stop can be called multiple times in a row
ok 874 should be in stopped state
ok 875 should still be in stopped state
# teardown
ok 876 should not be in started state
# setup
ok 877 should be in started state
# #startListeningForAdvertisements can be called multiple times in a row
ok 878 should be in listening state
ok 879 should still be in listening state
# teardown
ok 880 should not be in started state
# setup
ok 881 should be in started state
# #stopListeningForAdvertisements can be called multiple times in a row
ok 882 should not be in listening state
ok 883 should still not be in listening state
# teardown
ok 884 should not be in started state
# setup
ok 885 should be in started state
# #stopAdvertisingAndListening can be called multiple times in a row
ok 886 should not be in advertising state
ok 887 should still not be in advertising state
# teardown
ok 888 should not be in started state
# setup
ok 889 should be in started state
# functions are run from a queue in the right order
2016-11-29 12:24:26 - DEBUG thaliWifiInfrastructure: 'listening 50050'
2016-11-29 12:24:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 890 call order must match
# teardown
ok 891 should not be in started state
# setup
ok 892 should be in started state
# does not get peer changes from self
2016-11-29 12:24:26 - DEBUG thaliWifiInfrastructure: 'listening 50051'
ok 893 USN must have changed again
# teardown
2016-11-29 12:24:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 894 should not be in started state
# setup
ok 895 should be in started state
# network changes are ignored while stopping
2016-11-29 12:24:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":null,"ssidName":null}'
2016-11-29 12:24:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
ok 896 should not be called
# teardown
ok 897 should not be in started state
# setup
ok 898 should be in started state
# #startListeningForAdvertisements returns error if wifi is off and fires event when on
2016-11-29 12:24:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":null,"ssidName":null}'
ok 899 wifi should be off
ok 900 specific error expected
2016-11-29 12:24:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
ok 901 discoveryActive should be true
# teardown
ok 902 should not be in started state
# setup
ok 903 should be in started state
# #startUpdateAdvertisingAndListening returns error if wifi is off and fires event when on
2016-11-29 12:24:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":null,"ssidName":null}'
ok 904 wifi should be off
ok 905 specific error expected
2016-11-29 12:24:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:24:28 - DEBUG thaliWifiInfrastructure: 'listening 50052'
ok 906 advertisingActive should be true
# teardown
2016-11-29 12:24:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 907 should not be in started state
# setup
ok 908 should be in started state
# when wifi is enabled discovery is activated and peers become available
2016-11-29 12:24:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":null,"ssidName":null}'
ok 909 wifi should be off
ok 910 specific error expected
2016-11-29 12:24:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:24:28 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:85f943b3-ff22-4bb7-bb35-9519fe5171b7","hostAddress":"1d52eef5","portNumber":8080}'
ok 911 peer identifier should match
ok 912 host address should match
ok 913 port should match
# teardown
ok 914 should not be in started state
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - emits incomingConnectionState'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - native server connections all up'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - calling createPeerListener without calling start produces error'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - calling createPeerListener after calling stop produces error'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - can call createPeerListener'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - calling createPeerListener twice with same peerIdentifier should return the same port'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - createPeerListener - closing connection to native listener closes everything and triggers new listener'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - createPeerListener - closing mux closes listener and triggers a new listener'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - peerListener - no native server'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - peerListener - with native server'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - peerListener - with native server and data transfer'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - createPeerListener is idempotent'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - createPeerListener - ask for new peer when we are at maximum and make sure we remove the right existing listener'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - createPeerListener - ask for a new peer when we are not at maximum peers and make sure we do not remove any existing listeners'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - createPeerListener - test timeout'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - createPeerListener - multiple connections out'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - createPeerListener - multiple bi-directional connections'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - createPeerListener - multiple parallel calls'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - createPeerListener - we shouldn't create a dead pipe'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - server is not there'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - server accepts & closes connection'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - server always returns 500'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - create new seq doc'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - doc exists, need to get rev and update'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - update seq three times'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - rev got changed under us'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - fail if stop is called'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - stop after get but before put fails right'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #update - fail if stop is called'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #update - set seq for first time'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #update - Fail on bad seq value'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #update - do we cancel timer properly on an immediate?'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #update - do we wait for blocked update'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #update - test that we wait long enough'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #update - test that we pick up new sequences while we wait'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - closeAll with promise'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - closeAll works even with a server that is not listening yet witheatNotRunning set to true'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Call of onCheckpointReached handler on a single db change'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Call of multiple onCheckpointReached handlers on a single db change'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - test defaultDirectory'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - test defaultAdapter'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - enqueue and run in order'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - queues handled independently'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - ssdp server should be restarted when wifi toggled'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - basic'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - another'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - test thali manager spies'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - test thali manager multiple starts and stops'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #start should fail if called twice in a row'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #stop should clear watchers and change peers'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - does not emit duplicate discoveryAdvertisingStateUpdate'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - does not send duplicate availability changes'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - can get the network status'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - wifi peer is marked unavailable if announcements stop'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - network changes emitted correctly'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - network changes not emitted in started state'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - network changes not emitted in stopped state'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - calls correct starts when network changes'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - peer is marked unavailable if port number changes'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - when network connection is lost a peer should be marked unavailable'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - We properly fire peer unavailable and then available when connection fails'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Test BEACONS_RETRIEVED_AND_PARSED locally'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Test HTTP_BAD_RESPONSE locally'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Test NETWORK_PROBLEM locally'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Call the start two times'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Call the kill before calling the start'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Call the kill immediately after the start'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Call the kill while waiting a response from the server'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Test to exceed the max content size locally'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Close the server socket while the client is waiting a response from the server. Local test.'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Close the client socket while the client is waiting a response from the server. Local test.'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons bad args'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons empty keys to notify'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons multiple keys to notify'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #parseBeacons invalid expiration in beaconStreamWithPreAmble'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #parseBeacons no beacons returns null'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback fails decrypt'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns no matches'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns spurious match'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns public key'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - validate generatePskIdentityField'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - validate generatePskSecret'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - validate generatePskSecrets'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - validate generateBeaconStreamAndSecrets'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Add two Peers.'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - TCP_NATIVE peer loses DNS'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Received beacons with no values for us'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Notification action killed with a superseded'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Resolves an action locally'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Resolves an action locally using ThaliPeerPoolDefault'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Action fails because of a bad hostname.'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - hostaddress is removed when the action is running. '
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Client to server request locally'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Test ThaliPskMapCache clean and expiration'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Test ThaliPskMapCache getSecret and getPublic'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Test ThaliPskMapCache multiple entries'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Start and stop ThaliNotificationServer'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Pass an empty array to ThaliNotificationServer.start'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Pass a string to ThaliNotificationServer.start'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Pass an empty parameter to ThaliNotificationServer.start'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons (no keys)'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeaconsbefore calling start'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #testThaliPeerAction - test getters'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #testThaliPeerAction - start and kill'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #testThaliPeerAction - double start'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #testThaliPeerAction - start after kill'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #testThaliPeerAction - make sure ids are unique'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #testThaliPeerAction - check that forever agent can be destroyed'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Test PeerConnectionInformation basics'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Test PeerDictionary basic functionality'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Test PeerDictionary with multiple entries.'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - RESOLVED entries are removed before WAITING state entry.'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - WAITING entries are removed before CONTROLLED_BY_POOL state entry.'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - When CONTROLLED_BY_POOL entry is removed and kill is called.'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - single action'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - multiple actions'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - PSK Pool works'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - stop'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that start verifies queue length'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - bad enqueues'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - do not allow same object type'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure we catch kill and dequeue'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that stop removes all actions'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - We reject unrecognized connection type'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - We reject unrecognized action type'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - One action on bluetooth'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - Two notification actions'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - replicateThroughProblems'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - Replication goes first'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - wifi allows many parallel non-replication actions'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - wifi allows no more than 2 simultaneous replication actions for same peerID'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Make sure peerDictionaryKey is reasonable'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Make sure start works'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Make sure stop works'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Simple peer event'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Server is not there'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Server accepts & closes connection'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Server always returns 500'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Server always returns 401'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Server always returns 403'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Make sure docs replicate'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Do nothing and make sure we time out'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Do something and make sure we time out'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Start replicating and then catch error when server goes'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Make sure clone works'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - compareBufferArrays'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Call start twice and get error'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Start and make sure it runs'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Make sure getTimeWhenRun is right after start'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Make sure getTimeWhenRun is -1 after function is called'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Test TransientState'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - No peers and empty database'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - One peer and empty DB'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - One peer with _Local set behind current seq'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - One peer with _Local set equal to current seq'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - One peer with _Local set ahead of current seq (and no this should not happen)'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Three peers, one not in DB, one behind and one ahead'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - More than maximum peers, make sure we only send maximum allowed'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - two peers with empty DB, update the doc'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - add doc and make sure tokens refresh when they expire'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - start and stop and start and stop'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - two identical starts in a row'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - two different starts in a row'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - two stops and a start and two stops'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - we properly enqueue requests so no then needed'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - test calculateSeqPointKeyId'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - can create servers manager'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - calling stop without start causes error'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - can start/stop servers manager'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should use different USN after every invocation'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - messages with invalid location or USN should be ignored'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - verify that Thali-specific messages are filtered correctly'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #start should fail if called twice in a row'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - should not be started after stop is called'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail invalid router has been passed'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if router server starting fails'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should start hosting given router object'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening bad psk should be rejected object'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #stop can be called multiple times in a row'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #startListeningForAdvertisements can be called multiple times in a row'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #stopListeningForAdvertisements can be called multiple times in a row'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #stopAdvertisingAndListening can be called multiple times in a row'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - functions are run from a queue in the right order'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - does not get peer changes from self'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - network changes are ignored while stopping'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #startListeningForAdvertisements returns error if wifi is off and fires event when on'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening returns error if wifi is off and fires event when on'
2016-11-29 12:24:28 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - when wifi is enabled discovery is activated and peers become available'
2016-11-29 12:24:28 - DEBUG SimpleThaliTape: 'all unit tests succeeded, platformName: 'desktop''
2016-11-29 12:24:28 - DEBUG SimpleThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'

1..914
# tests 914
# pass  914

# ok

2016-11-29 12:24:30 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: android'
2016-11-29 12:24:30 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreateNativeListener.js'
2016-11-29 12:24:30 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js'
2016-11-29 12:24:30 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js'
2016-11-29 12:24:30 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
2016-11-29 12:24:30 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
2016-11-29 12:24:30 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testNativeMethod.js'
2016-11-29 12:24:30 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
2016-11-29 12:24:31 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBGenerator.js'
2016-11-29 12:24:31 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPromiseQueue.js'
2016-11-29 12:24:31 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testSSDPServer.js'
2016-11-29 12:24:31 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testTests.js'
2016-11-29 12:24:31 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManager.js'
2016-11-29 12:24:31 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
2016-11-29 12:24:31 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js'
2016-11-29 12:24:31 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNative.js'
2016-11-29 12:24:31 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
2016-11-29 12:24:31 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
2016-11-29 12:24:31 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotification.js'
2016-11-29 12:24:31 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationAction.js'
2016-11-29 12:24:31 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
2016-11-29 12:24:31 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationClient.js'
2016-11-29 12:24:31 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationLocal.js'
2016-11-29 12:24:31 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationServer.js'
2016-11-29 12:24:31 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerAction.js'
2016-11-29 12:24:31 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerDictionary.js'
2016-11-29 12:24:31 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
2016-11-29 12:24:31 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
2016-11-29 12:24:31 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
2016-11-29 12:24:31 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
2016-11-29 12:24:31 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
2016-11-29 12:24:31 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
2016-11-29 12:24:31 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
2016-11-29 12:24:31 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
2016-11-29 12:24:31 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
2016-11-29 12:24:31 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliTcpServersManager.js'
2016-11-29 12:24:31 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
2016-11-29 12:24:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-29 12:24:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-29 12:24:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:24:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-29 12:24:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
TAP version 13
# setup
# calling createNativeListener directly rejects
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'listening 50054'
ok 1 Should throw
# teardown
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - close'
# setup
# emits incomingConnectionState
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'listening 50056'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 2 initial connection state should be CONNECTED
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 3 final connection state should be DISCONNECTED
# teardown
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - close'
# setup
# emits routerPortConnectionFailed
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'listening 50059'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
ok 4 tried to connect to right port
ok 5 failed due to refused connection
ok 6 routerPortConnectionFailed is emitted
# teardown
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# setup
# native server connections all up
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'listening 50063'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
ok 7 Send/recvd #1 should be equal length
ok 8 Send/recvd #1 should be same
ok 9 Send/recvd #2 should be equal length
ok 10 Send/recvd #2 should be same
ok 11 Should be exactly 2 client sockets
# teardown
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# setup
# native server - closing incoming stream cleans outgoing socket
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'listening 50068'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
ok 12 socket shouldn't close until after stream
ok 13 incoming remains open
# teardown
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# setup
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# native server - closing incoming connection cleans outgoing socket
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'listening 50072'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 14 we should not have gotten an error
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 15 socket shouldn't close until after incoming
ok 16 incoming is cleaned up
# teardown
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - close'
# setup
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# native server - closing outgoing socket cleans associated mux stream
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'listening 50076'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
ok 17 stream was closed
ok 18 incoming should survive
ok 19 mux should have no streams
# teardown
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# setup
# native server - closing the whole server cleans everything up
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'listening 50080'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 20 we should not have gotten an error
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 21 Buffers are identical
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 22 native server is nulled out
ok 23 native server should be closed
ok 24 incoming has been removed
ok 25 Incoming should be done
ok 26 The mux object should be closed
ok 27 The mux stream should be closed
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# teardown
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# setup
# native server - we can get a ton of connections and data through and still clean up the server completely
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'listening 50084'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
ok 28 native server is nulled out
ok 29 native server should be closed
ok 30 incoming has been removed
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# teardown
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# native server - simulate mux failure, make sure everything is cleaned up
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'listening 50136'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 31 we should not have gotten an error
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 32 Buffers are identical
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 33 server should be fine
ok 34 server should be open
ok 35 incoming has been removed
ok 36 The mux object should be closed
ok 37 The mux stream should be closed
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# teardown
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - close'
# setup
# native server - timing out the incoming connection cleans everything up
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'listening 50140'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 38 we should not have gotten an error
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 39 Buffers are identical
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 40 server should be fine
ok 41 server should be open
ok 42 incoming has been removed
ok 43 The mux object should be closed
ok 44 The mux stream should be closed
# teardown
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - close'
# setup
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# calling createPeerListener without calling start produces error
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'listening 50145'
# teardown
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# calling createPeerListener after calling stop produces error
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'listening 50148'
# teardown
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# can call createPeerListener
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'listening 50151'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'creating new server for peerId'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peerId listening on 50152'
ok 45 port must be in range
# teardown
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peerId'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# calling createPeerListener twice with same peerIdentifier should return the same port
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'listening 50155'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50156'
ok 46 port values should be the same
# teardown
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - closing connection to native listener closes everything and triggers new listener
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'listening 50159'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'creating new server for peer2'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 50160'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer2 - 0 - got a new incoming connection'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'Issuing callNative for peer2'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'callNative for peer2 connected'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer2'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 47 Data should be of same length and content
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer2 - finish'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer2 - 0 - close'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer2 - finish'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer2 - 0 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer2 - close'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'We are emitting failedConnection with error Error: Outgoing closed, recreating connection and peerIdentifier peer2'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'Will try to recreate server for peer2'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer2 - close'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer2'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'creating new server for peer2'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 50165'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer2 and portNumber 50165'
ok 48 same peer ID
ok 49 different ports
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
# teardown
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer2'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# createPeerListener - closing mux closes listener and triggers a new listener
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'listening 50168'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'creating new server for peer2'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 50169'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer2 - 0 - got a new incoming connection'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'Issuing callNative for peer2'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'callNative for peer2 connected'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer2'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 50 Data should be of same length and content
2016-11-29 12:24:31 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer2 - 0 - close'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer2 - close'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer2 - finish'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer2 - finish'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer2 - 0 - close'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'We are emitting failedConnection with error Error: Outgoing closed, recreating connection and peerIdentifier peer2'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'Will try to recreate server for peer2'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer2 - close'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer2'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'creating new server for peer2'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 50174'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer2 and portNumber 50174'
ok 51 same peer ID
ok 52 different ports
# teardown
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer2'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# setup
# peerListener - no native server
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Creating Native Server'
ok 53 Can call startUpdateAdvertisingAndListening without error
ok 54 Can call startListeningForAdvertisements without error
2016-11-29 12:24:31 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'listening 50177'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50178'
ok 55 peerPort should not be nativePort
2016-11-29 12:24:31 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - finish'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'We are emitting failedConnection with error Error: Cannot Connect To Peer and peerIdentifier peer1'
ok 56 Should not get event until connection is made
ok 57 reason should be as expected
2016-11-29 12:24:31 - DEBUG createPeerListener: 'Will try to recreate server for peer1'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50181'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer1 and portNumber 50181'
# teardown
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
# setup
# peerListener - with native server
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Creating Native Server'
ok 58 Can call startUpdateAdvertisingAndListening without error
ok 59 Can call startListeningForAdvertisements without error
2016-11-29 12:24:31 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'listening 50184'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50185'
ok 60 peerPort != nativePort
2016-11-29 12:24:31 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
ok 61 Should not get unexpected connection
# teardown
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer1 - 0 - close'
# setup
2016-11-29 12:24:31 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# peerListener - with native server and data transfer
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'listening 50190'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50191'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer1 - close'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - close'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 62 Data should be of same length and content
ok 63 Data should be of same length and content
# teardown
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer1 - 0 - close'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:24:31 - WARN createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 -  error Error: read ECONNRESET'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - close'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# setup
2016-11-29 12:24:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer1 - close'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# createPeerListener is idempotent
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Creating Native Server'
ok 64 Can call startUpdateAdvertisingAndListening without error
ok 65 Can call startListeningForAdvertisements without error
2016-11-29 12:24:31 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'listening 50197'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50198'
ok 66 Second call to existing peerListener returns existing port
# teardown
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - ask for new peer when we are at maximum and make sure we remove the right existing listener
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'listening 50201'
# teardown
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - ask for a new peer when we are not at maximum peers and make sure we do not remove any existing listeners
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'listening 50204'
# teardown
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - test timeout
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'listening 50207'
# teardown
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - multiple connections out
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'listening 50210'
# teardown
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - multiple bi-directional connections
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'listening 50213'
# teardown
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - multiple parallel calls
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'listening 50216'
# teardown
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - we shouldn't create a dead pipe
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Creating Native Server'
ok 67 Can call startUpdateAdvertisingAndListening without error
ok 68 Can call startListeningForAdvertisements without error
2016-11-29 12:24:31 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'listening 50219'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50220'
ok 69 peerPort != nativePort
2016-11-29 12:24:31 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
ok 70 Should not get unexpected connection
2016-11-29 12:24:31 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID peer1 with port 50220'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client - is already closed'
ok 71 passed
2016-11-29 12:24:31 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
# teardown
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# setup
# #_doImmediateSeqUpdate - server is not there
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer1 - close'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - close'
2016-11-29 12:24:31 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
2016-11-29 12:24:31 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
ok 72 Got right error
# teardown
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - server accepts & closes connection
2016-11-29 12:24:31 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
ok 73 Got socket hang up
# teardown
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - server always returns 500
2016-11-29 12:24:31 - DEBUG localSeqManager: 'Got an error trying to update seq []'
ok 74 Got 500 as expected
# teardown
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - create new seq doc
ok 75 should be equal
ok 76 revs are equal
# teardown
2016-11-29 12:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - doc exists, need to get rev and update
ok 77 should be equal
ok 78 revs are equal
# teardown
2016-11-29 12:24:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - update seq three times
ok 79 should be equal
ok 80 revs are equal
ok 81 should be equal
ok 82 revs are equal
ok 83 should be equal
ok 84 revs are equal
# teardown
2016-11-29 12:24:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - rev got changed under us
2016-11-29 12:24:32 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
ok 85 Our rev is old so we should fail
# teardown
2016-11-29 12:24:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - fail if stop is called
ok 86 confirm stop caused failure
# teardown
2016-11-29 12:24:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - stop after get but before put fails right
2016-11-29 12:24:32 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
ok 87 stop caused us to fail
ok 88 We specifically failed on a stop before put
# teardown
2016-11-29 12:24:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - fail if stop is called
ok 89 failed due to stop
ok 90 failed due to stop
# teardown
2016-11-29 12:24:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - set seq for first time
ok 91 should be equal
# teardown
2016-11-29 12:24:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - Fail on bad seq value
2016-11-29 12:24:32 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
ok 92 Expected bad seq error
# teardown
2016-11-29 12:24:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - do we cancel timer properly on an immediate?
ok 93 Different promises
ok 94 Timer was cancelled
ok 95 should be equal
# teardown
2016-11-29 12:24:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - do we wait for blocked update
ok 96 One go and one blocked
ok 97 All blocked
ok 98 Still blocked
ok 99 should be equal
# teardown
2016-11-29 12:24:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - test that we wait long enough
ok 100 We waited long enough
ok 101 should be equal
# teardown
2016-11-29 12:24:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - test that we pick up new sequences while we wait
ok 102 Should have gotten same timer promise
ok 103 Still same timer promise
ok 104 We waited long enough
ok 105 should be equal
# teardown
2016-11-29 12:24:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# closeAll can close even when connections open
2016-11-29 12:24:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 106 not possible to connect to the server anymore
# teardown
# setup
# closeAll with promise
2016-11-29 12:24:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 107 not possible to connect to the server anymore
# teardown
# setup
# closeAll properly throws when closing a non open server with eatNotRunning set to false
2016-11-29 12:24:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 108 Got the right error
# teardown
# setup
# closeAll works even with a server that is not listening yet witheatNotRunning set to true
2016-11-29 12:24:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
# setup
# Call of onCheckpointReached handler on a single db change
# teardown
# setup
# Call of multiple onCheckpointReached handlers on a single db change
# teardown
# setup
# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
ok 109 the checkpointReached handler should be called once. Called 1 time(s)
# teardown
# setup
# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
# teardown
# setup
# test defaultDirectory
ok 110 should be equal
ok 111 should be equal
ok 112 should be equal
# teardown
# setup
# test defaultAdapter
ok 113 should be equal
ok 114 should be equal
ok 115 should be equal
ok 116 should be equal
ok 117 should be equal
ok 118 should be equal
ok 119 should be equal
ok 120 should be equal
# teardown
# setup
# enqueue and run in order
ok 121 firstPromise setTimeout
ok 122 firstPromise result
ok 123 firstPromise testValue
ok 124 secondPromise setTimeout
ok 125 secondPromise result
ok 126 secondPromise testValue
ok 127 thirdPromise in promise
ok 128 thirdPromise result
ok 129 thirdPromise testValue
# teardown
# setup
# enqueueAtTop and run backwards
ok 130 thirdPromise - first to run
ok 131 thirdPromise - in resolve
ok 132 secondPromise - second to run
ok 133 secondPromise - in catch
ok 134 firstPromise - third to run
ok 135 firstPromise - in then
ok 136 testing promises
# teardown
# setup
# mix enqueue and enqueueAtTop
ok 137 fourth
ok 138 fourth
ok 139 second
ok 140 secondPromise - in then
ok 141 first
ok 142 firstPromise - in catch
ok 143 third
ok 144 thirdPromise - in then
ok 145 testingPromises
# teardown
# setup
# queues handled independently
ok 146 all short operations completed before the long resolves
# teardown
# setup
# ssdp server should be restarted when wifi toggled
2016-11-29 12:24:37 - DEBUG SimpleThaliTape: 'test was skipped, name: 'ssdp server should be restarted when wifi toggled''
# teardown
# setup
# basic
ok 147 sane
# teardown
# setup
# another
ok 148 sane
# teardown
# setup
# test thali manager spies
2016-11-29 12:24:37 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
2016-11-29 12:24:37 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
2016-11-29 12:24:37 - DEBUG thaliManager: 'creating express pouchdb instance'
ok 149 expressPouchDB was called once
ok 150 expressPouchDB was called with 2 arguments
ok 151 expressPouchDB was called with 'PouchDB' as 1-st argument
ok 152 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
ok 153 PouchDB was called once
ok 154 PouchDB was called with 1 arguments
ok 155 PouchDB was called with 'dbName' as 1-st argument
ok 156 ThaliSendNotificationBasedOnReplication was called once
ok 157 ThaliSendNotificationBasedOnReplication was called with 4 arguments
ok 158 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
ok 159 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
ok 160 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
ok 161 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
ok 162 ThaliPullReplicationFromNotification was called once
ok 163 ThaliPullReplicationFromNotification was called with 4 arguments
ok 164 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
ok 165 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
ok 166 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
ok 167 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
ok 168 Salti was called once
ok 169 Salti was called with 4 arguments
ok 170 Salti was called with 'dbName' as 1-st argument
ok 171 Salti was called with 'acl' as 2-st argument
ok 172 Salti was called with 'thaliIdCallback' as 3-st argument
ok 173 Salti was called with 'options' as 4-st argument
2016-11-29 12:24:37 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-29 12:24:37 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-29 12:24:37 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-29 12:24:37 - DEBUG thaliMobileNativeWrapper: 'listening 50298'
2016-11-29 12:24:37 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:37 - DEBUG createNativeListener: 'listening 50299'
2016-11-29 12:24:37 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-29 12:24:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:24:37 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-29 12:24:37 - DEBUG thaliWifiInfrastructure: 'listening 50301'
2016-11-29 12:24:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-11-29 12:24:37 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
ok 174 ThaliMobile.start was called once
ok 175 ThaliMobile.start was called with 3 arguments
ok 176 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
ok 177 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
ok 178 ThaliMobile.start was called with 'networkType' as 3-st argument
ok 179 ThaliMobile.startListeningForAdvertisements was called once
ok 180 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
ok 181 ThaliMobile.startUpdateAdvertisingAndListening was called once
ok 182 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
ok 183 ThaliSendNotificationBasedOnReplication.prototype.start was called once
ok 184 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
ok 185 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
ok 186 ThaliPullReplicationFromNotification.prototype.start was called once
ok 187 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
ok 188 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
2016-11-29 12:24:37 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-29 12:24:37 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-29 12:24:37 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-29 12:24:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:37 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-29 12:24:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:24:37 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-29 12:24:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:24:37 - DEBUG thaliManager: 'stopping ThaliMobile'
2016-11-29 12:24:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:37 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 189 ThaliMobile.stop was called once
ok 190 ThaliMobile.stop was called with 0 arguments
ok 191 ThaliMobile.stopListeningForAdvertisements was called once
ok 192 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
ok 193 ThaliMobile.stopAdvertisingAndListening was called once
ok 194 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
ok 195 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
ok 196 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
ok 197 ThaliPullReplicationFromNotification.prototype.stop was called once
ok 198 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
# teardown
# setup
# test thali manager multiple starts and stops
2016-11-29 12:24:37 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
2016-11-29 12:24:37 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
2016-11-29 12:24:37 - DEBUG thaliManager: 'creating express pouchdb instance'
ok 199 expressPouchDB was called once
ok 200 expressPouchDB was called with 2 arguments
ok 201 expressPouchDB was called with 'PouchDB' as 1-st argument
ok 202 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
ok 203 PouchDB was called once
ok 204 PouchDB was called with 1 arguments
ok 205 PouchDB was called with 'dbName' as 1-st argument
ok 206 ThaliSendNotificationBasedOnReplication was called once
ok 207 ThaliSendNotificationBasedOnReplication was called with 4 arguments
ok 208 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
ok 209 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
ok 210 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
ok 211 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
ok 212 ThaliPullReplicationFromNotification was called once
ok 213 ThaliPullReplicationFromNotification was called with 4 arguments
ok 214 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
ok 215 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
ok 216 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
ok 217 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
ok 218 Salti was called once
ok 219 Salti was called with 4 arguments
ok 220 Salti was called with 'dbName' as 1-st argument
ok 221 Salti was called with 'acl' as 2-st argument
ok 222 Salti was called with 'thaliIdCallback' as 3-st argument
ok 223 Salti was called with 'options' as 4-st argument
2016-11-29 12:24:37 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-29 12:24:37 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-29 12:24:37 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-29 12:24:37 - DEBUG thaliMobileNativeWrapper: 'listening 50302'
2016-11-29 12:24:37 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:37 - DEBUG createNativeListener: 'listening 50303'
2016-11-29 12:24:37 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-29 12:24:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:24:37 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-29 12:24:37 - DEBUG thaliWifiInfrastructure: 'listening 50305'
2016-11-29 12:24:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-11-29 12:24:37 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
ok 224 ThaliMobile.start was called once
ok 225 ThaliMobile.start was called with 3 arguments
ok 226 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
ok 227 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
ok 228 ThaliMobile.start was called with 'networkType' as 3-st argument
ok 229 ThaliMobile.startListeningForAdvertisements was called once
ok 230 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
ok 231 ThaliMobile.startUpdateAdvertisingAndListening was called once
ok 232 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
ok 233 ThaliSendNotificationBasedOnReplication.prototype.start was called once
ok 234 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
ok 235 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
ok 236 ThaliPullReplicationFromNotification.prototype.start was called once
ok 237 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
ok 238 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
2016-11-29 12:24:37 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-29 12:24:37 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-29 12:24:37 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-29 12:24:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:37 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-29 12:24:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:24:37 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-29 12:24:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:24:37 - DEBUG thaliManager: 'stopping ThaliMobile'
2016-11-29 12:24:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:37 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 239 ThaliMobile.stop was called once
ok 240 ThaliMobile.stop was called with 0 arguments
ok 241 ThaliMobile.stopListeningForAdvertisements was called once
ok 242 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
ok 243 ThaliMobile.stopAdvertisingAndListening was called once
ok 244 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
ok 245 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
ok 246 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
ok 247 ThaliPullReplicationFromNotification.prototype.stop was called once
ok 248 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
2016-11-29 12:24:37 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-29 12:24:37 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-29 12:24:37 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-29 12:24:37 - DEBUG thaliMobileNativeWrapper: 'listening 50306'
2016-11-29 12:24:37 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:37 - DEBUG createNativeListener: 'listening 50307'
2016-11-29 12:24:37 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-29 12:24:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:24:37 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-29 12:24:37 - DEBUG thaliWifiInfrastructure: 'listening 50309'
2016-11-29 12:24:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-11-29 12:24:37 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
2016-11-29 12:24:37 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-29 12:24:37 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-29 12:24:37 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-29 12:24:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:37 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-29 12:24:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:24:37 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-29 12:24:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:24:37 - DEBUG thaliManager: 'stopping ThaliMobile'
2016-11-29 12:24:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:37 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:37 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-29 12:24:37 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-29 12:24:37 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-29 12:24:37 - DEBUG thaliMobileNativeWrapper: 'listening 50310'
2016-11-29 12:24:37 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:37 - DEBUG createNativeListener: 'listening 50311'
2016-11-29 12:24:37 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-29 12:24:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:24:37 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-29 12:24:37 - DEBUG thaliWifiInfrastructure: 'listening 50313'
2016-11-29 12:24:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-11-29 12:24:37 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
2016-11-29 12:24:37 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-29 12:24:37 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-29 12:24:37 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-29 12:24:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:37 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-29 12:24:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:24:37 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-29 12:24:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:24:37 - DEBUG thaliManager: 'stopping ThaliMobile'
2016-11-29 12:24:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:37 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:37 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-29 12:24:37 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-29 12:24:37 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-29 12:24:37 - DEBUG thaliMobileNativeWrapper: 'listening 50314'
2016-11-29 12:24:37 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:37 - DEBUG createNativeListener: 'listening 50315'
2016-11-29 12:24:37 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-29 12:24:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:24:37 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-29 12:24:37 - DEBUG thaliWifiInfrastructure: 'listening 50317'
2016-11-29 12:24:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-11-29 12:24:37 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
ok 249 ThaliMobile.start was called once
ok 250 ThaliMobile.start was called with 3 arguments
ok 251 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
ok 252 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
ok 253 ThaliMobile.start was called with 'networkType' as 3-st argument
ok 254 ThaliMobile.startListeningForAdvertisements was called once
ok 255 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
ok 256 ThaliMobile.startUpdateAdvertisingAndListening was called once
ok 257 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
ok 258 ThaliSendNotificationBasedOnReplication.prototype.start was called once
ok 259 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
ok 260 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
ok 261 ThaliPullReplicationFromNotification.prototype.start was called once
ok 262 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
ok 263 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
2016-11-29 12:24:38 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-29 12:24:38 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-29 12:24:38 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:24:38 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:24:38 - DEBUG thaliManager: 'stopping ThaliMobile'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
# setup
# #startListeningForAdvertisements should fail if start not called
ok 264 specific error should be returned
# teardown
ok 265 error should be null
ok 266 error should be null
# setup
# #startUpdateAdvertisingAndListening should fail if start not called
ok 267 specific error should be returned
# teardown
ok 268 error should be null
ok 269 error should be null
# setup
# should be able to call #stopListeningForAdvertisements many times
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'listening 50318'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'listening 50319'
ok 270 error should be null
ok 271 error should be null
ok 272 error should be null
ok 273 error should be null
# teardown
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 274 error should be null
ok 275 error should be null
# setup
# should be able to call #startListeningForAdvertisements many times
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'listening 50320'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'listening 50321'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 276 error should be null
ok 277 error should be null
ok 278 error should be null
ok 279 error should be null
# teardown
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:24:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 280 error should be null
ok 281 error should be null
# setup
# should be able to call #startUpdateAdvertisingAndListening many times
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'listening 50322'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'listening 50323'
2016-11-29 12:24:38 - DEBUG thaliWifiInfrastructure: 'listening 50325'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 282 error should be null
ok 283 error should be null
ok 284 error should be null
ok 285 error should be null
# teardown
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:24:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 286 error should be null
ok 287 error should be null
# setup
# should be able to call #stopAdvertisingAndListening many times
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'listening 50326'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'listening 50327'
ok 288 error should be null
ok 289 error should be null
ok 290 error should be null
ok 291 error should be null
# teardown
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 292 error should be null
ok 293 error should be null
# setup
# #start should fail if called twice in a row
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'listening 50328'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'listening 50329'
ok 294 first call should succeed
ok 295 first call should succeed
ok 296 specific error should be returned
# teardown
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 297 error should be null
ok 298 error should be null
# setup
# #stop should clear watchers and change peers
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'listening 50330'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'listening 50331'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"urn:uuid:7cd312dd-7854-4370-b3ee-4b9de8282ffb","peerAvailable":true}'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'creating new server for urn:uuid:7cd312dd-7854-4370-b3ee-4b9de8282ffb'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for urn:uuid:7cd312dd-7854-4370-b3ee-4b9de8282ffb listening on 50332'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"urn:uuid:7cd312dd-7854-4370-b3ee-4b9de8282ffb","portNumber":50332}'
2016-11-29 12:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"urn:uuid:7cd312dd-7854-4370-b3ee-4b9de8282ffb","hostAddress":"127.0.0.1","portNumber":50332,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
ok 299 Watchers have one entry for our connection type
ok 300 Peer availabilities has one entry for our connection type
2016-11-29 12:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"urn:uuid:7cd312dd-7854-4370-b3ee-4b9de8282ffb","hostAddress":null,"portNumber":null,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:24:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for urn:uuid:7cd312dd-7854-4370-b3ee-4b9de8282ffb'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 301 No watchers
ok 302 No peers
ok 303 No watchers
ok 304 No peers
ok 305 No watchers
ok 306 No peers
# teardown
ok 307 error should be null
ok 308 error should be null
# setup
# does not emit duplicate discoveryAdvertisingStateUpdate
2016-11-29 12:24:38 - DEBUG SimpleThaliTape: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
# teardown
ok 309 error should be null
ok 310 error should be null
# setup
# does not send duplicate availability changes
2016-11-29 12:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"dummy","hostAddress":"127.0.0.1","portNumber":8080,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
ok 311 should be called once
ok 312 should not have been called more than once
# teardown
2016-11-29 12:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"dummy","hostAddress":null,"portNumber":null,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
ok 313 error should be null
ok 314 error should be null
# setup
# can get the network status
ok 315 network status should have certain non-empty properties
# teardown
ok 316 error should be null
ok 317 error should be null
# setup
# wifi peer is marked unavailable if announcements stop
2016-11-29 12:24:38 - DEBUG SimpleThaliTape: 'test was skipped, name: 'wifi peer is marked unavailable if announcements stop''
# teardown
ok 318 error should be null
ok 319 error should be null
# setup
# network changes emitted correctly
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'listening 50333'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'listening 50334'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":null,"ssidName":null}'
ok 320 wifi should be off
ok 321 bssid should be null
ok 322 ssid should be null
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
ok 323 wifi should be on
ok 324 bssid should be valid
ok 325 ssid should exist
# teardown
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 326 error should be null
ok 327 error should be null
# setup
# network changes not emitted in started state
ok 328 event should not be emitted
# teardown
ok 329 error should be null
ok 330 error should be null
# setup
# network changes not emitted in stopped state
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'listening 50335'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'listening 50336'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":null,"ssidName":null}'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 331 event should not be emitted
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'listening 50337'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'listening 50338'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
ok 332 error should be null
ok 333 error should be null
# setup
# calls correct starts when network changes
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'listening 50339'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'listening 50340'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":null,"ssidName":null}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:24:38 - DEBUG thaliWifiInfrastructure: 'listening 50342'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
ok 334 startListeningForAdvertisements should have been called
ok 335 startUpdateAdvertisingAndListening should have been called
# teardown
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:24:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-29 12:24:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:24:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 336 error should be null
ok 337 error should be null
# setup
# peer is marked unavailable if port number changes
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'listening 50343'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'listening 50344'
2016-11-29 12:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"urn:uuid:2bbc799a-6c5b-4278-81f0-eafe28d00887","hostAddress":"127.0.0.1","portNumber":8080,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
ok 338 peer should have a non-empty identifier
ok 339 peer should have a non-empty host address
ok 340 peer should have port number
ok 341 peer should have suggested timeout
ok 342 peer should have a connection type
ok 343 connection type should match one of the pre-defined types
2016-11-29 12:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"urn:uuid:2bbc799a-6c5b-4278-81f0-eafe28d00887","hostAddress":null,"portNumber":null,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
ok 344 peer should have a non-empty identifier
ok 345 host address should be null
ok 346 port number should be null
ok 347 peer should have suggested timeout
ok 348 peer should have a connection type
ok 349 connection type should match one of the pre-defined types
2016-11-29 12:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"urn:uuid:2bbc799a-6c5b-4278-81f0-eafe28d00887","hostAddress":"127.0.0.1","portNumber":8081,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
ok 350 port number must match
ok 351 peer should have a non-empty identifier
ok 352 peer should have a non-empty host address
ok 353 peer should have port number
ok 354 peer should have suggested timeout
ok 355 peer should have a connection type
ok 356 connection type should match one of the pre-defined types
# teardown
2016-11-29 12:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"urn:uuid:2bbc799a-6c5b-4278-81f0-eafe28d00887","hostAddress":null,"portNumber":null,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 357 error should be null
ok 358 error should be null
# setup
# when network connection is lost a peer should be marked unavailable
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'listening 50345'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'listening 50346'
2016-11-29 12:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"urn:uuid:fb8a2764-6d58-4ee4-9b9c-51e9f12c0b6a","hostAddress":"127.0.0.1","portNumber":8080,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:24:38 - INFO testUtils: 'Toggling radios to: false'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"off","bluetoothLowEnergy":"on","cellular":"on","bssidName":null,"ssidName":null}'
2016-11-29 12:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"urn:uuid:fb8a2764-6d58-4ee4-9b9c-51e9f12c0b6a","hostAddress":null,"portNumber":null,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
ok 359 peer should have a non-empty identifier
ok 360 host address should be null
ok 361 port number should be null
ok 362 peer should have suggested timeout
ok 363 peer should have a connection type
ok 364 connection type should match one of the pre-defined types
2016-11-29 12:24:38 - INFO testUtils: 'Toggling radios to: true'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":null,"ssidName":null}'
# teardown
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 365 error should be null
ok 366 error should be null
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
# setup
# We properly fire peer unavailable and then available when connection fails
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'listening 50347'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'listening 50348'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"urn:uuid:59da536c-0834-4f63-91dd-135687ffc054","peerAvailable":true}'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'creating new server for urn:uuid:59da536c-0834-4f63-91dd-135687ffc054'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for urn:uuid:59da536c-0834-4f63-91dd-135687ffc054 listening on 50349'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"urn:uuid:59da536c-0834-4f63-91dd-135687ffc054","portNumber":50349}'
2016-11-29 12:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"urn:uuid:59da536c-0834-4f63-91dd-135687ffc054","hostAddress":"127.0.0.1","portNumber":50349,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
ok 367 peerIds match
ok 368 peer has a portNumber
ok 369 peer has a host address
ok 370 We should have connected
2016-11-29 12:24:38 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - urn:uuid:59da536c-0834-4f63-91dd-135687ffc054 - 0 - got a new incoming connection'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'Issuing callNative for urn:uuid:59da536c-0834-4f63-91dd-135687ffc054'
2016-11-29 12:24:38 - WARN createPeerListener: 'callNative for urn:uuid:59da536c-0834-4f63-91dd-135687ffc054 failed with Connection could not be established'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - urn:uuid:59da536c-0834-4f63-91dd-135687ffc054 - 0 - finish'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'We are emitting failedConnection with error Error: Connection could not be established and peerIdentifier urn:uuid:59da536c-0834-4f63-91dd-135687ffc054'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"urn:uuid:59da536c-0834-4f63-91dd-135687ffc054","portNumber":null,"recreated":true}'
ok 371 Failed on right peer
ok 372 Marked as recreated
2016-11-29 12:24:38 - DEBUG createPeerListener: 'Will try to recreate server for urn:uuid:59da536c-0834-4f63-91dd-135687ffc054'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for urn:uuid:59da536c-0834-4f63-91dd-135687ffc054'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"urn:uuid:59da536c-0834-4f63-91dd-135687ffc054","portNumber":null,"recreated":true}'
2016-11-29 12:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"urn:uuid:59da536c-0834-4f63-91dd-135687ffc054","hostAddress":null,"portNumber":null,"connectionType":"MPCF","suggestedTCPTimeout":5000,"recreated":true}'
ok 373 still same peer IDs
ok 374 peer should not have a portNumber
ok 375 peer should not have a host address
2016-11-29 12:24:38 - DEBUG createPeerListener: 'creating new server for urn:uuid:59da536c-0834-4f63-91dd-135687ffc054'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for urn:uuid:59da536c-0834-4f63-91dd-135687ffc054 listening on 50351'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier urn:uuid:59da536c-0834-4f63-91dd-135687ffc054 and portNumber 50351'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'listenerRecreatedAfterFailureHandler - We are emitting nonTCPPeerAvailabilityChangedEvent with peerIdentifier urn:uuid:59da536c-0834-4f63-91dd-135687ffc054 and portNumber 50351'
2016-11-29 12:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"urn:uuid:59da536c-0834-4f63-91dd-135687ffc054","hostAddress":"127.0.0.1","portNumber":50351,"connectionType":"MPCF","suggestedTCPTimeout":5000,"recreated":true}'
ok 376 peerIds match again
ok 377 peer has a portNumber again
ok 378 peer has a host address again
ok 379 We got the error we expected
2016-11-29 12:24:38 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - urn:uuid:59da536c-0834-4f63-91dd-135687ffc054 - 0 - close'
# teardown
2016-11-29 12:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"urn:uuid:59da536c-0834-4f63-91dd-135687ffc054","hostAddress":null,"portNumber":null,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:24:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for urn:uuid:59da536c-0834-4f63-91dd-135687ffc054'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 380 error should be null
ok 381 error should be null
# setup
# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'listening 50352'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'listening 50353'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'creating new server for urn:uuid:d276754d-58b8-4753-a236-3ea65ce3f04d'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for urn:uuid:d276754d-58b8-4753-a236-3ea65ce3f04d listening on 50354'
ok 382 We should have connected
2016-11-29 12:24:38 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - urn:uuid:d276754d-58b8-4753-a236-3ea65ce3f04d - 0 - got a new incoming connection'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'Issuing callNative for urn:uuid:d276754d-58b8-4753-a236-3ea65ce3f04d'
2016-11-29 12:24:38 - WARN createPeerListener: 'callNative for urn:uuid:d276754d-58b8-4753-a236-3ea65ce3f04d failed with Connection could not be established'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - urn:uuid:d276754d-58b8-4753-a236-3ea65ce3f04d - 0 - finish'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'We are emitting failedConnection with error Error: Connection could not be established and peerIdentifier urn:uuid:d276754d-58b8-4753-a236-3ea65ce3f04d'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"urn:uuid:d276754d-58b8-4753-a236-3ea65ce3f04d","portNumber":null,"recreated":true}'
ok 383 Failed on right peer
ok 384 Marked as recreated
2016-11-29 12:24:38 - DEBUG createPeerListener: 'Will try to recreate server for urn:uuid:d276754d-58b8-4753-a236-3ea65ce3f04d'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for urn:uuid:d276754d-58b8-4753-a236-3ea65ce3f04d'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"urn:uuid:d276754d-58b8-4753-a236-3ea65ce3f04d","portNumber":null,"recreated":true}'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'creating new server for urn:uuid:d276754d-58b8-4753-a236-3ea65ce3f04d'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for urn:uuid:d276754d-58b8-4753-a236-3ea65ce3f04d listening on 50356'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier urn:uuid:d276754d-58b8-4753-a236-3ea65ce3f04d and portNumber 50356'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'listenerRecreatedAfterFailureHandler - We are emitting nonTCPPeerAvailabilityChangedEvent with peerIdentifier urn:uuid:d276754d-58b8-4753-a236-3ea65ce3f04d and portNumber 50356'
ok 385 Peer still matches
ok 386 We got the connection error
2016-11-29 12:24:38 - WARN createPeerListener: 'Got error trying to restart listener for peer urn:uuid:d276754d-58b8-4753-a236-3ea65ce3f04d after failure TypeError: Cannot call method 'catch' of undefined'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - urn:uuid:d276754d-58b8-4753-a236-3ea65ce3f04d - 0 - close'
# teardown
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:24:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for urn:uuid:d276754d-58b8-4753-a236-3ea65ce3f04d'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 387 error should be null
ok 388 error should be null
# setup
# Can call start/stopListeningForAdvertisements
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:24:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-29 12:24:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 389 Can call startListeningForAdvertisements without error
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:24:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 390 Can call stopListeningForAdvertisements without error
# teardown
ok 391 Should be able to call stopListeningForAdvertisements in teardown
ok 392 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Calling startListeningForAdvertisements twice is NOT an error
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:24:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-29 12:24:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 393 Can call startListeningForAdvertisements without error
ok 394 Can call startListeningForAdvertisements twice without error
# teardown
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:24:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 395 Should be able to call stopListeningForAdvertisements in teardown
ok 396 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Calling stopListeningForAdvertisements without calling start is NOT an error
ok 397 Can call stopListeningForAdvertisements without error
ok 398 Can call stopListeningForAdvertisements without error
# teardown
ok 399 Should be able to call stopListeningForAdvertisements in teardown
ok 400 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Can call start/stopUpdateAdvertisingAndListening
2016-11-29 12:24:38 - DEBUG thaliWifiInfrastructure: 'listening 50358'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2016-11-29 12:24:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-29 12:24:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 401 Can call startUpdateAdvertisingAndListening without error
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:24:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 402 Can call stopAdvertisingAndListening without error
# teardown
ok 403 Should be able to call stopListeningForAdvertisements in teardown
ok 404 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Calling startUpdateAdvertisingAndListening twice is NOT an error
2016-11-29 12:24:38 - DEBUG thaliWifiInfrastructure: 'listening 50360'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2016-11-29 12:24:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-29 12:24:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 405 Can call startUpdateAdvertisingAndListening without error
ok 406 Can call startUpdateAdvertisingAndListening twice without error
# teardown
ok 407 Should be able to call stopListeningForAdvertisements in teardown
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:24:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 408 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
ok 409 Can call startUpdateAdvertisingAndListening without error
ok 410 Can call stopAdvertisingAndListening without error
# teardown
ok 411 Should be able to call stopListeningForAdvertisements in teardown
ok 412 Should be able to call stopAdvertisingAndListening in teardown
# setup
# cannot call connect when start listening for advertisements is not active
ok 413 got right error
# teardown
ok 414 Should be able to call stopListeningForAdvertisements in teardown
ok 415 Should be able to call stopAdvertisingAndListening in teardown
# setup
# #startListeningForAdvertisements should fail if start not called
ok 416 specific error should be returned
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 417 must be stopped
# setup
# #startUpdateAdvertisingAndListening should fail if start not called
ok 418 specific error should be returned
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 419 must be stopped
# setup
# should be able to call #stopListeningForAdvertisements many times
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'listening 50361'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'listening 50362'
ok 420 no errors
ok 421 still no errors
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 422 must be stopped
# setup
# should be able to call #startListeningForAdvertisements many times
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'listening 50363'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'listening 50364'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:24:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-29 12:24:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 423 no errors
ok 424 still no errors
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:24:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 425 must be stopped
# setup
# should be able to call #startUpdateAdvertisingAndListening many times
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'listening 50365'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'listening 50366'
2016-11-29 12:24:38 - DEBUG thaliWifiInfrastructure: 'listening 50368'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2016-11-29 12:24:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-29 12:24:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 426 no errors
ok 427 still no errors
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:24:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 428 must be stopped
# setup
# should be able to call #stopAdvertisingAndListening many times
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'listening 50369'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'listening 50370'
ok 429 no errors
ok 430 still no errors
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 431 must be stopped
# setup
# can get the network status before starting
ok 432 network status should have certain non-empty properties
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 433 must be stopped
# setup
# error returned with bad router
2016-11-29 12:24:38 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 434 specific error expected
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 435 must be stopped
# setup
# all services are stopped when we call stop
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'listening 50371'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'listening 50372'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:24:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-29 12:24:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:24:38 - DEBUG thaliWifiInfrastructure: 'listening 50374'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-11-29 12:24:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-29 12:24:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
ok 436 connection to servers manager should succeed after starting
2016-11-29 12:24:38 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
ok 437 connection to router server should succeed after starting
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:24:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-29 12:24:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:24:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 438 is stopped after calling stop
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
ok 439 connection to servers manager should fail after stopping
ok 440 connection to router server should fail after stopping
# teardown
ok 441 must be stopped
# setup
# make sure terminateConnection is properly hooked up
ok 442 called with right arguments
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 443 must be stopped
# setup
# make sure terminateListener is properly hooked up
ok 444 called with right arguments
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 445 must be stopped
# setup
# make sure we actually call kill connections properly
ok 446 specific error expected
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 447 must be stopped
# setup
# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'listening 50379'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'listening 50380'
2016-11-29 12:24:38 - INFO thaliMobileNativeWrapper: 'routerPortConnectionFailed - {"routerPort":50379,"error":{}}'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 448 failure reason is as expected
ok 449 error description is as expected
ok 450 must be stopped
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 451 must be stopped
# setup
# We repeat failedConnection event when we get it from thaliTcpServersManager
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'listening 50381'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'listening 50382'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"some-identifier","portNumber":null}'
ok 452 peerIdentifier matches
ok 453 error description matches
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"some-identifier","portNumber":null}'
2016-11-29 12:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"some-identifier","hostAddress":null,"portNumber":null,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 454 must be stopped
# setup
# can do HTTP requests between peers without coordinator
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'listening 50383'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'listening 50384'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:24:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-29 12:24:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:24:38 - DEBUG thaliWifiInfrastructure: 'listening 50386'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-11-29 12:24:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-29 12:24:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerIdentifier":"foo","peerAvailable":true}]'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"foo","peerAvailable":true}'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'creating new server for foo'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for foo listening on 50387'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"foo","portNumber":50387}'
2016-11-29 12:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","hostAddress":"127.0.0.1","portNumber":50387,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:24:38 - DEBUG testUtils: 'We got a peer {"peerIdentifier":"foo","portNumber":50387,"hostAddress":"127.0.0.1"}'
2016-11-29 12:24:38 - WARN testUtils: 'Retry count for getSamePeerWithRetry is 1'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - foo - 0 - got a new incoming connection'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'Issuing callNative for foo'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:24:38 - DEBUG wifiBasedNativeMock: 'proxy socket connected'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'callNative for foo connected'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID foo'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 455 Should only get expected id
2016-11-29 12:24:38 - DEBUG testUtils: 'Got response data'
2016-11-29 12:24:38 - DEBUG testUtils: 'Got end'
ok 456 response body should match testData
# teardown
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - foo - finish'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:24:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-29 12:24:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:24:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for foo'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 457 must be stopped
2016-11-29 12:24:38 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  foo - 0 - close'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - foo - finish'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - foo - 0 - close'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - foo - close'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - foo - close'
# setup
# make sure bad PSK connections fail
ok 458 FIX ME, PLEASE!!!
2016-11-29 12:24:38 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 459 must be stopped
# setup
# peer changes handled from a queue
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'listening 50394'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'listening 50395'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerIdentifier":"1","peerAvailable":true},{"peerIdentifier":"2","peerAvailable":true},{"peerIdentifier":"3","peerAvailable":true},{"peerIdentifier":"4","peerAvailable":true},{"peerIdentifier":"5","peerAvailable":true},{"peerIdentifier":"6","peerAvailable":true},{"peerIdentifier":"7","peerAvailable":true},{"peerIdentifier":"8","peerAvailable":true},{"peerIdentifier":"9","peerAvailable":true},{"peerIdentifier":"10","peerAvailable":true}]'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"1","peerAvailable":true}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"2","peerAvailable":true}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3","peerAvailable":true}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"4","peerAvailable":true}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"5","peerAvailable":true}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"6","peerAvailable":true}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"7","peerAvailable":true}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"8","peerAvailable":true}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9","peerAvailable":true}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"10","peerAvailable":true}'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'creating new server for 1'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for 1 listening on 50396'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1","portNumber":50396}'
2016-11-29 12:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1","hostAddress":"127.0.0.1","portNumber":50396,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'creating new server for 2'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for 2 listening on 50397'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2","portNumber":50397}'
2016-11-29 12:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2","hostAddress":"127.0.0.1","portNumber":50397,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'creating new server for 3'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for 3 listening on 50398'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"3","portNumber":50398}'
2016-11-29 12:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3","hostAddress":"127.0.0.1","portNumber":50398,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'creating new server for 4'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for 4 listening on 50399'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"4","portNumber":50399}'
2016-11-29 12:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4","hostAddress":"127.0.0.1","portNumber":50399,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'creating new server for 5'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for 5 listening on 50400'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5","portNumber":50400}'
2016-11-29 12:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5","hostAddress":"127.0.0.1","portNumber":50400,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'creating new server for 6'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for 6 listening on 50401'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"6","portNumber":50401}'
2016-11-29 12:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6","hostAddress":"127.0.0.1","portNumber":50401,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'creating new server for 7'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for 7 listening on 50402'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7","portNumber":50402}'
2016-11-29 12:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7","hostAddress":"127.0.0.1","portNumber":50402,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'creating new server for 8'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for 8 listening on 50403'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"8","portNumber":50403}'
2016-11-29 12:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8","hostAddress":"127.0.0.1","portNumber":50403,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'creating new server for 9'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for 9 listening on 50404'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"9","portNumber":50404}'
2016-11-29 12:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9","hostAddress":"127.0.0.1","portNumber":50404,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'creating new server for 10'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for 10 listening on 50405'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"10","portNumber":50405}'
2016-11-29 12:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"10","hostAddress":"127.0.0.1","portNumber":50405,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
ok 460 peers were handled in the right order
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerIdentifier":"1","peerAvailable":false},{"peerIdentifier":"2","peerAvailable":false},{"peerIdentifier":"3","peerAvailable":false},{"peerIdentifier":"4","peerAvailable":false},{"peerIdentifier":"5","peerAvailable":false},{"peerIdentifier":"6","peerAvailable":false},{"peerIdentifier":"7","peerAvailable":false},{"peerIdentifier":"8","peerAvailable":false},{"peerIdentifier":"9","peerAvailable":false},{"peerIdentifier":"10","peerAvailable":false}]'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"1","peerAvailable":false}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"2","peerAvailable":false}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3","peerAvailable":false}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"4","peerAvailable":false}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"5","peerAvailable":false}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"6","peerAvailable":false}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"7","peerAvailable":false}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"8","peerAvailable":false}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9","peerAvailable":false}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"10","peerAvailable":false}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"1","portNumber":null}'
2016-11-29 12:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1","hostAddress":null,"portNumber":null,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"2","portNumber":null}'
2016-11-29 12:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2","hostAddress":null,"portNumber":null,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"3","portNumber":null}'
2016-11-29 12:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3","hostAddress":null,"portNumber":null,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"4","portNumber":null}'
2016-11-29 12:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4","hostAddress":null,"portNumber":null,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"5","portNumber":null}'
2016-11-29 12:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5","hostAddress":null,"portNumber":null,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"6","portNumber":null}'
2016-11-29 12:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6","hostAddress":null,"portNumber":null,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"7","portNumber":null}'
2016-11-29 12:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7","hostAddress":null,"portNumber":null,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"8","portNumber":null}'
2016-11-29 12:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8","hostAddress":null,"portNumber":null,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"9","portNumber":null}'
2016-11-29 12:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9","hostAddress":null,"portNumber":null,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"10","portNumber":null}'
2016-11-29 12:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"10","hostAddress":null,"portNumber":null,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for 1'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for 2'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for 3'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for 4'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for 5'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for 6'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for 7'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for 8'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for 9'
2016-11-29 12:24:38 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for 10'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 461 must be stopped
# setup
# relaying discoveryAdvertisingStateUpdateNonTCP
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'listening 50406'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'listening 50407'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-11-29 12:24:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-29 12:24:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 462 discovery is active
ok 463 advertising is active
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 464 must be stopped
# setup
# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'listening 50408'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'listening 50409'
2016-11-29 12:24:38 - DEBUG thaliWifiInfrastructure: 'listening 50411'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2016-11-29 12:24:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-29 12:24:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:24:38 - INFO thaliMobileNativeWrapper: 'incomingConnectionToPortNumberFailed: 50409'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:24:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 465 right error reason
ok 466 Stop should be fine
ok 467 same port
ok 468 we should be off
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 469 must be stopped
# setup
# we successfully receive and replay discoveryAdvertisingStateUpdate
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'listening 50412'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'listening 50413'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:24:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-29 12:24:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 470 discoveryActive matches
ok 471 advertisingActive matches
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:24:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 472 discoveryActive matches
ok 473 advertisingActive matches
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'listening 50414'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'listening 50415'
2016-11-29 12:24:38 - DEBUG thaliWifiInfrastructure: 'listening 50417'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2016-11-29 12:24:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-29 12:24:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 474 discoveryActive matches
ok 475 advertisingActive matches
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:24:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 476 discoveryActive matches
ok 477 advertisingActive matches
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'listening 50418'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'listening 50419'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-29 12:24:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:38 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 478 must be stopped
# setup
# Test BEACONS_RETRIEVED_AND_PARSED locally
ok 479 peerIdentifier should be identifier
ok 480 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 481 good beacon
ok 482 good preAmble
ok 483 public keys match!
ok 484 must return null after successful call
ok 485 Once start returns the action should be in KILLED state
# teardown
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test HTTP_BAD_RESPONSE locally
ok 486 Response should be HTTP_BAD_RESPONSE
ok 487 must return null after successful call
# teardown
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test NETWORK_PROBLEM locally
ok 488 Response should be NETWORK_PROBLEM
ok 489 reject reason should be: Could not establish TCP connection
# teardown
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Call the start two times
ok 490 Call start once
ok 491 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 492 must return null after successful call.
# teardown
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Call the kill before calling the start
ok 493 Should be Killed
ok 494 Start after killed
# teardown
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Call the kill immediately after the start
ok 495 Should be KILLED
ok 496 must return null after successful kill
# teardown
2016-11-29 12:24:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Call the kill while waiting a response from the server
ok 497 Should be KILLED
ok 498 must return null after successful kill
# teardown
2016-11-29 12:24:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test to exceed the max content size locally
ok 499 HTTP_BAD_RESPONSE should be response when content size is exceeded
ok 500 must return null after successful call
# teardown
2016-11-29 12:24:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Close the server socket while the client is waiting a response from the server. Local test.
2016-11-29 12:24:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 501 Should be NETWORK_PROBLEM caused closing server socket
ok 502 Should be Could not establish TCP connection
# teardown
# setup
# Close the client socket while the client is waiting a response from the server. Local test.
ok 503 Should be NETWORK_PROBLEM caused closing client socket
ok 504 Should be Could not establish TCP connection
# teardown
2016-11-29 12:24:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #generatePreambleAndBeacons bad args
ok 505 publicKeysToNotify cannot be null
ok 506 ecdh for local device cannot be null
ok 507 milliseconds cannot be less than 0
ok 508 milliseconds cannot be 0
ok 509 milliseconds cannot be greater than one_day
# teardown
# setup
# #generatePreambleAndBeacons empty keys to notify
ok 510 should be equal
# teardown
# setup
# #generatePreambleAndBeacons multiple keys to notify
ok 511 should be equal
ok 512 should be equal
ok 513 (unnamed assert)
ok 514 should be equal
# teardown
# setup
# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
ok 515 should throw
# teardown
# setup
# #parseBeacons invalid expiration in beaconStreamWithPreAmble
ok 516 Preamble expiration must be a 64 bit integer
# teardown
# setup
# #parseBeacons expiration out of range lower
ok 517 Expiration out of range
# teardown
# setup
# #parseBeacons expiration out of range lower
ok 518 Expiration out of range
# teardown
# setup
# #parseBeacons no beacons returns null
ok 519 should be equal
# teardown
# setup
# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
ok 520 Malformed encrypted beacon key ID
# teardown
# setup
# #parseBeacons addressBookCallback fails decrypt
ok 521 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns no matches
ok 522 should be equal
ok 523 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns spurious match
ok 524 should be equal
ok 525 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns public key
ok 526 right number of calls to address book
ok 527 good preAmble
ok 528 good unencryptedKeyId
ok 529 good beacon
# teardown
# setup
# validate generatePskIdentityField
ok 530 decoded buffers match
# teardown
# setup
# validate generatePskSecret
ok 531 secrets match
# teardown
# setup
# validate generatePskSecrets
ok 532 Matching numbers
ok 533 We have an entry!
ok 534 keys match
ok 535 secrets match
ok 536 We have an entry!
ok 537 keys match
ok 538 secrets match
ok 539 We have an entry!
ok 540 keys match
ok 541 secrets match
# teardown
# setup
# validate generateBeaconStreamAndSecrets
ok 542 Streams have same length
ok 543 matching size
ok 544 keys match
ok 545 secrets match
# teardown
# setup
# Add two Peers.
ok 546 should be equal
ok 547 should be equal
ok 548 should be equal
ok 549 should be equal
ok 550 should be equal
# teardown
2016-11-29 12:24:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# TCP_NATIVE peer loses DNS
ok 551 should be equal
ok 552 should be equal
# teardown
2016-11-29 12:24:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Received beacons with no values for us
ok 553 entry exists
ok 554 entry is resolved
# teardown
2016-11-29 12:24:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Notification action killed with a superseded
ok 555 Action should be killed
ok 556 should be equal
# teardown
2016-11-29 12:24:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Resolves an action locally
ok 557 Host address must match
ok 558 suggestedTCPTimeout must match
ok 559 connectionType must match
ok 560 portNumber must match
ok 561 peerIDs must match
# teardown
2016-11-29 12:24:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Resolves an action locally using ThaliPeerPoolDefault
ok 562 Host address must match
ok 563 suggestedTCPTimeout must match
ok 564 connectionType must match
ok 565 portNumber must match
ok 566 peerIds must match
# teardown
2016-11-29 12:24:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Action fails because of a bad hostname.
2016-11-29 12:24:44 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 567 action should be resolved with NETWORK_PROBLEM error
2016-11-29 12:24:45 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 568 action should be resolved with NETWORK_PROBLEM error
2016-11-29 12:24:45 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 569 action should be resolved with NETWORK_PROBLEM error
2016-11-29 12:24:46 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 570 action should be resolved with NETWORK_PROBLEM error
ok 571 correct number of requests
ok 572 correct number of failures
ok 573 correct final peer state
# teardown
2016-11-29 12:24:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# hostaddress is removed when the action is running. 
2016-11-29 12:24:48 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 574 should be equal
# teardown
2016-11-29 12:24:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Client to server request locally
ok 575 secrets are equal
ok 576 Public key matches with the server key
ok 577 Host address must match
ok 578 suggestedTCPTimeout must match
ok 579 connectionType must match
ok 580 portNumber must match
# teardown
2016-11-29 12:24:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test ThaliPskMapCache clean and expiration
ok 581 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
ok 582 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
ok 583 All entries should be expired after 1 second
# teardown
2016-11-29 12:24:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test ThaliPskMapCache getSecret and getPublic
ok 584 All keys need to be available in the cache
ok 585 All entries should be expired after 1 second
# teardown
2016-11-29 12:24:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test ThaliPskMapCache multiple entries
ok 586 Size of the cache should be 2
ok 587 Cache doesn't contain dictionary1
ok 588 Size of the cache should be 1
ok 589 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
2016-11-29 12:24:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Start and stop ThaliNotificationServer
ok 590 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
ok 591 ThaliMobile.StopAdvertisingAndListeningshould be called once
# teardown
2016-11-29 12:24:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Pass an empty array to ThaliNotificationServer.start
ok 592 StartUpdateAdvertisingAndListening should not be called
ok 593 ThaliMobile.StopAdvertisingAndListening should be called once
ok 594 no error
ok 595 should be 204
# teardown
2016-11-29 12:24:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Pass a string to ThaliNotificationServer.start
ok 596 StartUpdateAdvertisingAndListening should not be called
# teardown
2016-11-29 12:24:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Pass an empty parameter to ThaliNotificationServer.start
ok 597 StartUpdateAdvertisingAndListening should not be called
# teardown
2016-11-29 12:24:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make an HTTP request to /NotificationBeacons
ok 598 no error
ok 599 should be 200
ok 600 should be equal
ok 601 should be equal
ok 602 (unnamed assert)
ok 603 no error
ok 604 should be 204
# teardown
2016-11-29 12:24:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make an HTTP request to /NotificationBeacons (no keys)
ok 605 error should be null
ok 606 should be 204
# teardown
2016-11-29 12:24:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make an HTTP request to /NotificationBeaconsbefore calling start
ok 607 should be 404
# teardown
2016-11-29 12:24:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #testThaliPeerAction - test getters
ok 608 getPeerIdentifier
ok 609 getConnectionType
ok 610 getActionType
ok 611 getActionState
ok 612 getPskIdentity
ok 613 getPskKey
# teardown
# setup
# #testThaliPeerAction - start and kill
ok 614 initial state
ok 615 after start
2016-11-29 12:24:52 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 616 after kill
# teardown
# setup
# #testThaliPeerAction - double start
ok 617 should be equal
# teardown
# setup
# #testThaliPeerAction - start after kill
2016-11-29 12:24:52 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 618 clean kill
ok 619 should be equal
# teardown
# setup
# #testThaliPeerAction - make sure ids are unique
ok 620 should not be equal
# teardown
# setup
# #testThaliPeerAction - check that forever agent can be destroyed
ok 621 forever agent should have it's own destroy method
ok 622 agent's destroy should be called
ok 623 agent's destroy should not be called again
ok 624 agent is destroyed
# teardown
# setup
# Test PeerConnectionInformation basics
ok 625 connection type works
ok 626 getHostAddress works
ok 627 getPortNumber works
ok 628 getSuggestedTCPTimeout works
# teardown
# setup
# Test PeerDictionary basic functionality
ok 629 Entry counter must be 1
ok 630 Size must be 1
ok 631 Entry counter must be 2
ok 632 Size must be 2
ok 633 Entry2 should not be found
ok 634 Size must be 1
ok 635 Size must be 0
# teardown
# setup
# Test PeerDictionary with multiple entries.
ok 636 Size must be100
ok 637 Entries between 20 and MAXSIZE + 20 should exist
ok 638 WAITING state entry should not be removed
# teardown
# setup
# RESOLVED entries are removed before WAITING state entry.
ok 639 Entries between 6 and MAXSIZE + 4 should exist
ok 640 Size should be MAXSIZE
ok 641 Size should be MAXSIZE+6
# teardown
# setup
# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
ok 642 WAITING state entry should not be removed
ok 643 Waiting entries between 6 and MAXSIZE + 4 should exist
ok 644 Size should be MAXSIZE
ok 645 entryCounter should be MAXSIZE+6
# teardown
# setup
# When CONTROLLED_BY_POOL entry is removed and kill is called.
ok 646 Kill should be called once
ok 647 Size should be 100
# teardown
# setup
# #ThaliPeerPoolDefault - single action
ok 648 is an agent
ok 649 enqueue is fine
ok 650 Everything should be off the queue
# teardown
# setup
# #ThaliPeerPoolDefault - multiple actions
ok 651 is an agent
ok 652 first enqueue is fine
ok 653 is an agent
ok 654 second enqueue is fine
ok 655 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 656 Queue is empty
# teardown
# setup
# #ThaliPeerPoolDefault - PSK Pool works
ok 657 is an agent
ok 658 good enqueue
ok 659 Identity should match
2016-11-29 12:24:52 - DEBUG testUtils: 'Got response data'
2016-11-29 12:24:52 - DEBUG testUtils: 'Got end'
ok 660 Got expected response
ok 661 Got psk call back
# teardown
2016-11-29 12:24:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #ThaliPeerPoolDefault - stop
ok 662 is an agent
ok 663 enqueue worked
ok 664 is an agent
ok 665 enqueue 2 worked
ok 666 enqueue is not available when stopped
ok 667 start action is killed
ok 668 killed action is still killed
ok 669 inQueue is empty
# teardown
# setup
# #ThaliPeerPoolInterface - make sure that start verifies queue length
ok 670 good start
ok 671 good enqueue
ok 672 queue is not empty
# teardown
# setup
# #ThaliPeerPoolInterface - bad enqueues
ok 673 null arg
ok 674 wrong arg type
ok 675 wrong arg type
# teardown
# setup
# #ThaliPeerPoolInterface - do not allow same object type
ok 676 good enqueue
ok 677 already enqueued
# teardown
# setup
# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
ok 678 good enqueue
ok 679 2nd good enqueue
ok 680 we are in the pool
ok 681 We are out of the pool
ok 682 Action was killed
ok 683 The original kill was called too
ok 684 second item is still in queue
# teardown
# setup
# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
ok 685 good enqueue
ok 686 first kill
ok 687 second NOOP kill
# teardown
# setup
# #ThaliPeerPoolInterface - make sure that stop removes all actions
ok 688 1st good enqueue
ok 689 2nd good enqueue
ok 690 1st action is in the pool
ok 691 2nd action is in the pool
ok 692 1st action is out of the pool
ok 693 2st action is out of the pool
ok 694 pool is empty
# teardown
# setup
# We reject unrecognized connection type
2016-11-29 12:24:53 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 695 Got right error
ok 696 Start should not be called
ok 697 Kill should have been called at least once
# teardown
# setup
# We reject unrecognized action type
2016-11-29 12:24:53 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2016-11-29 12:24:53 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
ok 698 Got right error
ok 699 Start should not be called
ok 700 Kill should have been called at least once
# teardown
# setup
# One action on bluetooth
2016-11-29 12:24:53 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 701 Got null
2016-11-29 12:24:53 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 607, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
ok 702 is an agent
2016-11-29 12:24:53 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 607, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
ok 703 Got killed at least once
# teardown
# setup
# Two notification actions
2016-11-29 12:24:53 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 704 Got Null
ok 705 Got another null
2016-11-29 12:24:53 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 608, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
ok 706 is an agent
2016-11-29 12:24:53 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 608, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
2016-11-29 12:24:53 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 609, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
ok 707 is an agent
ok 708 Action 1 killed at least once
2016-11-29 12:24:53 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 609, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
ok 709 Action 1 went first
ok 710 Action 2 killed at least once
# teardown
# setup
# replicateThroughProblems
2016-11-29 12:24:53 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
2016-11-29 12:24:53 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
2016-11-29 12:24:53 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
ok 711 should have gotten null
2016-11-29 12:24:53 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
2016-11-29 12:24:53 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
ok 712 Should have stopped nicely
2016-11-29 12:24:53 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
2016-11-29 12:24:53 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
ok 713 Still looking for null
2016-11-29 12:24:53 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
2016-11-29 12:24:53 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
2016-11-29 12:24:53 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
2016-11-29 12:24:53 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
2016-11-29 12:24:53 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
2016-11-29 12:24:53 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
ok 714 Yup, another null
ok 715 We cloned!
# teardown
# setup
# Replication goes first
2016-11-29 12:24:53 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 716 Null 1
ok 717 (unnamed assert)
2016-11-29 12:24:53 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 610, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
ok 718 is an agent
ok 719 Null 3
2016-11-29 12:24:53 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 610, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
2016-11-29 12:24:53 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 611, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
ok 720 is an agent
ok 721 Replication not yet called
ok 722 Notification 2 not yet called
2016-11-29 12:24:53 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 611, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
2016-11-29 12:24:53 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
2016-11-29 12:24:53 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 612, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
ok 723 is an agent
ok 724 Notification went first
ok 725 Notification 2 not called yet
2016-11-29 12:24:53 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 612, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
ok 726 Notification finished
ok 727 Replication finished
# teardown
# setup
# wifi allows many parallel non-replication actions
2016-11-29 12:24:53 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2016-11-29 12:24:53 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 613, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
ok 728 is an agent
ok 729 First null
2016-11-29 12:24:53 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 614, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
ok 730 is an agent
ok 731 Second null
2016-11-29 12:24:53 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 614, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
truetruefalsetrue
2016-11-29 12:24:53 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 613, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
truetruetruetrue
# teardown
# setup
# wifi allows no more than 2 simultaneous replication actions for same peerID
2016-11-29 12:24:53 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2016-11-29 12:24:53 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 615, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
ok 732 is an agent
ok 733 First null
2016-11-29 12:24:53 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 616, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
ok 734 is an agent
ok 735 second null
ok 736 third null
2016-11-29 12:24:53 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 615, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
2016-11-29 12:24:53 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 616, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
2016-11-29 12:24:53 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
2016-11-29 12:24:53 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
# teardown
# setup
# Make sure peerDictionaryKey is reasonable
ok 737 equal keys
ok 738 not equal connection type
ok 739 same connection type, different buffer
# teardown
# setup
# Make sure start works
2016-11-29 12:24:53 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 740 First start and on called correctly
# teardown
# setup
# Make sure stop works
ok 741 second cleared dictionary
2016-11-29 12:24:53 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 742 First start and on called correctly
ok 743 First stop and removeListener called correctly
ok 744 first action kill called
ok 745 second action kill called
ok 746 first cleared dictionary
ok 747 first cleared pool
ok 748 second cleared dictionary
ok 749 second cleared pool
# teardown
# setup
# Simple peer event
2016-11-29 12:24:53 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 750 listener has been set
ok 751 peer dictionary has expected number of entries
ok 752 Dictionary and pool have same action
ok 753 ads match
ok 754 PouchDB matches
ok 755 DB Names match
ok 756 public keys match
ok 757 peer dictionary has expected number of entries
ok 758 Dictionary and pool have same action
ok 759 ads match
ok 760 PouchDB matches
ok 761 DB Names match
ok 762 public keys match
2016-11-29 12:24:53 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
ok 763 start called once
ok 764 One entry left
ok 765 Dictionary and pool have same action
ok 766 Start never called
ok 767 Kill called once
ok 768 no entries left
ok 769 Third action is dead
ok 770 peer dictionary has expected number of entries
ok 771 Dictionary and pool have same action
ok 772 ads match
ok 773 PouchDB matches
ok 774 DB Names match
ok 775 public keys match
# teardown
# setup
# Server is not there
2016-11-29 12:24:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:53 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
2016-11-29 12:24:53 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: connect ECONNREFUSED  and it caused us to complete'
ok 776 right error
# teardown
2016-11-29 12:24:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Server accepts & closes connection
2016-11-29 12:24:53 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
2016-11-29 12:24:53 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
ok 777 right error
# teardown
2016-11-29 12:24:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Server always returns 500
2016-11-29 12:24:53 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
2016-11-29 12:24:53 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
ok 778 Got error as expected
# teardown
2016-11-29 12:24:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Server always returns 401
2016-11-29 12:24:53 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
2016-11-29 12:24:53 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
ok 779 Got error as expected
# teardown
2016-11-29 12:24:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Server always returns 403
2016-11-29 12:24:53 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
2016-11-29 12:24:53 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
ok 780 Got error as expected
# teardown
2016-11-29 12:24:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make sure docs replicate
2016-11-29 12:24:53 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
2016-11-29 12:24:53 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
2016-11-29 12:24:53 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
ok 781 should be equal
ok 782 All tests passed!
# teardown
2016-11-29 12:24:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Do nothing and make sure we time out
2016-11-29 12:24:53 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
2016-11-29 12:24:55 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2016-11-29 12:24:55 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
ok 783 action should be killed
ok 784 Error should be timed out
ok 785 No doc found
# teardown
2016-11-29 12:24:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Do something and make sure we time out
2016-11-29 12:24:55 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
2016-11-29 12:24:56 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
ok 786 should be equal
2016-11-29 12:24:57 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2016-11-29 12:24:57 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
ok 787 action should be killed
ok 788 Error should be timed out
# teardown
2016-11-29 12:24:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Start replicating and then catch error when server goes
ok 789 socket hung up
# teardown
2016-11-29 12:24:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make sure clone works
ok 790 same getPeerAdvertisesDataForUs
ok 791 Same pouchdB
ok 792 same dbName
ok 793 Same public key
# teardown
# setup
# compareBufferArrays
ok 794 should throw
ok 795 should throw
ok 796 (unnamed assert)
ok 797 (unnamed assert)
ok 798 (unnamed assert)
ok 799 (unnamed assert)
ok 800 (unnamed assert)
# teardown
# setup
# Call start twice and get error
ok 801 should throw
# teardown
# setup
# Start and make sure it runs
# teardown
# setup
# Make sure getTimeWhenRun is right after start
ok 802 (unnamed assert)
# teardown
# setup
# Make sure getTimeWhenRun is -1 after function is called
ok 803 should be equal
# teardown
# setup
# Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
ok 804 should be equal
ok 805 should be equal
ok 806 should throw
# teardown
# setup
# Test TransientState
ok 807 should throw
ok 808 should throw
ok 809 should be equal
ok 810 should be equal
ok 811 should be equal
ok 812 should be equal
ok 813 (unnamed assert)
ok 814 (unnamed assert)
# teardown
# setup
# No peers and empty database
ok 815 verify failed
ok 816 constructor called once
ok 817 constructor called with right args
ok 818 match start arg
ok 819 start called once
ok 820 stop called once
ok 821 stop after start
# teardown
# setup
# One peer and empty DB
ok 822 verify failed
ok 823 constructor called once
ok 824 constructor called with right args
ok 825 match start arg
ok 826 start called once
ok 827 stop called once
ok 828 stop after start
2016-11-29 12:24:58 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# One peer with _Local set behind current seq
ok 829 verify failed
ok 830 constructor called once
ok 831 constructor called with right args
ok 832 match start arg
ok 833 start called once
ok 834 stop called once
ok 835 stop after start
2016-11-29 12:24:58 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# One peer with _Local set equal to current seq
ok 836 verify failed
ok 837 constructor called once
ok 838 constructor called with right args
ok 839 match start arg
ok 840 start called once
ok 841 stop called once
ok 842 stop after start
2016-11-29 12:24:58 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# One peer with _Local set ahead of current seq (and no this should not happen)
ok 843 verify failed
ok 844 constructor called once
ok 845 constructor called with right args
ok 846 match start arg
ok 847 start called once
ok 848 stop called once
ok 849 stop after start
2016-11-29 12:24:58 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# Three peers, one not in DB, one behind and one ahead
ok 850 verify failed
ok 851 constructor called once
ok 852 constructor called with right args
ok 853 match start arg
ok 854 start called once
ok 855 stop called once
ok 856 stop after start
2016-11-29 12:24:58 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# More than maximum peers, make sure we only send maximum allowed
ok 857 verify failed
ok 858 constructor called once
ok 859 constructor called with right args
ok 860 match start arg
ok 861 start called once
ok 862 stop called once
ok 863 stop after start
2016-11-29 12:24:58 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# two peers with empty DB, update the doc
2016-11-29 12:24:58 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 864 verify failed
ok 865 constructor called once
ok 866 constructor called with right args
ok 867 last start before stop
ok 868 empty first start
ok 869 full second start
ok 870 only 2 timers
2016-11-29 12:24:58 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# add doc and make sure tokens refresh when they expire
2016-11-29 12:24:58 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
2016-11-29 12:24:58 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 871 verify failed
ok 872 constructor called once
ok 873 constructor called with right args
ok 874 start before stop
ok 875 We got at least 3 calls to start
ok 876 at least 3
ok 877 default 1
ok 878 1 run
ok 879 default 2
ok 880 2 run
ok 881 default 3
2016-11-29 12:24:58 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# start and stop and start and stop
ok 882 start out null
ok 883 back to null
2016-11-29 12:24:58 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 884 still null
ok 885 verify failed
ok 886 constructor called once
ok 887 constructor called with right args
ok 888 first start before first stop
ok 889 first stop before second start
ok 890 second start before second stop
2016-11-29 12:24:58 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# two identical starts in a row
ok 891 verify failed
ok 892 constructor called once
ok 893 constructor called with right args
ok 894 (unnamed assert)
2016-11-29 12:24:58 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# two different starts in a row
2016-11-29 12:24:58 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 895 verify failed
ok 896 constructor called once
ok 897 constructor called with right args
ok 898 (unnamed assert)
ok 899 (unnamed assert)
# teardown
# setup
# two stops and a start and two stops
ok 900 verify failed
ok 901 constructor called once
ok 902 constructor called with right args
ok 903 start before stop
2016-11-29 12:24:58 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# we properly enqueue requests so no then needed
2016-11-29 12:24:58 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 904 verify failed
ok 905 constructor called once
ok 906 constructor called with right args
ok 907 start before stop
# teardown
# setup
# test calculateSeqPointKeyId
ok 908 should be equal
ok 909 should be equal
# teardown
# setup
# can create servers manager
ok 910 serversManager must not be null
ok 911 serversManager must be an object
# teardown
# setup
# calling stop without start causes error
ok 912 We need to call start first
# teardown
# setup
# can start/stop servers manager
2016-11-29 12:24:58 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:58 - DEBUG createNativeListener: 'listening 50529'
ok 913 port must be in range
# teardown
2016-11-29 12:24:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:58 - DEBUG createNativeListener: 'Native Server - close'
# setup
# starting twice resolves with listening port
2016-11-29 12:24:58 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:58 - DEBUG createNativeListener: 'listening 50530'
ok 914 second start should return same port
# teardown
2016-11-29 12:24:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:58 - DEBUG createNativeListener: 'Native Server - close'
# setup
# terminateIncomingConnection will terminate a connection
2016-11-29 12:24:58 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:24:58 - DEBUG createNativeListener: 'listening 50532'
2016-11-29 12:24:58 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:24:58 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 915 we should be connected
2016-11-29 12:24:58 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 916 now we are disconnected
2016-11-29 12:24:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
2016-11-29 12:24:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:24:58 - DEBUG createNativeListener: 'Native Server - close'
# setup
# terminate an Outgoing connection
2016-11-29 12:24:58 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
ok 917 Passed bogus id
2016-11-29 12:24:58 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
ok 918 Passed good id but bogus port
2016-11-29 12:24:58 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
ok 919 Passed right context
ok 920 Right server
ok 921 No error should be set
ok 922 Retry should be false
ok 923 We called close server
# teardown
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - emits incomingConnectionState'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - native server connections all up'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - calling createPeerListener without calling start produces error'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - calling createPeerListener after calling stop produces error'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - can call createPeerListener'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - calling createPeerListener twice with same peerIdentifier should return the same port'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - createPeerListener - closing connection to native listener closes everything and triggers new listener'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - createPeerListener - closing mux closes listener and triggers a new listener'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - peerListener - no native server'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - peerListener - with native server'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - peerListener - with native server and data transfer'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - createPeerListener is idempotent'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - createPeerListener - ask for new peer when we are at maximum and make sure we remove the right existing listener'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - createPeerListener - ask for a new peer when we are not at maximum peers and make sure we do not remove any existing listeners'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - createPeerListener - test timeout'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - createPeerListener - multiple connections out'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - createPeerListener - multiple bi-directional connections'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - createPeerListener - multiple parallel calls'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - createPeerListener - we shouldn't create a dead pipe'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - server is not there'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - server accepts & closes connection'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - server always returns 500'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - create new seq doc'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - doc exists, need to get rev and update'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - update seq three times'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - rev got changed under us'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - fail if stop is called'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - stop after get but before put fails right'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #update - fail if stop is called'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #update - set seq for first time'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #update - Fail on bad seq value'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #update - do we cancel timer properly on an immediate?'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #update - do we wait for blocked update'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #update - test that we wait long enough'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #update - test that we pick up new sequences while we wait'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - closeAll with promise'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - closeAll works even with a server that is not listening yet witheatNotRunning set to true'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Call of onCheckpointReached handler on a single db change'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Call of multiple onCheckpointReached handlers on a single db change'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - test defaultDirectory'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - test defaultAdapter'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - enqueue and run in order'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - queues handled independently'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - ssdp server should be restarted when wifi toggled'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - basic'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - another'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - test thali manager spies'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - test thali manager multiple starts and stops'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #start should fail if called twice in a row'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #stop should clear watchers and change peers'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - does not emit duplicate discoveryAdvertisingStateUpdate'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - does not send duplicate availability changes'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - can get the network status'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - wifi peer is marked unavailable if announcements stop'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - network changes emitted correctly'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - network changes not emitted in started state'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - network changes not emitted in stopped state'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - calls correct starts when network changes'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - peer is marked unavailable if port number changes'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - when network connection is lost a peer should be marked unavailable'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - We properly fire peer unavailable and then available when connection fails'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - cannot call connect when start listening for advertisements is not active'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
2016-11-29 12:24:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - can get the network status before starting'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - error returned with bad router'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - all services are stopped when we call stop'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - make sure terminateConnection is properly hooked up'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - make sure terminateListener is properly hooked up'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - make sure we actually call kill connections properly'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - We repeat failedConnection event when we get it from thaliTcpServersManager'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - can do HTTP requests between peers without coordinator'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - make sure bad PSK connections fail'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - peer changes handled from a queue'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - relaying discoveryAdvertisingStateUpdateNonTCP'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - we successfully receive and replay discoveryAdvertisingStateUpdate'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Test BEACONS_RETRIEVED_AND_PARSED locally'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Test HTTP_BAD_RESPONSE locally'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Test NETWORK_PROBLEM locally'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Call the start two times'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Call the kill before calling the start'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Call the kill immediately after the start'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Call the kill while waiting a response from the server'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Test to exceed the max content size locally'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Close the server socket while the client is waiting a response from the server. Local test.'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Close the client socket while the client is waiting a response from the server. Local test.'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons bad args'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons empty keys to notify'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons multiple keys to notify'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #parseBeacons invalid expiration in beaconStreamWithPreAmble'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #parseBeacons no beacons returns null'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback fails decrypt'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns no matches'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns spurious match'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns public key'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - validate generatePskIdentityField'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - validate generatePskSecret'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - validate generatePskSecrets'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - validate generateBeaconStreamAndSecrets'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Add two Peers.'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - TCP_NATIVE peer loses DNS'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Received beacons with no values for us'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Notification action killed with a superseded'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Resolves an action locally'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Resolves an action locally using ThaliPeerPoolDefault'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Action fails because of a bad hostname.'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - hostaddress is removed when the action is running. '
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Client to server request locally'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Test ThaliPskMapCache clean and expiration'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Test ThaliPskMapCache getSecret and getPublic'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Test ThaliPskMapCache multiple entries'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Start and stop ThaliNotificationServer'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Pass an empty array to ThaliNotificationServer.start'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Pass a string to ThaliNotificationServer.start'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Pass an empty parameter to ThaliNotificationServer.start'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons (no keys)'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeaconsbefore calling start'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #testThaliPeerAction - test getters'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #testThaliPeerAction - start and kill'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #testThaliPeerAction - double start'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #testThaliPeerAction - start after kill'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #testThaliPeerAction - make sure ids are unique'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #testThaliPeerAction - check that forever agent can be destroyed'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Test PeerConnectionInformation basics'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Test PeerDictionary basic functionality'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Test PeerDictionary with multiple entries.'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - RESOLVED entries are removed before WAITING state entry.'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - WAITING entries are removed before CONTROLLED_BY_POOL state entry.'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - When CONTROLLED_BY_POOL entry is removed and kill is called.'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - single action'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - multiple actions'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - PSK Pool works'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - stop'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that start verifies queue length'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - bad enqueues'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - do not allow same object type'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure we catch kill and dequeue'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that stop removes all actions'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - We reject unrecognized connection type'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - We reject unrecognized action type'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - One action on bluetooth'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Two notification actions'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - replicateThroughProblems'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Replication goes first'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - wifi allows many parallel non-replication actions'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - wifi allows no more than 2 simultaneous replication actions for same peerID'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Make sure peerDictionaryKey is reasonable'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Make sure start works'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Make sure stop works'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Simple peer event'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Server is not there'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Server accepts & closes connection'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Server always returns 500'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Server always returns 401'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Server always returns 403'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Make sure docs replicate'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Do nothing and make sure we time out'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Do something and make sure we time out'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Start replicating and then catch error when server goes'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Make sure clone works'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - compareBufferArrays'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Call start twice and get error'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Start and make sure it runs'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Make sure getTimeWhenRun is right after start'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Make sure getTimeWhenRun is -1 after function is called'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Test TransientState'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - No peers and empty database'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - One peer and empty DB'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - One peer with _Local set behind current seq'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - One peer with _Local set equal to current seq'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - One peer with _Local set ahead of current seq (and no this should not happen)'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Three peers, one not in DB, one behind and one ahead'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - More than maximum peers, make sure we only send maximum allowed'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - two peers with empty DB, update the doc'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - add doc and make sure tokens refresh when they expire'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - start and stop and start and stop'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - two identical starts in a row'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - two different starts in a row'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - two stops and a start and two stops'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - we properly enqueue requests so no then needed'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - test calculateSeqPointKeyId'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - can create servers manager'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - calling stop without start causes error'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - can start/stop servers manager'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
2016-11-29 12:24:59 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
2016-11-29 12:24:59 - DEBUG SimpleThaliTape: 'all unit tests succeeded, platformName: 'desktop''
2016-11-29 12:24:59 - DEBUG SimpleThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'

1..923
# tests 923
# pass  923

# ok

2016-11-29 12:25:00 - INFO runTests: 'Starting tests. Network type: BOTH. Platform: android'
2016-11-29 12:25:00 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreateNativeListener.js'
2016-11-29 12:25:00 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js'
2016-11-29 12:25:00 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js'
2016-11-29 12:25:00 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
2016-11-29 12:25:01 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
2016-11-29 12:25:01 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testNativeMethod.js'
2016-11-29 12:25:01 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
2016-11-29 12:25:01 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBGenerator.js'
2016-11-29 12:25:01 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPromiseQueue.js'
2016-11-29 12:25:01 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testSSDPServer.js'
2016-11-29 12:25:01 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testTests.js'
2016-11-29 12:25:01 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManager.js'
2016-11-29 12:25:01 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
2016-11-29 12:25:01 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js'
2016-11-29 12:25:01 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNative.js'
2016-11-29 12:25:01 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
2016-11-29 12:25:01 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
2016-11-29 12:25:01 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotification.js'
2016-11-29 12:25:01 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationAction.js'
2016-11-29 12:25:01 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
2016-11-29 12:25:01 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationClient.js'
2016-11-29 12:25:01 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationLocal.js'
2016-11-29 12:25:01 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationServer.js'
2016-11-29 12:25:01 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerAction.js'
2016-11-29 12:25:01 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerDictionary.js'
2016-11-29 12:25:01 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
2016-11-29 12:25:01 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
2016-11-29 12:25:01 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
2016-11-29 12:25:01 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
2016-11-29 12:25:01 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
2016-11-29 12:25:01 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
2016-11-29 12:25:01 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
2016-11-29 12:25:01 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
2016-11-29 12:25:01 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
2016-11-29 12:25:01 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliTcpServersManager.js'
2016-11-29 12:25:01 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
2016-11-29 12:25:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-29 12:25:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-29 12:25:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:25:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-29 12:25:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
TAP version 13
# setup
# calling createNativeListener directly rejects
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'listening 50535'
ok 1 Should throw
# teardown
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - close'
# setup
# emits incomingConnectionState
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'listening 50537'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 2 initial connection state should be CONNECTED
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 3 final connection state should be DISCONNECTED
# teardown
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - close'
# setup
# emits routerPortConnectionFailed
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'listening 50540'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
ok 4 tried to connect to right port
ok 5 failed due to refused connection
ok 6 routerPortConnectionFailed is emitted
# teardown
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# setup
# native server connections all up
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'listening 50544'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
ok 7 Send/recvd #1 should be equal length
ok 8 Send/recvd #1 should be same
ok 9 Send/recvd #2 should be equal length
ok 10 Send/recvd #2 should be same
ok 11 Should be exactly 2 client sockets
# teardown
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# setup
# native server - closing incoming stream cleans outgoing socket
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'listening 50549'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
ok 12 socket shouldn't close until after stream
ok 13 incoming remains open
# teardown
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# setup
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# native server - closing incoming connection cleans outgoing socket
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'listening 50553'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 14 we should not have gotten an error
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 15 socket shouldn't close until after incoming
ok 16 incoming is cleaned up
# teardown
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - close'
# setup
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# native server - closing outgoing socket cleans associated mux stream
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'listening 50557'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
ok 17 stream was closed
ok 18 incoming should survive
ok 19 mux should have no streams
# teardown
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# setup
# native server - closing the whole server cleans everything up
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'listening 50561'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 20 we should not have gotten an error
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 21 Buffers are identical
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 22 native server is nulled out
ok 23 native server should be closed
ok 24 incoming has been removed
ok 25 Incoming should be done
ok 26 The mux object should be closed
ok 27 The mux stream should be closed
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# teardown
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# setup
# native server - we can get a ton of connections and data through and still clean up the server completely
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'listening 50565'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
ok 28 native server is nulled out
ok 29 native server should be closed
ok 30 incoming has been removed
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# teardown
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# native server - simulate mux failure, make sure everything is cleaned up
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'listening 50617'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 31 we should not have gotten an error
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 32 Buffers are identical
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 33 server should be fine
ok 34 server should be open
ok 35 incoming has been removed
ok 36 The mux object should be closed
ok 37 The mux stream should be closed
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# teardown
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - close'
# setup
# native server - timing out the incoming connection cleans everything up
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'listening 50621'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 38 we should not have gotten an error
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 39 Buffers are identical
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 40 server should be fine
ok 41 server should be open
ok 42 incoming has been removed
ok 43 The mux object should be closed
ok 44 The mux stream should be closed
# teardown
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - close'
# setup
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# calling createPeerListener without calling start produces error
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'listening 50626'
# teardown
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# calling createPeerListener after calling stop produces error
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'listening 50629'
# teardown
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# can call createPeerListener
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'listening 50632'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'creating new server for peerId'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peerId listening on 50633'
ok 45 port must be in range
# teardown
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peerId'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# calling createPeerListener twice with same peerIdentifier should return the same port
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'listening 50636'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50637'
ok 46 port values should be the same
# teardown
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - closing connection to native listener closes everything and triggers new listener
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'listening 50640'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'creating new server for peer2'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 50641'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer2 - 0 - got a new incoming connection'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'Issuing callNative for peer2'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'callNative for peer2 connected'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer2'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 47 Data should be of same length and content
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer2 - finish'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer2 - 0 - close'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer2 - finish'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer2 - 0 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer2 - close'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'We are emitting failedConnection with error Error: Outgoing closed, recreating connection and peerIdentifier peer2'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'Will try to recreate server for peer2'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer2 - close'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer2'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'creating new server for peer2'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 50646'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer2 and portNumber 50646'
ok 48 same peer ID
ok 49 different ports
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
# teardown
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer2'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# createPeerListener - closing mux closes listener and triggers a new listener
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'listening 50649'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'creating new server for peer2'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 50650'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer2 - 0 - got a new incoming connection'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'Issuing callNative for peer2'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'callNative for peer2 connected'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer2'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 50 Data should be of same length and content
2016-11-29 12:25:01 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer2 - 0 - close'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer2 - close'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer2 - finish'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer2 - finish'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer2 - 0 - close'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'We are emitting failedConnection with error Error: Outgoing closed, recreating connection and peerIdentifier peer2'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'Will try to recreate server for peer2'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer2 - close'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer2'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'creating new server for peer2'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 50655'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer2 and portNumber 50655'
ok 51 same peer ID
ok 52 different ports
# teardown
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer2'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# setup
# peerListener - no native server
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Creating Native Server'
ok 53 Can call startUpdateAdvertisingAndListening without error
ok 54 Can call startListeningForAdvertisements without error
2016-11-29 12:25:01 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'listening 50658'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50659'
ok 55 peerPort should not be nativePort
2016-11-29 12:25:01 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - finish'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'We are emitting failedConnection with error Error: Cannot Connect To Peer and peerIdentifier peer1'
ok 56 Should not get event until connection is made
ok 57 reason should be as expected
2016-11-29 12:25:01 - DEBUG createPeerListener: 'Will try to recreate server for peer1'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50662'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer1 and portNumber 50662'
# teardown
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
# setup
# peerListener - with native server
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Creating Native Server'
ok 58 Can call startUpdateAdvertisingAndListening without error
ok 59 Can call startListeningForAdvertisements without error
2016-11-29 12:25:01 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'listening 50665'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50666'
ok 60 peerPort != nativePort
2016-11-29 12:25:01 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
ok 61 Should not get unexpected connection
# teardown
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer1 - 0 - close'
# setup
2016-11-29 12:25:01 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# peerListener - with native server and data transfer
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'listening 50671'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50672'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer1 - close'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - close'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 62 Data should be of same length and content
ok 63 Data should be of same length and content
# teardown
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer1 - 0 - close'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:25:01 - WARN createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 -  error Error: read ECONNRESET'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - close'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# setup
2016-11-29 12:25:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer1 - close'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# createPeerListener is idempotent
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Creating Native Server'
ok 64 Can call startUpdateAdvertisingAndListening without error
ok 65 Can call startListeningForAdvertisements without error
2016-11-29 12:25:01 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'listening 50678'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50679'
ok 66 Second call to existing peerListener returns existing port
# teardown
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - ask for new peer when we are at maximum and make sure we remove the right existing listener
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'listening 50682'
# teardown
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - ask for a new peer when we are not at maximum peers and make sure we do not remove any existing listeners
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'listening 50685'
# teardown
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - test timeout
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'listening 50688'
# teardown
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - multiple connections out
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'listening 50691'
# teardown
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - multiple bi-directional connections
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'listening 50694'
# teardown
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - multiple parallel calls
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'listening 50697'
# teardown
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - we shouldn't create a dead pipe
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Creating Native Server'
ok 67 Can call startUpdateAdvertisingAndListening without error
ok 68 Can call startListeningForAdvertisements without error
2016-11-29 12:25:01 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'listening 50700'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50701'
ok 69 peerPort != nativePort
2016-11-29 12:25:01 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
ok 70 Should not get unexpected connection
2016-11-29 12:25:01 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID peer1 with port 50701'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client - is already closed'
ok 71 passed
2016-11-29 12:25:01 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
# teardown
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# setup
# #_doImmediateSeqUpdate - server is not there
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer1 - close'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - close'
2016-11-29 12:25:01 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
2016-11-29 12:25:01 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
ok 72 Got right error
# teardown
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - server accepts & closes connection
2016-11-29 12:25:01 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
ok 73 Got socket hang up
# teardown
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - server always returns 500
2016-11-29 12:25:01 - DEBUG localSeqManager: 'Got an error trying to update seq []'
ok 74 Got 500 as expected
# teardown
2016-11-29 12:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - create new seq doc
ok 75 should be equal
ok 76 revs are equal
# teardown
2016-11-29 12:25:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - doc exists, need to get rev and update
ok 77 should be equal
ok 78 revs are equal
# teardown
2016-11-29 12:25:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - update seq three times
ok 79 should be equal
ok 80 revs are equal
ok 81 should be equal
ok 82 revs are equal
ok 83 should be equal
ok 84 revs are equal
# teardown
2016-11-29 12:25:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - rev got changed under us
2016-11-29 12:25:02 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
ok 85 Our rev is old so we should fail
# teardown
2016-11-29 12:25:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - fail if stop is called
ok 86 confirm stop caused failure
# teardown
2016-11-29 12:25:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - stop after get but before put fails right
2016-11-29 12:25:02 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
ok 87 stop caused us to fail
ok 88 We specifically failed on a stop before put
# teardown
2016-11-29 12:25:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - fail if stop is called
ok 89 failed due to stop
ok 90 failed due to stop
# teardown
2016-11-29 12:25:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - set seq for first time
ok 91 should be equal
# teardown
2016-11-29 12:25:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - Fail on bad seq value
2016-11-29 12:25:02 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
ok 92 Expected bad seq error
# teardown
2016-11-29 12:25:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - do we cancel timer properly on an immediate?
ok 93 Different promises
ok 94 Timer was cancelled
ok 95 should be equal
# teardown
2016-11-29 12:25:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - do we wait for blocked update
ok 96 One go and one blocked
ok 97 All blocked
ok 98 Still blocked
ok 99 should be equal
# teardown
2016-11-29 12:25:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - test that we wait long enough
ok 100 We waited long enough
ok 101 should be equal
# teardown
2016-11-29 12:25:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - test that we pick up new sequences while we wait
ok 102 Should have gotten same timer promise
ok 103 Still same timer promise
ok 104 We waited long enough
ok 105 should be equal
# teardown
2016-11-29 12:25:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# closeAll can close even when connections open
2016-11-29 12:25:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 106 not possible to connect to the server anymore
# teardown
# setup
# closeAll with promise
2016-11-29 12:25:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 107 not possible to connect to the server anymore
# teardown
# setup
# closeAll properly throws when closing a non open server with eatNotRunning set to false
2016-11-29 12:25:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 108 Got the right error
# teardown
# setup
# closeAll works even with a server that is not listening yet witheatNotRunning set to true
2016-11-29 12:25:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
# setup
# Call of onCheckpointReached handler on a single db change
# teardown
# setup
# Call of multiple onCheckpointReached handlers on a single db change
# teardown
# setup
# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
ok 109 the checkpointReached handler should be called once. Called 1 time(s)
# teardown
# setup
# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
# teardown
# setup
# test defaultDirectory
ok 110 should be equal
ok 111 should be equal
ok 112 should be equal
# teardown
# setup
# test defaultAdapter
ok 113 should be equal
ok 114 should be equal
ok 115 should be equal
ok 116 should be equal
ok 117 should be equal
ok 118 should be equal
ok 119 should be equal
ok 120 should be equal
# teardown
# setup
# enqueue and run in order
ok 121 firstPromise setTimeout
ok 122 firstPromise result
ok 123 firstPromise testValue
ok 124 secondPromise setTimeout
ok 125 secondPromise result
ok 126 secondPromise testValue
ok 127 thirdPromise in promise
ok 128 thirdPromise result
ok 129 thirdPromise testValue
# teardown
# setup
# enqueueAtTop and run backwards
ok 130 thirdPromise - first to run
ok 131 thirdPromise - in resolve
ok 132 secondPromise - second to run
ok 133 secondPromise - in catch
ok 134 firstPromise - third to run
ok 135 firstPromise - in then
ok 136 testing promises
# teardown
# setup
# mix enqueue and enqueueAtTop
ok 137 fourth
ok 138 fourth
ok 139 second
ok 140 secondPromise - in then
ok 141 first
ok 142 firstPromise - in catch
ok 143 third
ok 144 thirdPromise - in then
ok 145 testingPromises
# teardown
# setup
# queues handled independently
ok 146 all short operations completed before the long resolves
# teardown
# setup
# ssdp server should be restarted when wifi toggled
2016-11-29 12:25:07 - DEBUG SimpleThaliTape: 'test was skipped, name: 'ssdp server should be restarted when wifi toggled''
# teardown
# setup
# basic
ok 147 sane
# teardown
# setup
# another
ok 148 sane
# teardown
# setup
# test thali manager spies
2016-11-29 12:25:07 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
2016-11-29 12:25:07 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
2016-11-29 12:25:07 - DEBUG thaliManager: 'creating express pouchdb instance'
ok 149 expressPouchDB was called once
ok 150 expressPouchDB was called with 2 arguments
ok 151 expressPouchDB was called with 'PouchDB' as 1-st argument
ok 152 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
ok 153 PouchDB was called once
ok 154 PouchDB was called with 1 arguments
ok 155 PouchDB was called with 'dbName' as 1-st argument
ok 156 ThaliSendNotificationBasedOnReplication was called once
ok 157 ThaliSendNotificationBasedOnReplication was called with 4 arguments
ok 158 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
ok 159 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
ok 160 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
ok 161 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
ok 162 ThaliPullReplicationFromNotification was called once
ok 163 ThaliPullReplicationFromNotification was called with 4 arguments
ok 164 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
ok 165 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
ok 166 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
ok 167 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
ok 168 Salti was called once
ok 169 Salti was called with 4 arguments
ok 170 Salti was called with 'dbName' as 1-st argument
ok 171 Salti was called with 'acl' as 2-st argument
ok 172 Salti was called with 'thaliIdCallback' as 3-st argument
ok 173 Salti was called with 'options' as 4-st argument
2016-11-29 12:25:07 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-29 12:25:07 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-29 12:25:07 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-29 12:25:07 - DEBUG thaliMobileNativeWrapper: 'listening 50779'
2016-11-29 12:25:07 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:07 - DEBUG createNativeListener: 'listening 50780'
2016-11-29 12:25:07 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-29 12:25:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:25:07 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-29 12:25:07 - DEBUG thaliWifiInfrastructure: 'listening 50781'
2016-11-29 12:25:07 - DEBUG thaliWifiInfrastructure: 'listening 50783'
2016-11-29 12:25:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-11-29 12:25:07 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
ok 174 ThaliMobile.start was called once
ok 175 ThaliMobile.start was called with 3 arguments
ok 176 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
ok 177 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
ok 178 ThaliMobile.start was called with 'networkType' as 3-st argument
ok 179 ThaliMobile.startListeningForAdvertisements was called once
ok 180 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
ok 181 ThaliMobile.startUpdateAdvertisingAndListening was called once
ok 182 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
ok 183 ThaliSendNotificationBasedOnReplication.prototype.start was called once
ok 184 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
ok 185 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
ok 186 ThaliPullReplicationFromNotification.prototype.start was called once
ok 187 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
ok 188 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
2016-11-29 12:25:07 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-29 12:25:07 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-29 12:25:07 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-29 12:25:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:07 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-29 12:25:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:25:07 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-29 12:25:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:25:07 - DEBUG thaliManager: 'stopping ThaliMobile'
2016-11-29 12:25:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:07 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 189 ThaliMobile.stop was called once
ok 190 ThaliMobile.stop was called with 0 arguments
ok 191 ThaliMobile.stopListeningForAdvertisements was called once
ok 192 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
ok 193 ThaliMobile.stopAdvertisingAndListening was called once
ok 194 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
ok 195 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
ok 196 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
ok 197 ThaliPullReplicationFromNotification.prototype.stop was called once
ok 198 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
# teardown
# setup
# test thali manager multiple starts and stops
2016-11-29 12:25:07 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
2016-11-29 12:25:07 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
2016-11-29 12:25:07 - DEBUG thaliManager: 'creating express pouchdb instance'
ok 199 expressPouchDB was called once
ok 200 expressPouchDB was called with 2 arguments
ok 201 expressPouchDB was called with 'PouchDB' as 1-st argument
ok 202 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
ok 203 PouchDB was called once
ok 204 PouchDB was called with 1 arguments
ok 205 PouchDB was called with 'dbName' as 1-st argument
ok 206 ThaliSendNotificationBasedOnReplication was called once
ok 207 ThaliSendNotificationBasedOnReplication was called with 4 arguments
ok 208 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
ok 209 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
ok 210 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
ok 211 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
ok 212 ThaliPullReplicationFromNotification was called once
ok 213 ThaliPullReplicationFromNotification was called with 4 arguments
ok 214 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
ok 215 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
ok 216 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
ok 217 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
ok 218 Salti was called once
ok 219 Salti was called with 4 arguments
ok 220 Salti was called with 'dbName' as 1-st argument
ok 221 Salti was called with 'acl' as 2-st argument
ok 222 Salti was called with 'thaliIdCallback' as 3-st argument
ok 223 Salti was called with 'options' as 4-st argument
2016-11-29 12:25:07 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-29 12:25:07 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-29 12:25:07 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-29 12:25:07 - DEBUG thaliMobileNativeWrapper: 'listening 50784'
2016-11-29 12:25:07 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:07 - DEBUG createNativeListener: 'listening 50785'
2016-11-29 12:25:07 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-29 12:25:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:25:07 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-29 12:25:07 - DEBUG thaliWifiInfrastructure: 'listening 50786'
2016-11-29 12:25:07 - DEBUG thaliWifiInfrastructure: 'listening 50788'
2016-11-29 12:25:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-11-29 12:25:07 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
ok 224 ThaliMobile.start was called once
ok 225 ThaliMobile.start was called with 3 arguments
ok 226 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
ok 227 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
ok 228 ThaliMobile.start was called with 'networkType' as 3-st argument
ok 229 ThaliMobile.startListeningForAdvertisements was called once
ok 230 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
ok 231 ThaliMobile.startUpdateAdvertisingAndListening was called once
ok 232 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
ok 233 ThaliSendNotificationBasedOnReplication.prototype.start was called once
ok 234 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
ok 235 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
ok 236 ThaliPullReplicationFromNotification.prototype.start was called once
ok 237 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
ok 238 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
2016-11-29 12:25:07 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-29 12:25:07 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-29 12:25:07 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-29 12:25:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:07 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-29 12:25:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:25:07 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-29 12:25:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:25:07 - DEBUG thaliManager: 'stopping ThaliMobile'
2016-11-29 12:25:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:07 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 239 ThaliMobile.stop was called once
ok 240 ThaliMobile.stop was called with 0 arguments
ok 241 ThaliMobile.stopListeningForAdvertisements was called once
ok 242 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
ok 243 ThaliMobile.stopAdvertisingAndListening was called once
ok 244 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
ok 245 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
ok 246 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
ok 247 ThaliPullReplicationFromNotification.prototype.stop was called once
ok 248 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
2016-11-29 12:25:07 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-29 12:25:07 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-29 12:25:07 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-29 12:25:07 - DEBUG thaliMobileNativeWrapper: 'listening 50789'
2016-11-29 12:25:07 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:07 - DEBUG createNativeListener: 'listening 50790'
2016-11-29 12:25:07 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-29 12:25:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:25:07 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-29 12:25:07 - DEBUG thaliWifiInfrastructure: 'listening 50791'
2016-11-29 12:25:07 - DEBUG thaliWifiInfrastructure: 'listening 50793'
2016-11-29 12:25:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-11-29 12:25:07 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
2016-11-29 12:25:07 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-29 12:25:07 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-29 12:25:07 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-29 12:25:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:07 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:25:08 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:25:08 - DEBUG thaliManager: 'stopping ThaliMobile'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-29 12:25:08 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-29 12:25:08 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'listening 50794'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'listening 50795'
2016-11-29 12:25:08 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:25:08 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-29 12:25:08 - DEBUG thaliWifiInfrastructure: 'listening 50796'
2016-11-29 12:25:08 - DEBUG thaliWifiInfrastructure: 'listening 50798'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-11-29 12:25:08 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
2016-11-29 12:25:08 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-29 12:25:08 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-29 12:25:08 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:25:08 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:25:08 - DEBUG thaliManager: 'stopping ThaliMobile'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-29 12:25:08 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-29 12:25:08 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'listening 50799'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'listening 50800'
2016-11-29 12:25:08 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:25:08 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-29 12:25:08 - DEBUG thaliWifiInfrastructure: 'listening 50801'
2016-11-29 12:25:08 - DEBUG thaliWifiInfrastructure: 'listening 50803'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-11-29 12:25:08 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
ok 249 ThaliMobile.start was called once
ok 250 ThaliMobile.start was called with 3 arguments
ok 251 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
ok 252 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
ok 253 ThaliMobile.start was called with 'networkType' as 3-st argument
ok 254 ThaliMobile.startListeningForAdvertisements was called once
ok 255 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
ok 256 ThaliMobile.startUpdateAdvertisingAndListening was called once
ok 257 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
ok 258 ThaliSendNotificationBasedOnReplication.prototype.start was called once
ok 259 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
ok 260 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
ok 261 ThaliPullReplicationFromNotification.prototype.start was called once
ok 262 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
ok 263 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
2016-11-29 12:25:08 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-29 12:25:08 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-29 12:25:08 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:25:08 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:25:08 - DEBUG thaliManager: 'stopping ThaliMobile'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
# setup
# #startListeningForAdvertisements should fail if start not called
ok 264 specific error should be returned
# teardown
ok 265 error should be null
ok 266 error should be null
# setup
# #startUpdateAdvertisingAndListening should fail if start not called
ok 267 specific error should be returned
# teardown
ok 268 error should be null
ok 269 error should be null
# setup
# should be able to call #stopListeningForAdvertisements many times
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'listening 50804'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'listening 50805'
ok 270 error should be null
ok 271 error should be null
ok 272 error should be null
ok 273 error should be null
# teardown
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 274 error should be null
ok 275 error should be null
# setup
# should be able to call #startListeningForAdvertisements many times
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'listening 50806'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'listening 50807'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 276 error should be null
ok 277 error should be null
ok 278 error should be null
ok 279 error should be null
# teardown
2016-11-29 12:25:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:25:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 280 error should be null
ok 281 error should be null
# setup
# should be able to call #startUpdateAdvertisingAndListening many times
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'listening 50808'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'listening 50809'
2016-11-29 12:25:08 - DEBUG thaliWifiInfrastructure: 'listening 50810'
2016-11-29 12:25:08 - DEBUG thaliWifiInfrastructure: 'listening 50812'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 282 error should be null
ok 283 error should be null
ok 284 error should be null
ok 285 error should be null
# teardown
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:25:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 286 error should be null
ok 287 error should be null
# setup
# should be able to call #stopAdvertisingAndListening many times
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'listening 50813'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'listening 50814'
ok 288 error should be null
ok 289 error should be null
ok 290 error should be null
ok 291 error should be null
# teardown
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 292 error should be null
ok 293 error should be null
# setup
# #start should fail if called twice in a row
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'listening 50815'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'listening 50816'
ok 294 first call should succeed
ok 295 first call should succeed
ok 296 specific error should be returned
# teardown
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 297 error should be null
ok 298 error should be null
# setup
# #stop should clear watchers and change peers
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'listening 50817'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'listening 50818'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"urn:uuid:ce7f1ae7-fcda-47d5-b15b-81f2837869b2","peerAvailable":true}'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'creating new server for urn:uuid:ce7f1ae7-fcda-47d5-b15b-81f2837869b2'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for urn:uuid:ce7f1ae7-fcda-47d5-b15b-81f2837869b2 listening on 50819'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"urn:uuid:ce7f1ae7-fcda-47d5-b15b-81f2837869b2","portNumber":50819}'
2016-11-29 12:25:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"urn:uuid:ce7f1ae7-fcda-47d5-b15b-81f2837869b2","hostAddress":"127.0.0.1","portNumber":50819,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
ok 299 Watchers have one entry for our connection type
ok 300 Peer availabilities has one entry for our connection type
2016-11-29 12:25:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"urn:uuid:ce7f1ae7-fcda-47d5-b15b-81f2837869b2","hostAddress":null,"portNumber":null,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:25:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for urn:uuid:ce7f1ae7-fcda-47d5-b15b-81f2837869b2'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 301 No watchers
ok 302 No peers
ok 303 No watchers
ok 304 No peers
ok 305 No watchers
ok 306 No peers
# teardown
ok 307 error should be null
ok 308 error should be null
# setup
# does not emit duplicate discoveryAdvertisingStateUpdate
2016-11-29 12:25:08 - DEBUG SimpleThaliTape: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
# teardown
ok 309 error should be null
ok 310 error should be null
# setup
# does not send duplicate availability changes
2016-11-29 12:25:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"dummy","hostAddress":"127.0.0.1","portNumber":8080,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
ok 311 should be called once
ok 312 should not have been called more than once
# teardown
2016-11-29 12:25:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"dummy","hostAddress":null,"portNumber":null,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
ok 313 error should be null
ok 314 error should be null
# setup
# can get the network status
ok 315 network status should have certain non-empty properties
# teardown
ok 316 error should be null
ok 317 error should be null
# setup
# wifi peer is marked unavailable if announcements stop
2016-11-29 12:25:08 - DEBUG SimpleThaliTape: 'test was skipped, name: 'wifi peer is marked unavailable if announcements stop''
# teardown
ok 318 error should be null
ok 319 error should be null
# setup
# network changes emitted correctly
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'listening 50820'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'listening 50821'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":null,"ssidName":null}'
ok 320 wifi should be off
ok 321 bssid should be null
ok 322 ssid should be null
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
ok 323 wifi should be on
ok 324 bssid should be valid
ok 325 ssid should exist
# teardown
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 326 error should be null
ok 327 error should be null
# setup
# network changes not emitted in started state
ok 328 event should not be emitted
# teardown
ok 329 error should be null
ok 330 error should be null
# setup
# network changes not emitted in stopped state
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'listening 50822'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'listening 50823'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":null,"ssidName":null}'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 331 event should not be emitted
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'listening 50824'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'listening 50825'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
ok 332 error should be null
ok 333 error should be null
# setup
# calls correct starts when network changes
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'listening 50826'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'listening 50827'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":null,"ssidName":null}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 334 specific error expected
2016-11-29 12:25:08 - DEBUG thaliWifiInfrastructure: 'listening 50829'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
ok 335 specific error expected
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:25:08 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":true,"listening":true,"advertising":true,"networkType":"BOTH"})'
2016-11-29 12:25:08 - DEBUG thaliWifiInfrastructure: 'listening 50830'
ok 336 startListeningForAdvertisements should have been called
ok 337 startUpdateAdvertisingAndListening should have been called
# teardown
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-29 12:25:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:25:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:25:08 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-29 12:25:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:25:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 338 error should be null
ok 339 error should be null
# setup
# peer is marked unavailable if port number changes
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'listening 50831'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'listening 50832'
2016-11-29 12:25:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"urn:uuid:e83bb719-0f22-4183-af73-538df8934113","hostAddress":"127.0.0.1","portNumber":8080,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
ok 340 peer should have a non-empty identifier
ok 341 peer should have a non-empty host address
ok 342 peer should have port number
ok 343 peer should have suggested timeout
ok 344 peer should have a connection type
ok 345 connection type should match one of the pre-defined types
2016-11-29 12:25:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"urn:uuid:e83bb719-0f22-4183-af73-538df8934113","hostAddress":null,"portNumber":null,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
ok 346 peer should have a non-empty identifier
ok 347 host address should be null
ok 348 port number should be null
ok 349 peer should have suggested timeout
ok 350 peer should have a connection type
ok 351 connection type should match one of the pre-defined types
2016-11-29 12:25:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"urn:uuid:e83bb719-0f22-4183-af73-538df8934113","hostAddress":"127.0.0.1","portNumber":8081,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
ok 352 port number must match
ok 353 peer should have a non-empty identifier
ok 354 peer should have a non-empty host address
ok 355 peer should have port number
ok 356 peer should have suggested timeout
ok 357 peer should have a connection type
ok 358 connection type should match one of the pre-defined types
# teardown
2016-11-29 12:25:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"urn:uuid:e83bb719-0f22-4183-af73-538df8934113","hostAddress":null,"portNumber":null,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 359 error should be null
ok 360 error should be null
# setup
# when network connection is lost a peer should be marked unavailable
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'listening 50833'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'listening 50834'
2016-11-29 12:25:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"urn:uuid:9f7c391f-0e2b-4f20-86a7-573494e8ab50","hostAddress":"127.0.0.1","portNumber":8080,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:25:08 - INFO testUtils: 'Toggling radios to: false'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"off","bluetoothLowEnergy":"on","cellular":"on","bssidName":null,"ssidName":null}'
2016-11-29 12:25:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"urn:uuid:9f7c391f-0e2b-4f20-86a7-573494e8ab50","hostAddress":null,"portNumber":null,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
ok 361 peer should have a non-empty identifier
ok 362 host address should be null
ok 363 port number should be null
ok 364 peer should have suggested timeout
ok 365 peer should have a connection type
ok 366 connection type should match one of the pre-defined types
2016-11-29 12:25:08 - INFO testUtils: 'Toggling radios to: true'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":null,"ssidName":null}'
# teardown
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 367 error should be null
ok 368 error should be null
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
# setup
# We properly fire peer unavailable and then available when connection fails
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'listening 50835'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'listening 50836'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"urn:uuid:7560c3ff-3d92-45f8-84d7-292cda0129ea","peerAvailable":true}'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'creating new server for urn:uuid:7560c3ff-3d92-45f8-84d7-292cda0129ea'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for urn:uuid:7560c3ff-3d92-45f8-84d7-292cda0129ea listening on 50837'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"urn:uuid:7560c3ff-3d92-45f8-84d7-292cda0129ea","portNumber":50837}'
2016-11-29 12:25:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"urn:uuid:7560c3ff-3d92-45f8-84d7-292cda0129ea","hostAddress":"127.0.0.1","portNumber":50837,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
ok 369 peerIds match
ok 370 peer has a portNumber
ok 371 peer has a host address
ok 372 We should have connected
2016-11-29 12:25:08 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - urn:uuid:7560c3ff-3d92-45f8-84d7-292cda0129ea - 0 - got a new incoming connection'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'Issuing callNative for urn:uuid:7560c3ff-3d92-45f8-84d7-292cda0129ea'
2016-11-29 12:25:08 - WARN createPeerListener: 'callNative for urn:uuid:7560c3ff-3d92-45f8-84d7-292cda0129ea failed with Connection could not be established'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - urn:uuid:7560c3ff-3d92-45f8-84d7-292cda0129ea - 0 - finish'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'We are emitting failedConnection with error Error: Connection could not be established and peerIdentifier urn:uuid:7560c3ff-3d92-45f8-84d7-292cda0129ea'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"urn:uuid:7560c3ff-3d92-45f8-84d7-292cda0129ea","portNumber":null,"recreated":true}'
ok 373 Failed on right peer
ok 374 Marked as recreated
2016-11-29 12:25:08 - DEBUG createPeerListener: 'Will try to recreate server for urn:uuid:7560c3ff-3d92-45f8-84d7-292cda0129ea'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for urn:uuid:7560c3ff-3d92-45f8-84d7-292cda0129ea'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"urn:uuid:7560c3ff-3d92-45f8-84d7-292cda0129ea","portNumber":null,"recreated":true}'
2016-11-29 12:25:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"urn:uuid:7560c3ff-3d92-45f8-84d7-292cda0129ea","hostAddress":null,"portNumber":null,"connectionType":"MPCF","suggestedTCPTimeout":5000,"recreated":true}'
ok 375 still same peer IDs
ok 376 peer should not have a portNumber
ok 377 peer should not have a host address
2016-11-29 12:25:08 - DEBUG createPeerListener: 'creating new server for urn:uuid:7560c3ff-3d92-45f8-84d7-292cda0129ea'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for urn:uuid:7560c3ff-3d92-45f8-84d7-292cda0129ea listening on 50839'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier urn:uuid:7560c3ff-3d92-45f8-84d7-292cda0129ea and portNumber 50839'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'listenerRecreatedAfterFailureHandler - We are emitting nonTCPPeerAvailabilityChangedEvent with peerIdentifier urn:uuid:7560c3ff-3d92-45f8-84d7-292cda0129ea and portNumber 50839'
2016-11-29 12:25:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"urn:uuid:7560c3ff-3d92-45f8-84d7-292cda0129ea","hostAddress":"127.0.0.1","portNumber":50839,"connectionType":"MPCF","suggestedTCPTimeout":5000,"recreated":true}'
ok 378 peerIds match again
ok 379 peer has a portNumber again
ok 380 peer has a host address again
ok 381 We got the error we expected
2016-11-29 12:25:08 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - urn:uuid:7560c3ff-3d92-45f8-84d7-292cda0129ea - 0 - close'
# teardown
2016-11-29 12:25:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"urn:uuid:7560c3ff-3d92-45f8-84d7-292cda0129ea","hostAddress":null,"portNumber":null,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:25:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for urn:uuid:7560c3ff-3d92-45f8-84d7-292cda0129ea'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 382 error should be null
ok 383 error should be null
# setup
# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'listening 50840'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'listening 50841'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'creating new server for urn:uuid:10e5fdde-fd64-4a90-ac51-dd478b59e369'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for urn:uuid:10e5fdde-fd64-4a90-ac51-dd478b59e369 listening on 50842'
ok 384 We should have connected
2016-11-29 12:25:08 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - urn:uuid:10e5fdde-fd64-4a90-ac51-dd478b59e369 - 0 - got a new incoming connection'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'Issuing callNative for urn:uuid:10e5fdde-fd64-4a90-ac51-dd478b59e369'
2016-11-29 12:25:08 - WARN createPeerListener: 'callNative for urn:uuid:10e5fdde-fd64-4a90-ac51-dd478b59e369 failed with Connection could not be established'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - urn:uuid:10e5fdde-fd64-4a90-ac51-dd478b59e369 - 0 - finish'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'We are emitting failedConnection with error Error: Connection could not be established and peerIdentifier urn:uuid:10e5fdde-fd64-4a90-ac51-dd478b59e369'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"urn:uuid:10e5fdde-fd64-4a90-ac51-dd478b59e369","portNumber":null,"recreated":true}'
ok 385 Failed on right peer
ok 386 Marked as recreated
2016-11-29 12:25:08 - DEBUG createPeerListener: 'Will try to recreate server for urn:uuid:10e5fdde-fd64-4a90-ac51-dd478b59e369'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for urn:uuid:10e5fdde-fd64-4a90-ac51-dd478b59e369'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"urn:uuid:10e5fdde-fd64-4a90-ac51-dd478b59e369","portNumber":null,"recreated":true}'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'creating new server for urn:uuid:10e5fdde-fd64-4a90-ac51-dd478b59e369'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for urn:uuid:10e5fdde-fd64-4a90-ac51-dd478b59e369 listening on 50844'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier urn:uuid:10e5fdde-fd64-4a90-ac51-dd478b59e369 and portNumber 50844'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'listenerRecreatedAfterFailureHandler - We are emitting nonTCPPeerAvailabilityChangedEvent with peerIdentifier urn:uuid:10e5fdde-fd64-4a90-ac51-dd478b59e369 and portNumber 50844'
ok 387 Peer still matches
ok 388 We got the connection error
2016-11-29 12:25:08 - WARN createPeerListener: 'Got error trying to restart listener for peer urn:uuid:10e5fdde-fd64-4a90-ac51-dd478b59e369 after failure TypeError: Cannot call method 'catch' of undefined'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - urn:uuid:10e5fdde-fd64-4a90-ac51-dd478b59e369 - 0 - close'
# teardown
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:25:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for urn:uuid:10e5fdde-fd64-4a90-ac51-dd478b59e369'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 389 error should be null
ok 390 error should be null
# setup
# Can call start/stopListeningForAdvertisements
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:25:08 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-29 12:25:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 391 Can call startListeningForAdvertisements without error
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:25:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 392 Can call stopListeningForAdvertisements without error
# teardown
ok 393 Should be able to call stopListeningForAdvertisements in teardown
ok 394 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Calling startListeningForAdvertisements twice is NOT an error
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:25:08 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-29 12:25:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 395 Can call startListeningForAdvertisements without error
ok 396 Can call startListeningForAdvertisements twice without error
# teardown
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:25:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 397 Should be able to call stopListeningForAdvertisements in teardown
ok 398 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Calling stopListeningForAdvertisements without calling start is NOT an error
ok 399 Can call stopListeningForAdvertisements without error
ok 400 Can call stopListeningForAdvertisements without error
# teardown
ok 401 Should be able to call stopListeningForAdvertisements in teardown
ok 402 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Can call start/stopUpdateAdvertisingAndListening
2016-11-29 12:25:08 - DEBUG thaliWifiInfrastructure: 'listening 50846'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2016-11-29 12:25:08 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-29 12:25:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 403 Can call startUpdateAdvertisingAndListening without error
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:25:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 404 Can call stopAdvertisingAndListening without error
# teardown
ok 405 Should be able to call stopListeningForAdvertisements in teardown
ok 406 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Calling startUpdateAdvertisingAndListening twice is NOT an error
2016-11-29 12:25:08 - DEBUG thaliWifiInfrastructure: 'listening 50848'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2016-11-29 12:25:08 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-29 12:25:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 407 Can call startUpdateAdvertisingAndListening without error
ok 408 Can call startUpdateAdvertisingAndListening twice without error
# teardown
ok 409 Should be able to call stopListeningForAdvertisements in teardown
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:25:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 410 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
ok 411 Can call startUpdateAdvertisingAndListening without error
ok 412 Can call stopAdvertisingAndListening without error
# teardown
ok 413 Should be able to call stopListeningForAdvertisements in teardown
ok 414 Should be able to call stopAdvertisingAndListening in teardown
# setup
# cannot call connect when start listening for advertisements is not active
ok 415 got right error
# teardown
ok 416 Should be able to call stopListeningForAdvertisements in teardown
ok 417 Should be able to call stopAdvertisingAndListening in teardown
# setup
# #startListeningForAdvertisements should fail if start not called
ok 418 specific error should be returned
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 419 must be stopped
# setup
# #startUpdateAdvertisingAndListening should fail if start not called
ok 420 specific error should be returned
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 421 must be stopped
# setup
# should be able to call #stopListeningForAdvertisements many times
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'listening 50849'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'listening 50850'
ok 422 no errors
ok 423 still no errors
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 424 must be stopped
# setup
# should be able to call #startListeningForAdvertisements many times
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'listening 50851'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'listening 50852'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:25:08 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-29 12:25:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 425 no errors
ok 426 still no errors
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:25:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 427 must be stopped
# setup
# should be able to call #startUpdateAdvertisingAndListening many times
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'listening 50853'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'listening 50854'
2016-11-29 12:25:08 - DEBUG thaliWifiInfrastructure: 'listening 50856'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2016-11-29 12:25:08 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-29 12:25:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 428 no errors
ok 429 still no errors
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:25:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 430 must be stopped
# setup
# should be able to call #stopAdvertisingAndListening many times
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'listening 50857'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'listening 50858'
ok 431 no errors
ok 432 still no errors
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 433 must be stopped
# setup
# can get the network status before starting
ok 434 network status should have certain non-empty properties
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 435 must be stopped
# setup
# error returned with bad router
2016-11-29 12:25:08 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 436 specific error expected
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 437 must be stopped
# setup
# all services are stopped when we call stop
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'listening 50859'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'listening 50860'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:25:08 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-29 12:25:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:25:08 - DEBUG thaliWifiInfrastructure: 'listening 50862'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-11-29 12:25:08 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-29 12:25:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
ok 438 connection to servers manager should succeed after starting
2016-11-29 12:25:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
ok 439 connection to router server should succeed after starting
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:25:08 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-29 12:25:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:25:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 440 is stopped after calling stop
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
ok 441 connection to servers manager should fail after stopping
ok 442 connection to router server should fail after stopping
# teardown
ok 443 must be stopped
# setup
# make sure terminateConnection is properly hooked up
ok 444 called with right arguments
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 445 must be stopped
# setup
# make sure terminateListener is properly hooked up
ok 446 called with right arguments
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 447 must be stopped
# setup
# make sure we actually call kill connections properly
ok 448 specific error expected
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 449 must be stopped
# setup
# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'listening 50867'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'listening 50868'
2016-11-29 12:25:08 - INFO thaliMobileNativeWrapper: 'routerPortConnectionFailed - {"routerPort":50867,"error":{}}'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 450 failure reason is as expected
ok 451 error description is as expected
ok 452 must be stopped
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 453 must be stopped
# setup
# We repeat failedConnection event when we get it from thaliTcpServersManager
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'listening 50869'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'listening 50870'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"some-identifier","portNumber":null}'
ok 454 peerIdentifier matches
ok 455 error description matches
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"some-identifier","portNumber":null}'
2016-11-29 12:25:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"some-identifier","hostAddress":null,"portNumber":null,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 456 must be stopped
# setup
# can do HTTP requests between peers without coordinator
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'listening 50871'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'listening 50872'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:25:08 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-29 12:25:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:25:08 - DEBUG thaliWifiInfrastructure: 'listening 50874'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-11-29 12:25:08 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-29 12:25:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerIdentifier":"foo","peerAvailable":true}]'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"foo","peerAvailable":true}'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'creating new server for foo'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for foo listening on 50875'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"foo","portNumber":50875}'
2016-11-29 12:25:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","hostAddress":"127.0.0.1","portNumber":50875,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:25:08 - DEBUG testUtils: 'We got a peer {"peerIdentifier":"foo","portNumber":50875,"hostAddress":"127.0.0.1"}'
2016-11-29 12:25:08 - WARN testUtils: 'Retry count for getSamePeerWithRetry is 1'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - foo - 0 - got a new incoming connection'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'Issuing callNative for foo'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-29 12:25:08 - DEBUG wifiBasedNativeMock: 'proxy socket connected'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'callNative for foo connected'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID foo'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 457 Should only get expected id
2016-11-29 12:25:08 - DEBUG testUtils: 'Got response data'
2016-11-29 12:25:08 - DEBUG testUtils: 'Got end'
ok 458 response body should match testData
# teardown
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - foo - finish'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:25:08 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-29 12:25:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:25:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for foo'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 459 must be stopped
2016-11-29 12:25:08 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  foo - 0 - close'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - foo - finish'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - foo - 0 - close'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - foo - close'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - foo - close'
# setup
# make sure bad PSK connections fail
ok 460 FIX ME, PLEASE!!!
2016-11-29 12:25:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 461 must be stopped
# setup
# peer changes handled from a queue
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'listening 50882'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'listening 50883'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerIdentifier":"1","peerAvailable":true},{"peerIdentifier":"2","peerAvailable":true},{"peerIdentifier":"3","peerAvailable":true},{"peerIdentifier":"4","peerAvailable":true},{"peerIdentifier":"5","peerAvailable":true},{"peerIdentifier":"6","peerAvailable":true},{"peerIdentifier":"7","peerAvailable":true},{"peerIdentifier":"8","peerAvailable":true},{"peerIdentifier":"9","peerAvailable":true},{"peerIdentifier":"10","peerAvailable":true}]'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"1","peerAvailable":true}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"2","peerAvailable":true}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3","peerAvailable":true}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"4","peerAvailable":true}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"5","peerAvailable":true}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"6","peerAvailable":true}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"7","peerAvailable":true}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"8","peerAvailable":true}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9","peerAvailable":true}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"10","peerAvailable":true}'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'creating new server for 1'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for 1 listening on 50884'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1","portNumber":50884}'
2016-11-29 12:25:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1","hostAddress":"127.0.0.1","portNumber":50884,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'creating new server for 2'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for 2 listening on 50885'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2","portNumber":50885}'
2016-11-29 12:25:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2","hostAddress":"127.0.0.1","portNumber":50885,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'creating new server for 3'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for 3 listening on 50886'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"3","portNumber":50886}'
2016-11-29 12:25:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3","hostAddress":"127.0.0.1","portNumber":50886,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'creating new server for 4'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for 4 listening on 50887'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"4","portNumber":50887}'
2016-11-29 12:25:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4","hostAddress":"127.0.0.1","portNumber":50887,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'creating new server for 5'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for 5 listening on 50888'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5","portNumber":50888}'
2016-11-29 12:25:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5","hostAddress":"127.0.0.1","portNumber":50888,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'creating new server for 6'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for 6 listening on 50889'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"6","portNumber":50889}'
2016-11-29 12:25:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6","hostAddress":"127.0.0.1","portNumber":50889,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'creating new server for 7'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for 7 listening on 50890'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7","portNumber":50890}'
2016-11-29 12:25:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7","hostAddress":"127.0.0.1","portNumber":50890,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'creating new server for 8'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for 8 listening on 50891'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"8","portNumber":50891}'
2016-11-29 12:25:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8","hostAddress":"127.0.0.1","portNumber":50891,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'creating new server for 9'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for 9 listening on 50892'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"9","portNumber":50892}'
2016-11-29 12:25:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9","hostAddress":"127.0.0.1","portNumber":50892,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'creating new server for 10'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for 10 listening on 50893'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"10","portNumber":50893}'
2016-11-29 12:25:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"10","hostAddress":"127.0.0.1","portNumber":50893,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
ok 462 peers were handled in the right order
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerIdentifier":"1","peerAvailable":false},{"peerIdentifier":"2","peerAvailable":false},{"peerIdentifier":"3","peerAvailable":false},{"peerIdentifier":"4","peerAvailable":false},{"peerIdentifier":"5","peerAvailable":false},{"peerIdentifier":"6","peerAvailable":false},{"peerIdentifier":"7","peerAvailable":false},{"peerIdentifier":"8","peerAvailable":false},{"peerIdentifier":"9","peerAvailable":false},{"peerIdentifier":"10","peerAvailable":false}]'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"1","peerAvailable":false}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"2","peerAvailable":false}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3","peerAvailable":false}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"4","peerAvailable":false}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"5","peerAvailable":false}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"6","peerAvailable":false}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"7","peerAvailable":false}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"8","peerAvailable":false}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9","peerAvailable":false}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"10","peerAvailable":false}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"1","portNumber":null}'
2016-11-29 12:25:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1","hostAddress":null,"portNumber":null,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"2","portNumber":null}'
2016-11-29 12:25:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2","hostAddress":null,"portNumber":null,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"3","portNumber":null}'
2016-11-29 12:25:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3","hostAddress":null,"portNumber":null,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"4","portNumber":null}'
2016-11-29 12:25:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4","hostAddress":null,"portNumber":null,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"5","portNumber":null}'
2016-11-29 12:25:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5","hostAddress":null,"portNumber":null,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"6","portNumber":null}'
2016-11-29 12:25:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6","hostAddress":null,"portNumber":null,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"7","portNumber":null}'
2016-11-29 12:25:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7","hostAddress":null,"portNumber":null,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"8","portNumber":null}'
2016-11-29 12:25:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8","hostAddress":null,"portNumber":null,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"9","portNumber":null}'
2016-11-29 12:25:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9","hostAddress":null,"portNumber":null,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"10","portNumber":null}'
2016-11-29 12:25:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"10","hostAddress":null,"portNumber":null,"connectionType":"MPCF","suggestedTCPTimeout":5000}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for 1'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for 2'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for 3'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for 4'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for 5'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for 6'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for 7'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for 8'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for 9'
2016-11-29 12:25:08 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for 10'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 463 must be stopped
# setup
# relaying discoveryAdvertisingStateUpdateNonTCP
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'listening 50894'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'listening 50895'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-11-29 12:25:08 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-29 12:25:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 464 discovery is active
ok 465 advertising is active
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 466 must be stopped
# setup
# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'listening 50896'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'listening 50897'
2016-11-29 12:25:08 - DEBUG thaliWifiInfrastructure: 'listening 50899'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2016-11-29 12:25:08 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-29 12:25:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:25:08 - INFO thaliMobileNativeWrapper: 'incomingConnectionToPortNumberFailed: 50897'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:25:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 467 right error reason
ok 468 Stop should be fine
ok 469 same port
ok 470 we should be off
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 471 must be stopped
# setup
# we successfully receive and replay discoveryAdvertisingStateUpdate
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'listening 50900'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'listening 50901'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-29 12:25:08 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-29 12:25:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 472 discoveryActive matches
ok 473 advertisingActive matches
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:25:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 474 discoveryActive matches
ok 475 advertisingActive matches
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'listening 50902'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'listening 50903'
2016-11-29 12:25:08 - DEBUG thaliWifiInfrastructure: 'listening 50905'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2016-11-29 12:25:08 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-29 12:25:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 476 discoveryActive matches
ok 477 advertisingActive matches
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-29 12:25:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 478 discoveryActive matches
ok 479 advertisingActive matches
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'listening 50906'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'listening 50907'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-29 12:25:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:08 - DEBUG createNativeListener: 'Native Server - close'
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 480 must be stopped
# setup
# Test BEACONS_RETRIEVED_AND_PARSED locally
ok 481 peerIdentifier should be identifier
ok 482 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 483 good beacon
ok 484 good preAmble
ok 485 public keys match!
ok 486 must return null after successful call
ok 487 Once start returns the action should be in KILLED state
# teardown
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test HTTP_BAD_RESPONSE locally
ok 488 Response should be HTTP_BAD_RESPONSE
ok 489 must return null after successful call
# teardown
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test NETWORK_PROBLEM locally
ok 490 Response should be NETWORK_PROBLEM
ok 491 reject reason should be: Could not establish TCP connection
# teardown
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Call the start two times
ok 492 Call start once
ok 493 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 494 must return null after successful call.
# teardown
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Call the kill before calling the start
ok 495 Should be Killed
ok 496 Start after killed
# teardown
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Call the kill immediately after the start
ok 497 Should be KILLED
ok 498 must return null after successful kill
# teardown
2016-11-29 12:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Call the kill while waiting a response from the server
ok 499 Should be KILLED
ok 500 must return null after successful kill
# teardown
2016-11-29 12:25:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test to exceed the max content size locally
ok 501 HTTP_BAD_RESPONSE should be response when content size is exceeded
ok 502 must return null after successful call
# teardown
2016-11-29 12:25:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Close the server socket while the client is waiting a response from the server. Local test.
2016-11-29 12:25:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 503 Should be NETWORK_PROBLEM caused closing server socket
ok 504 Should be Could not establish TCP connection
# teardown
# setup
# Close the client socket while the client is waiting a response from the server. Local test.
ok 505 Should be NETWORK_PROBLEM caused closing client socket
ok 506 Should be Could not establish TCP connection
# teardown
2016-11-29 12:25:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #generatePreambleAndBeacons bad args
ok 507 publicKeysToNotify cannot be null
ok 508 ecdh for local device cannot be null
ok 509 milliseconds cannot be less than 0
ok 510 milliseconds cannot be 0
ok 511 milliseconds cannot be greater than one_day
# teardown
# setup
# #generatePreambleAndBeacons empty keys to notify
ok 512 should be equal
# teardown
# setup
# #generatePreambleAndBeacons multiple keys to notify
ok 513 should be equal
ok 514 should be equal
ok 515 (unnamed assert)
ok 516 should be equal
# teardown
# setup
# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
ok 517 should throw
# teardown
# setup
# #parseBeacons invalid expiration in beaconStreamWithPreAmble
ok 518 Preamble expiration must be a 64 bit integer
# teardown
# setup
# #parseBeacons expiration out of range lower
ok 519 Expiration out of range
# teardown
# setup
# #parseBeacons expiration out of range lower
ok 520 Expiration out of range
# teardown
# setup
# #parseBeacons no beacons returns null
ok 521 should be equal
# teardown
# setup
# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
ok 522 Malformed encrypted beacon key ID
# teardown
# setup
# #parseBeacons addressBookCallback fails decrypt
ok 523 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns no matches
ok 524 should be equal
ok 525 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns spurious match
ok 526 should be equal
ok 527 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns public key
ok 528 right number of calls to address book
ok 529 good preAmble
ok 530 good unencryptedKeyId
ok 531 good beacon
# teardown
# setup
# validate generatePskIdentityField
ok 532 decoded buffers match
# teardown
# setup
# validate generatePskSecret
ok 533 secrets match
# teardown
# setup
# validate generatePskSecrets
ok 534 Matching numbers
ok 535 We have an entry!
ok 536 keys match
ok 537 secrets match
ok 538 We have an entry!
ok 539 keys match
ok 540 secrets match
ok 541 We have an entry!
ok 542 keys match
ok 543 secrets match
# teardown
# setup
# validate generateBeaconStreamAndSecrets
ok 544 Streams have same length
ok 545 matching size
ok 546 keys match
ok 547 secrets match
# teardown
# setup
# Add two Peers.
ok 548 should be equal
ok 549 should be equal
ok 550 should be equal
ok 551 should be equal
ok 552 should be equal
# teardown
2016-11-29 12:25:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# TCP_NATIVE peer loses DNS
ok 553 should be equal
ok 554 should be equal
# teardown
2016-11-29 12:25:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Received beacons with no values for us
ok 555 entry exists
ok 556 entry is resolved
# teardown
2016-11-29 12:25:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Notification action killed with a superseded
ok 557 Action should be killed
ok 558 should be equal
# teardown
2016-11-29 12:25:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Resolves an action locally
ok 559 Host address must match
ok 560 suggestedTCPTimeout must match
ok 561 connectionType must match
ok 562 portNumber must match
ok 563 peerIDs must match
# teardown
2016-11-29 12:25:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Resolves an action locally using ThaliPeerPoolDefault
ok 564 Host address must match
ok 565 suggestedTCPTimeout must match
ok 566 connectionType must match
ok 567 portNumber must match
ok 568 peerIds must match
# teardown
2016-11-29 12:25:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Action fails because of a bad hostname.
2016-11-29 12:25:14 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 569 action should be resolved with NETWORK_PROBLEM error
2016-11-29 12:25:14 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 570 action should be resolved with NETWORK_PROBLEM error
2016-11-29 12:25:15 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 571 action should be resolved with NETWORK_PROBLEM error
2016-11-29 12:25:16 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 572 action should be resolved with NETWORK_PROBLEM error
ok 573 correct number of requests
ok 574 correct number of failures
ok 575 correct final peer state
# teardown
2016-11-29 12:25:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# hostaddress is removed when the action is running. 
2016-11-29 12:25:18 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 576 should be equal
# teardown
2016-11-29 12:25:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Client to server request locally
ok 577 secrets are equal
ok 578 Public key matches with the server key
ok 579 Host address must match
ok 580 suggestedTCPTimeout must match
ok 581 connectionType must match
ok 582 portNumber must match
# teardown
2016-11-29 12:25:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test ThaliPskMapCache clean and expiration
ok 583 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
ok 584 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
ok 585 All entries should be expired after 1 second
# teardown
2016-11-29 12:25:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test ThaliPskMapCache getSecret and getPublic
ok 586 All keys need to be available in the cache
ok 587 All entries should be expired after 1 second
# teardown
2016-11-29 12:25:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test ThaliPskMapCache multiple entries
ok 588 Size of the cache should be 2
ok 589 Cache doesn't contain dictionary1
ok 590 Size of the cache should be 1
ok 591 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
2016-11-29 12:25:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Start and stop ThaliNotificationServer
ok 592 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
ok 593 ThaliMobile.StopAdvertisingAndListeningshould be called once
# teardown
2016-11-29 12:25:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Pass an empty array to ThaliNotificationServer.start
ok 594 StartUpdateAdvertisingAndListening should not be called
ok 595 ThaliMobile.StopAdvertisingAndListening should be called once
ok 596 no error
ok 597 should be 204
# teardown
2016-11-29 12:25:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Pass a string to ThaliNotificationServer.start
ok 598 StartUpdateAdvertisingAndListening should not be called
# teardown
2016-11-29 12:25:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Pass an empty parameter to ThaliNotificationServer.start
ok 599 StartUpdateAdvertisingAndListening should not be called
# teardown
2016-11-29 12:25:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make an HTTP request to /NotificationBeacons
ok 600 no error
ok 601 should be 200
ok 602 should be equal
ok 603 should be equal
ok 604 (unnamed assert)
ok 605 no error
ok 606 should be 204
# teardown
2016-11-29 12:25:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make an HTTP request to /NotificationBeacons (no keys)
ok 607 error should be null
ok 608 should be 204
# teardown
2016-11-29 12:25:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make an HTTP request to /NotificationBeaconsbefore calling start
ok 609 should be 404
# teardown
2016-11-29 12:25:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #testThaliPeerAction - test getters
ok 610 getPeerIdentifier
ok 611 getConnectionType
ok 612 getActionType
ok 613 getActionState
ok 614 getPskIdentity
ok 615 getPskKey
# teardown
# setup
# #testThaliPeerAction - start and kill
ok 616 initial state
ok 617 after start
2016-11-29 12:25:22 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 618 after kill
# teardown
# setup
# #testThaliPeerAction - double start
ok 619 should be equal
# teardown
# setup
# #testThaliPeerAction - start after kill
2016-11-29 12:25:22 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 620 clean kill
ok 621 should be equal
# teardown
# setup
# #testThaliPeerAction - make sure ids are unique
ok 622 should not be equal
# teardown
# setup
# #testThaliPeerAction - check that forever agent can be destroyed
ok 623 forever agent should have it's own destroy method
ok 624 agent's destroy should be called
ok 625 agent's destroy should not be called again
ok 626 agent is destroyed
# teardown
# setup
# Test PeerConnectionInformation basics
ok 627 connection type works
ok 628 getHostAddress works
ok 629 getPortNumber works
ok 630 getSuggestedTCPTimeout works
# teardown
# setup
# Test PeerDictionary basic functionality
ok 631 Entry counter must be 1
ok 632 Size must be 1
ok 633 Entry counter must be 2
ok 634 Size must be 2
ok 635 Entry2 should not be found
ok 636 Size must be 1
ok 637 Size must be 0
# teardown
# setup
# Test PeerDictionary with multiple entries.
ok 638 Size must be100
ok 639 Entries between 20 and MAXSIZE + 20 should exist
ok 640 WAITING state entry should not be removed
# teardown
# setup
# RESOLVED entries are removed before WAITING state entry.
ok 641 Entries between 6 and MAXSIZE + 4 should exist
ok 642 Size should be MAXSIZE
ok 643 Size should be MAXSIZE+6
# teardown
# setup
# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
ok 644 WAITING state entry should not be removed
ok 645 Waiting entries between 6 and MAXSIZE + 4 should exist
ok 646 Size should be MAXSIZE
ok 647 entryCounter should be MAXSIZE+6
# teardown
# setup
# When CONTROLLED_BY_POOL entry is removed and kill is called.
ok 648 Kill should be called once
ok 649 Size should be 100
# teardown
# setup
# #ThaliPeerPoolDefault - single action
ok 650 is an agent
ok 651 enqueue is fine
ok 652 Everything should be off the queue
# teardown
# setup
# #ThaliPeerPoolDefault - multiple actions
ok 653 is an agent
ok 654 first enqueue is fine
ok 655 is an agent
ok 656 second enqueue is fine
ok 657 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 658 Queue is empty
# teardown
# setup
# #ThaliPeerPoolDefault - PSK Pool works
ok 659 is an agent
ok 660 good enqueue
ok 661 Identity should match
2016-11-29 12:25:22 - DEBUG testUtils: 'Got response data'
2016-11-29 12:25:22 - DEBUG testUtils: 'Got end'
ok 662 Got expected response
ok 663 Got psk call back
# teardown
2016-11-29 12:25:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #ThaliPeerPoolDefault - stop
ok 664 is an agent
ok 665 enqueue worked
ok 666 is an agent
ok 667 enqueue 2 worked
ok 668 enqueue is not available when stopped
ok 669 start action is killed
ok 670 killed action is still killed
ok 671 inQueue is empty
# teardown
# setup
# #ThaliPeerPoolInterface - make sure that start verifies queue length
ok 672 good start
ok 673 good enqueue
ok 674 queue is not empty
# teardown
# setup
# #ThaliPeerPoolInterface - bad enqueues
ok 675 null arg
ok 676 wrong arg type
ok 677 wrong arg type
# teardown
# setup
# #ThaliPeerPoolInterface - do not allow same object type
ok 678 good enqueue
ok 679 already enqueued
# teardown
# setup
# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
ok 680 good enqueue
ok 681 2nd good enqueue
ok 682 we are in the pool
ok 683 We are out of the pool
ok 684 Action was killed
ok 685 The original kill was called too
ok 686 second item is still in queue
# teardown
# setup
# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
ok 687 good enqueue
ok 688 first kill
ok 689 second NOOP kill
# teardown
# setup
# #ThaliPeerPoolInterface - make sure that stop removes all actions
ok 690 1st good enqueue
ok 691 2nd good enqueue
ok 692 1st action is in the pool
ok 693 2nd action is in the pool
ok 694 1st action is out of the pool
ok 695 2st action is out of the pool
ok 696 pool is empty
# teardown
# setup
# We reject unrecognized connection type
2016-11-29 12:25:22 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 697 Got right error
ok 698 Start should not be called
ok 699 Kill should have been called at least once
# teardown
# setup
# We reject unrecognized action type
2016-11-29 12:25:22 - DEBUG SimpleThaliTape: 'test was skipped, name: 'We reject unrecognized action type''
# teardown
# setup
# One action on bluetooth
2016-11-29 12:25:22 - DEBUG SimpleThaliTape: 'test was skipped, name: 'One action on bluetooth''
# teardown
# setup
# Two notification actions
2016-11-29 12:25:22 - DEBUG SimpleThaliTape: 'test was skipped, name: 'Two notification actions''
# teardown
# setup
# replicateThroughProblems
2016-11-29 12:25:22 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
2016-11-29 12:25:22 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
2016-11-29 12:25:22 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
ok 700 should have gotten null
2016-11-29 12:25:22 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
2016-11-29 12:25:22 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
ok 701 Should have stopped nicely
2016-11-29 12:25:22 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
2016-11-29 12:25:22 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
ok 702 Still looking for null
2016-11-29 12:25:22 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
2016-11-29 12:25:22 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
2016-11-29 12:25:22 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
2016-11-29 12:25:22 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
2016-11-29 12:25:22 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
2016-11-29 12:25:22 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
ok 703 Yup, another null
ok 704 We cloned!
# teardown
# setup
# Replication goes first
2016-11-29 12:25:22 - DEBUG SimpleThaliTape: 'test was skipped, name: 'Replication goes first''
# teardown
# setup
# wifi allows many parallel non-replication actions
2016-11-29 12:25:22 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2016-11-29 12:25:22 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 606, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
ok 705 is an agent
ok 706 First null
2016-11-29 12:25:22 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 607, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
ok 707 is an agent
ok 708 Second null
2016-11-29 12:25:22 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 607, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
truetruefalsetrue
2016-11-29 12:25:23 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 606, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
truetruetruetrue
# teardown
# setup
# wifi allows no more than 2 simultaneous replication actions for same peerID
2016-11-29 12:25:23 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2016-11-29 12:25:23 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 608, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
ok 709 is an agent
ok 710 First null
2016-11-29 12:25:23 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 609, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
ok 711 is an agent
ok 712 second null
ok 713 third null
2016-11-29 12:25:23 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 608, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
2016-11-29 12:25:23 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 609, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
2016-11-29 12:25:23 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
2016-11-29 12:25:23 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
# teardown
# setup
# Make sure peerDictionaryKey is reasonable
ok 714 equal keys
ok 715 not equal connection type
ok 716 same connection type, different buffer
# teardown
# setup
# Make sure start works
2016-11-29 12:25:23 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 717 First start and on called correctly
# teardown
# setup
# Make sure stop works
ok 718 second cleared dictionary
2016-11-29 12:25:23 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 719 First start and on called correctly
ok 720 First stop and removeListener called correctly
ok 721 first action kill called
ok 722 second action kill called
ok 723 first cleared dictionary
ok 724 first cleared pool
ok 725 second cleared dictionary
ok 726 second cleared pool
# teardown
# setup
# Simple peer event
2016-11-29 12:25:23 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 727 listener has been set
ok 728 peer dictionary has expected number of entries
ok 729 Dictionary and pool have same action
ok 730 ads match
ok 731 PouchDB matches
ok 732 DB Names match
ok 733 public keys match
ok 734 peer dictionary has expected number of entries
ok 735 Dictionary and pool have same action
ok 736 ads match
ok 737 PouchDB matches
ok 738 DB Names match
ok 739 public keys match
2016-11-29 12:25:23 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
ok 740 start called once
ok 741 One entry left
ok 742 Dictionary and pool have same action
ok 743 Start never called
ok 744 Kill called once
ok 745 no entries left
ok 746 Third action is dead
ok 747 peer dictionary has expected number of entries
ok 748 Dictionary and pool have same action
ok 749 ads match
ok 750 PouchDB matches
ok 751 DB Names match
ok 752 public keys match
# teardown
# setup
# Server is not there
2016-11-29 12:25:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-29 12:25:23 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
2016-11-29 12:25:23 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: connect ECONNREFUSED  and it caused us to complete'
ok 753 right error
# teardown
2016-11-29 12:25:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Server accepts & closes connection
2016-11-29 12:25:23 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
2016-11-29 12:25:23 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
ok 754 right error
# teardown
2016-11-29 12:25:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Server always returns 500
2016-11-29 12:25:23 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
2016-11-29 12:25:23 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
ok 755 Got error as expected
# teardown
2016-11-29 12:25:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Server always returns 401
2016-11-29 12:25:23 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
2016-11-29 12:25:23 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
ok 756 Got error as expected
# teardown
2016-11-29 12:25:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Server always returns 403
2016-11-29 12:25:23 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
2016-11-29 12:25:23 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
ok 757 Got error as expected
# teardown
2016-11-29 12:25:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make sure docs replicate
2016-11-29 12:25:23 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
-e [0;31mcompilation aborted
 [0m
./build.sh CI FAILED - build.sh failure[0m

npm WARN thali-test-server@0.0.1 No repository field.
npm WARN thali-test-server@0.0.1 No license field.
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/javascript-state-machine
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/winston
npm http 304 http://192.168.1.100:4873/bluebird
npm http 200 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/express
npm http 200 http://192.168.1.100:4873/javascript-state-machine
npm http 200 http://192.168.1.100:4873/ip
npm http 200 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/long
npm http 200 http://192.168.1.100:4873/multiplex
npm http 200 http://192.168.1.100:4873/lie
npm http 200 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/js-extend
npm http 200 http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/bytes
npm http 304 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/type-is
npm http 200 http://192.168.1.100:4873/iconv-lite
npm http 200 http://192.168.1.100:4873/raw-body
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/statuses
npm http 304 http://192.168.1.100:4873/statuses
npm http 304 http://192.168.1.100:4873/inherits
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
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/content-disposition
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
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 200 http://192.168.1.100:4873/immediate
npm http 200 http://192.168.1.100:4873/es3ify
npm http 200 http://192.168.1.100:4873/inline-process-browser
npm http 200 http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/through
npm http 200 http://192.168.1.100:4873/esprima
npm http 304 http://192.168.1.100:4873/through
npm http 200 http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/base62
npm http 200 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/source-map
npm http fetch GET http://192.168.1.100:4873/base62/-/base62-1.1.2.tgz
npm http 200 http://192.168.1.100:4873/commoner
npm http fetch 200 http://192.168.1.100:4873/base62/-/base62-1.1.2.tgz
npm http fetch GET http://192.168.1.100:4873/commoner/-/commoner-0.10.8.tgz
npm http fetch 200 http://192.168.1.100:4873/commoner/-/commoner-0.10.8.tgz
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/detective
npm http 200 http://192.168.1.100:4873/commander
npm http 304 http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http 200 http://192.168.1.100:4873/mkdirp
npm http 200 http://192.168.1.100:4873/private
npm http 200 http://192.168.1.100:4873/q
npm http 200 http://192.168.1.100:4873/recast
npm http fetch GET http://192.168.1.100:4873/recast/-/recast-0.11.18.tgz
npm http fetch 200 http://192.168.1.100:4873/recast/-/recast-0.11.18.tgz
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http 304 http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/defined
npm http request GET http://192.168.1.100:4873/acorn
npm http 304 http://192.168.1.100:4873/defined
npm http 304 http://192.168.1.100:4873/acorn
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/minimatch
npm http 304 http://192.168.1.100:4873/inflight
npm http 304 http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/wrappy
npm http 304 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 304 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/minimist
npm http 304 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/ast-types
npm http fetch GET http://192.168.1.100:4873/esprima/-/esprima-3.1.2.tgz
npm http fetch 200 http://192.168.1.100:4873/esprima/-/esprima-3.1.2.tgz
npm http 200 http://192.168.1.100:4873/ast-types
npm http fetch GET http://192.168.1.100:4873/ast-types/-/ast-types-0.9.2.tgz
npm http fetch 200 http://192.168.1.100:4873/ast-types/-/ast-types-0.9.2.tgz
npm http request GET http://192.168.1.100:4873/amdefine
npm http 200 http://192.168.1.100:4873/amdefine
npm http request GET http://192.168.1.100:4873/falafel
npm http request GET http://192.168.1.100:4873/through2
npm http 304 http://192.168.1.100:4873/falafel
npm http 200 http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/foreach
npm http 304 http://192.168.1.100:4873/object-keys
npm http request GET http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/core-util-is
npm http request GET http://192.168.1.100:4873/string_decoder
npm http 304 http://192.168.1.100:4873/core-util-is
npm http 304 http://192.168.1.100:4873/string_decoder
npm http request GET http://192.168.1.100:4873/esmangle-evaluator
npm http 200 http://192.168.1.100:4873/esmangle-evaluator
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/varint
npm http 304 http://192.168.1.100:4873/duplexify
npm http 200 http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/stream-shift
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http 304 http://192.168.1.100:4873/stream-shift
npm http 304 http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/process-nextick-args
npm http 304 http://192.168.1.100:4873/buffer-shims
npm http 304 http://192.168.1.100:4873/util-deprecate
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 200 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 200 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http fetch GET http://192.168.1.100:4873/async/-/async-2.1.4.tgz
npm http fetch 200 http://192.168.1.100:4873/async/-/async-2.1.4.tgz
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/lodash
npm http fetch GET http://192.168.1.100:4873/lodash/-/lodash-4.17.2.tgz
npm http fetch 200 http://192.168.1.100:4873/lodash/-/lodash-4.17.2.tgz
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/chalk
npm http 304 http://192.168.1.100:4873/is-my-json-valid
npm http 304 http://192.168.1.100:4873/bluebird
npm http 200 http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/ansi-styles
npm http 304 http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-function
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/cryptiles
npm http 304 http://192.168.1.100:4873/hoek
npm http 304 http://192.168.1.100:4873/boom
npm http 304 http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 304 http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/punycode
npm http 304 http://192.168.1.100:4873/punycode
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
npm http 200 http://192.168.1.100:4873/jsdoc
npm http request GET http://192.168.1.100:4873/catharsis
npm http request GET http://192.168.1.100:4873/requizzle
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/underscore
npm http request GET http://192.168.1.100:4873/js2xmlparser
npm http request GET http://192.168.1.100:4873/marked
npm http request GET http://192.168.1.100:4873/wrench
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 200 http://192.168.1.100:4873/catharsis
npm http 304 http://192.168.1.100:4873/strip-json-comments
npm http 200 http://192.168.1.100:4873/underscore
npm http 200 http://192.168.1.100:4873/js2xmlparser
npm http 200 http://192.168.1.100:4873/requizzle
npm http 200 http://192.168.1.100:4873/wrench
npm http 200 http://192.168.1.100:4873/marked
npm WARN deprecated wrench@1.5.9: wrench.js is deprecated! You should check out fs-extra (https://github.com/jprichardson/node-fs-extra) for any operations you were using wrench for. Thanks for all the usage over the years.
npm http fetch 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http request GET http://192.168.1.100:4873/underscore-contrib
npm http 200 http://192.168.1.100:4873/underscore-contrib
npm WARN prefer global marked@0.3.6 should be installed with -g
npm WARN install@0.0.1 No repository field.
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/bn.js
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/express-pouchdb
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/leveldown-mobile
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/pouchdb-size
npm http request GET http://192.168.1.100:4873/nock
npm http request GET http://192.168.1.100:4873/request-promise
npm http request GET http://192.168.1.100:4873/pouchdb
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/proxyquire
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/sinon
npm http request GET http://192.168.1.100:4873/supertest
npm http request GET http://192.168.1.100:4873/supertest-as-promised
npm http request GET http://192.168.1.100:4873/uuid-validate
npm http request GET http://192.168.1.100:4873/tape
npm http request GET http://192.168.1.100:4873/tape-catch
npm http request GET http://192.168.1.100:4873/tmp
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/bn.js
npm http 304 http://192.168.1.100:4873/js-extend
npm http 304 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/multiplex
npm http 200 http://192.168.1.100:4873/express-pouchdb
npm http 200 http://192.168.1.100:4873/leveldown-mobile
npm http fetch GET http://192.168.1.100:4873/express-pouchdb/-/express-pouchdb-1.0.6-thali.tgz
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/randomstring
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/socket.io-client
npm http 200 http://192.168.1.100:4873/pouchdb-size
npm http 304 http://192.168.1.100:4873/urlsafe-base64
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 200 http://192.168.1.100:4873/request-promise
npm http 200 http://192.168.1.100:4873/pouchdb
npm http 304 http://192.168.1.100:4873/uuid
npm http 304 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/proxyquire
npm http 200 http://192.168.1.100:4873/nock
npm http fetch 200 http://192.168.1.100:4873/express-pouchdb/-/express-pouchdb-1.0.6-thali.tgz
npm http 200 http://192.168.1.100:4873/supertest
npm http 200 http://192.168.1.100:4873/supertest-as-promised
npm http 200 http://192.168.1.100:4873/uuid-validate
npm http 200 http://192.168.1.100:4873/sinon
npm http 200 http://192.168.1.100:4873/tape-catch
npm http 200 http://192.168.1.100:4873/tmp
npm http 200 http://192.168.1.100:4873/tape
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
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/type-is
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/raw-body
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
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/cookie-signature
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
npm http 304 http://192.168.1.100:4873/send
npm http 304 http://192.168.1.100:4873/serve-static
npm http 304 http://192.168.1.100:4873/utils-merge
npm http 304 http://192.168.1.100:4873/vary
npm http request GET http://192.168.1.100:4873/negotiator
npm http 304 http://192.168.1.100:4873/negotiator
npm http request GET http://192.168.1.100:4873/forwarded
npm http request GET http://192.168.1.100:4873/ipaddr.js
npm http 304 http://192.168.1.100:4873/ipaddr.js
npm http 304 http://192.168.1.100:4873/forwarded
npm http request GET http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/mime
npm http 304 http://192.168.1.100:4873/mime
npm http 304 http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/basic-auth
npm http request GET http://192.168.1.100:4873/compression
npm http request GET http://192.168.1.100:4873/header-case-normalizer
npm http request GET http://192.168.1.100:4873/cookie-parser
npm http request GET http://192.168.1.100:4873/pouchdb-all-dbs
npm http request GET http://192.168.1.100:4873/multiparty
npm http request GET http://192.168.1.100:4873/pouchdb-auth
npm http request GET http://192.168.1.100:4873/pouchdb-list
npm http request GET http://192.168.1.100:4873/pouchdb-replicator
npm http request GET http://192.168.1.100:4873/pouchdb-rewrite
npm http request GET http://192.168.1.100:4873/pouchdb-find
npm http request GET http://192.168.1.100:4873/pouchdb-security
npm http request GET http://192.168.1.100:4873/pouchdb-wrappers
npm http request GET http://192.168.1.100:4873/pouchdb-show
npm http request GET http://192.168.1.100:4873/pouchdb-update
npm http request GET http://192.168.1.100:4873/pouchdb-validation
npm http request GET http://192.168.1.100:4873/pouchdb-vhost
npm http 304 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/basic-auth
npm http 304 http://192.168.1.100:4873/compression
npm http 200 http://192.168.1.100:4873/cookie-parser
npm http 200 http://192.168.1.100:4873/header-case-normalizer
npm http 200 http://192.168.1.100:4873/multiparty
npm http 200 http://192.168.1.100:4873/pouchdb-all-dbs
npm http 200 http://192.168.1.100:4873/pouchdb-auth
npm http 200 http://192.168.1.100:4873/pouchdb-list
npm http 200 http://192.168.1.100:4873/pouchdb-replicator
npm http 200 http://192.168.1.100:4873/pouchdb-rewrite
npm http 200 http://192.168.1.100:4873/pouchdb-find
npm http 200 http://192.168.1.100:4873/pouchdb-security
npm http 200 http://192.168.1.100:4873/pouchdb-wrappers
npm http 200 http://192.168.1.100:4873/pouchdb-show
npm http 200 http://192.168.1.100:4873/pouchdb-update
npm http 200 http://192.168.1.100:4873/pouchdb-validation
npm http 200 http://192.168.1.100:4873/pouchdb-vhost
npm http request GET http://192.168.1.100:4873/setprototypeof
npm http 304 http://192.168.1.100:4873/setprototypeof
npm http request GET http://192.168.1.100:4873/on-headers
npm http request GET http://192.168.1.100:4873/compressible
npm http 200 http://192.168.1.100:4873/compressible
npm http 304 http://192.168.1.100:4873/on-headers
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/stream-counter
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 200 http://192.168.1.100:4873/stream-counter
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/argsarray
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/tiny-queue
npm http 304 http://192.168.1.100:4873/es3ify
npm http 200 http://192.168.1.100:4873/argsarray
npm http 200 http://192.168.1.100:4873/pouchdb-promise
npm http 200 http://192.168.1.100:4873/tiny-queue
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/base62
npm http 304 http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/crypto-lite
npm http request GET http://192.168.1.100:4873/base64url
npm http request GET http://192.168.1.100:4873/couchdb-calculate-session-id
npm http request GET http://192.168.1.100:4873/pouchdb-plugin-error
npm http request GET http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http request GET http://192.168.1.100:4873/pouchdb-req-http-query
npm http request GET http://192.168.1.100:4873/pouchdb-system-db
npm http request GET http://192.168.1.100:4873/promise-nodify
npm http request GET http://192.168.1.100:4873/secure-random
npm http 200 http://192.168.1.100:4873/base64url
npm http 200 http://192.168.1.100:4873/crypto-lite
npm http 200 http://192.168.1.100:4873/pouchdb-plugin-error
npm http 200 http://192.168.1.100:4873/couchdb-calculate-session-id
npm http 200 http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http 200 http://192.168.1.100:4873/pouchdb-req-http-query
npm http 200 http://192.168.1.100:4873/pouchdb-system-db
npm http 200 http://192.168.1.100:4873/promise-nodify
npm http 200 http://192.168.1.100:4873/secure-random
npm http request GET http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/meow
npm http 200 http://192.168.1.100:4873/concat-stream
npm http 200 http://192.168.1.100:4873/meow
npm http request GET http://192.168.1.100:4873/typedarray
npm http 304 http://192.168.1.100:4873/typedarray
npm http request GET http://192.168.1.100:4873/camelcase-keys
npm http request GET http://192.168.1.100:4873/indent-string
npm http 200 http://192.168.1.100:4873/camelcase-keys
npm http 200 http://192.168.1.100:4873/indent-string
npm http request GET http://192.168.1.100:4873/camelcase
npm http request GET http://192.168.1.100:4873/map-obj
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
npm http request GET http://192.168.1.100:4873/fruitdown
npm http request GET http://192.168.1.100:4873/es6-promise-pool
npm http request GET http://192.168.1.100:4873/level-write-stream
npm http request GET http://192.168.1.100:4873/localstorage-down
npm http request GET http://192.168.1.100:4873/pouchdb-collate
npm http request GET http://192.168.1.100:4873/memdown
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/scope-eval
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/vuvuzela
npm http request GET http://192.168.1.100:4873/spark-md5
npm http 200 http://192.168.1.100:4873/double-ended-queue
npm http 200 http://192.168.1.100:4873/fruitdown
npm http 200 http://192.168.1.100:4873/es6-promise-pool
npm http 200 http://192.168.1.100:4873/level-write-stream
npm http 200 http://192.168.1.100:4873/localstorage-down
npm http 200 http://192.168.1.100:4873/pouchdb-collate
npm http 304 http://192.168.1.100:4873/through2
npm http 200 http://192.168.1.100:4873/memdown
npm http 200 http://192.168.1.100:4873/scope-eval
npm http 200 http://192.168.1.100:4873/levelup
npm http 200 http://192.168.1.100:4873/sublevel-pouchdb
npm http 200 http://192.168.1.100:4873/pouchdb-collections
npm http 200 http://192.168.1.100:4873/spark-md5
npm http 200 http://192.168.1.100:4873/vuvuzela
npm http request GET http://192.168.1.100:4873/d64
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http 200 http://192.168.1.100:4873/d64
npm http 200 http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/end-stream
npm http 200 http://192.168.1.100:4873/end-stream
npm http request GET http://192.168.1.100:4873/write-stream
npm http 200 http://192.168.1.100:4873/write-stream
npm http request GET http://192.168.1.100:4873/deferred-leveldown
npm http request GET http://192.168.1.100:4873/level-codec
npm http request GET http://192.168.1.100:4873/level-iterator-stream
npm http request GET http://192.168.1.100:4873/level-errors
npm http request GET http://192.168.1.100:4873/prr
npm http request GET http://192.168.1.100:4873/semver
npm http 200 http://192.168.1.100:4873/deferred-leveldown
npm http 200 http://192.168.1.100:4873/level-codec
npm http 200 http://192.168.1.100:4873/prr
npm http 200 http://192.168.1.100:4873/level-errors
npm http 200 http://192.168.1.100:4873/level-iterator-stream
npm http 304 http://192.168.1.100:4873/semver
npm http request GET http://192.168.1.100:4873/errno
npm http 200 http://192.168.1.100:4873/errno
npm http request GET http://192.168.1.100:4873/humble-localstorage
npm http 200 http://192.168.1.100:4873/humble-localstorage
npm http request GET http://192.168.1.100:4873/has-localstorage
npm http request GET http://192.168.1.100:4873/localstorage-memory
npm http 200 http://192.168.1.100:4873/has-localstorage
npm http 200 http://192.168.1.100:4873/localstorage-memory
npm http request GET http://192.168.1.100:4873/functional-red-black-tree
npm http request GET http://192.168.1.100:4873/ltgt
npm http 200 http://192.168.1.100:4873/functional-red-black-tree
npm http 200 http://192.168.1.100:4873/ltgt
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/is-typedarray
npm http request GET http://192.168.1.100:4873/aws4
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 304 http://192.168.1.100:4873/is-typedarray
npm http 304 http://192.168.1.100:4873/stringstream
npm WARN deprecated tough-cookie@2.2.2: ReDoS vulnerability parsing Set-Cookie https://nodesecurity.io/advisories/130
npm http 304 http://192.168.1.100:4873/aws4
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/process-nextick-args
npm http 304 http://192.168.1.100:4873/isarray
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
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http 304 http://192.168.1.100:4873/generate-function
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http request GET http://192.168.1.100:4873/pinkie
npm http 304 http://192.168.1.100:4873/pinkie
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/cryptiles
npm http 304 http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/boom
npm http 304 http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/jsprim
npm http request GET http://192.168.1.100:4873/sshpk
npm http 304 http://192.168.1.100:4873/jsprim
npm http 304 http://192.168.1.100:4873/sshpk
npm http 304 http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/json-schema
npm http request GET http://192.168.1.100:4873/extsprintf
npm http request GET http://192.168.1.100:4873/verror
npm http 304 http://192.168.1.100:4873/json-schema
npm http 304 http://192.168.1.100:4873/verror
npm http 304 http://192.168.1.100:4873/extsprintf
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/getpass
npm http request GET http://192.168.1.100:4873/dashdash
npm http 304 http://192.168.1.100:4873/dashdash
npm http 304 http://192.168.1.100:4873/getpass
npm http 304 http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/pull-stream
npm http 200 http://192.168.1.100:4873/pull-stream
npm http request GET http://192.168.1.100:4873/pull-core
npm http 200 http://192.168.1.100:4873/pull-core
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/xmlhttprequest-cookie
npm http 200 http://192.168.1.100:4873/xmlhttprequest-cookie
npm http request GET http://192.168.1.100:4873/xmlhttprequest
npm http 200 http://192.168.1.100:4873/xmlhttprequest
npm http request GET http://192.168.1.100:4873/pouchdb-changeslike-wrapper
npm http 200 http://192.168.1.100:4873/pouchdb-changeslike-wrapper
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/couchdb-objects
npm http request GET http://192.168.1.100:4873/couchdb-eval
npm http request GET http://192.168.1.100:4873/random-uuid-v4
npm http 200 http://192.168.1.100:4873/couchdb-eval
npm http 200 http://192.168.1.100:4873/random-uuid-v4
npm http 200 http://192.168.1.100:4873/couchdb-objects
npm http request GET http://192.168.1.100:4873/is-empty
npm http 200 http://192.168.1.100:4873/is-empty
npm http request GET http://192.168.1.100:4873/pouchdb-extend
npm http request GET http://192.168.1.100:4873/is-array
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
npm http 304 http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/couchdb-render
npm http 200 http://192.168.1.100:4873/couchdb-render
npm http 304 http://192.168.1.100:4873/extend
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
npm http 200 http://192.168.1.100:4873/fast-future
npm http 200 http://192.168.1.100:4873/bindings
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
npm WARN deprecated lodash@2.4.1: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/propagate
npm http request GET http://192.168.1.100:4873/chai
npm http request GET http://192.168.1.100:4873/deep-equal
npm http 200 http://192.168.1.100:4873/propagate
npm http 200 http://192.168.1.100:4873/deep-equal
npm http 304 http://192.168.1.100:4873/debug
npm http 200 http://192.168.1.100:4873/chai
npm http request GET http://192.168.1.100:4873/assertion-error
npm http request GET http://192.168.1.100:4873/deep-eql
npm http request GET http://192.168.1.100:4873/type-detect
npm http 200 http://192.168.1.100:4873/deep-eql
npm http 200 http://192.168.1.100:4873/assertion-error
npm http 200 http://192.168.1.100:4873/type-detect
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/ip
npm http 304 http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/fill-keys
npm http request GET http://192.168.1.100:4873/module-not-found-error
npm http 200 http://192.168.1.100:4873/module-not-found-error
npm http 200 http://192.168.1.100:4873/fill-keys
npm http request GET http://192.168.1.100:4873/is-object
npm http 200 http://192.168.1.100:4873/is-object
npm http request GET http://192.168.1.100:4873/array-uniq
npm http 304 http://192.168.1.100:4873/array-uniq
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/jsonschema
npm http 304 http://192.168.1.100:4873/jsonschema
npm http request GET http://192.168.1.100:4873/formatio
npm http request GET http://192.168.1.100:4873/util
npm http request GET http://192.168.1.100:4873/lolex
npm http request GET http://192.168.1.100:4873/samsam
npm http 304 http://192.168.1.100:4873/util
npm http 200 http://192.168.1.100:4873/formatio
npm http 200 http://192.168.1.100:4873/samsam
npm http 200 http://192.168.1.100:4873/lolex
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
npm http 304 http://192.168.1.100:4873/object-component
npm http 304 http://192.168.1.100:4873/socket.io-parser
npm http 304 http://192.168.1.100:4873/component-emitter
npm http 304 http://192.168.1.100:4873/component-bind
npm http 304 http://192.168.1.100:4873/engine.io-client
npm http 304 http://192.168.1.100:4873/parseuri
npm http 304 http://192.168.1.100:4873/to-array
npm http 304 http://192.168.1.100:4873/has-binary
npm http 304 http://192.168.1.100:4873/backo2
npm http 304 http://192.168.1.100:4873/indexof
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/ws
npm http request GET http://192.168.1.100:4873/xmlhttprequest-ssl
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/parseqs
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/yeast
npm http 304 http://192.168.1.100:4873/has-cors
npm http 304 http://192.168.1.100:4873/engine.io-parser
npm http 304 http://192.168.1.100:4873/xmlhttprequest-ssl
npm http 304 http://192.168.1.100:4873/parsejson
npm http 304 http://192.168.1.100:4873/ws
npm http 304 http://192.168.1.100:4873/parseqs
npm http 304 http://192.168.1.100:4873/component-inherit
npm http 304 http://192.168.1.100:4873/yeast
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/utf8
npm http 304 http://192.168.1.100:4873/after
npm http 304 http://192.168.1.100:4873/arraybuffer.slice
npm http 304 http://192.168.1.100:4873/base64-arraybuffer
npm http 304 http://192.168.1.100:4873/utf8
npm http 304 http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/better-assert
npm http 304 http://192.168.1.100:4873/better-assert
npm http request GET http://192.168.1.100:4873/callsite
npm http 304 http://192.168.1.100:4873/callsite
npm http request GET http://192.168.1.100:4873/options
npm http request GET http://192.168.1.100:4873/ultron
npm http 304 http://192.168.1.100:4873/ultron
npm http 304 http://192.168.1.100:4873/options
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
npm http request GET http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/methods
npm http 200 http://192.168.1.100:4873/cookiejar
npm http 200 http://192.168.1.100:4873/formidable
npm http 200 http://192.168.1.100:4873/reduce-component
npm http 304 http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/mime-db
npm http 304 http://192.168.1.100:4873/mime-db
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/defined
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/object-inspect
npm http request GET http://192.168.1.100:4873/resumer
npm http 304 http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/defined
npm http 200 http://192.168.1.100:4873/resumer
npm http 200 http://192.168.1.100:4873/object-inspect
npm http request GET http://192.168.1.100:4873/os-tmpdir
npm http 304 http://192.168.1.100:4873/os-tmpdir
gyp JXcore NODE-GYP Using node-gyp bundled in npm coming from JXcore
gyp http GET https://jxcore.azureedge.net/jxb311.tar.gz
gyp http 200 https://jxcore.azureedge.net/jxb311.tar.gz
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
(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
Trace
    at EventEmitter.addListener (events.js:140:15)
    at module.exports (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.js:82:9)
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:35
    at tryCatcher (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:23)
    at Promise._settlePromiseFromHandler (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:31)
    at Promise._settlePromise (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:561:18)
    at Promise._settlePromise0 (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:606:10)
    at Promise._settlePromises (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:681:18)
    at Async._drainQueue (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:138:16)
    at Async._drainQueues (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:148:10)
    at Async.drainQueues (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:17:14)
    at process._tickCallback (node.js:924:13)
(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
Trace
    at EventEmitter.addListener (events.js:140:15)
    at module.exports (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.js:57:9)
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:35
    at tryCatcher (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:23)
    at Promise._settlePromiseFromHandler (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:31)
    at Promise._settlePromise (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:561:18)
    at Promise._settlePromise0 (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:606:10)
    at Promise._settlePromises (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:681:18)
    at Async._drainQueue (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:138:16)
    at Async._drainQueues (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:148:10)
    at Async.drainQueues (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:17:14)
    at process._tickCallback (node.js:924:13)
(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
Trace
    at EventEmitter.addListener (events.js:140:15)
    at module.exports (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.js:82:9)
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:35
    at tryCatcher (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:23)
    at Promise._settlePromiseFromHandler (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:31)
    at Promise._settlePromise (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:561:18)
    at Promise._settlePromise0 (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:606:10)
    at Promise._settlePromises (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:681:18)
    at Async._drainQueue (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:138:16)
    at Async._drainQueues (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:148:10)
    at Async.drainQueues (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:17:14)
    at process._tickCallback (node.js:924:13)
(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
Trace
    at EventEmitter.addListener (events.js:140:15)
    at module.exports (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.js:57:9)
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:35
    at tryCatcher (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:23)
    at Promise._settlePromiseFromHandler (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:31)
    at Promise._settlePromise (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:561:18)
    at Promise._settlePromise0 (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:606:10)
    at Promise._settlePromises (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:681:18)
    at Async._drainQueue (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:138:16)
    at Async._drainQueues (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:148:10)
    at Async.drainQueues (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:17:14)
    at process._tickCallback (node.js:924:13)
(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
Trace
    at EventEmitter.addListener (events.js:140:15)
    at module.exports (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.js:82:9)
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:35
    at tryCatcher (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:23)
    at Promise._settlePromiseFromHandler (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:31)
    at Promise._settlePromise (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:561:18)
    at Promise._settlePromise0 (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:606:10)
    at Promise._settlePromises (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:681:18)
    at Async._drainQueue (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:138:16)
    at Async._drainQueues (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:148:10)
    at Async.drainQueues (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:17:14)
    at process._tickCallback (node.js:924:13)
(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
Trace
    at EventEmitter.addListener (events.js:140:15)
    at module.exports (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.js:57:9)
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:35
    at tryCatcher (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:23)
    at Promise._settlePromiseFromHandler (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:31)
    at Promise._settlePromise (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:561:18)
    at Promise._settlePromise0 (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:606:10)
    at Promise._settlePromises (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:681:18)
    at Async._drainQueue (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:138:16)
    at Async._drainQueues (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:148:10)
    at Async.drainQueues (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:17:14)
    at process._tickCallback (node.js:924:13)
./build.sh: line 60:  3593 Segmentation fault: 11  jx runTests.js --networkType BOTH

```

Error: Command failed: npm WARN thali-test-server@0.0.1 No repository field.
npm WARN thali-test-server@0.0.1 No license field.
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/javascript-state-machine
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/winston
npm http 304 http://192.168.1.100:4873/bluebird
npm http 200 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/express
npm http 200 http://192.168.1.100:4873/javascript-state-machine
npm http 200 http://192.168.1.100:4873/ip
npm http 200 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/long
npm http 200 http://192.168.1.100:4873/multiplex
npm http 200 http://192.168.1.100:4873/lie
npm http 200 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/js-extend
npm http 200 http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/bytes
npm http 304 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/type-is
npm http 200 http://192.168.1.100:4873/iconv-lite
npm http 200 http://192.168.1.100:4873/raw-body
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/statuses
npm http 304 http://192.168.1.100:4873/statuses
npm http 304 http://192.168.1.100:4873/inherits
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
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/content-disposition
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
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 200 http://192.168.1.100:4873/immediate
npm http 200 http://192.168.1.100:4873/es3ify
npm http 200 http://192.168.1.100:4873/inline-process-browser
npm http 200 http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/through
npm http 200 http://192.168.1.100:4873/esprima
npm http 304 http://192.168.1.100:4873/through
npm http 200 http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/base62
npm http 200 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/source-map
npm http fetch GET http://192.168.1.100:4873/base62/-/base62-1.1.2.tgz
npm http 200 http://192.168.1.100:4873/commoner
npm http fetch 200 http://192.168.1.100:4873/base62/-/base62-1.1.2.tgz
npm http fetch GET http://192.168.1.100:4873/commoner/-/commoner-0.10.8.tgz
npm http fetch 200 http://192.168.1.100:4873/commoner/-/commoner-0.10.8.tgz
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/detective
npm http 200 http://192.168.1.100:4873/commander
npm http 304 http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http 200 http://192.168.1.100:4873/mkdirp
npm http 200 http://192.168.1.100:4873/private
npm http 200 http://192.168.1.100:4873/q
npm http 200 http://192.168.1.100:4873/recast
npm http fetch GET http://192.168.1.100:4873/recast/-/recast-0.11.18.tgz
npm http fetch 200 http://192.168.1.100:4873/recast/-/recast-0.11.18.tgz
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http 304 http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/defined
npm http request GET http://192.168.1.100:4873/acorn
npm http 304 http://192.168.1.100:4873/defined
npm http 304 http://192.168.1.100:4873/acorn
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/minimatch
npm http 304 http://192.168.1.100:4873/inflight
npm http 304 http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/wrappy
npm http 304 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 304 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/minimist
npm http 304 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/ast-types
npm http fetch GET http://192.168.1.100:4873/esprima/-/esprima-3.1.2.tgz
npm http fetch 200 http://192.168.1.100:4873/esprima/-/esprima-3.1.2.tgz
npm http 200 http://192.168.1.100:4873/ast-types
npm http fetch GET http://192.168.1.100:4873/ast-types/-/ast-types-0.9.2.tgz
npm http fetch 200 http://192.168.1.100:4873/ast-types/-/ast-types-0.9.2.tgz
npm http request GET http://192.168.1.100:4873/amdefine
npm http 200 http://192.168.1.100:4873/amdefine
npm http request GET http://192.168.1.100:4873/falafel
npm http request GET http://192.168.1.100:4873/through2
npm http 304 http://192.168.1.100:4873/falafel
npm http 200 http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/foreach
npm http 304 http://192.168.1.100:4873/object-keys
npm http request GET http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/core-util-is
npm http request GET http://192.168.1.100:4873/string_decoder
npm http 304 http://192.168.1.100:4873/core-util-is
npm http 304 http://192.168.1.100:4873/string_decoder
npm http request GET http://192.168.1.100:4873/esmangle-evaluator
npm http 200 http://192.168.1.100:4873/esmangle-evaluator
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/varint
npm http 304 http://192.168.1.100:4873/duplexify
npm http 200 http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/stream-shift
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http 304 http://192.168.1.100:4873/stream-shift
npm http 304 http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/process-nextick-args
npm http 304 http://192.168.1.100:4873/buffer-shims
npm http 304 http://192.168.1.100:4873/util-deprecate
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 200 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 200 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http fetch GET http://192.168.1.100:4873/async/-/async-2.1.4.tgz
npm http fetch 200 http://192.168.1.100:4873/async/-/async-2.1.4.tgz
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/lodash
npm http fetch GET http://192.168.1.100:4873/lodash/-/lodash-4.17.2.tgz
npm http fetch 200 http://192.168.1.100:4873/lodash/-/lodash-4.17.2.tgz
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/chalk
npm http 304 http://192.168.1.100:4873/is-my-json-valid
npm http 304 http://192.168.1.100:4873/bluebird
npm http 200 http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/ansi-styles
npm http 304 http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-function
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/cryptiles
npm http 304 http://192.168.1.100:4873/hoek
npm http 304 http://192.168.1.100:4873/boom
npm http 304 http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 304 http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/punycode
npm http 304 http://192.168.1.100:4873/punycode
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
npm http 200 http://192.168.1.100:4873/jsdoc
npm http request GET http://192.168.1.100:4873/catharsis
npm http request GET http://192.168.1.100:4873/requizzle
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/underscore
npm http request GET http://192.168.1.100:4873/js2xmlparser
npm http request GET http://192.168.1.100:4873/marked
npm http request GET http://192.168.1.100:4873/wrench
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 200 http://192.168.1.100:4873/catharsis
npm http 304 http://192.168.1.100:4873/strip-json-comments
npm http 200 http://192.168.1.100:4873/underscore
npm http 200 http://192.168.1.100:4873/js2xmlparser
npm http 200 http://192.168.1.100:4873/requizzle
npm http 200 http://192.168.1.100:4873/wrench
npm http 200 http://192.168.1.100:4873/marked
npm WARN deprecated wrench@1.5.9: wrench.js is deprecated! You should check out fs-extra (https://github.com/jprichardson/node-fs-extra) for any operations you were using wrench for. Thanks for all the usage over the years.
npm http fetch 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http request GET http://192.168.1.100:4873/underscore-contrib
npm http 200 http://192.168.1.100:4873/underscore-contrib
npm WARN prefer global marked@0.3.6 should be installed with -g
npm WARN install@0.0.1 No repository field.
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/bn.js
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/express-pouchdb
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/leveldown-mobile
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/pouchdb-size
npm http request GET http://192.168.1.100:4873/nock
npm http request GET http://192.168.1.100:4873/request-promise
npm http request GET http://192.168.1.100:4873/pouchdb
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/proxyquire
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/sinon
npm http request GET http://192.168.1.100:4873/supertest
npm http request GET http://192.168.1.100:4873/supertest-as-promised
npm http request GET http://192.168.1.100:4873/uuid-validate
npm http request GET http://192.168.1.100:4873/tape
npm http request GET http://192.168.1.100:4873/tape-catch
npm http request GET http://192.168.1.100:4873/tmp
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/bn.js
npm http 304 http://192.168.1.100:4873/js-extend
npm http 304 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/multiplex
npm http 200 http://192.168.1.100:4873/express-pouchdb
npm http 200 http://192.168.1.100:4873/leveldown-mobile
npm http fetch GET http://192.168.1.100:4873/express-pouchdb/-/express-pouchdb-1.0.6-thali.tgz
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/randomstring
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/socket.io-client
npm http 200 http://192.168.1.100:4873/pouchdb-size
npm http 304 http://192.168.1.100:4873/urlsafe-base64
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 200 http://192.168.1.100:4873/request-promise
npm http 200 http://192.168.1.100:4873/pouchdb
npm http 304 http://192.168.1.100:4873/uuid
npm http 304 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/proxyquire
npm http 200 http://192.168.1.100:4873/nock
npm http fetch 200 http://192.168.1.100:4873/express-pouchdb/-/express-pouchdb-1.0.6-thali.tgz
npm http 200 http://192.168.1.100:4873/supertest
npm http 200 http://192.168.1.100:4873/supertest-as-promised
npm http 200 http://192.168.1.100:4873/uuid-validate
npm http 200 http://192.168.1.100:4873/sinon
npm http 200 http://192.168.1.100:4873/tape-catch
npm http 200 http://192.168.1.100:4873/tmp
npm http 200 http://192.168.1.100:4873/tape
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
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/type-is
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/raw-body
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
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/cookie-signature
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
npm http 304 http://192.168.1.100:4873/send
npm http 304 http://192.168.1.100:4873/serve-static
npm http 304 http://192.168.1.100:4873/utils-merge
npm http 304 http://192.168.1.100:4873/vary
npm http request GET http://192.168.1.100:4873/negotiator
npm http 304 http://192.168.1.100:4873/negotiator
npm http request GET http://192.168.1.100:4873/forwarded
npm http request GET http://192.168.1.100:4873/ipaddr.js
npm http 304 http://192.168.1.100:4873/ipaddr.js
npm http 304 http://192.168.1.100:4873/forwarded
npm http request GET http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/mime
npm http 304 http://192.168.1.100:4873/mime
npm http 304 http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/basic-auth
npm http request GET http://192.168.1.100:4873/compression
npm http request GET http://192.168.1.100:4873/header-case-normalizer
npm http request GET http://192.168.1.100:4873/cookie-parser
npm http request GET http://192.168.1.100:4873/pouchdb-all-dbs
npm http request GET http://192.168.1.100:4873/multiparty
npm http request GET http://192.168.1.100:4873/pouchdb-auth
npm http request GET http://192.168.1.100:4873/pouchdb-list
npm http request GET http://192.168.1.100:4873/pouchdb-replicator
npm http request GET http://192.168.1.100:4873/pouchdb-rewrite
npm http request GET http://192.168.1.100:4873/pouchdb-find
npm http request GET http://192.168.1.100:4873/pouchdb-security
npm http request GET http://192.168.1.100:4873/pouchdb-wrappers
npm http request GET http://192.168.1.100:4873/pouchdb-show
npm http request GET http://192.168.1.100:4873/pouchdb-update
npm http request GET http://192.168.1.100:4873/pouchdb-validation
npm http request GET http://192.168.1.100:4873/pouchdb-vhost
npm http 304 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/basic-auth
npm http 304 http://192.168.1.100:4873/compression
npm http 200 http://192.168.1.100:4873/cookie-parser
npm http 200 http://192.168.1.100:4873/header-case-normalizer
npm http 200 http://192.168.1.100:4873/multiparty
npm http 200 http://192.168.1.100:4873/pouchdb-all-dbs
npm http 200 http://192.168.1.100:4873/pouchdb-auth
npm http 200 http://192.168.1.100:4873/pouchdb-list
npm http 200 http://192.168.1.100:4873/pouchdb-replicator
npm http 200 http://192.168.1.100:4873/pouchdb-rewrite
npm http 200 http://192.168.1.100:4873/pouchdb-find
npm http 200 http://192.168.1.100:4873/pouchdb-security
npm http 200 http://192.168.1.100:4873/pouchdb-wrappers
npm http 200 http://192.168.1.100:4873/pouchdb-show
npm http 200 http://192.168.1.100:4873/pouchdb-update
npm http 200 http://192.168.1.100:4873/pouchdb-validation
npm http 200 http://192.168.1.100:4873/pouchdb-vhost
npm http request GET http://192.168.1.100:4873/setprototypeof
npm http 304 http://192.168.1.100:4873/setprototypeof
npm http request GET http://192.168.1.100:4873/on-headers
npm http request GET http://192.168.1.100:4873/compressible
npm http 200 http://192.168.1.100:4873/compressible
npm http 304 http://192.168.1.100:4873/on-headers
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/stream-counter
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 200 http://192.168.1.100:4873/stream-counter
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/argsarray
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/tiny-queue
npm http 304 http://192.168.1.100:4873/es3ify
npm http 200 http://192.168.1.100:4873/argsarray
npm http 200 http://192.168.1.100:4873/pouchdb-promise
npm http 200 http://192.168.1.100:4873/tiny-queue
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/base62
npm http 304 http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/crypto-lite
npm http request GET http://192.168.1.100:4873/base64url
npm http request GET http://192.168.1.100:4873/couchdb-calculate-session-id
npm http request GET http://192.168.1.100:4873/pouchdb-plugin-error
npm http request GET http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http request GET http://192.168.1.100:4873/pouchdb-req-http-query
npm http request GET http://192.168.1.100:4873/pouchdb-system-db
npm http request GET http://192.168.1.100:4873/promise-nodify
npm http request GET http://192.168.1.100:4873/secure-random
npm http 200 http://192.168.1.100:4873/base64url
npm http 200 http://192.168.1.100:4873/crypto-lite
npm http 200 http://192.168.1.100:4873/pouchdb-plugin-error
npm http 200 http://192.168.1.100:4873/couchdb-calculate-session-id
npm http 200 http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http 200 http://192.168.1.100:4873/pouchdb-req-http-query
npm http 200 http://192.168.1.100:4873/pouchdb-system-db
npm http 200 http://192.168.1.100:4873/promise-nodify
npm http 200 http://192.168.1.100:4873/secure-random
npm http request GET http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/meow
npm http 200 http://192.168.1.100:4873/concat-stream
npm http 200 http://192.168.1.100:4873/meow
npm http request GET http://192.168.1.100:4873/typedarray
npm http 304 http://192.168.1.100:4873/typedarray
npm http request GET http://192.168.1.100:4873/camelcase-keys
npm http request GET http://192.168.1.100:4873/indent-string
npm http 200 http://192.168.1.100:4873/camelcase-keys
npm http 200 http://192.168.1.100:4873/indent-string
npm http request GET http://192.168.1.100:4873/camelcase
npm http request GET http://192.168.1.100:4873/map-obj
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
npm http request GET http://192.168.1.100:4873/fruitdown
npm http request GET http://192.168.1.100:4873/es6-promise-pool
npm http request GET http://192.168.1.100:4873/level-write-stream
npm http request GET http://192.168.1.100:4873/localstorage-down
npm http request GET http://192.168.1.100:4873/pouchdb-collate
npm http request GET http://192.168.1.100:4873/memdown
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/scope-eval
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/vuvuzela
npm http request GET http://192.168.1.100:4873/spark-md5
npm http 200 http://192.168.1.100:4873/double-ended-queue
npm http 200 http://192.168.1.100:4873/fruitdown
npm http 200 http://192.168.1.100:4873/es6-promise-pool
npm http 200 http://192.168.1.100:4873/level-write-stream
npm http 200 http://192.168.1.100:4873/localstorage-down
npm http 200 http://192.168.1.100:4873/pouchdb-collate
npm http 304 http://192.168.1.100:4873/through2
npm http 200 http://192.168.1.100:4873/memdown
npm http 200 http://192.168.1.100:4873/scope-eval
npm http 200 http://192.168.1.100:4873/levelup
npm http 200 http://192.168.1.100:4873/sublevel-pouchdb
npm http 200 http://192.168.1.100:4873/pouchdb-collections
npm http 200 http://192.168.1.100:4873/spark-md5
npm http 200 http://192.168.1.100:4873/vuvuzela
npm http request GET http://192.168.1.100:4873/d64
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http 200 http://192.168.1.100:4873/d64
npm http 200 http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/end-stream
npm http 200 http://192.168.1.100:4873/end-stream
npm http request GET http://192.168.1.100:4873/write-stream
npm http 200 http://192.168.1.100:4873/write-stream
npm http request GET http://192.168.1.100:4873/deferred-leveldown
npm http request GET http://192.168.1.100:4873/level-codec
npm http request GET http://192.168.1.100:4873/level-iterator-stream
npm http request GET http://192.168.1.100:4873/level-errors
npm http request GET http://192.168.1.100:4873/prr
npm http request GET http://192.168.1.100:4873/semver
npm http 200 http://192.168.1.100:4873/deferred-leveldown
npm http 200 http://192.168.1.100:4873/level-codec
npm http 200 http://192.168.1.100:4873/prr
npm http 200 http://192.168.1.100:4873/level-errors
npm http 200 http://192.168.1.100:4873/level-iterator-stream
npm http 304 http://192.168.1.100:4873/semver
npm http request GET http://192.168.1.100:4873/errno
npm http 200 http://192.168.1.100:4873/errno
npm http request GET http://192.168.1.100:4873/humble-localstorage
npm http 200 http://192.168.1.100:4873/humble-localstorage
npm http request GET http://192.168.1.100:4873/has-localstorage
npm http request GET http://192.168.1.100:4873/localstorage-memory
npm http 200 http://192.168.1.100:4873/has-localstorage
npm http 200 http://192.168.1.100:4873/localstorage-memory
npm http request GET http://192.168.1.100:4873/functional-red-black-tree
npm http request GET http://192.168.1.100:4873/ltgt
npm http 200 http://192.168.1.100:4873/functional-red-black-tree
npm http 200 http://192.168.1.100:4873/ltgt
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/is-typedarray
npm http request GET http://192.168.1.100:4873/aws4
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 304 http://192.168.1.100:4873/is-typedarray
npm http 304 http://192.168.1.100:4873/stringstream
npm WARN deprecated tough-cookie@2.2.2: ReDoS vulnerability parsing Set-Cookie https://nodesecurity.io/advisories/130
npm http 304 http://192.168.1.100:4873/aws4
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/process-nextick-args
npm http 304 http://192.168.1.100:4873/isarray
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
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http 304 http://192.168.1.100:4873/generate-function
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http request GET http://192.168.1.100:4873/pinkie
npm http 304 http://192.168.1.100:4873/pinkie
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/cryptiles
npm http 304 http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/boom
npm http 304 http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/jsprim
npm http request GET http://192.168.1.100:4873/sshpk
npm http 304 http://192.168.1.100:4873/jsprim
npm http 304 http://192.168.1.100:4873/sshpk
npm http 304 http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/json-schema
npm http request GET http://192.168.1.100:4873/extsprintf
npm http request GET http://192.168.1.100:4873/verror
npm http 304 http://192.168.1.100:4873/json-schema
npm http 304 http://192.168.1.100:4873/verror
npm http 304 http://192.168.1.100:4873/extsprintf
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/getpass
npm http request GET http://192.168.1.100:4873/dashdash
npm http 304 http://192.168.1.100:4873/dashdash
npm http 304 http://192.168.1.100:4873/getpass
npm http 304 http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/pull-stream
npm http 200 http://192.168.1.100:4873/pull-stream
npm http request GET http://192.168.1.100:4873/pull-core
npm http 200 http://192.168.1.100:4873/pull-core
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/xmlhttprequest-cookie
npm http 200 http://192.168.1.100:4873/xmlhttprequest-cookie
npm http request GET http://192.168.1.100:4873/xmlhttprequest
npm http 200 http://192.168.1.100:4873/xmlhttprequest
npm http request GET http://192.168.1.100:4873/pouchdb-changeslike-wrapper
npm http 200 http://192.168.1.100:4873/pouchdb-changeslike-wrapper
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/couchdb-objects
npm http request GET http://192.168.1.100:4873/couchdb-eval
npm http request GET http://192.168.1.100:4873/random-uuid-v4
npm http 200 http://192.168.1.100:4873/couchdb-eval
npm http 200 http://192.168.1.100:4873/random-uuid-v4
npm http 200 http://192.168.1.100:4873/couchdb-objects
npm http request GET http://192.168.1.100:4873/is-empty
npm http 200 http://192.168.1.100:4873/is-empty
npm http request GET http://192.168.1.100:4873/pouchdb-extend
npm http request GET http://192.168.1.100:4873/is-array
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
npm http 304 http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/couchdb-render
npm http 200 http://192.168.1.100:4873/couchdb-render
npm http 304 http://192.168.1.100:4873/extend
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
npm http 200 http://192.168.1.100:4873/fast-future
npm http 200 http://192.168.1.100:4873/bindings
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
npm WARN deprecated lodash@2.4.1: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/propagate
npm http request GET http://192.168.1.100:4873/chai
npm http request GET http://192.168.1.100:4873/deep-equal
npm http 200 http://192.168.1.100:4873/propagate
npm http 200 http://192.168.1.100:4873/deep-equal
npm http 304 http://192.168.1.100:4873/debug
npm http 200 http://192.168.1.100:4873/chai
npm http request GET http://192.168.1.100:4873/assertion-error
npm http request GET http://192.168.1.100:4873/deep-eql
npm http request GET http://192.168.1.100:4873/type-detect
npm http 200 http://192.168.1.100:4873/deep-eql
npm http 200 http://192.168.1.100:4873/assertion-error
npm http 200 http://192.168.1.100:4873/type-detect
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/ip
npm http 304 http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/fill-keys
npm http request GET http://192.168.1.100:4873/module-not-found-error
npm http 200 http://192.168.1.100:4873/module-not-found-error
npm http 200 http://192.168.1.100:4873/fill-keys
npm http request GET http://192.168.1.100:4873/is-object
npm http 200 http://192.168.1.100:4873/is-object
npm http request GET http://192.168.1.100:4873/array-uniq
npm http 304 http://192.168.1.100:4873/array-uniq
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/jsonschema
npm http 304 http://192.168.1.100:4873/jsonschema
npm http request GET http://192.168.1.100:4873/formatio
npm http request GET http://192.168.1.100:4873/util
npm http request GET http://192.168.1.100:4873/lolex
npm http request GET http://192.168.1.100:4873/samsam
npm http 304 http://192.168.1.100:4873/util
npm http 200 http://192.168.1.100:4873/formatio
npm http 200 http://192.168.1.100:4873/samsam
npm http 200 http://192.168.1.100:4873/lolex
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
npm http 304 http://192.168.1.100:4873/object-component
npm http 304 http://192.168.1.100:4873/socket.io-parser
npm http 304 http://192.168.1.100:4873/component-emitter
npm http 304 http://192.168.1.100:4873/component-bind
npm http 304 http://192.168.1.100:4873/engine.io-client
npm http 304 http://192.168.1.100:4873/parseuri
npm http 304 http://192.168.1.100:4873/to-array
npm http 304 http://192.168.1.100:4873/has-binary
npm http 304 http://192.168.1.100:4873/backo2
npm http 304 http://192.168.1.100:4873/indexof
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/ws
npm http request GET http://192.168.1.100:4873/xmlhttprequest-ssl
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/parseqs
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/yeast
npm http 304 http://192.168.1.100:4873/has-cors
npm http 304 http://192.168.1.100:4873/engine.io-parser
npm http 304 http://192.168.1.100:4873/xmlhttprequest-ssl
npm http 304 http://192.168.1.100:4873/parsejson
npm http 304 http://192.168.1.100:4873/ws
npm http 304 http://192.168.1.100:4873/parseqs
npm http 304 http://192.168.1.100:4873/component-inherit
npm http 304 http://192.168.1.100:4873/yeast
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/utf8
npm http 304 http://192.168.1.100:4873/after
npm http 304 http://192.168.1.100:4873/arraybuffer.slice
npm http 304 http://192.168.1.100:4873/base64-arraybuffer
npm http 304 http://192.168.1.100:4873/utf8
npm http 304 http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/better-assert
npm http 304 http://192.168.1.100:4873/better-assert
npm http request GET http://192.168.1.100:4873/callsite
npm http 304 http://192.168.1.100:4873/callsite
npm http request GET http://192.168.1.100:4873/options
npm http request GET http://192.168.1.100:4873/ultron
npm http 304 http://192.168.1.100:4873/ultron
npm http 304 http://192.168.1.100:4873/options
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
npm http request GET http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/methods
npm http 200 http://192.168.1.100:4873/cookiejar
npm http 200 http://192.168.1.100:4873/formidable
npm http 200 http://192.168.1.100:4873/reduce-component
npm http 304 http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/mime-db
npm http 304 http://192.168.1.100:4873/mime-db
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/defined
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/object-inspect
npm http request GET http://192.168.1.100:4873/resumer
npm http 304 http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/defined
npm http 200 http://192.168.1.100:4873/resumer
npm http 200 http://192.168.1.100:4873/object-inspect
npm http request GET http://192.168.1.100:4873/os-tmpdir
npm http 304 http://192.168.1.100:4873/os-tmpdir
gyp JXcore NODE-GYP Using node-gyp bundled in npm coming from JXcore
gyp http GET https://jxcore.azureedge.net/jxb311.tar.gz
gyp http 200 https://jxcore.azureedge.net/jxb311.tar.gz
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
(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
Trace
    at EventEmitter.addListener (events.js:140:15)
    at module.exports (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.js:82:9)
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:35
    at tryCatcher (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:23)
    at Promise._settlePromiseFromHandler (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:31)
    at Promise._settlePromise (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:561:18)
    at Promise._settlePromise0 (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:606:10)
    at Promise._settlePromises (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:681:18)
    at Async._drainQueue (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:138:16)
    at Async._drainQueues (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:148:10)
    at Async.drainQueues (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:17:14)
    at process._tickCallback (node.js:924:13)
(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
Trace
    at EventEmitter.addListener (events.js:140:15)
    at module.exports (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.js:57:9)
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:35
    at tryCatcher (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:23)
    at Promise._settlePromiseFromHandler (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:31)
    at Promise._settlePromise (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:561:18)
    at Promise._settlePromise0 (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:606:10)
    at Promise._settlePromises (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:681:18)
    at Async._drainQueue (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:138:16)
    at Async._drainQueues (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:148:10)
    at Async.drainQueues (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:17:14)
    at process._tickCallback (node.js:924:13)
(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
Trace
    at EventEmitter.addListener (events.js:140:15)
    at module.exports (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.js:82:9)
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:35
    at tryCatcher (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:23)
    at Promise._settlePromiseFromHandler (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:31)
    at Promise._settlePromise (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:561:18)
    at Promise._settlePromise0 (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:606:10)
    at Promise._settlePromises (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:681:18)
    at Async._drainQueue (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:138:16)
    at Async._drainQueues (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:148:10)
    at Async.drainQueues (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:17:14)
    at process._tickCallback (node.js:924:13)
(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
Trace
    at EventEmitter.addListener (events.js:140:15)
    at module.exports (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.js:57:9)
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:35
    at tryCatcher (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:23)
    at Promise._settlePromiseFromHandler (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:31)
    at Promise._settlePromise (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:561:18)
    at Promise._settlePromise0 (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:606:10)
    at Promise._settlePromises (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:681:18)
    at Async._drainQueue (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:138:16)
    at Async._drainQueues (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:148:10)
    at Async.drainQueues (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:17:14)
    at process._tickCallback (node.js:924:13)
(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
Trace
    at EventEmitter.addListener (events.js:140:15)
    at module.exports (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.js:82:9)
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:35
    at tryCatcher (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:23)
    at Promise._settlePromiseFromHandler (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:31)
    at Promise._settlePromise (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:561:18)
    at Promise._settlePromise0 (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:606:10)
    at Promise._settlePromises (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:681:18)
    at Async._drainQueue (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:138:16)
    at Async._drainQueues (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:148:10)
    at Async.drainQueues (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:17:14)
    at process._tickCallback (node.js:924:13)
(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
Trace
    at EventEmitter.addListener (events.js:140:15)
    at module.exports (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.js:57:9)
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:35
    at tryCatcher (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:23)
    at Promise._settlePromiseFromHandler (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:31)
    at Promise._settlePromise (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:561:18)
    at Promise._settlePromise0 (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:606:10)
    at Promise._settlePromises (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:681:18)
    at Async._drainQueue (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:138:16)
    at Async._drainQueues (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:148:10)
    at Async.drainQueues (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:17:14)
    at process._tickCallback (node.js:924:13)
./build.sh: line 60:  3593 Segmentation fault: 11  jx runTests.js --networkType BOTH
