#### Test (Fail) 57924002 Build Logs


```


```

```
Already up-to-date.

From https://github.com/thaliproject/Thali_CordovaPlugin
   19324d6..ce356e3  vNext_yarong_501 -> origin/vNext_yarong_501

```

```
Your branch is up-to-date with 'origin/master'.
Branch vNext_tobe_issue355 set up to track remote branch vNext_tobe_issue355 from origin.
Merge made by the 'recursive' strategy.
 src/ios/MultipeerConnectivity/THEMultipeerClient.m |  58 +++++------
 .../MultipeerConnectivity/THEMultipeerManager.m    | 107 ++++++++++++++-------
 .../THEMultipeerPeerSession.h                      |   2 +
 .../THEMultipeerPeerSession.m                      |   5 +
 src/ios/THEPeerBluetooth.h                         |   2 +-
 .../TestAppTests/ThaliMultipleInstanceTests.m      | 107 +++++++++++++++++++++
 test/TestServer/UnitTestFramework.js               |   2 +-
 test/www/jxcore/bv_tests/testThaliMobileNative.js  |   5 +
 8 files changed, 224 insertions(+), 64 deletions(-)

Already on 'master'
Switched to a new branch 'vNext_tobe_issue355'
Note: checking out 'ce356e3'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at ce356e3... Merge remote-tracking branch 'origin/vNext' into vNext_yarong_501

```

