#### Test (Fail) 92005191 Build Logs


```
Updating 56c6e22..ef5909f
Fast-forward
 thali/package.json |    2 +-
 1 file changed, 1 insertion(+), 1 deletion(-)

From https://github.com/thaliproject/Thali_CordovaPlugin
   56c6e22..ef5909f  master     -> origin/master
 + 02df989...e12c4c0 master_1470 -> origin/master_1470  (forced update)

```

```
Your branch is up-to-date with 'origin/master'.
Your branch is up-to-date with 'origin/master'.
Merge made by the 'recursive' strategy.
 thali/package.json | 2 +-
 1 file changed, 1 insertion(+), 1 deletion(-)

Already on 'master'
Already on 'master'
Note: checking out '55ceef7'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at 55ceef7... added pipe test

```

```
Cordova version:
6.3.1
Start setUpDesktop.sh
Setup TestServer
thali-test-server@0.0.1 /Users/thali/Github/Thali_CordovaPlugin/test/TestServer
├── bluebird@3.4.6 
├─┬ express@4.13.3 
│ ├─┬ accepts@1.2.13 
│ │ ├─┬ mime-types@2.1.12 
│ │ │ └── mime-db@1.24.0 
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
│ ├─┬ type-is@1.6.13 
│ │ └── media-typer@0.3.0 
│ ├── utils-merge@1.0.0 
│ └── vary@1.0.1 
├─┬ fs-extra-promise@0.2.0 
│ ├── bluebird@2.11.0 
│ └─┬ fs-extra@0.21.0 
│   ├── graceful-fs@4.1.10 
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
├── forever-agent@0.6.1 
│   HTTP Agent that keeps socket connections alive between keep-alive requests. Formerly part of mikeal/request, now a standalone module.
│   git+https://github.com/mikeal/forever-agent.git
│   https://github.com/mikeal/forever-agent
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
├── node-ssdp@2.6.5  (git://github.com/thaliproject/node-ssdp.git#caf1a75aa54fb47a9e51b72bf4c902c366536cbd)
│   A node.js SSDP client and server library.
│   git+ssh://git@github.com/diversario/node-ssdp.git
│   https://github.com/diversario/node-ssdp#readme
│   git://github.com/thaliproject/node-ssdp.git#caf1a75aa54fb47a9e51b72bf4c902c366536cbd
├── request@2.64.0 
│   Simplified HTTP request client.
│   git+https://github.com/request/request.git
│   https://github.com/request/request#readme
├── salti@0.2.1  (git+https://github.com/thaliproject/salti.git#32abe64b9cd1a4213aed9012a94e26e06aa9c3ca)
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
│   ├── graceful-fs@4.1.10 
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
│ │ │ ├── base62@1.1.1 
│ │ │ ├─┬ commoner@0.10.4 
│ │ │ │ ├─┬ detective@4.3.2 
│ │ │ │ │ ├── acorn@3.3.0 
│ │ │ │ │ └── defined@1.0.0 
│ │ │ │ ├── glob@5.0.15 
│ │ │ │ ├── iconv-lite@0.4.13 
│ │ │ │ └── q@1.4.1 
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
│ │ └─┬ async@2.1.2 
│ │   └── lodash@4.16.6 
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
│ ├─┬ mime-types@2.1.12 
│ │ └── mime-db@1.24.0 
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
├── express-pouchdb@1.0.5-thali 
│   Express submodule with a CouchDB style REST interface to PouchDB.
│   git://github.com/pouchdb/express-pouchdb.git
│   https://github.com/pouchdb/express-pouchdb
├── forever-agent@0.6.1 
│   HTTP Agent that keeps socket connections alive between keep-alive requests. Formerly part of mikeal/request, now a standalone module.
│   git+https://github.com/mikeal/forever-agent.git
│   https://github.com/mikeal/forever-agent
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
├── node-ssdp@2.6.5  (git://github.com/thaliproject/node-ssdp.git#caf1a75aa54fb47a9e51b72bf4c902c366536cbd)
│   A node.js SSDP client and server library.
│   git+ssh://git@github.com/diversario/node-ssdp.git
│   https://github.com/diversario/node-ssdp#readme
│   git://github.com/thaliproject/node-ssdp.git#caf1a75aa54fb47a9e51b72bf4c902c366536cbd
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
├── salti@0.2.1  (git+https://github.com/thaliproject/salti.git#32abe64b9cd1a4213aed9012a94e26e06aa9c3ca)
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

> thali-cordova-plugin-jxcore@1.0.0 test /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore
> jx runTests.js

2016-11-03 12:06:11 - INFO runTests: 'Starting tests. Network type: undefined. Platform: android'
2016-11-03 12:06:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreateNativeListener.js'
2016-11-03 12:06:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js'
2016-11-03 12:06:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js'
2016-11-03 12:06:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
2016-11-03 12:06:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
2016-11-03 12:06:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testNativeMethod.js'
2016-11-03 12:06:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
2016-11-03 12:06:12 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBGenerator.js'
2016-11-03 12:06:12 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPromiseQueue.js'
2016-11-03 12:06:12 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testTests.js'
2016-11-03 12:06:12 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManager.js'
2016-11-03 12:06:12 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
2016-11-03 12:06:12 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js'
2016-11-03 12:06:12 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNative.js'
2016-11-03 12:06:12 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
2016-11-03 12:06:12 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
2016-11-03 12:06:12 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotification.js'
2016-11-03 12:06:12 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationAction.js'
2016-11-03 12:06:12 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
2016-11-03 12:06:12 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationClient.js'
2016-11-03 12:06:12 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationLocal.js'
2016-11-03 12:06:12 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationServer.js'
2016-11-03 12:06:12 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerAction.js'
2016-11-03 12:06:12 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerDictionary.js'
2016-11-03 12:06:12 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
2016-11-03 12:06:12 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
2016-11-03 12:06:12 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
2016-11-03 12:06:12 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
2016-11-03 12:06:12 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
2016-11-03 12:06:12 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
2016-11-03 12:06:12 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
2016-11-03 12:06:12 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
2016-11-03 12:06:12 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
2016-11-03 12:06:12 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliTcpServersManager.js'
2016-11-03 12:06:12 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
2016-11-03 12:06:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-03 12:06:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-03 12:06:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-03 12:06:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-03 12:06:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
TAP version 13
# setup
# calling createNativeListener directly rejects
2016-11-03 12:06:12 - DEBUG createNativeListener: 'creating native server'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'listening 49666'
ok 1 Should throw
# teardown
# setup
# emits incomingConnectionState
2016-11-03 12:06:12 - DEBUG createNativeListener: 'creating native server'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'listening 49668'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new incoming socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'creating incoming mux'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new mux'
ok 2 initial connection state should be CONNECTED
2016-11-03 12:06:12 - DEBUG createNativeListener: 'incoming socket close'
ok 3 final connection state should be DISCONNECTED
# teardown
# setup
# emits routerPortConnectionFailed
2016-11-03 12:06:12 - DEBUG createNativeListener: 'creating native server'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'listening 49671'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new incoming socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'creating incoming mux'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new mux'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: ' Error: connect ECONNREFUSED
    at errnoException (net.js:837:11)
    at Object.afterConnect [as oncomplete] (net.js:829:19)'
ok 4 tried to connect to right port
ok 5 failed due to refused connection
ok 6 routerPortConnectionFailed is emitted
# teardown
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'mux close'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'incoming socket close'
# setup
# native server connections all up
2016-11-03 12:06:12 - DEBUG createNativeListener: 'creating native server'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'listening 49675'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new incoming socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'creating incoming mux'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new mux'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
ok 7 Send/recvd #1 should be equal length
ok 8 Send/recvd #1 should be same
ok 9 Send/recvd #2 should be equal length
ok 10 Send/recvd #2 should be same
ok 11 Should be exactly 2 client sockets
# teardown
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'mux close'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'incoming socket close'
# setup
# native server - closing incoming stream cleans outgoing socket
2016-11-03 12:06:12 - DEBUG createNativeListener: 'creating native server'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'listening 49680'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new incoming socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'creating incoming mux'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new mux'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
ok 12 socket shouldn't close until after stream
ok 13 incoming remains open
# teardown
2016-11-03 12:06:12 - DEBUG createNativeListener: 'mux close'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'incoming socket close'
# setup
# native server - closing incoming connection cleans outgoing socket
2016-11-03 12:06:12 - DEBUG createNativeListener: 'creating native server'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'listening 49684'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new incoming socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'creating incoming mux'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new mux'
ok 14 we should not have gotten an error
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'incoming socket close'
ok 15 socket shouldn't close until after incoming
ok 16 incoming is cleaned up
# teardown
# setup
# native server - closing outgoing socket cleans associated mux stream
2016-11-03 12:06:12 - DEBUG createNativeListener: 'creating native server'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'listening 49688'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new incoming socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'creating incoming mux'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new mux'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
ok 17 stream was closed
ok 18 incoming should survive
ok 19 mux should have no streams
# teardown
2016-11-03 12:06:12 - DEBUG createNativeListener: 'mux close'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'incoming socket close'
# setup
# native server - closing the whole server cleans everything up
2016-11-03 12:06:12 - DEBUG createNativeListener: 'creating native server'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'listening 49692'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new incoming socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'creating incoming mux'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new mux'
ok 20 we should not have gotten an error
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
ok 21 Buffers are identical
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'mux close'
ok 22 native server is nulled out
ok 23 native server should be closed
ok 24 incoming has been removed
ok 25 Incoming should be done
ok 26 The mux object should be closed
ok 27 The mux stream should be closed
2016-11-03 12:06:12 - DEBUG createNativeListener: 'incoming socket close'
# teardown
# setup
# native server - we can get a ton of connections and data through and still clean up the server completely
2016-11-03 12:06:12 - DEBUG createNativeListener: 'creating native server'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'listening 49696'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new incoming socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'creating incoming mux'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new mux'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new incoming socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'creating incoming mux'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new mux'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new incoming socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'creating incoming mux'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new mux'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new incoming socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'creating incoming mux'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new mux'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new incoming socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'creating incoming mux'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new mux'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new incoming socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'creating incoming mux'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new mux'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new incoming socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'creating incoming mux'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new mux'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new incoming socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'creating incoming mux'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new mux'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new incoming socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'creating incoming mux'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new mux'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new incoming socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'creating incoming mux'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new mux'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'mux close'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'mux close'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'mux close'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'mux close'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'mux close'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'mux close'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'mux close'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'mux close'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'mux close'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'mux close'
ok 28 native server is nulled out
ok 29 native server should be closed
ok 30 incoming has been removed
2016-11-03 12:06:12 - DEBUG createNativeListener: 'incoming socket close'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'incoming socket close'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'incoming socket close'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'incoming socket close'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'incoming socket close'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'incoming socket close'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'incoming socket close'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'incoming socket close'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'incoming socket close'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'incoming socket close'
# teardown
# setup
# native server - simulate mux failure, make sure everything is cleaned up
2016-11-03 12:06:12 - DEBUG createNativeListener: 'creating native server'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'listening 49748'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new incoming socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'creating incoming mux'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new mux'
ok 31 we should not have gotten an error
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
ok 32 Buffers are identical
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'mux close'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'incoming socket close'
ok 33 server should be fine
ok 34 server should be open
ok 35 incoming has been removed
ok 36 The mux object should be closed
ok 37 The mux stream should be closed
# teardown
# setup
# native server - timing out the incoming connection cleans everything up
2016-11-03 12:06:12 - DEBUG createNativeListener: 'creating native server'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'listening 49752'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new incoming socket'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'creating incoming mux'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new mux'
ok 38 we should not have gotten an error
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:12 - DEBUG createNativeListener: 'new outgoing socket'
ok 39 Buffers are identical
2016-11-03 12:06:12 - DEBUG createNativeListener: 'incoming socket timeout'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'mux close'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'incoming socket close'
ok 40 server should be fine
ok 41 server should be open
ok 42 incoming has been removed
ok 43 The mux object should be closed
ok 44 The mux stream should be closed
# teardown
# setup
# createPeerListener - we shouldn't create a dead pipe
2016-11-03 12:06:12 - DEBUG createNativeListener: 'creating native server'
ok 45 Can call startUpdateAdvertisingAndListening without error
ok 46 Can call startListeningForAdvertisements without error
2016-11-03 12:06:12 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-11-03 12:06:12 - DEBUG createNativeListener: 'listening 49757'
2016-11-03 12:06:12 - DEBUG createPeerListener: 'listening 49758'
2016-11-03 12:06:12 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 47 peerPort != nativePort
2016-11-03 12:06:12 - DEBUG createPeerListener: 'first connection'
2016-11-03 12:06:12 - DEBUG createPeerListener: 'forward connection'
ok 48 Should not get unexpected connection
2016-11-03 12:06:12 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID peer1 with port 49758'
ok 49 passed
2016-11-03 12:06:12 - DEBUG createPeerListener: 'incoming is already closed'
# teardown
# setup
# #_doImmediateSeqUpdate - server is not there
not ok 50 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
2016-11-03 12:06:12 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
ok 51 Got right error
# teardown
# setup
# #_doImmediateSeqUpdate - server accepts & closes connection
not ok 52 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
2016-11-03 12:06:12 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
ok 53 Got socket hang up
# teardown
# setup
# #_doImmediateSeqUpdate - server always returns 500
not ok 54 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 55 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
2016-11-03 12:06:12 - DEBUG localSeqManager: 'Got an error trying to update seq []'
ok 56 Got 500 as expected
# teardown
# setup
# #_doImmediateSeqUpdate - create new seq doc
not ok 57 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 58 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 59 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 60 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 61 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 62 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 63 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 64 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
ok 65 should be equal
ok 66 revs are equal
# teardown
# setup
# #_doImmediateSeqUpdate - doc exists, need to get rev and update
not ok 67 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 68 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 69 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 70 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 71 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 72 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 73 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 74 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 75 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 76 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
ok 77 should be equal
ok 78 revs are equal
# teardown
# setup
# #_doImmediateSeqUpdate - update seq three times
not ok 79 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 80 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 81 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 82 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 83 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 84 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 85 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 86 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
ok 87 should be equal
ok 88 revs are equal
not ok 89 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 90 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 91 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 92 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
ok 93 should be equal
ok 94 revs are equal
not ok 95 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 96 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 97 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 98 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
ok 99 should be equal
ok 100 revs are equal
# teardown
# setup
# #_doImmediateSeqUpdate - rev got changed under us
not ok 101 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 102 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 103 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 104 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 105 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 106 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 107 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 108 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 109 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 110 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
2016-11-03 12:06:13 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
ok 111 Our rev is old so we should fail
# teardown
# setup
# #_doImmediateSeqUpdate - fail if stop is called
ok 112 confirm stop caused failure
# teardown
# setup
# #_doImmediateSeqUpdate - stop after get but before put fails right
not ok 113 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 114 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 115 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 116 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
2016-11-03 12:06:13 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
ok 117 stop caused us to fail
ok 118 We specifically failed on a stop before put
# teardown
# setup
# #update - fail if stop is called
ok 119 failed due to stop
ok 120 failed due to stop
# teardown
# setup
# #update - set seq for first time
not ok 121 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 122 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 123 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 124 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 125 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 126 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 127 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 128 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
ok 129 should be equal
# teardown
# setup
# #update - Fail on bad seq value
not ok 130 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 131 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 132 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 133 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 134 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 135 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
2016-11-03 12:06:13 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
ok 136 Expected bad seq error
# teardown
# setup
# #update - do we cancel timer properly on an immediate?
not ok 137 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 138 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 139 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 140 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 141 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 142 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
ok 143 Different promises
ok 144 Timer was cancelled
not ok 145 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 146 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 147 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 148 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
ok 149 should be equal
# teardown
# setup
# #update - do we wait for blocked update
ok 150 One go and one blocked
ok 151 All blocked
ok 152 Still blocked
not ok 153 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 154 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 155 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 156 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 157 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 158 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 159 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 160 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
ok 161 should be equal
# teardown
# setup
# #update - test that we wait long enough
not ok 162 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 163 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 164 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 165 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 166 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 167 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 168 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 169 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
ok 170 We waited long enough
not ok 171 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 172 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
ok 173 should be equal
# teardown
# setup
# #update - test that we pick up new sequences while we wait
not ok 174 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 175 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 176 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 177 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 178 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 179 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
ok 180 Should have gotten same timer promise
ok 181 Still same timer promise
not ok 182 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 183 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
ok 184 We waited long enough
not ok 185 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 186 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
ok 187 should be equal
# teardown
# setup
# closeAll can close even when connections open
not ok 188 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
ok 189 not possible to connect to the server anymore
# teardown
# setup
# closeAll with promise
not ok 190 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
ok 191 not possible to connect to the server anymore
# teardown
# setup
# closeAll properly throws when closing a non open server with eatNotRunning set to false
ok 192 Got the right error
# teardown
# setup
# closeAll works even with a server that is not listening yet witheatNotRunning set to true
# teardown
# setup
# Call of onCheckpointReached handler on a single db change
# teardown
# setup
# Call of multiple onCheckpointReached handlers on a single db change
# teardown
# setup
# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
ok 193 the checkpointReached handler should be called once. Called 1 time(s)
# teardown
# setup
# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
# teardown
# setup
# test defaultDirectory
ok 194 should be equal
ok 195 should be equal
ok 196 should be equal
# teardown
# setup
# test defaultAdapter
ok 197 should be equal
ok 198 should be equal
ok 199 should be equal
ok 200 should be equal
ok 201 should be equal
ok 202 should be equal
ok 203 should be equal
ok 204 should be equal
# teardown
# setup
# enqueue and run in order
ok 205 firstPromise setTimeout
ok 206 firstPromise result
ok 207 firstPromise testValue
ok 208 secondPromise setTimeout
ok 209 secondPromise result
ok 210 secondPromise testValue
ok 211 thirdPromise in promise
ok 212 thirdPromise result
ok 213 thirdPromise testValue
# teardown
# setup
# enqueueAtTop and run backwards
ok 214 thirdPromise - first to run
ok 215 thirdPromise - in resolve
ok 216 secondPromise - second to run
ok 217 secondPromise - in catch
ok 218 firstPromise - third to run
ok 219 firstPromise - in then
ok 220 testing promises
# teardown
# setup
# mix enqueue and enqueueAtTop
ok 221 fourth
ok 222 fourth
ok 223 second
ok 224 secondPromise - in then
ok 225 first
ok 226 firstPromise - in catch
ok 227 third
ok 228 thirdPromise - in then
ok 229 testingPromises
# teardown
# setup
# queues handled independently
ok 230 all short operations completed before the long resolves
# teardown
# setup
# basic
ok 231 sane
# teardown
# setup
# another
ok 232 sane
# teardown
# setup
# test thali manager spies
2016-11-03 12:06:18 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
2016-11-03 12:06:18 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
2016-11-03 12:06:18 - DEBUG thaliManager: 'creating express pouchdb instance'
ok 233 expressPouchDB was called once
ok 234 expressPouchDB was called with 2 arguments
ok 235 expressPouchDB was called with 'PouchDB' as 1-st argument
ok 236 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
ok 237 PouchDB was called once
ok 238 PouchDB was called with 1 arguments
ok 239 PouchDB was called with 'dbName' as 1-st argument
ok 240 ThaliSendNotificationBasedOnReplication was called once
ok 241 ThaliSendNotificationBasedOnReplication was called with 4 arguments
ok 242 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
ok 243 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
ok 244 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
ok 245 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
ok 246 ThaliPullReplicationFromNotification was called once
ok 247 ThaliPullReplicationFromNotification was called with 4 arguments
ok 248 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
ok 249 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
ok 250 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
ok 251 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
ok 252 Salti was called once
ok 253 Salti was called with 4 arguments
ok 254 Salti was called with 'dbName' as 1-st argument
ok 255 Salti was called with 'acl' as 2-st argument
ok 256 Salti was called with 'thaliIdCallback' as 3-st argument
ok 257 Salti was called with 'options' as 4-st argument
2016-11-03 12:06:18 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-03 12:06:18 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-03 12:06:18 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-03 12:06:18 - DEBUG thaliMobileNativeWrapper: 'listening 49836'
2016-11-03 12:06:18 - DEBUG createNativeListener: 'creating native server'
2016-11-03 12:06:18 - DEBUG createNativeListener: 'listening 49837'
2016-11-03 12:06:18 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-03 12:06:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-03 12:06:18 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-03 12:06:18 - DEBUG thaliWifiInfrastructure: 'listening 49838'
2016-11-03 12:06:18 - DEBUG thaliWifiInfrastructure: 'listening 49840'
2016-11-03 12:06:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-11-03 12:06:18 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
ok 258 ThaliMobile.start was called once
ok 259 ThaliMobile.start was called with 3 arguments
ok 260 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
ok 261 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
ok 262 ThaliMobile.start was called with 'networkType' as 3-st argument
ok 263 ThaliMobile.startListeningForAdvertisements was called once
ok 264 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
ok 265 ThaliMobile.startUpdateAdvertisingAndListening was called once
ok 266 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
ok 267 ThaliSendNotificationBasedOnReplication.prototype.start was called once
ok 268 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
ok 269 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
ok 270 ThaliPullReplicationFromNotification.prototype.start was called once
ok 271 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
ok 272 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
2016-11-03 12:06:18 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-03 12:06:18 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-03 12:06:18 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-03 12:06:18 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-03 12:06:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-03 12:06:18 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-03 12:06:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-03 12:06:18 - DEBUG thaliManager: 'stopping ThaliMobile'
ok 273 ThaliMobile.stop was called once
ok 274 ThaliMobile.stop was called with 0 arguments
ok 275 ThaliMobile.stopListeningForAdvertisements was called once
ok 276 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
ok 277 ThaliMobile.stopAdvertisingAndListening was called once
ok 278 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
ok 279 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
ok 280 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
ok 281 ThaliPullReplicationFromNotification.prototype.stop was called once
ok 282 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
# teardown
# setup
# test thali manager multiple starts and stops
2016-11-03 12:06:18 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
2016-11-03 12:06:18 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
2016-11-03 12:06:18 - DEBUG thaliManager: 'creating express pouchdb instance'
ok 283 expressPouchDB was called once
ok 284 expressPouchDB was called with 2 arguments
ok 285 expressPouchDB was called with 'PouchDB' as 1-st argument
ok 286 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
ok 287 PouchDB was called once
ok 288 PouchDB was called with 1 arguments
ok 289 PouchDB was called with 'dbName' as 1-st argument
ok 290 ThaliSendNotificationBasedOnReplication was called once
ok 291 ThaliSendNotificationBasedOnReplication was called with 4 arguments
ok 292 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
ok 293 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
ok 294 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
ok 295 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
ok 296 ThaliPullReplicationFromNotification was called once
ok 297 ThaliPullReplicationFromNotification was called with 4 arguments
ok 298 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
ok 299 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
ok 300 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
ok 301 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
ok 302 Salti was called once
ok 303 Salti was called with 4 arguments
ok 304 Salti was called with 'dbName' as 1-st argument
ok 305 Salti was called with 'acl' as 2-st argument
ok 306 Salti was called with 'thaliIdCallback' as 3-st argument
ok 307 Salti was called with 'options' as 4-st argument
2016-11-03 12:06:18 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-03 12:06:18 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-03 12:06:18 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-03 12:06:18 - DEBUG thaliMobileNativeWrapper: 'listening 49841'
2016-11-03 12:06:18 - DEBUG createNativeListener: 'creating native server'
2016-11-03 12:06:18 - DEBUG createNativeListener: 'listening 49842'
2016-11-03 12:06:18 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-03 12:06:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-03 12:06:18 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-03 12:06:18 - DEBUG thaliWifiInfrastructure: 'listening 49843'
2016-11-03 12:06:18 - DEBUG thaliWifiInfrastructure: 'listening 49845'
2016-11-03 12:06:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-11-03 12:06:18 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
ok 308 ThaliMobile.start was called once
ok 309 ThaliMobile.start was called with 3 arguments
ok 310 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
ok 311 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
ok 312 ThaliMobile.start was called with 'networkType' as 3-st argument
ok 313 ThaliMobile.startListeningForAdvertisements was called once
ok 314 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
ok 315 ThaliMobile.startUpdateAdvertisingAndListening was called once
ok 316 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
ok 317 ThaliSendNotificationBasedOnReplication.prototype.start was called once
ok 318 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
ok 319 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
ok 320 ThaliPullReplicationFromNotification.prototype.start was called once
ok 321 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
ok 322 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
2016-11-03 12:06:18 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-03 12:06:18 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-03 12:06:18 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-03 12:06:18 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-03 12:06:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-03 12:06:18 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-03 12:06:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-03 12:06:18 - DEBUG thaliManager: 'stopping ThaliMobile'
ok 323 ThaliMobile.stop was called once
ok 324 ThaliMobile.stop was called with 0 arguments
ok 325 ThaliMobile.stopListeningForAdvertisements was called once
ok 326 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
ok 327 ThaliMobile.stopAdvertisingAndListening was called once
ok 328 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
ok 329 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
ok 330 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
ok 331 ThaliPullReplicationFromNotification.prototype.stop was called once
ok 332 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
2016-11-03 12:06:19 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-03 12:06:19 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-03 12:06:19 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-03 12:06:19 - DEBUG thaliMobileNativeWrapper: 'listening 49846'
2016-11-03 12:06:19 - DEBUG createNativeListener: 'creating native server'
2016-11-03 12:06:19 - DEBUG createNativeListener: 'listening 49847'
2016-11-03 12:06:19 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-03 12:06:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-03 12:06:19 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-03 12:06:19 - DEBUG thaliWifiInfrastructure: 'listening 49848'
2016-11-03 12:06:19 - DEBUG thaliWifiInfrastructure: 'listening 49850'
2016-11-03 12:06:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-11-03 12:06:19 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
2016-11-03 12:06:19 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-03 12:06:19 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-03 12:06:19 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-03 12:06:19 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-03 12:06:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-03 12:06:19 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-03 12:06:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-03 12:06:19 - DEBUG thaliManager: 'stopping ThaliMobile'
2016-11-03 12:06:19 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-03 12:06:19 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-03 12:06:19 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-03 12:06:19 - DEBUG thaliMobileNativeWrapper: 'listening 49851'
2016-11-03 12:06:19 - DEBUG createNativeListener: 'creating native server'
2016-11-03 12:06:19 - DEBUG createNativeListener: 'listening 49852'
2016-11-03 12:06:19 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-03 12:06:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-03 12:06:19 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-03 12:06:19 - DEBUG thaliWifiInfrastructure: 'listening 49853'
2016-11-03 12:06:19 - DEBUG thaliWifiInfrastructure: 'listening 49855'
2016-11-03 12:06:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-11-03 12:06:19 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
2016-11-03 12:06:19 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-03 12:06:19 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-03 12:06:19 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-03 12:06:19 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-03 12:06:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-03 12:06:19 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-03 12:06:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-03 12:06:19 - DEBUG thaliManager: 'stopping ThaliMobile'
2016-11-03 12:06:19 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-03 12:06:19 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-03 12:06:19 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-03 12:06:19 - DEBUG thaliMobileNativeWrapper: 'listening 49856'
2016-11-03 12:06:19 - DEBUG createNativeListener: 'creating native server'
2016-11-03 12:06:19 - DEBUG createNativeListener: 'listening 49857'
2016-11-03 12:06:19 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-03 12:06:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-03 12:06:19 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-03 12:06:19 - DEBUG thaliWifiInfrastructure: 'listening 49858'
2016-11-03 12:06:19 - DEBUG thaliWifiInfrastructure: 'listening 49860'
2016-11-03 12:06:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-11-03 12:06:19 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
ok 333 ThaliMobile.start was called once
ok 334 ThaliMobile.start was called with 3 arguments
ok 335 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
ok 336 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
ok 337 ThaliMobile.start was called with 'networkType' as 3-st argument
ok 338 ThaliMobile.startListeningForAdvertisements was called once
ok 339 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
ok 340 ThaliMobile.startUpdateAdvertisingAndListening was called once
ok 341 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
ok 342 ThaliSendNotificationBasedOnReplication.prototype.start was called once
ok 343 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
ok 344 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
ok 345 ThaliPullReplicationFromNotification.prototype.start was called once
ok 346 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
ok 347 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
2016-11-03 12:06:19 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-03 12:06:19 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-03 12:06:19 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-03 12:06:19 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-03 12:06:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-03 12:06:19 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-03 12:06:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-03 12:06:19 - DEBUG thaliManager: 'stopping ThaliMobile'
# teardown
# setup
# #startListeningForAdvertisements should fail if start not called
ok 348 specific error should be returned
# teardown
ok 349 error should be null
ok 350 error should be null
# setup
# #startUpdateAdvertisingAndListening should fail if start not called
ok 351 specific error should be returned
# teardown
ok 352 error should be null
ok 353 error should be null
# setup
# should be able to call #stopListeningForAdvertisements many times
2016-11-03 12:06:19 - DEBUG thaliMobileNativeWrapper: 'listening 49861'
2016-11-03 12:06:19 - DEBUG createNativeListener: 'creating native server'
2016-11-03 12:06:19 - DEBUG createNativeListener: 'listening 49862'
ok 354 error should be null
ok 355 error should be null
ok 356 error should be null
ok 357 error should be null
# teardown
ok 358 error should be null
ok 359 error should be null
# setup
# should be able to call #startListeningForAdvertisements many times
2016-11-03 12:06:19 - DEBUG thaliMobileNativeWrapper: 'listening 49863'
2016-11-03 12:06:19 - DEBUG createNativeListener: 'creating native server'
2016-11-03 12:06:19 - DEBUG createNativeListener: 'listening 49864'
2016-11-03 12:06:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 360 error should be null
ok 361 error should be null
ok 362 error should be null
ok 363 error should be null
# teardown
2016-11-03 12:06:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-03 12:06:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-03 12:06:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 364 error should be null
ok 365 error should be null
# setup
# should be able to call #startUpdateAdvertisingAndListening many times
2016-11-03 12:06:19 - DEBUG thaliMobileNativeWrapper: 'listening 49865'
2016-11-03 12:06:19 - DEBUG createNativeListener: 'creating native server'
2016-11-03 12:06:19 - DEBUG createNativeListener: 'listening 49866'
2016-11-03 12:06:19 - DEBUG thaliWifiInfrastructure: 'listening 49867'
2016-11-03 12:06:19 - DEBUG thaliWifiInfrastructure: 'listening 49869'
2016-11-03 12:06:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 366 error should be null
ok 367 error should be null
ok 368 error should be null
ok 369 error should be null
# teardown
2016-11-03 12:06:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-03 12:06:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-03 12:06:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 370 error should be null
ok 371 error should be null
# setup
# should be able to call #stopAdvertisingAndListening many times
2016-11-03 12:06:19 - DEBUG thaliMobileNativeWrapper: 'listening 49870'
2016-11-03 12:06:19 - DEBUG createNativeListener: 'creating native server'
2016-11-03 12:06:19 - DEBUG createNativeListener: 'listening 49871'
ok 372 error should be null
ok 373 error should be null
ok 374 error should be null
ok 375 error should be null
# teardown
ok 376 error should be null
ok 377 error should be null
# setup
# #start should fail if called twice in a row
2016-11-03 12:06:19 - DEBUG thaliMobileNativeWrapper: 'listening 49872'
2016-11-03 12:06:19 - DEBUG createNativeListener: 'creating native server'
2016-11-03 12:06:19 - DEBUG createNativeListener: 'listening 49873'
ok 378 first call should succeed
ok 379 first call should succeed
ok 380 specific error should be returned
# teardown
ok 381 error should be null
ok 382 error should be null
# setup
# does not emit duplicate discoveryAdvertisingStateUpdate
2016-11-03 12:06:19 - DEBUG SimpleThaliTape: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
# teardown
ok 383 error should be null
ok 384 error should be null
# setup
# does not send duplicate availability changes
ok 385 should be called once
ok 386 should not have been called more than once
# teardown
ok 387 error should be null
ok 388 error should be null
# setup
# can get the network status
ok 389 network status should have certain non-empty properties
# teardown
ok 390 error should be null
ok 391 error should be null
# setup
# wifi peer is marked unavailable if announcements stop
2016-11-03 12:06:19 - DEBUG SimpleThaliTape: 'test was skipped, name: 'wifi peer is marked unavailable if announcements stop''
# teardown
ok 392 error should be null
ok 393 error should be null
# setup
# network changes emitted correctly
2016-11-03 12:06:19 - DEBUG SimpleThaliTape: 'test was skipped, name: 'network changes emitted correctly''
# teardown
ok 394 error should be null
ok 395 error should be null
# setup
# network changes not emitted in stopped state
ok 396 event was not emitted
2016-11-03 12:06:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-03 12:06:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
# teardown
ok 397 error should be null
ok 398 error should be null
# setup
# calls correct starts when network changes
2016-11-03 12:06:19 - DEBUG SimpleThaliTape: 'test was skipped, name: 'calls correct starts when network changes''
# teardown
ok 399 error should be null
ok 400 error should be null
# setup
# peer is marked unavailable if port number changes
2016-11-03 12:06:19 - DEBUG thaliMobileNativeWrapper: 'listening 49874'
2016-11-03 12:06:19 - DEBUG createNativeListener: 'creating native server'
2016-11-03 12:06:19 - DEBUG createNativeListener: 'listening 49875'
ok 401 peer should have a non-empty identifier
ok 402 peer should have a non-empty host address
ok 403 peer should have port number
ok 404 peer should have suggested timeout
ok 405 peer should have a connection type
ok 406 connection type should match one of the pre-defined types
ok 407 peer should have a non-empty identifier
ok 408 host address should be null
ok 409 port number should be null
ok 410 peer should have suggested timeout
ok 411 peer should have a connection type
ok 412 connection type should match one of the pre-defined types
ok 413 port number must match
ok 414 peer should have a non-empty identifier
ok 415 peer should have a non-empty host address
ok 416 peer should have port number
ok 417 peer should have suggested timeout
ok 418 peer should have a connection type
ok 419 connection type should match one of the pre-defined types
# teardown
ok 420 error should be null
ok 421 error should be null
# setup
# when network connection is lost a peer should be marked unavailable
2016-11-03 12:06:19 - DEBUG thaliMobileNativeWrapper: 'listening 49876'
2016-11-03 12:06:19 - DEBUG createNativeListener: 'creating native server'
2016-11-03 12:06:19 - DEBUG createNativeListener: 'listening 49877'
2016-11-03 12:06:19 - INFO testUtils: 'Toggling radios to: false'
2016-11-03 12:06:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-03 12:06:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
ok 422 peer should have a non-empty identifier
ok 423 host address should be null
ok 424 port number should be null
ok 425 peer should have suggested timeout
ok 426 peer should have a connection type
ok 427 connection type should match one of the pre-defined types
2016-11-03 12:06:19 - INFO testUtils: 'Toggling radios to: true'
2016-11-03 12:06:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
# teardown
ok 428 error should be null
ok 429 error should be null
2016-11-03 12:06:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
# setup
# Can call start/stopListeningForAdvertisements
2016-11-03 12:06:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-03 12:06:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-03 12:06:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 430 Can call startListeningForAdvertisements without error
2016-11-03 12:06:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-03 12:06:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 431 Can call stopListeningForAdvertisements without error
# teardown
ok 432 Should be able to call stopListeningForAdvertisements in teardown
ok 433 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Calling startListeningForAdvertisements twice is NOT an error
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-03 12:06:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-03 12:06:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 434 Can call startListeningForAdvertisements without error
ok 435 Can call startListeningForAdvertisements twice without error
# teardown
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-03 12:06:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 436 Should be able to call stopListeningForAdvertisements in teardown
ok 437 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Calling stopListeningForAdvertisements without calling start is NOT an error
ok 438 Can call stopListeningForAdvertisements without error
ok 439 Can call stopListeningForAdvertisements without error
# teardown
ok 440 Should be able to call stopListeningForAdvertisements in teardown
ok 441 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Can call start/stopUpdateAdvertisingAndListening
2016-11-03 12:06:20 - DEBUG thaliWifiInfrastructure: 'listening 49879'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2016-11-03 12:06:20 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-03 12:06:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 442 Can call startUpdateAdvertisingAndListening without error
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-03 12:06:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 443 Can call stopAdvertisingAndListening without error
# teardown
ok 444 Should be able to call stopListeningForAdvertisements in teardown
ok 445 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Calling startUpdateAdvertisingAndListening twice is NOT an error
2016-11-03 12:06:20 - DEBUG thaliWifiInfrastructure: 'listening 49881'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2016-11-03 12:06:20 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-03 12:06:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 446 Can call startUpdateAdvertisingAndListening without error
ok 447 Can call startUpdateAdvertisingAndListening twice without error
# teardown
ok 448 Should be able to call stopListeningForAdvertisements in teardown
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-03 12:06:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 449 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
ok 450 Can call startUpdateAdvertisingAndListening without error
ok 451 Can call stopAdvertisingAndListening without error
# teardown
ok 452 Should be able to call stopListeningForAdvertisements in teardown
ok 453 Should be able to call stopAdvertisingAndListening in teardown
# setup
# cannot call connect when start listening for advertisements is not active
ok 454 got right error
# teardown
ok 455 Should be able to call stopListeningForAdvertisements in teardown
ok 456 Should be able to call stopAdvertisingAndListening in teardown
# setup
# #startListeningForAdvertisements should fail if start not called
ok 457 specific error should be returned
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 458 must be stopped
# setup
# #startUpdateAdvertisingAndListening should fail if start not called
ok 459 specific error should be returned
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 460 must be stopped
# setup
# should be able to call #stopListeningForAdvertisements many times
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'listening 49882'
2016-11-03 12:06:20 - DEBUG createNativeListener: 'creating native server'
2016-11-03 12:06:20 - DEBUG createNativeListener: 'listening 49883'
ok 461 no errors
ok 462 still no errors
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 463 must be stopped
# setup
# should be able to call #startListeningForAdvertisements many times
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'listening 49884'
2016-11-03 12:06:20 - DEBUG createNativeListener: 'creating native server'
2016-11-03 12:06:20 - DEBUG createNativeListener: 'listening 49885'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-03 12:06:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-03 12:06:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 464 no errors
ok 465 still no errors
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-03 12:06:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 466 must be stopped
# setup
# should be able to call #startUpdateAdvertisingAndListening many times
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'listening 49886'
2016-11-03 12:06:20 - DEBUG createNativeListener: 'creating native server'
2016-11-03 12:06:20 - DEBUG createNativeListener: 'listening 49887'
2016-11-03 12:06:20 - DEBUG thaliWifiInfrastructure: 'listening 49889'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2016-11-03 12:06:20 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-03 12:06:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 467 no errors
ok 468 still no errors
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-03 12:06:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 469 must be stopped
# setup
# should be able to call #stopAdvertisingAndListening many times
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'listening 49890'
2016-11-03 12:06:20 - DEBUG createNativeListener: 'creating native server'
2016-11-03 12:06:20 - DEBUG createNativeListener: 'listening 49891'
ok 470 no errors
ok 471 still no errors
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 472 must be stopped
# setup
# can get the network status before starting
ok 473 network status should have certain non-empty properties
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 474 must be stopped
# setup
# error returned with bad router
2016-11-03 12:06:20 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 475 specific error expected
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 476 must be stopped
# setup
# all services are stopped when we call stop
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'listening 49892'
2016-11-03 12:06:20 - DEBUG createNativeListener: 'creating native server'
2016-11-03 12:06:20 - DEBUG createNativeListener: 'listening 49893'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-03 12:06:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-03 12:06:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-03 12:06:20 - DEBUG thaliWifiInfrastructure: 'listening 49895'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-11-03 12:06:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-03 12:06:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-03 12:06:20 - DEBUG createNativeListener: 'new incoming socket'
2016-11-03 12:06:20 - DEBUG createNativeListener: 'creating incoming mux'
2016-11-03 12:06:20 - DEBUG createNativeListener: 'new mux'
not ok 477 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
ok 478 connection to servers manager should succeed after starting
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
not ok 479 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
ok 480 connection to router server should succeed after starting
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-03 12:06:20 - DEBUG createNativeListener: 'incoming socket close'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-03 12:06:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-03 12:06:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-03 12:06:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 481 is stopped after calling stop
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
ok 482 connection to servers manager should fail after stopping
ok 483 connection to router server should fail after stopping
# teardown
ok 484 must be stopped
# setup
# make sure terminateConnection is properly hooked up
ok 485 called with right arguments
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 486 must be stopped
# setup
# make sure terminateListener is properly hooked up
ok 487 called with right arguments
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 488 must be stopped
# setup
# make sure we actually call kill connections properly
ok 489 specific error expected
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 490 must be stopped
# setup
# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'listening 49900'
2016-11-03 12:06:20 - DEBUG createNativeListener: 'creating native server'
2016-11-03 12:06:20 - DEBUG createNativeListener: 'listening 49901'
2016-11-03 12:06:20 - INFO thaliMobileNativeWrapper: 'routerPortConnectionFailed - {"routerPort":49900,"error":{}}'
ok 491 failure reason is as expected
ok 492 error description is as expected
ok 493 must be stopped
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 494 must be stopped
# setup
# We repeat failedConnection event when we get it from thaliTcpServersManager
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'listening 49902'
2016-11-03 12:06:20 - DEBUG createNativeListener: 'creating native server'
2016-11-03 12:06:20 - DEBUG createNativeListener: 'listening 49903'
ok 495 peerIdentifier matches
ok 496 error description matches
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 497 must be stopped
# setup
# can do HTTP requests between peers without coordinator
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'listening 49904'
2016-11-03 12:06:20 - DEBUG createNativeListener: 'creating native server'
2016-11-03 12:06:20 - DEBUG createNativeListener: 'listening 49905'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-03 12:06:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-03 12:06:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-03 12:06:20 - DEBUG thaliWifiInfrastructure: 'listening 49907'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-11-03 12:06:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-03 12:06:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-03 12:06:20 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-11-03 12:06:20 - DEBUG createPeerListener: 'listening 49908'
2016-11-03 12:06:20 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-03 12:06:20 - DEBUG testUtils: 'We got a peer {"peerIdentifier":"foo","portNumber":49908,"hostAddress":"127.0.0.1"}'
2016-11-03 12:06:20 - WARN testUtils: 'Retry count for getSamePeerWithRetry is 1'
not ok 498 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
2016-11-03 12:06:20 - DEBUG createPeerListener: 'first connection'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
not ok 499 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 500 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-03 12:06:20 - DEBUG createNativeListener: 'new incoming socket'
2016-11-03 12:06:20 - DEBUG createNativeListener: 'creating incoming mux'
2016-11-03 12:06:20 - DEBUG createNativeListener: 'new mux'
not ok 501 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
2016-11-03 12:06:20 - DEBUG wifiBasedNativeMock: 'proxy socket connected'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
2016-11-03 12:06:20 - DEBUG createPeerListener: 'forward connection'
not ok 502 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 503 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 504 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
2016-11-03 12:06:20 - DEBUG createNativeListener: 'new stream: '
2016-11-03 12:06:20 - DEBUG createNativeListener: 'new outgoing socket'
not ok 505 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 506 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
ok 507 Should only get expected id
ok 508 response body should match testData
# teardown
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-03 12:06:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-03 12:06:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-03 12:06:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-03 12:06:20 - DEBUG createNativeListener: 'stream close:'
2016-11-03 12:06:20 - DEBUG createNativeListener: 'mux close'
ok 509 must be stopped
2016-11-03 12:06:20 - DEBUG createNativeListener: 'incoming socket close'
# setup
# make sure bad PSK connections fail
ok 510 FIX ME, PLEASE!!!
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 511 must be stopped
# setup
# peer changes handled from a queue
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'listening 49915'
2016-11-03 12:06:20 - DEBUG createNativeListener: 'creating native server'
2016-11-03 12:06:20 - DEBUG createNativeListener: 'listening 49916'
2016-11-03 12:06:20 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-11-03 12:06:20 - DEBUG createPeerListener: 'listening 49917'
2016-11-03 12:06:20 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-03 12:06:20 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-11-03 12:06:20 - DEBUG createPeerListener: 'listening 49918'
2016-11-03 12:06:20 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-03 12:06:20 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-11-03 12:06:20 - DEBUG createPeerListener: 'listening 49919'
2016-11-03 12:06:20 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-03 12:06:20 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-11-03 12:06:20 - DEBUG createPeerListener: 'listening 49920'
2016-11-03 12:06:20 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-03 12:06:20 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-11-03 12:06:20 - DEBUG createPeerListener: 'listening 49921'
2016-11-03 12:06:20 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-03 12:06:20 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-11-03 12:06:20 - DEBUG createPeerListener: 'listening 49922'
2016-11-03 12:06:20 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-03 12:06:20 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-11-03 12:06:20 - DEBUG createPeerListener: 'listening 49923'
2016-11-03 12:06:20 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-03 12:06:20 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-11-03 12:06:20 - DEBUG createPeerListener: 'listening 49924'
2016-11-03 12:06:20 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-03 12:06:20 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-11-03 12:06:20 - DEBUG createPeerListener: 'listening 49925'
2016-11-03 12:06:20 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-03 12:06:20 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-11-03 12:06:20 - DEBUG createPeerListener: 'listening 49926'
2016-11-03 12:06:20 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 512 peers were handled in the right order
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 513 must be stopped
# setup
# relaying discoveryAdvertisingStateUpdateNonTCP
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'listening 49927'
2016-11-03 12:06:20 - DEBUG createNativeListener: 'creating native server'
2016-11-03 12:06:20 - DEBUG createNativeListener: 'listening 49928'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-11-03 12:06:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-03 12:06:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 514 discovery is active
ok 515 advertising is active
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 516 must be stopped
# setup
# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'listening 49929'
2016-11-03 12:06:20 - DEBUG createNativeListener: 'creating native server'
2016-11-03 12:06:20 - DEBUG createNativeListener: 'listening 49930'
2016-11-03 12:06:20 - DEBUG thaliWifiInfrastructure: 'listening 49932'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2016-11-03 12:06:20 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-03 12:06:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-03 12:06:20 - INFO thaliMobileNativeWrapper: 'incomingConnectionToPortNumberFailed: 49930'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-03 12:06:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 517 right error reason
ok 518 Stop should be fine
ok 519 same port
ok 520 we should be off
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 521 must be stopped
# setup
# we successfully receive and replay discoveryAdvertisingStateUpdate
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'listening 49933'
2016-11-03 12:06:20 - DEBUG createNativeListener: 'creating native server'
2016-11-03 12:06:20 - DEBUG createNativeListener: 'listening 49934'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-03 12:06:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-03 12:06:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 522 discoveryActive matches
ok 523 advertisingActive matches
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-03 12:06:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 524 discoveryActive matches
ok 525 advertisingActive matches
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'listening 49935'
2016-11-03 12:06:20 - DEBUG createNativeListener: 'creating native server'
2016-11-03 12:06:20 - DEBUG createNativeListener: 'listening 49936'
2016-11-03 12:06:20 - DEBUG thaliWifiInfrastructure: 'listening 49938'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2016-11-03 12:06:20 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-03 12:06:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 526 discoveryActive matches
ok 527 advertisingActive matches
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-03 12:06:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 528 discoveryActive matches
ok 529 advertisingActive matches
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'listening 49939'
2016-11-03 12:06:20 - DEBUG createNativeListener: 'creating native server'
2016-11-03 12:06:20 - DEBUG createNativeListener: 'listening 49940'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-03 12:06:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 530 must be stopped
# setup
# Test BEACONS_RETRIEVED_AND_PARSED locally
not ok 531 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 532 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
ok 533 peerIdentifier should be identifier
ok 534 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 535 good beacon
ok 536 good preAmble
ok 537 public keys match!
ok 538 must return null after successful call
ok 539 Once start returns the action should be in KILLED state
# teardown
# setup
# Test HTTP_BAD_RESPONSE locally
not ok 540 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 541 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
ok 542 Response should be HTTP_BAD_RESPONSE
ok 543 must return null after successful call
# teardown
# setup
# Test NETWORK_PROBLEM locally
not ok 544 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
ok 545 Response should be NETWORK_PROBLEM
ok 546 reject reason should be: Could not establish TCP connection
# teardown
# setup
# Call the start two times
not ok 547 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
ok 548 Call start once
not ok 549 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
ok 550 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 551 must return null after successful call.
# teardown
# setup
# Call the kill before calling the start
ok 552 Should be Killed
ok 553 Start after killed
# teardown
# setup
# Call the kill immediately after the start
ok 554 Should be KILLED
ok 555 must return null after successful kill
# teardown
# setup
# Call the kill while waiting a response from the server
not ok 556 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 557 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
ok 558 Should be KILLED
ok 559 must return null after successful kill
# teardown
# setup
# Test to exceed the max content size locally
not ok 560 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 561 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
ok 562 HTTP_BAD_RESPONSE should be response when content size is exceeded
ok 563 must return null after successful call
# teardown
# setup
# Close the server socket while the client is waiting a response from the server. Local test.
not ok 564 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 565 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
ok 566 Should be NETWORK_PROBLEM caused closing server socket
ok 567 Should be Could not establish TCP connection
# teardown
# setup
# Close the client socket while the client is waiting a response from the server. Local test.
not ok 568 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 569 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
ok 570 Should be NETWORK_PROBLEM caused closing client socket
ok 571 Should be Could not establish TCP connection
# teardown
# setup
# #generatePreambleAndBeacons bad args
ok 572 publicKeysToNotify cannot be null
ok 573 ecdh for local device cannot be null
ok 574 milliseconds cannot be less than 0
ok 575 milliseconds cannot be 0
ok 576 milliseconds cannot be greater than one_day
# teardown
# setup
# #generatePreambleAndBeacons empty keys to notify
ok 577 should be equal
# teardown
# setup
# #generatePreambleAndBeacons multiple keys to notify
ok 578 should be equal
ok 579 should be equal
ok 580 (unnamed assert)
ok 581 should be equal
# teardown
# setup
# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
ok 582 should throw
# teardown
# setup
# #parseBeacons invalid expiration in beaconStreamWithPreAmble
ok 583 Preamble expiration must be a 64 bit integer
# teardown
# setup
# #parseBeacons expiration out of range lower
ok 584 Expiration out of range
# teardown
# setup
# #parseBeacons expiration out of range lower
ok 585 Expiration out of range
# teardown
# setup
# #parseBeacons no beacons returns null
ok 586 should be equal
# teardown
# setup
# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
ok 587 Malformed encrypted beacon key ID
# teardown
# setup
# #parseBeacons addressBookCallback fails decrypt
ok 588 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns no matches
ok 589 should be equal
ok 590 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns spurious match
ok 591 should be equal
ok 592 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns public key
ok 593 right number of calls to address book
ok 594 good preAmble
ok 595 good unencryptedKeyId
ok 596 good beacon
# teardown
# setup
# validate generatePskIdentityField
ok 597 decoded buffers match
# teardown
# setup
# validate generatePskSecret
ok 598 secrets match
# teardown
# setup
# validate generatePskSecrets
ok 599 Matching numbers
ok 600 We have an entry!
ok 601 keys match
ok 602 secrets match
ok 603 We have an entry!
ok 604 keys match
ok 605 secrets match
ok 606 We have an entry!
ok 607 keys match
ok 608 secrets match
# teardown
# setup
# validate generateBeaconStreamAndSecrets
ok 609 Streams have same length
ok 610 matching size
ok 611 keys match
ok 612 secrets match
# teardown
# setup
# Add two Peers.
ok 613 should be equal
ok 614 should be equal
ok 615 should be equal
ok 616 should be equal
ok 617 should be equal
# teardown
# setup
# TCP_NATIVE peer loses DNS
ok 618 should be equal
ok 619 should be equal
# teardown
# setup
# Received beacons with no values for us
not ok 620 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 621 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
ok 622 entry exists
ok 623 entry is resolved
# teardown
# setup
# Notification action killed with a superseded
ok 624 Action should be killed
ok 625 should be equal
# teardown
# setup
# Resolves an action locally
not ok 626 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 627 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
ok 628 Host address must match
ok 629 suggestedTCPTimeout must match
ok 630 connectionType must match
ok 631 portNumber must match
# teardown
# setup
# Resolves an action locally using ThaliPeerPoolDefault
not ok 632 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 633 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
ok 634 Host address must match
ok 635 suggestedTCPTimeout must match
ok 636 connectionType must match
ok 637 portNumber must match
# teardown
# setup
# Action fails because of a bad hostname.
ok 638 action should be resolved with NETWORK_PROBLEM error
ok 639 action should be resolved with NETWORK_PROBLEM error
ok 640 action should be resolved with NETWORK_PROBLEM error
ok 641 action should be resolved with NETWORK_PROBLEM error
ok 642 correct number of requests
ok 643 correct number of failures
ok 644 correct final peer state
# teardown
# setup
# hostaddress is removed when the action is running. 
not ok 645 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
ok 646 should be equal
# teardown
# setup
# Client to server request locally
not ok 647 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 648 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
ok 649 secrets are equal
ok 650 Public key matches with the server key
ok 651 Host address must match
ok 652 suggestedTCPTimeout must match
ok 653 connectionType must match
ok 654 portNumber must match
# teardown
# setup
# Test ThaliPskMapCache clean and expiration
ok 655 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
ok 656 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
ok 657 All entries should be expired after 1 second
# teardown
# setup
# Test ThaliPskMapCache getSecret and getPublic
ok 658 All keys need to be available in the cache
ok 659 All entries should be expired after 1 second
# teardown
# setup
# Test ThaliPskMapCache multiple entries
ok 660 Size of the cache should be 2
ok 661 Cache doesn't contain dictionary1
ok 662 Size of the cache should be 1
ok 663 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
# setup
# Start and stop ThaliNotificationServer
ok 664 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
ok 665 ThaliMobile.StopAdvertisingAndListeningshould be called once
# teardown
# setup
# Pass an empty array to ThaliNotificationServer.start
ok 666 StartUpdateAdvertisingAndListening should not be called
ok 667 ThaliMobile.StopAdvertisingAndListening should be called once
ok 668 no error
ok 669 should be 204
# teardown
# setup
# Pass a string to ThaliNotificationServer.start
ok 670 StartUpdateAdvertisingAndListening should not be called
# teardown
# setup
# Pass an empty parameter to ThaliNotificationServer.start
ok 671 StartUpdateAdvertisingAndListening should not be called
# teardown
# setup
# Make an HTTP request to /NotificationBeacons
ok 672 no error
ok 673 should be 200
ok 674 should be equal
ok 675 should be equal
ok 676 (unnamed assert)
ok 677 no error
ok 678 should be 204
# teardown
# setup
# Make an HTTP request to /NotificationBeacons (no keys)
ok 679 error should be null
ok 680 should be 204
# teardown
# setup
# Make an HTTP request to /NotificationBeaconsbefore calling start
ok 681 should be 404
# teardown
# setup
# #testThaliPeerAction - test getters
ok 682 getPeerIdentifier
ok 683 getConnectionType
ok 684 getActionType
ok 685 getActionState
ok 686 getPskIdentity
ok 687 getPskKey
# teardown
# setup
# #testThaliPeerAction - start and kill
ok 688 initial state
ok 689 after start
ok 690 after kill
# teardown
# setup
# #testThaliPeerAction - double start
ok 691 should be equal
# teardown
# setup
# #testThaliPeerAction - start after kill
ok 692 clean kill
ok 693 should be equal
# teardown
# setup
# #testThaliPeerAction - make sure ids are unique
ok 694 should not be equal
# teardown
# setup
# Test PeerConnectionInformation basics
ok 695 connection type works
ok 696 getHostAddress works
ok 697 getPortNumber works
ok 698 getSuggestedTCPTimeout works
# teardown
# setup
# Test PeerDictionary basic functionality
ok 699 Entry counter must be 1
ok 700 Size must be 1
ok 701 Entry counter must be 2
ok 702 Size must be 2
ok 703 Entry2 should not be found
ok 704 Size must be 1
ok 705 Size must be 0
# teardown
# setup
# Test PeerDictionary with multiple entries.
ok 706 Size must be100
ok 707 Entries between 20 and MAXSIZE + 20 should exist
ok 708 WAITING state entry should not be removed
# teardown
# setup
# RESOLVED entries are removed before WAITING state entry.
ok 709 Entries between 6 and MAXSIZE + 4 should exist
ok 710 Size should be MAXSIZE
ok 711 Size should be MAXSIZE+6
# teardown
# setup
# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
ok 712 WAITING state entry should not be removed
ok 713 Waiting entries between 6 and MAXSIZE + 4 should exist
ok 714 Size should be MAXSIZE
ok 715 entryCounter should be MAXSIZE+6
# teardown
# setup
# When CONTROLLED_BY_POOL entry is removed and kill is called.
ok 716 Kill should be called once
ok 717 Size should be 100
# teardown
# setup
# #ThaliPeerPoolDefault - single action
ok 718 is an agent
ok 719 enqueue is fine
ok 720 Everything should be off the queue
# teardown
# setup
# #ThaliPeerPoolDefault - multiple actions
ok 721 is an agent
ok 722 first enqueue is fine
ok 723 is an agent
ok 724 second enqueue is fine
ok 725 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 726 Queue is empty
# teardown
# setup
# #ThaliPeerPoolDefault - PSK Pool works
ok 727 is an agent
ok 728 good enqueue
not ok 729 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 730 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
ok 731 Identity should match
ok 732 Got expected response
ok 733 Got psk call back
# teardown
# setup
# #ThaliPeerPoolDefault - stop
ok 734 is an agent
ok 735 enqueue worked
ok 736 is an agent
ok 737 enqueue 2 worked
ok 738 enqueue is not available when stopped
ok 739 start action is killed
ok 740 killed action is still killed
ok 741 inQueue is empty
# teardown
# setup
# #ThaliPeerPoolInterface - make sure that start verifies queue length
ok 742 good start
ok 743 good enqueue
ok 744 queue is not empty
# teardown
# setup
# #ThaliPeerPoolInterface - bad enqueues
ok 745 null arg
ok 746 wrong arg type
ok 747 wrong arg type
# teardown
# setup
# #ThaliPeerPoolInterface - do not allow same object type
ok 748 good enqueue
ok 749 already enqueued
# teardown
# setup
# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
ok 750 good enqueue
ok 751 2nd good enqueue
ok 752 we are in the pool
ok 753 We are out of the pool
ok 754 Action was killed
ok 755 The original kill was called too
ok 756 second item is still in queue
# teardown
# setup
# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
ok 757 good enqueue
ok 758 first kill
ok 759 second NOOP kill
# teardown
# setup
# #ThaliPeerPoolInterface - make sure that stop removes all actions
ok 760 1st good enqueue
ok 761 2nd good enqueue
ok 762 1st action is in the pool
ok 763 2nd action is in the pool
ok 764 1st action is out of the pool
ok 765 2st action is out of the pool
ok 766 pool is empty
# teardown
# setup
# #ThaliPeerPoolOneAtATime - single action
ok 767 is an agent
ok 768 enqueue is fine
ok 769 Everything should be off the queue
# teardown
# setup
# #ThaliPeerPoolOneAtATime - multiple actions
ok 770 is an agent
ok 771 first enqueue is fine
ok 772 is an agent
ok 773 second enqueue is fine
ok 774 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 775 Queue is empty
# teardown
# setup
# #ThaliPeerPoolOneAtATime - PSK Pool works
ok 776 is an agent
ok 777 good enqueue
not ok 778 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 779 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
ok 780 Identity should match
ok 781 Got expected response
ok 782 Got psk call back
# teardown
# setup
# #ThaliPeerPoolOneAtATime - stop
ok 783 is an agent
ok 784 enqueue worked
ok 785 is an agent
ok 786 enqueue 2 worked
ok 787 enqueue is not available when stopped
ok 788 start action is killed
ok 789 killed action is still killed
ok 790 inQueue is empty
# teardown
# setup
# Make sure peerDictionaryKey is reasonable
ok 791 equal keys
ok 792 not equal connection type
ok 793 same connection type, different buffer
# teardown
# setup
# Make sure start works
2016-11-03 12:06:34 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 794 First start and on called correctly
# teardown
# setup
# Make sure stop works
ok 795 second cleared dictionary
2016-11-03 12:06:34 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 796 First start and on called correctly
ok 797 First stop and removeListener called correctly
ok 798 first action kill called
ok 799 second action kill called
ok 800 first cleared dictionary
ok 801 first cleared pool
ok 802 second cleared dictionary
ok 803 second cleared pool
# teardown
# setup
# Simple peer event
2016-11-03 12:06:34 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 804 listener has been set
ok 805 peer dictionary has expected number of entries
ok 806 Dictionary and pool have same action
ok 807 ads match
ok 808 PouchDB matches
ok 809 DB Names match
ok 810 public keys match
ok 811 peer dictionary has expected number of entries
ok 812 Dictionary and pool have same action
ok 813 ads match
ok 814 PouchDB matches
ok 815 DB Names match
ok 816 public keys match
ok 817 start called once
ok 818 One entry left
ok 819 Dictionary and pool have same action
ok 820 Start never called
ok 821 Kill called once
ok 822 no entries left
ok 823 Third action is dead
ok 824 peer dictionary has expected number of entries
ok 825 Dictionary and pool have same action
ok 826 ads match
ok 827 PouchDB matches
ok 828 DB Names match
ok 829 public keys match
# teardown
# setup
# Server is not there
not ok 830 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 831 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
2016-11-03 12:06:34 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
ok 832 right error
# teardown
# setup
# Server accepts & closes connection
not ok 833 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 834 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
2016-11-03 12:06:34 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
ok 835 right error
# teardown
# setup
# Server always returns 500
not ok 836 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 837 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
2016-11-03 12:06:35 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
ok 838 Got error as expected
# teardown
# setup
# Server always returns 401
not ok 839 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 840 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
2016-11-03 12:06:35 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
ok 841 Got error as expected
# teardown
# setup
# Server always returns 403
not ok 842 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 843 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
2016-11-03 12:06:35 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
ok 844 Got error as expected
# teardown
# setup
# Make sure docs replicate
not ok 845 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 846 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 847 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 848 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 849 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 850 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 851 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 852 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 853 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 854 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 855 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 856 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 857 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 858 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 859 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 860 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 861 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 862 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 863 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 864 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 865 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 866 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 867 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 868 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
2016-11-03 12:06:35 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
not ok 869 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 870 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 871 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 872 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 873 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 874 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 875 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 876 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 877 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 878 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
2016-11-03 12:06:35 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
not ok 879 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 880 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
ok 881 should be equal
ok 882 All tests passed!
# teardown
# setup
# Do nothing and make sure we time out
not ok 883 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 884 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 885 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 886 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
2016-11-03 12:06:35 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
ok 887 action should be killed
ok 888 Error should be timed out
not ok 889 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 890 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
ok 891 No doc found
# teardown
# setup
# Do something and make sure we time out
not ok 892 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 893 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 894 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 895 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 896 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 897 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 898 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 899 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 900 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 901 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 902 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 903 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 904 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 905 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 906 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 907 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 908 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 909 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 910 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 911 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 912 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 913 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 914 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 915 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
2016-11-03 12:06:37 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
not ok 916 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 917 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 918 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 919 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 920 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 921 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 922 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 923 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 924 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 925 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
2016-11-03 12:06:37 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
not ok 926 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 927 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
ok 928 should be equal
ok 929 action should be killed
ok 930 Error should be timed out
# teardown
# setup
# Start replicating and then catch error when server goes
not ok 931 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 932 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 933 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 934 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 935 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 936 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 937 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 938 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 939 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 940 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 941 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 942 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 943 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 944 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 945 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 946 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 947 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 948 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 949 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 950 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 951 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 952 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 953 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 954 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
ok 955 socket hung up
# teardown
# setup
# compareBufferArrays
ok 956 should throw
ok 957 should throw
ok 958 (unnamed assert)
ok 959 (unnamed assert)
ok 960 (unnamed assert)
ok 961 (unnamed assert)
ok 962 (unnamed assert)
# teardown
# setup
# Call start twice and get error
ok 963 should throw
# teardown
# setup
# Start and make sure it runs
# teardown
# setup
# Make sure getTimeWhenRun is right after start
ok 964 (unnamed assert)
# teardown
# setup
# Make sure getTimeWhenRun is -1 after function is called
ok 965 should be equal
# teardown
# setup
# Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
ok 966 should be equal
ok 967 should be equal
ok 968 should throw
# teardown
# setup
# Test TransientState
ok 969 should throw
ok 970 should throw
ok 971 should be equal
ok 972 should be equal
ok 973 should be equal
ok 974 should be equal
ok 975 (unnamed assert)
ok 976 (unnamed assert)
# teardown
# setup
# No peers and empty database
ok 977 verify failed
ok 978 constructor called once
ok 979 constructor called with right args
ok 980 match start arg
ok 981 start called once
ok 982 stop called once
ok 983 stop after start
# teardown
# setup
# One peer and empty DB
ok 984 verify failed
ok 985 constructor called once
ok 986 constructor called with right args
ok 987 match start arg
ok 988 start called once
ok 989 stop called once
ok 990 stop after start
2016-11-03 12:06:40 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# One peer with _Local set behind current seq
ok 991 verify failed
ok 992 constructor called once
ok 993 constructor called with right args
ok 994 match start arg
ok 995 start called once
ok 996 stop called once
ok 997 stop after start
2016-11-03 12:06:40 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# One peer with _Local set equal to current seq
ok 998 verify failed
ok 999 constructor called once
ok 1000 constructor called with right args
ok 1001 match start arg
ok 1002 start called once
ok 1003 stop called once
ok 1004 stop after start
2016-11-03 12:06:40 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# One peer with _Local set ahead of current seq (and no this should not happen)
ok 1005 verify failed
ok 1006 constructor called once
ok 1007 constructor called with right args
ok 1008 match start arg
ok 1009 start called once
ok 1010 stop called once
ok 1011 stop after start
2016-11-03 12:06:40 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# Three peers, one not in DB, one behind and one ahead
ok 1012 verify failed
ok 1013 constructor called once
ok 1014 constructor called with right args
ok 1015 match start arg
ok 1016 start called once
ok 1017 stop called once
ok 1018 stop after start
2016-11-03 12:06:40 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# More than maximum peers, make sure we only send maximum allowed
ok 1019 verify failed
ok 1020 constructor called once
ok 1021 constructor called with right args
ok 1022 match start arg
ok 1023 start called once
ok 1024 stop called once
ok 1025 stop after start
2016-11-03 12:06:40 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# two peers with empty DB, update the doc
2016-11-03 12:06:40 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 1026 verify failed
ok 1027 constructor called once
ok 1028 constructor called with right args
ok 1029 last start before stop
ok 1030 empty first start
ok 1031 full second start
ok 1032 only 2 timers
2016-11-03 12:06:40 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# add doc and make sure tokens refresh when they expire
2016-11-03 12:06:40 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
2016-11-03 12:06:40 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 1033 verify failed
ok 1034 constructor called once
ok 1035 constructor called with right args
ok 1036 start before stop
ok 1037 We got at least 3 calls to start
ok 1038 at least 3
ok 1039 default 1
ok 1040 1 run
ok 1041 default 2
ok 1042 2 run
ok 1043 default 3
2016-11-03 12:06:40 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# start and stop and start and stop
ok 1044 start out null
ok 1045 back to null
2016-11-03 12:06:40 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 1046 still null
ok 1047 verify failed
ok 1048 constructor called once
ok 1049 constructor called with right args
ok 1050 first start before first stop
ok 1051 first stop before second start
ok 1052 second start before second stop
2016-11-03 12:06:40 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# two identical starts in a row
ok 1053 verify failed
ok 1054 constructor called once
ok 1055 constructor called with right args
ok 1056 (unnamed assert)
2016-11-03 12:06:40 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# two different starts in a row
2016-11-03 12:06:40 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 1057 verify failed
ok 1058 constructor called once
ok 1059 constructor called with right args
ok 1060 (unnamed assert)
ok 1061 (unnamed assert)
# teardown
# setup
# two stops and a start and two stops
ok 1062 verify failed
ok 1063 constructor called once
ok 1064 constructor called with right args
ok 1065 start before stop
2016-11-03 12:06:40 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# we properly enqueue requests so no then needed
2016-11-03 12:06:40 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 1066 verify failed
ok 1067 constructor called once
ok 1068 constructor called with right args
ok 1069 start before stop
# teardown
# setup
# test calculateSeqPointKeyId
ok 1070 should be equal
ok 1071 should be equal
# teardown
# setup
# can create servers manager
ok 1072 serversManager must not be null
ok 1073 serversManager must be an object
# teardown
# setup
# calling stop without start causes error
ok 1074 We need to call start first
# teardown
# setup
# can start/stop servers manager
2016-11-03 12:06:40 - DEBUG createNativeListener: 'creating native server'
2016-11-03 12:06:40 - DEBUG createNativeListener: 'listening 50058'
ok 1075 port must be in range
# teardown
# setup
# starting twice resolves with listening port
2016-11-03 12:06:40 - DEBUG createNativeListener: 'creating native server'
2016-11-03 12:06:40 - DEBUG createNativeListener: 'listening 50059'
ok 1076 second start should return same port
# teardown
# setup
# terminateIncomingConnection will terminate a connection
2016-11-03 12:06:40 - DEBUG createNativeListener: 'creating native server'
2016-11-03 12:06:40 - DEBUG createNativeListener: 'listening 50061'
2016-11-03 12:06:40 - DEBUG createNativeListener: 'new incoming socket'
2016-11-03 12:06:40 - DEBUG createNativeListener: 'creating incoming mux'
2016-11-03 12:06:40 - DEBUG createNativeListener: 'new mux'
not ok 1077 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
ok 1078 we should be connected
2016-11-03 12:06:40 - DEBUG createNativeListener: 'incoming socket close'
ok 1079 now we are disconnected
# teardown
# setup
# terminate an Outgoing connection
2016-11-03 12:06:40 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
ok 1080 Passed bogus id
2016-11-03 12:06:40 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
ok 1081 Passed good id but bogus port
2016-11-03 12:06:40 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
ok 1082 Passed right context
ok 1083 Right server
ok 1084 No error should be set
ok 1085 Retry should be false
ok 1086 We called close server
# teardown
# setup
ok 1087 should be in started state
# After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
ok 1088 peer identifier should match
ok 1089 host address should match
ok 1090 port should match
ok 1091 host address should be null
ok 1092 port should should be null
# teardown
ok 1093 should not be in started state
# setup
ok 1094 should be in started state
# #startUpdateAdvertisingAndListening should use different USN after every invocation
2016-11-03 12:06:40 - DEBUG thaliWifiInfrastructure: 'listening 50063'
ok 1095 USN should have changed from the first one
ok 1096 when receiving the second byebye, the first USN should be already set
# teardown
ok 1097 should not be in started state
# setup
ok 1098 should be in started state
# messages with invalid location or USN should be ignored
2016-11-03 12:06:40 - WARN thaliWifiInfrastructure: 'Failed to parse a valid port number from location: http://foo.bar:90000'
ok 1099 should not have emitted with invalid port
2016-11-03 12:06:40 - WARN thaliWifiInfrastructure: 'Received an invalid USN value: '
ok 1100 should not have emitted with invalid USN
# teardown
ok 1101 should not be in started state
# setup
ok 1102 should be in started state
# verify that Thali-specific messages are filtered correctly
ok 1103 irrelevant messages should be ignored
ok 1104 relevant messages should not be ignored
ok 1105 messages from this device should be ignored
# teardown
ok 1106 should not be in started state
# setup
ok 1107 should be in started state
# #startListeningForAdvertisements should fail if start not called
ok 1108 specific error should be returned
# teardown
ok 1109 should not be in started state
# setup
ok 1110 should be in started state
# #startUpdateAdvertisingAndListening should fail if start not called
ok 1111 specific error should be returned
# teardown
ok 1112 should not be in started state
# setup
ok 1113 should be in started state
# #start should fail if called twice in a row
ok 1114 specific error should be received
# teardown
ok 1115 should not be in started state
# setup
ok 1116 should be in started state
# should not be started after stop is called
ok 1117 should not be started
ok 1118 should not be listening
ok 1119 should not target listening
ok 1120 should not be advertising
ok 1121 should not target advertising
# teardown
ok 1122 should not be in started state
# setup
ok 1123 should be in started state
# #startUpdateAdvertisingAndListening should fail invalid router has been passed
2016-11-03 12:06:40 - ERROR thaliWifiInfrastructure: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 1124 specific error should be received
# teardown
ok 1125 should not be in started state
# setup
ok 1126 should be in started state
# #startUpdateAdvertisingAndListening should fail if router server starting fails
2016-11-03 12:06:40 - ERROR thaliWifiInfrastructure: 'Router server emitted an error: Error: listen EADDRINUSE'
ok 1127 specific error expected
# teardown
ok 1128 should not be in started state
# setup
ok 1129 should be in started state
# #startUpdateAdvertisingAndListening should start hosting given router object
2016-11-03 12:06:40 - DEBUG thaliWifiInfrastructure: 'listening 50065'
not ok 1130 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 1131 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
ok 1132 server should respond with code 200
# teardown
ok 1133 should not be in started state
# setup
ok 1134 should be in started state
# #startUpdateAdvertisingAndListening bad psk should be rejected object
2016-11-03 12:06:40 - DEBUG thaliWifiInfrastructure: 'listening 50067'
not ok 1135 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
not ok 1136 we should not create pipe with closed socket
  ---
    operator: fail
    at: Socket.socket.__proto__.pipe (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:932:9)
  ...
ok 1137 Connection should be rejected
# teardown
ok 1138 should not be in started state
# setup
ok 1139 should be in started state
# #stop can be called multiple times in a row
ok 1140 should be in stopped state
ok 1141 should still be in stopped state
# teardown
ok 1142 should not be in started state
# setup
ok 1143 should be in started state
# #startListeningForAdvertisements can be called multiple times in a row
ok 1144 should be in listening state
ok 1145 should still be in listening state
# teardown
ok 1146 should not be in started state
# setup
ok 1147 should be in started state
# #stopListeningForAdvertisements can be called multiple times in a row
ok 1148 should not be in listening state
ok 1149 should still not be in listening state
# teardown
ok 1150 should not be in started state
# setup
ok 1151 should be in started state
# #stopAdvertisingAndListening can be called multiple times in a row
ok 1152 should not be in advertising state
ok 1153 should still not be in advertising state
# teardown
ok 1154 should not be in started state
# setup
ok 1155 should be in started state
# functions are run from a queue in the right order
2016-11-03 12:06:41 - DEBUG thaliWifiInfrastructure: 'listening 50069'
ok 1156 call order must match
# teardown
ok 1157 should not be in started state
# setup
ok 1158 should be in started state
# does not get peer changes from self
2016-11-03 12:06:41 - DEBUG thaliWifiInfrastructure: 'listening 50070'
ok 1159 USN must have changed again
# teardown
ok 1160 should not be in started state
# setup
ok 1161 should be in started state
# network changes are ignored while stopping
2016-11-03 12:06:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-03 12:06:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
ok 1162 should not be called
# teardown
ok 1163 should not be in started state
# setup
ok 1164 should be in started state
# #startListeningForAdvertisements returns error if wifi is off and fires event when on
2016-11-03 12:06:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
ok 1165 wifi should be off
ok 1166 specific error expected
2016-11-03 12:06:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
ok 1167 discoveryActive should be true
# teardown
ok 1168 should not be in started state
# setup
ok 1169 should be in started state
# #startUpdateAdvertisingAndListening returns error if wifi is off and fires event when on
2016-11-03 12:06:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
ok 1170 wifi should be off
ok 1171 specific error expected
2016-11-03 12:06:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-03 12:06:43 - DEBUG thaliWifiInfrastructure: 'listening 50071'
ok 1172 advertisingActive should be true
# teardown
ok 1173 should not be in started state
# setup
ok 1174 should be in started state
# when wifi is enabled discovery is activated and peers become available
2016-11-03 12:06:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
ok 1175 wifi should be off
ok 1176 specific error expected
2016-11-03 12:06:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
ok 1177 peer identifier should match
ok 1178 host address should match
ok 1179 port should match
# teardown
ok 1180 should not be in started state
2016-11-03 12:06:43 - DEBUG SimpleThaliTape: 'all unit tests succeeded, platformName: 'desktop''
2016-11-03 12:06:43 - DEBUG SimpleThaliTape: 'skipped tests: '["does not emit duplicate discoveryAdvertisingStateUpdate","wifi peer is marked unavailable if announcements stop","network changes emitted correctly","calls correct starts when network changes"]''
2016-11-03 12:06:43 - DEBUG SimpleThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'

1..1180
# tests 1180
# pass  918
# fail  262

-e [0;31mcompilation aborted
 [0m
build aborted
 [0m

npm WARN thali-test-server@0.0.1 No repository field.
npm WARN thali-test-server@0.0.1 No license field.
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/forever-agent
npm http request GET http://192.168.1.100:4873/javascript-state-machine
npm http request GET http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/js-extend
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/bluebird
npm http 200 http://192.168.1.100:4873/forever-agent
npm http 304 http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/body-parser
npm http 200 http://192.168.1.100:4873/javascript-state-machine
npm http 200 http://192.168.1.100:4873/ip
npm http 200 http://192.168.1.100:4873/long
npm http 200 http://192.168.1.100:4873/lie
npm http 200 http://192.168.1.100:4873/uuid
npm http 200 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/js-extend
npm http 304 http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/qs
npm http 200 http://192.168.1.100:4873/bytes
npm http 200 http://192.168.1.100:4873/iconv-lite
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
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/send
npm http 304 http://192.168.1.100:4873/serve-static
npm http 304 http://192.168.1.100:4873/vary
npm http 304 http://192.168.1.100:4873/utils-merge
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
npm http 200 http://192.168.1.100:4873/es3ify
npm http 200 http://192.168.1.100:4873/inline-process-browser
npm http 200 http://192.168.1.100:4873/unreachable-branch-transform
npm http 200 http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/through
npm http 304 http://192.168.1.100:4873/esprima
npm http 200 http://192.168.1.100:4873/through
npm http 200 http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/base62
npm http 200 http://192.168.1.100:4873/esprima-fb
npm http 200 http://192.168.1.100:4873/commoner
npm http 200 http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http 200 http://192.168.1.100:4873/commander
npm http 200 http://192.168.1.100:4873/private
npm http 200 http://192.168.1.100:4873/detective
npm http 200 http://192.168.1.100:4873/mkdirp
npm http 200 http://192.168.1.100:4873/q
npm http 200 http://192.168.1.100:4873/recast
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http 200 http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/defined
npm http request GET http://192.168.1.100:4873/acorn
npm http 200 http://192.168.1.100:4873/defined
npm http 200 http://192.168.1.100:4873/acorn
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/inflight
npm http 304 http://192.168.1.100:4873/minimatch
npm http 304 http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/path-is-absolute
npm http request GET http://192.168.1.100:4873/wrappy
npm http 304 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 304 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/minimist
npm http 200 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/ast-types
npm http 200 http://192.168.1.100:4873/ast-types
npm http request GET http://192.168.1.100:4873/amdefine
npm http 200 http://192.168.1.100:4873/amdefine
npm http request GET http://192.168.1.100:4873/falafel
npm http request GET http://192.168.1.100:4873/through2
npm http 200 http://192.168.1.100:4873/through2
npm http 200 http://192.168.1.100:4873/falafel
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/isarray
npm http 200 http://192.168.1.100:4873/foreach
npm http 200 http://192.168.1.100:4873/object-keys
npm http request GET http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 200 http://192.168.1.100:4873/xtend
npm http 200 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/core-util-is
npm http request GET http://192.168.1.100:4873/string_decoder
npm http 200 http://192.168.1.100:4873/core-util-is
npm http 200 http://192.168.1.100:4873/string_decoder
npm http request GET http://192.168.1.100:4873/esmangle-evaluator
npm http 200 http://192.168.1.100:4873/esmangle-evaluator
npm http request GET http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/duplexify
npm http 200 http://192.168.1.100:4873/duplexify
npm http 200 http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/stream-shift
npm http 200 http://192.168.1.100:4873/end-of-stream
npm http 200 http://192.168.1.100:4873/stream-shift
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 200 http://192.168.1.100:4873/buffer-shims
npm http 200 http://192.168.1.100:4873/util-deprecate
npm http 200 http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 200 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/http-signature
npm http 200 http://192.168.1.100:4873/tunnel-agent
npm http 200 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/form-data
npm http 200 http://192.168.1.100:4873/caseless
npm http 200 http://192.168.1.100:4873/json-stringify-safe
npm http 200 http://192.168.1.100:4873/aws-sign2
npm http 200 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/bl
npm http 200 http://192.168.1.100:4873/oauth-sign
npm http 200 http://192.168.1.100:4873/stringstream
npm http 200 http://192.168.1.100:4873/har-validator
npm http 200 http://192.168.1.100:4873/combined-stream
npm http 200 http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 200 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/lodash
npm http 200 http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http 200 http://192.168.1.100:4873/chalk
npm http 200 http://192.168.1.100:4873/is-my-json-valid
npm http 200 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 200 http://192.168.1.100:4873/ansi-styles
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 200 http://192.168.1.100:4873/strip-ansi
npm http 200 http://192.168.1.100:4873/supports-color
npm http 200 http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 200 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 200 http://192.168.1.100:4873/jsonpointer
npm http 200 http://192.168.1.100:4873/generate-object-property
npm http 200 http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/is-property
npm http 200 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/boom
npm http 200 http://192.168.1.100:4873/cryptiles
npm http 200 http://192.168.1.100:4873/sntp
npm http 200 http://192.168.1.100:4873/boom
npm http 200 http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/ctype
npm http 200 http://192.168.1.100:4873/asn1
npm http 200 http://192.168.1.100:4873/ctype
npm http 200 http://192.168.1.100:4873/assert-plus
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
npm http 304 http://192.168.1.100:4873/pkginfo
npm http 304 http://192.168.1.100:4873/cycle
npm http 304 http://192.168.1.100:4873/eyes
npm http 304 http://192.168.1.100:4873/stack-trace
npm http request GET http://192.168.1.100:4873/jsdoc
npm http 200 http://192.168.1.100:4873/jsdoc
npm http request GET http://192.168.1.100:4873/js2xmlparser
npm http request GET http://192.168.1.100:4873/marked
npm http request GET http://192.168.1.100:4873/requizzle
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/catharsis
npm http request GET http://192.168.1.100:4873/underscore
npm http request GET http://192.168.1.100:4873/wrench
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 200 http://192.168.1.100:4873/js2xmlparser
npm http 304 http://192.168.1.100:4873/strip-json-comments
npm http 200 http://192.168.1.100:4873/marked
npm http 200 http://192.168.1.100:4873/underscore
npm http 200 http://192.168.1.100:4873/wrench
npm WARN deprecated wrench@1.5.9: wrench.js is deprecated! You should check out fs-extra (https://github.com/jprichardson/node-fs-extra) for any operations you were using wrench for. Thanks for all the usage over the years.
npm http 200 http://192.168.1.100:4873/catharsis
npm http 200 http://192.168.1.100:4873/requizzle
npm http fetch 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http request GET http://192.168.1.100:4873/underscore-contrib
npm http 200 http://192.168.1.100:4873/underscore-contrib
npm WARN prefer global marked@0.3.6 should be installed with -g
npm WARN install@0.0.1 No repository field.
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/bn.js
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/forever-agent
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/express-pouchdb
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/leveldown-mobile
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/pouchdb-size
npm http request GET http://192.168.1.100:4873/pouchdb
npm http request GET http://192.168.1.100:4873/proxyquire
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/request-promise
npm http request GET http://192.168.1.100:4873/supertest
npm http request GET http://192.168.1.100:4873/sinon
npm http request GET http://192.168.1.100:4873/nock
npm http request GET http://192.168.1.100:4873/supertest-as-promised
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/tmp
npm http request GET http://192.168.1.100:4873/tape-catch
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/tape
npm http request GET http://192.168.1.100:4873/uuid-validate
npm http request GET http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/forever-agent
npm http 200 http://192.168.1.100:4873/bn.js
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/randomstring
npm http 304 http://192.168.1.100:4873/js-extend
npm http 200 http://192.168.1.100:4873/express-pouchdb
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/multiplex
npm http 304 http://192.168.1.100:4873/socket.io-client
npm http 304 http://192.168.1.100:4873/pouchdb-size
npm http 200 http://192.168.1.100:4873/pouchdb
npm http 200 http://192.168.1.100:4873/proxyquire
npm http 200 http://192.168.1.100:4873/request-promise
npm http 200 http://192.168.1.100:4873/supertest
npm http 304 http://192.168.1.100:4873/leveldown-mobile
npm http 200 http://192.168.1.100:4873/supertest-as-promised
npm http 200 http://192.168.1.100:4873/sinon
npm http 304 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/tape-catch
npm http 200 http://192.168.1.100:4873/uuid
npm http 200 http://192.168.1.100:4873/tmp
npm http 304 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/tape
npm http 304 http://192.168.1.100:4873/uuid-validate
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
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/bytes
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/type-is
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
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/parseurl
npm http 200 http://192.168.1.100:4873/fresh
npm http 200 http://192.168.1.100:4873/merge-descriptors
npm http 200 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/send
npm http 304 http://192.168.1.100:4873/serve-static
npm http 304 http://192.168.1.100:4873/vary
npm http 200 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/utils-merge
npm http request GET http://192.168.1.100:4873/negotiator
npm http 304 http://192.168.1.100:4873/negotiator
npm http request GET http://192.168.1.100:4873/forwarded
npm http request GET http://192.168.1.100:4873/ipaddr.js
npm http 304 http://192.168.1.100:4873/forwarded
npm http 200 http://192.168.1.100:4873/ipaddr.js
npm http request GET http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/mime
npm http 304 http://192.168.1.100:4873/mime
npm http 304 http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/basic-auth
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/pouchdb-all-dbs
npm http request GET http://192.168.1.100:4873/multiparty
npm http request GET http://192.168.1.100:4873/header-case-normalizer
npm http request GET http://192.168.1.100:4873/cookie-parser
npm http request GET http://192.168.1.100:4873/compression
npm http request GET http://192.168.1.100:4873/pouchdb-auth
npm http request GET http://192.168.1.100:4873/pouchdb-list
npm http request GET http://192.168.1.100:4873/pouchdb-find
npm http request GET http://192.168.1.100:4873/pouchdb-replicator
npm http request GET http://192.168.1.100:4873/pouchdb-security
npm http request GET http://192.168.1.100:4873/pouchdb-show
npm http request GET http://192.168.1.100:4873/pouchdb-rewrite
npm http request GET http://192.168.1.100:4873/pouchdb-update
npm http request GET http://192.168.1.100:4873/pouchdb-validation
npm http request GET http://192.168.1.100:4873/pouchdb-vhost
npm http request GET http://192.168.1.100:4873/pouchdb-wrappers
npm http 304 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/multiparty
npm http 200 http://192.168.1.100:4873/basic-auth
npm http 200 http://192.168.1.100:4873/cookie-parser
npm http 200 http://192.168.1.100:4873/compression
npm http 200 http://192.168.1.100:4873/pouchdb-find
npm http 304 http://192.168.1.100:4873/pouchdb-auth
npm http 304 http://192.168.1.100:4873/pouchdb-list
npm http 304 http://192.168.1.100:4873/pouchdb-all-dbs
npm http 200 http://192.168.1.100:4873/header-case-normalizer
npm http 304 http://192.168.1.100:4873/pouchdb-rewrite
npm http 304 http://192.168.1.100:4873/pouchdb-update
npm http 304 http://192.168.1.100:4873/pouchdb-security
npm http 304 http://192.168.1.100:4873/pouchdb-validation
npm http 304 http://192.168.1.100:4873/pouchdb-replicator
npm http 304 http://192.168.1.100:4873/pouchdb-show
npm http 304 http://192.168.1.100:4873/pouchdb-vhost
npm http 304 http://192.168.1.100:4873/pouchdb-wrappers
npm http request GET http://192.168.1.100:4873/setprototypeof
npm http 200 http://192.168.1.100:4873/setprototypeof
npm http request GET http://192.168.1.100:4873/on-headers
npm http request GET http://192.168.1.100:4873/compressible
npm http 200 http://192.168.1.100:4873/on-headers
npm http 200 http://192.168.1.100:4873/compressible
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/stream-counter
npm http 200 http://192.168.1.100:4873/stream-counter
npm http 304 http://192.168.1.100:4873/readable-stream
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
npm http 304 http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/promise-nodify
npm http request GET http://192.168.1.100:4873/pouchdb-req-http-query
npm http request GET http://192.168.1.100:4873/pouchdb-system-db
npm http request GET http://192.168.1.100:4873/crypto-lite
npm http request GET http://192.168.1.100:4873/pouchdb-plugin-error
npm http request GET http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http request GET http://192.168.1.100:4873/couchdb-calculate-session-id
npm http request GET http://192.168.1.100:4873/base64url
npm http request GET http://192.168.1.100:4873/secure-random
npm http 304 http://192.168.1.100:4873/pouchdb-req-http-query
npm http 304 http://192.168.1.100:4873/pouchdb-plugin-error
npm http 304 http://192.168.1.100:4873/pouchdb-system-db
npm http 304 http://192.168.1.100:4873/crypto-lite
npm http 304 http://192.168.1.100:4873/promise-nodify
npm http 200 http://192.168.1.100:4873/base64url
npm http 304 http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http 304 http://192.168.1.100:4873/couchdb-calculate-session-id
npm http 200 http://192.168.1.100:4873/secure-random
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
npm http 200 http://192.168.1.100:4873/get-stdin
npm http 200 http://192.168.1.100:4873/repeating
npm http request GET http://192.168.1.100:4873/is-finite
npm http 200 http://192.168.1.100:4873/is-finite
npm http request GET http://192.168.1.100:4873/number-is-nan
npm http 200 http://192.168.1.100:4873/number-is-nan
npm http request GET http://192.168.1.100:4873/aproba
npm http 200 http://192.168.1.100:4873/aproba
npm http request GET http://192.168.1.100:4873/memdown
npm http request GET http://192.168.1.100:4873/fruitdown
npm http request GET http://192.168.1.100:4873/pouchdb-collate
npm http request GET http://192.168.1.100:4873/localstorage-down
npm http request GET http://192.168.1.100:4873/level-write-stream
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/es6-promise-pool
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/scope-eval
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/vuvuzela
npm http request GET http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/localstorage-down
npm http 200 http://192.168.1.100:4873/pouchdb-collate
npm http 200 http://192.168.1.100:4873/fruitdown
npm http 200 http://192.168.1.100:4873/level-write-stream
npm http 304 http://192.168.1.100:4873/double-ended-queue
npm http 200 http://192.168.1.100:4873/memdown
npm http 200 http://192.168.1.100:4873/levelup
npm http 200 http://192.168.1.100:4873/scope-eval
npm http 304 http://192.168.1.100:4873/through2
npm http 304 http://192.168.1.100:4873/js-extend
npm http 200 http://192.168.1.100:4873/es6-promise-pool
npm http 200 http://192.168.1.100:4873/pouchdb-collections
npm http 200 http://192.168.1.100:4873/sublevel-pouchdb
npm http 304 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/vuvuzela
npm http 200 http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/d64
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http 200 http://192.168.1.100:4873/abstract-leveldown
npm http 200 http://192.168.1.100:4873/d64
npm http request GET http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/end-stream
npm http 200 http://192.168.1.100:4873/end-stream
npm http request GET http://192.168.1.100:4873/write-stream
npm http 200 http://192.168.1.100:4873/write-stream
npm http request GET http://192.168.1.100:4873/deferred-leveldown
npm http request GET http://192.168.1.100:4873/level-errors
npm http request GET http://192.168.1.100:4873/level-codec
npm http request GET http://192.168.1.100:4873/level-iterator-stream
npm http request GET http://192.168.1.100:4873/prr
npm http request GET http://192.168.1.100:4873/semver
npm http 304 http://192.168.1.100:4873/prr
npm http 200 http://192.168.1.100:4873/level-iterator-stream
npm http 200 http://192.168.1.100:4873/level-errors
npm http 200 http://192.168.1.100:4873/level-codec
npm http 304 http://192.168.1.100:4873/semver
npm http 200 http://192.168.1.100:4873/deferred-leveldown
npm http request GET http://192.168.1.100:4873/errno
npm http 200 http://192.168.1.100:4873/errno
npm http request GET http://192.168.1.100:4873/humble-localstorage
npm http 200 http://192.168.1.100:4873/humble-localstorage
npm http request GET http://192.168.1.100:4873/has-localstorage
npm http request GET http://192.168.1.100:4873/localstorage-memory
npm http 200 http://192.168.1.100:4873/has-localstorage
npm http 200 http://192.168.1.100:4873/localstorage-memory
npm http request GET http://192.168.1.100:4873/ltgt
npm http request GET http://192.168.1.100:4873/functional-red-black-tree
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
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/is-typedarray
npm http request GET http://192.168.1.100:4873/aws4
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 200 http://192.168.1.100:4873/is-typedarray
npm WARN deprecated tough-cookie@2.2.2: ReDoS vulnerability parsing Set-Cookie https://nodesecurity.io/advisories/130
npm http 200 http://192.168.1.100:4873/aws4
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/readable-stream
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
npm http 200 http://192.168.1.100:4873/pinkie-promise
npm http 200 http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/ansi-styles
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/pinkie
npm http 200 http://192.168.1.100:4873/pinkie
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
npm http 200 http://192.168.1.100:4873/sshpk
npm http request GET http://192.168.1.100:4873/json-schema
npm http request GET http://192.168.1.100:4873/extsprintf
npm http request GET http://192.168.1.100:4873/verror
npm http 200 http://192.168.1.100:4873/json-schema
npm http 200 http://192.168.1.100:4873/extsprintf
npm http 200 http://192.168.1.100:4873/verror
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/getpass
npm http request GET http://192.168.1.100:4873/dashdash
npm http 304 http://192.168.1.100:4873/asn1
npm http 200 http://192.168.1.100:4873/getpass
npm http 200 http://192.168.1.100:4873/dashdash
npm http request GET http://192.168.1.100:4873/pull-stream
npm http 200 http://192.168.1.100:4873/pull-stream
npm http request GET http://192.168.1.100:4873/pull-core
npm http 200 http://192.168.1.100:4873/pull-core
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/xmlhttprequest-cookie
npm http 304 http://192.168.1.100:4873/xmlhttprequest-cookie
npm http request GET http://192.168.1.100:4873/xmlhttprequest
npm http 200 http://192.168.1.100:4873/xmlhttprequest
npm http request GET http://192.168.1.100:4873/pouchdb-changeslike-wrapper
npm http 304 http://192.168.1.100:4873/pouchdb-changeslike-wrapper
npm http request GET http://192.168.1.100:4873/random-uuid-v4
npm http request GET http://192.168.1.100:4873/couchdb-objects
npm http request GET http://192.168.1.100:4873/couchdb-eval
npm http 304 http://192.168.1.100:4873/random-uuid-v4
npm http 304 http://192.168.1.100:4873/couchdb-eval
npm http 304 http://192.168.1.100:4873/couchdb-objects
npm http request GET http://192.168.1.100:4873/is-empty
npm http 304 http://192.168.1.100:4873/is-empty
npm http request GET http://192.168.1.100:4873/is-array
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/pouchdb-extend
npm http request GET http://192.168.1.100:4873/pouchdb-upsert
npm http 304 http://192.168.1.100:4873/spark-md5
npm http 304 http://192.168.1.100:4873/pouchdb-upsert
npm http 200 http://192.168.1.100:4873/pouchdb-extend
npm http 200 http://192.168.1.100:4873/is-array
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 200 http://192.168.1.100:4873/unreachable-branch-transform
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
npm http 200 http://192.168.1.100:4873/get-folder-size
npm http request GET http://192.168.1.100:4873/minimist
npm http 304 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/fast-future
npm http request GET http://192.168.1.100:4873/bindings
npm http 304 http://192.168.1.100:4873/abstract-leveldown
npm http 304 http://192.168.1.100:4873/bindings
npm http 200 http://192.168.1.100:4873/fast-future
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
npm http request GET http://192.168.1.100:4873/deep-equal
npm http request GET http://192.168.1.100:4873/propagate
npm http request GET http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/chai
npm http 304 http://192.168.1.100:4873/lodash
npm WARN deprecated lodash@2.4.1: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
npm http 200 http://192.168.1.100:4873/deep-equal
npm http 304 http://192.168.1.100:4873/debug
npm http 200 http://192.168.1.100:4873/propagate
npm http 200 http://192.168.1.100:4873/chai
npm http request GET http://192.168.1.100:4873/type-detect
npm http request GET http://192.168.1.100:4873/assertion-error
npm http request GET http://192.168.1.100:4873/deep-eql
npm http 200 http://192.168.1.100:4873/assertion-error
npm http 200 http://192.168.1.100:4873/deep-eql
npm http 200 http://192.168.1.100:4873/type-detect
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/ip
npm http 304 http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/fill-keys
npm http request GET http://192.168.1.100:4873/module-not-found-error
npm http 200 http://192.168.1.100:4873/fill-keys
npm http 200 http://192.168.1.100:4873/module-not-found-error
npm http request GET http://192.168.1.100:4873/is-object
npm http 200 http://192.168.1.100:4873/is-object
npm http request GET http://192.168.1.100:4873/array-uniq
npm http 304 http://192.168.1.100:4873/array-uniq
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/assert-plus
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 304 http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/jsonschema
npm http 304 http://192.168.1.100:4873/jsonschema
npm http request GET http://192.168.1.100:4873/util
npm http request GET http://192.168.1.100:4873/formatio
npm http request GET http://192.168.1.100:4873/lolex
npm http request GET http://192.168.1.100:4873/samsam
npm http 200 http://192.168.1.100:4873/util
npm http 200 http://192.168.1.100:4873/lolex
npm http 200 http://192.168.1.100:4873/samsam
npm http 200 http://192.168.1.100:4873/formatio
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
npm http 304 http://192.168.1.100:4873/object-component
npm http 304 http://192.168.1.100:4873/socket.io-parser
npm http 304 http://192.168.1.100:4873/engine.io-client
npm http 304 http://192.168.1.100:4873/component-emitter
npm http 304 http://192.168.1.100:4873/parseuri
npm http 304 http://192.168.1.100:4873/indexof
npm http 304 http://192.168.1.100:4873/to-array
npm http 304 http://192.168.1.100:4873/has-binary
npm http 304 http://192.168.1.100:4873/backo2
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/xmlhttprequest-ssl
npm http request GET http://192.168.1.100:4873/ws
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/parseqs
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/yeast
npm http 304 http://192.168.1.100:4873/xmlhttprequest-ssl
npm http 304 http://192.168.1.100:4873/has-cors
npm http 304 http://192.168.1.100:4873/engine.io-parser
npm http 304 http://192.168.1.100:4873/ws
npm http 304 http://192.168.1.100:4873/parsejson
npm http 304 http://192.168.1.100:4873/parseqs
npm http 304 http://192.168.1.100:4873/component-inherit
npm http 304 http://192.168.1.100:4873/yeast
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/utf8
npm http 200 http://192.168.1.100:4873/after
npm http 200 http://192.168.1.100:4873/arraybuffer.slice
npm http 304 http://192.168.1.100:4873/base64-arraybuffer
npm http 304 http://192.168.1.100:4873/blob
npm http 304 http://192.168.1.100:4873/utf8
npm http request GET http://192.168.1.100:4873/better-assert
npm http 200 http://192.168.1.100:4873/better-assert
npm http request GET http://192.168.1.100:4873/callsite
npm http 200 http://192.168.1.100:4873/callsite
npm http request GET http://192.168.1.100:4873/options
npm http request GET http://192.168.1.100:4873/ultron
npm http 304 http://192.168.1.100:4873/ultron
npm http 304 http://192.168.1.100:4873/options
npm http request GET http://192.168.1.100:4873/json3
npm http request GET http://192.168.1.100:4873/benchmark
npm http 304 http://192.168.1.100:4873/json3
npm http 200 http://192.168.1.100:4873/benchmark
npm http request GET http://192.168.1.100:4873/superagent
npm http 200 http://192.168.1.100:4873/superagent
npm http request GET http://192.168.1.100:4873/reduce-component
npm http request GET http://192.168.1.100:4873/formidable
npm http request GET http://192.168.1.100:4873/cookiejar
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/methods
npm http 200 http://192.168.1.100:4873/formidable
npm http 200 http://192.168.1.100:4873/reduce-component
npm http 304 http://192.168.1.100:4873/form-data
npm http 200 http://192.168.1.100:4873/cookiejar
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
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/defined
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/resumer
npm http request GET http://192.168.1.100:4873/object-inspect
npm http 304 http://192.168.1.100:4873/defined
npm http 304 http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/resumer
npm http 200 http://192.168.1.100:4873/object-inspect
npm http request GET http://192.168.1.100:4873/os-tmpdir
npm http 200 http://192.168.1.100:4873/os-tmpdir
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
npm ERR! Test failed.  See above for more details.

```

