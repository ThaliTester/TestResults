#### Test (Fail) 93572167 Build Logs


```


```

```
Already up-to-date.

From https://github.com/thaliproject/Thali_CordovaPlugin
 * [new branch]      evabishchevich_1517 -> origin/evabishchevich_1517

```

```
Your branch is up-to-date with 'origin/master'.
Branch iOS_chapko_merge-master set up to track remote branch iOS_chapko_merge-master from origin.
Already up-to-date.

Already on 'master'
Switched to a new branch 'iOS_chapko_merge-master'
Note: checking out '30f5d57'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at 30f5d57... Updated jxcore-cordova plugin to 0.1.6 version

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
├── node-ssdp@2.6.5  (git+https://github.com/thaliproject/node-ssdp.git#caf1a75aa54fb47a9e51b72bf4c902c366536cbd)
│   A node.js SSDP client and server library.
│   git+ssh://git@github.com/diversario/node-ssdp.git
│   https://github.com/diversario/node-ssdp#readme
│   git+https://github.com/thaliproject/node-ssdp.git#caf1a75aa54fb47a9e51b72bf4c902c366536cbd
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
├─┬ child-process-promise@1.1.0 
│ └── q@1.4.1 
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
│ │ └─┬ async@2.1.2 
│ │   └── lodash@4.17.0 
│ ├─┬ har-validator@2.0.6 
│ │ ├─┬ chalk@1.1.3 
│ │ │ ├── ansi-styles@2.2.1 
│ │ │ ├── escape-string-regexp@1.0.5 
│ │ │ ├─┬ has-ansi@2.0.0 
│ │ │ │ └── ansi-regex@2.0.0 
│ │ │ ├── strip-ansi@3.0.1 
│ │ │ └── supports-color@2.0.0 
│ │ ├─┬ commander@2.9.0 
│ │ │ └── graceful-readlink@1.0.1 
│ │ ├─┬ is-my-json-valid@2.15.0 
│ │ │ ├── generate-function@2.0.0 
│ │ │ ├─┬ generate-object-property@1.2.0 
│ │ │ │ └── is-property@1.0.2 
│ │ │ ├── jsonpointer@4.0.0 
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
│ │ └─┬ sshpk@1.10.1 
│ │   ├── asn1@0.2.3 
│ │   ├── assert-plus@1.0.0 
│ │   ├─┬ dashdash@1.14.0 
│ │   │ └── assert-plus@1.0.0 
│ │   └─┬ getpass@0.1.6 
│ │     └── assert-plus@1.0.0 
│ ├── is-typedarray@1.0.0 
│ ├── isstream@0.1.2 
│ ├── json-stringify-safe@5.0.1 
│ ├─┬ mime-types@2.1.12 
│ │ └── mime-db@1.24.0 
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
      └── xmldom@0.1.22 

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
2016-11-14 14:11:35 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
2016-11-14 14:11:35 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreateNativeListener.js'
2016-11-14 14:11:36 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js'
2016-11-14 14:11:36 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js'
2016-11-14 14:11:36 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
2016-11-14 14:11:36 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
2016-11-14 14:11:36 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testNativeMethod.js'
2016-11-14 14:11:36 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
2016-11-14 14:11:36 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBGenerator.js'
2016-11-14 14:11:36 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPromiseQueue.js'
2016-11-14 14:11:36 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testTests.js'
2016-11-14 14:11:36 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManager.js'
2016-11-14 14:11:36 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
2016-11-14 14:11:36 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js'
2016-11-14 14:11:36 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNative.js'
2016-11-14 14:11:36 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
2016-11-14 14:11:36 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
2016-11-14 14:11:36 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
2016-11-14 14:11:36 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
2016-11-14 14:11:36 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotification.js'
2016-11-14 14:11:36 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationAction.js'
2016-11-14 14:11:36 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
2016-11-14 14:11:36 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationClient.js'
2016-11-14 14:11:36 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationLocal.js'
2016-11-14 14:11:36 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationServer.js'
2016-11-14 14:11:36 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerAction.js'
2016-11-14 14:11:36 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerDictionary.js'
2016-11-14 14:11:36 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
2016-11-14 14:11:36 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
2016-11-14 14:11:36 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
2016-11-14 14:11:36 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
2016-11-14 14:11:36 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
2016-11-14 14:11:36 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
2016-11-14 14:11:36 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
2016-11-14 14:11:36 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
2016-11-14 14:11:36 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
2016-11-14 14:11:36 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliTcpServersManager.js'
2016-11-14 14:11:36 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
2016-11-14 14:11:36 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testUsn.js'
2016-11-14 14:11:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-14 14:11:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-14 14:11:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-14 14:11:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-14 14:11:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-14 14:11:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
TAP version 13
# setup
# calling createNativeListener directly rejects
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'listening 49618'
ok 1 Should throw
# teardown
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - close'
# setup
# emits incomingConnectionState
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'listening 49620'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 2 initial connection state should be CONNECTED
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 3 final connection state should be DISCONNECTED
# teardown
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - close'
# setup
# emits routerPortConnectionFailed
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'listening 49623'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
ok 4 tried to connect to right port
ok 5 failed due to refused connection
ok 6 routerPortConnectionFailed is emitted
# teardown
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# setup
# native server connections all up
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'listening 49627'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
ok 7 Send/recvd #1 should be equal length
ok 8 Send/recvd #1 should be same
ok 9 Send/recvd #2 should be equal length
ok 10 Send/recvd #2 should be same
ok 11 Should be exactly 2 client sockets
# teardown
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# setup
# native server - closing incoming stream cleans outgoing socket
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'listening 49632'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
ok 12 socket shouldn't close until after stream
ok 13 incoming remains open
# teardown
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# setup
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# native server - closing incoming connection cleans outgoing socket
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'listening 49636'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 14 we should not have gotten an error
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 15 socket shouldn't close until after incoming
ok 16 incoming is cleaned up
# teardown
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - close'
# setup
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# native server - closing outgoing socket cleans associated mux stream
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'listening 49640'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
ok 17 stream was closed
ok 18 incoming should survive
ok 19 mux should have no streams
# teardown
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# setup
# native server - closing the whole server cleans everything up
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'listening 49644'
ok 20 we should not have gotten an error
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 21 Buffers are identical
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 22 native server is nulled out
ok 23 native server should be closed
ok 24 incoming has been removed
ok 25 Incoming should be done
ok 26 The mux object should be closed
ok 27 The mux stream should be closed
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# teardown
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# setup
# native server - we can get a ton of connections and data through and still clean up the server completely
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'listening 49648'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
ok 28 native server is nulled out
ok 29 native server should be closed
ok 30 incoming has been removed
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# teardown
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# native server - simulate mux failure, make sure everything is cleaned up
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'listening 49700'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 31 we should not have gotten an error
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 32 Buffers are identical
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 33 server should be fine
ok 34 server should be open
ok 35 incoming has been removed
ok 36 The mux object should be closed
ok 37 The mux stream should be closed
# teardown
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - close'
# setup
# native server - timing out the incoming connection cleans everything up
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'listening 49704'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 38 we should not have gotten an error
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 39 Buffers are identical
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 40 server should be fine
ok 41 server should be open
ok 42 incoming has been removed
ok 43 The mux object should be closed
ok 44 The mux stream should be closed
# teardown
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - close'
# setup
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# calling createPeerListener without calling start produces error
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'listening 49709'
# teardown
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# calling createPeerListener after calling stop produces error
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'listening 49712'
# teardown
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# can call createPeerListener (pleaseConnect === false)
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'listening 49715'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'creating new server for peerId'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peerId listening on 49716'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 45 port must be in range
# teardown
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peerId'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# calling createPeerListener (pleaseConnect === true) with unknown peer is error
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'listening 49719'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'creating new server for peerId'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peerId listening on 49720'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Issuing callNative for peerId'
2016-11-14 14:11:36 - WARN createPeerListener: 'callNative for peerId failed with Unknown Peer'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'We are emitting failedConnection with error Error: Unknown Peer and peerIdentifier peerId'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Will try to recreate server for peerId'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peerId'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'creating new server for peerId'
ok 46 should get error
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peerId listening on 49721'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peerId and portNumber 49721'
# teardown
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peerId'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# calling createPeerListener twice with same peerIdentifier should return the same port
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'listening 49724'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49725'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 47 port values should be the same
# teardown
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - closing connection to native listener closes everything and triggers new listener
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'listening 49728'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'creating new server for peer2'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 49729'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer2 - 0 - got a new incoming connection'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Issuing callNative for peer2'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'callNative for peer2 connected'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer2'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 48 Data should be of same length and content
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer2 - finish'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer2 - 0 - close'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer2 - finish'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer2 - 0 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer2 - close'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'We are emitting failedConnection with error Error: Outgoing closed, recreating connection and peerIdentifier peer2'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Will try to recreate server for peer2'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer2 - close'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer2'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'creating new server for peer2'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 49734'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer2 and portNumber 49734'
ok 49 same peer ID
ok 50 different ports
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
# teardown
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer2'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# createPeerListener - closing mux closes listener and triggers a new listener
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'listening 49737'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'creating new server for peer2'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 49738'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer2 - 0 - got a new incoming connection'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Issuing callNative for peer2'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'callNative for peer2 connected'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer2'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 51 Data should be of same length and content
2016-11-14 14:11:36 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer2 - 0 - close'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer2 - close'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer2 - finish'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer2 - finish'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer2 - 0 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'We are emitting failedConnection with error Error: Outgoing closed, recreating connection and peerIdentifier peer2'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Will try to recreate server for peer2'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer2 - close'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer2'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'creating new server for peer2'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 49743'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer2 and portNumber 49743'
ok 52 same peer ID
ok 53 different ports
# teardown
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer2'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# peerListener - forwardConnection, pleaseConnect === true - no native server
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Creating Native Server'
ok 54 Can call startUpdateAdvertisingAndListening without error
ok 55 Can call startListeningForAdvertisements without error
2016-11-14 14:11:36 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'listening 49746'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49747'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'We are emitting failedConnection with error Error: Cannot Connect To Peer and peerIdentifier peer1'
ok 56 reason should be as expected
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Will try to recreate server for peer1'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49749'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer1 and portNumber 49749'
# teardown
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# peerListener - forwardConnection, pleaseConnect === false - no native server
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Creating Native Server'
ok 57 Can call startUpdateAdvertisingAndListening without error
ok 58 Can call startListeningForAdvertisements without error
2016-11-14 14:11:36 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'listening 49752'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49753'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 59 peerPort should not be nativePort
2016-11-14 14:11:36 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'We are emitting failedConnection with error Error: Cannot Connect To Peer and peerIdentifier peer1'
ok 60 Should not get event until connection is made
ok 61 reason should be as expected
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Will try to recreate server for peer1'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - finish'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49756'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer1 and portNumber 49756'
# teardown
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
# setup
# peerListener - forwardConnection, pleaseConnect === true - with native server
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Creating Native Server'
ok 62 Can call startUpdateAdvertisingAndListening without error
ok 63 Can call startListeningForAdvertisements without error
2016-11-14 14:11:36 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'listening 49759'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49760'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
ok 64 peerPort != nativePort
ok 65 Should get spontaneous connection
# teardown
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
2016-11-14 14:11:36 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# peerListener - forwardConnection, pleaseConnect === false - with native server
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Creating Native Server'
ok 66 Can call startUpdateAdvertisingAndListening without error
ok 67 Can call startListeningForAdvertisements without error
2016-11-14 14:11:36 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'listening 49764'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49765'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 68 peerPort != nativePort
2016-11-14 14:11:36 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer1 - close'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - close'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
ok 69 Should not get unexpected connection
# teardown
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer1 - 0 - close'
# setup
2016-11-14 14:11:36 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# peerListener - forwardConnection, pleaseConnect === false - with native server and data transfer
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'listening 49770'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49771'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer1 - close'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - close'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 70 Data should be of same length and content
ok 71 Data should be of same length and content
# teardown
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer1 - 0 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:11:36 - WARN createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 -  error Error: read ECONNRESET'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - close'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# setup
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer1 - close'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# createPeerListener is idempotent
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Creating Native Server'
ok 72 Can call startUpdateAdvertisingAndListening without error
ok 73 Can call startListeningForAdvertisements without error
2016-11-14 14:11:36 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'listening 49777'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49778'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 74 Second call to existing peerListener returns existing port
# teardown
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - pleaseConnect === true, failed connection rejects promise
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Creating Native Server'
ok 75 Can call startUpdateAdvertisingAndListening without error
ok 76 Can call startListeningForAdvertisements without error
2016-11-14 14:11:36 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'listening 49781'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49782'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-14 14:11:36 - WARN createPeerListener: 'callNative for peer1 failed with a nasty error'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'We are emitting failedConnection with error Error: a nasty error and peerIdentifier peer1'
ok 77 got our failed connection
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Will try to recreate server for peer1'
ok 78 failed connection should reject with error
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49783'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer1 and portNumber 49783'
# teardown
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - pleaseConnect === true, connection resolves promise
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Creating Native Server'
ok 79 Can call startUpdateAdvertisingAndListening without error
ok 80 Can call startListeningForAdvertisements without error
2016-11-14 14:11:36 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'listening 49786'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49787'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
ok 81 Should get spontaneous connection
ok 82 promise should resolve
# teardown
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
2016-11-14 14:11:36 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# peerListener - reverseConnection, pleaseConnect === true
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Creating Native Server'
ok 83 Can call startUpdateAdvertisingAndListening without error
ok 84 Can call startListeningForAdvertisements without error
2016-11-14 14:11:36 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'listening 49791'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49792'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-14 14:11:36 - WARN createPeerListener: 'was expecting a forward connection to be made'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'We are emitting failedConnection with error Error: Cannot Connect To Peer and peerIdentifier peer1'
ok 85 reason should be as expected
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Will try to recreate server for peer1'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49793'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer1 and portNumber 49793'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer1 - close'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - close'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# teardown
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# peerListener - reverseConnection, pleaseConnect === false - no incoming
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Creating Native Server'
ok 86 Can call startUpdateAdvertisingAndListening without error
ok 87 Can call startListeningForAdvertisements without error
2016-11-14 14:11:36 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'listening 49796'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49797'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 88 peerPort should not be nativePort
2016-11-14 14:11:36 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'looking up mux for client port:  0'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'timed out waiting for incoming connection'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'reverse connection'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'looking up mux for client port:  0'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'no mux found'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'We are emitting failedConnection with error Error: Incoming connection died and peerIdentifier peer1'
ok 89 should not get event until connection is made
ok 90 reason should be as expected
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Will try to recreate server for peer1'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client - is already closed'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49799'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer1 and portNumber 49799'
# teardown
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
# setup
# peerListener - reverseConnection, pleaseConnect === false - with incoming
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Creating Native Server'
ok 91 Can call startUpdateAdvertisingAndListening without error
ok 92 Can call startListeningForAdvertisements without error
2016-11-14 14:11:36 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'listening 49802'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49803'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'looking up mux for client port:  49805'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'reverse connection'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'looking up mux for client port:  49805'
ok 93 sent and received should be the same
# teardown
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer1 - 0 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# setup
# peerListener - reverseConnection, pleaseConnect === false - no server
2016-11-14 14:11:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Creating Native Server'
ok 94 Can call startUpdateAdvertisingAndListening without error
ok 95 Can call startListeningForAdvertisements without error
2016-11-14 14:11:36 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'listening 49808'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49809'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'looking up mux for client port:  49811'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'reverse connection'
2016-11-14 14:11:36 - DEBUG createPeerListener: 'looking up mux for client port:  49811'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-14 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
ok 96 should get routerPortConnectionFailed
2016-11-14 14:11:37 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
2016-11-14 14:11:37 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
# teardown
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:37 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:11:37 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer1 - 0 - close'
2016-11-14 14:11:37 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:11:37 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:37 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
2016-11-14 14:11:37 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# setup
# createPeerListener - ask for new peer when we are at maximum and make sure we remove the right existing listener
2016-11-14 14:11:37 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:11:37 - DEBUG createNativeListener: 'listening 49815'
# teardown
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:37 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - ask for a new peer when we are not at maximum peers and make sure we do not remove any existing listeners
2016-11-14 14:11:37 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:11:37 - DEBUG createNativeListener: 'listening 49818'
# teardown
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:37 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - pleaseConnect = false - test timeout
2016-11-14 14:11:37 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:11:37 - DEBUG createNativeListener: 'listening 49821'
# teardown
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:37 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - pleaseConnect = true - test timeout
2016-11-14 14:11:37 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:11:37 - DEBUG createNativeListener: 'listening 49824'
# teardown
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:37 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - forward connection - wrong serverPort
2016-11-14 14:11:37 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:11:37 - DEBUG createNativeListener: 'listening 49827'
# teardown
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:37 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - forward connection - wrong clientPort
2016-11-14 14:11:37 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:11:37 - DEBUG createNativeListener: 'listening 49830'
# teardown
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:37 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - please connect = false, multiple connections out
2016-11-14 14:11:37 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:11:37 - DEBUG createNativeListener: 'listening 49833'
# teardown
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:37 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - please connect = false, multiple bi-directional connections
2016-11-14 14:11:37 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:11:37 - DEBUG createNativeListener: 'listening 49836'
# teardown
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:37 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - multiple parallel calls
2016-11-14 14:11:37 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:11:37 - DEBUG createNativeListener: 'listening 49839'
# teardown
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:37 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - we shouldn't create a dead pipe
2016-11-14 14:11:37 - DEBUG createNativeListener: 'Creating Native Server'
ok 97 Can call startUpdateAdvertisingAndListening without error
ok 98 Can call startListeningForAdvertisements without error
2016-11-14 14:11:37 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:11:37 - DEBUG createNativeListener: 'listening 49842'
2016-11-14 14:11:37 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49843'
2016-11-14 14:11:37 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 99 peerPort != nativePort
2016-11-14 14:11:37 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-14 14:11:37 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-14 14:11:37 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-14 14:11:37 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
ok 100 Should not get unexpected connection
2016-11-14 14:11:37 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID peer1 with port 49843'
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:37 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:11:37 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client - is already closed'
ok 101 passed
2016-11-14 14:11:37 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
# teardown
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:37 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:37 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# setup
# #_doImmediateSeqUpdate - server is not there
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:37 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer1 - close'
2016-11-14 14:11:37 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - close'
2016-11-14 14:11:37 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
2016-11-14 14:11:37 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
ok 102 Got right error
# teardown
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - server accepts & closes connection
2016-11-14 14:11:37 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
ok 103 Got socket hang up
# teardown
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - server always returns 500
2016-11-14 14:11:37 - DEBUG localSeqManager: 'Got an error trying to update seq []'
ok 104 Got 500 as expected
# teardown
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - create new seq doc
ok 105 should be equal
ok 106 revs are equal
# teardown
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - doc exists, need to get rev and update
ok 107 should be equal
ok 108 revs are equal
# teardown
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - update seq three times
ok 109 should be equal
ok 110 revs are equal
ok 111 should be equal
ok 112 revs are equal
ok 113 should be equal
ok 114 revs are equal
# teardown
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - rev got changed under us
2016-11-14 14:11:37 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
ok 115 Our rev is old so we should fail
# teardown
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - fail if stop is called
ok 116 confirm stop caused failure
# teardown
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - stop after get but before put fails right
2016-11-14 14:11:37 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
ok 117 stop caused us to fail
ok 118 We specifically failed on a stop before put
# teardown
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - fail if stop is called
ok 119 failed due to stop
ok 120 failed due to stop
# teardown
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - set seq for first time
ok 121 should be equal
# teardown
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - Fail on bad seq value
2016-11-14 14:11:37 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
ok 122 Expected bad seq error
# teardown
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - do we cancel timer properly on an immediate?
ok 123 Different promises
ok 124 Timer was cancelled
ok 125 should be equal
# teardown
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - do we wait for blocked update
ok 126 One go and one blocked
ok 127 All blocked
ok 128 Still blocked
ok 129 should be equal
# teardown
2016-11-14 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - test that we wait long enough
ok 130 We waited long enough
ok 131 should be equal
# teardown
2016-11-14 14:11:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - test that we pick up new sequences while we wait
ok 132 Should have gotten same timer promise
ok 133 Still same timer promise
ok 134 We waited long enough
ok 135 should be equal
# teardown
2016-11-14 14:11:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# closeAll can close even when connections open
2016-11-14 14:11:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 136 not possible to connect to the server anymore
# teardown
# setup
# closeAll with promise
2016-11-14 14:11:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 137 not possible to connect to the server anymore
# teardown
# setup
# closeAll properly throws when closing a non open server with eatNotRunning set to false
2016-11-14 14:11:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 138 Got the right error
# teardown
# setup
# closeAll works even with a server that is not listening yet witheatNotRunning set to true
2016-11-14 14:11:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
# setup
# Call of onCheckpointReached handler on a single db change
# teardown
# setup
# Call of multiple onCheckpointReached handlers on a single db change
# teardown
# setup
# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
ok 139 the checkpointReached handler should be called once. Called 1 time(s)
# teardown
# setup
# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
# teardown
# setup
# test defaultDirectory
ok 140 should be equal
ok 141 should be equal
ok 142 should be equal
# teardown
# setup
# test defaultAdapter
ok 143 should be equal
ok 144 should be equal
ok 145 should be equal
ok 146 should be equal
ok 147 should be equal
ok 148 should be equal
ok 149 should be equal
ok 150 should be equal
# teardown
# setup
# enqueue and run in order
ok 151 firstPromise setTimeout
ok 152 firstPromise result
ok 153 firstPromise testValue
ok 154 secondPromise setTimeout
ok 155 secondPromise result
ok 156 secondPromise testValue
ok 157 thirdPromise in promise
ok 158 thirdPromise result
ok 159 thirdPromise testValue
# teardown
# setup
# enqueueAtTop and run backwards
ok 160 thirdPromise - first to run
ok 161 thirdPromise - in resolve
ok 162 secondPromise - second to run
ok 163 secondPromise - in catch
ok 164 firstPromise - third to run
ok 165 firstPromise - in then
ok 166 testing promises
# teardown
# setup
# mix enqueue and enqueueAtTop
ok 167 fourth
ok 168 fourth
ok 169 second
ok 170 secondPromise - in then
ok 171 first
ok 172 firstPromise - in catch
ok 173 third
ok 174 thirdPromise - in then
ok 175 testingPromises
# teardown
# setup
# queues handled independently
ok 176 all short operations completed before the long resolves
# teardown
# setup
# basic
ok 177 sane
# teardown
# setup
# another
ok 178 sane
# teardown
# setup
# test thali manager spies
2016-11-14 14:11:43 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
2016-11-14 14:11:43 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
2016-11-14 14:11:43 - DEBUG thaliManager: 'creating express pouchdb instance'
ok 179 expressPouchDB was called once
ok 180 expressPouchDB was called with 2 arguments
ok 181 expressPouchDB was called with 'PouchDB' as 1-st argument
ok 182 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
ok 183 PouchDB was called once
ok 184 PouchDB was called with 1 arguments
ok 185 PouchDB was called with 'dbName' as 1-st argument
ok 186 ThaliSendNotificationBasedOnReplication was called once
ok 187 ThaliSendNotificationBasedOnReplication was called with 4 arguments
ok 188 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
ok 189 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
ok 190 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
ok 191 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
ok 192 ThaliPullReplicationFromNotification was called once
ok 193 ThaliPullReplicationFromNotification was called with 4 arguments
ok 194 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
ok 195 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
ok 196 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
ok 197 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
ok 198 Salti was called once
ok 199 Salti was called with 4 arguments
ok 200 Salti was called with 'dbName' as 1-st argument
ok 201 Salti was called with 'acl' as 2-st argument
ok 202 Salti was called with 'thaliIdCallback' as 3-st argument
ok 203 Salti was called with 'options' as 4-st argument
2016-11-14 14:11:43 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-14 14:11:43 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-14 14:11:43 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-14 14:11:43 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-14 14:11:43 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-14 14:11:43 - DEBUG thaliWifiInfrastructure: 'listening 49921'
2016-11-14 14:11:43 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
ok 204 ThaliMobile.start was called once
ok 205 ThaliMobile.start was called with 3 arguments
ok 206 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
ok 207 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
ok 208 ThaliMobile.start was called with 'networkType' as 3-st argument
ok 209 ThaliMobile.startListeningForAdvertisements was called once
ok 210 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
ok 211 ThaliMobile.startUpdateAdvertisingAndListening was called once
ok 212 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
ok 213 ThaliSendNotificationBasedOnReplication.prototype.start was called once
ok 214 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
ok 215 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
ok 216 ThaliPullReplicationFromNotification.prototype.start was called once
ok 217 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
ok 218 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
2016-11-14 14:11:43 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-14 14:11:43 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-14 14:11:43 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-14 14:11:43 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-14 14:11:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:43 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-14 14:11:43 - DEBUG thaliManager: 'stopping ThaliMobile'
ok 219 ThaliMobile.stop was called once
ok 220 ThaliMobile.stop was called with 0 arguments
ok 221 ThaliMobile.stopListeningForAdvertisements was called once
ok 222 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
ok 223 ThaliMobile.stopAdvertisingAndListening was called once
ok 224 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
ok 225 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
ok 226 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
ok 227 ThaliPullReplicationFromNotification.prototype.stop was called once
ok 228 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
# teardown
# setup
# test thali manager multiple starts and stops
2016-11-14 14:11:43 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
2016-11-14 14:11:43 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
2016-11-14 14:11:43 - DEBUG thaliManager: 'creating express pouchdb instance'
ok 229 expressPouchDB was called once
ok 230 expressPouchDB was called with 2 arguments
ok 231 expressPouchDB was called with 'PouchDB' as 1-st argument
ok 232 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
ok 233 PouchDB was called once
ok 234 PouchDB was called with 1 arguments
ok 235 PouchDB was called with 'dbName' as 1-st argument
ok 236 ThaliSendNotificationBasedOnReplication was called once
ok 237 ThaliSendNotificationBasedOnReplication was called with 4 arguments
ok 238 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
ok 239 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
ok 240 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
ok 241 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
ok 242 ThaliPullReplicationFromNotification was called once
ok 243 ThaliPullReplicationFromNotification was called with 4 arguments
ok 244 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
ok 245 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
ok 246 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
ok 247 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
ok 248 Salti was called once
ok 249 Salti was called with 4 arguments
ok 250 Salti was called with 'dbName' as 1-st argument
ok 251 Salti was called with 'acl' as 2-st argument
ok 252 Salti was called with 'thaliIdCallback' as 3-st argument
ok 253 Salti was called with 'options' as 4-st argument
2016-11-14 14:11:43 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-14 14:11:43 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-14 14:11:43 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-14 14:11:43 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-14 14:11:43 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-14 14:11:43 - DEBUG thaliWifiInfrastructure: 'listening 49922'
2016-11-14 14:11:43 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
ok 254 ThaliMobile.start was called once
ok 255 ThaliMobile.start was called with 3 arguments
ok 256 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
ok 257 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
ok 258 ThaliMobile.start was called with 'networkType' as 3-st argument
ok 259 ThaliMobile.startListeningForAdvertisements was called once
ok 260 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
ok 261 ThaliMobile.startUpdateAdvertisingAndListening was called once
ok 262 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
ok 263 ThaliSendNotificationBasedOnReplication.prototype.start was called once
ok 264 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
ok 265 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
ok 266 ThaliPullReplicationFromNotification.prototype.start was called once
ok 267 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
ok 268 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
2016-11-14 14:11:43 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-14 14:11:43 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-14 14:11:43 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-14 14:11:43 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-14 14:11:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:43 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-14 14:11:43 - DEBUG thaliManager: 'stopping ThaliMobile'
ok 269 ThaliMobile.stop was called once
ok 270 ThaliMobile.stop was called with 0 arguments
ok 271 ThaliMobile.stopListeningForAdvertisements was called once
ok 272 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
ok 273 ThaliMobile.stopAdvertisingAndListening was called once
ok 274 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
ok 275 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
ok 276 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
ok 277 ThaliPullReplicationFromNotification.prototype.stop was called once
ok 278 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
2016-11-14 14:11:43 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-14 14:11:43 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-14 14:11:43 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-14 14:11:43 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-14 14:11:43 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-14 14:11:43 - DEBUG thaliWifiInfrastructure: 'listening 49923'
2016-11-14 14:11:43 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
2016-11-14 14:11:43 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-14 14:11:43 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-14 14:11:43 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-14 14:11:43 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-14 14:11:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:43 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-14 14:11:43 - DEBUG thaliManager: 'stopping ThaliMobile'
2016-11-14 14:11:43 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-14 14:11:43 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-14 14:11:43 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-14 14:11:43 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-14 14:11:43 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-14 14:11:43 - DEBUG thaliWifiInfrastructure: 'listening 49924'
2016-11-14 14:11:43 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
2016-11-14 14:11:43 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-14 14:11:43 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-14 14:11:43 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-14 14:11:43 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-14 14:11:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:43 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-14 14:11:43 - DEBUG thaliManager: 'stopping ThaliMobile'
2016-11-14 14:11:43 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-14 14:11:43 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-14 14:11:43 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-14 14:11:43 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-14 14:11:43 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-14 14:11:43 - DEBUG thaliWifiInfrastructure: 'listening 49925'
2016-11-14 14:11:43 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
ok 279 ThaliMobile.start was called once
ok 280 ThaliMobile.start was called with 3 arguments
ok 281 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
ok 282 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
ok 283 ThaliMobile.start was called with 'networkType' as 3-st argument
ok 284 ThaliMobile.startListeningForAdvertisements was called once
ok 285 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
ok 286 ThaliMobile.startUpdateAdvertisingAndListening was called once
ok 287 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
ok 288 ThaliSendNotificationBasedOnReplication.prototype.start was called once
ok 289 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
ok 290 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
ok 291 ThaliPullReplicationFromNotification.prototype.start was called once
ok 292 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
ok 293 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
2016-11-14 14:11:43 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-14 14:11:43 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-14 14:11:43 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-14 14:11:43 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-14 14:11:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:43 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-14 14:11:43 - DEBUG thaliManager: 'stopping ThaliMobile'
# teardown
# setup
# #startListeningForAdvertisements should fail if start not called
ok 294 specific error should be returned
# teardown
ok 295 error should be null
ok 296 error should be null
# setup
# #startUpdateAdvertisingAndListening should fail if start not called
ok 297 specific error should be returned
# teardown
ok 298 error should be null
ok 299 error should be null
# setup
# should be able to call #stopListeningForAdvertisements many times
ok 300 error should be null
ok 301 error should be null
ok 302 error should be null
ok 303 error should be null
# teardown
ok 304 error should be null
ok 305 error should be null
# setup
# should be able to call #startListeningForAdvertisements many times
ok 306 error should be null
ok 307 error should be null
ok 308 error should be null
ok 309 error should be null
# teardown
2016-11-14 14:11:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 310 error should be null
ok 311 error should be null
# setup
# should be able to call #startUpdateAdvertisingAndListening many times
2016-11-14 14:11:43 - DEBUG thaliWifiInfrastructure: 'listening 49926'
ok 312 error should be null
ok 313 error should be null
ok 314 error should be null
ok 315 error should be null
# teardown
2016-11-14 14:11:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 316 error should be null
ok 317 error should be null
# setup
# should be able to call #stopAdvertisingAndListening many times
ok 318 error should be null
ok 319 error should be null
ok 320 error should be null
ok 321 error should be null
# teardown
ok 322 error should be null
ok 323 error should be null
# setup
# #start - Causing native or wifi to fail will cause a promise reject 
2016-11-14 14:11:43 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
ok 324 This should not cause wifi to fail
ok 325 native router should be bad
# teardown
ok 326 error should be null
ok 327 error should be null
# setup
# #start should fail if called twice in a row
ok 328 first call should succeed
ok 329 first call should succeed
ok 330 specific error should be returned
# teardown
ok 331 error should be null
ok 332 error should be null
# setup
# #stop should clear watchers and change peers
2016-11-14 14:11:43 - DEBUG thaliMobileNativeWrapper: 'listening 49927'
2016-11-14 14:11:43 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:11:43 - DEBUG createNativeListener: 'listening 49928'
2016-11-14 14:11:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-14 14:11:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"urn:uuid:bf1d0358-c5bf-4de9-87bf-01e09ee5386c","peerAvailable":true,"pleaseConnect":false}'
2016-11-14 14:11:44 - DEBUG createPeerListener: 'creating new server for urn:uuid:bf1d0358-c5bf-4de9-87bf-01e09ee5386c'
2016-11-14 14:11:44 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for urn:uuid:bf1d0358-c5bf-4de9-87bf-01e09ee5386c listening on 49929'
2016-11-14 14:11:44 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-14 14:11:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"urn:uuid:bf1d0358-c5bf-4de9-87bf-01e09ee5386c","peerAvailable":true,"portNumber":49929}'
ok 333 Watchers have one entry for our connection type
ok 334 Peer availabilities has one entry for our connection type
2016-11-14 14:11:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"urn:uuid:bf1d0358-c5bf-4de9-87bf-01e09ee5386c","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
2016-11-14 14:11:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-14 14:11:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-14 14:11:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:44 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:11:44 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for urn:uuid:bf1d0358-c5bf-4de9-87bf-01e09ee5386c'
2016-11-14 14:11:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 335 No watchers
ok 336 No peers
ok 337 No watchers
ok 338 No peers
ok 339 No watchers
ok 340 No peers
# teardown
ok 341 error should be null
ok 342 error should be null
# setup
# does not emit duplicate discoveryAdvertisingStateUpdate
2016-11-14 14:11:44 - DEBUG thaliWifiInfrastructure: 'listening 49930'
ok 343 called only once
ok 344 discovery state matches
ok 345 advertising state matches
# teardown
2016-11-14 14:11:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:44 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-14 14:11:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-14 14:11:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 346 error should be null
ok 347 error should be null
# setup
# does not send duplicate availability changes
ok 348 should be called once
ok 349 should not have been called more than once
# teardown
2016-11-14 14:11:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"46fed1f0-fab7-4d87-8cec-cc418696a788","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 350 error should be null
ok 351 error should be null
# setup
# can get the network status
ok 352 network status should have certain non-empty properties
# teardown
ok 353 error should be null
ok 354 error should be null
# setup
# wifi peer is marked unavailable if announcements stop
2016-11-14 14:11:44 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"70527397-41f8-4ad8-8163-fb351b3c2500","generation":0,"hostAddress":"2e0b810a","portNumber":8080}'
ok 355 peer should be available
2016-11-14 14:11:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"70527397-41f8-4ad8-8163-fb351b3c2500","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 356 peer should become unavailable
# teardown
2016-11-14 14:11:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 357 error should be null
ok 358 error should be null
# setup
# native peer should be removed if no availability updates were received during availability timeout
ok 359 peer is available
2016-11-14 14:11:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2da299a8-6f1f-4ad3-a7bf-7b3f9a8f2794","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 360 peer is not availabel because it was too silent
# teardown
ok 361 error should be null
ok 362 error should be null
# setup
# peerAvailabilityChanged - peer added/removed to/from cache (native)
ok 363 we have not added peer to the cache yet
ok 364 peer should be available
ok 365 cache contains native peer
ok 366 peer should be unavailable
ok 367 peer has been removed from cache
# teardown
ok 368 error should be null
ok 369 error should be null
# setup
# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
ok 370 we have not added peer to the cache yet
ok 371 peer should be available
ok 372 cache contains wifi peer
ok 373 peer should be unavailable
ok 374 peer has been removed from cache
# teardown
ok 375 error should be null
ok 376 error should be null
# setup
# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
ok 377 first peer is available
ok 378 second peer is available
ok 379 first and second peers are different
# teardown
2016-11-14 14:11:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9f35a650-1caf-460c-9a40-fa32c5bbd429","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
2016-11-14 14:11:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"cbcdc968-4d65-4e23-8de5-e340a1b8de85","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 380 error should be null
ok 381 error should be null
# setup
# native available - new peer is cached
ok 382 should not be in cache at start
ok 383 peer is available
# teardown
2016-11-14 14:11:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"13e0148b-1a6b-4b61-a1b2-dd60a2f22aa8","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 384 error should be null
ok 385 error should be null
# setup
# native available - peer with same port and different generation is cached (BLUETOOTH)
ok 386 peer should be available
ok 387 peer should be available
ok 388 peer should be available
# teardown
2016-11-14 14:11:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"db85f8b6-84e8-4839-a57e-5412fecec34f","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 389 error should be null
ok 390 error should be null
# setup
# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
ok 391 peer should be available
ok 392 peer should be available
# teardown
2016-11-14 14:11:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"e9e93094-199d-4513-8e9d-1aae2732d6ba","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 393 error should be null
ok 394 error should be null
# setup
# native available - peer with greater generation is cached (MPCF)
2016-11-14 14:11:46 - DEBUG SimpleThaliTape: 'test was skipped, name: 'native available - peer with greater generation is cached (MPCF)''
# teardown
ok 395 error should be null
ok 396 error should be null
# setup
# native available - peer with same or older generation is ignored (MPCF)
2016-11-14 14:11:46 - DEBUG SimpleThaliTape: 'test was skipped, name: 'native available - peer with same or older generation is ignored (MPCF)''
# teardown
ok 397 error should be null
ok 398 error should be null
# setup
# native unavailable - new peer is ignored
ok 399 NOT IMPLEMENTED # SKIP
# teardown
ok 400 error should be null
ok 401 error should be null
# setup
# native unavailable - cached peer is removed
ok 402 NOT IMPLEMENTED # SKIP
# teardown
ok 403 error should be null
ok 404 error should be null
# setup
# networkChanged - fires peerAvailabilityChanged event for wifi peers
ok 405 first peer is expected to be available
ok 406 second peer is expected to be available
2016-11-14 14:11:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ebb76aea-364e-4b24-bc38-b9301440026a","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 407 peer became unavailable
ok 408 it was wifi peer
# teardown
2016-11-14 14:11:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"24a37c64-159d-4643-bc74-5508cb30f314","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 409 error should be null
ok 410 error should be null
# setup
# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
ok 411 first peer is expected to be available
ok 412 second peer is expected to be available
2016-11-14 14:11:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"749de442-9ccd-493f-b1d7-fc10b56f483e","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 413 peer became unavailable
ok 414 it was a native peer
# teardown
2016-11-14 14:11:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c838ee11-79eb-479e-9c45-b3256ad09485","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 415 error should be null
ok 416 error should be null
# setup
# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
2016-11-14 14:11:46 - DEBUG SimpleThaliTape: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''
# teardown
ok 417 error should be null
ok 418 error should be null
# setup
# multiconnect failure - new peer is ignored (MPCF)
2016-11-14 14:11:46 - DEBUG SimpleThaliTape: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
# teardown
ok 419 error should be null
ok 420 error should be null
# setup
# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
2016-11-14 14:11:46 - DEBUG SimpleThaliTape: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
# teardown
ok 421 error should be null
ok 422 error should be null
# setup
# newAddressPort field (TCP_NATIVE)
ok 423 peer discovered first time does not have new address
ok 424 address has not been changed
ok 425 new port handled correctly
ok 426 new host handled correctly
ok 427 newAddressPort is null for unavailable peers
# teardown
ok 428 error should be null
ok 429 error should be null
# setup
# newAddressPort field (BLUETOOTH)
ok 430 peer discovered first time does not have new address
ok 431 address has not been changed
ok 432 new port handled correctly
ok 433 newAddressPort is null for unavailable peers
# teardown
ok 434 error should be null
ok 435 error should be null
# setup
# newAddressPort field (MPCF)
2016-11-14 14:11:46 - DEBUG SimpleThaliTape: 'test was skipped, name: 'newAddressPort field (MPCF)''
# teardown
ok 436 error should be null
ok 437 error should be null
# setup
# newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)
ok 438 NOT IMPLEMENTED # SKIP
# teardown
ok 439 error should be null
ok 440 error should be null
# setup
# network changes emitted correctly
2016-11-14 14:11:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
ok 441 wifi is off
2016-11-14 14:11:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
ok 442 wifi is on
# teardown
ok 443 error should be null
ok 444 error should be null
# setup
# network changes not emitted in stopped state
ok 445 event was not emitted
2016-11-14 14:11:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-14 14:11:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-14 14:11:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-14 14:11:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
# teardown
ok 446 error should be null
ok 447 error should be null
# setup
# calls correct starts when network changes
2016-11-14 14:11:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
ok 448 specific error expected
ok 449 specific error expected
2016-11-14 14:11:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-14 14:11:46 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":true,"listening":true,"advertising":true,"networkType":"WIFI"})'
2016-11-14 14:11:46 - DEBUG thaliWifiInfrastructure: 'listening 49931'
ok 450 startListeningForAdvertisements should have been called
ok 451 startUpdateAdvertisingAndListening should have been called
# teardown
2016-11-14 14:11:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:11:46 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-14 14:11:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-14 14:11:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 452 error should be null
ok 453 error should be null
# setup
# We properly fire peer unavailable and then available when connection fails
2016-11-14 14:11:46 - DEBUG SimpleThaliTape: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails''
# teardown
ok 454 error should be null
ok 455 error should be null
# setup
# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
2016-11-14 14:11:46 - DEBUG SimpleThaliTape: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
# teardown
ok 456 error should be null
ok 457 error should be null
# setup
# Test BEACONS_RETRIEVED_AND_PARSED locally
ok 458 peerIdentifier should be identifier
ok 459 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 460 good beacon
ok 461 good preAmble
ok 462 public keys match!
ok 463 must return null after successful call
ok 464 Once start returns the action should be in KILLED state
# teardown
2016-11-14 14:11:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test HTTP_BAD_RESPONSE locally
ok 465 Response should be HTTP_BAD_RESPONSE
ok 466 must return null after successful call
# teardown
2016-11-14 14:11:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test NETWORK_PROBLEM locally
ok 467 Response should be NETWORK_PROBLEM
ok 468 reject reason should be: Could not establish TCP connection
# teardown
2016-11-14 14:11:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Call the start two times
ok 469 Call start once
ok 470 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 471 must return null after successful call.
# teardown
2016-11-14 14:11:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Call the kill before calling the start
ok 472 Should be Killed
ok 473 Start after killed
# teardown
2016-11-14 14:11:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Call the kill immediately after the start
ok 474 Should be KILLED
ok 475 must return null after successful kill
# teardown
2016-11-14 14:11:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Call the kill while waiting a response from the server
ok 476 Should be KILLED
ok 477 must return null after successful kill
# teardown
2016-11-14 14:11:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test to exceed the max content size locally
ok 478 HTTP_BAD_RESPONSE should be response when content size is exceeded
ok 479 must return null after successful call
# teardown
2016-11-14 14:11:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Close the server socket while the client is waiting a response from the server. Local test.
2016-11-14 14:11:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 480 Should be NETWORK_PROBLEM caused closing server socket
ok 481 Should be Could not establish TCP connection
# teardown
# setup
# Close the client socket while the client is waiting a response from the server. Local test.
ok 482 Should be NETWORK_PROBLEM caused closing client socket
ok 483 Should be Could not establish TCP connection
# teardown
2016-11-14 14:11:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #generatePreambleAndBeacons bad args
ok 484 publicKeysToNotify cannot be null
ok 485 ecdh for local device cannot be null
ok 486 milliseconds cannot be less than 0
ok 487 milliseconds cannot be 0
ok 488 milliseconds cannot be greater than one_day
# teardown
# setup
# #generatePreambleAndBeacons empty keys to notify
ok 489 should be equal
# teardown
# setup
# #generatePreambleAndBeacons multiple keys to notify
ok 490 should be equal
ok 491 should be equal
ok 492 (unnamed assert)
ok 493 should be equal
# teardown
# setup
# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
ok 494 should throw
# teardown
# setup
# #parseBeacons invalid expiration in beaconStreamWithPreAmble
ok 495 Preamble expiration must be a 64 bit integer
# teardown
# setup
# #parseBeacons expiration out of range lower
ok 496 Expiration out of range
# teardown
# setup
# #parseBeacons expiration out of range lower
ok 497 Expiration out of range
# teardown
# setup
# #parseBeacons no beacons returns null
ok 498 should be equal
# teardown
# setup
# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
ok 499 Malformed encrypted beacon key ID
# teardown
# setup
# #parseBeacons addressBookCallback fails decrypt
ok 500 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns no matches
ok 501 should be equal
ok 502 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns spurious match
ok 503 should be equal
ok 504 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns public key
ok 505 right number of calls to address book
ok 506 good preAmble
ok 507 good unencryptedKeyId
ok 508 good beacon
# teardown
# setup
# validate generatePskIdentityField
ok 509 decoded buffers match
# teardown
# setup
# validate generatePskSecret
ok 510 secrets match
# teardown
# setup
# validate generatePskSecrets
ok 511 Matching numbers
ok 512 We have an entry!
ok 513 keys match
ok 514 secrets match
ok 515 We have an entry!
ok 516 keys match
ok 517 secrets match
ok 518 We have an entry!
ok 519 keys match
ok 520 secrets match
# teardown
# setup
# validate generateBeaconStreamAndSecrets
ok 521 Streams have same length
ok 522 matching size
ok 523 keys match
ok 524 secrets match
# teardown
# setup
# Add two Peers.
ok 525 should be equal
ok 526 should be equal
ok 527 should be equal
ok 528 should be equal
ok 529 should be equal
# teardown
2016-11-14 14:11:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# TCP_NATIVE peer loses DNS
ok 530 should be equal
ok 531 should be equal
# teardown
2016-11-14 14:11:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Received beacons with no values for us
ok 532 entry exists
ok 533 entry is resolved
# teardown
2016-11-14 14:11:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Notification action killed with a superseded
ok 534 Action should be killed
ok 535 should be equal
# teardown
2016-11-14 14:11:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Resolves an action locally
ok 536 Host address must match
ok 537 suggestedTCPTimeout must match
ok 538 connectionType must match
ok 539 portNumber must match
ok 540 peerIDs must match
# teardown
2016-11-14 14:11:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Resolves an action locally using ThaliPeerPoolDefault
ok 541 Host address must match
ok 542 suggestedTCPTimeout must match
ok 543 connectionType must match
ok 544 portNumber must match
ok 545 peerIds must match
# teardown
2016-11-14 14:11:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Action fails because of a bad hostname.
2016-11-14 14:11:53 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 546 action should be resolved with NETWORK_PROBLEM error
2016-11-14 14:11:53 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 547 action should be resolved with NETWORK_PROBLEM error
2016-11-14 14:11:53 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 548 action should be resolved with NETWORK_PROBLEM error
2016-11-14 14:11:54 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 549 action should be resolved with NETWORK_PROBLEM error
ok 550 correct number of requests
ok 551 correct number of failures
ok 552 correct final peer state
# teardown
2016-11-14 14:11:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# hostaddress is removed when the action is running. 
2016-11-14 14:11:56 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 553 should be equal
# teardown
2016-11-14 14:11:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Client to server request locally
ok 554 secrets are equal
ok 555 Public key matches with the server key
ok 556 Host address must match
ok 557 suggestedTCPTimeout must match
ok 558 connectionType must match
ok 559 portNumber must match
# teardown
2016-11-14 14:11:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test ThaliPskMapCache clean and expiration
ok 560 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
ok 561 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
ok 562 All entries should be expired after 1 second
# teardown
2016-11-14 14:11:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test ThaliPskMapCache getSecret and getPublic
ok 563 All keys need to be available in the cache
ok 564 All entries should be expired after 1 second
# teardown
2016-11-14 14:11:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test ThaliPskMapCache multiple entries
ok 565 Size of the cache should be 2
ok 566 Cache doesn't contain dictionary1
ok 567 Size of the cache should be 1
ok 568 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
2016-11-14 14:12:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Start and stop ThaliNotificationServer
ok 569 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
ok 570 ThaliMobile.StopAdvertisingAndListeningshould be called once
# teardown
2016-11-14 14:12:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Pass an empty array to ThaliNotificationServer.start
ok 571 StartUpdateAdvertisingAndListening should not be called
ok 572 ThaliMobile.StopAdvertisingAndListening should be called once
ok 573 no error
ok 574 should be 204
# teardown
2016-11-14 14:12:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Pass a string to ThaliNotificationServer.start
ok 575 StartUpdateAdvertisingAndListening should not be called
# teardown
2016-11-14 14:12:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Pass an empty parameter to ThaliNotificationServer.start
ok 576 StartUpdateAdvertisingAndListening should not be called
# teardown
2016-11-14 14:12:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make an HTTP request to /NotificationBeacons
ok 577 no error
ok 578 should be 200
ok 579 should be equal
ok 580 should be equal
ok 581 (unnamed assert)
ok 582 no error
ok 583 should be 204
# teardown
2016-11-14 14:12:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make an HTTP request to /NotificationBeacons (no keys)
ok 584 error should be null
ok 585 should be 204
# teardown
2016-11-14 14:12:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make an HTTP request to /NotificationBeaconsbefore calling start
ok 586 should be 404
# teardown
2016-11-14 14:12:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #testThaliPeerAction - test getters
ok 587 getPeerIdentifier
ok 588 getConnectionType
ok 589 getActionType
ok 590 getActionState
ok 591 getPskIdentity
ok 592 getPskKey
# teardown
# setup
# #testThaliPeerAction - start and kill
ok 593 initial state
ok 594 after start
2016-11-14 14:12:00 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 595 after kill
# teardown
# setup
# #testThaliPeerAction - double start
ok 596 should be equal
# teardown
# setup
# #testThaliPeerAction - start after kill
2016-11-14 14:12:00 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 597 clean kill
ok 598 should be equal
# teardown
# setup
# #testThaliPeerAction - make sure ids are unique
ok 599 should not be equal
# teardown
# setup
# #testThaliPeerAction - check that forever agent can be destroyed
ok 600 forever agent should have it's own destroy method
ok 601 agent's destroy should be called
ok 602 agent's destroy should not be called again
ok 603 agent is destroyed
# teardown
# setup
# Test PeerConnectionInformation basics
ok 604 connection type works
ok 605 getHostAddress works
ok 606 getPortNumber works
ok 607 getSuggestedTCPTimeout works
# teardown
# setup
# Test PeerDictionary basic functionality
ok 608 Entry counter must be 1
ok 609 Size must be 1
ok 610 Entry counter must be 2
ok 611 Size must be 2
ok 612 Entry2 should not be found
ok 613 Size must be 1
ok 614 Size must be 0
# teardown
# setup
# Test PeerDictionary with multiple entries.
ok 615 Size must be100
ok 616 Entries between 20 and MAXSIZE + 20 should exist
ok 617 WAITING state entry should not be removed
# teardown
# setup
# RESOLVED entries are removed before WAITING state entry.
ok 618 Entries between 6 and MAXSIZE + 4 should exist
ok 619 Size should be MAXSIZE
ok 620 Size should be MAXSIZE+6
# teardown
# setup
# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
ok 621 WAITING state entry should not be removed
ok 622 Waiting entries between 6 and MAXSIZE + 4 should exist
ok 623 Size should be MAXSIZE
ok 624 entryCounter should be MAXSIZE+6
# teardown
# setup
# When CONTROLLED_BY_POOL entry is removed and kill is called.
ok 625 Kill should be called once
ok 626 Size should be 100
# teardown
# setup
# #ThaliPeerPoolDefault - single action
ok 627 is an agent
ok 628 enqueue is fine
ok 629 Everything should be off the queue
# teardown
# setup
# #ThaliPeerPoolDefault - multiple actions
ok 630 is an agent
ok 631 first enqueue is fine
ok 632 is an agent
ok 633 second enqueue is fine
ok 634 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 635 Queue is empty
# teardown
# setup
# #ThaliPeerPoolDefault - PSK Pool works
ok 636 is an agent
ok 637 good enqueue
ok 638 Identity should match
2016-11-14 14:12:01 - DEBUG testUtils: 'Got response data'
2016-11-14 14:12:01 - DEBUG testUtils: 'Got end'
ok 639 Got expected response
ok 640 Got psk call back
# teardown
2016-11-14 14:12:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #ThaliPeerPoolDefault - stop
ok 641 is an agent
ok 642 enqueue worked
ok 643 is an agent
ok 644 enqueue 2 worked
ok 645 enqueue is not available when stopped
ok 646 start action is killed
ok 647 killed action is still killed
ok 648 inQueue is empty
# teardown
# setup
# #ThaliPeerPoolInterface - make sure that start verifies queue length
ok 649 good start
ok 650 good enqueue
ok 651 queue is not empty
# teardown
# setup
# #ThaliPeerPoolInterface - bad enqueues
ok 652 null arg
ok 653 wrong arg type
ok 654 wrong arg type
# teardown
# setup
# #ThaliPeerPoolInterface - do not allow same object type
ok 655 good enqueue
ok 656 already enqueued
# teardown
# setup
# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
ok 657 good enqueue
ok 658 2nd good enqueue
ok 659 we are in the pool
ok 660 We are out of the pool
ok 661 Action was killed
ok 662 The original kill was called too
ok 663 second item is still in queue
# teardown
# setup
# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
ok 664 good enqueue
ok 665 first kill
ok 666 second NOOP kill
# teardown
# setup
# #ThaliPeerPoolInterface - make sure that stop removes all actions
ok 667 1st good enqueue
ok 668 2nd good enqueue
ok 669 1st action is in the pool
ok 670 2nd action is in the pool
ok 671 1st action is out of the pool
ok 672 2st action is out of the pool
ok 673 pool is empty
# teardown
# setup
# We reject unrecognized connection type
2016-11-14 14:12:01 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 674 Got right error
ok 675 Start should not be called
ok 676 Kill should have been called at least once
# teardown
# setup
# We reject unrecognized action type
2016-11-14 14:12:01 - DEBUG SimpleThaliTape: 'test was skipped, name: 'We reject unrecognized action type''
# teardown
# setup
# One action on bluetooth
2016-11-14 14:12:01 - DEBUG SimpleThaliTape: 'test was skipped, name: 'One action on bluetooth''
# teardown
# setup
# Two notification actions
2016-11-14 14:12:01 - DEBUG SimpleThaliTape: 'test was skipped, name: 'Two notification actions''
# teardown
# setup
# replicateThroughProblems
2016-11-14 14:12:01 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
2016-11-14 14:12:01 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
2016-11-14 14:12:01 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
ok 677 should have gotten null
2016-11-14 14:12:01 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
2016-11-14 14:12:01 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
ok 678 Should have stopped nicely
2016-11-14 14:12:01 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
2016-11-14 14:12:01 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
ok 679 Still looking for null
2016-11-14 14:12:01 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
2016-11-14 14:12:01 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
2016-11-14 14:12:01 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
2016-11-14 14:12:01 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
2016-11-14 14:12:01 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
2016-11-14 14:12:01 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
ok 680 Yup, another null
ok 681 We cloned!
# teardown
# setup
# Replication goes first
2016-11-14 14:12:01 - DEBUG SimpleThaliTape: 'test was skipped, name: 'Replication goes first''
# teardown
# setup
# wifi allows many parallel non-replication actions
2016-11-14 14:12:01 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2016-11-14 14:12:01 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 606, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
ok 682 is an agent
ok 683 First null
2016-11-14 14:12:01 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 607, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
ok 684 is an agent
ok 685 Second null
2016-11-14 14:12:01 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 607, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
truetruefalsetrue
2016-11-14 14:12:01 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 606, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
truetruetruetrue
# teardown
# setup
# wifi allows no more than 2 simultaneous replication actions for same peerID
2016-11-14 14:12:01 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2016-11-14 14:12:01 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 608, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
ok 686 is an agent
ok 687 First null
2016-11-14 14:12:01 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 609, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
ok 688 is an agent
ok 689 second null
ok 690 third null
2016-11-14 14:12:01 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 608, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
2016-11-14 14:12:01 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 609, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
2016-11-14 14:12:01 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
2016-11-14 14:12:01 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
# teardown
# setup
# Make sure peerDictionaryKey is reasonable
ok 691 equal keys
ok 692 not equal connection type
ok 693 same connection type, different buffer
# teardown
# setup
# Make sure start works
2016-11-14 14:12:01 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 694 First start and on called correctly
# teardown
# setup
# Make sure stop works
ok 695 second cleared dictionary
2016-11-14 14:12:01 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 696 First start and on called correctly
ok 697 First stop and removeListener called correctly
ok 698 first action kill called
ok 699 second action kill called
ok 700 first cleared dictionary
ok 701 first cleared pool
ok 702 second cleared dictionary
ok 703 second cleared pool
# teardown
# setup
# Simple peer event
2016-11-14 14:12:01 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 704 listener has been set
ok 705 peer dictionary has expected number of entries
ok 706 Dictionary and pool have same action
ok 707 ads match
ok 708 PouchDB matches
ok 709 DB Names match
ok 710 public keys match
ok 711 peer dictionary has expected number of entries
ok 712 Dictionary and pool have same action
ok 713 ads match
ok 714 PouchDB matches
ok 715 DB Names match
ok 716 public keys match
2016-11-14 14:12:01 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
ok 717 start called once
ok 718 One entry left
ok 719 Dictionary and pool have same action
ok 720 Start never called
ok 721 Kill called once
ok 722 no entries left
ok 723 Third action is dead
ok 724 peer dictionary has expected number of entries
ok 725 Dictionary and pool have same action
ok 726 ads match
ok 727 PouchDB matches
ok 728 DB Names match
ok 729 public keys match
# teardown
# setup
# Server is not there
2016-11-14 14:12:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:01 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
2016-11-14 14:12:01 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: connect ECONNREFUSED  and it caused us to complete'
ok 730 right error
# teardown
2016-11-14 14:12:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Server accepts & closes connection
2016-11-14 14:12:01 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
2016-11-14 14:12:01 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
ok 731 right error
# teardown
2016-11-14 14:12:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Server always returns 500
2016-11-14 14:12:01 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
2016-11-14 14:12:01 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
ok 732 Got error as expected
# teardown
2016-11-14 14:12:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Server always returns 401
2016-11-14 14:12:01 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
2016-11-14 14:12:01 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
ok 733 Got error as expected
# teardown
2016-11-14 14:12:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Server always returns 403
2016-11-14 14:12:01 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
2016-11-14 14:12:01 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
ok 734 Got error as expected
# teardown
2016-11-14 14:12:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make sure docs replicate
2016-11-14 14:12:01 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
2016-11-14 14:12:01 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
2016-11-14 14:12:01 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
ok 735 should be equal
ok 736 All tests passed!
# teardown
2016-11-14 14:12:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Do nothing and make sure we time out
2016-11-14 14:12:02 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
2016-11-14 14:12:04 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2016-11-14 14:12:04 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
ok 737 action should be killed
ok 738 Error should be timed out
ok 739 No doc found
# teardown
2016-11-14 14:12:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Do something and make sure we time out
2016-11-14 14:12:04 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
2016-11-14 14:12:04 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
ok 740 should be equal
2016-11-14 14:12:06 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2016-11-14 14:12:06 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
ok 741 action should be killed
ok 742 Error should be timed out
# teardown
2016-11-14 14:12:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Start replicating and then catch error when server goes
ok 743 socket hung up
# teardown
2016-11-14 14:12:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make sure clone works
ok 744 same getPeerAdvertisesDataForUs
ok 745 Same pouchdB
ok 746 same dbName
ok 747 Same public key
# teardown
# setup
# compareBufferArrays
ok 748 should throw
ok 749 should throw
ok 750 (unnamed assert)
ok 751 (unnamed assert)
ok 752 (unnamed assert)
ok 753 (unnamed assert)
ok 754 (unnamed assert)
# teardown
# setup
# Call start twice and get error
ok 755 should throw
# teardown
# setup
# Start and make sure it runs
# teardown
# setup
# Make sure getTimeWhenRun is right after start
ok 756 (unnamed assert)
# teardown
# setup
# Make sure getTimeWhenRun is -1 after function is called
ok 757 should be equal
# teardown
# setup
# Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
ok 758 should be equal
ok 759 should be equal
ok 760 should throw
# teardown
# setup
# Test TransientState
ok 761 should throw
ok 762 should throw
ok 763 should be equal
ok 764 should be equal
ok 765 should be equal
ok 766 should be equal
ok 767 (unnamed assert)
ok 768 (unnamed assert)
# teardown
# setup
# No peers and empty database
ok 769 verify failed
ok 770 constructor called once
ok 771 constructor called with right args
ok 772 match start arg
ok 773 start called once
ok 774 stop called once
ok 775 stop after start
# teardown
# setup
# One peer and empty DB
ok 776 verify failed
ok 777 constructor called once
ok 778 constructor called with right args
ok 779 match start arg
ok 780 start called once
ok 781 stop called once
ok 782 stop after start
2016-11-14 14:12:06 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# One peer with _Local set behind current seq
ok 783 verify failed
ok 784 constructor called once
ok 785 constructor called with right args
ok 786 match start arg
ok 787 start called once
ok 788 stop called once
ok 789 stop after start
2016-11-14 14:12:06 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# One peer with _Local set equal to current seq
ok 790 verify failed
ok 791 constructor called once
ok 792 constructor called with right args
ok 793 match start arg
ok 794 start called once
ok 795 stop called once
ok 796 stop after start
2016-11-14 14:12:06 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# One peer with _Local set ahead of current seq (and no this should not happen)
ok 797 verify failed
ok 798 constructor called once
ok 799 constructor called with right args
ok 800 match start arg
ok 801 start called once
ok 802 stop called once
ok 803 stop after start
2016-11-14 14:12:06 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# Three peers, one not in DB, one behind and one ahead
ok 804 verify failed
ok 805 constructor called once
ok 806 constructor called with right args
ok 807 match start arg
ok 808 start called once
ok 809 stop called once
ok 810 stop after start
2016-11-14 14:12:06 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# More than maximum peers, make sure we only send maximum allowed
ok 811 verify failed
ok 812 constructor called once
ok 813 constructor called with right args
ok 814 match start arg
ok 815 start called once
ok 816 stop called once
ok 817 stop after start
2016-11-14 14:12:06 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# two peers with empty DB, update the doc
2016-11-14 14:12:06 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 818 verify failed
ok 819 constructor called once
ok 820 constructor called with right args
ok 821 last start before stop
ok 822 empty first start
ok 823 full second start
ok 824 only 2 timers
2016-11-14 14:12:06 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# add doc and make sure tokens refresh when they expire
2016-11-14 14:12:06 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
2016-11-14 14:12:06 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 825 verify failed
ok 826 constructor called once
ok 827 constructor called with right args
ok 828 start before stop
ok 829 We got at least 3 calls to start
ok 830 at least 3
ok 831 default 1
ok 832 1 run
ok 833 default 2
ok 834 2 run
ok 835 default 3
2016-11-14 14:12:07 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# start and stop and start and stop
ok 836 start out null
ok 837 back to null
2016-11-14 14:12:07 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 838 still null
ok 839 verify failed
ok 840 constructor called once
ok 841 constructor called with right args
ok 842 first start before first stop
ok 843 first stop before second start
ok 844 second start before second stop
2016-11-14 14:12:07 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# two identical starts in a row
ok 845 verify failed
ok 846 constructor called once
ok 847 constructor called with right args
ok 848 (unnamed assert)
2016-11-14 14:12:07 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# two different starts in a row
2016-11-14 14:12:07 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 849 verify failed
ok 850 constructor called once
ok 851 constructor called with right args
ok 852 (unnamed assert)
ok 853 (unnamed assert)
# teardown
# setup
# two stops and a start and two stops
ok 854 verify failed
ok 855 constructor called once
ok 856 constructor called with right args
ok 857 start before stop
2016-11-14 14:12:07 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# we properly enqueue requests so no then needed
2016-11-14 14:12:07 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 858 verify failed
ok 859 constructor called once
ok 860 constructor called with right args
ok 861 start before stop
# teardown
# setup
# test calculateSeqPointKeyId
ok 862 should be equal
ok 863 should be equal
# teardown
# setup
# can create servers manager
ok 864 serversManager must not be null
ok 865 serversManager must be an object
# teardown
# setup
# calling stop without start causes error
ok 866 We need to call start first
# teardown
# setup
# can start/stop servers manager
2016-11-14 14:12:07 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:07 - DEBUG createNativeListener: 'listening 50054'
ok 867 port must be in range
# teardown
2016-11-14 14:12:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:07 - DEBUG createNativeListener: 'Native Server - close'
# setup
# starting twice resolves with listening port
2016-11-14 14:12:07 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:07 - DEBUG createNativeListener: 'listening 50055'
ok 868 second start should return same port
# teardown
2016-11-14 14:12:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:07 - DEBUG createNativeListener: 'Native Server - close'
# setup
# terminateIncomingConnection will terminate a connection
2016-11-14 14:12:07 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:07 - DEBUG createNativeListener: 'listening 50057'
2016-11-14 14:12:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:12:07 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 869 we should be connected
2016-11-14 14:12:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 870 now we are disconnected
2016-11-14 14:12:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
2016-11-14 14:12:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:07 - DEBUG createNativeListener: 'Native Server - close'
# setup
# terminate an Outgoing connection
2016-11-14 14:12:07 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
ok 871 Passed bogus id
2016-11-14 14:12:07 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
ok 872 Passed good id but bogus port
2016-11-14 14:12:07 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
ok 873 Passed right context
ok 874 Right server
ok 875 No error should be set
ok 876 Retry should be false
ok 877 We called close server
# teardown
# setup
ok 878 should be in started state
# After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
2016-11-14 14:12:07 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"9d7db346-6d50-4edd-9952-f3efd0d8514e","generation":0,"hostAddress":"64f91796","portNumber":8080}'
ok 879 peer identifier should match
ok 880 generation should be 0
ok 881 host address should match
ok 882 port should match
2016-11-14 14:12:07 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"9d7db346-6d50-4edd-9952-f3efd0d8514e","generation":0,"portNumber":null,"hostAddress":null}'
ok 883 generation should be 0
ok 884 host address should be null
ok 885 port should should be null
# teardown
ok 886 should not be in started state
# setup
ok 887 should be in started state
# #startUpdateAdvertisingAndListening correctly updates USN
2016-11-14 14:12:07 - DEBUG thaliWifiInfrastructure: 'listening 50059'
ok 888 first invocation sets 0 generation
ok 889 second invocation doesn’t change UUID but increments generation
ok 890 third invocation doesn’t change UUID but increments generation
# teardown
2016-11-14 14:12:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 891 should not be in started state
# setup
ok 892 should be in started state
# #startUpdateAdvertisingAndListening generates new peerIdentifier after #stopAdvertisingAndListening has been called
2016-11-14 14:12:07 - DEBUG thaliWifiInfrastructure: 'listening 50060'
2016-11-14 14:12:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:07 - DEBUG thaliWifiInfrastructure: 'listening 50061'
ok 893 new UUID after advertising is stopped
# teardown
2016-11-14 14:12:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 894 should not be in started state
# setup
ok 895 should be in started state
# #startUpdateAdvertisingAndListening sends correct requests
2016-11-14 14:12:07 - DEBUG thaliWifiInfrastructure: 'listening 50062'
2016-11-14 14:12:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 896 advertise-alive fired with expected usn
ok 897 advertise-bye fired with expected usn
# teardown
ok 898 should not be in started state
# setup
ok 899 should be in started state
# messages with invalid location or USN should be ignored
2016-11-14 14:12:07 - WARN thaliWifiInfrastructure: 'Failed to parse a valid port number from location: http://foo.bar:90000'
ok 900 should not have emitted with invalid port
2016-11-14 14:12:07 - WARN thaliWifiInfrastructure: 'Invalid USN (expected "data:" prefix): foobar'
ok 901 should not have emitted with invalid USN
# teardown
ok 902 should not be in started state
# setup
ok 903 should be in started state
# Delayed own message are still ignored after advertisement has been toggled on and off several times
2016-11-14 14:12:07 - DEBUG thaliWifiInfrastructure: 'listening 50063'
2016-11-14 14:12:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:07 - DEBUG thaliWifiInfrastructure: 'listening 50064'
2016-11-14 14:12:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:07 - DEBUG thaliWifiInfrastructure: 'listening 50065'
2016-11-14 14:12:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:07 - DEBUG thaliWifiInfrastructure: 'listening 50066'
ok 904 all captured messages are not handled
# teardown
2016-11-14 14:12:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 905 should not be in started state
# setup
ok 906 should be in started state
# verify that Thali-specific messages are filtered correctly
ok 907 messages with irrelevant NT should be ignored
ok 908 relevant messages should not be ignored
# teardown
ok 909 should not be in started state
# setup
ok 910 should be in started state
# #startListeningForAdvertisements should fail if start not called
ok 911 specific error should be returned
# teardown
ok 912 should not be in started state
# setup
ok 913 should be in started state
# #startUpdateAdvertisingAndListening should fail if start not called
ok 914 specific error should be returned
# teardown
ok 915 should not be in started state
# setup
ok 916 should be in started state
# #start should fail if called twice in a row
ok 917 specific error should be received
# teardown
ok 918 should not be in started state
# setup
ok 919 should be in started state
# should not be started after stop is called
ok 920 should not be started
ok 921 should not be listening
ok 922 should not target listening
ok 923 should not be advertising
ok 924 should not target advertising
# teardown
ok 925 should not be in started state
# setup
ok 926 should be in started state
# #startUpdateAdvertisingAndListening should fail invalid router has been passed
2016-11-14 14:12:07 - ERROR thaliWifiInfrastructure: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 927 specific error should be received
# teardown
ok 928 should not be in started state
# setup
ok 929 should be in started state
# #startUpdateAdvertisingAndListening should fail if router server starting fails
2016-11-14 14:12:07 - ERROR thaliWifiInfrastructure: 'Router server emitted an error: Error: listen EADDRINUSE'
ok 930 specific error expected
# teardown
ok 931 should not be in started state
# setup
ok 932 should be in started state
# #startUpdateAdvertisingAndListening should start hosting given router object
2016-11-14 14:12:07 - DEBUG thaliWifiInfrastructure: 'listening 50068'
ok 933 server should respond with code 200
# teardown
2016-11-14 14:12:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 934 should not be in started state
# setup
ok 935 should be in started state
# #startUpdateAdvertisingAndListening bad psk should be rejected object
2016-11-14 14:12:07 - DEBUG thaliWifiInfrastructure: 'listening 50070'
ok 936 Connection should be rejected
# teardown
2016-11-14 14:12:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 937 should not be in started state
# setup
ok 938 should be in started state
# #stop can be called multiple times in a row
ok 939 should be in stopped state
ok 940 should still be in stopped state
# teardown
ok 941 should not be in started state
# setup
ok 942 should be in started state
# #startListeningForAdvertisements can be called multiple times in a row
ok 943 should be in listening state
ok 944 should still be in listening state
# teardown
ok 945 should not be in started state
# setup
ok 946 should be in started state
# #stopListeningForAdvertisements can be called multiple times in a row
ok 947 should not be in listening state
ok 948 should still not be in listening state
# teardown
ok 949 should not be in started state
# setup
ok 950 should be in started state
# #stopAdvertisingAndListening can be called multiple times in a row
ok 951 should not be in advertising state
ok 952 should still not be in advertising state
# teardown
ok 953 should not be in started state
# setup
ok 954 should be in started state
# functions are run from a queue in the right order
2016-11-14 14:12:07 - DEBUG thaliWifiInfrastructure: 'listening 50072'
2016-11-14 14:12:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 955 call order must match
# teardown
ok 956 should not be in started state
# setup
ok 957 should be in started state
# does not get peer changes from self
2016-11-14 14:12:07 - DEBUG thaliWifiInfrastructure: 'listening 50073'
# teardown
2016-11-14 14:12:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 958 should not be in started state
# setup
# Correctly parses/stringifies USN
ok 959 correctly parses USN string
ok 960 throws if usn has invalid prefix
ok 961 throws if usn has invalid identifier format
ok 962 throws if usn has invalid generation
ok 963 correctly stringifies peer
# teardown
2016-11-14 14:12:09 - DEBUG SimpleThaliTape: 'all unit tests succeeded, platformName: 'android''
2016-11-14 14:12:09 - DEBUG SimpleThaliTape: 'skipped tests: '["native available - peer with greater generation is cached (MPCF)","native available - peer with same or older generation is ignored (MPCF)","networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)","multiconnect failure - new peer is ignored (MPCF)","multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)","newAddressPort field (MPCF)","We properly fire peer unavailable and then available when connection fails","If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen","We reject unrecognized action type","One action on bluetooth","Two notification actions","Replication goes first"]''
2016-11-14 14:12:09 - DEBUG SimpleThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'
2016-11-14 14:12:09 - INFO runTests: 'Finished'

1..963
# tests 963
# pass  963

# ok

2016-11-14 14:12:11 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: android'
2016-11-14 14:12:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreateNativeListener.js'
2016-11-14 14:12:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js'
2016-11-14 14:12:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js'
2016-11-14 14:12:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
2016-11-14 14:12:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
2016-11-14 14:12:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testNativeMethod.js'
2016-11-14 14:12:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
2016-11-14 14:12:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBGenerator.js'
2016-11-14 14:12:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPromiseQueue.js'
2016-11-14 14:12:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testTests.js'
2016-11-14 14:12:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManager.js'
2016-11-14 14:12:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
2016-11-14 14:12:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js'
2016-11-14 14:12:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNative.js'
2016-11-14 14:12:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
2016-11-14 14:12:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
2016-11-14 14:12:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
2016-11-14 14:12:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
2016-11-14 14:12:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotification.js'
2016-11-14 14:12:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationAction.js'
2016-11-14 14:12:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
2016-11-14 14:12:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationClient.js'
2016-11-14 14:12:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationLocal.js'
2016-11-14 14:12:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationServer.js'
2016-11-14 14:12:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerAction.js'
2016-11-14 14:12:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerDictionary.js'
2016-11-14 14:12:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
2016-11-14 14:12:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
2016-11-14 14:12:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
2016-11-14 14:12:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
2016-11-14 14:12:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
2016-11-14 14:12:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
2016-11-14 14:12:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
2016-11-14 14:12:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
2016-11-14 14:12:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
2016-11-14 14:12:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliTcpServersManager.js'
2016-11-14 14:12:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
2016-11-14 14:12:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testUsn.js'
2016-11-14 14:12:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-14 14:12:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-14 14:12:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-14 14:12:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-14 14:12:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-14 14:12:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
TAP version 13
# setup
# calling createNativeListener directly rejects
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'listening 50075'
ok 1 Should throw
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - close'
# setup
# emits incomingConnectionState
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'listening 50077'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 2 initial connection state should be CONNECTED
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 3 final connection state should be DISCONNECTED
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - close'
# setup
# emits routerPortConnectionFailed
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'listening 50080'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
ok 4 tried to connect to right port
ok 5 failed due to refused connection
ok 6 routerPortConnectionFailed is emitted
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# setup
# native server connections all up
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'listening 50084'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
ok 7 Send/recvd #1 should be equal length
ok 8 Send/recvd #1 should be same
ok 9 Send/recvd #2 should be equal length
ok 10 Send/recvd #2 should be same
ok 11 Should be exactly 2 client sockets
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# setup
# native server - closing incoming stream cleans outgoing socket
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'listening 50089'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
ok 12 socket shouldn't close until after stream
ok 13 incoming remains open
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# setup
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# native server - closing incoming connection cleans outgoing socket
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'listening 50093'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 14 we should not have gotten an error
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 15 socket shouldn't close until after incoming
ok 16 incoming is cleaned up
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - close'
# setup
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# native server - closing outgoing socket cleans associated mux stream
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'listening 50097'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
ok 17 stream was closed
ok 18 incoming should survive
ok 19 mux should have no streams
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# setup
# native server - closing the whole server cleans everything up
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'listening 50101'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 20 we should not have gotten an error
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 21 Buffers are identical
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 22 native server is nulled out
ok 23 native server should be closed
ok 24 incoming has been removed
ok 25 Incoming should be done
ok 26 The mux object should be closed
ok 27 The mux stream should be closed
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# setup
# native server - we can get a ton of connections and data through and still clean up the server completely
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'listening 50105'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
ok 28 native server is nulled out
ok 29 native server should be closed
ok 30 incoming has been removed
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# native server - simulate mux failure, make sure everything is cleaned up
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'listening 50157'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 31 we should not have gotten an error
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 32 Buffers are identical
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 33 server should be fine
ok 34 server should be open
ok 35 incoming has been removed
ok 36 The mux object should be closed
ok 37 The mux stream should be closed
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - close'
# setup
# native server - timing out the incoming connection cleans everything up
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'listening 50161'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 38 we should not have gotten an error
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 39 Buffers are identical
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 40 server should be fine
ok 41 server should be open
ok 42 incoming has been removed
ok 43 The mux object should be closed
ok 44 The mux stream should be closed
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - close'
# setup
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# calling createPeerListener without calling start produces error
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'listening 50166'
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# calling createPeerListener after calling stop produces error
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'listening 50169'
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# can call createPeerListener (pleaseConnect === false)
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'listening 50172'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'creating new server for peerId'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peerId listening on 50173'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 45 port must be in range
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peerId'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# calling createPeerListener (pleaseConnect === true) with unknown peer is error
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'listening 50176'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'creating new server for peerId'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peerId listening on 50177'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Issuing callNative for peerId'
2016-11-14 14:12:12 - WARN createPeerListener: 'callNative for peerId failed with Unknown Peer'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'We are emitting failedConnection with error Error: Unknown Peer and peerIdentifier peerId'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Will try to recreate server for peerId'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peerId'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'creating new server for peerId'
ok 46 should get error
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peerId listening on 50178'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peerId and portNumber 50178'
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peerId'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# calling createPeerListener twice with same peerIdentifier should return the same port
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'listening 50181'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50182'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 47 port values should be the same
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - closing connection to native listener closes everything and triggers new listener
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'listening 50185'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'creating new server for peer2'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 50186'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer2 - 0 - got a new incoming connection'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Issuing callNative for peer2'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'callNative for peer2 connected'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer2'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 48 Data should be of same length and content
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer2 - finish'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer2 - 0 - close'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer2 - finish'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer2 - 0 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer2 - close'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'We are emitting failedConnection with error Error: Outgoing closed, recreating connection and peerIdentifier peer2'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Will try to recreate server for peer2'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer2 - close'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer2'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'creating new server for peer2'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 50191'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer2 and portNumber 50191'
ok 49 same peer ID
ok 50 different ports
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer2'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# createPeerListener - closing mux closes listener and triggers a new listener
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'listening 50194'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'creating new server for peer2'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 50195'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer2 - 0 - got a new incoming connection'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Issuing callNative for peer2'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'callNative for peer2 connected'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer2'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 51 Data should be of same length and content
2016-11-14 14:12:12 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer2 - 0 - close'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer2 - close'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer2 - finish'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer2 - finish'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer2 - 0 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'We are emitting failedConnection with error Error: Outgoing closed, recreating connection and peerIdentifier peer2'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Will try to recreate server for peer2'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer2 - close'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer2'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'creating new server for peer2'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 50200'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer2 and portNumber 50200'
ok 52 same peer ID
ok 53 different ports
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer2'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# peerListener - forwardConnection, pleaseConnect === true - no native server
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Creating Native Server'
ok 54 Can call startUpdateAdvertisingAndListening without error
ok 55 Can call startListeningForAdvertisements without error
2016-11-14 14:12:12 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'listening 50203'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50204'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'We are emitting failedConnection with error Error: Cannot Connect To Peer and peerIdentifier peer1'
ok 56 reason should be as expected
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Will try to recreate server for peer1'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50206'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer1 and portNumber 50206'
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# peerListener - forwardConnection, pleaseConnect === false - no native server
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Creating Native Server'
ok 57 Can call startUpdateAdvertisingAndListening without error
ok 58 Can call startListeningForAdvertisements without error
2016-11-14 14:12:12 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'listening 50209'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50210'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 59 peerPort should not be nativePort
2016-11-14 14:12:12 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'We are emitting failedConnection with error Error: Cannot Connect To Peer and peerIdentifier peer1'
ok 60 Should not get event until connection is made
ok 61 reason should be as expected
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Will try to recreate server for peer1'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - finish'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50213'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer1 and portNumber 50213'
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
# setup
# peerListener - forwardConnection, pleaseConnect === true - with native server
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Creating Native Server'
ok 62 Can call startUpdateAdvertisingAndListening without error
ok 63 Can call startListeningForAdvertisements without error
2016-11-14 14:12:12 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'listening 50216'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50217'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
ok 64 peerPort != nativePort
ok 65 Should get spontaneous connection
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
2016-11-14 14:12:12 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# peerListener - forwardConnection, pleaseConnect === false - with native server
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Creating Native Server'
ok 66 Can call startUpdateAdvertisingAndListening without error
ok 67 Can call startListeningForAdvertisements without error
2016-11-14 14:12:12 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'listening 50221'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50222'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 68 peerPort != nativePort
2016-11-14 14:12:12 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer1 - close'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - close'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
ok 69 Should not get unexpected connection
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer1 - 0 - close'
# setup
2016-11-14 14:12:12 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# peerListener - forwardConnection, pleaseConnect === false - with native server and data transfer
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'listening 50227'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50228'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer1 - close'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - close'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 70 Data should be of same length and content
ok 71 Data should be of same length and content
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer1 - 0 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:12:12 - WARN createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 -  error Error: read ECONNRESET'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - close'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# setup
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer1 - close'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# createPeerListener is idempotent
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Creating Native Server'
ok 72 Can call startUpdateAdvertisingAndListening without error
ok 73 Can call startListeningForAdvertisements without error
2016-11-14 14:12:12 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'listening 50234'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50235'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 74 Second call to existing peerListener returns existing port
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - pleaseConnect === true, failed connection rejects promise
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Creating Native Server'
ok 75 Can call startUpdateAdvertisingAndListening without error
ok 76 Can call startListeningForAdvertisements without error
2016-11-14 14:12:12 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'listening 50238'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50239'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-14 14:12:12 - WARN createPeerListener: 'callNative for peer1 failed with a nasty error'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'We are emitting failedConnection with error Error: a nasty error and peerIdentifier peer1'
ok 77 got our failed connection
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Will try to recreate server for peer1'
ok 78 failed connection should reject with error
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50240'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer1 and portNumber 50240'
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - pleaseConnect === true, connection resolves promise
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Creating Native Server'
ok 79 Can call startUpdateAdvertisingAndListening without error
ok 80 Can call startListeningForAdvertisements without error
2016-11-14 14:12:12 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'listening 50243'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50244'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
ok 81 Should get spontaneous connection
ok 82 promise should resolve
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
2016-11-14 14:12:12 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# peerListener - reverseConnection, pleaseConnect === true
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Creating Native Server'
ok 83 Can call startUpdateAdvertisingAndListening without error
ok 84 Can call startListeningForAdvertisements without error
2016-11-14 14:12:12 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'listening 50248'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50249'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-14 14:12:12 - WARN createPeerListener: 'was expecting a forward connection to be made'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'We are emitting failedConnection with error Error: Cannot Connect To Peer and peerIdentifier peer1'
ok 85 reason should be as expected
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Will try to recreate server for peer1'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50250'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer1 and portNumber 50250'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer1 - close'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - close'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# peerListener - reverseConnection, pleaseConnect === false - no incoming
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Creating Native Server'
ok 86 Can call startUpdateAdvertisingAndListening without error
ok 87 Can call startListeningForAdvertisements without error
2016-11-14 14:12:12 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'listening 50253'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50254'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 88 peerPort should not be nativePort
2016-11-14 14:12:12 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'looking up mux for client port:  0'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'timed out waiting for incoming connection'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'reverse connection'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'looking up mux for client port:  0'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'no mux found'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'We are emitting failedConnection with error Error: Incoming connection died and peerIdentifier peer1'
ok 89 should not get event until connection is made
ok 90 reason should be as expected
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Will try to recreate server for peer1'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client - is already closed'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50256'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer1 and portNumber 50256'
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
# setup
# peerListener - reverseConnection, pleaseConnect === false - with incoming
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Creating Native Server'
ok 91 Can call startUpdateAdvertisingAndListening without error
ok 92 Can call startListeningForAdvertisements without error
2016-11-14 14:12:12 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'listening 50259'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50260'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'looking up mux for client port:  50262'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'reverse connection'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'looking up mux for client port:  50262'
ok 93 sent and received should be the same
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer1 - 0 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# setup
# peerListener - reverseConnection, pleaseConnect === false - no server
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Creating Native Server'
ok 94 Can call startUpdateAdvertisingAndListening without error
ok 95 Can call startListeningForAdvertisements without error
2016-11-14 14:12:12 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'listening 50265'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50266'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'looking up mux for client port:  50268'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'reverse connection'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'looking up mux for client port:  50268'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
ok 96 should get routerPortConnectionFailed
2016-11-14 14:12:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer1 - 0 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# setup
# createPeerListener - ask for new peer when we are at maximum and make sure we remove the right existing listener
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'listening 50272'
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - ask for a new peer when we are not at maximum peers and make sure we do not remove any existing listeners
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'listening 50275'
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - pleaseConnect = false - test timeout
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'listening 50278'
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - pleaseConnect = true - test timeout
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'listening 50281'
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - forward connection - wrong serverPort
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'listening 50284'
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - forward connection - wrong clientPort
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'listening 50287'
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - please connect = false, multiple connections out
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'listening 50290'
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - please connect = false, multiple bi-directional connections
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'listening 50293'
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - multiple parallel calls
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'listening 50296'
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - we shouldn't create a dead pipe
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Creating Native Server'
ok 97 Can call startUpdateAdvertisingAndListening without error
ok 98 Can call startListeningForAdvertisements without error
2016-11-14 14:12:12 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'listening 50299'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50300'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 99 peerPort != nativePort
2016-11-14 14:12:12 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
ok 100 Should not get unexpected connection
2016-11-14 14:12:12 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID peer1 with port 50300'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client - is already closed'
ok 101 passed
2016-11-14 14:12:12 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# setup
# #_doImmediateSeqUpdate - server is not there
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer1 - close'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - close'
2016-11-14 14:12:12 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
2016-11-14 14:12:12 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
ok 102 Got right error
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - server accepts & closes connection
2016-11-14 14:12:12 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
ok 103 Got socket hang up
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - server always returns 500
2016-11-14 14:12:12 - DEBUG localSeqManager: 'Got an error trying to update seq []'
ok 104 Got 500 as expected
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - create new seq doc
ok 105 should be equal
ok 106 revs are equal
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - doc exists, need to get rev and update
ok 107 should be equal
ok 108 revs are equal
# teardown
2016-11-14 14:12:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - update seq three times
ok 109 should be equal
ok 110 revs are equal
ok 111 should be equal
ok 112 revs are equal
ok 113 should be equal
ok 114 revs are equal
# teardown
2016-11-14 14:12:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - rev got changed under us
2016-11-14 14:12:13 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
ok 115 Our rev is old so we should fail
# teardown
2016-11-14 14:12:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - fail if stop is called
ok 116 confirm stop caused failure
# teardown
2016-11-14 14:12:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - stop after get but before put fails right
2016-11-14 14:12:13 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
ok 117 stop caused us to fail
ok 118 We specifically failed on a stop before put
# teardown
2016-11-14 14:12:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - fail if stop is called
ok 119 failed due to stop
ok 120 failed due to stop
# teardown
2016-11-14 14:12:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - set seq for first time
ok 121 should be equal
# teardown
2016-11-14 14:12:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - Fail on bad seq value
2016-11-14 14:12:13 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
ok 122 Expected bad seq error
# teardown
2016-11-14 14:12:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - do we cancel timer properly on an immediate?
ok 123 Different promises
ok 124 Timer was cancelled
ok 125 should be equal
# teardown
2016-11-14 14:12:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - do we wait for blocked update
ok 126 One go and one blocked
ok 127 All blocked
ok 128 Still blocked
ok 129 should be equal
# teardown
2016-11-14 14:12:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - test that we wait long enough
ok 130 We waited long enough
ok 131 should be equal
# teardown
2016-11-14 14:12:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - test that we pick up new sequences while we wait
ok 132 Should have gotten same timer promise
ok 133 Still same timer promise
ok 134 We waited long enough
ok 135 should be equal
# teardown
2016-11-14 14:12:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# closeAll can close even when connections open
2016-11-14 14:12:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 136 not possible to connect to the server anymore
# teardown
# setup
# closeAll with promise
2016-11-14 14:12:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 137 not possible to connect to the server anymore
# teardown
# setup
# closeAll properly throws when closing a non open server with eatNotRunning set to false
2016-11-14 14:12:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 138 Got the right error
# teardown
# setup
# closeAll works even with a server that is not listening yet witheatNotRunning set to true
2016-11-14 14:12:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
# setup
# Call of onCheckpointReached handler on a single db change
# teardown
# setup
# Call of multiple onCheckpointReached handlers on a single db change
# teardown
# setup
# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
ok 139 the checkpointReached handler should be called once. Called 1 time(s)
# teardown
# setup
# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
# teardown
# setup
# test defaultDirectory
ok 140 should be equal
ok 141 should be equal
ok 142 should be equal
# teardown
# setup
# test defaultAdapter
ok 143 should be equal
ok 144 should be equal
ok 145 should be equal
ok 146 should be equal
ok 147 should be equal
ok 148 should be equal
ok 149 should be equal
ok 150 should be equal
# teardown
# setup
# enqueue and run in order
ok 151 firstPromise setTimeout
ok 152 firstPromise result
ok 153 firstPromise testValue
ok 154 secondPromise setTimeout
ok 155 secondPromise result
ok 156 secondPromise testValue
ok 157 thirdPromise in promise
ok 158 thirdPromise result
ok 159 thirdPromise testValue
# teardown
# setup
# enqueueAtTop and run backwards
ok 160 thirdPromise - first to run
ok 161 thirdPromise - in resolve
ok 162 secondPromise - second to run
ok 163 secondPromise - in catch
ok 164 firstPromise - third to run
ok 165 firstPromise - in then
ok 166 testing promises
# teardown
# setup
# mix enqueue and enqueueAtTop
ok 167 fourth
ok 168 fourth
ok 169 second
ok 170 secondPromise - in then
ok 171 first
ok 172 firstPromise - in catch
ok 173 third
ok 174 thirdPromise - in then
ok 175 testingPromises
# teardown
# setup
# queues handled independently
ok 176 all short operations completed before the long resolves
# teardown
# setup
# basic
ok 177 sane
# teardown
# setup
# another
ok 178 sane
# teardown
# setup
# test thali manager spies
2016-11-14 14:12:18 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
2016-11-14 14:12:18 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
2016-11-14 14:12:18 - DEBUG thaliManager: 'creating express pouchdb instance'
ok 179 expressPouchDB was called once
ok 180 expressPouchDB was called with 2 arguments
ok 181 expressPouchDB was called with 'PouchDB' as 1-st argument
ok 182 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
ok 183 PouchDB was called once
ok 184 PouchDB was called with 1 arguments
ok 185 PouchDB was called with 'dbName' as 1-st argument
ok 186 ThaliSendNotificationBasedOnReplication was called once
ok 187 ThaliSendNotificationBasedOnReplication was called with 4 arguments
ok 188 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
ok 189 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
ok 190 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
ok 191 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
ok 192 ThaliPullReplicationFromNotification was called once
ok 193 ThaliPullReplicationFromNotification was called with 4 arguments
ok 194 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
ok 195 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
ok 196 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
ok 197 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
ok 198 Salti was called once
ok 199 Salti was called with 4 arguments
ok 200 Salti was called with 'dbName' as 1-st argument
ok 201 Salti was called with 'acl' as 2-st argument
ok 202 Salti was called with 'thaliIdCallback' as 3-st argument
ok 203 Salti was called with 'options' as 4-st argument
2016-11-14 14:12:18 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-14 14:12:18 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-14 14:12:18 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-14 14:12:18 - DEBUG thaliMobileNativeWrapper: 'listening 50378'
2016-11-14 14:12:18 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:18 - DEBUG createNativeListener: 'listening 50379'
2016-11-14 14:12:18 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-14 14:12:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-14 14:12:18 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-14 14:12:18 - DEBUG thaliWifiInfrastructure: 'listening 50381'
2016-11-14 14:12:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-11-14 14:12:18 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
ok 204 ThaliMobile.start was called once
ok 205 ThaliMobile.start was called with 3 arguments
ok 206 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
ok 207 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
ok 208 ThaliMobile.start was called with 'networkType' as 3-st argument
ok 209 ThaliMobile.startListeningForAdvertisements was called once
ok 210 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
ok 211 ThaliMobile.startUpdateAdvertisingAndListening was called once
ok 212 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
ok 213 ThaliSendNotificationBasedOnReplication.prototype.start was called once
ok 214 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
ok 215 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
ok 216 ThaliPullReplicationFromNotification.prototype.start was called once
ok 217 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
ok 218 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
2016-11-14 14:12:18 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-14 14:12:18 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-14 14:12:18 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-14 14:12:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:18 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-14 14:12:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-14 14:12:18 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-14 14:12:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-14 14:12:18 - DEBUG thaliManager: 'stopping ThaliMobile'
2016-11-14 14:12:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:18 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 219 ThaliMobile.stop was called once
ok 220 ThaliMobile.stop was called with 0 arguments
ok 221 ThaliMobile.stopListeningForAdvertisements was called once
ok 222 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
ok 223 ThaliMobile.stopAdvertisingAndListening was called once
ok 224 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
ok 225 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
ok 226 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
ok 227 ThaliPullReplicationFromNotification.prototype.stop was called once
ok 228 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
# teardown
# setup
# test thali manager multiple starts and stops
2016-11-14 14:12:18 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
2016-11-14 14:12:18 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
2016-11-14 14:12:18 - DEBUG thaliManager: 'creating express pouchdb instance'
ok 229 expressPouchDB was called once
ok 230 expressPouchDB was called with 2 arguments
ok 231 expressPouchDB was called with 'PouchDB' as 1-st argument
ok 232 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
ok 233 PouchDB was called once
ok 234 PouchDB was called with 1 arguments
ok 235 PouchDB was called with 'dbName' as 1-st argument
ok 236 ThaliSendNotificationBasedOnReplication was called once
ok 237 ThaliSendNotificationBasedOnReplication was called with 4 arguments
ok 238 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
ok 239 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
ok 240 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
ok 241 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
ok 242 ThaliPullReplicationFromNotification was called once
ok 243 ThaliPullReplicationFromNotification was called with 4 arguments
ok 244 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
ok 245 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
ok 246 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
ok 247 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
ok 248 Salti was called once
ok 249 Salti was called with 4 arguments
ok 250 Salti was called with 'dbName' as 1-st argument
ok 251 Salti was called with 'acl' as 2-st argument
ok 252 Salti was called with 'thaliIdCallback' as 3-st argument
ok 253 Salti was called with 'options' as 4-st argument
2016-11-14 14:12:18 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-14 14:12:18 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-14 14:12:18 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-14 14:12:18 - DEBUG thaliMobileNativeWrapper: 'listening 50382'
2016-11-14 14:12:18 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:18 - DEBUG createNativeListener: 'listening 50383'
2016-11-14 14:12:18 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-14 14:12:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-14 14:12:18 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-14 14:12:18 - DEBUG thaliWifiInfrastructure: 'listening 50385'
2016-11-14 14:12:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-11-14 14:12:18 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
ok 254 ThaliMobile.start was called once
ok 255 ThaliMobile.start was called with 3 arguments
ok 256 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
ok 257 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
ok 258 ThaliMobile.start was called with 'networkType' as 3-st argument
ok 259 ThaliMobile.startListeningForAdvertisements was called once
ok 260 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
ok 261 ThaliMobile.startUpdateAdvertisingAndListening was called once
ok 262 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
ok 263 ThaliSendNotificationBasedOnReplication.prototype.start was called once
ok 264 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
ok 265 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
ok 266 ThaliPullReplicationFromNotification.prototype.start was called once
ok 267 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
ok 268 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
2016-11-14 14:12:18 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-14 14:12:18 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-14 14:12:18 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-14 14:12:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:18 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-14 14:12:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-14 14:12:18 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-14 14:12:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-14 14:12:18 - DEBUG thaliManager: 'stopping ThaliMobile'
2016-11-14 14:12:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:18 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 269 ThaliMobile.stop was called once
ok 270 ThaliMobile.stop was called with 0 arguments
ok 271 ThaliMobile.stopListeningForAdvertisements was called once
ok 272 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
ok 273 ThaliMobile.stopAdvertisingAndListening was called once
ok 274 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
ok 275 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
ok 276 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
ok 277 ThaliPullReplicationFromNotification.prototype.stop was called once
ok 278 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
2016-11-14 14:12:18 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-14 14:12:18 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-14 14:12:18 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-14 14:12:18 - DEBUG thaliMobileNativeWrapper: 'listening 50386'
2016-11-14 14:12:18 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:18 - DEBUG createNativeListener: 'listening 50387'
2016-11-14 14:12:18 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-14 14:12:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-14 14:12:18 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-14 14:12:18 - DEBUG thaliWifiInfrastructure: 'listening 50389'
2016-11-14 14:12:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-11-14 14:12:18 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
2016-11-14 14:12:18 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-14 14:12:18 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-14 14:12:18 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-14 14:12:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:18 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-14 14:12:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-14 14:12:18 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-14 14:12:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-14 14:12:18 - DEBUG thaliManager: 'stopping ThaliMobile'
2016-11-14 14:12:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:18 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:18 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-14 14:12:18 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-14 14:12:18 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-14 14:12:18 - DEBUG thaliMobileNativeWrapper: 'listening 50390'
2016-11-14 14:12:18 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:18 - DEBUG createNativeListener: 'listening 50391'
2016-11-14 14:12:18 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-14 14:12:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-14 14:12:18 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-14 14:12:18 - DEBUG thaliWifiInfrastructure: 'listening 50393'
2016-11-14 14:12:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-11-14 14:12:18 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
2016-11-14 14:12:18 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-14 14:12:18 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-14 14:12:18 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-14 14:12:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:18 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-14 14:12:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-14 14:12:18 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-14 14:12:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-14 14:12:18 - DEBUG thaliManager: 'stopping ThaliMobile'
2016-11-14 14:12:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:18 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:18 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-14 14:12:18 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-14 14:12:18 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-14 14:12:18 - DEBUG thaliMobileNativeWrapper: 'listening 50394'
2016-11-14 14:12:18 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:18 - DEBUG createNativeListener: 'listening 50395'
2016-11-14 14:12:18 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-14 14:12:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-14 14:12:18 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-14 14:12:18 - DEBUG thaliWifiInfrastructure: 'listening 50397'
2016-11-14 14:12:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-11-14 14:12:18 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
ok 279 ThaliMobile.start was called once
ok 280 ThaliMobile.start was called with 3 arguments
ok 281 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
ok 282 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
ok 283 ThaliMobile.start was called with 'networkType' as 3-st argument
ok 284 ThaliMobile.startListeningForAdvertisements was called once
ok 285 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
ok 286 ThaliMobile.startUpdateAdvertisingAndListening was called once
ok 287 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
ok 288 ThaliSendNotificationBasedOnReplication.prototype.start was called once
ok 289 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
ok 290 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
ok 291 ThaliPullReplicationFromNotification.prototype.start was called once
ok 292 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
ok 293 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
2016-11-14 14:12:18 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-14 14:12:18 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-14 14:12:18 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-14 14:12:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:18 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-14 14:12:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-14 14:12:18 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-14 14:12:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-14 14:12:18 - DEBUG thaliManager: 'stopping ThaliMobile'
2016-11-14 14:12:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:18 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
# setup
# #startListeningForAdvertisements should fail if start not called
ok 294 specific error should be returned
# teardown
ok 295 error should be null
ok 296 error should be null
# setup
# #startUpdateAdvertisingAndListening should fail if start not called
ok 297 specific error should be returned
# teardown
ok 298 error should be null
ok 299 error should be null
# setup
# should be able to call #stopListeningForAdvertisements many times
2016-11-14 14:12:18 - DEBUG thaliMobileNativeWrapper: 'listening 50398'
2016-11-14 14:12:18 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:18 - DEBUG createNativeListener: 'listening 50399'
ok 300 error should be null
ok 301 error should be null
ok 302 error should be null
ok 303 error should be null
# teardown
2016-11-14 14:12:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:18 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 304 error should be null
ok 305 error should be null
# setup
# should be able to call #startListeningForAdvertisements many times
2016-11-14 14:12:18 - DEBUG thaliMobileNativeWrapper: 'listening 50400'
2016-11-14 14:12:18 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:18 - DEBUG createNativeListener: 'listening 50401'
2016-11-14 14:12:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 306 error should be null
ok 307 error should be null
ok 308 error should be null
ok 309 error should be null
# teardown
2016-11-14 14:12:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-14 14:12:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-14 14:12:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:18 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 310 error should be null
ok 311 error should be null
# setup
# should be able to call #startUpdateAdvertisingAndListening many times
2016-11-14 14:12:18 - DEBUG thaliMobileNativeWrapper: 'listening 50402'
2016-11-14 14:12:18 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:18 - DEBUG createNativeListener: 'listening 50403'
2016-11-14 14:12:18 - DEBUG thaliWifiInfrastructure: 'listening 50405'
2016-11-14 14:12:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 312 error should be null
ok 313 error should be null
ok 314 error should be null
ok 315 error should be null
# teardown
2016-11-14 14:12:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-14 14:12:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-14 14:12:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:18 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 316 error should be null
ok 317 error should be null
# setup
# should be able to call #stopAdvertisingAndListening many times
2016-11-14 14:12:18 - DEBUG thaliMobileNativeWrapper: 'listening 50406'
2016-11-14 14:12:18 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:18 - DEBUG createNativeListener: 'listening 50407'
ok 318 error should be null
ok 319 error should be null
ok 320 error should be null
ok 321 error should be null
# teardown
2016-11-14 14:12:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:18 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 322 error should be null
ok 323 error should be null
# setup
# #start - Causing native or wifi to fail will cause a promise reject 
2016-11-14 14:12:18 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
ok 324 This should not cause wifi to fail
ok 325 native router should be bad
# teardown
ok 326 error should be null
ok 327 error should be null
# setup
# #start should fail if called twice in a row
2016-11-14 14:12:18 - DEBUG thaliMobileNativeWrapper: 'listening 50408'
2016-11-14 14:12:18 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:18 - DEBUG createNativeListener: 'listening 50409'
ok 328 first call should succeed
ok 329 first call should succeed
ok 330 specific error should be returned
# teardown
2016-11-14 14:12:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:18 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 331 error should be null
ok 332 error should be null
# setup
# #stop should clear watchers and change peers
2016-11-14 14:12:18 - DEBUG thaliMobileNativeWrapper: 'listening 50410'
2016-11-14 14:12:18 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:18 - DEBUG createNativeListener: 'listening 50411'
2016-11-14 14:12:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-14 14:12:18 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"urn:uuid:ad651876-5f61-4a7d-a92a-caa46a2c6a6a","peerAvailable":true,"pleaseConnect":false}'
2016-11-14 14:12:18 - DEBUG createPeerListener: 'creating new server for urn:uuid:ad651876-5f61-4a7d-a92a-caa46a2c6a6a'
2016-11-14 14:12:18 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for urn:uuid:ad651876-5f61-4a7d-a92a-caa46a2c6a6a listening on 50412'
2016-11-14 14:12:18 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-14 14:12:18 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"urn:uuid:ad651876-5f61-4a7d-a92a-caa46a2c6a6a","peerAvailable":true,"portNumber":50412}'
ok 333 Watchers have one entry for our connection type
ok 334 Peer availabilities has one entry for our connection type
2016-11-14 14:12:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"urn:uuid:ad651876-5f61-4a7d-a92a-caa46a2c6a6a","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
2016-11-14 14:12:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-14 14:12:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-14 14:12:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:18 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:18 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for urn:uuid:ad651876-5f61-4a7d-a92a-caa46a2c6a6a'
2016-11-14 14:12:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 335 No watchers
ok 336 No peers
ok 337 No watchers
ok 338 No peers
ok 339 No watchers
ok 340 No peers
# teardown
ok 341 error should be null
ok 342 error should be null
# setup
# does not emit duplicate discoveryAdvertisingStateUpdate
2016-11-14 14:12:18 - DEBUG SimpleThaliTape: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
# teardown
ok 343 error should be null
ok 344 error should be null
# setup
# does not send duplicate availability changes
ok 345 should be called once
ok 346 should not have been called more than once
# teardown
2016-11-14 14:12:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"914106bb-b19f-4423-9f1f-6a753bb35391","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 347 error should be null
ok 348 error should be null
# setup
# can get the network status
ok 349 network status should have certain non-empty properties
# teardown
ok 350 error should be null
ok 351 error should be null
# setup
# wifi peer is marked unavailable if announcements stop
2016-11-14 14:12:18 - DEBUG SimpleThaliTape: 'test was skipped, name: 'wifi peer is marked unavailable if announcements stop''
# teardown
ok 352 error should be null
ok 353 error should be null
# setup
# native peer should be removed if no availability updates were received during availability timeout
2016-11-14 14:12:18 - DEBUG thaliMobileNativeWrapper: 'listening 50413'
2016-11-14 14:12:18 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:18 - DEBUG createNativeListener: 'listening 50414'
ok 354 peer is available
2016-11-14 14:12:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"cb1df90c-c01d-40a7-80fb-943646785843","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 355 peer is not availabel because it was too silent
# teardown
2016-11-14 14:12:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:18 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 356 error should be null
ok 357 error should be null
# setup
# peerAvailabilityChanged - peer added/removed to/from cache (native)
ok 358 we have not added peer to the cache yet
ok 359 peer should be available
ok 360 cache contains native peer
ok 361 peer should be unavailable
ok 362 peer has been removed from cache
# teardown
ok 363 error should be null
ok 364 error should be null
# setup
# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
ok 365 we have not added peer to the cache yet
ok 366 peer should be available
ok 367 cache contains wifi peer
ok 368 peer should be unavailable
ok 369 peer has been removed from cache
# teardown
ok 370 error should be null
ok 371 error should be null
# setup
# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
ok 372 first peer is available
ok 373 second peer is available
ok 374 first and second peers are different
# teardown
2016-11-14 14:12:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c1da58de-bacf-4f6e-935f-635008ef75bd","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
2016-11-14 14:12:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"04489154-7082-4cc7-a914-72b1989a549a","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 375 error should be null
ok 376 error should be null
# setup
# native available - new peer is cached
ok 377 should not be in cache at start
ok 378 peer is available
# teardown
2016-11-14 14:12:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"62e60ea7-3a3e-4e84-8d06-33f8b1cff1fd","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 379 error should be null
ok 380 error should be null
# setup
# native available - peer with same port and different generation is cached (BLUETOOTH)
ok 381 peer should be available
ok 382 peer should be available
ok 383 peer should be available
# teardown
2016-11-14 14:12:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"3c03bd78-e5bf-449b-99aa-6d92aa80d80d","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 384 error should be null
ok 385 error should be null
# setup
# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
ok 386 peer should be available
ok 387 peer should be available
# teardown
2016-11-14 14:12:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"6c223844-6e8f-4d19-acad-a2211c3dffc0","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 388 error should be null
ok 389 error should be null
# setup
# native available - peer with greater generation is cached (MPCF)
2016-11-14 14:12:19 - DEBUG SimpleThaliTape: 'test was skipped, name: 'native available - peer with greater generation is cached (MPCF)''
# teardown
ok 390 error should be null
ok 391 error should be null
# setup
# native available - peer with same or older generation is ignored (MPCF)
2016-11-14 14:12:19 - DEBUG SimpleThaliTape: 'test was skipped, name: 'native available - peer with same or older generation is ignored (MPCF)''
# teardown
ok 392 error should be null
ok 393 error should be null
# setup
# native unavailable - new peer is ignored
ok 394 NOT IMPLEMENTED # SKIP
# teardown
ok 395 error should be null
ok 396 error should be null
# setup
# native unavailable - cached peer is removed
ok 397 NOT IMPLEMENTED # SKIP
# teardown
ok 398 error should be null
ok 399 error should be null
# setup
# networkChanged - fires peerAvailabilityChanged event for wifi peers
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'listening 50415'
2016-11-14 14:12:19 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:19 - DEBUG createNativeListener: 'listening 50416'
ok 400 first peer is expected to be available
ok 401 second peer is expected to be available
2016-11-14 14:12:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"a545afd3-7aff-46f9-a6f4-14b23489fc34","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 402 peer became unavailable
ok 403 it was wifi peer
# teardown
2016-11-14 14:12:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"690aade3-0ac5-495e-8b32-0e881562706e","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
2016-11-14 14:12:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:19 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 404 error should be null
ok 405 error should be null
# setup
# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'listening 50417'
2016-11-14 14:12:19 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:19 - DEBUG createNativeListener: 'listening 50418'
ok 406 first peer is expected to be available
ok 407 second peer is expected to be available
2016-11-14 14:12:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c2c6dd27-1cc5-406d-a03c-514722d82405","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 408 peer became unavailable
ok 409 it was a native peer
# teardown
2016-11-14 14:12:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"371be2bd-c9ab-4e17-bab1-73c5208d4847","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
2016-11-14 14:12:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:19 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 410 error should be null
ok 411 error should be null
# setup
# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
2016-11-14 14:12:19 - DEBUG SimpleThaliTape: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''
# teardown
ok 412 error should be null
ok 413 error should be null
# setup
# multiconnect failure - new peer is ignored (MPCF)
2016-11-14 14:12:19 - DEBUG SimpleThaliTape: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
# teardown
ok 414 error should be null
ok 415 error should be null
# setup
# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
2016-11-14 14:12:19 - DEBUG SimpleThaliTape: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
# teardown
ok 416 error should be null
ok 417 error should be null
# setup
# newAddressPort field (TCP_NATIVE)
ok 418 peer discovered first time does not have new address
ok 419 address has not been changed
ok 420 new port handled correctly
ok 421 new host handled correctly
ok 422 newAddressPort is null for unavailable peers
# teardown
ok 423 error should be null
ok 424 error should be null
# setup
# newAddressPort field (BLUETOOTH)
ok 425 peer discovered first time does not have new address
ok 426 address has not been changed
ok 427 new port handled correctly
ok 428 newAddressPort is null for unavailable peers
# teardown
ok 429 error should be null
ok 430 error should be null
# setup
# newAddressPort field (MPCF)
2016-11-14 14:12:19 - DEBUG SimpleThaliTape: 'test was skipped, name: 'newAddressPort field (MPCF)''
# teardown
ok 431 error should be null
ok 432 error should be null
# setup
# newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)
ok 433 NOT IMPLEMENTED # SKIP
# teardown
ok 434 error should be null
ok 435 error should be null
# setup
# network changes emitted correctly
2016-11-14 14:12:19 - DEBUG SimpleThaliTape: 'test was skipped, name: 'network changes emitted correctly''
# teardown
ok 436 error should be null
ok 437 error should be null
# setup
# network changes not emitted in stopped state
ok 438 event was not emitted
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-14 14:12:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-14 14:12:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
# teardown
ok 439 error should be null
ok 440 error should be null
# setup
# calls correct starts when network changes
2016-11-14 14:12:19 - DEBUG SimpleThaliTape: 'test was skipped, name: 'calls correct starts when network changes''
# teardown
ok 441 error should be null
ok 442 error should be null
# setup
# We properly fire peer unavailable and then available when connection fails
2016-11-14 14:12:19 - DEBUG SimpleThaliTape: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails''
# teardown
ok 443 error should be null
ok 444 error should be null
# setup
# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'listening 50419'
2016-11-14 14:12:19 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:19 - DEBUG createNativeListener: 'listening 50420'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-14 14:12:19 - DEBUG createPeerListener: 'creating new server for 4332a4ad-c7f8-4321-ab91-3f96c1fa1bb4'
2016-11-14 14:12:19 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for 4332a4ad-c7f8-4321-ab91-3f96c1fa1bb4 listening on 50421'
2016-11-14 14:12:19 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 445 We should have connected
2016-11-14 14:12:19 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - 4332a4ad-c7f8-4321-ab91-3f96c1fa1bb4 - 0 - got a new incoming connection'
2016-11-14 14:12:19 - DEBUG createPeerListener: 'Issuing callNative for 4332a4ad-c7f8-4321-ab91-3f96c1fa1bb4'
2016-11-14 14:12:19 - WARN createPeerListener: 'callNative for 4332a4ad-c7f8-4321-ab91-3f96c1fa1bb4 failed with Connection could not be established'
2016-11-14 14:12:19 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - 4332a4ad-c7f8-4321-ab91-3f96c1fa1bb4 - 0 - finish'
2016-11-14 14:12:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:19 - DEBUG createPeerListener: 'We are emitting failedConnection with error Error: Connection could not be established and peerIdentifier 4332a4ad-c7f8-4321-ab91-3f96c1fa1bb4'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"4332a4ad-c7f8-4321-ab91-3f96c1fa1bb4","peerAvailable":false,"portNumber":null,"recreated":true}'
ok 446 Failed on right peer
2016-11-14 14:12:19 - DEBUG createPeerListener: 'Will try to recreate server for 4332a4ad-c7f8-4321-ab91-3f96c1fa1bb4'
2016-11-14 14:12:19 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for 4332a4ad-c7f8-4321-ab91-3f96c1fa1bb4'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"4332a4ad-c7f8-4321-ab91-3f96c1fa1bb4","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2016-11-14 14:12:19 - DEBUG createPeerListener: 'creating new server for 4332a4ad-c7f8-4321-ab91-3f96c1fa1bb4'
2016-11-14 14:12:19 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for 4332a4ad-c7f8-4321-ab91-3f96c1fa1bb4 listening on 50423'
2016-11-14 14:12:19 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-14 14:12:19 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier 4332a4ad-c7f8-4321-ab91-3f96c1fa1bb4 and portNumber 50423'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'listenerRecreatedAfterFailureHandler - We are emitting nonTCPPeerAvailabilityChangedEvent with peerIdentifier 4332a4ad-c7f8-4321-ab91-3f96c1fa1bb4, generation undefined, and portNumber 50423'
ok 447 Peer still matches
ok 448 We got the connection error
2016-11-14 14:12:19 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - 4332a4ad-c7f8-4321-ab91-3f96c1fa1bb4 - 0 - close'
# teardown
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-14 14:12:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-14 14:12:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:19 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:19 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for 4332a4ad-c7f8-4321-ab91-3f96c1fa1bb4'
2016-11-14 14:12:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 449 error should be null
ok 450 error should be null
# setup
# Can call start/stopListeningForAdvertisements
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-14 14:12:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-14 14:12:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 451 Can call startListeningForAdvertisements without error
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-14 14:12:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 452 Can call stopListeningForAdvertisements without error
# teardown
ok 453 Should be able to call stopListeningForAdvertisements in teardown
ok 454 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Calling startListeningForAdvertisements twice is NOT an error
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-14 14:12:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-14 14:12:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 455 Can call startListeningForAdvertisements without error
ok 456 Can call startListeningForAdvertisements twice without error
# teardown
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-14 14:12:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 457 Should be able to call stopListeningForAdvertisements in teardown
ok 458 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Calling stopListeningForAdvertisements without calling start is NOT an error
ok 459 Can call stopListeningForAdvertisements without error
ok 460 Can call stopListeningForAdvertisements without error
# teardown
ok 461 Should be able to call stopListeningForAdvertisements in teardown
ok 462 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Can call start/stopUpdateAdvertisingAndListening
2016-11-14 14:12:19 - DEBUG thaliWifiInfrastructure: 'listening 50425'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2016-11-14 14:12:19 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-14 14:12:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 463 Can call startUpdateAdvertisingAndListening without error
2016-11-14 14:12:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-14 14:12:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 464 Can call stopAdvertisingAndListening without error
# teardown
ok 465 Should be able to call stopListeningForAdvertisements in teardown
ok 466 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Calling startUpdateAdvertisingAndListening twice is NOT an error
2016-11-14 14:12:19 - DEBUG thaliWifiInfrastructure: 'listening 50427'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2016-11-14 14:12:19 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-14 14:12:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 467 Can call startUpdateAdvertisingAndListening without error
ok 468 Can call startUpdateAdvertisingAndListening twice without error
# teardown
ok 469 Should be able to call stopListeningForAdvertisements in teardown
2016-11-14 14:12:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-14 14:12:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 470 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
ok 471 Can call startUpdateAdvertisingAndListening without error
ok 472 Can call stopAdvertisingAndListening without error
# teardown
ok 473 Should be able to call stopListeningForAdvertisements in teardown
ok 474 Should be able to call stopAdvertisingAndListening in teardown
# setup
# cannot call connect when start listening for advertisements is not active
ok 475 got right error
# teardown
ok 476 Should be able to call stopListeningForAdvertisements in teardown
ok 477 Should be able to call stopAdvertisingAndListening in teardown
# setup
# #startListeningForAdvertisements should fail if start not called
ok 478 specific error should be returned
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-14 14:12:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 479 must be stopped
# setup
# #startUpdateAdvertisingAndListening should fail if start not called
ok 480 specific error should be returned
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-14 14:12:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 481 must be stopped
# setup
# should be able to call #stopListeningForAdvertisements many times
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'listening 50428'
2016-11-14 14:12:19 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:19 - DEBUG createNativeListener: 'listening 50429'
ok 482 no errors
ok 483 still no errors
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-14 14:12:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
2016-11-14 14:12:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:19 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 484 must be stopped
# setup
# should be able to call #startListeningForAdvertisements many times
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'listening 50430'
2016-11-14 14:12:19 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:19 - DEBUG createNativeListener: 'listening 50431'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-14 14:12:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-14 14:12:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 485 no errors
ok 486 still no errors
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-14 14:12:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-14 14:12:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-14 14:12:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:19 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 487 must be stopped
# setup
# should be able to call #startUpdateAdvertisingAndListening many times
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'listening 50432'
2016-11-14 14:12:19 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:19 - DEBUG createNativeListener: 'listening 50433'
2016-11-14 14:12:19 - DEBUG thaliWifiInfrastructure: 'listening 50435'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2016-11-14 14:12:19 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-14 14:12:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 488 no errors
ok 489 still no errors
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-14 14:12:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
2016-11-14 14:12:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-14 14:12:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-14 14:12:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:19 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 490 must be stopped
# setup
# should be able to call #stopAdvertisingAndListening many times
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'listening 50436'
2016-11-14 14:12:19 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:19 - DEBUG createNativeListener: 'listening 50437'
ok 491 no errors
ok 492 still no errors
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-14 14:12:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
2016-11-14 14:12:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:19 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 493 must be stopped
# setup
# can get the network status before starting
ok 494 network status should have certain non-empty properties
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-14 14:12:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 495 must be stopped
# setup
# error returned with bad router
2016-11-14 14:12:19 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 496 specific error expected
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-14 14:12:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 497 must be stopped
# setup
# all services are stopped when we call stop
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'listening 50438'
2016-11-14 14:12:19 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:19 - DEBUG createNativeListener: 'listening 50439'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-14 14:12:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-14 14:12:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-14 14:12:19 - DEBUG thaliWifiInfrastructure: 'listening 50441'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-11-14 14:12:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-14 14:12:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-14 14:12:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:12:19 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 498 connection to servers manager should succeed after starting
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
ok 499 connection to router server should succeed after starting
2016-11-14 14:12:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-14 14:12:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:12:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-14 14:12:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-14 14:12:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-14 14:12:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-14 14:12:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:19 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 500 is stopped after calling stop
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-14 14:12:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
ok 501 connection to servers manager should fail after stopping
ok 502 connection to router server should fail after stopping
# teardown
ok 503 must be stopped
# setup
# make sure terminateConnection is properly hooked up
ok 504 called with right arguments
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-14 14:12:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 505 must be stopped
# setup
# make sure terminateListener is properly hooked up
ok 506 called with right arguments
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-14 14:12:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 507 must be stopped
# setup
# make sure we actually call kill connections properly
ok 508 specific error expected
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-14 14:12:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 509 must be stopped
# setup
# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'listening 50446'
2016-11-14 14:12:19 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:19 - DEBUG createNativeListener: 'listening 50447'
2016-11-14 14:12:19 - INFO thaliMobileNativeWrapper: 'routerPortConnectionFailed - {"routerPort":50446,"error":{}}'
2016-11-14 14:12:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:19 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 510 failure reason is as expected
ok 511 error description is as expected
ok 512 must be stopped
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-14 14:12:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 513 must be stopped
# setup
# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'listening 50448'
2016-11-14 14:12:19 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:19 - DEBUG createNativeListener: 'listening 50449'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"some-identifier","peerAvailable":false,"portNumber":null}'
ok 514 peerIdentifier matches
ok 515 error description matches
ok 516 connection type is tcp
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"some-identifier","peerAvailable":false,"generation":null,"portNumber":null}'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-14 14:12:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
2016-11-14 14:12:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:19 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 517 must be stopped
# setup
# we successfully receive and replay discoveryAdvertisingStateUpdate
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'listening 50450'
2016-11-14 14:12:19 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:19 - DEBUG createNativeListener: 'listening 50451'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-14 14:12:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-14 14:12:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 518 discoveryActive matches
ok 519 advertisingActive matches
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-14 14:12:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 520 discoveryActive matches
ok 521 advertisingActive matches
2016-11-14 14:12:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:19 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'listening 50452'
2016-11-14 14:12:19 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:19 - DEBUG createNativeListener: 'listening 50453'
2016-11-14 14:12:19 - DEBUG thaliWifiInfrastructure: 'listening 50455'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2016-11-14 14:12:19 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-14 14:12:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 522 discoveryActive matches
ok 523 advertisingActive matches
2016-11-14 14:12:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-14 14:12:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 524 discoveryActive matches
ok 525 advertisingActive matches
2016-11-14 14:12:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:19 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'listening 50456'
2016-11-14 14:12:19 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:19 - DEBUG createNativeListener: 'listening 50457'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-14 14:12:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-14 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
2016-11-14 14:12:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:19 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 526 must be stopped
# setup
# Test BEACONS_RETRIEVED_AND_PARSED locally
ok 527 peerIdentifier should be identifier
ok 528 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 529 good beacon
ok 530 good preAmble
ok 531 public keys match!
ok 532 must return null after successful call
ok 533 Once start returns the action should be in KILLED state
# teardown
2016-11-14 14:12:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test HTTP_BAD_RESPONSE locally
ok 534 Response should be HTTP_BAD_RESPONSE
ok 535 must return null after successful call
# teardown
2016-11-14 14:12:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test NETWORK_PROBLEM locally
ok 536 Response should be NETWORK_PROBLEM
ok 537 reject reason should be: Could not establish TCP connection
# teardown
2016-11-14 14:12:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Call the start two times
ok 538 Call start once
ok 539 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 540 must return null after successful call.
# teardown
2016-11-14 14:12:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Call the kill before calling the start
ok 541 Should be Killed
ok 542 Start after killed
# teardown
2016-11-14 14:12:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Call the kill immediately after the start
ok 543 Should be KILLED
ok 544 must return null after successful kill
# teardown
2016-11-14 14:12:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Call the kill while waiting a response from the server
ok 545 Should be KILLED
ok 546 must return null after successful kill
# teardown
2016-11-14 14:12:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test to exceed the max content size locally
ok 547 HTTP_BAD_RESPONSE should be response when content size is exceeded
ok 548 must return null after successful call
# teardown
2016-11-14 14:12:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Close the server socket while the client is waiting a response from the server. Local test.
2016-11-14 14:12:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 549 Should be NETWORK_PROBLEM caused closing server socket
ok 550 Should be Could not establish TCP connection
# teardown
# setup
# Close the client socket while the client is waiting a response from the server. Local test.
ok 551 Should be NETWORK_PROBLEM caused closing client socket
ok 552 Should be Could not establish TCP connection
# teardown
2016-11-14 14:12:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #generatePreambleAndBeacons bad args
ok 553 publicKeysToNotify cannot be null
ok 554 ecdh for local device cannot be null
ok 555 milliseconds cannot be less than 0
ok 556 milliseconds cannot be 0
ok 557 milliseconds cannot be greater than one_day
# teardown
# setup
# #generatePreambleAndBeacons empty keys to notify
ok 558 should be equal
# teardown
# setup
# #generatePreambleAndBeacons multiple keys to notify
ok 559 should be equal
ok 560 should be equal
ok 561 (unnamed assert)
ok 562 should be equal
# teardown
# setup
# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
ok 563 should throw
# teardown
# setup
# #parseBeacons invalid expiration in beaconStreamWithPreAmble
ok 564 Preamble expiration must be a 64 bit integer
# teardown
# setup
# #parseBeacons expiration out of range lower
ok 565 Expiration out of range
# teardown
# setup
# #parseBeacons expiration out of range lower
ok 566 Expiration out of range
# teardown
# setup
# #parseBeacons no beacons returns null
ok 567 should be equal
# teardown
# setup
# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
ok 568 Malformed encrypted beacon key ID
# teardown
# setup
# #parseBeacons addressBookCallback fails decrypt
ok 569 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns no matches
ok 570 should be equal
ok 571 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns spurious match
ok 572 should be equal
ok 573 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns public key
ok 574 right number of calls to address book
ok 575 good preAmble
ok 576 good unencryptedKeyId
ok 577 good beacon
# teardown
# setup
# validate generatePskIdentityField
ok 578 decoded buffers match
# teardown
# setup
# validate generatePskSecret
ok 579 secrets match
# teardown
# setup
# validate generatePskSecrets
ok 580 Matching numbers
ok 581 We have an entry!
ok 582 keys match
ok 583 secrets match
ok 584 We have an entry!
ok 585 keys match
ok 586 secrets match
ok 587 We have an entry!
ok 588 keys match
ok 589 secrets match
# teardown
# setup
# validate generateBeaconStreamAndSecrets
ok 590 Streams have same length
ok 591 matching size
ok 592 keys match
ok 593 secrets match
# teardown
# setup
# Add two Peers.
ok 594 should be equal
ok 595 should be equal
ok 596 should be equal
ok 597 should be equal
ok 598 should be equal
# teardown
2016-11-14 14:12:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# TCP_NATIVE peer loses DNS
ok 599 should be equal
ok 600 should be equal
# teardown
2016-11-14 14:12:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Received beacons with no values for us
ok 601 entry exists
ok 602 entry is resolved
# teardown
2016-11-14 14:12:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Notification action killed with a superseded
ok 603 Action should be killed
ok 604 should be equal
# teardown
2016-11-14 14:12:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Resolves an action locally
ok 605 Host address must match
ok 606 suggestedTCPTimeout must match
ok 607 connectionType must match
ok 608 portNumber must match
ok 609 peerIDs must match
# teardown
2016-11-14 14:12:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Resolves an action locally using ThaliPeerPoolDefault
ok 610 Host address must match
ok 611 suggestedTCPTimeout must match
ok 612 connectionType must match
ok 613 portNumber must match
ok 614 peerIds must match
# teardown
2016-11-14 14:12:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Action fails because of a bad hostname.
2016-11-14 14:12:25 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 615 action should be resolved with NETWORK_PROBLEM error
2016-11-14 14:12:25 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 616 action should be resolved with NETWORK_PROBLEM error
2016-11-14 14:12:25 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 617 action should be resolved with NETWORK_PROBLEM error
2016-11-14 14:12:26 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 618 action should be resolved with NETWORK_PROBLEM error
ok 619 correct number of requests
ok 620 correct number of failures
ok 621 correct final peer state
# teardown
2016-11-14 14:12:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# hostaddress is removed when the action is running. 
2016-11-14 14:12:28 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 622 should be equal
# teardown
2016-11-14 14:12:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Client to server request locally
ok 623 secrets are equal
ok 624 Public key matches with the server key
ok 625 Host address must match
ok 626 suggestedTCPTimeout must match
ok 627 connectionType must match
ok 628 portNumber must match
# teardown
2016-11-14 14:12:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test ThaliPskMapCache clean and expiration
ok 629 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
ok 630 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
ok 631 All entries should be expired after 1 second
# teardown
2016-11-14 14:12:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test ThaliPskMapCache getSecret and getPublic
ok 632 All keys need to be available in the cache
ok 633 All entries should be expired after 1 second
# teardown
2016-11-14 14:12:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test ThaliPskMapCache multiple entries
ok 634 Size of the cache should be 2
ok 635 Cache doesn't contain dictionary1
ok 636 Size of the cache should be 1
ok 637 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
2016-11-14 14:12:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Start and stop ThaliNotificationServer
ok 638 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
ok 639 ThaliMobile.StopAdvertisingAndListeningshould be called once
# teardown
2016-11-14 14:12:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Pass an empty array to ThaliNotificationServer.start
ok 640 StartUpdateAdvertisingAndListening should not be called
ok 641 ThaliMobile.StopAdvertisingAndListening should be called once
ok 642 no error
ok 643 should be 204
# teardown
2016-11-14 14:12:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Pass a string to ThaliNotificationServer.start
ok 644 StartUpdateAdvertisingAndListening should not be called
# teardown
2016-11-14 14:12:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Pass an empty parameter to ThaliNotificationServer.start
ok 645 StartUpdateAdvertisingAndListening should not be called
# teardown
2016-11-14 14:12:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make an HTTP request to /NotificationBeacons
ok 646 no error
ok 647 should be 200
ok 648 should be equal
ok 649 should be equal
ok 650 (unnamed assert)
ok 651 no error
ok 652 should be 204
# teardown
2016-11-14 14:12:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make an HTTP request to /NotificationBeacons (no keys)
ok 653 error should be null
ok 654 should be 204
# teardown
2016-11-14 14:12:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make an HTTP request to /NotificationBeaconsbefore calling start
ok 655 should be 404
# teardown
2016-11-14 14:12:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #testThaliPeerAction - test getters
ok 656 getPeerIdentifier
ok 657 getConnectionType
ok 658 getActionType
ok 659 getActionState
ok 660 getPskIdentity
ok 661 getPskKey
# teardown
# setup
# #testThaliPeerAction - start and kill
ok 662 initial state
ok 663 after start
2016-11-14 14:12:33 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 664 after kill
# teardown
# setup
# #testThaliPeerAction - double start
ok 665 should be equal
# teardown
# setup
# #testThaliPeerAction - start after kill
2016-11-14 14:12:33 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 666 clean kill
ok 667 should be equal
# teardown
# setup
# #testThaliPeerAction - make sure ids are unique
ok 668 should not be equal
# teardown
# setup
# #testThaliPeerAction - check that forever agent can be destroyed
ok 669 forever agent should have it's own destroy method
ok 670 agent's destroy should be called
ok 671 agent's destroy should not be called again
ok 672 agent is destroyed
# teardown
# setup
# Test PeerConnectionInformation basics
ok 673 connection type works
ok 674 getHostAddress works
ok 675 getPortNumber works
ok 676 getSuggestedTCPTimeout works
# teardown
# setup
# Test PeerDictionary basic functionality
ok 677 Entry counter must be 1
ok 678 Size must be 1
ok 679 Entry counter must be 2
ok 680 Size must be 2
ok 681 Entry2 should not be found
ok 682 Size must be 1
ok 683 Size must be 0
# teardown
# setup
# Test PeerDictionary with multiple entries.
ok 684 Size must be100
ok 685 Entries between 20 and MAXSIZE + 20 should exist
ok 686 WAITING state entry should not be removed
# teardown
# setup
# RESOLVED entries are removed before WAITING state entry.
ok 687 Entries between 6 and MAXSIZE + 4 should exist
ok 688 Size should be MAXSIZE
ok 689 Size should be MAXSIZE+6
# teardown
# setup
# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
ok 690 WAITING state entry should not be removed
ok 691 Waiting entries between 6 and MAXSIZE + 4 should exist
ok 692 Size should be MAXSIZE
ok 693 entryCounter should be MAXSIZE+6
# teardown
# setup
# When CONTROLLED_BY_POOL entry is removed and kill is called.
ok 694 Kill should be called once
ok 695 Size should be 100
# teardown
# setup
# #ThaliPeerPoolDefault - single action
ok 696 is an agent
ok 697 enqueue is fine
ok 698 Everything should be off the queue
# teardown
# setup
# #ThaliPeerPoolDefault - multiple actions
ok 699 is an agent
ok 700 first enqueue is fine
ok 701 is an agent
ok 702 second enqueue is fine
ok 703 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 704 Queue is empty
# teardown
# setup
# #ThaliPeerPoolDefault - PSK Pool works
ok 705 is an agent
ok 706 good enqueue
ok 707 Identity should match
2016-11-14 14:12:33 - DEBUG testUtils: 'Got response data'
2016-11-14 14:12:33 - DEBUG testUtils: 'Got end'
ok 708 Got expected response
ok 709 Got psk call back
# teardown
2016-11-14 14:12:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #ThaliPeerPoolDefault - stop
ok 710 is an agent
ok 711 enqueue worked
ok 712 is an agent
ok 713 enqueue 2 worked
ok 714 enqueue is not available when stopped
ok 715 start action is killed
ok 716 killed action is still killed
ok 717 inQueue is empty
# teardown
# setup
# #ThaliPeerPoolInterface - make sure that start verifies queue length
ok 718 good start
ok 719 good enqueue
ok 720 queue is not empty
# teardown
# setup
# #ThaliPeerPoolInterface - bad enqueues
ok 721 null arg
ok 722 wrong arg type
ok 723 wrong arg type
# teardown
# setup
# #ThaliPeerPoolInterface - do not allow same object type
ok 724 good enqueue
ok 725 already enqueued
# teardown
# setup
# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
ok 726 good enqueue
ok 727 2nd good enqueue
ok 728 we are in the pool
ok 729 We are out of the pool
ok 730 Action was killed
ok 731 The original kill was called too
ok 732 second item is still in queue
# teardown
# setup
# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
ok 733 good enqueue
ok 734 first kill
ok 735 second NOOP kill
# teardown
# setup
# #ThaliPeerPoolInterface - make sure that stop removes all actions
ok 736 1st good enqueue
ok 737 2nd good enqueue
ok 738 1st action is in the pool
ok 739 2nd action is in the pool
ok 740 1st action is out of the pool
ok 741 2st action is out of the pool
ok 742 pool is empty
# teardown
# setup
# We reject unrecognized connection type
2016-11-14 14:12:33 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 743 Got right error
ok 744 Start should not be called
ok 745 Kill should have been called at least once
# teardown
# setup
# We reject unrecognized action type
2016-11-14 14:12:33 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2016-11-14 14:12:33 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
ok 746 Got right error
ok 747 Start should not be called
ok 748 Kill should have been called at least once
# teardown
# setup
# One action on bluetooth
2016-11-14 14:12:33 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 749 Got null
2016-11-14 14:12:33 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 607, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
ok 750 is an agent
2016-11-14 14:12:33 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 607, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
ok 751 Got killed at least once
# teardown
# setup
# Two notification actions
2016-11-14 14:12:33 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 752 Got Null
ok 753 Got another null
2016-11-14 14:12:33 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 608, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
ok 754 is an agent
2016-11-14 14:12:33 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 608, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
2016-11-14 14:12:33 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 609, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
ok 755 is an agent
ok 756 Action 1 killed at least once
2016-11-14 14:12:33 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 609, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
ok 757 Action 1 went first
ok 758 Action 2 killed at least once
# teardown
# setup
# replicateThroughProblems
2016-11-14 14:12:33 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
2016-11-14 14:12:33 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
2016-11-14 14:12:33 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
ok 759 should have gotten null
2016-11-14 14:12:33 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
2016-11-14 14:12:33 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
ok 760 Should have stopped nicely
2016-11-14 14:12:33 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
2016-11-14 14:12:33 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
ok 761 Still looking for null
2016-11-14 14:12:33 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
2016-11-14 14:12:33 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
2016-11-14 14:12:33 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
2016-11-14 14:12:33 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
2016-11-14 14:12:33 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
2016-11-14 14:12:33 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
ok 762 Yup, another null
ok 763 We cloned!
# teardown
# setup
# Replication goes first
2016-11-14 14:12:33 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 764 Null 1
ok 765 (unnamed assert)
2016-11-14 14:12:33 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 610, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
ok 766 is an agent
ok 767 Null 3
2016-11-14 14:12:33 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 610, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
2016-11-14 14:12:33 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 611, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
ok 768 is an agent
ok 769 Replication not yet called
ok 770 Notification 2 not yet called
2016-11-14 14:12:33 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 611, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
2016-11-14 14:12:33 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
2016-11-14 14:12:33 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 612, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
ok 771 is an agent
ok 772 Notification went first
ok 773 Notification 2 not called yet
2016-11-14 14:12:33 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 612, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
ok 774 Notification finished
ok 775 Replication finished
# teardown
# setup
# wifi allows many parallel non-replication actions
2016-11-14 14:12:33 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2016-11-14 14:12:33 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 613, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
ok 776 is an agent
ok 777 First null
2016-11-14 14:12:33 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 614, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
ok 778 is an agent
ok 779 Second null
2016-11-14 14:12:33 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 614, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
truetruefalsetrue
2016-11-14 14:12:33 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 613, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
truetruetruetrue
# teardown
# setup
# wifi allows no more than 2 simultaneous replication actions for same peerID
2016-11-14 14:12:33 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2016-11-14 14:12:33 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 615, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
ok 780 is an agent
ok 781 First null
2016-11-14 14:12:33 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 616, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
ok 782 is an agent
ok 783 second null
ok 784 third null
2016-11-14 14:12:33 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 615, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
2016-11-14 14:12:33 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 616, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
2016-11-14 14:12:33 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
2016-11-14 14:12:33 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
# teardown
# setup
# Make sure peerDictionaryKey is reasonable
ok 785 equal keys
ok 786 not equal connection type
ok 787 same connection type, different buffer
# teardown
# setup
# Make sure start works
2016-11-14 14:12:33 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 788 First start and on called correctly
# teardown
# setup
# Make sure stop works
ok 789 second cleared dictionary
2016-11-14 14:12:33 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 790 First start and on called correctly
ok 791 First stop and removeListener called correctly
ok 792 first action kill called
ok 793 second action kill called
ok 794 first cleared dictionary
ok 795 first cleared pool
ok 796 second cleared dictionary
ok 797 second cleared pool
# teardown
# setup
# Simple peer event
2016-11-14 14:12:33 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 798 listener has been set
ok 799 peer dictionary has expected number of entries
ok 800 Dictionary and pool have same action
ok 801 ads match
ok 802 PouchDB matches
ok 803 DB Names match
ok 804 public keys match
ok 805 peer dictionary has expected number of entries
ok 806 Dictionary and pool have same action
ok 807 ads match
ok 808 PouchDB matches
ok 809 DB Names match
ok 810 public keys match
2016-11-14 14:12:33 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
ok 811 start called once
ok 812 One entry left
ok 813 Dictionary and pool have same action
ok 814 Start never called
ok 815 Kill called once
ok 816 no entries left
ok 817 Third action is dead
ok 818 peer dictionary has expected number of entries
ok 819 Dictionary and pool have same action
ok 820 ads match
ok 821 PouchDB matches
ok 822 DB Names match
ok 823 public keys match
# teardown
# setup
# Server is not there
2016-11-14 14:12:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:33 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
2016-11-14 14:12:33 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: connect ECONNREFUSED  and it caused us to complete'
ok 824 right error
# teardown
2016-11-14 14:12:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Server accepts & closes connection
2016-11-14 14:12:33 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
2016-11-14 14:12:33 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
ok 825 right error
# teardown
2016-11-14 14:12:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Server always returns 500
2016-11-14 14:12:33 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
2016-11-14 14:12:33 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
ok 826 Got error as expected
# teardown
2016-11-14 14:12:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Server always returns 401
2016-11-14 14:12:33 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
2016-11-14 14:12:33 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
ok 827 Got error as expected
# teardown
2016-11-14 14:12:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Server always returns 403
2016-11-14 14:12:33 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
2016-11-14 14:12:33 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
ok 828 Got error as expected
# teardown
2016-11-14 14:12:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make sure docs replicate
2016-11-14 14:12:34 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
2016-11-14 14:12:34 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
2016-11-14 14:12:34 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
ok 829 should be equal
ok 830 All tests passed!
# teardown
2016-11-14 14:12:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Do nothing and make sure we time out
2016-11-14 14:12:34 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
2016-11-14 14:12:36 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2016-11-14 14:12:36 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
ok 831 action should be killed
ok 832 Error should be timed out
ok 833 No doc found
# teardown
2016-11-14 14:12:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Do something and make sure we time out
2016-11-14 14:12:36 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
2016-11-14 14:12:36 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
ok 834 should be equal
2016-11-14 14:12:38 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2016-11-14 14:12:38 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
ok 835 action should be killed
ok 836 Error should be timed out
# teardown
2016-11-14 14:12:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Start replicating and then catch error when server goes
ok 837 socket hung up
# teardown
2016-11-14 14:12:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make sure clone works
ok 838 same getPeerAdvertisesDataForUs
ok 839 Same pouchdB
ok 840 same dbName
ok 841 Same public key
# teardown
# setup
# compareBufferArrays
ok 842 should throw
ok 843 should throw
ok 844 (unnamed assert)
ok 845 (unnamed assert)
ok 846 (unnamed assert)
ok 847 (unnamed assert)
ok 848 (unnamed assert)
# teardown
# setup
# Call start twice and get error
ok 849 should throw
# teardown
# setup
# Start and make sure it runs
# teardown
# setup
# Make sure getTimeWhenRun is right after start
ok 850 (unnamed assert)
# teardown
# setup
# Make sure getTimeWhenRun is -1 after function is called
ok 851 should be equal
# teardown
# setup
# Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
ok 852 should be equal
ok 853 should be equal
ok 854 should throw
# teardown
# setup
# Test TransientState
ok 855 should throw
ok 856 should throw
ok 857 should be equal
ok 858 should be equal
ok 859 should be equal
ok 860 should be equal
ok 861 (unnamed assert)
ok 862 (unnamed assert)
# teardown
# setup
# No peers and empty database
ok 863 verify failed
ok 864 constructor called once
ok 865 constructor called with right args
ok 866 match start arg
ok 867 start called once
ok 868 stop called once
ok 869 stop after start
# teardown
# setup
# One peer and empty DB
ok 870 verify failed
ok 871 constructor called once
ok 872 constructor called with right args
ok 873 match start arg
ok 874 start called once
ok 875 stop called once
ok 876 stop after start
2016-11-14 14:12:38 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# One peer with _Local set behind current seq
ok 877 verify failed
ok 878 constructor called once
ok 879 constructor called with right args
ok 880 match start arg
ok 881 start called once
ok 882 stop called once
ok 883 stop after start
2016-11-14 14:12:39 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# One peer with _Local set equal to current seq
ok 884 verify failed
ok 885 constructor called once
ok 886 constructor called with right args
ok 887 match start arg
ok 888 start called once
ok 889 stop called once
ok 890 stop after start
2016-11-14 14:12:39 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# One peer with _Local set ahead of current seq (and no this should not happen)
ok 891 verify failed
ok 892 constructor called once
ok 893 constructor called with right args
ok 894 match start arg
ok 895 start called once
ok 896 stop called once
ok 897 stop after start
2016-11-14 14:12:39 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# Three peers, one not in DB, one behind and one ahead
ok 898 verify failed
ok 899 constructor called once
ok 900 constructor called with right args
ok 901 match start arg
ok 902 start called once
ok 903 stop called once
ok 904 stop after start
2016-11-14 14:12:39 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# More than maximum peers, make sure we only send maximum allowed
ok 905 verify failed
ok 906 constructor called once
ok 907 constructor called with right args
ok 908 match start arg
ok 909 start called once
ok 910 stop called once
ok 911 stop after start
2016-11-14 14:12:39 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# two peers with empty DB, update the doc
2016-11-14 14:12:39 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 912 verify failed
ok 913 constructor called once
ok 914 constructor called with right args
ok 915 last start before stop
ok 916 empty first start
ok 917 full second start
ok 918 only 2 timers
2016-11-14 14:12:39 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# add doc and make sure tokens refresh when they expire
2016-11-14 14:12:39 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
2016-11-14 14:12:39 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 919 verify failed
ok 920 constructor called once
ok 921 constructor called with right args
ok 922 start before stop
ok 923 We got at least 3 calls to start
ok 924 at least 3
ok 925 default 1
ok 926 1 run
ok 927 default 2
ok 928 2 run
ok 929 default 3
2016-11-14 14:12:39 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# start and stop and start and stop
ok 930 start out null
ok 931 back to null
2016-11-14 14:12:39 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 932 still null
ok 933 verify failed
ok 934 constructor called once
ok 935 constructor called with right args
ok 936 first start before first stop
ok 937 first stop before second start
ok 938 second start before second stop
2016-11-14 14:12:39 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# two identical starts in a row
ok 939 verify failed
ok 940 constructor called once
ok 941 constructor called with right args
ok 942 (unnamed assert)
2016-11-14 14:12:39 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# two different starts in a row
2016-11-14 14:12:39 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 943 verify failed
ok 944 constructor called once
ok 945 constructor called with right args
ok 946 (unnamed assert)
ok 947 (unnamed assert)
# teardown
# setup
# two stops and a start and two stops
ok 948 verify failed
ok 949 constructor called once
ok 950 constructor called with right args
ok 951 start before stop
2016-11-14 14:12:39 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# we properly enqueue requests so no then needed
2016-11-14 14:12:39 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 952 verify failed
ok 953 constructor called once
ok 954 constructor called with right args
ok 955 start before stop
# teardown
# setup
# test calculateSeqPointKeyId
ok 956 should be equal
ok 957 should be equal
# teardown
# setup
# can create servers manager
ok 958 serversManager must not be null
ok 959 serversManager must be an object
# teardown
# setup
# calling stop without start causes error
ok 960 We need to call start first
# teardown
# setup
# can start/stop servers manager
2016-11-14 14:12:39 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:39 - DEBUG createNativeListener: 'listening 50578'
ok 961 port must be in range
# teardown
2016-11-14 14:12:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:39 - DEBUG createNativeListener: 'Native Server - close'
# setup
# starting twice resolves with listening port
2016-11-14 14:12:39 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:39 - DEBUG createNativeListener: 'listening 50579'
ok 962 second start should return same port
# teardown
2016-11-14 14:12:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:39 - DEBUG createNativeListener: 'Native Server - close'
# setup
# terminateIncomingConnection will terminate a connection
2016-11-14 14:12:39 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:39 - DEBUG createNativeListener: 'listening 50581'
2016-11-14 14:12:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:12:39 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 963 we should be connected
2016-11-14 14:12:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 964 now we are disconnected
2016-11-14 14:12:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
2016-11-14 14:12:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:39 - DEBUG createNativeListener: 'Native Server - close'
# setup
# terminate an Outgoing connection
2016-11-14 14:12:39 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
ok 965 Passed bogus id
2016-11-14 14:12:39 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
ok 966 Passed good id but bogus port
2016-11-14 14:12:39 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
ok 967 Passed right context
ok 968 Right server
ok 969 No error should be set
ok 970 Retry should be false
ok 971 We called close server
# teardown
# setup
# Correctly parses/stringifies USN
ok 972 correctly parses USN string
ok 973 throws if usn has invalid prefix
ok 974 throws if usn has invalid identifier format
ok 975 throws if usn has invalid generation
ok 976 correctly stringifies peer
# teardown
2016-11-14 14:12:39 - DEBUG SimpleThaliTape: 'all unit tests succeeded, platformName: 'android''
2016-11-14 14:12:39 - DEBUG SimpleThaliTape: 'skipped tests: '["does not emit duplicate discoveryAdvertisingStateUpdate","wifi peer is marked unavailable if announcements stop","native available - peer with greater generation is cached (MPCF)","native available - peer with same or older generation is ignored (MPCF)","networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)","multiconnect failure - new peer is ignored (MPCF)","multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)","newAddressPort field (MPCF)","network changes emitted correctly","calls correct starts when network changes","We properly fire peer unavailable and then available when connection fails"]''
2016-11-14 14:12:39 - DEBUG SimpleThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'
2016-11-14 14:12:39 - INFO runTests: 'Finished'

1..976
# tests 976
# pass  976

# ok

2016-11-14 14:12:41 - INFO runTests: 'Starting tests. Network type: BOTH. Platform: android'
2016-11-14 14:12:41 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreateNativeListener.js'
2016-11-14 14:12:41 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js'
2016-11-14 14:12:41 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js'
2016-11-14 14:12:41 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
2016-11-14 14:12:41 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
2016-11-14 14:12:41 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testNativeMethod.js'
2016-11-14 14:12:41 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
2016-11-14 14:12:42 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBGenerator.js'
2016-11-14 14:12:42 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPromiseQueue.js'
2016-11-14 14:12:42 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testTests.js'
2016-11-14 14:12:42 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManager.js'
2016-11-14 14:12:42 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
2016-11-14 14:12:42 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js'
2016-11-14 14:12:42 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNative.js'
2016-11-14 14:12:42 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
2016-11-14 14:12:42 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
2016-11-14 14:12:42 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
2016-11-14 14:12:42 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
2016-11-14 14:12:42 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotification.js'
2016-11-14 14:12:42 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationAction.js'
2016-11-14 14:12:42 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
2016-11-14 14:12:42 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationClient.js'
2016-11-14 14:12:42 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationLocal.js'
2016-11-14 14:12:42 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationServer.js'
2016-11-14 14:12:42 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerAction.js'
2016-11-14 14:12:42 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerDictionary.js'
2016-11-14 14:12:42 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
2016-11-14 14:12:42 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
2016-11-14 14:12:42 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
2016-11-14 14:12:42 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
2016-11-14 14:12:42 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
2016-11-14 14:12:42 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
2016-11-14 14:12:42 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
2016-11-14 14:12:42 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
2016-11-14 14:12:42 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
2016-11-14 14:12:42 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliTcpServersManager.js'
2016-11-14 14:12:42 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
2016-11-14 14:12:42 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testUsn.js'
2016-11-14 14:12:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-14 14:12:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-14 14:12:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-14 14:12:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-14 14:12:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-14 14:12:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
TAP version 13
# setup
# calling createNativeListener directly rejects
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'listening 50584'
ok 1 Should throw
# teardown
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - close'
# setup
# emits incomingConnectionState
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'listening 50586'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 2 initial connection state should be CONNECTED
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 3 final connection state should be DISCONNECTED
# teardown
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - close'
# setup
# emits routerPortConnectionFailed
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'listening 50589'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
ok 4 tried to connect to right port
ok 5 failed due to refused connection
ok 6 routerPortConnectionFailed is emitted
# teardown
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# setup
# native server connections all up
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'listening 50593'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
ok 7 Send/recvd #1 should be equal length
ok 8 Send/recvd #1 should be same
ok 9 Send/recvd #2 should be equal length
ok 10 Send/recvd #2 should be same
ok 11 Should be exactly 2 client sockets
# teardown
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# setup
# native server - closing incoming stream cleans outgoing socket
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'listening 50598'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
ok 12 socket shouldn't close until after stream
ok 13 incoming remains open
# teardown
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# setup
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# native server - closing incoming connection cleans outgoing socket
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'listening 50602'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 14 we should not have gotten an error
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 15 socket shouldn't close until after incoming
ok 16 incoming is cleaned up
# teardown
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - close'
# setup
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# native server - closing outgoing socket cleans associated mux stream
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'listening 50606'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
ok 17 stream was closed
ok 18 incoming should survive
ok 19 mux should have no streams
# teardown
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# setup
# native server - closing the whole server cleans everything up
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'listening 50610'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 20 we should not have gotten an error
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 21 Buffers are identical
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 22 native server is nulled out
ok 23 native server should be closed
ok 24 incoming has been removed
ok 25 Incoming should be done
ok 26 The mux object should be closed
ok 27 The mux stream should be closed
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# teardown
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# setup
# native server - we can get a ton of connections and data through and still clean up the server completely
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'listening 50614'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
ok 28 native server is nulled out
ok 29 native server should be closed
ok 30 incoming has been removed
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# teardown
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# native server - simulate mux failure, make sure everything is cleaned up
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'listening 50666'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 31 we should not have gotten an error
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 32 Buffers are identical
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 33 server should be fine
ok 34 server should be open
ok 35 incoming has been removed
ok 36 The mux object should be closed
ok 37 The mux stream should be closed
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# teardown
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - close'
# setup
# native server - timing out the incoming connection cleans everything up
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'listening 50670'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 38 we should not have gotten an error
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 39 Buffers are identical
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 40 server should be fine
ok 41 server should be open
ok 42 incoming has been removed
ok 43 The mux object should be closed
ok 44 The mux stream should be closed
# teardown
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - close'
# setup
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# calling createPeerListener without calling start produces error
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'listening 50675'
# teardown
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# calling createPeerListener after calling stop produces error
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'listening 50678'
# teardown
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# can call createPeerListener (pleaseConnect === false)
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'listening 50681'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'creating new server for peerId'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peerId listening on 50682'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 45 port must be in range
# teardown
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peerId'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# calling createPeerListener (pleaseConnect === true) with unknown peer is error
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'listening 50685'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'creating new server for peerId'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peerId listening on 50686'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Issuing callNative for peerId'
2016-11-14 14:12:42 - WARN createPeerListener: 'callNative for peerId failed with Unknown Peer'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'We are emitting failedConnection with error Error: Unknown Peer and peerIdentifier peerId'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Will try to recreate server for peerId'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peerId'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'creating new server for peerId'
ok 46 should get error
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peerId listening on 50687'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peerId and portNumber 50687'
# teardown
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peerId'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# calling createPeerListener twice with same peerIdentifier should return the same port
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'listening 50690'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50691'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 47 port values should be the same
# teardown
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - closing connection to native listener closes everything and triggers new listener
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'listening 50694'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'creating new server for peer2'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 50695'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer2 - 0 - got a new incoming connection'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Issuing callNative for peer2'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'callNative for peer2 connected'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer2'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 48 Data should be of same length and content
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer2 - finish'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer2 - 0 - close'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer2 - finish'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer2 - 0 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer2 - close'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'We are emitting failedConnection with error Error: Outgoing closed, recreating connection and peerIdentifier peer2'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Will try to recreate server for peer2'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer2 - close'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer2'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'creating new server for peer2'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 50700'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer2 and portNumber 50700'
ok 49 same peer ID
ok 50 different ports
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
# teardown
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer2'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# createPeerListener - closing mux closes listener and triggers a new listener
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'listening 50703'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'creating new server for peer2'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 50704'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer2 - 0 - got a new incoming connection'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Issuing callNative for peer2'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'callNative for peer2 connected'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer2'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 51 Data should be of same length and content
2016-11-14 14:12:42 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer2 - 0 - close'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer2 - close'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer2 - finish'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer2 - finish'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer2 - 0 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'We are emitting failedConnection with error Error: Outgoing closed, recreating connection and peerIdentifier peer2'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Will try to recreate server for peer2'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer2 - close'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer2'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'creating new server for peer2'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 50709'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer2 and portNumber 50709'
ok 52 same peer ID
ok 53 different ports
# teardown
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer2'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# peerListener - forwardConnection, pleaseConnect === true - no native server
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Creating Native Server'
ok 54 Can call startUpdateAdvertisingAndListening without error
ok 55 Can call startListeningForAdvertisements without error
2016-11-14 14:12:42 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'listening 50712'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50713'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'We are emitting failedConnection with error Error: Cannot Connect To Peer and peerIdentifier peer1'
ok 56 reason should be as expected
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Will try to recreate server for peer1'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50715'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer1 and portNumber 50715'
# teardown
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# peerListener - forwardConnection, pleaseConnect === false - no native server
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Creating Native Server'
ok 57 Can call startUpdateAdvertisingAndListening without error
ok 58 Can call startListeningForAdvertisements without error
2016-11-14 14:12:42 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'listening 50718'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50719'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 59 peerPort should not be nativePort
2016-11-14 14:12:42 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'We are emitting failedConnection with error Error: Cannot Connect To Peer and peerIdentifier peer1'
ok 60 Should not get event until connection is made
ok 61 reason should be as expected
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Will try to recreate server for peer1'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - finish'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50722'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer1 and portNumber 50722'
# teardown
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
# setup
# peerListener - forwardConnection, pleaseConnect === true - with native server
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Creating Native Server'
ok 62 Can call startUpdateAdvertisingAndListening without error
ok 63 Can call startListeningForAdvertisements without error
2016-11-14 14:12:42 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'listening 50725'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50726'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
ok 64 Should get spontaneous connection
ok 65 peerPort != nativePort
# teardown
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
2016-11-14 14:12:42 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# peerListener - forwardConnection, pleaseConnect === false - with native server
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Creating Native Server'
ok 66 Can call startUpdateAdvertisingAndListening without error
ok 67 Can call startListeningForAdvertisements without error
2016-11-14 14:12:42 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'listening 50730'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50731'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 68 peerPort != nativePort
2016-11-14 14:12:42 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer1 - close'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - close'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
ok 69 Should not get unexpected connection
# teardown
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer1 - 0 - close'
# setup
2016-11-14 14:12:42 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# peerListener - forwardConnection, pleaseConnect === false - with native server and data transfer
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'listening 50736'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50737'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer1 - close'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - close'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 70 Data should be of same length and content
ok 71 Data should be of same length and content
# teardown
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer1 - 0 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:12:42 - WARN createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 -  error Error: read ECONNRESET'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - close'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# setup
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer1 - close'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# createPeerListener is idempotent
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Creating Native Server'
ok 72 Can call startUpdateAdvertisingAndListening without error
ok 73 Can call startListeningForAdvertisements without error
2016-11-14 14:12:42 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'listening 50743'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50744'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 74 Second call to existing peerListener returns existing port
# teardown
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - pleaseConnect === true, failed connection rejects promise
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Creating Native Server'
ok 75 Can call startUpdateAdvertisingAndListening without error
ok 76 Can call startListeningForAdvertisements without error
2016-11-14 14:12:42 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'listening 50747'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50748'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-14 14:12:42 - WARN createPeerListener: 'callNative for peer1 failed with a nasty error'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'We are emitting failedConnection with error Error: a nasty error and peerIdentifier peer1'
ok 77 got our failed connection
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Will try to recreate server for peer1'
ok 78 failed connection should reject with error
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50749'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer1 and portNumber 50749'
# teardown
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - pleaseConnect === true, connection resolves promise
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Creating Native Server'
ok 79 Can call startUpdateAdvertisingAndListening without error
ok 80 Can call startListeningForAdvertisements without error
2016-11-14 14:12:42 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'listening 50752'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50753'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
ok 81 Should get spontaneous connection
ok 82 promise should resolve
# teardown
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
2016-11-14 14:12:42 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# peerListener - reverseConnection, pleaseConnect === true
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Creating Native Server'
ok 83 Can call startUpdateAdvertisingAndListening without error
ok 84 Can call startListeningForAdvertisements without error
2016-11-14 14:12:42 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'listening 50757'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50758'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-14 14:12:42 - WARN createPeerListener: 'was expecting a forward connection to be made'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'We are emitting failedConnection with error Error: Cannot Connect To Peer and peerIdentifier peer1'
ok 85 reason should be as expected
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Will try to recreate server for peer1'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50759'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer1 and portNumber 50759'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer1 - close'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - close'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# teardown
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# peerListener - reverseConnection, pleaseConnect === false - no incoming
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Creating Native Server'
ok 86 Can call startUpdateAdvertisingAndListening without error
ok 87 Can call startListeningForAdvertisements without error
2016-11-14 14:12:42 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'listening 50762'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50763'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 88 peerPort should not be nativePort
2016-11-14 14:12:42 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'looking up mux for client port:  0'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'timed out waiting for incoming connection'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'reverse connection'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'looking up mux for client port:  0'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'no mux found'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'We are emitting failedConnection with error Error: Incoming connection died and peerIdentifier peer1'
ok 89 should not get event until connection is made
ok 90 reason should be as expected
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Will try to recreate server for peer1'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client - is already closed'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50765'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer1 and portNumber 50765'
# teardown
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
# setup
# peerListener - reverseConnection, pleaseConnect === false - with incoming
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Creating Native Server'
ok 91 Can call startUpdateAdvertisingAndListening without error
ok 92 Can call startListeningForAdvertisements without error
2016-11-14 14:12:42 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'listening 50768'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50769'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'looking up mux for client port:  50771'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'reverse connection'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'looking up mux for client port:  50771'
ok 93 sent and received should be the same
# teardown
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer1 - 0 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# setup
# peerListener - reverseConnection, pleaseConnect === false - no server
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Creating Native Server'
ok 94 Can call startUpdateAdvertisingAndListening without error
ok 95 Can call startListeningForAdvertisements without error
2016-11-14 14:12:42 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'listening 50774'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50775'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'looking up mux for client port:  50777'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'reverse connection'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'looking up mux for client port:  50777'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
ok 96 should get routerPortConnectionFailed
2016-11-14 14:12:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
# teardown
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer1 - 0 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# setup
# createPeerListener - ask for new peer when we are at maximum and make sure we remove the right existing listener
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'listening 50781'
# teardown
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - ask for a new peer when we are not at maximum peers and make sure we do not remove any existing listeners
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'listening 50784'
# teardown
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - pleaseConnect = false - test timeout
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'listening 50787'
# teardown
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - pleaseConnect = true - test timeout
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'listening 50790'
# teardown
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - forward connection - wrong serverPort
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'listening 50793'
# teardown
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - forward connection - wrong clientPort
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'listening 50796'
# teardown
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - please connect = false, multiple connections out
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'listening 50799'
# teardown
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - please connect = false, multiple bi-directional connections
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'listening 50802'
# teardown
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - multiple parallel calls
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'listening 50805'
# teardown
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - we shouldn't create a dead pipe
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Creating Native Server'
ok 97 Can call startUpdateAdvertisingAndListening without error
ok 98 Can call startListeningForAdvertisements without error
2016-11-14 14:12:42 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'listening 50808'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50809'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 99 peerPort != nativePort
2016-11-14 14:12:42 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
ok 100 Should not get unexpected connection
2016-11-14 14:12:42 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID peer1 with port 50809'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client - is already closed'
ok 101 passed
2016-11-14 14:12:42 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
# teardown
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# setup
# #_doImmediateSeqUpdate - server is not there
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer1 - close'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - close'
2016-11-14 14:12:42 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
2016-11-14 14:12:42 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
ok 102 Got right error
# teardown
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - server accepts & closes connection
2016-11-14 14:12:42 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
ok 103 Got socket hang up
# teardown
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - server always returns 500
2016-11-14 14:12:42 - DEBUG localSeqManager: 'Got an error trying to update seq []'
ok 104 Got 500 as expected
# teardown
2016-11-14 14:12:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - create new seq doc
ok 105 should be equal
ok 106 revs are equal
# teardown
2016-11-14 14:12:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - doc exists, need to get rev and update
ok 107 should be equal
ok 108 revs are equal
# teardown
2016-11-14 14:12:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - update seq three times
ok 109 should be equal
ok 110 revs are equal
ok 111 should be equal
ok 112 revs are equal
ok 113 should be equal
ok 114 revs are equal
# teardown
2016-11-14 14:12:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - rev got changed under us
2016-11-14 14:12:43 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
ok 115 Our rev is old so we should fail
# teardown
2016-11-14 14:12:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - fail if stop is called
ok 116 confirm stop caused failure
# teardown
2016-11-14 14:12:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - stop after get but before put fails right
2016-11-14 14:12:43 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
ok 117 stop caused us to fail
ok 118 We specifically failed on a stop before put
# teardown
2016-11-14 14:12:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - fail if stop is called
ok 119 failed due to stop
ok 120 failed due to stop
# teardown
2016-11-14 14:12:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - set seq for first time
ok 121 should be equal
# teardown
2016-11-14 14:12:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - Fail on bad seq value
2016-11-14 14:12:43 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
ok 122 Expected bad seq error
# teardown
2016-11-14 14:12:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - do we cancel timer properly on an immediate?
ok 123 Different promises
ok 124 Timer was cancelled
ok 125 should be equal
# teardown
2016-11-14 14:12:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - do we wait for blocked update
ok 126 One go and one blocked
ok 127 All blocked
ok 128 Still blocked
ok 129 should be equal
# teardown
2016-11-14 14:12:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - test that we wait long enough
ok 130 We waited long enough
ok 131 should be equal
# teardown
2016-11-14 14:12:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - test that we pick up new sequences while we wait
ok 132 Should have gotten same timer promise
ok 133 Still same timer promise
ok 134 We waited long enough
ok 135 should be equal
# teardown
2016-11-14 14:12:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# closeAll can close even when connections open
2016-11-14 14:12:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 136 not possible to connect to the server anymore
# teardown
# setup
# closeAll with promise
2016-11-14 14:12:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 137 not possible to connect to the server anymore
# teardown
# setup
# closeAll properly throws when closing a non open server with eatNotRunning set to false
2016-11-14 14:12:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 138 Got the right error
# teardown
# setup
# closeAll works even with a server that is not listening yet witheatNotRunning set to true
2016-11-14 14:12:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
# setup
# Call of onCheckpointReached handler on a single db change
# teardown
# setup
# Call of multiple onCheckpointReached handlers on a single db change
# teardown
# setup
# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
ok 139 the checkpointReached handler should be called once. Called 1 time(s)
# teardown
# setup
# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
# teardown
# setup
# test defaultDirectory
ok 140 should be equal
ok 141 should be equal
ok 142 should be equal
# teardown
# setup
# test defaultAdapter
ok 143 should be equal
ok 144 should be equal
ok 145 should be equal
ok 146 should be equal
ok 147 should be equal
ok 148 should be equal
ok 149 should be equal
ok 150 should be equal
# teardown
# setup
# enqueue and run in order
ok 151 firstPromise setTimeout
ok 152 firstPromise result
ok 153 firstPromise testValue
ok 154 secondPromise setTimeout
ok 155 secondPromise result
ok 156 secondPromise testValue
ok 157 thirdPromise in promise
ok 158 thirdPromise result
ok 159 thirdPromise testValue
# teardown
# setup
# enqueueAtTop and run backwards
ok 160 thirdPromise - first to run
ok 161 thirdPromise - in resolve
ok 162 secondPromise - second to run
ok 163 secondPromise - in catch
ok 164 firstPromise - third to run
ok 165 firstPromise - in then
ok 166 testing promises
# teardown
# setup
# mix enqueue and enqueueAtTop
ok 167 fourth
ok 168 fourth
ok 169 second
ok 170 secondPromise - in then
ok 171 first
ok 172 firstPromise - in catch
ok 173 third
ok 174 thirdPromise - in then
ok 175 testingPromises
# teardown
# setup
# queues handled independently
ok 176 all short operations completed before the long resolves
# teardown
# setup
# basic
ok 177 sane
# teardown
# setup
# another
ok 178 sane
# teardown
# setup
# test thali manager spies
2016-11-14 14:12:48 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
2016-11-14 14:12:48 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
2016-11-14 14:12:49 - DEBUG thaliManager: 'creating express pouchdb instance'
ok 179 expressPouchDB was called once
ok 180 expressPouchDB was called with 2 arguments
ok 181 expressPouchDB was called with 'PouchDB' as 1-st argument
ok 182 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
ok 183 PouchDB was called once
ok 184 PouchDB was called with 1 arguments
ok 185 PouchDB was called with 'dbName' as 1-st argument
ok 186 ThaliSendNotificationBasedOnReplication was called once
ok 187 ThaliSendNotificationBasedOnReplication was called with 4 arguments
ok 188 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
ok 189 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
ok 190 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
ok 191 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
ok 192 ThaliPullReplicationFromNotification was called once
ok 193 ThaliPullReplicationFromNotification was called with 4 arguments
ok 194 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
ok 195 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
ok 196 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
ok 197 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
ok 198 Salti was called once
ok 199 Salti was called with 4 arguments
ok 200 Salti was called with 'dbName' as 1-st argument
ok 201 Salti was called with 'acl' as 2-st argument
ok 202 Salti was called with 'thaliIdCallback' as 3-st argument
ok 203 Salti was called with 'options' as 4-st argument
2016-11-14 14:12:49 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-14 14:12:49 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-14 14:12:49 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'listening 50887'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'listening 50888'
2016-11-14 14:12:49 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-14 14:12:49 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-14 14:12:49 - DEBUG thaliWifiInfrastructure: 'listening 50889'
2016-11-14 14:12:49 - DEBUG thaliWifiInfrastructure: 'listening 50891'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-11-14 14:12:49 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
ok 204 ThaliMobile.start was called once
ok 205 ThaliMobile.start was called with 3 arguments
ok 206 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
ok 207 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
ok 208 ThaliMobile.start was called with 'networkType' as 3-st argument
ok 209 ThaliMobile.startListeningForAdvertisements was called once
ok 210 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
ok 211 ThaliMobile.startUpdateAdvertisingAndListening was called once
ok 212 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
ok 213 ThaliSendNotificationBasedOnReplication.prototype.start was called once
ok 214 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
ok 215 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
ok 216 ThaliPullReplicationFromNotification.prototype.start was called once
ok 217 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
ok 218 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
2016-11-14 14:12:49 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-14 14:12:49 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-14 14:12:49 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-14 14:12:49 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-14 14:12:49 - DEBUG thaliManager: 'stopping ThaliMobile'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 219 ThaliMobile.stop was called once
ok 220 ThaliMobile.stop was called with 0 arguments
ok 221 ThaliMobile.stopListeningForAdvertisements was called once
ok 222 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
ok 223 ThaliMobile.stopAdvertisingAndListening was called once
ok 224 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
ok 225 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
ok 226 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
ok 227 ThaliPullReplicationFromNotification.prototype.stop was called once
ok 228 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
# teardown
# setup
# test thali manager multiple starts and stops
2016-11-14 14:12:49 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
2016-11-14 14:12:49 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
2016-11-14 14:12:49 - DEBUG thaliManager: 'creating express pouchdb instance'
ok 229 expressPouchDB was called once
ok 230 expressPouchDB was called with 2 arguments
ok 231 expressPouchDB was called with 'PouchDB' as 1-st argument
ok 232 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
ok 233 PouchDB was called once
ok 234 PouchDB was called with 1 arguments
ok 235 PouchDB was called with 'dbName' as 1-st argument
ok 236 ThaliSendNotificationBasedOnReplication was called once
ok 237 ThaliSendNotificationBasedOnReplication was called with 4 arguments
ok 238 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
ok 239 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
ok 240 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
ok 241 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
ok 242 ThaliPullReplicationFromNotification was called once
ok 243 ThaliPullReplicationFromNotification was called with 4 arguments
ok 244 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
ok 245 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
ok 246 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
ok 247 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
ok 248 Salti was called once
ok 249 Salti was called with 4 arguments
ok 250 Salti was called with 'dbName' as 1-st argument
ok 251 Salti was called with 'acl' as 2-st argument
ok 252 Salti was called with 'thaliIdCallback' as 3-st argument
ok 253 Salti was called with 'options' as 4-st argument
2016-11-14 14:12:49 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-14 14:12:49 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-14 14:12:49 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'listening 50892'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'listening 50893'
2016-11-14 14:12:49 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-14 14:12:49 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-14 14:12:49 - DEBUG thaliWifiInfrastructure: 'listening 50894'
2016-11-14 14:12:49 - DEBUG thaliWifiInfrastructure: 'listening 50896'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-11-14 14:12:49 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
ok 254 ThaliMobile.start was called once
ok 255 ThaliMobile.start was called with 3 arguments
ok 256 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
ok 257 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
ok 258 ThaliMobile.start was called with 'networkType' as 3-st argument
ok 259 ThaliMobile.startListeningForAdvertisements was called once
ok 260 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
ok 261 ThaliMobile.startUpdateAdvertisingAndListening was called once
ok 262 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
ok 263 ThaliSendNotificationBasedOnReplication.prototype.start was called once
ok 264 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
ok 265 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
ok 266 ThaliPullReplicationFromNotification.prototype.start was called once
ok 267 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
ok 268 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
2016-11-14 14:12:49 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-14 14:12:49 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-14 14:12:49 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-14 14:12:49 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-14 14:12:49 - DEBUG thaliManager: 'stopping ThaliMobile'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 269 ThaliMobile.stop was called once
ok 270 ThaliMobile.stop was called with 0 arguments
ok 271 ThaliMobile.stopListeningForAdvertisements was called once
ok 272 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
ok 273 ThaliMobile.stopAdvertisingAndListening was called once
ok 274 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
ok 275 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
ok 276 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
ok 277 ThaliPullReplicationFromNotification.prototype.stop was called once
ok 278 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
2016-11-14 14:12:49 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-14 14:12:49 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-14 14:12:49 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'listening 50897'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'listening 50898'
2016-11-14 14:12:49 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-14 14:12:49 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-14 14:12:49 - DEBUG thaliWifiInfrastructure: 'listening 50899'
2016-11-14 14:12:49 - DEBUG thaliWifiInfrastructure: 'listening 50901'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-11-14 14:12:49 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
2016-11-14 14:12:49 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-14 14:12:49 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-14 14:12:49 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-14 14:12:49 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-14 14:12:49 - DEBUG thaliManager: 'stopping ThaliMobile'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-14 14:12:49 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-14 14:12:49 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'listening 50902'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'listening 50903'
2016-11-14 14:12:49 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-14 14:12:49 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-14 14:12:49 - DEBUG thaliWifiInfrastructure: 'listening 50904'
2016-11-14 14:12:49 - DEBUG thaliWifiInfrastructure: 'listening 50906'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-11-14 14:12:49 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
2016-11-14 14:12:49 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-14 14:12:49 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-14 14:12:49 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-14 14:12:49 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-14 14:12:49 - DEBUG thaliManager: 'stopping ThaliMobile'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-14 14:12:49 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-14 14:12:49 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'listening 50907'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'listening 50908'
2016-11-14 14:12:49 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-14 14:12:49 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-14 14:12:49 - DEBUG thaliWifiInfrastructure: 'listening 50909'
2016-11-14 14:12:49 - DEBUG thaliWifiInfrastructure: 'listening 50911'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-11-14 14:12:49 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
ok 279 ThaliMobile.start was called once
ok 280 ThaliMobile.start was called with 3 arguments
ok 281 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
ok 282 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
ok 283 ThaliMobile.start was called with 'networkType' as 3-st argument
ok 284 ThaliMobile.startListeningForAdvertisements was called once
ok 285 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
ok 286 ThaliMobile.startUpdateAdvertisingAndListening was called once
ok 287 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
ok 288 ThaliSendNotificationBasedOnReplication.prototype.start was called once
ok 289 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
ok 290 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
ok 291 ThaliPullReplicationFromNotification.prototype.start was called once
ok 292 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
ok 293 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
2016-11-14 14:12:49 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-14 14:12:49 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-14 14:12:49 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-14 14:12:49 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-14 14:12:49 - DEBUG thaliManager: 'stopping ThaliMobile'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
# setup
# #startListeningForAdvertisements should fail if start not called
ok 294 specific error should be returned
# teardown
ok 295 error should be null
ok 296 error should be null
# setup
# #startUpdateAdvertisingAndListening should fail if start not called
ok 297 specific error should be returned
# teardown
ok 298 error should be null
ok 299 error should be null
# setup
# should be able to call #stopListeningForAdvertisements many times
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'listening 50912'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'listening 50913'
ok 300 error should be null
ok 301 error should be null
ok 302 error should be null
ok 303 error should be null
# teardown
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 304 error should be null
ok 305 error should be null
# setup
# should be able to call #startListeningForAdvertisements many times
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'listening 50914'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'listening 50915'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 306 error should be null
ok 307 error should be null
ok 308 error should be null
ok 309 error should be null
# teardown
2016-11-14 14:12:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-14 14:12:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 310 error should be null
ok 311 error should be null
# setup
# should be able to call #startUpdateAdvertisingAndListening many times
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'listening 50916'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'listening 50917'
2016-11-14 14:12:49 - DEBUG thaliWifiInfrastructure: 'listening 50918'
2016-11-14 14:12:49 - DEBUG thaliWifiInfrastructure: 'listening 50920'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 312 error should be null
ok 313 error should be null
ok 314 error should be null
ok 315 error should be null
# teardown
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-14 14:12:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 316 error should be null
ok 317 error should be null
# setup
# should be able to call #stopAdvertisingAndListening many times
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'listening 50921'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'listening 50922'
ok 318 error should be null
ok 319 error should be null
ok 320 error should be null
ok 321 error should be null
# teardown
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 322 error should be null
ok 323 error should be null
# setup
# #start - Causing native or wifi to fail will cause a promise reject 
2016-11-14 14:12:49 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
ok 324 This should not cause wifi to fail
ok 325 native router should be bad
# teardown
ok 326 error should be null
ok 327 error should be null
# setup
# #start should fail if called twice in a row
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'listening 50923'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'listening 50924'
ok 328 first call should succeed
ok 329 first call should succeed
ok 330 specific error should be returned
# teardown
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 331 error should be null
ok 332 error should be null
# setup
# #stop should clear watchers and change peers
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'listening 50925'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'listening 50926'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"urn:uuid:755be88f-764d-4c01-a531-022b2617531e","peerAvailable":true,"pleaseConnect":false}'
2016-11-14 14:12:49 - DEBUG createPeerListener: 'creating new server for urn:uuid:755be88f-764d-4c01-a531-022b2617531e'
2016-11-14 14:12:49 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for urn:uuid:755be88f-764d-4c01-a531-022b2617531e listening on 50927'
2016-11-14 14:12:49 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"urn:uuid:755be88f-764d-4c01-a531-022b2617531e","peerAvailable":true,"portNumber":50927}'
ok 333 Watchers have one entry for our connection type
ok 334 Peer availabilities has one entry for our connection type
2016-11-14 14:12:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"urn:uuid:755be88f-764d-4c01-a531-022b2617531e","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-14 14:12:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:49 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for urn:uuid:755be88f-764d-4c01-a531-022b2617531e'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 335 No watchers
ok 336 No peers
ok 337 No watchers
ok 338 No peers
ok 339 No watchers
ok 340 No peers
# teardown
ok 341 error should be null
ok 342 error should be null
# setup
# does not emit duplicate discoveryAdvertisingStateUpdate
2016-11-14 14:12:49 - DEBUG SimpleThaliTape: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
# teardown
ok 343 error should be null
ok 344 error should be null
# setup
# does not send duplicate availability changes
ok 345 should be called once
ok 346 should not have been called more than once
# teardown
2016-11-14 14:12:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"660a2c68-c4a9-45d7-8330-61e1f20598e4","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 347 error should be null
ok 348 error should be null
# setup
# can get the network status
ok 349 network status should have certain non-empty properties
# teardown
ok 350 error should be null
ok 351 error should be null
# setup
# wifi peer is marked unavailable if announcements stop
2016-11-14 14:12:49 - DEBUG SimpleThaliTape: 'test was skipped, name: 'wifi peer is marked unavailable if announcements stop''
# teardown
ok 352 error should be null
ok 353 error should be null
# setup
# native peer should be removed if no availability updates were received during availability timeout
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'listening 50928'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'listening 50929'
ok 354 peer is available
2016-11-14 14:12:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b421187e-fb63-447f-a729-30d40bee7558","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 355 peer is not availabel because it was too silent
# teardown
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 356 error should be null
ok 357 error should be null
# setup
# peerAvailabilityChanged - peer added/removed to/from cache (native)
ok 358 we have not added peer to the cache yet
ok 359 peer should be available
ok 360 cache contains native peer
ok 361 peer should be unavailable
ok 362 peer has been removed from cache
# teardown
ok 363 error should be null
ok 364 error should be null
# setup
# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
ok 365 we have not added peer to the cache yet
ok 366 peer should be available
ok 367 cache contains wifi peer
ok 368 peer should be unavailable
ok 369 peer has been removed from cache
# teardown
ok 370 error should be null
ok 371 error should be null
# setup
# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
ok 372 first peer is available
ok 373 second peer is available
ok 374 first and second peers are different
# teardown
2016-11-14 14:12:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5db8206a-92d4-4872-97cd-b8406c024046","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
2016-11-14 14:12:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"56f128e0-8f03-4bae-b468-2ca0c5bd1470","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 375 error should be null
ok 376 error should be null
# setup
# native available - new peer is cached
ok 377 should not be in cache at start
ok 378 peer is available
# teardown
2016-11-14 14:12:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"592ea40f-07c8-48e5-bcda-8a612ea0efce","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 379 error should be null
ok 380 error should be null
# setup
# native available - peer with same port and different generation is cached (BLUETOOTH)
ok 381 peer should be available
ok 382 peer should be available
ok 383 peer should be available
# teardown
2016-11-14 14:12:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"6fb0891e-2267-479f-87a5-2da1b782fb2a","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 384 error should be null
ok 385 error should be null
# setup
# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
ok 386 peer should be available
ok 387 peer should be available
# teardown
2016-11-14 14:12:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"f2e53d2e-e14d-482f-a95f-d722d4def8df","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 388 error should be null
ok 389 error should be null
# setup
# native available - peer with greater generation is cached (MPCF)
2016-11-14 14:12:49 - DEBUG SimpleThaliTape: 'test was skipped, name: 'native available - peer with greater generation is cached (MPCF)''
# teardown
ok 390 error should be null
ok 391 error should be null
# setup
# native available - peer with same or older generation is ignored (MPCF)
2016-11-14 14:12:49 - DEBUG SimpleThaliTape: 'test was skipped, name: 'native available - peer with same or older generation is ignored (MPCF)''
# teardown
ok 392 error should be null
ok 393 error should be null
# setup
# native unavailable - new peer is ignored
ok 394 NOT IMPLEMENTED # SKIP
# teardown
ok 395 error should be null
ok 396 error should be null
# setup
# native unavailable - cached peer is removed
ok 397 NOT IMPLEMENTED # SKIP
# teardown
ok 398 error should be null
ok 399 error should be null
# setup
# networkChanged - fires peerAvailabilityChanged event for wifi peers
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'listening 50930'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'listening 50931'
ok 400 first peer is expected to be available
ok 401 second peer is expected to be available
2016-11-14 14:12:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"a23c1c42-59bb-4405-a0a2-37d0ec2ff883","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 402 peer became unavailable
ok 403 it was wifi peer
# teardown
2016-11-14 14:12:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"cc30b834-d410-490a-bcbe-8cd8913a9f16","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 404 error should be null
ok 405 error should be null
# setup
# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'listening 50932'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'listening 50933'
ok 406 first peer is expected to be available
ok 407 second peer is expected to be available
2016-11-14 14:12:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"d2d1003a-6451-46ff-8d52-d036377d776d","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 408 peer became unavailable
ok 409 it was a native peer
# teardown
2016-11-14 14:12:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"48562338-7362-404e-b029-ac07f5bcd9d1","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 410 error should be null
ok 411 error should be null
# setup
# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
2016-11-14 14:12:49 - DEBUG SimpleThaliTape: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''
# teardown
ok 412 error should be null
ok 413 error should be null
# setup
# multiconnect failure - new peer is ignored (MPCF)
2016-11-14 14:12:49 - DEBUG SimpleThaliTape: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
# teardown
ok 414 error should be null
ok 415 error should be null
# setup
# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
2016-11-14 14:12:49 - DEBUG SimpleThaliTape: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
# teardown
ok 416 error should be null
ok 417 error should be null
# setup
# newAddressPort field (TCP_NATIVE)
ok 418 peer discovered first time does not have new address
ok 419 address has not been changed
ok 420 new port handled correctly
ok 421 new host handled correctly
ok 422 newAddressPort is null for unavailable peers
# teardown
ok 423 error should be null
ok 424 error should be null
# setup
# newAddressPort field (BLUETOOTH)
ok 425 peer discovered first time does not have new address
ok 426 address has not been changed
ok 427 new port handled correctly
ok 428 newAddressPort is null for unavailable peers
# teardown
ok 429 error should be null
ok 430 error should be null
# setup
# newAddressPort field (MPCF)
2016-11-14 14:12:49 - DEBUG SimpleThaliTape: 'test was skipped, name: 'newAddressPort field (MPCF)''
# teardown
ok 431 error should be null
ok 432 error should be null
# setup
# newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)
ok 433 NOT IMPLEMENTED # SKIP
# teardown
ok 434 error should be null
ok 435 error should be null
# setup
# network changes emitted correctly
2016-11-14 14:12:49 - DEBUG SimpleThaliTape: 'test was skipped, name: 'network changes emitted correctly''
# teardown
ok 436 error should be null
ok 437 error should be null
# setup
# network changes not emitted in stopped state
ok 438 event was not emitted
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-14 14:12:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-14 14:12:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
# teardown
ok 439 error should be null
ok 440 error should be null
# setup
# calls correct starts when network changes
2016-11-14 14:12:49 - DEBUG SimpleThaliTape: 'test was skipped, name: 'calls correct starts when network changes''
# teardown
ok 441 error should be null
ok 442 error should be null
# setup
# We properly fire peer unavailable and then available when connection fails
2016-11-14 14:12:49 - DEBUG SimpleThaliTape: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails''
# teardown
ok 443 error should be null
ok 444 error should be null
# setup
# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
2016-11-14 14:12:49 - DEBUG SimpleThaliTape: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
# teardown
ok 445 error should be null
ok 446 error should be null
# setup
# Can call start/stopListeningForAdvertisements
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-14 14:12:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-14 14:12:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 447 Can call startListeningForAdvertisements without error
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-14 14:12:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 448 Can call stopListeningForAdvertisements without error
# teardown
ok 449 Should be able to call stopListeningForAdvertisements in teardown
ok 450 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Calling startListeningForAdvertisements twice is NOT an error
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-14 14:12:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-14 14:12:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 451 Can call startListeningForAdvertisements without error
ok 452 Can call startListeningForAdvertisements twice without error
# teardown
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-14 14:12:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 453 Should be able to call stopListeningForAdvertisements in teardown
ok 454 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Calling stopListeningForAdvertisements without calling start is NOT an error
ok 455 Can call stopListeningForAdvertisements without error
ok 456 Can call stopListeningForAdvertisements without error
# teardown
ok 457 Should be able to call stopListeningForAdvertisements in teardown
ok 458 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Can call start/stopUpdateAdvertisingAndListening
2016-11-14 14:12:49 - DEBUG thaliWifiInfrastructure: 'listening 50935'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2016-11-14 14:12:49 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-14 14:12:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 459 Can call startUpdateAdvertisingAndListening without error
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-14 14:12:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 460 Can call stopAdvertisingAndListening without error
# teardown
ok 461 Should be able to call stopListeningForAdvertisements in teardown
ok 462 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Calling startUpdateAdvertisingAndListening twice is NOT an error
2016-11-14 14:12:49 - DEBUG thaliWifiInfrastructure: 'listening 50937'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2016-11-14 14:12:49 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-14 14:12:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 463 Can call startUpdateAdvertisingAndListening without error
ok 464 Can call startUpdateAdvertisingAndListening twice without error
# teardown
ok 465 Should be able to call stopListeningForAdvertisements in teardown
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-14 14:12:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 466 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
ok 467 Can call startUpdateAdvertisingAndListening without error
ok 468 Can call stopAdvertisingAndListening without error
# teardown
ok 469 Should be able to call stopListeningForAdvertisements in teardown
ok 470 Should be able to call stopAdvertisingAndListening in teardown
# setup
# cannot call connect when start listening for advertisements is not active
ok 471 got right error
# teardown
ok 472 Should be able to call stopListeningForAdvertisements in teardown
ok 473 Should be able to call stopAdvertisingAndListening in teardown
# setup
# #startListeningForAdvertisements should fail if start not called
ok 474 specific error should be returned
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-14 14:12:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 475 must be stopped
# setup
# #startUpdateAdvertisingAndListening should fail if start not called
ok 476 specific error should be returned
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-14 14:12:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 477 must be stopped
# setup
# should be able to call #stopListeningForAdvertisements many times
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'listening 50938'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'listening 50939'
ok 478 no errors
ok 479 still no errors
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-14 14:12:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 480 must be stopped
# setup
# should be able to call #startListeningForAdvertisements many times
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'listening 50940'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'listening 50941'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-14 14:12:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-14 14:12:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 481 no errors
ok 482 still no errors
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-14 14:12:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-14 14:12:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 483 must be stopped
# setup
# should be able to call #startUpdateAdvertisingAndListening many times
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'listening 50942'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'listening 50943'
2016-11-14 14:12:49 - DEBUG thaliWifiInfrastructure: 'listening 50945'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2016-11-14 14:12:49 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-14 14:12:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 484 no errors
ok 485 still no errors
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-14 14:12:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-14 14:12:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 486 must be stopped
# setup
# should be able to call #stopAdvertisingAndListening many times
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'listening 50946'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'listening 50947'
ok 487 no errors
ok 488 still no errors
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-14 14:12:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 489 must be stopped
# setup
# can get the network status before starting
ok 490 network status should have certain non-empty properties
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-14 14:12:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 491 must be stopped
# setup
# error returned with bad router
2016-11-14 14:12:49 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 492 specific error expected
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-14 14:12:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 493 must be stopped
# setup
# all services are stopped when we call stop
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'listening 50948'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'listening 50949'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-14 14:12:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-14 14:12:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-14 14:12:49 - DEBUG thaliWifiInfrastructure: 'listening 50951'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-11-14 14:12:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-14 14:12:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 494 connection to servers manager should succeed after starting
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
ok 495 connection to router server should succeed after starting
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-14 14:12:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-14 14:12:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-14 14:12:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 496 is stopped after calling stop
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-14 14:12:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
ok 497 connection to servers manager should fail after stopping
ok 498 connection to router server should fail after stopping
# teardown
ok 499 must be stopped
# setup
# make sure terminateConnection is properly hooked up
ok 500 called with right arguments
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-14 14:12:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 501 must be stopped
# setup
# make sure terminateListener is properly hooked up
ok 502 called with right arguments
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-14 14:12:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 503 must be stopped
# setup
# make sure we actually call kill connections properly
ok 504 specific error expected
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-14 14:12:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 505 must be stopped
# setup
# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'listening 50956'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'listening 50957'
2016-11-14 14:12:49 - INFO thaliMobileNativeWrapper: 'routerPortConnectionFailed - {"routerPort":50956,"error":{}}'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 506 failure reason is as expected
ok 507 error description is as expected
ok 508 must be stopped
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-14 14:12:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 509 must be stopped
# setup
# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'listening 50958'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'listening 50959'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"some-identifier","peerAvailable":false,"portNumber":null}'
ok 510 peerIdentifier matches
ok 511 error description matches
ok 512 connection type is tcp
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"some-identifier","peerAvailable":false,"generation":null,"portNumber":null}'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-14 14:12:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 513 must be stopped
# setup
# we successfully receive and replay discoveryAdvertisingStateUpdate
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'listening 50960'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'listening 50961'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-14 14:12:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-14 14:12:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 514 discoveryActive matches
ok 515 advertisingActive matches
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-14 14:12:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 516 discoveryActive matches
ok 517 advertisingActive matches
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'listening 50962'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'listening 50963'
2016-11-14 14:12:49 - DEBUG thaliWifiInfrastructure: 'listening 50965'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2016-11-14 14:12:49 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-14 14:12:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 518 discoveryActive matches
ok 519 advertisingActive matches
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-14 14:12:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 520 discoveryActive matches
ok 521 advertisingActive matches
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'listening 50966'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'listening 50967'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-14 14:12:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-14 14:12:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:12:49 - DEBUG createNativeListener: 'Native Server - close'
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 522 must be stopped
# setup
# Test BEACONS_RETRIEVED_AND_PARSED locally
ok 523 peerIdentifier should be identifier
ok 524 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 525 good beacon
ok 526 good preAmble
ok 527 public keys match!
ok 528 must return null after successful call
ok 529 Once start returns the action should be in KILLED state
# teardown
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test HTTP_BAD_RESPONSE locally
ok 530 Response should be HTTP_BAD_RESPONSE
ok 531 must return null after successful call
# teardown
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test NETWORK_PROBLEM locally
ok 532 Response should be NETWORK_PROBLEM
ok 533 reject reason should be: Could not establish TCP connection
# teardown
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Call the start two times
ok 534 Call start once
ok 535 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 536 must return null after successful call.
# teardown
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Call the kill before calling the start
ok 537 Should be Killed
ok 538 Start after killed
# teardown
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Call the kill immediately after the start
ok 539 Should be KILLED
ok 540 must return null after successful kill
# teardown
2016-11-14 14:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Call the kill while waiting a response from the server
ok 541 Should be KILLED
ok 542 must return null after successful kill
# teardown
2016-11-14 14:12:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test to exceed the max content size locally
ok 543 HTTP_BAD_RESPONSE should be response when content size is exceeded
ok 544 must return null after successful call
# teardown
2016-11-14 14:12:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Close the server socket while the client is waiting a response from the server. Local test.
2016-11-14 14:12:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 545 Should be NETWORK_PROBLEM caused closing server socket
ok 546 Should be Could not establish TCP connection
# teardown
# setup
# Close the client socket while the client is waiting a response from the server. Local test.
ok 547 Should be NETWORK_PROBLEM caused closing client socket
ok 548 Should be Could not establish TCP connection
# teardown
2016-11-14 14:12:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #generatePreambleAndBeacons bad args
ok 549 publicKeysToNotify cannot be null
ok 550 ecdh for local device cannot be null
ok 551 milliseconds cannot be less than 0
ok 552 milliseconds cannot be 0
ok 553 milliseconds cannot be greater than one_day
# teardown
# setup
# #generatePreambleAndBeacons empty keys to notify
ok 554 should be equal
# teardown
# setup
# #generatePreambleAndBeacons multiple keys to notify
ok 555 should be equal
ok 556 should be equal
ok 557 (unnamed assert)
ok 558 should be equal
# teardown
# setup
# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
ok 559 should throw
# teardown
# setup
# #parseBeacons invalid expiration in beaconStreamWithPreAmble
ok 560 Preamble expiration must be a 64 bit integer
# teardown
# setup
# #parseBeacons expiration out of range lower
ok 561 Expiration out of range
# teardown
# setup
# #parseBeacons expiration out of range lower
ok 562 Expiration out of range
# teardown
# setup
# #parseBeacons no beacons returns null
ok 563 should be equal
# teardown
# setup
# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
ok 564 Malformed encrypted beacon key ID
# teardown
# setup
# #parseBeacons addressBookCallback fails decrypt
ok 565 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns no matches
ok 566 should be equal
ok 567 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns spurious match
ok 568 should be equal
ok 569 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns public key
ok 570 right number of calls to address book
ok 571 good preAmble
ok 572 good unencryptedKeyId
ok 573 good beacon
# teardown
# setup
# validate generatePskIdentityField
ok 574 decoded buffers match
# teardown
# setup
# validate generatePskSecret
ok 575 secrets match
# teardown
# setup
# validate generatePskSecrets
ok 576 Matching numbers
ok 577 We have an entry!
ok 578 keys match
ok 579 secrets match
ok 580 We have an entry!
ok 581 keys match
ok 582 secrets match
ok 583 We have an entry!
ok 584 keys match
ok 585 secrets match
# teardown
# setup
# validate generateBeaconStreamAndSecrets
ok 586 Streams have same length
ok 587 matching size
ok 588 keys match
ok 589 secrets match
# teardown
# setup
# Add two Peers.
ok 590 should be equal
ok 591 should be equal
ok 592 should be equal
ok 593 should be equal
ok 594 should be equal
# teardown
2016-11-14 14:12:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# TCP_NATIVE peer loses DNS
ok 595 should be equal
ok 596 should be equal
# teardown
2016-11-14 14:12:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Received beacons with no values for us
ok 597 entry exists
ok 598 entry is resolved
# teardown
2016-11-14 14:12:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Notification action killed with a superseded
ok 599 Action should be killed
ok 600 should be equal
# teardown
2016-11-14 14:12:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Resolves an action locally
ok 601 Host address must match
ok 602 suggestedTCPTimeout must match
ok 603 connectionType must match
ok 604 portNumber must match
ok 605 peerIDs must match
# teardown
2016-11-14 14:12:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Resolves an action locally using ThaliPeerPoolDefault
ok 606 Host address must match
ok 607 suggestedTCPTimeout must match
ok 608 connectionType must match
ok 609 portNumber must match
ok 610 peerIds must match
# teardown
2016-11-14 14:12:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Action fails because of a bad hostname.
2016-11-14 14:12:56 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 611 action should be resolved with NETWORK_PROBLEM error
2016-11-14 14:12:56 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 612 action should be resolved with NETWORK_PROBLEM error
2016-11-14 14:12:56 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 613 action should be resolved with NETWORK_PROBLEM error
2016-11-14 14:12:57 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 614 action should be resolved with NETWORK_PROBLEM error
ok 615 correct number of requests
ok 616 correct number of failures
ok 617 correct final peer state
# teardown
2016-11-14 14:12:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# hostaddress is removed when the action is running. 
2016-11-14 14:12:59 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 618 should be equal
# teardown
2016-11-14 14:12:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Client to server request locally
ok 619 secrets are equal
ok 620 Public key matches with the server key
ok 621 Host address must match
ok 622 suggestedTCPTimeout must match
ok 623 connectionType must match
ok 624 portNumber must match
# teardown
2016-11-14 14:12:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test ThaliPskMapCache clean and expiration
ok 625 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
ok 626 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
ok 627 All entries should be expired after 1 second
# teardown
2016-11-14 14:13:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test ThaliPskMapCache getSecret and getPublic
ok 628 All keys need to be available in the cache
ok 629 All entries should be expired after 1 second
# teardown
2016-11-14 14:13:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test ThaliPskMapCache multiple entries
ok 630 Size of the cache should be 2
ok 631 Cache doesn't contain dictionary1
ok 632 Size of the cache should be 1
ok 633 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
2016-11-14 14:13:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Start and stop ThaliNotificationServer
ok 634 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
ok 635 ThaliMobile.StopAdvertisingAndListeningshould be called once
# teardown
2016-11-14 14:13:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Pass an empty array to ThaliNotificationServer.start
ok 636 StartUpdateAdvertisingAndListening should not be called
ok 637 ThaliMobile.StopAdvertisingAndListening should be called once
ok 638 no error
ok 639 should be 204
# teardown
2016-11-14 14:13:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Pass a string to ThaliNotificationServer.start
ok 640 StartUpdateAdvertisingAndListening should not be called
# teardown
2016-11-14 14:13:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Pass an empty parameter to ThaliNotificationServer.start
ok 641 StartUpdateAdvertisingAndListening should not be called
# teardown
2016-11-14 14:13:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make an HTTP request to /NotificationBeacons
ok 642 no error
ok 643 should be 200
ok 644 should be equal
ok 645 should be equal
ok 646 (unnamed assert)
ok 647 no error
ok 648 should be 204
# teardown
2016-11-14 14:13:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make an HTTP request to /NotificationBeacons (no keys)
ok 649 error should be null
ok 650 should be 204
# teardown
2016-11-14 14:13:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make an HTTP request to /NotificationBeaconsbefore calling start
ok 651 should be 404
# teardown
2016-11-14 14:13:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #testThaliPeerAction - test getters
ok 652 getPeerIdentifier
ok 653 getConnectionType
ok 654 getActionType
ok 655 getActionState
ok 656 getPskIdentity
ok 657 getPskKey
# teardown
# setup
# #testThaliPeerAction - start and kill
ok 658 initial state
ok 659 after start
2016-11-14 14:13:03 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 660 after kill
# teardown
# setup
# #testThaliPeerAction - double start
ok 661 should be equal
# teardown
# setup
# #testThaliPeerAction - start after kill
2016-11-14 14:13:03 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 662 clean kill
ok 663 should be equal
# teardown
# setup
# #testThaliPeerAction - make sure ids are unique
ok 664 should not be equal
# teardown
# setup
# #testThaliPeerAction - check that forever agent can be destroyed
ok 665 forever agent should have it's own destroy method
ok 666 agent's destroy should be called
ok 667 agent's destroy should not be called again
ok 668 agent is destroyed
# teardown
# setup
# Test PeerConnectionInformation basics
ok 669 connection type works
ok 670 getHostAddress works
ok 671 getPortNumber works
ok 672 getSuggestedTCPTimeout works
# teardown
# setup
# Test PeerDictionary basic functionality
ok 673 Entry counter must be 1
ok 674 Size must be 1
ok 675 Entry counter must be 2
ok 676 Size must be 2
ok 677 Entry2 should not be found
ok 678 Size must be 1
ok 679 Size must be 0
# teardown
# setup
# Test PeerDictionary with multiple entries.
ok 680 Size must be100
ok 681 Entries between 20 and MAXSIZE + 20 should exist
ok 682 WAITING state entry should not be removed
# teardown
# setup
# RESOLVED entries are removed before WAITING state entry.
ok 683 Entries between 6 and MAXSIZE + 4 should exist
ok 684 Size should be MAXSIZE
ok 685 Size should be MAXSIZE+6
# teardown
# setup
# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
ok 686 WAITING state entry should not be removed
ok 687 Waiting entries between 6 and MAXSIZE + 4 should exist
ok 688 Size should be MAXSIZE
ok 689 entryCounter should be MAXSIZE+6
# teardown
# setup
# When CONTROLLED_BY_POOL entry is removed and kill is called.
ok 690 Kill should be called once
ok 691 Size should be 100
# teardown
# setup
# #ThaliPeerPoolDefault - single action
ok 692 is an agent
ok 693 enqueue is fine
ok 694 Everything should be off the queue
# teardown
# setup
# #ThaliPeerPoolDefault - multiple actions
ok 695 is an agent
ok 696 first enqueue is fine
ok 697 is an agent
ok 698 second enqueue is fine
ok 699 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 700 Queue is empty
# teardown
# setup
# #ThaliPeerPoolDefault - PSK Pool works
ok 701 is an agent
ok 702 good enqueue
ok 703 Identity should match
2016-11-14 14:13:04 - DEBUG testUtils: 'Got response data'
2016-11-14 14:13:04 - DEBUG testUtils: 'Got end'
ok 704 Got expected response
ok 705 Got psk call back
# teardown
2016-11-14 14:13:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #ThaliPeerPoolDefault - stop
ok 706 is an agent
ok 707 enqueue worked
ok 708 is an agent
ok 709 enqueue 2 worked
ok 710 enqueue is not available when stopped
ok 711 start action is killed
ok 712 killed action is still killed
ok 713 inQueue is empty
# teardown
# setup
# #ThaliPeerPoolInterface - make sure that start verifies queue length
ok 714 good start
ok 715 good enqueue
ok 716 queue is not empty
# teardown
# setup
# #ThaliPeerPoolInterface - bad enqueues
ok 717 null arg
ok 718 wrong arg type
ok 719 wrong arg type
# teardown
# setup
# #ThaliPeerPoolInterface - do not allow same object type
ok 720 good enqueue
ok 721 already enqueued
# teardown
# setup
# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
ok 722 good enqueue
ok 723 2nd good enqueue
ok 724 we are in the pool
ok 725 We are out of the pool
ok 726 Action was killed
ok 727 The original kill was called too
ok 728 second item is still in queue
# teardown
# setup
# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
ok 729 good enqueue
ok 730 first kill
ok 731 second NOOP kill
# teardown
# setup
# #ThaliPeerPoolInterface - make sure that stop removes all actions
ok 732 1st good enqueue
ok 733 2nd good enqueue
ok 734 1st action is in the pool
ok 735 2nd action is in the pool
ok 736 1st action is out of the pool
ok 737 2st action is out of the pool
ok 738 pool is empty
# teardown
# setup
# We reject unrecognized connection type
2016-11-14 14:13:04 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 739 Got right error
ok 740 Start should not be called
ok 741 Kill should have been called at least once
# teardown
# setup
# We reject unrecognized action type
2016-11-14 14:13:04 - DEBUG SimpleThaliTape: 'test was skipped, name: 'We reject unrecognized action type''
# teardown
# setup
# One action on bluetooth
2016-11-14 14:13:04 - DEBUG SimpleThaliTape: 'test was skipped, name: 'One action on bluetooth''
# teardown
# setup
# Two notification actions
2016-11-14 14:13:04 - DEBUG SimpleThaliTape: 'test was skipped, name: 'Two notification actions''
# teardown
# setup
# replicateThroughProblems
2016-11-14 14:13:04 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
2016-11-14 14:13:04 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
2016-11-14 14:13:04 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
ok 742 should have gotten null
2016-11-14 14:13:04 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
2016-11-14 14:13:04 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
ok 743 Should have stopped nicely
2016-11-14 14:13:04 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
2016-11-14 14:13:04 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
ok 744 Still looking for null
2016-11-14 14:13:04 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
2016-11-14 14:13:04 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
2016-11-14 14:13:04 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
2016-11-14 14:13:04 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
2016-11-14 14:13:04 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
2016-11-14 14:13:04 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
ok 745 Yup, another null
ok 746 We cloned!
# teardown
# setup
# Replication goes first
2016-11-14 14:13:04 - DEBUG SimpleThaliTape: 'test was skipped, name: 'Replication goes first''
# teardown
# setup
# wifi allows many parallel non-replication actions
2016-11-14 14:13:04 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2016-11-14 14:13:04 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 606, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
ok 747 is an agent
ok 748 First null
2016-11-14 14:13:04 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 607, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
ok 749 is an agent
ok 750 Second null
2016-11-14 14:13:04 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 607, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
truetruefalsetrue
2016-11-14 14:13:04 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 606, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
truetruetruetrue
# teardown
# setup
# wifi allows no more than 2 simultaneous replication actions for same peerID
2016-11-14 14:13:04 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2016-11-14 14:13:04 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 608, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
ok 751 is an agent
ok 752 First null
2016-11-14 14:13:04 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 609, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
ok 753 is an agent
ok 754 second null
ok 755 third null
2016-11-14 14:13:04 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 608, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
2016-11-14 14:13:04 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 609, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
2016-11-14 14:13:04 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
2016-11-14 14:13:04 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
# teardown
# setup
# Make sure peerDictionaryKey is reasonable
ok 756 equal keys
ok 757 not equal connection type
ok 758 same connection type, different buffer
# teardown
# setup
# Make sure start works
2016-11-14 14:13:04 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 759 First start and on called correctly
# teardown
# setup
# Make sure stop works
ok 760 second cleared dictionary
2016-11-14 14:13:04 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 761 First start and on called correctly
ok 762 First stop and removeListener called correctly
ok 763 first action kill called
ok 764 second action kill called
ok 765 first cleared dictionary
ok 766 first cleared pool
ok 767 second cleared dictionary
ok 768 second cleared pool
# teardown
# setup
# Simple peer event
2016-11-14 14:13:04 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 769 listener has been set
ok 770 peer dictionary has expected number of entries
ok 771 Dictionary and pool have same action
ok 772 ads match
ok 773 PouchDB matches
ok 774 DB Names match
ok 775 public keys match
ok 776 peer dictionary has expected number of entries
ok 777 Dictionary and pool have same action
ok 778 ads match
ok 779 PouchDB matches
ok 780 DB Names match
ok 781 public keys match
2016-11-14 14:13:04 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
ok 782 start called once
ok 783 One entry left
ok 784 Dictionary and pool have same action
ok 785 Start never called
ok 786 Kill called once
ok 787 no entries left
ok 788 Third action is dead
ok 789 peer dictionary has expected number of entries
ok 790 Dictionary and pool have same action
ok 791 ads match
ok 792 PouchDB matches
ok 793 DB Names match
ok 794 public keys match
# teardown
# setup
# Server is not there
2016-11-14 14:13:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-14 14:13:04 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
2016-11-14 14:13:04 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: connect ECONNREFUSED  and it caused us to complete'
ok 795 right error
# teardown
2016-11-14 14:13:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Server accepts & closes connection
2016-11-14 14:13:04 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
2016-11-14 14:13:04 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
ok 796 right error
# teardown
2016-11-14 14:13:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Server always returns 500
2016-11-14 14:13:04 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
2016-11-14 14:13:04 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
ok 797 Got error as expected
# teardown
2016-11-14 14:13:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Server always returns 401
2016-11-14 14:13:04 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
2016-11-14 14:13:04 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
ok 798 Got error as expected
# teardown
2016-11-14 14:13:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Server always returns 403
2016-11-14 14:13:04 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
2016-11-14 14:13:04 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
ok 799 Got error as expected
# teardown
2016-11-14 14:13:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make sure docs replicate
2016-11-14 14:13:04 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
2016-11-14 14:13:04 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
2016-11-14 14:13:04 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
ok 800 should be equal
ok 801 All tests passed!
# teardown
2016-11-14 14:13:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Do nothing and make sure we time out
2016-11-14 14:13:05 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
2016-11-14 14:13:07 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2016-11-14 14:13:07 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
ok 802 action should be killed
ok 803 Error should be timed out
ok 804 No doc found
# teardown
2016-11-14 14:13:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Do something and make sure we time out
2016-11-14 14:13:07 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
2016-11-14 14:13:07 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
ok 805 should be equal
2016-11-14 14:13:09 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2016-11-14 14:13:09 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
ok 806 action should be killed
ok 807 Error should be timed out
# teardown
2016-11-14 14:13:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Start replicating and then catch error when server goes
ok 808 socket hung up
# teardown
2016-11-14 14:13:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make sure clone works
ok 809 same getPeerAdvertisesDataForUs
ok 810 Same pouchdB
ok 811 same dbName
ok 812 Same public key
# teardown
# setup
# compareBufferArrays
ok 813 should throw
ok 814 should throw
ok 815 (unnamed assert)
ok 816 (unnamed assert)
ok 817 (unnamed assert)
ok 818 (unnamed assert)
ok 819 (unnamed assert)
# teardown
# setup
# Call start twice and get error
ok 820 should throw
# teardown
# setup
# Start and make sure it runs
# teardown
# setup
# Make sure getTimeWhenRun is right after start
not ok 821 (unnamed assert)
  ---
    operator: ok
    expected: true
    actual:   false
    at: Object.ran (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationUtilities.js:76:5)
  ...
2016-11-14 14:13:09 - ERROR SimpleThaliTape: 'test failed, name: 'Make sure getTimeWhenRun is right after start''
2016-11-14 14:13:09 - ERROR TestsProcess: 'uncaught promise rejection, error: 'Error: test failed, name: 'Make sure getTimeWhenRun is right after start'', stack: 'Error: test failed, name: 'Make sure getTimeWhenRun is right after start'
    at Test.endHandler (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/SimpleTape.js:139:20)
    at Test.g (events.js:160:16)
    at Test.emit (events.js:98:20)
    at Test.bound [as emit] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:62:32)
    at Test._end (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:145:27)
    at Test.bound [as _end] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:62:32)
    at Test.end (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:133:10)
    at Test.bound [as end] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:62:32)
    at Object.ran (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationUtilities.js:77:5)
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/SimpleTape.js:182:23
    at tryCatcher (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/bluebird/js/release/util.js:16:23)
    at Promise._settlePromiseFromHandler (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/bluebird/js/release/promise.js:510:31)
    at Promise._settlePromise (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/bluebird/js/release/promise.js:567:18)
    at Promise._settlePromiseCtx (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/bluebird/js/release/promise.js:604:10)
    at Async._drainQueue (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/bluebird/js/release/async.js:143:12)
    at Async._drainQueues (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/bluebird/js/release/async.js:148:10)
    at Async.drainQueues (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/bluebird/js/release/async.js:17:14)
    at process._tickCallback (node.js:924:13)''
2016-11-14 14:13:09 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
-e [0;31mjx runTests.js --networkType BOTH FAILED - build.sh failure[0m
./build.sh CI FAILED - build.sh failure[0m

npm WARN thali-test-server@0.0.1 No repository field.
npm WARN thali-test-server@0.0.1 No license field.
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/javascript-state-machine
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/js-extend
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/winston
npm http 304 http://192.168.1.100:4873/express
npm http 200 http://192.168.1.100:4873/ip
npm http 200 http://192.168.1.100:4873/javascript-state-machine
npm http 200 http://192.168.1.100:4873/lie
npm http 200 http://192.168.1.100:4873/body-parser
npm http 200 http://192.168.1.100:4873/long
npm http 200 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/js-extend
npm http 200 http://192.168.1.100:4873/uuid
npm http 200 http://192.168.1.100:4873/multiplex
npm http 200 http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/type-is
npm http 200 http://192.168.1.100:4873/bytes
npm http 200 http://192.168.1.100:4873/iconv-lite
npm http 200 http://192.168.1.100:4873/raw-body
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/statuses
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/statuses
npm http fetch GET http://192.168.1.100:4873/statuses/-/statuses-1.3.1.tgz
npm http fetch 200 http://192.168.1.100:4873/statuses/-/statuses-1.3.1.tgz
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
npm http 304 http://192.168.1.100:4873/forwarded
npm http 304 http://192.168.1.100:4873/ipaddr.js
npm http request GET http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/mime
npm http 304 http://192.168.1.100:4873/destroy
npm http 304 http://192.168.1.100:4873/mime
npm http request GET http://192.168.1.100:4873/immediate
npm http 200 http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/xtend
npm http 200 http://192.168.1.100:4873/xtend
npm http 200 http://192.168.1.100:4873/duplexify
npm http 200 http://192.168.1.100:4873/varint
npm http 200 http://192.168.1.100:4873/readable-stream
npm http fetch GET http://192.168.1.100:4873/readable-stream/-/readable-stream-2.2.2.tgz
npm http fetch 200 http://192.168.1.100:4873/readable-stream/-/readable-stream-2.2.2.tgz
npm http request GET http://192.168.1.100:4873/stream-shift
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http 200 http://192.168.1.100:4873/end-of-stream
npm http 200 http://192.168.1.100:4873/stream-shift
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
npm http 200 http://192.168.1.100:4873/string_decoder
npm http 200 http://192.168.1.100:4873/core-util-is
npm http 200 http://192.168.1.100:4873/buffer-shims
npm http 200 http://192.168.1.100:4873/process-nextick-args
npm http 200 http://192.168.1.100:4873/util-deprecate
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 200 http://192.168.1.100:4873/bl
npm http 200 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/caseless
npm http 200 http://192.168.1.100:4873/form-data
npm http 200 http://192.168.1.100:4873/tunnel-agent
npm http 200 http://192.168.1.100:4873/tough-cookie
npm http 200 http://192.168.1.100:4873/oauth-sign
npm http 200 http://192.168.1.100:4873/http-signature
npm http 200 http://192.168.1.100:4873/hawk
npm http 200 http://192.168.1.100:4873/aws-sign2
npm http 200 http://192.168.1.100:4873/combined-stream
npm http 200 http://192.168.1.100:4873/stringstream
npm http 200 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 200 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/lodash
npm http 200 http://192.168.1.100:4873/lodash
npm http fetch GET http://192.168.1.100:4873/lodash/-/lodash-4.17.0.tgz
npm http fetch 200 http://192.168.1.100:4873/lodash/-/lodash-4.17.0.tgz
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http 200 http://192.168.1.100:4873/chalk
npm http 200 http://192.168.1.100:4873/commander
npm http 200 http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 200 http://192.168.1.100:4873/escape-string-regexp
npm http 200 http://192.168.1.100:4873/has-ansi
npm http 200 http://192.168.1.100:4873/strip-ansi
npm http 200 http://192.168.1.100:4873/supports-color
npm http 200 http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 200 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http 200 http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 200 http://192.168.1.100:4873/generate-object-property
npm http 200 http://192.168.1.100:4873/jsonpointer
npm http 200 http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/is-property
npm http 200 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/boom
npm http 200 http://192.168.1.100:4873/boom
npm http 200 http://192.168.1.100:4873/sntp
npm http 200 http://192.168.1.100:4873/cryptiles
npm http 200 http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/ctype
npm http 200 http://192.168.1.100:4873/assert-plus
npm http 200 http://192.168.1.100:4873/ctype
npm http 200 http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/punycode
npm http 200 http://192.168.1.100:4873/punycode
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/jsonschema
npm http 304 http://192.168.1.100:4873/object-assign
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
npm http request GET http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/js2xmlparser
npm http request GET http://192.168.1.100:4873/requizzle
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/marked
npm http request GET http://192.168.1.100:4873/underscore
npm http request GET http://192.168.1.100:4873/wrench
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 200 http://192.168.1.100:4873/catharsis
npm http 200 http://192.168.1.100:4873/esprima
npm http 200 http://192.168.1.100:4873/requizzle
npm http 200 http://192.168.1.100:4873/strip-json-comments
npm http 200 http://192.168.1.100:4873/js2xmlparser
npm http 200 http://192.168.1.100:4873/marked
npm http 200 http://192.168.1.100:4873/underscore
npm http 200 http://192.168.1.100:4873/wrench
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
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/express-pouchdb
npm http request GET http://192.168.1.100:4873/bn.js
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/leveldown-mobile
npm http request GET http://192.168.1.100:4873/request-promise
npm http request GET http://192.168.1.100:4873/pouchdb
npm http request GET http://192.168.1.100:4873/pouchdb-size
npm http request GET http://192.168.1.100:4873/tmp
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/proxyquire
npm http request GET http://192.168.1.100:4873/nock
npm http request GET http://192.168.1.100:4873/sinon
npm http request GET http://192.168.1.100:4873/supertest
npm http request GET http://192.168.1.100:4873/supertest-as-promised
npm http request GET http://192.168.1.100:4873/tape-catch
npm http request GET http://192.168.1.100:4873/uuid-validate
npm http request GET http://192.168.1.100:4873/tape
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/child-process-promise
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/js-extend
npm http 304 http://192.168.1.100:4873/multiplex
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/randomstring
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/socket.io-client
npm http 200 http://192.168.1.100:4873/express-pouchdb
npm http 200 http://192.168.1.100:4873/leveldown-mobile
npm http 200 http://192.168.1.100:4873/pouchdb-size
npm http 304 http://192.168.1.100:4873/urlsafe-base64
npm http 304 http://192.168.1.100:4873/uuid
npm http 200 http://192.168.1.100:4873/request-promise
npm http 200 http://192.168.1.100:4873/bn.js
npm http fetch GET http://192.168.1.100:4873/express-pouchdb/-/express-pouchdb-1.0.6-thali.tgz
npm http 200 http://192.168.1.100:4873/pouchdb
npm http 200 http://192.168.1.100:4873/tmp
npm http 200 http://192.168.1.100:4873/proxyquire
npm http 200 http://192.168.1.100:4873/supertest
npm http 200 http://192.168.1.100:4873/sinon
npm http fetch 200 http://192.168.1.100:4873/express-pouchdb/-/express-pouchdb-1.0.6-thali.tgz
npm http 200 http://192.168.1.100:4873/tape-catch
npm http 200 http://192.168.1.100:4873/supertest-as-promised
npm http 200 http://192.168.1.100:4873/uuid-validate
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
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/statuses
npm http 200 http://192.168.1.100:4873/statuses
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
npm http 304 http://192.168.1.100:4873/forwarded
npm http 304 http://192.168.1.100:4873/ipaddr.js
npm http request GET http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/mime
npm http 304 http://192.168.1.100:4873/destroy
npm http 304 http://192.168.1.100:4873/mime
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/basic-auth
npm http request GET http://192.168.1.100:4873/compression
npm http request GET http://192.168.1.100:4873/cookie-parser
npm http request GET http://192.168.1.100:4873/header-case-normalizer
npm http request GET http://192.168.1.100:4873/multiparty
npm http request GET http://192.168.1.100:4873/pouchdb-all-dbs
npm http request GET http://192.168.1.100:4873/pouchdb-auth
npm http request GET http://192.168.1.100:4873/pouchdb-list
npm http request GET http://192.168.1.100:4873/pouchdb-find
npm http request GET http://192.168.1.100:4873/pouchdb-replicator
npm http request GET http://192.168.1.100:4873/pouchdb-rewrite
npm http request GET http://192.168.1.100:4873/pouchdb-security
npm http request GET http://192.168.1.100:4873/pouchdb-show
npm http request GET http://192.168.1.100:4873/pouchdb-update
npm http request GET http://192.168.1.100:4873/pouchdb-validation
npm http request GET http://192.168.1.100:4873/pouchdb-vhost
npm http request GET http://192.168.1.100:4873/pouchdb-wrappers
npm http 304 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/basic-auth
npm http 200 http://192.168.1.100:4873/cookie-parser
npm http 200 http://192.168.1.100:4873/header-case-normalizer
npm http 200 http://192.168.1.100:4873/compression
npm http 200 http://192.168.1.100:4873/multiparty
npm http 200 http://192.168.1.100:4873/pouchdb-all-dbs
npm http 200 http://192.168.1.100:4873/pouchdb-list
npm http 200 http://192.168.1.100:4873/pouchdb-auth
npm http 200 http://192.168.1.100:4873/pouchdb-replicator
npm http 200 http://192.168.1.100:4873/pouchdb-find
npm http 200 http://192.168.1.100:4873/pouchdb-security
npm http 200 http://192.168.1.100:4873/pouchdb-rewrite
npm http 200 http://192.168.1.100:4873/pouchdb-show
npm http 200 http://192.168.1.100:4873/pouchdb-update
npm http 200 http://192.168.1.100:4873/pouchdb-validation
npm http 200 http://192.168.1.100:4873/pouchdb-wrappers
npm http 200 http://192.168.1.100:4873/pouchdb-vhost
npm http request GET http://192.168.1.100:4873/setprototypeof
npm http 200 http://192.168.1.100:4873/setprototypeof
npm http request GET http://192.168.1.100:4873/compressible
npm http request GET http://192.168.1.100:4873/on-headers
npm http 200 http://192.168.1.100:4873/on-headers
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
npm http 200 http://192.168.1.100:4873/argsarray
npm http 200 http://192.168.1.100:4873/tiny-queue
npm http 200 http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/source-map
npm http 200 http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/crypto-lite
npm http request GET http://192.168.1.100:4873/base64url
npm http request GET http://192.168.1.100:4873/couchdb-calculate-session-id
npm http request GET http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http request GET http://192.168.1.100:4873/pouchdb-plugin-error
npm http request GET http://192.168.1.100:4873/pouchdb-req-http-query
npm http request GET http://192.168.1.100:4873/pouchdb-system-db
npm http request GET http://192.168.1.100:4873/secure-random
npm http request GET http://192.168.1.100:4873/promise-nodify
npm http 200 http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http 200 http://192.168.1.100:4873/couchdb-calculate-session-id
npm http 200 http://192.168.1.100:4873/base64url
npm http 200 http://192.168.1.100:4873/pouchdb-plugin-error
npm http 200 http://192.168.1.100:4873/crypto-lite
npm http 200 http://192.168.1.100:4873/pouchdb-system-db
npm http 200 http://192.168.1.100:4873/pouchdb-req-http-query
npm http 200 http://192.168.1.100:4873/secure-random
npm http 200 http://192.168.1.100:4873/promise-nodify
npm http request GET http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/meow
npm http 200 http://192.168.1.100:4873/concat-stream
npm http 200 http://192.168.1.100:4873/meow
npm http request GET http://192.168.1.100:4873/typedarray
npm http 200 http://192.168.1.100:4873/typedarray
npm http request GET http://192.168.1.100:4873/indent-string
npm http request GET http://192.168.1.100:4873/camelcase-keys
npm http 200 http://192.168.1.100:4873/indent-string
npm http 200 http://192.168.1.100:4873/camelcase-keys
npm http request GET http://192.168.1.100:4873/camelcase
npm http request GET http://192.168.1.100:4873/map-obj
npm http 200 http://192.168.1.100:4873/map-obj
npm http 200 http://192.168.1.100:4873/camelcase
npm http request GET http://192.168.1.100:4873/repeating
npm http request GET http://192.168.1.100:4873/get-stdin
npm http 200 http://192.168.1.100:4873/get-stdin
npm http 200 http://192.168.1.100:4873/repeating
npm http request GET http://192.168.1.100:4873/is-finite
npm http 200 http://192.168.1.100:4873/is-finite
npm http request GET http://192.168.1.100:4873/number-is-nan
npm http 200 http://192.168.1.100:4873/number-is-nan
npm http request GET http://192.168.1.100:4873/aproba
npm http 200 http://192.168.1.100:4873/aproba
npm http request GET http://192.168.1.100:4873/es6-promise-pool
npm http request GET http://192.168.1.100:4873/fruitdown
npm http request GET http://192.168.1.100:4873/level-write-stream
npm http request GET http://192.168.1.100:4873/localstorage-down
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/memdown
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/scope-eval
npm http request GET http://192.168.1.100:4873/pouchdb-collate
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/vuvuzela
npm http 304 http://192.168.1.100:4873/through2
npm http 200 http://192.168.1.100:4873/es6-promise-pool
npm http 200 http://192.168.1.100:4873/double-ended-queue
npm http 200 http://192.168.1.100:4873/fruitdown
npm http 200 http://192.168.1.100:4873/level-write-stream
npm http 200 http://192.168.1.100:4873/localstorage-down
npm http 200 http://192.168.1.100:4873/scope-eval
npm http 200 http://192.168.1.100:4873/memdown
npm http 200 http://192.168.1.100:4873/pouchdb-collate
npm http 200 http://192.168.1.100:4873/pouchdb-collections
npm http 200 http://192.168.1.100:4873/levelup
npm http 200 http://192.168.1.100:4873/spark-md5
npm http 200 http://192.168.1.100:4873/sublevel-pouchdb
npm http 200 http://192.168.1.100:4873/vuvuzela
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/d64
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
npm http request GET http://192.168.1.100:4873/level-errors
npm http request GET http://192.168.1.100:4873/level-iterator-stream
npm http request GET http://192.168.1.100:4873/prr
npm http request GET http://192.168.1.100:4873/semver
npm http 200 http://192.168.1.100:4873/prr
npm http 200 http://192.168.1.100:4873/level-errors
npm http 200 http://192.168.1.100:4873/level-iterator-stream
npm http 200 http://192.168.1.100:4873/level-codec
npm http 200 http://192.168.1.100:4873/deferred-leveldown
npm http 200 http://192.168.1.100:4873/semver
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
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/aws4
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/is-typedarray
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 304 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/tough-cookie
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
npm http 304 http://192.168.1.100:4873/sshpk
npm http 304 http://192.168.1.100:4873/jsprim
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
npm http request GET http://192.168.1.100:4873/couchdb-objects
npm http request GET http://192.168.1.100:4873/couchdb-eval
npm http request GET http://192.168.1.100:4873/random-uuid-v4
npm http 200 http://192.168.1.100:4873/couchdb-eval
npm http 200 http://192.168.1.100:4873/couchdb-objects
npm http 200 http://192.168.1.100:4873/random-uuid-v4
npm http request GET http://192.168.1.100:4873/is-empty
npm http 200 http://192.168.1.100:4873/is-empty
npm http request GET http://192.168.1.100:4873/is-array
npm http request GET http://192.168.1.100:4873/pouchdb-extend
npm http request GET http://192.168.1.100:4873/pouchdb-upsert
npm http 200 http://192.168.1.100:4873/is-array
npm http 200 http://192.168.1.100:4873/pouchdb-upsert
npm http 200 http://192.168.1.100:4873/pouchdb-extend
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 304 http://192.168.1.100:4873/unreachable-branch-transform
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
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/get-folder-size
npm http 200 http://192.168.1.100:4873/get-folder-size
npm http request GET http://192.168.1.100:4873/minimist
npm http 304 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/fast-future
npm http request GET http://192.168.1.100:4873/bindings
npm http 200 http://192.168.1.100:4873/fast-future
npm http 200 http://192.168.1.100:4873/bindings
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
npm http request GET http://192.168.1.100:4873/debug
npm WARN deprecated lodash@2.4.1: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
npm http request GET http://192.168.1.100:4873/deep-equal
npm http request GET http://192.168.1.100:4873/propagate
npm http request GET http://192.168.1.100:4873/chai
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
npm http request GET http://192.168.1.100:4873/fill-keys
npm http request GET http://192.168.1.100:4873/module-not-found-error
npm http 200 http://192.168.1.100:4873/fill-keys
npm http 200 http://192.168.1.100:4873/module-not-found-error
npm http request GET http://192.168.1.100:4873/is-object
npm http 200 http://192.168.1.100:4873/is-object
npm http request GET http://192.168.1.100:4873/array-uniq
npm http 304 http://192.168.1.100:4873/array-uniq
npm http request GET http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/jsonschema
npm http 304 http://192.168.1.100:4873/jsonschema
npm http request GET http://192.168.1.100:4873/util
npm http request GET http://192.168.1.100:4873/formatio
npm http request GET http://192.168.1.100:4873/lolex
npm http request GET http://192.168.1.100:4873/samsam
npm http 200 http://192.168.1.100:4873/util
npm http 200 http://192.168.1.100:4873/formatio
npm http 200 http://192.168.1.100:4873/lolex
npm http 200 http://192.168.1.100:4873/samsam
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
npm http 304 http://192.168.1.100:4873/component-bind
npm http 304 http://192.168.1.100:4873/engine.io-client
npm http 304 http://192.168.1.100:4873/component-emitter
npm http 304 http://192.168.1.100:4873/object-component
npm http 304 http://192.168.1.100:4873/socket.io-parser
npm http 304 http://192.168.1.100:4873/has-binary
npm http 304 http://192.168.1.100:4873/parseuri
npm http 304 http://192.168.1.100:4873/to-array
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
npm http 304 http://192.168.1.100:4873/ws
npm http 304 http://192.168.1.100:4873/xmlhttprequest-ssl
npm http 304 http://192.168.1.100:4873/engine.io-parser
npm http 304 http://192.168.1.100:4873/parsejson
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
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/formidable
npm http request GET http://192.168.1.100:4873/cookiejar
npm http request GET http://192.168.1.100:4873/reduce-component
npm http 304 http://192.168.1.100:4873/methods
npm http 200 http://192.168.1.100:4873/formidable
npm http 200 http://192.168.1.100:4873/reduce-component
npm http 200 http://192.168.1.100:4873/cookiejar
npm http request GET http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/mime-types
npm http request GET http://192.168.1.100:4873/mime-db
npm http 304 http://192.168.1.100:4873/mime-db
npm http request GET http://192.168.1.100:4873/defined
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/object-inspect
npm http request GET http://192.168.1.100:4873/resumer
npm http 304 http://192.168.1.100:4873/defined
npm http 304 http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/object-inspect
npm http 200 http://192.168.1.100:4873/resumer
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

```

