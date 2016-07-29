#### Test (Fail) 79426650 Build Logs


```


```

```
Already up-to-date.

From https://github.com/thaliproject/Thali_CordovaPlugin
   d1cf255..ec0c820  vNext_yarong_780 -> origin/vNext_yarong_780

```

```
Your branch is up-to-date with 'origin/master'.
Branch vNext set up to track remote branch vNext from origin.
Already up-to-date.

Already on 'master'
Switched to a new branch 'vNext'
Note: checking out 'ec0c820'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at ec0c820... Put diagonistics into installCustomPouchDB

```

```
-e [0;32mAndroid native UT files will be copied to the platform folder
 [0m
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
│       ├─┬ minimatch@3.0.2 
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
│ │ │ │ │ ├─┬ minimatch@3.0.2 
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
│       ├─┬ minimatch@3.0.2 
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
npm install of fs-extra-promise@0.4.0 failed with error Error: Command failed: /bin/sh: npm: command not found
, stdout: , stderr: /bin/sh: npm: command not found

-e [0;31mcompilation aborted
 [0m
build aborted
 [0m

npm http request GET https://registry.npmjs.org/fs-extra-promise
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/socket.io
npm http request GET https://registry.npmjs.org/winston
npm http request GET https://registry.npmjs.org/express
npm http 200 https://registry.npmjs.org/winston
npm http 200 https://registry.npmjs.org/socket.io
npm http fetch GET https://registry.npmjs.org/socket.io/-/socket.io-1.3.6.tgz
npm http 200 https://registry.npmjs.org/express
npm http fetch 200 https://registry.npmjs.org/socket.io/-/socket.io-1.3.6.tgz
npm http 200 https://registry.npmjs.org/lie
npm http fetch GET https://registry.npmjs.org/lie/-/lie-3.0.4.tgz
npm http 200 https://registry.npmjs.org/fs-extra-promise
npm http fetch GET https://registry.npmjs.org/fs-extra-promise/-/fs-extra-promise-0.2.0.tgz
npm http fetch 200 https://registry.npmjs.org/lie/-/lie-3.0.4.tgz
npm http fetch 200 https://registry.npmjs.org/fs-extra-promise/-/fs-extra-promise-0.2.0.tgz
npm http request GET https://registry.npmjs.org/array-flatten
npm http request GET https://registry.npmjs.org/accepts
npm http request GET https://registry.npmjs.org/etag
npm http request GET https://registry.npmjs.org/depd
npm http request GET https://registry.npmjs.org/escape-html
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/cookie
npm http request GET https://registry.npmjs.org/cookie-signature
npm http request GET https://registry.npmjs.org/content-type
npm http request GET https://registry.npmjs.org/content-disposition
npm http request GET https://registry.npmjs.org/proxy-addr
npm http request GET https://registry.npmjs.org/parseurl
npm http request GET https://registry.npmjs.org/on-finished
npm http request GET https://registry.npmjs.org/path-to-regexp
npm http request GET https://registry.npmjs.org/merge-descriptors
npm http request GET https://registry.npmjs.org/methods
npm http request GET https://registry.npmjs.org/fresh
npm http request GET https://registry.npmjs.org/finalhandler
npm http request GET https://registry.npmjs.org/range-parser
npm http request GET https://registry.npmjs.org/send
npm http request GET https://registry.npmjs.org/utils-merge
npm http request GET https://registry.npmjs.org/type-is
npm http request GET https://registry.npmjs.org/serve-static
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/vary
npm http 200 https://registry.npmjs.org/etag
npm http 200 https://registry.npmjs.org/escape-html
npm http 200 https://registry.npmjs.org/array-flatten
npm http 200 https://registry.npmjs.org/depd
npm http 200 https://registry.npmjs.org/accepts
npm http 200 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/content-disposition
npm http 200 https://registry.npmjs.org/cookie
npm http 200 https://registry.npmjs.org/cookie-signature
npm http 200 https://registry.npmjs.org/content-type
npm http 200 https://registry.npmjs.org/proxy-addr
npm http 200 https://registry.npmjs.org/parseurl
npm http 304 https://registry.npmjs.org/on-finished
npm http 304 https://registry.npmjs.org/fresh
npm http 200 https://registry.npmjs.org/methods
npm http 200 https://registry.npmjs.org/merge-descriptors
npm http 200 https://registry.npmjs.org/path-to-regexp
npm http fetch GET https://registry.npmjs.org/content-type/-/content-type-1.0.2.tgz
npm http 200 https://registry.npmjs.org/finalhandler
npm http 200 https://registry.npmjs.org/range-parser
npm http 200 https://registry.npmjs.org/utils-merge
npm http 200 https://registry.npmjs.org/type-is
npm http 200 https://registry.npmjs.org/send
npm http 304 https://registry.npmjs.org/vary
npm http fetch 200 https://registry.npmjs.org/content-type/-/content-type-1.0.2.tgz
npm http 200 https://registry.npmjs.org/serve-static
npm http 200 https://registry.npmjs.org/qs
npm http fetch GET https://registry.npmjs.org/type-is/-/type-is-1.6.13.tgz
npm http fetch GET https://registry.npmjs.org/serve-static/-/serve-static-1.10.3.tgz
npm http fetch 200 https://registry.npmjs.org/type-is/-/type-is-1.6.13.tgz
npm http fetch 200 https://registry.npmjs.org/serve-static/-/serve-static-1.10.3.tgz
npm http request GET https://registry.npmjs.org/negotiator
npm http request GET https://registry.npmjs.org/mime-types
npm http 200 https://registry.npmjs.org/negotiator
npm http 200 https://registry.npmjs.org/mime-types
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
npm http request GET https://registry.npmjs.org/mime
npm http request GET https://registry.npmjs.org/statuses
npm http request GET https://registry.npmjs.org/destroy
npm http request GET https://registry.npmjs.org/http-errors
npm http 200 https://registry.npmjs.org/mime
npm http 200 https://registry.npmjs.org/statuses
npm http 200 https://registry.npmjs.org/http-errors
npm http 304 https://registry.npmjs.org/destroy
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
npm http fetch GET https://registry.npmjs.org/jsonfile/-/jsonfile-2.3.1.tgz
npm http 200 https://registry.npmjs.org/graceful-fs
npm http fetch GET https://registry.npmjs.org/rimraf/-/rimraf-2.5.4.tgz
npm http fetch GET https://registry.npmjs.org/graceful-fs/-/graceful-fs-4.1.5.tgz
npm http fetch 200 https://registry.npmjs.org/jsonfile/-/jsonfile-2.3.1.tgz
npm http fetch 200 https://registry.npmjs.org/graceful-fs/-/graceful-fs-4.1.5.tgz
npm http fetch 200 https://registry.npmjs.org/rimraf/-/rimraf-2.5.4.tgz
npm http request GET https://registry.npmjs.org/glob
npm http 200 https://registry.npmjs.org/glob
npm http fetch GET https://registry.npmjs.org/glob/-/glob-7.0.5.tgz
npm http fetch 200 https://registry.npmjs.org/glob/-/glob-7.0.5.tgz
npm http request GET https://registry.npmjs.org/fs.realpath
npm http request GET https://registry.npmjs.org/path-is-absolute
npm http request GET https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/once
npm http request GET https://registry.npmjs.org/minimatch
npm http 200 https://registry.npmjs.org/fs.realpath
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http 200 https://registry.npmjs.org/once
npm http 200 https://registry.npmjs.org/inflight
npm http 200 https://registry.npmjs.org/minimatch
npm http fetch GET https://registry.npmjs.org/fs.realpath/-/fs.realpath-1.0.0.tgz
npm http fetch GET https://registry.npmjs.org/inflight/-/inflight-1.0.5.tgz
npm http fetch GET https://registry.npmjs.org/minimatch/-/minimatch-3.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/fs.realpath/-/fs.realpath-1.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/inflight/-/inflight-1.0.5.tgz
npm http fetch 200 https://registry.npmjs.org/minimatch/-/minimatch-3.0.2.tgz
npm http request GET https://registry.npmjs.org/wrappy
npm http 200 https://registry.npmjs.org/wrappy
npm http fetch GET https://registry.npmjs.org/wrappy/-/wrappy-1.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/wrappy/-/wrappy-1.0.2.tgz
npm http request GET https://registry.npmjs.org/brace-expansion
npm http 200 https://registry.npmjs.org/brace-expansion
npm http fetch GET https://registry.npmjs.org/brace-expansion/-/brace-expansion-1.1.6.tgz
npm http fetch 200 https://registry.npmjs.org/brace-expansion/-/brace-expansion-1.1.6.tgz
npm http request GET https://registry.npmjs.org/concat-map
npm http request GET https://registry.npmjs.org/balanced-match
npm http 304 https://registry.npmjs.org/concat-map
npm http 200 https://registry.npmjs.org/balanced-match
npm http fetch GET https://registry.npmjs.org/balanced-match/-/balanced-match-0.4.2.tgz
npm http fetch 200 https://registry.npmjs.org/balanced-match/-/balanced-match-0.4.2.tgz
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 200 https://registry.npmjs.org/es3ify
npm http fetch GET https://registry.npmjs.org/es3ify/-/es3ify-0.2.2.tgz
npm http 200 https://registry.npmjs.org/inline-process-browser
npm http 200 https://registry.npmjs.org/immediate
npm http fetch GET https://registry.npmjs.org/immediate/-/immediate-3.0.6.tgz
npm http fetch 200 https://registry.npmjs.org/es3ify/-/es3ify-0.2.2.tgz
npm http fetch 200 https://registry.npmjs.org/immediate/-/immediate-3.0.6.tgz
npm http 200 https://registry.npmjs.org/unreachable-branch-transform
npm http request GET https://registry.npmjs.org/esprima
npm http request GET https://registry.npmjs.org/through
npm http request GET https://registry.npmjs.org/jstransform
npm http 200 https://registry.npmjs.org/esprima
npm http 304 https://registry.npmjs.org/jstransform
npm http 200 https://registry.npmjs.org/through
npm http fetch GET https://registry.npmjs.org/jstransform/-/jstransform-11.0.3.tgz
npm http fetch 200 https://registry.npmjs.org/jstransform/-/jstransform-11.0.3.tgz
npm http request GET https://registry.npmjs.org/commoner
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/object-assign
npm http request GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 200 https://registry.npmjs.org/base62
npm http 200 https://registry.npmjs.org/object-assign
npm http fetch GET https://registry.npmjs.org/esprima-fb/-/esprima-fb-15001.1.0-dev-harmony-fb.tgz
npm http fetch GET https://registry.npmjs.org/base62/-/base62-1.1.1.tgz
npm http 200 https://registry.npmjs.org/source-map
npm http fetch GET https://registry.npmjs.org/object-assign/-/object-assign-2.1.1.tgz
npm http 200 https://registry.npmjs.org/commoner
npm http fetch GET https://registry.npmjs.org/commoner/-/commoner-0.10.4.tgz
npm http fetch 200 https://registry.npmjs.org/object-assign/-/object-assign-2.1.1.tgz
npm http fetch 200 https://registry.npmjs.org/base62/-/base62-1.1.1.tgz
npm http fetch 200 https://registry.npmjs.org/esprima-fb/-/esprima-fb-15001.1.0-dev-harmony-fb.tgz
npm http fetch 200 https://registry.npmjs.org/commoner/-/commoner-0.10.4.tgz
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/mkdirp
npm http request GET https://registry.npmjs.org/iconv-lite
npm http request GET https://registry.npmjs.org/detective
npm http request GET https://registry.npmjs.org/q
npm http request GET https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/recast
npm http 200 https://registry.npmjs.org/mkdirp
npm http 200 https://registry.npmjs.org/detective
npm http 200 https://registry.npmjs.org/q
npm http 200 https://registry.npmjs.org/commander
npm http 200 https://registry.npmjs.org/iconv-lite
npm http 200 https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/private
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
npm http 200 https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/object-keys
npm http 200 https://registry.npmjs.org/isarray
npm http 200 https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/foreach
npm http fetch GET https://registry.npmjs.org/object-keys/-/object-keys-1.0.11.tgz
npm http fetch 200 https://registry.npmjs.org/object-keys/-/object-keys-1.0.11.tgz
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/xtend
npm http 200 https://registry.npmjs.org/xtend
npm http 200 https://registry.npmjs.org/readable-stream
npm http fetch GET https://registry.npmjs.org/readable-stream/-/readable-stream-1.0.34.tgz
npm http fetch 200 https://registry.npmjs.org/readable-stream/-/readable-stream-1.0.34.tgz
npm http request GET https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/core-util-is
npm http 200 https://registry.npmjs.org/string_decoder
npm http request GET https://registry.npmjs.org/esmangle-evaluator
npm http 200 https://registry.npmjs.org/esmangle-evaluator
npm http fetch GET https://registry.npmjs.org/esmangle-evaluator/-/esmangle-evaluator-1.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/esmangle-evaluator/-/esmangle-evaluator-1.0.1.tgz
npm http request GET https://registry.npmjs.org/has-binary-data
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/socket.io-adapter
npm http request GET https://registry.npmjs.org/engine.io
npm http request GET https://registry.npmjs.org/socket.io-parser
npm http request GET https://registry.npmjs.org/socket.io-client
npm http 200 https://registry.npmjs.org/has-binary-data
npm http 304 https://registry.npmjs.org/debug
npm http fetch GET https://registry.npmjs.org/has-binary-data/-/has-binary-data-0.1.3.tgz
npm http 304 https://registry.npmjs.org/socket.io-parser
npm http 304 https://registry.npmjs.org/socket.io-adapter
npm http fetch GET https://registry.npmjs.org/debug/-/debug-2.1.0.tgz
npm http fetch GET https://registry.npmjs.org/socket.io-parser/-/socket.io-parser-2.2.4.tgz
npm http fetch GET https://registry.npmjs.org/socket.io-adapter/-/socket.io-adapter-0.3.1.tgz
npm http 200 https://registry.npmjs.org/socket.io-client
npm http 200 https://registry.npmjs.org/engine.io
npm http fetch GET https://registry.npmjs.org/socket.io-client/-/socket.io-client-1.3.6.tgz
npm http fetch GET https://registry.npmjs.org/engine.io/-/engine.io-1.5.2.tgz
npm http fetch 200 https://registry.npmjs.org/has-binary-data/-/has-binary-data-0.1.3.tgz
npm http fetch 200 https://registry.npmjs.org/engine.io/-/engine.io-1.5.2.tgz
npm http fetch 200 https://registry.npmjs.org/socket.io-adapter/-/socket.io-adapter-0.3.1.tgz
npm http fetch 200 https://registry.npmjs.org/debug/-/debug-2.1.0.tgz
npm http fetch 200 https://registry.npmjs.org/socket.io-parser/-/socket.io-parser-2.2.4.tgz
npm http fetch 200 https://registry.npmjs.org/socket.io-client/-/socket.io-client-1.3.6.tgz
npm http request GET https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/base64id
npm http request GET https://registry.npmjs.org/engine.io-parser
npm http request GET https://registry.npmjs.org/ws
npm http fetch GET https://registry.npmjs.org/debug/-/debug-1.0.3.tgz
npm http 304 https://registry.npmjs.org/base64id
npm http 304 https://registry.npmjs.org/engine.io-parser
npm http 200 https://registry.npmjs.org/ws
npm http fetch 200 https://registry.npmjs.org/debug/-/debug-1.0.3.tgz
npm http fetch GET https://registry.npmjs.org/engine.io-parser/-/engine.io-parser-1.2.1.tgz
npm http fetch GET https://registry.npmjs.org/ws/-/ws-0.7.2.tgz
npm http fetch 200 https://registry.npmjs.org/engine.io-parser/-/engine.io-parser-1.2.1.tgz
npm http fetch 200 https://registry.npmjs.org/ws/-/ws-0.7.2.tgz
npm http request GET https://registry.npmjs.org/arraybuffer.slice
npm http request GET https://registry.npmjs.org/after
npm http request GET https://registry.npmjs.org/base64-arraybuffer
npm http request GET https://registry.npmjs.org/blob
npm http request GET https://registry.npmjs.org/has-binary
npm http request GET https://registry.npmjs.org/utf8
npm http 304 https://registry.npmjs.org/base64-arraybuffer
npm http 200 https://registry.npmjs.org/blob
npm http 304 https://registry.npmjs.org/arraybuffer.slice
npm http 304 https://registry.npmjs.org/has-binary
npm http 200 https://registry.npmjs.org/after
npm http fetch GET https://registry.npmjs.org/blob/-/blob-0.0.2.tgz
npm http fetch GET https://registry.npmjs.org/has-binary/-/has-binary-0.1.5.tgz
npm http 304 https://registry.npmjs.org/utf8
npm http fetch GET https://registry.npmjs.org/utf8/-/utf8-2.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/utf8/-/utf8-2.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/has-binary/-/has-binary-0.1.5.tgz
npm http fetch 200 https://registry.npmjs.org/blob/-/blob-0.0.2.tgz
npm http request GET https://registry.npmjs.org/bufferutil
npm http request GET https://registry.npmjs.org/utf-8-validate
npm http request GET https://registry.npmjs.org/options
npm http request GET https://registry.npmjs.org/ultron
npm http 304 https://registry.npmjs.org/options
npm http 200 https://registry.npmjs.org/ultron
npm http 200 https://registry.npmjs.org/bufferutil
npm http fetch GET https://registry.npmjs.org/bufferutil/-/bufferutil-1.1.0.tgz
npm http 200 https://registry.npmjs.org/utf-8-validate
npm http fetch GET https://registry.npmjs.org/utf-8-validate/-/utf-8-validate-1.1.0.tgz
npm http fetch 200 https://registry.npmjs.org/bufferutil/-/bufferutil-1.1.0.tgz
npm http fetch 200 https://registry.npmjs.org/utf-8-validate/-/utf-8-validate-1.1.0.tgz
npm http request GET https://registry.npmjs.org/bindings
npm http request GET https://registry.npmjs.org/nan
npm http 200 https://registry.npmjs.org/nan
npm http fetch GET https://registry.npmjs.org/nan/-/nan-1.8.4.tgz
npm http 200 https://registry.npmjs.org/bindings
npm http fetch 200 https://registry.npmjs.org/nan/-/nan-1.8.4.tgz
npm http fetch GET https://registry.npmjs.org/debug/-/debug-1.0.2.tgz
npm http fetch GET https://registry.npmjs.org/object-keys/-/object-keys-1.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/debug/-/debug-1.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/object-keys/-/object-keys-1.0.1.tgz
npm http request GET https://registry.npmjs.org/component-emitter
npm http request GET https://registry.npmjs.org/benchmark
npm http request GET https://registry.npmjs.org/json3
npm http 200 https://registry.npmjs.org/component-emitter
npm http 200 https://registry.npmjs.org/benchmark
npm http 304 https://registry.npmjs.org/json3
npm http request GET https://registry.npmjs.org/backo2
npm http request GET https://registry.npmjs.org/to-array
npm http request GET https://registry.npmjs.org/parseuri
npm http request GET https://registry.npmjs.org/object-component
npm http request GET https://registry.npmjs.org/indexof
npm http request GET https://registry.npmjs.org/component-bind
npm http request GET https://registry.npmjs.org/engine.io-client
npm http 304 https://registry.npmjs.org/backo2
npm http 304 https://registry.npmjs.org/to-array
npm http 304 https://registry.npmjs.org/parseuri
npm http 304 https://registry.npmjs.org/object-component
npm http 200 https://registry.npmjs.org/indexof
npm http fetch GET https://registry.npmjs.org/to-array/-/to-array-0.1.3.tgz
npm http 304 https://registry.npmjs.org/component-bind
npm http fetch GET https://registry.npmjs.org/parseuri/-/parseuri-0.0.2.tgz
npm http 200 https://registry.npmjs.org/engine.io-client
npm http fetch GET https://registry.npmjs.org/engine.io-client/-/engine.io-client-1.5.2.tgz
npm http fetch 200 https://registry.npmjs.org/to-array/-/to-array-0.1.3.tgz
npm http fetch 200 https://registry.npmjs.org/parseuri/-/parseuri-0.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/engine.io-client/-/engine.io-client-1.5.2.tgz
npm http request GET https://registry.npmjs.org/component-inherit
npm http request GET https://registry.npmjs.org/parsejson
npm http request GET https://registry.npmjs.org/parseqs
npm http request GET https://registry.npmjs.org/has-cors
npm http fetch GET https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http 304 https://registry.npmjs.org/parseqs
npm http 304 https://registry.npmjs.org/has-cors
npm http 304 https://registry.npmjs.org/component-inherit
npm http 304 https://registry.npmjs.org/parsejson
npm http fetch GET https://registry.npmjs.org/has-cors/-/has-cors-1.0.3.tgz
npm http fetch 200 https://registry.npmjs.org/has-cors/-/has-cors-1.0.3.tgz
npm http fetch 200 https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http fetch GET https://github.com/component/global/archive/v2.0.1.tar.gz
npm http fetch 200 https://github.com/component/global/archive/v2.0.1.tar.gz
npm http request GET https://registry.npmjs.org/better-assert
npm http 200 https://registry.npmjs.org/better-assert
npm http request GET https://registry.npmjs.org/callsite
npm http 200 https://registry.npmjs.org/callsite
npm http request GET https://registry.npmjs.org/isstream
npm http request GET https://registry.npmjs.org/eyes
npm http request GET https://registry.npmjs.org/cycle
npm http request GET https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/colors
npm http request GET https://registry.npmjs.org/pkginfo
npm http request GET https://registry.npmjs.org/stack-trace
npm http 200 https://registry.npmjs.org/eyes
npm http 200 https://registry.npmjs.org/colors
npm http 200 https://registry.npmjs.org/cycle
npm http 200 https://registry.npmjs.org/isstream
npm http 200 https://registry.npmjs.org/pkginfo
npm http 200 https://registry.npmjs.org/stack-trace
npm http 200 https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/node-uuid
npm http request GET https://registry.npmjs.org/tape
npm http 200 https://registry.npmjs.org/node-uuid
npm http 200 https://registry.npmjs.org/tape
npm http request GET https://registry.npmjs.org/defined
npm http request GET https://registry.npmjs.org/jsonify
npm http request GET https://registry.npmjs.org/deep-equal
npm http 200 https://registry.npmjs.org/defined
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
npm http request GET https://registry.npmjs.org/forever-agent
npm http request GET https://registry.npmjs.org/body-parser
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/ip
npm http request GET https://registry.npmjs.org/javascript-state-machine
npm http request GET https://registry.npmjs.org/node-uuid
npm http request GET https://registry.npmjs.org/long
npm http request GET https://registry.npmjs.org/multiplex
npm http request GET https://registry.npmjs.org/winston
npm http request GET https://registry.npmjs.org/urlsafe-base64
npm http request GET https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/forever-agent
npm http 304 https://registry.npmjs.org/express
npm http 200 https://registry.npmjs.org/node-uuid
npm http 200 https://registry.npmjs.org/body-parser
npm http 200 https://registry.npmjs.org/long
npm http 304 https://registry.npmjs.org/winston
npm http fetch GET https://registry.npmjs.org/body-parser/-/body-parser-1.13.3.tgz
npm http 304 https://registry.npmjs.org/urlsafe-base64
npm http 200 https://registry.npmjs.org/salti
npm http fetch GET https://registry.npmjs.org/salti/-/salti-0.2.0.tgz
npm http fetch 200 https://registry.npmjs.org/body-parser/-/body-parser-1.13.3.tgz
npm http 200 https://registry.npmjs.org/javascript-state-machine
npm http 200 https://registry.npmjs.org/ip
npm http fetch GET https://registry.npmjs.org/ip/-/ip-1.0.1.tgz
npm http 304 https://registry.npmjs.org/multiplex
npm http fetch 200 https://registry.npmjs.org/salti/-/salti-0.2.0.tgz
npm http 200 https://registry.npmjs.org/request
npm http fetch GET https://registry.npmjs.org/request/-/request-2.64.0.tgz
npm http fetch 200 https://registry.npmjs.org/ip/-/ip-1.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/request/-/request-2.64.0.tgz
npm http request GET https://registry.npmjs.org/content-type
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/depd
npm http request GET https://registry.npmjs.org/http-errors
npm http request GET https://registry.npmjs.org/on-finished
npm http request GET https://registry.npmjs.org/iconv-lite
npm http request GET https://registry.npmjs.org/bytes
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/type-is
npm http request GET https://registry.npmjs.org/raw-body
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/on-finished
npm http 304 https://registry.npmjs.org/content-type
npm http 200 https://registry.npmjs.org/http-errors
npm http 200 https://registry.npmjs.org/depd
npm http 304 https://registry.npmjs.org/iconv-lite
npm http 304 https://registry.npmjs.org/qs
npm http 200 https://registry.npmjs.org/bytes
npm http 304 https://registry.npmjs.org/type-is
npm http 200 https://registry.npmjs.org/raw-body
npm http fetch GET https://registry.npmjs.org/iconv-lite/-/iconv-lite-0.4.11.tgz
npm http fetch GET https://registry.npmjs.org/bytes/-/bytes-2.1.0.tgz
npm http fetch GET https://registry.npmjs.org/raw-body/-/raw-body-2.1.7.tgz
npm http fetch 200 https://registry.npmjs.org/bytes/-/bytes-2.1.0.tgz
npm http fetch 200 https://registry.npmjs.org/iconv-lite/-/iconv-lite-0.4.11.tgz
npm http fetch 200 https://registry.npmjs.org/raw-body/-/raw-body-2.1.7.tgz
npm http request GET https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/inherits
npm http request GET https://registry.npmjs.org/statuses
npm http 304 https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/statuses
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
npm http 304 https://registry.npmjs.org/cookie-signature
npm http 304 https://registry.npmjs.org/array-flatten
npm http 304 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/cookie
npm http 304 https://registry.npmjs.org/content-disposition
npm http 304 https://registry.npmjs.org/escape-html
npm http 304 https://registry.npmjs.org/finalhandler
npm http 200 https://registry.npmjs.org/etag
npm http 304 https://registry.npmjs.org/fresh
npm http 304 https://registry.npmjs.org/merge-descriptors
npm http 304 https://registry.npmjs.org/methods
npm http 304 https://registry.npmjs.org/parseurl
npm http 304 https://registry.npmjs.org/path-to-regexp
npm http 304 https://registry.npmjs.org/proxy-addr
npm http 304 https://registry.npmjs.org/range-parser
npm http 304 https://registry.npmjs.org/send
npm http 200 https://registry.npmjs.org/utils-merge
npm http 304 https://registry.npmjs.org/vary
npm http 304 https://registry.npmjs.org/serve-static
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
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/immediate
npm http 304 https://registry.npmjs.org/inline-process-browser
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/esprima
npm http request GET https://registry.npmjs.org/jstransform
npm http request GET https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/esprima
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/commoner
npm http request GET https://registry.npmjs.org/object-assign
npm http request GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/object-assign
npm http 200 https://registry.npmjs.org/base62
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 304 https://registry.npmjs.org/commoner
npm http 200 https://registry.npmjs.org/source-map
npm http request GET https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/detective
npm http request GET https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/mkdirp
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/q
npm http request GET https://registry.npmjs.org/recast
npm http 200 https://registry.npmjs.org/detective
npm http 304 https://registry.npmjs.org/mkdirp
npm http 200 https://registry.npmjs.org/graceful-fs
npm http 304 https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/commander
npm http 304 https://registry.npmjs.org/q
npm http 200 https://registry.npmjs.org/private
npm http 200 https://registry.npmjs.org/recast
npm http request GET https://registry.npmjs.org/graceful-readlink
npm http 304 https://registry.npmjs.org/graceful-readlink
npm http request GET https://registry.npmjs.org/acorn
npm http request GET https://registry.npmjs.org/defined
npm http 304 https://registry.npmjs.org/acorn
npm http 304 https://registry.npmjs.org/defined
npm http request GET https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/once
npm http request GET https://registry.npmjs.org/path-is-absolute
npm http 304 https://registry.npmjs.org/inflight
npm http 304 https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/minimatch
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http request GET https://registry.npmjs.org/wrappy
npm http 304 https://registry.npmjs.org/wrappy
npm http request GET https://registry.npmjs.org/brace-expansion
npm http 304 https://registry.npmjs.org/brace-expansion
npm http request GET https://registry.npmjs.org/balanced-match
npm http request GET https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/balanced-match
npm http request GET https://registry.npmjs.org/minimist
npm http 304 https://registry.npmjs.org/minimist
npm http request GET https://registry.npmjs.org/ast-types
npm http 200 https://registry.npmjs.org/ast-types
npm http request GET https://registry.npmjs.org/amdefine
npm http 304 https://registry.npmjs.org/amdefine
npm http request GET https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/falafel
npm http 304 https://registry.npmjs.org/through2
npm http request GET https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/object-keys
npm http 200 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/foreach
npm http 304 https://registry.npmjs.org/object-keys
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/string_decoder
npm http 200 https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/esmangle-evaluator
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/duplexify
npm http request GET https://registry.npmjs.org/varint
npm http fetch GET https://registry.npmjs.org/readable-stream/-/readable-stream-2.1.4.tgz
npm http fetch 200 https://registry.npmjs.org/readable-stream/-/readable-stream-2.1.4.tgz
npm http 200 https://registry.npmjs.org/duplexify
npm http fetch GET https://registry.npmjs.org/duplexify/-/duplexify-3.4.5.tgz
npm http fetch 200 https://registry.npmjs.org/duplexify/-/duplexify-3.4.5.tgz
npm http 200 https://registry.npmjs.org/varint
npm http fetch GET https://registry.npmjs.org/varint/-/varint-4.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/varint/-/varint-4.0.1.tgz
npm http request GET https://registry.npmjs.org/stream-shift
npm http request GET https://registry.npmjs.org/end-of-stream
npm http 200 https://registry.npmjs.org/stream-shift
npm http 304 https://registry.npmjs.org/end-of-stream
npm http fetch GET https://registry.npmjs.org/stream-shift/-/stream-shift-1.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/stream-shift/-/stream-shift-1.0.0.tgz
npm http request GET https://registry.npmjs.org/buffer-shims
npm http request GET https://registry.npmjs.org/process-nextick-args
npm http request GET https://registry.npmjs.org/util-deprecate
npm http 304 https://registry.npmjs.org/util-deprecate
npm http 200 https://registry.npmjs.org/buffer-shims
npm http 200 https://registry.npmjs.org/process-nextick-args
npm http fetch GET https://registry.npmjs.org/buffer-shims/-/buffer-shims-1.0.0.tgz
npm http fetch GET https://registry.npmjs.org/process-nextick-args/-/process-nextick-args-1.0.7.tgz
npm http fetch 200 https://registry.npmjs.org/process-nextick-args/-/process-nextick-args-1.0.7.tgz
npm http fetch 200 https://registry.npmjs.org/buffer-shims/-/buffer-shims-1.0.0.tgz
npm http request GET https://registry.npmjs.org/bl
npm http request GET https://registry.npmjs.org/caseless
npm http request GET https://registry.npmjs.org/tunnel-agent
npm http request GET https://registry.npmjs.org/json-stringify-safe
npm http request GET https://registry.npmjs.org/form-data
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/http-signature
npm http request GET https://registry.npmjs.org/tough-cookie
npm http request GET https://registry.npmjs.org/oauth-sign
npm http request GET https://registry.npmjs.org/stringstream
npm http request GET https://registry.npmjs.org/aws-sign2
npm http request GET https://registry.npmjs.org/hawk
npm http request GET https://registry.npmjs.org/combined-stream
npm http request GET https://registry.npmjs.org/isstream
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/har-validator
npm http 304 https://registry.npmjs.org/caseless
npm http 200 https://registry.npmjs.org/tunnel-agent
npm http 200 https://registry.npmjs.org/json-stringify-safe
npm http 200 https://registry.npmjs.org/form-data
npm http fetch GET https://registry.npmjs.org/tunnel-agent/-/tunnel-agent-0.4.3.tgz
npm http 200 https://registry.npmjs.org/extend
npm http 200 https://registry.npmjs.org/http-signature
npm http 200 https://registry.npmjs.org/oauth-sign
npm http 200 https://registry.npmjs.org/tough-cookie
npm http fetch GET https://registry.npmjs.org/http-signature/-/http-signature-0.11.0.tgz
npm http fetch GET https://registry.npmjs.org/oauth-sign/-/oauth-sign-0.8.2.tgz
npm http fetch GET https://registry.npmjs.org/tough-cookie/-/tough-cookie-2.3.1.tgz
npm http 304 https://registry.npmjs.org/aws-sign2
npm http 304 https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/qs
npm http 200 https://registry.npmjs.org/isstream
npm http 200 https://registry.npmjs.org/hawk
npm http fetch GET https://registry.npmjs.org/qs/-/qs-5.1.0.tgz
npm http fetch 200 https://registry.npmjs.org/tunnel-agent/-/tunnel-agent-0.4.3.tgz
npm http fetch 200 https://registry.npmjs.org/http-signature/-/http-signature-0.11.0.tgz
npm http 200 https://registry.npmjs.org/har-validator
npm http fetch GET https://registry.npmjs.org/har-validator/-/har-validator-1.8.0.tgz
npm http fetch 200 https://registry.npmjs.org/oauth-sign/-/oauth-sign-0.8.2.tgz
npm http fetch 200 https://registry.npmjs.org/tough-cookie/-/tough-cookie-2.3.1.tgz
npm http fetch 200 https://registry.npmjs.org/qs/-/qs-5.1.0.tgz
npm http fetch 200 https://registry.npmjs.org/har-validator/-/har-validator-1.8.0.tgz
npm http 304 https://registry.npmjs.org/stringstream
npm http 200 https://registry.npmjs.org/bl
npm http request GET https://registry.npmjs.org/delayed-stream
npm http 304 https://registry.npmjs.org/delayed-stream
npm http request GET https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/chalk
npm http request GET https://registry.npmjs.org/is-my-json-valid
npm http 200 https://registry.npmjs.org/is-my-json-valid
npm http 200 https://registry.npmjs.org/chalk
npm http 304 https://registry.npmjs.org/bluebird
npm http fetch GET https://registry.npmjs.org/chalk/-/chalk-1.1.3.tgz
npm http fetch 200 https://registry.npmjs.org/chalk/-/chalk-1.1.3.tgz
npm http request GET https://registry.npmjs.org/has-ansi
npm http request GET https://registry.npmjs.org/escape-string-regexp
npm http request GET https://registry.npmjs.org/ansi-styles
npm http request GET https://registry.npmjs.org/strip-ansi
npm http request GET https://registry.npmjs.org/supports-color
npm http 200 https://registry.npmjs.org/has-ansi
npm http 200 https://registry.npmjs.org/supports-color
npm http 200 https://registry.npmjs.org/escape-string-regexp
npm http 200 https://registry.npmjs.org/ansi-styles
npm http 200 https://registry.npmjs.org/strip-ansi
npm http fetch GET https://registry.npmjs.org/ansi-styles/-/ansi-styles-2.2.1.tgz
npm http fetch 200 https://registry.npmjs.org/ansi-styles/-/ansi-styles-2.2.1.tgz
npm http request GET https://registry.npmjs.org/ansi-regex
npm http 200 https://registry.npmjs.org/ansi-regex
npm http request GET https://registry.npmjs.org/generate-object-property
npm http request GET https://registry.npmjs.org/generate-function
npm http request GET https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/generate-object-property
npm http 200 https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/generate-function
npm http request GET https://registry.npmjs.org/is-property
npm http 304 https://registry.npmjs.org/is-property
npm http request GET https://registry.npmjs.org/hoek
npm http request GET https://registry.npmjs.org/cryptiles
npm http request GET https://registry.npmjs.org/sntp
npm http request GET https://registry.npmjs.org/boom
npm http 200 https://registry.npmjs.org/cryptiles
npm http 200 https://registry.npmjs.org/sntp
npm http 200 https://registry.npmjs.org/boom
npm http 200 https://registry.npmjs.org/hoek
npm http request GET https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/asn1
npm http request GET https://registry.npmjs.org/ctype
npm http 304 https://registry.npmjs.org/ctype
npm http 200 https://registry.npmjs.org/asn1
npm http 200 https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/colors
npm http request GET https://registry.npmjs.org/cycle
npm http request GET https://registry.npmjs.org/eyes
npm http request GET https://registry.npmjs.org/pkginfo
npm http request GET https://registry.npmjs.org/stack-trace
npm http 200 https://registry.npmjs.org/cycle
npm http 200 https://registry.npmjs.org/colors
npm http 304 https://registry.npmjs.org/stack-trace
npm http 304 https://registry.npmjs.org/pkginfo
npm http 200 https://registry.npmjs.org/eyes
npm http request GET https://registry.npmjs.org/jsdoc
npm http 200 https://registry.npmjs.org/jsdoc
npm http fetch GET https://registry.npmjs.org/jsdoc/-/jsdoc-3.3.3.tgz
npm http fetch 200 https://registry.npmjs.org/jsdoc/-/jsdoc-3.3.3.tgz
npm http request GET https://registry.npmjs.org/catharsis
npm http request GET https://registry.npmjs.org/js2xmlparser
npm http request GET https://registry.npmjs.org/marked
npm http request GET https://registry.npmjs.org/strip-json-comments
npm http request GET https://registry.npmjs.org/underscore
npm http request GET https://registry.npmjs.org/requizzle
npm http request GET https://registry.npmjs.org/wrench
npm http request GET https://registry.npmjs.org/esprima
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 200 https://registry.npmjs.org/underscore
npm http 200 https://registry.npmjs.org/strip-json-comments
npm http 200 https://registry.npmjs.org/marked
npm http 304 https://registry.npmjs.org/esprima
npm http 200 https://registry.npmjs.org/wrench
npm http fetch GET https://registry.npmjs.org/esprima/-/esprima-1.2.5.tgz
npm WARN deprecated wrench@1.5.9: wrench.js is deprecated! You should check out fs-extra (https://github.com/jprichardson/node-fs-extra) for any operations you were using wrench for. Thanks for all the usage over the years.
npm http fetch GET https://registry.npmjs.org/wrench/-/wrench-1.5.9.tgz
npm http fetch 200 https://registry.npmjs.org/esprima/-/esprima-1.2.5.tgz
npm http fetch 200 https://registry.npmjs.org/wrench/-/wrench-1.5.9.tgz
npm http 200 https://registry.npmjs.org/catharsis
npm http fetch GET https://registry.npmjs.org/catharsis/-/catharsis-0.8.8.tgz
npm http 200 https://registry.npmjs.org/js2xmlparser
npm http fetch GET https://registry.npmjs.org/js2xmlparser/-/js2xmlparser-0.1.9.tgz
npm http fetch 200 https://registry.npmjs.org/catharsis/-/catharsis-0.8.8.tgz
npm http fetch 200 https://registry.npmjs.org/js2xmlparser/-/js2xmlparser-0.1.9.tgz
npm http 304 https://registry.npmjs.org/requizzle
npm http fetch 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http request GET https://registry.npmjs.org/underscore-contrib
npm http 304 https://registry.npmjs.org/underscore-contrib
npm WARN prefer global marked@0.3.5 should be installed with -g
npm http request GET https://registry.npmjs.org/fs-extra-promise
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/request
npm http request GET https://registry.npmjs.org/jxc
npm http request GET https://registry.npmjs.org/unzip
npm http 304 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/fs-extra-promise
npm http 200 https://registry.npmjs.org/unzip
npm http 200 https://registry.npmjs.org/jxc
npm http request GET https://registry.npmjs.org/fs-extra
npm http request GET https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/fs-extra
npm http 304 https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/jsonfile
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/jsonfile
npm http 200 https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/fs.realpath
npm http request GET https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/inherits
npm http request GET https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/once
npm http request GET https://registry.npmjs.org/path-is-absolute
npm http 304 https://registry.npmjs.org/inflight
npm http 304 https://registry.npmjs.org/once
npm http 200 https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/minimatch
npm http 304 https://registry.npmjs.org/fs.realpath
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http request GET https://registry.npmjs.org/wrappy
npm http 304 https://registry.npmjs.org/wrappy
npm http request GET https://registry.npmjs.org/brace-expansion
npm http 304 https://registry.npmjs.org/brace-expansion
npm http request GET https://registry.npmjs.org/balanced-match
npm http request GET https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/balanced-match
npm http request GET https://registry.npmjs.org/adm-zip
npm http request GET https://registry.npmjs.org/progress
npm http 200 https://registry.npmjs.org/adm-zip
npm http 200 https://registry.npmjs.org/progress
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/es3ify
npm http 304 https://registry.npmjs.org/immediate
npm http 304 https://registry.npmjs.org/inline-process-browser
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http request GET https://registry.npmjs.org/esprima
npm http request GET https://registry.npmjs.org/jstransform
npm http request GET https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/esprima
npm http 304 https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/through
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/commoner
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/object-assign
npm http request GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/object-assign
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 304 https://registry.npmjs.org/commoner
npm http 200 https://registry.npmjs.org/source-map
npm http 200 https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/detective
npm http request GET https://registry.npmjs.org/iconv-lite
npm http request GET https://registry.npmjs.org/mkdirp
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/q
npm http request GET https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/mkdirp
npm http 200 https://registry.npmjs.org/detective
npm http 200 https://registry.npmjs.org/private
npm http 304 https://registry.npmjs.org/iconv-lite
npm http 304 https://registry.npmjs.org/commander
npm http 304 https://registry.npmjs.org/q
npm http 200 https://registry.npmjs.org/recast
npm http request GET https://registry.npmjs.org/graceful-readlink
npm http 304 https://registry.npmjs.org/graceful-readlink
npm http request GET https://registry.npmjs.org/acorn
npm http request GET https://registry.npmjs.org/defined
npm http 200 https://registry.npmjs.org/defined
npm http 304 https://registry.npmjs.org/acorn
npm http request GET https://registry.npmjs.org/minimist
npm http 304 https://registry.npmjs.org/minimist
npm http request GET https://registry.npmjs.org/ast-types
npm http 200 https://registry.npmjs.org/ast-types
npm http request GET https://registry.npmjs.org/amdefine
npm http 304 https://registry.npmjs.org/amdefine
npm http request GET https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/falafel
npm http 304 https://registry.npmjs.org/through2
npm http request GET https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/object-keys
npm http 200 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/string_decoder
npm http request GET https://registry.npmjs.org/core-util-is
npm http 304 https://registry.npmjs.org/core-util-is
npm http 200 https://registry.npmjs.org/string_decoder
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
npm http 200 https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/forever-agent
npm http 304 https://registry.npmjs.org/extend
npm http 200 https://registry.npmjs.org/caseless
npm http 200 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/json-stringify-safe
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/tunnel-agent
npm http 200 https://registry.npmjs.org/node-uuid
npm http 200 https://registry.npmjs.org/mime-types
npm http 304 https://registry.npmjs.org/tough-cookie
npm http 304 https://registry.npmjs.org/http-signature
npm http 304 https://registry.npmjs.org/oauth-sign
npm http 304 https://registry.npmjs.org/hawk
npm http 200 https://registry.npmjs.org/aws-sign2
npm http 304 https://registry.npmjs.org/stringstream
npm http 304 https://registry.npmjs.org/combined-stream
npm http 200 https://registry.npmjs.org/isstream
npm http 200 https://registry.npmjs.org/har-validator
npm http request GET https://registry.npmjs.org/process-nextick-args
npm http request GET https://registry.npmjs.org/util-deprecate
npm http 200 https://registry.npmjs.org/util-deprecate
npm http 200 https://registry.npmjs.org/process-nextick-args
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
npm http 304 https://registry.npmjs.org/ansi-styles
npm http 304 https://registry.npmjs.org/strip-ansi
npm http 304 https://registry.npmjs.org/escape-string-regexp
npm http 304 https://registry.npmjs.org/supports-color
npm http 304 https://registry.npmjs.org/has-ansi
npm http request GET https://registry.npmjs.org/ansi-regex
npm http 304 https://registry.npmjs.org/ansi-regex
npm http request GET https://registry.npmjs.org/generate-function
npm http request GET https://registry.npmjs.org/generate-object-property
npm http request GET https://registry.npmjs.org/jsonpointer
npm http 200 https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/generate-function
npm http 304 https://registry.npmjs.org/generate-object-property
npm http request GET https://registry.npmjs.org/is-property
npm http 304 https://registry.npmjs.org/is-property
npm http request GET https://registry.npmjs.org/hoek
npm http request GET https://registry.npmjs.org/boom
npm http request GET https://registry.npmjs.org/cryptiles
npm http request GET https://registry.npmjs.org/sntp
npm http 304 https://registry.npmjs.org/hoek
npm http 304 https://registry.npmjs.org/cryptiles
npm http 304 https://registry.npmjs.org/sntp
npm http 304 https://registry.npmjs.org/boom
npm http request GET https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/asn1
npm http request GET https://registry.npmjs.org/ctype
npm http 304 https://registry.npmjs.org/asn1
npm http 304 https://registry.npmjs.org/assert-plus
npm http 304 https://registry.npmjs.org/ctype
npm http request GET https://registry.npmjs.org/fstream
npm http request GET https://registry.npmjs.org/setimmediate
npm http request GET https://registry.npmjs.org/binary
npm http request GET https://registry.npmjs.org/pullstream
npm http request GET https://registry.npmjs.org/match-stream
npm http 200 https://registry.npmjs.org/fstream
npm http 304 https://registry.npmjs.org/binary
npm http 304 https://registry.npmjs.org/pullstream
npm http 304 https://registry.npmjs.org/match-stream
npm http 200 https://registry.npmjs.org/setimmediate
npm http request GET https://registry.npmjs.org/chainsaw
npm http request GET https://registry.npmjs.org/buffers
npm http 304 https://registry.npmjs.org/chainsaw
npm http 304 https://registry.npmjs.org/buffers
npm http request GET https://registry.npmjs.org/traverse
npm http 200 https://registry.npmjs.org/traverse
npm http request GET https://registry.npmjs.org/graceful-fs
npm http 200 https://registry.npmjs.org/graceful-fs
npm WARN deprecated graceful-fs@3.0.8: graceful-fs v3.0.0 and before will fail on node releases >= v7.0. Please update to graceful-fs@^4.0.0 as soon as possible. Use 'npm ls graceful-fs' to find it in the tree.
npm http request GET https://registry.npmjs.org/over
npm http request GET https://registry.npmjs.org/slice-stream
npm http 304 https://registry.npmjs.org/slice-stream
npm http 304 https://registry.npmjs.org/over
npm WARN EPACKAGEJSON install@0.0.1 No repository field.

```