```
node-uuid@1.4.7 node_modules/node-uuid

tape@1.1.1 node_modules/tape
├── deep-equal@0.0.0
├── defined@0.0.0
├── jsonify@0.0.0
└── through@2.3.8

winston@2.1.1 node_modules/winston
├── cycle@1.0.3
├── stack-trace@0.0.9
├── eyes@0.1.8
├── isstream@0.1.2
├── pkginfo@0.3.1
├── async@1.0.0
└── colors@1.0.3

express@4.13.4 node_modules/express
├── escape-html@1.0.3
├── array-flatten@1.1.1
├── utils-merge@1.0.0
├── cookie-signature@1.0.6
├── merge-descriptors@1.0.1
├── fresh@0.3.0
├── methods@1.1.2
├── range-parser@1.0.3
├── vary@1.0.1
├── path-to-regexp@0.1.7
├── cookie@0.1.5
├── parseurl@1.3.1
├── content-type@1.0.1
├── etag@1.7.0
├── content-disposition@0.5.1
├── serve-static@1.10.2
├── depd@1.1.0
├── finalhandler@0.4.1 (unpipe@1.0.0)
├── qs@4.0.0
├── on-finished@2.3.0 (ee-first@1.1.1)
├── proxy-addr@1.0.10 (forwarded@0.1.0, ipaddr.js@1.0.5)
├── send@0.13.1 (destroy@1.0.4, statuses@1.2.1, ms@0.7.1, mime@1.3.4, http-errors@1.3.1)
├── debug@2.2.0 (ms@0.7.1)
├── accepts@1.2.13 (negotiator@0.5.3, mime-types@2.1.9)
└── type-is@1.6.11 (media-typer@0.3.0, mime-types@2.1.9)

socket.io@1.4.5 node_modules/socket.io
├── has-binary@0.1.7 (isarray@0.0.1)
├── debug@2.2.0 (ms@0.7.1)
├── socket.io-parser@2.2.6 (component-emitter@1.1.2, isarray@0.0.1, json3@3.3.2, benchmark@1.0.0)
├── engine.io@1.6.8 (base64id@0.1.0, engine.io-parser@1.2.4, ws@1.0.1, accepts@1.1.4)
└── socket.io-adapter@0.4.0 (socket.io-parser@2.2.2)

socket.io-client@1.4.5 node_modules/socket.io-client
├── indexof@0.0.1
├── to-array@0.1.4
├── component-emitter@1.2.0
├── component-bind@1.0.0
├── backo2@1.0.2
├── object-component@0.0.3
├── has-binary@0.1.7 (isarray@0.0.1)
├── parseuri@0.0.4 (better-assert@1.0.2)
├── debug@2.2.0 (ms@0.7.1)
├── engine.io-client@1.6.8 (yeast@0.1.2, component-inherit@0.0.3, has-cors@1.1.0, component-emitter@1.1.2, xmlhttprequest-ssl@1.5.1, parseqs@0.0.2, parsejson@0.0.1, engine.io-parser@1.2.4, ws@1.0.1)
└── socket.io-parser@2.2.6 (component-emitter@1.1.2, json3@3.3.2, isarray@0.0.1, benchmark@1.0.0)

fs-extra-promise@0.2.1 node_modules/fs-extra-promise
├── bluebird@2.10.2
└── fs-extra@0.24.0 (path-is-absolute@1.0.0, jsonfile@2.2.3, graceful-fs@4.1.2, rimraf@2.5.1)

lie@3.0.2 node_modules/lie
├── immediate@3.0.5
├── inline-process-browser@1.0.0 (through2@0.6.5, falafel@1.2.0)
├── unreachable-branch-transform@0.3.0 (esmangle-evaluator@1.0.0, through2@0.6.5, recast@0.10.43)
└── es3ify@0.1.4 (through@2.3.8, jstransform@3.0.0, esprima-fb@3001.1.0-dev-harmony-fb)

> thali@2.1.0 postinstall /Users/thali/Github/Thali_CordovaPlugin/thali
> jx installCordovaPlugin.js

We believe we are in a clone of the GitHub Repo so we will not install Cordova dependencies

> thali@2.1.0 prepublish /Users/thali/Github/Thali_CordovaPlugin/thali
> jx install/prePublishThaliCordovaPlugin.js

urlsafe-base64@1.0.0 node_modules/urlsafe-base64

ip@1.1.0 node_modules/ip

node-uuid@1.4.7 node_modules/node-uuid

node-ssdp@2.6.5 node_modules/node-ssdp

multiplex@6.6.1 node_modules/multiplex
├── varint@4.0.0
├── xtend@4.0.1
├── duplexify@3.4.2 (end-of-stream@1.0.0)
└── readable-stream@2.0.5 (process-nextick-args@1.0.6, util-deprecate@1.0.2, isarray@0.0.1, string_decoder@0.10.31, core-util-is@1.0.2, inherits@2.0.1)

winston@1.1.2 node_modules/winston
├── cycle@1.0.3
├── stack-trace@0.0.9
├── eyes@0.1.8
├── isstream@0.1.2
├── pkginfo@0.3.1
├── async@1.0.0
└── colors@1.0.3

body-parser@1.14.2 node_modules/body-parser
├── content-type@1.0.1
├── bytes@2.2.0
├── depd@1.1.0
├── on-finished@2.3.0 (ee-first@1.1.1)
├── raw-body@2.1.5 (unpipe@1.0.0)
├── http-errors@1.3.1 (inherits@2.0.1, statuses@1.2.1)
├── debug@2.2.0 (ms@0.7.1)
├── qs@5.2.0
├── iconv-lite@0.4.13
└── type-is@1.6.11 (media-typer@0.3.0, mime-types@2.1.9)

request@2.69.0 node_modules/request
├── is-typedarray@1.0.0
├── aws-sign2@0.6.0
├── forever-agent@0.6.1
├── caseless@0.11.0
├── stringstream@0.0.5
├── tunnel-agent@0.4.2
├── oauth-sign@0.8.1
├── isstream@0.1.2
├── json-stringify-safe@5.0.1
├── extend@3.0.0
├── combined-stream@1.0.5 (delayed-stream@1.0.0)
├── qs@6.0.2
├── aws4@1.2.1 (lru-cache@2.7.3)
├── mime-types@2.1.9 (mime-db@1.21.0)
├── tough-cookie@2.2.1
├── form-data@1.0.0-rc3 (async@1.5.2)
├── bl@1.0.1 (readable-stream@2.0.5)
├── http-signature@1.1.1 (assert-plus@0.2.0, jsprim@1.2.2, sshpk@1.7.3)
├── hawk@3.1.3 (cryptiles@2.0.5, sntp@1.0.9, boom@2.10.1, hoek@2.16.3)
└── har-validator@2.0.6 (pinkie-promise@2.0.0, commander@2.9.0, chalk@1.1.1, is-my-json-valid@2.12.4)

javascript-state-machine@2.3.5 node_modules/javascript-state-machine

express@4.13.3 node_modules/express
├── array-flatten@1.1.1
├── escape-html@1.0.2
├── merge-descriptors@1.0.0
├── utils-merge@1.0.0
├── cookie-signature@1.0.6
├── cookie@0.1.3
├── methods@1.1.2
├── fresh@0.3.0
├── range-parser@1.0.3
├── vary@1.0.1
├── path-to-regexp@0.1.7
├── parseurl@1.3.1
├── etag@1.7.0
├── content-disposition@0.5.0
├── content-type@1.0.1
├── depd@1.0.1
├── on-finished@2.3.0 (ee-first@1.1.1)
├── finalhandler@0.4.0 (unpipe@1.0.0)
├── qs@4.0.0
├── proxy-addr@1.0.10 (forwarded@0.1.0, ipaddr.js@1.0.5)
├── send@0.13.0 (destroy@1.0.3, statuses@1.2.1, ms@0.7.1, mime@1.3.4, http-errors@1.3.1)
├── debug@2.2.0 (ms@0.7.1)
├── serve-static@1.10.2 (escape-html@1.0.3, send@0.13.1)
├── accepts@1.2.13 (negotiator@0.5.3, mime-types@2.1.9)
└── type-is@1.6.11 (media-typer@0.3.0, mime-types@2.1.9)

lie@3.0.2 node_modules/lie
├── immediate@3.0.5
├── inline-process-browser@1.0.0 (through2@0.6.5, falafel@1.2.0)
├── unreachable-branch-transform@0.3.0 (esmangle-evaluator@1.0.0, through2@0.6.5, recast@0.10.43)
└── es3ify@0.1.4 (through@2.3.8, jstransform@3.0.0, esprima-fb@3001.1.0-dev-harmony-fb)

jsdoc@3.4.0 node_modules/jsdoc
├── escape-string-regexp@1.0.4
├── strip-json-comments@1.0.4
├── async@1.4.2
├── taffydb@2.6.2
├── underscore@1.8.3
├── wrench@1.5.8
├── marked@0.3.5
├── js2xmlparser@1.0.0
├── requizzle@0.2.1 (underscore@1.6.0)
├── espree@2.2.5
├── bluebird@2.9.34
└── catharsis@0.8.7 (underscore-contrib@0.3.0)

> thali@2.1.0 postinstall /Users/thali/Github/Thali_CordovaPlugin/thali
> jx installCordovaPlugin.js

We believe we are in a clone of the GitHub Repo so we will not install Cordova dependencies

> thali@2.1.0 prepublish /Users/thali/Github/Thali_CordovaPlugin/thali
> jx install/prePublishThaliCordovaPlugin.js

/usr/local/lib/node_modules/thali -> /Users/thali/Github/Thali_CordovaPlugin/thali
-e [0;31mcompilation aborted
 [0m
build aborted
 [0m

npm WARN package.json thali-test-server@0.0.1 No repository field.
npm http GET https://registry.npmjs.org/express
npm http GET https://registry.npmjs.org/fs-extra-promise
npm http GET https://registry.npmjs.org/lie
npm http GET https://registry.npmjs.org/socket.io
npm http GET https://registry.npmjs.org/winston
npm http GET https://registry.npmjs.org/socket.io-client
npm http GET https://registry.npmjs.org/node-uuid
npm http GET https://registry.npmjs.org/tape
npm http 200 https://registry.npmjs.org/lie
npm http 200 https://registry.npmjs.org/winston
npm http 200 https://registry.npmjs.org/socket.io
npm http 200 https://registry.npmjs.org/socket.io-client
npm http GET https://registry.npmjs.org/socket.io/-/socket.io-1.4.5.tgz
npm http 200 https://registry.npmjs.org/node-uuid
npm http GET https://registry.npmjs.org/lie/-/lie-3.0.2.tgz
npm http GET https://registry.npmjs.org/winston/-/winston-2.1.1.tgz
npm http GET https://registry.npmjs.org/socket.io-client/-/socket.io-client-1.4.5.tgz
npm http GET https://registry.npmjs.org/node-uuid/-/node-uuid-1.4.7.tgz
npm http 200 https://registry.npmjs.org/express
npm http 200 https://registry.npmjs.org/tape
npm http 200 https://registry.npmjs.org/socket.io/-/socket.io-1.4.5.tgz
npm http 200 https://registry.npmjs.org/lie/-/lie-3.0.2.tgz
npm http GET https://registry.npmjs.org/express/-/express-4.13.4.tgz
npm http GET https://registry.npmjs.org/tape/-/tape-1.1.1.tgz
npm http 200 https://registry.npmjs.org/winston/-/winston-2.1.1.tgz
npm http 200 https://registry.npmjs.org/socket.io-client/-/socket.io-client-1.4.5.tgz
npm http 200 https://registry.npmjs.org/node-uuid/-/node-uuid-1.4.7.tgz
npm http 200 https://registry.npmjs.org/fs-extra-promise
npm http 200 https://registry.npmjs.org/tape/-/tape-1.1.1.tgz
npm http GET https://registry.npmjs.org/fs-extra-promise/-/fs-extra-promise-0.2.1.tgz
npm http 200 https://registry.npmjs.org/express/-/express-4.13.4.tgz
npm http 200 https://registry.npmjs.org/fs-extra-promise/-/fs-extra-promise-0.2.1.tgz
npm http GET https://registry.npmjs.org/fs-extra
npm http GET https://registry.npmjs.org/bluebird
npm http GET https://registry.npmjs.org/socket.io-adapter
npm http GET https://registry.npmjs.org/has-binary
npm http GET https://registry.npmjs.org/debug
npm http GET https://registry.npmjs.org/engine.io
npm http GET https://registry.npmjs.org/socket.io-parser
npm http GET https://registry.npmjs.org/es3ify
npm http GET https://registry.npmjs.org/immediate
npm http GET https://registry.npmjs.org/inline-process-browser
npm http GET https://registry.npmjs.org/unreachable-branch-transform
npm http GET https://registry.npmjs.org/jsonify
npm http GET https://registry.npmjs.org/defined
npm http GET https://registry.npmjs.org/deep-equal
npm http GET https://registry.npmjs.org/through
npm http GET https://registry.npmjs.org/content-disposition
npm http GET https://registry.npmjs.org/content-type
npm http GET https://registry.npmjs.org/cookie
npm http GET https://registry.npmjs.org/cookie-signature
npm http 200 https://registry.npmjs.org/socket.io-adapter
npm http GET https://registry.npmjs.org/debug
npm http GET https://registry.npmjs.org/depd
npm http 200 https://registry.npmjs.org/has-binary
npm http 200 https://registry.npmjs.org/fs-extra
npm http GET https://registry.npmjs.org/escape-html
npm http GET https://registry.npmjs.org/etag
npm http GET https://registry.npmjs.org/finalhandler
npm http GET https://registry.npmjs.org/fresh
npm http GET https://registry.npmjs.org/merge-descriptors
npm http GET https://registry.npmjs.org/methods
npm http GET https://registry.npmjs.org/on-finished
npm http GET https://registry.npmjs.org/parseurl
npm http GET https://registry.npmjs.org/path-to-regexp
npm http GET https://registry.npmjs.org/proxy-addr
npm http GET https://registry.npmjs.org/range-parser
npm http GET https://registry.npmjs.org/send
npm http GET https://registry.npmjs.org/serve-static
npm http GET https://registry.npmjs.org/type-is
npm http GET https://registry.npmjs.org/utils-merge
npm http GET https://registry.npmjs.org/vary
npm http GET https://registry.npmjs.org/accepts
npm http GET https://registry.npmjs.org/array-flatten
npm http 200 https://registry.npmjs.org/socket.io-parser
npm http 200 https://registry.npmjs.org/debug
npm http 200 https://registry.npmjs.org/es3ify
npm http 200 https://registry.npmjs.org/bluebird
npm http 200 https://registry.npmjs.org/inline-process-browser
npm http GET https://registry.npmjs.org/qs
npm http 200 https://registry.npmjs.org/unreachable-branch-transform
npm http 200 https://registry.npmjs.org/immediate
npm http 304 https://registry.npmjs.org/jsonify
npm http 200 https://registry.npmjs.org/engine.io
npm http GET https://registry.npmjs.org/socket.io-adapter/-/socket.io-adapter-0.4.0.tgz
npm http 304 https://registry.npmjs.org/defined
npm http 200 https://registry.npmjs.org/deep-equal
npm http 200 https://registry.npmjs.org/through
npm http 200 https://registry.npmjs.org/content-disposition
npm http GET https://registry.npmjs.org/has-binary/-/has-binary-0.1.7.tgz
npm http 200 https://registry.npmjs.org/content-type
npm http GET https://registry.npmjs.org/debug/-/debug-2.2.0.tgz
npm http GET https://registry.npmjs.org/socket.io-parser/-/socket.io-parser-2.2.6.tgz
npm http 200 https://registry.npmjs.org/cookie
npm http 200 https://registry.npmjs.org/cookie-signature
npm http 200 https://registry.npmjs.org/debug
npm http 200 https://registry.npmjs.org/depd
npm http 200 https://registry.npmjs.org/escape-html
npm http GET https://registry.npmjs.org/fs-extra/-/fs-extra-0.24.0.tgz
npm http 200 https://registry.npmjs.org/etag
npm http 200 https://registry.npmjs.org/finalhandler
npm http GET https://registry.npmjs.org/es3ify/-/es3ify-0.1.4.tgz
npm http 200 https://registry.npmjs.org/fresh
npm http 200 https://registry.npmjs.org/merge-descriptors
npm http 200 https://registry.npmjs.org/methods
npm http GET https://registry.npmjs.org/bluebird/-/bluebird-2.10.2.tgz
npm http 200 https://registry.npmjs.org/on-finished
npm http 200 https://registry.npmjs.org/parseurl
npm http GET https://registry.npmjs.org/inline-process-browser/-/inline-process-browser-1.0.0.tgz
npm http GET https://registry.npmjs.org/engine.io-client
npm http GET https://registry.npmjs.org/component-bind
npm http GET https://registry.npmjs.org/component-emitter
npm http GET https://registry.npmjs.org/object-component
npm http GET https://registry.npmjs.org/parseuri
npm http GET https://registry.npmjs.org/to-array
npm http GET https://registry.npmjs.org/backo2
npm http GET https://registry.npmjs.org/unreachable-branch-transform/-/unreachable-branch-transform-0.3.0.tgz
npm http GET https://registry.npmjs.org/immediate/-/immediate-3.0.5.tgz
npm http 200 https://registry.npmjs.org/proxy-addr
npm http 200 https://registry.npmjs.org/range-parser
npm http GET https://registry.npmjs.org/engine.io/-/engine.io-1.6.8.tgz
npm http 200 https://registry.npmjs.org/path-to-regexp
npm http GET https://registry.npmjs.org/content-disposition/-/content-disposition-0.5.1.tgz
npm http GET https://registry.npmjs.org/indexof
npm http 200 https://registry.npmjs.org/serve-static
npm http 200 https://registry.npmjs.org/type-is
npm http 200 https://registry.npmjs.org/send
npm http 200 https://registry.npmjs.org/socket.io-adapter/-/socket.io-adapter-0.4.0.tgz
npm http 200 https://registry.npmjs.org/utils-merge
npm http 200 https://registry.npmjs.org/has-binary/-/has-binary-0.1.7.tgz
npm http 200 https://registry.npmjs.org/socket.io-parser/-/socket.io-parser-2.2.6.tgz
npm http 200 https://registry.npmjs.org/vary
npm http 200 https://registry.npmjs.org/debug/-/debug-2.2.0.tgz
npm http GET https://registry.npmjs.org/deep-equal/-/deep-equal-0.0.0.tgz
npm http 200 https://registry.npmjs.org/accepts
npm http 200 https://registry.npmjs.org/array-flatten
npm http 200 https://registry.npmjs.org/es3ify/-/es3ify-0.1.4.tgz
npm http GET https://registry.npmjs.org/cookie/-/cookie-0.1.5.tgz
npm http GET https://registry.npmjs.org/cookie-signature/-/cookie-signature-1.0.6.tgz
npm http 200 https://registry.npmjs.org/qs
npm http 200 https://registry.npmjs.org/component-bind
npm http 200 https://registry.npmjs.org/inline-process-browser/-/inline-process-browser-1.0.0.tgz
npm http GET https://registry.npmjs.org/content-type/-/content-type-1.0.1.tgz
npm http GET https://registry.npmjs.org/finalhandler/-/finalhandler-0.4.1.tgz
npm http 200 https://registry.npmjs.org/unreachable-branch-transform/-/unreachable-branch-transform-0.3.0.tgz
npm http 200 https://registry.npmjs.org/component-emitter
npm http 200 https://registry.npmjs.org/object-component
npm http 200 https://registry.npmjs.org/immediate/-/immediate-3.0.5.tgz
npm http GET https://registry.npmjs.org/depd/-/depd-1.1.0.tgz
npm http GET https://registry.npmjs.org/escape-html/-/escape-html-1.0.3.tgz
npm http GET https://registry.npmjs.org/fresh/-/fresh-0.3.0.tgz
npm http GET https://registry.npmjs.org/merge-descriptors/-/merge-descriptors-1.0.1.tgz
npm http 200 https://registry.npmjs.org/fs-extra/-/fs-extra-0.24.0.tgz
npm http 200 https://registry.npmjs.org/bluebird/-/bluebird-2.10.2.tgz
npm http GET https://registry.npmjs.org/etag/-/etag-1.7.0.tgz
npm http 200 https://registry.npmjs.org/parseuri
npm http 200 https://registry.npmjs.org/to-array
npm http 200 https://registry.npmjs.org/engine.io/-/engine.io-1.6.8.tgz
npm http 200 https://registry.npmjs.org/engine.io-client
npm http 200 https://registry.npmjs.org/backo2
npm http 200 https://registry.npmjs.org/content-disposition/-/content-disposition-0.5.1.tgz
npm http 304 https://registry.npmjs.org/indexof
npm http 200 https://registry.npmjs.org/deep-equal/-/deep-equal-0.0.0.tgz
npm http 200 https://registry.npmjs.org/cookie/-/cookie-0.1.5.tgz
npm http GET https://registry.npmjs.org/methods/-/methods-1.1.2.tgz
npm http 200 https://registry.npmjs.org/cookie-signature/-/cookie-signature-1.0.6.tgz
npm http GET https://registry.npmjs.org/on-finished/-/on-finished-2.3.0.tgz
npm http GET https://registry.npmjs.org/parseurl/-/parseurl-1.3.1.tgz
npm http GET https://registry.npmjs.org/path-to-regexp/-/path-to-regexp-0.1.7.tgz
npm http GET https://registry.npmjs.org/proxy-addr/-/proxy-addr-1.0.10.tgz
npm http GET https://registry.npmjs.org/range-parser/-/range-parser-1.0.3.tgz
npm http GET https://registry.npmjs.org/send/-/send-0.13.1.tgz
npm http GET https://registry.npmjs.org/utils-merge/-/utils-merge-1.0.0.tgz
npm http 200 https://registry.npmjs.org/content-type/-/content-type-1.0.1.tgz
npm http 200 https://registry.npmjs.org/finalhandler/-/finalhandler-0.4.1.tgz
npm http GET https://registry.npmjs.org/array-flatten/-/array-flatten-1.1.1.tgz
npm http 200 https://registry.npmjs.org/depd/-/depd-1.1.0.tgz
npm http GET https://registry.npmjs.org/serve-static/-/serve-static-1.10.2.tgz
npm http GET https://registry.npmjs.org/type-is/-/type-is-1.6.11.tgz
npm http GET https://registry.npmjs.org/qs/-/qs-4.0.0.tgz
npm http 200 https://registry.npmjs.org/escape-html/-/escape-html-1.0.3.tgz
npm http GET https://registry.npmjs.org/vary/-/vary-1.0.1.tgz
npm http 200 https://registry.npmjs.org/fresh/-/fresh-0.3.0.tgz
npm http GET https://registry.npmjs.org/accepts/-/accepts-1.2.13.tgz
npm http GET https://registry.npmjs.org/component-bind/-/component-bind-1.0.0.tgz
npm http 200 https://registry.npmjs.org/merge-descriptors/-/merge-descriptors-1.0.1.tgz
npm http 200 https://registry.npmjs.org/etag/-/etag-1.7.0.tgz
npm http GET https://registry.npmjs.org/component-emitter/-/component-emitter-1.2.0.tgz
npm http 200 https://registry.npmjs.org/methods/-/methods-1.1.2.tgz
npm http GET https://registry.npmjs.org/object-component/-/object-component-0.0.3.tgz
npm http 200 https://registry.npmjs.org/on-finished/-/on-finished-2.3.0.tgz
npm http 200 https://registry.npmjs.org/parseurl/-/parseurl-1.3.1.tgz
npm http 200 https://registry.npmjs.org/path-to-regexp/-/path-to-regexp-0.1.7.tgz
npm http 200 https://registry.npmjs.org/proxy-addr/-/proxy-addr-1.0.10.tgz
npm http GET https://registry.npmjs.org/parseuri/-/parseuri-0.0.4.tgz
npm http GET https://registry.npmjs.org/to-array/-/to-array-0.1.4.tgz
npm http GET https://registry.npmjs.org/engine.io-client/-/engine.io-client-1.6.8.tgz
npm http 200 https://registry.npmjs.org/range-parser/-/range-parser-1.0.3.tgz
npm http GET https://registry.npmjs.org/backo2/-/backo2-1.0.2.tgz
npm http 200 https://registry.npmjs.org/send/-/send-0.13.1.tgz
npm http 200 https://registry.npmjs.org/utils-merge/-/utils-merge-1.0.0.tgz
npm http 200 https://registry.npmjs.org/array-flatten/-/array-flatten-1.1.1.tgz
npm http 200 https://registry.npmjs.org/serve-static/-/serve-static-1.10.2.tgz
npm http 200 https://registry.npmjs.org/type-is/-/type-is-1.6.11.tgz
npm http 200 https://registry.npmjs.org/vary/-/vary-1.0.1.tgz
npm http 200 https://registry.npmjs.org/qs/-/qs-4.0.0.tgz
npm http 200 https://registry.npmjs.org/accepts/-/accepts-1.2.13.tgz
npm http 200 https://registry.npmjs.org/component-emitter/-/component-emitter-1.2.0.tgz
npm http 200 https://registry.npmjs.org/component-bind/-/component-bind-1.0.0.tgz
npm http 200 https://registry.npmjs.org/object-component/-/object-component-0.0.3.tgz
npm http 200 https://registry.npmjs.org/parseuri/-/parseuri-0.0.4.tgz
npm http 200 https://registry.npmjs.org/to-array/-/to-array-0.1.4.tgz
npm http 200 https://registry.npmjs.org/engine.io-client/-/engine.io-client-1.6.8.tgz
npm http 200 https://registry.npmjs.org/backo2/-/backo2-1.0.2.tgz
npm http GET https://registry.npmjs.org/stack-trace
npm http GET https://registry.npmjs.org/colors
npm http GET https://registry.npmjs.org/cycle
npm http GET https://registry.npmjs.org/eyes
npm http GET https://registry.npmjs.org/isstream
npm http GET https://registry.npmjs.org/pkginfo
npm http GET https://registry.npmjs.org/async
npm http 200 https://registry.npmjs.org/stack-trace
npm http 200 https://registry.npmjs.org/isstream
npm http 200 https://registry.npmjs.org/eyes
npm http 200 https://registry.npmjs.org/cycle
npm http 200 https://registry.npmjs.org/colors
npm http 200 https://registry.npmjs.org/pkginfo
npm http 200 https://registry.npmjs.org/async
npm http GET https://registry.npmjs.org/isstream/-/isstream-0.1.2.tgz
npm http GET https://registry.npmjs.org/stack-trace/-/stack-trace-0.0.9.tgz
npm http GET https://registry.npmjs.org/eyes/-/eyes-0.1.8.tgz
npm http GET https://registry.npmjs.org/cycle/-/cycle-1.0.3.tgz
npm http GET https://registry.npmjs.org/colors/-/colors-1.0.3.tgz
npm http GET https://registry.npmjs.org/pkginfo/-/pkginfo-0.3.1.tgz
npm http GET https://registry.npmjs.org/async/-/async-1.0.0.tgz
npm http GET https://registry.npmjs.org/falafel
npm http GET https://registry.npmjs.org/through2
npm http 200 https://registry.npmjs.org/eyes/-/eyes-0.1.8.tgz
npm http 200 https://registry.npmjs.org/isstream/-/isstream-0.1.2.tgz
npm http 200 https://registry.npmjs.org/stack-trace/-/stack-trace-0.0.9.tgz
npm http 200 https://registry.npmjs.org/pkginfo/-/pkginfo-0.3.1.tgz
npm http 200 https://registry.npmjs.org/cycle/-/cycle-1.0.3.tgz
npm http 200 https://registry.npmjs.org/colors/-/colors-1.0.3.tgz
npm http 200 https://registry.npmjs.org/async/-/async-1.0.0.tgz
npm http 200 https://registry.npmjs.org/falafel
npm http 200 https://registry.npmjs.org/through2
npm http GET https://registry.npmjs.org/esmangle-evaluator
npm http GET https://registry.npmjs.org/recast
npm http GET https://registry.npmjs.org/through2
npm http 200 https://registry.npmjs.org/esmangle-evaluator
npm http 304 https://registry.npmjs.org/through2
npm http GET https://registry.npmjs.org/falafel/-/falafel-1.2.0.tgz
npm http GET https://registry.npmjs.org/through2/-/through2-0.6.5.tgz
npm http 200 https://registry.npmjs.org/recast
npm http GET https://registry.npmjs.org/esprima-fb
npm http GET https://registry.npmjs.org/jstransform
npm http GET https://registry.npmjs.org/socket.io-parser/-/socket.io-parser-2.2.2.tgz
npm http GET https://registry.npmjs.org/better-assert
npm http GET https://registry.npmjs.org/isarray
npm http 200 https://registry.npmjs.org/through2/-/through2-0.6.5.tgz
npm http 200 https://registry.npmjs.org/falafel/-/falafel-1.2.0.tgz
npm http GET https://registry.npmjs.org/unpipe
npm http GET https://registry.npmjs.org/esmangle-evaluator/-/esmangle-evaluator-1.0.0.tgz
npm http 200 https://registry.npmjs.org/esprima-fb
npm http 200 https://registry.npmjs.org/jstransform
npm http 200 https://registry.npmjs.org/socket.io-parser/-/socket.io-parser-2.2.2.tgz
npm http GET https://registry.npmjs.org/recast/-/recast-0.10.43.tgz
npm http GET https://registry.npmjs.org/ee-first
npm http GET https://registry.npmjs.org/forwarded
npm http GET https://registry.npmjs.org/ipaddr.js
npm http 200 https://registry.npmjs.org/isarray
npm http GET https://registry.npmjs.org/media-typer
npm http GET https://registry.npmjs.org/negotiator
npm http 200 https://registry.npmjs.org/better-assert
npm http GET https://registry.npmjs.org/mime-types
npm http GET https://registry.npmjs.org/mime-types
npm http 200 https://registry.npmjs.org/unpipe
npm http 200 https://registry.npmjs.org/media-typer
npm http 200 https://registry.npmjs.org/esmangle-evaluator/-/esmangle-evaluator-1.0.0.tgz
npm http 200 https://registry.npmjs.org/ipaddr.js
npm http GET https://registry.npmjs.org/esprima-fb/-/esprima-fb-3001.0001.0000-dev-harmony-fb.tgz
npm http GET https://registry.npmjs.org/jstransform/-/jstransform-3.0.0.tgz
npm http GET https://registry.npmjs.org/isarray/-/isarray-0.0.1.tgz
npm http GET https://registry.npmjs.org/better-assert/-/better-assert-1.0.2.tgz
npm http 200 https://registry.npmjs.org/negotiator
npm http GET https://registry.npmjs.org/media-typer/-/media-typer-0.3.0.tgz
npm http GET https://registry.npmjs.org/unpipe/-/unpipe-1.0.0.tgz
npm http 200 https://registry.npmjs.org/recast/-/recast-0.10.43.tgz
npm http 200 https://registry.npmjs.org/mime-types
npm http 200 https://registry.npmjs.org/ee-first
npm http GET https://registry.npmjs.org/ipaddr.js/-/ipaddr.js-1.0.5.tgz
npm http 200 https://registry.npmjs.org/mime-types
npm http 200 https://registry.npmjs.org/forwarded
npm http 200 https://registry.npmjs.org/media-typer/-/media-typer-0.3.0.tgz
npm http 200 https://registry.npmjs.org/unpipe/-/unpipe-1.0.0.tgz
npm http GET https://registry.npmjs.org/negotiator/-/negotiator-0.5.3.tgz
npm http GET https://registry.npmjs.org/destroy
npm http GET https://registry.npmjs.org/http-errors
npm http GET https://registry.npmjs.org/ms
npm http GET https://registry.npmjs.org/statuses
npm http 200 https://registry.npmjs.org/isarray/-/isarray-0.0.1.tgz
npm http 200 https://registry.npmjs.org/ipaddr.js/-/ipaddr.js-1.0.5.tgz
npm http GET https://registry.npmjs.org/mime
npm http GET https://registry.npmjs.org/ee-first/-/ee-first-1.1.1.tgz
npm http GET https://registry.npmjs.org/mime-types/-/mime-types-2.1.9.tgz
npm http 200 https://registry.npmjs.org/jstransform/-/jstransform-3.0.0.tgz
npm http 200 https://registry.npmjs.org/esprima-fb/-/esprima-fb-3001.0001.0000-dev-harmony-fb.tgz
npm http 200 https://registry.npmjs.org/better-assert/-/better-assert-1.0.2.tgz
npm http 200 https://registry.npmjs.org/negotiator/-/negotiator-0.5.3.tgz
npm http GET https://registry.npmjs.org/forwarded/-/forwarded-0.1.0.tgz
npm http 200 https://registry.npmjs.org/mime-types/-/mime-types-2.1.9.tgz
npm http GET https://registry.npmjs.org/json3
npm http GET https://registry.npmjs.org/benchmark
npm http 200 https://registry.npmjs.org/statuses
npm http 200 https://registry.npmjs.org/ee-first/-/ee-first-1.1.1.tgz
npm http 200 https://registry.npmjs.org/ms
npm http 200 https://registry.npmjs.org/destroy
npm http 200 https://registry.npmjs.org/json3
npm http 200 https://registry.npmjs.org/http-errors
npm http 200 https://registry.npmjs.org/mime
npm http GET https://registry.npmjs.org/component-emitter/-/component-emitter-1.1.2.tgz
npm http 200 https://registry.npmjs.org/forwarded/-/forwarded-0.1.0.tgz
npm http GET https://registry.npmjs.org/statuses/-/statuses-1.2.1.tgz
npm http 200 https://registry.npmjs.org/benchmark
npm http GET https://registry.npmjs.org/ms/-/ms-0.7.1.tgz
npm http GET https://registry.npmjs.org/json3/-/json3-3.3.2.tgz
npm http GET https://registry.npmjs.org/mime/-/mime-1.3.4.tgz
npm http GET https://registry.npmjs.org/destroy/-/destroy-1.0.4.tgz
npm http GET https://registry.npmjs.org/http-errors/-/http-errors-1.3.1.tgz
npm http GET https://registry.npmjs.org/benchmark/-/benchmark-1.0.0.tgz
npm http 200 https://registry.npmjs.org/component-emitter/-/component-emitter-1.1.2.tgz
npm http 200 https://registry.npmjs.org/statuses/-/statuses-1.2.1.tgz
npm http 200 https://registry.npmjs.org/destroy/-/destroy-1.0.4.tgz
npm http 200 https://registry.npmjs.org/mime/-/mime-1.3.4.tgz
npm http 200 https://registry.npmjs.org/ms/-/ms-0.7.1.tgz
npm http 200 https://registry.npmjs.org/json3/-/json3-3.3.2.tgz
npm http 200 https://registry.npmjs.org/http-errors/-/http-errors-1.3.1.tgz
npm http 200 https://registry.npmjs.org/benchmark/-/benchmark-1.0.0.tgz
npm http GET https://registry.npmjs.org/readable-stream
npm http GET https://registry.npmjs.org/xtend
npm http 200 https://registry.npmjs.org/xtend
npm http 200 https://registry.npmjs.org/readable-stream
npm http GET https://registry.npmjs.org/callsite
npm http GET https://registry.npmjs.org/base64id
npm http GET https://registry.npmjs.org/ws
npm http GET https://registry.npmjs.org/engine.io-parser
npm http GET https://registry.npmjs.org/accepts
npm http GET https://registry.npmjs.org/mime-db
npm http GET https://registry.npmjs.org/debug
npm http GET https://registry.npmjs.org/component-emitter
npm http GET https://registry.npmjs.org/json3/-/json3-3.2.6.tgz
npm http 200 https://registry.npmjs.org/callsite
npm http GET https://registry.npmjs.org/foreach
npm http GET https://registry.npmjs.org/object-keys
npm http GET https://registry.npmjs.org/acorn
npm http 200 https://registry.npmjs.org/base64id
npm http GET https://registry.npmjs.org/callsite/-/callsite-1.0.0.tgz
npm http GET https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/debug
npm http 200 https://registry.npmjs.org/mime-db
npm http 200 https://registry.npmjs.org/engine.io-parser
npm http 304 https://registry.npmjs.org/component-emitter
npm http GET https://registry.npmjs.org/base64id/-/base64id-0.1.0.tgz
npm http 200 https://registry.npmjs.org/ws
npm http 200 https://registry.npmjs.org/foreach
npm http 200 https://registry.npmjs.org/object-keys
npm http 200 https://registry.npmjs.org/json3/-/json3-3.2.6.tgz
npm http 200 https://registry.npmjs.org/inherits
npm http GET https://registry.npmjs.org/accepts/-/accepts-1.1.4.tgz
npm http GET https://registry.npmjs.org/debug/-/debug-0.7.4.tgz
npm http 200 https://registry.npmjs.org/acorn
npm http GET https://registry.npmjs.org/engine.io-parser/-/engine.io-parser-1.2.4.tgz
npm http GET https://registry.npmjs.org/mime-db/-/mime-db-1.21.0.tgz
npm http GET https://registry.npmjs.org/ws/-/ws-1.0.1.tgz
npm http GET https://registry.npmjs.org/foreach/-/foreach-2.0.5.tgz
npm http GET https://registry.npmjs.org/object-keys/-/object-keys-1.0.9.tgz
npm http 200 https://registry.npmjs.org/callsite/-/callsite-1.0.0.tgz
npm http 200 https://registry.npmjs.org/engine.io-parser/-/engine.io-parser-1.2.4.tgz
npm http 200 https://registry.npmjs.org/base64id/-/base64id-0.1.0.tgz
npm http 200 https://registry.npmjs.org/ws/-/ws-1.0.1.tgz
npm http 200 https://registry.npmjs.org/mime-db/-/mime-db-1.21.0.tgz
npm http 200 https://registry.npmjs.org/accepts/-/accepts-1.1.4.tgz
npm http 200 https://registry.npmjs.org/foreach/-/foreach-2.0.5.tgz
npm http 200 https://registry.npmjs.org/object-keys/-/object-keys-1.0.9.tgz
npm http 200 https://registry.npmjs.org/debug/-/debug-0.7.4.tgz
npm http GET https://registry.npmjs.org/jsonfile
npm http GET https://registry.npmjs.org/graceful-fs
npm http GET https://registry.npmjs.org/path-is-absolute
npm http GET https://registry.npmjs.org/rimraf
npm http 200 https://registry.npmjs.org/jsonfile
npm http 200 https://registry.npmjs.org/path-is-absolute
npm http 200 https://registry.npmjs.org/graceful-fs
npm http 200 https://registry.npmjs.org/rimraf
npm http GET https://registry.npmjs.org/jsonfile/-/jsonfile-2.2.3.tgz
npm http GET https://registry.npmjs.org/graceful-fs/-/graceful-fs-4.1.2.tgz
npm http GET https://registry.npmjs.org/rimraf/-/rimraf-2.5.1.tgz
npm http GET https://registry.npmjs.org/negotiator/-/negotiator-0.4.9.tgz
npm http GET https://registry.npmjs.org/mime-types/-/mime-types-2.0.14.tgz
npm http GET https://registry.npmjs.org/core-util-is
npm http GET https://registry.npmjs.org/string_decoder
npm http 200 https://registry.npmjs.org/jsonfile/-/jsonfile-2.2.3.tgz
npm http GET https://registry.npmjs.org/has-cors
npm http GET https://registry.npmjs.org/xmlhttprequest-ssl
npm http GET https://registry.npmjs.org/parsejson
npm http GET https://registry.npmjs.org/parseqs
npm http 200 https://registry.npmjs.org/graceful-fs/-/graceful-fs-4.1.2.tgz
npm http GET https://registry.npmjs.org/component-inherit
npm http GET https://registry.npmjs.org/yeast
npm http 200 https://registry.npmjs.org/rimraf/-/rimraf-2.5.1.tgz
npm http 200 https://registry.npmjs.org/negotiator/-/negotiator-0.4.9.tgz
npm http 200 https://registry.npmjs.org/mime-types/-/mime-types-2.0.14.tgz
npm http 200 https://registry.npmjs.org/core-util-is
npm http 200 https://registry.npmjs.org/string_decoder
npm http 200 https://registry.npmjs.org/parseqs
npm http 200 https://registry.npmjs.org/component-inherit
npm http 200 https://registry.npmjs.org/has-cors
npm http 200 https://registry.npmjs.org/parsejson
npm http 200 https://registry.npmjs.org/xmlhttprequest-ssl
npm http 200 https://registry.npmjs.org/yeast
npm http GET https://registry.npmjs.org/core-util-is/-/core-util-is-1.0.2.tgz
npm http GET https://registry.npmjs.org/parseqs/-/parseqs-0.0.2.tgz
npm http GET https://registry.npmjs.org/component-inherit/-/component-inherit-0.0.3.tgz
npm http GET https://registry.npmjs.org/parsejson/-/parsejson-0.0.1.tgz
npm http GET https://registry.npmjs.org/has-cors/-/has-cors-1.1.0.tgz
npm http GET https://registry.npmjs.org/xmlhttprequest-ssl/-/xmlhttprequest-ssl-1.5.1.tgz
npm http GET https://registry.npmjs.org/yeast/-/yeast-0.1.2.tgz
npm http GET https://registry.npmjs.org/base64-arraybuffer
npm http GET https://registry.npmjs.org/blob
npm http GET https://registry.npmjs.org/utf8
npm http GET https://registry.npmjs.org/after
npm http GET https://registry.npmjs.org/arraybuffer.slice
npm http GET https://registry.npmjs.org/has-binary
npm http GET https://registry.npmjs.org/base62
npm http GET https://registry.npmjs.org/source-map
npm http 200 https://registry.npmjs.org/core-util-is/-/core-util-is-1.0.2.tgz
npm http 200 https://registry.npmjs.org/component-inherit/-/component-inherit-0.0.3.tgz
npm http 200 https://registry.npmjs.org/parseqs/-/parseqs-0.0.2.tgz
npm http 200 https://registry.npmjs.org/parsejson/-/parsejson-0.0.1.tgz
npm http 200 https://registry.npmjs.org/has-cors/-/has-cors-1.1.0.tgz
npm http GET https://registry.npmjs.org/private
npm http GET https://registry.npmjs.org/ast-types
npm http 200 https://registry.npmjs.org/xmlhttprequest-ssl/-/xmlhttprequest-ssl-1.5.1.tgz
npm http 200 https://registry.npmjs.org/yeast/-/yeast-0.1.2.tgz
npm http GET https://registry.npmjs.org/source-map
npm http GET https://registry.npmjs.org/esprima-fb/-/esprima-fb-15001.1001.0-dev-harmony-fb.tgz
npm http GET https://registry.npmjs.org/glob
npm http 200 https://registry.npmjs.org/base64-arraybuffer
npm http 200 https://registry.npmjs.org/blob
npm http 200 https://registry.npmjs.org/arraybuffer.slice
npm http 200 https://registry.npmjs.org/utf8
npm http 304 https://registry.npmjs.org/has-binary
npm http 200 https://registry.npmjs.org/base62
npm http 200 https://registry.npmjs.org/after
npm http 200 https://registry.npmjs.org/private
npm http GET https://registry.npmjs.org/base64-arraybuffer/-/base64-arraybuffer-0.1.2.tgz
npm http GET https://registry.npmjs.org/blob/-/blob-0.0.4.tgz
npm http GET https://registry.npmjs.org/arraybuffer.slice/-/arraybuffer.slice-0.0.6.tgz
npm http GET https://registry.npmjs.org/utf8/-/utf8-2.1.0.tgz
npm http GET https://registry.npmjs.org/has-binary/-/has-binary-0.1.6.tgz
npm http GET https://registry.npmjs.org/base62/-/base62-0.1.1.tgz
npm http GET https://registry.npmjs.org/mime-db/-/mime-db-1.12.0.tgz
npm http GET https://registry.npmjs.org/after/-/after-0.8.1.tgz
npm http 200 https://registry.npmjs.org/source-map
npm http GET https://registry.npmjs.org/private/-/private-0.1.6.tgz
npm http 200 https://registry.npmjs.org/glob
npm http 200 https://registry.npmjs.org/ast-types
npm http 200 https://registry.npmjs.org/source-map
npm http 200 https://registry.npmjs.org/esprima-fb/-/esprima-fb-15001.1001.0-dev-harmony-fb.tgz
npm http 200 https://registry.npmjs.org/base64-arraybuffer/-/base64-arraybuffer-0.1.2.tgz
npm http GET https://registry.npmjs.org/source-map/-/source-map-0.1.31.tgz
npm http 200 https://registry.npmjs.org/arraybuffer.slice/-/arraybuffer.slice-0.0.6.tgz
npm http GET https://registry.npmjs.org/ast-types/-/ast-types-0.8.15.tgz
npm http GET https://registry.npmjs.org/glob/-/glob-6.0.4.tgz
npm http 200 https://registry.npmjs.org/has-binary/-/has-binary-0.1.6.tgz
npm http GET https://registry.npmjs.org/source-map/-/source-map-0.5.3.tgz
npm http 200 https://registry.npmjs.org/blob/-/blob-0.0.4.tgz
npm http 200 https://registry.npmjs.org/utf8/-/utf8-2.1.0.tgz
npm http 200 https://registry.npmjs.org/base62/-/base62-0.1.1.tgz
npm http 200 https://registry.npmjs.org/after/-/after-0.8.1.tgz
npm http 200 https://registry.npmjs.org/private/-/private-0.1.6.tgz
npm http 200 https://registry.npmjs.org/source-map/-/source-map-0.1.31.tgz
npm http 200 https://registry.npmjs.org/mime-db/-/mime-db-1.12.0.tgz
npm http 200 https://registry.npmjs.org/ast-types/-/ast-types-0.8.15.tgz
npm http 200 https://registry.npmjs.org/glob/-/glob-6.0.4.tgz
npm http 200 https://registry.npmjs.org/source-map/-/source-map-0.5.3.tgz
npm http GET https://registry.npmjs.org/options
npm http GET https://registry.npmjs.org/ultron
npm http 200 https://registry.npmjs.org/options
npm http 200 https://registry.npmjs.org/ultron
npm http GET https://registry.npmjs.org/options/-/options-0.0.6.tgz
npm http GET https://registry.npmjs.org/ultron/-/ultron-1.0.2.tgz
npm http 200 https://registry.npmjs.org/ultron/-/ultron-1.0.2.tgz
npm http 200 https://registry.npmjs.org/options/-/options-0.0.6.tgz
npm http GET https://registry.npmjs.org/once
npm http GET https://registry.npmjs.org/inflight
npm http GET https://registry.npmjs.org/minimatch
npm http 200 https://registry.npmjs.org/once
npm http 200 https://registry.npmjs.org/inflight
npm http GET https://registry.npmjs.org/once/-/once-1.3.3.tgz
npm http 200 https://registry.npmjs.org/minimatch
npm http GET https://registry.npmjs.org/minimatch/-/minimatch-3.0.0.tgz
npm http 200 https://registry.npmjs.org/once/-/once-1.3.3.tgz
npm http 200 https://registry.npmjs.org/minimatch/-/minimatch-3.0.0.tgz
npm http GET https://registry.npmjs.org/wrappy
npm http GET https://registry.npmjs.org/brace-expansion
npm http GET https://registry.npmjs.org/amdefine
npm http 200 https://registry.npmjs.org/wrappy
npm http 200 https://registry.npmjs.org/brace-expansion
npm http GET https://registry.npmjs.org/brace-expansion/-/brace-expansion-1.1.2.tgz
npm http 200 https://registry.npmjs.org/amdefine
npm http 200 https://registry.npmjs.org/brace-expansion/-/brace-expansion-1.1.2.tgz
npm http GET https://registry.npmjs.org/concat-map
npm http GET https://registry.npmjs.org/balanced-match
npm http 200 https://registry.npmjs.org/concat-map
npm http GET https://registry.npmjs.org/concat-map/-/concat-map-0.0.1.tgz
npm http 200 https://registry.npmjs.org/balanced-match
npm http GET https://registry.npmjs.org/balanced-match/-/balanced-match-0.3.0.tgz
npm http 200 https://registry.npmjs.org/concat-map/-/concat-map-0.0.1.tgz
npm http 200 https://registry.npmjs.org/balanced-match/-/balanced-match-0.3.0.tgz
npm WARN package.json thali@2.1.0 No README data
npm http GET https://registry.npmjs.org/body-parser
npm http GET https://registry.npmjs.org/ip
npm http GET https://registry.npmjs.org/javascript-state-machine
npm http GET https://registry.npmjs.org/multiplex
npm http GET https://registry.npmjs.org/node-ssdp
npm http GET https://registry.npmjs.org/urlsafe-base64
npm http GET https://registry.npmjs.org/jsdoc
npm http GET https://registry.npmjs.org/express
npm http GET https://registry.npmjs.org/node-uuid
npm http GET https://registry.npmjs.org/winston
npm http GET https://registry.npmjs.org/lie
npm http GET https://registry.npmjs.org/request
npm http 200 https://registry.npmjs.org/ip
npm http GET https://registry.npmjs.org/ip/-/ip-1.1.0.tgz
npm http 200 https://registry.npmjs.org/body-parser
npm http GET https://registry.npmjs.org/body-parser/-/body-parser-1.14.2.tgz
npm http 200 https://registry.npmjs.org/jsdoc
npm http GET https://registry.npmjs.org/jsdoc/-/jsdoc-3.4.0.tgz
npm http 304 https://registry.npmjs.org/express
npm http GET https://registry.npmjs.org/express/-/express-4.13.3.tgz
npm http 200 https://registry.npmjs.org/ip/-/ip-1.1.0.tgz
npm http 304 https://registry.npmjs.org/node-uuid
npm http 200 https://registry.npmjs.org/urlsafe-base64
npm http GET https://registry.npmjs.org/urlsafe-base64/-/urlsafe-base64-1.0.0.tgz
npm http 304 https://registry.npmjs.org/winston
npm http 304 https://registry.npmjs.org/lie
npm http GET https://registry.npmjs.org/winston/-/winston-1.1.2.tgz
npm http 200 https://registry.npmjs.org/body-parser/-/body-parser-1.14.2.tgz
npm http 200 https://registry.npmjs.org/jsdoc/-/jsdoc-3.4.0.tgz
npm http 200 https://registry.npmjs.org/request
npm http GET https://registry.npmjs.org/request/-/request-2.69.0.tgz
npm http 200 https://registry.npmjs.org/express/-/express-4.13.3.tgz
npm http 200 https://registry.npmjs.org/javascript-state-machine
npm http GET https://registry.npmjs.org/javascript-state-machine/-/javascript-state-machine-2.3.5.tgz
npm http 200 https://registry.npmjs.org/urlsafe-base64/-/urlsafe-base64-1.0.0.tgz
npm http 200 https://registry.npmjs.org/winston/-/winston-1.1.2.tgz
npm http 200 https://registry.npmjs.org/multiplex
npm http GET https://registry.npmjs.org/multiplex/-/multiplex-6.6.1.tgz
npm http 200 https://registry.npmjs.org/request/-/request-2.69.0.tgz
npm http 200 https://registry.npmjs.org/javascript-state-machine/-/javascript-state-machine-2.3.5.tgz
npm http 200 https://registry.npmjs.org/node-ssdp
npm http 200 https://registry.npmjs.org/multiplex/-/multiplex-6.6.1.tgz
npm http GET https://registry.npmjs.org/varint
npm http GET https://registry.npmjs.org/duplexify
npm http GET https://registry.npmjs.org/readable-stream/-/readable-stream-2.0.5.tgz
npm http GET https://registry.npmjs.org/bytes
npm http GET https://registry.npmjs.org/iconv-lite
npm http GET https://registry.npmjs.org/raw-body
npm http GET https://registry.npmjs.org/content-type
npm http GET https://registry.npmjs.org/depd
npm http GET https://registry.npmjs.org/http-errors
npm http GET https://registry.npmjs.org/on-finished
npm http GET https://registry.npmjs.org/qs
npm http GET https://registry.npmjs.org/type-is
npm http GET https://registry.npmjs.org/es3ify
npm http GET https://registry.npmjs.org/immediate
npm http GET https://registry.npmjs.org/inline-process-browser
npm http GET https://registry.npmjs.org/unreachable-branch-transform
npm http 200 https://registry.npmjs.org/duplexify
npm http GET https://registry.npmjs.org/duplexify/-/duplexify-3.4.2.tgz
npm http 200 https://registry.npmjs.org/readable-stream/-/readable-stream-2.0.5.tgz
npm http 304 https://registry.npmjs.org/content-type
npm http 200 https://registry.npmjs.org/varint
npm http 200 https://registry.npmjs.org/bytes
npm http 304 https://registry.npmjs.org/depd
npm http GET https://registry.npmjs.org/bytes/-/bytes-2.2.0.tgz
npm http GET https://registry.npmjs.org/varint/-/varint-4.0.0.tgz
npm http 304 https://registry.npmjs.org/http-errors
npm http 304 https://registry.npmjs.org/on-finished
npm http 200 https://registry.npmjs.org/raw-body
npm http 304 https://registry.npmjs.org/qs
npm http 200 https://registry.npmjs.org/iconv-lite
npm http 304 https://registry.npmjs.org/type-is
npm http 304 https://registry.npmjs.org/immediate
npm http 304 https://registry.npmjs.org/es3ify
npm http 304 https://registry.npmjs.org/inline-process-browser
npm http GET https://registry.npmjs.org/raw-body/-/raw-body-2.1.5.tgz
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http GET https://registry.npmjs.org/qs/-/qs-5.2.0.tgz
npm http 200 https://registry.npmjs.org/duplexify/-/duplexify-3.4.2.tgz
npm http GET https://registry.npmjs.org/iconv-lite/-/iconv-lite-0.4.13.tgz
npm http 200 https://registry.npmjs.org/bytes/-/bytes-2.2.0.tgz
npm http 200 https://registry.npmjs.org/raw-body/-/raw-body-2.1.5.tgz
npm http GET https://registry.npmjs.org/falafel
npm http GET https://registry.npmjs.org/through2
npm http 200 https://registry.npmjs.org/varint/-/varint-4.0.0.tgz
npm http 200 https://registry.npmjs.org/qs/-/qs-5.2.0.tgz
npm http 200 https://registry.npmjs.org/iconv-lite/-/iconv-lite-0.4.13.tgz
npm http GET https://registry.npmjs.org/esmangle-evaluator
npm http GET https://registry.npmjs.org/recast
npm http GET https://registry.npmjs.org/through2
npm http GET https://registry.npmjs.org/content-disposition
npm http GET https://registry.npmjs.org/cookie
npm http GET https://registry.npmjs.org/cookie-signature
npm http GET https://registry.npmjs.org/debug
npm http GET https://registry.npmjs.org/escape-html
npm http GET https://registry.npmjs.org/etag
npm http GET https://registry.npmjs.org/finalhandler
npm http GET https://registry.npmjs.org/fresh
npm http GET https://registry.npmjs.org/merge-descriptors
npm http GET https://registry.npmjs.org/methods
npm http GET https://registry.npmjs.org/parseurl
npm http GET https://registry.npmjs.org/path-to-regexp
npm http GET https://registry.npmjs.org/proxy-addr
npm http GET https://registry.npmjs.org/range-parser
npm http GET https://registry.npmjs.org/send
npm http GET https://registry.npmjs.org/serve-static
npm http GET https://registry.npmjs.org/utils-merge
npm http GET https://registry.npmjs.org/vary
npm http GET https://registry.npmjs.org/accepts
npm http GET https://registry.npmjs.org/array-flatten
npm http GET https://registry.npmjs.org/depd/-/depd-1.0.1.tgz
npm http GET https://registry.npmjs.org/esprima-fb
npm http GET https://registry.npmjs.org/jstransform
npm http GET https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/falafel
npm http 304 https://registry.npmjs.org/through2
npm http GET https://registry.npmjs.org/extend
npm http GET https://registry.npmjs.org/har-validator
npm http GET https://registry.npmjs.org/is-typedarray
npm http GET https://registry.npmjs.org/aws4
npm http 304 https://registry.npmjs.org/cookie
npm http 304 https://registry.npmjs.org/content-disposition
npm http GET https://registry.npmjs.org/combined-stream
npm http GET https://registry.npmjs.org/form-data
npm http GET https://registry.npmjs.org/forever-agent
npm http GET https://registry.npmjs.org/isstream
npm http GET https://registry.npmjs.org/mime-types
npm http GET https://registry.npmjs.org/http-signature
npm http GET https://registry.npmjs.org/json-stringify-safe
npm http GET https://registry.npmjs.org/hawk
npm http GET https://registry.npmjs.org/oauth-sign
npm http GET https://registry.npmjs.org/stringstream
npm http GET https://registry.npmjs.org/tunnel-agent
npm http GET https://registry.npmjs.org/tough-cookie
npm http GET https://registry.npmjs.org/aws-sign2
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http GET https://registry.npmjs.org/caseless
npm http GET https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/cookie-signature
npm http GET https://registry.npmjs.org/qs/-/qs-6.0.2.tgz
npm http 304 https://registry.npmjs.org/escape-html
npm http 304 https://registry.npmjs.org/etag
npm http 304 https://registry.npmjs.org/fresh
npm http 304 https://registry.npmjs.org/merge-descriptors
npm http 304 https://registry.npmjs.org/finalhandler
npm http GET https://registry.npmjs.org/content-disposition/-/content-disposition-0.5.0.tgz
npm http GET https://registry.npmjs.org/cookie/-/cookie-0.1.3.tgz
npm http 304 https://registry.npmjs.org/methods
npm http 200 https://registry.npmjs.org/depd/-/depd-1.0.1.tgz
npm http 304 https://registry.npmjs.org/parseurl
npm http 304 https://registry.npmjs.org/path-to-regexp
npm http 304 https://registry.npmjs.org/range-parser
npm http 304 https://registry.npmjs.org/proxy-addr
npm http 304 https://registry.npmjs.org/send
npm http 304 https://registry.npmjs.org/serve-static
npm http 304 https://registry.npmjs.org/utils-merge
npm http 304 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/vary
npm http GET https://registry.npmjs.org/escape-html/-/escape-html-1.0.2.tgz
npm http 304 https://registry.npmjs.org/array-flatten
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 304 https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/through
npm http GET https://registry.npmjs.org/merge-descriptors/-/merge-descriptors-1.0.0.tgz
npm http GET https://registry.npmjs.org/finalhandler/-/finalhandler-0.4.0.tgz
npm http 200 https://registry.npmjs.org/is-typedarray
npm http 200 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/combined-stream
npm http 200 https://registry.npmjs.org/qs/-/qs-6.0.2.tgz
npm http 200 https://registry.npmjs.org/forever-agent
npm http GET https://registry.npmjs.org/send/-/send-0.13.0.tgz
npm http 200 https://registry.npmjs.org/cookie/-/cookie-0.1.3.tgz
npm http 200 https://registry.npmjs.org/har-validator
npm http 200 https://registry.npmjs.org/content-disposition/-/content-disposition-0.5.0.tgz
npm http 200 https://registry.npmjs.org/finalhandler/-/finalhandler-0.4.0.tgz
npm http 304 https://registry.npmjs.org/isstream
npm http 200 https://registry.npmjs.org/aws4
npm http 200 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/mime-types
npm http 200 https://registry.npmjs.org/send/-/send-0.13.0.tgz
npm http 200 https://registry.npmjs.org/http-signature
npm http 200 https://registry.npmjs.org/json-stringify-safe
npm http 200 https://registry.npmjs.org/stringstream
npm http 200 https://registry.npmjs.org/oauth-sign
npm http 200 https://registry.npmjs.org/tunnel-agent
npm http GET https://registry.npmjs.org/extend/-/extend-3.0.0.tgz
npm http GET https://registry.npmjs.org/is-typedarray/-/is-typedarray-1.0.0.tgz
npm http 200 https://registry.npmjs.org/hawk
npm http 200 https://registry.npmjs.org/escape-html/-/escape-html-1.0.2.tgz
npm http 200 https://registry.npmjs.org/merge-descriptors/-/merge-descriptors-1.0.0.tgz
npm http 304 https://registry.npmjs.org/caseless
npm http 200 https://registry.npmjs.org/aws-sign2
npm http GET https://registry.npmjs.org/forever-agent/-/forever-agent-0.6.1.tgz
npm http 200 https://registry.npmjs.org/bl
npm http GET https://registry.npmjs.org/har-validator/-/har-validator-2.0.6.tgz
npm http GET https://registry.npmjs.org/aws4/-/aws4-1.2.1.tgz
npm http 200 https://registry.npmjs.org/tough-cookie
npm http GET https://registry.npmjs.org/form-data/-/form-data-1.0.0-rc3.tgz
npm http GET https://registry.npmjs.org/http-signature/-/http-signature-1.1.1.tgz
npm http GET https://registry.npmjs.org/stringstream/-/stringstream-0.0.5.tgz
npm http GET https://registry.npmjs.org/oauth-sign/-/oauth-sign-0.8.1.tgz
npm http GET https://registry.npmjs.org/tunnel-agent/-/tunnel-agent-0.4.2.tgz
npm http GET https://registry.npmjs.org/hawk/-/hawk-3.1.3.tgz
npm http GET https://registry.npmjs.org/caseless/-/caseless-0.11.0.tgz
npm http GET https://registry.npmjs.org/aws-sign2/-/aws-sign2-0.6.0.tgz
npm http GET https://registry.npmjs.org/bl/-/bl-1.0.1.tgz
npm http GET https://registry.npmjs.org/tough-cookie/-/tough-cookie-2.2.1.tgz
npm http 200 https://registry.npmjs.org/is-typedarray/-/is-typedarray-1.0.0.tgz
npm http 200 https://registry.npmjs.org/extend/-/extend-3.0.0.tgz
npm http 200 https://registry.npmjs.org/form-data/-/form-data-1.0.0-rc3.tgz
npm http 200 https://registry.npmjs.org/forever-agent/-/forever-agent-0.6.1.tgz
npm http 200 https://registry.npmjs.org/http-signature/-/http-signature-1.1.1.tgz
npm http 200 https://registry.npmjs.org/oauth-sign/-/oauth-sign-0.8.1.tgz
npm http 200 https://registry.npmjs.org/stringstream/-/stringstream-0.0.5.tgz
npm http 200 https://registry.npmjs.org/tunnel-agent/-/tunnel-agent-0.4.2.tgz
npm http 200 https://registry.npmjs.org/caseless/-/caseless-0.11.0.tgz
npm http 200 https://registry.npmjs.org/hawk/-/hawk-3.1.3.tgz
npm http 200 https://registry.npmjs.org/aws-sign2/-/aws-sign2-0.6.0.tgz
npm http 200 https://registry.npmjs.org/bl/-/bl-1.0.1.tgz
npm http 200 https://registry.npmjs.org/tough-cookie/-/tough-cookie-2.2.1.tgz
npm http 200 https://registry.npmjs.org/har-validator/-/har-validator-2.0.6.tgz
npm http 200 https://registry.npmjs.org/aws4/-/aws4-1.2.1.tgz
npm http GET https://registry.npmjs.org/inherits
npm http GET https://registry.npmjs.org/statuses
npm http GET https://registry.npmjs.org/end-of-stream
npm http GET https://registry.npmjs.org/readable-stream
npm http GET https://registry.npmjs.org/ee-first
npm http GET https://registry.npmjs.org/xtend
npm http GET https://registry.npmjs.org/media-typer
npm http GET https://registry.npmjs.org/unpipe
npm http 304 https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/statuses
npm http 200 https://registry.npmjs.org/end-of-stream
npm http 304 https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/media-typer
npm http 304 https://registry.npmjs.org/unpipe
npm http 304 https://registry.npmjs.org/ee-first
npm http GET https://registry.npmjs.org/end-of-stream/-/end-of-stream-1.0.0.tgz
npm http 304 https://registry.npmjs.org/readable-stream
npm http GET https://registry.npmjs.org/forwarded
npm http GET https://registry.npmjs.org/ipaddr.js
npm http GET https://registry.npmjs.org/negotiator
npm http GET https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/negotiator
npm http 200 https://registry.npmjs.org/end-of-stream/-/end-of-stream-1.0.0.tgz
npm http 304 https://registry.npmjs.org/ipaddr.js
npm http 304 https://registry.npmjs.org/forwarded
npm http 304 https://registry.npmjs.org/ms
npm http GET https://registry.npmjs.org/acorn
npm http GET https://registry.npmjs.org/foreach
npm http GET https://registry.npmjs.org/isarray
npm http GET https://registry.npmjs.org/object-keys
npm http GET https://registry.npmjs.org/destroy
npm http GET https://registry.npmjs.org/mime
npm http GET https://registry.npmjs.org/delayed-stream
npm http GET https://registry.npmjs.org/mime-db
npm http 304 https://registry.npmjs.org/acorn
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/foreach
npm http 304 https://registry.npmjs.org/mime
npm http 304 https://registry.npmjs.org/delayed-stream
npm http 304 https://registry.npmjs.org/destroy
npm http 304 https://registry.npmjs.org/mime-db
npm http GET https://registry.npmjs.org/async
npm http GET https://registry.npmjs.org/destroy/-/destroy-1.0.3.tgz
npm http 304 https://registry.npmjs.org/async
npm http 200 https://registry.npmjs.org/destroy/-/destroy-1.0.3.tgz
npm http GET https://registry.npmjs.org/async/-/async-1.5.2.tgz
npm http GET https://registry.npmjs.org/lru-cache
npm http 200 https://registry.npmjs.org/async/-/async-1.5.2.tgz
npm http 200 https://registry.npmjs.org/lru-cache
npm http GET https://registry.npmjs.org/jsprim
npm http GET https://registry.npmjs.org/sshpk
npm http GET https://registry.npmjs.org/assert-plus
npm http GET https://registry.npmjs.org/lru-cache/-/lru-cache-2.7.3.tgz
npm http GET https://registry.npmjs.org/process-nextick-args
npm http GET https://registry.npmjs.org/string_decoder
npm http GET https://registry.npmjs.org/core-util-is
npm http GET https://registry.npmjs.org/util-deprecate
npm http 200 https://registry.npmjs.org/assert-plus
npm http GET https://registry.npmjs.org/pinkie-promise
npm http GET https://registry.npmjs.org/chalk
npm http 304 https://registry.npmjs.org/core-util-is
npm http GET https://registry.npmjs.org/commander
npm http 200 https://registry.npmjs.org/lru-cache/-/lru-cache-2.7.3.tgz
npm http GET https://registry.npmjs.org/is-my-json-valid
npm http 200 https://registry.npmjs.org/sshpk
npm http 200 https://registry.npmjs.org/util-deprecate
npm http GET https://registry.npmjs.org/assert-plus/-/assert-plus-0.2.0.tgz
npm http 200 https://registry.npmjs.org/jsprim
npm http 200 https://registry.npmjs.org/pinkie-promise
npm http 200 https://registry.npmjs.org/process-nextick-args
npm http 304 https://registry.npmjs.org/string_decoder
npm http GET https://registry.npmjs.org/wrappy
npm http 200 https://registry.npmjs.org/chalk
npm http GET https://registry.npmjs.org/sshpk/-/sshpk-1.7.3.tgz
npm http GET https://registry.npmjs.org/util-deprecate/-/util-deprecate-1.0.2.tgz
npm http 200 https://registry.npmjs.org/commander
npm http 200 https://registry.npmjs.org/is-my-json-valid
npm http GET https://registry.npmjs.org/jsprim/-/jsprim-1.2.2.tgz
npm http GET https://registry.npmjs.org/pinkie-promise/-/pinkie-promise-2.0.0.tgz
npm http GET https://registry.npmjs.org/process-nextick-args/-/process-nextick-args-1.0.6.tgz
npm http GET https://registry.npmjs.org/chalk/-/chalk-1.1.1.tgz
npm http 200 https://registry.npmjs.org/assert-plus/-/assert-plus-0.2.0.tgz
npm http GET https://registry.npmjs.org/commander/-/commander-2.9.0.tgz
npm http GET https://registry.npmjs.org/is-my-json-valid/-/is-my-json-valid-2.12.4.tgz
npm http 200 https://registry.npmjs.org/process-nextick-args/-/process-nextick-args-1.0.6.tgz
npm http 304 https://registry.npmjs.org/wrappy
npm http 200 https://registry.npmjs.org/chalk/-/chalk-1.1.1.tgz
npm http 200 https://registry.npmjs.org/jsprim/-/jsprim-1.2.2.tgz
npm http 200 https://registry.npmjs.org/sshpk/-/sshpk-1.7.3.tgz
npm http 200 https://registry.npmjs.org/util-deprecate/-/util-deprecate-1.0.2.tgz
npm http 200 https://registry.npmjs.org/commander/-/commander-2.9.0.tgz
npm http 200 https://registry.npmjs.org/pinkie-promise/-/pinkie-promise-2.0.0.tgz
npm http 200 https://registry.npmjs.org/is-my-json-valid/-/is-my-json-valid-2.12.4.tgz
npm http GET https://registry.npmjs.org/base62
npm http GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/base62
npm http 304 https://registry.npmjs.org/source-map
npm http GET https://registry.npmjs.org/private
npm http GET https://registry.npmjs.org/ast-types
npm http GET https://registry.npmjs.org/pkginfo
npm http GET https://registry.npmjs.org/stack-trace
npm http GET https://registry.npmjs.org/colors
npm http GET https://registry.npmjs.org/cycle
npm http GET https://registry.npmjs.org/eyes
npm http 304 https://registry.npmjs.org/private
npm http 304 https://registry.npmjs.org/ast-types
npm http GET https://registry.npmjs.org/pinkie
npm http 304 https://registry.npmjs.org/cycle
npm http 304 https://registry.npmjs.org/eyes
npm http 304 https://registry.npmjs.org/pkginfo
npm http 304 https://registry.npmjs.org/colors
npm http 304 https://registry.npmjs.org/stack-trace
npm http 200 https://registry.npmjs.org/pinkie
npm http GET https://registry.npmjs.org/strip-ansi
npm http GET https://registry.npmjs.org/supports-color
npm http GET https://registry.npmjs.org/ansi-styles
npm http GET https://registry.npmjs.org/escape-string-regexp
npm http GET https://registry.npmjs.org/has-ansi
npm http GET https://registry.npmjs.org/pinkie/-/pinkie-2.0.4.tgz
npm http GET https://registry.npmjs.org/extsprintf
npm http GET https://registry.npmjs.org/json-schema
npm http GET https://registry.npmjs.org/verror
npm http 200 https://registry.npmjs.org/ansi-styles
npm http 200 https://registry.npmjs.org/escape-string-regexp
npm http 200 https://registry.npmjs.org/has-ansi
npm http 200 https://registry.npmjs.org/extsprintf
npm http 200 https://registry.npmjs.org/json-schema
npm http 200 https://registry.npmjs.org/supports-color
npm http 200 https://registry.npmjs.org/strip-ansi
npm http 200 https://registry.npmjs.org/verror
npm http 200 https://registry.npmjs.org/pinkie/-/pinkie-2.0.4.tgz
npm http GET https://registry.npmjs.org/escape-string-regexp/-/escape-string-regexp-1.0.4.tgz
npm http GET https://registry.npmjs.org/ansi-styles/-/ansi-styles-2.1.0.tgz
npm http GET https://registry.npmjs.org/extsprintf/-/extsprintf-1.0.2.tgz
npm http GET https://registry.npmjs.org/json-schema/-/json-schema-0.2.2.tgz
npm http GET https://registry.npmjs.org/has-ansi/-/has-ansi-2.0.0.tgz
npm http GET https://registry.npmjs.org/supports-color/-/supports-color-2.0.0.tgz
npm http GET https://registry.npmjs.org/strip-ansi/-/strip-ansi-3.0.0.tgz
npm http GET https://registry.npmjs.org/verror/-/verror-1.3.6.tgz
npm http GET https://registry.npmjs.org/graceful-readlink
npm http 200 https://registry.npmjs.org/escape-string-regexp/-/escape-string-regexp-1.0.4.tgz
npm http 200 https://registry.npmjs.org/ansi-styles/-/ansi-styles-2.1.0.tgz
npm http 200 https://registry.npmjs.org/extsprintf/-/extsprintf-1.0.2.tgz
npm http 200 https://registry.npmjs.org/json-schema/-/json-schema-0.2.2.tgz
npm http 200 https://registry.npmjs.org/supports-color/-/supports-color-2.0.0.tgz
npm http 200 https://registry.npmjs.org/has-ansi/-/has-ansi-2.0.0.tgz
npm http 200 https://registry.npmjs.org/strip-ansi/-/strip-ansi-3.0.0.tgz
npm http 200 https://registry.npmjs.org/verror/-/verror-1.3.6.tgz
npm http 200 https://registry.npmjs.org/graceful-readlink
npm http GET https://registry.npmjs.org/graceful-readlink/-/graceful-readlink-1.0.1.tgz
npm http 200 https://registry.npmjs.org/graceful-readlink/-/graceful-readlink-1.0.1.tgz
npm http GET https://registry.npmjs.org/ansi-regex
npm http 200 https://registry.npmjs.org/ansi-regex
npm http GET https://registry.npmjs.org/ansi-regex/-/ansi-regex-2.0.0.tgz
npm http 200 https://registry.npmjs.org/ansi-regex/-/ansi-regex-2.0.0.tgz
npm http GET https://registry.npmjs.org/tweetnacl
npm http GET https://registry.npmjs.org/jodid25519
npm http GET https://registry.npmjs.org/ecc-jsbn
npm http GET https://registry.npmjs.org/dashdash
npm http GET https://registry.npmjs.org/jsbn
npm http GET https://registry.npmjs.org/asn1
npm http GET https://registry.npmjs.org/jsonpointer
npm http GET https://registry.npmjs.org/generate-function
npm http GET https://registry.npmjs.org/generate-object-property
npm http 200 https://registry.npmjs.org/jodid25519
npm http 200 https://registry.npmjs.org/jsbn
npm http 200 https://registry.npmjs.org/ecc-jsbn
npm http GET https://registry.npmjs.org/hoek
npm http GET https://registry.npmjs.org/boom
npm http GET https://registry.npmjs.org/cryptiles
npm http GET https://registry.npmjs.org/sntp
npm http GET https://registry.npmjs.org/jodid25519/-/jodid25519-1.0.2.tgz
npm http 200 https://registry.npmjs.org/jsonpointer
npm http GET https://registry.npmjs.org/jsbn/-/jsbn-0.1.0.tgz
npm http 200 https://registry.npmjs.org/generate-function
npm http 200 https://registry.npmjs.org/tweetnacl
npm http 200 https://registry.npmjs.org/asn1
npm http GET https://registry.npmjs.org/ecc-jsbn/-/ecc-jsbn-0.1.1.tgz
npm http GET https://registry.npmjs.org/jsonpointer/-/jsonpointer-2.0.0.tgz
npm http 200 https://registry.npmjs.org/generate-object-property
npm http 200 https://registry.npmjs.org/dashdash
npm http GET https://registry.npmjs.org/generate-function/-/generate-function-2.0.0.tgz
npm http 200 https://registry.npmjs.org/cryptiles
npm http GET https://registry.npmjs.org/tweetnacl/-/tweetnacl-0.13.3.tgz
npm http GET https://registry.npmjs.org/asn1/-/asn1-0.2.3.tgz
npm http 200 https://registry.npmjs.org/boom
npm http GET https://registry.npmjs.org/generate-object-property/-/generate-object-property-1.2.0.tgz
npm http GET https://registry.npmjs.org/dashdash/-/dashdash-1.12.2.tgz
npm http GET https://registry.npmjs.org/cryptiles/-/cryptiles-2.0.5.tgz
npm http 200 https://registry.npmjs.org/sntp
npm http GET https://registry.npmjs.org/amdefine
npm http GET https://registry.npmjs.org/boom/-/boom-2.10.1.tgz
npm http 200 https://registry.npmjs.org/hoek
npm http GET https://registry.npmjs.org/sntp/-/sntp-1.0.9.tgz
npm http GET https://registry.npmjs.org/hoek/-/hoek-2.16.3.tgz
npm http 200 https://registry.npmjs.org/jsbn/-/jsbn-0.1.0.tgz
npm http 200 https://registry.npmjs.org/ecc-jsbn/-/ecc-jsbn-0.1.1.tgz
npm http 200 https://registry.npmjs.org/jodid25519/-/jodid25519-1.0.2.tgz
npm http 200 https://registry.npmjs.org/jsonpointer/-/jsonpointer-2.0.0.tgz
npm http 200 https://registry.npmjs.org/generate-function/-/generate-function-2.0.0.tgz
npm http 200 https://registry.npmjs.org/tweetnacl/-/tweetnacl-0.13.3.tgz
npm http 200 https://registry.npmjs.org/asn1/-/asn1-0.2.3.tgz
npm http 200 https://registry.npmjs.org/generate-object-property/-/generate-object-property-1.2.0.tgz
npm http 200 https://registry.npmjs.org/cryptiles/-/cryptiles-2.0.5.tgz
npm http 200 https://registry.npmjs.org/boom/-/boom-2.10.1.tgz
npm http 200 https://registry.npmjs.org/sntp/-/sntp-1.0.9.tgz
npm http 200 https://registry.npmjs.org/dashdash/-/dashdash-1.12.2.tgz
npm http 304 https://registry.npmjs.org/amdefine
npm http 200 https://registry.npmjs.org/hoek/-/hoek-2.16.3.tgz
npm http GET https://registry.npmjs.org/is-property
npm http 200 https://registry.npmjs.org/is-property
npm http GET https://registry.npmjs.org/is-property/-/is-property-1.0.2.tgz
npm http 200 https://registry.npmjs.org/is-property/-/is-property-1.0.2.tgz
npm http GET https://registry.npmjs.org/catharsis
npm http GET https://registry.npmjs.org/espree
npm http GET https://registry.npmjs.org/js2xmlparser
npm http GET https://registry.npmjs.org/marked
npm http GET https://registry.npmjs.org/requizzle
npm http GET https://registry.npmjs.org/bluebird
npm http GET https://registry.npmjs.org/wrench
npm http GET https://registry.npmjs.org/strip-json-comments
npm http GET https://registry.npmjs.org/underscore
npm http GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http GET https://registry.npmjs.org/async/-/async-1.4.2.tgz
npm http 200 https://registry.npmjs.org/requizzle
npm http GET https://registry.npmjs.org/requizzle/-/requizzle-0.2.1.tgz
npm http 200 https://registry.npmjs.org/async/-/async-1.4.2.tgz
npm http 304 https://registry.npmjs.org/bluebird
npm http 200 https://registry.npmjs.org/js2xmlparser
npm http 200 https://registry.npmjs.org/catharsis
npm http GET https://registry.npmjs.org/bluebird/-/bluebird-2.9.34.tgz
npm http GET https://registry.npmjs.org/js2xmlparser/-/js2xmlparser-1.0.0.tgz
npm http GET https://registry.npmjs.org/catharsis/-/catharsis-0.8.7.tgz
npm http 200 https://registry.npmjs.org/espree
npm http GET https://registry.npmjs.org/espree/-/espree-2.2.5.tgz
npm http 200 https://registry.npmjs.org/underscore
npm http 200 https://registry.npmjs.org/strip-json-comments
npm http 200 https://registry.npmjs.org/wrench
npm http GET https://registry.npmjs.org/strip-json-comments/-/strip-json-comments-1.0.4.tgz
npm http GET https://registry.npmjs.org/underscore/-/underscore-1.8.3.tgz
npm http 200 https://registry.npmjs.org/marked
npm http GET https://registry.npmjs.org/wrench/-/wrench-1.5.8.tgz
npm http GET https://registry.npmjs.org/marked/-/marked-0.3.5.tgz
npm http 200 https://registry.npmjs.org/requizzle/-/requizzle-0.2.1.tgz
npm http 200 https://registry.npmjs.org/strip-json-comments/-/strip-json-comments-1.0.4.tgz
npm http 200 https://registry.npmjs.org/bluebird/-/bluebird-2.9.34.tgz
npm http 200 https://registry.npmjs.org/js2xmlparser/-/js2xmlparser-1.0.0.tgz
npm http 200 https://registry.npmjs.org/espree/-/espree-2.2.5.tgz
npm http 200 https://registry.npmjs.org/catharsis/-/catharsis-0.8.7.tgz
npm http 200 https://registry.npmjs.org/underscore/-/underscore-1.8.3.tgz
npm http 200 https://registry.npmjs.org/marked/-/marked-0.3.5.tgz
npm http 200 https://registry.npmjs.org/wrench/-/wrench-1.5.8.tgz
npm http 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http GET https://registry.npmjs.org/underscore/-/underscore-1.6.0.tgz
npm http 200 https://registry.npmjs.org/underscore/-/underscore-1.6.0.tgz
npm http GET https://registry.npmjs.org/underscore-contrib
npm http 200 https://registry.npmjs.org/underscore-contrib
npm http GET https://registry.npmjs.org/underscore-contrib/-/underscore-contrib-0.3.0.tgz
npm http 200 https://registry.npmjs.org/underscore-contrib/-/underscore-contrib-0.3.0.tgz
npm http GET https://registry.npmjs.org/node-ssdp
npm http 304 https://registry.npmjs.org/node-ssdp
while [jx install] is a special command, the current folder has install.js, running that instead.


module.js:802
    throw err;
          ^
Error: Cannot find module 'unzip'
    at Function.Module._oldRes (module.js:800:15)
    at Function.Module._resolveFilename (module.js:1653:19)
    at Function.Module._load (module.js:360:25)
    at Module.require (module.js:475:17)
    at require (module.js:493:17)
    at Object.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/thali/install/install.js:6:13)
    at Module._compile (module.js:619:26)
    at Object.Module._extensions..js (module.js:649:10)
    at Module.load (module.js:440:36)
    at Function.Module._load (module.js:405:12)

```

