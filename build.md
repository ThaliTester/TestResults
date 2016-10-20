#### Test (Fail) 89378607 Build Logs


```


```

```
Updating b3bc3ee..06cd5e9
Fast-forward
 thali/install/install.js             |   25 ++++++++++++++++++-------
 thali/install/utils/child_process.js |   30 ++++--------------------------
 thali/installCordovaPlugin.js        |    8 ++++----
 3 files changed, 26 insertions(+), 37 deletions(-)

From https://github.com/thaliproject/Thali_CordovaPlugin
   b3bc3ee..06cd5e9  master     -> origin/master
   5c5846f..44ecb7f  aaladev_1332 -> origin/aaladev_1332
   1bc4377..043093e  iOS        -> origin/iOS
 + 5849728...8e42e33 iOS_dersim_1318 -> origin/iOS_dersim_1318  (forced update)

```

```
Your branch is up-to-date with 'origin/master'.
Branch iOS set up to track remote branch iOS from origin.
Already up-to-date.

Already on 'master'
Switched to a new branch 'iOS'
Note: checking out '8e42e33'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at 8e42e33... Update AppContext.swift.
bash: shell_session_update: command not found

```

```
Cordova version:
6.3.1
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
│   ├── graceful-fs@4.1.9 
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


> thali@2.1.0 postinstall /Users/thali/Github/Thali_CordovaPlugin/thali
> "/usr/local/bin/jx" installCordovaPlugin.js

We believe we are in a clone of the GitHub Repo so we will not install Cordova dependencies

> thali@2.1.0 prepublish /Users/thali/Github/Thali_CordovaPlugin/thali
> "/usr/local/bin/jx" install/prePublishThaliCordovaPlugin.js

thali@2.1.0 /Users/thali/Github/Thali_CordovaPlugin/thali
├── bluebird@3.4.6 
├─┬ body-parser@1.13.3 
│ ├── bytes@2.1.0 
│ ├── content-type@1.0.2 
│ ├─┬ debug@2.2.0 
│ │ └── ms@0.7.1 
│ ├── depd@1.0.1 
│ ├─┬ http-errors@1.3.1 
│ │ └── statuses@1.3.0 
│ ├── iconv-lite@0.4.11 
│ ├─┬ on-finished@2.3.0 
│ │ └── ee-first@1.1.1 
│ ├── qs@4.0.0 
│ ├─┬ raw-body@2.1.7 
│ │ ├── bytes@2.4.0 
│ │ ├── iconv-lite@0.4.13 
│ │ └── unpipe@1.0.0 
│ └─┬ type-is@1.6.13 
│   └── media-typer@0.3.0 
├─┬ express@4.13.3 
│ ├─┬ accepts@1.2.13 
│ │ └── negotiator@0.5.3 
│ ├── array-flatten@1.1.1 
│ ├── content-disposition@0.5.0 
│ ├── cookie@0.1.3 
│ ├── cookie-signature@1.0.6 
│ ├── escape-html@1.0.2 
│ ├── etag@1.7.0 
│ ├── finalhandler@0.4.0 
│ ├── fresh@0.3.0 
│ ├── merge-descriptors@1.0.0 
│ ├── methods@1.1.2 
│ ├── parseurl@1.3.1 
│ ├── path-to-regexp@0.1.7 
│ ├─┬ proxy-addr@1.0.10 
│ │ ├── forwarded@0.1.0 
│ │ └── ipaddr.js@1.0.5 
│ ├── range-parser@1.0.3 
│ ├─┬ send@0.13.0 
│ │ ├── destroy@1.0.3 
│ │ ├── mime@1.3.4 
│ │ └── statuses@1.2.1 
│ ├─┬ serve-static@1.10.3 
│ │ ├── escape-html@1.0.3 
│ │ └─┬ send@0.13.2 
│ │   ├── depd@1.1.0 
│ │   ├── destroy@1.0.4 
│ │   └── statuses@1.2.1 
│ ├── utils-merge@1.0.0 
│ └── vary@1.0.1 
├── forever-agent@0.6.1 
├── ip@1.0.1 
├── javascript-state-machine@2.3.5 
├── js-extend@1.0.1 
├─┬ jsdoc@3.3.3 
│ ├── async@0.9.2 
│ ├─┬ catharsis@0.8.8 
│ │ └─┬ underscore-contrib@0.3.0 
│ │   └── underscore@1.6.0 
│ ├── escape-string-regexp@1.0.5 
│ ├── esprima@1.2.5 
│ ├── js2xmlparser@0.1.9 
│ ├── marked@0.3.6 
│ ├─┬ requizzle@0.2.1 
│ │ └── underscore@1.6.0 
│ ├── strip-json-comments@1.0.4 
│ ├── taffydb@2.6.2 
│ ├── underscore@1.7.0 
│ └── wrench@1.5.9 
├─┬ lie@3.1.0 
│ └── immediate@3.0.6 
├── long@3.0.3 
├─┬ multiplex@6.7.0 
│ ├─┬ duplexify@3.4.6 
│ │ ├─┬ end-of-stream@1.0.0 
│ │ │ └─┬ once@1.3.3 
│ │ │   └── wrappy@1.0.2 
│ │ └── stream-shift@1.0.0 
│ ├── inherits@2.0.3 
│ ├─┬ readable-stream@2.1.5 
│ │ ├── buffer-shims@1.0.0 
│ │ ├── core-util-is@1.0.2 
│ │ ├── isarray@1.0.0 
│ │ ├── process-nextick-args@1.0.7 
│ │ ├── string_decoder@0.10.31 
│ │ └── util-deprecate@1.0.2 
│ ├── varint@4.0.1 
│ └── xtend@4.0.1 
├── node-ssdp@2.6.5  (git://github.com/thaliproject/node-ssdp.git#fcc5d403f6cc5e667572fba059332908c3cc822e)
├─┬ request@2.64.0 
│ ├── aws-sign2@0.5.0 
│ ├─┬ bl@1.0.3 
│ │ └── readable-stream@2.0.6 
│ ├── caseless@0.11.0 
│ ├─┬ combined-stream@1.0.5 
│ │ └── delayed-stream@1.0.0 
│ ├── extend@3.0.0 
│ ├─┬ form-data@1.0.1 
│ │ └─┬ async@2.1.2 
│ │   └── lodash@4.16.4 
│ ├─┬ har-validator@1.8.0 
│ │ ├── bluebird@2.11.0 
│ │ ├─┬ chalk@1.1.3 
│ │ │ ├── ansi-styles@2.2.1 
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
│ ├── node-uuid@1.4.7 
│ ├── oauth-sign@0.8.2 
│ ├── qs@5.1.0 
│ ├── stringstream@0.0.5 
│ ├── tough-cookie@2.3.1 
│ └── tunnel-agent@0.4.3 
├─┬ salti@0.2.1  (git+https://github.com/thaliproject/salti.git#32abe64b9cd1a4213aed9012a94e26e06aa9c3ca)
│ ├── jsonschema@1.1.0 
│ └── object-assign@4.1.0 
├── urlsafe-base64@1.0.0 
├── uuid@2.0.2 
└─┬ winston@2.2.0 
  ├── async@1.0.0 
  ├── colors@1.0.3 
  ├── cycle@1.0.3 
  ├── eyes@0.1.8 
  ├── pkginfo@0.3.1 
  └── stack-trace@0.0.9 


> thali@2.1.0 postinstall /Users/thali/Github/Thali_CordovaPlugin/thali
> node installCordovaPlugin.js

We believe we are in a clone of the GitHub Repo so we will not install Cordova dependencies

> thali@2.1.0 prepublish /Users/thali/Github/Thali_CordovaPlugin/thali
> node install/prePublishThaliCordovaPlugin.js

/usr/local/lib/node_modules/thali -> /Users/thali/Github/Thali_CordovaPlugin/thali
install@0.0.1 /Users/thali/Github/Thali_CordovaPlugin/thali/install
├── bluebird@3.4.6 
├─┬ child-process-promise@1.1.0 
│ └── q@1.4.1 
├── end-with@1.0.2 
├── findit@2.0.0 
├─┬ fs-extra-promise@0.2.0 
│ ├── bluebird@2.11.0 
│ └─┬ fs-extra@0.21.0 
│   ├── graceful-fs@4.1.9 
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
│ │   └── lodash@4.16.4 
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
│ ├── tough-cookie@2.3.1 
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
thali-cordova-plugin-jxcore@1.0.0 /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore
├── balanced-match@0.2.0 
├── bluebird@3.4.6 
├── bn.js@4.10.0 
├─┬ body-parser@1.13.3 
│ ├── bytes@2.1.0 
│ ├── content-type@1.0.2 
│ ├─┬ debug@2.2.0 
│ │ └── ms@0.7.1 
│ ├── depd@1.0.1 
│ ├─┬ http-errors@1.3.1 
│ │ └── statuses@1.3.0 
│ ├── iconv-lite@0.4.11 
│ ├─┬ on-finished@2.3.0 
│ │ └── ee-first@1.1.1 
│ ├── qs@4.0.0 
│ ├─┬ raw-body@2.1.7 
│ │ ├── bytes@2.4.0 
│ │ └── unpipe@1.0.0 
│ └─┬ type-is@1.6.13 
│   └── media-typer@0.3.0 
├── child-process-promise@1.1.0 
├── concat-map@0.0.1 
├─┬ express@4.13.3 
│ ├─┬ accepts@1.2.13 
│ │ └── negotiator@0.5.3 
│ ├── array-flatten@1.1.1 
│ ├── content-disposition@0.5.0 
│ ├── cookie@0.1.3 
│ ├── cookie-signature@1.0.6 
│ ├── escape-html@1.0.2 
│ ├── etag@1.7.0 
│ ├── finalhandler@0.4.0 
│ ├── fresh@0.3.0 
│ ├── merge-descriptors@1.0.0 
│ ├── methods@1.1.2 
│ ├── parseurl@1.3.1 
│ ├── path-to-regexp@0.1.7 
│ ├─┬ proxy-addr@1.0.10 
│ │ ├── forwarded@0.1.0 
│ │ └── ipaddr.js@1.0.5 
│ ├── range-parser@1.0.3 
│ ├─┬ send@0.13.0 
│ │ ├── destroy@1.0.3 
│ │ ├── mime@1.3.4 
│ │ └── statuses@1.2.1 
│ ├─┬ serve-static@1.10.3 
│ │ ├── escape-html@1.0.3 
│ │ └─┬ send@0.13.2 
│ │   ├── depd@1.1.0 
│ │   ├── destroy@1.0.4 
│ │   └── statuses@1.2.1 
│ ├── utils-merge@1.0.0 
│ └── vary@1.0.1 
├─┬ express-pouchdb@1.0.5-thali 
│ ├── basic-auth@1.0.4 
│ ├── bluebird@3.4.1 
│ ├─┬ body-parser@1.15.2 
│ │ ├── bytes@2.4.0 
│ │ ├── depd@1.1.0 
│ │ ├─┬ http-errors@1.5.0 
│ │ │ └── setprototypeof@1.0.1 
│ │ └── qs@6.2.0 
│ ├─┬ compression@1.6.2 
│ │ ├─┬ accepts@1.3.3 
│ │ │ └── negotiator@0.6.1 
│ │ ├── bytes@2.3.0 
│ │ ├── compressible@2.0.8 
│ │ ├── on-headers@1.0.1 
│ │ └── vary@1.1.0 
│ ├─┬ cookie-parser@1.4.1 
│ │ └── cookie@0.2.3 
│ ├── extend@1.3.0 
│ ├── header-case-normalizer@1.0.3 
│ ├─┬ multiparty@3.3.2 
│ │ ├── readable-stream@1.1.14 
│ │ └─┬ stream-counter@0.2.0 
│ │   └── readable-stream@1.1.14 
│ ├── node-uuid@1.4.1 
│ ├─┬ pouchdb-all-dbs@1.0.2 
│ │ ├─┬ es3ify@0.1.4 
│ │ │ ├── esprima-fb@3001.1.0-dev-harmony-fb 
│ │ │ └─┬ jstransform@3.0.0 
│ │ │   ├── base62@0.1.1 
│ │ │   └── source-map@0.1.31 
│ │ ├── pouchdb-promise@5.4.3 
│ │ └── tiny-queue@0.2.1 
│ ├─┬ pouchdb-auth@2.1.0 
│ │ ├─┬ base64url@1.0.6 
│ │ │ ├─┬ concat-stream@1.4.10 
│ │ │ │ ├── readable-stream@1.1.14 
│ │ │ │ └── typedarray@0.0.6 
│ │ │ └─┬ meow@2.0.0 
│ │ │   ├─┬ camelcase-keys@1.0.0 
│ │ │   │ ├── camelcase@1.2.1 
│ │ │   │ └── map-obj@1.0.1 
│ │ │   ├─┬ indent-string@1.2.2 
│ │ │   │ ├── get-stdin@4.0.1 
│ │ │   │ └─┬ repeating@1.1.3 
│ │ │   │   └─┬ is-finite@1.0.2 
│ │ │   │     └── number-is-nan@1.0.1 
│ │ │   └── object-assign@1.0.0 
│ │ ├─┬ couchdb-calculate-session-id@1.1.1 
│ │ │ ├── aproba@1.0.4 
│ │ │ └── base64url@2.0.0 
│ │ ├── crypto-lite@0.1.0 
│ │ ├─┬ pouchdb-bulkdocs-wrapper@1.0.2 
│ │ │ └─┬ pouchdb-promise@0.0.0 
│ │ │   ├── bluebird@1.2.4 
│ │ │   └── lie@2.7.7 
│ │ ├── pouchdb-plugin-error@1.0.1 
│ │ ├─┬ pouchdb-req-http-query@1.0.3 
│ │ │ ├─┬ pouchdb-promise@0.0.0 
│ │ │ │ ├── bluebird@1.2.4 
│ │ │ │ └── lie@2.7.7 
│ │ │ └─┬ xmlhttprequest-cookie@0.9.4 
│ │ │   └── xmlhttprequest@1.8.0 
│ │ ├── pouchdb-system-db@1.0.4 
│ │ └── secure-random@1.1.1 
│ ├─┬ pouchdb-find@0.10.2 
│ │ ├── is-array@1.0.1 
│ │ ├─┬ lie@2.9.1 
│ │ │ └── unreachable-branch-transform@0.2.3 
│ │ ├── pouchdb-extend@0.1.2 
│ │ ├─┬ pouchdb-promise@5.4.0 
│ │ │ └─┬ lie@3.0.4 
│ │ │   └── unreachable-branch-transform@0.3.0 
│ │ ├── pouchdb-upsert@2.0.2 
│ │ └── spark-md5@0.0.5 
│ ├─┬ pouchdb-list@1.1.0 
│ │ ├─┬ couchdb-objects@1.0.7 
│ │ │ ├── is-empty@0.0.1 
│ │ │ └─┬ pouchdb-promise@0.0.0 
│ │ │   ├── bluebird@1.2.4 
│ │ │   └── lie@2.7.7 
│ │ ├── couchdb-render@1.0.1 
│ │ ├── extend@3.0.0 
│ │ └─┬ pouchdb-promise@0.0.0 
│ │   ├── bluebird@1.2.4 
│ │   └── lie@2.7.7 
│ ├─┬ pouchdb-replicator@2.1.3 
│ │ ├─┬ equals@1.0.5 
│ │ │ └── jkroso-type@1.1.1 
│ │ ├─┬ pouchdb-promise@0.0.0 
│ │ │ ├── bluebird@1.2.4 
│ │ │ └── lie@2.7.7 
│ │ └── random-uuid-v4@0.0.4 
│ ├─┬ pouchdb-rewrite@1.0.7 
│ │ └── pouchdb-route@1.0.3 
│ ├─┬ pouchdb-security@1.2.6 
│ │ ├── pouchdb-changeslike-wrapper@1.0.1 
│ │ └─┬ pouchdb-promise@0.0.0 
│ │   ├── bluebird@1.2.4 
│ │   └── lie@2.7.7 
│ ├─┬ pouchdb-show@1.0.8 
│ │ └─┬ pouchdb-promise@0.0.0 
│ │   ├── bluebird@1.2.4 
│ │   └── lie@2.7.7 
│ ├─┬ pouchdb-update@1.0.8 
│ │ ├── couchdb-eval@1.0.6 
│ │ ├── couchdb-resp-completer@1.0.3 
│ │ └─┬ pouchdb-promise@0.0.0 
│ │   ├── bluebird@1.2.4 
│ │   └── lie@2.7.7 
│ ├─┬ pouchdb-validation@1.2.1 
│ │ └─┬ pouchdb-promise@0.0.0 
│ │   ├── bluebird@1.2.4 
│ │   └── lie@2.7.7 
│ ├── pouchdb-vhost@1.0.2 
│ └── pouchdb-wrappers@1.3.6 
├── forever-agent@0.6.1 
├─┬ fs-extra-promise@0.4.0
│ └── bluebird@3.4.6 
├── inherits@2.0.1 
├── is-property@1.0.2 
├── js-extend@1.0.1 
├─┬ leveldown-mobile@1.1.1 
│ ├── abstract-leveldown@2.1.4 
│ ├── bindings@1.2.1 
│ └── fast-future@1.0.1 
├─┬ lie@3.0.4 
│ ├─┬ es3ify@0.2.2
│ │ └─┬ jstransform@11.0.3
│ │   └─┬ commoner@0.10.4
│ │     └── glob@5.0.15 
│ └── unreachable-branch-transform@0.3.0 
├── long@3.0.3 
├── minimist@1.2.0 
├─┬ multiplex@6.7.0 
│ ├─┬ duplexify@3.4.6 
│ │ ├─┬ end-of-stream@1.0.0 
│ │ │ └── once@1.3.3 
│ │ ├─┬ readable-stream@2.1.5 
│ │ │ └── isarray@1.0.0 
│ │ └── stream-shift@1.0.0 
│ ├─┬ readable-stream@2.1.5 
│ │ ├── buffer-shims@1.0.0 
│ │ ├── isarray@1.0.0 
│ │ ├── process-nextick-args@1.0.7 
│ │ └── util-deprecate@1.0.2 
│ └── varint@4.0.1 
├─┬ nock@2.12.0 
│ ├─┬ chai@3.5.0 
│ │ ├── assertion-error@1.0.2 
│ │ ├─┬ deep-eql@0.1.3 
│ │ │ └── type-detect@0.1.1 
│ │ └── type-detect@1.0.0 
│ ├─┬ debug@1.0.4 
│ │ └── ms@0.6.2 
│ ├── deep-equal@1.0.1 
│ ├── lodash@2.4.1 
│ └── propagate@0.3.1 
├─┬ node-ssdp@2.6.5  (git://github.com/thaliproject/node-ssdp.git#fcc5d403f6cc5e667572fba059332908c3cc822e)
│ └── ip@1.1.3 
├── node-uuid@1.4.7 
├── object-assign@4.1.0 
├─┬ pouchdb@5.4.5 
│ ├── argsarray@0.0.1 
│ ├── double-ended-queue@2.0.0-0 
│ ├── es6-promise-pool@2.4.2 
│ ├─┬ fruitdown@1.0.2 
│ │ ├─┬ abstract-leveldown@0.12.3 
│ │ │ └── xtend@3.0.0 
│ │ ├── d64@1.0.0 
│ │ └── tiny-queue@0.2.0 
│ ├── js-extend@0.0.1 
│ ├─┬ level-write-stream@1.0.0 
│ │ └─┬ end-stream@0.1.0 
│ │   └─┬ write-stream@0.4.3 
│ │     └── readable-stream@0.0.4 
│ ├─┬ levelup@1.3.2 
│ │ ├─┬ deferred-leveldown@1.2.1 
│ │ │ └── abstract-leveldown@2.4.1 
│ │ ├── level-codec@6.1.0 
│ │ ├── level-errors@1.0.4 
│ │ ├── level-iterator-stream@1.3.1 
│ │ ├── prr@1.0.1 
│ │ └── semver@5.1.1 
│ ├─┬ localstorage-down@0.6.6 
│ │ ├─┬ humble-localstorage@1.4.2 
│ │ │ ├── has-localstorage@1.0.1 
│ │ │ └── localstorage-memory@1.0.2 
│ │ └── tiny-queue@0.2.0 
│ ├─┬ memdown@1.1.2 
│ │ ├── abstract-leveldown@2.6.1 
│ │ ├── functional-red-black-tree@1.0.1 
│ │ └── ltgt@1.0.2 
│ ├── pouchdb-collate@1.2.0 
│ ├── pouchdb-collections@1.0.1 
│ ├─┬ request@2.72.0 
│ │ ├── aws-sign2@0.6.0 
│ │ ├── aws4@1.5.0 
│ │ ├─┬ bl@1.1.2 
│ │ │ └─┬ readable-stream@2.0.6 
│ │ │   └── isarray@1.0.0 
│ │ ├── extend@3.0.0 
│ │ ├─┬ har-validator@2.0.6 
│ │ │ └─┬ pinkie-promise@2.0.1 
│ │ │   └── pinkie@2.0.4 
│ │ ├─┬ http-signature@1.1.1 
│ │ │ ├── assert-plus@0.2.0 
│ │ │ ├─┬ jsprim@1.3.1 
│ │ │ │ ├── extsprintf@1.0.2 
│ │ │ │ ├── json-schema@0.2.3 
│ │ │ │ └── verror@1.3.6 
│ │ │ └─┬ sshpk@1.10.1 
│ │ │   ├── asn1@0.2.3 
│ │ │   ├── assert-plus@1.0.0 
│ │ │   ├─┬ dashdash@1.14.0 
│ │ │   │ └── assert-plus@1.0.0 
│ │ │   └─┬ getpass@0.1.6 
│ │ │     └── assert-plus@1.0.0 
│ │ ├── is-typedarray@1.0.0 
│ │ └── qs@6.1.0 
│ ├── scope-eval@0.0.3 
│ ├── spark-md5@2.0.2 
│ ├─┬ sublevel-pouchdb@1.0.1 
│ │ ├─┬ errno@0.1.4 
│ │ │ └── prr@0.0.0 
│ │ ├── ltgt@2.1.2 
│ │ ├─┬ pull-stream@2.21.0 
│ │ │ └── pull-core@1.0.0 
│ │ └── readable-stream@1.0.33 
│ ├─┬ through2@2.0.1 
│ │ └─┬ readable-stream@2.0.6 
│ │   └── isarray@1.0.0 
│ └── vuvuzela@1.0.3 
├─┬ pouchdb-size@1.2.2 
│ ├── bluebird@2.11.0 
│ ├─┬ get-folder-size@0.1.1 
│ │ ├── async@0.9.2 
│ │ └── minimist@0.1.0 
│ └── promise-nodify@1.0.2 
├─┬ proxyquire@1.7.4 
│ ├─┬ fill-keys@1.0.2 
│ │ └── is-object@1.0.1 
│ └── module-not-found-error@1.0.1 
├─┬ randomstring@1.1.5 
│ └── array-uniq@1.0.2 
├─┬ request@2.64.0 
│ ├── aws-sign2@0.5.0 
│ ├─┬ bl@1.0.3 
│ │ └─┬ readable-stream@2.0.6 
│ │   └── isarray@1.0.0 
│ ├── caseless@0.11.0 
│ ├─┬ combined-stream@1.0.5 
│ │ └── delayed-stream@1.0.0 
│ ├── extend@3.0.0 
│ ├─┬ form-data@1.0.1 
│ │ └─┬ async@2.1.2 
│ │   └── lodash@4.16.4 
│ ├─┬ har-validator@1.8.0 
│ │ ├── bluebird@2.11.0 
│ │ └─┬ is-my-json-valid@2.15.0 
│ │   ├── generate-function@2.0.0 
│ │   ├── generate-object-property@1.2.0 
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
│ ├── tough-cookie@2.2.2 
│ └── tunnel-agent@0.4.3 
├─┬ request-promise@0.4.3 
│ ├── bluebird@2.11.0 
│ ├─┬ chalk@1.1.3 
│ │ ├── ansi-styles@2.2.1 
│ │ ├── escape-string-regexp@1.0.5 
│ │ ├─┬ has-ansi@2.0.0 
│ │ │ └── ansi-regex@2.0.0 
│ │ ├── strip-ansi@3.0.1 
│ │ └── supports-color@2.0.0 
│ └── lodash@3.10.1 
├─┬ salti@0.2.1  (git+https://github.com/thaliproject/salti.git#32abe64b9cd1a4213aed9012a94e26e06aa9c3ca)
│ └── jsonschema@1.1.0 
├─┬ sinon@1.17.3 
│ ├── formatio@1.1.1 
│ ├── lolex@1.3.2 
│ ├── samsam@1.1.2 
│ └── util@0.10.3 
├─┬ socket.io-client@1.4.8 
│ ├── backo2@1.0.2 
│ ├── component-bind@1.0.0 
│ ├── component-emitter@1.2.0 
│ ├─┬ engine.io-client@1.6.11 
│ │ ├── component-emitter@1.1.2 
│ │ ├── component-inherit@0.0.3 
│ │ ├─┬ engine.io-parser@1.2.4 
│ │ │ ├── after@0.8.1 
│ │ │ ├── arraybuffer.slice@0.0.6 
│ │ │ ├── base64-arraybuffer@0.1.2 
│ │ │ ├── blob@0.0.4 
│ │ │ ├── has-binary@0.1.6 
│ │ │ └── utf8@2.1.0 
│ │ ├── has-cors@1.1.0 
│ │ ├── parsejson@0.0.1 
│ │ ├── parseqs@0.0.2 
│ │ ├─┬ ws@1.0.1 
│ │ │ ├── options@0.0.6 
│ │ │ └── ultron@1.0.2 
│ │ ├── xmlhttprequest-ssl@1.5.1 
│ │ └── yeast@0.1.2 
│ ├── has-binary@0.1.7 
│ ├── indexof@0.0.1 
│ ├── object-component@0.0.3 
│ ├─┬ parseuri@0.0.4 
│ │ └─┬ better-assert@1.0.2 
│ │   └── callsite@1.0.0 
│ ├─┬ socket.io-parser@2.2.6 
│ │ ├── benchmark@1.0.0 
│ │ ├── component-emitter@1.1.2 
│ │ └── json3@3.3.2 
│ └── to-array@0.1.4 
├─┬ supertest@1.1.0 
│ └─┬ superagent@1.3.0 
│   ├── component-emitter@1.1.2 
│   ├── cookiejar@2.0.1 
│   ├── extend@1.2.1 
│   ├─┬ form-data@0.2.0 
│   │ ├── async@0.9.2 
│   │ ├─┬ combined-stream@0.0.7 
│   │ │ └── delayed-stream@0.0.5 
│   │ └─┬ mime-types@2.0.14 
│   │   └── mime-db@1.12.0 
│   ├── formidable@1.0.14 
│   ├── methods@1.0.1 
│   ├── qs@2.3.3 
│   ├── readable-stream@1.0.27-1 
│   └── reduce-component@1.0.1 
├─┬ supertest-as-promised@2.0.2 
│ └── bluebird@2.11.0 
├─┬ tape@4.0.0 
│ ├── defined@0.0.0 
│ ├─┬ glob@5.0.15 
│ │ └─┬ minimatch@3.0.3
│ │   └─┬ brace-expansion@1.1.6
│ │     └── concat-map@0.0.1 
│ ├── object-inspect@1.0.2 
│ └── resumer@0.0.0 
├── tape-catch@1.0.4 
├─┬ thali@2.1.0 -> /Users/thali/Github/Thali_CordovaPlugin/thali
│ ├── bluebird@3.4.6 
│ ├─┬ body-parser@1.13.3 
│ │ ├── bytes@2.1.0 
│ │ ├── content-type@1.0.2 
│ │ ├─┬ debug@2.2.0 
│ │ │ └── ms@0.7.1 
│ │ ├── depd@1.0.1 
│ │ ├─┬ http-errors@1.3.1 
│ │ │ └── statuses@1.3.0 
│ │ ├── iconv-lite@0.4.11 
│ │ ├─┬ on-finished@2.3.0 
│ │ │ └── ee-first@1.1.1 
│ │ ├── qs@4.0.0 
│ │ ├─┬ raw-body@2.1.7 
│ │ │ ├── bytes@2.4.0 
│ │ │ └── unpipe@1.0.0 
│ │ └─┬ type-is@1.6.13 
│ │   └── media-typer@0.3.0 
│ ├─┬ express@4.13.3 
│ │ ├─┬ accepts@1.2.13 
│ │ │ └── negotiator@0.5.3 
│ │ ├── array-flatten@1.1.1 
│ │ ├── content-disposition@0.5.0 
│ │ ├── cookie@0.1.3 
│ │ ├── cookie-signature@1.0.6 
│ │ ├── escape-html@1.0.2 
│ │ ├── etag@1.7.0 
│ │ ├── finalhandler@0.4.0 
│ │ ├── fresh@0.3.0 
│ │ ├── merge-descriptors@1.0.0 
│ │ ├── methods@1.1.2 
│ │ ├── parseurl@1.3.1 
│ │ ├── path-to-regexp@0.1.7 
│ │ ├─┬ proxy-addr@1.0.10 
│ │ │ ├── forwarded@0.1.0 
│ │ │ └── ipaddr.js@1.0.5 
│ │ ├── range-parser@1.0.3 
│ │ ├─┬ send@0.13.0 
│ │ │ ├── destroy@1.0.3 
│ │ │ ├── mime@1.3.4 
│ │ │ └── statuses@1.2.1 
│ │ ├─┬ serve-static@1.10.3 
│ │ │ ├── escape-html@1.0.3 
│ │ │ └─┬ send@0.13.2 
│ │ │   ├── depd@1.1.0 
│ │ │   ├── destroy@1.0.4 
│ │ │   └── statuses@1.2.1 
│ │ ├── utils-merge@1.0.0 
│ │ └── vary@1.0.1 
│ ├── forever-agent@0.6.1 
│ ├── js-extend@1.0.1 
│ ├─┬ jsdoc@3.3.3
│ │ ├── async@0.9.2 
│ │ └── escape-string-regexp@1.0.5 
│ ├── long@3.0.3 
│ ├─┬ multiplex@6.7.0 
│ │ ├─┬ duplexify@3.4.6 
│ │ │ ├─┬ end-of-stream@1.0.0 
│ │ │ │ └── once@1.3.3 
│ │ │ └── stream-shift@1.0.0 
│ │ ├─┬ readable-stream@2.1.5 
│ │ │ ├── buffer-shims@1.0.0 
│ │ │ ├── isarray@1.0.0 
│ │ │ ├── process-nextick-args@1.0.7 
│ │ │ └── util-deprecate@1.0.2 
│ │ └── varint@4.0.1 
│ ├── node-ssdp@2.6.5  (git://github.com/thaliproject/node-ssdp.git#fcc5d403f6cc5e667572fba059332908c3cc822e)
│ ├─┬ request@2.64.0 
│ │ ├── aws-sign2@0.5.0 
│ │ ├─┬ bl@1.0.3 
│ │ │ └── readable-stream@2.0.6 
│ │ ├── caseless@0.11.0 
│ │ ├─┬ combined-stream@1.0.5 
│ │ │ └── delayed-stream@1.0.0 
│ │ ├── extend@3.0.0 
│ │ ├─┬ form-data@1.0.1 
│ │ │ └─┬ async@2.1.2 
│ │ │   └── lodash@4.16.4 
│ │ ├─┬ har-validator@1.8.0 
│ │ │ ├── bluebird@2.11.0 
│ │ │ ├─┬ chalk@1.1.3 
│ │ │ │ ├── ansi-styles@2.2.1 
│ │ │ │ ├─┬ has-ansi@2.0.0 
│ │ │ │ │ └── ansi-regex@2.0.0 
│ │ │ │ ├── strip-ansi@3.0.1 
│ │ │ │ └── supports-color@2.0.0 
│ │ │ └─┬ is-my-json-valid@2.15.0 
│ │ │   ├── generate-function@2.0.0 
│ │ │   ├─┬ generate-object-property@1.2.0 
│ │ │   │ └── is-property@1.0.2 
│ │ │   └── jsonpointer@4.0.0 
│ │ ├─┬ hawk@3.1.3 
│ │ │ ├── boom@2.10.1 
│ │ │ ├── cryptiles@2.0.5 
│ │ │ ├── hoek@2.16.3 
│ │ │ └── sntp@1.0.9 
│ │ ├─┬ http-signature@0.11.0 
│ │ │ ├── asn1@0.1.11 
│ │ │ ├── assert-plus@0.1.5 
│ │ │ └── ctype@0.5.3 
│ │ ├── isstream@0.1.2 
│ │ ├── json-stringify-safe@5.0.1 
│ │ ├─┬ mime-types@2.1.12 
│ │ │ └── mime-db@1.24.0 
│ │ ├── node-uuid@1.4.7 
│ │ ├── oauth-sign@0.8.2 
│ │ ├── qs@5.1.0 
│ │ ├── stringstream@0.0.5 
│ │ └── tunnel-agent@0.4.3 
│ ├─┬ salti@0.2.1  (git+https://github.com/thaliproject/salti.git#32abe64b9cd1a4213aed9012a94e26e06aa9c3ca)
│ │ ├── jsonschema@1.1.0 
│ │ └── object-assign@4.1.0 
│ └── urlsafe-base64@1.0.0 
├─┬ tmp@0.0.28 
│ └── os-tmpdir@1.0.2 
├── urlsafe-base64@1.0.0 
├── uuid@2.0.0 
└── uuid-validate@0.0.2 


> thali-cordova-plugin-jxcore@1.0.0 test /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore
> jx runTests.js

2016-10-20 08:15:36 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreateNativeListener.js'
2016-10-20 08:15:36 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js'
2016-10-20 08:15:36 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js'
2016-10-20 08:15:37 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
2016-10-20 08:15:37 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
2016-10-20 08:15:37 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testNativeMethod.js'
2016-10-20 08:15:37 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
2016-10-20 08:15:37 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBGenerator.js'
2016-10-20 08:15:37 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPromiseQueue.js'
2016-10-20 08:15:37 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testTests.js'
2016-10-20 08:15:37 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManager.js'
2016-10-20 08:15:37 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
2016-10-20 08:15:37 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js'
2016-10-20 08:15:37 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNative.js'
2016-10-20 08:15:37 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
2016-10-20 08:15:37 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
2016-10-20 08:15:37 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
2016-10-20 08:15:37 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
2016-10-20 08:15:37 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotification.js'
2016-10-20 08:15:37 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationAction.js'
2016-10-20 08:15:37 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
2016-10-20 08:15:37 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationClient.js'
2016-10-20 08:15:37 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationLocal.js'
2016-10-20 08:15:37 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationServer.js'
2016-10-20 08:15:37 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerAction.js'
2016-10-20 08:15:37 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerDictionary.js'
2016-10-20 08:15:37 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
2016-10-20 08:15:37 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
2016-10-20 08:15:37 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
2016-10-20 08:15:37 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
2016-10-20 08:15:37 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
2016-10-20 08:15:37 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
2016-10-20 08:15:37 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
2016-10-20 08:15:37 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
2016-10-20 08:15:37 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliTcpServersManager.js'
2016-10-20 08:15:37 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
2016-10-20 08:15:37 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testUsn.js'
2016-10-20 08:15:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-20 08:15:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-20 08:15:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-20 08:15:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-10-20 08:15:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-20 08:15:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
TAP version 13
# setup
# calling createNativeListener directly rejects
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'listening 49676'
ok 1 Should throw
# teardown
# setup
# emits incomingConnectionState
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'listening 49678'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new mux'
ok 2 initial connection state should be CONNECTED
2016-10-20 08:15:37 - DEBUG createNativeListener: 'incoming socket close'
ok 3 final connection state should be DISCONNECTED
# teardown
# setup
# emits routerPortConnectionFailed
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'listening 49681'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new mux'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: ' Error: connect ECONNREFUSED
    at errnoException (net.js:837:11)
    at Object.afterConnect [as oncomplete] (net.js:829:19)'
ok 4 tried to connect to right port
ok 5 failed due to refused connection
ok 6 routerPortConnectionFailed is emitted
# teardown
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'mux close'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'incoming socket close'
# setup
# native server connections all up
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'listening 49685'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new mux'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
ok 7 Send/recvd #1 should be equal length
ok 8 Send/recvd #1 should be same
ok 9 Send/recvd #2 should be equal length
ok 10 Send/recvd #2 should be same
ok 11 Should be exactly 2 client sockets
# teardown
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'mux close'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'incoming socket close'
# setup
# native server - closing incoming stream cleans outgoing socket
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'listening 49690'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new mux'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
ok 12 socket shouldn't close until after stream
ok 13 incoming remains open
# teardown
2016-10-20 08:15:37 - DEBUG createNativeListener: 'mux close'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'incoming socket close'
# setup
# native server - closing incoming connection cleans outgoing socket
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'listening 49694'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new mux'
ok 14 we should not have gotten an error
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'incoming socket close'
ok 15 socket shouldn't close until after incoming
ok 16 incoming is cleaned up
# teardown
# setup
# native server - closing outgoing socket cleans associated mux stream
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'listening 49698'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new mux'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
ok 17 stream was closed
ok 18 incoming should survive
ok 19 mux should have no streams
# teardown
2016-10-20 08:15:37 - DEBUG createNativeListener: 'mux close'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'incoming socket close'
# setup
# native server - closing the whole server cleans everything up
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'listening 49702'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new mux'
ok 20 we should not have gotten an error
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
ok 21 Buffers are identical
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'mux close'
ok 22 native server is nulled out
ok 23 native server should be closed
ok 24 incoming has been removed
ok 25 Incoming should be done
ok 26 The mux object should be closed
ok 27 The mux stream should be closed
2016-10-20 08:15:37 - DEBUG createNativeListener: 'incoming socket close'
# teardown
# setup
# native server - we can get a ton of connections and data through and still clean up the server completely
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'listening 49706'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new mux'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new mux'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new mux'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new mux'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new mux'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new mux'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new mux'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new mux'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new mux'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new mux'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'mux close'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'mux close'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'mux close'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'mux close'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'mux close'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'mux close'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'mux close'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'mux close'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'mux close'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'mux close'
ok 28 native server is nulled out
ok 29 native server should be closed
ok 30 incoming has been removed
2016-10-20 08:15:37 - DEBUG createNativeListener: 'incoming socket close'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'incoming socket close'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'incoming socket close'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'incoming socket close'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'incoming socket close'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'incoming socket close'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'incoming socket close'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'incoming socket close'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'incoming socket close'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'incoming socket close'
# teardown
# setup
# native server - simulate mux failure, make sure everything is cleaned up
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'listening 49758'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new mux'
ok 31 we should not have gotten an error
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
ok 32 Buffers are identical
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'mux close'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'incoming socket close'
ok 33 server should be fine
ok 34 server should be open
ok 35 incoming has been removed
ok 36 The mux object should be closed
ok 37 The mux stream should be closed
# teardown
# setup
# native server - timing out the incoming connection cleans everything up
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'listening 49762'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new mux'
ok 38 we should not have gotten an error
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
ok 39 Buffers are identical
2016-10-20 08:15:37 - DEBUG createNativeListener: 'incoming socket timeout'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'mux close'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'incoming socket close'
ok 40 server should be fine
ok 41 server should be open
ok 42 incoming has been removed
ok 43 The mux object should be closed
ok 44 The mux stream should be closed
# teardown
# setup
# calling createPeerListener without calling start produces error
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'listening 49767'
# teardown
# setup
# calling createPeerListener after calling stop produces error
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'listening 49770'
# teardown
# setup
# can call createPeerListener (pleaseConnect === false)
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'listening 49773'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'listening 49774'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 45 port must be in range
# teardown
# setup
# calling createPeerListener (pleaseConnect === true) with unknown peer is error
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'listening 49777'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'listening 49778'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'first connection'
2016-10-20 08:15:37 - WARN createPeerListener: ' Error: Unknown Peer
    at /Users/thali/Github/Thali_CordovaPlugin/thali/NextGeneration/mux/createPeerListener.js:255:23
    at Object.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:100:7)
    at Object.callNative (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/MockMobile.js:28:12)
    at /Users/thali/Github/Thali_CordovaPlugin/thali/NextGeneration/mux/createPeerListener.js:252:23
    at tryToUnwrap (/Users/thali/Github/Thali_CordovaPlugin/thali/node_modules/lie/lib/index.js:171:5)
    at tryCatch (/Users/thali/Github/Thali_CordovaPlugin/thali/node_modules/lie/lib/index.js:183:17)
    at safelyResolveThenable (/Users/thali/Github/Thali_CordovaPlugin/thali/node_modules/lie/lib/index.js:174:16)
    at new Promise (/Users/thali/Github/Thali_CordovaPlugin/thali/node_modules/lie/lib/index.js:32:5)
    at connectToRemotePeer (/Users/thali/Github/Thali_CordovaPlugin/thali/NextGeneration/mux/createPeerListener.js:247:10)
    at Server.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/thali/NextGeneration/mux/createPeerListener.js:619:29)
    at Server.g (events.js:160:16)
    at Server.emit (events.js:79:17)
    at net.js:989:10
    at process._tickCallback (node.js:917:13)'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'failedConnection'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'Recreating listener'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'createPeerListener creating new server'
ok 46 should get error
2016-10-20 08:15:37 - DEBUG createPeerListener: 'listening 49779'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'pleaseConnect= false'
# teardown
# setup
# calling createPeerListener twice with same peerIdentifier should return the same port
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'listening 49782'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'listening 49783'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 47 port values should be the same
# teardown
# setup
# createPeerListener - closing connection to native listener closes everything and triggers new listener
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'listening 49786'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'listening 49787'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'first connection'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'forward connection'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new mux'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
ok 48 Data should be of same length and content
2016-10-20 08:15:37 - DEBUG createNativeListener: 'incoming socket close'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'Recreating listener'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'listening 49792'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 49 same peer ID
ok 50 different ports
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
# teardown
# setup
# createPeerListener - closing mux closes listener and triggers a new listener
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'listening 49795'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'listening 49796'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'first connection'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'forward connection'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new mux'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
ok 51 Data should be of same length and content
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'incoming socket close'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'Recreating listener'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'listening 49801'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 52 same peer ID
ok 53 different ports
# teardown
# setup
# peerListener - forwardConnection, pleaseConnect === true - no native server
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating native server'
ok 54 Can call startUpdateAdvertisingAndListening without error
ok 55 Can call startListeningForAdvertisements without error
2016-10-20 08:15:37 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'listening 49804'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'listening 49805'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'first connection'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'forward connection'
2016-10-20 08:15:37 - WARN createPeerListener: ' Error: connect ECONNREFUSED
    at errnoException (net.js:837:11)
    at Object.afterConnect [as oncomplete] (net.js:829:19)'
ok 56 reason should be as expected
2016-10-20 08:15:37 - DEBUG createPeerListener: 'Recreating listener'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'listening 49807'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'pleaseConnect= false'
# teardown
# setup
# peerListener - forwardConnection, pleaseConnect === false - no native server
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating native server'
ok 57 Can call startUpdateAdvertisingAndListening without error
ok 58 Can call startListeningForAdvertisements without error
2016-10-20 08:15:37 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'listening 49810'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'listening 49811'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 59 peerPort should not be nativePort
2016-10-20 08:15:37 - DEBUG createPeerListener: 'first connection'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'forward connection'
2016-10-20 08:15:37 - WARN createPeerListener: ' Error: connect ECONNREFUSED
    at errnoException (net.js:837:11)
    at Object.afterConnect [as oncomplete] (net.js:829:19)'
ok 60 Should not get event until connection is made
ok 61 reason should be as expected
2016-10-20 08:15:37 - DEBUG createPeerListener: 'Recreating listener'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'failed incoming connection because of mux promise failure - undefined'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'listening 49814'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'pleaseConnect= false'
# teardown
# setup
# peerListener - forwardConnection, pleaseConnect === true - with native server
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating native server'
ok 62 Can call startUpdateAdvertisingAndListening without error
ok 63 Can call startListeningForAdvertisements without error
2016-10-20 08:15:37 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'listening 49817'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'listening 49818'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'first connection'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'forward connection'
ok 64 Should get spontaneous connection
ok 65 peerPort != nativePort
# teardown
# setup
# peerListener - forwardConnection, pleaseConnect === false - with native server
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating native server'
ok 66 Can call startUpdateAdvertisingAndListening without error
ok 67 Can call startListeningForAdvertisements without error
2016-10-20 08:15:37 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'listening 49822'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'listening 49823'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 68 peerPort != nativePort
2016-10-20 08:15:37 - DEBUG createPeerListener: 'first connection'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'forward connection'
ok 69 Should not get unexpected connection
# teardown
# setup
# peerListener - forwardConnection, pleaseConnect === false - with native server and data transfer
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'listening 49828'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'listening 49829'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'first connection'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'forward connection'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new mux'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
ok 70 Data should be of same length and content
ok 71 Data should be of same length and content
# teardown
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'mux close'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'incoming socket close'
2016-10-20 08:15:37 - WARN createPeerListener: ' Error: read ECONNRESET
    at errnoException (net.js:837:11)
    at TCP.onread (net.js:519:19)'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'Got error on outgoing to native - Error: read ECONNRESET'
# setup
# createPeerListener is idempotent
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating native server'
ok 72 Can call startUpdateAdvertisingAndListening without error
ok 73 Can call startListeningForAdvertisements without error
2016-10-20 08:15:37 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'listening 49835'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'listening 49836'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 74 Second call to existing peerListener returns existing port
# teardown
# setup
# createPeerListener - pleaseConnect === true, failed connection rejects promise
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating native server'
ok 75 Can call startUpdateAdvertisingAndListening without error
ok 76 Can call startListeningForAdvertisements without error
2016-10-20 08:15:37 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'listening 49839'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'listening 49840'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'first connection'
2016-10-20 08:15:37 - WARN createPeerListener: ' Error: a nasty error
    at /Users/thali/Github/Thali_CordovaPlugin/thali/NextGeneration/mux/createPeerListener.js:255:23
    at Object.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:589:7)
    at Object.callNative (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/MockMobile.js:28:12)
    at /Users/thali/Github/Thali_CordovaPlugin/thali/NextGeneration/mux/createPeerListener.js:252:23
    at tryToUnwrap (/Users/thali/Github/Thali_CordovaPlugin/thali/node_modules/lie/lib/index.js:171:5)
    at tryCatch (/Users/thali/Github/Thali_CordovaPlugin/thali/node_modules/lie/lib/index.js:183:17)
    at safelyResolveThenable (/Users/thali/Github/Thali_CordovaPlugin/thali/node_modules/lie/lib/index.js:174:16)
    at new Promise (/Users/thali/Github/Thali_CordovaPlugin/thali/node_modules/lie/lib/index.js:32:5)
    at connectToRemotePeer (/Users/thali/Github/Thali_CordovaPlugin/thali/NextGeneration/mux/createPeerListener.js:247:10)
    at Server.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/thali/NextGeneration/mux/createPeerListener.js:619:29)
    at Server.g (events.js:160:16)
    at Server.emit (events.js:79:17)
    at net.js:989:10
    at process._tickCallback (node.js:917:13)'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'failedConnection'
ok 77 got our failed connection
2016-10-20 08:15:37 - DEBUG createPeerListener: 'Recreating listener'
ok 78 failed connection should reject with error
2016-10-20 08:15:37 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'listening 49841'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'pleaseConnect= false'
# teardown
# setup
# createPeerListener - pleaseConnect === true, connection resolves promise
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating native server'
ok 79 Can call startUpdateAdvertisingAndListening without error
ok 80 Can call startListeningForAdvertisements without error
2016-10-20 08:15:37 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'listening 49844'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'listening 49845'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'first connection'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'forward connection'
ok 81 Should get spontaneous connection
ok 82 promise should resolve
# teardown
# setup
# peerListener - reverseConnection, pleaseConnect === true
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating native server'
ok 83 Can call startUpdateAdvertisingAndListening without error
ok 84 Can call startListeningForAdvertisements without error
2016-10-20 08:15:37 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'listening 49849'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'listening 49850'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'first connection'
2016-10-20 08:15:37 - WARN createPeerListener: 'was expecting a forward connection to be made'
ok 85 reason should be as expected
2016-10-20 08:15:37 - DEBUG createPeerListener: 'Recreating listener'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'listening 49851'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'pleaseConnect= false'
# teardown
# setup
# peerListener - reverseConnection, pleaseConnect === false - no incoming
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating native server'
ok 86 Can call startUpdateAdvertisingAndListening without error
ok 87 Can call startListeningForAdvertisements without error
2016-10-20 08:15:37 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'listening 49854'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'listening 49855'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 88 peerPort should not be nativePort
2016-10-20 08:15:37 - DEBUG createPeerListener: 'first connection'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'looking up mux for client port:  0'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'timed out waiting for incoming connection'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'reverse connection'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'looking up mux for client port:  0'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'no mux found'
ok 89 should not get event until connection is made
ok 90 reason should be as expected
2016-10-20 08:15:37 - DEBUG createPeerListener: 'Recreating listener'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'failed incoming connection because of mux promise failure - AssertionError: server._mux must exist by now'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'listening 49857'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'pleaseConnect= false'
# teardown
# setup
# peerListener - reverseConnection, pleaseConnect === false - with incoming
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating native server'
ok 91 Can call startUpdateAdvertisingAndListening without error
ok 92 Can call startListeningForAdvertisements without error
2016-10-20 08:15:37 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'listening 49860'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'listening 49861'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'first connection'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new mux'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'looking up mux for client port:  49863'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'reverse connection'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'looking up mux for client port:  49863'
ok 93 sent and received should be the same
# teardown
2016-10-20 08:15:37 - DEBUG createNativeListener: 'mux close'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'incoming socket close'
# setup
# peerListener - reverseConnection, pleaseConnect === false - no server
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating native server'
ok 94 Can call startUpdateAdvertisingAndListening without error
ok 95 Can call startListeningForAdvertisements without error
2016-10-20 08:15:37 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'listening 49866'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'listening 49867'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'first connection'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'looking up mux for client port:  49869'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new mux'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'reverse connection'
2016-10-20 08:15:37 - DEBUG createPeerListener: 'looking up mux for client port:  49869'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:15:37 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:15:37 - DEBUG createNativeListener: ' Error: connect ECONNREFUSED
    at errnoException (net.js:837:11)
    at Object.afterConnect [as oncomplete] (net.js:829:19)'
ok 96 should get routerPortConnectionFailed
2016-10-20 08:15:37 - DEBUG createNativeListener: 'stream close:'
# teardown
2016-10-20 08:15:37 - DEBUG createNativeListener: 'mux close'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'incoming socket close'
# setup
# createPeerListener - ask for new peer when we are at maximum and make sure we remove the right existing listener
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'listening 49873'
# teardown
# setup
# createPeerListener - ask for a new peer when we are not at maximum peers and make sure we do not remove any existing listeners
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'listening 49876'
# teardown
# setup
# createPeerListener - pleaseConnect = false - test timeout
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'listening 49879'
# teardown
# setup
# createPeerListener - pleaseConnect = true - test timeout
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'listening 49882'
# teardown
# setup
# createPeerListener - forward connection - wrong serverPort
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'listening 49885'
# teardown
# setup
# createPeerListener - forward connection - wrong clientPort
2016-10-20 08:15:37 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:37 - DEBUG createNativeListener: 'listening 49888'
# teardown
# setup
# createPeerListener - please connect = false, multiple connections out
2016-10-20 08:15:38 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:38 - DEBUG createNativeListener: 'listening 49891'
# teardown
# setup
# createPeerListener - please connect = false, multiple bi-directional connections
2016-10-20 08:15:38 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:38 - DEBUG createNativeListener: 'listening 49894'
# teardown
# setup
# createPeerListener - multiple parallel calls
2016-10-20 08:15:38 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:38 - DEBUG createNativeListener: 'listening 49897'
# teardown
# setup
# #_doImmediateSeqUpdate - server is not there
2016-10-20 08:15:38 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
ok 97 Got right error
# teardown
# setup
# #_doImmediateSeqUpdate - server accepts & closes connection
2016-10-20 08:15:38 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
ok 98 Got socket hang up
# teardown
# setup
# #_doImmediateSeqUpdate - server always returns 500
2016-10-20 08:15:38 - DEBUG localSeqManager: 'Got an error trying to update seq []'
ok 99 Got 500 as expected
# teardown
# setup
# #_doImmediateSeqUpdate - create new seq doc
ok 100 should be equal
ok 101 revs are equal
# teardown
# setup
# #_doImmediateSeqUpdate - doc exists, need to get rev and update
ok 102 should be equal
ok 103 revs are equal
# teardown
# setup
# #_doImmediateSeqUpdate - update seq three times
ok 104 should be equal
ok 105 revs are equal
ok 106 should be equal
ok 107 revs are equal
ok 108 should be equal
ok 109 revs are equal
# teardown
# setup
# #_doImmediateSeqUpdate - rev got changed under us
2016-10-20 08:15:38 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
ok 110 Our rev is old so we should fail
# teardown
# setup
# #_doImmediateSeqUpdate - fail if stop is called
ok 111 confirm stop caused failure
# teardown
# setup
# #_doImmediateSeqUpdate - stop after get but before put fails right
2016-10-20 08:15:38 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
ok 112 stop caused us to fail
ok 113 We specifically failed on a stop before put
# teardown
# setup
# #update - fail if stop is called
ok 114 failed due to stop
ok 115 failed due to stop
# teardown
# setup
# #update - set seq for first time
ok 116 should be equal
# teardown
# setup
# #update - Fail on bad seq value
2016-10-20 08:15:38 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
ok 117 Expected bad seq error
# teardown
# setup
# #update - do we cancel timer properly on an immediate?
ok 118 Different promises
ok 119 Timer was cancelled
ok 120 should be equal
# teardown
# setup
# #update - do we wait for blocked update
ok 121 One go and one blocked
ok 122 All blocked
ok 123 Still blocked
ok 124 should be equal
# teardown
# setup
# #update - test that we wait long enough
ok 125 We waited long enough
ok 126 should be equal
# teardown
# setup
# #update - test that we pick up new sequences while we wait
ok 127 Should have gotten same timer promise
ok 128 Still same timer promise
ok 129 We waited long enough
ok 130 should be equal
# teardown
# setup
# closeAll can close even when connections open
ok 131 not possible to connect to the server anymore
# teardown
# setup
# closeAll with promise
ok 132 not possible to connect to the server anymore
# teardown
# setup
# closeAll properly throws when closing a non open server with eatNotRunning set to false
ok 133 Got the right error
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
ok 134 the checkpointReached handler should be called once. Called 1 time(s)
# teardown
# setup
# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
# teardown
# setup
# test defaultDirectory
ok 135 should be equal
ok 136 should be equal
ok 137 should be equal
# teardown
# setup
# test defaultAdapter
ok 138 should be equal
ok 139 should be equal
ok 140 should be equal
ok 141 should be equal
ok 142 should be equal
ok 143 should be equal
ok 144 should be equal
ok 145 should be equal
# teardown
# setup
# enqueue and run in order
ok 146 firstPromise setTimeout
ok 147 firstPromise result
ok 148 firstPromise testValue
ok 149 secondPromise setTimeout
ok 150 secondPromise result
ok 151 secondPromise testValue
ok 152 thirdPromise in promise
ok 153 thirdPromise result
ok 154 thirdPromise testValue
# teardown
# setup
# enqueueAtTop and run backwards
ok 155 thirdPromise - first to run
ok 156 thirdPromise - in resolve
ok 157 secondPromise - second to run
ok 158 secondPromise - in catch
ok 159 firstPromise - third to run
ok 160 firstPromise - in then
ok 161 testing promises
# teardown
# setup
# mix enqueue and enqueueAtTop
ok 162 fourth
ok 163 fourth
ok 164 second
ok 165 secondPromise - in then
ok 166 first
ok 167 firstPromise - in catch
ok 168 third
ok 169 thirdPromise - in then
ok 170 testingPromises
# teardown
# setup
# queues handled independently
ok 171 all short operations completed before the long resolves
# teardown
# setup
# basic
ok 172 sane
# teardown
# setup
# another
ok 173 sane
# teardown
# setup
# test thali manager spies
2016-10-20 08:15:44 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
2016-10-20 08:15:44 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
2016-10-20 08:15:44 - DEBUG thaliManager: 'creating express pouchdb instance'
ok 174 expressPouchDB was called once
ok 175 expressPouchDB was called with 2 arguments
ok 176 expressPouchDB was called with 'PouchDB' as 1-st argument
ok 177 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
ok 178 PouchDB was called once
ok 179 PouchDB was called with 1 arguments
ok 180 PouchDB was called with 'dbName' as 1-st argument
ok 181 ThaliSendNotificationBasedOnReplication was called once
ok 182 ThaliSendNotificationBasedOnReplication was called with 4 arguments
ok 183 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
ok 184 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
ok 185 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
ok 186 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
ok 187 ThaliPullReplicationFromNotification was called once
ok 188 ThaliPullReplicationFromNotification was called with 4 arguments
ok 189 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
ok 190 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
ok 191 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
ok 192 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
ok 193 Salti was called once
ok 194 Salti was called with 4 arguments
ok 195 Salti was called with 'dbName' as 1-st argument
ok 196 Salti was called with 'acl' as 2-st argument
ok 197 Salti was called with 'thaliIdCallback' as 3-st argument
ok 198 Salti was called with 'options' as 4-st argument
2016-10-20 08:15:44 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-10-20 08:15:44 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-10-20 08:15:44 - DEBUG thaliManager: 'starting ThaliMobile'
2016-10-20 08:15:44 - DEBUG thaliMobileNativeWrapper: 'listening 49973'
2016-10-20 08:15:44 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:44 - DEBUG createNativeListener: 'listening 49974'
2016-10-20 08:15:44 - DEBUG thaliManager: 'start listening for advertisements'
2016-10-20 08:15:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-20 08:15:44 - DEBUG thaliManager: 'start update advertising and listening'
2016-10-20 08:15:44 - DEBUG thaliWifiInfrastructure: 'listening 49975'
2016-10-20 08:15:44 - DEBUG thaliWifiInfrastructure: 'listening 49977'
2016-10-20 08:15:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-10-20 08:15:44 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
ok 199 ThaliMobile.start was called once
ok 200 ThaliMobile.start was called with 3 arguments
ok 201 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
ok 202 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
ok 203 ThaliMobile.start was called with 'networkType' as 3-st argument
ok 204 ThaliMobile.startListeningForAdvertisements was called once
ok 205 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
ok 206 ThaliMobile.startUpdateAdvertisingAndListening was called once
ok 207 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
ok 208 ThaliSendNotificationBasedOnReplication.prototype.start was called once
ok 209 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
ok 210 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
ok 211 ThaliPullReplicationFromNotification.prototype.start was called once
ok 212 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
ok 213 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
2016-10-20 08:15:44 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-10-20 08:15:44 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-10-20 08:15:44 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-10-20 08:15:44 - DEBUG thaliManager: 'stopping advertising and listening'
2016-10-20 08:15:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-20 08:15:44 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-10-20 08:15:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-10-20 08:15:44 - DEBUG thaliManager: 'stopping ThaliMobile'
ok 214 ThaliMobile.stop was called once
ok 215 ThaliMobile.stop was called with 0 arguments
ok 216 ThaliMobile.stopListeningForAdvertisements was called once
ok 217 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
ok 218 ThaliMobile.stopAdvertisingAndListening was called once
ok 219 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
ok 220 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
ok 221 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
ok 222 ThaliPullReplicationFromNotification.prototype.stop was called once
ok 223 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
# teardown
# setup
# test thali manager multiple starts and stops
2016-10-20 08:15:44 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
2016-10-20 08:15:44 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
2016-10-20 08:15:44 - DEBUG thaliManager: 'creating express pouchdb instance'
ok 224 expressPouchDB was called once
ok 225 expressPouchDB was called with 2 arguments
ok 226 expressPouchDB was called with 'PouchDB' as 1-st argument
ok 227 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
ok 228 PouchDB was called once
ok 229 PouchDB was called with 1 arguments
ok 230 PouchDB was called with 'dbName' as 1-st argument
ok 231 ThaliSendNotificationBasedOnReplication was called once
ok 232 ThaliSendNotificationBasedOnReplication was called with 4 arguments
ok 233 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
ok 234 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
ok 235 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
ok 236 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
ok 237 ThaliPullReplicationFromNotification was called once
ok 238 ThaliPullReplicationFromNotification was called with 4 arguments
ok 239 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
ok 240 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
ok 241 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
ok 242 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
ok 243 Salti was called once
ok 244 Salti was called with 4 arguments
ok 245 Salti was called with 'dbName' as 1-st argument
ok 246 Salti was called with 'acl' as 2-st argument
ok 247 Salti was called with 'thaliIdCallback' as 3-st argument
ok 248 Salti was called with 'options' as 4-st argument
2016-10-20 08:15:44 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-10-20 08:15:44 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-10-20 08:15:44 - DEBUG thaliManager: 'starting ThaliMobile'
2016-10-20 08:15:44 - DEBUG thaliMobileNativeWrapper: 'listening 49978'
2016-10-20 08:15:44 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:44 - DEBUG createNativeListener: 'listening 49979'
2016-10-20 08:15:44 - DEBUG thaliManager: 'start listening for advertisements'
2016-10-20 08:15:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-20 08:15:44 - DEBUG thaliManager: 'start update advertising and listening'
2016-10-20 08:15:44 - DEBUG thaliWifiInfrastructure: 'listening 49980'
2016-10-20 08:15:44 - DEBUG thaliWifiInfrastructure: 'listening 49982'
2016-10-20 08:15:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-10-20 08:15:44 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
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
2016-10-20 08:15:44 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-10-20 08:15:44 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-10-20 08:15:44 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-10-20 08:15:44 - DEBUG thaliManager: 'stopping advertising and listening'
2016-10-20 08:15:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-20 08:15:44 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-10-20 08:15:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-10-20 08:15:44 - DEBUG thaliManager: 'stopping ThaliMobile'
ok 264 ThaliMobile.stop was called once
ok 265 ThaliMobile.stop was called with 0 arguments
ok 266 ThaliMobile.stopListeningForAdvertisements was called once
ok 267 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
ok 268 ThaliMobile.stopAdvertisingAndListening was called once
ok 269 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
ok 270 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
ok 271 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
ok 272 ThaliPullReplicationFromNotification.prototype.stop was called once
ok 273 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
2016-10-20 08:15:44 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-10-20 08:15:44 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-10-20 08:15:44 - DEBUG thaliManager: 'starting ThaliMobile'
2016-10-20 08:15:44 - DEBUG thaliMobileNativeWrapper: 'listening 49983'
2016-10-20 08:15:44 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:44 - DEBUG createNativeListener: 'listening 49984'
2016-10-20 08:15:44 - DEBUG thaliManager: 'start listening for advertisements'
2016-10-20 08:15:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-20 08:15:44 - DEBUG thaliManager: 'start update advertising and listening'
2016-10-20 08:15:44 - DEBUG thaliWifiInfrastructure: 'listening 49985'
2016-10-20 08:15:44 - DEBUG thaliWifiInfrastructure: 'listening 49987'
2016-10-20 08:15:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-10-20 08:15:44 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
2016-10-20 08:15:44 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-10-20 08:15:44 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-10-20 08:15:44 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-10-20 08:15:44 - DEBUG thaliManager: 'stopping advertising and listening'
2016-10-20 08:15:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-20 08:15:44 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-10-20 08:15:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-10-20 08:15:44 - DEBUG thaliManager: 'stopping ThaliMobile'
2016-10-20 08:15:44 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-10-20 08:15:44 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-10-20 08:15:44 - DEBUG thaliManager: 'starting ThaliMobile'
2016-10-20 08:15:44 - DEBUG thaliMobileNativeWrapper: 'listening 49988'
2016-10-20 08:15:44 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:44 - DEBUG createNativeListener: 'listening 49989'
2016-10-20 08:15:44 - DEBUG thaliManager: 'start listening for advertisements'
2016-10-20 08:15:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-20 08:15:44 - DEBUG thaliManager: 'start update advertising and listening'
2016-10-20 08:15:44 - DEBUG thaliWifiInfrastructure: 'listening 49990'
2016-10-20 08:15:44 - DEBUG thaliWifiInfrastructure: 'listening 49992'
2016-10-20 08:15:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-10-20 08:15:44 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
2016-10-20 08:15:44 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-10-20 08:15:44 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-10-20 08:15:44 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-10-20 08:15:44 - DEBUG thaliManager: 'stopping advertising and listening'
2016-10-20 08:15:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-20 08:15:44 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-10-20 08:15:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-10-20 08:15:44 - DEBUG thaliManager: 'stopping ThaliMobile'
2016-10-20 08:15:44 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-10-20 08:15:44 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-10-20 08:15:44 - DEBUG thaliManager: 'starting ThaliMobile'
2016-10-20 08:15:44 - DEBUG thaliMobileNativeWrapper: 'listening 49993'
2016-10-20 08:15:44 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:44 - DEBUG createNativeListener: 'listening 49994'
2016-10-20 08:15:44 - DEBUG thaliManager: 'start listening for advertisements'
2016-10-20 08:15:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-20 08:15:44 - DEBUG thaliManager: 'start update advertising and listening'
2016-10-20 08:15:44 - DEBUG thaliWifiInfrastructure: 'listening 49995'
2016-10-20 08:15:44 - DEBUG thaliWifiInfrastructure: 'listening 49997'
2016-10-20 08:15:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-10-20 08:15:44 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
ok 274 ThaliMobile.start was called once
ok 275 ThaliMobile.start was called with 3 arguments
ok 276 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
ok 277 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
ok 278 ThaliMobile.start was called with 'networkType' as 3-st argument
ok 279 ThaliMobile.startListeningForAdvertisements was called once
ok 280 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
ok 281 ThaliMobile.startUpdateAdvertisingAndListening was called once
ok 282 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
ok 283 ThaliSendNotificationBasedOnReplication.prototype.start was called once
ok 284 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
ok 285 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
ok 286 ThaliPullReplicationFromNotification.prototype.start was called once
ok 287 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
ok 288 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
2016-10-20 08:15:44 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-10-20 08:15:44 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-10-20 08:15:44 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-10-20 08:15:44 - DEBUG thaliManager: 'stopping advertising and listening'
2016-10-20 08:15:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-20 08:15:44 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-10-20 08:15:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-10-20 08:15:44 - DEBUG thaliManager: 'stopping ThaliMobile'
# teardown
# setup
# #startListeningForAdvertisements should fail if start not called
ok 289 specific error should be returned
# teardown
ok 290 error should be null
ok 291 error should be null
# setup
# #startUpdateAdvertisingAndListening should fail if start not called
ok 292 specific error should be returned
# teardown
ok 293 error should be null
ok 294 error should be null
# setup
# should be able to call #stopListeningForAdvertisements many times
2016-10-20 08:15:44 - DEBUG thaliMobileNativeWrapper: 'listening 49998'
2016-10-20 08:15:44 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:44 - DEBUG createNativeListener: 'listening 49999'
ok 295 error should be null
ok 296 error should be null
ok 297 error should be null
ok 298 error should be null
# teardown
ok 299 error should be null
ok 300 error should be null
# setup
# should be able to call #startListeningForAdvertisements many times
2016-10-20 08:15:44 - DEBUG thaliMobileNativeWrapper: 'listening 50000'
2016-10-20 08:15:44 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:44 - DEBUG createNativeListener: 'listening 50001'
2016-10-20 08:15:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 301 error should be null
ok 302 error should be null
ok 303 error should be null
ok 304 error should be null
# teardown
2016-10-20 08:15:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-10-20 08:15:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 305 error should be null
ok 306 error should be null
# setup
# should be able to call #startUpdateAdvertisingAndListening many times
2016-10-20 08:15:44 - DEBUG thaliMobileNativeWrapper: 'listening 50002'
2016-10-20 08:15:44 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:44 - DEBUG createNativeListener: 'listening 50003'
2016-10-20 08:15:44 - DEBUG thaliWifiInfrastructure: 'listening 50004'
2016-10-20 08:15:44 - DEBUG thaliWifiInfrastructure: 'listening 50006'
2016-10-20 08:15:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 307 error should be null
ok 308 error should be null
ok 309 error should be null
ok 310 error should be null
# teardown
2016-10-20 08:15:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-10-20 08:15:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 311 error should be null
ok 312 error should be null
# setup
# should be able to call #stopAdvertisingAndListening many times
2016-10-20 08:15:44 - DEBUG thaliMobileNativeWrapper: 'listening 50007'
2016-10-20 08:15:44 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:44 - DEBUG createNativeListener: 'listening 50008'
ok 313 error should be null
ok 314 error should be null
ok 315 error should be null
ok 316 error should be null
# teardown
ok 317 error should be null
ok 318 error should be null
# setup
# #start - Causing native or wifi to fail will cause a promise reject 
2016-10-20 08:15:44 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
ok 319 This should not cause wifi to fail
ok 320 native router should be bad
# teardown
ok 321 error should be null
ok 322 error should be null
# setup
# #start should fail if called twice in a row
2016-10-20 08:15:44 - DEBUG thaliMobileNativeWrapper: 'listening 50009'
2016-10-20 08:15:44 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:44 - DEBUG createNativeListener: 'listening 50010'
ok 323 first call should succeed
ok 324 first call should succeed
ok 325 specific error should be returned
# teardown
ok 326 error should be null
ok 327 error should be null
# setup
# does not emit duplicate discoveryAdvertisingStateUpdate
2016-10-20 08:15:44 - DEBUG thaliMobileNativeWrapper: 'listening 50011'
2016-10-20 08:15:44 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:44 - DEBUG createNativeListener: 'listening 50012'
2016-10-20 08:15:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-20 08:15:44 - DEBUG thaliWifiInfrastructure: 'listening 50013'
2016-10-20 08:15:44 - DEBUG thaliWifiInfrastructure: 'listening 50015'
2016-10-20 08:15:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
ok 328 called only once
ok 329 discovery state matches
ok 330 advertising state matches
# teardown
2016-10-20 08:15:44 - INFO thaliMobile: 'Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}'
2016-10-20 08:15:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-10-20 08:15:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-10-20 08:15:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-20 08:15:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 331 error should be null
ok 332 error should be null
# setup
# does not send duplicate availability changes
ok 333 should be called once
ok 334 should not have been called more than once
# teardown
ok 335 error should be null
ok 336 error should be null
# setup
# can get the network status
ok 337 network status should have certain non-empty properties
# teardown
ok 338 error should be null
ok 339 error should be null
# setup
# wifi peer is marked unavailable if announcements stop
2016-10-20 08:15:44 - DEBUG thaliMobileNativeWrapper: 'listening 50016'
2016-10-20 08:15:44 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:44 - DEBUG createNativeListener: 'listening 50017'
2016-10-20 08:15:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 340 peer should be available
ok 341 peer should become unavailable
# teardown
2016-10-20 08:15:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 342 error should be null
ok 343 error should be null
# setup
# native peer should be removed if no availability updates were received during availability timeout
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'listening 50018'
2016-10-20 08:15:46 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:46 - DEBUG createNativeListener: 'listening 50019'
ok 344 peer is available
ok 345 peer is not availabel because it was too silent
# teardown
ok 346 error should be null
ok 347 error should be null
# setup
# peerAvailabilityChanged - peer added/removed to/from cache (native)
ok 348 we have not added peer to the cache yet
ok 349 peer should be available
ok 350 cache contains native peer
ok 351 peer should be unavailable
ok 352 peer has been removed from cache
# teardown
ok 353 error should be null
ok 354 error should be null
# setup
# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
ok 355 we have not added peer to the cache yet
ok 356 peer should be available
ok 357 cache contains wifi peer
ok 358 peer should be unavailable
ok 359 peer has been removed from cache
# teardown
ok 360 error should be null
ok 361 error should be null
# setup
# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
ok 362 first peer is available
ok 363 second peer is available
ok 364 first and second peers are different
# teardown
ok 365 error should be null
ok 366 error should be null
# setup
# native available - new peer is cached
ok 367 should not be in cache at start
ok 368 peer is available
# teardown
ok 369 error should be null
ok 370 error should be null
# setup
# native available - peer with same port and different generation is cached (BLUETOOTH)
ok 371 peer should be available
ok 372 peer should be available
ok 373 peer should be available
# teardown
ok 374 error should be null
ok 375 error should be null
# setup
# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
ok 376 peer should be available
ok 377 peer should be available
# teardown
ok 378 error should be null
ok 379 error should be null
# setup
# native available - peer with greater generation is cached (MPCF)
2016-10-20 08:15:46 - DEBUG SimpleThaliTape: 'test was skipped, name: 'native available - peer with greater generation is cached (MPCF)''
# teardown
ok 380 error should be null
ok 381 error should be null
# setup
# native available - peer with same or older generation is ignored (MPCF)
2016-10-20 08:15:46 - DEBUG SimpleThaliTape: 'test was skipped, name: 'native available - peer with same or older generation is ignored (MPCF)''
# teardown
ok 382 error should be null
ok 383 error should be null
# setup
# native unavailable - new peer is ignored
ok 384 NOT IMPLEMENTED # SKIP
# teardown
ok 385 error should be null
ok 386 error should be null
# setup
# native unavailable - cached peer is removed
ok 387 NOT IMPLEMENTED # SKIP
# teardown
ok 388 error should be null
ok 389 error should be null
# setup
# networkChanged - fires peerAvailabilityChanged event for wifi peers
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'listening 50020'
2016-10-20 08:15:46 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:46 - DEBUG createNativeListener: 'listening 50021'
ok 390 first peer is expected to be available
ok 391 second peer is expected to be available
ok 392 peer became unavailable
ok 393 it was wifi peer
# teardown
ok 394 error should be null
ok 395 error should be null
# setup
# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'listening 50022'
2016-10-20 08:15:46 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:46 - DEBUG createNativeListener: 'listening 50023'
ok 396 first peer is expected to be available
ok 397 second peer is expected to be available
ok 398 peer became unavailable
ok 399 it was a native peer
# teardown
ok 400 error should be null
ok 401 error should be null
# setup
# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
2016-10-20 08:15:46 - DEBUG SimpleThaliTape: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''
# teardown
ok 402 error should be null
ok 403 error should be null
# setup
# multiconnect failure - new peer is ignored (MPCF)
2016-10-20 08:15:46 - DEBUG SimpleThaliTape: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
# teardown
ok 404 error should be null
ok 405 error should be null
# setup
# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
2016-10-20 08:15:46 - DEBUG SimpleThaliTape: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
# teardown
ok 406 error should be null
ok 407 error should be null
# setup
# newAddressPort field (TCP_NATIVE)
ok 408 peer discovered first time does not have new address
ok 409 address has not been changed
ok 410 new port handled correctly
ok 411 new host handled correctly
ok 412 newAddressPort is null for unavailable peers
# teardown
ok 413 error should be null
ok 414 error should be null
# setup
# newAddressPort field (BLUETOOTH)
ok 415 peer discovered first time does not have new address
ok 416 address has not been changed
ok 417 new port handled correctly
ok 418 newAddressPort is null for unavailable peers
# teardown
ok 419 error should be null
ok 420 error should be null
# setup
# newAddressPort field (MPCF)
2016-10-20 08:15:46 - DEBUG SimpleThaliTape: 'test was skipped, name: 'newAddressPort field (MPCF)''
# teardown
ok 421 error should be null
ok 422 error should be null
# setup
# newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)
ok 423 NOT IMPLEMENTED # SKIP
# teardown
ok 424 error should be null
ok 425 error should be null
# setup
# network changes emitted correctly
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'listening 50024'
2016-10-20 08:15:46 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:46 - DEBUG createNativeListener: 'listening 50025'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
ok 426 wifi is off
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
ok 427 wifi is on
# teardown
ok 428 error should be null
ok 429 error should be null
# setup
# network changes not emitted in stopped state
ok 430 event was not emitted
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-20 08:15:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-20 08:15:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
# teardown
ok 431 error should be null
ok 432 error should be null
# setup
# calls correct starts when network changes
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'listening 50026'
2016-10-20 08:15:46 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:46 - DEBUG createNativeListener: 'listening 50027'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 433 specific error expected
2016-10-20 08:15:46 - DEBUG thaliWifiInfrastructure: 'listening 50029'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
ok 434 specific error expected
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-20 08:15:46 - INFO thaliMobile: 'Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":true,"advertisingActive":true}'
2016-10-20 08:15:46 - DEBUG thaliWifiInfrastructure: 'listening 50030'
ok 435 startListeningForAdvertisements should have been called
ok 436 startUpdateAdvertisingAndListening should have been called
# teardown
2016-10-20 08:15:46 - INFO thaliMobile: 'Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}'
2016-10-20 08:15:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-10-20 08:15:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 437 error should be null
ok 438 error should be null
# setup
# Can call start/stopListeningForAdvertisements
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 439 Can call startListeningForAdvertisements without error
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 440 Can call stopListeningForAdvertisements without error
# teardown
ok 441 Should be able to call stopListeningForAdvertisements in teardown
ok 442 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Calling startListeningForAdvertisements twice is NOT an error
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 443 Can call startListeningForAdvertisements without error
ok 444 Can call startListeningForAdvertisements twice without error
# teardown
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 445 Should be able to call stopListeningForAdvertisements in teardown
ok 446 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Calling stopListeningForAdvertisements without calling start is NOT an error
ok 447 Can call stopListeningForAdvertisements without error
ok 448 Can call stopListeningForAdvertisements without error
# teardown
ok 449 Should be able to call stopListeningForAdvertisements in teardown
ok 450 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Can call start/stopUpdateAdvertisingAndListening
2016-10-20 08:15:46 - DEBUG thaliWifiInfrastructure: 'listening 50032'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 451 Can call startUpdateAdvertisingAndListening without error
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 452 Can call stopAdvertisingAndListening without error
# teardown
ok 453 Should be able to call stopListeningForAdvertisements in teardown
ok 454 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Calling startUpdateAdvertisingAndListening twice is NOT an error
2016-10-20 08:15:46 - DEBUG thaliWifiInfrastructure: 'listening 50034'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 455 Can call startUpdateAdvertisingAndListening without error
ok 456 Can call startUpdateAdvertisingAndListening twice without error
# teardown
ok 457 Should be able to call stopListeningForAdvertisements in teardown
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 458 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
ok 459 Can call startUpdateAdvertisingAndListening without error
ok 460 Can call stopAdvertisingAndListening without error
# teardown
ok 461 Should be able to call stopListeningForAdvertisements in teardown
ok 462 Should be able to call stopAdvertisingAndListening in teardown
# setup
# cannot call connect when start listening for advertisements is not active
ok 463 got right error
# teardown
ok 464 Should be able to call stopListeningForAdvertisements in teardown
ok 465 Should be able to call stopAdvertisingAndListening in teardown
# setup
# #startListeningForAdvertisements should fail if start not called
ok 466 specific error should be returned
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-20 08:15:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 467 must be stopped
# setup
# #startUpdateAdvertisingAndListening should fail if start not called
ok 468 specific error should be returned
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-20 08:15:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 469 must be stopped
# setup
# should be able to call #stopListeningForAdvertisements many times
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'listening 50035'
2016-10-20 08:15:46 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:46 - DEBUG createNativeListener: 'listening 50036'
ok 470 no errors
ok 471 still no errors
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-20 08:15:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 472 must be stopped
# setup
# should be able to call #startListeningForAdvertisements many times
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'listening 50037'
2016-10-20 08:15:46 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:46 - DEBUG createNativeListener: 'listening 50038'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 473 no errors
ok 474 still no errors
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-20 08:15:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 475 must be stopped
# setup
# should be able to call #startUpdateAdvertisingAndListening many times
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'listening 50039'
2016-10-20 08:15:46 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:46 - DEBUG createNativeListener: 'listening 50040'
2016-10-20 08:15:46 - DEBUG thaliWifiInfrastructure: 'listening 50042'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 476 no errors
ok 477 still no errors
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-20 08:15:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 478 must be stopped
# setup
# should be able to call #stopAdvertisingAndListening many times
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'listening 50043'
2016-10-20 08:15:46 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:46 - DEBUG createNativeListener: 'listening 50044'
ok 479 no errors
ok 480 still no errors
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-20 08:15:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 481 must be stopped
# setup
# can get the network status before starting
ok 482 network status should have certain non-empty properties
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-20 08:15:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 483 must be stopped
# setup
# error returned with bad router
2016-10-20 08:15:46 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 484 specific error expected
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-20 08:15:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 485 must be stopped
# setup
# all services are stopped when we call stop
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'listening 50045'
2016-10-20 08:15:46 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:46 - DEBUG createNativeListener: 'listening 50046'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-20 08:15:46 - DEBUG thaliWifiInfrastructure: 'listening 50048'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
ok 486 connection to servers manager should succeed after starting
2016-10-20 08:15:46 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:15:46 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:15:46 - DEBUG createNativeListener: 'new mux'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
ok 487 connection to router server should succeed after starting
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-20 08:15:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-10-20 08:15:46 - DEBUG createNativeListener: 'incoming socket close'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 488 is stopped after calling stop
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
ok 489 connection to servers manager should fail after stopping
ok 490 connection to router server should fail after stopping
# teardown
ok 491 must be stopped
# setup
# make sure terminateConnection is properly hooked up
ok 492 called with right arguments
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-20 08:15:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 493 must be stopped
# setup
# make sure terminateListener is properly hooked up
ok 494 called with right arguments
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-20 08:15:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 495 must be stopped
# setup
# make sure we actually call kill connections properly
ok 496 specific error expected
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-20 08:15:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 497 must be stopped
# setup
# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'listening 50053'
2016-10-20 08:15:46 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:46 - DEBUG createNativeListener: 'listening 50054'
2016-10-20 08:15:46 - INFO thaliMobileNativeWrapper: 'routerPortConnectionFailed - {"routerPort":50053,"error":{}}'
ok 498 failure reason is as expected
ok 499 error description is as expected
ok 500 must be stopped
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-20 08:15:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 501 must be stopped
# setup
# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'listening 50055'
2016-10-20 08:15:46 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:46 - DEBUG createNativeListener: 'listening 50056'
ok 502 peerIdentifier matches
ok 503 error description matches
ok 504 connection type is tcp
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-20 08:15:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 505 must be stopped
# setup
# we successfully receive and replay discoveryAdvertisingStateUpdate
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'listening 50057'
2016-10-20 08:15:46 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:46 - DEBUG createNativeListener: 'listening 50058'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 506 discoveryActive matches
ok 507 advertisingActive matches
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 508 discoveryActive matches
ok 509 advertisingActive matches
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'listening 50059'
2016-10-20 08:15:46 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:46 - DEBUG createNativeListener: 'listening 50060'
2016-10-20 08:15:46 - DEBUG thaliWifiInfrastructure: 'listening 50062'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 510 discoveryActive matches
ok 511 advertisingActive matches
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 512 discoveryActive matches
ok 513 advertisingActive matches
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'listening 50063'
2016-10-20 08:15:46 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:15:46 - DEBUG createNativeListener: 'listening 50064'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-20 08:15:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-20 08:15:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 514 must be stopped
# setup
# Test BEACONS_RETRIEVED_AND_PARSED locally
ok 515 peerIdentifier should be identifier
ok 516 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 517 good beacon
ok 518 good preAmble
ok 519 public keys match!
ok 520 must return null after successful call
ok 521 Once start returns the action should be in KILLED state
# teardown
# setup
# Test HTTP_BAD_RESPONSE locally
ok 522 Response should be HTTP_BAD_RESPONSE
ok 523 must return null after successful call
# teardown
# setup
# Test NETWORK_PROBLEM locally
ok 524 Response should be NETWORK_PROBLEM
ok 525 reject reason should be: Could not establish TCP connection
# teardown
# setup
# Call the start two times
ok 526 Call start once
ok 527 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 528 must return null after successful call.
# teardown
# setup
# Call the kill before calling the start
ok 529 Should be Killed
ok 530 Start after killed
# teardown
# setup
# Call the kill immediately after the start
ok 531 Should be KILLED
ok 532 must return null after successful kill
# teardown
# setup
# Call the kill while waiting a response from the server
ok 533 Should be KILLED
ok 534 must return null after successful kill
# teardown
# setup
# Test to exceed the max content size locally
ok 535 HTTP_BAD_RESPONSE should be response when content size is exceeded
ok 536 must return null after successful call
# teardown
# setup
# Close the server socket while the client is waiting a response from the server. Local test.
ok 537 Should be NETWORK_PROBLEM caused closing server socket
ok 538 Should be Could not establish TCP connection
# teardown
# setup
# Close the client socket while the client is waiting a response from the server. Local test.
ok 539 Should be NETWORK_PROBLEM caused closing client socket
ok 540 Should be Could not establish TCP connection
# teardown
# setup
# #generatePreambleAndBeacons bad args
ok 541 publicKeysToNotify cannot be null
ok 542 ecdh for local device cannot be null
ok 543 milliseconds cannot be less than 0
ok 544 milliseconds cannot be 0
ok 545 milliseconds cannot be greater than one_day
# teardown
# setup
# #generatePreambleAndBeacons empty keys to notify
ok 546 should be equal
# teardown
# setup
# #generatePreambleAndBeacons multiple keys to notify
ok 547 should be equal
ok 548 should be equal
ok 549 (unnamed assert)
ok 550 should be equal
# teardown
# setup
# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
ok 551 should throw
# teardown
# setup
# #parseBeacons invalid expiration in beaconStreamWithPreAmble
ok 552 Preamble expiration must be a 64 bit integer
# teardown
# setup
# #parseBeacons expiration out of range lower
ok 553 Expiration out of range
# teardown
# setup
# #parseBeacons expiration out of range lower
ok 554 Expiration out of range
# teardown
# setup
# #parseBeacons no beacons returns null
ok 555 should be equal
# teardown
# setup
# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
ok 556 Malformed encrypted beacon key ID
# teardown
# setup
# #parseBeacons addressBookCallback fails decrypt
ok 557 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns no matches
ok 558 should be equal
ok 559 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns spurious match
ok 560 should be equal
ok 561 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns public key
ok 562 right number of calls to address book
ok 563 good preAmble
ok 564 good unencryptedKeyId
ok 565 good beacon
# teardown
# setup
# validate generatePskIdentityField
ok 566 decoded buffers match
# teardown
# setup
# validate generatePskSecret
ok 567 secrets match
# teardown
# setup
# validate generatePskSecrets
ok 568 Matching numbers
ok 569 We have an entry!
ok 570 keys match
ok 571 secrets match
ok 572 We have an entry!
ok 573 keys match
ok 574 secrets match
ok 575 We have an entry!
ok 576 keys match
ok 577 secrets match
# teardown
# setup
# validate generateBeaconStreamAndSecrets
ok 578 Streams have same length
ok 579 matching size
ok 580 keys match
ok 581 secrets match
# teardown
# setup
# Add two Peers.
ok 582 should be equal
ok 583 should be equal
ok 584 should be equal
ok 585 should be equal
ok 586 should be equal
# teardown
# setup
# TCP_NATIVE peer loses DNS
ok 587 should be equal
ok 588 should be equal
# teardown
# setup
# Received beacons with no values for us
ok 589 entry exists
ok 590 entry is resolved
# teardown
# setup
# Resolves an action locally
ok 591 Host address must match
ok 592 suggestedTCPTimeout must match
ok 593 connectionType must match
ok 594 portNumber must match
# teardown
# setup
# Resolves an action locally using ThaliPeerPoolDefault
ok 595 Host address must match
ok 596 suggestedTCPTimeout must match
ok 597 connectionType must match
ok 598 portNumber must match
# teardown
# setup
# Action fails because of a bad hostname.
ok 599 action should be resolved with NETWORK_PROBLEM error
ok 600 action should be resolved with NETWORK_PROBLEM error
ok 601 action should be resolved with NETWORK_PROBLEM error
ok 602 action should be resolved with NETWORK_PROBLEM error
ok 603 correct number of requests
ok 604 correct number of failures
ok 605 correct final peer state
# teardown
# setup
# hostaddress is removed when the action is running. 
ok 606 should be equal
# teardown
# setup
# Client to server request locally
ok 607 secrets are equal
ok 608 Public key matches with the server key
ok 609 Host address must match
ok 610 suggestedTCPTimeout must match
ok 611 connectionType must match
ok 612 portNumber must match
# teardown
# setup
# Test ThaliPskMapCache clean and expiration
ok 613 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
ok 614 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
ok 615 All entries should be expired after 1 second
# teardown
# setup
# Test ThaliPskMapCache getSecret and getPublic
ok 616 All keys need to be available in the cache
ok 617 All entries should be expired after 1 second
# teardown
# setup
# Test ThaliPskMapCache multiple entries
ok 618 Size of the cache should be 2
ok 619 Cache doesn't contain dictionary1
ok 620 Size of the cache should be 1
ok 621 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
# setup
# Start and stop ThaliNotificationServer
ok 622 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
ok 623 ThaliMobile.StopAdvertisingAndListeningshould be called once
# teardown
# setup
# Pass an empty array to ThaliNotificationServer.start
ok 624 StartUpdateAdvertisingAndListening should not be called
ok 625 ThaliMobile.StopAdvertisingAndListening should be called once
ok 626 no error
ok 627 should be 204
# teardown
# setup
# Pass a string to ThaliNotificationServer.start
ok 628 StartUpdateAdvertisingAndListening should not be called
# teardown
# setup
# Pass an empty parameter to ThaliNotificationServer.start
ok 629 StartUpdateAdvertisingAndListening should not be called
# teardown
# setup
# Make an HTTP request to /NotificationBeacons
ok 630 no error
ok 631 should be 200
ok 632 should be equal
ok 633 should be equal
ok 634 (unnamed assert)
ok 635 no error
ok 636 should be 204
# teardown
# setup
# Make an HTTP request to /NotificationBeacons (no keys)
ok 637 error should be null
ok 638 should be 204
# teardown
# setup
# Make an HTTP request to /NotificationBeaconsbefore calling start
ok 639 should be 404
# teardown
# setup
# #testThaliPeerAction - test getters
ok 640 getPeerIdentifier
ok 641 getConnectionType
ok 642 getActionType
ok 643 getActionState
ok 644 getPskIdentity
ok 645 getPskKey
# teardown
# setup
# #testThaliPeerAction - start and kill
ok 646 initial state
ok 647 after start
ok 648 after kill
# teardown
# setup
# #testThaliPeerAction - double start
ok 649 should be equal
# teardown
# setup
# #testThaliPeerAction - start after kill
ok 650 clean kill
ok 651 should be equal
# teardown
# setup
# #testThaliPeerAction - make sure ids are unique
ok 652 should not be equal
# teardown
# setup
# Test PeerConnectionInformation basics
ok 653 connection type works
ok 654 getHostAddress works
ok 655 getPortNumber works
ok 656 getSuggestedTCPTimeout works
# teardown
# setup
# Test PeerDictionary basic functionality
ok 657 Entry counter must be 1
ok 658 Size must be 1
ok 659 Entry counter must be 2
ok 660 Size must be 2
ok 661 Entry2 should not be found
ok 662 Size must be 1
ok 663 Size must be 0
# teardown
# setup
# Test PeerDictionary with multiple entries.
ok 664 Size must be100
ok 665 Entries between 20 and MAXSIZE + 20 should exist
ok 666 WAITING state entry should not be removed
# teardown
# setup
# RESOLVED entries are removed before WAITING state entry.
ok 667 Entries between 6 and MAXSIZE + 4 should exist
ok 668 Size should be MAXSIZE
ok 669 Size should be MAXSIZE+6
# teardown
# setup
# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
ok 670 WAITING state entry should not be removed
ok 671 Waiting entries between 6 and MAXSIZE + 4 should exist
ok 672 Size should be MAXSIZE
ok 673 entryCounter should be MAXSIZE+6
# teardown
# setup
# When CONTROLLED_BY_POOL entry is removed and kill is called.
ok 674 Kill should be called once
ok 675 Size should be 100
# teardown
# setup
# #ThaliPeerPoolDefault - single action
ok 676 is an agent
ok 677 enqueue is fine
ok 678 Everything should be off the queue
# teardown
# setup
# #ThaliPeerPoolDefault - multiple actions
ok 679 is an agent
ok 680 first enqueue is fine
ok 681 is an agent
ok 682 second enqueue is fine
ok 683 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 684 Queue is empty
# teardown
# setup
# #ThaliPeerPoolDefault - PSK Pool works
ok 685 is an agent
ok 686 good enqueue
ok 687 Identity should match
ok 688 Got expected response
ok 689 Got psk call back
# teardown
# setup
# #ThaliPeerPoolDefault - stop
ok 690 is an agent
ok 691 enqueue worked
ok 692 is an agent
ok 693 enqueue 2 worked
ok 694 enqueue is not available when stopped
ok 695 start action is killed
ok 696 killed action is still killed
ok 697 inQueue is empty
# teardown
# setup
# #ThaliPeerPoolInterface - make sure that start verifies queue length
ok 698 good start
ok 699 good enqueue
ok 700 queue is not empty
# teardown
# setup
# #ThaliPeerPoolInterface - bad enqueues
ok 701 null arg
ok 702 wrong arg type
ok 703 wrong arg type
# teardown
# setup
# #ThaliPeerPoolInterface - do not allow same object type
ok 704 good enqueue
ok 705 already enqueued
# teardown
# setup
# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
ok 706 good enqueue
ok 707 2nd good enqueue
ok 708 we are in the pool
ok 709 We are out of the pool
ok 710 Action was killed
ok 711 The original kill was called too
ok 712 second item is still in queue
# teardown
# setup
# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
ok 713 good enqueue
ok 714 first kill
ok 715 second NOOP kill
# teardown
# setup
# #ThaliPeerPoolInterface - make sure that stop removes all actions
ok 716 1st good enqueue
ok 717 2nd good enqueue
ok 718 1st action is in the pool
ok 719 2nd action is in the pool
ok 720 1st action is out of the pool
ok 721 2st action is out of the pool
ok 722 pool is empty
# teardown
# setup
# Make sure peerDictionaryKey is reasonable
ok 723 equal keys
ok 724 not equal connection type
ok 725 same connection type, different buffer
# teardown
# setup
# Make sure start works
2016-10-20 08:16:01 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 726 First start and on called correctly
# teardown
# setup
# Make sure stop works
ok 727 second cleared dictionary
2016-10-20 08:16:01 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 728 First start and on called correctly
ok 729 First stop and removeListener called correctly
ok 730 first action kill called
ok 731 second action kill called
ok 732 first cleared dictionary
ok 733 first cleared pool
ok 734 second cleared dictionary
ok 735 second cleared pool
# teardown
# setup
# Simple peer event
2016-10-20 08:16:01 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 736 listener has been set
ok 737 peer dictionary has expected number of entries
ok 738 Dictionary and pool have same action
ok 739 ads match
ok 740 PouchDB matches
ok 741 DB Names match
ok 742 public keys match
ok 743 peer dictionary has expected number of entries
ok 744 Dictionary and pool have same action
ok 745 ads match
ok 746 PouchDB matches
ok 747 DB Names match
ok 748 public keys match
ok 749 start called once
ok 750 One entry left
ok 751 Dictionary and pool have same action
ok 752 Start never called
ok 753 Kill called once
ok 754 no entries left
ok 755 Third action is dead
ok 756 peer dictionary has expected number of entries
ok 757 Dictionary and pool have same action
ok 758 ads match
ok 759 PouchDB matches
ok 760 DB Names match
ok 761 public keys match
# teardown
# setup
# Server is not there
2016-10-20 08:16:01 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
ok 762 right error
# teardown
# setup
# Server accepts & closes connection
2016-10-20 08:16:01 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
ok 763 right error
# teardown
# setup
# Server always returns 500
2016-10-20 08:16:01 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
ok 764 Got error as expected
# teardown
# setup
# Server always returns 401
2016-10-20 08:16:01 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
ok 765 Got error as expected
# teardown
# setup
# Server always returns 403
2016-10-20 08:16:01 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
ok 766 Got error as expected
# teardown
# setup
# Make sure docs replicate
2016-10-20 08:16:01 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
2016-10-20 08:16:01 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
ok 767 should be equal
ok 768 All tests passed!
# teardown
# setup
# Do nothing and make sure we time out
2016-10-20 08:16:02 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
ok 769 action should be killed
ok 770 Error should be timed out
ok 771 No doc found
# teardown
# setup
# Do something and make sure we time out
2016-10-20 08:16:04 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
2016-10-20 08:16:04 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
ok 772 should be equal
ok 773 action should be killed
ok 774 Error should be timed out
# teardown
# setup
# Start replicating and then catch error when server goes
ok 775 socket hung up
# teardown
# setup
# compareBufferArrays
ok 776 should throw
ok 777 should throw
ok 778 (unnamed assert)
ok 779 (unnamed assert)
ok 780 (unnamed assert)
ok 781 (unnamed assert)
ok 782 (unnamed assert)
# teardown
# setup
# Call start twice and get error
ok 783 should throw
# teardown
# setup
# Start and make sure it runs
# teardown
# setup
# Make sure getTimeWhenRun is right after start
ok 784 (unnamed assert)
# teardown
# setup
# Make sure getTimeWhenRun is -1 after function is called
ok 785 should be equal
# teardown
# setup
# Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
ok 786 should be equal
ok 787 should be equal
ok 788 should throw
# teardown
# setup
# Test TransientState
ok 789 should throw
ok 790 should throw
ok 791 should be equal
ok 792 should be equal
ok 793 should be equal
ok 794 should be equal
ok 795 (unnamed assert)
ok 796 (unnamed assert)
# teardown
# setup
# No peers and empty database
ok 797 verify failed
ok 798 constructor called once
ok 799 constructor called with right args
ok 800 match start arg
ok 801 start called once
ok 802 stop called once
ok 803 stop after start
# teardown
# setup
# One peer and empty DB
ok 804 verify failed
ok 805 constructor called once
ok 806 constructor called with right args
ok 807 match start arg
ok 808 start called once
ok 809 stop called once
ok 810 stop after start
2016-10-20 08:16:06 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# One peer with _Local set behind current seq
ok 811 verify failed
ok 812 constructor called once
ok 813 constructor called with right args
ok 814 match start arg
ok 815 start called once
ok 816 stop called once
ok 817 stop after start
2016-10-20 08:16:06 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# One peer with _Local set equal to current seq
ok 818 verify failed
ok 819 constructor called once
ok 820 constructor called with right args
ok 821 match start arg
ok 822 start called once
ok 823 stop called once
ok 824 stop after start
2016-10-20 08:16:06 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# One peer with _Local set ahead of current seq (and no this should not happen)
ok 825 verify failed
ok 826 constructor called once
ok 827 constructor called with right args
ok 828 match start arg
ok 829 start called once
ok 830 stop called once
ok 831 stop after start
2016-10-20 08:16:06 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# Three peers, one not in DB, one behind and one ahead
ok 832 verify failed
ok 833 constructor called once
ok 834 constructor called with right args
ok 835 match start arg
ok 836 start called once
ok 837 stop called once
ok 838 stop after start
2016-10-20 08:16:06 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# More than maximum peers, make sure we only send maximum allowed
ok 839 verify failed
ok 840 constructor called once
ok 841 constructor called with right args
ok 842 match start arg
ok 843 start called once
ok 844 stop called once
ok 845 stop after start
2016-10-20 08:16:06 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# two peers with empty DB, update the doc
2016-10-20 08:16:06 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 846 verify failed
ok 847 constructor called once
ok 848 constructor called with right args
ok 849 last start before stop
ok 850 empty first start
ok 851 full second start
ok 852 only 2 timers
2016-10-20 08:16:06 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# add doc and make sure tokens refresh when they expire
2016-10-20 08:16:06 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
2016-10-20 08:16:06 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
2016-10-20 08:16:07 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 853 verify failed
ok 854 constructor called once
ok 855 constructor called with right args
ok 856 start before stop
ok 857 We got at least 3 calls to start
ok 858 at least 3
ok 859 default 1
ok 860 1 run
ok 861 default 2
ok 862 2 run
ok 863 default 3
2016-10-20 08:16:07 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# start and stop and start and stop
ok 864 start out null
ok 865 back to null
2016-10-20 08:16:07 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 866 still null
ok 867 verify failed
ok 868 constructor called once
ok 869 constructor called with right args
ok 870 first start before first stop
ok 871 first stop before second start
ok 872 second start before second stop
2016-10-20 08:16:07 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# two identical starts in a row
ok 873 verify failed
ok 874 constructor called once
ok 875 constructor called with right args
ok 876 (unnamed assert)
2016-10-20 08:16:07 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# two different starts in a row
2016-10-20 08:16:07 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 877 verify failed
ok 878 constructor called once
ok 879 constructor called with right args
ok 880 (unnamed assert)
ok 881 (unnamed assert)
# teardown
# setup
# two stops and a start and two stops
ok 882 verify failed
ok 883 constructor called once
ok 884 constructor called with right args
ok 885 start before stop
2016-10-20 08:16:07 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# we properly enqueue requests so no then needed
2016-10-20 08:16:07 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 886 verify failed
ok 887 constructor called once
ok 888 constructor called with right args
ok 889 start before stop
# teardown
# setup
# test calculateSeqPointKeyId
ok 890 should be equal
ok 891 should be equal
# teardown
# setup
# can create servers manager
ok 892 serversManager must not be null
ok 893 serversManager must be an object
# teardown
# setup
# calling stop without start causes error
ok 894 We need to call start first
# teardown
# setup
# can start/stop servers manager
2016-10-20 08:16:07 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:16:07 - DEBUG createNativeListener: 'listening 50179'
ok 895 port must be in range
# teardown
# setup
# starting twice resolves with listening port
2016-10-20 08:16:07 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:16:07 - DEBUG createNativeListener: 'listening 50180'
ok 896 second start should return same port
# teardown
# setup
# terminateIncomingConnection will terminate a connection
2016-10-20 08:16:07 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:16:07 - DEBUG createNativeListener: 'listening 50182'
2016-10-20 08:16:07 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:16:07 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:16:07 - DEBUG createNativeListener: 'new mux'
ok 897 we should be connected
2016-10-20 08:16:07 - DEBUG createNativeListener: 'incoming socket close'
ok 898 now we are disconnected
# teardown
# setup
# terminate an Outgoing connection will terminate the server
2016-10-20 08:16:07 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:16:07 - DEBUG createNativeListener: 'listening 50184'
# teardown
# setup
# terminate an Outgoing connection with wrong arguments is not harmful
2016-10-20 08:16:07 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:16:07 - DEBUG createNativeListener: 'listening 50185'
# teardown
# setup
ok 899 should be in started state
# After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
ok 900 peer identifier should match
ok 901 generation should be 0
ok 902 host address should match
ok 903 port should match
ok 904 generation should be 0
ok 905 host address should be null
ok 906 port should should be null
# teardown
ok 907 should not be in started state
# setup
ok 908 should be in started state
# #startUpdateAdvertisingAndListening correctly updates USN
2016-10-20 08:16:07 - DEBUG thaliWifiInfrastructure: 'listening 50186'
ok 909 first invocation sets 0 generation
ok 910 second invocation doesn’t change UUID but increments generation
ok 911 third invocation doesn’t change UUID but increments generation
# teardown
ok 912 should not be in started state
# setup
ok 913 should be in started state
# #startUpdateAdvertisingAndListening generates new peerIdentifier after #stopAdvertisingAndListening has been called
2016-10-20 08:16:07 - DEBUG thaliWifiInfrastructure: 'listening 50187'
2016-10-20 08:16:07 - DEBUG thaliWifiInfrastructure: 'listening 50188'
ok 914 new UUID after advertising is stopped
# teardown
ok 915 should not be in started state
# setup
ok 916 should be in started state
# #startUpdateAdvertisingAndListening sends correct requests
2016-10-20 08:16:07 - DEBUG thaliWifiInfrastructure: 'listening 50189'
ok 917 advertise-alive fired with expected usn
ok 918 advertise-bye fired with expected usn
# teardown
ok 919 should not be in started state
# setup
ok 920 should be in started state
# messages with invalid location or USN should be ignored
2016-10-20 08:16:07 - WARN thaliWifiInfrastructure: 'Failed to parse a valid port number from location: http://foo.bar:90000'
ok 921 should not have emitted with invalid port
2016-10-20 08:16:07 - WARN thaliWifiInfrastructure: 'Invalid USN (expected "data:" prefix): foobar'
ok 922 should not have emitted with invalid USN
# teardown
ok 923 should not be in started state
# setup
ok 924 should be in started state
# Delayed own message are still ignored after advertisement has been toggled on and off several times
2016-10-20 08:16:07 - DEBUG thaliWifiInfrastructure: 'listening 50190'
2016-10-20 08:16:07 - DEBUG thaliWifiInfrastructure: 'listening 50191'
2016-10-20 08:16:07 - DEBUG thaliWifiInfrastructure: 'listening 50192'
2016-10-20 08:16:07 - DEBUG thaliWifiInfrastructure: 'listening 50193'
ok 925 all captured messages are not handled
# teardown
ok 926 should not be in started state
# setup
ok 927 should be in started state
# verify that Thali-specific messages are filtered correctly
ok 928 messages with irrelevant NT should be ignored
ok 929 relevant messages should not be ignored
# teardown
ok 930 should not be in started state
# setup
ok 931 should be in started state
# #startListeningForAdvertisements should fail if start not called
ok 932 specific error should be returned
# teardown
ok 933 should not be in started state
# setup
ok 934 should be in started state
# #startUpdateAdvertisingAndListening should fail if start not called
ok 935 specific error should be returned
# teardown
ok 936 should not be in started state
# setup
ok 937 should be in started state
# #start should fail if called twice in a row
ok 938 specific error should be received
# teardown
ok 939 should not be in started state
# setup
ok 940 should be in started state
# should not be started after stop is called
ok 941 should not be started
ok 942 should not be listening
ok 943 should not target listening
ok 944 should not be advertising
ok 945 should not target advertising
# teardown
ok 946 should not be in started state
# setup
ok 947 should be in started state
# #startUpdateAdvertisingAndListening should fail invalid router has been passed
2016-10-20 08:16:07 - ERROR thaliWifiInfrastructure: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 948 specific error should be received
# teardown
ok 949 should not be in started state
# setup
ok 950 should be in started state
# #startUpdateAdvertisingAndListening should fail if router server starting fails
2016-10-20 08:16:07 - ERROR thaliWifiInfrastructure: 'Router server emitted an error: Error: listen EADDRINUSE'
ok 951 specific error expected
# teardown
ok 952 should not be in started state
# setup
ok 953 should be in started state
# #startUpdateAdvertisingAndListening should start hosting given router object
2016-10-20 08:16:07 - DEBUG thaliWifiInfrastructure: 'listening 50195'
ok 954 server should respond with code 200
# teardown
ok 955 should not be in started state
# setup
ok 956 should be in started state
# #startUpdateAdvertisingAndListening bad psk should be rejected object
2016-10-20 08:16:07 - DEBUG thaliWifiInfrastructure: 'listening 50197'
ok 957 Connection should be rejected
# teardown
ok 958 should not be in started state
# setup
ok 959 should be in started state
# #stop can be called multiple times in a row
ok 960 should be in stopped state
ok 961 should still be in stopped state
# teardown
ok 962 should not be in started state
# setup
ok 963 should be in started state
# #startListeningForAdvertisements can be called multiple times in a row
ok 964 should be in listening state
ok 965 should still be in listening state
# teardown
ok 966 should not be in started state
# setup
ok 967 should be in started state
# #stopListeningForAdvertisements can be called multiple times in a row
ok 968 should not be in listening state
ok 969 should still not be in listening state
# teardown
ok 970 should not be in started state
# setup
ok 971 should be in started state
# #stopAdvertisingAndListening can be called multiple times in a row
ok 972 should not be in advertising state
ok 973 should still not be in advertising state
# teardown
ok 974 should not be in started state
# setup
ok 975 should be in started state
# functions are run from a queue in the right order
2016-10-20 08:16:07 - DEBUG thaliWifiInfrastructure: 'listening 50199'
ok 976 call order must match
# teardown
ok 977 should not be in started state
# setup
ok 978 should be in started state
# does not get peer changes from self
2016-10-20 08:16:07 - DEBUG thaliWifiInfrastructure: 'listening 50200'
# teardown
ok 979 should not be in started state
# setup
# Correctly parses/stringifies USN
ok 980 correctly parses USN string
ok 981 throws if usn has invalid prefix
ok 982 throws if usn has invalid identifier format
ok 983 throws if usn has invalid generation
ok 984 correctly stringifies peer
# teardown
2016-10-20 08:16:09 - DEBUG SimpleThaliTape: 'all unit tests succeeded, platformName: 'desktop''
2016-10-20 08:16:09 - DEBUG SimpleThaliTape: 'skipped tests: '["native available - peer with greater generation is cached (MPCF)","native available - peer with same or older generation is ignored (MPCF)","networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)","multiconnect failure - new peer is ignored (MPCF)","multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)","newAddressPort field (MPCF)"]''
2016-10-20 08:16:09 - DEBUG SimpleThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'
2016-10-20 08:16:09 - INFO runTests: 'Finished'

1..984
# tests 984
# pass  984

# ok


> thali-cordova-plugin-jxcore@1.0.0 test-meta /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore
> jx runTests.js meta_tests

2016-10-20 08:16:12 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/meta_tests/testCanBeSkipped.js'
2016-10-20 08:16:12 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/meta_tests/testInstall.js'
2016-10-20 08:16:12 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/meta_tests/testResultsProcessor.js'
2016-10-20 08:16:12 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/meta_tests/testSync.js'
2016-10-20 08:16:12 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/meta_tests/testTestSendData.js'
2016-10-20 08:16:12 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/meta_tests/testTestUtils.js'
2016-10-20 08:16:12 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/meta_tests/testUnitTestFramework.js'
TAP version 13
# setup
# we should not skip test without 'canBeSkipped' function
ok 1 passed
# teardown
# setup
# we should not skip test with 'canBeSkipped' returned false
ok 2 passed
# teardown
# setup
# we should not skip test with 'canBeSkipped' returned promise with false
ok 3 passed
# teardown
# setup
# we should skip test with 'canBeSkipped' returned true
2016-10-20 08:16:12 - DEBUG SimpleThaliTape: 'test was skipped, name: 'we should skip test with 'canBeSkipped' returned true''
# teardown
# setup
# we should skip test with 'canBeSkipped' returned promise with true
2016-10-20 08:16:12 - DEBUG SimpleThaliTape: 'test was skipped, name: 'we should skip test with 'canBeSkipped' returned promise with true''
# teardown
# setup
# two required plugins should get installed
Trying to install jxcore-cordova version: 0.1.5
Spawning: jx - /Users/thali/Github/Thali_CordovaPlugin/thali/install/node_modules/jxc/bin/jxc.bin.js,install,0.1.5,--use-url,http://jxcore.azureedge.net/jxcore-cordova/0.1.5/release/io.jxcore.node.jx - {"cwd":"/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/T/tmp-3380DvI0mAnMicv7/TestApp"}
[36mDownloading:[39m [32mhttp://jxcore.azureedge.net/jxcore-cordova/0.1.5/release/io.jxcore.node.jx
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

Starting to download Thali Cordova plugin from: https://codeload.github.com/thaliproject/Thali_CordovaPlugin/zip/iOS
Adding Thali Cordova plugin from: /var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/T/tmp-3380DvI0mAnMicv7/TestApp/thaliDontCheckIn/Thali_CordovaPlugin-iOS
Spawning: cordova - plugins,add,/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/T/tmp-3380DvI0mAnMicv7/TestApp/thaliDontCheckIn/Thali_CordovaPlugin-iOS - {"cwd":"/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/T/tmp-3380DvI0mAnMicv7/TestApp"}
ok 4 jxcore cordova plugin is installed
ok 5 thali cordova plugin is installed
# teardown
# setup
# should be able to process valid results without exceptions
{ 'name:': 'LGE-Nexus 5_PT7062',
  result: 'OK',
  sendList: 
   [ { connections: 3,
       dataAmount: 100000,
       dataReceived: 100000,
       doneRounds: 1,
       name: '90:E7:C4:FC:13:3C',
       result: 'OK',
       time: 57792,
       tryCount: 1 } ],
  time: 119819 }
{ 'name:': 'HTC-HTC6535LVW_PT3841',
  result: 'OK',
  sendList: 
   [ { connections: 2,
       dataAmount: 100000,
       dataReceived: 100000,
       doneRounds: 5,
       name: 'F8:95:C7:13:51:1E',
       result: 'OK',
       time: 30550,
       tryCount: 1 } ],
  time: 115137 }
{ 'name:': 'A5-1', time: 10005, result: 'TIMEOUT', sendList: [] }
--------------- test report ---------------------
--------------- LGE-Nexus 5_PT7062 --------------------- : 1
Send data : 100% : 57792 ms, 99% : 57792 ms, 95 : 57792 ms, 90% : 57792 ms.
Average data rate: 0.002 MB/s
Result count 1, range 57792 ms to  57792 ms.
Send data failed peers count : 0 [0 %]
Send data never tried peers count : 0 [0 %]
--------------- HTC-HTC6535LVW_PT3841 --------------------- : 2
Send data : 100% : 30550 ms, 99% : 30550 ms, 95 : 30550 ms, 90% : 30550 ms.
Average data rate: 0.003 MB/s
Result count 1, range 30550 ms to  30550 ms.
Send data failed peers count : 0 [0 %]
Send data never tried peers count : 0 [0 %]
--------------- A5-1 --------------------- : 3
No send data results!
--------------- Combined ---------------------
Send data : 100% : 57792 ms, 99% : 57792 ms, 95 : 57792 ms, 90% : 57792 ms.
Average data rate: 0.003 MB/s
--------------- end of test report ---------------------
ok 6 received processed results
# teardown
# setup
# connector should fail if server not running
daya0
oneRoundDownNow
ok 7 received a result to the done event
# teardown
# setup
# connector should be able to send data to a running server
daya1000000
oneRoundDownNow
ok 8 received a result to the done event
# teardown
# setup
# should run test with 5 peers
testSendData created {"timeout":1500000,"rounds":1,"dataTimeout":10000,"dataAmount":1000000,"conReTryTimeout":50,"conReTryCount":5,"peerCount":5}bt-address length : 5
daya1000000
check server
serverPort is 8889
StartBroadcasting started ok
[ { address: 'device-address-0' },
  { address: 'device-address-1' },
  { address: 'device-address-2' },
  { address: 'device-address-3' },
  { address: 'device-address-4' } ]
startWithNextDevice
do fake peer & start
Connect to fake peer: device-address-0
oneRoundDownNow
---- round done--------
startWithNextDevice
do fake peer & start
Connect to fake peer: device-address-1
oneRoundDownNow
---- round done--------
startWithNextDevice
do fake peer & start
Connect to fake peer: device-address-2
oneRoundDownNow
---- round done--------
startWithNextDevice
do fake peer & start
Connect to fake peer: device-address-3
oneRoundDownNow
---- round done--------
startWithNextDevice
do fake peer & start
Connect to fake peer: device-address-4
oneRoundDownNow
---- round done--------
startWithNextDevice
weAreDoneNow, resultArray.length: 5
sendReportNow
ok 9 received a result to the done event
ok 10 should be equal
testSendData stopped
# teardown
# setup
# should return same temporary folder when called multiple times
ok 11 should be equal
# teardown
# setup
# should be able to write to the temporary folder
/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/T/tmp-3380DvI0mAnMicv7
ok 12 no error returned when creating a subfolder
# teardown
# setup
# can call hasRequiredHardware
ok 13 resolves with a boolean
# teardown
2016-10-20 08:16:50 - DEBUG SimpleThaliTape: 'all unit tests succeeded, platformName: 'desktop''
2016-10-20 08:16:50 - DEBUG SimpleThaliTape: 'skipped tests: '["we should skip test with 'canBeSkipped' returned true","we should skip test with 'canBeSkipped' returned promise with true"]''
2016-10-20 08:16:50 - DEBUG SimpleThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'
2016-10-20 08:16:50 - INFO runTests: 'Finished'

1..13
# tests 13
# pass  13

# ok


> thali-cordova-plugin-jxcore@1.0.0 test-coordinated /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore
> jx runCoordinatedTests.js

2016-10-20 08:16:52 - INFO HttpServer: 'listening on *:3000'

[33m2016-10-20 08:16:54 - DEBUG UnitTest_app: 'Unit Test app is loaded'
[39m
[33m2016-10-20 08:16:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
[39m
[33m2016-10-20 08:16:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
[39m
[33m2016-10-20 08:16:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
[39m
[33m2016-10-20 08:16:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
[39m
[33m2016-10-20 08:16:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
[39m
[33m2016-10-20 08:16:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
[39m
[33m2016-10-20 08:16:54 - DEBUG UnitTest_app: 'My device name is: f33d72ed-c004-4f3c-b7ff-e41191fab56d'
[39m
[33m2016-10-20 08:16:54 - WARN testUtils: 'myNameCallback not set!'
[39m
[33m2016-10-20 08:16:54 - DEBUG UnitTest_app: 'Running for NATIVE network type'
[39m
[32m2016-10-20 08:16:54 - DEBUG UnitTest_app: 'Unit Test app is loaded'
[39m
[32m2016-10-20 08:16:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
[39m
[32m2016-10-20 08:16:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
[39m
[32m2016-10-20 08:16:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
[39m
[32m2016-10-20 08:16:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
[39m
[32m2016-10-20 08:16:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
[39m
[32m2016-10-20 08:16:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
[39m
[32m2016-10-20 08:16:54 - DEBUG UnitTest_app: 'My device name is: 873edde4-e80e-4434-8053-c55d63c20640'
[39m
[32m2016-10-20 08:16:54 - WARN testUtils: 'myNameCallback not set!'
[39m
[32m2016-10-20 08:16:54 - DEBUG UnitTest_app: 'Running for NATIVE network type'
[39m
[33m2016-10-20 08:16:54 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreateNativeListener.js'
[39m
[36m2016-10-20 08:16:54 - DEBUG UnitTest_app: 'Unit Test app is loaded'
[39m
[36m2016-10-20 08:16:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
[39m
[36m2016-10-20 08:16:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
[39m
[36m2016-10-20 08:16:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
[39m
[36m2016-10-20 08:16:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
[39m
[36m2016-10-20 08:16:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
[39m
[36m2016-10-20 08:16:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
[39m
[36m2016-10-20 08:16:54 - DEBUG UnitTest_app: 'My device name is: 4fb18f8b-0fab-4f3e-90a4-be4f608dc2ea'
[39m
[36m2016-10-20 08:16:54 - WARN testUtils: 'myNameCallback not set!'
[39m
[36m2016-10-20 08:16:54 - DEBUG UnitTest_app: 'Running for NATIVE network type'
[39m
[33m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js'
[39m
[33m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js'
[39m
[32m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreateNativeListener.js'
[39m
[33m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
[39m
[33m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
[39m
[33m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testNativeMethod.js'
[39m
[33m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
[39m
[36m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreateNativeListener.js'
[39m
[32m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js'
[39m
[33m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBGenerator.js'
[39m
[32m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js'
[39m
[33m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPromiseQueue.js'
[39m
[33m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testTests.js'
[39m
[33m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManager.js'
[39m
[33m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
[39m
[33m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js'
[39m
[36m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js'
[39m
[36m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js'
[39m
[33m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNative.js'
[39m
[33m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
[39m
[33m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
[39m
[33m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
[39m
[33m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
[39m
[32m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
[39m
[33m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotification.js'
[39m
[33m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationAction.js'
[39m
[32m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
[39m
[32m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testNativeMethod.js'
[39m
[32m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
[39m
[36m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
[39m
[33m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
[39m
[33m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationClient.js'
[39m
[33m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationLocal.js'
[39m
[33m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationServer.js'
[39m
[33m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerAction.js'
[39m
[33m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerDictionary.js'
[39m
[33m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
[39m
[33m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
[39m
[33m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
[39m
[33m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
[39m
[33m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
[39m
[33m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
[39m
[33m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
[39m
[33m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
[39m
[33m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliTcpServersManager.js'
[39m
[33m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
[39m
[33m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testUsn.js'
[39m
[36m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
[39m
[36m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testNativeMethod.js'
[39m
[36m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
[39m
[33m2016-10-20 08:16:55 - DEBUG CoordinatedClient: 'connected to the test server'
[39m
2016-10-20 08:16:55 - DEBUG HttpServer: 'device presented, name: 'f33d72ed-c004-4f3c-b7ff-e41191fab56d', uuid: '2d5ac673-605e-4611-8737-593c8c6f7f1d', platformName: 'desktop', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-20 08:16:55 - DEBUG TestFramework: 'device added, name: 'f33d72ed-c004-4f3c-b7ff-e41191fab56d''

[32m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBGenerator.js'
[39m
[32m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPromiseQueue.js'
[39m
[32m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testTests.js'
[39m
[32m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManager.js'
[39m
[36m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBGenerator.js'
[39m
[36m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPromiseQueue.js'
[39m
[36m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testTests.js'
[39m
[36m2016-10-20 08:16:55 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManager.js'
[39m
[32m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
[39m
[32m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js'
[39m
[36m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
[39m
[36m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js'
[39m
[32m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNative.js'
[39m
[32m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
[39m
[32m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
[39m
[32m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
[39m
[32m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
[39m
[36m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNative.js'
[39m
[32m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotification.js'
[39m
[32m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationAction.js'
[39m
[36m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
[39m
[36m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
[39m
[36m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
[39m
[36m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
[39m
[32m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
[39m
[36m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotification.js'
[39m
[36m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationAction.js'
[39m
[32m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationClient.js'
[39m
[32m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationLocal.js'
[39m
[32m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationServer.js'
[39m
[32m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerAction.js'
[39m
[32m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerDictionary.js'
[39m
[32m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
[39m
[32m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
[39m
[32m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
[39m
[32m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
[39m
[32m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
[39m
[36m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
[39m
[32m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
[39m
[32m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
[39m
[32m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
[39m
[32m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliTcpServersManager.js'
[39m
[32m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
[39m
[36m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationClient.js'
[39m
[32m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testUsn.js'
[39m
[36m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationLocal.js'
[39m
[36m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationServer.js'
[39m
[36m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerAction.js'
[39m
[36m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerDictionary.js'
[39m
[36m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
[39m
[36m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
[39m
[36m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
[39m
[36m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
[39m
[36m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
[39m
[36m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
[39m
[32m2016-10-20 08:16:56 - DEBUG CoordinatedClient: 'connected to the test server'
[39m
[36m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
[39m
[36m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
[39m
[36m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliTcpServersManager.js'
[39m
[36m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
[39m
2016-10-20 08:16:56 - DEBUG HttpServer: 'device presented, name: '873edde4-e80e-4434-8053-c55d63c20640', uuid: '40637163-426b-4188-bf38-3cba27f28b87', platformName: 'desktop', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-20 08:16:56 - DEBUG TestFramework: 'device added, name: '873edde4-e80e-4434-8053-c55d63c20640''

[36m2016-10-20 08:16:56 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testUsn.js'
[39m
[36m2016-10-20 08:16:56 - DEBUG CoordinatedClient: 'connected to the test server'
[39m
2016-10-20 08:16:56 - DEBUG HttpServer: 'device presented, name: '4fb18f8b-0fab-4f3e-90a4-be4f608dc2ea', uuid: 'b324b363-53be-4949-919e-9ccbbf5b08af', platformName: 'desktop', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-20 08:16:56 - DEBUG TestFramework: 'device added, name: '4fb18f8b-0fab-4f3e-90a4-be4f608dc2ea''
2016-10-20 08:16:56 - INFO TestFramework: 'all required 3 devices are present for platformName: 'desktop''

2016-10-20 08:16:56 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'desktop''
2016-10-20 08:16:56 - DEBUG UnitTestFramework: 'scheduling tests'

[33mTAP version 13
[39m
[33m# setup
[39m
[32mTAP version 13
[39m
[32m# setup
[39m
[36mTAP version 13
[39m
[36m# setup
[39m
2016-10-20 08:16:56 - DEBUG UnitTestFramework: 'tests scheduled'

2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#setup: 'calling createNativeListener directly rejects''

[33m# calling createNativeListener directly rejects
[39m
[32m# calling createNativeListener directly rejects
[39m
[36m# calling createNativeListener directly rejects
[39m
2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#setup ok: 'calling createNativeListener directly rejects''

2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#run: 'calling createNativeListener directly rejects''

[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating native server'
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'listening 50216'
[39m
[33mok 1 Should throw
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating native server'
[39m
[33m# teardown
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'listening 50217'
[39m
[32mok 1 Should throw
[39m
[32m# teardown
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating native server'
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'listening 50218'
[39m
[36mok 1 Should throw
[39m
[36m# teardown
[39m
2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#run ok: 'calling createNativeListener directly rejects''

2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#teardown: 'calling createNativeListener directly rejects''

[33m# setup
[39m
[32m# setup
[39m
[36m# setup
[39m
2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#teardown ok: 'calling createNativeListener directly rejects''

2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#setup: 'emits incomingConnectionState''

[33m# emits incomingConnectionState
[39m
[32m# emits incomingConnectionState
[39m
[36m# emits incomingConnectionState
[39m
2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#setup ok: 'emits incomingConnectionState''

2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#run: 'emits incomingConnectionState''

[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating native server'
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'listening 50222'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating native server'
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new incoming socket'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'listening 50224'
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new mux'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new incoming socket'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[33mok 2 initial connection state should be CONNECTED
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new mux'
[39m
[32mok 2 initial connection state should be CONNECTED
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'incoming socket close'
[39m
[33mok 3 final connection state should be DISCONNECTED
[39m
[33m# teardown
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating native server'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'incoming socket close'
[39m
[32mok 3 final connection state should be DISCONNECTED
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'listening 50226'
[39m
[32m# teardown
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new incoming socket'
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new mux'
[39m
[36mok 2 initial connection state should be CONNECTED
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'incoming socket close'
[39m
[36mok 3 final connection state should be DISCONNECTED
[39m
2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#run ok: 'emits incomingConnectionState''

2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#teardown: 'emits incomingConnectionState''

[36m# teardown
[39m
[33m# setup
[39m
[32m# setup
[39m
[36m# setup
[39m
2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#teardown ok: 'emits incomingConnectionState''

2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#setup: 'emits routerPortConnectionFailed''

[33m# emits routerPortConnectionFailed
[39m
[32m# emits routerPortConnectionFailed
[39m
[36m# emits routerPortConnectionFailed
[39m
2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#setup ok: 'emits routerPortConnectionFailed''

2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#run: 'emits routerPortConnectionFailed''

[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating native server'
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'listening 50231'
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new incoming socket'
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new mux'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating native server'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'listening 50233'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new incoming socket'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new mux'
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: ' Error: connect ECONNREFUSED
    at errnoException (net.js:837:11)
    at Object.afterConnect [as oncomplete] (net.js:829:19)'
[39m
[33mok 4 tried to connect to right port
ok 5 failed due to refused connection
ok 6 routerPortConnectionFailed is emitted
# teardown
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: ' Error: connect ECONNREFUSED
    at errnoException (net.js:837:11)
    at Object.afterConnect [as oncomplete] (net.js:829:19)'
[39m
[32mok 4 tried to connect to right port
[39m
[32mok 5 failed due to refused connection
[39m
[32mok 6 routerPortConnectionFailed is emitted
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating native server'
[39m
[32m# teardown
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'listening 50237'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new mux'
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: ' Error: connect ECONNREFUSED
    at errnoException (net.js:837:11)
    at Object.afterConnect [as oncomplete] (net.js:829:19)'
[39m
[36mok 4 tried to connect to right port
[39m
[36mok 5 failed due to refused connection
ok 6 routerPortConnectionFailed is emitted
[39m
2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#run ok: 'emits routerPortConnectionFailed''
2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#teardown: 'emits routerPortConnectionFailed''

[36m# teardown
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'mux close'
[39m
[33m# setup
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'incoming socket close'
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'mux close'
[39m
[36m# setup
2016-10-20 08:16:56 - DEBUG createNativeListener: 'incoming socket close'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'mux close'
[39m
[32m# setup
2016-10-20 08:16:56 - DEBUG createNativeListener: 'incoming socket close'
[39m
2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#teardown ok: 'emits routerPortConnectionFailed''
2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#setup: 'native server connections all up''

[33m# native server connections all up
[39m
[32m# native server connections all up
[39m
[36m# native server connections all up
[39m
2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#setup ok: 'native server connections all up''

2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#run: 'native server connections all up''

[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating native server'
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'listening 50243'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating native server'
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new incoming socket'
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:16:56 - DEBUG createNativeListener: 'new mux'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'listening 50245'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:16:56 - DEBUG createNativeListener: 'new mux'
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:16:56 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33mok 7 Send/recvd #1 should be equal length
[39m
[33mok 8 Send/recvd #1 should be same
[39m
[33mok 9 Send/recvd #2 should be equal length
ok 10 Send/recvd #2 should be same
ok 11 Should be exactly 2 client sockets
[39m
[33m# teardown
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating native server'
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'listening 50251'
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new mux'
[39m
[32mok 7 Send/recvd #1 should be equal length
[39m
[32mok 8 Send/recvd #1 should be same
[39m
[32mok 9 Send/recvd #2 should be equal length
ok 10 Send/recvd #2 should be same
ok 11 Should be exactly 2 client sockets
[39m
[32m# teardown
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36mok 7 Send/recvd #1 should be equal length
[39m
[36mok 8 Send/recvd #1 should be same
[39m
[36mok 9 Send/recvd #2 should be equal length
ok 10 Send/recvd #2 should be same
[39m
[36mok 11 Should be exactly 2 client sockets
[39m
[36m# teardown
[39m
2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#run ok: 'native server connections all up''
2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#teardown: 'native server connections all up''

[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'mux close'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'mux close'
[39m
[33m# setup
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'incoming socket close'
[39m
[32m# setup
2016-10-20 08:16:56 - DEBUG createNativeListener: 'incoming socket close'
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:56 - DEBUG createNativeListener: 'mux close'
[39m
[36m# setup
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'incoming socket close'
[39m
2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#teardown ok: 'native server connections all up''

2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming stream cleans outgoing socket''

[33m# native server - closing incoming stream cleans outgoing socket
[39m
[36m# native server - closing incoming stream cleans outgoing socket
[39m
[32m# native server - closing incoming stream cleans outgoing socket
[39m
2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming stream cleans outgoing socket''

2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming stream cleans outgoing socket''

[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:16:56 - DEBUG createNativeListener: 'listening 50258'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating native server'
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:16:56 - DEBUG createNativeListener: 'new mux'
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'listening 50260'
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new incoming socket'
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating native server'
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:16:56 - DEBUG createNativeListener: 'new mux'
[39m
[33mok 12 socket shouldn't close until after stream
ok 13 incoming remains open
# teardown
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'listening 50263'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:16:56 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new incoming socket'
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:16:56 - DEBUG createNativeListener: 'new mux'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32mok 12 socket shouldn't close until after stream
ok 13 incoming remains open
[39m
[32m# teardown
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'stream close:'
[39m
[36mok 12 socket shouldn't close until after stream
[39m
[36mok 13 incoming remains open
[39m
[36m# teardown
[39m
2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming stream cleans outgoing socket''
2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming stream cleans outgoing socket''

[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'mux close'
[39m
[33m# setup
2016-10-20 08:16:56 - DEBUG createNativeListener: 'incoming socket close'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'mux close'
[39m
[32m# setup
2016-10-20 08:16:56 - DEBUG createNativeListener: 'incoming socket close'
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'mux close'
[39m
[36m# setup
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'incoming socket close'
[39m
2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming stream cleans outgoing socket''

2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming connection cleans outgoing socket''

[33m# native server - closing incoming connection cleans outgoing socket
[39m
[32m# native server - closing incoming connection cleans outgoing socket
[39m
[36m# native server - closing incoming connection cleans outgoing socket
[39m
2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming connection cleans outgoing socket''

2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming connection cleans outgoing socket''

[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:16:56 - DEBUG createNativeListener: 'listening 50270'
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:16:56 - DEBUG createNativeListener: 'new mux'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating native server'
[39m
[33mok 14 we should not have gotten an error
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'listening 50272'
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new incoming socket'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new mux'
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'incoming socket close'
[39m
[33mok 15 socket shouldn't close until after incoming
[39m
[33mok 16 incoming is cleaned up
[39m
[33m# teardown
[39m
[32mok 14 we should not have gotten an error
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:16:56 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:56 - DEBUG createNativeListener: 'incoming socket close'
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating native server'
[39m
[32mok 15 socket shouldn't close until after incoming
ok 16 incoming is cleaned up
[39m
[32m# teardown
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'listening 50276'
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new incoming socket'
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:16:56 - DEBUG createNativeListener: 'new mux'
ok 14 we should not have gotten an error
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:56 - DEBUG createNativeListener: 'incoming socket close'
[39m
[36mok 15 socket shouldn't close until after incoming
[39m
[36mok 16 incoming is cleaned up
[39m
[36m# teardown
[39m
2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming connection cleans outgoing socket''

2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming connection cleans outgoing socket''

[33m# setup
[39m
[32m# setup
[39m
[36m# setup
[39m
2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming connection cleans outgoing socket''

2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#setup: 'native server - closing outgoing socket cleans associated mux stream''

[33m# native server - closing outgoing socket cleans associated mux stream
[39m
[32m# native server - closing outgoing socket cleans associated mux stream
[39m
[36m# native server - closing outgoing socket cleans associated mux stream
[39m
2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#run: 'native server - closing outgoing socket cleans associated mux stream''

[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:16:56 - DEBUG createNativeListener: 'listening 50282'
2016-10-20 08:16:56 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:16:56 - DEBUG createNativeListener: 'new mux'
2016-10-20 08:16:56 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:16:56 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating native server'
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'stream close:'
[39m
[33mok 17 stream was closed
ok 18 incoming should survive
ok 19 mux should have no streams
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'listening 50285'
[39m
[33m# teardown
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new mux'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating native server'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'listening 50288'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:16:56 - DEBUG createNativeListener: 'new mux'
[39m
[32mok 17 stream was closed
ok 18 incoming should survive
ok 19 mux should have no streams
[39m
[32m# teardown
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'stream close:'
[39m
[36mok 17 stream was closed
[39m
[36mok 18 incoming should survive
ok 19 mux should have no streams
[39m
[36m# teardown
[39m
2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#run ok: 'native server - closing outgoing socket cleans associated mux stream''
2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#teardown: 'native server - closing outgoing socket cleans associated mux stream''

[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'mux close'
# setup
2016-10-20 08:16:56 - DEBUG createNativeListener: 'incoming socket close'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'mux close'
[39m
[32m# setup
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'incoming socket close'
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'mux close'
[39m
[36m# setup
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'incoming socket close'
[39m
2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing outgoing socket cleans associated mux stream''
2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#setup: 'native server - closing the whole server cleans everything up''

[33m# native server - closing the whole server cleans everything up
[39m
[32m# native server - closing the whole server cleans everything up
[39m
[36m# native server - closing the whole server cleans everything up
[39m
2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing the whole server cleans everything up''

2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#run: 'native server - closing the whole server cleans everything up''

[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating native server'
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'listening 50294'
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:16:56 - DEBUG createNativeListener: 'new mux'
[39m
[33mok 20 we should not have gotten an error
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating native server'
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'listening 50297'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating native server'
[39m
[33mok 21 Buffers are identical
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'mux close'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'listening 50298'
[39m
[33mok 22 native server is nulled out
ok 23 native server should be closed
ok 24 incoming has been removed
ok 25 Incoming should be done
ok 26 The mux object should be closed
ok 27 The mux stream should be closed
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'incoming socket close'
[39m
[33m# teardown
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new mux'
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new incoming socket'
[39m
[32mok 20 we should not have gotten an error
2016-10-20 08:16:56 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:16:56 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:16:56 - DEBUG createNativeListener: 'new mux'
[39m
[36mok 20 we should not have gotten an error
[39m
[32mok 21 Buffers are identical
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'mux close'
[39m
[32mok 22 native server is nulled out
ok 23 native server should be closed
ok 24 incoming has been removed
ok 25 Incoming should be done
ok 26 The mux object should be closed
ok 27 The mux stream should be closed
2016-10-20 08:16:56 - DEBUG createNativeListener: 'incoming socket close'
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m# teardown
[39m
[36mok 21 Buffers are identical
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'mux close'
[39m
[36mok 22 native server is nulled out
[39m
[36mok 23 native server should be closed
ok 24 incoming has been removed
ok 25 Incoming should be done
[39m
[36mok 26 The mux object should be closed
ok 27 The mux stream should be closed
[39m
[36m2016-10-20 08:16:56 - DEBUG createNativeListener: 'incoming socket close'
[39m
[36m# teardown
[39m
2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#run ok: 'native server - closing the whole server cleans everything up''
2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#teardown: 'native server - closing the whole server cleans everything up''

[33m# setup
[39m
[32m# setup
[39m
[36m# setup
[39m
2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing the whole server cleans everything up''

2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#setup: 'native server - we can get a ton of connections and data through and still clean up the server completely''

[33m# native server - we can get a ton of connections and data through and still clean up the server completely
[39m
[32m# native server - we can get a ton of connections and data through and still clean up the server completely
[39m
[36m# native server - we can get a ton of connections and data through and still clean up the server completely
[39m
2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#setup ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''
2016-10-20 08:16:56 - DEBUG UnitTestFramework: '#run: 'native server - we can get a ton of connections and data through and still clean up the server completely''

[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating native server'
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'listening 50306'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating native server'
[39m
[32m2016-10-20 08:16:56 - DEBUG createNativeListener: 'listening 50313'
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new incoming socket'
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new mux'
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:16:56 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[33m2016-10-20 08:16:56 - DEBUG createNativeListener: 'new mux'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new mux'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new incoming socket'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new mux'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new incoming socket'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new mux'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'new mux'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'new mux'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'new incoming socket'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'new mux'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new incoming socket'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new mux'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new incoming socket'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'new mux'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new incoming socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'new mux'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new incoming socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new mux'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new incoming socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new mux'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'new incoming socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'new mux'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new incoming socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'new mux'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new mux'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new mux'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new incoming socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new mux'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'new incoming socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'new mux'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new mux'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'creating native server'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'listening 50342'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new incoming socket'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new mux'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new mux'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new incoming socket'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new mux'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new incoming socket'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'new mux'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new incoming socket'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new mux'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new incoming socket'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new mux'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new incoming socket'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'new mux'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new incoming socket'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new mux'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new mux'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new incoming socket'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new mux'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'mux close'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'mux close'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'mux close'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'mux close'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'mux close'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'mux close'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'mux close'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'mux close'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'mux close'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'mux close'
[39m
[33mok 28 native server is nulled out
[39m
[33mok 29 native server should be closed
[39m
[33mok 30 incoming has been removed
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'incoming socket close'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'incoming socket close'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'incoming socket close'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'incoming socket close'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'incoming socket close'
[39m
[33m2016-10-20 08:16:57 - DEBUG createNativeListener: 'incoming socket close'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'incoming socket close'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'incoming socket close'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'incoming socket close'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'incoming socket close'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m# teardown
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'mux close'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'mux close'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'mux close'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'mux close'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'mux close'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'mux close'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'mux close'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'mux close'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'mux close'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'mux close'
ok 28 native server is nulled out
ok 29 native server should be closed
ok 30 incoming has been removed
2016-10-20 08:16:57 - DEBUG createNativeListener: 'incoming socket close'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'incoming socket close'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'incoming socket close'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'incoming socket close'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'incoming socket close'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'incoming socket close'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'incoming socket close'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'incoming socket close'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'incoming socket close'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'incoming socket close'
[39m
[32m# teardown
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'mux close'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'mux close'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'mux close'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'mux close'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'mux close'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'mux close'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'mux close'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'mux close'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'mux close'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'stream close:'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'mux close'
[39m
[36mok 28 native server is nulled out
[39m
[36mok 29 native server should be closed
ok 30 incoming has been removed
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'incoming socket close'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'incoming socket close'
2016-10-20 08:16:57 - DEBUG createNativeListener: 'incoming socket close'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'incoming socket close'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'incoming socket close'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'incoming socket close'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'incoming socket close'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'incoming socket close'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'incoming socket close'
[39m
[36m2016-10-20 08:16:57 - DEBUG createNativeListener: 'incoming socket close'
[39m
2016-10-20 08:16:57 - DEBUG UnitTestFramework: '#run ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-10-20 08:16:57 - DEBUG UnitTestFramework: '#teardown: 'native server - we can get a ton of connections and data through and still clean up the server completely''

[32m# setup
[39m
[33m# setup
[39m
[36m# teardown
[39m
[36m# setup
[39m
2016-10-20 08:16:58 - DEBUG UnitTestFramework: '#teardown ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''
2016-10-20 08:16:58 - DEBUG UnitTestFramework: '#setup: 'native server - simulate mux failure, make sure everything is cleaned up''

[33m# native server - simulate mux failure, make sure everything is cleaned up
[39m
[36m# native server - simulate mux failure, make sure everything is cleaned up
[39m
[32m# native server - simulate mux failure, make sure everything is cleaned up
[39m
2016-10-20 08:16:58 - DEBUG UnitTestFramework: '#setup ok: 'native server - simulate mux failure, make sure everything is cleaned up''
2016-10-20 08:16:58 - DEBUG UnitTestFramework: '#run: 'native server - simulate mux failure, make sure everything is cleaned up''

[33m2016-10-20 08:16:58 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:16:58 - DEBUG createNativeListener: 'listening 50462'
2016-10-20 08:16:58 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:16:58 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:16:58 - DEBUG createNativeListener: 'new mux'
ok 31 we should not have gotten an error
2016-10-20 08:16:58 - DEBUG createNativeListener: 'new stream: '
2016-10-20 08:16:58 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-20 08:16:58 - DEBUG createNativeListener: 'creating native server'
2016-10-20 08:16:58 - DEBUG createNativeListener: 'listening 50464'
2016-10-20 08:16:58 - DEBUG createNativeListener: 'new incoming socket'
2016-10-20 08:16:58 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-20 08:16:58 - DEBUG createNativeListener: 'new mux'
[39m
[33mok 32 Buffers are identical
[39m
[32m2016-10-20 08:16:58 - DEBUG createNativeListener: 'creating native server'
[39m
[33m2016-10-20 08:16:58 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-20 08:16:58 - DEBUG createNativeListener: 'listening 50467'
[39m
[36mok 31 we should not have gotten an error
[39m
[32m2016-10-20 08:16:58 - DEBUG createNativeListener: 'new incoming socket'
[39m
[33m2016-10-20 08:16:58 - DEBUG createNativeListener: 'mux close'
[39m
[32m2016-10-20 08:16:58 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[32m2016-10-20 08:16:58 - DEBUG createNativeListener: 'new mux'
[39m
[32mok 31 we should not have gotten an error
[39m
[32m2016-10-20 08:16:58 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-20 08:16:58 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32mok 32 Buffers are identical
[39m
[32m2016-10-20 08:16:58 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-20 08:16:58 - DEBUG createNativeListener: 'mux close'
[39m
[33m2016-10-20 08:16:58 - DEBUG createNativeListener: 'incoming socket close'
[39m
[33mok 33 server should be fine
[39m
[33mok 34 server should be open
[39m
[32m2016-10-20 08:16:58 - DEBUG createNativeListener: 'incoming socket close'
[39m
[32mok 33 server should be fine
[39m
[32mok 34 server should be open
ok 35 incoming has been removed
[39m
[32mok 36 The mux object should be closed
[39m
[33mok 35 incoming has been removed
[39m
[33mok 36 The mux object should be closed
[39m
[32mok 37 The mux stream should be closed
[39m
[33mok 37 The mux stream should be closed
[39m
[32m# teardown
[39m
[36m2016-10-20 08:16:58 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-20 08:16:58 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m# teardown
[39m
[36mok 32 Buffers are identical
[39m
[36m2016-10-20 08:16:58 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:58 - DEBUG createNativeListener: 'mux close'
[39m
[36m2016-10-20 08:16:58 - DEBUG createNativeListener: 'incoming socket close'
[39m
[36mok 33 server should be fine
[39m
[36mok 34 server should be open
[39m
[36mok 35 incoming has been removed
[39m
[36mok 36 The mux object should be closed
[39m
[36mok 37 The mux stream should be closed
[39m
2016-10-20 08:16:58 - DEBUG UnitTestFramework: '#run ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-10-20 08:16:58 - DEBUG UnitTestFramework: '#teardown: 'native server - simulate mux failure, make sure everything is cleaned up''

[36m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-10-20 08:16:58 - DEBUG UnitTestFramework: '#teardown ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-10-20 08:16:58 - DEBUG UnitTestFramework: '#setup: 'native server - timing out the incoming connection cleans everything up''

[32m# native server - timing out the incoming connection cleans everything up
[39m
[33m# native server - timing out the incoming connection cleans everything up
[39m
[36m# native server - timing out the incoming connection cleans everything up
[39m
2016-10-20 08:16:58 - DEBUG UnitTestFramework: '#setup ok: 'native server - timing out the incoming connection cleans everything up''

2016-10-20 08:16:58 - DEBUG UnitTestFramework: '#run: 'native server - timing out the incoming connection cleans everything up''

[32m2016-10-20 08:16:58 - DEBUG createNativeListener: 'creating native server'
[39m
[33m2016-10-20 08:16:58 - DEBUG createNativeListener: 'creating native server'
[39m
[32m2016-10-20 08:16:58 - DEBUG createNativeListener: 'listening 50474'
[39m
[32m2016-10-20 08:16:58 - DEBUG createNativeListener: 'new incoming socket'
[39m
[32m2016-10-20 08:16:58 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[33m2016-10-20 08:16:58 - DEBUG createNativeListener: 'listening 50476'
[39m
[32m2016-10-20 08:16:58 - DEBUG createNativeListener: 'new mux'
[39m
[32mok 38 we should not have gotten an error
[39m
[32m2016-10-20 08:16:58 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-20 08:16:58 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-20 08:16:58 - DEBUG createNativeListener: 'new incoming socket'
[39m
[33m2016-10-20 08:16:58 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[32mok 39 Buffers are identical
[39m
[33m2016-10-20 08:16:58 - DEBUG createNativeListener: 'new mux'
[39m
[36m2016-10-20 08:16:58 - DEBUG createNativeListener: 'creating native server'
[39m
[33mok 38 we should not have gotten an error
[39m
[32m2016-10-20 08:16:58 - DEBUG createNativeListener: 'incoming socket timeout'
[39m
[33m2016-10-20 08:16:58 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-20 08:16:58 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-20 08:16:58 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33mok 39 Buffers are identical
[39m
[32m2016-10-20 08:16:58 - DEBUG createNativeListener: 'mux close'
[39m
[36m2016-10-20 08:16:58 - DEBUG createNativeListener: 'listening 50480'
[39m
[32m2016-10-20 08:16:58 - DEBUG createNativeListener: 'incoming socket close'
[39m
[32mok 40 server should be fine
[39m
[32mok 41 server should be open
[39m
[32mok 42 incoming has been removed
[39m
[32mok 43 The mux object should be closed
[39m
[32mok 44 The mux stream should be closed
[39m
[33m2016-10-20 08:16:58 - DEBUG createNativeListener: 'incoming socket timeout'
[39m
[32m# teardown
[39m
[36m2016-10-20 08:16:58 - DEBUG createNativeListener: 'new incoming socket'
[39m
[33m2016-10-20 08:16:58 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:58 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[36m2016-10-20 08:16:58 - DEBUG createNativeListener: 'new mux'
[39m
[36mok 38 we should not have gotten an error
[39m
[36m2016-10-20 08:16:58 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-20 08:16:58 - DEBUG createNativeListener: 'mux close'
[39m
[36m2016-10-20 08:16:58 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-20 08:16:58 - DEBUG createNativeListener: 'incoming socket close'
[39m
[36mok 39 Buffers are identical
[39m
[33mok 40 server should be fine
[39m
[33mok 41 server should be open
[39m
[33mok 42 incoming has been removed
[39m
[33mok 43 The mux object should be closed
[39m
[33mok 44 The mux stream should be closed
[39m
[36m2016-10-20 08:16:58 - DEBUG createNativeListener: 'incoming socket timeout'
[39m
[33m# teardown
[39m
[36m2016-10-20 08:16:58 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-20 08:16:58 - DEBUG createNativeListener: 'mux close'
[39m
[36m2016-10-20 08:16:58 - DEBUG createNativeListener: 'incoming socket close'
[39m
[36mok 40 server should be fine
[39m
[36mok 41 server should be open
[39m
[36mok 42 incoming has been removed
[39m
[36mok 43 The mux object should be closed
[39m
[36mok 44 The mux stream should be closed
[39m
2016-10-20 08:16:58 - DEBUG UnitTestFramework: '#run ok: 'native server - timing out the incoming connection cleans everything up''

2016-10-20 08:16:58 - DEBUG UnitTestFramework: '#teardown: 'native server - timing out the incoming connection cleans everything up''

[36m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-10-20 08:16:58 - DEBUG UnitTestFramework: '#teardown ok: 'native server - timing out the incoming connection cleans everything up''

2016-10-20 08:16:58 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server is not there''

[33m# #_doImmediateSeqUpdate - server is not there
[39m
[32m# #_doImmediateSeqUpdate - server is not there
[39m
[36m# #_doImmediateSeqUpdate - server is not there
[39m
2016-10-20 08:16:58 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server is not there''

2016-10-20 08:16:58 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server is not there''

[33m2016-10-20 08:16:58 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
ok 45 Got right error
[39m
[33m# teardown
[39m
[32m2016-10-20 08:16:58 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
ok 45 Got right error
[39m
[32m# teardown
[39m
[36m2016-10-20 08:16:58 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
[39m
[36mok 45 Got right error
[39m
[36m# teardown
[39m
2016-10-20 08:16:58 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server is not there''

2016-10-20 08:16:58 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server is not there''

[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-10-20 08:16:58 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server is not there''

2016-10-20 08:16:58 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server accepts & closes connection''

[33m# #_doImmediateSeqUpdate - server accepts & closes connection
[39m
[36m# #_doImmediateSeqUpdate - server accepts & closes connection
[39m
[32m# #_doImmediateSeqUpdate - server accepts & closes connection
[39m
2016-10-20 08:16:58 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-20 08:16:58 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server accepts & closes connection''

[33m2016-10-20 08:16:58 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
ok 46 Got socket hang up
[39m
[33m# teardown
[39m
[32m2016-10-20 08:16:58 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
ok 46 Got socket hang up
[39m
[32m# teardown
[39m
[36m2016-10-20 08:16:58 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
[39m
[36mok 46 Got socket hang up
[39m
[36m# teardown
[39m
2016-10-20 08:16:58 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server accepts & closes connection''
2016-10-20 08:16:58 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server accepts & closes connection''

[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-10-20 08:16:58 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-20 08:16:58 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server always returns 500''

[33m# #_doImmediateSeqUpdate - server always returns 500
[39m
[32m# #_doImmediateSeqUpdate - server always returns 500
[39m
[36m# #_doImmediateSeqUpdate - server always returns 500
[39m
2016-10-20 08:16:58 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-20 08:16:58 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server always returns 500''

[33m2016-10-20 08:16:58 - DEBUG localSeqManager: 'Got an error trying to update seq []'
ok 47 Got 500 as expected
[39m
[33m# teardown
[39m
[32m2016-10-20 08:16:58 - DEBUG localSeqManager: 'Got an error trying to update seq []'
ok 47 Got 500 as expected
[39m
[32m# teardown
[39m
[36m2016-10-20 08:16:58 - DEBUG localSeqManager: 'Got an error trying to update seq []'
[39m
[36mok 47 Got 500 as expected
[39m
[36m# teardown
[39m
2016-10-20 08:16:58 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server always returns 500''
2016-10-20 08:16:58 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server always returns 500''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-20 08:16:58 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-20 08:16:58 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - create new seq doc''

[32m# #_doImmediateSeqUpdate - create new seq doc
[39m
[33m# #_doImmediateSeqUpdate - create new seq doc
[39m
[36m# #_doImmediateSeqUpdate - create new seq doc
[39m
2016-10-20 08:16:58 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - create new seq doc''
2016-10-20 08:16:58 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - create new seq doc''

[36mok 48 should be equal
[39m
[36mok 49 revs are equal
[39m
[36m# teardown
[39m
[33mok 48 should be equal
[39m
[33mok 49 revs are equal
[39m
[33m# teardown
[39m
[32mok 48 should be equal
[39m
[32mok 49 revs are equal
[39m
[32m# teardown
[39m
2016-10-20 08:16:59 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-20 08:16:59 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - create new seq doc''

[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-10-20 08:16:59 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-20 08:16:59 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

[32m# #_doImmediateSeqUpdate - doc exists, need to get rev and update
[39m
[33m# #_doImmediateSeqUpdate - doc exists, need to get rev and update
[39m
[36m# #_doImmediateSeqUpdate - doc exists, need to get rev and update
[39m
2016-10-20 08:16:59 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-20 08:16:59 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

[36mok 50 should be equal
ok 51 revs are equal
[39m
[36m# teardown
[39m
[33mok 50 should be equal
[39m
[33mok 51 revs are equal
[39m
[33m# teardown
[39m
[32mok 50 should be equal
[39m
[32mok 51 revs are equal
[39m
2016-10-20 08:16:59 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''
2016-10-20 08:16:59 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

[32m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-10-20 08:16:59 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-20 08:16:59 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - update seq three times''

[32m# #_doImmediateSeqUpdate - update seq three times
[39m
[36m# #_doImmediateSeqUpdate - update seq three times
[39m
[33m# #_doImmediateSeqUpdate - update seq three times
[39m
2016-10-20 08:16:59 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - update seq three times''

2016-10-20 08:16:59 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - update seq three times''

[33mok 52 should be equal
[39m
[33mok 53 revs are equal
[39m
[36mok 52 should be equal
[39m
[36mok 53 revs are equal
[39m
[36mok 54 should be equal
[39m
[36mok 55 revs are equal
[39m
[32mok 52 should be equal
[39m
[32mok 53 revs are equal
[39m
[33mok 54 should be equal
[39m
[33mok 55 revs are equal
[39m
[32mok 54 should be equal
[39m
[32mok 55 revs are equal
[39m
[33mok 56 should be equal
[39m
[33mok 57 revs are equal
[39m
[33m# teardown
[39m
[32mok 56 should be equal
ok 57 revs are equal
[39m
[32m# teardown
[39m
[36mok 56 should be equal
ok 57 revs are equal
[39m
2016-10-20 08:16:59 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - update seq three times''
2016-10-20 08:16:59 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - update seq three times''

[33m# setup
[39m
[32m# setup
[39m
[36m# teardown
[39m
[36m# setup
[39m
2016-10-20 08:17:00 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - update seq three times''
2016-10-20 08:17:00 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - rev got changed under us''

[33m# #_doImmediateSeqUpdate - rev got changed under us
[39m
[32m# #_doImmediateSeqUpdate - rev got changed under us
[39m
[36m# #_doImmediateSeqUpdate - rev got changed under us
[39m
2016-10-20 08:17:00 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-20 08:17:00 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - rev got changed under us''

[32m2016-10-20 08:17:00 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
[39m
[32mok 58 Our rev is old so we should fail
[39m
[32m# teardown
[39m
[33m2016-10-20 08:17:00 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
[39m
[33mok 58 Our rev is old so we should fail
[39m
[33m# teardown
[39m
[36m2016-10-20 08:17:00 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
[39m
[36mok 58 Our rev is old so we should fail
[39m
2016-10-20 08:17:00 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-20 08:17:00 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - rev got changed under us''

[32m# setup
[39m
[33m# setup
[39m
[36m# teardown
[39m
[36m# setup
[39m
2016-10-20 08:17:01 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - rev got changed under us''
2016-10-20 08:17:01 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - fail if stop is called''

[33m# #_doImmediateSeqUpdate - fail if stop is called
[39m
[36m# #_doImmediateSeqUpdate - fail if stop is called
[39m
[32m# #_doImmediateSeqUpdate - fail if stop is called
[39m
2016-10-20 08:17:01 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - fail if stop is called''
2016-10-20 08:17:01 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - fail if stop is called''

[33mok 59 confirm stop caused failure
# teardown
[39m
[36mok 59 confirm stop caused failure
# teardown
[39m
[32mok 59 confirm stop caused failure
[39m
[32m# teardown
[39m
2016-10-20 08:17:01 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-20 08:17:01 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - fail if stop is called''

[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-10-20 08:17:01 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-20 08:17:01 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - stop after get but before put fails right''

[33m# #_doImmediateSeqUpdate - stop after get but before put fails right
[39m
[36m# #_doImmediateSeqUpdate - stop after get but before put fails right
[39m
[32m# #_doImmediateSeqUpdate - stop after get but before put fails right
[39m
2016-10-20 08:17:01 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-20 08:17:01 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - stop after get but before put fails right''

[36m2016-10-20 08:17:01 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
[39m
[36mok 60 stop caused us to fail
[39m
[36mok 61 We specifically failed on a stop before put
[39m
[36m# teardown
[39m
[32m2016-10-20 08:17:01 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
[39m
[32mok 60 stop caused us to fail
[39m
[32mok 61 We specifically failed on a stop before put
[39m
[32m# teardown
[39m
[33m2016-10-20 08:17:01 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
[39m
[33mok 60 stop caused us to fail
[39m
[33mok 61 We specifically failed on a stop before put
[39m
2016-10-20 08:17:01 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-20 08:17:01 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - stop after get but before put fails right''

[36m# setup
[39m
[32m# setup
[39m
[33m# teardown
[39m
[33m# setup
[39m
2016-10-20 08:17:02 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-20 08:17:02 - DEBUG UnitTestFramework: '#setup: '#update - fail if stop is called''

[33m# #update - fail if stop is called
[39m
[32m# #update - fail if stop is called
[39m
[36m# #update - fail if stop is called
[39m
2016-10-20 08:17:02 - DEBUG UnitTestFramework: '#setup ok: '#update - fail if stop is called''
2016-10-20 08:17:02 - DEBUG UnitTestFramework: '#run: '#update - fail if stop is called''

[33mok 62 failed due to stop
ok 63 failed due to stop
# teardown
[39m
[32mok 62 failed due to stop
ok 63 failed due to stop
# teardown
[39m
[36mok 62 failed due to stop
[39m
[36mok 63 failed due to stop
[39m
[36m# teardown
[39m
2016-10-20 08:17:02 - DEBUG UnitTestFramework: '#run ok: '#update - fail if stop is called''

2016-10-20 08:17:02 - DEBUG UnitTestFramework: '#teardown: '#update - fail if stop is called''

[33m# setup
[39m
[32m# setup
[39m
[36m# setup
[39m
2016-10-20 08:17:02 - DEBUG UnitTestFramework: '#teardown ok: '#update - fail if stop is called''

2016-10-20 08:17:02 - DEBUG UnitTestFramework: '#setup: '#update - set seq for first time''

[33m# #update - set seq for first time
[39m
[36m# #update - set seq for first time
[39m
[32m# #update - set seq for first time
[39m
2016-10-20 08:17:02 - DEBUG UnitTestFramework: '#setup ok: '#update - set seq for first time''

2016-10-20 08:17:02 - DEBUG UnitTestFramework: '#run: '#update - set seq for first time''

[36mok 64 should be equal
[39m
[33mok 64 should be equal
[39m
[32mok 64 should be equal
[39m
[33m# teardown
[39m
[32m# teardown
[39m
2016-10-20 08:17:03 - DEBUG UnitTestFramework: '#run ok: '#update - set seq for first time''
2016-10-20 08:17:03 - DEBUG UnitTestFramework: '#teardown: '#update - set seq for first time''

[33m# setup
[39m
[32m# setup
[39m
[36m# teardown
[39m
[36m# setup
[39m
2016-10-20 08:17:04 - DEBUG UnitTestFramework: '#teardown ok: '#update - set seq for first time''
2016-10-20 08:17:04 - DEBUG UnitTestFramework: '#setup: '#update - Fail on bad seq value''

[33m# #update - Fail on bad seq value
[39m
[32m# #update - Fail on bad seq value
[39m
[36m# #update - Fail on bad seq value
[39m
2016-10-20 08:17:04 - DEBUG UnitTestFramework: '#setup ok: '#update - Fail on bad seq value''
2016-10-20 08:17:04 - DEBUG UnitTestFramework: '#run: '#update - Fail on bad seq value''

[36m2016-10-20 08:17:04 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
ok 65 Expected bad seq error
# teardown
[39m
[33m2016-10-20 08:17:04 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
[39m
[33mok 65 Expected bad seq error
[39m
[33m# teardown
[39m
[32m2016-10-20 08:17:04 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
[39m
[32mok 65 Expected bad seq error
[39m
2016-10-20 08:17:04 - DEBUG UnitTestFramework: '#run ok: '#update - Fail on bad seq value''

2016-10-20 08:17:04 - DEBUG UnitTestFramework: '#teardown: '#update - Fail on bad seq value''

[32m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-10-20 08:17:04 - DEBUG UnitTestFramework: '#teardown ok: '#update - Fail on bad seq value''

2016-10-20 08:17:04 - DEBUG UnitTestFramework: '#setup: '#update - do we cancel timer properly on an immediate?''

[36m# #update - do we cancel timer properly on an immediate?
[39m
[33m# #update - do we cancel timer properly on an immediate?
[39m
[32m# #update - do we cancel timer properly on an immediate?
[39m
2016-10-20 08:17:04 - DEBUG UnitTestFramework: '#setup ok: '#update - do we cancel timer properly on an immediate?''

2016-10-20 08:17:04 - DEBUG UnitTestFramework: '#run: '#update - do we cancel timer properly on an immediate?''

[33m(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
[39m
[33mTrace
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
    at process._tickCallback (node.js:917:13)
[39m
[36m(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
[39m
[36mTrace
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
    at process._tickCallback (node.js:917:13)
[39m
[32m(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
[39m
[32mTrace
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
    at process._tickCallback (node.js:917:13)
[39m
[33mok 66 Different promises
[39m
[33mok 67 Timer was cancelled
[39m
[33mok 68 should be equal
[39m
[33m# teardown
[39m
[36mok 66 Different promises
[39m
[32mok 66 Different promises
[39m
[36mnot ok 67 timerPromise should have failed.
[39m
[36m  ---
    operator: fail
[39m
[36m    at: Array.0 (/Users/thali/Github/Thali_CordovaPlugin/thali/node_modules/lie/lib/index.js:88:21)
[39m
[36m  ...
[39m
[32mnot ok 67 timerPromise should have failed.
  ---
    operator: fail
    at: Array.0 (/Users/thali/Github/Thali_CordovaPlugin/thali/node_modules/lie/lib/index.js:88:21)
  ...
[39m
[36mok 68 should be equal
[39m
[36m2016-10-20 08:17:05 - ERROR CoordinatedClient: 'test failed, name: '#update - do we cancel timer properly on an immediate?''
[39m
[36m2016-10-20 08:17:05 - ERROR CoordinatedClient: 'unexpected error: 'Error: test failed, name: '#update - do we cancel timer properly on an immediate?'', stack: 'Error: test failed, name: '#update - do we cancel timer properly on an immediate?'
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/CoordinatedClient.js:365:22
    at process._tickCallback (node.js:917:13)''
[39m
[36m2016-10-20 08:17:05 - DEBUG CoordinatedClient: 'test client failed'
[39m
[36m2016-10-20 08:17:05 - DEBUG CoordinatedClient: 'device disconnected from the test server'
[39m
2016-10-20 08:17:05 - ERROR UnitTestFramework: '#run failed: '#update - do we cancel timer properly on an immediate?', error: 'Error: run failed, test: '#update - do we cancel timer properly on an immediate?', event: 'run_#update - do we cancel timer properly on an immediate?', sent data: '[{"uuid":"2d5ac673-605e-4611-8737-593c8c6f7f1d"},{"uuid":"40637163-426b-4188-bf38-3cba27f28b87"},{"uuid":"b324b363-53be-4949-919e-9ccbbf5b08af"}]', received data: '{"success":false}'', stack: 'Error: run failed, test: '#update - do we cancel timer properly on an immediate?', event: 'run_#update - do we cancel timer properly on an immediate?', sent data: '[{"uuid":"2d5ac673-605e-4611-8737-593c8c6f7f1d"},{"uuid":"40637163-426b-4188-bf38-3cba27f28b87"},{"uuid":"b324b363-53be-4949-919e-9ccbbf5b08af"}]', received data: '{"success":false}'
    at finishedHandler (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/Socket.js:205:15)
    at Socket.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/Socket.js:238:9)
    at Socket.g (events.js:291:16)
    at emitOne (events.js:96:13)
    at Socket.emit (events.js:188:7)
    at Socket.onevent (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/socket.io/lib/socket.js:335:8)
    at Socket.onpacket (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/socket.io/lib/socket.js:295:12)
    at Client.ondecoded (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/socket.io/lib/client.js:175:18)
    at emitOne (events.js:96:13)
    at Socket.emit (events.js:188:7)
    at Socket.onPacket (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/engine.io/lib/socket.js:101:14)
    at emitOne (events.js:96:13)
    at WebSocket.emit (events.js:188:7)
From previous event:
    at Socket.runEvent (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/Socket.js:233:10)
    at TestDevice.runTest (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/TestDevice.js:115:23)
    at /Users/thali/Github/Thali_CordovaPlugin/test/TestServer/UnitTestFramework.js:135:23
    at Array.map (native)
    at /Users/thali/Github/Thali_CordovaPlugin/test/TestServer/UnitTestFramework.js:134:15
From previous event:
    at UnitTestFramework.runTest (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/UnitTestFramework.js:129:4)
    at /Users/thali/Github/Thali_CordovaPlugin/test/TestServer/UnitTestFramework.js:54:21
From previous event:
    at /Users/thali/Github/Thali_CordovaPlugin/test/TestServer/UnitTestFramework.js:53:22
    at Array.reduce (native)
    at /Users/thali/Github/Thali_CordovaPlugin/test/TestServer/UnitTestFramework.js:52:18
    at runCallback (timers.js:574:20)
    at tryOnImmediate (timers.js:554:5)
From previous event:
    at UnitTestFramework.startTests (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/UnitTestFramework.js:46:4)
    at UnitTestFramework.TestFramework.addDevice (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/TestFramework.js:174:10)
    at Server.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/index.js:34:23)
    at emitOne (events.js:96:13)
    at Server.emit (events.js:188:7)
    at Server._present (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/HttpServer.js:92:8)
    at emitOne (events.js:96:13)
    at Socket.emit (events.js:188:7)
    at Socket.onevent (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/socket.io/lib/socket.js:335:8)
    at Socket.onpacket (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/socket.io/lib/socket.js:295:12)
    at Client.ondecoded (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/socket.io/lib/client.js:175:18)
    at emitOne (events.js:96:13)
    at Socket.emit (events.js:188:7)
    at Socket.onPacket (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/engine.io/lib/socket.js:101:14)
    at emitOne (events.js:96:13)
    at WebSocket.emit (events.js:188:7)''

[36m2016-10-20 08:17:05 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: test failed, name: '#update - do we cancel timer properly on an immediate?'', stack: 'Error: test failed, name: '#update - do we cancel timer properly on an immediate?'
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/CoordinatedClient.js:365:22
    at process._tickCallback (node.js:917:13)''
[39m
[36m2016-10-20 08:17:05 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
[39m
[36m2016-10-20 08:17:05 - ERROR runTests: 'test failed, name: '#update - do we cancel timer properly on an immediate?'
Error: test failed, name: '#update - do we cancel timer properly on an immediate?'
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/CoordinatedClient.js:365:22
    at process._tickCallback (node.js:917:13)'
[39m
2016-10-20 08:17:05 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'desktop', error: 'Error: run failed, test: '#update - do we cancel timer properly on an immediate?', event: 'run_#update - do we cancel timer properly on an immediate?', sent data: '[{"uuid":"2d5ac673-605e-4611-8737-593c8c6f7f1d"},{"uuid":"40637163-426b-4188-bf38-3cba27f28b87"},{"uuid":"b324b363-53be-4949-919e-9ccbbf5b08af"}]', received data: '{"success":false}'', stack: 'Error: run failed, test: '#update - do we cancel timer properly on an immediate?', event: 'run_#update - do we cancel timer properly on an immediate?', sent data: '[{"uuid":"2d5ac673-605e-4611-8737-593c8c6f7f1d"},{"uuid":"40637163-426b-4188-bf38-3cba27f28b87"},{"uuid":"b324b363-53be-4949-919e-9ccbbf5b08af"}]', received data: '{"success":false}'
    at finishedHandler (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/Socket.js:205:15)
    at Socket.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/Socket.js:238:9)
    at Socket.g (events.js:291:16)
    at emitOne (events.js:96:13)
    at Socket.emit (events.js:188:7)
    at Socket.onevent (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/socket.io/lib/socket.js:335:8)
    at Socket.onpacket (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/socket.io/lib/socket.js:295:12)
    at Client.ondecoded (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/socket.io/lib/client.js:175:18)
    at emitOne (events.js:96:13)
    at Socket.emit (events.js:188:7)
    at Socket.onPacket (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/engine.io/lib/socket.js:101:14)
    at emitOne (events.js:96:13)
    at WebSocket.emit (events.js:188:7)
From previous event:
    at Socket.runEvent (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/Socket.js:233:10)
    at TestDevice.runTest (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/TestDevice.js:115:23)
    at /Users/thali/Github/Thali_CordovaPlugin/test/TestServer/UnitTestFramework.js:135:23
    at Array.map (native)
    at /Users/thali/Github/Thali_CordovaPlugin/test/TestServer/UnitTestFramework.js:134:15
From previous event:
    at UnitTestFramework.runTest (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/UnitTestFramework.js:129:4)
    at /Users/thali/Github/Thali_CordovaPlugin/test/TestServer/UnitTestFramework.js:54:21
From previous event:
    at /Users/thali/Github/Thali_CordovaPlugin/test/TestServer/UnitTestFramework.js:53:22
    at Array.reduce (native)
    at /Users/thali/Github/Thali_CordovaPlugin/test/TestServer/UnitTestFramework.js:52:18
    at runCallback (timers.js:574:20)
    at tryOnImmediate (timers.js:554:5)
From previous event:
    at UnitTestFramework.startTests (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/UnitTestFramework.js:46:4)
    at UnitTestFramework.TestFramework.addDevice (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/TestFramework.js:174:10)
    at Server.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/index.js:34:23)
    at emitOne (events.js:96:13)
    at Server.emit (events.js:188:7)
    at Server._present (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/HttpServer.js:92:8)
    at emitOne (events.js:96:13)
    at Socket.emit (events.js:188:7)
    at Socket.onevent (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/socket.io/lib/socket.js:335:8)
    at Socket.onpacket (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/socket.io/lib/socket.js:295:12)
    at Client.ondecoded (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/socket.io/lib/client.js:175:18)
    at emitOne (events.js:96:13)
    at Socket.emit (events.js:188:7)
    at Socket.onPacket (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/engine.io/lib/socket.js:101:14)
    at emitOne (events.js:96:13)
    at WebSocket.emit (events.js:188:7)''

2016-10-20 08:17:05 - ERROR HttpServer: 'unexpected server error: 'Error: run failed, test: '#update - do we cancel timer properly on an immediate?', event: 'run_#update - do we cancel timer properly on an immediate?', sent data: '[{"uuid":"2d5ac673-605e-4611-8737-593c8c6f7f1d"},{"uuid":"40637163-426b-4188-bf38-3cba27f28b87"},{"uuid":"b324b363-53be-4949-919e-9ccbbf5b08af"}]', received data: '{"success":false}'''

2016-10-20 08:17:05 - ERROR HttpServer: 'unexpected server error: 'Error: run failed, test: '#update - do we cancel timer properly on an immediate?', event: 'run_#update - do we cancel timer properly on an immediate?', sent data: '[{"uuid":"2d5ac673-605e-4611-8737-593c8c6f7f1d"},{"uuid":"40637163-426b-4188-bf38-3cba27f28b87"},{"uuid":"b324b363-53be-4949-919e-9ccbbf5b08af"}]', received data: '{"success":false}'''

2016-10-20 08:17:05 - ERROR HttpServer: 'unexpected server error: 'Error: run failed, test: '#update - do we cancel timer properly on an immediate?', event: 'run_#update - do we cancel timer properly on an immediate?', sent data: '[{"uuid":"2d5ac673-605e-4611-8737-593c8c6f7f1d"},{"uuid":"40637163-426b-4188-bf38-3cba27f28b87"},{"uuid":"b324b363-53be-4949-919e-9ccbbf5b08af"}]', received data: '{"success":false}'''

2016-10-20 08:17:05 - ERROR UnitTestFramework: 'unexpected error: 'Error: Error: run failed, test: '#update - do we cancel timer properly on an immediate?', event: 'run_#update - do we cancel timer properly on an immediate?', sent data: '[{"uuid":"2d5ac673-605e-4611-8737-593c8c6f7f1d"},{"uuid":"40637163-426b-4188-bf38-3cba27f28b87"},{"uuid":"b324b363-53be-4949-919e-9ccbbf5b08af"}]', received data: '{"success":false}'', stack: 'Error: Error: run failed, test: '#update - do we cancel timer properly on an immediate?', event: 'run_#update - do we cancel timer properly on an immediate?', sent data: '[{"uuid":"2d5ac673-605e-4611-8737-593c8c6f7f1d"},{"uuid":"40637163-426b-4188-bf38-3cba27f28b87"},{"uuid":"b324b363-53be-4949-919e-9ccbbf5b08af"}]', received data: '{"success":false}'
    at Server._error (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/HttpServer.js:78:9)
    at emitOne (events.js:96:13)
    at Socket.emit (events.js:188:7)
    at Socket.emit (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/socket.io/lib/socket.js:128:10)
    at updatedHandler (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/Socket.js:105:29)
    at Socket._apply (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/Socket.js:108:3)
    at emit (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/Socket.js:167:22)
    at /Users/thali/Github/Thali_CordovaPlugin/test/TestServer/Socket.js:171:5
    at Socket.emitData (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/Socket.js:136:10)
    at TestDevice.error (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/TestDevice.js:137:23)
    at /Users/thali/Github/Thali_CordovaPlugin/test/TestServer/UnitTestFramework.js:86:23
    at Array.map (native)
    at /Users/thali/Github/Thali_CordovaPlugin/test/TestServer/UnitTestFramework.js:85:15
From previous event:
    at UnitTestFramework.startTests (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/UnitTestFramework.js:78:9)
    at UnitTestFramework.TestFramework.addDevice (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/TestFramework.js:174:10)
    at Server.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/index.js:34:23)
    at emitOne (events.js:96:13)
    at Server.emit (events.js:188:7)
    at Server._present (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/HttpServer.js:92:8)
    at emitOne (events.js:96:13)
    at Socket.emit (events.js:188:7)
    at Socket.onevent (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/socket.io/lib/socket.js:335:8)
    at Socket.onpacket (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/socket.io/lib/socket.js:295:12)
    at Client.ondecoded (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/socket.io/lib/client.js:175:18)
    at emitOne (events.js:96:13)
    at Socket.emit (events.js:188:7)
    at Socket.onPacket (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/engine.io/lib/socket.js:101:14)
    at emitOne (events.js:96:13)''

2016-10-20 08:17:05 - ERROR UnitTestFramework: 'unexpected error: 'Error: Error: run failed, test: '#update - do we cancel timer properly on an immediate?', event: 'run_#update - do we cancel timer properly on an immediate?', sent data: '[{"uuid":"2d5ac673-605e-4611-8737-593c8c6f7f1d"},{"uuid":"40637163-426b-4188-bf38-3cba27f28b87"},{"uuid":"b324b363-53be-4949-919e-9ccbbf5b08af"}]', received data: '{"success":false}'', stack: 'Error: Error: run failed, test: '#update - do we cancel timer properly on an immediate?', event: 'run_#update - do we cancel timer properly on an immediate?', sent data: '[{"uuid":"2d5ac673-605e-4611-8737-593c8c6f7f1d"},{"uuid":"40637163-426b-4188-bf38-3cba27f28b87"},{"uuid":"b324b363-53be-4949-919e-9ccbbf5b08af"}]', received data: '{"success":false}'
    at Server._error (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/HttpServer.js:78:9)
    at emitOne (events.js:96:13)
    at Socket.emit (events.js:188:7)
    at Socket.emit (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/socket.io/lib/socket.js:128:10)
    at updatedHandler (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/Socket.js:105:29)
    at Socket._apply (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/Socket.js:108:3)
    at emit (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/Socket.js:167:22)
    at /Users/thali/Github/Thali_CordovaPlugin/test/TestServer/Socket.js:171:5
    at Socket.emitData (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/Socket.js:136:10)
    at TestDevice.error (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/TestDevice.js:137:23)
    at /Users/thali/Github/Thali_CordovaPlugin/test/TestServer/UnitTestFramework.js:86:23
    at Array.map (native)
    at /Users/thali/Github/Thali_CordovaPlugin/test/TestServer/UnitTestFramework.js:85:15
From previous event:
    at UnitTestFramework.startTests (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/UnitTestFramework.js:78:9)
    at UnitTestFramework.TestFramework.addDevice (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/TestFramework.js:174:10)
    at Server.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/index.js:34:23)
    at emitOne (events.js:96:13)
    at Server.emit (events.js:188:7)
    at Server._present (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/HttpServer.js:92:8)
    at emitOne (events.js:96:13)
    at Socket.emit (events.js:188:7)
    at Socket.onevent (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/socket.io/lib/socket.js:335:8)
    at Socket.onpacket (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/socket.io/lib/socket.js:295:12)
    at Client.ondecoded (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/socket.io/lib/client.js:175:18)
    at emitOne (events.js:96:13)
    at Socket.emit (events.js:188:7)
    at Socket.onPacket (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/engine.io/lib/socket.js:101:14)
    at emitOne (events.js:96:13)''
2016-10-20 08:17:05 - ERROR UnitTestFramework: 'unexpected error: 'Error: Error: run failed, test: '#update - do we cancel timer properly on an immediate?', event: 'run_#update - do we cancel timer properly on an immediate?', sent data: '[{"uuid":"2d5ac673-605e-4611-8737-593c8c6f7f1d"},{"uuid":"40637163-426b-4188-bf38-3cba27f28b87"},{"uuid":"b324b363-53be-4949-919e-9ccbbf5b08af"}]', received data: '{"success":false}'', stack: 'Error: Error: run failed, test: '#update - do we cancel timer properly on an immediate?', event: 'run_#update - do we cancel timer properly on an immediate?', sent data: '[{"uuid":"2d5ac673-605e-4611-8737-593c8c6f7f1d"},{"uuid":"40637163-426b-4188-bf38-3cba27f28b87"},{"uuid":"b324b363-53be-4949-919e-9ccbbf5b08af"}]', received data: '{"success":false}'
    at Server._error (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/HttpServer.js:78:9)
    at emitOne (events.js:96:13)
    at Socket.emit (events.js:188:7)
    at Socket.emit (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/socket.io/lib/socket.js:128:10)
    at updatedHandler (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/Socket.js:105:29)
    at Socket._apply (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/Socket.js:108:3)
    at emit (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/Socket.js:167:22)
    at /Users/thali/Github/Thali_CordovaPlugin/test/TestServer/Socket.js:171:5
    at Socket.emitData (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/Socket.js:136:10)
    at TestDevice.error (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/TestDevice.js:137:23)
    at /Users/thali/Github/Thali_CordovaPlugin/test/TestServer/UnitTestFramework.js:86:23
    at Array.map (native)
    at /Users/thali/Github/Thali_CordovaPlugin/test/TestServer/UnitTestFramework.js:85:15
From previous event:
    at UnitTestFramework.startTests (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/UnitTestFramework.js:78:9)
    at UnitTestFramework.TestFramework.addDevice (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/TestFramework.js:174:10)
    at Server.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/index.js:34:23)
    at emitOne (events.js:96:13)
    at Server.emit (events.js:188:7)
    at Server._present (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/HttpServer.js:92:8)
    at emitOne (events.js:96:13)
    at Socket.emit (events.js:188:7)
    at Socket.onevent (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/socket.io/lib/socket.js:335:8)
    at Socket.onpacket (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/socket.io/lib/socket.js:295:12)
    at Client.ondecoded (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/socket.io/lib/client.js:175:18)
    at emitOne (events.js:96:13)
    at Socket.emit (events.js:188:7)
    at Socket.onPacket (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/engine.io/lib/socket.js:101:14)
    at emitOne (events.js:96:13)''

[33m2016-10-20 08:17:05 - DEBUG CoordinatedClient: 'all tests completed'
[39m
[32m2016-10-20 08:17:05 - DEBUG CoordinatedClient: 'all tests completed'
[39m
[32mok 68 should be equal
2016-10-20 08:17:05 - ERROR CoordinatedClient: 'test failed, name: '#update - do we cancel timer properly on an immediate?''
2016-10-20 08:17:05 - ERROR CoordinatedClient: 'unexpected error: 'Error: test failed, name: '#update - do we cancel timer properly on an immediate?'', stack: 'Error: test failed, name: '#update - do we cancel timer properly on an immediate?'
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/CoordinatedClient.js:365:22
    at process._tickCallback (node.js:917:13)''
2016-10-20 08:17:05 - DEBUG CoordinatedClient: 'test client failed'
2016-10-20 08:17:05 - DEBUG CoordinatedClient: 'test client disconnected'
2016-10-20 08:17:05 - DEBUG CoordinatedClient: 'test client succeed'
[39m
[32m2016-10-20 08:17:05 - DEBUG CoordinatedThaliTape: 'all tests succeed'
[39m
[32m2016-10-20 08:17:05 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'
[39m
[32m2016-10-20 08:17:05 - INFO runTests: 'Finished'
[39m
-e [0;31mcompilation aborted
 [0m
build aborted
 [0m

npm WARN thali-test-server@0.0.1 No repository field.
npm WARN thali-test-server@0.0.1 No license field.
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/forever-agent
npm http request GET http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/javascript-state-machine
npm http request GET http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/bluebird
npm http 200 http://192.168.1.100:4873/ip
npm http 304 http://192.168.1.100:4873/express
npm http 200 http://192.168.1.100:4873/forever-agent
npm http 304 http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/body-parser
npm http 200 http://192.168.1.100:4873/long
npm http 200 http://192.168.1.100:4873/lie
npm http 200 http://192.168.1.100:4873/multiplex
npm http 200 http://192.168.1.100:4873/javascript-state-machine
npm http 200 http://192.168.1.100:4873/uuid
npm http 200 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/raw-body
npm http request GET http://192.168.1.100:4873/type-is
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/http-errors
npm http 200 http://192.168.1.100:4873/bytes
npm http 304 http://192.168.1.100:4873/on-finished
npm http 200 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/type-is
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
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/serve-static
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/send
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
npm http request GET http://192.168.1.100:4873/immediate
npm http 200 http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/xtend
npm http 200 http://192.168.1.100:4873/xtend
npm http 200 http://192.168.1.100:4873/duplexify
npm http fetch GET http://192.168.1.100:4873/duplexify/-/duplexify-3.4.6.tgz
npm http 200 http://192.168.1.100:4873/readable-stream
npm http fetch 200 http://192.168.1.100:4873/duplexify/-/duplexify-3.4.6.tgz
npm http 200 http://192.168.1.100:4873/varint
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
npm http request GET http://192.168.1.100:4873/string_decoder
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 200 http://192.168.1.100:4873/process-nextick-args
npm http 304 http://192.168.1.100:4873/isarray
npm http 200 http://192.168.1.100:4873/buffer-shims
npm http 200 http://192.168.1.100:4873/string_decoder
npm http 200 http://192.168.1.100:4873/core-util-is
npm http 200 http://192.168.1.100:4873/util-deprecate
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/har-validator
npm http 200 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 200 http://192.168.1.100:4873/caseless
npm http 200 http://192.168.1.100:4873/form-data
npm http 200 http://192.168.1.100:4873/bl
npm http 200 http://192.168.1.100:4873/oauth-sign
npm http 200 http://192.168.1.100:4873/tunnel-agent
npm http 200 http://192.168.1.100:4873/json-stringify-safe
npm http 200 http://192.168.1.100:4873/http-signature
npm http 200 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/hawk
npm http 200 http://192.168.1.100:4873/combined-stream
npm http 200 http://192.168.1.100:4873/aws-sign2
npm http 200 http://192.168.1.100:4873/stringstream
npm http 200 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 200 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http fetch GET http://192.168.1.100:4873/async/-/async-2.1.2.tgz
npm http fetch 200 http://192.168.1.100:4873/async/-/async-2.1.2.tgz
npm http request GET http://192.168.1.100:4873/lodash
npm http 200 http://192.168.1.100:4873/lodash
npm http fetch GET http://192.168.1.100:4873/lodash/-/lodash-4.16.4.tgz
npm http fetch 200 http://192.168.1.100:4873/lodash/-/lodash-4.16.4.tgz
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http 200 http://192.168.1.100:4873/is-my-json-valid
npm http 200 http://192.168.1.100:4873/chalk
npm http 200 http://192.168.1.100:4873/commander
npm http fetch GET http://192.168.1.100:4873/is-my-json-valid/-/is-my-json-valid-2.15.0.tgz
npm http fetch 200 http://192.168.1.100:4873/is-my-json-valid/-/is-my-json-valid-2.15.0.tgz
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 200 http://192.168.1.100:4873/has-ansi
npm http 200 http://192.168.1.100:4873/ansi-styles
npm http 200 http://192.168.1.100:4873/supports-color
npm http 200 http://192.168.1.100:4873/escape-string-regexp
npm http 200 http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 200 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http 200 http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 200 http://192.168.1.100:4873/generate-object-property
npm http 200 http://192.168.1.100:4873/jsonpointer
npm http 200 http://192.168.1.100:4873/generate-function
npm http fetch GET http://192.168.1.100:4873/jsonpointer/-/jsonpointer-4.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/jsonpointer/-/jsonpointer-4.0.0.tgz
npm http request GET http://192.168.1.100:4873/is-property
npm http 200 http://192.168.1.100:4873/is-property
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
npm http 200 http://192.168.1.100:4873/asn1
npm http 200 http://192.168.1.100:4873/assert-plus
npm http 200 http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/jsonschema
npm http request GET http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/jsonschema
npm http fetch GET http://192.168.1.100:4873/jsonschema/-/jsonschema-1.1.0.tgz
npm http fetch 200 http://192.168.1.100:4873/jsonschema/-/jsonschema-1.1.0.tgz
npm http request GET http://192.168.1.100:4873/colors
npm http request GET http://192.168.1.100:4873/cycle
npm http request GET http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/pkginfo
npm http request GET http://192.168.1.100:4873/stack-trace
npm http 304 http://192.168.1.100:4873/cycle
npm http 304 http://192.168.1.100:4873/eyes
npm http 304 http://192.168.1.100:4873/colors
npm http 304 http://192.168.1.100:4873/pkginfo
npm http 304 http://192.168.1.100:4873/stack-trace
npm http request GET http://192.168.1.100:4873/jsdoc
npm http 200 http://192.168.1.100:4873/jsdoc
npm http request GET http://192.168.1.100:4873/js2xmlparser
npm http request GET http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/catharsis
npm http request GET http://192.168.1.100:4873/marked
npm http request GET http://192.168.1.100:4873/requizzle
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/underscore
npm http request GET http://192.168.1.100:4873/wrench
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 200 http://192.168.1.100:4873/catharsis
npm http 200 http://192.168.1.100:4873/esprima
npm http 200 http://192.168.1.100:4873/js2xmlparser
npm http 200 http://192.168.1.100:4873/marked
npm http 200 http://192.168.1.100:4873/requizzle
npm http 200 http://192.168.1.100:4873/strip-json-comments
npm http 200 http://192.168.1.100:4873/underscore
npm http 200 http://192.168.1.100:4873/wrench
npm WARN deprecated wrench@1.5.9: wrench.js is deprecated! You should check out fs-extra (https://github.com/jprichardson/node-fs-extra) for any operations you were using wrench for. Thanks for all the usage over the years.
npm http fetch 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http request GET http://192.168.1.100:4873/underscore-contrib
npm http 200 http://192.168.1.100:4873/underscore-contrib
npm WARN prefer global marked@0.3.6 should be installed with -g
npm WARN install@0.0.1 No repository field.
npm http request GET http://192.168.1.100:4873/uuid-validate
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/child-process-promise
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/bn.js
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/forever-agent
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/express-pouchdb
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/leveldown-mobile
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/pouchdb-size
npm http request GET http://192.168.1.100:4873/pouchdb
npm http request GET http://192.168.1.100:4873/nock
npm http request GET http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/proxyquire
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/request-promise
npm http request GET http://192.168.1.100:4873/sinon
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/supertest
npm http request GET http://192.168.1.100:4873/tape-catch
npm http request GET http://192.168.1.100:4873/supertest-as-promised
npm http request GET http://192.168.1.100:4873/tape
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/tmp
npm http request GET http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/child-process-promise
npm http 200 http://192.168.1.100:4873/uuid-validate
npm http fetch GET http://192.168.1.100:4873/uuid-validate/-/uuid-validate-0.0.2.tgz
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/js-extend
npm http 200 http://192.168.1.100:4873/bn.js
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/forever-agent
npm http 304 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/multiplex
npm http 200 http://192.168.1.100:4873/express-pouchdb
npm http 304 http://192.168.1.100:4873/node-uuid
npm http fetch GET http://192.168.1.100:4873/express-pouchdb/-/express-pouchdb-1.0.5-thali.tgz
npm http 200 http://192.168.1.100:4873/pouchdb-size
npm http 304 http://192.168.1.100:4873/randomstring
npm http 200 http://192.168.1.100:4873/proxyquire
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/leveldown-mobile
npm http 304 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/pouchdb
npm http 200 http://192.168.1.100:4873/nock
npm http 304 http://192.168.1.100:4873/socket.io-client
npm http 200 http://192.168.1.100:4873/supertest
npm http 200 http://192.168.1.100:4873/request-promise
npm http 304 http://192.168.1.100:4873/uuid
npm http 200 http://192.168.1.100:4873/tape-catch
npm http 200 http://192.168.1.100:4873/supertest-as-promised
npm http fetch 200 http://192.168.1.100:4873/uuid-validate/-/uuid-validate-0.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/express-pouchdb/-/express-pouchdb-1.0.5-thali.tgz
npm http 200 http://192.168.1.100:4873/tmp
npm http 200 http://192.168.1.100:4873/sinon
npm http 304 http://192.168.1.100:4873/object-assign
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
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/iconv-lite
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
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/send
npm http 304 http://192.168.1.100:4873/serve-static
npm http 304 http://192.168.1.100:4873/range-parser
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
npm http request GET http://192.168.1.100:4873/compression
npm http request GET http://192.168.1.100:4873/cookie-parser
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/pouchdb-all-dbs
npm http request GET http://192.168.1.100:4873/multiparty
npm http request GET http://192.168.1.100:4873/basic-auth
npm http request GET http://192.168.1.100:4873/pouchdb-auth
npm http request GET http://192.168.1.100:4873/pouchdb-list
npm http request GET http://192.168.1.100:4873/header-case-normalizer
npm http request GET http://192.168.1.100:4873/pouchdb-rewrite
npm http request GET http://192.168.1.100:4873/pouchdb-replicator
npm http request GET http://192.168.1.100:4873/pouchdb-find
npm http request GET http://192.168.1.100:4873/pouchdb-security
npm http request GET http://192.168.1.100:4873/pouchdb-wrappers
npm http request GET http://192.168.1.100:4873/pouchdb-show
npm http request GET http://192.168.1.100:4873/pouchdb-vhost
npm http request GET http://192.168.1.100:4873/pouchdb-validation
npm http request GET http://192.168.1.100:4873/pouchdb-update
npm http 304 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/compression
npm http 200 http://192.168.1.100:4873/cookie-parser
npm http 200 http://192.168.1.100:4873/multiparty
npm http 200 http://192.168.1.100:4873/basic-auth
npm http 200 http://192.168.1.100:4873/pouchdb-all-dbs
npm http 200 http://192.168.1.100:4873/pouchdb-list
npm http 200 http://192.168.1.100:4873/pouchdb-rewrite
npm http 200 http://192.168.1.100:4873/pouchdb-replicator
npm http 200 http://192.168.1.100:4873/pouchdb-find
npm http 200 http://192.168.1.100:4873/pouchdb-wrappers
npm http 200 http://192.168.1.100:4873/header-case-normalizer
npm http 200 http://192.168.1.100:4873/pouchdb-auth
npm http 200 http://192.168.1.100:4873/pouchdb-security
npm http 200 http://192.168.1.100:4873/pouchdb-update
npm http 200 http://192.168.1.100:4873/pouchdb-vhost
npm http 200 http://192.168.1.100:4873/pouchdb-show
npm http 200 http://192.168.1.100:4873/pouchdb-validation
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
npm http request GET http://192.168.1.100:4873/tiny-queue
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/es3ify
npm http 200 http://192.168.1.100:4873/pouchdb-promise
npm http 200 http://192.168.1.100:4873/tiny-queue
npm http 200 http://192.168.1.100:4873/argsarray
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
npm http request GET http://192.168.1.100:4873/pouchdb-req-http-query
npm http request GET http://192.168.1.100:4873/pouchdb-plugin-error
npm http request GET http://192.168.1.100:4873/promise-nodify
npm http request GET http://192.168.1.100:4873/pouchdb-system-db
npm http request GET http://192.168.1.100:4873/secure-random
npm http 200 http://192.168.1.100:4873/base64url
npm http 200 http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http 200 http://192.168.1.100:4873/couchdb-calculate-session-id
npm http fetch GET http://192.168.1.100:4873/couchdb-calculate-session-id/-/couchdb-calculate-session-id-1.1.1.tgz
npm http 200 http://192.168.1.100:4873/crypto-lite
npm http 200 http://192.168.1.100:4873/pouchdb-req-http-query
npm http fetch 200 http://192.168.1.100:4873/couchdb-calculate-session-id/-/couchdb-calculate-session-id-1.1.1.tgz
npm http 200 http://192.168.1.100:4873/pouchdb-plugin-error
npm http 200 http://192.168.1.100:4873/pouchdb-system-db
npm http 200 http://192.168.1.100:4873/promise-nodify
npm http 200 http://192.168.1.100:4873/secure-random
npm http request GET http://192.168.1.100:4873/meow
npm http request GET http://192.168.1.100:4873/concat-stream
npm http 200 http://192.168.1.100:4873/concat-stream
npm http 200 http://192.168.1.100:4873/meow
npm http request GET http://192.168.1.100:4873/typedarray
npm http 200 http://192.168.1.100:4873/typedarray
npm http request GET http://192.168.1.100:4873/camelcase-keys
npm http request GET http://192.168.1.100:4873/indent-string
npm http 200 http://192.168.1.100:4873/camelcase-keys
npm http 200 http://192.168.1.100:4873/indent-string
npm http request GET http://192.168.1.100:4873/camelcase
npm http request GET http://192.168.1.100:4873/map-obj
npm http 200 http://192.168.1.100:4873/map-obj
npm http 200 http://192.168.1.100:4873/camelcase
npm http request GET http://192.168.1.100:4873/repeating
npm http request GET http://192.168.1.100:4873/get-stdin
npm http 200 http://192.168.1.100:4873/repeating
npm http 200 http://192.168.1.100:4873/get-stdin
npm http request GET http://192.168.1.100:4873/is-finite
npm http 200 http://192.168.1.100:4873/is-finite
npm http fetch GET http://192.168.1.100:4873/is-finite/-/is-finite-1.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/is-finite/-/is-finite-1.0.2.tgz
npm http request GET http://192.168.1.100:4873/number-is-nan
npm http 200 http://192.168.1.100:4873/number-is-nan
npm http fetch GET http://192.168.1.100:4873/number-is-nan/-/number-is-nan-1.0.1.tgz
npm http fetch 200 http://192.168.1.100:4873/number-is-nan/-/number-is-nan-1.0.1.tgz
npm http request GET http://192.168.1.100:4873/aproba
npm http fetch GET http://192.168.1.100:4873/base64url/-/base64url-2.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/base64url/-/base64url-2.0.0.tgz
npm http 200 http://192.168.1.100:4873/aproba
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/es6-promise-pool
npm http request GET http://192.168.1.100:4873/fruitdown
npm http request GET http://192.168.1.100:4873/level-write-stream
npm http request GET http://192.168.1.100:4873/localstorage-down
npm http request GET http://192.168.1.100:4873/scope-eval
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/pouchdb-collate
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/memdown
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/vuvuzela
npm http 200 http://192.168.1.100:4873/double-ended-queue
npm http 200 http://192.168.1.100:4873/level-write-stream
npm http 200 http://192.168.1.100:4873/fruitdown
npm http 200 http://192.168.1.100:4873/localstorage-down
npm http 200 http://192.168.1.100:4873/es6-promise-pool
npm http 200 http://192.168.1.100:4873/scope-eval
npm http 200 http://192.168.1.100:4873/spark-md5
npm http 304 http://192.168.1.100:4873/through2
npm http 304 http://192.168.1.100:4873/js-extend
npm http 200 http://192.168.1.100:4873/pouchdb-collate
npm http 200 http://192.168.1.100:4873/pouchdb-collections
npm http 200 http://192.168.1.100:4873/memdown
npm http 304 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/vuvuzela
npm http 200 http://192.168.1.100:4873/sublevel-pouchdb
npm http 200 http://192.168.1.100:4873/levelup
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
npm http request GET http://192.168.1.100:4873/level-errors
npm http request GET http://192.168.1.100:4873/level-codec
npm http request GET http://192.168.1.100:4873/deferred-leveldown
npm http request GET http://192.168.1.100:4873/prr
npm http request GET http://192.168.1.100:4873/level-iterator-stream
npm http request GET http://192.168.1.100:4873/semver
npm http 200 http://192.168.1.100:4873/prr
npm http 200 http://192.168.1.100:4873/level-codec
npm http 200 http://192.168.1.100:4873/level-iterator-stream
npm http 200 http://192.168.1.100:4873/deferred-leveldown
npm http 200 http://192.168.1.100:4873/level-errors
npm http 200 http://192.168.1.100:4873/semver
npm http request GET http://192.168.1.100:4873/errno
npm http 200 http://192.168.1.100:4873/errno
npm http request GET http://192.168.1.100:4873/humble-localstorage
npm http 200 http://192.168.1.100:4873/humble-localstorage
npm http request GET http://192.168.1.100:4873/has-localstorage
npm http request GET http://192.168.1.100:4873/localstorage-memory
npm http 200 http://192.168.1.100:4873/localstorage-memory
npm http 200 http://192.168.1.100:4873/has-localstorage
npm http request GET http://192.168.1.100:4873/ltgt
npm http request GET http://192.168.1.100:4873/functional-red-black-tree
npm http fetch GET http://192.168.1.100:4873/abstract-leveldown/-/abstract-leveldown-2.6.1.tgz
npm http fetch 200 http://192.168.1.100:4873/abstract-leveldown/-/abstract-leveldown-2.6.1.tgz
npm http 200 http://192.168.1.100:4873/ltgt
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
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/aws4
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/is-typedarray
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/qs
npm WARN deprecated tough-cookie@2.2.2: ReDoS vulnerability parsing Set-Cookie https://nodesecurity.io/advisories/130
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/process-nextick-args
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
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/ansi-styles
npm http 304 http://192.168.1.100:4873/supports-color
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-function
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-object-property
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
npm http 304 http://192.168.1.100:4873/verror
npm http 304 http://192.168.1.100:4873/json-schema
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/dashdash
npm http request GET http://192.168.1.100:4873/getpass
npm http 304 http://192.168.1.100:4873/dashdash
npm http 304 http://192.168.1.100:4873/getpass
npm http 304 http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/pull-stream
npm http 304 http://192.168.1.100:4873/readable-stream
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
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/is-array
npm http request GET http://192.168.1.100:4873/pouchdb-extend
npm http request GET http://192.168.1.100:4873/pouchdb-upsert
npm http 200 http://192.168.1.100:4873/is-array
npm http 200 http://192.168.1.100:4873/pouchdb-upsert
npm http 200 http://192.168.1.100:4873/spark-md5
npm http fetch GET http://192.168.1.100:4873/spark-md5/-/spark-md5-0.0.5.tgz
npm http fetch 200 http://192.168.1.100:4873/spark-md5/-/spark-md5-0.0.5.tgz
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
npm http request GET http://192.168.1.100:4873/get-folder-size
npm http 200 http://192.168.1.100:4873/get-folder-size
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/minimist
npm http 304 http://192.168.1.100:4873/minimist
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/fast-future
npm http request GET http://192.168.1.100:4873/bindings
npm http 304 http://192.168.1.100:4873/abstract-leveldown
npm http 200 http://192.168.1.100:4873/fast-future
npm http 200 http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/varint
npm http 304 http://192.168.1.100:4873/duplexify
npm http 304 http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/stream-shift
npm http 304 http://192.168.1.100:4873/stream-shift
npm http 304 http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http 304 http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/propagate
npm http request GET http://192.168.1.100:4873/chai
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/deep-equal
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/lodash
npm WARN deprecated lodash@2.4.1: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
npm http 304 http://192.168.1.100:4873/debug
npm http 200 http://192.168.1.100:4873/deep-equal
npm http 200 http://192.168.1.100:4873/propagate
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
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 304 http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/jsonschema
npm http 304 http://192.168.1.100:4873/jsonschema
npm http request GET http://192.168.1.100:4873/util
npm http request GET http://192.168.1.100:4873/formatio
npm http request GET http://192.168.1.100:4873/lolex
npm http request GET http://192.168.1.100:4873/samsam
npm http 200 http://192.168.1.100:4873/util
npm http 200 http://192.168.1.100:4873/formatio
npm http 200 http://192.168.1.100:4873/samsam
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
npm http 304 http://192.168.1.100:4873/engine.io-client
npm http 304 http://192.168.1.100:4873/component-bind
npm http 304 http://192.168.1.100:4873/object-component
npm http 304 http://192.168.1.100:4873/socket.io-parser
npm http 304 http://192.168.1.100:4873/has-binary
npm http 304 http://192.168.1.100:4873/indexof
npm http 304 http://192.168.1.100:4873/component-emitter
npm http 304 http://192.168.1.100:4873/parseuri
npm http 304 http://192.168.1.100:4873/backo2
npm http 304 http://192.168.1.100:4873/to-array
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/ws
npm http request GET http://192.168.1.100:4873/xmlhttprequest-ssl
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/parseqs
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/yeast
npm http 304 http://192.168.1.100:4873/engine.io-parser
npm http 304 http://192.168.1.100:4873/xmlhttprequest-ssl
npm http 304 http://192.168.1.100:4873/parsejson
npm http 304 http://192.168.1.100:4873/ws
npm http 304 http://192.168.1.100:4873/has-cors
npm http 304 http://192.168.1.100:4873/parseqs
npm http 304 http://192.168.1.100:4873/yeast
npm http 304 http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/utf8
npm http 304 http://192.168.1.100:4873/arraybuffer.slice
npm http 304 http://192.168.1.100:4873/base64-arraybuffer
npm http 304 http://192.168.1.100:4873/utf8
npm http 304 http://192.168.1.100:4873/after
npm http 304 http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/better-assert
npm http 304 http://192.168.1.100:4873/better-assert
npm http request GET http://192.168.1.100:4873/callsite
npm http 304 http://192.168.1.100:4873/callsite
npm http request GET http://192.168.1.100:4873/options
npm http request GET http://192.168.1.100:4873/ultron
npm http 304 http://192.168.1.100:4873/options
npm http 304 http://192.168.1.100:4873/ultron
npm http request GET http://192.168.1.100:4873/benchmark
npm http request GET http://192.168.1.100:4873/json3
npm http 304 http://192.168.1.100:4873/json3
npm http 304 http://192.168.1.100:4873/benchmark
npm http request GET http://192.168.1.100:4873/superagent
npm http 200 http://192.168.1.100:4873/superagent
npm http request GET http://192.168.1.100:4873/formidable
npm http request GET http://192.168.1.100:4873/cookiejar
npm http request GET http://192.168.1.100:4873/reduce-component
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/form-data
npm http 200 http://192.168.1.100:4873/cookiejar
npm http 304 http://192.168.1.100:4873/methods
npm http 200 http://192.168.1.100:4873/reduce-component
npm http 304 http://192.168.1.100:4873/form-data
npm http 200 http://192.168.1.100:4873/formidable
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
npm http request GET http://192.168.1.100:4873/object-inspect
npm http request GET http://192.168.1.100:4873/resumer
npm http 304 http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/defined
npm http 200 http://192.168.1.100:4873/object-inspect
npm http 200 http://192.168.1.100:4873/resumer
npm http request GET http://192.168.1.100:4873/os-tmpdir
npm http 200 http://192.168.1.100:4873/os-tmpdir
npm http fetch GET http://192.168.1.100:4873/os-tmpdir/-/os-tmpdir-1.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/os-tmpdir/-/os-tmpdir-1.0.2.tgz
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
    at process._tickCallback (node.js:917:13)
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
    at process._tickCallback (node.js:917:13)

npm ERR! Darwin 15.6.0
npm ERR! argv "/usr/local/bin/jx" "/Users/thali/.jx/npm/bin/npm-cli.js" "--loglevel" "http" "--color" "true" "run" "test-coordinated"
npm ERR! node v0.10.40
npm ERR! npm  v3.3.12
npm ERR! code ELIFECYCLE
npm ERR! thali-cordova-plugin-jxcore@1.0.0 test-coordinated: `jx runCoordinatedTests.js`
npm ERR! Exit status 1
npm ERR! 
npm ERR! Failed at the thali-cordova-plugin-jxcore@1.0.0 test-coordinated script 'jx runCoordinatedTests.js'.
npm ERR! Make sure you have the latest version of node.js and npm installed.
npm ERR! If you do, this is most likely a problem with the thali-cordova-plugin-jxcore package,
npm ERR! not with npm itself.
npm ERR! Tell the author that this fails on your system:
npm ERR!     jx runCoordinatedTests.js
npm ERR! You can get their info via:
npm ERR!     npm owner ls thali-cordova-plugin-jxcore
npm ERR! There is likely additional logging output above.

npm ERR! Please include the following file with any support request:
npm ERR!     /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/npm-debug.log
bash: shell_session_update: command not found

```