Error: Command failed: npm http request GET https://registry.npmjs.org/fs-extra-promise
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/socket.io
npm http request GET https://registry.npmjs.org/winston
npm http request GET https://registry.npmjs.org/express
npm http 200 https://registry.npmjs.org/winston
npm http 200 https://registry.npmjs.org/socket.io
npm http fetch GET https://registry.npmjs.org/socket.io/-/socket.io-1.3.6.tgz
npm http 200 https://registry.npmjs.org/express
npm http fetch 200 https://registry.npmjs.org/socket.io/-/socket.io-1.3.6.tgz
npm http 200 https://registry.npmjs.org/lie
npm http fetch GET https://registry.npmjs.org/lie/-/lie-3.0.4.tgz
npm http 200 https://registry.npmjs.org/fs-extra-promise
npm http fetch GET https://registry.npmjs.org/fs-extra-promise/-/fs-extra-promise-0.2.0.tgz
npm http fetch 200 https://registry.npmjs.org/lie/-/lie-3.0.4.tgz
npm http fetch 200 https://registry.npmjs.org/fs-extra-promise/-/fs-extra-promise-0.2.0.tgz
npm http request GET https://registry.npmjs.org/array-flatten
npm http request GET https://registry.npmjs.org/accepts
npm http request GET https://registry.npmjs.org/etag
npm http request GET https://registry.npmjs.org/depd
npm http request GET https://registry.npmjs.org/escape-html
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/cookie
npm http request GET https://registry.npmjs.org/cookie-signature
npm http request GET https://registry.npmjs.org/content-type
npm http request GET https://registry.npmjs.org/content-disposition
npm http request GET https://registry.npmjs.org/proxy-addr
npm http request GET https://registry.npmjs.org/parseurl
npm http request GET https://registry.npmjs.org/on-finished
npm http request GET https://registry.npmjs.org/path-to-regexp
npm http request GET https://registry.npmjs.org/merge-descriptors
npm http request GET https://registry.npmjs.org/methods
npm http request GET https://registry.npmjs.org/fresh
npm http request GET https://registry.npmjs.org/finalhandler
npm http request GET https://registry.npmjs.org/range-parser
npm http request GET https://registry.npmjs.org/send
npm http request GET https://registry.npmjs.org/utils-merge
npm http request GET https://registry.npmjs.org/type-is
npm http request GET https://registry.npmjs.org/serve-static
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/vary
npm http 200 https://registry.npmjs.org/etag
npm http 200 https://registry.npmjs.org/escape-html
npm http 200 https://registry.npmjs.org/array-flatten
npm http 200 https://registry.npmjs.org/depd
npm http 200 https://registry.npmjs.org/accepts
npm http 200 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/content-disposition
npm http 200 https://registry.npmjs.org/cookie
npm http 200 https://registry.npmjs.org/cookie-signature
npm http 200 https://registry.npmjs.org/content-type
npm http 200 https://registry.npmjs.org/proxy-addr
npm http 200 https://registry.npmjs.org/parseurl
npm http 304 https://registry.npmjs.org/on-finished
npm http 304 https://registry.npmjs.org/fresh
npm http 200 https://registry.npmjs.org/methods
npm http 200 https://registry.npmjs.org/merge-descriptors
npm http 200 https://registry.npmjs.org/path-to-regexp
npm http fetch GET https://registry.npmjs.org/content-type/-/content-type-1.0.2.tgz
npm http 200 https://registry.npmjs.org/finalhandler
npm http 200 https://registry.npmjs.org/range-parser
npm http 200 https://registry.npmjs.org/utils-merge
npm http 200 https://registry.npmjs.org/type-is
npm http 200 https://registry.npmjs.org/send
npm http 304 https://registry.npmjs.org/vary
npm http fetch 200 https://registry.npmjs.org/content-type/-/content-type-1.0.2.tgz
npm http 200 https://registry.npmjs.org/serve-static
npm http 200 https://registry.npmjs.org/qs
npm http fetch GET https://registry.npmjs.org/type-is/-/type-is-1.6.13.tgz
npm http fetch GET https://registry.npmjs.org/serve-static/-/serve-static-1.10.3.tgz
npm http fetch 200 https://registry.npmjs.org/type-is/-/type-is-1.6.13.tgz
npm http fetch 200 https://registry.npmjs.org/serve-static/-/serve-static-1.10.3.tgz
npm http request GET https://registry.npmjs.org/negotiator
npm http request GET https://registry.npmjs.org/mime-types
npm http 200 https://registry.npmjs.org/negotiator
npm http 200 https://registry.npmjs.org/mime-types
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
npm http request GET https://registry.npmjs.org/mime
npm http request GET https://registry.npmjs.org/statuses
npm http request GET https://registry.npmjs.org/destroy
npm http request GET https://registry.npmjs.org/http-errors
npm http 200 https://registry.npmjs.org/mime
npm http 200 https://registry.npmjs.org/statuses
npm http 200 https://registry.npmjs.org/http-errors
npm http 304 https://registry.npmjs.org/destroy
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
npm http fetch GET https://registry.npmjs.org/jsonfile/-/jsonfile-2.3.1.tgz
npm http 200 https://registry.npmjs.org/graceful-fs
npm http fetch GET https://registry.npmjs.org/rimraf/-/rimraf-2.5.4.tgz
npm http fetch GET https://registry.npmjs.org/graceful-fs/-/graceful-fs-4.1.5.tgz
npm http fetch 200 https://registry.npmjs.org/jsonfile/-/jsonfile-2.3.1.tgz
npm http fetch 200 https://registry.npmjs.org/graceful-fs/-/graceful-fs-4.1.5.tgz
npm http fetch 200 https://registry.npmjs.org/rimraf/-/rimraf-2.5.4.tgz
npm http request GET https://registry.npmjs.org/glob
npm http 200 https://registry.npmjs.org/glob
npm http fetch GET https://registry.npmjs.org/glob/-/glob-7.0.5.tgz
npm http fetch 200 https://registry.npmjs.org/glob/-/glob-7.0.5.tgz
npm http request GET https://registry.npmjs.org/fs.realpath
npm http request GET https://registry.npmjs.org/path-is-absolute
npm http request GET https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/once
npm http request GET https://registry.npmjs.org/minimatch
npm http 200 https://registry.npmjs.org/fs.realpath
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http 200 https://registry.npmjs.org/once
npm http 200 https://registry.npmjs.org/inflight
npm http 200 https://registry.npmjs.org/minimatch
npm http fetch GET https://registry.npmjs.org/fs.realpath/-/fs.realpath-1.0.0.tgz
npm http fetch GET https://registry.npmjs.org/inflight/-/inflight-1.0.5.tgz
npm http fetch GET https://registry.npmjs.org/minimatch/-/minimatch-3.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/fs.realpath/-/fs.realpath-1.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/inflight/-/inflight-1.0.5.tgz
npm http fetch 200 https://registry.npmjs.org/minimatch/-/minimatch-3.0.2.tgz
npm http request GET https://registry.npmjs.org/wrappy
npm http 200 https://registry.npmjs.org/wrappy
npm http fetch GET https://registry.npmjs.org/wrappy/-/wrappy-1.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/wrappy/-/wrappy-1.0.2.tgz
npm http request GET https://registry.npmjs.org/brace-expansion
npm http 200 https://registry.npmjs.org/brace-expansion
npm http fetch GET https://registry.npmjs.org/brace-expansion/-/brace-expansion-1.1.6.tgz
npm http fetch 200 https://registry.npmjs.org/brace-expansion/-/brace-expansion-1.1.6.tgz
npm http request GET https://registry.npmjs.org/concat-map
npm http request GET https://registry.npmjs.org/balanced-match
npm http 304 https://registry.npmjs.org/concat-map
npm http 200 https://registry.npmjs.org/balanced-match
npm http fetch GET https://registry.npmjs.org/balanced-match/-/balanced-match-0.4.2.tgz
npm http fetch 200 https://registry.npmjs.org/balanced-match/-/balanced-match-0.4.2.tgz
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 200 https://registry.npmjs.org/es3ify
npm http fetch GET https://registry.npmjs.org/es3ify/-/es3ify-0.2.2.tgz
npm http 200 https://registry.npmjs.org/inline-process-browser
npm http 200 https://registry.npmjs.org/immediate
npm http fetch GET https://registry.npmjs.org/immediate/-/immediate-3.0.6.tgz
npm http fetch 200 https://registry.npmjs.org/es3ify/-/es3ify-0.2.2.tgz
npm http fetch 200 https://registry.npmjs.org/immediate/-/immediate-3.0.6.tgz
npm http 200 https://registry.npmjs.org/unreachable-branch-transform
npm http request GET https://registry.npmjs.org/esprima
npm http request GET https://registry.npmjs.org/through
npm http request GET https://registry.npmjs.org/jstransform
npm http 200 https://registry.npmjs.org/esprima
npm http 304 https://registry.npmjs.org/jstransform
npm http 200 https://registry.npmjs.org/through
npm http fetch GET https://registry.npmjs.org/jstransform/-/jstransform-11.0.3.tgz
npm http fetch 200 https://registry.npmjs.org/jstransform/-/jstransform-11.0.3.tgz
npm http request GET https://registry.npmjs.org/commoner
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/object-assign
npm http request GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 200 https://registry.npmjs.org/base62
npm http 200 https://registry.npmjs.org/object-assign
npm http fetch GET https://registry.npmjs.org/esprima-fb/-/esprima-fb-15001.1.0-dev-harmony-fb.tgz
npm http fetch GET https://registry.npmjs.org/base62/-/base62-1.1.1.tgz
npm http 200 https://registry.npmjs.org/source-map
npm http fetch GET https://registry.npmjs.org/object-assign/-/object-assign-2.1.1.tgz
npm http 200 https://registry.npmjs.org/commoner
npm http fetch GET https://registry.npmjs.org/commoner/-/commoner-0.10.4.tgz
npm http fetch 200 https://registry.npmjs.org/object-assign/-/object-assign-2.1.1.tgz
npm http fetch 200 https://registry.npmjs.org/base62/-/base62-1.1.1.tgz
npm http fetch 200 https://registry.npmjs.org/esprima-fb/-/esprima-fb-15001.1.0-dev-harmony-fb.tgz
npm http fetch 200 https://registry.npmjs.org/commoner/-/commoner-0.10.4.tgz
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/mkdirp
npm http request GET https://registry.npmjs.org/iconv-lite
npm http request GET https://registry.npmjs.org/detective
npm http request GET https://registry.npmjs.org/q
npm http request GET https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/recast
npm http 200 https://registry.npmjs.org/mkdirp
npm http 200 https://registry.npmjs.org/detective
npm http 200 https://registry.npmjs.org/q
npm http 200 https://registry.npmjs.org/commander
npm http 200 https://registry.npmjs.org/iconv-lite
npm http 200 https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/private
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
npm http 200 https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/object-keys
npm http 200 https://registry.npmjs.org/isarray
npm http 200 https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/foreach
npm http fetch GET https://registry.npmjs.org/object-keys/-/object-keys-1.0.11.tgz
npm http fetch 200 https://registry.npmjs.org/object-keys/-/object-keys-1.0.11.tgz
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/xtend
npm http 200 https://registry.npmjs.org/xtend
npm http 200 https://registry.npmjs.org/readable-stream
npm http fetch GET https://registry.npmjs.org/readable-stream/-/readable-stream-1.0.34.tgz
npm http fetch 200 https://registry.npmjs.org/readable-stream/-/readable-stream-1.0.34.tgz
npm http request GET https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/core-util-is
npm http 200 https://registry.npmjs.org/string_decoder
npm http request GET https://registry.npmjs.org/esmangle-evaluator
npm http 200 https://registry.npmjs.org/esmangle-evaluator
npm http fetch GET https://registry.npmjs.org/esmangle-evaluator/-/esmangle-evaluator-1.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/esmangle-evaluator/-/esmangle-evaluator-1.0.1.tgz
npm http request GET https://registry.npmjs.org/has-binary-data
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/socket.io-adapter
npm http request GET https://registry.npmjs.org/engine.io
npm http request GET https://registry.npmjs.org/socket.io-parser
npm http request GET https://registry.npmjs.org/socket.io-client
npm http 200 https://registry.npmjs.org/has-binary-data
npm http 304 https://registry.npmjs.org/debug
npm http fetch GET https://registry.npmjs.org/has-binary-data/-/has-binary-data-0.1.3.tgz
npm http 304 https://registry.npmjs.org/socket.io-parser
npm http 304 https://registry.npmjs.org/socket.io-adapter
npm http fetch GET https://registry.npmjs.org/debug/-/debug-2.1.0.tgz
npm http fetch GET https://registry.npmjs.org/socket.io-parser/-/socket.io-parser-2.2.4.tgz
npm http fetch GET https://registry.npmjs.org/socket.io-adapter/-/socket.io-adapter-0.3.1.tgz
npm http 200 https://registry.npmjs.org/socket.io-client
npm http 200 https://registry.npmjs.org/engine.io
npm http fetch GET https://registry.npmjs.org/socket.io-client/-/socket.io-client-1.3.6.tgz
npm http fetch GET https://registry.npmjs.org/engine.io/-/engine.io-1.5.2.tgz
npm http fetch 200 https://registry.npmjs.org/has-binary-data/-/has-binary-data-0.1.3.tgz
npm http fetch 200 https://registry.npmjs.org/engine.io/-/engine.io-1.5.2.tgz
npm http fetch 200 https://registry.npmjs.org/socket.io-adapter/-/socket.io-adapter-0.3.1.tgz
npm http fetch 200 https://registry.npmjs.org/debug/-/debug-2.1.0.tgz
npm http fetch 200 https://registry.npmjs.org/socket.io-parser/-/socket.io-parser-2.2.4.tgz
npm http fetch 200 https://registry.npmjs.org/socket.io-client/-/socket.io-client-1.3.6.tgz
npm http request GET https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/base64id
npm http request GET https://registry.npmjs.org/engine.io-parser
npm http request GET https://registry.npmjs.org/ws
npm http fetch GET https://registry.npmjs.org/debug/-/debug-1.0.3.tgz
npm http 304 https://registry.npmjs.org/base64id
npm http 304 https://registry.npmjs.org/engine.io-parser
npm http 200 https://registry.npmjs.org/ws
npm http fetch 200 https://registry.npmjs.org/debug/-/debug-1.0.3.tgz
npm http fetch GET https://registry.npmjs.org/engine.io-parser/-/engine.io-parser-1.2.1.tgz
npm http fetch GET https://registry.npmjs.org/ws/-/ws-0.7.2.tgz
npm http fetch 200 https://registry.npmjs.org/engine.io-parser/-/engine.io-parser-1.2.1.tgz
npm http fetch 200 https://registry.npmjs.org/ws/-/ws-0.7.2.tgz
npm http request GET https://registry.npmjs.org/arraybuffer.slice
npm http request GET https://registry.npmjs.org/after
npm http request GET https://registry.npmjs.org/base64-arraybuffer
npm http request GET https://registry.npmjs.org/blob
npm http request GET https://registry.npmjs.org/has-binary
npm http request GET https://registry.npmjs.org/utf8
npm http 304 https://registry.npmjs.org/base64-arraybuffer
npm http 200 https://registry.npmjs.org/blob
npm http 304 https://registry.npmjs.org/arraybuffer.slice
npm http 304 https://registry.npmjs.org/has-binary
npm http 200 https://registry.npmjs.org/after
npm http fetch GET https://registry.npmjs.org/blob/-/blob-0.0.2.tgz
npm http fetch GET https://registry.npmjs.org/has-binary/-/has-binary-0.1.5.tgz
npm http 304 https://registry.npmjs.org/utf8
npm http fetch GET https://registry.npmjs.org/utf8/-/utf8-2.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/utf8/-/utf8-2.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/has-binary/-/has-binary-0.1.5.tgz
npm http fetch 200 https://registry.npmjs.org/blob/-/blob-0.0.2.tgz
npm http request GET https://registry.npmjs.org/bufferutil
npm http request GET https://registry.npmjs.org/utf-8-validate
npm http request GET https://registry.npmjs.org/options
npm http request GET https://registry.npmjs.org/ultron
npm http 304 https://registry.npmjs.org/options
npm http 200 https://registry.npmjs.org/ultron
npm http 200 https://registry.npmjs.org/bufferutil
npm http fetch GET https://registry.npmjs.org/bufferutil/-/bufferutil-1.1.0.tgz
npm http 200 https://registry.npmjs.org/utf-8-validate
npm http fetch GET https://registry.npmjs.org/utf-8-validate/-/utf-8-validate-1.1.0.tgz
npm http fetch 200 https://registry.npmjs.org/bufferutil/-/bufferutil-1.1.0.tgz
npm http fetch 200 https://registry.npmjs.org/utf-8-validate/-/utf-8-validate-1.1.0.tgz
npm http request GET https://registry.npmjs.org/bindings
npm http request GET https://registry.npmjs.org/nan
npm http 200 https://registry.npmjs.org/nan
npm http fetch GET https://registry.npmjs.org/nan/-/nan-1.8.4.tgz
npm http 200 https://registry.npmjs.org/bindings
npm http fetch 200 https://registry.npmjs.org/nan/-/nan-1.8.4.tgz
npm http fetch GET https://registry.npmjs.org/debug/-/debug-1.0.2.tgz
npm http fetch GET https://registry.npmjs.org/object-keys/-/object-keys-1.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/debug/-/debug-1.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/object-keys/-/object-keys-1.0.1.tgz
npm http request GET https://registry.npmjs.org/component-emitter
npm http request GET https://registry.npmjs.org/benchmark
npm http request GET https://registry.npmjs.org/json3
npm http 200 https://registry.npmjs.org/component-emitter
npm http 200 https://registry.npmjs.org/benchmark
npm http 304 https://registry.npmjs.org/json3
npm http request GET https://registry.npmjs.org/backo2
npm http request GET https://registry.npmjs.org/to-array
npm http request GET https://registry.npmjs.org/parseuri
npm http request GET https://registry.npmjs.org/object-component
npm http request GET https://registry.npmjs.org/indexof
npm http request GET https://registry.npmjs.org/component-bind
npm http request GET https://registry.npmjs.org/engine.io-client
npm http 304 https://registry.npmjs.org/backo2
npm http 304 https://registry.npmjs.org/to-array
npm http 304 https://registry.npmjs.org/parseuri
npm http 304 https://registry.npmjs.org/object-component
npm http 200 https://registry.npmjs.org/indexof
npm http fetch GET https://registry.npmjs.org/to-array/-/to-array-0.1.3.tgz
npm http 304 https://registry.npmjs.org/component-bind
npm http fetch GET https://registry.npmjs.org/parseuri/-/parseuri-0.0.2.tgz
npm http 200 https://registry.npmjs.org/engine.io-client
npm http fetch GET https://registry.npmjs.org/engine.io-client/-/engine.io-client-1.5.2.tgz
npm http fetch 200 https://registry.npmjs.org/to-array/-/to-array-0.1.3.tgz
npm http fetch 200 https://registry.npmjs.org/parseuri/-/parseuri-0.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/engine.io-client/-/engine.io-client-1.5.2.tgz
npm http request GET https://registry.npmjs.org/component-inherit
npm http request GET https://registry.npmjs.org/parsejson
npm http request GET https://registry.npmjs.org/parseqs
npm http request GET https://registry.npmjs.org/has-cors
npm http fetch GET https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http 304 https://registry.npmjs.org/parseqs
npm http 304 https://registry.npmjs.org/has-cors
npm http 304 https://registry.npmjs.org/component-inherit
npm http 304 https://registry.npmjs.org/parsejson
npm http fetch GET https://registry.npmjs.org/has-cors/-/has-cors-1.0.3.tgz
npm http fetch 200 https://registry.npmjs.org/has-cors/-/has-cors-1.0.3.tgz
npm http fetch 200 https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http fetch GET https://github.com/component/global/archive/v2.0.1.tar.gz
npm http fetch 200 https://github.com/component/global/archive/v2.0.1.tar.gz
npm http request GET https://registry.npmjs.org/better-assert
npm http 200 https://registry.npmjs.org/better-assert
npm http request GET https://registry.npmjs.org/callsite
npm http 200 https://registry.npmjs.org/callsite
npm http request GET https://registry.npmjs.org/isstream
npm http request GET https://registry.npmjs.org/eyes
npm http request GET https://registry.npmjs.org/cycle
npm http request GET https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/colors
npm http request GET https://registry.npmjs.org/pkginfo
npm http request GET https://registry.npmjs.org/stack-trace
npm http 200 https://registry.npmjs.org/eyes
npm http 200 https://registry.npmjs.org/colors
npm http 200 https://registry.npmjs.org/cycle
npm http 200 https://registry.npmjs.org/isstream
npm http 200 https://registry.npmjs.org/pkginfo
npm http 200 https://registry.npmjs.org/stack-trace
npm http 200 https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/node-uuid
npm http request GET https://registry.npmjs.org/tape
npm http 200 https://registry.npmjs.org/node-uuid
npm http 200 https://registry.npmjs.org/tape
npm http request GET https://registry.npmjs.org/defined
npm http request GET https://registry.npmjs.org/jsonify
npm http request GET https://registry.npmjs.org/deep-equal
npm http 200 https://registry.npmjs.org/defined
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
npm http request GET https://registry.npmjs.org/forever-agent
npm http request GET https://registry.npmjs.org/body-parser
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/ip
npm http request GET https://registry.npmjs.org/javascript-state-machine
npm http request GET https://registry.npmjs.org/node-uuid
npm http request GET https://registry.npmjs.org/long
npm http request GET https://registry.npmjs.org/multiplex
npm http request GET https://registry.npmjs.org/winston
npm http request GET https://registry.npmjs.org/urlsafe-base64
npm http request GET https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/forever-agent
npm http 304 https://registry.npmjs.org/express
npm http 200 https://registry.npmjs.org/node-uuid
npm http 200 https://registry.npmjs.org/body-parser
npm http 200 https://registry.npmjs.org/long
npm http 304 https://registry.npmjs.org/winston
npm http fetch GET https://registry.npmjs.org/body-parser/-/body-parser-1.13.3.tgz
npm http 304 https://registry.npmjs.org/urlsafe-base64
npm http 200 https://registry.npmjs.org/salti
npm http fetch GET https://registry.npmjs.org/salti/-/salti-0.2.0.tgz
npm http fetch 200 https://registry.npmjs.org/body-parser/-/body-parser-1.13.3.tgz
npm http 200 https://registry.npmjs.org/javascript-state-machine
npm http 200 https://registry.npmjs.org/ip
npm http fetch GET https://registry.npmjs.org/ip/-/ip-1.0.1.tgz
npm http 304 https://registry.npmjs.org/multiplex
npm http fetch 200 https://registry.npmjs.org/salti/-/salti-0.2.0.tgz
npm http 200 https://registry.npmjs.org/request
npm http fetch GET https://registry.npmjs.org/request/-/request-2.64.0.tgz
npm http fetch 200 https://registry.npmjs.org/ip/-/ip-1.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/request/-/request-2.64.0.tgz
npm http request GET https://registry.npmjs.org/content-type
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/depd
npm http request GET https://registry.npmjs.org/http-errors
npm http request GET https://registry.npmjs.org/on-finished
npm http request GET https://registry.npmjs.org/iconv-lite
npm http request GET https://registry.npmjs.org/bytes
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/type-is
npm http request GET https://registry.npmjs.org/raw-body
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/on-finished
npm http 304 https://registry.npmjs.org/content-type
npm http 200 https://registry.npmjs.org/http-errors
npm http 200 https://registry.npmjs.org/depd
npm http 304 https://registry.npmjs.org/iconv-lite
npm http 304 https://registry.npmjs.org/qs
npm http 200 https://registry.npmjs.org/bytes
npm http 304 https://registry.npmjs.org/type-is
npm http 200 https://registry.npmjs.org/raw-body
npm http fetch GET https://registry.npmjs.org/iconv-lite/-/iconv-lite-0.4.11.tgz
npm http fetch GET https://registry.npmjs.org/bytes/-/bytes-2.1.0.tgz
npm http fetch GET https://registry.npmjs.org/raw-body/-/raw-body-2.1.7.tgz
npm http fetch 200 https://registry.npmjs.org/bytes/-/bytes-2.1.0.tgz
npm http fetch 200 https://registry.npmjs.org/iconv-lite/-/iconv-lite-0.4.11.tgz
npm http fetch 200 https://registry.npmjs.org/raw-body/-/raw-body-2.1.7.tgz
npm http request GET https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/inherits
npm http request GET https://registry.npmjs.org/statuses
npm http 304 https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/statuses
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
npm http 304 https://registry.npmjs.org/cookie-signature
npm http 304 https://registry.npmjs.org/array-flatten
npm http 304 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/cookie
npm http 304 https://registry.npmjs.org/content-disposition
npm http 304 https://registry.npmjs.org/escape-html
npm http 304 https://registry.npmjs.org/finalhandler
npm http 200 https://registry.npmjs.org/etag
npm http 304 https://registry.npmjs.org/fresh
npm http 304 https://registry.npmjs.org/merge-descriptors
npm http 304 https://registry.npmjs.org/methods
npm http 304 https://registry.npmjs.org/parseurl
npm http 304 https://registry.npmjs.org/path-to-regexp
npm http 304 https://registry.npmjs.org/proxy-addr
npm http 304 https://registry.npmjs.org/range-parser
npm http 304 https://registry.npmjs.org/send
npm http 200 https://registry.npmjs.org/utils-merge
npm http 304 https://registry.npmjs.org/vary
npm http 304 https://registry.npmjs.org/serve-static
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
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/immediate
npm http 304 https://registry.npmjs.org/inline-process-browser
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/esprima
npm http request GET https://registry.npmjs.org/jstransform
npm http request GET https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/esprima
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/commoner
npm http request GET https://registry.npmjs.org/object-assign
npm http request GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/object-assign
npm http 200 https://registry.npmjs.org/base62
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 304 https://registry.npmjs.org/commoner
npm http 200 https://registry.npmjs.org/source-map
npm http request GET https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/detective
npm http request GET https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/mkdirp
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/q
npm http request GET https://registry.npmjs.org/recast
npm http 200 https://registry.npmjs.org/detective
npm http 304 https://registry.npmjs.org/mkdirp
npm http 200 https://registry.npmjs.org/graceful-fs
npm http 304 https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/commander
npm http 304 https://registry.npmjs.org/q
npm http 200 https://registry.npmjs.org/private
npm http 200 https://registry.npmjs.org/recast
npm http request GET https://registry.npmjs.org/graceful-readlink
npm http 304 https://registry.npmjs.org/graceful-readlink
npm http request GET https://registry.npmjs.org/acorn
npm http request GET https://registry.npmjs.org/defined
npm http 304 https://registry.npmjs.org/acorn
npm http 304 https://registry.npmjs.org/defined
npm http request GET https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/once
npm http request GET https://registry.npmjs.org/path-is-absolute
npm http 304 https://registry.npmjs.org/inflight
npm http 304 https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/minimatch
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http request GET https://registry.npmjs.org/wrappy
npm http 304 https://registry.npmjs.org/wrappy
npm http request GET https://registry.npmjs.org/brace-expansion
npm http 304 https://registry.npmjs.org/brace-expansion
npm http request GET https://registry.npmjs.org/balanced-match
npm http request GET https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/balanced-match
npm http request GET https://registry.npmjs.org/minimist
npm http 304 https://registry.npmjs.org/minimist
npm http request GET https://registry.npmjs.org/ast-types
npm http 200 https://registry.npmjs.org/ast-types
npm http request GET https://registry.npmjs.org/amdefine
npm http 304 https://registry.npmjs.org/amdefine
npm http request GET https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/falafel
npm http 304 https://registry.npmjs.org/through2
npm http request GET https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/object-keys
npm http 200 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/foreach
npm http 304 https://registry.npmjs.org/object-keys
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/string_decoder
npm http 200 https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/esmangle-evaluator
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/duplexify
npm http request GET https://registry.npmjs.org/varint
npm http fetch GET https://registry.npmjs.org/readable-stream/-/readable-stream-2.1.4.tgz
npm http fetch 200 https://registry.npmjs.org/readable-stream/-/readable-stream-2.1.4.tgz
npm http 200 https://registry.npmjs.org/duplexify
npm http fetch GET https://registry.npmjs.org/duplexify/-/duplexify-3.4.5.tgz
npm http fetch 200 https://registry.npmjs.org/duplexify/-/duplexify-3.4.5.tgz
npm http 200 https://registry.npmjs.org/varint
npm http fetch GET https://registry.npmjs.org/varint/-/varint-4.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/varint/-/varint-4.0.1.tgz
npm http request GET https://registry.npmjs.org/stream-shift
npm http request GET https://registry.npmjs.org/end-of-stream
npm http 200 https://registry.npmjs.org/stream-shift
npm http 304 https://registry.npmjs.org/end-of-stream
npm http fetch GET https://registry.npmjs.org/stream-shift/-/stream-shift-1.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/stream-shift/-/stream-shift-1.0.0.tgz
npm http request GET https://registry.npmjs.org/buffer-shims
npm http request GET https://registry.npmjs.org/process-nextick-args
npm http request GET https://registry.npmjs.org/util-deprecate
npm http 304 https://registry.npmjs.org/util-deprecate
npm http 200 https://registry.npmjs.org/buffer-shims
npm http 200 https://registry.npmjs.org/process-nextick-args
npm http fetch GET https://registry.npmjs.org/buffer-shims/-/buffer-shims-1.0.0.tgz
npm http fetch GET https://registry.npmjs.org/process-nextick-args/-/process-nextick-args-1.0.7.tgz
npm http fetch 200 https://registry.npmjs.org/process-nextick-args/-/process-nextick-args-1.0.7.tgz
npm http fetch 200 https://registry.npmjs.org/buffer-shims/-/buffer-shims-1.0.0.tgz
npm http request GET https://registry.npmjs.org/bl
npm http request GET https://registry.npmjs.org/caseless
npm http request GET https://registry.npmjs.org/tunnel-agent
npm http request GET https://registry.npmjs.org/json-stringify-safe
npm http request GET https://registry.npmjs.org/form-data
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/http-signature
npm http request GET https://registry.npmjs.org/tough-cookie
npm http request GET https://registry.npmjs.org/oauth-sign
npm http request GET https://registry.npmjs.org/stringstream
npm http request GET https://registry.npmjs.org/aws-sign2
npm http request GET https://registry.npmjs.org/hawk
npm http request GET https://registry.npmjs.org/combined-stream
npm http request GET https://registry.npmjs.org/isstream
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/har-validator
npm http 304 https://registry.npmjs.org/caseless
npm http 200 https://registry.npmjs.org/tunnel-agent
npm http 200 https://registry.npmjs.org/json-stringify-safe
npm http 200 https://registry.npmjs.org/form-data
npm http fetch GET https://registry.npmjs.org/tunnel-agent/-/tunnel-agent-0.4.3.tgz
npm http 200 https://registry.npmjs.org/extend
npm http 200 https://registry.npmjs.org/http-signature
npm http 200 https://registry.npmjs.org/oauth-sign
npm http 200 https://registry.npmjs.org/tough-cookie
npm http fetch GET https://registry.npmjs.org/http-signature/-/http-signature-0.11.0.tgz
npm http fetch GET https://registry.npmjs.org/oauth-sign/-/oauth-sign-0.8.2.tgz
npm http fetch GET https://registry.npmjs.org/tough-cookie/-/tough-cookie-2.3.1.tgz
npm http 304 https://registry.npmjs.org/aws-sign2
npm http 304 https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/qs
npm http 200 https://registry.npmjs.org/isstream
npm http 200 https://registry.npmjs.org/hawk
npm http fetch GET https://registry.npmjs.org/qs/-/qs-5.1.0.tgz
npm http fetch 200 https://registry.npmjs.org/tunnel-agent/-/tunnel-agent-0.4.3.tgz
npm http fetch 200 https://registry.npmjs.org/http-signature/-/http-signature-0.11.0.tgz
npm http 200 https://registry.npmjs.org/har-validator
npm http fetch GET https://registry.npmjs.org/har-validator/-/har-validator-1.8.0.tgz
npm http fetch 200 https://registry.npmjs.org/oauth-sign/-/oauth-sign-0.8.2.tgz
npm http fetch 200 https://registry.npmjs.org/tough-cookie/-/tough-cookie-2.3.1.tgz
npm http fetch 200 https://registry.npmjs.org/qs/-/qs-5.1.0.tgz
npm http fetch 200 https://registry.npmjs.org/har-validator/-/har-validator-1.8.0.tgz
npm http 304 https://registry.npmjs.org/stringstream
npm http 200 https://registry.npmjs.org/bl
npm http request GET https://registry.npmjs.org/delayed-stream
npm http 304 https://registry.npmjs.org/delayed-stream
npm http request GET https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/chalk
npm http request GET https://registry.npmjs.org/is-my-json-valid
npm http 200 https://registry.npmjs.org/is-my-json-valid
npm http 200 https://registry.npmjs.org/chalk
npm http 304 https://registry.npmjs.org/bluebird
npm http fetch GET https://registry.npmjs.org/chalk/-/chalk-1.1.3.tgz
npm http fetch 200 https://registry.npmjs.org/chalk/-/chalk-1.1.3.tgz
npm http request GET https://registry.npmjs.org/has-ansi
npm http request GET https://registry.npmjs.org/escape-string-regexp
npm http request GET https://registry.npmjs.org/ansi-styles
npm http request GET https://registry.npmjs.org/strip-ansi
npm http request GET https://registry.npmjs.org/supports-color
npm http 200 https://registry.npmjs.org/has-ansi
npm http 200 https://registry.npmjs.org/supports-color
npm http 200 https://registry.npmjs.org/escape-string-regexp
npm http 200 https://registry.npmjs.org/ansi-styles
npm http 200 https://registry.npmjs.org/strip-ansi
npm http fetch GET https://registry.npmjs.org/ansi-styles/-/ansi-styles-2.2.1.tgz
npm http fetch 200 https://registry.npmjs.org/ansi-styles/-/ansi-styles-2.2.1.tgz
npm http request GET https://registry.npmjs.org/ansi-regex
npm http 200 https://registry.npmjs.org/ansi-regex
npm http request GET https://registry.npmjs.org/generate-object-property
npm http request GET https://registry.npmjs.org/generate-function
npm http request GET https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/generate-object-property
npm http 200 https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/generate-function
npm http request GET https://registry.npmjs.org/is-property
npm http 304 https://registry.npmjs.org/is-property
npm http request GET https://registry.npmjs.org/hoek
npm http request GET https://registry.npmjs.org/cryptiles
npm http request GET https://registry.npmjs.org/sntp
npm http request GET https://registry.npmjs.org/boom
npm http 200 https://registry.npmjs.org/cryptiles
npm http 200 https://registry.npmjs.org/sntp
npm http 200 https://registry.npmjs.org/boom
npm http 200 https://registry.npmjs.org/hoek
npm http request GET https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/asn1
npm http request GET https://registry.npmjs.org/ctype
npm http 304 https://registry.npmjs.org/ctype
npm http 200 https://registry.npmjs.org/asn1
npm http 200 https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/colors
npm http request GET https://registry.npmjs.org/cycle
npm http request GET https://registry.npmjs.org/eyes
npm http request GET https://registry.npmjs.org/pkginfo
npm http request GET https://registry.npmjs.org/stack-trace
npm http 200 https://registry.npmjs.org/cycle
npm http 200 https://registry.npmjs.org/colors
npm http 304 https://registry.npmjs.org/stack-trace
npm http 304 https://registry.npmjs.org/pkginfo
npm http 200 https://registry.npmjs.org/eyes
npm http request GET https://registry.npmjs.org/jsdoc
npm http 200 https://registry.npmjs.org/jsdoc
npm http fetch GET https://registry.npmjs.org/jsdoc/-/jsdoc-3.3.3.tgz
npm http fetch 200 https://registry.npmjs.org/jsdoc/-/jsdoc-3.3.3.tgz
npm http request GET https://registry.npmjs.org/catharsis
npm http request GET https://registry.npmjs.org/js2xmlparser
npm http request GET https://registry.npmjs.org/marked
npm http request GET https://registry.npmjs.org/strip-json-comments
npm http request GET https://registry.npmjs.org/underscore
npm http request GET https://registry.npmjs.org/requizzle
npm http request GET https://registry.npmjs.org/wrench
npm http request GET https://registry.npmjs.org/esprima
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 200 https://registry.npmjs.org/underscore
npm http 200 https://registry.npmjs.org/strip-json-comments
npm http 200 https://registry.npmjs.org/marked
npm http 304 https://registry.npmjs.org/esprima
npm http 200 https://registry.npmjs.org/wrench
npm http fetch GET https://registry.npmjs.org/esprima/-/esprima-1.2.5.tgz
npm WARN deprecated wrench@1.5.9: wrench.js is deprecated! You should check out fs-extra (https://github.com/jprichardson/node-fs-extra) for any operations you were using wrench for. Thanks for all the usage over the years.
npm http fetch GET https://registry.npmjs.org/wrench/-/wrench-1.5.9.tgz
npm http fetch 200 https://registry.npmjs.org/esprima/-/esprima-1.2.5.tgz
npm http fetch 200 https://registry.npmjs.org/wrench/-/wrench-1.5.9.tgz
npm http 200 https://registry.npmjs.org/catharsis
npm http fetch GET https://registry.npmjs.org/catharsis/-/catharsis-0.8.8.tgz
npm http 200 https://registry.npmjs.org/js2xmlparser
npm http fetch GET https://registry.npmjs.org/js2xmlparser/-/js2xmlparser-0.1.9.tgz
npm http fetch 200 https://registry.npmjs.org/catharsis/-/catharsis-0.8.8.tgz
npm http fetch 200 https://registry.npmjs.org/js2xmlparser/-/js2xmlparser-0.1.9.tgz
npm http 304 https://registry.npmjs.org/requizzle
npm http fetch 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http request GET https://registry.npmjs.org/underscore-contrib
npm http 304 https://registry.npmjs.org/underscore-contrib
npm WARN prefer global marked@0.3.5 should be installed with -g
npm http request GET https://registry.npmjs.org/fs-extra-promise
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/request
npm http request GET https://registry.npmjs.org/jxc
npm http request GET https://registry.npmjs.org/unzip
npm http 304 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/fs-extra-promise
npm http 200 https://registry.npmjs.org/unzip
npm http 200 https://registry.npmjs.org/jxc
npm http request GET https://registry.npmjs.org/fs-extra
npm http request GET https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/fs-extra
npm http 304 https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/jsonfile
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/jsonfile
npm http 200 https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/fs.realpath
npm http request GET https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/inherits
npm http request GET https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/once
npm http request GET https://registry.npmjs.org/path-is-absolute
npm http 304 https://registry.npmjs.org/inflight
npm http 304 https://registry.npmjs.org/once
npm http 200 https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/minimatch
npm http 304 https://registry.npmjs.org/fs.realpath
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http request GET https://registry.npmjs.org/wrappy
npm http 304 https://registry.npmjs.org/wrappy
npm http request GET https://registry.npmjs.org/brace-expansion
npm http 304 https://registry.npmjs.org/brace-expansion
npm http request GET https://registry.npmjs.org/balanced-match
npm http request GET https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/balanced-match
npm http request GET https://registry.npmjs.org/adm-zip
npm http request GET https://registry.npmjs.org/progress
npm http 200 https://registry.npmjs.org/adm-zip
npm http 200 https://registry.npmjs.org/progress
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/es3ify
npm http 304 https://registry.npmjs.org/immediate
npm http 304 https://registry.npmjs.org/inline-process-browser
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http request GET https://registry.npmjs.org/esprima
npm http request GET https://registry.npmjs.org/jstransform
npm http request GET https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/esprima
npm http 304 https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/through
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/commoner
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/object-assign
npm http request GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/object-assign
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 304 https://registry.npmjs.org/commoner
npm http 200 https://registry.npmjs.org/source-map
npm http 200 https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/detective
npm http request GET https://registry.npmjs.org/iconv-lite
npm http request GET https://registry.npmjs.org/mkdirp
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/q
npm http request GET https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/mkdirp
npm http 200 https://registry.npmjs.org/detective
npm http 200 https://registry.npmjs.org/private
npm http 304 https://registry.npmjs.org/iconv-lite
npm http 304 https://registry.npmjs.org/commander
npm http 304 https://registry.npmjs.org/q
npm http 200 https://registry.npmjs.org/recast
npm http request GET https://registry.npmjs.org/graceful-readlink
npm http 304 https://registry.npmjs.org/graceful-readlink
npm http request GET https://registry.npmjs.org/acorn
npm http request GET https://registry.npmjs.org/defined
npm http 200 https://registry.npmjs.org/defined
npm http 304 https://registry.npmjs.org/acorn
npm http request GET https://registry.npmjs.org/minimist
npm http 304 https://registry.npmjs.org/minimist
npm http request GET https://registry.npmjs.org/ast-types
npm http 200 https://registry.npmjs.org/ast-types
npm http request GET https://registry.npmjs.org/amdefine
npm http 304 https://registry.npmjs.org/amdefine
npm http request GET https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/falafel
npm http 304 https://registry.npmjs.org/through2
npm http request GET https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/object-keys
npm http 200 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/string_decoder
npm http request GET https://registry.npmjs.org/core-util-is
npm http 304 https://registry.npmjs.org/core-util-is
npm http 200 https://registry.npmjs.org/string_decoder
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
npm http 200 https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/forever-agent
npm http 304 https://registry.npmjs.org/extend
npm http 200 https://registry.npmjs.org/caseless
npm http 200 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/json-stringify-safe
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/tunnel-agent
npm http 200 https://registry.npmjs.org/node-uuid
npm http 200 https://registry.npmjs.org/mime-types
npm http 304 https://registry.npmjs.org/tough-cookie
npm http 304 https://registry.npmjs.org/http-signature
npm http 304 https://registry.npmjs.org/oauth-sign
npm http 304 https://registry.npmjs.org/hawk
npm http 200 https://registry.npmjs.org/aws-sign2
npm http 304 https://registry.npmjs.org/stringstream
npm http 304 https://registry.npmjs.org/combined-stream
npm http 200 https://registry.npmjs.org/isstream
npm http 200 https://registry.npmjs.org/har-validator
npm http request GET https://registry.npmjs.org/process-nextick-args
npm http request GET https://registry.npmjs.org/util-deprecate
npm http 200 https://registry.npmjs.org/util-deprecate
npm http 200 https://registry.npmjs.org/process-nextick-args
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
npm http 304 https://registry.npmjs.org/ansi-styles
npm http 304 https://registry.npmjs.org/strip-ansi
npm http 304 https://registry.npmjs.org/escape-string-regexp
npm http 304 https://registry.npmjs.org/supports-color
npm http 304 https://registry.npmjs.org/has-ansi
npm http request GET https://registry.npmjs.org/ansi-regex
npm http 304 https://registry.npmjs.org/ansi-regex
npm http request GET https://registry.npmjs.org/generate-function
npm http request GET https://registry.npmjs.org/generate-object-property
npm http request GET https://registry.npmjs.org/jsonpointer
npm http 200 https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/generate-function
npm http 304 https://registry.npmjs.org/generate-object-property
npm http request GET https://registry.npmjs.org/is-property
npm http 304 https://registry.npmjs.org/is-property
npm http request GET https://registry.npmjs.org/hoek
npm http request GET https://registry.npmjs.org/boom
npm http request GET https://registry.npmjs.org/cryptiles
npm http request GET https://registry.npmjs.org/sntp
npm http 304 https://registry.npmjs.org/hoek
npm http 304 https://registry.npmjs.org/cryptiles
npm http 304 https://registry.npmjs.org/sntp
npm http 304 https://registry.npmjs.org/boom
npm http request GET https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/asn1
npm http request GET https://registry.npmjs.org/ctype
npm http 304 https://registry.npmjs.org/asn1
npm http 304 https://registry.npmjs.org/assert-plus
npm http 304 https://registry.npmjs.org/ctype
npm http request GET https://registry.npmjs.org/fstream
npm http request GET https://registry.npmjs.org/setimmediate
npm http request GET https://registry.npmjs.org/binary
npm http request GET https://registry.npmjs.org/pullstream
npm http request GET https://registry.npmjs.org/match-stream
npm http 200 https://registry.npmjs.org/fstream
npm http 304 https://registry.npmjs.org/binary
npm http 304 https://registry.npmjs.org/pullstream
npm http 304 https://registry.npmjs.org/match-stream
npm http 200 https://registry.npmjs.org/setimmediate
npm http request GET https://registry.npmjs.org/chainsaw
npm http request GET https://registry.npmjs.org/buffers
npm http 304 https://registry.npmjs.org/chainsaw
npm http 304 https://registry.npmjs.org/buffers
npm http request GET https://registry.npmjs.org/traverse
npm http 200 https://registry.npmjs.org/traverse
npm http request GET https://registry.npmjs.org/graceful-fs
npm http 200 https://registry.npmjs.org/graceful-fs
npm WARN deprecated graceful-fs@3.0.8: graceful-fs v3.0.0 and before will fail on node releases >= v7.0. Please update to graceful-fs@^4.0.0 as soon as possible. Use 'npm ls graceful-fs' to find it in the tree.
npm http request GET https://registry.npmjs.org/over
npm http request GET https://registry.npmjs.org/slice-stream
npm http 304 https://registry.npmjs.org/slice-stream
npm http 304 https://registry.npmjs.org/over
npm WARN EPACKAGEJSON install@0.0.1 No repository field.
