#### Test (Fail) 119487456 Build Logs


```


```

```
Already up-to-date.

From https://github.com/thaliproject/Thali_CordovaPlugin
   aa8aed2..be3f9ce  master_dersim_preliminary_verification_fix -> origin/master_dersim_preliminary_verification_fix

```

```
Your branch is up-to-date with 'origin/master'.
Your branch is up-to-date with 'origin/master'.
Already up-to-date.

Already on 'master'
Already on 'master'
Note: checking out 'be3f9ce'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at be3f9ce... Revert "Temporarily disable running desktop tests."

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
│       ├─┬ minimatch@3.0.4 
│       │ └─┬ brace-expansion@1.1.7 
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
│       ├─┬ minimatch@3.0.4 
│       │ └─┬ brace-expansion@1.1.7 
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
│ ├── extend@3.0.1 
│ ├── forever-agent@0.6.1 
│ ├─┬ form-data@1.0.1 
│ │ └─┬ async@2.4.0 
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
│ │ └─┬ sshpk@1.13.0 
│ │   ├── asn1@0.2.3 
│ │   ├── assert-plus@1.0.0 
│ │   ├─┬ dashdash@1.14.1 
│ │   │ └── assert-plus@1.0.0 
│ │   └─┬ getpass@0.1.7 
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
2017-05-08 17:09:45 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
2017-05-08 17:09:45 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
2017-05-08 17:09:45 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
2017-05-08 17:09:45 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBGenerator.js'
2017-05-08 17:09:45 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPromiseQueue.js'
2017-05-08 17:09:45 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testTests.js'
2017-05-08 17:09:45 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testUsn.js'
2017-05-08 17:09:45 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testNativeMethod.js'
2017-05-08 17:09:45 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNative.js'
2017-05-08 17:09:45 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
2017-05-08 17:09:45 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
2017-05-08 17:09:45 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
2017-05-08 17:09:45 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreateNativeListener.js'
2017-05-08 17:09:46 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js'
2017-05-08 17:09:46 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliTcpServersManager.js'
2017-05-08 17:09:46 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
2017-05-08 17:09:46 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
2017-05-08 17:09:46 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js'
2017-05-08 17:09:46 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerAction.js'
2017-05-08 17:09:46 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerDictionary.js'
2017-05-08 17:09:46 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
2017-05-08 17:09:46 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
2017-05-08 17:09:46 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
2017-05-08 17:09:46 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotification.js'
2017-05-08 17:09:46 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationAction.js'
2017-05-08 17:09:46 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
2017-05-08 17:09:46 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationClient.js'
2017-05-08 17:09:46 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationLocal.js'
2017-05-08 17:09:46 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationServer.js'
2017-05-08 17:09:46 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
2017-05-08 17:09:46 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
2017-05-08 17:09:46 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
2017-05-08 17:09:46 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
2017-05-08 17:09:46 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
2017-05-08 17:09:46 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
2017-05-08 17:09:47 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js'
2017-05-08 17:09:47 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
2017-05-08 17:09:47 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManager.js'
2017-05-08 17:09:47 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
2017-05-08 17:09:47 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testHttp.js'
2017-05-08 17:09:47 - INFO testLoader: 'loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testSSDPServer.js'
2017-05-08 17:09:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-05-08 17:09:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-05-08 17:09:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
2017-05-08 17:09:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2017-05-08 17:09:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-05-08 17:09:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-05-08 17:09:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-05-08 17:09:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
TAP version 13
# setup
# closeAll can close even when connections open
2017-05-08 17:09:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 1 not possible to connect to the server anymore
# teardown
# setup
# closeAll with promise
2017-05-08 17:09:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
# teardown
# setup
# closeAll properly throws when closing a non open server with eatNotRunning set to false
2017-05-08 17:09:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
# teardown
# setup
# closeAll works even with a server that is not listening yet witheatNotRunning set to true
2017-05-08 17:09:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
# setup
# Call of onCheckpointReached handler on a single db change
2017-05-08 17:09:47 - DEBUG SimpleThaliTape: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
# teardown
# setup
# Call of multiple onCheckpointReached handlers on a single db change
2017-05-08 17:09:47 - DEBUG SimpleThaliTape: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
# teardown
# setup
# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
2017-05-08 17:09:47 - DEBUG SimpleThaliTape: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
# teardown
# setup
# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
2017-05-08 17:09:47 - DEBUG SimpleThaliTape: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
# teardown
# setup
# test defaultDirectory
ok 4 should be equal
ok 5 should be equal
ok 6 should be equal
# teardown
# setup
# test defaultAdapter
ok 7 should be equal
ok 8 should be equal
ok 9 should be equal
ok 10 should be equal
ok 11 should be equal
ok 12 should be equal
ok 13 should be equal
ok 14 should be equal
# teardown
# setup
# enqueue and run in order
ok 15 firstPromise setTimeout
ok 16 firstPromise result
ok 17 firstPromise testValue
ok 18 secondPromise setTimeout
ok 19 secondPromise result
ok 20 secondPromise testValue
ok 21 thirdPromise in promise
ok 22 thirdPromise result
ok 23 thirdPromise testValue
# teardown
# setup
# enqueueAtTop and run backwards
ok 24 thirdPromise - first to run
ok 25 thirdPromise - in resolve
ok 26 secondPromise - second to run
ok 27 secondPromise - in catch
ok 28 firstPromise - third to run
ok 29 firstPromise - in then
ok 30 testing promises
# teardown
# setup
# mix enqueue and enqueueAtTop
ok 31 fourth
ok 32 fourth
ok 33 second
ok 34 secondPromise - in then
ok 35 first
ok 36 firstPromise - in catch
ok 37 third
ok 38 thirdPromise - in then
ok 39 testingPromises
# teardown
# setup
# queues handled independently
ok 40 all short operations completed before the long resolves
# teardown
# setup
# enqueued function are always executed asynchronously
ok 41 executor is not called here
ok 42 executors is called
# teardown
# setup
# exceptions in the executor are properly handled
ok 43 got expected error
# teardown
# setup
# basic
ok 44 sane
# teardown
# setup
# another
ok 45 sane
# teardown
# setup
# test sinon sansbox spy
2017-05-08 17:09:48 - DEBUG testTests: 'test spy method for global sinon sansbox'
ok 46 test sandbox spy works correctly
# teardown
# setup
# test sinon sansbox stub
ok 47 test sandbox stub works correctly
# teardown
# setup
# test sinon sansbox stub override
ok 48 test sandbox stub works correctly
# teardown
# setup
# test sinon sansbox mock
# teardown
# setup
# test sinon sansbox restore after test end
ok 49 test restore
# teardown
# setup
# Correctly parses/stringifies USN
ok 50 correctly parses USN string
ok 51 throws if usn has invalid prefix
ok 52 throws if usn has invalid identifier format
ok 53 throws if usn has invalid generation
ok 54 correctly stringifies peer
# teardown
# setup
# onPeerLost calls jxcore
2017-05-08 17:09:48 - DEBUG SimpleThaliTape: 'test was skipped, name: 'onPeerLost calls jxcore''
# teardown
# setup
# onPeerDiscovered calls jxcore
2017-05-08 17:09:48 - DEBUG SimpleThaliTape: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
2017-05-08 17:09:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-05-08 17:09:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-05-08 17:09:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
2017-05-08 17:09:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2017-05-08 17:09:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-05-08 17:09:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-05-08 17:09:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-05-08 17:09:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
# setup
# cannot call connect when start listening for advertisements is not active
2017-05-08 17:09:48 - DEBUG SimpleThaliTape: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
2017-05-08 17:09:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-05-08 17:09:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-05-08 17:09:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
2017-05-08 17:09:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2017-05-08 17:09:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-05-08 17:09:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-05-08 17:09:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-05-08 17:09:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 55 Should be able to call stopListeningForAdvertisements in teardown
ok 56 Should be able to call stopAdvertisingAndListening in teardown
# setup
# calling createNativeListener directly rejects
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Creating Native Server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'listening 49935'
ok 57 Should throw
# teardown
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - close'
# setup
# emits incomingConnectionState
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Creating Native Server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'listening 49937'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 58 initial connection state should be CONNECTED
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 59 final connection state should be DISCONNECTED
# teardown
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - close'
# setup
# emits routerPortConnectionFailed
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Creating Native Server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'listening 49940'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
ok 60 tried to connect to right port
ok 61 failed due to refused connection
ok 62 routerPortConnectionFailed is emitted
# teardown
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# setup
# native server connections all up
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Creating Native Server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'listening 49944'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
ok 63 Send/recvd #1 should be equal length
ok 64 Send/recvd #1 should be same
ok 65 Send/recvd #2 should be equal length
ok 66 Send/recvd #2 should be same
ok 67 Should be exactly 2 client sockets
# teardown
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# setup
# native server - closing incoming stream cleans outgoing socket
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Creating Native Server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'listening 49949'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
ok 68 socket shouldn't close until after stream
ok 69 incoming remains open
# teardown
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# setup
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# native server - closing incoming connection cleans outgoing socket
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Creating Native Server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'listening 49953'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 70 we should not have gotten an error
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 71 socket shouldn't close until after incoming
ok 72 incoming is cleaned up
# teardown
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - close'
# setup
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# native server - closing outgoing socket cleans associated mux stream
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Creating Native Server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'listening 49957'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
ok 73 stream was closed
ok 74 incoming should survive
ok 75 mux should have no streams
# teardown
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# setup
# native server - closing the whole server cleans everything up
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Creating Native Server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'listening 49961'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 76 we should not have gotten an error
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 77 Buffers are identical
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 78 native server is nulled out
ok 79 native server should be closed
ok 80 incoming has been removed
ok 81 Incoming should be done
ok 82 The mux object should be closed
ok 83 The mux stream should be closed
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# teardown
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# setup
# native server - we can get a ton of connections and data through and still clean up the server completely
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Creating Native Server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'listening 49965'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
ok 84 native server is nulled out
ok 85 native server should be closed
ok 86 incoming has been removed
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# teardown
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# native server - simulate mux failure, make sure everything is cleaned up
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Creating Native Server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'listening 50017'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 87 we should not have gotten an error
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 88 Buffers are identical
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 89 server should be fine
ok 90 server should be open
ok 91 incoming has been removed
ok 92 The mux object should be closed
ok 93 The mux stream should be closed
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# teardown
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - close'
# setup
# native server - timing out the incoming connection cleans everything up
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Creating Native Server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'listening 50021'
ok 94 we should not have gotten an error
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 95 Buffers are identical
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 96 server should be fine
ok 97 server should be open
ok 98 incoming has been removed
ok 99 The mux object should be closed
ok 100 The mux stream should be closed
# teardown
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - close'
# setup
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# calling createPeerListener without calling start produces error
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Creating Native Server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'listening 50026'
# teardown
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - close'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# calling createPeerListener after calling stop produces error
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Creating Native Server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'listening 50029'
# teardown
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - close'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# can call createPeerListener
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Creating Native Server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'listening 50032'
2017-05-08 17:09:48 - DEBUG createPeerListener: 'creating new server for peerId'
2017-05-08 17:09:48 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peerId listening on 50033'
ok 101 port must be in range
# teardown
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - close'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# calling createPeerListener twice with same peerIdentifier should return the same port
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Creating Native Server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'listening 50036'
2017-05-08 17:09:48 - DEBUG createPeerListener: 'creating new server for peer1'
2017-05-08 17:09:48 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50037'
ok 102 port values should be the same
# teardown
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - close'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - closing connection to native listener closes everything and triggers new listener
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Creating Native Server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'listening 50040'
2017-05-08 17:09:48 - DEBUG createPeerListener: 'creating new server for peer2'
2017-05-08 17:09:48 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 50041'
2017-05-08 17:09:48 - DEBUG createPeerListener: 'Issuing callNative for peer2'
2017-05-08 17:09:48 - DEBUG createPeerListener: 'callNative for peer2 connected'
2017-05-08 17:09:48 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer2'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 103 Data should be of same length and content
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG createPeerListener: 'We are emitting failedConnection with error "Error: Outgoing closed, recreating connection" and peerIdentifier "peer2"'
2017-05-08 17:09:48 - DEBUG createPeerListener: 'Will try to recreate server for peer2'
2017-05-08 17:09:48 - DEBUG createPeerListener: 'creating new server for peer2'
2017-05-08 17:09:48 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 50046'
2017-05-08 17:09:48 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer2 and portNumber 50046'
ok 104 same peer ID
ok 105 different ports
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
# teardown
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - close'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# createPeerListener - closing mux closes listener and triggers a new listener
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Creating Native Server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'listening 50049'
2017-05-08 17:09:48 - DEBUG createPeerListener: 'creating new server for peer2'
2017-05-08 17:09:48 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 50050'
2017-05-08 17:09:48 - DEBUG createPeerListener: 'Issuing callNative for peer2'
2017-05-08 17:09:48 - DEBUG createPeerListener: 'callNative for peer2 connected'
2017-05-08 17:09:48 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer2'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 106 Data should be of same length and content
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG createPeerListener: 'We are emitting failedConnection with error "Error: Outgoing closed, recreating connection" and peerIdentifier "peer2"'
2017-05-08 17:09:48 - DEBUG createPeerListener: 'Will try to recreate server for peer2'
2017-05-08 17:09:48 - DEBUG createPeerListener: 'creating new server for peer2'
2017-05-08 17:09:48 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 50055'
2017-05-08 17:09:48 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer2 and portNumber 50055'
ok 107 same peer ID
ok 108 different ports
# teardown
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - close'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# peerListener - no native server
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Creating Native Server'
ok 109 Can call startUpdateAdvertisingAndListening without error
ok 110 Can call startListeningForAdvertisements without error
2017-05-08 17:09:48 - DEBUG createPeerListener: 'creating new server for peer1'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'listening 50058'
2017-05-08 17:09:48 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50059'
ok 111 peerPort should not be nativePort
2017-05-08 17:09:48 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2017-05-08 17:09:48 - DEBUG createPeerListener: 'callNative for peer1 connected'
2017-05-08 17:09:48 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG createPeerListener: 'We are emitting failedConnection with error "Error: Cannot Connect To Peer" and peerIdentifier "peer1"'
ok 112 Should not get event until connection is made
ok 113 reason should be as expected
2017-05-08 17:09:48 - DEBUG createPeerListener: 'Will try to recreate server for peer1'
2017-05-08 17:09:48 - DEBUG createPeerListener: 'creating new server for peer1'
2017-05-08 17:09:48 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50062'
2017-05-08 17:09:48 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer1 and portNumber 50062'
# teardown
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - close'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# peerListener - with native server
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Creating Native Server'
ok 114 Can call startUpdateAdvertisingAndListening without error
ok 115 Can call startListeningForAdvertisements without error
2017-05-08 17:09:48 - DEBUG createPeerListener: 'creating new server for peer1'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'listening 50065'
2017-05-08 17:09:48 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50066'
ok 116 peerPort != nativePort
2017-05-08 17:09:48 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2017-05-08 17:09:48 - DEBUG createPeerListener: 'callNative for peer1 connected'
2017-05-08 17:09:48 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
ok 117 Should not get unexpected connection
# teardown
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - close'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# peerListener - with native server and data transfer
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Creating Native Server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'listening 50071'
2017-05-08 17:09:48 - DEBUG createPeerListener: 'creating new server for peer1'
2017-05-08 17:09:48 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50072'
2017-05-08 17:09:48 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2017-05-08 17:09:48 - DEBUG createPeerListener: 'callNative for peer1 connected'
2017-05-08 17:09:48 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 118 Data should be of same length and content
ok 119 Data should be of same length and content
# teardown
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - close'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-05-08 17:09:48 - WARN createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 -  error Error: read ECONNRESET'
# setup
2017-05-08 17:09:48 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# createPeerListener is idempotent
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Creating Native Server'
ok 120 Can call startUpdateAdvertisingAndListening without error
ok 121 Can call startListeningForAdvertisements without error
2017-05-08 17:09:48 - DEBUG createPeerListener: 'creating new server for peer1'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'listening 50078'
2017-05-08 17:09:48 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50079'
ok 122 Second call to existing peerListener returns existing port
# teardown
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - close'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - ask for new peer when we are at maximum and make sure we remove the right existing listener
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Creating Native Server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'listening 50082'
# teardown
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - close'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - ask for a new peer when we are not at maximum peers and make sure we do not remove any existing listeners
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Creating Native Server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'listening 50085'
# teardown
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - close'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - test timeout
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Creating Native Server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'listening 50088'
# teardown
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - close'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - multiple connections out
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Creating Native Server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'listening 50091'
# teardown
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - close'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - multiple bi-directional connections
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Creating Native Server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'listening 50094'
# teardown
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - close'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - multiple parallel calls
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Creating Native Server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'listening 50097'
# teardown
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - close'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - we shouldn't create a dead pipe
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Creating Native Server'
ok 123 Can call startUpdateAdvertisingAndListening without error
ok 124 Can call startListeningForAdvertisements without error
2017-05-08 17:09:48 - DEBUG createPeerListener: 'creating new server for peer1'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'listening 50100'
2017-05-08 17:09:48 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50101'
ok 125 peerPort != nativePort
2017-05-08 17:09:48 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2017-05-08 17:09:48 - DEBUG createPeerListener: 'callNative for peer1 connected'
2017-05-08 17:09:48 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
ok 126 Should not get unexpected connection
2017-05-08 17:09:48 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID peer1 with port 50101'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client - is already closed'
ok 127 passed
# teardown
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - close'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# can create servers manager
ok 128 serversManager must not be null
ok 129 serversManager must be an object
# teardown
# setup
# calling stop without start causes error
ok 130 We need to call start first
# teardown
# setup
# can start/stop servers manager
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Creating Native Server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'listening 50104'
ok 131 port must be in range
# teardown
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - close'
# setup
# starting twice resolves with listening port
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Creating Native Server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'listening 50105'
ok 132 second start should return same port
# teardown
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - close'
# setup
# terminateIncomingConnection will terminate a connection
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Creating Native Server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'listening 50107'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 133 we should be connected
2017-05-08 17:09:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 134 now we are disconnected
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG createNativeListener: 'Native Server - close'
# setup
# terminate an Outgoing connection
2017-05-08 17:09:48 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
ok 135 Passed bogus id
2017-05-08 17:09:48 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
ok 136 Passed good id but bogus port
2017-05-08 17:09:48 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
ok 137 Passed right context
ok 138 Right server
ok 139 No error should be set
ok 140 Retry should be false
ok 141 We called close server
# teardown
# setup
ok 142 should be in started state
# After #startListeningForAdvertisements call should listen to SSDP advertisements and emit wifiPeerAvailabilityChanged events
ok 143 peer identifier should match
ok 144 generation should be 0
ok 145 host address should match
ok 146 port should match
ok 147 generation should be 0
ok 148 host address should be null
ok 149 port should should be null
# teardown
ok 150 should not be in started state
# setup
ok 151 should be in started state
# #startUpdateAdvertisingAndListening correctly updates USN
2017-05-08 17:09:48 - DEBUG thaliWifiInfrastructure: 'listening 50109'
ok 152 first invocation sets 0 generation
ok 153 second invocation doesn’t change UUID but increments generation
ok 154 third invocation doesn’t change UUID but increments generation
# teardown
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 155 should not be in started state
# setup
ok 156 should be in started state
# #startUpdateAdvertisingAndListening generates new peerIdentifier after #stopAdvertisingAndListening has been called
2017-05-08 17:09:48 - DEBUG thaliWifiInfrastructure: 'listening 50110'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG thaliWifiInfrastructure: 'listening 50111'
ok 157 new UUID after advertising is stopped
# teardown
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 158 should not be in started state
# setup
ok 159 should be in started state
# #startUpdateAdvertisingAndListening sends correct requests
2017-05-08 17:09:48 - DEBUG thaliWifiInfrastructure: 'listening 50112'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 160 advertise-alive fired with expected usn
ok 161 advertise-bye fired with expected usn
# teardown
ok 162 should not be in started state
# setup
ok 163 should be in started state
# messages with invalid location or USN should be ignored
2017-05-08 17:09:48 - WARN thaliWifiInfrastructure: 'Failed to parse a valid port number from location: http://foo.bar:90000'
ok 164 should not have emitted with invalid port
ok 165 should not have emitted with invalid USN
# teardown
ok 166 should not be in started state
# setup
ok 167 should be in started state
# Delayed own message are still ignored after advertisement has been toggled on and off several times
2017-05-08 17:09:48 - DEBUG thaliWifiInfrastructure: 'listening 50113'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG thaliWifiInfrastructure: 'listening 50114'
2017-05-08 17:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:48 - DEBUG thaliWifiInfrastructure: 'listening 50115'
2017-05-08 17:09:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:49 - DEBUG thaliWifiInfrastructure: 'listening 50116'
ok 168 all captured messages are not handled
# teardown
2017-05-08 17:09:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 169 should not be in started state
# setup
ok 170 should be in started state
# verify that Thali-specific messages are filtered correctly
ok 171 messages with irrelevant NT should be ignored
ok 172 relevant messages should not be ignored
# teardown
ok 173 should not be in started state
# setup
ok 174 should be in started state
# #startListeningForAdvertisements should fail if start not called
ok 175 specific error should be returned
# teardown
ok 176 should not be in started state
# setup
ok 177 should be in started state
# #startUpdateAdvertisingAndListening should fail if start not called
ok 178 specific error should be returned
# teardown
ok 179 should not be in started state
# setup
ok 180 should be in started state
# #start should fail if called twice in a row
ok 181 specific error should be received
# teardown
ok 182 should not be in started state
# setup
ok 183 should be in started state
# should not be started after stop is called
ok 184 should not be started
ok 185 should not be listening
ok 186 should not be advertising
ok 187 should not target listening
ok 188 should not target advertising
# teardown
ok 189 should not be in started state
# setup
ok 190 should be in started state
# #startUpdateAdvertisingAndListening should fail invalid router has been passed
2017-05-08 17:09:50 - ERROR thaliWifiInfrastructure: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 191 specific error should be received
# teardown
ok 192 should not be in started state
# setup
ok 193 should be in started state
# #startUpdateAdvertisingAndListening should fail if router server starting fails
2017-05-08 17:09:50 - ERROR thaliWifiInfrastructure: 'Router server emitted an error: Error: listen EADDRINUSE'
ok 194 specific error expected
# teardown
ok 195 should not be in started state
# setup
ok 196 should be in started state
# #startUpdateAdvertisingAndListening should start hosting given router object
2017-05-08 17:09:50 - DEBUG thaliWifiInfrastructure: 'listening 50118'
ok 197 server should respond with code 200
# teardown
2017-05-08 17:09:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 198 should not be in started state
# setup
ok 199 should be in started state
# #startUpdateAdvertisingAndListening bad psk should be rejected object
2017-05-08 17:09:50 - DEBUG thaliWifiInfrastructure: 'listening 50120'
ok 200 Connection should be rejected
# teardown
2017-05-08 17:09:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 201 should not be in started state
# setup
ok 202 should be in started state
# #stop can be called multiple times in a row
ok 203 should be in stopped state
ok 204 should still be in stopped state
# teardown
ok 205 should not be in started state
# setup
ok 206 should be in started state
# #startListeningForAdvertisements can be called multiple times in a row
ok 207 should be in listening state
ok 208 should still be in listening state
# teardown
ok 209 should not be in started state
# setup
ok 210 should be in started state
# #stopListeningForAdvertisements can be called multiple times in a row
ok 211 should not be in listening state
ok 212 should still not be in listening state
# teardown
ok 213 should not be in started state
# setup
ok 214 should be in started state
# #stopAdvertisingAndListening can be called multiple times in a row
ok 215 should not be in advertising state
ok 216 should still not be in advertising state
# teardown
ok 217 should not be in started state
# setup
ok 218 should be in started state
# calls correct starts when network changes
2017-05-08 17:09:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":null,"ssidName":null}'
2017-05-08 17:09:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
ok 219 specific error expected
ok 220 specific error expected
2017-05-08 17:09:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2017-05-08 17:09:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-05-08 17:09:50 - DEBUG thaliWifiInfrastructure: 'listening 50122'
ok 221 listening started at least once
ok 222 advertising started at least once
# teardown
2017-05-08 17:09:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 223 should not be in started state
# setup
ok 224 should be in started state
# does not get peer changes from self
2017-05-08 17:09:50 - DEBUG thaliWifiInfrastructure: 'listening 50123'
# teardown
2017-05-08 17:09:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 225 should not be in started state
# setup
ok 226 should be in started state
# Make sure we turn on and off the Android multicast locks
ok 227 We have locked
ok 228 We have not unlocked
ok 229 No new locks
ok 230 We unlocked
# teardown
ok 231 should not be in started state
# setup
ok 232 should be in started state
# Make sure we do not use Android locks when we are not on Android
2017-05-08 17:09:52 - DEBUG SimpleThaliTape: 'test was skipped, name: 'Make sure we do not use Android locks when we are not on Android''
# teardown
ok 233 should not be in started state
# setup
ok 234 should be in started state
# functions are run from a queue in the right order
2017-05-08 17:09:52 - DEBUG thaliWifiInfrastructure: 'listening 50124'
2017-05-08 17:09:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 235 call order must match
# teardown
ok 236 should not be in started state
# setup
ok 237 should be in started state
# Discovered peer should be removed if no availability updates were received during availability timeout
ok 238 port is null
ok 239 host is null
# teardown
ok 240 should not be in started state
# setup
ok 241 should be in started state
# #stop should clear watchers
ok 242 Watchers have one entry for our connection type
ok 243 No watchers
# teardown
ok 244 should not be in started state
# setup
ok 245 should be in started state
# wifi peer is marked unavailable if announcements stop
ok 246 peer should be available
ok 247 peer should become unavailable
# teardown
ok 248 should not be in started state
# setup
ok 249 should be in started state
# network changes are ignored while stopping
2017-05-08 17:09:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-05-08 17:09:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
ok 250 should not be called
# teardown
ok 251 should not be in started state
# setup
ok 252 should be in started state
# #startListeningForAdvertisements returns error if wifi is off and fires event when on
2017-05-08 17:09:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":null,"ssidName":null}'
2017-05-08 17:09:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
ok 253 wifi should be off
ok 254 specific error expected
2017-05-08 17:09:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2017-05-08 17:09:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
ok 255 discoveryActive should be true
# teardown
ok 256 should not be in started state
# setup
ok 257 should be in started state
# #startUpdateAdvertisingAndListening returns error if wifi is off and fires event when on
2017-05-08 17:09:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":null,"ssidName":null}'
2017-05-08 17:09:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
ok 258 wifi should be off
ok 259 specific error expected
2017-05-08 17:09:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2017-05-08 17:09:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-05-08 17:09:53 - DEBUG thaliWifiInfrastructure: 'listening 50125'
ok 260 advertisingActive should be true
# teardown
2017-05-08 17:09:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 261 should not be in started state
# setup
ok 262 should be in started state
# when wifi is enabled discovery is activated and peers become available
2017-05-08 17:09:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":null,"ssidName":null}'
2017-05-08 17:09:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
ok 263 wifi should be off
ok 264 specific error expected
2017-05-08 17:09:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2017-05-08 17:09:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
ok 265 peer identifier should match
ok 266 host address should match
ok 267 port should match
# teardown
ok 268 should not be in started state
# setup
ok 269 should be in started state
# SSDP server should not restart after Wifi Client changed generation
2017-05-08 17:09:54 - DEBUG thaliWifiInfrastructure: 'listening 50126'
ok 270 SDDP server does not restart
# teardown
2017-05-08 17:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 271 should not be in started state
# setup
ok 272 should be in started state
# startUpdateAdvertisingAndListening does not send ssdp:byebye notifications
2017-05-08 17:09:54 - DEBUG thaliWifiInfrastructure: 'listening 50127'
ok 273 advertise-alive fired
ok 274 advertise-bye not fired
ok 275 generation must be increased
# teardown
2017-05-08 17:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 276 should not be in started state
# setup
ok 277 ThaliMobile should be stopped
# #startListeningForAdvertisements should fail if start not called
ok 278 specific error should be returned
# teardown
ok 279 error should be null
ok 280 error should be null
# setup
ok 281 ThaliMobile should be stopped
# #startUpdateAdvertisingAndListening should fail if start not called
ok 282 specific error should be returned
# teardown
ok 283 error should be null
ok 284 error should be null
# setup
ok 285 ThaliMobile should be stopped
# should be able to call #stopListeningForAdvertisements many times
ok 286 error should be null
ok 287 error should be null
ok 288 error should be null
ok 289 error should be null
# teardown
ok 290 error should be null
ok 291 error should be null
# setup
ok 292 ThaliMobile should be stopped
# should be able to call #startListeningForAdvertisements many times
ok 293 error should be null
ok 294 error should be null
ok 295 error should be null
ok 296 error should be null
# teardown
2017-05-08 17:09:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 297 error should be null
ok 298 error should be null
# setup
ok 299 ThaliMobile should be stopped
# should be able to call #startUpdateAdvertisingAndListening many times
2017-05-08 17:09:54 - DEBUG thaliWifiInfrastructure: 'listening 50128'
ok 300 error should be null
ok 301 error should be null
ok 302 error should be null
ok 303 error should be null
# teardown
2017-05-08 17:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 304 error should be null
ok 305 error should be null
# setup
ok 306 ThaliMobile should be stopped
# should be able to call #stopAdvertisingAndListening many times
ok 307 error should be null
ok 308 error should be null
ok 309 error should be null
ok 310 error should be null
# teardown
ok 311 error should be null
ok 312 error should be null
# setup
ok 313 ThaliMobile should be stopped
# #start - Causing native or wifi to fail will cause a promise reject 
2017-05-08 17:09:54 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
ok 314 This should not cause wifi to fail
ok 315 native router should be bad
# teardown
ok 316 error should be null
ok 317 error should be null
# setup
ok 318 ThaliMobile should be stopped
# #start should fail if called twice in a row
ok 319 first call should succeed
ok 320 first call should succeed
ok 321 specific error should be returned
# teardown
ok 322 error should be null
ok 323 error should be null
# setup
ok 324 ThaliMobile should be stopped
# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
2017-05-08 17:09:54 - DEBUG SimpleThaliTape: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
# teardown
ok 325 error should be null
ok 326 error should be null
# setup
ok 327 ThaliMobile should be stopped
# does not emit duplicate discoveryAdvertisingStateUpdate
2017-05-08 17:09:54 - DEBUG thaliWifiInfrastructure: 'listening 50129'
ok 328 called only once
ok 329 discovery state matches
ok 330 advertising state matches
# teardown
2017-05-08 17:09:54 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-05-08 17:09:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-05-08 17:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 331 error should be null
ok 332 error should be null
# setup
ok 333 ThaliMobile should be stopped
# does not send duplicate availability changes
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8fc4950b-1966-4c00-b1b3-88c7c6b236ca","connectionType":"AndroidBluetooth","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 334 should be called once
ok 335 should not have been called more than once
# teardown
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8fc4950b-1966-4c00-b1b3-88c7c6b236ca","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 336 error should be null
ok 337 error should be null
# setup
ok 338 ThaliMobile should be stopped
# can get the network status
ok 339 network status should have certain non-empty properties
# teardown
ok 340 error should be null
ok 341 error should be null
# setup
ok 342 ThaliMobile should be stopped
# peerAvailabilityChanged - peer added/removed to/from cache (native)
ok 343 we have not added peer to the cache yet
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6a435f15-de34-4c9d-9acb-255d928206fd","connectionType":"AndroidBluetooth","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 344 peer should be available
ok 345 cache contains native peer
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6a435f15-de34-4c9d-9acb-255d928206fd","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 346 peer should be unavailable
ok 347 peer has been removed from cache
# teardown
ok 348 error should be null
ok 349 error should be null
# setup
ok 350 ThaliMobile should be stopped
# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
ok 351 we have not added peer to the cache yet
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d7e1d205-50bd-4635-91a2-0088f793f845","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 352 peer should be available
ok 353 cache contains wifi peer
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d7e1d205-50bd-4635-91a2-0088f793f845","connectionType":"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 354 peer should be unavailable
ok 355 peer has been removed from cache
# teardown
ok 356 error should be null
ok 357 error should be null
# setup
ok 358 ThaliMobile should be stopped
# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d2937c3e-4b4c-4905-842f-defa1c05f2f7","connectionType":"AndroidBluetooth","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 359 first peer is available
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0fcbd34e-a944-49f4-bdad-2bde81e865a1","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 360 second peer is available
ok 361 first and second peers are different
# teardown
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"d2937c3e-4b4c-4905-842f-defa1c05f2f7","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0fcbd34e-a944-49f4-bdad-2bde81e865a1","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 362 error should be null
ok 363 error should be null
# setup
ok 364 ThaliMobile should be stopped
# native available - new peer is cached
ok 365 should not be in cache at start
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c04e3268-c2af-463f-a6ad-030d0be8ddb0","connectionType":"AndroidBluetooth","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 366 peer is available
# teardown
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c04e3268-c2af-463f-a6ad-030d0be8ddb0","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 367 error should be null
ok 368 error should be null
# setup
ok 369 ThaliMobile should be stopped
# native available - peer with same port and different generation is cached (BLUETOOTH)
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"293040c8-2e85-45c8-b2a2-22188f635a31","connectionType":"AndroidBluetooth","peerAvailable":true,"generation":2,"newAddressPort":false}'
ok 370 peer should be available
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"293040c8-2e85-45c8-b2a2-22188f635a31","connectionType":"AndroidBluetooth","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 371 peer should be available
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"293040c8-2e85-45c8-b2a2-22188f635a31","connectionType":"AndroidBluetooth","peerAvailable":true,"generation":1,"newAddressPort":false}'
ok 372 peer should be available
# teardown
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"293040c8-2e85-45c8-b2a2-22188f635a31","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 373 error should be null
ok 374 error should be null
# setup
ok 375 ThaliMobile should be stopped
# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"936c6744-d054-4bd1-b993-92b1712e8755","connectionType":"AndroidBluetooth","peerAvailable":true,"generation":2,"newAddressPort":false}'
ok 376 peer should be available
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"936c6744-d054-4bd1-b993-92b1712e8755","connectionType":"AndroidBluetooth","peerAvailable":true,"generation":2,"newAddressPort":false}'
ok 377 peer should be available
# teardown
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"936c6744-d054-4bd1-b993-92b1712e8755","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 378 error should be null
ok 379 error should be null
# setup
ok 380 ThaliMobile should be stopped
# native available - peer with greater generation is cached (MPCF)
2017-05-08 17:09:54 - DEBUG SimpleThaliTape: 'test was skipped, name: 'native available - peer with greater generation is cached (MPCF)''
# teardown
ok 381 error should be null
ok 382 error should be null
# setup
ok 383 ThaliMobile should be stopped
# native available - peer with same or older generation is ignored (MPCF)
2017-05-08 17:09:54 - DEBUG SimpleThaliTape: 'test was skipped, name: 'native available - peer with same or older generation is ignored (MPCF)''
# teardown
ok 384 error should be null
ok 385 error should be null
# setup
ok 386 ThaliMobile should be stopped
# native unavailable - new peer is ignored
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6b439f86-f83b-48da-8227-9ffcfa99a8ee","connectionType":"AndroidBluetooth","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 387 discovered available peer
ok 388 peer is available
# teardown
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"6b439f86-f83b-48da-8227-9ffcfa99a8ee","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 389 error should be null
ok 390 error should be null
# setup
ok 391 ThaliMobile should be stopped
# native unavailable - cached peer is removed
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a6b47846-78c0-456c-9e29-75a4a4566d73","connectionType":"AndroidBluetooth","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 392 peer should be available
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a6b47846-78c0-456c-9e29-75a4a4566d73","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 393 peer should be unavailable
ok 394 should be removed from cache
# teardown
ok 395 error should be null
ok 396 error should be null
# setup
ok 397 ThaliMobile should be stopped
# networkChanged - fires peerAvailabilityChanged event for wifi peers
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"854a2074-3ca0-4a43-8537-3200380fbfbc","connectionType":"AndroidBluetooth","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 398 first peer is expected to be available
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4ccf09c1-7ae7-4c53-8ccb-488c094bbd37","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 399 second peer is expected to be available
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"4ccf09c1-7ae7-4c53-8ccb-488c094bbd37","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 400 peer became unavailable
ok 401 it was wifi peer
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4ccf09c1-7ae7-4c53-8ccb-488c094bbd37","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 402 we found peer again
ok 403 it was wifi peer
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"4ccf09c1-7ae7-4c53-8ccb-488c094bbd37","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 404 peer became unavailable
ok 405 it was wifi peer
# teardown
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"854a2074-3ca0-4a43-8537-3200380fbfbc","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 406 error should be null
ok 407 error should be null
# setup
ok 408 ThaliMobile should be stopped
# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b733cafc-b3b4-49d4-8f12-b573094d85c3","connectionType":"AndroidBluetooth","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 409 first peer is expected to be available
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"58a56524-df34-487b-a537-d63d5a4d808a","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 410 second peer is expected to be available
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b733cafc-b3b4-49d4-8f12-b573094d85c3","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 411 peer became unavailable
ok 412 it was a native peer
# teardown
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"58a56524-df34-487b-a537-d63d5a4d808a","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 413 error should be null
ok 414 error should be null
# setup
ok 415 ThaliMobile should be stopped
# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
2017-05-08 17:09:54 - DEBUG SimpleThaliTape: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''
# teardown
ok 416 error should be null
ok 417 error should be null
# setup
ok 418 ThaliMobile should be stopped
# multiconnect failure - new peer is ignored (MPCF)
2017-05-08 17:09:54 - DEBUG SimpleThaliTape: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
# teardown
ok 419 error should be null
ok 420 error should be null
# setup
ok 421 ThaliMobile should be stopped
# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
2017-05-08 17:09:54 - DEBUG SimpleThaliTape: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
# teardown
ok 422 error should be null
ok 423 error should be null
# setup
ok 424 ThaliMobile should be stopped
# newAddressPort field (TCP_NATIVE)
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"247c50ee-964c-44da-a146-32374154e1f7","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 425 peer discovered first time does not have new address
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"247c50ee-964c-44da-a146-32374154e1f7","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":false}'
ok 426 address has not been changed
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"247c50ee-964c-44da-a146-32374154e1f7","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
ok 427 new port handled correctly
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"247c50ee-964c-44da-a146-32374154e1f7","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
ok 428 new host handled correctly
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"247c50ee-964c-44da-a146-32374154e1f7","connectionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
ok 429 newAddressPort is null for unavailable peers
# teardown
ok 430 error should be null
ok 431 error should be null
# setup
ok 432 ThaliMobile should be stopped
# newAddressPort field (BLUETOOTH)
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"935a7e00-4484-469a-990d-7eac4ad48685","connectionType":"AndroidBluetooth","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 433 peer discovered first time does not have new address
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"935a7e00-4484-469a-990d-7eac4ad48685","connectionType":"AndroidBluetooth","peerAvailable":true,"generation":20,"newAddressPort":false}'
ok 434 address has not been changed
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"935a7e00-4484-469a-990d-7eac4ad48685","connectionType":"AndroidBluetooth","peerAvailable":true,"generation":20,"newAddressPort":true}'
ok 435 new port handled correctly
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"935a7e00-4484-469a-990d-7eac4ad48685","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":20,"newAddressPort":null}'
ok 436 newAddressPort is null for unavailable peers
# teardown
ok 437 error should be null
ok 438 error should be null
# setup
ok 439 ThaliMobile should be stopped
# newAddressPort field (MPCF)
2017-05-08 17:09:54 - DEBUG SimpleThaliTape: 'test was skipped, name: 'newAddressPort field (MPCF)''
# teardown
ok 440 error should be null
ok 441 error should be null
# setup
ok 442 ThaliMobile should be stopped
# newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)
ok 443 NOT IMPLEMENTED # SKIP
# teardown
ok 444 error should be null
ok 445 error should be null
# setup
ok 446 ThaliMobile should be stopped
# #getPeerHostInfo - error when peer has not been discovered yet
ok 447 should be equal
# teardown
ok 448 error should be null
ok 449 error should be null
# setup
ok 450 ThaliMobile should be stopped
# #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"AndroidBluetooth","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 451 contains expected properties
ok 452 the same hostAddress
ok 453 the same portNumber
# teardown
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 454 error should be null
ok 455 error should be null
# setup
ok 456 ThaliMobile should be stopped
# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
2017-05-08 17:09:54 - DEBUG SimpleThaliTape: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)''
# teardown
ok 457 error should be null
ok 458 error should be null
# setup
ok 459 ThaliMobile should be stopped
# #getPeerHostInfo - returns discovered cached wifi peer
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 460 contains expected properties
ok 461 the same hostAddress
ok 462 the same portNumber
# teardown
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 463 error should be null
ok 464 error should be null
# setup
ok 465 ThaliMobile should be stopped
# #disconnect fails on wifi peers
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"462215ec-2a64-4136-8172-c8910306f9a0","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 466 Got specific error message
# teardown
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"462215ec-2a64-4136-8172-c8910306f9a0","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 467 error should be null
ok 468 error should be null
# setup
ok 469 ThaliMobile should be stopped
# #disconnect delegates native peers to the native wrapper
2017-05-08 17:09:54 - DEBUG SimpleThaliTape: 'test was skipped, name: '#disconnect delegates native peers to the native wrapper''
# teardown
ok 470 error should be null
ok 471 error should be null
# setup
ok 472 ThaliMobile should be stopped
# network changes emitted correctly
2017-05-08 17:09:54 - DEBUG SimpleThaliTape: 'test was skipped, name: 'network changes emitted correctly''
# teardown
ok 473 error should be null
ok 474 error should be null
# setup
ok 475 ThaliMobile should be stopped
# network changes not emitted in started state
2017-05-08 17:09:54 - DEBUG SimpleThaliTape: 'test was skipped, name: 'network changes not emitted in started state''
# teardown
ok 476 error should be null
ok 477 error should be null
# setup
ok 478 ThaliMobile should be stopped
# network changes not emitted in stopped state
2017-05-08 17:09:54 - DEBUG SimpleThaliTape: 'test was skipped, name: 'network changes not emitted in stopped state''
# teardown
ok 479 error should be null
ok 480 error should be null
# setup
ok 481 ThaliMobile should be stopped
# We properly fire peer unavailable and then available when connection fails on Android
2017-05-08 17:09:54 - DEBUG SimpleThaliTape: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on Android''
# teardown
ok 482 error should be null
ok 483 error should be null
# setup
ok 484 ThaliMobile should be stopped
# We properly fire peer unavailable and then available when connection fails on iOS
2017-05-08 17:09:54 - DEBUG SimpleThaliTape: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
# teardown
ok 485 error should be null
ok 486 error should be null
# setup
ok 487 ThaliMobile should be stopped
# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
2017-05-08 17:09:54 - DEBUG SimpleThaliTape: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
# teardown
ok 488 error should be null
ok 489 error should be null
# setup
ok 490 ThaliMobile should be stopped
# does not fire duplicate events after peer listener recreation
2017-05-08 17:09:54 - DEBUG SimpleThaliTape: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
# teardown
ok 491 error should be null
ok 492 error should be null
# setup
ok 493 ThaliMobile should be stopped
# #stop should change peers
2017-05-08 17:09:54 - DEBUG thaliMobileNativeWrapper: 'listening 50130'
2017-05-08 17:09:54 - DEBUG createNativeListener: 'Creating Native Server'
2017-05-08 17:09:54 - DEBUG createNativeListener: 'listening 50131'
2017-05-08 17:09:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8f8c1f47-c508-4bab-8b1c-1ddf13eedbce","connectionType":"AndroidBluetooth","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 494 Peer availabilities has one entry for our connection type
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7c0c0b71-1169-489d-bcc5-f1a626c6c4d7","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 495 Peer availabilities has one entry for our connection type
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8f8c1f47-c508-4bab-8b1c-1ddf13eedbce","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"7c0c0b71-1169-489d-bcc5-f1a626c6c4d7","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-05-08 17:09:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-05-08 17:09:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-05-08 17:09:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-05-08 17:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:09:54 - DEBUG createNativeListener: 'Native Server - close'
2017-05-08 17:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 496 No peers
ok 497 No peers
ok 498 No peers
# teardown
ok 499 error should be null
ok 500 error should be null
# setup
ok 501 ThaliMobile should be stopped
# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9e1a5096-d4b5-4849-ad1a-102ba35465c4","connectionType":"AndroidBluetooth","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 502 1
ok 503 2
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"64530530-ddc4-4d3c-974e-b657128f385a","connectionType":"AndroidBluetooth","peerAvailable":true,"generation":0,"newAddressPort":false}'
# teardown
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9e1a5096-d4b5-4849-ad1a-102ba35465c4","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-05-08 17:09:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"64530530-ddc4-4d3c-974e-b657128f385a","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 504 error should be null
ok 505 error should be null
# setup
# #testThaliPeerAction - test getters
ok 506 getPeerIdentifier
ok 507 getConnectionType
ok 508 getActionType
ok 509 getActionState
ok 510 getPskIdentity
ok 511 getPskKey
# teardown
# setup
# #testThaliPeerAction - start and kill
ok 512 initial state
ok 513 after start
2017-05-08 17:09:54 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 514 after kill
# teardown
# setup
# #testThaliPeerAction - double start
ok 515 should be equal
# teardown
# setup
# #testThaliPeerAction - start after kill
2017-05-08 17:09:54 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 516 clean kill
ok 517 should be equal
# teardown
# setup
# #testThaliPeerAction - make sure ids are unique
ok 518 should not be equal
# teardown
# setup
# #testThaliPeerAction - check that forever agent can be destroyed
ok 519 forever agent should have it's own destroy method
ok 520 agent's destroy should be called
ok 521 agent's destroy should not be called again
ok 522 agent is destroyed
# teardown
# setup
# Test PeerDictionary basic functionality
ok 523 Entry counter must be 1
ok 524 Entry exists
ok 525 Size must be 1
ok 526 Entry counter must be 2
ok 527 Entry exists
ok 528 Size must be 2
ok 529 Entry counter must be 1
ok 530 Entry exists
ok 531 Size must be 3
ok 532 Entry counter must be 2
ok 533 Entry exists
ok 534 Size must be 4
ok 535 Entry 1_1 should not be found
ok 536 Entry 1_1 does not exist
ok 537 Size must be 3
ok 538 Entry 1_2 should not be found
ok 539 Entry 1_2 does not exist
ok 540 Size must be 2
ok 541 should be equal
ok 542 Entry 2_1 should not be found
ok 543 Entry 2_2 should not be found
ok 544 Entry 2_1 does not exist
ok 545 Entry 2_2 does not exist
ok 546 Size must be 0
# teardown
# setup
# Test PeerDictionary with multiple entries.
ok 547 Size must be100
ok 548 Entries between 20 and MAXSIZE + 20 should exist
ok 549 WAITING state entry should not be removed
# teardown
# setup
# RESOLVED entries are removed before WAITING state entry.
ok 550 Entries between 6 and MAXSIZE + 4 should exist
ok 551 Size should be MAXSIZE
ok 552 Size should be MAXSIZE+6
# teardown
# setup
# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
ok 553 WAITING state entry should not be removed
ok 554 Waiting entries between 6 and MAXSIZE + 4 should exist
ok 555 Size should be MAXSIZE
ok 556 entryCounter should be MAXSIZE+6
# teardown
# setup
# When CONTROLLED_BY_POOL entry is removed and kill is called.
ok 557 Kill should be called once
ok 558 Size should be MAXSIZE
# teardown
# setup
# #ThaliPeerPoolDefault - single action
ok 559 is an agent
ok 560 enqueue is fine
ok 561 Everything should be off the queue
# teardown
# setup
# #ThaliPeerPoolDefault - multiple actions
ok 562 is an agent
ok 563 first enqueue is fine
ok 564 is an agent
ok 565 second enqueue is fine
ok 566 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 567 Queue is empty
# teardown
# setup
# #ThaliPeerPoolDefault - PSK Pool works
ok 568 is an agent
ok 569 good enqueue
ok 570 Identity should match
2017-05-08 17:09:55 - DEBUG testUtils: 'Got response data'
2017-05-08 17:09:55 - DEBUG testUtils: 'Got end'
ok 571 Got expected response
ok 572 Got psk call back
# teardown
2017-05-08 17:09:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #ThaliPeerPoolDefault - stop
ok 573 is an agent
ok 574 enqueue worked
ok 575 is an agent
ok 576 enqueue 2 worked
ok 577 enqueue is not available when stopped
ok 578 start action is killed
ok 579 killed action is still killed
ok 580 enqueued action when stopped is killed
ok 581 inQueue is empty
# teardown
# setup
# #ThaliPeerPoolInterface - make sure that start verifies queue length
ok 582 good start
ok 583 good enqueue
ok 584 queue is not empty
# teardown
# setup
# #ThaliPeerPoolInterface - bad enqueues
ok 585 null arg
ok 586 wrong arg type
ok 587 wrong arg type
# teardown
# setup
# #ThaliPeerPoolInterface - do not allow same object type
ok 588 good enqueue
ok 589 already enqueued
# teardown
# setup
# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
ok 590 good enqueue
ok 591 2nd good enqueue
ok 592 we are in the pool
ok 593 We are out of the pool
ok 594 Action was killed
ok 595 The original kill was called too
ok 596 second item is still in queue
# teardown
# setup
# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
ok 597 good enqueue
ok 598 first kill
ok 599 second NOOP kill
# teardown
# setup
# #ThaliPeerPoolInterface - make sure that stop removes all actions
ok 600 1st good enqueue
ok 601 2nd good enqueue
ok 602 1st action is in the pool
ok 603 2nd action is in the pool
ok 604 1st action is out of the pool
ok 605 2st action is out of the pool
ok 606 pool is empty
# teardown
# setup
# We reject unrecognized connection type
2017-05-08 17:09:55 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 607 Got right error
ok 608 Start should not be called
ok 609 Kill should have been called at least once
# teardown
# setup
# We reject unrecognized action type
2017-05-08 17:09:55 - DEBUG SimpleThaliTape: 'test was skipped, name: 'We reject unrecognized action type''
# teardown
# setup
# One action on bluetooth
2017-05-08 17:09:55 - DEBUG SimpleThaliTape: 'test was skipped, name: 'One action on bluetooth''
# teardown
# setup
# Two notification actions
2017-05-08 17:09:55 - DEBUG SimpleThaliTape: 'test was skipped, name: 'Two notification actions''
# teardown
# setup
# replicateThroughProblems
2017-05-08 17:09:55 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
2017-05-08 17:09:55 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
2017-05-08 17:09:55 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
ok 610 should have gotten null
2017-05-08 17:09:55 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
2017-05-08 17:09:55 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
ok 611 Should have stopped nicely
2017-05-08 17:09:55 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
2017-05-08 17:09:55 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
ok 612 Still looking for null
2017-05-08 17:09:55 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
2017-05-08 17:09:55 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
2017-05-08 17:09:55 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
2017-05-08 17:09:55 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
2017-05-08 17:09:55 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
2017-05-08 17:09:55 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
ok 613 Yup, another null
ok 614 We cloned!
# teardown
# setup
# Replication goes first
2017-05-08 17:09:55 - DEBUG SimpleThaliTape: 'test was skipped, name: 'Replication goes first''
# teardown
# setup
# wifi allows many parallel non-replication actions
2017-05-08 17:09:55 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2017-05-08 17:09:55 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 586, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
ok 615 is an agent
ok 616 First does not throw
2017-05-08 17:09:55 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
ok 617 is an agent
ok 618 Second does not throw
2017-05-08 17:09:55 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 587, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
truetruefalsetrue
2017-05-08 17:09:55 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 586, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
truetruetruetrue
# teardown
# setup
# wifi allows no more than 2 simultaneous replication actions for same peerID
2017-05-08 17:09:55 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2017-05-08 17:09:55 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
ok 619 is an agent
ok 620 first ok
2017-05-08 17:09:55 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
ok 621 is an agent
ok 622 second ok
ok 623 third ok
2017-05-08 17:09:55 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
2017-05-08 17:09:55 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 589, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
2017-05-08 17:09:55 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
2017-05-08 17:09:55 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
# teardown
# setup
# Test BEACONS_RETRIEVED_AND_PARSED locally
ok 624 peerIdentifier should match
ok 625 generation should match
ok 626 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 627 good beacon
ok 628 good preAmble
ok 629 public keys match!
ok 630 must return null after successful call
ok 631 Once start returns the action should be in KILLED state
# teardown
2017-05-08 17:09:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test HTTP_BAD_RESPONSE locally
ok 632 Response should be HTTP_BAD_RESPONSE
ok 633 must return null after successful call
# teardown
2017-05-08 17:09:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test NETWORK_PROBLEM locally
ok 634 Response should be NETWORK_PROBLEM
ok 635 reject reason should be: Could not establish TCP connection
# teardown
2017-05-08 17:09:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Action fails when getPeerHostInfo fails
ok 636 Resolution should be BAD_PEER
ok 637 correct error message
# teardown
2017-05-08 17:09:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Call the start two times
ok 638 Call start once
ok 639 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 640 must return null after successful call.
# teardown
2017-05-08 17:09:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Call the kill before calling the start
ok 641 Should be Killed
ok 642 Start after killed
# teardown
2017-05-08 17:09:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Call the kill immediately after the start
ok 643 Should be KILLED
ok 644 must return null after successful kill
# teardown
2017-05-08 17:09:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Call the kill while waiting a response from the server
ok 645 Should be KILLED
ok 646 must return null after successful kill
# teardown
2017-05-08 17:09:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test to exceed the max content size locally
ok 647 HTTP_BAD_RESPONSE should be response when content size is exceeded
ok 648 must return null after successful call
# teardown
2017-05-08 17:09:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Close the server socket while the client is waiting a response from the server. Local test.
2017-05-08 17:09:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 649 Should be NETWORK_PROBLEM caused closing server socket
ok 650 Should be Could not establish TCP connection
# teardown
# setup
# Close the client socket while the client is waiting a response from the server. Local test.
ok 651 Should be NETWORK_PROBLEM caused closing client socket
ok 652 Should be Could not establish TCP connection
# teardown
2017-05-08 17:10:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #generatePreambleAndBeacons bad args
ok 653 publicKeysToNotify cannot be null
ok 654 ecdh for local device cannot be null
ok 655 milliseconds cannot be less than 0
ok 656 milliseconds cannot be 0
ok 657 milliseconds cannot be greater than one_day
# teardown
# setup
# #generatePreambleAndBeacons empty keys to notify
ok 658 should be equal
# teardown
# setup
# #generatePreambleAndBeacons multiple keys to notify
ok 659 should be equal
ok 660 should be equal
ok 661 (unnamed assert)
ok 662 should be equal
# teardown
# setup
# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
ok 663 should throw
# teardown
# setup
# #parseBeacons invalid expiration in beaconStreamWithPreAmble
ok 664 Preamble expiration must be a 64 bit integer
# teardown
# setup
# #parseBeacons expiration out of range lower
ok 665 Expiration out of range
# teardown
# setup
# #parseBeacons expiration out of range lower
ok 666 Expiration out of range
# teardown
# setup
# #parseBeacons no beacons returns null
ok 667 should be equal
# teardown
# setup
# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
ok 668 Malformed encrypted beacon key ID
# teardown
# setup
# #parseBeacons addressBookCallback fails decrypt
ok 669 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns no matches
ok 670 should be equal
ok 671 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns spurious match
ok 672 should be equal
ok 673 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns public key
ok 674 right number of calls to address book
ok 675 good preAmble
ok 676 good unencryptedKeyId
ok 677 good beacon
# teardown
# setup
# validate generatePskIdentityField
ok 678 decoded buffers match
# teardown
# setup
# validate generatePskSecret
ok 679 secrets match
# teardown
# setup
# validate generatePskSecrets
ok 680 Matching numbers
ok 681 We have an entry!
ok 682 keys match
ok 683 secrets match
ok 684 We have an entry!
ok 685 keys match
ok 686 secrets match
ok 687 We have an entry!
ok 688 keys match
ok 689 secrets match
# teardown
# setup
# validate generateBeaconStreamAndSecrets
ok 690 Streams have same length
ok 691 matching size
ok 692 keys match
ok 693 secrets match
# teardown
# setup
# Add two Peers.
ok 694 should be equal
ok 695 peerDictionalty contains 2 peers
ok 696 bluetooth peer's notification has correct connection type
ok 697 tcp peer's notification has correct connection type
2017-05-08 17:10:02 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
2017-05-08 17:10:02 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
# teardown
2017-05-08 17:10:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# TCP_NATIVE peer loses DNS
ok 698 notification peer dictionary contains exactly 1 peer
2017-05-08 17:10:02 - WARN thaliNotificationClient: 'peer is not available'
ok 699 notification peer dictionary does not contain any peers
2017-05-08 17:10:02 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
# teardown
2017-05-08 17:10:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Received beacons with no values for us
ok 700 entry exists
ok 701 entry is resolved
# teardown
2017-05-08 17:10:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Notification action killed with a superseded
ok 702 Action should be KILLED
ok 703 Peer state should be RESOLVED
# teardown
2017-05-08 17:10:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Resolves an action locally
ok 704 hostAddress must match
ok 705 portNumber must match
ok 706 suggestedTCPTimeout must match
ok 707 connectionType must match
ok 708 peerIDs must match
# teardown
2017-05-08 17:10:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Emits error event when peerPool.enqueue throws
ok 709 Correct error
# teardown
2017-05-08 17:10:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Resolves an action locally using ThaliPeerPoolDefault
ok 710 hostAddress must match
ok 711 portNumber must match
ok 712 suggestedTCPTimeout must match
ok 713 connectionType must match
ok 714 peerIds must match
# teardown
2017-05-08 17:10:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Action fails because of a bad hostname.
2017-05-08 17:10:02 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 715 action should be resolved with NETWORK_PROBLEM error
2017-05-08 17:10:02 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 716 action should be resolved with NETWORK_PROBLEM error
2017-05-08 17:10:02 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 717 action should be resolved with NETWORK_PROBLEM error
2017-05-08 17:10:03 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 718 action should be resolved with NETWORK_PROBLEM error
ok 719 correct number of requests
ok 720 correct number of failures
ok 721 correct final peer state
# teardown
2017-05-08 17:10:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# hostaddress is removed when the action is running. 
2017-05-08 17:10:05 - WARN thaliNotificationClient: 'peer is not available'
2017-05-08 17:10:05 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 722 peerDictionary should become empty
# teardown
2017-05-08 17:10:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# notificationClient does not retry action with BAD_PEER resolution
2017-05-08 17:10:05 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 723 failed with expected error
ok 724 peer state should be RESOLVED
# teardown
2017-05-08 17:10:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# notification client correctly handles peer availability changes of the same peer
2017-05-08 17:10:05 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 725 First action failed
ok 726 second action killed
# teardown
2017-05-08 17:10:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Client to server request locally
ok 727 secrets are equal
ok 728 Public key matches with the server key
ok 729 hostAddress must match
ok 730 portNumber must match
ok 731 suggestedTCPTimeout must match
ok 732 connectionType must match
# teardown
2017-05-08 17:10:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test ThaliPskMapCache clean and expiration
ok 733 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
ok 734 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
ok 735 All entries should be expired after 1 second
# teardown
2017-05-08 17:10:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test ThaliPskMapCache getSecret and getPublic
ok 736 All keys need to be available in the cache
ok 737 All entries should be expired after 1 second
# teardown
2017-05-08 17:10:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test ThaliPskMapCache multiple entries
ok 738 Size of the cache should be 2
ok 739 Cache doesn't contain dictionary1
ok 740 Size of the cache should be 1
ok 741 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
2017-05-08 17:10:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Start and stop ThaliNotificationServer
ok 742 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
ok 743 ThaliMobile.StopAdvertisingAndListeningshould be called once
# teardown
2017-05-08 17:10:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Pass an empty array to ThaliNotificationServer.start
ok 744 StartUpdateAdvertisingAndListening should not be called
ok 745 ThaliMobile.StopAdvertisingAndListening should be called once
ok 746 no error
ok 747 should be 204
# teardown
2017-05-08 17:10:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Pass a string to ThaliNotificationServer.start
ok 748 StartUpdateAdvertisingAndListening should not be called
# teardown
2017-05-08 17:10:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Pass an empty parameter to ThaliNotificationServer.start
ok 749 StartUpdateAdvertisingAndListening should not be called
# teardown
2017-05-08 17:10:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make an HTTP request to /NotificationBeacons
ok 750 no error
ok 751 should be 200
ok 752 should be equal
ok 753 should be equal
ok 754 (unnamed assert)
ok 755 no error
ok 756 should be 204
# teardown
2017-05-08 17:10:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make an HTTP request to /NotificationBeacons (no keys)
ok 757 error should be null
ok 758 should be 204
# teardown
2017-05-08 17:10:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make an HTTP request to /NotificationBeaconsbefore calling start
ok 759 should be 404
# teardown
2017-05-08 17:10:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make sure peerDictionaryKey is reasonable
ok 760 equal keys
ok 761 not equal connection type
ok 762 same connection type, different buffer
# teardown
# setup
# Make sure start works
2017-05-08 17:10:10 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 763 First start and on called correctly
# teardown
# setup
# Make sure stop works
ok 764 second cleared dictionary
2017-05-08 17:10:10 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 765 First start and on called correctly
ok 766 First stop and removeListener called correctly
ok 767 first action kill called
ok 768 second action kill called
ok 769 first cleared dictionary
ok 770 first cleared pool
ok 771 second cleared dictionary
ok 772 second cleared pool
# teardown
# setup
# Emits error event when peerPool.enqueue throws
ok 773 Correct error
# teardown
# setup
# Simple peer event
2017-05-08 17:10:10 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 774 listener has been set
ok 775 peer dictionary has expected number of entries
ok 776 Dictionary and pool have same action
ok 777 ads match
ok 778 PouchDB matches
ok 779 DB Names match
ok 780 public keys match
ok 781 peer dictionary has expected number of entries
ok 782 Dictionary and pool have same action
ok 783 ads match
ok 784 PouchDB matches
ok 785 DB Names match
ok 786 public keys match
2017-05-08 17:10:10 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
ok 787 start called once
ok 788 One entry left
ok 789 Dictionary and pool have same action
ok 790 Start never called
ok 791 Kill called once
ok 792 no entries left
ok 793 Third action is dead
ok 794 peer dictionary has expected number of entries
ok 795 Dictionary and pool have same action
ok 796 ads match
ok 797 PouchDB matches
ok 798 DB Names match
ok 799 public keys match
# teardown
# setup
# Server is not there
2017-05-08 17:10:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:10:10 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
2017-05-08 17:10:10 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: connect ECONNREFUSED  and it caused us to complete'
ok 800 right error
# teardown
2017-05-08 17:10:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Server accepts & closes connection
2017-05-08 17:10:10 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
2017-05-08 17:10:10 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
ok 801 right error
# teardown
2017-05-08 17:10:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Server always returns 500
2017-05-08 17:10:10 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
2017-05-08 17:10:10 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
ok 802 Got error as expected
# teardown
2017-05-08 17:10:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Server always returns 401
2017-05-08 17:10:10 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
2017-05-08 17:10:10 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
ok 803 Got error as expected
# teardown
2017-05-08 17:10:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Server always returns 403
2017-05-08 17:10:10 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
2017-05-08 17:10:10 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
ok 804 Got error as expected
# teardown
2017-05-08 17:10:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make sure docs replicate
2017-05-08 17:10:10 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
2017-05-08 17:10:11 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
2017-05-08 17:10:13 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
ok 805 should be equal
ok 806 All tests passed!
# teardown
2017-05-08 17:10:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Do nothing and make sure we time out
2017-05-08 17:10:13 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
2017-05-08 17:10:15 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-05-08 17:10:15 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
ok 807 action should be killed
ok 808 Error should be timed out
ok 809 No doc found
# teardown
2017-05-08 17:10:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Do something and make sure we time out
2017-05-08 17:10:15 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
2017-05-08 17:10:15 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
ok 810 should be equal
2017-05-08 17:10:17 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-05-08 17:10:17 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
ok 811 action should be killed
ok 812 Error should be timed out
# teardown
2017-05-08 17:10:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Start replicating and then catch error when server goes
ok 813 socket hung up
# teardown
2017-05-08 17:10:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make sure clone works
ok 814 same getPeerAdvertisesDataForUs
ok 815 Same pouchdB
ok 816 same dbName
ok 817 Same public key
# teardown
# setup
# compareBufferArrays
ok 818 should throw
ok 819 should throw
ok 820 (unnamed assert)
ok 821 (unnamed assert)
ok 822 (unnamed assert)
ok 823 (unnamed assert)
ok 824 (unnamed assert)
# teardown
# setup
# Call start twice and get error
ok 825 should throw
# teardown
# setup
# Start and make sure it runs
# teardown
# setup
# Make sure getTimeWhenRun is right after start
ok 826 (unnamed assert)
# teardown
# setup
# Make sure getTimeWhenRun is -1 after function is called
ok 827 should be equal
# teardown
# setup
# Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
ok 828 should be equal
ok 829 should be equal
ok 830 should throw
# teardown
# setup
# Test TransientState
ok 831 should throw
ok 832 should throw
ok 833 should be equal
ok 834 should be equal
ok 835 should be equal
ok 836 should be equal
ok 837 (unnamed assert)
ok 838 (unnamed assert)
# teardown
# setup
# No peers and empty database
ok 839 verify failed
ok 840 constructor called once
ok 841 constructor called with right args
ok 842 match start arg
ok 843 start called once
ok 844 stop called once
ok 845 stop after start
# teardown
# setup
# One peer and empty DB
2017-05-08 17:10:17 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 846 verify failed
ok 847 constructor called once
ok 848 constructor called with right args
ok 849 match start arg
ok 850 start called once
ok 851 stop called once
ok 852 stop after start
# teardown
# setup
# One peer with _Local set behind current seq
2017-05-08 17:10:17 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 853 verify failed
ok 854 constructor called once
ok 855 constructor called with right args
ok 856 match start arg
ok 857 start called once
ok 858 stop called once
ok 859 stop after start
# teardown
# setup
# One peer with _Local set equal to current seq
2017-05-08 17:10:17 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 860 verify failed
ok 861 constructor called once
ok 862 constructor called with right args
ok 863 match start arg
ok 864 start called once
ok 865 stop called once
ok 866 stop after start
# teardown
# setup
# One peer with _Local set ahead of current seq (and no this should not happen)
2017-05-08 17:10:18 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 867 verify failed
ok 868 constructor called once
ok 869 constructor called with right args
ok 870 match start arg
ok 871 start called once
ok 872 stop called once
ok 873 stop after start
# teardown
# setup
# Three peers, one not in DB, one behind and one ahead
2017-05-08 17:10:18 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 874 verify failed
ok 875 constructor called once
ok 876 constructor called with right args
ok 877 match start arg
ok 878 start called once
ok 879 stop called once
ok 880 stop after start
# teardown
# setup
# More than maximum peers, make sure we only send maximum allowed
2017-05-08 17:10:18 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 881 verify failed
ok 882 constructor called once
ok 883 constructor called with right args
ok 884 match start arg
ok 885 start called once
ok 886 stop called once
ok 887 stop after start
# teardown
# setup
# two peers with empty DB, update the doc
2017-05-08 17:10:18 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
2017-05-08 17:10:18 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 888 verify failed
ok 889 constructor called once
ok 890 constructor called with right args
ok 891 last start before stop
ok 892 empty first start
ok 893 full second start
ok 894 only 2 timers
# teardown
# setup
# add doc and make sure tokens refresh when they expire
2017-05-08 17:10:18 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
2017-05-08 17:10:18 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
2017-05-08 17:10:18 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 895 verify failed
ok 896 constructor called once
ok 897 constructor called with right args
ok 898 start before stop
ok 899 We got at least 3 calls to start
ok 900 at least 3
ok 901 default 1
ok 902 1 run
ok 903 default 2
ok 904 2 run
ok 905 default 3
# teardown
# setup
# start and stop and start and stop
ok 906 start out null
ok 907 back to null
2017-05-08 17:10:18 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
2017-05-08 17:10:18 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 908 still null
ok 909 verify failed
ok 910 constructor called once
ok 911 constructor called with right args
ok 912 first start before first stop
ok 913 first stop before second start
ok 914 second start before second stop
# teardown
# setup
# two identical starts in a row
2017-05-08 17:10:18 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 915 verify failed
ok 916 constructor called once
ok 917 constructor called with right args
ok 918 (unnamed assert)
# teardown
# setup
# two different starts in a row
2017-05-08 17:10:18 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 919 verify failed
ok 920 constructor called once
ok 921 constructor called with right args
ok 922 (unnamed assert)
ok 923 (unnamed assert)
# teardown
# setup
# two stops and a start and two stops
2017-05-08 17:10:18 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 924 verify failed
ok 925 constructor called once
ok 926 constructor called with right args
ok 927 start before stop
# teardown
# setup
# we properly enqueue requests so no then needed
2017-05-08 17:10:18 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 928 verify failed
ok 929 constructor called once
ok 930 constructor called with right args
ok 931 start before stop
# teardown
# setup
# test calculateSeqPointKeyId
ok 932 should be equal
ok 933 should be equal
# teardown
# setup
# #_doImmediateSeqUpdate - server is not there
2017-05-08 17:10:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:10:18 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
ok 934 Got right error
# teardown
2017-05-08 17:10:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - server accepts & closes connection
2017-05-08 17:10:18 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
ok 935 Got socket hang up
# teardown
2017-05-08 17:10:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - server always returns 500
2017-05-08 17:10:18 - DEBUG localSeqManager: 'Got an error trying to update seq []'
ok 936 Got 500 as expected
# teardown
2017-05-08 17:10:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - create new seq doc
ok 937 should be equal
ok 938 revs are equal
# teardown
2017-05-08 17:10:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - doc exists, need to get rev and update
ok 939 should be equal
ok 940 revs are equal
# teardown
2017-05-08 17:10:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - update seq three times
ok 941 should be equal
ok 942 revs are equal
ok 943 should be equal
ok 944 revs are equal
ok 945 should be equal
ok 946 revs are equal
# teardown
2017-05-08 17:10:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - rev got changed under us
2017-05-08 17:10:19 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict"}'
ok 947 Our rev is old so we should fail
# teardown
2017-05-08 17:10:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - fail if stop is called
ok 948 confirm stop caused failure
# teardown
2017-05-08 17:10:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - stop after get but before put fails right
2017-05-08 17:10:19 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
ok 949 stop caused us to fail
ok 950 We specifically failed on a stop before put
# teardown
2017-05-08 17:10:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - fail if stop is called
ok 951 failed due to stop
ok 952 failed due to stop
# teardown
2017-05-08 17:10:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - set seq for first time
ok 953 should be equal
# teardown
2017-05-08 17:10:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - Fail on bad seq value
2017-05-08 17:10:19 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
ok 954 Expected bad seq error
# teardown
2017-05-08 17:10:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - do we cancel timer properly on an immediate?
ok 955 Different promises
ok 956 Timer was cancelled
ok 957 should be equal
# teardown
2017-05-08 17:10:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - do we wait for blocked update
ok 958 One go and one blocked
ok 959 All blocked
ok 960 Still blocked
ok 961 should be equal
# teardown
2017-05-08 17:10:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - test that we wait long enough
ok 962 We waited long enough
ok 963 should be equal
# teardown
2017-05-08 17:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - test that we pick up new sequences while we wait
ok 964 Should have gotten same timer promise
ok 965 Still same timer promise
ok 966 We waited long enough
ok 967 should be equal
# teardown
2017-05-08 17:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# test thali manager spies
2017-05-08 17:10:36 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
2017-05-08 17:10:36 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
2017-05-08 17:10:36 - DEBUG thaliManager: 'creating express pouchdb instance'
ok 968 expressPouchDB was called once
ok 969 expressPouchDB was called with 2 arguments
ok 970 expressPouchDB was called with 'PouchDB' as 1-st argument
ok 971 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
ok 972 PouchDB was called once
ok 973 PouchDB was called with 1 arguments
ok 974 PouchDB was called with 'dbName' as 1-st argument
ok 975 ThaliSendNotificationBasedOnReplication was called once
ok 976 ThaliSendNotificationBasedOnReplication was called with 4 arguments
ok 977 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
ok 978 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
ok 979 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
ok 980 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
ok 981 ThaliPullReplicationFromNotification was called once
ok 982 ThaliPullReplicationFromNotification was called with 4 arguments
ok 983 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
ok 984 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
ok 985 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
ok 986 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
ok 987 Salti was called once
ok 988 Salti was called with 4 arguments
ok 989 Salti was called with 'dbName' as 1-st argument
ok 990 Salti was called with 'acl' as 2-st argument
ok 991 Salti was called with 'thaliIdCallback' as 3-st argument
ok 992 Salti was called with 'options' as 4-st argument
2017-05-08 17:10:36 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2017-05-08 17:10:36 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2017-05-08 17:10:36 - DEBUG thaliManager: 'starting ThaliMobile'
2017-05-08 17:10:36 - DEBUG thaliManager: 'start listening for advertisements'
2017-05-08 17:10:36 - DEBUG thaliManager: 'start update advertising and listening'
2017-05-08 17:10:36 - DEBUG thaliWifiInfrastructure: 'listening 50312'
2017-05-08 17:10:36 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
ok 993 ThaliMobile.start was called once
ok 994 ThaliMobile.start was called with 3 arguments
ok 995 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
ok 996 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
ok 997 ThaliMobile.start was called with 'networkType' as 3-st argument
ok 998 ThaliMobile.startListeningForAdvertisements was called once
ok 999 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
ok 1000 ThaliMobile.startUpdateAdvertisingAndListening was called once
ok 1001 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
ok 1002 ThaliSendNotificationBasedOnReplication.prototype.start was called once
ok 1003 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
ok 1004 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
ok 1005 ThaliPullReplicationFromNotification.prototype.start was called once
ok 1006 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
ok 1007 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
2017-05-08 17:10:36 - DEBUG thaliManager: 'stopping everything'
2017-05-08 17:10:36 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"WIFI"}})'
2017-05-08 17:10:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-05-08 17:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:10:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 1008 ThaliMobile.stop was called once
ok 1009 ThaliMobile.stop was called with 0 arguments
ok 1010 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
ok 1011 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
ok 1012 ThaliPullReplicationFromNotification.prototype.stop was called once
ok 1013 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
# teardown
# setup
# test thali manager multiple starts and stops
2017-05-08 17:10:36 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
2017-05-08 17:10:36 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
2017-05-08 17:10:36 - DEBUG thaliManager: 'creating express pouchdb instance'
ok 1014 expressPouchDB was called once
ok 1015 expressPouchDB was called with 2 arguments
ok 1016 expressPouchDB was called with 'PouchDB' as 1-st argument
ok 1017 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
ok 1018 PouchDB was called once
ok 1019 PouchDB was called with 1 arguments
ok 1020 PouchDB was called with 'dbName' as 1-st argument
ok 1021 ThaliSendNotificationBasedOnReplication was called once
ok 1022 ThaliSendNotificationBasedOnReplication was called with 4 arguments
ok 1023 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
ok 1024 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
ok 1025 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
ok 1026 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
ok 1027 ThaliPullReplicationFromNotification was called once
ok 1028 ThaliPullReplicationFromNotification was called with 4 arguments
ok 1029 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
ok 1030 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
ok 1031 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
ok 1032 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
ok 1033 Salti was called once
ok 1034 Salti was called with 4 arguments
ok 1035 Salti was called with 'dbName' as 1-st argument
ok 1036 Salti was called with 'acl' as 2-st argument
ok 1037 Salti was called with 'thaliIdCallback' as 3-st argument
ok 1038 Salti was called with 'options' as 4-st argument
2017-05-08 17:10:36 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2017-05-08 17:10:36 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2017-05-08 17:10:36 - DEBUG thaliManager: 'starting ThaliMobile'
2017-05-08 17:10:36 - DEBUG thaliManager: 'start listening for advertisements'
2017-05-08 17:10:36 - DEBUG thaliManager: 'start update advertising and listening'
2017-05-08 17:10:36 - DEBUG thaliWifiInfrastructure: 'listening 50313'
2017-05-08 17:10:36 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
ok 1039 ThaliMobile.start was called once
ok 1040 ThaliMobile.start was called with 3 arguments
ok 1041 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
ok 1042 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
ok 1043 ThaliMobile.start was called with 'networkType' as 3-st argument
ok 1044 ThaliMobile.startListeningForAdvertisements was called once
ok 1045 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
ok 1046 ThaliMobile.startUpdateAdvertisingAndListening was called once
ok 1047 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
ok 1048 ThaliSendNotificationBasedOnReplication.prototype.start was called once
ok 1049 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
ok 1050 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
ok 1051 ThaliPullReplicationFromNotification.prototype.start was called once
ok 1052 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
ok 1053 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
2017-05-08 17:10:36 - DEBUG thaliManager: 'stopping everything'
2017-05-08 17:10:36 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"WIFI"}})'
2017-05-08 17:10:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-05-08 17:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:10:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 1054 ThaliMobile.stop was called once
ok 1055 ThaliMobile.stop was called with 0 arguments
ok 1056 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
ok 1057 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
ok 1058 ThaliPullReplicationFromNotification.prototype.stop was called once
ok 1059 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
2017-05-08 17:10:36 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2017-05-08 17:10:36 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2017-05-08 17:10:36 - DEBUG thaliManager: 'starting ThaliMobile'
2017-05-08 17:10:36 - DEBUG thaliManager: 'start listening for advertisements'
2017-05-08 17:10:36 - DEBUG thaliManager: 'start update advertising and listening'
2017-05-08 17:10:36 - DEBUG thaliWifiInfrastructure: 'listening 50314'
2017-05-08 17:10:36 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
2017-05-08 17:10:36 - DEBUG thaliManager: 'stopping everything'
2017-05-08 17:10:36 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"WIFI"}})'
2017-05-08 17:10:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-05-08 17:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:10:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-05-08 17:10:36 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2017-05-08 17:10:36 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2017-05-08 17:10:36 - DEBUG thaliManager: 'starting ThaliMobile'
2017-05-08 17:10:36 - DEBUG thaliManager: 'start listening for advertisements'
2017-05-08 17:10:36 - DEBUG thaliManager: 'start update advertising and listening'
2017-05-08 17:10:36 - DEBUG thaliWifiInfrastructure: 'listening 50315'
2017-05-08 17:10:36 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
2017-05-08 17:10:36 - DEBUG thaliManager: 'stopping everything'
2017-05-08 17:10:36 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"WIFI"}})'
2017-05-08 17:10:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-05-08 17:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:10:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-05-08 17:10:36 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2017-05-08 17:10:36 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2017-05-08 17:10:36 - DEBUG thaliManager: 'starting ThaliMobile'
2017-05-08 17:10:36 - DEBUG thaliManager: 'start listening for advertisements'
2017-05-08 17:10:36 - DEBUG thaliManager: 'start update advertising and listening'
2017-05-08 17:10:36 - DEBUG thaliWifiInfrastructure: 'listening 50316'
2017-05-08 17:10:36 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
ok 1060 ThaliMobile.start was called once
ok 1061 ThaliMobile.start was called with 3 arguments
ok 1062 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
ok 1063 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
ok 1064 ThaliMobile.start was called with 'networkType' as 3-st argument
ok 1065 ThaliMobile.startListeningForAdvertisements was called once
ok 1066 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
ok 1067 ThaliMobile.startUpdateAdvertisingAndListening was called once
ok 1068 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
ok 1069 ThaliSendNotificationBasedOnReplication.prototype.start was called once
ok 1070 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
ok 1071 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
ok 1072 ThaliPullReplicationFromNotification.prototype.start was called once
ok 1073 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
ok 1074 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
2017-05-08 17:10:36 - DEBUG thaliManager: 'stopping everything'
2017-05-08 17:10:36 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"WIFI"}})'
2017-05-08 17:10:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-05-08 17:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-05-08 17:10:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
# teardown
# setup
# Single local http request
listening on 50317
ok 1075 should be equal
# teardown
2017-05-08 17:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Single coordinated request ios native
2017-05-08 17:10:51 - DEBUG SimpleThaliTape: 'test was skipped, name: 'Single coordinated request ios native''
# teardown
2017-05-08 17:10:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
not ok 1076 httpServer had stop err Error: Not running
  ---
    operator: fail
    at: Array.1 (/Users/thali/Github/Thali_CordovaPlugin/thali/node_modules/lie/lib/index.js:88:21)
  ...
2017-05-08 17:11:06 - ERROR SimpleThaliTape: 'test failed, name: 'Single coordinated request ios native''
# setup
# Multiple local http requests
listening on 50319
ok 1077 should be equal
ok 1078 should be equal
ok 1079 should be equal
# teardown
2017-05-08 17:11:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Multiple coordinated request ios native
2017-05-08 17:11:21 - DEBUG SimpleThaliTape: 'test was skipped, name: 'Multiple coordinated request ios native''
# teardown
2017-05-08 17:11:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
not ok 1080 httpServer had stop err Error: Not running
  ---
    operator: fail
    at: Array.1 (/Users/thali/Github/Thali_CordovaPlugin/thali/node_modules/lie/lib/index.js:88:21)
  ...
2017-05-08 17:11:36 - ERROR SimpleThaliTape: 'test failed, name: 'Multiple coordinated request ios native''
# setup
# ssdp server and client should be restarted when wifi toggled
ok 1081 should be in started state
2017-05-08 17:11:36 - DEBUG thaliWifiInfrastructure: 'listening 50323'
ok 1082 server start should be called once
ok 1083 server stop should not be called
ok 1084 client start should be called once
ok 1085 client stop should not be called
2017-05-08 17:11:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-05-08 17:11:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
ok 1086 server start should be called twice
ok 1087 server stop should be called once
ok 1088 client start should be called twice
ok 1089 client stop should be called once
2017-05-08 17:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 1090 server stop should be called twice
ok 1091 client stop should be called twice
ok 1092 should not be in started state
# teardown
# setup
# ssdp server and client should be restarted when bssid changed
2017-05-08 17:11:37 - DEBUG thaliWifiInfrastructure: 'listening 50324'
2017-05-08 17:11:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-05-08 17:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 1093 server start called 0 times
ok 1094 server stop called 1 times
ok 1095 client start called 0 times
ok 1096 client stop called 1 times
2017-05-08 17:11:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-05-08 17:11:37 - DEBUG thaliWifiInfrastructure: 'listening 50325'
ok 1097 server start called 1 times
ok 1098 server stop called 0 times
ok 1099 client start called 1 times
ok 1100 client stop called 0 times
2017-05-08 17:11:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
ok 1101 server start called 1 times
ok 1102 server stop called 1 times
ok 1103 client start called 1 times
ok 1104 client stop called 1 times
ok 1105 server stop called before start
ok 1106 client stop called before start
2017-05-08 17:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 1107 should not be in started state
# teardown
# setup
# ssdp server and client should be restarted only when advertising/listening is active
2017-05-08 17:11:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
ok 1108 server start called 0 times
ok 1109 server stop called 0 times
ok 1110 client start called 0 times
ok 1111 client stop called 0 times
2017-05-08 17:11:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
ok 1112 server start called 0 times
ok 1113 server stop called 0 times
ok 1114 client start called 0 times
ok 1115 client stop called 0 times
2017-05-08 17:11:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
ok 1116 server start called 0 times
ok 1117 server stop called 0 times
ok 1118 client start called 0 times
ok 1119 client stop called 0 times
ok 1120 should not be in started state
# teardown
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - closeAll with promise'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - closeAll works even with a server that is not listening yet witheatNotRunning set to true'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - enqueue and run in order'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - queues handled independently'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - basic'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - another'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - test sinon sansbox spy'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - test sinon sansbox stub'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - test sinon sansbox mock'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - emits incomingConnectionState'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - native server connections all up'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - calling createPeerListener without calling start produces error'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - calling createPeerListener after calling stop produces error'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - can call createPeerListener'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - calling createPeerListener twice with same peerIdentifier should return the same port'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - createPeerListener - closing connection to native listener closes everything and triggers new listener'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - createPeerListener - closing mux closes listener and triggers a new listener'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - peerListener - no native server'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - peerListener - with native server'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - peerListener - with native server and data transfer'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - createPeerListener is idempotent'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - createPeerListener - ask for new peer when we are at maximum and make sure we remove the right existing listener'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - createPeerListener - ask for a new peer when we are not at maximum peers and make sure we do not remove any existing listeners'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - createPeerListener - test timeout'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - createPeerListener - multiple connections out'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - createPeerListener - multiple bi-directional connections'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - createPeerListener - multiple parallel calls'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - createPeerListener - we shouldn't create a dead pipe'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - can create servers manager'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - calling stop without start causes error'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - can start/stop servers manager'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - After #startListeningForAdvertisements call should listen to SSDP advertisements and emit wifiPeerAvailabilityChanged events'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening correctly updates USN'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening generates new peerIdentifier after #stopAdvertisingAndListening has been called'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening sends correct requests'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - messages with invalid location or USN should be ignored'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Delayed own message are still ignored after advertisement has been toggled on and off several times'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - verify that Thali-specific messages are filtered correctly'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #start should fail if called twice in a row'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - should not be started after stop is called'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail invalid router has been passed'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if router server starting fails'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should start hosting given router object'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening bad psk should be rejected object'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #stop can be called multiple times in a row'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #startListeningForAdvertisements can be called multiple times in a row'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #stopListeningForAdvertisements can be called multiple times in a row'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #stopAdvertisingAndListening can be called multiple times in a row'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - calls correct starts when network changes'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - does not get peer changes from self'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Make sure we turn on and off the Android multicast locks'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - Make sure we do not use Android locks when we are not on Android'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - functions are run from a queue in the right order'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Discovered peer should be removed if no availability updates were received during availability timeout'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #stop should clear watchers'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - wifi peer is marked unavailable if announcements stop'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - network changes are ignored while stopping'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #startListeningForAdvertisements returns error if wifi is off and fires event when on'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening returns error if wifi is off and fires event when on'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - when wifi is enabled discovery is activated and peers become available'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - SSDP server should not restart after Wifi Client changed generation'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - startUpdateAdvertisingAndListening does not send ssdp:byebye notifications'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #start - Causing native or wifi to fail will cause a promise reject '
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #start should fail if called twice in a row'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - does not emit duplicate discoveryAdvertisingStateUpdate'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - does not send duplicate availability changes'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - can get the network status'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (native)'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (wifi)'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - native available - new peer is cached'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - native available - peer with same port and different generation is cached (BLUETOOTH)'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - native available - peer with greater generation is cached (MPCF)'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - native available - peer with same or older generation is ignored (MPCF)'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - native unavailable - new peer is ignored'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - native unavailable - cached peer is removed'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for wifi peers'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - multiconnect failure - new peer is ignored (MPCF)'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - newAddressPort field (TCP_NATIVE)'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - newAddressPort field (BLUETOOTH)'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - newAddressPort field (MPCF)'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #getPeerHostInfo - error when peer has not been discovered yet'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached wifi peer'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #disconnect fails on wifi peers'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - #disconnect delegates native peers to the native wrapper'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - network changes emitted correctly'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - network changes not emitted in started state'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - network changes not emitted in stopped state'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on Android'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on iOS'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - does not fire duplicate events after peer listener recreation'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #stop should change peers'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #testThaliPeerAction - test getters'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #testThaliPeerAction - start and kill'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #testThaliPeerAction - double start'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #testThaliPeerAction - start after kill'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #testThaliPeerAction - make sure ids are unique'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #testThaliPeerAction - check that forever agent can be destroyed'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Test PeerDictionary basic functionality'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Test PeerDictionary with multiple entries.'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - RESOLVED entries are removed before WAITING state entry.'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - WAITING entries are removed before CONTROLLED_BY_POOL state entry.'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - When CONTROLLED_BY_POOL entry is removed and kill is called.'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - single action'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - multiple actions'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - PSK Pool works'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - stop'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that start verifies queue length'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - bad enqueues'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - do not allow same object type'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure we catch kill and dequeue'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that stop removes all actions'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - We reject unrecognized connection type'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - We reject unrecognized action type'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - One action on bluetooth'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - Two notification actions'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - replicateThroughProblems'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - Replication goes first'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - wifi allows many parallel non-replication actions'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - wifi allows no more than 2 simultaneous replication actions for same peerID'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Test BEACONS_RETRIEVED_AND_PARSED locally'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Test HTTP_BAD_RESPONSE locally'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Test NETWORK_PROBLEM locally'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Action fails when getPeerHostInfo fails'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Call the start two times'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Call the kill before calling the start'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Call the kill immediately after the start'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Call the kill while waiting a response from the server'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Test to exceed the max content size locally'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Close the server socket while the client is waiting a response from the server. Local test.'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Close the client socket while the client is waiting a response from the server. Local test.'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons bad args'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons empty keys to notify'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons multiple keys to notify'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #parseBeacons invalid expiration in beaconStreamWithPreAmble'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #parseBeacons no beacons returns null'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback fails decrypt'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns no matches'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns spurious match'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns public key'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - validate generatePskIdentityField'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - validate generatePskSecret'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - validate generatePskSecrets'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - validate generateBeaconStreamAndSecrets'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Add two Peers.'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - TCP_NATIVE peer loses DNS'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Received beacons with no values for us'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Notification action killed with a superseded'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Resolves an action locally'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Resolves an action locally using ThaliPeerPoolDefault'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Action fails because of a bad hostname.'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - hostaddress is removed when the action is running. '
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - notificationClient does not retry action with BAD_PEER resolution'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - notification client correctly handles peer availability changes of the same peer'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Client to server request locally'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Test ThaliPskMapCache clean and expiration'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Test ThaliPskMapCache getSecret and getPublic'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Test ThaliPskMapCache multiple entries'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Start and stop ThaliNotificationServer'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Pass an empty array to ThaliNotificationServer.start'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Pass a string to ThaliNotificationServer.start'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Pass an empty parameter to ThaliNotificationServer.start'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons (no keys)'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeaconsbefore calling start'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Make sure peerDictionaryKey is reasonable'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Make sure start works'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Make sure stop works'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Simple peer event'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Server is not there'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Server accepts & closes connection'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Server always returns 500'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Server always returns 401'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Server always returns 403'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Make sure docs replicate'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Do nothing and make sure we time out'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Do something and make sure we time out'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Start replicating and then catch error when server goes'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Make sure clone works'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - compareBufferArrays'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Call start twice and get error'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Start and make sure it runs'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Make sure getTimeWhenRun is right after start'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Make sure getTimeWhenRun is -1 after function is called'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Test TransientState'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - No peers and empty database'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - One peer and empty DB'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - One peer with _Local set behind current seq'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - One peer with _Local set equal to current seq'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - One peer with _Local set ahead of current seq (and no this should not happen)'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Three peers, one not in DB, one behind and one ahead'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - More than maximum peers, make sure we only send maximum allowed'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - two peers with empty DB, update the doc'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - add doc and make sure tokens refresh when they expire'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - start and stop and start and stop'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - two identical starts in a row'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - two different starts in a row'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - two stops and a start and two stops'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - we properly enqueue requests so no then needed'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - test calculateSeqPointKeyId'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - server is not there'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - server accepts & closes connection'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - server always returns 500'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - create new seq doc'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - doc exists, need to get rev and update'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - update seq three times'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - rev got changed under us'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - fail if stop is called'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - stop after get but before put fails right'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #update - fail if stop is called'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #update - set seq for first time'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #update - Fail on bad seq value'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #update - do we cancel timer properly on an immediate?'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #update - do we wait for blocked update'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #update - test that we wait long enough'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - #update - test that we pick up new sequences while we wait'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - test thali manager spies'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - test thali manager multiple starts and stops'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Single local http request'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - Single coordinated request ios native'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - Multiple local http requests'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: skipped - Multiple coordinated request ios native'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - ssdp server and client should be restarted when wifi toggled'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - ssdp server and client should be restarted when bssid changed'
2017-05-08 17:11:38 - INFO SimpleThaliTape: '***TEST_LOGGER result: passed - ssdp server and client should be restarted only when advertising/listening is active'
2017-05-08 17:11:38 - DEBUG SimpleThaliTape: 'all unit tests succeeded, platformName: 'android''
2017-05-08 17:11:38 - DEBUG SimpleThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'
2017-05-08 17:11:38 - INFO runTests: 'Finished'

1..1120
# tests 1120
# pass  1118
# fail  2


[0;31merror: command 'jx runTests.js --networkType WIFI' failed with code 1, file 'build.sh' on line 62[0m
./build.sh CI FAILED - build.sh failure[0m

npm WARN thali-test-server@0.0.1 No repository field.
npm WARN thali-test-server@0.0.1 No license field.
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/javascript-state-machine
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-leveldb-core
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/javascript-state-machine
npm http 304 http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/lie
npm http 200 http://192.168.1.100:4873/body-parser
npm http 200 http://192.168.1.100:4873/ip
npm http 304 http://192.168.1.100:4873/winston
npm http 304 http://192.168.1.100:4873/long
npm http 200 http://192.168.1.100:4873/uuid
npm http 304 http://192.168.1.100:4873/multiplex
npm http 304 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/pouchdb-adapter-leveldb-core
npm http 200 http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/http-errors
npm http 200 http://192.168.1.100:4873/bytes
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/type-is
npm http 304 http://192.168.1.100:4873/raw-body
npm http 200 http://192.168.1.100:4873/iconv-lite
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
npm http request GET http://192.168.1.100:4873/parseurl
npm http request GET http://192.168.1.100:4873/path-to-regexp
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/proxy-addr
npm http request GET http://192.168.1.100:4873/range-parser
npm http request GET http://192.168.1.100:4873/send
npm http request GET http://192.168.1.100:4873/utils-merge
npm http request GET http://192.168.1.100:4873/vary
npm http request GET http://192.168.1.100:4873/serve-static
npm http 304 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/send
npm http 304 http://192.168.1.100:4873/utils-merge
npm http 304 http://192.168.1.100:4873/vary
npm http 304 http://192.168.1.100:4873/serve-static
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
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/xtend
npm http 200 http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/duplexify
npm http 304 http://192.168.1.100:4873/varint
npm http 200 http://192.168.1.100:4873/xtend
npm http fetch GET http://192.168.1.100:4873/readable-stream/-/readable-stream-2.2.9.tgz
npm http fetch 200 http://192.168.1.100:4873/readable-stream/-/readable-stream-2.2.9.tgz
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
npm http 304 http://192.168.1.100:4873/process-nextick-args
npm http 304 http://192.168.1.100:4873/buffer-shims
npm http 200 http://192.168.1.100:4873/string_decoder
npm http 200 http://192.168.1.100:4873/core-util-is
npm http 304 http://192.168.1.100:4873/util-deprecate
npm http fetch GET http://192.168.1.100:4873/string_decoder/-/string_decoder-1.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/string_decoder/-/string_decoder-1.0.0.tgz
npm http request GET http://192.168.1.100:4873/argsarray
npm http request GET http://192.168.1.100:4873/buffer-from
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/pouchdb-binary-utils
npm http request GET http://192.168.1.100:4873/pouchdb-json
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-utils
npm http request GET http://192.168.1.100:4873/pouchdb-errors
npm http request GET http://192.168.1.100:4873/pouchdb-md5
npm http request GET http://192.168.1.100:4873/pouchdb-merge
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/pouchdb-utils
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http 200 http://192.168.1.100:4873/argsarray
npm http 304 http://192.168.1.100:4873/buffer-from
npm http 304 http://192.168.1.100:4873/double-ended-queue
npm http 200 http://192.168.1.100:4873/pouchdb-binary-utils
npm http 200 http://192.168.1.100:4873/levelup
npm http 200 http://192.168.1.100:4873/pouchdb-json
npm http 200 http://192.168.1.100:4873/pouchdb-collections
npm http 200 http://192.168.1.100:4873/pouchdb-adapter-utils
npm http 200 http://192.168.1.100:4873/pouchdb-errors
npm http 200 http://192.168.1.100:4873/pouchdb-md5
npm http 200 http://192.168.1.100:4873/pouchdb-merge
npm http 200 http://192.168.1.100:4873/pouchdb-promise
npm http 200 http://192.168.1.100:4873/sublevel-pouchdb
npm http 200 http://192.168.1.100:4873/pouchdb-utils
npm http 200 http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/is-array-buffer-x
npm http 200 http://192.168.1.100:4873/is-array-buffer-x
npm http fetch GET http://192.168.1.100:4873/is-array-buffer-x/-/is-array-buffer-x-1.2.1.tgz
npm http fetch 200 http://192.168.1.100:4873/is-array-buffer-x/-/is-array-buffer-x-1.2.1.tgz
npm http request GET http://192.168.1.100:4873/is-object-like-x
npm http request GET http://192.168.1.100:4873/to-string-tag-x
npm http request GET http://192.168.1.100:4873/has-to-string-tag-x
npm http 200 http://192.168.1.100:4873/is-object-like-x
npm http 200 http://192.168.1.100:4873/has-to-string-tag-x
npm http 200 http://192.168.1.100:4873/to-string-tag-x
npm http fetch GET http://192.168.1.100:4873/is-object-like-x/-/is-object-like-x-1.2.0.tgz
npm http fetch GET http://192.168.1.100:4873/has-to-string-tag-x/-/has-to-string-tag-x-1.2.0.tgz
npm http fetch GET http://192.168.1.100:4873/to-string-tag-x/-/to-string-tag-x-1.2.0.tgz
npm http fetch 200 http://192.168.1.100:4873/is-object-like-x/-/is-object-like-x-1.2.0.tgz
npm http fetch 200 http://192.168.1.100:4873/has-to-string-tag-x/-/has-to-string-tag-x-1.2.0.tgz
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
npm http 304 http://192.168.1.100:4873/lodash.isnull
npm http 304 http://192.168.1.100:4873/validate.io-undefined
npm http request GET http://192.168.1.100:4873/level-errors
npm http request GET http://192.168.1.100:4873/prr
npm http request GET http://192.168.1.100:4873/deferred-leveldown
npm http request GET http://192.168.1.100:4873/level-codec
npm http request GET http://192.168.1.100:4873/level-iterator-stream
npm http request GET http://192.168.1.100:4873/semver
npm http 304 http://192.168.1.100:4873/level-errors
npm http 304 http://192.168.1.100:4873/deferred-leveldown
npm http 304 http://192.168.1.100:4873/level-iterator-stream
npm http 200 http://192.168.1.100:4873/semver
npm http 304 http://192.168.1.100:4873/level-codec
npm http 304 http://192.168.1.100:4873/prr
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http 304 http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/errno
npm http 304 http://192.168.1.100:4873/errno
npm http request GET http://192.168.1.100:4873/spark-md5
npm http 304 http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/clone-buffer
npm http 200 http://192.168.1.100:4873/clone-buffer
npm http request GET http://192.168.1.100:4873/vuvuzela
npm http 304 http://192.168.1.100:4873/vuvuzela
npm http request GET http://192.168.1.100:4873/ltgt
npm http 200 http://192.168.1.100:4873/ltgt
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/caseless
npm http 200 http://192.168.1.100:4873/form-data
npm http 200 http://192.168.1.100:4873/extend
npm http fetch GET http://192.168.1.100:4873/extend/-/extend-3.0.1.tgz
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/tunnel-agent
npm http 200 http://192.168.1.100:4873/bl
npm http 200 http://192.168.1.100:4873/tough-cookie
npm WARN deprecated node-uuid@1.4.8: Use uuid module instead
npm http fetch GET http://192.168.1.100:4873/node-uuid/-/node-uuid-1.4.8.tgz
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 200 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/stringstream
npm http fetch 200 http://192.168.1.100:4873/extend/-/extend-3.0.1.tgz
npm http fetch 200 http://192.168.1.100:4873/node-uuid/-/node-uuid-1.4.8.tgz
npm http 200 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/hawk
npm http 200 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 200 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http fetch GET http://192.168.1.100:4873/async/-/async-2.4.0.tgz
npm http fetch 200 http://192.168.1.100:4873/async/-/async-2.4.0.tgz
npm http request GET http://192.168.1.100:4873/lodash
npm http 200 http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/is-my-json-valid
npm http 200 http://192.168.1.100:4873/chalk
npm http 200 http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http 200 http://192.168.1.100:4873/ansi-styles
npm http 200 http://192.168.1.100:4873/has-ansi
npm http 200 http://192.168.1.100:4873/escape-string-regexp
npm http 200 http://192.168.1.100:4873/supports-color
npm http 200 http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 200 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http 304 http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http 304 http://192.168.1.100:4873/generate-function
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http request GET http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/boom
npm http 200 http://192.168.1.100:4873/sntp
npm http 200 http://192.168.1.100:4873/cryptiles
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
npm http request GET http://192.168.1.100:4873/stack-trace
npm http request GET http://192.168.1.100:4873/pkginfo
npm http 304 http://192.168.1.100:4873/colors
npm http 304 http://192.168.1.100:4873/cycle
npm http 304 http://192.168.1.100:4873/stack-trace
npm http 304 http://192.168.1.100:4873/pkginfo
npm http 304 http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/jsdoc
npm http request GET http://192.168.1.100:4873/eslint
npm http 200 http://192.168.1.100:4873/jsdoc
npm http 200 http://192.168.1.100:4873/eslint
npm http request GET http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/babel-code-frame
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/doctrine
npm http request GET http://192.168.1.100:4873/escope
npm http request GET http://192.168.1.100:4873/espree
npm http request GET http://192.168.1.100:4873/estraverse
npm http request GET http://192.168.1.100:4873/file-entry-cache
npm http request GET http://192.168.1.100:4873/ignore
npm http request GET http://192.168.1.100:4873/imurmurhash
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/globals
npm http request GET http://192.168.1.100:4873/is-resolvable
npm http request GET http://192.168.1.100:4873/json-stable-stringify
npm http request GET http://192.168.1.100:4873/inquirer
npm http request GET http://192.168.1.100:4873/levn
npm http request GET http://192.168.1.100:4873/natural-compare
npm http request GET http://192.168.1.100:4873/js-yaml
npm http request GET http://192.168.1.100:4873/optionator
npm http request GET http://192.168.1.100:4873/path-is-inside
npm http request GET http://192.168.1.100:4873/progress
npm http request GET http://192.168.1.100:4873/pluralize
npm http request GET http://192.168.1.100:4873/esutils
npm http request GET http://192.168.1.100:4873/require-uncached
npm http request GET http://192.168.1.100:4873/shelljs
npm http request GET http://192.168.1.100:4873/strip-bom
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/table
npm http request GET http://192.168.1.100:4873/text-table
npm http request GET http://192.168.1.100:4873/user-home
npm http 304 http://192.168.1.100:4873/doctrine
npm http 304 http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/concat-stream
npm http 200 http://192.168.1.100:4873/escope
npm http 200 http://192.168.1.100:4873/babel-code-frame
npm http 304 http://192.168.1.100:4873/file-entry-cache
npm http 304 http://192.168.1.100:4873/estraverse
npm http 200 http://192.168.1.100:4873/espree
npm http 304 http://192.168.1.100:4873/imurmurhash
npm http 200 http://192.168.1.100:4873/ignore
npm http 200 http://192.168.1.100:4873/mkdirp
npm http 304 http://192.168.1.100:4873/is-resolvable
npm http fetch GET http://192.168.1.100:4873/espree/-/espree-3.4.3.tgz
npm http 200 http://192.168.1.100:4873/json-stable-stringify
npm http fetch GET http://192.168.1.100:4873/ignore/-/ignore-3.3.0.tgz
npm http 200 http://192.168.1.100:4873/globals
npm http fetch GET http://192.168.1.100:4873/globals/-/globals-9.17.0.tgz
npm http 304 http://192.168.1.100:4873/natural-compare
npm http 200 http://192.168.1.100:4873/inquirer
npm http 200 http://192.168.1.100:4873/levn
npm http 200 http://192.168.1.100:4873/optionator
npm http 200 http://192.168.1.100:4873/js-yaml
npm http 200 http://192.168.1.100:4873/path-is-inside
npm http 304 http://192.168.1.100:4873/esutils
npm http 200 http://192.168.1.100:4873/progress
npm http fetch GET http://192.168.1.100:4873/js-yaml/-/js-yaml-3.8.4.tgz
npm http 200 http://192.168.1.100:4873/require-uncached
npm http 200 http://192.168.1.100:4873/pluralize
npm http 304 http://192.168.1.100:4873/strip-bom
npm http 200 http://192.168.1.100:4873/shelljs
npm http fetch 200 http://192.168.1.100:4873/espree/-/espree-3.4.3.tgz
npm http fetch 200 http://192.168.1.100:4873/ignore/-/ignore-3.3.0.tgz
npm http 200 http://192.168.1.100:4873/strip-json-comments
npm http 200 http://192.168.1.100:4873/text-table
npm http fetch 200 http://192.168.1.100:4873/globals/-/globals-9.17.0.tgz
npm http fetch 200 http://192.168.1.100:4873/js-yaml/-/js-yaml-3.8.4.tgz
npm http 200 http://192.168.1.100:4873/table
npm http 200 http://192.168.1.100:4873/user-home
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
npm http fetch GET http://192.168.1.100:4873/es6-weak-map/-/es6-weak-map-2.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/es6-map/-/es6-map-0.1.5.tgz
npm http fetch 200 http://192.168.1.100:4873/es6-weak-map/-/es6-weak-map-2.0.2.tgz
npm http request GET http://192.168.1.100:4873/d
npm http request GET http://192.168.1.100:4873/es6-symbol
npm http request GET http://192.168.1.100:4873/es6-iterator
npm http request GET http://192.168.1.100:4873/es6-set
npm http request GET http://192.168.1.100:4873/event-emitter
npm http request GET http://192.168.1.100:4873/es5-ext
npm http 200 http://192.168.1.100:4873/d
npm http 200 http://192.168.1.100:4873/es6-symbol
npm http 200 http://192.168.1.100:4873/es6-iterator
npm http 200 http://192.168.1.100:4873/es6-set
npm http 200 http://192.168.1.100:4873/event-emitter
npm http fetch GET http://192.168.1.100:4873/d/-/d-1.0.0.tgz
npm http fetch GET http://192.168.1.100:4873/es6-iterator/-/es6-iterator-2.0.1.tgz
npm http fetch GET http://192.168.1.100:4873/es6-set/-/es6-set-0.1.5.tgz
npm http fetch GET http://192.168.1.100:4873/es6-symbol/-/es6-symbol-3.1.1.tgz
npm http fetch GET http://192.168.1.100:4873/event-emitter/-/event-emitter-0.3.5.tgz
npm http fetch 200 http://192.168.1.100:4873/es6-iterator/-/es6-iterator-2.0.1.tgz
npm http fetch 200 http://192.168.1.100:4873/d/-/d-1.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/es6-set/-/es6-set-0.1.5.tgz
npm http fetch 200 http://192.168.1.100:4873/event-emitter/-/event-emitter-0.3.5.tgz
npm http fetch 200 http://192.168.1.100:4873/es6-symbol/-/es6-symbol-3.1.1.tgz
npm http 200 http://192.168.1.100:4873/es5-ext
npm http fetch GET http://192.168.1.100:4873/es5-ext/-/es5-ext-0.10.15.tgz
npm http fetch 200 http://192.168.1.100:4873/es5-ext/-/es5-ext-0.10.15.tgz
npm http request GET http://192.168.1.100:4873/acorn-jsx
npm http request GET http://192.168.1.100:4873/acorn
npm http 304 http://192.168.1.100:4873/acorn-jsx
npm http 200 http://192.168.1.100:4873/acorn
npm http fetch GET http://192.168.1.100:4873/acorn/-/acorn-5.0.3.tgz
npm http fetch 200 http://192.168.1.100:4873/acorn/-/acorn-5.0.3.tgz
npm http request GET http://192.168.1.100:4873/flat-cache
npm http 200 http://192.168.1.100:4873/flat-cache
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/circular-json
npm http request GET http://192.168.1.100:4873/del
npm http request GET http://192.168.1.100:4873/write
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http 200 http://192.168.1.100:4873/circular-json
npm http 200 http://192.168.1.100:4873/write
npm http 200 http://192.168.1.100:4873/del
npm http request GET http://192.168.1.100:4873/rimraf
npm http request GET http://192.168.1.100:4873/is-path-cwd
npm http request GET http://192.168.1.100:4873/is-path-in-cwd
npm http request GET http://192.168.1.100:4873/pify
npm http request GET http://192.168.1.100:4873/pinkie-promise
npm http request GET http://192.168.1.100:4873/globby
npm http 304 http://192.168.1.100:4873/pinkie-promise
npm http 304 http://192.168.1.100:4873/is-path-cwd
npm http 304 http://192.168.1.100:4873/is-path-in-cwd
npm http 304 http://192.168.1.100:4873/rimraf
npm http 200 http://192.168.1.100:4873/pify
npm http 200 http://192.168.1.100:4873/globby
npm http request GET http://192.168.1.100:4873/arrify
npm http request GET http://192.168.1.100:4873/array-union
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
npm http 304 http://192.168.1.100:4873/is-path-inside
npm http request GET http://192.168.1.100:4873/minimist
npm http 200 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/ansi-escapes
npm http request GET http://192.168.1.100:4873/cli-cursor
npm http request GET http://192.168.1.100:4873/cli-width
npm http request GET http://192.168.1.100:4873/figures
npm http request GET http://192.168.1.100:4873/readline2
npm http request GET http://192.168.1.100:4873/run-async
npm http request GET http://192.168.1.100:4873/rx-lite
npm http request GET http://192.168.1.100:4873/string-width
npm http request GET http://192.168.1.100:4873/through
npm http 200 http://192.168.1.100:4873/cli-cursor
npm http 304 http://192.168.1.100:4873/figures
npm http 304 http://192.168.1.100:4873/cli-width
npm http 200 http://192.168.1.100:4873/ansi-escapes
npm http 304 http://192.168.1.100:4873/readline2
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
npm http request GET http://192.168.1.100:4873/is-fullwidth-code-point
npm http request GET http://192.168.1.100:4873/code-point-at
npm http request GET http://192.168.1.100:4873/mute-stream
npm http 304 http://192.168.1.100:4873/is-fullwidth-code-point
npm http 304 http://192.168.1.100:4873/mute-stream
npm http 304 http://192.168.1.100:4873/code-point-at
npm http request GET http://192.168.1.100:4873/number-is-nan
npm http 200 http://192.168.1.100:4873/number-is-nan
npm http request GET http://192.168.1.100:4873/tryit
npm http 304 http://192.168.1.100:4873/tryit
npm http request GET http://192.168.1.100:4873/argparse
npm http request GET http://192.168.1.100:4873/esprima
npm http 200 http://192.168.1.100:4873/esprima
npm http 200 http://192.168.1.100:4873/argparse
npm http request GET http://192.168.1.100:4873/sprintf-js
npm http 200 http://192.168.1.100:4873/sprintf-js
npm http request GET http://192.168.1.100:4873/jsonify
npm http 304 http://192.168.1.100:4873/jsonify
npm http request GET http://192.168.1.100:4873/prelude-ls
npm http request GET http://192.168.1.100:4873/type-check
npm http 304 http://192.168.1.100:4873/type-check
npm http 304 http://192.168.1.100:4873/prelude-ls
npm http request GET http://192.168.1.100:4873/deep-is
npm http request GET http://192.168.1.100:4873/wordwrap
npm http request GET http://192.168.1.100:4873/fast-levenshtein
npm http 304 http://192.168.1.100:4873/deep-is
npm http 200 http://192.168.1.100:4873/wordwrap
npm http 200 http://192.168.1.100:4873/fast-levenshtein
npm http request GET http://192.168.1.100:4873/resolve-from
npm http request GET http://192.168.1.100:4873/caller-path
npm http 304 http://192.168.1.100:4873/caller-path
npm http 200 http://192.168.1.100:4873/resolve-from
npm http request GET http://192.168.1.100:4873/callsites
npm http 304 http://192.168.1.100:4873/callsites
npm http request GET http://192.168.1.100:4873/interpret
npm http request GET http://192.168.1.100:4873/rechoir
npm http 304 http://192.168.1.100:4873/rechoir
npm http 200 http://192.168.1.100:4873/interpret
npm http fetch GET http://192.168.1.100:4873/interpret/-/interpret-1.0.3.tgz
npm http fetch 200 http://192.168.1.100:4873/interpret/-/interpret-1.0.3.tgz
npm http request GET http://192.168.1.100:4873/resolve
npm http 200 http://192.168.1.100:4873/resolve
npm http fetch GET http://192.168.1.100:4873/resolve/-/resolve-1.3.3.tgz
npm http fetch 200 http://192.168.1.100:4873/resolve/-/resolve-1.3.3.tgz
npm http request GET http://192.168.1.100:4873/path-parse
npm http 200 http://192.168.1.100:4873/path-parse
npm http request GET http://192.168.1.100:4873/ajv-keywords
npm http request GET http://192.168.1.100:4873/ajv
npm http request GET http://192.168.1.100:4873/slice-ansi
npm http 200 http://192.168.1.100:4873/ajv-keywords
npm http 304 http://192.168.1.100:4873/slice-ansi
npm http 200 http://192.168.1.100:4873/ajv
npm http fetch GET http://192.168.1.100:4873/ajv/-/ajv-4.11.8.tgz
npm http fetch 200 http://192.168.1.100:4873/ajv/-/ajv-4.11.8.tgz
npm http request GET http://192.168.1.100:4873/co
npm http 200 http://192.168.1.100:4873/co
npm http request GET http://192.168.1.100:4873/os-homedir
npm http 304 http://192.168.1.100:4873/os-homedir
npm http request GET http://192.168.1.100:4873/catharsis
npm http request GET http://192.168.1.100:4873/js2xmlparser
npm http request GET http://192.168.1.100:4873/requizzle
npm http request GET http://192.168.1.100:4873/marked
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/wrench
npm http request GET http://192.168.1.100:4873/underscore
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 304 http://192.168.1.100:4873/catharsis
npm http 200 http://192.168.1.100:4873/js2xmlparser
npm http 200 http://192.168.1.100:4873/requizzle
npm http 304 http://192.168.1.100:4873/async
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
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/bn.js
npm http request GET http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/express-pouchdb
npm http request GET http://192.168.1.100:4873/leveldown-mobile
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/pouchdb
npm http request GET http://192.168.1.100:4873/proxyquire
npm http request GET http://192.168.1.100:4873/nock
npm http request GET http://192.168.1.100:4873/pouchdb-size
npm http request GET http://192.168.1.100:4873/request-promise
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/tmp
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/stacky
npm http request GET http://192.168.1.100:4873/supertest
npm http request GET http://192.168.1.100:4873/supertest-as-promised
npm http request GET http://192.168.1.100:4873/sinon
npm http request GET http://192.168.1.100:4873/tape-catch
npm http request GET http://192.168.1.100:4873/tape
npm http request GET http://192.168.1.100:4873/uuid-validate
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/child-process-promise
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/minimist
npm http 304 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/multiplex
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/randomstring
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/leveldown-mobile
npm http 304 http://192.168.1.100:4873/socket.io-client
npm http 304 http://192.168.1.100:4873/js-extend
npm http 200 http://192.168.1.100:4873/bn.js
npm http 304 http://192.168.1.100:4873/pouchdb-size
npm http 200 http://192.168.1.100:4873/proxyquire
npm http 200 http://192.168.1.100:4873/express-pouchdb
npm http 304 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/request-promise
npm http 304 http://192.168.1.100:4873/uuid
npm http 304 http://192.168.1.100:4873/stacky
npm http 304 http://192.168.1.100:4873/tape-catch
npm http 200 http://192.168.1.100:4873/tmp
npm http 200 http://192.168.1.100:4873/supertest-as-promised
npm http 200 http://192.168.1.100:4873/supertest
npm http 200 http://192.168.1.100:4873/uuid-validate
npm http 200 http://192.168.1.100:4873/pouchdb
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
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/merge-descriptors
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
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/basic-auth
npm http request GET http://192.168.1.100:4873/compression
npm http request GET http://192.168.1.100:4873/cookie-parser
npm http request GET http://192.168.1.100:4873/header-case-normalizer
npm http request GET http://192.168.1.100:4873/pouchdb-rewrite
npm http request GET http://192.168.1.100:4873/pouchdb-all-dbs
npm http request GET http://192.168.1.100:4873/multiparty
npm http request GET http://192.168.1.100:4873/pouchdb-auth
npm http request GET http://192.168.1.100:4873/pouchdb-list
npm http request GET http://192.168.1.100:4873/pouchdb-replicator
npm http request GET http://192.168.1.100:4873/pouchdb-find
npm http request GET http://192.168.1.100:4873/pouchdb-security
npm http request GET http://192.168.1.100:4873/pouchdb-update
npm http request GET http://192.168.1.100:4873/pouchdb-show
npm http request GET http://192.168.1.100:4873/pouchdb-validation
npm http request GET http://192.168.1.100:4873/pouchdb-vhost
npm http request GET http://192.168.1.100:4873/pouchdb-wrappers
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/header-case-normalizer
npm http 200 http://192.168.1.100:4873/basic-auth
npm http 200 http://192.168.1.100:4873/cookie-parser
npm http 200 http://192.168.1.100:4873/compression
npm http 304 http://192.168.1.100:4873/pouchdb-rewrite
npm http 304 http://192.168.1.100:4873/pouchdb-all-dbs
npm http 304 http://192.168.1.100:4873/pouchdb-auth
npm http 304 http://192.168.1.100:4873/pouchdb-list
npm http 200 http://192.168.1.100:4873/multiparty
npm http 200 http://192.168.1.100:4873/pouchdb-replicator
npm http 304 http://192.168.1.100:4873/pouchdb-update
npm http 200 http://192.168.1.100:4873/pouchdb-security
npm http 304 http://192.168.1.100:4873/pouchdb-show
npm http 200 http://192.168.1.100:4873/pouchdb-find
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
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/argsarray
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/tiny-queue
npm http 304 http://192.168.1.100:4873/es3ify
npm http 304 http://192.168.1.100:4873/argsarray
npm http 304 http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/tiny-queue
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/base62
npm http 304 http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/base64url
npm http request GET http://192.168.1.100:4873/couchdb-calculate-session-id
npm http request GET http://192.168.1.100:4873/crypto-lite
npm http request GET http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http request GET http://192.168.1.100:4873/pouchdb-plugin-error
npm http request GET http://192.168.1.100:4873/pouchdb-system-db
npm http request GET http://192.168.1.100:4873/promise-nodify
npm http request GET http://192.168.1.100:4873/pouchdb-req-http-query
npm http request GET http://192.168.1.100:4873/secure-random
npm http 304 http://192.168.1.100:4873/couchdb-calculate-session-id
npm http 200 http://192.168.1.100:4873/base64url
npm http 304 http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http 304 http://192.168.1.100:4873/crypto-lite
npm http 304 http://192.168.1.100:4873/pouchdb-plugin-error
npm http 304 http://192.168.1.100:4873/pouchdb-system-db
npm http 304 http://192.168.1.100:4873/promise-nodify
npm http 304 http://192.168.1.100:4873/pouchdb-req-http-query
npm http 200 http://192.168.1.100:4873/secure-random
npm http request GET http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/meow
npm http 304 http://192.168.1.100:4873/concat-stream
npm http 200 http://192.168.1.100:4873/meow
npm http request GET http://192.168.1.100:4873/typedarray
npm http 304 http://192.168.1.100:4873/typedarray
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/camelcase-keys
npm http request GET http://192.168.1.100:4873/indent-string
npm http 304 http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/indent-string
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
npm http 304 http://192.168.1.100:4873/is-finite
npm http request GET http://192.168.1.100:4873/number-is-nan
npm http 304 http://192.168.1.100:4873/number-is-nan
npm http request GET http://192.168.1.100:4873/aproba
npm http 200 http://192.168.1.100:4873/aproba
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/vuvuzela
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/level-write-stream
npm http request GET http://192.168.1.100:4873/es6-promise-pool
npm http request GET http://192.168.1.100:4873/localstorage-down
npm http request GET http://192.168.1.100:4873/fruitdown
npm http request GET http://192.168.1.100:4873/pouchdb-collate
npm http request GET http://192.168.1.100:4873/scope-eval
npm http request GET http://192.168.1.100:4873/memdown
npm http 304 http://192.168.1.100:4873/double-ended-queue
npm http 304 http://192.168.1.100:4873/levelup
npm http 304 http://192.168.1.100:4873/spark-md5
npm http 304 http://192.168.1.100:4873/pouchdb-collections
npm http 304 http://192.168.1.100:4873/through2
npm http 304 http://192.168.1.100:4873/sublevel-pouchdb
npm http 304 http://192.168.1.100:4873/vuvuzela
npm http 304 http://192.168.1.100:4873/js-extend
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/level-write-stream
npm http 200 http://192.168.1.100:4873/es6-promise-pool
npm http 304 http://192.168.1.100:4873/fruitdown
npm http 304 http://192.168.1.100:4873/localstorage-down
npm http 200 http://192.168.1.100:4873/pouchdb-collate
npm http 304 http://192.168.1.100:4873/scope-eval
npm http 304 http://192.168.1.100:4873/memdown
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
npm http request GET http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/is-typedarray
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/aws4
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/is-typedarray
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/stringstream
npm WARN deprecated tough-cookie@2.2.2: ReDoS vulnerability parsing Set-Cookie https://nodesecurity.io/advisories/130
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 304 http://192.168.1.100:4873/qs
npm http fetch GET http://192.168.1.100:4873/qs/-/qs-6.1.2.tgz
npm http fetch 200 http://192.168.1.100:4873/qs/-/qs-6.1.2.tgz
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/pinkie-promise
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http 304 http://192.168.1.100:4873/pinkie-promise
npm http 304 http://192.168.1.100:4873/chalk
npm http 304 http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/ansi-styles
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/supports-color
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/generate-function
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
npm http 304 http://192.168.1.100:4873/boom
npm http 304 http://192.168.1.100:4873/hoek
npm http 304 http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/jsprim
npm http request GET http://192.168.1.100:4873/sshpk
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 304 http://192.168.1.100:4873/jsprim
npm http 304 http://192.168.1.100:4873/sshpk
npm http request GET http://192.168.1.100:4873/extsprintf
npm http request GET http://192.168.1.100:4873/json-schema
npm http request GET http://192.168.1.100:4873/verror
npm http 304 http://192.168.1.100:4873/json-schema
npm http 304 http://192.168.1.100:4873/verror
npm http 304 http://192.168.1.100:4873/extsprintf
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/dashdash
npm http request GET http://192.168.1.100:4873/getpass
npm http 304 http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/getpass
npm http 304 http://192.168.1.100:4873/dashdash
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/pull-stream
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/pull-stream
npm http request GET http://192.168.1.100:4873/pull-core
npm http 304 http://192.168.1.100:4873/pull-core
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/pouchdb-promise
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
npm http request GET http://192.168.1.100:4873/random-uuid-v4
npm http request GET http://192.168.1.100:4873/couchdb-eval
npm http request GET http://192.168.1.100:4873/couchdb-objects
npm http 304 http://192.168.1.100:4873/couchdb-objects
npm http 304 http://192.168.1.100:4873/random-uuid-v4
npm http 304 http://192.168.1.100:4873/couchdb-eval
npm http request GET http://192.168.1.100:4873/is-empty
npm http 304 http://192.168.1.100:4873/is-empty
npm http request GET http://192.168.1.100:4873/pouchdb-extend
npm http request GET http://192.168.1.100:4873/is-array
npm http request GET http://192.168.1.100:4873/pouchdb-upsert
npm http 304 http://192.168.1.100:4873/pouchdb-extend
npm http 304 http://192.168.1.100:4873/is-array
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
npm http request GET http://192.168.1.100:4873/fast-future
npm http request GET http://192.168.1.100:4873/bindings
npm http 304 http://192.168.1.100:4873/abstract-leveldown
npm http 304 http://192.168.1.100:4873/bindings
npm http 304 http://192.168.1.100:4873/fast-future
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/varint
npm http 304 http://192.168.1.100:4873/duplexify
npm http 304 http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/stream-shift
npm http 304 http://192.168.1.100:4873/end-of-stream
npm http 304 http://192.168.1.100:4873/stream-shift
npm http request GET http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/string_decoder
npm http 304 http://192.168.1.100:4873/buffer-shims
npm http 304 http://192.168.1.100:4873/string_decoder
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
npm http 200 http://192.168.1.100:4873/deep-eql
npm http 200 http://192.168.1.100:4873/type-detect
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
npm http 304 http://192.168.1.100:4873/clone-buffer
npm http 304 http://192.168.1.100:4873/level-codec
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/double-ended-queue
npm http 304 http://192.168.1.100:4873/levelup
npm http 304 http://192.168.1.100:4873/ltgt
npm http 304 http://192.168.1.100:4873/spark-md5
npm http 304 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/leveldown
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
npm http request GET http://192.168.1.100:4873/execspawn
npm http request GET http://192.168.1.100:4873/expand-template
npm http request GET http://192.168.1.100:4873/os-homedir
npm http request GET http://192.168.1.100:4873/ghreleases
npm http request GET http://192.168.1.100:4873/github-from-package
npm http request GET http://192.168.1.100:4873/node-ninja
npm http request GET http://192.168.1.100:4873/noop-logger
npm http request GET http://192.168.1.100:4873/node-gyp
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/npmlog
npm http request GET http://192.168.1.100:4873/pump
npm http request GET http://192.168.1.100:4873/simple-get
npm http request GET http://192.168.1.100:4873/rc
npm http request GET http://192.168.1.100:4873/tar-fs
npm http request GET http://192.168.1.100:4873/tar-stream
npm http 304 http://192.168.1.100:4873/execspawn
npm http 304 http://192.168.1.100:4873/expand-template
npm http 304 http://192.168.1.100:4873/os-homedir
npm http 304 http://192.168.1.100:4873/ghreleases
npm http 304 http://192.168.1.100:4873/github-from-package
npm http 304 http://192.168.1.100:4873/node-ninja
npm http 304 http://192.168.1.100:4873/noop-logger
npm http 304 http://192.168.1.100:4873/async
npm http 200 http://192.168.1.100:4873/npmlog
npm http 200 http://192.168.1.100:4873/node-gyp
npm http 200 http://192.168.1.100:4873/pump
npm http 200 http://192.168.1.100:4873/simple-get
npm http 304 http://192.168.1.100:4873/tar-stream
npm http 200 http://192.168.1.100:4873/rc
npm http 200 http://192.168.1.100:4873/tar-fs
npm http fetch GET http://192.168.1.100:4873/node-gyp/-/node-gyp-3.6.1.tgz
npm http fetch 200 http://192.168.1.100:4873/node-gyp/-/node-gyp-3.6.1.tgz
npm http fetch GET http://192.168.1.100:4873/rc/-/rc-1.2.1.tgz
npm http fetch GET http://192.168.1.100:4873/tar-fs/-/tar-fs-1.15.2.tgz
npm http fetch 200 http://192.168.1.100:4873/rc/-/rc-1.2.1.tgz
npm http fetch 200 http://192.168.1.100:4873/tar-fs/-/tar-fs-1.15.2.tgz
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
npm http 304 http://192.168.1.100:4873/hyperquest
npm http 304 http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/duplexer2
npm http 200 http://192.168.1.100:4873/duplexer2
npm http request GET http://192.168.1.100:4873/fstream
npm http request GET http://192.168.1.100:4873/semver
npm http request GET http://192.168.1.100:4873/nopt
npm http request GET http://192.168.1.100:4873/tar
npm http request GET http://192.168.1.100:4873/osenv
npm http request GET http://192.168.1.100:4873/which
npm http 304 http://192.168.1.100:4873/fstream
npm http 304 http://192.168.1.100:4873/tar
npm http 304 http://192.168.1.100:4873/nopt
npm http 304 http://192.168.1.100:4873/semver
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
npm http 200 http://192.168.1.100:4873/are-we-there-yet
npm http 304 http://192.168.1.100:4873/ansi
npm http 200 http://192.168.1.100:4873/gauge
npm http fetch GET http://192.168.1.100:4873/are-we-there-yet/-/are-we-there-yet-1.1.4.tgz
npm http fetch 200 http://192.168.1.100:4873/are-we-there-yet/-/are-we-there-yet-1.1.4.tgz
npm http request GET http://192.168.1.100:4873/delegates
npm http 200 http://192.168.1.100:4873/delegates
npm http request GET http://192.168.1.100:4873/has-unicode
npm http request GET http://192.168.1.100:4873/lodash.pad
npm http request GET http://192.168.1.100:4873/lodash.padend
npm http request GET http://192.168.1.100:4873/lodash.padstart
npm http 200 http://192.168.1.100:4873/has-unicode
npm http 304 http://192.168.1.100:4873/lodash.pad
npm http 304 http://192.168.1.100:4873/lodash.padend
npm http 304 http://192.168.1.100:4873/lodash.padstart
npm http request GET http://192.168.1.100:4873/os-tmpdir
npm http 304 http://192.168.1.100:4873/os-tmpdir
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 304 http://192.168.1.100:4873/asn1
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
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http 304 http://192.168.1.100:4873/end-of-stream
npm http fetch GET http://192.168.1.100:4873/end-of-stream/-/end-of-stream-1.4.0.tgz
npm http fetch 200 http://192.168.1.100:4873/end-of-stream/-/end-of-stream-1.4.0.tgz
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/deep-extend
npm http request GET http://192.168.1.100:4873/ini
npm http 304 http://192.168.1.100:4873/deep-extend
npm http 304 http://192.168.1.100:4873/strip-json-comments
npm http 200 http://192.168.1.100:4873/ini
npm http request GET http://192.168.1.100:4873/unzip-response
npm http 200 http://192.168.1.100:4873/unzip-response
npm http request GET http://192.168.1.100:4873/chownr
npm http 304 http://192.168.1.100:4873/chownr
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/uuid
npm http fetch GET http://192.168.1.100:4873/qs/-/qs-6.3.2.tgz
npm http fetch 200 http://192.168.1.100:4873/qs/-/qs-6.3.2.tgz
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/uuid
npm http fetch GET http://192.168.1.100:4873/form-data/-/form-data-2.1.4.tgz
npm http fetch 200 http://192.168.1.100:4873/form-data/-/form-data-2.1.4.tgz
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
npm http request GET http://192.168.1.100:4873/samsam
npm http request GET http://192.168.1.100:4873/lolex
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
npm http 304 http://192.168.1.100:4873/component-bind
npm http 304 http://192.168.1.100:4873/component-emitter
npm http 304 http://192.168.1.100:4873/engine.io-client
npm http 304 http://192.168.1.100:4873/object-component
npm http 304 http://192.168.1.100:4873/socket.io-parser
npm http 304 http://192.168.1.100:4873/indexof
npm http 304 http://192.168.1.100:4873/backo2
npm http 304 http://192.168.1.100:4873/has-binary
npm http 304 http://192.168.1.100:4873/parseuri
npm http 304 http://192.168.1.100:4873/to-array
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/ws
npm http request GET http://192.168.1.100:4873/xmlhttprequest-ssl
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/parseqs
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/yeast
npm http 304 http://192.168.1.100:4873/ws
npm http 304 http://192.168.1.100:4873/has-cors
npm http 304 http://192.168.1.100:4873/engine.io-parser
npm http 304 http://192.168.1.100:4873/xmlhttprequest-ssl
npm http 304 http://192.168.1.100:4873/parsejson
npm http 304 http://192.168.1.100:4873/parseqs
npm http 304 http://192.168.1.100:4873/yeast
npm http 304 http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/utf8
npm http request GET http://192.168.1.100:4873/after
npm http 304 http://192.168.1.100:4873/arraybuffer.slice
npm http 304 http://192.168.1.100:4873/blob
npm http 304 http://192.168.1.100:4873/base64-arraybuffer
npm http 304 http://192.168.1.100:4873/after
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
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/formidable
npm http request GET http://192.168.1.100:4873/reduce-component
npm http request GET http://192.168.1.100:4873/cookiejar
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 200 http://192.168.1.100:4873/cookiejar
npm http 200 http://192.168.1.100:4873/formidable
npm http 304 http://192.168.1.100:4873/reduce-component
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
npm http 304 http://192.168.1.100:4873/resumer
npm http 304 http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/defined
npm http 200 http://192.168.1.100:4873/object-inspect
npm WARN prefer global node-ninja@1.0.2 should be installed with -g
npm WARN prefer global node-gyp@3.6.1 should be installed with -g
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
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/javascript-state-machine
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-leveldb-core
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/javascript-state-machine
npm http 304 http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/lie
npm http 200 http://192.168.1.100:4873/body-parser
npm http 200 http://192.168.1.100:4873/ip
npm http 304 http://192.168.1.100:4873/winston
npm http 304 http://192.168.1.100:4873/long
npm http 200 http://192.168.1.100:4873/uuid
npm http 304 http://192.168.1.100:4873/multiplex
npm http 304 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/pouchdb-adapter-leveldb-core
npm http 200 http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/http-errors
npm http 200 http://192.168.1.100:4873/bytes
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/type-is
npm http 304 http://192.168.1.100:4873/raw-body
npm http 200 http://192.168.1.100:4873/iconv-lite
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
npm http request GET http://192.168.1.100:4873/parseurl
npm http request GET http://192.168.1.100:4873/path-to-regexp
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/proxy-addr
npm http request GET http://192.168.1.100:4873/range-parser
npm http request GET http://192.168.1.100:4873/send
npm http request GET http://192.168.1.100:4873/utils-merge
npm http request GET http://192.168.1.100:4873/vary
npm http request GET http://192.168.1.100:4873/serve-static
npm http 304 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/send
npm http 304 http://192.168.1.100:4873/utils-merge
npm http 304 http://192.168.1.100:4873/vary
npm http 304 http://192.168.1.100:4873/serve-static
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
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/xtend
npm http 200 http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/duplexify
npm http 304 http://192.168.1.100:4873/varint
npm http 200 http://192.168.1.100:4873/xtend
npm http fetch GET http://192.168.1.100:4873/readable-stream/-/readable-stream-2.2.9.tgz
npm http fetch 200 http://192.168.1.100:4873/readable-stream/-/readable-stream-2.2.9.tgz
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
npm http 304 http://192.168.1.100:4873/process-nextick-args
npm http 304 http://192.168.1.100:4873/buffer-shims
npm http 200 http://192.168.1.100:4873/string_decoder
npm http 200 http://192.168.1.100:4873/core-util-is
npm http 304 http://192.168.1.100:4873/util-deprecate
npm http fetch GET http://192.168.1.100:4873/string_decoder/-/string_decoder-1.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/string_decoder/-/string_decoder-1.0.0.tgz
npm http request GET http://192.168.1.100:4873/argsarray
npm http request GET http://192.168.1.100:4873/buffer-from
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/pouchdb-binary-utils
npm http request GET http://192.168.1.100:4873/pouchdb-json
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-utils
npm http request GET http://192.168.1.100:4873/pouchdb-errors
npm http request GET http://192.168.1.100:4873/pouchdb-md5
npm http request GET http://192.168.1.100:4873/pouchdb-merge
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/pouchdb-utils
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http 200 http://192.168.1.100:4873/argsarray
npm http 304 http://192.168.1.100:4873/buffer-from
npm http 304 http://192.168.1.100:4873/double-ended-queue
npm http 200 http://192.168.1.100:4873/pouchdb-binary-utils
npm http 200 http://192.168.1.100:4873/levelup
npm http 200 http://192.168.1.100:4873/pouchdb-json
npm http 200 http://192.168.1.100:4873/pouchdb-collections
npm http 200 http://192.168.1.100:4873/pouchdb-adapter-utils
npm http 200 http://192.168.1.100:4873/pouchdb-errors
npm http 200 http://192.168.1.100:4873/pouchdb-md5
npm http 200 http://192.168.1.100:4873/pouchdb-merge
npm http 200 http://192.168.1.100:4873/pouchdb-promise
npm http 200 http://192.168.1.100:4873/sublevel-pouchdb
npm http 200 http://192.168.1.100:4873/pouchdb-utils
npm http 200 http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/is-array-buffer-x
npm http 200 http://192.168.1.100:4873/is-array-buffer-x
npm http fetch GET http://192.168.1.100:4873/is-array-buffer-x/-/is-array-buffer-x-1.2.1.tgz
npm http fetch 200 http://192.168.1.100:4873/is-array-buffer-x/-/is-array-buffer-x-1.2.1.tgz
npm http request GET http://192.168.1.100:4873/is-object-like-x
npm http request GET http://192.168.1.100:4873/to-string-tag-x
npm http request GET http://192.168.1.100:4873/has-to-string-tag-x
npm http 200 http://192.168.1.100:4873/is-object-like-x
npm http 200 http://192.168.1.100:4873/has-to-string-tag-x
npm http 200 http://192.168.1.100:4873/to-string-tag-x
npm http fetch GET http://192.168.1.100:4873/is-object-like-x/-/is-object-like-x-1.2.0.tgz
npm http fetch GET http://192.168.1.100:4873/has-to-string-tag-x/-/has-to-string-tag-x-1.2.0.tgz
npm http fetch GET http://192.168.1.100:4873/to-string-tag-x/-/to-string-tag-x-1.2.0.tgz
npm http fetch 200 http://192.168.1.100:4873/is-object-like-x/-/is-object-like-x-1.2.0.tgz
npm http fetch 200 http://192.168.1.100:4873/has-to-string-tag-x/-/has-to-string-tag-x-1.2.0.tgz
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
npm http 304 http://192.168.1.100:4873/lodash.isnull
npm http 304 http://192.168.1.100:4873/validate.io-undefined
npm http request GET http://192.168.1.100:4873/level-errors
npm http request GET http://192.168.1.100:4873/prr
npm http request GET http://192.168.1.100:4873/deferred-leveldown
npm http request GET http://192.168.1.100:4873/level-codec
npm http request GET http://192.168.1.100:4873/level-iterator-stream
npm http request GET http://192.168.1.100:4873/semver
npm http 304 http://192.168.1.100:4873/level-errors
npm http 304 http://192.168.1.100:4873/deferred-leveldown
npm http 304 http://192.168.1.100:4873/level-iterator-stream
npm http 200 http://192.168.1.100:4873/semver
npm http 304 http://192.168.1.100:4873/level-codec
npm http 304 http://192.168.1.100:4873/prr
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http 304 http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/errno
npm http 304 http://192.168.1.100:4873/errno
npm http request GET http://192.168.1.100:4873/spark-md5
npm http 304 http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/clone-buffer
npm http 200 http://192.168.1.100:4873/clone-buffer
npm http request GET http://192.168.1.100:4873/vuvuzela
npm http 304 http://192.168.1.100:4873/vuvuzela
npm http request GET http://192.168.1.100:4873/ltgt
npm http 200 http://192.168.1.100:4873/ltgt
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/caseless
npm http 200 http://192.168.1.100:4873/form-data
npm http 200 http://192.168.1.100:4873/extend
npm http fetch GET http://192.168.1.100:4873/extend/-/extend-3.0.1.tgz
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/tunnel-agent
npm http 200 http://192.168.1.100:4873/bl
npm http 200 http://192.168.1.100:4873/tough-cookie
npm WARN deprecated node-uuid@1.4.8: Use uuid module instead
npm http fetch GET http://192.168.1.100:4873/node-uuid/-/node-uuid-1.4.8.tgz
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 200 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/stringstream
npm http fetch 200 http://192.168.1.100:4873/extend/-/extend-3.0.1.tgz
npm http fetch 200 http://192.168.1.100:4873/node-uuid/-/node-uuid-1.4.8.tgz
npm http 200 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/hawk
npm http 200 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 200 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http fetch GET http://192.168.1.100:4873/async/-/async-2.4.0.tgz
npm http fetch 200 http://192.168.1.100:4873/async/-/async-2.4.0.tgz
npm http request GET http://192.168.1.100:4873/lodash
npm http 200 http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/is-my-json-valid
npm http 200 http://192.168.1.100:4873/chalk
npm http 200 http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http 200 http://192.168.1.100:4873/ansi-styles
npm http 200 http://192.168.1.100:4873/has-ansi
npm http 200 http://192.168.1.100:4873/escape-string-regexp
npm http 200 http://192.168.1.100:4873/supports-color
npm http 200 http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 200 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http 304 http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http 304 http://192.168.1.100:4873/generate-function
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http request GET http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/boom
npm http 200 http://192.168.1.100:4873/sntp
npm http 200 http://192.168.1.100:4873/cryptiles
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
npm http request GET http://192.168.1.100:4873/stack-trace
npm http request GET http://192.168.1.100:4873/pkginfo
npm http 304 http://192.168.1.100:4873/colors
npm http 304 http://192.168.1.100:4873/cycle
npm http 304 http://192.168.1.100:4873/stack-trace
npm http 304 http://192.168.1.100:4873/pkginfo
npm http 304 http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/jsdoc
npm http request GET http://192.168.1.100:4873/eslint
npm http 200 http://192.168.1.100:4873/jsdoc
npm http 200 http://192.168.1.100:4873/eslint
npm http request GET http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/babel-code-frame
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/doctrine
npm http request GET http://192.168.1.100:4873/escope
npm http request GET http://192.168.1.100:4873/espree
npm http request GET http://192.168.1.100:4873/estraverse
npm http request GET http://192.168.1.100:4873/file-entry-cache
npm http request GET http://192.168.1.100:4873/ignore
npm http request GET http://192.168.1.100:4873/imurmurhash
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/globals
npm http request GET http://192.168.1.100:4873/is-resolvable
npm http request GET http://192.168.1.100:4873/json-stable-stringify
npm http request GET http://192.168.1.100:4873/inquirer
npm http request GET http://192.168.1.100:4873/levn
npm http request GET http://192.168.1.100:4873/natural-compare
npm http request GET http://192.168.1.100:4873/js-yaml
npm http request GET http://192.168.1.100:4873/optionator
npm http request GET http://192.168.1.100:4873/path-is-inside
npm http request GET http://192.168.1.100:4873/progress
npm http request GET http://192.168.1.100:4873/pluralize
npm http request GET http://192.168.1.100:4873/esutils
npm http request GET http://192.168.1.100:4873/require-uncached
npm http request GET http://192.168.1.100:4873/shelljs
npm http request GET http://192.168.1.100:4873/strip-bom
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/table
npm http request GET http://192.168.1.100:4873/text-table
npm http request GET http://192.168.1.100:4873/user-home
npm http 304 http://192.168.1.100:4873/doctrine
npm http 304 http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/concat-stream
npm http 200 http://192.168.1.100:4873/escope
npm http 200 http://192.168.1.100:4873/babel-code-frame
npm http 304 http://192.168.1.100:4873/file-entry-cache
npm http 304 http://192.168.1.100:4873/estraverse
npm http 200 http://192.168.1.100:4873/espree
npm http 304 http://192.168.1.100:4873/imurmurhash
npm http 200 http://192.168.1.100:4873/ignore
npm http 200 http://192.168.1.100:4873/mkdirp
npm http 304 http://192.168.1.100:4873/is-resolvable
npm http fetch GET http://192.168.1.100:4873/espree/-/espree-3.4.3.tgz
npm http 200 http://192.168.1.100:4873/json-stable-stringify
npm http fetch GET http://192.168.1.100:4873/ignore/-/ignore-3.3.0.tgz
npm http 200 http://192.168.1.100:4873/globals
npm http fetch GET http://192.168.1.100:4873/globals/-/globals-9.17.0.tgz
npm http 304 http://192.168.1.100:4873/natural-compare
npm http 200 http://192.168.1.100:4873/inquirer
npm http 200 http://192.168.1.100:4873/levn
npm http 200 http://192.168.1.100:4873/optionator
npm http 200 http://192.168.1.100:4873/js-yaml
npm http 200 http://192.168.1.100:4873/path-is-inside
npm http 304 http://192.168.1.100:4873/esutils
npm http 200 http://192.168.1.100:4873/progress
npm http fetch GET http://192.168.1.100:4873/js-yaml/-/js-yaml-3.8.4.tgz
npm http 200 http://192.168.1.100:4873/require-uncached
npm http 200 http://192.168.1.100:4873/pluralize
npm http 304 http://192.168.1.100:4873/strip-bom
npm http 200 http://192.168.1.100:4873/shelljs
npm http fetch 200 http://192.168.1.100:4873/espree/-/espree-3.4.3.tgz
npm http fetch 200 http://192.168.1.100:4873/ignore/-/ignore-3.3.0.tgz
npm http 200 http://192.168.1.100:4873/strip-json-comments
npm http 200 http://192.168.1.100:4873/text-table
npm http fetch 200 http://192.168.1.100:4873/globals/-/globals-9.17.0.tgz
npm http fetch 200 http://192.168.1.100:4873/js-yaml/-/js-yaml-3.8.4.tgz
npm http 200 http://192.168.1.100:4873/table
npm http 200 http://192.168.1.100:4873/user-home
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
npm http fetch GET http://192.168.1.100:4873/es6-weak-map/-/es6-weak-map-2.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/es6-map/-/es6-map-0.1.5.tgz
npm http fetch 200 http://192.168.1.100:4873/es6-weak-map/-/es6-weak-map-2.0.2.tgz
npm http request GET http://192.168.1.100:4873/d
npm http request GET http://192.168.1.100:4873/es6-symbol
npm http request GET http://192.168.1.100:4873/es6-iterator
npm http request GET http://192.168.1.100:4873/es6-set
npm http request GET http://192.168.1.100:4873/event-emitter
npm http request GET http://192.168.1.100:4873/es5-ext
npm http 200 http://192.168.1.100:4873/d
npm http 200 http://192.168.1.100:4873/es6-symbol
npm http 200 http://192.168.1.100:4873/es6-iterator
npm http 200 http://192.168.1.100:4873/es6-set
npm http 200 http://192.168.1.100:4873/event-emitter
npm http fetch GET http://192.168.1.100:4873/d/-/d-1.0.0.tgz
npm http fetch GET http://192.168.1.100:4873/es6-iterator/-/es6-iterator-2.0.1.tgz
npm http fetch GET http://192.168.1.100:4873/es6-set/-/es6-set-0.1.5.tgz
npm http fetch GET http://192.168.1.100:4873/es6-symbol/-/es6-symbol-3.1.1.tgz
npm http fetch GET http://192.168.1.100:4873/event-emitter/-/event-emitter-0.3.5.tgz
npm http fetch 200 http://192.168.1.100:4873/es6-iterator/-/es6-iterator-2.0.1.tgz
npm http fetch 200 http://192.168.1.100:4873/d/-/d-1.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/es6-set/-/es6-set-0.1.5.tgz
npm http fetch 200 http://192.168.1.100:4873/event-emitter/-/event-emitter-0.3.5.tgz
npm http fetch 200 http://192.168.1.100:4873/es6-symbol/-/es6-symbol-3.1.1.tgz
npm http 200 http://192.168.1.100:4873/es5-ext
npm http fetch GET http://192.168.1.100:4873/es5-ext/-/es5-ext-0.10.15.tgz
npm http fetch 200 http://192.168.1.100:4873/es5-ext/-/es5-ext-0.10.15.tgz
npm http request GET http://192.168.1.100:4873/acorn-jsx
npm http request GET http://192.168.1.100:4873/acorn
npm http 304 http://192.168.1.100:4873/acorn-jsx
npm http 200 http://192.168.1.100:4873/acorn
npm http fetch GET http://192.168.1.100:4873/acorn/-/acorn-5.0.3.tgz
npm http fetch 200 http://192.168.1.100:4873/acorn/-/acorn-5.0.3.tgz
npm http request GET http://192.168.1.100:4873/flat-cache
npm http 200 http://192.168.1.100:4873/flat-cache
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/circular-json
npm http request GET http://192.168.1.100:4873/del
npm http request GET http://192.168.1.100:4873/write
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http 200 http://192.168.1.100:4873/circular-json
npm http 200 http://192.168.1.100:4873/write
npm http 200 http://192.168.1.100:4873/del
npm http request GET http://192.168.1.100:4873/rimraf
npm http request GET http://192.168.1.100:4873/is-path-cwd
npm http request GET http://192.168.1.100:4873/is-path-in-cwd
npm http request GET http://192.168.1.100:4873/pify
npm http request GET http://192.168.1.100:4873/pinkie-promise
npm http request GET http://192.168.1.100:4873/globby
npm http 304 http://192.168.1.100:4873/pinkie-promise
npm http 304 http://192.168.1.100:4873/is-path-cwd
npm http 304 http://192.168.1.100:4873/is-path-in-cwd
npm http 304 http://192.168.1.100:4873/rimraf
npm http 200 http://192.168.1.100:4873/pify
npm http 200 http://192.168.1.100:4873/globby
npm http request GET http://192.168.1.100:4873/arrify
npm http request GET http://192.168.1.100:4873/array-union
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
npm http 304 http://192.168.1.100:4873/is-path-inside
npm http request GET http://192.168.1.100:4873/minimist
npm http 200 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/ansi-escapes
npm http request GET http://192.168.1.100:4873/cli-cursor
npm http request GET http://192.168.1.100:4873/cli-width
npm http request GET http://192.168.1.100:4873/figures
npm http request GET http://192.168.1.100:4873/readline2
npm http request GET http://192.168.1.100:4873/run-async
npm http request GET http://192.168.1.100:4873/rx-lite
npm http request GET http://192.168.1.100:4873/string-width
npm http request GET http://192.168.1.100:4873/through
npm http 200 http://192.168.1.100:4873/cli-cursor
npm http 304 http://192.168.1.100:4873/figures
npm http 304 http://192.168.1.100:4873/cli-width
npm http 200 http://192.168.1.100:4873/ansi-escapes
npm http 304 http://192.168.1.100:4873/readline2
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
npm http request GET http://192.168.1.100:4873/is-fullwidth-code-point
npm http request GET http://192.168.1.100:4873/code-point-at
npm http request GET http://192.168.1.100:4873/mute-stream
npm http 304 http://192.168.1.100:4873/is-fullwidth-code-point
npm http 304 http://192.168.1.100:4873/mute-stream
npm http 304 http://192.168.1.100:4873/code-point-at
npm http request GET http://192.168.1.100:4873/number-is-nan
npm http 200 http://192.168.1.100:4873/number-is-nan
npm http request GET http://192.168.1.100:4873/tryit
npm http 304 http://192.168.1.100:4873/tryit
npm http request GET http://192.168.1.100:4873/argparse
npm http request GET http://192.168.1.100:4873/esprima
npm http 200 http://192.168.1.100:4873/esprima
npm http 200 http://192.168.1.100:4873/argparse
npm http request GET http://192.168.1.100:4873/sprintf-js
npm http 200 http://192.168.1.100:4873/sprintf-js
npm http request GET http://192.168.1.100:4873/jsonify
npm http 304 http://192.168.1.100:4873/jsonify
npm http request GET http://192.168.1.100:4873/prelude-ls
npm http request GET http://192.168.1.100:4873/type-check
npm http 304 http://192.168.1.100:4873/type-check
npm http 304 http://192.168.1.100:4873/prelude-ls
npm http request GET http://192.168.1.100:4873/deep-is
npm http request GET http://192.168.1.100:4873/wordwrap
npm http request GET http://192.168.1.100:4873/fast-levenshtein
npm http 304 http://192.168.1.100:4873/deep-is
npm http 200 http://192.168.1.100:4873/wordwrap
npm http 200 http://192.168.1.100:4873/fast-levenshtein
npm http request GET http://192.168.1.100:4873/resolve-from
npm http request GET http://192.168.1.100:4873/caller-path
npm http 304 http://192.168.1.100:4873/caller-path
npm http 200 http://192.168.1.100:4873/resolve-from
npm http request GET http://192.168.1.100:4873/callsites
npm http 304 http://192.168.1.100:4873/callsites
npm http request GET http://192.168.1.100:4873/interpret
npm http request GET http://192.168.1.100:4873/rechoir
npm http 304 http://192.168.1.100:4873/rechoir
npm http 200 http://192.168.1.100:4873/interpret
npm http fetch GET http://192.168.1.100:4873/interpret/-/interpret-1.0.3.tgz
npm http fetch 200 http://192.168.1.100:4873/interpret/-/interpret-1.0.3.tgz
npm http request GET http://192.168.1.100:4873/resolve
npm http 200 http://192.168.1.100:4873/resolve
npm http fetch GET http://192.168.1.100:4873/resolve/-/resolve-1.3.3.tgz
npm http fetch 200 http://192.168.1.100:4873/resolve/-/resolve-1.3.3.tgz
npm http request GET http://192.168.1.100:4873/path-parse
npm http 200 http://192.168.1.100:4873/path-parse
npm http request GET http://192.168.1.100:4873/ajv-keywords
npm http request GET http://192.168.1.100:4873/ajv
npm http request GET http://192.168.1.100:4873/slice-ansi
npm http 200 http://192.168.1.100:4873/ajv-keywords
npm http 304 http://192.168.1.100:4873/slice-ansi
npm http 200 http://192.168.1.100:4873/ajv
npm http fetch GET http://192.168.1.100:4873/ajv/-/ajv-4.11.8.tgz
npm http fetch 200 http://192.168.1.100:4873/ajv/-/ajv-4.11.8.tgz
npm http request GET http://192.168.1.100:4873/co
npm http 200 http://192.168.1.100:4873/co
npm http request GET http://192.168.1.100:4873/os-homedir
npm http 304 http://192.168.1.100:4873/os-homedir
npm http request GET http://192.168.1.100:4873/catharsis
npm http request GET http://192.168.1.100:4873/js2xmlparser
npm http request GET http://192.168.1.100:4873/requizzle
npm http request GET http://192.168.1.100:4873/marked
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/wrench
npm http request GET http://192.168.1.100:4873/underscore
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 304 http://192.168.1.100:4873/catharsis
npm http 200 http://192.168.1.100:4873/js2xmlparser
npm http 200 http://192.168.1.100:4873/requizzle
npm http 304 http://192.168.1.100:4873/async
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
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/bn.js
npm http request GET http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/express-pouchdb
npm http request GET http://192.168.1.100:4873/leveldown-mobile
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/pouchdb
npm http request GET http://192.168.1.100:4873/proxyquire
npm http request GET http://192.168.1.100:4873/nock
npm http request GET http://192.168.1.100:4873/pouchdb-size
npm http request GET http://192.168.1.100:4873/request-promise
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/tmp
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/stacky
npm http request GET http://192.168.1.100:4873/supertest
npm http request GET http://192.168.1.100:4873/supertest-as-promised
npm http request GET http://192.168.1.100:4873/sinon
npm http request GET http://192.168.1.100:4873/tape-catch
npm http request GET http://192.168.1.100:4873/tape
npm http request GET http://192.168.1.100:4873/uuid-validate
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/child-process-promise
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/minimist
npm http 304 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/multiplex
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/randomstring
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/leveldown-mobile
npm http 304 http://192.168.1.100:4873/socket.io-client
npm http 304 http://192.168.1.100:4873/js-extend
npm http 200 http://192.168.1.100:4873/bn.js
npm http 304 http://192.168.1.100:4873/pouchdb-size
npm http 200 http://192.168.1.100:4873/proxyquire
npm http 200 http://192.168.1.100:4873/express-pouchdb
npm http 304 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/request-promise
npm http 304 http://192.168.1.100:4873/uuid
npm http 304 http://192.168.1.100:4873/stacky
npm http 304 http://192.168.1.100:4873/tape-catch
npm http 200 http://192.168.1.100:4873/tmp
npm http 200 http://192.168.1.100:4873/supertest-as-promised
npm http 200 http://192.168.1.100:4873/supertest
npm http 200 http://192.168.1.100:4873/uuid-validate
npm http 200 http://192.168.1.100:4873/pouchdb
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
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/merge-descriptors
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
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/basic-auth
npm http request GET http://192.168.1.100:4873/compression
npm http request GET http://192.168.1.100:4873/cookie-parser
npm http request GET http://192.168.1.100:4873/header-case-normalizer
npm http request GET http://192.168.1.100:4873/pouchdb-rewrite
npm http request GET http://192.168.1.100:4873/pouchdb-all-dbs
npm http request GET http://192.168.1.100:4873/multiparty
npm http request GET http://192.168.1.100:4873/pouchdb-auth
npm http request GET http://192.168.1.100:4873/pouchdb-list
npm http request GET http://192.168.1.100:4873/pouchdb-replicator
npm http request GET http://192.168.1.100:4873/pouchdb-find
npm http request GET http://192.168.1.100:4873/pouchdb-security
npm http request GET http://192.168.1.100:4873/pouchdb-update
npm http request GET http://192.168.1.100:4873/pouchdb-show
npm http request GET http://192.168.1.100:4873/pouchdb-validation
npm http request GET http://192.168.1.100:4873/pouchdb-vhost
npm http request GET http://192.168.1.100:4873/pouchdb-wrappers
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/header-case-normalizer
npm http 200 http://192.168.1.100:4873/basic-auth
npm http 200 http://192.168.1.100:4873/cookie-parser
npm http 200 http://192.168.1.100:4873/compression
npm http 304 http://192.168.1.100:4873/pouchdb-rewrite
npm http 304 http://192.168.1.100:4873/pouchdb-all-dbs
npm http 304 http://192.168.1.100:4873/pouchdb-auth
npm http 304 http://192.168.1.100:4873/pouchdb-list
npm http 200 http://192.168.1.100:4873/multiparty
npm http 200 http://192.168.1.100:4873/pouchdb-replicator
npm http 304 http://192.168.1.100:4873/pouchdb-update
npm http 200 http://192.168.1.100:4873/pouchdb-security
npm http 304 http://192.168.1.100:4873/pouchdb-show
npm http 200 http://192.168.1.100:4873/pouchdb-find
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
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/argsarray
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/tiny-queue
npm http 304 http://192.168.1.100:4873/es3ify
npm http 304 http://192.168.1.100:4873/argsarray
npm http 304 http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/tiny-queue
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/base62
npm http 304 http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/base64url
npm http request GET http://192.168.1.100:4873/couchdb-calculate-session-id
npm http request GET http://192.168.1.100:4873/crypto-lite
npm http request GET http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http request GET http://192.168.1.100:4873/pouchdb-plugin-error
npm http request GET http://192.168.1.100:4873/pouchdb-system-db
npm http request GET http://192.168.1.100:4873/promise-nodify
npm http request GET http://192.168.1.100:4873/pouchdb-req-http-query
npm http request GET http://192.168.1.100:4873/secure-random
npm http 304 http://192.168.1.100:4873/couchdb-calculate-session-id
npm http 200 http://192.168.1.100:4873/base64url
npm http 304 http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http 304 http://192.168.1.100:4873/crypto-lite
npm http 304 http://192.168.1.100:4873/pouchdb-plugin-error
npm http 304 http://192.168.1.100:4873/pouchdb-system-db
npm http 304 http://192.168.1.100:4873/promise-nodify
npm http 304 http://192.168.1.100:4873/pouchdb-req-http-query
npm http 200 http://192.168.1.100:4873/secure-random
npm http request GET http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/meow
npm http 304 http://192.168.1.100:4873/concat-stream
npm http 200 http://192.168.1.100:4873/meow
npm http request GET http://192.168.1.100:4873/typedarray
npm http 304 http://192.168.1.100:4873/typedarray
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/camelcase-keys
npm http request GET http://192.168.1.100:4873/indent-string
npm http 304 http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/indent-string
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
npm http 304 http://192.168.1.100:4873/is-finite
npm http request GET http://192.168.1.100:4873/number-is-nan
npm http 304 http://192.168.1.100:4873/number-is-nan
npm http request GET http://192.168.1.100:4873/aproba
npm http 200 http://192.168.1.100:4873/aproba
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/vuvuzela
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/level-write-stream
npm http request GET http://192.168.1.100:4873/es6-promise-pool
npm http request GET http://192.168.1.100:4873/localstorage-down
npm http request GET http://192.168.1.100:4873/fruitdown
npm http request GET http://192.168.1.100:4873/pouchdb-collate
npm http request GET http://192.168.1.100:4873/scope-eval
npm http request GET http://192.168.1.100:4873/memdown
npm http 304 http://192.168.1.100:4873/double-ended-queue
npm http 304 http://192.168.1.100:4873/levelup
npm http 304 http://192.168.1.100:4873/spark-md5
npm http 304 http://192.168.1.100:4873/pouchdb-collections
npm http 304 http://192.168.1.100:4873/through2
npm http 304 http://192.168.1.100:4873/sublevel-pouchdb
npm http 304 http://192.168.1.100:4873/vuvuzela
npm http 304 http://192.168.1.100:4873/js-extend
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/level-write-stream
npm http 200 http://192.168.1.100:4873/es6-promise-pool
npm http 304 http://192.168.1.100:4873/fruitdown
npm http 304 http://192.168.1.100:4873/localstorage-down
npm http 200 http://192.168.1.100:4873/pouchdb-collate
npm http 304 http://192.168.1.100:4873/scope-eval
npm http 304 http://192.168.1.100:4873/memdown
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
npm http request GET http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/is-typedarray
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/aws4
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/is-typedarray
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/stringstream
npm WARN deprecated tough-cookie@2.2.2: ReDoS vulnerability parsing Set-Cookie https://nodesecurity.io/advisories/130
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 304 http://192.168.1.100:4873/qs
npm http fetch GET http://192.168.1.100:4873/qs/-/qs-6.1.2.tgz
npm http fetch 200 http://192.168.1.100:4873/qs/-/qs-6.1.2.tgz
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/pinkie-promise
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http 304 http://192.168.1.100:4873/pinkie-promise
npm http 304 http://192.168.1.100:4873/chalk
npm http 304 http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/ansi-styles
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/supports-color
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/generate-function
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
npm http 304 http://192.168.1.100:4873/boom
npm http 304 http://192.168.1.100:4873/hoek
npm http 304 http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/jsprim
npm http request GET http://192.168.1.100:4873/sshpk
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 304 http://192.168.1.100:4873/jsprim
npm http 304 http://192.168.1.100:4873/sshpk
npm http request GET http://192.168.1.100:4873/extsprintf
npm http request GET http://192.168.1.100:4873/json-schema
npm http request GET http://192.168.1.100:4873/verror
npm http 304 http://192.168.1.100:4873/json-schema
npm http 304 http://192.168.1.100:4873/verror
npm http 304 http://192.168.1.100:4873/extsprintf
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/dashdash
npm http request GET http://192.168.1.100:4873/getpass
npm http 304 http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/getpass
npm http 304 http://192.168.1.100:4873/dashdash
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/pull-stream
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/pull-stream
npm http request GET http://192.168.1.100:4873/pull-core
npm http 304 http://192.168.1.100:4873/pull-core
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/pouchdb-promise
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
npm http request GET http://192.168.1.100:4873/random-uuid-v4
npm http request GET http://192.168.1.100:4873/couchdb-eval
npm http request GET http://192.168.1.100:4873/couchdb-objects
npm http 304 http://192.168.1.100:4873/couchdb-objects
npm http 304 http://192.168.1.100:4873/random-uuid-v4
npm http 304 http://192.168.1.100:4873/couchdb-eval
npm http request GET http://192.168.1.100:4873/is-empty
npm http 304 http://192.168.1.100:4873/is-empty
npm http request GET http://192.168.1.100:4873/pouchdb-extend
npm http request GET http://192.168.1.100:4873/is-array
npm http request GET http://192.168.1.100:4873/pouchdb-upsert
npm http 304 http://192.168.1.100:4873/pouchdb-extend
npm http 304 http://192.168.1.100:4873/is-array
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
npm http request GET http://192.168.1.100:4873/fast-future
npm http request GET http://192.168.1.100:4873/bindings
npm http 304 http://192.168.1.100:4873/abstract-leveldown
npm http 304 http://192.168.1.100:4873/bindings
npm http 304 http://192.168.1.100:4873/fast-future
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/varint
npm http 304 http://192.168.1.100:4873/duplexify
npm http 304 http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/stream-shift
npm http 304 http://192.168.1.100:4873/end-of-stream
npm http 304 http://192.168.1.100:4873/stream-shift
npm http request GET http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/string_decoder
npm http 304 http://192.168.1.100:4873/buffer-shims
npm http 304 http://192.168.1.100:4873/string_decoder
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
npm http 200 http://192.168.1.100:4873/deep-eql
npm http 200 http://192.168.1.100:4873/type-detect
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
npm http 304 http://192.168.1.100:4873/clone-buffer
npm http 304 http://192.168.1.100:4873/level-codec
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/double-ended-queue
npm http 304 http://192.168.1.100:4873/levelup
npm http 304 http://192.168.1.100:4873/ltgt
npm http 304 http://192.168.1.100:4873/spark-md5
npm http 304 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/leveldown
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
npm http request GET http://192.168.1.100:4873/execspawn
npm http request GET http://192.168.1.100:4873/expand-template
npm http request GET http://192.168.1.100:4873/os-homedir
npm http request GET http://192.168.1.100:4873/ghreleases
npm http request GET http://192.168.1.100:4873/github-from-package
npm http request GET http://192.168.1.100:4873/node-ninja
npm http request GET http://192.168.1.100:4873/noop-logger
npm http request GET http://192.168.1.100:4873/node-gyp
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/npmlog
npm http request GET http://192.168.1.100:4873/pump
npm http request GET http://192.168.1.100:4873/simple-get
npm http request GET http://192.168.1.100:4873/rc
npm http request GET http://192.168.1.100:4873/tar-fs
npm http request GET http://192.168.1.100:4873/tar-stream
npm http 304 http://192.168.1.100:4873/execspawn
npm http 304 http://192.168.1.100:4873/expand-template
npm http 304 http://192.168.1.100:4873/os-homedir
npm http 304 http://192.168.1.100:4873/ghreleases
npm http 304 http://192.168.1.100:4873/github-from-package
npm http 304 http://192.168.1.100:4873/node-ninja
npm http 304 http://192.168.1.100:4873/noop-logger
npm http 304 http://192.168.1.100:4873/async
npm http 200 http://192.168.1.100:4873/npmlog
npm http 200 http://192.168.1.100:4873/node-gyp
npm http 200 http://192.168.1.100:4873/pump
npm http 200 http://192.168.1.100:4873/simple-get
npm http 304 http://192.168.1.100:4873/tar-stream
npm http 200 http://192.168.1.100:4873/rc
npm http 200 http://192.168.1.100:4873/tar-fs
npm http fetch GET http://192.168.1.100:4873/node-gyp/-/node-gyp-3.6.1.tgz
npm http fetch 200 http://192.168.1.100:4873/node-gyp/-/node-gyp-3.6.1.tgz
npm http fetch GET http://192.168.1.100:4873/rc/-/rc-1.2.1.tgz
npm http fetch GET http://192.168.1.100:4873/tar-fs/-/tar-fs-1.15.2.tgz
npm http fetch 200 http://192.168.1.100:4873/rc/-/rc-1.2.1.tgz
npm http fetch 200 http://192.168.1.100:4873/tar-fs/-/tar-fs-1.15.2.tgz
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
npm http 304 http://192.168.1.100:4873/hyperquest
npm http 304 http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/duplexer2
npm http 200 http://192.168.1.100:4873/duplexer2
npm http request GET http://192.168.1.100:4873/fstream
npm http request GET http://192.168.1.100:4873/semver
npm http request GET http://192.168.1.100:4873/nopt
npm http request GET http://192.168.1.100:4873/tar
npm http request GET http://192.168.1.100:4873/osenv
npm http request GET http://192.168.1.100:4873/which
npm http 304 http://192.168.1.100:4873/fstream
npm http 304 http://192.168.1.100:4873/tar
npm http 304 http://192.168.1.100:4873/nopt
npm http 304 http://192.168.1.100:4873/semver
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
npm http 200 http://192.168.1.100:4873/are-we-there-yet
npm http 304 http://192.168.1.100:4873/ansi
npm http 200 http://192.168.1.100:4873/gauge
npm http fetch GET http://192.168.1.100:4873/are-we-there-yet/-/are-we-there-yet-1.1.4.tgz
npm http fetch 200 http://192.168.1.100:4873/are-we-there-yet/-/are-we-there-yet-1.1.4.tgz
npm http request GET http://192.168.1.100:4873/delegates
npm http 200 http://192.168.1.100:4873/delegates
npm http request GET http://192.168.1.100:4873/has-unicode
npm http request GET http://192.168.1.100:4873/lodash.pad
npm http request GET http://192.168.1.100:4873/lodash.padend
npm http request GET http://192.168.1.100:4873/lodash.padstart
npm http 200 http://192.168.1.100:4873/has-unicode
npm http 304 http://192.168.1.100:4873/lodash.pad
npm http 304 http://192.168.1.100:4873/lodash.padend
npm http 304 http://192.168.1.100:4873/lodash.padstart
npm http request GET http://192.168.1.100:4873/os-tmpdir
npm http 304 http://192.168.1.100:4873/os-tmpdir
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 304 http://192.168.1.100:4873/asn1
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
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http 304 http://192.168.1.100:4873/end-of-stream
npm http fetch GET http://192.168.1.100:4873/end-of-stream/-/end-of-stream-1.4.0.tgz
npm http fetch 200 http://192.168.1.100:4873/end-of-stream/-/end-of-stream-1.4.0.tgz
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/deep-extend
npm http request GET http://192.168.1.100:4873/ini
npm http 304 http://192.168.1.100:4873/deep-extend
npm http 304 http://192.168.1.100:4873/strip-json-comments
npm http 200 http://192.168.1.100:4873/ini
npm http request GET http://192.168.1.100:4873/unzip-response
npm http 200 http://192.168.1.100:4873/unzip-response
npm http request GET http://192.168.1.100:4873/chownr
npm http 304 http://192.168.1.100:4873/chownr
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/uuid
npm http fetch GET http://192.168.1.100:4873/qs/-/qs-6.3.2.tgz
npm http fetch 200 http://192.168.1.100:4873/qs/-/qs-6.3.2.tgz
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/uuid
npm http fetch GET http://192.168.1.100:4873/form-data/-/form-data-2.1.4.tgz
npm http fetch 200 http://192.168.1.100:4873/form-data/-/form-data-2.1.4.tgz
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
npm http request GET http://192.168.1.100:4873/samsam
npm http request GET http://192.168.1.100:4873/lolex
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
npm http 304 http://192.168.1.100:4873/component-bind
npm http 304 http://192.168.1.100:4873/component-emitter
npm http 304 http://192.168.1.100:4873/engine.io-client
npm http 304 http://192.168.1.100:4873/object-component
npm http 304 http://192.168.1.100:4873/socket.io-parser
npm http 304 http://192.168.1.100:4873/indexof
npm http 304 http://192.168.1.100:4873/backo2
npm http 304 http://192.168.1.100:4873/has-binary
npm http 304 http://192.168.1.100:4873/parseuri
npm http 304 http://192.168.1.100:4873/to-array
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/ws
npm http request GET http://192.168.1.100:4873/xmlhttprequest-ssl
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/parseqs
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/yeast
npm http 304 http://192.168.1.100:4873/ws
npm http 304 http://192.168.1.100:4873/has-cors
npm http 304 http://192.168.1.100:4873/engine.io-parser
npm http 304 http://192.168.1.100:4873/xmlhttprequest-ssl
npm http 304 http://192.168.1.100:4873/parsejson
npm http 304 http://192.168.1.100:4873/parseqs
npm http 304 http://192.168.1.100:4873/yeast
npm http 304 http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/utf8
npm http request GET http://192.168.1.100:4873/after
npm http 304 http://192.168.1.100:4873/arraybuffer.slice
npm http 304 http://192.168.1.100:4873/blob
npm http 304 http://192.168.1.100:4873/base64-arraybuffer
npm http 304 http://192.168.1.100:4873/after
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
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/formidable
npm http request GET http://192.168.1.100:4873/reduce-component
npm http request GET http://192.168.1.100:4873/cookiejar
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 200 http://192.168.1.100:4873/cookiejar
npm http 200 http://192.168.1.100:4873/formidable
npm http 304 http://192.168.1.100:4873/reduce-component
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
npm http 304 http://192.168.1.100:4873/resumer
npm http 304 http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/defined
npm http 200 http://192.168.1.100:4873/object-inspect
npm WARN prefer global node-ninja@1.0.2 should be installed with -g
npm WARN prefer global node-gyp@3.6.1 should be installed with -g
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
