#### Test (Fail) 109227327 Build Logs


```


```

```
Already up-to-date.

From https://github.com/thaliproject/Thali_CordovaPlugin
   7326a90..a1ecb89  evabishchevich_sanity_check -> origin/evabishchevich_sanity_check

```

```
Your branch is up-to-date with 'origin/master'.
Your branch is up-to-date with 'origin/master'.
Already up-to-date.

Already on 'master'
Already on 'master'
Note: checking out 'a1ecb89'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at a1ecb89... Trigger CI

```

```
triggering build 

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
│ └── q@1.4.1 
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
│ │ └─┬ async@2.1.5 
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
│ │ ├─┬ jsprim@1.3.1 
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
│ ├─┬ mime-types@2.1.14 
│ │ └── mime-db@1.26.0 
│ ├── oauth-sign@0.8.2 
│ ├── qs@6.2.2 
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
2017-03-06 11:27:53 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
2017-03-06 11:27:53 - INFO testLoader: 'loading file: ../bv_tests/testTests.js'
2017-03-06 11:27:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-03-06 11:27:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-03-06 11:27:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
2017-03-06 11:27:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2017-03-06 11:27:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-03-06 11:27:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-03-06 11:27:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-03-06 11:27:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
TAP version 13
# setup
# basic
ok 1 sane
# teardown
# setup
# another
ok 2 sane
# teardown
2017-03-06 11:27:53 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - basic'
2017-03-06 11:27:53 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - another'
2017-03-06 11:27:53 - DEBUG SimpleThaliTape: 'all unit tests succeeded, platformName: 'android''
2017-03-06 11:27:53 - DEBUG SimpleThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'
2017-03-06 11:27:53 - INFO runTests: 'Finished'

1..2
# tests 2
# pass  2

# ok

2017-03-06 11:27:56 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: android'
2017-03-06 11:27:56 - INFO testLoader: 'loading file: ../bv_tests/testTests.js'
2017-03-06 11:27:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-03-06 11:27:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-03-06 11:27:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
2017-03-06 11:27:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2017-03-06 11:27:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-03-06 11:27:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-03-06 11:27:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-03-06 11:27:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
TAP version 13
# setup
# basic
ok 1 sane
# teardown
# setup
# another
ok 2 sane
# teardown
2017-03-06 11:27:56 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - basic'
2017-03-06 11:27:56 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - another'
2017-03-06 11:27:56 - DEBUG SimpleThaliTape: 'all unit tests succeeded, platformName: 'android''
2017-03-06 11:27:56 - DEBUG SimpleThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'
2017-03-06 11:27:56 - INFO runTests: 'Finished'

1..2
# tests 2
# pass  2

# ok

2017-03-06 11:27:58 - INFO runTests: 'Starting tests. Network type: BOTH. Platform: android'
2017-03-06 11:27:58 - INFO testLoader: 'loading file: ../bv_tests/testTests.js'
2017-03-06 11:27:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-03-06 11:27:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-03-06 11:27:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
2017-03-06 11:27:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2017-03-06 11:27:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-03-06 11:27:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-03-06 11:27:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-03-06 11:27:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
TAP version 13
# setup
# basic
ok 1 sane
# teardown
# setup
# another
ok 2 sane
# teardown
2017-03-06 11:27:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - basic'
2017-03-06 11:27:58 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - another'
2017-03-06 11:27:58 - DEBUG SimpleThaliTape: 'all unit tests succeeded, platformName: 'android''
2017-03-06 11:27:58 - DEBUG SimpleThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'
2017-03-06 11:27:58 - INFO runTests: 'Finished'

1..2
# tests 2
# pass  2

# ok


> thali-cordova-plugin-jxcore@1.0.0 test-meta /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore
> jx runTests.js meta_tests

2017-03-06 11:28:02 - INFO runTests: 'Starting tests. Network type: undefined. Platform: android'
2017-03-06 11:28:02 - INFO testLoader: 'loading file: ../bv_tests/testTests.js'
2017-03-06 11:28:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-03-06 11:28:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-03-06 11:28:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
2017-03-06 11:28:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2017-03-06 11:28:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-03-06 11:28:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-03-06 11:28:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-03-06 11:28:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
TAP version 13
# setup
# basic
ok 1 sane
# teardown
# setup
# another
ok 2 sane
# teardown
2017-03-06 11:28:02 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - basic'
2017-03-06 11:28:02 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - another'
2017-03-06 11:28:02 - DEBUG SimpleThaliTape: 'all unit tests succeeded, platformName: 'android''
2017-03-06 11:28:02 - DEBUG SimpleThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'
2017-03-06 11:28:02 - INFO runTests: 'Finished'

1..2
# tests 2
# pass  2

# ok

2017-03-06 11:28:03 - INFO HttpServer: 'listening on *:3000'

[36m2017-03-06 11:28:06 - DEBUG UnitTest_app: 'Unit Test app is loaded'
[39m
[36m2017-03-06 11:28:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
[39m
[36m2017-03-06 11:28:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
[39m
[36m2017-03-06 11:28:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
[39m
[36m2017-03-06 11:28:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
[39m
[36m2017-03-06 11:28:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
[39m
[36m2017-03-06 11:28:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
[39m
[36m2017-03-06 11:28:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
[39m
[36m2017-03-06 11:28:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
[39m
[36m2017-03-06 11:28:06 - DEBUG UnitTest_app: 'My device name is: '4da583dd-e851-42f2-8cb8-a0ebbb8d70e3''
[39m
[36m2017-03-06 11:28:06 - WARN testUtils: 'myNameCallback not set!'
[39m
[33m2017-03-06 11:28:06 - DEBUG UnitTest_app: 'Unit Test app is loaded'
[39m
[33m2017-03-06 11:28:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
[39m
[33m2017-03-06 11:28:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
[39m
[33m2017-03-06 11:28:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
[39m
[33m2017-03-06 11:28:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
[39m
[33m2017-03-06 11:28:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-03-06 11:28:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-03-06 11:28:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
[39m
[33m2017-03-06 11:28:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
[39m
[33m2017-03-06 11:28:06 - DEBUG UnitTest_app: 'My device name is: '9319bbcd-e444-48a2-a2f0-bb6bfb937245''
[39m
[33m2017-03-06 11:28:06 - WARN testUtils: 'myNameCallback not set!'
[39m
[32m2017-03-06 11:28:06 - DEBUG UnitTest_app: 'Unit Test app is loaded'
[39m
[32m2017-03-06 11:28:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
[39m
[32m2017-03-06 11:28:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
[39m
[32m2017-03-06 11:28:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
[39m
[32m2017-03-06 11:28:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
[39m
[32m2017-03-06 11:28:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
[39m
[32m2017-03-06 11:28:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
[39m
[32m2017-03-06 11:28:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
[39m
[32m2017-03-06 11:28:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
2017-03-06 11:28:06 - DEBUG UnitTest_app: 'My device name is: '1d11a6b6-9175-40cb-b892-efb59a194185''
[39m
[32m2017-03-06 11:28:06 - WARN testUtils: 'myNameCallback not set!'
[39m
[33m2017-03-06 11:28:07 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: android'
[39m
[33m2017-03-06 11:28:07 - INFO testLoader: 'loading file: ../bv_tests/testTests.js'
[39m
[36m2017-03-06 11:28:07 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: android'
[39m
[36m2017-03-06 11:28:07 - INFO testLoader: 'loading file: ../bv_tests/testTests.js'
[39m
[33m2017-03-06 11:28:07 - INFO CoordinatedClient: 'Connecting to coordination server on http://192.168.1.20:3000/'
[39m
[36m2017-03-06 11:28:07 - INFO CoordinatedClient: 'Connecting to coordination server on http://192.168.1.20:3000/'
[39m
[32m2017-03-06 11:28:07 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: android'
[39m
[32m2017-03-06 11:28:07 - INFO testLoader: 'loading file: ../bv_tests/testTests.js'
[39m
[36m2017-03-06 11:28:07 - DEBUG CoordinatedClient: 'connected to the test server'
[39m
[32m2017-03-06 11:28:07 - INFO CoordinatedClient: 'Connecting to coordination server on http://192.168.1.20:3000/'
[39m
2017-03-06 11:28:07 - DEBUG HttpServer: 'device presented, name: '4da583dd-e851-42f2-8cb8-a0ebbb8d70e3', uuid: 'be93bc0b-cb08-4ee6-b1c9-47218e3caf41', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-03-06 11:28:07 - DEBUG TestFramework: 'device added, name: '4da583dd-e851-42f2-8cb8-a0ebbb8d70e3''

[33m2017-03-06 11:28:07 - DEBUG CoordinatedClient: 'connected to the test server'
[39m
2017-03-06 11:28:07 - DEBUG HttpServer: 'device presented, name: '9319bbcd-e444-48a2-a2f0-bb6bfb937245', uuid: 'd4c7fcfc-eff4-43c9-8f2d-6b321af0c978', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-03-06 11:28:07 - DEBUG TestFramework: 'device added, name: '9319bbcd-e444-48a2-a2f0-bb6bfb937245''

[32m2017-03-06 11:28:07 - DEBUG CoordinatedClient: 'connected to the test server'
[39m
2017-03-06 11:28:07 - DEBUG HttpServer: 'device presented, name: '1d11a6b6-9175-40cb-b892-efb59a194185', uuid: 'f99ae8d0-9422-4f7d-a821-ef1537d5a23a', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-03-06 11:28:07 - DEBUG TestFramework: 'device added, name: '1d11a6b6-9175-40cb-b892-efb59a194185''

2017-03-06 11:28:07 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-03-06 11:28:07 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2017-03-06 11:28:07 - DEBUG UnitTestFramework: 'scheduling tests'

[36mTAP version 13
[39m
[36m# setup
[39m
2017-03-06 11:28:07 - DEBUG UnitTestFramework: 'tests scheduled'

2017-03-06 11:28:07 - DEBUG UnitTestFramework: '#setup: 'basic''

[33mTAP version 13
[39m
[36m# basic
[39m
[33m# setup
[39m
[32mTAP version 13
[39m
[32m# setup
[39m
[33m# basic
[39m
[32m# basic
[39m
2017-03-06 11:28:08 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-03-06 11:28:08 - DEBUG UnitTestFramework: '#run: 'basic''

[36mok 1 sane
# teardown
[39m
[33mok 1 sane
# teardown
[39m
[32mok 1 sane
# teardown
[39m
2017-03-06 11:28:08 - DEBUG UnitTestFramework: '#run ok: 'basic''
2017-03-06 11:28:08 - DEBUG UnitTestFramework: '#teardown: 'basic''

[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2017-03-06 11:28:08 - DEBUG UnitTestFramework: '#teardown ok: 'basic''
2017-03-06 11:28:08 - DEBUG UnitTestFramework: '#setup: 'another''

[32m# another
[39m
[36m# another
[39m
[33m# another
[39m
2017-03-06 11:28:08 - DEBUG UnitTestFramework: '#setup ok: 'another''
2017-03-06 11:28:08 - DEBUG UnitTestFramework: '#run: 'another''

[36mok 2 sane
# teardown
[39m
[32mok 2 sane
# teardown
[39m
[33mok 2 sane
# teardown
[39m
2017-03-06 11:28:08 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-03-06 11:28:08 - DEBUG UnitTestFramework: '#teardown: 'another''

[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2017-03-06 11:28:08 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-03-06 11:28:08 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

[36m# can pass data in setup
[39m
[33m# can pass data in setup
[39m
[32m# can pass data in setup
[39m
2017-03-06 11:28:08 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-03-06 11:28:08 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

[36mok 3 test participant has uuid
[39m
[36mok 4 participant data matches
ok 5 test participant has uuid
[39m
[36mok 6 participant data matches
ok 7 test participant has uuid
ok 8 participant data matches
[39m
[36mok 9 own UUID is found from the participants list
[39m
[36m# teardown
[39m
[33mok 3 test participant has uuid
[39m
[33mok 4 participant data matches
[39m
[33mok 5 test participant has uuid
[39m
[33mok 6 participant data matches
[39m
[33mok 7 test participant has uuid
[39m
[33mok 8 participant data matches
[39m
[33mok 9 own UUID is found from the participants list
[39m
[33m# teardown
[39m
[32mok 3 test participant has uuid
[39m
[32mok 4 participant data matches
[39m
[32mok 5 test participant has uuid
[39m
[32mok 6 participant data matches
[39m
[32mok 7 test participant has uuid
[39m
[32mok 8 participant data matches
ok 9 own UUID is found from the participants list
[39m
[32m# teardown
[39m
2017-03-06 11:28:08 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-03-06 11:28:08 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

[36m2017-03-06 11:28:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
2017-03-06 11:28:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
[39m
[36m2017-03-06 11:28:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
2017-03-06 11:28:08 - DEBUG CoordinatedClient: 'all unit tests succeeded, platformName: 'android''
[39m
[33m2017-03-06 11:28:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
[39m
[33m2017-03-06 11:28:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
[39m
[33m2017-03-06 11:28:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
2017-03-06 11:28:08 - DEBUG CoordinatedClient: 'all unit tests succeeded, platformName: 'android''
[39m
[32m2017-03-06 11:28:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
[39m
[32m2017-03-06 11:28:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
2017-03-06 11:28:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
2017-03-06 11:28:08 - DEBUG CoordinatedClient: 'all unit tests succeeded, platformName: 'android''
[39m
2017-03-06 11:28:08 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-03-06 11:28:08 - DEBUG UnitTestFramework: 'all unit tests succeeded, platformName: 'android''
2017-03-06 11:28:08 - DEBUG UnitTestFramework: 'skipped tests: '[]''

[36m2017-03-06 11:28:08 - DEBUG CoordinatedClient: 'all tests completed'
[39m
[33m2017-03-06 11:28:08 - DEBUG CoordinatedClient: 'all tests completed'
[39m
[32m2017-03-06 11:28:08 - DEBUG CoordinatedClient: 'all tests completed'
[39m
2017-03-06 11:28:08 - DEBUG TestServer: 'completed'

2017-03-06 11:28:08 - INFO HttpServer: 'Socket to device name: '9319bbcd-e444-48a2-a2f0-bb6bfb937245' disconnected, reason: 'undefined''

2017-03-06 11:28:08 - INFO HttpServer: 'Socket to device name: '4da583dd-e851-42f2-8cb8-a0ebbb8d70e3' disconnected, reason: 'undefined''
2017-03-06 11:28:08 - INFO HttpServer: 'Socket to device name: '1d11a6b6-9175-40cb-b892-efb59a194185' disconnected, reason: 'undefined''

Exit code: 0. Exit signal: null
[32m2017-03-06 11:28:08 - DEBUG CoordinatedClient: 'test client disconnected'
2017-03-06 11:28:08 - DEBUG CoordinatedClient: 'test client succeed'
2017-03-06 11:28:08 - DEBUG CoordinatedThaliTape: 'all tests succeed'
2017-03-06 11:28:08 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'
2017-03-06 11:28:08 - INFO runTests: 'Finished'
[39m
[32m
1..9
# tests 9
# pass  9

# ok

[39m
[36m2017-03-06 11:28:08 - DEBUG CoordinatedClient: 'test client disconnected'
2017-03-06 11:28:08 - DEBUG CoordinatedClient: 'test client succeed'
[39m
[36m2017-03-06 11:28:08 - DEBUG CoordinatedThaliTape: 'all tests succeed'
2017-03-06 11:28:08 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'
2017-03-06 11:28:08 - INFO runTests: 'Finished'

1..9
# tests 9
# pass  9

# ok

[39m
[32mExit code: 0. Exit signal: null[39m
[33m2017-03-06 11:28:08 - DEBUG CoordinatedClient: 'test client disconnected'
[39m
[33m2017-03-06 11:28:08 - DEBUG CoordinatedClient: 'test client succeed'
[39m
[33m2017-03-06 11:28:08 - DEBUG CoordinatedThaliTape: 'all tests succeed'
2017-03-06 11:28:08 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'
2017-03-06 11:28:08 - INFO runTests: 'Finished'
[39m
[33m
1..9
# tests 9
# pass  9

# ok

[39m
[36mExit code: 0. Exit signal: null[39m
[33mExit code: 0. Exit signal: null[39m
2017-03-06 11:28:09 - INFO HttpServer: 'listening on *:3000'

[36m2017-03-06 11:28:12 - DEBUG UnitTest_app: 'Unit Test app is loaded'
[39m
[33m2017-03-06 11:28:12 - DEBUG UnitTest_app: 'Unit Test app is loaded'
[39m
[36m2017-03-06 11:28:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
[39m
[36m2017-03-06 11:28:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
[39m
[36m2017-03-06 11:28:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
2017-03-06 11:28:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2017-03-06 11:28:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-03-06 11:28:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-03-06 11:28:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-03-06 11:28:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
2017-03-06 11:28:12 - DEBUG UnitTest_app: 'My device name is: '1edeb126-3deb-45e1-8d40-d0749f0e2db1''
2017-03-06 11:28:12 - WARN testUtils: 'myNameCallback not set!'
[39m
[33m2017-03-06 11:28:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
[39m
[33m2017-03-06 11:28:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
[39m
[33m2017-03-06 11:28:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
[39m
[33m2017-03-06 11:28:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
[39m
[33m2017-03-06 11:28:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
[39m
[33m2017-03-06 11:28:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
[39m
[33m2017-03-06 11:28:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
[39m
[33m2017-03-06 11:28:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
[39m
[33m2017-03-06 11:28:12 - DEBUG UnitTest_app: 'My device name is: 'c2c3ce87-869c-4fa8-9e64-8cd2cea65387''
[39m
[33m2017-03-06 11:28:12 - WARN testUtils: 'myNameCallback not set!'
[39m
[32m2017-03-06 11:28:12 - DEBUG UnitTest_app: 'Unit Test app is loaded'
[39m
[32m2017-03-06 11:28:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
[39m
[32m2017-03-06 11:28:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-03-06 11:28:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
[39m
[32m2017-03-06 11:28:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
[39m
[32m2017-03-06 11:28:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-03-06 11:28:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-03-06 11:28:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
[39m
[32m2017-03-06 11:28:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
[39m
[32m2017-03-06 11:28:12 - DEBUG UnitTest_app: 'My device name is: '3b2934c3-4c0b-4429-b5b0-eeeeb00003fa''
[39m
[32m2017-03-06 11:28:12 - WARN testUtils: 'myNameCallback not set!'
[39m
[33m2017-03-06 11:28:13 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
[39m
[33m2017-03-06 11:28:13 - INFO testLoader: 'loading file: ../bv_tests/testTests.js'
[39m
[36m2017-03-06 11:28:13 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
[39m
[36m2017-03-06 11:28:13 - INFO testLoader: 'loading file: ../bv_tests/testTests.js'
[39m
[33m2017-03-06 11:28:13 - INFO CoordinatedClient: 'Connecting to coordination server on http://192.168.1.20:3000/'
[39m
[36m2017-03-06 11:28:13 - INFO CoordinatedClient: 'Connecting to coordination server on http://192.168.1.20:3000/'
[39m
[32m2017-03-06 11:28:13 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
[39m
[32m2017-03-06 11:28:13 - INFO testLoader: 'loading file: ../bv_tests/testTests.js'
[39m
[32m2017-03-06 11:28:13 - INFO CoordinatedClient: 'Connecting to coordination server on http://192.168.1.20:3000/'
[39m
[32m2017-03-06 11:28:13 - DEBUG CoordinatedClient: 'connected to the test server'
[39m
[33m2017-03-06 11:28:13 - DEBUG CoordinatedClient: 'connected to the test server'
[39m
2017-03-06 11:28:13 - DEBUG HttpServer: 'device presented, name: '3b2934c3-4c0b-4429-b5b0-eeeeb00003fa', uuid: '2a0f2bf5-99a4-4d70-ad03-a505b9a0127b', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-03-06 11:28:13 - DEBUG TestFramework: 'device added, name: '3b2934c3-4c0b-4429-b5b0-eeeeb00003fa''

2017-03-06 11:28:13 - DEBUG HttpServer: 'device presented, name: 'c2c3ce87-869c-4fa8-9e64-8cd2cea65387', uuid: 'd8810dc5-ecde-4abd-a107-569c2be35b76', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-03-06 11:28:13 - DEBUG TestFramework: 'device added, name: 'c2c3ce87-869c-4fa8-9e64-8cd2cea65387''

[36m2017-03-06 11:28:13 - DEBUG CoordinatedClient: 'connected to the test server'
[39m
2017-03-06 11:28:13 - DEBUG HttpServer: 'device presented, name: '1edeb126-3deb-45e1-8d40-d0749f0e2db1', uuid: 'e8dcf804-2304-4293-8d6c-7965a953f24b', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-03-06 11:28:13 - DEBUG TestFramework: 'device added, name: '1edeb126-3deb-45e1-8d40-d0749f0e2db1''

2017-03-06 11:28:13 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-03-06 11:28:13 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2017-03-06 11:28:13 - DEBUG UnitTestFramework: 'scheduling tests'

[32mTAP version 13
[39m
[32m# setup
[39m
[33mTAP version 13
[39m
[33m# setup
[39m
2017-03-06 11:28:13 - DEBUG UnitTestFramework: 'tests scheduled'

2017-03-06 11:28:13 - DEBUG UnitTestFramework: '#setup: 'basic''

[32m# basic
[39m
[33m# basic
[39m
[36mTAP version 13
[39m
[36m# setup
[39m
[36m# basic
[39m
2017-03-06 11:28:14 - DEBUG UnitTestFramework: '#setup ok: 'basic''
2017-03-06 11:28:14 - DEBUG UnitTestFramework: '#run: 'basic''

[32mok 1 sane
# teardown
[39m
[33mok 1 sane
# teardown
[39m
[36mok 1 sane
# teardown
[39m
2017-03-06 11:28:14 - DEBUG UnitTestFramework: '#run ok: 'basic''
2017-03-06 11:28:14 - DEBUG UnitTestFramework: '#teardown: 'basic''

[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2017-03-06 11:28:14 - DEBUG UnitTestFramework: '#teardown ok: 'basic''
2017-03-06 11:28:14 - DEBUG UnitTestFramework: '#setup: 'another''

[32m# another
[39m
[33m# another
[39m
[36m# another
[39m
2017-03-06 11:28:14 - DEBUG UnitTestFramework: '#setup ok: 'another''
2017-03-06 11:28:14 - DEBUG UnitTestFramework: '#run: 'another''

[32mok 2 sane
# teardown
[39m
[33mok 2 sane
[39m
[33m# teardown
[39m
[36mok 2 sane
[39m
[36m# teardown
[39m
2017-03-06 11:28:14 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-03-06 11:28:14 - DEBUG UnitTestFramework: '#teardown: 'another''

[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2017-03-06 11:28:14 - DEBUG UnitTestFramework: '#teardown ok: 'another''
2017-03-06 11:28:14 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

[32m# can pass data in setup
[39m
[33m# can pass data in setup
[39m
[36m# can pass data in setup
[39m
2017-03-06 11:28:14 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-03-06 11:28:14 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

[33mok 3 test participant has uuid
[39m
[33mok 4 participant data matches
[39m
[33mok 5 test participant has uuid
[39m
[33mok 6 participant data matches
ok 7 test participant has uuid
[39m
[33mok 8 participant data matches
[39m
[33mok 9 own UUID is found from the participants list
[39m
[33m# teardown
[39m
[36mok 3 test participant has uuid
[39m
[36mok 4 participant data matches
ok 5 test participant has uuid
[39m
[36mok 6 participant data matches
[39m
[36mok 7 test participant has uuid
[39m
[36mok 8 participant data matches
ok 9 own UUID is found from the participants list
[39m
[36m# teardown
[39m
[32mok 3 test participant has uuid
[39m
[32mok 4 participant data matches
ok 5 test participant has uuid
ok 6 participant data matches
ok 7 test participant has uuid
ok 8 participant data matches
ok 9 own UUID is found from the participants list
[39m
[32m# teardown
[39m
2017-03-06 11:28:14 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-03-06 11:28:14 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

[32m2017-03-06 11:28:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
2017-03-06 11:28:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
2017-03-06 11:28:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
2017-03-06 11:28:14 - DEBUG CoordinatedClient: 'all unit tests succeeded, platformName: 'android''
[39m
[33m2017-03-06 11:28:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
2017-03-06 11:28:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
2017-03-06 11:28:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
2017-03-06 11:28:14 - DEBUG CoordinatedClient: 'all unit tests succeeded, platformName: 'android''
[39m
[36m2017-03-06 11:28:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
2017-03-06 11:28:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
2017-03-06 11:28:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
2017-03-06 11:28:14 - DEBUG CoordinatedClient: 'all unit tests succeeded, platformName: 'android''
[39m
2017-03-06 11:28:14 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''
2017-03-06 11:28:14 - DEBUG UnitTestFramework: 'all unit tests succeeded, platformName: 'android''
2017-03-06 11:28:14 - DEBUG UnitTestFramework: 'skipped tests: '[]''

[32m2017-03-06 11:28:14 - DEBUG CoordinatedClient: 'all tests completed'
[39m
[33m2017-03-06 11:28:14 - DEBUG CoordinatedClient: 'all tests completed'
[39m
[36m2017-03-06 11:28:14 - DEBUG CoordinatedClient: 'all tests completed'
[39m
2017-03-06 11:28:14 - DEBUG TestServer: 'completed'

2017-03-06 11:28:14 - INFO HttpServer: 'Socket to device name: 'c2c3ce87-869c-4fa8-9e64-8cd2cea65387' disconnected, reason: 'undefined''
2017-03-06 11:28:14 - INFO HttpServer: 'Socket to device name: '1edeb126-3deb-45e1-8d40-d0749f0e2db1' disconnected, reason: 'undefined''
2017-03-06 11:28:14 - INFO HttpServer: 'Socket to device name: '3b2934c3-4c0b-4429-b5b0-eeeeb00003fa' disconnected, reason: 'undefined''

Exit code: 0. Exit signal: null
[33m2017-03-06 11:28:14 - DEBUG CoordinatedClient: 'test client disconnected'
[39m
[33m2017-03-06 11:28:14 - DEBUG CoordinatedClient: 'test client succeed'
[39m
[36m2017-03-06 11:28:14 - DEBUG CoordinatedClient: 'test client disconnected'
2017-03-06 11:28:14 - DEBUG CoordinatedClient: 'test client succeed'
[39m
[33m2017-03-06 11:28:14 - DEBUG CoordinatedThaliTape: 'all tests succeed'
[39m
[33m2017-03-06 11:28:14 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'
[39m
[33m2017-03-06 11:28:14 - INFO runTests: 'Finished'
[39m
[36m2017-03-06 11:28:14 - DEBUG CoordinatedThaliTape: 'all tests succeed'
2017-03-06 11:28:14 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'
2017-03-06 11:28:14 - INFO runTests: 'Finished'
[39m
[33m
[39m
[33m1..9
[39m
[33m# tests 9
# pass  9

# ok
[39m
[33m
[39m
[36m
1..9
# tests 9
# pass  9

# ok

[39m
[32m2017-03-06 11:28:14 - DEBUG CoordinatedClient: 'test client disconnected'
2017-03-06 11:28:14 - DEBUG CoordinatedClient: 'test client succeed'
2017-03-06 11:28:14 - DEBUG CoordinatedThaliTape: 'all tests succeed'
[39m
[33mExit code: 0. Exit signal: null[39m
[32m2017-03-06 11:28:14 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'
2017-03-06 11:28:14 - INFO runTests: 'Finished'
[39m
[32m
1..9
# tests 9
# pass  9

# ok
[39m
[36mExit code: 0. Exit signal: null[39m
[32m
[39m
[32mExit code: 0. Exit signal: null[39m
2017-03-06 11:28:15 - INFO HttpServer: 'listening on *:3000'

[32m2017-03-06 11:28:19 - DEBUG UnitTest_app: 'Unit Test app is loaded'
[39m
[32m2017-03-06 11:28:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
[39m
[32m2017-03-06 11:28:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
[39m
[32m2017-03-06 11:28:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
[39m
[32m2017-03-06 11:28:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2017-03-06 11:28:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-03-06 11:28:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-03-06 11:28:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-03-06 11:28:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
2017-03-06 11:28:19 - DEBUG UnitTest_app: 'My device name is: 'f401bc27-8802-4f8c-b713-d60516076317''
2017-03-06 11:28:19 - WARN testUtils: 'myNameCallback not set!'
[39m
[33m2017-03-06 11:28:19 - DEBUG UnitTest_app: 'Unit Test app is loaded'
[39m
[33m2017-03-06 11:28:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
[39m
[33m2017-03-06 11:28:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-03-06 11:28:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
[39m
[33m2017-03-06 11:28:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
[39m
[33m2017-03-06 11:28:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-03-06 11:28:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-03-06 11:28:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-03-06 11:28:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
2017-03-06 11:28:19 - DEBUG UnitTest_app: 'My device name is: '9c65dd8b-993b-4a44-bfc4-e2151d5ad74f''
2017-03-06 11:28:19 - WARN testUtils: 'myNameCallback not set!'
[39m
[36m2017-03-06 11:28:19 - DEBUG UnitTest_app: 'Unit Test app is loaded'
[39m
[36m2017-03-06 11:28:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
[39m
[36m2017-03-06 11:28:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-03-06 11:28:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
2017-03-06 11:28:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
[39m
[36m2017-03-06 11:28:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
[39m
[36m2017-03-06 11:28:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
[39m
[36m2017-03-06 11:28:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-03-06 11:28:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
[39m
[36m2017-03-06 11:28:19 - DEBUG UnitTest_app: 'My device name is: '2c011289-1e3d-4878-9835-f7eb9f59a1bd''
[39m
[36m2017-03-06 11:28:19 - WARN testUtils: 'myNameCallback not set!'
[39m
[32m2017-03-06 11:28:20 - INFO runTests: 'Starting tests. Network type: BOTH. Platform: android'
[39m
[32m2017-03-06 11:28:20 - INFO testLoader: 'loading file: ../bv_tests/testTests.js'
[39m
[32m2017-03-06 11:28:20 - INFO CoordinatedClient: 'Connecting to coordination server on http://192.168.1.20:3000/'
[39m
[32m2017-03-06 11:28:20 - DEBUG CoordinatedClient: 'connected to the test server'
[39m
2017-03-06 11:28:20 - DEBUG HttpServer: 'device presented, name: 'f401bc27-8802-4f8c-b713-d60516076317', uuid: '608df919-9c89-44dd-b16d-00af0c72d547', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-03-06 11:28:20 - DEBUG TestFramework: 'device added, name: 'f401bc27-8802-4f8c-b713-d60516076317''

[33m2017-03-06 11:28:20 - INFO runTests: 'Starting tests. Network type: BOTH. Platform: android'
[39m
[33m2017-03-06 11:28:20 - INFO testLoader: 'loading file: ../bv_tests/testTests.js'
[39m
[33m2017-03-06 11:28:20 - INFO CoordinatedClient: 'Connecting to coordination server on http://192.168.1.20:3000/'
[39m
[36m2017-03-06 11:28:20 - INFO runTests: 'Starting tests. Network type: BOTH. Platform: android'
[39m
[36m2017-03-06 11:28:20 - INFO testLoader: 'loading file: ../bv_tests/testTests.js'
[39m
[33m2017-03-06 11:28:20 - DEBUG CoordinatedClient: 'connected to the test server'
[39m
2017-03-06 11:28:20 - DEBUG HttpServer: 'device presented, name: '9c65dd8b-993b-4a44-bfc4-e2151d5ad74f', uuid: '42b22110-65ca-4784-86d5-1ad2e9f9bb45', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-03-06 11:28:20 - DEBUG TestFramework: 'device added, name: '9c65dd8b-993b-4a44-bfc4-e2151d5ad74f''

[36m2017-03-06 11:28:20 - INFO CoordinatedClient: 'Connecting to coordination server on http://192.168.1.20:3000/'
[39m
[36m2017-03-06 11:28:20 - DEBUG CoordinatedClient: 'connected to the test server'
[39m
2017-03-06 11:28:20 - DEBUG HttpServer: 'device presented, name: '2c011289-1e3d-4878-9835-f7eb9f59a1bd', uuid: '0238dfe8-11c2-4140-997e-41f3399ad681', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-03-06 11:28:20 - DEBUG TestFramework: 'device added, name: '2c011289-1e3d-4878-9835-f7eb9f59a1bd''

2017-03-06 11:28:20 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-03-06 11:28:20 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2017-03-06 11:28:20 - DEBUG UnitTestFramework: 'scheduling tests'

[32mTAP version 13
[39m
[32m# setup
[39m
2017-03-06 11:28:20 - DEBUG UnitTestFramework: 'tests scheduled'

2017-03-06 11:28:20 - DEBUG UnitTestFramework: '#setup: 'basic''

[32m# basic
[39m
[33mTAP version 13
[39m
[36mTAP version 13
[39m
[33m# setup
[39m
[36m# setup
[39m
[36m# basic
[39m
[33m# basic
[39m
2017-03-06 11:28:21 - DEBUG UnitTestFramework: '#setup ok: 'basic''
2017-03-06 11:28:21 - DEBUG UnitTestFramework: '#run: 'basic''

[32mok 1 sane
# teardown
[39m
[33mok 1 sane
# teardown
[39m
[36mok 1 sane
[39m
[36m# teardown
[39m
2017-03-06 11:28:21 - DEBUG UnitTestFramework: '#run ok: 'basic''
2017-03-06 11:28:21 - DEBUG UnitTestFramework: '#teardown: 'basic''

[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2017-03-06 11:28:21 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-03-06 11:28:21 - DEBUG UnitTestFramework: '#setup: 'another''

[33m# another
[39m
[32m# another
[39m
[36m# another
[39m
2017-03-06 11:28:21 - DEBUG UnitTestFramework: '#setup ok: 'another''
2017-03-06 11:28:21 - DEBUG UnitTestFramework: '#run: 'another''

[32mok 2 sane
# teardown
[39m
[33mok 2 sane
# teardown
[39m
[36mok 2 sane
# teardown
[39m
2017-03-06 11:28:21 - DEBUG UnitTestFramework: '#run ok: 'another''
2017-03-06 11:28:21 - DEBUG UnitTestFramework: '#teardown: 'another''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2017-03-06 11:28:21 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-03-06 11:28:21 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

[32m# can pass data in setup
[39m
[33m# can pass data in setup
[39m
[36m# can pass data in setup
[39m
2017-03-06 11:28:21 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-03-06 11:28:21 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

[32mok 3 test participant has uuid
ok 4 participant data matches
ok 5 test participant has uuid
ok 6 participant data matches
ok 7 test participant has uuid
ok 8 participant data matches
ok 9 own UUID is found from the participants list
# teardown
[39m
[33mok 3 test participant has uuid
ok 4 participant data matches
ok 5 test participant has uuid
ok 6 participant data matches
ok 7 test participant has uuid
ok 8 participant data matches
ok 9 own UUID is found from the participants list
# teardown
[39m
[36mok 3 test participant has uuid
ok 4 participant data matches
ok 5 test participant has uuid
ok 6 participant data matches
ok 7 test participant has uuid
ok 8 participant data matches
ok 9 own UUID is found from the participants list
[39m
[36m# teardown
[39m
2017-03-06 11:28:21 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''
2017-03-06 11:28:21 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

[33m2017-03-06 11:28:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
2017-03-06 11:28:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
2017-03-06 11:28:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
2017-03-06 11:28:21 - DEBUG CoordinatedClient: 'all unit tests succeeded, platformName: 'android''
[39m
[32m2017-03-06 11:28:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
2017-03-06 11:28:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
2017-03-06 11:28:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
2017-03-06 11:28:21 - DEBUG CoordinatedClient: 'all unit tests succeeded, platformName: 'android''
[39m
[36m2017-03-06 11:28:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
2017-03-06 11:28:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
2017-03-06 11:28:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
[39m
[36m2017-03-06 11:28:21 - DEBUG CoordinatedClient: 'all unit tests succeeded, platformName: 'android''
[39m
2017-03-06 11:28:21 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-03-06 11:28:21 - DEBUG UnitTestFramework: 'all unit tests succeeded, platformName: 'android''

2017-03-06 11:28:21 - DEBUG UnitTestFramework: 'skipped tests: '[]''

[32m2017-03-06 11:28:21 - DEBUG CoordinatedClient: 'all tests completed'
[39m
[33m2017-03-06 11:28:21 - DEBUG CoordinatedClient: 'all tests completed'
[39m
[36m2017-03-06 11:28:21 - DEBUG CoordinatedClient: 'all tests completed'
[39m
2017-03-06 11:28:21 - DEBUG TestServer: 'completed'

2017-03-06 11:28:21 - INFO HttpServer: 'Socket to device name: 'f401bc27-8802-4f8c-b713-d60516076317' disconnected, reason: 'undefined''

2017-03-06 11:28:21 - INFO HttpServer: 'Socket to device name: '9c65dd8b-993b-4a44-bfc4-e2151d5ad74f' disconnected, reason: 'undefined''

2017-03-06 11:28:21 - INFO HttpServer: 'Socket to device name: '2c011289-1e3d-4878-9835-f7eb9f59a1bd' disconnected, reason: 'undefined''

Exit code: 0. Exit signal: null
[36m2017-03-06 11:28:21 - DEBUG CoordinatedClient: 'test client disconnected'
2017-03-06 11:28:21 - DEBUG CoordinatedClient: 'test client succeed'
2017-03-06 11:28:21 - DEBUG CoordinatedThaliTape: 'all tests succeed'
2017-03-06 11:28:21 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'
2017-03-06 11:28:21 - INFO runTests: 'Finished'
[39m
[33m2017-03-06 11:28:21 - DEBUG CoordinatedClient: 'test client disconnected'
2017-03-06 11:28:21 - DEBUG CoordinatedClient: 'test client succeed'
2017-03-06 11:28:21 - DEBUG CoordinatedThaliTape: 'all tests succeed'
2017-03-06 11:28:21 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'
2017-03-06 11:28:21 - INFO runTests: 'Finished'
[39m
[32m2017-03-06 11:28:21 - DEBUG CoordinatedClient: 'test client disconnected'
2017-03-06 11:28:21 - DEBUG CoordinatedClient: 'test client succeed'
[39m
[32m2017-03-06 11:28:21 - DEBUG CoordinatedThaliTape: 'all tests succeed'
2017-03-06 11:28:21 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'
2017-03-06 11:28:21 - INFO runTests: 'Finished'

1..9
# tests 9
# pass  9

# ok

[39m
[33m
1..9
# tests 9
# pass  9

# ok

[39m
[36m
1..9
# tests 9
# pass  9

# ok

[39m
[32mExit code: 0. Exit signal: null[39m
[33mExit code: 0. Exit signal: null[39m
[36mExit code: 0. Exit signal: null[39m
end desktop tests


remove the previous build result (if any) to start from a clean state.

start setUpTests.sh

start preparing ThaliTest Cordova project
install@0.0.1 /Users/thali/Github/testBuild/thali/install
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
│ │ └─┬ async@2.1.5 
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
│ │ ├─┬ jsprim@1.3.1 
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
│ ├─┬ mime-types@2.1.14 
│ │ └── mime-db@1.26.0 
│ ├── oauth-sign@0.8.2 
│ ├── qs@6.2.2 
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
thali-test-server@0.0.1 /Users/thali/Github/testBuild/test/TestServer
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

end preparing ThaliTest Cordova project


start adding Android platform into ThaliTest
Adding android project...
Creating Cordova project for the Android platform:
	Path: platforms/android
	Package: com.test.thalitest
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

Total time: 13.511 secs
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

Total time: 1.942 secs

               This plugin is only applicable for versions of cordova-android greater than 4.0. If you have a previous platform version, you do *not* need this plugin since the whitelist will be built in.
          
end adding Android platform


start adding iOS platform into ThaliTest
Adding ios project...
Creating Cordova project for the iOS platform:
	Path: platforms/ios
	Package: com.test.thalitest
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
<widget id="com.test.thalitest" version="1.0.0" xmlns="http://www.w3.org/ns/widgets" xmlns:cdv="http://cordova.apache.org/ns/1.0">
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
 GET http://192.168.1.100:4873/child-process-promise

npm 
http request GET http://192.168.1.100:4873/end-with

npm 
http request GET http://192.168.1.100:4873/findit

npm
 http request GET http://192.168.1.100:4873/bluebird

npm 
http request GET http://192.168.1.100:4873/randomstring

npm 
http request GET http://192.168.1.100:4873/node-uuid

npm
 http request GET http://192.168.1.100:4873/fs-extra-promise

npm
 http 
request
 GET http://192.168.1.100:4873/jxc

npm 
http request GET http://192.168.1.100:4873/lie

npm
 http request
 GET http://192.168.1.100:4873/request

npm http 
request
 GET http://192.168.1.100:4873/unzip

npm http
 request GET http://192.168.1.100:4873/xcode

npm
 
http 
304
 http://192.168.1.100:4873/findit

npm http 304 http://192.168.1.100:4873/bluebird

npm
 
http
 
304
 http://192.168.1.100:4873/end-with

npm
 
http
 304
 http://192.168.1.100:4873/child-process-promise

npm 
http 304 http://192.168.1.100:4873/node-uuid

npm http
 304 http://192.168.1.100:4873/randomstring

npm 
http
 
304 http://192.168.1.100:4873/fs-extra-promise

npm 
http 304
 http://192.168.1.100:4873/jxc

npm http
 304 http://192.168.1.100:4873/lie

npm
 http
 304
 http://192.168.1.100:4873/unzip

npm http
 304 http://192.168.1.100:4873/xcode

npm http
 304 http://192.168.1.100:4873/request

npm
 http request GET http://192.168.1.100:4873/q

npm http
 304 http://192.168.1.100:4873/q

npm
 http request GET http://192.168.1.100:4873/fs-extra

npm http 304 http://192.168.1.100:4873/fs-extra

npm 
http request GET http://192.168.1.100:4873/graceful-fs

npm 
http request GET http://192.168.1.100:4873/jsonfile

npm http request GET http://192.168.1.100:4873/rimraf

npm http 304 http://192.168.1.100:4873/graceful-fs

npm http 304 http://192.168.1.100:4873/jsonfile

npm http 304 http://192.168.1.100:4873/rimraf

npm http request GET http://192.168.1.100:4873/glob

npm http 304 http://192.168.1.100:4873/glob

npm http request GET http://192.168.1.100:4873/fs.realpath

npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/minimatch

npm http request GET http://192.168.1.100:4873/once

npm http request GET http://192.168.1.100:4873/path-is-absolute

npm 
http 304 http://192.168.1.100:4873/inflight

npm http 304 http://192.168.1.100:4873/fs.realpath

npm http 304 http://192.168.1.100:4873/inherits

npm http
 304 http://192.168.1.100:4873/minimatch

npm http 304 http://192.168.1.100:4873/once

npm 
http 304 http://192.168.1.100:4873/path-is-absolute

npm 
http request GET http://192.168.1.100:4873/wrappy

npm 
http 304 http://192.168.1.100:4873/wrappy

npm 
http request GET http://192.168.1.100:4873/brace-expansion

npm http 304 http://192.168.1.100:4873/brace-expansion

npm http request GET http://192.168.1.100:4873/balanced-match

npm http request GET http://192.168.1.100:4873/concat-map

npm http
 304 http://192.168.1.100:4873/balanced-match

npm http 304
 http://192.168.1.100:4873/concat-map

npm
 
http
 
request
 GET http://192.168.1.100:4873/adm-zip

npm
 http request GET http://192.168.1.100:4873/progress

npm
 
http
 
304
 http://192.168.1.100:4873/adm-zip

npm
 
http 304 http://192.168.1.100:4873/progress

npm http
 request GET http://192.168.1.100:4873/immediate

npm
 
http 304 http://192.168.1.100:4873/immediate

npm http
 request GET http://192.168.1.100:4873/array-uniq

npm http 304 http://192.168.1.100:4873/array-uniq

npm 
http request GET http://192.168.1.100:4873/aws-sign2

npm
 http request GET http://192.168.1.100:4873/aws4

npm 
http request GET http://192.168.1.100:4873/bl

npm 
http request GET http://192.168.1.100:4873/caseless

npm 
http request GET http://192.168.1.100:4873/combined-stream

npm 
http request GET http://192.168.1.100:4873/extend

npm
 http request GET http://192.168.1.100:4873/forever-agent

npm http request
 GET http://192.168.1.100:4873/form-data

npm http request GET http://192.168.1.100:4873/har-validator

npm 
http request GET http://192.168.1.100:4873/http-signature

npm
 http request GET http://192.168.1.100:4873/is-typedarray

npm http
 request GET http://192.168.1.100:4873/isstream

npm 
http request GET http://192.168.1.100:4873/json-stringify-safe

npm http request GET http://192.168.1.100:4873/mime-types

npm http
 request GET http://192.168.1.100:4873/hawk

npm 
http request GET http://192.168.1.100:4873/oauth-sign

npm 
http request GET http://192.168.1.100:4873/stringstream

npm 
http request GET http://192.168.1.100:4873/qs

npm http
 request GET http://192.168.1.100:4873/tough-cookie

npm 
http request GET http://192.168.1.100:4873/tunnel-agent

npm
 
http 304
 http://192.168.1.100:4873/aws-sign2

npm
 http
 
304 http://192.168.1.100:4873/aws4

npm http
 304 http://192.168.1.100:4873/bl

npm 
http 304 http://192.168.1.100:4873/caseless

npm 
http 304 http://192.168.1.100:4873/extend

npm http 304 http://192.168.1.100:4873/combined-stream

npm http 
304 http://192.168.1.100:4873/forever-agent

npm http 
304 http://192.168.1.100:4873/form-data

npm http 304 http://192.168.1.100:4873/http-signature

npm http 304
 http://192.168.1.100:4873/har-validator

npm http 304
 http://192.168.1.100:4873/is-typedarray

npm 
http 304 http://192.168.1.100:4873/isstream

npm 
http 304 http://192.168.1.100:4873/json-stringify-safe

npm http
 304 http://192.168.1.100:4873/mime-types

npm http 304 http://192.168.1.100:4873/oauth-sign

npm
 http 304 http://192.168.1.100:4873/stringstream

npm 
http 304 http://192.168.1.100:4873/hawk

npm 
http 304 http://192.168.1.100:4873/qs

npm 
http 304 http://192.168.1.100:4873/tunnel-agent

npm 
http 304 http://192.168.1.100:4873/tough-cookie

npm http fetch
 GET http://192.168.1.100:4873/forever-agent/-/forever-agent-0.6.1.tgz

npm 
http fetch 200 http://192.168.1.100:4873/forever-agent/-/forever-agent-0.6.1.tgz

npm 
http
 
request
 GET http://192.168.1.100:4873/readable-stream

npm
 
http
 
304
 http://192.168.1.100:4873/readable-stream

npm
 
http
 
request
 GET http://192.168.1.100:4873/core-util-is

npm
 
http
 
request
 GET http://192.168.1.100:4873/isarray

npm http request GET http://192.168.1.100:4873/process-nextick-args

npm
 
http request
 GET http://192.168.1.100:4873/string_decoder

npm
 
http
 
request
 GET http://192.168.1.100:4873/util-deprecate

npm
 
http
 304
 http://192.168.1.100:4873/process-nextick-args

npm http 
304 http://192.168.1.100:4873/core-util-is

npm 
http 304 http://192.168.1.100:4873/isarray

npm http
 304 http://192.168.1.100:4873/util-deprecate

npm
 
http 
304
 http://192.168.1.100:4873/string_decoder

npm http request GET http://192.168.1.100:4873/delayed-stream

npm
 http
 
304
 http://192.168.1.100:4873/delayed-stream

npm http request GET http://192.168.1.100:4873/async

npm http 304 http://192.168.1.100:4873/async

npm http request GET http://192.168.1.100:4873/lodash

npm http 304 http://192.168.1.100:4873/lodash

npm http request
 GET http://192.168.1.100:4873/mime-db

npm http 304 http://192.168.1.100:4873/mime-db

npm http request GET http://192.168.1.100:4873/chalk

npm http request GET http://192.168.1.100:4873/commander

npm
 http request
 GET http://192.168.1.100:4873/is-my-json-valid

npm http 
request GET http://192.168.1.100:4873/pinkie-promise

npm http 304 http://192.168.1.100:4873/commander

npm http 
304 http://192.168.1.100:4873/pinkie-promise

npm http 304
 http://192.168.1.100:4873/chalk

npm http 304 http://192.168.1.100:4873/is-my-json-valid

npm
 
http
 
request
 GET http://192.168.1.100:4873/escape-string-regexp

npm 
http request GET http://192.168.1.100:4873/ansi-styles

npm
 http 
request
 GET http://192.168.1.100:4873/has-ansi

npm http
 request GET http://192.168.1.100:4873/strip-ansi

npm http request GET http://192.168.1.100:4873/supports-color

npm http 304 http://192.168.1.100:4873/escape-string-regexp

npm http 304
 http://192.168.1.100:4873/ansi-styles

npm
 http 304 http://192.168.1.100:4873/has-ansi

npm 
http 304 http://192.168.1.100:4873/strip-ansi

npm http 304 http://192.168.1.100:4873/supports-color

npm http 
request GET http://192.168.1.100:4873/ansi-regex

npm http 304 http://192.168.1.100:4873/ansi-regex

npm http request GET http://192.168.1.100:4873/graceful-readlink

npm http
 304 http://192.168.1.100:4873/graceful-readlink

npm http 
request GET http://192.168.1.100:4873/generate-function

npm http
 request GET http://192.168.1.100:4873/generate-object-property

npm http request GET http://192.168.1.100:4873/jsonpointer

npm http request GET http://192.168.1.100:4873/xtend

npm http 
304 http://192.168.1.100:4873/generate-function

npm http 304 http://192.168.1.100:4873/generate-object-property

npm http 304 http://192.168.1.100:4873/jsonpointer

npm http 304
 http://192.168.1.100:4873/xtend

npm 
http request GET http://192.168.1.100:4873/is-property

npm
 http 304 http://192.168.1.100:4873/is-property

npm http request GET http://192.168.1.100:4873/pinkie

npm http 304 http://192.168.1.100:4873/pinkie

npm http request GET http://192.168.1.100:4873/hoek

npm http request GET http://192.168.1.100:4873/boom

npm
 
http request GET http://192.168.1.100:4873/cryptiles

npm http request GET http://192.168.1.100:4873/sntp

npm http 304 http://192.168.1.100:4873/hoek

npm http 304 http://192.168.1.100:4873/cryptiles

npm
 http 304 http://192.168.1.100:4873/sntp

npm http 304 http://192.168.1.100:4873/boom

npm
 http
 
request
 GET http://192.168.1.100:4873/assert-plus

npm
 
http
 
request
 GET http://192.168.1.100:4873/jsprim

npm
 http 
request
 GET http://192.168.1.100:4873/sshpk

npm 
http
 
304
 http://192.168.1.100:4873/jsprim

npm http
 304 http://192.168.1.100:4873/assert-plus

npm http 304
 http://192.168.1.100:4873/sshpk

npm
 
http
 
request
 GET http://192.168.1.100:4873/extsprintf

npm
 
http
 request GET http://192.168.1.100:4873/json-schema

npm
 
http request GET http://192.168.1.100:4873/verror

npm
 
http 304 http://192.168.1.100:4873/json-schema

npm
 http 
304
 http://192.168.1.100:4873/verror

npm http
 304 http://192.168.1.100:4873/extsprintf

npm http request GET http://192.168.1.100:4873/asn1

npm 
http
 
request GET http://192.168.1.100:4873/dashdash

npm
 http request GET http://192.168.1.100:4873/getpass

npm http
 304 http://192.168.1.100:4873/asn1

npm http 304
 http://192.168.1.100:4873/dashdash

npm http
 304 http://192.168.1.100:4873/getpass

npm http request GET http://192.168.1.100:4873/punycode

npm
 http 304 http://192.168.1.100:4873/punycode

npm http request GET http://192.168.1.100:4873/fstream

npm http request GET http://192.168.1.100:4873/pullstream

npm http request GET http://192.168.1.100:4873/binary

npm http request GET http://192.168.1.100:4873/setimmediate

npm http request GET http://192.168.1.100:4873/match-stream

npm
 http 304
 http://192.168.1.100:4873/fstream

npm http 304 http://192.168.1.100:4873/pullstream

npm http 304 http://192.168.1.100:4873/binary

npm http 304 http://192.168.1.100:4873/setimmediate

npm http 304 http://192.168.1.100:4873/match-stream

npm http request GET http://192.168.1.100:4873/chainsaw

npm http
 request GET http://192.168.1.100:4873/buffers

npm http 304 http://192.168.1.100:4873/buffers

npm http 304 http://192.168.1.100:4873/chainsaw

npm http request GET http://192.168.1.100:4873/traverse

npm http 304 http://192.168.1.100:4873/traverse

npm http request GET http://192.168.1.100:4873/mkdirp

npm http 304 http://192.168.1.100:4873/mkdirp

npm http request GET http://192.168.1.100:4873/natives

npm http 
304 http://192.168.1.100:4873/natives

npm http request GET http://192.168.1.100:4873/minimist

npm http 304 http://192.168.1.100:4873/minimist

npm http request GET http://192.168.1.100:4873/over

npm http request GET http://192.168.1.100:4873/slice-stream

npm http 304 http://192.168.1.100:4873/over

npm http 304 http://192.168.1.100:4873/slice-stream

npm http 
request GET http://192.168.1.100:4873/simple-plist

npm http request GET http://192.168.1.100:4873/pegjs

npm http 304 http://192.168.1.100:4873/pegjs

npm http 304 http://192.168.1.100:4873/simple-plist

npm http request GET http://192.168.1.100:4873/plist

npm http request GET http://192.168.1.100:4873/bplist-parser

npm http request GET http://192.168.1.100:4873/bplist-creator

npm http 304 http://192.168.1.100:4873/plist

npm http 304 http://192.168.1.100:4873/bplist-creator

npm http 304 http://192.168.1.100:4873/bplist-parser

npm http request GET http://192.168.1.100:4873/stream-buffers

npm
 http 304 http://192.168.1.100:4873/stream-buffers

npm http request GET http://192.168.1.100:4873/xmlbuilder

npm http request GET http://192.168.1.100:4873/xmldom

npm http request GET http://192.168.1.100:4873/base64-js

npm http 304 http://192.168.1.100:4873/xmldom

npm http 304 http://192.168.1.100:4873/xmlbuilder

npm http 304 http://192.168.1.100:4873/base64-js

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
│ └── q@1.4.1 
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
npm
 WARN install@0.0.1 No repository field.

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
│ │ ├─┬ async@2.1.5 
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
│ │ └── mime-types@2.1.14 
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
│ │ ├─┬ jsprim@1.3.1 
│ │ │ │ utilities for primitive JavaScript types
│ │ │ │ git://github.com/davepacheco/node-jsprim.git
│ │ │ │ https://github.com/davepacheco/node-jsprim#readme
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
│ ├─┬ mime-types@2.1.14 
│ │ │ The ultimate javascript content-type utility.
│ │ │ git+https://github.com/jshttp/mime-types.git
│ │ │ https://github.com/jshttp/mime-types#readme
│ │ └── mime-db@1.26.0 
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
│ ├── qs@6.2.2 
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
│ │ └─┬ chainsaw@0.1.0 
│ │   │ Build chainable fluent interfaces the easy way... with a freakin' chainsaw!
│ │   │ git://github.com/substack/node-chainsaw.git
│ │   │ https://github.com/substack/node-chainsaw#re
adme
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
└─┬ xcode@0.8.9 
  │ parser for xcodeproj/project.pbxproj files
  │ git+https://github.com/alunny/node-xcode.git
  │ https://github.com/alunny/node-xcode#readme
  ├── node-uuid@1.4.7 
  │   Rigorous implementation of RFC4122 (v1 and v4) UUIDs.
  │   git+https://github.com/broofa/node-uuid.git
  │   https://github.com/broofa/node-uuid
  ├── pegjs@0.9.0 
  │   Parser generator for 
JavaScript
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

[1A[K
Attempt 1 / 3

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




Total time: 1.832 secs


Subproject Path: CordovaLib

Preparing UT test environment

Removing UT flag

Installing "org.thaliproject.p2p" for ios


Updating JXcoreExtension.m

Removing UT flag

Building ThaliCore.framework

Failed to install 'org.thaliproject.p2p':Error: Command failed: set -o pipefail && xcodebuild -project "/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCore.xcodeproj" -scheme "ThaliCoreCITests" -configuration Release -sdk iphoneos ONLY_ACTIVE_ARCH=NO  BUILD_DIR="/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/build" clean build
** CLEAN FAILED **


The following build commands failed:
	Check dependencies
(1 failure)
** BUILD FAILED **


The following build commands failed:
	Check dependencies
(1 failure)
 `set -o pipefail && xcodebuild -project "/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCore.xcodeproj" -scheme "ThaliCoreCITests" -configuration Release -sdk iphoneos ONLY_ACTIVE_ARCH=NO  BUILD_DIR="/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/build" clean build` (exited with error code 65)
    at ChildProcess.exithandler (child_process.js:206:12)
    at emitTwo (events.js:106:13)
    at ChildProcess.emit (events.js:191:7)
    at maybeClose (internal/child_process.js:877:16)
    at Process.ChildProcess._handle.onexit (internal/child_process.js:226:5)


Error: Command failed: set -o pipefail && xcodebuild -project "/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCore.xcodeproj" -scheme "ThaliCoreCITests" -configuration Release -sdk iphoneos ONLY_ACTIVE_ARCH=NO  BUILD_DIR="/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/build" clean build
** CLEAN FAILED **


The following build commands failed:
	Check dependencies
(1 failure)
** BUILD FAILED **


The following build commands failed:
	Check dependencies
(1 failure)
 `set -o pipefail && xcodebuild -project "/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCore.xcodeproj" -scheme "ThaliCoreCITests" -configuration Release -sdk iphoneos ONLY_ACTIVE_ARCH=NO  BUILD_DIR="/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/build" clean build` (exited with error code 65)


Failed with - `cordova plugins add /Users/thali/Github/ThaliTest/thaliDontCheckIn/Thali_CordovaPlugin-iOS` (exited with error code1)

[0;31merror: command 'thali/install/setUpTests.sh $TEST_TYPE $SERVER_ADDRESS' failed with code 1, file 'build.sh' on line 94[0m
./build.sh CI FAILED - build.sh failure[0m

npm WARN thali-test-server@0.0.1 No repository field.
npm WARN thali-test-server@0.0.1 No license field.
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/javascript-state-machine
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-leveldb-core
npm http request GET http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/javascript-state-machine
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/bluebird
npm http 200 http://192.168.1.100:4873/ip
npm http 200 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/lie
npm http 304 http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/multiplex
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-leveldb-core
npm http 304 http://192.168.1.100:4873/winston
npm http 304 http://192.168.1.100:4873/urlsafe-base64
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
npm http request GET http://192.168.1.100:4873/raw-body
npm http request GET http://192.168.1.100:4873/type-is
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/bytes
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/type-is
npm http 304 http://192.168.1.100:4873/iconv-lite
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
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/send
npm http 304 http://192.168.1.100:4873/utils-merge
npm http 304 http://192.168.1.100:4873/serve-static
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
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/varint
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/stream-shift
npm http 304 http://192.168.1.100:4873/end-of-stream
npm http 304 http://192.168.1.100:4873/stream-shift
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
npm http 304 http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/string_decoder
npm http 200 http://192.168.1.100:4873/core-util-is
npm http 304 http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/buffer-from
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/pouchdb-errors
npm http request GET http://192.168.1.100:4873/pouchdb-merge
npm http request GET http://192.168.1.100:4873/pouchdb-md5
npm http request GET http://192.168.1.100:4873/argsarray
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-utils
npm http request GET http://192.168.1.100:4873/pouchdb-binary-utils
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/pouchdb-json
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/pouchdb-utils
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/buffer-from
npm http 304 http://192.168.1.100:4873/double-ended-queue
npm http 304 http://192.168.1.100:4873/pouchdb-errors
npm http 304 http://192.168.1.100:4873/pouchdb-merge
npm http 304 http://192.168.1.100:4873/pouchdb-md5
npm http 200 http://192.168.1.100:4873/argsarray
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-utils
npm http 304 http://192.168.1.100:4873/pouchdb-binary-utils
npm http 304 http://192.168.1.100:4873/pouchdb-collections
npm http 304 http://192.168.1.100:4873/pouchdb-json
npm http 304 http://192.168.1.100:4873/sublevel-pouchdb
npm http 304 http://192.168.1.100:4873/through2
npm http 304 http://192.168.1.100:4873/pouchdb-utils
npm http 200 http://192.168.1.100:4873/pouchdb-promise
npm http 200 http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/is-array-buffer-x
npm http 304 http://192.168.1.100:4873/is-array-buffer-x
npm http request GET http://192.168.1.100:4873/is-object-like-x
npm http request GET http://192.168.1.100:4873/to-string-tag-x
npm http request GET http://192.168.1.100:4873/has-to-string-tag-x
npm http 304 http://192.168.1.100:4873/is-object-like-x
npm http 304 http://192.168.1.100:4873/has-to-string-tag-x
npm http 304 http://192.168.1.100:4873/to-string-tag-x
npm http request GET http://192.168.1.100:4873/has-symbol-support-x
npm http 304 http://192.168.1.100:4873/has-symbol-support-x
npm http request GET http://192.168.1.100:4873/is-primitive
npm http request GET http://192.168.1.100:4873/is-function-x
npm http 304 http://192.168.1.100:4873/is-primitive
npm http 304 http://192.168.1.100:4873/is-function-x
npm http request GET http://192.168.1.100:4873/validate.io-undefined
npm http request GET http://192.168.1.100:4873/lodash.isnull
npm http 304 http://192.168.1.100:4873/validate.io-undefined
npm http 304 http://192.168.1.100:4873/lodash.isnull
npm http request GET http://192.168.1.100:4873/prr
npm http request GET http://192.168.1.100:4873/level-codec
npm http request GET http://192.168.1.100:4873/deferred-leveldown
npm http request GET http://192.168.1.100:4873/level-iterator-stream
npm http request GET http://192.168.1.100:4873/level-errors
npm http request GET http://192.168.1.100:4873/semver
npm http 304 http://192.168.1.100:4873/prr
npm http 304 http://192.168.1.100:4873/level-codec
npm http 304 http://192.168.1.100:4873/level-errors
npm http 304 http://192.168.1.100:4873/level-iterator-stream
npm http 304 http://192.168.1.100:4873/deferred-leveldown
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
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 200 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/http-signature
npm http 200 http://192.168.1.100:4873/tunnel-agent
npm http 200 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/hawk
npm http 200 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 200 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/lodash
npm http 200 http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/chalk
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/is-my-json-valid
npm http 200 http://192.168.1.100:4873/chalk
npm http 200 http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 200 http://192.168.1.100:4873/ansi-styles
npm http 304 http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http 304 http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-function
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http request GET http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/hoek
npm http 304 http://192.168.1.100:4873/boom
npm http 304 http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/cryptiles
npm http 304 http://192.168.1.100:4873/hoek
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
npm http 304 http://192.168.1.100:4873/cycle
npm http 304 http://192.168.1.100:4873/eyes
npm http 304 http://192.168.1.100:4873/pkginfo
npm http 304 http://192.168.1.100:4873/stack-trace
npm http request GET http://192.168.1.100:4873/jsdoc
npm http request GET http://192.168.1.100:4873/eslint
npm http 304 http://192.168.1.100:4873/jsdoc
npm http 200 http://192.168.1.100:4873/eslint
npm http request GET http://192.168.1.100:4873/escope
npm http request GET http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/babel-code-frame
npm http request GET http://192.168.1.100:4873/doctrine
npm http request GET http://192.168.1.100:4873/espree
npm http request GET http://192.168.1.100:4873/esutils
npm http request GET http://192.168.1.100:4873/estraverse
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/file-entry-cache
npm http request GET http://192.168.1.100:4873/globals
npm http request GET http://192.168.1.100:4873/imurmurhash
npm http request GET http://192.168.1.100:4873/ignore
npm http request GET http://192.168.1.100:4873/is-resolvable
npm http request GET http://192.168.1.100:4873/js-yaml
npm http request GET http://192.168.1.100:4873/inquirer
npm http request GET http://192.168.1.100:4873/json-stable-stringify
npm http request GET http://192.168.1.100:4873/levn
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/natural-compare
npm http request GET http://192.168.1.100:4873/optionator
npm http request GET http://192.168.1.100:4873/path-is-inside
npm http request GET http://192.168.1.100:4873/progress
npm http request GET http://192.168.1.100:4873/pluralize
npm http request GET http://192.168.1.100:4873/require-uncached
npm http request GET http://192.168.1.100:4873/strip-bom
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/shelljs
npm http request GET http://192.168.1.100:4873/text-table
npm http request GET http://192.168.1.100:4873/table
npm http request GET http://192.168.1.100:4873/user-home
npm http 304 http://192.168.1.100:4873/escope
npm http 304 http://192.168.1.100:4873/doctrine
npm http 304 http://192.168.1.100:4873/espree
npm http 304 http://192.168.1.100:4873/concat-stream
npm http 200 http://192.168.1.100:4873/babel-code-frame
npm http 304 http://192.168.1.100:4873/esutils
npm http 304 http://192.168.1.100:4873/estraverse
npm http 304 http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/file-entry-cache
npm http 304 http://192.168.1.100:4873/globals
npm http 304 http://192.168.1.100:4873/imurmurhash
npm http 304 http://192.168.1.100:4873/is-resolvable
npm http 304 http://192.168.1.100:4873/ignore
npm http 200 http://192.168.1.100:4873/js-yaml
npm http 200 http://192.168.1.100:4873/inquirer
npm http 304 http://192.168.1.100:4873/json-stable-stringify
npm http 304 http://192.168.1.100:4873/levn
npm http 304 http://192.168.1.100:4873/natural-compare
npm http fetch GET http://192.168.1.100:4873/js-yaml/-/js-yaml-3.8.2.tgz
npm http 200 http://192.168.1.100:4873/mkdirp
npm http 304 http://192.168.1.100:4873/optionator
npm http 304 http://192.168.1.100:4873/path-is-inside
npm http 200 http://192.168.1.100:4873/require-uncached
npm http 200 http://192.168.1.100:4873/pluralize
npm http 200 http://192.168.1.100:4873/progress
npm http 304 http://192.168.1.100:4873/strip-bom
npm http 200 http://192.168.1.100:4873/strip-json-comments
npm http fetch 200 http://192.168.1.100:4873/js-yaml/-/js-yaml-3.8.2.tgz
npm http 304 http://192.168.1.100:4873/text-table
npm http 304 http://192.168.1.100:4873/user-home
npm http 200 http://192.168.1.100:4873/shelljs
npm http 200 http://192.168.1.100:4873/table
npm http request GET http://192.168.1.100:4873/js-tokens
npm http 304 http://192.168.1.100:4873/js-tokens
npm http request GET http://192.168.1.100:4873/typedarray
npm http 304 http://192.168.1.100:4873/typedarray
npm http request GET http://192.168.1.100:4873/es6-weak-map
npm http request GET http://192.168.1.100:4873/es6-map
npm http request GET http://192.168.1.100:4873/esrecurse
npm http 304 http://192.168.1.100:4873/es6-weak-map
npm http 304 http://192.168.1.100:4873/es6-map
npm http 304 http://192.168.1.100:4873/esrecurse
npm http request GET http://192.168.1.100:4873/d
npm http request GET http://192.168.1.100:4873/es6-iterator
npm http request GET http://192.168.1.100:4873/es6-set
npm http request GET http://192.168.1.100:4873/es5-ext
npm http request GET http://192.168.1.100:4873/es6-symbol
npm http request GET http://192.168.1.100:4873/event-emitter
npm http 304 http://192.168.1.100:4873/d
npm http 304 http://192.168.1.100:4873/es6-iterator
npm http 304 http://192.168.1.100:4873/es6-set
npm http 304 http://192.168.1.100:4873/es6-symbol
npm http 304 http://192.168.1.100:4873/es5-ext
npm http 304 http://192.168.1.100:4873/event-emitter
npm http request GET http://192.168.1.100:4873/acorn
npm http request GET http://192.168.1.100:4873/acorn-jsx
npm http 304 http://192.168.1.100:4873/acorn-jsx
npm http 200 http://192.168.1.100:4873/acorn
npm http request GET http://192.168.1.100:4873/flat-cache
npm http 304 http://192.168.1.100:4873/flat-cache
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/circular-json
npm http request GET http://192.168.1.100:4873/del
npm http request GET http://192.168.1.100:4873/write
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http 304 http://192.168.1.100:4873/circular-json
npm http 304 http://192.168.1.100:4873/write
npm http 200 http://192.168.1.100:4873/del
npm http request GET http://192.168.1.100:4873/is-path-cwd
npm http request GET http://192.168.1.100:4873/globby
npm http request GET http://192.168.1.100:4873/is-path-in-cwd
npm http request GET http://192.168.1.100:4873/pify
npm http request GET http://192.168.1.100:4873/rimraf
npm http request GET http://192.168.1.100:4873/pinkie-promise
npm http 304 http://192.168.1.100:4873/is-path-cwd
npm http 304 http://192.168.1.100:4873/globby
npm http 304 http://192.168.1.100:4873/is-path-in-cwd
npm http 304 http://192.168.1.100:4873/rimraf
npm http 200 http://192.168.1.100:4873/pify
npm http 304 http://192.168.1.100:4873/pinkie-promise
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
npm http 304 http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/minimatch
npm http 304 http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 304 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/pinkie
npm http 304 http://192.168.1.100:4873/pinkie
npm http request GET http://192.168.1.100:4873/is-path-inside
npm http 304 http://192.168.1.100:4873/is-path-inside
npm http request GET http://192.168.1.100:4873/minimist
npm http 200 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/ansi-escapes
npm http request GET http://192.168.1.100:4873/cli-cursor
npm http request GET http://192.168.1.100:4873/cli-width
npm http request GET http://192.168.1.100:4873/figures
npm http request GET http://192.168.1.100:4873/readline2
npm http request GET http://192.168.1.100:4873/run-async
npm http request GET http://192.168.1.100:4873/string-width
npm http request GET http://192.168.1.100:4873/rx-lite
npm http request GET http://192.168.1.100:4873/through
npm http 304 http://192.168.1.100:4873/cli-cursor
npm http 304 http://192.168.1.100:4873/ansi-escapes
npm http 304 http://192.168.1.100:4873/cli-width
npm http 304 http://192.168.1.100:4873/readline2
npm http 304 http://192.168.1.100:4873/figures
npm http 304 http://192.168.1.100:4873/string-width
npm http 304 http://192.168.1.100:4873/run-async
npm http 304 http://192.168.1.100:4873/rx-lite
npm http 200 http://192.168.1.100:4873/through
npm http request GET http://192.168.1.100:4873/restore-cursor
npm http 304 http://192.168.1.100:4873/restore-cursor
npm http request GET http://192.168.1.100:4873/exit-hook
npm http request GET http://192.168.1.100:4873/onetime
npm http 304 http://192.168.1.100:4873/exit-hook
npm http 200 http://192.168.1.100:4873/onetime
npm http request GET http://192.168.1.100:4873/code-point-at
npm http request GET http://192.168.1.100:4873/is-fullwidth-code-point
npm http request GET http://192.168.1.100:4873/mute-stream
npm http 304 http://192.168.1.100:4873/code-point-at
npm http 304 http://192.168.1.100:4873/is-fullwidth-code-point
npm http 304 http://192.168.1.100:4873/mute-stream
npm http request GET http://192.168.1.100:4873/number-is-nan
npm http 200 http://192.168.1.100:4873/number-is-nan
npm http request GET http://192.168.1.100:4873/tryit
npm http 304 http://192.168.1.100:4873/tryit
npm http request GET http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/argparse
npm http 304 http://192.168.1.100:4873/argparse
npm http 200 http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/sprintf-js
npm http 304 http://192.168.1.100:4873/sprintf-js
npm http request GET http://192.168.1.100:4873/jsonify
npm http 304 http://192.168.1.100:4873/jsonify
npm http request GET http://192.168.1.100:4873/prelude-ls
npm http request GET http://192.168.1.100:4873/type-check
npm http 304 http://192.168.1.100:4873/prelude-ls
npm http 304 http://192.168.1.100:4873/type-check
npm http request GET http://192.168.1.100:4873/wordwrap
npm http request GET http://192.168.1.100:4873/deep-is
npm http request GET http://192.168.1.100:4873/fast-levenshtein
npm http 304 http://192.168.1.100:4873/deep-is
npm http 304 http://192.168.1.100:4873/fast-levenshtein
npm http 304 http://192.168.1.100:4873/wordwrap
npm http request GET http://192.168.1.100:4873/caller-path
npm http request GET http://192.168.1.100:4873/resolve-from
npm http 304 http://192.168.1.100:4873/caller-path
npm http 304 http://192.168.1.100:4873/resolve-from
npm http request GET http://192.168.1.100:4873/callsites
npm http 304 http://192.168.1.100:4873/callsites
npm http request GET http://192.168.1.100:4873/interpret
npm http request GET http://192.168.1.100:4873/rechoir
npm http 304 http://192.168.1.100:4873/interpret
npm http 304 http://192.168.1.100:4873/rechoir
npm http request GET http://192.168.1.100:4873/resolve
npm http 304 http://192.168.1.100:4873/resolve
npm http request GET http://192.168.1.100:4873/path-parse
npm http 304 http://192.168.1.100:4873/path-parse
npm http request GET http://192.168.1.100:4873/slice-ansi
npm http request GET http://192.168.1.100:4873/ajv
npm http request GET http://192.168.1.100:4873/ajv-keywords
npm http 304 http://192.168.1.100:4873/slice-ansi
npm http 200 http://192.168.1.100:4873/ajv-keywords
npm http 200 http://192.168.1.100:4873/ajv
npm http fetch GET http://192.168.1.100:4873/ajv/-/ajv-4.11.4.tgz
npm http fetch 200 http://192.168.1.100:4873/ajv/-/ajv-4.11.4.tgz
npm http request GET http://192.168.1.100:4873/co
npm http 200 http://192.168.1.100:4873/co
npm http request GET http://192.168.1.100:4873/os-homedir
npm http 304 http://192.168.1.100:4873/os-homedir
npm http request GET http://192.168.1.100:4873/requizzle
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/js2xmlparser
npm http request GET http://192.168.1.100:4873/catharsis
npm http request GET http://192.168.1.100:4873/marked
npm http request GET http://192.168.1.100:4873/underscore
npm http request GET http://192.168.1.100:4873/wrench
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 304 http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/requizzle
npm http 304 http://192.168.1.100:4873/catharsis
npm http 200 http://192.168.1.100:4873/js2xmlparser
npm http 200 http://192.168.1.100:4873/marked
npm http 304 http://192.168.1.100:4873/wrench
npm http 200 http://192.168.1.100:4873/underscore
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
npm http request GET http://192.168.1.100:4873/bn.js
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/express-pouchdb
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/leveldown-mobile
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/nock
npm http request GET http://192.168.1.100:4873/pouchdb-size
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/pouchdb
npm http request GET http://192.168.1.100:4873/proxyquire
npm http request GET http://192.168.1.100:4873/request-promise
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/sinon
npm http request GET http://192.168.1.100:4873/stacky
npm http request GET http://192.168.1.100:4873/supertest-as-promised
npm http request GET http://192.168.1.100:4873/supertest
npm http request GET http://192.168.1.100:4873/tape-catch
npm http request GET http://192.168.1.100:4873/tmp
npm http request GET http://192.168.1.100:4873/tape
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/uuid-validate
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/bn.js
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/child-process-promise
npm http 304 http://192.168.1.100:4873/minimist
npm http 304 http://192.168.1.100:4873/js-extend
npm http 304 http://192.168.1.100:4873/multiplex
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/leveldown-mobile
npm http 304 http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/randomstring
npm http 200 http://192.168.1.100:4873/express-pouchdb
npm http 304 http://192.168.1.100:4873/pouchdb-size
npm http 304 http://192.168.1.100:4873/pouchdb
npm http 304 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/proxyquire
npm http 304 http://192.168.1.100:4873/socket.io-client
npm http 304 http://192.168.1.100:4873/stacky
npm http 304 http://192.168.1.100:4873/supertest-as-promised
npm http 304 http://192.168.1.100:4873/tape-catch
npm http 304 http://192.168.1.100:4873/tmp
npm http 200 http://192.168.1.100:4873/request-promise
npm http 200 http://192.168.1.100:4873/supertest
npm http 304 http://192.168.1.100:4873/urlsafe-base64
npm http 304 http://192.168.1.100:4873/uuid
npm http 304 http://192.168.1.100:4873/uuid-validate
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
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/bytes
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
npm http 304 http://192.168.1.100:4873/utils-merge
npm http 304 http://192.168.1.100:4873/vary
npm http request GET http://192.168.1.100:4873/negotiator
npm http 304 http://192.168.1.100:4873/negotiator
npm http request GET http://192.168.1.100:4873/ipaddr.js
npm http request GET http://192.168.1.100:4873/forwarded
npm http 304 http://192.168.1.100:4873/ipaddr.js
npm http 304 http://192.168.1.100:4873/forwarded
npm http request GET http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/mime
npm http 304 http://192.168.1.100:4873/destroy
npm http 304 http://192.168.1.100:4873/mime
npm http request GET http://192.168.1.100:4873/basic-auth
npm http request GET http://192.168.1.100:4873/cookie-parser
npm http request GET http://192.168.1.100:4873/compression
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/header-case-normalizer
npm http request GET http://192.168.1.100:4873/multiparty
npm http request GET http://192.168.1.100:4873/pouchdb-all-dbs
npm http request GET http://192.168.1.100:4873/pouchdb-auth
npm http request GET http://192.168.1.100:4873/pouchdb-list
npm http request GET http://192.168.1.100:4873/pouchdb-find
npm http request GET http://192.168.1.100:4873/pouchdb-rewrite
npm http request GET http://192.168.1.100:4873/pouchdb-replicator
npm http request GET http://192.168.1.100:4873/pouchdb-security
npm http request GET http://192.168.1.100:4873/pouchdb-show
npm http request GET http://192.168.1.100:4873/pouchdb-validation
npm http request GET http://192.168.1.100:4873/pouchdb-update
npm http request GET http://192.168.1.100:4873/pouchdb-vhost
npm http request GET http://192.168.1.100:4873/pouchdb-wrappers
npm http 304 http://192.168.1.100:4873/basic-auth
npm http 304 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/cookie-parser
npm http 304 http://192.168.1.100:4873/header-case-normalizer
npm http 200 http://192.168.1.100:4873/compression
npm http 304 http://192.168.1.100:4873/pouchdb-all-dbs
npm http 304 http://192.168.1.100:4873/pouchdb-auth
npm http 304 http://192.168.1.100:4873/pouchdb-list
npm http 304 http://192.168.1.100:4873/pouchdb-find
npm http 200 http://192.168.1.100:4873/multiparty
npm http 304 http://192.168.1.100:4873/pouchdb-rewrite
npm http 304 http://192.168.1.100:4873/pouchdb-validation
npm http 304 http://192.168.1.100:4873/pouchdb-show
npm http 200 http://192.168.1.100:4873/pouchdb-replicator
npm http 200 http://192.168.1.100:4873/pouchdb-security
npm http 304 http://192.168.1.100:4873/pouchdb-update
npm http 304 http://192.168.1.100:4873/pouchdb-vhost
npm http 304 http://192.168.1.100:4873/pouchdb-wrappers
npm http request GET http://192.168.1.100:4873/setprototypeof
npm http 304 http://192.168.1.100:4873/setprototypeof
npm http request GET http://192.168.1.100:4873/compressible
npm http request GET http://192.168.1.100:4873/on-headers
npm http 304 http://192.168.1.100:4873/compressible
npm http 200 http://192.168.1.100:4873/on-headers
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/stream-counter
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/stream-counter
npm http request GET http://192.168.1.100:4873/argsarray
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/tiny-queue
npm http 304 http://192.168.1.100:4873/es3ify
npm http 304 http://192.168.1.100:4873/argsarray
npm http 304 http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/tiny-queue
npm http request GET http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/base62
npm http 304 http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/base64url
npm http request GET http://192.168.1.100:4873/crypto-lite
npm http request GET http://192.168.1.100:4873/couchdb-calculate-session-id
npm http request GET http://192.168.1.100:4873/pouchdb-plugin-error
npm http request GET http://192.168.1.100:4873/pouchdb-system-db
npm http request GET http://192.168.1.100:4873/promise-nodify
npm http request GET http://192.168.1.100:4873/secure-random
npm http request GET http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http request GET http://192.168.1.100:4873/pouchdb-req-http-query
npm http 304 http://192.168.1.100:4873/base64url
npm http 304 http://192.168.1.100:4873/crypto-lite
npm http 304 http://192.168.1.100:4873/couchdb-calculate-session-id
npm http 304 http://192.168.1.100:4873/pouchdb-plugin-error
npm http 304 http://192.168.1.100:4873/pouchdb-system-db
npm http 304 http://192.168.1.100:4873/promise-nodify
npm http 304 http://192.168.1.100:4873/secure-random
npm http 304 http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http 304 http://192.168.1.100:4873/pouchdb-req-http-query
npm http request GET http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/meow
npm http 304 http://192.168.1.100:4873/concat-stream
npm http 200 http://192.168.1.100:4873/meow
npm http request GET http://192.168.1.100:4873/typedarray
npm http 304 http://192.168.1.100:4873/typedarray
npm http request GET http://192.168.1.100:4873/indent-string
npm http request GET http://192.168.1.100:4873/camelcase-keys
npm http 304 http://192.168.1.100:4873/indent-string
npm http 304 http://192.168.1.100:4873/camelcase-keys
npm http request GET http://192.168.1.100:4873/map-obj
npm http request GET http://192.168.1.100:4873/camelcase
npm http 304 http://192.168.1.100:4873/map-obj
npm http 200 http://192.168.1.100:4873/camelcase
npm http request GET http://192.168.1.100:4873/repeating
npm http request GET http://192.168.1.100:4873/get-stdin
npm http 304 http://192.168.1.100:4873/repeating
npm http 304 http://192.168.1.100:4873/get-stdin
npm http request GET http://192.168.1.100:4873/is-finite
npm http 304 http://192.168.1.100:4873/is-finite
npm http request GET http://192.168.1.100:4873/number-is-nan
npm http 304 http://192.168.1.100:4873/number-is-nan
npm http request GET http://192.168.1.100:4873/aproba
npm http 304 http://192.168.1.100:4873/aproba
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/localstorage-down
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/es6-promise-pool
npm http request GET http://192.168.1.100:4873/level-write-stream
npm http request GET http://192.168.1.100:4873/fruitdown
npm http request GET http://192.168.1.100:4873/memdown
npm http request GET http://192.168.1.100:4873/pouchdb-collate
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/scope-eval
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/vuvuzela
npm http 304 http://192.168.1.100:4873/double-ended-queue
npm http 304 http://192.168.1.100:4873/levelup
npm http 304 http://192.168.1.100:4873/localstorage-down
npm http 304 http://192.168.1.100:4873/pouchdb-collections
npm http 200 http://192.168.1.100:4873/es6-promise-pool
npm http 304 http://192.168.1.100:4873/level-write-stream
npm http 304 http://192.168.1.100:4873/memdown
npm http 304 http://192.168.1.100:4873/spark-md5
npm http 304 http://192.168.1.100:4873/pouchdb-collate
npm http 304 http://192.168.1.100:4873/fruitdown
npm http 304 http://192.168.1.100:4873/scope-eval
npm http 304 http://192.168.1.100:4873/sublevel-pouchdb
npm http 304 http://192.168.1.100:4873/through2
npm http 304 http://192.168.1.100:4873/vuvuzela
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
npm http 304 http://192.168.1.100:4873/level-errors
npm http 304 http://192.168.1.100:4873/level-codec
npm http 304 http://192.168.1.100:4873/prr
npm http 304 http://192.168.1.100:4873/level-iterator-stream
npm http 304 http://192.168.1.100:4873/semver
npm http request GET http://192.168.1.100:4873/errno
npm http 304 http://192.168.1.100:4873/errno
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
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/is-typedarray
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/tough-cookie
npm WARN deprecated tough-cookie@2.2.2: ReDoS vulnerability parsing Set-Cookie https://nodesecurity.io/advisories/130
npm http 304 http://192.168.1.100:4873/tunnel-agent
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
npm http 304 http://192.168.1.100:4873/chalk
npm http 304 http://192.168.1.100:4873/is-my-json-valid
npm http 304 http://192.168.1.100:4873/pinkie-promise
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
npm http request GET http://192.168.1.100:4873/couchdb-objects
npm http request GET http://192.168.1.100:4873/couchdb-eval
npm http request GET http://192.168.1.100:4873/random-uuid-v4
npm http 304 http://192.168.1.100:4873/couchdb-objects
npm http 304 http://192.168.1.100:4873/couchdb-eval
npm http 304 http://192.168.1.100:4873/random-uuid-v4
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
npm http 304 http://192.168.1.100:4873/ast-types
npm http 304 http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/couchdb-render
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/pouchdb-promise
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
npm http request GET http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/fast-future
npm http 304 http://192.168.1.100:4873/bindings
npm http 304 http://192.168.1.100:4873/fast-future
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
npm http request GET http://192.168.1.100:4873/propagate
npm http request GET http://192.168.1.100:4873/deep-equal
npm http request GET http://192.168.1.100:4873/chai
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/propagate
npm http 200 http://192.168.1.100:4873/deep-equal
npm http 200 http://192.168.1.100:4873/chai
npm http request GET http://192.168.1.100:4873/assertion-error
npm http request GET http://192.168.1.100:4873/deep-eql
npm http request GET http://192.168.1.100:4873/type-detect
npm http 304 http://192.168.1.100:4873/assertion-error
npm http 304 http://192.168.1.100:4873/deep-eql
npm http 304 http://192.168.1.100:4873/type-detect
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
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/leveldown
npm http 304 http://192.168.1.100:4873/buffer-from
npm http 304 http://192.168.1.100:4873/clone-buffer
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/double-ended-queue
npm http 304 http://192.168.1.100:4873/levelup
npm http 304 http://192.168.1.100:4873/spark-md5
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/leveldown
npm http request GET http://192.168.1.100:4873/is-array-buffer-x
npm http 304 http://192.168.1.100:4873/is-array-buffer-x
npm http request GET http://192.168.1.100:4873/is-object-like-x
npm http request GET http://192.168.1.100:4873/to-string-tag-x
npm http request GET http://192.168.1.100:4873/has-to-string-tag-x
npm http 304 http://192.168.1.100:4873/is-object-like-x
npm http 304 http://192.168.1.100:4873/to-string-tag-x
npm http 304 http://192.168.1.100:4873/has-to-string-tag-x
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
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/nan
npm http request GET http://192.168.1.100:4873/prebuild
npm http 304 http://192.168.1.100:4873/abstract-leveldown
npm http 304 http://192.168.1.100:4873/nan
npm http 200 http://192.168.1.100:4873/prebuild
npm http request GET http://192.168.1.100:4873/execspawn
npm http request GET http://192.168.1.100:4873/expand-template
npm http request GET http://192.168.1.100:4873/ghreleases
npm http request GET http://192.168.1.100:4873/github-from-package
npm http request GET http://192.168.1.100:4873/node-ninja
npm http request GET http://192.168.1.100:4873/noop-logger
npm http request GET http://192.168.1.100:4873/npmlog
npm http request GET http://192.168.1.100:4873/os-homedir
npm http request GET http://192.168.1.100:4873/pump
npm http request GET http://192.168.1.100:4873/rc
npm http request GET http://192.168.1.100:4873/node-gyp
npm http request GET http://192.168.1.100:4873/tar-stream
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/simple-get
npm http request GET http://192.168.1.100:4873/tar-fs
npm http 304 http://192.168.1.100:4873/expand-template
npm http 304 http://192.168.1.100:4873/github-from-package
npm http 304 http://192.168.1.100:4873/execspawn
npm http 304 http://192.168.1.100:4873/ghreleases
npm http 304 http://192.168.1.100:4873/node-ninja
npm http 304 http://192.168.1.100:4873/noop-logger
npm http 304 http://192.168.1.100:4873/npmlog
npm http 304 http://192.168.1.100:4873/os-homedir
npm http 304 http://192.168.1.100:4873/pump
npm http 200 http://192.168.1.100:4873/rc
npm http 304 http://192.168.1.100:4873/node-gyp
npm http 304 http://192.168.1.100:4873/tar-stream
npm http 304 http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/tar-fs
npm http 200 http://192.168.1.100:4873/simple-get
npm http request GET http://192.168.1.100:4873/util-extend
npm http 304 http://192.168.1.100:4873/util-extend
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/ghrepos
npm http request GET http://192.168.1.100:4873/ghutils
npm http request GET http://192.168.1.100:4873/simple-mime
npm http request GET http://192.168.1.100:4873/url-template
npm http 304 http://192.168.1.100:4873/after
npm http 304 http://192.168.1.100:4873/ghrepos
npm http 304 http://192.168.1.100:4873/simple-mime
npm http 304 http://192.168.1.100:4873/ghutils
npm http 304 http://192.168.1.100:4873/url-template
npm http request GET http://192.168.1.100:4873/jsonist
npm http 304 http://192.168.1.100:4873/jsonist
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/hyperquest
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/hyperquest
npm http request GET http://192.168.1.100:4873/duplexer2
npm http 304 http://192.168.1.100:4873/duplexer2
npm http request GET http://192.168.1.100:4873/fstream
npm http request GET http://192.168.1.100:4873/nopt
npm http request GET http://192.168.1.100:4873/osenv
npm http request GET http://192.168.1.100:4873/tar
npm http request GET http://192.168.1.100:4873/which
npm http 304 http://192.168.1.100:4873/fstream
npm http 304 http://192.168.1.100:4873/nopt
npm http 304 http://192.168.1.100:4873/tar
npm http 304 http://192.168.1.100:4873/which
npm http 200 http://192.168.1.100:4873/osenv
npm http request GET http://192.168.1.100:4873/abbrev
npm http 200 http://192.168.1.100:4873/abbrev
npm http request GET http://192.168.1.100:4873/ansi
npm http request GET http://192.168.1.100:4873/are-we-there-yet
npm http request GET http://192.168.1.100:4873/gauge
npm http 304 http://192.168.1.100:4873/ansi
npm http 304 http://192.168.1.100:4873/are-we-there-yet
npm http 304 http://192.168.1.100:4873/gauge
npm http request GET http://192.168.1.100:4873/delegates
npm http 200 http://192.168.1.100:4873/delegates
npm http request GET http://192.168.1.100:4873/lodash.pad
npm http request GET http://192.168.1.100:4873/has-unicode
npm http request GET http://192.168.1.100:4873/lodash.padend
npm http request GET http://192.168.1.100:4873/lodash.padstart
npm http 304 http://192.168.1.100:4873/lodash.pad
npm http 304 http://192.168.1.100:4873/has-unicode
npm http 304 http://192.168.1.100:4873/lodash.padend
npm http 304 http://192.168.1.100:4873/lodash.padstart
npm http request GET http://192.168.1.100:4873/os-tmpdir
npm http 304 http://192.168.1.100:4873/os-tmpdir
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 304 http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/asn1
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
npm http 304 http://192.168.1.100:4873/d
npm http 304 http://192.168.1.100:4873/es5-ext
npm http request GET http://192.168.1.100:4873/es6-iterator
npm http 304 http://192.168.1.100:4873/es6-iterator
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/deep-extend
npm http request GET http://192.168.1.100:4873/ini
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
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/asynckit
npm http 304 http://192.168.1.100:4873/asynckit
npm http request GET http://192.168.1.100:4873/punycode
npm http 304 http://192.168.1.100:4873/punycode
npm http request GET http://192.168.1.100:4873/fill-keys
npm http request GET http://192.168.1.100:4873/module-not-found-error
npm http 304 http://192.168.1.100:4873/fill-keys
npm http 304 http://192.168.1.100:4873/module-not-found-error
npm http request GET http://192.168.1.100:4873/is-object
npm http 304 http://192.168.1.100:4873/is-object
npm http request GET http://192.168.1.100:4873/array-uniq
npm http 304 http://192.168.1.100:4873/array-uniq
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/jsonschema
npm http 304 http://192.168.1.100:4873/jsonschema
npm http request GET http://192.168.1.100:4873/formatio
npm http request GET http://192.168.1.100:4873/util
npm http request GET http://192.168.1.100:4873/lolex
npm http request GET http://192.168.1.100:4873/samsam
npm http 304 http://192.168.1.100:4873/formatio
npm http 304 http://192.168.1.100:4873/samsam
npm http 304 http://192.168.1.100:4873/lolex
npm http 200 http://192.168.1.100:4873/util
npm http request GET http://192.168.1.100:4873/engine.io-client
npm http request GET http://192.168.1.100:4873/object-component
npm http request GET http://192.168.1.100:4873/socket.io-parser
npm http request GET http://192.168.1.100:4873/has-binary
npm http request GET http://192.168.1.100:4873/indexof
npm http request GET http://192.168.1.100:4873/parseuri
npm http request GET http://192.168.1.100:4873/to-array
npm http request GET http://192.168.1.100:4873/backo2
npm http request GET http://192.168.1.100:4873/component-bind
npm http request GET http://192.168.1.100:4873/component-emitter
npm http 304 http://192.168.1.100:4873/object-component
npm http 304 http://192.168.1.100:4873/engine.io-client
npm http 304 http://192.168.1.100:4873/socket.io-parser
npm http 304 http://192.168.1.100:4873/has-binary
npm http 304 http://192.168.1.100:4873/indexof
npm http 304 http://192.168.1.100:4873/parseuri
npm http 304 http://192.168.1.100:4873/to-array
npm http 304 http://192.168.1.100:4873/backo2
npm http 304 http://192.168.1.100:4873/component-bind
npm http 304 http://192.168.1.100:4873/component-emitter
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
npm http 304 http://192.168.1.100:4873/superagent
npm http request GET http://192.168.1.100:4873/formidable
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/cookiejar
npm http request GET http://192.168.1.100:4873/reduce-component
npm http request GET http://192.168.1.100:4873/methods
npm http 200 http://192.168.1.100:4873/formidable
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/reduce-component
npm http 304 http://192.168.1.100:4873/cookiejar
npm http 304 http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/mime-db
npm http 304 http://192.168.1.100:4873/mime-db
npm http request GET http://192.168.1.100:4873/defined
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/resumer
npm http request GET http://192.168.1.100:4873/object-inspect
npm http 304 http://192.168.1.100:4873/defined
npm http 304 http://192.168.1.100:4873/object-inspect
npm http 304 http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/resumer
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
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/object-assign
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
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/multiplex
npm http 304 http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-leveldb-core
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/urlsafe-base64
npm http 304 http://192.168.1.100:4873/uuid
npm http 304 http://192.168.1.100:4873/winston
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
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/finalhandler
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
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/varint
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
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/buffer-shims
npm http 304 http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/process-nextick-args
npm http 304 http://192.168.1.100:4873/util-deprecate
npm http request GET http://192.168.1.100:4873/argsarray
npm http request GET http://192.168.1.100:4873/buffer-from
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-utils
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
npm http 304 http://192.168.1.100:4873/pouchdb-collections
npm http 304 http://192.168.1.100:4873/pouchdb-binary-utils
npm http 304 http://192.168.1.100:4873/pouchdb-errors
npm http 304 http://192.168.1.100:4873/pouchdb-json
npm http 304 http://192.168.1.100:4873/pouchdb-md5
npm http 304 http://192.168.1.100:4873/pouchdb-utils
npm http 304 http://192.168.1.100:4873/pouchdb-merge
npm http 304 http://192.168.1.100:4873/sublevel-pouchdb
npm http 304 http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/is-array-buffer-x
npm http 304 http://192.168.1.100:4873/is-array-buffer-x
npm http request GET http://192.168.1.100:4873/is-object-like-x
npm http request GET http://192.168.1.100:4873/to-string-tag-x
npm http request GET http://192.168.1.100:4873/has-to-string-tag-x
npm http 304 http://192.168.1.100:4873/has-to-string-tag-x
npm http 304 http://192.168.1.100:4873/is-object-like-x
npm http 304 http://192.168.1.100:4873/to-string-tag-x
npm http request GET http://192.168.1.100:4873/has-symbol-support-x
npm http 304 http://192.168.1.100:4873/has-symbol-support-x
npm http request GET http://192.168.1.100:4873/is-function-x
npm http request GET http://192.168.1.100:4873/is-primitive
npm http 304 http://192.168.1.100:4873/is-primitive
npm http 304 http://192.168.1.100:4873/is-function-x
npm http request GET http://192.168.1.100:4873/lodash.isnull
npm http request GET http://192.168.1.100:4873/validate.io-undefined
npm http 304 http://192.168.1.100:4873/validate.io-undefined
npm http 304 http://192.168.1.100:4873/lodash.isnull
npm http request GET http://192.168.1.100:4873/deferred-leveldown
npm http request GET http://192.168.1.100:4873/level-codec
npm http request GET http://192.168.1.100:4873/level-errors
npm http request GET http://192.168.1.100:4873/level-iterator-stream
npm http request GET http://192.168.1.100:4873/prr
npm http request GET http://192.168.1.100:4873/semver
npm http 304 http://192.168.1.100:4873/deferred-leveldown
npm http 304 http://192.168.1.100:4873/level-errors
npm http 304 http://192.168.1.100:4873/level-codec
npm http 304 http://192.168.1.100:4873/prr
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
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/oauth-sign
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
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/ansi-styles
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http 304 http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/hoek
npm http 304 http://192.168.1.100:4873/boom
npm http 304 http://192.168.1.100:4873/cryptiles
npm http 304 http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 304 http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/punycode
npm http 304 http://192.168.1.100:4873/punycode
npm http request GET http://192.168.1.100:4873/jsonschema
npm http 304 http://192.168.1.100:4873/jsonschema
npm http request GET http://192.168.1.100:4873/colors
npm http request GET http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/pkginfo
npm http request GET http://192.168.1.100:4873/cycle
npm http request GET http://192.168.1.100:4873/stack-trace
npm http 304 http://192.168.1.100:4873/colors
npm http 304 http://192.168.1.100:4873/eyes
npm http 304 http://192.168.1.100:4873/pkginfo
npm http 304 http://192.168.1.100:4873/stack-trace
npm http 304 http://192.168.1.100:4873/cycle
npm WARN EPACKAGEJSON thali-cordova-plugin-jxcore@1.0.0 No repository field.
npm ERR! Darwin 16.4.0
npm ERR! argv "/usr/local/bin/jx" "/Users/thali/.jx/npm/bin/npm-cli.js" "install" "--loglevel" "http" "--color" "true" "/Users/thali/Github/testBuild/thali" "--save" "--no-optional" "--build-from-source"
npm ERR! node v0.10.40
npm ERR! npm  v3.3.12
npm ERR! code ELIFECYCLE

npm ERR! thali@2.1.0 postinstall: `"/usr/local/bin/jx" installCordovaPlugin.js`
npm ERR! Exit status 1
npm ERR! 
npm ERR! Failed at the thali@2.1.0 postinstall script '"/usr/local/bin/jx" installCordovaPlugin.js'.
npm ERR! Make sure you have the latest version of node.js and npm installed.
npm ERR! If you do, this is most likely a problem with the thali package,
npm ERR! not with npm itself.
npm ERR! Tell the author that this fails on your system:
npm ERR!     "/usr/local/bin/jx" installCordovaPlugin.js
npm ERR! You can get their info via:
npm ERR!     npm owner ls thali
npm ERR! There is likely additional logging output above.

npm ERR! Please include the following file with any support request:
npm ERR!     /Users/thali/Github/ThaliTest/www/jxcore/npm-debug.log

```