Error: Command failed: npm WARN thali-test-server@0.0.1 No repository field.
npm WARN thali-test-server@0.0.1 No license field.
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/forever-agent
npm http request GET http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/javascript-state-machine
npm http request GET http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/bluebird
npm http 200 http://192.168.1.100:4873/ip
npm http 304 http://192.168.1.100:4873/express
npm http 200 http://192.168.1.100:4873/forever-agent
npm http 304 http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/body-parser
npm http 200 http://192.168.1.100:4873/long
npm http 200 http://192.168.1.100:4873/lie
npm http 200 http://192.168.1.100:4873/multiplex
npm http 200 http://192.168.1.100:4873/javascript-state-machine
npm http 200 http://192.168.1.100:4873/uuid
npm http 200 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/raw-body
npm http request GET http://192.168.1.100:4873/type-is
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/http-errors
npm http 200 http://192.168.1.100:4873/bytes
npm http 304 http://192.168.1.100:4873/on-finished
npm http 200 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/type-is
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
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/serve-static
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/send
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
npm http request GET http://192.168.1.100:4873/immediate
npm http 200 http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/xtend
npm http 200 http://192.168.1.100:4873/xtend
npm http 200 http://192.168.1.100:4873/duplexify
npm http fetch GET http://192.168.1.100:4873/duplexify/-/duplexify-3.4.6.tgz
npm http 200 http://192.168.1.100:4873/readable-stream
npm http fetch 200 http://192.168.1.100:4873/duplexify/-/duplexify-3.4.6.tgz
npm http 200 http://192.168.1.100:4873/varint
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
npm http request GET http://192.168.1.100:4873/string_decoder
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 200 http://192.168.1.100:4873/process-nextick-args
npm http 304 http://192.168.1.100:4873/isarray
npm http 200 http://192.168.1.100:4873/buffer-shims
npm http 200 http://192.168.1.100:4873/string_decoder
npm http 200 http://192.168.1.100:4873/core-util-is
npm http 200 http://192.168.1.100:4873/util-deprecate
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/har-validator
npm http 200 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 200 http://192.168.1.100:4873/caseless
npm http 200 http://192.168.1.100:4873/form-data
npm http 200 http://192.168.1.100:4873/bl
npm http 200 http://192.168.1.100:4873/oauth-sign
npm http 200 http://192.168.1.100:4873/tunnel-agent
npm http 200 http://192.168.1.100:4873/json-stringify-safe
npm http 200 http://192.168.1.100:4873/http-signature
npm http 200 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/hawk
npm http 200 http://192.168.1.100:4873/combined-stream
npm http 200 http://192.168.1.100:4873/aws-sign2
npm http 200 http://192.168.1.100:4873/stringstream
npm http 200 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 200 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http fetch GET http://192.168.1.100:4873/async/-/async-2.1.2.tgz
npm http fetch 200 http://192.168.1.100:4873/async/-/async-2.1.2.tgz
npm http request GET http://192.168.1.100:4873/lodash
npm http 200 http://192.168.1.100:4873/lodash
npm http fetch GET http://192.168.1.100:4873/lodash/-/lodash-4.16.4.tgz
npm http fetch 200 http://192.168.1.100:4873/lodash/-/lodash-4.16.4.tgz
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http 200 http://192.168.1.100:4873/is-my-json-valid
npm http 200 http://192.168.1.100:4873/chalk
npm http 200 http://192.168.1.100:4873/commander
npm http fetch GET http://192.168.1.100:4873/is-my-json-valid/-/is-my-json-valid-2.15.0.tgz
npm http fetch 200 http://192.168.1.100:4873/is-my-json-valid/-/is-my-json-valid-2.15.0.tgz
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 200 http://192.168.1.100:4873/has-ansi
npm http 200 http://192.168.1.100:4873/ansi-styles
npm http 200 http://192.168.1.100:4873/supports-color
npm http 200 http://192.168.1.100:4873/escape-string-regexp
npm http 200 http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 200 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http 200 http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 200 http://192.168.1.100:4873/generate-object-property
npm http 200 http://192.168.1.100:4873/jsonpointer
npm http 200 http://192.168.1.100:4873/generate-function
npm http fetch GET http://192.168.1.100:4873/jsonpointer/-/jsonpointer-4.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/jsonpointer/-/jsonpointer-4.0.0.tgz
npm http request GET http://192.168.1.100:4873/is-property
npm http 200 http://192.168.1.100:4873/is-property
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
npm http 200 http://192.168.1.100:4873/asn1
npm http 200 http://192.168.1.100:4873/assert-plus
npm http 200 http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/jsonschema
npm http request GET http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/jsonschema
npm http fetch GET http://192.168.1.100:4873/jsonschema/-/jsonschema-1.1.0.tgz
npm http fetch 200 http://192.168.1.100:4873/jsonschema/-/jsonschema-1.1.0.tgz
npm http request GET http://192.168.1.100:4873/colors
npm http request GET http://192.168.1.100:4873/cycle
npm http request GET http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/pkginfo
npm http request GET http://192.168.1.100:4873/stack-trace
npm http 304 http://192.168.1.100:4873/cycle
npm http 304 http://192.168.1.100:4873/eyes
npm http 304 http://192.168.1.100:4873/colors
npm http 304 http://192.168.1.100:4873/pkginfo
npm http 304 http://192.168.1.100:4873/stack-trace
npm http request GET http://192.168.1.100:4873/jsdoc
npm http 200 http://192.168.1.100:4873/jsdoc
npm http request GET http://192.168.1.100:4873/js2xmlparser
npm http request GET http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/catharsis
npm http request GET http://192.168.1.100:4873/marked
npm http request GET http://192.168.1.100:4873/requizzle
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/underscore
npm http request GET http://192.168.1.100:4873/wrench
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 200 http://192.168.1.100:4873/catharsis
npm http 200 http://192.168.1.100:4873/esprima
npm http 200 http://192.168.1.100:4873/js2xmlparser
npm http 200 http://192.168.1.100:4873/marked
npm http 200 http://192.168.1.100:4873/requizzle
npm http 200 http://192.168.1.100:4873/strip-json-comments
npm http 200 http://192.168.1.100:4873/underscore
npm http 200 http://192.168.1.100:4873/wrench
npm WARN deprecated wrench@1.5.9: wrench.js is deprecated! You should check out fs-extra (https://github.com/jprichardson/node-fs-extra) for any operations you were using wrench for. Thanks for all the usage over the years.
npm http fetch 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http request GET http://192.168.1.100:4873/underscore-contrib
npm http 200 http://192.168.1.100:4873/underscore-contrib
npm WARN prefer global marked@0.3.6 should be installed with -g
npm WARN install@0.0.1 No repository field.
npm http request GET http://192.168.1.100:4873/uuid-validate
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/child-process-promise
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/bn.js
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/forever-agent
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/express-pouchdb
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/leveldown-mobile
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/pouchdb-size
npm http request GET http://192.168.1.100:4873/pouchdb
npm http request GET http://192.168.1.100:4873/nock
npm http request GET http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/proxyquire
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/request-promise
npm http request GET http://192.168.1.100:4873/sinon
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/supertest
npm http request GET http://192.168.1.100:4873/tape-catch
npm http request GET http://192.168.1.100:4873/supertest-as-promised
npm http request GET http://192.168.1.100:4873/tape
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/tmp
npm http request GET http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/child-process-promise
npm http 200 http://192.168.1.100:4873/uuid-validate
npm http fetch GET http://192.168.1.100:4873/uuid-validate/-/uuid-validate-0.0.2.tgz
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/js-extend
npm http 200 http://192.168.1.100:4873/bn.js
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/forever-agent
npm http 304 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/multiplex
npm http 200 http://192.168.1.100:4873/express-pouchdb
npm http 304 http://192.168.1.100:4873/node-uuid
npm http fetch GET http://192.168.1.100:4873/express-pouchdb/-/express-pouchdb-1.0.5-thali.tgz
npm http 200 http://192.168.1.100:4873/pouchdb-size
npm http 304 http://192.168.1.100:4873/randomstring
npm http 200 http://192.168.1.100:4873/proxyquire
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/leveldown-mobile
npm http 304 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/pouchdb
npm http 200 http://192.168.1.100:4873/nock
npm http 304 http://192.168.1.100:4873/socket.io-client
npm http 200 http://192.168.1.100:4873/supertest
npm http 200 http://192.168.1.100:4873/request-promise
npm http 304 http://192.168.1.100:4873/uuid
npm http 200 http://192.168.1.100:4873/tape-catch
npm http 200 http://192.168.1.100:4873/supertest-as-promised
npm http fetch 200 http://192.168.1.100:4873/uuid-validate/-/uuid-validate-0.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/express-pouchdb/-/express-pouchdb-1.0.5-thali.tgz
npm http 200 http://192.168.1.100:4873/tmp
npm http 200 http://192.168.1.100:4873/sinon
npm http 304 http://192.168.1.100:4873/object-assign
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
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/iconv-lite
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
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/send
npm http 304 http://192.168.1.100:4873/serve-static
npm http 304 http://192.168.1.100:4873/range-parser
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
npm http request GET http://192.168.1.100:4873/compression
npm http request GET http://192.168.1.100:4873/cookie-parser
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/pouchdb-all-dbs
npm http request GET http://192.168.1.100:4873/multiparty
npm http request GET http://192.168.1.100:4873/basic-auth
npm http request GET http://192.168.1.100:4873/pouchdb-auth
npm http request GET http://192.168.1.100:4873/pouchdb-list
npm http request GET http://192.168.1.100:4873/header-case-normalizer
npm http request GET http://192.168.1.100:4873/pouchdb-rewrite
npm http request GET http://192.168.1.100:4873/pouchdb-replicator
npm http request GET http://192.168.1.100:4873/pouchdb-find
npm http request GET http://192.168.1.100:4873/pouchdb-security
npm http request GET http://192.168.1.100:4873/pouchdb-wrappers
npm http request GET http://192.168.1.100:4873/pouchdb-show
npm http request GET http://192.168.1.100:4873/pouchdb-vhost
npm http request GET http://192.168.1.100:4873/pouchdb-validation
npm http request GET http://192.168.1.100:4873/pouchdb-update
npm http 304 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/compression
npm http 200 http://192.168.1.100:4873/cookie-parser
npm http 200 http://192.168.1.100:4873/multiparty
npm http 200 http://192.168.1.100:4873/basic-auth
npm http 200 http://192.168.1.100:4873/pouchdb-all-dbs
npm http 200 http://192.168.1.100:4873/pouchdb-list
npm http 200 http://192.168.1.100:4873/pouchdb-rewrite
npm http 200 http://192.168.1.100:4873/pouchdb-replicator
npm http 200 http://192.168.1.100:4873/pouchdb-find
npm http 200 http://192.168.1.100:4873/pouchdb-wrappers
npm http 200 http://192.168.1.100:4873/header-case-normalizer
npm http 200 http://192.168.1.100:4873/pouchdb-auth
npm http 200 http://192.168.1.100:4873/pouchdb-security
npm http 200 http://192.168.1.100:4873/pouchdb-update
npm http 200 http://192.168.1.100:4873/pouchdb-vhost
npm http 200 http://192.168.1.100:4873/pouchdb-show
npm http 200 http://192.168.1.100:4873/pouchdb-validation
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
npm http request GET http://192.168.1.100:4873/tiny-queue
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/es3ify
npm http 200 http://192.168.1.100:4873/pouchdb-promise
npm http 200 http://192.168.1.100:4873/tiny-queue
npm http 200 http://192.168.1.100:4873/argsarray
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
npm http request GET http://192.168.1.100:4873/pouchdb-req-http-query
npm http request GET http://192.168.1.100:4873/pouchdb-plugin-error
npm http request GET http://192.168.1.100:4873/promise-nodify
npm http request GET http://192.168.1.100:4873/pouchdb-system-db
npm http request GET http://192.168.1.100:4873/secure-random
npm http 200 http://192.168.1.100:4873/base64url
npm http 200 http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http 200 http://192.168.1.100:4873/couchdb-calculate-session-id
npm http fetch GET http://192.168.1.100:4873/couchdb-calculate-session-id/-/couchdb-calculate-session-id-1.1.1.tgz
npm http 200 http://192.168.1.100:4873/crypto-lite
npm http 200 http://192.168.1.100:4873/pouchdb-req-http-query
npm http fetch 200 http://192.168.1.100:4873/couchdb-calculate-session-id/-/couchdb-calculate-session-id-1.1.1.tgz
npm http 200 http://192.168.1.100:4873/pouchdb-plugin-error
npm http 200 http://192.168.1.100:4873/pouchdb-system-db
npm http 200 http://192.168.1.100:4873/promise-nodify
npm http 200 http://192.168.1.100:4873/secure-random
npm http request GET http://192.168.1.100:4873/meow
npm http request GET http://192.168.1.100:4873/concat-stream
npm http 200 http://192.168.1.100:4873/concat-stream
npm http 200 http://192.168.1.100:4873/meow
npm http request GET http://192.168.1.100:4873/typedarray
npm http 200 http://192.168.1.100:4873/typedarray
npm http request GET http://192.168.1.100:4873/camelcase-keys
npm http request GET http://192.168.1.100:4873/indent-string
npm http 200 http://192.168.1.100:4873/camelcase-keys
npm http 200 http://192.168.1.100:4873/indent-string
npm http request GET http://192.168.1.100:4873/camelcase
npm http request GET http://192.168.1.100:4873/map-obj
npm http 200 http://192.168.1.100:4873/map-obj
npm http 200 http://192.168.1.100:4873/camelcase
npm http request GET http://192.168.1.100:4873/repeating
npm http request GET http://192.168.1.100:4873/get-stdin
npm http 200 http://192.168.1.100:4873/repeating
npm http 200 http://192.168.1.100:4873/get-stdin
npm http request GET http://192.168.1.100:4873/is-finite
npm http 200 http://192.168.1.100:4873/is-finite
npm http fetch GET http://192.168.1.100:4873/is-finite/-/is-finite-1.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/is-finite/-/is-finite-1.0.2.tgz
npm http request GET http://192.168.1.100:4873/number-is-nan
npm http 200 http://192.168.1.100:4873/number-is-nan
npm http fetch GET http://192.168.1.100:4873/number-is-nan/-/number-is-nan-1.0.1.tgz
npm http fetch 200 http://192.168.1.100:4873/number-is-nan/-/number-is-nan-1.0.1.tgz
npm http request GET http://192.168.1.100:4873/aproba
npm http fetch GET http://192.168.1.100:4873/base64url/-/base64url-2.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/base64url/-/base64url-2.0.0.tgz
npm http 200 http://192.168.1.100:4873/aproba
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/es6-promise-pool
npm http request GET http://192.168.1.100:4873/fruitdown
npm http request GET http://192.168.1.100:4873/level-write-stream
npm http request GET http://192.168.1.100:4873/localstorage-down
npm http request GET http://192.168.1.100:4873/scope-eval
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/pouchdb-collate
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/memdown
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/vuvuzela
npm http 200 http://192.168.1.100:4873/double-ended-queue
npm http 200 http://192.168.1.100:4873/level-write-stream
npm http 200 http://192.168.1.100:4873/fruitdown
npm http 200 http://192.168.1.100:4873/localstorage-down
npm http 200 http://192.168.1.100:4873/es6-promise-pool
npm http 200 http://192.168.1.100:4873/scope-eval
npm http 200 http://192.168.1.100:4873/spark-md5
npm http 304 http://192.168.1.100:4873/through2
npm http 304 http://192.168.1.100:4873/js-extend
npm http 200 http://192.168.1.100:4873/pouchdb-collate
npm http 200 http://192.168.1.100:4873/pouchdb-collections
npm http 200 http://192.168.1.100:4873/memdown
npm http 304 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/vuvuzela
npm http 200 http://192.168.1.100:4873/sublevel-pouchdb
npm http 200 http://192.168.1.100:4873/levelup
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
npm http request GET http://192.168.1.100:4873/level-errors
npm http request GET http://192.168.1.100:4873/level-codec
npm http request GET http://192.168.1.100:4873/deferred-leveldown
npm http request GET http://192.168.1.100:4873/prr
npm http request GET http://192.168.1.100:4873/level-iterator-stream
npm http request GET http://192.168.1.100:4873/semver
npm http 200 http://192.168.1.100:4873/prr
npm http 200 http://192.168.1.100:4873/level-codec
npm http 200 http://192.168.1.100:4873/level-iterator-stream
npm http 200 http://192.168.1.100:4873/deferred-leveldown
npm http 200 http://192.168.1.100:4873/level-errors
npm http 200 http://192.168.1.100:4873/semver
npm http request GET http://192.168.1.100:4873/errno
npm http 200 http://192.168.1.100:4873/errno
npm http request GET http://192.168.1.100:4873/humble-localstorage
npm http 200 http://192.168.1.100:4873/humble-localstorage
npm http request GET http://192.168.1.100:4873/has-localstorage
npm http request GET http://192.168.1.100:4873/localstorage-memory
npm http 200 http://192.168.1.100:4873/localstorage-memory
npm http 200 http://192.168.1.100:4873/has-localstorage
npm http request GET http://192.168.1.100:4873/ltgt
npm http request GET http://192.168.1.100:4873/functional-red-black-tree
npm http fetch GET http://192.168.1.100:4873/abstract-leveldown/-/abstract-leveldown-2.6.1.tgz
npm http fetch 200 http://192.168.1.100:4873/abstract-leveldown/-/abstract-leveldown-2.6.1.tgz
npm http 200 http://192.168.1.100:4873/ltgt
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
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/aws4
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/is-typedarray
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/qs
npm WARN deprecated tough-cookie@2.2.2: ReDoS vulnerability parsing Set-Cookie https://nodesecurity.io/advisories/130
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/process-nextick-args
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
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/ansi-styles
npm http 304 http://192.168.1.100:4873/supports-color
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-function
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-object-property
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
npm http 304 http://192.168.1.100:4873/verror
npm http 304 http://192.168.1.100:4873/json-schema
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/dashdash
npm http request GET http://192.168.1.100:4873/getpass
npm http 304 http://192.168.1.100:4873/dashdash
npm http 304 http://192.168.1.100:4873/getpass
npm http 304 http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/pull-stream
npm http 304 http://192.168.1.100:4873/readable-stream
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
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/is-array
npm http request GET http://192.168.1.100:4873/pouchdb-extend
npm http request GET http://192.168.1.100:4873/pouchdb-upsert
npm http 200 http://192.168.1.100:4873/is-array
npm http 200 http://192.168.1.100:4873/pouchdb-upsert
npm http 200 http://192.168.1.100:4873/spark-md5
npm http fetch GET http://192.168.1.100:4873/spark-md5/-/spark-md5-0.0.5.tgz
npm http fetch 200 http://192.168.1.100:4873/spark-md5/-/spark-md5-0.0.5.tgz
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
npm http request GET http://192.168.1.100:4873/get-folder-size
npm http 200 http://192.168.1.100:4873/get-folder-size
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/minimist
npm http 304 http://192.168.1.100:4873/minimist
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/fast-future
npm http request GET http://192.168.1.100:4873/bindings
npm http 304 http://192.168.1.100:4873/abstract-leveldown
npm http 200 http://192.168.1.100:4873/fast-future
npm http 200 http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/varint
npm http 304 http://192.168.1.100:4873/duplexify
npm http 304 http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/stream-shift
npm http 304 http://192.168.1.100:4873/stream-shift
npm http 304 http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http 304 http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/propagate
npm http request GET http://192.168.1.100:4873/chai
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/deep-equal
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/lodash
npm WARN deprecated lodash@2.4.1: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
npm http 304 http://192.168.1.100:4873/debug
npm http 200 http://192.168.1.100:4873/deep-equal
npm http 200 http://192.168.1.100:4873/propagate
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
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 304 http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/jsonschema
npm http 304 http://192.168.1.100:4873/jsonschema
npm http request GET http://192.168.1.100:4873/util
npm http request GET http://192.168.1.100:4873/formatio
npm http request GET http://192.168.1.100:4873/lolex
npm http request GET http://192.168.1.100:4873/samsam
npm http 200 http://192.168.1.100:4873/util
npm http 200 http://192.168.1.100:4873/formatio
npm http 200 http://192.168.1.100:4873/samsam
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
npm http 304 http://192.168.1.100:4873/engine.io-client
npm http 304 http://192.168.1.100:4873/component-bind
npm http 304 http://192.168.1.100:4873/object-component
npm http 304 http://192.168.1.100:4873/socket.io-parser
npm http 304 http://192.168.1.100:4873/has-binary
npm http 304 http://192.168.1.100:4873/indexof
npm http 304 http://192.168.1.100:4873/component-emitter
npm http 304 http://192.168.1.100:4873/parseuri
npm http 304 http://192.168.1.100:4873/backo2
npm http 304 http://192.168.1.100:4873/to-array
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/ws
npm http request GET http://192.168.1.100:4873/xmlhttprequest-ssl
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/parseqs
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/yeast
npm http 304 http://192.168.1.100:4873/engine.io-parser
npm http 304 http://192.168.1.100:4873/xmlhttprequest-ssl
npm http 304 http://192.168.1.100:4873/parsejson
npm http 304 http://192.168.1.100:4873/ws
npm http 304 http://192.168.1.100:4873/has-cors
npm http 304 http://192.168.1.100:4873/parseqs
npm http 304 http://192.168.1.100:4873/yeast
npm http 304 http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/utf8
npm http 304 http://192.168.1.100:4873/arraybuffer.slice
npm http 304 http://192.168.1.100:4873/base64-arraybuffer
npm http 304 http://192.168.1.100:4873/utf8
npm http 304 http://192.168.1.100:4873/after
npm http 304 http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/better-assert
npm http 304 http://192.168.1.100:4873/better-assert
npm http request GET http://192.168.1.100:4873/callsite
npm http 304 http://192.168.1.100:4873/callsite
npm http request GET http://192.168.1.100:4873/options
npm http request GET http://192.168.1.100:4873/ultron
npm http 304 http://192.168.1.100:4873/options
npm http 304 http://192.168.1.100:4873/ultron
npm http request GET http://192.168.1.100:4873/benchmark
npm http request GET http://192.168.1.100:4873/json3
npm http 304 http://192.168.1.100:4873/json3
npm http 304 http://192.168.1.100:4873/benchmark
npm http request GET http://192.168.1.100:4873/superagent
npm http 200 http://192.168.1.100:4873/superagent
npm http request GET http://192.168.1.100:4873/formidable
npm http request GET http://192.168.1.100:4873/cookiejar
npm http request GET http://192.168.1.100:4873/reduce-component
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/form-data
npm http 200 http://192.168.1.100:4873/cookiejar
npm http 304 http://192.168.1.100:4873/methods
npm http 200 http://192.168.1.100:4873/reduce-component
npm http 304 http://192.168.1.100:4873/form-data
npm http 200 http://192.168.1.100:4873/formidable
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
npm http request GET http://192.168.1.100:4873/object-inspect
npm http request GET http://192.168.1.100:4873/resumer
npm http 304 http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/defined
npm http 200 http://192.168.1.100:4873/object-inspect
npm http 200 http://192.168.1.100:4873/resumer
npm http request GET http://192.168.1.100:4873/os-tmpdir
npm http 200 http://192.168.1.100:4873/os-tmpdir
npm http fetch GET http://192.168.1.100:4873/os-tmpdir/-/os-tmpdir-1.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/os-tmpdir/-/os-tmpdir-1.0.2.tgz
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
    at process._tickCallback (node.js:917:13)
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
    at process._tickCallback (node.js:917:13)

npm ERR! Darwin 15.6.0
npm ERR! argv "/usr/local/bin/jx" "/Users/thali/.jx/npm/bin/npm-cli.js" "--loglevel" "http" "--color" "true" "run" "test-coordinated"
npm ERR! node v0.10.40
npm ERR! npm  v3.3.12
npm ERR! code ELIFECYCLE
npm ERR! thali-cordova-plugin-jxcore@1.0.0 test-coordinated: `jx runCoordinatedTests.js`
npm ERR! Exit status 1
npm ERR! 
npm ERR! Failed at the thali-cordova-plugin-jxcore@1.0.0 test-coordinated script 'jx runCoordinatedTests.js'.
npm ERR! Make sure you have the latest version of node.js and npm installed.
npm ERR! If you do, this is most likely a problem with the thali-cordova-plugin-jxcore package,
npm ERR! not with npm itself.
npm ERR! Tell the author that this fails on your system:
npm ERR!     jx runCoordinatedTests.js
npm ERR! You can get their info via:
npm ERR!     npm owner ls thali-cordova-plugin-jxcore
npm ERR! There is likely additional logging output above.

npm ERR! Please include the following file with any support request:
npm ERR!     /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/npm-debug.log
bash: shell_session_update: command not found
