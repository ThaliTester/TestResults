#### Test (Fail) 75173807 Build Logs


```


```

```
Already up-to-date.

From https://github.com/thaliproject/Thali_CordovaPlugin
   dbcc44d..8130305  vNext_yarong_417_1 -> origin/vNext_yarong_417_1

```

```
Your branch is up-to-date with 'origin/master'.
Branch vNext set up to track remote branch vNext from origin.
Merge made by the 'recursive' strategy.
 build.sh | 6 ------
 1 file changed, 6 deletions(-)

Already on 'master'
Switched to a new branch 'vNext'
Note: checking out '8130305'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at 8130305... Fixed not handling beacon results with no value for us

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
│   ├── graceful-fs@4.1.4 
│   ├── jsonfile@2.3.1 
│   └─┬ rimraf@2.5.2 
│     └─┬ glob@7.0.5 
│       ├── fs.realpath@1.0.0 
│       ├─┬ inflight@1.0.5 
│       │ └── wrappy@1.0.2 
│       ├─┬ minimatch@3.0.2 
│       │ └─┬ brace-expansion@1.1.5 
│       │   ├── balanced-match@0.4.1 
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
│ ├── immediate@3.0.5 
│ ├─┬ inline-process-browser@1.0.0 
│ │ ├─┬ falafel@1.2.0 
│ │ │ ├── acorn@1.2.2 
│ │ │ ├── foreach@2.0.5 
│ │ │ └── object-keys@1.0.9 
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
│ │ ├─┬ pouchdb@5.4.4 
│ │ │ ├── double-ended-queue@2.0.0-0 
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
│ │ │ │ │ └─┬ sshpk@1.8.3 
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
│ │ ├── pouchdb-promise@5.4.4 
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
│ │ │ │ └─┬ brace-expansion@1.1.5 
│ │ │ │   ├── balanced-match@0.4.1 
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
│ │ ├─┬ equals@1.1.0 
│ │ │ └── @jkroso/type@1.1.1 
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
├─┬ jsdoc@3.3.3 
│ ├── async@0.9.2 
│ ├─┬ catharsis@0.8.8 
│ │ └─┬ underscore-contrib@0.3.0 
│ │   └── underscore@1.6.0 
│ ├── escape-string-regexp@1.0.5 
│ ├── esprima@1.2.5 
│ ├── js2xmlparser@0.1.9 
│ ├── marked@0.3.5 
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
│ │ │ │ │ ├── minimatch@3.0.2 
│ │ │ │ │ └── path-is-absolute@1.0.0 
│ │ │ │ ├── graceful-fs@4.1.4 
│ │ │ │ ├─┬ mkdirp@0.5.1 
│ │ │ │ │ └── minimist@0.0.8 
│ │ │ │ └── q@1.4.1 
│ │ │ ├── esprima-fb@15001.1.0-dev-harmony-fb 
│ │ │ ├── object-assign@2.1.1 
│ │ │ └─┬ source-map@0.4.4 
│ │ │   └── amdefine@1.0.0 
│ │ └── through@2.3.8 
│ ├─┬ immediate@3.0.5 
│ │ └── unreachable-branch-transform@0.3.0 
│ ├─┬ inline-process-browser@1.0.0 
│ │ ├─┬ falafel@1.2.0 
│ │ │ ├── acorn@1.2.2 
│ │ │ ├── foreach@2.0.5 
│ │ │ └── object-keys@1.0.9 
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
│ ├─┬ duplexify@3.4.3 
│ │ ├─┬ end-of-stream@1.0.0 
│ │ │ └─┬ once@1.3.3 
│ │ │   └── wrappy@1.0.2 
│ │ └─┬ readable-stream@2.1.4 
│ │   └── isarray@1.0.0 
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
├── salti@0.2.0 
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
│ ├─┬ pouchdb-auth@2.1.0
│ │ └─┬ pouchdb@5.4.4
│ │   ├─┬ leveldown@1.4.6 
│ │   │ ├── abstract-leveldown@2.4.1 
│ │   │ ├── bindings@1.2.1 
│ │   │ ├── fast-future@1.0.1 
│ │   │ ├── nan@2.3.5 
│ │   │ └─┬ prebuild@4.2.2 
│ │   │   ├── expand-template@1.0.2 
│ │   │   ├─┬ ghreleases@1.0.5 
│ │   │   │ ├── after@0.8.1 
│ │   │   │ ├── ghrepos@2.0.0 
│ │   │   │ ├─┬ ghutils@3.2.0 
│ │   │   │ │ └─┬ jsonist@1.2.0 
│ │   │   │ │   ├─┬ bl@1.0.3 
│ │   │   │ │   │ └─┬ readable-stream@2.0.6 
│ │   │   │ │   │   └── isarray@1.0.0 
│ │   │   │ │   └─┬ hyperquest@1.2.0 
│ │   │   │ │     └── duplexer2@0.0.2 
│ │   │   │ ├── simple-mime@0.1.0 
│ │   │   │ └── url-template@2.0.7 
│ │   │   ├── github-from-package@0.0.0 
│ │   │   ├─┬ node-gyp@3.3.1 
│ │   │   │ ├── fstream@1.0.10 
│ │   │   │ ├─┬ glob@4.5.3 
│ │   │   │ │ └── minimatch@2.0.10 
│ │   │   │ ├── minimatch@1.0.0 
│ │   │   │ ├─┬ nopt@3.0.6 
│ │   │   │ │ └── abbrev@1.0.9 
│ │   │   │ ├─┬ osenv@0.1.3 
│ │   │   │ │ └── os-tmpdir@1.0.1 
│ │   │   │ ├─┬ path-array@1.0.1 
│ │   │   │ │ └─┬ array-index@1.0.0 
│ │   │   │ │   └─┬ es6-symbol@3.1.0 
│ │   │   │ │     ├── d@0.1.1 
│ │   │   │ │     └─┬ es5-ext@0.10.11 
│ │   │   │ │       ├── es6-iterator@2.0.0 
│ │   │   │ │       └── es6-symbol@3.0.2 
│ │   │   │ ├─┬ rimraf@2.5.2 
│ │   │   │ │ └─┬ glob@7.0.5 
│ │   │   │ │   └── fs.realpath@1.0.0 
│ │   │   │ ├─┬ tar@2.2.1 
│ │   │   │ │ └── block-stream@0.0.9 
│ │   │   │ └─┬ which@1.2.10 
│ │   │   │   └── isexe@1.1.2 
│ │   │   ├─┬ node-ninja@1.0.1 
│ │   │   │ ├─┬ glob@4.5.3 
│ │   │   │ │ └── minimatch@2.0.10 
│ │   │   │ └── minimatch@1.0.0 
│ │   │   ├── noop-logger@0.1.1 
│ │   │   ├─┬ npmlog@2.0.4 
│ │   │   │ ├── ansi@0.3.1 
│ │   │   │ ├─┬ are-we-there-yet@1.1.2 
│ │   │   │ │ └── delegates@1.0.0 
│ │   │   │ └─┬ gauge@1.2.7 
│ │   │   │   ├── has-unicode@2.0.1 
│ │   │   │   ├─┬ lodash.pad@4.4.0 
│ │   │   │   │ ├── lodash._baseslice@4.0.0 
│ │   │   │   │ ├── lodash._basetostring@4.12.0 
│ │   │   │   │ └── lodash.tostring@4.1.3 
│ │   │   │   ├── lodash.padend@4.5.0 
│ │   │   │   └── lodash.padstart@4.5.0 
│ │   │   ├── os-homedir@1.0.1 
│ │   │   ├─┬ pump@1.0.1 
│ │   │   │ └── end-of-stream@1.1.0 
│ │   │   ├─┬ rc@1.1.6 
│ │   │   │ ├── deep-extend@0.4.1 
│ │   │   │ └── ini@1.3.4 
│ │   │   ├─┬ simple-get@1.4.3 
│ │   │   │ └── unzip-response@1.0.0 
│ │   │   ├── tar-fs@1.13.0 
│ │   │   └─┬ tar-stream@1.5.2 
│ │   │     └─┬ readable-stream@2.1.4 
│ │   │       └── isarray@1.0.0 
│ │   ├─┬ levelup@1.3.2
│ │   │ └─┬ deferred-leveldown@1.2.1
│ │   │   └── abstract-leveldown@2.4.1 
│ │   ├─┬ request@2.72.0
│ │   │ ├─┬ bl@1.1.2
│ │   │ │ └─┬ readable-stream@2.0.6 
│ │   │ │   └── isarray@1.0.0 
│ │   │ └─┬ http-signature@1.1.1
│ │   │   └─┬ sshpk@1.8.3
│ │   │     ├── ecc-jsbn@0.1.1 
│ │   │     ├── jodid25519@1.0.2 
│ │   │     ├── jsbn@0.1.0 
│ │   │     └── tweetnacl@0.13.3 
│ │   ├─┬ through2@2.0.1
│ │   │ └─┬ readable-stream@2.0.6 
│ │   │   └── isarray@1.0.0 
│ │   └─┬ websql@0.4.4 
│ │     ├── immediate@3.2.2 
│ │     ├── noop-fn@1.0.0 
│ │     └─┬ sqlite3@3.1.4 
│ │       └─┬ node-pre-gyp@0.6.28
│ │         ├── nopt@3.0.6 
│ │         ├─┬ npmlog@2.0.3
│ │         │ ├── ansi@0.3.1 
│ │         │ ├─┬ are-we-there-yet@1.1.2 
│ │         │ │ └── delegates@1.0.0 
│ │         │ └─┬ gauge@1.2.7 
│ │         │   ├─┬ lodash.pad@4.4.0 
│ │         │   │ ├── lodash._baseslice@4.0.0 
│ │         │   │ ├── lodash._basetostring@4.12.0 
│ │         │   │ └── lodash.tostring@4.1.3 
│ │         │   ├── lodash.padend@4.5.0 
│ │         │   └── lodash.padstart@4.5.0 
│ │         ├─┬ rc@1.1.6 
│ │         │ ├── deep-extend@0.4.1 
│ │         │ └── ini@1.3.4 
│ │         ├─┬ request@2.72.0
│ │         │ ├─┬ bl@1.1.2
│ │         │ │ └── readable-stream@2.0.6 
│ │         │ └─┬ http-signature@1.1.1
│ │         │   └─┬ sshpk@1.8.3
│ │         │     ├── ecc-jsbn@0.1.1 
│ │         │     ├── jodid25519@1.0.2 
│ │         │     ├── jsbn@0.1.0 
│ │         │     └── tweetnacl@0.13.3 
│ │         ├── rimraf@2.5.2 
│ │         ├─┬ tar@2.2.1 
│ │         │ └── block-stream@0.0.9 
│ │         └─┬ tar-pack@3.1.3
│ │           └─┬ readable-stream@2.0.6 
│ │             └── isarray@1.0.0 
│ └─┬ pouchdb-find@0.1.0
│   └─┬ jshint@2.9.2
│     └── minimatch@2.0.10 
├─┬ multiplex@6.7.0
│ ├─┬ duplexify@3.4.3
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
│   ├── graceful-fs@4.1.4 
│   ├── jsonfile@2.3.1 
│   └─┬ rimraf@2.5.2 
│     └─┬ glob@7.0.5 
│       ├── fs.realpath@1.0.0 
│       ├─┬ inflight@1.0.5 
│       │ └── wrappy@1.0.2 
│       ├─┬ minimatch@3.0.2 
│       │ └─┬ brace-expansion@1.1.5 
│       │   ├── balanced-match@0.4.1 
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
│ ├── immediate@3.0.5 
│ ├─┬ inline-process-browser@1.0.0 
│ │ ├─┬ falafel@1.2.0 
│ │ │ ├── acorn@1.2.2 
│ │ │ ├── foreach@2.0.5 
│ │ │ └── object-keys@1.0.9 
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
│ ├── tough-cookie@2.2.2 
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
│ │ ├─┬ pouchdb@5.4.4 
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
│ │ │ │ │ └─┬ sshpk@1.8.3 
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
│ │ ├── pouchdb-promise@5.4.4 
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
│ │ ├─┬ equals@1.1.0 
│ │ │ └── @jkroso/type@1.1.1 
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
│   ├── graceful-fs@4.1.4 
│   ├── jsonfile@2.3.1 
│   └─┬ rimraf@2.5.2 
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
│ ├─┬ immediate@3.0.5 
│ │ └── unreachable-branch-transform@0.3.0 
│ ├─┬ inline-process-browser@1.0.0 
│ │ ├─┬ falafel@1.2.0 
│ │ │ ├── acorn@1.2.2 
│ │ │ ├── foreach@2.0.5 
│ │ │ └── object-keys@1.0.9 
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
│ ├─┬ duplexify@3.4.3 
│ │ ├── end-of-stream@1.0.0 
│ │ └─┬ readable-stream@2.1.4 
│ │   └── isarray@1.0.0 
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
│ │ │ └─┬ request@2.72.0 
│ │ │   ├── extend@3.0.0 
│ │ │   └── qs@6.1.0 
│ │ ├── pouchdb-binary-utils@5.4.4 
│ │ ├── pouchdb-errors@5.4.4 
│ │ ├── pouchdb-md5@5.4.4 
│ │ └── pouchdb-utils@5.4.4 
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
│ │ │   │ └── url-template@2.0.7 
│ │ │   ├── github-from-package@0.0.0 
│ │ │   ├─┬ node-gyp@3.3.1 
│ │ │   │ ├── fstream@1.0.10 
│ │ │   │ ├─┬ glob@4.5.3 
│ │ │   │ │ └── minimatch@2.0.10 
│ │ │   │ ├── minimatch@1.0.0 
│ │ │   │ ├─┬ nopt@3.0.6 
│ │ │   │ │ └── abbrev@1.0.9 
│ │ │   │ ├── osenv@0.1.3 
│ │ │   │ ├─┬ path-array@1.0.1 
│ │ │   │ │ └─┬ array-index@1.0.0 
│ │ │   │ │   └─┬ es6-symbol@3.1.0 
│ │ │   │ │     ├── d@0.1.1 
│ │ │   │ │     └─┬ es5-ext@0.10.11 
│ │ │   │ │       ├── es6-iterator@2.0.0 
│ │ │   │ │       └── es6-symbol@3.0.2 
│ │ │   │ ├─┬ tar@2.2.1 
│ │ │   │ │ └── block-stream@0.0.9 
│ │ │   │ └─┬ which@1.2.10 
│ │ │   │   └── isexe@1.1.2 
│ │ │   ├─┬ node-ninja@1.0.1 
│ │ │   │ ├─┬ glob@4.5.3 
│ │ │   │ │ └── minimatch@2.0.10 
│ │ │   │ └── minimatch@1.0.0 
│ │ │   ├── noop-logger@0.1.1 
│ │ │   ├─┬ npmlog@2.0.4 
│ │ │   │ ├── ansi@0.3.1 
│ │ │   │ ├─┬ are-we-there-yet@1.1.2 
│ │ │   │ │ └── delegates@1.0.0 
│ │ │   │ └─┬ gauge@1.2.7 
│ │ │   │   ├── has-unicode@2.0.1 
│ │ │   │   ├─┬ lodash.pad@4.4.0 
│ │ │   │   │ ├── lodash._baseslice@4.0.0 
│ │ │   │   │ ├── lodash._basetostring@4.12.0 
│ │ │   │   │ └── lodash.tostring@4.1.3 
│ │ │   │   ├── lodash.padend@4.5.0 
│ │ │   │   └── lodash.padstart@4.5.0 
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
│ │   └─┬ through2@2.0.1 
│ │     └─┬ readable-stream@2.0.6 
│ │       └── isarray@1.0.0 
│ ├─┬ pouchdb-core@5.4.4 
│ │ ├── double-ended-queue@2.0.0-0 
│ │ ├── pouchdb-collections@1.0.1 
│ │ ├── pouchdb-merge@5.4.4 
│ │ └── scope-eval@0.0.3 
│ ├─┬ pouchdb-mapreduce@5.4.4 
│ │ ├── pouchdb-mapreduce-utils@5.4.4 
│ │ └── spark-md5@2.0.2 
│ └─┬ pouchdb-replication@5.4.4 
│   ├── pouchdb-checkpointer@5.4.4 
│   └── pouchdb-generate-replication-id@5.4.4 
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
│ │ ├─┬ minimatch@3.0.2 
│ │ │ └─┬ brace-expansion@1.1.5 
│ │ │   └── balanced-match@0.4.1 
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
│ │ │ ├─┬ pouchdb@5.4.4 
│ │ │ │ ├── double-ended-queue@2.0.0-0 
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
│ │ │ │ │   │ └── url-template@2.0.7 
│ │ │ │ │   ├── github-from-package@0.0.0 
│ │ │ │ │   ├─┬ node-gyp@3.3.1 
│ │ │ │ │   │ ├── fstream@1.0.10 
│ │ │ │ │   │ ├─┬ glob@4.5.3 
│ │ │ │ │   │ │ └── minimatch@2.0.10 
│ │ │ │ │   │ ├── minimatch@1.0.0 
│ │ │ │ │   │ ├─┬ nopt@3.0.6 
│ │ │ │ │   │ │ └── abbrev@1.0.9 
│ │ │ │ │   │ ├─┬ osenv@0.1.3 
│ │ │ │ │   │ │ └── os-tmpdir@1.0.1 
│ │ │ │ │   │ ├─┬ path-array@1.0.1 
│ │ │ │ │   │ │ └─┬ array-index@1.0.0 
│ │ │ │ │   │ │   └─┬ es6-symbol@3.1.0 
│ │ │ │ │   │ │     ├── d@0.1.1 
│ │ │ │ │   │ │     └─┬ es5-ext@0.10.11 
│ │ │ │ │   │ │       ├── es6-iterator@2.0.0 
│ │ │ │ │   │ │       └── es6-symbol@3.0.2 
│ │ │ │ │   │ ├─┬ rimraf@2.5.2 
│ │ │ │ │   │ │ └─┬ glob@7.0.5 
│ │ │ │ │   │ │   └── fs.realpath@1.0.0 
│ │ │ │ │   │ ├─┬ tar@2.2.1 
│ │ │ │ │   │ │ └── block-stream@0.0.9 
│ │ │ │ │   │ └─┬ which@1.2.10 
│ │ │ │ │   │   └── isexe@1.1.2 
│ │ │ │ │   ├─┬ node-ninja@1.0.1 
│ │ │ │ │   │ ├─┬ glob@4.5.3 
│ │ │ │ │   │ │ └── minimatch@2.0.10 
│ │ │ │ │   │ └── minimatch@1.0.0 
│ │ │ │ │   ├── noop-logger@0.1.1 
│ │ │ │ │   ├─┬ npmlog@2.0.4 
│ │ │ │ │   │ ├── ansi@0.3.1 
│ │ │ │ │   │ ├─┬ are-we-there-yet@1.1.2 
│ │ │ │ │   │ │ └── delegates@1.0.0 
│ │ │ │ │   │ └─┬ gauge@1.2.7 
│ │ │ │ │   │   ├── has-unicode@2.0.1 
│ │ │ │ │   │   ├─┬ lodash.pad@4.4.0 
│ │ │ │ │   │   │ ├── lodash._baseslice@4.0.0 
│ │ │ │ │   │   │ ├── lodash._basetostring@4.12.0 
│ │ │ │ │   │   │ └── lodash.tostring@4.1.3 
│ │ │ │ │   │   ├── lodash.padend@4.5.0 
│ │ │ │ │   │   └── lodash.padstart@4.5.0 
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
│ │ │ │ │ │ └─┬ sshpk@1.8.3 
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
│ │ │ │       │ └─┬ gauge@1.2.7 
│ │ │ │       │   ├─┬ lodash.pad@4.4.0 
│ │ │ │       │   │ ├── lodash._baseslice@4.0.0 
│ │ │ │       │   │ ├── lodash._basetostring@4.12.0 
│ │ │ │       │   │ └── lodash.tostring@4.1.3 
│ │ │ │       │   ├── lodash.padend@4.5.0 
│ │ │ │       │   └── lodash.padstart@4.5.0 
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
│ │ │ │       │   │   ├── balanced-match@0.4.1 
│ │ │ │       │   │   └── concat-map@0.0.1 
│ │ │ │       │   └── path-is-absolute@1.0.0 
│ │ │ │       ├─┬ tar@2.2.1 
│ │ │ │       │ ├── block-stream@0.0.9 
│ │ │ │       │ ├─┬ fstream@1.0.9
│ │ │ │       │ │ └── graceful-fs@4.1.4 
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
│ │ │ ├── pouchdb-promise@5.4.4 
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
│ │ │ │ │ └─┬ brace-expansion@1.1.5 
│ │ │ │ │   ├── balanced-match@0.4.1 
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
│ │ │ ├─┬ equals@1.1.0 
│ │ │ │ └── @jkroso/type@1.1.1 
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
│ │ │ │ │ │ ├── minimatch@3.0.2 
│ │ │ │ │ │ └── path-is-absolute@1.0.0 
│ │ │ │ │ ├── graceful-fs@4.1.4 
│ │ │ │ │ ├─┬ mkdirp@0.5.1 
│ │ │ │ │ │ └── minimist@0.0.8 
│ │ │ │ │ └── q@1.4.1 
│ │ │ │ ├── esprima-fb@15001.1.0-dev-harmony-fb 
│ │ │ │ ├── object-assign@2.1.1 
│ │ │ │ └─┬ source-map@0.4.4 
│ │ │ │   └── amdefine@1.0.0 
│ │ │ └── through@2.3.8 
│ │ ├─┬ immediate@3.0.5 
│ │ │ └── unreachable-branch-transform@0.3.0 
│ │ ├─┬ inline-process-browser@1.0.0 
│ │ │ ├─┬ falafel@1.2.0 
│ │ │ │ ├── acorn@1.2.2 
│ │ │ │ ├── foreach@2.0.5 
│ │ │ │ └── object-keys@1.0.9 
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
│ │ ├─┬ duplexify@3.4.3 
│ │ │ ├─┬ end-of-stream@1.0.0 
│ │ │ │ └─┬ once@1.3.3 
│ │ │ │   └── wrappy@1.0.2 
│ │ │ └─┬ readable-stream@2.1.4 
│ │ │   └── isarray@1.0.0 
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
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPromiseQueue.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testTests.js
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
DEBUG createNativeListener: listening 50186
ok 1 Should throw
# teardown
# setup
# emits incomingConnectionState
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50188
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
DEBUG createNativeListener: listening 50191
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
DEBUG createNativeListener: listening 50195
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
DEBUG createNativeListener: listening 50200
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
DEBUG createNativeListener: listening 50204
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
DEBUG createNativeListener: listening 50208
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
DEBUG createNativeListener: listening 50212
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
DEBUG createNativeListener: listening 50216
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
DEBUG createNativeListener: listening 50268
ok 31 we should not have gotten an error
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
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
DEBUG createNativeListener: listening 50272
ok 38 we should not have gotten an error
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
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
DEBUG createNativeListener: listening 50277
# teardown
# setup
# calling createPeerListener after calling stop produces error
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50280
# teardown
# setup
# can call createPeerListener (pleaseConnect === false)
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50283
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
ok 45 port must be in range
# teardown
# setup
# calling createPeerListener (pleaseConnect === true) with unknown peer is error
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50287
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= true
DEBUG createPeerListener: first connection
WARN createPeerListener: 
DEBUG createPeerListener: failedConnection
DEBUG createPeerListener: Recreating listener
DEBUG createPeerListener: createPeerListener creating new server
ok 46 should get error
DEBUG createPeerListener: pleaseConnect= false
# teardown
# setup
# calling createPeerListener twice with same peerIdentifier should return the same port
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50292
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
ok 47 port values should be the same
# teardown
# setup
# createPeerListener - closing connection to native listener closes everything and triggers new listener
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50296
DEBUG createPeerListener: createPeerListener creating new server
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
DEBUG createPeerListener: pleaseConnect= false
ok 49 same peer ID
ok 50 different ports
DEBUG createNativeListener: stream close:
# teardown
# setup
# createPeerListener - closing mux closes listener and triggers a new listener
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50305
DEBUG createPeerListener: createPeerListener creating new server
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
DEBUG createNativeListener: listening 50314
DEBUG createPeerListener: pleaseConnect= true
DEBUG createPeerListener: first connection
DEBUG createPeerListener: forward connection
WARN createPeerListener: 
ok 56 reason should be as expected
DEBUG createPeerListener: Recreating listener
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
# teardown
# setup
# peerListener - forwardConnection, pleaseConnect === false - no native server
DEBUG createNativeListener: creating native server
ok 57 Can call startUpdateAdvertisingAndListening without error
ok 58 Can call startListeningForAdvertisements without error
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createNativeListener: listening 50320
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
DEBUG createPeerListener: pleaseConnect= false
# teardown
# setup
# peerListener - forwardConnection, pleaseConnect === true - with native server
DEBUG createNativeListener: creating native server
ok 62 Can call startUpdateAdvertisingAndListening without error
ok 63 Can call startListeningForAdvertisements without error
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createNativeListener: listening 50327
DEBUG createPeerListener: pleaseConnect= true
DEBUG createPeerListener: first connection
DEBUG createPeerListener: forward connection
ok 64 peerPort != nativePort
ok 65 Should get spontaneous connection
# teardown
# setup
# peerListener - forwardConnection, pleaseConnect === false - with native server
DEBUG createNativeListener: creating native server
ok 66 Can call startUpdateAdvertisingAndListening without error
ok 67 Can call startListeningForAdvertisements without error
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createNativeListener: listening 50332
DEBUG createPeerListener: pleaseConnect= false
ok 68 peerPort != nativePort
DEBUG createPeerListener: first connection
DEBUG createPeerListener: forward connection
ok 69 Should not get unexpected connection
# teardown
# setup
# peerListener - forwardConnection, pleaseConnect === false - with native server and data transfer
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50338
DEBUG createPeerListener: createPeerListener creating new server
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
DEBUG createNativeListener: listening 50345
DEBUG createPeerListener: pleaseConnect= false
ok 74 Second call to existing peerListener returns existing port
# teardown
# setup
# createPeerListener - pleaseConnect === true, failed connection rejects promise
DEBUG createNativeListener: creating native server
ok 75 Can call startUpdateAdvertisingAndListening without error
ok 76 Can call startListeningForAdvertisements without error
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createNativeListener: listening 50349
DEBUG createPeerListener: pleaseConnect= true
DEBUG createPeerListener: first connection
WARN createPeerListener: 
DEBUG createPeerListener: failedConnection
ok 77 got our failed connection
DEBUG createPeerListener: Recreating listener
ok 78 failed connection should reject with error
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
# teardown
# setup
# createPeerListener - pleaseConnect === true, connection resolves promise
DEBUG createNativeListener: creating native server
ok 79 Can call startUpdateAdvertisingAndListening without error
ok 80 Can call startListeningForAdvertisements without error
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createNativeListener: listening 50354
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
DEBUG createNativeListener: listening 50359
DEBUG createPeerListener: pleaseConnect= true
DEBUG createPeerListener: first connection
WARN createPeerListener: was expecting a forward connection to be made
ok 85 reason should be as expected
DEBUG createPeerListener: Recreating listener
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
# teardown
# setup
# peerListener - reverseConnection, pleaseConnect === false - no incoming
DEBUG createNativeListener: creating native server
ok 86 Can call startUpdateAdvertisingAndListening without error
ok 87 Can call startListeningForAdvertisements without error
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createNativeListener: listening 50364
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
DEBUG createPeerListener: pleaseConnect= false
# teardown
# setup
# peerListener - reverseConnection, pleaseConnect === false - with incoming
DEBUG createNativeListener: creating native server
ok 91 Can call startUpdateAdvertisingAndListening without error
ok 92 Can call startListeningForAdvertisements without error
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createNativeListener: listening 50370
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: first connection
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createPeerListener: looking up mux for client port:  50373
DEBUG createPeerListener: reverse connection
DEBUG createPeerListener: looking up mux for client port:  50373
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
DEBUG createNativeListener: listening 50376
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: first connection
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createPeerListener: looking up mux for client port:  50379
DEBUG createPeerListener: reverse connection
DEBUG createPeerListener: looking up mux for client port:  50379
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
DEBUG createNativeListener: listening 50383
# teardown
# setup
# createPeerListener - ask for a new peer when we are not at maximum peers and make sure we do not remove any existing listeners
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50386
# teardown
# setup
# createPeerListener - pleaseConnect = false - test timeout
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50389
# teardown
# setup
# createPeerListener - pleaseConnect = true - test timeout
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50392
# teardown
# setup
# createPeerListener - forward connection - wrong serverPort
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50395
# teardown
# setup
# createPeerListener - forward connection - wrong clientPort
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50398
# teardown
# setup
# createPeerListener - please connect = false, multiple connections out
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50401
# teardown
# setup
# createPeerListener - please connect = false, multiple bi-directional connections
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50404
# teardown
# setup
# createPeerListener - multiple parallel calls
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50407
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
not ok 99 Error: Missing PFX or certificate + private key.
  ---
    operator: error
    expected: undefined
    actual:   [Error: Missing PFX or certificate + private key.]
    at: Test.exports.Test.run (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape-catch/index.js:20:10)
    stack:
      Error: Missing PFX or certificate + private key.
        at Server (tls.js:1064:11)
        at new Server (https.js:16:14)
        at Object.exports.createServer (https.js:33:10)
        at Test.testUtils.setUpServer.lastSyncedSequenceNumber (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js:101:11)
        at Test.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/simpleTape.js:61:16)
        at Test.bound [as _cb] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:62:32)
        at Test.exports.Test.run (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape-catch/index.js:17:10)
        at Test.bound [as run] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:62:32)
        at Object.next [as _onImmediate] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/results.js:66:15)
        at processImmediate [as _immediateCallback] (timers.js:370:15)
  ...
# teardown
# setup
# #_doImmediateSeqUpdate - create new seq doc
not ok 100 Error: Missing PFX or certificate + private key.
  ---
    operator: error
    expected: undefined
    actual:   [Error: Missing PFX or certificate + private key.]
    at: Test.exports.Test.run (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape-catch/index.js:20:10)
    stack:
      Error: Missing PFX or certificate + private key.
        at Server (tls.js:1064:11)
        at new Server (https.js:16:14)
        at Object.exports.createServer (https.js:33:10)
        at Object.module.exports.setUpServer (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/testUtils.js:554:57)
        at Test.testUtils.setUpServer.lastSyncedSequenceNumber (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js:124:34)
        at Test.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/simpleTape.js:61:16)
        at Test.bound [as _cb] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:62:32)
        at Test.exports.Test.run (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape-catch/index.js:17:10)
        at Test.bound [as run] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:62:32)
        at Object.next [as _onImmediate] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/results.js:66:15)
        at processImmediate [as _immediateCallback] (timers.js:370:15)
  ...
# teardown
# setup
# #_doImmediateSeqUpdate - doc exists, need to get rev and update
not ok 101 Error: Missing PFX or certificate + private key.
  ---
    operator: error
    expected: undefined
    actual:   [Error: Missing PFX or certificate + private key.]
    at: Test.exports.Test.run (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape-catch/index.js:20:10)
    stack:
      Error: Missing PFX or certificate + private key.
        at Server (tls.js:1064:11)
        at new Server (https.js:16:14)
        at Object.exports.createServer (https.js:33:10)
        at Object.module.exports.setUpServer (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/testUtils.js:554:57)
        at Test.testUtils.setUpServer.lastSyncedSequenceNumber (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js:147:36)
        at Test.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/simpleTape.js:61:16)
        at Test.bound [as _cb] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:62:32)
        at Test.exports.Test.run (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape-catch/index.js:17:10)
        at Test.bound [as run] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:62:32)
        at Object.next [as _onImmediate] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/results.js:66:15)
        at processImmediate [as _immediateCallback] (timers.js:370:15)
  ...
# teardown
# setup
# #_doImmediateSeqUpdate - update seq three times
not ok 102 Error: Missing PFX or certificate + private key.
  ---
    operator: error
    expected: undefined
    actual:   [Error: Missing PFX or certificate + private key.]
    at: Test.exports.Test.run (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape-catch/index.js:20:10)
    stack:
      Error: Missing PFX or certificate + private key.
        at Server (tls.js:1064:11)
        at new Server (https.js:16:14)
        at Object.exports.createServer (https.js:33:10)
        at Object.module.exports.setUpServer (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/testUtils.js:554:57)
        at Test.testUtils.setUpServer.lastSyncedSequenceNumber (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js:176:34)
        at Test.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/simpleTape.js:61:16)
        at Test.bound [as _cb] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:62:32)
        at Test.exports.Test.run (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape-catch/index.js:17:10)
        at Test.bound [as run] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:62:32)
        at Object.next [as _onImmediate] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/results.js:66:15)
        at processImmediate [as _immediateCallback] (timers.js:370:15)
  ...
# teardown
# setup
# #_doImmediateSeqUpdate - rev got changed under us
not ok 103 Error: Missing PFX or certificate + private key.
  ---
    operator: error
    expected: undefined
    actual:   [Error: Missing PFX or certificate + private key.]
    at: Test.exports.Test.run (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape-catch/index.js:20:10)
    stack:
      Error: Missing PFX or certificate + private key.
        at Server (tls.js:1064:11)
        at new Server (https.js:16:14)
        at Object.exports.createServer (https.js:33:10)
        at Object.module.exports.setUpServer (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/testUtils.js:554:57)
        at Test.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js:213:34)
        at Test.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/simpleTape.js:61:16)
        at Test.bound [as _cb] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:62:32)
        at Test.exports.Test.run (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape-catch/index.js:17:10)
        at Test.bound [as run] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:62:32)
        at Object.next [as _onImmediate] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/results.js:66:15)
        at processImmediate [as _immediateCallback] (timers.js:370:15)
  ...
# teardown
# setup
# #_doImmediateSeqUpdate - fail if stop is called
not ok 104 Error: Missing PFX or certificate + private key.
  ---
    operator: error
    expected: undefined
    actual:   [Error: Missing PFX or certificate + private key.]
    at: Test.exports.Test.run (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape-catch/index.js:20:10)
    stack:
      Error: Missing PFX or certificate + private key.
        at Server (tls.js:1064:11)
        at new Server (https.js:16:14)
        at Object.exports.createServer (https.js:33:10)
        at Object.module.exports.setUpServer (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/testUtils.js:554:57)
        at Test.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js:250:34)
        at Test.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/simpleTape.js:61:16)
        at Test.bound [as _cb] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:62:32)
        at Test.exports.Test.run (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape-catch/index.js:17:10)
        at Test.bound [as run] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:62:32)
        at Object.next [as _onImmediate] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/results.js:66:15)
        at processImmediate [as _immediateCallback] (timers.js:370:15)
  ...
# teardown
# setup
# #_doImmediateSeqUpdate - stop after get but before put fails right
not ok 105 Error: Missing PFX or certificate + private key.
  ---
    operator: error
    expected: undefined
    actual:   [Error: Missing PFX or certificate + private key.]
    at: Test.exports.Test.run (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape-catch/index.js:20:10)
    stack:
      Error: Missing PFX or certificate + private key.
        at Server (tls.js:1064:11)
        at new Server (https.js:16:14)
        at Object.exports.createServer (https.js:33:10)
        at Object.module.exports.setUpServer (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/testUtils.js:554:57)
        at Test.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js:270:36)
        at Test.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/simpleTape.js:61:16)
        at Test.bound [as _cb] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:62:32)
        at Test.exports.Test.run (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape-catch/index.js:17:10)
        at Test.bound [as run] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:62:32)
        at Object.next [as _onImmediate] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/results.js:66:15)
        at processImmediate [as _immediateCallback] (timers.js:370:15)
  ...
# teardown
# setup
# #update - fail if stop is called
not ok 106 Error: Missing PFX or certificate + private key.
  ---
    operator: error
    expected: undefined
    actual:   [Error: Missing PFX or certificate + private key.]
    at: Test.exports.Test.run (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape-catch/index.js:20:10)
    stack:
      Error: Missing PFX or certificate + private key.
        at Server (tls.js:1064:11)
        at new Server (https.js:16:14)
        at Object.exports.createServer (https.js:33:10)
        at Object.module.exports.setUpServer (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/testUtils.js:554:57)
        at Test.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js:295:34)
        at Test.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/simpleTape.js:61:16)
        at Test.bound [as _cb] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:62:32)
        at Test.exports.Test.run (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape-catch/index.js:17:10)
        at Test.bound [as run] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:62:32)
        at Object.next [as _onImmediate] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/results.js:66:15)
        at processImmediate [as _immediateCallback] (timers.js:370:15)
  ...
# teardown
# setup
# #update - set seq for first time
not ok 107 Error: Missing PFX or certificate + private key.
  ---
    operator: error
    expected: undefined
    actual:   [Error: Missing PFX or certificate + private key.]
    at: Test.exports.Test.run (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape-catch/index.js:20:10)
    stack:
      Error: Missing PFX or certificate + private key.
        at Server (tls.js:1064:11)
        at new Server (https.js:16:14)
        at Object.exports.createServer (https.js:33:10)
        at Object.module.exports.setUpServer (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/testUtils.js:554:57)
        at Test.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js:321:34)
        at Test.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/simpleTape.js:61:16)
        at Test.bound [as _cb] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:62:32)
        at Test.exports.Test.run (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape-catch/index.js:17:10)
        at Test.bound [as run] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:62:32)
        at Object.next [as _onImmediate] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/results.js:66:15)
        at processImmediate [as _immediateCallback] (timers.js:370:15)
  ...
# teardown
# setup
# #update - Fail on bad seq value
not ok 108 Error: Missing PFX or certificate + private key.
  ---
    operator: error
    expected: undefined
    actual:   [Error: Missing PFX or certificate + private key.]
    at: Test.exports.Test.run (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape-catch/index.js:20:10)
    stack:
      Error: Missing PFX or certificate + private key.
        at Server (tls.js:1064:11)
        at new Server (https.js:16:14)
        at Object.exports.createServer (https.js:33:10)
        at Object.module.exports.setUpServer (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/testUtils.js:554:57)
        at Test.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js:342:34)
        at Test.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/simpleTape.js:61:16)
        at Test.bound [as _cb] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:62:32)
        at Test.exports.Test.run (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape-catch/index.js:17:10)
        at Test.bound [as run] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:62:32)
        at Object.next [as _onImmediate] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/results.js:66:15)
        at processImmediate [as _immediateCallback] (timers.js:370:15)
  ...
# teardown
# setup
# #update - do we cancel timer properly on an immediate?
not ok 109 Error: Missing PFX or certificate + private key.
  ---
    operator: error
    expected: undefined
    actual:   [Error: Missing PFX or certificate + private key.]
    at: Test.exports.Test.run (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape-catch/index.js:20:10)
    stack:
      Error: Missing PFX or certificate + private key.
        at Server (tls.js:1064:11)
        at new Server (https.js:16:14)
        at Object.exports.createServer (https.js:33:10)
        at Object.module.exports.setUpServer (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/testUtils.js:554:57)
        at Test.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js:366:34)
        at Test.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/simpleTape.js:61:16)
        at Test.bound [as _cb] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:62:32)
        at Test.exports.Test.run (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape-catch/index.js:17:10)
        at Test.bound [as run] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:62:32)
        at Object.next [as _onImmediate] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/results.js:66:15)
        at processImmediate [as _immediateCallback] (timers.js:370:15)
  ...
# teardown
# setup
# #update - do we wait for blocked update
not ok 110 Error: Missing PFX or certificate + private key.
  ---
    operator: error
    expected: undefined
    actual:   [Error: Missing PFX or certificate + private key.]
    at: Test.exports.Test.run (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape-catch/index.js:20:10)
    stack:
      Error: Missing PFX or certificate + private key.
        at Server (tls.js:1064:11)
        at new Server (https.js:16:14)
        at Object.exports.createServer (https.js:33:10)
        at Object.module.exports.setUpServer (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/testUtils.js:554:57)
        at Test.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js:406:34)
        at Test.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/simpleTape.js:61:16)
        at Test.bound [as _cb] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:62:32)
        at Test.exports.Test.run (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape-catch/index.js:17:10)
        at Test.bound [as run] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:62:32)
        at Object.next [as _onImmediate] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/results.js:66:15)
        at processImmediate [as _immediateCallback] (timers.js:370:15)
  ...
# teardown
# setup
# #update - test that we wait long enough
not ok 111 Error: Missing PFX or certificate + private key.
  ---
    operator: error
    expected: undefined
    actual:   [Error: Missing PFX or certificate + private key.]
    at: Test.exports.Test.run (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape-catch/index.js:20:10)
    stack:
      Error: Missing PFX or certificate + private key.
        at Server (tls.js:1064:11)
        at new Server (https.js:16:14)
        at Object.exports.createServer (https.js:33:10)
        at Object.module.exports.setUpServer (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/testUtils.js:554:57)
        at testTimer (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js:438:34)
        at Test.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js:469:3)
        at Test.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/simpleTape.js:61:16)
        at Test.bound [as _cb] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:62:32)
        at Test.exports.Test.run (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape-catch/index.js:17:10)
        at Test.bound [as run] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:62:32)
        at Object.next [as _onImmediate] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/results.js:66:15)
        at processImmediate [as _immediateCallback] (timers.js:370:15)
  ...
# teardown
# setup
# #update - test that we pick up new sequences while we wait
not ok 112 Error: Missing PFX or certificate + private key.
  ---
    operator: error
    expected: undefined
    actual:   [Error: Missing PFX or certificate + private key.]
    at: Test.exports.Test.run (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape-catch/index.js:20:10)
    stack:
      Error: Missing PFX or certificate + private key.
        at Server (tls.js:1064:11)
        at new Server (https.js:16:14)
        at Object.exports.createServer (https.js:33:10)
        at Object.module.exports.setUpServer (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/testUtils.js:554:57)
        at testTimer (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js:438:34)
        at Test.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js:480:5)
        at Test.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/simpleTape.js:61:16)
        at Test.bound [as _cb] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:62:32)
        at Test.exports.Test.run (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape-catch/index.js:17:10)
        at Test.bound [as run] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:62:32)
        at Object.next [as _onImmediate] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/results.js:66:15)
        at processImmediate [as _immediateCallback] (timers.js:370:15)
  ...
# teardown
# setup
# closeAll can close even when connections open
ok 113 not possible to connect to the server anymore
# teardown
# setup
# closeAll with promise
ok 114 not possible to connect to the server anymore
# teardown
# setup
# closeAll properly throws when closing a non open server with eatNotRunning set to false
ok 115 Got the right error
# teardown
# setup
# closeAll works even with a server that is not listening yet witheatNotRunning set to true
# teardown
# setup
# enqueue and run in order
ok 116 firstPromise setTimeout
ok 117 firstPromise result
ok 118 firstPromise testValue
ok 119 secondPromise setTimeout
ok 120 secondPromise result
ok 121 secondPromise testValue
ok 122 thirdPromise in promise
ok 123 thirdPromise result
ok 124 thirdPromise testValue
# teardown
# setup
# enqueueAtTop and run backwards
ok 125 thirdPromise - first to run
ok 126 thirdPromise - in resolve
ok 127 secondPromise - second to run
ok 128 secondPromise - in catch
ok 129 firstPromise - third to run
ok 130 firstPromise - in then
ok 131 testing promises
# teardown
# setup
# mix enqueue and enqueueAtTop
ok 132 fourth
ok 133 fourth
ok 134 second
ok 135 secondPromise - in then
ok 136 first
ok 137 firstPromise - in catch
ok 138 third
ok 139 thirdPromise - in then
ok 140 testingPromises
# teardown
# setup
# queues handled independently
ok 141 all short operations completed before the long resolves
# teardown
# setup
# basic
ok 142 sane
# teardown
# setup
# another
ok 143 sane
# teardown
# setup
# #startListeningForAdvertisements should fail if start not called
ok 144 specific error should be returned
# teardown
ok 145 error should be null
ok 146 error should be null
# setup
# #startUpdateAdvertisingAndListening should fail if start not called
ok 147 specific error should be returned
# teardown
ok 148 error should be null
ok 149 error should be null
# setup
# should be able to call #stopListeningForAdvertisements many times
Uncaught Promise Rejection: Error: Missing PFX or certificate + private key.
Error: Missing PFX or certificate + private key.
    at Server (tls.js:1064:11)
    at new Server (https.js:16:14)
    at Object.exports.createServer (https.js:33:10)
    at Object.fn (/Users/thali/Github/Thali_CordovaPlugin/thali/NextGeneration/thaliMobileNativeWrapper.js:241:27)
    at /Users/thali/Github/Thali_CordovaPlugin/thali/NextGeneration/promiseQueue.js:96:21
    at tryToUnwrap (/Users/thali/Github/Thali_CordovaPlugin/thali/node_modules/lie/lib/index.js:171:5)
    at tryCatch (/Users/thali/Github/Thali_CordovaPlugin/thali/node_modules/lie/lib/index.js:183:17)
    at safelyResolveThenable (/Users/thali/Github/Thali_CordovaPlugin/thali/node_modules/lie/lib/index.js:174:16)
    at new Promise (/Users/thali/Github/Thali_CordovaPlugin/thali/node_modules/lie/lib/index.js:32:5)
    at /Users/thali/Github/Thali_CordovaPlugin/thali/NextGeneration/promiseQueue.js:94:14
    at Array.1 (/Users/thali/Github/Thali_CordovaPlugin/thali/node_modules/lie/lib/index.js:88:21)
    at nextTick (/Users/thali/Github/Thali_CordovaPlugin/thali/node_modules/immediate/lib/index.js:61:18)
    at process._tickCallback (node.js:917:13)
****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
-e [0;31mcompilation aborted
 [0m
build aborted
 [0m

npm http request GET https://registry.npmjs.org/fs-extra-promise
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/express
npm http request GET https://registry.npmjs.org/socket.io
npm http request GET https://registry.npmjs.org/winston
npm http 200 https://registry.npmjs.org/winston
npm http 200 https://registry.npmjs.org/socket.io
npm http 200 https://registry.npmjs.org/fs-extra-promise
npm http 200 https://registry.npmjs.org/lie
npm http fetch GET https://registry.npmjs.org/socket.io/-/socket.io-1.3.6.tgz
npm http fetch GET https://registry.npmjs.org/fs-extra-promise/-/fs-extra-promise-0.2.0.tgz
npm http fetch GET https://registry.npmjs.org/lie/-/lie-3.0.4.tgz
npm http 200 https://registry.npmjs.org/express
npm http fetch 200 https://registry.npmjs.org/lie/-/lie-3.0.4.tgz
npm http fetch 200 https://registry.npmjs.org/fs-extra-promise/-/fs-extra-promise-0.2.0.tgz
npm http fetch 200 https://registry.npmjs.org/socket.io/-/socket.io-1.3.6.tgz
npm http request GET https://registry.npmjs.org/content-type
npm http request GET https://registry.npmjs.org/content-disposition
npm http request GET https://registry.npmjs.org/accepts
npm http request GET https://registry.npmjs.org/array-flatten
npm http request GET https://registry.npmjs.org/cookie
npm http request GET https://registry.npmjs.org/cookie-signature
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/etag
npm http request GET https://registry.npmjs.org/depd
npm http request GET https://registry.npmjs.org/escape-html
npm http request GET https://registry.npmjs.org/finalhandler
npm http request GET https://registry.npmjs.org/fresh
npm http request GET https://registry.npmjs.org/merge-descriptors
npm http request GET https://registry.npmjs.org/methods
npm http request GET https://registry.npmjs.org/on-finished
npm http request GET https://registry.npmjs.org/parseurl
npm http request GET https://registry.npmjs.org/proxy-addr
npm http request GET https://registry.npmjs.org/path-to-regexp
npm http request GET https://registry.npmjs.org/send
npm http request GET https://registry.npmjs.org/vary
npm http request GET https://registry.npmjs.org/utils-merge
npm http request GET https://registry.npmjs.org/type-is
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/range-parser
npm http request GET https://registry.npmjs.org/serve-static
npm http 200 https://registry.npmjs.org/content-type
npm http 304 https://registry.npmjs.org/content-disposition
npm http 200 https://registry.npmjs.org/array-flatten
npm http 200 https://registry.npmjs.org/cookie
npm http 200 https://registry.npmjs.org/accepts
npm http fetch GET https://registry.npmjs.org/content-type/-/content-type-1.0.2.tgz
npm http 200 https://registry.npmjs.org/cookie-signature
npm http 200 https://registry.npmjs.org/etag
npm http 200 https://registry.npmjs.org/debug
npm http 200 https://registry.npmjs.org/depd
npm http 200 https://registry.npmjs.org/escape-html
npm http 304 https://registry.npmjs.org/fresh
npm http 304 https://registry.npmjs.org/methods
npm http 304 https://registry.npmjs.org/on-finished
npm http 200 https://registry.npmjs.org/merge-descriptors
npm http 200 https://registry.npmjs.org/finalhandler
npm http 200 https://registry.npmjs.org/parseurl
npm http 304 https://registry.npmjs.org/vary
npm http 200 https://registry.npmjs.org/proxy-addr
npm http 200 https://registry.npmjs.org/path-to-regexp
npm http 200 https://registry.npmjs.org/send
npm http 200 https://registry.npmjs.org/utils-merge
npm http 200 https://registry.npmjs.org/range-parser
npm http 200 https://registry.npmjs.org/type-is
npm http 200 https://registry.npmjs.org/qs
npm http fetch 200 https://registry.npmjs.org/content-type/-/content-type-1.0.2.tgz
npm http 200 https://registry.npmjs.org/serve-static
npm http fetch GET https://registry.npmjs.org/type-is/-/type-is-1.6.13.tgz
npm http fetch GET https://registry.npmjs.org/serve-static/-/serve-static-1.10.3.tgz
npm http fetch 200 https://registry.npmjs.org/type-is/-/type-is-1.6.13.tgz
npm http fetch 200 https://registry.npmjs.org/serve-static/-/serve-static-1.10.3.tgz
npm http request GET https://registry.npmjs.org/mime-types
npm http request GET https://registry.npmjs.org/negotiator
npm http 200 https://registry.npmjs.org/mime-types
npm http 200 https://registry.npmjs.org/negotiator
npm http fetch GET https://registry.npmjs.org/mime-types/-/mime-types-2.1.11.tgz
npm http fetch 200 https://registry.npmjs.org/mime-types/-/mime-types-2.1.11.tgz
npm http request GET https://registry.npmjs.org/mime-db
npm http 200 https://registry.npmjs.org/mime-db
npm http fetch GET https://registry.npmjs.org/mime-db/-/mime-db-1.23.0.tgz
npm http fetch 200 https://registry.npmjs.org/mime-db/-/mime-db-1.23.0.tgz
npm http request GET https://registry.npmjs.org/ms
npm http 200 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/unpipe
npm http 304 https://registry.npmjs.org/unpipe
npm http request GET https://registry.npmjs.org/ee-first
npm http 304 https://registry.npmjs.org/ee-first
npm http request GET https://registry.npmjs.org/forwarded
npm http request GET https://registry.npmjs.org/ipaddr.js
npm http 304 https://registry.npmjs.org/forwarded
npm http 200 https://registry.npmjs.org/ipaddr.js
npm http request GET https://registry.npmjs.org/destroy
npm http request GET https://registry.npmjs.org/http-errors
npm http request GET https://registry.npmjs.org/mime
npm http request GET https://registry.npmjs.org/statuses
npm http 304 https://registry.npmjs.org/destroy
npm http 200 https://registry.npmjs.org/http-errors
npm http 200 https://registry.npmjs.org/mime
npm http 200 https://registry.npmjs.org/statuses
npm http request GET https://registry.npmjs.org/inherits
npm http 200 https://registry.npmjs.org/inherits
npm http fetch GET https://registry.npmjs.org/send/-/send-0.13.2.tgz
npm http fetch 200 https://registry.npmjs.org/send/-/send-0.13.2.tgz
npm http request GET https://registry.npmjs.org/media-typer
npm http 304 https://registry.npmjs.org/media-typer
npm http request GET https://registry.npmjs.org/fs-extra
npm http request GET https://registry.npmjs.org/bluebird
npm http 200 https://registry.npmjs.org/fs-extra
npm http fetch GET https://registry.npmjs.org/fs-extra/-/fs-extra-0.21.0.tgz
npm http 200 https://registry.npmjs.org/bluebird
npm http fetch 200 https://registry.npmjs.org/fs-extra/-/fs-extra-0.21.0.tgz
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/jsonfile
npm http request GET https://registry.npmjs.org/rimraf
npm http 200 https://registry.npmjs.org/jsonfile
npm http 200 https://registry.npmjs.org/rimraf
npm http 200 https://registry.npmjs.org/graceful-fs
npm http fetch GET https://registry.npmjs.org/jsonfile/-/jsonfile-2.3.1.tgz
npm http fetch GET https://registry.npmjs.org/graceful-fs/-/graceful-fs-4.1.4.tgz
npm http fetch 200 https://registry.npmjs.org/graceful-fs/-/graceful-fs-4.1.4.tgz
npm http fetch 200 https://registry.npmjs.org/jsonfile/-/jsonfile-2.3.1.tgz
npm http request GET https://registry.npmjs.org/glob
npm http 200 https://registry.npmjs.org/glob
npm http fetch GET https://registry.npmjs.org/glob/-/glob-7.0.5.tgz
npm http fetch 200 https://registry.npmjs.org/glob/-/glob-7.0.5.tgz
npm http request GET https://registry.npmjs.org/fs.realpath
npm http request GET https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/once
npm http request GET https://registry.npmjs.org/path-is-absolute
npm http 200 https://registry.npmjs.org/fs.realpath
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http 200 https://registry.npmjs.org/inflight
npm http 304 https://registry.npmjs.org/once
npm http 200 https://registry.npmjs.org/minimatch
npm http fetch GET https://registry.npmjs.org/fs.realpath/-/fs.realpath-1.0.0.tgz
npm http fetch GET https://registry.npmjs.org/inflight/-/inflight-1.0.5.tgz
npm http fetch GET https://registry.npmjs.org/minimatch/-/minimatch-3.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/inflight/-/inflight-1.0.5.tgz
npm http fetch 200 https://registry.npmjs.org/fs.realpath/-/fs.realpath-1.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/minimatch/-/minimatch-3.0.2.tgz
npm http request GET https://registry.npmjs.org/wrappy
npm http 200 https://registry.npmjs.org/wrappy
npm http fetch GET https://registry.npmjs.org/wrappy/-/wrappy-1.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/wrappy/-/wrappy-1.0.2.tgz
npm http request GET https://registry.npmjs.org/brace-expansion
npm http 200 https://registry.npmjs.org/brace-expansion
npm http fetch GET https://registry.npmjs.org/brace-expansion/-/brace-expansion-1.1.5.tgz
npm http fetch 200 https://registry.npmjs.org/brace-expansion/-/brace-expansion-1.1.5.tgz
npm http request GET https://registry.npmjs.org/balanced-match
npm http request GET https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/concat-map
npm http 200 https://registry.npmjs.org/balanced-match
npm http fetch GET https://registry.npmjs.org/balanced-match/-/balanced-match-0.4.1.tgz
npm http fetch 200 https://registry.npmjs.org/balanced-match/-/balanced-match-0.4.1.tgz
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http request GET https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/immediate
npm http 200 https://registry.npmjs.org/es3ify
npm http fetch GET https://registry.npmjs.org/es3ify/-/es3ify-0.2.2.tgz
npm http 304 https://registry.npmjs.org/immediate
npm http 200 https://registry.npmjs.org/unreachable-branch-transform
npm http 200 https://registry.npmjs.org/inline-process-browser
npm http fetch 200 https://registry.npmjs.org/es3ify/-/es3ify-0.2.2.tgz
npm http request GET https://registry.npmjs.org/jstransform
npm http request GET https://registry.npmjs.org/esprima
npm http request GET https://registry.npmjs.org/through
npm http 200 https://registry.npmjs.org/through
npm http 200 https://registry.npmjs.org/esprima
npm http 304 https://registry.npmjs.org/jstransform
npm http fetch GET https://registry.npmjs.org/jstransform/-/jstransform-11.0.3.tgz
npm http fetch 200 https://registry.npmjs.org/jstransform/-/jstransform-11.0.3.tgz
npm http request GET https://registry.npmjs.org/commoner
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/object-assign
npm http request GET https://registry.npmjs.org/source-map
npm http 200 https://registry.npmjs.org/commoner
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 200 https://registry.npmjs.org/object-assign
npm http 200 https://registry.npmjs.org/base62
npm http fetch GET https://registry.npmjs.org/esprima-fb/-/esprima-fb-15001.1.0-dev-harmony-fb.tgz
npm http fetch GET https://registry.npmjs.org/commoner/-/commoner-0.10.4.tgz
npm http fetch GET https://registry.npmjs.org/object-assign/-/object-assign-2.1.1.tgz
npm http fetch GET https://registry.npmjs.org/base62/-/base62-1.1.1.tgz
npm http 200 https://registry.npmjs.org/source-map
npm http fetch 200 https://registry.npmjs.org/esprima-fb/-/esprima-fb-15001.1.0-dev-harmony-fb.tgz
npm http fetch 200 https://registry.npmjs.org/commoner/-/commoner-0.10.4.tgz
npm http fetch 200 https://registry.npmjs.org/base62/-/base62-1.1.1.tgz
npm http fetch 200 https://registry.npmjs.org/object-assign/-/object-assign-2.1.1.tgz
npm http request GET https://registry.npmjs.org/detective
npm http request GET https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/iconv-lite
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/mkdirp
npm http request GET https://registry.npmjs.org/q
npm http request GET https://registry.npmjs.org/recast
npm http 200 https://registry.npmjs.org/detective
npm http 304 https://registry.npmjs.org/private
npm http 200 https://registry.npmjs.org/mkdirp
npm http 200 https://registry.npmjs.org/iconv-lite
npm http 200 https://registry.npmjs.org/commander
npm http 200 https://registry.npmjs.org/q
npm http 200 https://registry.npmjs.org/recast
npm http request GET https://registry.npmjs.org/graceful-readlink
npm http 304 https://registry.npmjs.org/graceful-readlink
npm http request GET https://registry.npmjs.org/defined
npm http request GET https://registry.npmjs.org/acorn
npm http 200 https://registry.npmjs.org/defined
npm http 200 https://registry.npmjs.org/acorn
npm http request GET https://registry.npmjs.org/minimist
npm http 200 https://registry.npmjs.org/minimist
npm http request GET https://registry.npmjs.org/ast-types
npm http fetch GET https://registry.npmjs.org/source-map/-/source-map-0.5.6.tgz
npm http fetch 200 https://registry.npmjs.org/source-map/-/source-map-0.5.6.tgz
npm http 200 https://registry.npmjs.org/ast-types
npm http request GET https://registry.npmjs.org/amdefine
npm http 304 https://registry.npmjs.org/amdefine
npm http request GET https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/falafel
npm http 200 https://registry.npmjs.org/through2
npm http request GET https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/foreach
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/object-keys
npm http request GET https://registry.npmjs.org/xtend
npm http request GET https://registry.npmjs.org/readable-stream
npm http 200 https://registry.npmjs.org/readable-stream
npm http 200 https://registry.npmjs.org/xtend
npm http fetch GET https://registry.npmjs.org/readable-stream/-/readable-stream-1.0.34.tgz
npm http fetch 200 https://registry.npmjs.org/readable-stream/-/readable-stream-1.0.34.tgz
npm http request GET https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/core-util-is
npm http 304 https://registry.npmjs.org/string_decoder
npm http request GET https://registry.npmjs.org/esmangle-evaluator
npm http 200 https://registry.npmjs.org/esmangle-evaluator
npm http fetch GET https://registry.npmjs.org/esmangle-evaluator/-/esmangle-evaluator-1.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/esmangle-evaluator/-/esmangle-evaluator-1.0.1.tgz
npm http request GET https://registry.npmjs.org/has-binary-data
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/socket.io-adapter
npm http request GET https://registry.npmjs.org/socket.io-parser
npm http request GET https://registry.npmjs.org/socket.io-client
npm http request GET https://registry.npmjs.org/engine.io
npm http 304 https://registry.npmjs.org/socket.io-adapter
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/socket.io-parser
npm http 200 https://registry.npmjs.org/socket.io-client
npm http fetch GET https://registry.npmjs.org/debug/-/debug-2.1.0.tgz
npm http fetch GET https://registry.npmjs.org/socket.io-adapter/-/socket.io-adapter-0.3.1.tgz
npm http fetch GET https://registry.npmjs.org/socket.io-parser/-/socket.io-parser-2.2.4.tgz
npm http fetch GET https://registry.npmjs.org/socket.io-client/-/socket.io-client-1.3.6.tgz
npm http 200 https://registry.npmjs.org/engine.io
npm http fetch GET https://registry.npmjs.org/engine.io/-/engine.io-1.5.2.tgz
npm http fetch 200 https://registry.npmjs.org/socket.io-client/-/socket.io-client-1.3.6.tgz
npm http fetch 200 https://registry.npmjs.org/debug/-/debug-2.1.0.tgz
npm http fetch 200 https://registry.npmjs.org/socket.io-adapter/-/socket.io-adapter-0.3.1.tgz
npm http fetch 200 https://registry.npmjs.org/engine.io/-/engine.io-1.5.2.tgz
npm http fetch 200 https://registry.npmjs.org/socket.io-parser/-/socket.io-parser-2.2.4.tgz
npm http 200 https://registry.npmjs.org/has-binary-data
npm http fetch GET https://registry.npmjs.org/has-binary-data/-/has-binary-data-0.1.3.tgz
npm http fetch 200 https://registry.npmjs.org/has-binary-data/-/has-binary-data-0.1.3.tgz
npm http request GET https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/base64id
npm http request GET https://registry.npmjs.org/engine.io-parser
npm http request GET https://registry.npmjs.org/ws
npm http fetch GET https://registry.npmjs.org/debug/-/debug-1.0.3.tgz
npm http 304 https://registry.npmjs.org/base64id
npm http 200 https://registry.npmjs.org/ws
npm http 304 https://registry.npmjs.org/engine.io-parser
npm http fetch 200 https://registry.npmjs.org/debug/-/debug-1.0.3.tgz
npm http fetch GET https://registry.npmjs.org/ws/-/ws-0.7.2.tgz
npm http fetch GET https://registry.npmjs.org/engine.io-parser/-/engine.io-parser-1.2.1.tgz
npm http fetch 200 https://registry.npmjs.org/engine.io-parser/-/engine.io-parser-1.2.1.tgz
npm http fetch 200 https://registry.npmjs.org/ws/-/ws-0.7.2.tgz
npm http request GET https://registry.npmjs.org/blob
npm http request GET https://registry.npmjs.org/has-binary
npm http request GET https://registry.npmjs.org/base64-arraybuffer
npm http request GET https://registry.npmjs.org/arraybuffer.slice
npm http request GET https://registry.npmjs.org/after
npm http request GET https://registry.npmjs.org/utf8
npm http 304 https://registry.npmjs.org/base64-arraybuffer
npm http 304 https://registry.npmjs.org/has-binary
npm http 304 https://registry.npmjs.org/after
npm http 304 https://registry.npmjs.org/arraybuffer.slice
npm http 200 https://registry.npmjs.org/blob
npm http 304 https://registry.npmjs.org/utf8
npm http fetch GET https://registry.npmjs.org/has-binary/-/has-binary-0.1.5.tgz
npm http fetch GET https://registry.npmjs.org/blob/-/blob-0.0.2.tgz
npm http fetch GET https://registry.npmjs.org/utf8/-/utf8-2.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/blob/-/blob-0.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/has-binary/-/has-binary-0.1.5.tgz
npm http fetch 200 https://registry.npmjs.org/utf8/-/utf8-2.0.0.tgz
npm http request GET https://registry.npmjs.org/bufferutil
npm http request GET https://registry.npmjs.org/utf-8-validate
npm http request GET https://registry.npmjs.org/options
npm http request GET https://registry.npmjs.org/ultron
npm http 200 https://registry.npmjs.org/bufferutil
npm http 304 https://registry.npmjs.org/options
npm http 200 https://registry.npmjs.org/ultron
npm http 200 https://registry.npmjs.org/utf-8-validate
npm http fetch GET https://registry.npmjs.org/bufferutil/-/bufferutil-1.1.0.tgz
npm http fetch GET https://registry.npmjs.org/utf-8-validate/-/utf-8-validate-1.1.0.tgz
npm http fetch 200 https://registry.npmjs.org/bufferutil/-/bufferutil-1.1.0.tgz
npm http fetch 200 https://registry.npmjs.org/utf-8-validate/-/utf-8-validate-1.1.0.tgz
npm http request GET https://registry.npmjs.org/bindings
npm http request GET https://registry.npmjs.org/nan
npm http 200 https://registry.npmjs.org/bindings
npm http 200 https://registry.npmjs.org/nan
npm http fetch GET https://registry.npmjs.org/nan/-/nan-1.8.4.tgz
npm http fetch 200 https://registry.npmjs.org/nan/-/nan-1.8.4.tgz
npm http fetch GET https://registry.npmjs.org/debug/-/debug-1.0.2.tgz
npm http fetch GET https://registry.npmjs.org/object-keys/-/object-keys-1.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/debug/-/debug-1.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/object-keys/-/object-keys-1.0.1.tgz
npm http request GET https://registry.npmjs.org/component-emitter
npm http request GET https://registry.npmjs.org/benchmark
npm http request GET https://registry.npmjs.org/json3
npm http 200 https://registry.npmjs.org/component-emitter
npm http 304 https://registry.npmjs.org/json3
npm http 200 https://registry.npmjs.org/benchmark
npm http request GET https://registry.npmjs.org/component-bind
npm http request GET https://registry.npmjs.org/indexof
npm http request GET https://registry.npmjs.org/object-component
npm http request GET https://registry.npmjs.org/to-array
npm http request GET https://registry.npmjs.org/backo2
npm http request GET https://registry.npmjs.org/parseuri
npm http request GET https://registry.npmjs.org/engine.io-client
npm http 304 https://registry.npmjs.org/component-bind
npm http 304 https://registry.npmjs.org/indexof
npm http 304 https://registry.npmjs.org/object-component
npm http 304 https://registry.npmjs.org/to-array
npm http 304 https://registry.npmjs.org/backo2
npm http fetch GET https://registry.npmjs.org/to-array/-/to-array-0.1.3.tgz
npm http 304 https://registry.npmjs.org/parseuri
npm http fetch GET https://registry.npmjs.org/parseuri/-/parseuri-0.0.2.tgz
npm http 200 https://registry.npmjs.org/engine.io-client
npm http fetch GET https://registry.npmjs.org/engine.io-client/-/engine.io-client-1.5.2.tgz
npm http fetch 200 https://registry.npmjs.org/to-array/-/to-array-0.1.3.tgz
npm http fetch 200 https://registry.npmjs.org/parseuri/-/parseuri-0.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/engine.io-client/-/engine.io-client-1.5.2.tgz
npm http request GET https://registry.npmjs.org/component-inherit
npm http request GET https://registry.npmjs.org/has-cors
npm http request GET https://registry.npmjs.org/parsejson
npm http request GET https://registry.npmjs.org/parseqs
npm http fetch GET https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http 304 https://registry.npmjs.org/component-inherit
npm http 304 https://registry.npmjs.org/has-cors
npm http 304 https://registry.npmjs.org/parseqs
npm http fetch GET https://registry.npmjs.org/has-cors/-/has-cors-1.0.3.tgz
npm http 304 https://registry.npmjs.org/parsejson
npm http fetch 200 https://registry.npmjs.org/has-cors/-/has-cors-1.0.3.tgz
npm http fetch 200 https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http fetch GET https://github.com/component/global/archive/v2.0.1.tar.gz
npm http fetch 200 https://github.com/component/global/archive/v2.0.1.tar.gz
npm http request GET https://registry.npmjs.org/better-assert
npm http 200 https://registry.npmjs.org/better-assert
npm http request GET https://registry.npmjs.org/callsite
npm http 304 https://registry.npmjs.org/callsite
npm http request GET https://registry.npmjs.org/stack-trace
npm http request GET https://registry.npmjs.org/pkginfo
npm http request GET https://registry.npmjs.org/isstream
npm http request GET https://registry.npmjs.org/eyes
npm http request GET https://registry.npmjs.org/cycle
npm http request GET https://registry.npmjs.org/colors
npm http request GET https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/stack-trace
npm http 304 https://registry.npmjs.org/cycle
npm http 200 https://registry.npmjs.org/isstream
npm http 200 https://registry.npmjs.org/eyes
npm http 200 https://registry.npmjs.org/colors
npm http 200 https://registry.npmjs.org/async
npm http 200 https://registry.npmjs.org/pkginfo
npm http request GET https://registry.npmjs.org/node-uuid
npm http request GET https://registry.npmjs.org/tape
npm http 200 https://registry.npmjs.org/node-uuid
npm http 200 https://registry.npmjs.org/tape
npm http request GET https://registry.npmjs.org/defined
npm http request GET https://registry.npmjs.org/jsonify
npm http request GET https://registry.npmjs.org/deep-equal
npm http 304 https://registry.npmjs.org/defined
npm http 200 https://registry.npmjs.org/deep-equal
npm http 304 https://registry.npmjs.org/jsonify
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
npm http request GET https://registry.npmjs.org/salti
npm http request GET https://registry.npmjs.org/express
npm http request GET https://registry.npmjs.org/body-parser
npm http request GET https://registry.npmjs.org/forever-agent
npm http request GET https://registry.npmjs.org/express-pouchdb
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/javascript-state-machine
npm http request GET https://registry.npmjs.org/ip
npm http request GET https://registry.npmjs.org/node-uuid
npm http request GET https://registry.npmjs.org/long
npm http request GET https://registry.npmjs.org/multiplex
npm http request GET https://registry.npmjs.org/winston
npm http request GET https://registry.npmjs.org/request
npm http request GET https://registry.npmjs.org/urlsafe-base64
npm http 304 https://registry.npmjs.org/express
npm http 304 https://registry.npmjs.org/forever-agent
npm http 200 https://registry.npmjs.org/body-parser
npm http 200 https://registry.npmjs.org/ip
npm http 304 https://registry.npmjs.org/node-uuid
npm http 200 https://registry.npmjs.org/salti
npm http fetch GET https://registry.npmjs.org/ip/-/ip-1.0.1.tgz
npm http 200 https://registry.npmjs.org/long
npm http fetch GET https://registry.npmjs.org/body-parser/-/body-parser-1.13.3.tgz
npm http fetch GET https://registry.npmjs.org/salti/-/salti-0.2.0.tgz
npm http 200 https://registry.npmjs.org/winston
npm http 200 https://registry.npmjs.org/request
npm http fetch GET https://registry.npmjs.org/request/-/request-2.64.0.tgz
npm http 200 https://registry.npmjs.org/express-pouchdb
npm http fetch GET https://registry.npmjs.org/express-pouchdb/-/express-pouchdb-1.0.4.tgz
npm http 304 https://registry.npmjs.org/lie
npm http fetch 200 https://registry.npmjs.org/body-parser/-/body-parser-1.13.3.tgz
npm http fetch 200 https://registry.npmjs.org/ip/-/ip-1.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/request/-/request-2.64.0.tgz
npm http fetch 200 https://registry.npmjs.org/salti/-/salti-0.2.0.tgz
npm http fetch 200 https://registry.npmjs.org/express-pouchdb/-/express-pouchdb-1.0.4.tgz
npm http 200 https://registry.npmjs.org/javascript-state-machine
npm http 304 https://registry.npmjs.org/multiplex
npm http 304 https://registry.npmjs.org/urlsafe-base64
npm http request GET https://registry.npmjs.org/content-type
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/depd
npm http request GET https://registry.npmjs.org/iconv-lite
npm http request GET https://registry.npmjs.org/bytes
npm http request GET https://registry.npmjs.org/http-errors
npm http request GET https://registry.npmjs.org/on-finished
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/type-is
npm http request GET https://registry.npmjs.org/raw-body
npm http 304 https://registry.npmjs.org/content-type
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/depd
npm http 200 https://registry.npmjs.org/bytes
npm http 200 https://registry.npmjs.org/iconv-lite
npm http 304 https://registry.npmjs.org/on-finished
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/type-is
npm http 200 https://registry.npmjs.org/http-errors
npm http 200 https://registry.npmjs.org/raw-body
npm http fetch GET https://registry.npmjs.org/bytes/-/bytes-2.1.0.tgz
npm http fetch GET https://registry.npmjs.org/iconv-lite/-/iconv-lite-0.4.11.tgz
npm http fetch GET https://registry.npmjs.org/raw-body/-/raw-body-2.1.7.tgz
npm http fetch 200 https://registry.npmjs.org/bytes/-/bytes-2.1.0.tgz
npm http fetch 200 https://registry.npmjs.org/iconv-lite/-/iconv-lite-0.4.11.tgz
npm http fetch 200 https://registry.npmjs.org/raw-body/-/raw-body-2.1.7.tgz
npm http request GET https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/inherits
npm http request GET https://registry.npmjs.org/statuses
npm http 304 https://registry.npmjs.org/statuses
npm http 304 https://registry.npmjs.org/inherits
npm http fetch GET https://registry.npmjs.org/statuses/-/statuses-1.3.0.tgz
npm http fetch 200 https://registry.npmjs.org/statuses/-/statuses-1.3.0.tgz
npm http request GET https://registry.npmjs.org/ee-first
npm http 304 https://registry.npmjs.org/ee-first
npm http request GET https://registry.npmjs.org/unpipe
npm http fetch GET https://registry.npmjs.org/bytes/-/bytes-2.4.0.tgz
npm http 304 https://registry.npmjs.org/unpipe
npm http fetch 200 https://registry.npmjs.org/bytes/-/bytes-2.4.0.tgz
npm http request GET https://registry.npmjs.org/media-typer
npm http request GET https://registry.npmjs.org/mime-types
npm http 304 https://registry.npmjs.org/media-typer
npm http 304 https://registry.npmjs.org/mime-types
npm http request GET https://registry.npmjs.org/mime-db
npm http 304 https://registry.npmjs.org/mime-db
npm http request GET https://registry.npmjs.org/accepts
npm http request GET https://registry.npmjs.org/array-flatten
npm http request GET https://registry.npmjs.org/content-disposition
npm http request GET https://registry.npmjs.org/cookie
npm http request GET https://registry.npmjs.org/cookie-signature
npm http request GET https://registry.npmjs.org/escape-html
npm http request GET https://registry.npmjs.org/etag
npm http request GET https://registry.npmjs.org/finalhandler
npm http request GET https://registry.npmjs.org/fresh
npm http request GET https://registry.npmjs.org/merge-descriptors
npm http request GET https://registry.npmjs.org/methods
npm http request GET https://registry.npmjs.org/parseurl
npm http request GET https://registry.npmjs.org/path-to-regexp
npm http request GET https://registry.npmjs.org/proxy-addr
npm http request GET https://registry.npmjs.org/range-parser
npm http request GET https://registry.npmjs.org/send
npm http request GET https://registry.npmjs.org/serve-static
npm http request GET https://registry.npmjs.org/utils-merge
npm http request GET https://registry.npmjs.org/vary
npm http 304 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/content-disposition
npm http 304 https://registry.npmjs.org/cookie
npm http 304 https://registry.npmjs.org/cookie-signature
npm http 304 https://registry.npmjs.org/array-flatten
npm http 304 https://registry.npmjs.org/etag
npm http 200 https://registry.npmjs.org/escape-html
npm http 304 https://registry.npmjs.org/finalhandler
npm http 304 https://registry.npmjs.org/fresh
npm http 304 https://registry.npmjs.org/merge-descriptors
npm http 304 https://registry.npmjs.org/methods
npm http 304 https://registry.npmjs.org/parseurl
npm http 304 https://registry.npmjs.org/path-to-regexp
npm http 304 https://registry.npmjs.org/proxy-addr
npm http 304 https://registry.npmjs.org/range-parser
npm http 304 https://registry.npmjs.org/send
npm http 304 https://registry.npmjs.org/serve-static
npm http 304 https://registry.npmjs.org/utils-merge
npm http 304 https://registry.npmjs.org/vary
npm http request GET https://registry.npmjs.org/negotiator
npm http 304 https://registry.npmjs.org/negotiator
npm http request GET https://registry.npmjs.org/forwarded
npm http request GET https://registry.npmjs.org/ipaddr.js
npm http 304 https://registry.npmjs.org/forwarded
npm http 304 https://registry.npmjs.org/ipaddr.js
npm http request GET https://registry.npmjs.org/destroy
npm http request GET https://registry.npmjs.org/mime
npm http 304 https://registry.npmjs.org/destroy
npm http 304 https://registry.npmjs.org/mime
npm http request GET https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/basic-auth
npm http request GET https://registry.npmjs.org/compression
npm http request GET https://registry.npmjs.org/cookie-parser
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/pouchdb-auth
npm http request GET https://registry.npmjs.org/pouchdb-all-dbs
npm http request GET https://registry.npmjs.org/multiparty
npm http request GET https://registry.npmjs.org/header-case-normalizer
npm http request GET https://registry.npmjs.org/pouchdb-find
npm http request GET https://registry.npmjs.org/pouchdb-list
npm http request GET https://registry.npmjs.org/pouchdb-replicator
npm http request GET https://registry.npmjs.org/pouchdb-rewrite
npm http request GET https://registry.npmjs.org/pouchdb-show
npm http request GET https://registry.npmjs.org/pouchdb-security
npm http request GET https://registry.npmjs.org/pouchdb-size
npm http request GET https://registry.npmjs.org/pouchdb-update
npm http request GET https://registry.npmjs.org/pouchdb-vhost
npm http request GET https://registry.npmjs.org/pouchdb-validation
npm http request GET https://registry.npmjs.org/pouchdb-wrappers
npm http 304 https://registry.npmjs.org/bluebird
npm http 200 https://registry.npmjs.org/basic-auth
npm http 200 https://registry.npmjs.org/extend
npm http 200 https://registry.npmjs.org/cookie-parser
npm http 200 https://registry.npmjs.org/compression
npm http fetch GET https://registry.npmjs.org/bluebird/-/bluebird-3.3.4.tgz
npm http 200 https://registry.npmjs.org/multiparty
npm http 304 https://registry.npmjs.org/header-case-normalizer
npm http 304 https://registry.npmjs.org/pouchdb-list
npm http 304 https://registry.npmjs.org/pouchdb-rewrite
npm http 200 https://registry.npmjs.org/pouchdb-find
npm http 200 https://registry.npmjs.org/pouchdb-auth
npm http 200 https://registry.npmjs.org/pouchdb-all-dbs
npm http fetch GET https://registry.npmjs.org/pouchdb-auth/-/pouchdb-auth-2.1.0.tgz
npm http 304 https://registry.npmjs.org/pouchdb-replicator
npm http 304 https://registry.npmjs.org/pouchdb-size
npm http 304 https://registry.npmjs.org/pouchdb-validation
npm http 304 https://registry.npmjs.org/pouchdb-security
npm http 304 https://registry.npmjs.org/pouchdb-show
npm http fetch 200 https://registry.npmjs.org/bluebird/-/bluebird-3.3.4.tgz
npm http 304 https://registry.npmjs.org/pouchdb-update
npm http fetch 200 https://registry.npmjs.org/pouchdb-auth/-/pouchdb-auth-2.1.0.tgz
npm http 304 https://registry.npmjs.org/pouchdb-wrappers
npm http 304 https://registry.npmjs.org/pouchdb-vhost
npm http request GET https://registry.npmjs.org/compressible
npm http request GET https://registry.npmjs.org/on-headers
npm http fetch GET https://registry.npmjs.org/accepts/-/accepts-1.3.3.tgz
npm http fetch 200 https://registry.npmjs.org/accepts/-/accepts-1.3.3.tgz
npm http 200 https://registry.npmjs.org/compressible
npm http 200 https://registry.npmjs.org/on-headers
npm http fetch GET https://registry.npmjs.org/compressible/-/compressible-2.0.8.tgz
npm http fetch 200 https://registry.npmjs.org/compressible/-/compressible-2.0.8.tgz
npm http fetch GET https://registry.npmjs.org/negotiator/-/negotiator-0.6.1.tgz
npm http fetch 200 https://registry.npmjs.org/negotiator/-/negotiator-0.6.1.tgz
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/stream-counter
npm http 200 https://registry.npmjs.org/readable-stream
npm http fetch GET https://registry.npmjs.org/readable-stream/-/readable-stream-1.1.14.tgz
npm http fetch 200 https://registry.npmjs.org/readable-stream/-/readable-stream-1.1.14.tgz
npm http 304 https://registry.npmjs.org/stream-counter
npm http request GET https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/argsarray
npm http request GET https://registry.npmjs.org/tiny-queue
npm http 304 https://registry.npmjs.org/argsarray
npm http 304 https://registry.npmjs.org/tiny-queue
npm http 304 https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/jstransform
npm http request GET https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 304 https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/jstransform
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/source-map
npm http 200 https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/amdefine
npm http 304 https://registry.npmjs.org/amdefine
npm http request GET https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/immediate
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/acorn
npm http request GET https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/foreach
npm http 304 https://registry.npmjs.org/acorn
npm http 304 https://registry.npmjs.org/object-keys
npm http request GET https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/xtend
npm http request GET https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/ast-types
npm http 304 https://registry.npmjs.org/ast-types
npm http 304 https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/base64url
npm http request GET https://registry.npmjs.org/couchdb-calculate-session-id
npm http request GET https://registry.npmjs.org/crypto-lite
npm http request GET https://registry.npmjs.org/pouchdb-promise
npm http request GET https://registry.npmjs.org/pouchdb-bulkdocs-wrapper
npm http request GET https://registry.npmjs.org/pouchdb-plugin-error
npm http request GET https://registry.npmjs.org/pouchdb
npm http request GET https://registry.npmjs.org/pouchdb-req-http-query
npm http request GET https://registry.npmjs.org/pouchdb-system-db
npm http request GET https://registry.npmjs.org/promise-nodify
npm http request GET https://registry.npmjs.org/secure-random
npm http 304 https://registry.npmjs.org/base64url
npm http 304 https://registry.npmjs.org/pouchdb-bulkdocs-wrapper
npm http 200 https://registry.npmjs.org/pouchdb-promise
npm http fetch GET https://registry.npmjs.org/pouchdb-promise/-/pouchdb-promise-5.4.4.tgz
npm http 304 https://registry.npmjs.org/pouchdb-plugin-error
npm http 200 https://registry.npmjs.org/pouchdb
npm http fetch GET https://registry.npmjs.org/pouchdb/-/pouchdb-5.4.4.tgz
npm http 304 https://registry.npmjs.org/couchdb-calculate-session-id
npm http 304 https://registry.npmjs.org/crypto-lite
npm http fetch 200 https://registry.npmjs.org/pouchdb-promise/-/pouchdb-promise-5.4.4.tgz
npm http 304 https://registry.npmjs.org/pouchdb-req-http-query
npm http fetch 200 https://registry.npmjs.org/pouchdb/-/pouchdb-5.4.4.tgz
npm http 304 https://registry.npmjs.org/pouchdb-system-db
npm http 304 https://registry.npmjs.org/promise-nodify
npm http 304 https://registry.npmjs.org/secure-random
npm http request GET https://registry.npmjs.org/concat-stream
npm http request GET https://registry.npmjs.org/meow
npm http 200 https://registry.npmjs.org/concat-stream
npm http 200 https://registry.npmjs.org/meow
npm http request GET https://registry.npmjs.org/typedarray
npm http 304 https://registry.npmjs.org/typedarray
npm http request GET https://registry.npmjs.org/minimist
npm http request GET https://registry.npmjs.org/object-assign
npm http request GET https://registry.npmjs.org/camelcase-keys
npm http request GET https://registry.npmjs.org/indent-string
npm http 304 https://registry.npmjs.org/minimist
npm http 200 https://registry.npmjs.org/camelcase-keys
npm http 200 https://registry.npmjs.org/indent-string
npm http 304 https://registry.npmjs.org/object-assign
npm http request GET https://registry.npmjs.org/map-obj
npm http request GET https://registry.npmjs.org/camelcase
npm http 200 https://registry.npmjs.org/map-obj
npm http 200 https://registry.npmjs.org/camelcase
npm http request GET https://registry.npmjs.org/get-stdin
npm http request GET https://registry.npmjs.org/repeating
npm http 200 https://registry.npmjs.org/repeating
npm http 200 https://registry.npmjs.org/get-stdin
npm http request GET https://registry.npmjs.org/is-finite
npm http 304 https://registry.npmjs.org/is-finite
npm http request GET https://registry.npmjs.org/number-is-nan
npm http 304 https://registry.npmjs.org/number-is-nan
npm http request GET https://registry.npmjs.org/aproba
npm http 200 https://registry.npmjs.org/aproba
npm http fetch GET https://registry.npmjs.org/aproba/-/aproba-1.0.4.tgz
npm http fetch 200 https://registry.npmjs.org/aproba/-/aproba-1.0.4.tgz
npm http request GET https://registry.npmjs.org/double-ended-queue
npm http request GET https://registry.npmjs.org/fruitdown
npm http request GET https://registry.npmjs.org/js-extend
npm http request GET https://registry.npmjs.org/level-write-stream
npm http request GET https://registry.npmjs.org/pouchdb-collections
npm http request GET https://registry.npmjs.org/levelup
npm http request GET https://registry.npmjs.org/pouchdb-collate
npm http request GET https://registry.npmjs.org/request
npm http request GET https://registry.npmjs.org/sublevel-pouchdb
npm http request GET https://registry.npmjs.org/vuvuzela
npm http request GET https://registry.npmjs.org/spark-md5
npm http request GET https://registry.npmjs.org/scope-eval
npm http request GET https://registry.npmjs.org/memdown
npm http request GET https://registry.npmjs.org/localstorage-down
npm http 304 https://registry.npmjs.org/double-ended-queue
npm http 304 https://registry.npmjs.org/level-write-stream
npm http 304 https://registry.npmjs.org/pouchdb-collections
npm http 304 https://registry.npmjs.org/request
npm http fetch GET https://registry.npmjs.org/request/-/request-2.72.0.tgz
npm http 304 https://registry.npmjs.org/pouchdb-collate
npm http 200 https://registry.npmjs.org/sublevel-pouchdb
npm http fetch GET https://registry.npmjs.org/sublevel-pouchdb/-/sublevel-pouchdb-1.0.1.tgz
npm http 304 https://registry.npmjs.org/js-extend
npm http 304 https://registry.npmjs.org/fruitdown
npm http fetch GET https://registry.npmjs.org/js-extend/-/js-extend-0.0.1.tgz
npm http 200 https://registry.npmjs.org/spark-md5
npm http 200 https://registry.npmjs.org/levelup
npm http fetch GET https://registry.npmjs.org/levelup/-/levelup-1.3.2.tgz
npm http fetch 200 https://registry.npmjs.org/request/-/request-2.72.0.tgz
npm http 304 https://registry.npmjs.org/scope-eval
npm http 200 https://registry.npmjs.org/memdown
npm http fetch 200 https://registry.npmjs.org/sublevel-pouchdb/-/sublevel-pouchdb-1.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/js-extend/-/js-extend-0.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/levelup/-/levelup-1.3.2.tgz
npm http 200 https://registry.npmjs.org/vuvuzela
npm http fetch GET https://registry.npmjs.org/vuvuzela/-/vuvuzela-1.0.3.tgz
npm http 304 https://registry.npmjs.org/localstorage-down
npm http fetch 200 https://registry.npmjs.org/vuvuzela/-/vuvuzela-1.0.3.tgz
npm http request GET https://registry.npmjs.org/tiny-queue
npm http request GET https://registry.npmjs.org/d64
npm http request GET https://registry.npmjs.org/abstract-leveldown
npm http 304 https://registry.npmjs.org/tiny-queue
npm http 304 https://registry.npmjs.org/abstract-leveldown
npm http 304 https://registry.npmjs.org/d64
npm http request GET https://registry.npmjs.org/end-stream
npm http 304 https://registry.npmjs.org/end-stream
npm http request GET https://registry.npmjs.org/write-stream
npm http 304 https://registry.npmjs.org/write-stream
npm http request GET https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/deferred-leveldown
npm http request GET https://registry.npmjs.org/level-errors
npm http request GET https://registry.npmjs.org/level-codec
npm http request GET https://registry.npmjs.org/level-iterator-stream
npm http request GET https://registry.npmjs.org/prr
npm http request GET https://registry.npmjs.org/semver
npm http 304 https://registry.npmjs.org/prr
npm http 200 https://registry.npmjs.org/semver
npm http fetch GET https://registry.npmjs.org/semver/-/semver-5.1.1.tgz
npm http 304 https://registry.npmjs.org/deferred-leveldown
npm http 304 https://registry.npmjs.org/level-errors
npm http 304 https://registry.npmjs.org/level-codec
npm http fetch 200 https://registry.npmjs.org/semver/-/semver-5.1.1.tgz
npm http 304 https://registry.npmjs.org/level-iterator-stream
npm http request GET https://registry.npmjs.org/errno
npm http 304 https://registry.npmjs.org/errno
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/esprima
npm http request GET https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/esprima
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/commoner
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/base62
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 304 https://registry.npmjs.org/commoner
npm http request GET https://registry.npmjs.org/detective
npm http request GET https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/mkdirp
npm http request GET https://registry.npmjs.org/q
npm http 304 https://registry.npmjs.org/detective
npm http 304 https://registry.npmjs.org/commander
npm http 200 https://registry.npmjs.org/mkdirp
npm http 304 https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/graceful-fs
npm http 304 https://registry.npmjs.org/q
npm http request GET https://registry.npmjs.org/graceful-readlink
npm http 304 https://registry.npmjs.org/graceful-readlink
npm http request GET https://registry.npmjs.org/defined
npm http 304 https://registry.npmjs.org/defined
npm http request GET https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/path-is-absolute
npm http request GET https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/inflight
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http 304 https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/wrappy
npm http 304 https://registry.npmjs.org/wrappy
npm http request GET https://registry.npmjs.org/brace-expansion
npm http 304 https://registry.npmjs.org/brace-expansion
npm http request GET https://registry.npmjs.org/balanced-match
npm http request GET https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/balanced-match
npm http 304 https://registry.npmjs.org/concat-map
npm http request GET https://registry.npmjs.org/minimist
npm http 304 https://registry.npmjs.org/minimist
npm http request GET https://registry.npmjs.org/humble-localstorage
npm http 200 https://registry.npmjs.org/humble-localstorage
npm http request GET https://registry.npmjs.org/has-localstorage
npm http request GET https://registry.npmjs.org/localstorage-memory
npm http 304 https://registry.npmjs.org/localstorage-memory
npm http 304 https://registry.npmjs.org/has-localstorage
npm http request GET https://registry.npmjs.org/ltgt
npm http request GET https://registry.npmjs.org/functional-red-black-tree
npm http 304 https://registry.npmjs.org/ltgt
npm http 304 https://registry.npmjs.org/functional-red-black-tree
npm http request GET https://registry.npmjs.org/combined-stream
npm http request GET https://registry.npmjs.org/caseless
npm http request GET https://registry.npmjs.org/aws4
npm http request GET https://registry.npmjs.org/bl
npm http request GET https://registry.npmjs.org/aws-sign2
npm http request GET https://registry.npmjs.org/form-data
npm http request GET https://registry.npmjs.org/har-validator
npm http request GET https://registry.npmjs.org/isstream
npm http request GET https://registry.npmjs.org/oauth-sign
npm http request GET https://registry.npmjs.org/json-stringify-safe
npm http request GET https://registry.npmjs.org/is-typedarray
npm http request GET https://registry.npmjs.org/http-signature
npm http request GET https://registry.npmjs.org/hawk
npm http request GET https://registry.npmjs.org/stringstream
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/tunnel-agent
npm http request GET https://registry.npmjs.org/tough-cookie
npm http 304 https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/aws-sign2
npm http 200 https://registry.npmjs.org/aws4
npm http 304 https://registry.npmjs.org/caseless
npm http 200 https://registry.npmjs.org/bl
npm http fetch GET https://registry.npmjs.org/aws4/-/aws4-1.4.1.tgz
npm http 200 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/isstream
npm http fetch GET https://registry.npmjs.org/bl/-/bl-1.1.2.tgz
npm http 200 https://registry.npmjs.org/oauth-sign
npm http 200 https://registry.npmjs.org/har-validator
npm http 200 https://registry.npmjs.org/json-stringify-safe
npm http 304 https://registry.npmjs.org/is-typedarray
npm http 304 https://registry.npmjs.org/stringstream
npm http fetch GET https://registry.npmjs.org/oauth-sign/-/oauth-sign-0.8.2.tgz
npm http 200 https://registry.npmjs.org/http-signature
npm http 200 https://registry.npmjs.org/extend
npm http 200 https://registry.npmjs.org/hawk
npm http 304 https://registry.npmjs.org/qs
npm http fetch 200 https://registry.npmjs.org/bl/-/bl-1.1.2.tgz
npm http fetch 200 https://registry.npmjs.org/aws4/-/aws4-1.4.1.tgz
npm http 200 https://registry.npmjs.org/tunnel-agent
npm http 200 https://registry.npmjs.org/tough-cookie
npm http fetch 200 https://registry.npmjs.org/oauth-sign/-/oauth-sign-0.8.2.tgz
npm http fetch GET https://registry.npmjs.org/tunnel-agent/-/tunnel-agent-0.4.3.tgz
npm http fetch 200 https://registry.npmjs.org/tunnel-agent/-/tunnel-agent-0.4.3.tgz
npm http request GET https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/process-nextick-args
npm http request GET https://registry.npmjs.org/util-deprecate
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/util-deprecate
npm http 200 https://registry.npmjs.org/process-nextick-args
npm http fetch GET https://registry.npmjs.org/process-nextick-args/-/process-nextick-args-1.0.7.tgz
npm http fetch 200 https://registry.npmjs.org/process-nextick-args/-/process-nextick-args-1.0.7.tgz
npm http request GET https://registry.npmjs.org/delayed-stream
npm http 304 https://registry.npmjs.org/delayed-stream
npm http request GET https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/chalk
npm http request GET https://registry.npmjs.org/is-my-json-valid
npm http request GET https://registry.npmjs.org/pinkie-promise
npm http 200 https://registry.npmjs.org/chalk
npm http 200 https://registry.npmjs.org/is-my-json-valid
npm http fetch GET https://registry.npmjs.org/chalk/-/chalk-1.1.3.tgz
npm http fetch 200 https://registry.npmjs.org/chalk/-/chalk-1.1.3.tgz
npm http 200 https://registry.npmjs.org/pinkie-promise
npm http fetch GET https://registry.npmjs.org/pinkie-promise/-/pinkie-promise-2.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/pinkie-promise/-/pinkie-promise-2.0.1.tgz
npm http request GET https://registry.npmjs.org/has-ansi
npm http request GET https://registry.npmjs.org/escape-string-regexp
npm http request GET https://registry.npmjs.org/ansi-styles
npm http request GET https://registry.npmjs.org/strip-ansi
npm http request GET https://registry.npmjs.org/supports-color
npm http 200 https://registry.npmjs.org/has-ansi
npm http 200 https://registry.npmjs.org/ansi-styles
npm http 200 https://registry.npmjs.org/strip-ansi
npm http 200 https://registry.npmjs.org/supports-color
npm http fetch GET https://registry.npmjs.org/ansi-styles/-/ansi-styles-2.2.1.tgz
npm http fetch 200 https://registry.npmjs.org/ansi-styles/-/ansi-styles-2.2.1.tgz
npm http 200 https://registry.npmjs.org/escape-string-regexp
npm http request GET https://registry.npmjs.org/ansi-regex
npm http 200 https://registry.npmjs.org/ansi-regex
npm http request GET https://registry.npmjs.org/generate-object-property
npm http request GET https://registry.npmjs.org/generate-function
npm http request GET https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/generate-object-property
npm http 304 https://registry.npmjs.org/generate-function
npm http 200 https://registry.npmjs.org/jsonpointer
npm http request GET https://registry.npmjs.org/is-property
npm http 304 https://registry.npmjs.org/is-property
npm http request GET https://registry.npmjs.org/pinkie
npm http 304 https://registry.npmjs.org/pinkie
npm http request GET https://registry.npmjs.org/hoek
npm http request GET https://registry.npmjs.org/boom
npm http request GET https://registry.npmjs.org/sntp
npm http request GET https://registry.npmjs.org/cryptiles
npm http 304 https://registry.npmjs.org/sntp
npm http 200 https://registry.npmjs.org/cryptiles
npm http 200 https://registry.npmjs.org/boom
npm http 200 https://registry.npmjs.org/hoek
npm http request GET https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/jsprim
npm http request GET https://registry.npmjs.org/sshpk
npm http 200 https://registry.npmjs.org/assert-plus
npm http 200 https://registry.npmjs.org/jsprim
npm http fetch GET https://registry.npmjs.org/jsprim/-/jsprim-1.3.0.tgz
npm http 200 https://registry.npmjs.org/sshpk
npm http fetch GET https://registry.npmjs.org/sshpk/-/sshpk-1.8.3.tgz
npm http fetch 200 https://registry.npmjs.org/jsprim/-/jsprim-1.3.0.tgz
npm http fetch 200 https://registry.npmjs.org/sshpk/-/sshpk-1.8.3.tgz
npm http request GET https://registry.npmjs.org/extsprintf
npm http request GET https://registry.npmjs.org/json-schema
npm http request GET https://registry.npmjs.org/verror
npm http 304 https://registry.npmjs.org/extsprintf
npm http 200 https://registry.npmjs.org/json-schema
npm http 200 https://registry.npmjs.org/verror
npm http request GET https://registry.npmjs.org/getpass
npm http request GET https://registry.npmjs.org/dashdash
npm http request GET https://registry.npmjs.org/asn1
npm http 200 https://registry.npmjs.org/getpass
npm http 200 https://registry.npmjs.org/asn1
npm http 200 https://registry.npmjs.org/dashdash
npm http fetch GET https://registry.npmjs.org/getpass/-/getpass-0.1.6.tgz
npm http fetch GET https://registry.npmjs.org/dashdash/-/dashdash-1.14.0.tgz
npm http fetch 200 https://registry.npmjs.org/getpass/-/getpass-0.1.6.tgz
npm http fetch 200 https://registry.npmjs.org/dashdash/-/dashdash-1.14.0.tgz
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/pull-stream
npm http 304 https://registry.npmjs.org/readable-stream
npm http 200 https://registry.npmjs.org/pull-stream
npm http request GET https://registry.npmjs.org/pull-core
npm http 304 https://registry.npmjs.org/pull-core
npm http request GET https://registry.npmjs.org/pouchdb-promise
npm http 304 https://registry.npmjs.org/pouchdb-promise
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/xmlhttprequest-cookie
npm http 304 https://registry.npmjs.org/xmlhttprequest-cookie
npm http request GET https://registry.npmjs.org/xmlhttprequest
npm http 304 https://registry.npmjs.org/xmlhttprequest
npm http request GET https://registry.npmjs.org/pouchdb-changeslike-wrapper
npm http 304 https://registry.npmjs.org/pouchdb-changeslike-wrapper
npm http request GET https://registry.npmjs.org/couchdb-objects
npm http request GET https://registry.npmjs.org/couchdb-eval
npm http request GET https://registry.npmjs.org/random-uuid-v4
npm http 304 https://registry.npmjs.org/couchdb-eval
npm http 200 https://registry.npmjs.org/random-uuid-v4
npm http 304 https://registry.npmjs.org/couchdb-objects
npm http request GET https://registry.npmjs.org/is-empty
npm http 304 https://registry.npmjs.org/is-empty
npm http request GET https://registry.npmjs.org/spark-md5
npm http request GET https://registry.npmjs.org/pouchdb-abstract-mapreduce
npm http request GET https://registry.npmjs.org/jshint
npm http request GET https://registry.npmjs.org/pouchdb-extend
npm http request GET https://registry.npmjs.org/pouchdb-upsert
npm http 304 https://registry.npmjs.org/spark-md5
npm http 200 https://registry.npmjs.org/jshint
npm http fetch GET https://registry.npmjs.org/jshint/-/jshint-2.9.2.tgz
npm http 304 https://registry.npmjs.org/pouchdb-extend
npm http 200 https://registry.npmjs.org/pouchdb-upsert
npm http fetch 200 https://registry.npmjs.org/jshint/-/jshint-2.9.2.tgz
npm http 304 https://registry.npmjs.org/pouchdb-abstract-mapreduce
npm http request GET https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/console-browserify
npm http request GET https://registry.npmjs.org/exit
npm http request GET https://registry.npmjs.org/cli
npm http request GET https://registry.npmjs.org/htmlparser2
npm http request GET https://registry.npmjs.org/shelljs
npm http request GET https://registry.npmjs.org/strip-json-comments
npm http request GET https://registry.npmjs.org/lodash
npm http 304 https://registry.npmjs.org/minimatch
npm WARN deprecated minimatch@2.0.10: Please update to minimatch 3.0.2 or higher to avoid a RegExp DoS issue
npm http 200 https://registry.npmjs.org/exit
npm http 200 https://registry.npmjs.org/console-browserify
npm http 200 https://registry.npmjs.org/htmlparser2
npm http 200 https://registry.npmjs.org/cli
npm http 200 https://registry.npmjs.org/strip-json-comments
npm http 200 https://registry.npmjs.org/shelljs
npm http 200 https://registry.npmjs.org/lodash
npm http request GET https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/glob
npm WARN deprecated minimatch@0.3.0: Please update to minimatch 3.0.2 or higher to avoid a RegExp DoS issue
npm http request GET https://registry.npmjs.org/sigmund
npm http request GET https://registry.npmjs.org/lru-cache
npm http 304 https://registry.npmjs.org/sigmund
npm http 200 https://registry.npmjs.org/lru-cache
npm http request GET https://registry.npmjs.org/date-now
npm http 304 https://registry.npmjs.org/date-now
npm http request GET https://registry.npmjs.org/domhandler
npm http request GET https://registry.npmjs.org/domelementtype
npm http request GET https://registry.npmjs.org/domutils
npm http request GET https://registry.npmjs.org/entities
npm http 304 https://registry.npmjs.org/domhandler
npm http 304 https://registry.npmjs.org/domelementtype
npm http 200 https://registry.npmjs.org/entities
npm http 304 https://registry.npmjs.org/domutils
npm http request GET https://registry.npmjs.org/dom-serializer
npm http 304 https://registry.npmjs.org/dom-serializer
npm http request GET https://registry.npmjs.org/bl
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/http-signature
npm http request GET https://registry.npmjs.org/aws-sign2
npm http request GET https://registry.npmjs.org/har-validator
npm http 304 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/http-signature
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/aws-sign2
npm http fetch GET https://registry.npmjs.org/http-signature/-/http-signature-0.11.0.tgz
npm http fetch GET https://registry.npmjs.org/qs/-/qs-5.1.0.tgz
npm http 304 https://registry.npmjs.org/har-validator
npm http fetch GET https://registry.npmjs.org/har-validator/-/har-validator-1.8.0.tgz
npm http fetch 200 https://registry.npmjs.org/har-validator/-/har-validator-1.8.0.tgz
npm http fetch 200 https://registry.npmjs.org/qs/-/qs-5.1.0.tgz
npm http fetch 200 https://registry.npmjs.org/http-signature/-/http-signature-0.11.0.tgz
npm http request GET https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/ctype
npm http 200 https://registry.npmjs.org/assert-plus
npm http 200 https://registry.npmjs.org/ctype
npm http request GET https://registry.npmjs.org/couchdb-render
npm http 304 https://registry.npmjs.org/couchdb-render
npm http request GET https://registry.npmjs.org/couchdb-resp-completer
npm http 304 https://registry.npmjs.org/couchdb-resp-completer
npm http request GET https://registry.npmjs.org/equals
npm http 200 https://registry.npmjs.org/equals
npm http fetch GET https://registry.npmjs.org/equals/-/equals-1.1.0.tgz
npm http fetch 200 https://registry.npmjs.org/equals/-/equals-1.1.0.tgz
npm http request GET https://registry.npmjs.org/@jkroso%2ftype
npm http 200 https://registry.npmjs.org/@jkroso%2ftype
npm http fetch GET https://registry.npmjs.org/@jkroso/type/-/type-1.1.1.tgz
npm http fetch 200 https://registry.npmjs.org/@jkroso/type/-/type-1.1.1.tgz
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/pouchdb-route
npm http 304 https://registry.npmjs.org/pouchdb-route
npm http request GET https://registry.npmjs.org/pouchdb-promise
npm http 304 https://registry.npmjs.org/pouchdb-promise
npm http request GET https://registry.npmjs.org/get-folder-size
npm http 304 https://registry.npmjs.org/get-folder-size
npm http request GET https://registry.npmjs.org/minimist
npm http request GET https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/minimist
npm http 304 https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/duplexify
npm http request GET https://registry.npmjs.org/varint
npm http 200 https://registry.npmjs.org/readable-stream
npm http 200 https://registry.npmjs.org/duplexify
npm http fetch GET https://registry.npmjs.org/readable-stream/-/readable-stream-2.1.4.tgz
npm http fetch 200 https://registry.npmjs.org/readable-stream/-/readable-stream-2.1.4.tgz
npm http 200 https://registry.npmjs.org/varint
npm http fetch GET https://registry.npmjs.org/varint/-/varint-4.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/varint/-/varint-4.0.1.tgz
npm http request GET https://registry.npmjs.org/end-of-stream
npm http 304 https://registry.npmjs.org/end-of-stream
npm http request GET https://registry.npmjs.org/buffer-shims
npm http 200 https://registry.npmjs.org/buffer-shims
npm http fetch GET https://registry.npmjs.org/buffer-shims/-/buffer-shims-1.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/buffer-shims/-/buffer-shims-1.0.0.tgz
npm http request GET https://registry.npmjs.org/colors
npm http request GET https://registry.npmjs.org/cycle
npm http request GET https://registry.npmjs.org/eyes
npm http request GET https://registry.npmjs.org/pkginfo
npm http request GET https://registry.npmjs.org/stack-trace
npm http 304 https://registry.npmjs.org/cycle
npm http 304 https://registry.npmjs.org/colors
npm http 304 https://registry.npmjs.org/pkginfo
npm http 304 https://registry.npmjs.org/eyes
npm http 304 https://registry.npmjs.org/stack-trace
npm http request GET https://registry.npmjs.org/jsdoc
npm http 200 https://registry.npmjs.org/jsdoc
npm http fetch GET https://registry.npmjs.org/jsdoc/-/jsdoc-3.3.3.tgz
npm http fetch 200 https://registry.npmjs.org/jsdoc/-/jsdoc-3.3.3.tgz
npm http request GET https://registry.npmjs.org/catharsis
npm http request GET https://registry.npmjs.org/js2xmlparser
npm http request GET https://registry.npmjs.org/requizzle
npm http request GET https://registry.npmjs.org/marked
npm http request GET https://registry.npmjs.org/underscore
npm http request GET https://registry.npmjs.org/wrench
npm http request GET https://registry.npmjs.org/esprima
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 304 https://registry.npmjs.org/requizzle
npm http 200 https://registry.npmjs.org/underscore
npm http 200 https://registry.npmjs.org/marked
npm http 304 https://registry.npmjs.org/esprima
npm http 200 https://registry.npmjs.org/wrench
npm http fetch GET https://registry.npmjs.org/esprima/-/esprima-1.2.5.tgz
npm WARN deprecated wrench@1.5.9: wrench.js is deprecated! You should check out fs-extra (https://github.com/jprichardson/node-fs-extra) for any operations you were using wrench for. Thanks for all the usage over the years.
npm http fetch GET https://registry.npmjs.org/wrench/-/wrench-1.5.9.tgz
npm http 200 https://registry.npmjs.org/catharsis
npm http fetch GET https://registry.npmjs.org/catharsis/-/catharsis-0.8.8.tgz
npm http 200 https://registry.npmjs.org/js2xmlparser
npm http fetch GET https://registry.npmjs.org/js2xmlparser/-/js2xmlparser-0.1.9.tgz
npm http fetch 200 https://registry.npmjs.org/esprima/-/esprima-1.2.5.tgz
npm http fetch 200 https://registry.npmjs.org/wrench/-/wrench-1.5.9.tgz
npm http fetch 200 https://registry.npmjs.org/catharsis/-/catharsis-0.8.8.tgz
npm http fetch 200 https://registry.npmjs.org/js2xmlparser/-/js2xmlparser-0.1.9.tgz
npm http fetch 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http request GET https://registry.npmjs.org/underscore-contrib
npm http 304 https://registry.npmjs.org/underscore-contrib
npm WARN prefer global marked@0.3.5 should be installed with -g
npm WARN prefer global jshint@2.9.2 should be installed with -g
npm http request GET https://registry.npmjs.org/leveldown
npm http request GET https://registry.npmjs.org/websql
npm http 200 https://registry.npmjs.org/leveldown
npm http fetch GET https://registry.npmjs.org/leveldown/-/leveldown-1.4.6.tgz
npm http fetch 200 https://registry.npmjs.org/leveldown/-/leveldown-1.4.6.tgz
npm http 200 https://registry.npmjs.org/websql
npm http fetch GET https://registry.npmjs.org/websql/-/websql-0.4.4.tgz
npm http fetch 200 https://registry.npmjs.org/websql/-/websql-0.4.4.tgz
npm http request GET https://registry.npmjs.org/prebuild
npm http request GET https://registry.npmjs.org/bindings
npm http request GET https://registry.npmjs.org/abstract-leveldown
npm http request GET https://registry.npmjs.org/nan
npm http request GET https://registry.npmjs.org/fast-future
npm http 200 https://registry.npmjs.org/bindings
npm http 304 https://registry.npmjs.org/nan
npm http fetch GET https://registry.npmjs.org/nan/-/nan-2.3.5.tgz
npm http 304 https://registry.npmjs.org/fast-future
npm http fetch 200 https://registry.npmjs.org/nan/-/nan-2.3.5.tgz
npm http 200 https://registry.npmjs.org/prebuild
npm http fetch GET https://registry.npmjs.org/prebuild/-/prebuild-4.2.2.tgz
npm http 304 https://registry.npmjs.org/abstract-leveldown
npm http fetch 200 https://registry.npmjs.org/prebuild/-/prebuild-4.2.2.tgz
npm http request GET https://registry.npmjs.org/expand-template
npm http request GET https://registry.npmjs.org/ghreleases
npm http request GET https://registry.npmjs.org/github-from-package
npm http request GET https://registry.npmjs.org/node-gyp
npm http request GET https://registry.npmjs.org/node-ninja
npm http request GET https://registry.npmjs.org/noop-logger
npm http request GET https://registry.npmjs.org/npmlog
npm http request GET https://registry.npmjs.org/pump
npm http request GET https://registry.npmjs.org/simple-get
npm http request GET https://registry.npmjs.org/tar-fs
npm http request GET https://registry.npmjs.org/tar-stream
npm http request GET https://registry.npmjs.org/os-homedir
npm http request GET https://registry.npmjs.org/rc
npm http 200 https://registry.npmjs.org/node-gyp
npm http fetch GET https://registry.npmjs.org/node-gyp/-/node-gyp-3.3.1.tgz
npm http 200 https://registry.npmjs.org/node-ninja
npm http fetch GET https://registry.npmjs.org/node-ninja/-/node-ninja-1.0.1.tgz
npm http 200 https://registry.npmjs.org/npmlog
npm http fetch GET https://registry.npmjs.org/npmlog/-/npmlog-2.0.4.tgz
npm http 200 https://registry.npmjs.org/noop-logger
npm http 200 https://registry.npmjs.org/pump
npm http fetch GET https://registry.npmjs.org/noop-logger/-/noop-logger-0.1.1.tgz
npm http fetch GET https://registry.npmjs.org/pump/-/pump-1.0.1.tgz
npm http 200 https://registry.npmjs.org/tar-fs
npm http fetch GET https://registry.npmjs.org/tar-fs/-/tar-fs-1.13.0.tgz
npm http 200 https://registry.npmjs.org/tar-stream
npm http fetch GET https://registry.npmjs.org/tar-stream/-/tar-stream-1.5.2.tgz
npm http 200 https://registry.npmjs.org/os-homedir
npm http 200 https://registry.npmjs.org/rc
npm http 200 https://registry.npmjs.org/github-from-package
npm http fetch 200 https://registry.npmjs.org/node-gyp/-/node-gyp-3.3.1.tgz
npm http fetch GET https://registry.npmjs.org/github-from-package/-/github-from-package-0.0.0.tgz
npm http 200 https://registry.npmjs.org/ghreleases
npm http 200 https://registry.npmjs.org/simple-get
npm http fetch GET https://registry.npmjs.org/ghreleases/-/ghreleases-1.0.5.tgz
npm http fetch GET https://registry.npmjs.org/simple-get/-/simple-get-1.4.3.tgz
npm http fetch 200 https://registry.npmjs.org/node-ninja/-/node-ninja-1.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/npmlog/-/npmlog-2.0.4.tgz
npm http 200 https://registry.npmjs.org/expand-template
npm http fetch 200 https://registry.npmjs.org/noop-logger/-/noop-logger-0.1.1.tgz
npm http fetch GET https://registry.npmjs.org/expand-template/-/expand-template-1.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/pump/-/pump-1.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/tar-stream/-/tar-stream-1.5.2.tgz
npm http fetch 200 https://registry.npmjs.org/tar-fs/-/tar-fs-1.13.0.tgz
npm http fetch 200 https://registry.npmjs.org/ghreleases/-/ghreleases-1.0.5.tgz
npm http fetch 200 https://registry.npmjs.org/github-from-package/-/github-from-package-0.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/expand-template/-/expand-template-1.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/simple-get/-/simple-get-1.4.3.tgz
npm http request GET https://registry.npmjs.org/ghrepos
npm http request GET https://registry.npmjs.org/ghutils
npm http request GET https://registry.npmjs.org/simple-mime
npm http request GET https://registry.npmjs.org/url-template
npm http request GET https://registry.npmjs.org/after
npm http 304 https://registry.npmjs.org/after
npm http 200 https://registry.npmjs.org/url-template
npm http 200 https://registry.npmjs.org/simple-mime
npm http 200 https://registry.npmjs.org/ghrepos
npm http fetch GET https://registry.npmjs.org/url-template/-/url-template-2.0.7.tgz
npm http fetch GET https://registry.npmjs.org/simple-mime/-/simple-mime-0.1.0.tgz
npm http fetch GET https://registry.npmjs.org/ghrepos/-/ghrepos-2.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/url-template/-/url-template-2.0.7.tgz
npm http fetch 200 https://registry.npmjs.org/simple-mime/-/simple-mime-0.1.0.tgz
npm http fetch 200 https://registry.npmjs.org/ghrepos/-/ghrepos-2.0.0.tgz
npm http 200 https://registry.npmjs.org/ghutils
npm http fetch GET https://registry.npmjs.org/ghutils/-/ghutils-3.2.0.tgz
npm http fetch 200 https://registry.npmjs.org/ghutils/-/ghutils-3.2.0.tgz
npm http request GET https://registry.npmjs.org/jsonist
npm http 200 https://registry.npmjs.org/jsonist
npm http fetch GET https://registry.npmjs.org/jsonist/-/jsonist-1.2.0.tgz
npm http fetch 200 https://registry.npmjs.org/jsonist/-/jsonist-1.2.0.tgz
npm http request GET https://registry.npmjs.org/hyperquest
npm http request GET https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/bl
npm http 200 https://registry.npmjs.org/hyperquest
npm http fetch GET https://registry.npmjs.org/hyperquest/-/hyperquest-1.2.0.tgz
npm http fetch 200 https://registry.npmjs.org/hyperquest/-/hyperquest-1.2.0.tgz
npm http request GET https://registry.npmjs.org/readable-stream
npm http 200 https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/isarray
npm http 200 https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/duplexer2
npm http 200 https://registry.npmjs.org/duplexer2
npm http request GET https://registry.npmjs.org/path-array
npm http request GET https://registry.npmjs.org/which
npm http request GET https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/rimraf
npm http request GET https://registry.npmjs.org/osenv
npm http request GET https://registry.npmjs.org/nopt
npm http request GET https://registry.npmjs.org/fstream
npm http request GET https://registry.npmjs.org/tar
npm http 200 https://registry.npmjs.org/path-array
npm http 200 https://registry.npmjs.org/which
npm http 304 https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/minimatch
npm http fetch GET https://registry.npmjs.org/which/-/which-1.2.10.tgz
npm http fetch GET https://registry.npmjs.org/path-array/-/path-array-1.0.1.tgz
npm WARN deprecated minimatch@1.0.0: Please update to minimatch 3.0.2 or higher to avoid a RegExp DoS issue
npm http 200 https://registry.npmjs.org/osenv
npm http 304 https://registry.npmjs.org/rimraf
npm http 200 https://registry.npmjs.org/nopt
npm http fetch GET https://registry.npmjs.org/minimatch/-/minimatch-1.0.0.tgz
npm http 200 https://registry.npmjs.org/tar
npm http 200 https://registry.npmjs.org/fstream
npm http fetch 200 https://registry.npmjs.org/which/-/which-1.2.10.tgz
npm http fetch 200 https://registry.npmjs.org/path-array/-/path-array-1.0.1.tgz
npm http fetch GET https://registry.npmjs.org/tar/-/tar-2.2.1.tgz
npm http fetch GET https://registry.npmjs.org/fstream/-/fstream-1.0.10.tgz
npm http fetch 200 https://registry.npmjs.org/minimatch/-/minimatch-1.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/tar/-/tar-2.2.1.tgz
npm http fetch 200 https://registry.npmjs.org/fstream/-/fstream-1.0.10.tgz
npm http request GET https://registry.npmjs.org/fs.realpath
npm http 304 https://registry.npmjs.org/fs.realpath
npm WARN deprecated minimatch@2.0.10: Please update to minimatch 3.0.2 or higher to avoid a RegExp DoS issue
npm http request GET https://registry.npmjs.org/abbrev
npm http 200 https://registry.npmjs.org/abbrev
npm http fetch GET https://registry.npmjs.org/abbrev/-/abbrev-1.0.9.tgz
npm http fetch 200 https://registry.npmjs.org/abbrev/-/abbrev-1.0.9.tgz
npm http request GET https://registry.npmjs.org/are-we-there-yet
npm http request GET https://registry.npmjs.org/gauge
npm http request GET https://registry.npmjs.org/ansi
npm http 200 https://registry.npmjs.org/ansi
npm http 200 https://registry.npmjs.org/are-we-there-yet
npm http 200 https://registry.npmjs.org/gauge
npm http fetch GET https://registry.npmjs.org/are-we-there-yet/-/are-we-there-yet-1.1.2.tgz
npm http fetch GET https://registry.npmjs.org/gauge/-/gauge-1.2.7.tgz
npm http fetch 200 https://registry.npmjs.org/are-we-there-yet/-/are-we-there-yet-1.1.2.tgz
npm http fetch 200 https://registry.npmjs.org/gauge/-/gauge-1.2.7.tgz
npm http request GET https://registry.npmjs.org/delegates
npm http 200 https://registry.npmjs.org/delegates
npm http fetch GET https://registry.npmjs.org/delegates/-/delegates-1.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/delegates/-/delegates-1.0.0.tgz
npm http request GET https://registry.npmjs.org/has-unicode
npm http request GET https://registry.npmjs.org/lodash.pad
npm http request GET https://registry.npmjs.org/lodash.padend
npm http request GET https://registry.npmjs.org/lodash.padstart
npm http 200 https://registry.npmjs.org/has-unicode
npm http 200 https://registry.npmjs.org/lodash.padend
npm http 200 https://registry.npmjs.org/lodash.pad
npm http fetch GET https://registry.npmjs.org/has-unicode/-/has-unicode-2.0.1.tgz
npm http fetch GET https://registry.npmjs.org/lodash.padend/-/lodash.padend-4.5.0.tgz
npm http fetch GET https://registry.npmjs.org/lodash.pad/-/lodash.pad-4.4.0.tgz
npm http 200 https://registry.npmjs.org/lodash.padstart
npm http fetch GET https://registry.npmjs.org/lodash.padstart/-/lodash.padstart-4.5.0.tgz
npm http fetch 200 https://registry.npmjs.org/has-unicode/-/has-unicode-2.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/lodash.padend/-/lodash.padend-4.5.0.tgz
npm http fetch 200 https://registry.npmjs.org/lodash.pad/-/lodash.pad-4.4.0.tgz
npm http fetch 200 https://registry.npmjs.org/lodash.padstart/-/lodash.padstart-4.5.0.tgz
npm http request GET https://registry.npmjs.org/lodash._baseslice
npm http request GET https://registry.npmjs.org/lodash._basetostring
npm http request GET https://registry.npmjs.org/lodash.tostring
npm http 200 https://registry.npmjs.org/lodash._baseslice
npm http 200 https://registry.npmjs.org/lodash._basetostring
npm http 200 https://registry.npmjs.org/lodash.tostring
npm http fetch GET https://registry.npmjs.org/lodash._baseslice/-/lodash._baseslice-4.0.0.tgz
npm http fetch GET https://registry.npmjs.org/lodash._basetostring/-/lodash._basetostring-4.12.0.tgz
npm http fetch GET https://registry.npmjs.org/lodash.tostring/-/lodash.tostring-4.1.3.tgz
npm http fetch 200 https://registry.npmjs.org/lodash.tostring/-/lodash.tostring-4.1.3.tgz
npm http fetch 200 https://registry.npmjs.org/lodash._baseslice/-/lodash._baseslice-4.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/lodash._basetostring/-/lodash._basetostring-4.12.0.tgz
npm http request GET https://registry.npmjs.org/os-tmpdir
npm http 304 https://registry.npmjs.org/os-tmpdir
npm http request GET https://registry.npmjs.org/array-index
npm http 200 https://registry.npmjs.org/array-index
npm http fetch GET https://registry.npmjs.org/array-index/-/array-index-1.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/array-index/-/array-index-1.0.0.tgz
npm http request GET https://registry.npmjs.org/es6-symbol
npm http 200 https://registry.npmjs.org/es6-symbol
npm http fetch GET https://registry.npmjs.org/es6-symbol/-/es6-symbol-3.1.0.tgz
npm http fetch 200 https://registry.npmjs.org/es6-symbol/-/es6-symbol-3.1.0.tgz
npm http request GET https://registry.npmjs.org/d
npm http request GET https://registry.npmjs.org/es5-ext
npm http 200 https://registry.npmjs.org/d
npm http fetch GET https://registry.npmjs.org/d/-/d-0.1.1.tgz
npm http 200 https://registry.npmjs.org/es5-ext
npm http fetch GET https://registry.npmjs.org/es5-ext/-/es5-ext-0.10.11.tgz
npm http fetch 200 https://registry.npmjs.org/d/-/d-0.1.1.tgz
npm http fetch 200 https://registry.npmjs.org/es5-ext/-/es5-ext-0.10.11.tgz
npm http request GET https://registry.npmjs.org/es6-iterator
npm http fetch GET https://registry.npmjs.org/es6-symbol/-/es6-symbol-3.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/es6-symbol/-/es6-symbol-3.0.2.tgz
npm http 200 https://registry.npmjs.org/es6-iterator
npm http fetch GET https://registry.npmjs.org/es6-iterator/-/es6-iterator-2.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/es6-iterator/-/es6-iterator-2.0.0.tgz
npm http request GET https://registry.npmjs.org/block-stream
npm http 200 https://registry.npmjs.org/block-stream
npm http fetch GET https://registry.npmjs.org/block-stream/-/block-stream-0.0.9.tgz
npm http fetch 200 https://registry.npmjs.org/block-stream/-/block-stream-0.0.9.tgz
npm http request GET https://registry.npmjs.org/isexe
npm http 200 https://registry.npmjs.org/isexe
npm http fetch GET https://registry.npmjs.org/isexe/-/isexe-1.1.2.tgz
npm http fetch 200 https://registry.npmjs.org/isexe/-/isexe-1.1.2.tgz
npm http request GET https://registry.npmjs.org/end-of-stream
npm http 304 https://registry.npmjs.org/end-of-stream
npm http fetch GET https://registry.npmjs.org/end-of-stream/-/end-of-stream-1.1.0.tgz
npm http fetch 200 https://registry.npmjs.org/end-of-stream/-/end-of-stream-1.1.0.tgz
npm http request GET https://registry.npmjs.org/deep-extend
npm http request GET https://registry.npmjs.org/ini
npm http 200 https://registry.npmjs.org/ini
npm http 200 https://registry.npmjs.org/deep-extend
npm WARN engine deep-extend@0.4.1: wanted: {"node":">=0.12.0","iojs":">=1.0.0"} (current: {"node":"0.10.40","npm":"3.3.12"})
npm http request GET https://registry.npmjs.org/unzip-response
npm http 200 https://registry.npmjs.org/unzip-response
npm http fetch GET https://registry.npmjs.org/unzip-response/-/unzip-response-1.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/unzip-response/-/unzip-response-1.0.0.tgz
npm http request GET https://registry.npmjs.org/jsbn
npm http request GET https://registry.npmjs.org/ecc-jsbn
npm http request GET https://registry.npmjs.org/jodid25519
npm http request GET https://registry.npmjs.org/tweetnacl
npm http 304 https://registry.npmjs.org/jodid25519
npm http 200 https://registry.npmjs.org/tweetnacl
npm http 304 https://registry.npmjs.org/ecc-jsbn
npm http 200 https://registry.npmjs.org/jsbn
npm http fetch GET https://registry.npmjs.org/tweetnacl/-/tweetnacl-0.13.3.tgz
npm http fetch 200 https://registry.npmjs.org/tweetnacl/-/tweetnacl-0.13.3.tgz
npm http request GET https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/noop-fn
npm http request GET https://registry.npmjs.org/sqlite3
npm http 304 https://registry.npmjs.org/immediate
npm http 200 https://registry.npmjs.org/sqlite3
npm http fetch GET https://registry.npmjs.org/sqlite3/-/sqlite3-3.1.4.tgz
npm http fetch 200 https://registry.npmjs.org/sqlite3/-/sqlite3-3.1.4.tgz
npm http 304 https://registry.npmjs.org/noop-fn
npm WARN prefer global node-ninja@1.0.1 should be installed with -g
npm WARN prefer global node-gyp@3.3.1 should be installed with -g
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
npm http request GET https://registry.npmjs.org/fs-extra-promise
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/request
npm http request GET https://registry.npmjs.org/jxc
npm http request GET https://registry.npmjs.org/unzip
npm http 304 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/fs-extra-promise
npm http 304 https://registry.npmjs.org/request
npm http 200 https://registry.npmjs.org/jxc
npm http 200 https://registry.npmjs.org/unzip
npm http request GET https://registry.npmjs.org/fs-extra
npm http request GET https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/fs-extra
npm http 304 https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/jsonfile
npm http request GET https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/graceful-fs
npm http 200 https://registry.npmjs.org/jsonfile
npm http 304 https://registry.npmjs.org/rimraf
npm http request GET https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/fs.realpath
npm http request GET https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/inherits
npm http request GET https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/once
npm http request GET https://registry.npmjs.org/path-is-absolute
npm http 304 https://registry.npmjs.org/fs.realpath
npm http 304 https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/minimatch
npm http 200 https://registry.npmjs.org/inflight
npm http 304 https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http request GET https://registry.npmjs.org/wrappy
npm http 200 https://registry.npmjs.org/wrappy
npm http request GET https://registry.npmjs.org/brace-expansion
npm http 304 https://registry.npmjs.org/brace-expansion
npm http request GET https://registry.npmjs.org/balanced-match
npm http request GET https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/balanced-match
npm http 304 https://registry.npmjs.org/concat-map
npm http request GET https://registry.npmjs.org/progress
npm http request GET https://registry.npmjs.org/adm-zip
npm http 200 https://registry.npmjs.org/adm-zip
npm http 200 https://registry.npmjs.org/progress
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/immediate
npm http 304 https://registry.npmjs.org/inline-process-browser
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/jstransform
npm http request GET https://registry.npmjs.org/esprima
npm http request GET https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/esprima
npm http 304 https://registry.npmjs.org/through
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/commoner
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/object-assign
npm http request GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/commoner
npm http 304 https://registry.npmjs.org/object-assign
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 200 https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/detective
npm http request GET https://registry.npmjs.org/iconv-lite
npm http request GET https://registry.npmjs.org/mkdirp
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/q
npm http request GET https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/commander
npm http 304 https://registry.npmjs.org/detective
npm http 304 https://registry.npmjs.org/private
npm http 200 https://registry.npmjs.org/mkdirp
npm http 200 https://registry.npmjs.org/iconv-lite
npm http 304 https://registry.npmjs.org/q
npm http 304 https://registry.npmjs.org/recast
npm http request GET https://registry.npmjs.org/graceful-readlink
npm http 304 https://registry.npmjs.org/graceful-readlink
npm http request GET https://registry.npmjs.org/acorn
npm http request GET https://registry.npmjs.org/defined
npm http 304 https://registry.npmjs.org/acorn
npm http 304 https://registry.npmjs.org/defined
npm http request GET https://registry.npmjs.org/minimist
npm http 304 https://registry.npmjs.org/minimist
npm http request GET https://registry.npmjs.org/ast-types
npm http 304 https://registry.npmjs.org/ast-types
npm http request GET https://registry.npmjs.org/amdefine
npm http 304 https://registry.npmjs.org/amdefine
npm http request GET https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/falafel
npm http 304 https://registry.npmjs.org/through2
npm http request GET https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/foreach
npm http 200 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/object-keys
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/xtend
npm http 200 https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/core-util-is
npm http 304 https://registry.npmjs.org/string_decoder
npm http request GET https://registry.npmjs.org/esmangle-evaluator
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/bl
npm http request GET https://registry.npmjs.org/caseless
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/forever-agent
npm http request GET https://registry.npmjs.org/form-data
npm http request GET https://registry.npmjs.org/json-stringify-safe
npm http request GET https://registry.npmjs.org/mime-types
npm http request GET https://registry.npmjs.org/node-uuid
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/tunnel-agent
npm http request GET https://registry.npmjs.org/tough-cookie
npm http request GET https://registry.npmjs.org/http-signature
npm http request GET https://registry.npmjs.org/oauth-sign
npm http request GET https://registry.npmjs.org/hawk
npm http request GET https://registry.npmjs.org/aws-sign2
npm http request GET https://registry.npmjs.org/stringstream
npm http request GET https://registry.npmjs.org/combined-stream
npm http request GET https://registry.npmjs.org/isstream
npm http request GET https://registry.npmjs.org/har-validator
npm http 304 https://registry.npmjs.org/form-data
npm http 200 https://registry.npmjs.org/caseless
npm http 304 https://registry.npmjs.org/forever-agent
npm http 304 https://registry.npmjs.org/bl
npm http 200 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/json-stringify-safe
npm http 304 https://registry.npmjs.org/mime-types
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/tunnel-agent
npm http 200 https://registry.npmjs.org/node-uuid
npm http 304 https://registry.npmjs.org/tough-cookie
npm http 304 https://registry.npmjs.org/http-signature
npm http 304 https://registry.npmjs.org/oauth-sign
npm http 200 https://registry.npmjs.org/aws-sign2
npm http 304 https://registry.npmjs.org/stringstream
npm http 304 https://registry.npmjs.org/combined-stream
npm http 200 https://registry.npmjs.org/isstream
npm http 304 https://registry.npmjs.org/har-validator
npm http 200 https://registry.npmjs.org/hawk
npm http request GET https://registry.npmjs.org/process-nextick-args
npm http request GET https://registry.npmjs.org/util-deprecate
npm http 304 https://registry.npmjs.org/process-nextick-args
npm http 200 https://registry.npmjs.org/util-deprecate
npm http request GET https://registry.npmjs.org/delayed-stream
npm http 304 https://registry.npmjs.org/delayed-stream
npm http request GET https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/mime-db
npm http 304 https://registry.npmjs.org/mime-db
npm http request GET https://registry.npmjs.org/chalk
npm http request GET https://registry.npmjs.org/is-my-json-valid
npm http 304 https://registry.npmjs.org/is-my-json-valid
npm http 304 https://registry.npmjs.org/chalk
npm http request GET https://registry.npmjs.org/ansi-styles
npm http request GET https://registry.npmjs.org/escape-string-regexp
npm http request GET https://registry.npmjs.org/has-ansi
npm http request GET https://registry.npmjs.org/strip-ansi
npm http request GET https://registry.npmjs.org/supports-color
npm http 304 https://registry.npmjs.org/escape-string-regexp
npm http 304 https://registry.npmjs.org/strip-ansi
npm http 304 https://registry.npmjs.org/supports-color
npm http 304 https://registry.npmjs.org/has-ansi
npm http 304 https://registry.npmjs.org/ansi-styles
npm http request GET https://registry.npmjs.org/ansi-regex
npm http 200 https://registry.npmjs.org/ansi-regex
npm http request GET https://registry.npmjs.org/generate-function
npm http request GET https://registry.npmjs.org/generate-object-property
npm http request GET https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/generate-function
npm http 304 https://registry.npmjs.org/jsonpointer
npm http 200 https://registry.npmjs.org/generate-object-property
npm http request GET https://registry.npmjs.org/is-property
npm http 200 https://registry.npmjs.org/is-property
npm http request GET https://registry.npmjs.org/hoek
npm http request GET https://registry.npmjs.org/boom
npm http request GET https://registry.npmjs.org/cryptiles
npm http request GET https://registry.npmjs.org/sntp
npm http 304 https://registry.npmjs.org/sntp
npm http 304 https://registry.npmjs.org/cryptiles
npm http 200 https://registry.npmjs.org/boom
npm http 200 https://registry.npmjs.org/hoek
npm http request GET https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/asn1
npm http request GET https://registry.npmjs.org/ctype
npm http 304 https://registry.npmjs.org/ctype
npm http 304 https://registry.npmjs.org/assert-plus
npm http 304 https://registry.npmjs.org/asn1
npm http request GET https://registry.npmjs.org/fstream
npm http request GET https://registry.npmjs.org/pullstream
npm http request GET https://registry.npmjs.org/binary
npm http request GET https://registry.npmjs.org/setimmediate
npm http request GET https://registry.npmjs.org/match-stream
npm http 304 https://registry.npmjs.org/binary
npm http 200 https://registry.npmjs.org/setimmediate
npm http 200 https://registry.npmjs.org/fstream
npm http 304 https://registry.npmjs.org/match-stream
npm http 304 https://registry.npmjs.org/pullstream
npm http request GET https://registry.npmjs.org/chainsaw
npm http request GET https://registry.npmjs.org/buffers
npm http 304 https://registry.npmjs.org/buffers
npm http 304 https://registry.npmjs.org/chainsaw
npm http request GET https://registry.npmjs.org/traverse
npm http 200 https://registry.npmjs.org/traverse
npm http request GET https://registry.npmjs.org/graceful-fs
npm http 304 https://registry.npmjs.org/graceful-fs
npm WARN deprecated graceful-fs@3.0.8: graceful-fs v3.0.0 and before will fail on node releases >= v7.0. Please update to graceful-fs@^4.0.0 as soon as possible. Use 'npm ls graceful-fs' to find it in the tree.
npm http request GET https://registry.npmjs.org/over
npm http request GET https://registry.npmjs.org/slice-stream
npm http 304 https://registry.npmjs.org/slice-stream
npm http 304 https://registry.npmjs.org/over
npm WARN EPACKAGEJSON install@0.0.1 No repository field.
npm http request GET https://registry.npmjs.org/pouchdb-node
npm http request GET https://registry.npmjs.org/balanced-match
npm http request GET https://registry.npmjs.org/body-parser
npm http request GET https://registry.npmjs.org/concat-map
npm http request GET https://registry.npmjs.org/express
npm http request GET https://registry.npmjs.org/bn.js
npm http request GET https://registry.npmjs.org/forever-agent
npm http request GET https://registry.npmjs.org/express-pouchdb
npm http request GET https://registry.npmjs.org/inherits
npm http request GET https://registry.npmjs.org/fs-extra-promise
npm http request GET https://registry.npmjs.org/is-property
npm http request GET https://registry.npmjs.org/js-extend
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/long
npm http request GET https://registry.npmjs.org/minimist
npm http request GET https://registry.npmjs.org/multiplex
npm http request GET https://registry.npmjs.org/node-uuid
npm http request GET https://registry.npmjs.org/request
npm http request GET https://registry.npmjs.org/socket.io-client
npm http request GET https://registry.npmjs.org/leveldown-mobile
npm http request GET https://registry.npmjs.org/nock
npm http request GET https://registry.npmjs.org/randomstring
npm http request GET https://registry.npmjs.org/proxyquire
npm http request GET https://registry.npmjs.org/request-promise
npm http request GET https://registry.npmjs.org/urlsafe-base64
npm http request GET https://registry.npmjs.org/tape
npm http request GET https://registry.npmjs.org/supertest
npm http request GET https://registry.npmjs.org/sinon
npm http request GET https://registry.npmjs.org/supertest-as-promised
npm http request GET https://registry.npmjs.org/tape-catch
npm http request GET https://registry.npmjs.org/tmp
npm http request GET https://registry.npmjs.org/uuid
npm http 304 https://registry.npmjs.org/balanced-match
npm http 304 https://registry.npmjs.org/body-parser
npm http 304 https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/express
npm http 304 https://registry.npmjs.org/forever-agent
npm http 304 https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/fs-extra-promise
npm http 304 https://registry.npmjs.org/is-property
npm http 200 https://registry.npmjs.org/bn.js
npm http 304 https://registry.npmjs.org/lie
npm http fetch GET https://registry.npmjs.org/balanced-match/-/balanced-match-0.2.0.tgz
npm http 304 https://registry.npmjs.org/minimist
npm http fetch GET https://registry.npmjs.org/bn.js/-/bn.js-4.10.0.tgz
npm http 304 https://registry.npmjs.org/js-extend
npm http 304 https://registry.npmjs.org/node-uuid
npm http 304 https://registry.npmjs.org/express-pouchdb
npm http 304 https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/socket.io-client
npm http 200 https://registry.npmjs.org/nock
npm http 304 https://registry.npmjs.org/multiplex
npm http 200 https://registry.npmjs.org/pouchdb-node
npm http fetch GET https://registry.npmjs.org/nock/-/nock-2.12.0.tgz
npm http fetch GET https://registry.npmjs.org/pouchdb-node/-/pouchdb-node-5.4.4.tgz
npm http 200 https://registry.npmjs.org/request-promise
npm http 304 https://registry.npmjs.org/long
npm http 304 https://registry.npmjs.org/leveldown-mobile
npm http 304 https://registry.npmjs.org/tape
npm http 200 https://registry.npmjs.org/supertest
npm http fetch GET https://registry.npmjs.org/tape/-/tape-4.0.0.tgz
npm http fetch GET https://registry.npmjs.org/supertest/-/supertest-1.1.0.tgz
npm http 200 https://registry.npmjs.org/proxyquire
npm http 200 https://registry.npmjs.org/sinon
npm http 200 https://registry.npmjs.org/tmp
npm http 200 https://registry.npmjs.org/uuid
npm http fetch 200 https://registry.npmjs.org/balanced-match/-/balanced-match-0.2.0.tgz
npm http fetch GET https://registry.npmjs.org/uuid/-/uuid-2.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/bn.js/-/bn.js-4.10.0.tgz
npm http 200 https://registry.npmjs.org/randomstring
npm http fetch GET https://registry.npmjs.org/randomstring/-/randomstring-1.1.5.tgz
npm http fetch 200 https://registry.npmjs.org/nock/-/nock-2.12.0.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-node/-/pouchdb-node-5.4.4.tgz
npm http fetch 200 https://registry.npmjs.org/tape/-/tape-4.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/supertest/-/supertest-1.1.0.tgz
npm http 200 https://registry.npmjs.org/tape-catch
npm http fetch 200 https://registry.npmjs.org/uuid/-/uuid-2.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/randomstring/-/randomstring-1.1.5.tgz
npm http 304 https://registry.npmjs.org/urlsafe-base64
npm http 200 https://registry.npmjs.org/supertest-as-promised
npm http request GET https://registry.npmjs.org/bytes
npm http request GET https://registry.npmjs.org/content-type
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/depd
npm http request GET https://registry.npmjs.org/http-errors
npm http request GET https://registry.npmjs.org/iconv-lite
npm http request GET https://registry.npmjs.org/on-finished
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/raw-body
npm http request GET https://registry.npmjs.org/type-is
npm http 304 https://registry.npmjs.org/http-errors
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/bytes
npm http 304 https://registry.npmjs.org/depd
npm http 304 https://registry.npmjs.org/content-type
npm http 304 https://registry.npmjs.org/iconv-lite
npm http 304 https://registry.npmjs.org/on-finished
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/raw-body
npm http 304 https://registry.npmjs.org/type-is
npm http request GET https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/statuses
npm http 304 https://registry.npmjs.org/statuses
npm http request GET https://registry.npmjs.org/ee-first
npm http 304 https://registry.npmjs.org/ee-first
npm http request GET https://registry.npmjs.org/unpipe
npm http 304 https://registry.npmjs.org/unpipe
npm http request GET https://registry.npmjs.org/media-typer
npm http request GET https://registry.npmjs.org/mime-types
npm http 304 https://registry.npmjs.org/mime-types
npm http 304 https://registry.npmjs.org/media-typer
npm http request GET https://registry.npmjs.org/mime-db
npm http 304 https://registry.npmjs.org/mime-db
npm http request GET https://registry.npmjs.org/accepts
npm http request GET https://registry.npmjs.org/array-flatten
npm http request GET https://registry.npmjs.org/content-disposition
npm http request GET https://registry.npmjs.org/cookie
npm http request GET https://registry.npmjs.org/cookie-signature
npm http request GET https://registry.npmjs.org/escape-html
npm http request GET https://registry.npmjs.org/etag
npm http request GET https://registry.npmjs.org/finalhandler
npm http request GET https://registry.npmjs.org/fresh
npm http request GET https://registry.npmjs.org/merge-descriptors
npm http request GET https://registry.npmjs.org/methods
npm http request GET https://registry.npmjs.org/parseurl
npm http request GET https://registry.npmjs.org/path-to-regexp
npm http request GET https://registry.npmjs.org/proxy-addr
npm http request GET https://registry.npmjs.org/range-parser
npm http request GET https://registry.npmjs.org/send
npm http request GET https://registry.npmjs.org/serve-static
npm http request GET https://registry.npmjs.org/utils-merge
npm http request GET https://registry.npmjs.org/vary
npm http 304 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/cookie
npm http 304 https://registry.npmjs.org/content-disposition
npm http 304 https://registry.npmjs.org/array-flatten
npm http 304 https://registry.npmjs.org/cookie-signature
npm http 200 https://registry.npmjs.org/escape-html
npm http 304 https://registry.npmjs.org/etag
npm http 304 https://registry.npmjs.org/fresh
npm http 304 https://registry.npmjs.org/merge-descriptors
npm http 200 https://registry.npmjs.org/finalhandler
npm http 200 https://registry.npmjs.org/methods
npm http 200 https://registry.npmjs.org/parseurl
npm http 304 https://registry.npmjs.org/proxy-addr
npm http 304 https://registry.npmjs.org/range-parser
npm http 304 https://registry.npmjs.org/path-to-regexp
npm http 304 https://registry.npmjs.org/send
npm http 304 https://registry.npmjs.org/serve-static
npm http 304 https://registry.npmjs.org/utils-merge
npm http 304 https://registry.npmjs.org/vary
npm http request GET https://registry.npmjs.org/negotiator
npm http 304 https://registry.npmjs.org/negotiator
npm http request GET https://registry.npmjs.org/forwarded
npm http request GET https://registry.npmjs.org/ipaddr.js
npm http 304 https://registry.npmjs.org/ipaddr.js
npm http 200 https://registry.npmjs.org/forwarded
npm http request GET https://registry.npmjs.org/destroy
npm http request GET https://registry.npmjs.org/mime
npm http 304 https://registry.npmjs.org/destroy
npm http 304 https://registry.npmjs.org/mime
npm http request GET https://registry.npmjs.org/basic-auth
npm http request GET https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/compression
npm http request GET https://registry.npmjs.org/cookie-parser
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/header-case-normalizer
npm http request GET https://registry.npmjs.org/multiparty
npm http request GET https://registry.npmjs.org/pouchdb-all-dbs
npm http request GET https://registry.npmjs.org/pouchdb-auth
npm http request GET https://registry.npmjs.org/pouchdb-find
npm http request GET https://registry.npmjs.org/pouchdb-list
npm http request GET https://registry.npmjs.org/pouchdb-replicator
npm http request GET https://registry.npmjs.org/pouchdb-rewrite
npm http request GET https://registry.npmjs.org/pouchdb-security
npm http request GET https://registry.npmjs.org/pouchdb-show
npm http request GET https://registry.npmjs.org/pouchdb-size
npm http request GET https://registry.npmjs.org/pouchdb-update
npm http request GET https://registry.npmjs.org/pouchdb-validation
npm http request GET https://registry.npmjs.org/pouchdb-vhost
npm http request GET https://registry.npmjs.org/pouchdb-wrappers
npm http 304 https://registry.npmjs.org/basic-auth
npm http 304 https://registry.npmjs.org/compression
npm http 304 https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/extend
npm http 200 https://registry.npmjs.org/multiparty
npm http 304 https://registry.npmjs.org/pouchdb-auth
npm http 304 https://registry.npmjs.org/pouchdb-find
npm http 304 https://registry.npmjs.org/cookie-parser
npm http 304 https://registry.npmjs.org/pouchdb-all-dbs
npm http 304 https://registry.npmjs.org/header-case-normalizer
npm http 304 https://registry.npmjs.org/pouchdb-list
npm http 304 https://registry.npmjs.org/pouchdb-replicator
npm http 304 https://registry.npmjs.org/pouchdb-show
npm http 304 https://registry.npmjs.org/pouchdb-security
npm http 304 https://registry.npmjs.org/pouchdb-size
npm http 304 https://registry.npmjs.org/pouchdb-validation
npm http 304 https://registry.npmjs.org/pouchdb-vhost
npm http 304 https://registry.npmjs.org/pouchdb-update
npm http 304 https://registry.npmjs.org/pouchdb-wrappers
npm http 304 https://registry.npmjs.org/pouchdb-rewrite
npm http request GET https://registry.npmjs.org/compressible
npm http request GET https://registry.npmjs.org/on-headers
npm http 304 https://registry.npmjs.org/on-headers
npm http 304 https://registry.npmjs.org/compressible
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/stream-counter
npm http 304 https://registry.npmjs.org/stream-counter
npm http 304 https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/argsarray
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/tiny-queue
npm http 304 https://registry.npmjs.org/es3ify
npm http 304 https://registry.npmjs.org/argsarray
npm http 304 https://registry.npmjs.org/tiny-queue
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/jstransform
npm http request GET https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 304 https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/through
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/base62
npm http 304 https://registry.npmjs.org/source-map
npm http request GET https://registry.npmjs.org/amdefine
npm http 304 https://registry.npmjs.org/amdefine
npm http request GET https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/inline-process-browser
npm http 304 https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/falafel
npm http 304 https://registry.npmjs.org/through2
npm http request GET https://registry.npmjs.org/acorn
npm http request GET https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/acorn
npm http 304 https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/xtend
npm http request GET https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http 304 https://registry.npmjs.org/recast
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/ast-types
npm http 304 https://registry.npmjs.org/private
npm http 304 https://registry.npmjs.org/ast-types
npm http request GET https://registry.npmjs.org/base64url
npm http request GET https://registry.npmjs.org/couchdb-calculate-session-id
npm http request GET https://registry.npmjs.org/crypto-lite
npm http request GET https://registry.npmjs.org/pouchdb
npm http request GET https://registry.npmjs.org/pouchdb-bulkdocs-wrapper
npm http request GET https://registry.npmjs.org/pouchdb-plugin-error
npm http request GET https://registry.npmjs.org/pouchdb-promise
npm http request GET https://registry.npmjs.org/pouchdb-req-http-query
npm http request GET https://registry.npmjs.org/pouchdb-system-db
npm http request GET https://registry.npmjs.org/promise-nodify
npm http request GET https://registry.npmjs.org/secure-random
npm http 304 https://registry.npmjs.org/base64url
npm http 304 https://registry.npmjs.org/pouchdb
npm http 304 https://registry.npmjs.org/pouchdb-promise
npm http 304 https://registry.npmjs.org/pouchdb-req-http-query
npm http 304 https://registry.npmjs.org/couchdb-calculate-session-id
npm http 304 https://registry.npmjs.org/pouchdb-system-db
npm http 304 https://registry.npmjs.org/promise-nodify
npm http 304 https://registry.npmjs.org/pouchdb-bulkdocs-wrapper
npm http 304 https://registry.npmjs.org/crypto-lite
npm http 304 https://registry.npmjs.org/pouchdb-plugin-error
npm http 304 https://registry.npmjs.org/secure-random
npm http request GET https://registry.npmjs.org/concat-stream
npm http request GET https://registry.npmjs.org/meow
npm http 304 https://registry.npmjs.org/meow
npm http 200 https://registry.npmjs.org/concat-stream
npm http request GET https://registry.npmjs.org/typedarray
npm http 304 https://registry.npmjs.org/typedarray
npm http request GET https://registry.npmjs.org/camelcase-keys
npm http request GET https://registry.npmjs.org/indent-string
npm http request GET https://registry.npmjs.org/object-assign
npm http 304 https://registry.npmjs.org/camelcase-keys
npm http 304 https://registry.npmjs.org/indent-string
npm http 304 https://registry.npmjs.org/object-assign
npm http request GET https://registry.npmjs.org/map-obj
npm http request GET https://registry.npmjs.org/camelcase
npm http 304 https://registry.npmjs.org/camelcase
npm http 200 https://registry.npmjs.org/map-obj
npm http request GET https://registry.npmjs.org/get-stdin
npm http request GET https://registry.npmjs.org/repeating
npm http 200 https://registry.npmjs.org/get-stdin
npm http 200 https://registry.npmjs.org/repeating
npm http request GET https://registry.npmjs.org/is-finite
npm http 304 https://registry.npmjs.org/is-finite
npm http request GET https://registry.npmjs.org/number-is-nan
npm http 304 https://registry.npmjs.org/number-is-nan
npm http request GET https://registry.npmjs.org/aproba
npm http 304 https://registry.npmjs.org/aproba
npm http request GET https://registry.npmjs.org/double-ended-queue
npm http request GET https://registry.npmjs.org/fruitdown
npm http request GET https://registry.npmjs.org/level-write-stream
npm http request GET https://registry.npmjs.org/levelup
npm http request GET https://registry.npmjs.org/localstorage-down
npm http request GET https://registry.npmjs.org/memdown
npm http request GET https://registry.npmjs.org/pouchdb-collate
npm http request GET https://registry.npmjs.org/pouchdb-collections
npm http request GET https://registry.npmjs.org/scope-eval
npm http request GET https://registry.npmjs.org/spark-md5
npm http request GET https://registry.npmjs.org/sublevel-pouchdb
npm http request GET https://registry.npmjs.org/vuvuzela
npm http request GET https://registry.npmjs.org/js-extend
npm http request GET https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/double-ended-queue
npm http 304 https://registry.npmjs.org/memdown
npm http 304 https://registry.npmjs.org/levelup
npm http 304 https://registry.npmjs.org/level-write-stream
npm http 304 https://registry.npmjs.org/localstorage-down
npm http 304 https://registry.npmjs.org/fruitdown
npm http 304 https://registry.npmjs.org/pouchdb-collections
npm http 304 https://registry.npmjs.org/pouchdb-collate
npm http 304 https://registry.npmjs.org/js-extend
npm http 304 https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/scope-eval
npm http 304 https://registry.npmjs.org/sublevel-pouchdb
npm http 304 https://registry.npmjs.org/vuvuzela
npm http 304 https://registry.npmjs.org/spark-md5
npm http request GET https://registry.npmjs.org/abstract-leveldown
npm http request GET https://registry.npmjs.org/d64
npm http 304 https://registry.npmjs.org/abstract-leveldown
npm http 304 https://registry.npmjs.org/d64
npm http request GET https://registry.npmjs.org/end-stream
npm http 304 https://registry.npmjs.org/end-stream
npm http request GET https://registry.npmjs.org/write-stream
npm http 304 https://registry.npmjs.org/write-stream
npm http request GET https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/deferred-leveldown
npm http request GET https://registry.npmjs.org/level-codec
npm http request GET https://registry.npmjs.org/level-errors
npm http request GET https://registry.npmjs.org/level-iterator-stream
npm http request GET https://registry.npmjs.org/prr
npm http request GET https://registry.npmjs.org/semver
npm http 304 https://registry.npmjs.org/prr
npm http 304 https://registry.npmjs.org/semver
npm http 304 https://registry.npmjs.org/deferred-leveldown
npm http 304 https://registry.npmjs.org/level-iterator-stream
npm http 304 https://registry.npmjs.org/level-codec
npm http 304 https://registry.npmjs.org/level-errors
npm http request GET https://registry.npmjs.org/errno
npm http 304 https://registry.npmjs.org/errno
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/es3ify
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http request GET https://registry.npmjs.org/esprima
npm http request GET https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/esprima
npm http 304 https://registry.npmjs.org/jstransform
npm http request GET https://registry.npmjs.org/commoner
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/commoner
npm http 304 https://registry.npmjs.org/base62
npm http 304 https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/detective
npm http request GET https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/mkdirp
npm http request GET https://registry.npmjs.org/q
npm http 304 https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/detective
npm http 304 https://registry.npmjs.org/commander
npm http 304 https://registry.npmjs.org/graceful-fs
npm http 304 https://registry.npmjs.org/q
npm http 304 https://registry.npmjs.org/mkdirp
npm http request GET https://registry.npmjs.org/graceful-readlink
npm http 304 https://registry.npmjs.org/graceful-readlink
npm http request GET https://registry.npmjs.org/defined
npm http 304 https://registry.npmjs.org/defined
npm http request GET https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/once
npm http request GET https://registry.npmjs.org/path-is-absolute
npm http 304 https://registry.npmjs.org/inflight
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http 304 https://registry.npmjs.org/minimatch
npm http 304 https://registry.npmjs.org/once
npm http request GET https://registry.npmjs.org/wrappy
npm http 304 https://registry.npmjs.org/wrappy
npm http request GET https://registry.npmjs.org/brace-expansion
npm http 304 https://registry.npmjs.org/brace-expansion
npm http request GET https://registry.npmjs.org/balanced-match
npm http 304 https://registry.npmjs.org/balanced-match
npm http request GET https://registry.npmjs.org/minimist
npm http 304 https://registry.npmjs.org/minimist
npm http request GET https://registry.npmjs.org/humble-localstorage
npm http request GET https://registry.npmjs.org/tiny-queue
npm http 304 https://registry.npmjs.org/tiny-queue
npm http 304 https://registry.npmjs.org/humble-localstorage
npm http request GET https://registry.npmjs.org/has-localstorage
npm http request GET https://registry.npmjs.org/localstorage-memory
npm http 304 https://registry.npmjs.org/has-localstorage
npm http 304 https://registry.npmjs.org/localstorage-memory
npm http request GET https://registry.npmjs.org/ltgt
npm http request GET https://registry.npmjs.org/functional-red-black-tree
npm http 304 https://registry.npmjs.org/ltgt
npm http 304 https://registry.npmjs.org/functional-red-black-tree
npm http request GET https://registry.npmjs.org/aws-sign2
npm http request GET https://registry.npmjs.org/aws4
npm http request GET https://registry.npmjs.org/bl
npm http request GET https://registry.npmjs.org/caseless
npm http request GET https://registry.npmjs.org/combined-stream
npm http request GET https://registry.npmjs.org/form-data
npm http request GET https://registry.npmjs.org/har-validator
npm http request GET https://registry.npmjs.org/hawk
npm http request GET https://registry.npmjs.org/http-signature
npm http request GET https://registry.npmjs.org/is-typedarray
npm http request GET https://registry.npmjs.org/isstream
npm http request GET https://registry.npmjs.org/json-stringify-safe
npm http request GET https://registry.npmjs.org/oauth-sign
npm http request GET https://registry.npmjs.org/stringstream
npm http request GET https://registry.npmjs.org/tough-cookie
npm http request GET https://registry.npmjs.org/tunnel-agent
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/aws-sign2
npm http 304 https://registry.npmjs.org/caseless
npm http 304 https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/aws4
npm http 304 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/har-validator
npm http 304 https://registry.npmjs.org/hawk
npm http 304 https://registry.npmjs.org/http-signature
npm http 304 https://registry.npmjs.org/is-typedarray
npm http 304 https://registry.npmjs.org/isstream
npm http 304 https://registry.npmjs.org/json-stringify-safe
npm http 304 https://registry.npmjs.org/oauth-sign
npm http 304 https://registry.npmjs.org/stringstream
npm http 304 https://registry.npmjs.org/tough-cookie
npm http 304 https://registry.npmjs.org/tunnel-agent
npm http 304 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/process-nextick-args
npm http request GET https://registry.npmjs.org/util-deprecate
npm http request GET https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/util-deprecate
npm http 304 https://registry.npmjs.org/process-nextick-args
npm http 304 https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/delayed-stream
npm http 304 https://registry.npmjs.org/delayed-stream
npm http request GET https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/chalk
npm http request GET https://registry.npmjs.org/is-my-json-valid
npm http request GET https://registry.npmjs.org/pinkie-promise
npm http 304 https://registry.npmjs.org/chalk
npm http 304 https://registry.npmjs.org/pinkie-promise
npm http 304 https://registry.npmjs.org/is-my-json-valid
npm http request GET https://registry.npmjs.org/ansi-styles
npm http request GET https://registry.npmjs.org/escape-string-regexp
npm http request GET https://registry.npmjs.org/has-ansi
npm http request GET https://registry.npmjs.org/strip-ansi
npm http request GET https://registry.npmjs.org/supports-color
npm http 304 https://registry.npmjs.org/strip-ansi
npm http 304 https://registry.npmjs.org/ansi-styles
npm http 304 https://registry.npmjs.org/supports-color
npm http 304 https://registry.npmjs.org/escape-string-regexp
npm http 304 https://registry.npmjs.org/has-ansi
npm http request GET https://registry.npmjs.org/ansi-regex
npm http 304 https://registry.npmjs.org/ansi-regex
npm http request GET https://registry.npmjs.org/generate-function
npm http request GET https://registry.npmjs.org/generate-object-property
npm http request GET https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/generate-object-property
npm http 304 https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/generate-function
npm http request GET https://registry.npmjs.org/pinkie
npm http 304 https://registry.npmjs.org/pinkie
npm http request GET https://registry.npmjs.org/hoek
npm http request GET https://registry.npmjs.org/cryptiles
npm http request GET https://registry.npmjs.org/sntp
npm http request GET https://registry.npmjs.org/boom
npm http 304 https://registry.npmjs.org/sntp
npm http 304 https://registry.npmjs.org/cryptiles
npm http 304 https://registry.npmjs.org/hoek
npm http 304 https://registry.npmjs.org/boom
npm http request GET https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/jsprim
npm http request GET https://registry.npmjs.org/sshpk
npm http 304 https://registry.npmjs.org/jsprim
npm http 304 https://registry.npmjs.org/assert-plus
npm http 304 https://registry.npmjs.org/sshpk
npm http request GET https://registry.npmjs.org/extsprintf
npm http request GET https://registry.npmjs.org/json-schema
npm http request GET https://registry.npmjs.org/verror
npm http 304 https://registry.npmjs.org/extsprintf
npm http 304 https://registry.npmjs.org/json-schema
npm http 200 https://registry.npmjs.org/verror
npm http request GET https://registry.npmjs.org/asn1
npm http request GET https://registry.npmjs.org/dashdash
npm http request GET https://registry.npmjs.org/getpass
npm http 304 https://registry.npmjs.org/getpass
npm http 304 https://registry.npmjs.org/asn1
npm http 304 https://registry.npmjs.org/dashdash
npm http request GET https://registry.npmjs.org/pull-stream
npm http 304 https://registry.npmjs.org/pull-stream
npm http request GET https://registry.npmjs.org/pull-core
npm http 304 https://registry.npmjs.org/pull-core
npm http request GET https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/pouchdb-promise
npm http 304 https://registry.npmjs.org/pouchdb-promise
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/xmlhttprequest-cookie
npm http 304 https://registry.npmjs.org/xmlhttprequest-cookie
npm http request GET https://registry.npmjs.org/xmlhttprequest
npm http 304 https://registry.npmjs.org/xmlhttprequest
npm http request GET https://registry.npmjs.org/pouchdb-changeslike-wrapper
npm http 304 https://registry.npmjs.org/pouchdb-changeslike-wrapper
npm http request GET https://registry.npmjs.org/couchdb-objects
npm http request GET https://registry.npmjs.org/couchdb-eval
npm http request GET https://registry.npmjs.org/random-uuid-v4
npm http 304 https://registry.npmjs.org/random-uuid-v4
npm http 304 https://registry.npmjs.org/couchdb-objects
npm http 304 https://registry.npmjs.org/couchdb-eval
npm http request GET https://registry.npmjs.org/is-empty
npm http 304 https://registry.npmjs.org/is-empty
npm http request GET https://registry.npmjs.org/jshint
npm http request GET https://registry.npmjs.org/pouchdb-abstract-mapreduce
npm http request GET https://registry.npmjs.org/pouchdb-extend
npm http request GET https://registry.npmjs.org/pouchdb-upsert
npm http request GET https://registry.npmjs.org/spark-md5
npm http 304 https://registry.npmjs.org/jshint
npm http 304 https://registry.npmjs.org/spark-md5
npm http 304 https://registry.npmjs.org/pouchdb-extend
npm http 304 https://registry.npmjs.org/pouchdb-abstract-mapreduce
npm http 304 https://registry.npmjs.org/pouchdb-upsert
npm http request GET https://registry.npmjs.org/cli
npm http request GET https://registry.npmjs.org/console-browserify
npm http request GET https://registry.npmjs.org/exit
npm http request GET https://registry.npmjs.org/htmlparser2
npm http request GET https://registry.npmjs.org/shelljs
npm http request GET https://registry.npmjs.org/strip-json-comments
npm http request GET https://registry.npmjs.org/lodash
npm http request GET https://registry.npmjs.org/minimatch
npm http 200 https://registry.npmjs.org/exit
npm http 304 https://registry.npmjs.org/shelljs
npm http 200 https://registry.npmjs.org/console-browserify
npm http 304 https://registry.npmjs.org/cli
npm http 200 https://registry.npmjs.org/htmlparser2
npm http 304 https://registry.npmjs.org/strip-json-comments
npm http 304 https://registry.npmjs.org/lodash
npm http 304 https://registry.npmjs.org/minimatch
npm WARN deprecated minimatch@2.0.10: Please update to minimatch 3.0.2 or higher to avoid a RegExp DoS issue
npm http request GET https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/glob
npm WARN deprecated minimatch@0.3.0: Please update to minimatch 3.0.2 or higher to avoid a RegExp DoS issue
npm http request GET https://registry.npmjs.org/lru-cache
npm http request GET https://registry.npmjs.org/sigmund
npm http 304 https://registry.npmjs.org/lru-cache
npm http 304 https://registry.npmjs.org/sigmund
npm http request GET https://registry.npmjs.org/date-now
npm http 304 https://registry.npmjs.org/date-now
npm http request GET https://registry.npmjs.org/domhandler
npm http request GET https://registry.npmjs.org/domutils
npm http request GET https://registry.npmjs.org/domelementtype
npm http request GET https://registry.npmjs.org/entities
npm http 304 https://registry.npmjs.org/domhandler
npm http 304 https://registry.npmjs.org/domelementtype
npm http 304 https://registry.npmjs.org/domutils
npm http 304 https://registry.npmjs.org/entities
npm http request GET https://registry.npmjs.org/dom-serializer
npm http 200 https://registry.npmjs.org/dom-serializer
npm http request GET https://registry.npmjs.org/bl
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/http-signature
npm http request GET https://registry.npmjs.org/aws-sign2
npm http request GET https://registry.npmjs.org/har-validator
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/http-signature
npm http 304 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/aws-sign2
npm http 304 https://registry.npmjs.org/har-validator
npm http request GET https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/ctype
npm http request GET https://registry.npmjs.org/assert-plus
npm http 304 https://registry.npmjs.org/assert-plus
npm http 304 https://registry.npmjs.org/ctype
npm http request GET https://registry.npmjs.org/couchdb-render
npm http 304 https://registry.npmjs.org/couchdb-render
npm http request GET https://registry.npmjs.org/couchdb-resp-completer
npm http 304 https://registry.npmjs.org/couchdb-resp-completer
npm http request GET https://registry.npmjs.org/equals
npm http 304 https://registry.npmjs.org/equals
npm http request GET https://registry.npmjs.org/@jkroso%2ftype
npm http 304 https://registry.npmjs.org/@jkroso%2ftype
npm http request GET https://registry.npmjs.org/pouchdb-route
npm http 304 https://registry.npmjs.org/pouchdb-route
npm http request GET https://registry.npmjs.org/pouchdb-promise
npm http 304 https://registry.npmjs.org/pouchdb-promise
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/get-folder-size
npm http 304 https://registry.npmjs.org/get-folder-size
npm http request GET https://registry.npmjs.org/minimist
npm http request GET https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/minimist
npm http request GET https://registry.npmjs.org/fs-extra
npm http 304 https://registry.npmjs.org/fs-extra
npm http request GET https://registry.npmjs.org/jsonfile
npm http request GET https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/rimraf
npm http 200 https://registry.npmjs.org/jsonfile
npm http request GET https://registry.npmjs.org/fs.realpath
npm http 304 https://registry.npmjs.org/fs.realpath
npm http request GET https://registry.npmjs.org/bindings
npm http request GET https://registry.npmjs.org/fast-future
npm http request GET https://registry.npmjs.org/abstract-leveldown
npm http 200 https://registry.npmjs.org/bindings
npm http 304 https://registry.npmjs.org/fast-future
npm http 304 https://registry.npmjs.org/abstract-leveldown
npm http request GET https://registry.npmjs.org/varint
npm http request GET https://registry.npmjs.org/duplexify
npm http request GET https://registry.npmjs.org/readable-stream
npm http 200 https://registry.npmjs.org/duplexify
npm http 200 https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/varint
npm http request GET https://registry.npmjs.org/end-of-stream
npm http 304 https://registry.npmjs.org/end-of-stream
npm http request GET https://registry.npmjs.org/buffer-shims
npm http 304 https://registry.npmjs.org/buffer-shims
npm http request GET https://registry.npmjs.org/deep-equal
npm http request GET https://registry.npmjs.org/debug
npm WARN deprecated lodash@2.4.1: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
npm http request GET https://registry.npmjs.org/chai
npm http request GET https://registry.npmjs.org/propagate
npm http 200 https://registry.npmjs.org/deep-equal
npm http 304 https://registry.npmjs.org/debug
npm http 200 https://registry.npmjs.org/propagate
npm http 200 https://registry.npmjs.org/chai
npm http request GET https://registry.npmjs.org/type-detect
npm http request GET https://registry.npmjs.org/assertion-error
npm http request GET https://registry.npmjs.org/deep-eql
npm http 200 https://registry.npmjs.org/deep-eql
npm http 200 https://registry.npmjs.org/assertion-error
npm http 200 https://registry.npmjs.org/type-detect
npm http fetch GET https://registry.npmjs.org/assertion-error/-/assertion-error-1.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/assertion-error/-/assertion-error-1.0.2.tgz
npm http request GET https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/ip
npm http 304 https://registry.npmjs.org/ip
npm http fetch GET https://registry.npmjs.org/ip/-/ip-1.1.3.tgz
npm http fetch 200 https://registry.npmjs.org/ip/-/ip-1.1.3.tgz
npm http request GET https://registry.npmjs.org/pouchdb-adapter-http
npm http request GET https://registry.npmjs.org/pouchdb-adapter-leveldb
npm http request GET https://registry.npmjs.org/pouchdb-core
npm http request GET https://registry.npmjs.org/pouchdb-mapreduce
npm http request GET https://registry.npmjs.org/pouchdb-replication
npm http 200 https://registry.npmjs.org/pouchdb-mapreduce
npm http fetch GET https://registry.npmjs.org/pouchdb-mapreduce/-/pouchdb-mapreduce-5.4.4.tgz
npm http 200 https://registry.npmjs.org/pouchdb-adapter-http
npm http fetch GET https://registry.npmjs.org/pouchdb-adapter-http/-/pouchdb-adapter-http-5.4.4.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-mapreduce/-/pouchdb-mapreduce-5.4.4.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-adapter-http/-/pouchdb-adapter-http-5.4.4.tgz
npm http 200 https://registry.npmjs.org/pouchdb-core
npm http 200 https://registry.npmjs.org/pouchdb-adapter-leveldb
npm http fetch GET https://registry.npmjs.org/pouchdb-core/-/pouchdb-core-5.4.4.tgz
npm http fetch GET https://registry.npmjs.org/pouchdb-adapter-leveldb/-/pouchdb-adapter-leveldb-5.4.4.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-core/-/pouchdb-core-5.4.4.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-adapter-leveldb/-/pouchdb-adapter-leveldb-5.4.4.tgz
npm http 200 https://registry.npmjs.org/pouchdb-replication
npm http fetch GET https://registry.npmjs.org/pouchdb-replication/-/pouchdb-replication-5.4.4.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-replication/-/pouchdb-replication-5.4.4.tgz
npm http request GET https://registry.npmjs.org/pouchdb-ajax
npm http request GET https://registry.npmjs.org/pouchdb-binary-utils
npm http request GET https://registry.npmjs.org/pouchdb-errors
npm http request GET https://registry.npmjs.org/pouchdb-md5
npm http request GET https://registry.npmjs.org/pouchdb-utils
npm http 200 https://registry.npmjs.org/pouchdb-binary-utils
npm http 200 https://registry.npmjs.org/pouchdb-errors
npm http fetch GET https://registry.npmjs.org/pouchdb-binary-utils/-/pouchdb-binary-utils-5.4.4.tgz
npm http fetch GET https://registry.npmjs.org/pouchdb-errors/-/pouchdb-errors-5.4.4.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-binary-utils/-/pouchdb-binary-utils-5.4.4.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-errors/-/pouchdb-errors-5.4.4.tgz
npm http 200 https://registry.npmjs.org/pouchdb-ajax
npm http 200 https://registry.npmjs.org/pouchdb-md5
npm http 200 https://registry.npmjs.org/pouchdb-utils
npm http fetch GET https://registry.npmjs.org/pouchdb-ajax/-/pouchdb-ajax-5.4.4.tgz
npm http fetch GET https://registry.npmjs.org/pouchdb-md5/-/pouchdb-md5-5.4.4.tgz
npm http fetch GET https://registry.npmjs.org/pouchdb-utils/-/pouchdb-utils-5.4.4.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-ajax/-/pouchdb-ajax-5.4.4.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-utils/-/pouchdb-utils-5.4.4.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-md5/-/pouchdb-md5-5.4.4.tgz
npm http request GET https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/request
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/qs
npm http 200 https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/pouchdb-adapter-leveldb-core
npm http request GET https://registry.npmjs.org/leveldown
npm http 304 https://registry.npmjs.org/leveldown
npm http 200 https://registry.npmjs.org/pouchdb-adapter-leveldb-core
npm http fetch GET https://registry.npmjs.org/pouchdb-adapter-leveldb-core/-/pouchdb-adapter-leveldb-core-5.4.4.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-adapter-leveldb-core/-/pouchdb-adapter-leveldb-core-5.4.4.tgz
npm http request GET https://registry.npmjs.org/nan
npm http request GET https://registry.npmjs.org/prebuild
npm http 304 https://registry.npmjs.org/nan
npm http 304 https://registry.npmjs.org/prebuild
npm http request GET https://registry.npmjs.org/expand-template
npm http request GET https://registry.npmjs.org/ghreleases
npm http request GET https://registry.npmjs.org/github-from-package
npm http request GET https://registry.npmjs.org/node-gyp
npm http request GET https://registry.npmjs.org/node-ninja
npm http request GET https://registry.npmjs.org/noop-logger
npm http request GET https://registry.npmjs.org/npmlog
npm http request GET https://registry.npmjs.org/os-homedir
npm http request GET https://registry.npmjs.org/pump
npm http request GET https://registry.npmjs.org/rc
npm http request GET https://registry.npmjs.org/simple-get
npm http request GET https://registry.npmjs.org/tar-fs
npm http request GET https://registry.npmjs.org/tar-stream
npm http 200 https://registry.npmjs.org/node-gyp
npm http 304 https://registry.npmjs.org/noop-logger
npm http 304 https://registry.npmjs.org/npmlog
npm http 200 https://registry.npmjs.org/os-homedir
npm http 200 https://registry.npmjs.org/pump
npm http 304 https://registry.npmjs.org/rc
npm http 304 https://registry.npmjs.org/simple-get
npm http 304 https://registry.npmjs.org/tar-fs
npm http 304 https://registry.npmjs.org/expand-template
npm http 304 https://registry.npmjs.org/tar-stream
npm http 304 https://registry.npmjs.org/ghreleases
npm http 304 https://registry.npmjs.org/node-ninja
npm http 304 https://registry.npmjs.org/github-from-package
npm http request GET https://registry.npmjs.org/after
npm http request GET https://registry.npmjs.org/ghrepos
npm http request GET https://registry.npmjs.org/ghutils
npm http request GET https://registry.npmjs.org/simple-mime
npm http request GET https://registry.npmjs.org/url-template
npm http 304 https://registry.npmjs.org/url-template
npm http 304 https://registry.npmjs.org/after
npm http 304 https://registry.npmjs.org/ghrepos
npm http 304 https://registry.npmjs.org/simple-mime
npm http 304 https://registry.npmjs.org/ghutils
npm http request GET https://registry.npmjs.org/jsonist
npm http 304 https://registry.npmjs.org/jsonist
npm http request GET https://registry.npmjs.org/hyperquest
npm http request GET https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/hyperquest
npm http request GET https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/duplexer2
npm http 304 https://registry.npmjs.org/duplexer2
npm http request GET https://registry.npmjs.org/fstream
npm http request GET https://registry.npmjs.org/nopt
npm http request GET https://registry.npmjs.org/osenv
npm http request GET https://registry.npmjs.org/path-array
npm http request GET https://registry.npmjs.org/tar
npm http request GET https://registry.npmjs.org/which
npm http request GET https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/minimatch
npm http 304 https://registry.npmjs.org/nopt
npm http 304 https://registry.npmjs.org/path-array
npm http 200 https://registry.npmjs.org/osenv
npm http 200 https://registry.npmjs.org/tar
npm http 200 https://registry.npmjs.org/fstream
npm http 304 https://registry.npmjs.org/which
npm http 304 https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/minimatch
npm WARN deprecated minimatch@1.0.0: Please update to minimatch 3.0.2 or higher to avoid a RegExp DoS issue
npm http request GET https://registry.npmjs.org/abbrev
npm http 304 https://registry.npmjs.org/abbrev
npm http request GET https://registry.npmjs.org/ansi
npm http request GET https://registry.npmjs.org/are-we-there-yet
npm http request GET https://registry.npmjs.org/gauge
npm http 304 https://registry.npmjs.org/ansi
npm http 304 https://registry.npmjs.org/are-we-there-yet
npm http 304 https://registry.npmjs.org/gauge
npm http request GET https://registry.npmjs.org/delegates
npm http 304 https://registry.npmjs.org/delegates
npm http request GET https://registry.npmjs.org/lodash.pad
npm http request GET https://registry.npmjs.org/has-unicode
npm http request GET https://registry.npmjs.org/lodash.padend
npm http request GET https://registry.npmjs.org/lodash.padstart
npm http 304 https://registry.npmjs.org/has-unicode
npm http 304 https://registry.npmjs.org/lodash.pad
npm http 304 https://registry.npmjs.org/lodash.padend
npm http 200 https://registry.npmjs.org/lodash.padstart
npm http request GET https://registry.npmjs.org/lodash._baseslice
npm http request GET https://registry.npmjs.org/lodash._basetostring
npm http request GET https://registry.npmjs.org/lodash.tostring
npm http 304 https://registry.npmjs.org/lodash._baseslice
npm http 304 https://registry.npmjs.org/lodash._basetostring
npm http 200 https://registry.npmjs.org/lodash.tostring
npm http request GET https://registry.npmjs.org/os-tmpdir
npm http 304 https://registry.npmjs.org/os-tmpdir
npm http request GET https://registry.npmjs.org/array-index
npm http 304 https://registry.npmjs.org/array-index
npm http request GET https://registry.npmjs.org/es6-symbol
npm http 304 https://registry.npmjs.org/es6-symbol
npm http request GET https://registry.npmjs.org/d
npm http request GET https://registry.npmjs.org/es5-ext
npm http 304 https://registry.npmjs.org/d
npm http 304 https://registry.npmjs.org/es5-ext
npm http request GET https://registry.npmjs.org/es6-iterator
npm http 200 https://registry.npmjs.org/es6-iterator
npm http request GET https://registry.npmjs.org/block-stream
npm http 304 https://registry.npmjs.org/block-stream
npm http request GET https://registry.npmjs.org/isexe
npm http 304 https://registry.npmjs.org/isexe
npm http request GET https://registry.npmjs.org/end-of-stream
npm http 304 https://registry.npmjs.org/end-of-stream
npm http request GET https://registry.npmjs.org/deep-extend
npm http request GET https://registry.npmjs.org/ini
npm http 304 https://registry.npmjs.org/deep-extend
npm http 304 https://registry.npmjs.org/ini
npm WARN engine deep-extend@0.4.1: wanted: {"node":">=0.12.0","iojs":">=1.0.0"} (current: {"node":"0.10.40","npm":"3.3.12"})
npm http request GET https://registry.npmjs.org/unzip-response
npm http 304 https://registry.npmjs.org/unzip-response
npm http request GET https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/pouchdb-adapter-utils
npm http request GET https://registry.npmjs.org/pouchdb-json
npm http request GET https://registry.npmjs.org/pouchdb-merge
npm http request GET https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/through2
npm http 200 https://registry.npmjs.org/pouchdb-merge
npm http fetch GET https://registry.npmjs.org/pouchdb-merge/-/pouchdb-merge-5.4.4.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-merge/-/pouchdb-merge-5.4.4.tgz
npm http 200 https://registry.npmjs.org/pouchdb-json
npm http 200 https://registry.npmjs.org/pouchdb-adapter-utils
npm http fetch GET https://registry.npmjs.org/pouchdb-json/-/pouchdb-json-5.4.4.tgz
npm http fetch GET https://registry.npmjs.org/pouchdb-adapter-utils/-/pouchdb-adapter-utils-5.4.4.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-json/-/pouchdb-json-5.4.4.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-adapter-utils/-/pouchdb-adapter-utils-5.4.4.tgz
npm http request GET https://registry.npmjs.org/pouchdb-mapreduce-utils
npm http 200 https://registry.npmjs.org/pouchdb-mapreduce-utils
npm http fetch GET https://registry.npmjs.org/pouchdb-mapreduce-utils/-/pouchdb-mapreduce-utils-5.4.4.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-mapreduce-utils/-/pouchdb-mapreduce-utils-5.4.4.tgz
npm http request GET https://registry.npmjs.org/pouchdb-checkpointer
npm http request GET https://registry.npmjs.org/pouchdb-generate-replication-id
npm http 200 https://registry.npmjs.org/pouchdb-checkpointer
npm http fetch GET https://registry.npmjs.org/pouchdb-checkpointer/-/pouchdb-checkpointer-5.4.4.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-checkpointer/-/pouchdb-checkpointer-5.4.4.tgz
npm http 200 https://registry.npmjs.org/pouchdb-generate-replication-id
npm http fetch GET https://registry.npmjs.org/pouchdb-generate-replication-id/-/pouchdb-generate-replication-id-5.4.4.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-generate-replication-id/-/pouchdb-generate-replication-id-5.4.4.tgz
npm http request GET https://registry.npmjs.org/module-not-found-error
npm http request GET https://registry.npmjs.org/fill-keys
npm http 304 https://registry.npmjs.org/fill-keys
npm http 304 https://registry.npmjs.org/module-not-found-error
npm http request GET https://registry.npmjs.org/is-object
npm http 200 https://registry.npmjs.org/is-object
npm http request GET https://registry.npmjs.org/array-uniq
npm http 200 https://registry.npmjs.org/array-uniq
npm http request GET https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/lodash
npm http 304 https://registry.npmjs.org/lodash
npm http 304 https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/formatio
npm http request GET https://registry.npmjs.org/lolex
npm http request GET https://registry.npmjs.org/util
npm http request GET https://registry.npmjs.org/samsam
npm http 304 https://registry.npmjs.org/formatio
npm http 304 https://registry.npmjs.org/samsam
npm http 200 https://registry.npmjs.org/util
npm http 200 https://registry.npmjs.org/lolex
npm http request GET https://registry.npmjs.org/engine.io-client
npm http request GET https://registry.npmjs.org/component-bind
npm http request GET https://registry.npmjs.org/component-emitter
npm http request GET https://registry.npmjs.org/object-component
npm http request GET https://registry.npmjs.org/socket.io-parser
npm http request GET https://registry.npmjs.org/has-binary
npm http request GET https://registry.npmjs.org/indexof
npm http request GET https://registry.npmjs.org/parseuri
npm http request GET https://registry.npmjs.org/to-array
npm http request GET https://registry.npmjs.org/backo2
npm http request GET https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/engine.io-client
npm http 304 https://registry.npmjs.org/component-bind
npm http 304 https://registry.npmjs.org/component-emitter
npm http 304 https://registry.npmjs.org/object-component
npm http 304 https://registry.npmjs.org/socket.io-parser
npm http 304 https://registry.npmjs.org/has-binary
npm http 304 https://registry.npmjs.org/indexof
npm http 304 https://registry.npmjs.org/parseuri
npm http 304 https://registry.npmjs.org/to-array
npm http 304 https://registry.npmjs.org/backo2
npm http 304 https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/component-inherit
npm http request GET https://registry.npmjs.org/engine.io-parser
npm http request GET https://registry.npmjs.org/has-cors
npm http request GET https://registry.npmjs.org/parsejson
npm http request GET https://registry.npmjs.org/parseqs
npm http request GET https://registry.npmjs.org/ws
npm http fetch GET https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http 304 https://registry.npmjs.org/component-inherit
npm http 304 https://registry.npmjs.org/engine.io-parser
npm http 304 https://registry.npmjs.org/parsejson
npm http 304 https://registry.npmjs.org/has-cors
npm http 304 https://registry.npmjs.org/parseqs
npm http 304 https://registry.npmjs.org/ws
npm http fetch 200 https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http request GET https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/arraybuffer.slice
npm http request GET https://registry.npmjs.org/base64-arraybuffer
npm http request GET https://registry.npmjs.org/blob
npm http request GET https://registry.npmjs.org/utf8
npm http 304 https://registry.npmjs.org/arraybuffer.slice
npm http 304 https://registry.npmjs.org/base64-arraybuffer
npm http 304 https://registry.npmjs.org/blob
npm http 304 https://registry.npmjs.org/utf8
npm http fetch GET https://github.com/component/global/archive/v2.0.1.tar.gz
npm http fetch 200 https://github.com/component/global/archive/v2.0.1.tar.gz
npm http request GET https://registry.npmjs.org/better-assert
npm http 304 https://registry.npmjs.org/better-assert
npm http request GET https://registry.npmjs.org/callsite
npm http 304 https://registry.npmjs.org/callsite
npm http request GET https://registry.npmjs.org/options
npm http request GET https://registry.npmjs.org/ultron
npm http 304 https://registry.npmjs.org/options
npm http 304 https://registry.npmjs.org/ultron
npm http request GET https://registry.npmjs.org/json3
npm http request GET https://registry.npmjs.org/benchmark
npm http 304 https://registry.npmjs.org/benchmark
npm http 304 https://registry.npmjs.org/json3
npm http request GET https://registry.npmjs.org/superagent
npm http 200 https://registry.npmjs.org/superagent
npm http fetch GET https://registry.npmjs.org/superagent/-/superagent-1.3.0.tgz
npm http fetch 200 https://registry.npmjs.org/superagent/-/superagent-1.3.0.tgz
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/methods
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/form-data
npm http request GET https://registry.npmjs.org/formidable
npm http request GET https://registry.npmjs.org/cookiejar
npm http request GET https://registry.npmjs.org/reduce-component
npm http 304 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/qs
npm http 200 https://registry.npmjs.org/methods
npm http 200 https://registry.npmjs.org/formidable
npm http fetch GET https://registry.npmjs.org/form-data/-/form-data-0.2.0.tgz
npm http fetch GET https://registry.npmjs.org/extend/-/extend-1.2.1.tgz
npm http fetch GET https://registry.npmjs.org/methods/-/methods-1.0.1.tgz
npm http 304 https://registry.npmjs.org/reduce-component
npm http 200 https://registry.npmjs.org/cookiejar
npm http fetch GET https://registry.npmjs.org/formidable/-/formidable-1.0.14.tgz
npm http fetch GET https://registry.npmjs.org/cookiejar/-/cookiejar-2.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/form-data/-/form-data-0.2.0.tgz
npm http fetch 200 https://registry.npmjs.org/extend/-/extend-1.2.1.tgz
npm http fetch 200 https://registry.npmjs.org/methods/-/methods-1.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/formidable/-/formidable-1.0.14.tgz
npm http fetch 200 https://registry.npmjs.org/cookiejar/-/cookiejar-2.0.1.tgz
npm http request GET https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/combined-stream
npm http request GET https://registry.npmjs.org/mime-types
npm http 304 https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/mime-types
npm http request GET https://registry.npmjs.org/delayed-stream
npm http 304 https://registry.npmjs.org/delayed-stream
npm http request GET https://registry.npmjs.org/mime-db
npm http 304 https://registry.npmjs.org/mime-db
npm http request GET https://registry.npmjs.org/defined
npm http request GET https://registry.npmjs.org/resumer
npm http request GET https://registry.npmjs.org/object-inspect
npm http 200 https://registry.npmjs.org/defined
npm http 304 https://registry.npmjs.org/resumer
npm http 200 https://registry.npmjs.org/object-inspect
npm http fetch GET https://registry.npmjs.org/object-inspect/-/object-inspect-1.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/object-inspect/-/object-inspect-1.0.2.tgz
npm WARN prefer global jshint@2.9.2 should be installed with -g
npm WARN prefer global node-ninja@1.0.1 should be installed with -g
npm WARN prefer global node-gyp@3.3.1 should be installed with -g
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
Trace: [Error: Missing PFX or certificate + private key.]
    at process.tests (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/thaliTape.js:38:11)
    at process.emit (events.js:98:20)
    at Array.0 (/Users/thali/Github/Thali_CordovaPlugin/thali/node_modules/lie/lib/index.js:128:19)
    at nextTick (/Users/thali/Github/Thali_CordovaPlugin/thali/node_modules/immediate/lib/index.js:61:18)
    at process._tickCallback (node.js:917:13)
npm ERR! Test failed.  See above for more details.

```

Error: Command failed: npm http request GET https://registry.npmjs.org/fs-extra-promise
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/express
npm http request GET https://registry.npmjs.org/socket.io
npm http request GET https://registry.npmjs.org/winston
npm http 200 https://registry.npmjs.org/winston
npm http 200 https://registry.npmjs.org/socket.io
npm http 200 https://registry.npmjs.org/fs-extra-promise
npm http 200 https://registry.npmjs.org/lie
npm http fetch GET https://registry.npmjs.org/socket.io/-/socket.io-1.3.6.tgz
npm http fetch GET https://registry.npmjs.org/fs-extra-promise/-/fs-extra-promise-0.2.0.tgz
npm http fetch GET https://registry.npmjs.org/lie/-/lie-3.0.4.tgz
npm http 200 https://registry.npmjs.org/express
npm http fetch 200 https://registry.npmjs.org/lie/-/lie-3.0.4.tgz
npm http fetch 200 https://registry.npmjs.org/fs-extra-promise/-/fs-extra-promise-0.2.0.tgz
npm http fetch 200 https://registry.npmjs.org/socket.io/-/socket.io-1.3.6.tgz
npm http request GET https://registry.npmjs.org/content-type
npm http request GET https://registry.npmjs.org/content-disposition
npm http request GET https://registry.npmjs.org/accepts
npm http request GET https://registry.npmjs.org/array-flatten
npm http request GET https://registry.npmjs.org/cookie
npm http request GET https://registry.npmjs.org/cookie-signature
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/etag
npm http request GET https://registry.npmjs.org/depd
npm http request GET https://registry.npmjs.org/escape-html
npm http request GET https://registry.npmjs.org/finalhandler
npm http request GET https://registry.npmjs.org/fresh
npm http request GET https://registry.npmjs.org/merge-descriptors
npm http request GET https://registry.npmjs.org/methods
npm http request GET https://registry.npmjs.org/on-finished
npm http request GET https://registry.npmjs.org/parseurl
npm http request GET https://registry.npmjs.org/proxy-addr
npm http request GET https://registry.npmjs.org/path-to-regexp
npm http request GET https://registry.npmjs.org/send
npm http request GET https://registry.npmjs.org/vary
npm http request GET https://registry.npmjs.org/utils-merge
npm http request GET https://registry.npmjs.org/type-is
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/range-parser
npm http request GET https://registry.npmjs.org/serve-static
npm http 200 https://registry.npmjs.org/content-type
npm http 304 https://registry.npmjs.org/content-disposition
npm http 200 https://registry.npmjs.org/array-flatten
npm http 200 https://registry.npmjs.org/cookie
npm http 200 https://registry.npmjs.org/accepts
npm http fetch GET https://registry.npmjs.org/content-type/-/content-type-1.0.2.tgz
npm http 200 https://registry.npmjs.org/cookie-signature
npm http 200 https://registry.npmjs.org/etag
npm http 200 https://registry.npmjs.org/debug
npm http 200 https://registry.npmjs.org/depd
npm http 200 https://registry.npmjs.org/escape-html
npm http 304 https://registry.npmjs.org/fresh
npm http 304 https://registry.npmjs.org/methods
npm http 304 https://registry.npmjs.org/on-finished
npm http 200 https://registry.npmjs.org/merge-descriptors
npm http 200 https://registry.npmjs.org/finalhandler
npm http 200 https://registry.npmjs.org/parseurl
npm http 304 https://registry.npmjs.org/vary
npm http 200 https://registry.npmjs.org/proxy-addr
npm http 200 https://registry.npmjs.org/path-to-regexp
npm http 200 https://registry.npmjs.org/send
npm http 200 https://registry.npmjs.org/utils-merge
npm http 200 https://registry.npmjs.org/range-parser
npm http 200 https://registry.npmjs.org/type-is
npm http 200 https://registry.npmjs.org/qs
npm http fetch 200 https://registry.npmjs.org/content-type/-/content-type-1.0.2.tgz
npm http 200 https://registry.npmjs.org/serve-static
npm http fetch GET https://registry.npmjs.org/type-is/-/type-is-1.6.13.tgz
npm http fetch GET https://registry.npmjs.org/serve-static/-/serve-static-1.10.3.tgz
npm http fetch 200 https://registry.npmjs.org/type-is/-/type-is-1.6.13.tgz
npm http fetch 200 https://registry.npmjs.org/serve-static/-/serve-static-1.10.3.tgz
npm http request GET https://registry.npmjs.org/mime-types
npm http request GET https://registry.npmjs.org/negotiator
npm http 200 https://registry.npmjs.org/mime-types
npm http 200 https://registry.npmjs.org/negotiator
npm http fetch GET https://registry.npmjs.org/mime-types/-/mime-types-2.1.11.tgz
npm http fetch 200 https://registry.npmjs.org/mime-types/-/mime-types-2.1.11.tgz
npm http request GET https://registry.npmjs.org/mime-db
npm http 200 https://registry.npmjs.org/mime-db
npm http fetch GET https://registry.npmjs.org/mime-db/-/mime-db-1.23.0.tgz
npm http fetch 200 https://registry.npmjs.org/mime-db/-/mime-db-1.23.0.tgz
npm http request GET https://registry.npmjs.org/ms
npm http 200 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/unpipe
npm http 304 https://registry.npmjs.org/unpipe
npm http request GET https://registry.npmjs.org/ee-first
npm http 304 https://registry.npmjs.org/ee-first
npm http request GET https://registry.npmjs.org/forwarded
npm http request GET https://registry.npmjs.org/ipaddr.js
npm http 304 https://registry.npmjs.org/forwarded
npm http 200 https://registry.npmjs.org/ipaddr.js
npm http request GET https://registry.npmjs.org/destroy
npm http request GET https://registry.npmjs.org/http-errors
npm http request GET https://registry.npmjs.org/mime
npm http request GET https://registry.npmjs.org/statuses
npm http 304 https://registry.npmjs.org/destroy
npm http 200 https://registry.npmjs.org/http-errors
npm http 200 https://registry.npmjs.org/mime
npm http 200 https://registry.npmjs.org/statuses
npm http request GET https://registry.npmjs.org/inherits
npm http 200 https://registry.npmjs.org/inherits
npm http fetch GET https://registry.npmjs.org/send/-/send-0.13.2.tgz
npm http fetch 200 https://registry.npmjs.org/send/-/send-0.13.2.tgz
npm http request GET https://registry.npmjs.org/media-typer
npm http 304 https://registry.npmjs.org/media-typer
npm http request GET https://registry.npmjs.org/fs-extra
npm http request GET https://registry.npmjs.org/bluebird
npm http 200 https://registry.npmjs.org/fs-extra
npm http fetch GET https://registry.npmjs.org/fs-extra/-/fs-extra-0.21.0.tgz
npm http 200 https://registry.npmjs.org/bluebird
npm http fetch 200 https://registry.npmjs.org/fs-extra/-/fs-extra-0.21.0.tgz
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/jsonfile
npm http request GET https://registry.npmjs.org/rimraf
npm http 200 https://registry.npmjs.org/jsonfile
npm http 200 https://registry.npmjs.org/rimraf
npm http 200 https://registry.npmjs.org/graceful-fs
npm http fetch GET https://registry.npmjs.org/jsonfile/-/jsonfile-2.3.1.tgz
npm http fetch GET https://registry.npmjs.org/graceful-fs/-/graceful-fs-4.1.4.tgz
npm http fetch 200 https://registry.npmjs.org/graceful-fs/-/graceful-fs-4.1.4.tgz
npm http fetch 200 https://registry.npmjs.org/jsonfile/-/jsonfile-2.3.1.tgz
npm http request GET https://registry.npmjs.org/glob
npm http 200 https://registry.npmjs.org/glob
npm http fetch GET https://registry.npmjs.org/glob/-/glob-7.0.5.tgz
npm http fetch 200 https://registry.npmjs.org/glob/-/glob-7.0.5.tgz
npm http request GET https://registry.npmjs.org/fs.realpath
npm http request GET https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/once
npm http request GET https://registry.npmjs.org/path-is-absolute
npm http 200 https://registry.npmjs.org/fs.realpath
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http 200 https://registry.npmjs.org/inflight
npm http 304 https://registry.npmjs.org/once
npm http 200 https://registry.npmjs.org/minimatch
npm http fetch GET https://registry.npmjs.org/fs.realpath/-/fs.realpath-1.0.0.tgz
npm http fetch GET https://registry.npmjs.org/inflight/-/inflight-1.0.5.tgz
npm http fetch GET https://registry.npmjs.org/minimatch/-/minimatch-3.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/inflight/-/inflight-1.0.5.tgz
npm http fetch 200 https://registry.npmjs.org/fs.realpath/-/fs.realpath-1.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/minimatch/-/minimatch-3.0.2.tgz
npm http request GET https://registry.npmjs.org/wrappy
npm http 200 https://registry.npmjs.org/wrappy
npm http fetch GET https://registry.npmjs.org/wrappy/-/wrappy-1.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/wrappy/-/wrappy-1.0.2.tgz
npm http request GET https://registry.npmjs.org/brace-expansion
npm http 200 https://registry.npmjs.org/brace-expansion
npm http fetch GET https://registry.npmjs.org/brace-expansion/-/brace-expansion-1.1.5.tgz
npm http fetch 200 https://registry.npmjs.org/brace-expansion/-/brace-expansion-1.1.5.tgz
npm http request GET https://registry.npmjs.org/balanced-match
npm http request GET https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/concat-map
npm http 200 https://registry.npmjs.org/balanced-match
npm http fetch GET https://registry.npmjs.org/balanced-match/-/balanced-match-0.4.1.tgz
npm http fetch 200 https://registry.npmjs.org/balanced-match/-/balanced-match-0.4.1.tgz
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http request GET https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/immediate
npm http 200 https://registry.npmjs.org/es3ify
npm http fetch GET https://registry.npmjs.org/es3ify/-/es3ify-0.2.2.tgz
npm http 304 https://registry.npmjs.org/immediate
npm http 200 https://registry.npmjs.org/unreachable-branch-transform
npm http 200 https://registry.npmjs.org/inline-process-browser
npm http fetch 200 https://registry.npmjs.org/es3ify/-/es3ify-0.2.2.tgz
npm http request GET https://registry.npmjs.org/jstransform
npm http request GET https://registry.npmjs.org/esprima
npm http request GET https://registry.npmjs.org/through
npm http 200 https://registry.npmjs.org/through
npm http 200 https://registry.npmjs.org/esprima
npm http 304 https://registry.npmjs.org/jstransform
npm http fetch GET https://registry.npmjs.org/jstransform/-/jstransform-11.0.3.tgz
npm http fetch 200 https://registry.npmjs.org/jstransform/-/jstransform-11.0.3.tgz
npm http request GET https://registry.npmjs.org/commoner
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/object-assign
npm http request GET https://registry.npmjs.org/source-map
npm http 200 https://registry.npmjs.org/commoner
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 200 https://registry.npmjs.org/object-assign
npm http 200 https://registry.npmjs.org/base62
npm http fetch GET https://registry.npmjs.org/esprima-fb/-/esprima-fb-15001.1.0-dev-harmony-fb.tgz
npm http fetch GET https://registry.npmjs.org/commoner/-/commoner-0.10.4.tgz
npm http fetch GET https://registry.npmjs.org/object-assign/-/object-assign-2.1.1.tgz
npm http fetch GET https://registry.npmjs.org/base62/-/base62-1.1.1.tgz
npm http 200 https://registry.npmjs.org/source-map
npm http fetch 200 https://registry.npmjs.org/esprima-fb/-/esprima-fb-15001.1.0-dev-harmony-fb.tgz
npm http fetch 200 https://registry.npmjs.org/commoner/-/commoner-0.10.4.tgz
npm http fetch 200 https://registry.npmjs.org/base62/-/base62-1.1.1.tgz
npm http fetch 200 https://registry.npmjs.org/object-assign/-/object-assign-2.1.1.tgz
npm http request GET https://registry.npmjs.org/detective
npm http request GET https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/iconv-lite
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/mkdirp
npm http request GET https://registry.npmjs.org/q
npm http request GET https://registry.npmjs.org/recast
npm http 200 https://registry.npmjs.org/detective
npm http 304 https://registry.npmjs.org/private
npm http 200 https://registry.npmjs.org/mkdirp
npm http 200 https://registry.npmjs.org/iconv-lite
npm http 200 https://registry.npmjs.org/commander
npm http 200 https://registry.npmjs.org/q
npm http 200 https://registry.npmjs.org/recast
npm http request GET https://registry.npmjs.org/graceful-readlink
npm http 304 https://registry.npmjs.org/graceful-readlink
npm http request GET https://registry.npmjs.org/defined
npm http request GET https://registry.npmjs.org/acorn
npm http 200 https://registry.npmjs.org/defined
npm http 200 https://registry.npmjs.org/acorn
npm http request GET https://registry.npmjs.org/minimist
npm http 200 https://registry.npmjs.org/minimist
npm http request GET https://registry.npmjs.org/ast-types
npm http fetch GET https://registry.npmjs.org/source-map/-/source-map-0.5.6.tgz
npm http fetch 200 https://registry.npmjs.org/source-map/-/source-map-0.5.6.tgz
npm http 200 https://registry.npmjs.org/ast-types
npm http request GET https://registry.npmjs.org/amdefine
npm http 304 https://registry.npmjs.org/amdefine
npm http request GET https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/falafel
npm http 200 https://registry.npmjs.org/through2
npm http request GET https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/foreach
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/object-keys
npm http request GET https://registry.npmjs.org/xtend
npm http request GET https://registry.npmjs.org/readable-stream
npm http 200 https://registry.npmjs.org/readable-stream
npm http 200 https://registry.npmjs.org/xtend
npm http fetch GET https://registry.npmjs.org/readable-stream/-/readable-stream-1.0.34.tgz
npm http fetch 200 https://registry.npmjs.org/readable-stream/-/readable-stream-1.0.34.tgz
npm http request GET https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/core-util-is
npm http 304 https://registry.npmjs.org/string_decoder
npm http request GET https://registry.npmjs.org/esmangle-evaluator
npm http 200 https://registry.npmjs.org/esmangle-evaluator
npm http fetch GET https://registry.npmjs.org/esmangle-evaluator/-/esmangle-evaluator-1.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/esmangle-evaluator/-/esmangle-evaluator-1.0.1.tgz
npm http request GET https://registry.npmjs.org/has-binary-data
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/socket.io-adapter
npm http request GET https://registry.npmjs.org/socket.io-parser
npm http request GET https://registry.npmjs.org/socket.io-client
npm http request GET https://registry.npmjs.org/engine.io
npm http 304 https://registry.npmjs.org/socket.io-adapter
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/socket.io-parser
npm http 200 https://registry.npmjs.org/socket.io-client
npm http fetch GET https://registry.npmjs.org/debug/-/debug-2.1.0.tgz
npm http fetch GET https://registry.npmjs.org/socket.io-adapter/-/socket.io-adapter-0.3.1.tgz
npm http fetch GET https://registry.npmjs.org/socket.io-parser/-/socket.io-parser-2.2.4.tgz
npm http fetch GET https://registry.npmjs.org/socket.io-client/-/socket.io-client-1.3.6.tgz
npm http 200 https://registry.npmjs.org/engine.io
npm http fetch GET https://registry.npmjs.org/engine.io/-/engine.io-1.5.2.tgz
npm http fetch 200 https://registry.npmjs.org/socket.io-client/-/socket.io-client-1.3.6.tgz
npm http fetch 200 https://registry.npmjs.org/debug/-/debug-2.1.0.tgz
npm http fetch 200 https://registry.npmjs.org/socket.io-adapter/-/socket.io-adapter-0.3.1.tgz
npm http fetch 200 https://registry.npmjs.org/engine.io/-/engine.io-1.5.2.tgz
npm http fetch 200 https://registry.npmjs.org/socket.io-parser/-/socket.io-parser-2.2.4.tgz
npm http 200 https://registry.npmjs.org/has-binary-data
npm http fetch GET https://registry.npmjs.org/has-binary-data/-/has-binary-data-0.1.3.tgz
npm http fetch 200 https://registry.npmjs.org/has-binary-data/-/has-binary-data-0.1.3.tgz
npm http request GET https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/base64id
npm http request GET https://registry.npmjs.org/engine.io-parser
npm http request GET https://registry.npmjs.org/ws
npm http fetch GET https://registry.npmjs.org/debug/-/debug-1.0.3.tgz
npm http 304 https://registry.npmjs.org/base64id
npm http 200 https://registry.npmjs.org/ws
npm http 304 https://registry.npmjs.org/engine.io-parser
npm http fetch 200 https://registry.npmjs.org/debug/-/debug-1.0.3.tgz
npm http fetch GET https://registry.npmjs.org/ws/-/ws-0.7.2.tgz
npm http fetch GET https://registry.npmjs.org/engine.io-parser/-/engine.io-parser-1.2.1.tgz
npm http fetch 200 https://registry.npmjs.org/engine.io-parser/-/engine.io-parser-1.2.1.tgz
npm http fetch 200 https://registry.npmjs.org/ws/-/ws-0.7.2.tgz
npm http request GET https://registry.npmjs.org/blob
npm http request GET https://registry.npmjs.org/has-binary
npm http request GET https://registry.npmjs.org/base64-arraybuffer
npm http request GET https://registry.npmjs.org/arraybuffer.slice
npm http request GET https://registry.npmjs.org/after
npm http request GET https://registry.npmjs.org/utf8
npm http 304 https://registry.npmjs.org/base64-arraybuffer
npm http 304 https://registry.npmjs.org/has-binary
npm http 304 https://registry.npmjs.org/after
npm http 304 https://registry.npmjs.org/arraybuffer.slice
npm http 200 https://registry.npmjs.org/blob
npm http 304 https://registry.npmjs.org/utf8
npm http fetch GET https://registry.npmjs.org/has-binary/-/has-binary-0.1.5.tgz
npm http fetch GET https://registry.npmjs.org/blob/-/blob-0.0.2.tgz
npm http fetch GET https://registry.npmjs.org/utf8/-/utf8-2.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/blob/-/blob-0.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/has-binary/-/has-binary-0.1.5.tgz
npm http fetch 200 https://registry.npmjs.org/utf8/-/utf8-2.0.0.tgz
npm http request GET https://registry.npmjs.org/bufferutil
npm http request GET https://registry.npmjs.org/utf-8-validate
npm http request GET https://registry.npmjs.org/options
npm http request GET https://registry.npmjs.org/ultron
npm http 200 https://registry.npmjs.org/bufferutil
npm http 304 https://registry.npmjs.org/options
npm http 200 https://registry.npmjs.org/ultron
npm http 200 https://registry.npmjs.org/utf-8-validate
npm http fetch GET https://registry.npmjs.org/bufferutil/-/bufferutil-1.1.0.tgz
npm http fetch GET https://registry.npmjs.org/utf-8-validate/-/utf-8-validate-1.1.0.tgz
npm http fetch 200 https://registry.npmjs.org/bufferutil/-/bufferutil-1.1.0.tgz
npm http fetch 200 https://registry.npmjs.org/utf-8-validate/-/utf-8-validate-1.1.0.tgz
npm http request GET https://registry.npmjs.org/bindings
npm http request GET https://registry.npmjs.org/nan
npm http 200 https://registry.npmjs.org/bindings
npm http 200 https://registry.npmjs.org/nan
npm http fetch GET https://registry.npmjs.org/nan/-/nan-1.8.4.tgz
npm http fetch 200 https://registry.npmjs.org/nan/-/nan-1.8.4.tgz
npm http fetch GET https://registry.npmjs.org/debug/-/debug-1.0.2.tgz
npm http fetch GET https://registry.npmjs.org/object-keys/-/object-keys-1.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/debug/-/debug-1.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/object-keys/-/object-keys-1.0.1.tgz
npm http request GET https://registry.npmjs.org/component-emitter
npm http request GET https://registry.npmjs.org/benchmark
npm http request GET https://registry.npmjs.org/json3
npm http 200 https://registry.npmjs.org/component-emitter
npm http 304 https://registry.npmjs.org/json3
npm http 200 https://registry.npmjs.org/benchmark
npm http request GET https://registry.npmjs.org/component-bind
npm http request GET https://registry.npmjs.org/indexof
npm http request GET https://registry.npmjs.org/object-component
npm http request GET https://registry.npmjs.org/to-array
npm http request GET https://registry.npmjs.org/backo2
npm http request GET https://registry.npmjs.org/parseuri
npm http request GET https://registry.npmjs.org/engine.io-client
npm http 304 https://registry.npmjs.org/component-bind
npm http 304 https://registry.npmjs.org/indexof
npm http 304 https://registry.npmjs.org/object-component
npm http 304 https://registry.npmjs.org/to-array
npm http 304 https://registry.npmjs.org/backo2
npm http fetch GET https://registry.npmjs.org/to-array/-/to-array-0.1.3.tgz
npm http 304 https://registry.npmjs.org/parseuri
npm http fetch GET https://registry.npmjs.org/parseuri/-/parseuri-0.0.2.tgz
npm http 200 https://registry.npmjs.org/engine.io-client
npm http fetch GET https://registry.npmjs.org/engine.io-client/-/engine.io-client-1.5.2.tgz
npm http fetch 200 https://registry.npmjs.org/to-array/-/to-array-0.1.3.tgz
npm http fetch 200 https://registry.npmjs.org/parseuri/-/parseuri-0.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/engine.io-client/-/engine.io-client-1.5.2.tgz
npm http request GET https://registry.npmjs.org/component-inherit
npm http request GET https://registry.npmjs.org/has-cors
npm http request GET https://registry.npmjs.org/parsejson
npm http request GET https://registry.npmjs.org/parseqs
npm http fetch GET https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http 304 https://registry.npmjs.org/component-inherit
npm http 304 https://registry.npmjs.org/has-cors
npm http 304 https://registry.npmjs.org/parseqs
npm http fetch GET https://registry.npmjs.org/has-cors/-/has-cors-1.0.3.tgz
npm http 304 https://registry.npmjs.org/parsejson
npm http fetch 200 https://registry.npmjs.org/has-cors/-/has-cors-1.0.3.tgz
npm http fetch 200 https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http fetch GET https://github.com/component/global/archive/v2.0.1.tar.gz
npm http fetch 200 https://github.com/component/global/archive/v2.0.1.tar.gz
npm http request GET https://registry.npmjs.org/better-assert
npm http 200 https://registry.npmjs.org/better-assert
npm http request GET https://registry.npmjs.org/callsite
npm http 304 https://registry.npmjs.org/callsite
npm http request GET https://registry.npmjs.org/stack-trace
npm http request GET https://registry.npmjs.org/pkginfo
npm http request GET https://registry.npmjs.org/isstream
npm http request GET https://registry.npmjs.org/eyes
npm http request GET https://registry.npmjs.org/cycle
npm http request GET https://registry.npmjs.org/colors
npm http request GET https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/stack-trace
npm http 304 https://registry.npmjs.org/cycle
npm http 200 https://registry.npmjs.org/isstream
npm http 200 https://registry.npmjs.org/eyes
npm http 200 https://registry.npmjs.org/colors
npm http 200 https://registry.npmjs.org/async
npm http 200 https://registry.npmjs.org/pkginfo
npm http request GET https://registry.npmjs.org/node-uuid
npm http request GET https://registry.npmjs.org/tape
npm http 200 https://registry.npmjs.org/node-uuid
npm http 200 https://registry.npmjs.org/tape
npm http request GET https://registry.npmjs.org/defined
npm http request GET https://registry.npmjs.org/jsonify
npm http request GET https://registry.npmjs.org/deep-equal
npm http 304 https://registry.npmjs.org/defined
npm http 200 https://registry.npmjs.org/deep-equal
npm http 304 https://registry.npmjs.org/jsonify
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
npm http request GET https://registry.npmjs.org/salti
npm http request GET https://registry.npmjs.org/express
npm http request GET https://registry.npmjs.org/body-parser
npm http request GET https://registry.npmjs.org/forever-agent
npm http request GET https://registry.npmjs.org/express-pouchdb
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/javascript-state-machine
npm http request GET https://registry.npmjs.org/ip
npm http request GET https://registry.npmjs.org/node-uuid
npm http request GET https://registry.npmjs.org/long
npm http request GET https://registry.npmjs.org/multiplex
npm http request GET https://registry.npmjs.org/winston
npm http request GET https://registry.npmjs.org/request
npm http request GET https://registry.npmjs.org/urlsafe-base64
npm http 304 https://registry.npmjs.org/express
npm http 304 https://registry.npmjs.org/forever-agent
npm http 200 https://registry.npmjs.org/body-parser
npm http 200 https://registry.npmjs.org/ip
npm http 304 https://registry.npmjs.org/node-uuid
npm http 200 https://registry.npmjs.org/salti
npm http fetch GET https://registry.npmjs.org/ip/-/ip-1.0.1.tgz
npm http 200 https://registry.npmjs.org/long
npm http fetch GET https://registry.npmjs.org/body-parser/-/body-parser-1.13.3.tgz
npm http fetch GET https://registry.npmjs.org/salti/-/salti-0.2.0.tgz
npm http 200 https://registry.npmjs.org/winston
npm http 200 https://registry.npmjs.org/request
npm http fetch GET https://registry.npmjs.org/request/-/request-2.64.0.tgz
npm http 200 https://registry.npmjs.org/express-pouchdb
npm http fetch GET https://registry.npmjs.org/express-pouchdb/-/express-pouchdb-1.0.4.tgz
npm http 304 https://registry.npmjs.org/lie
npm http fetch 200 https://registry.npmjs.org/body-parser/-/body-parser-1.13.3.tgz
npm http fetch 200 https://registry.npmjs.org/ip/-/ip-1.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/request/-/request-2.64.0.tgz
npm http fetch 200 https://registry.npmjs.org/salti/-/salti-0.2.0.tgz
npm http fetch 200 https://registry.npmjs.org/express-pouchdb/-/express-pouchdb-1.0.4.tgz
npm http 200 https://registry.npmjs.org/javascript-state-machine
npm http 304 https://registry.npmjs.org/multiplex
npm http 304 https://registry.npmjs.org/urlsafe-base64
npm http request GET https://registry.npmjs.org/content-type
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/depd
npm http request GET https://registry.npmjs.org/iconv-lite
npm http request GET https://registry.npmjs.org/bytes
npm http request GET https://registry.npmjs.org/http-errors
npm http request GET https://registry.npmjs.org/on-finished
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/type-is
npm http request GET https://registry.npmjs.org/raw-body
npm http 304 https://registry.npmjs.org/content-type
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/depd
npm http 200 https://registry.npmjs.org/bytes
npm http 200 https://registry.npmjs.org/iconv-lite
npm http 304 https://registry.npmjs.org/on-finished
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/type-is
npm http 200 https://registry.npmjs.org/http-errors
npm http 200 https://registry.npmjs.org/raw-body
npm http fetch GET https://registry.npmjs.org/bytes/-/bytes-2.1.0.tgz
npm http fetch GET https://registry.npmjs.org/iconv-lite/-/iconv-lite-0.4.11.tgz
npm http fetch GET https://registry.npmjs.org/raw-body/-/raw-body-2.1.7.tgz
npm http fetch 200 https://registry.npmjs.org/bytes/-/bytes-2.1.0.tgz
npm http fetch 200 https://registry.npmjs.org/iconv-lite/-/iconv-lite-0.4.11.tgz
npm http fetch 200 https://registry.npmjs.org/raw-body/-/raw-body-2.1.7.tgz
npm http request GET https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/inherits
npm http request GET https://registry.npmjs.org/statuses
npm http 304 https://registry.npmjs.org/statuses
npm http 304 https://registry.npmjs.org/inherits
npm http fetch GET https://registry.npmjs.org/statuses/-/statuses-1.3.0.tgz
npm http fetch 200 https://registry.npmjs.org/statuses/-/statuses-1.3.0.tgz
npm http request GET https://registry.npmjs.org/ee-first
npm http 304 https://registry.npmjs.org/ee-first
npm http request GET https://registry.npmjs.org/unpipe
npm http fetch GET https://registry.npmjs.org/bytes/-/bytes-2.4.0.tgz
npm http 304 https://registry.npmjs.org/unpipe
npm http fetch 200 https://registry.npmjs.org/bytes/-/bytes-2.4.0.tgz
npm http request GET https://registry.npmjs.org/media-typer
npm http request GET https://registry.npmjs.org/mime-types
npm http 304 https://registry.npmjs.org/media-typer
npm http 304 https://registry.npmjs.org/mime-types
npm http request GET https://registry.npmjs.org/mime-db
npm http 304 https://registry.npmjs.org/mime-db
npm http request GET https://registry.npmjs.org/accepts
npm http request GET https://registry.npmjs.org/array-flatten
npm http request GET https://registry.npmjs.org/content-disposition
npm http request GET https://registry.npmjs.org/cookie
npm http request GET https://registry.npmjs.org/cookie-signature
npm http request GET https://registry.npmjs.org/escape-html
npm http request GET https://registry.npmjs.org/etag
npm http request GET https://registry.npmjs.org/finalhandler
npm http request GET https://registry.npmjs.org/fresh
npm http request GET https://registry.npmjs.org/merge-descriptors
npm http request GET https://registry.npmjs.org/methods
npm http request GET https://registry.npmjs.org/parseurl
npm http request GET https://registry.npmjs.org/path-to-regexp
npm http request GET https://registry.npmjs.org/proxy-addr
npm http request GET https://registry.npmjs.org/range-parser
npm http request GET https://registry.npmjs.org/send
npm http request GET https://registry.npmjs.org/serve-static
npm http request GET https://registry.npmjs.org/utils-merge
npm http request GET https://registry.npmjs.org/vary
npm http 304 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/content-disposition
npm http 304 https://registry.npmjs.org/cookie
npm http 304 https://registry.npmjs.org/cookie-signature
npm http 304 https://registry.npmjs.org/array-flatten
npm http 304 https://registry.npmjs.org/etag
npm http 200 https://registry.npmjs.org/escape-html
npm http 304 https://registry.npmjs.org/finalhandler
npm http 304 https://registry.npmjs.org/fresh
npm http 304 https://registry.npmjs.org/merge-descriptors
npm http 304 https://registry.npmjs.org/methods
npm http 304 https://registry.npmjs.org/parseurl
npm http 304 https://registry.npmjs.org/path-to-regexp
npm http 304 https://registry.npmjs.org/proxy-addr
npm http 304 https://registry.npmjs.org/range-parser
npm http 304 https://registry.npmjs.org/send
npm http 304 https://registry.npmjs.org/serve-static
npm http 304 https://registry.npmjs.org/utils-merge
npm http 304 https://registry.npmjs.org/vary
npm http request GET https://registry.npmjs.org/negotiator
npm http 304 https://registry.npmjs.org/negotiator
npm http request GET https://registry.npmjs.org/forwarded
npm http request GET https://registry.npmjs.org/ipaddr.js
npm http 304 https://registry.npmjs.org/forwarded
npm http 304 https://registry.npmjs.org/ipaddr.js
npm http request GET https://registry.npmjs.org/destroy
npm http request GET https://registry.npmjs.org/mime
npm http 304 https://registry.npmjs.org/destroy
npm http 304 https://registry.npmjs.org/mime
npm http request GET https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/basic-auth
npm http request GET https://registry.npmjs.org/compression
npm http request GET https://registry.npmjs.org/cookie-parser
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/pouchdb-auth
npm http request GET https://registry.npmjs.org/pouchdb-all-dbs
npm http request GET https://registry.npmjs.org/multiparty
npm http request GET https://registry.npmjs.org/header-case-normalizer
npm http request GET https://registry.npmjs.org/pouchdb-find
npm http request GET https://registry.npmjs.org/pouchdb-list
npm http request GET https://registry.npmjs.org/pouchdb-replicator
npm http request GET https://registry.npmjs.org/pouchdb-rewrite
npm http request GET https://registry.npmjs.org/pouchdb-show
npm http request GET https://registry.npmjs.org/pouchdb-security
npm http request GET https://registry.npmjs.org/pouchdb-size
npm http request GET https://registry.npmjs.org/pouchdb-update
npm http request GET https://registry.npmjs.org/pouchdb-vhost
npm http request GET https://registry.npmjs.org/pouchdb-validation
npm http request GET https://registry.npmjs.org/pouchdb-wrappers
npm http 304 https://registry.npmjs.org/bluebird
npm http 200 https://registry.npmjs.org/basic-auth
npm http 200 https://registry.npmjs.org/extend
npm http 200 https://registry.npmjs.org/cookie-parser
npm http 200 https://registry.npmjs.org/compression
npm http fetch GET https://registry.npmjs.org/bluebird/-/bluebird-3.3.4.tgz
npm http 200 https://registry.npmjs.org/multiparty
npm http 304 https://registry.npmjs.org/header-case-normalizer
npm http 304 https://registry.npmjs.org/pouchdb-list
npm http 304 https://registry.npmjs.org/pouchdb-rewrite
npm http 200 https://registry.npmjs.org/pouchdb-find
npm http 200 https://registry.npmjs.org/pouchdb-auth
npm http 200 https://registry.npmjs.org/pouchdb-all-dbs
npm http fetch GET https://registry.npmjs.org/pouchdb-auth/-/pouchdb-auth-2.1.0.tgz
npm http 304 https://registry.npmjs.org/pouchdb-replicator
npm http 304 https://registry.npmjs.org/pouchdb-size
npm http 304 https://registry.npmjs.org/pouchdb-validation
npm http 304 https://registry.npmjs.org/pouchdb-security
npm http 304 https://registry.npmjs.org/pouchdb-show
npm http fetch 200 https://registry.npmjs.org/bluebird/-/bluebird-3.3.4.tgz
npm http 304 https://registry.npmjs.org/pouchdb-update
npm http fetch 200 https://registry.npmjs.org/pouchdb-auth/-/pouchdb-auth-2.1.0.tgz
npm http 304 https://registry.npmjs.org/pouchdb-wrappers
npm http 304 https://registry.npmjs.org/pouchdb-vhost
npm http request GET https://registry.npmjs.org/compressible
npm http request GET https://registry.npmjs.org/on-headers
npm http fetch GET https://registry.npmjs.org/accepts/-/accepts-1.3.3.tgz
npm http fetch 200 https://registry.npmjs.org/accepts/-/accepts-1.3.3.tgz
npm http 200 https://registry.npmjs.org/compressible
npm http 200 https://registry.npmjs.org/on-headers
npm http fetch GET https://registry.npmjs.org/compressible/-/compressible-2.0.8.tgz
npm http fetch 200 https://registry.npmjs.org/compressible/-/compressible-2.0.8.tgz
npm http fetch GET https://registry.npmjs.org/negotiator/-/negotiator-0.6.1.tgz
npm http fetch 200 https://registry.npmjs.org/negotiator/-/negotiator-0.6.1.tgz
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/stream-counter
npm http 200 https://registry.npmjs.org/readable-stream
npm http fetch GET https://registry.npmjs.org/readable-stream/-/readable-stream-1.1.14.tgz
npm http fetch 200 https://registry.npmjs.org/readable-stream/-/readable-stream-1.1.14.tgz
npm http 304 https://registry.npmjs.org/stream-counter
npm http request GET https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/argsarray
npm http request GET https://registry.npmjs.org/tiny-queue
npm http 304 https://registry.npmjs.org/argsarray
npm http 304 https://registry.npmjs.org/tiny-queue
npm http 304 https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/jstransform
npm http request GET https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 304 https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/jstransform
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/source-map
npm http 200 https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/amdefine
npm http 304 https://registry.npmjs.org/amdefine
npm http request GET https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/immediate
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/acorn
npm http request GET https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/foreach
npm http 304 https://registry.npmjs.org/acorn
npm http 304 https://registry.npmjs.org/object-keys
npm http request GET https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/xtend
npm http request GET https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/ast-types
npm http 304 https://registry.npmjs.org/ast-types
npm http 304 https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/base64url
npm http request GET https://registry.npmjs.org/couchdb-calculate-session-id
npm http request GET https://registry.npmjs.org/crypto-lite
npm http request GET https://registry.npmjs.org/pouchdb-promise
npm http request GET https://registry.npmjs.org/pouchdb-bulkdocs-wrapper
npm http request GET https://registry.npmjs.org/pouchdb-plugin-error
npm http request GET https://registry.npmjs.org/pouchdb
npm http request GET https://registry.npmjs.org/pouchdb-req-http-query
npm http request GET https://registry.npmjs.org/pouchdb-system-db
npm http request GET https://registry.npmjs.org/promise-nodify
npm http request GET https://registry.npmjs.org/secure-random
npm http 304 https://registry.npmjs.org/base64url
npm http 304 https://registry.npmjs.org/pouchdb-bulkdocs-wrapper
npm http 200 https://registry.npmjs.org/pouchdb-promise
npm http fetch GET https://registry.npmjs.org/pouchdb-promise/-/pouchdb-promise-5.4.4.tgz
npm http 304 https://registry.npmjs.org/pouchdb-plugin-error
npm http 200 https://registry.npmjs.org/pouchdb
npm http fetch GET https://registry.npmjs.org/pouchdb/-/pouchdb-5.4.4.tgz
npm http 304 https://registry.npmjs.org/couchdb-calculate-session-id
npm http 304 https://registry.npmjs.org/crypto-lite
npm http fetch 200 https://registry.npmjs.org/pouchdb-promise/-/pouchdb-promise-5.4.4.tgz
npm http 304 https://registry.npmjs.org/pouchdb-req-http-query
npm http fetch 200 https://registry.npmjs.org/pouchdb/-/pouchdb-5.4.4.tgz
npm http 304 https://registry.npmjs.org/pouchdb-system-db
npm http 304 https://registry.npmjs.org/promise-nodify
npm http 304 https://registry.npmjs.org/secure-random
npm http request GET https://registry.npmjs.org/concat-stream
npm http request GET https://registry.npmjs.org/meow
npm http 200 https://registry.npmjs.org/concat-stream
npm http 200 https://registry.npmjs.org/meow
npm http request GET https://registry.npmjs.org/typedarray
npm http 304 https://registry.npmjs.org/typedarray
npm http request GET https://registry.npmjs.org/minimist
npm http request GET https://registry.npmjs.org/object-assign
npm http request GET https://registry.npmjs.org/camelcase-keys
npm http request GET https://registry.npmjs.org/indent-string
npm http 304 https://registry.npmjs.org/minimist
npm http 200 https://registry.npmjs.org/camelcase-keys
npm http 200 https://registry.npmjs.org/indent-string
npm http 304 https://registry.npmjs.org/object-assign
npm http request GET https://registry.npmjs.org/map-obj
npm http request GET https://registry.npmjs.org/camelcase
npm http 200 https://registry.npmjs.org/map-obj
npm http 200 https://registry.npmjs.org/camelcase
npm http request GET https://registry.npmjs.org/get-stdin
npm http request GET https://registry.npmjs.org/repeating
npm http 200 https://registry.npmjs.org/repeating
npm http 200 https://registry.npmjs.org/get-stdin
npm http request GET https://registry.npmjs.org/is-finite
npm http 304 https://registry.npmjs.org/is-finite
npm http request GET https://registry.npmjs.org/number-is-nan
npm http 304 https://registry.npmjs.org/number-is-nan
npm http request GET https://registry.npmjs.org/aproba
npm http 200 https://registry.npmjs.org/aproba
npm http fetch GET https://registry.npmjs.org/aproba/-/aproba-1.0.4.tgz
npm http fetch 200 https://registry.npmjs.org/aproba/-/aproba-1.0.4.tgz
npm http request GET https://registry.npmjs.org/double-ended-queue
npm http request GET https://registry.npmjs.org/fruitdown
npm http request GET https://registry.npmjs.org/js-extend
npm http request GET https://registry.npmjs.org/level-write-stream
npm http request GET https://registry.npmjs.org/pouchdb-collections
npm http request GET https://registry.npmjs.org/levelup
npm http request GET https://registry.npmjs.org/pouchdb-collate
npm http request GET https://registry.npmjs.org/request
npm http request GET https://registry.npmjs.org/sublevel-pouchdb
npm http request GET https://registry.npmjs.org/vuvuzela
npm http request GET https://registry.npmjs.org/spark-md5
npm http request GET https://registry.npmjs.org/scope-eval
npm http request GET https://registry.npmjs.org/memdown
npm http request GET https://registry.npmjs.org/localstorage-down
npm http 304 https://registry.npmjs.org/double-ended-queue
npm http 304 https://registry.npmjs.org/level-write-stream
npm http 304 https://registry.npmjs.org/pouchdb-collections
npm http 304 https://registry.npmjs.org/request
npm http fetch GET https://registry.npmjs.org/request/-/request-2.72.0.tgz
npm http 304 https://registry.npmjs.org/pouchdb-collate
npm http 200 https://registry.npmjs.org/sublevel-pouchdb
npm http fetch GET https://registry.npmjs.org/sublevel-pouchdb/-/sublevel-pouchdb-1.0.1.tgz
npm http 304 https://registry.npmjs.org/js-extend
npm http 304 https://registry.npmjs.org/fruitdown
npm http fetch GET https://registry.npmjs.org/js-extend/-/js-extend-0.0.1.tgz
npm http 200 https://registry.npmjs.org/spark-md5
npm http 200 https://registry.npmjs.org/levelup
npm http fetch GET https://registry.npmjs.org/levelup/-/levelup-1.3.2.tgz
npm http fetch 200 https://registry.npmjs.org/request/-/request-2.72.0.tgz
npm http 304 https://registry.npmjs.org/scope-eval
npm http 200 https://registry.npmjs.org/memdown
npm http fetch 200 https://registry.npmjs.org/sublevel-pouchdb/-/sublevel-pouchdb-1.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/js-extend/-/js-extend-0.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/levelup/-/levelup-1.3.2.tgz
npm http 200 https://registry.npmjs.org/vuvuzela
npm http fetch GET https://registry.npmjs.org/vuvuzela/-/vuvuzela-1.0.3.tgz
npm http 304 https://registry.npmjs.org/localstorage-down
npm http fetch 200 https://registry.npmjs.org/vuvuzela/-/vuvuzela-1.0.3.tgz
npm http request GET https://registry.npmjs.org/tiny-queue
npm http request GET https://registry.npmjs.org/d64
npm http request GET https://registry.npmjs.org/abstract-leveldown
npm http 304 https://registry.npmjs.org/tiny-queue
npm http 304 https://registry.npmjs.org/abstract-leveldown
npm http 304 https://registry.npmjs.org/d64
npm http request GET https://registry.npmjs.org/end-stream
npm http 304 https://registry.npmjs.org/end-stream
npm http request GET https://registry.npmjs.org/write-stream
npm http 304 https://registry.npmjs.org/write-stream
npm http request GET https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/deferred-leveldown
npm http request GET https://registry.npmjs.org/level-errors
npm http request GET https://registry.npmjs.org/level-codec
npm http request GET https://registry.npmjs.org/level-iterator-stream
npm http request GET https://registry.npmjs.org/prr
npm http request GET https://registry.npmjs.org/semver
npm http 304 https://registry.npmjs.org/prr
npm http 200 https://registry.npmjs.org/semver
npm http fetch GET https://registry.npmjs.org/semver/-/semver-5.1.1.tgz
npm http 304 https://registry.npmjs.org/deferred-leveldown
npm http 304 https://registry.npmjs.org/level-errors
npm http 304 https://registry.npmjs.org/level-codec
npm http fetch 200 https://registry.npmjs.org/semver/-/semver-5.1.1.tgz
npm http 304 https://registry.npmjs.org/level-iterator-stream
npm http request GET https://registry.npmjs.org/errno
npm http 304 https://registry.npmjs.org/errno
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/esprima
npm http request GET https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/esprima
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/commoner
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/base62
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 304 https://registry.npmjs.org/commoner
npm http request GET https://registry.npmjs.org/detective
npm http request GET https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/mkdirp
npm http request GET https://registry.npmjs.org/q
npm http 304 https://registry.npmjs.org/detective
npm http 304 https://registry.npmjs.org/commander
npm http 200 https://registry.npmjs.org/mkdirp
npm http 304 https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/graceful-fs
npm http 304 https://registry.npmjs.org/q
npm http request GET https://registry.npmjs.org/graceful-readlink
npm http 304 https://registry.npmjs.org/graceful-readlink
npm http request GET https://registry.npmjs.org/defined
npm http 304 https://registry.npmjs.org/defined
npm http request GET https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/path-is-absolute
npm http request GET https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/inflight
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http 304 https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/wrappy
npm http 304 https://registry.npmjs.org/wrappy
npm http request GET https://registry.npmjs.org/brace-expansion
npm http 304 https://registry.npmjs.org/brace-expansion
npm http request GET https://registry.npmjs.org/balanced-match
npm http request GET https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/balanced-match
npm http 304 https://registry.npmjs.org/concat-map
npm http request GET https://registry.npmjs.org/minimist
npm http 304 https://registry.npmjs.org/minimist
npm http request GET https://registry.npmjs.org/humble-localstorage
npm http 200 https://registry.npmjs.org/humble-localstorage
npm http request GET https://registry.npmjs.org/has-localstorage
npm http request GET https://registry.npmjs.org/localstorage-memory
npm http 304 https://registry.npmjs.org/localstorage-memory
npm http 304 https://registry.npmjs.org/has-localstorage
npm http request GET https://registry.npmjs.org/ltgt
npm http request GET https://registry.npmjs.org/functional-red-black-tree
npm http 304 https://registry.npmjs.org/ltgt
npm http 304 https://registry.npmjs.org/functional-red-black-tree
npm http request GET https://registry.npmjs.org/combined-stream
npm http request GET https://registry.npmjs.org/caseless
npm http request GET https://registry.npmjs.org/aws4
npm http request GET https://registry.npmjs.org/bl
npm http request GET https://registry.npmjs.org/aws-sign2
npm http request GET https://registry.npmjs.org/form-data
npm http request GET https://registry.npmjs.org/har-validator
npm http request GET https://registry.npmjs.org/isstream
npm http request GET https://registry.npmjs.org/oauth-sign
npm http request GET https://registry.npmjs.org/json-stringify-safe
npm http request GET https://registry.npmjs.org/is-typedarray
npm http request GET https://registry.npmjs.org/http-signature
npm http request GET https://registry.npmjs.org/hawk
npm http request GET https://registry.npmjs.org/stringstream
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/tunnel-agent
npm http request GET https://registry.npmjs.org/tough-cookie
npm http 304 https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/aws-sign2
npm http 200 https://registry.npmjs.org/aws4
npm http 304 https://registry.npmjs.org/caseless
npm http 200 https://registry.npmjs.org/bl
npm http fetch GET https://registry.npmjs.org/aws4/-/aws4-1.4.1.tgz
npm http 200 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/isstream
npm http fetch GET https://registry.npmjs.org/bl/-/bl-1.1.2.tgz
npm http 200 https://registry.npmjs.org/oauth-sign
npm http 200 https://registry.npmjs.org/har-validator
npm http 200 https://registry.npmjs.org/json-stringify-safe
npm http 304 https://registry.npmjs.org/is-typedarray
npm http 304 https://registry.npmjs.org/stringstream
npm http fetch GET https://registry.npmjs.org/oauth-sign/-/oauth-sign-0.8.2.tgz
npm http 200 https://registry.npmjs.org/http-signature
npm http 200 https://registry.npmjs.org/extend
npm http 200 https://registry.npmjs.org/hawk
npm http 304 https://registry.npmjs.org/qs
npm http fetch 200 https://registry.npmjs.org/bl/-/bl-1.1.2.tgz
npm http fetch 200 https://registry.npmjs.org/aws4/-/aws4-1.4.1.tgz
npm http 200 https://registry.npmjs.org/tunnel-agent
npm http 200 https://registry.npmjs.org/tough-cookie
npm http fetch 200 https://registry.npmjs.org/oauth-sign/-/oauth-sign-0.8.2.tgz
npm http fetch GET https://registry.npmjs.org/tunnel-agent/-/tunnel-agent-0.4.3.tgz
npm http fetch 200 https://registry.npmjs.org/tunnel-agent/-/tunnel-agent-0.4.3.tgz
npm http request GET https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/process-nextick-args
npm http request GET https://registry.npmjs.org/util-deprecate
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/util-deprecate
npm http 200 https://registry.npmjs.org/process-nextick-args
npm http fetch GET https://registry.npmjs.org/process-nextick-args/-/process-nextick-args-1.0.7.tgz
npm http fetch 200 https://registry.npmjs.org/process-nextick-args/-/process-nextick-args-1.0.7.tgz
npm http request GET https://registry.npmjs.org/delayed-stream
npm http 304 https://registry.npmjs.org/delayed-stream
npm http request GET https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/chalk
npm http request GET https://registry.npmjs.org/is-my-json-valid
npm http request GET https://registry.npmjs.org/pinkie-promise
npm http 200 https://registry.npmjs.org/chalk
npm http 200 https://registry.npmjs.org/is-my-json-valid
npm http fetch GET https://registry.npmjs.org/chalk/-/chalk-1.1.3.tgz
npm http fetch 200 https://registry.npmjs.org/chalk/-/chalk-1.1.3.tgz
npm http 200 https://registry.npmjs.org/pinkie-promise
npm http fetch GET https://registry.npmjs.org/pinkie-promise/-/pinkie-promise-2.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/pinkie-promise/-/pinkie-promise-2.0.1.tgz
npm http request GET https://registry.npmjs.org/has-ansi
npm http request GET https://registry.npmjs.org/escape-string-regexp
npm http request GET https://registry.npmjs.org/ansi-styles
npm http request GET https://registry.npmjs.org/strip-ansi
npm http request GET https://registry.npmjs.org/supports-color
npm http 200 https://registry.npmjs.org/has-ansi
npm http 200 https://registry.npmjs.org/ansi-styles
npm http 200 https://registry.npmjs.org/strip-ansi
npm http 200 https://registry.npmjs.org/supports-color
npm http fetch GET https://registry.npmjs.org/ansi-styles/-/ansi-styles-2.2.1.tgz
npm http fetch 200 https://registry.npmjs.org/ansi-styles/-/ansi-styles-2.2.1.tgz
npm http 200 https://registry.npmjs.org/escape-string-regexp
npm http request GET https://registry.npmjs.org/ansi-regex
npm http 200 https://registry.npmjs.org/ansi-regex
npm http request GET https://registry.npmjs.org/generate-object-property
npm http request GET https://registry.npmjs.org/generate-function
npm http request GET https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/generate-object-property
npm http 304 https://registry.npmjs.org/generate-function
npm http 200 https://registry.npmjs.org/jsonpointer
npm http request GET https://registry.npmjs.org/is-property
npm http 304 https://registry.npmjs.org/is-property
npm http request GET https://registry.npmjs.org/pinkie
npm http 304 https://registry.npmjs.org/pinkie
npm http request GET https://registry.npmjs.org/hoek
npm http request GET https://registry.npmjs.org/boom
npm http request GET https://registry.npmjs.org/sntp
npm http request GET https://registry.npmjs.org/cryptiles
npm http 304 https://registry.npmjs.org/sntp
npm http 200 https://registry.npmjs.org/cryptiles
npm http 200 https://registry.npmjs.org/boom
npm http 200 https://registry.npmjs.org/hoek
npm http request GET https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/jsprim
npm http request GET https://registry.npmjs.org/sshpk
npm http 200 https://registry.npmjs.org/assert-plus
npm http 200 https://registry.npmjs.org/jsprim
npm http fetch GET https://registry.npmjs.org/jsprim/-/jsprim-1.3.0.tgz
npm http 200 https://registry.npmjs.org/sshpk
npm http fetch GET https://registry.npmjs.org/sshpk/-/sshpk-1.8.3.tgz
npm http fetch 200 https://registry.npmjs.org/jsprim/-/jsprim-1.3.0.tgz
npm http fetch 200 https://registry.npmjs.org/sshpk/-/sshpk-1.8.3.tgz
npm http request GET https://registry.npmjs.org/extsprintf
npm http request GET https://registry.npmjs.org/json-schema
npm http request GET https://registry.npmjs.org/verror
npm http 304 https://registry.npmjs.org/extsprintf
npm http 200 https://registry.npmjs.org/json-schema
npm http 200 https://registry.npmjs.org/verror
npm http request GET https://registry.npmjs.org/getpass
npm http request GET https://registry.npmjs.org/dashdash
npm http request GET https://registry.npmjs.org/asn1
npm http 200 https://registry.npmjs.org/getpass
npm http 200 https://registry.npmjs.org/asn1
npm http 200 https://registry.npmjs.org/dashdash
npm http fetch GET https://registry.npmjs.org/getpass/-/getpass-0.1.6.tgz
npm http fetch GET https://registry.npmjs.org/dashdash/-/dashdash-1.14.0.tgz
npm http fetch 200 https://registry.npmjs.org/getpass/-/getpass-0.1.6.tgz
npm http fetch 200 https://registry.npmjs.org/dashdash/-/dashdash-1.14.0.tgz
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/pull-stream
npm http 304 https://registry.npmjs.org/readable-stream
npm http 200 https://registry.npmjs.org/pull-stream
npm http request GET https://registry.npmjs.org/pull-core
npm http 304 https://registry.npmjs.org/pull-core
npm http request GET https://registry.npmjs.org/pouchdb-promise
npm http 304 https://registry.npmjs.org/pouchdb-promise
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/xmlhttprequest-cookie
npm http 304 https://registry.npmjs.org/xmlhttprequest-cookie
npm http request GET https://registry.npmjs.org/xmlhttprequest
npm http 304 https://registry.npmjs.org/xmlhttprequest
npm http request GET https://registry.npmjs.org/pouchdb-changeslike-wrapper
npm http 304 https://registry.npmjs.org/pouchdb-changeslike-wrapper
npm http request GET https://registry.npmjs.org/couchdb-objects
npm http request GET https://registry.npmjs.org/couchdb-eval
npm http request GET https://registry.npmjs.org/random-uuid-v4
npm http 304 https://registry.npmjs.org/couchdb-eval
npm http 200 https://registry.npmjs.org/random-uuid-v4
npm http 304 https://registry.npmjs.org/couchdb-objects
npm http request GET https://registry.npmjs.org/is-empty
npm http 304 https://registry.npmjs.org/is-empty
npm http request GET https://registry.npmjs.org/spark-md5
npm http request GET https://registry.npmjs.org/pouchdb-abstract-mapreduce
npm http request GET https://registry.npmjs.org/jshint
npm http request GET https://registry.npmjs.org/pouchdb-extend
npm http request GET https://registry.npmjs.org/pouchdb-upsert
npm http 304 https://registry.npmjs.org/spark-md5
npm http 200 https://registry.npmjs.org/jshint
npm http fetch GET https://registry.npmjs.org/jshint/-/jshint-2.9.2.tgz
npm http 304 https://registry.npmjs.org/pouchdb-extend
npm http 200 https://registry.npmjs.org/pouchdb-upsert
npm http fetch 200 https://registry.npmjs.org/jshint/-/jshint-2.9.2.tgz
npm http 304 https://registry.npmjs.org/pouchdb-abstract-mapreduce
npm http request GET https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/console-browserify
npm http request GET https://registry.npmjs.org/exit
npm http request GET https://registry.npmjs.org/cli
npm http request GET https://registry.npmjs.org/htmlparser2
npm http request GET https://registry.npmjs.org/shelljs
npm http request GET https://registry.npmjs.org/strip-json-comments
npm http request GET https://registry.npmjs.org/lodash
npm http 304 https://registry.npmjs.org/minimatch
npm WARN deprecated minimatch@2.0.10: Please update to minimatch 3.0.2 or higher to avoid a RegExp DoS issue
npm http 200 https://registry.npmjs.org/exit
npm http 200 https://registry.npmjs.org/console-browserify
npm http 200 https://registry.npmjs.org/htmlparser2
npm http 200 https://registry.npmjs.org/cli
npm http 200 https://registry.npmjs.org/strip-json-comments
npm http 200 https://registry.npmjs.org/shelljs
npm http 200 https://registry.npmjs.org/lodash
npm http request GET https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/glob
npm WARN deprecated minimatch@0.3.0: Please update to minimatch 3.0.2 or higher to avoid a RegExp DoS issue
npm http request GET https://registry.npmjs.org/sigmund
npm http request GET https://registry.npmjs.org/lru-cache
npm http 304 https://registry.npmjs.org/sigmund
npm http 200 https://registry.npmjs.org/lru-cache
npm http request GET https://registry.npmjs.org/date-now
npm http 304 https://registry.npmjs.org/date-now
npm http request GET https://registry.npmjs.org/domhandler
npm http request GET https://registry.npmjs.org/domelementtype
npm http request GET https://registry.npmjs.org/domutils
npm http request GET https://registry.npmjs.org/entities
npm http 304 https://registry.npmjs.org/domhandler
npm http 304 https://registry.npmjs.org/domelementtype
npm http 200 https://registry.npmjs.org/entities
npm http 304 https://registry.npmjs.org/domutils
npm http request GET https://registry.npmjs.org/dom-serializer
npm http 304 https://registry.npmjs.org/dom-serializer
npm http request GET https://registry.npmjs.org/bl
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/http-signature
npm http request GET https://registry.npmjs.org/aws-sign2
npm http request GET https://registry.npmjs.org/har-validator
npm http 304 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/http-signature
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/aws-sign2
npm http fetch GET https://registry.npmjs.org/http-signature/-/http-signature-0.11.0.tgz
npm http fetch GET https://registry.npmjs.org/qs/-/qs-5.1.0.tgz
npm http 304 https://registry.npmjs.org/har-validator
npm http fetch GET https://registry.npmjs.org/har-validator/-/har-validator-1.8.0.tgz
npm http fetch 200 https://registry.npmjs.org/har-validator/-/har-validator-1.8.0.tgz
npm http fetch 200 https://registry.npmjs.org/qs/-/qs-5.1.0.tgz
npm http fetch 200 https://registry.npmjs.org/http-signature/-/http-signature-0.11.0.tgz
npm http request GET https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/ctype
npm http 200 https://registry.npmjs.org/assert-plus
npm http 200 https://registry.npmjs.org/ctype
npm http request GET https://registry.npmjs.org/couchdb-render
npm http 304 https://registry.npmjs.org/couchdb-render
npm http request GET https://registry.npmjs.org/couchdb-resp-completer
npm http 304 https://registry.npmjs.org/couchdb-resp-completer
npm http request GET https://registry.npmjs.org/equals
npm http 200 https://registry.npmjs.org/equals
npm http fetch GET https://registry.npmjs.org/equals/-/equals-1.1.0.tgz
npm http fetch 200 https://registry.npmjs.org/equals/-/equals-1.1.0.tgz
npm http request GET https://registry.npmjs.org/@jkroso%2ftype
npm http 200 https://registry.npmjs.org/@jkroso%2ftype
npm http fetch GET https://registry.npmjs.org/@jkroso/type/-/type-1.1.1.tgz
npm http fetch 200 https://registry.npmjs.org/@jkroso/type/-/type-1.1.1.tgz
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/pouchdb-route
npm http 304 https://registry.npmjs.org/pouchdb-route
npm http request GET https://registry.npmjs.org/pouchdb-promise
npm http 304 https://registry.npmjs.org/pouchdb-promise
npm http request GET https://registry.npmjs.org/get-folder-size
npm http 304 https://registry.npmjs.org/get-folder-size
npm http request GET https://registry.npmjs.org/minimist
npm http request GET https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/minimist
npm http 304 https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/duplexify
npm http request GET https://registry.npmjs.org/varint
npm http 200 https://registry.npmjs.org/readable-stream
npm http 200 https://registry.npmjs.org/duplexify
npm http fetch GET https://registry.npmjs.org/readable-stream/-/readable-stream-2.1.4.tgz
npm http fetch 200 https://registry.npmjs.org/readable-stream/-/readable-stream-2.1.4.tgz
npm http 200 https://registry.npmjs.org/varint
npm http fetch GET https://registry.npmjs.org/varint/-/varint-4.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/varint/-/varint-4.0.1.tgz
npm http request GET https://registry.npmjs.org/end-of-stream
npm http 304 https://registry.npmjs.org/end-of-stream
npm http request GET https://registry.npmjs.org/buffer-shims
npm http 200 https://registry.npmjs.org/buffer-shims
npm http fetch GET https://registry.npmjs.org/buffer-shims/-/buffer-shims-1.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/buffer-shims/-/buffer-shims-1.0.0.tgz
npm http request GET https://registry.npmjs.org/colors
npm http request GET https://registry.npmjs.org/cycle
npm http request GET https://registry.npmjs.org/eyes
npm http request GET https://registry.npmjs.org/pkginfo
npm http request GET https://registry.npmjs.org/stack-trace
npm http 304 https://registry.npmjs.org/cycle
npm http 304 https://registry.npmjs.org/colors
npm http 304 https://registry.npmjs.org/pkginfo
npm http 304 https://registry.npmjs.org/eyes
npm http 304 https://registry.npmjs.org/stack-trace
npm http request GET https://registry.npmjs.org/jsdoc
npm http 200 https://registry.npmjs.org/jsdoc
npm http fetch GET https://registry.npmjs.org/jsdoc/-/jsdoc-3.3.3.tgz
npm http fetch 200 https://registry.npmjs.org/jsdoc/-/jsdoc-3.3.3.tgz
npm http request GET https://registry.npmjs.org/catharsis
npm http request GET https://registry.npmjs.org/js2xmlparser
npm http request GET https://registry.npmjs.org/requizzle
npm http request GET https://registry.npmjs.org/marked
npm http request GET https://registry.npmjs.org/underscore
npm http request GET https://registry.npmjs.org/wrench
npm http request GET https://registry.npmjs.org/esprima
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 304 https://registry.npmjs.org/requizzle
npm http 200 https://registry.npmjs.org/underscore
npm http 200 https://registry.npmjs.org/marked
npm http 304 https://registry.npmjs.org/esprima
npm http 200 https://registry.npmjs.org/wrench
npm http fetch GET https://registry.npmjs.org/esprima/-/esprima-1.2.5.tgz
npm WARN deprecated wrench@1.5.9: wrench.js is deprecated! You should check out fs-extra (https://github.com/jprichardson/node-fs-extra) for any operations you were using wrench for. Thanks for all the usage over the years.
npm http fetch GET https://registry.npmjs.org/wrench/-/wrench-1.5.9.tgz
npm http 200 https://registry.npmjs.org/catharsis
npm http fetch GET https://registry.npmjs.org/catharsis/-/catharsis-0.8.8.tgz
npm http 200 https://registry.npmjs.org/js2xmlparser
npm http fetch GET https://registry.npmjs.org/js2xmlparser/-/js2xmlparser-0.1.9.tgz
npm http fetch 200 https://registry.npmjs.org/esprima/-/esprima-1.2.5.tgz
npm http fetch 200 https://registry.npmjs.org/wrench/-/wrench-1.5.9.tgz
npm http fetch 200 https://registry.npmjs.org/catharsis/-/catharsis-0.8.8.tgz
npm http fetch 200 https://registry.npmjs.org/js2xmlparser/-/js2xmlparser-0.1.9.tgz
npm http fetch 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http request GET https://registry.npmjs.org/underscore-contrib
npm http 304 https://registry.npmjs.org/underscore-contrib
npm WARN prefer global marked@0.3.5 should be installed with -g
npm WARN prefer global jshint@2.9.2 should be installed with -g
npm http request GET https://registry.npmjs.org/leveldown
npm http request GET https://registry.npmjs.org/websql
npm http 200 https://registry.npmjs.org/leveldown
npm http fetch GET https://registry.npmjs.org/leveldown/-/leveldown-1.4.6.tgz
npm http fetch 200 https://registry.npmjs.org/leveldown/-/leveldown-1.4.6.tgz
npm http 200 https://registry.npmjs.org/websql
npm http fetch GET https://registry.npmjs.org/websql/-/websql-0.4.4.tgz
npm http fetch 200 https://registry.npmjs.org/websql/-/websql-0.4.4.tgz
npm http request GET https://registry.npmjs.org/prebuild
npm http request GET https://registry.npmjs.org/bindings
npm http request GET https://registry.npmjs.org/abstract-leveldown
npm http request GET https://registry.npmjs.org/nan
npm http request GET https://registry.npmjs.org/fast-future
npm http 200 https://registry.npmjs.org/bindings
npm http 304 https://registry.npmjs.org/nan
npm http fetch GET https://registry.npmjs.org/nan/-/nan-2.3.5.tgz
npm http 304 https://registry.npmjs.org/fast-future
npm http fetch 200 https://registry.npmjs.org/nan/-/nan-2.3.5.tgz
npm http 200 https://registry.npmjs.org/prebuild
npm http fetch GET https://registry.npmjs.org/prebuild/-/prebuild-4.2.2.tgz
npm http 304 https://registry.npmjs.org/abstract-leveldown
npm http fetch 200 https://registry.npmjs.org/prebuild/-/prebuild-4.2.2.tgz
npm http request GET https://registry.npmjs.org/expand-template
npm http request GET https://registry.npmjs.org/ghreleases
npm http request GET https://registry.npmjs.org/github-from-package
npm http request GET https://registry.npmjs.org/node-gyp
npm http request GET https://registry.npmjs.org/node-ninja
npm http request GET https://registry.npmjs.org/noop-logger
npm http request GET https://registry.npmjs.org/npmlog
npm http request GET https://registry.npmjs.org/pump
npm http request GET https://registry.npmjs.org/simple-get
npm http request GET https://registry.npmjs.org/tar-fs
npm http request GET https://registry.npmjs.org/tar-stream
npm http request GET https://registry.npmjs.org/os-homedir
npm http request GET https://registry.npmjs.org/rc
npm http 200 https://registry.npmjs.org/node-gyp
npm http fetch GET https://registry.npmjs.org/node-gyp/-/node-gyp-3.3.1.tgz
npm http 200 https://registry.npmjs.org/node-ninja
npm http fetch GET https://registry.npmjs.org/node-ninja/-/node-ninja-1.0.1.tgz
npm http 200 https://registry.npmjs.org/npmlog
npm http fetch GET https://registry.npmjs.org/npmlog/-/npmlog-2.0.4.tgz
npm http 200 https://registry.npmjs.org/noop-logger
npm http 200 https://registry.npmjs.org/pump
npm http fetch GET https://registry.npmjs.org/noop-logger/-/noop-logger-0.1.1.tgz
npm http fetch GET https://registry.npmjs.org/pump/-/pump-1.0.1.tgz
npm http 200 https://registry.npmjs.org/tar-fs
npm http fetch GET https://registry.npmjs.org/tar-fs/-/tar-fs-1.13.0.tgz
npm http 200 https://registry.npmjs.org/tar-stream
npm http fetch GET https://registry.npmjs.org/tar-stream/-/tar-stream-1.5.2.tgz
npm http 200 https://registry.npmjs.org/os-homedir
npm http 200 https://registry.npmjs.org/rc
npm http 200 https://registry.npmjs.org/github-from-package
npm http fetch 200 https://registry.npmjs.org/node-gyp/-/node-gyp-3.3.1.tgz
npm http fetch GET https://registry.npmjs.org/github-from-package/-/github-from-package-0.0.0.tgz
npm http 200 https://registry.npmjs.org/ghreleases
npm http 200 https://registry.npmjs.org/simple-get
npm http fetch GET https://registry.npmjs.org/ghreleases/-/ghreleases-1.0.5.tgz
npm http fetch GET https://registry.npmjs.org/simple-get/-/simple-get-1.4.3.tgz
npm http fetch 200 https://registry.npmjs.org/node-ninja/-/node-ninja-1.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/npmlog/-/npmlog-2.0.4.tgz
npm http 200 https://registry.npmjs.org/expand-template
npm http fetch 200 https://registry.npmjs.org/noop-logger/-/noop-logger-0.1.1.tgz
npm http fetch GET https://registry.npmjs.org/expand-template/-/expand-template-1.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/pump/-/pump-1.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/tar-stream/-/tar-stream-1.5.2.tgz
npm http fetch 200 https://registry.npmjs.org/tar-fs/-/tar-fs-1.13.0.tgz
npm http fetch 200 https://registry.npmjs.org/ghreleases/-/ghreleases-1.0.5.tgz
npm http fetch 200 https://registry.npmjs.org/github-from-package/-/github-from-package-0.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/expand-template/-/expand-template-1.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/simple-get/-/simple-get-1.4.3.tgz
npm http request GET https://registry.npmjs.org/ghrepos
npm http request GET https://registry.npmjs.org/ghutils
npm http request GET https://registry.npmjs.org/simple-mime
npm http request GET https://registry.npmjs.org/url-template
npm http request GET https://registry.npmjs.org/after
npm http 304 https://registry.npmjs.org/after
npm http 200 https://registry.npmjs.org/url-template
npm http 200 https://registry.npmjs.org/simple-mime
npm http 200 https://registry.npmjs.org/ghrepos
npm http fetch GET https://registry.npmjs.org/url-template/-/url-template-2.0.7.tgz
npm http fetch GET https://registry.npmjs.org/simple-mime/-/simple-mime-0.1.0.tgz
npm http fetch GET https://registry.npmjs.org/ghrepos/-/ghrepos-2.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/url-template/-/url-template-2.0.7.tgz
npm http fetch 200 https://registry.npmjs.org/simple-mime/-/simple-mime-0.1.0.tgz
npm http fetch 200 https://registry.npmjs.org/ghrepos/-/ghrepos-2.0.0.tgz
npm http 200 https://registry.npmjs.org/ghutils
npm http fetch GET https://registry.npmjs.org/ghutils/-/ghutils-3.2.0.tgz
npm http fetch 200 https://registry.npmjs.org/ghutils/-/ghutils-3.2.0.tgz
npm http request GET https://registry.npmjs.org/jsonist
npm http 200 https://registry.npmjs.org/jsonist
npm http fetch GET https://registry.npmjs.org/jsonist/-/jsonist-1.2.0.tgz
npm http fetch 200 https://registry.npmjs.org/jsonist/-/jsonist-1.2.0.tgz
npm http request GET https://registry.npmjs.org/hyperquest
npm http request GET https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/bl
npm http 200 https://registry.npmjs.org/hyperquest
npm http fetch GET https://registry.npmjs.org/hyperquest/-/hyperquest-1.2.0.tgz
npm http fetch 200 https://registry.npmjs.org/hyperquest/-/hyperquest-1.2.0.tgz
npm http request GET https://registry.npmjs.org/readable-stream
npm http 200 https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/isarray
npm http 200 https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/duplexer2
npm http 200 https://registry.npmjs.org/duplexer2
npm http request GET https://registry.npmjs.org/path-array
npm http request GET https://registry.npmjs.org/which
npm http request GET https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/rimraf
npm http request GET https://registry.npmjs.org/osenv
npm http request GET https://registry.npmjs.org/nopt
npm http request GET https://registry.npmjs.org/fstream
npm http request GET https://registry.npmjs.org/tar
npm http 200 https://registry.npmjs.org/path-array
npm http 200 https://registry.npmjs.org/which
npm http 304 https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/minimatch
npm http fetch GET https://registry.npmjs.org/which/-/which-1.2.10.tgz
npm http fetch GET https://registry.npmjs.org/path-array/-/path-array-1.0.1.tgz
npm WARN deprecated minimatch@1.0.0: Please update to minimatch 3.0.2 or higher to avoid a RegExp DoS issue
npm http 200 https://registry.npmjs.org/osenv
npm http 304 https://registry.npmjs.org/rimraf
npm http 200 https://registry.npmjs.org/nopt
npm http fetch GET https://registry.npmjs.org/minimatch/-/minimatch-1.0.0.tgz
npm http 200 https://registry.npmjs.org/tar
npm http 200 https://registry.npmjs.org/fstream
npm http fetch 200 https://registry.npmjs.org/which/-/which-1.2.10.tgz
npm http fetch 200 https://registry.npmjs.org/path-array/-/path-array-1.0.1.tgz
npm http fetch GET https://registry.npmjs.org/tar/-/tar-2.2.1.tgz
npm http fetch GET https://registry.npmjs.org/fstream/-/fstream-1.0.10.tgz
npm http fetch 200 https://registry.npmjs.org/minimatch/-/minimatch-1.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/tar/-/tar-2.2.1.tgz
npm http fetch 200 https://registry.npmjs.org/fstream/-/fstream-1.0.10.tgz
npm http request GET https://registry.npmjs.org/fs.realpath
npm http 304 https://registry.npmjs.org/fs.realpath
npm WARN deprecated minimatch@2.0.10: Please update to minimatch 3.0.2 or higher to avoid a RegExp DoS issue
npm http request GET https://registry.npmjs.org/abbrev
npm http 200 https://registry.npmjs.org/abbrev
npm http fetch GET https://registry.npmjs.org/abbrev/-/abbrev-1.0.9.tgz
npm http fetch 200 https://registry.npmjs.org/abbrev/-/abbrev-1.0.9.tgz
npm http request GET https://registry.npmjs.org/are-we-there-yet
npm http request GET https://registry.npmjs.org/gauge
npm http request GET https://registry.npmjs.org/ansi
npm http 200 https://registry.npmjs.org/ansi
npm http 200 https://registry.npmjs.org/are-we-there-yet
npm http 200 https://registry.npmjs.org/gauge
npm http fetch GET https://registry.npmjs.org/are-we-there-yet/-/are-we-there-yet-1.1.2.tgz
npm http fetch GET https://registry.npmjs.org/gauge/-/gauge-1.2.7.tgz
npm http fetch 200 https://registry.npmjs.org/are-we-there-yet/-/are-we-there-yet-1.1.2.tgz
npm http fetch 200 https://registry.npmjs.org/gauge/-/gauge-1.2.7.tgz
npm http request GET https://registry.npmjs.org/delegates
npm http 200 https://registry.npmjs.org/delegates
npm http fetch GET https://registry.npmjs.org/delegates/-/delegates-1.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/delegates/-/delegates-1.0.0.tgz
npm http request GET https://registry.npmjs.org/has-unicode
npm http request GET https://registry.npmjs.org/lodash.pad
npm http request GET https://registry.npmjs.org/lodash.padend
npm http request GET https://registry.npmjs.org/lodash.padstart
npm http 200 https://registry.npmjs.org/has-unicode
npm http 200 https://registry.npmjs.org/lodash.padend
npm http 200 https://registry.npmjs.org/lodash.pad
npm http fetch GET https://registry.npmjs.org/has-unicode/-/has-unicode-2.0.1.tgz
npm http fetch GET https://registry.npmjs.org/lodash.padend/-/lodash.padend-4.5.0.tgz
npm http fetch GET https://registry.npmjs.org/lodash.pad/-/lodash.pad-4.4.0.tgz
npm http 200 https://registry.npmjs.org/lodash.padstart
npm http fetch GET https://registry.npmjs.org/lodash.padstart/-/lodash.padstart-4.5.0.tgz
npm http fetch 200 https://registry.npmjs.org/has-unicode/-/has-unicode-2.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/lodash.padend/-/lodash.padend-4.5.0.tgz
npm http fetch 200 https://registry.npmjs.org/lodash.pad/-/lodash.pad-4.4.0.tgz
npm http fetch 200 https://registry.npmjs.org/lodash.padstart/-/lodash.padstart-4.5.0.tgz
npm http request GET https://registry.npmjs.org/lodash._baseslice
npm http request GET https://registry.npmjs.org/lodash._basetostring
npm http request GET https://registry.npmjs.org/lodash.tostring
npm http 200 https://registry.npmjs.org/lodash._baseslice
npm http 200 https://registry.npmjs.org/lodash._basetostring
npm http 200 https://registry.npmjs.org/lodash.tostring
npm http fetch GET https://registry.npmjs.org/lodash._baseslice/-/lodash._baseslice-4.0.0.tgz
npm http fetch GET https://registry.npmjs.org/lodash._basetostring/-/lodash._basetostring-4.12.0.tgz
npm http fetch GET https://registry.npmjs.org/lodash.tostring/-/lodash.tostring-4.1.3.tgz
npm http fetch 200 https://registry.npmjs.org/lodash.tostring/-/lodash.tostring-4.1.3.tgz
npm http fetch 200 https://registry.npmjs.org/lodash._baseslice/-/lodash._baseslice-4.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/lodash._basetostring/-/lodash._basetostring-4.12.0.tgz
npm http request GET https://registry.npmjs.org/os-tmpdir
npm http 304 https://registry.npmjs.org/os-tmpdir
npm http request GET https://registry.npmjs.org/array-index
npm http 200 https://registry.npmjs.org/array-index
npm http fetch GET https://registry.npmjs.org/array-index/-/array-index-1.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/array-index/-/array-index-1.0.0.tgz
npm http request GET https://registry.npmjs.org/es6-symbol
npm http 200 https://registry.npmjs.org/es6-symbol
npm http fetch GET https://registry.npmjs.org/es6-symbol/-/es6-symbol-3.1.0.tgz
npm http fetch 200 https://registry.npmjs.org/es6-symbol/-/es6-symbol-3.1.0.tgz
npm http request GET https://registry.npmjs.org/d
npm http request GET https://registry.npmjs.org/es5-ext
npm http 200 https://registry.npmjs.org/d
npm http fetch GET https://registry.npmjs.org/d/-/d-0.1.1.tgz
npm http 200 https://registry.npmjs.org/es5-ext
npm http fetch GET https://registry.npmjs.org/es5-ext/-/es5-ext-0.10.11.tgz
npm http fetch 200 https://registry.npmjs.org/d/-/d-0.1.1.tgz
npm http fetch 200 https://registry.npmjs.org/es5-ext/-/es5-ext-0.10.11.tgz
npm http request GET https://registry.npmjs.org/es6-iterator
npm http fetch GET https://registry.npmjs.org/es6-symbol/-/es6-symbol-3.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/es6-symbol/-/es6-symbol-3.0.2.tgz
npm http 200 https://registry.npmjs.org/es6-iterator
npm http fetch GET https://registry.npmjs.org/es6-iterator/-/es6-iterator-2.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/es6-iterator/-/es6-iterator-2.0.0.tgz
npm http request GET https://registry.npmjs.org/block-stream
npm http 200 https://registry.npmjs.org/block-stream
npm http fetch GET https://registry.npmjs.org/block-stream/-/block-stream-0.0.9.tgz
npm http fetch 200 https://registry.npmjs.org/block-stream/-/block-stream-0.0.9.tgz
npm http request GET https://registry.npmjs.org/isexe
npm http 200 https://registry.npmjs.org/isexe
npm http fetch GET https://registry.npmjs.org/isexe/-/isexe-1.1.2.tgz
npm http fetch 200 https://registry.npmjs.org/isexe/-/isexe-1.1.2.tgz
npm http request GET https://registry.npmjs.org/end-of-stream
npm http 304 https://registry.npmjs.org/end-of-stream
npm http fetch GET https://registry.npmjs.org/end-of-stream/-/end-of-stream-1.1.0.tgz
npm http fetch 200 https://registry.npmjs.org/end-of-stream/-/end-of-stream-1.1.0.tgz
npm http request GET https://registry.npmjs.org/deep-extend
npm http request GET https://registry.npmjs.org/ini
npm http 200 https://registry.npmjs.org/ini
npm http 200 https://registry.npmjs.org/deep-extend
npm WARN engine deep-extend@0.4.1: wanted: {"node":">=0.12.0","iojs":">=1.0.0"} (current: {"node":"0.10.40","npm":"3.3.12"})
npm http request GET https://registry.npmjs.org/unzip-response
npm http 200 https://registry.npmjs.org/unzip-response
npm http fetch GET https://registry.npmjs.org/unzip-response/-/unzip-response-1.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/unzip-response/-/unzip-response-1.0.0.tgz
npm http request GET https://registry.npmjs.org/jsbn
npm http request GET https://registry.npmjs.org/ecc-jsbn
npm http request GET https://registry.npmjs.org/jodid25519
npm http request GET https://registry.npmjs.org/tweetnacl
npm http 304 https://registry.npmjs.org/jodid25519
npm http 200 https://registry.npmjs.org/tweetnacl
npm http 304 https://registry.npmjs.org/ecc-jsbn
npm http 200 https://registry.npmjs.org/jsbn
npm http fetch GET https://registry.npmjs.org/tweetnacl/-/tweetnacl-0.13.3.tgz
npm http fetch 200 https://registry.npmjs.org/tweetnacl/-/tweetnacl-0.13.3.tgz
npm http request GET https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/noop-fn
npm http request GET https://registry.npmjs.org/sqlite3
npm http 304 https://registry.npmjs.org/immediate
npm http 200 https://registry.npmjs.org/sqlite3
npm http fetch GET https://registry.npmjs.org/sqlite3/-/sqlite3-3.1.4.tgz
npm http fetch 200 https://registry.npmjs.org/sqlite3/-/sqlite3-3.1.4.tgz
npm http 304 https://registry.npmjs.org/noop-fn
npm WARN prefer global node-ninja@1.0.1 should be installed with -g
npm WARN prefer global node-gyp@3.3.1 should be installed with -g
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
npm http request GET https://registry.npmjs.org/fs-extra-promise
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/request
npm http request GET https://registry.npmjs.org/jxc
npm http request GET https://registry.npmjs.org/unzip
npm http 304 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/fs-extra-promise
npm http 304 https://registry.npmjs.org/request
npm http 200 https://registry.npmjs.org/jxc
npm http 200 https://registry.npmjs.org/unzip
npm http request GET https://registry.npmjs.org/fs-extra
npm http request GET https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/fs-extra
npm http 304 https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/jsonfile
npm http request GET https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/graceful-fs
npm http 200 https://registry.npmjs.org/jsonfile
npm http 304 https://registry.npmjs.org/rimraf
npm http request GET https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/fs.realpath
npm http request GET https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/inherits
npm http request GET https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/once
npm http request GET https://registry.npmjs.org/path-is-absolute
npm http 304 https://registry.npmjs.org/fs.realpath
npm http 304 https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/minimatch
npm http 200 https://registry.npmjs.org/inflight
npm http 304 https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http request GET https://registry.npmjs.org/wrappy
npm http 200 https://registry.npmjs.org/wrappy
npm http request GET https://registry.npmjs.org/brace-expansion
npm http 304 https://registry.npmjs.org/brace-expansion
npm http request GET https://registry.npmjs.org/balanced-match
npm http request GET https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/balanced-match
npm http 304 https://registry.npmjs.org/concat-map
npm http request GET https://registry.npmjs.org/progress
npm http request GET https://registry.npmjs.org/adm-zip
npm http 200 https://registry.npmjs.org/adm-zip
npm http 200 https://registry.npmjs.org/progress
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/immediate
npm http 304 https://registry.npmjs.org/inline-process-browser
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/jstransform
npm http request GET https://registry.npmjs.org/esprima
npm http request GET https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/esprima
npm http 304 https://registry.npmjs.org/through
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/commoner
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/object-assign
npm http request GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/commoner
npm http 304 https://registry.npmjs.org/object-assign
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 200 https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/detective
npm http request GET https://registry.npmjs.org/iconv-lite
npm http request GET https://registry.npmjs.org/mkdirp
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/q
npm http request GET https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/commander
npm http 304 https://registry.npmjs.org/detective
npm http 304 https://registry.npmjs.org/private
npm http 200 https://registry.npmjs.org/mkdirp
npm http 200 https://registry.npmjs.org/iconv-lite
npm http 304 https://registry.npmjs.org/q
npm http 304 https://registry.npmjs.org/recast
npm http request GET https://registry.npmjs.org/graceful-readlink
npm http 304 https://registry.npmjs.org/graceful-readlink
npm http request GET https://registry.npmjs.org/acorn
npm http request GET https://registry.npmjs.org/defined
npm http 304 https://registry.npmjs.org/acorn
npm http 304 https://registry.npmjs.org/defined
npm http request GET https://registry.npmjs.org/minimist
npm http 304 https://registry.npmjs.org/minimist
npm http request GET https://registry.npmjs.org/ast-types
npm http 304 https://registry.npmjs.org/ast-types
npm http request GET https://registry.npmjs.org/amdefine
npm http 304 https://registry.npmjs.org/amdefine
npm http request GET https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/falafel
npm http 304 https://registry.npmjs.org/through2
npm http request GET https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/foreach
npm http 200 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/object-keys
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/xtend
npm http 200 https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/core-util-is
npm http 304 https://registry.npmjs.org/string_decoder
npm http request GET https://registry.npmjs.org/esmangle-evaluator
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/bl
npm http request GET https://registry.npmjs.org/caseless
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/forever-agent
npm http request GET https://registry.npmjs.org/form-data
npm http request GET https://registry.npmjs.org/json-stringify-safe
npm http request GET https://registry.npmjs.org/mime-types
npm http request GET https://registry.npmjs.org/node-uuid
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/tunnel-agent
npm http request GET https://registry.npmjs.org/tough-cookie
npm http request GET https://registry.npmjs.org/http-signature
npm http request GET https://registry.npmjs.org/oauth-sign
npm http request GET https://registry.npmjs.org/hawk
npm http request GET https://registry.npmjs.org/aws-sign2
npm http request GET https://registry.npmjs.org/stringstream
npm http request GET https://registry.npmjs.org/combined-stream
npm http request GET https://registry.npmjs.org/isstream
npm http request GET https://registry.npmjs.org/har-validator
npm http 304 https://registry.npmjs.org/form-data
npm http 200 https://registry.npmjs.org/caseless
npm http 304 https://registry.npmjs.org/forever-agent
npm http 304 https://registry.npmjs.org/bl
npm http 200 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/json-stringify-safe
npm http 304 https://registry.npmjs.org/mime-types
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/tunnel-agent
npm http 200 https://registry.npmjs.org/node-uuid
npm http 304 https://registry.npmjs.org/tough-cookie
npm http 304 https://registry.npmjs.org/http-signature
npm http 304 https://registry.npmjs.org/oauth-sign
npm http 200 https://registry.npmjs.org/aws-sign2
npm http 304 https://registry.npmjs.org/stringstream
npm http 304 https://registry.npmjs.org/combined-stream
npm http 200 https://registry.npmjs.org/isstream
npm http 304 https://registry.npmjs.org/har-validator
npm http 200 https://registry.npmjs.org/hawk
npm http request GET https://registry.npmjs.org/process-nextick-args
npm http request GET https://registry.npmjs.org/util-deprecate
npm http 304 https://registry.npmjs.org/process-nextick-args
npm http 200 https://registry.npmjs.org/util-deprecate
npm http request GET https://registry.npmjs.org/delayed-stream
npm http 304 https://registry.npmjs.org/delayed-stream
npm http request GET https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/mime-db
npm http 304 https://registry.npmjs.org/mime-db
npm http request GET https://registry.npmjs.org/chalk
npm http request GET https://registry.npmjs.org/is-my-json-valid
npm http 304 https://registry.npmjs.org/is-my-json-valid
npm http 304 https://registry.npmjs.org/chalk
npm http request GET https://registry.npmjs.org/ansi-styles
npm http request GET https://registry.npmjs.org/escape-string-regexp
npm http request GET https://registry.npmjs.org/has-ansi
npm http request GET https://registry.npmjs.org/strip-ansi
npm http request GET https://registry.npmjs.org/supports-color
npm http 304 https://registry.npmjs.org/escape-string-regexp
npm http 304 https://registry.npmjs.org/strip-ansi
npm http 304 https://registry.npmjs.org/supports-color
npm http 304 https://registry.npmjs.org/has-ansi
npm http 304 https://registry.npmjs.org/ansi-styles
npm http request GET https://registry.npmjs.org/ansi-regex
npm http 200 https://registry.npmjs.org/ansi-regex
npm http request GET https://registry.npmjs.org/generate-function
npm http request GET https://registry.npmjs.org/generate-object-property
npm http request GET https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/generate-function
npm http 304 https://registry.npmjs.org/jsonpointer
npm http 200 https://registry.npmjs.org/generate-object-property
npm http request GET https://registry.npmjs.org/is-property
npm http 200 https://registry.npmjs.org/is-property
npm http request GET https://registry.npmjs.org/hoek
npm http request GET https://registry.npmjs.org/boom
npm http request GET https://registry.npmjs.org/cryptiles
npm http request GET https://registry.npmjs.org/sntp
npm http 304 https://registry.npmjs.org/sntp
npm http 304 https://registry.npmjs.org/cryptiles
npm http 200 https://registry.npmjs.org/boom
npm http 200 https://registry.npmjs.org/hoek
npm http request GET https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/asn1
npm http request GET https://registry.npmjs.org/ctype
npm http 304 https://registry.npmjs.org/ctype
npm http 304 https://registry.npmjs.org/assert-plus
npm http 304 https://registry.npmjs.org/asn1
npm http request GET https://registry.npmjs.org/fstream
npm http request GET https://registry.npmjs.org/pullstream
npm http request GET https://registry.npmjs.org/binary
npm http request GET https://registry.npmjs.org/setimmediate
npm http request GET https://registry.npmjs.org/match-stream
npm http 304 https://registry.npmjs.org/binary
npm http 200 https://registry.npmjs.org/setimmediate
npm http 200 https://registry.npmjs.org/fstream
npm http 304 https://registry.npmjs.org/match-stream
npm http 304 https://registry.npmjs.org/pullstream
npm http request GET https://registry.npmjs.org/chainsaw
npm http request GET https://registry.npmjs.org/buffers
npm http 304 https://registry.npmjs.org/buffers
npm http 304 https://registry.npmjs.org/chainsaw
npm http request GET https://registry.npmjs.org/traverse
npm http 200 https://registry.npmjs.org/traverse
npm http request GET https://registry.npmjs.org/graceful-fs
npm http 304 https://registry.npmjs.org/graceful-fs
npm WARN deprecated graceful-fs@3.0.8: graceful-fs v3.0.0 and before will fail on node releases >= v7.0. Please update to graceful-fs@^4.0.0 as soon as possible. Use 'npm ls graceful-fs' to find it in the tree.
npm http request GET https://registry.npmjs.org/over
npm http request GET https://registry.npmjs.org/slice-stream
npm http 304 https://registry.npmjs.org/slice-stream
npm http 304 https://registry.npmjs.org/over
npm WARN EPACKAGEJSON install@0.0.1 No repository field.
npm http request GET https://registry.npmjs.org/pouchdb-node
npm http request GET https://registry.npmjs.org/balanced-match
npm http request GET https://registry.npmjs.org/body-parser
npm http request GET https://registry.npmjs.org/concat-map
npm http request GET https://registry.npmjs.org/express
npm http request GET https://registry.npmjs.org/bn.js
npm http request GET https://registry.npmjs.org/forever-agent
npm http request GET https://registry.npmjs.org/express-pouchdb
npm http request GET https://registry.npmjs.org/inherits
npm http request GET https://registry.npmjs.org/fs-extra-promise
npm http request GET https://registry.npmjs.org/is-property
npm http request GET https://registry.npmjs.org/js-extend
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/long
npm http request GET https://registry.npmjs.org/minimist
npm http request GET https://registry.npmjs.org/multiplex
npm http request GET https://registry.npmjs.org/node-uuid
npm http request GET https://registry.npmjs.org/request
npm http request GET https://registry.npmjs.org/socket.io-client
npm http request GET https://registry.npmjs.org/leveldown-mobile
npm http request GET https://registry.npmjs.org/nock
npm http request GET https://registry.npmjs.org/randomstring
npm http request GET https://registry.npmjs.org/proxyquire
npm http request GET https://registry.npmjs.org/request-promise
npm http request GET https://registry.npmjs.org/urlsafe-base64
npm http request GET https://registry.npmjs.org/tape
npm http request GET https://registry.npmjs.org/supertest
npm http request GET https://registry.npmjs.org/sinon
npm http request GET https://registry.npmjs.org/supertest-as-promised
npm http request GET https://registry.npmjs.org/tape-catch
npm http request GET https://registry.npmjs.org/tmp
npm http request GET https://registry.npmjs.org/uuid
npm http 304 https://registry.npmjs.org/balanced-match
npm http 304 https://registry.npmjs.org/body-parser
npm http 304 https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/express
npm http 304 https://registry.npmjs.org/forever-agent
npm http 304 https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/fs-extra-promise
npm http 304 https://registry.npmjs.org/is-property
npm http 200 https://registry.npmjs.org/bn.js
npm http 304 https://registry.npmjs.org/lie
npm http fetch GET https://registry.npmjs.org/balanced-match/-/balanced-match-0.2.0.tgz
npm http 304 https://registry.npmjs.org/minimist
npm http fetch GET https://registry.npmjs.org/bn.js/-/bn.js-4.10.0.tgz
npm http 304 https://registry.npmjs.org/js-extend
npm http 304 https://registry.npmjs.org/node-uuid
npm http 304 https://registry.npmjs.org/express-pouchdb
npm http 304 https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/socket.io-client
npm http 200 https://registry.npmjs.org/nock
npm http 304 https://registry.npmjs.org/multiplex
npm http 200 https://registry.npmjs.org/pouchdb-node
npm http fetch GET https://registry.npmjs.org/nock/-/nock-2.12.0.tgz
npm http fetch GET https://registry.npmjs.org/pouchdb-node/-/pouchdb-node-5.4.4.tgz
npm http 200 https://registry.npmjs.org/request-promise
npm http 304 https://registry.npmjs.org/long
npm http 304 https://registry.npmjs.org/leveldown-mobile
npm http 304 https://registry.npmjs.org/tape
npm http 200 https://registry.npmjs.org/supertest
npm http fetch GET https://registry.npmjs.org/tape/-/tape-4.0.0.tgz
npm http fetch GET https://registry.npmjs.org/supertest/-/supertest-1.1.0.tgz
npm http 200 https://registry.npmjs.org/proxyquire
npm http 200 https://registry.npmjs.org/sinon
npm http 200 https://registry.npmjs.org/tmp
npm http 200 https://registry.npmjs.org/uuid
npm http fetch 200 https://registry.npmjs.org/balanced-match/-/balanced-match-0.2.0.tgz
npm http fetch GET https://registry.npmjs.org/uuid/-/uuid-2.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/bn.js/-/bn.js-4.10.0.tgz
npm http 200 https://registry.npmjs.org/randomstring
npm http fetch GET https://registry.npmjs.org/randomstring/-/randomstring-1.1.5.tgz
npm http fetch 200 https://registry.npmjs.org/nock/-/nock-2.12.0.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-node/-/pouchdb-node-5.4.4.tgz
npm http fetch 200 https://registry.npmjs.org/tape/-/tape-4.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/supertest/-/supertest-1.1.0.tgz
npm http 200 https://registry.npmjs.org/tape-catch
npm http fetch 200 https://registry.npmjs.org/uuid/-/uuid-2.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/randomstring/-/randomstring-1.1.5.tgz
npm http 304 https://registry.npmjs.org/urlsafe-base64
npm http 200 https://registry.npmjs.org/supertest-as-promised
npm http request GET https://registry.npmjs.org/bytes
npm http request GET https://registry.npmjs.org/content-type
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/depd
npm http request GET https://registry.npmjs.org/http-errors
npm http request GET https://registry.npmjs.org/iconv-lite
npm http request GET https://registry.npmjs.org/on-finished
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/raw-body
npm http request GET https://registry.npmjs.org/type-is
npm http 304 https://registry.npmjs.org/http-errors
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/bytes
npm http 304 https://registry.npmjs.org/depd
npm http 304 https://registry.npmjs.org/content-type
npm http 304 https://registry.npmjs.org/iconv-lite
npm http 304 https://registry.npmjs.org/on-finished
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/raw-body
npm http 304 https://registry.npmjs.org/type-is
npm http request GET https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/statuses
npm http 304 https://registry.npmjs.org/statuses
npm http request GET https://registry.npmjs.org/ee-first
npm http 304 https://registry.npmjs.org/ee-first
npm http request GET https://registry.npmjs.org/unpipe
npm http 304 https://registry.npmjs.org/unpipe
npm http request GET https://registry.npmjs.org/media-typer
npm http request GET https://registry.npmjs.org/mime-types
npm http 304 https://registry.npmjs.org/mime-types
npm http 304 https://registry.npmjs.org/media-typer
npm http request GET https://registry.npmjs.org/mime-db
npm http 304 https://registry.npmjs.org/mime-db
npm http request GET https://registry.npmjs.org/accepts
npm http request GET https://registry.npmjs.org/array-flatten
npm http request GET https://registry.npmjs.org/content-disposition
npm http request GET https://registry.npmjs.org/cookie
npm http request GET https://registry.npmjs.org/cookie-signature
npm http request GET https://registry.npmjs.org/escape-html
npm http request GET https://registry.npmjs.org/etag
npm http request GET https://registry.npmjs.org/finalhandler
npm http request GET https://registry.npmjs.org/fresh
npm http request GET https://registry.npmjs.org/merge-descriptors
npm http request GET https://registry.npmjs.org/methods
npm http request GET https://registry.npmjs.org/parseurl
npm http request GET https://registry.npmjs.org/path-to-regexp
npm http request GET https://registry.npmjs.org/proxy-addr
npm http request GET https://registry.npmjs.org/range-parser
npm http request GET https://registry.npmjs.org/send
npm http request GET https://registry.npmjs.org/serve-static
npm http request GET https://registry.npmjs.org/utils-merge
npm http request GET https://registry.npmjs.org/vary
npm http 304 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/cookie
npm http 304 https://registry.npmjs.org/content-disposition
npm http 304 https://registry.npmjs.org/array-flatten
npm http 304 https://registry.npmjs.org/cookie-signature
npm http 200 https://registry.npmjs.org/escape-html
npm http 304 https://registry.npmjs.org/etag
npm http 304 https://registry.npmjs.org/fresh
npm http 304 https://registry.npmjs.org/merge-descriptors
npm http 200 https://registry.npmjs.org/finalhandler
npm http 200 https://registry.npmjs.org/methods
npm http 200 https://registry.npmjs.org/parseurl
npm http 304 https://registry.npmjs.org/proxy-addr
npm http 304 https://registry.npmjs.org/range-parser
npm http 304 https://registry.npmjs.org/path-to-regexp
npm http 304 https://registry.npmjs.org/send
npm http 304 https://registry.npmjs.org/serve-static
npm http 304 https://registry.npmjs.org/utils-merge
npm http 304 https://registry.npmjs.org/vary
npm http request GET https://registry.npmjs.org/negotiator
npm http 304 https://registry.npmjs.org/negotiator
npm http request GET https://registry.npmjs.org/forwarded
npm http request GET https://registry.npmjs.org/ipaddr.js
npm http 304 https://registry.npmjs.org/ipaddr.js
npm http 200 https://registry.npmjs.org/forwarded
npm http request GET https://registry.npmjs.org/destroy
npm http request GET https://registry.npmjs.org/mime
npm http 304 https://registry.npmjs.org/destroy
npm http 304 https://registry.npmjs.org/mime
npm http request GET https://registry.npmjs.org/basic-auth
npm http request GET https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/compression
npm http request GET https://registry.npmjs.org/cookie-parser
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/header-case-normalizer
npm http request GET https://registry.npmjs.org/multiparty
npm http request GET https://registry.npmjs.org/pouchdb-all-dbs
npm http request GET https://registry.npmjs.org/pouchdb-auth
npm http request GET https://registry.npmjs.org/pouchdb-find
npm http request GET https://registry.npmjs.org/pouchdb-list
npm http request GET https://registry.npmjs.org/pouchdb-replicator
npm http request GET https://registry.npmjs.org/pouchdb-rewrite
npm http request GET https://registry.npmjs.org/pouchdb-security
npm http request GET https://registry.npmjs.org/pouchdb-show
npm http request GET https://registry.npmjs.org/pouchdb-size
npm http request GET https://registry.npmjs.org/pouchdb-update
npm http request GET https://registry.npmjs.org/pouchdb-validation
npm http request GET https://registry.npmjs.org/pouchdb-vhost
npm http request GET https://registry.npmjs.org/pouchdb-wrappers
npm http 304 https://registry.npmjs.org/basic-auth
npm http 304 https://registry.npmjs.org/compression
npm http 304 https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/extend
npm http 200 https://registry.npmjs.org/multiparty
npm http 304 https://registry.npmjs.org/pouchdb-auth
npm http 304 https://registry.npmjs.org/pouchdb-find
npm http 304 https://registry.npmjs.org/cookie-parser
npm http 304 https://registry.npmjs.org/pouchdb-all-dbs
npm http 304 https://registry.npmjs.org/header-case-normalizer
npm http 304 https://registry.npmjs.org/pouchdb-list
npm http 304 https://registry.npmjs.org/pouchdb-replicator
npm http 304 https://registry.npmjs.org/pouchdb-show
npm http 304 https://registry.npmjs.org/pouchdb-security
npm http 304 https://registry.npmjs.org/pouchdb-size
npm http 304 https://registry.npmjs.org/pouchdb-validation
npm http 304 https://registry.npmjs.org/pouchdb-vhost
npm http 304 https://registry.npmjs.org/pouchdb-update
npm http 304 https://registry.npmjs.org/pouchdb-wrappers
npm http 304 https://registry.npmjs.org/pouchdb-rewrite
npm http request GET https://registry.npmjs.org/compressible
npm http request GET https://registry.npmjs.org/on-headers
npm http 304 https://registry.npmjs.org/on-headers
npm http 304 https://registry.npmjs.org/compressible
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/stream-counter
npm http 304 https://registry.npmjs.org/stream-counter
npm http 304 https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/argsarray
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/tiny-queue
npm http 304 https://registry.npmjs.org/es3ify
npm http 304 https://registry.npmjs.org/argsarray
npm http 304 https://registry.npmjs.org/tiny-queue
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/jstransform
npm http request GET https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 304 https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/through
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/base62
npm http 304 https://registry.npmjs.org/source-map
npm http request GET https://registry.npmjs.org/amdefine
npm http 304 https://registry.npmjs.org/amdefine
npm http request GET https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/inline-process-browser
npm http 304 https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/falafel
npm http 304 https://registry.npmjs.org/through2
npm http request GET https://registry.npmjs.org/acorn
npm http request GET https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/acorn
npm http 304 https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/xtend
npm http request GET https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http 304 https://registry.npmjs.org/recast
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/ast-types
npm http 304 https://registry.npmjs.org/private
npm http 304 https://registry.npmjs.org/ast-types
npm http request GET https://registry.npmjs.org/base64url
npm http request GET https://registry.npmjs.org/couchdb-calculate-session-id
npm http request GET https://registry.npmjs.org/crypto-lite
npm http request GET https://registry.npmjs.org/pouchdb
npm http request GET https://registry.npmjs.org/pouchdb-bulkdocs-wrapper
npm http request GET https://registry.npmjs.org/pouchdb-plugin-error
npm http request GET https://registry.npmjs.org/pouchdb-promise
npm http request GET https://registry.npmjs.org/pouchdb-req-http-query
npm http request GET https://registry.npmjs.org/pouchdb-system-db
npm http request GET https://registry.npmjs.org/promise-nodify
npm http request GET https://registry.npmjs.org/secure-random
npm http 304 https://registry.npmjs.org/base64url
npm http 304 https://registry.npmjs.org/pouchdb
npm http 304 https://registry.npmjs.org/pouchdb-promise
npm http 304 https://registry.npmjs.org/pouchdb-req-http-query
npm http 304 https://registry.npmjs.org/couchdb-calculate-session-id
npm http 304 https://registry.npmjs.org/pouchdb-system-db
npm http 304 https://registry.npmjs.org/promise-nodify
npm http 304 https://registry.npmjs.org/pouchdb-bulkdocs-wrapper
npm http 304 https://registry.npmjs.org/crypto-lite
npm http 304 https://registry.npmjs.org/pouchdb-plugin-error
npm http 304 https://registry.npmjs.org/secure-random
npm http request GET https://registry.npmjs.org/concat-stream
npm http request GET https://registry.npmjs.org/meow
npm http 304 https://registry.npmjs.org/meow
npm http 200 https://registry.npmjs.org/concat-stream
npm http request GET https://registry.npmjs.org/typedarray
npm http 304 https://registry.npmjs.org/typedarray
npm http request GET https://registry.npmjs.org/camelcase-keys
npm http request GET https://registry.npmjs.org/indent-string
npm http request GET https://registry.npmjs.org/object-assign
npm http 304 https://registry.npmjs.org/camelcase-keys
npm http 304 https://registry.npmjs.org/indent-string
npm http 304 https://registry.npmjs.org/object-assign
npm http request GET https://registry.npmjs.org/map-obj
npm http request GET https://registry.npmjs.org/camelcase
npm http 304 https://registry.npmjs.org/camelcase
npm http 200 https://registry.npmjs.org/map-obj
npm http request GET https://registry.npmjs.org/get-stdin
npm http request GET https://registry.npmjs.org/repeating
npm http 200 https://registry.npmjs.org/get-stdin
npm http 200 https://registry.npmjs.org/repeating
npm http request GET https://registry.npmjs.org/is-finite
npm http 304 https://registry.npmjs.org/is-finite
npm http request GET https://registry.npmjs.org/number-is-nan
npm http 304 https://registry.npmjs.org/number-is-nan
npm http request GET https://registry.npmjs.org/aproba
npm http 304 https://registry.npmjs.org/aproba
npm http request GET https://registry.npmjs.org/double-ended-queue
npm http request GET https://registry.npmjs.org/fruitdown
npm http request GET https://registry.npmjs.org/level-write-stream
npm http request GET https://registry.npmjs.org/levelup
npm http request GET https://registry.npmjs.org/localstorage-down
npm http request GET https://registry.npmjs.org/memdown
npm http request GET https://registry.npmjs.org/pouchdb-collate
npm http request GET https://registry.npmjs.org/pouchdb-collections
npm http request GET https://registry.npmjs.org/scope-eval
npm http request GET https://registry.npmjs.org/spark-md5
npm http request GET https://registry.npmjs.org/sublevel-pouchdb
npm http request GET https://registry.npmjs.org/vuvuzela
npm http request GET https://registry.npmjs.org/js-extend
npm http request GET https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/double-ended-queue
npm http 304 https://registry.npmjs.org/memdown
npm http 304 https://registry.npmjs.org/levelup
npm http 304 https://registry.npmjs.org/level-write-stream
npm http 304 https://registry.npmjs.org/localstorage-down
npm http 304 https://registry.npmjs.org/fruitdown
npm http 304 https://registry.npmjs.org/pouchdb-collections
npm http 304 https://registry.npmjs.org/pouchdb-collate
npm http 304 https://registry.npmjs.org/js-extend
npm http 304 https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/scope-eval
npm http 304 https://registry.npmjs.org/sublevel-pouchdb
npm http 304 https://registry.npmjs.org/vuvuzela
npm http 304 https://registry.npmjs.org/spark-md5
npm http request GET https://registry.npmjs.org/abstract-leveldown
npm http request GET https://registry.npmjs.org/d64
npm http 304 https://registry.npmjs.org/abstract-leveldown
npm http 304 https://registry.npmjs.org/d64
npm http request GET https://registry.npmjs.org/end-stream
npm http 304 https://registry.npmjs.org/end-stream
npm http request GET https://registry.npmjs.org/write-stream
npm http 304 https://registry.npmjs.org/write-stream
npm http request GET https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/deferred-leveldown
npm http request GET https://registry.npmjs.org/level-codec
npm http request GET https://registry.npmjs.org/level-errors
npm http request GET https://registry.npmjs.org/level-iterator-stream
npm http request GET https://registry.npmjs.org/prr
npm http request GET https://registry.npmjs.org/semver
npm http 304 https://registry.npmjs.org/prr
npm http 304 https://registry.npmjs.org/semver
npm http 304 https://registry.npmjs.org/deferred-leveldown
npm http 304 https://registry.npmjs.org/level-iterator-stream
npm http 304 https://registry.npmjs.org/level-codec
npm http 304 https://registry.npmjs.org/level-errors
npm http request GET https://registry.npmjs.org/errno
npm http 304 https://registry.npmjs.org/errno
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/es3ify
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http request GET https://registry.npmjs.org/esprima
npm http request GET https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/esprima
npm http 304 https://registry.npmjs.org/jstransform
npm http request GET https://registry.npmjs.org/commoner
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/commoner
npm http 304 https://registry.npmjs.org/base62
npm http 304 https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/detective
npm http request GET https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/mkdirp
npm http request GET https://registry.npmjs.org/q
npm http 304 https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/detective
npm http 304 https://registry.npmjs.org/commander
npm http 304 https://registry.npmjs.org/graceful-fs
npm http 304 https://registry.npmjs.org/q
npm http 304 https://registry.npmjs.org/mkdirp
npm http request GET https://registry.npmjs.org/graceful-readlink
npm http 304 https://registry.npmjs.org/graceful-readlink
npm http request GET https://registry.npmjs.org/defined
npm http 304 https://registry.npmjs.org/defined
npm http request GET https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/once
npm http request GET https://registry.npmjs.org/path-is-absolute
npm http 304 https://registry.npmjs.org/inflight
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http 304 https://registry.npmjs.org/minimatch
npm http 304 https://registry.npmjs.org/once
npm http request GET https://registry.npmjs.org/wrappy
npm http 304 https://registry.npmjs.org/wrappy
npm http request GET https://registry.npmjs.org/brace-expansion
npm http 304 https://registry.npmjs.org/brace-expansion
npm http request GET https://registry.npmjs.org/balanced-match
npm http 304 https://registry.npmjs.org/balanced-match
npm http request GET https://registry.npmjs.org/minimist
npm http 304 https://registry.npmjs.org/minimist
npm http request GET https://registry.npmjs.org/humble-localstorage
npm http request GET https://registry.npmjs.org/tiny-queue
npm http 304 https://registry.npmjs.org/tiny-queue
npm http 304 https://registry.npmjs.org/humble-localstorage
npm http request GET https://registry.npmjs.org/has-localstorage
npm http request GET https://registry.npmjs.org/localstorage-memory
npm http 304 https://registry.npmjs.org/has-localstorage
npm http 304 https://registry.npmjs.org/localstorage-memory
npm http request GET https://registry.npmjs.org/ltgt
npm http request GET https://registry.npmjs.org/functional-red-black-tree
npm http 304 https://registry.npmjs.org/ltgt
npm http 304 https://registry.npmjs.org/functional-red-black-tree
npm http request GET https://registry.npmjs.org/aws-sign2
npm http request GET https://registry.npmjs.org/aws4
npm http request GET https://registry.npmjs.org/bl
npm http request GET https://registry.npmjs.org/caseless
npm http request GET https://registry.npmjs.org/combined-stream
npm http request GET https://registry.npmjs.org/form-data
npm http request GET https://registry.npmjs.org/har-validator
npm http request GET https://registry.npmjs.org/hawk
npm http request GET https://registry.npmjs.org/http-signature
npm http request GET https://registry.npmjs.org/is-typedarray
npm http request GET https://registry.npmjs.org/isstream
npm http request GET https://registry.npmjs.org/json-stringify-safe
npm http request GET https://registry.npmjs.org/oauth-sign
npm http request GET https://registry.npmjs.org/stringstream
npm http request GET https://registry.npmjs.org/tough-cookie
npm http request GET https://registry.npmjs.org/tunnel-agent
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/aws-sign2
npm http 304 https://registry.npmjs.org/caseless
npm http 304 https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/aws4
npm http 304 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/har-validator
npm http 304 https://registry.npmjs.org/hawk
npm http 304 https://registry.npmjs.org/http-signature
npm http 304 https://registry.npmjs.org/is-typedarray
npm http 304 https://registry.npmjs.org/isstream
npm http 304 https://registry.npmjs.org/json-stringify-safe
npm http 304 https://registry.npmjs.org/oauth-sign
npm http 304 https://registry.npmjs.org/stringstream
npm http 304 https://registry.npmjs.org/tough-cookie
npm http 304 https://registry.npmjs.org/tunnel-agent
npm http 304 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/process-nextick-args
npm http request GET https://registry.npmjs.org/util-deprecate
npm http request GET https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/util-deprecate
npm http 304 https://registry.npmjs.org/process-nextick-args
npm http 304 https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/delayed-stream
npm http 304 https://registry.npmjs.org/delayed-stream
npm http request GET https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/chalk
npm http request GET https://registry.npmjs.org/is-my-json-valid
npm http request GET https://registry.npmjs.org/pinkie-promise
npm http 304 https://registry.npmjs.org/chalk
npm http 304 https://registry.npmjs.org/pinkie-promise
npm http 304 https://registry.npmjs.org/is-my-json-valid
npm http request GET https://registry.npmjs.org/ansi-styles
npm http request GET https://registry.npmjs.org/escape-string-regexp
npm http request GET https://registry.npmjs.org/has-ansi
npm http request GET https://registry.npmjs.org/strip-ansi
npm http request GET https://registry.npmjs.org/supports-color
npm http 304 https://registry.npmjs.org/strip-ansi
npm http 304 https://registry.npmjs.org/ansi-styles
npm http 304 https://registry.npmjs.org/supports-color
npm http 304 https://registry.npmjs.org/escape-string-regexp
npm http 304 https://registry.npmjs.org/has-ansi
npm http request GET https://registry.npmjs.org/ansi-regex
npm http 304 https://registry.npmjs.org/ansi-regex
npm http request GET https://registry.npmjs.org/generate-function
npm http request GET https://registry.npmjs.org/generate-object-property
npm http request GET https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/generate-object-property
npm http 304 https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/generate-function
npm http request GET https://registry.npmjs.org/pinkie
npm http 304 https://registry.npmjs.org/pinkie
npm http request GET https://registry.npmjs.org/hoek
npm http request GET https://registry.npmjs.org/cryptiles
npm http request GET https://registry.npmjs.org/sntp
npm http request GET https://registry.npmjs.org/boom
npm http 304 https://registry.npmjs.org/sntp
npm http 304 https://registry.npmjs.org/cryptiles
npm http 304 https://registry.npmjs.org/hoek
npm http 304 https://registry.npmjs.org/boom
npm http request GET https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/jsprim
npm http request GET https://registry.npmjs.org/sshpk
npm http 304 https://registry.npmjs.org/jsprim
npm http 304 https://registry.npmjs.org/assert-plus
npm http 304 https://registry.npmjs.org/sshpk
npm http request GET https://registry.npmjs.org/extsprintf
npm http request GET https://registry.npmjs.org/json-schema
npm http request GET https://registry.npmjs.org/verror
npm http 304 https://registry.npmjs.org/extsprintf
npm http 304 https://registry.npmjs.org/json-schema
npm http 200 https://registry.npmjs.org/verror
npm http request GET https://registry.npmjs.org/asn1
npm http request GET https://registry.npmjs.org/dashdash
npm http request GET https://registry.npmjs.org/getpass
npm http 304 https://registry.npmjs.org/getpass
npm http 304 https://registry.npmjs.org/asn1
npm http 304 https://registry.npmjs.org/dashdash
npm http request GET https://registry.npmjs.org/pull-stream
npm http 304 https://registry.npmjs.org/pull-stream
npm http request GET https://registry.npmjs.org/pull-core
npm http 304 https://registry.npmjs.org/pull-core
npm http request GET https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/pouchdb-promise
npm http 304 https://registry.npmjs.org/pouchdb-promise
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/xmlhttprequest-cookie
npm http 304 https://registry.npmjs.org/xmlhttprequest-cookie
npm http request GET https://registry.npmjs.org/xmlhttprequest
npm http 304 https://registry.npmjs.org/xmlhttprequest
npm http request GET https://registry.npmjs.org/pouchdb-changeslike-wrapper
npm http 304 https://registry.npmjs.org/pouchdb-changeslike-wrapper
npm http request GET https://registry.npmjs.org/couchdb-objects
npm http request GET https://registry.npmjs.org/couchdb-eval
npm http request GET https://registry.npmjs.org/random-uuid-v4
npm http 304 https://registry.npmjs.org/random-uuid-v4
npm http 304 https://registry.npmjs.org/couchdb-objects
npm http 304 https://registry.npmjs.org/couchdb-eval
npm http request GET https://registry.npmjs.org/is-empty
npm http 304 https://registry.npmjs.org/is-empty
npm http request GET https://registry.npmjs.org/jshint
npm http request GET https://registry.npmjs.org/pouchdb-abstract-mapreduce
npm http request GET https://registry.npmjs.org/pouchdb-extend
npm http request GET https://registry.npmjs.org/pouchdb-upsert
npm http request GET https://registry.npmjs.org/spark-md5
npm http 304 https://registry.npmjs.org/jshint
npm http 304 https://registry.npmjs.org/spark-md5
npm http 304 https://registry.npmjs.org/pouchdb-extend
npm http 304 https://registry.npmjs.org/pouchdb-abstract-mapreduce
npm http 304 https://registry.npmjs.org/pouchdb-upsert
npm http request GET https://registry.npmjs.org/cli
npm http request GET https://registry.npmjs.org/console-browserify
npm http request GET https://registry.npmjs.org/exit
npm http request GET https://registry.npmjs.org/htmlparser2
npm http request GET https://registry.npmjs.org/shelljs
npm http request GET https://registry.npmjs.org/strip-json-comments
npm http request GET https://registry.npmjs.org/lodash
npm http request GET https://registry.npmjs.org/minimatch
npm http 200 https://registry.npmjs.org/exit
npm http 304 https://registry.npmjs.org/shelljs
npm http 200 https://registry.npmjs.org/console-browserify
npm http 304 https://registry.npmjs.org/cli
npm http 200 https://registry.npmjs.org/htmlparser2
npm http 304 https://registry.npmjs.org/strip-json-comments
npm http 304 https://registry.npmjs.org/lodash
npm http 304 https://registry.npmjs.org/minimatch
npm WARN deprecated minimatch@2.0.10: Please update to minimatch 3.0.2 or higher to avoid a RegExp DoS issue
npm http request GET https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/glob
npm WARN deprecated minimatch@0.3.0: Please update to minimatch 3.0.2 or higher to avoid a RegExp DoS issue
npm http request GET https://registry.npmjs.org/lru-cache
npm http request GET https://registry.npmjs.org/sigmund
npm http 304 https://registry.npmjs.org/lru-cache
npm http 304 https://registry.npmjs.org/sigmund
npm http request GET https://registry.npmjs.org/date-now
npm http 304 https://registry.npmjs.org/date-now
npm http request GET https://registry.npmjs.org/domhandler
npm http request GET https://registry.npmjs.org/domutils
npm http request GET https://registry.npmjs.org/domelementtype
npm http request GET https://registry.npmjs.org/entities
npm http 304 https://registry.npmjs.org/domhandler
npm http 304 https://registry.npmjs.org/domelementtype
npm http 304 https://registry.npmjs.org/domutils
npm http 304 https://registry.npmjs.org/entities
npm http request GET https://registry.npmjs.org/dom-serializer
npm http 200 https://registry.npmjs.org/dom-serializer
npm http request GET https://registry.npmjs.org/bl
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/http-signature
npm http request GET https://registry.npmjs.org/aws-sign2
npm http request GET https://registry.npmjs.org/har-validator
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/http-signature
npm http 304 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/aws-sign2
npm http 304 https://registry.npmjs.org/har-validator
npm http request GET https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/ctype
npm http request GET https://registry.npmjs.org/assert-plus
npm http 304 https://registry.npmjs.org/assert-plus
npm http 304 https://registry.npmjs.org/ctype
npm http request GET https://registry.npmjs.org/couchdb-render
npm http 304 https://registry.npmjs.org/couchdb-render
npm http request GET https://registry.npmjs.org/couchdb-resp-completer
npm http 304 https://registry.npmjs.org/couchdb-resp-completer
npm http request GET https://registry.npmjs.org/equals
npm http 304 https://registry.npmjs.org/equals
npm http request GET https://registry.npmjs.org/@jkroso%2ftype
npm http 304 https://registry.npmjs.org/@jkroso%2ftype
npm http request GET https://registry.npmjs.org/pouchdb-route
npm http 304 https://registry.npmjs.org/pouchdb-route
npm http request GET https://registry.npmjs.org/pouchdb-promise
npm http 304 https://registry.npmjs.org/pouchdb-promise
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/get-folder-size
npm http 304 https://registry.npmjs.org/get-folder-size
npm http request GET https://registry.npmjs.org/minimist
npm http request GET https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/minimist
npm http request GET https://registry.npmjs.org/fs-extra
npm http 304 https://registry.npmjs.org/fs-extra
npm http request GET https://registry.npmjs.org/jsonfile
npm http request GET https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/rimraf
npm http 200 https://registry.npmjs.org/jsonfile
npm http request GET https://registry.npmjs.org/fs.realpath
npm http 304 https://registry.npmjs.org/fs.realpath
npm http request GET https://registry.npmjs.org/bindings
npm http request GET https://registry.npmjs.org/fast-future
npm http request GET https://registry.npmjs.org/abstract-leveldown
npm http 200 https://registry.npmjs.org/bindings
npm http 304 https://registry.npmjs.org/fast-future
npm http 304 https://registry.npmjs.org/abstract-leveldown
npm http request GET https://registry.npmjs.org/varint
npm http request GET https://registry.npmjs.org/duplexify
npm http request GET https://registry.npmjs.org/readable-stream
npm http 200 https://registry.npmjs.org/duplexify
npm http 200 https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/varint
npm http request GET https://registry.npmjs.org/end-of-stream
npm http 304 https://registry.npmjs.org/end-of-stream
npm http request GET https://registry.npmjs.org/buffer-shims
npm http 304 https://registry.npmjs.org/buffer-shims
npm http request GET https://registry.npmjs.org/deep-equal
npm http request GET https://registry.npmjs.org/debug
npm WARN deprecated lodash@2.4.1: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
npm http request GET https://registry.npmjs.org/chai
npm http request GET https://registry.npmjs.org/propagate
npm http 200 https://registry.npmjs.org/deep-equal
npm http 304 https://registry.npmjs.org/debug
npm http 200 https://registry.npmjs.org/propagate
npm http 200 https://registry.npmjs.org/chai
npm http request GET https://registry.npmjs.org/type-detect
npm http request GET https://registry.npmjs.org/assertion-error
npm http request GET https://registry.npmjs.org/deep-eql
npm http 200 https://registry.npmjs.org/deep-eql
npm http 200 https://registry.npmjs.org/assertion-error
npm http 200 https://registry.npmjs.org/type-detect
npm http fetch GET https://registry.npmjs.org/assertion-error/-/assertion-error-1.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/assertion-error/-/assertion-error-1.0.2.tgz
npm http request GET https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/ip
npm http 304 https://registry.npmjs.org/ip
npm http fetch GET https://registry.npmjs.org/ip/-/ip-1.1.3.tgz
npm http fetch 200 https://registry.npmjs.org/ip/-/ip-1.1.3.tgz
npm http request GET https://registry.npmjs.org/pouchdb-adapter-http
npm http request GET https://registry.npmjs.org/pouchdb-adapter-leveldb
npm http request GET https://registry.npmjs.org/pouchdb-core
npm http request GET https://registry.npmjs.org/pouchdb-mapreduce
npm http request GET https://registry.npmjs.org/pouchdb-replication
npm http 200 https://registry.npmjs.org/pouchdb-mapreduce
npm http fetch GET https://registry.npmjs.org/pouchdb-mapreduce/-/pouchdb-mapreduce-5.4.4.tgz
npm http 200 https://registry.npmjs.org/pouchdb-adapter-http
npm http fetch GET https://registry.npmjs.org/pouchdb-adapter-http/-/pouchdb-adapter-http-5.4.4.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-mapreduce/-/pouchdb-mapreduce-5.4.4.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-adapter-http/-/pouchdb-adapter-http-5.4.4.tgz
npm http 200 https://registry.npmjs.org/pouchdb-core
npm http 200 https://registry.npmjs.org/pouchdb-adapter-leveldb
npm http fetch GET https://registry.npmjs.org/pouchdb-core/-/pouchdb-core-5.4.4.tgz
npm http fetch GET https://registry.npmjs.org/pouchdb-adapter-leveldb/-/pouchdb-adapter-leveldb-5.4.4.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-core/-/pouchdb-core-5.4.4.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-adapter-leveldb/-/pouchdb-adapter-leveldb-5.4.4.tgz
npm http 200 https://registry.npmjs.org/pouchdb-replication
npm http fetch GET https://registry.npmjs.org/pouchdb-replication/-/pouchdb-replication-5.4.4.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-replication/-/pouchdb-replication-5.4.4.tgz
npm http request GET https://registry.npmjs.org/pouchdb-ajax
npm http request GET https://registry.npmjs.org/pouchdb-binary-utils
npm http request GET https://registry.npmjs.org/pouchdb-errors
npm http request GET https://registry.npmjs.org/pouchdb-md5
npm http request GET https://registry.npmjs.org/pouchdb-utils
npm http 200 https://registry.npmjs.org/pouchdb-binary-utils
npm http 200 https://registry.npmjs.org/pouchdb-errors
npm http fetch GET https://registry.npmjs.org/pouchdb-binary-utils/-/pouchdb-binary-utils-5.4.4.tgz
npm http fetch GET https://registry.npmjs.org/pouchdb-errors/-/pouchdb-errors-5.4.4.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-binary-utils/-/pouchdb-binary-utils-5.4.4.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-errors/-/pouchdb-errors-5.4.4.tgz
npm http 200 https://registry.npmjs.org/pouchdb-ajax
npm http 200 https://registry.npmjs.org/pouchdb-md5
npm http 200 https://registry.npmjs.org/pouchdb-utils
npm http fetch GET https://registry.npmjs.org/pouchdb-ajax/-/pouchdb-ajax-5.4.4.tgz
npm http fetch GET https://registry.npmjs.org/pouchdb-md5/-/pouchdb-md5-5.4.4.tgz
npm http fetch GET https://registry.npmjs.org/pouchdb-utils/-/pouchdb-utils-5.4.4.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-ajax/-/pouchdb-ajax-5.4.4.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-utils/-/pouchdb-utils-5.4.4.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-md5/-/pouchdb-md5-5.4.4.tgz
npm http request GET https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/request
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/qs
npm http 200 https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/pouchdb-adapter-leveldb-core
npm http request GET https://registry.npmjs.org/leveldown
npm http 304 https://registry.npmjs.org/leveldown
npm http 200 https://registry.npmjs.org/pouchdb-adapter-leveldb-core
npm http fetch GET https://registry.npmjs.org/pouchdb-adapter-leveldb-core/-/pouchdb-adapter-leveldb-core-5.4.4.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-adapter-leveldb-core/-/pouchdb-adapter-leveldb-core-5.4.4.tgz
npm http request GET https://registry.npmjs.org/nan
npm http request GET https://registry.npmjs.org/prebuild
npm http 304 https://registry.npmjs.org/nan
npm http 304 https://registry.npmjs.org/prebuild
npm http request GET https://registry.npmjs.org/expand-template
npm http request GET https://registry.npmjs.org/ghreleases
npm http request GET https://registry.npmjs.org/github-from-package
npm http request GET https://registry.npmjs.org/node-gyp
npm http request GET https://registry.npmjs.org/node-ninja
npm http request GET https://registry.npmjs.org/noop-logger
npm http request GET https://registry.npmjs.org/npmlog
npm http request GET https://registry.npmjs.org/os-homedir
npm http request GET https://registry.npmjs.org/pump
npm http request GET https://registry.npmjs.org/rc
npm http request GET https://registry.npmjs.org/simple-get
npm http request GET https://registry.npmjs.org/tar-fs
npm http request GET https://registry.npmjs.org/tar-stream
npm http 200 https://registry.npmjs.org/node-gyp
npm http 304 https://registry.npmjs.org/noop-logger
npm http 304 https://registry.npmjs.org/npmlog
npm http 200 https://registry.npmjs.org/os-homedir
npm http 200 https://registry.npmjs.org/pump
npm http 304 https://registry.npmjs.org/rc
npm http 304 https://registry.npmjs.org/simple-get
npm http 304 https://registry.npmjs.org/tar-fs
npm http 304 https://registry.npmjs.org/expand-template
npm http 304 https://registry.npmjs.org/tar-stream
npm http 304 https://registry.npmjs.org/ghreleases
npm http 304 https://registry.npmjs.org/node-ninja
npm http 304 https://registry.npmjs.org/github-from-package
npm http request GET https://registry.npmjs.org/after
npm http request GET https://registry.npmjs.org/ghrepos
npm http request GET https://registry.npmjs.org/ghutils
npm http request GET https://registry.npmjs.org/simple-mime
npm http request GET https://registry.npmjs.org/url-template
npm http 304 https://registry.npmjs.org/url-template
npm http 304 https://registry.npmjs.org/after
npm http 304 https://registry.npmjs.org/ghrepos
npm http 304 https://registry.npmjs.org/simple-mime
npm http 304 https://registry.npmjs.org/ghutils
npm http request GET https://registry.npmjs.org/jsonist
npm http 304 https://registry.npmjs.org/jsonist
npm http request GET https://registry.npmjs.org/hyperquest
npm http request GET https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/hyperquest
npm http request GET https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/duplexer2
npm http 304 https://registry.npmjs.org/duplexer2
npm http request GET https://registry.npmjs.org/fstream
npm http request GET https://registry.npmjs.org/nopt
npm http request GET https://registry.npmjs.org/osenv
npm http request GET https://registry.npmjs.org/path-array
npm http request GET https://registry.npmjs.org/tar
npm http request GET https://registry.npmjs.org/which
npm http request GET https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/minimatch
npm http 304 https://registry.npmjs.org/nopt
npm http 304 https://registry.npmjs.org/path-array
npm http 200 https://registry.npmjs.org/osenv
npm http 200 https://registry.npmjs.org/tar
npm http 200 https://registry.npmjs.org/fstream
npm http 304 https://registry.npmjs.org/which
npm http 304 https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/minimatch
npm WARN deprecated minimatch@1.0.0: Please update to minimatch 3.0.2 or higher to avoid a RegExp DoS issue
npm http request GET https://registry.npmjs.org/abbrev
npm http 304 https://registry.npmjs.org/abbrev
npm http request GET https://registry.npmjs.org/ansi
npm http request GET https://registry.npmjs.org/are-we-there-yet
npm http request GET https://registry.npmjs.org/gauge
npm http 304 https://registry.npmjs.org/ansi
npm http 304 https://registry.npmjs.org/are-we-there-yet
npm http 304 https://registry.npmjs.org/gauge
npm http request GET https://registry.npmjs.org/delegates
npm http 304 https://registry.npmjs.org/delegates
npm http request GET https://registry.npmjs.org/lodash.pad
npm http request GET https://registry.npmjs.org/has-unicode
npm http request GET https://registry.npmjs.org/lodash.padend
npm http request GET https://registry.npmjs.org/lodash.padstart
npm http 304 https://registry.npmjs.org/has-unicode
npm http 304 https://registry.npmjs.org/lodash.pad
npm http 304 https://registry.npmjs.org/lodash.padend
npm http 200 https://registry.npmjs.org/lodash.padstart
npm http request GET https://registry.npmjs.org/lodash._baseslice
npm http request GET https://registry.npmjs.org/lodash._basetostring
npm http request GET https://registry.npmjs.org/lodash.tostring
npm http 304 https://registry.npmjs.org/lodash._baseslice
npm http 304 https://registry.npmjs.org/lodash._basetostring
npm http 200 https://registry.npmjs.org/lodash.tostring
npm http request GET https://registry.npmjs.org/os-tmpdir
npm http 304 https://registry.npmjs.org/os-tmpdir
npm http request GET https://registry.npmjs.org/array-index
npm http 304 https://registry.npmjs.org/array-index
npm http request GET https://registry.npmjs.org/es6-symbol
npm http 304 https://registry.npmjs.org/es6-symbol
npm http request GET https://registry.npmjs.org/d
npm http request GET https://registry.npmjs.org/es5-ext
npm http 304 https://registry.npmjs.org/d
npm http 304 https://registry.npmjs.org/es5-ext
npm http request GET https://registry.npmjs.org/es6-iterator
npm http 200 https://registry.npmjs.org/es6-iterator
npm http request GET https://registry.npmjs.org/block-stream
npm http 304 https://registry.npmjs.org/block-stream
npm http request GET https://registry.npmjs.org/isexe
npm http 304 https://registry.npmjs.org/isexe
npm http request GET https://registry.npmjs.org/end-of-stream
npm http 304 https://registry.npmjs.org/end-of-stream
npm http request GET https://registry.npmjs.org/deep-extend
npm http request GET https://registry.npmjs.org/ini
npm http 304 https://registry.npmjs.org/deep-extend
npm http 304 https://registry.npmjs.org/ini
npm WARN engine deep-extend@0.4.1: wanted: {"node":">=0.12.0","iojs":">=1.0.0"} (current: {"node":"0.10.40","npm":"3.3.12"})
npm http request GET https://registry.npmjs.org/unzip-response
npm http 304 https://registry.npmjs.org/unzip-response
npm http request GET https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/pouchdb-adapter-utils
npm http request GET https://registry.npmjs.org/pouchdb-json
npm http request GET https://registry.npmjs.org/pouchdb-merge
npm http request GET https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/through2
npm http 200 https://registry.npmjs.org/pouchdb-merge
npm http fetch GET https://registry.npmjs.org/pouchdb-merge/-/pouchdb-merge-5.4.4.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-merge/-/pouchdb-merge-5.4.4.tgz
npm http 200 https://registry.npmjs.org/pouchdb-json
npm http 200 https://registry.npmjs.org/pouchdb-adapter-utils
npm http fetch GET https://registry.npmjs.org/pouchdb-json/-/pouchdb-json-5.4.4.tgz
npm http fetch GET https://registry.npmjs.org/pouchdb-adapter-utils/-/pouchdb-adapter-utils-5.4.4.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-json/-/pouchdb-json-5.4.4.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-adapter-utils/-/pouchdb-adapter-utils-5.4.4.tgz
npm http request GET https://registry.npmjs.org/pouchdb-mapreduce-utils
npm http 200 https://registry.npmjs.org/pouchdb-mapreduce-utils
npm http fetch GET https://registry.npmjs.org/pouchdb-mapreduce-utils/-/pouchdb-mapreduce-utils-5.4.4.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-mapreduce-utils/-/pouchdb-mapreduce-utils-5.4.4.tgz
npm http request GET https://registry.npmjs.org/pouchdb-checkpointer
npm http request GET https://registry.npmjs.org/pouchdb-generate-replication-id
npm http 200 https://registry.npmjs.org/pouchdb-checkpointer
npm http fetch GET https://registry.npmjs.org/pouchdb-checkpointer/-/pouchdb-checkpointer-5.4.4.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-checkpointer/-/pouchdb-checkpointer-5.4.4.tgz
npm http 200 https://registry.npmjs.org/pouchdb-generate-replication-id
npm http fetch GET https://registry.npmjs.org/pouchdb-generate-replication-id/-/pouchdb-generate-replication-id-5.4.4.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-generate-replication-id/-/pouchdb-generate-replication-id-5.4.4.tgz
npm http request GET https://registry.npmjs.org/module-not-found-error
npm http request GET https://registry.npmjs.org/fill-keys
npm http 304 https://registry.npmjs.org/fill-keys
npm http 304 https://registry.npmjs.org/module-not-found-error
npm http request GET https://registry.npmjs.org/is-object
npm http 200 https://registry.npmjs.org/is-object
npm http request GET https://registry.npmjs.org/array-uniq
npm http 200 https://registry.npmjs.org/array-uniq
npm http request GET https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/lodash
npm http 304 https://registry.npmjs.org/lodash
npm http 304 https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/formatio
npm http request GET https://registry.npmjs.org/lolex
npm http request GET https://registry.npmjs.org/util
npm http request GET https://registry.npmjs.org/samsam
npm http 304 https://registry.npmjs.org/formatio
npm http 304 https://registry.npmjs.org/samsam
npm http 200 https://registry.npmjs.org/util
npm http 200 https://registry.npmjs.org/lolex
npm http request GET https://registry.npmjs.org/engine.io-client
npm http request GET https://registry.npmjs.org/component-bind
npm http request GET https://registry.npmjs.org/component-emitter
npm http request GET https://registry.npmjs.org/object-component
npm http request GET https://registry.npmjs.org/socket.io-parser
npm http request GET https://registry.npmjs.org/has-binary
npm http request GET https://registry.npmjs.org/indexof
npm http request GET https://registry.npmjs.org/parseuri
npm http request GET https://registry.npmjs.org/to-array
npm http request GET https://registry.npmjs.org/backo2
npm http request GET https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/engine.io-client
npm http 304 https://registry.npmjs.org/component-bind
npm http 304 https://registry.npmjs.org/component-emitter
npm http 304 https://registry.npmjs.org/object-component
npm http 304 https://registry.npmjs.org/socket.io-parser
npm http 304 https://registry.npmjs.org/has-binary
npm http 304 https://registry.npmjs.org/indexof
npm http 304 https://registry.npmjs.org/parseuri
npm http 304 https://registry.npmjs.org/to-array
npm http 304 https://registry.npmjs.org/backo2
npm http 304 https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/component-inherit
npm http request GET https://registry.npmjs.org/engine.io-parser
npm http request GET https://registry.npmjs.org/has-cors
npm http request GET https://registry.npmjs.org/parsejson
npm http request GET https://registry.npmjs.org/parseqs
npm http request GET https://registry.npmjs.org/ws
npm http fetch GET https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http 304 https://registry.npmjs.org/component-inherit
npm http 304 https://registry.npmjs.org/engine.io-parser
npm http 304 https://registry.npmjs.org/parsejson
npm http 304 https://registry.npmjs.org/has-cors
npm http 304 https://registry.npmjs.org/parseqs
npm http 304 https://registry.npmjs.org/ws
npm http fetch 200 https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http request GET https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/arraybuffer.slice
npm http request GET https://registry.npmjs.org/base64-arraybuffer
npm http request GET https://registry.npmjs.org/blob
npm http request GET https://registry.npmjs.org/utf8
npm http 304 https://registry.npmjs.org/arraybuffer.slice
npm http 304 https://registry.npmjs.org/base64-arraybuffer
npm http 304 https://registry.npmjs.org/blob
npm http 304 https://registry.npmjs.org/utf8
npm http fetch GET https://github.com/component/global/archive/v2.0.1.tar.gz
npm http fetch 200 https://github.com/component/global/archive/v2.0.1.tar.gz
npm http request GET https://registry.npmjs.org/better-assert
npm http 304 https://registry.npmjs.org/better-assert
npm http request GET https://registry.npmjs.org/callsite
npm http 304 https://registry.npmjs.org/callsite
npm http request GET https://registry.npmjs.org/options
npm http request GET https://registry.npmjs.org/ultron
npm http 304 https://registry.npmjs.org/options
npm http 304 https://registry.npmjs.org/ultron
npm http request GET https://registry.npmjs.org/json3
npm http request GET https://registry.npmjs.org/benchmark
npm http 304 https://registry.npmjs.org/benchmark
npm http 304 https://registry.npmjs.org/json3
npm http request GET https://registry.npmjs.org/superagent
npm http 200 https://registry.npmjs.org/superagent
npm http fetch GET https://registry.npmjs.org/superagent/-/superagent-1.3.0.tgz
npm http fetch 200 https://registry.npmjs.org/superagent/-/superagent-1.3.0.tgz
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/methods
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/form-data
npm http request GET https://registry.npmjs.org/formidable
npm http request GET https://registry.npmjs.org/cookiejar
npm http request GET https://registry.npmjs.org/reduce-component
npm http 304 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/qs
npm http 200 https://registry.npmjs.org/methods
npm http 200 https://registry.npmjs.org/formidable
npm http fetch GET https://registry.npmjs.org/form-data/-/form-data-0.2.0.tgz
npm http fetch GET https://registry.npmjs.org/extend/-/extend-1.2.1.tgz
npm http fetch GET https://registry.npmjs.org/methods/-/methods-1.0.1.tgz
npm http 304 https://registry.npmjs.org/reduce-component
npm http 200 https://registry.npmjs.org/cookiejar
npm http fetch GET https://registry.npmjs.org/formidable/-/formidable-1.0.14.tgz
npm http fetch GET https://registry.npmjs.org/cookiejar/-/cookiejar-2.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/form-data/-/form-data-0.2.0.tgz
npm http fetch 200 https://registry.npmjs.org/extend/-/extend-1.2.1.tgz
npm http fetch 200 https://registry.npmjs.org/methods/-/methods-1.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/formidable/-/formidable-1.0.14.tgz
npm http fetch 200 https://registry.npmjs.org/cookiejar/-/cookiejar-2.0.1.tgz
npm http request GET https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/combined-stream
npm http request GET https://registry.npmjs.org/mime-types
npm http 304 https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/mime-types
npm http request GET https://registry.npmjs.org/delayed-stream
npm http 304 https://registry.npmjs.org/delayed-stream
npm http request GET https://registry.npmjs.org/mime-db
npm http 304 https://registry.npmjs.org/mime-db
npm http request GET https://registry.npmjs.org/defined
npm http request GET https://registry.npmjs.org/resumer
npm http request GET https://registry.npmjs.org/object-inspect
npm http 200 https://registry.npmjs.org/defined
npm http 304 https://registry.npmjs.org/resumer
npm http 200 https://registry.npmjs.org/object-inspect
npm http fetch GET https://registry.npmjs.org/object-inspect/-/object-inspect-1.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/object-inspect/-/object-inspect-1.0.2.tgz
npm WARN prefer global jshint@2.9.2 should be installed with -g
npm WARN prefer global node-ninja@1.0.1 should be installed with -g
npm WARN prefer global node-gyp@3.3.1 should be installed with -g
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
Trace: [Error: Missing PFX or certificate + private key.]
    at process.tests (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/thaliTape.js:38:11)
    at process.emit (events.js:98:20)
    at Array.0 (/Users/thali/Github/Thali_CordovaPlugin/thali/node_modules/lie/lib/index.js:128:19)
    at nextTick (/Users/thali/Github/Thali_CordovaPlugin/thali/node_modules/immediate/lib/index.js:61:18)
    at process._tickCallback (node.js:917:13)
npm ERR! Test failed.  See above for more details.