Error: Command failed: npm WARN package.json thali-test-server@0.0.1 No repository field.
npm http GET https://registry.npmjs.org/express
npm http GET https://registry.npmjs.org/fs-extra-promise
npm http GET https://registry.npmjs.org/lie
npm http GET https://registry.npmjs.org/socket.io
npm http GET https://registry.npmjs.org/winston
npm http GET https://registry.npmjs.org/socket.io-client
npm http GET https://registry.npmjs.org/node-uuid
npm http GET https://registry.npmjs.org/tape
npm http 200 https://registry.npmjs.org/lie
npm http 200 https://registry.npmjs.org/winston
npm http 200 https://registry.npmjs.org/socket.io
npm http 200 https://registry.npmjs.org/socket.io-client
npm http GET https://registry.npmjs.org/socket.io/-/socket.io-1.4.5.tgz
npm http 200 https://registry.npmjs.org/node-uuid
npm http GET https://registry.npmjs.org/lie/-/lie-3.0.2.tgz
npm http GET https://registry.npmjs.org/winston/-/winston-2.1.1.tgz
npm http GET https://registry.npmjs.org/socket.io-client/-/socket.io-client-1.4.5.tgz
npm http GET https://registry.npmjs.org/node-uuid/-/node-uuid-1.4.7.tgz
npm http 200 https://registry.npmjs.org/express
npm http 200 https://registry.npmjs.org/tape
npm http 200 https://registry.npmjs.org/socket.io/-/socket.io-1.4.5.tgz
npm http 200 https://registry.npmjs.org/lie/-/lie-3.0.2.tgz
npm http GET https://registry.npmjs.org/express/-/express-4.13.4.tgz
npm http GET https://registry.npmjs.org/tape/-/tape-1.1.1.tgz
npm http 200 https://registry.npmjs.org/winston/-/winston-2.1.1.tgz
npm http 200 https://registry.npmjs.org/socket.io-client/-/socket.io-client-1.4.5.tgz
npm http 200 https://registry.npmjs.org/node-uuid/-/node-uuid-1.4.7.tgz
npm http 200 https://registry.npmjs.org/fs-extra-promise
npm http 200 https://registry.npmjs.org/tape/-/tape-1.1.1.tgz
npm http GET https://registry.npmjs.org/fs-extra-promise/-/fs-extra-promise-0.2.1.tgz
npm http 200 https://registry.npmjs.org/express/-/express-4.13.4.tgz
npm http 200 https://registry.npmjs.org/fs-extra-promise/-/fs-extra-promise-0.2.1.tgz
npm http GET https://registry.npmjs.org/fs-extra
npm http GET https://registry.npmjs.org/bluebird
npm http GET https://registry.npmjs.org/socket.io-adapter
npm http GET https://registry.npmjs.org/has-binary
npm http GET https://registry.npmjs.org/debug
npm http GET https://registry.npmjs.org/engine.io
npm http GET https://registry.npmjs.org/socket.io-parser
npm http GET https://registry.npmjs.org/es3ify
npm http GET https://registry.npmjs.org/immediate
npm http GET https://registry.npmjs.org/inline-process-browser
npm http GET https://registry.npmjs.org/unreachable-branch-transform
npm http GET https://registry.npmjs.org/jsonify
npm http GET https://registry.npmjs.org/defined
npm http GET https://registry.npmjs.org/deep-equal
npm http GET https://registry.npmjs.org/through
npm http GET https://registry.npmjs.org/content-disposition
npm http GET https://registry.npmjs.org/content-type
npm http GET https://registry.npmjs.org/cookie
npm http GET https://registry.npmjs.org/cookie-signature
npm http 200 https://registry.npmjs.org/socket.io-adapter
npm http GET https://registry.npmjs.org/debug
npm http GET https://registry.npmjs.org/depd
npm http 200 https://registry.npmjs.org/has-binary
npm http 200 https://registry.npmjs.org/fs-extra
npm http GET https://registry.npmjs.org/escape-html
npm http GET https://registry.npmjs.org/etag
npm http GET https://registry.npmjs.org/finalhandler
npm http GET https://registry.npmjs.org/fresh
npm http GET https://registry.npmjs.org/merge-descriptors
npm http GET https://registry.npmjs.org/methods
npm http GET https://registry.npmjs.org/on-finished
npm http GET https://registry.npmjs.org/parseurl
npm http GET https://registry.npmjs.org/path-to-regexp
npm http GET https://registry.npmjs.org/proxy-addr
npm http GET https://registry.npmjs.org/range-parser
npm http GET https://registry.npmjs.org/send
npm http GET https://registry.npmjs.org/serve-static
npm http GET https://registry.npmjs.org/type-is
npm http GET https://registry.npmjs.org/utils-merge
npm http GET https://registry.npmjs.org/vary
npm http GET https://registry.npmjs.org/accepts
npm http GET https://registry.npmjs.org/array-flatten
npm http 200 https://registry.npmjs.org/socket.io-parser
npm http 200 https://registry.npmjs.org/debug
npm http 200 https://registry.npmjs.org/es3ify
npm http 200 https://registry.npmjs.org/bluebird
npm http 200 https://registry.npmjs.org/inline-process-browser
npm http GET https://registry.npmjs.org/qs
npm http 200 https://registry.npmjs.org/unreachable-branch-transform
npm http 200 https://registry.npmjs.org/immediate
npm http 304 https://registry.npmjs.org/jsonify
npm http 200 https://registry.npmjs.org/engine.io
npm http GET https://registry.npmjs.org/socket.io-adapter/-/socket.io-adapter-0.4.0.tgz
npm http 304 https://registry.npmjs.org/defined
npm http 200 https://registry.npmjs.org/deep-equal
npm http 200 https://registry.npmjs.org/through
npm http 200 https://registry.npmjs.org/content-disposition
npm http GET https://registry.npmjs.org/has-binary/-/has-binary-0.1.7.tgz
npm http 200 https://registry.npmjs.org/content-type
npm http GET https://registry.npmjs.org/debug/-/debug-2.2.0.tgz
npm http GET https://registry.npmjs.org/socket.io-parser/-/socket.io-parser-2.2.6.tgz
npm http 200 https://registry.npmjs.org/cookie
npm http 200 https://registry.npmjs.org/cookie-signature
npm http 200 https://registry.npmjs.org/debug
npm http 200 https://registry.npmjs.org/depd
npm http 200 https://registry.npmjs.org/escape-html
npm http GET https://registry.npmjs.org/fs-extra/-/fs-extra-0.24.0.tgz
npm http 200 https://registry.npmjs.org/etag
npm http 200 https://registry.npmjs.org/finalhandler
npm http GET https://registry.npmjs.org/es3ify/-/es3ify-0.1.4.tgz
npm http 200 https://registry.npmjs.org/fresh
npm http 200 https://registry.npmjs.org/merge-descriptors
npm http 200 https://registry.npmjs.org/methods
npm http GET https://registry.npmjs.org/bluebird/-/bluebird-2.10.2.tgz
npm http 200 https://registry.npmjs.org/on-finished
npm http 200 https://registry.npmjs.org/parseurl
npm http GET https://registry.npmjs.org/inline-process-browser/-/inline-process-browser-1.0.0.tgz
npm http GET https://registry.npmjs.org/engine.io-client
npm http GET https://registry.npmjs.org/component-bind
npm http GET https://registry.npmjs.org/component-emitter
npm http GET https://registry.npmjs.org/object-component
npm http GET https://registry.npmjs.org/parseuri
npm http GET https://registry.npmjs.org/to-array
npm http GET https://registry.npmjs.org/backo2
npm http GET https://registry.npmjs.org/unreachable-branch-transform/-/unreachable-branch-transform-0.3.0.tgz
npm http GET https://registry.npmjs.org/immediate/-/immediate-3.0.5.tgz
npm http 200 https://registry.npmjs.org/proxy-addr
npm http 200 https://registry.npmjs.org/range-parser
npm http GET https://registry.npmjs.org/engine.io/-/engine.io-1.6.8.tgz
npm http 200 https://registry.npmjs.org/path-to-regexp
npm http GET https://registry.npmjs.org/content-disposition/-/content-disposition-0.5.1.tgz
npm http GET https://registry.npmjs.org/indexof
npm http 200 https://registry.npmjs.org/serve-static
npm http 200 https://registry.npmjs.org/type-is
npm http 200 https://registry.npmjs.org/send
npm http 200 https://registry.npmjs.org/socket.io-adapter/-/socket.io-adapter-0.4.0.tgz
npm http 200 https://registry.npmjs.org/utils-merge
npm http 200 https://registry.npmjs.org/has-binary/-/has-binary-0.1.7.tgz
npm http 200 https://registry.npmjs.org/socket.io-parser/-/socket.io-parser-2.2.6.tgz
npm http 200 https://registry.npmjs.org/vary
npm http 200 https://registry.npmjs.org/debug/-/debug-2.2.0.tgz
npm http GET https://registry.npmjs.org/deep-equal/-/deep-equal-0.0.0.tgz
npm http 200 https://registry.npmjs.org/accepts
npm http 200 https://registry.npmjs.org/array-flatten
npm http 200 https://registry.npmjs.org/es3ify/-/es3ify-0.1.4.tgz
npm http GET https://registry.npmjs.org/cookie/-/cookie-0.1.5.tgz
npm http GET https://registry.npmjs.org/cookie-signature/-/cookie-signature-1.0.6.tgz
npm http 200 https://registry.npmjs.org/qs
npm http 200 https://registry.npmjs.org/component-bind
npm http 200 https://registry.npmjs.org/inline-process-browser/-/inline-process-browser-1.0.0.tgz
npm http GET https://registry.npmjs.org/content-type/-/content-type-1.0.1.tgz
npm http GET https://registry.npmjs.org/finalhandler/-/finalhandler-0.4.1.tgz
npm http 200 https://registry.npmjs.org/unreachable-branch-transform/-/unreachable-branch-transform-0.3.0.tgz
npm http 200 https://registry.npmjs.org/component-emitter
npm http 200 https://registry.npmjs.org/object-component
npm http 200 https://registry.npmjs.org/immediate/-/immediate-3.0.5.tgz
npm http GET https://registry.npmjs.org/depd/-/depd-1.1.0.tgz
npm http GET https://registry.npmjs.org/escape-html/-/escape-html-1.0.3.tgz
npm http GET https://registry.npmjs.org/fresh/-/fresh-0.3.0.tgz
npm http GET https://registry.npmjs.org/merge-descriptors/-/merge-descriptors-1.0.1.tgz
npm http 200 https://registry.npmjs.org/fs-extra/-/fs-extra-0.24.0.tgz
npm http 200 https://registry.npmjs.org/bluebird/-/bluebird-2.10.2.tgz
npm http GET https://registry.npmjs.org/etag/-/etag-1.7.0.tgz
npm http 200 https://registry.npmjs.org/parseuri
npm http 200 https://registry.npmjs.org/to-array
npm http 200 https://registry.npmjs.org/engine.io/-/engine.io-1.6.8.tgz
npm http 200 https://registry.npmjs.org/engine.io-client
npm http 200 https://registry.npmjs.org/backo2
npm http 200 https://registry.npmjs.org/content-disposition/-/content-disposition-0.5.1.tgz
npm http 304 https://registry.npmjs.org/indexof
npm http 200 https://registry.npmjs.org/deep-equal/-/deep-equal-0.0.0.tgz
npm http 200 https://registry.npmjs.org/cookie/-/cookie-0.1.5.tgz
npm http GET https://registry.npmjs.org/methods/-/methods-1.1.2.tgz
npm http 200 https://registry.npmjs.org/cookie-signature/-/cookie-signature-1.0.6.tgz
npm http GET https://registry.npmjs.org/on-finished/-/on-finished-2.3.0.tgz
npm http GET https://registry.npmjs.org/parseurl/-/parseurl-1.3.1.tgz
npm http GET https://registry.npmjs.org/path-to-regexp/-/path-to-regexp-0.1.7.tgz
npm http GET https://registry.npmjs.org/proxy-addr/-/proxy-addr-1.0.10.tgz
npm http GET https://registry.npmjs.org/range-parser/-/range-parser-1.0.3.tgz
npm http GET https://registry.npmjs.org/send/-/send-0.13.1.tgz
npm http GET https://registry.npmjs.org/utils-merge/-/utils-merge-1.0.0.tgz
npm http 200 https://registry.npmjs.org/content-type/-/content-type-1.0.1.tgz
npm http 200 https://registry.npmjs.org/finalhandler/-/finalhandler-0.4.1.tgz
npm http GET https://registry.npmjs.org/array-flatten/-/array-flatten-1.1.1.tgz
npm http 200 https://registry.npmjs.org/depd/-/depd-1.1.0.tgz
npm http GET https://registry.npmjs.org/serve-static/-/serve-static-1.10.2.tgz
npm http GET https://registry.npmjs.org/type-is/-/type-is-1.6.11.tgz
npm http GET https://registry.npmjs.org/qs/-/qs-4.0.0.tgz
npm http 200 https://registry.npmjs.org/escape-html/-/escape-html-1.0.3.tgz
npm http GET https://registry.npmjs.org/vary/-/vary-1.0.1.tgz
npm http 200 https://registry.npmjs.org/fresh/-/fresh-0.3.0.tgz
npm http GET https://registry.npmjs.org/accepts/-/accepts-1.2.13.tgz
npm http GET https://registry.npmjs.org/component-bind/-/component-bind-1.0.0.tgz
npm http 200 https://registry.npmjs.org/merge-descriptors/-/merge-descriptors-1.0.1.tgz
npm http 200 https://registry.npmjs.org/etag/-/etag-1.7.0.tgz
npm http GET https://registry.npmjs.org/component-emitter/-/component-emitter-1.2.0.tgz
npm http 200 https://registry.npmjs.org/methods/-/methods-1.1.2.tgz
npm http GET https://registry.npmjs.org/object-component/-/object-component-0.0.3.tgz
npm http 200 https://registry.npmjs.org/on-finished/-/on-finished-2.3.0.tgz
npm http 200 https://registry.npmjs.org/parseurl/-/parseurl-1.3.1.tgz
npm http 200 https://registry.npmjs.org/path-to-regexp/-/path-to-regexp-0.1.7.tgz
npm http 200 https://registry.npmjs.org/proxy-addr/-/proxy-addr-1.0.10.tgz
npm http GET https://registry.npmjs.org/parseuri/-/parseuri-0.0.4.tgz
npm http GET https://registry.npmjs.org/to-array/-/to-array-0.1.4.tgz
npm http GET https://registry.npmjs.org/engine.io-client/-/engine.io-client-1.6.8.tgz
npm http 200 https://registry.npmjs.org/range-parser/-/range-parser-1.0.3.tgz
npm http GET https://registry.npmjs.org/backo2/-/backo2-1.0.2.tgz
npm http 200 https://registry.npmjs.org/send/-/send-0.13.1.tgz
npm http 200 https://registry.npmjs.org/utils-merge/-/utils-merge-1.0.0.tgz
npm http 200 https://registry.npmjs.org/array-flatten/-/array-flatten-1.1.1.tgz
npm http 200 https://registry.npmjs.org/serve-static/-/serve-static-1.10.2.tgz
npm http 200 https://registry.npmjs.org/type-is/-/type-is-1.6.11.tgz
npm http 200 https://registry.npmjs.org/vary/-/vary-1.0.1.tgz
npm http 200 https://registry.npmjs.org/qs/-/qs-4.0.0.tgz
npm http 200 https://registry.npmjs.org/accepts/-/accepts-1.2.13.tgz
npm http 200 https://registry.npmjs.org/component-emitter/-/component-emitter-1.2.0.tgz
npm http 200 https://registry.npmjs.org/component-bind/-/component-bind-1.0.0.tgz
npm http 200 https://registry.npmjs.org/object-component/-/object-component-0.0.3.tgz
npm http 200 https://registry.npmjs.org/parseuri/-/parseuri-0.0.4.tgz
npm http 200 https://registry.npmjs.org/to-array/-/to-array-0.1.4.tgz
npm http 200 https://registry.npmjs.org/engine.io-client/-/engine.io-client-1.6.8.tgz
npm http 200 https://registry.npmjs.org/backo2/-/backo2-1.0.2.tgz
npm http GET https://registry.npmjs.org/stack-trace
npm http GET https://registry.npmjs.org/colors
npm http GET https://registry.npmjs.org/cycle
npm http GET https://registry.npmjs.org/eyes
npm http GET https://registry.npmjs.org/isstream
npm http GET https://registry.npmjs.org/pkginfo
npm http GET https://registry.npmjs.org/async
npm http 200 https://registry.npmjs.org/stack-trace
npm http 200 https://registry.npmjs.org/isstream
npm http 200 https://registry.npmjs.org/eyes
npm http 200 https://registry.npmjs.org/cycle
npm http 200 https://registry.npmjs.org/colors
npm http 200 https://registry.npmjs.org/pkginfo
npm http 200 https://registry.npmjs.org/async
npm http GET https://registry.npmjs.org/isstream/-/isstream-0.1.2.tgz
npm http GET https://registry.npmjs.org/stack-trace/-/stack-trace-0.0.9.tgz
npm http GET https://registry.npmjs.org/eyes/-/eyes-0.1.8.tgz
npm http GET https://registry.npmjs.org/cycle/-/cycle-1.0.3.tgz
npm http GET https://registry.npmjs.org/colors/-/colors-1.0.3.tgz
npm http GET https://registry.npmjs.org/pkginfo/-/pkginfo-0.3.1.tgz
npm http GET https://registry.npmjs.org/async/-/async-1.0.0.tgz
npm http GET https://registry.npmjs.org/falafel
npm http GET https://registry.npmjs.org/through2
npm http 200 https://registry.npmjs.org/eyes/-/eyes-0.1.8.tgz
npm http 200 https://registry.npmjs.org/isstream/-/isstream-0.1.2.tgz
npm http 200 https://registry.npmjs.org/stack-trace/-/stack-trace-0.0.9.tgz
npm http 200 https://registry.npmjs.org/pkginfo/-/pkginfo-0.3.1.tgz
npm http 200 https://registry.npmjs.org/cycle/-/cycle-1.0.3.tgz
npm http 200 https://registry.npmjs.org/colors/-/colors-1.0.3.tgz
npm http 200 https://registry.npmjs.org/async/-/async-1.0.0.tgz
npm http 200 https://registry.npmjs.org/falafel
npm http 200 https://registry.npmjs.org/through2
npm http GET https://registry.npmjs.org/esmangle-evaluator
npm http GET https://registry.npmjs.org/recast
npm http GET https://registry.npmjs.org/through2
npm http 200 https://registry.npmjs.org/esmangle-evaluator
npm http 304 https://registry.npmjs.org/through2
npm http GET https://registry.npmjs.org/falafel/-/falafel-1.2.0.tgz
npm http GET https://registry.npmjs.org/through2/-/through2-0.6.5.tgz
npm http 200 https://registry.npmjs.org/recast
npm http GET https://registry.npmjs.org/esprima-fb
npm http GET https://registry.npmjs.org/jstransform
npm http GET https://registry.npmjs.org/socket.io-parser/-/socket.io-parser-2.2.2.tgz
npm http GET https://registry.npmjs.org/better-assert
npm http GET https://registry.npmjs.org/isarray
npm http 200 https://registry.npmjs.org/through2/-/through2-0.6.5.tgz
npm http 200 https://registry.npmjs.org/falafel/-/falafel-1.2.0.tgz
npm http GET https://registry.npmjs.org/unpipe
npm http GET https://registry.npmjs.org/esmangle-evaluator/-/esmangle-evaluator-1.0.0.tgz
npm http 200 https://registry.npmjs.org/esprima-fb
npm http 200 https://registry.npmjs.org/jstransform
npm http 200 https://registry.npmjs.org/socket.io-parser/-/socket.io-parser-2.2.2.tgz
npm http GET https://registry.npmjs.org/recast/-/recast-0.10.43.tgz
npm http GET https://registry.npmjs.org/ee-first
npm http GET https://registry.npmjs.org/forwarded
npm http GET https://registry.npmjs.org/ipaddr.js
npm http 200 https://registry.npmjs.org/isarray
npm http GET https://registry.npmjs.org/media-typer
npm http GET https://registry.npmjs.org/negotiator
npm http 200 https://registry.npmjs.org/better-assert
npm http GET https://registry.npmjs.org/mime-types
npm http GET https://registry.npmjs.org/mime-types
npm http 200 https://registry.npmjs.org/unpipe
npm http 200 https://registry.npmjs.org/media-typer
npm http 200 https://registry.npmjs.org/esmangle-evaluator/-/esmangle-evaluator-1.0.0.tgz
npm http 200 https://registry.npmjs.org/ipaddr.js
npm http GET https://registry.npmjs.org/esprima-fb/-/esprima-fb-3001.0001.0000-dev-harmony-fb.tgz
npm http GET https://registry.npmjs.org/jstransform/-/jstransform-3.0.0.tgz
npm http GET https://registry.npmjs.org/isarray/-/isarray-0.0.1.tgz
npm http GET https://registry.npmjs.org/better-assert/-/better-assert-1.0.2.tgz
npm http 200 https://registry.npmjs.org/negotiator
npm http GET https://registry.npmjs.org/media-typer/-/media-typer-0.3.0.tgz
npm http GET https://registry.npmjs.org/unpipe/-/unpipe-1.0.0.tgz
npm http 200 https://registry.npmjs.org/recast/-/recast-0.10.43.tgz
npm http 200 https://registry.npmjs.org/mime-types
npm http 200 https://registry.npmjs.org/ee-first
npm http GET https://registry.npmjs.org/ipaddr.js/-/ipaddr.js-1.0.5.tgz
npm http 200 https://registry.npmjs.org/mime-types
npm http 200 https://registry.npmjs.org/forwarded
npm http 200 https://registry.npmjs.org/media-typer/-/media-typer-0.3.0.tgz
npm http 200 https://registry.npmjs.org/unpipe/-/unpipe-1.0.0.tgz
npm http GET https://registry.npmjs.org/negotiator/-/negotiator-0.5.3.tgz
npm http GET https://registry.npmjs.org/destroy
npm http GET https://registry.npmjs.org/http-errors
npm http GET https://registry.npmjs.org/ms
npm http GET https://registry.npmjs.org/statuses
npm http 200 https://registry.npmjs.org/isarray/-/isarray-0.0.1.tgz
npm http 200 https://registry.npmjs.org/ipaddr.js/-/ipaddr.js-1.0.5.tgz
npm http GET https://registry.npmjs.org/mime
npm http GET https://registry.npmjs.org/ee-first/-/ee-first-1.1.1.tgz
npm http GET https://registry.npmjs.org/mime-types/-/mime-types-2.1.9.tgz
npm http 200 https://registry.npmjs.org/jstransform/-/jstransform-3.0.0.tgz
npm http 200 https://registry.npmjs.org/esprima-fb/-/esprima-fb-3001.0001.0000-dev-harmony-fb.tgz
npm http 200 https://registry.npmjs.org/better-assert/-/better-assert-1.0.2.tgz
npm http 200 https://registry.npmjs.org/negotiator/-/negotiator-0.5.3.tgz
npm http GET https://registry.npmjs.org/forwarded/-/forwarded-0.1.0.tgz
npm http 200 https://registry.npmjs.org/mime-types/-/mime-types-2.1.9.tgz
npm http GET https://registry.npmjs.org/json3
npm http GET https://registry.npmjs.org/benchmark
npm http 200 https://registry.npmjs.org/statuses
npm http 200 https://registry.npmjs.org/ee-first/-/ee-first-1.1.1.tgz
npm http 200 https://registry.npmjs.org/ms
npm http 200 https://registry.npmjs.org/destroy
npm http 200 https://registry.npmjs.org/json3
npm http 200 https://registry.npmjs.org/http-errors
npm http 200 https://registry.npmjs.org/mime
npm http GET https://registry.npmjs.org/component-emitter/-/component-emitter-1.1.2.tgz
npm http 200 https://registry.npmjs.org/forwarded/-/forwarded-0.1.0.tgz
npm http GET https://registry.npmjs.org/statuses/-/statuses-1.2.1.tgz
npm http 200 https://registry.npmjs.org/benchmark
npm http GET https://registry.npmjs.org/ms/-/ms-0.7.1.tgz
npm http GET https://registry.npmjs.org/json3/-/json3-3.3.2.tgz
npm http GET https://registry.npmjs.org/mime/-/mime-1.3.4.tgz
npm http GET https://registry.npmjs.org/destroy/-/destroy-1.0.4.tgz
npm http GET https://registry.npmjs.org/http-errors/-/http-errors-1.3.1.tgz
npm http GET https://registry.npmjs.org/benchmark/-/benchmark-1.0.0.tgz
npm http 200 https://registry.npmjs.org/component-emitter/-/component-emitter-1.1.2.tgz
npm http 200 https://registry.npmjs.org/statuses/-/statuses-1.2.1.tgz
npm http 200 https://registry.npmjs.org/destroy/-/destroy-1.0.4.tgz
npm http 200 https://registry.npmjs.org/mime/-/mime-1.3.4.tgz
npm http 200 https://registry.npmjs.org/ms/-/ms-0.7.1.tgz
npm http 200 https://registry.npmjs.org/json3/-/json3-3.3.2.tgz
npm http 200 https://registry.npmjs.org/http-errors/-/http-errors-1.3.1.tgz
npm http 200 https://registry.npmjs.org/benchmark/-/benchmark-1.0.0.tgz
npm http GET https://registry.npmjs.org/readable-stream
npm http GET https://registry.npmjs.org/xtend
npm http 200 https://registry.npmjs.org/xtend
npm http 200 https://registry.npmjs.org/readable-stream
npm http GET https://registry.npmjs.org/callsite
npm http GET https://registry.npmjs.org/base64id
npm http GET https://registry.npmjs.org/ws
npm http GET https://registry.npmjs.org/engine.io-parser
npm http GET https://registry.npmjs.org/accepts
npm http GET https://registry.npmjs.org/mime-db
npm http GET https://registry.npmjs.org/debug
npm http GET https://registry.npmjs.org/component-emitter
npm http GET https://registry.npmjs.org/json3/-/json3-3.2.6.tgz
npm http 200 https://registry.npmjs.org/callsite
npm http GET https://registry.npmjs.org/foreach
npm http GET https://registry.npmjs.org/object-keys
npm http GET https://registry.npmjs.org/acorn
npm http 200 https://registry.npmjs.org/base64id
npm http GET https://registry.npmjs.org/callsite/-/callsite-1.0.0.tgz
npm http GET https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/debug
npm http 200 https://registry.npmjs.org/mime-db
npm http 200 https://registry.npmjs.org/engine.io-parser
npm http 304 https://registry.npmjs.org/component-emitter
npm http GET https://registry.npmjs.org/base64id/-/base64id-0.1.0.tgz
npm http 200 https://registry.npmjs.org/ws
npm http 200 https://registry.npmjs.org/foreach
npm http 200 https://registry.npmjs.org/object-keys
npm http 200 https://registry.npmjs.org/json3/-/json3-3.2.6.tgz
npm http 200 https://registry.npmjs.org/inherits
npm http GET https://registry.npmjs.org/accepts/-/accepts-1.1.4.tgz
npm http GET https://registry.npmjs.org/debug/-/debug-0.7.4.tgz
npm http 200 https://registry.npmjs.org/acorn
npm http GET https://registry.npmjs.org/engine.io-parser/-/engine.io-parser-1.2.4.tgz
npm http GET https://registry.npmjs.org/mime-db/-/mime-db-1.21.0.tgz
npm http GET https://registry.npmjs.org/ws/-/ws-1.0.1.tgz
npm http GET https://registry.npmjs.org/foreach/-/foreach-2.0.5.tgz
npm http GET https://registry.npmjs.org/object-keys/-/object-keys-1.0.9.tgz
npm http 200 https://registry.npmjs.org/callsite/-/callsite-1.0.0.tgz
npm http 200 https://registry.npmjs.org/engine.io-parser/-/engine.io-parser-1.2.4.tgz
npm http 200 https://registry.npmjs.org/base64id/-/base64id-0.1.0.tgz
npm http 200 https://registry.npmjs.org/ws/-/ws-1.0.1.tgz
npm http 200 https://registry.npmjs.org/mime-db/-/mime-db-1.21.0.tgz
npm http 200 https://registry.npmjs.org/accepts/-/accepts-1.1.4.tgz
npm http 200 https://registry.npmjs.org/foreach/-/foreach-2.0.5.tgz
npm http 200 https://registry.npmjs.org/object-keys/-/object-keys-1.0.9.tgz
npm http 200 https://registry.npmjs.org/debug/-/debug-0.7.4.tgz
npm http GET https://registry.npmjs.org/jsonfile
npm http GET https://registry.npmjs.org/graceful-fs
npm http GET https://registry.npmjs.org/path-is-absolute
npm http GET https://registry.npmjs.org/rimraf
npm http 200 https://registry.npmjs.org/jsonfile
npm http 200 https://registry.npmjs.org/path-is-absolute
npm http 200 https://registry.npmjs.org/graceful-fs
npm http 200 https://registry.npmjs.org/rimraf
npm http GET https://registry.npmjs.org/jsonfile/-/jsonfile-2.2.3.tgz
npm http GET https://registry.npmjs.org/graceful-fs/-/graceful-fs-4.1.2.tgz
npm http GET https://registry.npmjs.org/rimraf/-/rimraf-2.5.1.tgz
npm http GET https://registry.npmjs.org/negotiator/-/negotiator-0.4.9.tgz
npm http GET https://registry.npmjs.org/mime-types/-/mime-types-2.0.14.tgz
npm http GET https://registry.npmjs.org/core-util-is
npm http GET https://registry.npmjs.org/string_decoder
npm http 200 https://registry.npmjs.org/jsonfile/-/jsonfile-2.2.3.tgz
npm http GET https://registry.npmjs.org/has-cors
npm http GET https://registry.npmjs.org/xmlhttprequest-ssl
npm http GET https://registry.npmjs.org/parsejson
npm http GET https://registry.npmjs.org/parseqs
npm http 200 https://registry.npmjs.org/graceful-fs/-/graceful-fs-4.1.2.tgz
npm http GET https://registry.npmjs.org/component-inherit
npm http GET https://registry.npmjs.org/yeast
npm http 200 https://registry.npmjs.org/rimraf/-/rimraf-2.5.1.tgz
npm http 200 https://registry.npmjs.org/negotiator/-/negotiator-0.4.9.tgz
npm http 200 https://registry.npmjs.org/mime-types/-/mime-types-2.0.14.tgz
npm http 200 https://registry.npmjs.org/core-util-is
npm http 200 https://registry.npmjs.org/string_decoder
npm http 200 https://registry.npmjs.org/parseqs
npm http 200 https://registry.npmjs.org/component-inherit
npm http 200 https://registry.npmjs.org/has-cors
npm http 200 https://registry.npmjs.org/parsejson
npm http 200 https://registry.npmjs.org/xmlhttprequest-ssl
npm http 200 https://registry.npmjs.org/yeast
npm http GET https://registry.npmjs.org/core-util-is/-/core-util-is-1.0.2.tgz
npm http GET https://registry.npmjs.org/parseqs/-/parseqs-0.0.2.tgz
npm http GET https://registry.npmjs.org/component-inherit/-/component-inherit-0.0.3.tgz
npm http GET https://registry.npmjs.org/parsejson/-/parsejson-0.0.1.tgz
npm http GET https://registry.npmjs.org/has-cors/-/has-cors-1.1.0.tgz
npm http GET https://registry.npmjs.org/xmlhttprequest-ssl/-/xmlhttprequest-ssl-1.5.1.tgz
npm http GET https://registry.npmjs.org/yeast/-/yeast-0.1.2.tgz
npm http GET https://registry.npmjs.org/base64-arraybuffer
npm http GET https://registry.npmjs.org/blob
npm http GET https://registry.npmjs.org/utf8
npm http GET https://registry.npmjs.org/after
npm http GET https://registry.npmjs.org/arraybuffer.slice
npm http GET https://registry.npmjs.org/has-binary
npm http GET https://registry.npmjs.org/base62
npm http GET https://registry.npmjs.org/source-map
npm http 200 https://registry.npmjs.org/core-util-is/-/core-util-is-1.0.2.tgz
npm http 200 https://registry.npmjs.org/component-inherit/-/component-inherit-0.0.3.tgz
npm http 200 https://registry.npmjs.org/parseqs/-/parseqs-0.0.2.tgz
npm http 200 https://registry.npmjs.org/parsejson/-/parsejson-0.0.1.tgz
npm http 200 https://registry.npmjs.org/has-cors/-/has-cors-1.1.0.tgz
npm http GET https://registry.npmjs.org/private
npm http GET https://registry.npmjs.org/ast-types
npm http 200 https://registry.npmjs.org/xmlhttprequest-ssl/-/xmlhttprequest-ssl-1.5.1.tgz
npm http 200 https://registry.npmjs.org/yeast/-/yeast-0.1.2.tgz
npm http GET https://registry.npmjs.org/source-map
npm http GET https://registry.npmjs.org/esprima-fb/-/esprima-fb-15001.1001.0-dev-harmony-fb.tgz
npm http GET https://registry.npmjs.org/glob
npm http 200 https://registry.npmjs.org/base64-arraybuffer
npm http 200 https://registry.npmjs.org/blob
npm http 200 https://registry.npmjs.org/arraybuffer.slice
npm http 200 https://registry.npmjs.org/utf8
npm http 304 https://registry.npmjs.org/has-binary
npm http 200 https://registry.npmjs.org/base62
npm http 200 https://registry.npmjs.org/after
npm http 200 https://registry.npmjs.org/private
npm http GET https://registry.npmjs.org/base64-arraybuffer/-/base64-arraybuffer-0.1.2.tgz
npm http GET https://registry.npmjs.org/blob/-/blob-0.0.4.tgz
npm http GET https://registry.npmjs.org/arraybuffer.slice/-/arraybuffer.slice-0.0.6.tgz
npm http GET https://registry.npmjs.org/utf8/-/utf8-2.1.0.tgz
npm http GET https://registry.npmjs.org/has-binary/-/has-binary-0.1.6.tgz
npm http GET https://registry.npmjs.org/base62/-/base62-0.1.1.tgz
npm http GET https://registry.npmjs.org/mime-db/-/mime-db-1.12.0.tgz
npm http GET https://registry.npmjs.org/after/-/after-0.8.1.tgz
npm http 200 https://registry.npmjs.org/source-map
npm http GET https://registry.npmjs.org/private/-/private-0.1.6.tgz
npm http 200 https://registry.npmjs.org/glob
npm http 200 https://registry.npmjs.org/ast-types
npm http 200 https://registry.npmjs.org/source-map
npm http 200 https://registry.npmjs.org/esprima-fb/-/esprima-fb-15001.1001.0-dev-harmony-fb.tgz
npm http 200 https://registry.npmjs.org/base64-arraybuffer/-/base64-arraybuffer-0.1.2.tgz
npm http GET https://registry.npmjs.org/source-map/-/source-map-0.1.31.tgz
npm http 200 https://registry.npmjs.org/arraybuffer.slice/-/arraybuffer.slice-0.0.6.tgz
npm http GET https://registry.npmjs.org/ast-types/-/ast-types-0.8.15.tgz
npm http GET https://registry.npmjs.org/glob/-/glob-6.0.4.tgz
npm http 200 https://registry.npmjs.org/has-binary/-/has-binary-0.1.6.tgz
npm http GET https://registry.npmjs.org/source-map/-/source-map-0.5.3.tgz
npm http 200 https://registry.npmjs.org/blob/-/blob-0.0.4.tgz
npm http 200 https://registry.npmjs.org/utf8/-/utf8-2.1.0.tgz
npm http 200 https://registry.npmjs.org/base62/-/base62-0.1.1.tgz
npm http 200 https://registry.npmjs.org/after/-/after-0.8.1.tgz
npm http 200 https://registry.npmjs.org/private/-/private-0.1.6.tgz
npm http 200 https://registry.npmjs.org/source-map/-/source-map-0.1.31.tgz
npm http 200 https://registry.npmjs.org/mime-db/-/mime-db-1.12.0.tgz
npm http 200 https://registry.npmjs.org/ast-types/-/ast-types-0.8.15.tgz
npm http 200 https://registry.npmjs.org/glob/-/glob-6.0.4.tgz
npm http 200 https://registry.npmjs.org/source-map/-/source-map-0.5.3.tgz
npm http GET https://registry.npmjs.org/options
npm http GET https://registry.npmjs.org/ultron
npm http 200 https://registry.npmjs.org/options
npm http 200 https://registry.npmjs.org/ultron
npm http GET https://registry.npmjs.org/options/-/options-0.0.6.tgz
npm http GET https://registry.npmjs.org/ultron/-/ultron-1.0.2.tgz
npm http 200 https://registry.npmjs.org/ultron/-/ultron-1.0.2.tgz
npm http 200 https://registry.npmjs.org/options/-/options-0.0.6.tgz
npm http GET https://registry.npmjs.org/once
npm http GET https://registry.npmjs.org/inflight
npm http GET https://registry.npmjs.org/minimatch
npm http 200 https://registry.npmjs.org/once
npm http 200 https://registry.npmjs.org/inflight
npm http GET https://registry.npmjs.org/once/-/once-1.3.3.tgz
npm http 200 https://registry.npmjs.org/minimatch
npm http GET https://registry.npmjs.org/minimatch/-/minimatch-3.0.0.tgz
npm http 200 https://registry.npmjs.org/once/-/once-1.3.3.tgz
npm http 200 https://registry.npmjs.org/minimatch/-/minimatch-3.0.0.tgz
npm http GET https://registry.npmjs.org/wrappy
npm http GET https://registry.npmjs.org/brace-expansion
npm http GET https://registry.npmjs.org/amdefine
npm http 200 https://registry.npmjs.org/wrappy
npm http 200 https://registry.npmjs.org/brace-expansion
npm http GET https://registry.npmjs.org/brace-expansion/-/brace-expansion-1.1.2.tgz
npm http 200 https://registry.npmjs.org/amdefine
npm http 200 https://registry.npmjs.org/brace-expansion/-/brace-expansion-1.1.2.tgz
npm http GET https://registry.npmjs.org/concat-map
npm http GET https://registry.npmjs.org/balanced-match
npm http 200 https://registry.npmjs.org/concat-map
npm http GET https://registry.npmjs.org/concat-map/-/concat-map-0.0.1.tgz
npm http 200 https://registry.npmjs.org/balanced-match
npm http GET https://registry.npmjs.org/balanced-match/-/balanced-match-0.3.0.tgz
npm http 200 https://registry.npmjs.org/concat-map/-/concat-map-0.0.1.tgz
npm http 200 https://registry.npmjs.org/balanced-match/-/balanced-match-0.3.0.tgz
npm WARN package.json thali@2.1.0 No README data
npm http GET https://registry.npmjs.org/body-parser
npm http GET https://registry.npmjs.org/ip
npm http GET https://registry.npmjs.org/javascript-state-machine
npm http GET https://registry.npmjs.org/multiplex
npm http GET https://registry.npmjs.org/node-ssdp
npm http GET https://registry.npmjs.org/urlsafe-base64
npm http GET https://registry.npmjs.org/jsdoc
npm http GET https://registry.npmjs.org/express
npm http GET https://registry.npmjs.org/node-uuid
npm http GET https://registry.npmjs.org/winston
npm http GET https://registry.npmjs.org/lie
npm http GET https://registry.npmjs.org/request
npm http 200 https://registry.npmjs.org/ip
npm http GET https://registry.npmjs.org/ip/-/ip-1.1.0.tgz
npm http 200 https://registry.npmjs.org/body-parser
npm http GET https://registry.npmjs.org/body-parser/-/body-parser-1.14.2.tgz
npm http 200 https://registry.npmjs.org/jsdoc
npm http GET https://registry.npmjs.org/jsdoc/-/jsdoc-3.4.0.tgz
npm http 304 https://registry.npmjs.org/express
npm http GET https://registry.npmjs.org/express/-/express-4.13.3.tgz
npm http 200 https://registry.npmjs.org/ip/-/ip-1.1.0.tgz
npm http 304 https://registry.npmjs.org/node-uuid
npm http 200 https://registry.npmjs.org/urlsafe-base64
npm http GET https://registry.npmjs.org/urlsafe-base64/-/urlsafe-base64-1.0.0.tgz
npm http 304 https://registry.npmjs.org/winston
npm http 304 https://registry.npmjs.org/lie
npm http GET https://registry.npmjs.org/winston/-/winston-1.1.2.tgz
npm http 200 https://registry.npmjs.org/body-parser/-/body-parser-1.14.2.tgz
npm http 200 https://registry.npmjs.org/jsdoc/-/jsdoc-3.4.0.tgz
npm http 200 https://registry.npmjs.org/request
npm http GET https://registry.npmjs.org/request/-/request-2.69.0.tgz
npm http 200 https://registry.npmjs.org/express/-/express-4.13.3.tgz
npm http 200 https://registry.npmjs.org/javascript-state-machine
npm http GET https://registry.npmjs.org/javascript-state-machine/-/javascript-state-machine-2.3.5.tgz
npm http 200 https://registry.npmjs.org/urlsafe-base64/-/urlsafe-base64-1.0.0.tgz
npm http 200 https://registry.npmjs.org/winston/-/winston-1.1.2.tgz
npm http 200 https://registry.npmjs.org/multiplex
npm http GET https://registry.npmjs.org/multiplex/-/multiplex-6.6.1.tgz
npm http 200 https://registry.npmjs.org/request/-/request-2.69.0.tgz
npm http 200 https://registry.npmjs.org/javascript-state-machine/-/javascript-state-machine-2.3.5.tgz
npm http 200 https://registry.npmjs.org/node-ssdp
npm http 200 https://registry.npmjs.org/multiplex/-/multiplex-6.6.1.tgz
npm http GET https://registry.npmjs.org/varint
npm http GET https://registry.npmjs.org/duplexify
npm http GET https://registry.npmjs.org/readable-stream/-/readable-stream-2.0.5.tgz
npm http GET https://registry.npmjs.org/bytes
npm http GET https://registry.npmjs.org/iconv-lite
npm http GET https://registry.npmjs.org/raw-body
npm http GET https://registry.npmjs.org/content-type
npm http GET https://registry.npmjs.org/depd
npm http GET https://registry.npmjs.org/http-errors
npm http GET https://registry.npmjs.org/on-finished
npm http GET https://registry.npmjs.org/qs
npm http GET https://registry.npmjs.org/type-is
npm http GET https://registry.npmjs.org/es3ify
npm http GET https://registry.npmjs.org/immediate
npm http GET https://registry.npmjs.org/inline-process-browser
npm http GET https://registry.npmjs.org/unreachable-branch-transform
npm http 200 https://registry.npmjs.org/duplexify
npm http GET https://registry.npmjs.org/duplexify/-/duplexify-3.4.2.tgz
npm http 200 https://registry.npmjs.org/readable-stream/-/readable-stream-2.0.5.tgz
npm http 304 https://registry.npmjs.org/content-type
npm http 200 https://registry.npmjs.org/varint
npm http 200 https://registry.npmjs.org/bytes
npm http 304 https://registry.npmjs.org/depd
npm http GET https://registry.npmjs.org/bytes/-/bytes-2.2.0.tgz
npm http GET https://registry.npmjs.org/varint/-/varint-4.0.0.tgz
npm http 304 https://registry.npmjs.org/http-errors
npm http 304 https://registry.npmjs.org/on-finished
npm http 200 https://registry.npmjs.org/raw-body
npm http 304 https://registry.npmjs.org/qs
npm http 200 https://registry.npmjs.org/iconv-lite
npm http 304 https://registry.npmjs.org/type-is
npm http 304 https://registry.npmjs.org/immediate
npm http 304 https://registry.npmjs.org/es3ify
npm http 304 https://registry.npmjs.org/inline-process-browser
npm http GET https://registry.npmjs.org/raw-body/-/raw-body-2.1.5.tgz
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http GET https://registry.npmjs.org/qs/-/qs-5.2.0.tgz
npm http 200 https://registry.npmjs.org/duplexify/-/duplexify-3.4.2.tgz
npm http GET https://registry.npmjs.org/iconv-lite/-/iconv-lite-0.4.13.tgz
npm http 200 https://registry.npmjs.org/bytes/-/bytes-2.2.0.tgz
npm http 200 https://registry.npmjs.org/raw-body/-/raw-body-2.1.5.tgz
npm http GET https://registry.npmjs.org/falafel
npm http GET https://registry.npmjs.org/through2
npm http 200 https://registry.npmjs.org/varint/-/varint-4.0.0.tgz
npm http 200 https://registry.npmjs.org/qs/-/qs-5.2.0.tgz
npm http 200 https://registry.npmjs.org/iconv-lite/-/iconv-lite-0.4.13.tgz
npm http GET https://registry.npmjs.org/esmangle-evaluator
npm http GET https://registry.npmjs.org/recast
npm http GET https://registry.npmjs.org/through2
npm http GET https://registry.npmjs.org/content-disposition
npm http GET https://registry.npmjs.org/cookie
npm http GET https://registry.npmjs.org/cookie-signature
npm http GET https://registry.npmjs.org/debug
npm http GET https://registry.npmjs.org/escape-html
npm http GET https://registry.npmjs.org/etag
npm http GET https://registry.npmjs.org/finalhandler
npm http GET https://registry.npmjs.org/fresh
npm http GET https://registry.npmjs.org/merge-descriptors
npm http GET https://registry.npmjs.org/methods
npm http GET https://registry.npmjs.org/parseurl
npm http GET https://registry.npmjs.org/path-to-regexp
npm http GET https://registry.npmjs.org/proxy-addr
npm http GET https://registry.npmjs.org/range-parser
npm http GET https://registry.npmjs.org/send
npm http GET https://registry.npmjs.org/serve-static
npm http GET https://registry.npmjs.org/utils-merge
npm http GET https://registry.npmjs.org/vary
npm http GET https://registry.npmjs.org/accepts
npm http GET https://registry.npmjs.org/array-flatten
npm http GET https://registry.npmjs.org/depd/-/depd-1.0.1.tgz
npm http GET https://registry.npmjs.org/esprima-fb
npm http GET https://registry.npmjs.org/jstransform
npm http GET https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/falafel
npm http 304 https://registry.npmjs.org/through2
npm http GET https://registry.npmjs.org/extend
npm http GET https://registry.npmjs.org/har-validator
npm http GET https://registry.npmjs.org/is-typedarray
npm http GET https://registry.npmjs.org/aws4
npm http 304 https://registry.npmjs.org/cookie
npm http 304 https://registry.npmjs.org/content-disposition
npm http GET https://registry.npmjs.org/combined-stream
npm http GET https://registry.npmjs.org/form-data
npm http GET https://registry.npmjs.org/forever-agent
npm http GET https://registry.npmjs.org/isstream
npm http GET https://registry.npmjs.org/mime-types
npm http GET https://registry.npmjs.org/http-signature
npm http GET https://registry.npmjs.org/json-stringify-safe
npm http GET https://registry.npmjs.org/hawk
npm http GET https://registry.npmjs.org/oauth-sign
npm http GET https://registry.npmjs.org/stringstream
npm http GET https://registry.npmjs.org/tunnel-agent
npm http GET https://registry.npmjs.org/tough-cookie
npm http GET https://registry.npmjs.org/aws-sign2
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http GET https://registry.npmjs.org/caseless
npm http GET https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/cookie-signature
npm http GET https://registry.npmjs.org/qs/-/qs-6.0.2.tgz
npm http 304 https://registry.npmjs.org/escape-html
npm http 304 https://registry.npmjs.org/etag
npm http 304 https://registry.npmjs.org/fresh
npm http 304 https://registry.npmjs.org/merge-descriptors
npm http 304 https://registry.npmjs.org/finalhandler
npm http GET https://registry.npmjs.org/content-disposition/-/content-disposition-0.5.0.tgz
npm http GET https://registry.npmjs.org/cookie/-/cookie-0.1.3.tgz
npm http 304 https://registry.npmjs.org/methods
npm http 200 https://registry.npmjs.org/depd/-/depd-1.0.1.tgz
npm http 304 https://registry.npmjs.org/parseurl
npm http 304 https://registry.npmjs.org/path-to-regexp
npm http 304 https://registry.npmjs.org/range-parser
npm http 304 https://registry.npmjs.org/proxy-addr
npm http 304 https://registry.npmjs.org/send
npm http 304 https://registry.npmjs.org/serve-static
npm http 304 https://registry.npmjs.org/utils-merge
npm http 304 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/vary
npm http GET https://registry.npmjs.org/escape-html/-/escape-html-1.0.2.tgz
npm http 304 https://registry.npmjs.org/array-flatten
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 304 https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/through
npm http GET https://registry.npmjs.org/merge-descriptors/-/merge-descriptors-1.0.0.tgz
npm http GET https://registry.npmjs.org/finalhandler/-/finalhandler-0.4.0.tgz
npm http 200 https://registry.npmjs.org/is-typedarray
npm http 200 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/combined-stream
npm http 200 https://registry.npmjs.org/qs/-/qs-6.0.2.tgz
npm http 200 https://registry.npmjs.org/forever-agent
npm http GET https://registry.npmjs.org/send/-/send-0.13.0.tgz
npm http 200 https://registry.npmjs.org/cookie/-/cookie-0.1.3.tgz
npm http 200 https://registry.npmjs.org/har-validator
npm http 200 https://registry.npmjs.org/content-disposition/-/content-disposition-0.5.0.tgz
npm http 200 https://registry.npmjs.org/finalhandler/-/finalhandler-0.4.0.tgz
npm http 304 https://registry.npmjs.org/isstream
npm http 200 https://registry.npmjs.org/aws4
npm http 200 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/mime-types
npm http 200 https://registry.npmjs.org/send/-/send-0.13.0.tgz
npm http 200 https://registry.npmjs.org/http-signature
npm http 200 https://registry.npmjs.org/json-stringify-safe
npm http 200 https://registry.npmjs.org/stringstream
npm http 200 https://registry.npmjs.org/oauth-sign
npm http 200 https://registry.npmjs.org/tunnel-agent
npm http GET https://registry.npmjs.org/extend/-/extend-3.0.0.tgz
npm http GET https://registry.npmjs.org/is-typedarray/-/is-typedarray-1.0.0.tgz
npm http 200 https://registry.npmjs.org/hawk
npm http 200 https://registry.npmjs.org/escape-html/-/escape-html-1.0.2.tgz
npm http 200 https://registry.npmjs.org/merge-descriptors/-/merge-descriptors-1.0.0.tgz
npm http 304 https://registry.npmjs.org/caseless
npm http 200 https://registry.npmjs.org/aws-sign2
npm http GET https://registry.npmjs.org/forever-agent/-/forever-agent-0.6.1.tgz
npm http 200 https://registry.npmjs.org/bl
npm http GET https://registry.npmjs.org/har-validator/-/har-validator-2.0.6.tgz
npm http GET https://registry.npmjs.org/aws4/-/aws4-1.2.1.tgz
npm http 200 https://registry.npmjs.org/tough-cookie
npm http GET https://registry.npmjs.org/form-data/-/form-data-1.0.0-rc3.tgz
npm http GET https://registry.npmjs.org/http-signature/-/http-signature-1.1.1.tgz
npm http GET https://registry.npmjs.org/stringstream/-/stringstream-0.0.5.tgz
npm http GET https://registry.npmjs.org/oauth-sign/-/oauth-sign-0.8.1.tgz
npm http GET https://registry.npmjs.org/tunnel-agent/-/tunnel-agent-0.4.2.tgz
npm http GET https://registry.npmjs.org/hawk/-/hawk-3.1.3.tgz
npm http GET https://registry.npmjs.org/caseless/-/caseless-0.11.0.tgz
npm http GET https://registry.npmjs.org/aws-sign2/-/aws-sign2-0.6.0.tgz
npm http GET https://registry.npmjs.org/bl/-/bl-1.0.1.tgz
npm http GET https://registry.npmjs.org/tough-cookie/-/tough-cookie-2.2.1.tgz
npm http 200 https://registry.npmjs.org/is-typedarray/-/is-typedarray-1.0.0.tgz
npm http 200 https://registry.npmjs.org/extend/-/extend-3.0.0.tgz
npm http 200 https://registry.npmjs.org/form-data/-/form-data-1.0.0-rc3.tgz
npm http 200 https://registry.npmjs.org/forever-agent/-/forever-agent-0.6.1.tgz
npm http 200 https://registry.npmjs.org/http-signature/-/http-signature-1.1.1.tgz
npm http 200 https://registry.npmjs.org/oauth-sign/-/oauth-sign-0.8.1.tgz
npm http 200 https://registry.npmjs.org/stringstream/-/stringstream-0.0.5.tgz
npm http 200 https://registry.npmjs.org/tunnel-agent/-/tunnel-agent-0.4.2.tgz
npm http 200 https://registry.npmjs.org/caseless/-/caseless-0.11.0.tgz
npm http 200 https://registry.npmjs.org/hawk/-/hawk-3.1.3.tgz
npm http 200 https://registry.npmjs.org/aws-sign2/-/aws-sign2-0.6.0.tgz
npm http 200 https://registry.npmjs.org/bl/-/bl-1.0.1.tgz
npm http 200 https://registry.npmjs.org/tough-cookie/-/tough-cookie-2.2.1.tgz
npm http 200 https://registry.npmjs.org/har-validator/-/har-validator-2.0.6.tgz
npm http 200 https://registry.npmjs.org/aws4/-/aws4-1.2.1.tgz
npm http GET https://registry.npmjs.org/inherits
npm http GET https://registry.npmjs.org/statuses
npm http GET https://registry.npmjs.org/end-of-stream
npm http GET https://registry.npmjs.org/readable-stream
npm http GET https://registry.npmjs.org/ee-first
npm http GET https://registry.npmjs.org/xtend
npm http GET https://registry.npmjs.org/media-typer
npm http GET https://registry.npmjs.org/unpipe
npm http 304 https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/statuses
npm http 200 https://registry.npmjs.org/end-of-stream
npm http 304 https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/media-typer
npm http 304 https://registry.npmjs.org/unpipe
npm http 304 https://registry.npmjs.org/ee-first
npm http GET https://registry.npmjs.org/end-of-stream/-/end-of-stream-1.0.0.tgz
npm http 304 https://registry.npmjs.org/readable-stream
npm http GET https://registry.npmjs.org/forwarded
npm http GET https://registry.npmjs.org/ipaddr.js
npm http GET https://registry.npmjs.org/negotiator
npm http GET https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/negotiator
npm http 200 https://registry.npmjs.org/end-of-stream/-/end-of-stream-1.0.0.tgz
npm http 304 https://registry.npmjs.org/ipaddr.js
npm http 304 https://registry.npmjs.org/forwarded
npm http 304 https://registry.npmjs.org/ms
npm http GET https://registry.npmjs.org/acorn
npm http GET https://registry.npmjs.org/foreach
npm http GET https://registry.npmjs.org/isarray
npm http GET https://registry.npmjs.org/object-keys
npm http GET https://registry.npmjs.org/destroy
npm http GET https://registry.npmjs.org/mime
npm http GET https://registry.npmjs.org/delayed-stream
npm http GET https://registry.npmjs.org/mime-db
npm http 304 https://registry.npmjs.org/acorn
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/foreach
npm http 304 https://registry.npmjs.org/mime
npm http 304 https://registry.npmjs.org/delayed-stream
npm http 304 https://registry.npmjs.org/destroy
npm http 304 https://registry.npmjs.org/mime-db
npm http GET https://registry.npmjs.org/async
npm http GET https://registry.npmjs.org/destroy/-/destroy-1.0.3.tgz
npm http 304 https://registry.npmjs.org/async
npm http 200 https://registry.npmjs.org/destroy/-/destroy-1.0.3.tgz
npm http GET https://registry.npmjs.org/async/-/async-1.5.2.tgz
npm http GET https://registry.npmjs.org/lru-cache
npm http 200 https://registry.npmjs.org/async/-/async-1.5.2.tgz
npm http 200 https://registry.npmjs.org/lru-cache
npm http GET https://registry.npmjs.org/jsprim
npm http GET https://registry.npmjs.org/sshpk
npm http GET https://registry.npmjs.org/assert-plus
npm http GET https://registry.npmjs.org/lru-cache/-/lru-cache-2.7.3.tgz
npm http GET https://registry.npmjs.org/process-nextick-args
npm http GET https://registry.npmjs.org/string_decoder
npm http GET https://registry.npmjs.org/core-util-is
npm http GET https://registry.npmjs.org/util-deprecate
npm http 200 https://registry.npmjs.org/assert-plus
npm http GET https://registry.npmjs.org/pinkie-promise
npm http GET https://registry.npmjs.org/chalk
npm http 304 https://registry.npmjs.org/core-util-is
npm http GET https://registry.npmjs.org/commander
npm http 200 https://registry.npmjs.org/lru-cache/-/lru-cache-2.7.3.tgz
npm http GET https://registry.npmjs.org/is-my-json-valid
npm http 200 https://registry.npmjs.org/sshpk
npm http 200 https://registry.npmjs.org/util-deprecate
npm http GET https://registry.npmjs.org/assert-plus/-/assert-plus-0.2.0.tgz
npm http 200 https://registry.npmjs.org/jsprim
npm http 200 https://registry.npmjs.org/pinkie-promise
npm http 200 https://registry.npmjs.org/process-nextick-args
npm http 304 https://registry.npmjs.org/string_decoder
npm http GET https://registry.npmjs.org/wrappy
npm http 200 https://registry.npmjs.org/chalk
npm http GET https://registry.npmjs.org/sshpk/-/sshpk-1.7.3.tgz
npm http GET https://registry.npmjs.org/util-deprecate/-/util-deprecate-1.0.2.tgz
npm http 200 https://registry.npmjs.org/commander
npm http 200 https://registry.npmjs.org/is-my-json-valid
npm http GET https://registry.npmjs.org/jsprim/-/jsprim-1.2.2.tgz
npm http GET https://registry.npmjs.org/pinkie-promise/-/pinkie-promise-2.0.0.tgz
npm http GET https://registry.npmjs.org/process-nextick-args/-/process-nextick-args-1.0.6.tgz
npm http GET https://registry.npmjs.org/chalk/-/chalk-1.1.1.tgz
npm http 200 https://registry.npmjs.org/assert-plus/-/assert-plus-0.2.0.tgz
npm http GET https://registry.npmjs.org/commander/-/commander-2.9.0.tgz
npm http GET https://registry.npmjs.org/is-my-json-valid/-/is-my-json-valid-2.12.4.tgz
npm http 200 https://registry.npmjs.org/process-nextick-args/-/process-nextick-args-1.0.6.tgz
npm http 304 https://registry.npmjs.org/wrappy
npm http 200 https://registry.npmjs.org/chalk/-/chalk-1.1.1.tgz
npm http 200 https://registry.npmjs.org/jsprim/-/jsprim-1.2.2.tgz
npm http 200 https://registry.npmjs.org/sshpk/-/sshpk-1.7.3.tgz
npm http 200 https://registry.npmjs.org/util-deprecate/-/util-deprecate-1.0.2.tgz
npm http 200 https://registry.npmjs.org/commander/-/commander-2.9.0.tgz
npm http 200 https://registry.npmjs.org/pinkie-promise/-/pinkie-promise-2.0.0.tgz
npm http 200 https://registry.npmjs.org/is-my-json-valid/-/is-my-json-valid-2.12.4.tgz
npm http GET https://registry.npmjs.org/base62
npm http GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/base62
npm http 304 https://registry.npmjs.org/source-map
npm http GET https://registry.npmjs.org/private
npm http GET https://registry.npmjs.org/ast-types
npm http GET https://registry.npmjs.org/pkginfo
npm http GET https://registry.npmjs.org/stack-trace
npm http GET https://registry.npmjs.org/colors
npm http GET https://registry.npmjs.org/cycle
npm http GET https://registry.npmjs.org/eyes
npm http 304 https://registry.npmjs.org/private
npm http 304 https://registry.npmjs.org/ast-types
npm http GET https://registry.npmjs.org/pinkie
npm http 304 https://registry.npmjs.org/cycle
npm http 304 https://registry.npmjs.org/eyes
npm http 304 https://registry.npmjs.org/pkginfo
npm http 304 https://registry.npmjs.org/colors
npm http 304 https://registry.npmjs.org/stack-trace
npm http 200 https://registry.npmjs.org/pinkie
npm http GET https://registry.npmjs.org/strip-ansi
npm http GET https://registry.npmjs.org/supports-color
npm http GET https://registry.npmjs.org/ansi-styles
npm http GET https://registry.npmjs.org/escape-string-regexp
npm http GET https://registry.npmjs.org/has-ansi
npm http GET https://registry.npmjs.org/pinkie/-/pinkie-2.0.4.tgz
npm http GET https://registry.npmjs.org/extsprintf
npm http GET https://registry.npmjs.org/json-schema
npm http GET https://registry.npmjs.org/verror
npm http 200 https://registry.npmjs.org/ansi-styles
npm http 200 https://registry.npmjs.org/escape-string-regexp
npm http 200 https://registry.npmjs.org/has-ansi
npm http 200 https://registry.npmjs.org/extsprintf
npm http 200 https://registry.npmjs.org/json-schema
npm http 200 https://registry.npmjs.org/supports-color
npm http 200 https://registry.npmjs.org/strip-ansi
npm http 200 https://registry.npmjs.org/verror
npm http 200 https://registry.npmjs.org/pinkie/-/pinkie-2.0.4.tgz
npm http GET https://registry.npmjs.org/escape-string-regexp/-/escape-string-regexp-1.0.4.tgz
npm http GET https://registry.npmjs.org/ansi-styles/-/ansi-styles-2.1.0.tgz
npm http GET https://registry.npmjs.org/extsprintf/-/extsprintf-1.0.2.tgz
npm http GET https://registry.npmjs.org/json-schema/-/json-schema-0.2.2.tgz
npm http GET https://registry.npmjs.org/has-ansi/-/has-ansi-2.0.0.tgz
npm http GET https://registry.npmjs.org/supports-color/-/supports-color-2.0.0.tgz
npm http GET https://registry.npmjs.org/strip-ansi/-/strip-ansi-3.0.0.tgz
npm http GET https://registry.npmjs.org/verror/-/verror-1.3.6.tgz
npm http GET https://registry.npmjs.org/graceful-readlink
npm http 200 https://registry.npmjs.org/escape-string-regexp/-/escape-string-regexp-1.0.4.tgz
npm http 200 https://registry.npmjs.org/ansi-styles/-/ansi-styles-2.1.0.tgz
npm http 200 https://registry.npmjs.org/extsprintf/-/extsprintf-1.0.2.tgz
npm http 200 https://registry.npmjs.org/json-schema/-/json-schema-0.2.2.tgz
npm http 200 https://registry.npmjs.org/supports-color/-/supports-color-2.0.0.tgz
npm http 200 https://registry.npmjs.org/has-ansi/-/has-ansi-2.0.0.tgz
npm http 200 https://registry.npmjs.org/strip-ansi/-/strip-ansi-3.0.0.tgz
npm http 200 https://registry.npmjs.org/verror/-/verror-1.3.6.tgz
npm http 200 https://registry.npmjs.org/graceful-readlink
npm http GET https://registry.npmjs.org/graceful-readlink/-/graceful-readlink-1.0.1.tgz
npm http 200 https://registry.npmjs.org/graceful-readlink/-/graceful-readlink-1.0.1.tgz
npm http GET https://registry.npmjs.org/ansi-regex
npm http 200 https://registry.npmjs.org/ansi-regex
npm http GET https://registry.npmjs.org/ansi-regex/-/ansi-regex-2.0.0.tgz
npm http 200 https://registry.npmjs.org/ansi-regex/-/ansi-regex-2.0.0.tgz
npm http GET https://registry.npmjs.org/tweetnacl
npm http GET https://registry.npmjs.org/jodid25519
npm http GET https://registry.npmjs.org/ecc-jsbn
npm http GET https://registry.npmjs.org/dashdash
npm http GET https://registry.npmjs.org/jsbn
npm http GET https://registry.npmjs.org/asn1
npm http GET https://registry.npmjs.org/jsonpointer
npm http GET https://registry.npmjs.org/generate-function
npm http GET https://registry.npmjs.org/generate-object-property
npm http 200 https://registry.npmjs.org/jodid25519
npm http 200 https://registry.npmjs.org/jsbn
npm http 200 https://registry.npmjs.org/ecc-jsbn
npm http GET https://registry.npmjs.org/hoek
npm http GET https://registry.npmjs.org/boom
npm http GET https://registry.npmjs.org/cryptiles
npm http GET https://registry.npmjs.org/sntp
npm http GET https://registry.npmjs.org/jodid25519/-/jodid25519-1.0.2.tgz
npm http 200 https://registry.npmjs.org/jsonpointer
npm http GET https://registry.npmjs.org/jsbn/-/jsbn-0.1.0.tgz
npm http 200 https://registry.npmjs.org/generate-function
npm http 200 https://registry.npmjs.org/tweetnacl
npm http 200 https://registry.npmjs.org/asn1
npm http GET https://registry.npmjs.org/ecc-jsbn/-/ecc-jsbn-0.1.1.tgz
npm http GET https://registry.npmjs.org/jsonpointer/-/jsonpointer-2.0.0.tgz
npm http 200 https://registry.npmjs.org/generate-object-property
npm http 200 https://registry.npmjs.org/dashdash
npm http GET https://registry.npmjs.org/generate-function/-/generate-function-2.0.0.tgz
npm http 200 https://registry.npmjs.org/cryptiles
npm http GET https://registry.npmjs.org/tweetnacl/-/tweetnacl-0.13.3.tgz
npm http GET https://registry.npmjs.org/asn1/-/asn1-0.2.3.tgz
npm http 200 https://registry.npmjs.org/boom
npm http GET https://registry.npmjs.org/generate-object-property/-/generate-object-property-1.2.0.tgz
npm http GET https://registry.npmjs.org/dashdash/-/dashdash-1.12.2.tgz
npm http GET https://registry.npmjs.org/cryptiles/-/cryptiles-2.0.5.tgz
npm http 200 https://registry.npmjs.org/sntp
npm http GET https://registry.npmjs.org/amdefine
npm http GET https://registry.npmjs.org/boom/-/boom-2.10.1.tgz
npm http 200 https://registry.npmjs.org/hoek
npm http GET https://registry.npmjs.org/sntp/-/sntp-1.0.9.tgz
npm http GET https://registry.npmjs.org/hoek/-/hoek-2.16.3.tgz
npm http 200 https://registry.npmjs.org/jsbn/-/jsbn-0.1.0.tgz
npm http 200 https://registry.npmjs.org/ecc-jsbn/-/ecc-jsbn-0.1.1.tgz
npm http 200 https://registry.npmjs.org/jodid25519/-/jodid25519-1.0.2.tgz
npm http 200 https://registry.npmjs.org/jsonpointer/-/jsonpointer-2.0.0.tgz
npm http 200 https://registry.npmjs.org/generate-function/-/generate-function-2.0.0.tgz
npm http 200 https://registry.npmjs.org/tweetnacl/-/tweetnacl-0.13.3.tgz
npm http 200 https://registry.npmjs.org/asn1/-/asn1-0.2.3.tgz
npm http 200 https://registry.npmjs.org/generate-object-property/-/generate-object-property-1.2.0.tgz
npm http 200 https://registry.npmjs.org/cryptiles/-/cryptiles-2.0.5.tgz
npm http 200 https://registry.npmjs.org/boom/-/boom-2.10.1.tgz
npm http 200 https://registry.npmjs.org/sntp/-/sntp-1.0.9.tgz
npm http 200 https://registry.npmjs.org/dashdash/-/dashdash-1.12.2.tgz
npm http 304 https://registry.npmjs.org/amdefine
npm http 200 https://registry.npmjs.org/hoek/-/hoek-2.16.3.tgz
npm http GET https://registry.npmjs.org/is-property
npm http 200 https://registry.npmjs.org/is-property
npm http GET https://registry.npmjs.org/is-property/-/is-property-1.0.2.tgz
npm http 200 https://registry.npmjs.org/is-property/-/is-property-1.0.2.tgz
npm http GET https://registry.npmjs.org/catharsis
npm http GET https://registry.npmjs.org/espree
npm http GET https://registry.npmjs.org/js2xmlparser
npm http GET https://registry.npmjs.org/marked
npm http GET https://registry.npmjs.org/requizzle
npm http GET https://registry.npmjs.org/bluebird
npm http GET https://registry.npmjs.org/wrench
npm http GET https://registry.npmjs.org/strip-json-comments
npm http GET https://registry.npmjs.org/underscore
npm http GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http GET https://registry.npmjs.org/async/-/async-1.4.2.tgz
npm http 200 https://registry.npmjs.org/requizzle
npm http GET https://registry.npmjs.org/requizzle/-/requizzle-0.2.1.tgz
npm http 200 https://registry.npmjs.org/async/-/async-1.4.2.tgz
npm http 304 https://registry.npmjs.org/bluebird
npm http 200 https://registry.npmjs.org/js2xmlparser
npm http 200 https://registry.npmjs.org/catharsis
npm http GET https://registry.npmjs.org/bluebird/-/bluebird-2.9.34.tgz
npm http GET https://registry.npmjs.org/js2xmlparser/-/js2xmlparser-1.0.0.tgz
npm http GET https://registry.npmjs.org/catharsis/-/catharsis-0.8.7.tgz
npm http 200 https://registry.npmjs.org/espree
npm http GET https://registry.npmjs.org/espree/-/espree-2.2.5.tgz
npm http 200 https://registry.npmjs.org/underscore
npm http 200 https://registry.npmjs.org/strip-json-comments
npm http 200 https://registry.npmjs.org/wrench
npm http GET https://registry.npmjs.org/strip-json-comments/-/strip-json-comments-1.0.4.tgz
npm http GET https://registry.npmjs.org/underscore/-/underscore-1.8.3.tgz
npm http 200 https://registry.npmjs.org/marked
npm http GET https://registry.npmjs.org/wrench/-/wrench-1.5.8.tgz
npm http GET https://registry.npmjs.org/marked/-/marked-0.3.5.tgz
npm http 200 https://registry.npmjs.org/requizzle/-/requizzle-0.2.1.tgz
npm http 200 https://registry.npmjs.org/strip-json-comments/-/strip-json-comments-1.0.4.tgz
npm http 200 https://registry.npmjs.org/bluebird/-/bluebird-2.9.34.tgz
npm http 200 https://registry.npmjs.org/js2xmlparser/-/js2xmlparser-1.0.0.tgz
npm http 200 https://registry.npmjs.org/espree/-/espree-2.2.5.tgz
npm http 200 https://registry.npmjs.org/catharsis/-/catharsis-0.8.7.tgz
npm http 200 https://registry.npmjs.org/underscore/-/underscore-1.8.3.tgz
npm http 200 https://registry.npmjs.org/marked/-/marked-0.3.5.tgz
npm http 200 https://registry.npmjs.org/wrench/-/wrench-1.5.8.tgz
npm http 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http GET https://registry.npmjs.org/underscore/-/underscore-1.6.0.tgz
npm http 200 https://registry.npmjs.org/underscore/-/underscore-1.6.0.tgz
npm http GET https://registry.npmjs.org/underscore-contrib
npm http 200 https://registry.npmjs.org/underscore-contrib
npm http GET https://registry.npmjs.org/underscore-contrib/-/underscore-contrib-0.3.0.tgz
npm http 200 https://registry.npmjs.org/underscore-contrib/-/underscore-contrib-0.3.0.tgz
npm http GET https://registry.npmjs.org/node-ssdp
npm http 304 https://registry.npmjs.org/node-ssdp
while [jx install] is a special command, the current folder has install.js, running that instead.


module.js:802
    throw err;
          ^
Error: Cannot find module 'unzip'
    at Function.Module._oldRes (module.js:800:15)
    at Function.Module._resolveFilename (module.js:1653:19)
    at Function.Module._load (module.js:360:25)
    at Module.require (module.js:475:17)
    at require (module.js:493:17)
    at Object.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/thali/install/install.js:6:13)
    at Module._compile (module.js:619:26)
    at Object.Module._extensions..js (module.js:649:10)
    at Module.load (module.js:440:36)
    at Function.Module._load (module.js:405:12)
