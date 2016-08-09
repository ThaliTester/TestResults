#### Test (Fail) 80473891 Build Logs


```


```

```
Already up-to-date.

From https://github.com/thaliproject/Thali_CordovaPlugin
   c1794c3..03d5d83  vNext_aaladev_507 -> origin/vNext_aaladev_507

```

```
Your branch is up-to-date with 'origin/master'.
Branch vNext_yarong_417_1 set up to track remote branch vNext_yarong_417_1 from origin.
Already up-to-date.

Already on 'master'
Switched to a new branch 'vNext_yarong_417_1'
Note: checking out '03d5d83'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at 03d5d83... Remove Cordova update during build

```

```
Cordova version:
6.1.0

> bufferutil@1.1.0 install /Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/bufferutil
> "/usr/local/bin/jx" /Users/thali/.jx/npm/node_modules/node-gyp/bin/node-gyp.js rebuild

Target arch x64
  CXX(target) Release/obj.target/bufferutil/src/bufferutil.o
  SOLINK_MODULE(target) Release/bufferutil.node

> utf-8-validate@1.1.0 install /Users/thali/Github/Thali_CordovaPlugin/test/TestServer/node_modules/utf-8-validate
> "/usr/local/bin/jx" /Users/thali/.jx/npm/node_modules/node-gyp/bin/node-gyp.js rebuild

Target arch x64
  CXX(target) Release/obj.target/validation/src/validation.o
  SOLINK_MODULE(target) Release/validation.node
thali-test-server@0.0.1 /Users/thali/Github/Thali_CordovaPlugin/test/TestServer
├─┬ express@4.13.3 
│ ├─┬ accepts@1.2.13 
│ │ ├─┬ mime-types@2.1.11 
│ │ │ └── mime-db@1.23.0 
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
│ │ │ └── inherits@2.0.1 
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
│ ├── bluebird@2.10.2 
│ └─┬ fs-extra@0.21.0 
│   ├── graceful-fs@4.1.5 
│   ├── jsonfile@2.3.1 
│   └─┬ rimraf@2.5.4 
│     └─┬ glob@7.0.5 
│       ├── fs.realpath@1.0.0 
│       ├─┬ inflight@1.0.5 
│       │ └── wrappy@1.0.2 
│       ├─┬ minimatch@3.0.3 
│       │ └─┬ brace-expansion@1.1.6 
│       │   ├── balanced-match@0.4.2 
│       │   └── concat-map@0.0.1 
│       ├── once@1.3.3 
│       └── path-is-absolute@1.0.0 
├─┬ lie@3.0.4 
│ ├─┬ es3ify@0.2.2 
│ │ ├── esprima@2.7.2 
│ │ └─┬ jstransform@11.0.3 
│ │   ├── base62@1.1.1 
│ │   ├─┬ commoner@0.10.4 
│ │   │ ├─┬ commander@2.9.0 
│ │   │ │ └── graceful-readlink@1.0.1 
│ │   │ ├─┬ detective@4.3.1 
│ │   │ │ └── defined@1.0.0 
│ │   │ ├── glob@5.0.15 
│ │   │ ├── iconv-lite@0.4.13 
│ │   │ ├─┬ mkdirp@0.5.1 
│ │   │ │ └── minimist@0.0.8 
│ │   │ └── q@1.4.1 
│ │   ├── esprima-fb@15001.1.0-dev-harmony-fb 
│ │   ├── object-assign@2.1.1 
│ │   └─┬ source-map@0.4.4 
│ │     └── amdefine@1.0.0 
│ ├── immediate@3.0.6 
│ ├─┬ inline-process-browser@1.0.0 
│ │ ├─┬ falafel@1.2.0 
│ │ │ ├── acorn@1.2.2 
│ │ │ ├── foreach@2.0.5 
│ │ │ └── object-keys@1.0.11 
│ │ └─┬ through2@0.6.5 
│ │   ├─┬ readable-stream@1.0.34 
│ │   │ ├── core-util-is@1.0.2 
│ │   │ └── string_decoder@0.10.31 
│ │   └── xtend@4.0.1 
│ └─┬ unreachable-branch-transform@0.3.0 
│   ├── esmangle-evaluator@1.0.1 
│   └─┬ recast@0.10.43 
│     ├── ast-types@0.8.15 
│     ├── esprima-fb@15001.1001.0-dev-harmony-fb 
│     ├── private@0.1.6 
│     └── source-map@0.5.6 
├── node-uuid@1.4.7 
├─┬ socket.io@1.3.6 
│ ├─┬ debug@2.1.0 
│ │ └── ms@0.6.2 
│ ├─┬ engine.io@1.5.2 
│ │ ├── base64id@0.1.0 
│ │ ├─┬ debug@1.0.3 
│ │ │ └── ms@0.6.2 
│ │ ├─┬ engine.io-parser@1.2.1 
│ │ │ ├── after@0.8.1 
│ │ │ ├── arraybuffer.slice@0.0.6 
│ │ │ ├── base64-arraybuffer@0.1.2 
│ │ │ ├── blob@0.0.2 
│ │ │ ├── has-binary@0.1.5 
│ │ │ └── utf8@2.0.0 
│ │ └─┬ ws@0.7.2 
│ │   ├─┬ bufferutil@1.1.0 
│ │   │ ├── bindings@1.2.1 
│ │   │ └── nan@1.8.4 
│ │   ├── options@0.0.6 
│ │   ├── ultron@1.0.2 
│ │   └── utf-8-validate@1.1.0 
│ ├─┬ has-binary-data@0.1.3 
│ │ └── isarray@0.0.1 
│ ├─┬ socket.io-adapter@0.3.1 
│ │ ├─┬ debug@1.0.2 
│ │ │ └── ms@0.6.2 
│ │ ├── object-keys@1.0.1 
│ │ └─┬ socket.io-parser@2.2.2 
│ │   └── debug@0.7.4 
│ └─┬ socket.io-parser@2.2.4 
│   ├── benchmark@1.0.0 
│   ├── debug@0.7.4 
│   └── json3@3.2.6 
├─┬ socket.io-client@1.3.6 
│ ├── backo2@1.0.2 
│ ├── component-bind@1.0.0 
│ ├── component-emitter@1.1.2 
│ ├── debug@0.7.4 
│ ├─┬ engine.io-client@1.5.2 
│ │ ├── component-inherit@0.0.3 
│ │ ├─┬ debug@1.0.4 
│ │ │ └── ms@0.6.2 
│ │ ├─┬ has-cors@1.0.3 
│ │ │ └── global@2.0.1 
│ │ ├── parsejson@0.0.1 
│ │ ├── parseqs@0.0.2 
│ │ ├── parseuri@0.0.4 
│ │ └── xmlhttprequest@1.5.0 
│ ├── has-binary@0.1.6 
│ ├── indexof@0.0.1 
│ ├── object-component@0.0.3 
│ ├─┬ parseuri@0.0.2 
│ │ └─┬ better-assert@1.0.2 
│ │   └── callsite@1.0.0 
│ └── to-array@0.1.3 
├─┬ tape@1.1.2 
│ ├── deep-equal@0.0.0 
│ ├── defined@0.0.0 
│ ├── jsonify@0.0.0 
│ └── through@2.3.8 
└─┬ winston@2.2.0 
  ├── async@1.0.0 
  ├── colors@1.0.3 
  ├── cycle@1.0.3 
  ├── eyes@0.1.8 
  ├── isstream@0.1.2 
  ├── pkginfo@0.3.1 
  └── stack-trace@0.0.9 


> thali@2.1.0 postinstall /Users/thali/Github/Thali_CordovaPlugin/thali
> jx installCordovaPlugin.js

We believe we are in a clone of the GitHub Repo so we will not install Cordova dependencies

> thali@2.1.0 prepublish /Users/thali/Github/Thali_CordovaPlugin/thali
> jx install/prePublishThaliCordovaPlugin.js

thali@2.1.0 /Users/thali/Github/Thali_CordovaPlugin/thali
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
├─┬ express-pouchdb@1.0.4 
│ ├── basic-auth@1.0.3 
│ ├── bluebird@3.3.4 
│ ├─┬ body-parser@1.15.0 
│ │ ├── bytes@2.2.0 
│ │ ├── depd@1.1.0 
│ │ ├── http-errors@1.4.0 
│ │ ├── iconv-lite@0.4.13 
│ │ └── qs@6.1.0 
│ ├─┬ compression@1.6.1 
│ │ ├─┬ accepts@1.3.3 
│ │ │ └── negotiator@0.6.1 
│ │ ├── bytes@2.2.0 
│ │ ├── compressible@2.0.8 
│ │ ├── on-headers@1.0.1 
│ │ └── vary@1.1.0 
│ ├─┬ cookie-parser@1.4.1 
│ │ └── cookie@0.2.3 
│ ├── extend@1.3.0 
│ ├── header-case-normalizer@1.0.3 
│ ├─┬ multiparty@3.3.2 
│ │ ├─┬ readable-stream@1.1.14 
│ │ │ └── isarray@0.0.1 
│ │ └── stream-counter@0.2.0 
│ ├── node-uuid@1.4.1 
│ ├─┬ pouchdb-all-dbs@1.0.1 
│ │ ├── argsarray@0.0.1 
│ │ ├─┬ es3ify@0.1.4 
│ │ │ ├── esprima-fb@3001.1.0-dev-harmony-fb 
│ │ │ └─┬ jstransform@3.0.0 
│ │ │   ├── base62@0.1.1 
│ │ │   └── source-map@0.1.31 
│ │ ├─┬ lie@2.9.1 
│ │ │ └── unreachable-branch-transform@0.2.3 
│ │ └── tiny-queue@0.2.1 
│ ├─┬ pouchdb-auth@2.1.0 
│ │ ├─┬ base64url@1.0.6 
│ │ │ ├─┬ concat-stream@1.4.10 
│ │ │ │ └── typedarray@0.0.6 
│ │ │ └─┬ meow@2.0.0 
│ │ │   ├─┬ camelcase-keys@1.0.0 
│ │ │   │ ├── camelcase@1.2.1 
│ │ │   │ └── map-obj@1.0.1 
│ │ │   ├─┬ indent-string@1.2.2 
│ │ │   │ ├── get-stdin@4.0.1 
│ │ │   │ └─┬ repeating@1.1.3 
│ │ │   │   └─┬ is-finite@1.0.1 
│ │ │   │     └── number-is-nan@1.0.0 
│ │ │   ├── minimist@1.2.0 
│ │ │   └── object-assign@1.0.0 
│ │ ├─┬ couchdb-calculate-session-id@1.1.0 
│ │ │ └── aproba@1.0.4 
│ │ ├── crypto-lite@0.1.0 
│ │ ├─┬ pouchdb@5.4.5 
│ │ │ ├── double-ended-queue@2.0.0-0 
│ │ │ ├── es6-promise-pool@2.4.2 
│ │ │ ├─┬ fruitdown@1.0.2 
│ │ │ │ ├─┬ abstract-leveldown@0.12.3 
│ │ │ │ │ └── xtend@3.0.0 
│ │ │ │ ├── d64@1.0.0 
│ │ │ │ └── tiny-queue@0.2.0 
│ │ │ ├── js-extend@0.0.1 
│ │ │ ├─┬ level-write-stream@1.0.0 
│ │ │ │ └─┬ end-stream@0.1.0 
│ │ │ │   └─┬ write-stream@0.4.3 
│ │ │ │     └── readable-stream@0.0.4 
│ │ │ ├─┬ levelup@1.3.2 
│ │ │ │ ├─┬ deferred-leveldown@1.2.1 
│ │ │ │ │ └── abstract-leveldown@2.4.1 
│ │ │ │ ├── level-codec@6.1.0 
│ │ │ │ ├── level-errors@1.0.4 
│ │ │ │ ├── level-iterator-stream@1.3.1 
│ │ │ │ ├── prr@1.0.1 
│ │ │ │ └── semver@5.1.1 
│ │ │ ├─┬ localstorage-down@0.6.6 
│ │ │ │ ├─┬ humble-localstorage@1.4.2 
│ │ │ │ │ ├── has-localstorage@1.0.1 
│ │ │ │ │ └── localstorage-memory@1.0.2 
│ │ │ │ └── tiny-queue@0.2.0 
│ │ │ ├─┬ memdown@1.1.2 
│ │ │ │ ├── abstract-leveldown@2.6.0 
│ │ │ │ ├── functional-red-black-tree@1.0.1 
│ │ │ │ └── ltgt@1.0.2 
│ │ │ ├── pouchdb-collections@1.0.1 
│ │ │ ├─┬ request@2.72.0 
│ │ │ │ ├── aws-sign2@0.6.0 
│ │ │ │ ├── aws4@1.4.1 
│ │ │ │ ├─┬ bl@1.1.2 
│ │ │ │ │ └─┬ readable-stream@2.0.6 
│ │ │ │ │   └── isarray@1.0.0 
│ │ │ │ ├── extend@3.0.0 
│ │ │ │ ├─┬ har-validator@2.0.6 
│ │ │ │ │ └─┬ pinkie-promise@2.0.1 
│ │ │ │ │   └── pinkie@2.0.4 
│ │ │ │ ├─┬ http-signature@1.1.1 
│ │ │ │ │ ├── assert-plus@0.2.0 
│ │ │ │ │ ├─┬ jsprim@1.3.0 
│ │ │ │ │ │ ├── extsprintf@1.0.2 
│ │ │ │ │ │ ├── json-schema@0.2.2 
│ │ │ │ │ │ └── verror@1.3.6 
│ │ │ │ │ └─┬ sshpk@1.9.2 
│ │ │ │ │   ├── asn1@0.2.3 
│ │ │ │ │   ├── assert-plus@1.0.0 
│ │ │ │ │   ├─┬ dashdash@1.14.0 
│ │ │ │ │   │ └── assert-plus@1.0.0 
│ │ │ │ │   └─┬ getpass@0.1.6 
│ │ │ │ │     └── assert-plus@1.0.0 
│ │ │ │ ├── is-typedarray@1.0.0 
│ │ │ │ └── qs@6.1.0 
│ │ │ ├── scope-eval@0.0.3 
│ │ │ ├── spark-md5@2.0.2 
│ │ │ ├─┬ sublevel-pouchdb@1.0.1 
│ │ │ │ ├─┬ errno@0.1.4 
│ │ │ │ │ └── prr@0.0.0 
│ │ │ │ ├── ltgt@2.1.2 
│ │ │ │ ├─┬ pull-stream@2.21.0 
│ │ │ │ │ └── pull-core@1.0.0 
│ │ │ │ └── readable-stream@1.0.33 
│ │ │ ├─┬ through2@2.0.1 
│ │ │ │ └─┬ readable-stream@2.0.6 
│ │ │ │   └── isarray@1.0.0 
│ │ │ └── vuvuzela@1.0.3 
│ │ ├─┬ pouchdb-bulkdocs-wrapper@1.0.2 
│ │ │ └─┬ pouchdb-promise@0.0.0 
│ │ │   ├── bluebird@1.2.4 
│ │ │   └── lie@2.7.7 
│ │ ├── pouchdb-plugin-error@1.0.1 
│ │ ├── pouchdb-promise@5.4.5 
│ │ ├─┬ pouchdb-req-http-query@1.0.3 
│ │ │ ├─┬ pouchdb-promise@0.0.0 
│ │ │ │ ├── bluebird@1.2.4 
│ │ │ │ └── lie@2.7.7 
│ │ │ └─┬ xmlhttprequest-cookie@0.9.4 
│ │ │   └── xmlhttprequest@1.8.0 
│ │ ├── pouchdb-system-db@1.0.4 
│ │ ├── promise-nodify@1.0.2 
│ │ └── secure-random@1.1.1 
│ ├─┬ pouchdb-find@0.1.0 
│ │ ├─┬ jshint@2.9.2 
│ │ │ ├─┬ cli@0.6.6 
│ │ │ │ └─┬ glob@3.2.11 
│ │ │ │   └─┬ minimatch@0.3.0 
│ │ │ │     ├── lru-cache@2.7.3 
│ │ │ │     └── sigmund@1.0.1 
│ │ │ ├─┬ console-browserify@1.1.0 
│ │ │ │ └── date-now@0.1.4 
│ │ │ ├── exit@0.1.2 
│ │ │ ├─┬ htmlparser2@3.8.3 
│ │ │ │ ├── domelementtype@1.3.0 
│ │ │ │ ├── domhandler@2.3.0 
│ │ │ │ ├─┬ domutils@1.5.1 
│ │ │ │ │ └─┬ dom-serializer@0.1.0 
│ │ │ │ │   ├── domelementtype@1.1.3 
│ │ │ │ │   └── entities@1.1.1 
│ │ │ │ └── entities@1.0.0 
│ │ │ ├── lodash@3.7.0 
│ │ │ ├─┬ minimatch@2.0.10 
│ │ │ │ └─┬ brace-expansion@1.1.6 
│ │ │ │   ├── balanced-match@0.4.2 
│ │ │ │   └── concat-map@0.0.1 
│ │ │ └── shelljs@0.3.0 
│ │ ├── lie@2.9.1 
│ │ ├─┬ pouchdb-abstract-mapreduce@0.2.2 
│ │ │ ├── lie@2.9.1 
│ │ │ └── spark-md5@0.0.5 
│ │ ├── pouchdb-collate@1.2.0 
│ │ ├── pouchdb-extend@0.1.2 
│ │ ├─┬ pouchdb-upsert@1.1.3 
│ │ │ └── lie@2.9.1 
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
│ ├─┬ pouchdb-size@1.2.2 
│ │ ├── bluebird@2.10.2 
│ │ └─┬ get-folder-size@0.1.1 
│ │   ├── async@0.9.2 
│ │   └── minimist@0.1.0 
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
│ ├── pouchdb-wrappers@1.3.6 
│ └─┬ raw-body@2.1.6 
│   └── bytes@2.3.0 
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
├─┬ lie@3.0.4 
│ ├─┬ es3ify@0.2.2 
│ │ ├── esprima@2.7.2 
│ │ ├─┬ jstransform@11.0.3 
│ │ │ ├── base62@1.1.1 
│ │ │ ├─┬ commoner@0.10.4 
│ │ │ │ ├─┬ detective@4.3.1 
│ │ │ │ │ └── defined@1.0.0 
│ │ │ │ ├─┬ glob@5.0.15 
│ │ │ │ │ ├── inflight@1.0.5 
│ │ │ │ │ ├── minimatch@3.0.3 
│ │ │ │ │ └── path-is-absolute@1.0.0 
│ │ │ │ ├── graceful-fs@4.1.5 
│ │ │ │ ├─┬ mkdirp@0.5.1 
│ │ │ │ │ └── minimist@0.0.8 
│ │ │ │ └── q@1.4.1 
│ │ │ ├── esprima-fb@15001.1.0-dev-harmony-fb 
│ │ │ ├── object-assign@2.1.1 
│ │ │ └─┬ source-map@0.4.4 
│ │ │   └── amdefine@1.0.0 
│ │ └── through@2.3.8 
│ ├── immediate@3.0.6 
│ ├─┬ inline-process-browser@1.0.0 
│ │ ├─┬ falafel@1.2.0 
│ │ │ ├── acorn@1.2.2 
│ │ │ ├── foreach@2.0.5 
│ │ │ └── object-keys@1.0.11 
│ │ └─┬ through2@0.6.5 
│ │   └── readable-stream@1.0.34 
│ └─┬ unreachable-branch-transform@0.3.0 
│   ├── esmangle-evaluator@1.0.1 
│   └─┬ recast@0.10.43 
│     ├── ast-types@0.8.15 
│     ├── esprima-fb@15001.1001.0-dev-harmony-fb 
│     ├── private@0.1.6 
│     └── source-map@0.5.6 
├── long@3.0.3 
├─┬ multiplex@6.7.0 
│ ├─┬ duplexify@3.4.5 
│ │ ├─┬ end-of-stream@1.0.0 
│ │ │ └─┬ once@1.3.3 
│ │ │   └── wrappy@1.0.2 
│ │ ├─┬ readable-stream@2.1.4 
│ │ │ └── isarray@1.0.0 
│ │ └── stream-shift@1.0.0 
│ ├── inherits@2.0.1 
│ ├─┬ readable-stream@2.1.4 
│ │ ├── buffer-shims@1.0.0 
│ │ ├── core-util-is@1.0.2 
│ │ ├── isarray@1.0.0 
│ │ ├── process-nextick-args@1.0.7 
│ │ ├── string_decoder@0.10.31 
│ │ └── util-deprecate@1.0.2 
│ ├── varint@4.0.1 
│ └── xtend@4.0.1 
├── node-ssdp@2.6.5  (git://github.com/thaliproject/node-ssdp.git#fcc5d403f6cc5e667572fba059332908c3cc822e)
├── node-uuid@1.4.7 
├─┬ request@2.64.0 
│ ├── aws-sign2@0.5.0 
│ ├─┬ bl@1.0.3 
│ │ └─┬ readable-stream@2.0.6 
│ │   └── isarray@1.0.0 
│ ├── caseless@0.11.0 
│ ├─┬ combined-stream@1.0.5 
│ │ └── delayed-stream@1.0.0 
│ ├── extend@3.0.0 
│ ├─┬ form-data@1.0.0-rc4 
│ │ └── async@1.5.2 
│ ├─┬ har-validator@1.8.0 
│ │ ├── bluebird@2.10.2 
│ │ ├─┬ chalk@1.1.3 
│ │ │ ├── ansi-styles@2.2.1 
│ │ │ ├─┬ has-ansi@2.0.0 
│ │ │ │ └── ansi-regex@2.0.0 
│ │ │ ├── strip-ansi@3.0.1 
│ │ │ └── supports-color@2.0.0 
│ │ ├─┬ commander@2.9.0 
│ │ │ └── graceful-readlink@1.0.1 
│ │ └─┬ is-my-json-valid@2.13.1 
│ │   ├── generate-function@2.0.0 
│ │   ├─┬ generate-object-property@1.2.0 
│ │   │ └── is-property@1.0.2 
│ │   └── jsonpointer@2.0.0 
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
│ ├─┬ mime-types@2.1.11 
│ │ └── mime-db@1.23.0 
│ ├── oauth-sign@0.8.2 
│ ├── qs@5.1.0 
│ ├── stringstream@0.0.5 
│ ├── tough-cookie@2.2.2 
│ └── tunnel-agent@0.4.3 
├─┬ salti@0.2.0  (git+https://github.com/thaliproject/salti.git#2dadb4413347200a22e2fa3faff4dfc37bf1e214)
│ ├── jsonschema@1.1.0 
│ └── object-assign@4.1.0 
├── urlsafe-base64@1.0.0 
└─┬ winston@2.2.0 
  ├── async@1.0.0 
  ├── colors@1.0.3 
  ├── cycle@1.0.3 
  ├── eyes@0.1.8 
  ├── pkginfo@0.3.1 
  └── stack-trace@0.0.9 


> sqlite3@3.1.4 install /Users/thali/Github/Thali_CordovaPlugin/thali/node_modules/sqlite3
> node-pre-gyp install --fallback-to-build

[sqlite3] Success: "/Users/thali/Github/Thali_CordovaPlugin/thali/node_modules/sqlite3/lib/binding/node-v11-darwin-x64/node_sqlite3.node" is installed via remote

> leveldown@1.4.6 install /Users/thali/Github/Thali_CordovaPlugin/thali/node_modules/leveldown
> "/usr/local/bin/jx" /Users/thali/.jx/npm/node_modules/node-gyp/bin/node-gyp.js rebuild

Target arch x64
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/db/builder.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/db/db_impl.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/db/db_iter.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/db/filename.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/db/dbformat.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/db/leveldb_main.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/db/log_reader.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/db/log_writer.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/db/memtable.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/db/repair.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/db/table_cache.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/db/version_edit.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/db/version_set.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/db/write_batch.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/helpers/memenv/memenv.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/table/block.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/table/block_builder.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/table/filter_block.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/table/format.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/table/iterator.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/table/merger.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/table/table.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/table/table_builder.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/table/two_level_iterator.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/util/arena.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/util/bloom.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/util/cache.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/util/coding.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/util/comparator.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/util/crc32c.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/util/env.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/util/filter_policy.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/util/hash.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/util/logging.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/util/options.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/util/status.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/port/port_posix.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/util/env_posix.o
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

> thali@2.1.0 postinstall /Users/thali/Github/Thali_CordovaPlugin/thali
> jx installCordovaPlugin.js

We believe we are in a clone of the GitHub Repo so we will not install Cordova dependencies

> thali@2.1.0 prepublish /Users/thali/Github/Thali_CordovaPlugin/thali
> jx install/prePublishThaliCordovaPlugin.js

thali@2.1.0 /Users/thali/Github/Thali_CordovaPlugin/thali
├─┬ express-pouchdb@1.0.4
│ └─┬ pouchdb-auth@2.1.0
│   └─┬ pouchdb@5.4.5
│     ├─┬ leveldown@1.4.6 
│     │ ├── abstract-leveldown@2.4.1 
│     │ ├── bindings@1.2.1 
│     │ ├── fast-future@1.0.1 
│     │ ├── nan@2.3.5 
│     │ └─┬ prebuild@4.2.2 
│     │   ├── expand-template@1.0.2 
│     │   ├─┬ ghreleases@1.0.5 
│     │   │ ├── after@0.8.1 
│     │   │ ├── ghrepos@2.0.0 
│     │   │ ├─┬ ghutils@3.2.0 
│     │   │ │ └─┬ jsonist@1.2.0 
│     │   │ │   ├─┬ bl@1.0.3 
│     │   │ │   │ └─┬ readable-stream@2.0.6 
│     │   │ │   │   └── isarray@1.0.0 
│     │   │ │   └─┬ hyperquest@1.2.0 
│     │   │ │     └── duplexer2@0.0.2 
│     │   │ ├── simple-mime@0.1.0 
│     │   │ └── url-template@2.0.8 
│     │   ├── github-from-package@0.0.0 
│     │   ├─┬ node-gyp@3.4.0 
│     │   │ ├── fstream@1.0.10 
│     │   │ ├─┬ glob@7.0.5 
│     │   │ │ └── fs.realpath@1.0.0 
│     │   │ ├─┬ nopt@3.0.6 
│     │   │ │ └── abbrev@1.0.9 
│     │   │ ├─┬ osenv@0.1.3 
│     │   │ │ └── os-tmpdir@1.0.1 
│     │   │ ├─┬ path-array@1.0.1 
│     │   │ │ └─┬ array-index@1.0.0 
│     │   │ │   └─┬ es6-symbol@3.1.0 
│     │   │ │     ├── d@0.1.1 
│     │   │ │     └─┬ es5-ext@0.10.12 
│     │   │ │       └── es6-iterator@2.0.0 
│     │   │ ├─┬ rimraf@2.5.4 
│     │   │ │ └── glob@7.0.5 
│     │   │ ├─┬ tar@2.2.1 
│     │   │ │ └── block-stream@0.0.9 
│     │   │ └─┬ which@1.2.10 
│     │   │   └── isexe@1.1.2 
│     │   ├── node-ninja@1.0.2 
│     │   ├── noop-logger@0.1.1 
│     │   ├─┬ npmlog@2.0.4 
│     │   │ ├── ansi@0.3.1 
│     │   │ ├─┬ are-we-there-yet@1.1.2 
│     │   │ │ └── delegates@1.0.0 
│     │   │ └─┬ gauge@1.2.7 
│     │   │   ├── has-unicode@2.0.1 
│     │   │   ├── lodash.pad@4.5.0 
│     │   │   ├── lodash.padend@4.6.0 
│     │   │   └── lodash.padstart@4.6.0 
│     │   ├── os-homedir@1.0.1 
│     │   ├─┬ pump@1.0.1 
│     │   │ └── end-of-stream@1.1.0 
│     │   ├─┬ rc@1.1.6 
│     │   │ ├── deep-extend@0.4.1 
│     │   │ └── ini@1.3.4 
│     │   ├─┬ simple-get@1.4.3 
│     │   │ └── unzip-response@1.0.0 
│     │   ├── tar-fs@1.13.0 
│     │   └─┬ tar-stream@1.5.2 
│     │     └─┬ readable-stream@2.1.4 
│     │       └── isarray@1.0.0 
│     ├─┬ levelup@1.3.2
│     │ └─┬ deferred-leveldown@1.2.1
│     │   └── abstract-leveldown@2.4.1 
│     ├─┬ request@2.72.0
│     │ ├─┬ bl@1.1.2
│     │ │ └─┬ readable-stream@2.0.6 
│     │ │   └── isarray@1.0.0 
│     │ └─┬ http-signature@1.1.1
│     │   └─┬ sshpk@1.9.2
│     │     ├── ecc-jsbn@0.1.1 
│     │     ├── jodid25519@1.0.2 
│     │     ├── jsbn@0.1.0 
│     │     └── tweetnacl@0.13.3 
│     ├─┬ through2@2.0.1
│     │ └─┬ readable-stream@2.0.6 
│     │   └── isarray@1.0.0 
│     └─┬ websql@0.4.4 
│       ├── immediate@3.2.2 
│       ├── noop-fn@1.0.0 
│       └─┬ sqlite3@3.1.4 
│         └─┬ node-pre-gyp@0.6.28
│           ├── nopt@3.0.6 
│           ├─┬ npmlog@2.0.3
│           │ ├── ansi@0.3.1 
│           │ ├─┬ are-we-there-yet@1.1.2 
│           │ │ └── delegates@1.0.0 
│           │ └── gauge@1.2.7 
│           ├─┬ rc@1.1.6 
│           │ ├── deep-extend@0.4.1 
│           │ └── ini@1.3.4 
│           ├─┬ request@2.72.0
│           │ ├─┬ bl@1.1.2
│           │ │ └── readable-stream@2.0.6 
│           │ └─┬ http-signature@1.1.1
│           │   └─┬ sshpk@1.8.3
│           │     ├── ecc-jsbn@0.1.1 
│           │     ├── jodid25519@1.0.2 
│           │     ├── jsbn@0.1.0 
│           │     └── tweetnacl@0.13.3 
│           ├─┬ tar@2.2.1 
│           │ └── block-stream@0.0.9 
│           └─┬ tar-pack@3.1.3
│             └─┬ readable-stream@2.0.6 
│               └── isarray@1.0.0 
├─┬ multiplex@6.7.0
│ ├─┬ duplexify@3.4.5
│ │ └─┬ readable-stream@2.1.4 
│ │   └── isarray@1.0.0 
│ └─┬ readable-stream@2.1.4 
│   └── isarray@1.0.0 
└─┬ request@2.64.0
  └─┬ bl@1.0.3 
    └─┬ readable-stream@2.0.6 
      └── isarray@1.0.0 

/usr/local/lib/node_modules/thali -> /Users/thali/Github/Thali_CordovaPlugin/thali
install@0.0.1 /Users/thali/Github/Thali_CordovaPlugin/thali/install
├─┬ fs-extra-promise@0.2.0 
│ ├── bluebird@2.10.2 
│ └─┬ fs-extra@0.21.0 
│   ├── graceful-fs@4.1.5 
│   ├── jsonfile@2.3.1 
│   └─┬ rimraf@2.5.4 
│     └─┬ glob@7.0.5 
│       ├── fs.realpath@1.0.0 
│       ├─┬ inflight@1.0.5 
│       │ └── wrappy@1.0.2 
│       ├─┬ minimatch@3.0.3 
│       │ └─┬ brace-expansion@1.1.6 
│       │   ├── balanced-match@0.4.2 
│       │   └── concat-map@0.0.1 
│       ├── once@1.3.3 
│       └── path-is-absolute@1.0.0 
├─┬ jxc@1.0.14 
│ └─┬ jxtools@0.0.4  (git+https://github.com/ktrzeciaknubisa/jxtools.git#644cf31ea259cb65a97e5c3ed5ea1236dba298a3)
│   ├── adm-zip@0.4.7 
│   └── progress@1.1.8 
├─┬ lie@3.0.4 
│ ├─┬ es3ify@0.2.2 
│ │ ├── esprima@2.7.2 
│ │ ├─┬ jstransform@11.0.3 
│ │ │ ├── base62@1.1.1 
│ │ │ ├─┬ commoner@0.10.4 
│ │ │ │ ├─┬ detective@4.3.1 
│ │ │ │ │ └── defined@1.0.0 
│ │ │ │ ├── glob@5.0.15 
│ │ │ │ ├── iconv-lite@0.4.13 
│ │ │ │ └── q@1.4.1 
│ │ │ ├── esprima-fb@15001.1.0-dev-harmony-fb 
│ │ │ ├── object-assign@2.1.1 
│ │ │ └─┬ source-map@0.4.4 
│ │ │   └── amdefine@1.0.0 
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
│ ├─┬ form-data@1.0.0-rc4 
│ │ └── async@1.5.2 
│ ├─┬ har-validator@1.8.0 
│ │ ├─┬ chalk@1.1.3 
│ │ │ ├── ansi-styles@2.2.1 
│ │ │ ├── escape-string-regexp@1.0.5 
│ │ │ ├─┬ has-ansi@2.0.0 
│ │ │ │ └── ansi-regex@2.0.0 
│ │ │ ├── strip-ansi@3.0.1 
│ │ │ └── supports-color@2.0.0 
│ │ ├─┬ commander@2.9.0 
│ │ │ └── graceful-readlink@1.0.1 
│ │ └─┬ is-my-json-valid@2.13.1 
│ │   ├── generate-function@2.0.0 
│ │   ├─┬ generate-object-property@1.2.0 
│ │   │ └── is-property@1.0.2 
│ │   └── jsonpointer@2.0.0 
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
│ ├─┬ mime-types@2.1.11 
│ │ └── mime-db@1.23.0 
│ ├── node-uuid@1.4.7 
│ ├── oauth-sign@0.8.2 
│ ├── qs@5.1.0 
│ ├── stringstream@0.0.5 
│ ├── tough-cookie@2.3.1 
│ └── tunnel-agent@0.4.3 
└─┬ unzip@0.1.11 
  ├─┬ binary@0.3.0 
  │ ├── buffers@0.1.1 
  │ └─┬ chainsaw@0.1.0 
  │   └── traverse@0.3.9 
  ├─┬ fstream@0.1.31 
  │ ├── graceful-fs@3.0.8 
  │ ├── inherits@2.0.1 
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
  └── setimmediate@1.0.4 

/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/thali -> /usr/local/lib/node_modules/thali -> /Users/thali/Github/Thali_CordovaPlugin/thali

> leveldown@1.4.6 install /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/leveldown
> "/usr/local/bin/jx" /Users/thali/.jx/npm/node_modules/node-gyp/bin/node-gyp.js rebuild

Target arch x64
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/db/builder.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/db/db_impl.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/db/db_iter.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/db/filename.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/db/dbformat.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/db/leveldb_main.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/db/log_reader.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/db/log_writer.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/db/memtable.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/db/repair.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/db/table_cache.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/db/version_edit.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/db/version_set.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/db/write_batch.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/helpers/memenv/memenv.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/table/block.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/table/block_builder.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/table/filter_block.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/table/format.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/table/iterator.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/table/merger.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/table/table.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/table/table_builder.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/table/two_level_iterator.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/util/arena.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/util/bloom.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/util/cache.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/util/coding.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/util/comparator.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/util/crc32c.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/util/env.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/util/filter_policy.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/util/hash.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/util/logging.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/util/options.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/util/status.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/port/port_posix.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.18.0/util/env_posix.o
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
thali-cordova-plugin-jxcore@1.0.0 /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore
├── balanced-match@0.2.0 
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
│ │ ├── iconv-lite@0.4.13 
│ │ └── unpipe@1.0.0 
│ └─┬ type-is@1.6.13 
│   └── media-typer@0.3.0 
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
├─┬ express-pouchdb@1.0.4 
│ ├── basic-auth@1.0.3 
│ ├── bluebird@3.3.4 
│ ├─┬ body-parser@1.15.0 
│ │ ├── bytes@2.2.0 
│ │ ├── depd@1.1.0 
│ │ ├── http-errors@1.4.0 
│ │ ├── iconv-lite@0.4.13 
│ │ └── qs@6.1.0 
│ ├─┬ compression@1.6.1 
│ │ ├─┬ accepts@1.3.3 
│ │ │ └── negotiator@0.6.1 
│ │ ├── bytes@2.2.0 
│ │ ├── compressible@2.0.8 
│ │ ├── on-headers@1.0.1 
│ │ └── vary@1.1.0 
│ ├─┬ cookie-parser@1.4.1 
│ │ └── cookie@0.2.3 
│ ├── extend@1.3.0 
│ ├── header-case-normalizer@1.0.3 
│ ├─┬ multiparty@3.3.2 
│ │ ├── readable-stream@1.1.14 
│ │ └── stream-counter@0.2.0 
│ ├── node-uuid@1.4.1 
│ ├─┬ pouchdb-all-dbs@1.0.1 
│ │ ├── argsarray@0.0.1 
│ │ ├─┬ es3ify@0.1.4 
│ │ │ ├── esprima-fb@3001.1.0-dev-harmony-fb 
│ │ │ └─┬ jstransform@3.0.0 
│ │ │   ├── base62@0.1.1 
│ │ │   └── source-map@0.1.31 
│ │ ├─┬ lie@2.9.1 
│ │ │ └── unreachable-branch-transform@0.2.3 
│ │ └── tiny-queue@0.2.1 
│ ├─┬ pouchdb-auth@2.1.0 
│ │ ├─┬ base64url@1.0.6 
│ │ │ ├─┬ concat-stream@1.4.10 
│ │ │ │ └── typedarray@0.0.6 
│ │ │ └─┬ meow@2.0.0 
│ │ │   ├─┬ camelcase-keys@1.0.0 
│ │ │   │ ├── camelcase@1.2.1 
│ │ │   │ └── map-obj@1.0.1 
│ │ │   ├─┬ indent-string@1.2.2 
│ │ │   │ ├── get-stdin@4.0.1 
│ │ │   │ └─┬ repeating@1.1.3 
│ │ │   │   └─┬ is-finite@1.0.1 
│ │ │   │     └── number-is-nan@1.0.0 
│ │ │   └── object-assign@1.0.0 
│ │ ├─┬ couchdb-calculate-session-id@1.1.0 
│ │ │ └── aproba@1.0.4 
│ │ ├── crypto-lite@0.1.0 
│ │ ├─┬ pouchdb@5.4.5 
│ │ │ ├── es6-promise-pool@2.4.2 
│ │ │ ├─┬ fruitdown@1.0.2 
│ │ │ │ ├─┬ abstract-leveldown@0.12.3 
│ │ │ │ │ └── xtend@3.0.0 
│ │ │ │ ├── d64@1.0.0 
│ │ │ │ └── tiny-queue@0.2.0 
│ │ │ ├── js-extend@0.0.1 
│ │ │ ├─┬ level-write-stream@1.0.0 
│ │ │ │ └─┬ end-stream@0.1.0 
│ │ │ │   └─┬ write-stream@0.4.3 
│ │ │ │     └── readable-stream@0.0.4 
│ │ │ ├─┬ levelup@1.3.2 
│ │ │ │ ├─┬ deferred-leveldown@1.2.1 
│ │ │ │ │ └── abstract-leveldown@2.4.1 
│ │ │ │ ├── level-codec@6.1.0 
│ │ │ │ ├── level-errors@1.0.4 
│ │ │ │ ├── level-iterator-stream@1.3.1 
│ │ │ │ ├── prr@1.0.1 
│ │ │ │ └── semver@5.1.1 
│ │ │ ├─┬ localstorage-down@0.6.6 
│ │ │ │ ├─┬ humble-localstorage@1.4.2 
│ │ │ │ │ ├── has-localstorage@1.0.1 
│ │ │ │ │ └── localstorage-memory@1.0.2 
│ │ │ │ └── tiny-queue@0.2.0 
│ │ │ ├─┬ memdown@1.1.2 
│ │ │ │ ├── abstract-leveldown@2.6.0 
│ │ │ │ ├── functional-red-black-tree@1.0.1 
│ │ │ │ └── ltgt@1.0.2 
│ │ │ ├─┬ request@2.72.0 
│ │ │ │ ├── aws-sign2@0.6.0 
│ │ │ │ ├── aws4@1.4.1 
│ │ │ │ ├─┬ bl@1.1.2 
│ │ │ │ │ └─┬ readable-stream@2.0.6 
│ │ │ │ │   └── isarray@1.0.0 
│ │ │ │ ├── extend@3.0.0 
│ │ │ │ ├─┬ har-validator@2.0.6 
│ │ │ │ │ └─┬ pinkie-promise@2.0.1 
│ │ │ │ │   └── pinkie@2.0.4 
│ │ │ │ ├─┬ http-signature@1.1.1 
│ │ │ │ │ ├── assert-plus@0.2.0 
│ │ │ │ │ ├─┬ jsprim@1.3.0 
│ │ │ │ │ │ ├── extsprintf@1.0.2 
│ │ │ │ │ │ ├── json-schema@0.2.2 
│ │ │ │ │ │ └── verror@1.3.6 
│ │ │ │ │ └─┬ sshpk@1.9.2 
│ │ │ │ │   ├── asn1@0.2.3 
│ │ │ │ │   ├── assert-plus@1.0.0 
│ │ │ │ │   ├─┬ dashdash@1.14.0 
│ │ │ │ │   │ └── assert-plus@1.0.0 
│ │ │ │ │   └─┬ getpass@0.1.6 
│ │ │ │ │     └── assert-plus@1.0.0 
│ │ │ │ ├── is-typedarray@1.0.0 
│ │ │ │ └── qs@6.1.0 
│ │ │ ├─┬ sublevel-pouchdb@1.0.1 
│ │ │ │ ├─┬ errno@0.1.4 
│ │ │ │ │ └── prr@0.0.0 
│ │ │ │ ├── ltgt@2.1.2 
│ │ │ │ ├─┬ pull-stream@2.21.0 
│ │ │ │ │ └── pull-core@1.0.0 
│ │ │ │ └── readable-stream@1.0.33 
│ │ │ ├─┬ through2@2.0.1 
│ │ │ │ └─┬ readable-stream@2.0.6 
│ │ │ │   └── isarray@1.0.0 
│ │ │ └── vuvuzela@1.0.3 
│ │ ├─┬ pouchdb-bulkdocs-wrapper@1.0.2 
│ │ │ └─┬ pouchdb-promise@0.0.0 
│ │ │   ├── bluebird@1.2.4 
│ │ │   └── lie@2.7.7 
│ │ ├── pouchdb-plugin-error@1.0.1 
│ │ ├── pouchdb-promise@5.4.5 
│ │ ├─┬ pouchdb-req-http-query@1.0.3 
│ │ │ ├─┬ pouchdb-promise@0.0.0 
│ │ │ │ ├── bluebird@1.2.4 
│ │ │ │ └── lie@2.7.7 
│ │ │ └─┬ xmlhttprequest-cookie@0.9.4 
│ │ │   └── xmlhttprequest@1.8.0 
│ │ ├── pouchdb-system-db@1.0.4 
│ │ ├── promise-nodify@1.0.2 
│ │ └── secure-random@1.1.1 
│ ├─┬ pouchdb-find@0.1.0 
│ │ ├─┬ jshint@2.9.2 
│ │ │ ├─┬ cli@0.6.6 
│ │ │ │ └─┬ glob@3.2.11 
│ │ │ │   └─┬ minimatch@0.3.0 
│ │ │ │     ├── lru-cache@2.7.3 
│ │ │ │     └── sigmund@1.0.1 
│ │ │ ├─┬ console-browserify@1.1.0 
│ │ │ │ └── date-now@0.1.4 
│ │ │ ├── exit@0.1.2 
│ │ │ ├─┬ htmlparser2@3.8.3 
│ │ │ │ ├── domelementtype@1.3.0 
│ │ │ │ ├── domhandler@2.3.0 
│ │ │ │ ├─┬ domutils@1.5.1 
│ │ │ │ │ └─┬ dom-serializer@0.1.0 
│ │ │ │ │   ├── domelementtype@1.1.3 
│ │ │ │ │   └── entities@1.1.1 
│ │ │ │ └── entities@1.0.0 
│ │ │ ├── lodash@3.7.0 
│ │ │ ├── minimatch@2.0.10 
│ │ │ ├── shelljs@0.3.0 
│ │ │ └── strip-json-comments@1.0.4 
│ │ ├── lie@2.9.1 
│ │ ├─┬ pouchdb-abstract-mapreduce@0.2.2 
│ │ │ ├── lie@2.9.1 
│ │ │ └── spark-md5@0.0.5 
│ │ ├── pouchdb-collate@1.2.0 
│ │ ├── pouchdb-extend@0.1.2 
│ │ ├─┬ pouchdb-upsert@1.1.3 
│ │ │ └── lie@2.9.1 
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
│ ├─┬ pouchdb-size@1.2.2 
│ │ ├── bluebird@2.10.2 
│ │ └─┬ get-folder-size@0.1.1 
│ │   ├── async@0.9.2 
│ │   └── minimist@0.1.0 
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
│ ├── pouchdb-wrappers@1.3.6 
│ └─┬ raw-body@2.1.6 
│   └── bytes@2.3.0 
├── forever-agent@0.6.1 
├─┬ fs-extra-promise@0.2.0 
│ ├── bluebird@2.10.2 
│ └─┬ fs-extra@0.21.0 
│   ├── graceful-fs@4.1.5 
│   ├── jsonfile@2.3.1 
│   └─┬ rimraf@2.5.4 
│     └─┬ glob@7.0.5 
│       └── fs.realpath@1.0.0 
├── inherits@2.0.1 
├── is-property@1.0.2 
├── js-extend@1.0.1 
├─┬ leveldown-mobile@1.1.1 
│ ├── abstract-leveldown@2.1.4 
│ ├── bindings@1.2.1 
│ └── fast-future@1.0.1 
├─┬ lie@3.0.4 
│ ├─┬ es3ify@0.2.2 
│ │ ├── esprima@2.7.2 
│ │ └─┬ jstransform@11.0.3 
│ │   ├── base62@1.1.1 
│ │   ├─┬ commoner@0.10.4 
│ │   │ ├─┬ detective@4.3.1 
│ │   │ │ └── defined@1.0.0 
│ │   │ └── q@1.4.1 
│ │   ├── esprima-fb@15001.1.0-dev-harmony-fb 
│ │   ├── object-assign@2.1.1 
│ │   └─┬ source-map@0.4.4 
│ │     └── amdefine@1.0.0 
│ ├── immediate@3.0.6 
│ ├─┬ inline-process-browser@1.0.0 
│ │ ├─┬ falafel@1.2.0 
│ │ │ ├── acorn@1.2.2 
│ │ │ ├── foreach@2.0.5 
│ │ │ └── object-keys@1.0.11 
│ │ └─┬ through2@0.6.5 
│ │   └── readable-stream@1.0.34 
│ └─┬ unreachable-branch-transform@0.3.0 
│   ├── esmangle-evaluator@1.0.1 
│   └─┬ recast@0.10.43 
│     ├── ast-types@0.8.15 
│     ├── esprima-fb@15001.1001.0-dev-harmony-fb 
│     ├── private@0.1.6 
│     └── source-map@0.5.6 
├── long@3.0.3 
├── minimist@1.2.0 
├─┬ multiplex@6.7.0 
│ ├─┬ duplexify@3.4.5 
│ │ ├── end-of-stream@1.0.0 
│ │ ├─┬ readable-stream@2.1.4 
│ │ │ └── isarray@1.0.0 
│ │ └── stream-shift@1.0.0 
│ ├─┬ readable-stream@2.1.4 
│ │ ├── buffer-shims@1.0.0 
│ │ ├── core-util-is@1.0.2 
│ │ ├── isarray@1.0.0 
│ │ ├── process-nextick-args@1.0.7 
│ │ ├── string_decoder@0.10.31 
│ │ └── util-deprecate@1.0.2 
│ ├── varint@4.0.1 
│ └── xtend@4.0.1 
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
│ ├─┬ mkdirp@0.5.1 
│ │ └── minimist@0.0.8 
│ └── propagate@0.3.1 
├─┬ node-ssdp@2.6.5  (git://github.com/thaliproject/node-ssdp.git#fcc5d403f6cc5e667572fba059332908c3cc822e)
│ └── ip@1.1.3 
├── node-uuid@1.4.7 
├─┬ pouchdb-node@5.4.4 
│ ├─┬ pouchdb-adapter-http@5.4.4 
│ │ ├─┬ pouchdb-ajax@5.4.4 
│ │ │ ├── pouchdb-promise@5.4.4 
│ │ │ └─┬ request@2.72.0 
│ │ │   ├── extend@3.0.0 
│ │ │   └── qs@6.1.0 
│ │ ├── pouchdb-binary-utils@5.4.4 
│ │ ├── pouchdb-errors@5.4.4 
│ │ ├─┬ pouchdb-md5@5.4.4 
│ │ │ └── pouchdb-promise@5.4.4 
│ │ ├── pouchdb-promise@5.4.4 
│ │ └─┬ pouchdb-utils@5.4.4 
│ │   └── pouchdb-promise@5.4.4 
│ ├─┬ pouchdb-adapter-leveldb@5.4.4 
│ │ ├─┬ leveldown@1.4.6 
│ │ │ ├── abstract-leveldown@2.4.1 
│ │ │ ├── nan@2.3.5 
│ │ │ └─┬ prebuild@4.2.2 
│ │ │   ├── expand-template@1.0.2 
│ │ │   ├─┬ ghreleases@1.0.5 
│ │ │   │ ├── ghrepos@2.0.0 
│ │ │   │ ├─┬ ghutils@3.2.0 
│ │ │   │ │ └─┬ jsonist@1.2.0 
│ │ │   │ │   ├─┬ bl@1.0.3 
│ │ │   │ │   │ └─┬ readable-stream@2.0.6 
│ │ │   │ │   │   └── isarray@1.0.0 
│ │ │   │ │   └─┬ hyperquest@1.2.0 
│ │ │   │ │     └── duplexer2@0.0.2 
│ │ │   │ ├── simple-mime@0.1.0 
│ │ │   │ └── url-template@2.0.8 
│ │ │   ├── github-from-package@0.0.0 
│ │ │   ├─┬ node-gyp@3.4.0 
│ │ │   │ ├── fstream@1.0.10 
│ │ │   │ ├── glob@7.0.5 
│ │ │   │ ├─┬ nopt@3.0.6 
│ │ │   │ │ └── abbrev@1.0.9 
│ │ │   │ ├── osenv@0.1.3 
│ │ │   │ ├─┬ path-array@1.0.1 
│ │ │   │ │ └─┬ array-index@1.0.0 
│ │ │   │ │   └─┬ es6-symbol@3.1.0 
│ │ │   │ │     ├── d@0.1.1 
│ │ │   │ │     └─┬ es5-ext@0.10.12 
│ │ │   │ │       └── es6-iterator@2.0.0 
│ │ │   │ ├─┬ tar@2.2.1 
│ │ │   │ │ └── block-stream@0.0.9 
│ │ │   │ └─┬ which@1.2.10 
│ │ │   │   └── isexe@1.1.2 
│ │ │   ├── node-ninja@1.0.2 
│ │ │   ├── noop-logger@0.1.1 
│ │ │   ├─┬ npmlog@2.0.4 
│ │ │   │ ├── ansi@0.3.1 
│ │ │   │ ├─┬ are-we-there-yet@1.1.2 
│ │ │   │ │ └── delegates@1.0.0 
│ │ │   │ └─┬ gauge@1.2.7 
│ │ │   │   ├── has-unicode@2.0.1 
│ │ │   │   ├── lodash.pad@4.5.0 
│ │ │   │   ├── lodash.padend@4.6.0 
│ │ │   │   └── lodash.padstart@4.6.0 
│ │ │   ├── os-homedir@1.0.1 
│ │ │   ├─┬ pump@1.0.1 
│ │ │   │ └── end-of-stream@1.1.0 
│ │ │   ├─┬ rc@1.1.6 
│ │ │   │ ├── deep-extend@0.4.1 
│ │ │   │ └── ini@1.3.4 
│ │ │   ├─┬ simple-get@1.4.3 
│ │ │   │ └── unzip-response@1.0.0 
│ │ │   ├── tar-fs@1.13.0 
│ │ │   └─┬ tar-stream@1.5.2 
│ │ │     └─┬ readable-stream@2.1.4 
│ │ │       └── isarray@1.0.0 
│ │ └─┬ pouchdb-adapter-leveldb-core@5.4.4 
│ │   ├── pouchdb-adapter-utils@5.4.4 
│ │   ├── pouchdb-json@5.4.4 
│ │   ├── pouchdb-promise@5.4.4 
│ │   └─┬ through2@2.0.1 
│ │     └─┬ readable-stream@2.0.6 
│ │       └── isarray@1.0.0 
│ ├─┬ pouchdb-core@5.4.4 
│ │ ├── double-ended-queue@2.0.0-0 
│ │ ├── pouchdb-collections@1.0.1 
│ │ ├── pouchdb-merge@5.4.4 
│ │ ├── pouchdb-promise@5.4.4 
│ │ └── scope-eval@0.0.3 
│ ├─┬ pouchdb-mapreduce@5.4.4 
│ │ ├── pouchdb-mapreduce-utils@5.4.4 
│ │ ├── pouchdb-promise@5.4.4 
│ │ └── spark-md5@2.0.2 
│ └─┬ pouchdb-replication@5.4.4 
│   ├─┬ pouchdb-checkpointer@5.4.4 
│   │ └── pouchdb-promise@5.4.4 
│   ├─┬ pouchdb-generate-replication-id@5.4.4 
│   │ └── pouchdb-promise@5.4.4 
│   └── pouchdb-promise@5.4.4 
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
│ ├─┬ form-data@1.0.0-rc4 
│ │ └── async@1.5.2 
│ ├─┬ har-validator@1.8.0 
│ │ ├── bluebird@2.10.2 
│ │ ├─┬ commander@2.9.0 
│ │ │ └── graceful-readlink@1.0.1 
│ │ └─┬ is-my-json-valid@2.13.1 
│ │   ├── generate-function@2.0.0 
│ │   ├── generate-object-property@1.2.0 
│ │   └── jsonpointer@2.0.0 
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
│ ├─┬ mime-types@2.1.11 
│ │ └── mime-db@1.23.0 
│ ├── oauth-sign@0.8.2 
│ ├── qs@5.1.0 
│ ├── stringstream@0.0.5 
│ ├── tough-cookie@2.2.2 
│ └── tunnel-agent@0.4.3 
├─┬ request-promise@0.4.3 
│ ├── bluebird@2.10.2 
│ ├─┬ chalk@1.1.3 
│ │ ├── ansi-styles@2.2.1 
│ │ ├── escape-string-regexp@1.0.5 
│ │ ├─┬ has-ansi@2.0.0 
│ │ │ └── ansi-regex@2.0.0 
│ │ ├── strip-ansi@3.0.1 
│ │ └── supports-color@2.0.0 
│ └── lodash@3.10.1 
├─┬ salti@0.2.0  (git+https://github.com/thaliproject/salti.git#2dadb4413347200a22e2fa3faff4dfc37bf1e214)
│ ├── jsonschema@1.1.0 
│ └── object-assign@4.1.0 
├─┬ sinon@1.17.3 
│ ├── formatio@1.1.1 
│ ├── lolex@1.3.2 
│ ├── samsam@1.1.2 
│ └── util@0.10.3 
├─┬ socket.io-client@1.3.6 
│ ├── backo2@1.0.2 
│ ├── component-bind@1.0.0 
│ ├── component-emitter@1.1.2 
│ ├── debug@0.7.4 
│ ├─┬ engine.io-client@1.5.2 
│ │ ├── component-inherit@0.0.3 
│ │ ├─┬ debug@1.0.4 
│ │ │ └── ms@0.6.2 
│ │ ├─┬ engine.io-parser@1.2.1 
│ │ │ ├── after@0.8.1 
│ │ │ ├── arraybuffer.slice@0.0.6 
│ │ │ ├── base64-arraybuffer@0.1.2 
│ │ │ ├── blob@0.0.2 
│ │ │ ├── has-binary@0.1.5 
│ │ │ └── utf8@2.0.0 
│ │ ├─┬ has-cors@1.0.3 
│ │ │ └── global@2.0.1 
│ │ ├── parsejson@0.0.1 
│ │ ├── parseqs@0.0.2 
│ │ ├── parseuri@0.0.4 
│ │ ├─┬ ws@0.7.2 
│ │ │ ├── options@0.0.6 
│ │ │ └── ultron@1.0.2 
│ │ └── xmlhttprequest@1.5.0 
│ ├─┬ has-binary@0.1.6 
│ │ └── isarray@0.0.1 
│ ├── indexof@0.0.1 
│ ├── object-component@0.0.3 
│ ├─┬ parseuri@0.0.2 
│ │ └─┬ better-assert@1.0.2 
│ │   └── callsite@1.0.0 
│ ├─┬ socket.io-parser@2.2.4 
│ │ ├── benchmark@1.0.0 
│ │ ├── debug@0.7.4 
│ │ └── json3@3.2.6 
│ └── to-array@0.1.3 
├─┬ supertest@1.1.0 
│ └─┬ superagent@1.3.0 
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
│ └── bluebird@2.10.2 
├─┬ tape@4.0.0 
│ ├── defined@0.0.0 
│ ├─┬ glob@5.0.15 
│ │ ├─┬ inflight@1.0.5 
│ │ │ └── wrappy@1.0.2 
│ │ ├─┬ minimatch@3.0.3 
│ │ │ └─┬ brace-expansion@1.1.6 
│ │ │   └── balanced-match@0.4.2 
│ │ ├── once@1.3.3 
│ │ └── path-is-absolute@1.0.0 
│ ├── object-inspect@1.0.2 
│ ├── resumer@0.0.0 
│ └── through@2.3.8 
├── tape-catch@1.0.4 
├─┬ thali@2.1.0 -> /Users/thali/Github/Thali_CordovaPlugin/thali
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
│ │ │ ├── iconv-lite@0.4.13 
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
│ ├─┬ express-pouchdb@1.0.4 
│ │ ├── basic-auth@1.0.3 
│ │ ├── bluebird@3.3.4 
│ │ ├─┬ body-parser@1.15.0 
│ │ │ ├── bytes@2.2.0 
│ │ │ ├── depd@1.1.0 
│ │ │ ├── http-errors@1.4.0 
│ │ │ ├── iconv-lite@0.4.13 
│ │ │ └── qs@6.1.0 
│ │ ├─┬ compression@1.6.1 
│ │ │ ├─┬ accepts@1.3.3 
│ │ │ │ └── negotiator@0.6.1 
│ │ │ ├── bytes@2.2.0 
│ │ │ ├── compressible@2.0.8 
│ │ │ ├── on-headers@1.0.1 
│ │ │ └── vary@1.1.0 
│ │ ├─┬ cookie-parser@1.4.1 
│ │ │ └── cookie@0.2.3 
│ │ ├── extend@1.3.0 
│ │ ├── header-case-normalizer@1.0.3 
│ │ ├─┬ multiparty@3.3.2 
│ │ │ ├─┬ readable-stream@1.1.14 
│ │ │ │ └── isarray@0.0.1 
│ │ │ └── stream-counter@0.2.0 
│ │ ├── node-uuid@1.4.1 
│ │ ├─┬ pouchdb-all-dbs@1.0.1 
│ │ │ ├── argsarray@0.0.1 
│ │ │ ├─┬ es3ify@0.1.4 
│ │ │ │ ├── esprima-fb@3001.1.0-dev-harmony-fb 
│ │ │ │ └─┬ jstransform@3.0.0 
│ │ │ │   ├── base62@0.1.1 
│ │ │ │   └── source-map@0.1.31 
│ │ │ ├─┬ lie@2.9.1 
│ │ │ │ └── unreachable-branch-transform@0.2.3 
│ │ │ └── tiny-queue@0.2.1 
│ │ ├─┬ pouchdb-auth@2.1.0 
│ │ │ ├─┬ base64url@1.0.6 
│ │ │ │ ├─┬ concat-stream@1.4.10 
│ │ │ │ │ └── typedarray@0.0.6 
│ │ │ │ └─┬ meow@2.0.0 
│ │ │ │   ├─┬ camelcase-keys@1.0.0 
│ │ │ │   │ ├── camelcase@1.2.1 
│ │ │ │   │ └── map-obj@1.0.1 
│ │ │ │   ├─┬ indent-string@1.2.2 
│ │ │ │   │ ├── get-stdin@4.0.1 
│ │ │ │   │ └─┬ repeating@1.1.3 
│ │ │ │   │   └─┬ is-finite@1.0.1 
│ │ │ │   │     └── number-is-nan@1.0.0 
│ │ │ │   ├── minimist@1.2.0 
│ │ │ │   └── object-assign@1.0.0 
│ │ │ ├─┬ couchdb-calculate-session-id@1.1.0 
│ │ │ │ └── aproba@1.0.4 
│ │ │ ├── crypto-lite@0.1.0 
│ │ │ ├─┬ pouchdb@5.4.5 
│ │ │ │ ├── double-ended-queue@2.0.0-0 
│ │ │ │ ├── es6-promise-pool@2.4.2 
│ │ │ │ ├─┬ fruitdown@1.0.2 
│ │ │ │ │ ├─┬ abstract-leveldown@0.12.3 
│ │ │ │ │ │ └── xtend@3.0.0 
│ │ │ │ │ ├── d64@1.0.0 
│ │ │ │ │ └── tiny-queue@0.2.0 
│ │ │ │ ├── js-extend@0.0.1 
│ │ │ │ ├─┬ level-write-stream@1.0.0 
│ │ │ │ │ └─┬ end-stream@0.1.0 
│ │ │ │ │   └─┬ write-stream@0.4.3 
│ │ │ │ │     └── readable-stream@0.0.4 
│ │ │ │ ├─┬ leveldown@1.4.6 
│ │ │ │ │ ├── abstract-leveldown@2.4.1 
│ │ │ │ │ ├── bindings@1.2.1 
│ │ │ │ │ ├── fast-future@1.0.1 
│ │ │ │ │ ├── nan@2.3.5 
│ │ │ │ │ └─┬ prebuild@4.2.2 
│ │ │ │ │   ├── expand-template@1.0.2 
│ │ │ │ │   ├─┬ ghreleases@1.0.5 
│ │ │ │ │   │ ├── after@0.8.1 
│ │ │ │ │   │ ├── ghrepos@2.0.0 
│ │ │ │ │   │ ├─┬ ghutils@3.2.0 
│ │ │ │ │   │ │ └─┬ jsonist@1.2.0 
│ │ │ │ │   │ │   ├─┬ bl@1.0.3 
│ │ │ │ │   │ │   │ └─┬ readable-stream@2.0.6 
│ │ │ │ │   │ │   │   └── isarray@1.0.0 
│ │ │ │ │   │ │   └─┬ hyperquest@1.2.0 
│ │ │ │ │   │ │     └── duplexer2@0.0.2 
│ │ │ │ │   │ ├── simple-mime@0.1.0 
│ │ │ │ │   │ └── url-template@2.0.8 
│ │ │ │ │   ├── github-from-package@0.0.0 
│ │ │ │ │   ├─┬ node-gyp@3.4.0 
│ │ │ │ │   │ ├── fstream@1.0.10 
│ │ │ │ │   │ ├─┬ glob@7.0.5 
│ │ │ │ │   │ │ └── fs.realpath@1.0.0 
│ │ │ │ │   │ ├─┬ nopt@3.0.6 
│ │ │ │ │   │ │ └── abbrev@1.0.9 
│ │ │ │ │   │ ├─┬ osenv@0.1.3 
│ │ │ │ │   │ │ └── os-tmpdir@1.0.1 
│ │ │ │ │   │ ├─┬ path-array@1.0.1 
│ │ │ │ │   │ │ └─┬ array-index@1.0.0 
│ │ │ │ │   │ │   └─┬ es6-symbol@3.1.0 
│ │ │ │ │   │ │     ├── d@0.1.1 
│ │ │ │ │   │ │     └─┬ es5-ext@0.10.12 
│ │ │ │ │   │ │       └── es6-iterator@2.0.0 
│ │ │ │ │   │ ├─┬ rimraf@2.5.4 
│ │ │ │ │   │ │ └── glob@7.0.5 
│ │ │ │ │   │ ├─┬ tar@2.2.1 
│ │ │ │ │   │ │ └── block-stream@0.0.9 
│ │ │ │ │   │ └─┬ which@1.2.10 
│ │ │ │ │   │   └── isexe@1.1.2 
│ │ │ │ │   ├── node-ninja@1.0.2 
│ │ │ │ │   ├── noop-logger@0.1.1 
│ │ │ │ │   ├─┬ npmlog@2.0.4 
│ │ │ │ │   │ ├── ansi@0.3.1 
│ │ │ │ │   │ ├─┬ are-we-there-yet@1.1.2 
│ │ │ │ │   │ │ └── delegates@1.0.0 
│ │ │ │ │   │ └─┬ gauge@1.2.7 
│ │ │ │ │   │   ├── has-unicode@2.0.1 
│ │ │ │ │   │   ├── lodash.pad@4.5.0 
│ │ │ │ │   │   ├── lodash.padend@4.6.0 
│ │ │ │ │   │   └── lodash.padstart@4.6.0 
│ │ │ │ │   ├── os-homedir@1.0.1 
│ │ │ │ │   ├─┬ pump@1.0.1 
│ │ │ │ │   │ └── end-of-stream@1.1.0 
│ │ │ │ │   ├─┬ rc@1.1.6 
│ │ │ │ │   │ ├── deep-extend@0.4.1 
│ │ │ │ │   │ └── ini@1.3.4 
│ │ │ │ │   ├─┬ simple-get@1.4.3 
│ │ │ │ │   │ └── unzip-response@1.0.0 
│ │ │ │ │   ├── tar-fs@1.13.0 
│ │ │ │ │   └─┬ tar-stream@1.5.2 
│ │ │ │ │     └─┬ readable-stream@2.1.4 
│ │ │ │ │       └── isarray@1.0.0 
│ │ │ │ ├─┬ levelup@1.3.2 
│ │ │ │ │ ├─┬ deferred-leveldown@1.2.1 
│ │ │ │ │ │ └── abstract-leveldown@2.4.1 
│ │ │ │ │ ├── level-codec@6.1.0 
│ │ │ │ │ ├── level-errors@1.0.4 
│ │ │ │ │ ├── level-iterator-stream@1.3.1 
│ │ │ │ │ ├── prr@1.0.1 
│ │ │ │ │ └── semver@5.1.1 
│ │ │ │ ├─┬ localstorage-down@0.6.6 
│ │ │ │ │ ├─┬ humble-localstorage@1.4.2 
│ │ │ │ │ │ ├── has-localstorage@1.0.1 
│ │ │ │ │ │ └── localstorage-memory@1.0.2 
│ │ │ │ │ └── tiny-queue@0.2.0 
│ │ │ │ ├─┬ memdown@1.1.2 
│ │ │ │ │ ├── abstract-leveldown@2.6.0 
│ │ │ │ │ ├── functional-red-black-tree@1.0.1 
│ │ │ │ │ └── ltgt@1.0.2 
│ │ │ │ ├── pouchdb-collections@1.0.1 
│ │ │ │ ├─┬ request@2.72.0 
│ │ │ │ │ ├── aws-sign2@0.6.0 
│ │ │ │ │ ├── aws4@1.4.1 
│ │ │ │ │ ├─┬ bl@1.1.2 
│ │ │ │ │ │ └─┬ readable-stream@2.0.6 
│ │ │ │ │ │   └── isarray@1.0.0 
│ │ │ │ │ ├── extend@3.0.0 
│ │ │ │ │ ├─┬ har-validator@2.0.6 
│ │ │ │ │ │ └─┬ pinkie-promise@2.0.1 
│ │ │ │ │ │   └── pinkie@2.0.4 
│ │ │ │ │ ├─┬ http-signature@1.1.1 
│ │ │ │ │ │ ├── assert-plus@0.2.0 
│ │ │ │ │ │ ├─┬ jsprim@1.3.0 
│ │ │ │ │ │ │ ├── extsprintf@1.0.2 
│ │ │ │ │ │ │ ├── json-schema@0.2.2 
│ │ │ │ │ │ │ └── verror@1.3.6 
│ │ │ │ │ │ └─┬ sshpk@1.9.2 
│ │ │ │ │ │   ├── asn1@0.2.3 
│ │ │ │ │ │   ├── assert-plus@1.0.0 
│ │ │ │ │ │   ├─┬ dashdash@1.14.0 
│ │ │ │ │ │   │ └── assert-plus@1.0.0 
│ │ │ │ │ │   └─┬ getpass@0.1.6 
│ │ │ │ │ │     └── assert-plus@1.0.0 
│ │ │ │ │ ├── is-typedarray@1.0.0 
│ │ │ │ │ └── qs@6.1.0 
│ │ │ │ ├── scope-eval@0.0.3 
│ │ │ │ ├── spark-md5@2.0.2 
│ │ │ │ ├─┬ sublevel-pouchdb@1.0.1 
│ │ │ │ │ ├─┬ errno@0.1.4 
│ │ │ │ │ │ └── prr@0.0.0 
│ │ │ │ │ ├── ltgt@2.1.2 
│ │ │ │ │ ├─┬ pull-stream@2.21.0 
│ │ │ │ │ │ └── pull-core@1.0.0 
│ │ │ │ │ └── readable-stream@1.0.33 
│ │ │ │ ├─┬ through2@2.0.1 
│ │ │ │ │ └─┬ readable-stream@2.0.6 
│ │ │ │ │   └── isarray@1.0.0 
│ │ │ │ ├── vuvuzela@1.0.3 
│ │ │ │ └─┬ websql@0.4.4
│ │ │ │   └─┬ sqlite3@3.1.4
│ │ │ │     └─┬ node-pre-gyp@0.6.28
│ │ │ │       ├─┬ mkdirp@0.5.1 
│ │ │ │       │ └── minimist@0.0.8 
│ │ │ │       ├── nopt@3.0.6 
│ │ │ │       ├─┬ npmlog@2.0.3
│ │ │ │       │ ├── ansi@0.3.1 
│ │ │ │       │ ├─┬ are-we-there-yet@1.1.2 
│ │ │ │       │ │ └── delegates@1.0.0 
│ │ │ │       │ └── gauge@1.2.7 
│ │ │ │       ├─┬ rc@1.1.6 
│ │ │ │       │ ├── deep-extend@0.4.1 
│ │ │ │       │ ├── ini@1.3.4 
│ │ │ │       │ ├── minimist@1.2.0 
│ │ │ │       │ └── strip-json-comments@1.0.4 
│ │ │ │       ├─┬ request@2.72.0 
│ │ │ │       │ ├── aws-sign2@0.6.0 
│ │ │ │       │ ├── aws4@1.4.1 
│ │ │ │       │ ├─┬ bl@1.1.2 
│ │ │ │       │ │ └── readable-stream@2.0.6 
│ │ │ │       │ ├── caseless@0.11.0 
│ │ │ │       │ ├─┬ combined-stream@1.0.5 
│ │ │ │       │ │ └── delayed-stream@1.0.0 
│ │ │ │       │ ├── extend@3.0.0 
│ │ │ │       │ ├── forever-agent@0.6.1 
│ │ │ │       │ ├─┬ form-data@1.0.0-rc4 
│ │ │ │       │ │ └── async@1.5.2 
│ │ │ │       │ ├─┬ har-validator@2.0.6 
│ │ │ │       │ │ ├─┬ chalk@1.1.3 
│ │ │ │       │ │ │ ├── ansi-styles@2.2.1 
│ │ │ │       │ │ │ ├── escape-string-regexp@1.0.5 
│ │ │ │       │ │ │ ├─┬ has-ansi@2.0.0 
│ │ │ │       │ │ │ │ └── ansi-regex@2.0.0 
│ │ │ │       │ │ │ ├── strip-ansi@3.0.1 
│ │ │ │       │ │ │ └── supports-color@2.0.0 
│ │ │ │       │ │ ├─┬ commander@2.9.0 
│ │ │ │       │ │ │ └── graceful-readlink@1.0.1 
│ │ │ │       │ │ ├─┬ is-my-json-valid@2.13.1 
│ │ │ │       │ │ │ ├── generate-function@2.0.0 
│ │ │ │       │ │ │ ├─┬ generate-object-property@1.2.0 
│ │ │ │       │ │ │ │ └── is-property@1.0.2 
│ │ │ │       │ │ │ ├── jsonpointer@2.0.0 
│ │ │ │       │ │ │ └── xtend@4.0.1 
│ │ │ │       │ │ └─┬ pinkie-promise@2.0.1 
│ │ │ │       │ │   └── pinkie@2.0.4 
│ │ │ │       │ ├─┬ hawk@3.1.3 
│ │ │ │       │ │ ├── boom@2.10.1 
│ │ │ │       │ │ ├── cryptiles@2.0.5 
│ │ │ │       │ │ ├── hoek@2.16.3 
│ │ │ │       │ │ └── sntp@1.0.9 
│ │ │ │       │ ├─┬ http-signature@1.1.1 
│ │ │ │       │ │ ├── assert-plus@0.2.0 
│ │ │ │       │ │ ├─┬ jsprim@1.2.2
│ │ │ │       │ │ │ ├── extsprintf@1.0.2 
│ │ │ │       │ │ │ ├── json-schema@0.2.2 
│ │ │ │       │ │ │ └── verror@1.3.6 
│ │ │ │       │ │ └─┬ sshpk@1.8.3
│ │ │ │       │ │   ├── asn1@0.2.3 
│ │ │ │       │ │   ├── assert-plus@1.0.0 
│ │ │ │       │ │   ├─┬ dashdash@1.13.1
│ │ │ │       │ │   │ └── assert-plus@1.0.0 
│ │ │ │       │ │   └─┬ getpass@0.1.6 
│ │ │ │       │ │     └── assert-plus@1.0.0 
│ │ │ │       │ ├── is-typedarray@1.0.0 
│ │ │ │       │ ├── isstream@0.1.2 
│ │ │ │       │ ├── json-stringify-safe@5.0.1 
│ │ │ │       │ ├─┬ mime-types@2.1.11 
│ │ │ │       │ │ └── mime-db@1.23.0 
│ │ │ │       │ ├── node-uuid@1.4.7 
│ │ │ │       │ ├── oauth-sign@0.8.2 
│ │ │ │       │ ├── qs@6.1.0 
│ │ │ │       │ ├── stringstream@0.0.5 
│ │ │ │       │ ├── tough-cookie@2.2.2 
│ │ │ │       │ └── tunnel-agent@0.4.3 
│ │ │ │       ├─┬ rimraf@2.5.2
│ │ │ │       │ └─┬ glob@7.0.3
│ │ │ │       │   ├─┬ minimatch@3.0.0
│ │ │ │       │   │ └─┬ brace-expansion@1.1.4
│ │ │ │       │   │   └── concat-map@0.0.1 
│ │ │ │       │   └── path-is-absolute@1.0.0 
│ │ │ │       ├─┬ tar@2.2.1 
│ │ │ │       │ ├── block-stream@0.0.9 
│ │ │ │       │ └── inherits@2.0.1 
│ │ │ │       └─┬ tar-pack@3.1.3
│ │ │ │         ├─┬ debug@2.2.0 
│ │ │ │         │ └── ms@0.7.1 
│ │ │ │         ├── once@1.3.3 
│ │ │ │         └─┬ readable-stream@2.0.6 
│ │ │ │           ├── core-util-is@1.0.2 
│ │ │ │           ├── isarray@1.0.0 
│ │ │ │           ├── process-nextick-args@1.0.7 
│ │ │ │           ├── string_decoder@0.10.31 
│ │ │ │           └── util-deprecate@1.0.2 
│ │ │ ├─┬ pouchdb-bulkdocs-wrapper@1.0.2 
│ │ │ │ └─┬ pouchdb-promise@0.0.0 
│ │ │ │   ├── bluebird@1.2.4 
│ │ │ │   └── lie@2.7.7 
│ │ │ ├── pouchdb-plugin-error@1.0.1 
│ │ │ ├── pouchdb-promise@5.4.5 
│ │ │ ├─┬ pouchdb-req-http-query@1.0.3 
│ │ │ │ ├─┬ pouchdb-promise@0.0.0 
│ │ │ │ │ ├── bluebird@1.2.4 
│ │ │ │ │ └── lie@2.7.7 
│ │ │ │ └─┬ xmlhttprequest-cookie@0.9.4 
│ │ │ │   └── xmlhttprequest@1.8.0 
│ │ │ ├── pouchdb-system-db@1.0.4 
│ │ │ ├── promise-nodify@1.0.2 
│ │ │ └── secure-random@1.1.1 
│ │ ├─┬ pouchdb-find@0.1.0 
│ │ │ ├─┬ jshint@2.9.2 
│ │ │ │ ├─┬ cli@0.6.6 
│ │ │ │ │ └─┬ glob@3.2.11 
│ │ │ │ │   └─┬ minimatch@0.3.0 
│ │ │ │ │     ├── lru-cache@2.7.3 
│ │ │ │ │     └── sigmund@1.0.1 
│ │ │ │ ├─┬ console-browserify@1.1.0 
│ │ │ │ │ └── date-now@0.1.4 
│ │ │ │ ├── exit@0.1.2 
│ │ │ │ ├─┬ htmlparser2@3.8.3 
│ │ │ │ │ ├── domelementtype@1.3.0 
│ │ │ │ │ ├── domhandler@2.3.0 
│ │ │ │ │ ├─┬ domutils@1.5.1 
│ │ │ │ │ │ └─┬ dom-serializer@0.1.0 
│ │ │ │ │ │   ├── domelementtype@1.1.3 
│ │ │ │ │ │   └── entities@1.1.1 
│ │ │ │ │ └── entities@1.0.0 
│ │ │ │ ├── lodash@3.7.0 
│ │ │ │ ├─┬ minimatch@2.0.10 
│ │ │ │ │ └─┬ brace-expansion@1.1.6 
│ │ │ │ │   ├── balanced-match@0.4.2 
│ │ │ │ │   └── concat-map@0.0.1 
│ │ │ │ └── shelljs@0.3.0 
│ │ │ ├── lie@2.9.1 
│ │ │ ├─┬ pouchdb-abstract-mapreduce@0.2.2 
│ │ │ │ ├── lie@2.9.1 
│ │ │ │ └── spark-md5@0.0.5 
│ │ │ ├── pouchdb-collate@1.2.0 
│ │ │ ├── pouchdb-extend@0.1.2 
│ │ │ ├─┬ pouchdb-upsert@1.1.3 
│ │ │ │ └── lie@2.9.1 
│ │ │ └── spark-md5@0.0.5 
│ │ ├─┬ pouchdb-list@1.1.0 
│ │ │ ├─┬ couchdb-objects@1.0.7 
│ │ │ │ ├── is-empty@0.0.1 
│ │ │ │ └─┬ pouchdb-promise@0.0.0 
│ │ │ │   ├── bluebird@1.2.4 
│ │ │ │   └── lie@2.7.7 
│ │ │ ├── couchdb-render@1.0.1 
│ │ │ ├── extend@3.0.0 
│ │ │ └─┬ pouchdb-promise@0.0.0 
│ │ │   ├── bluebird@1.2.4 
│ │ │   └── lie@2.7.7 
│ │ ├─┬ pouchdb-replicator@2.1.3 
│ │ │ ├─┬ equals@1.0.5 
│ │ │ │ └── jkroso-type@1.1.1 
│ │ │ ├─┬ pouchdb-promise@0.0.0 
│ │ │ │ ├── bluebird@1.2.4 
│ │ │ │ └── lie@2.7.7 
│ │ │ └── random-uuid-v4@0.0.4 
│ │ ├─┬ pouchdb-rewrite@1.0.7 
│ │ │ └── pouchdb-route@1.0.3 
│ │ ├─┬ pouchdb-security@1.2.6 
│ │ │ ├── pouchdb-changeslike-wrapper@1.0.1 
│ │ │ └─┬ pouchdb-promise@0.0.0 
│ │ │   ├── bluebird@1.2.4 
│ │ │   └── lie@2.7.7 
│ │ ├─┬ pouchdb-show@1.0.8 
│ │ │ └─┬ pouchdb-promise@0.0.0 
│ │ │   ├── bluebird@1.2.4 
│ │ │   └── lie@2.7.7 
│ │ ├─┬ pouchdb-size@1.2.2 
│ │ │ ├── bluebird@2.10.2 
│ │ │ └─┬ get-folder-size@0.1.1 
│ │ │   ├── async@0.9.2 
│ │ │   └── minimist@0.1.0 
│ │ ├─┬ pouchdb-update@1.0.8 
│ │ │ ├── couchdb-eval@1.0.6 
│ │ │ ├── couchdb-resp-completer@1.0.3 
│ │ │ └─┬ pouchdb-promise@0.0.0 
│ │ │   ├── bluebird@1.2.4 
│ │ │   └── lie@2.7.7 
│ │ ├─┬ pouchdb-validation@1.2.1 
│ │ │ └─┬ pouchdb-promise@0.0.0 
│ │ │   ├── bluebird@1.2.4 
│ │ │   └── lie@2.7.7 
│ │ ├── pouchdb-vhost@1.0.2 
│ │ ├── pouchdb-wrappers@1.3.6 
│ │ └─┬ raw-body@2.1.6 
│ │   └── bytes@2.3.0 
│ ├── forever-agent@0.6.1 
│ ├── js-extend@1.0.1 
│ ├─┬ jsdoc@3.3.3
│ │ ├── async@0.9.2 
│ │ ├── escape-string-regexp@1.0.5 
│ │ └── strip-json-comments@1.0.4 
│ ├─┬ lie@3.0.4 
│ │ ├─┬ es3ify@0.2.2 
│ │ │ ├── esprima@2.7.2 
│ │ │ ├─┬ jstransform@11.0.3 
│ │ │ │ ├── base62@1.1.1 
│ │ │ │ ├─┬ commoner@0.10.4 
│ │ │ │ │ ├─┬ detective@4.3.1 
│ │ │ │ │ │ └── defined@1.0.0 
│ │ │ │ │ ├─┬ glob@5.0.15 
│ │ │ │ │ │ ├── inflight@1.0.5 
│ │ │ │ │ │ ├── minimatch@3.0.3 
│ │ │ │ │ │ └── path-is-absolute@1.0.0 
│ │ │ │ │ ├── graceful-fs@4.1.5 
│ │ │ │ │ ├─┬ mkdirp@0.5.1 
│ │ │ │ │ │ └── minimist@0.0.8 
│ │ │ │ │ └── q@1.4.1 
│ │ │ │ ├── esprima-fb@15001.1.0-dev-harmony-fb 
│ │ │ │ ├── object-assign@2.1.1 
│ │ │ │ └─┬ source-map@0.4.4 
│ │ │ │   └── amdefine@1.0.0 
│ │ │ └── through@2.3.8 
│ │ ├── immediate@3.0.6 
│ │ ├─┬ inline-process-browser@1.0.0 
│ │ │ ├─┬ falafel@1.2.0 
│ │ │ │ ├── acorn@1.2.2 
│ │ │ │ ├── foreach@2.0.5 
│ │ │ │ └── object-keys@1.0.11 
│ │ │ └─┬ through2@0.6.5 
│ │ │   └── readable-stream@1.0.34 
│ │ └─┬ unreachable-branch-transform@0.3.0 
│ │   ├── esmangle-evaluator@1.0.1 
│ │   └─┬ recast@0.10.43 
│ │     ├── ast-types@0.8.15 
│ │     ├── esprima-fb@15001.1001.0-dev-harmony-fb 
│ │     ├── private@0.1.6 
│ │     └── source-map@0.5.6 
│ ├── long@3.0.3 
│ ├─┬ multiplex@6.7.0 
│ │ ├─┬ duplexify@3.4.5 
│ │ │ ├─┬ end-of-stream@1.0.0 
│ │ │ │ └─┬ once@1.3.3 
│ │ │ │   └── wrappy@1.0.2 
│ │ │ ├─┬ readable-stream@2.1.4 
│ │ │ │ └── isarray@1.0.0 
│ │ │ └── stream-shift@1.0.0 
│ │ ├── inherits@2.0.1 
│ │ ├─┬ readable-stream@2.1.4 
│ │ │ ├── buffer-shims@1.0.0 
│ │ │ ├── core-util-is@1.0.2 
│ │ │ ├── isarray@1.0.0 
│ │ │ ├── process-nextick-args@1.0.7 
│ │ │ ├── string_decoder@0.10.31 
│ │ │ └── util-deprecate@1.0.2 
│ │ ├── varint@4.0.1 
│ │ └── xtend@4.0.1 
│ ├── node-ssdp@2.6.5  (git://github.com/thaliproject/node-ssdp.git#fcc5d403f6cc5e667572fba059332908c3cc822e)
│ ├── node-uuid@1.4.7 
│ ├─┬ request@2.64.0 
│ │ ├── aws-sign2@0.5.0 
│ │ ├─┬ bl@1.0.3 
│ │ │ └─┬ readable-stream@2.0.6 
│ │ │   └── isarray@1.0.0 
│ │ ├── caseless@0.11.0 
│ │ ├─┬ combined-stream@1.0.5 
│ │ │ └── delayed-stream@1.0.0 
│ │ ├── extend@3.0.0 
│ │ ├─┬ form-data@1.0.0-rc4 
│ │ │ └── async@1.5.2 
│ │ ├─┬ har-validator@1.8.0 
│ │ │ ├── bluebird@2.10.2 
│ │ │ ├─┬ chalk@1.1.3 
│ │ │ │ ├── ansi-styles@2.2.1 
│ │ │ │ ├─┬ has-ansi@2.0.0 
│ │ │ │ │ └── ansi-regex@2.0.0 
│ │ │ │ ├── strip-ansi@3.0.1 
│ │ │ │ └── supports-color@2.0.0 
│ │ │ ├─┬ commander@2.9.0 
│ │ │ │ └── graceful-readlink@1.0.1 
│ │ │ └─┬ is-my-json-valid@2.13.1 
│ │ │   ├── generate-function@2.0.0 
│ │ │   ├─┬ generate-object-property@1.2.0 
│ │ │   │ └── is-property@1.0.2 
│ │ │   └── jsonpointer@2.0.0 
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
│ │ ├─┬ mime-types@2.1.11 
│ │ │ └── mime-db@1.23.0 
│ │ ├── oauth-sign@0.8.2 
│ │ ├── qs@5.1.0 
│ │ ├── stringstream@0.0.5 
│ │ ├── tough-cookie@2.2.2 
│ │ └── tunnel-agent@0.4.3 
│ ├─┬ salti@0.2.0  (git+https://github.com/thaliproject/salti.git#2dadb4413347200a22e2fa3faff4dfc37bf1e214)
│ │ ├── jsonschema@1.1.0 
│ │ └── object-assign@4.1.0 
│ └── urlsafe-base64@1.0.0 
├─┬ tmp@0.0.28 
│ └── os-tmpdir@1.0.1 
├── urlsafe-base64@1.0.0 
└── uuid@2.0.0 


> thali-cordova-plugin-jxcore@1.0.0 test /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore
> jx runTests.js

Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreateNativeListener.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBGenerator.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPromiseQueue.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testTests.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManager.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManagerCoordinated.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNative.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotification.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationAction.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationBeacons.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationClient.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationLocal.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationServer.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerAction.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerDictionary.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationUtilities.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliTcpServersManager.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
TAP version 13
# setup
# calling createNativeListener directly rejects
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50017
ok 1 Should throw
# teardown
# setup
# emits incomingConnectionState
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50019
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 2 initial connection state should be CONNECTED
DEBUG createNativeListener: incoming socket close
ok 3 final connection state should be DISCONNECTED
# teardown
# setup
# emits routerPortConnectionFailed
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50022
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: 
ok 4 tried to connect to right port
ok 5 failed due to refused connection
ok 6 routerPortConnectionFailed is emitted
# teardown
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: incoming socket close
# setup
# native server connections all up
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50026
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
ok 7 Send/recvd #1 should be equal length
ok 8 Send/recvd #1 should be same
ok 9 Send/recvd #2 should be equal length
ok 10 Send/recvd #2 should be same
ok 11 Should be exactly 2 client sockets
# teardown
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: incoming socket close
# setup
# native server - closing incoming stream cleans outgoing socket
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50031
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: stream close:
ok 12 socket shouldn't close until after stream
ok 13 incoming remains open
# teardown
DEBUG createNativeListener: mux close
DEBUG createNativeListener: incoming socket close
# setup
# native server - closing incoming connection cleans outgoing socket
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50035
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 14 we should not have gotten an error
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: incoming socket close
ok 15 socket shouldn't close until after incoming
ok 16 incoming is cleaned up
# teardown
# setup
# native server - closing outgoing socket cleans associated mux stream
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50039
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: stream close:
ok 17 stream was closed
ok 18 incoming should survive
ok 19 mux should have no streams
# teardown
DEBUG createNativeListener: mux close
DEBUG createNativeListener: incoming socket close
# setup
# native server - closing the whole server cleans everything up
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50043
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 20 we should not have gotten an error
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
ok 21 Buffers are identical
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
ok 22 native server is nulled out
ok 23 native server should be closed
ok 24 incoming has been removed
ok 25 Incoming should be done
ok 26 The mux object should be closed
ok 27 The mux stream should be closed
DEBUG createNativeListener: incoming socket close
# teardown
# setup
# native server - we can get a ton of connections and data through and still clean up the server completely
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50047
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
ok 28 native server is nulled out
ok 29 native server should be closed
ok 30 incoming has been removed
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
# teardown
# setup
# native server - simulate mux failure, make sure everything is cleaned up
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50099
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 31 we should not have gotten an error
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
ok 32 Buffers are identical
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: incoming socket close
ok 33 server should be fine
ok 34 server should be open
ok 35 incoming has been removed
ok 36 The mux object should be closed
ok 37 The mux stream should be closed
# teardown
# setup
# native server - timing out the incoming connection cleans everything up
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50103
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 38 we should not have gotten an error
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
ok 39 Buffers are identical
DEBUG createNativeListener: incoming socket timeout
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: incoming socket close
ok 40 server should be fine
ok 41 server should be open
ok 42 incoming has been removed
ok 43 The mux object should be closed
ok 44 The mux stream should be closed
# teardown
# setup
# calling createPeerListener without calling start produces error
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50108
# teardown
# setup
# calling createPeerListener after calling stop produces error
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50111
# teardown
# setup
# can call createPeerListener (pleaseConnect === false)
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50114
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: listening 50115
DEBUG createPeerListener: pleaseConnect= false
ok 45 port must be in range
# teardown
# setup
# calling createPeerListener (pleaseConnect === true) with unknown peer is error
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50118
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: listening 50119
DEBUG createPeerListener: pleaseConnect= true
DEBUG createPeerListener: first connection
WARN createPeerListener: 
DEBUG createPeerListener: failedConnection
DEBUG createPeerListener: Recreating listener
DEBUG createPeerListener: createPeerListener creating new server
ok 46 should get error
DEBUG createPeerListener: listening 50120
DEBUG createPeerListener: pleaseConnect= false
# teardown
# setup
# calling createPeerListener twice with same peerIdentifier should return the same port
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50123
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: listening 50124
DEBUG createPeerListener: pleaseConnect= false
ok 47 port values should be the same
# teardown
# setup
# createPeerListener - closing connection to native listener closes everything and triggers new listener
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50127
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: listening 50128
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: first connection
DEBUG createPeerListener: forward connection
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
ok 48 Data should be of same length and content
DEBUG createNativeListener: incoming socket close
DEBUG createPeerListener: Recreating listener
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: listening 50133
DEBUG createPeerListener: pleaseConnect= false
ok 49 same peer ID
ok 50 different ports
DEBUG createNativeListener: stream close:
# teardown
# setup
# createPeerListener - closing mux closes listener and triggers a new listener
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50136
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: listening 50137
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: first connection
DEBUG createPeerListener: forward connection
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
ok 51 Data should be of same length and content
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: incoming socket close
DEBUG createPeerListener: Recreating listener
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: listening 50142
DEBUG createPeerListener: pleaseConnect= false
ok 52 same peer ID
ok 53 different ports
# teardown
# setup
# peerListener - forwardConnection, pleaseConnect === true - no native server
DEBUG createNativeListener: creating native server
ok 54 Can call startUpdateAdvertisingAndListening without error
ok 55 Can call startListeningForAdvertisements without error
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createNativeListener: listening 50145
DEBUG createPeerListener: listening 50146
DEBUG createPeerListener: pleaseConnect= true
DEBUG createPeerListener: first connection
DEBUG createPeerListener: forward connection
WARN createPeerListener: 
ok 56 reason should be as expected
DEBUG createPeerListener: Recreating listener
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: listening 50148
DEBUG createPeerListener: pleaseConnect= false
# teardown
# setup
# peerListener - forwardConnection, pleaseConnect === false - no native server
DEBUG createNativeListener: creating native server
ok 57 Can call startUpdateAdvertisingAndListening without error
ok 58 Can call startListeningForAdvertisements without error
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createNativeListener: listening 50151
DEBUG createPeerListener: listening 50152
DEBUG createPeerListener: pleaseConnect= false
ok 59 peerPort should not be nativePort
DEBUG createPeerListener: first connection
DEBUG createPeerListener: forward connection
WARN createPeerListener: 
ok 60 Should not get event until connection is made
ok 61 reason should be as expected
DEBUG createPeerListener: Recreating listener
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: failed incoming connection because of mux promise failure - undefined
DEBUG createPeerListener: listening 50155
DEBUG createPeerListener: pleaseConnect= false
# teardown
# setup
# peerListener - forwardConnection, pleaseConnect === true - with native server
DEBUG createNativeListener: creating native server
ok 62 Can call startUpdateAdvertisingAndListening without error
ok 63 Can call startListeningForAdvertisements without error
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createNativeListener: listening 50158
DEBUG createPeerListener: listening 50159
DEBUG createPeerListener: pleaseConnect= true
DEBUG createPeerListener: first connection
DEBUG createPeerListener: forward connection
ok 64 Should get spontaneous connection
ok 65 peerPort != nativePort
# teardown
# setup
# peerListener - forwardConnection, pleaseConnect === false - with native server
DEBUG createNativeListener: creating native server
ok 66 Can call startUpdateAdvertisingAndListening without error
ok 67 Can call startListeningForAdvertisements without error
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createNativeListener: listening 50163
DEBUG createPeerListener: listening 50164
DEBUG createPeerListener: pleaseConnect= false
ok 68 peerPort != nativePort
DEBUG createPeerListener: first connection
DEBUG createPeerListener: forward connection
ok 69 Should not get unexpected connection
# teardown
# setup
# peerListener - forwardConnection, pleaseConnect === false - with native server and data transfer
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50169
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: listening 50170
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: first connection
DEBUG createPeerListener: forward connection
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
ok 70 Data should be of same length and content
ok 71 Data should be of same length and content
# teardown
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: incoming socket close
WARN createPeerListener: 
DEBUG createPeerListener: Got error on outgoing to native - Error: read ECONNRESET
# setup
# createPeerListener is idempotent
DEBUG createNativeListener: creating native server
ok 72 Can call startUpdateAdvertisingAndListening without error
ok 73 Can call startListeningForAdvertisements without error
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createNativeListener: listening 50176
DEBUG createPeerListener: listening 50177
DEBUG createPeerListener: pleaseConnect= false
ok 74 Second call to existing peerListener returns existing port
# teardown
# setup
# createPeerListener - pleaseConnect === true, failed connection rejects promise
DEBUG createNativeListener: creating native server
ok 75 Can call startUpdateAdvertisingAndListening without error
ok 76 Can call startListeningForAdvertisements without error
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createNativeListener: listening 50180
DEBUG createPeerListener: listening 50181
DEBUG createPeerListener: pleaseConnect= true
DEBUG createPeerListener: first connection
WARN createPeerListener: 
DEBUG createPeerListener: failedConnection
ok 77 got our failed connection
DEBUG createPeerListener: Recreating listener
ok 78 failed connection should reject with error
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: listening 50182
DEBUG createPeerListener: pleaseConnect= false
# teardown
# setup
# createPeerListener - pleaseConnect === true, connection resolves promise
DEBUG createNativeListener: creating native server
ok 79 Can call startUpdateAdvertisingAndListening without error
ok 80 Can call startListeningForAdvertisements without error
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createNativeListener: listening 50185
DEBUG createPeerListener: listening 50186
DEBUG createPeerListener: pleaseConnect= true
DEBUG createPeerListener: first connection
DEBUG createPeerListener: forward connection
ok 81 Should get spontaneous connection
ok 82 promise should resolve
# teardown
# setup
# peerListener - reverseConnection, pleaseConnect === true
DEBUG createNativeListener: creating native server
ok 83 Can call startUpdateAdvertisingAndListening without error
ok 84 Can call startListeningForAdvertisements without error
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createNativeListener: listening 50190
DEBUG createPeerListener: listening 50191
DEBUG createPeerListener: pleaseConnect= true
DEBUG createPeerListener: first connection
WARN createPeerListener: was expecting a forward connection to be made
ok 85 reason should be as expected
DEBUG createPeerListener: Recreating listener
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: listening 50192
DEBUG createPeerListener: pleaseConnect= false
# teardown
# setup
# peerListener - reverseConnection, pleaseConnect === false - no incoming
DEBUG createNativeListener: creating native server
ok 86 Can call startUpdateAdvertisingAndListening without error
ok 87 Can call startListeningForAdvertisements without error
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createNativeListener: listening 50195
DEBUG createPeerListener: listening 50196
DEBUG createPeerListener: pleaseConnect= false
ok 88 peerPort should not be nativePort
DEBUG createPeerListener: first connection
DEBUG createPeerListener: looking up mux for client port:  0
DEBUG createPeerListener: timed out waiting for incoming connection
DEBUG createPeerListener: reverse connection
DEBUG createPeerListener: looking up mux for client port:  0
DEBUG createPeerListener: no mux found
ok 89 should not get event until connection is made
ok 90 reason should be as expected
DEBUG createPeerListener: Recreating listener
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: failed incoming connection because of mux promise failure - AssertionError: server._mux must exist by now
DEBUG createPeerListener: listening 50198
DEBUG createPeerListener: pleaseConnect= false
# teardown
# setup
# peerListener - reverseConnection, pleaseConnect === false - with incoming
DEBUG createNativeListener: creating native server
ok 91 Can call startUpdateAdvertisingAndListening without error
ok 92 Can call startListeningForAdvertisements without error
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createNativeListener: listening 50201
DEBUG createPeerListener: listening 50202
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: first connection
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createPeerListener: looking up mux for client port:  50204
DEBUG createPeerListener: reverse connection
DEBUG createPeerListener: looking up mux for client port:  50204
ok 93 sent and received should be the same
# teardown
DEBUG createNativeListener: mux close
DEBUG createNativeListener: incoming socket close
# setup
# peerListener - reverseConnection, pleaseConnect === false - no server
DEBUG createNativeListener: creating native server
ok 94 Can call startUpdateAdvertisingAndListening without error
ok 95 Can call startListeningForAdvertisements without error
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createNativeListener: listening 50207
DEBUG createPeerListener: listening 50208
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: first connection
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createPeerListener: looking up mux for client port:  50210
DEBUG createPeerListener: reverse connection
DEBUG createPeerListener: looking up mux for client port:  50210
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: 
ok 96 should get routerPortConnectionFailed
DEBUG createNativeListener: stream close:
# teardown
DEBUG createNativeListener: mux close
DEBUG createNativeListener: incoming socket close
# setup
# createPeerListener - ask for new peer when we are at maximum and make sure we remove the right existing listener
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50214
# teardown
# setup
# createPeerListener - ask for a new peer when we are not at maximum peers and make sure we do not remove any existing listeners
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50217
# teardown
# setup
# createPeerListener - pleaseConnect = false - test timeout
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50220
# teardown
# setup
# createPeerListener - pleaseConnect = true - test timeout
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50223
# teardown
# setup
# createPeerListener - forward connection - wrong serverPort
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50226
# teardown
# setup
# createPeerListener - forward connection - wrong clientPort
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50229
# teardown
# setup
# createPeerListener - please connect = false, multiple connections out
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50232
# teardown
# setup
# createPeerListener - please connect = false, multiple bi-directional connections
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50235
# teardown
# setup
# createPeerListener - multiple parallel calls
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50238
# teardown
# setup
# #_doImmediateSeqUpdate - server is not there
DEBUG localSeqManager: Got an error trying to update seq {"status":400}
ok 97 Got right error
# teardown
# setup
# #_doImmediateSeqUpdate - server accepts & closes connection
DEBUG localSeqManager: Got an error trying to update seq {"status":400}
ok 98 Got socket hang up
# teardown
# setup
# #_doImmediateSeqUpdate - server always returns 500
DEBUG localSeqManager: Got an error trying to update seq {"status":500,"name":"unknown_error","message":"Database encountered an unknown error","error":true}
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
DEBUG localSeqManager: Got an error trying to update seq {"status":409,"name":"conflict","message":"Document update conflict","error":true,"reason":"Document update conflict","ok":true}
ok 110 Our rev is old so we should fail
# teardown
# setup
# #_doImmediateSeqUpdate - fail if stop is called
ok 111 confirm stop caused failure
# teardown
# setup
# #_doImmediateSeqUpdate - stop after get but before put fails right
DEBUG localSeqManager: Got an error trying to update seq {"onPut":true}
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
DEBUG localSeqManager: Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10
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
# test defaultDirectory
ok 134 should be equal
ok 135 should be equal
ok 136 should be equal
# teardown
# setup
# test defaultAdapter
ok 137 should be equal
ok 138 should be equal
ok 139 should be equal
ok 140 should be equal
ok 141 should be equal
ok 142 should be equal
ok 143 should be equal
ok 144 should be equal
# teardown
# setup
# enqueue and run in order
ok 145 firstPromise setTimeout
ok 146 firstPromise result
ok 147 firstPromise testValue
ok 148 secondPromise setTimeout
ok 149 secondPromise result
ok 150 secondPromise testValue
ok 151 thirdPromise in promise
ok 152 thirdPromise result
ok 153 thirdPromise testValue
# teardown
# setup
# enqueueAtTop and run backwards
ok 154 thirdPromise - first to run
ok 155 thirdPromise - in resolve
ok 156 secondPromise - second to run
ok 157 secondPromise - in catch
ok 158 firstPromise - third to run
ok 159 firstPromise - in then
ok 160 testing promises
# teardown
# setup
# mix enqueue and enqueueAtTop
ok 161 fourth
ok 162 fourth
ok 163 second
ok 164 secondPromise - in then
ok 165 first
ok 166 firstPromise - in catch
ok 167 third
ok 168 thirdPromise - in then
ok 169 testingPromises
# teardown
# setup
# queues handled independently
ok 170 all short operations completed before the long resolves
# teardown
# setup
# basic
ok 171 sane
# teardown
# setup
# another
ok 172 sane
# teardown
# setup
# test thali manager spies
DEBUG thaliManager: creating ThaliSendNotificationBasedOnReplication instance
DEBUG thaliManager: creating ThaliPullReplicationFromNotification instance
DEBUG thaliManager: creating express pouchdb instance
ok 173 expressPouchDB was called once
ok 174 expressPouchDB was called with 2 arguments
ok 175 expressPouchDB was called with 'PouchDB' as 1-st argument
ok 176 PouchDB was called once
ok 177 PouchDB was called with 1 arguments
ok 178 PouchDB was called with 'dbName' as 1-st argument
ok 179 ThaliSendNotificationBasedOnReplication was called once
ok 180 ThaliSendNotificationBasedOnReplication was called with 4 arguments
ok 181 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
ok 182 ThaliPullReplicationFromNotification was called once
ok 183 ThaliPullReplicationFromNotification was called with 4 arguments
ok 184 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
ok 185 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
ok 186 ThaliPullReplicationFromNotification was called with 'thaliPeerPoolInterface' as 3-st argument
ok 187 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
ok 188 ThaliMobile.stopAdvertisingAndListening was called once
ok 189 ThaliMobile.stopAdvertisingAndListening was called with 4 arguments
ok 190 ThaliMobile.stopAdvertisingAndListening was called with 'dbName' as 1-st argument
DEBUG thaliManager: starting thaliPullReplicationFromNotification
DEBUG thaliManager: starting ThaliMobile
DEBUG thaliMobileNativeWrapper: listening 50314
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50315
DEBUG thaliManager: start listening for advertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliManager: start update advertising and listening
DEBUG thaliWifiInfrastructure: listening 50316
DEBUG thaliWifiInfrastructure: listening 50318
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
DEBUG thaliManager: starting thaliSendNotificationBasedOnReplication
ok 191 ThaliMobile.start was called once
ok 192 ThaliMobile.start was called with 2 arguments
ok 193 ThaliMobile.startListeningForAdvertisements was called once
ok 194 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
ok 195 ThaliMobile.startUpdateAdvertisingAndListening was called once
ok 196 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
ok 197 ThaliSendNotificationBasedOnReplication.prototype.start was called once
ok 198 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
ok 199 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
ok 200 ThaliPullReplicationFromNotification.prototype.start was called once
ok 201 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
ok 202 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
DEBUG thaliManager: stopping thaliSendNotificationBasedOnReplication
DEBUG thaliManager: stopping advertising and listening
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliManager: stopping listening for advertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
DEBUG thaliManager: stopping ThaliMobile
DEBUG thaliManager: stopping thaliPullReplicationFromNotification
ok 203 ThaliMobile.stop was called once
ok 204 ThaliMobile.stop was called with 0 arguments
ok 205 ThaliMobile.stopListeningForAdvertisements was called once
ok 206 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
ok 207 ThaliMobile.stopAdvertisingAndListening was called once
ok 208 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
ok 209 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
ok 210 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
ok 211 ThaliPullReplicationFromNotification.prototype.stop was called once
ok 212 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
# teardown
# setup
# test thali manager multiple starts and stops
DEBUG thaliManager: creating ThaliSendNotificationBasedOnReplication instance
DEBUG thaliManager: creating ThaliPullReplicationFromNotification instance
DEBUG thaliManager: creating express pouchdb instance
ok 213 expressPouchDB was called once
ok 214 expressPouchDB was called with 2 arguments
ok 215 expressPouchDB was called with 'PouchDB' as 1-st argument
ok 216 PouchDB was called once
ok 217 PouchDB was called with 1 arguments
ok 218 PouchDB was called with 'dbName' as 1-st argument
ok 219 ThaliSendNotificationBasedOnReplication was called once
ok 220 ThaliSendNotificationBasedOnReplication was called with 4 arguments
ok 221 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
ok 222 ThaliPullReplicationFromNotification was called once
ok 223 ThaliPullReplicationFromNotification was called with 4 arguments
ok 224 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
ok 225 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
ok 226 ThaliPullReplicationFromNotification was called with 'thaliPeerPoolInterface' as 3-st argument
ok 227 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
ok 228 ThaliMobile.stopAdvertisingAndListening was called once
ok 229 ThaliMobile.stopAdvertisingAndListening was called with 4 arguments
ok 230 ThaliMobile.stopAdvertisingAndListening was called with 'dbName' as 1-st argument
DEBUG thaliManager: starting thaliPullReplicationFromNotification
DEBUG thaliManager: starting ThaliMobile
DEBUG thaliMobileNativeWrapper: listening 50319
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50320
DEBUG thaliManager: start listening for advertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliManager: start update advertising and listening
DEBUG thaliWifiInfrastructure: listening 50321
DEBUG thaliWifiInfrastructure: listening 50323
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
DEBUG thaliManager: starting thaliSendNotificationBasedOnReplication
ok 231 ThaliMobile.start was called once
ok 232 ThaliMobile.start was called with 2 arguments
ok 233 ThaliMobile.startListeningForAdvertisements was called once
ok 234 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
ok 235 ThaliMobile.startUpdateAdvertisingAndListening was called once
ok 236 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
ok 237 ThaliSendNotificationBasedOnReplication.prototype.start was called once
ok 238 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
ok 239 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
ok 240 ThaliPullReplicationFromNotification.prototype.start was called once
ok 241 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
ok 242 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
DEBUG thaliManager: stopping thaliSendNotificationBasedOnReplication
DEBUG thaliManager: stopping advertising and listening
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliManager: stopping listening for advertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
DEBUG thaliManager: stopping ThaliMobile
DEBUG thaliManager: stopping thaliPullReplicationFromNotification
ok 243 ThaliMobile.stop was called once
ok 244 ThaliMobile.stop was called with 0 arguments
ok 245 ThaliMobile.stopListeningForAdvertisements was called once
ok 246 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
ok 247 ThaliMobile.stopAdvertisingAndListening was called once
ok 248 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
ok 249 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
ok 250 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
ok 251 ThaliPullReplicationFromNotification.prototype.stop was called once
ok 252 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
DEBUG thaliManager: starting thaliPullReplicationFromNotification
DEBUG thaliManager: starting ThaliMobile
DEBUG thaliMobileNativeWrapper: listening 50324
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50325
DEBUG thaliManager: start listening for advertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliManager: start update advertising and listening
DEBUG thaliWifiInfrastructure: listening 50326
DEBUG thaliWifiInfrastructure: listening 50328
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
DEBUG thaliManager: starting thaliSendNotificationBasedOnReplication
DEBUG thaliManager: stopping thaliSendNotificationBasedOnReplication
DEBUG thaliManager: stopping advertising and listening
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliManager: stopping listening for advertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
DEBUG thaliManager: stopping ThaliMobile
DEBUG thaliManager: stopping thaliPullReplicationFromNotification
DEBUG thaliManager: starting thaliPullReplicationFromNotification
DEBUG thaliManager: starting ThaliMobile
DEBUG thaliMobileNativeWrapper: listening 50329
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50330
DEBUG thaliManager: start listening for advertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliManager: start update advertising and listening
DEBUG thaliWifiInfrastructure: listening 50331
DEBUG thaliWifiInfrastructure: listening 50333
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
DEBUG thaliManager: starting thaliSendNotificationBasedOnReplication
DEBUG thaliManager: stopping thaliSendNotificationBasedOnReplication
DEBUG thaliManager: stopping advertising and listening
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliManager: stopping listening for advertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
DEBUG thaliManager: stopping ThaliMobile
DEBUG thaliManager: stopping thaliPullReplicationFromNotification
# teardown
# setup
# #startListeningForAdvertisements should fail if start not called
ok 253 specific error should be returned
# teardown
ok 254 error should be null
ok 255 error should be null
# setup
# #startUpdateAdvertisingAndListening should fail if start not called
ok 256 specific error should be returned
# teardown
ok 257 error should be null
ok 258 error should be null
# setup
# should be able to call #stopListeningForAdvertisements many times
DEBUG thaliMobileNativeWrapper: listening 50334
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50335
ok 259 error should be null
ok 260 error should be null
ok 261 error should be null
ok 262 error should be null
# teardown
ok 263 error should be null
ok 264 error should be null
# setup
# should be able to call #startListeningForAdvertisements many times
DEBUG thaliMobileNativeWrapper: listening 50336
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50337
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 265 error should be null
ok 266 error should be null
ok 267 error should be null
ok 268 error should be null
# teardown
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 269 error should be null
ok 270 error should be null
# setup
# should be able to call #startUpdateAdvertisingAndListening many times
DEBUG thaliMobileNativeWrapper: listening 50338
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50339
DEBUG thaliWifiInfrastructure: listening 50340
DEBUG thaliWifiInfrastructure: listening 50342
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 271 error should be null
ok 272 error should be null
ok 273 error should be null
ok 274 error should be null
# teardown
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 275 error should be null
ok 276 error should be null
# setup
# should be able to call #stopAdvertisingAndListening many times
DEBUG thaliMobileNativeWrapper: listening 50343
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50344
ok 277 error should be null
ok 278 error should be null
ok 279 error should be null
ok 280 error should be null
# teardown
ok 281 error should be null
ok 282 error should be null
# setup
# #start should fail if called twice in a row
DEBUG thaliMobileNativeWrapper: listening 50345
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50346
ok 283 first call should succeed
ok 284 first call should succeed
ok 285 specific error should be returned
# teardown
ok 286 error should be null
ok 287 error should be null
# setup
# does not emit duplicate discoveryAdvertisingStateUpdate
DEBUG thaliMobileNativeWrapper: listening 50347
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50348
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliWifiInfrastructure: listening 50349
DEBUG thaliWifiInfrastructure: listening 50351
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 288 called only once
ok 289 discovery state matches
ok 290 advertising state matches
# teardown
INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 291 error should be null
ok 292 error should be null
# setup
# does not send duplicate availability changes
ok 293 should be called once
ok 294 should not have been called more than once
# teardown
ok 295 error should be null
ok 296 error should be null
# setup
# can get the network status
ok 297 network status should have certain non-empty properties
# teardown
ok 298 error should be null
ok 299 error should be null
# setup
# wifi peer is marked unavailable if announcements stop
ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
ok 300 host address should match
ok 301 port should match
ok 302 host address should be null
ok 303 port should should be null
# teardown
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 304 error should be null
ok 305 error should be null
# setup
# network changes emitted correctly
DEBUG thaliMobileNativeWrapper: listening 50352
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50353
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 306 wifi is off
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 307 wifi is on
# teardown
ok 308 error should be null
ok 309 error should be null
# setup
# network changes not emitted in stopped state
ok 310 event was not emitted
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
# teardown
ok 311 error should be null
ok 312 error should be null
# setup
# calls correct starts when network changes
DEBUG thaliMobileNativeWrapper: listening 50354
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50355
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 313 specific error expected
DEBUG thaliWifiInfrastructure: listening 50357
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 314 specific error expected
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":true,"advertisingActive":true}
DEBUG thaliWifiInfrastructure: listening 50358
ok 315 startListeningForAdvertisements should have been called
ok 316 startUpdateAdvertisingAndListening should have been called
# teardown
INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 317 error should be null
ok 318 error should be null
# setup
# peer is marked unavailable if port number changes
DEBUG thaliMobileNativeWrapper: listening 50359
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50360
ok 319 peer should have a non-empty identifier
ok 320 peer should have a non-empty host address
ok 321 peer should have port number
ok 322 peer should have suggested timeout
ok 323 peer should have a connection type
ok 324 connection type should match one of the pre-defined types
ok 325 peer should have a non-empty identifier
ok 326 host address should be null
ok 327 port number should be null
ok 328 peer should have suggested timeout
ok 329 peer should have a connection type
ok 330 connection type should match one of the pre-defined types
ok 331 port number must match
ok 332 peer should have a non-empty identifier
ok 333 peer should have a non-empty host address
ok 334 peer should have port number
ok 335 peer should have suggested timeout
ok 336 peer should have a connection type
ok 337 connection type should match one of the pre-defined types
# teardown
ok 338 error should be null
ok 339 error should be null
# setup
# when network connection is lost a peer should be marked unavailable
DEBUG thaliMobileNativeWrapper: listening 50361
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50362
INFO testUtils: Toggling radios to: false
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 340 peer should have a non-empty identifier
ok 341 host address should be null
ok 342 port number should be null
ok 343 peer should have suggested timeout
ok 344 peer should have a connection type
ok 345 connection type should match one of the pre-defined types
INFO testUtils: Toggling radios to: true
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
# teardown
ok 346 error should be null
ok 347 error should be null
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
# setup
# Can call start/stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 348 Can call startListeningForAdvertisements without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 349 Can call stopListeningForAdvertisements without error
# teardown
ok 350 Should be able to call stopListeningForAdvertisements in teardown
ok 351 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Calling startListeningForAdvertisements twice is NOT an error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 352 Can call startListeningForAdvertisements without error
ok 353 Can call startListeningForAdvertisements twice without error
# teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 354 Should be able to call stopListeningForAdvertisements in teardown
ok 355 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Calling stopListeningForAdvertisements without calling start is NOT an error
ok 356 Can call stopListeningForAdvertisements without error
ok 357 Can call stopListeningForAdvertisements without error
# teardown
ok 358 Should be able to call stopListeningForAdvertisements in teardown
ok 359 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Can call start/stopUpdateAdvertisingAndListening
DEBUG thaliWifiInfrastructure: listening 50364
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 360 Can call startUpdateAdvertisingAndListening without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 361 Can call stopAdvertisingAndListening without error
# teardown
ok 362 Should be able to call stopListeningForAdvertisements in teardown
ok 363 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Calling startUpdateAdvertisingAndListening twice is NOT an error
DEBUG thaliWifiInfrastructure: listening 50366
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 364 Can call startUpdateAdvertisingAndListening without error
ok 365 Can call startUpdateAdvertisingAndListening twice without error
# teardown
ok 366 Should be able to call stopListeningForAdvertisements in teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 367 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
ok 368 Can call startUpdateAdvertisingAndListening without error
ok 369 Can call stopAdvertisingAndListening without error
# teardown
ok 370 Should be able to call stopListeningForAdvertisements in teardown
ok 371 Should be able to call stopAdvertisingAndListening in teardown
# setup
# cannot call connect when start listening for advertisements is not active
ok 372 got right error
# teardown
ok 373 Should be able to call stopListeningForAdvertisements in teardown
ok 374 Should be able to call stopAdvertisingAndListening in teardown
# setup
# #startListeningForAdvertisements should fail if start not called
ok 375 specific error should be returned
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 376 must be stopped
# setup
# #startUpdateAdvertisingAndListening should fail if start not called
ok 377 specific error should be returned
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 378 must be stopped
# setup
# should be able to call #stopListeningForAdvertisements many times
DEBUG thaliMobileNativeWrapper: listening 50367
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50368
ok 379 no errors
ok 380 still no errors
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 381 must be stopped
# setup
# should be able to call #startListeningForAdvertisements many times
DEBUG thaliMobileNativeWrapper: listening 50369
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50370
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 382 no errors
ok 383 still no errors
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 384 must be stopped
# setup
# should be able to call #startUpdateAdvertisingAndListening many times
DEBUG thaliMobileNativeWrapper: listening 50371
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50372
DEBUG thaliWifiInfrastructure: listening 50374
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 385 no errors
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
ok 386 still no errors
# teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 387 must be stopped
# setup
# should be able to call #stopAdvertisingAndListening many times
DEBUG thaliMobileNativeWrapper: listening 50375
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50376
ok 388 no errors
ok 389 still no errors
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 390 must be stopped
# setup
# can get the network status before starting
ok 391 network status should have certain non-empty properties
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 392 must be stopped
# setup
# error returned with bad router
ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
ok 393 specific error expected
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 394 must be stopped
# setup
# all services are stopped when we call stop
DEBUG thaliMobileNativeWrapper: listening 50377
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50378
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliWifiInfrastructure: listening 50380
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 395 connection to servers manager should succeed after starting
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
ok 396 connection to router server should succeed after starting
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG createNativeListener: incoming socket close
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 397 is stopped after calling stop
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
ok 398 connection to servers manager should fail after stopping
ok 399 connection to router server should fail after stopping
# teardown
ok 400 must be stopped
# setup
# make sure terminateConnection is properly hooked up
ok 401 called with right arguments
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 402 must be stopped
# setup
# make sure terminateListener is properly hooked up
ok 403 called with right arguments
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 404 must be stopped
# setup
# make sure we actually call kill connections properly
ok 405 specific error expected
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 406 must be stopped
# setup
# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
DEBUG thaliMobileNativeWrapper: listening 50385
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50386
INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":50385,"error":{}}
ok 407 failure reason is as expected
ok 408 error description is as expected
ok 409 must be stopped
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 410 must be stopped
# setup
# We repeat failedConnection event when we get it from thaliTcpServersManager
DEBUG thaliMobileNativeWrapper: listening 50387
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50388
ok 411 peerIdentifier matches
ok 412 error description matches
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 413 must be stopped
# setup
# can do HTTP requests between peers without coordinator
DEBUG thaliMobileNativeWrapper: listening 50389
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50390
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliWifiInfrastructure: listening 50392
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: listening 50393
DEBUG createPeerListener: pleaseConnect= false
DEBUG testUtils: We got a peer {"peerIdentifier":"foo","portNumber":50393,"hostAddress":"127.0.0.1"}
WARN testUtils: Retry count for getSamePeerWithRetry is 1
DEBUG createPeerListener: first connection
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG wifiBasedNativeMock: proxy socket connected
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
DEBUG createPeerListener: forward connection
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
ok 414 Should only get expected id
ok 415 response body should match testData
# teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
ok 416 must be stopped
DEBUG createNativeListener: incoming socket close
# setup
# make sure bad PSK connections fail
ok 417 FIX ME, PLEASE!!!
# teardown
ok 418 must be stopped
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# setup
# peer changes handled from a queue
DEBUG thaliMobileNativeWrapper: listening 50400
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50401
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: listening 50402
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: listening 50403
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: listening 50404
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: listening 50405
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: listening 50406
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: listening 50407
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: listening 50408
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: listening 50409
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: listening 50410
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: listening 50411
DEBUG createPeerListener: pleaseConnect= false
ok 419 peers were handled in the right order
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 420 must be stopped
# setup
# relaying discoveryAdvertisingStateUpdateNonTCP
DEBUG thaliMobileNativeWrapper: listening 50412
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50413
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 421 discovery is active
ok 422 advertising is active
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 423 must be stopped
# setup
# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
DEBUG thaliMobileNativeWrapper: listening 50414
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50415
DEBUG thaliWifiInfrastructure: listening 50417
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: 50415
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 424 right error reason
ok 425 Stop should be fine
ok 426 same port
ok 427 we should be off
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 428 must be stopped
# setup
# we successfully receive and replay discoveryAdvertisingStateUpdate
DEBUG thaliMobileNativeWrapper: listening 50418
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50419
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 429 discoveryActive matches
ok 430 advertisingActive matches
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 431 discoveryActive matches
ok 432 advertisingActive matches
DEBUG thaliMobileNativeWrapper: listening 50420
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50421
DEBUG thaliWifiInfrastructure: listening 50423
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 433 discoveryActive matches
ok 434 advertisingActive matches
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 435 discoveryActive matches
ok 436 advertisingActive matches
DEBUG thaliMobileNativeWrapper: listening 50424
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50425
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 437 must be stopped
# setup
# Test BEACONS_RETRIEVED_AND_PARSED locally
ok 438 peerIdentifier should be identifier
ok 439 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 440 good beacon
ok 441 good preAmble
ok 442 public keys match!
ok 443 must return null after successful call
ok 444 Once start returns the action should be in KILLED state
# teardown
# setup
# Test HTTP_BAD_RESPONSE locally
ok 445 Response should be HTTP_BAD_RESPONSE
ok 446 must return null after successful call
# teardown
# setup
# Test NETWORK_PROBLEM locally
ok 447 Response should be NETWORK_PROBLEM
ok 448 reject reason should be: Could not establish TCP connection
# teardown
# setup
# Call the start two times
ok 449 Call start once
ok 450 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 451 must return null after successful call.
# teardown
# setup
# Call the kill before calling the start
ok 452 Should be Killed
ok 453 Start after killed
# teardown
# setup
# Call the kill immediately after the start
ok 454 Should be KILLED
ok 455 must return null after successful kill
# teardown
# setup
# Call the kill while waiting a response from the server
ok 456 Should be KILLED
ok 457 must return null after successful kill
# teardown
# setup
# Test to exceed the max content size locally
ok 458 HTTP_BAD_RESPONSE should be response when content size is exceeded
ok 459 must return null after successful call
# teardown
# setup
# Close the server socket while the client is waiting a response from the server. Local test.
ok 460 Should be NETWORK_PROBLEM caused closing server socket
ok 461 Should be Could not establish TCP connection
# teardown
# setup
# Close the client socket while the client is waiting a response from the server. Local test.
ok 462 Should be NETWORK_PROBLEM caused closing client socket
ok 463 Should be Could not establish TCP connection
# teardown
# setup
# #generatePreambleAndBeacons bad args
ok 464 publicKeysToNotify cannot be null
ok 465 ecdh for local device cannot be null
ok 466 milliseconds cannot be less than 0
ok 467 milliseconds cannot be 0
ok 468 milliseconds cannot be greater than one_day
# teardown
# setup
# #generatePreambleAndBeacons empty keys to notify
ok 469 should be equal
# teardown
# setup
# #generatePreambleAndBeacons multiple keys to notify
ok 470 should be equal
ok 471 should be equal
ok 472 (unnamed assert)
ok 473 should be equal
# teardown
# setup
# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
ok 474 should throw
# teardown
# setup
# #parseBeacons invalid expiration in beaconStreamWithPreAmble
ok 475 Preamble expiration must be a 64 bit integer
# teardown
# setup
# #parseBeacons expiration out of range lower
ok 476 Expiration out of range
# teardown
# setup
# #parseBeacons expiration out of range lower
ok 477 Expiration out of range
# teardown
# setup
# #parseBeacons no beacons returns null
ok 478 should be equal
# teardown
# setup
# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
ok 479 Malformed encrypted beacon key ID
# teardown
# setup
# #parseBeacons addressBookCallback fails decrypt
ok 480 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns no matches
ok 481 should be equal
ok 482 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns spurious match
ok 483 should be equal
ok 484 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns public key
ok 485 right number of calls to address book
ok 486 good preAmble
ok 487 good unencryptedKeyId
ok 488 good beacon
# teardown
# setup
# validate generatePskIdentityField
ok 489 decoded buffers match
# teardown
# setup
# validate generatePskSecret
ok 490 secrets match
# teardown
# setup
# validate generatePskSecrets
ok 491 Matching numbers
ok 492 We have an entry!
ok 493 keys match
ok 494 secrets match
ok 495 We have an entry!
ok 496 keys match
ok 497 secrets match
ok 498 We have an entry!
ok 499 keys match
ok 500 secrets match
# teardown
# setup
# validate generateBeaconStreamAndSecrets
ok 501 Streams have same length
ok 502 matching size
ok 503 keys match
ok 504 secrets match
# teardown
# setup
# Add two Peers.
ok 505 should be equal
ok 506 should be equal
ok 507 should be equal
ok 508 should be equal
ok 509 should be equal
# teardown
# setup
# TCP_NATIVE peer loses DNS
ok 510 should be equal
ok 511 should be equal
# teardown
# setup
# Received beacons with no values for us
ok 512 entry exists
ok 513 entry is resolved
# teardown
# setup
# Resolves an action locally
ok 514 Host address must match
ok 515 suggestedTCPTimeout must match
ok 516 connectionType must match
ok 517 portNumber must match
# teardown
# setup
# Resolves an action locally using ThaliPeerPoolDefault
ok 518 Host address must match
ok 519 suggestedTCPTimeout must match
ok 520 connectionType must match
ok 521 portNumber must match
# teardown
# setup
# Action fails because of a bad hostname.
ok 522 should be equal
ok 523 should be equal
ok 524 should be equal
# teardown
# setup
# hostaddress is removed when the action is running. 
ok 525 should be equal
# teardown
# setup
# Client to server request locally
ok 526 secrets are equal
ok 527 Public key matches with the server key
ok 528 Host address must match
ok 529 suggestedTCPTimeout must match
ok 530 connectionType must match
ok 531 portNumber must match
# teardown
# setup
# Test ThaliPskMapCache clean and expiration
ok 532 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
ok 533 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
ok 534 All entries should be expired after 1 second
# teardown
# setup
# Test ThaliPskMapCache getSecret and getPublic
ok 535 All keys need to be available in the cache
ok 536 All entries should be expired after 1 second
# teardown
# setup
# Test ThaliPskMapCache multiple entries
ok 537 Size of the cache should be 2
ok 538 Cache doesn't contain dictionary1
ok 539 Size of the cache should be 1
ok 540 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
# setup
# Start and stop ThaliNotificationServer
ok 541 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
ok 542 ThaliMobile.StopAdvertisingAndListeningshould be called once
# teardown
# setup
# Pass an empty array to ThaliNotificationServer.start
ok 543 StartUpdateAdvertisingAndListening should not be called
ok 544 ThaliMobile.StopAdvertisingAndListening should be called once
ok 545 no error
ok 546 should be 204
# teardown
# setup
# Pass a string to ThaliNotificationServer.start
ok 547 StartUpdateAdvertisingAndListening should not be called
# teardown
# setup
# Pass an empty parameter to ThaliNotificationServer.start
ok 548 StartUpdateAdvertisingAndListening should not be called
# teardown
# setup
# Make an HTTP request to /NotificationBeacons
ok 549 no error
ok 550 should be 200
ok 551 should be equal
ok 552 should be equal
ok 553 (unnamed assert)
ok 554 no error
ok 555 should be 204
# teardown
# setup
# Make an HTTP request to /NotificationBeacons (no keys)
ok 556 error should be null
ok 557 should be 204
# teardown
# setup
# Make an HTTP request to /NotificationBeaconsbefore calling start
ok 558 should be 404
# teardown
# setup
# #testThaliPeerAction - test getters
ok 559 getPeerIdentifier
ok 560 getConnectionType
ok 561 getActionType
ok 562 getActionState
ok 563 getPskIdentity
ok 564 getPskKey
# teardown
# setup
# #testThaliPeerAction - start and kill
ok 565 initial state
ok 566 after start
ok 567 after kill
# teardown
# setup
# #testThaliPeerAction - double start
ok 568 should be equal
# teardown
# setup
# #testThaliPeerAction - start after kill
ok 569 clean kill
ok 570 should be equal
# teardown
# setup
# #testThaliPeerAction - make sure ids are unique
ok 571 should not be equal
# teardown
# setup
# Test PeerConnectionInformation basics
ok 572 connection type works
ok 573 getHostAddress works
ok 574 getPortNumber works
ok 575 getSuggestedTCPTimeout works
# teardown
# setup
# Test PeerDictionary basic functionality
ok 576 Entry counter must be 1
ok 577 Size must be 1
ok 578 Entry counter must be 2
ok 579 Size must be 2
ok 580 Entry2 should not be found
ok 581 Size must be 1
ok 582 Size must be 0
# teardown
# setup
# Test PeerDictionary with multiple entries.
ok 583 Size must be100
ok 584 Entries between 20 and MAXSIZE + 20 should exist
ok 585 WAITING state entry should not be removed
# teardown
# setup
# RESOLVED entries are removed before WAITING state entry.
ok 586 Entries between 6 and MAXSIZE + 4 should exist
ok 587 Size should be MAXSIZE
ok 588 Size should be MAXSIZE+6
# teardown
# setup
# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
ok 589 WAITING state entry should not be removed
ok 590 Waiting entries between 6 and MAXSIZE + 4 should exist
ok 591 Size should be MAXSIZE
ok 592 entryCounter should be MAXSIZE+6
# teardown
# setup
# When CONTROLLED_BY_POOL entry is removed and kill is called.
ok 593 Kill should be called once
ok 594 Size should be 100
# teardown
# setup
# #ThaliPeerPoolInterface - bad enqueues
ok 595 null arg
ok 596 wrong arg type
ok 597 wrong state
# teardown
# setup
# #ThaliPeerPoolInterface - do not allow same object type
ok 598 good enqueue
ok 599 should be equal
# teardown
# setup
# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
ok 600 good enqueue
ok 601 2nd good enqueue
ok 602 we are in the pool
ok 603 We are out of the pool
ok 604 Action was killed
ok 605 The original kill was called too
ok 606 second item is still in queue
# teardown
# setup
# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
ok 607 good enqueue
ok 608 first kill
ok 609 second NOOP kill
# teardown
# setup
# Make sure peerDictionaryKey is reasonable
ok 610 equal keys
ok 611 not equal connection type
ok 612 same connection type, different buffer
# teardown
# setup
# Make sure start works
ok 613 First start and on called correctly
# teardown
# setup
# Make sure stop works
ok 614 second cleared dictionary
ok 615 First start and on called correctly
ok 616 First stop and removeListener called correctly
ok 617 first action kill called
ok 618 second action kill called
ok 619 first cleared dictionary
ok 620 second cleared dictionary
# teardown
# setup
# Simple peer event
ok 621 listener has been set
ok 622 peer dictionary has expected number of entries
ok 623 Dictionary and pool have same action
ok 624 ads match
ok 625 PouchDB matches
ok 626 DB Names match
ok 627 public keys match
ok 628 peer dictionary has expected number of entries
ok 629 Dictionary and pool have same action
ok 630 ads match
ok 631 PouchDB matches
ok 632 DB Names match
ok 633 public keys match
ok 634 start called once
ok 635 kill never called
ok 636 One entry left
ok 637 Dictionary and pool have same action
ok 638 Start never called
ok 639 Kill called once
ok 640 no entries left
ok 641 Third action is dead
ok 642 peer dictionary has expected number of entries
ok 643 Dictionary and pool have same action
ok 644 ads match
ok 645 PouchDB matches
ok 646 DB Names match
ok 647 public keys match
# teardown
# setup
# Server is not there
DEBUG thaliReplicationPeerAction: Got error on replication -  400 connect ECONNREFUSED
ok 648 right error
# teardown
# setup
# Server accepts & closes connection
DEBUG thaliReplicationPeerAction: Got error on replication -  400 socket hang up
ok 649 right error
# teardown
# setup
# Server always returns 500
DEBUG thaliReplicationPeerAction: Got error on replication -  500 Database encountered an unknown error
ok 650 Got error as expected
# teardown
# setup
# Server always returns 401
DEBUG thaliReplicationPeerAction: Got error on replication -  401 Database encountered an unknown error
ok 651 Got error as expected
# teardown
# setup
# Server always returns 403
DEBUG thaliReplicationPeerAction: Got error on replication -  403 Database encountered an unknown error
ok 652 Got error as expected
# teardown
# setup
# Make sure docs replicate
DEBUG thaliReplicationPeerAction: Replication resumed
DEBUG thaliReplicationPeerAction: Got paused with -  
ok 653 should be equal
ok 654 All tests passed!
# teardown
# setup
# Do nothing and make sure we time out
DEBUG thaliReplicationPeerAction: Got paused with -  
ok 655 action should be killed
ok 656 Error should be timed out
ok 657 No doc found
# teardown
# setup
# Do something and make sure we time out
DEBUG thaliReplicationPeerAction: Replication resumed
DEBUG thaliReplicationPeerAction: Got paused with -  
ok 658 should be equal
ok 659 action should be killed
ok 660 Error should be timed out
# teardown
# setup
# Start replicating and then catch error when server goes
ok 661 socket hung up
# teardown
# setup
# compareBufferArrays
ok 662 should throw
ok 663 should throw
ok 664 (unnamed assert)
ok 665 (unnamed assert)
ok 666 (unnamed assert)
ok 667 (unnamed assert)
ok 668 (unnamed assert)
# teardown
# setup
# Call start twice and get error
ok 669 should throw
# teardown
# setup
# Start and make sure it runs
# teardown
# setup
# Make sure getTimeWhenRun is right after start
ok 670 (unnamed assert)
# teardown
# setup
# Make sure getTimeWhenRun is -1 after function is called
ok 671 should be equal
# teardown
# setup
# Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
ok 672 should be equal
ok 673 should be equal
ok 674 should throw
# teardown
# setup
# Test TransientState
ok 675 should throw
ok 676 should throw
ok 677 should be equal
ok 678 should be equal
ok 679 should be equal
ok 680 should be equal
ok 681 (unnamed assert)
ok 682 (unnamed assert)
# teardown
# setup
# No peers and empty database
ok 683 verify failed
ok 684 constructor called once
ok 685 constructor called with right args
ok 686 match start arg
ok 687 start called once
ok 688 stop called once
ok 689 stop after start
# teardown
# setup
# One peer and empty DB
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 690 verify failed
ok 691 constructor called once
ok 692 constructor called with right args
ok 693 match start arg
ok 694 start called once
ok 695 stop called once
ok 696 stop after start
# teardown
# setup
# One peer with _Local set behind current seq
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 697 verify failed
ok 698 constructor called once
ok 699 constructor called with right args
ok 700 match start arg
ok 701 start called once
ok 702 stop called once
ok 703 stop after start
# teardown
# setup
# One peer with _Local set equal to current seq
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 704 verify failed
ok 705 constructor called once
ok 706 constructor called with right args
ok 707 match start arg
ok 708 start called once
ok 709 stop called once
ok 710 stop after start
# teardown
# setup
# One peer with _Local set ahead of current seq (and no this should not happen)
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 711 verify failed
ok 712 constructor called once
ok 713 constructor called with right args
ok 714 match start arg
ok 715 start called once
ok 716 stop called once
ok 717 stop after start
# teardown
# setup
# Three peers, one not in DB, one behind and one ahead
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 718 verify failed
ok 719 constructor called once
ok 720 constructor called with right args
ok 721 match start arg
ok 722 start called once
ok 723 stop called once
ok 724 stop after start
# teardown
# setup
# More than maximum peers, make sure we only send maximum allowed
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 725 verify failed
ok 726 constructor called once
ok 727 constructor called with right args
ok 728 match start arg
ok 729 start called once
ok 730 stop called once
ok 731 stop after start
# teardown
# setup
# two peers with empty DB, update the doc
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 732 verify failed
ok 733 constructor called once
ok 734 constructor called with right args
ok 735 last start before stop
ok 736 empty first start
ok 737 full second start
ok 738 only 2 timers
# teardown
# setup
# add doc and make sure tokens refresh when they expire
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 739 verify failed
ok 740 constructor called once
ok 741 constructor called with right args
ok 742 start before stop
ok 743 We got at least 3 calls to start
ok 744 at least 3
ok 745 default 1
ok 746 1 run
ok 747 default 2
ok 748 2 run
ok 749 default 3
# teardown
# setup
# start and stop and start and stop
ok 750 start out null
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 751 back to null
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 752 still null
ok 753 verify failed
ok 754 constructor called once
ok 755 constructor called with right args
ok 756 first start before first stop
ok 757 first stop before second start
ok 758 second start before second stop
# teardown
# setup
# two identical starts in a row
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 759 verify failed
ok 760 constructor called once
ok 761 constructor called with right args
ok 762 (unnamed assert)
# teardown
# setup
# two different starts in a row
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 763 verify failed
ok 764 constructor called once
ok 765 constructor called with right args
ok 766 (unnamed assert)
ok 767 (unnamed assert)
# teardown
# setup
# two stops and a start and two stops
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 768 verify failed
ok 769 constructor called once
ok 770 constructor called with right args
ok 771 start before stop
# teardown
# setup
# we properly enqueue requests so no then needed
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 772 verify failed
ok 773 constructor called once
ok 774 constructor called with right args
ok 775 start before stop
# teardown
# setup
# test calculateSeqPointKeyId
ok 776 should be equal
ok 777 should be equal
# teardown
# setup
# can create servers manager
ok 778 serversManager must not be null
ok 779 serversManager must be an object
# teardown
# setup
# calling stop without start causes error
ok 780 We need to call start first
# teardown
# setup
# can start/stop servers manager
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50538
ok 781 port must be in range
# teardown
# setup
# starting twice resolves with listening port
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50539
ok 782 second start should return same port
# teardown
# setup
# terminateIncomingConnection will terminate a connection
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50541
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 783 we should be connected
DEBUG createNativeListener: incoming socket close
ok 784 now we are disconnected
# teardown
# setup
# terminate an Outgoing connection will terminate the server
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50543
# teardown
# setup
# terminate an Outgoing connection with wrong arguments is not harmful
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50544
# teardown
# setup
ok 785 should be in started state
# After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
ok 786 peer identifier should match
ok 787 host address should match
ok 788 port should match
ok 789 host address should be null
ok 790 port should should be null
# teardown
ok 791 should not be in started state
# setup
ok 792 should be in started state
# #startUpdateAdvertisingAndListening should use different USN after every invocation
DEBUG thaliWifiInfrastructure: listening 50545
ok 793 USN should have changed from the first one
ok 794 when receiving the second byebye, the first USN should be already set
# teardown
ok 795 should not be in started state
# setup
ok 796 should be in started state
# messages with invalid location or USN should be ignored
WARN thaliWifiInfrastructure: Failed to parse a valid port number from location: http://foo.bar:90000
ok 797 should not have emitted with invalid port
WARN thaliWifiInfrastructure: Received an invalid USN value: 
ok 798 should not have emitted with invalid USN
# teardown
ok 799 should not be in started state
# setup
ok 800 should be in started state
# verify that Thali-specific messages are filtered correctly
ok 801 irrelevant messages should be ignored
ok 802 relevant messages should not be ignored
ok 803 messages from this device should be ignored
# teardown
ok 804 should not be in started state
# setup
ok 805 should be in started state
# #startListeningForAdvertisements should fail if start not called
ok 806 specific error should be returned
# teardown
ok 807 should not be in started state
# setup
ok 808 should be in started state
# #startUpdateAdvertisingAndListening should fail if start not called
ok 809 specific error should be returned
# teardown
ok 810 should not be in started state
# setup
ok 811 should be in started state
# #start should fail if called twice in a row
ok 812 specific error should be received
# teardown
ok 813 should not be in started state
# setup
ok 814 should be in started state
# should not be started after stop is called
ok 815 should not be started
ok 816 should not be listening
ok 817 should not target listening
ok 818 should not be advertising
ok 819 should not target advertising
# teardown
ok 820 should not be in started state
# setup
ok 821 should be in started state
# #startUpdateAdvertisingAndListening should fail invalid router has been passed
ERROR thaliWifiInfrastructure: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
ok 822 specific error should be received
# teardown
ok 823 should not be in started state
# setup
ok 824 should be in started state
# #startUpdateAdvertisingAndListening should fail if router server starting fails
ERROR thaliWifiInfrastructure: Router server emitted an error: Error: listen EADDRINUSE
ok 825 specific error expected
# teardown
ok 826 should not be in started state
# setup
ok 827 should be in started state
# #startUpdateAdvertisingAndListening should start hosting given router object
DEBUG thaliWifiInfrastructure: listening 50547
ok 828 server should respond with code 200
# teardown
ok 829 should not be in started state
# setup
ok 830 should be in started state
# #startUpdateAdvertisingAndListening bad psk should be rejected object
DEBUG thaliWifiInfrastructure: listening 50549
ok 831 Connection should be rejected
# teardown
ok 832 should not be in started state
# setup
ok 833 should be in started state
# #stop can be called multiple times in a row
ok 834 should be in stopped state
ok 835 should still be in stopped state
# teardown
ok 836 should not be in started state
# setup
ok 837 should be in started state
# #startListeningForAdvertisements can be called multiple times in a row
ok 838 should be in listening state
ok 839 should still be in listening state
# teardown
ok 840 should not be in started state
# setup
ok 841 should be in started state
# #stopListeningForAdvertisements can be called multiple times in a row
ok 842 should not be in listening state
ok 843 should still not be in listening state
# teardown
ok 844 should not be in started state
# setup
ok 845 should be in started state
# #stopAdvertisingAndListening can be called multiple times in a row
ok 846 should not be in advertising state
ok 847 should still not be in advertising state
# teardown
ok 848 should not be in started state
# setup
ok 849 should be in started state
# functions are run from a queue in the right order
DEBUG thaliWifiInfrastructure: listening 50551
ok 850 call order must match
# teardown
ok 851 should not be in started state
# setup
ok 852 should be in started state
# does not get peer changes from self
DEBUG thaliWifiInfrastructure: listening 50552
ok 853 USN must have changed again
# teardown
ok 854 should not be in started state
# setup
ok 855 should be in started state
# network changes are ignored while stopping
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 856 should not be called
# teardown
ok 857 should not be in started state
# setup
ok 858 should be in started state
# #startListeningForAdvertisements returns error if wifi is off and fires event when on
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 859 wifi should be off
ok 860 specific error expected
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 861 discoveryActive should be true
# teardown
ok 862 should not be in started state
# setup
ok 863 should be in started state
# #startUpdateAdvertisingAndListening returns error if wifi is off and fires event when on
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 864 wifi should be off
ok 865 specific error expected
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliWifiInfrastructure: listening 50553
ok 866 advertisingActive should be true
# teardown
ok 867 should not be in started state
# setup
ok 868 should be in started state
# when wifi is enabled discovery is activated and peers become available
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 869 wifi should be off
ok 870 specific error expected
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 871 peer identifier should match
ok 872 host address should match
ok 873 port should match
# teardown
ok 874 should not be in started state
# setup
# #ThaliPeerPoolDefault - single action
ok 875 is an agent
ok 876 enqueue is fine
ok 877 Everything should be off the queue
# teardown
# setup
# #ThaliPeerPoolDefault - multiple actions
ok 878 is an agent
ok 879 first enqueue is fine
ok 880 is an agent
ok 881 second enqueue is fine
ok 882 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 883 Queue is empty
# teardown
# setup
# #ThaliPeerPoolDefault - PSK Pool works
ok 884 is an agent
ok 885 good enqueue
ok 886 Identity should match
ok 887 Got expected response
ok 888 Got psk call back
# teardown
# setup
# #ThaliPeerPoolDefault - stop
ok 889 is an agent
ok 890 enqueue worked
ok 891 is an agent
ok 892 enqueue 2 worked
ok 893 start action is killed
ok 894 killed action is still killed
ok 895 inQueue is empty
ok 896 Make sure we won enqueue after stopping
# teardown

npm http request GET http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/socket.io
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/fs-extra-promise
npm http request GET http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/fs-extra-promise
npm http 200 http://192.168.1.100:4873/socket.io
npm http 200 http://192.168.1.100:4873/express
npm http 200 http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/content-disposition
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/array-flatten
npm http request GET http://192.168.1.100:4873/cookie
npm http request GET http://192.168.1.100:4873/accepts
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/escape-html
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/parseurl
npm http request GET http://192.168.1.100:4873/proxy-addr
npm http request GET http://192.168.1.100:4873/finalhandler
npm http request GET http://192.168.1.100:4873/etag
npm http request GET http://192.168.1.100:4873/merge-descriptors
npm http request GET http://192.168.1.100:4873/path-to-regexp
npm http request GET http://192.168.1.100:4873/fresh
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/cookie-signature
npm http request GET http://192.168.1.100:4873/vary
npm http request GET http://192.168.1.100:4873/send
npm http request GET http://192.168.1.100:4873/utils-merge
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/range-parser
npm http request GET http://192.168.1.100:4873/serve-static
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/accepts
npm http 200 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/escape-html
npm http 200 http://192.168.1.100:4873/methods
npm http 200 http://192.168.1.100:4873/on-finished
npm http 200 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 200 http://192.168.1.100:4873/etag
npm http 200 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 200 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/depd
npm http 200 http://192.168.1.100:4873/vary
npm http 200 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/send
npm http 200 http://192.168.1.100:4873/type-is
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/utils-merge
npm http 200 http://192.168.1.100:4873/qs
npm http 200 http://192.168.1.100:4873/serve-static
npm http request GET http://192.168.1.100:4873/mime-types
npm http request GET http://192.168.1.100:4873/negotiator
npm http 304 http://192.168.1.100:4873/mime-types
npm http 200 http://192.168.1.100:4873/negotiator
npm http request GET http://192.168.1.100:4873/mime-db
npm http 200 http://192.168.1.100:4873/mime-db
npm http request GET http://192.168.1.100:4873/ms
npm http 200 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/unpipe
npm http 200 http://192.168.1.100:4873/unpipe
npm http request GET http://192.168.1.100:4873/ee-first
npm http 200 http://192.168.1.100:4873/ee-first
npm http request GET http://192.168.1.100:4873/forwarded
npm http request GET http://192.168.1.100:4873/ipaddr.js
npm http 200 http://192.168.1.100:4873/forwarded
npm http 200 http://192.168.1.100:4873/ipaddr.js
npm http request GET http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/statuses
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/mime
npm http 304 http://192.168.1.100:4873/statuses
npm http 304 http://192.168.1.100:4873/http-errors
npm http 200 http://192.168.1.100:4873/destroy
npm http 200 http://192.168.1.100:4873/mime
npm http request GET http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/media-typer
npm http 200 http://192.168.1.100:4873/media-typer
npm http request GET http://192.168.1.100:4873/fs-extra
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/fs-extra
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/jsonfile
npm http request GET http://192.168.1.100:4873/rimraf
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http 304 http://192.168.1.100:4873/rimraf
npm http 200 http://192.168.1.100:4873/jsonfile
npm http request GET http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/fs.realpath
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/fs.realpath
npm http 304 http://192.168.1.100:4873/inflight
npm http 200 http://192.168.1.100:4873/path-is-absolute
npm http 200 http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/wrappy
npm http 304 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 304 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/immediate
npm http 200 http://192.168.1.100:4873/es3ify
npm http 200 http://192.168.1.100:4873/immediate
npm http 200 http://192.168.1.100:4873/inline-process-browser
npm http 200 http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/through
npm http request GET http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/esprima
npm http 304 http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/esprima
npm http 200 http://192.168.1.100:4873/through
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/base62
npm http 200 http://192.168.1.100:4873/commoner
npm http 200 http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/recast
npm http 200 http://192.168.1.100:4873/private
npm http 200 http://192.168.1.100:4873/mkdirp
npm http 200 http://192.168.1.100:4873/commander
npm http 200 http://192.168.1.100:4873/detective
npm http 200 http://192.168.1.100:4873/iconv-lite
npm http 200 http://192.168.1.100:4873/recast
npm http 200 http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http 304 http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/defined
npm http request GET http://192.168.1.100:4873/acorn
npm http 200 http://192.168.1.100:4873/defined
npm http 200 http://192.168.1.100:4873/acorn
npm http request GET http://192.168.1.100:4873/minimist
npm http 304 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/ast-types
npm http 200 http://192.168.1.100:4873/ast-types
npm http request GET http://192.168.1.100:4873/amdefine
npm http 200 http://192.168.1.100:4873/amdefine
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/falafel
npm http 304 http://192.168.1.100:4873/through2
npm http 200 http://192.168.1.100:4873/falafel
npm http request GET http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/foreach
npm http 304 http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/object-keys
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
npm http request GET http://192.168.1.100:4873/socket.io-parser
npm http request GET http://192.168.1.100:4873/has-binary-data
npm http request GET http://192.168.1.100:4873/socket.io-adapter
npm http request GET http://192.168.1.100:4873/engine.io
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http 304 http://192.168.1.100:4873/has-binary-data
npm http 304 http://192.168.1.100:4873/engine.io
npm http 304 http://192.168.1.100:4873/socket.io-adapter
npm http 200 http://192.168.1.100:4873/socket.io-parser
npm http 200 http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/base64id
npm http request GET http://192.168.1.100:4873/ws
npm http 200 http://192.168.1.100:4873/base64id
npm http 304 http://192.168.1.100:4873/engine.io-parser
npm http 200 http://192.168.1.100:4873/ws
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/utf8
npm http request GET http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/has-binary
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http 200 http://192.168.1.100:4873/blob
npm http 304 http://192.168.1.100:4873/has-binary
npm http 304 http://192.168.1.100:4873/after
npm http 200 http://192.168.1.100:4873/utf8
npm http 200 http://192.168.1.100:4873/base64-arraybuffer
npm http 200 http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/ultron
npm http request GET http://192.168.1.100:4873/bufferutil
npm http request GET http://192.168.1.100:4873/options
npm http request GET http://192.168.1.100:4873/utf-8-validate
npm http 304 http://192.168.1.100:4873/options
npm http 200 http://192.168.1.100:4873/bufferutil
npm http 200 http://192.168.1.100:4873/utf-8-validate
npm http 304 http://192.168.1.100:4873/ultron
npm http request GET http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/nan
npm http 304 http://192.168.1.100:4873/bindings
npm http 304 http://192.168.1.100:4873/nan
npm http request GET http://192.168.1.100:4873/benchmark
npm http request GET http://192.168.1.100:4873/component-emitter
npm http request GET http://192.168.1.100:4873/json3
npm http 304 http://192.168.1.100:4873/component-emitter
npm http 304 http://192.168.1.100:4873/benchmark
npm http 304 http://192.168.1.100:4873/json3
npm http request GET http://192.168.1.100:4873/backo2
npm http request GET http://192.168.1.100:4873/to-array
npm http request GET http://192.168.1.100:4873/indexof
npm http request GET http://192.168.1.100:4873/parseuri
npm http request GET http://192.168.1.100:4873/object-component
npm http request GET http://192.168.1.100:4873/component-bind
npm http request GET http://192.168.1.100:4873/engine.io-client
npm http 304 http://192.168.1.100:4873/indexof
npm http 304 http://192.168.1.100:4873/to-array
npm http 304 http://192.168.1.100:4873/parseuri
npm http 200 http://192.168.1.100:4873/backo2
npm http 200 http://192.168.1.100:4873/object-component
npm http 200 http://192.168.1.100:4873/component-bind
npm http 304 http://192.168.1.100:4873/engine.io-client
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/parseqs
npm http fetch GET https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/has-cors
npm http 304 http://192.168.1.100:4873/parseqs
npm http 200 http://192.168.1.100:4873/parsejson
npm http 200 http://192.168.1.100:4873/component-inherit
npm http fetch 200 https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http fetch GET https://github.com/component/global/archive/v2.0.1.tar.gz
npm http fetch 200 https://github.com/component/global/archive/v2.0.1.tar.gz
npm http request GET http://192.168.1.100:4873/better-assert
npm http 304 http://192.168.1.100:4873/better-assert
npm http request GET http://192.168.1.100:4873/callsite
npm http 200 http://192.168.1.100:4873/callsite
npm http request GET http://192.168.1.100:4873/pkginfo
npm http request GET http://192.168.1.100:4873/cycle
npm http request GET http://192.168.1.100:4873/colors
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/stack-trace
npm http 304 http://192.168.1.100:4873/pkginfo
npm http 304 http://192.168.1.100:4873/cycle
npm http 200 http://192.168.1.100:4873/colors
npm http 200 http://192.168.1.100:4873/eyes
npm http 200 http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/stack-trace
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/tape
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 200 http://192.168.1.100:4873/tape
npm http request GET http://192.168.1.100:4873/jsonify
npm http request GET http://192.168.1.100:4873/deep-equal
npm http 200 http://192.168.1.100:4873/jsonify
npm http 200 http://192.168.1.100:4873/deep-equal
gyp JXcore NODE-GYP Using node-gyp bundled in npm coming from JXcore
In file included from ../src/bufferutil.cc:10:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
1 warning generated.
gyp JXcore NODE-GYP Using node-gyp bundled in npm coming from JXcore
In file included from ../src/validation.cc:10:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
1 warning generated.
npm WARN EPACKAGEJSON thali-test-server@0.0.1 No repository field.
npm WARN EPACKAGEJSON thali-test-server@0.0.1 No license field.
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/express-pouchdb
npm http request GET http://192.168.1.100:4873/forever-agent
npm http request GET http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/javascript-state-machine
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/js-extend
npm http 304 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/ip
npm http 304 http://192.168.1.100:4873/forever-agent
npm http 304 http://192.168.1.100:4873/lie
npm http 304 http://192.168.1.100:4873/express-pouchdb
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/winston
npm http fetch GET http://192.168.1.100:4873/express-pouchdb/-/express-pouchdb-1.0.4.tgz
npm http 200 http://192.168.1.100:4873/javascript-state-machine
npm http 200 http://192.168.1.100:4873/js-extend
npm http 304 http://192.168.1.100:4873/multiplex
npm http fetch 200 http://192.168.1.100:4873/express-pouchdb/-/express-pouchdb-1.0.4.tgz
npm http 200 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/http-errors
npm http 200 http://192.168.1.100:4873/bytes
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
npm http 304 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/fresh
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
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/basic-auth
npm http request GET http://192.168.1.100:4873/compression
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/pouchdb-all-dbs
npm http request GET http://192.168.1.100:4873/pouchdb-auth
npm http request GET http://192.168.1.100:4873/multiparty
npm http request GET http://192.168.1.100:4873/header-case-normalizer
npm http request GET http://192.168.1.100:4873/cookie-parser
npm http request GET http://192.168.1.100:4873/pouchdb-find
npm http request GET http://192.168.1.100:4873/pouchdb-size
npm http request GET http://192.168.1.100:4873/pouchdb-update
npm http request GET http://192.168.1.100:4873/pouchdb-show
npm http request GET http://192.168.1.100:4873/pouchdb-security
npm http request GET http://192.168.1.100:4873/pouchdb-replicator
npm http request GET http://192.168.1.100:4873/pouchdb-rewrite
npm http request GET http://192.168.1.100:4873/pouchdb-list
npm http request GET http://192.168.1.100:4873/pouchdb-validation
npm http request GET http://192.168.1.100:4873/pouchdb-vhost
npm http request GET http://192.168.1.100:4873/pouchdb-wrappers
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/compression
npm http 200 http://192.168.1.100:4873/basic-auth
npm http fetch GET http://192.168.1.100:4873/bluebird/-/bluebird-3.3.4.tgz
npm http 304 http://192.168.1.100:4873/multiparty
npm http 304 http://192.168.1.100:4873/pouchdb-all-dbs
npm http 304 http://192.168.1.100:4873/cookie-parser
npm http 200 http://192.168.1.100:4873/pouchdb-auth
npm http 200 http://192.168.1.100:4873/header-case-normalizer
npm http 200 http://192.168.1.100:4873/pouchdb-security
npm http 304 http://192.168.1.100:4873/pouchdb-size
npm http 304 http://192.168.1.100:4873/pouchdb-show
npm http 304 http://192.168.1.100:4873/pouchdb-update
npm http 200 http://192.168.1.100:4873/pouchdb-validation
npm http 304 http://192.168.1.100:4873/pouchdb-rewrite
npm http 304 http://192.168.1.100:4873/pouchdb-replicator
npm http fetch 200 http://192.168.1.100:4873/bluebird/-/bluebird-3.3.4.tgz
npm http 200 http://192.168.1.100:4873/pouchdb-wrappers
npm http 304 http://192.168.1.100:4873/pouchdb-find
npm http 304 http://192.168.1.100:4873/pouchdb-list
npm http 304 http://192.168.1.100:4873/pouchdb-vhost
npm http request GET http://192.168.1.100:4873/on-headers
npm http request GET http://192.168.1.100:4873/compressible
npm http 200 http://192.168.1.100:4873/on-headers
npm http 304 http://192.168.1.100:4873/compressible
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/stream-counter
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/stream-counter
npm http request GET http://192.168.1.100:4873/core-util-is
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/string_decoder
npm http 304 http://192.168.1.100:4873/core-util-is
npm http 304 http://192.168.1.100:4873/string_decoder
npm http 304 http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/tiny-queue
npm http request GET http://192.168.1.100:4873/argsarray
npm http 304 http://192.168.1.100:4873/es3ify
npm http 200 http://192.168.1.100:4873/argsarray
npm http 200 http://192.168.1.100:4873/tiny-queue
npm http request GET http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/through
npm http 304 http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/through
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/amdefine
npm http 304 http://192.168.1.100:4873/amdefine
npm http request GET http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 304 http://192.168.1.100:4873/immediate
npm http 304 http://192.168.1.100:4873/inline-process-browser
npm http 304 http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/falafel
npm http request GET http://192.168.1.100:4873/through2
npm http 304 http://192.168.1.100:4873/falafel
npm http 304 http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/acorn
npm http request GET http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/acorn
npm http 304 http://192.168.1.100:4873/foreach
npm http 304 http://192.168.1.100:4873/object-keys
npm http request GET http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/esmangle-evaluator
npm http request GET http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/esmangle-evaluator
npm http 304 http://192.168.1.100:4873/recast
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/ast-types
npm http 304 http://192.168.1.100:4873/ast-types
npm http 304 http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/crypto-lite
npm http request GET http://192.168.1.100:4873/base64url
npm http request GET http://192.168.1.100:4873/couchdb-calculate-session-id
npm http request GET http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http request GET http://192.168.1.100:4873/pouchdb-req-http-query
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/pouchdb-plugin-error
npm http request GET http://192.168.1.100:4873/promise-nodify
npm http request GET http://192.168.1.100:4873/pouchdb-system-db
npm http request GET http://192.168.1.100:4873/secure-random
npm http request GET http://192.168.1.100:4873/pouchdb
npm http 200 http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http 200 http://192.168.1.100:4873/couchdb-calculate-session-id
npm http 304 http://192.168.1.100:4873/base64url
npm http 200 http://192.168.1.100:4873/crypto-lite
npm http 200 http://192.168.1.100:4873/pouchdb-req-http-query
npm http 200 http://192.168.1.100:4873/pouchdb-promise
npm http 200 http://192.168.1.100:4873/promise-nodify
npm http 200 http://192.168.1.100:4873/pouchdb-plugin-error
npm http 200 http://192.168.1.100:4873/secure-random
npm http 200 http://192.168.1.100:4873/pouchdb-system-db
npm http fetch GET http://192.168.1.100:4873/pouchdb-promise/-/pouchdb-promise-5.4.5.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-promise/-/pouchdb-promise-5.4.5.tgz
npm http 200 http://192.168.1.100:4873/pouchdb
npm http request GET http://192.168.1.100:4873/meow
npm http request GET http://192.168.1.100:4873/concat-stream
npm http 200 http://192.168.1.100:4873/meow
npm http 200 http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/typedarray
npm http 304 http://192.168.1.100:4873/typedarray
npm http request GET http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/camelcase-keys
npm http request GET http://192.168.1.100:4873/indent-string
npm http 304 http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/minimist
npm http 200 http://192.168.1.100:4873/camelcase-keys
npm http 200 http://192.168.1.100:4873/indent-string
npm http request GET http://192.168.1.100:4873/camelcase
npm http request GET http://192.168.1.100:4873/map-obj
npm http 304 http://192.168.1.100:4873/map-obj
npm http 200 http://192.168.1.100:4873/camelcase
npm http request GET http://192.168.1.100:4873/get-stdin
npm http request GET http://192.168.1.100:4873/repeating
npm http 200 http://192.168.1.100:4873/get-stdin
npm http 304 http://192.168.1.100:4873/repeating
npm http request GET http://192.168.1.100:4873/is-finite
npm http 200 http://192.168.1.100:4873/is-finite
npm http request GET http://192.168.1.100:4873/number-is-nan
npm http 304 http://192.168.1.100:4873/number-is-nan
npm http request GET http://192.168.1.100:4873/aproba
npm http 200 http://192.168.1.100:4873/aproba
npm http request GET http://192.168.1.100:4873/memdown
npm http request GET http://192.168.1.100:4873/localstorage-down
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/level-write-stream
npm http request GET http://192.168.1.100:4873/es6-promise-pool
npm http request GET http://192.168.1.100:4873/fruitdown
npm http request GET http://192.168.1.100:4873/pouchdb-collate
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/scope-eval
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/vuvuzela
npm http 200 http://192.168.1.100:4873/memdown
npm http 200 http://192.168.1.100:4873/localstorage-down
npm http 200 http://192.168.1.100:4873/level-write-stream
npm http 200 http://192.168.1.100:4873/es6-promise-pool
npm http 200 http://192.168.1.100:4873/levelup
npm http 200 http://192.168.1.100:4873/fruitdown
npm http 200 http://192.168.1.100:4873/pouchdb-collections
npm http 200 http://192.168.1.100:4873/pouchdb-collate
npm http 304 http://192.168.1.100:4873/js-extend
npm http 304 http://192.168.1.100:4873/double-ended-queue
npm http 200 http://192.168.1.100:4873/scope-eval
npm http 200 http://192.168.1.100:4873/sublevel-pouchdb
npm http 200 http://192.168.1.100:4873/spark-md5
npm http 200 http://192.168.1.100:4873/vuvuzela
npm http request GET http://192.168.1.100:4873/d64
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http 200 http://192.168.1.100:4873/d64
npm http 200 http://192.168.1.100:4873/abstract-leveldown
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
npm http 304 http://192.168.1.100:4873/prr
npm http 200 http://192.168.1.100:4873/level-errors
npm http 200 http://192.168.1.100:4873/level-codec
npm http 200 http://192.168.1.100:4873/level-iterator-stream
npm http 200 http://192.168.1.100:4873/deferred-leveldown
npm http 304 http://192.168.1.100:4873/semver
npm http request GET http://192.168.1.100:4873/errno
npm http 200 http://192.168.1.100:4873/errno
npm http request GET http://192.168.1.100:4873/esprima
npm http 304 http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/commoner
npm http 304 http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/q
npm http 304 http://192.168.1.100:4873/commander
npm http 304 http://192.168.1.100:4873/detective
npm http 304 http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/q
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http 304 http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http 304 http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/defined
npm http 304 http://192.168.1.100:4873/defined
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/minimatch
npm http 304 http://192.168.1.100:4873/inflight
npm http 304 http://192.168.1.100:4873/once
npm http 200 http://192.168.1.100:4873/path-is-absolute
npm http request GET http://192.168.1.100:4873/wrappy
npm http 304 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 304 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/humble-localstorage
npm http 200 http://192.168.1.100:4873/humble-localstorage
npm http request GET http://192.168.1.100:4873/has-localstorage
npm http request GET http://192.168.1.100:4873/localstorage-memory
npm http 200 http://192.168.1.100:4873/localstorage-memory
npm http 200 http://192.168.1.100:4873/has-localstorage
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
npm http request GET http://192.168.1.100:4873/is-typedarray
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/caseless
npm http 200 http://192.168.1.100:4873/aws4
npm http 200 http://192.168.1.100:4873/aws-sign2
npm http 200 http://192.168.1.100:4873/combined-stream
npm http 200 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/is-typedarray
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/stringstream
npm http 200 http://192.168.1.100:4873/oauth-sign
npm http 200 http://192.168.1.100:4873/tunnel-agent
npm http 200 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/qs
npm WARN deprecated tough-cookie@2.2.2: ReDoS vulnerability parsing Set-Cookie https://nodesecurity.io/advisories/130
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/process-nextick-args
npm http 304 http://192.168.1.100:4873/util-deprecate
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/pinkie-promise
npm http 304 http://192.168.1.100:4873/pinkie-promise
npm http 304 http://192.168.1.100:4873/chalk
npm http 200 http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/ansi-styles
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/supports-color
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 200 http://192.168.1.100:4873/generate-object-property
npm http 200 http://192.168.1.100:4873/generate-function
npm http 200 http://192.168.1.100:4873/jsonpointer
npm http request GET http://192.168.1.100:4873/is-property
npm http 200 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/pinkie
npm http 304 http://192.168.1.100:4873/pinkie
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/boom
npm http 200 http://192.168.1.100:4873/hoek
npm http 304 http://192.168.1.100:4873/cryptiles
npm http 200 http://192.168.1.100:4873/sntp
npm http 200 http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/jsprim
npm http request GET http://192.168.1.100:4873/sshpk
npm http 304 http://192.168.1.100:4873/jsprim
npm http 304 http://192.168.1.100:4873/sshpk
npm http 304 http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/json-schema
npm http request GET http://192.168.1.100:4873/verror
npm http request GET http://192.168.1.100:4873/extsprintf
npm http 304 http://192.168.1.100:4873/verror
npm http 200 http://192.168.1.100:4873/json-schema
npm http 200 http://192.168.1.100:4873/extsprintf
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/dashdash
npm http request GET http://192.168.1.100:4873/getpass
npm http 304 http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/dashdash
npm http 200 http://192.168.1.100:4873/getpass
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/pull-stream
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 200 http://192.168.1.100:4873/pull-stream
npm http request GET http://192.168.1.100:4873/pull-core
npm http 200 http://192.168.1.100:4873/pull-core
npm http request GET http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/pouchdb-promise
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
npm http 200 http://192.168.1.100:4873/random-uuid-v4
npm http 200 http://192.168.1.100:4873/couchdb-eval
npm http 200 http://192.168.1.100:4873/couchdb-objects
npm http request GET http://192.168.1.100:4873/is-empty
npm http 200 http://192.168.1.100:4873/is-empty
npm http request GET http://192.168.1.100:4873/jshint
npm http request GET http://192.168.1.100:4873/pouchdb-abstract-mapreduce
npm http request GET http://192.168.1.100:4873/pouchdb-extend
npm http request GET http://192.168.1.100:4873/pouchdb-upsert
npm http 200 http://192.168.1.100:4873/pouchdb-extend
npm http 200 http://192.168.1.100:4873/pouchdb-upsert
npm http 200 http://192.168.1.100:4873/jshint
npm http fetch GET http://192.168.1.100:4873/jshint/-/jshint-2.9.2.tgz
npm http fetch 200 http://192.168.1.100:4873/jshint/-/jshint-2.9.2.tgz
npm http 200 http://192.168.1.100:4873/pouchdb-abstract-mapreduce
npm http request GET http://192.168.1.100:4873/cli
npm http request GET http://192.168.1.100:4873/console-browserify
npm http request GET http://192.168.1.100:4873/exit
npm http request GET http://192.168.1.100:4873/htmlparser2
npm http request GET http://192.168.1.100:4873/shelljs
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/lodash
npm WARN deprecated minimatch@2.0.10: Please update to minimatch 3.0.2 or higher to avoid a RegExp DoS issue
npm http 200 http://192.168.1.100:4873/cli
npm http 200 http://192.168.1.100:4873/exit
npm http 200 http://192.168.1.100:4873/console-browserify
npm http 200 http://192.168.1.100:4873/htmlparser2
npm http 200 http://192.168.1.100:4873/shelljs
npm http 304 http://192.168.1.100:4873/strip-json-comments
npm http 304 http://192.168.1.100:4873/lodash
npm WARN deprecated minimatch@0.3.0: Please update to minimatch 3.0.2 or higher to avoid a RegExp DoS issue
npm http request GET http://192.168.1.100:4873/lru-cache
npm http request GET http://192.168.1.100:4873/sigmund
npm http 200 http://192.168.1.100:4873/sigmund
npm http 200 http://192.168.1.100:4873/lru-cache
npm http request GET http://192.168.1.100:4873/date-now
npm http 200 http://192.168.1.100:4873/date-now
npm http request GET http://192.168.1.100:4873/domhandler
npm http request GET http://192.168.1.100:4873/domutils
npm http request GET http://192.168.1.100:4873/domelementtype
npm http request GET http://192.168.1.100:4873/entities
npm http 200 http://192.168.1.100:4873/entities
npm http 200 http://192.168.1.100:4873/domutils
npm http 200 http://192.168.1.100:4873/domelementtype
npm http 200 http://192.168.1.100:4873/domhandler
npm http request GET http://192.168.1.100:4873/dom-serializer
npm http 200 http://192.168.1.100:4873/dom-serializer
npm http request GET http://192.168.1.100:4873/spark-md5
npm http 304 http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/ctype
npm http 200 http://192.168.1.100:4873/ctype
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
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/minimist
npm http 304 http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/duplexify
npm http 304 http://192.168.1.100:4873/duplexify
npm http 304 http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/stream-shift
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http 200 http://192.168.1.100:4873/end-of-stream
npm http 304 http://192.168.1.100:4873/stream-shift
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http 200 http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/jsonschema
npm http request GET http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/jsonschema
npm http fetch GET http://192.168.1.100:4873/object-assign/-/object-assign-4.1.0.tgz
npm http fetch 200 http://192.168.1.100:4873/object-assign/-/object-assign-4.1.0.tgz
npm http fetch GET http://192.168.1.100:4873/jsonschema/-/jsonschema-1.1.0.tgz
npm http fetch 200 http://192.168.1.100:4873/jsonschema/-/jsonschema-1.1.0.tgz
npm http request GET http://192.168.1.100:4873/colors
npm http request GET http://192.168.1.100:4873/cycle
npm http request GET http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/pkginfo
npm http request GET http://192.168.1.100:4873/stack-trace
npm http 304 http://192.168.1.100:4873/colors
npm http 304 http://192.168.1.100:4873/cycle
npm http 304 http://192.168.1.100:4873/pkginfo
npm http 304 http://192.168.1.100:4873/stack-trace
npm http 304 http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/jsdoc
npm http 200 http://192.168.1.100:4873/jsdoc
npm http request GET http://192.168.1.100:4873/js2xmlparser
npm http request GET http://192.168.1.100:4873/catharsis
npm http request GET http://192.168.1.100:4873/marked
npm http request GET http://192.168.1.100:4873/requizzle
npm http request GET http://192.168.1.100:4873/underscore
npm http request GET http://192.168.1.100:4873/wrench
npm http request GET http://192.168.1.100:4873/esprima
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 304 http://192.168.1.100:4873/catharsis
npm http 304 http://192.168.1.100:4873/js2xmlparser
npm http 304 http://192.168.1.100:4873/requizzle
npm http 304 http://192.168.1.100:4873/underscore
npm http 200 http://192.168.1.100:4873/marked
npm http 304 http://192.168.1.100:4873/wrench
npm http 304 http://192.168.1.100:4873/esprima
npm WARN deprecated wrench@1.5.9: wrench.js is deprecated! You should check out fs-extra (https://github.com/jprichardson/node-fs-extra) for any operations you were using wrench for. Thanks for all the usage over the years.
npm http fetch 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http request GET http://192.168.1.100:4873/underscore-contrib
npm http 304 http://192.168.1.100:4873/underscore-contrib
npm WARN prefer global marked@0.3.6 should be installed with -g
npm WARN prefer global jshint@2.9.2 should be installed with -g
npm http request GET http://192.168.1.100:4873/leveldown
npm http request GET http://192.168.1.100:4873/websql
npm http 200 http://192.168.1.100:4873/websql
npm http 200 http://192.168.1.100:4873/leveldown
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/nan
npm http request GET http://192.168.1.100:4873/fast-future
npm http request GET http://192.168.1.100:4873/prebuild
npm http 200 http://192.168.1.100:4873/bindings
npm http 200 http://192.168.1.100:4873/fast-future
npm http 304 http://192.168.1.100:4873/nan
npm http 200 http://192.168.1.100:4873/prebuild
npm http 200 http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/expand-template
npm http request GET http://192.168.1.100:4873/ghreleases
npm http request GET http://192.168.1.100:4873/github-from-package
npm http request GET http://192.168.1.100:4873/node-ninja
npm http request GET http://192.168.1.100:4873/os-homedir
npm http request GET http://192.168.1.100:4873/npmlog
npm http request GET http://192.168.1.100:4873/node-gyp
npm http request GET http://192.168.1.100:4873/noop-logger
npm http request GET http://192.168.1.100:4873/pump
npm http request GET http://192.168.1.100:4873/simple-get
npm http request GET http://192.168.1.100:4873/rc
npm http request GET http://192.168.1.100:4873/tar-fs
npm http request GET http://192.168.1.100:4873/tar-stream
npm http 304 http://192.168.1.100:4873/os-homedir
npm http 200 http://192.168.1.100:4873/node-ninja
npm http 200 http://192.168.1.100:4873/github-from-package
npm http 200 http://192.168.1.100:4873/ghreleases
npm http 200 http://192.168.1.100:4873/expand-template
npm http 304 http://192.168.1.100:4873/npmlog
npm http 304 http://192.168.1.100:4873/node-gyp
npm http 304 http://192.168.1.100:4873/pump
npm http 200 http://192.168.1.100:4873/noop-logger
npm http 200 http://192.168.1.100:4873/simple-get
npm http 304 http://192.168.1.100:4873/rc
npm http 304 http://192.168.1.100:4873/tar-stream
npm http 200 http://192.168.1.100:4873/tar-fs
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/simple-mime
npm http request GET http://192.168.1.100:4873/ghrepos
npm http request GET http://192.168.1.100:4873/url-template
npm http request GET http://192.168.1.100:4873/ghutils
npm http 200 http://192.168.1.100:4873/ghutils
npm http 200 http://192.168.1.100:4873/ghrepos
npm http 200 http://192.168.1.100:4873/url-template
npm http 200 http://192.168.1.100:4873/after
npm http 200 http://192.168.1.100:4873/simple-mime
npm http request GET http://192.168.1.100:4873/jsonist
npm http 200 http://192.168.1.100:4873/jsonist
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/hyperquest
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/hyperquest
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/duplexer2
npm http 304 http://192.168.1.100:4873/duplexer2
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/rimraf
npm http request GET http://192.168.1.100:4873/fstream
npm http request GET http://192.168.1.100:4873/nopt
npm http request GET http://192.168.1.100:4873/path-array
npm http request GET http://192.168.1.100:4873/osenv
npm http request GET http://192.168.1.100:4873/tar
npm http request GET http://192.168.1.100:4873/which
npm http 304 http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/rimraf
npm http 200 http://192.168.1.100:4873/path-array
npm http 304 http://192.168.1.100:4873/osenv
npm http 304 http://192.168.1.100:4873/fstream
npm http 200 http://192.168.1.100:4873/nopt
npm http 304 http://192.168.1.100:4873/tar
npm http 200 http://192.168.1.100:4873/which
npm http request GET http://192.168.1.100:4873/fs.realpath
npm http 304 http://192.168.1.100:4873/fs.realpath
npm http request GET http://192.168.1.100:4873/abbrev
npm http 200 http://192.168.1.100:4873/abbrev
npm http request GET http://192.168.1.100:4873/ansi
npm http request GET http://192.168.1.100:4873/are-we-there-yet
npm http request GET http://192.168.1.100:4873/gauge
npm http 304 http://192.168.1.100:4873/ansi
npm http 304 http://192.168.1.100:4873/are-we-there-yet
npm http 200 http://192.168.1.100:4873/gauge
npm http request GET http://192.168.1.100:4873/delegates
npm http 304 http://192.168.1.100:4873/delegates
npm http request GET http://192.168.1.100:4873/has-unicode
npm http request GET http://192.168.1.100:4873/lodash.pad
npm http request GET http://192.168.1.100:4873/lodash.padstart
npm http request GET http://192.168.1.100:4873/lodash.padend
npm http 304 http://192.168.1.100:4873/lodash.padstart
npm http 200 http://192.168.1.100:4873/lodash.padend
npm http 304 http://192.168.1.100:4873/lodash.pad
npm http 200 http://192.168.1.100:4873/has-unicode
npm http request GET http://192.168.1.100:4873/os-tmpdir
npm http 304 http://192.168.1.100:4873/os-tmpdir
npm http request GET http://192.168.1.100:4873/array-index
npm http 304 http://192.168.1.100:4873/array-index
npm http request GET http://192.168.1.100:4873/es6-symbol
npm http 200 http://192.168.1.100:4873/es6-symbol
npm http request GET http://192.168.1.100:4873/d
npm http request GET http://192.168.1.100:4873/es5-ext
npm http 304 http://192.168.1.100:4873/d
npm http 304 http://192.168.1.100:4873/es5-ext
npm http request GET http://192.168.1.100:4873/es6-iterator
npm http 304 http://192.168.1.100:4873/es6-iterator
npm http request GET http://192.168.1.100:4873/block-stream
npm http 304 http://192.168.1.100:4873/block-stream
npm http request GET http://192.168.1.100:4873/isexe
npm http 304 http://192.168.1.100:4873/isexe
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http 304 http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/deep-extend
npm http request GET http://192.168.1.100:4873/ini
npm http 200 http://192.168.1.100:4873/ini
npm http 304 http://192.168.1.100:4873/deep-extend
npm WARN engine deep-extend@0.4.1: wanted: {"node":">=0.12.0","iojs":">=1.0.0"} (current: {"node":"0.10.40","npm":"3.3.12"})
npm http request GET http://192.168.1.100:4873/unzip-response
npm http 304 http://192.168.1.100:4873/unzip-response
npm http request GET http://192.168.1.100:4873/ecc-jsbn
npm http request GET http://192.168.1.100:4873/jodid25519
npm http request GET http://192.168.1.100:4873/jsbn
npm http request GET http://192.168.1.100:4873/tweetnacl
npm http 304 http://192.168.1.100:4873/ecc-jsbn
npm http 304 http://192.168.1.100:4873/jodid25519
npm http 304 http://192.168.1.100:4873/tweetnacl
npm http 304 http://192.168.1.100:4873/jsbn
npm http request GET http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/noop-fn
npm http request GET http://192.168.1.100:4873/sqlite3
npm http 304 http://192.168.1.100:4873/immediate
npm http 304 http://192.168.1.100:4873/sqlite3
npm http 200 http://192.168.1.100:4873/noop-fn
npm WARN prefer global node-ninja@1.0.2 should be installed with -g
npm WARN prefer global node-gyp@3.4.0 should be installed with -g
node-pre-gyp http GET https://mapbox-node-binary.s3.amazonaws.com/sqlite3/v3.1.4/node-v11-darwin-x64.tar.gz
node-pre-gyp http 200 https://mapbox-node-binary.s3.amazonaws.com/sqlite3/v3.1.4/node-v11-darwin-x64.tar.gz
gyp JXcore NODE-GYP Using node-gyp bundled in npm coming from JXcore
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
npm http request GET http://192.168.1.100:4873/fs-extra-promise
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/jxc
npm http request GET http://192.168.1.100:4873/unzip
npm http 304 http://192.168.1.100:4873/fs-extra-promise
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/lie
npm http 304 http://192.168.1.100:4873/unzip
npm http 304 http://192.168.1.100:4873/jxc
npm http request GET http://192.168.1.100:4873/fs-extra
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/fs-extra
npm http 304 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/jsonfile
npm http request GET http://192.168.1.100:4873/rimraf
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http 304 http://192.168.1.100:4873/rimraf
npm http 200 http://192.168.1.100:4873/jsonfile
npm http request GET http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/fs.realpath
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/inflight
npm http 304 http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/minimatch
npm http 304 http://192.168.1.100:4873/fs.realpath
npm http 304 http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/wrappy
npm http 304 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 304 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 200 http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/adm-zip
npm http request GET http://192.168.1.100:4873/progress
npm http 304 http://192.168.1.100:4873/progress
npm http 304 http://192.168.1.100:4873/adm-zip
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 304 http://192.168.1.100:4873/es3ify
npm http 304 http://192.168.1.100:4873/inline-process-browser
npm http 304 http://192.168.1.100:4873/unreachable-branch-transform
npm http 304 http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/through
npm http 304 http://192.168.1.100:4873/esprima
npm http 304 http://192.168.1.100:4873/through
npm http 304 http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/base62
npm http 304 http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 200 http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/mkdirp
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/detective
npm http 304 http://192.168.1.100:4873/private
npm http 200 http://192.168.1.100:4873/commander
npm http 304 http://192.168.1.100:4873/q
npm http 304 http://192.168.1.100:4873/recast
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http 304 http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/acorn
npm http request GET http://192.168.1.100:4873/defined
npm http 304 http://192.168.1.100:4873/acorn
npm http 304 http://192.168.1.100:4873/defined
npm http request GET http://192.168.1.100:4873/minimist
npm http 304 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/ast-types
npm http 304 http://192.168.1.100:4873/ast-types
npm http request GET http://192.168.1.100:4873/amdefine
npm http 304 http://192.168.1.100:4873/amdefine
npm http request GET http://192.168.1.100:4873/falafel
npm http request GET http://192.168.1.100:4873/through2
npm http 304 http://192.168.1.100:4873/through2
npm http 304 http://192.168.1.100:4873/falafel
npm http request GET http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/foreach
npm http 304 http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/core-util-is
npm http request GET http://192.168.1.100:4873/string_decoder
npm http 304 http://192.168.1.100:4873/core-util-is
npm http 304 http://192.168.1.100:4873/string_decoder
npm http request GET http://192.168.1.100:4873/esmangle-evaluator
npm http 304 http://192.168.1.100:4873/esmangle-evaluator
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/forever-agent
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/mime-types
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/qs
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
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/forever-agent
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 200 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/process-nextick-args
npm http 304 http://192.168.1.100:4873/util-deprecate
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/mime-db
npm http 304 http://192.168.1.100:4873/mime-db
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http 304 http://192.168.1.100:4873/is-my-json-valid
npm http 304 http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http 304 http://192.168.1.100:4873/generate-function
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http request GET http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/hoek
npm http 304 http://192.168.1.100:4873/cryptiles
npm http 200 http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/fstream
npm http request GET http://192.168.1.100:4873/setimmediate
npm http request GET http://192.168.1.100:4873/binary
npm http request GET http://192.168.1.100:4873/match-stream
npm http request GET http://192.168.1.100:4873/pullstream
npm http 304 http://192.168.1.100:4873/match-stream
npm http 304 http://192.168.1.100:4873/binary
npm http 200 http://192.168.1.100:4873/setimmediate
npm http 200 http://192.168.1.100:4873/fstream
npm http 304 http://192.168.1.100:4873/pullstream
npm http request GET http://192.168.1.100:4873/chainsaw
npm http request GET http://192.168.1.100:4873/buffers
npm http 304 http://192.168.1.100:4873/chainsaw
npm http 304 http://192.168.1.100:4873/buffers
npm http request GET http://192.168.1.100:4873/traverse
npm http 304 http://192.168.1.100:4873/traverse
npm WARN deprecated graceful-fs@3.0.8: graceful-fs v3.0.0 and before will fail on node releases >= v7.0. Please update to graceful-fs@^4.0.0 as soon as possible. Use 'npm ls graceful-fs' to find it in the tree.
npm http request GET http://192.168.1.100:4873/slice-stream
npm http request GET http://192.168.1.100:4873/over
npm http 200 http://192.168.1.100:4873/over
npm http 200 http://192.168.1.100:4873/slice-stream
npm WARN EPACKAGEJSON install@0.0.1 No repository field.
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/express-pouchdb
npm http request GET http://192.168.1.100:4873/forever-agent
npm http request GET http://192.168.1.100:4873/fs-extra-promise
npm http request GET http://192.168.1.100:4873/bn.js
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/leveldown-mobile
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/pouchdb-node
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/request-promise
npm http request GET http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/proxyquire
npm http request GET http://192.168.1.100:4873/nock
npm http request GET http://192.168.1.100:4873/supertest
npm http request GET http://192.168.1.100:4873/sinon
npm http request GET http://192.168.1.100:4873/tape
npm http request GET http://192.168.1.100:4873/supertest-as-promised
npm http request GET http://192.168.1.100:4873/tape-catch
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/tmp
npm http request GET http://192.168.1.100:4873/uuid
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/express-pouchdb
npm http 304 http://192.168.1.100:4873/forever-agent
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/fs-extra-promise
npm http 304 http://192.168.1.100:4873/bn.js
npm http 304 http://192.168.1.100:4873/lie
npm http 304 http://192.168.1.100:4873/minimist
npm http 304 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/multiplex
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/leveldown-mobile
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/pouchdb-node
npm http 304 http://192.168.1.100:4873/request-promise
npm http 200 http://192.168.1.100:4873/socket.io-client
npm http fetch GET http://192.168.1.100:4873/pouchdb-node/-/pouchdb-node-5.4.4.tgz
npm http 304 http://192.168.1.100:4873/proxyquire
npm http 304 http://192.168.1.100:4873/supertest
npm http 200 http://192.168.1.100:4873/js-extend
npm http 200 http://192.168.1.100:4873/nock
npm http 304 http://192.168.1.100:4873/tape
npm http 200 http://192.168.1.100:4873/supertest-as-promised
npm http 200 http://192.168.1.100:4873/sinon
npm http 304 http://192.168.1.100:4873/tape-catch
npm http fetch 200 http://192.168.1.100:4873/pouchdb-node/-/pouchdb-node-5.4.4.tgz
npm http 304 http://192.168.1.100:4873/urlsafe-base64
npm http 304 http://192.168.1.100:4873/tmp
npm http 304 http://192.168.1.100:4873/uuid
npm http 200 http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/iconv-lite
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
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/send
npm http 304 http://192.168.1.100:4873/serve-static
npm http 304 http://192.168.1.100:4873/utils-merge
npm http 304 http://192.168.1.100:4873/vary
npm http request GET http://192.168.1.100:4873/negotiator
npm http 304 http://192.168.1.100:4873/negotiator
npm http request GET http://192.168.1.100:4873/forwarded
npm http request GET http://192.168.1.100:4873/ipaddr.js
npm http 200 http://192.168.1.100:4873/ipaddr.js
npm http 200 http://192.168.1.100:4873/forwarded
npm http request GET http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/mime
npm http 304 http://192.168.1.100:4873/mime
npm http 304 http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/basic-auth
npm http request GET http://192.168.1.100:4873/compression
npm http request GET http://192.168.1.100:4873/cookie-parser
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/header-case-normalizer
npm http request GET http://192.168.1.100:4873/multiparty
npm http request GET http://192.168.1.100:4873/pouchdb-all-dbs
npm http request GET http://192.168.1.100:4873/pouchdb-auth
npm http request GET http://192.168.1.100:4873/pouchdb-find
npm http request GET http://192.168.1.100:4873/pouchdb-list
npm http request GET http://192.168.1.100:4873/pouchdb-replicator
npm http request GET http://192.168.1.100:4873/pouchdb-rewrite
npm http request GET http://192.168.1.100:4873/pouchdb-security
npm http request GET http://192.168.1.100:4873/pouchdb-show
npm http request GET http://192.168.1.100:4873/pouchdb-size
npm http request GET http://192.168.1.100:4873/pouchdb-update
npm http request GET http://192.168.1.100:4873/pouchdb-validation
npm http request GET http://192.168.1.100:4873/pouchdb-vhost
npm http request GET http://192.168.1.100:4873/pouchdb-wrappers
npm http 304 http://192.168.1.100:4873/basic-auth
npm http 304 http://192.168.1.100:4873/compression
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/cookie-parser
npm http 304 http://192.168.1.100:4873/pouchdb-all-dbs
npm http 304 http://192.168.1.100:4873/multiparty
npm http 304 http://192.168.1.100:4873/pouchdb-find
npm http 304 http://192.168.1.100:4873/pouchdb-list
npm http 304 http://192.168.1.100:4873/pouchdb-replicator
npm http 304 http://192.168.1.100:4873/pouchdb-rewrite
npm http 200 http://192.168.1.100:4873/pouchdb-auth
npm http 304 http://192.168.1.100:4873/pouchdb-show
npm http 304 http://192.168.1.100:4873/pouchdb-size
npm http 304 http://192.168.1.100:4873/pouchdb-update
npm http 304 http://192.168.1.100:4873/pouchdb-vhost
npm http 200 http://192.168.1.100:4873/pouchdb-validation
npm http 200 http://192.168.1.100:4873/header-case-normalizer
npm http 200 http://192.168.1.100:4873/pouchdb-wrappers
npm http 200 http://192.168.1.100:4873/pouchdb-security
npm http request GET http://192.168.1.100:4873/compressible
npm http request GET http://192.168.1.100:4873/on-headers
npm http 304 http://192.168.1.100:4873/compressible
npm http 304 http://192.168.1.100:4873/on-headers
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/stream-counter
npm http 304 http://192.168.1.100:4873/stream-counter
npm http 304 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/core-util-is
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/string_decoder
npm http 304 http://192.168.1.100:4873/core-util-is
npm http 304 http://192.168.1.100:4873/string_decoder
npm http 304 http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/argsarray
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/tiny-queue
npm http 304 http://192.168.1.100:4873/es3ify
npm http 200 http://192.168.1.100:4873/argsarray
npm http 200 http://192.168.1.100:4873/tiny-queue
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/through
npm http 304 http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/through
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/amdefine
npm http 304 http://192.168.1.100:4873/amdefine
npm http request GET http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 304 http://192.168.1.100:4873/unreachable-branch-transform
npm http 304 http://192.168.1.100:4873/immediate
npm http 304 http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/falafel
npm http request GET http://192.168.1.100:4873/through2
npm http 304 http://192.168.1.100:4873/through2
npm http 200 http://192.168.1.100:4873/falafel
npm http request GET http://192.168.1.100:4873/acorn
npm http request GET http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/foreach
npm http 304 http://192.168.1.100:4873/acorn
npm http request GET http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/esmangle-evaluator
npm http request GET http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/esmangle-evaluator
npm http 200 http://192.168.1.100:4873/recast
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/ast-types
npm http 304 http://192.168.1.100:4873/private
npm http 200 http://192.168.1.100:4873/ast-types
npm http request GET http://192.168.1.100:4873/base64url
npm http request GET http://192.168.1.100:4873/couchdb-calculate-session-id
npm http request GET http://192.168.1.100:4873/crypto-lite
npm http request GET http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http request GET http://192.168.1.100:4873/pouchdb-plugin-error
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/pouchdb
npm http request GET http://192.168.1.100:4873/pouchdb-req-http-query
npm http request GET http://192.168.1.100:4873/pouchdb-system-db
npm http request GET http://192.168.1.100:4873/promise-nodify
npm http request GET http://192.168.1.100:4873/secure-random
npm http 304 http://192.168.1.100:4873/base64url
npm http 200 http://192.168.1.100:4873/crypto-lite
npm http 200 http://192.168.1.100:4873/couchdb-calculate-session-id
npm http 200 http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http 200 http://192.168.1.100:4873/pouchdb-system-db
npm http 200 http://192.168.1.100:4873/pouchdb-req-http-query
npm http 200 http://192.168.1.100:4873/pouchdb-promise
npm http 200 http://192.168.1.100:4873/pouchdb-plugin-error
npm http 200 http://192.168.1.100:4873/promise-nodify
npm http 200 http://192.168.1.100:4873/secure-random
npm http 200 http://192.168.1.100:4873/pouchdb
npm http request GET http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/meow
npm http 304 http://192.168.1.100:4873/concat-stream
npm http 304 http://192.168.1.100:4873/meow
npm http request GET http://192.168.1.100:4873/typedarray
npm http 304 http://192.168.1.100:4873/typedarray
npm http request GET http://192.168.1.100:4873/camelcase-keys
npm http request GET http://192.168.1.100:4873/indent-string
npm http request GET http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/camelcase-keys
npm http 304 http://192.168.1.100:4873/indent-string
npm http 304 http://192.168.1.100:4873/object-assign
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
npm http request GET http://192.168.1.100:4873/es6-promise-pool
npm http request GET http://192.168.1.100:4873/fruitdown
npm http request GET http://192.168.1.100:4873/level-write-stream
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/localstorage-down
npm http request GET http://192.168.1.100:4873/memdown
npm http request GET http://192.168.1.100:4873/pouchdb-collate
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/scope-eval
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/vuvuzela
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/fruitdown
npm http 200 http://192.168.1.100:4873/es6-promise-pool
npm http 200 http://192.168.1.100:4873/double-ended-queue
npm http 200 http://192.168.1.100:4873/localstorage-down
npm http 200 http://192.168.1.100:4873/levelup
npm http 200 http://192.168.1.100:4873/pouchdb-collate
npm http 200 http://192.168.1.100:4873/pouchdb-collections
npm http 200 http://192.168.1.100:4873/level-write-stream
npm http 200 http://192.168.1.100:4873/spark-md5
npm http 200 http://192.168.1.100:4873/scope-eval
npm http 304 http://192.168.1.100:4873/js-extend
npm http 200 http://192.168.1.100:4873/sublevel-pouchdb
npm http 304 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/vuvuzela
npm http 200 http://192.168.1.100:4873/memdown
npm http request GET http://192.168.1.100:4873/d64
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http 304 http://192.168.1.100:4873/abstract-leveldown
npm http 200 http://192.168.1.100:4873/d64
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
npm http 304 http://192.168.1.100:4873/prr
npm http 200 http://192.168.1.100:4873/level-errors
npm http 200 http://192.168.1.100:4873/deferred-leveldown
npm http 304 http://192.168.1.100:4873/semver
npm http 200 http://192.168.1.100:4873/level-codec
npm http 200 http://192.168.1.100:4873/level-iterator-stream
npm http request GET http://192.168.1.100:4873/errno
npm http 304 http://192.168.1.100:4873/errno
npm http request GET http://192.168.1.100:4873/esprima
npm http 304 http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/commoner
npm http 304 http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/q
npm http 304 http://192.168.1.100:4873/commander
npm http 304 http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/detective
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http 304 http://192.168.1.100:4873/mkdirp
npm http 304 http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http 304 http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/defined
npm http 304 http://192.168.1.100:4873/defined
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/inflight
npm http 304 http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/minimatch
npm http 304 http://192.168.1.100:4873/path-is-absolute
npm http request GET http://192.168.1.100:4873/wrappy
npm http 304 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 304 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/minimist
npm http 304 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/humble-localstorage
npm http request GET http://192.168.1.100:4873/tiny-queue
npm http 304 http://192.168.1.100:4873/tiny-queue
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
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/aws4
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/is-typedarray
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/tough-cookie
npm WARN deprecated tough-cookie@2.2.2: ReDoS vulnerability parsing Set-Cookie https://nodesecurity.io/advisories/130
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http request GET http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/process-nextick-args
npm http 304 http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
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
npm http 304 http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-function
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/pinkie
npm http 304 http://192.168.1.100:4873/pinkie
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/boom
npm http 304 http://192.168.1.100:4873/cryptiles
npm http 304 http://192.168.1.100:4873/hoek
npm http 200 http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/jsprim
npm http request GET http://192.168.1.100:4873/sshpk
npm http 304 http://192.168.1.100:4873/jsprim
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 304 http://192.168.1.100:4873/sshpk
npm http request GET http://192.168.1.100:4873/extsprintf
npm http request GET http://192.168.1.100:4873/json-schema
npm http request GET http://192.168.1.100:4873/verror
npm http 304 http://192.168.1.100:4873/verror
npm http 200 http://192.168.1.100:4873/extsprintf
npm http 200 http://192.168.1.100:4873/json-schema
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/dashdash
npm http request GET http://192.168.1.100:4873/getpass
npm http 304 http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/getpass
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
npm http 200 http://192.168.1.100:4873/xmlhttprequest-cookie
npm http request GET http://192.168.1.100:4873/xmlhttprequest
npm http 304 http://192.168.1.100:4873/xmlhttprequest
npm http request GET http://192.168.1.100:4873/pouchdb-changeslike-wrapper
npm http 200 http://192.168.1.100:4873/pouchdb-changeslike-wrapper
npm http request GET http://192.168.1.100:4873/couchdb-objects
npm http request GET http://192.168.1.100:4873/couchdb-eval
npm http request GET http://192.168.1.100:4873/random-uuid-v4
npm http 200 http://192.168.1.100:4873/random-uuid-v4
npm http 200 http://192.168.1.100:4873/couchdb-eval
npm http 200 http://192.168.1.100:4873/couchdb-objects
npm http request GET http://192.168.1.100:4873/is-empty
npm http 200 http://192.168.1.100:4873/is-empty
npm http request GET http://192.168.1.100:4873/jshint
npm http request GET http://192.168.1.100:4873/pouchdb-abstract-mapreduce
npm http request GET http://192.168.1.100:4873/pouchdb-extend
npm http request GET http://192.168.1.100:4873/pouchdb-upsert
npm http request GET http://192.168.1.100:4873/spark-md5
npm http 304 http://192.168.1.100:4873/spark-md5
npm http 304 http://192.168.1.100:4873/pouchdb-abstract-mapreduce
npm http 304 http://192.168.1.100:4873/jshint
npm http 200 http://192.168.1.100:4873/pouchdb-upsert
npm http 200 http://192.168.1.100:4873/pouchdb-extend
npm http request GET http://192.168.1.100:4873/cli
npm http request GET http://192.168.1.100:4873/console-browserify
npm http request GET http://192.168.1.100:4873/exit
npm http request GET http://192.168.1.100:4873/htmlparser2
npm http request GET http://192.168.1.100:4873/shelljs
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/console-browserify
npm http 304 http://192.168.1.100:4873/htmlparser2
npm http 304 http://192.168.1.100:4873/cli
npm http 304 http://192.168.1.100:4873/shelljs
npm http 200 http://192.168.1.100:4873/exit
npm http 304 http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/strip-json-comments
npm http 304 http://192.168.1.100:4873/minimatch
npm WARN deprecated minimatch@2.0.10: Please update to minimatch 3.0.2 or higher to avoid a RegExp DoS issue
npm http request GET http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/glob
npm WARN deprecated minimatch@0.3.0: Please update to minimatch 3.0.2 or higher to avoid a RegExp DoS issue
npm http request GET http://192.168.1.100:4873/sigmund
npm http request GET http://192.168.1.100:4873/lru-cache
npm http 304 http://192.168.1.100:4873/lru-cache
npm http 304 http://192.168.1.100:4873/sigmund
npm http request GET http://192.168.1.100:4873/date-now
npm http 304 http://192.168.1.100:4873/date-now
npm http request GET http://192.168.1.100:4873/domhandler
npm http request GET http://192.168.1.100:4873/domutils
npm http request GET http://192.168.1.100:4873/domelementtype
npm http request GET http://192.168.1.100:4873/entities
npm http 304 http://192.168.1.100:4873/entities
npm http 304 http://192.168.1.100:4873/domhandler
npm http 304 http://192.168.1.100:4873/domelementtype
npm http 200 http://192.168.1.100:4873/domutils
npm http request GET http://192.168.1.100:4873/dom-serializer
npm http 304 http://192.168.1.100:4873/dom-serializer
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/ctype
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
npm http request GET http://192.168.1.100:4873/fs-extra
npm http 304 http://192.168.1.100:4873/fs-extra
npm http request GET http://192.168.1.100:4873/jsonfile
npm http request GET http://192.168.1.100:4873/rimraf
npm http 304 http://192.168.1.100:4873/jsonfile
npm http 304 http://192.168.1.100:4873/rimraf
npm http request GET http://192.168.1.100:4873/fs.realpath
npm http 304 http://192.168.1.100:4873/fs.realpath
npm http request GET http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/fast-future
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http 304 http://192.168.1.100:4873/bindings
npm http 304 http://192.168.1.100:4873/abstract-leveldown
npm http 304 http://192.168.1.100:4873/fast-future
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/varint
npm http 304 http://192.168.1.100:4873/varint
npm http 304 http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/stream-shift
npm http 304 http://192.168.1.100:4873/stream-shift
npm http 304 http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http 304 http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/deep-equal
npm http request GET http://192.168.1.100:4873/debug
npm WARN deprecated lodash@2.4.1: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
npm http request GET http://192.168.1.100:4873/propagate
npm http request GET http://192.168.1.100:4873/chai
npm http 304 http://192.168.1.100:4873/propagate
npm http 304 http://192.168.1.100:4873/chai
npm http 304 http://192.168.1.100:4873/debug
npm http 200 http://192.168.1.100:4873/deep-equal
npm http request GET http://192.168.1.100:4873/type-detect
npm http request GET http://192.168.1.100:4873/deep-eql
npm http request GET http://192.168.1.100:4873/assertion-error
npm http 304 http://192.168.1.100:4873/type-detect
npm http 200 http://192.168.1.100:4873/assertion-error
npm http 304 http://192.168.1.100:4873/deep-eql
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/ip
npm http 304 http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-http
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-leveldb
npm http request GET http://192.168.1.100:4873/pouchdb-core
npm http request GET http://192.168.1.100:4873/pouchdb-replication
npm http request GET http://192.168.1.100:4873/pouchdb-mapreduce
npm http 304 http://192.168.1.100:4873/pouchdb-mapreduce
npm http fetch GET http://192.168.1.100:4873/pouchdb-mapreduce/-/pouchdb-mapreduce-5.4.4.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-mapreduce/-/pouchdb-mapreduce-5.4.4.tgz
npm http 304 http://192.168.1.100:4873/pouchdb-core
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-leveldb
npm http fetch GET http://192.168.1.100:4873/pouchdb-core/-/pouchdb-core-5.4.4.tgz
npm http fetch GET http://192.168.1.100:4873/pouchdb-adapter-leveldb/-/pouchdb-adapter-leveldb-5.4.4.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-core/-/pouchdb-core-5.4.4.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-adapter-leveldb/-/pouchdb-adapter-leveldb-5.4.4.tgz
npm http 304 http://192.168.1.100:4873/pouchdb-replication
npm http fetch GET http://192.168.1.100:4873/pouchdb-replication/-/pouchdb-replication-5.4.4.tgz
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-http
npm http fetch 200 http://192.168.1.100:4873/pouchdb-replication/-/pouchdb-replication-5.4.4.tgz
npm http fetch GET http://192.168.1.100:4873/pouchdb-adapter-http/-/pouchdb-adapter-http-5.4.4.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-adapter-http/-/pouchdb-adapter-http-5.4.4.tgz
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/pouchdb-binary-utils
npm http request GET http://192.168.1.100:4873/pouchdb-ajax
npm http request GET http://192.168.1.100:4873/pouchdb-errors
npm http request GET http://192.168.1.100:4873/pouchdb-md5
npm http request GET http://192.168.1.100:4873/pouchdb-utils
npm http 304 http://192.168.1.100:4873/pouchdb-promise
npm http fetch GET http://192.168.1.100:4873/pouchdb-promise/-/pouchdb-promise-5.4.4.tgz
npm http 304 http://192.168.1.100:4873/pouchdb-ajax
npm http fetch 200 http://192.168.1.100:4873/pouchdb-promise/-/pouchdb-promise-5.4.4.tgz
npm http fetch GET http://192.168.1.100:4873/pouchdb-ajax/-/pouchdb-ajax-5.4.4.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-ajax/-/pouchdb-ajax-5.4.4.tgz
npm http 304 http://192.168.1.100:4873/pouchdb-binary-utils
npm http 304 http://192.168.1.100:4873/pouchdb-errors
npm http 304 http://192.168.1.100:4873/pouchdb-utils
npm http 304 http://192.168.1.100:4873/pouchdb-md5
npm http fetch GET http://192.168.1.100:4873/pouchdb-binary-utils/-/pouchdb-binary-utils-5.4.4.tgz
npm http fetch GET http://192.168.1.100:4873/pouchdb-errors/-/pouchdb-errors-5.4.4.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-binary-utils/-/pouchdb-binary-utils-5.4.4.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-errors/-/pouchdb-errors-5.4.4.tgz
npm http fetch GET http://192.168.1.100:4873/pouchdb-utils/-/pouchdb-utils-5.4.4.tgz
npm http fetch GET http://192.168.1.100:4873/pouchdb-md5/-/pouchdb-md5-5.4.4.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-utils/-/pouchdb-utils-5.4.4.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-md5/-/pouchdb-md5-5.4.4.tgz
npm http request GET http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/leveldown
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-leveldb-core
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-leveldb-core
npm http fetch GET http://192.168.1.100:4873/pouchdb-adapter-leveldb-core/-/pouchdb-adapter-leveldb-core-5.4.4.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-adapter-leveldb-core/-/pouchdb-adapter-leveldb-core-5.4.4.tgz
npm http 200 http://192.168.1.100:4873/leveldown
npm http request GET http://192.168.1.100:4873/nan
npm http request GET http://192.168.1.100:4873/prebuild
npm http 304 http://192.168.1.100:4873/nan
npm http 200 http://192.168.1.100:4873/prebuild
npm http request GET http://192.168.1.100:4873/expand-template
npm http request GET http://192.168.1.100:4873/ghreleases
npm http request GET http://192.168.1.100:4873/github-from-package
npm http request GET http://192.168.1.100:4873/node-gyp
npm http request GET http://192.168.1.100:4873/node-ninja
npm http request GET http://192.168.1.100:4873/noop-logger
npm http request GET http://192.168.1.100:4873/npmlog
npm http request GET http://192.168.1.100:4873/os-homedir
npm http request GET http://192.168.1.100:4873/pump
npm http request GET http://192.168.1.100:4873/rc
npm http request GET http://192.168.1.100:4873/simple-get
npm http request GET http://192.168.1.100:4873/tar-fs
npm http request GET http://192.168.1.100:4873/tar-stream
npm http 200 http://192.168.1.100:4873/node-gyp
npm http 200 http://192.168.1.100:4873/node-ninja
npm http 200 http://192.168.1.100:4873/expand-template
npm http 200 http://192.168.1.100:4873/github-from-package
npm http 304 http://192.168.1.100:4873/npmlog
npm http 200 http://192.168.1.100:4873/os-homedir
npm http 304 http://192.168.1.100:4873/pump
npm http 304 http://192.168.1.100:4873/tar-fs
npm http 200 http://192.168.1.100:4873/ghreleases
npm http 200 http://192.168.1.100:4873/rc
npm http 200 http://192.168.1.100:4873/noop-logger
npm http 304 http://192.168.1.100:4873/tar-stream
npm http 200 http://192.168.1.100:4873/simple-get
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/ghrepos
npm http request GET http://192.168.1.100:4873/ghutils
npm http request GET http://192.168.1.100:4873/simple-mime
npm http request GET http://192.168.1.100:4873/url-template
npm http 304 http://192.168.1.100:4873/after
npm http 304 http://192.168.1.100:4873/ghutils
npm http 304 http://192.168.1.100:4873/url-template
npm http 304 http://192.168.1.100:4873/ghrepos
npm http 304 http://192.168.1.100:4873/simple-mime
npm http request GET http://192.168.1.100:4873/jsonist
npm http 304 http://192.168.1.100:4873/jsonist
npm http request GET http://192.168.1.100:4873/hyperquest
npm http 304 http://192.168.1.100:4873/hyperquest
npm http request GET http://192.168.1.100:4873/duplexer2
npm http 304 http://192.168.1.100:4873/duplexer2
npm http request GET http://192.168.1.100:4873/fstream
npm http request GET http://192.168.1.100:4873/nopt
npm http request GET http://192.168.1.100:4873/osenv
npm http request GET http://192.168.1.100:4873/path-array
npm http request GET http://192.168.1.100:4873/tar
npm http request GET http://192.168.1.100:4873/which
npm http request GET http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/fstream
npm http 304 http://192.168.1.100:4873/nopt
npm http 304 http://192.168.1.100:4873/which
npm http 304 http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/path-array
npm http 200 http://192.168.1.100:4873/osenv
npm http 304 http://192.168.1.100:4873/tar
npm http request GET http://192.168.1.100:4873/abbrev
npm http 304 http://192.168.1.100:4873/abbrev
npm http request GET http://192.168.1.100:4873/ansi
npm http request GET http://192.168.1.100:4873/are-we-there-yet
npm http request GET http://192.168.1.100:4873/gauge
npm http 304 http://192.168.1.100:4873/gauge
npm http 304 http://192.168.1.100:4873/ansi
npm http 200 http://192.168.1.100:4873/are-we-there-yet
npm http request GET http://192.168.1.100:4873/delegates
npm http 304 http://192.168.1.100:4873/delegates
npm http request GET http://192.168.1.100:4873/has-unicode
npm http request GET http://192.168.1.100:4873/lodash.pad
npm http request GET http://192.168.1.100:4873/lodash.padend
npm http request GET http://192.168.1.100:4873/lodash.padstart
npm http 304 http://192.168.1.100:4873/lodash.pad
npm http 304 http://192.168.1.100:4873/has-unicode
npm http 200 http://192.168.1.100:4873/lodash.padend
npm http 200 http://192.168.1.100:4873/lodash.padstart
npm http request GET http://192.168.1.100:4873/os-tmpdir
npm http 304 http://192.168.1.100:4873/os-tmpdir
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
npm http request GET http://192.168.1.100:4873/block-stream
npm http 304 http://192.168.1.100:4873/block-stream
npm http request GET http://192.168.1.100:4873/isexe
npm http 304 http://192.168.1.100:4873/isexe
npm http request GET http://192.168.1.100:4873/deep-extend
npm http request GET http://192.168.1.100:4873/ini
npm http 304 http://192.168.1.100:4873/ini
npm http 304 http://192.168.1.100:4873/deep-extend
npm WARN engine deep-extend@0.4.1: wanted: {"node":">=0.12.0","iojs":">=1.0.0"} (current: {"node":"0.10.40","npm":"3.3.12"})
npm http request GET http://192.168.1.100:4873/unzip-response
npm http 304 http://192.168.1.100:4873/unzip-response
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/pouchdb-json
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-utils
npm http request GET http://192.168.1.100:4873/pouchdb-merge
npm http 304 http://192.168.1.100:4873/through2
npm http 304 http://192.168.1.100:4873/pouchdb-json
npm http fetch GET http://192.168.1.100:4873/pouchdb-json/-/pouchdb-json-5.4.4.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-json/-/pouchdb-json-5.4.4.tgz
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-utils
npm http fetch GET http://192.168.1.100:4873/pouchdb-adapter-utils/-/pouchdb-adapter-utils-5.4.4.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-adapter-utils/-/pouchdb-adapter-utils-5.4.4.tgz
npm http 304 http://192.168.1.100:4873/pouchdb-merge
npm http fetch GET http://192.168.1.100:4873/pouchdb-merge/-/pouchdb-merge-5.4.4.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-merge/-/pouchdb-merge-5.4.4.tgz
npm http request GET http://192.168.1.100:4873/pouchdb-mapreduce-utils
npm http 304 http://192.168.1.100:4873/pouchdb-mapreduce-utils
npm http fetch GET http://192.168.1.100:4873/pouchdb-mapreduce-utils/-/pouchdb-mapreduce-utils-5.4.4.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-mapreduce-utils/-/pouchdb-mapreduce-utils-5.4.4.tgz
npm http request GET http://192.168.1.100:4873/pouchdb-checkpointer
npm http request GET http://192.168.1.100:4873/pouchdb-generate-replication-id
npm http 304 http://192.168.1.100:4873/pouchdb-generate-replication-id
npm http fetch GET http://192.168.1.100:4873/pouchdb-generate-replication-id/-/pouchdb-generate-replication-id-5.4.4.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-generate-replication-id/-/pouchdb-generate-replication-id-5.4.4.tgz
npm http 304 http://192.168.1.100:4873/pouchdb-checkpointer
npm http fetch GET http://192.168.1.100:4873/pouchdb-checkpointer/-/pouchdb-checkpointer-5.4.4.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-checkpointer/-/pouchdb-checkpointer-5.4.4.tgz
npm http request GET http://192.168.1.100:4873/module-not-found-error
npm http request GET http://192.168.1.100:4873/fill-keys
npm http 200 http://192.168.1.100:4873/fill-keys
npm http 200 http://192.168.1.100:4873/module-not-found-error
npm http request GET http://192.168.1.100:4873/is-object
npm http 200 http://192.168.1.100:4873/is-object
npm http request GET http://192.168.1.100:4873/array-uniq
npm http 304 http://192.168.1.100:4873/array-uniq
npm http request GET http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/jsonschema
npm http request GET http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/jsonschema
npm http request GET http://192.168.1.100:4873/formatio
npm http request GET http://192.168.1.100:4873/samsam
npm http request GET http://192.168.1.100:4873/lolex
npm http request GET http://192.168.1.100:4873/util
npm http 304 http://192.168.1.100:4873/formatio
npm http 304 http://192.168.1.100:4873/util
npm http 304 http://192.168.1.100:4873/samsam
npm http 304 http://192.168.1.100:4873/lolex
npm http request GET http://192.168.1.100:4873/engine.io-client
npm http request GET http://192.168.1.100:4873/component-emitter
npm http request GET http://192.168.1.100:4873/object-component
npm http request GET http://192.168.1.100:4873/component-bind
npm http request GET http://192.168.1.100:4873/socket.io-parser
npm http request GET http://192.168.1.100:4873/has-binary
npm http request GET http://192.168.1.100:4873/indexof
npm http request GET http://192.168.1.100:4873/parseuri
npm http request GET http://192.168.1.100:4873/to-array
npm http request GET http://192.168.1.100:4873/backo2
npm http request GET http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/engine.io-client
npm http 304 http://192.168.1.100:4873/component-bind
npm http 304 http://192.168.1.100:4873/component-emitter
npm http 304 http://192.168.1.100:4873/object-component
npm http 304 http://192.168.1.100:4873/socket.io-parser
npm http 304 http://192.168.1.100:4873/has-binary
npm http 304 http://192.168.1.100:4873/to-array
npm http 304 http://192.168.1.100:4873/indexof
npm http 304 http://192.168.1.100:4873/parseuri
npm http 200 http://192.168.1.100:4873/backo2
npm http 304 http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/parseqs
npm http request GET http://192.168.1.100:4873/ws
npm http fetch GET https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http 304 http://192.168.1.100:4873/has-cors
npm http 304 http://192.168.1.100:4873/component-inherit
npm http 304 http://192.168.1.100:4873/parsejson
npm http 304 http://192.168.1.100:4873/engine.io-parser
npm http 304 http://192.168.1.100:4873/parseqs
npm http 304 http://192.168.1.100:4873/ws
npm http fetch 200 https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/utf8
npm http 304 http://192.168.1.100:4873/utf8
npm http 304 http://192.168.1.100:4873/blob
npm http 304 http://192.168.1.100:4873/arraybuffer.slice
npm http 200 http://192.168.1.100:4873/base64-arraybuffer
npm http fetch GET https://github.com/component/global/archive/v2.0.1.tar.gz
npm http fetch 200 https://github.com/component/global/archive/v2.0.1.tar.gz
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
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/reduce-component
npm http request GET http://192.168.1.100:4873/cookiejar
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/formidable
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/reduce-component
npm http 200 http://192.168.1.100:4873/cookiejar
npm http 304 http://192.168.1.100:4873/form-data
npm http 200 http://192.168.1.100:4873/formidable
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/mime-types
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/mime-db
npm http 304 http://192.168.1.100:4873/mime-db
npm http request GET http://192.168.1.100:4873/defined
npm http request GET http://192.168.1.100:4873/resumer
npm http request GET http://192.168.1.100:4873/object-inspect
npm http 304 http://192.168.1.100:4873/object-inspect
npm http 200 http://192.168.1.100:4873/defined
npm http 304 http://192.168.1.100:4873/resumer
npm WARN prefer global jshint@2.9.2 should be installed with -g
npm WARN prefer global node-ninja@1.0.2 should be installed with -g
npm WARN prefer global node-gyp@3.4.0 should be installed with -g
gyp JXcore NODE-GYP Using node-gyp bundled in npm coming from JXcore
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
Using a callback for new PouchDB()is deprecated.
Using a callback for new PouchDB()is deprecated.
Using a callback for new PouchDB()is deprecated.
Using a callback for new PouchDB()is deprecated.
Using a callback for new PouchDB()is deprecated.
Using a callback for new PouchDB()is deprecated.
Using a callback for new PouchDB()is deprecated.
Using a callback for new PouchDB()is deprecated.
Using a callback for new PouchDB()is deprecated.
Using a callback for new PouchDB()is deprecated.
Using a callback for new PouchDB()is deprecated.
Using a callback for new PouchDB()is deprecated.

```