Error: Command failed: npm WARN thali-test-server@0.0.1 No repository field.
npm WARN thali-test-server@0.0.1 No license field.
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/javascript-state-machine
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-leveldb-core
npm http request GET http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/javascript-state-machine
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/bluebird
npm http 200 http://192.168.1.100:4873/ip
npm http 200 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/lie
npm http 304 http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/multiplex
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-leveldb-core
npm http 304 http://192.168.1.100:4873/winston
npm http 304 http://192.168.1.100:4873/urlsafe-base64
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
npm http request GET http://192.168.1.100:4873/raw-body
npm http request GET http://192.168.1.100:4873/type-is
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/bytes
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/type-is
npm http 304 http://192.168.1.100:4873/iconv-lite
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
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/send
npm http 304 http://192.168.1.100:4873/utils-merge
npm http 304 http://192.168.1.100:4873/serve-static
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
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/varint
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/stream-shift
npm http 304 http://192.168.1.100:4873/end-of-stream
npm http 304 http://192.168.1.100:4873/stream-shift
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
npm http 304 http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/string_decoder
npm http 200 http://192.168.1.100:4873/core-util-is
npm http 304 http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/buffer-from
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/pouchdb-errors
npm http request GET http://192.168.1.100:4873/pouchdb-merge
npm http request GET http://192.168.1.100:4873/pouchdb-md5
npm http request GET http://192.168.1.100:4873/argsarray
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-utils
npm http request GET http://192.168.1.100:4873/pouchdb-binary-utils
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/pouchdb-json
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/pouchdb-utils
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/buffer-from
npm http 304 http://192.168.1.100:4873/double-ended-queue
npm http 304 http://192.168.1.100:4873/pouchdb-errors
npm http 304 http://192.168.1.100:4873/pouchdb-merge
npm http 304 http://192.168.1.100:4873/pouchdb-md5
npm http 200 http://192.168.1.100:4873/argsarray
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-utils
npm http 304 http://192.168.1.100:4873/pouchdb-binary-utils
npm http 304 http://192.168.1.100:4873/pouchdb-collections
npm http 304 http://192.168.1.100:4873/pouchdb-json
npm http 304 http://192.168.1.100:4873/sublevel-pouchdb
npm http 304 http://192.168.1.100:4873/through2
npm http 304 http://192.168.1.100:4873/pouchdb-utils
npm http 200 http://192.168.1.100:4873/pouchdb-promise
npm http 200 http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/is-array-buffer-x
npm http 304 http://192.168.1.100:4873/is-array-buffer-x
npm http request GET http://192.168.1.100:4873/is-object-like-x
npm http request GET http://192.168.1.100:4873/to-string-tag-x
npm http request GET http://192.168.1.100:4873/has-to-string-tag-x
npm http 304 http://192.168.1.100:4873/is-object-like-x
npm http 304 http://192.168.1.100:4873/has-to-string-tag-x
npm http 304 http://192.168.1.100:4873/to-string-tag-x
npm http request GET http://192.168.1.100:4873/has-symbol-support-x
npm http 304 http://192.168.1.100:4873/has-symbol-support-x
npm http request GET http://192.168.1.100:4873/is-primitive
npm http request GET http://192.168.1.100:4873/is-function-x
npm http 304 http://192.168.1.100:4873/is-primitive
npm http 304 http://192.168.1.100:4873/is-function-x
npm http request GET http://192.168.1.100:4873/validate.io-undefined
npm http request GET http://192.168.1.100:4873/lodash.isnull
npm http 304 http://192.168.1.100:4873/validate.io-undefined
npm http 304 http://192.168.1.100:4873/lodash.isnull
npm http request GET http://192.168.1.100:4873/prr
npm http request GET http://192.168.1.100:4873/level-codec
npm http request GET http://192.168.1.100:4873/deferred-leveldown
npm http request GET http://192.168.1.100:4873/level-iterator-stream
npm http request GET http://192.168.1.100:4873/level-errors
npm http request GET http://192.168.1.100:4873/semver
npm http 304 http://192.168.1.100:4873/prr
npm http 304 http://192.168.1.100:4873/level-codec
npm http 304 http://192.168.1.100:4873/level-errors
npm http 304 http://192.168.1.100:4873/level-iterator-stream
npm http 304 http://192.168.1.100:4873/deferred-leveldown
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
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 200 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/http-signature
npm http 200 http://192.168.1.100:4873/tunnel-agent
npm http 200 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/hawk
npm http 200 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 200 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/lodash
npm http 200 http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/chalk
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/is-my-json-valid
npm http 200 http://192.168.1.100:4873/chalk
npm http 200 http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 200 http://192.168.1.100:4873/ansi-styles
npm http 304 http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http 304 http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-function
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http request GET http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/hoek
npm http 304 http://192.168.1.100:4873/boom
npm http 304 http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/cryptiles
npm http 304 http://192.168.1.100:4873/hoek
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
npm http 304 http://192.168.1.100:4873/cycle
npm http 304 http://192.168.1.100:4873/eyes
npm http 304 http://192.168.1.100:4873/pkginfo
npm http 304 http://192.168.1.100:4873/stack-trace
npm http request GET http://192.168.1.100:4873/jsdoc
npm http request GET http://192.168.1.100:4873/eslint
npm http 304 http://192.168.1.100:4873/jsdoc
npm http 200 http://192.168.1.100:4873/eslint
npm http request GET http://192.168.1.100:4873/escope
npm http request GET http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/babel-code-frame
npm http request GET http://192.168.1.100:4873/doctrine
npm http request GET http://192.168.1.100:4873/espree
npm http request GET http://192.168.1.100:4873/esutils
npm http request GET http://192.168.1.100:4873/estraverse
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/file-entry-cache
npm http request GET http://192.168.1.100:4873/globals
npm http request GET http://192.168.1.100:4873/imurmurhash
npm http request GET http://192.168.1.100:4873/ignore
npm http request GET http://192.168.1.100:4873/is-resolvable
npm http request GET http://192.168.1.100:4873/js-yaml
npm http request GET http://192.168.1.100:4873/inquirer
npm http request GET http://192.168.1.100:4873/json-stable-stringify
npm http request GET http://192.168.1.100:4873/levn
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/natural-compare
npm http request GET http://192.168.1.100:4873/optionator
npm http request GET http://192.168.1.100:4873/path-is-inside
npm http request GET http://192.168.1.100:4873/progress
npm http request GET http://192.168.1.100:4873/pluralize
npm http request GET http://192.168.1.100:4873/require-uncached
npm http request GET http://192.168.1.100:4873/strip-bom
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/shelljs
npm http request GET http://192.168.1.100:4873/text-table
npm http request GET http://192.168.1.100:4873/table
npm http request GET http://192.168.1.100:4873/user-home
npm http 304 http://192.168.1.100:4873/escope
npm http 304 http://192.168.1.100:4873/doctrine
npm http 304 http://192.168.1.100:4873/espree
npm http 304 http://192.168.1.100:4873/concat-stream
npm http 200 http://192.168.1.100:4873/babel-code-frame
npm http 304 http://192.168.1.100:4873/esutils
npm http 304 http://192.168.1.100:4873/estraverse
npm http 304 http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/file-entry-cache
npm http 304 http://192.168.1.100:4873/globals
npm http 304 http://192.168.1.100:4873/imurmurhash
npm http 304 http://192.168.1.100:4873/is-resolvable
npm http 304 http://192.168.1.100:4873/ignore
npm http 200 http://192.168.1.100:4873/js-yaml
npm http 200 http://192.168.1.100:4873/inquirer
npm http 304 http://192.168.1.100:4873/json-stable-stringify
npm http 304 http://192.168.1.100:4873/levn
npm http 304 http://192.168.1.100:4873/natural-compare
npm http fetch GET http://192.168.1.100:4873/js-yaml/-/js-yaml-3.8.2.tgz
npm http 200 http://192.168.1.100:4873/mkdirp
npm http 304 http://192.168.1.100:4873/optionator
npm http 304 http://192.168.1.100:4873/path-is-inside
npm http 200 http://192.168.1.100:4873/require-uncached
npm http 200 http://192.168.1.100:4873/pluralize
npm http 200 http://192.168.1.100:4873/progress
npm http 304 http://192.168.1.100:4873/strip-bom
npm http 200 http://192.168.1.100:4873/strip-json-comments
npm http fetch 200 http://192.168.1.100:4873/js-yaml/-/js-yaml-3.8.2.tgz
npm http 304 http://192.168.1.100:4873/text-table
npm http 304 http://192.168.1.100:4873/user-home
npm http 200 http://192.168.1.100:4873/shelljs
npm http 200 http://192.168.1.100:4873/table
npm http request GET http://192.168.1.100:4873/js-tokens
npm http 304 http://192.168.1.100:4873/js-tokens
npm http request GET http://192.168.1.100:4873/typedarray
npm http 304 http://192.168.1.100:4873/typedarray
npm http request GET http://192.168.1.100:4873/es6-weak-map
npm http request GET http://192.168.1.100:4873/es6-map
npm http request GET http://192.168.1.100:4873/esrecurse
npm http 304 http://192.168.1.100:4873/es6-weak-map
npm http 304 http://192.168.1.100:4873/es6-map
npm http 304 http://192.168.1.100:4873/esrecurse
npm http request GET http://192.168.1.100:4873/d
npm http request GET http://192.168.1.100:4873/es6-iterator
npm http request GET http://192.168.1.100:4873/es6-set
npm http request GET http://192.168.1.100:4873/es5-ext
npm http request GET http://192.168.1.100:4873/es6-symbol
npm http request GET http://192.168.1.100:4873/event-emitter
npm http 304 http://192.168.1.100:4873/d
npm http 304 http://192.168.1.100:4873/es6-iterator
npm http 304 http://192.168.1.100:4873/es6-set
npm http 304 http://192.168.1.100:4873/es6-symbol
npm http 304 http://192.168.1.100:4873/es5-ext
npm http 304 http://192.168.1.100:4873/event-emitter
npm http request GET http://192.168.1.100:4873/acorn
npm http request GET http://192.168.1.100:4873/acorn-jsx
npm http 304 http://192.168.1.100:4873/acorn-jsx
npm http 200 http://192.168.1.100:4873/acorn
npm http request GET http://192.168.1.100:4873/flat-cache
npm http 304 http://192.168.1.100:4873/flat-cache
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/circular-json
npm http request GET http://192.168.1.100:4873/del
npm http request GET http://192.168.1.100:4873/write
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http 304 http://192.168.1.100:4873/circular-json
npm http 304 http://192.168.1.100:4873/write
npm http 200 http://192.168.1.100:4873/del
npm http request GET http://192.168.1.100:4873/is-path-cwd
npm http request GET http://192.168.1.100:4873/globby
npm http request GET http://192.168.1.100:4873/is-path-in-cwd
npm http request GET http://192.168.1.100:4873/pify
npm http request GET http://192.168.1.100:4873/rimraf
npm http request GET http://192.168.1.100:4873/pinkie-promise
npm http 304 http://192.168.1.100:4873/is-path-cwd
npm http 304 http://192.168.1.100:4873/globby
npm http 304 http://192.168.1.100:4873/is-path-in-cwd
npm http 304 http://192.168.1.100:4873/rimraf
npm http 200 http://192.168.1.100:4873/pify
npm http 304 http://192.168.1.100:4873/pinkie-promise
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
npm http 304 http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/minimatch
npm http 304 http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 304 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/pinkie
npm http 304 http://192.168.1.100:4873/pinkie
npm http request GET http://192.168.1.100:4873/is-path-inside
npm http 304 http://192.168.1.100:4873/is-path-inside
npm http request GET http://192.168.1.100:4873/minimist
npm http 200 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/ansi-escapes
npm http request GET http://192.168.1.100:4873/cli-cursor
npm http request GET http://192.168.1.100:4873/cli-width
npm http request GET http://192.168.1.100:4873/figures
npm http request GET http://192.168.1.100:4873/readline2
npm http request GET http://192.168.1.100:4873/run-async
npm http request GET http://192.168.1.100:4873/string-width
npm http request GET http://192.168.1.100:4873/rx-lite
npm http request GET http://192.168.1.100:4873/through
npm http 304 http://192.168.1.100:4873/cli-cursor
npm http 304 http://192.168.1.100:4873/ansi-escapes
npm http 304 http://192.168.1.100:4873/cli-width
npm http 304 http://192.168.1.100:4873/readline2
npm http 304 http://192.168.1.100:4873/figures
npm http 304 http://192.168.1.100:4873/string-width
npm http 304 http://192.168.1.100:4873/run-async
npm http 304 http://192.168.1.100:4873/rx-lite
npm http 200 http://192.168.1.100:4873/through
npm http request GET http://192.168.1.100:4873/restore-cursor
npm http 304 http://192.168.1.100:4873/restore-cursor
npm http request GET http://192.168.1.100:4873/exit-hook
npm http request GET http://192.168.1.100:4873/onetime
npm http 304 http://192.168.1.100:4873/exit-hook
npm http 200 http://192.168.1.100:4873/onetime
npm http request GET http://192.168.1.100:4873/code-point-at
npm http request GET http://192.168.1.100:4873/is-fullwidth-code-point
npm http request GET http://192.168.1.100:4873/mute-stream
npm http 304 http://192.168.1.100:4873/code-point-at
npm http 304 http://192.168.1.100:4873/is-fullwidth-code-point
npm http 304 http://192.168.1.100:4873/mute-stream
npm http request GET http://192.168.1.100:4873/number-is-nan
npm http 200 http://192.168.1.100:4873/number-is-nan
npm http request GET http://192.168.1.100:4873/tryit
npm http 304 http://192.168.1.100:4873/tryit
npm http request GET http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/argparse
npm http 304 http://192.168.1.100:4873/argparse
npm http 200 http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/sprintf-js
npm http 304 http://192.168.1.100:4873/sprintf-js
npm http request GET http://192.168.1.100:4873/jsonify
npm http 304 http://192.168.1.100:4873/jsonify
npm http request GET http://192.168.1.100:4873/prelude-ls
npm http request GET http://192.168.1.100:4873/type-check
npm http 304 http://192.168.1.100:4873/prelude-ls
npm http 304 http://192.168.1.100:4873/type-check
npm http request GET http://192.168.1.100:4873/wordwrap
npm http request GET http://192.168.1.100:4873/deep-is
npm http request GET http://192.168.1.100:4873/fast-levenshtein
npm http 304 http://192.168.1.100:4873/deep-is
npm http 304 http://192.168.1.100:4873/fast-levenshtein
npm http 304 http://192.168.1.100:4873/wordwrap
npm http request GET http://192.168.1.100:4873/caller-path
npm http request GET http://192.168.1.100:4873/resolve-from
npm http 304 http://192.168.1.100:4873/caller-path
npm http 304 http://192.168.1.100:4873/resolve-from
npm http request GET http://192.168.1.100:4873/callsites
npm http 304 http://192.168.1.100:4873/callsites
npm http request GET http://192.168.1.100:4873/interpret
npm http request GET http://192.168.1.100:4873/rechoir
npm http 304 http://192.168.1.100:4873/interpret
npm http 304 http://192.168.1.100:4873/rechoir
npm http request GET http://192.168.1.100:4873/resolve
npm http 304 http://192.168.1.100:4873/resolve
npm http request GET http://192.168.1.100:4873/path-parse
npm http 304 http://192.168.1.100:4873/path-parse
npm http request GET http://192.168.1.100:4873/slice-ansi
npm http request GET http://192.168.1.100:4873/ajv
npm http request GET http://192.168.1.100:4873/ajv-keywords
npm http 304 http://192.168.1.100:4873/slice-ansi
npm http 200 http://192.168.1.100:4873/ajv-keywords
npm http 200 http://192.168.1.100:4873/ajv
npm http fetch GET http://192.168.1.100:4873/ajv/-/ajv-4.11.4.tgz
npm http fetch 200 http://192.168.1.100:4873/ajv/-/ajv-4.11.4.tgz
npm http request GET http://192.168.1.100:4873/co
npm http 200 http://192.168.1.100:4873/co
npm http request GET http://192.168.1.100:4873/os-homedir
npm http 304 http://192.168.1.100:4873/os-homedir
npm http request GET http://192.168.1.100:4873/requizzle
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/js2xmlparser
npm http request GET http://192.168.1.100:4873/catharsis
npm http request GET http://192.168.1.100:4873/marked
npm http request GET http://192.168.1.100:4873/underscore
npm http request GET http://192.168.1.100:4873/wrench
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 304 http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/requizzle
npm http 304 http://192.168.1.100:4873/catharsis
npm http 200 http://192.168.1.100:4873/js2xmlparser
npm http 200 http://192.168.1.100:4873/marked
npm http 304 http://192.168.1.100:4873/wrench
npm http 200 http://192.168.1.100:4873/underscore
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
npm http request GET http://192.168.1.100:4873/bn.js
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/express-pouchdb
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/leveldown-mobile
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/nock
npm http request GET http://192.168.1.100:4873/pouchdb-size
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/pouchdb
npm http request GET http://192.168.1.100:4873/proxyquire
npm http request GET http://192.168.1.100:4873/request-promise
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/sinon
npm http request GET http://192.168.1.100:4873/stacky
npm http request GET http://192.168.1.100:4873/supertest-as-promised
npm http request GET http://192.168.1.100:4873/supertest
npm http request GET http://192.168.1.100:4873/tape-catch
npm http request GET http://192.168.1.100:4873/tmp
npm http request GET http://192.168.1.100:4873/tape
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/uuid-validate
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/bn.js
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/child-process-promise
npm http 304 http://192.168.1.100:4873/minimist
npm http 304 http://192.168.1.100:4873/js-extend
npm http 304 http://192.168.1.100:4873/multiplex
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/leveldown-mobile
npm http 304 http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/randomstring
npm http 200 http://192.168.1.100:4873/express-pouchdb
npm http 304 http://192.168.1.100:4873/pouchdb-size
npm http 304 http://192.168.1.100:4873/pouchdb
npm http 304 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/proxyquire
npm http 304 http://192.168.1.100:4873/socket.io-client
npm http 304 http://192.168.1.100:4873/stacky
npm http 304 http://192.168.1.100:4873/supertest-as-promised
npm http 304 http://192.168.1.100:4873/tape-catch
npm http 304 http://192.168.1.100:4873/tmp
npm http 200 http://192.168.1.100:4873/request-promise
npm http 200 http://192.168.1.100:4873/supertest
npm http 304 http://192.168.1.100:4873/urlsafe-base64
npm http 304 http://192.168.1.100:4873/uuid
npm http 304 http://192.168.1.100:4873/uuid-validate
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
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/bytes
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
npm http 304 http://192.168.1.100:4873/utils-merge
npm http 304 http://192.168.1.100:4873/vary
npm http request GET http://192.168.1.100:4873/negotiator
npm http 304 http://192.168.1.100:4873/negotiator
npm http request GET http://192.168.1.100:4873/ipaddr.js
npm http request GET http://192.168.1.100:4873/forwarded
npm http 304 http://192.168.1.100:4873/ipaddr.js
npm http 304 http://192.168.1.100:4873/forwarded
npm http request GET http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/mime
npm http 304 http://192.168.1.100:4873/destroy
npm http 304 http://192.168.1.100:4873/mime
npm http request GET http://192.168.1.100:4873/basic-auth
npm http request GET http://192.168.1.100:4873/cookie-parser
npm http request GET http://192.168.1.100:4873/compression
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/header-case-normalizer
npm http request GET http://192.168.1.100:4873/multiparty
npm http request GET http://192.168.1.100:4873/pouchdb-all-dbs
npm http request GET http://192.168.1.100:4873/pouchdb-auth
npm http request GET http://192.168.1.100:4873/pouchdb-list
npm http request GET http://192.168.1.100:4873/pouchdb-find
npm http request GET http://192.168.1.100:4873/pouchdb-rewrite
npm http request GET http://192.168.1.100:4873/pouchdb-replicator
npm http request GET http://192.168.1.100:4873/pouchdb-security
npm http request GET http://192.168.1.100:4873/pouchdb-show
npm http request GET http://192.168.1.100:4873/pouchdb-validation
npm http request GET http://192.168.1.100:4873/pouchdb-update
npm http request GET http://192.168.1.100:4873/pouchdb-vhost
npm http request GET http://192.168.1.100:4873/pouchdb-wrappers
npm http 304 http://192.168.1.100:4873/basic-auth
npm http 304 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/cookie-parser
npm http 304 http://192.168.1.100:4873/header-case-normalizer
npm http 200 http://192.168.1.100:4873/compression
npm http 304 http://192.168.1.100:4873/pouchdb-all-dbs
npm http 304 http://192.168.1.100:4873/pouchdb-auth
npm http 304 http://192.168.1.100:4873/pouchdb-list
npm http 304 http://192.168.1.100:4873/pouchdb-find
npm http 200 http://192.168.1.100:4873/multiparty
npm http 304 http://192.168.1.100:4873/pouchdb-rewrite
npm http 304 http://192.168.1.100:4873/pouchdb-validation
npm http 304 http://192.168.1.100:4873/pouchdb-show
npm http 200 http://192.168.1.100:4873/pouchdb-replicator
npm http 200 http://192.168.1.100:4873/pouchdb-security
npm http 304 http://192.168.1.100:4873/pouchdb-update
npm http 304 http://192.168.1.100:4873/pouchdb-vhost
npm http 304 http://192.168.1.100:4873/pouchdb-wrappers
npm http request GET http://192.168.1.100:4873/setprototypeof
npm http 304 http://192.168.1.100:4873/setprototypeof
npm http request GET http://192.168.1.100:4873/compressible
npm http request GET http://192.168.1.100:4873/on-headers
npm http 304 http://192.168.1.100:4873/compressible
npm http 200 http://192.168.1.100:4873/on-headers
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/stream-counter
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/stream-counter
npm http request GET http://192.168.1.100:4873/argsarray
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/tiny-queue
npm http 304 http://192.168.1.100:4873/es3ify
npm http 304 http://192.168.1.100:4873/argsarray
npm http 304 http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/tiny-queue
npm http request GET http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/base62
npm http 304 http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/base64url
npm http request GET http://192.168.1.100:4873/crypto-lite
npm http request GET http://192.168.1.100:4873/couchdb-calculate-session-id
npm http request GET http://192.168.1.100:4873/pouchdb-plugin-error
npm http request GET http://192.168.1.100:4873/pouchdb-system-db
npm http request GET http://192.168.1.100:4873/promise-nodify
npm http request GET http://192.168.1.100:4873/secure-random
npm http request GET http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http request GET http://192.168.1.100:4873/pouchdb-req-http-query
npm http 304 http://192.168.1.100:4873/base64url
npm http 304 http://192.168.1.100:4873/crypto-lite
npm http 304 http://192.168.1.100:4873/couchdb-calculate-session-id
npm http 304 http://192.168.1.100:4873/pouchdb-plugin-error
npm http 304 http://192.168.1.100:4873/pouchdb-system-db
npm http 304 http://192.168.1.100:4873/promise-nodify
npm http 304 http://192.168.1.100:4873/secure-random
npm http 304 http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http 304 http://192.168.1.100:4873/pouchdb-req-http-query
npm http request GET http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/meow
npm http 304 http://192.168.1.100:4873/concat-stream
npm http 200 http://192.168.1.100:4873/meow
npm http request GET http://192.168.1.100:4873/typedarray
npm http 304 http://192.168.1.100:4873/typedarray
npm http request GET http://192.168.1.100:4873/indent-string
npm http request GET http://192.168.1.100:4873/camelcase-keys
npm http 304 http://192.168.1.100:4873/indent-string
npm http 304 http://192.168.1.100:4873/camelcase-keys
npm http request GET http://192.168.1.100:4873/map-obj
npm http request GET http://192.168.1.100:4873/camelcase
npm http 304 http://192.168.1.100:4873/map-obj
npm http 200 http://192.168.1.100:4873/camelcase
npm http request GET http://192.168.1.100:4873/repeating
npm http request GET http://192.168.1.100:4873/get-stdin
npm http 304 http://192.168.1.100:4873/repeating
npm http 304 http://192.168.1.100:4873/get-stdin
npm http request GET http://192.168.1.100:4873/is-finite
npm http 304 http://192.168.1.100:4873/is-finite
npm http request GET http://192.168.1.100:4873/number-is-nan
npm http 304 http://192.168.1.100:4873/number-is-nan
npm http request GET http://192.168.1.100:4873/aproba
npm http 304 http://192.168.1.100:4873/aproba
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/localstorage-down
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/es6-promise-pool
npm http request GET http://192.168.1.100:4873/level-write-stream
npm http request GET http://192.168.1.100:4873/fruitdown
npm http request GET http://192.168.1.100:4873/memdown
npm http request GET http://192.168.1.100:4873/pouchdb-collate
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/scope-eval
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/vuvuzela
npm http 304 http://192.168.1.100:4873/double-ended-queue
npm http 304 http://192.168.1.100:4873/levelup
npm http 304 http://192.168.1.100:4873/localstorage-down
npm http 304 http://192.168.1.100:4873/pouchdb-collections
npm http 200 http://192.168.1.100:4873/es6-promise-pool
npm http 304 http://192.168.1.100:4873/level-write-stream
npm http 304 http://192.168.1.100:4873/memdown
npm http 304 http://192.168.1.100:4873/spark-md5
npm http 304 http://192.168.1.100:4873/pouchdb-collate
npm http 304 http://192.168.1.100:4873/fruitdown
npm http 304 http://192.168.1.100:4873/scope-eval
npm http 304 http://192.168.1.100:4873/sublevel-pouchdb
npm http 304 http://192.168.1.100:4873/through2
npm http 304 http://192.168.1.100:4873/vuvuzela
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
npm http 304 http://192.168.1.100:4873/level-errors
npm http 304 http://192.168.1.100:4873/level-codec
npm http 304 http://192.168.1.100:4873/prr
npm http 304 http://192.168.1.100:4873/level-iterator-stream
npm http 304 http://192.168.1.100:4873/semver
npm http request GET http://192.168.1.100:4873/errno
npm http 304 http://192.168.1.100:4873/errno
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
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/is-typedarray
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/tough-cookie
npm WARN deprecated tough-cookie@2.2.2: ReDoS vulnerability parsing Set-Cookie https://nodesecurity.io/advisories/130
npm http 304 http://192.168.1.100:4873/tunnel-agent
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
npm http 304 http://192.168.1.100:4873/chalk
npm http 304 http://192.168.1.100:4873/is-my-json-valid
npm http 304 http://192.168.1.100:4873/pinkie-promise
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
npm http request GET http://192.168.1.100:4873/couchdb-objects
npm http request GET http://192.168.1.100:4873/couchdb-eval
npm http request GET http://192.168.1.100:4873/random-uuid-v4
npm http 304 http://192.168.1.100:4873/couchdb-objects
npm http 304 http://192.168.1.100:4873/couchdb-eval
npm http 304 http://192.168.1.100:4873/random-uuid-v4
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
npm http 304 http://192.168.1.100:4873/ast-types
npm http 304 http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/couchdb-render
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/pouchdb-promise
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
npm http request GET http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/fast-future
npm http 304 http://192.168.1.100:4873/bindings
npm http 304 http://192.168.1.100:4873/fast-future
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
npm http request GET http://192.168.1.100:4873/propagate
npm http request GET http://192.168.1.100:4873/deep-equal
npm http request GET http://192.168.1.100:4873/chai
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/propagate
npm http 200 http://192.168.1.100:4873/deep-equal
npm http 200 http://192.168.1.100:4873/chai
npm http request GET http://192.168.1.100:4873/assertion-error
npm http request GET http://192.168.1.100:4873/deep-eql
npm http request GET http://192.168.1.100:4873/type-detect
npm http 304 http://192.168.1.100:4873/assertion-error
npm http 304 http://192.168.1.100:4873/deep-eql
npm http 304 http://192.168.1.100:4873/type-detect
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
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/leveldown
npm http 304 http://192.168.1.100:4873/buffer-from
npm http 304 http://192.168.1.100:4873/clone-buffer
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/double-ended-queue
npm http 304 http://192.168.1.100:4873/levelup
npm http 304 http://192.168.1.100:4873/spark-md5
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/leveldown
npm http request GET http://192.168.1.100:4873/is-array-buffer-x
npm http 304 http://192.168.1.100:4873/is-array-buffer-x
npm http request GET http://192.168.1.100:4873/is-object-like-x
npm http request GET http://192.168.1.100:4873/to-string-tag-x
npm http request GET http://192.168.1.100:4873/has-to-string-tag-x
npm http 304 http://192.168.1.100:4873/is-object-like-x
npm http 304 http://192.168.1.100:4873/to-string-tag-x
npm http 304 http://192.168.1.100:4873/has-to-string-tag-x
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
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/nan
npm http request GET http://192.168.1.100:4873/prebuild
npm http 304 http://192.168.1.100:4873/abstract-leveldown
npm http 304 http://192.168.1.100:4873/nan
npm http 200 http://192.168.1.100:4873/prebuild
npm http request GET http://192.168.1.100:4873/execspawn
npm http request GET http://192.168.1.100:4873/expand-template
npm http request GET http://192.168.1.100:4873/ghreleases
npm http request GET http://192.168.1.100:4873/github-from-package
npm http request GET http://192.168.1.100:4873/node-ninja
npm http request GET http://192.168.1.100:4873/noop-logger
npm http request GET http://192.168.1.100:4873/npmlog
npm http request GET http://192.168.1.100:4873/os-homedir
npm http request GET http://192.168.1.100:4873/pump
npm http request GET http://192.168.1.100:4873/rc
npm http request GET http://192.168.1.100:4873/node-gyp
npm http request GET http://192.168.1.100:4873/tar-stream
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/simple-get
npm http request GET http://192.168.1.100:4873/tar-fs
npm http 304 http://192.168.1.100:4873/expand-template
npm http 304 http://192.168.1.100:4873/github-from-package
npm http 304 http://192.168.1.100:4873/execspawn
npm http 304 http://192.168.1.100:4873/ghreleases
npm http 304 http://192.168.1.100:4873/node-ninja
npm http 304 http://192.168.1.100:4873/noop-logger
npm http 304 http://192.168.1.100:4873/npmlog
npm http 304 http://192.168.1.100:4873/os-homedir
npm http 304 http://192.168.1.100:4873/pump
npm http 200 http://192.168.1.100:4873/rc
npm http 304 http://192.168.1.100:4873/node-gyp
npm http 304 http://192.168.1.100:4873/tar-stream
npm http 304 http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/tar-fs
npm http 200 http://192.168.1.100:4873/simple-get
npm http request GET http://192.168.1.100:4873/util-extend
npm http 304 http://192.168.1.100:4873/util-extend
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/ghrepos
npm http request GET http://192.168.1.100:4873/ghutils
npm http request GET http://192.168.1.100:4873/simple-mime
npm http request GET http://192.168.1.100:4873/url-template
npm http 304 http://192.168.1.100:4873/after
npm http 304 http://192.168.1.100:4873/ghrepos
npm http 304 http://192.168.1.100:4873/simple-mime
npm http 304 http://192.168.1.100:4873/ghutils
npm http 304 http://192.168.1.100:4873/url-template
npm http request GET http://192.168.1.100:4873/jsonist
npm http 304 http://192.168.1.100:4873/jsonist
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/hyperquest
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/hyperquest
npm http request GET http://192.168.1.100:4873/duplexer2
npm http 304 http://192.168.1.100:4873/duplexer2
npm http request GET http://192.168.1.100:4873/fstream
npm http request GET http://192.168.1.100:4873/nopt
npm http request GET http://192.168.1.100:4873/osenv
npm http request GET http://192.168.1.100:4873/tar
npm http request GET http://192.168.1.100:4873/which
npm http 304 http://192.168.1.100:4873/fstream
npm http 304 http://192.168.1.100:4873/nopt
npm http 304 http://192.168.1.100:4873/tar
npm http 304 http://192.168.1.100:4873/which
npm http 200 http://192.168.1.100:4873/osenv
npm http request GET http://192.168.1.100:4873/abbrev
npm http 200 http://192.168.1.100:4873/abbrev
npm http request GET http://192.168.1.100:4873/ansi
npm http request GET http://192.168.1.100:4873/are-we-there-yet
npm http request GET http://192.168.1.100:4873/gauge
npm http 304 http://192.168.1.100:4873/ansi
npm http 304 http://192.168.1.100:4873/are-we-there-yet
npm http 304 http://192.168.1.100:4873/gauge
npm http request GET http://192.168.1.100:4873/delegates
npm http 200 http://192.168.1.100:4873/delegates
npm http request GET http://192.168.1.100:4873/lodash.pad
npm http request GET http://192.168.1.100:4873/has-unicode
npm http request GET http://192.168.1.100:4873/lodash.padend
npm http request GET http://192.168.1.100:4873/lodash.padstart
npm http 304 http://192.168.1.100:4873/lodash.pad
npm http 304 http://192.168.1.100:4873/has-unicode
npm http 304 http://192.168.1.100:4873/lodash.padend
npm http 304 http://192.168.1.100:4873/lodash.padstart
npm http request GET http://192.168.1.100:4873/os-tmpdir
npm http 304 http://192.168.1.100:4873/os-tmpdir
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 304 http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/asn1
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
npm http 304 http://192.168.1.100:4873/d
npm http 304 http://192.168.1.100:4873/es5-ext
npm http request GET http://192.168.1.100:4873/es6-iterator
npm http 304 http://192.168.1.100:4873/es6-iterator
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/deep-extend
npm http request GET http://192.168.1.100:4873/ini
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
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/asynckit
npm http 304 http://192.168.1.100:4873/asynckit
npm http request GET http://192.168.1.100:4873/punycode
npm http 304 http://192.168.1.100:4873/punycode
npm http request GET http://192.168.1.100:4873/fill-keys
npm http request GET http://192.168.1.100:4873/module-not-found-error
npm http 304 http://192.168.1.100:4873/fill-keys
npm http 304 http://192.168.1.100:4873/module-not-found-error
npm http request GET http://192.168.1.100:4873/is-object
npm http 304 http://192.168.1.100:4873/is-object
npm http request GET http://192.168.1.100:4873/array-uniq
npm http 304 http://192.168.1.100:4873/array-uniq
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/jsonschema
npm http 304 http://192.168.1.100:4873/jsonschema
npm http request GET http://192.168.1.100:4873/formatio
npm http request GET http://192.168.1.100:4873/util
npm http request GET http://192.168.1.100:4873/lolex
npm http request GET http://192.168.1.100:4873/samsam
npm http 304 http://192.168.1.100:4873/formatio
npm http 304 http://192.168.1.100:4873/samsam
npm http 304 http://192.168.1.100:4873/lolex
npm http 200 http://192.168.1.100:4873/util
npm http request GET http://192.168.1.100:4873/engine.io-client
npm http request GET http://192.168.1.100:4873/object-component
npm http request GET http://192.168.1.100:4873/socket.io-parser
npm http request GET http://192.168.1.100:4873/has-binary
npm http request GET http://192.168.1.100:4873/indexof
npm http request GET http://192.168.1.100:4873/parseuri
npm http request GET http://192.168.1.100:4873/to-array
npm http request GET http://192.168.1.100:4873/backo2
npm http request GET http://192.168.1.100:4873/component-bind
npm http request GET http://192.168.1.100:4873/component-emitter
npm http 304 http://192.168.1.100:4873/object-component
npm http 304 http://192.168.1.100:4873/engine.io-client
npm http 304 http://192.168.1.100:4873/socket.io-parser
npm http 304 http://192.168.1.100:4873/has-binary
npm http 304 http://192.168.1.100:4873/indexof
npm http 304 http://192.168.1.100:4873/parseuri
npm http 304 http://192.168.1.100:4873/to-array
npm http 304 http://192.168.1.100:4873/backo2
npm http 304 http://192.168.1.100:4873/component-bind
npm http 304 http://192.168.1.100:4873/component-emitter
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
npm http 304 http://192.168.1.100:4873/superagent
npm http request GET http://192.168.1.100:4873/formidable
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/cookiejar
npm http request GET http://192.168.1.100:4873/reduce-component
npm http request GET http://192.168.1.100:4873/methods
npm http 200 http://192.168.1.100:4873/formidable
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/reduce-component
npm http 304 http://192.168.1.100:4873/cookiejar
npm http 304 http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/mime-db
npm http 304 http://192.168.1.100:4873/mime-db
npm http request GET http://192.168.1.100:4873/defined
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/resumer
npm http request GET http://192.168.1.100:4873/object-inspect
npm http 304 http://192.168.1.100:4873/defined
npm http 304 http://192.168.1.100:4873/object-inspect
npm http 304 http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/resumer
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
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/object-assign
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
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/multiplex
npm http 304 http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-leveldb-core
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/urlsafe-base64
npm http 304 http://192.168.1.100:4873/uuid
npm http 304 http://192.168.1.100:4873/winston
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
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/finalhandler
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
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/varint
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
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/buffer-shims
npm http 304 http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/process-nextick-args
npm http 304 http://192.168.1.100:4873/util-deprecate
npm http request GET http://192.168.1.100:4873/argsarray
npm http request GET http://192.168.1.100:4873/buffer-from
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-utils
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
npm http 304 http://192.168.1.100:4873/pouchdb-collections
npm http 304 http://192.168.1.100:4873/pouchdb-binary-utils
npm http 304 http://192.168.1.100:4873/pouchdb-errors
npm http 304 http://192.168.1.100:4873/pouchdb-json
npm http 304 http://192.168.1.100:4873/pouchdb-md5
npm http 304 http://192.168.1.100:4873/pouchdb-utils
npm http 304 http://192.168.1.100:4873/pouchdb-merge
npm http 304 http://192.168.1.100:4873/sublevel-pouchdb
npm http 304 http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/is-array-buffer-x
npm http 304 http://192.168.1.100:4873/is-array-buffer-x
npm http request GET http://192.168.1.100:4873/is-object-like-x
npm http request GET http://192.168.1.100:4873/to-string-tag-x
npm http request GET http://192.168.1.100:4873/has-to-string-tag-x
npm http 304 http://192.168.1.100:4873/has-to-string-tag-x
npm http 304 http://192.168.1.100:4873/is-object-like-x
npm http 304 http://192.168.1.100:4873/to-string-tag-x
npm http request GET http://192.168.1.100:4873/has-symbol-support-x
npm http 304 http://192.168.1.100:4873/has-symbol-support-x
npm http request GET http://192.168.1.100:4873/is-function-x
npm http request GET http://192.168.1.100:4873/is-primitive
npm http 304 http://192.168.1.100:4873/is-primitive
npm http 304 http://192.168.1.100:4873/is-function-x
npm http request GET http://192.168.1.100:4873/lodash.isnull
npm http request GET http://192.168.1.100:4873/validate.io-undefined
npm http 304 http://192.168.1.100:4873/validate.io-undefined
npm http 304 http://192.168.1.100:4873/lodash.isnull
npm http request GET http://192.168.1.100:4873/deferred-leveldown
npm http request GET http://192.168.1.100:4873/level-codec
npm http request GET http://192.168.1.100:4873/level-errors
npm http request GET http://192.168.1.100:4873/level-iterator-stream
npm http request GET http://192.168.1.100:4873/prr
npm http request GET http://192.168.1.100:4873/semver
npm http 304 http://192.168.1.100:4873/deferred-leveldown
npm http 304 http://192.168.1.100:4873/level-errors
npm http 304 http://192.168.1.100:4873/level-codec
npm http 304 http://192.168.1.100:4873/prr
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
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/oauth-sign
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
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/ansi-styles
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http 304 http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/hoek
npm http 304 http://192.168.1.100:4873/boom
npm http 304 http://192.168.1.100:4873/cryptiles
npm http 304 http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 304 http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/punycode
npm http 304 http://192.168.1.100:4873/punycode
npm http request GET http://192.168.1.100:4873/jsonschema
npm http 304 http://192.168.1.100:4873/jsonschema
npm http request GET http://192.168.1.100:4873/colors
npm http request GET http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/pkginfo
npm http request GET http://192.168.1.100:4873/cycle
npm http request GET http://192.168.1.100:4873/stack-trace
npm http 304 http://192.168.1.100:4873/colors
npm http 304 http://192.168.1.100:4873/eyes
npm http 304 http://192.168.1.100:4873/pkginfo
npm http 304 http://192.168.1.100:4873/stack-trace
npm http 304 http://192.168.1.100:4873/cycle
npm WARN EPACKAGEJSON thali-cordova-plugin-jxcore@1.0.0 No repository field.
npm ERR! Darwin 16.4.0
npm ERR! argv "/usr/local/bin/jx" "/Users/thali/.jx/npm/bin/npm-cli.js" "install" "--loglevel" "http" "--color" "true" "/Users/thali/Github/testBuild/thali" "--save" "--no-optional" "--build-from-source"
npm ERR! node v0.10.40
npm ERR! npm  v3.3.12
npm ERR! code ELIFECYCLE

npm ERR! thali@2.1.0 postinstall: `"/usr/local/bin/jx" installCordovaPlugin.js`
npm ERR! Exit status 1
npm ERR! 
npm ERR! Failed at the thali@2.1.0 postinstall script '"/usr/local/bin/jx" installCordovaPlugin.js'.
npm ERR! Make sure you have the latest version of node.js and npm installed.
npm ERR! If you do, this is most likely a problem with the thali package,
npm ERR! not with npm itself.
npm ERR! Tell the author that this fails on your system:
npm ERR!     "/usr/local/bin/jx" installCordovaPlugin.js
npm ERR! You can get their info via:
npm ERR!     npm owner ls thali
npm ERR! There is likely additional logging output above.

npm ERR! Please include the following file with any support request:
npm ERR!     /Users/thali/Github/ThaliTest/www/jxcore/npm-debug.log
