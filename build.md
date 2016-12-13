#### Test (Fail) 92349294 Build Logs


```


```

```
Already up-to-date.

From https://github.com/thaliproject/Thali_CordovaPlugin
   a1d445d..0c52c37  iOS_swift3_migration -> origin/iOS_swift3_migration

```

```
Your branch is up-to-date with 'origin/master'.
Branch iOS set up to track remote branch iOS from origin.
Auto-merging lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift
Merge made by the 'recursive' strategy.
 build.sh                                                                | 2 +-
 .../ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift        | 2 +-
 thali/package.json                                                      | 2 +-
 3 files changed, 3 insertions(+), 3 deletions(-)

Already on 'master'
Switched to a new branch 'iOS'
Note: checking out '0c52c37'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at 0c52c37... update node-xcode to 0.9.0

```

```

start build.sh

-- Environment:
Cordova version: 6.4.0
Node version: v6.9.1
JXcore version: v0.3.1.7
JXcore engine: Google V8 v3.14.5.9
xcodebuild version: Xcode 7.3.1


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
│   ├── graceful-fs@4.1.11 
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
[33mPreparing NPM for JXcore (v0.3.1.7) for the first run[39m
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
│ │ └─┬ async@2.1.4 
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
│ │   ├─┬ dashdash@1.14.1 
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
└─┬ xcode@0.9.0 
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

Environment not valid: 
Object Name: xcode : Error: Command: xcodebuild -version failed
Object Name: carthage : Error: Command: carthage version failed
Object Name: swiftlint : Error: Command: swiftlint version failed

[0;31merror: command 'node validateBuildEnvironment.js' failed with code 1, file 'setUpDesktop.sh' on line 41[0m

[0;31merror: command 'thali/install/setUpDesktop.sh' failed with code 1, file 'build.sh' on line 48[0m
./build.sh CI FAILED - build.sh failure[0m

npm WARN thali-test-server@0.0.1 No repository field.
npm WARN thali-test-server@0.0.1 No license field.
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/javascript-state-machine
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/uuid
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/winston
npm http 304 http://192.168.1.100:4873/express
npm http 200 http://192.168.1.100:4873/ip
npm http 200 http://192.168.1.100:4873/js-extend
npm http 200 http://192.168.1.100:4873/body-parser
npm http 200 http://192.168.1.100:4873/javascript-state-machine
npm http 200 http://192.168.1.100:4873/long
npm http 200 http://192.168.1.100:4873/lie
npm http 200 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/uuid
npm http 200 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/bytes
npm http 304 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/type-is
npm http 200 http://192.168.1.100:4873/raw-body
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
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/array-flatten
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
npm http 304 http://192.168.1.100:4873/vary
npm http 304 http://192.168.1.100:4873/utils-merge
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
npm http 200 http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/duplexify
npm http 304 http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 200 http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/stream-shift
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http 304 http://192.168.1.100:4873/end-of-stream
npm http 304 http://192.168.1.100:4873/stream-shift
npm http request GET http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/wrappy
npm http 304 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/core-util-is
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/string_decoder
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/buffer-shims
npm http 304 http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/process-nextick-args
npm http 304 http://192.168.1.100:4873/string_decoder
npm http 304 http://192.168.1.100:4873/core-util-is
npm http 304 http://192.168.1.100:4873/util-deprecate
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 200 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/json-stringify-safe
npm http 200 http://192.168.1.100:4873/tunnel-agent
npm http 304 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 200 http://192.168.1.100:4873/form-data
npm http 200 http://192.168.1.100:4873/hawk
npm http 200 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http fetch GET http://192.168.1.100:4873/async/-/async-2.1.4.tgz
npm http fetch 200 http://192.168.1.100:4873/async/-/async-2.1.4.tgz
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
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http request GET http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http 304 http://192.168.1.100:4873/ansi-styles
npm http 304 http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http 304 http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http 304 http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/boom
npm http 200 http://192.168.1.100:4873/cryptiles
npm http 304 http://192.168.1.100:4873/hoek
npm http 200 http://192.168.1.100:4873/sntp
npm http 200 http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 304 http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/punycode
npm http 304 http://192.168.1.100:4873/punycode
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/jsonschema
npm http 200 http://192.168.1.100:4873/jsonschema
npm http 304 http://192.168.1.100:4873/object-assign
npm http fetch GET http://192.168.1.100:4873/jsonschema/-/jsonschema-1.1.1.tgz
npm http fetch 200 http://192.168.1.100:4873/jsonschema/-/jsonschema-1.1.1.tgz
npm http request GET http://192.168.1.100:4873/colors
npm http request GET http://192.168.1.100:4873/cycle
npm http request GET http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/pkginfo
npm http request GET http://192.168.1.100:4873/stack-trace
npm http 304 http://192.168.1.100:4873/colors
npm http 304 http://192.168.1.100:4873/eyes
npm http 304 http://192.168.1.100:4873/cycle
npm http 304 http://192.168.1.100:4873/stack-trace
npm http 304 http://192.168.1.100:4873/pkginfo
npm http request GET http://192.168.1.100:4873/eslint
npm http request GET http://192.168.1.100:4873/jsdoc
npm http 200 http://192.168.1.100:4873/jsdoc
npm http 200 http://192.168.1.100:4873/eslint
npm http fetch GET http://192.168.1.100:4873/eslint/-/eslint-3.11.1.tgz
npm http fetch 200 http://192.168.1.100:4873/eslint/-/eslint-3.11.1.tgz
npm http request GET http://192.168.1.100:4873/babel-code-frame
npm http request GET http://192.168.1.100:4873/doctrine
npm http request GET http://192.168.1.100:4873/escope
npm http request GET http://192.168.1.100:4873/estraverse
npm http request GET http://192.168.1.100:4873/esutils
npm http request GET http://192.168.1.100:4873/file-entry-cache
npm http request GET http://192.168.1.100:4873/globals
npm http request GET http://192.168.1.100:4873/ignore
npm http request GET http://192.168.1.100:4873/is-resolvable
npm http request GET http://192.168.1.100:4873/js-yaml
npm http request GET http://192.168.1.100:4873/levn
npm http request GET http://192.168.1.100:4873/natural-compare
npm http request GET http://192.168.1.100:4873/optionator
npm http request GET http://192.168.1.100:4873/path-is-inside
npm http request GET http://192.168.1.100:4873/pluralize
npm http request GET http://192.168.1.100:4873/require-uncached
npm http request GET http://192.168.1.100:4873/strip-bom
npm http request GET http://192.168.1.100:4873/table
npm http request GET http://192.168.1.100:4873/text-table
npm http request GET http://192.168.1.100:4873/user-home
npm http request GET http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/inquirer
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/espree
npm http request GET http://192.168.1.100:4873/imurmurhash
npm http request GET http://192.168.1.100:4873/json-stable-stringify
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/progress
npm http request GET http://192.168.1.100:4873/shelljs
npm http 200 http://192.168.1.100:4873/babel-code-frame
npm http 200 http://192.168.1.100:4873/esutils
npm http 200 http://192.168.1.100:4873/doctrine
npm http 200 http://192.168.1.100:4873/estraverse
npm http 200 http://192.168.1.100:4873/escope
npm http fetch GET http://192.168.1.100:4873/esutils/-/esutils-2.0.2.tgz
npm http fetch GET http://192.168.1.100:4873/babel-code-frame/-/babel-code-frame-6.20.0.tgz
npm http fetch GET http://192.168.1.100:4873/doctrine/-/doctrine-1.5.0.tgz
npm http fetch GET http://192.168.1.100:4873/estraverse/-/estraverse-4.2.0.tgz
npm http fetch GET http://192.168.1.100:4873/escope/-/escope-3.6.0.tgz
npm http 200 http://192.168.1.100:4873/file-entry-cache
npm http 200 http://192.168.1.100:4873/globals
npm http 200 http://192.168.1.100:4873/ignore
npm http 200 http://192.168.1.100:4873/is-resolvable
npm http fetch GET http://192.168.1.100:4873/file-entry-cache/-/file-entry-cache-2.0.0.tgz
npm http fetch GET http://192.168.1.100:4873/globals/-/globals-9.14.0.tgz
npm http 200 http://192.168.1.100:4873/js-yaml
npm http fetch GET http://192.168.1.100:4873/ignore/-/ignore-3.2.0.tgz
npm http fetch GET http://192.168.1.100:4873/is-resolvable/-/is-resolvable-1.0.0.tgz
npm http fetch GET http://192.168.1.100:4873/js-yaml/-/js-yaml-3.7.0.tgz
npm http 200 http://192.168.1.100:4873/levn
npm http 200 http://192.168.1.100:4873/natural-compare
npm http 200 http://192.168.1.100:4873/optionator
npm http 200 http://192.168.1.100:4873/path-is-inside
npm http fetch GET http://192.168.1.100:4873/levn/-/levn-0.3.0.tgz
npm http 200 http://192.168.1.100:4873/pluralize
npm http fetch GET http://192.168.1.100:4873/natural-compare/-/natural-compare-1.4.0.tgz
npm http fetch GET http://192.168.1.100:4873/optionator/-/optionator-0.8.2.tgz
npm http fetch GET http://192.168.1.100:4873/path-is-inside/-/path-is-inside-1.0.2.tgz
npm http 200 http://192.168.1.100:4873/require-uncached
npm http 200 http://192.168.1.100:4873/strip-bom
npm http 200 http://192.168.1.100:4873/user-home
npm http 200 http://192.168.1.100:4873/table
npm http 200 http://192.168.1.100:4873/text-table
npm http fetch GET http://192.168.1.100:4873/require-uncached/-/require-uncached-1.0.3.tgz
npm http fetch GET http://192.168.1.100:4873/pluralize/-/pluralize-1.2.1.tgz
npm http fetch GET http://192.168.1.100:4873/user-home/-/user-home-2.0.0.tgz
npm http fetch GET http://192.168.1.100:4873/strip-bom/-/strip-bom-3.0.0.tgz
npm http fetch GET http://192.168.1.100:4873/table/-/table-3.8.3.tgz
npm http fetch GET http://192.168.1.100:4873/text-table/-/text-table-0.2.0.tgz
npm http 200 http://192.168.1.100:4873/inquirer
npm http fetch GET http://192.168.1.100:4873/inquirer/-/inquirer-0.12.0.tgz
npm http 304 http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/mkdirp
npm http 200 http://192.168.1.100:4873/concat-stream
npm http 200 http://192.168.1.100:4873/espree
npm http fetch GET http://192.168.1.100:4873/espree/-/espree-3.3.2.tgz
npm http 304 http://192.168.1.100:4873/json-stable-stringify
npm http 304 http://192.168.1.100:4873/imurmurhash
npm http fetch GET http://192.168.1.100:4873/json-stable-stringify/-/json-stable-stringify-1.0.1.tgz
npm http 200 http://192.168.1.100:4873/progress
npm http 200 http://192.168.1.100:4873/strip-json-comments
npm http fetch 200 http://192.168.1.100:4873/esutils/-/esutils-2.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/babel-code-frame/-/babel-code-frame-6.20.0.tgz
npm http fetch 200 http://192.168.1.100:4873/estraverse/-/estraverse-4.2.0.tgz
npm http fetch 200 http://192.168.1.100:4873/doctrine/-/doctrine-1.5.0.tgz
npm http fetch 200 http://192.168.1.100:4873/escope/-/escope-3.6.0.tgz
npm http fetch 200 http://192.168.1.100:4873/file-entry-cache/-/file-entry-cache-2.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/globals/-/globals-9.14.0.tgz
npm http fetch 200 http://192.168.1.100:4873/ignore/-/ignore-3.2.0.tgz
npm http fetch 200 http://192.168.1.100:4873/is-resolvable/-/is-resolvable-1.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/levn/-/levn-0.3.0.tgz
npm http fetch 200 http://192.168.1.100:4873/js-yaml/-/js-yaml-3.7.0.tgz
npm http fetch 200 http://192.168.1.100:4873/natural-compare/-/natural-compare-1.4.0.tgz
npm http fetch 200 http://192.168.1.100:4873/optionator/-/optionator-0.8.2.tgz
npm http fetch 200 http://192.168.1.100:4873/path-is-inside/-/path-is-inside-1.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/require-uncached/-/require-uncached-1.0.3.tgz
npm http 200 http://192.168.1.100:4873/shelljs
npm http fetch 200 http://192.168.1.100:4873/user-home/-/user-home-2.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/pluralize/-/pluralize-1.2.1.tgz
npm http fetch 200 http://192.168.1.100:4873/strip-bom/-/strip-bom-3.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/table/-/table-3.8.3.tgz
npm http fetch 200 http://192.168.1.100:4873/text-table/-/text-table-0.2.0.tgz
npm http fetch 200 http://192.168.1.100:4873/json-stable-stringify/-/json-stable-stringify-1.0.1.tgz
npm http fetch 200 http://192.168.1.100:4873/inquirer/-/inquirer-0.12.0.tgz
npm http fetch 200 http://192.168.1.100:4873/espree/-/espree-3.3.2.tgz
npm http request GET http://192.168.1.100:4873/js-tokens
npm http 200 http://192.168.1.100:4873/js-tokens
npm http fetch GET http://192.168.1.100:4873/js-tokens/-/js-tokens-2.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/js-tokens/-/js-tokens-2.0.0.tgz
npm http request GET http://192.168.1.100:4873/typedarray
npm http 304 http://192.168.1.100:4873/typedarray
npm http request GET http://192.168.1.100:4873/es6-map
npm http request GET http://192.168.1.100:4873/es6-weak-map
npm http request GET http://192.168.1.100:4873/esrecurse
npm http 200 http://192.168.1.100:4873/es6-map
npm http 200 http://192.168.1.100:4873/es6-weak-map
npm http 200 http://192.168.1.100:4873/esrecurse
npm http fetch GET http://192.168.1.100:4873/es6-map/-/es6-map-0.1.4.tgz
npm http fetch GET http://192.168.1.100:4873/es6-weak-map/-/es6-weak-map-2.0.1.tgz
npm http fetch GET http://192.168.1.100:4873/esrecurse/-/esrecurse-4.1.0.tgz
npm http fetch 200 http://192.168.1.100:4873/es6-map/-/es6-map-0.1.4.tgz
npm http fetch 200 http://192.168.1.100:4873/es6-weak-map/-/es6-weak-map-2.0.1.tgz
npm http fetch 200 http://192.168.1.100:4873/esrecurse/-/esrecurse-4.1.0.tgz
npm http request GET http://192.168.1.100:4873/es6-set
npm http request GET http://192.168.1.100:4873/event-emitter
npm http request GET http://192.168.1.100:4873/d
npm http request GET http://192.168.1.100:4873/es6-iterator
npm http request GET http://192.168.1.100:4873/es5-ext
npm http request GET http://192.168.1.100:4873/es6-symbol
npm http 200 http://192.168.1.100:4873/event-emitter
npm http fetch GET http://192.168.1.100:4873/event-emitter/-/event-emitter-0.3.4.tgz
npm http 200 http://192.168.1.100:4873/es6-set
npm http 200 http://192.168.1.100:4873/d
npm http fetch 200 http://192.168.1.100:4873/event-emitter/-/event-emitter-0.3.4.tgz
npm http 200 http://192.168.1.100:4873/es6-iterator
npm http 200 http://192.168.1.100:4873/es5-ext
npm http fetch GET http://192.168.1.100:4873/es6-set/-/es6-set-0.1.4.tgz
npm http fetch 200 http://192.168.1.100:4873/es6-set/-/es6-set-0.1.4.tgz
npm http 200 http://192.168.1.100:4873/es6-symbol
npm http fetch GET http://192.168.1.100:4873/estraverse/-/estraverse-4.1.1.tgz
npm http fetch 200 http://192.168.1.100:4873/estraverse/-/estraverse-4.1.1.tgz
npm http request GET http://192.168.1.100:4873/acorn-jsx
npm http request GET http://192.168.1.100:4873/acorn
npm http 200 http://192.168.1.100:4873/acorn-jsx
npm http 304 http://192.168.1.100:4873/acorn
npm http fetch GET http://192.168.1.100:4873/acorn-jsx/-/acorn-jsx-3.0.1.tgz
npm http fetch 200 http://192.168.1.100:4873/acorn-jsx/-/acorn-jsx-3.0.1.tgz
npm http fetch GET http://192.168.1.100:4873/acorn/-/acorn-4.0.3.tgz
npm http fetch 200 http://192.168.1.100:4873/acorn/-/acorn-4.0.3.tgz
npm http request GET http://192.168.1.100:4873/flat-cache
npm http 200 http://192.168.1.100:4873/flat-cache
npm http fetch GET http://192.168.1.100:4873/flat-cache/-/flat-cache-1.2.1.tgz
npm http fetch 200 http://192.168.1.100:4873/flat-cache/-/flat-cache-1.2.1.tgz
npm http request GET http://192.168.1.100:4873/circular-json
npm http request GET http://192.168.1.100:4873/del
npm http request GET http://192.168.1.100:4873/write
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http 200 http://192.168.1.100:4873/circular-json
npm http fetch GET http://192.168.1.100:4873/circular-json/-/circular-json-0.3.1.tgz
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http fetch 200 http://192.168.1.100:4873/circular-json/-/circular-json-0.3.1.tgz
npm http 200 http://192.168.1.100:4873/write
npm http 200 http://192.168.1.100:4873/del
npm http fetch GET http://192.168.1.100:4873/write/-/write-0.2.1.tgz
npm http fetch GET http://192.168.1.100:4873/del/-/del-2.2.2.tgz
npm http fetch 200 http://192.168.1.100:4873/write/-/write-0.2.1.tgz
npm http fetch 200 http://192.168.1.100:4873/del/-/del-2.2.2.tgz
npm http request GET http://192.168.1.100:4873/globby
npm http request GET http://192.168.1.100:4873/is-path-cwd
npm http request GET http://192.168.1.100:4873/is-path-in-cwd
npm http request GET http://192.168.1.100:4873/pify
npm http request GET http://192.168.1.100:4873/pinkie-promise
npm http request GET http://192.168.1.100:4873/rimraf
npm http 304 http://192.168.1.100:4873/pinkie-promise
npm http 200 http://192.168.1.100:4873/is-path-cwd
npm http 200 http://192.168.1.100:4873/globby
npm http 200 http://192.168.1.100:4873/pify
npm http 200 http://192.168.1.100:4873/is-path-in-cwd
npm http fetch GET http://192.168.1.100:4873/is-path-cwd/-/is-path-cwd-1.0.0.tgz
npm http fetch GET http://192.168.1.100:4873/globby/-/globby-5.0.0.tgz
npm http fetch GET http://192.168.1.100:4873/pify/-/pify-2.3.0.tgz
npm http fetch 200 http://192.168.1.100:4873/is-path-cwd/-/is-path-cwd-1.0.0.tgz
npm http fetch GET http://192.168.1.100:4873/is-path-in-cwd/-/is-path-in-cwd-1.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/globby/-/globby-5.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/pify/-/pify-2.3.0.tgz
npm http fetch 200 http://192.168.1.100:4873/is-path-in-cwd/-/is-path-in-cwd-1.0.0.tgz
npm http 304 http://192.168.1.100:4873/rimraf
npm http request GET http://192.168.1.100:4873/array-union
npm http request GET http://192.168.1.100:4873/arrify
npm http 200 http://192.168.1.100:4873/arrify
npm http fetch GET http://192.168.1.100:4873/arrify/-/arrify-1.0.1.tgz
npm http fetch 200 http://192.168.1.100:4873/arrify/-/arrify-1.0.1.tgz
npm http 200 http://192.168.1.100:4873/array-union
npm http fetch GET http://192.168.1.100:4873/array-union/-/array-union-1.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/array-union/-/array-union-1.0.2.tgz
npm http request GET http://192.168.1.100:4873/array-uniq
npm http 200 http://192.168.1.100:4873/array-uniq
npm http fetch GET http://192.168.1.100:4873/array-uniq/-/array-uniq-1.0.3.tgz
npm http fetch 200 http://192.168.1.100:4873/array-uniq/-/array-uniq-1.0.3.tgz
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
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/pinkie
npm http 304 http://192.168.1.100:4873/pinkie
npm http request GET http://192.168.1.100:4873/is-path-inside
npm http 200 http://192.168.1.100:4873/is-path-inside
npm http fetch GET http://192.168.1.100:4873/is-path-inside/-/is-path-inside-1.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/is-path-inside/-/is-path-inside-1.0.0.tgz
npm http request GET http://192.168.1.100:4873/minimist
npm http 200 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/string-width
npm http request GET http://192.168.1.100:4873/ansi-escapes
npm http request GET http://192.168.1.100:4873/cli-width
npm http request GET http://192.168.1.100:4873/cli-cursor
npm http request GET http://192.168.1.100:4873/readline2
npm http request GET http://192.168.1.100:4873/through
npm http request GET http://192.168.1.100:4873/figures
npm http request GET http://192.168.1.100:4873/run-async
npm http request GET http://192.168.1.100:4873/rx-lite
npm http 200 http://192.168.1.100:4873/string-width
npm http fetch GET http://192.168.1.100:4873/string-width/-/string-width-1.0.2.tgz
npm http 304 http://192.168.1.100:4873/cli-width
npm http 304 http://192.168.1.100:4873/cli-cursor
npm http 200 http://192.168.1.100:4873/ansi-escapes
npm http 304 http://192.168.1.100:4873/readline2
npm http fetch GET http://192.168.1.100:4873/cli-width/-/cli-width-2.1.0.tgz
npm http fetch 200 http://192.168.1.100:4873/string-width/-/string-width-1.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/cli-width/-/cli-width-2.1.0.tgz
npm http 200 http://192.168.1.100:4873/through
npm http 304 http://192.168.1.100:4873/figures
npm http 200 http://192.168.1.100:4873/run-async
npm http 304 http://192.168.1.100:4873/rx-lite
npm http request GET http://192.168.1.100:4873/restore-cursor
npm http 304 http://192.168.1.100:4873/restore-cursor
npm http request GET http://192.168.1.100:4873/exit-hook
npm http request GET http://192.168.1.100:4873/onetime
npm http 304 http://192.168.1.100:4873/exit-hook
npm http 304 http://192.168.1.100:4873/onetime
npm http request GET http://192.168.1.100:4873/code-point-at
npm http request GET http://192.168.1.100:4873/is-fullwidth-code-point
npm http request GET http://192.168.1.100:4873/mute-stream
npm http 304 http://192.168.1.100:4873/mute-stream
npm http 304 http://192.168.1.100:4873/code-point-at
npm http 304 http://192.168.1.100:4873/is-fullwidth-code-point
npm http request GET http://192.168.1.100:4873/number-is-nan
npm http 304 http://192.168.1.100:4873/number-is-nan
npm http request GET http://192.168.1.100:4873/tryit
npm http 200 http://192.168.1.100:4873/tryit
npm http fetch GET http://192.168.1.100:4873/tryit/-/tryit-1.0.3.tgz
npm http fetch 200 http://192.168.1.100:4873/tryit/-/tryit-1.0.3.tgz
npm http request GET http://192.168.1.100:4873/argparse
npm http request GET http://192.168.1.100:4873/esprima
npm http 200 http://192.168.1.100:4873/argparse
npm http fetch GET http://192.168.1.100:4873/argparse/-/argparse-1.0.9.tgz
npm http fetch 200 http://192.168.1.100:4873/argparse/-/argparse-1.0.9.tgz
npm http 200 http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/sprintf-js
npm http 200 http://192.168.1.100:4873/sprintf-js
npm http fetch GET http://192.168.1.100:4873/sprintf-js/-/sprintf-js-1.0.3.tgz
npm http fetch 200 http://192.168.1.100:4873/sprintf-js/-/sprintf-js-1.0.3.tgz
npm http request GET http://192.168.1.100:4873/jsonify
npm http 304 http://192.168.1.100:4873/jsonify
npm http request GET http://192.168.1.100:4873/prelude-ls
npm http request GET http://192.168.1.100:4873/type-check
npm http 200 http://192.168.1.100:4873/prelude-ls
npm http 200 http://192.168.1.100:4873/type-check
npm http fetch GET http://192.168.1.100:4873/prelude-ls/-/prelude-ls-1.1.2.tgz
npm http fetch 200 http://192.168.1.100:4873/prelude-ls/-/prelude-ls-1.1.2.tgz
npm http fetch GET http://192.168.1.100:4873/type-check/-/type-check-0.3.2.tgz
npm http fetch 200 http://192.168.1.100:4873/type-check/-/type-check-0.3.2.tgz
npm http request GET http://192.168.1.100:4873/deep-is
npm http request GET http://192.168.1.100:4873/wordwrap
npm http request GET http://192.168.1.100:4873/fast-levenshtein
npm http 200 http://192.168.1.100:4873/deep-is
npm http 200 http://192.168.1.100:4873/fast-levenshtein
npm http 200 http://192.168.1.100:4873/wordwrap
npm http fetch GET http://192.168.1.100:4873/deep-is/-/deep-is-0.1.3.tgz
npm http fetch 200 http://192.168.1.100:4873/deep-is/-/deep-is-0.1.3.tgz
npm http fetch GET http://192.168.1.100:4873/fast-levenshtein/-/fast-levenshtein-2.0.5.tgz
npm http fetch GET http://192.168.1.100:4873/wordwrap/-/wordwrap-1.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/fast-levenshtein/-/fast-levenshtein-2.0.5.tgz
npm http fetch 200 http://192.168.1.100:4873/wordwrap/-/wordwrap-1.0.0.tgz
npm http request GET http://192.168.1.100:4873/caller-path
npm http request GET http://192.168.1.100:4873/resolve-from
npm http 200 http://192.168.1.100:4873/resolve-from
npm http fetch GET http://192.168.1.100:4873/resolve-from/-/resolve-from-1.0.1.tgz
npm http fetch 200 http://192.168.1.100:4873/resolve-from/-/resolve-from-1.0.1.tgz
npm http 200 http://192.168.1.100:4873/caller-path
npm http fetch GET http://192.168.1.100:4873/caller-path/-/caller-path-0.1.0.tgz
npm http fetch 200 http://192.168.1.100:4873/caller-path/-/caller-path-0.1.0.tgz
npm http request GET http://192.168.1.100:4873/callsites
npm http 200 http://192.168.1.100:4873/callsites
npm http fetch GET http://192.168.1.100:4873/callsites/-/callsites-0.2.0.tgz
npm http fetch 200 http://192.168.1.100:4873/callsites/-/callsites-0.2.0.tgz
npm http request GET http://192.168.1.100:4873/interpret
npm http request GET http://192.168.1.100:4873/rechoir
npm http 304 http://192.168.1.100:4873/rechoir
npm http 200 http://192.168.1.100:4873/interpret
npm http request GET http://192.168.1.100:4873/resolve
npm http 200 http://192.168.1.100:4873/resolve
npm http request GET http://192.168.1.100:4873/ajv
npm http request GET http://192.168.1.100:4873/ajv-keywords
npm http request GET http://192.168.1.100:4873/slice-ansi
npm http fetch GET http://192.168.1.100:4873/string-width/-/string-width-2.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/string-width/-/string-width-2.0.0.tgz
npm http 200 http://192.168.1.100:4873/slice-ansi
npm http 200 http://192.168.1.100:4873/ajv-keywords
npm http fetch GET http://192.168.1.100:4873/slice-ansi/-/slice-ansi-0.0.4.tgz
npm http fetch GET http://192.168.1.100:4873/ajv-keywords/-/ajv-keywords-1.2.0.tgz
npm http 200 http://192.168.1.100:4873/ajv
npm http fetch 200 http://192.168.1.100:4873/slice-ansi/-/slice-ansi-0.0.4.tgz
npm http fetch 200 http://192.168.1.100:4873/ajv-keywords/-/ajv-keywords-1.2.0.tgz
npm http fetch GET http://192.168.1.100:4873/ajv/-/ajv-4.10.0.tgz
npm http fetch 200 http://192.168.1.100:4873/ajv/-/ajv-4.10.0.tgz
npm http request GET http://192.168.1.100:4873/co
npm http 200 http://192.168.1.100:4873/co
npm http fetch GET http://192.168.1.100:4873/co/-/co-4.6.0.tgz
npm http fetch 200 http://192.168.1.100:4873/co/-/co-4.6.0.tgz
npm http fetch GET http://192.168.1.100:4873/is-fullwidth-code-point/-/is-fullwidth-code-point-2.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/is-fullwidth-code-point/-/is-fullwidth-code-point-2.0.0.tgz
npm http request GET http://192.168.1.100:4873/os-homedir
npm http 304 http://192.168.1.100:4873/os-homedir
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/underscore
npm http request GET http://192.168.1.100:4873/wrench
npm http request GET http://192.168.1.100:4873/js2xmlparser
npm http request GET http://192.168.1.100:4873/catharsis
npm http request GET http://192.168.1.100:4873/requizzle
npm http request GET http://192.168.1.100:4873/marked
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 200 http://192.168.1.100:4873/underscore
npm http 304 http://192.168.1.100:4873/async
npm http 200 http://192.168.1.100:4873/js2xmlparser
npm http 200 http://192.168.1.100:4873/wrench
npm http 200 http://192.168.1.100:4873/catharsis
npm WARN deprecated wrench@1.5.9: wrench.js is deprecated! You should check out fs-extra (https://github.com/jprichardson/node-fs-extra) for any operations you were using wrench for. Thanks for all the usage over the years.
npm http 200 http://192.168.1.100:4873/requizzle
npm http 200 http://192.168.1.100:4873/marked
npm http fetch 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http request GET http://192.168.1.100:4873/underscore-contrib
npm http 200 http://192.168.1.100:4873/underscore-contrib
npm WARN prefer global marked@0.3.6 should be installed with -g
npm WARN install@0.0.1 No repository field.

```