Error: Command failed: npm WARN thali-test-server@0.0.1 No repository field.
npm WARN thali-test-server@0.0.1 No license field.
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/forever-agent
npm http request GET http://192.168.1.100:4873/javascript-state-machine
npm http request GET http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/js-extend
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/bluebird
npm http 200 http://192.168.1.100:4873/forever-agent
npm http 304 http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/body-parser
npm http 200 http://192.168.1.100:4873/javascript-state-machine
npm http 200 http://192.168.1.100:4873/ip
npm http 200 http://192.168.1.100:4873/long
npm http 200 http://192.168.1.100:4873/lie
npm http 200 http://192.168.1.100:4873/uuid
npm http 200 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/js-extend
npm http 304 http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/qs
npm http 200 http://192.168.1.100:4873/bytes
npm http 200 http://192.168.1.100:4873/iconv-lite
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
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/send
npm http 304 http://192.168.1.100:4873/serve-static
npm http 304 http://192.168.1.100:4873/vary
npm http 304 http://192.168.1.100:4873/utils-merge
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
npm http 200 http://192.168.1.100:4873/es3ify
npm http 200 http://192.168.1.100:4873/inline-process-browser
npm http 200 http://192.168.1.100:4873/unreachable-branch-transform
npm http 200 http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/through
npm http 304 http://192.168.1.100:4873/esprima
npm http 200 http://192.168.1.100:4873/through
npm http 200 http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/base62
npm http 200 http://192.168.1.100:4873/esprima-fb
npm http 200 http://192.168.1.100:4873/commoner
npm http 200 http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http 200 http://192.168.1.100:4873/commander
npm http 200 http://192.168.1.100:4873/private
npm http 200 http://192.168.1.100:4873/detective
npm http 200 http://192.168.1.100:4873/mkdirp
npm http 200 http://192.168.1.100:4873/q
npm http 200 http://192.168.1.100:4873/recast
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http 200 http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/defined
npm http request GET http://192.168.1.100:4873/acorn
npm http 200 http://192.168.1.100:4873/defined
npm http 200 http://192.168.1.100:4873/acorn
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/inflight
npm http 304 http://192.168.1.100:4873/minimatch
npm http 304 http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/path-is-absolute
npm http request GET http://192.168.1.100:4873/wrappy
npm http 304 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 304 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/minimist
npm http 200 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/ast-types
npm http 200 http://192.168.1.100:4873/ast-types
npm http request GET http://192.168.1.100:4873/amdefine
npm http 200 http://192.168.1.100:4873/amdefine
npm http request GET http://192.168.1.100:4873/falafel
npm http request GET http://192.168.1.100:4873/through2
npm http 200 http://192.168.1.100:4873/through2
npm http 200 http://192.168.1.100:4873/falafel
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/isarray
npm http 200 http://192.168.1.100:4873/foreach
npm http 200 http://192.168.1.100:4873/object-keys
npm http request GET http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 200 http://192.168.1.100:4873/xtend
npm http 200 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/core-util-is
npm http request GET http://192.168.1.100:4873/string_decoder
npm http 200 http://192.168.1.100:4873/core-util-is
npm http 200 http://192.168.1.100:4873/string_decoder
npm http request GET http://192.168.1.100:4873/esmangle-evaluator
npm http 200 http://192.168.1.100:4873/esmangle-evaluator
npm http request GET http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/duplexify
npm http 200 http://192.168.1.100:4873/duplexify
npm http 200 http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/stream-shift
npm http 200 http://192.168.1.100:4873/end-of-stream
npm http 200 http://192.168.1.100:4873/stream-shift
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 200 http://192.168.1.100:4873/buffer-shims
npm http 200 http://192.168.1.100:4873/util-deprecate
npm http 200 http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 200 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/http-signature
npm http 200 http://192.168.1.100:4873/tunnel-agent
npm http 200 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/form-data
npm http 200 http://192.168.1.100:4873/caseless
npm http 200 http://192.168.1.100:4873/json-stringify-safe
npm http 200 http://192.168.1.100:4873/aws-sign2
npm http 200 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/bl
npm http 200 http://192.168.1.100:4873/oauth-sign
npm http 200 http://192.168.1.100:4873/stringstream
npm http 200 http://192.168.1.100:4873/har-validator
npm http 200 http://192.168.1.100:4873/combined-stream
npm http 200 http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 200 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/lodash
npm http 200 http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http 200 http://192.168.1.100:4873/chalk
npm http 200 http://192.168.1.100:4873/is-my-json-valid
npm http 200 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 200 http://192.168.1.100:4873/ansi-styles
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 200 http://192.168.1.100:4873/strip-ansi
npm http 200 http://192.168.1.100:4873/supports-color
npm http 200 http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 200 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 200 http://192.168.1.100:4873/jsonpointer
npm http 200 http://192.168.1.100:4873/generate-object-property
npm http 200 http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/is-property
npm http 200 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/boom
npm http 200 http://192.168.1.100:4873/cryptiles
npm http 200 http://192.168.1.100:4873/sntp
npm http 200 http://192.168.1.100:4873/boom
npm http 200 http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/ctype
npm http 200 http://192.168.1.100:4873/asn1
npm http 200 http://192.168.1.100:4873/ctype
npm http 200 http://192.168.1.100:4873/assert-plus
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
npm http 304 http://192.168.1.100:4873/pkginfo
npm http 304 http://192.168.1.100:4873/cycle
npm http 304 http://192.168.1.100:4873/eyes
npm http 304 http://192.168.1.100:4873/stack-trace
npm http request GET http://192.168.1.100:4873/jsdoc
npm http 200 http://192.168.1.100:4873/jsdoc
npm http request GET http://192.168.1.100:4873/js2xmlparser
npm http request GET http://192.168.1.100:4873/marked
npm http request GET http://192.168.1.100:4873/requizzle
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/catharsis
npm http request GET http://192.168.1.100:4873/underscore
npm http request GET http://192.168.1.100:4873/wrench
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 200 http://192.168.1.100:4873/js2xmlparser
npm http 304 http://192.168.1.100:4873/strip-json-comments
npm http 200 http://192.168.1.100:4873/marked
npm http 200 http://192.168.1.100:4873/underscore
npm http 200 http://192.168.1.100:4873/wrench
npm WARN deprecated wrench@1.5.9: wrench.js is deprecated! You should check out fs-extra (https://github.com/jprichardson/node-fs-extra) for any operations you were using wrench for. Thanks for all the usage over the years.
npm http 200 http://192.168.1.100:4873/catharsis
npm http 200 http://192.168.1.100:4873/requizzle
npm http fetch 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http request GET http://192.168.1.100:4873/underscore-contrib
npm http 200 http://192.168.1.100:4873/underscore-contrib
npm WARN prefer global marked@0.3.6 should be installed with -g
npm WARN install@0.0.1 No repository field.
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/bn.js
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/forever-agent
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/express-pouchdb
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/leveldown-mobile
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/pouchdb-size
npm http request GET http://192.168.1.100:4873/pouchdb
npm http request GET http://192.168.1.100:4873/proxyquire
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/request-promise
npm http request GET http://192.168.1.100:4873/supertest
npm http request GET http://192.168.1.100:4873/sinon
npm http request GET http://192.168.1.100:4873/nock
npm http request GET http://192.168.1.100:4873/supertest-as-promised
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/tmp
npm http request GET http://192.168.1.100:4873/tape-catch
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/tape
npm http request GET http://192.168.1.100:4873/uuid-validate
npm http request GET http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/forever-agent
npm http 200 http://192.168.1.100:4873/bn.js
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/randomstring
npm http 304 http://192.168.1.100:4873/js-extend
npm http 200 http://192.168.1.100:4873/express-pouchdb
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/multiplex
npm http 304 http://192.168.1.100:4873/socket.io-client
npm http 304 http://192.168.1.100:4873/pouchdb-size
npm http 200 http://192.168.1.100:4873/pouchdb
npm http 200 http://192.168.1.100:4873/proxyquire
npm http 200 http://192.168.1.100:4873/request-promise
npm http 200 http://192.168.1.100:4873/supertest
npm http 304 http://192.168.1.100:4873/leveldown-mobile
npm http 200 http://192.168.1.100:4873/supertest-as-promised
npm http 200 http://192.168.1.100:4873/sinon
npm http 304 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/tape-catch
npm http 200 http://192.168.1.100:4873/uuid
npm http 200 http://192.168.1.100:4873/tmp
npm http 304 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/tape
npm http 304 http://192.168.1.100:4873/uuid-validate
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
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/bytes
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/type-is
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
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/parseurl
npm http 200 http://192.168.1.100:4873/fresh
npm http 200 http://192.168.1.100:4873/merge-descriptors
npm http 200 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/send
npm http 304 http://192.168.1.100:4873/serve-static
npm http 304 http://192.168.1.100:4873/vary
npm http 200 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/utils-merge
npm http request GET http://192.168.1.100:4873/negotiator
npm http 304 http://192.168.1.100:4873/negotiator
npm http request GET http://192.168.1.100:4873/forwarded
npm http request GET http://192.168.1.100:4873/ipaddr.js
npm http 304 http://192.168.1.100:4873/forwarded
npm http 200 http://192.168.1.100:4873/ipaddr.js
npm http request GET http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/mime
npm http 304 http://192.168.1.100:4873/mime
npm http 304 http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/basic-auth
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/pouchdb-all-dbs
npm http request GET http://192.168.1.100:4873/multiparty
npm http request GET http://192.168.1.100:4873/header-case-normalizer
npm http request GET http://192.168.1.100:4873/cookie-parser
npm http request GET http://192.168.1.100:4873/compression
npm http request GET http://192.168.1.100:4873/pouchdb-auth
npm http request GET http://192.168.1.100:4873/pouchdb-list
npm http request GET http://192.168.1.100:4873/pouchdb-find
npm http request GET http://192.168.1.100:4873/pouchdb-replicator
npm http request GET http://192.168.1.100:4873/pouchdb-security
npm http request GET http://192.168.1.100:4873/pouchdb-show
npm http request GET http://192.168.1.100:4873/pouchdb-rewrite
npm http request GET http://192.168.1.100:4873/pouchdb-update
npm http request GET http://192.168.1.100:4873/pouchdb-validation
npm http request GET http://192.168.1.100:4873/pouchdb-vhost
npm http request GET http://192.168.1.100:4873/pouchdb-wrappers
npm http 304 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/multiparty
npm http 200 http://192.168.1.100:4873/basic-auth
npm http 200 http://192.168.1.100:4873/cookie-parser
npm http 200 http://192.168.1.100:4873/compression
npm http 200 http://192.168.1.100:4873/pouchdb-find
npm http 304 http://192.168.1.100:4873/pouchdb-auth
npm http 304 http://192.168.1.100:4873/pouchdb-list
npm http 304 http://192.168.1.100:4873/pouchdb-all-dbs
npm http 200 http://192.168.1.100:4873/header-case-normalizer
npm http 304 http://192.168.1.100:4873/pouchdb-rewrite
npm http 304 http://192.168.1.100:4873/pouchdb-update
npm http 304 http://192.168.1.100:4873/pouchdb-security
npm http 304 http://192.168.1.100:4873/pouchdb-validation
npm http 304 http://192.168.1.100:4873/pouchdb-replicator
npm http 304 http://192.168.1.100:4873/pouchdb-show
npm http 304 http://192.168.1.100:4873/pouchdb-vhost
npm http 304 http://192.168.1.100:4873/pouchdb-wrappers
npm http request GET http://192.168.1.100:4873/setprototypeof
npm http 200 http://192.168.1.100:4873/setprototypeof
npm http request GET http://192.168.1.100:4873/on-headers
npm http request GET http://192.168.1.100:4873/compressible
npm http 200 http://192.168.1.100:4873/on-headers
npm http 200 http://192.168.1.100:4873/compressible
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/stream-counter
npm http 200 http://192.168.1.100:4873/stream-counter
npm http 304 http://192.168.1.100:4873/readable-stream
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
npm http 304 http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/promise-nodify
npm http request GET http://192.168.1.100:4873/pouchdb-req-http-query
npm http request GET http://192.168.1.100:4873/pouchdb-system-db
npm http request GET http://192.168.1.100:4873/crypto-lite
npm http request GET http://192.168.1.100:4873/pouchdb-plugin-error
npm http request GET http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http request GET http://192.168.1.100:4873/couchdb-calculate-session-id
npm http request GET http://192.168.1.100:4873/base64url
npm http request GET http://192.168.1.100:4873/secure-random
npm http 304 http://192.168.1.100:4873/pouchdb-req-http-query
npm http 304 http://192.168.1.100:4873/pouchdb-plugin-error
npm http 304 http://192.168.1.100:4873/pouchdb-system-db
npm http 304 http://192.168.1.100:4873/crypto-lite
npm http 304 http://192.168.1.100:4873/promise-nodify
npm http 200 http://192.168.1.100:4873/base64url
npm http 304 http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http 304 http://192.168.1.100:4873/couchdb-calculate-session-id
npm http 200 http://192.168.1.100:4873/secure-random
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
npm http 200 http://192.168.1.100:4873/get-stdin
npm http 200 http://192.168.1.100:4873/repeating
npm http request GET http://192.168.1.100:4873/is-finite
npm http 200 http://192.168.1.100:4873/is-finite
npm http request GET http://192.168.1.100:4873/number-is-nan
npm http 200 http://192.168.1.100:4873/number-is-nan
npm http request GET http://192.168.1.100:4873/aproba
npm http 200 http://192.168.1.100:4873/aproba
npm http request GET http://192.168.1.100:4873/memdown
npm http request GET http://192.168.1.100:4873/fruitdown
npm http request GET http://192.168.1.100:4873/pouchdb-collate
npm http request GET http://192.168.1.100:4873/localstorage-down
npm http request GET http://192.168.1.100:4873/level-write-stream
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/es6-promise-pool
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/scope-eval
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/vuvuzela
npm http request GET http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/localstorage-down
npm http 200 http://192.168.1.100:4873/pouchdb-collate
npm http 200 http://192.168.1.100:4873/fruitdown
npm http 200 http://192.168.1.100:4873/level-write-stream
npm http 304 http://192.168.1.100:4873/double-ended-queue
npm http 200 http://192.168.1.100:4873/memdown
npm http 200 http://192.168.1.100:4873/levelup
npm http 200 http://192.168.1.100:4873/scope-eval
npm http 304 http://192.168.1.100:4873/through2
npm http 304 http://192.168.1.100:4873/js-extend
npm http 200 http://192.168.1.100:4873/es6-promise-pool
npm http 200 http://192.168.1.100:4873/pouchdb-collections
npm http 200 http://192.168.1.100:4873/sublevel-pouchdb
npm http 304 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/vuvuzela
npm http 200 http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/d64
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http 200 http://192.168.1.100:4873/abstract-leveldown
npm http 200 http://192.168.1.100:4873/d64
npm http request GET http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/end-stream
npm http 200 http://192.168.1.100:4873/end-stream
npm http request GET http://192.168.1.100:4873/write-stream
npm http 200 http://192.168.1.100:4873/write-stream
npm http request GET http://192.168.1.100:4873/deferred-leveldown
npm http request GET http://192.168.1.100:4873/level-errors
npm http request GET http://192.168.1.100:4873/level-codec
npm http request GET http://192.168.1.100:4873/level-iterator-stream
npm http request GET http://192.168.1.100:4873/prr
npm http request GET http://192.168.1.100:4873/semver
npm http 304 http://192.168.1.100:4873/prr
npm http 200 http://192.168.1.100:4873/level-iterator-stream
npm http 200 http://192.168.1.100:4873/level-errors
npm http 200 http://192.168.1.100:4873/level-codec
npm http 304 http://192.168.1.100:4873/semver
npm http 200 http://192.168.1.100:4873/deferred-leveldown
npm http request GET http://192.168.1.100:4873/errno
npm http 200 http://192.168.1.100:4873/errno
npm http request GET http://192.168.1.100:4873/humble-localstorage
npm http 200 http://192.168.1.100:4873/humble-localstorage
npm http request GET http://192.168.1.100:4873/has-localstorage
npm http request GET http://192.168.1.100:4873/localstorage-memory
npm http 200 http://192.168.1.100:4873/has-localstorage
npm http 200 http://192.168.1.100:4873/localstorage-memory
npm http request GET http://192.168.1.100:4873/ltgt
npm http request GET http://192.168.1.100:4873/functional-red-black-tree
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
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/is-typedarray
npm http request GET http://192.168.1.100:4873/aws4
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 200 http://192.168.1.100:4873/is-typedarray
npm WARN deprecated tough-cookie@2.2.2: ReDoS vulnerability parsing Set-Cookie https://nodesecurity.io/advisories/130
npm http 200 http://192.168.1.100:4873/aws4
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/readable-stream
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
npm http 200 http://192.168.1.100:4873/pinkie-promise
npm http 200 http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/ansi-styles
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/pinkie
npm http 200 http://192.168.1.100:4873/pinkie
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
npm http 200 http://192.168.1.100:4873/sshpk
npm http request GET http://192.168.1.100:4873/json-schema
npm http request GET http://192.168.1.100:4873/extsprintf
npm http request GET http://192.168.1.100:4873/verror
npm http 200 http://192.168.1.100:4873/json-schema
npm http 200 http://192.168.1.100:4873/extsprintf
npm http 200 http://192.168.1.100:4873/verror
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/getpass
npm http request GET http://192.168.1.100:4873/dashdash
npm http 304 http://192.168.1.100:4873/asn1
npm http 200 http://192.168.1.100:4873/getpass
npm http 200 http://192.168.1.100:4873/dashdash
npm http request GET http://192.168.1.100:4873/pull-stream
npm http 200 http://192.168.1.100:4873/pull-stream
npm http request GET http://192.168.1.100:4873/pull-core
npm http 200 http://192.168.1.100:4873/pull-core
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/xmlhttprequest-cookie
npm http 304 http://192.168.1.100:4873/xmlhttprequest-cookie
npm http request GET http://192.168.1.100:4873/xmlhttprequest
npm http 200 http://192.168.1.100:4873/xmlhttprequest
npm http request GET http://192.168.1.100:4873/pouchdb-changeslike-wrapper
npm http 304 http://192.168.1.100:4873/pouchdb-changeslike-wrapper
npm http request GET http://192.168.1.100:4873/random-uuid-v4
npm http request GET http://192.168.1.100:4873/couchdb-objects
npm http request GET http://192.168.1.100:4873/couchdb-eval
npm http 304 http://192.168.1.100:4873/random-uuid-v4
npm http 304 http://192.168.1.100:4873/couchdb-eval
npm http 304 http://192.168.1.100:4873/couchdb-objects
npm http request GET http://192.168.1.100:4873/is-empty
npm http 304 http://192.168.1.100:4873/is-empty
npm http request GET http://192.168.1.100:4873/is-array
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/pouchdb-extend
npm http request GET http://192.168.1.100:4873/pouchdb-upsert
npm http 304 http://192.168.1.100:4873/spark-md5
npm http 304 http://192.168.1.100:4873/pouchdb-upsert
npm http 200 http://192.168.1.100:4873/pouchdb-extend
npm http 200 http://192.168.1.100:4873/is-array
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 200 http://192.168.1.100:4873/unreachable-branch-transform
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
npm http 200 http://192.168.1.100:4873/get-folder-size
npm http request GET http://192.168.1.100:4873/minimist
npm http 304 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/fast-future
npm http request GET http://192.168.1.100:4873/bindings
npm http 304 http://192.168.1.100:4873/abstract-leveldown
npm http 304 http://192.168.1.100:4873/bindings
npm http 200 http://192.168.1.100:4873/fast-future
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
npm http request GET http://192.168.1.100:4873/deep-equal
npm http request GET http://192.168.1.100:4873/propagate
npm http request GET http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/chai
npm http 304 http://192.168.1.100:4873/lodash
npm WARN deprecated lodash@2.4.1: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
npm http 200 http://192.168.1.100:4873/deep-equal
npm http 304 http://192.168.1.100:4873/debug
npm http 200 http://192.168.1.100:4873/propagate
npm http 200 http://192.168.1.100:4873/chai
npm http request GET http://192.168.1.100:4873/type-detect
npm http request GET http://192.168.1.100:4873/assertion-error
npm http request GET http://192.168.1.100:4873/deep-eql
npm http 200 http://192.168.1.100:4873/assertion-error
npm http 200 http://192.168.1.100:4873/deep-eql
npm http 200 http://192.168.1.100:4873/type-detect
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/ip
npm http 304 http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/fill-keys
npm http request GET http://192.168.1.100:4873/module-not-found-error
npm http 200 http://192.168.1.100:4873/fill-keys
npm http 200 http://192.168.1.100:4873/module-not-found-error
npm http request GET http://192.168.1.100:4873/is-object
npm http 200 http://192.168.1.100:4873/is-object
npm http request GET http://192.168.1.100:4873/array-uniq
npm http 304 http://192.168.1.100:4873/array-uniq
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/assert-plus
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 304 http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/jsonschema
npm http 304 http://192.168.1.100:4873/jsonschema
npm http request GET http://192.168.1.100:4873/util
npm http request GET http://192.168.1.100:4873/formatio
npm http request GET http://192.168.1.100:4873/lolex
npm http request GET http://192.168.1.100:4873/samsam
npm http 200 http://192.168.1.100:4873/util
npm http 200 http://192.168.1.100:4873/lolex
npm http 200 http://192.168.1.100:4873/samsam
npm http 200 http://192.168.1.100:4873/formatio
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
npm http 304 http://192.168.1.100:4873/object-component
npm http 304 http://192.168.1.100:4873/socket.io-parser
npm http 304 http://192.168.1.100:4873/engine.io-client
npm http 304 http://192.168.1.100:4873/component-emitter
npm http 304 http://192.168.1.100:4873/parseuri
npm http 304 http://192.168.1.100:4873/indexof
npm http 304 http://192.168.1.100:4873/to-array
npm http 304 http://192.168.1.100:4873/has-binary
npm http 304 http://192.168.1.100:4873/backo2
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/xmlhttprequest-ssl
npm http request GET http://192.168.1.100:4873/ws
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/parseqs
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/yeast
npm http 304 http://192.168.1.100:4873/xmlhttprequest-ssl
npm http 304 http://192.168.1.100:4873/has-cors
npm http 304 http://192.168.1.100:4873/engine.io-parser
npm http 304 http://192.168.1.100:4873/ws
npm http 304 http://192.168.1.100:4873/parsejson
npm http 304 http://192.168.1.100:4873/parseqs
npm http 304 http://192.168.1.100:4873/component-inherit
npm http 304 http://192.168.1.100:4873/yeast
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/utf8
npm http 200 http://192.168.1.100:4873/after
npm http 200 http://192.168.1.100:4873/arraybuffer.slice
npm http 304 http://192.168.1.100:4873/base64-arraybuffer
npm http 304 http://192.168.1.100:4873/blob
npm http 304 http://192.168.1.100:4873/utf8
npm http request GET http://192.168.1.100:4873/better-assert
npm http 200 http://192.168.1.100:4873/better-assert
npm http request GET http://192.168.1.100:4873/callsite
npm http 200 http://192.168.1.100:4873/callsite
npm http request GET http://192.168.1.100:4873/options
npm http request GET http://192.168.1.100:4873/ultron
npm http 304 http://192.168.1.100:4873/ultron
npm http 304 http://192.168.1.100:4873/options
npm http request GET http://192.168.1.100:4873/json3
npm http request GET http://192.168.1.100:4873/benchmark
npm http 304 http://192.168.1.100:4873/json3
npm http 200 http://192.168.1.100:4873/benchmark
npm http request GET http://192.168.1.100:4873/superagent
npm http 200 http://192.168.1.100:4873/superagent
npm http request GET http://192.168.1.100:4873/reduce-component
npm http request GET http://192.168.1.100:4873/formidable
npm http request GET http://192.168.1.100:4873/cookiejar
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/methods
npm http 200 http://192.168.1.100:4873/formidable
npm http 200 http://192.168.1.100:4873/reduce-component
npm http 304 http://192.168.1.100:4873/form-data
npm http 200 http://192.168.1.100:4873/cookiejar
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
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/defined
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/resumer
npm http request GET http://192.168.1.100:4873/object-inspect
npm http 304 http://192.168.1.100:4873/defined
npm http 304 http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/resumer
npm http 200 http://192.168.1.100:4873/object-inspect
npm http request GET http://192.168.1.100:4873/os-tmpdir
npm http 200 http://192.168.1.100:4873/os-tmpdir
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
npm ERR! Test failed.  See above for more details.