Error: Command failed: npm http request GET http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/socket.io
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/fs-extra-promise
npm http request GET http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/fs-extra-promise
npm http 200 http://192.168.1.100:4873/socket.io
npm http 200 http://192.168.1.100:4873/express
npm http 200 http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/content-disposition
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/array-flatten
npm http request GET http://192.168.1.100:4873/cookie
npm http request GET http://192.168.1.100:4873/accepts
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/escape-html
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/parseurl
npm http request GET http://192.168.1.100:4873/proxy-addr
npm http request GET http://192.168.1.100:4873/finalhandler
npm http request GET http://192.168.1.100:4873/etag
npm http request GET http://192.168.1.100:4873/merge-descriptors
npm http request GET http://192.168.1.100:4873/path-to-regexp
npm http request GET http://192.168.1.100:4873/fresh
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/cookie-signature
npm http request GET http://192.168.1.100:4873/vary
npm http request GET http://192.168.1.100:4873/send
npm http request GET http://192.168.1.100:4873/utils-merge
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/range-parser
npm http request GET http://192.168.1.100:4873/serve-static
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/accepts
npm http 200 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/escape-html
npm http 200 http://192.168.1.100:4873/methods
npm http 200 http://192.168.1.100:4873/on-finished
npm http 200 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 200 http://192.168.1.100:4873/etag
npm http 200 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 200 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/depd
npm http 200 http://192.168.1.100:4873/vary
npm http 200 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/send
npm http 200 http://192.168.1.100:4873/type-is
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/utils-merge
npm http 200 http://192.168.1.100:4873/qs
npm http 200 http://192.168.1.100:4873/serve-static
npm http request GET http://192.168.1.100:4873/mime-types
npm http request GET http://192.168.1.100:4873/negotiator
npm http 304 http://192.168.1.100:4873/mime-types
npm http 200 http://192.168.1.100:4873/negotiator
npm http request GET http://192.168.1.100:4873/mime-db
npm http 200 http://192.168.1.100:4873/mime-db
npm http request GET http://192.168.1.100:4873/ms
npm http 200 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/unpipe
npm http 200 http://192.168.1.100:4873/unpipe
npm http request GET http://192.168.1.100:4873/ee-first
npm http 200 http://192.168.1.100:4873/ee-first
npm http request GET http://192.168.1.100:4873/forwarded
npm http request GET http://192.168.1.100:4873/ipaddr.js
npm http 200 http://192.168.1.100:4873/forwarded
npm http 200 http://192.168.1.100:4873/ipaddr.js
npm http request GET http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/statuses
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/mime
npm http 304 http://192.168.1.100:4873/statuses
npm http 304 http://192.168.1.100:4873/http-errors
npm http 200 http://192.168.1.100:4873/destroy
npm http 200 http://192.168.1.100:4873/mime
npm http request GET http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/media-typer
npm http 200 http://192.168.1.100:4873/media-typer
npm http request GET http://192.168.1.100:4873/fs-extra
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/fs-extra
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/jsonfile
npm http request GET http://192.168.1.100:4873/rimraf
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http 304 http://192.168.1.100:4873/rimraf
npm http 200 http://192.168.1.100:4873/jsonfile
npm http request GET http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/fs.realpath
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/fs.realpath
npm http 304 http://192.168.1.100:4873/inflight
npm http 200 http://192.168.1.100:4873/path-is-absolute
npm http 200 http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/wrappy
npm http 304 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 304 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/immediate
npm http 200 http://192.168.1.100:4873/es3ify
npm http 200 http://192.168.1.100:4873/immediate
npm http 200 http://192.168.1.100:4873/inline-process-browser
npm http 200 http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/through
npm http request GET http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/esprima
npm http 304 http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/esprima
npm http 200 http://192.168.1.100:4873/through
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/base62
npm http 200 http://192.168.1.100:4873/commoner
npm http 200 http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/recast
npm http 200 http://192.168.1.100:4873/private
npm http 200 http://192.168.1.100:4873/mkdirp
npm http 200 http://192.168.1.100:4873/commander
npm http 200 http://192.168.1.100:4873/detective
npm http 200 http://192.168.1.100:4873/iconv-lite
npm http 200 http://192.168.1.100:4873/recast
npm http 200 http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http 304 http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/defined
npm http request GET http://192.168.1.100:4873/acorn
npm http 200 http://192.168.1.100:4873/defined
npm http 200 http://192.168.1.100:4873/acorn
npm http request GET http://192.168.1.100:4873/minimist
npm http 304 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/ast-types
npm http 200 http://192.168.1.100:4873/ast-types
npm http request GET http://192.168.1.100:4873/amdefine
npm http 200 http://192.168.1.100:4873/amdefine
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/falafel
npm http 304 http://192.168.1.100:4873/through2
npm http 200 http://192.168.1.100:4873/falafel
npm http request GET http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/foreach
npm http 304 http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/object-keys
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
npm http request GET http://192.168.1.100:4873/socket.io-parser
npm http request GET http://192.168.1.100:4873/has-binary-data
npm http request GET http://192.168.1.100:4873/socket.io-adapter
npm http request GET http://192.168.1.100:4873/engine.io
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http 304 http://192.168.1.100:4873/has-binary-data
npm http 304 http://192.168.1.100:4873/engine.io
npm http 304 http://192.168.1.100:4873/socket.io-adapter
npm http 200 http://192.168.1.100:4873/socket.io-parser
npm http 200 http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/base64id
npm http request GET http://192.168.1.100:4873/ws
npm http 200 http://192.168.1.100:4873/base64id
npm http 304 http://192.168.1.100:4873/engine.io-parser
npm http 200 http://192.168.1.100:4873/ws
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/utf8
npm http request GET http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/has-binary
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http 200 http://192.168.1.100:4873/blob
npm http 304 http://192.168.1.100:4873/has-binary
npm http 304 http://192.168.1.100:4873/after
npm http 200 http://192.168.1.100:4873/utf8
npm http 200 http://192.168.1.100:4873/base64-arraybuffer
npm http 200 http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/ultron
npm http request GET http://192.168.1.100:4873/bufferutil
npm http request GET http://192.168.1.100:4873/options
npm http request GET http://192.168.1.100:4873/utf-8-validate
npm http 304 http://192.168.1.100:4873/options
npm http 200 http://192.168.1.100:4873/bufferutil
npm http 200 http://192.168.1.100:4873/utf-8-validate
npm http 304 http://192.168.1.100:4873/ultron
npm http request GET http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/nan
npm http 304 http://192.168.1.100:4873/bindings
npm http 304 http://192.168.1.100:4873/nan
npm http request GET http://192.168.1.100:4873/benchmark
npm http request GET http://192.168.1.100:4873/component-emitter
npm http request GET http://192.168.1.100:4873/json3
npm http 304 http://192.168.1.100:4873/component-emitter
npm http 304 http://192.168.1.100:4873/benchmark
npm http 304 http://192.168.1.100:4873/json3
npm http request GET http://192.168.1.100:4873/backo2
npm http request GET http://192.168.1.100:4873/to-array
npm http request GET http://192.168.1.100:4873/indexof
npm http request GET http://192.168.1.100:4873/parseuri
npm http request GET http://192.168.1.100:4873/object-component
npm http request GET http://192.168.1.100:4873/component-bind
npm http request GET http://192.168.1.100:4873/engine.io-client
npm http 304 http://192.168.1.100:4873/indexof
npm http 304 http://192.168.1.100:4873/to-array
npm http 304 http://192.168.1.100:4873/parseuri
npm http 200 http://192.168.1.100:4873/backo2
npm http 200 http://192.168.1.100:4873/object-component
npm http 200 http://192.168.1.100:4873/component-bind
npm http 304 http://192.168.1.100:4873/engine.io-client
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/parseqs
npm http fetch GET https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/has-cors
npm http 304 http://192.168.1.100:4873/parseqs
npm http 200 http://192.168.1.100:4873/parsejson
npm http 200 http://192.168.1.100:4873/component-inherit
npm http fetch 200 https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http fetch GET https://github.com/component/global/archive/v2.0.1.tar.gz
npm http fetch 200 https://github.com/component/global/archive/v2.0.1.tar.gz
npm http request GET http://192.168.1.100:4873/better-assert
npm http 304 http://192.168.1.100:4873/better-assert
npm http request GET http://192.168.1.100:4873/callsite
npm http 200 http://192.168.1.100:4873/callsite
npm http request GET http://192.168.1.100:4873/pkginfo
npm http request GET http://192.168.1.100:4873/cycle
npm http request GET http://192.168.1.100:4873/colors
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/stack-trace
npm http 304 http://192.168.1.100:4873/pkginfo
npm http 304 http://192.168.1.100:4873/cycle
npm http 200 http://192.168.1.100:4873/colors
npm http 200 http://192.168.1.100:4873/eyes
npm http 200 http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/stack-trace
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/tape
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 200 http://192.168.1.100:4873/tape
npm http request GET http://192.168.1.100:4873/jsonify
npm http request GET http://192.168.1.100:4873/deep-equal
npm http 200 http://192.168.1.100:4873/jsonify
npm http 200 http://192.168.1.100:4873/deep-equal
gyp JXcore NODE-GYP Using node-gyp bundled in npm coming from JXcore
In file included from ../src/bufferutil.cc:10:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
1 warning generated.
gyp JXcore NODE-GYP Using node-gyp bundled in npm coming from JXcore
In file included from ../src/validation.cc:10:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
1 warning generated.
npm WARN EPACKAGEJSON thali-test-server@0.0.1 No repository field.
npm WARN EPACKAGEJSON thali-test-server@0.0.1 No license field.
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/express-pouchdb
npm http request GET http://192.168.1.100:4873/forever-agent
npm http request GET http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/javascript-state-machine
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/js-extend
npm http 304 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/ip
npm http 304 http://192.168.1.100:4873/forever-agent
npm http 304 http://192.168.1.100:4873/lie
npm http 304 http://192.168.1.100:4873/express-pouchdb
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/winston
npm http fetch GET http://192.168.1.100:4873/express-pouchdb/-/express-pouchdb-1.0.4.tgz
npm http 200 http://192.168.1.100:4873/javascript-state-machine
npm http 200 http://192.168.1.100:4873/js-extend
npm http 304 http://192.168.1.100:4873/multiplex
npm http fetch 200 http://192.168.1.100:4873/express-pouchdb/-/express-pouchdb-1.0.4.tgz
npm http 200 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/http-errors
npm http 200 http://192.168.1.100:4873/bytes
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
npm http 304 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/fresh
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
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/basic-auth
npm http request GET http://192.168.1.100:4873/compression
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/pouchdb-all-dbs
npm http request GET http://192.168.1.100:4873/pouchdb-auth
npm http request GET http://192.168.1.100:4873/multiparty
npm http request GET http://192.168.1.100:4873/header-case-normalizer
npm http request GET http://192.168.1.100:4873/cookie-parser
npm http request GET http://192.168.1.100:4873/pouchdb-find
npm http request GET http://192.168.1.100:4873/pouchdb-size
npm http request GET http://192.168.1.100:4873/pouchdb-update
npm http request GET http://192.168.1.100:4873/pouchdb-show
npm http request GET http://192.168.1.100:4873/pouchdb-security
npm http request GET http://192.168.1.100:4873/pouchdb-replicator
npm http request GET http://192.168.1.100:4873/pouchdb-rewrite
npm http request GET http://192.168.1.100:4873/pouchdb-list
npm http request GET http://192.168.1.100:4873/pouchdb-validation
npm http request GET http://192.168.1.100:4873/pouchdb-vhost
npm http request GET http://192.168.1.100:4873/pouchdb-wrappers
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/compression
npm http 200 http://192.168.1.100:4873/basic-auth
npm http fetch GET http://192.168.1.100:4873/bluebird/-/bluebird-3.3.4.tgz
npm http 304 http://192.168.1.100:4873/multiparty
npm http 304 http://192.168.1.100:4873/pouchdb-all-dbs
npm http 304 http://192.168.1.100:4873/cookie-parser
npm http 200 http://192.168.1.100:4873/pouchdb-auth
npm http 200 http://192.168.1.100:4873/header-case-normalizer
npm http 200 http://192.168.1.100:4873/pouchdb-security
npm http 304 http://192.168.1.100:4873/pouchdb-size
npm http 304 http://192.168.1.100:4873/pouchdb-show
npm http 304 http://192.168.1.100:4873/pouchdb-update
npm http 200 http://192.168.1.100:4873/pouchdb-validation
npm http 304 http://192.168.1.100:4873/pouchdb-rewrite
npm http 304 http://192.168.1.100:4873/pouchdb-replicator
npm http fetch 200 http://192.168.1.100:4873/bluebird/-/bluebird-3.3.4.tgz
npm http 200 http://192.168.1.100:4873/pouchdb-wrappers
npm http 304 http://192.168.1.100:4873/pouchdb-find
npm http 304 http://192.168.1.100:4873/pouchdb-list
npm http 304 http://192.168.1.100:4873/pouchdb-vhost
npm http request GET http://192.168.1.100:4873/on-headers
npm http request GET http://192.168.1.100:4873/compressible
npm http 200 http://192.168.1.100:4873/on-headers
npm http 304 http://192.168.1.100:4873/compressible
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/stream-counter
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/stream-counter
npm http request GET http://192.168.1.100:4873/core-util-is
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/string_decoder
npm http 304 http://192.168.1.100:4873/core-util-is
npm http 304 http://192.168.1.100:4873/string_decoder
npm http 304 http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/tiny-queue
npm http request GET http://192.168.1.100:4873/argsarray
npm http 304 http://192.168.1.100:4873/es3ify
npm http 200 http://192.168.1.100:4873/argsarray
npm http 200 http://192.168.1.100:4873/tiny-queue
npm http request GET http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/through
npm http 304 http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/through
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/amdefine
npm http 304 http://192.168.1.100:4873/amdefine
npm http request GET http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 304 http://192.168.1.100:4873/immediate
npm http 304 http://192.168.1.100:4873/inline-process-browser
npm http 304 http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/falafel
npm http request GET http://192.168.1.100:4873/through2
npm http 304 http://192.168.1.100:4873/falafel
npm http 304 http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/acorn
npm http request GET http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/acorn
npm http 304 http://192.168.1.100:4873/foreach
npm http 304 http://192.168.1.100:4873/object-keys
npm http request GET http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/esmangle-evaluator
npm http request GET http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/esmangle-evaluator
npm http 304 http://192.168.1.100:4873/recast
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/ast-types
npm http 304 http://192.168.1.100:4873/ast-types
npm http 304 http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/crypto-lite
npm http request GET http://192.168.1.100:4873/base64url
npm http request GET http://192.168.1.100:4873/couchdb-calculate-session-id
npm http request GET http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http request GET http://192.168.1.100:4873/pouchdb-req-http-query
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/pouchdb-plugin-error
npm http request GET http://192.168.1.100:4873/promise-nodify
npm http request GET http://192.168.1.100:4873/pouchdb-system-db
npm http request GET http://192.168.1.100:4873/secure-random
npm http request GET http://192.168.1.100:4873/pouchdb
npm http 200 http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http 200 http://192.168.1.100:4873/couchdb-calculate-session-id
npm http 304 http://192.168.1.100:4873/base64url
npm http 200 http://192.168.1.100:4873/crypto-lite
npm http 200 http://192.168.1.100:4873/pouchdb-req-http-query
npm http 200 http://192.168.1.100:4873/pouchdb-promise
npm http 200 http://192.168.1.100:4873/promise-nodify
npm http 200 http://192.168.1.100:4873/pouchdb-plugin-error
npm http 200 http://192.168.1.100:4873/secure-random
npm http 200 http://192.168.1.100:4873/pouchdb-system-db
npm http fetch GET http://192.168.1.100:4873/pouchdb-promise/-/pouchdb-promise-5.4.5.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-promise/-/pouchdb-promise-5.4.5.tgz
npm http 200 http://192.168.1.100:4873/pouchdb
npm http request GET http://192.168.1.100:4873/meow
npm http request GET http://192.168.1.100:4873/concat-stream
npm http 200 http://192.168.1.100:4873/meow
npm http 200 http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/typedarray
npm http 304 http://192.168.1.100:4873/typedarray
npm http request GET http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/camelcase-keys
npm http request GET http://192.168.1.100:4873/indent-string
npm http 304 http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/minimist
npm http 200 http://192.168.1.100:4873/camelcase-keys
npm http 200 http://192.168.1.100:4873/indent-string
npm http request GET http://192.168.1.100:4873/camelcase
npm http request GET http://192.168.1.100:4873/map-obj
npm http 304 http://192.168.1.100:4873/map-obj
npm http 200 http://192.168.1.100:4873/camelcase
npm http request GET http://192.168.1.100:4873/get-stdin
npm http request GET http://192.168.1.100:4873/repeating
npm http 200 http://192.168.1.100:4873/get-stdin
npm http 304 http://192.168.1.100:4873/repeating
npm http request GET http://192.168.1.100:4873/is-finite
npm http 200 http://192.168.1.100:4873/is-finite
npm http request GET http://192.168.1.100:4873/number-is-nan
npm http 304 http://192.168.1.100:4873/number-is-nan
npm http request GET http://192.168.1.100:4873/aproba
npm http 200 http://192.168.1.100:4873/aproba
npm http request GET http://192.168.1.100:4873/memdown
npm http request GET http://192.168.1.100:4873/localstorage-down
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/level-write-stream
npm http request GET http://192.168.1.100:4873/es6-promise-pool
npm http request GET http://192.168.1.100:4873/fruitdown
npm http request GET http://192.168.1.100:4873/pouchdb-collate
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/scope-eval
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/vuvuzela
npm http 200 http://192.168.1.100:4873/memdown
npm http 200 http://192.168.1.100:4873/localstorage-down
npm http 200 http://192.168.1.100:4873/level-write-stream
npm http 200 http://192.168.1.100:4873/es6-promise-pool
npm http 200 http://192.168.1.100:4873/levelup
npm http 200 http://192.168.1.100:4873/fruitdown
npm http 200 http://192.168.1.100:4873/pouchdb-collections
npm http 200 http://192.168.1.100:4873/pouchdb-collate
npm http 304 http://192.168.1.100:4873/js-extend
npm http 304 http://192.168.1.100:4873/double-ended-queue
npm http 200 http://192.168.1.100:4873/scope-eval
npm http 200 http://192.168.1.100:4873/sublevel-pouchdb
npm http 200 http://192.168.1.100:4873/spark-md5
npm http 200 http://192.168.1.100:4873/vuvuzela
npm http request GET http://192.168.1.100:4873/d64
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http 200 http://192.168.1.100:4873/d64
npm http 200 http://192.168.1.100:4873/abstract-leveldown
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
npm http 304 http://192.168.1.100:4873/prr
npm http 200 http://192.168.1.100:4873/level-errors
npm http 200 http://192.168.1.100:4873/level-codec
npm http 200 http://192.168.1.100:4873/level-iterator-stream
npm http 200 http://192.168.1.100:4873/deferred-leveldown
npm http 304 http://192.168.1.100:4873/semver
npm http request GET http://192.168.1.100:4873/errno
npm http 200 http://192.168.1.100:4873/errno
npm http request GET http://192.168.1.100:4873/esprima
npm http 304 http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/commoner
npm http 304 http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/q
npm http 304 http://192.168.1.100:4873/commander
npm http 304 http://192.168.1.100:4873/detective
npm http 304 http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/q
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http 304 http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http 304 http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/defined
npm http 304 http://192.168.1.100:4873/defined
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/minimatch
npm http 304 http://192.168.1.100:4873/inflight
npm http 304 http://192.168.1.100:4873/once
npm http 200 http://192.168.1.100:4873/path-is-absolute
npm http request GET http://192.168.1.100:4873/wrappy
npm http 304 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 304 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/humble-localstorage
npm http 200 http://192.168.1.100:4873/humble-localstorage
npm http request GET http://192.168.1.100:4873/has-localstorage
npm http request GET http://192.168.1.100:4873/localstorage-memory
npm http 200 http://192.168.1.100:4873/localstorage-memory
npm http 200 http://192.168.1.100:4873/has-localstorage
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
npm http request GET http://192.168.1.100:4873/is-typedarray
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/caseless
npm http 200 http://192.168.1.100:4873/aws4
npm http 200 http://192.168.1.100:4873/aws-sign2
npm http 200 http://192.168.1.100:4873/combined-stream
npm http 200 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/is-typedarray
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/stringstream
npm http 200 http://192.168.1.100:4873/oauth-sign
npm http 200 http://192.168.1.100:4873/tunnel-agent
npm http 200 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/qs
npm WARN deprecated tough-cookie@2.2.2: ReDoS vulnerability parsing Set-Cookie https://nodesecurity.io/advisories/130
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/process-nextick-args
npm http 304 http://192.168.1.100:4873/util-deprecate
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/pinkie-promise
npm http 304 http://192.168.1.100:4873/pinkie-promise
npm http 304 http://192.168.1.100:4873/chalk
npm http 200 http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/ansi-styles
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/supports-color
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 200 http://192.168.1.100:4873/generate-object-property
npm http 200 http://192.168.1.100:4873/generate-function
npm http 200 http://192.168.1.100:4873/jsonpointer
npm http request GET http://192.168.1.100:4873/is-property
npm http 200 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/pinkie
npm http 304 http://192.168.1.100:4873/pinkie
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/boom
npm http 200 http://192.168.1.100:4873/hoek
npm http 304 http://192.168.1.100:4873/cryptiles
npm http 200 http://192.168.1.100:4873/sntp
npm http 200 http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/jsprim
npm http request GET http://192.168.1.100:4873/sshpk
npm http 304 http://192.168.1.100:4873/jsprim
npm http 304 http://192.168.1.100:4873/sshpk
npm http 304 http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/json-schema
npm http request GET http://192.168.1.100:4873/verror
npm http request GET http://192.168.1.100:4873/extsprintf
npm http 304 http://192.168.1.100:4873/verror
npm http 200 http://192.168.1.100:4873/json-schema
npm http 200 http://192.168.1.100:4873/extsprintf
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/dashdash
npm http request GET http://192.168.1.100:4873/getpass
npm http 304 http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/dashdash
npm http 200 http://192.168.1.100:4873/getpass
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/pull-stream
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 200 http://192.168.1.100:4873/pull-stream
npm http request GET http://192.168.1.100:4873/pull-core
npm http 200 http://192.168.1.100:4873/pull-core
npm http request GET http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/pouchdb-promise
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
npm http 200 http://192.168.1.100:4873/random-uuid-v4
npm http 200 http://192.168.1.100:4873/couchdb-eval
npm http 200 http://192.168.1.100:4873/couchdb-objects
npm http request GET http://192.168.1.100:4873/is-empty
npm http 200 http://192.168.1.100:4873/is-empty
npm http request GET http://192.168.1.100:4873/jshint
npm http request GET http://192.168.1.100:4873/pouchdb-abstract-mapreduce
npm http request GET http://192.168.1.100:4873/pouchdb-extend
npm http request GET http://192.168.1.100:4873/pouchdb-upsert
npm http 200 http://192.168.1.100:4873/pouchdb-extend
npm http 200 http://192.168.1.100:4873/pouchdb-upsert
npm http 200 http://192.168.1.100:4873/jshint
npm http fetch GET http://192.168.1.100:4873/jshint/-/jshint-2.9.2.tgz
npm http fetch 200 http://192.168.1.100:4873/jshint/-/jshint-2.9.2.tgz
npm http 200 http://192.168.1.100:4873/pouchdb-abstract-mapreduce
npm http request GET http://192.168.1.100:4873/cli
npm http request GET http://192.168.1.100:4873/console-browserify
npm http request GET http://192.168.1.100:4873/exit
npm http request GET http://192.168.1.100:4873/htmlparser2
npm http request GET http://192.168.1.100:4873/shelljs
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/lodash
npm WARN deprecated minimatch@2.0.10: Please update to minimatch 3.0.2 or higher to avoid a RegExp DoS issue
npm http 200 http://192.168.1.100:4873/cli
npm http 200 http://192.168.1.100:4873/exit
npm http 200 http://192.168.1.100:4873/console-browserify
npm http 200 http://192.168.1.100:4873/htmlparser2
npm http 200 http://192.168.1.100:4873/shelljs
npm http 304 http://192.168.1.100:4873/strip-json-comments
npm http 304 http://192.168.1.100:4873/lodash
npm WARN deprecated minimatch@0.3.0: Please update to minimatch 3.0.2 or higher to avoid a RegExp DoS issue
npm http request GET http://192.168.1.100:4873/lru-cache
npm http request GET http://192.168.1.100:4873/sigmund
npm http 200 http://192.168.1.100:4873/sigmund
npm http 200 http://192.168.1.100:4873/lru-cache
npm http request GET http://192.168.1.100:4873/date-now
npm http 200 http://192.168.1.100:4873/date-now
npm http request GET http://192.168.1.100:4873/domhandler
npm http request GET http://192.168.1.100:4873/domutils
npm http request GET http://192.168.1.100:4873/domelementtype
npm http request GET http://192.168.1.100:4873/entities
npm http 200 http://192.168.1.100:4873/entities
npm http 200 http://192.168.1.100:4873/domutils
npm http 200 http://192.168.1.100:4873/domelementtype
npm http 200 http://192.168.1.100:4873/domhandler
npm http request GET http://192.168.1.100:4873/dom-serializer
npm http 200 http://192.168.1.100:4873/dom-serializer
npm http request GET http://192.168.1.100:4873/spark-md5
npm http 304 http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/ctype
npm http 200 http://192.168.1.100:4873/ctype
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
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/minimist
npm http 304 http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/duplexify
npm http 304 http://192.168.1.100:4873/duplexify
npm http 304 http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/stream-shift
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http 200 http://192.168.1.100:4873/end-of-stream
npm http 304 http://192.168.1.100:4873/stream-shift
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http 200 http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/jsonschema
npm http request GET http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/jsonschema
npm http fetch GET http://192.168.1.100:4873/object-assign/-/object-assign-4.1.0.tgz
npm http fetch 200 http://192.168.1.100:4873/object-assign/-/object-assign-4.1.0.tgz
npm http fetch GET http://192.168.1.100:4873/jsonschema/-/jsonschema-1.1.0.tgz
npm http fetch 200 http://192.168.1.100:4873/jsonschema/-/jsonschema-1.1.0.tgz
npm http request GET http://192.168.1.100:4873/colors
npm http request GET http://192.168.1.100:4873/cycle
npm http request GET http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/pkginfo
npm http request GET http://192.168.1.100:4873/stack-trace
npm http 304 http://192.168.1.100:4873/colors
npm http 304 http://192.168.1.100:4873/cycle
npm http 304 http://192.168.1.100:4873/pkginfo
npm http 304 http://192.168.1.100:4873/stack-trace
npm http 304 http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/jsdoc
npm http 200 http://192.168.1.100:4873/jsdoc
npm http request GET http://192.168.1.100:4873/js2xmlparser
npm http request GET http://192.168.1.100:4873/catharsis
npm http request GET http://192.168.1.100:4873/marked
npm http request GET http://192.168.1.100:4873/requizzle
npm http request GET http://192.168.1.100:4873/underscore
npm http request GET http://192.168.1.100:4873/wrench
npm http request GET http://192.168.1.100:4873/esprima
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 304 http://192.168.1.100:4873/catharsis
npm http 304 http://192.168.1.100:4873/js2xmlparser
npm http 304 http://192.168.1.100:4873/requizzle
npm http 304 http://192.168.1.100:4873/underscore
npm http 200 http://192.168.1.100:4873/marked
npm http 304 http://192.168.1.100:4873/wrench
npm http 304 http://192.168.1.100:4873/esprima
npm WARN deprecated wrench@1.5.9: wrench.js is deprecated! You should check out fs-extra (https://github.com/jprichardson/node-fs-extra) for any operations you were using wrench for. Thanks for all the usage over the years.
npm http fetch 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http request GET http://192.168.1.100:4873/underscore-contrib
npm http 304 http://192.168.1.100:4873/underscore-contrib
npm WARN prefer global marked@0.3.6 should be installed with -g
npm WARN prefer global jshint@2.9.2 should be installed with -g
npm http request GET http://192.168.1.100:4873/leveldown
npm http request GET http://192.168.1.100:4873/websql
npm http 200 http://192.168.1.100:4873/websql
npm http 200 http://192.168.1.100:4873/leveldown
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/nan
npm http request GET http://192.168.1.100:4873/fast-future
npm http request GET http://192.168.1.100:4873/prebuild
npm http 200 http://192.168.1.100:4873/bindings
npm http 200 http://192.168.1.100:4873/fast-future
npm http 304 http://192.168.1.100:4873/nan
npm http 200 http://192.168.1.100:4873/prebuild
npm http 200 http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/expand-template
npm http request GET http://192.168.1.100:4873/ghreleases
npm http request GET http://192.168.1.100:4873/github-from-package
npm http request GET http://192.168.1.100:4873/node-ninja
npm http request GET http://192.168.1.100:4873/os-homedir
npm http request GET http://192.168.1.100:4873/npmlog
npm http request GET http://192.168.1.100:4873/node-gyp
npm http request GET http://192.168.1.100:4873/noop-logger
npm http request GET http://192.168.1.100:4873/pump
npm http request GET http://192.168.1.100:4873/simple-get
npm http request GET http://192.168.1.100:4873/rc
npm http request GET http://192.168.1.100:4873/tar-fs
npm http request GET http://192.168.1.100:4873/tar-stream
npm http 304 http://192.168.1.100:4873/os-homedir
npm http 200 http://192.168.1.100:4873/node-ninja
npm http 200 http://192.168.1.100:4873/github-from-package
npm http 200 http://192.168.1.100:4873/ghreleases
npm http 200 http://192.168.1.100:4873/expand-template
npm http 304 http://192.168.1.100:4873/npmlog
npm http 304 http://192.168.1.100:4873/node-gyp
npm http 304 http://192.168.1.100:4873/pump
npm http 200 http://192.168.1.100:4873/noop-logger
npm http 200 http://192.168.1.100:4873/simple-get
npm http 304 http://192.168.1.100:4873/rc
npm http 304 http://192.168.1.100:4873/tar-stream
npm http 200 http://192.168.1.100:4873/tar-fs
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/simple-mime
npm http request GET http://192.168.1.100:4873/ghrepos
npm http request GET http://192.168.1.100:4873/url-template
npm http request GET http://192.168.1.100:4873/ghutils
npm http 200 http://192.168.1.100:4873/ghutils
npm http 200 http://192.168.1.100:4873/ghrepos
npm http 200 http://192.168.1.100:4873/url-template
npm http 200 http://192.168.1.100:4873/after
npm http 200 http://192.168.1.100:4873/simple-mime
npm http request GET http://192.168.1.100:4873/jsonist
npm http 200 http://192.168.1.100:4873/jsonist
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/hyperquest
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/hyperquest
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/duplexer2
npm http 304 http://192.168.1.100:4873/duplexer2
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/rimraf
npm http request GET http://192.168.1.100:4873/fstream
npm http request GET http://192.168.1.100:4873/nopt
npm http request GET http://192.168.1.100:4873/path-array
npm http request GET http://192.168.1.100:4873/osenv
npm http request GET http://192.168.1.100:4873/tar
npm http request GET http://192.168.1.100:4873/which
npm http 304 http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/rimraf
npm http 200 http://192.168.1.100:4873/path-array
npm http 304 http://192.168.1.100:4873/osenv
npm http 304 http://192.168.1.100:4873/fstream
npm http 200 http://192.168.1.100:4873/nopt
npm http 304 http://192.168.1.100:4873/tar
npm http 200 http://192.168.1.100:4873/which
npm http request GET http://192.168.1.100:4873/fs.realpath
npm http 304 http://192.168.1.100:4873/fs.realpath
npm http request GET http://192.168.1.100:4873/abbrev
npm http 200 http://192.168.1.100:4873/abbrev
npm http request GET http://192.168.1.100:4873/ansi
npm http request GET http://192.168.1.100:4873/are-we-there-yet
npm http request GET http://192.168.1.100:4873/gauge
npm http 304 http://192.168.1.100:4873/ansi
npm http 304 http://192.168.1.100:4873/are-we-there-yet
npm http 200 http://192.168.1.100:4873/gauge
npm http request GET http://192.168.1.100:4873/delegates
npm http 304 http://192.168.1.100:4873/delegates
npm http request GET http://192.168.1.100:4873/has-unicode
npm http request GET http://192.168.1.100:4873/lodash.pad
npm http request GET http://192.168.1.100:4873/lodash.padstart
npm http request GET http://192.168.1.100:4873/lodash.padend
npm http 304 http://192.168.1.100:4873/lodash.padstart
npm http 200 http://192.168.1.100:4873/lodash.padend
npm http 304 http://192.168.1.100:4873/lodash.pad
npm http 200 http://192.168.1.100:4873/has-unicode
npm http request GET http://192.168.1.100:4873/os-tmpdir
npm http 304 http://192.168.1.100:4873/os-tmpdir
npm http request GET http://192.168.1.100:4873/array-index
npm http 304 http://192.168.1.100:4873/array-index
npm http request GET http://192.168.1.100:4873/es6-symbol
npm http 200 http://192.168.1.100:4873/es6-symbol
npm http request GET http://192.168.1.100:4873/d
npm http request GET http://192.168.1.100:4873/es5-ext
npm http 304 http://192.168.1.100:4873/d
npm http 304 http://192.168.1.100:4873/es5-ext
npm http request GET http://192.168.1.100:4873/es6-iterator
npm http 304 http://192.168.1.100:4873/es6-iterator
npm http request GET http://192.168.1.100:4873/block-stream
npm http 304 http://192.168.1.100:4873/block-stream
npm http request GET http://192.168.1.100:4873/isexe
npm http 304 http://192.168.1.100:4873/isexe
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http 304 http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/deep-extend
npm http request GET http://192.168.1.100:4873/ini
npm http 200 http://192.168.1.100:4873/ini
npm http 304 http://192.168.1.100:4873/deep-extend
npm WARN engine deep-extend@0.4.1: wanted: {"node":">=0.12.0","iojs":">=1.0.0"} (current: {"node":"0.10.40","npm":"3.3.12"})
npm http request GET http://192.168.1.100:4873/unzip-response
npm http 304 http://192.168.1.100:4873/unzip-response
npm http request GET http://192.168.1.100:4873/ecc-jsbn
npm http request GET http://192.168.1.100:4873/jodid25519
npm http request GET http://192.168.1.100:4873/jsbn
npm http request GET http://192.168.1.100:4873/tweetnacl
npm http 304 http://192.168.1.100:4873/ecc-jsbn
npm http 304 http://192.168.1.100:4873/jodid25519
npm http 304 http://192.168.1.100:4873/tweetnacl
npm http 304 http://192.168.1.100:4873/jsbn
npm http request GET http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/noop-fn
npm http request GET http://192.168.1.100:4873/sqlite3
npm http 304 http://192.168.1.100:4873/immediate
npm http 304 http://192.168.1.100:4873/sqlite3
npm http 200 http://192.168.1.100:4873/noop-fn
npm WARN prefer global node-ninja@1.0.2 should be installed with -g
npm WARN prefer global node-gyp@3.4.0 should be installed with -g
node-pre-gyp http GET https://mapbox-node-binary.s3.amazonaws.com/sqlite3/v3.1.4/node-v11-darwin-x64.tar.gz
node-pre-gyp http 200 https://mapbox-node-binary.s3.amazonaws.com/sqlite3/v3.1.4/node-v11-darwin-x64.tar.gz
gyp JXcore NODE-GYP Using node-gyp bundled in npm coming from JXcore
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
npm http request GET http://192.168.1.100:4873/fs-extra-promise
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/jxc
npm http request GET http://192.168.1.100:4873/unzip
npm http 304 http://192.168.1.100:4873/fs-extra-promise
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/lie
npm http 304 http://192.168.1.100:4873/unzip
npm http 304 http://192.168.1.100:4873/jxc
npm http request GET http://192.168.1.100:4873/fs-extra
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/fs-extra
npm http 304 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/jsonfile
npm http request GET http://192.168.1.100:4873/rimraf
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http 304 http://192.168.1.100:4873/rimraf
npm http 200 http://192.168.1.100:4873/jsonfile
npm http request GET http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/fs.realpath
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/inflight
npm http 304 http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/minimatch
npm http 304 http://192.168.1.100:4873/fs.realpath
npm http 304 http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/wrappy
npm http 304 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 304 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 200 http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/adm-zip
npm http request GET http://192.168.1.100:4873/progress
npm http 304 http://192.168.1.100:4873/progress
npm http 304 http://192.168.1.100:4873/adm-zip
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 304 http://192.168.1.100:4873/es3ify
npm http 304 http://192.168.1.100:4873/inline-process-browser
npm http 304 http://192.168.1.100:4873/unreachable-branch-transform
npm http 304 http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/through
npm http 304 http://192.168.1.100:4873/esprima
npm http 304 http://192.168.1.100:4873/through
npm http 304 http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/base62
npm http 304 http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 200 http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/mkdirp
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/detective
npm http 304 http://192.168.1.100:4873/private
npm http 200 http://192.168.1.100:4873/commander
npm http 304 http://192.168.1.100:4873/q
npm http 304 http://192.168.1.100:4873/recast
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http 304 http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/acorn
npm http request GET http://192.168.1.100:4873/defined
npm http 304 http://192.168.1.100:4873/acorn
npm http 304 http://192.168.1.100:4873/defined
npm http request GET http://192.168.1.100:4873/minimist
npm http 304 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/ast-types
npm http 304 http://192.168.1.100:4873/ast-types
npm http request GET http://192.168.1.100:4873/amdefine
npm http 304 http://192.168.1.100:4873/amdefine
npm http request GET http://192.168.1.100:4873/falafel
npm http request GET http://192.168.1.100:4873/through2
npm http 304 http://192.168.1.100:4873/through2
npm http 304 http://192.168.1.100:4873/falafel
npm http request GET http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/foreach
npm http 304 http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/core-util-is
npm http request GET http://192.168.1.100:4873/string_decoder
npm http 304 http://192.168.1.100:4873/core-util-is
npm http 304 http://192.168.1.100:4873/string_decoder
npm http request GET http://192.168.1.100:4873/esmangle-evaluator
npm http 304 http://192.168.1.100:4873/esmangle-evaluator
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/forever-agent
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/mime-types
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/qs
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
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/forever-agent
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 200 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/process-nextick-args
npm http 304 http://192.168.1.100:4873/util-deprecate
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/mime-db
npm http 304 http://192.168.1.100:4873/mime-db
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http 304 http://192.168.1.100:4873/is-my-json-valid
npm http 304 http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http 304 http://192.168.1.100:4873/generate-function
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http request GET http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/hoek
npm http 304 http://192.168.1.100:4873/cryptiles
npm http 200 http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/fstream
npm http request GET http://192.168.1.100:4873/setimmediate
npm http request GET http://192.168.1.100:4873/binary
npm http request GET http://192.168.1.100:4873/match-stream
npm http request GET http://192.168.1.100:4873/pullstream
npm http 304 http://192.168.1.100:4873/match-stream
npm http 304 http://192.168.1.100:4873/binary
npm http 200 http://192.168.1.100:4873/setimmediate
npm http 200 http://192.168.1.100:4873/fstream
npm http 304 http://192.168.1.100:4873/pullstream
npm http request GET http://192.168.1.100:4873/chainsaw
npm http request GET http://192.168.1.100:4873/buffers
npm http 304 http://192.168.1.100:4873/chainsaw
npm http 304 http://192.168.1.100:4873/buffers
npm http request GET http://192.168.1.100:4873/traverse
npm http 304 http://192.168.1.100:4873/traverse
npm WARN deprecated graceful-fs@3.0.8: graceful-fs v3.0.0 and before will fail on node releases >= v7.0. Please update to graceful-fs@^4.0.0 as soon as possible. Use 'npm ls graceful-fs' to find it in the tree.
npm http request GET http://192.168.1.100:4873/slice-stream
npm http request GET http://192.168.1.100:4873/over
npm http 200 http://192.168.1.100:4873/over
npm http 200 http://192.168.1.100:4873/slice-stream
npm WARN EPACKAGEJSON install@0.0.1 No repository field.
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/express-pouchdb
npm http request GET http://192.168.1.100:4873/forever-agent
npm http request GET http://192.168.1.100:4873/fs-extra-promise
npm http request GET http://192.168.1.100:4873/bn.js
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/leveldown-mobile
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/pouchdb-node
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/request-promise
npm http request GET http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/proxyquire
npm http request GET http://192.168.1.100:4873/nock
npm http request GET http://192.168.1.100:4873/supertest
npm http request GET http://192.168.1.100:4873/sinon
npm http request GET http://192.168.1.100:4873/tape
npm http request GET http://192.168.1.100:4873/supertest-as-promised
npm http request GET http://192.168.1.100:4873/tape-catch
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/tmp
npm http request GET http://192.168.1.100:4873/uuid
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/express-pouchdb
npm http 304 http://192.168.1.100:4873/forever-agent
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/fs-extra-promise
npm http 304 http://192.168.1.100:4873/bn.js
npm http 304 http://192.168.1.100:4873/lie
npm http 304 http://192.168.1.100:4873/minimist
npm http 304 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/multiplex
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/leveldown-mobile
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/pouchdb-node
npm http 304 http://192.168.1.100:4873/request-promise
npm http 200 http://192.168.1.100:4873/socket.io-client
npm http fetch GET http://192.168.1.100:4873/pouchdb-node/-/pouchdb-node-5.4.4.tgz
npm http 304 http://192.168.1.100:4873/proxyquire
npm http 304 http://192.168.1.100:4873/supertest
npm http 200 http://192.168.1.100:4873/js-extend
npm http 200 http://192.168.1.100:4873/nock
npm http 304 http://192.168.1.100:4873/tape
npm http 200 http://192.168.1.100:4873/supertest-as-promised
npm http 200 http://192.168.1.100:4873/sinon
npm http 304 http://192.168.1.100:4873/tape-catch
npm http fetch 200 http://192.168.1.100:4873/pouchdb-node/-/pouchdb-node-5.4.4.tgz
npm http 304 http://192.168.1.100:4873/urlsafe-base64
npm http 304 http://192.168.1.100:4873/tmp
npm http 304 http://192.168.1.100:4873/uuid
npm http 200 http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/iconv-lite
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
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/send
npm http 304 http://192.168.1.100:4873/serve-static
npm http 304 http://192.168.1.100:4873/utils-merge
npm http 304 http://192.168.1.100:4873/vary
npm http request GET http://192.168.1.100:4873/negotiator
npm http 304 http://192.168.1.100:4873/negotiator
npm http request GET http://192.168.1.100:4873/forwarded
npm http request GET http://192.168.1.100:4873/ipaddr.js
npm http 200 http://192.168.1.100:4873/ipaddr.js
npm http 200 http://192.168.1.100:4873/forwarded
npm http request GET http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/mime
npm http 304 http://192.168.1.100:4873/mime
npm http 304 http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/basic-auth
npm http request GET http://192.168.1.100:4873/compression
npm http request GET http://192.168.1.100:4873/cookie-parser
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/header-case-normalizer
npm http request GET http://192.168.1.100:4873/multiparty
npm http request GET http://192.168.1.100:4873/pouchdb-all-dbs
npm http request GET http://192.168.1.100:4873/pouchdb-auth
npm http request GET http://192.168.1.100:4873/pouchdb-find
npm http request GET http://192.168.1.100:4873/pouchdb-list
npm http request GET http://192.168.1.100:4873/pouchdb-replicator
npm http request GET http://192.168.1.100:4873/pouchdb-rewrite
npm http request GET http://192.168.1.100:4873/pouchdb-security
npm http request GET http://192.168.1.100:4873/pouchdb-show
npm http request GET http://192.168.1.100:4873/pouchdb-size
npm http request GET http://192.168.1.100:4873/pouchdb-update
npm http request GET http://192.168.1.100:4873/pouchdb-validation
npm http request GET http://192.168.1.100:4873/pouchdb-vhost
npm http request GET http://192.168.1.100:4873/pouchdb-wrappers
npm http 304 http://192.168.1.100:4873/basic-auth
npm http 304 http://192.168.1.100:4873/compression
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/cookie-parser
npm http 304 http://192.168.1.100:4873/pouchdb-all-dbs
npm http 304 http://192.168.1.100:4873/multiparty
npm http 304 http://192.168.1.100:4873/pouchdb-find
npm http 304 http://192.168.1.100:4873/pouchdb-list
npm http 304 http://192.168.1.100:4873/pouchdb-replicator
npm http 304 http://192.168.1.100:4873/pouchdb-rewrite
npm http 200 http://192.168.1.100:4873/pouchdb-auth
npm http 304 http://192.168.1.100:4873/pouchdb-show
npm http 304 http://192.168.1.100:4873/pouchdb-size
npm http 304 http://192.168.1.100:4873/pouchdb-update
npm http 304 http://192.168.1.100:4873/pouchdb-vhost
npm http 200 http://192.168.1.100:4873/pouchdb-validation
npm http 200 http://192.168.1.100:4873/header-case-normalizer
npm http 200 http://192.168.1.100:4873/pouchdb-wrappers
npm http 200 http://192.168.1.100:4873/pouchdb-security
npm http request GET http://192.168.1.100:4873/compressible
npm http request GET http://192.168.1.100:4873/on-headers
npm http 304 http://192.168.1.100:4873/compressible
npm http 304 http://192.168.1.100:4873/on-headers
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/stream-counter
npm http 304 http://192.168.1.100:4873/stream-counter
npm http 304 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/core-util-is
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/string_decoder
npm http 304 http://192.168.1.100:4873/core-util-is
npm http 304 http://192.168.1.100:4873/string_decoder
npm http 304 http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/argsarray
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/tiny-queue
npm http 304 http://192.168.1.100:4873/es3ify
npm http 200 http://192.168.1.100:4873/argsarray
npm http 200 http://192.168.1.100:4873/tiny-queue
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/through
npm http 304 http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/through
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/amdefine
npm http 304 http://192.168.1.100:4873/amdefine
npm http request GET http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 304 http://192.168.1.100:4873/unreachable-branch-transform
npm http 304 http://192.168.1.100:4873/immediate
npm http 304 http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/falafel
npm http request GET http://192.168.1.100:4873/through2
npm http 304 http://192.168.1.100:4873/through2
npm http 200 http://192.168.1.100:4873/falafel
npm http request GET http://192.168.1.100:4873/acorn
npm http request GET http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/foreach
npm http 304 http://192.168.1.100:4873/acorn
npm http request GET http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/esmangle-evaluator
npm http request GET http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/esmangle-evaluator
npm http 200 http://192.168.1.100:4873/recast
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/ast-types
npm http 304 http://192.168.1.100:4873/private
npm http 200 http://192.168.1.100:4873/ast-types
npm http request GET http://192.168.1.100:4873/base64url
npm http request GET http://192.168.1.100:4873/couchdb-calculate-session-id
npm http request GET http://192.168.1.100:4873/crypto-lite
npm http request GET http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http request GET http://192.168.1.100:4873/pouchdb-plugin-error
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/pouchdb
npm http request GET http://192.168.1.100:4873/pouchdb-req-http-query
npm http request GET http://192.168.1.100:4873/pouchdb-system-db
npm http request GET http://192.168.1.100:4873/promise-nodify
npm http request GET http://192.168.1.100:4873/secure-random
npm http 304 http://192.168.1.100:4873/base64url
npm http 200 http://192.168.1.100:4873/crypto-lite
npm http 200 http://192.168.1.100:4873/couchdb-calculate-session-id
npm http 200 http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http 200 http://192.168.1.100:4873/pouchdb-system-db
npm http 200 http://192.168.1.100:4873/pouchdb-req-http-query
npm http 200 http://192.168.1.100:4873/pouchdb-promise
npm http 200 http://192.168.1.100:4873/pouchdb-plugin-error
npm http 200 http://192.168.1.100:4873/promise-nodify
npm http 200 http://192.168.1.100:4873/secure-random
npm http 200 http://192.168.1.100:4873/pouchdb
npm http request GET http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/meow
npm http 304 http://192.168.1.100:4873/concat-stream
npm http 304 http://192.168.1.100:4873/meow
npm http request GET http://192.168.1.100:4873/typedarray
npm http 304 http://192.168.1.100:4873/typedarray
npm http request GET http://192.168.1.100:4873/camelcase-keys
npm http request GET http://192.168.1.100:4873/indent-string
npm http request GET http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/camelcase-keys
npm http 304 http://192.168.1.100:4873/indent-string
npm http 304 http://192.168.1.100:4873/object-assign
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
npm http request GET http://192.168.1.100:4873/es6-promise-pool
npm http request GET http://192.168.1.100:4873/fruitdown
npm http request GET http://192.168.1.100:4873/level-write-stream
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/localstorage-down
npm http request GET http://192.168.1.100:4873/memdown
npm http request GET http://192.168.1.100:4873/pouchdb-collate
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/scope-eval
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/vuvuzela
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/fruitdown
npm http 200 http://192.168.1.100:4873/es6-promise-pool
npm http 200 http://192.168.1.100:4873/double-ended-queue
npm http 200 http://192.168.1.100:4873/localstorage-down
npm http 200 http://192.168.1.100:4873/levelup
npm http 200 http://192.168.1.100:4873/pouchdb-collate
npm http 200 http://192.168.1.100:4873/pouchdb-collections
npm http 200 http://192.168.1.100:4873/level-write-stream
npm http 200 http://192.168.1.100:4873/spark-md5
npm http 200 http://192.168.1.100:4873/scope-eval
npm http 304 http://192.168.1.100:4873/js-extend
npm http 200 http://192.168.1.100:4873/sublevel-pouchdb
npm http 304 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/vuvuzela
npm http 200 http://192.168.1.100:4873/memdown
npm http request GET http://192.168.1.100:4873/d64
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http 304 http://192.168.1.100:4873/abstract-leveldown
npm http 200 http://192.168.1.100:4873/d64
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
npm http 304 http://192.168.1.100:4873/prr
npm http 200 http://192.168.1.100:4873/level-errors
npm http 200 http://192.168.1.100:4873/deferred-leveldown
npm http 304 http://192.168.1.100:4873/semver
npm http 200 http://192.168.1.100:4873/level-codec
npm http 200 http://192.168.1.100:4873/level-iterator-stream
npm http request GET http://192.168.1.100:4873/errno
npm http 304 http://192.168.1.100:4873/errno
npm http request GET http://192.168.1.100:4873/esprima
npm http 304 http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/commoner
npm http 304 http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/q
npm http 304 http://192.168.1.100:4873/commander
npm http 304 http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/detective
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http 304 http://192.168.1.100:4873/mkdirp
npm http 304 http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http 304 http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/defined
npm http 304 http://192.168.1.100:4873/defined
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/inflight
npm http 304 http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/minimatch
npm http 304 http://192.168.1.100:4873/path-is-absolute
npm http request GET http://192.168.1.100:4873/wrappy
npm http 304 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 304 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/minimist
npm http 304 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/humble-localstorage
npm http request GET http://192.168.1.100:4873/tiny-queue
npm http 304 http://192.168.1.100:4873/tiny-queue
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
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/aws4
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/is-typedarray
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/tough-cookie
npm WARN deprecated tough-cookie@2.2.2: ReDoS vulnerability parsing Set-Cookie https://nodesecurity.io/advisories/130
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http request GET http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/process-nextick-args
npm http 304 http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
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
npm http 304 http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-function
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/pinkie
npm http 304 http://192.168.1.100:4873/pinkie
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/boom
npm http 304 http://192.168.1.100:4873/cryptiles
npm http 304 http://192.168.1.100:4873/hoek
npm http 200 http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/jsprim
npm http request GET http://192.168.1.100:4873/sshpk
npm http 304 http://192.168.1.100:4873/jsprim
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 304 http://192.168.1.100:4873/sshpk
npm http request GET http://192.168.1.100:4873/extsprintf
npm http request GET http://192.168.1.100:4873/json-schema
npm http request GET http://192.168.1.100:4873/verror
npm http 304 http://192.168.1.100:4873/verror
npm http 200 http://192.168.1.100:4873/extsprintf
npm http 200 http://192.168.1.100:4873/json-schema
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/dashdash
npm http request GET http://192.168.1.100:4873/getpass
npm http 304 http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/getpass
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
npm http 200 http://192.168.1.100:4873/xmlhttprequest-cookie
npm http request GET http://192.168.1.100:4873/xmlhttprequest
npm http 304 http://192.168.1.100:4873/xmlhttprequest
npm http request GET http://192.168.1.100:4873/pouchdb-changeslike-wrapper
npm http 200 http://192.168.1.100:4873/pouchdb-changeslike-wrapper
npm http request GET http://192.168.1.100:4873/couchdb-objects
npm http request GET http://192.168.1.100:4873/couchdb-eval
npm http request GET http://192.168.1.100:4873/random-uuid-v4
npm http 200 http://192.168.1.100:4873/random-uuid-v4
npm http 200 http://192.168.1.100:4873/couchdb-eval
npm http 200 http://192.168.1.100:4873/couchdb-objects
npm http request GET http://192.168.1.100:4873/is-empty
npm http 200 http://192.168.1.100:4873/is-empty
npm http request GET http://192.168.1.100:4873/jshint
npm http request GET http://192.168.1.100:4873/pouchdb-abstract-mapreduce
npm http request GET http://192.168.1.100:4873/pouchdb-extend
npm http request GET http://192.168.1.100:4873/pouchdb-upsert
npm http request GET http://192.168.1.100:4873/spark-md5
npm http 304 http://192.168.1.100:4873/spark-md5
npm http 304 http://192.168.1.100:4873/pouchdb-abstract-mapreduce
npm http 304 http://192.168.1.100:4873/jshint
npm http 200 http://192.168.1.100:4873/pouchdb-upsert
npm http 200 http://192.168.1.100:4873/pouchdb-extend
npm http request GET http://192.168.1.100:4873/cli
npm http request GET http://192.168.1.100:4873/console-browserify
npm http request GET http://192.168.1.100:4873/exit
npm http request GET http://192.168.1.100:4873/htmlparser2
npm http request GET http://192.168.1.100:4873/shelljs
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/console-browserify
npm http 304 http://192.168.1.100:4873/htmlparser2
npm http 304 http://192.168.1.100:4873/cli
npm http 304 http://192.168.1.100:4873/shelljs
npm http 200 http://192.168.1.100:4873/exit
npm http 304 http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/strip-json-comments
npm http 304 http://192.168.1.100:4873/minimatch
npm WARN deprecated minimatch@2.0.10: Please update to minimatch 3.0.2 or higher to avoid a RegExp DoS issue
npm http request GET http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/glob
npm WARN deprecated minimatch@0.3.0: Please update to minimatch 3.0.2 or higher to avoid a RegExp DoS issue
npm http request GET http://192.168.1.100:4873/sigmund
npm http request GET http://192.168.1.100:4873/lru-cache
npm http 304 http://192.168.1.100:4873/lru-cache
npm http 304 http://192.168.1.100:4873/sigmund
npm http request GET http://192.168.1.100:4873/date-now
npm http 304 http://192.168.1.100:4873/date-now
npm http request GET http://192.168.1.100:4873/domhandler
npm http request GET http://192.168.1.100:4873/domutils
npm http request GET http://192.168.1.100:4873/domelementtype
npm http request GET http://192.168.1.100:4873/entities
npm http 304 http://192.168.1.100:4873/entities
npm http 304 http://192.168.1.100:4873/domhandler
npm http 304 http://192.168.1.100:4873/domelementtype
npm http 200 http://192.168.1.100:4873/domutils
npm http request GET http://192.168.1.100:4873/dom-serializer
npm http 304 http://192.168.1.100:4873/dom-serializer
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/ctype
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
npm http request GET http://192.168.1.100:4873/fs-extra
npm http 304 http://192.168.1.100:4873/fs-extra
npm http request GET http://192.168.1.100:4873/jsonfile
npm http request GET http://192.168.1.100:4873/rimraf
npm http 304 http://192.168.1.100:4873/jsonfile
npm http 304 http://192.168.1.100:4873/rimraf
npm http request GET http://192.168.1.100:4873/fs.realpath
npm http 304 http://192.168.1.100:4873/fs.realpath
npm http request GET http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/fast-future
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http 304 http://192.168.1.100:4873/bindings
npm http 304 http://192.168.1.100:4873/abstract-leveldown
npm http 304 http://192.168.1.100:4873/fast-future
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/varint
npm http 304 http://192.168.1.100:4873/varint
npm http 304 http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/stream-shift
npm http 304 http://192.168.1.100:4873/stream-shift
npm http 304 http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http 304 http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/deep-equal
npm http request GET http://192.168.1.100:4873/debug
npm WARN deprecated lodash@2.4.1: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
npm http request GET http://192.168.1.100:4873/propagate
npm http request GET http://192.168.1.100:4873/chai
npm http 304 http://192.168.1.100:4873/propagate
npm http 304 http://192.168.1.100:4873/chai
npm http 304 http://192.168.1.100:4873/debug
npm http 200 http://192.168.1.100:4873/deep-equal
npm http request GET http://192.168.1.100:4873/type-detect
npm http request GET http://192.168.1.100:4873/deep-eql
npm http request GET http://192.168.1.100:4873/assertion-error
npm http 304 http://192.168.1.100:4873/type-detect
npm http 200 http://192.168.1.100:4873/assertion-error
npm http 304 http://192.168.1.100:4873/deep-eql
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/ip
npm http 304 http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-http
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-leveldb
npm http request GET http://192.168.1.100:4873/pouchdb-core
npm http request GET http://192.168.1.100:4873/pouchdb-replication
npm http request GET http://192.168.1.100:4873/pouchdb-mapreduce
npm http 304 http://192.168.1.100:4873/pouchdb-mapreduce
npm http fetch GET http://192.168.1.100:4873/pouchdb-mapreduce/-/pouchdb-mapreduce-5.4.4.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-mapreduce/-/pouchdb-mapreduce-5.4.4.tgz
npm http 304 http://192.168.1.100:4873/pouchdb-core
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-leveldb
npm http fetch GET http://192.168.1.100:4873/pouchdb-core/-/pouchdb-core-5.4.4.tgz
npm http fetch GET http://192.168.1.100:4873/pouchdb-adapter-leveldb/-/pouchdb-adapter-leveldb-5.4.4.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-core/-/pouchdb-core-5.4.4.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-adapter-leveldb/-/pouchdb-adapter-leveldb-5.4.4.tgz
npm http 304 http://192.168.1.100:4873/pouchdb-replication
npm http fetch GET http://192.168.1.100:4873/pouchdb-replication/-/pouchdb-replication-5.4.4.tgz
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-http
npm http fetch 200 http://192.168.1.100:4873/pouchdb-replication/-/pouchdb-replication-5.4.4.tgz
npm http fetch GET http://192.168.1.100:4873/pouchdb-adapter-http/-/pouchdb-adapter-http-5.4.4.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-adapter-http/-/pouchdb-adapter-http-5.4.4.tgz
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/pouchdb-binary-utils
npm http request GET http://192.168.1.100:4873/pouchdb-ajax
npm http request GET http://192.168.1.100:4873/pouchdb-errors
npm http request GET http://192.168.1.100:4873/pouchdb-md5
npm http request GET http://192.168.1.100:4873/pouchdb-utils
npm http 304 http://192.168.1.100:4873/pouchdb-promise
npm http fetch GET http://192.168.1.100:4873/pouchdb-promise/-/pouchdb-promise-5.4.4.tgz
npm http 304 http://192.168.1.100:4873/pouchdb-ajax
npm http fetch 200 http://192.168.1.100:4873/pouchdb-promise/-/pouchdb-promise-5.4.4.tgz
npm http fetch GET http://192.168.1.100:4873/pouchdb-ajax/-/pouchdb-ajax-5.4.4.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-ajax/-/pouchdb-ajax-5.4.4.tgz
npm http 304 http://192.168.1.100:4873/pouchdb-binary-utils
npm http 304 http://192.168.1.100:4873/pouchdb-errors
npm http 304 http://192.168.1.100:4873/pouchdb-utils
npm http 304 http://192.168.1.100:4873/pouchdb-md5
npm http fetch GET http://192.168.1.100:4873/pouchdb-binary-utils/-/pouchdb-binary-utils-5.4.4.tgz
npm http fetch GET http://192.168.1.100:4873/pouchdb-errors/-/pouchdb-errors-5.4.4.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-binary-utils/-/pouchdb-binary-utils-5.4.4.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-errors/-/pouchdb-errors-5.4.4.tgz
npm http fetch GET http://192.168.1.100:4873/pouchdb-utils/-/pouchdb-utils-5.4.4.tgz
npm http fetch GET http://192.168.1.100:4873/pouchdb-md5/-/pouchdb-md5-5.4.4.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-utils/-/pouchdb-utils-5.4.4.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-md5/-/pouchdb-md5-5.4.4.tgz
npm http request GET http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/leveldown
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-leveldb-core
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-leveldb-core
npm http fetch GET http://192.168.1.100:4873/pouchdb-adapter-leveldb-core/-/pouchdb-adapter-leveldb-core-5.4.4.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-adapter-leveldb-core/-/pouchdb-adapter-leveldb-core-5.4.4.tgz
npm http 200 http://192.168.1.100:4873/leveldown
npm http request GET http://192.168.1.100:4873/nan
npm http request GET http://192.168.1.100:4873/prebuild
npm http 304 http://192.168.1.100:4873/nan
npm http 200 http://192.168.1.100:4873/prebuild
npm http request GET http://192.168.1.100:4873/expand-template
npm http request GET http://192.168.1.100:4873/ghreleases
npm http request GET http://192.168.1.100:4873/github-from-package
npm http request GET http://192.168.1.100:4873/node-gyp
npm http request GET http://192.168.1.100:4873/node-ninja
npm http request GET http://192.168.1.100:4873/noop-logger
npm http request GET http://192.168.1.100:4873/npmlog
npm http request GET http://192.168.1.100:4873/os-homedir
npm http request GET http://192.168.1.100:4873/pump
npm http request GET http://192.168.1.100:4873/rc
npm http request GET http://192.168.1.100:4873/simple-get
npm http request GET http://192.168.1.100:4873/tar-fs
npm http request GET http://192.168.1.100:4873/tar-stream
npm http 200 http://192.168.1.100:4873/node-gyp
npm http 200 http://192.168.1.100:4873/node-ninja
npm http 200 http://192.168.1.100:4873/expand-template
npm http 200 http://192.168.1.100:4873/github-from-package
npm http 304 http://192.168.1.100:4873/npmlog
npm http 200 http://192.168.1.100:4873/os-homedir
npm http 304 http://192.168.1.100:4873/pump
npm http 304 http://192.168.1.100:4873/tar-fs
npm http 200 http://192.168.1.100:4873/ghreleases
npm http 200 http://192.168.1.100:4873/rc
npm http 200 http://192.168.1.100:4873/noop-logger
npm http 304 http://192.168.1.100:4873/tar-stream
npm http 200 http://192.168.1.100:4873/simple-get
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/ghrepos
npm http request GET http://192.168.1.100:4873/ghutils
npm http request GET http://192.168.1.100:4873/simple-mime
npm http request GET http://192.168.1.100:4873/url-template
npm http 304 http://192.168.1.100:4873/after
npm http 304 http://192.168.1.100:4873/ghutils
npm http 304 http://192.168.1.100:4873/url-template
npm http 304 http://192.168.1.100:4873/ghrepos
npm http 304 http://192.168.1.100:4873/simple-mime
npm http request GET http://192.168.1.100:4873/jsonist
npm http 304 http://192.168.1.100:4873/jsonist
npm http request GET http://192.168.1.100:4873/hyperquest
npm http 304 http://192.168.1.100:4873/hyperquest
npm http request GET http://192.168.1.100:4873/duplexer2
npm http 304 http://192.168.1.100:4873/duplexer2
npm http request GET http://192.168.1.100:4873/fstream
npm http request GET http://192.168.1.100:4873/nopt
npm http request GET http://192.168.1.100:4873/osenv
npm http request GET http://192.168.1.100:4873/path-array
npm http request GET http://192.168.1.100:4873/tar
npm http request GET http://192.168.1.100:4873/which
npm http request GET http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/fstream
npm http 304 http://192.168.1.100:4873/nopt
npm http 304 http://192.168.1.100:4873/which
npm http 304 http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/path-array
npm http 200 http://192.168.1.100:4873/osenv
npm http 304 http://192.168.1.100:4873/tar
npm http request GET http://192.168.1.100:4873/abbrev
npm http 304 http://192.168.1.100:4873/abbrev
npm http request GET http://192.168.1.100:4873/ansi
npm http request GET http://192.168.1.100:4873/are-we-there-yet
npm http request GET http://192.168.1.100:4873/gauge
npm http 304 http://192.168.1.100:4873/gauge
npm http 304 http://192.168.1.100:4873/ansi
npm http 200 http://192.168.1.100:4873/are-we-there-yet
npm http request GET http://192.168.1.100:4873/delegates
npm http 304 http://192.168.1.100:4873/delegates
npm http request GET http://192.168.1.100:4873/has-unicode
npm http request GET http://192.168.1.100:4873/lodash.pad
npm http request GET http://192.168.1.100:4873/lodash.padend
npm http request GET http://192.168.1.100:4873/lodash.padstart
npm http 304 http://192.168.1.100:4873/lodash.pad
npm http 304 http://192.168.1.100:4873/has-unicode
npm http 200 http://192.168.1.100:4873/lodash.padend
npm http 200 http://192.168.1.100:4873/lodash.padstart
npm http request GET http://192.168.1.100:4873/os-tmpdir
npm http 304 http://192.168.1.100:4873/os-tmpdir
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
npm http request GET http://192.168.1.100:4873/block-stream
npm http 304 http://192.168.1.100:4873/block-stream
npm http request GET http://192.168.1.100:4873/isexe
npm http 304 http://192.168.1.100:4873/isexe
npm http request GET http://192.168.1.100:4873/deep-extend
npm http request GET http://192.168.1.100:4873/ini
npm http 304 http://192.168.1.100:4873/ini
npm http 304 http://192.168.1.100:4873/deep-extend
npm WARN engine deep-extend@0.4.1: wanted: {"node":">=0.12.0","iojs":">=1.0.0"} (current: {"node":"0.10.40","npm":"3.3.12"})
npm http request GET http://192.168.1.100:4873/unzip-response
npm http 304 http://192.168.1.100:4873/unzip-response
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/pouchdb-json
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-utils
npm http request GET http://192.168.1.100:4873/pouchdb-merge
npm http 304 http://192.168.1.100:4873/through2
npm http 304 http://192.168.1.100:4873/pouchdb-json
npm http fetch GET http://192.168.1.100:4873/pouchdb-json/-/pouchdb-json-5.4.4.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-json/-/pouchdb-json-5.4.4.tgz
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-utils
npm http fetch GET http://192.168.1.100:4873/pouchdb-adapter-utils/-/pouchdb-adapter-utils-5.4.4.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-adapter-utils/-/pouchdb-adapter-utils-5.4.4.tgz
npm http 304 http://192.168.1.100:4873/pouchdb-merge
npm http fetch GET http://192.168.1.100:4873/pouchdb-merge/-/pouchdb-merge-5.4.4.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-merge/-/pouchdb-merge-5.4.4.tgz
npm http request GET http://192.168.1.100:4873/pouchdb-mapreduce-utils
npm http 304 http://192.168.1.100:4873/pouchdb-mapreduce-utils
npm http fetch GET http://192.168.1.100:4873/pouchdb-mapreduce-utils/-/pouchdb-mapreduce-utils-5.4.4.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-mapreduce-utils/-/pouchdb-mapreduce-utils-5.4.4.tgz
npm http request GET http://192.168.1.100:4873/pouchdb-checkpointer
npm http request GET http://192.168.1.100:4873/pouchdb-generate-replication-id
npm http 304 http://192.168.1.100:4873/pouchdb-generate-replication-id
npm http fetch GET http://192.168.1.100:4873/pouchdb-generate-replication-id/-/pouchdb-generate-replication-id-5.4.4.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-generate-replication-id/-/pouchdb-generate-replication-id-5.4.4.tgz
npm http 304 http://192.168.1.100:4873/pouchdb-checkpointer
npm http fetch GET http://192.168.1.100:4873/pouchdb-checkpointer/-/pouchdb-checkpointer-5.4.4.tgz
npm http fetch 200 http://192.168.1.100:4873/pouchdb-checkpointer/-/pouchdb-checkpointer-5.4.4.tgz
npm http request GET http://192.168.1.100:4873/module-not-found-error
npm http request GET http://192.168.1.100:4873/fill-keys
npm http 200 http://192.168.1.100:4873/fill-keys
npm http 200 http://192.168.1.100:4873/module-not-found-error
npm http request GET http://192.168.1.100:4873/is-object
npm http 200 http://192.168.1.100:4873/is-object
npm http request GET http://192.168.1.100:4873/array-uniq
npm http 304 http://192.168.1.100:4873/array-uniq
npm http request GET http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/jsonschema
npm http request GET http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/jsonschema
npm http request GET http://192.168.1.100:4873/formatio
npm http request GET http://192.168.1.100:4873/samsam
npm http request GET http://192.168.1.100:4873/lolex
npm http request GET http://192.168.1.100:4873/util
npm http 304 http://192.168.1.100:4873/formatio
npm http 304 http://192.168.1.100:4873/util
npm http 304 http://192.168.1.100:4873/samsam
npm http 304 http://192.168.1.100:4873/lolex
npm http request GET http://192.168.1.100:4873/engine.io-client
npm http request GET http://192.168.1.100:4873/component-emitter
npm http request GET http://192.168.1.100:4873/object-component
npm http request GET http://192.168.1.100:4873/component-bind
npm http request GET http://192.168.1.100:4873/socket.io-parser
npm http request GET http://192.168.1.100:4873/has-binary
npm http request GET http://192.168.1.100:4873/indexof
npm http request GET http://192.168.1.100:4873/parseuri
npm http request GET http://192.168.1.100:4873/to-array
npm http request GET http://192.168.1.100:4873/backo2
npm http request GET http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/engine.io-client
npm http 304 http://192.168.1.100:4873/component-bind
npm http 304 http://192.168.1.100:4873/component-emitter
npm http 304 http://192.168.1.100:4873/object-component
npm http 304 http://192.168.1.100:4873/socket.io-parser
npm http 304 http://192.168.1.100:4873/has-binary
npm http 304 http://192.168.1.100:4873/to-array
npm http 304 http://192.168.1.100:4873/indexof
npm http 304 http://192.168.1.100:4873/parseuri
npm http 200 http://192.168.1.100:4873/backo2
npm http 304 http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/parseqs
npm http request GET http://192.168.1.100:4873/ws
npm http fetch GET https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http 304 http://192.168.1.100:4873/has-cors
npm http 304 http://192.168.1.100:4873/component-inherit
npm http 304 http://192.168.1.100:4873/parsejson
npm http 304 http://192.168.1.100:4873/engine.io-parser
npm http 304 http://192.168.1.100:4873/parseqs
npm http 304 http://192.168.1.100:4873/ws
npm http fetch 200 https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/utf8
npm http 304 http://192.168.1.100:4873/utf8
npm http 304 http://192.168.1.100:4873/blob
npm http 304 http://192.168.1.100:4873/arraybuffer.slice
npm http 200 http://192.168.1.100:4873/base64-arraybuffer
npm http fetch GET https://github.com/component/global/archive/v2.0.1.tar.gz
npm http fetch 200 https://github.com/component/global/archive/v2.0.1.tar.gz
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
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/reduce-component
npm http request GET http://192.168.1.100:4873/cookiejar
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/formidable
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/reduce-component
npm http 200 http://192.168.1.100:4873/cookiejar
npm http 304 http://192.168.1.100:4873/form-data
npm http 200 http://192.168.1.100:4873/formidable
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/mime-types
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/mime-db
npm http 304 http://192.168.1.100:4873/mime-db
npm http request GET http://192.168.1.100:4873/defined
npm http request GET http://192.168.1.100:4873/resumer
npm http request GET http://192.168.1.100:4873/object-inspect
npm http 304 http://192.168.1.100:4873/object-inspect
npm http 200 http://192.168.1.100:4873/defined
npm http 304 http://192.168.1.100:4873/resumer
npm WARN prefer global jshint@2.9.2 should be installed with -g
npm WARN prefer global node-ninja@1.0.2 should be installed with -g
npm WARN prefer global node-gyp@3.4.0 should be installed with -g
gyp JXcore NODE-GYP Using node-gyp bundled in npm coming from JXcore
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
Using a callback for new PouchDB()is deprecated.
Using a callback for new PouchDB()is deprecated.
Using a callback for new PouchDB()is deprecated.
Using a callback for new PouchDB()is deprecated.
Using a callback for new PouchDB()is deprecated.
Using a callback for new PouchDB()is deprecated.
Using a callback for new PouchDB()is deprecated.
Using a callback for new PouchDB()is deprecated.
Using a callback for new PouchDB()is deprecated.
Using a callback for new PouchDB()is deprecated.
Using a callback for new PouchDB()is deprecated.
Using a callback for new PouchDB()is deprecated.
