#### Test (Fail) 80931293 Build Logs


```


```

```
Already up-to-date.


```

```
Your branch is up-to-date with 'origin/master'.
Branch vNext_yarong_780 set up to track remote branch vNext_yarong_780 from origin.
Merge made by the 'recursive' strategy.
 build.sh                                           |  8 +-----
 test/README.md                                     |  4 +--
 test/www/jxcore/bv_tests/testCreatePeerListener.js |  2 +-
 test/www/jxcore/bv_tests/testLocalSeqManager.js    |  4 ++-
 test/www/jxcore/bv_tests/testThaliMobileNative.js  |  2 +-
 test/www/jxcore/bv_tests/testThaliNotification.js  |  2 +-
 .../testThaliPullReplicationFromNotification.js    | 14 ++++-------
 ...liPullReplicationFromNotificationCoordinated.js |  2 +-
 .../bv_tests/testThaliReplicationPeerAction.js     |  6 +++--
 .../testThaliReplicationPeerActionCoordinated.js   |  2 +-
 .../jxcore/bv_tests/testthaliPeerPoolDefault.js    |  4 ++-
 test/www/jxcore/lib/httpTester.js                  |  2 ++
 test/www/jxcore/lib/testUtils.js                   |  4 ++-
 test/www/jxcore/lib/wifiBasedNativeMock.js         | 20 +++++++--------
 test/www/jxcore/runTests.js                        |  2 +-
 thali/NextGeneration/mux/createNativeListener.js   |  2 +-
 thali/NextGeneration/mux/createPeerListener.js     |  2 +-
 .../notification/thaliNotificationClient.js        |  8 +++++-
 .../notification/thaliNotificationServer.js        |  2 +-
 .../NextGeneration/replication/localSeqManager.js  | 16 ++++++++----
 .../thaliPullReplicationFromNotification.js        | 16 ++++++------
 .../replication/thaliReplicationPeerAction.js      | 15 ++++++-----
 .../thaliSendNotificationBasedOnReplication.js     |  2 +-
 thali/NextGeneration/thaliConfig.js                | 29 ++++++++++++++++++++++
 thali/NextGeneration/thaliMobile.js                |  2 +-
 thali/NextGeneration/thaliMobileNativeWrapper.js   |  6 +++--
 thali/NextGeneration/thaliWifiInfrastructure.js    | 19 ++++++++++----
 thali/identityExchange/LargerHashStateMachine.js   |  4 +--
 thali/identityExchange/SmallerHashStateMachine.js  |  2 +-
 thali/identityExchange/identityexchange.js         |  2 +-
 thali/install/setUpTests.sh                        |  7 ++----
 thali/thaliLogger.js                               |  2 +-
 32 files changed, 133 insertions(+), 81 deletions(-)
 mode change 100644 => 100755 test/www/jxcore/bv_tests/testLocalSeqManager.js
 mode change 100644 => 100755 test/www/jxcore/bv_tests/testThaliNotification.js
 mode change 100644 => 100755 test/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
 mode change 100644 => 100755 test/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
 mode change 100644 => 100755 test/www/jxcore/lib/httpTester.js
 mode change 100644 => 100755 test/www/jxcore/lib/testUtils.js
 mode change 100644 => 100755 thali/NextGeneration/replication/thaliReplicationPeerAction.js
 mode change 100644 => 100755 thali/NextGeneration/thaliMobileNativeWrapper.js
 mode change 100644 => 100755 thali/NextGeneration/thaliWifiInfrastructure.js

Already on 'master'
Switched to a new branch 'vNext_yarong_780'
Note: checking out 'f0af700'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at f0af700... Added emulation of 'setup' and 'teardown' failures
Auto packing the repository in background for optimum performance.
See "git help gc" for manual housekeeping.

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
│ │ │ │ │ ├─┬ minimatch@3.0.3 
│ │ │ │ │ │ └─┬ brace-expansion@1.1.6 
│ │ │ │ │ │   ├── balanced-match@0.4.2 
│ │ │ │ │ │   └── concat-map@0.0.1 
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
│ │ │ ├── isarray@0.0.1 
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
│ ├── tough-cookie@2.3.1 
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


> thali@2.1.0 postinstall /Users/thali/Github/Thali_CordovaPlugin/thali
> jx installCordovaPlugin.js

We believe we are in a clone of the GitHub Repo so we will not install Cordova dependencies

> thali@2.1.0 prepublish /Users/thali/Github/Thali_CordovaPlugin/thali
> jx install/prePublishThaliCordovaPlugin.js

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
├─┬ express-pouchdb@1.0.5-thali 
│ ├── basic-auth@1.0.4 
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
│ │ ├── argsarray@0.0.1 
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
│ │ │   │   └─┬ is-finite@1.0.1 
│ │ │   │     └── number-is-nan@1.0.0 
│ │ │   └── object-assign@1.0.0 
│ │ ├─┬ couchdb-calculate-session-id@1.1.0 
│ │ │ └── aproba@1.0.4 
│ │ ├── crypto-lite@0.1.0 
│ │ ├─┬ pouchdb@5.4.5 
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
│ │ ├─┬ pouchdb-req-http-query@1.0.3 
│ │ │ ├─┬ pouchdb-promise@0.0.0 
│ │ │ │ ├── bluebird@1.2.4 
│ │ │ │ └── lie@2.7.7 
│ │ │ └─┬ xmlhttprequest-cookie@0.9.4 
│ │ │   └── xmlhttprequest@1.8.0 
│ │ ├── pouchdb-system-db@1.0.4 
│ │ ├── promise-nodify@1.0.2 
│ │ └── secure-random@1.1.1 
│ ├─┬ pouchdb-find@0.10.2 
│ │ ├── is-array@1.0.1 
│ │ ├─┬ lie@2.9.1 
│ │ │ └── unreachable-branch-transform@0.2.3 
│ │ ├── pouchdb-collate@1.2.0 
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
│ └── pouchdb-wrappers@1.3.6 
├── forever-agent@0.6.1 
├─┬ fs-extra-promise@0.4.0
│ └─┬ fs-extra@0.30.0
│   └─┬ rimraf@2.5.4
│     └─┬ glob@7.0.5
│       └── inherits@2.0.1 
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
│ │     └─┬ glob@5.0.15 
│ │       └── inherits@2.0.1 
│ ├─┬ inline-process-browser@1.0.0
│ │ └─┬ through2@0.6.5
│ │   └─┬ readable-stream@1.0.34
│ │     └── inherits@2.0.1 
│ └── unreachable-branch-transform@0.3.0 
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
├─┬ pouchdb-node@5.5.0-prerelease 
│ ├─┬ pouchdb-adapter-http@5.5.0-prerelease 
│ │ ├── es6-promise-pool@2.4.2 
│ │ ├─┬ pouchdb-ajax@5.5.0-prerelease 
│ │ │ ├── pouchdb-promise@5.5.0-prerelease 
│ │ │ └─┬ request@2.72.0 
│ │ │   ├── extend@3.0.0 
│ │ │   └── qs@6.1.0 
│ │ ├── pouchdb-binary-utils@5.5.0-prerelease 
│ │ ├── pouchdb-errors@5.5.0-prerelease 
│ │ ├─┬ pouchdb-md5@5.5.0-prerelease 
│ │ │ ├── pouchdb-collections@5.5.0-prerelease 
│ │ │ └── pouchdb-promise@5.5.0-prerelease 
│ │ ├── pouchdb-promise@5.5.0-prerelease 
│ │ └─┬ pouchdb-utils@5.5.0-prerelease 
│ │   ├── pouchdb-collections@5.5.0-prerelease 
│ │   └── pouchdb-promise@5.5.0-prerelease 
│ ├─┬ pouchdb-adapter-leveldb@5.5.0-prerelease 
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
│ │ │   │ │     └─┬ duplexer2@0.0.2 
│ │ │   │ │       └── readable-stream@1.1.14 
│ │ │   │ ├── simple-mime@0.1.0 
│ │ │   │ └── url-template@2.0.8 
│ │ │   ├── github-from-package@0.0.0 
│ │ │   ├─┬ node-gyp@3.4.0 
│ │ │   │ ├── fstream@1.0.10 
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
│ │ │   │ │ ├── delegates@1.0.0 
│ │ │   │ │ └─┬ readable-stream@2.1.4 
│ │ │   │ │   └── isarray@1.0.0 
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
│ │ │   │ ├── ini@1.3.4 
│ │ │   │ └── strip-json-comments@1.0.4 
│ │ │   ├─┬ simple-get@1.4.3 
│ │ │   │ └── unzip-response@1.0.0 
│ │ │   ├── tar-fs@1.13.0 
│ │ │   └─┬ tar-stream@1.5.2 
│ │ │     └─┬ readable-stream@2.1.4 
│ │ │       └── isarray@1.0.0 
│ │ └─┬ pouchdb-adapter-leveldb-core@5.5.0-prerelease 
│ │   ├─┬ pouchdb-adapter-utils@5.5.0-prerelease 
│ │   │ └── pouchdb-collections@5.5.0-prerelease 
│ │   ├── pouchdb-collections@5.5.0-prerelease 
│ │   ├── pouchdb-json@5.5.0-prerelease 
│ │   ├── pouchdb-promise@5.5.0-prerelease 
│ │   ├─┬ sublevel-pouchdb@5.5.0-prerelease 
│ │   │ ├── ltgt@2.1.2 
│ │   │ └── readable-stream@1.0.33 
│ │   └─┬ through2@2.0.1 
│ │     └─┬ readable-stream@2.0.6 
│ │       └── isarray@1.0.0 
│ ├─┬ pouchdb-core@5.5.0-prerelease 
│ │ ├── double-ended-queue@2.0.0-0 
│ │ ├── pouchdb-collections@5.5.0-prerelease 
│ │ ├── pouchdb-merge@5.5.0-prerelease 
│ │ ├── pouchdb-promise@5.5.0-prerelease 
│ │ └── scope-eval@0.0.3 
│ ├─┬ pouchdb-mapreduce@5.5.0-prerelease 
│ │ ├── pouchdb-mapreduce-utils@5.5.0-prerelease 
│ │ ├── pouchdb-promise@5.5.0-prerelease 
│ │ └── spark-md5@2.0.2 
│ └─┬ pouchdb-replication@5.5.0-prerelease 
│   ├─┬ pouchdb-checkpointer@5.5.0-prerelease 
│   │ └── pouchdb-promise@5.5.0-prerelease 
│   ├─┬ pouchdb-generate-replication-id@5.5.0-prerelease 
│   │ └── pouchdb-promise@5.5.0-prerelease 
│   └── pouchdb-promise@5.5.0-prerelease 
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
│ ├── has-binary@0.1.6 
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
│ │ └─┬ minimatch@3.0.3
│ │   └─┬ brace-expansion@1.1.6
│ │     └── concat-map@0.0.1 
│ ├── object-inspect@1.0.2 
│ └── resumer@0.0.0 
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
│ ├─┬ jsdoc@3.3.3
│ │ ├── async@0.9.2 
│ │ ├── escape-string-regexp@1.0.5 
│ │ └── strip-json-comments@1.0.4 
│ ├─┬ lie@3.0.4 
│ │ ├─┬ es3ify@0.2.2
│ │ │ └─┬ jstransform@11.0.3
│ │ │   └─┬ commoner@0.10.4
│ │ │     └─┬ glob@5.0.15 
│ │ │       └─┬ minimatch@3.0.3
│ │ │         └─┬ brace-expansion@1.1.6
│ │ │           └── concat-map@0.0.1 
│ │ └── unreachable-branch-transform@0.3.0 
│ ├── long@3.0.3 
│ ├─┬ multiplex@6.7.0 
│ │ ├─┬ duplexify@3.4.5 
│ │ │ ├── end-of-stream@1.0.0 
│ │ │ ├─┬ readable-stream@2.1.4 
│ │ │ │ └── isarray@1.0.0 
│ │ │ └── stream-shift@1.0.0 
│ │ ├── inherits@2.0.1 
│ │ ├─┬ readable-stream@2.1.4 
│ │ │ ├── buffer-shims@1.0.0 
│ │ │ ├── isarray@1.0.0 
│ │ │ ├── process-nextick-args@1.0.7 
│ │ │ └── util-deprecate@1.0.2 
│ │ └── varint@4.0.1 
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
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testUnitTestFramework.js
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
DEBUG createNativeListener: listening 49842
ok 1 Should throw
# teardown
# setup
# emits incomingConnectionState
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49844
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
DEBUG createNativeListener: listening 49847
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
DEBUG createNativeListener: listening 49851
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
DEBUG createNativeListener: listening 49856
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
DEBUG createNativeListener: listening 49860
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
DEBUG createNativeListener: listening 49864
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
DEBUG createNativeListener: listening 49868
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
DEBUG createNativeListener: listening 49872
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
DEBUG createNativeListener: listening 49924
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
DEBUG createNativeListener: listening 49928
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
DEBUG createNativeListener: listening 49933
# teardown
# setup
# calling createPeerListener after calling stop produces error
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49936
# teardown
# setup
# can call createPeerListener (pleaseConnect === false)
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49939
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
ok 45 port must be in range
# teardown
# setup
# calling createPeerListener (pleaseConnect === true) with unknown peer is error
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49943
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
DEBUG createNativeListener: listening 49948
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
ok 47 port values should be the same
# teardown
# setup
# createPeerListener - closing connection to native listener closes everything and triggers new listener
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49952
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
DEBUG createNativeListener: listening 49961
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
DEBUG createPeerListener: Recreating listener
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
ok 52 same peer ID
ok 53 different ports
# teardown
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: incoming socket close
# setup
# peerListener - forwardConnection, pleaseConnect === true - no native server
DEBUG createNativeListener: creating native server
ok 54 Can call startUpdateAdvertisingAndListening without error
ok 55 Can call startListeningForAdvertisements without error
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createNativeListener: listening 49970
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
DEBUG createNativeListener: listening 49976
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
DEBUG createNativeListener: listening 49983
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
DEBUG createNativeListener: listening 49988
DEBUG createPeerListener: pleaseConnect= false
ok 68 peerPort != nativePort
DEBUG createPeerListener: first connection
DEBUG createPeerListener: forward connection
ok 69 Should not get unexpected connection
# teardown
# setup
# peerListener - forwardConnection, pleaseConnect === false - with native server and data transfer
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49994
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
DEBUG createNativeListener: listening 50001
DEBUG createPeerListener: pleaseConnect= false
ok 74 Second call to existing peerListener returns existing port
# teardown
# setup
# createPeerListener - pleaseConnect === true, failed connection rejects promise
DEBUG createNativeListener: creating native server
ok 75 Can call startUpdateAdvertisingAndListening without error
ok 76 Can call startListeningForAdvertisements without error
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createNativeListener: listening 50005
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
DEBUG createNativeListener: listening 50010
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
DEBUG createNativeListener: listening 50015
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
DEBUG createNativeListener: listening 50020
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
DEBUG createNativeListener: listening 50026
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: first connection
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createPeerListener: looking up mux for client port:  50029
DEBUG createPeerListener: reverse connection
DEBUG createPeerListener: looking up mux for client port:  50029
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
DEBUG createNativeListener: listening 50032
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: first connection
DEBUG createPeerListener: looking up mux for client port:  50035
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createPeerListener: reverse connection
DEBUG createPeerListener: looking up mux for client port:  50035
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
DEBUG createNativeListener: listening 50039
# teardown
# setup
# createPeerListener - ask for a new peer when we are not at maximum peers and make sure we do not remove any existing listeners
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50042
# teardown
# setup
# createPeerListener - pleaseConnect = false - test timeout
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50045
# teardown
# setup
# createPeerListener - pleaseConnect = true - test timeout
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50048
# teardown
# setup
# createPeerListener - forward connection - wrong serverPort
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50051
# teardown
# setup
# createPeerListener - forward connection - wrong clientPort
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50054
# teardown
# setup
# createPeerListener - please connect = false, multiple connections out
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50057
# teardown
# setup
# createPeerListener - please connect = false, multiple bi-directional connections
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50060
# teardown
# setup
# createPeerListener - multiple parallel calls
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50063
# teardown
# setup
# #_doImmediateSeqUpdate - server is not there
DEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}
ok 97 Got right error
# teardown
# setup
# #_doImmediateSeqUpdate - server accepts & closes connection
DEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNRESET","status":500}
ok 98 Got socket hang up
# teardown
# setup
# #_doImmediateSeqUpdate - server always returns 500
DEBUG localSeqManager: Got an error trying to update seq []
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
DEBUG localSeqManager: Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}
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
# enqueue and run in order
ok 134 firstPromise setTimeout
ok 135 firstPromise result
ok 136 firstPromise testValue
ok 137 secondPromise setTimeout
ok 138 secondPromise result
ok 139 secondPromise testValue
ok 140 thirdPromise in promise
ok 141 thirdPromise result
ok 142 thirdPromise testValue
# teardown
# setup
# enqueueAtTop and run backwards
ok 143 thirdPromise - first to run
ok 144 thirdPromise - in resolve
ok 145 secondPromise - second to run
ok 146 secondPromise - in catch
ok 147 firstPromise - third to run
ok 148 firstPromise - in then
ok 149 testing promises
# teardown
# setup
# mix enqueue and enqueueAtTop
ok 150 fourth
ok 151 fourth
ok 152 second
ok 153 secondPromise - in then
ok 154 first
ok 155 firstPromise - in catch
ok 156 third
ok 157 thirdPromise - in then
ok 158 testingPromises
# teardown
# setup
# queues handled independently
ok 159 all short operations completed before the long resolves
# teardown
# setup
# basic
ok 160 sane
# teardown
# setup
# another
ok 161 sane
# teardown
# setup
# #startListeningForAdvertisements should fail if start not called
ok 162 specific error should be returned
# teardown
ok 163 error should be null
ok 164 error should be null
# setup
# #startUpdateAdvertisingAndListening should fail if start not called
ok 165 specific error should be returned
# teardown
ok 166 error should be null
ok 167 error should be null
# setup
# should be able to call #stopListeningForAdvertisements many times
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50140
ok 168 error should be null
ok 169 error should be null
ok 170 error should be null
ok 171 error should be null
# teardown
ok 172 error should be null
ok 173 error should be null
# setup
# should be able to call #startListeningForAdvertisements many times
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50142
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 174 error should be null
ok 175 error should be null
ok 176 error should be null
ok 177 error should be null
# teardown
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 178 error should be null
ok 179 error should be null
# setup
# should be able to call #startUpdateAdvertisingAndListening many times
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50144
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 180 error should be null
ok 181 error should be null
ok 182 error should be null
ok 183 error should be null
# teardown
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 184 error should be null
ok 185 error should be null
# setup
# should be able to call #stopAdvertisingAndListening many times
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50149
ok 186 error should be null
ok 187 error should be null
ok 188 error should be null
ok 189 error should be null
# teardown
ok 190 error should be null
ok 191 error should be null
# setup
# #start should fail if called twice in a row
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50151
ok 192 first call should succeed
ok 193 first call should succeed
ok 194 specific error should be returned
# teardown
ok 195 error should be null
ok 196 error should be null
# setup
# does not emit duplicate discoveryAdvertisingStateUpdate
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50153
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 197 called only once
ok 198 discovery state matches
ok 199 advertising state matches
# teardown
INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 200 error should be null
ok 201 error should be null
# setup
# does not send duplicate availability changes
ok 202 should be called once
ok 203 should not have been called more than once
# teardown
ok 204 error should be null
ok 205 error should be null
# setup
# can get the network status
ok 206 network status should have certain non-empty properties
# teardown
ok 207 error should be null
ok 208 error should be null
# setup
# wifi peer is marked unavailable if announcements stop
ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
ok 209 host address should match
ok 210 port should match
ok 211 host address should be null
ok 212 port should should be null
# teardown
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 213 error should be null
ok 214 error should be null
# setup
# network changes emitted correctly
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50158
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 215 wifi is off
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 216 wifi is on
# teardown
ok 217 error should be null
ok 218 error should be null
# setup
# network changes not emitted in stopped state
ok 219 event was not emitted
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
# teardown
ok 220 error should be null
ok 221 error should be null
# setup
# calls correct starts when network changes
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50160
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 222 specific error expected
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 223 specific error expected
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":true,"advertisingActive":true}
ok 224 startListeningForAdvertisements should have been called
ok 225 startUpdateAdvertisingAndListening should have been called
# teardown
INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 226 error should be null
ok 227 error should be null
# setup
# peer is marked unavailable if port number changes
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50165
ok 228 peer should have a non-empty identifier
ok 229 peer should have a non-empty host address
ok 230 peer should have port number
ok 231 peer should have suggested timeout
ok 232 peer should have a connection type
ok 233 connection type should match one of the pre-defined types
ok 234 peer should have a non-empty identifier
ok 235 host address should be null
ok 236 port number should be null
ok 237 peer should have suggested timeout
ok 238 peer should have a connection type
ok 239 connection type should match one of the pre-defined types
ok 240 port number must match
ok 241 peer should have a non-empty identifier
ok 242 peer should have a non-empty host address
ok 243 peer should have port number
ok 244 peer should have suggested timeout
ok 245 peer should have a connection type
ok 246 connection type should match one of the pre-defined types
# teardown
ok 247 error should be null
ok 248 error should be null
# setup
# when network connection is lost a peer should be marked unavailable
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50167
INFO testUtils: Toggling radios to: false
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 249 peer should have a non-empty identifier
ok 250 host address should be null
ok 251 port number should be null
ok 252 peer should have suggested timeout
ok 253 peer should have a connection type
ok 254 connection type should match one of the pre-defined types
INFO testUtils: Toggling radios to: true
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
# teardown
ok 255 error should be null
ok 256 error should be null
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
# setup
# Can call start/stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 257 Can call startListeningForAdvertisements without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 258 Can call stopListeningForAdvertisements without error
# teardown
ok 259 Should be able to call stopListeningForAdvertisements in teardown
ok 260 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Calling startListeningForAdvertisements twice is NOT an error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 261 Can call startListeningForAdvertisements without error
ok 262 Can call startListeningForAdvertisements twice without error
# teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 263 Should be able to call stopListeningForAdvertisements in teardown
ok 264 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Calling stopListeningForAdvertisements without calling start is NOT an error
ok 265 Can call stopListeningForAdvertisements without error
ok 266 Can call stopListeningForAdvertisements without error
# teardown
ok 267 Should be able to call stopListeningForAdvertisements in teardown
ok 268 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Can call start/stopUpdateAdvertisingAndListening
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 269 Can call startUpdateAdvertisingAndListening without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 270 Can call stopAdvertisingAndListening without error
# teardown
ok 271 Should be able to call stopListeningForAdvertisements in teardown
ok 272 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Calling startUpdateAdvertisingAndListening twice is NOT an error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 273 Can call startUpdateAdvertisingAndListening without error
ok 274 Can call startUpdateAdvertisingAndListening twice without error
# teardown
ok 275 Should be able to call stopListeningForAdvertisements in teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 276 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
ok 277 Can call startUpdateAdvertisingAndListening without error
ok 278 Can call stopAdvertisingAndListening without error
# teardown
ok 279 Should be able to call stopListeningForAdvertisements in teardown
ok 280 Should be able to call stopAdvertisingAndListening in teardown
# setup
# cannot call connect when start listening for advertisements is not active
ok 281 got right error
# teardown
ok 282 Should be able to call stopListeningForAdvertisements in teardown
ok 283 Should be able to call stopAdvertisingAndListening in teardown
# setup
# #startListeningForAdvertisements should fail if start not called
ok 284 specific error should be returned
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 285 must be stopped
# setup
# #startUpdateAdvertisingAndListening should fail if start not called
ok 286 specific error should be returned
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 287 must be stopped
# setup
# should be able to call #stopListeningForAdvertisements many times
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50173
ok 288 no errors
ok 289 still no errors
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 290 must be stopped
# setup
# should be able to call #startListeningForAdvertisements many times
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50175
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 291 no errors
ok 292 still no errors
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 293 must be stopped
# setup
# should be able to call #startUpdateAdvertisingAndListening many times
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50177
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 294 no errors
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
ok 295 still no errors
# teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 296 must be stopped
# setup
# should be able to call #stopAdvertisingAndListening many times
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50181
ok 297 no errors
ok 298 still no errors
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 299 must be stopped
# setup
# can get the network status before starting
ok 300 network status should have certain non-empty properties
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 301 must be stopped
# setup
# error returned with bad router
ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
ok 302 specific error expected
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 303 must be stopped
# setup
# all services are stopped when we call stop
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50183
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
ok 304 connection to servers manager should succeed after starting
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
ok 305 connection to router server should succeed after starting
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG createNativeListener: incoming socket close
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 306 is stopped after calling stop
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
ok 307 connection to servers manager should fail after stopping
ok 308 connection to router server should fail after stopping
# teardown
ok 309 must be stopped
# setup
# make sure terminateConnection is properly hooked up
ok 310 called with right arguments
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 311 must be stopped
# setup
# make sure terminateListener is properly hooked up
ok 312 called with right arguments
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 313 must be stopped
# setup
# make sure we actually call kill connections properly
ok 314 specific error expected
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 315 must be stopped
# setup
# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50191
INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":50190,"error":{}}
ok 316 failure reason is as expected
ok 317 error description is as expected
ok 318 must be stopped
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 319 must be stopped
# setup
# We repeat failedConnection event when we get it from thaliTcpServersManager
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50193
ok 320 peerIdentifier matches
ok 321 error description matches
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 322 must be stopped
# setup
# can do HTTP requests between peers without coordinator
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50195
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG testUtils: We got a peer {"peerIdentifier":"foo","portNumber":50198,"hostAddress":"127.0.0.1"}
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
ok 323 Should only get expected id
ok 324 response body should match testData
# teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
ok 325 must be stopped
DEBUG createNativeListener: incoming socket close
# setup
# make sure bad PSK connections fail
ok 326 FIX ME, PLEASE!!!
# teardown
ok 327 must be stopped
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# setup
# peer changes handled from a queue
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50206
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
ok 328 peers were handled in the right order
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 329 must be stopped
# setup
# relaying discoveryAdvertisingStateUpdateNonTCP
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50218
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 330 discovery is active
ok 331 advertising is active
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 332 must be stopped
# setup
# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50220
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: 50220
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 333 right error reason
ok 334 Stop should be fine
ok 335 same port
ok 336 we should be off
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 337 must be stopped
# setup
# we successfully receive and replay discoveryAdvertisingStateUpdate
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50224
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 338 discoveryActive matches
ok 339 advertisingActive matches
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 340 discoveryActive matches
ok 341 advertisingActive matches
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50226
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 342 discoveryActive matches
ok 343 advertisingActive matches
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 344 discoveryActive matches
ok 345 advertisingActive matches
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50230
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 346 must be stopped
# setup
# Test BEACONS_RETRIEVED_AND_PARSED locally
ok 347 peerIdentifier should be identifier
ok 348 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 349 good beacon
ok 350 good preAmble
ok 351 public keys match!
ok 352 must return null after successful call
ok 353 Once start returns the action should be in KILLED state
# teardown
# setup
# Test HTTP_BAD_RESPONSE locally
ok 354 Response should be HTTP_BAD_RESPONSE
ok 355 must return null after successful call
# teardown
# setup
# Test NETWORK_PROBLEM locally
ok 356 Response should be NETWORK_PROBLEM
ok 357 reject reason should be: Could not establish TCP connection
# teardown
# setup
# Call the start two times
ok 358 Call start once
ok 359 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 360 must return null after successful call.
# teardown
# setup
# Call the kill before calling the start
ok 361 Should be Killed
ok 362 Start after killed
# teardown
# setup
# Call the kill immediately after the start
ok 363 Should be KILLED
ok 364 must return null after successful kill
# teardown
# setup
# Call the kill while waiting a response from the server
ok 365 Should be KILLED
ok 366 must return null after successful kill
# teardown
# setup
# Test to exceed the max content size locally
ok 367 HTTP_BAD_RESPONSE should be response when content size is exceeded
ok 368 must return null after successful call
# teardown
# setup
# Close the server socket while the client is waiting a response from the server. Local test.
ok 369 Should be NETWORK_PROBLEM caused closing server socket
ok 370 Should be Could not establish TCP connection
# teardown
# setup
# Close the client socket while the client is waiting a response from the server. Local test.
ok 371 Should be NETWORK_PROBLEM caused closing client socket
ok 372 Should be Could not establish TCP connection
# teardown
# setup
# #generatePreambleAndBeacons bad args
ok 373 publicKeysToNotify cannot be null
ok 374 ecdh for local device cannot be null
ok 375 milliseconds cannot be less than 0
ok 376 milliseconds cannot be 0
ok 377 milliseconds cannot be greater than one_day
# teardown
# setup
# #generatePreambleAndBeacons empty keys to notify
ok 378 should be equal
# teardown
# setup
# #generatePreambleAndBeacons multiple keys to notify
ok 379 should be equal
ok 380 should be equal
ok 381 (unnamed assert)
ok 382 should be equal
# teardown
# setup
# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
ok 383 should throw
# teardown
# setup
# #parseBeacons invalid expiration in beaconStreamWithPreAmble
ok 384 Preamble expiration must be a 64 bit integer
# teardown
# setup
# #parseBeacons expiration out of range lower
ok 385 Expiration out of range
# teardown
# setup
# #parseBeacons expiration out of range lower
ok 386 Expiration out of range
# teardown
# setup
# #parseBeacons no beacons returns null
ok 387 should be equal
# teardown
# setup
# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
ok 388 Malformed encrypted beacon key ID
# teardown
# setup
# #parseBeacons addressBookCallback fails decrypt
ok 389 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns no matches
ok 390 should be equal
ok 391 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns spurious match
ok 392 should be equal
ok 393 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns public key
ok 394 right number of calls to address book
ok 395 good preAmble
ok 396 good unencryptedKeyId
ok 397 good beacon
# teardown
# setup
# validate generatePskIdentityField
ok 398 decoded buffers match
# teardown
# setup
# validate generatePskSecret
ok 399 secrets match
# teardown
# setup
# validate generatePskSecrets
ok 400 Matching numbers
ok 401 We have an entry!
ok 402 keys match
ok 403 secrets match
ok 404 We have an entry!
ok 405 keys match
ok 406 secrets match
ok 407 We have an entry!
ok 408 keys match
ok 409 secrets match
# teardown
# setup
# validate generateBeaconStreamAndSecrets
ok 410 Streams have same length
ok 411 matching size
ok 412 keys match
ok 413 secrets match
# teardown
# setup
# Add two Peers.
ok 414 should be equal
ok 415 should be equal
ok 416 should be equal
ok 417 should be equal
ok 418 should be equal
# teardown
# setup
# TCP_NATIVE peer loses DNS
ok 419 should be equal
ok 420 should be equal
# teardown
# setup
# Received beacons with no values for us
ok 421 entry exists
ok 422 entry is resolved
# teardown
# setup
# Resolves an action locally
ok 423 Host address must match
ok 424 suggestedTCPTimeout must match
ok 425 connectionType must match
ok 426 portNumber must match
# teardown
# setup
# Resolves an action locally using ThaliPeerPoolDefault
ok 427 Host address must match
ok 428 suggestedTCPTimeout must match
ok 429 connectionType must match
ok 430 portNumber must match
# teardown
# setup
# Action fails because of a bad hostname.
ok 431 should be equal
ok 432 should be equal
ok 433 should be equal
# teardown
# setup
# hostaddress is removed when the action is running. 
ok 434 should be equal
# teardown
# setup
# Client to server request locally
ok 435 secrets are equal
ok 436 Public key matches with the server key
ok 437 Host address must match
ok 438 suggestedTCPTimeout must match
ok 439 connectionType must match
ok 440 portNumber must match
# teardown
# setup
# Test ThaliPskMapCache clean and expiration
ok 441 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
ok 442 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
ok 443 All entries should be expired after 1 second
# teardown
# setup
# Test ThaliPskMapCache getSecret and getPublic
ok 444 All keys need to be available in the cache
ok 445 All entries should be expired after 1 second
# teardown
# setup
# Test ThaliPskMapCache multiple entries
ok 446 Size of the cache should be 2
ok 447 Cache doesn't contain dictionary1
ok 448 Size of the cache should be 1
ok 449 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
# setup
# Start and stop ThaliNotificationServer
ok 450 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
ok 451 ThaliMobile.StopAdvertisingAndListeningshould be called once
# teardown
# setup
# Pass an empty array to ThaliNotificationServer.start
ok 452 StartUpdateAdvertisingAndListening should not be called
ok 453 ThaliMobile.StopAdvertisingAndListening should be called once
ok 454 no error
ok 455 should be 204
# teardown
# setup
# Pass a string to ThaliNotificationServer.start
ok 456 StartUpdateAdvertisingAndListening should not be called
# teardown
# setup
# Pass an empty parameter to ThaliNotificationServer.start
ok 457 StartUpdateAdvertisingAndListening should not be called
# teardown
# setup
# Make an HTTP request to /NotificationBeacons
ok 458 no error
ok 459 should be 200
ok 460 should be equal
ok 461 should be equal
ok 462 (unnamed assert)
ok 463 no error
ok 464 should be 204
# teardown
# setup
# Make an HTTP request to /NotificationBeacons (no keys)
ok 465 error should be null
ok 466 should be 204
# teardown
# setup
# Make an HTTP request to /NotificationBeaconsbefore calling start
ok 467 should be 404
# teardown
# setup
# #testThaliPeerAction - test getters
ok 468 getPeerIdentifier
ok 469 getConnectionType
ok 470 getActionType
ok 471 getActionState
ok 472 getPskIdentity
ok 473 getPskKey
# teardown
# setup
# #testThaliPeerAction - start and kill
ok 474 initial state
ok 475 after start
ok 476 after kill
# teardown
# setup
# #testThaliPeerAction - double start
ok 477 should be equal
# teardown
# setup
# #testThaliPeerAction - start after kill
ok 478 clean kill
ok 479 should be equal
# teardown
# setup
# #testThaliPeerAction - make sure ids are unique
ok 480 should not be equal
# teardown
# setup
# Test PeerConnectionInformation basics
ok 481 connection type works
ok 482 getHostAddress works
ok 483 getPortNumber works
ok 484 getSuggestedTCPTimeout works
# teardown
# setup
# Test PeerDictionary basic functionality
ok 485 Entry counter must be 1
ok 486 Size must be 1
ok 487 Entry counter must be 2
ok 488 Size must be 2
ok 489 Entry2 should not be found
ok 490 Size must be 1
ok 491 Size must be 0
# teardown
# setup
# Test PeerDictionary with multiple entries.
ok 492 Size must be100
ok 493 Entries between 20 and MAXSIZE + 20 should exist
ok 494 WAITING state entry should not be removed
# teardown
# setup
# RESOLVED entries are removed before WAITING state entry.
ok 495 Entries between 6 and MAXSIZE + 4 should exist
ok 496 Size should be MAXSIZE
ok 497 Size should be MAXSIZE+6
# teardown
# setup
# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
ok 498 WAITING state entry should not be removed
ok 499 Waiting entries between 6 and MAXSIZE + 4 should exist
ok 500 Size should be MAXSIZE
ok 501 entryCounter should be MAXSIZE+6
# teardown
# setup
# When CONTROLLED_BY_POOL entry is removed and kill is called.
ok 502 Kill should be called once
ok 503 Size should be 100
# teardown
# setup
# #ThaliPeerPoolInterface - bad enqueues
ok 504 null arg
ok 505 wrong arg type
ok 506 wrong state
# teardown
# setup
# #ThaliPeerPoolInterface - do not allow same object type
ok 507 good enqueue
ok 508 should be equal
# teardown
# setup
# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
ok 509 good enqueue
ok 510 2nd good enqueue
ok 511 we are in the pool
ok 512 We are out of the pool
ok 513 Action was killed
ok 514 The original kill was called too
ok 515 second item is still in queue
# teardown
# setup
# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
ok 516 good enqueue
ok 517 first kill
ok 518 second NOOP kill
# teardown
# setup
# Make sure peerDictionaryKey is reasonable
ok 519 equal keys
ok 520 not equal connection type
ok 521 same connection type, different buffer
# teardown
# setup
# Make sure start works
ok 522 First start and on called correctly
# teardown
# setup
# Make sure stop works
ok 523 second cleared dictionary
ok 524 First start and on called correctly
ok 525 First stop and removeListener called correctly
ok 526 first action kill called
ok 527 second action kill called
ok 528 first cleared dictionary
ok 529 second cleared dictionary
# teardown
# setup
# Simple peer event
ok 530 listener has been set
ok 531 peer dictionary has expected number of entries
ok 532 Dictionary and pool have same action
ok 533 ads match
ok 534 PouchDB matches
ok 535 DB Names match
ok 536 public keys match
ok 537 peer dictionary has expected number of entries
ok 538 Dictionary and pool have same action
ok 539 ads match
ok 540 PouchDB matches
ok 541 DB Names match
ok 542 public keys match
ok 543 start called once
ok 544 kill never called
ok 545 One entry left
ok 546 Dictionary and pool have same action
ok 547 Start never called
ok 548 Kill called once
ok 549 no entries left
ok 550 Third action is dead
ok 551 peer dictionary has expected number of entries
ok 552 Dictionary and pool have same action
ok 553 ads match
ok 554 PouchDB matches
ok 555 DB Names match
ok 556 public keys match
# teardown
# setup
# Server is not there
DEBUG thaliReplicationPeerAction: Got error on replication - Error: connect ECONNREFUSED
ok 557 right error
# teardown
# setup
# Server accepts & closes connection
DEBUG thaliReplicationPeerAction: Got error on replication - Error: socket hang up
ok 558 right error
# teardown
# setup
# Server always returns 500
DEBUG thaliReplicationPeerAction: Got error on replication - 
ok 559 Got error as expected
# teardown
# setup
# Server always returns 401
DEBUG thaliReplicationPeerAction: Got error on replication - 
ok 560 Got error as expected
# teardown
# setup
# Server always returns 403
DEBUG thaliReplicationPeerAction: Got error on replication - 
ok 561 Got error as expected
# teardown
# setup
# Make sure docs replicate
DEBUG thaliReplicationPeerAction: Replication resumed
DEBUG thaliReplicationPeerAction: Got paused with undefined
ok 562 should be equal
ok 563 All tests passed!
# teardown
# setup
# Do nothing and make sure we time out
DEBUG thaliReplicationPeerAction: Got paused with undefined
ok 564 action should be killed
ok 565 Error should be timed out
ok 566 No doc found
# teardown
# setup
# Do something and make sure we time out
DEBUG thaliReplicationPeerAction: Replication resumed
DEBUG thaliReplicationPeerAction: Got paused with undefined
ok 567 should be equal
ok 568 action should be killed
ok 569 Error should be timed out
# teardown
# setup
# Start replicating and then catch error when server goes
ok 570 socket hung up
# teardown
# setup
# compareBufferArrays
ok 571 should throw
ok 572 should throw
ok 573 (unnamed assert)
ok 574 (unnamed assert)
ok 575 (unnamed assert)
ok 576 (unnamed assert)
ok 577 (unnamed assert)
# teardown
# setup
# Call start twice and get error
ok 578 should throw
# teardown
# setup
# Start and make sure it runs
# teardown
# setup
# Make sure getTimeWhenRun is right after start
ok 579 (unnamed assert)
# teardown
# setup
# Make sure getTimeWhenRun is -1 after function is called
ok 580 should be equal
# teardown
# setup
# Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
ok 581 should be equal
ok 582 should be equal
ok 583 should throw
# teardown
# setup
# Test TransientState
ok 584 should throw
ok 585 should throw
ok 586 should be equal
ok 587 should be equal
ok 588 should be equal
ok 589 should be equal
ok 590 (unnamed assert)
ok 591 (unnamed assert)
# teardown
# setup
# No peers and empty database
ok 592 verify failed
ok 593 constructor called once
ok 594 constructor called with right args
ok 595 match start arg
ok 596 start called once
ok 597 stop called once
ok 598 stop after start
# teardown
# setup
# One peer and empty DB
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 599 verify failed
ok 600 constructor called once
ok 601 constructor called with right args
ok 602 match start arg
ok 603 start called once
ok 604 stop called once
ok 605 stop after start
# teardown
# setup
# One peer with _Local set behind current seq
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 606 verify failed
ok 607 constructor called once
ok 608 constructor called with right args
ok 609 match start arg
ok 610 start called once
ok 611 stop called once
ok 612 stop after start
# teardown
# setup
# One peer with _Local set equal to current seq
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 613 verify failed
ok 614 constructor called once
ok 615 constructor called with right args
ok 616 match start arg
ok 617 start called once
ok 618 stop called once
ok 619 stop after start
# teardown
# setup
# One peer with _Local set ahead of current seq (and no this should not happen)
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 620 verify failed
ok 621 constructor called once
ok 622 constructor called with right args
ok 623 match start arg
ok 624 start called once
ok 625 stop called once
ok 626 stop after start
# teardown
# setup
# Three peers, one not in DB, one behind and one ahead
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 627 verify failed
ok 628 constructor called once
ok 629 constructor called with right args
ok 630 match start arg
ok 631 start called once
ok 632 stop called once
ok 633 stop after start
# teardown
# setup
# More than maximum peers, make sure we only send maximum allowed
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 634 verify failed
ok 635 constructor called once
ok 636 constructor called with right args
ok 637 match start arg
ok 638 start called once
ok 639 stop called once
ok 640 stop after start
# teardown
# setup
# two peers with empty DB, update the doc
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 641 verify failed
ok 642 constructor called once
ok 643 constructor called with right args
ok 644 last start before stop
ok 645 empty first start
ok 646 full second start
ok 647 only 2 timers
# teardown
# setup
# add doc and make sure tokens refresh when they expire
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 648 verify failed
ok 649 constructor called once
ok 650 constructor called with right args
ok 651 start before stop
ok 652 We got at least 3 calls to start
ok 653 at least 3
ok 654 default 1
ok 655 1 run
ok 656 default 2
ok 657 2 run
ok 658 default 3
# teardown
# setup
# start and stop and start and stop
ok 659 start out null
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 660 back to null
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 661 still null
ok 662 verify failed
ok 663 constructor called once
ok 664 constructor called with right args
ok 665 first start before first stop
ok 666 first stop before second start
ok 667 second start before second stop
# teardown
# setup
# two identical starts in a row
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 668 verify failed
ok 669 constructor called once
ok 670 constructor called with right args
ok 671 (unnamed assert)
# teardown
# setup
# two different starts in a row
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 672 verify failed
ok 673 constructor called once
ok 674 constructor called with right args
ok 675 (unnamed assert)
ok 676 (unnamed assert)
# teardown
# setup
# two stops and a start and two stops
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 677 verify failed
ok 678 constructor called once
ok 679 constructor called with right args
ok 680 start before stop
# teardown
# setup
# we properly enqueue requests so no then needed
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 681 verify failed
ok 682 constructor called once
ok 683 constructor called with right args
ok 684 start before stop
# teardown
# setup
# test calculateSeqPointKeyId
ok 685 should be equal
ok 686 should be equal
# teardown
# setup
# can create servers manager
ok 687 serversManager must not be null
ok 688 serversManager must be an object
# teardown
# setup
# calling stop without start causes error
ok 689 We need to call start first
# teardown
# setup
# can start/stop servers manager
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50341
ok 690 port must be in range
# teardown
# setup
# starting twice resolves with listening port
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50342
ok 691 second start should return same port
# teardown
# setup
# terminateIncomingConnection will terminate a connection
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50344
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 692 we should be connected
DEBUG createNativeListener: incoming socket close
ok 693 now we are disconnected
# teardown
# setup
# terminate an Outgoing connection will terminate the server
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50346
# teardown
# setup
# terminate an Outgoing connection with wrong arguments is not harmful
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50347
# teardown
# setup
ok 694 should be in started state
# After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
ok 695 peer identifier should match
ok 696 host address should match
ok 697 port should match
ok 698 host address should be null
ok 699 port should should be null
# teardown
ok 700 should not be in started state
# setup
ok 701 should be in started state
# #startUpdateAdvertisingAndListening should use different USN after every invocation
ok 702 USN should have changed from the first one
ok 703 when receiving the second byebye, the first USN should be already set
# teardown
ok 704 should not be in started state
# setup
ok 705 should be in started state
# messages with invalid location or USN should be ignored
WARN thaliWifiInfrastructure: Failed to parse a valid port number from location: http://foo.bar:90000
ok 706 should not have emitted with invalid port
WARN thaliWifiInfrastructure: Received an invalid USN value: 
ok 707 should not have emitted with invalid USN
# teardown
ok 708 should not be in started state
# setup
ok 709 should be in started state
# verify that Thali-specific messages are filtered correctly
ok 710 irrelevant messages should be ignored
ok 711 relevant messages should not be ignored
ok 712 messages from this device should be ignored
# teardown
ok 713 should not be in started state
# setup
ok 714 should be in started state
# #startListeningForAdvertisements should fail if start not called
ok 715 specific error should be returned
# teardown
ok 716 should not be in started state
# setup
ok 717 should be in started state
# #startUpdateAdvertisingAndListening should fail if start not called
ok 718 specific error should be returned
# teardown
ok 719 should not be in started state
# setup
ok 720 should be in started state
# #start should fail if called twice in a row
ok 721 specific error should be received
# teardown
ok 722 should not be in started state
# setup
ok 723 should be in started state
# should not be started after stop is called
ok 724 should not be started
ok 725 should not be listening
ok 726 should not target listening
ok 727 should not be advertising
ok 728 should not target advertising
# teardown
ok 729 should not be in started state
# setup
ok 730 should be in started state
# #startUpdateAdvertisingAndListening should fail invalid router has been passed
ERROR thaliWifiInfrastructure: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
ok 731 specific error should be received
# teardown
ok 732 should not be in started state
# setup
ok 733 should be in started state
# #startUpdateAdvertisingAndListening should fail if router server starting fails
ERROR thaliWifiInfrastructure: Router server emitted an error: Error: listen EADDRINUSE
ok 734 specific error expected
# teardown
ok 735 should not be in started state
# setup
ok 736 should be in started state
# #startUpdateAdvertisingAndListening should start hosting given router object
ok 737 server should respond with code 200
# teardown
ok 738 should not be in started state
# setup
ok 739 should be in started state
# #startUpdateAdvertisingAndListening bad psk should be rejected object
ok 740 Connection should be rejected
# teardown
ok 741 should not be in started state
# setup
ok 742 should be in started state
# #stop can be called multiple times in a row
ok 743 should be in stopped state
ok 744 should still be in stopped state
# teardown
ok 745 should not be in started state
# setup
ok 746 should be in started state
# #startListeningForAdvertisements can be called multiple times in a row
ok 747 should be in listening state
ok 748 should still be in listening state
# teardown
ok 749 should not be in started state
# setup
ok 750 should be in started state
# #stopListeningForAdvertisements can be called multiple times in a row
ok 751 should not be in listening state
ok 752 should still not be in listening state
# teardown
ok 753 should not be in started state
# setup
ok 754 should be in started state
# #stopAdvertisingAndListening can be called multiple times in a row
ok 755 should not be in advertising state
ok 756 should still not be in advertising state
# teardown
ok 757 should not be in started state
# setup
ok 758 should be in started state
# functions are run from a queue in the right order
ok 759 call order must match
# teardown
ok 760 should not be in started state
# setup
ok 761 should be in started state
# does not get peer changes from self
ok 762 USN must have changed again
# teardown
ok 763 should not be in started state
# setup
ok 764 should be in started state
# network changes are ignored while stopping
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 765 should not be called
# teardown
ok 766 should not be in started state
# setup
ok 767 should be in started state
# #startListeningForAdvertisements returns error if wifi is off and fires event when on
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 768 wifi should be off
ok 769 specific error expected
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 770 discoveryActive should be true
# teardown
ok 771 should not be in started state
# setup
ok 772 should be in started state
# #startUpdateAdvertisingAndListening returns error if wifi is off and fires event when on
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 773 wifi should be off
ok 774 specific error expected
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 775 advertisingActive should be true
# teardown
ok 776 should not be in started state
# setup
ok 777 should be in started state
# when wifi is enabled discovery is activated and peers become available
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 778 wifi should be off
ok 779 specific error expected
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 780 peer identifier should match
ok 781 host address should match
ok 782 port should match
# teardown
ok 783 should not be in started state
# setup
not ok 784 Deliberatly setup failure
  ---
    operator: fail
    at: Test.tape.setup (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testUnitTestFramework.js:7:7)
  ...
# Issue #691: test failure during setup
# teardown
# setup
# Issue #691: test failure during teardown
# teardown
not ok 785 Deliberatly teardown failure
  ---
    operator: fail
    at: Test.tape.teardown (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testUnitTestFramework.js:24:7)
  ...
# setup
# #ThaliPeerPoolDefault - single action
ok 786 is an agent
ok 787 enqueue is fine
ok 788 Everything should be off the queue
# teardown
# setup
# #ThaliPeerPoolDefault - multiple actions
ok 789 is an agent
ok 790 first enqueue is fine
ok 791 is an agent
ok 792 second enqueue is fine
ok 793 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 794 Queue is empty
# teardown
# setup
# #ThaliPeerPoolDefault - PSK Pool works
ok 795 is an agent
ok 796 good enqueue
ok 797 Identity should match
ok 798 Got expected response
ok 799 Got psk call back
# teardown
# setup
# #ThaliPeerPoolDefault - stop
ok 800 is an agent
ok 801 enqueue worked
ok 802 is an agent
ok 803 enqueue 2 worked
ok 804 start action is killed
ok 805 killed action is still killed
ok 806 inQueue is empty
ok 807 Make sure we won enqueue after stopping
# teardown

1..807
# tests 807
# pass  805
# fail  2

-e [0;31mcompilation aborted
 [0m
build aborted
 [0m

cp: testBuildOrg//.git/objects/9c/558e357c41674e39880abb6c3209e539de42e2: No such file or directory
cp: testBuildOrg//.git/objects/9c/560864575e93a8f8b728faeb71009703e9d58c: No such file or directory
cp: testBuildOrg//.git/objects/9c/5a3ba5aa1a9a903982985623573bbaf3f4f545: No such file or directory
cp: testBuildOrg//.git/objects/9c/5be7335aa574f9fe65e38fd9211db6322313a2: No such file or directory
cp: testBuildOrg//.git/objects/9c/5c74933221490599638313c65d58aa784ddd48: No such file or directory
cp: testBuildOrg//.git/objects/9c/5fb24996524f3cd91f6ea8aa63093b6e9d9f7f: No such file or directory
cp: testBuildOrg//.git/objects/9c/60a3ee147f45d1ab26df82ac1ebbe0947c49f8: No such file or directory
cp: testBuildOrg//.git/objects/9c/612424b341739c062a88059fdd872bc170c0cd: No such file or directory
cp: testBuildOrg//.git/objects/9c/61b918185efde06cce0c13854487f8c98887c3: No such file or directory
cp: testBuildOrg//.git/objects/9c/62280d81b834be794b34d39a76691f1bb21e99: No such file or directory
cp: testBuildOrg//.git/objects/9c/71b3badca23986e9b8644800caf719b3892ef0: No such file or directory
cp: testBuildOrg//.git/objects/9c/73de9430430be2ddad3c1c3e13fa175097aa08: No such file or directory
cp: testBuildOrg//.git/objects/9c/7ecf1268ed8d4d5669662250fd4b1e62758c8e: No such file or directory
cp: testBuildOrg//.git/objects/9c/87be5c7ec1db0e5cf4aa0c4533e663831af768: No such file or directory
cp: testBuildOrg//.git/objects/9c/89154a6b22ac746063aa6b1b126e2d9fd033b4: No such file or directory
cp: testBuildOrg//.git/objects/9c/893638b02eef82f9b5a9c6fe893d1b8af3fdbe: No such file or directory
cp: testBuildOrg//.git/objects/9c/89fa44483728eff07b195490ce6e6f3289a83f: No such file or directory
cp: testBuildOrg//.git/objects/9c/8a3f4b5357bed9669b514f5fef22bce63174c6: No such file or directory
cp: testBuildOrg//.git/objects/9c/91ee57ad376bf4ca61d668c67a3526abb7e8f9: No such file or directory
cp: testBuildOrg//.git/objects/9c/a045e02a072a0f8df80573ddaf6e1fa33eba68: No such file or directory
cp: testBuildOrg//.git/objects/9c/a27ce9e9811e6633e54052eeffc7bbdf947f95: No such file or directory
cp: testBuildOrg//.git/objects/9c/a3c7f49baf1bd0b903cd14dd77084bbfbde372: No such file or directory
cp: testBuildOrg//.git/objects/9c/ac5b5f594e268e42cd561dd1fea60e5a419649: No such file or directory
cp: testBuildOrg//.git/objects/9c/ae33a297fee1a388dbd081b1c9974e2b36bffb: No such file or directory
cp: testBuildOrg//.git/objects/9c/b0282ebd75f67bad3e92a60a5c8a7480582df8: No such file or directory
cp: testBuildOrg//.git/objects/9c/b2f94dec0a82613de5df97047741a203ef734e: No such file or directory
cp: testBuildOrg//.git/objects/9c/bac6a011e0a5bf7001184ffa6d82c91e9fbfee: No such file or directory
cp: testBuildOrg//.git/objects/9c/c07aa7e0ba46b38a396d2b0d0a06608b579fdc: No such file or directory
cp: testBuildOrg//.git/objects/9c/c6f1cfc649a17e5c99d43776985e6458f7de42: No such file or directory
cp: testBuildOrg//.git/objects/9c/c7df1e6e6f54e9f1da32895ebc5a87f5cae386: No such file or directory
cp: testBuildOrg//.git/objects/9c/ce6456e5a1a28cbac65ac8b55f51290ccd24a2: No such file or directory
cp: testBuildOrg//.git/objects/9c/d652f9be64b96acc0889731461a7d248c61299: No such file or directory
cp: testBuildOrg//.git/objects/9c/d874398a65023948f270e26e6e15dc70c1c4af: No such file or directory
cp: testBuildOrg//.git/objects/9c/e4518abd6afd9ef2fc38acec1742edc4331af5: No such file or directory
cp: testBuildOrg//.git/objects/9c/f16222f041f58b74666144496811a0603580de: No such file or directory
cp: testBuildOrg//.git/objects/9c/fb3a28e1f38e17de834d6d9b55d20ae616e89d: No such file or directory
cp: testBuildOrg//.git/objects/9c/fe3b62c8da9b28a40b390bd0cd5631361f4199: No such file or directory
cp: testBuildOrg//.git/objects/a8/d7abe6d2340ab89447ced4917a44c430b6a710: No such file or directory
cp: testBuildOrg//.git/objects/a8/e4b01e3c3965bde68df812c9b88fa668348070: No such file or directory
cp: testBuildOrg//.git/objects/a8/f29bf75a0369a8ed40e8a0fbeb9c13dc7e7f42: No such file or directory
cp: testBuildOrg//.git/objects/a8/f658f14eb4fd5a0716eccd101631ac41f0bb0e: No such file or directory
cp: testBuildOrg//.git/objects/a9/6e324cfa03ba588d9957a55a989c992ac934eb: No such file or directory
cp: testBuildOrg//.git/objects/a9/784c2972ad7905f95a77fc8fdbc2e84ae0e2e5: No such file or directory
cp: testBuildOrg//.git/objects/a9/7b769e3e5b275e9cb92f7a5d00840b85d44fe3: No such file or directory
cp: testBuildOrg//.git/objects/a9/7c4156995a27e4501d9ee2c8ee66b183f16664: No such file or directory
cp: testBuildOrg//.git/objects/a9/7e458ca3043946b2b8fdd1091019a2d1bb5a03: No such file or directory
cp: testBuildOrg//.git/objects/a9/80235e96dab80a2463634caca28be53e7253a9: No such file or directory
cp: testBuildOrg//.git/objects/a9/8c1d2fae9cebaeeef7ab03d5a8526d15e26b3b: No such file or directory
cp: testBuildOrg//.git/objects/a9/928e773b5947b5a56f2bda8fe67306c665f623: No such file or directory
cp: testBuildOrg//.git/objects/a9/ac1fa3b14369589095f9b15baecd60e8485a7a: No such file or directory
cp: testBuildOrg//.git/objects/a9/b0c66f04c6c56b05e364141fe82666ae875b21: No such file or directory
cp: testBuildOrg//.git/objects/a9/b43e85de5e278b46cf423e80d335c63f1893db: No such file or directory
cp: testBuildOrg//.git/objects/a9/bbbdda6f45fdab24529e9e09466705788f1a75: No such file or directory
cp: testBuildOrg//.git/objects/a9/bd21e532806eabb47887f79f88906c5f322a3f: No such file or directory
cp: testBuildOrg//.git/objects/a9/c9b2f21cd7ea0b87b908c097e1c08b9b048b9f: No such file or directory
cp: testBuildOrg//.git/objects/a9/c9dc7289447b8159c840d1edf5b1af403405f2: No such file or directory
cp: testBuildOrg//.git/objects/a9/cbef23af3991a25174b409e3716d875cba66d0: No such file or directory
cp: testBuildOrg//.git/objects/a9/cf2029346ad4e6159e25378908755cadb11abf: No such file or directory
cp: testBuildOrg//.git/objects/a9/db8a3572a75794b215c435adfafd79c9c456a8: No such file or directory
cp: testBuildOrg//.git/objects/a9/e42bba40137d94cd4ced6c1d204af1dd075984: No such file or directory
cp: testBuildOrg//.git/objects/a9/e62a349c8ea5165762da05a4197cfe56b2f019: No such file or directory
cp: testBuildOrg//.git/objects/a9/e83831555efe3b9f4c1ff093398b48b571a1e6: No such file or directory
cp: testBuildOrg//.git/objects/a9/f7756c8390f7b6f8cb985e82bffc7aa6aa4b62: No such file or directory
cp: testBuildOrg//.git/objects/a9/f86f0e7a851628c3c07035b3f0d7c13fe8b552: No such file or directory
cp: testBuildOrg//.git/objects/aa/301c2251128c2015276861382161f1ba5a8f13: No such file or directory
cp: testBuildOrg//.git/objects/aa/30ae2ded039fb3b77c1317bcd71ff76c63fd75: No such file or directory
cp: testBuildOrg//.git/objects/aa/30fe81b8a71e1f74c6cf8dbaac96bcf54e6b0b: No such file or directory
cp: testBuildOrg//.git/objects/aa/3bd361cd85d0d85ca6c6d04a096ae6476ba16e: No such file or directory
cp: testBuildOrg//.git/objects/aa/3e2d78e8bad8dc2534bffa10dc5be7011ea3a3: No such file or directory
cp: testBuildOrg//.git/objects/aa/4323293f47d0d9e2dd21b1cb6180227c64f003: No such file or directory
cp: testBuildOrg//.git/objects/aa/4a6e322e14838f73e3f3b49ea16ca076ec394a: No such file or directory
cp: testBuildOrg//.git/objects/aa/5627958c8a18dc6ca29f5ccaa6dc45a0e6aafd: No such file or directory
cp: testBuildOrg//.git/objects/aa/567886768069e7b8dd05fda619083f4add29cb: No such file or directory
cp: testBuildOrg//.git/objects/aa/56850e4c213cc63aa1579cf0d7fec8ab230a0b: No such file or directory
cp: testBuildOrg//.git/objects/aa/6916a9ac35d6ccc907aaffd51868763443e2fd: No such file or directory
cp: testBuildOrg//.git/objects/aa/7739e72f869123ef829310b7f18580876397e1: No such file or directory
cp: testBuildOrg//.git/objects/aa/7cc9239be58ef4393531be653a71d6ac649b48: No such file or directory
cp: testBuildOrg//.git/objects/aa/93e39a3032f0bd057822ebfc5a7ce7f75656aa: No such file or directory
cp: testBuildOrg//.git/objects/aa/98d07a791da0627f7c6fd98f3c42b50bceae49: No such file or directory
cp: testBuildOrg//.git/objects/aa/9f129219217c51c038ffbff1dbe21ee3c3ac3c: No such file or directory
cp: testBuildOrg//.git/objects/aa/a0562a99e1a2742c54cd112fcc3a750e7341c8: No such file or directory
cp: testBuildOrg//.git/objects/aa/a35171cac2d30edeafd32900ca47afd6b5e76a: No such file or directory
cp: testBuildOrg//.git/objects/aa/a3c6244b02b097803f6b07b1daaba00d510e5a: No such file or directory
cp: testBuildOrg//.git/objects/aa/a3c96c24f98a713a6460981df1392cc6b9bd6e: No such file or directory
cp: testBuildOrg//.git/objects/aa/a41b7e8d7c84918dbca9d45fd020df76f20971: No such file or directory
cp: testBuildOrg//.git/objects/aa/aa6912fc94aec5d0c6c048a7139b732e9faa23: No such file or directory
cp: testBuildOrg//.git/objects/aa/c134fb0b18f36e4dd51d38c6419ce34855ee90: No such file or directory
cp: testBuildOrg//.git/objects/aa/c35f15996990893f8c18c9a0af3193e5171ba5: No such file or directory
cp: testBuildOrg//.git/objects/aa/c82a09b3fd9ff5ca728a8eebbcb0fb95b2905c: No such file or directory
cp: testBuildOrg//.git/objects/aa/d2ff3928ed20067363c1a9e646d97297bcd49b: No such file or directory
cp: testBuildOrg//.git/objects/aa/d5c893539d0d372255d85c0bd7443351aa8e78: No such file or directory
cp: testBuildOrg//.git/objects/aa/e328d7aa0ad2c48057b05ff7bd5a3f9705816e: No such file or directory
cp: testBuildOrg//.git/objects/aa/e7080b5fad28a88452469c339394bfbe8b5582: No such file or directory
cp: testBuildOrg//.git/objects/aa/eb160e56581a781e00e0f329573b9894985afc: No such file or directory
cp: testBuildOrg//.git/objects/aa/f5b26e189de940b58af7e0b7f382d479ce287d: No such file or directory
cp: testBuildOrg//.git/objects/aa/fa7ca1539a6c25a85ba831f9e0c7e2afa73166: No such file or directory
cp: testBuildOrg//.git/objects/aa/fd65f357fb432a08b275d3e17654b1867cd0d6: No such file or directory
cp: testBuildOrg//.git/objects/aa/ffc484296f31a18c4d59300e150eef0d101784: No such file or directory
cp: testBuildOrg//.git/objects/ab/ed9be56909c92d0de97d7252d4960abdc12c2b: No such file or directory
cp: testBuildOrg//.git/objects/ab/edf605fef945575b4409f8a08268e21da52c6a: No such file or directory
cp: testBuildOrg//.git/objects/ab/f85dffc996d80c1f0d739ef1ef61e4459fe29f: No such file or directory
cp: testBuildOrg//.git/objects/ab/f99dd3f0c68e2f4fdbf397010985adcb3fa757: No such file or directory
cp: testBuildOrg//.git/objects/ab/fc33ebcb18d5de50aec64cd082a8e31620346e: No such file or directory
cp: testBuildOrg//.git/objects/ab/ffe1101e964879593443f6013e8f138c8f995f: No such file or directory
cp: testBuildOrg//.git/objects/ae/163044ab51d4287d0d0a5ad786ee4b93a18bcc: No such file or directory
cp: testBuildOrg//.git/objects/ae/1703d6bfb3dbb58d63ccbf4cdaca36a6994e85: No such file or directory
cp: testBuildOrg//.git/objects/ae/1a75db20d2f624f7be589da990e5ef0ef653dd: No such file or directory
cp: testBuildOrg//.git/objects/ae/295f392fb49f2ead2e97aca1b53e77e8755cfb: No such file or directory
cp: testBuildOrg//.git/objects/ae/2c96674f3c97c2f3c81cad10cc4a691a61f8fc: No such file or directory
cp: testBuildOrg//.git/objects/ae/31ccce9186a2a2d69d05aa9717f83c71e4f954: No such file or directory
cp: testBuildOrg//.git/objects/ae/32d3f9e02c71284317495a3d1ef79eb98a98b1: No such file or directory
cp: testBuildOrg//.git/objects/ae/51cc157f15ac037787987678e072001bf2bdd0: No such file or directory
cp: testBuildOrg//.git/objects/ae/52a62e55f0a314c56e9500e09f02ac1c9bdad6: No such file or directory
cp: testBuildOrg//.git/objects/ae/58f774b1fd895a31233051b5a10598ea3886cf: No such file or directory
cp: testBuildOrg//.git/objects/ae/5e9980058317cea96cc38ac4e6ff988f86e773: No such file or directory
cp: testBuildOrg//.git/objects/ae/6319362837929f4da315e41e65b6c97408d099: No such file or directory
cp: testBuildOrg//.git/objects/ae/6bca068381ccd78a1c9653e83771add7fc3a15: No such file or directory
cp: testBuildOrg//.git/objects/ae/834132d4a06e64dd4449a64143965058182403: No such file or directory
cp: testBuildOrg//.git/objects/ae/8c494e1425ffef45ed24f606fda5b4d515b974: No such file or directory
cp: testBuildOrg//.git/objects/ae/8d1c67e72f9e1e5159782e8aee0b90b9fd74eb: No such file or directory
cp: testBuildOrg//.git/objects/ae/90032ff449339099c612f0c4209249ad7bc4ab: No such file or directory
cp: testBuildOrg//.git/objects/ae/9167462d4cbf45036b7a3500595131d44d7ba8: No such file or directory
cp: testBuildOrg//.git/objects/ae/930729b4144eb2e9b5d630a314fc5c93001ce7: No such file or directory
cp: testBuildOrg//.git/objects/ae/95041a9208e2a9b52d640cefa36db11a109f93: No such file or directory
cp: testBuildOrg//.git/objects/ae/95360d487301789b8aa447ac44194ebebb8788: No such file or directory
cp: testBuildOrg//.git/objects/ae/9830ce52182184e0c1d052cb238b105dd4bfbd: No such file or directory
cp: testBuildOrg//.git/objects/ae/9b385d09cfc2ebea8f1b98dcd3d34f549f00d6: No such file or directory
cp: testBuildOrg//.git/objects/ae/a7c0ece77565d35f9a1323cbd95c2aba09cd08: No such file or directory
cp: testBuildOrg//.git/objects/ae/b9befdda901bafc033f501ea4a6d9a38651c39: No such file or directory
cp: testBuildOrg//.git/objects/ae/c19f2f3d00ca1a5104e3a36405e2aeef75d403: No such file or directory
cp: testBuildOrg//.git/objects/ae/c8023dc6638129c5790f6992510e055c3f7a5b: No such file or directory
cp: testBuildOrg//.git/objects/ae/dcce72e2f80480394d23d9b32750847b7abad7: No such file or directory
cp: testBuildOrg//.git/objects/ae/e40209e7c770672c02a0c957cfb72804d6aca3: No such file or directory
cp: testBuildOrg//.git/objects/ae/eb190353afb9c9690902131f68b1c7c4c39c81: No such file or directory
cp: testBuildOrg//.git/objects/ae/ecb4b984ff55304a242d4d81dcca56a9875390: No such file or directory
cp: testBuildOrg//.git/objects/ae/f3d766f86f9f75bd5c55a1ac880d4dc5840eec: No such file or directory
cp: testBuildOrg//.git/objects/ae/fbd2ef8f862f2492947727baf5fa0e50a4e991: No such file or directory
cp: testBuildOrg//.git/objects/ae/fed65677c67a567739ef52c1b3a935ce9d5d1a: No such file or directory
cp: testBuildOrg//.git/objects/af/2c956691278cba05c8968a23e9d1a425a35944: No such file or directory
cp: testBuildOrg//.git/objects/af/34780bcd5d156771ade907d3650b654c7e349a: No such file or directory
cp: testBuildOrg//.git/objects/af/35f5880575071570c1df6646b597bad01b2101: No such file or directory
cp: testBuildOrg//.git/objects/af/3b2c456087815ab65402f47b4372036a975dfe: No such file or directory
cp: testBuildOrg//.git/objects/af/451c0cb8a4190d652a43d9c9c424c2c270f488: No such file or directory
cp: testBuildOrg//.git/objects/af/4a7e87a1a4863e5bf17492f1b46a33f43734d5: No such file or directory
cp: testBuildOrg//.git/objects/af/4ba54a7b27a6623711eb794d938ba3f9069740: No such file or directory
cp: testBuildOrg//.git/objects/af/50e5e423ce2634d7948e32e4f3ea0156fbb344: No such file or directory
cp: testBuildOrg//.git/objects/af/643a3189cd54b89029ff2323a03161815d1653: No such file or directory
cp: testBuildOrg//.git/objects/af/6b7599d9e1f3bfba1ca01aa0f14e8f97a0124c: No such file or directory
cp: testBuildOrg//.git/objects/af/6c07b8efff14e1dfbe82139e421d168f29142c: No such file or directory
cp: testBuildOrg//.git/objects/af/797b87c5026b813154d94d723e51f69867502e: No such file or directory
cp: testBuildOrg//.git/objects/af/8192de24c6735e87cd7c745b851d53be4b04ef: No such file or directory
cp: testBuildOrg//.git/objects/af/81f3cf2d6e11e8016193290247e076d39fcc79: No such file or directory
cp: testBuildOrg//.git/objects/af/971393f2f69eea8fbee4649e3271e215e647af: No such file or directory
cp: testBuildOrg//.git/objects/af/97a777cc2c71bd4802821a29f169015a1bf1d3: No such file or directory
cp: testBuildOrg//.git/objects/af/9f0015229df34f87de06ae435e14225edf7924: No such file or directory
cp: testBuildOrg//.git/objects/af/a1391849ecf824af592da31c321aca4f065212: No such file or directory
cp: testBuildOrg//.git/objects/af/a53c9dedaed32e42aadaea5308ae27b3a8469c: No such file or directory
cp: testBuildOrg//.git/objects/af/a71b18fcb8a97e4bf6619343c49ca07b27f509: No such file or directory
cp: testBuildOrg//.git/objects/af/af1d71e254cdda304399921d7b59956e487a08: No such file or directory
cp: testBuildOrg//.git/objects/af/af6eb57cdf45c9ea58787e543580f138524813: No such file or directory
cp: testBuildOrg//.git/objects/af/b8ab2574927ee62f22705bfea7f4d8a6755ab0: No such file or directory
cp: testBuildOrg//.git/objects/af/c362153b4915a973015c5a125bfb1c09d444e1: No such file or directory
cp: testBuildOrg//.git/objects/af/c4b959e45d1ee70cac4c94e4ed58458ca75097: No such file or directory
cp: testBuildOrg//.git/objects/af/ca3379eb9aafb8704571cb5d7ee36ff0197a9a: No such file or directory
cp: testBuildOrg//.git/objects/af/cf2d1b354517105b6c9aaced37b823b0374066: No such file or directory
cp: testBuildOrg//.git/objects/af/d4f67b6751f39cb0f1188a4826cca8ed5792c6: No such file or directory
cp: testBuildOrg//.git/objects/af/e67cbbf007cc656b883930e1a956510c5fc59d: No such file or directory
cp: testBuildOrg//.git/objects/af/e89f1e73ac1c2d2304cf3b01754df8dac40118: No such file or directory
cp: testBuildOrg//.git/objects/af/eb1f40f0bfa7af7017ec95f75e2da629ecf01d: No such file or directory
cp: testBuildOrg//.git/objects/af/ecdbf60ce8e0d5e06ccf6f4778d563fbb75006: No such file or directory
cp: testBuildOrg//.git/objects/af/ee8df5ea7376aabbdb2e17d9676417a894c2f2: No such file or directory
cp: testBuildOrg//.git/objects/af/f10f5e8df4b108ad5976a3c293daa6d01275f6: No such file or directory
cp: testBuildOrg//.git/objects/af/f19f44e6d03699b0783e60140bc4465f817c39: No such file or directory
cp: testBuildOrg//.git/objects/af/f41e16d92dc44851c28fe5973901982e3b4ef4: No such file or directory
cp: testBuildOrg//.git/objects/af/ff9c516b16675f1a5f46fe28392ec470a579e8: No such file or directory
cp: testBuildOrg//.git/objects/b0/36308b6ed9d9491a2e3c3cd15ec351da15f5d2: No such file or directory
cp: testBuildOrg//.git/objects/b0/394d036476e9be750ae35cdd1d49e7b433956a: No such file or directory
cp: testBuildOrg//.git/objects/b0/3c61c66bd120a0369bc506c1d9525abe0e8cbe: No such file or directory
cp: testBuildOrg//.git/objects/b0/3d0653f2fc896ae9e7ce9d041e35666babbc14: No such file or directory
cp: testBuildOrg//.git/objects/b0/3f0ac18b4f44a1abf4d0962a04597deb821216: No such file or directory
cp: testBuildOrg//.git/objects/b0/43bea9e9588c07e9afdff237f27beae2af6fe8: No such file or directory
cp: testBuildOrg//.git/objects/b0/4e07539990621be3348922e8422e06efa73a38: No such file or directory
cp: testBuildOrg//.git/objects/b0/4e3e50f9b9ef4222fa9e9d11e8e2a9dcf59ddc: No such file or directory
cp: testBuildOrg//.git/objects/b0/4f17e1f569b06583a60eea93134aef2448ea40: No such file or directory
cp: testBuildOrg//.git/objects/b0/527faeeb33e3ea29dde1a01b6c7d6e1f544220: No such file or directory
cp: testBuildOrg//.git/objects/b0/57e931d31ce8f9583a76b8988ea5eb66aa2bba: No such file or directory
cp: testBuildOrg//.git/objects/b0/5bb1df422d81a3d999a227a76044254eb94526: No such file or directory
cp: testBuildOrg//.git/objects/b0/667f44deecaa766b12879cbf355dd30166cbd8: No such file or directory
cp: testBuildOrg//.git/objects/b0/71672b79840107fe7c1e7d2157a63bf4235879: No such file or directory
cp: testBuildOrg//.git/objects/b0/763ea1696298020aca4f59fed2bf40d77674c5: No such file or directory
cp: testBuildOrg//.git/objects/b0/768aef252629aa42408bee46c5099ed39efcca: No such file or directory
cp: testBuildOrg//.git/objects/b0/7841c1670bf397e8725698b63986182c31346e: No such file or directory
cp: testBuildOrg//.git/objects/b0/7f714ba68bd8b6d67814a2c7b0150eaf98f16d: No such file or directory
cp: testBuildOrg//.git/objects/b0/803eb0e1c6d9cbc09cbdd54d4f0d3def2b80cc: No such file or directory
cp: testBuildOrg//.git/objects/b0/8c1c4abb94328b210166247f314a8358f85709: No such file or directory
cp: testBuildOrg//.git/objects/b0/8ea6c9e146e7fb57f9ed87c73f0d4857e28c75: No such file or directory
cp: testBuildOrg//.git/objects/b0/9cdc24ddd9e67c1d3e2d8709d047db08850c10: No such file or directory
cp: testBuildOrg//.git/objects/b0/9da68968015e738f82805b0fbb53cf06dc2a17: No such file or directory
cp: testBuildOrg//.git/objects/b0/a49be1d48de3a23ef2f86f952dcd6b70a63f72: No such file or directory
cp: testBuildOrg//.git/objects/b0/ab3f22d07c3774e93c2eee5616217ba513b2d5: No such file or directory
cp: testBuildOrg//.git/objects/b0/b30a8d686e735a859f479ac193437fa8a06b98: No such file or directory
cp: testBuildOrg//.git/objects/b0/c93129f33bdc82ee4cf124f63a83dade18d60f: No such file or directory
cp: testBuildOrg//.git/objects/b0/d2de7da760a77e871c6abbbd6a5991a153a6d6: No such file or directory
cp: testBuildOrg//.git/objects/b0/de729a777c26b6c2d6ee2b3b4b585fd3be76fb: No such file or directory
cp: testBuildOrg//.git/objects/b0/deb165d127c028022d1663200ae8eb49fe420a: No such file or directory
cp: testBuildOrg//.git/objects/b0/e0167af82821b4eaa18f3509a715515522c12d: No such file or directory
cp: testBuildOrg//.git/objects/b0/e3f6454199c37c3021517389600e60f487ed32: No such file or directory
cp: testBuildOrg//.git/objects/b0/ebb78e6b448264cc578767dd453b3c7ca7d15e: No such file or directory
cp: testBuildOrg//.git/objects/b0/f4c8ad187817b13863a99bc2543443242cdb89: No such file or directory
cp: testBuildOrg//.git/objects/b1/3276f6a8747407ab3a0a6e4aed1dbcd46bfaa1: No such file or directory
cp: testBuildOrg//.git/objects/b1/350b0bfc263fb2bd4652ca873165586f098e56: No such file or directory
cp: testBuildOrg//.git/objects/b1/3a03829b0e62c760b3f1f9be788ee238c15b20: No such file or directory
cp: testBuildOrg//.git/objects/b1/4142dec8ce4d7b5914e2a89e328b413721071f: No such file or directory
cp: testBuildOrg//.git/objects/b1/488beb0128b3d7b2e8020b3775ed89cdfcaa4e: No such file or directory
cp: testBuildOrg//.git/objects/b1/48f1f9a83cdbea8fadaae328dc94df78d570b0: No such file or directory
cp: testBuildOrg//.git/objects/b1/4b9e4eb9676022d3a024c0912e91d6a06ec740: No such file or directory
cp: testBuildOrg//.git/objects/b1/526ee46d4bc1f896125c9b3f3b3edf9a43bc0a: No such file or directory
cp: testBuildOrg//.git/objects/b1/67c10f7db2ca6cc78e0cd6bf4c9045eb477b9b: No such file or directory
cp: testBuildOrg//.git/objects/b1/6a410ebfbfe93c83bc5d4f6db0023d25ddb3ee: No such file or directory
cp: testBuildOrg//.git/objects/b1/72042d385dc06bcf9349399e16eb005b6ff5d9: No such file or directory
cp: testBuildOrg//.git/objects/b1/759ae0b4514cafc3426bc16281e132f66e86de: No such file or directory
cp: testBuildOrg//.git/objects/b1/8d86a906d8be0590b7cd040cbcc5a3760128eb: No such file or directory
cp: testBuildOrg//.git/objects/b1/8dc078825137befbe426467368574438f60744: No such file or directory
cp: testBuildOrg//.git/objects/b1/a03767a48d0e3afbdeab7466cb6d1e6808fd01: No such file or directory
cp: testBuildOrg//.git/objects/b1/aca7ab2d9e4b13bc032b0cde997f8af5acdbc5: No such file or directory
cp: testBuildOrg//.git/objects/b1/aec7179ad21697f2d6a7d99e53c0ce1466be27: No such file or directory
cp: testBuildOrg//.git/objects/b1/b2a67d343ea67980880a48b157cf228373068e: No such file or directory
cp: testBuildOrg//.git/objects/b1/b5ca461d6232229bb85530bedec59fc6b03d8e: No such file or directory
cp: testBuildOrg//.git/objects/b1/b8bc38c3fb45316f6ae96b1a7cf34e7a532142: No such file or directory
cp: testBuildOrg//.git/objects/b1/b956fa72486bb6b56e57bb816a5eeef12c22aa: No such file or directory
cp: testBuildOrg//.git/objects/b1/b95e155a583d3d52ff260970752859ee4e94ce: No such file or directory
cp: testBuildOrg//.git/objects/b1/bb7f8c68fc5c47a490212bf05927a8185be7b6: No such file or directory
cp: testBuildOrg//.git/objects/b1/c0caccdf8e54919e7f8b666ded238b8fbf19e8: No such file or directory
cp: testBuildOrg//.git/objects/b1/c5caeda06d4c24f0e52da465bf52e67988f6f7: No such file or directory
cp: testBuildOrg//.git/objects/b1/cd185e0aa7056598f75443292909fb2b67931a: No such file or directory
cp: testBuildOrg//.git/objects/b1/d9f3facad29705535c47eaeb8676a769dc54ea: No such file or directory
cp: testBuildOrg//.git/objects/b1/dd5e8d8d389ac95dc9e06a330cfa623bd058d8: No such file or directory
cp: testBuildOrg//.git/objects/b1/dfc65b40a985b2d347157841f01acff9b49d21: No such file or directory
cp: testBuildOrg//.git/objects/b1/e1002174982748963693c9ab99a2339a8b2b52: No such file or directory
cp: testBuildOrg//.git/objects/b1/ea9b9e3753184c57166fc92ec4ca641161b32d: No such file or directory
cp: testBuildOrg//.git/objects/b1/f4275640e6f6d14794ee86ffc21315aadffe9b: No such file or directory
cp: testBuildOrg//.git/objects/b1/f5f43e8c05dc0581c47cb7e199cf8bd7c90c64: No such file or directory
cp: testBuildOrg//.git/objects/b1/f959d7d0760ba86bbef41e7a781b5f6fc1fe1d: No such file or directory
cp: testBuildOrg//.git/objects/b1/fb1fc51a610dac136db1c6c9564cf8b2a90a45: No such file or directory
cp: testBuildOrg//.git/objects/b2/62cccdfd619f60e0b623197f9484cd207875c8: No such file or directory
cp: testBuildOrg//.git/objects/b2/6badcf6efb23afc11ac4345473921c91ab2b32: No such file or directory
cp: testBuildOrg//.git/objects/b2/766997eb2f5cf049d82f717e1ef63c5b441c83: No such file or directory
cp: testBuildOrg//.git/objects/b2/76975a6427798109687f90982899ed16fc9b3f: No such file or directory
cp: testBuildOrg//.git/objects/b2/7fd04e3e0dda5ea6872365a8a7345b0c512579: No such file or directory
cp: testBuildOrg//.git/objects/b2/8a87a1acb7f6d84e193e1340556fdd36f64df6: No such file or directory
cp: testBuildOrg//.git/objects/b2/91b2994eec878ff1cbf388f1aa171443cad498: No such file or directory
cp: testBuildOrg//.git/objects/b2/949dffa79a0a6c5ec09350d6af02b7487146cf: No such file or directory
cp: testBuildOrg//.git/objects/b2/a530933df29c68d6fdf4c4d0423118a8862b8b: No such file or directory
cp: testBuildOrg//.git/objects/b2/aabf73fb7a21c79223d8f3e6c87e99f2c316a1: No such file or directory
cp: testBuildOrg//.git/objects/b2/ad914b050cdfea5ffe3861b895617fb13a6fdc: No such file or directory
cp: testBuildOrg//.git/objects/b2/b51ba337cf27757e55b611f673459b32107ad7: No such file or directory
cp: testBuildOrg//.git/objects/b2/ba79feda7e097a2f5d81894715ae25354465a8: No such file or directory
cp: testBuildOrg//.git/objects/b2/c39a00567c2e53d9d6f132787bc1b1c068873f: No such file or directory
cp: testBuildOrg//.git/objects/b2/ccefce24e5fb1ce12eb140a749e4961d2adf0e: No such file or directory
cp: testBuildOrg//.git/objects/b2/d89a87ca975a2995cfbfe032379589d9c78eac: No such file or directory
cp: testBuildOrg//.git/objects/b2/d9356ef4dd217b468b5c95a71adb20497184eb: No such file or directory
cp: testBuildOrg//.git/objects/b2/dfcfc5ba425f1cfc2b3801c5ac423a6cf5baf3: No such file or directory
cp: testBuildOrg//.git/objects/b2/ea4df0b5f45509760cd9dcbb198aa9f666b4f4: No such file or directory
cp: testBuildOrg//.git/objects/b2/f31ec50215d4542704f55c306b7249ecfd70dd: No such file or directory
cp: testBuildOrg//.git/objects/b2/f43f813a151ea3e7ae65885ab21eee7c11b80c: No such file or directory
cp: testBuildOrg//.git/objects/b4/cb41ac208bffc3043f104fa1329bfe5e81da5c: No such file or directory
cp: testBuildOrg//.git/objects/b4/cdf1ccd4b184159736774d42c345af6c97988e: No such file or directory
cp: testBuildOrg//.git/objects/b4/d13510556c7c12a6405d49014238bc0785be5b: No such file or directory
cp: testBuildOrg//.git/objects/b4/d82c43209280259b9e25c737bce748e87eeef1: No such file or directory
cp: testBuildOrg//.git/objects/b4/dcfbbc1182912f0f0f893159663ec201ce1467: No such file or directory
cp: testBuildOrg//.git/objects/b4/deaccfd1605683aff10707fc4238e41b80d1bf: No such file or directory
cp: testBuildOrg//.git/objects/b4/e504091350db2a507bd16710a109f253646b28: No such file or directory
cp: testBuildOrg//.git/objects/b4/e824c2228b7c6b4e6bd3381d1c359af7aa114d: No such file or directory
cp: testBuildOrg//.git/objects/b4/f8d48b8fd69c0df9df696bb7564b7d94aa80aa: No such file or directory
cp: testBuildOrg//.git/objects/b4/fbb76b549dc75a22c8c7836e6f9fd0ced42101: No such file or directory
cp: testBuildOrg//.git/objects/b4/fd11b79f50b63ca0bfe4df96958db9687692a4: No such file or directory
cp: testBuildOrg//.git/objects/b4/fe76df5eb2a68c8a739471fb4977367c7de664: No such file or directory
cp: testBuildOrg//.git/objects/b5/2a31570e0f85695ab6dc0cfacf05f2762a1cfc: No such file or directory
cp: testBuildOrg//.git/objects/b5/34c4d07da1d7ea097cea089b542b942d6749d7: No such file or directory
cp: testBuildOrg//.git/objects/b5/3818b588dbd56d409615c4bdceaa36ba6fcb83: No such file or directory
cp: testBuildOrg//.git/objects/b5/384bb4036223983db590321683cae49927c8b6: No such file or directory
cp: testBuildOrg//.git/objects/b5/38618c270074b8d5af41f95c34240469ce8f70: No such file or directory
cp: testBuildOrg//.git/objects/b5/485d454c0714716ce12af569907a576405ec4e: No such file or directory
cp: testBuildOrg//.git/objects/b5/4b58012aa16b9ab8e363e1b2e9e086ed94fe1d: No such file or directory
cp: testBuildOrg//.git/objects/b5/4edd719f0d4bb94548f606bc10a168c77e6ac8: No such file or directory
cp: testBuildOrg//.git/objects/b5/5af366b1ccda3da3040999a261c62cf123df11: No such file or directory
cp: testBuildOrg//.git/objects/b5/644133f230b5c749b73812ac15c8ef36e9957d: No such file or directory
cp: testBuildOrg//.git/objects/b5/6db8156fabd61f5bb3cbcb96a4b515d462156b: No such file or directory
cp: testBuildOrg//.git/objects/b5/71f02877a97dc3ccedc06b0ce951d4a5e64294: No such file or directory
cp: testBuildOrg//.git/objects/b5/7467ee3a0d289858ae6048d39d7ac25c3db541: No such file or directory
cp: testBuildOrg//.git/objects/b5/7ba20d56a59692103890032e3737dcf7f1f927: No such file or directory
cp: testBuildOrg//.git/objects/b5/7f4b8e967a4c3aba9f83f469aafc44eb9f8de0: No such file or directory
cp: testBuildOrg//.git/objects/b5/86f82eb30ddadc141c07ee54576a6d8926c04e: No such file or directory
cp: testBuildOrg//.git/objects/b5/913090e16417a92fbef6739e44c45639556cb2: No such file or directory
cp: testBuildOrg//.git/objects/b5/933f74cfb5daba3701ee8f1e0edfc9e9ecd619: No such file or directory
cp: testBuildOrg//.git/objects/b5/acad180a2312f50903fc632e5349e9dc7b3cb9: No such file or directory
cp: testBuildOrg//.git/objects/b5/b379c507e4eb89d89f88a6c02fa6b5f80606f9: No such file or directory
cp: testBuildOrg//.git/objects/b5/b3a171a45cfed3559b94da418811f54335b3eb: No such file or directory
cp: testBuildOrg//.git/objects/b5/b6b3df3335367e1cde57d510bb31f1c0757179: No such file or directory
cp: testBuildOrg//.git/objects/b5/b73da554861f751acb4066829a35c157815e0f: No such file or directory
cp: testBuildOrg//.git/objects/b5/c13f6613d8c52804f8faa7eb641edddc0dc6a4: No such file or directory
cp: testBuildOrg//.git/objects/b5/c260165ecfe04842def39dd57fc51ed8fd6e66: No such file or directory
cp: testBuildOrg//.git/objects/b5/c53c2b54bae6ed050dbf9d02d517bfee8ba567: No such file or directory
cp: testBuildOrg//.git/objects/b5/c5e17c91a362a0dbca950874e8b9c8d8f4f172: No such file or directory
cp: testBuildOrg//.git/objects/b5/cd60baf182eb06d9a15bc09b146e2c31f857d3: No such file or directory
cp: testBuildOrg//.git/objects/b5/da7f866170bfd22e9d0dadbba2688ab34e56fd: No such file or directory
cp: testBuildOrg//.git/objects/b5/db08ef32c5f35132b746dea2f8ca8a4a38f85d: No such file or directory
cp: testBuildOrg//.git/objects/b5/deef2ac5610a66cf52de146de68f3cc6a33138: No such file or directory
cp: testBuildOrg//.git/objects/b5/e29d227fb69230cdf4e67bcc3c0f12e737d48c: No such file or directory
cp: testBuildOrg//.git/objects/b5/e588eaa4dda05f7ca0403ac163b4b3f3ea5312: No such file or directory
cp: testBuildOrg//.git/objects/b5/ef734535e3642f56fa87df7d3e79ab97844e7a: No such file or directory
cp: testBuildOrg//.git/objects/b5/f8aef56ec6f6ec9b0d979268ca8414d052e188: No such file or directory
cp: testBuildOrg//.git/objects/b5/fce9aa1826e9eaa10b3261885001adfacc2afb: No such file or directory
cp: testBuildOrg//.git/objects/b8/d20aa8eaa9091a6891e65a49e12ae7cfdaee73: No such file or directory
cp: testBuildOrg//.git/objects/b8/ed845d6144f5f2edc645044cfb60a3c18b14f2: No such file or directory
cp: testBuildOrg//.git/objects/b8/f1913f739f23e802ef943707592f6b9ef331a8: No such file or directory
cp: testBuildOrg//.git/objects/b8/fef24b7082fe0d2a4fbb27763593dad0e842f5: No such file or directory
cp: testBuildOrg//.git/objects/b8/ff39ac18611fc5bab10137af7adc20e02b58ce: No such file or directory
cp: testBuildOrg//.git/objects/b9/1f5a4672351f8887b2777123313da3330e5fa7: No such file or directory
cp: testBuildOrg//.git/objects/b9/2179b324d24740190e5b737aa7ef0030bd382a: No such file or directory
cp: testBuildOrg//.git/objects/b9/277dce4ed1fc57492a232ae504bd585acb61a3: No such file or directory
cp: testBuildOrg//.git/objects/b9/36de9f5dd0bc43609c4f68fbf87bed5ba61ebe: No such file or directory
cp: testBuildOrg//.git/objects/b9/3a0b39a5bc4fcb884808a88eda2d5fb50be905: No such file or directory
cp: testBuildOrg//.git/objects/b9/3f04cc5433fbb1e0a8d4762ee470cdf615be5c: No such file or directory
cp: testBuildOrg//.git/objects/b9/4053c5b3078f3aa7a91c2fff6056cdff88572d: No such file or directory
cp: testBuildOrg//.git/objects/b9/4277ff5efd2ad07d581c73e01eeddbb4c0a845: No such file or directory
cp: testBuildOrg//.git/objects/b9/43a3bbc8730c32e98a821f2033c58e3fca097c: No such file or directory
cp: testBuildOrg//.git/objects/b9/5b109eb489eec3916dbdcf4810571336ead26b: No such file or directory
cp: testBuildOrg//.git/objects/b9/5cb18d0435c9d450a3eaf35141c60f82c19934: No such file or directory
cp: testBuildOrg//.git/objects/b9/5e74fd31544a5c042e3b160249d474c6c622b1: No such file or directory
cp: testBuildOrg//.git/objects/b9/60a834b5e2ab4b2565556210d232274d537e95: No such file or directory
cp: testBuildOrg//.git/objects/b9/61b04cc40fe40175a15c76fc998bd7ac05f22a: No such file or directory
cp: testBuildOrg//.git/objects/b9/62cf1116454eb1db9fd2c0ad1bc1dd8ab50a71: No such file or directory
cp: testBuildOrg//.git/objects/b9/680a2a66371dc6deb704da3e4df3f30a569bdb: No such file or directory
cp: testBuildOrg//.git/objects/b9/6905db1aecb5e786c574471ee65dd03a91632d: No such file or directory
cp: testBuildOrg//.git/objects/b9/6a594edc0a7a07381493fc80007aa8de554c1c: No such file or directory
cp: testBuildOrg//.git/objects/b9/6db1684fc663a743a938d117f155d3df39fbf2: No such file or directory
cp: testBuildOrg//.git/objects/b9/6f6a10a50e26e925090d842a98b9d6540b1678: No such file or directory
cp: testBuildOrg//.git/objects/b9/71c412e7d0b71f87b6bd2ab71f95542ea419ae: No such file or directory
cp: testBuildOrg//.git/objects/b9/77fd98b3f5aa7b10e99d28f1d66493931be20d: No such file or directory
cp: testBuildOrg//.git/objects/b9/7a0427b95dba05e7660e558c968a36f16a4bc1: No such file or directory
cp: testBuildOrg//.git/objects/b9/7d15fcb35987afbf9f57726064fa6a61d8eaf1: No such file or directory
cp: testBuildOrg//.git/objects/b9/87f4bddf06b11d439e74310d5205a5c4dfe169: No such file or directory
cp: testBuildOrg//.git/objects/b9/8a01a4d1adfcd70968d6f5847d90215c0cef27: No such file or directory
cp: testBuildOrg//.git/objects/b9/8b65e247b7b142d32d42bd6832fc4eb125f206: No such file or directory
cp: testBuildOrg//.git/objects/b9/8f367a284ffe66655d70cea16152b385e89395: No such file or directory
cp: testBuildOrg//.git/objects/b9/a278e8c381469408a5a7eb28d0ba3b967977bd: No such file or directory
cp: testBuildOrg//.git/objects/b9/c338016e07a6bfd058ee069181961eca489268: No such file or directory
cp: testBuildOrg//.git/objects/b9/cbd3830ef2e4864403a9946b0c3bf447ac84e8: No such file or directory
cp: testBuildOrg//.git/objects/b9/d819c8f4ec6d240f2e0cda4d294ae18622c563: No such file or directory
cp: testBuildOrg//.git/objects/b9/d86523b12a383b9583388c1c059e465227817e: No such file or directory
cp: testBuildOrg//.git/objects/b9/dab625f5110803ac05855c1b2d1d33587e8a77: No such file or directory
cp: testBuildOrg//.git/objects/b9/dcf8a0d14e2ef54b43180b84826543c1725337: No such file or directory
cp: testBuildOrg//.git/objects/b9/df64211c6b6c4bce9b467fbe6759023f2c9fe2: No such file or directory
cp: testBuildOrg//.git/objects/b9/e3f09a0976acaaf402bf30e647036764c3e4c5: No such file or directory
cp: testBuildOrg//.git/objects/b9/e5c59e3cba6c45467d65eb606329d2114c8e18: No such file or directory
cp: testBuildOrg//.git/objects/b9/ea373db91bb2a5c0e0bcc6967a16380dbdf21b: No such file or directory
cp: testBuildOrg//.git/objects/b9/ec7d76913c7fc572ec8cdaae20338bd6d5fb84: No such file or directory
cp: testBuildOrg//.git/objects/b9/f5b8528e98ab8cbe332b4bc78af47f9bc076e1: No such file or directory
cp: testBuildOrg//.git/objects/bc: No such file or directory
cp: testBuildOrg//.git/objects/bd/26e74bd43c667906ea58a563dc8f3d06771842: No such file or directory
cp: testBuildOrg//.git/objects/bd/27a4e2349f831c15bde022ae41498284a6ede6: No such file or directory
cp: testBuildOrg//.git/objects/bd/2aa46b7bf2abc23483c52bf34a2c005374980e: No such file or directory
cp: testBuildOrg//.git/objects/bd/30ffbb41e3885d05b934f88d59e5fb8048ca51: No such file or directory
cp: testBuildOrg//.git/objects/bd/32b8b06bb13be136e42f9e3aebc3a6405d50e6: No such file or directory
cp: testBuildOrg//.git/objects/bd/352f6f250f48129191cb8e3043c6abd477ad69: No such file or directory
cp: testBuildOrg//.git/objects/bd/37bd79d9e41924b66a5971cb3d40c4ffeac7a2: No such file or directory
cp: testBuildOrg//.git/objects/bd/3a48eebc7098bb1e94943f76ac29fe2fc8f5e2: No such file or directory
cp: testBuildOrg//.git/objects/bd/43bb6b19ee7f51ea034ed0f13b679910b17bf8: No such file or directory
cp: testBuildOrg//.git/objects/bd/470a48a844a4c9da1a7587414f1b2c72795deb: No such file or directory
cp: testBuildOrg//.git/objects/bd/481b95b29e2d7bca1d892375632dc4dfc43a9a: No such file or directory
cp: testBuildOrg//.git/objects/bd/4e809ae3b52ff3d2eb18db0303a9d89b0d9c09: No such file or directory
cp: testBuildOrg//.git/objects/bd/573a26d7fab32cc39a6e07ea517b00387efea8: No such file or directory
cp: testBuildOrg//.git/objects/bd/60c68026f755a815d2cdbedcb83e683fda2a2e: No such file or directory
cp: testBuildOrg//.git/objects/bd/6149bb5946e3ead63ec88a0fa2bec1894708a0: No such file or directory
cp: testBuildOrg//.git/objects/bd/61f6cffa3414d07e2e82c3664ad2225a336be6: No such file or directory
cp: testBuildOrg//.git/objects/bd/64162a6c8e483b460eaccf38f6ea4c4e255563: No such file or directory
cp: testBuildOrg//.git/objects/bd/667c965d914d3bc73542933d0ed617d29104d5: No such file or directory
cp: testBuildOrg//.git/objects/bd/68ec9b3c40a860816878872dd08ba9f2bcd111: No such file or directory
cp: testBuildOrg//.git/objects/bd/6dd81d82c91353e7db8868eff3c9b90710e688: No such file or directory
cp: testBuildOrg//.git/objects/bd/7af432f057889a8b6586b8aaec89e6763c9fff: No such file or directory
cp: testBuildOrg//.git/objects/bd/8cadd20c78a20dee3e986032b9d38bbe2e8cfe: No such file or directory
cp: testBuildOrg//.git/objects/bd/9008d33ddd01d837937334e9a59a8c960f12af: No such file or directory
cp: testBuildOrg//.git/objects/bd/923507bc42fe88b827dd166075932d2540fd42: No such file or directory
cp: testBuildOrg//.git/objects/bd/96554551a84db581020fdf05860124dfb5819f: No such file or directory
cp: testBuildOrg//.git/objects/bd/97462c4bc2b410867e49940004beebee1f88a6: No such file or directory
cp: testBuildOrg//.git/objects/bd/998475700afdb46f6785c9a96340bfc7839745: No such file or directory
cp: testBuildOrg//.git/objects/bd/9a5021d4e7102cd0306a6a2f66111aa29b7e01: No such file or directory
cp: testBuildOrg//.git/objects/bd/a6e710158080f0af894de917d42b429785362a: No such file or directory
cp: testBuildOrg//.git/objects/bd/a79c8eefba8532230711bc8f3939e17b91b11c: No such file or directory
cp: testBuildOrg//.git/objects/bd/b2abd5c0ece73985f09da912e672b385710c32: No such file or directory
cp: testBuildOrg//.git/objects/bd/b5ce761c6cb4de82090fd56d423a1bc9f7cd05: No such file or directory
cp: testBuildOrg//.git/objects/bd/ca1365ab886c1ff9975cb5d7dd2cc96bba88b4: No such file or directory
cp: testBuildOrg//.git/objects/bd/e2cd50dccb50e241fd619cc11f8a083e05065e: No such file or directory
cp: testBuildOrg//.git/objects/bd/e5937519cfbb2cedba12be19ffd8b0bd1ff819: No such file or directory
cp: testBuildOrg//.git/objects/bd/f838f334aa34a719a6e2b3c277600805944af4: No such file or directory
cp: testBuildOrg//.git/objects/c0/a9a5c266b1d4feb4d9276167ec32fbc3a01035: No such file or directory
cp: testBuildOrg//.git/objects/c0/af2b6e2c80e01c3a66fe67279e82b57b947579: No such file or directory
cp: testBuildOrg//.git/objects/c0/afff9a5a5d2dae66d52f89b73aa1c19ab57308: No such file or directory
cp: testBuildOrg//.git/objects/c0/b31376020f6d34df3675180a89c1b5e8e90135: No such file or directory
cp: testBuildOrg//.git/objects/c0/bcde1c97e56978cda2b060aa57b608bd84cc63: No such file or directory
cp: testBuildOrg//.git/objects/c0/c0acf2c00716a2f471ed76a3c7cd7dfb1e2f72: No such file or directory
cp: testBuildOrg//.git/objects/c0/c95ccdaa9242a196b7e265d456144bed2c5f81: No such file or directory
cp: testBuildOrg//.git/objects/c0/cf08e4a08e16b20352ea3f81b89fb78a31ffa2: No such file or directory
cp: testBuildOrg//.git/objects/c0/cfda5fa83935ce7425550621bfa0abf2a7ec43: No such file or directory
cp: testBuildOrg//.git/objects/c0/d1cbaa2f69f6401a3646f07888a1e5870a9b62: No such file or directory
cp: testBuildOrg//.git/objects/c0/db81b7080ae50ba1eff8472ab0ab7031bd8597: No such file or directory
cp: testBuildOrg//.git/objects/c0/f6ec21dbb48133ef23be5f15024e5e02b701c2: No such file or directory
cp: testBuildOrg//.git/objects/c0/f7474e3c2f7d63a8fc381b8ecda3ef2ba5dfa1: No such file or directory
cp: testBuildOrg//.git/objects/c0/fcaf3fe36db3e42dba3fa2e89e89fc4a6dfec4: No such file or directory
cp: testBuildOrg//.git/objects/c1/c172d42b21f02014c5d8e8d121b3e1959fdcdd: No such file or directory
cp: testBuildOrg//.git/objects/c1/c65d467609369f7b47494528d8843599a7a752: No such file or directory
cp: testBuildOrg//.git/objects/c1/c7ecc31df3e0e864d1b2f6431c0f3ab5b9ac19: No such file or directory
cp: testBuildOrg//.git/objects/c1/d1007f6d9fc8622e7ab434b2720a42fe3a43cc: No such file or directory
cp: testBuildOrg//.git/objects/c1/e201075fe5c7565e7914cc5cc92393d09779bf: No such file or directory
cp: testBuildOrg//.git/objects/c1/e6f5edf21a7cec36bb8744cc3fc6cda031e10a: No such file or directory
cp: testBuildOrg//.git/objects/c1/e9930b97bb3a7cfa2a0ee44fcbcee4f2c33c19: No such file or directory
cp: testBuildOrg//.git/objects/c1/f1271d3995688e1b2d40b0f92e854373519769: No such file or directory
cp: testBuildOrg//.git/objects/c2/5750eaa2be5910eee98b0fd7fadc183159cba2: No such file or directory
cp: testBuildOrg//.git/objects/c2/5a5bd6cc49538d6b5ba4965635811072426ffb: No such file or directory
cp: testBuildOrg//.git/objects/c2/689ed84f67b73a74c734b9326b64096ea9a730: No such file or directory
cp: testBuildOrg//.git/objects/c2/6a9ef372af30d6a63d0dc797d7a7750a25d12f: No such file or directory
cp: testBuildOrg//.git/objects/c2/7a0025366084cb8af4e2aadabec4ae0b7a27ed: No such file or directory
cp: testBuildOrg//.git/objects/c2/7da76ad94ec0091ac8f7dbede53937aaa28714: No such file or directory
cp: testBuildOrg//.git/objects/c2/87417d77d401fc6f86e8647e7caa72964fc4da: No such file or directory
cp: testBuildOrg//.git/objects/c2/89374ff5a55829d22a4a436912d9aba3bb9774: No such file or directory
cp: testBuildOrg//.git/objects/c2/8cc77debae00a5508723fad86a0ab8fef59ec3: No such file or directory
cp: testBuildOrg//.git/objects/c2/9d5b7bbf00e551d0ffc5b6067420856ea9f7c5: No such file or directory
cp: testBuildOrg//.git/objects/c2/a0f24815e1375ed94e7262cede9e98373e9b2f: No such file or directory
cp: testBuildOrg//.git/objects/c2/a5d785bc8d9bdf0e912da6b74ce6ea1409290f: No such file or directory
cp: testBuildOrg//.git/objects/c2/b0691f9faaf7c732498cf4f7b9b25373931ed6: No such file or directory
cp: testBuildOrg//.git/objects/c2/bdc3f5c2504ac58d1190cec85dbc64c9b3d8a4: No such file or directory
cp: testBuildOrg//.git/objects/c2/cd782f85fc0729291350e729d5571256b33bcc: No such file or directory
cp: testBuildOrg//.git/objects/c2/cec26e5c98154136a898faa5906be6a40b10d8: No such file or directory
cp: testBuildOrg//.git/objects/c2/d363d85ad96b6bad558b450d9755adc332e63e: No such file or directory
cp: testBuildOrg//.git/objects/c2/ddc841e714351241e373ad35dac5c9ca143bcf: No such file or directory
cp: testBuildOrg//.git/objects/c2/f4c8d3cc872fc5b2ff8317fc2b3c96a9283ee0: No such file or directory
cp: testBuildOrg//.git/objects/c2/f88c8f809567bc03b71c83a11cffdafeaeb079: No such file or directory
cp: testBuildOrg//.git/objects/c2/fa0447e996c053e79eb42eda87422e084a5f67: No such file or directory
cp: testBuildOrg//.git/objects/c6/e9414e0d7352f69db4215dbda3ae6b63a19527: No such file or directory
cp: testBuildOrg//.git/objects/c6/eb4ee94b5fe4d567fae11f5627be3b39392e5b: No such file or directory
cp: testBuildOrg//.git/objects/c6/f7a00b10bb6782303d2a1637fc34f3babb5864: No such file or directory
cp: testBuildOrg//.git/objects/c6/f9a6b727036a2358a47f9f41b5bdb3a983f7c1: No such file or directory
cp: testBuildOrg//.git/objects/c7/7d04ee033c413e9153be915bcd15fa2f8286e1: No such file or directory
cp: testBuildOrg//.git/objects/c7/7f121f2f14cc2710bf166914cdd58ecc9faa9a: No such file or directory
cp: testBuildOrg//.git/objects/c7/83a88c0eae3b49779b7e747d1820e5176df6c5: No such file or directory
cp: testBuildOrg//.git/objects/c7/87c966173389e161e6c35cfb8e6c47e92ce49a: No such file or directory
cp: testBuildOrg//.git/objects/c7/8bfa8b769a062426f825cec6c414120ef70e3c: No such file or directory
cp: testBuildOrg//.git/objects/c7/8d5ad076e2f3ccf0acd6e9edde797cd3b288b2: No such file or directory
cp: testBuildOrg//.git/objects/c7/8f94b49d2cb2e19696a973057aa5550932a729: No such file or directory
cp: testBuildOrg//.git/objects/c7/914f376854402d9217434ff72df76e4ab92812: No such file or directory
cp: testBuildOrg//.git/objects/c7/998a3267d9e9622d597d0956cc27aef6920702: No such file or directory
cp: testBuildOrg//.git/objects/c7/9a5ddc85a099057693fc735532ea065630b528: No such file or directory
cp: testBuildOrg//.git/objects/c7/ac76917fbc3211165d6b82061f807d931e6e3f: No such file or directory
cp: testBuildOrg//.git/objects/c7/ac8a68d32d6d93452a418249dcf094025594c1: No such file or directory
cp: testBuildOrg//.git/objects/c7/b35d9c8c47608ea8f9d63f44b3de877707fe2f: No such file or directory
cp: testBuildOrg//.git/objects/c7/b67a5f8fc329c871f36619cca009ebc09be6d9: No such file or directory
cp: testBuildOrg//.git/objects/c7/c8fb39b7b707d8bddc8dc1fb84fe4a1f970f97: No such file or directory
cp: testBuildOrg//.git/objects/c7/cd84264dd872ce79f5be461b38e15a59916d89: No such file or directory
cp: testBuildOrg//.git/objects/c7/d3ed6e015ae9eeaf7ab5a51804bfa04f40f1f4: No such file or directory
cp: testBuildOrg//.git/objects/c7/db3be973f1a532b5b463e4bcc31e91b35ec91b: No such file or directory
cp: testBuildOrg//.git/objects/c7/ea3675f788a42b293dc5977f20a672e8d0408c: No such file or directory
cp: testBuildOrg//.git/objects/c7/ea3c21a6c83665c844cb74a79b8d37da9cadd6: No such file or directory
cp: testBuildOrg//.git/objects/c8/86730c873e4a0c5ab131f163850b09e2596516: No such file or directory
cp: testBuildOrg//.git/objects/c8/8a4a892c58fd2f4f61cb93a1fda2ae23ce8810: No such file or directory
cp: testBuildOrg//.git/objects/c8/8c3edfe7f4c6857edca32e041f4d21909dfb58: No such file or directory
cp: testBuildOrg//.git/objects/c8/9299b80c60e0d3a8db8d0c2c4a813b20581a01: No such file or directory
cp: testBuildOrg//.git/objects/c8/958070f5c32af148bfce2160d0e9ea67d65782: No such file or directory
cp: testBuildOrg//.git/objects/c8/a113450dea24fe5e4e480777624c127a165481: No such file or directory
cp: testBuildOrg//.git/objects/c8/a96a92260e2e20e5611f7156f5274d88fe2200: No such file or directory
cp: testBuildOrg//.git/objects/c8/acf0808c7774562d99ac30619d5f70a6562c7d: No such file or directory
cp: testBuildOrg//.git/objects/c8/ad2e96c6eadcceee13c59ec37fc7f368649d73: No such file or directory
cp: testBuildOrg//.git/objects/c8/bfd5fa0b2c3673e1f3f0a0a0352dd7ca994a9b: No such file or directory
cp: testBuildOrg//.git/objects/c8/c8bd4b2b5d877d4bc8229c443f93d7e5571c98: No such file or directory
cp: testBuildOrg//.git/objects/c8/c999853a1c14f2d2eb58630db4d59c923a0602: No such file or directory
cp: testBuildOrg//.git/objects/c8/cc7f11be5633934b9f4939241ae0a7b3a6806b: No such file or directory
cp: testBuildOrg//.git/objects/c8/cd6102e3d0ba029211cdd0a0d82eb0d6f65edd: No such file or directory
cp: testBuildOrg//.git/objects/c8/d73d02f28d83435b668a04930209f0de0c929d: No such file or directory
cp: testBuildOrg//.git/objects/c8/d9420db7fcebd371eaec8a76f4faf87192950a: No such file or directory
cp: testBuildOrg//.git/objects/c8/de7c07fa95cdcaf362a1ea1601fa0814dc77d3: No such file or directory
cp: testBuildOrg//.git/objects/c8/e75e6ccac362ffbfbee824f0795c156ca78495: No such file or directory
cp: testBuildOrg//.git/objects/c8/ea55bbcf3f5eec471261b829ec82fdcec1d4f9: No such file or directory
cp: testBuildOrg//.git/objects/ca/85a1f0af98bc068337c4b0e1d05706a2d4b2b1: No such file or directory
cp: testBuildOrg//.git/objects/ca/88b57164451b24e7e76a2903780293e45dafd5: No such file or directory
cp: testBuildOrg//.git/objects/ca/8975220dc09912b03ce873b59146d4547a265b: No such file or directory
cp: testBuildOrg//.git/objects/ca/8be2efcfd96e7e0ed7e4572a52438324a1ac26: No such file or directory
cp: testBuildOrg//.git/objects/ca/8c43b8da8ecdd4992ef0af90f195453d61b9e8: No such file or directory
cp: testBuildOrg//.git/objects/ca/908a3677d80a9cab49a6c7b6aff4732a35fd38: No such file or directory
cp: testBuildOrg//.git/objects/ca/995a29c171b8673609da970d88df75c97108f7: No such file or directory
cp: testBuildOrg//.git/objects/ca/a41c8734572649e1ca64523c8359d96d7adb48: No such file or directory
cp: testBuildOrg//.git/objects/ca/ac25d1b4a9d6cd98d0a12571846f1c88e5da8c: No such file or directory
cp: testBuildOrg//.git/objects/ca/b051198fc092323d07d9ed2d9aca1b86d220fa: No such file or directory
cp: testBuildOrg//.git/objects/ca/c8ea6f4f5b741055bb5e3e6f8ea34f7555b5b8: No such file or directory
cp: testBuildOrg//.git/objects/ca/cde16eaa4ab2aafc0b68349c604420964783f2: No such file or directory
cp: testBuildOrg//.git/objects/ca/ce7afa92385dd3bc5202e31fd11a326774b5b3: No such file or directory
cp: testBuildOrg//.git/objects/ca/d625bda5868f1cd01e48c6407d4961bd3d1d84: No such file or directory
cp: testBuildOrg//.git/objects/ca/e17694177f33b655290a34538f427777b1d0bb: No such file or directory
cp: testBuildOrg//.git/objects/ca/ebe960ab48f47136731c0894067040ff69e1e3: No such file or directory
cp: testBuildOrg//.git/objects/ca/edc11864deb72e0d27a54562bd79d0da7f23f1: No such file or directory
cp: testBuildOrg//.git/objects/ca/fb2912cfdcc273c09e37ee75d097fcabbb5c0d: No such file or directory
cp: testBuildOrg//.git/objects/ca/fe2db8be6cfe9838dd65010f218bfc4e5c1309: No such file or directory
cp: testBuildOrg//.git/objects/ca/ffd7b7ea902156cb40c67472cd4d8d6675a9c9: No such file or directory
cp: testBuildOrg//.git/objects/cc/3261387a3fc97ca4da851e84d2c27757555ef7: No such file or directory
cp: testBuildOrg//.git/objects/cc/3669dcffe7c50f730bbaab962dc828c3c61c7d: No such file or directory
cp: testBuildOrg//.git/objects/cc/4140ecf3bf560a0bb4e862c43160ac170c7532: No such file or directory
cp: testBuildOrg//.git/objects/cc/42a230162ca949defe4b838093cc6cf639e5a6: No such file or directory
cp: testBuildOrg//.git/objects/cc/4ec5d3a9b58c5c488fbbd94cce64cb1c764670: No such file or directory
cp: testBuildOrg//.git/objects/cc/55cc1ec0779189ba85c6eea214cdabd99c002d: No such file or directory
cp: testBuildOrg//.git/objects/cc/604f37b9b30dde38f02c37e875980e277f1dcc: No such file or directory
cp: testBuildOrg//.git/objects/cc/6513d830155facc2c81b6724abce8fd5eb9a34: No such file or directory
cp: testBuildOrg//.git/objects/cc/67289c5f946c0ccc6bda5280f2a3abf48d41eb: No such file or directory
cp: testBuildOrg//.git/objects/cc/6a793ef1a7a55d7f82906faf9dab936cbbf514: No such file or directory
cp: testBuildOrg//.git/objects/cc/6aa0dc43e698801b305e5c94ea16f039db2409: No such file or directory
cp: testBuildOrg//.git/objects/cc/770aa83a11d607bbf3395ebcfde21d382934bd: No such file or directory
cp: testBuildOrg//.git/objects/cc/7b821f3222374cfbf8c8ab581e294dc59e70d8: No such file or directory
cp: testBuildOrg//.git/objects/cc/7c8ceaa772089f2bb968a49dda32c89e9e7ecb: No such file or directory
cp: testBuildOrg//.git/objects/cc/7e9b87851776cb979183db98636e064935a8c4: No such file or directory
cp: testBuildOrg//.git/objects/cc/8f6052f1cb454dd9f54ed9c620c64214e28d8b: No such file or directory
cp: testBuildOrg//.git/objects/cc/962b1dc89d7f6cbef8a0f5c027079c14de0dc1: No such file or directory
cp: testBuildOrg//.git/objects/cc/9b38411aa5b3752182770e3bd6c45cfc05f02c: No such file or directory
cp: testBuildOrg//.git/objects/cc/9d7b2a6987757977b0e7ef91678d55f24f896d: No such file or directory
cp: testBuildOrg//.git/objects/cc/9da0fd3c737b0535d8ca7747247a73d54d04de: No such file or directory
cp: testBuildOrg//.git/objects/cc/9f37217483d2d84f6b8a7a700a56e520896cb6: No such file or directory
cp: testBuildOrg//.git/objects/cc/9fe0dd57fa120332489f5aa46be7faf762e2f9: No such file or directory
cp: testBuildOrg//.git/objects/cc/a52e2e7599dfb9baa80b1d8fabdb11a641919f: No such file or directory
cp: testBuildOrg//.git/objects/cc/a5a6610523eefb2fe8f2d434a2e089eba05549: No such file or directory
cp: testBuildOrg//.git/objects/cc/b742decf4443d72ac06a53ab27cf9230551eaa: No such file or directory
cp: testBuildOrg//.git/objects/cc/c405a7bb9fa9eba39a47eeaa228e5340192c26: No such file or directory
cp: testBuildOrg//.git/objects/cc/cff9e085d326d7827185b696838fa6a25c7a08: No such file or directory
cp: testBuildOrg//.git/objects/cc/dbb6ab28594b80f0e838bcc0d561cf9a7adefd: No such file or directory
cp: testBuildOrg//.git/objects/cc/e0a48091f05d1299864a3aaa22ea6c6bfed914: No such file or directory
cp: testBuildOrg//.git/objects/cc/e13e109cab4735167ad715e7aa618a62bce750: No such file or directory
cp: testBuildOrg//.git/objects/cc/e9bb5c5acb4911c487cd1ecf35457e0bed3b0a: No such file or directory
cp: testBuildOrg//.git/objects/cc/ea4af3571d2ca74ff865241918a4ae5852adb1: No such file or directory
cp: testBuildOrg//.git/objects/cc/ef2b7cf313c715490ad0f7db96824499eb2191: No such file or directory
cp: testBuildOrg//.git/objects/cc/f452a609a30248573a3da4f34359d15dc395d2: No such file or directory
cp: testBuildOrg//.git/objects/cc/fe79c014bf75cef3763be9fa487c022f8e8b64: No such file or directory
cp: testBuildOrg//.git/objects/cc/ffe02ec38f3f054c338cba754ef73cfd2385ee: No such file or directory
cp: testBuildOrg//.git/objects/cd/8ca127f79922454b77e917e5d166c8eb95ea8f: No such file or directory
cp: testBuildOrg//.git/objects/cd/94afdbc549bf92a4426eaacd75160be4cdf8f0: No such file or directory
cp: testBuildOrg//.git/objects/cd/9971886b67511e8a3a336387b14ba652eac970: No such file or directory
cp: testBuildOrg//.git/objects/cd/9bfc29870b98de4581c14b710a379867c2acb2: No such file or directory
cp: testBuildOrg//.git/objects/cd/a230106407df78b24b95583af0c7d13d2f062c: No such file or directory
cp: testBuildOrg//.git/objects/cd/a71f6b53e9ee0b2bc20778df019d9f012cec2e: No such file or directory
cp: testBuildOrg//.git/objects/cd/b217513fc1132a1a4caae64a6655297d649575: No such file or directory
cp: testBuildOrg//.git/objects/cd/b661e9a7b2f6d7f4882e6f0279fb4ad4da440e: No such file or directory
cp: testBuildOrg//.git/objects/cd/c7d90a1699659fb0e06d7685bd9cf55732adf8: No such file or directory
cp: testBuildOrg//.git/objects/cd/c8e1ed735ab1838b9721ef86f1c96f9dcf1ec7: No such file or directory
cp: testBuildOrg//.git/objects/cd/c9b4e37ad314ae55650f59e4931e0a3c8ea0b5: No such file or directory
cp: testBuildOrg//.git/objects/cd/d07e8e88fbec52b6ef469b79ced2a59485e278: No such file or directory
cp: testBuildOrg//.git/objects/cd/d2a67c821d35853716a186a7de56c48cc88833: No such file or directory
cp: testBuildOrg//.git/objects/cd/d87ac44f13a24e9dd2ba240a1b584b5b9ee2ae: No such file or directory
cp: testBuildOrg//.git/objects/cd/dbc8a11b6b3d0507db6f004b97659359d840b8: No such file or directory
cp: testBuildOrg//.git/objects/cd/e82d18fe1f433b55230baec269ead9f89c120c: No such file or directory
cp: testBuildOrg//.git/objects/cd/e8cd1b6e9802dc8bcd596b19361d0739ea5d8d: No such file or directory
cp: testBuildOrg//.git/objects/cd/ecc480a0c92e1732448f6550ed79823bb9f449: No such file or directory
cp: testBuildOrg//.git/objects/cd/f3f1e2a295b441052152ed2e0787afe819e4e2: No such file or directory
cp: testBuildOrg//.git/objects/cd/fb1bd444f9335a6c40396a6ea1a8d62ab889b9: No such file or directory
cp: testBuildOrg//.git/objects/d0/85ed652bc43aaf64a7109500449cb0c5dfdee1: No such file or directory
cp: testBuildOrg//.git/objects/d0/961c97d12639f97b355b2a8c3fd11b1cdfa347: No such file or directory
cp: testBuildOrg//.git/objects/d0/a228975fe79b2fd7361917d090542ea5d4d8f4: No such file or directory
cp: testBuildOrg//.git/objects/d0/a8ed3477480b2c2ace6ff208caccc2ce6a57ff: No such file or directory
cp: testBuildOrg//.git/objects/d0/aa29c92d34c046191d6477dd3f95cc5ba0d421: No such file or directory
cp: testBuildOrg//.git/objects/d0/b139b054e672861fe70068b695b58b18a59a3d: No such file or directory
cp: testBuildOrg//.git/objects/d0/b2155d64a5dc8b0b455338eed7b7d710e5e777: No such file or directory
cp: testBuildOrg//.git/objects/d0/b27a289e3ccbc5d0c88ee1330e8fcfd7444c6a: No such file or directory
cp: testBuildOrg//.git/objects/d0/b9f4f8c7d5cdad0a6fc32e51bc0592e4541831: No such file or directory
cp: testBuildOrg//.git/objects/d0/bf8d416edc08eee13145b116a65a2e1b9e67bb: No such file or directory
cp: testBuildOrg//.git/objects/d0/c53480f7fd2c4ce32d6090dbbdedbb1bbb2b58: No such file or directory
cp: testBuildOrg//.git/objects/d0/c6cb69192c1b94a2d5c1bd6341198f92a055f1: No such file or directory
cp: testBuildOrg//.git/objects/d0/c8fe05bd05e2d9ab195f71001ab298d9d15108: No such file or directory
cp: testBuildOrg//.git/objects/d0/caa45b77e1ca4bbd741b8ec7189d3371d84f02: No such file or directory
cp: testBuildOrg//.git/objects/d0/d1dbafc55789a1be318a48986d7df8ad37e892: No such file or directory
cp: testBuildOrg//.git/objects/d0/d409da523500ae2d6490f698b06dfff1374e30: No such file or directory
cp: testBuildOrg//.git/objects/d0/df85f55192329ed7458f896c6fa0cb34b0093f: No such file or directory
cp: testBuildOrg//.git/objects/d0/e0fc3d865dee75f4f9ff09f23579ad6534f6a6: No such file or directory
cp: testBuildOrg//.git/objects/d0/ec5cf09735418e52e6fad05bd09f7683411d4b: No such file or directory
cp: testBuildOrg//.git/objects/d0/f5fbf3edd8227f316e016033e6a6dd006ea3ca: No such file or directory
cp: testBuildOrg//.git/objects/d2/f03460e4c0bc92a8f436d1f2f8197598d90f25: No such file or directory
cp: testBuildOrg//.git/objects/d2/f1e25a5f7a819f30ff043a46d2c56da5c46491: No such file or directory
cp: testBuildOrg//.git/objects/d2/f720e1e98e115919401c622930fae967fe9d41: No such file or directory
cp: testBuildOrg//.git/objects/d3/584ead34d52d7aea3ff7b4a35a242f2d12acf1: No such file or directory
cp: testBuildOrg//.git/objects/d3/5862c3f6b680fc49e854ae1d469d96b2988d1e: No such file or directory
cp: testBuildOrg//.git/objects/d3/67ff83e2d7e3a84ede4959a8d755c8378ab51f: No such file or directory
cp: testBuildOrg//.git/objects/d3/683045e8aac28bfa6434c1132b0384e847ebb9: No such file or directory
cp: testBuildOrg//.git/objects/d3/6b81d575c294e3070968527a2e2bcdfa8b8180: No such file or directory
cp: testBuildOrg//.git/objects/d3/7c3ccaf39ee44000294736ffcda549a62b21a0: No such file or directory
cp: testBuildOrg//.git/objects/d3/7c8951f1245436114c2b06ab0f059463a84b2a: No such file or directory
cp: testBuildOrg//.git/objects/d3/7e5f04ffa8988693d8bbc29fc89c7abf9001a0: No such file or directory
cp: testBuildOrg//.git/objects/d3/7f81ddbc89899f9ee7c3fca7b58cb56ce7a464: No such file or directory
cp: testBuildOrg//.git/objects/d3/8acf52b2b208f283a25f86ea129b19d18c94bb: No such file or directory
cp: testBuildOrg//.git/objects/d3/8c28914046c7630a3371def865e2f1dce8115f: No such file or directory
cp: testBuildOrg//.git/objects/d3/9b56691f7d3dfdd96028b870aa4ac030bef440: No such file or directory
cp: testBuildOrg//.git/objects/d3/9db2cd1e3538378b95e500fb91b9d523043874: No such file or directory
cp: testBuildOrg//.git/objects/d3/a2e669a64ca5fea712d7e6d3e8bf4e0ee3b31b: No such file or directory
cp: testBuildOrg//.git/objects/d3/a5bacf99dabd992d7e1887587981f98fe8be87: No such file or directory
cp: testBuildOrg//.git/objects/d3/ab385599034125be25fe56acd6073efdb5d44e: No such file or directory
cp: testBuildOrg//.git/objects/d3/ae972944773dfd916540ee8c93403e4ff83dec: No such file or directory
cp: testBuildOrg//.git/objects/d3/af4e054307c6f5e27468ea0565f36655c2a8bd: No such file or directory
cp: testBuildOrg//.git/objects/d3/b6e7bc048707b25ccb9584f27931fde819d22d: No such file or directory
cp: testBuildOrg//.git/objects/d3/b8d6186ce24668c2ea453a7121b078c8644921: No such file or directory
cp: testBuildOrg//.git/objects/d3/c5b5051e2b02662eed7dda6836dce2a5977d7a: No such file or directory
cp: testBuildOrg//.git/objects/d3/cc455e95d42ce4a3463f521a99c914b064719b: No such file or directory
cp: testBuildOrg//.git/objects/d3/dc9dace894d50122cb3c536633a465b01be757: No such file or directory
cp: testBuildOrg//.git/objects/d3/e4a8f5115523a25eab632637efb02e2e5074f8: No such file or directory
cp: testBuildOrg//.git/objects/d3/e82d01ec9cac437547d2443ec399e65ce789c9: No such file or directory
cp: testBuildOrg//.git/objects/d3/ea6cd4efbedfb4e17794b03ca09c3610b350f5: No such file or directory
cp: testBuildOrg//.git/objects/d3/eb4ff62326c42fba0c6db71ad2f17d24edb061: No such file or directory
cp: testBuildOrg//.git/objects/d3/ebdb1a73d34bea83543b49395e5d6440dd7148: No such file or directory
cp: testBuildOrg//.git/objects/d3/ee6f54e4ca9ed618b4117585cc7c76dfddc391: No such file or directory
cp: testBuildOrg//.git/objects/d3/f25e5321a153ed60f3be5ecd32fa45f946fb21: No such file or directory
cp: testBuildOrg//.git/objects/d3/f8238008d5ba71e6967aaa824834347bf792c5: No such file or directory
cp: testBuildOrg//.git/objects/d3/fab72dc273e1ea5da9eebd85e77af6ef718dc1: No such file or directory
cp: testBuildOrg//.git/objects/d3/fc1ce7f72c3d79712ec058fb96974e2aa43d33: No such file or directory
cp: testBuildOrg//.git/objects/d6/d45d83549fcd95d2d69a5e53ae38a68fec9b52: No such file or directory
cp: testBuildOrg//.git/objects/d6/d804510b66a319f4a76ae7519563048773c4bb: No such file or directory
cp: testBuildOrg//.git/objects/d6/dd8229045cfa4af3fa93700b9a862990f60417: No such file or directory
cp: testBuildOrg//.git/objects/d6/e20c06579a04717abadcb198766fd3dc74b2be: No such file or directory
cp: testBuildOrg//.git/objects/d6/e22204de2ff90981bab69250df202c227d2d67: No such file or directory
cp: testBuildOrg//.git/objects/d6/e7601dbbb0c7e7a43a2c458771cfc364332171: No such file or directory
cp: testBuildOrg//.git/objects/d6/e96bb8397b224c9105d8553d7131e46f051469: No such file or directory
cp: testBuildOrg//.git/objects/d6/f3e520fbeba86cfd9e6426c88d0a580aaba6cc: No such file or directory
cp: testBuildOrg//.git/objects/d6/fd752f7282839dc40ab607ecc7e90b522f1201: No such file or directory
cp: testBuildOrg//.git/objects/d6/ffa04d01cd8d93460d7dd4321c06847c56b4e8: No such file or directory
cp: testBuildOrg//.git/objects/d6/ffbe507fa341bbe4cfe66464fc720933d184b6: No such file or directory
cp: testBuildOrg//.git/objects/d7/ab8ef92b6f8d89b7377f61714996cda90202c7: No such file or directory
cp: testBuildOrg//.git/objects/d7/ac08580153ad37e26ecddfc08a3575cffdcc67: No such file or directory
cp: testBuildOrg//.git/objects/d7/b2a31c3b4382c6aa377726962eba2c4aded998: No such file or directory
cp: testBuildOrg//.git/objects/d7/b5f0ec1abb06e51db653f43151d1265342f804: No such file or directory
cp: testBuildOrg//.git/objects/d7/c14b68bdb6b752ee8248c18813efe9ffcb08cc: No such file or directory
cp: testBuildOrg//.git/objects/d7/c4b8aed009a0e7482c42bd5702ff6b748fcd2c: No such file or directory
cp: testBuildOrg//.git/objects/d7/d3b81e56d973b6cf55ba8c616d622062aeda8e: No such file or directory
cp: testBuildOrg//.git/objects/d7/e175b6101a6bf322335a0fd7e9175b2233132d: No such file or directory
cp: testBuildOrg//.git/objects/d7/e3aa90637f84d7136e53c3c689cad058afdda7: No such file or directory
cp: testBuildOrg//.git/objects/d7/eb1bc2fda9a7487c97f71da389ffdd65ad6b4e: No such file or directory
cp: testBuildOrg//.git/objects/d7/ec47e2e3aa8e49938670c7660ab842749f904e: No such file or directory
cp: testBuildOrg//.git/objects/d7/f104f0c81042083348cda77f8b94e915340805: No such file or directory
cp: testBuildOrg//.git/objects/d7/f11c821188956fb7da031881c86a797c54ad14: No such file or directory
cp: testBuildOrg//.git/objects/d7/f2772ff78b5479b73be6a1a58dd9ffd1b0a359: No such file or directory
cp: testBuildOrg//.git/objects/d7/f769e9ecb16ebbe304091c5aafba39c66fd192: No such file or directory
cp: testBuildOrg//.git/objects/d7/fc59b52dfc2505b131d2080d046200e32f91ef: No such file or directory
cp: testBuildOrg//.git/objects/d8/610c63bdde14817961e5237f9588c9dfff5230: No such file or directory
cp: testBuildOrg//.git/objects/d8/702f102ea570fa51c7f146bfa911fc5527c96b: No such file or directory
cp: testBuildOrg//.git/objects/d8/70626ec2731f2b501a2b8c939aa0f7b4b4ec5a: No such file or directory
cp: testBuildOrg//.git/objects/d8/7d04cd4d4e77f6de665eef8d769cda2c558936: No such file or directory
cp: testBuildOrg//.git/objects/d8/807588af775c2dcd75c87b8ac01218a672ef26: No such file or directory
cp: testBuildOrg//.git/objects/d8/80bacaff7549c17b50d83f9662055f368468a9: No such file or directory
cp: testBuildOrg//.git/objects/d8/865d939b3ebc30494650d529c7b9912654633b: No such file or directory
cp: testBuildOrg//.git/objects/d8/87d2a7a1334d1c43989954d78919e1fe66498c: No such file or directory
cp: testBuildOrg//.git/objects/d8/9834080220d78bf4de757c70156385dd68f5f3: No such file or directory
cp: testBuildOrg//.git/objects/d8/9f914a4a702c7ea6d4c5b4576b35cb1f6d9b0a: No such file or directory
cp: testBuildOrg//.git/objects/d8/aa3936c53f116c0871507f419ae7b03a391f15: No such file or directory
cp: testBuildOrg//.git/objects/d8/b316ddb5c87c75f2918b61334791c0d52a8318: No such file or directory
cp: testBuildOrg//.git/objects/d8/b3172cbbf07e7bafc15f13e66a41c3805ef5f4: No such file or directory
cp: testBuildOrg//.git/objects/d8/b4ed8036e5782347452a9a9f8016b5709285d7: No such file or directory
cp: testBuildOrg//.git/objects/d8/c4a66a52b0c6da5df49d124503ad2ee529889c: No such file or directory
cp: testBuildOrg//.git/objects/d8/cbdc292a23e79b1981d286e907b99d95384b91: No such file or directory
cp: testBuildOrg//.git/objects/d8/d84a56e7df43727748500da26adcc4ab9b643f: No such file or directory
cp: testBuildOrg//.git/objects/d8/dcb62522a3854742827bd25538338c32d424fc: No such file or directory
cp: testBuildOrg//.git/objects/dc/8ad7e70758e736ce8b45bde79dce10625db7bb: No such file or directory
cp: testBuildOrg//.git/objects/dc/8f4623ec6958bf93441a6638f55848409f4250: No such file or directory
cp: testBuildOrg//.git/objects/dc/92c329d3ba660755e2daad29a80cf8145876a4: No such file or directory
cp: testBuildOrg//.git/objects/dc/95b3fc2fb51f796ecd2a174ae7d4e48b15b1e5: No such file or directory
cp: testBuildOrg//.git/objects/dc/96973fa03f5fb09d4a555475b2b72d4e60fac8: No such file or directory
cp: testBuildOrg//.git/objects/dc/9a88f71cf894e8f80923ec616d3917d4f47ce7: No such file or directory
cp: testBuildOrg//.git/objects/dc/9ea5de1f1b1ca589629c7232bb3be199bf5776: No such file or directory
cp: testBuildOrg//.git/objects/dc/a05f13812e042d3b52cd99695855191d330aaa: No such file or directory
cp: testBuildOrg//.git/objects/dc/a7083384cae803933ccbae443118405433a4e4: No such file or directory
cp: testBuildOrg//.git/objects/dc/b31f536f204bc363f6dc173975613a4ca1098d: No such file or directory
cp: testBuildOrg//.git/objects/dc/b771b6d2bfe80944e42077e8e5baac4703aad4: No such file or directory
cp: testBuildOrg//.git/objects/dc/b98ea4907c157239947ee1fb10e6ac62fed195: No such file or directory
cp: testBuildOrg//.git/objects/dc/bba31b413296b58e1af334d0bc0881c8f975d6: No such file or directory
cp: testBuildOrg//.git/objects/dc/c45a865445c4622f8b2c9d9492c87be3e7def4: No such file or directory
cp: testBuildOrg//.git/objects/dc/c919024fde7767db35a6cd887de4fb58037f02: No such file or directory
cp: testBuildOrg//.git/objects/dc/c9c36a093a5184bc69782bf5d9929bd97a360e: No such file or directory
cp: testBuildOrg//.git/objects/dc/ccbc3fdf5d00b18f5d02a862ba1d3e0d63b88f: No such file or directory
cp: testBuildOrg//.git/objects/dc/ccc25ebed34681f4bcc49c347ea1b4445f119a: No such file or directory
cp: testBuildOrg//.git/objects/dc/cdeed448e2de77e1565fddf21eeb6718997314: No such file or directory
cp: testBuildOrg//.git/objects/dc/ce35e5980e7e5c7dbc724d103036dcc0fc173b: No such file or directory
cp: testBuildOrg//.git/objects/dc/cebd765a2458f594f8d4dca79ef45dc921b2c8: No such file or directory
cp: testBuildOrg//.git/objects/dc/cf6dfa491f86eb7aefe30f81ae2b2fb6cd2dc8: No such file or directory
cp: testBuildOrg//.git/objects/dc/d43fa10e47ac9afc5b0a5d87dda2394c50fa5b: No such file or directory
cp: testBuildOrg//.git/objects/dc/dcc854e6ac7aa30db5cb7f78226de865712a11: No such file or directory
cp: testBuildOrg//.git/objects/dc/dfa3cfd45cb9d7671e4be3062b75a79a005175: No such file or directory
cp: testBuildOrg//.git/objects/dc/e880f4c1c7b6e667afd7262c7bbe7201d16b78: No such file or directory
cp: testBuildOrg//.git/objects/dc/eaf03306e7e2f16ef32e964cabc0f53955fb83: No such file or directory
cp: testBuildOrg//.git/objects/dc/eb906abc3bbf7c4a90342dba5a5b3664c6a677: No such file or directory
cp: testBuildOrg//.git/objects/dc/f02066d823cdd7cccc90013d9d79ad713b0b76: No such file or directory
cp: testBuildOrg//.git/objects/dc/f24c17a93718ff0e732d31742a41a5975c8a69: No such file or directory
cp: testBuildOrg//.git/objects/dc/f3b3864722f4d8b16c605dee50d7548286e6e3: No such file or directory
cp: testBuildOrg//.git/objects/dc/fe20cf80396c4b4d070b9b1b33192ebc9ade69: No such file or directory
cp: testBuildOrg//.git/objects/e8/6cd55cdfddf15bfded67101e3b7bc009bbcdf3: No such file or directory
cp: testBuildOrg//.git/objects/e8/708b11b47da0637247e697cc86b78e6b6c419b: No such file or directory
cp: testBuildOrg//.git/objects/e8/7fad44e178d1b801545026ad87b065289c26f1: No such file or directory
cp: testBuildOrg//.git/objects/e8/8443ca14cf63c3689d9f686097755d1470b5a4: No such file or directory
cp: testBuildOrg//.git/objects/e8/87174af3b27bd75ef2d70537076792e9079401: No such file or directory
cp: testBuildOrg//.git/objects/e8/91c50ff78538b340dfdc860771682250eca5b6: No such file or directory
cp: testBuildOrg//.git/objects/e8/92c784f8c97afa003ce83dc692cf7784e8ce8d: No such file or directory
cp: testBuildOrg//.git/objects/e8/9878055cf36bc9abbc0ff734c9361762abcab3: No such file or directory
cp: testBuildOrg//.git/objects/e8/99f867450a44c63e3f17dbbe0ad9d35ce89b16: No such file or directory
cp: testBuildOrg//.git/objects/e8/9ebacd126992c1e7f63f0205078e0dbf13ad0d: No such file or directory
cp: testBuildOrg//.git/objects/e8/b0bed5bf35f95ffdf37fac8b3862418f8de4a7: No such file or directory
cp: testBuildOrg//.git/objects/e8/be9a4eadea53c1d491ca37025902195f291138: No such file or directory
cp: testBuildOrg//.git/objects/e8/c170842e319df88b7d509cc75c47381215aeac: No such file or directory
cp: testBuildOrg//.git/objects/e8/c4d09a3c969f264ed44bdbfb5ac109c52fc1ac: No such file or directory
cp: testBuildOrg//.git/objects/e8/cca64c10d19970cf8b61545a162dd2a6af5e67: No such file or directory
cp: testBuildOrg//.git/objects/e8/ce7770d52ddbbdc449add3370c5a520ee3e5d8: No such file or directory
cp: testBuildOrg//.git/objects/e8/da54caff8f73ca02d74f4b98ea74c9e771c9c5: No such file or directory
cp: testBuildOrg//.git/objects/e8/dd24c26dad7e78f70d07e6376f24d9c11ff0ca: No such file or directory
cp: testBuildOrg//.git/objects/e8/df84e25e76ecbf797c6890d672801195cf014e: No such file or directory
cp: testBuildOrg//.git/objects/e8/e55f3039829d4bed457ae623cc06821513d95a: No such file or directory
cp: testBuildOrg//.git/objects/e8/e63fcb4123428c493a67c1832d82265da604c3: No such file or directory
cp: testBuildOrg//.git/objects/e8/ef668c59da39f49f5d1ceb0214733e76723f67: No such file or directory
cp: testBuildOrg//.git/objects/e8/f5d92134c19a1c3595520809a9d426437dbd8b: No such file or directory
cp: testBuildOrg//.git/objects/e8/f72332bd3c2ed685ebf3b87a0b25f6bb1aab5a: No such file or directory
cp: testBuildOrg//.git/objects/e8/fb1f84d5366f01764af19a4f9386f6849b400a: No such file or directory
cp: testBuildOrg//.git/objects/e8/fe6c58a882c2f94237b6b6446082e2477dcd0d: No such file or directory
cp: testBuildOrg//.git/objects/e9/c6fa8d79c0d4147f2f1bfccdc68aae33f79d12: No such file or directory
cp: testBuildOrg//.git/objects/e9/cbca6d87cc9ba34e34008bd683ac764c235690: No such file or directory
cp: testBuildOrg//.git/objects/e9/d1df71242c3c17fb0588c29a7db08f14827d50: No such file or directory
cp: testBuildOrg//.git/objects/e9/d6c16923f6499b57625d36c9573099a5578a7a: No such file or directory
cp: testBuildOrg//.git/objects/e9/e350ab511b612d3b891673550fa21a785bcf31: No such file or directory
cp: testBuildOrg//.git/objects/e9/e52642f9cac9309830f4c8f383d643f6ea20a7: No such file or directory
cp: testBuildOrg//.git/objects/e9/e7eb804e3c4a4d467a9cb3271c91009e5e5439: No such file or directory
cp: testBuildOrg//.git/objects/e9/eaebda19c94f00197bb5cb6c37f2092f1f2e84: No such file or directory
cp: testBuildOrg//.git/objects/e9/ebe3f69b71541f3264b393876ff2db949e4042: No such file or directory
cp: testBuildOrg//.git/objects/e9/effd805e1205d2817431ee0efa2535e7eeb06b: No such file or directory
cp: testBuildOrg//.git/objects/e9/f6171291bc462b2e5b10153e5ade209a20a326: No such file or directory
cp: testBuildOrg//.git/objects/ea/87f9ec813b42c477bb8ba036c4d9ec6654e671: No such file or directory
cp: testBuildOrg//.git/objects/ea/88be4243207750ac283da3131366fc368ac5f3: No such file or directory
cp: testBuildOrg//.git/objects/ea/896ac6f21e97f7084cb695011ce3bc0453b646: No such file or directory
cp: testBuildOrg//.git/objects/ea/8f8f1d703ef089f880058b693fc3074a80f33c: No such file or directory
cp: testBuildOrg//.git/objects/ea/9047a000066b8363b4a6505165d8c3bb91fd7a: No such file or directory
cp: testBuildOrg//.git/objects/ea/991af313f1d5d0828f52236768ab78a08e9fed: No such file or directory
cp: testBuildOrg//.git/objects/ea/a083569bf43fe1a787a23fd1740abf38a61b39: No such file or directory
cp: testBuildOrg//.git/objects/ea/a32edd31533aee4a3fb251dcd52467ad06f06f: No such file or directory
cp: testBuildOrg//.git/objects/ea/a83f7e67d9d791ce2c72dfbea5a94f9e30b5d6: No such file or directory
cp: testBuildOrg//.git/objects/ea/a90a9f3e49aa843650e6ff0c7fd43f67a3e539: No such file or directory
cp: testBuildOrg//.git/objects/ea/a9e63c180bfa76e3fc9fd11412628cd8277235: No such file or directory
cp: testBuildOrg//.git/objects/ea/b32a598a20925d718ef66e3288a1b85f613ca2: No such file or directory
cp: testBuildOrg//.git/objects/ea/b82cf481a0092c3d3c85f0cce52ecd48126537: No such file or directory
cp: testBuildOrg//.git/objects/ea/b9c506b8f3d440e8df8e58bdbf7796f9f1b5c8: No such file or directory
cp: testBuildOrg//.git/objects/ea/d9dec3414b19a669bb8216a269b694fa914334: No such file or directory
cp: testBuildOrg//.git/objects/ea/deeb5169783069fab8a211b9c7031b411ef5c8: No such file or directory
cp: testBuildOrg//.git/objects/ea/e3c6a7a80a2d85990e29aee5784de2f518a7f6: No such file or directory
cp: testBuildOrg//.git/objects/ea/e5cbaf5cf60565e4b6bbc0144ad371ba15e7f5: No such file or directory
cp: testBuildOrg//.git/objects/ea/e68b20091568667226df587a7a94717cc9a499: No such file or directory
cp: testBuildOrg//.git/objects/ea/ed2159cd05c0bc89869510915ab50e209b6ea7: No such file or directory
cp: testBuildOrg//.git/objects/ea/f891361187765be848d9f9822cb4b6273fc361: No such file or directory
cp: testBuildOrg//.git/objects/ea/fb8b6103bd3eecd1fbbc4b68478408950bc7d0: No such file or directory
cp: testBuildOrg//.git/objects/ea/fca6d914bcea230da7091e586e50c0da8e8524: No such file or directory
cp: testBuildOrg//.git/objects/f2: unable to copy extended attributes to testBuild/.git/objects/f2: No such file or directory
cp: testBuildOrg//.git/objects/f2: No such file or directory
cp: testBuildOrg//.git/objects/f9/b8270a5b87e44af1c1abe952116132f68aef14: No such file or directory
cp: testBuildOrg//.git/objects/f9/b9191176cbc78c6e2afe24e0a2e2d69201fb5e: No such file or directory
cp: testBuildOrg//.git/objects/f9/c2e51288c11e53b79d442bf0c1e0358bb1e6a1: No such file or directory
cp: testBuildOrg//.git/objects/f9/d14e624bec19b9d67fc24e52a3852f27525440: No such file or directory
cp: testBuildOrg//.git/objects/f9/d38962a49c6920a94ad00c48f84f5c104f8843: No such file or directory
cp: testBuildOrg//.git/objects/f9/de2fa297271654fcdc92b9d23e9aa45709c037: No such file or directory
cp: testBuildOrg//.git/objects/f9/e3213b7621ee082e4f78c44b54960ccd21401e: No such file or directory
cp: testBuildOrg//.git/objects/f9/e4b61df560ce5ed1f8c86f6342ca7db67c3c57: No such file or directory
cp: testBuildOrg//.git/objects/f9/e802ec7ea426fb9d870d0df9cf0eeb8812f2bd: No such file or directory
cp: testBuildOrg//.git/objects/f9/ee7508db3b04e715dcf72c9c71d04039e62572: No such file or directory
cp: testBuildOrg//.git/objects/fa/73c6b0420f2f230ba755ec889598396d501818: No such file or directory
cp: testBuildOrg//.git/objects/fa/7bd0c53136301400b0e00c0a8035872c6bdbe6: No such file or directory
cp: testBuildOrg//.git/objects/fa/7d054f1b8133fa8304f53daf53b79af5e250f2: No such file or directory
cp: testBuildOrg//.git/objects/fa/812e1dacb8cfe7f8e3f6b297ade43f4adcc6f7: No such file or directory
cp: testBuildOrg//.git/objects/fa/888ad3ed47a32d3632bfc1fc636695fe72dcbb: No such file or directory
cp: testBuildOrg//.git/objects/fa/90c80532cbe38d0e7646d298e5c94e2fc9987c: No such file or directory
cp: testBuildOrg//.git/objects/fa/91ca3cb524b09149f3e76de4a10c59c3310ab9: No such file or directory
cp: testBuildOrg//.git/objects/fa/933d09d535fcd5e9809b2eeeec7149b0bca1ab: No such file or directory
cp: testBuildOrg//.git/objects/fa/94ec7be56dc80ad121707a4e8e082d60012f5e: No such file or directory
cp: testBuildOrg//.git/objects/fa/acf1d163297a8d0a4917726580f71f1a16a24e: No such file or directory
cp: testBuildOrg//.git/objects/fa/af6901fc6c2530363e10eeca437c6093402642: No such file or directory
cp: testBuildOrg//.git/objects/fa/bdb7e41f251c880498c7908ae00b6827ace055: No such file or directory
cp: testBuildOrg//.git/objects/fa/c73c7931fa32e6808c936b1c377cdb760b9e4e: No such file or directory
cp: testBuildOrg//.git/objects/fa/c78de38538ee78fa2b523758c892c6cd7e8123: No such file or directory
cp: testBuildOrg//.git/objects/fa/d6cfedf288d4db56016aeeac3b326e3d25a9ec: No such file or directory
cp: testBuildOrg//.git/objects/fa/d9524a09202314cc866806e6e3eeb1f548788a: No such file or directory
cp: testBuildOrg//.git/objects/fa/e2ac926d55629096cc3669482466a57c0d1a0e: No such file or directory
cp: testBuildOrg//.git/objects/fa/edfd5b903653c0d2fd73b24d5096ce21e907a1: No such file or directory
cp: testBuildOrg//.git/objects/fa/f5c06dee410eb74f265edf65d3cf6b1b8b244e: No such file or directory
cp: testBuildOrg//.git/objects/fa/f65e07f68f84be9cfc1a8355aa34b435f6f3c7: No such file or directory
cp: testBuildOrg//.git/objects/fa/fd3982709eaae8623e29fb76f2c9ab054e315b: No such file or directory
cp: testBuildOrg//.git/objects/fa/fe3d897fa180bc6e2c02543502dd22d58d61ed: No such file or directory
cp: testBuildOrg//.git/objects/fb/3891b3ee64f47e247c497e01cb0dff1fd1f97d: No such file or directory
cp: testBuildOrg//.git/objects/fb/40a6c0b1f6e489ac3146522e253e5ededcc584: No such file or directory
cp: testBuildOrg//.git/objects/fb/482c843fbb0c9de300932ac34fc45b57bfe44b: No such file or directory
cp: testBuildOrg//.git/objects/fb/4878968c4b651bce5c1ebbbcc2558b6818954a: No such file or directory
cp: testBuildOrg//.git/objects/fb/49b5ead17792e58d461cd0746bbe08c10fa7de: No such file or directory
cp: testBuildOrg//.git/objects/fb/53f385e4862c93688272dfeabb44668527d6e4: No such file or directory
cp: testBuildOrg//.git/objects/fb/62ea7e318e8001145ba85c30be4d77fdb61211: No such file or directory
cp: testBuildOrg//.git/objects/fb/64fa4ca9eb1e75f93303f2265d764b343e9794: No such file or directory
cp: testBuildOrg//.git/objects/fb/6d91c6d8e30adc9587f0a54ecdd1a7f3132db3: No such file or directory
cp: testBuildOrg//.git/objects/fb/70d68b05f95c8deb7f0652cbb8fc3261421396: No such file or directory
cp: testBuildOrg//.git/objects/fb/7fd53e17628b3f905696ad4789743420ba099b: No such file or directory
cp: testBuildOrg//.git/objects/fb/88aa5db2610d68d6d34799bd464fea8d6634eb: No such file or directory
cp: testBuildOrg//.git/objects/fb/8b6c14ab8281be5bbf84638178f4d10f62ab34: No such file or directory
cp: testBuildOrg//.git/objects/fb/9272b68ee1fede93ab83f2afaa51f46af2e5a6: No such file or directory
cp: testBuildOrg//.git/objects/fb/ab494773e49b31ca5734921b902d229f991d29: No such file or directory
cp: testBuildOrg//.git/objects/fb/b1b27a665ea42ed7c0aaef3fcc4e9711962196: No such file or directory
cp: testBuildOrg//.git/objects/fb/b22d25b2e4605fd40ec3c31c65b6c81ff2a572: No such file or directory
cp: testBuildOrg//.git/objects/fb/b488a9df299e648045089c16a420ca9862373e: No such file or directory
cp: testBuildOrg//.git/objects/fb/c6a5ebe451bb27de396c726ec3891f6690d299: No such file or directory
cp: testBuildOrg//.git/objects/fb/c720e48a3e1ae9cafd4ac74a27cd4f0c434e95: No such file or directory
cp: testBuildOrg//.git/objects/fb/ce2387518065de7a8dbcd20b6c3de014de8bae: No such file or directory
cp: testBuildOrg//.git/objects/fb/d53591136e4ef357ced951c1a78d8c8971212b: No such file or directory
cp: testBuildOrg//.git/objects/fb/d72fe4aeb4fffbab32e67e616b47e91405243a: No such file or directory
cp: testBuildOrg//.git/objects/fb/d8d4f7dcb774143ac72b421e41b54ae7c944ca: No such file or directory
cp: testBuildOrg//.git/objects/fb/ddcb489f229186b40c2858560d5c2b216b5c25: No such file or directory
cp: testBuildOrg//.git/objects/fb/e843926443d51e70223ab123f4e57917b570fc: No such file or directory
cp: testBuildOrg//.git/objects/fb/fed8f1d7df4495ded7cfff5aac4acaabd359ec: No such file or directory
cp: testBuildOrg//.git/objects/fc/9f7d3fa55719c44b048f63e3f12be4c564aaa7: No such file or directory
cp: testBuildOrg//.git/objects/fc/9fa6f146b04765f20140e6c8b6afb5da277899: No such file or directory
cp: testBuildOrg//.git/objects/fc/b2e773f8da16b99972459a0be68fbef56f5ea9: No such file or directory
cp: testBuildOrg//.git/objects/fc/b3114927c194b051c714cab0fb29ff602ec306: No such file or directory
cp: testBuildOrg//.git/objects/fc/b904fd247e05224771a4153894850f3ef80581: No such file or directory
cp: testBuildOrg//.git/objects/fc/c46903369ec497f9b777881a67060f5e2fce7f: No such file or directory
cp: testBuildOrg//.git/objects/fc/c7f1711f4e9b378fdd48c5f31a1278bd9e7c94: No such file or directory
cp: testBuildOrg//.git/objects/fc/cc2691b6095b3d7b9674b5d680bbe894ab3ee7: No such file or directory
cp: testBuildOrg//.git/objects/fc/cea7e88e56be399f07ec44c0d717ba4f438ee9: No such file or directory
cp: testBuildOrg//.git/objects/fc/dc31b81da2f98f626a7f15604b9935cee18e95: No such file or directory
cp: testBuildOrg//.git/objects/fc/f0eb996a97e16e9e7152077ffe0cdb9aaeb727: No such file or directory
cp: testBuildOrg//.git/objects/fc/f4b31ec06a85611d976b377fa38e6a9f2caa3a: No such file or directory
cp: testBuildOrg//.git/objects/fd/7eafcb617794330ae8e966601f3802b476354e: No such file or directory
cp: testBuildOrg//.git/objects/fd/83edafc2d69c3cf3ee27f08b6b34d18d602de1: No such file or directory
cp: testBuildOrg//.git/objects/fd/8a85244b3b7c02bc487bc6ca5c1bd9f8a65e6a: No such file or directory
cp: testBuildOrg//.git/objects/fd/8d22b68c82dbfc27003698b132288710fea842: No such file or directory
cp: testBuildOrg//.git/objects/fd/a5ffe3156fc8e984575384970805c9c7f2fb14: No such file or directory
cp: testBuildOrg//.git/objects/fd/a7c0b5ec1d5a867275a2c189e4e4bb51091be4: No such file or directory
cp: testBuildOrg//.git/objects/fd/a9f42f245e48cc140537e86cde9cdc301a80ce: No such file or directory
cp: testBuildOrg//.git/objects/fd/ae11fa91338d087b439b3e8132da14f14b5ee3: No such file or directory
cp: testBuildOrg//.git/objects/fd/c174e40cae6b0a817476ca54fc8320d4eb354c: No such file or directory
cp: testBuildOrg//.git/objects/fd/cee0cda56b6b869d44e56afe9bae086739f60d: No such file or directory
cp: testBuildOrg//.git/objects/fd/d630afb5e2d9adf7e4349fe8f516a4987e0ea7: No such file or directory
cp: testBuildOrg//.git/objects/fd/e0215087e8b7de836d0ac6454d7c4bbc90bd37: No such file or directory
cp: testBuildOrg//.git/objects/fd/e119119b56346ab1c9b35d52769bf62bf3b15a: No such file or directory
cp: testBuildOrg//.git/objects/fd/e6ef37b91ebd2e44ffc035194ff934d4e7da3c: No such file or directory
cp: testBuildOrg//.git/objects/fd/ed54dbf26ab1cf83c63e04075fc13989a92f43: No such file or directory
cp: testBuildOrg//.git/objects/fd/eec24b9ee162fabac137f2ca0def13cca35aa2: No such file or directory
cp: testBuildOrg//.git/objects/fd/ef387a0b162a06608dfc9bf2b8c957e4a027e1: No such file or directory
cp: testBuildOrg//.git/objects/fd/f1d3baaa5524b9b91430b325c0c0811f029c26: No such file or directory
cp: testBuildOrg//.git/objects/fd/fa90b74bbf0e211e2b0d93dc01224e50fdf75b: No such file or directory
cp: testBuildOrg//.git/objects/fe/1f0c4c9db965c67d9ac1e0f9b9399bb9f809dc: No such file or directory
cp: testBuildOrg//.git/objects/fe/1fc1e3d9abea4339c6511734289ea424bcbc66: No such file or directory
cp: testBuildOrg//.git/objects/fe/202a2bd7ce8ae3962717d1fcd8e46f8c33be4b: No such file or directory
cp: testBuildOrg//.git/objects/fe/21644cd1e28b23b94332d02677ca012b343438: No such file or directory
cp: testBuildOrg//.git/objects/fe/2180a49b0bf68e086fe9d37359c6f7140197c1: No such file or directory
cp: testBuildOrg//.git/objects/fe/24014906eb92396ccee5d59043e05c1def2d87: No such file or directory
cp: testBuildOrg//.git/objects/fe/31153be424c45e9aa6270840d28c321c44f55c: No such file or directory
cp: testBuildOrg//.git/objects/fe/353339cc5fbf30954744e079ba3cf756a8daa9: No such file or directory
cp: testBuildOrg//.git/objects/fe/3675ee3b662a3a127b42181e4b710a256ea256: No such file or directory
cp: testBuildOrg//.git/objects/fe/3a77a4f539be5989c9f182485364c4f6ff94bc: No such file or directory
cp: testBuildOrg//.git/objects/fe/409967af5199e1fd7ae9901be8203f0a75d6ff: No such file or directory
cp: testBuildOrg//.git/objects/fe/4721dd90a7674765c136cd16c3e270a1e6c3b5: No such file or directory
cp: testBuildOrg//.git/objects/fe/4be939245e17a63f46c06ea2dc9131a905bd8c: No such file or directory
cp: testBuildOrg//.git/objects/fe/4e202f3df00f78860a514d7fc54f1d11af789d: No such file or directory
cp: testBuildOrg//.git/objects/fe/5727b4f25e0ca7127799d4b845b7e9b628e054: No such file or directory
cp: testBuildOrg//.git/objects/fe/57564bb27ee27021546ca7385e19b88a941735: No such file or directory
cp: testBuildOrg//.git/objects/fe/5ef8653c4586b3e6bc1ec70339080617496b93: No such file or directory
cp: testBuildOrg//.git/objects/fe/5fcc49ced662dd33e6ad6b37dc54996286a67e: No such file or directory
cp: testBuildOrg//.git/objects/fe/6330e4be79057c9ac8b754192420c0d2f01c30: No such file or directory
cp: testBuildOrg//.git/objects/fe/683ba5aa8a3df6a2fa41846b055e97ba276b9c: No such file or directory
cp: testBuildOrg//.git/objects/fe/6f81afa32860254018c7fcec255ef704060b73: No such file or directory
cp: testBuildOrg//.git/objects/fe/76b7ef33113647c05c56afdfbe24d25e460aad: No such file or directory
cp: testBuildOrg//.git/objects/fe/78772b9fd0eaa0733aca495c6495cbebbbc1f8: No such file or directory
cp: testBuildOrg//.git/objects/fe/864cae1d9a176f014bb6eaf4fd342198613d4d: No such file or directory
cp: testBuildOrg//.git/objects/fe/95070ae5fea2fe278d4cfec84f8f3f71a9e566: No such file or directory
cp: testBuildOrg//.git/objects/fe/9654c538585721f465bb71f3e4e9ffde58aa3f: No such file or directory
cp: testBuildOrg//.git/objects/fe/9ea3f1c497999af85ea82ed995c5158af75f2c: No such file or directory
cp: testBuildOrg//.git/objects/fe/a0fd559489c9f931e4d4ad4315427b185182ae: No such file or directory
cp: testBuildOrg//.git/objects/fe/b2bbc6b600ad535656bbc5f2a68163686221ab: No such file or directory
cp: testBuildOrg//.git/objects/fe/ba808b3fc092feacc50f090f608f23574c863f: No such file or directory
cp: testBuildOrg//.git/objects/fe/c4474477f639451d096ca75612eda3e53a0ce8: No such file or directory
cp: testBuildOrg//.git/objects/fe/cb810296d4cfb5f427e5a8da1c2078f6ef00c2: No such file or directory
cp: testBuildOrg//.git/objects/fe/d2af1361c152c7007424a98e81ae66029d5dc0: No such file or directory
cp: testBuildOrg//.git/objects/fe/d9a857a50c6b85acfd7817c45199e280db0173: No such file or directory
cp: testBuildOrg//.git/objects/fe/df67127ea02fdc28138fe3cc46f42b00e6da93: No such file or directory
cp: testBuildOrg//.git/objects/fe/f0cc9d8ff113e8b3d04a00467a4229bf359e40: No such file or directory
cp: testBuildOrg//.git/objects/fe/f441027327e5aad02a7aab3ab88b3c5899c53a: No such file or directory
cp: testBuildOrg//.git/objects/fe/f578067e0683da663d130cd93e64f6856c9482: No such file or directory
cp: testBuildOrg//.git/objects/fe/f6fadf5eca9b757de123ec6acc1aff7ab0236d: No such file or directory
cp: testBuildOrg//.git/objects/ff/77b058cbb800341a92c2e1d9811debeccd6b03: No such file or directory
cp: testBuildOrg//.git/objects/ff/7ecb8f1f20806e9be1ac392a8dfbf15ea77a38: No such file or directory
cp: testBuildOrg//.git/objects/ff/823a7885dbe5e4849c4e518bebdaf8b297aff1: No such file or directory
cp: testBuildOrg//.git/objects/ff/8589d4167e8971976b1d831472d29b8d59e7a4: No such file or directory
cp: testBuildOrg//.git/objects/ff/85a284aa13216c03273d2bb8eca961ee6ad1ab: No such file or directory
cp: testBuildOrg//.git/objects/ff/863a6dc3b7db84b8044d918be84eddf64d6204: No such file or directory
cp: testBuildOrg//.git/objects/ff/8c1ff290ba385ff68df2cd93a022d2b53f7b8e: No such file or directory
cp: testBuildOrg//.git/objects/ff/8dafb9e6004082412bb7717e9a4014c8a156e7: No such file or directory
cp: testBuildOrg//.git/objects/ff/911f6bbb0e1380e5dc231706d6e0582ab88cc9: No such file or directory
cp: testBuildOrg//.git/objects/ff/923cdec1b389eae4b87320daa242928c9b81bf: No such file or directory
cp: testBuildOrg//.git/objects/ff/92f4bb5fa60f693f63303d86e4f6ed7274a85a: No such file or directory
cp: testBuildOrg//.git/objects/ff/9b09190bb93e9417ac042c026975ef1dda5212: No such file or directory
cp: testBuildOrg//.git/objects/ff/ae00f65bd9ca7b700620325a064a715c05ff24: No such file or directory
cp: testBuildOrg//.git/objects/ff/b14ce03656af904474359febb0e40d51b1f019: No such file or directory
cp: testBuildOrg//.git/objects/ff/b651022788e995003ba03eeb0a8330c5e115ae: No such file or directory
cp: testBuildOrg//.git/objects/ff/c7a76147102fb41fd4d8a40081a144ea554ad7: No such file or directory
cp: testBuildOrg//.git/objects/ff/cc7a56f3f8fbbe267f54c55b5d9b747ca03ba6: No such file or directory
cp: testBuildOrg//.git/objects/ff/ccd69469bd9ae9f6fc5286da085eb2caab2a04: No such file or directory
cp: testBuildOrg//.git/objects/ff/ce09b6cb038d0d8c61376bcea2590c7ab567c5: No such file or directory
cp: testBuildOrg//.git/objects/ff/d022733d52591bf0a7e28543890e7c4a4dd58d: No such file or directory
cp: testBuildOrg//.git/objects/ff/d2bfe34a7357a0fed764d8850beda430dc5be7: No such file or directory
cp: testBuildOrg//.git/objects/ff/da1b4b35362a5a6d6c5d7d0b398712ae965ca7: No such file or directory
cp: testBuildOrg//.git/objects/ff/dfe90284091a8992537089ecbd5537d8aba36f: No such file or directory
cp: testBuildOrg//.git/objects/ff/e7a1c73eb78523d049e40e4c366773d6da3418: No such file or directory
cp: testBuildOrg//.git/objects/ff/e9ac362c4b9bc32a07cfd2f65f5370b45b7e58: No such file or directory
cp: testBuildOrg//.git/objects/ff/e9f380d97c6aa31b006a496caa8b8237b623ff: No such file or directory
cp: testBuildOrg//.git/objects/ff/efeb465376d0c9dbb408b5f92b68f92f47fefa: No such file or directory
cp: testBuildOrg//.git/objects/ff/fa4574636b3a86f2a18a0650b08673e6e04775: No such file or directory
cp: testBuildOrg//.git/objects/ff/fd6a1c8f09343823886e0f43a144145144c547: No such file or directory
npm http request GET http://192.168.1.100:4873/fs-extra-promise
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/socket.io
npm http request GET http://192.168.1.100:4873/express
npm http 200 http://192.168.1.100:4873/lie
npm http 200 http://192.168.1.100:4873/fs-extra-promise
npm http 200 http://192.168.1.100:4873/winston
npm http 304 http://192.168.1.100:4873/socket.io
npm http 200 http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/accepts
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/content-disposition
npm http request GET http://192.168.1.100:4873/array-flatten
npm http request GET http://192.168.1.100:4873/cookie-signature
npm http request GET http://192.168.1.100:4873/cookie
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/etag
npm http request GET http://192.168.1.100:4873/escape-html
npm http request GET http://192.168.1.100:4873/parseurl
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/fresh
npm http request GET http://192.168.1.100:4873/merge-descriptors
npm http request GET http://192.168.1.100:4873/finalhandler
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/range-parser
npm http request GET http://192.168.1.100:4873/utils-merge
npm http request GET http://192.168.1.100:4873/send
npm http request GET http://192.168.1.100:4873/path-to-regexp
npm http request GET http://192.168.1.100:4873/proxy-addr
npm http request GET http://192.168.1.100:4873/vary
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/serve-static
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/accepts
npm http 200 http://192.168.1.100:4873/content-disposition
npm http 200 http://192.168.1.100:4873/array-flatten
npm http 200 http://192.168.1.100:4873/cookie-signature
npm http 200 http://192.168.1.100:4873/cookie
npm http 200 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/escape-html
npm http 200 http://192.168.1.100:4873/etag
npm http 200 http://192.168.1.100:4873/debug
npm http 200 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 200 http://192.168.1.100:4873/methods
npm http 200 http://192.168.1.100:4873/fresh
npm http 200 http://192.168.1.100:4873/on-finished
npm http 200 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/utils-merge
npm http 200 http://192.168.1.100:4873/qs
npm http 200 http://192.168.1.100:4873/range-parser
npm http 200 http://192.168.1.100:4873/send
npm http 200 http://192.168.1.100:4873/path-to-regexp
npm http 200 http://192.168.1.100:4873/proxy-addr
npm http 200 http://192.168.1.100:4873/vary
npm http 200 http://192.168.1.100:4873/type-is
npm http 304 http://192.168.1.100:4873/serve-static
npm http request GET http://192.168.1.100:4873/negotiator
npm http request GET http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/negotiator
npm http 200 http://192.168.1.100:4873/mime-types
npm http request GET http://192.168.1.100:4873/mime-db
npm http 304 http://192.168.1.100:4873/mime-db
npm http request GET http://192.168.1.100:4873/ms
npm http 200 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/unpipe
npm http 200 http://192.168.1.100:4873/unpipe
npm http request GET http://192.168.1.100:4873/ee-first
npm http 304 http://192.168.1.100:4873/ee-first
npm http request GET http://192.168.1.100:4873/forwarded
npm http request GET http://192.168.1.100:4873/ipaddr.js
npm http 200 http://192.168.1.100:4873/forwarded
npm http 200 http://192.168.1.100:4873/ipaddr.js
npm http request GET http://192.168.1.100:4873/mime
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/statuses
npm http 200 http://192.168.1.100:4873/destroy
npm http 304 http://192.168.1.100:4873/statuses
npm http 200 http://192.168.1.100:4873/mime
npm http 200 http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/inherits
npm http 200 http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/media-typer
npm http 200 http://192.168.1.100:4873/media-typer
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/fs-extra
npm http 304 http://192.168.1.100:4873/bluebird
npm http 200 http://192.168.1.100:4873/fs-extra
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/jsonfile
npm http request GET http://192.168.1.100:4873/rimraf
npm http 304 http://192.168.1.100:4873/rimraf
npm http 200 http://192.168.1.100:4873/jsonfile
npm http 200 http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/fs.realpath
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/inflight
npm http 200 http://192.168.1.100:4873/fs.realpath
npm http 200 http://192.168.1.100:4873/once
npm http 200 http://192.168.1.100:4873/minimatch
npm http 200 http://192.168.1.100:4873/path-is-absolute
npm http request GET http://192.168.1.100:4873/wrappy
npm http 200 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 200 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/concat-map
npm http 200 http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/immediate
npm http 200 http://192.168.1.100:4873/inline-process-browser
npm http 200 http://192.168.1.100:4873/immediate
npm http 200 http://192.168.1.100:4873/es3ify
npm http 200 http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/through
npm http 304 http://192.168.1.100:4873/esprima
npm http 200 http://192.168.1.100:4873/through
npm http 200 http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/source-map
npm http 200 http://192.168.1.100:4873/base62
npm http 304 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/esprima-fb
npm http 200 http://192.168.1.100:4873/source-map
npm http 200 http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/recast
npm http request GET http://192.168.1.100:4873/q
npm http 304 http://192.168.1.100:4873/mkdirp
npm http 304 http://192.168.1.100:4873/detective
npm http 200 http://192.168.1.100:4873/private
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 200 http://192.168.1.100:4873/commander
npm http 304 http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http 200 http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/defined
npm http request GET http://192.168.1.100:4873/acorn
npm http 200 http://192.168.1.100:4873/defined
npm http 200 http://192.168.1.100:4873/acorn
npm http request GET http://192.168.1.100:4873/minimist
npm http 200 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/ast-types
npm http 200 http://192.168.1.100:4873/ast-types
npm http request GET http://192.168.1.100:4873/amdefine
npm http 304 http://192.168.1.100:4873/amdefine
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/falafel
npm http 200 http://192.168.1.100:4873/falafel
npm http 200 http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/xtend
npm http 200 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/string_decoder
npm http request GET http://192.168.1.100:4873/core-util-is
npm http 200 http://192.168.1.100:4873/core-util-is
npm http 304 http://192.168.1.100:4873/string_decoder
npm http request GET http://192.168.1.100:4873/esmangle-evaluator
npm http 200 http://192.168.1.100:4873/esmangle-evaluator
npm http request GET http://192.168.1.100:4873/has-binary-data
npm http request GET http://192.168.1.100:4873/socket.io-adapter
npm http request GET http://192.168.1.100:4873/socket.io-parser
npm http request GET http://192.168.1.100:4873/engine.io
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http 304 http://192.168.1.100:4873/socket.io-adapter
npm http 304 http://192.168.1.100:4873/socket.io-parser
npm http 200 http://192.168.1.100:4873/has-binary-data
npm http 200 http://192.168.1.100:4873/socket.io-client
npm http 200 http://192.168.1.100:4873/engine.io
npm http request GET http://192.168.1.100:4873/base64id
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/ws
npm http 304 http://192.168.1.100:4873/base64id
npm http 304 http://192.168.1.100:4873/engine.io-parser
npm http 200 http://192.168.1.100:4873/ws
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/has-binary
npm http request GET http://192.168.1.100:4873/utf8
npm http 200 http://192.168.1.100:4873/arraybuffer.slice
npm http 200 http://192.168.1.100:4873/has-binary
npm http 200 http://192.168.1.100:4873/blob
npm http 200 http://192.168.1.100:4873/after
npm http 200 http://192.168.1.100:4873/utf8
npm http 200 http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/ultron
npm http request GET http://192.168.1.100:4873/options
npm http request GET http://192.168.1.100:4873/bufferutil
npm http request GET http://192.168.1.100:4873/utf-8-validate
npm http 304 http://192.168.1.100:4873/ultron
npm http 200 http://192.168.1.100:4873/utf-8-validate
npm http 200 http://192.168.1.100:4873/options
npm http 200 http://192.168.1.100:4873/bufferutil
npm http request GET http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/nan
npm http 200 http://192.168.1.100:4873/nan
npm http 200 http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/component-emitter
npm http request GET http://192.168.1.100:4873/json3
npm http request GET http://192.168.1.100:4873/benchmark
npm http 304 http://192.168.1.100:4873/benchmark
npm http 200 http://192.168.1.100:4873/component-emitter
npm http 200 http://192.168.1.100:4873/json3
npm http request GET http://192.168.1.100:4873/component-bind
npm http request GET http://192.168.1.100:4873/backo2
npm http request GET http://192.168.1.100:4873/to-array
npm http request GET http://192.168.1.100:4873/parseuri
npm http request GET http://192.168.1.100:4873/object-component
npm http request GET http://192.168.1.100:4873/indexof
npm http request GET http://192.168.1.100:4873/engine.io-client
npm http 304 http://192.168.1.100:4873/component-bind
npm http 200 http://192.168.1.100:4873/to-array
npm http 200 http://192.168.1.100:4873/backo2
npm http 304 http://192.168.1.100:4873/parseuri
npm http 304 http://192.168.1.100:4873/object-component
npm http 200 http://192.168.1.100:4873/engine.io-client
npm http 200 http://192.168.1.100:4873/indexof
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/parseqs
npm http fetch GET https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http 304 http://192.168.1.100:4873/has-cors
npm http 200 http://192.168.1.100:4873/parseqs
npm http 304 http://192.168.1.100:4873/component-inherit
npm http 200 http://192.168.1.100:4873/parsejson
npm http fetch 200 https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http fetch GET https://github.com/component/global/archive/v2.0.1.tar.gz
npm http fetch 200 https://github.com/component/global/archive/v2.0.1.tar.gz
npm http request GET http://192.168.1.100:4873/better-assert
npm http 200 http://192.168.1.100:4873/better-assert
npm http request GET http://192.168.1.100:4873/callsite
npm http 200 http://192.168.1.100:4873/callsite
npm http request GET http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/stack-trace
npm http request GET http://192.168.1.100:4873/pkginfo
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/cycle
npm http request GET http://192.168.1.100:4873/colors
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/pkginfo
npm http 200 http://192.168.1.100:4873/cycle
npm http 200 http://192.168.1.100:4873/stack-trace
npm http 200 http://192.168.1.100:4873/eyes
npm http 200 http://192.168.1.100:4873/colors
npm http 200 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/tape
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 200 http://192.168.1.100:4873/tape
npm http request GET http://192.168.1.100:4873/jsonify
npm http request GET http://192.168.1.100:4873/deep-equal
npm http 200 http://192.168.1.100:4873/jsonify
npm http 304 http://192.168.1.100:4873/deep-equal
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
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/forever-agent
npm http request GET http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/javascript-state-machine
npm http request GET http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/salti
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/lie
npm http 200 http://192.168.1.100:4873/forever-agent
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/winston
npm http 304 http://192.168.1.100:4873/body-parser
npm http 200 http://192.168.1.100:4873/ip
npm http 200 http://192.168.1.100:4873/long
npm http 200 http://192.168.1.100:4873/javascript-state-machine
npm http 200 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/multiplex
npm http 200 http://192.168.1.100:4873/salti
npm http 304 http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/type-is
npm http 200 http://192.168.1.100:4873/bytes
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
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/send
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/utils-merge
npm http 304 http://192.168.1.100:4873/serve-static
npm http 304 http://192.168.1.100:4873/vary
npm http request GET http://192.168.1.100:4873/negotiator
npm http 304 http://192.168.1.100:4873/negotiator
npm http request GET http://192.168.1.100:4873/ipaddr.js
npm http request GET http://192.168.1.100:4873/forwarded
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
npm http 304 http://192.168.1.100:4873/es3ify
npm http 304 http://192.168.1.100:4873/inline-process-browser
npm http 304 http://192.168.1.100:4873/immediate
npm http 304 http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/through
npm http 304 http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/esprima
npm http 304 http://192.168.1.100:4873/through
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/commoner
npm http 304 http://192.168.1.100:4873/base62
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/commander
npm http 304 http://192.168.1.100:4873/detective
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http 304 http://192.168.1.100:4873/mkdirp
npm http 304 http://192.168.1.100:4873/q
npm http 304 http://192.168.1.100:4873/private
npm http 304 http://192.168.1.100:4873/recast
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http 304 http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/acorn
npm http request GET http://192.168.1.100:4873/defined
npm http 304 http://192.168.1.100:4873/acorn
npm http 304 http://192.168.1.100:4873/defined
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/inflight
npm http 304 http://192.168.1.100:4873/minimatch
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
npm http 304 http://192.168.1.100:4873/ast-types
npm http request GET http://192.168.1.100:4873/amdefine
npm http 304 http://192.168.1.100:4873/amdefine
npm http request GET http://192.168.1.100:4873/falafel
npm http request GET http://192.168.1.100:4873/through2
npm http 304 http://192.168.1.100:4873/through2
npm http 200 http://192.168.1.100:4873/falafel
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
npm http 304 http://192.168.1.100:4873/esmangle-evaluator
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/varint
npm http 304 http://192.168.1.100:4873/duplexify
npm http 304 http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/stream-shift
npm http 304 http://192.168.1.100:4873/stream-shift
npm http 200 http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http 304 http://192.168.1.100:4873/buffer-shims
npm http 200 http://192.168.1.100:4873/process-nextick-args
npm http 200 http://192.168.1.100:4873/util-deprecate
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 200 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/bl
npm http 200 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/stringstream
npm http 200 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/har-validator
npm http 200 http://192.168.1.100:4873/combined-stream
npm http 200 http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/chalk
npm http 304 http://192.168.1.100:4873/chalk
npm http 304 http://192.168.1.100:4873/is-my-json-valid
npm http 304 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 200 http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/ansi-styles
npm http 200 http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 200 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 200 http://192.168.1.100:4873/generate-object-property
npm http 200 http://192.168.1.100:4873/generate-function
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http request GET http://192.168.1.100:4873/is-property
npm http 200 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/boom
npm http 304 http://192.168.1.100:4873/cryptiles
npm http 200 http://192.168.1.100:4873/sntp
npm http 200 http://192.168.1.100:4873/boom
npm http 200 http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 304 http://192.168.1.100:4873/asn1
npm http 200 http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/colors
npm http request GET http://192.168.1.100:4873/cycle
npm http request GET http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/pkginfo
npm http request GET http://192.168.1.100:4873/stack-trace
npm http 304 http://192.168.1.100:4873/stack-trace
npm http 304 http://192.168.1.100:4873/colors
npm http 304 http://192.168.1.100:4873/eyes
npm http 304 http://192.168.1.100:4873/pkginfo
npm http 304 http://192.168.1.100:4873/cycle
npm http request GET http://192.168.1.100:4873/jsdoc
npm http 200 http://192.168.1.100:4873/jsdoc
npm http request GET http://192.168.1.100:4873/catharsis
npm http request GET http://192.168.1.100:4873/js2xmlparser
npm http request GET http://192.168.1.100:4873/marked
npm http request GET http://192.168.1.100:4873/requizzle
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/underscore
npm http request GET http://192.168.1.100:4873/wrench
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 200 http://192.168.1.100:4873/js2xmlparser
npm http 304 http://192.168.1.100:4873/strip-json-comments
npm http 200 http://192.168.1.100:4873/catharsis
npm http 200 http://192.168.1.100:4873/requizzle
npm http 200 http://192.168.1.100:4873/marked
npm http 200 http://192.168.1.100:4873/underscore
npm http 200 http://192.168.1.100:4873/wrench
npm WARN deprecated wrench@1.5.9: wrench.js is deprecated! You should check out fs-extra (https://github.com/jprichardson/node-fs-extra) for any operations you were using wrench for. Thanks for all the usage over the years.
npm http fetch 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http request GET http://192.168.1.100:4873/underscore-contrib
npm http 304 http://192.168.1.100:4873/underscore-contrib
npm WARN prefer global marked@0.3.6 should be installed with -g
npm http request GET http://192.168.1.100:4873/fs-extra-promise
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/jxc
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/unzip
npm http 304 http://192.168.1.100:4873/fs-extra-promise
npm http 304 http://192.168.1.100:4873/lie
npm http 304 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/unzip
npm http 304 http://192.168.1.100:4873/jxc
npm http request GET http://192.168.1.100:4873/fs-extra
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/fs-extra
npm http 304 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/jsonfile
npm http request GET http://192.168.1.100:4873/rimraf
npm http 304 http://192.168.1.100:4873/jsonfile
npm http 304 http://192.168.1.100:4873/rimraf
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/fs.realpath
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/inflight
npm http 304 http://192.168.1.100:4873/fs.realpath
npm http 304 http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/minimatch
npm http 304 http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/wrappy
npm http 304 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 304 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/adm-zip
npm http request GET http://192.168.1.100:4873/progress
npm http 200 http://192.168.1.100:4873/progress
npm http 200 http://192.168.1.100:4873/adm-zip
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
npm http 304 http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/through
npm http 200 http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/commoner
npm http 304 http://192.168.1.100:4873/base62
npm http 304 http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/detective
npm http 304 http://192.168.1.100:4873/commander
npm http 304 http://192.168.1.100:4873/private
npm http 304 http://192.168.1.100:4873/mkdirp
npm http 304 http://192.168.1.100:4873/iconv-lite
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
npm http 304 http://192.168.1.100:4873/falafel
npm http 200 http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/core-util-is
npm http request GET http://192.168.1.100:4873/string_decoder
npm http 304 http://192.168.1.100:4873/core-util-is
npm http 304 http://192.168.1.100:4873/string_decoder
npm http request GET http://192.168.1.100:4873/esmangle-evaluator
npm http 200 http://192.168.1.100:4873/esmangle-evaluator
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/forever-agent
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/mime-types
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/forever-agent
npm http 304 http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 200 http://192.168.1.100:4873/isstream
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
npm http 304 http://192.168.1.100:4873/ansi-styles
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/supports-color
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
npm http 304 http://192.168.1.100:4873/hoek
npm http 304 http://192.168.1.100:4873/cryptiles
npm http 304 http://192.168.1.100:4873/boom
npm http 304 http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 304 http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/fstream
npm http request GET http://192.168.1.100:4873/pullstream
npm http request GET http://192.168.1.100:4873/binary
npm http request GET http://192.168.1.100:4873/setimmediate
npm http request GET http://192.168.1.100:4873/match-stream
npm http 304 http://192.168.1.100:4873/binary
npm http 304 http://192.168.1.100:4873/setimmediate
npm http 200 http://192.168.1.100:4873/match-stream
npm http 200 http://192.168.1.100:4873/pullstream
npm http 200 http://192.168.1.100:4873/fstream
npm http request GET http://192.168.1.100:4873/chainsaw
npm http request GET http://192.168.1.100:4873/buffers
npm http 200 http://192.168.1.100:4873/chainsaw
npm http 200 http://192.168.1.100:4873/buffers
npm http request GET http://192.168.1.100:4873/traverse
npm http 200 http://192.168.1.100:4873/traverse
npm WARN deprecated graceful-fs@3.0.8: graceful-fs v3.0.0 and before will fail on node releases >= v7.0. Please update to graceful-fs@^4.0.0 as soon as possible. Use 'npm ls graceful-fs' to find it in the tree.
npm http request GET http://192.168.1.100:4873/over
npm http request GET http://192.168.1.100:4873/slice-stream
npm http 200 http://192.168.1.100:4873/over
npm http 200 http://192.168.1.100:4873/slice-stream
npm WARN EPACKAGEJSON install@0.0.1 No repository field.
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/forever-agent
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/express-pouchdb
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/bn.js
npm http request GET http://192.168.1.100:4873/leveldown-mobile
npm http request GET http://192.168.1.100:4873/proxyquire
npm http request GET http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/tape
npm http request GET http://192.168.1.100:4873/nock
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/pouchdb-node
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/request-promise
npm http request GET http://192.168.1.100:4873/sinon
npm http request GET http://192.168.1.100:4873/supertest
npm http request GET http://192.168.1.100:4873/supertest-as-promised
npm http request GET http://192.168.1.100:4873/tape-catch
npm http request GET http://192.168.1.100:4873/tmp
npm http request GET http://192.168.1.100:4873/uuid
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/forever-agent
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/express-pouchdb
npm http 200 http://192.168.1.100:4873/bn.js
npm http 200 http://192.168.1.100:4873/socket.io-client
npm http 304 http://192.168.1.100:4873/multiplex
npm http 200 http://192.168.1.100:4873/proxyquire
npm http 200 http://192.168.1.100:4873/randomstring
npm http 304 http://192.168.1.100:4873/tape
npm http 304 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/nock
npm http 304 http://192.168.1.100:4873/pouchdb-node
npm http 304 http://192.168.1.100:4873/leveldown-mobile
npm http 304 http://192.168.1.100:4873/js-extend
npm http 200 http://192.168.1.100:4873/request-promise
npm http 200 http://192.168.1.100:4873/supertest
npm http 200 http://192.168.1.100:4873/sinon
npm http 304 http://192.168.1.100:4873/uuid
npm http 304 http://192.168.1.100:4873/tmp
npm http 200 http://192.168.1.100:4873/supertest-as-promised
npm http 304 http://192.168.1.100:4873/tape-catch
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/raw-body
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/bytes
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/type-is
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/ms
npm http 200 http://192.168.1.100:4873/ms
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
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/etag
npm http 200 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/methods
npm http 200 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/send
npm http 304 http://192.168.1.100:4873/path-to-regexp
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
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/cookie-parser
npm http request GET http://192.168.1.100:4873/header-case-normalizer
npm http request GET http://192.168.1.100:4873/multiparty
npm http request GET http://192.168.1.100:4873/pouchdb-all-dbs
npm http request GET http://192.168.1.100:4873/pouchdb-auth
npm http request GET http://192.168.1.100:4873/pouchdb-find
npm http request GET http://192.168.1.100:4873/pouchdb-list
npm http request GET http://192.168.1.100:4873/pouchdb-replicator
npm http request GET http://192.168.1.100:4873/pouchdb-rewrite
npm http request GET http://192.168.1.100:4873/compression
npm http request GET http://192.168.1.100:4873/basic-auth
npm http request GET http://192.168.1.100:4873/pouchdb-show
npm http request GET http://192.168.1.100:4873/pouchdb-security
npm http request GET http://192.168.1.100:4873/pouchdb-size
npm http request GET http://192.168.1.100:4873/pouchdb-validation
npm http request GET http://192.168.1.100:4873/pouchdb-update
npm http request GET http://192.168.1.100:4873/pouchdb-vhost
npm http request GET http://192.168.1.100:4873/pouchdb-wrappers
npm http 304 http://192.168.1.100:4873/cookie-parser
npm http 304 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/multiparty
npm http 304 http://192.168.1.100:4873/pouchdb-auth
npm http 304 http://192.168.1.100:4873/pouchdb-list
npm http 304 http://192.168.1.100:4873/pouchdb-find
npm http 304 http://192.168.1.100:4873/header-case-normalizer
npm http 304 http://192.168.1.100:4873/pouchdb-all-dbs
npm http 304 http://192.168.1.100:4873/compression
npm http 304 http://192.168.1.100:4873/pouchdb-rewrite
npm http 304 http://192.168.1.100:4873/basic-auth
npm http 304 http://192.168.1.100:4873/pouchdb-show
npm http 304 http://192.168.1.100:4873/pouchdb-validation
npm http 304 http://192.168.1.100:4873/pouchdb-replicator
npm http 304 http://192.168.1.100:4873/pouchdb-security
npm http 304 http://192.168.1.100:4873/pouchdb-update
npm http 304 http://192.168.1.100:4873/pouchdb-vhost
npm http 304 http://192.168.1.100:4873/pouchdb-wrappers
npm http 304 http://192.168.1.100:4873/pouchdb-size
npm http request GET http://192.168.1.100:4873/setprototypeof
npm http 200 http://192.168.1.100:4873/setprototypeof
npm http request GET http://192.168.1.100:4873/on-headers
npm http request GET http://192.168.1.100:4873/compressible
npm http 304 http://192.168.1.100:4873/compressible
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
npm http 304 http://192.168.1.100:4873/tiny-queue
npm http 200 http://192.168.1.100:4873/argsarray
npm http 200 http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/base62
npm http 304 http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/base64url
npm http request GET http://192.168.1.100:4873/crypto-lite
npm http request GET http://192.168.1.100:4873/couchdb-calculate-session-id
npm http request GET http://192.168.1.100:4873/pouchdb-req-http-query
npm http request GET http://192.168.1.100:4873/pouchdb-plugin-error
npm http request GET http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http request GET http://192.168.1.100:4873/pouchdb
npm http request GET http://192.168.1.100:4873/pouchdb-system-db
npm http request GET http://192.168.1.100:4873/promise-nodify
npm http request GET http://192.168.1.100:4873/secure-random
npm http 200 http://192.168.1.100:4873/base64url
npm http 304 http://192.168.1.100:4873/crypto-lite
npm http 200 http://192.168.1.100:4873/pouchdb-plugin-error
npm http 304 http://192.168.1.100:4873/couchdb-calculate-session-id
npm http 304 http://192.168.1.100:4873/pouchdb-req-http-query
npm http 304 http://192.168.1.100:4873/promise-nodify
npm http 304 http://192.168.1.100:4873/secure-random
npm http 200 http://192.168.1.100:4873/pouchdb-system-db
npm http 304 http://192.168.1.100:4873/pouchdb
npm http 304 http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http request GET http://192.168.1.100:4873/meow
npm http request GET http://192.168.1.100:4873/concat-stream
npm http 200 http://192.168.1.100:4873/meow
npm http 304 http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/typedarray
npm http 200 http://192.168.1.100:4873/typedarray
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/camelcase-keys
npm http request GET http://192.168.1.100:4873/indent-string
npm http 304 http://192.168.1.100:4873/indent-string
npm http 304 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/camelcase-keys
npm http request GET http://192.168.1.100:4873/map-obj
npm http request GET http://192.168.1.100:4873/camelcase
npm http 304 http://192.168.1.100:4873/camelcase
npm http 200 http://192.168.1.100:4873/map-obj
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
npm http request GET http://192.168.1.100:4873/localstorage-down
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/memdown
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/pouchdb-collate
npm http request GET http://192.168.1.100:4873/scope-eval
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/vuvuzela
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http 200 http://192.168.1.100:4873/level-write-stream
npm http 200 http://192.168.1.100:4873/double-ended-queue
npm http 304 http://192.168.1.100:4873/through2
npm http 304 http://192.168.1.100:4873/localstorage-down
npm http 304 http://192.168.1.100:4873/es6-promise-pool
npm http 304 http://192.168.1.100:4873/fruitdown
npm http 304 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/memdown
npm http 200 http://192.168.1.100:4873/pouchdb-collections
npm http 200 http://192.168.1.100:4873/spark-md5
npm http 304 http://192.168.1.100:4873/scope-eval
npm http 200 http://192.168.1.100:4873/pouchdb-collate
npm http 304 http://192.168.1.100:4873/vuvuzela
npm http 200 http://192.168.1.100:4873/levelup
npm http 200 http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/d64
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http 200 http://192.168.1.100:4873/d64
npm http 200 http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/end-stream
npm http 304 http://192.168.1.100:4873/end-stream
npm http request GET http://192.168.1.100:4873/write-stream
npm http 200 http://192.168.1.100:4873/write-stream
npm http request GET http://192.168.1.100:4873/deferred-leveldown
npm http request GET http://192.168.1.100:4873/level-codec
npm http request GET http://192.168.1.100:4873/level-errors
npm http request GET http://192.168.1.100:4873/level-iterator-stream
npm http request GET http://192.168.1.100:4873/prr
npm http request GET http://192.168.1.100:4873/semver
npm http 200 http://192.168.1.100:4873/prr
npm http 200 http://192.168.1.100:4873/semver
npm http 200 http://192.168.1.100:4873/level-errors
npm http 200 http://192.168.1.100:4873/level-codec
npm http 200 http://192.168.1.100:4873/deferred-leveldown
npm http 200 http://192.168.1.100:4873/level-iterator-stream
npm http request GET http://192.168.1.100:4873/errno
npm http 200 http://192.168.1.100:4873/errno
npm http request GET http://192.168.1.100:4873/humble-localstorage
npm http 200 http://192.168.1.100:4873/humble-localstorage
npm http request GET http://192.168.1.100:4873/has-localstorage
npm http request GET http://192.168.1.100:4873/localstorage-memory
npm http 304 http://192.168.1.100:4873/has-localstorage
npm http 304 http://192.168.1.100:4873/localstorage-memory
npm http request GET http://192.168.1.100:4873/ltgt
npm http request GET http://192.168.1.100:4873/functional-red-black-tree
npm http 200 http://192.168.1.100:4873/ltgt
npm http 200 http://192.168.1.100:4873/functional-red-black-tree
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
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/is-typedarray
npm http request GET http://192.168.1.100:4873/aws4
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/tough-cookie
npm WARN deprecated tough-cookie@2.2.2: ReDoS vulnerability parsing Set-Cookie https://nodesecurity.io/advisories/130
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/aws4
npm http 200 http://192.168.1.100:4873/is-typedarray
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
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http 304 http://192.168.1.100:4873/supports-color
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-function
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/pinkie
npm http 200 http://192.168.1.100:4873/pinkie
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/hoek
npm http 304 http://192.168.1.100:4873/boom
npm http 304 http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/jsprim
npm http request GET http://192.168.1.100:4873/sshpk
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 200 http://192.168.1.100:4873/jsprim
npm http 200 http://192.168.1.100:4873/sshpk
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
npm http 200 http://192.168.1.100:4873/getpass
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
npm http 304 http://192.168.1.100:4873/random-uuid-v4
npm http 304 http://192.168.1.100:4873/couchdb-objects
npm http 304 http://192.168.1.100:4873/couchdb-eval
npm http request GET http://192.168.1.100:4873/is-empty
npm http 200 http://192.168.1.100:4873/is-empty
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/is-array
npm http request GET http://192.168.1.100:4873/pouchdb-upsert
npm http request GET http://192.168.1.100:4873/pouchdb-extend
npm http 304 http://192.168.1.100:4873/spark-md5
npm http 200 http://192.168.1.100:4873/is-array
npm http 304 http://192.168.1.100:4873/pouchdb-extend
npm http 304 http://192.168.1.100:4873/pouchdb-upsert
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 304 http://192.168.1.100:4873/unreachable-branch-transform
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
npm http 304 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/fast-future
npm http 304 http://192.168.1.100:4873/bindings
npm http 304 http://192.168.1.100:4873/abstract-leveldown
npm http 200 http://192.168.1.100:4873/fast-future
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
npm http request GET http://192.168.1.100:4873/propagate
npm http request GET http://192.168.1.100:4873/chai
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/deep-equal
npm http 304 http://192.168.1.100:4873/propagate
npm http 304 http://192.168.1.100:4873/lodash
npm WARN deprecated lodash@2.4.1: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
npm http 200 http://192.168.1.100:4873/chai
npm http request GET http://192.168.1.100:4873/assertion-error
npm http request GET http://192.168.1.100:4873/deep-eql
npm http request GET http://192.168.1.100:4873/type-detect
npm http 200 http://192.168.1.100:4873/deep-eql
npm http 304 http://192.168.1.100:4873/type-detect
npm http 304 http://192.168.1.100:4873/assertion-error
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/ip
npm http 304 http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-http
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-leveldb
npm http request GET http://192.168.1.100:4873/pouchdb-core
npm http request GET http://192.168.1.100:4873/pouchdb-mapreduce
npm http request GET http://192.168.1.100:4873/pouchdb-replication
npm http 304 http://192.168.1.100:4873/pouchdb-core
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-http
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-leveldb
npm http 304 http://192.168.1.100:4873/pouchdb-replication
npm http 304 http://192.168.1.100:4873/pouchdb-mapreduce
npm http request GET http://192.168.1.100:4873/pouchdb-ajax
npm http request GET http://192.168.1.100:4873/pouchdb-errors
npm http request GET http://192.168.1.100:4873/pouchdb-binary-utils
npm http request GET http://192.168.1.100:4873/pouchdb-md5
npm http request GET http://192.168.1.100:4873/pouchdb-utils
npm http 304 http://192.168.1.100:4873/pouchdb-errors
npm http 304 http://192.168.1.100:4873/pouchdb-ajax
npm http 304 http://192.168.1.100:4873/pouchdb-md5
npm http 304 http://192.168.1.100:4873/pouchdb-binary-utils
npm http 200 http://192.168.1.100:4873/pouchdb-utils
npm http request GET http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http 304 http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/leveldown
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-leveldb-core
npm http 200 http://192.168.1.100:4873/leveldown
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-leveldb-core
npm http request GET http://192.168.1.100:4873/nan
npm http request GET http://192.168.1.100:4873/prebuild
npm http 304 http://192.168.1.100:4873/nan
npm http 200 http://192.168.1.100:4873/prebuild
npm http request GET http://192.168.1.100:4873/expand-template
npm http request GET http://192.168.1.100:4873/ghreleases
npm http request GET http://192.168.1.100:4873/github-from-package
npm http request GET http://192.168.1.100:4873/noop-logger
npm http request GET http://192.168.1.100:4873/node-ninja
npm http request GET http://192.168.1.100:4873/npmlog
npm http request GET http://192.168.1.100:4873/os-homedir
npm http request GET http://192.168.1.100:4873/node-gyp
npm http request GET http://192.168.1.100:4873/pump
npm http request GET http://192.168.1.100:4873/rc
npm http request GET http://192.168.1.100:4873/simple-get
npm http request GET http://192.168.1.100:4873/tar-fs
npm http request GET http://192.168.1.100:4873/tar-stream
npm http 200 http://192.168.1.100:4873/expand-template
npm http 200 http://192.168.1.100:4873/github-from-package
npm http 200 http://192.168.1.100:4873/noop-logger
npm http 200 http://192.168.1.100:4873/node-ninja
npm http 200 http://192.168.1.100:4873/ghreleases
npm http 200 http://192.168.1.100:4873/npmlog
npm http 200 http://192.168.1.100:4873/os-homedir
npm http 200 http://192.168.1.100:4873/node-gyp
npm http 200 http://192.168.1.100:4873/pump
npm http 200 http://192.168.1.100:4873/rc
npm http 200 http://192.168.1.100:4873/simple-get
npm http 200 http://192.168.1.100:4873/tar-fs
npm http 200 http://192.168.1.100:4873/tar-stream
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/ghrepos
npm http request GET http://192.168.1.100:4873/ghutils
npm http request GET http://192.168.1.100:4873/simple-mime
npm http request GET http://192.168.1.100:4873/url-template
npm http 200 http://192.168.1.100:4873/ghrepos
npm http 304 http://192.168.1.100:4873/after
npm http 200 http://192.168.1.100:4873/ghutils
npm http 200 http://192.168.1.100:4873/url-template
npm http 200 http://192.168.1.100:4873/simple-mime
npm http request GET http://192.168.1.100:4873/jsonist
npm http 200 http://192.168.1.100:4873/jsonist
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/hyperquest
npm http 304 http://192.168.1.100:4873/bl
npm http 200 http://192.168.1.100:4873/hyperquest
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/duplexer2
npm http 200 http://192.168.1.100:4873/duplexer2
npm http request GET http://192.168.1.100:4873/fstream
npm http request GET http://192.168.1.100:4873/nopt
npm http request GET http://192.168.1.100:4873/osenv
npm http request GET http://192.168.1.100:4873/path-array
npm http request GET http://192.168.1.100:4873/tar
npm http request GET http://192.168.1.100:4873/which
npm http 304 http://192.168.1.100:4873/fstream
npm http 200 http://192.168.1.100:4873/path-array
npm http 200 http://192.168.1.100:4873/which
npm http 200 http://192.168.1.100:4873/osenv
npm http 200 http://192.168.1.100:4873/tar
npm http 200 http://192.168.1.100:4873/nopt
npm http request GET http://192.168.1.100:4873/abbrev
npm http 304 http://192.168.1.100:4873/abbrev
npm http request GET http://192.168.1.100:4873/are-we-there-yet
npm http request GET http://192.168.1.100:4873/ansi
npm http request GET http://192.168.1.100:4873/gauge
npm http 200 http://192.168.1.100:4873/are-we-there-yet
npm http 200 http://192.168.1.100:4873/ansi
npm http 200 http://192.168.1.100:4873/gauge
npm http request GET http://192.168.1.100:4873/delegates
npm http 200 http://192.168.1.100:4873/delegates
npm http request GET http://192.168.1.100:4873/has-unicode
npm http request GET http://192.168.1.100:4873/lodash.pad
npm http request GET http://192.168.1.100:4873/lodash.padend
npm http request GET http://192.168.1.100:4873/lodash.padstart
npm http 200 http://192.168.1.100:4873/has-unicode
npm http 200 http://192.168.1.100:4873/lodash.pad
npm http 200 http://192.168.1.100:4873/lodash.padend
npm http 200 http://192.168.1.100:4873/lodash.padstart
npm http request GET http://192.168.1.100:4873/os-tmpdir
npm http 304 http://192.168.1.100:4873/os-tmpdir
npm http request GET http://192.168.1.100:4873/array-index
npm http 200 http://192.168.1.100:4873/array-index
npm http request GET http://192.168.1.100:4873/es6-symbol
npm http 200 http://192.168.1.100:4873/es6-symbol
npm http request GET http://192.168.1.100:4873/d
npm http request GET http://192.168.1.100:4873/es5-ext
npm http 200 http://192.168.1.100:4873/d
npm http 200 http://192.168.1.100:4873/es5-ext
npm http request GET http://192.168.1.100:4873/es6-iterator
npm http 200 http://192.168.1.100:4873/es6-iterator
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 304 http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/block-stream
npm http 200 http://192.168.1.100:4873/block-stream
npm http request GET http://192.168.1.100:4873/isexe
npm http 200 http://192.168.1.100:4873/isexe
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http 304 http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/ini
npm http request GET http://192.168.1.100:4873/deep-extend
npm http 304 http://192.168.1.100:4873/strip-json-comments
npm http 200 http://192.168.1.100:4873/deep-extend
npm http 200 http://192.168.1.100:4873/ini
npm WARN engine deep-extend@0.4.1: wanted: {"node":">=0.12.0","iojs":">=1.0.0"} (current: {"node":"0.10.40","npm":"3.3.12"})
npm http request GET http://192.168.1.100:4873/unzip-response
npm http 200 http://192.168.1.100:4873/unzip-response
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/pouchdb-json
npm http request GET http://192.168.1.100:4873/pouchdb-merge
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-utils
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-utils
npm http 304 http://192.168.1.100:4873/sublevel-pouchdb
npm http 304 http://192.168.1.100:4873/pouchdb-json
npm http 304 http://192.168.1.100:4873/pouchdb-merge
npm http request GET http://192.168.1.100:4873/ltgt
npm http 304 http://192.168.1.100:4873/ltgt
npm http request GET http://192.168.1.100:4873/pouchdb-mapreduce-utils
npm http 304 http://192.168.1.100:4873/pouchdb-mapreduce-utils
npm http request GET http://192.168.1.100:4873/pouchdb-checkpointer
npm http request GET http://192.168.1.100:4873/pouchdb-generate-replication-id
npm http 304 http://192.168.1.100:4873/pouchdb-checkpointer
npm http 304 http://192.168.1.100:4873/pouchdb-generate-replication-id
npm http request GET http://192.168.1.100:4873/module-not-found-error
npm http request GET http://192.168.1.100:4873/fill-keys
npm http 200 http://192.168.1.100:4873/fill-keys
npm http 200 http://192.168.1.100:4873/module-not-found-error
npm http request GET http://192.168.1.100:4873/is-object
npm http 200 http://192.168.1.100:4873/is-object
npm http request GET http://192.168.1.100:4873/array-uniq
npm http 200 http://192.168.1.100:4873/array-uniq
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/samsam
npm http request GET http://192.168.1.100:4873/formatio
npm http request GET http://192.168.1.100:4873/util
npm http request GET http://192.168.1.100:4873/lolex
npm http 200 http://192.168.1.100:4873/lolex
npm http 200 http://192.168.1.100:4873/samsam
npm http 304 http://192.168.1.100:4873/util
npm http 200 http://192.168.1.100:4873/formatio
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
npm http request GET http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/component-bind
npm http 304 http://192.168.1.100:4873/socket.io-parser
npm http 304 http://192.168.1.100:4873/component-emitter
npm http 304 http://192.168.1.100:4873/engine.io-client
npm http 304 http://192.168.1.100:4873/object-component
npm http 304 http://192.168.1.100:4873/indexof
npm http 304 http://192.168.1.100:4873/parseuri
npm http 304 http://192.168.1.100:4873/has-binary
npm http 304 http://192.168.1.100:4873/to-array
npm http 304 http://192.168.1.100:4873/backo2
npm http 304 http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/parseqs
npm http request GET http://192.168.1.100:4873/ws
npm http fetch GET https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http 304 http://192.168.1.100:4873/parsejson
npm http 304 http://192.168.1.100:4873/component-inherit
npm http 304 http://192.168.1.100:4873/engine.io-parser
npm http 304 http://192.168.1.100:4873/parseqs
npm http 304 http://192.168.1.100:4873/has-cors
npm http 304 http://192.168.1.100:4873/ws
npm http fetch 200 https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/utf8
npm http 304 http://192.168.1.100:4873/blob
npm http 304 http://192.168.1.100:4873/arraybuffer.slice
npm http 304 http://192.168.1.100:4873/base64-arraybuffer
npm http 304 http://192.168.1.100:4873/utf8
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
npm http 200 http://192.168.1.100:4873/superagent
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/reduce-component
npm http request GET http://192.168.1.100:4873/formidable
npm http request GET http://192.168.1.100:4873/cookiejar
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/form-data
npm http 200 http://192.168.1.100:4873/reduce-component
npm http 304 http://192.168.1.100:4873/formidable
npm http 200 http://192.168.1.100:4873/cookiejar
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/combined-stream
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
npm http 304 http://192.168.1.100:4873/resumer
npm http 200 http://192.168.1.100:4873/object-inspect
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
npm ERR! Test failed.  See above for more details.

```

Error: Command failed: cp: testBuildOrg//.git/objects/9c/558e357c41674e39880abb6c3209e539de42e2: No such file or directory
cp: testBuildOrg//.git/objects/9c/560864575e93a8f8b728faeb71009703e9d58c: No such file or directory
cp: testBuildOrg//.git/objects/9c/5a3ba5aa1a9a903982985623573bbaf3f4f545: No such file or directory
cp: testBuildOrg//.git/objects/9c/5be7335aa574f9fe65e38fd9211db6322313a2: No such file or directory
cp: testBuildOrg//.git/objects/9c/5c74933221490599638313c65d58aa784ddd48: No such file or directory
cp: testBuildOrg//.git/objects/9c/5fb24996524f3cd91f6ea8aa63093b6e9d9f7f: No such file or directory
cp: testBuildOrg//.git/objects/9c/60a3ee147f45d1ab26df82ac1ebbe0947c49f8: No such file or directory
cp: testBuildOrg//.git/objects/9c/612424b341739c062a88059fdd872bc170c0cd: No such file or directory
cp: testBuildOrg//.git/objects/9c/61b918185efde06cce0c13854487f8c98887c3: No such file or directory
cp: testBuildOrg//.git/objects/9c/62280d81b834be794b34d39a76691f1bb21e99: No such file or directory
cp: testBuildOrg//.git/objects/9c/71b3badca23986e9b8644800caf719b3892ef0: No such file or directory
cp: testBuildOrg//.git/objects/9c/73de9430430be2ddad3c1c3e13fa175097aa08: No such file or directory
cp: testBuildOrg//.git/objects/9c/7ecf1268ed8d4d5669662250fd4b1e62758c8e: No such file or directory
cp: testBuildOrg//.git/objects/9c/87be5c7ec1db0e5cf4aa0c4533e663831af768: No such file or directory
cp: testBuildOrg//.git/objects/9c/89154a6b22ac746063aa6b1b126e2d9fd033b4: No such file or directory
cp: testBuildOrg//.git/objects/9c/893638b02eef82f9b5a9c6fe893d1b8af3fdbe: No such file or directory
cp: testBuildOrg//.git/objects/9c/89fa44483728eff07b195490ce6e6f3289a83f: No such file or directory
cp: testBuildOrg//.git/objects/9c/8a3f4b5357bed9669b514f5fef22bce63174c6: No such file or directory
cp: testBuildOrg//.git/objects/9c/91ee57ad376bf4ca61d668c67a3526abb7e8f9: No such file or directory
cp: testBuildOrg//.git/objects/9c/a045e02a072a0f8df80573ddaf6e1fa33eba68: No such file or directory
cp: testBuildOrg//.git/objects/9c/a27ce9e9811e6633e54052eeffc7bbdf947f95: No such file or directory
cp: testBuildOrg//.git/objects/9c/a3c7f49baf1bd0b903cd14dd77084bbfbde372: No such file or directory
cp: testBuildOrg//.git/objects/9c/ac5b5f594e268e42cd561dd1fea60e5a419649: No such file or directory
cp: testBuildOrg//.git/objects/9c/ae33a297fee1a388dbd081b1c9974e2b36bffb: No such file or directory
cp: testBuildOrg//.git/objects/9c/b0282ebd75f67bad3e92a60a5c8a7480582df8: No such file or directory
cp: testBuildOrg//.git/objects/9c/b2f94dec0a82613de5df97047741a203ef734e: No such file or directory
cp: testBuildOrg//.git/objects/9c/bac6a011e0a5bf7001184ffa6d82c91e9fbfee: No such file or directory
cp: testBuildOrg//.git/objects/9c/c07aa7e0ba46b38a396d2b0d0a06608b579fdc: No such file or directory
cp: testBuildOrg//.git/objects/9c/c6f1cfc649a17e5c99d43776985e6458f7de42: No such file or directory
cp: testBuildOrg//.git/objects/9c/c7df1e6e6f54e9f1da32895ebc5a87f5cae386: No such file or directory
cp: testBuildOrg//.git/objects/9c/ce6456e5a1a28cbac65ac8b55f51290ccd24a2: No such file or directory
cp: testBuildOrg//.git/objects/9c/d652f9be64b96acc0889731461a7d248c61299: No such file or directory
cp: testBuildOrg//.git/objects/9c/d874398a65023948f270e26e6e15dc70c1c4af: No such file or directory
cp: testBuildOrg//.git/objects/9c/e4518abd6afd9ef2fc38acec1742edc4331af5: No such file or directory
cp: testBuildOrg//.git/objects/9c/f16222f041f58b74666144496811a0603580de: No such file or directory
cp: testBuildOrg//.git/objects/9c/fb3a28e1f38e17de834d6d9b55d20ae616e89d: No such file or directory
cp: testBuildOrg//.git/objects/9c/fe3b62c8da9b28a40b390bd0cd5631361f4199: No such file or directory
cp: testBuildOrg//.git/objects/a8/d7abe6d2340ab89447ced4917a44c430b6a710: No such file or directory
cp: testBuildOrg//.git/objects/a8/e4b01e3c3965bde68df812c9b88fa668348070: No such file or directory
cp: testBuildOrg//.git/objects/a8/f29bf75a0369a8ed40e8a0fbeb9c13dc7e7f42: No such file or directory
cp: testBuildOrg//.git/objects/a8/f658f14eb4fd5a0716eccd101631ac41f0bb0e: No such file or directory
cp: testBuildOrg//.git/objects/a9/6e324cfa03ba588d9957a55a989c992ac934eb: No such file or directory
cp: testBuildOrg//.git/objects/a9/784c2972ad7905f95a77fc8fdbc2e84ae0e2e5: No such file or directory
cp: testBuildOrg//.git/objects/a9/7b769e3e5b275e9cb92f7a5d00840b85d44fe3: No such file or directory
cp: testBuildOrg//.git/objects/a9/7c4156995a27e4501d9ee2c8ee66b183f16664: No such file or directory
cp: testBuildOrg//.git/objects/a9/7e458ca3043946b2b8fdd1091019a2d1bb5a03: No such file or directory
cp: testBuildOrg//.git/objects/a9/80235e96dab80a2463634caca28be53e7253a9: No such file or directory
cp: testBuildOrg//.git/objects/a9/8c1d2fae9cebaeeef7ab03d5a8526d15e26b3b: No such file or directory
cp: testBuildOrg//.git/objects/a9/928e773b5947b5a56f2bda8fe67306c665f623: No such file or directory
cp: testBuildOrg//.git/objects/a9/ac1fa3b14369589095f9b15baecd60e8485a7a: No such file or directory
cp: testBuildOrg//.git/objects/a9/b0c66f04c6c56b05e364141fe82666ae875b21: No such file or directory
cp: testBuildOrg//.git/objects/a9/b43e85de5e278b46cf423e80d335c63f1893db: No such file or directory
cp: testBuildOrg//.git/objects/a9/bbbdda6f45fdab24529e9e09466705788f1a75: No such file or directory
cp: testBuildOrg//.git/objects/a9/bd21e532806eabb47887f79f88906c5f322a3f: No such file or directory
cp: testBuildOrg//.git/objects/a9/c9b2f21cd7ea0b87b908c097e1c08b9b048b9f: No such file or directory
cp: testBuildOrg//.git/objects/a9/c9dc7289447b8159c840d1edf5b1af403405f2: No such file or directory
cp: testBuildOrg//.git/objects/a9/cbef23af3991a25174b409e3716d875cba66d0: No such file or directory
cp: testBuildOrg//.git/objects/a9/cf2029346ad4e6159e25378908755cadb11abf: No such file or directory
cp: testBuildOrg//.git/objects/a9/db8a3572a75794b215c435adfafd79c9c456a8: No such file or directory
cp: testBuildOrg//.git/objects/a9/e42bba40137d94cd4ced6c1d204af1dd075984: No such file or directory
cp: testBuildOrg//.git/objects/a9/e62a349c8ea5165762da05a4197cfe56b2f019: No such file or directory
cp: testBuildOrg//.git/objects/a9/e83831555efe3b9f4c1ff093398b48b571a1e6: No such file or directory
cp: testBuildOrg//.git/objects/a9/f7756c8390f7b6f8cb985e82bffc7aa6aa4b62: No such file or directory
cp: testBuildOrg//.git/objects/a9/f86f0e7a851628c3c07035b3f0d7c13fe8b552: No such file or directory
cp: testBuildOrg//.git/objects/aa/301c2251128c2015276861382161f1ba5a8f13: No such file or directory
cp: testBuildOrg//.git/objects/aa/30ae2ded039fb3b77c1317bcd71ff76c63fd75: No such file or directory
cp: testBuildOrg//.git/objects/aa/30fe81b8a71e1f74c6cf8dbaac96bcf54e6b0b: No such file or directory
cp: testBuildOrg//.git/objects/aa/3bd361cd85d0d85ca6c6d04a096ae6476ba16e: No such file or directory
cp: testBuildOrg//.git/objects/aa/3e2d78e8bad8dc2534bffa10dc5be7011ea3a3: No such file or directory
cp: testBuildOrg//.git/objects/aa/4323293f47d0d9e2dd21b1cb6180227c64f003: No such file or directory
cp: testBuildOrg//.git/objects/aa/4a6e322e14838f73e3f3b49ea16ca076ec394a: No such file or directory
cp: testBuildOrg//.git/objects/aa/5627958c8a18dc6ca29f5ccaa6dc45a0e6aafd: No such file or directory
cp: testBuildOrg//.git/objects/aa/567886768069e7b8dd05fda619083f4add29cb: No such file or directory
cp: testBuildOrg//.git/objects/aa/56850e4c213cc63aa1579cf0d7fec8ab230a0b: No such file or directory
cp: testBuildOrg//.git/objects/aa/6916a9ac35d6ccc907aaffd51868763443e2fd: No such file or directory
cp: testBuildOrg//.git/objects/aa/7739e72f869123ef829310b7f18580876397e1: No such file or directory
cp: testBuildOrg//.git/objects/aa/7cc9239be58ef4393531be653a71d6ac649b48: No such file or directory
cp: testBuildOrg//.git/objects/aa/93e39a3032f0bd057822ebfc5a7ce7f75656aa: No such file or directory
cp: testBuildOrg//.git/objects/aa/98d07a791da0627f7c6fd98f3c42b50bceae49: No such file or directory
cp: testBuildOrg//.git/objects/aa/9f129219217c51c038ffbff1dbe21ee3c3ac3c: No such file or directory
cp: testBuildOrg//.git/objects/aa/a0562a99e1a2742c54cd112fcc3a750e7341c8: No such file or directory
cp: testBuildOrg//.git/objects/aa/a35171cac2d30edeafd32900ca47afd6b5e76a: No such file or directory
cp: testBuildOrg//.git/objects/aa/a3c6244b02b097803f6b07b1daaba00d510e5a: No such file or directory
cp: testBuildOrg//.git/objects/aa/a3c96c24f98a713a6460981df1392cc6b9bd6e: No such file or directory
cp: testBuildOrg//.git/objects/aa/a41b7e8d7c84918dbca9d45fd020df76f20971: No such file or directory
cp: testBuildOrg//.git/objects/aa/aa6912fc94aec5d0c6c048a7139b732e9faa23: No such file or directory
cp: testBuildOrg//.git/objects/aa/c134fb0b18f36e4dd51d38c6419ce34855ee90: No such file or directory
cp: testBuildOrg//.git/objects/aa/c35f15996990893f8c18c9a0af3193e5171ba5: No such file or directory
cp: testBuildOrg//.git/objects/aa/c82a09b3fd9ff5ca728a8eebbcb0fb95b2905c: No such file or directory
cp: testBuildOrg//.git/objects/aa/d2ff3928ed20067363c1a9e646d97297bcd49b: No such file or directory
cp: testBuildOrg//.git/objects/aa/d5c893539d0d372255d85c0bd7443351aa8e78: No such file or directory
cp: testBuildOrg//.git/objects/aa/e328d7aa0ad2c48057b05ff7bd5a3f9705816e: No such file or directory
cp: testBuildOrg//.git/objects/aa/e7080b5fad28a88452469c339394bfbe8b5582: No such file or directory
cp: testBuildOrg//.git/objects/aa/eb160e56581a781e00e0f329573b9894985afc: No such file or directory
cp: testBuildOrg//.git/objects/aa/f5b26e189de940b58af7e0b7f382d479ce287d: No such file or directory
cp: testBuildOrg//.git/objects/aa/fa7ca1539a6c25a85ba831f9e0c7e2afa73166: No such file or directory
cp: testBuildOrg//.git/objects/aa/fd65f357fb432a08b275d3e17654b1867cd0d6: No such file or directory
cp: testBuildOrg//.git/objects/aa/ffc484296f31a18c4d59300e150eef0d101784: No such file or directory
cp: testBuildOrg//.git/objects/ab/ed9be56909c92d0de97d7252d4960abdc12c2b: No such file or directory
cp: testBuildOrg//.git/objects/ab/edf605fef945575b4409f8a08268e21da52c6a: No such file or directory
cp: testBuildOrg//.git/objects/ab/f85dffc996d80c1f0d739ef1ef61e4459fe29f: No such file or directory
cp: testBuildOrg//.git/objects/ab/f99dd3f0c68e2f4fdbf397010985adcb3fa757: No such file or directory
cp: testBuildOrg//.git/objects/ab/fc33ebcb18d5de50aec64cd082a8e31620346e: No such file or directory
cp: testBuildOrg//.git/objects/ab/ffe1101e964879593443f6013e8f138c8f995f: No such file or directory
cp: testBuildOrg//.git/objects/ae/163044ab51d4287d0d0a5ad786ee4b93a18bcc: No such file or directory
cp: testBuildOrg//.git/objects/ae/1703d6bfb3dbb58d63ccbf4cdaca36a6994e85: No such file or directory
cp: testBuildOrg//.git/objects/ae/1a75db20d2f624f7be589da990e5ef0ef653dd: No such file or directory
cp: testBuildOrg//.git/objects/ae/295f392fb49f2ead2e97aca1b53e77e8755cfb: No such file or directory
cp: testBuildOrg//.git/objects/ae/2c96674f3c97c2f3c81cad10cc4a691a61f8fc: No such file or directory
cp: testBuildOrg//.git/objects/ae/31ccce9186a2a2d69d05aa9717f83c71e4f954: No such file or directory
cp: testBuildOrg//.git/objects/ae/32d3f9e02c71284317495a3d1ef79eb98a98b1: No such file or directory
cp: testBuildOrg//.git/objects/ae/51cc157f15ac037787987678e072001bf2bdd0: No such file or directory
cp: testBuildOrg//.git/objects/ae/52a62e55f0a314c56e9500e09f02ac1c9bdad6: No such file or directory
cp: testBuildOrg//.git/objects/ae/58f774b1fd895a31233051b5a10598ea3886cf: No such file or directory
cp: testBuildOrg//.git/objects/ae/5e9980058317cea96cc38ac4e6ff988f86e773: No such file or directory
cp: testBuildOrg//.git/objects/ae/6319362837929f4da315e41e65b6c97408d099: No such file or directory
cp: testBuildOrg//.git/objects/ae/6bca068381ccd78a1c9653e83771add7fc3a15: No such file or directory
cp: testBuildOrg//.git/objects/ae/834132d4a06e64dd4449a64143965058182403: No such file or directory
cp: testBuildOrg//.git/objects/ae/8c494e1425ffef45ed24f606fda5b4d515b974: No such file or directory
cp: testBuildOrg//.git/objects/ae/8d1c67e72f9e1e5159782e8aee0b90b9fd74eb: No such file or directory
cp: testBuildOrg//.git/objects/ae/90032ff449339099c612f0c4209249ad7bc4ab: No such file or directory
cp: testBuildOrg//.git/objects/ae/9167462d4cbf45036b7a3500595131d44d7ba8: No such file or directory
cp: testBuildOrg//.git/objects/ae/930729b4144eb2e9b5d630a314fc5c93001ce7: No such file or directory
cp: testBuildOrg//.git/objects/ae/95041a9208e2a9b52d640cefa36db11a109f93: No such file or directory
cp: testBuildOrg//.git/objects/ae/95360d487301789b8aa447ac44194ebebb8788: No such file or directory
cp: testBuildOrg//.git/objects/ae/9830ce52182184e0c1d052cb238b105dd4bfbd: No such file or directory
cp: testBuildOrg//.git/objects/ae/9b385d09cfc2ebea8f1b98dcd3d34f549f00d6: No such file or directory
cp: testBuildOrg//.git/objects/ae/a7c0ece77565d35f9a1323cbd95c2aba09cd08: No such file or directory
cp: testBuildOrg//.git/objects/ae/b9befdda901bafc033f501ea4a6d9a38651c39: No such file or directory
cp: testBuildOrg//.git/objects/ae/c19f2f3d00ca1a5104e3a36405e2aeef75d403: No such file or directory
cp: testBuildOrg//.git/objects/ae/c8023dc6638129c5790f6992510e055c3f7a5b: No such file or directory
cp: testBuildOrg//.git/objects/ae/dcce72e2f80480394d23d9b32750847b7abad7: No such file or directory
cp: testBuildOrg//.git/objects/ae/e40209e7c770672c02a0c957cfb72804d6aca3: No such file or directory
cp: testBuildOrg//.git/objects/ae/eb190353afb9c9690902131f68b1c7c4c39c81: No such file or directory
cp: testBuildOrg//.git/objects/ae/ecb4b984ff55304a242d4d81dcca56a9875390: No such file or directory
cp: testBuildOrg//.git/objects/ae/f3d766f86f9f75bd5c55a1ac880d4dc5840eec: No such file or directory
cp: testBuildOrg//.git/objects/ae/fbd2ef8f862f2492947727baf5fa0e50a4e991: No such file or directory
cp: testBuildOrg//.git/objects/ae/fed65677c67a567739ef52c1b3a935ce9d5d1a: No such file or directory
cp: testBuildOrg//.git/objects/af/2c956691278cba05c8968a23e9d1a425a35944: No such file or directory
cp: testBuildOrg//.git/objects/af/34780bcd5d156771ade907d3650b654c7e349a: No such file or directory
cp: testBuildOrg//.git/objects/af/35f5880575071570c1df6646b597bad01b2101: No such file or directory
cp: testBuildOrg//.git/objects/af/3b2c456087815ab65402f47b4372036a975dfe: No such file or directory
cp: testBuildOrg//.git/objects/af/451c0cb8a4190d652a43d9c9c424c2c270f488: No such file or directory
cp: testBuildOrg//.git/objects/af/4a7e87a1a4863e5bf17492f1b46a33f43734d5: No such file or directory
cp: testBuildOrg//.git/objects/af/4ba54a7b27a6623711eb794d938ba3f9069740: No such file or directory
cp: testBuildOrg//.git/objects/af/50e5e423ce2634d7948e32e4f3ea0156fbb344: No such file or directory
cp: testBuildOrg//.git/objects/af/643a3189cd54b89029ff2323a03161815d1653: No such file or directory
cp: testBuildOrg//.git/objects/af/6b7599d9e1f3bfba1ca01aa0f14e8f97a0124c: No such file or directory
cp: testBuildOrg//.git/objects/af/6c07b8efff14e1dfbe82139e421d168f29142c: No such file or directory
cp: testBuildOrg//.git/objects/af/797b87c5026b813154d94d723e51f69867502e: No such file or directory
cp: testBuildOrg//.git/objects/af/8192de24c6735e87cd7c745b851d53be4b04ef: No such file or directory
cp: testBuildOrg//.git/objects/af/81f3cf2d6e11e8016193290247e076d39fcc79: No such file or directory
cp: testBuildOrg//.git/objects/af/971393f2f69eea8fbee4649e3271e215e647af: No such file or directory
cp: testBuildOrg//.git/objects/af/97a777cc2c71bd4802821a29f169015a1bf1d3: No such file or directory
cp: testBuildOrg//.git/objects/af/9f0015229df34f87de06ae435e14225edf7924: No such file or directory
cp: testBuildOrg//.git/objects/af/a1391849ecf824af592da31c321aca4f065212: No such file or directory
cp: testBuildOrg//.git/objects/af/a53c9dedaed32e42aadaea5308ae27b3a8469c: No such file or directory
cp: testBuildOrg//.git/objects/af/a71b18fcb8a97e4bf6619343c49ca07b27f509: No such file or directory
cp: testBuildOrg//.git/objects/af/af1d71e254cdda304399921d7b59956e487a08: No such file or directory
cp: testBuildOrg//.git/objects/af/af6eb57cdf45c9ea58787e543580f138524813: No such file or directory
cp: testBuildOrg//.git/objects/af/b8ab2574927ee62f22705bfea7f4d8a6755ab0: No such file or directory
cp: testBuildOrg//.git/objects/af/c362153b4915a973015c5a125bfb1c09d444e1: No such file or directory
cp: testBuildOrg//.git/objects/af/c4b959e45d1ee70cac4c94e4ed58458ca75097: No such file or directory
cp: testBuildOrg//.git/objects/af/ca3379eb9aafb8704571cb5d7ee36ff0197a9a: No such file or directory
cp: testBuildOrg//.git/objects/af/cf2d1b354517105b6c9aaced37b823b0374066: No such file or directory
cp: testBuildOrg//.git/objects/af/d4f67b6751f39cb0f1188a4826cca8ed5792c6: No such file or directory
cp: testBuildOrg//.git/objects/af/e67cbbf007cc656b883930e1a956510c5fc59d: No such file or directory
cp: testBuildOrg//.git/objects/af/e89f1e73ac1c2d2304cf3b01754df8dac40118: No such file or directory
cp: testBuildOrg//.git/objects/af/eb1f40f0bfa7af7017ec95f75e2da629ecf01d: No such file or directory
cp: testBuildOrg//.git/objects/af/ecdbf60ce8e0d5e06ccf6f4778d563fbb75006: No such file or directory
cp: testBuildOrg//.git/objects/af/ee8df5ea7376aabbdb2e17d9676417a894c2f2: No such file or directory
cp: testBuildOrg//.git/objects/af/f10f5e8df4b108ad5976a3c293daa6d01275f6: No such file or directory
cp: testBuildOrg//.git/objects/af/f19f44e6d03699b0783e60140bc4465f817c39: No such file or directory
cp: testBuildOrg//.git/objects/af/f41e16d92dc44851c28fe5973901982e3b4ef4: No such file or directory
cp: testBuildOrg//.git/objects/af/ff9c516b16675f1a5f46fe28392ec470a579e8: No such file or directory
cp: testBuildOrg//.git/objects/b0/36308b6ed9d9491a2e3c3cd15ec351da15f5d2: No such file or directory
cp: testBuildOrg//.git/objects/b0/394d036476e9be750ae35cdd1d49e7b433956a: No such file or directory
cp: testBuildOrg//.git/objects/b0/3c61c66bd120a0369bc506c1d9525abe0e8cbe: No such file or directory
cp: testBuildOrg//.git/objects/b0/3d0653f2fc896ae9e7ce9d041e35666babbc14: No such file or directory
cp: testBuildOrg//.git/objects/b0/3f0ac18b4f44a1abf4d0962a04597deb821216: No such file or directory
cp: testBuildOrg//.git/objects/b0/43bea9e9588c07e9afdff237f27beae2af6fe8: No such file or directory
cp: testBuildOrg//.git/objects/b0/4e07539990621be3348922e8422e06efa73a38: No such file or directory
cp: testBuildOrg//.git/objects/b0/4e3e50f9b9ef4222fa9e9d11e8e2a9dcf59ddc: No such file or directory
cp: testBuildOrg//.git/objects/b0/4f17e1f569b06583a60eea93134aef2448ea40: No such file or directory
cp: testBuildOrg//.git/objects/b0/527faeeb33e3ea29dde1a01b6c7d6e1f544220: No such file or directory
cp: testBuildOrg//.git/objects/b0/57e931d31ce8f9583a76b8988ea5eb66aa2bba: No such file or directory
cp: testBuildOrg//.git/objects/b0/5bb1df422d81a3d999a227a76044254eb94526: No such file or directory
cp: testBuildOrg//.git/objects/b0/667f44deecaa766b12879cbf355dd30166cbd8: No such file or directory
cp: testBuildOrg//.git/objects/b0/71672b79840107fe7c1e7d2157a63bf4235879: No such file or directory
cp: testBuildOrg//.git/objects/b0/763ea1696298020aca4f59fed2bf40d77674c5: No such file or directory
cp: testBuildOrg//.git/objects/b0/768aef252629aa42408bee46c5099ed39efcca: No such file or directory
cp: testBuildOrg//.git/objects/b0/7841c1670bf397e8725698b63986182c31346e: No such file or directory
cp: testBuildOrg//.git/objects/b0/7f714ba68bd8b6d67814a2c7b0150eaf98f16d: No such file or directory
cp: testBuildOrg//.git/objects/b0/803eb0e1c6d9cbc09cbdd54d4f0d3def2b80cc: No such file or directory
cp: testBuildOrg//.git/objects/b0/8c1c4abb94328b210166247f314a8358f85709: No such file or directory
cp: testBuildOrg//.git/objects/b0/8ea6c9e146e7fb57f9ed87c73f0d4857e28c75: No such file or directory
cp: testBuildOrg//.git/objects/b0/9cdc24ddd9e67c1d3e2d8709d047db08850c10: No such file or directory
cp: testBuildOrg//.git/objects/b0/9da68968015e738f82805b0fbb53cf06dc2a17: No such file or directory
cp: testBuildOrg//.git/objects/b0/a49be1d48de3a23ef2f86f952dcd6b70a63f72: No such file or directory
cp: testBuildOrg//.git/objects/b0/ab3f22d07c3774e93c2eee5616217ba513b2d5: No such file or directory
cp: testBuildOrg//.git/objects/b0/b30a8d686e735a859f479ac193437fa8a06b98: No such file or directory
cp: testBuildOrg//.git/objects/b0/c93129f33bdc82ee4cf124f63a83dade18d60f: No such file or directory
cp: testBuildOrg//.git/objects/b0/d2de7da760a77e871c6abbbd6a5991a153a6d6: No such file or directory
cp: testBuildOrg//.git/objects/b0/de729a777c26b6c2d6ee2b3b4b585fd3be76fb: No such file or directory
cp: testBuildOrg//.git/objects/b0/deb165d127c028022d1663200ae8eb49fe420a: No such file or directory
cp: testBuildOrg//.git/objects/b0/e0167af82821b4eaa18f3509a715515522c12d: No such file or directory
cp: testBuildOrg//.git/objects/b0/e3f6454199c37c3021517389600e60f487ed32: No such file or directory
cp: testBuildOrg//.git/objects/b0/ebb78e6b448264cc578767dd453b3c7ca7d15e: No such file or directory
cp: testBuildOrg//.git/objects/b0/f4c8ad187817b13863a99bc2543443242cdb89: No such file or directory
cp: testBuildOrg//.git/objects/b1/3276f6a8747407ab3a0a6e4aed1dbcd46bfaa1: No such file or directory
cp: testBuildOrg//.git/objects/b1/350b0bfc263fb2bd4652ca873165586f098e56: No such file or directory
cp: testBuildOrg//.git/objects/b1/3a03829b0e62c760b3f1f9be788ee238c15b20: No such file or directory
cp: testBuildOrg//.git/objects/b1/4142dec8ce4d7b5914e2a89e328b413721071f: No such file or directory
cp: testBuildOrg//.git/objects/b1/488beb0128b3d7b2e8020b3775ed89cdfcaa4e: No such file or directory
cp: testBuildOrg//.git/objects/b1/48f1f9a83cdbea8fadaae328dc94df78d570b0: No such file or directory
cp: testBuildOrg//.git/objects/b1/4b9e4eb9676022d3a024c0912e91d6a06ec740: No such file or directory
cp: testBuildOrg//.git/objects/b1/526ee46d4bc1f896125c9b3f3b3edf9a43bc0a: No such file or directory
cp: testBuildOrg//.git/objects/b1/67c10f7db2ca6cc78e0cd6bf4c9045eb477b9b: No such file or directory
cp: testBuildOrg//.git/objects/b1/6a410ebfbfe93c83bc5d4f6db0023d25ddb3ee: No such file or directory
cp: testBuildOrg//.git/objects/b1/72042d385dc06bcf9349399e16eb005b6ff5d9: No such file or directory
cp: testBuildOrg//.git/objects/b1/759ae0b4514cafc3426bc16281e132f66e86de: No such file or directory
cp: testBuildOrg//.git/objects/b1/8d86a906d8be0590b7cd040cbcc5a3760128eb: No such file or directory
cp: testBuildOrg//.git/objects/b1/8dc078825137befbe426467368574438f60744: No such file or directory
cp: testBuildOrg//.git/objects/b1/a03767a48d0e3afbdeab7466cb6d1e6808fd01: No such file or directory
cp: testBuildOrg//.git/objects/b1/aca7ab2d9e4b13bc032b0cde997f8af5acdbc5: No such file or directory
cp: testBuildOrg//.git/objects/b1/aec7179ad21697f2d6a7d99e53c0ce1466be27: No such file or directory
cp: testBuildOrg//.git/objects/b1/b2a67d343ea67980880a48b157cf228373068e: No such file or directory
cp: testBuildOrg//.git/objects/b1/b5ca461d6232229bb85530bedec59fc6b03d8e: No such file or directory
cp: testBuildOrg//.git/objects/b1/b8bc38c3fb45316f6ae96b1a7cf34e7a532142: No such file or directory
cp: testBuildOrg//.git/objects/b1/b956fa72486bb6b56e57bb816a5eeef12c22aa: No such file or directory
cp: testBuildOrg//.git/objects/b1/b95e155a583d3d52ff260970752859ee4e94ce: No such file or directory
cp: testBuildOrg//.git/objects/b1/bb7f8c68fc5c47a490212bf05927a8185be7b6: No such file or directory
cp: testBuildOrg//.git/objects/b1/c0caccdf8e54919e7f8b666ded238b8fbf19e8: No such file or directory
cp: testBuildOrg//.git/objects/b1/c5caeda06d4c24f0e52da465bf52e67988f6f7: No such file or directory
cp: testBuildOrg//.git/objects/b1/cd185e0aa7056598f75443292909fb2b67931a: No such file or directory
cp: testBuildOrg//.git/objects/b1/d9f3facad29705535c47eaeb8676a769dc54ea: No such file or directory
cp: testBuildOrg//.git/objects/b1/dd5e8d8d389ac95dc9e06a330cfa623bd058d8: No such file or directory
cp: testBuildOrg//.git/objects/b1/dfc65b40a985b2d347157841f01acff9b49d21: No such file or directory
cp: testBuildOrg//.git/objects/b1/e1002174982748963693c9ab99a2339a8b2b52: No such file or directory
cp: testBuildOrg//.git/objects/b1/ea9b9e3753184c57166fc92ec4ca641161b32d: No such file or directory
cp: testBuildOrg//.git/objects/b1/f4275640e6f6d14794ee86ffc21315aadffe9b: No such file or directory
cp: testBuildOrg//.git/objects/b1/f5f43e8c05dc0581c47cb7e199cf8bd7c90c64: No such file or directory
cp: testBuildOrg//.git/objects/b1/f959d7d0760ba86bbef41e7a781b5f6fc1fe1d: No such file or directory
cp: testBuildOrg//.git/objects/b1/fb1fc51a610dac136db1c6c9564cf8b2a90a45: No such file or directory
cp: testBuildOrg//.git/objects/b2/62cccdfd619f60e0b623197f9484cd207875c8: No such file or directory
cp: testBuildOrg//.git/objects/b2/6badcf6efb23afc11ac4345473921c91ab2b32: No such file or directory
cp: testBuildOrg//.git/objects/b2/766997eb2f5cf049d82f717e1ef63c5b441c83: No such file or directory
cp: testBuildOrg//.git/objects/b2/76975a6427798109687f90982899ed16fc9b3f: No such file or directory
cp: testBuildOrg//.git/objects/b2/7fd04e3e0dda5ea6872365a8a7345b0c512579: No such file or directory
cp: testBuildOrg//.git/objects/b2/8a87a1acb7f6d84e193e1340556fdd36f64df6: No such file or directory
cp: testBuildOrg//.git/objects/b2/91b2994eec878ff1cbf388f1aa171443cad498: No such file or directory
cp: testBuildOrg//.git/objects/b2/949dffa79a0a6c5ec09350d6af02b7487146cf: No such file or directory
cp: testBuildOrg//.git/objects/b2/a530933df29c68d6fdf4c4d0423118a8862b8b: No such file or directory
cp: testBuildOrg//.git/objects/b2/aabf73fb7a21c79223d8f3e6c87e99f2c316a1: No such file or directory
cp: testBuildOrg//.git/objects/b2/ad914b050cdfea5ffe3861b895617fb13a6fdc: No such file or directory
cp: testBuildOrg//.git/objects/b2/b51ba337cf27757e55b611f673459b32107ad7: No such file or directory
cp: testBuildOrg//.git/objects/b2/ba79feda7e097a2f5d81894715ae25354465a8: No such file or directory
cp: testBuildOrg//.git/objects/b2/c39a00567c2e53d9d6f132787bc1b1c068873f: No such file or directory
cp: testBuildOrg//.git/objects/b2/ccefce24e5fb1ce12eb140a749e4961d2adf0e: No such file or directory
cp: testBuildOrg//.git/objects/b2/d89a87ca975a2995cfbfe032379589d9c78eac: No such file or directory
cp: testBuildOrg//.git/objects/b2/d9356ef4dd217b468b5c95a71adb20497184eb: No such file or directory
cp: testBuildOrg//.git/objects/b2/dfcfc5ba425f1cfc2b3801c5ac423a6cf5baf3: No such file or directory
cp: testBuildOrg//.git/objects/b2/ea4df0b5f45509760cd9dcbb198aa9f666b4f4: No such file or directory
cp: testBuildOrg//.git/objects/b2/f31ec50215d4542704f55c306b7249ecfd70dd: No such file or directory
cp: testBuildOrg//.git/objects/b2/f43f813a151ea3e7ae65885ab21eee7c11b80c: No such file or directory
cp: testBuildOrg//.git/objects/b4/cb41ac208bffc3043f104fa1329bfe5e81da5c: No such file or directory
cp: testBuildOrg//.git/objects/b4/cdf1ccd4b184159736774d42c345af6c97988e: No such file or directory
cp: testBuildOrg//.git/objects/b4/d13510556c7c12a6405d49014238bc0785be5b: No such file or directory
cp: testBuildOrg//.git/objects/b4/d82c43209280259b9e25c737bce748e87eeef1: No such file or directory
cp: testBuildOrg//.git/objects/b4/dcfbbc1182912f0f0f893159663ec201ce1467: No such file or directory
cp: testBuildOrg//.git/objects/b4/deaccfd1605683aff10707fc4238e41b80d1bf: No such file or directory
cp: testBuildOrg//.git/objects/b4/e504091350db2a507bd16710a109f253646b28: No such file or directory
cp: testBuildOrg//.git/objects/b4/e824c2228b7c6b4e6bd3381d1c359af7aa114d: No such file or directory
cp: testBuildOrg//.git/objects/b4/f8d48b8fd69c0df9df696bb7564b7d94aa80aa: No such file or directory
cp: testBuildOrg//.git/objects/b4/fbb76b549dc75a22c8c7836e6f9fd0ced42101: No such file or directory
cp: testBuildOrg//.git/objects/b4/fd11b79f50b63ca0bfe4df96958db9687692a4: No such file or directory
cp: testBuildOrg//.git/objects/b4/fe76df5eb2a68c8a739471fb4977367c7de664: No such file or directory
cp: testBuildOrg//.git/objects/b5/2a31570e0f85695ab6dc0cfacf05f2762a1cfc: No such file or directory
cp: testBuildOrg//.git/objects/b5/34c4d07da1d7ea097cea089b542b942d6749d7: No such file or directory
cp: testBuildOrg//.git/objects/b5/3818b588dbd56d409615c4bdceaa36ba6fcb83: No such file or directory
cp: testBuildOrg//.git/objects/b5/384bb4036223983db590321683cae49927c8b6: No such file or directory
cp: testBuildOrg//.git/objects/b5/38618c270074b8d5af41f95c34240469ce8f70: No such file or directory
cp: testBuildOrg//.git/objects/b5/485d454c0714716ce12af569907a576405ec4e: No such file or directory
cp: testBuildOrg//.git/objects/b5/4b58012aa16b9ab8e363e1b2e9e086ed94fe1d: No such file or directory
cp: testBuildOrg//.git/objects/b5/4edd719f0d4bb94548f606bc10a168c77e6ac8: No such file or directory
cp: testBuildOrg//.git/objects/b5/5af366b1ccda3da3040999a261c62cf123df11: No such file or directory
cp: testBuildOrg//.git/objects/b5/644133f230b5c749b73812ac15c8ef36e9957d: No such file or directory
cp: testBuildOrg//.git/objects/b5/6db8156fabd61f5bb3cbcb96a4b515d462156b: No such file or directory
cp: testBuildOrg//.git/objects/b5/71f02877a97dc3ccedc06b0ce951d4a5e64294: No such file or directory
cp: testBuildOrg//.git/objects/b5/7467ee3a0d289858ae6048d39d7ac25c3db541: No such file or directory
cp: testBuildOrg//.git/objects/b5/7ba20d56a59692103890032e3737dcf7f1f927: No such file or directory
cp: testBuildOrg//.git/objects/b5/7f4b8e967a4c3aba9f83f469aafc44eb9f8de0: No such file or directory
cp: testBuildOrg//.git/objects/b5/86f82eb30ddadc141c07ee54576a6d8926c04e: No such file or directory
cp: testBuildOrg//.git/objects/b5/913090e16417a92fbef6739e44c45639556cb2: No such file or directory
cp: testBuildOrg//.git/objects/b5/933f74cfb5daba3701ee8f1e0edfc9e9ecd619: No such file or directory
cp: testBuildOrg//.git/objects/b5/acad180a2312f50903fc632e5349e9dc7b3cb9: No such file or directory
cp: testBuildOrg//.git/objects/b5/b379c507e4eb89d89f88a6c02fa6b5f80606f9: No such file or directory
cp: testBuildOrg//.git/objects/b5/b3a171a45cfed3559b94da418811f54335b3eb: No such file or directory
cp: testBuildOrg//.git/objects/b5/b6b3df3335367e1cde57d510bb31f1c0757179: No such file or directory
cp: testBuildOrg//.git/objects/b5/b73da554861f751acb4066829a35c157815e0f: No such file or directory
cp: testBuildOrg//.git/objects/b5/c13f6613d8c52804f8faa7eb641edddc0dc6a4: No such file or directory
cp: testBuildOrg//.git/objects/b5/c260165ecfe04842def39dd57fc51ed8fd6e66: No such file or directory
cp: testBuildOrg//.git/objects/b5/c53c2b54bae6ed050dbf9d02d517bfee8ba567: No such file or directory
cp: testBuildOrg//.git/objects/b5/c5e17c91a362a0dbca950874e8b9c8d8f4f172: No such file or directory
cp: testBuildOrg//.git/objects/b5/cd60baf182eb06d9a15bc09b146e2c31f857d3: No such file or directory
cp: testBuildOrg//.git/objects/b5/da7f866170bfd22e9d0dadbba2688ab34e56fd: No such file or directory
cp: testBuildOrg//.git/objects/b5/db08ef32c5f35132b746dea2f8ca8a4a38f85d: No such file or directory
cp: testBuildOrg//.git/objects/b5/deef2ac5610a66cf52de146de68f3cc6a33138: No such file or directory
cp: testBuildOrg//.git/objects/b5/e29d227fb69230cdf4e67bcc3c0f12e737d48c: No such file or directory
cp: testBuildOrg//.git/objects/b5/e588eaa4dda05f7ca0403ac163b4b3f3ea5312: No such file or directory
cp: testBuildOrg//.git/objects/b5/ef734535e3642f56fa87df7d3e79ab97844e7a: No such file or directory
cp: testBuildOrg//.git/objects/b5/f8aef56ec6f6ec9b0d979268ca8414d052e188: No such file or directory
cp: testBuildOrg//.git/objects/b5/fce9aa1826e9eaa10b3261885001adfacc2afb: No such file or directory
cp: testBuildOrg//.git/objects/b8/d20aa8eaa9091a6891e65a49e12ae7cfdaee73: No such file or directory
cp: testBuildOrg//.git/objects/b8/ed845d6144f5f2edc645044cfb60a3c18b14f2: No such file or directory
cp: testBuildOrg//.git/objects/b8/f1913f739f23e802ef943707592f6b9ef331a8: No such file or directory
cp: testBuildOrg//.git/objects/b8/fef24b7082fe0d2a4fbb27763593dad0e842f5: No such file or directory
cp: testBuildOrg//.git/objects/b8/ff39ac18611fc5bab10137af7adc20e02b58ce: No such file or directory
cp: testBuildOrg//.git/objects/b9/1f5a4672351f8887b2777123313da3330e5fa7: No such file or directory
cp: testBuildOrg//.git/objects/b9/2179b324d24740190e5b737aa7ef0030bd382a: No such file or directory
cp: testBuildOrg//.git/objects/b9/277dce4ed1fc57492a232ae504bd585acb61a3: No such file or directory
cp: testBuildOrg//.git/objects/b9/36de9f5dd0bc43609c4f68fbf87bed5ba61ebe: No such file or directory
cp: testBuildOrg//.git/objects/b9/3a0b39a5bc4fcb884808a88eda2d5fb50be905: No such file or directory
cp: testBuildOrg//.git/objects/b9/3f04cc5433fbb1e0a8d4762ee470cdf615be5c: No such file or directory
cp: testBuildOrg//.git/objects/b9/4053c5b3078f3aa7a91c2fff6056cdff88572d: No such file or directory
cp: testBuildOrg//.git/objects/b9/4277ff5efd2ad07d581c73e01eeddbb4c0a845: No such file or directory
cp: testBuildOrg//.git/objects/b9/43a3bbc8730c32e98a821f2033c58e3fca097c: No such file or directory
cp: testBuildOrg//.git/objects/b9/5b109eb489eec3916dbdcf4810571336ead26b: No such file or directory
cp: testBuildOrg//.git/objects/b9/5cb18d0435c9d450a3eaf35141c60f82c19934: No such file or directory
cp: testBuildOrg//.git/objects/b9/5e74fd31544a5c042e3b160249d474c6c622b1: No such file or directory
cp: testBuildOrg//.git/objects/b9/60a834b5e2ab4b2565556210d232274d537e95: No such file or directory
cp: testBuildOrg//.git/objects/b9/61b04cc40fe40175a15c76fc998bd7ac05f22a: No such file or directory
cp: testBuildOrg//.git/objects/b9/62cf1116454eb1db9fd2c0ad1bc1dd8ab50a71: No such file or directory
cp: testBuildOrg//.git/objects/b9/680a2a66371dc6deb704da3e4df3f30a569bdb: No such file or directory
cp: testBuildOrg//.git/objects/b9/6905db1aecb5e786c574471ee65dd03a91632d: No such file or directory
cp: testBuildOrg//.git/objects/b9/6a594edc0a7a07381493fc80007aa8de554c1c: No such file or directory
cp: testBuildOrg//.git/objects/b9/6db1684fc663a743a938d117f155d3df39fbf2: No such file or directory
cp: testBuildOrg//.git/objects/b9/6f6a10a50e26e925090d842a98b9d6540b1678: No such file or directory
cp: testBuildOrg//.git/objects/b9/71c412e7d0b71f87b6bd2ab71f95542ea419ae: No such file or directory
cp: testBuildOrg//.git/objects/b9/77fd98b3f5aa7b10e99d28f1d66493931be20d: No such file or directory
cp: testBuildOrg//.git/objects/b9/7a0427b95dba05e7660e558c968a36f16a4bc1: No such file or directory
cp: testBuildOrg//.git/objects/b9/7d15fcb35987afbf9f57726064fa6a61d8eaf1: No such file or directory
cp: testBuildOrg//.git/objects/b9/87f4bddf06b11d439e74310d5205a5c4dfe169: No such file or directory
cp: testBuildOrg//.git/objects/b9/8a01a4d1adfcd70968d6f5847d90215c0cef27: No such file or directory
cp: testBuildOrg//.git/objects/b9/8b65e247b7b142d32d42bd6832fc4eb125f206: No such file or directory
cp: testBuildOrg//.git/objects/b9/8f367a284ffe66655d70cea16152b385e89395: No such file or directory
cp: testBuildOrg//.git/objects/b9/a278e8c381469408a5a7eb28d0ba3b967977bd: No such file or directory
cp: testBuildOrg//.git/objects/b9/c338016e07a6bfd058ee069181961eca489268: No such file or directory
cp: testBuildOrg//.git/objects/b9/cbd3830ef2e4864403a9946b0c3bf447ac84e8: No such file or directory
cp: testBuildOrg//.git/objects/b9/d819c8f4ec6d240f2e0cda4d294ae18622c563: No such file or directory
cp: testBuildOrg//.git/objects/b9/d86523b12a383b9583388c1c059e465227817e: No such file or directory
cp: testBuildOrg//.git/objects/b9/dab625f5110803ac05855c1b2d1d33587e8a77: No such file or directory
cp: testBuildOrg//.git/objects/b9/dcf8a0d14e2ef54b43180b84826543c1725337: No such file or directory
cp: testBuildOrg//.git/objects/b9/df64211c6b6c4bce9b467fbe6759023f2c9fe2: No such file or directory
cp: testBuildOrg//.git/objects/b9/e3f09a0976acaaf402bf30e647036764c3e4c5: No such file or directory
cp: testBuildOrg//.git/objects/b9/e5c59e3cba6c45467d65eb606329d2114c8e18: No such file or directory
cp: testBuildOrg//.git/objects/b9/ea373db91bb2a5c0e0bcc6967a16380dbdf21b: No such file or directory
cp: testBuildOrg//.git/objects/b9/ec7d76913c7fc572ec8cdaae20338bd6d5fb84: No such file or directory
cp: testBuildOrg//.git/objects/b9/f5b8528e98ab8cbe332b4bc78af47f9bc076e1: No such file or directory
cp: testBuildOrg//.git/objects/bc: No such file or directory
cp: testBuildOrg//.git/objects/bd/26e74bd43c667906ea58a563dc8f3d06771842: No such file or directory
cp: testBuildOrg//.git/objects/bd/27a4e2349f831c15bde022ae41498284a6ede6: No such file or directory
cp: testBuildOrg//.git/objects/bd/2aa46b7bf2abc23483c52bf34a2c005374980e: No such file or directory
cp: testBuildOrg//.git/objects/bd/30ffbb41e3885d05b934f88d59e5fb8048ca51: No such file or directory
cp: testBuildOrg//.git/objects/bd/32b8b06bb13be136e42f9e3aebc3a6405d50e6: No such file or directory
cp: testBuildOrg//.git/objects/bd/352f6f250f48129191cb8e3043c6abd477ad69: No such file or directory
cp: testBuildOrg//.git/objects/bd/37bd79d9e41924b66a5971cb3d40c4ffeac7a2: No such file or directory
cp: testBuildOrg//.git/objects/bd/3a48eebc7098bb1e94943f76ac29fe2fc8f5e2: No such file or directory
cp: testBuildOrg//.git/objects/bd/43bb6b19ee7f51ea034ed0f13b679910b17bf8: No such file or directory
cp: testBuildOrg//.git/objects/bd/470a48a844a4c9da1a7587414f1b2c72795deb: No such file or directory
cp: testBuildOrg//.git/objects/bd/481b95b29e2d7bca1d892375632dc4dfc43a9a: No such file or directory
cp: testBuildOrg//.git/objects/bd/4e809ae3b52ff3d2eb18db0303a9d89b0d9c09: No such file or directory
cp: testBuildOrg//.git/objects/bd/573a26d7fab32cc39a6e07ea517b00387efea8: No such file or directory
cp: testBuildOrg//.git/objects/bd/60c68026f755a815d2cdbedcb83e683fda2a2e: No such file or directory
cp: testBuildOrg//.git/objects/bd/6149bb5946e3ead63ec88a0fa2bec1894708a0: No such file or directory
cp: testBuildOrg//.git/objects/bd/61f6cffa3414d07e2e82c3664ad2225a336be6: No such file or directory
cp: testBuildOrg//.git/objects/bd/64162a6c8e483b460eaccf38f6ea4c4e255563: No such file or directory
cp: testBuildOrg//.git/objects/bd/667c965d914d3bc73542933d0ed617d29104d5: No such file or directory
cp: testBuildOrg//.git/objects/bd/68ec9b3c40a860816878872dd08ba9f2bcd111: No such file or directory
cp: testBuildOrg//.git/objects/bd/6dd81d82c91353e7db8868eff3c9b90710e688: No such file or directory
cp: testBuildOrg//.git/objects/bd/7af432f057889a8b6586b8aaec89e6763c9fff: No such file or directory
cp: testBuildOrg//.git/objects/bd/8cadd20c78a20dee3e986032b9d38bbe2e8cfe: No such file or directory
cp: testBuildOrg//.git/objects/bd/9008d33ddd01d837937334e9a59a8c960f12af: No such file or directory
cp: testBuildOrg//.git/objects/bd/923507bc42fe88b827dd166075932d2540fd42: No such file or directory
cp: testBuildOrg//.git/objects/bd/96554551a84db581020fdf05860124dfb5819f: No such file or directory
cp: testBuildOrg//.git/objects/bd/97462c4bc2b410867e49940004beebee1f88a6: No such file or directory
cp: testBuildOrg//.git/objects/bd/998475700afdb46f6785c9a96340bfc7839745: No such file or directory
cp: testBuildOrg//.git/objects/bd/9a5021d4e7102cd0306a6a2f66111aa29b7e01: No such file or directory
cp: testBuildOrg//.git/objects/bd/a6e710158080f0af894de917d42b429785362a: No such file or directory
cp: testBuildOrg//.git/objects/bd/a79c8eefba8532230711bc8f3939e17b91b11c: No such file or directory
cp: testBuildOrg//.git/objects/bd/b2abd5c0ece73985f09da912e672b385710c32: No such file or directory
cp: testBuildOrg//.git/objects/bd/b5ce761c6cb4de82090fd56d423a1bc9f7cd05: No such file or directory
cp: testBuildOrg//.git/objects/bd/ca1365ab886c1ff9975cb5d7dd2cc96bba88b4: No such file or directory
cp: testBuildOrg//.git/objects/bd/e2cd50dccb50e241fd619cc11f8a083e05065e: No such file or directory
cp: testBuildOrg//.git/objects/bd/e5937519cfbb2cedba12be19ffd8b0bd1ff819: No such file or directory
cp: testBuildOrg//.git/objects/bd/f838f334aa34a719a6e2b3c277600805944af4: No such file or directory
cp: testBuildOrg//.git/objects/c0/a9a5c266b1d4feb4d9276167ec32fbc3a01035: No such file or directory
cp: testBuildOrg//.git/objects/c0/af2b6e2c80e01c3a66fe67279e82b57b947579: No such file or directory
cp: testBuildOrg//.git/objects/c0/afff9a5a5d2dae66d52f89b73aa1c19ab57308: No such file or directory
cp: testBuildOrg//.git/objects/c0/b31376020f6d34df3675180a89c1b5e8e90135: No such file or directory
cp: testBuildOrg//.git/objects/c0/bcde1c97e56978cda2b060aa57b608bd84cc63: No such file or directory
cp: testBuildOrg//.git/objects/c0/c0acf2c00716a2f471ed76a3c7cd7dfb1e2f72: No such file or directory
cp: testBuildOrg//.git/objects/c0/c95ccdaa9242a196b7e265d456144bed2c5f81: No such file or directory
cp: testBuildOrg//.git/objects/c0/cf08e4a08e16b20352ea3f81b89fb78a31ffa2: No such file or directory
cp: testBuildOrg//.git/objects/c0/cfda5fa83935ce7425550621bfa0abf2a7ec43: No such file or directory
cp: testBuildOrg//.git/objects/c0/d1cbaa2f69f6401a3646f07888a1e5870a9b62: No such file or directory
cp: testBuildOrg//.git/objects/c0/db81b7080ae50ba1eff8472ab0ab7031bd8597: No such file or directory
cp: testBuildOrg//.git/objects/c0/f6ec21dbb48133ef23be5f15024e5e02b701c2: No such file or directory
cp: testBuildOrg//.git/objects/c0/f7474e3c2f7d63a8fc381b8ecda3ef2ba5dfa1: No such file or directory
cp: testBuildOrg//.git/objects/c0/fcaf3fe36db3e42dba3fa2e89e89fc4a6dfec4: No such file or directory
cp: testBuildOrg//.git/objects/c1/c172d42b21f02014c5d8e8d121b3e1959fdcdd: No such file or directory
cp: testBuildOrg//.git/objects/c1/c65d467609369f7b47494528d8843599a7a752: No such file or directory
cp: testBuildOrg//.git/objects/c1/c7ecc31df3e0e864d1b2f6431c0f3ab5b9ac19: No such file or directory
cp: testBuildOrg//.git/objects/c1/d1007f6d9fc8622e7ab434b2720a42fe3a43cc: No such file or directory
cp: testBuildOrg//.git/objects/c1/e201075fe5c7565e7914cc5cc92393d09779bf: No such file or directory
cp: testBuildOrg//.git/objects/c1/e6f5edf21a7cec36bb8744cc3fc6cda031e10a: No such file or directory
cp: testBuildOrg//.git/objects/c1/e9930b97bb3a7cfa2a0ee44fcbcee4f2c33c19: No such file or directory
cp: testBuildOrg//.git/objects/c1/f1271d3995688e1b2d40b0f92e854373519769: No such file or directory
cp: testBuildOrg//.git/objects/c2/5750eaa2be5910eee98b0fd7fadc183159cba2: No such file or directory
cp: testBuildOrg//.git/objects/c2/5a5bd6cc49538d6b5ba4965635811072426ffb: No such file or directory
cp: testBuildOrg//.git/objects/c2/689ed84f67b73a74c734b9326b64096ea9a730: No such file or directory
cp: testBuildOrg//.git/objects/c2/6a9ef372af30d6a63d0dc797d7a7750a25d12f: No such file or directory
cp: testBuildOrg//.git/objects/c2/7a0025366084cb8af4e2aadabec4ae0b7a27ed: No such file or directory
cp: testBuildOrg//.git/objects/c2/7da76ad94ec0091ac8f7dbede53937aaa28714: No such file or directory
cp: testBuildOrg//.git/objects/c2/87417d77d401fc6f86e8647e7caa72964fc4da: No such file or directory
cp: testBuildOrg//.git/objects/c2/89374ff5a55829d22a4a436912d9aba3bb9774: No such file or directory
cp: testBuildOrg//.git/objects/c2/8cc77debae00a5508723fad86a0ab8fef59ec3: No such file or directory
cp: testBuildOrg//.git/objects/c2/9d5b7bbf00e551d0ffc5b6067420856ea9f7c5: No such file or directory
cp: testBuildOrg//.git/objects/c2/a0f24815e1375ed94e7262cede9e98373e9b2f: No such file or directory
cp: testBuildOrg//.git/objects/c2/a5d785bc8d9bdf0e912da6b74ce6ea1409290f: No such file or directory
cp: testBuildOrg//.git/objects/c2/b0691f9faaf7c732498cf4f7b9b25373931ed6: No such file or directory
cp: testBuildOrg//.git/objects/c2/bdc3f5c2504ac58d1190cec85dbc64c9b3d8a4: No such file or directory
cp: testBuildOrg//.git/objects/c2/cd782f85fc0729291350e729d5571256b33bcc: No such file or directory
cp: testBuildOrg//.git/objects/c2/cec26e5c98154136a898faa5906be6a40b10d8: No such file or directory
cp: testBuildOrg//.git/objects/c2/d363d85ad96b6bad558b450d9755adc332e63e: No such file or directory
cp: testBuildOrg//.git/objects/c2/ddc841e714351241e373ad35dac5c9ca143bcf: No such file or directory
cp: testBuildOrg//.git/objects/c2/f4c8d3cc872fc5b2ff8317fc2b3c96a9283ee0: No such file or directory
cp: testBuildOrg//.git/objects/c2/f88c8f809567bc03b71c83a11cffdafeaeb079: No such file or directory
cp: testBuildOrg//.git/objects/c2/fa0447e996c053e79eb42eda87422e084a5f67: No such file or directory
cp: testBuildOrg//.git/objects/c6/e9414e0d7352f69db4215dbda3ae6b63a19527: No such file or directory
cp: testBuildOrg//.git/objects/c6/eb4ee94b5fe4d567fae11f5627be3b39392e5b: No such file or directory
cp: testBuildOrg//.git/objects/c6/f7a00b10bb6782303d2a1637fc34f3babb5864: No such file or directory
cp: testBuildOrg//.git/objects/c6/f9a6b727036a2358a47f9f41b5bdb3a983f7c1: No such file or directory
cp: testBuildOrg//.git/objects/c7/7d04ee033c413e9153be915bcd15fa2f8286e1: No such file or directory
cp: testBuildOrg//.git/objects/c7/7f121f2f14cc2710bf166914cdd58ecc9faa9a: No such file or directory
cp: testBuildOrg//.git/objects/c7/83a88c0eae3b49779b7e747d1820e5176df6c5: No such file or directory
cp: testBuildOrg//.git/objects/c7/87c966173389e161e6c35cfb8e6c47e92ce49a: No such file or directory
cp: testBuildOrg//.git/objects/c7/8bfa8b769a062426f825cec6c414120ef70e3c: No such file or directory
cp: testBuildOrg//.git/objects/c7/8d5ad076e2f3ccf0acd6e9edde797cd3b288b2: No such file or directory
cp: testBuildOrg//.git/objects/c7/8f94b49d2cb2e19696a973057aa5550932a729: No such file or directory
cp: testBuildOrg//.git/objects/c7/914f376854402d9217434ff72df76e4ab92812: No such file or directory
cp: testBuildOrg//.git/objects/c7/998a3267d9e9622d597d0956cc27aef6920702: No such file or directory
cp: testBuildOrg//.git/objects/c7/9a5ddc85a099057693fc735532ea065630b528: No such file or directory
cp: testBuildOrg//.git/objects/c7/ac76917fbc3211165d6b82061f807d931e6e3f: No such file or directory
cp: testBuildOrg//.git/objects/c7/ac8a68d32d6d93452a418249dcf094025594c1: No such file or directory
cp: testBuildOrg//.git/objects/c7/b35d9c8c47608ea8f9d63f44b3de877707fe2f: No such file or directory
cp: testBuildOrg//.git/objects/c7/b67a5f8fc329c871f36619cca009ebc09be6d9: No such file or directory
cp: testBuildOrg//.git/objects/c7/c8fb39b7b707d8bddc8dc1fb84fe4a1f970f97: No such file or directory
cp: testBuildOrg//.git/objects/c7/cd84264dd872ce79f5be461b38e15a59916d89: No such file or directory
cp: testBuildOrg//.git/objects/c7/d3ed6e015ae9eeaf7ab5a51804bfa04f40f1f4: No such file or directory
cp: testBuildOrg//.git/objects/c7/db3be973f1a532b5b463e4bcc31e91b35ec91b: No such file or directory
cp: testBuildOrg//.git/objects/c7/ea3675f788a42b293dc5977f20a672e8d0408c: No such file or directory
cp: testBuildOrg//.git/objects/c7/ea3c21a6c83665c844cb74a79b8d37da9cadd6: No such file or directory
cp: testBuildOrg//.git/objects/c8/86730c873e4a0c5ab131f163850b09e2596516: No such file or directory
cp: testBuildOrg//.git/objects/c8/8a4a892c58fd2f4f61cb93a1fda2ae23ce8810: No such file or directory
cp: testBuildOrg//.git/objects/c8/8c3edfe7f4c6857edca32e041f4d21909dfb58: No such file or directory
cp: testBuildOrg//.git/objects/c8/9299b80c60e0d3a8db8d0c2c4a813b20581a01: No such file or directory
cp: testBuildOrg//.git/objects/c8/958070f5c32af148bfce2160d0e9ea67d65782: No such file or directory
cp: testBuildOrg//.git/objects/c8/a113450dea24fe5e4e480777624c127a165481: No such file or directory
cp: testBuildOrg//.git/objects/c8/a96a92260e2e20e5611f7156f5274d88fe2200: No such file or directory
cp: testBuildOrg//.git/objects/c8/acf0808c7774562d99ac30619d5f70a6562c7d: No such file or directory
cp: testBuildOrg//.git/objects/c8/ad2e96c6eadcceee13c59ec37fc7f368649d73: No such file or directory
cp: testBuildOrg//.git/objects/c8/bfd5fa0b2c3673e1f3f0a0a0352dd7ca994a9b: No such file or directory
cp: testBuildOrg//.git/objects/c8/c8bd4b2b5d877d4bc8229c443f93d7e5571c98: No such file or directory
cp: testBuildOrg//.git/objects/c8/c999853a1c14f2d2eb58630db4d59c923a0602: No such file or directory
cp: testBuildOrg//.git/objects/c8/cc7f11be5633934b9f4939241ae0a7b3a6806b: No such file or directory
cp: testBuildOrg//.git/objects/c8/cd6102e3d0ba029211cdd0a0d82eb0d6f65edd: No such file or directory
cp: testBuildOrg//.git/objects/c8/d73d02f28d83435b668a04930209f0de0c929d: No such file or directory
cp: testBuildOrg//.git/objects/c8/d9420db7fcebd371eaec8a76f4faf87192950a: No such file or directory
cp: testBuildOrg//.git/objects/c8/de7c07fa95cdcaf362a1ea1601fa0814dc77d3: No such file or directory
cp: testBuildOrg//.git/objects/c8/e75e6ccac362ffbfbee824f0795c156ca78495: No such file or directory
cp: testBuildOrg//.git/objects/c8/ea55bbcf3f5eec471261b829ec82fdcec1d4f9: No such file or directory
cp: testBuildOrg//.git/objects/ca/85a1f0af98bc068337c4b0e1d05706a2d4b2b1: No such file or directory
cp: testBuildOrg//.git/objects/ca/88b57164451b24e7e76a2903780293e45dafd5: No such file or directory
cp: testBuildOrg//.git/objects/ca/8975220dc09912b03ce873b59146d4547a265b: No such file or directory
cp: testBuildOrg//.git/objects/ca/8be2efcfd96e7e0ed7e4572a52438324a1ac26: No such file or directory
cp: testBuildOrg//.git/objects/ca/8c43b8da8ecdd4992ef0af90f195453d61b9e8: No such file or directory
cp: testBuildOrg//.git/objects/ca/908a3677d80a9cab49a6c7b6aff4732a35fd38: No such file or directory
cp: testBuildOrg//.git/objects/ca/995a29c171b8673609da970d88df75c97108f7: No such file or directory
cp: testBuildOrg//.git/objects/ca/a41c8734572649e1ca64523c8359d96d7adb48: No such file or directory
cp: testBuildOrg//.git/objects/ca/ac25d1b4a9d6cd98d0a12571846f1c88e5da8c: No such file or directory
cp: testBuildOrg//.git/objects/ca/b051198fc092323d07d9ed2d9aca1b86d220fa: No such file or directory
cp: testBuildOrg//.git/objects/ca/c8ea6f4f5b741055bb5e3e6f8ea34f7555b5b8: No such file or directory
cp: testBuildOrg//.git/objects/ca/cde16eaa4ab2aafc0b68349c604420964783f2: No such file or directory
cp: testBuildOrg//.git/objects/ca/ce7afa92385dd3bc5202e31fd11a326774b5b3: No such file or directory
cp: testBuildOrg//.git/objects/ca/d625bda5868f1cd01e48c6407d4961bd3d1d84: No such file or directory
cp: testBuildOrg//.git/objects/ca/e17694177f33b655290a34538f427777b1d0bb: No such file or directory
cp: testBuildOrg//.git/objects/ca/ebe960ab48f47136731c0894067040ff69e1e3: No such file or directory
cp: testBuildOrg//.git/objects/ca/edc11864deb72e0d27a54562bd79d0da7f23f1: No such file or directory
cp: testBuildOrg//.git/objects/ca/fb2912cfdcc273c09e37ee75d097fcabbb5c0d: No such file or directory
cp: testBuildOrg//.git/objects/ca/fe2db8be6cfe9838dd65010f218bfc4e5c1309: No such file or directory
cp: testBuildOrg//.git/objects/ca/ffd7b7ea902156cb40c67472cd4d8d6675a9c9: No such file or directory
cp: testBuildOrg//.git/objects/cc/3261387a3fc97ca4da851e84d2c27757555ef7: No such file or directory
cp: testBuildOrg//.git/objects/cc/3669dcffe7c50f730bbaab962dc828c3c61c7d: No such file or directory
cp: testBuildOrg//.git/objects/cc/4140ecf3bf560a0bb4e862c43160ac170c7532: No such file or directory
cp: testBuildOrg//.git/objects/cc/42a230162ca949defe4b838093cc6cf639e5a6: No such file or directory
cp: testBuildOrg//.git/objects/cc/4ec5d3a9b58c5c488fbbd94cce64cb1c764670: No such file or directory
cp: testBuildOrg//.git/objects/cc/55cc1ec0779189ba85c6eea214cdabd99c002d: No such file or directory
cp: testBuildOrg//.git/objects/cc/604f37b9b30dde38f02c37e875980e277f1dcc: No such file or directory
cp: testBuildOrg//.git/objects/cc/6513d830155facc2c81b6724abce8fd5eb9a34: No such file or directory
cp: testBuildOrg//.git/objects/cc/67289c5f946c0ccc6bda5280f2a3abf48d41eb: No such file or directory
cp: testBuildOrg//.git/objects/cc/6a793ef1a7a55d7f82906faf9dab936cbbf514: No such file or directory
cp: testBuildOrg//.git/objects/cc/6aa0dc43e698801b305e5c94ea16f039db2409: No such file or directory
cp: testBuildOrg//.git/objects/cc/770aa83a11d607bbf3395ebcfde21d382934bd: No such file or directory
cp: testBuildOrg//.git/objects/cc/7b821f3222374cfbf8c8ab581e294dc59e70d8: No such file or directory
cp: testBuildOrg//.git/objects/cc/7c8ceaa772089f2bb968a49dda32c89e9e7ecb: No such file or directory
cp: testBuildOrg//.git/objects/cc/7e9b87851776cb979183db98636e064935a8c4: No such file or directory
cp: testBuildOrg//.git/objects/cc/8f6052f1cb454dd9f54ed9c620c64214e28d8b: No such file or directory
cp: testBuildOrg//.git/objects/cc/962b1dc89d7f6cbef8a0f5c027079c14de0dc1: No such file or directory
cp: testBuildOrg//.git/objects/cc/9b38411aa5b3752182770e3bd6c45cfc05f02c: No such file or directory
cp: testBuildOrg//.git/objects/cc/9d7b2a6987757977b0e7ef91678d55f24f896d: No such file or directory
cp: testBuildOrg//.git/objects/cc/9da0fd3c737b0535d8ca7747247a73d54d04de: No such file or directory
cp: testBuildOrg//.git/objects/cc/9f37217483d2d84f6b8a7a700a56e520896cb6: No such file or directory
cp: testBuildOrg//.git/objects/cc/9fe0dd57fa120332489f5aa46be7faf762e2f9: No such file or directory
cp: testBuildOrg//.git/objects/cc/a52e2e7599dfb9baa80b1d8fabdb11a641919f: No such file or directory
cp: testBuildOrg//.git/objects/cc/a5a6610523eefb2fe8f2d434a2e089eba05549: No such file or directory
cp: testBuildOrg//.git/objects/cc/b742decf4443d72ac06a53ab27cf9230551eaa: No such file or directory
cp: testBuildOrg//.git/objects/cc/c405a7bb9fa9eba39a47eeaa228e5340192c26: No such file or directory
cp: testBuildOrg//.git/objects/cc/cff9e085d326d7827185b696838fa6a25c7a08: No such file or directory
cp: testBuildOrg//.git/objects/cc/dbb6ab28594b80f0e838bcc0d561cf9a7adefd: No such file or directory
cp: testBuildOrg//.git/objects/cc/e0a48091f05d1299864a3aaa22ea6c6bfed914: No such file or directory
cp: testBuildOrg//.git/objects/cc/e13e109cab4735167ad715e7aa618a62bce750: No such file or directory
cp: testBuildOrg//.git/objects/cc/e9bb5c5acb4911c487cd1ecf35457e0bed3b0a: No such file or directory
cp: testBuildOrg//.git/objects/cc/ea4af3571d2ca74ff865241918a4ae5852adb1: No such file or directory
cp: testBuildOrg//.git/objects/cc/ef2b7cf313c715490ad0f7db96824499eb2191: No such file or directory
cp: testBuildOrg//.git/objects/cc/f452a609a30248573a3da4f34359d15dc395d2: No such file or directory
cp: testBuildOrg//.git/objects/cc/fe79c014bf75cef3763be9fa487c022f8e8b64: No such file or directory
cp: testBuildOrg//.git/objects/cc/ffe02ec38f3f054c338cba754ef73cfd2385ee: No such file or directory
cp: testBuildOrg//.git/objects/cd/8ca127f79922454b77e917e5d166c8eb95ea8f: No such file or directory
cp: testBuildOrg//.git/objects/cd/94afdbc549bf92a4426eaacd75160be4cdf8f0: No such file or directory
cp: testBuildOrg//.git/objects/cd/9971886b67511e8a3a336387b14ba652eac970: No such file or directory
cp: testBuildOrg//.git/objects/cd/9bfc29870b98de4581c14b710a379867c2acb2: No such file or directory
cp: testBuildOrg//.git/objects/cd/a230106407df78b24b95583af0c7d13d2f062c: No such file or directory
cp: testBuildOrg//.git/objects/cd/a71f6b53e9ee0b2bc20778df019d9f012cec2e: No such file or directory
cp: testBuildOrg//.git/objects/cd/b217513fc1132a1a4caae64a6655297d649575: No such file or directory
cp: testBuildOrg//.git/objects/cd/b661e9a7b2f6d7f4882e6f0279fb4ad4da440e: No such file or directory
cp: testBuildOrg//.git/objects/cd/c7d90a1699659fb0e06d7685bd9cf55732adf8: No such file or directory
cp: testBuildOrg//.git/objects/cd/c8e1ed735ab1838b9721ef86f1c96f9dcf1ec7: No such file or directory
cp: testBuildOrg//.git/objects/cd/c9b4e37ad314ae55650f59e4931e0a3c8ea0b5: No such file or directory
cp: testBuildOrg//.git/objects/cd/d07e8e88fbec52b6ef469b79ced2a59485e278: No such file or directory
cp: testBuildOrg//.git/objects/cd/d2a67c821d35853716a186a7de56c48cc88833: No such file or directory
cp: testBuildOrg//.git/objects/cd/d87ac44f13a24e9dd2ba240a1b584b5b9ee2ae: No such file or directory
cp: testBuildOrg//.git/objects/cd/dbc8a11b6b3d0507db6f004b97659359d840b8: No such file or directory
cp: testBuildOrg//.git/objects/cd/e82d18fe1f433b55230baec269ead9f89c120c: No such file or directory
cp: testBuildOrg//.git/objects/cd/e8cd1b6e9802dc8bcd596b19361d0739ea5d8d: No such file or directory
cp: testBuildOrg//.git/objects/cd/ecc480a0c92e1732448f6550ed79823bb9f449: No such file or directory
cp: testBuildOrg//.git/objects/cd/f3f1e2a295b441052152ed2e0787afe819e4e2: No such file or directory
cp: testBuildOrg//.git/objects/cd/fb1bd444f9335a6c40396a6ea1a8d62ab889b9: No such file or directory
cp: testBuildOrg//.git/objects/d0/85ed652bc43aaf64a7109500449cb0c5dfdee1: No such file or directory
cp: testBuildOrg//.git/objects/d0/961c97d12639f97b355b2a8c3fd11b1cdfa347: No such file or directory
cp: testBuildOrg//.git/objects/d0/a228975fe79b2fd7361917d090542ea5d4d8f4: No such file or directory
cp: testBuildOrg//.git/objects/d0/a8ed3477480b2c2ace6ff208caccc2ce6a57ff: No such file or directory
cp: testBuildOrg//.git/objects/d0/aa29c92d34c046191d6477dd3f95cc5ba0d421: No such file or directory
cp: testBuildOrg//.git/objects/d0/b139b054e672861fe70068b695b58b18a59a3d: No such file or directory
cp: testBuildOrg//.git/objects/d0/b2155d64a5dc8b0b455338eed7b7d710e5e777: No such file or directory
cp: testBuildOrg//.git/objects/d0/b27a289e3ccbc5d0c88ee1330e8fcfd7444c6a: No such file or directory
cp: testBuildOrg//.git/objects/d0/b9f4f8c7d5cdad0a6fc32e51bc0592e4541831: No such file or directory
cp: testBuildOrg//.git/objects/d0/bf8d416edc08eee13145b116a65a2e1b9e67bb: No such file or directory
cp: testBuildOrg//.git/objects/d0/c53480f7fd2c4ce32d6090dbbdedbb1bbb2b58: No such file or directory
cp: testBuildOrg//.git/objects/d0/c6cb69192c1b94a2d5c1bd6341198f92a055f1: No such file or directory
cp: testBuildOrg//.git/objects/d0/c8fe05bd05e2d9ab195f71001ab298d9d15108: No such file or directory
cp: testBuildOrg//.git/objects/d0/caa45b77e1ca4bbd741b8ec7189d3371d84f02: No such file or directory
cp: testBuildOrg//.git/objects/d0/d1dbafc55789a1be318a48986d7df8ad37e892: No such file or directory
cp: testBuildOrg//.git/objects/d0/d409da523500ae2d6490f698b06dfff1374e30: No such file or directory
cp: testBuildOrg//.git/objects/d0/df85f55192329ed7458f896c6fa0cb34b0093f: No such file or directory
cp: testBuildOrg//.git/objects/d0/e0fc3d865dee75f4f9ff09f23579ad6534f6a6: No such file or directory
cp: testBuildOrg//.git/objects/d0/ec5cf09735418e52e6fad05bd09f7683411d4b: No such file or directory
cp: testBuildOrg//.git/objects/d0/f5fbf3edd8227f316e016033e6a6dd006ea3ca: No such file or directory
cp: testBuildOrg//.git/objects/d2/f03460e4c0bc92a8f436d1f2f8197598d90f25: No such file or directory
cp: testBuildOrg//.git/objects/d2/f1e25a5f7a819f30ff043a46d2c56da5c46491: No such file or directory
cp: testBuildOrg//.git/objects/d2/f720e1e98e115919401c622930fae967fe9d41: No such file or directory
cp: testBuildOrg//.git/objects/d3/584ead34d52d7aea3ff7b4a35a242f2d12acf1: No such file or directory
cp: testBuildOrg//.git/objects/d3/5862c3f6b680fc49e854ae1d469d96b2988d1e: No such file or directory
cp: testBuildOrg//.git/objects/d3/67ff83e2d7e3a84ede4959a8d755c8378ab51f: No such file or directory
cp: testBuildOrg//.git/objects/d3/683045e8aac28bfa6434c1132b0384e847ebb9: No such file or directory
cp: testBuildOrg//.git/objects/d3/6b81d575c294e3070968527a2e2bcdfa8b8180: No such file or directory
cp: testBuildOrg//.git/objects/d3/7c3ccaf39ee44000294736ffcda549a62b21a0: No such file or directory
cp: testBuildOrg//.git/objects/d3/7c8951f1245436114c2b06ab0f059463a84b2a: No such file or directory
cp: testBuildOrg//.git/objects/d3/7e5f04ffa8988693d8bbc29fc89c7abf9001a0: No such file or directory
cp: testBuildOrg//.git/objects/d3/7f81ddbc89899f9ee7c3fca7b58cb56ce7a464: No such file or directory
cp: testBuildOrg//.git/objects/d3/8acf52b2b208f283a25f86ea129b19d18c94bb: No such file or directory
cp: testBuildOrg//.git/objects/d3/8c28914046c7630a3371def865e2f1dce8115f: No such file or directory
cp: testBuildOrg//.git/objects/d3/9b56691f7d3dfdd96028b870aa4ac030bef440: No such file or directory
cp: testBuildOrg//.git/objects/d3/9db2cd1e3538378b95e500fb91b9d523043874: No such file or directory
cp: testBuildOrg//.git/objects/d3/a2e669a64ca5fea712d7e6d3e8bf4e0ee3b31b: No such file or directory
cp: testBuildOrg//.git/objects/d3/a5bacf99dabd992d7e1887587981f98fe8be87: No such file or directory
cp: testBuildOrg//.git/objects/d3/ab385599034125be25fe56acd6073efdb5d44e: No such file or directory
cp: testBuildOrg//.git/objects/d3/ae972944773dfd916540ee8c93403e4ff83dec: No such file or directory
cp: testBuildOrg//.git/objects/d3/af4e054307c6f5e27468ea0565f36655c2a8bd: No such file or directory
cp: testBuildOrg//.git/objects/d3/b6e7bc048707b25ccb9584f27931fde819d22d: No such file or directory
cp: testBuildOrg//.git/objects/d3/b8d6186ce24668c2ea453a7121b078c8644921: No such file or directory
cp: testBuildOrg//.git/objects/d3/c5b5051e2b02662eed7dda6836dce2a5977d7a: No such file or directory
cp: testBuildOrg//.git/objects/d3/cc455e95d42ce4a3463f521a99c914b064719b: No such file or directory
cp: testBuildOrg//.git/objects/d3/dc9dace894d50122cb3c536633a465b01be757: No such file or directory
cp: testBuildOrg//.git/objects/d3/e4a8f5115523a25eab632637efb02e2e5074f8: No such file or directory
cp: testBuildOrg//.git/objects/d3/e82d01ec9cac437547d2443ec399e65ce789c9: No such file or directory
cp: testBuildOrg//.git/objects/d3/ea6cd4efbedfb4e17794b03ca09c3610b350f5: No such file or directory
cp: testBuildOrg//.git/objects/d3/eb4ff62326c42fba0c6db71ad2f17d24edb061: No such file or directory
cp: testBuildOrg//.git/objects/d3/ebdb1a73d34bea83543b49395e5d6440dd7148: No such file or directory
cp: testBuildOrg//.git/objects/d3/ee6f54e4ca9ed618b4117585cc7c76dfddc391: No such file or directory
cp: testBuildOrg//.git/objects/d3/f25e5321a153ed60f3be5ecd32fa45f946fb21: No such file or directory
cp: testBuildOrg//.git/objects/d3/f8238008d5ba71e6967aaa824834347bf792c5: No such file or directory
cp: testBuildOrg//.git/objects/d3/fab72dc273e1ea5da9eebd85e77af6ef718dc1: No such file or directory
cp: testBuildOrg//.git/objects/d3/fc1ce7f72c3d79712ec058fb96974e2aa43d33: No such file or directory
cp: testBuildOrg//.git/objects/d6/d45d83549fcd95d2d69a5e53ae38a68fec9b52: No such file or directory
cp: testBuildOrg//.git/objects/d6/d804510b66a319f4a76ae7519563048773c4bb: No such file or directory
cp: testBuildOrg//.git/objects/d6/dd8229045cfa4af3fa93700b9a862990f60417: No such file or directory
cp: testBuildOrg//.git/objects/d6/e20c06579a04717abadcb198766fd3dc74b2be: No such file or directory
cp: testBuildOrg//.git/objects/d6/e22204de2ff90981bab69250df202c227d2d67: No such file or directory
cp: testBuildOrg//.git/objects/d6/e7601dbbb0c7e7a43a2c458771cfc364332171: No such file or directory
cp: testBuildOrg//.git/objects/d6/e96bb8397b224c9105d8553d7131e46f051469: No such file or directory
cp: testBuildOrg//.git/objects/d6/f3e520fbeba86cfd9e6426c88d0a580aaba6cc: No such file or directory
cp: testBuildOrg//.git/objects/d6/fd752f7282839dc40ab607ecc7e90b522f1201: No such file or directory
cp: testBuildOrg//.git/objects/d6/ffa04d01cd8d93460d7dd4321c06847c56b4e8: No such file or directory
cp: testBuildOrg//.git/objects/d6/ffbe507fa341bbe4cfe66464fc720933d184b6: No such file or directory
cp: testBuildOrg//.git/objects/d7/ab8ef92b6f8d89b7377f61714996cda90202c7: No such file or directory
cp: testBuildOrg//.git/objects/d7/ac08580153ad37e26ecddfc08a3575cffdcc67: No such file or directory
cp: testBuildOrg//.git/objects/d7/b2a31c3b4382c6aa377726962eba2c4aded998: No such file or directory
cp: testBuildOrg//.git/objects/d7/b5f0ec1abb06e51db653f43151d1265342f804: No such file or directory
cp: testBuildOrg//.git/objects/d7/c14b68bdb6b752ee8248c18813efe9ffcb08cc: No such file or directory
cp: testBuildOrg//.git/objects/d7/c4b8aed009a0e7482c42bd5702ff6b748fcd2c: No such file or directory
cp: testBuildOrg//.git/objects/d7/d3b81e56d973b6cf55ba8c616d622062aeda8e: No such file or directory
cp: testBuildOrg//.git/objects/d7/e175b6101a6bf322335a0fd7e9175b2233132d: No such file or directory
cp: testBuildOrg//.git/objects/d7/e3aa90637f84d7136e53c3c689cad058afdda7: No such file or directory
cp: testBuildOrg//.git/objects/d7/eb1bc2fda9a7487c97f71da389ffdd65ad6b4e: No such file or directory
cp: testBuildOrg//.git/objects/d7/ec47e2e3aa8e49938670c7660ab842749f904e: No such file or directory
cp: testBuildOrg//.git/objects/d7/f104f0c81042083348cda77f8b94e915340805: No such file or directory
cp: testBuildOrg//.git/objects/d7/f11c821188956fb7da031881c86a797c54ad14: No such file or directory
cp: testBuildOrg//.git/objects/d7/f2772ff78b5479b73be6a1a58dd9ffd1b0a359: No such file or directory
cp: testBuildOrg//.git/objects/d7/f769e9ecb16ebbe304091c5aafba39c66fd192: No such file or directory
cp: testBuildOrg//.git/objects/d7/fc59b52dfc2505b131d2080d046200e32f91ef: No such file or directory
cp: testBuildOrg//.git/objects/d8/610c63bdde14817961e5237f9588c9dfff5230: No such file or directory
cp: testBuildOrg//.git/objects/d8/702f102ea570fa51c7f146bfa911fc5527c96b: No such file or directory
cp: testBuildOrg//.git/objects/d8/70626ec2731f2b501a2b8c939aa0f7b4b4ec5a: No such file or directory
cp: testBuildOrg//.git/objects/d8/7d04cd4d4e77f6de665eef8d769cda2c558936: No such file or directory
cp: testBuildOrg//.git/objects/d8/807588af775c2dcd75c87b8ac01218a672ef26: No such file or directory
cp: testBuildOrg//.git/objects/d8/80bacaff7549c17b50d83f9662055f368468a9: No such file or directory
cp: testBuildOrg//.git/objects/d8/865d939b3ebc30494650d529c7b9912654633b: No such file or directory
cp: testBuildOrg//.git/objects/d8/87d2a7a1334d1c43989954d78919e1fe66498c: No such file or directory
cp: testBuildOrg//.git/objects/d8/9834080220d78bf4de757c70156385dd68f5f3: No such file or directory
cp: testBuildOrg//.git/objects/d8/9f914a4a702c7ea6d4c5b4576b35cb1f6d9b0a: No such file or directory
cp: testBuildOrg//.git/objects/d8/aa3936c53f116c0871507f419ae7b03a391f15: No such file or directory
cp: testBuildOrg//.git/objects/d8/b316ddb5c87c75f2918b61334791c0d52a8318: No such file or directory
cp: testBuildOrg//.git/objects/d8/b3172cbbf07e7bafc15f13e66a41c3805ef5f4: No such file or directory
cp: testBuildOrg//.git/objects/d8/b4ed8036e5782347452a9a9f8016b5709285d7: No such file or directory
cp: testBuildOrg//.git/objects/d8/c4a66a52b0c6da5df49d124503ad2ee529889c: No such file or directory
cp: testBuildOrg//.git/objects/d8/cbdc292a23e79b1981d286e907b99d95384b91: No such file or directory
cp: testBuildOrg//.git/objects/d8/d84a56e7df43727748500da26adcc4ab9b643f: No such file or directory
cp: testBuildOrg//.git/objects/d8/dcb62522a3854742827bd25538338c32d424fc: No such file or directory
cp: testBuildOrg//.git/objects/dc/8ad7e70758e736ce8b45bde79dce10625db7bb: No such file or directory
cp: testBuildOrg//.git/objects/dc/8f4623ec6958bf93441a6638f55848409f4250: No such file or directory
cp: testBuildOrg//.git/objects/dc/92c329d3ba660755e2daad29a80cf8145876a4: No such file or directory
cp: testBuildOrg//.git/objects/dc/95b3fc2fb51f796ecd2a174ae7d4e48b15b1e5: No such file or directory
cp: testBuildOrg//.git/objects/dc/96973fa03f5fb09d4a555475b2b72d4e60fac8: No such file or directory
cp: testBuildOrg//.git/objects/dc/9a88f71cf894e8f80923ec616d3917d4f47ce7: No such file or directory
cp: testBuildOrg//.git/objects/dc/9ea5de1f1b1ca589629c7232bb3be199bf5776: No such file or directory
cp: testBuildOrg//.git/objects/dc/a05f13812e042d3b52cd99695855191d330aaa: No such file or directory
cp: testBuildOrg//.git/objects/dc/a7083384cae803933ccbae443118405433a4e4: No such file or directory
cp: testBuildOrg//.git/objects/dc/b31f536f204bc363f6dc173975613a4ca1098d: No such file or directory
cp: testBuildOrg//.git/objects/dc/b771b6d2bfe80944e42077e8e5baac4703aad4: No such file or directory
cp: testBuildOrg//.git/objects/dc/b98ea4907c157239947ee1fb10e6ac62fed195: No such file or directory
cp: testBuildOrg//.git/objects/dc/bba31b413296b58e1af334d0bc0881c8f975d6: No such file or directory
cp: testBuildOrg//.git/objects/dc/c45a865445c4622f8b2c9d9492c87be3e7def4: No such file or directory
cp: testBuildOrg//.git/objects/dc/c919024fde7767db35a6cd887de4fb58037f02: No such file or directory
cp: testBuildOrg//.git/objects/dc/c9c36a093a5184bc69782bf5d9929bd97a360e: No such file or directory
cp: testBuildOrg//.git/objects/dc/ccbc3fdf5d00b18f5d02a862ba1d3e0d63b88f: No such file or directory
cp: testBuildOrg//.git/objects/dc/ccc25ebed34681f4bcc49c347ea1b4445f119a: No such file or directory
cp: testBuildOrg//.git/objects/dc/cdeed448e2de77e1565fddf21eeb6718997314: No such file or directory
cp: testBuildOrg//.git/objects/dc/ce35e5980e7e5c7dbc724d103036dcc0fc173b: No such file or directory
cp: testBuildOrg//.git/objects/dc/cebd765a2458f594f8d4dca79ef45dc921b2c8: No such file or directory
cp: testBuildOrg//.git/objects/dc/cf6dfa491f86eb7aefe30f81ae2b2fb6cd2dc8: No such file or directory
cp: testBuildOrg//.git/objects/dc/d43fa10e47ac9afc5b0a5d87dda2394c50fa5b: No such file or directory
cp: testBuildOrg//.git/objects/dc/dcc854e6ac7aa30db5cb7f78226de865712a11: No such file or directory
cp: testBuildOrg//.git/objects/dc/dfa3cfd45cb9d7671e4be3062b75a79a005175: No such file or directory
cp: testBuildOrg//.git/objects/dc/e880f4c1c7b6e667afd7262c7bbe7201d16b78: No such file or directory
cp: testBuildOrg//.git/objects/dc/eaf03306e7e2f16ef32e964cabc0f53955fb83: No such file or directory
cp: testBuildOrg//.git/objects/dc/eb906abc3bbf7c4a90342dba5a5b3664c6a677: No such file or directory
cp: testBuildOrg//.git/objects/dc/f02066d823cdd7cccc90013d9d79ad713b0b76: No such file or directory
cp: testBuildOrg//.git/objects/dc/f24c17a93718ff0e732d31742a41a5975c8a69: No such file or directory
cp: testBuildOrg//.git/objects/dc/f3b3864722f4d8b16c605dee50d7548286e6e3: No such file or directory
cp: testBuildOrg//.git/objects/dc/fe20cf80396c4b4d070b9b1b33192ebc9ade69: No such file or directory
cp: testBuildOrg//.git/objects/e8/6cd55cdfddf15bfded67101e3b7bc009bbcdf3: No such file or directory
cp: testBuildOrg//.git/objects/e8/708b11b47da0637247e697cc86b78e6b6c419b: No such file or directory
cp: testBuildOrg//.git/objects/e8/7fad44e178d1b801545026ad87b065289c26f1: No such file or directory
cp: testBuildOrg//.git/objects/e8/8443ca14cf63c3689d9f686097755d1470b5a4: No such file or directory
cp: testBuildOrg//.git/objects/e8/87174af3b27bd75ef2d70537076792e9079401: No such file or directory
cp: testBuildOrg//.git/objects/e8/91c50ff78538b340dfdc860771682250eca5b6: No such file or directory
cp: testBuildOrg//.git/objects/e8/92c784f8c97afa003ce83dc692cf7784e8ce8d: No such file or directory
cp: testBuildOrg//.git/objects/e8/9878055cf36bc9abbc0ff734c9361762abcab3: No such file or directory
cp: testBuildOrg//.git/objects/e8/99f867450a44c63e3f17dbbe0ad9d35ce89b16: No such file or directory
cp: testBuildOrg//.git/objects/e8/9ebacd126992c1e7f63f0205078e0dbf13ad0d: No such file or directory
cp: testBuildOrg//.git/objects/e8/b0bed5bf35f95ffdf37fac8b3862418f8de4a7: No such file or directory
cp: testBuildOrg//.git/objects/e8/be9a4eadea53c1d491ca37025902195f291138: No such file or directory
cp: testBuildOrg//.git/objects/e8/c170842e319df88b7d509cc75c47381215aeac: No such file or directory
cp: testBuildOrg//.git/objects/e8/c4d09a3c969f264ed44bdbfb5ac109c52fc1ac: No such file or directory
cp: testBuildOrg//.git/objects/e8/cca64c10d19970cf8b61545a162dd2a6af5e67: No such file or directory
cp: testBuildOrg//.git/objects/e8/ce7770d52ddbbdc449add3370c5a520ee3e5d8: No such file or directory
cp: testBuildOrg//.git/objects/e8/da54caff8f73ca02d74f4b98ea74c9e771c9c5: No such file or directory
cp: testBuildOrg//.git/objects/e8/dd24c26dad7e78f70d07e6376f24d9c11ff0ca: No such file or directory
cp: testBuildOrg//.git/objects/e8/df84e25e76ecbf797c6890d672801195cf014e: No such file or directory
cp: testBuildOrg//.git/objects/e8/e55f3039829d4bed457ae623cc06821513d95a: No such file or directory
cp: testBuildOrg//.git/objects/e8/e63fcb4123428c493a67c1832d82265da604c3: No such file or directory
cp: testBuildOrg//.git/objects/e8/ef668c59da39f49f5d1ceb0214733e76723f67: No such file or directory
cp: testBuildOrg//.git/objects/e8/f5d92134c19a1c3595520809a9d426437dbd8b: No such file or directory
cp: testBuildOrg//.git/objects/e8/f72332bd3c2ed685ebf3b87a0b25f6bb1aab5a: No such file or directory
cp: testBuildOrg//.git/objects/e8/fb1f84d5366f01764af19a4f9386f6849b400a: No such file or directory
cp: testBuildOrg//.git/objects/e8/fe6c58a882c2f94237b6b6446082e2477dcd0d: No such file or directory
cp: testBuildOrg//.git/objects/e9/c6fa8d79c0d4147f2f1bfccdc68aae33f79d12: No such file or directory
cp: testBuildOrg//.git/objects/e9/cbca6d87cc9ba34e34008bd683ac764c235690: No such file or directory
cp: testBuildOrg//.git/objects/e9/d1df71242c3c17fb0588c29a7db08f14827d50: No such file or directory
cp: testBuildOrg//.git/objects/e9/d6c16923f6499b57625d36c9573099a5578a7a: No such file or directory
cp: testBuildOrg//.git/objects/e9/e350ab511b612d3b891673550fa21a785bcf31: No such file or directory
cp: testBuildOrg//.git/objects/e9/e52642f9cac9309830f4c8f383d643f6ea20a7: No such file or directory
cp: testBuildOrg//.git/objects/e9/e7eb804e3c4a4d467a9cb3271c91009e5e5439: No such file or directory
cp: testBuildOrg//.git/objects/e9/eaebda19c94f00197bb5cb6c37f2092f1f2e84: No such file or directory
cp: testBuildOrg//.git/objects/e9/ebe3f69b71541f3264b393876ff2db949e4042: No such file or directory
cp: testBuildOrg//.git/objects/e9/effd805e1205d2817431ee0efa2535e7eeb06b: No such file or directory
cp: testBuildOrg//.git/objects/e9/f6171291bc462b2e5b10153e5ade209a20a326: No such file or directory
cp: testBuildOrg//.git/objects/ea/87f9ec813b42c477bb8ba036c4d9ec6654e671: No such file or directory
cp: testBuildOrg//.git/objects/ea/88be4243207750ac283da3131366fc368ac5f3: No such file or directory
cp: testBuildOrg//.git/objects/ea/896ac6f21e97f7084cb695011ce3bc0453b646: No such file or directory
cp: testBuildOrg//.git/objects/ea/8f8f1d703ef089f880058b693fc3074a80f33c: No such file or directory
cp: testBuildOrg//.git/objects/ea/9047a000066b8363b4a6505165d8c3bb91fd7a: No such file or directory
cp: testBuildOrg//.git/objects/ea/991af313f1d5d0828f52236768ab78a08e9fed: No such file or directory
cp: testBuildOrg//.git/objects/ea/a083569bf43fe1a787a23fd1740abf38a61b39: No such file or directory
cp: testBuildOrg//.git/objects/ea/a32edd31533aee4a3fb251dcd52467ad06f06f: No such file or directory
cp: testBuildOrg//.git/objects/ea/a83f7e67d9d791ce2c72dfbea5a94f9e30b5d6: No such file or directory
cp: testBuildOrg//.git/objects/ea/a90a9f3e49aa843650e6ff0c7fd43f67a3e539: No such file or directory
cp: testBuildOrg//.git/objects/ea/a9e63c180bfa76e3fc9fd11412628cd8277235: No such file or directory
cp: testBuildOrg//.git/objects/ea/b32a598a20925d718ef66e3288a1b85f613ca2: No such file or directory
cp: testBuildOrg//.git/objects/ea/b82cf481a0092c3d3c85f0cce52ecd48126537: No such file or directory
cp: testBuildOrg//.git/objects/ea/b9c506b8f3d440e8df8e58bdbf7796f9f1b5c8: No such file or directory
cp: testBuildOrg//.git/objects/ea/d9dec3414b19a669bb8216a269b694fa914334: No such file or directory
cp: testBuildOrg//.git/objects/ea/deeb5169783069fab8a211b9c7031b411ef5c8: No such file or directory
cp: testBuildOrg//.git/objects/ea/e3c6a7a80a2d85990e29aee5784de2f518a7f6: No such file or directory
cp: testBuildOrg//.git/objects/ea/e5cbaf5cf60565e4b6bbc0144ad371ba15e7f5: No such file or directory
cp: testBuildOrg//.git/objects/ea/e68b20091568667226df587a7a94717cc9a499: No such file or directory
cp: testBuildOrg//.git/objects/ea/ed2159cd05c0bc89869510915ab50e209b6ea7: No such file or directory
cp: testBuildOrg//.git/objects/ea/f891361187765be848d9f9822cb4b6273fc361: No such file or directory
cp: testBuildOrg//.git/objects/ea/fb8b6103bd3eecd1fbbc4b68478408950bc7d0: No such file or directory
cp: testBuildOrg//.git/objects/ea/fca6d914bcea230da7091e586e50c0da8e8524: No such file or directory
cp: testBuildOrg//.git/objects/f2: unable to copy extended attributes to testBuild/.git/objects/f2: No such file or directory
cp: testBuildOrg//.git/objects/f2: No such file or directory
cp: testBuildOrg//.git/objects/f9/b8270a5b87e44af1c1abe952116132f68aef14: No such file or directory
cp: testBuildOrg//.git/objects/f9/b9191176cbc78c6e2afe24e0a2e2d69201fb5e: No such file or directory
cp: testBuildOrg//.git/objects/f9/c2e51288c11e53b79d442bf0c1e0358bb1e6a1: No such file or directory
cp: testBuildOrg//.git/objects/f9/d14e624bec19b9d67fc24e52a3852f27525440: No such file or directory
cp: testBuildOrg//.git/objects/f9/d38962a49c6920a94ad00c48f84f5c104f8843: No such file or directory
cp: testBuildOrg//.git/objects/f9/de2fa297271654fcdc92b9d23e9aa45709c037: No such file or directory
cp: testBuildOrg//.git/objects/f9/e3213b7621ee082e4f78c44b54960ccd21401e: No such file or directory
cp: testBuildOrg//.git/objects/f9/e4b61df560ce5ed1f8c86f6342ca7db67c3c57: No such file or directory
cp: testBuildOrg//.git/objects/f9/e802ec7ea426fb9d870d0df9cf0eeb8812f2bd: No such file or directory
cp: testBuildOrg//.git/objects/f9/ee7508db3b04e715dcf72c9c71d04039e62572: No such file or directory
cp: testBuildOrg//.git/objects/fa/73c6b0420f2f230ba755ec889598396d501818: No such file or directory
cp: testBuildOrg//.git/objects/fa/7bd0c53136301400b0e00c0a8035872c6bdbe6: No such file or directory
cp: testBuildOrg//.git/objects/fa/7d054f1b8133fa8304f53daf53b79af5e250f2: No such file or directory
cp: testBuildOrg//.git/objects/fa/812e1dacb8cfe7f8e3f6b297ade43f4adcc6f7: No such file or directory
cp: testBuildOrg//.git/objects/fa/888ad3ed47a32d3632bfc1fc636695fe72dcbb: No such file or directory
cp: testBuildOrg//.git/objects/fa/90c80532cbe38d0e7646d298e5c94e2fc9987c: No such file or directory
cp: testBuildOrg//.git/objects/fa/91ca3cb524b09149f3e76de4a10c59c3310ab9: No such file or directory
cp: testBuildOrg//.git/objects/fa/933d09d535fcd5e9809b2eeeec7149b0bca1ab: No such file or directory
cp: testBuildOrg//.git/objects/fa/94ec7be56dc80ad121707a4e8e082d60012f5e: No such file or directory
cp: testBuildOrg//.git/objects/fa/acf1d163297a8d0a4917726580f71f1a16a24e: No such file or directory
cp: testBuildOrg//.git/objects/fa/af6901fc6c2530363e10eeca437c6093402642: No such file or directory
cp: testBuildOrg//.git/objects/fa/bdb7e41f251c880498c7908ae00b6827ace055: No such file or directory
cp: testBuildOrg//.git/objects/fa/c73c7931fa32e6808c936b1c377cdb760b9e4e: No such file or directory
cp: testBuildOrg//.git/objects/fa/c78de38538ee78fa2b523758c892c6cd7e8123: No such file or directory
cp: testBuildOrg//.git/objects/fa/d6cfedf288d4db56016aeeac3b326e3d25a9ec: No such file or directory
cp: testBuildOrg//.git/objects/fa/d9524a09202314cc866806e6e3eeb1f548788a: No such file or directory
cp: testBuildOrg//.git/objects/fa/e2ac926d55629096cc3669482466a57c0d1a0e: No such file or directory
cp: testBuildOrg//.git/objects/fa/edfd5b903653c0d2fd73b24d5096ce21e907a1: No such file or directory
cp: testBuildOrg//.git/objects/fa/f5c06dee410eb74f265edf65d3cf6b1b8b244e: No such file or directory
cp: testBuildOrg//.git/objects/fa/f65e07f68f84be9cfc1a8355aa34b435f6f3c7: No such file or directory
cp: testBuildOrg//.git/objects/fa/fd3982709eaae8623e29fb76f2c9ab054e315b: No such file or directory
cp: testBuildOrg//.git/objects/fa/fe3d897fa180bc6e2c02543502dd22d58d61ed: No such file or directory
cp: testBuildOrg//.git/objects/fb/3891b3ee64f47e247c497e01cb0dff1fd1f97d: No such file or directory
cp: testBuildOrg//.git/objects/fb/40a6c0b1f6e489ac3146522e253e5ededcc584: No such file or directory
cp: testBuildOrg//.git/objects/fb/482c843fbb0c9de300932ac34fc45b57bfe44b: No such file or directory
cp: testBuildOrg//.git/objects/fb/4878968c4b651bce5c1ebbbcc2558b6818954a: No such file or directory
cp: testBuildOrg//.git/objects/fb/49b5ead17792e58d461cd0746bbe08c10fa7de: No such file or directory
cp: testBuildOrg//.git/objects/fb/53f385e4862c93688272dfeabb44668527d6e4: No such file or directory
cp: testBuildOrg//.git/objects/fb/62ea7e318e8001145ba85c30be4d77fdb61211: No such file or directory
cp: testBuildOrg//.git/objects/fb/64fa4ca9eb1e75f93303f2265d764b343e9794: No such file or directory
cp: testBuildOrg//.git/objects/fb/6d91c6d8e30adc9587f0a54ecdd1a7f3132db3: No such file or directory
cp: testBuildOrg//.git/objects/fb/70d68b05f95c8deb7f0652cbb8fc3261421396: No such file or directory
cp: testBuildOrg//.git/objects/fb/7fd53e17628b3f905696ad4789743420ba099b: No such file or directory
cp: testBuildOrg//.git/objects/fb/88aa5db2610d68d6d34799bd464fea8d6634eb: No such file or directory
cp: testBuildOrg//.git/objects/fb/8b6c14ab8281be5bbf84638178f4d10f62ab34: No such file or directory
cp: testBuildOrg//.git/objects/fb/9272b68ee1fede93ab83f2afaa51f46af2e5a6: No such file or directory
cp: testBuildOrg//.git/objects/fb/ab494773e49b31ca5734921b902d229f991d29: No such file or directory
cp: testBuildOrg//.git/objects/fb/b1b27a665ea42ed7c0aaef3fcc4e9711962196: No such file or directory
cp: testBuildOrg//.git/objects/fb/b22d25b2e4605fd40ec3c31c65b6c81ff2a572: No such file or directory
cp: testBuildOrg//.git/objects/fb/b488a9df299e648045089c16a420ca9862373e: No such file or directory
cp: testBuildOrg//.git/objects/fb/c6a5ebe451bb27de396c726ec3891f6690d299: No such file or directory
cp: testBuildOrg//.git/objects/fb/c720e48a3e1ae9cafd4ac74a27cd4f0c434e95: No such file or directory
cp: testBuildOrg//.git/objects/fb/ce2387518065de7a8dbcd20b6c3de014de8bae: No such file or directory
cp: testBuildOrg//.git/objects/fb/d53591136e4ef357ced951c1a78d8c8971212b: No such file or directory
cp: testBuildOrg//.git/objects/fb/d72fe4aeb4fffbab32e67e616b47e91405243a: No such file or directory
cp: testBuildOrg//.git/objects/fb/d8d4f7dcb774143ac72b421e41b54ae7c944ca: No such file or directory
cp: testBuildOrg//.git/objects/fb/ddcb489f229186b40c2858560d5c2b216b5c25: No such file or directory
cp: testBuildOrg//.git/objects/fb/e843926443d51e70223ab123f4e57917b570fc: No such file or directory
cp: testBuildOrg//.git/objects/fb/fed8f1d7df4495ded7cfff5aac4acaabd359ec: No such file or directory
cp: testBuildOrg//.git/objects/fc/9f7d3fa55719c44b048f63e3f12be4c564aaa7: No such file or directory
cp: testBuildOrg//.git/objects/fc/9fa6f146b04765f20140e6c8b6afb5da277899: No such file or directory
cp: testBuildOrg//.git/objects/fc/b2e773f8da16b99972459a0be68fbef56f5ea9: No such file or directory
cp: testBuildOrg//.git/objects/fc/b3114927c194b051c714cab0fb29ff602ec306: No such file or directory
cp: testBuildOrg//.git/objects/fc/b904fd247e05224771a4153894850f3ef80581: No such file or directory
cp: testBuildOrg//.git/objects/fc/c46903369ec497f9b777881a67060f5e2fce7f: No such file or directory
cp: testBuildOrg//.git/objects/fc/c7f1711f4e9b378fdd48c5f31a1278bd9e7c94: No such file or directory
cp: testBuildOrg//.git/objects/fc/cc2691b6095b3d7b9674b5d680bbe894ab3ee7: No such file or directory
cp: testBuildOrg//.git/objects/fc/cea7e88e56be399f07ec44c0d717ba4f438ee9: No such file or directory
cp: testBuildOrg//.git/objects/fc/dc31b81da2f98f626a7f15604b9935cee18e95: No such file or directory
cp: testBuildOrg//.git/objects/fc/f0eb996a97e16e9e7152077ffe0cdb9aaeb727: No such file or directory
cp: testBuildOrg//.git/objects/fc/f4b31ec06a85611d976b377fa38e6a9f2caa3a: No such file or directory
cp: testBuildOrg//.git/objects/fd/7eafcb617794330ae8e966601f3802b476354e: No such file or directory
cp: testBuildOrg//.git/objects/fd/83edafc2d69c3cf3ee27f08b6b34d18d602de1: No such file or directory
cp: testBuildOrg//.git/objects/fd/8a85244b3b7c02bc487bc6ca5c1bd9f8a65e6a: No such file or directory
cp: testBuildOrg//.git/objects/fd/8d22b68c82dbfc27003698b132288710fea842: No such file or directory
cp: testBuildOrg//.git/objects/fd/a5ffe3156fc8e984575384970805c9c7f2fb14: No such file or directory
cp: testBuildOrg//.git/objects/fd/a7c0b5ec1d5a867275a2c189e4e4bb51091be4: No such file or directory
cp: testBuildOrg//.git/objects/fd/a9f42f245e48cc140537e86cde9cdc301a80ce: No such file or directory
cp: testBuildOrg//.git/objects/fd/ae11fa91338d087b439b3e8132da14f14b5ee3: No such file or directory
cp: testBuildOrg//.git/objects/fd/c174e40cae6b0a817476ca54fc8320d4eb354c: No such file or directory
cp: testBuildOrg//.git/objects/fd/cee0cda56b6b869d44e56afe9bae086739f60d: No such file or directory
cp: testBuildOrg//.git/objects/fd/d630afb5e2d9adf7e4349fe8f516a4987e0ea7: No such file or directory
cp: testBuildOrg//.git/objects/fd/e0215087e8b7de836d0ac6454d7c4bbc90bd37: No such file or directory
cp: testBuildOrg//.git/objects/fd/e119119b56346ab1c9b35d52769bf62bf3b15a: No such file or directory
cp: testBuildOrg//.git/objects/fd/e6ef37b91ebd2e44ffc035194ff934d4e7da3c: No such file or directory
cp: testBuildOrg//.git/objects/fd/ed54dbf26ab1cf83c63e04075fc13989a92f43: No such file or directory
cp: testBuildOrg//.git/objects/fd/eec24b9ee162fabac137f2ca0def13cca35aa2: No such file or directory
cp: testBuildOrg//.git/objects/fd/ef387a0b162a06608dfc9bf2b8c957e4a027e1: No such file or directory
cp: testBuildOrg//.git/objects/fd/f1d3baaa5524b9b91430b325c0c0811f029c26: No such file or directory
cp: testBuildOrg//.git/objects/fd/fa90b74bbf0e211e2b0d93dc01224e50fdf75b: No such file or directory
cp: testBuildOrg//.git/objects/fe/1f0c4c9db965c67d9ac1e0f9b9399bb9f809dc: No such file or directory
cp: testBuildOrg//.git/objects/fe/1fc1e3d9abea4339c6511734289ea424bcbc66: No such file or directory
cp: testBuildOrg//.git/objects/fe/202a2bd7ce8ae3962717d1fcd8e46f8c33be4b: No such file or directory
cp: testBuildOrg//.git/objects/fe/21644cd1e28b23b94332d02677ca012b343438: No such file or directory
cp: testBuildOrg//.git/objects/fe/2180a49b0bf68e086fe9d37359c6f7140197c1: No such file or directory
cp: testBuildOrg//.git/objects/fe/24014906eb92396ccee5d59043e05c1def2d87: No such file or directory
cp: testBuildOrg//.git/objects/fe/31153be424c45e9aa6270840d28c321c44f55c: No such file or directory
cp: testBuildOrg//.git/objects/fe/353339cc5fbf30954744e079ba3cf756a8daa9: No such file or directory
cp: testBuildOrg//.git/objects/fe/3675ee3b662a3a127b42181e4b710a256ea256: No such file or directory
cp: testBuildOrg//.git/objects/fe/3a77a4f539be5989c9f182485364c4f6ff94bc: No such file or directory
cp: testBuildOrg//.git/objects/fe/409967af5199e1fd7ae9901be8203f0a75d6ff: No such file or directory
cp: testBuildOrg//.git/objects/fe/4721dd90a7674765c136cd16c3e270a1e6c3b5: No such file or directory
cp: testBuildOrg//.git/objects/fe/4be939245e17a63f46c06ea2dc9131a905bd8c: No such file or directory
cp: testBuildOrg//.git/objects/fe/4e202f3df00f78860a514d7fc54f1d11af789d: No such file or directory
cp: testBuildOrg//.git/objects/fe/5727b4f25e0ca7127799d4b845b7e9b628e054: No such file or directory
cp: testBuildOrg//.git/objects/fe/57564bb27ee27021546ca7385e19b88a941735: No such file or directory
cp: testBuildOrg//.git/objects/fe/5ef8653c4586b3e6bc1ec70339080617496b93: No such file or directory
cp: testBuildOrg//.git/objects/fe/5fcc49ced662dd33e6ad6b37dc54996286a67e: No such file or directory
cp: testBuildOrg//.git/objects/fe/6330e4be79057c9ac8b754192420c0d2f01c30: No such file or directory
cp: testBuildOrg//.git/objects/fe/683ba5aa8a3df6a2fa41846b055e97ba276b9c: No such file or directory
cp: testBuildOrg//.git/objects/fe/6f81afa32860254018c7fcec255ef704060b73: No such file or directory
cp: testBuildOrg//.git/objects/fe/76b7ef33113647c05c56afdfbe24d25e460aad: No such file or directory
cp: testBuildOrg//.git/objects/fe/78772b9fd0eaa0733aca495c6495cbebbbc1f8: No such file or directory
cp: testBuildOrg//.git/objects/fe/864cae1d9a176f014bb6eaf4fd342198613d4d: No such file or directory
cp: testBuildOrg//.git/objects/fe/95070ae5fea2fe278d4cfec84f8f3f71a9e566: No such file or directory
cp: testBuildOrg//.git/objects/fe/9654c538585721f465bb71f3e4e9ffde58aa3f: No such file or directory
cp: testBuildOrg//.git/objects/fe/9ea3f1c497999af85ea82ed995c5158af75f2c: No such file or directory
cp: testBuildOrg//.git/objects/fe/a0fd559489c9f931e4d4ad4315427b185182ae: No such file or directory
cp: testBuildOrg//.git/objects/fe/b2bbc6b600ad535656bbc5f2a68163686221ab: No such file or directory
cp: testBuildOrg//.git/objects/fe/ba808b3fc092feacc50f090f608f23574c863f: No such file or directory
cp: testBuildOrg//.git/objects/fe/c4474477f639451d096ca75612eda3e53a0ce8: No such file or directory
cp: testBuildOrg//.git/objects/fe/cb810296d4cfb5f427e5a8da1c2078f6ef00c2: No such file or directory
cp: testBuildOrg//.git/objects/fe/d2af1361c152c7007424a98e81ae66029d5dc0: No such file or directory
cp: testBuildOrg//.git/objects/fe/d9a857a50c6b85acfd7817c45199e280db0173: No such file or directory
cp: testBuildOrg//.git/objects/fe/df67127ea02fdc28138fe3cc46f42b00e6da93: No such file or directory
cp: testBuildOrg//.git/objects/fe/f0cc9d8ff113e8b3d04a00467a4229bf359e40: No such file or directory
cp: testBuildOrg//.git/objects/fe/f441027327e5aad02a7aab3ab88b3c5899c53a: No such file or directory
cp: testBuildOrg//.git/objects/fe/f578067e0683da663d130cd93e64f6856c9482: No such file or directory
cp: testBuildOrg//.git/objects/fe/f6fadf5eca9b757de123ec6acc1aff7ab0236d: No such file or directory
cp: testBuildOrg//.git/objects/ff/77b058cbb800341a92c2e1d9811debeccd6b03: No such file or directory
cp: testBuildOrg//.git/objects/ff/7ecb8f1f20806e9be1ac392a8dfbf15ea77a38: No such file or directory
cp: testBuildOrg//.git/objects/ff/823a7885dbe5e4849c4e518bebdaf8b297aff1: No such file or directory
cp: testBuildOrg//.git/objects/ff/8589d4167e8971976b1d831472d29b8d59e7a4: No such file or directory
cp: testBuildOrg//.git/objects/ff/85a284aa13216c03273d2bb8eca961ee6ad1ab: No such file or directory
cp: testBuildOrg//.git/objects/ff/863a6dc3b7db84b8044d918be84eddf64d6204: No such file or directory
cp: testBuildOrg//.git/objects/ff/8c1ff290ba385ff68df2cd93a022d2b53f7b8e: No such file or directory
cp: testBuildOrg//.git/objects/ff/8dafb9e6004082412bb7717e9a4014c8a156e7: No such file or directory
cp: testBuildOrg//.git/objects/ff/911f6bbb0e1380e5dc231706d6e0582ab88cc9: No such file or directory
cp: testBuildOrg//.git/objects/ff/923cdec1b389eae4b87320daa242928c9b81bf: No such file or directory
cp: testBuildOrg//.git/objects/ff/92f4bb5fa60f693f63303d86e4f6ed7274a85a: No such file or directory
cp: testBuildOrg//.git/objects/ff/9b09190bb93e9417ac042c026975ef1dda5212: No such file or directory
cp: testBuildOrg//.git/objects/ff/ae00f65bd9ca7b700620325a064a715c05ff24: No such file or directory
cp: testBuildOrg//.git/objects/ff/b14ce03656af904474359febb0e40d51b1f019: No such file or directory
cp: testBuildOrg//.git/objects/ff/b651022788e995003ba03eeb0a8330c5e115ae: No such file or directory
cp: testBuildOrg//.git/objects/ff/c7a76147102fb41fd4d8a40081a144ea554ad7: No such file or directory
cp: testBuildOrg//.git/objects/ff/cc7a56f3f8fbbe267f54c55b5d9b747ca03ba6: No such file or directory
cp: testBuildOrg//.git/objects/ff/ccd69469bd9ae9f6fc5286da085eb2caab2a04: No such file or directory
cp: testBuildOrg//.git/objects/ff/ce09b6cb038d0d8c61376bcea2590c7ab567c5: No such file or directory
cp: testBuildOrg//.git/objects/ff/d022733d52591bf0a7e28543890e7c4a4dd58d: No such file or directory
cp: testBuildOrg//.git/objects/ff/d2bfe34a7357a0fed764d8850beda430dc5be7: No such file or directory
cp: testBuildOrg//.git/objects/ff/da1b4b35362a5a6d6c5d7d0b398712ae965ca7: No such file or directory
cp: testBuildOrg//.git/objects/ff/dfe90284091a8992537089ecbd5537d8aba36f: No such file or directory
cp: testBuildOrg//.git/objects/ff/e7a1c73eb78523d049e40e4c366773d6da3418: No such file or directory
cp: testBuildOrg//.git/objects/ff/e9ac362c4b9bc32a07cfd2f65f5370b45b7e58: No such file or directory
cp: testBuildOrg//.git/objects/ff/e9f380d97c6aa31b006a496caa8b8237b623ff: No such file or directory
cp: testBuildOrg//.git/objects/ff/efeb465376d0c9dbb408b5f92b68f92f47fefa: No such file or directory
cp: testBuildOrg//.git/objects/ff/fa4574636b3a86f2a18a0650b08673e6e04775: No such file or directory
cp: testBuildOrg//.git/objects/ff/fd6a1c8f09343823886e0f43a144145144c547: No such file or directory
npm http request GET http://192.168.1.100:4873/fs-extra-promise
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/socket.io
npm http request GET http://192.168.1.100:4873/express
npm http 200 http://192.168.1.100:4873/lie
npm http 200 http://192.168.1.100:4873/fs-extra-promise
npm http 200 http://192.168.1.100:4873/winston
npm http 304 http://192.168.1.100:4873/socket.io
npm http 200 http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/accepts
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/content-disposition
npm http request GET http://192.168.1.100:4873/array-flatten
npm http request GET http://192.168.1.100:4873/cookie-signature
npm http request GET http://192.168.1.100:4873/cookie
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/etag
npm http request GET http://192.168.1.100:4873/escape-html
npm http request GET http://192.168.1.100:4873/parseurl
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/fresh
npm http request GET http://192.168.1.100:4873/merge-descriptors
npm http request GET http://192.168.1.100:4873/finalhandler
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/range-parser
npm http request GET http://192.168.1.100:4873/utils-merge
npm http request GET http://192.168.1.100:4873/send
npm http request GET http://192.168.1.100:4873/path-to-regexp
npm http request GET http://192.168.1.100:4873/proxy-addr
npm http request GET http://192.168.1.100:4873/vary
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/serve-static
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/accepts
npm http 200 http://192.168.1.100:4873/content-disposition
npm http 200 http://192.168.1.100:4873/array-flatten
npm http 200 http://192.168.1.100:4873/cookie-signature
npm http 200 http://192.168.1.100:4873/cookie
npm http 200 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/escape-html
npm http 200 http://192.168.1.100:4873/etag
npm http 200 http://192.168.1.100:4873/debug
npm http 200 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 200 http://192.168.1.100:4873/methods
npm http 200 http://192.168.1.100:4873/fresh
npm http 200 http://192.168.1.100:4873/on-finished
npm http 200 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/utils-merge
npm http 200 http://192.168.1.100:4873/qs
npm http 200 http://192.168.1.100:4873/range-parser
npm http 200 http://192.168.1.100:4873/send
npm http 200 http://192.168.1.100:4873/path-to-regexp
npm http 200 http://192.168.1.100:4873/proxy-addr
npm http 200 http://192.168.1.100:4873/vary
npm http 200 http://192.168.1.100:4873/type-is
npm http 304 http://192.168.1.100:4873/serve-static
npm http request GET http://192.168.1.100:4873/negotiator
npm http request GET http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/negotiator
npm http 200 http://192.168.1.100:4873/mime-types
npm http request GET http://192.168.1.100:4873/mime-db
npm http 304 http://192.168.1.100:4873/mime-db
npm http request GET http://192.168.1.100:4873/ms
npm http 200 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/unpipe
npm http 200 http://192.168.1.100:4873/unpipe
npm http request GET http://192.168.1.100:4873/ee-first
npm http 304 http://192.168.1.100:4873/ee-first
npm http request GET http://192.168.1.100:4873/forwarded
npm http request GET http://192.168.1.100:4873/ipaddr.js
npm http 200 http://192.168.1.100:4873/forwarded
npm http 200 http://192.168.1.100:4873/ipaddr.js
npm http request GET http://192.168.1.100:4873/mime
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/statuses
npm http 200 http://192.168.1.100:4873/destroy
npm http 304 http://192.168.1.100:4873/statuses
npm http 200 http://192.168.1.100:4873/mime
npm http 200 http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/inherits
npm http 200 http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/media-typer
npm http 200 http://192.168.1.100:4873/media-typer
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/fs-extra
npm http 304 http://192.168.1.100:4873/bluebird
npm http 200 http://192.168.1.100:4873/fs-extra
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/jsonfile
npm http request GET http://192.168.1.100:4873/rimraf
npm http 304 http://192.168.1.100:4873/rimraf
npm http 200 http://192.168.1.100:4873/jsonfile
npm http 200 http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/fs.realpath
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/inflight
npm http 200 http://192.168.1.100:4873/fs.realpath
npm http 200 http://192.168.1.100:4873/once
npm http 200 http://192.168.1.100:4873/minimatch
npm http 200 http://192.168.1.100:4873/path-is-absolute
npm http request GET http://192.168.1.100:4873/wrappy
npm http 200 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 200 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/concat-map
npm http 200 http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/immediate
npm http 200 http://192.168.1.100:4873/inline-process-browser
npm http 200 http://192.168.1.100:4873/immediate
npm http 200 http://192.168.1.100:4873/es3ify
npm http 200 http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/through
npm http 304 http://192.168.1.100:4873/esprima
npm http 200 http://192.168.1.100:4873/through
npm http 200 http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/source-map
npm http 200 http://192.168.1.100:4873/base62
npm http 304 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/esprima-fb
npm http 200 http://192.168.1.100:4873/source-map
npm http 200 http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/recast
npm http request GET http://192.168.1.100:4873/q
npm http 304 http://192.168.1.100:4873/mkdirp
npm http 304 http://192.168.1.100:4873/detective
npm http 200 http://192.168.1.100:4873/private
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 200 http://192.168.1.100:4873/commander
npm http 304 http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http 200 http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/defined
npm http request GET http://192.168.1.100:4873/acorn
npm http 200 http://192.168.1.100:4873/defined
npm http 200 http://192.168.1.100:4873/acorn
npm http request GET http://192.168.1.100:4873/minimist
npm http 200 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/ast-types
npm http 200 http://192.168.1.100:4873/ast-types
npm http request GET http://192.168.1.100:4873/amdefine
npm http 304 http://192.168.1.100:4873/amdefine
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/falafel
npm http 200 http://192.168.1.100:4873/falafel
npm http 200 http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/xtend
npm http 200 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/string_decoder
npm http request GET http://192.168.1.100:4873/core-util-is
npm http 200 http://192.168.1.100:4873/core-util-is
npm http 304 http://192.168.1.100:4873/string_decoder
npm http request GET http://192.168.1.100:4873/esmangle-evaluator
npm http 200 http://192.168.1.100:4873/esmangle-evaluator
npm http request GET http://192.168.1.100:4873/has-binary-data
npm http request GET http://192.168.1.100:4873/socket.io-adapter
npm http request GET http://192.168.1.100:4873/socket.io-parser
npm http request GET http://192.168.1.100:4873/engine.io
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http 304 http://192.168.1.100:4873/socket.io-adapter
npm http 304 http://192.168.1.100:4873/socket.io-parser
npm http 200 http://192.168.1.100:4873/has-binary-data
npm http 200 http://192.168.1.100:4873/socket.io-client
npm http 200 http://192.168.1.100:4873/engine.io
npm http request GET http://192.168.1.100:4873/base64id
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/ws
npm http 304 http://192.168.1.100:4873/base64id
npm http 304 http://192.168.1.100:4873/engine.io-parser
npm http 200 http://192.168.1.100:4873/ws
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/has-binary
npm http request GET http://192.168.1.100:4873/utf8
npm http 200 http://192.168.1.100:4873/arraybuffer.slice
npm http 200 http://192.168.1.100:4873/has-binary
npm http 200 http://192.168.1.100:4873/blob
npm http 200 http://192.168.1.100:4873/after
npm http 200 http://192.168.1.100:4873/utf8
npm http 200 http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/ultron
npm http request GET http://192.168.1.100:4873/options
npm http request GET http://192.168.1.100:4873/bufferutil
npm http request GET http://192.168.1.100:4873/utf-8-validate
npm http 304 http://192.168.1.100:4873/ultron
npm http 200 http://192.168.1.100:4873/utf-8-validate
npm http 200 http://192.168.1.100:4873/options
npm http 200 http://192.168.1.100:4873/bufferutil
npm http request GET http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/nan
npm http 200 http://192.168.1.100:4873/nan
npm http 200 http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/component-emitter
npm http request GET http://192.168.1.100:4873/json3
npm http request GET http://192.168.1.100:4873/benchmark
npm http 304 http://192.168.1.100:4873/benchmark
npm http 200 http://192.168.1.100:4873/component-emitter
npm http 200 http://192.168.1.100:4873/json3
npm http request GET http://192.168.1.100:4873/component-bind
npm http request GET http://192.168.1.100:4873/backo2
npm http request GET http://192.168.1.100:4873/to-array
npm http request GET http://192.168.1.100:4873/parseuri
npm http request GET http://192.168.1.100:4873/object-component
npm http request GET http://192.168.1.100:4873/indexof
npm http request GET http://192.168.1.100:4873/engine.io-client
npm http 304 http://192.168.1.100:4873/component-bind
npm http 200 http://192.168.1.100:4873/to-array
npm http 200 http://192.168.1.100:4873/backo2
npm http 304 http://192.168.1.100:4873/parseuri
npm http 304 http://192.168.1.100:4873/object-component
npm http 200 http://192.168.1.100:4873/engine.io-client
npm http 200 http://192.168.1.100:4873/indexof
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/parseqs
npm http fetch GET https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http 304 http://192.168.1.100:4873/has-cors
npm http 200 http://192.168.1.100:4873/parseqs
npm http 304 http://192.168.1.100:4873/component-inherit
npm http 200 http://192.168.1.100:4873/parsejson
npm http fetch 200 https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http fetch GET https://github.com/component/global/archive/v2.0.1.tar.gz
npm http fetch 200 https://github.com/component/global/archive/v2.0.1.tar.gz
npm http request GET http://192.168.1.100:4873/better-assert
npm http 200 http://192.168.1.100:4873/better-assert
npm http request GET http://192.168.1.100:4873/callsite
npm http 200 http://192.168.1.100:4873/callsite
npm http request GET http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/stack-trace
npm http request GET http://192.168.1.100:4873/pkginfo
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/cycle
npm http request GET http://192.168.1.100:4873/colors
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/pkginfo
npm http 200 http://192.168.1.100:4873/cycle
npm http 200 http://192.168.1.100:4873/stack-trace
npm http 200 http://192.168.1.100:4873/eyes
npm http 200 http://192.168.1.100:4873/colors
npm http 200 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/tape
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 200 http://192.168.1.100:4873/tape
npm http request GET http://192.168.1.100:4873/jsonify
npm http request GET http://192.168.1.100:4873/deep-equal
npm http 200 http://192.168.1.100:4873/jsonify
npm http 304 http://192.168.1.100:4873/deep-equal
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
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/forever-agent
npm http request GET http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/javascript-state-machine
npm http request GET http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/salti
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/lie
npm http 200 http://192.168.1.100:4873/forever-agent
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/winston
npm http 304 http://192.168.1.100:4873/body-parser
npm http 200 http://192.168.1.100:4873/ip
npm http 200 http://192.168.1.100:4873/long
npm http 200 http://192.168.1.100:4873/javascript-state-machine
npm http 200 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/multiplex
npm http 200 http://192.168.1.100:4873/salti
npm http 304 http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/type-is
npm http 200 http://192.168.1.100:4873/bytes
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
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/send
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/utils-merge
npm http 304 http://192.168.1.100:4873/serve-static
npm http 304 http://192.168.1.100:4873/vary
npm http request GET http://192.168.1.100:4873/negotiator
npm http 304 http://192.168.1.100:4873/negotiator
npm http request GET http://192.168.1.100:4873/ipaddr.js
npm http request GET http://192.168.1.100:4873/forwarded
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
npm http 304 http://192.168.1.100:4873/es3ify
npm http 304 http://192.168.1.100:4873/inline-process-browser
npm http 304 http://192.168.1.100:4873/immediate
npm http 304 http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/through
npm http 304 http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/esprima
npm http 304 http://192.168.1.100:4873/through
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/commoner
npm http 304 http://192.168.1.100:4873/base62
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/commander
npm http 304 http://192.168.1.100:4873/detective
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http 304 http://192.168.1.100:4873/mkdirp
npm http 304 http://192.168.1.100:4873/q
npm http 304 http://192.168.1.100:4873/private
npm http 304 http://192.168.1.100:4873/recast
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http 304 http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/acorn
npm http request GET http://192.168.1.100:4873/defined
npm http 304 http://192.168.1.100:4873/acorn
npm http 304 http://192.168.1.100:4873/defined
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/inflight
npm http 304 http://192.168.1.100:4873/minimatch
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
npm http 304 http://192.168.1.100:4873/ast-types
npm http request GET http://192.168.1.100:4873/amdefine
npm http 304 http://192.168.1.100:4873/amdefine
npm http request GET http://192.168.1.100:4873/falafel
npm http request GET http://192.168.1.100:4873/through2
npm http 304 http://192.168.1.100:4873/through2
npm http 200 http://192.168.1.100:4873/falafel
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
npm http 304 http://192.168.1.100:4873/esmangle-evaluator
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/varint
npm http 304 http://192.168.1.100:4873/duplexify
npm http 304 http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/stream-shift
npm http 304 http://192.168.1.100:4873/stream-shift
npm http 200 http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http 304 http://192.168.1.100:4873/buffer-shims
npm http 200 http://192.168.1.100:4873/process-nextick-args
npm http 200 http://192.168.1.100:4873/util-deprecate
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 200 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/bl
npm http 200 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/stringstream
npm http 200 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/har-validator
npm http 200 http://192.168.1.100:4873/combined-stream
npm http 200 http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/chalk
npm http 304 http://192.168.1.100:4873/chalk
npm http 304 http://192.168.1.100:4873/is-my-json-valid
npm http 304 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 200 http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/ansi-styles
npm http 200 http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 200 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 200 http://192.168.1.100:4873/generate-object-property
npm http 200 http://192.168.1.100:4873/generate-function
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http request GET http://192.168.1.100:4873/is-property
npm http 200 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/boom
npm http 304 http://192.168.1.100:4873/cryptiles
npm http 200 http://192.168.1.100:4873/sntp
npm http 200 http://192.168.1.100:4873/boom
npm http 200 http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 304 http://192.168.1.100:4873/asn1
npm http 200 http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/colors
npm http request GET http://192.168.1.100:4873/cycle
npm http request GET http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/pkginfo
npm http request GET http://192.168.1.100:4873/stack-trace
npm http 304 http://192.168.1.100:4873/stack-trace
npm http 304 http://192.168.1.100:4873/colors
npm http 304 http://192.168.1.100:4873/eyes
npm http 304 http://192.168.1.100:4873/pkginfo
npm http 304 http://192.168.1.100:4873/cycle
npm http request GET http://192.168.1.100:4873/jsdoc
npm http 200 http://192.168.1.100:4873/jsdoc
npm http request GET http://192.168.1.100:4873/catharsis
npm http request GET http://192.168.1.100:4873/js2xmlparser
npm http request GET http://192.168.1.100:4873/marked
npm http request GET http://192.168.1.100:4873/requizzle
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/underscore
npm http request GET http://192.168.1.100:4873/wrench
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 200 http://192.168.1.100:4873/js2xmlparser
npm http 304 http://192.168.1.100:4873/strip-json-comments
npm http 200 http://192.168.1.100:4873/catharsis
npm http 200 http://192.168.1.100:4873/requizzle
npm http 200 http://192.168.1.100:4873/marked
npm http 200 http://192.168.1.100:4873/underscore
npm http 200 http://192.168.1.100:4873/wrench
npm WARN deprecated wrench@1.5.9: wrench.js is deprecated! You should check out fs-extra (https://github.com/jprichardson/node-fs-extra) for any operations you were using wrench for. Thanks for all the usage over the years.
npm http fetch 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http request GET http://192.168.1.100:4873/underscore-contrib
npm http 304 http://192.168.1.100:4873/underscore-contrib
npm WARN prefer global marked@0.3.6 should be installed with -g
npm http request GET http://192.168.1.100:4873/fs-extra-promise
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/jxc
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/unzip
npm http 304 http://192.168.1.100:4873/fs-extra-promise
npm http 304 http://192.168.1.100:4873/lie
npm http 304 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/unzip
npm http 304 http://192.168.1.100:4873/jxc
npm http request GET http://192.168.1.100:4873/fs-extra
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/fs-extra
npm http 304 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/jsonfile
npm http request GET http://192.168.1.100:4873/rimraf
npm http 304 http://192.168.1.100:4873/jsonfile
npm http 304 http://192.168.1.100:4873/rimraf
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/fs.realpath
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/inflight
npm http 304 http://192.168.1.100:4873/fs.realpath
npm http 304 http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/minimatch
npm http 304 http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/wrappy
npm http 304 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 304 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/adm-zip
npm http request GET http://192.168.1.100:4873/progress
npm http 200 http://192.168.1.100:4873/progress
npm http 200 http://192.168.1.100:4873/adm-zip
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
npm http 304 http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/through
npm http 200 http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/commoner
npm http 304 http://192.168.1.100:4873/base62
npm http 304 http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/detective
npm http 304 http://192.168.1.100:4873/commander
npm http 304 http://192.168.1.100:4873/private
npm http 304 http://192.168.1.100:4873/mkdirp
npm http 304 http://192.168.1.100:4873/iconv-lite
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
npm http 304 http://192.168.1.100:4873/falafel
npm http 200 http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/core-util-is
npm http request GET http://192.168.1.100:4873/string_decoder
npm http 304 http://192.168.1.100:4873/core-util-is
npm http 304 http://192.168.1.100:4873/string_decoder
npm http request GET http://192.168.1.100:4873/esmangle-evaluator
npm http 200 http://192.168.1.100:4873/esmangle-evaluator
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/forever-agent
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/mime-types
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/forever-agent
npm http 304 http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 200 http://192.168.1.100:4873/isstream
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
npm http 304 http://192.168.1.100:4873/ansi-styles
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/supports-color
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
npm http 304 http://192.168.1.100:4873/hoek
npm http 304 http://192.168.1.100:4873/cryptiles
npm http 304 http://192.168.1.100:4873/boom
npm http 304 http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 304 http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/fstream
npm http request GET http://192.168.1.100:4873/pullstream
npm http request GET http://192.168.1.100:4873/binary
npm http request GET http://192.168.1.100:4873/setimmediate
npm http request GET http://192.168.1.100:4873/match-stream
npm http 304 http://192.168.1.100:4873/binary
npm http 304 http://192.168.1.100:4873/setimmediate
npm http 200 http://192.168.1.100:4873/match-stream
npm http 200 http://192.168.1.100:4873/pullstream
npm http 200 http://192.168.1.100:4873/fstream
npm http request GET http://192.168.1.100:4873/chainsaw
npm http request GET http://192.168.1.100:4873/buffers
npm http 200 http://192.168.1.100:4873/chainsaw
npm http 200 http://192.168.1.100:4873/buffers
npm http request GET http://192.168.1.100:4873/traverse
npm http 200 http://192.168.1.100:4873/traverse
npm WARN deprecated graceful-fs@3.0.8: graceful-fs v3.0.0 and before will fail on node releases >= v7.0. Please update to graceful-fs@^4.0.0 as soon as possible. Use 'npm ls graceful-fs' to find it in the tree.
npm http request GET http://192.168.1.100:4873/over
npm http request GET http://192.168.1.100:4873/slice-stream
npm http 200 http://192.168.1.100:4873/over
npm http 200 http://192.168.1.100:4873/slice-stream
npm WARN EPACKAGEJSON install@0.0.1 No repository field.
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/forever-agent
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/express-pouchdb
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/bn.js
npm http request GET http://192.168.1.100:4873/leveldown-mobile
npm http request GET http://192.168.1.100:4873/proxyquire
npm http request GET http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/tape
npm http request GET http://192.168.1.100:4873/nock
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/pouchdb-node
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/request-promise
npm http request GET http://192.168.1.100:4873/sinon
npm http request GET http://192.168.1.100:4873/supertest
npm http request GET http://192.168.1.100:4873/supertest-as-promised
npm http request GET http://192.168.1.100:4873/tape-catch
npm http request GET http://192.168.1.100:4873/tmp
npm http request GET http://192.168.1.100:4873/uuid
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/forever-agent
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/express-pouchdb
npm http 200 http://192.168.1.100:4873/bn.js
npm http 200 http://192.168.1.100:4873/socket.io-client
npm http 304 http://192.168.1.100:4873/multiplex
npm http 200 http://192.168.1.100:4873/proxyquire
npm http 200 http://192.168.1.100:4873/randomstring
npm http 304 http://192.168.1.100:4873/tape
npm http 304 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/nock
npm http 304 http://192.168.1.100:4873/pouchdb-node
npm http 304 http://192.168.1.100:4873/leveldown-mobile
npm http 304 http://192.168.1.100:4873/js-extend
npm http 200 http://192.168.1.100:4873/request-promise
npm http 200 http://192.168.1.100:4873/supertest
npm http 200 http://192.168.1.100:4873/sinon
npm http 304 http://192.168.1.100:4873/uuid
npm http 304 http://192.168.1.100:4873/tmp
npm http 200 http://192.168.1.100:4873/supertest-as-promised
npm http 304 http://192.168.1.100:4873/tape-catch
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/raw-body
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/bytes
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/type-is
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/ms
npm http 200 http://192.168.1.100:4873/ms
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
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/etag
npm http 200 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/methods
npm http 200 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/send
npm http 304 http://192.168.1.100:4873/path-to-regexp
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
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/cookie-parser
npm http request GET http://192.168.1.100:4873/header-case-normalizer
npm http request GET http://192.168.1.100:4873/multiparty
npm http request GET http://192.168.1.100:4873/pouchdb-all-dbs
npm http request GET http://192.168.1.100:4873/pouchdb-auth
npm http request GET http://192.168.1.100:4873/pouchdb-find
npm http request GET http://192.168.1.100:4873/pouchdb-list
npm http request GET http://192.168.1.100:4873/pouchdb-replicator
npm http request GET http://192.168.1.100:4873/pouchdb-rewrite
npm http request GET http://192.168.1.100:4873/compression
npm http request GET http://192.168.1.100:4873/basic-auth
npm http request GET http://192.168.1.100:4873/pouchdb-show
npm http request GET http://192.168.1.100:4873/pouchdb-security
npm http request GET http://192.168.1.100:4873/pouchdb-size
npm http request GET http://192.168.1.100:4873/pouchdb-validation
npm http request GET http://192.168.1.100:4873/pouchdb-update
npm http request GET http://192.168.1.100:4873/pouchdb-vhost
npm http request GET http://192.168.1.100:4873/pouchdb-wrappers
npm http 304 http://192.168.1.100:4873/cookie-parser
npm http 304 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/multiparty
npm http 304 http://192.168.1.100:4873/pouchdb-auth
npm http 304 http://192.168.1.100:4873/pouchdb-list
npm http 304 http://192.168.1.100:4873/pouchdb-find
npm http 304 http://192.168.1.100:4873/header-case-normalizer
npm http 304 http://192.168.1.100:4873/pouchdb-all-dbs
npm http 304 http://192.168.1.100:4873/compression
npm http 304 http://192.168.1.100:4873/pouchdb-rewrite
npm http 304 http://192.168.1.100:4873/basic-auth
npm http 304 http://192.168.1.100:4873/pouchdb-show
npm http 304 http://192.168.1.100:4873/pouchdb-validation
npm http 304 http://192.168.1.100:4873/pouchdb-replicator
npm http 304 http://192.168.1.100:4873/pouchdb-security
npm http 304 http://192.168.1.100:4873/pouchdb-update
npm http 304 http://192.168.1.100:4873/pouchdb-vhost
npm http 304 http://192.168.1.100:4873/pouchdb-wrappers
npm http 304 http://192.168.1.100:4873/pouchdb-size
npm http request GET http://192.168.1.100:4873/setprototypeof
npm http 200 http://192.168.1.100:4873/setprototypeof
npm http request GET http://192.168.1.100:4873/on-headers
npm http request GET http://192.168.1.100:4873/compressible
npm http 304 http://192.168.1.100:4873/compressible
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
npm http 304 http://192.168.1.100:4873/tiny-queue
npm http 200 http://192.168.1.100:4873/argsarray
npm http 200 http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/base62
npm http 304 http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/base64url
npm http request GET http://192.168.1.100:4873/crypto-lite
npm http request GET http://192.168.1.100:4873/couchdb-calculate-session-id
npm http request GET http://192.168.1.100:4873/pouchdb-req-http-query
npm http request GET http://192.168.1.100:4873/pouchdb-plugin-error
npm http request GET http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http request GET http://192.168.1.100:4873/pouchdb
npm http request GET http://192.168.1.100:4873/pouchdb-system-db
npm http request GET http://192.168.1.100:4873/promise-nodify
npm http request GET http://192.168.1.100:4873/secure-random
npm http 200 http://192.168.1.100:4873/base64url
npm http 304 http://192.168.1.100:4873/crypto-lite
npm http 200 http://192.168.1.100:4873/pouchdb-plugin-error
npm http 304 http://192.168.1.100:4873/couchdb-calculate-session-id
npm http 304 http://192.168.1.100:4873/pouchdb-req-http-query
npm http 304 http://192.168.1.100:4873/promise-nodify
npm http 304 http://192.168.1.100:4873/secure-random
npm http 200 http://192.168.1.100:4873/pouchdb-system-db
npm http 304 http://192.168.1.100:4873/pouchdb
npm http 304 http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http request GET http://192.168.1.100:4873/meow
npm http request GET http://192.168.1.100:4873/concat-stream
npm http 200 http://192.168.1.100:4873/meow
npm http 304 http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/typedarray
npm http 200 http://192.168.1.100:4873/typedarray
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/camelcase-keys
npm http request GET http://192.168.1.100:4873/indent-string
npm http 304 http://192.168.1.100:4873/indent-string
npm http 304 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/camelcase-keys
npm http request GET http://192.168.1.100:4873/map-obj
npm http request GET http://192.168.1.100:4873/camelcase
npm http 304 http://192.168.1.100:4873/camelcase
npm http 200 http://192.168.1.100:4873/map-obj
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
npm http request GET http://192.168.1.100:4873/localstorage-down
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/memdown
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/pouchdb-collate
npm http request GET http://192.168.1.100:4873/scope-eval
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/vuvuzela
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http 200 http://192.168.1.100:4873/level-write-stream
npm http 200 http://192.168.1.100:4873/double-ended-queue
npm http 304 http://192.168.1.100:4873/through2
npm http 304 http://192.168.1.100:4873/localstorage-down
npm http 304 http://192.168.1.100:4873/es6-promise-pool
npm http 304 http://192.168.1.100:4873/fruitdown
npm http 304 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/memdown
npm http 200 http://192.168.1.100:4873/pouchdb-collections
npm http 200 http://192.168.1.100:4873/spark-md5
npm http 304 http://192.168.1.100:4873/scope-eval
npm http 200 http://192.168.1.100:4873/pouchdb-collate
npm http 304 http://192.168.1.100:4873/vuvuzela
npm http 200 http://192.168.1.100:4873/levelup
npm http 200 http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/d64
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http 200 http://192.168.1.100:4873/d64
npm http 200 http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/end-stream
npm http 304 http://192.168.1.100:4873/end-stream
npm http request GET http://192.168.1.100:4873/write-stream
npm http 200 http://192.168.1.100:4873/write-stream
npm http request GET http://192.168.1.100:4873/deferred-leveldown
npm http request GET http://192.168.1.100:4873/level-codec
npm http request GET http://192.168.1.100:4873/level-errors
npm http request GET http://192.168.1.100:4873/level-iterator-stream
npm http request GET http://192.168.1.100:4873/prr
npm http request GET http://192.168.1.100:4873/semver
npm http 200 http://192.168.1.100:4873/prr
npm http 200 http://192.168.1.100:4873/semver
npm http 200 http://192.168.1.100:4873/level-errors
npm http 200 http://192.168.1.100:4873/level-codec
npm http 200 http://192.168.1.100:4873/deferred-leveldown
npm http 200 http://192.168.1.100:4873/level-iterator-stream
npm http request GET http://192.168.1.100:4873/errno
npm http 200 http://192.168.1.100:4873/errno
npm http request GET http://192.168.1.100:4873/humble-localstorage
npm http 200 http://192.168.1.100:4873/humble-localstorage
npm http request GET http://192.168.1.100:4873/has-localstorage
npm http request GET http://192.168.1.100:4873/localstorage-memory
npm http 304 http://192.168.1.100:4873/has-localstorage
npm http 304 http://192.168.1.100:4873/localstorage-memory
npm http request GET http://192.168.1.100:4873/ltgt
npm http request GET http://192.168.1.100:4873/functional-red-black-tree
npm http 200 http://192.168.1.100:4873/ltgt
npm http 200 http://192.168.1.100:4873/functional-red-black-tree
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
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/is-typedarray
npm http request GET http://192.168.1.100:4873/aws4
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/tough-cookie
npm WARN deprecated tough-cookie@2.2.2: ReDoS vulnerability parsing Set-Cookie https://nodesecurity.io/advisories/130
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/aws4
npm http 200 http://192.168.1.100:4873/is-typedarray
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
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http 304 http://192.168.1.100:4873/supports-color
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-function
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/pinkie
npm http 200 http://192.168.1.100:4873/pinkie
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/hoek
npm http 304 http://192.168.1.100:4873/boom
npm http 304 http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/jsprim
npm http request GET http://192.168.1.100:4873/sshpk
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 200 http://192.168.1.100:4873/jsprim
npm http 200 http://192.168.1.100:4873/sshpk
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
npm http 200 http://192.168.1.100:4873/getpass
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
npm http 304 http://192.168.1.100:4873/random-uuid-v4
npm http 304 http://192.168.1.100:4873/couchdb-objects
npm http 304 http://192.168.1.100:4873/couchdb-eval
npm http request GET http://192.168.1.100:4873/is-empty
npm http 200 http://192.168.1.100:4873/is-empty
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/is-array
npm http request GET http://192.168.1.100:4873/pouchdb-upsert
npm http request GET http://192.168.1.100:4873/pouchdb-extend
npm http 304 http://192.168.1.100:4873/spark-md5
npm http 200 http://192.168.1.100:4873/is-array
npm http 304 http://192.168.1.100:4873/pouchdb-extend
npm http 304 http://192.168.1.100:4873/pouchdb-upsert
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 304 http://192.168.1.100:4873/unreachable-branch-transform
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
npm http 304 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/fast-future
npm http 304 http://192.168.1.100:4873/bindings
npm http 304 http://192.168.1.100:4873/abstract-leveldown
npm http 200 http://192.168.1.100:4873/fast-future
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
npm http request GET http://192.168.1.100:4873/propagate
npm http request GET http://192.168.1.100:4873/chai
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/deep-equal
npm http 304 http://192.168.1.100:4873/propagate
npm http 304 http://192.168.1.100:4873/lodash
npm WARN deprecated lodash@2.4.1: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
npm http 200 http://192.168.1.100:4873/chai
npm http request GET http://192.168.1.100:4873/assertion-error
npm http request GET http://192.168.1.100:4873/deep-eql
npm http request GET http://192.168.1.100:4873/type-detect
npm http 200 http://192.168.1.100:4873/deep-eql
npm http 304 http://192.168.1.100:4873/type-detect
npm http 304 http://192.168.1.100:4873/assertion-error
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/ip
npm http 304 http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-http
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-leveldb
npm http request GET http://192.168.1.100:4873/pouchdb-core
npm http request GET http://192.168.1.100:4873/pouchdb-mapreduce
npm http request GET http://192.168.1.100:4873/pouchdb-replication
npm http 304 http://192.168.1.100:4873/pouchdb-core
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-http
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-leveldb
npm http 304 http://192.168.1.100:4873/pouchdb-replication
npm http 304 http://192.168.1.100:4873/pouchdb-mapreduce
npm http request GET http://192.168.1.100:4873/pouchdb-ajax
npm http request GET http://192.168.1.100:4873/pouchdb-errors
npm http request GET http://192.168.1.100:4873/pouchdb-binary-utils
npm http request GET http://192.168.1.100:4873/pouchdb-md5
npm http request GET http://192.168.1.100:4873/pouchdb-utils
npm http 304 http://192.168.1.100:4873/pouchdb-errors
npm http 304 http://192.168.1.100:4873/pouchdb-ajax
npm http 304 http://192.168.1.100:4873/pouchdb-md5
npm http 304 http://192.168.1.100:4873/pouchdb-binary-utils
npm http 200 http://192.168.1.100:4873/pouchdb-utils
npm http request GET http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http 304 http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/leveldown
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-leveldb-core
npm http 200 http://192.168.1.100:4873/leveldown
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-leveldb-core
npm http request GET http://192.168.1.100:4873/nan
npm http request GET http://192.168.1.100:4873/prebuild
npm http 304 http://192.168.1.100:4873/nan
npm http 200 http://192.168.1.100:4873/prebuild
npm http request GET http://192.168.1.100:4873/expand-template
npm http request GET http://192.168.1.100:4873/ghreleases
npm http request GET http://192.168.1.100:4873/github-from-package
npm http request GET http://192.168.1.100:4873/noop-logger
npm http request GET http://192.168.1.100:4873/node-ninja
npm http request GET http://192.168.1.100:4873/npmlog
npm http request GET http://192.168.1.100:4873/os-homedir
npm http request GET http://192.168.1.100:4873/node-gyp
npm http request GET http://192.168.1.100:4873/pump
npm http request GET http://192.168.1.100:4873/rc
npm http request GET http://192.168.1.100:4873/simple-get
npm http request GET http://192.168.1.100:4873/tar-fs
npm http request GET http://192.168.1.100:4873/tar-stream
npm http 200 http://192.168.1.100:4873/expand-template
npm http 200 http://192.168.1.100:4873/github-from-package
npm http 200 http://192.168.1.100:4873/noop-logger
npm http 200 http://192.168.1.100:4873/node-ninja
npm http 200 http://192.168.1.100:4873/ghreleases
npm http 200 http://192.168.1.100:4873/npmlog
npm http 200 http://192.168.1.100:4873/os-homedir
npm http 200 http://192.168.1.100:4873/node-gyp
npm http 200 http://192.168.1.100:4873/pump
npm http 200 http://192.168.1.100:4873/rc
npm http 200 http://192.168.1.100:4873/simple-get
npm http 200 http://192.168.1.100:4873/tar-fs
npm http 200 http://192.168.1.100:4873/tar-stream
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/ghrepos
npm http request GET http://192.168.1.100:4873/ghutils
npm http request GET http://192.168.1.100:4873/simple-mime
npm http request GET http://192.168.1.100:4873/url-template
npm http 200 http://192.168.1.100:4873/ghrepos
npm http 304 http://192.168.1.100:4873/after
npm http 200 http://192.168.1.100:4873/ghutils
npm http 200 http://192.168.1.100:4873/url-template
npm http 200 http://192.168.1.100:4873/simple-mime
npm http request GET http://192.168.1.100:4873/jsonist
npm http 200 http://192.168.1.100:4873/jsonist
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/hyperquest
npm http 304 http://192.168.1.100:4873/bl
npm http 200 http://192.168.1.100:4873/hyperquest
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/duplexer2
npm http 200 http://192.168.1.100:4873/duplexer2
npm http request GET http://192.168.1.100:4873/fstream
npm http request GET http://192.168.1.100:4873/nopt
npm http request GET http://192.168.1.100:4873/osenv
npm http request GET http://192.168.1.100:4873/path-array
npm http request GET http://192.168.1.100:4873/tar
npm http request GET http://192.168.1.100:4873/which
npm http 304 http://192.168.1.100:4873/fstream
npm http 200 http://192.168.1.100:4873/path-array
npm http 200 http://192.168.1.100:4873/which
npm http 200 http://192.168.1.100:4873/osenv
npm http 200 http://192.168.1.100:4873/tar
npm http 200 http://192.168.1.100:4873/nopt
npm http request GET http://192.168.1.100:4873/abbrev
npm http 304 http://192.168.1.100:4873/abbrev
npm http request GET http://192.168.1.100:4873/are-we-there-yet
npm http request GET http://192.168.1.100:4873/ansi
npm http request GET http://192.168.1.100:4873/gauge
npm http 200 http://192.168.1.100:4873/are-we-there-yet
npm http 200 http://192.168.1.100:4873/ansi
npm http 200 http://192.168.1.100:4873/gauge
npm http request GET http://192.168.1.100:4873/delegates
npm http 200 http://192.168.1.100:4873/delegates
npm http request GET http://192.168.1.100:4873/has-unicode
npm http request GET http://192.168.1.100:4873/lodash.pad
npm http request GET http://192.168.1.100:4873/lodash.padend
npm http request GET http://192.168.1.100:4873/lodash.padstart
npm http 200 http://192.168.1.100:4873/has-unicode
npm http 200 http://192.168.1.100:4873/lodash.pad
npm http 200 http://192.168.1.100:4873/lodash.padend
npm http 200 http://192.168.1.100:4873/lodash.padstart
npm http request GET http://192.168.1.100:4873/os-tmpdir
npm http 304 http://192.168.1.100:4873/os-tmpdir
npm http request GET http://192.168.1.100:4873/array-index
npm http 200 http://192.168.1.100:4873/array-index
npm http request GET http://192.168.1.100:4873/es6-symbol
npm http 200 http://192.168.1.100:4873/es6-symbol
npm http request GET http://192.168.1.100:4873/d
npm http request GET http://192.168.1.100:4873/es5-ext
npm http 200 http://192.168.1.100:4873/d
npm http 200 http://192.168.1.100:4873/es5-ext
npm http request GET http://192.168.1.100:4873/es6-iterator
npm http 200 http://192.168.1.100:4873/es6-iterator
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 304 http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/block-stream
npm http 200 http://192.168.1.100:4873/block-stream
npm http request GET http://192.168.1.100:4873/isexe
npm http 200 http://192.168.1.100:4873/isexe
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http 304 http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/ini
npm http request GET http://192.168.1.100:4873/deep-extend
npm http 304 http://192.168.1.100:4873/strip-json-comments
npm http 200 http://192.168.1.100:4873/deep-extend
npm http 200 http://192.168.1.100:4873/ini
npm WARN engine deep-extend@0.4.1: wanted: {"node":">=0.12.0","iojs":">=1.0.0"} (current: {"node":"0.10.40","npm":"3.3.12"})
npm http request GET http://192.168.1.100:4873/unzip-response
npm http 200 http://192.168.1.100:4873/unzip-response
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/pouchdb-json
npm http request GET http://192.168.1.100:4873/pouchdb-merge
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-utils
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-utils
npm http 304 http://192.168.1.100:4873/sublevel-pouchdb
npm http 304 http://192.168.1.100:4873/pouchdb-json
npm http 304 http://192.168.1.100:4873/pouchdb-merge
npm http request GET http://192.168.1.100:4873/ltgt
npm http 304 http://192.168.1.100:4873/ltgt
npm http request GET http://192.168.1.100:4873/pouchdb-mapreduce-utils
npm http 304 http://192.168.1.100:4873/pouchdb-mapreduce-utils
npm http request GET http://192.168.1.100:4873/pouchdb-checkpointer
npm http request GET http://192.168.1.100:4873/pouchdb-generate-replication-id
npm http 304 http://192.168.1.100:4873/pouchdb-checkpointer
npm http 304 http://192.168.1.100:4873/pouchdb-generate-replication-id
npm http request GET http://192.168.1.100:4873/module-not-found-error
npm http request GET http://192.168.1.100:4873/fill-keys
npm http 200 http://192.168.1.100:4873/fill-keys
npm http 200 http://192.168.1.100:4873/module-not-found-error
npm http request GET http://192.168.1.100:4873/is-object
npm http 200 http://192.168.1.100:4873/is-object
npm http request GET http://192.168.1.100:4873/array-uniq
npm http 200 http://192.168.1.100:4873/array-uniq
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/samsam
npm http request GET http://192.168.1.100:4873/formatio
npm http request GET http://192.168.1.100:4873/util
npm http request GET http://192.168.1.100:4873/lolex
npm http 200 http://192.168.1.100:4873/lolex
npm http 200 http://192.168.1.100:4873/samsam
npm http 304 http://192.168.1.100:4873/util
npm http 200 http://192.168.1.100:4873/formatio
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
npm http request GET http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/component-bind
npm http 304 http://192.168.1.100:4873/socket.io-parser
npm http 304 http://192.168.1.100:4873/component-emitter
npm http 304 http://192.168.1.100:4873/engine.io-client
npm http 304 http://192.168.1.100:4873/object-component
npm http 304 http://192.168.1.100:4873/indexof
npm http 304 http://192.168.1.100:4873/parseuri
npm http 304 http://192.168.1.100:4873/has-binary
npm http 304 http://192.168.1.100:4873/to-array
npm http 304 http://192.168.1.100:4873/backo2
npm http 304 http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/parseqs
npm http request GET http://192.168.1.100:4873/ws
npm http fetch GET https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http 304 http://192.168.1.100:4873/parsejson
npm http 304 http://192.168.1.100:4873/component-inherit
npm http 304 http://192.168.1.100:4873/engine.io-parser
npm http 304 http://192.168.1.100:4873/parseqs
npm http 304 http://192.168.1.100:4873/has-cors
npm http 304 http://192.168.1.100:4873/ws
npm http fetch 200 https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/utf8
npm http 304 http://192.168.1.100:4873/blob
npm http 304 http://192.168.1.100:4873/arraybuffer.slice
npm http 304 http://192.168.1.100:4873/base64-arraybuffer
npm http 304 http://192.168.1.100:4873/utf8
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
npm http 200 http://192.168.1.100:4873/superagent
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/reduce-component
npm http request GET http://192.168.1.100:4873/formidable
npm http request GET http://192.168.1.100:4873/cookiejar
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/form-data
npm http 200 http://192.168.1.100:4873/reduce-component
npm http 304 http://192.168.1.100:4873/formidable
npm http 200 http://192.168.1.100:4873/cookiejar
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/combined-stream
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
npm http 304 http://192.168.1.100:4873/resumer
npm http 200 http://192.168.1.100:4873/object-inspect
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
npm ERR! Test failed.  See above for more details.
