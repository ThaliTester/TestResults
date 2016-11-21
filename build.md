#### Test (Fail) 93765317 Build Logs


```
Your branch is up-to-date with 'origin/master'.
Branch iOS set up to track remote branch iOS from origin.
Already up-to-date.

Already on 'master'
Switched to a new branch 'iOS'
Note: checking out '3a8cc8a'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at 3a8cc8a... - replace 'npm install'  with 'jx install' where npm isn't valid - replace 'jx npm install' with 'jx install'

```

```
start build.sh
Cordova version:
6.3.1
start setUpDesktop.sh
start preparing TestServer
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

end preparing TestServer
start installing Thali root
[33mPreparing NPM for JXcore (v0.3.1.6) for the first run[39m
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
│ │   └── lodash@4.17.2 
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
│ ├─┬ mime-types@2.1.13 
│ │ └── mime-db@1.25.0 
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

Environment validated
end installing Thali install
start preparing 
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

end prepating 
end setUpDesktop.sh
run desktop tests
2016-11-21 10:33:27 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
2016-11-21 10:33:27 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreateNativeListener.js'
2016-11-21 10:33:27 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js'
2016-11-21 10:33:27 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js'
2016-11-21 10:33:27 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
2016-11-21 10:33:27 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
2016-11-21 10:33:27 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testNativeMethod.js'
2016-11-21 10:33:27 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
2016-11-21 10:33:27 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBGenerator.js'
2016-11-21 10:33:27 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPromiseQueue.js'
2016-11-21 10:33:27 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testTests.js'
2016-11-21 10:33:27 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManager.js'
2016-11-21 10:33:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
2016-11-21 10:33:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js'
2016-11-21 10:33:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNative.js'
2016-11-21 10:33:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
2016-11-21 10:33:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
2016-11-21 10:33:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
2016-11-21 10:33:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
2016-11-21 10:33:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotification.js'
2016-11-21 10:33:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationAction.js'
2016-11-21 10:33:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
2016-11-21 10:33:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationClient.js'
2016-11-21 10:33:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationLocal.js'
2016-11-21 10:33:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationServer.js'
2016-11-21 10:33:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerAction.js'
2016-11-21 10:33:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerDictionary.js'
2016-11-21 10:33:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
2016-11-21 10:33:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
2016-11-21 10:33:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
2016-11-21 10:33:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
2016-11-21 10:33:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
2016-11-21 10:33:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
2016-11-21 10:33:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
2016-11-21 10:33:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
2016-11-21 10:33:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
2016-11-21 10:33:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliTcpServersManager.js'
2016-11-21 10:33:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
2016-11-21 10:33:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testUsn.js'
2016-11-21 10:33:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-21 10:33:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-21 10:33:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-21 10:33:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-21 10:33:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-21 10:33:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
TAP version 13
# setup
# calling createNativeListener directly rejects
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'listening 49673'
ok 1 Should throw
# teardown
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - close'
# setup
# emits incomingConnectionState
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'listening 49675'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 2 initial connection state should be CONNECTED
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 3 final connection state should be DISCONNECTED
# teardown
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - close'
# setup
# emits routerPortConnectionFailed
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'listening 49678'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
ok 4 tried to connect to right port
ok 5 failed due to refused connection
ok 6 routerPortConnectionFailed is emitted
# teardown
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# setup
# native server connections all up
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'listening 49682'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
ok 7 Send/recvd #1 should be equal length
ok 8 Send/recvd #1 should be same
ok 9 Send/recvd #2 should be equal length
ok 10 Send/recvd #2 should be same
ok 11 Should be exactly 2 client sockets
# teardown
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# setup
# native server - closing incoming stream cleans outgoing socket
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'listening 49687'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
ok 12 socket shouldn't close until after stream
ok 13 incoming remains open
# teardown
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# setup
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# native server - closing incoming connection cleans outgoing socket
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'listening 49691'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 14 we should not have gotten an error
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 15 socket shouldn't close until after incoming
ok 16 incoming is cleaned up
# teardown
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - close'
# setup
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# native server - closing outgoing socket cleans associated mux stream
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'listening 49695'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
ok 17 stream was closed
ok 18 incoming should survive
ok 19 mux should have no streams
# teardown
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# setup
# native server - closing the whole server cleans everything up
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'listening 49699'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 20 we should not have gotten an error
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 21 Buffers are identical
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 22 native server is nulled out
ok 23 native server should be closed
ok 24 incoming has been removed
ok 25 Incoming should be done
ok 26 The mux object should be closed
ok 27 The mux stream should be closed
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# teardown
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# setup
# native server - we can get a ton of connections and data through and still clean up the server completely
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'listening 49703'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
ok 28 native server is nulled out
ok 29 native server should be closed
ok 30 incoming has been removed
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# teardown
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# native server - simulate mux failure, make sure everything is cleaned up
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'listening 49755'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 31 we should not have gotten an error
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 32 Buffers are identical
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 33 server should be fine
ok 34 server should be open
ok 35 incoming has been removed
ok 36 The mux object should be closed
ok 37 The mux stream should be closed
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# teardown
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - close'
# setup
# native server - timing out the incoming connection cleans everything up
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'listening 49759'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 38 we should not have gotten an error
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 39 Buffers are identical
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 40 server should be fine
ok 41 server should be open
ok 42 incoming has been removed
ok 43 The mux object should be closed
ok 44 The mux stream should be closed
# teardown
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - close'
# setup
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# calling createPeerListener without calling start produces error
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'listening 49764'
# teardown
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# calling createPeerListener after calling stop produces error
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'listening 49767'
# teardown
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# can call createPeerListener (pleaseConnect === false)
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'listening 49770'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'creating new server for peerId'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peerId listening on 49771'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 45 port must be in range
# teardown
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peerId'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# calling createPeerListener (pleaseConnect === true) with unknown peer is error
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'listening 49774'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'creating new server for peerId'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peerId listening on 49775'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Issuing callNative for peerId'
2016-11-21 10:33:28 - WARN createPeerListener: 'callNative for peerId failed with Unknown Peer'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'We are emitting failedConnection with error "Error: Unknown Peer" and peerIdentifier "peerId"'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Will try to recreate server for peerId'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peerId'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'creating new server for peerId'
ok 46 should get error
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peerId listening on 49776'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peerId and portNumber 49776'
# teardown
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peerId'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# calling createPeerListener twice with same peerIdentifier should return the same port
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'listening 49779'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49780'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 47 port values should be the same
# teardown
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - closing connection to native listener closes everything and triggers new listener
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'listening 49783'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'creating new server for peer2'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 49784'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer2 - 0 - got a new incoming connection'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Issuing callNative for peer2'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'callNative for peer2 connected'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer2'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 48 Data should be of same length and content
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer2 - finish'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer2 - 0 - close'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer2 - finish'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer2 - 0 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer2 - close'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'We are emitting failedConnection with error "Error: Outgoing closed, recreating connection" and peerIdentifier "peer2"'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Will try to recreate server for peer2'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer2 - close'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer2'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'creating new server for peer2'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 49789'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer2 and portNumber 49789'
ok 49 same peer ID
ok 50 different ports
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
# teardown
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer2'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# createPeerListener - closing mux closes listener and triggers a new listener
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'listening 49792'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'creating new server for peer2'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 49793'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer2 - 0 - got a new incoming connection'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Issuing callNative for peer2'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'callNative for peer2 connected'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer2'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 51 Data should be of same length and content
2016-11-21 10:33:28 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer2 - 0 - close'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer2 - close'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer2 - finish'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer2 - finish'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer2 - 0 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'We are emitting failedConnection with error "Error: Outgoing closed, recreating connection" and peerIdentifier "peer2"'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Will try to recreate server for peer2'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer2 - close'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer2'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'creating new server for peer2'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 49798'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer2 and portNumber 49798'
ok 52 same peer ID
ok 53 different ports
# teardown
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer2'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# peerListener - forwardConnection, pleaseConnect === true - no native server
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Creating Native Server'
ok 54 Can call startUpdateAdvertisingAndListening without error
ok 55 Can call startListeningForAdvertisements without error
2016-11-21 10:33:28 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'listening 49801'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49802'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'We are emitting failedConnection with error "Error: Cannot Connect To Peer" and peerIdentifier "peer1"'
ok 56 reason should be as expected
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Will try to recreate server for peer1'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49804'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer1 and portNumber 49804'
# teardown
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# peerListener - forwardConnection, pleaseConnect === false - no native server
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Creating Native Server'
ok 57 Can call startUpdateAdvertisingAndListening without error
ok 58 Can call startListeningForAdvertisements without error
2016-11-21 10:33:28 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'listening 49807'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49808'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 59 peerPort should not be nativePort
2016-11-21 10:33:28 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'We are emitting failedConnection with error "Error: Cannot Connect To Peer" and peerIdentifier "peer1"'
ok 60 Should not get event until connection is made
ok 61 reason should be as expected
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Will try to recreate server for peer1'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - finish'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49811'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer1 and portNumber 49811'
# teardown
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
# setup
# peerListener - forwardConnection, pleaseConnect === true - with native server
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Creating Native Server'
ok 62 Can call startUpdateAdvertisingAndListening without error
ok 63 Can call startListeningForAdvertisements without error
2016-11-21 10:33:28 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'listening 49814'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49815'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
ok 64 Should get spontaneous connection
ok 65 peerPort != nativePort
# teardown
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
2016-11-21 10:33:28 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# peerListener - forwardConnection, pleaseConnect === false - with native server
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Creating Native Server'
ok 66 Can call startUpdateAdvertisingAndListening without error
ok 67 Can call startListeningForAdvertisements without error
2016-11-21 10:33:28 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'listening 49819'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49820'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 68 peerPort != nativePort
2016-11-21 10:33:28 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer1 - close'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - close'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
ok 69 Should not get unexpected connection
# teardown
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer1 - 0 - close'
# setup
2016-11-21 10:33:28 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# peerListener - forwardConnection, pleaseConnect === false - with native server and data transfer
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'listening 49825'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49826'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer1 - close'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - close'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 70 Data should be of same length and content
ok 71 Data should be of same length and content
# teardown
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer1 - 0 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 10:33:28 - WARN createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 -  error Error: read ECONNRESET'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - close'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# setup
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer1 - close'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# createPeerListener is idempotent
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Creating Native Server'
ok 72 Can call startUpdateAdvertisingAndListening without error
ok 73 Can call startListeningForAdvertisements without error
2016-11-21 10:33:28 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'listening 49832'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49833'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 74 Second call to existing peerListener returns existing port
# teardown
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - pleaseConnect === true, failed connection rejects promise
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Creating Native Server'
ok 75 Can call startUpdateAdvertisingAndListening without error
ok 76 Can call startListeningForAdvertisements without error
2016-11-21 10:33:28 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'listening 49836'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49837'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 10:33:28 - WARN createPeerListener: 'callNative for peer1 failed with a nasty error'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'We are emitting failedConnection with error "Error: a nasty error" and peerIdentifier "peer1"'
ok 77 got our failed connection
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Will try to recreate server for peer1'
ok 78 failed connection should reject with error
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49838'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer1 and portNumber 49838'
# teardown
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - pleaseConnect === true, connection resolves promise
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Creating Native Server'
ok 79 Can call startUpdateAdvertisingAndListening without error
ok 80 Can call startListeningForAdvertisements without error
2016-11-21 10:33:28 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'listening 49841'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49842'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
ok 81 Should get spontaneous connection
ok 82 promise should resolve
# teardown
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
2016-11-21 10:33:28 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# peerListener - reverseConnection, pleaseConnect === true
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Creating Native Server'
ok 83 Can call startUpdateAdvertisingAndListening without error
ok 84 Can call startListeningForAdvertisements without error
2016-11-21 10:33:28 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'listening 49846'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49847'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-21 10:33:28 - WARN createPeerListener: 'was expecting a forward connection to be made'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'We are emitting failedConnection with error "Error: Cannot Connect To Peer" and peerIdentifier "peer1"'
ok 85 reason should be as expected
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Will try to recreate server for peer1'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49848'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer1 and portNumber 49848'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer1 - close'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - close'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# teardown
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# peerListener - reverseConnection, pleaseConnect === false - no incoming
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Creating Native Server'
ok 86 Can call startUpdateAdvertisingAndListening without error
ok 87 Can call startListeningForAdvertisements without error
2016-11-21 10:33:28 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'listening 49851'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49852'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 88 peerPort should not be nativePort
2016-11-21 10:33:28 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'looking up mux for client port:  0'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'timed out waiting for incoming connection'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'reverse connection'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'looking up mux for client port:  0'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'no mux found'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'We are emitting failedConnection with error "Error: Incoming connection died" and peerIdentifier "peer1"'
ok 89 should not get event until connection is made
ok 90 reason should be as expected
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Will try to recreate server for peer1'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client - is already closed'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49854'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer1 and portNumber 49854'
# teardown
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
# setup
# peerListener - reverseConnection, pleaseConnect === false - with incoming
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Creating Native Server'
ok 91 Can call startUpdateAdvertisingAndListening without error
ok 92 Can call startListeningForAdvertisements without error
2016-11-21 10:33:28 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'listening 49857'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49858'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'looking up mux for client port:  49860'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'reverse connection'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'looking up mux for client port:  49860'
ok 93 sent and received should be the same
# teardown
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer1 - 0 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# setup
# peerListener - reverseConnection, pleaseConnect === false - no server
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Creating Native Server'
ok 94 Can call startUpdateAdvertisingAndListening without error
ok 95 Can call startListeningForAdvertisements without error
2016-11-21 10:33:28 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'listening 49863'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49864'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'looking up mux for client port:  49866'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'timed out waiting for incoming connection'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'reverse connection'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'looking up mux for client port:  49866'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'no mux found'
2016-11-21 10:33:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'We are emitting failedConnection with error "Error: Incoming connection died" and peerIdentifier "peer1"'
not ok 96 connection shouldn't fail
  ---
    operator: fail
    at: ThaliTcpServersManager.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:776:9)
  ...
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Will try to recreate server for peer1'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client - is already closed'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49867'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer1 and portNumber 49867'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 10:33:28 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-21 10:33:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
ok 97 should get routerPortConnectionFailed
2016-11-21 10:33:28 - ERROR SimpleThaliTape: 'test failed, name: 'peerListener - reverseConnection, pleaseConnect === false - no server''
2016-11-21 10:33:28 - ERROR TestsProcess: 'uncaught promise rejection, error: 'Error: test failed, name: 'peerListener - reverseConnection, pleaseConnect === false - no server'', stack: 'Error: test failed, name: 'peerListener - reverseConnection, pleaseConnect === false - no server'
    at Test.endHandler (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/SimpleTape.js:139:20)
    at Test.g (events.js:160:16)
    at Test.emit (events.js:98:20)
    at Test.bound [as emit] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:62:32)
    at Test._end (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:145:27)
    at Test.bound [as _end] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:62:32)
    at Test.end (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:133:10)
    at Test.bound [as end] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:62:32)
    at ThaliTcpServersManager.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:783:9)
    at ThaliTcpServersManager.emit (events.js:82:17)
    at Socket.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/thali/NextGeneration/mux/createNativeListener.js:292:16)
    at Socket.emit (events.js:82:17)
    at net.js:398:14
    at process._tickCallback (node.js:924:13)''
2016-11-21 10:33:28 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
[0;31merror: command 'jx runTests.js --networkType WIFI' failed with code 1, file 'build.sh' on line 57[0m
./build.sh CI FAILED - build.sh failure[0m

npm WARN thali-test-server@0.0.1 No repository field.
npm WARN thali-test-server@0.0.1 No license field.
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/javascript-state-machine
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/js-extend
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/express
npm http 200 http://192.168.1.100:4873/ip
npm http 200 http://192.168.1.100:4873/javascript-state-machine
npm http 200 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/uuid
npm http 200 http://192.168.1.100:4873/long
npm http 200 http://192.168.1.100:4873/body-parser
npm http 200 http://192.168.1.100:4873/lie
npm http 200 http://192.168.1.100:4873/multiplex
npm http 304 http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/js-extend
npm http 200 http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/depd
npm http 200 http://192.168.1.100:4873/bytes
npm http 304 http://192.168.1.100:4873/http-errors
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
npm http fetch GET http://192.168.1.100:4873/statuses/-/statuses-1.3.1.tgz
npm http fetch 200 http://192.168.1.100:4873/statuses/-/statuses-1.3.1.tgz
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
npm http request GET http://192.168.1.100:4873/cookie-signature
npm http request GET http://192.168.1.100:4873/escape-html
npm http request GET http://192.168.1.100:4873/cookie
npm http request GET http://192.168.1.100:4873/finalhandler
npm http request GET http://192.168.1.100:4873/etag
npm http request GET http://192.168.1.100:4873/fresh
npm http request GET http://192.168.1.100:4873/merge-descriptors
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/parseurl
npm http request GET http://192.168.1.100:4873/proxy-addr
npm http request GET http://192.168.1.100:4873/path-to-regexp
npm http request GET http://192.168.1.100:4873/range-parser
npm http request GET http://192.168.1.100:4873/send
npm http request GET http://192.168.1.100:4873/serve-static
npm http request GET http://192.168.1.100:4873/utils-merge
npm http request GET http://192.168.1.100:4873/vary
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/finalhandler
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
npm http 304 http://192.168.1.100:4873/destroy
npm http 304 http://192.168.1.100:4873/mime
npm http request GET http://192.168.1.100:4873/immediate
npm http 200 http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/varint
npm http 200 http://192.168.1.100:4873/varint
npm http 200 http://192.168.1.100:4873/xtend
npm http 200 http://192.168.1.100:4873/duplexify
npm http 200 http://192.168.1.100:4873/readable-stream
npm http fetch GET http://192.168.1.100:4873/readable-stream/-/readable-stream-2.2.2.tgz
npm http fetch 200 http://192.168.1.100:4873/readable-stream/-/readable-stream-2.2.2.tgz
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/stream-shift
npm http 200 http://192.168.1.100:4873/end-of-stream
npm http 200 http://192.168.1.100:4873/stream-shift
npm http request GET http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/wrappy
npm http 304 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/string_decoder
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http request GET http://192.168.1.100:4873/core-util-is
npm http 304 http://192.168.1.100:4873/isarray
npm http 200 http://192.168.1.100:4873/string_decoder
npm http 200 http://192.168.1.100:4873/process-nextick-args
npm http 200 http://192.168.1.100:4873/util-deprecate
npm http 200 http://192.168.1.100:4873/buffer-shims
npm http 200 http://192.168.1.100:4873/core-util-is
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/har-validator
npm http 200 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/bl
npm http 200 http://192.168.1.100:4873/caseless
npm http 200 http://192.168.1.100:4873/json-stringify-safe
npm http 200 http://192.168.1.100:4873/form-data
npm http 200 http://192.168.1.100:4873/tunnel-agent
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 200 http://192.168.1.100:4873/http-signature
npm http 200 http://192.168.1.100:4873/oauth-sign
npm http 200 http://192.168.1.100:4873/tough-cookie
npm http 200 http://192.168.1.100:4873/aws-sign2
npm http 200 http://192.168.1.100:4873/stringstream
npm http 200 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/hawk
npm http 200 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 200 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/lodash
npm http 200 http://192.168.1.100:4873/lodash
npm http fetch GET http://192.168.1.100:4873/lodash/-/lodash-4.17.2.tgz
npm http fetch 200 http://192.168.1.100:4873/lodash/-/lodash-4.17.2.tgz
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http 200 http://192.168.1.100:4873/chalk
npm http 200 http://192.168.1.100:4873/commander
npm http 200 http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 200 http://192.168.1.100:4873/has-ansi
npm http 200 http://192.168.1.100:4873/strip-ansi
npm http 200 http://192.168.1.100:4873/supports-color
npm http 200 http://192.168.1.100:4873/escape-string-regexp
npm http 200 http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 200 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http 200 http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http 200 http://192.168.1.100:4873/generate-function
npm http 200 http://192.168.1.100:4873/generate-object-property
npm http 200 http://192.168.1.100:4873/jsonpointer
npm http request GET http://192.168.1.100:4873/is-property
npm http 200 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/boom
npm http 200 http://192.168.1.100:4873/cryptiles
npm http 200 http://192.168.1.100:4873/boom
npm http 200 http://192.168.1.100:4873/hoek
npm http 200 http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/asn1
npm http 200 http://192.168.1.100:4873/asn1
npm http 200 http://192.168.1.100:4873/ctype
npm http 200 http://192.168.1.100:4873/assert-plus
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
npm http 304 http://192.168.1.100:4873/eyes
npm http 304 http://192.168.1.100:4873/cycle
npm http 304 http://192.168.1.100:4873/colors
npm http 304 http://192.168.1.100:4873/pkginfo
npm http 304 http://192.168.1.100:4873/stack-trace
npm http request GET http://192.168.1.100:4873/jsdoc
npm http 200 http://192.168.1.100:4873/jsdoc
npm http request GET http://192.168.1.100:4873/underscore
npm http request GET http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/catharsis
npm http request GET http://192.168.1.100:4873/marked
npm http request GET http://192.168.1.100:4873/js2xmlparser
npm http request GET http://192.168.1.100:4873/requizzle
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/wrench
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 200 http://192.168.1.100:4873/underscore
npm http 200 http://192.168.1.100:4873/esprima
npm http 200 http://192.168.1.100:4873/js2xmlparser
npm http 200 http://192.168.1.100:4873/catharsis
npm http 200 http://192.168.1.100:4873/marked
npm http 200 http://192.168.1.100:4873/requizzle
npm http 200 http://192.168.1.100:4873/strip-json-comments
npm http 200 http://192.168.1.100:4873/wrench
npm WARN deprecated wrench@1.5.9: wrench.js is deprecated! You should check out fs-extra (https://github.com/jprichardson/node-fs-extra) for any operations you were using wrench for. Thanks for all the usage over the years.
npm http fetch 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http request GET http://192.168.1.100:4873/underscore-contrib
npm http 200 http://192.168.1.100:4873/underscore-contrib
npm WARN prefer global marked@0.3.6 should be installed with -g
npm WARN install@0.0.1 No repository field.
thali/install/setUpDesktop.sh: line 40: test/www/jxcore: No such file or directory
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/child-process-promise
npm http request GET http://192.168.1.100:4873/bn.js
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/express-pouchdb
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/leveldown-mobile
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/pouchdb-size
npm http request GET http://192.168.1.100:4873/pouchdb
npm http request GET http://192.168.1.100:4873/nock
npm http request GET http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/proxyquire
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/request-promise
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/sinon
npm http request GET http://192.168.1.100:4873/supertest
npm http request GET http://192.168.1.100:4873/supertest-as-promised
npm http request GET http://192.168.1.100:4873/tape
npm http request GET http://192.168.1.100:4873/tape-catch
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/tmp
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/uuid-validate
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/child-process-promise
npm http 304 http://192.168.1.100:4873/concat-map
npm http 200 http://192.168.1.100:4873/bn.js
npm http 304 http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/js-extend
npm http 200 http://192.168.1.100:4873/express-pouchdb
npm http fetch GET http://192.168.1.100:4873/express-pouchdb/-/express-pouchdb-1.0.6-thali.tgz
npm http 304 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/multiplex
npm http 200 http://192.168.1.100:4873/pouchdb-size
npm http 200 http://192.168.1.100:4873/leveldown-mobile
npm http 304 http://192.168.1.100:4873/randomstring
npm http 304 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/proxyquire
npm http 200 http://192.168.1.100:4873/pouchdb
npm http 200 http://192.168.1.100:4873/request-promise
npm http 304 http://192.168.1.100:4873/socket.io-client
npm http 200 http://192.168.1.100:4873/supertest-as-promised
npm http 200 http://192.168.1.100:4873/supertest
npm http 200 http://192.168.1.100:4873/nock
npm http 304 http://192.168.1.100:4873/urlsafe-base64
npm http 304 http://192.168.1.100:4873/uuid
npm http 200 http://192.168.1.100:4873/sinon
npm http fetch 200 http://192.168.1.100:4873/express-pouchdb/-/express-pouchdb-1.0.6-thali.tgz
npm http 200 http://192.168.1.100:4873/tape-catch
npm http 200 http://192.168.1.100:4873/tape
npm http 200 http://192.168.1.100:4873/tmp
npm http 200 http://192.168.1.100:4873/uuid-validate
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
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/qs
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
npm http 304 http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/media-typer
npm http request GET http://192.168.1.100:4873/mime-db
npm http 304 http://192.168.1.100:4873/mime-db
npm http request GET http://192.168.1.100:4873/array-flatten
npm http request GET http://192.168.1.100:4873/content-disposition
npm http request GET http://192.168.1.100:4873/accepts
npm http request GET http://192.168.1.100:4873/cookie-signature
npm http request GET http://192.168.1.100:4873/cookie
npm http request GET http://192.168.1.100:4873/escape-html
npm http request GET http://192.168.1.100:4873/etag
npm http request GET http://192.168.1.100:4873/finalhandler
npm http request GET http://192.168.1.100:4873/fresh
npm http request GET http://192.168.1.100:4873/merge-descriptors
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/parseurl
npm http request GET http://192.168.1.100:4873/proxy-addr
npm http request GET http://192.168.1.100:4873/range-parser
npm http request GET http://192.168.1.100:4873/path-to-regexp
npm http request GET http://192.168.1.100:4873/send
npm http request GET http://192.168.1.100:4873/serve-static
npm http request GET http://192.168.1.100:4873/utils-merge
npm http request GET http://192.168.1.100:4873/vary
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/path-to-regexp
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
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/basic-auth
npm http request GET http://192.168.1.100:4873/cookie-parser
npm http request GET http://192.168.1.100:4873/compression
npm http request GET http://192.168.1.100:4873/header-case-normalizer
npm http request GET http://192.168.1.100:4873/pouchdb-all-dbs
npm http request GET http://192.168.1.100:4873/multiparty
npm http request GET http://192.168.1.100:4873/pouchdb-auth
npm http request GET http://192.168.1.100:4873/pouchdb-list
npm http request GET http://192.168.1.100:4873/pouchdb-find
npm http request GET http://192.168.1.100:4873/pouchdb-replicator
npm http request GET http://192.168.1.100:4873/pouchdb-rewrite
npm http request GET http://192.168.1.100:4873/pouchdb-security
npm http request GET http://192.168.1.100:4873/pouchdb-show
npm http request GET http://192.168.1.100:4873/pouchdb-validation
npm http request GET http://192.168.1.100:4873/pouchdb-update
npm http request GET http://192.168.1.100:4873/pouchdb-vhost
npm http request GET http://192.168.1.100:4873/pouchdb-wrappers
npm http 304 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/cookie-parser
npm http 200 http://192.168.1.100:4873/basic-auth
npm http 200 http://192.168.1.100:4873/header-case-normalizer
npm http 200 http://192.168.1.100:4873/compression
npm http 200 http://192.168.1.100:4873/multiparty
npm http 200 http://192.168.1.100:4873/pouchdb-all-dbs
npm http 200 http://192.168.1.100:4873/pouchdb-auth
npm http 200 http://192.168.1.100:4873/pouchdb-list
npm http 200 http://192.168.1.100:4873/pouchdb-find
npm http 200 http://192.168.1.100:4873/pouchdb-replicator
npm http 200 http://192.168.1.100:4873/pouchdb-rewrite
npm http 200 http://192.168.1.100:4873/pouchdb-security
npm http 200 http://192.168.1.100:4873/pouchdb-validation
npm http 200 http://192.168.1.100:4873/pouchdb-show
npm http 200 http://192.168.1.100:4873/pouchdb-update
npm http 200 http://192.168.1.100:4873/pouchdb-vhost
npm http 200 http://192.168.1.100:4873/pouchdb-wrappers
npm http fetch GET http://192.168.1.100:4873/http-errors/-/http-errors-1.5.1.tgz
npm http fetch 200 http://192.168.1.100:4873/http-errors/-/http-errors-1.5.1.tgz
npm http request GET http://192.168.1.100:4873/setprototypeof
npm http 200 http://192.168.1.100:4873/setprototypeof
npm http fetch GET http://192.168.1.100:4873/setprototypeof/-/setprototypeof-1.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/setprototypeof/-/setprototypeof-1.0.2.tgz
npm http request GET http://192.168.1.100:4873/on-headers
npm http request GET http://192.168.1.100:4873/compressible
npm http 200 http://192.168.1.100:4873/on-headers
npm http 200 http://192.168.1.100:4873/compressible
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/stream-counter
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 200 http://192.168.1.100:4873/stream-counter
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/tiny-queue
npm http request GET http://192.168.1.100:4873/argsarray
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
npm http request GET http://192.168.1.100:4873/base64url
npm http request GET http://192.168.1.100:4873/couchdb-calculate-session-id
npm http request GET http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http request GET http://192.168.1.100:4873/crypto-lite
npm http request GET http://192.168.1.100:4873/pouchdb-plugin-error
npm http request GET http://192.168.1.100:4873/pouchdb-req-http-query
npm http request GET http://192.168.1.100:4873/pouchdb-system-db
npm http request GET http://192.168.1.100:4873/promise-nodify
npm http request GET http://192.168.1.100:4873/secure-random
npm http 200 http://192.168.1.100:4873/base64url
npm http 200 http://192.168.1.100:4873/pouchdb-plugin-error
npm http 200 http://192.168.1.100:4873/crypto-lite
npm http 200 http://192.168.1.100:4873/couchdb-calculate-session-id
npm http 200 http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http 200 http://192.168.1.100:4873/pouchdb-system-db
npm http 200 http://192.168.1.100:4873/promise-nodify
npm http 200 http://192.168.1.100:4873/pouchdb-req-http-query
npm http 200 http://192.168.1.100:4873/secure-random
npm http request GET http://192.168.1.100:4873/meow
npm http request GET http://192.168.1.100:4873/concat-stream
npm http 200 http://192.168.1.100:4873/meow
npm http 200 http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/typedarray
npm http 200 http://192.168.1.100:4873/typedarray
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/camelcase-keys
npm http request GET http://192.168.1.100:4873/indent-string
npm http 304 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/camelcase-keys
npm http 200 http://192.168.1.100:4873/indent-string
npm http request GET http://192.168.1.100:4873/camelcase
npm http request GET http://192.168.1.100:4873/map-obj
npm http 200 http://192.168.1.100:4873/camelcase
npm http 200 http://192.168.1.100:4873/map-obj
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
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/level-write-stream
npm http request GET http://192.168.1.100:4873/es6-promise-pool
npm http request GET http://192.168.1.100:4873/fruitdown
npm http request GET http://192.168.1.100:4873/localstorage-down
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/pouchdb-collate
npm http request GET http://192.168.1.100:4873/memdown
npm http request GET http://192.168.1.100:4873/scope-eval
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/vuvuzela
npm http 200 http://192.168.1.100:4873/double-ended-queue
npm http 200 http://192.168.1.100:4873/level-write-stream
npm http 200 http://192.168.1.100:4873/fruitdown
npm http 200 http://192.168.1.100:4873/localstorage-down
npm http 200 http://192.168.1.100:4873/es6-promise-pool
npm http 200 http://192.168.1.100:4873/levelup
npm http 200 http://192.168.1.100:4873/scope-eval
npm http 200 http://192.168.1.100:4873/memdown
npm http 200 http://192.168.1.100:4873/spark-md5
npm http 200 http://192.168.1.100:4873/pouchdb-collate
npm http 200 http://192.168.1.100:4873/sublevel-pouchdb
npm http 304 http://192.168.1.100:4873/through2
npm http 200 http://192.168.1.100:4873/pouchdb-collections
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
npm http request GET http://192.168.1.100:4873/semver
npm http request GET http://192.168.1.100:4873/prr
npm http request GET http://192.168.1.100:4873/level-errors
npm http request GET http://192.168.1.100:4873/level-iterator-stream
npm http 200 http://192.168.1.100:4873/level-codec
npm http 200 http://192.168.1.100:4873/semver
npm http 200 http://192.168.1.100:4873/prr
npm http 200 http://192.168.1.100:4873/level-errors
npm http 200 http://192.168.1.100:4873/deferred-leveldown
npm http 200 http://192.168.1.100:4873/level-iterator-stream
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
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/is-typedarray
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/tough-cookie
npm WARN deprecated tough-cookie@2.2.2: ReDoS vulnerability parsing Set-Cookie https://nodesecurity.io/advisories/130
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/process-nextick-args
npm http 304 http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/pinkie-promise
npm http request GET http://192.168.1.100:4873/is-my-json-valid
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
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/pinkie
npm http 304 http://192.168.1.100:4873/pinkie
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/boom
npm http 304 http://192.168.1.100:4873/hoek
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
npm http request GET http://192.168.1.100:4873/pouchdb-upsert
npm http request GET http://192.168.1.100:4873/pouchdb-extend
npm http request GET http://192.168.1.100:4873/is-array
npm http 200 http://192.168.1.100:4873/is-array
npm http 200 http://192.168.1.100:4873/pouchdb-extend
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
npm http request GET http://192.168.1.100:4873/fast-future
npm http request GET http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http 304 http://192.168.1.100:4873/abstract-leveldown
npm http 200 http://192.168.1.100:4873/fast-future
npm http 200 http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/duplexify
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
npm http request GET http://192.168.1.100:4873/deep-equal
npm http request GET http://192.168.1.100:4873/chai
npm http request GET http://192.168.1.100:4873/propagate
npm http 304 http://192.168.1.100:4873/debug
npm http 200 http://192.168.1.100:4873/deep-equal
npm http 200 http://192.168.1.100:4873/propagate
npm http 200 http://192.168.1.100:4873/chai
npm http request GET http://192.168.1.100:4873/assertion-error
npm http request GET http://192.168.1.100:4873/deep-eql
npm http request GET http://192.168.1.100:4873/type-detect
npm http 200 http://192.168.1.100:4873/assertion-error
npm http 200 http://192.168.1.100:4873/type-detect
npm http 200 http://192.168.1.100:4873/deep-eql
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
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/jsonschema
npm http 304 http://192.168.1.100:4873/jsonschema
npm http request GET http://192.168.1.100:4873/formatio
npm http request GET http://192.168.1.100:4873/util
npm http request GET http://192.168.1.100:4873/samsam
npm http request GET http://192.168.1.100:4873/lolex
npm http 200 http://192.168.1.100:4873/formatio
npm http 200 http://192.168.1.100:4873/util
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
npm http 304 http://192.168.1.100:4873/component-bind
npm http 304 http://192.168.1.100:4873/component-emitter
npm http 304 http://192.168.1.100:4873/object-component
npm http 304 http://192.168.1.100:4873/socket.io-parser
npm http 304 http://192.168.1.100:4873/engine.io-client
npm http 304 http://192.168.1.100:4873/indexof
npm http 304 http://192.168.1.100:4873/to-array
npm http 304 http://192.168.1.100:4873/parseuri
npm http 304 http://192.168.1.100:4873/has-binary
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
npm http 304 http://192.168.1.100:4873/engine.io-parser
npm http 304 http://192.168.1.100:4873/xmlhttprequest-ssl
npm http 304 http://192.168.1.100:4873/parsejson
npm http 304 http://192.168.1.100:4873/parseqs
npm http 304 http://192.168.1.100:4873/component-inherit
npm http 304 http://192.168.1.100:4873/yeast
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/utf8
npm http 304 http://192.168.1.100:4873/arraybuffer.slice
npm http 304 http://192.168.1.100:4873/base64-arraybuffer
npm http 304 http://192.168.1.100:4873/after
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
npm http 304 http://192.168.1.100:4873/benchmark
npm http 304 http://192.168.1.100:4873/json3
npm http request GET http://192.168.1.100:4873/superagent
npm http 200 http://192.168.1.100:4873/superagent
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/formidable
npm http request GET http://192.168.1.100:4873/reduce-component
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/cookiejar
npm http 304 http://192.168.1.100:4873/methods
npm http 200 http://192.168.1.100:4873/reduce-component
npm http 200 http://192.168.1.100:4873/formidable
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
npm http 304 http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/defined
npm http 200 http://192.168.1.100:4873/resumer
npm http 200 http://192.168.1.100:4873/object-inspect
npm http request GET http://192.168.1.100:4873/os-tmpdir
npm http 200 http://192.168.1.100:4873/os-tmpdir
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
thali/install/setUpDesktop.sh: line 45: test/www/jxcore: No such file or directory

```