Error: Command failed: npm WARN thali-test-server@0.0.1 No repository field.
npm WARN thali-test-server@0.0.1 No license field.
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/javascript-state-machine
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/uuid
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/winston
npm http 304 http://192.168.1.100:4873/express
npm http 200 http://192.168.1.100:4873/ip
npm http 200 http://192.168.1.100:4873/js-extend
npm http 200 http://192.168.1.100:4873/body-parser
npm http 200 http://192.168.1.100:4873/javascript-state-machine
npm http 200 http://192.168.1.100:4873/long
npm http 200 http://192.168.1.100:4873/lie
npm http 200 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/uuid
npm http 200 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/bytes
npm http 304 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/type-is
npm http 200 http://192.168.1.100:4873/raw-body
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
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/array-flatten
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
npm http 304 http://192.168.1.100:4873/vary
npm http 304 http://192.168.1.100:4873/utils-merge
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
npm http 200 http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/duplexify
npm http 304 http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 200 http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/stream-shift
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http 304 http://192.168.1.100:4873/end-of-stream
npm http 304 http://192.168.1.100:4873/stream-shift
npm http request GET http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/wrappy
npm http 304 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/core-util-is
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/string_decoder
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/buffer-shims
npm http 304 http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/process-nextick-args
npm http 304 http://192.168.1.100:4873/string_decoder
npm http 304 http://192.168.1.100:4873/core-util-is
npm http 304 http://192.168.1.100:4873/util-deprecate
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 200 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/json-stringify-safe
npm http 200 http://192.168.1.100:4873/tunnel-agent
npm http 304 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 200 http://192.168.1.100:4873/form-data
npm http 200 http://192.168.1.100:4873/hawk
npm http 200 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http fetch GET http://192.168.1.100:4873/async/-/async-2.1.4.tgz
npm http fetch 200 http://192.168.1.100:4873/async/-/async-2.1.4.tgz
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
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http request GET http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http 304 http://192.168.1.100:4873/ansi-styles
npm http 304 http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http 304 http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http 304 http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/boom
npm http 200 http://192.168.1.100:4873/cryptiles
npm http 304 http://192.168.1.100:4873/hoek
npm http 200 http://192.168.1.100:4873/sntp
npm http 200 http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 304 http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/punycode
npm http 304 http://192.168.1.100:4873/punycode
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/jsonschema
npm http 200 http://192.168.1.100:4873/jsonschema
npm http 304 http://192.168.1.100:4873/object-assign
npm http fetch GET http://192.168.1.100:4873/jsonschema/-/jsonschema-1.1.1.tgz
npm http fetch 200 http://192.168.1.100:4873/jsonschema/-/jsonschema-1.1.1.tgz
npm http request GET http://192.168.1.100:4873/colors
npm http request GET http://192.168.1.100:4873/cycle
npm http request GET http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/pkginfo
npm http request GET http://192.168.1.100:4873/stack-trace
npm http 304 http://192.168.1.100:4873/colors
npm http 304 http://192.168.1.100:4873/eyes
npm http 304 http://192.168.1.100:4873/cycle
npm http 304 http://192.168.1.100:4873/stack-trace
npm http 304 http://192.168.1.100:4873/pkginfo
npm http request GET http://192.168.1.100:4873/eslint
npm http request GET http://192.168.1.100:4873/jsdoc
npm http 200 http://192.168.1.100:4873/jsdoc
npm http 200 http://192.168.1.100:4873/eslint
npm http fetch GET http://192.168.1.100:4873/eslint/-/eslint-3.11.1.tgz
npm http fetch 200 http://192.168.1.100:4873/eslint/-/eslint-3.11.1.tgz
npm http request GET http://192.168.1.100:4873/babel-code-frame
npm http request GET http://192.168.1.100:4873/doctrine
npm http request GET http://192.168.1.100:4873/escope
npm http request GET http://192.168.1.100:4873/estraverse
npm http request GET http://192.168.1.100:4873/esutils
npm http request GET http://192.168.1.100:4873/file-entry-cache
npm http request GET http://192.168.1.100:4873/globals
npm http request GET http://192.168.1.100:4873/ignore
npm http request GET http://192.168.1.100:4873/is-resolvable
npm http request GET http://192.168.1.100:4873/js-yaml
npm http request GET http://192.168.1.100:4873/levn
npm http request GET http://192.168.1.100:4873/natural-compare
npm http request GET http://192.168.1.100:4873/optionator
npm http request GET http://192.168.1.100:4873/path-is-inside
npm http request GET http://192.168.1.100:4873/pluralize
npm http request GET http://192.168.1.100:4873/require-uncached
npm http request GET http://192.168.1.100:4873/strip-bom
npm http request GET http://192.168.1.100:4873/table
npm http request GET http://192.168.1.100:4873/text-table
npm http request GET http://192.168.1.100:4873/user-home
npm http request GET http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/inquirer
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/espree
npm http request GET http://192.168.1.100:4873/imurmurhash
npm http request GET http://192.168.1.100:4873/json-stable-stringify
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/progress
npm http request GET http://192.168.1.100:4873/shelljs
npm http 200 http://192.168.1.100:4873/babel-code-frame
npm http 200 http://192.168.1.100:4873/esutils
npm http 200 http://192.168.1.100:4873/doctrine
npm http 200 http://192.168.1.100:4873/estraverse
npm http 200 http://192.168.1.100:4873/escope
npm http fetch GET http://192.168.1.100:4873/esutils/-/esutils-2.0.2.tgz
npm http fetch GET http://192.168.1.100:4873/babel-code-frame/-/babel-code-frame-6.20.0.tgz
npm http fetch GET http://192.168.1.100:4873/doctrine/-/doctrine-1.5.0.tgz
npm http fetch GET http://192.168.1.100:4873/estraverse/-/estraverse-4.2.0.tgz
npm http fetch GET http://192.168.1.100:4873/escope/-/escope-3.6.0.tgz
npm http 200 http://192.168.1.100:4873/file-entry-cache
npm http 200 http://192.168.1.100:4873/globals
npm http 200 http://192.168.1.100:4873/ignore
npm http 200 http://192.168.1.100:4873/is-resolvable
npm http fetch GET http://192.168.1.100:4873/file-entry-cache/-/file-entry-cache-2.0.0.tgz
npm http fetch GET http://192.168.1.100:4873/globals/-/globals-9.14.0.tgz
npm http 200 http://192.168.1.100:4873/js-yaml
npm http fetch GET http://192.168.1.100:4873/ignore/-/ignore-3.2.0.tgz
npm http fetch GET http://192.168.1.100:4873/is-resolvable/-/is-resolvable-1.0.0.tgz
npm http fetch GET http://192.168.1.100:4873/js-yaml/-/js-yaml-3.7.0.tgz
npm http 200 http://192.168.1.100:4873/levn
npm http 200 http://192.168.1.100:4873/natural-compare
npm http 200 http://192.168.1.100:4873/optionator
npm http 200 http://192.168.1.100:4873/path-is-inside
npm http fetch GET http://192.168.1.100:4873/levn/-/levn-0.3.0.tgz
npm http 200 http://192.168.1.100:4873/pluralize
npm http fetch GET http://192.168.1.100:4873/natural-compare/-/natural-compare-1.4.0.tgz
npm http fetch GET http://192.168.1.100:4873/optionator/-/optionator-0.8.2.tgz
npm http fetch GET http://192.168.1.100:4873/path-is-inside/-/path-is-inside-1.0.2.tgz
npm http 200 http://192.168.1.100:4873/require-uncached
npm http 200 http://192.168.1.100:4873/strip-bom
npm http 200 http://192.168.1.100:4873/user-home
npm http 200 http://192.168.1.100:4873/table
npm http 200 http://192.168.1.100:4873/text-table
npm http fetch GET http://192.168.1.100:4873/require-uncached/-/require-uncached-1.0.3.tgz
npm http fetch GET http://192.168.1.100:4873/pluralize/-/pluralize-1.2.1.tgz
npm http fetch GET http://192.168.1.100:4873/user-home/-/user-home-2.0.0.tgz
npm http fetch GET http://192.168.1.100:4873/strip-bom/-/strip-bom-3.0.0.tgz
npm http fetch GET http://192.168.1.100:4873/table/-/table-3.8.3.tgz
npm http fetch GET http://192.168.1.100:4873/text-table/-/text-table-0.2.0.tgz
npm http 200 http://192.168.1.100:4873/inquirer
npm http fetch GET http://192.168.1.100:4873/inquirer/-/inquirer-0.12.0.tgz
npm http 304 http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/mkdirp
npm http 200 http://192.168.1.100:4873/concat-stream
npm http 200 http://192.168.1.100:4873/espree
npm http fetch GET http://192.168.1.100:4873/espree/-/espree-3.3.2.tgz
npm http 304 http://192.168.1.100:4873/json-stable-stringify
npm http 304 http://192.168.1.100:4873/imurmurhash
npm http fetch GET http://192.168.1.100:4873/json-stable-stringify/-/json-stable-stringify-1.0.1.tgz
npm http 200 http://192.168.1.100:4873/progress
npm http 200 http://192.168.1.100:4873/strip-json-comments
npm http fetch 200 http://192.168.1.100:4873/esutils/-/esutils-2.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/babel-code-frame/-/babel-code-frame-6.20.0.tgz
npm http fetch 200 http://192.168.1.100:4873/estraverse/-/estraverse-4.2.0.tgz
npm http fetch 200 http://192.168.1.100:4873/doctrine/-/doctrine-1.5.0.tgz
npm http fetch 200 http://192.168.1.100:4873/escope/-/escope-3.6.0.tgz
npm http fetch 200 http://192.168.1.100:4873/file-entry-cache/-/file-entry-cache-2.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/globals/-/globals-9.14.0.tgz
npm http fetch 200 http://192.168.1.100:4873/ignore/-/ignore-3.2.0.tgz
npm http fetch 200 http://192.168.1.100:4873/is-resolvable/-/is-resolvable-1.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/levn/-/levn-0.3.0.tgz
npm http fetch 200 http://192.168.1.100:4873/js-yaml/-/js-yaml-3.7.0.tgz
npm http fetch 200 http://192.168.1.100:4873/natural-compare/-/natural-compare-1.4.0.tgz
npm http fetch 200 http://192.168.1.100:4873/optionator/-/optionator-0.8.2.tgz
npm http fetch 200 http://192.168.1.100:4873/path-is-inside/-/path-is-inside-1.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/require-uncached/-/require-uncached-1.0.3.tgz
npm http 200 http://192.168.1.100:4873/shelljs
npm http fetch 200 http://192.168.1.100:4873/user-home/-/user-home-2.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/pluralize/-/pluralize-1.2.1.tgz
npm http fetch 200 http://192.168.1.100:4873/strip-bom/-/strip-bom-3.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/table/-/table-3.8.3.tgz
npm http fetch 200 http://192.168.1.100:4873/text-table/-/text-table-0.2.0.tgz
npm http fetch 200 http://192.168.1.100:4873/json-stable-stringify/-/json-stable-stringify-1.0.1.tgz
npm http fetch 200 http://192.168.1.100:4873/inquirer/-/inquirer-0.12.0.tgz
npm http fetch 200 http://192.168.1.100:4873/espree/-/espree-3.3.2.tgz
npm http request GET http://192.168.1.100:4873/js-tokens
npm http 200 http://192.168.1.100:4873/js-tokens
npm http fetch GET http://192.168.1.100:4873/js-tokens/-/js-tokens-2.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/js-tokens/-/js-tokens-2.0.0.tgz
npm http request GET http://192.168.1.100:4873/typedarray
npm http 304 http://192.168.1.100:4873/typedarray
npm http request GET http://192.168.1.100:4873/es6-map
npm http request GET http://192.168.1.100:4873/es6-weak-map
npm http request GET http://192.168.1.100:4873/esrecurse
npm http 200 http://192.168.1.100:4873/es6-map
npm http 200 http://192.168.1.100:4873/es6-weak-map
npm http 200 http://192.168.1.100:4873/esrecurse
npm http fetch GET http://192.168.1.100:4873/es6-map/-/es6-map-0.1.4.tgz
npm http fetch GET http://192.168.1.100:4873/es6-weak-map/-/es6-weak-map-2.0.1.tgz
npm http fetch GET http://192.168.1.100:4873/esrecurse/-/esrecurse-4.1.0.tgz
npm http fetch 200 http://192.168.1.100:4873/es6-map/-/es6-map-0.1.4.tgz
npm http fetch 200 http://192.168.1.100:4873/es6-weak-map/-/es6-weak-map-2.0.1.tgz
npm http fetch 200 http://192.168.1.100:4873/esrecurse/-/esrecurse-4.1.0.tgz
npm http request GET http://192.168.1.100:4873/es6-set
npm http request GET http://192.168.1.100:4873/event-emitter
npm http request GET http://192.168.1.100:4873/d
npm http request GET http://192.168.1.100:4873/es6-iterator
npm http request GET http://192.168.1.100:4873/es5-ext
npm http request GET http://192.168.1.100:4873/es6-symbol
npm http 200 http://192.168.1.100:4873/event-emitter
npm http fetch GET http://192.168.1.100:4873/event-emitter/-/event-emitter-0.3.4.tgz
npm http 200 http://192.168.1.100:4873/es6-set
npm http 200 http://192.168.1.100:4873/d
npm http fetch 200 http://192.168.1.100:4873/event-emitter/-/event-emitter-0.3.4.tgz
npm http 200 http://192.168.1.100:4873/es6-iterator
npm http 200 http://192.168.1.100:4873/es5-ext
npm http fetch GET http://192.168.1.100:4873/es6-set/-/es6-set-0.1.4.tgz
npm http fetch 200 http://192.168.1.100:4873/es6-set/-/es6-set-0.1.4.tgz
npm http 200 http://192.168.1.100:4873/es6-symbol
npm http fetch GET http://192.168.1.100:4873/estraverse/-/estraverse-4.1.1.tgz
npm http fetch 200 http://192.168.1.100:4873/estraverse/-/estraverse-4.1.1.tgz
npm http request GET http://192.168.1.100:4873/acorn-jsx
npm http request GET http://192.168.1.100:4873/acorn
npm http 200 http://192.168.1.100:4873/acorn-jsx
npm http 304 http://192.168.1.100:4873/acorn
npm http fetch GET http://192.168.1.100:4873/acorn-jsx/-/acorn-jsx-3.0.1.tgz
npm http fetch 200 http://192.168.1.100:4873/acorn-jsx/-/acorn-jsx-3.0.1.tgz
npm http fetch GET http://192.168.1.100:4873/acorn/-/acorn-4.0.3.tgz
npm http fetch 200 http://192.168.1.100:4873/acorn/-/acorn-4.0.3.tgz
npm http request GET http://192.168.1.100:4873/flat-cache
npm http 200 http://192.168.1.100:4873/flat-cache
npm http fetch GET http://192.168.1.100:4873/flat-cache/-/flat-cache-1.2.1.tgz
npm http fetch 200 http://192.168.1.100:4873/flat-cache/-/flat-cache-1.2.1.tgz
npm http request GET http://192.168.1.100:4873/circular-json
npm http request GET http://192.168.1.100:4873/del
npm http request GET http://192.168.1.100:4873/write
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http 200 http://192.168.1.100:4873/circular-json
npm http fetch GET http://192.168.1.100:4873/circular-json/-/circular-json-0.3.1.tgz
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http fetch 200 http://192.168.1.100:4873/circular-json/-/circular-json-0.3.1.tgz
npm http 200 http://192.168.1.100:4873/write
npm http 200 http://192.168.1.100:4873/del
npm http fetch GET http://192.168.1.100:4873/write/-/write-0.2.1.tgz
npm http fetch GET http://192.168.1.100:4873/del/-/del-2.2.2.tgz
npm http fetch 200 http://192.168.1.100:4873/write/-/write-0.2.1.tgz
npm http fetch 200 http://192.168.1.100:4873/del/-/del-2.2.2.tgz
npm http request GET http://192.168.1.100:4873/globby
npm http request GET http://192.168.1.100:4873/is-path-cwd
npm http request GET http://192.168.1.100:4873/is-path-in-cwd
npm http request GET http://192.168.1.100:4873/pify
npm http request GET http://192.168.1.100:4873/pinkie-promise
npm http request GET http://192.168.1.100:4873/rimraf
npm http 304 http://192.168.1.100:4873/pinkie-promise
npm http 200 http://192.168.1.100:4873/is-path-cwd
npm http 200 http://192.168.1.100:4873/globby
npm http 200 http://192.168.1.100:4873/pify
npm http 200 http://192.168.1.100:4873/is-path-in-cwd
npm http fetch GET http://192.168.1.100:4873/is-path-cwd/-/is-path-cwd-1.0.0.tgz
npm http fetch GET http://192.168.1.100:4873/globby/-/globby-5.0.0.tgz
npm http fetch GET http://192.168.1.100:4873/pify/-/pify-2.3.0.tgz
npm http fetch 200 http://192.168.1.100:4873/is-path-cwd/-/is-path-cwd-1.0.0.tgz
npm http fetch GET http://192.168.1.100:4873/is-path-in-cwd/-/is-path-in-cwd-1.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/globby/-/globby-5.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/pify/-/pify-2.3.0.tgz
npm http fetch 200 http://192.168.1.100:4873/is-path-in-cwd/-/is-path-in-cwd-1.0.0.tgz
npm http 304 http://192.168.1.100:4873/rimraf
npm http request GET http://192.168.1.100:4873/array-union
npm http request GET http://192.168.1.100:4873/arrify
npm http 200 http://192.168.1.100:4873/arrify
npm http fetch GET http://192.168.1.100:4873/arrify/-/arrify-1.0.1.tgz
npm http fetch 200 http://192.168.1.100:4873/arrify/-/arrify-1.0.1.tgz
npm http 200 http://192.168.1.100:4873/array-union
npm http fetch GET http://192.168.1.100:4873/array-union/-/array-union-1.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/array-union/-/array-union-1.0.2.tgz
npm http request GET http://192.168.1.100:4873/array-uniq
npm http 200 http://192.168.1.100:4873/array-uniq
npm http fetch GET http://192.168.1.100:4873/array-uniq/-/array-uniq-1.0.3.tgz
npm http fetch 200 http://192.168.1.100:4873/array-uniq/-/array-uniq-1.0.3.tgz
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
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/pinkie
npm http 304 http://192.168.1.100:4873/pinkie
npm http request GET http://192.168.1.100:4873/is-path-inside
npm http 200 http://192.168.1.100:4873/is-path-inside
npm http fetch GET http://192.168.1.100:4873/is-path-inside/-/is-path-inside-1.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/is-path-inside/-/is-path-inside-1.0.0.tgz
npm http request GET http://192.168.1.100:4873/minimist
npm http 200 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/string-width
npm http request GET http://192.168.1.100:4873/ansi-escapes
npm http request GET http://192.168.1.100:4873/cli-width
npm http request GET http://192.168.1.100:4873/cli-cursor
npm http request GET http://192.168.1.100:4873/readline2
npm http request GET http://192.168.1.100:4873/through
npm http request GET http://192.168.1.100:4873/figures
npm http request GET http://192.168.1.100:4873/run-async
npm http request GET http://192.168.1.100:4873/rx-lite
npm http 200 http://192.168.1.100:4873/string-width
npm http fetch GET http://192.168.1.100:4873/string-width/-/string-width-1.0.2.tgz
npm http 304 http://192.168.1.100:4873/cli-width
npm http 304 http://192.168.1.100:4873/cli-cursor
npm http 200 http://192.168.1.100:4873/ansi-escapes
npm http 304 http://192.168.1.100:4873/readline2
npm http fetch GET http://192.168.1.100:4873/cli-width/-/cli-width-2.1.0.tgz
npm http fetch 200 http://192.168.1.100:4873/string-width/-/string-width-1.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/cli-width/-/cli-width-2.1.0.tgz
npm http 200 http://192.168.1.100:4873/through
npm http 304 http://192.168.1.100:4873/figures
npm http 200 http://192.168.1.100:4873/run-async
npm http 304 http://192.168.1.100:4873/rx-lite
npm http request GET http://192.168.1.100:4873/restore-cursor
npm http 304 http://192.168.1.100:4873/restore-cursor
npm http request GET http://192.168.1.100:4873/exit-hook
npm http request GET http://192.168.1.100:4873/onetime
npm http 304 http://192.168.1.100:4873/exit-hook
npm http 304 http://192.168.1.100:4873/onetime
npm http request GET http://192.168.1.100:4873/code-point-at
npm http request GET http://192.168.1.100:4873/is-fullwidth-code-point
npm http request GET http://192.168.1.100:4873/mute-stream
npm http 304 http://192.168.1.100:4873/mute-stream
npm http 304 http://192.168.1.100:4873/code-point-at
npm http 304 http://192.168.1.100:4873/is-fullwidth-code-point
npm http request GET http://192.168.1.100:4873/number-is-nan
npm http 304 http://192.168.1.100:4873/number-is-nan
npm http request GET http://192.168.1.100:4873/tryit
npm http 200 http://192.168.1.100:4873/tryit
npm http fetch GET http://192.168.1.100:4873/tryit/-/tryit-1.0.3.tgz
npm http fetch 200 http://192.168.1.100:4873/tryit/-/tryit-1.0.3.tgz
npm http request GET http://192.168.1.100:4873/argparse
npm http request GET http://192.168.1.100:4873/esprima
npm http 200 http://192.168.1.100:4873/argparse
npm http fetch GET http://192.168.1.100:4873/argparse/-/argparse-1.0.9.tgz
npm http fetch 200 http://192.168.1.100:4873/argparse/-/argparse-1.0.9.tgz
npm http 200 http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/sprintf-js
npm http 200 http://192.168.1.100:4873/sprintf-js
npm http fetch GET http://192.168.1.100:4873/sprintf-js/-/sprintf-js-1.0.3.tgz
npm http fetch 200 http://192.168.1.100:4873/sprintf-js/-/sprintf-js-1.0.3.tgz
npm http request GET http://192.168.1.100:4873/jsonify
npm http 304 http://192.168.1.100:4873/jsonify
npm http request GET http://192.168.1.100:4873/prelude-ls
npm http request GET http://192.168.1.100:4873/type-check
npm http 200 http://192.168.1.100:4873/prelude-ls
npm http 200 http://192.168.1.100:4873/type-check
npm http fetch GET http://192.168.1.100:4873/prelude-ls/-/prelude-ls-1.1.2.tgz
npm http fetch 200 http://192.168.1.100:4873/prelude-ls/-/prelude-ls-1.1.2.tgz
npm http fetch GET http://192.168.1.100:4873/type-check/-/type-check-0.3.2.tgz
npm http fetch 200 http://192.168.1.100:4873/type-check/-/type-check-0.3.2.tgz
npm http request GET http://192.168.1.100:4873/deep-is
npm http request GET http://192.168.1.100:4873/wordwrap
npm http request GET http://192.168.1.100:4873/fast-levenshtein
npm http 200 http://192.168.1.100:4873/deep-is
npm http 200 http://192.168.1.100:4873/fast-levenshtein
npm http 200 http://192.168.1.100:4873/wordwrap
npm http fetch GET http://192.168.1.100:4873/deep-is/-/deep-is-0.1.3.tgz
npm http fetch 200 http://192.168.1.100:4873/deep-is/-/deep-is-0.1.3.tgz
npm http fetch GET http://192.168.1.100:4873/fast-levenshtein/-/fast-levenshtein-2.0.5.tgz
npm http fetch GET http://192.168.1.100:4873/wordwrap/-/wordwrap-1.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/fast-levenshtein/-/fast-levenshtein-2.0.5.tgz
npm http fetch 200 http://192.168.1.100:4873/wordwrap/-/wordwrap-1.0.0.tgz
npm http request GET http://192.168.1.100:4873/caller-path
npm http request GET http://192.168.1.100:4873/resolve-from
npm http 200 http://192.168.1.100:4873/resolve-from
npm http fetch GET http://192.168.1.100:4873/resolve-from/-/resolve-from-1.0.1.tgz
npm http fetch 200 http://192.168.1.100:4873/resolve-from/-/resolve-from-1.0.1.tgz
npm http 200 http://192.168.1.100:4873/caller-path
npm http fetch GET http://192.168.1.100:4873/caller-path/-/caller-path-0.1.0.tgz
npm http fetch 200 http://192.168.1.100:4873/caller-path/-/caller-path-0.1.0.tgz
npm http request GET http://192.168.1.100:4873/callsites
npm http 200 http://192.168.1.100:4873/callsites
npm http fetch GET http://192.168.1.100:4873/callsites/-/callsites-0.2.0.tgz
npm http fetch 200 http://192.168.1.100:4873/callsites/-/callsites-0.2.0.tgz
npm http request GET http://192.168.1.100:4873/interpret
npm http request GET http://192.168.1.100:4873/rechoir
npm http 304 http://192.168.1.100:4873/rechoir
npm http 200 http://192.168.1.100:4873/interpret
npm http request GET http://192.168.1.100:4873/resolve
npm http 200 http://192.168.1.100:4873/resolve
npm http request GET http://192.168.1.100:4873/ajv
npm http request GET http://192.168.1.100:4873/ajv-keywords
npm http request GET http://192.168.1.100:4873/slice-ansi
npm http fetch GET http://192.168.1.100:4873/string-width/-/string-width-2.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/string-width/-/string-width-2.0.0.tgz
npm http 200 http://192.168.1.100:4873/slice-ansi
npm http 200 http://192.168.1.100:4873/ajv-keywords
npm http fetch GET http://192.168.1.100:4873/slice-ansi/-/slice-ansi-0.0.4.tgz
npm http fetch GET http://192.168.1.100:4873/ajv-keywords/-/ajv-keywords-1.2.0.tgz
npm http 200 http://192.168.1.100:4873/ajv
npm http fetch 200 http://192.168.1.100:4873/slice-ansi/-/slice-ansi-0.0.4.tgz
npm http fetch 200 http://192.168.1.100:4873/ajv-keywords/-/ajv-keywords-1.2.0.tgz
npm http fetch GET http://192.168.1.100:4873/ajv/-/ajv-4.10.0.tgz
npm http fetch 200 http://192.168.1.100:4873/ajv/-/ajv-4.10.0.tgz
npm http request GET http://192.168.1.100:4873/co
npm http 200 http://192.168.1.100:4873/co
npm http fetch GET http://192.168.1.100:4873/co/-/co-4.6.0.tgz
npm http fetch 200 http://192.168.1.100:4873/co/-/co-4.6.0.tgz
npm http fetch GET http://192.168.1.100:4873/is-fullwidth-code-point/-/is-fullwidth-code-point-2.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/is-fullwidth-code-point/-/is-fullwidth-code-point-2.0.0.tgz
npm http request GET http://192.168.1.100:4873/os-homedir
npm http 304 http://192.168.1.100:4873/os-homedir
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/underscore
npm http request GET http://192.168.1.100:4873/wrench
npm http request GET http://192.168.1.100:4873/js2xmlparser
npm http request GET http://192.168.1.100:4873/catharsis
npm http request GET http://192.168.1.100:4873/requizzle
npm http request GET http://192.168.1.100:4873/marked
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 200 http://192.168.1.100:4873/underscore
npm http 304 http://192.168.1.100:4873/async
npm http 200 http://192.168.1.100:4873/js2xmlparser
npm http 200 http://192.168.1.100:4873/wrench
npm http 200 http://192.168.1.100:4873/catharsis
npm WARN deprecated wrench@1.5.9: wrench.js is deprecated! You should check out fs-extra (https://github.com/jprichardson/node-fs-extra) for any operations you were using wrench for. Thanks for all the usage over the years.
npm http 200 http://192.168.1.100:4873/requizzle
npm http 200 http://192.168.1.100:4873/marked
npm http fetch 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http request GET http://192.168.1.100:4873/underscore-contrib
npm http 200 http://192.168.1.100:4873/underscore-contrib
npm WARN prefer global marked@0.3.6 should be installed with -g
npm WARN install@0.0.1 No repository field.