Error: Command failed: npm WARN thali-test-server@0.0.1 No repository field.
npm WARN thali-test-server@0.0.1 No license field.
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/javascript-state-machine
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/js-extend
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/winston
npm http 304 http://192.168.1.100:4873/express
npm http 200 http://192.168.1.100:4873/ip
npm http 200 http://192.168.1.100:4873/javascript-state-machine
npm http 200 http://192.168.1.100:4873/lie
npm http 200 http://192.168.1.100:4873/body-parser
npm http 200 http://192.168.1.100:4873/long
npm http 200 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/js-extend
npm http 200 http://192.168.1.100:4873/uuid
npm http 200 http://192.168.1.100:4873/multiplex
npm http 200 http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/type-is
npm http 200 http://192.168.1.100:4873/bytes
npm http 200 http://192.168.1.100:4873/iconv-lite
npm http 200 http://192.168.1.100:4873/raw-body
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/statuses
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/statuses
npm http fetch GET http://192.168.1.100:4873/statuses/-/statuses-1.3.1.tgz
npm http fetch 200 http://192.168.1.100:4873/statuses/-/statuses-1.3.1.tgz
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
npm http 304 http://192.168.1.100:4873/forwarded
npm http 304 http://192.168.1.100:4873/ipaddr.js
npm http request GET http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/mime
npm http 304 http://192.168.1.100:4873/destroy
npm http 304 http://192.168.1.100:4873/mime
npm http request GET http://192.168.1.100:4873/immediate
npm http 200 http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/xtend
npm http 200 http://192.168.1.100:4873/xtend
npm http 200 http://192.168.1.100:4873/duplexify
npm http 200 http://192.168.1.100:4873/varint
npm http 200 http://192.168.1.100:4873/readable-stream
npm http fetch GET http://192.168.1.100:4873/readable-stream/-/readable-stream-2.2.2.tgz
npm http fetch 200 http://192.168.1.100:4873/readable-stream/-/readable-stream-2.2.2.tgz
npm http request GET http://192.168.1.100:4873/stream-shift
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http 200 http://192.168.1.100:4873/end-of-stream
npm http 200 http://192.168.1.100:4873/stream-shift
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
npm http 200 http://192.168.1.100:4873/string_decoder
npm http 200 http://192.168.1.100:4873/core-util-is
npm http 200 http://192.168.1.100:4873/buffer-shims
npm http 200 http://192.168.1.100:4873/process-nextick-args
npm http 200 http://192.168.1.100:4873/util-deprecate
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 200 http://192.168.1.100:4873/bl
npm http 200 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/caseless
npm http 200 http://192.168.1.100:4873/form-data
npm http 200 http://192.168.1.100:4873/tunnel-agent
npm http 200 http://192.168.1.100:4873/tough-cookie
npm http 200 http://192.168.1.100:4873/oauth-sign
npm http 200 http://192.168.1.100:4873/http-signature
npm http 200 http://192.168.1.100:4873/hawk
npm http 200 http://192.168.1.100:4873/aws-sign2
npm http 200 http://192.168.1.100:4873/combined-stream
npm http 200 http://192.168.1.100:4873/stringstream
npm http 200 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 200 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/lodash
npm http 200 http://192.168.1.100:4873/lodash
npm http fetch GET http://192.168.1.100:4873/lodash/-/lodash-4.17.0.tgz
npm http fetch 200 http://192.168.1.100:4873/lodash/-/lodash-4.17.0.tgz
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http 200 http://192.168.1.100:4873/chalk
npm http 200 http://192.168.1.100:4873/commander
npm http 200 http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 200 http://192.168.1.100:4873/escape-string-regexp
npm http 200 http://192.168.1.100:4873/has-ansi
npm http 200 http://192.168.1.100:4873/strip-ansi
npm http 200 http://192.168.1.100:4873/supports-color
npm http 200 http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 200 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http 200 http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 200 http://192.168.1.100:4873/generate-object-property
npm http 200 http://192.168.1.100:4873/jsonpointer
npm http 200 http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/is-property
npm http 200 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/boom
npm http 200 http://192.168.1.100:4873/boom
npm http 200 http://192.168.1.100:4873/sntp
npm http 200 http://192.168.1.100:4873/cryptiles
npm http 200 http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/ctype
npm http 200 http://192.168.1.100:4873/assert-plus
npm http 200 http://192.168.1.100:4873/ctype
npm http 200 http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/punycode
npm http 200 http://192.168.1.100:4873/punycode
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/jsonschema
npm http 304 http://192.168.1.100:4873/object-assign
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
npm http request GET http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/js2xmlparser
npm http request GET http://192.168.1.100:4873/requizzle
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/marked
npm http request GET http://192.168.1.100:4873/underscore
npm http request GET http://192.168.1.100:4873/wrench
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 200 http://192.168.1.100:4873/catharsis
npm http 200 http://192.168.1.100:4873/esprima
npm http 200 http://192.168.1.100:4873/requizzle
npm http 200 http://192.168.1.100:4873/strip-json-comments
npm http 200 http://192.168.1.100:4873/js2xmlparser
npm http 200 http://192.168.1.100:4873/marked
npm http 200 http://192.168.1.100:4873/underscore
npm http 200 http://192.168.1.100:4873/wrench
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
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/express-pouchdb
npm http request GET http://192.168.1.100:4873/bn.js
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/leveldown-mobile
npm http request GET http://192.168.1.100:4873/request-promise
npm http request GET http://192.168.1.100:4873/pouchdb
npm http request GET http://192.168.1.100:4873/pouchdb-size
npm http request GET http://192.168.1.100:4873/tmp
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/proxyquire
npm http request GET http://192.168.1.100:4873/nock
npm http request GET http://192.168.1.100:4873/sinon
npm http request GET http://192.168.1.100:4873/supertest
npm http request GET http://192.168.1.100:4873/supertest-as-promised
npm http request GET http://192.168.1.100:4873/tape-catch
npm http request GET http://192.168.1.100:4873/uuid-validate
npm http request GET http://192.168.1.100:4873/tape
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/child-process-promise
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/js-extend
npm http 304 http://192.168.1.100:4873/multiplex
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/randomstring
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/socket.io-client
npm http 200 http://192.168.1.100:4873/express-pouchdb
npm http 200 http://192.168.1.100:4873/leveldown-mobile
npm http 200 http://192.168.1.100:4873/pouchdb-size
npm http 304 http://192.168.1.100:4873/urlsafe-base64
npm http 304 http://192.168.1.100:4873/uuid
npm http 200 http://192.168.1.100:4873/request-promise
npm http 200 http://192.168.1.100:4873/bn.js
npm http fetch GET http://192.168.1.100:4873/express-pouchdb/-/express-pouchdb-1.0.6-thali.tgz
npm http 200 http://192.168.1.100:4873/pouchdb
npm http 200 http://192.168.1.100:4873/tmp
npm http 200 http://192.168.1.100:4873/proxyquire
npm http 200 http://192.168.1.100:4873/supertest
npm http 200 http://192.168.1.100:4873/sinon
npm http fetch 200 http://192.168.1.100:4873/express-pouchdb/-/express-pouchdb-1.0.6-thali.tgz
npm http 200 http://192.168.1.100:4873/tape-catch
npm http 200 http://192.168.1.100:4873/supertest-as-promised
npm http 200 http://192.168.1.100:4873/uuid-validate
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
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/statuses
npm http 200 http://192.168.1.100:4873/statuses
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
npm http 304 http://192.168.1.100:4873/forwarded
npm http 304 http://192.168.1.100:4873/ipaddr.js
npm http request GET http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/mime
npm http 304 http://192.168.1.100:4873/destroy
npm http 304 http://192.168.1.100:4873/mime
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/basic-auth
npm http request GET http://192.168.1.100:4873/compression
npm http request GET http://192.168.1.100:4873/cookie-parser
npm http request GET http://192.168.1.100:4873/header-case-normalizer
npm http request GET http://192.168.1.100:4873/multiparty
npm http request GET http://192.168.1.100:4873/pouchdb-all-dbs
npm http request GET http://192.168.1.100:4873/pouchdb-auth
npm http request GET http://192.168.1.100:4873/pouchdb-list
npm http request GET http://192.168.1.100:4873/pouchdb-find
npm http request GET http://192.168.1.100:4873/pouchdb-replicator
npm http request GET http://192.168.1.100:4873/pouchdb-rewrite
npm http request GET http://192.168.1.100:4873/pouchdb-security
npm http request GET http://192.168.1.100:4873/pouchdb-show
npm http request GET http://192.168.1.100:4873/pouchdb-update
npm http request GET http://192.168.1.100:4873/pouchdb-validation
npm http request GET http://192.168.1.100:4873/pouchdb-vhost
npm http request GET http://192.168.1.100:4873/pouchdb-wrappers
npm http 304 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/basic-auth
npm http 200 http://192.168.1.100:4873/cookie-parser
npm http 200 http://192.168.1.100:4873/header-case-normalizer
npm http 200 http://192.168.1.100:4873/compression
npm http 200 http://192.168.1.100:4873/multiparty
npm http 200 http://192.168.1.100:4873/pouchdb-all-dbs
npm http 200 http://192.168.1.100:4873/pouchdb-list
npm http 200 http://192.168.1.100:4873/pouchdb-auth
npm http 200 http://192.168.1.100:4873/pouchdb-replicator
npm http 200 http://192.168.1.100:4873/pouchdb-find
npm http 200 http://192.168.1.100:4873/pouchdb-security
npm http 200 http://192.168.1.100:4873/pouchdb-rewrite
npm http 200 http://192.168.1.100:4873/pouchdb-show
npm http 200 http://192.168.1.100:4873/pouchdb-update
npm http 200 http://192.168.1.100:4873/pouchdb-validation
npm http 200 http://192.168.1.100:4873/pouchdb-wrappers
npm http 200 http://192.168.1.100:4873/pouchdb-vhost
npm http request GET http://192.168.1.100:4873/setprototypeof
npm http 200 http://192.168.1.100:4873/setprototypeof
npm http request GET http://192.168.1.100:4873/compressible
npm http request GET http://192.168.1.100:4873/on-headers
npm http 200 http://192.168.1.100:4873/on-headers
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
npm http 200 http://192.168.1.100:4873/argsarray
npm http 200 http://192.168.1.100:4873/tiny-queue
npm http 200 http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/source-map
npm http 200 http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/crypto-lite
npm http request GET http://192.168.1.100:4873/base64url
npm http request GET http://192.168.1.100:4873/couchdb-calculate-session-id
npm http request GET http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http request GET http://192.168.1.100:4873/pouchdb-plugin-error
npm http request GET http://192.168.1.100:4873/pouchdb-req-http-query
npm http request GET http://192.168.1.100:4873/pouchdb-system-db
npm http request GET http://192.168.1.100:4873/secure-random
npm http request GET http://192.168.1.100:4873/promise-nodify
npm http 200 http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http 200 http://192.168.1.100:4873/couchdb-calculate-session-id
npm http 200 http://192.168.1.100:4873/base64url
npm http 200 http://192.168.1.100:4873/pouchdb-plugin-error
npm http 200 http://192.168.1.100:4873/crypto-lite
npm http 200 http://192.168.1.100:4873/pouchdb-system-db
npm http 200 http://192.168.1.100:4873/pouchdb-req-http-query
npm http 200 http://192.168.1.100:4873/secure-random
npm http 200 http://192.168.1.100:4873/promise-nodify
npm http request GET http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/meow
npm http 200 http://192.168.1.100:4873/concat-stream
npm http 200 http://192.168.1.100:4873/meow
npm http request GET http://192.168.1.100:4873/typedarray
npm http 200 http://192.168.1.100:4873/typedarray
npm http request GET http://192.168.1.100:4873/indent-string
npm http request GET http://192.168.1.100:4873/camelcase-keys
npm http 200 http://192.168.1.100:4873/indent-string
npm http 200 http://192.168.1.100:4873/camelcase-keys
npm http request GET http://192.168.1.100:4873/camelcase
npm http request GET http://192.168.1.100:4873/map-obj
npm http 200 http://192.168.1.100:4873/map-obj
npm http 200 http://192.168.1.100:4873/camelcase
npm http request GET http://192.168.1.100:4873/repeating
npm http request GET http://192.168.1.100:4873/get-stdin
npm http 200 http://192.168.1.100:4873/get-stdin
npm http 200 http://192.168.1.100:4873/repeating
npm http request GET http://192.168.1.100:4873/is-finite
npm http 200 http://192.168.1.100:4873/is-finite
npm http request GET http://192.168.1.100:4873/number-is-nan
npm http 200 http://192.168.1.100:4873/number-is-nan
npm http request GET http://192.168.1.100:4873/aproba
npm http 200 http://192.168.1.100:4873/aproba
npm http request GET http://192.168.1.100:4873/es6-promise-pool
npm http request GET http://192.168.1.100:4873/fruitdown
npm http request GET http://192.168.1.100:4873/level-write-stream
npm http request GET http://192.168.1.100:4873/localstorage-down
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/memdown
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/scope-eval
npm http request GET http://192.168.1.100:4873/pouchdb-collate
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/vuvuzela
npm http 304 http://192.168.1.100:4873/through2
npm http 200 http://192.168.1.100:4873/es6-promise-pool
npm http 200 http://192.168.1.100:4873/double-ended-queue
npm http 200 http://192.168.1.100:4873/fruitdown
npm http 200 http://192.168.1.100:4873/level-write-stream
npm http 200 http://192.168.1.100:4873/localstorage-down
npm http 200 http://192.168.1.100:4873/scope-eval
npm http 200 http://192.168.1.100:4873/memdown
npm http 200 http://192.168.1.100:4873/pouchdb-collate
npm http 200 http://192.168.1.100:4873/pouchdb-collections
npm http 200 http://192.168.1.100:4873/levelup
npm http 200 http://192.168.1.100:4873/spark-md5
npm http 200 http://192.168.1.100:4873/sublevel-pouchdb
npm http 200 http://192.168.1.100:4873/vuvuzela
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/d64
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
npm http request GET http://192.168.1.100:4873/level-errors
npm http request GET http://192.168.1.100:4873/level-iterator-stream
npm http request GET http://192.168.1.100:4873/prr
npm http request GET http://192.168.1.100:4873/semver
npm http 200 http://192.168.1.100:4873/prr
npm http 200 http://192.168.1.100:4873/level-errors
npm http 200 http://192.168.1.100:4873/level-iterator-stream
npm http 200 http://192.168.1.100:4873/level-codec
npm http 200 http://192.168.1.100:4873/deferred-leveldown
npm http 200 http://192.168.1.100:4873/semver
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
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/aws4
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/is-typedarray
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 304 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/tough-cookie
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
npm http 304 http://192.168.1.100:4873/sshpk
npm http 304 http://192.168.1.100:4873/jsprim
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
npm http request GET http://192.168.1.100:4873/couchdb-objects
npm http request GET http://192.168.1.100:4873/couchdb-eval
npm http request GET http://192.168.1.100:4873/random-uuid-v4
npm http 200 http://192.168.1.100:4873/couchdb-eval
npm http 200 http://192.168.1.100:4873/couchdb-objects
npm http 200 http://192.168.1.100:4873/random-uuid-v4
npm http request GET http://192.168.1.100:4873/is-empty
npm http 200 http://192.168.1.100:4873/is-empty
npm http request GET http://192.168.1.100:4873/is-array
npm http request GET http://192.168.1.100:4873/pouchdb-extend
npm http request GET http://192.168.1.100:4873/pouchdb-upsert
npm http 200 http://192.168.1.100:4873/is-array
npm http 200 http://192.168.1.100:4873/pouchdb-upsert
npm http 200 http://192.168.1.100:4873/pouchdb-extend
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 304 http://192.168.1.100:4873/unreachable-branch-transform
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
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/get-folder-size
npm http 200 http://192.168.1.100:4873/get-folder-size
npm http request GET http://192.168.1.100:4873/minimist
npm http 304 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/fast-future
npm http request GET http://192.168.1.100:4873/bindings
npm http 200 http://192.168.1.100:4873/fast-future
npm http 200 http://192.168.1.100:4873/bindings
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
npm http request GET http://192.168.1.100:4873/debug
npm WARN deprecated lodash@2.4.1: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
npm http request GET http://192.168.1.100:4873/deep-equal
npm http request GET http://192.168.1.100:4873/propagate
npm http request GET http://192.168.1.100:4873/chai
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
npm http request GET http://192.168.1.100:4873/fill-keys
npm http request GET http://192.168.1.100:4873/module-not-found-error
npm http 200 http://192.168.1.100:4873/fill-keys
npm http 200 http://192.168.1.100:4873/module-not-found-error
npm http request GET http://192.168.1.100:4873/is-object
npm http 200 http://192.168.1.100:4873/is-object
npm http request GET http://192.168.1.100:4873/array-uniq
npm http 304 http://192.168.1.100:4873/array-uniq
npm http request GET http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/jsonschema
npm http 304 http://192.168.1.100:4873/jsonschema
npm http request GET http://192.168.1.100:4873/util
npm http request GET http://192.168.1.100:4873/formatio
npm http request GET http://192.168.1.100:4873/lolex
npm http request GET http://192.168.1.100:4873/samsam
npm http 200 http://192.168.1.100:4873/util
npm http 200 http://192.168.1.100:4873/formatio
npm http 200 http://192.168.1.100:4873/lolex
npm http 200 http://192.168.1.100:4873/samsam
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
npm http 304 http://192.168.1.100:4873/component-bind
npm http 304 http://192.168.1.100:4873/engine.io-client
npm http 304 http://192.168.1.100:4873/component-emitter
npm http 304 http://192.168.1.100:4873/object-component
npm http 304 http://192.168.1.100:4873/socket.io-parser
npm http 304 http://192.168.1.100:4873/has-binary
npm http 304 http://192.168.1.100:4873/parseuri
npm http 304 http://192.168.1.100:4873/to-array
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
npm http 304 http://192.168.1.100:4873/ws
npm http 304 http://192.168.1.100:4873/xmlhttprequest-ssl
npm http 304 http://192.168.1.100:4873/engine.io-parser
npm http 304 http://192.168.1.100:4873/parsejson
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
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/formidable
npm http request GET http://192.168.1.100:4873/cookiejar
npm http request GET http://192.168.1.100:4873/reduce-component
npm http 304 http://192.168.1.100:4873/methods
npm http 200 http://192.168.1.100:4873/formidable
npm http 200 http://192.168.1.100:4873/reduce-component
npm http 200 http://192.168.1.100:4873/cookiejar
npm http request GET http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/mime-types
npm http request GET http://192.168.1.100:4873/mime-db
npm http 304 http://192.168.1.100:4873/mime-db
npm http request GET http://192.168.1.100:4873/defined
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/object-inspect
npm http request GET http://192.168.1.100:4873/resumer
npm http 304 http://192.168.1.100:4873/defined
npm http 304 http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/object-inspect
npm http 200 http://192.168.1.100:4873/resumer
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