Error: Command failed: npm WARN thali-test-server@0.0.1 No repository field.
npm WARN thali-test-server@0.0.1 No license field.
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/javascript-state-machine
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/js-extend
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/express
npm http 200 http://192.168.1.100:4873/ip
npm http 200 http://192.168.1.100:4873/javascript-state-machine
npm http 200 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/uuid
npm http 200 http://192.168.1.100:4873/long
npm http 200 http://192.168.1.100:4873/body-parser
npm http 200 http://192.168.1.100:4873/lie
npm http 200 http://192.168.1.100:4873/multiplex
npm http 304 http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/js-extend
npm http 200 http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/depd
npm http 200 http://192.168.1.100:4873/bytes
npm http 304 http://192.168.1.100:4873/http-errors
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
npm http fetch GET http://192.168.1.100:4873/statuses/-/statuses-1.3.1.tgz
npm http fetch 200 http://192.168.1.100:4873/statuses/-/statuses-1.3.1.tgz
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
npm http request GET http://192.168.1.100:4873/cookie-signature
npm http request GET http://192.168.1.100:4873/escape-html
npm http request GET http://192.168.1.100:4873/cookie
npm http request GET http://192.168.1.100:4873/finalhandler
npm http request GET http://192.168.1.100:4873/etag
npm http request GET http://192.168.1.100:4873/fresh
npm http request GET http://192.168.1.100:4873/merge-descriptors
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/parseurl
npm http request GET http://192.168.1.100:4873/proxy-addr
npm http request GET http://192.168.1.100:4873/path-to-regexp
npm http request GET http://192.168.1.100:4873/range-parser
npm http request GET http://192.168.1.100:4873/send
npm http request GET http://192.168.1.100:4873/serve-static
npm http request GET http://192.168.1.100:4873/utils-merge
npm http request GET http://192.168.1.100:4873/vary
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/finalhandler
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
npm http 304 http://192.168.1.100:4873/destroy
npm http 304 http://192.168.1.100:4873/mime
npm http request GET http://192.168.1.100:4873/immediate
npm http 200 http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/varint
npm http 200 http://192.168.1.100:4873/varint
npm http 200 http://192.168.1.100:4873/xtend
npm http 200 http://192.168.1.100:4873/duplexify
npm http 200 http://192.168.1.100:4873/readable-stream
npm http fetch GET http://192.168.1.100:4873/readable-stream/-/readable-stream-2.2.2.tgz
npm http fetch 200 http://192.168.1.100:4873/readable-stream/-/readable-stream-2.2.2.tgz
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/stream-shift
npm http 200 http://192.168.1.100:4873/end-of-stream
npm http 200 http://192.168.1.100:4873/stream-shift
npm http request GET http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/wrappy
npm http 304 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/string_decoder
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http request GET http://192.168.1.100:4873/core-util-is
npm http 304 http://192.168.1.100:4873/isarray
npm http 200 http://192.168.1.100:4873/string_decoder
npm http 200 http://192.168.1.100:4873/process-nextick-args
npm http 200 http://192.168.1.100:4873/util-deprecate
npm http 200 http://192.168.1.100:4873/buffer-shims
npm http 200 http://192.168.1.100:4873/core-util-is
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/har-validator
npm http 200 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/bl
npm http 200 http://192.168.1.100:4873/caseless
npm http 200 http://192.168.1.100:4873/json-stringify-safe
npm http 200 http://192.168.1.100:4873/form-data
npm http 200 http://192.168.1.100:4873/tunnel-agent
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 200 http://192.168.1.100:4873/http-signature
npm http 200 http://192.168.1.100:4873/oauth-sign
npm http 200 http://192.168.1.100:4873/tough-cookie
npm http 200 http://192.168.1.100:4873/aws-sign2
npm http 200 http://192.168.1.100:4873/stringstream
npm http 200 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/hawk
npm http 200 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 200 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/lodash
npm http 200 http://192.168.1.100:4873/lodash
npm http fetch GET http://192.168.1.100:4873/lodash/-/lodash-4.17.2.tgz
npm http fetch 200 http://192.168.1.100:4873/lodash/-/lodash-4.17.2.tgz
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http 200 http://192.168.1.100:4873/chalk
npm http 200 http://192.168.1.100:4873/commander
npm http 200 http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 200 http://192.168.1.100:4873/has-ansi
npm http 200 http://192.168.1.100:4873/strip-ansi
npm http 200 http://192.168.1.100:4873/supports-color
npm http 200 http://192.168.1.100:4873/escape-string-regexp
npm http 200 http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 200 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http 200 http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http 200 http://192.168.1.100:4873/generate-function
npm http 200 http://192.168.1.100:4873/generate-object-property
npm http 200 http://192.168.1.100:4873/jsonpointer
npm http request GET http://192.168.1.100:4873/is-property
npm http 200 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/boom
npm http 200 http://192.168.1.100:4873/cryptiles
npm http 200 http://192.168.1.100:4873/boom
npm http 200 http://192.168.1.100:4873/hoek
npm http 200 http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/asn1
npm http 200 http://192.168.1.100:4873/asn1
npm http 200 http://192.168.1.100:4873/ctype
npm http 200 http://192.168.1.100:4873/assert-plus
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
npm http 304 http://192.168.1.100:4873/eyes
npm http 304 http://192.168.1.100:4873/cycle
npm http 304 http://192.168.1.100:4873/colors
npm http 304 http://192.168.1.100:4873/pkginfo
npm http 304 http://192.168.1.100:4873/stack-trace
npm http request GET http://192.168.1.100:4873/jsdoc
npm http 200 http://192.168.1.100:4873/jsdoc
npm http request GET http://192.168.1.100:4873/underscore
npm http request GET http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/catharsis
npm http request GET http://192.168.1.100:4873/marked
npm http request GET http://192.168.1.100:4873/js2xmlparser
npm http request GET http://192.168.1.100:4873/requizzle
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/wrench
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 200 http://192.168.1.100:4873/underscore
npm http 200 http://192.168.1.100:4873/esprima
npm http 200 http://192.168.1.100:4873/js2xmlparser
npm http 200 http://192.168.1.100:4873/catharsis
npm http 200 http://192.168.1.100:4873/marked
npm http 200 http://192.168.1.100:4873/requizzle
npm http 200 http://192.168.1.100:4873/strip-json-comments
npm http 200 http://192.168.1.100:4873/wrench
npm WARN deprecated wrench@1.5.9: wrench.js is deprecated! You should check out fs-extra (https://github.com/jprichardson/node-fs-extra) for any operations you were using wrench for. Thanks for all the usage over the years.
npm http fetch 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http request GET http://192.168.1.100:4873/underscore-contrib
npm http 200 http://192.168.1.100:4873/underscore-contrib
npm WARN prefer global marked@0.3.6 should be installed with -g
npm WARN install@0.0.1 No repository field.
thali/install/setUpDesktop.sh: line 40: test/www/jxcore: No such file or directory
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/child-process-promise
npm http request GET http://192.168.1.100:4873/bn.js
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/express-pouchdb
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/leveldown-mobile
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/pouchdb-size
npm http request GET http://192.168.1.100:4873/pouchdb
npm http request GET http://192.168.1.100:4873/nock
npm http request GET http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/proxyquire
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/request-promise
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/sinon
npm http request GET http://192.168.1.100:4873/supertest
npm http request GET http://192.168.1.100:4873/supertest-as-promised
npm http request GET http://192.168.1.100:4873/tape
npm http request GET http://192.168.1.100:4873/tape-catch
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/tmp
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/uuid-validate
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/child-process-promise
npm http 304 http://192.168.1.100:4873/concat-map
npm http 200 http://192.168.1.100:4873/bn.js
npm http 304 http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/js-extend
npm http 200 http://192.168.1.100:4873/express-pouchdb
npm http fetch GET http://192.168.1.100:4873/express-pouchdb/-/express-pouchdb-1.0.6-thali.tgz
npm http 304 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/multiplex
npm http 200 http://192.168.1.100:4873/pouchdb-size
npm http 200 http://192.168.1.100:4873/leveldown-mobile
npm http 304 http://192.168.1.100:4873/randomstring
npm http 304 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/proxyquire
npm http 200 http://192.168.1.100:4873/pouchdb
npm http 200 http://192.168.1.100:4873/request-promise
npm http 304 http://192.168.1.100:4873/socket.io-client
npm http 200 http://192.168.1.100:4873/supertest-as-promised
npm http 200 http://192.168.1.100:4873/supertest
npm http 200 http://192.168.1.100:4873/nock
npm http 304 http://192.168.1.100:4873/urlsafe-base64
npm http 304 http://192.168.1.100:4873/uuid
npm http 200 http://192.168.1.100:4873/sinon
npm http fetch 200 http://192.168.1.100:4873/express-pouchdb/-/express-pouchdb-1.0.6-thali.tgz
npm http 200 http://192.168.1.100:4873/tape-catch
npm http 200 http://192.168.1.100:4873/tape
npm http 200 http://192.168.1.100:4873/tmp
npm http 200 http://192.168.1.100:4873/uuid-validate
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
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/qs
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
npm http 304 http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/media-typer
npm http request GET http://192.168.1.100:4873/mime-db
npm http 304 http://192.168.1.100:4873/mime-db
npm http request GET http://192.168.1.100:4873/array-flatten
npm http request GET http://192.168.1.100:4873/content-disposition
npm http request GET http://192.168.1.100:4873/accepts
npm http request GET http://192.168.1.100:4873/cookie-signature
npm http request GET http://192.168.1.100:4873/cookie
npm http request GET http://192.168.1.100:4873/escape-html
npm http request GET http://192.168.1.100:4873/etag
npm http request GET http://192.168.1.100:4873/finalhandler
npm http request GET http://192.168.1.100:4873/fresh
npm http request GET http://192.168.1.100:4873/merge-descriptors
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/parseurl
npm http request GET http://192.168.1.100:4873/proxy-addr
npm http request GET http://192.168.1.100:4873/range-parser
npm http request GET http://192.168.1.100:4873/path-to-regexp
npm http request GET http://192.168.1.100:4873/send
npm http request GET http://192.168.1.100:4873/serve-static
npm http request GET http://192.168.1.100:4873/utils-merge
npm http request GET http://192.168.1.100:4873/vary
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/path-to-regexp
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
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/basic-auth
npm http request GET http://192.168.1.100:4873/cookie-parser
npm http request GET http://192.168.1.100:4873/compression
npm http request GET http://192.168.1.100:4873/header-case-normalizer
npm http request GET http://192.168.1.100:4873/pouchdb-all-dbs
npm http request GET http://192.168.1.100:4873/multiparty
npm http request GET http://192.168.1.100:4873/pouchdb-auth
npm http request GET http://192.168.1.100:4873/pouchdb-list
npm http request GET http://192.168.1.100:4873/pouchdb-find
npm http request GET http://192.168.1.100:4873/pouchdb-replicator
npm http request GET http://192.168.1.100:4873/pouchdb-rewrite
npm http request GET http://192.168.1.100:4873/pouchdb-security
npm http request GET http://192.168.1.100:4873/pouchdb-show
npm http request GET http://192.168.1.100:4873/pouchdb-validation
npm http request GET http://192.168.1.100:4873/pouchdb-update
npm http request GET http://192.168.1.100:4873/pouchdb-vhost
npm http request GET http://192.168.1.100:4873/pouchdb-wrappers
npm http 304 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/cookie-parser
npm http 200 http://192.168.1.100:4873/basic-auth
npm http 200 http://192.168.1.100:4873/header-case-normalizer
npm http 200 http://192.168.1.100:4873/compression
npm http 200 http://192.168.1.100:4873/multiparty
npm http 200 http://192.168.1.100:4873/pouchdb-all-dbs
npm http 200 http://192.168.1.100:4873/pouchdb-auth
npm http 200 http://192.168.1.100:4873/pouchdb-list
npm http 200 http://192.168.1.100:4873/pouchdb-find
npm http 200 http://192.168.1.100:4873/pouchdb-replicator
npm http 200 http://192.168.1.100:4873/pouchdb-rewrite
npm http 200 http://192.168.1.100:4873/pouchdb-security
npm http 200 http://192.168.1.100:4873/pouchdb-validation
npm http 200 http://192.168.1.100:4873/pouchdb-show
npm http 200 http://192.168.1.100:4873/pouchdb-update
npm http 200 http://192.168.1.100:4873/pouchdb-vhost
npm http 200 http://192.168.1.100:4873/pouchdb-wrappers
npm http fetch GET http://192.168.1.100:4873/http-errors/-/http-errors-1.5.1.tgz
npm http fetch 200 http://192.168.1.100:4873/http-errors/-/http-errors-1.5.1.tgz
npm http request GET http://192.168.1.100:4873/setprototypeof
npm http 200 http://192.168.1.100:4873/setprototypeof
npm http fetch GET http://192.168.1.100:4873/setprototypeof/-/setprototypeof-1.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/setprototypeof/-/setprototypeof-1.0.2.tgz
npm http request GET http://192.168.1.100:4873/on-headers
npm http request GET http://192.168.1.100:4873/compressible
npm http 200 http://192.168.1.100:4873/on-headers
npm http 200 http://192.168.1.100:4873/compressible
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/stream-counter
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 200 http://192.168.1.100:4873/stream-counter
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/tiny-queue
npm http request GET http://192.168.1.100:4873/argsarray
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
npm http request GET http://192.168.1.100:4873/base64url
npm http request GET http://192.168.1.100:4873/couchdb-calculate-session-id
npm http request GET http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http request GET http://192.168.1.100:4873/crypto-lite
npm http request GET http://192.168.1.100:4873/pouchdb-plugin-error
npm http request GET http://192.168.1.100:4873/pouchdb-req-http-query
npm http request GET http://192.168.1.100:4873/pouchdb-system-db
npm http request GET http://192.168.1.100:4873/promise-nodify
npm http request GET http://192.168.1.100:4873/secure-random
npm http 200 http://192.168.1.100:4873/base64url
npm http 200 http://192.168.1.100:4873/pouchdb-plugin-error
npm http 200 http://192.168.1.100:4873/crypto-lite
npm http 200 http://192.168.1.100:4873/couchdb-calculate-session-id
npm http 200 http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http 200 http://192.168.1.100:4873/pouchdb-system-db
npm http 200 http://192.168.1.100:4873/promise-nodify
npm http 200 http://192.168.1.100:4873/pouchdb-req-http-query
npm http 200 http://192.168.1.100:4873/secure-random
npm http request GET http://192.168.1.100:4873/meow
npm http request GET http://192.168.1.100:4873/concat-stream
npm http 200 http://192.168.1.100:4873/meow
npm http 200 http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/typedarray
npm http 200 http://192.168.1.100:4873/typedarray
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/camelcase-keys
npm http request GET http://192.168.1.100:4873/indent-string
npm http 304 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/camelcase-keys
npm http 200 http://192.168.1.100:4873/indent-string
npm http request GET http://192.168.1.100:4873/camelcase
npm http request GET http://192.168.1.100:4873/map-obj
npm http 200 http://192.168.1.100:4873/camelcase
npm http 200 http://192.168.1.100:4873/map-obj
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
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/level-write-stream
npm http request GET http://192.168.1.100:4873/es6-promise-pool
npm http request GET http://192.168.1.100:4873/fruitdown
npm http request GET http://192.168.1.100:4873/localstorage-down
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/pouchdb-collate
npm http request GET http://192.168.1.100:4873/memdown
npm http request GET http://192.168.1.100:4873/scope-eval
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/vuvuzela
npm http 200 http://192.168.1.100:4873/double-ended-queue
npm http 200 http://192.168.1.100:4873/level-write-stream
npm http 200 http://192.168.1.100:4873/fruitdown
npm http 200 http://192.168.1.100:4873/localstorage-down
npm http 200 http://192.168.1.100:4873/es6-promise-pool
npm http 200 http://192.168.1.100:4873/levelup
npm http 200 http://192.168.1.100:4873/scope-eval
npm http 200 http://192.168.1.100:4873/memdown
npm http 200 http://192.168.1.100:4873/spark-md5
npm http 200 http://192.168.1.100:4873/pouchdb-collate
npm http 200 http://192.168.1.100:4873/sublevel-pouchdb
npm http 304 http://192.168.1.100:4873/through2
npm http 200 http://192.168.1.100:4873/pouchdb-collections
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
npm http request GET http://192.168.1.100:4873/semver
npm http request GET http://192.168.1.100:4873/prr
npm http request GET http://192.168.1.100:4873/level-errors
npm http request GET http://192.168.1.100:4873/level-iterator-stream
npm http 200 http://192.168.1.100:4873/level-codec
npm http 200 http://192.168.1.100:4873/semver
npm http 200 http://192.168.1.100:4873/prr
npm http 200 http://192.168.1.100:4873/level-errors
npm http 200 http://192.168.1.100:4873/deferred-leveldown
npm http 200 http://192.168.1.100:4873/level-iterator-stream
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
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/is-typedarray
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/tough-cookie
npm WARN deprecated tough-cookie@2.2.2: ReDoS vulnerability parsing Set-Cookie https://nodesecurity.io/advisories/130
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/process-nextick-args
npm http 304 http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/pinkie-promise
npm http request GET http://192.168.1.100:4873/is-my-json-valid
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
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/pinkie
npm http 304 http://192.168.1.100:4873/pinkie
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/boom
npm http 304 http://192.168.1.100:4873/hoek
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
npm http request GET http://192.168.1.100:4873/pouchdb-upsert
npm http request GET http://192.168.1.100:4873/pouchdb-extend
npm http request GET http://192.168.1.100:4873/is-array
npm http 200 http://192.168.1.100:4873/is-array
npm http 200 http://192.168.1.100:4873/pouchdb-extend
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
npm http request GET http://192.168.1.100:4873/fast-future
npm http request GET http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http 304 http://192.168.1.100:4873/abstract-leveldown
npm http 200 http://192.168.1.100:4873/fast-future
npm http 200 http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/duplexify
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
npm http request GET http://192.168.1.100:4873/deep-equal
npm http request GET http://192.168.1.100:4873/chai
npm http request GET http://192.168.1.100:4873/propagate
npm http 304 http://192.168.1.100:4873/debug
npm http 200 http://192.168.1.100:4873/deep-equal
npm http 200 http://192.168.1.100:4873/propagate
npm http 200 http://192.168.1.100:4873/chai
npm http request GET http://192.168.1.100:4873/assertion-error
npm http request GET http://192.168.1.100:4873/deep-eql
npm http request GET http://192.168.1.100:4873/type-detect
npm http 200 http://192.168.1.100:4873/assertion-error
npm http 200 http://192.168.1.100:4873/type-detect
npm http 200 http://192.168.1.100:4873/deep-eql
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
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/jsonschema
npm http 304 http://192.168.1.100:4873/jsonschema
npm http request GET http://192.168.1.100:4873/formatio
npm http request GET http://192.168.1.100:4873/util
npm http request GET http://192.168.1.100:4873/samsam
npm http request GET http://192.168.1.100:4873/lolex
npm http 200 http://192.168.1.100:4873/formatio
npm http 200 http://192.168.1.100:4873/util
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
npm http 304 http://192.168.1.100:4873/component-bind
npm http 304 http://192.168.1.100:4873/component-emitter
npm http 304 http://192.168.1.100:4873/object-component
npm http 304 http://192.168.1.100:4873/socket.io-parser
npm http 304 http://192.168.1.100:4873/engine.io-client
npm http 304 http://192.168.1.100:4873/indexof
npm http 304 http://192.168.1.100:4873/to-array
npm http 304 http://192.168.1.100:4873/parseuri
npm http 304 http://192.168.1.100:4873/has-binary
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
npm http 304 http://192.168.1.100:4873/engine.io-parser
npm http 304 http://192.168.1.100:4873/xmlhttprequest-ssl
npm http 304 http://192.168.1.100:4873/parsejson
npm http 304 http://192.168.1.100:4873/parseqs
npm http 304 http://192.168.1.100:4873/component-inherit
npm http 304 http://192.168.1.100:4873/yeast
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/utf8
npm http 304 http://192.168.1.100:4873/arraybuffer.slice
npm http 304 http://192.168.1.100:4873/base64-arraybuffer
npm http 304 http://192.168.1.100:4873/after
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
npm http 304 http://192.168.1.100:4873/benchmark
npm http 304 http://192.168.1.100:4873/json3
npm http request GET http://192.168.1.100:4873/superagent
npm http 200 http://192.168.1.100:4873/superagent
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/formidable
npm http request GET http://192.168.1.100:4873/reduce-component
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/cookiejar
npm http 304 http://192.168.1.100:4873/methods
npm http 200 http://192.168.1.100:4873/reduce-component
npm http 200 http://192.168.1.100:4873/formidable
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
npm http 304 http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/defined
npm http 200 http://192.168.1.100:4873/resumer
npm http 200 http://192.168.1.100:4873/object-inspect
npm http request GET http://192.168.1.100:4873/os-tmpdir
npm http 200 http://192.168.1.100:4873/os-tmpdir
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
thali/install/setUpDesktop.sh: line 45: test/www/jxcore: No such file or directory
