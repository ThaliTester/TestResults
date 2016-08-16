#### Test (Fail) 80761374 Build Logs


```


```

```
Already up-to-date.

From https://github.com/thaliproject/Thali_CordovaPlugin
   1c4a608..f9c4447  vNext_mlesnic_777_clean -> origin/vNext_mlesnic_777_clean

```

```
Your branch is up-to-date with 'origin/master'.
Branch vNext_yarong_780 set up to track remote branch vNext_yarong_780 from origin.
Already up-to-date.

Already on 'master'
Switched to a new branch 'vNext_yarong_780'
Note: checking out 'f9c4447'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at f9c4447... Rerun

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
  │ ├── graceful-fs@3.0.9 
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
│ │ │   │ ├── after@0.8.2 
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
│ │ │   │   ├── lodash.pad@4.5.1 
│ │ │   │   ├── lodash.padend@4.6.1 
│ │ │   │   └── lodash.padstart@4.6.1 
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
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testNativeMethod.js
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
DEBUG createNativeListener: listening 49891
ok 1 Should throw
# teardown
# setup
# emits incomingConnectionState
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49893
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
DEBUG createNativeListener: listening 49896
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
DEBUG createNativeListener: listening 49900
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
DEBUG createNativeListener: listening 49905
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
DEBUG createNativeListener: listening 49909
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
DEBUG createNativeListener: listening 49913
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
DEBUG createNativeListener: listening 49917
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
DEBUG createNativeListener: listening 49921
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
DEBUG createNativeListener: listening 49973
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
DEBUG createNativeListener: listening 49977
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
DEBUG createNativeListener: listening 49982
# teardown
# setup
# calling createPeerListener after calling stop produces error
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49985
# teardown
# setup
# can call createPeerListener (pleaseConnect === false)
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49988
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
ok 45 port must be in range
# teardown
# setup
# calling createPeerListener (pleaseConnect === true) with unknown peer is error
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49992
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
DEBUG createNativeListener: listening 49997
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
ok 47 port values should be the same
# teardown
# setup
# createPeerListener - closing connection to native listener closes everything and triggers new listener
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50001
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
DEBUG createNativeListener: listening 50010
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
DEBUG createNativeListener: listening 50019
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
DEBUG createNativeListener: listening 50025
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
DEBUG createNativeListener: listening 50032
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
DEBUG createNativeListener: listening 50037
DEBUG createPeerListener: pleaseConnect= false
ok 68 peerPort != nativePort
DEBUG createPeerListener: first connection
DEBUG createPeerListener: forward connection
ok 69 Should not get unexpected connection
# teardown
# setup
# peerListener - forwardConnection, pleaseConnect === false - with native server and data transfer
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50043
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
DEBUG createNativeListener: listening 50050
DEBUG createPeerListener: pleaseConnect= false
ok 74 Second call to existing peerListener returns existing port
# teardown
# setup
# createPeerListener - pleaseConnect === true, failed connection rejects promise
DEBUG createNativeListener: creating native server
ok 75 Can call startUpdateAdvertisingAndListening without error
ok 76 Can call startListeningForAdvertisements without error
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createNativeListener: listening 50054
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
DEBUG createNativeListener: listening 50059
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
DEBUG createNativeListener: listening 50064
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
DEBUG createNativeListener: listening 50069
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
DEBUG createNativeListener: listening 50075
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: first connection
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createPeerListener: looking up mux for client port:  50078
DEBUG createPeerListener: reverse connection
DEBUG createPeerListener: looking up mux for client port:  50078
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
DEBUG createNativeListener: listening 50081
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: first connection
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createPeerListener: looking up mux for client port:  50084
DEBUG createPeerListener: reverse connection
DEBUG createPeerListener: looking up mux for client port:  50084
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
DEBUG createNativeListener: listening 50088
# teardown
# setup
# createPeerListener - ask for a new peer when we are not at maximum peers and make sure we do not remove any existing listeners
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50091
# teardown
# setup
# createPeerListener - pleaseConnect = false - test timeout
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50094
# teardown
# setup
# createPeerListener - pleaseConnect = true - test timeout
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50097
# teardown
# setup
# createPeerListener - forward connection - wrong serverPort
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50100
# teardown
# setup
# createPeerListener - forward connection - wrong clientPort
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50103
# teardown
# setup
# createPeerListener - please connect = false, multiple connections out
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50106
# teardown
# setup
# createPeerListener - please connect = false, multiple bi-directional connections
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50109
# teardown
# setup
# createPeerListener - multiple parallel calls
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50112
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
DEBUG createNativeListener: listening 50189
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
DEBUG createNativeListener: listening 50191
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
DEBUG createNativeListener: listening 50193
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
DEBUG createNativeListener: listening 50198
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
DEBUG createNativeListener: listening 50200
ok 192 first call should succeed
ok 193 first call should succeed
ok 194 specific error should be returned
# teardown
ok 195 error should be null
ok 196 error should be null
# setup
# does not emit duplicate discoveryAdvertisingStateUpdate
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50202
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
DEBUG createNativeListener: listening 50207
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
DEBUG createNativeListener: listening 50209
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
DEBUG createNativeListener: listening 50214
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
DEBUG createNativeListener: listening 50216
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
DEBUG createNativeListener: listening 50222
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
DEBUG createNativeListener: listening 50224
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
DEBUG createNativeListener: listening 50226
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
DEBUG createNativeListener: listening 50230
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
DEBUG createNativeListener: listening 50232
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 304 connection to servers manager should succeed after starting
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
ok 305 connection to router server should succeed after starting
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG createNativeListener: incoming socket close
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 306 is stopped after calling stop
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
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
DEBUG createNativeListener: listening 50240
INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":50239,"error":{}}
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
DEBUG createNativeListener: listening 50242
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
DEBUG createNativeListener: listening 50244
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG testUtils: We got a peer {"peerIdentifier":"foo","portNumber":50247,"hostAddress":"127.0.0.1"}
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
DEBUG createNativeListener: listening 50255
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
DEBUG createNativeListener: listening 50267
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
DEBUG createNativeListener: listening 50269
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: 50269
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
DEBUG createNativeListener: listening 50273
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 338 discoveryActive matches
ok 339 advertisingActive matches
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 340 discoveryActive matches
ok 341 advertisingActive matches
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50275
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 342 discoveryActive matches
ok 343 advertisingActive matches
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 344 discoveryActive matches
ok 345 advertisingActive matches
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50279
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
DEBUG createNativeListener: listening 50390
ok 690 port must be in range
# teardown
# setup
# starting twice resolves with listening port
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50391
ok 691 second start should return same port
# teardown
# setup
# terminateIncomingConnection will terminate a connection
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50393
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
DEBUG createNativeListener: listening 50395
# teardown
# setup
# terminate an Outgoing connection with wrong arguments is not harmful
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50396
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
# #ThaliPeerPoolDefault - single action
ok 784 is an agent
ok 785 enqueue is fine
ok 786 Everything should be off the queue
# teardown
# setup
# #ThaliPeerPoolDefault - multiple actions
ok 787 is an agent
ok 788 first enqueue is fine
ok 789 is an agent
ok 790 second enqueue is fine
ok 791 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 792 Queue is empty
# teardown
# setup
# #ThaliPeerPoolDefault - PSK Pool works
ok 793 is an agent
ok 794 good enqueue
ok 795 Identity should match
ok 796 Got expected response
ok 797 Got psk call back
# teardown
# setup
# #ThaliPeerPoolDefault - stop
ok 798 is an agent
ok 799 enqueue worked
ok 800 is an agent
ok 801 enqueue 2 worked
ok 802 start action is killed
ok 803 killed action is still killed
ok 804 inQueue is empty
ok 805 Make sure we won enqueue after stopping
# teardown

1..805
# tests 805
# pass  805

# ok


> thali-cordova-plugin-jxcore@1.0.0 test-meta /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore
> jx runTests.js meta_tests

Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/meta_tests/testInstall.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/meta_tests/testPerfTestFramework.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/meta_tests/testPerfTestFrameworkClient.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/meta_tests/testResultsProcessor.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/meta_tests/testTestSendData.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/meta_tests/testTestUtils.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/meta_tests/testUnitTestFramework.js
TAP version 13
# setup
# two required plugins should get installed
Trying to install jxcore-cordova version: 0.1.2
[36mUsing cached file:[39m /Users/thali/.jxc/cache/0.1.2/io.jxcore.node.jx

[32mExtracting plugin package...[39m

[32mDone.[39m

[32mRemoving plugin from project...[39m

[1A[K
[31mRemoving plugin from project...[39m

[32mAdding plugin to project...[39m

[32mCleaning up...[39m

[32mDone.[39m

Starting to download Thali Cordova plugin from: https://codeload.github.com/thaliproject/Thali_CordovaPlugin/zip/npmv2.1.0
Adding Thali Cordova plugin from: /var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/T/tmp-455952T0WfCahv7m/TestApp/thaliDontCheckIn/Thali_CordovaPlugin-npmv2.1.0
Running jx npm install in: /var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/T/tmp-455952T0WfCahv7m/TestApp/plugins/org.thaliproject.p2p/scripts
scripts@0.0.1 /private/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/T/tmp-455952T0WfCahv7m/TestApp/plugins/org.thaliproject.p2p/scripts
└─┬ fs-extra-promise@0.2.1 
  ├── bluebird@2.10.2 
  └─┬ fs-extra@0.24.0 
    ├── graceful-fs@4.1.5 
    ├── jsonfile@2.3.1 
    ├── path-is-absolute@1.0.0 
    └─┬ rimraf@2.5.4 
      └─┬ glob@7.0.5 
        ├── fs.realpath@1.0.0 
        ├─┬ inflight@1.0.5 
        │ └── wrappy@1.0.2 
        ├── inherits@2.0.1 
        ├─┬ minimatch@3.0.3 
        │ └─┬ brace-expansion@1.1.6 
        │   ├── balanced-match@0.4.2 
        │   └── concat-map@0.0.1 
        └── once@1.3.3 


npm http request GET http://192.168.1.100:4873/fs-extra-promise
npm http 304 http://192.168.1.100:4873/fs-extra-promise
npm http request GET http://192.168.1.100:4873/fs-extra
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/fs-extra
npm http 200 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/jsonfile
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http request GET http://192.168.1.100:4873/rimraf
npm http 304 http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/rimraf
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http 200 http://192.168.1.100:4873/jsonfile
npm http request GET http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/fs.realpath
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/fs.realpath
npm http 304 http://192.168.1.100:4873/minimatch
npm http 200 http://192.168.1.100:4873/inflight
npm http 304 http://192.168.1.100:4873/once
npm http 200 http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/wrappy
npm http 304 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 304 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/balanced-match
npm WARN EPACKAGEJSON scripts@0.0.1 No repository field.

ok 1 jxcore cordova plugin is installed
ok 2 thali cordova plugin is installed
# teardown
# setup
# should be able to add devices to the framework
ok 3 should be equal
# teardown
# setup
# passing wrong test name should throw
check test folder
found test : ./testFindPeers.js
found test : ./testSendData.js
--- start :testThatDoesNotExist---
--- start :testThatDoesNotExist---
ok 4 Unknown test
# teardown
# setup
# own address should be filtered out and try count reseted
check test folder
found test : ./testFindPeers.js
found test : ./testSendData.js
--- start :mockTest---
--- start :mockTest---
ok 5 own address filtered out
ok 6 other addresses in the address property
ok 7 try count is 0 in the beginning
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
ok 8 received processed results
# teardown
# setup
# connector should fail if server not running
daya0
oneRoundDownNow
ok 9 received a result to the done event
# teardown
# setup
# connector should be able to send data to a running server
daya1000000
oneRoundDownNow
ok 10 received a result to the done event
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
ok 11 received a result to the done event
ok 12 should be equal
testSendData stopped
# teardown
# setup
# should return same temporary folder when called multiple times
ok 13 should be equal
# teardown
# setup
# should be able to write to the temporary folder
/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/T/tmp-455952T0WfCahv7m
ok 14 no error returned when creating a subfolder
# teardown
# setup
# can call hasRequiredHardware
ok 15 resolves with a boolean
# teardown
# setup
# should get right number of setup emits
Require 3 ios devices
Require 3 android devices
All 3 ios devices are present
Starting unit test run on 3 ios devices
Running on ios test: test-1
All 3 android devices are present
Starting unit test run on 3 android devices
Running on android test: test-1
ok 16 received right amount of setup commands from the server
# teardown
# setup
# should discard surplus devices
Require 3 ios devices
Require 3 android devices
All 3 ios devices are present
ok 17 should have discarded the extra devices
# teardown
# setup
# should disqualify unsupported device
Require 3 ios devices
Require 3 android devices
All 3 ios devices are present
Disqualifying device with unsupported hardware: some-name
ok 18 disqualified unsupported device
# teardown
StopBroadcasting went ok

1..18
# tests 18
# pass  18

# ok


> thali-cordova-plugin-jxcore@1.0.0 test-coordinated /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore
> jx runCoordinatedTests.js

2016-08-16T07:39:25.961Z - info: Require 3 ios devices

2016-08-16T07:39:25.966Z - info: Require 0 android devices

2016-08-16T07:39:25.979Z - info: listening on *:3000

[32mUnit Test app is loaded
[39m
[32mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[32mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[32mMy device name is: 0a79a281-dea2-4a2a-a650-0d351e01ba0c
[39m
[32mWARN testUtils: myNameCallback not set!
[39m
[36mUnit Test app is loaded
[39m
[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
My device name is: 6140f2bb-3ced-4f37-922e-8a80dec969c0
[39m
[36mWARN testUtils: myNameCallback not set!
[39m
[33mUnit Test app is loaded
[39m
[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[33mMy device name is: 7908f98f-c49a-41d6-ae68-11527ecf517c
[39m
[33mWARN testUtils: myNameCallback not set!
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreateNativeListener.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreateNativeListener.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreateNativeListener.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testNativeMethod.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPromiseQueue.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testTests.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testNativeMethod.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPromiseQueue.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testTests.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testNativeMethod.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPromiseQueue.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testTests.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNative.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotification.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationAction.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationBeacons.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNative.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotification.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationAction.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationBeacons.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationClient.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationLocal.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationClient.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationServer.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationLocal.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationServer.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerAction.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerAction.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerDictionary.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerDictionary.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNative.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationUtilities.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotification.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationAction.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliTcpServersManager.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationBeacons.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationUtilities.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliTcpServersManager.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationClient.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationLocal.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationServer.js
[39m
[36mConnected to the test server
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerAction.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerDictionary.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
[39m
2016-08-16T07:39:28.844Z - debug: Device presented: 6140f2bb-3ced-4f37-922e-8a80dec969c0 (e1cf421e-f4d3-45f2-8ce8-347e8346adcb) - ios dummy

[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationUtilities.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
[39m
[32mConnected to the test server
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliTcpServersManager.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
[39m
2016-08-16T07:39:28.874Z - debug: Device presented: 0a79a281-dea2-4a2a-a650-0d351e01ba0c (b85f0e42-f4f3-40d9-abe4-92e212f9c537) - ios dummy

[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
[39m
[33mConnected to the test server
[39m
2016-08-16T07:39:28.913Z - debug: Device presented: 7908f98f-c49a-41d6-ae68-11527ecf517c (c49b150c-30bd-4400-a254-fc6f975434b3) - ios dummy

2016-08-16T07:39:28.913Z - info: All 3 ios devices are present

2016-08-16T07:39:28.914Z - info: Starting unit test run on 3 ios devices

[36mTAP version 13
[39m
[36m# setup
[39m
[32mTAP version 13
[39m
[32m# setup
[39m
[33mTAP version 13
[39m
[33m# setup
[39m
2016-08-16T07:39:29.090Z - info: Running on ios test: 1. calling createNativeListener directly rejects

[36m# 1. calling createNativeListener directly rejects
[39m
[32m# 1. calling createNativeListener directly rejects
[39m
[33m# 1. calling createNativeListener directly rejects
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50439
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50440
[39m
[36mok 1 Should throw
# teardown
[39m
[32mok 1 Should throw
# teardown
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: listening 50441
[39m
[33mok 1 Should throw
[39m
[33m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-16T07:39:29.139Z - info: Running on ios test: 2. emits incomingConnectionState

[32m# 2. emits incomingConnectionState
[39m
[36m# 2. emits incomingConnectionState
[39m
[33m# 2. emits incomingConnectionState
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50446
[39m
[36mDEBUG createNativeListener: listening 50445
DEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[36mok 2 initial connection state should be CONNECTED
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[32mok 2 initial connection state should be CONNECTED
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: listening 50449
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[32mok 3 final connection state should be DISCONNECTED
[39m
[33mDEBUG createNativeListener: new incoming socket
[39m
[32m# teardown
[39m
[33mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: incoming socket close
ok 3 final connection state should be DISCONNECTED
[39m
[33mDEBUG createNativeListener: new mux
[39m
[36m# teardown
[39m
[33mok 2 initial connection state should be CONNECTED
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[33mok 3 final connection state should be DISCONNECTED
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:39:29.198Z - info: Running on ios test: 3. emits routerPortConnectionFailed

[32m# 3. emits routerPortConnectionFailed
[39m
[36m# 3. emits routerPortConnectionFailed
[39m
[33m# 3. emits routerPortConnectionFailed
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: listening 50454
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: listening 50456
[39m
[32mDEBUG createNativeListener: new mux
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: 
ok 4 tried to connect to right port
[39m
[36mok 5 failed due to refused connection
ok 6 routerPortConnectionFailed is emitted
[39m
[36m# teardown
DEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: 
ok 4 tried to connect to right port
ok 5 failed due to refused connection
ok 6 routerPortConnectionFailed is emitted
# teardown
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: listening 50460
[39m
[33mDEBUG createNativeListener: new incoming socket
[39m
[33mDEBUG createNativeListener: creating incoming mux
[39m
[33mDEBUG createNativeListener: new mux
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: 
[39m
[33mok 4 tried to connect to right port
[39m
[33mok 5 failed due to refused connection
[39m
[33mok 6 routerPortConnectionFailed is emitted
[39m
[33m# teardown
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: mux close
[39m
[32m# setup
DEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createNativeListener: mux close
[39m
[36m# setup
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[33mDEBUG createNativeListener: mux close
[39m
[33m# setup
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
2016-08-16T07:39:29.277Z - info: Running on ios test: 4. native server connections all up

[32m# 4. native server connections all up
[39m
[36m# 4. native server connections all up
[39m
[33m# 4. native server connections all up
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50466
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50467
[39m
[32mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[36mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[36mok 7 Send/recvd #1 should be equal length
ok 8 Send/recvd #1 should be same
ok 9 Send/recvd #2 should be equal length
ok 10 Send/recvd #2 should be same
ok 11 Should be exactly 2 client sockets
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[36m# teardown
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: listening 50474
[39m
[32mok 7 Send/recvd #1 should be equal length
ok 8 Send/recvd #1 should be same
[39m
[32mok 9 Send/recvd #2 should be equal length
[39m
[32mok 10 Send/recvd #2 should be same
[39m
[32mok 11 Should be exactly 2 client sockets
[39m
[32m# teardown
[39m
[33mDEBUG createNativeListener: new incoming socket
[39m
[33mDEBUG createNativeListener: creating incoming mux
[39m
[33mDEBUG createNativeListener: new mux
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mok 7 Send/recvd #1 should be equal length
[39m
[33mok 8 Send/recvd #1 should be same
[39m
[33mok 9 Send/recvd #2 should be equal length
ok 10 Send/recvd #2 should be same
[39m
[33mok 11 Should be exactly 2 client sockets
[39m
[33m# teardown
[39m
[36mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
# setup
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: mux close
[39m
[32m# setup
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: mux close
[39m
[33m# setup
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
2016-08-16T07:39:29.349Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

[32m# 5. native server - closing incoming stream cleans outgoing socket
[39m
[36m# 5. native server - closing incoming stream cleans outgoing socket
[39m
[33m# 5. native server - closing incoming stream cleans outgoing socket
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50481
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50482
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[32mok 12 socket shouldn't close until after stream
ok 13 incoming remains open
[39m
[32m# teardown
[39m
[36mok 12 socket shouldn't close until after stream
ok 13 incoming remains open
[39m
[36m# teardown
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: listening 50487
[39m
[33mDEBUG createNativeListener: new incoming socket
[39m
[33mDEBUG createNativeListener: creating incoming mux
[39m
[33mDEBUG createNativeListener: new mux
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mok 12 socket shouldn't close until after stream
[39m
[33mok 13 incoming remains open
[39m
[33m# teardown
[39m
[32mDEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createNativeListener: mux close
# setup
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[33mDEBUG createNativeListener: mux close
[39m
[33m# setup
DEBUG createNativeListener: incoming socket close
[39m
2016-08-16T07:39:29.403Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

[36m# 6. native server - closing incoming connection cleans outgoing socket
[39m
[32m# 6. native server - closing incoming connection cleans outgoing socket
[39m
[33m# 6. native server - closing incoming connection cleans outgoing socket
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50494
[39m
[32mDEBUG createNativeListener: listening 50493
[39m
[36mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 14 we should not have gotten an error
[39m
[32mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: incoming socket close
[39m
[36mok 15 socket shouldn't close until after incoming
[39m
[36mok 16 incoming is cleaned up
[39m
[36m# teardown
[39m
[32mok 14 we should not have gotten an error
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: incoming socket close
[39m
[32mok 15 socket shouldn't close until after incoming
ok 16 incoming is cleaned up
[39m
[32m# teardown
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50499
[39m
[33mDEBUG createNativeListener: new incoming socket
[39m
[33mDEBUG createNativeListener: creating incoming mux
[39m
[33mDEBUG createNativeListener: new mux
[39m
[33mok 14 we should not have gotten an error
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[33mok 15 socket shouldn't close until after incoming
[39m
[33mok 16 incoming is cleaned up
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:39:29.453Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

[32m# 7. native server - closing outgoing socket cleans associated mux stream
[39m
[36m# 7. native server - closing outgoing socket cleans associated mux stream
[39m
[33m# 7. native server - closing outgoing socket cleans associated mux stream
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50505
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[36mDEBUG createNativeListener: listening 50508
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[33mDEBUG createNativeListener: listening 50506
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: new incoming socket
[39m
[36mok 17 stream was closed
ok 18 incoming should survive
ok 19 mux should have no streams
[39m
[33mDEBUG createNativeListener: creating incoming mux
[39m
[36m# teardown
[39m
[32mok 17 stream was closed
[39m
[33mDEBUG createNativeListener: new mux
[39m
[32mok 18 incoming should survive
[39m
[32mok 19 mux should have no streams
[39m
[32m# teardown
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mok 17 stream was closed
[39m
[33mok 18 incoming should survive
ok 19 mux should have no streams
[39m
[33m# teardown
[39m
[36mDEBUG createNativeListener: mux close
[39m
[36m# setup
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createNativeListener: mux close
[39m
[32m# setup
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[33mDEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
[39m
2016-08-16T07:39:29.507Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

[36m# 8. native server - closing the whole server cleans everything up
[39m
[32m# 8. native server - closing the whole server cleans everything up
[39m
[33m# 8. native server - closing the whole server cleans everything up
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50517
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50518
[39m
[32mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[36mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 20 we should not have gotten an error
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mok 21 Buffers are identical
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: mux close
[39m
[32mok 20 we should not have gotten an error
[39m
[36mok 22 native server is nulled out
[39m
[36mok 23 native server should be closed
[39m
[36mok 24 incoming has been removed
ok 25 Incoming should be done
ok 26 The mux object should be closed
[39m
[36mok 27 The mux stream should be closed
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[36m# teardown
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mok 21 Buffers are identical
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50523
[39m
[33mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: mux close
[39m
[33mDEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[32mok 22 native server is nulled out
ok 23 native server should be closed
ok 24 incoming has been removed
ok 25 Incoming should be done
ok 26 The mux object should be closed
ok 27 The mux stream should be closed
DEBUG createNativeListener: incoming socket close
[39m
[33mok 20 we should not have gotten an error
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[32m# teardown
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mok 21 Buffers are identical
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: mux close
[39m
[33mok 22 native server is nulled out
[39m
[33mok 23 native server should be closed
ok 24 incoming has been removed
[39m
[33mok 25 Incoming should be done
ok 26 The mux object should be closed
ok 27 The mux stream should be closed
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:39:29.572Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

[36m# 9. native server - we can get a ton of connections and data through and still clean up the server completely
[39m
[32m# 9. native server - we can get a ton of connections and data through and still clean up the server completely
[39m
[33m# 9. native server - we can get a ton of connections and data through and still clean up the server completely
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50529
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50530
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[36mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[36mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[36mDEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[32mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[32mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: listening 50594
[39m
[32mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new incoming socket
[39m
[33mDEBUG createNativeListener: creating incoming mux
[39m
[33mDEBUG createNativeListener: new mux
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
[39m
[33mDEBUG createNativeListener: new mux
[39m
[33mDEBUG createNativeListener: new incoming socket
[39m
[33mDEBUG createNativeListener: creating incoming mux
[39m
[33mDEBUG createNativeListener: new mux
[39m
[33mDEBUG createNativeListener: new incoming socket
[39m
[33mDEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
[39m
[33mDEBUG createNativeListener: new mux
[39m
[33mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new mux
[39m
[33mDEBUG createNativeListener: new incoming socket
[39m
[33mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new mux
[39m
[33mDEBUG createNativeListener: new incoming socket
[39m
[33mDEBUG createNativeListener: creating incoming mux
[39m
[33mDEBUG createNativeListener: new mux
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: mux close
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: mux close
[39m
[36mok 28 native server is nulled out
[39m
[36mok 29 native server should be closed
ok 30 incoming has been removed
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
[39m
[33mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
[39m
[33mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: mux close
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: mux close
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: mux close
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: mux close
[39m
[33mok 28 native server is nulled out
ok 29 native server should be closed
[39m
[33mok 30 incoming has been removed
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[33mDEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[36m# teardown
[39m
[33m# teardown
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: mux close
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: mux close
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: mux close
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: mux close
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: mux close
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: mux close
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: mux close
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: mux close
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: mux close
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: mux close
ok 28 native server is nulled out
ok 29 native server should be closed
ok 30 incoming has been removed
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[32m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:39:29.875Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

[32m# 10. native server - simulate mux failure, make sure everything is cleaned up
[39m
[36m# 10. native server - simulate mux failure, make sure everything is cleaned up
[39m
[33m# 10. native server - simulate mux failure, make sure everything is cleaned up
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50685
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50686
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[32mok 31 we should not have gotten an error
[39m
[32mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[32mok 32 Buffers are identical
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: mux close
[39m
[32mDEBUG createNativeListener: incoming socket close
ok 33 server should be fine
[39m
[32mok 34 server should be open
ok 35 incoming has been removed
[39m
[32mok 36 The mux object should be closed
[39m
[32mok 37 The mux stream should be closed
[39m
[32m# teardown
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[36mok 31 we should not have gotten an error
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mok 32 Buffers are identical
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[36mok 33 server should be fine
[39m
[36mok 34 server should be open
ok 35 incoming has been removed
[39m
[36mok 36 The mux object should be closed
[39m
[36mok 37 The mux stream should be closed
[39m
[33mDEBUG createNativeListener: listening 50691
[39m
[36m# teardown
[39m
[33mDEBUG createNativeListener: new incoming socket
[39m
[33mDEBUG createNativeListener: creating incoming mux
[39m
[33mDEBUG createNativeListener: new mux
[39m
[33mok 31 we should not have gotten an error
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mok 32 Buffers are identical
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: mux close
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[33mok 33 server should be fine
[39m
[33mok 34 server should be open
ok 35 incoming has been removed
[39m
[33mok 36 The mux object should be closed
[39m
[33mok 37 The mux stream should be closed
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:39:29.926Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

[32m# 11. native server - timing out the incoming connection cleans everything up
[39m
[36m# 11. native server - timing out the incoming connection cleans everything up
[39m
[33m# 11. native server - timing out the incoming connection cleans everything up
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50697
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 38 we should not have gotten an error
[39m
[36mDEBUG createNativeListener: listening 50699
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
ok 39 Buffers are identical
[39m
[36mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[36mok 38 we should not have gotten an error
DEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: incoming socket timeout
DEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: mux close
[39m
[36mok 39 Buffers are identical
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[32mok 40 server should be fine
[39m
[32mok 41 server should be open
ok 42 incoming has been removed
[39m
[32mok 43 The mux object should be closed
ok 44 The mux stream should be closed
[39m
[32m# teardown
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: incoming socket timeout
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: listening 50703
[39m
[33mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[36mDEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: incoming socket close
ok 40 server should be fine
ok 41 server should be open
[39m
[33mok 38 we should not have gotten an error
[39m
[36mok 42 incoming has been removed
ok 43 The mux object should be closed
ok 44 The mux stream should be closed
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[36m# teardown
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mok 39 Buffers are identical
[39m
[33mDEBUG createNativeListener: incoming socket timeout
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: mux close
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[33mok 40 server should be fine
[39m
[33mok 41 server should be open
[39m
[33mok 42 incoming has been removed
[39m
[33mok 43 The mux object should be closed
ok 44 The mux stream should be closed
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:39:29.988Z - info: Running on ios test: 12. #_doImmediateSeqUpdate - server is not there

[36m# 12. #_doImmediateSeqUpdate - server is not there
[39m
[32m# 12. #_doImmediateSeqUpdate - server is not there
[39m
[33m# 12. #_doImmediateSeqUpdate - server is not there
[39m
[36mDEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}
ok 45 Got right error
# teardown
[39m
[32mDEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}
ok 45 Got right error
# teardown
[39m
[33mDEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}
[39m
[33mok 45 Got right error
[39m
[33m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-16T07:39:30.074Z - info: Running on ios test: 13. #_doImmediateSeqUpdate - server accepts & closes connection

[32m# 13. #_doImmediateSeqUpdate - server accepts & closes connection
[39m
[36m# 13. #_doImmediateSeqUpdate - server accepts & closes connection
[39m
[33m# 13. #_doImmediateSeqUpdate - server accepts & closes connection
[39m
[32mDEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNRESET","status":500}
ok 46 Got socket hang up
# teardown
[39m
[36mDEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNRESET","status":500}
ok 46 Got socket hang up
[39m
[36m# teardown
[39m
[33mDEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNRESET","status":500}
[39m
[33mok 46 Got socket hang up
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:39:30.122Z - info: Running on ios test: 14. #_doImmediateSeqUpdate - server always returns 500

[32m# 14. #_doImmediateSeqUpdate - server always returns 500
[39m
[36m# 14. #_doImmediateSeqUpdate - server always returns 500
[39m
[33m# 14. #_doImmediateSeqUpdate - server always returns 500
[39m
[32mDEBUG localSeqManager: Got an error trying to update seq []
ok 47 Got 500 as expected
[39m
[32m# teardown
[39m
[36mDEBUG localSeqManager: Got an error trying to update seq []
ok 47 Got 500 as expected
[39m
[36m# teardown
[39m
[33mDEBUG localSeqManager: Got an error trying to update seq []
[39m
[33mok 47 Got 500 as expected
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:39:30.180Z - info: Running on ios test: 15. #_doImmediateSeqUpdate - create new seq doc

[32m# 15. #_doImmediateSeqUpdate - create new seq doc
[39m
[36m# 15. #_doImmediateSeqUpdate - create new seq doc
[39m
[33m# 15. #_doImmediateSeqUpdate - create new seq doc
[39m
[32mok 48 should be equal
[39m
[32mok 49 revs are equal
[39m
[32m# teardown
[39m
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
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-16T07:39:30.656Z - info: Running on ios test: 16. #_doImmediateSeqUpdate - doc exists, need to get rev and update

[33m# 16. #_doImmediateSeqUpdate - doc exists, need to get rev and update
[39m
[36m# 16. #_doImmediateSeqUpdate - doc exists, need to get rev and update
[39m
[32m# 16. #_doImmediateSeqUpdate - doc exists, need to get rev and update
[39m
[36mok 50 should be equal
[39m
[36mok 51 revs are equal
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
[32m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:39:30.803Z - info: Running on ios test: 17. #_doImmediateSeqUpdate - update seq three times

[32m# 17. #_doImmediateSeqUpdate - update seq three times
[39m
[36m# 17. #_doImmediateSeqUpdate - update seq three times
[39m
[33m# 17. #_doImmediateSeqUpdate - update seq three times
[39m
[36mok 52 should be equal
ok 53 revs are equal
[39m
[33mok 52 should be equal
ok 53 revs are equal
[39m
[36mok 54 should be equal
[39m
[36mok 55 revs are equal
[39m
[32mok 52 should be equal
ok 53 revs are equal
[39m
[33mok 54 should be equal
[39m
[32mok 54 should be equal
ok 55 revs are equal
[39m
[36mok 56 should be equal
ok 57 revs are equal
[39m
[36m# teardown
[39m
[33mok 55 revs are equal
[39m
[32mok 56 should be equal
ok 57 revs are equal
[39m
[32m# teardown
[39m
[33mok 56 should be equal
[39m
[33mok 57 revs are equal
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:39:30.976Z - info: Running on ios test: 18. #_doImmediateSeqUpdate - rev got changed under us

[36m# 18. #_doImmediateSeqUpdate - rev got changed under us
[39m
[33m# 18. #_doImmediateSeqUpdate - rev got changed under us
[39m
[32m# 18. #_doImmediateSeqUpdate - rev got changed under us
[39m
[33mDEBUG localSeqManager: Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}
[39m
[33mok 58 Our rev is old so we should fail
[39m
[36mDEBUG localSeqManager: Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}
[39m
[36mok 58 Our rev is old so we should fail
[39m
[36m# teardown
[39m
[33m# teardown
[39m
[32mDEBUG localSeqManager: Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}
[39m
[32mok 58 Our rev is old so we should fail
[39m
[32m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-16T07:39:31.138Z - info: Running on ios test: 19. #_doImmediateSeqUpdate - fail if stop is called

[36m# 19. #_doImmediateSeqUpdate - fail if stop is called
[39m
[33m# 19. #_doImmediateSeqUpdate - fail if stop is called
[39m
[32m# 19. #_doImmediateSeqUpdate - fail if stop is called
[39m
[33mok 59 confirm stop caused failure
[39m
[33m# teardown
[39m
[36mok 59 confirm stop caused failure
[39m
[36m# teardown
[39m
[32mok 59 confirm stop caused failure
[39m
[32m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-16T07:39:31.179Z - info: Running on ios test: 20. #_doImmediateSeqUpdate - stop after get but before put fails right

[36m# 20. #_doImmediateSeqUpdate - stop after get but before put fails right
[39m
[33m# 20. #_doImmediateSeqUpdate - stop after get but before put fails right
[39m
[32m# 20. #_doImmediateSeqUpdate - stop after get but before put fails right
[39m
[33mDEBUG localSeqManager: Got an error trying to update seq {"onPut":true}
[39m
[33mok 60 stop caused us to fail
[39m
[33mok 61 We specifically failed on a stop before put
[39m
[33m# teardown
[39m
[36mDEBUG localSeqManager: Got an error trying to update seq {"onPut":true}
[39m
[36mok 60 stop caused us to fail
ok 61 We specifically failed on a stop before put
[39m
[36m# teardown
[39m
[32mDEBUG localSeqManager: Got an error trying to update seq {"onPut":true}
[39m
[32mok 60 stop caused us to fail
[39m
[32mok 61 We specifically failed on a stop before put
[39m
[32m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:39:31.282Z - info: Running on ios test: 21. #update - fail if stop is called

[32m# 21. #update - fail if stop is called
[39m
[36m# 21. #update - fail if stop is called
[39m
[33m# 21. #update - fail if stop is called
[39m
[32mok 62 failed due to stop
ok 63 failed due to stop
# teardown
[39m
[36mok 62 failed due to stop
ok 63 failed due to stop
# teardown
[39m
[33mok 62 failed due to stop
[39m
[33mok 63 failed due to stop
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:39:31.325Z - info: Running on ios test: 22. #update - set seq for first time

[32m# 22. #update - set seq for first time
[39m
[36m# 22. #update - set seq for first time
[39m
[33m# 22. #update - set seq for first time
[39m
[36mok 64 should be equal
[39m
[36m# teardown
[39m
[33mok 64 should be equal
[39m
[33m# teardown
[39m
[32mok 64 should be equal
[39m
[32m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-16T07:39:31.458Z - info: Running on ios test: 23. #update - Fail on bad seq value

[36m# 23. #update - Fail on bad seq value
[39m
[33m# 23. #update - Fail on bad seq value
[39m
[32m# 23. #update - Fail on bad seq value
[39m
[33mDEBUG localSeqManager: Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10
ok 65 Expected bad seq error
[39m
[33m# teardown
[39m
[36mDEBUG localSeqManager: Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10
[39m
[36mok 65 Expected bad seq error
# teardown
[39m
[32mDEBUG localSeqManager: Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10
[39m
[32mok 65 Expected bad seq error
[39m
[32m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-16T07:39:31.572Z - info: Running on ios test: 24. #update - do we cancel timer properly on an immediate?

[36m# 24. #update - do we cancel timer properly on an immediate?
[39m
[32m# 24. #update - do we cancel timer properly on an immediate?
[39m
[33m# 24. #update - do we cancel timer properly on an immediate?
[39m
[33mok 66 Different promises
[39m
[33mok 67 Timer was cancelled
[39m
[33mok 68 should be equal
[39m
[33m# teardown
[39m
[32mok 66 Different promises
[39m
[32mok 67 Timer was cancelled
[39m
[36mok 66 Different promises
[39m
[36mok 67 Timer was cancelled
[39m
[32mok 68 should be equal
[39m
[32m# teardown
[39m
[36mok 68 should be equal
[39m
[36m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:39:31.727Z - info: Running on ios test: 25. #update - do we wait for blocked update

[32m# 25. #update - do we wait for blocked update
[39m
[36m# 25. #update - do we wait for blocked update
[39m
[33m# 25. #update - do we wait for blocked update
[39m
[32mok 69 One go and one blocked
[39m
[32mok 70 All blocked
[39m
[36mok 69 One go and one blocked
ok 70 All blocked
[39m
[36mok 71 Still blocked
[39m
[32mok 71 Still blocked
[39m
[36mok 72 should be equal
[39m
[33mok 69 One go and one blocked
ok 70 All blocked
ok 71 Still blocked
[39m
[36m# teardown
[39m
[32mok 72 should be equal
[39m
[32m# teardown
[39m
[33mok 72 should be equal
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:39:31.850Z - info: Running on ios test: 26. #update - test that we wait long enough

[32m# 26. #update - test that we wait long enough
[39m
[36m# 26. #update - test that we wait long enough
[39m
[33m# 26. #update - test that we wait long enough
[39m
[32mok 73 We waited long enough
[39m
[36mok 73 We waited long enough
[39m
[36mok 74 should be equal
# teardown
[39m
[32mok 74 should be equal
# teardown
[39m
[33mok 73 We waited long enough
[39m
[33mok 74 should be equal
[39m
[33m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-16T07:39:32.943Z - info: Running on ios test: 27. #update - test that we pick up new sequences while we wait

[36m# 27. #update - test that we pick up new sequences while we wait
[39m
[32m# 27. #update - test that we pick up new sequences while we wait
[39m
[33m# 27. #update - test that we pick up new sequences while we wait
[39m
[36mok 75 Should have gotten same timer promise
ok 76 Still same timer promise
[39m
[32mok 75 Should have gotten same timer promise
ok 76 Still same timer promise
[39m
[33mok 75 Should have gotten same timer promise
[39m
[33mok 76 Still same timer promise
[39m
[32mok 77 We waited long enough
[39m
[36mok 77 We waited long enough
[39m
[32mok 78 should be equal
# teardown
[39m
[33mok 77 We waited long enough
[39m
[36mok 78 should be equal
# teardown
[39m
[33mok 78 should be equal
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:39:34.017Z - info: Running on ios test: 28. Coordinated seq test

[32m# 28. Coordinated seq test
[39m
[36m# 28. Coordinated seq test
[39m
[33m# 28. Coordinated seq test
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50914
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50919
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50920
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[36mDEBUG createPeerListener: first connection
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createNativeListener: new incoming socket
[39m
[33mDEBUG createNativeListener: creating incoming mux
[39m
[33mDEBUG createNativeListener: new mux
[39m
[33mDEBUG createNativeListener: new incoming socket
[39m
[33mDEBUG createNativeListener: creating incoming mux
[39m
[33mDEBUG createNativeListener: new mux
[39m
[33mDEBUG createPeerListener: first connection
[39m
[33mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[33mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createPeerListener: forward connection
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: 
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: 
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: 
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: 
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: 
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: 
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[36mok 79 should be equal
[39m
[32mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[32mok 79 should be equal
[39m
[36mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[32mok 80 should be equal
# teardown
DEBUG createNativeListener: stream close:
[39m
[33mok 79 should be equal
[39m
[36mDEBUG createPeerListener: error on incoming stream - Error: Channel destroyed
[39m
[32mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createPeerListener: error on incoming stream - Error: Channel destroyed
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createPeerListener: error on incoming stream - Error: Channel destroyed
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mok 80 should be equal
[39m
[36m# teardown
[39m
[33mok 80 should be equal
[39m
[33m# teardown
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[32mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: mux close
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: mux close
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[33mDEBUG wifiBasedNativeMock: error on peerConnections socket for urn:uuid:4c3097a6-7583-432d-bc69-fe46a227aea2, err - Error: read ECONNRESET
[39m
[32mDEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNRESET","status":500}
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[32mDEBUG testUtils: Got an err - Error: socket hang up -1
[39m
[36mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[32m# setup
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNRESET","status":500}
[39m
[36mDEBUG testUtils: Got an err - Error: socket hang up
[39m
[36m# setup
[39m
[33mDEBUG createPeerListener: Recreating listener
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNRESET","status":500}
[39m
[33mDEBUG testUtils: Got an err - Error: socket hang up -1
[39m
[33mDEBUG createPeerListener: first connection
[39m
[33mDEBUG createPeerListener: Recreating listener
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: first connection
[39m
[33mWARN createPeerListener: 
[39m
[33mDEBUG createPeerListener: failedConnection
[39m
[33mDEBUG createPeerListener: Recreating listener
[39m
[33mDEBUG createPeerListener: failed incoming connection because of mux promise failure - Error: Connection could not be established
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[33mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mWARN createPeerListener: 
[39m
[33mDEBUG createPeerListener: failedConnection
[39m
[33mDEBUG createPeerListener: failed incoming connection because of mux promise failure - Error: Connection could not be established
[39m
[33m# setup
[39m
2016-08-16T07:39:35.361Z - info: Running on ios test: 29. closeAll can close even when connections open

[32m# 29. closeAll can close even when connections open
[39m
[36m# 29. closeAll can close even when connections open
[39m
[33m# 29. closeAll can close even when connections open
[39m
[32mok 81 not possible to connect to the server anymore
[39m
[32m# teardown
[39m
[36mok 81 not possible to connect to the server anymore
[39m
[36m# teardown
[39m
[33mok 81 not possible to connect to the server anymore
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:39:35.495Z - info: Running on ios test: 30. closeAll with promise

[32m# 30. closeAll with promise
[39m
[36m# 30. closeAll with promise
[39m
[33m# 30. closeAll with promise
[39m
[36mok 82 not possible to connect to the server anymore
# teardown
[39m
[33mok 82 not possible to connect to the server anymore
# teardown
[39m
[32mok 82 not possible to connect to the server anymore
# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-16T07:39:35.628Z - info: Running on ios test: 31. closeAll properly throws when closing a non open server with eatNotRunning set to false

[32m# 31. closeAll properly throws when closing a non open server with eatNotRunning set to false
[39m
[36m# 31. closeAll properly throws when closing a non open server with eatNotRunning set to false
[39m
[33m# 31. closeAll properly throws when closing a non open server with eatNotRunning set to false
[39m
[32mok 83 Got the right error
# teardown
[39m
[33mok 83 Got the right error
# teardown
[39m
[36mok 83 Got the right error
[39m
[36m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:39:35.760Z - info: Running on ios test: 32. closeAll works even with a server that is not listening yet witheatNotRunning set to true

[32m# 32. closeAll works even with a server that is not listening yet witheatNotRunning set to true
[39m
[36m# 32. closeAll works even with a server that is not listening yet witheatNotRunning set to true
[39m
[33m# 32. closeAll works even with a server that is not listening yet witheatNotRunning set to true
[39m
[33m# teardown
[39m
[32m# teardown
# setup
[39m
[36m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:39:35.890Z - info: Running on ios test: 33. enqueue and run in order

[36m# 33. enqueue and run in order
[39m
[32m# 33. enqueue and run in order
[39m
[33m# 33. enqueue and run in order
[39m
[32mok 84 firstPromise setTimeout
ok 85 firstPromise result
ok 86 firstPromise testValue
[39m
[33mok 84 firstPromise setTimeout
ok 85 firstPromise result
ok 86 firstPromise testValue
[39m
[36mok 84 firstPromise setTimeout
ok 85 firstPromise result
ok 86 firstPromise testValue
[39m
[32mok 87 secondPromise setTimeout
ok 88 secondPromise result
ok 89 secondPromise testValue
ok 90 thirdPromise in promise
ok 91 thirdPromise result
ok 92 thirdPromise testValue
# teardown
[39m
[33mok 87 secondPromise setTimeout
ok 88 secondPromise result
ok 89 secondPromise testValue
ok 90 thirdPromise in promise
ok 91 thirdPromise result
ok 92 thirdPromise testValue
# teardown
[39m
[36mok 87 secondPromise setTimeout
ok 88 secondPromise result
ok 89 secondPromise testValue
ok 90 thirdPromise in promise
[39m
[36mok 91 thirdPromise result
ok 92 thirdPromise testValue
[39m
[36m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-16T07:39:36.129Z - info: Running on ios test: 34. enqueueAtTop and run backwards

[32m# 34. enqueueAtTop and run backwards
[39m
[36m# 34. enqueueAtTop and run backwards
[39m
[33m# 34. enqueueAtTop and run backwards
[39m
[32mok 93 thirdPromise - first to run
ok 94 thirdPromise - in resolve
ok 95 secondPromise - second to run
ok 96 secondPromise - in catch
ok 97 firstPromise - third to run
ok 98 firstPromise - in then
ok 99 testing promises
# teardown
[39m
[36mok 93 thirdPromise - first to run
ok 94 thirdPromise - in resolve
ok 95 secondPromise - second to run
ok 96 secondPromise - in catch
ok 97 firstPromise - third to run
ok 98 firstPromise - in then
ok 99 testing promises
# teardown
[39m
[33mok 93 thirdPromise - first to run
ok 94 thirdPromise - in resolve
ok 95 secondPromise - second to run
ok 96 secondPromise - in catch
ok 97 firstPromise - third to run
[39m
[33mok 98 firstPromise - in then
ok 99 testing promises
# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:39:36.155Z - info: Running on ios test: 35. mix enqueue and enqueueAtTop

[32m# 35. mix enqueue and enqueueAtTop
[39m
[36m# 35. mix enqueue and enqueueAtTop
[39m
[33m# 35. mix enqueue and enqueueAtTop
[39m
[32mok 100 fourth
ok 101 fourth
ok 102 second
ok 103 secondPromise - in then
[39m
[36mok 100 fourth
ok 101 fourth
ok 102 second
ok 103 secondPromise - in then
[39m
[33mok 100 fourth
ok 101 fourth
ok 102 second
ok 103 secondPromise - in then
[39m
[33mok 104 first
ok 105 firstPromise - in catch
ok 106 third
ok 107 thirdPromise - in then
ok 108 testingPromises
# teardown
[39m
[32mok 104 first
ok 105 firstPromise - in catch
ok 106 third
ok 107 thirdPromise - in then
ok 108 testingPromises
# teardown
[39m
[36mok 104 first
ok 105 firstPromise - in catch
[39m
[36mok 106 third
ok 107 thirdPromise - in then
ok 108 testingPromises
# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:39:36.288Z - info: Running on ios test: 36. queues handled independently

[32m# 36. queues handled independently
[39m
[36m# 36. queues handled independently
[39m
[33m# 36. queues handled independently
[39m
[36mok 109 all short operations completed before the long resolves
# teardown
[39m
[32mok 109 all short operations completed before the long resolves
# teardown
[39m
[33mok 109 all short operations completed before the long resolves
# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:39:36.359Z - info: Running on ios test: 37. basic

[32m# 37. basic
[39m
[36m# 37. basic
[39m
[33m# 37. basic
[39m
[32mok 110 sane
# teardown
[39m
[36mok 110 sane
# teardown
[39m
[33mok 110 sane
# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-16T07:39:36.385Z - info: Running on ios test: 38. another

[32m# 38. another
[39m
[36m# 38. another
[39m
[33m# 38. another
[39m
[36mok 111 sane
[39m
[32mok 111 sane
[39m
[36m# teardown
[39m
[32m# teardown
[39m
[33mok 111 sane
[39m
[33m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-16T07:39:36.411Z - info: Running on ios test: 39. can pass data in setup

[36m# 39. can pass data in setup
[39m
[32m# 39. can pass data in setup
[39m
[33m# 39. can pass data in setup
[39m
[32m[{"uuid":"b85f0e42-f4f3-40d9-abe4-92e212f9c537","data":"custom data"},{"uuid":"e1cf421e-f4d3-45f2-8ce8-347e8346adcb","data":"custom data"},{"uuid":"c49b150c-30bd-4400-a254-fc6f975434b3","data":"custom data"}]
[39m
[36m[{"uuid":"b85f0e42-f4f3-40d9-abe4-92e212f9c537","data":"custom data"},{"uuid":"e1cf421e-f4d3-45f2-8ce8-347e8346adcb","data":"custom data"},{"uuid":"c49b150c-30bd-4400-a254-fc6f975434b3","data":"custom data"}]
[39m
[32mok 112 test participant has uuid
[39m
[36mok 112 test participant has uuid
[39m
[32mok 113 participant data matches
[39m
[36mok 113 participant data matches
[39m
[36mok 114 test participant has uuid
ok 115 participant data matches
[39m
[32mok 114 test participant has uuid
[39m
[36mok 116 test participant has uuid
[39m
[32mok 115 participant data matches
[39m
[32mok 116 test participant has uuid
[39m
[36mok 117 participant data matches
[39m
[36mok 118 own UUID is found from the participants list
[39m
[32mok 117 participant data matches
[39m
[32mok 118 own UUID is found from the participants list
[39m
[32m# teardown
[39m
[36m# teardown
[39m
[33m[{"uuid":"b85f0e42-f4f3-40d9-abe4-92e212f9c537","data":"custom data"},{"uuid":"e1cf421e-f4d3-45f2-8ce8-347e8346adcb","data":"custom data"},{"uuid":"c49b150c-30bd-4400-a254-fc6f975434b3","data":"custom data"}]
[39m
[33mok 112 test participant has uuid
[39m
[33mok 113 participant data matches
[39m
[33mok 114 test participant has uuid
[39m
[33mok 115 participant data matches
[39m
[33mok 116 test participant has uuid
[39m
[33mok 117 participant data matches
[39m
[33mok 118 own UUID is found from the participants list
[39m
[33m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-16T07:39:36.443Z - info: Running on ios test: 40. can continue after disconnect from server

[33m# 40. can continue after disconnect from server
[39m
[36m# 40. can continue after disconnect from server
[39m
[32m# 40. can continue after disconnect from server
[39m
[33mDisconnected from the test server
[39m
[36mDisconnected from the test server
[39m
[32mDisconnected from the test server
[39m
2016-08-16T07:39:36.461Z - info: Socket to device 7908f98f-c49a-41d6-ae68-11527ecf517c disconnected: client namespace disconnect

2016-08-16T07:39:36.465Z - info: Socket to device 6140f2bb-3ced-4f37-922e-8a80dec969c0 disconnected: client namespace disconnect

2016-08-16T07:39:36.469Z - info: Socket to device 0a79a281-dea2-4a2a-a650-0d351e01ba0c disconnected: client namespace disconnect

[32mConnected to the test server
ok 119 got connect event
# teardown
[39m
[33mConnected to the test server
ok 119 got connect event
# teardown
[39m
[36mConnected to the test server
ok 119 got connect event
# teardown
[39m
2016-08-16T07:39:36.988Z - debug: Device presented: 0a79a281-dea2-4a2a-a650-0d351e01ba0c (b85f0e42-f4f3-40d9-abe4-92e212f9c537) - ios dummy
2016-08-16T07:39:36.988Z - info: Updating existing device: 0a79a281-dea2-4a2a-a650-0d351e01ba0c (b85f0e42-f4f3-40d9-abe4-92e212f9c537)
2016-08-16T07:39:36.988Z - debug: Device presented: 7908f98f-c49a-41d6-ae68-11527ecf517c (c49b150c-30bd-4400-a254-fc6f975434b3) - ios dummy
2016-08-16T07:39:36.988Z - info: Updating existing device: 7908f98f-c49a-41d6-ae68-11527ecf517c (c49b150c-30bd-4400-a254-fc6f975434b3)

2016-08-16T07:39:36.991Z - debug: Device presented: 6140f2bb-3ced-4f37-922e-8a80dec969c0 (e1cf421e-f4d3-45f2-8ce8-347e8346adcb) - ios dummy

2016-08-16T07:39:36.991Z - info: Updating existing device: 6140f2bb-3ced-4f37-922e-8a80dec969c0 (e1cf421e-f4d3-45f2-8ce8-347e8346adcb)

[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:39:37.000Z - info: Running on ios test: 41. test after disconnect

[32m# 41. test after disconnect
[39m
[36m# 41. test after disconnect
[39m
[33m# 41. test after disconnect
[39m
[32mok 120 worked
# teardown
[39m
[36mok 120 worked
# teardown
[39m
[33mok 120 worked
# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:39:37.024Z - info: Running on ios test: 42. #startListeningForAdvertisements should fail if start not called

[32m# 42. #startListeningForAdvertisements should fail if start not called
[39m
[36m# 42. #startListeningForAdvertisements should fail if start not called
[39m
[33m# 42. #startListeningForAdvertisements should fail if start not called
[39m
[36mok 121 specific error should be returned
# teardown
[39m
[32mok 121 specific error should be returned
# teardown
[39m
[33mok 121 specific error should be returned
[39m
[33m# teardown
[39m
[36mok 122 error should be null
ok 123 error should be null
# setup
[39m
[32mok 122 error should be null
ok 123 error should be null
# setup
[39m
[33mok 122 error should be null
[39m
[33mok 123 error should be null
[39m
[33m# setup
[39m
2016-08-16T07:39:37.056Z - info: Running on ios test: 43. #startUpdateAdvertisingAndListening should fail if start not called

[36m# 43. #startUpdateAdvertisingAndListening should fail if start not called
[39m
[32m# 43. #startUpdateAdvertisingAndListening should fail if start not called
[39m
[33m# 43. #startUpdateAdvertisingAndListening should fail if start not called
[39m
[36mok 124 specific error should be returned
# teardown
[39m
[32mok 124 specific error should be returned
# teardown
[39m
[33mok 124 specific error should be returned
# teardown
[39m
[36mok 125 error should be null
ok 126 error should be null
# setup
[39m
[33mok 125 error should be null
[39m
[33mok 126 error should be null
[39m
[33m# setup
[39m
[32mok 125 error should be null
ok 126 error should be null
# setup
[39m
2016-08-16T07:39:37.089Z - info: Running on ios test: 44. should be able to call #stopListeningForAdvertisements many times

[36m# 44. should be able to call #stopListeningForAdvertisements many times
[39m
[32m# 44. should be able to call #stopListeningForAdvertisements many times
[39m
[33m# 44. should be able to call #stopListeningForAdvertisements many times
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51055
ok 127 error should be null
ok 128 error should be null
ok 129 error should be null
ok 130 error should be null
# teardown
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51056
ok 127 error should be null
ok 128 error should be null
ok 129 error should be null
ok 130 error should be null
# teardown
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: listening 51058
[39m
[33mok 127 error should be null
[39m
[33mok 128 error should be null
[39m
[33mok 129 error should be null
[39m
[33mok 130 error should be null
[39m
[33m# teardown
[39m
[36mok 131 error should be null
ok 132 error should be null
# setup
[39m
[32mok 131 error should be null
ok 132 error should be null
# setup
[39m
[33mok 131 error should be null
ok 132 error should be null
[39m
[33m# setup
[39m
2016-08-16T07:39:37.129Z - info: Running on ios test: 45. should be able to call #startListeningForAdvertisements many times

[32m# 45. should be able to call #startListeningForAdvertisements many times
[39m
[36m# 45. should be able to call #startListeningForAdvertisements many times
[39m
[33m# 45. should be able to call #startListeningForAdvertisements many times
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51060
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 133 error should be null
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[36mok 134 error should be null
[39m
[32mDEBUG createNativeListener: listening 51062
[39m
[36mok 135 error should be null
ok 136 error should be null
# teardown
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 133 error should be null
[39m
[32mok 134 error should be null
[39m
[32mok 135 error should be null
ok 136 error should be null
# teardown
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: listening 51064
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[33mok 133 error should be null
[39m
[33mok 134 error should be null
[39m
[33mok 135 error should be null
[39m
[33mok 136 error should be null
[39m
[33m# teardown
[39m
[32mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[36mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 137 error should be null
ok 138 error should be null
[39m
[36m# setup
[39m
[32mok 137 error should be null
[39m
[32mok 138 error should be null
[39m
[32m# setup
[39m
[33mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mok 137 error should be null
[39m
[33mok 138 error should be null
[39m
[33m# setup
[39m
2016-08-16T07:39:37.169Z - info: Running on ios test: 46. should be able to call #startUpdateAdvertisingAndListening many times

[33m# 46. should be able to call #startUpdateAdvertisingAndListening many times
[39m
[32m# 46. should be able to call #startUpdateAdvertisingAndListening many times
[39m
[36m# 46. should be able to call #startUpdateAdvertisingAndListening many times
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51066
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 139 error should be null
ok 140 error should be null
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51068
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 139 error should be null
ok 140 error should be null
[39m
[36mok 141 error should be null
[39m
[36mok 142 error should be null
[39m
[36m# teardown
[39m
[32mok 141 error should be null
[39m
[32mok 142 error should be null
[39m
[32m# teardown
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: listening 51076
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[33mok 139 error should be null
[39m
[33mok 140 error should be null
[39m
[33mok 141 error should be null
ok 142 error should be null
[39m
[33m# teardown
[39m
[32mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[36mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 143 error should be null
ok 144 error should be null
[39m
[32mok 143 error should be null
ok 144 error should be null
# setup
[39m
[36m# setup
[39m
[33mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mok 143 error should be null
[39m
[33mok 144 error should be null
[39m
[33m# setup
[39m
2016-08-16T07:39:37.226Z - info: Running on ios test: 47. should be able to call #stopAdvertisingAndListening many times

[32m# 47. should be able to call #stopAdvertisingAndListening many times
[39m
[36m# 47. should be able to call #stopAdvertisingAndListening many times
[39m
[33m# 47. should be able to call #stopAdvertisingAndListening many times
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: listening 51083
[39m
[36mDEBUG createNativeListener: listening 51082
[39m
[36mok 145 error should be null
[39m
[32mok 145 error should be null
[39m
[32mok 146 error should be null
[39m
[36mok 146 error should be null
[39m
[32mok 147 error should be null
[39m
[32mok 148 error should be null
[39m
[32m# teardown
[39m
[36mok 147 error should be null
[39m
[36mok 148 error should be null
[39m
[36m# teardown
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: listening 51085
[39m
[33mok 145 error should be null
[39m
[33mok 146 error should be null
[39m
[33mok 147 error should be null
[39m
[33mok 148 error should be null
[39m
[33m# teardown
[39m
[33mok 149 error should be null
ok 150 error should be null
[39m
[33m# setup
[39m
[36mok 149 error should be null
[39m
[36mok 150 error should be null
[39m
[36m# setup
[39m
[32mok 149 error should be null
[39m
[32mok 150 error should be null
[39m
[32m# setup
[39m
2016-08-16T07:39:37.267Z - info: Running on ios test: 48. #start should fail if called twice in a row

[32m# 48. #start should fail if called twice in a row
[39m
[33m# 48. #start should fail if called twice in a row
[39m
[36m# 48. #start should fail if called twice in a row
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: listening 51087
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[32mok 151 first call should succeed
[39m
[33mDEBUG createNativeListener: listening 51089
[39m
[33mok 151 first call should succeed
[39m
[33mok 152 first call should succeed
[39m
[33mok 153 specific error should be returned
[39m
[33m# teardown
[39m
[32mok 152 first call should succeed
[39m
[32mok 153 specific error should be returned
[39m
[32m# teardown
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: listening 51091
[39m
[36mok 151 first call should succeed
[39m
[36mok 152 first call should succeed
[39m
[36mok 153 specific error should be returned
[39m
[36m# teardown
[39m
[32mok 154 error should be null
[39m
[32mok 155 error should be null
[39m
[36mok 154 error should be null
[39m
[36mok 155 error should be null
[39m
[36m# setup
[39m
[32m# setup
[39m
[33mok 154 error should be null
ok 155 error should be null
[39m
[33m# setup
[39m
2016-08-16T07:39:37.312Z - info: Running on ios test: 49. does not emit duplicate discoveryAdvertisingStateUpdate

[36m# 49. does not emit duplicate discoveryAdvertisingStateUpdate
[39m
[32m# 49. does not emit duplicate discoveryAdvertisingStateUpdate
[39m
[33m# 49. does not emit duplicate discoveryAdvertisingStateUpdate
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: listening 51093
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[36mok 156 called only once
[39m
[36mok 157 discovery state matches
[39m
[36mok 158 advertising state matches
[39m
[36m# teardown
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51098
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 156 called only once
ok 157 discovery state matches
ok 158 advertising state matches
# teardown
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51100
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mok 156 called only once
[39m
[33mok 157 discovery state matches
[39m
[33mok 158 advertising state matches
[39m
[33m# teardown
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[36mINFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[32mINFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[32mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[36mok 159 error should be null
[39m
[36mok 160 error should be null
[39m
[36m# setup
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 159 error should be null
ok 160 error should be null
# setup
[39m
[33mINFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
[39m
[33mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mok 159 error should be null
[39m
[33mok 160 error should be null
[39m
[33m# setup
[39m
2016-08-16T07:39:37.390Z - info: Running on ios test: 50. does not send duplicate availability changes

[36m# 50. does not send duplicate availability changes
[39m
[32m# 50. does not send duplicate availability changes
[39m
[33m# 50. does not send duplicate availability changes
[39m
[36mok 161 should be called once
ok 162 should not have been called more than once
# teardown
[39m
[32mok 161 should be called once
ok 162 should not have been called more than once
# teardown
[39m
[33mok 161 should be called once
[39m
[33mok 162 should not have been called more than once
[39m
[33m# teardown
[39m
[32mok 163 error should be null
[39m
[32mok 164 error should be null
# setup
[39m
[36mok 163 error should be null
[39m
[36mok 164 error should be null
[39m
[36m# setup
[39m
[33mok 163 error should be null
ok 164 error should be null
[39m
[33m# setup
[39m
2016-08-16T07:39:37.426Z - info: Running on ios test: 51. can get the network status

[32m# 51. can get the network status
[39m
[36m# 51. can get the network status
[39m
[33m# 51. can get the network status
[39m
[32mok 165 network status should have certain non-empty properties
[39m
[36mok 165 network status should have certain non-empty properties
[39m
[32m# teardown
[39m
[36m# teardown
[39m
[33mok 165 network status should have certain non-empty properties
[39m
[33m# teardown
[39m
[32mok 166 error should be null
[39m
[32mok 167 error should be null
[39m
[32m# setup
[39m
[33mok 166 error should be null
[39m
[33mok 167 error should be null
[39m
[33m# setup
[39m
[36mok 166 error should be null
[39m
[36mok 167 error should be null
[39m
[36m# setup
[39m
2016-08-16T07:39:37.453Z - info: Running on ios test: 52. wifi peer is marked unavailable if announcements stop

[32m# 52. wifi peer is marked unavailable if announcements stop
[39m
[33m# 52. wifi peer is marked unavailable if announcements stop
[39m
[36m# 52. wifi peer is marked unavailable if announcements stop
[39m
[32mERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
[39m
[36mERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
[39m
[32mok 168 host address should match
[39m
[32mok 169 port should match
[39m
[36mok 168 host address should match
[39m
[36mok 169 port should match
[39m
[33mERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
[39m
[33mok 168 host address should match
[39m
[33mok 169 port should match
[39m
[33mok 170 host address should be null
ok 171 port should should be null
[39m
[33m# teardown
[39m
[36mok 170 host address should be null
ok 171 port should should be null
# teardown
[39m
[32mok 170 host address should be null
ok 171 port should should be null
# teardown
[39m
[32mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 172 error should be null
ok 173 error should be null
# setup
[39m
[36mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 172 error should be null
ok 173 error should be null
# setup
[39m
[33mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 172 error should be null
ok 173 error should be null
# setup
[39m
2016-08-16T07:39:39.495Z - info: Running on ios test: 53. network changes emitted correctly

[32m# 53. network changes emitted correctly
[39m
[36m# 53. network changes emitted correctly
[39m
[33m# 53. network changes emitted correctly
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51113
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 174 wifi is off
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 175 wifi is on
# teardown
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51114
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 174 wifi is off
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 175 wifi is on
# teardown
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51116
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mok 174 wifi is off
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 175 wifi is on
[39m
[33m# teardown
[39m
[32mok 176 error should be null
ok 177 error should be null
# setup
[39m
[36mok 176 error should be null
ok 177 error should be null
# setup
[39m
[33mok 176 error should be null
ok 177 error should be null
[39m
[33m# setup
[39m
2016-08-16T07:39:39.529Z - info: Running on ios test: 54. network changes not emitted in stopped state

[36m# 54. network changes not emitted in stopped state
[39m
[32m# 54. network changes not emitted in stopped state
[39m
[33m# 54. network changes not emitted in stopped state
[39m
[32mok 178 event was not emitted
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
# teardown
[39m
[36mok 178 event was not emitted
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
# teardown
[39m
[33mok 178 event was not emitted
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
# teardown
[39m
[36mok 179 error should be null
ok 180 error should be null
# setup
[39m
[32mok 179 error should be null
ok 180 error should be null
# setup
[39m
[33mok 179 error should be null
ok 180 error should be null
[39m
[33m# setup
[39m
2016-08-16T07:39:39.555Z - info: Running on ios test: 55. calls correct starts when network changes

[36m# 55. calls correct starts when network changes
[39m
[32m# 55. calls correct starts when network changes
[39m
[33m# 55. calls correct starts when network changes
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51119
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 181 specific error expected
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 182 specific error expected
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51120
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 181 specific error expected
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 182 specific error expected
DEBUG createPeerListener: createPeerListener creating new server
[39m
[32mINFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":true,"advertisingActive":true}
ok 183 startListeningForAdvertisements should have been called
ok 184 startUpdateAdvertisingAndListening should have been called
# teardown
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51127
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 181 specific error expected
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 182 specific error expected
DEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":true,"advertisingActive":true}
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
ok 183 startListeningForAdvertisements should have been called
ok 184 startUpdateAdvertisingAndListening should have been called
# teardown
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":true,"advertisingActive":true}
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
ok 183 startListeningForAdvertisements should have been called
ok 184 startUpdateAdvertisingAndListening should have been called
# teardown
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[36mINFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 185 error should be null
ok 186 error should be null
# setup
[39m
[32mINFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 185 error should be null
ok 186 error should be null
# setup
[39m
[33mINFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[33mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mok 185 error should be null
[39m
[33mok 186 error should be null
[39m
[33m# setup
[39m
2016-08-16T07:39:39.620Z - info: Running on ios test: 56. peer is marked unavailable if port number changes

[32m# 56. peer is marked unavailable if port number changes
[39m
[36m# 56. peer is marked unavailable if port number changes
[39m
[33m# 56. peer is marked unavailable if port number changes
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51145
ok 187 peer should have a non-empty identifier
ok 188 peer should have a non-empty host address
ok 189 peer should have port number
ok 190 peer should have suggested timeout
ok 191 peer should have a connection type
ok 192 connection type should match one of the pre-defined types
ok 193 peer should have a non-empty identifier
ok 194 host address should be null
ok 195 port number should be null
ok 196 peer should have suggested timeout
ok 197 peer should have a connection type
ok 198 connection type should match one of the pre-defined types
ok 199 port number must match
ok 200 peer should have a non-empty identifier
ok 201 peer should have a non-empty host address
ok 202 peer should have port number
ok 203 peer should have suggested timeout
ok 204 peer should have a connection type
ok 205 connection type should match one of the pre-defined types
# teardown
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51146
ok 187 peer should have a non-empty identifier
ok 188 peer should have a non-empty host address
ok 189 peer should have port number
ok 190 peer should have suggested timeout
ok 191 peer should have a connection type
ok 192 connection type should match one of the pre-defined types
ok 193 peer should have a non-empty identifier
ok 194 host address should be null
ok 195 port number should be null
ok 196 peer should have suggested timeout
ok 197 peer should have a connection type
ok 198 connection type should match one of the pre-defined types
ok 199 port number must match
ok 200 peer should have a non-empty identifier
ok 201 peer should have a non-empty host address
ok 202 peer should have port number
ok 203 peer should have suggested timeout
ok 204 peer should have a connection type
ok 205 connection type should match one of the pre-defined types
# teardown
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: listening 51148
[39m
[33mok 187 peer should have a non-empty identifier
[39m
[33mok 188 peer should have a non-empty host address
[39m
[33mok 189 peer should have port number
[39m
[33mok 190 peer should have suggested timeout
[39m
[33mok 191 peer should have a connection type
ok 192 connection type should match one of the pre-defined types
[39m
[33mok 193 peer should have a non-empty identifier
[39m
[33mok 194 host address should be null
[39m
[33mok 195 port number should be null
[39m
[33mok 196 peer should have suggested timeout
ok 197 peer should have a connection type
[39m
[33mok 198 connection type should match one of the pre-defined types
[39m
[33mok 199 port number must match
[39m
[33mok 200 peer should have a non-empty identifier
[39m
[33mok 201 peer should have a non-empty host address
ok 202 peer should have port number
[39m
[33mok 203 peer should have suggested timeout
ok 204 peer should have a connection type
[39m
[33mok 205 connection type should match one of the pre-defined types
[39m
[33m# teardown
[39m
[32mok 206 error should be null
ok 207 error should be null
# setup
[39m
[36mok 206 error should be null
ok 207 error should be null
# setup
[39m
[33mok 206 error should be null
ok 207 error should be null
# setup
[39m
2016-08-16T07:39:39.655Z - info: Running on ios test: 57. when network connection is lost a peer should be marked unavailable

[32m# 57. when network connection is lost a peer should be marked unavailable
[39m
[36m# 57. when network connection is lost a peer should be marked unavailable
[39m
[33m# 57. when network connection is lost a peer should be marked unavailable
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51151
INFO testUtils: Toggling radios to: false
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 208 peer should have a non-empty identifier
ok 209 host address should be null
ok 210 port number should be null
ok 211 peer should have suggested timeout
ok 212 peer should have a connection type
ok 213 connection type should match one of the pre-defined types
INFO testUtils: Toggling radios to: true
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
# teardown
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51152
INFO testUtils: Toggling radios to: false
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 208 peer should have a non-empty identifier
ok 209 host address should be null
ok 210 port number should be null
ok 211 peer should have suggested timeout
ok 212 peer should have a connection type
ok 213 connection type should match one of the pre-defined types
INFO testUtils: Toggling radios to: true
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
# teardown
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: listening 51154
[39m
[36mINFO testUtils: Toggling radios to: false
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mok 208 peer should have a non-empty identifier
[39m
[36mok 209 host address should be null
ok 210 port number should be null
ok 211 peer should have suggested timeout
ok 212 peer should have a connection type
ok 213 connection type should match one of the pre-defined types
[39m
[36mINFO testUtils: Toggling radios to: true
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36m# teardown
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[32mok 214 error should be null
ok 215 error should be null
# setup
[39m
[36mok 214 error should be null
ok 215 error should be null
# setup
[39m
[33mok 214 error should be null
ok 215 error should be null
[39m
[33m# setup
[39m
2016-08-16T07:39:39.690Z - info: Running on ios test: 58. peer should be found once after listening and discovery started

[32m# 58. peer should be found once after listening and discovery started
[39m
[36m# 58. peer should be found once after listening and discovery started
[39m
[33m# 58. peer should be found once after listening and discovery started
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51157
ok 216 error should be null
ok 217 error should be null
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 218 error should be null
ok 219 error should be null
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 220 error should be null
ok 221 error should be null
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51158
ok 216 error should be null
ok 217 error should be null
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 218 error should be null
ok 219 error should be null
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 220 error should be null
ok 221 error should be null
[39m
[32mok 222 peer should have a non-empty identifier
ok 223 peer should have a non-empty host address
ok 224 peer should have port number
ok 225 peer should have suggested timeout
ok 226 peer should have a connection type
ok 227 connection type should match one of the pre-defined types
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51166
ok 216 error should be null
ok 217 error should be null
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 218 error should be null
ok 219 error should be null
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 220 error should be null
ok 221 error should be null
[39m
[36mok 222 peer should have a non-empty identifier
ok 223 peer should have a non-empty host address
ok 224 peer should have port number
ok 225 peer should have suggested timeout
ok 226 peer should have a connection type
ok 227 connection type should match one of the pre-defined types
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[33mok 222 peer should have a non-empty identifier
ok 223 peer should have a non-empty host address
ok 224 peer should have port number
ok 225 peer should have suggested timeout
ok 226 peer should have a connection type
ok 227 connection type should match one of the pre-defined types
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mok 228 must not receive too many peer availabilities
# teardown
[39m
[32mok 228 must not receive too many peer availabilities
# teardown
[39m
[33mok 228 must not receive too many peer availabilities
[39m
[33m# teardown
[39m
[36mINFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 229 error should be null
ok 230 error should be null
# setup
[39m
[32mINFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 229 error should be null
ok 230 error should be null
# setup
[39m
[33mINFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
[39m
[33mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[33mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mok 229 error should be null
[39m
[33mok 230 error should be null
[39m
[33m# setup
[39m
2016-08-16T07:39:43.246Z - info: Running on ios test: 59. can get data from all participants

[32m# 59. can get data from all participants
[39m
[36m# 59. can get data from all participants
[39m
[33m# 59. can get data from all participants
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51178
ok 231 error should be null
ok 232 error should be null
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 233 error should be null
ok 234 error should be null
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 235 error should be null
ok 236 error should be null
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51179
ok 231 error should be null
ok 232 error should be null
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 233 error should be null
ok 234 error should be null
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 235 error should be null
ok 236 error should be null
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51190
ok 231 error should be null
ok 232 error should be null
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 233 error should be null
ok 234 error should be null
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 235 error should be null
ok 236 error should be null
[39m
[36mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createPeerListener: first connection
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG wifiBasedNativeMock: proxy socket connected
DEBUG createPeerListener: first connection
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createPeerListener: first connection
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG createNativeListener: new incoming socket
[39m
[33mDEBUG createNativeListener: creating incoming mux
[39m
[33mDEBUG createNativeListener: new mux
[39m
[33mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG createNativeListener: new incoming socket
[39m
[33mDEBUG createNativeListener: creating incoming mux
[39m
[33mDEBUG createNativeListener: new mux
[39m
[33mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG createPeerListener: forward connection
DEBUG createPeerListener: forward connection
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createPeerListener: forward connection
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[36mok 237 received uuid must be in remaining list
[39m
[32mok 237 received uuid must be in remaining list
[39m
[36mok 238 received uuid must be in remaining list
ok 239 received all uuids
# teardown
[39m
[32mok 238 received uuid must be in remaining list
ok 239 received all uuids
# teardown
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: first connection
[39m
[33mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG createPeerListener: forward connection
[39m
[33mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[33mok 237 received uuid must be in remaining list
[39m
[33mok 238 received uuid must be in remaining list
[39m
[33mok 239 received all uuids
[39m
[33m# teardown
[39m
[32mINFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
ok 240 error should be null
ok 241 error should be null
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
# setup
[39m
[36mINFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
ok 240 error should be null
ok 241 error should be null
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
# setup
[39m
[33mDEBUG createPeerListener: Recreating listener
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: Recreating listener
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mINFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
[39m
[33mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[33mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mok 240 error should be null
[39m
[33mok 241 error should be null
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33m# setup
[39m
2016-08-16T07:39:43.944Z - info: Running on ios test: 60. Can call start/stopListeningForAdvertisements

[36m# 60. Can call start/stopListeningForAdvertisements
[39m
[32m# 60. Can call start/stopListeningForAdvertisements
[39m
[33m# 60. Can call start/stopListeningForAdvertisements
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 242 Can call startListeningForAdvertisements without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 243 Can call stopListeningForAdvertisements without error
# teardown
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 242 Can call startListeningForAdvertisements without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 243 Can call stopListeningForAdvertisements without error
# teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 242 Can call startListeningForAdvertisements without error
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mok 243 Can call stopListeningForAdvertisements without error
[39m
[33m# teardown
[39m
[32mok 244 Should be able to call stopListeningForAdvertisements in teardown
ok 245 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[36mok 244 Should be able to call stopListeningForAdvertisements in teardown
ok 245 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[33mok 244 Should be able to call stopListeningForAdvertisements in teardown
ok 245 Should be able to call stopAdvertisingAndListening in teardown
[39m
[33m# setup
[39m
2016-08-16T07:39:43.969Z - info: Running on ios test: 61. Calling startListeningForAdvertisements twice is NOT an error

[32m# 61. Calling startListeningForAdvertisements twice is NOT an error
[39m
[36m# 61. Calling startListeningForAdvertisements twice is NOT an error
[39m
[33m# 61. Calling startListeningForAdvertisements twice is NOT an error
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 246 Can call startListeningForAdvertisements without error
ok 247 Can call startListeningForAdvertisements twice without error
# teardown
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 246 Can call startListeningForAdvertisements without error
ok 247 Can call startListeningForAdvertisements twice without error
# teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 246 Can call startListeningForAdvertisements without error
ok 247 Can call startListeningForAdvertisements twice without error
[39m
[33m# teardown
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 248 Should be able to call stopListeningForAdvertisements in teardown
ok 249 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 248 Should be able to call stopListeningForAdvertisements in teardown
ok 249 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 248 Should be able to call stopListeningForAdvertisements in teardown
ok 249 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
2016-08-16T07:39:43.994Z - info: Running on ios test: 62. Calling stopListeningForAdvertisements without calling start is NOT an error

[36m# 62. Calling stopListeningForAdvertisements without calling start is NOT an error
[39m
[32m# 62. Calling stopListeningForAdvertisements without calling start is NOT an error
[39m
[33m# 62. Calling stopListeningForAdvertisements without calling start is NOT an error
[39m
[36mok 250 Can call stopListeningForAdvertisements without error
ok 251 Can call stopListeningForAdvertisements without error
# teardown
[39m
[32mok 250 Can call stopListeningForAdvertisements without error
ok 251 Can call stopListeningForAdvertisements without error
# teardown
[39m
[33mok 250 Can call stopListeningForAdvertisements without error
ok 251 Can call stopListeningForAdvertisements without error
# teardown
[39m
[32mok 252 Should be able to call stopListeningForAdvertisements in teardown
ok 253 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[36mok 252 Should be able to call stopListeningForAdvertisements in teardown
ok 253 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[33mok 252 Should be able to call stopListeningForAdvertisements in teardown
ok 253 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
2016-08-16T07:39:44.021Z - info: Running on ios test: 63. Can call start/stopUpdateAdvertisingAndListening

[32m# 63. Can call start/stopUpdateAdvertisingAndListening
[39m
[36m# 63. Can call start/stopUpdateAdvertisingAndListening
[39m
[33m# 63. Can call start/stopUpdateAdvertisingAndListening
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 254 Can call startUpdateAdvertisingAndListening without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 255 Can call stopAdvertisingAndListening without error
# teardown
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 254 Can call startUpdateAdvertisingAndListening without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 255 Can call stopAdvertisingAndListening without error
# teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[33mok 254 Can call startUpdateAdvertisingAndListening without error
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mok 255 Can call stopAdvertisingAndListening without error
[39m
[33m# teardown
[39m
[36mok 256 Should be able to call stopListeningForAdvertisements in teardown
ok 257 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[32mok 256 Should be able to call stopListeningForAdvertisements in teardown
ok 257 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[33mok 256 Should be able to call stopListeningForAdvertisements in teardown
[39m
[33mok 257 Should be able to call stopAdvertisingAndListening in teardown
[39m
[33m# setup
[39m
2016-08-16T07:39:44.052Z - info: Running on ios test: 64. Calling startUpdateAdvertisingAndListening twice is NOT an error

[32m# 64. Calling startUpdateAdvertisingAndListening twice is NOT an error
[39m
[36m# 64. Calling startUpdateAdvertisingAndListening twice is NOT an error
[39m
[33m# 64. Calling startUpdateAdvertisingAndListening twice is NOT an error
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 258 Can call startUpdateAdvertisingAndListening without error
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 258 Can call startUpdateAdvertisingAndListening without error
[39m
[36mok 259 Can call startUpdateAdvertisingAndListening twice without error
# teardown
[39m
[32mok 259 Can call startUpdateAdvertisingAndListening twice without error
# teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[33mok 258 Can call startUpdateAdvertisingAndListening without error
[39m
[33mok 259 Can call startUpdateAdvertisingAndListening twice without error
[39m
[33m# teardown
[39m
[36mok 260 Should be able to call stopListeningForAdvertisements in teardown
[39m
[32mok 260 Should be able to call stopListeningForAdvertisements in teardown
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[36mok 261 Should be able to call stopAdvertisingAndListening in teardown
[39m
[36m# setup
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[32mok 261 Should be able to call stopAdvertisingAndListening in teardown
[39m
[32m# setup
[39m
[33mok 260 Should be able to call stopListeningForAdvertisements in teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mok 261 Should be able to call stopAdvertisingAndListening in teardown
[39m
[33m# setup
[39m
2016-08-16T07:39:44.089Z - info: Running on ios test: 65. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error

[36m# 65. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
[39m
[32m# 65. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
[39m
[33m# 65. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
[39m
[36mok 262 Can call startUpdateAdvertisingAndListening without error
ok 263 Can call stopAdvertisingAndListening without error
# teardown
[39m
[32mok 262 Can call startUpdateAdvertisingAndListening without error
ok 263 Can call stopAdvertisingAndListening without error
[39m
[32m# teardown
[39m
[33mok 262 Can call startUpdateAdvertisingAndListening without error
[39m
[33mok 263 Can call stopAdvertisingAndListening without error
[39m
[33m# teardown
[39m
[36mok 264 Should be able to call stopListeningForAdvertisements in teardown
[39m
[36mok 265 Should be able to call stopAdvertisingAndListening in teardown
[39m
[36m# setup
[39m
[32mok 264 Should be able to call stopListeningForAdvertisements in teardown
[39m
[32mok 265 Should be able to call stopAdvertisingAndListening in teardown
[39m
[32m# setup
[39m
[33mok 264 Should be able to call stopListeningForAdvertisements in teardown
[39m
[33mok 265 Should be able to call stopAdvertisingAndListening in teardown
[39m
[33m# setup
[39m
2016-08-16T07:39:44.120Z - info: Running on ios test: 66. cannot call connect when start listening for advertisements is not active

[32m# 66. cannot call connect when start listening for advertisements is not active
[39m
[36m# 66. cannot call connect when start listening for advertisements is not active
[39m
[33m# 66. cannot call connect when start listening for advertisements is not active
[39m
[36mok 266 got right error
[39m
[32mok 266 got right error
[39m
[36m# teardown
[39m
[32m# teardown
[39m
[33mok 266 got right error
[39m
[33m# teardown
[39m
[32mok 267 Should be able to call stopListeningForAdvertisements in teardown
[39m
[36mok 267 Should be able to call stopListeningForAdvertisements in teardown
ok 268 Should be able to call stopAdvertisingAndListening in teardown
[39m
[36m# setup
[39m
[32mok 268 Should be able to call stopAdvertisingAndListening in teardown
[39m
[32m# setup
[39m
[33mok 267 Should be able to call stopListeningForAdvertisements in teardown
[39m
[33mok 268 Should be able to call stopAdvertisingAndListening in teardown
[39m
[33m# setup
[39m
2016-08-16T07:39:44.145Z - info: Running on ios test: 67. peerAvailabilityChange is called

[36m# 67. peerAvailabilityChange is called
[39m
[33m# 67. peerAvailabilityChange is called
[39m
[32m# 67. peerAvailabilityChange is called
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[36mok 269 Can call startUpdateAdvertisingAndListeningwithout error
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[36mok 270 Can call startListeningForAdvertisements without error
[39m
[32mok 269 Can call startUpdateAdvertisingAndListeningwithout error
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[32mok 270 Can call startListeningForAdvertisements without error
[39m
[32mok 271 peers must be an array
[39m
[36mok 271 peers must be an array
ok 272 peers must not be zero-length
[39m
[36mok 273 peer must have peerIdentifier
[39m
[36mok 274 peerIdentifier must be a string
ok 275 peer must have peerAvailable
[39m
[36mok 276 peer must have pleaseConnect
[39m
[36m# teardown
[39m
[32mok 272 peers must not be zero-length
[39m
[32mok 273 peer must have peerIdentifier
[39m
[32mok 274 peerIdentifier must be a string
[39m
[32mok 275 peer must have peerAvailable
[39m
[32mok 276 peer must have pleaseConnect
[39m
[32m# teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[33mok 269 Can call startUpdateAdvertisingAndListeningwithout error
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[33mok 270 Can call startListeningForAdvertisements without error
[39m
[33mok 271 peers must be an array
ok 272 peers must not be zero-length
ok 273 peer must have peerIdentifier
ok 274 peerIdentifier must be a string
[39m
[33mok 275 peer must have peerAvailable
ok 276 peer must have pleaseConnect
[39m
[33m# teardown
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 277 Should be able to call stopListeningForAdvertisements in teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 278 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 277 Should be able to call stopListeningForAdvertisements in teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 278 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 277 Should be able to call stopListeningForAdvertisements in teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 278 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
2016-08-16T07:39:44.680Z - info: Running on ios test: 68. Can connect to a remote peer

[32m# 68. Can connect to a remote peer
[39m
[36m# 68. Can connect to a remote peer
[39m
[33m# 68. Can connect to a remote peer
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 279 Can call startUpdateAdvertisingAndListening without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 280 Can call startListeningForAdvertisements without error
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:e4d5ea1d-1a00-4fcf-aa20-b8a9e65e96ae","peerAvailable":true,"pleaseConnect":false}]
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 279 Can call startUpdateAdvertisingAndListening without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 280 Can call startListeningForAdvertisements without error
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a4ef8836-9a64-4a42-b78a-c3d1f236cc37","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 279 Can call startUpdateAdvertisingAndListening without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 280 Can call startListeningForAdvertisements without error
[39m
[32mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:15cbd1bb-959b-4641-903f-84c486c146de","peerAvailable":true,"pleaseConnect":false}]
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:15cbd1bb-959b-4641-903f-84c486c146de","peerAvailable":true,"pleaseConnect":false}]
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mINFO testThaliMobileNative: 
[39m
[33mok 281 Must have listeningPort
ok 282 listeningPort must be a number
ok 283 Connection must have clientPort
[39m
[33mok 284 clientPort must be a number
ok 285 Connection must have serverPort
[39m
[33mok 286 serverPort must be a number
ok 287 forward connection must have clientPort == 0
[39m
[33mok 288 forward connection must have serverPort == 0
[39m
[33m# teardown
[39m
[32mINFO testThaliMobileNative: 
[39m
[32mok 281 Must have listeningPort
[39m
[32mok 282 listeningPort must be a number
ok 283 Connection must have clientPort
[39m
[32mok 284 clientPort must be a number
ok 285 Connection must have serverPort
ok 286 serverPort must be a number
ok 287 forward connection must have clientPort == 0
ok 288 forward connection must have serverPort == 0
# teardown
[39m
[32mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:e4d5ea1d-1a00-4fcf-aa20-b8a9e65e96ae","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:e4d5ea1d-1a00-4fcf-aa20-b8a9e65e96ae","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a4ef8836-9a64-4a42-b78a-c3d1f236cc37","peerAvailable":true,"pleaseConnect":false}]
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a4ef8836-9a64-4a42-b78a-c3d1f236cc37","peerAvailable":true,"pleaseConnect":false}]
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:15cbd1bb-959b-4641-903f-84c486c146de","peerAvailable":true,"pleaseConnect":false}]
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:15cbd1bb-959b-4641-903f-84c486c146de","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: 
[39m
[36mok 281 Must have listeningPort
ok 282 listeningPort must be a number
ok 283 Connection must have clientPort
ok 284 clientPort must be a number
ok 285 Connection must have serverPort
[39m
[36mok 286 serverPort must be a number
ok 287 forward connection must have clientPort == 0
[39m
[36mok 288 forward connection must have serverPort == 0
[39m
[36m# teardown
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 289 Should be able to call stopListeningForAdvertisements in teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 290 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 289 Should be able to call stopListeningForAdvertisements in teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 290 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:15cbd1bb-959b-4641-903f-84c486c146de","peerAvailable":false,"pleaseConnect":false}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a4ef8836-9a64-4a42-b78a-c3d1f236cc37","peerAvailable":false,"pleaseConnect":false}]
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[33mok 289 Should be able to call stopListeningForAdvertisements in teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 290 Should be able to call stopAdvertisingAndListening in teardown
[39m
[33m# setup
[39m
2016-08-16T07:39:45.331Z - info: Running on ios test: 69. Get error when trying to double connect to a peer

[32m# 69. Get error when trying to double connect to a peer
[39m
[36m# 69. Get error when trying to double connect to a peer
[39m
[33m# 69. Get error when trying to double connect to a peer
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 291 Can call startUpdateAdvertisingAndListening without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 292 Can call startListeningForAdvertisements without error
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 291 Can call startUpdateAdvertisingAndListening without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 292 Can call startListeningForAdvertisements without error
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 291 Can call startUpdateAdvertisingAndListening without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 292 Can call startListeningForAdvertisements without error
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mok 293 Expected error
[39m
[36mok 294 Null connection as expected
ok 295 Expected error
ok 296 Null connection as expected
[39m
[36m# teardown
[39m
[32mok 293 Expected error
[39m
[32mok 294 Null connection as expected
ok 295 Expected error
ok 296 Null connection as expected
[39m
[32m# teardown
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mok 293 Expected error
ok 294 Null connection as expected
[39m
[33mok 295 Expected error
ok 296 Null connection as expected
[39m
[33m# teardown
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 297 Should be able to call stopListeningForAdvertisements in teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 298 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 297 Should be able to call stopListeningForAdvertisements in teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 298 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 297 Should be able to call stopListeningForAdvertisements in teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mok 298 Should be able to call stopAdvertisingAndListening in teardown
[39m
[33m# setup
[39m
2016-08-16T07:39:45.966Z - info: Running on ios test: 70. Connect port dies if not connected to in time

[32m# 70. Connect port dies if not connected to in time
[39m
[36m# 70. Connect port dies if not connected to in time
[39m
[33m# 70. Connect port dies if not connected to in time
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 299 Can call startUpdateAdvertisingAndListening without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 300 Can call startListeningForAdvertisements without error
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 299 Can call startUpdateAdvertisingAndListening without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 300 Can call startListeningForAdvertisements without error
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 299 Can call startUpdateAdvertisingAndListening without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 300 Can call startListeningForAdvertisements without error
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mok 301 failed correctly due to refused connection
# teardown
[39m
[32mok 301 failed correctly due to refused connection
# teardown
[39m
[33mok 301 failed correctly due to refused connection
[39m
[33m# teardown
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 302 Should be able to call stopListeningForAdvertisements in teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 303 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 302 Should be able to call stopListeningForAdvertisements in teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 303 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 302 Should be able to call stopListeningForAdvertisements in teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mok 303 Should be able to call stopAdvertisingAndListening in teardown
[39m
[33m# setup
[39m
2016-08-16T07:39:49.615Z - info: Running on ios test: 71. Can shift large amounts of data

[32m# 71. Can shift large amounts of data
[39m
[36m# 71. Can shift large amounts of data
[39m
[33m# 71. Can shift large amounts of data
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 304 Can call startUpdateAdvertisingAndListening without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 305 Can call startListeningForAdvertisements without error
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 304 Can call startUpdateAdvertisingAndListening without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 305 Can call startListeningForAdvertisements without error
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[33mok 304 Can call startUpdateAdvertisingAndListening without error
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[33mok 305 Can call startListeningForAdvertisements without error
[39m
[33mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mINFO testThaliMobileNative: 
INFO testThaliMobileNative: Forward connection
INFO testThaliMobileNative: forwardSend
[39m
[32mINFO testThaliMobileNative: 
INFO testThaliMobileNative: Forward connection
[39m
[32mINFO testThaliMobileNative: forwardSend
[39m
[32mINFO testThaliMobileNative: forwardData
ok 306 received should match sent forward
# teardown
[39m
[36mINFO testThaliMobileNative: forwardData
ok 306 received should match sent forward
# teardown
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mINFO testThaliMobileNative: 
[39m
[33mINFO testThaliMobileNative: Forward connection
[39m
[33mINFO testThaliMobileNative: forwardSend
[39m
[33mINFO testThaliMobileNative: forwardData
[39m
[33mok 306 received should match sent forward
[39m
[33m# teardown
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 307 Should be able to call stopListeningForAdvertisements in teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 308 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 307 Should be able to call stopListeningForAdvertisements in teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 308 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[33mok 307 Should be able to call stopListeningForAdvertisements in teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mok 308 Should be able to call stopAdvertisingAndListening in teardown
[39m
[33m# setup
[39m
2016-08-16T07:39:50.266Z - info: Running on ios test: 72. #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection

[32m# 72. #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
[39m
[36m# 72. #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
[39m
[33m# 72. #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 309 Can call startUpdateAdvertisingAndListening without error
[39m
[32mok 309 Can call startUpdateAdvertisingAndListening without error
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[32mok 310 Can call startListeningForAdvertisements without error
[39m
[36mok 310 Can call startListeningForAdvertisements without error
[39m
[32mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:1a5da182-34f3-446f-b216-6602c15a4f3e","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:f1bd5383-a7d0-40ab-bdfc-a2de4adf6a21","peerAvailable":true,"pleaseConnect":false}]
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[33mok 309 Can call startUpdateAdvertisingAndListening without error
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[33mok 310 Can call startListeningForAdvertisements without error
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:03c335c5-8289-4c94-8a3d-2d9285503567","peerAvailable":true,"pleaseConnect":false}]
[39m
[32mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:03c335c5-8289-4c94-8a3d-2d9285503567","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: connection {"listeningPort":51341,"clientPort":0,"serverPort":0}
INFO testThaliMobileNative: connection to listening port is made
[39m
[32mINFO testThaliMobileNative: connection {"listeningPort":51340,"clientPort":0,"serverPort":0}
INFO testThaliMobileNative: connection to listening port is made
[39m
[32mok 311 Data matches
ok 312 Data matches
[39m
[36mok 311 Data matches
ok 312 Data matches
[39m
[36mok 313 We got the close message and we are closed
ok 314 We got an error which is what we wanted
# teardown
[39m
[32mok 313 We got the close message and we are closed
ok 314 We got an error which is what we wanted
# teardown
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:f1bd5383-a7d0-40ab-bdfc-a2de4adf6a21","peerAvailable":true,"pleaseConnect":false}]
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:f1bd5383-a7d0-40ab-bdfc-a2de4adf6a21","peerAvailable":true,"pleaseConnect":false}]
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:1a5da182-34f3-446f-b216-6602c15a4f3e","peerAvailable":true,"pleaseConnect":false}]
[39m
[32mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:1a5da182-34f3-446f-b216-6602c15a4f3e","peerAvailable":true,"pleaseConnect":false}]
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:03c335c5-8289-4c94-8a3d-2d9285503567","peerAvailable":true,"pleaseConnect":false}]
[39m
[32mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:03c335c5-8289-4c94-8a3d-2d9285503567","peerAvailable":true,"pleaseConnect":false}]
[39m
[33mINFO testThaliMobileNative: connection {"listeningPort":51353,"clientPort":0,"serverPort":0}
[39m
[33mINFO testThaliMobileNative: connection to listening port is made
[39m
[32mok 315 Data matches
[39m
[33mok 311 Data matches
[39m
[33mok 312 We got the close message and we are closed
[39m
[33mok 313 We got an error which is what we wanted
[39m
[33m# teardown
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 316 Should be able to call stopListeningForAdvertisements in teardown
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 315 Should be able to call stopListeningForAdvertisements in teardown
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 316 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 317 Should be able to call stopAdvertisingAndListening in teardown
[39m
[32m# setup
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:f1bd5383-a7d0-40ab-bdfc-a2de4adf6a21","peerAvailable":false,"pleaseConnect":false}]
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:1a5da182-34f3-446f-b216-6602c15a4f3e","peerAvailable":false,"pleaseConnect":false}]
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[33mok 314 Should be able to call stopListeningForAdvertisements in teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mok 315 Should be able to call stopAdvertisingAndListening in teardown
[39m
[33m# setup
[39m
2016-08-16T07:39:50.916Z - info: Running on ios test: 73. #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection

[32m# 73. #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
[39m
[36m# 73. #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
[39m
[33m# 73. #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 317 Can call startUpdateAdvertisingAndListening without error
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[36mok 318 Can call startListeningForAdvertisements without error
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[32mok 318 Can call startUpdateAdvertisingAndListening without error
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[32mok 319 Can call startListeningForAdvertisements without error
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bb367193-6469-4bc5-b507-5a0ce824885c","peerAvailable":true,"pleaseConnect":false}]
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[33mok 316 Can call startUpdateAdvertisingAndListening without error
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[33mok 317 Can call startListeningForAdvertisements without error
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:315b185b-cd91-402b-a0cf-23a6f00d6685","peerAvailable":true,"pleaseConnect":false}]
[39m
[32mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:315b185b-cd91-402b-a0cf-23a6f00d6685","peerAvailable":true,"pleaseConnect":false}]
[39m
[33mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mINFO testThaliMobileNative: connection {"listeningPort":51364,"clientPort":0,"serverPort":0}
INFO testThaliMobileNative: connection to listening port is made
[39m
[32mINFO testThaliMobileNative: connection {"listeningPort":51370,"clientPort":0,"serverPort":0}
[39m
[32mINFO testThaliMobileNative: connection to listening port is made
[39m
[32mok 320 Data matches
[39m
[33mok 318 Data matches
[39m
[36mok 319 Data matches
ok 320 We got the close message and we are closed
[39m
[36mok 321 We got an error which is what we wanted
# teardown
[39m
[32mok 321 Data matches
ok 322 We got the close message and we are closed
[39m
[32mok 323 We got an error which is what we wanted
[39m
[32m# teardown
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:315b185b-cd91-402b-a0cf-23a6f00d6685","peerAvailable":true,"pleaseConnect":false}]
[39m
[32mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:da334d10-04d3-4009-b5ce-f776b9bf6107","peerAvailable":true,"pleaseConnect":false}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:315b185b-cd91-402b-a0cf-23a6f00d6685","peerAvailable":true,"pleaseConnect":false}]
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:da334d10-04d3-4009-b5ce-f776b9bf6107","peerAvailable":true,"pleaseConnect":false}]
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bb367193-6469-4bc5-b507-5a0ce824885c","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bb367193-6469-4bc5-b507-5a0ce824885c","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mINFO testThaliMobileNative: connection {"listeningPort":51377,"clientPort":0,"serverPort":0}
[39m
[33mINFO testThaliMobileNative: connection to listening port is made
[39m
[36mok 322 Data matches
[39m
[33mok 319 Data matches
[39m
[33mok 320 We got the close message and we are closed
[39m
[33mok 321 We got an error which is what we wanted
[39m
[33m# teardown
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 324 Should be able to call stopListeningForAdvertisements in teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 325 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 323 Should be able to call stopListeningForAdvertisements in teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 324 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bb367193-6469-4bc5-b507-5a0ce824885c","peerAvailable":false,"pleaseConnect":false}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:da334d10-04d3-4009-b5ce-f776b9bf6107","peerAvailable":false,"pleaseConnect":false}]
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[33mok 322 Should be able to call stopListeningForAdvertisements in teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mok 323 Should be able to call stopAdvertisingAndListening in teardown
[39m
[33m# setup
[39m
2016-08-16T07:39:51.571Z - info: Running on ios test: 74. #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer

[32m# 74. #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
[39m
[36m# 74. #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
[39m
[33m# 74. #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 325 Can call startUpdateAdvertisingAndListening without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 326 Can call startListeningForAdvertisements without error
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:e929ba87-cde5-4876-a22c-dae151464c3a","peerAvailable":true,"pleaseConnect":false}]
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 326 Can call startUpdateAdvertisingAndListening without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 327 Can call startListeningForAdvertisements without error
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:58d7cfc1-def5-45e4-9fb5-f4d3b2585f5d","peerAvailable":true,"pleaseConnect":false}]
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[33mok 324 Can call startUpdateAdvertisingAndListening without error
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 325 Can call startListeningForAdvertisements without error
[39m
[32mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:399a6e80-3259-4584-9490-202b9fc30ee5","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:399a6e80-3259-4584-9490-202b9fc30ee5","peerAvailable":true,"pleaseConnect":false}]
[39m
[32mINFO testThaliMobileNative: connection {"listeningPort":51388,"clientPort":0,"serverPort":0}
[39m
[36mINFO testThaliMobileNative: connection {"listeningPort":51389,"clientPort":0,"serverPort":0}
[39m
[36mINFO testThaliMobileNative: connection to listening port is made
[39m
[32mINFO testThaliMobileNative: connection to listening port is made
[39m
[32mok 328 Data matches
[39m
[36mok 327 Data matches
[39m
[36mok 328 Data matches
ok 329 We got the close message and we are closed
DEBUG wifiBasedNativeMock: got an end on peerProxySockets
ok 330 We got an error which is what we wanted
# teardown
[39m
[32mok 329 Data matches
ok 330 We got the close message and we are closed
DEBUG wifiBasedNativeMock: got an end on peerProxySockets
ok 331 We got an error which is what we wanted
# teardown
[39m
[32mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:58d7cfc1-def5-45e4-9fb5-f4d3b2585f5d","peerAvailable":true,"pleaseConnect":false}]
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:58d7cfc1-def5-45e4-9fb5-f4d3b2585f5d","peerAvailable":true,"pleaseConnect":false}]
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:e929ba87-cde5-4876-a22c-dae151464c3a","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:e929ba87-cde5-4876-a22c-dae151464c3a","peerAvailable":true,"pleaseConnect":false}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:399a6e80-3259-4584-9490-202b9fc30ee5","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:399a6e80-3259-4584-9490-202b9fc30ee5","peerAvailable":true,"pleaseConnect":false}]
[39m
[33mINFO testThaliMobileNative: connection {"listeningPort":51401,"clientPort":0,"serverPort":0}
[39m
[33mINFO testThaliMobileNative: connection to listening port is made
[39m
[36mok 331 Data matches
[39m
[33mok 326 Data matches
[39m
[33mok 327 We got the close message and we are closed
[39m
[33mDEBUG wifiBasedNativeMock: got an end on peerProxySockets
[39m
[33mok 328 We got an error which is what we wanted
[39m
[33m# teardown
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 332 Should be able to call stopListeningForAdvertisements in teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 333 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 332 Should be able to call stopListeningForAdvertisements in teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 333 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:58d7cfc1-def5-45e4-9fb5-f4d3b2585f5d","peerAvailable":false,"pleaseConnect":false}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:e929ba87-cde5-4876-a22c-dae151464c3a","peerAvailable":false,"pleaseConnect":false}]
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[33mok 329 Should be able to call stopListeningForAdvertisements in teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mok 330 Should be able to call stopAdvertisingAndListening in teardown
[39m
[33m# setup
[39m
2016-08-16T07:39:52.218Z - info: Running on ios test: 75. #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer

[32m# 75. #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
[39m
[36m# 75. #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
[39m
[33m# 75. #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[32mok 334 Can call startUpdateAdvertisingAndListening without error
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 335 Can call startListeningForAdvertisements without error
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[36mok 334 Can call startUpdateAdvertisingAndListening without error
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[36mok 335 Can call startListeningForAdvertisements without error
[39m
[32mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:6b80d70e-3b4f-4588-97a5-c8f34c812a66","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[33mok 331 Can call startUpdateAdvertisingAndListening without error
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[33mok 332 Can call startListeningForAdvertisements without error
[39m
[32mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:aab1cc62-d193-4462-a75b-fcb1f8e19d19","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:aab1cc62-d193-4462-a75b-fcb1f8e19d19","peerAvailable":true,"pleaseConnect":false}]
[39m
[33mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mINFO testThaliMobileNative: connection {"listeningPort":51412,"clientPort":0,"serverPort":0}
INFO testThaliMobileNative: connection to listening port is made
[39m
[36mINFO testThaliMobileNative: connection {"listeningPort":51418,"clientPort":0,"serverPort":0}
[39m
[36mINFO testThaliMobileNative: connection to listening port is made
[39m
[36mok 336 Data matches
[39m
[33mok 333 Data matches
[39m
[32mok 336 Data matches
DEBUG wifiBasedNativeMock: got an end on peerProxySockets
ok 337 We got the close message and we are closed
ok 338 We got an error which is what we wanted
# teardown
[39m
[36mok 337 Data matches
DEBUG wifiBasedNativeMock: got an end on peerProxySockets
ok 338 We got the close message and we are closed
ok 339 We got an error which is what we wanted
# teardown
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a4dd1f79-3443-4fc1-9540-d873b0b42db8","peerAvailable":true,"pleaseConnect":false}]
[39m
[32mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:6b80d70e-3b4f-4588-97a5-c8f34c812a66","peerAvailable":true,"pleaseConnect":false}]
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a4dd1f79-3443-4fc1-9540-d873b0b42db8","peerAvailable":true,"pleaseConnect":false}]
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:6b80d70e-3b4f-4588-97a5-c8f34c812a66","peerAvailable":true,"pleaseConnect":false}]
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:aab1cc62-d193-4462-a75b-fcb1f8e19d19","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:aab1cc62-d193-4462-a75b-fcb1f8e19d19","peerAvailable":true,"pleaseConnect":false}]
[39m
[33mINFO testThaliMobileNative: connection {"listeningPort":51425,"clientPort":0,"serverPort":0}
[39m
[33mINFO testThaliMobileNative: connection to listening port is made
[39m
[32mok 339 Data matches
[39m
[33mok 334 Data matches
[39m
[33mDEBUG wifiBasedNativeMock: got an end on peerProxySockets
[39m
[33mok 335 We got the close message and we are closed
[39m
[33mok 336 We got an error which is what we wanted
[39m
[33m# teardown
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 340 Should be able to call stopListeningForAdvertisements in teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 341 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 340 Should be able to call stopListeningForAdvertisements in teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 341 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a4dd1f79-3443-4fc1-9540-d873b0b42db8","peerAvailable":false,"pleaseConnect":false}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:6b80d70e-3b4f-4588-97a5-c8f34c812a66","peerAvailable":false,"pleaseConnect":false}]
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 337 Should be able to call stopListeningForAdvertisements in teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mok 338 Should be able to call stopAdvertisingAndListening in teardown
[39m
[33m# setup
[39m
2016-08-16T07:39:52.866Z - info: Running on ios test: 76. We do not emit peerAvailabilityChanged events until one of the start methods is called

[32m# 76. We do not emit peerAvailabilityChanged events until one of the start methods is called
[39m
[36m# 76. We do not emit peerAvailabilityChanged events until one of the start methods is called
[39m
[33m# 76. We do not emit peerAvailabilityChanged events until one of the start methods is called
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 342 We should start listening fine
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 343 We should start updating fine
# teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 339 We should start listening fine
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 340 We should start updating fine
# teardown
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:2ded5878-940b-46d4-a5c8-552555a2457a","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:47295627-2a83-4826-8b7d-dcddb8b097e3","peerAvailable":true,"pleaseConnect":false}]
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:2ded5878-940b-46d4-a5c8-552555a2457a","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:47295627-2a83-4826-8b7d-dcddb8b097e3","peerAvailable":true,"pleaseConnect":false}]
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:2ded5878-940b-46d4-a5c8-552555a2457a","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:47295627-2a83-4826-8b7d-dcddb8b097e3","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:47295627-2a83-4826-8b7d-dcddb8b097e3","peerAvailable":true,"pleaseConnect":false}]
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:2ded5878-940b-46d4-a5c8-552555a2457a","peerAvailable":true,"pleaseConnect":false}]
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[32mok 342 Ready to advertise
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 343 Ready to listen
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:d93987cf-f83f-40a9-a6e1-a9878e67f278","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:d93987cf-f83f-40a9-a6e1-a9878e67f278","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:47295627-2a83-4826-8b7d-dcddb8b097e3","peerAvailable":true,"pleaseConnect":false}]
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 344 stop ads worked
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 345 test stop worked
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:d93987cf-f83f-40a9-a6e1-a9878e67f278","peerAvailable":false,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:d93987cf-f83f-40a9-a6e1-a9878e67f278","peerAvailable":false,"pleaseConnect":false}]
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:2ded5878-940b-46d4-a5c8-552555a2457a","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:47295627-2a83-4826-8b7d-dcddb8b097e3","peerAvailable":true,"pleaseConnect":false}]
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:2ded5878-940b-46d4-a5c8-552555a2457a","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:47295627-2a83-4826-8b7d-dcddb8b097e3","peerAvailable":true,"pleaseConnect":false}]
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:2ded5878-940b-46d4-a5c8-552555a2457a","peerAvailable":true,"pleaseConnect":false}]
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:2ded5878-940b-46d4-a5c8-552555a2457a","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:47295627-2a83-4826-8b7d-dcddb8b097e3","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:47295627-2a83-4826-8b7d-dcddb8b097e3","peerAvailable":true,"pleaseConnect":false}]
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:2ded5878-940b-46d4-a5c8-552555a2457a","peerAvailable":true,"pleaseConnect":false}]
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:2ded5878-940b-46d4-a5c8-552555a2457a","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:47295627-2a83-4826-8b7d-dcddb8b097e3","peerAvailable":true,"pleaseConnect":false}]
[39m
[32m# teardown
[39m
[32mok 346 Should be able to call stopListeningForAdvertisements in teardown
ok 347 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 344 Should be able to call stopListeningForAdvertisements in teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 345 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:2ded5878-940b-46d4-a5c8-552555a2457a","peerAvailable":false,"pleaseConnect":false}]
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 341 Should be able to call stopListeningForAdvertisements in teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 342 Should be able to call stopAdvertisingAndListening in teardown
[39m
[33m# setup
[39m
2016-08-16T07:39:57.925Z - info: Running on ios test: 77. Test updating advertising and parallel data transfer

[32m# 77. Test updating advertising and parallel data transfer
[39m
[36m# 77. Test updating advertising and parallel data transfer
[39m
[33m# 77. Test updating advertising and parallel data transfer
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 346 Can call startUpdateAdvertisingAndListening without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 347 Can call startListeningForAdvertisements without error
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 348 Can call startUpdateAdvertisingAndListening without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 349 Can call startListeningForAdvertisements without error
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 343 Can call startUpdateAdvertisingAndListening without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 344 Can call startListeningForAdvertisements without error
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG testThaliMobileNative: serverRound: Message written, closing socket (calling socket.end)
[39m
[32mDEBUG testThaliMobileNative: serverRound: Message written, closing socket (calling socket.end)
[39m
[36mDEBUG testThaliMobileNative: Response validated, calling connection.end
[39m
[33mDEBUG testThaliMobileNative: serverRound: Message written, closing socket (calling socket.end)
[39m
[36mDEBUG testThaliMobileNative: serverRound: Message written, closing socket (calling socket.end)
DEBUG testThaliMobileNative: Response validated, calling connection.end
[39m
[32mDEBUG testThaliMobileNative: Response validated, calling connection.end
[39m
[32mDEBUG testThaliMobileNative: Response validated, calling connection.end
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG testThaliMobileNative: serverRound: Message written, closing socket (calling socket.end)
DEBUG testThaliMobileNative: We made it through round one
ok 348 Round 1 ready
[39m
[32mDEBUG testThaliMobileNative: serverRound: Message written, closing socket (calling socket.end)
DEBUG testThaliMobileNative: We made it through round one
ok 350 Round 1 ready
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG testThaliMobileNative: Response validated, calling connection.end
DEBUG testThaliMobileNative: Response validated, calling connection.end
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG testThaliMobileNative: We made it through round one
[39m
[33mok 345 Round 1 ready
[39m
[33mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG testThaliMobileNative: serverRound: Message written, closing socket (calling socket.end)
[39m
[36mDEBUG testThaliMobileNative: serverRound: Message written, closing socket (calling socket.end)
[39m
[36mDEBUG testThaliMobileNative: Response validated, calling connection.end
[39m
[33mDEBUG testThaliMobileNative: serverRound: Message written, closing socket (calling socket.end)
[39m
[32mDEBUG testThaliMobileNative: Response validated, calling connection.end
[39m
[33mDEBUG testThaliMobileNative: serverRound: Message written, closing socket (calling socket.end)
[39m
[36mDEBUG testThaliMobileNative: Response validated, calling connection.end
[39m
[32mDEBUG testThaliMobileNative: Response validated, calling connection.end
[39m
[33mINFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
[39m
[33mINFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
[39m
[33mINFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG testThaliMobileNative: serverRound: Message written, closing socket (calling socket.end)
# teardown
[39m
[32mDEBUG testThaliMobileNative: serverRound: Message written, closing socket (calling socket.end)
# teardown
[39m
[33mDEBUG testThaliMobileNative: Response validated, calling connection.end
DEBUG testThaliMobileNative: Response validated, calling connection.end
[39m
[33m# teardown
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 351 Should be able to call stopListeningForAdvertisements in teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 352 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 349 Should be able to call stopListeningForAdvertisements in teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 350 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 346 Should be able to call stopListeningForAdvertisements in teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mok 347 Should be able to call stopAdvertisingAndListening in teardown
[39m
[33m# setup
[39m
2016-08-16T07:40:02.200Z - info: Running on ios test: 78. #startListeningForAdvertisements should fail if start not called

[32mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 78. #startListeningForAdvertisements should fail if start not called
[39m
[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 78. #startListeningForAdvertisements should fail if start not called
[39m
[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[33m# 78. #startListeningForAdvertisements should fail if start not called
[39m
[32mok 353 specific error should be returned
# teardown
[39m
[36mok 351 specific error should be returned
# teardown
[39m
[33mok 348 specific error should be returned
# teardown
[39m
[36mok 352 must be stopped
# setup
[39m
[32mok 354 must be stopped
# setup
[39m
[33mok 349 must be stopped
# setup
[39m
2016-08-16T07:40:02.228Z - info: Running on ios test: 79. #startUpdateAdvertisingAndListening should fail if start not called

[32mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 79. #startUpdateAdvertisingAndListening should fail if start not called
[39m
[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 79. #startUpdateAdvertisingAndListening should fail if start not called
[39m
[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 79. #startUpdateAdvertisingAndListening should fail if start not called
[39m
[32mok 355 specific error should be returned
# teardown
[39m
[36mok 353 specific error should be returned
# teardown
[39m
[33mok 350 specific error should be returned
# teardown
[39m
[32mok 356 must be stopped
# setup
[39m
[36mok 354 must be stopped
# setup
[39m
[33mok 351 must be stopped
# setup
[39m
2016-08-16T07:40:02.250Z - info: Running on ios test: 80. should be able to call #stopListeningForAdvertisements many times

[32mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[32m# 80. should be able to call #stopListeningForAdvertisements many times
[39m
[36mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[36m# 80. should be able to call #stopListeningForAdvertisements many times
[39m
[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 80. should be able to call #stopListeningForAdvertisements many times
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51502
ok 357 no errors
ok 358 still no errors
# teardown
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51501
ok 355 no errors
ok 356 still no errors
# teardown
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: listening 51504
[39m
[33mok 352 no errors
[39m
[33mok 353 still no errors
[39m
[33m# teardown
[39m
[32mok 359 must be stopped
# setup
[39m
[36mok 357 must be stopped
# setup
[39m
[33mok 354 must be stopped
[39m
[33m# setup
[39m
2016-08-16T07:40:02.288Z - info: Running on ios test: 81. should be able to call #startListeningForAdvertisements many times

[32mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 81. should be able to call #startListeningForAdvertisements many times
[39m
[32mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 81. should be able to call #startListeningForAdvertisements many times
[39m
[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[33m# 81. should be able to call #startListeningForAdvertisements many times
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51506
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 360 no errors
ok 361 still no errors
# teardown
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: listening 51509
[39m
[33mDEBUG createNativeListener: listening 51510
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 358 no errors
[39m
[36mok 359 still no errors
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[36m# teardown
[39m
[33mok 355 no errors
ok 356 still no errors
[39m
[33m# teardown
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 362 must be stopped
# setup
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 360 must be stopped
# setup
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mok 357 must be stopped
[39m
[33m# setup
[39m
2016-08-16T07:40:02.326Z - info: Running on ios test: 82. should be able to call #startUpdateAdvertisingAndListening many times

[32mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[32mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[32mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[36m# 82. should be able to call #startUpdateAdvertisingAndListening many times
[39m
[32mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[32m# 82. should be able to call #startUpdateAdvertisingAndListening many times
[39m
[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[33m# 82. should be able to call #startUpdateAdvertisingAndListening many times
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: listening 51513
[39m
[36mDEBUG createNativeListener: listening 51514
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[36mok 361 no errors
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[32mok 363 no errors
[39m
[36mok 362 still no errors
[39m
[36m# teardown
[39m
[32mok 364 still no errors
[39m
[32m# teardown
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: listening 51520
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[33mok 358 no errors
[39m
[33mok 359 still no errors
[39m
[33m# teardown
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[36mok 363 must be stopped
[39m
[36m# setup
[39m
[32mok 365 must be stopped
[39m
[32m# setup
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mok 360 must be stopped
[39m
[33m# setup
[39m
2016-08-16T07:40:02.378Z - info: Running on ios test: 83. should be able to call #stopAdvertisingAndListening many times

[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 83. should be able to call #stopAdvertisingAndListening many times
[39m
[32mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 83. should be able to call #stopAdvertisingAndListening many times
[39m
[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[33m# 83. should be able to call #stopAdvertisingAndListening many times
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51525
ok 366 no errors
ok 367 still no errors
# teardown
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51526
ok 364 no errors
[39m
[36mok 365 still no errors
[39m
[36m# teardown
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: listening 51528
[39m
[33mok 361 no errors
[39m
[33mok 362 still no errors
[39m
[33m# teardown
[39m
[36mok 366 must be stopped
# setup
[39m
[33mok 363 must be stopped
# setup
[39m
[32mok 368 must be stopped
[39m
[32m# setup
[39m
2016-08-16T07:40:02.420Z - info: Running on ios test: 84. can get the network status before starting

[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 84. can get the network status before starting
[39m
[32mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 84. can get the network status before starting
[39m
[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[33m# 84. can get the network status before starting
[39m
[32mok 369 network status should have certain non-empty properties
[39m
[32m# teardown
[39m
[33mok 364 network status should have certain non-empty properties
# teardown
[39m
[36mok 367 network status should have certain non-empty properties
[39m
[36m# teardown
[39m
[32mok 370 must be stopped
# setup
[39m
[36mok 368 must be stopped
# setup
[39m
[33mok 365 must be stopped
[39m
[33m# setup
[39m
2016-08-16T07:40:02.455Z - info: Running on ios test: 85. error returned with bad router

[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 85. error returned with bad router
[39m
[32mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 85. error returned with bad router
[39m
[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 85. error returned with bad router
[39m
[32mERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
ok 371 specific error expected
# teardown
[39m
[36mERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
ok 369 specific error expected
# teardown
[39m
[33mERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
[39m
[33mok 366 specific error expected
[39m
[33m# teardown
[39m
[32mok 372 must be stopped
# setup
[39m
[36mok 370 must be stopped
# setup
[39m
[33mok 367 must be stopped
[39m
[33m# setup
[39m
2016-08-16T07:40:02.483Z - info: Running on ios test: 86. all services are stopped when we call stop

[32mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 86. all services are stopped when we call stop
[39m
[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 86. all services are stopped when we call stop
[39m
[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 86. all services are stopped when we call stop
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51531
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51532
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 371 connection to servers manager should succeed after starting
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 372 connection to router server should succeed after starting
[39m
[32mok 373 connection to servers manager should succeed after starting
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[36mok 373 is stopped after calling stop
[39m
[36mok 374 connection to servers manager should fail after stopping
[39m
[32mok 374 connection to router server should succeed after starting
[39m
[36mok 375 connection to router server should fail after stopping
[39m
[36m# teardown
[39m
[32mDEBUG createNativeListener: incoming socket close
DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 375 is stopped after calling stop
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51545
[39m
[32mok 376 connection to servers manager should fail after stopping
[39m
[32mok 377 connection to router server should fail after stopping
# teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[33mDEBUG createNativeListener: new incoming socket
[39m
[33mDEBUG createNativeListener: creating incoming mux
[39m
[33mDEBUG createNativeListener: new mux
[39m
[33mok 368 connection to servers manager should succeed after starting
[39m
[33mok 369 connection to router server should succeed after starting
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mok 370 is stopped after calling stop
[39m
[33mok 371 connection to servers manager should fail after stopping
[39m
[33mok 372 connection to router server should fail after stopping
[39m
[33m# teardown
[39m
[36mok 376 must be stopped
# setup
[39m
[32mok 378 must be stopped
# setup
[39m
[33mok 373 must be stopped
# setup
[39m
2016-08-16T07:40:02.542Z - info: Running on ios test: 87. make sure terminateConnection is properly hooked up

[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[36m# 87. make sure terminateConnection is properly hooked up
[39m
[32mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[32mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[32m# 87. make sure terminateConnection is properly hooked up
[39m
[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[32mok 379 called with right arguments
[39m
[36mok 377 called with right arguments
# teardown
[39m
[32m# teardown
[39m
[33m# 87. make sure terminateConnection is properly hooked up
[39m
[33mok 374 called with right arguments
[39m
[33m# teardown
[39m
[36mok 378 must be stopped
# setup
[39m
[32mok 380 must be stopped
# setup
[39m
[33mok 375 must be stopped
[39m
[33m# setup
[39m
2016-08-16T07:40:02.586Z - info: Running on ios test: 88. make sure terminateListener is properly hooked up

[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 88. make sure terminateListener is properly hooked up
[39m
[32mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[32mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 88. make sure terminateListener is properly hooked up
[39m
[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 88. make sure terminateListener is properly hooked up
[39m
[32mok 381 called with right arguments
# teardown
[39m
[36mok 379 called with right arguments
# teardown
[39m
[33mok 376 called with right arguments
[39m
[33m# teardown
[39m
[36mok 380 must be stopped
# setup
[39m
[32mok 382 must be stopped
[39m
[32m# setup
[39m
[33mok 377 must be stopped
[39m
[33m# setup
[39m
2016-08-16T07:40:02.618Z - info: Running on ios test: 89. make sure we actually call kill connections properly

[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 89. make sure we actually call kill connections properly
[39m
[32mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[32mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 89. make sure we actually call kill connections properly
[39m
[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 89. make sure we actually call kill connections properly
[39m
[32mok 383 specific error expected
[39m
[36mok 381 specific error expected
[39m
[36m# teardown
[39m
[32m# teardown
[39m
[33mok 378 specific error expected
[39m
[33m# teardown
[39m
[36mok 382 must be stopped
[39m
[36m# setup
[39m
[32mok 384 must be stopped
[39m
[32m# setup
[39m
[33mok 379 must be stopped
[39m
[33m# setup
[39m
2016-08-16T07:40:02.651Z - info: Running on ios test: 90. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received

[32mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[32mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[32m# 90. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
[39m
[36mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[36m# 90. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
[39m
[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[33m# 90. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: listening 51555
[39m
[36mINFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":51554,"error":{}}
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[36mok 383 failure reason is as expected
[39m
[36mok 384 error description is as expected
ok 385 must be stopped
[39m
[36m# teardown
[39m
[32mDEBUG createNativeListener: listening 51557
[39m
[32mINFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":51556,"error":{}}
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[32mok 385 failure reason is as expected
[39m
[32mok 386 error description is as expected
ok 387 must be stopped
[39m
[32m# teardown
[39m
[33mDEBUG createNativeListener: listening 51559
[39m
[33mINFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":51558,"error":{}}
[39m
[33mok 380 failure reason is as expected
[39m
[33mok 381 error description is as expected
ok 382 must be stopped
[39m
[33m# teardown
[39m
[36mok 386 must be stopped
[39m
[36m# setup
[39m
[32mok 388 must be stopped
[39m
[32m# setup
[39m
[33mok 383 must be stopped
[39m
[33m# setup
[39m
2016-08-16T07:40:02.692Z - info: Running on ios test: 91. We repeat failedConnection event when we get it from thaliTcpServersManager

[32mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[32m# 91. We repeat failedConnection event when we get it from thaliTcpServersManager
[39m
[36mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[36m# 91. We repeat failedConnection event when we get it from thaliTcpServersManager
[39m
[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[33m# 91. We repeat failedConnection event when we get it from thaliTcpServersManager
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: listening 51561
[39m
[32mok 389 peerIdentifier matches
[39m
[32mok 390 error description matches
[39m
[32m# teardown
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: listening 51563
[39m
[36mok 387 peerIdentifier matches
[39m
[36mok 388 error description matches
[39m
[36m# teardown
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: listening 51565
[39m
[33mok 384 peerIdentifier matches
[39m
[33mok 385 error description matches
[39m
[33m# teardown
[39m
[32mok 391 must be stopped
[39m
[32m# setup
[39m
[33mok 386 must be stopped
[39m
[33m# setup
[39m
[36mok 389 must be stopped
[39m
[36m# setup
[39m
2016-08-16T07:40:02.730Z - info: Running on ios test: 92. can do HTTP requests between peers without coordinator

[32mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[32mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 92. can do HTTP requests between peers without coordinator
[39m
[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[36m# 92. can do HTTP requests between peers without coordinator
[39m
[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[33m# 92. can do HTTP requests between peers without coordinator
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: listening 51567
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG testUtils: We got a peer {"peerIdentifier":"foo","portNumber":51570,"hostAddress":"127.0.0.1"}
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[32mWARN testUtils: Retry count for getSamePeerWithRetry is 1
[39m
[36mDEBUG createNativeListener: listening 51572
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: first connection
[39m
[36mDEBUG testUtils: We got a peer {"peerIdentifier":"foo","portNumber":51578,"hostAddress":"127.0.0.1"}
[39m
[36mWARN testUtils: Retry count for getSamePeerWithRetry is 1
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: listening 51587
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG testUtils: We got a peer {"peerIdentifier":"foo","portNumber":51590,"hostAddress":"127.0.0.1"}
[39m
[33mWARN testUtils: Retry count for getSamePeerWithRetry is 1
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createNativeListener: new incoming socket
[39m
[33mDEBUG createNativeListener: creating incoming mux
[39m
[33mDEBUG createNativeListener: new mux
[39m
[33mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[36mok 390 Should only get expected id
[39m
[32mok 392 Should only get expected id
[39m
[36mok 391 response body should match testData
# teardown
[39m
[32mok 393 response body should match testData
[39m
[32m# teardown
[39m
[33mDEBUG createPeerListener: forward connection
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mok 387 Should only get expected id
[39m
[33mok 388 response body should match testData
[39m
[33m# teardown
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[36mDEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[32mDEBUG createNativeListener: mux close
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[32mok 394 must be stopped
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createNativeListener: mux close
[39m
[36mok 392 must be stopped
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[32m# setup
[39m
[36m# setup
[39m
[33mDEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
[39m
[33mDEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: mux close
[39m
[33mok 389 must be stopped
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[33m# setup
[39m
2016-08-16T07:40:02.934Z - info: Running on ios test: 93. make sure bad PSK connections fail

[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[32mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[36m# 93. make sure bad PSK connections fail
[39m
[32mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[32m# 93. make sure bad PSK connections fail
[39m
[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[33m# 93. make sure bad PSK connections fail
[39m
[32mok 395 FIX ME, PLEASE!!!
[39m
[32m# teardown
[39m
[36mok 393 FIX ME, PLEASE!!!
[39m
[36m# teardown
[39m
[33mok 390 FIX ME, PLEASE!!!
[39m
[33m# teardown
[39m
[36mok 394 must be stopped
[39m
[36m# setup
[39m
[32mok 396 must be stopped
[39m
[32m# setup
[39m
[33mok 391 must be stopped
[39m
[33m# setup
[39m
2016-08-16T07:40:02.969Z - info: Running on ios test: 94. peer changes handled from a queue

[32mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[32m# 94. peer changes handled from a queue
[39m
[36mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[36m# 94. peer changes handled from a queue
[39m
[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[33m# 94. peer changes handled from a queue
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: listening 51604
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createNativeListener: listening 51606
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mok 395 peers were handled in the right order
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mok 397 peers were handled in the right order
# teardown
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51628
DEBUG createPeerListener: createPeerListener creating new server
[39m
[36m# teardown
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mok 392 peers were handled in the right order
[39m
[33m# teardown
[39m
[33mok 393 must be stopped
# setup
[39m
[32mok 398 must be stopped
# setup
[39m
[36mok 396 must be stopped
[39m
[36m# setup
[39m
2016-08-16T07:40:03.035Z - info: Running on ios test: 95. relaying discoveryAdvertisingStateUpdateNonTCP

[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 95. relaying discoveryAdvertisingStateUpdateNonTCP
[39m
[32mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 95. relaying discoveryAdvertisingStateUpdateNonTCP
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 95. relaying discoveryAdvertisingStateUpdateNonTCP
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51640
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 394 discovery is active
ok 395 advertising is active
# teardown
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: listening 51642
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 399 discovery is active
ok 400 advertising is active
# teardown
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: listening 51644
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[36mok 397 discovery is active
[39m
[36mok 398 advertising is active
[39m
[36m# teardown
[39m
[33mok 396 must be stopped
# setup
[39m
[36mok 399 must be stopped
# setup
[39m
[32mok 401 must be stopped
[39m
[32m# setup
[39m
2016-08-16T07:40:03.067Z - info: Running on ios test: 96. thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received

[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 96. thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
[39m
[32mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[32mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 96. thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
[39m
[36mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[36m# 96. thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51646
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: 51646
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51649
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[36mINFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: 51649
[39m
[33mok 397 right error reason
ok 398 Stop should be fine
ok 399 same port
ok 400 we should be off
# teardown
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[36mok 400 right error reason
ok 401 Stop should be fine
ok 402 same port
ok 403 we should be off
# teardown
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: listening 51654
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[32mINFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: 51654
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[32mok 402 right error reason
[39m
[32mok 403 Stop should be fine
ok 404 same port
[39m
[32mok 405 we should be off
[39m
[32m# teardown
[39m
[33mok 401 must be stopped
# setup
[39m
[32mok 406 must be stopped
# setup
[39m
[36mok 404 must be stopped
[39m
[36m# setup
[39m
2016-08-16T07:40:03.112Z - info: Running on ios test: 97. we successfully receive and replay discoveryAdvertisingStateUpdate

[32mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[33m# 97. we successfully receive and replay discoveryAdvertisingStateUpdate
[39m
[32mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[32mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[32m# 97. we successfully receive and replay discoveryAdvertisingStateUpdate
[39m
[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 97. we successfully receive and replay discoveryAdvertisingStateUpdate
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51659
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 402 discoveryActive matches
ok 403 advertisingActive matches
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 404 discoveryActive matches
ok 405 advertisingActive matches
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51662
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 406 discoveryActive matches
ok 407 advertisingActive matches
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51660
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 407 discoveryActive matches
ok 408 advertisingActive matches
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 409 discoveryActive matches
ok 410 advertisingActive matches
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51665
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[32mok 411 discoveryActive matches
[39m
[32mok 412 advertisingActive matches
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 413 discoveryActive matches
ok 414 advertisingActive matches
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51670
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[36mok 405 discoveryActive matches
ok 406 advertisingActive matches
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51672
# teardown
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 407 discoveryActive matches
[39m
[36mok 408 advertisingActive matches
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 408 discoveryActive matches
ok 409 advertisingActive matches
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: listening 51674
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51678
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 409 discoveryActive matches
ok 410 advertisingActive matches
[39m
[33m# teardown
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 411 discoveryActive matches
[39m
[36mok 412 advertisingActive matches
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: listening 51680
[39m
[36m# teardown
[39m
[36mok 413 must be stopped
# setup
[39m
[32mok 415 must be stopped
# setup
[39m
[33mok 410 must be stopped
[39m
[33m# setup
[39m
2016-08-16T07:40:03.166Z - info: Running on ios test: 98. can do HTTP requests between peers

[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[32mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 98. can do HTTP requests between peers
[39m
[32mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[32m# 98. can do HTTP requests between peers
[39m
[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[33m# 98. can do HTTP requests between peers
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51683
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51684
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG testUtils: We got a peer {"peerIdentifier":"urn:uuid:b044169b-8427-4638-9ba2-3ba56beaf97a","portNumber":51689,"hostAddress":"127.0.0.1"}
WARN testUtils: Retry count for getSamePeerWithRetry is 1
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: listening 51692
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG testUtils: We got a peer {"peerIdentifier":"urn:uuid:2774c5ec-032f-4d6b-b1d3-b9193887e087","portNumber":51693,"hostAddress":"127.0.0.1"}
WARN testUtils: Retry count for getSamePeerWithRetry is 1
[39m
[32mDEBUG createPeerListener: first connection
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[36mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[36mok 414 Should only get expected id
[39m
[32mok 416 Should only get expected id
[39m
[32mok 417 response body should match testData
[39m
[32mok 418 must be started
[39m
[32m# teardown
[39m
[36mok 415 response body should match testData
[39m
[36mok 416 must be started
[39m
[36m# teardown
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG testUtils: We got a peer {"peerIdentifier":"urn:uuid:2774c5ec-032f-4d6b-b1d3-b9193887e087","portNumber":51709,"hostAddress":"127.0.0.1"}
[39m
[33mWARN testUtils: Retry count for getSamePeerWithRetry is 1
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG createPeerListener: forward connection
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mok 419 Should only get expected id
[39m
[33mok 411 response body should match testData
[39m
[33mok 412 must be started
[39m
[33m# teardown
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
ok 420 must be stopped
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
# setup
[39m
[36mDEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
ok 417 must be stopped
DEBUG createNativeListener: incoming socket close
# setup
[39m
[33mDEBUG createPeerListener: Recreating listener
DEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mok 413 must be stopped
[39m
[33m# setup
[39m
2016-08-16T07:40:03.837Z - info: Running on ios test: 99. can still do HTTP requests between peers

[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 99. can still do HTTP requests between peers
[39m
[32mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 99. can still do HTTP requests between peers
[39m
[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 99. can still do HTTP requests between peers
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51719
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51722
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG testUtils: We got a peer {"peerIdentifier":"urn:uuid:d49632f8-2441-4b12-ad09-595ec0cca523","portNumber":51726,"hostAddress":"127.0.0.1"}
WARN testUtils: Retry count for getSamePeerWithRetry is 1
DEBUG createPeerListener: first connection
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51728
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
DEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG testUtils: We got a peer {"peerIdentifier":"urn:uuid:5c9b1b5e-64e6-4505-8160-d893da23d2e1","portNumber":51733,"hostAddress":"127.0.0.1"}
WARN testUtils: Retry count for getSamePeerWithRetry is 1
DEBUG createPeerListener: first connection
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG testUtils: We got a peer {"peerIdentifier":"urn:uuid:5c9b1b5e-64e6-4505-8160-d893da23d2e1","portNumber":51735,"hostAddress":"127.0.0.1"}
WARN testUtils: Retry count for getSamePeerWithRetry is 1
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: first connection
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[36mok 418 Should only get expected id
[39m
[32mok 421 Should only get expected id
[39m
[36mok 419 Should only get expected id
[39m
[33mok 414 response body should match testData
ok 415 must be started
# teardown
[39m
[36mok 420 response body should match testData
[39m
[36mok 421 must be started
[39m
[36m# teardown
[39m
[32mok 422 response body should match testData
ok 423 must be started
[39m
[32m# teardown
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
ok 424 must be stopped
DEBUG createNativeListener: incoming socket close
# setup
[39m
[36mDEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
ok 422 must be stopped
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
# setup
[39m
[33mDEBUG createPeerListener: Recreating listener
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mok 416 must be stopped
[39m
[33m# setup
[39m
2016-08-16T07:40:04.024Z - info: Running on ios test: 100. test to coordinate connection cut

[32mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 100. test to coordinate connection cut
[39m
[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 100. test to coordinate connection cut
[39m
[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 100. test to coordinate connection cut
[39m
[32mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
# teardown
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
# teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
# teardown
[39m
[32mok 425 must be stopped
# setup
[39m
[33mok 417 must be stopped
# setup
[39m
[36mok 423 must be stopped
[39m
[36m# setup
[39m
2016-08-16T07:40:04.051Z - info: Running on ios test: 101. can do HTTP requests after connections are cut

[32mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[33m# 101. can do HTTP requests after connections are cut
[39m
[32mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[32m# 101. can do HTTP requests after connections are cut
[39m
[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[36m# 101. can do HTTP requests after connections are cut
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51755
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51758
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51761
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
DEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG testUtils: We got a peer {"peerIdentifier":"urn:uuid:5deca933-a770-4854-a53c-60d89e57da61","portNumber":51765,"hostAddress":"127.0.0.1"}
WARN testUtils: Retry count for getSamePeerWithRetry is 1
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG testUtils: We got a peer {"peerIdentifier":"urn:uuid:286d8504-5fb9-4c07-b261-b0b77af9f73d","portNumber":51768,"hostAddress":"127.0.0.1"}
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mWARN testUtils: Retry count for getSamePeerWithRetry is 1
[39m
[32mDEBUG createPeerListener: first connection
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createNativeListener: new incoming socket
[39m
[33mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG testUtils: We got a peer {"peerIdentifier":"urn:uuid:8af550a1-6f0d-4353-9842-b96569e0d06a","portNumber":51775,"hostAddress":"127.0.0.1"}
WARN testUtils: Retry count for getSamePeerWithRetry is 1
[39m
[33mDEBUG createNativeListener: new mux
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[32mDEBUG createNativeListener: new mux
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG createPeerListener: forward connection
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[33mok 418 Should only get expected id
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[36mok 424 Should only get expected id
[39m
[32mok 426 Should only get expected id
[39m
[32mok 427 response body should match testData
[39m
[32mok 428 must be started
[39m
[32m# teardown
[39m
[33mok 419 response body should match testData
[39m
[33mok 420 must be started
[39m
[33m# teardown
[39m
[36mok 425 response body should match testData
[39m
[36mok 426 must be started
[39m
[36m# teardown
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: mux close
[39m
[32mok 429 must be stopped
[39m
[36mok 427 must be stopped
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[36m# setup
[39m
[32m# setup
[39m
[33mDEBUG createPeerListener: Recreating listener
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mok 421 must be stopped
[39m
[33m# setup
[39m
2016-08-16T07:40:04.259Z - info: Running on ios test: 102. will fail bad PSK connection between peers

[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36m# 102. will fail bad PSK connection between peers
[39m
[32mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[32m# 102. will fail bad PSK connection between peers
[39m
[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[33m# 102. will fail bad PSK connection between peers
[39m
[36mok 428 FIX ME, PLEASE!!!
[39m
[36m# teardown
[39m
[32mok 430 FIX ME, PLEASE!!!
[39m
[32m# teardown
[39m
[33mok 422 FIX ME, PLEASE!!!
[39m
[33m# teardown
[39m
[36mok 429 must be stopped
[39m
[36m# setup
[39m
[32mok 431 must be stopped
[39m
[32m# setup
[39m
[33mok 423 must be stopped
[39m
[33m# setup
[39m
2016-08-16T07:40:04.292Z - info: Running on ios test: 103. We provide notification when a listener dies and we recreate it

[32mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[36m# 103. We provide notification when a listener dies and we recreate it
[39m
[33mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[33m# 103. We provide notification when a listener dies and we recreate it
[39m
[32mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[32m# 103. We provide notification when a listener dies and we recreate it
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51791
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51795
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG testUtils: We got a peer {"peerIdentifier":"urn:uuid:67ee804c-b45b-468d-9f27-593288275ae0","portNumber":51798,"hostAddress":"127.0.0.1"}
WARN testUtils: Retry count for getSamePeerWithRetry is 1
[39m
[36mDEBUG createPeerListener: first connection
[39m
[33mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
[39m
[33mDEBUG createNativeListener: new mux
[39m
[33mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: listening 51804
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG testUtils: We got a peer {"peerIdentifier":"urn:uuid:d03d4741-efb4-4f6f-a8a6-e1010324d589","portNumber":51807,"hostAddress":"127.0.0.1"}
[39m
[33mWARN testUtils: Retry count for getSamePeerWithRetry is 1
[39m
[33mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mok 424 Should only get expected id
[39m
[33mDEBUG createPeerListener: forward connection
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[36mok 430 response body should match testData
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[36mok 431 About to destroy connection to peer
[39m
[36mDEBUG wifiBasedNativeMock: got an end on peerProxySockets
[39m
[36mDEBUG createPeerListener: Recreating listener
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG testUtils: We got a peer {"peerIdentifier":"urn:uuid:67ee804c-b45b-468d-9f27-593288275ae0","portNumber":51817,"hostAddress":"127.0.0.1"}
[39m
[36mWARN testUtils: Retry count for getSamePeerWithRetry is 1
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[36mok 432 same ids
[39m
[36mDEBUG createPeerListener: first connection
[39m
[33mDEBUG createNativeListener: new incoming socket
[39m
[33mDEBUG createNativeListener: creating incoming mux
[39m
[33mDEBUG createNativeListener: new mux
[39m
[33mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mok 432 Should only get expected id
[39m
[33mok 425 response body should match testData
[39m
[33mok 426 About to destroy connection to peer
[39m
[33mDEBUG wifiBasedNativeMock: got an end on peerProxySockets
[39m
[33mDEBUG createPeerListener: Recreating listener
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG testUtils: We got a peer {"peerIdentifier":"urn:uuid:d03d4741-efb4-4f6f-a8a6-e1010324d589","portNumber":51822,"hostAddress":"127.0.0.1"}
[39m
[33mWARN testUtils: Retry count for getSamePeerWithRetry is 1
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[33mok 427 same ids
[39m
[33mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mok 428 Should only get expected id
[39m
[36mok 433 recreate - response body should match testData
[39m
[36m# teardown
[39m
[33mDEBUG createPeerListener: forward connection
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mok 433 Should only get expected id
[39m
[33mok 429 recreate - response body should match testData
[39m
[33m# teardown
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG testUtils: We got a peer {"peerIdentifier":"urn:uuid:1b1d7575-271b-43cf-af90-04ba0d215c8a","portNumber":51831,"hostAddress":"127.0.0.1"}
WARN testUtils: Retry count for getSamePeerWithRetry is 1
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mok 434 Should only get expected id
[39m
[32mok 434 response body should match testData
[39m
[32mok 435 About to destroy connection to peer
[39m
[32mDEBUG wifiBasedNativeMock: got an end on peerProxySockets
[39m
[32mDEBUG createPeerListener: Recreating listener
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG testUtils: We got a peer {"peerIdentifier":"urn:uuid:1b1d7575-271b-43cf-af90-04ba0d215c8a","portNumber":51840,"hostAddress":"127.0.0.1"}
WARN testUtils: Retry count for getSamePeerWithRetry is 1
ok 436 same ids
DEBUG createPeerListener: first connection
[39m
[36mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mok 435 Should only get expected id
[39m
[32mok 437 recreate - response body should match testData
[39m
[32m# teardown
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
ok 438 must be stopped
DEBUG createNativeListener: incoming socket close
# setup
[39m
[36mDEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
ok 436 must be stopped
DEBUG createNativeListener: incoming socket close
# setup
[39m
[33mDEBUG createPeerListener: Recreating listener
DEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mok 430 must be stopped
[39m
[33m# setup
[39m
2016-08-16T07:40:05.099Z - info: Running on ios test: 104. Client to server request coordinated

[32m# 104. Client to server request coordinated
[39m
[36m# 104. Client to server request coordinated
[39m
[33m# 104. Client to server request coordinated
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51849
ok 439 error should be null
ok 440 error should be null
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
INFO testThaliNotification: startListeningForAdvertisements
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51851
ok 437 error should be null
ok 438 error should be null
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
INFO testThaliNotification: startListeningForAdvertisements
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51856
ok 431 error should be null
ok 432 error should be null
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: first connection
DEBUG createPeerListener: first connection
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
INFO testThaliNotification: startListeningForAdvertisements
[39m
[33mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mINFO testThaliNotification: PeerAdvertisesDataForUs:tcp, 192.168.1.20, 192.168.1.20, 51860
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[36mDEBUG createPeerListener: first connection
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG createNativeListener: new incoming socket
[39m
[33mDEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[33mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mINFO testThaliNotification: PeerAdvertisesDataForUs:tcp, 192.168.1.20, 192.168.1.20, 51857
[39m
[36mINFO testThaliNotification: PeerAdvertisesDataForUs:tcp, 192.168.1.20, 192.168.1.20, 51860
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[32mINFO testThaliNotification: PeerAdvertisesDataForUs:MPCF, 127.0.0.1, 127.0.0.1, 51863
[39m
[36mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: 
DEBUG createNativeListener: stream close:
[39m
[32mINFO testThaliNotification: PeerAdvertisesDataForUs:MPCF, 127.0.0.1, 127.0.0.1, 51867
[39m
[33mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: 
DEBUG createNativeListener: stream close:
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createPeerListener: error on incoming stream - Error: Channel destroyed
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createPeerListener: error on incoming stream - Error: Channel destroyed
[39m
[36mINFO testThaliNotification: PeerAdvertisesDataForUs:MPCF, 127.0.0.1, 127.0.0.1, 51875
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: 
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createPeerListener: error on incoming stream - Error: Channel destroyed
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: first connection
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG createPeerListener: first connection
[39m
[36mINFO testThaliNotification: PeerAdvertisesDataForUs:tcp, 192.168.1.20, 192.168.1.20, 51852
[39m
[36mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mINFO testThaliNotification: PeerAdvertisesDataForUs:tcp, 192.168.1.20, 192.168.1.20, 51852
[39m
[33mINFO testThaliNotification: PeerAdvertisesDataForUs:tcp, 192.168.1.20, 192.168.1.20, 51857
[39m
[33mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[36mINFO testThaliNotification: PeerAdvertisesDataForUs:MPCF, 127.0.0.1, 127.0.0.1, 51897
[39m
[33mINFO testThaliNotification: PeerAdvertisesDataForUs:MPCF, 127.0.0.1, 127.0.0.1, 51896
[39m
[32mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: 
DEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: 
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[33mINFO testThaliNotification: PeerAdvertisesDataForUs:MPCF, 127.0.0.1, 127.0.0.1, 51907
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createPeerListener: error on incoming stream - Error: Channel destroyed
DEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: 
DEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createPeerListener: error on incoming stream - Error: Channel destroyed
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createPeerListener: error on incoming stream - Error: Channel destroyed
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 441 Peer made successful https requests to all peers
ok 442 Peer received right amount of https requests
ok 443 HTTPS server received zero PSK Identities. Count:0
DEBUG createPeerListener: Recreating listener
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: Recreating listener
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
# teardown
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 439 Peer made successful https requests to all peers
ok 440 Peer received right amount of https requests
ok 441 HTTPS server received zero PSK Identities. Count:0
DEBUG createPeerListener: Recreating listener
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: Recreating listener
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
# teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mok 433 Peer made successful https requests to all peers
[39m
[33mok 434 Peer received right amount of https requests
[39m
[33mok 435 HTTPS server received zero PSK Identities. Count:0
[39m
[33mDEBUG createPeerListener: Recreating listener
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: Recreating listener
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[33m# teardown
[39m
[36mINFO testThaliNotification: Participants:3 Peers Replied to us:2 Peers requested to:2
DEBUG createNativeListener: mux close
DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
[39m
[32mINFO testThaliNotification: Participants:3 Peers Replied to us:2 Peers requested to:2
DEBUG createNativeListener: mux close
DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
[39m
[33mINFO testThaliNotification: Participants:3 Peers Replied to us:2 Peers requested to:2
[39m
[33m# setup
[39m
2016-08-16T07:40:10.157Z - info: Running on ios test: 105. Test BEACONS_RETRIEVED_AND_PARSED locally

[36m# 105. Test BEACONS_RETRIEVED_AND_PARSED locally
[39m
[32m# 105. Test BEACONS_RETRIEVED_AND_PARSED locally
[39m
[33m# 105. Test BEACONS_RETRIEVED_AND_PARSED locally
[39m
[36mok 442 peerIdentifier should be identifier
ok 443 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 444 good beacon
ok 445 good preAmble
ok 446 public keys match!
ok 447 must return null after successful call
ok 448 Once start returns the action should be in KILLED state
# teardown
[39m
[32mok 444 peerIdentifier should be identifier
ok 445 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 446 good beacon
ok 447 good preAmble
ok 448 public keys match!
ok 449 must return null after successful call
ok 450 Once start returns the action should be in KILLED state
# teardown
[39m
[33mok 436 peerIdentifier should be identifier
ok 437 Response should be BEACONS_RETRIEVED_AND_PARSED
[39m
[33mok 438 good beacon
[39m
[33mok 439 good preAmble
ok 440 public keys match!
[39m
[33mok 441 must return null after successful call
[39m
[33mok 442 Once start returns the action should be in KILLED state
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:40:10.211Z - info: Running on ios test: 106. Test HTTP_BAD_RESPONSE locally

[32m# 106. Test HTTP_BAD_RESPONSE locally
[39m
[36m# 106. Test HTTP_BAD_RESPONSE locally
[39m
[33m# 106. Test HTTP_BAD_RESPONSE locally
[39m
[36mok 449 Response should be HTTP_BAD_RESPONSE
[39m
[33mok 443 Response should be HTTP_BAD_RESPONSE
[39m
[33mok 444 must return null after successful call
[39m
[36mok 450 must return null after successful call
[39m
[33m# teardown
[39m
[36m# teardown
[39m
[32mok 451 Response should be HTTP_BAD_RESPONSE
[39m
[32mok 452 must return null after successful call
[39m
[32m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-16T07:40:10.263Z - info: Running on ios test: 107. Test NETWORK_PROBLEM locally

[33m# 107. Test NETWORK_PROBLEM locally
[39m
[36m# 107. Test NETWORK_PROBLEM locally
[39m
[32m# 107. Test NETWORK_PROBLEM locally
[39m
[36mok 451 Response should be NETWORK_PROBLEM
[39m
[33mok 445 Response should be NETWORK_PROBLEM
[39m
[33mok 446 reject reason should be: Could not establish TCP connection
[39m
[36mok 452 reject reason should be: Could not establish TCP connection
[39m
[33m# teardown
[39m
[36m# teardown
[39m
[32mok 453 Response should be NETWORK_PROBLEM
[39m
[32mok 454 reject reason should be: Could not establish TCP connection
[39m
[32m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:40:10.308Z - info: Running on ios test: 108. Call the start two times

[32m# 108. Call the start two times
[39m
[36m# 108. Call the start two times
[39m
[33m# 108. Call the start two times
[39m
[32mok 455 Call start once
[39m
[36mok 453 Call start once
[39m
[33mok 447 Call start once
[39m
[32mok 456 Response should be BEACONS_RETRIEVED_AND_PARSED
[39m
[32mok 457 must return null after successful call.
[39m
[32m# teardown
[39m
[33mok 448 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 449 must return null after successful call.
# teardown
[39m
[36mok 454 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 455 must return null after successful call.
# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-16T07:40:10.360Z - info: Running on ios test: 109. Call the kill before calling the start

[36m# 109. Call the kill before calling the start
[39m
[33m# 109. Call the kill before calling the start
[39m
[32m# 109. Call the kill before calling the start
[39m
[33mok 450 Should be Killed
ok 451 Start after killed
# teardown
[39m
[36mok 456 Should be Killed
ok 457 Start after killed
# teardown
[39m
[32mok 458 Should be Killed
[39m
[32mok 459 Start after killed
[39m
[32m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-16T07:40:10.399Z - info: Running on ios test: 110. Call the kill immediately after the start

[36m# 110. Call the kill immediately after the start
[39m
[33m# 110. Call the kill immediately after the start
[39m
[32m# 110. Call the kill immediately after the start
[39m
[33mok 452 Should be KILLED
ok 453 must return null after successful kill
# teardown
[39m
[36mok 458 Should be KILLED
ok 459 must return null after successful kill
# teardown
[39m
[32mok 460 Should be KILLED
[39m
[32mok 461 must return null after successful kill
[39m
[32m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-16T07:40:10.435Z - info: Running on ios test: 111. Call the kill while waiting a response from the server

[36m# 111. Call the kill while waiting a response from the server
[39m
[33m# 111. Call the kill while waiting a response from the server
[39m
[32m# 111. Call the kill while waiting a response from the server
[39m
[33mok 454 Should be KILLED
ok 455 must return null after successful kill
# teardown
[39m
[36mok 460 Should be KILLED
ok 461 must return null after successful kill
# teardown
[39m
[32mok 462 Should be KILLED
[39m
[32mok 463 must return null after successful kill
[39m
[32m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-16T07:40:12.482Z - info: Running on ios test: 112. Test to exceed the max content size locally

[36m# 112. Test to exceed the max content size locally
[39m
[32m# 112. Test to exceed the max content size locally
[39m
[33m# 112. Test to exceed the max content size locally
[39m
[36mok 462 HTTP_BAD_RESPONSE should be response when content size is exceeded
ok 463 must return null after successful call
# teardown
[39m
[32mok 464 HTTP_BAD_RESPONSE should be response when content size is exceeded
ok 465 must return null after successful call
# teardown
[39m
[33mok 456 HTTP_BAD_RESPONSE should be response when content size is exceeded
[39m
[33mok 457 must return null after successful call
[39m
[33m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-16T07:40:12.537Z - info: Running on ios test: 113. Close the server socket while the client is waiting a response from the server. Local test.

[32m# 113. Close the server socket while the client is waiting a response from the server. Local test.
[39m
[36m# 113. Close the server socket while the client is waiting a response from the server. Local test.
[39m
[33m# 113. Close the server socket while the client is waiting a response from the server. Local test.
[39m
[32mok 466 Should be NETWORK_PROBLEM caused closing server socket
ok 467 Should be Could not establish TCP connection
# teardown
[39m
[36mok 464 Should be NETWORK_PROBLEM caused closing server socket
ok 465 Should be Could not establish TCP connection
# teardown
[39m
[33mok 458 Should be NETWORK_PROBLEM caused closing server socket
[39m
[33mok 459 Should be Could not establish TCP connection
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:40:14.582Z - info: Running on ios test: 114. Close the client socket while the client is waiting a response from the server. Local test.

[32m# 114. Close the client socket while the client is waiting a response from the server. Local test.
[39m
[36m# 114. Close the client socket while the client is waiting a response from the server. Local test.
[39m
[33m# 114. Close the client socket while the client is waiting a response from the server. Local test.
[39m
[33mok 460 Should be NETWORK_PROBLEM caused closing client socket
ok 461 Should be Could not establish TCP connection
# teardown
[39m
[32mok 468 Should be NETWORK_PROBLEM caused closing client socket
ok 469 Should be Could not establish TCP connection
# teardown
[39m
[36mok 466 Should be NETWORK_PROBLEM caused closing client socket
ok 467 Should be Could not establish TCP connection
[39m
[36m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:40:16.627Z - info: Running on ios test: 115. #generatePreambleAndBeacons bad args

[32m# 115. #generatePreambleAndBeacons bad args
[39m
[36m# 115. #generatePreambleAndBeacons bad args
[39m
[33m# 115. #generatePreambleAndBeacons bad args
[39m
[36mok 468 publicKeysToNotify cannot be null
ok 469 ecdh for local device cannot be null
ok 470 milliseconds cannot be less than 0
ok 471 milliseconds cannot be 0
ok 472 milliseconds cannot be greater than one_day
# teardown
[39m
[32mok 470 publicKeysToNotify cannot be null
ok 471 ecdh for local device cannot be null
ok 472 milliseconds cannot be less than 0
ok 473 milliseconds cannot be 0
ok 474 milliseconds cannot be greater than one_day
# teardown
[39m
[33mok 462 publicKeysToNotify cannot be null
ok 463 ecdh for local device cannot be null
[39m
[33mok 464 milliseconds cannot be less than 0
[39m
[33mok 465 milliseconds cannot be 0
[39m
[33mok 466 milliseconds cannot be greater than one_day
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:40:16.651Z - info: Running on ios test: 116. #generatePreambleAndBeacons empty keys to notify

[32m# 116. #generatePreambleAndBeacons empty keys to notify
[39m
[36m# 116. #generatePreambleAndBeacons empty keys to notify
[39m
[33m# 116. #generatePreambleAndBeacons empty keys to notify
[39m
[32mok 475 should be equal
# teardown
[39m
[36mok 473 should be equal
# teardown
[39m
[33mok 467 should be equal
# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:40:16.674Z - info: Running on ios test: 117. #generatePreambleAndBeacons multiple keys to notify

[32m# 117. #generatePreambleAndBeacons multiple keys to notify
[39m
[36m# 117. #generatePreambleAndBeacons multiple keys to notify
[39m
[33m# 117. #generatePreambleAndBeacons multiple keys to notify
[39m
[32mok 476 should be equal
ok 477 should be equal
ok 478 (unnamed assert)
ok 479 should be equal
# teardown
[39m
[36mok 474 should be equal
ok 475 should be equal
ok 476 (unnamed assert)
ok 477 should be equal
# teardown
[39m
[33mok 468 should be equal
ok 469 should be equal
[39m
[33mok 470 (unnamed assert)
[39m
[33mok 471 should be equal
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:40:16.713Z - info: Running on ios test: 118. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

[36m# 118. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
[39m
[33m# 118. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
[39m
[32m# 118. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
[39m
[36mok 478 should throw
# teardown
[39m
[32mok 480 should throw
# teardown
[39m
[33mok 472 should throw
[39m
[33m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-16T07:40:16.738Z - info: Running on ios test: 119. #parseBeacons invalid expiration in beaconStreamWithPreAmble

[32m# 119. #parseBeacons invalid expiration in beaconStreamWithPreAmble
[39m
[33m# 119. #parseBeacons invalid expiration in beaconStreamWithPreAmble
[39m
[36m# 119. #parseBeacons invalid expiration in beaconStreamWithPreAmble
[39m
[32mok 481 Preamble expiration must be a 64 bit integer
# teardown
[39m
[36mok 479 Preamble expiration must be a 64 bit integer
# teardown
[39m
[33mok 473 Preamble expiration must be a 64 bit integer
# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-16T07:40:16.763Z - info: Running on ios test: 120. #parseBeacons expiration out of range lower

[32m# 120. #parseBeacons expiration out of range lower
[39m
[36m# 120. #parseBeacons expiration out of range lower
[39m
[33m# 120. #parseBeacons expiration out of range lower
[39m
[32mok 482 Expiration out of range
# teardown
[39m
[36mok 480 Expiration out of range
# teardown
[39m
[33mok 474 Expiration out of range
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:40:16.788Z - info: Running on ios test: 121. #parseBeacons expiration out of range lower

[36m# 121. #parseBeacons expiration out of range lower
[39m
[32m# 121. #parseBeacons expiration out of range lower
[39m
[33m# 121. #parseBeacons expiration out of range lower
[39m
[32mok 483 Expiration out of range
# teardown
[39m
[36mok 481 Expiration out of range
# teardown
[39m
[33mok 475 Expiration out of range
[39m
[33m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-16T07:40:16.817Z - info: Running on ios test: 122. #parseBeacons no beacons returns null

[36m# 122. #parseBeacons no beacons returns null
[39m
[32m# 122. #parseBeacons no beacons returns null
[39m
[33m# 122. #parseBeacons no beacons returns null
[39m
[32mok 484 should be equal
# teardown
[39m
[36mok 482 should be equal
[39m
[36m# teardown
[39m
[33mok 476 should be equal
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:40:16.843Z - info: Running on ios test: 123. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

[32m# 123. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
[39m
[36m# 123. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
[39m
[33m# 123. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
[39m
[32mok 485 Malformed encrypted beacon key ID
# teardown
[39m
[36mok 483 Malformed encrypted beacon key ID
# teardown
[39m
[33mok 477 Malformed encrypted beacon key ID
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:40:16.867Z - info: Running on ios test: 124. #parseBeacons addressBookCallback fails decrypt

[36m# 124. #parseBeacons addressBookCallback fails decrypt
[39m
[32m# 124. #parseBeacons addressBookCallback fails decrypt
[39m
[33m# 124. #parseBeacons addressBookCallback fails decrypt
[39m
[36mok 484 should be equal
# teardown
[39m
[32mok 486 should be equal
[39m
[32m# teardown
[39m
[33mok 478 should be equal
[39m
[33m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-16T07:40:16.905Z - info: Running on ios test: 125. #parseBeacons addressBookCallback returns no matches

[32m# 125. #parseBeacons addressBookCallback returns no matches
[39m
[36m# 125. #parseBeacons addressBookCallback returns no matches
[39m
[33m# 125. #parseBeacons addressBookCallback returns no matches
[39m
[32mok 487 should be equal
[39m
[32mok 488 should be equal
[39m
[32m# teardown
[39m
[36mok 485 should be equal
[39m
[36mok 486 should be equal
[39m
[36m# teardown
[39m
[33mok 479 should be equal
[39m
[33mok 480 should be equal
[39m
[33m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-16T07:40:16.940Z - info: Running on ios test: 126. #parseBeacons addressBookCallback returns spurious match

[32m# 126. #parseBeacons addressBookCallback returns spurious match
[39m
[36m# 126. #parseBeacons addressBookCallback returns spurious match
[39m
[33m# 126. #parseBeacons addressBookCallback returns spurious match
[39m
[36mok 487 should be equal
[39m
[36mok 488 should be equal
[39m
[32mok 489 should be equal
[39m
[32mok 490 should be equal
[39m
[32m# teardown
[39m
[36m# teardown
[39m
[33mok 481 should be equal
[39m
[33mok 482 should be equal
[39m
[33m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-16T07:40:16.984Z - info: Running on ios test: 127. #parseBeacons addressBookCallback returns public key

[32m# 127. #parseBeacons addressBookCallback returns public key
[39m
[36m# 127. #parseBeacons addressBookCallback returns public key
[39m
[33m# 127. #parseBeacons addressBookCallback returns public key
[39m
[36mok 489 right number of calls to address book
[39m
[32mok 491 right number of calls to address book
[39m
[32mok 492 good preAmble
[39m
[36mok 490 good preAmble
[39m
[36mok 491 good unencryptedKeyId
ok 492 good beacon
# teardown
[39m
[32mok 493 good unencryptedKeyId
[39m
[32mok 494 good beacon
[39m
[32m# teardown
[39m
[33mok 483 right number of calls to address book
[39m
[33mok 484 good preAmble
ok 485 good unencryptedKeyId
ok 486 good beacon
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:40:17.028Z - info: Running on ios test: 128. validate generatePskIdentityField

[32m# 128. validate generatePskIdentityField
[39m
[36m# 128. validate generatePskIdentityField
[39m
[33m# 128. validate generatePskIdentityField
[39m
[32mok 495 decoded buffers match
[39m
[32m# teardown
[39m
[36mok 493 decoded buffers match
[39m
[36m# teardown
[39m
[33mok 487 decoded buffers match
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:40:17.053Z - info: Running on ios test: 129. validate generatePskSecret

[32m# 129. validate generatePskSecret
[39m
[36m# 129. validate generatePskSecret
[39m
[33m# 129. validate generatePskSecret
[39m
[32mok 496 secrets match
# teardown
[39m
[36mok 494 secrets match
# teardown
[39m
[33mok 488 secrets match
[39m
[33m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-16T07:40:17.083Z - info: Running on ios test: 130. validate generatePskSecrets

[32m# 130. validate generatePskSecrets
[39m
[36m# 130. validate generatePskSecrets
[39m
[33m# 130. validate generatePskSecrets
[39m
[32mok 497 Matching numbers
ok 498 We have an entry!
ok 499 keys match
ok 500 secrets match
ok 501 We have an entry!
ok 502 keys match
ok 503 secrets match
ok 504 We have an entry!
ok 505 keys match
ok 506 secrets match
# teardown
[39m
[36mok 495 Matching numbers
ok 496 We have an entry!
ok 497 keys match
ok 498 secrets match
ok 499 We have an entry!
ok 500 keys match
ok 501 secrets match
ok 502 We have an entry!
ok 503 keys match
ok 504 secrets match
# teardown
[39m
[33mok 489 Matching numbers
[39m
[33mok 490 We have an entry!
[39m
[33mok 491 keys match
ok 492 secrets match
[39m
[33mok 493 We have an entry!
[39m
[33mok 494 keys match
ok 495 secrets match
[39m
[33mok 496 We have an entry!
[39m
[33mok 497 keys match
ok 498 secrets match
[39m
[33m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-16T07:40:17.131Z - info: Running on ios test: 131. validate generateBeaconStreamAndSecrets

[36m# 131. validate generateBeaconStreamAndSecrets
[39m
[32m# 131. validate generateBeaconStreamAndSecrets
[39m
[33m# 131. validate generateBeaconStreamAndSecrets
[39m
[32mok 507 Streams have same length
[39m
[32mok 508 matching size
[39m
[32mok 509 keys match
[39m
[32mok 510 secrets match
[39m
[32m# teardown
[39m
[36mok 505 Streams have same length
[39m
[36mok 506 matching size
[39m
[36mok 507 keys match
[39m
[36mok 508 secrets match
[39m
[36m# teardown
[39m
[33mok 499 Streams have same length
[39m
[33mok 500 matching size
[39m
[33mok 501 keys match
[39m
[33mok 502 secrets match
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:40:17.173Z - info: Running on ios test: 132. Add two Peers.

[32m# 132. Add two Peers.
[39m
[36m# 132. Add two Peers.
[39m
[33m# 132. Add two Peers.
[39m
[36mok 509 should be equal
[39m
[32mok 511 should be equal
[39m
[36mok 510 should be equal
ok 511 should be equal
[39m
[32mok 512 should be equal
ok 513 should be equal
[39m
[32mok 514 should be equal
[39m
[32mok 515 should be equal
[39m
[32m# teardown
[39m
[36mok 512 should be equal
[39m
[36mok 513 should be equal
[39m
[36m# teardown
[39m
[33mok 503 should be equal
[39m
[33mok 504 should be equal
[39m
[33mok 505 should be equal
[39m
[33mok 506 should be equal
[39m
[33mok 507 should be equal
[39m
[33m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-16T07:40:17.214Z - info: Running on ios test: 133. TCP_NATIVE peer loses DNS

[36m# 133. TCP_NATIVE peer loses DNS
[39m
[32m# 133. TCP_NATIVE peer loses DNS
[39m
[33m# 133. TCP_NATIVE peer loses DNS
[39m
[36mok 514 should be equal
[39m
[36mok 515 should be equal
[39m
[36m# teardown
[39m
[32mok 516 should be equal
[39m
[32mok 517 should be equal
[39m
[32m# teardown
[39m
[33mok 508 should be equal
[39m
[33mok 509 should be equal
[39m
[33m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-16T07:40:17.255Z - info: Running on ios test: 134. Received beacons with no values for us

[36m# 134. Received beacons with no values for us
[39m
[32m# 134. Received beacons with no values for us
[39m
[33m# 134. Received beacons with no values for us
[39m
[36mok 516 entry exists
ok 517 entry is resolved
# teardown
[39m
[32mok 518 entry exists
[39m
[32mok 519 entry is resolved
[39m
[32m# teardown
[39m
[33mok 510 entry exists
[39m
[33mok 511 entry is resolved
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:40:17.331Z - info: Running on ios test: 135. Resolves an action locally

[32m# 135. Resolves an action locally
[39m
[36m# 135. Resolves an action locally
[39m
[33m# 135. Resolves an action locally
[39m
[36mok 518 Host address must match
[39m
[36mok 519 suggestedTCPTimeout must match
ok 520 connectionType must match
ok 521 portNumber must match
[39m
[36m# teardown
[39m
[32mok 520 Host address must match
[39m
[32mok 521 suggestedTCPTimeout must match
ok 522 connectionType must match
[39m
[32mok 523 portNumber must match
[39m
[32m# teardown
[39m
[33mok 512 Host address must match
ok 513 suggestedTCPTimeout must match
[39m
[33mok 514 connectionType must match
ok 515 portNumber must match
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:40:17.391Z - info: Running on ios test: 136. Resolves an action locally using ThaliPeerPoolDefault

[32m# 136. Resolves an action locally using ThaliPeerPoolDefault
[39m
[36m# 136. Resolves an action locally using ThaliPeerPoolDefault
[39m
[33m# 136. Resolves an action locally using ThaliPeerPoolDefault
[39m
[32mok 524 Host address must match
[39m
[32mok 525 suggestedTCPTimeout must match
[39m
[32mok 526 connectionType must match
[39m
[32mok 527 portNumber must match
[39m
[32m# teardown
[39m
[33mok 516 Host address must match
[39m
[33mok 517 suggestedTCPTimeout must match
[39m
[33mok 518 connectionType must match
[39m
[33mok 519 portNumber must match
[39m
[33m# teardown
[39m
[36mok 522 Host address must match
[39m
[36mok 523 suggestedTCPTimeout must match
ok 524 connectionType must match
ok 525 portNumber must match
[39m
[36m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-16T07:40:17.451Z - info: Running on ios test: 137. Action fails because of a bad hostname.

[33m# 137. Action fails because of a bad hostname.
[39m
[32m# 137. Action fails because of a bad hostname.
[39m
[36m# 137. Action fails because of a bad hostname.
[39m
[33mok 520 should be equal
ok 521 should be equal
ok 522 should be equal
# teardown
[39m
[32mok 528 should be equal
ok 529 should be equal
ok 530 should be equal
# teardown
[39m
[36mok 526 should be equal
ok 527 should be equal
[39m
[36mok 528 should be equal
[39m
[36m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:40:22.500Z - info: Running on ios test: 138. hostaddress is removed when the action is running. 

[36m# 138. hostaddress is removed when the action is running. 
[39m
[32m# 138. hostaddress is removed when the action is running. 
[39m
[33m# 138. hostaddress is removed when the action is running. 
[39m
[36mok 529 should be equal
# teardown
[39m
[32mok 531 should be equal
# teardown
[39m
[33mok 523 should be equal
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:40:24.542Z - info: Running on ios test: 139. Client to server request locally

[32m# 139. Client to server request locally
[39m
[36m# 139. Client to server request locally
[39m
[33m# 139. Client to server request locally
[39m
[32mok 532 secrets are equal
ok 533 Public key matches with the server key
ok 534 Host address must match
ok 535 suggestedTCPTimeout must match
ok 536 connectionType must match
ok 537 portNumber must match
# teardown
[39m
[36mok 530 secrets are equal
ok 531 Public key matches with the server key
ok 532 Host address must match
ok 533 suggestedTCPTimeout must match
ok 534 connectionType must match
ok 535 portNumber must match
# teardown
[39m
[33mok 524 secrets are equal
[39m
[33mok 525 Public key matches with the server key
[39m
[33mok 526 Host address must match
ok 527 suggestedTCPTimeout must match
[39m
[33mok 528 connectionType must match
ok 529 portNumber must match
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:40:24.596Z - info: Running on ios test: 140. Test ThaliPskMapCache clean and expiration

[32m# 140. Test ThaliPskMapCache clean and expiration
[39m
[36m# 140. Test ThaliPskMapCache clean and expiration
[39m
[33m# 140. Test ThaliPskMapCache clean and expiration
[39m
[32mok 538 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
[39m
[32mok 539 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
[39m
[36mok 536 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
ok 537 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
[39m
[33mok 530 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
ok 531 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
[39m
[36mok 538 All entries should be expired after 1 second
# teardown
[39m
[32mok 540 All entries should be expired after 1 second
# teardown
[39m
[33mok 532 All entries should be expired after 1 second
# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:40:25.633Z - info: Running on ios test: 141. Test ThaliPskMapCache getSecret and getPublic

[36m# 141. Test ThaliPskMapCache getSecret and getPublic
[39m
[32m# 141. Test ThaliPskMapCache getSecret and getPublic
[39m
[33m# 141. Test ThaliPskMapCache getSecret and getPublic
[39m
[33mok 533 All keys need to be available in the cache
[39m
[32mok 541 All keys need to be available in the cache
[39m
[36mok 539 All keys need to be available in the cache
[39m
[33mok 534 All entries should be expired after 1 second
# teardown
[39m
[32mok 542 All entries should be expired after 1 second
# teardown
[39m
[36mok 540 All entries should be expired after 1 second
# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:40:26.675Z - info: Running on ios test: 142. Test ThaliPskMapCache multiple entries

[36m# 142. Test ThaliPskMapCache multiple entries
[39m
[32m# 142. Test ThaliPskMapCache multiple entries
[39m
[33m# 142. Test ThaliPskMapCache multiple entries
[39m
[32mok 543 Size of the cache should be 2
ok 544 Cache doesn't contain dictionary1
[39m
[36mok 541 Size of the cache should be 2
ok 542 Cache doesn't contain dictionary1
[39m
[33mok 535 Size of the cache should be 2
ok 536 Cache doesn't contain dictionary1
[39m
[32mok 545 Size of the cache should be 1
ok 546 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
[39m
[36mok 543 Size of the cache should be 1
ok 544 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
[39m
[33mok 537 Size of the cache should be 1
ok 538 Cache doesn't contain beaconStreamAndSecretDictionary2
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:40:29.140Z - info: Running on ios test: 143. Start and stop ThaliNotificationServer

[36m# 143. Start and stop ThaliNotificationServer
[39m
[32m# 143. Start and stop ThaliNotificationServer
[39m
[33m# 143. Start and stop ThaliNotificationServer
[39m
[36mok 545 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
ok 546 ThaliMobile.StopAdvertisingAndListeningshould be called once
# teardown
[39m
[32mok 547 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
ok 548 ThaliMobile.StopAdvertisingAndListeningshould be called once
# teardown
[39m
[33mok 539 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
ok 540 ThaliMobile.StopAdvertisingAndListeningshould be called once
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:40:29.186Z - info: Running on ios test: 144. Pass an empty array to ThaliNotificationServer.start

[32m# 144. Pass an empty array to ThaliNotificationServer.start
[39m
[36m# 144. Pass an empty array to ThaliNotificationServer.start
[39m
[33m# 144. Pass an empty array to ThaliNotificationServer.start
[39m
[36mok 547 StartUpdateAdvertisingAndListening should not be called
ok 548 ThaliMobile.StopAdvertisingAndListening should be called once
ok 549 no error
ok 550 should be 204
# teardown
[39m
[32mok 549 StartUpdateAdvertisingAndListening should not be called
ok 550 ThaliMobile.StopAdvertisingAndListening should be called once
ok 551 no error
ok 552 should be 204
# teardown
[39m
[33mok 541 StartUpdateAdvertisingAndListening should not be called
[39m
[33mok 542 ThaliMobile.StopAdvertisingAndListening should be called once
[39m
[33mok 543 no error
ok 544 should be 204
[39m
[33m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-16T07:40:29.231Z - info: Running on ios test: 145. Pass a string to ThaliNotificationServer.start

[36m# 145. Pass a string to ThaliNotificationServer.start
[39m
[32m# 145. Pass a string to ThaliNotificationServer.start
[39m
[33m# 145. Pass a string to ThaliNotificationServer.start
[39m
[32mok 553 StartUpdateAdvertisingAndListening should not be called
# teardown
[39m
[36mok 551 StartUpdateAdvertisingAndListening should not be called
# teardown
[39m
[33mok 545 StartUpdateAdvertisingAndListening should not be called
# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:40:29.262Z - info: Running on ios test: 146. Pass an empty parameter to ThaliNotificationServer.start

[33m# 146. Pass an empty parameter to ThaliNotificationServer.start
[39m
[32m# 146. Pass an empty parameter to ThaliNotificationServer.start
[39m
[36m# 146. Pass an empty parameter to ThaliNotificationServer.start
[39m
[33mok 546 StartUpdateAdvertisingAndListening should not be called
# teardown
[39m
[32mok 554 StartUpdateAdvertisingAndListening should not be called
# teardown
[39m
[36mok 552 StartUpdateAdvertisingAndListening should not be called
[39m
[36m# teardown
[39m
[33m# setup
[39m
[32m# setup
[39m
[36m# setup
[39m
2016-08-16T07:40:29.295Z - info: Running on ios test: 147. Make an HTTP request to /NotificationBeacons

[36m# 147. Make an HTTP request to /NotificationBeacons
[39m
[33m# 147. Make an HTTP request to /NotificationBeacons
[39m
[32m# 147. Make an HTTP request to /NotificationBeacons
[39m
[36mok 553 no error
ok 554 should be 200
ok 555 should be equal
ok 556 should be equal
[39m
[33mok 547 no error
ok 548 should be 200
ok 549 should be equal
ok 550 should be equal
[39m
[33mok 551 (unnamed assert)
[39m
[33mok 552 no error
ok 553 should be 204
[39m
[33m# teardown
[39m
[36mok 557 (unnamed assert)
[39m
[32mok 555 no error
ok 556 should be 200
ok 557 should be equal
ok 558 should be equal
[39m
[32mok 559 (unnamed assert)
[39m
[32mok 560 no error
ok 561 should be 204
[39m
[32m# teardown
[39m
[36mok 558 no error
[39m
[36mok 559 should be 204
[39m
[36m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-16T07:40:29.360Z - info: Running on ios test: 148. Make an HTTP request to /NotificationBeacons (no keys)

[32m# 148. Make an HTTP request to /NotificationBeacons (no keys)
[39m
[33m# 148. Make an HTTP request to /NotificationBeacons (no keys)
[39m
[36m# 148. Make an HTTP request to /NotificationBeacons (no keys)
[39m
[32mok 562 error should be null
[39m
[32mok 563 should be 204
[39m
[32m# teardown
[39m
[33mok 554 error should be null
ok 555 should be 204
[39m
[33m# teardown
[39m
[36mok 560 error should be null
[39m
[36mok 561 should be 204
[39m
[36m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-16T07:40:29.398Z - info: Running on ios test: 149. Make an HTTP request to /NotificationBeaconsbefore calling start

[32m# 149. Make an HTTP request to /NotificationBeaconsbefore calling start
[39m
[33m# 149. Make an HTTP request to /NotificationBeaconsbefore calling start
[39m
[36m# 149. Make an HTTP request to /NotificationBeaconsbefore calling start
[39m
[33mok 556 should be 404
[39m
[32mok 564 should be 404
[39m
[33m# teardown
[39m
[32m# teardown
[39m
[36mok 562 should be 404
[39m
[36m# teardown
[39m
[33m# setup
[39m
[32m# setup
[39m
[36m# setup
[39m
2016-08-16T07:40:29.442Z - info: Running on ios test: 150. #testThaliPeerAction - test getters

[33m# 150. #testThaliPeerAction - test getters
[39m
[32m# 150. #testThaliPeerAction - test getters
[39m
[36m# 150. #testThaliPeerAction - test getters
[39m
[32mok 565 getPeerIdentifier
[39m
[33mok 557 getPeerIdentifier
[39m
[32mok 566 getConnectionType
ok 567 getActionType
ok 568 getActionState
ok 569 getPskIdentity
[39m
[33mok 558 getConnectionType
[39m
[32mok 570 getPskKey
[39m
[32m# teardown
[39m
[33mok 559 getActionType
[39m
[33mok 560 getActionState
ok 561 getPskIdentity
[39m
[33mok 562 getPskKey
[39m
[33m# teardown
[39m
[36mok 563 getPeerIdentifier
[39m
[36mok 564 getConnectionType
ok 565 getActionType
[39m
[36mok 566 getActionState
ok 567 getPskIdentity
[39m
[36mok 568 getPskKey
[39m
[36m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-16T07:40:29.469Z - info: Running on ios test: 151. #testThaliPeerAction - start and kill

[33m# 151. #testThaliPeerAction - start and kill
[39m
[32m# 151. #testThaliPeerAction - start and kill
[39m
[36m# 151. #testThaliPeerAction - start and kill
[39m
[33mok 563 initial state
[39m
[33mok 564 after start
[39m
[33mok 565 after kill
[39m
[33m# teardown
[39m
[32mok 571 initial state
[39m
[32mok 572 after start
[39m
[36mok 569 initial state
[39m
[32mok 573 after kill
[39m
[32m# teardown
[39m
[36mok 570 after start
[39m
[36mok 571 after kill
[39m
[36m# teardown
[39m
[33m# setup
[39m
[32m# setup
[39m
[36m# setup
[39m
2016-08-16T07:40:29.496Z - info: Running on ios test: 152. #testThaliPeerAction - double start

[33m# 152. #testThaliPeerAction - double start
[39m
[32m# 152. #testThaliPeerAction - double start
[39m
[36m# 152. #testThaliPeerAction - double start
[39m
[33mok 566 should be equal
[39m
[32mok 574 should be equal
[39m
[33m# teardown
[39m
[32m# teardown
[39m
[36mok 572 should be equal
[39m
[36m# teardown
[39m
[33m# setup
[39m
[32m# setup
[39m
[36m# setup
[39m
2016-08-16T07:40:29.520Z - info: Running on ios test: 153. #testThaliPeerAction - start after kill

[33m# 153. #testThaliPeerAction - start after kill
[39m
[36m# 153. #testThaliPeerAction - start after kill
[39m
[32m# 153. #testThaliPeerAction - start after kill
[39m
[32mok 575 clean kill
ok 576 should be equal
# teardown
[39m
[36mok 573 clean kill
ok 574 should be equal
# teardown
[39m
[33mok 567 clean kill
ok 568 should be equal
[39m
[33m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-16T07:40:29.543Z - info: Running on ios test: 154. #testThaliPeerAction - make sure ids are unique

[33m# 154. #testThaliPeerAction - make sure ids are unique
[39m
[32m# 154. #testThaliPeerAction - make sure ids are unique
[39m
[36m# 154. #testThaliPeerAction - make sure ids are unique
[39m
[33mok 569 should not be equal
# teardown
[39m
[36mok 575 should not be equal
[39m
[36m# teardown
[39m
[32mok 577 should not be equal
[39m
[32m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-16T07:40:29.567Z - info: Running on ios test: 155. Test PeerConnectionInformation basics

[32m# 155. Test PeerConnectionInformation basics
[39m
[33m# 155. Test PeerConnectionInformation basics
[39m
[36m# 155. Test PeerConnectionInformation basics
[39m
[33mok 570 connection type works
ok 571 getHostAddress works
ok 572 getPortNumber works
ok 573 getSuggestedTCPTimeout works
# teardown
[39m
[32mok 578 connection type works
ok 579 getHostAddress works
ok 580 getPortNumber works
ok 581 getSuggestedTCPTimeout works
# teardown
[39m
[36mok 576 connection type works
[39m
[36mok 577 getHostAddress works
ok 578 getPortNumber works
ok 579 getSuggestedTCPTimeout works
[39m
[36m# teardown
[39m
[33m# setup
[39m
[32m# setup
[39m
[36m# setup
[39m
2016-08-16T07:40:29.593Z - info: Running on ios test: 156. Test PeerDictionary basic functionality

[33m# 156. Test PeerDictionary basic functionality
[39m
[36m# 156. Test PeerDictionary basic functionality
[39m
[32m# 156. Test PeerDictionary basic functionality
[39m
[33mok 574 Entry counter must be 1
ok 575 Size must be 1
ok 576 Entry counter must be 2
ok 577 Size must be 2
ok 578 Entry2 should not be found
ok 579 Size must be 1
ok 580 Size must be 0
# teardown
[39m
[32mok 582 Entry counter must be 1
ok 583 Size must be 1
ok 584 Entry counter must be 2
ok 585 Size must be 2
ok 586 Entry2 should not be found
ok 587 Size must be 1
ok 588 Size must be 0
# teardown
[39m
[36mok 580 Entry counter must be 1
[39m
[36mok 581 Size must be 1
ok 582 Entry counter must be 2
ok 583 Size must be 2
[39m
[36mok 584 Entry2 should not be found
[39m
[36mok 585 Size must be 1
[39m
[36mok 586 Size must be 0
[39m
[36m# teardown
[39m
[33m# setup
[39m
[32m# setup
[39m
[36m# setup
[39m
2016-08-16T07:40:29.622Z - info: Running on ios test: 157. Test PeerDictionary with multiple entries.

[33m# 157. Test PeerDictionary with multiple entries.
[39m
[32m# 157. Test PeerDictionary with multiple entries.
[39m
[36m# 157. Test PeerDictionary with multiple entries.
[39m
[36mok 587 Size must be100
[39m
[36mok 588 Entries between 20 and MAXSIZE + 20 should exist
[39m
[32mok 589 Size must be100
[39m
[32mok 590 Entries between 20 and MAXSIZE + 20 should exist
[39m
[33mok 581 Size must be100
ok 582 Entries between 20 and MAXSIZE + 20 should exist
[39m
[36mok 589 WAITING state entry should not be removed
# teardown
[39m
[32mok 591 WAITING state entry should not be removed
# teardown
[39m
[33mok 583 WAITING state entry should not be removed
[39m
[33m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-16T07:40:29.857Z - info: Running on ios test: 158. RESOLVED entries are removed before WAITING state entry.

[36m# 158. RESOLVED entries are removed before WAITING state entry.
[39m
[32m# 158. RESOLVED entries are removed before WAITING state entry.
[39m
[33m# 158. RESOLVED entries are removed before WAITING state entry.
[39m
[36mok 590 Entries between 6 and MAXSIZE + 4 should exist
ok 591 Size should be MAXSIZE
ok 592 Size should be MAXSIZE+6
# teardown
[39m
[32mok 592 Entries between 6 and MAXSIZE + 4 should exist
ok 593 Size should be MAXSIZE
ok 594 Size should be MAXSIZE+6
# teardown
[39m
[33mok 584 Entries between 6 and MAXSIZE + 4 should exist
[39m
[33mok 585 Size should be MAXSIZE
ok 586 Size should be MAXSIZE+6
[39m
[33m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-16T07:40:29.974Z - info: Running on ios test: 159. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

[36m# 159. WAITING entries are removed before CONTROLLED_BY_POOL state entry.
[39m
[33m# 159. WAITING entries are removed before CONTROLLED_BY_POOL state entry.
[39m
[32m# 159. WAITING entries are removed before CONTROLLED_BY_POOL state entry.
[39m
[32mok 595 WAITING state entry should not be removed
ok 596 Waiting entries between 6 and MAXSIZE + 4 should exist
ok 597 Size should be MAXSIZE
ok 598 entryCounter should be MAXSIZE+6
# teardown
[39m
[36mok 593 WAITING state entry should not be removed
ok 594 Waiting entries between 6 and MAXSIZE + 4 should exist
ok 595 Size should be MAXSIZE
ok 596 entryCounter should be MAXSIZE+6
# teardown
[39m
[33mok 587 WAITING state entry should not be removed
[39m
[33mok 588 Waiting entries between 6 and MAXSIZE + 4 should exist
[39m
[33mok 589 Size should be MAXSIZE
ok 590 entryCounter should be MAXSIZE+6
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:40:30.095Z - info: Running on ios test: 160. When CONTROLLED_BY_POOL entry is removed and kill is called.

[32m# 160. When CONTROLLED_BY_POOL entry is removed and kill is called.
[39m
[33m# 160. When CONTROLLED_BY_POOL entry is removed and kill is called.
[39m
[36m# 160. When CONTROLLED_BY_POOL entry is removed and kill is called.
[39m
[32mok 599 Kill should be called once
ok 600 Size should be 100
[39m
[33mok 591 Kill should be called once
ok 592 Size should be 100
# teardown
[39m
[32m# teardown
[39m
[36mok 597 Kill should be called once
[39m
[36mok 598 Size should be 100
[39m
[36m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-16T07:40:30.210Z - info: Running on ios test: 161. #ThaliPeerPoolInterface - bad enqueues

[36m# 161. #ThaliPeerPoolInterface - bad enqueues
[39m
[32m# 161. #ThaliPeerPoolInterface - bad enqueues
[39m
[33m# 161. #ThaliPeerPoolInterface - bad enqueues
[39m
[33mok 593 null arg
[39m
[33mok 594 wrong arg type
[39m
[33mok 595 wrong state
[39m
[33m# teardown
[39m
[36mok 599 null arg
[39m
[36mok 600 wrong arg type
[39m
[36mok 601 wrong state
[39m
[36m# teardown
[39m
[32mok 601 null arg
[39m
[32mok 602 wrong arg type
[39m
[32mok 603 wrong state
[39m
[32m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-16T07:40:30.239Z - info: Running on ios test: 162. #ThaliPeerPoolInterface - do not allow same object type

[33m# 162. #ThaliPeerPoolInterface - do not allow same object type
[39m
[36m# 162. #ThaliPeerPoolInterface - do not allow same object type
[39m
[32m# 162. #ThaliPeerPoolInterface - do not allow same object type
[39m
[36mok 602 good enqueue
[39m
[32mok 604 good enqueue
[39m
[36mok 603 should be equal
[39m
[36m# teardown
[39m
[33mok 596 good enqueue
[39m
[33mok 597 should be equal
[39m
[33m# teardown
[39m
[32mok 605 should be equal
[39m
[32m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-16T07:40:30.265Z - info: Running on ios test: 163. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

[32m# 163. #ThaliPeerPoolInterface - make sure we catch kill and dequeue
[39m
[36m# 163. #ThaliPeerPoolInterface - make sure we catch kill and dequeue
[39m
[33m# 163. #ThaliPeerPoolInterface - make sure we catch kill and dequeue
[39m
[32mok 606 good enqueue
ok 607 2nd good enqueue
ok 608 we are in the pool
ok 609 We are out of the pool
ok 610 Action was killed
ok 611 The original kill was called too
ok 612 second item is still in queue
[39m
[36mok 604 good enqueue
ok 605 2nd good enqueue
ok 606 we are in the pool
[39m
[32m# teardown
[39m
[36mok 607 We are out of the pool
[39m
[36mok 608 Action was killed
[39m
[36mok 609 The original kill was called too
ok 610 second item is still in queue
[39m
[36m# teardown
[39m
[33mok 598 good enqueue
[39m
[33mok 599 2nd good enqueue
ok 600 we are in the pool
[39m
[33mok 601 We are out of the pool
[39m
[33mok 602 Action was killed
ok 603 The original kill was called too
[39m
[33mok 604 second item is still in queue
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:40:30.295Z - info: Running on ios test: 164. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent

[32m# 164. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
[39m
[36m# 164. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
[39m
[33m# 164. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
[39m
[32mok 613 good enqueue
[39m
[32mok 614 first kill
[39m
[32mok 615 second NOOP kill
[39m
[32m# teardown
[39m
[36mok 611 good enqueue
[39m
[36mok 612 first kill
[39m
[36mok 613 second NOOP kill
[39m
[36m# teardown
[39m
[33mok 605 good enqueue
[39m
[33mok 606 first kill
[39m
[33mok 607 second NOOP kill
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:40:30.321Z - info: Running on ios test: 165. Make sure peerDictionaryKey is reasonable

[32m# 165. Make sure peerDictionaryKey is reasonable
[39m
[36m# 165. Make sure peerDictionaryKey is reasonable
[39m
[33m# 165. Make sure peerDictionaryKey is reasonable
[39m
[32mok 616 equal keys
[39m
[32mok 617 not equal connection type
ok 618 same connection type, different buffer
[39m
[32m# teardown
[39m
[36mok 614 equal keys
[39m
[36mok 615 not equal connection type
[39m
[36mok 616 same connection type, different buffer
[39m
[36m# teardown
[39m
[33mok 608 equal keys
[39m
[33mok 609 not equal connection type
[39m
[33mok 610 same connection type, different buffer
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:40:30.349Z - info: Running on ios test: 166. Make sure start works

[32m# 166. Make sure start works
[39m
[36m# 166. Make sure start works
[39m
[33m# 166. Make sure start works
[39m
[32mok 619 First start and on called correctly
[39m
[32m# teardown
[39m
[33mok 611 First start and on called correctly
[39m
[33m# teardown
[39m
[36mok 617 First start and on called correctly
[39m
[36m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-16T07:40:30.384Z - info: Running on ios test: 167. Make sure stop works

[32m# 167. Make sure stop works
[39m
[36m# 167. Make sure stop works
[39m
[33m# 167. Make sure stop works
[39m
[32mok 620 second cleared dictionary
ok 621 First start and on called correctly
ok 622 First stop and removeListener called correctly
ok 623 first action kill called
ok 624 second action kill called
ok 625 first cleared dictionary
ok 626 second cleared dictionary
# teardown
[39m
[36mok 618 second cleared dictionary
ok 619 First start and on called correctly
[39m
[33mok 612 second cleared dictionary
ok 613 First start and on called correctly
[39m
[36mok 620 First stop and removeListener called correctly
ok 621 first action kill called
ok 622 second action kill called
ok 623 first cleared dictionary
ok 624 second cleared dictionary
# teardown
[39m
[33mok 614 First stop and removeListener called correctly
[39m
[33mok 615 first action kill called
ok 616 second action kill called
[39m
[33mok 617 first cleared dictionary
ok 618 second cleared dictionary
[39m
[33m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-16T07:40:30.422Z - info: Running on ios test: 168. Simple peer event

[32m# 168. Simple peer event
[39m
[36m# 168. Simple peer event
[39m
[33m# 168. Simple peer event
[39m
[32mok 627 listener has been set
ok 628 peer dictionary has expected number of entries
ok 629 Dictionary and pool have same action
ok 630 ads match
ok 631 PouchDB matches
ok 632 DB Names match
ok 633 public keys match
ok 634 peer dictionary has expected number of entries
ok 635 Dictionary and pool have same action
ok 636 ads match
ok 637 PouchDB matches
ok 638 DB Names match
ok 639 public keys match
ok 640 start called once
ok 641 kill never called
ok 642 One entry left
ok 643 Dictionary and pool have same action
ok 644 Start never called
ok 645 Kill called once
ok 646 no entries left
[39m
[36mok 625 listener has been set
ok 626 peer dictionary has expected number of entries
ok 627 Dictionary and pool have same action
ok 628 ads match
ok 629 PouchDB matches
ok 630 DB Names match
ok 631 public keys match
ok 632 peer dictionary has expected number of entries
ok 633 Dictionary and pool have same action
ok 634 ads match
ok 635 PouchDB matches
ok 636 DB Names match
ok 637 public keys match
ok 638 start called once
ok 639 kill never called
ok 640 One entry left
ok 641 Dictionary and pool have same action
ok 642 Start never called
ok 643 Kill called once
ok 644 no entries left
[39m
[36mok 645 Third action is dead
ok 646 peer dictionary has expected number of entries
[39m
[36mok 647 Dictionary and pool have same action
[39m
[36mok 648 ads match
ok 649 PouchDB matches
ok 650 DB Names match
[39m
[36mok 651 public keys match
[39m
[36m# teardown
[39m
[32mok 647 Third action is dead
ok 648 peer dictionary has expected number of entries
ok 649 Dictionary and pool have same action
ok 650 ads match
[39m
[32mok 651 PouchDB matches
ok 652 DB Names match
[39m
[32mok 653 public keys match
[39m
[32m# teardown
[39m
[33mok 619 listener has been set
[39m
[33mok 620 peer dictionary has expected number of entries
[39m
[33mok 621 Dictionary and pool have same action
ok 622 ads match
ok 623 PouchDB matches
[39m
[33mok 624 DB Names match
[39m
[33mok 625 public keys match
[39m
[33mok 626 peer dictionary has expected number of entries
[39m
[33mok 627 Dictionary and pool have same action
ok 628 ads match
ok 629 PouchDB matches
[39m
[33mok 630 DB Names match
[39m
[33mok 631 public keys match
[39m
[33mok 632 start called once
ok 633 kill never called
[39m
[33mok 634 One entry left
[39m
[33mok 635 Dictionary and pool have same action
[39m
[33mok 636 Start never called
[39m
[33mok 637 Kill called once
[39m
[33mok 638 no entries left
[39m
[33mok 639 Third action is dead
[39m
[33mok 640 peer dictionary has expected number of entries
[39m
[33mok 641 Dictionary and pool have same action
ok 642 ads match
[39m
[33mok 643 PouchDB matches
ok 644 DB Names match
[39m
[33mok 645 public keys match
[39m
[33m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-16T07:40:30.472Z - info: Running on ios test: 169. Coordinated pull replication from notification test

[36m# 169. Coordinated pull replication from notification test
[39m
[32m# 169. Coordinated pull replication from notification test
[39m
[33m# 169. Coordinated pull replication from notification test
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52071
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52076
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52080
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createPeerListener: first connection
[39m
[33mDEBUG createNativeListener: new incoming socket
[39m
[33mDEBUG createNativeListener: creating incoming mux
[39m
[33mDEBUG createNativeListener: new mux
[39m
[33mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG createPeerListener: first connection
[39m
[33mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[33mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG thaliReplicationPeerAction: Replication resumed
[39m
[36mDEBUG thaliReplicationPeerAction: Replication resumed
[39m
[33mDEBUG thaliReplicationPeerAction: Replication resumed
[39m
[36mok 652 all tests passed
[39m
[36m# teardown
DEBUG createPeerListener: forward connection
DEBUG createPeerListener: forward connection
[39m
[33mDEBUG createPeerListener: forward connection
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: 
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG localSeqManager: Got an error trying to update seq {"onPut":true}
DEBUG thaliReplicationPeerAction: Got error in update, waiting for main loop to detect and handle - Error: Stop Called
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: 
DEBUG createNativeListener: stream close:
[39m
[32mDEBUG thaliReplicationPeerAction: Replication resumed
[39m
[33mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG localSeqManager: Got an error trying to update seq {"onPut":true}
DEBUG thaliReplicationPeerAction: Got error in update, waiting for main loop to detect and handle - Error: Stop Called
[39m
[33mDEBUG createNativeListener: 
DEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: 
DEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: 
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: 
DEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: 
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: 
[39m
[32mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[36mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[36mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[33mDEBUG thaliReplicationPeerAction: Replication resumed
[39m
[33mundefined[39m
2016-08-16T07:40:30.861Z - info: Socket to device 7908f98f-c49a-41d6-ae68-11527ecf517c disconnected: transport close

[36mDEBUG createPeerListener: Recreating listener
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[36mDEBUG createPeerListener: first connection
[39m
[36mDEBUG wifiBasedNativeMock: error on peerConnections socket for urn:uuid:9c1dedf5-6d6e-438f-9342-251e5a408a62, err - Error: connect ECONNREFUSED
[39m
[32mDEBUG thaliReplicationPeerAction: Got error on replication - Error: socket hang up -1
[39m
[32mDEBUG thaliPeerPoolDefault: Got err Error: socket hang up -1
[39m
[32mDEBUG createPeerListener: Recreating listener
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG thaliReplicationPeerAction: Got error on replication - Error: connect ECONNREFUSED
DEBUG thaliPeerPoolDefault: Got err Error: Could not establish TCP connection
[39m
[32mDEBUG wifiBasedNativeMock: error on peerConnections socket for urn:uuid:9c1dedf5-6d6e-438f-9342-251e5a408a62, err - Error: connect ECONNREFUSED
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG thaliReplicationPeerAction: Replication resumed
[39m
[32mok 654 all tests passed
[39m
[32mDEBUG localSeqManager: Got an error trying to update seq {"onPut":true}
[39m
[32mDEBUG thaliReplicationPeerAction: Got error in update, waiting for main loop to detect and handle - Error: Stop Called
[39m
[32m# teardown
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createPeerListener: error on incoming stream - Error: Channel destroyed
[39m
[36mDEBUG createNativeListener: 
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[32mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[32mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[32mDEBUG createNativeListener: incoming socket timeout
[39m
[32mDEBUG createNativeListener: mux close
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createPeerListener: Recreating listener
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[36mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: 
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: incoming socket timeout
[39m
[36mDEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createPeerListener: Recreating listener
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[32mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: 
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: incoming socket timeout
DEBUG createNativeListener: mux close
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createPeerListener: Recreating listener
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[36mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: 
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: incoming socket timeout
DEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createPeerListener: Recreating listener
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[32mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: 
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: incoming socket timeout
DEBUG createNativeListener: mux close
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createPeerListener: Recreating listener
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[36mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: 
DEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: incoming socket timeout
[39m
[36mDEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createPeerListener: Recreating listener
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[32mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: 
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: incoming socket timeout
DEBUG createNativeListener: mux close
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createPeerListener: Recreating listener
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[36mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: 
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: incoming socket timeout
[39m
[36mDEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createPeerListener: Recreating listener
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[32mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: 
DEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: incoming socket timeout
[39m
[32mDEBUG createNativeListener: mux close
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createPeerListener: Recreating listener
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[36mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: 
DEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: incoming socket timeout
[39m
[36mDEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createPeerListener: Recreating listener
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[32mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: incoming socket timeout
DEBUG createNativeListener: mux close
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createPeerListener: Recreating listener
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[36mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[36mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: 
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: incoming socket timeout
DEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createPeerListener: Recreating listener
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[32mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: 
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: incoming socket timeout
[39m
[32mDEBUG createNativeListener: mux close
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createPeerListener: Recreating listener
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[36mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: 
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: incoming socket timeout
[39m
[36mDEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createPeerListener: Recreating listener
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[32mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: 
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: incoming socket timeout
[39m
[32mDEBUG createNativeListener: mux close
DEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createPeerListener: Recreating listener
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[36mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: 
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: incoming socket timeout
[39m
[36mDEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createPeerListener: Recreating listener
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[32mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: 
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: incoming socket timeout
[39m
[32mDEBUG createNativeListener: mux close
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createPeerListener: Recreating listener
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
WARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[36mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[32mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: 
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: incoming socket timeout
DEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createPeerListener: Recreating listener
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[32mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: 
DEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: incoming socket timeout
[39m
[32mDEBUG createNativeListener: mux close
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createPeerListener: Recreating listener
DEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[36mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: incoming socket timeout
[39m
[36mDEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createPeerListener: Recreating listener
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[32mDEBUG createPeerListener: first connection
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: 
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: incoming socket timeout
[39m
[32mDEBUG createNativeListener: mux close
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createPeerListener: Recreating listener
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[36mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[36mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: incoming socket timeout
DEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createPeerListener: Recreating listener
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[32mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: incoming socket timeout
[39m
[32mDEBUG createNativeListener: mux close
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createPeerListener: Recreating listener
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[36mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: incoming socket timeout
DEBUG createNativeListener: mux close
DEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createPeerListener: Recreating listener
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
WARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
DEBUG createPeerListener: first connection
[39m
[36mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: incoming socket timeout
[39m
[32mDEBUG createNativeListener: mux close
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createPeerListener: Recreating listener
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[36mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: 
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: incoming socket timeout
[39m
[36mDEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createPeerListener: Recreating listener
DEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[32mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: 
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: incoming socket timeout
[39m
[32mDEBUG createNativeListener: mux close
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createPeerListener: Recreating listener
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[36mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: incoming socket timeout
[39m
[36mDEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createPeerListener: Recreating listener
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[32mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: 
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: incoming socket timeout
[39m
[32mDEBUG createNativeListener: mux close
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createPeerListener: Recreating listener
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[36mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: 
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: incoming socket timeout
DEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createPeerListener: Recreating listener
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[32mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: incoming socket timeout
[39m
[32mDEBUG createNativeListener: mux close
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createPeerListener: Recreating listener
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[36mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: 
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: incoming socket timeout
[39m
[36mDEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createPeerListener: Recreating listener
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[32mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: 
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: incoming socket timeout
[39m
[32mDEBUG createNativeListener: mux close
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createPeerListener: Recreating listener
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[36mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: 
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: incoming socket timeout
[39m
[36mDEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createPeerListener: Recreating listener
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[32mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: 
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: incoming socket timeout
[39m
[32mDEBUG createNativeListener: mux close
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createPeerListener: Recreating listener
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[36mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: 
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: incoming socket timeout
[39m
[36mDEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createPeerListener: Recreating listener
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[32mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: 
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: incoming socket timeout
[39m
[32mDEBUG createNativeListener: mux close
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createPeerListener: Recreating listener
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[36mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: 
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: incoming socket timeout
[39m
[36mDEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createPeerListener: Recreating listener
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[32mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: 
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: incoming socket timeout
[39m
[32mDEBUG createNativeListener: mux close
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createPeerListener: Recreating listener
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[36mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[32mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: 
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: incoming socket timeout
[39m
[36mDEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createPeerListener: Recreating listener
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[32mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: incoming socket timeout
[39m
[32mDEBUG createNativeListener: mux close
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createPeerListener: Recreating listener
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[36mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: 
DEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: incoming socket timeout
[39m
[36mDEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createPeerListener: Recreating listener
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
WARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[32mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: 
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: incoming socket timeout
DEBUG createNativeListener: mux close
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createPeerListener: Recreating listener
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[36mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: incoming socket timeout
[39m
[36mDEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createPeerListener: Recreating listener
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[32mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: 
[39m
[36mDEBUG createNativeListener: stream close:
[39m

npm http request GET http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/socket.io
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/fs-extra-promise
npm http request GET http://192.168.1.100:4873/express
npm http 200 http://192.168.1.100:4873/socket.io
npm http 200 http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/lie
npm http 200 http://192.168.1.100:4873/fs-extra-promise
npm http 200 http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/cookie-signature
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/accepts
npm http request GET http://192.168.1.100:4873/cookie
npm http request GET http://192.168.1.100:4873/escape-html
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/content-disposition
npm http request GET http://192.168.1.100:4873/array-flatten
npm http request GET http://192.168.1.100:4873/parseurl
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/range-parser
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/path-to-regexp
npm http request GET http://192.168.1.100:4873/proxy-addr
npm http request GET http://192.168.1.100:4873/merge-descriptors
npm http request GET http://192.168.1.100:4873/finalhandler
npm http request GET http://192.168.1.100:4873/fresh
npm http request GET http://192.168.1.100:4873/etag
npm http request GET http://192.168.1.100:4873/utils-merge
npm http request GET http://192.168.1.100:4873/send
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/vary
npm http request GET http://192.168.1.100:4873/serve-static
npm http 200 http://192.168.1.100:4873/cookie-signature
npm http 200 http://192.168.1.100:4873/depd
npm http 200 http://192.168.1.100:4873/debug
npm http 200 http://192.168.1.100:4873/cookie
npm http 200 http://192.168.1.100:4873/accepts
npm http 200 http://192.168.1.100:4873/escape-html
npm http 200 http://192.168.1.100:4873/content-type
npm http 200 http://192.168.1.100:4873/array-flatten
npm http 200 http://192.168.1.100:4873/content-disposition
npm http 200 http://192.168.1.100:4873/parseurl
npm http 200 http://192.168.1.100:4873/on-finished
npm http 200 http://192.168.1.100:4873/range-parser
npm http 200 http://192.168.1.100:4873/methods
npm http 200 http://192.168.1.100:4873/qs
npm http 200 http://192.168.1.100:4873/path-to-regexp
npm http 200 http://192.168.1.100:4873/proxy-addr
npm http 200 http://192.168.1.100:4873/merge-descriptors
npm http 200 http://192.168.1.100:4873/fresh
npm http 200 http://192.168.1.100:4873/finalhandler
npm http 200 http://192.168.1.100:4873/etag
npm http 200 http://192.168.1.100:4873/utils-merge
npm http 200 http://192.168.1.100:4873/send
npm http 200 http://192.168.1.100:4873/type-is
npm http 200 http://192.168.1.100:4873/vary
npm http 200 http://192.168.1.100:4873/serve-static
npm http request GET http://192.168.1.100:4873/negotiator
npm http request GET http://192.168.1.100:4873/mime-types
npm http 200 http://192.168.1.100:4873/negotiator
npm http 200 http://192.168.1.100:4873/mime-types
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
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/mime
npm http request GET http://192.168.1.100:4873/statuses
npm http 200 http://192.168.1.100:4873/destroy
npm http 200 http://192.168.1.100:4873/http-errors
npm http 200 http://192.168.1.100:4873/statuses
npm http 200 http://192.168.1.100:4873/mime
npm http request GET http://192.168.1.100:4873/inherits
npm http 200 http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/media-typer
npm http 200 http://192.168.1.100:4873/media-typer
npm http request GET http://192.168.1.100:4873/fs-extra
npm http request GET http://192.168.1.100:4873/bluebird
npm http 200 http://192.168.1.100:4873/fs-extra
npm http 200 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/jsonfile
npm http request GET http://192.168.1.100:4873/rimraf
npm http 200 http://192.168.1.100:4873/jsonfile
npm http 200 http://192.168.1.100:4873/graceful-fs
npm http 200 http://192.168.1.100:4873/rimraf
npm http request GET http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/fs.realpath
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/minimatch
npm http 200 http://192.168.1.100:4873/inflight
npm http 200 http://192.168.1.100:4873/once
npm http 200 http://192.168.1.100:4873/fs.realpath
npm http 200 http://192.168.1.100:4873/path-is-absolute
npm http 200 http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/wrappy
npm http 200 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 200 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/concat-map
npm http 200 http://192.168.1.100:4873/concat-map
npm http 200 http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/immediate
npm http 200 http://192.168.1.100:4873/inline-process-browser
npm http 200 http://192.168.1.100:4873/es3ify
npm http 200 http://192.168.1.100:4873/unreachable-branch-transform
npm http 200 http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/through
npm http request GET http://192.168.1.100:4873/jstransform
npm http 200 http://192.168.1.100:4873/jstransform
npm http 200 http://192.168.1.100:4873/esprima
npm http 200 http://192.168.1.100:4873/through
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/source-map
npm http 200 http://192.168.1.100:4873/base62
npm http 200 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/esprima-fb
npm http 200 http://192.168.1.100:4873/commoner
npm http 200 http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/recast
npm http 200 http://192.168.1.100:4873/private
npm http 200 http://192.168.1.100:4873/mkdirp
npm http 200 http://192.168.1.100:4873/commander
npm http 200 http://192.168.1.100:4873/iconv-lite
npm http 200 http://192.168.1.100:4873/detective
npm http 200 http://192.168.1.100:4873/q
npm http 200 http://192.168.1.100:4873/recast
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
npm http 200 http://192.168.1.100:4873/amdefine
npm http request GET http://192.168.1.100:4873/falafel
npm http request GET http://192.168.1.100:4873/through2
npm http 200 http://192.168.1.100:4873/falafel
npm http 200 http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/object-keys
npm http 200 http://192.168.1.100:4873/foreach
npm http 200 http://192.168.1.100:4873/isarray
npm http 200 http://192.168.1.100:4873/object-keys
npm http request GET http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 200 http://192.168.1.100:4873/xtend
npm http 200 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/core-util-is
npm http request GET http://192.168.1.100:4873/string_decoder
npm http 200 http://192.168.1.100:4873/string_decoder
npm http 200 http://192.168.1.100:4873/core-util-is
npm http request GET http://192.168.1.100:4873/esmangle-evaluator
npm http 200 http://192.168.1.100:4873/esmangle-evaluator
npm http request GET http://192.168.1.100:4873/socket.io-parser
npm http request GET http://192.168.1.100:4873/has-binary-data
npm http request GET http://192.168.1.100:4873/socket.io-adapter
npm http request GET http://192.168.1.100:4873/engine.io
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http 200 http://192.168.1.100:4873/socket.io-parser
npm http 200 http://192.168.1.100:4873/socket.io-adapter
npm http 200 http://192.168.1.100:4873/engine.io
npm http 200 http://192.168.1.100:4873/socket.io-client
npm http 200 http://192.168.1.100:4873/has-binary-data
npm http request GET http://192.168.1.100:4873/base64id
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/ws
npm http 200 http://192.168.1.100:4873/base64id
npm http 200 http://192.168.1.100:4873/engine.io-parser
npm http 200 http://192.168.1.100:4873/ws
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/has-binary
npm http request GET http://192.168.1.100:4873/utf8
npm http 200 http://192.168.1.100:4873/arraybuffer.slice
npm http 200 http://192.168.1.100:4873/after
npm http 200 http://192.168.1.100:4873/blob
npm http 200 http://192.168.1.100:4873/has-binary
npm http 200 http://192.168.1.100:4873/base64-arraybuffer
npm http 200 http://192.168.1.100:4873/utf8
npm http request GET http://192.168.1.100:4873/options
npm http request GET http://192.168.1.100:4873/ultron
npm http request GET http://192.168.1.100:4873/bufferutil
npm http request GET http://192.168.1.100:4873/utf-8-validate
npm http 200 http://192.168.1.100:4873/ultron
npm http 200 http://192.168.1.100:4873/options
npm http 200 http://192.168.1.100:4873/bufferutil
npm http 200 http://192.168.1.100:4873/utf-8-validate
npm http request GET http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/nan
npm http 200 http://192.168.1.100:4873/nan
npm http 200 http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/component-emitter
npm http request GET http://192.168.1.100:4873/json3
npm http request GET http://192.168.1.100:4873/benchmark
npm http 200 http://192.168.1.100:4873/component-emitter
npm http 200 http://192.168.1.100:4873/json3
npm http 200 http://192.168.1.100:4873/benchmark
npm http request GET http://192.168.1.100:4873/object-component
npm http request GET http://192.168.1.100:4873/component-bind
npm http request GET http://192.168.1.100:4873/indexof
npm http request GET http://192.168.1.100:4873/parseuri
npm http request GET http://192.168.1.100:4873/engine.io-client
npm http request GET http://192.168.1.100:4873/to-array
npm http request GET http://192.168.1.100:4873/backo2
npm http 200 http://192.168.1.100:4873/component-bind
npm http 200 http://192.168.1.100:4873/indexof
npm http 200 http://192.168.1.100:4873/parseuri
npm http 200 http://192.168.1.100:4873/object-component
npm http 200 http://192.168.1.100:4873/engine.io-client
npm http 200 http://192.168.1.100:4873/backo2
npm http 200 http://192.168.1.100:4873/to-array
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/parseqs
npm http fetch GET https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http 200 http://192.168.1.100:4873/parseqs
npm http 200 http://192.168.1.100:4873/component-inherit
npm http 200 http://192.168.1.100:4873/parsejson
npm http 200 http://192.168.1.100:4873/has-cors
npm http fetch 200 https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http fetch GET https://github.com/component/global/archive/v2.0.1.tar.gz
npm http fetch 200 https://github.com/component/global/archive/v2.0.1.tar.gz
npm http request GET http://192.168.1.100:4873/better-assert
npm http 200 http://192.168.1.100:4873/better-assert
npm http request GET http://192.168.1.100:4873/callsite
npm http 200 http://192.168.1.100:4873/callsite
npm http request GET http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/cycle
npm http request GET http://192.168.1.100:4873/colors
npm http request GET http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/pkginfo
npm http request GET http://192.168.1.100:4873/stack-trace
npm http 200 http://192.168.1.100:4873/eyes
npm http 200 http://192.168.1.100:4873/cycle
npm http 200 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/colors
npm http 200 http://192.168.1.100:4873/async
npm http 200 http://192.168.1.100:4873/pkginfo
npm http 200 http://192.168.1.100:4873/stack-trace
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/tape
npm http 200 http://192.168.1.100:4873/node-uuid
npm http 200 http://192.168.1.100:4873/tape
npm http request GET http://192.168.1.100:4873/deep-equal
npm http request GET http://192.168.1.100:4873/jsonify
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
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/forever-agent
npm http request GET http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/javascript-state-machine
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/salti
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/lie
npm http 200 http://192.168.1.100:4873/forever-agent
npm http 200 http://192.168.1.100:4873/ip
npm http 200 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/javascript-state-machine
npm http 200 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/salti
npm http 200 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/depd
npm http 200 http://192.168.1.100:4873/bytes
npm http 200 http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/ms
npm http 200 http://192.168.1.100:4873/ms
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
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 200 http://192.168.1.100:4873/methods
npm http 200 http://192.168.1.100:4873/path-to-regexp
npm http 200 http://192.168.1.100:4873/proxy-addr
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
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 304 http://192.168.1.100:4873/es3ify
npm http 304 http://192.168.1.100:4873/immediate
npm http 304 http://192.168.1.100:4873/inline-process-browser
npm http 304 http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/through
npm http 304 http://192.168.1.100:4873/through
npm http 304 http://192.168.1.100:4873/esprima
npm http 200 http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/base62
npm http 304 http://192.168.1.100:4873/commoner
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/detective
npm http 304 http://192.168.1.100:4873/private
npm http 304 http://192.168.1.100:4873/q
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http 304 http://192.168.1.100:4873/recast
npm http 200 http://192.168.1.100:4873/commander
npm http 200 http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/mkdirp
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
npm http 304 http://192.168.1.100:4873/minimatch
npm http 200 http://192.168.1.100:4873/inflight
npm http 304 http://192.168.1.100:4873/once
npm http 200 http://192.168.1.100:4873/path-is-absolute
npm http request GET http://192.168.1.100:4873/wrappy
npm http 304 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 304 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/minimist
npm http 200 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/ast-types
npm http 304 http://192.168.1.100:4873/ast-types
npm http request GET http://192.168.1.100:4873/amdefine
npm http 200 http://192.168.1.100:4873/amdefine
npm http request GET http://192.168.1.100:4873/falafel
npm http request GET http://192.168.1.100:4873/through2
npm http 304 http://192.168.1.100:4873/falafel
npm http 304 http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/foreach
npm http 304 http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/core-util-is
npm http request GET http://192.168.1.100:4873/string_decoder
npm http 304 http://192.168.1.100:4873/core-util-is
npm http 304 http://192.168.1.100:4873/string_decoder
npm http request GET http://192.168.1.100:4873/esmangle-evaluator
npm http 304 http://192.168.1.100:4873/esmangle-evaluator
npm http request GET http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/duplexify
npm http 200 http://192.168.1.100:4873/duplexify
npm http 200 http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/stream-shift
npm http 200 http://192.168.1.100:4873/end-of-stream
npm http 200 http://192.168.1.100:4873/stream-shift
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http 200 http://192.168.1.100:4873/process-nextick-args
npm http 200 http://192.168.1.100:4873/util-deprecate
npm http 200 http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/har-validator
npm http 200 http://192.168.1.100:4873/json-stringify-safe
npm http 200 http://192.168.1.100:4873/oauth-sign
npm http 200 http://192.168.1.100:4873/form-data
npm http 200 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/caseless
npm http 200 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/http-signature
npm http 200 http://192.168.1.100:4873/tunnel-agent
npm http 200 http://192.168.1.100:4873/bl
npm http 200 http://192.168.1.100:4873/stringstream
npm http 200 http://192.168.1.100:4873/combined-stream
npm http 200 http://192.168.1.100:4873/aws-sign2
npm http 200 http://192.168.1.100:4873/har-validator
npm http 200 http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 200 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http 304 http://192.168.1.100:4873/bluebird
npm http 200 http://192.168.1.100:4873/chalk
npm http 200 http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 200 http://192.168.1.100:4873/has-ansi
npm http 200 http://192.168.1.100:4873/escape-string-regexp
npm http 200 http://192.168.1.100:4873/ansi-styles
npm http 200 http://192.168.1.100:4873/strip-ansi
npm http 200 http://192.168.1.100:4873/supports-color
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 200 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http request GET http://192.168.1.100:4873/generate-function
npm http 200 http://192.168.1.100:4873/generate-function
npm http 200 http://192.168.1.100:4873/jsonpointer
npm http 200 http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/is-property
npm http 200 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/boom
npm http 200 http://192.168.1.100:4873/sntp
npm http 200 http://192.168.1.100:4873/boom
npm http 200 http://192.168.1.100:4873/hoek
npm http 200 http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/ctype
npm http 200 http://192.168.1.100:4873/asn1
npm http 200 http://192.168.1.100:4873/assert-plus
npm http 200 http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/colors
npm http request GET http://192.168.1.100:4873/cycle
npm http request GET http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/pkginfo
npm http request GET http://192.168.1.100:4873/stack-trace
npm http 304 http://192.168.1.100:4873/colors
npm http 304 http://192.168.1.100:4873/pkginfo
npm http 304 http://192.168.1.100:4873/cycle
npm http 304 http://192.168.1.100:4873/eyes
npm http 200 http://192.168.1.100:4873/stack-trace
npm http request GET http://192.168.1.100:4873/jsdoc
npm http 200 http://192.168.1.100:4873/jsdoc
npm http request GET http://192.168.1.100:4873/js2xmlparser
npm http request GET http://192.168.1.100:4873/catharsis
npm http request GET http://192.168.1.100:4873/marked
npm http request GET http://192.168.1.100:4873/requizzle
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/underscore
npm http request GET http://192.168.1.100:4873/wrench
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 200 http://192.168.1.100:4873/js2xmlparser
npm http 200 http://192.168.1.100:4873/strip-json-comments
npm http 200 http://192.168.1.100:4873/marked
npm http 200 http://192.168.1.100:4873/catharsis
npm http 200 http://192.168.1.100:4873/requizzle
npm http 200 http://192.168.1.100:4873/underscore
npm http 200 http://192.168.1.100:4873/wrench
npm WARN deprecated wrench@1.5.9: wrench.js is deprecated! You should check out fs-extra (https://github.com/jprichardson/node-fs-extra) for any operations you were using wrench for. Thanks for all the usage over the years.
npm http fetch 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http request GET http://192.168.1.100:4873/underscore-contrib
npm http 200 http://192.168.1.100:4873/underscore-contrib
npm WARN prefer global marked@0.3.6 should be installed with -g
npm http request GET http://192.168.1.100:4873/fs-extra-promise
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/jxc
npm http request GET http://192.168.1.100:4873/unzip
npm http 304 http://192.168.1.100:4873/lie
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/fs-extra-promise
npm http 200 http://192.168.1.100:4873/unzip
npm http 200 http://192.168.1.100:4873/jxc
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
npm http 304 http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/fs.realpath
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/fs.realpath
npm http 304 http://192.168.1.100:4873/inflight
npm http 304 http://192.168.1.100:4873/minimatch
npm http 304 http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/inherits
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
npm http 200 http://192.168.1.100:4873/adm-zip
npm http 200 http://192.168.1.100:4873/progress
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 304 http://192.168.1.100:4873/es3ify
npm http 304 http://192.168.1.100:4873/immediate
npm http 304 http://192.168.1.100:4873/inline-process-browser
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
npm http 304 http://192.168.1.100:4873/base62
npm http 304 http://192.168.1.100:4873/commoner
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/commander
npm http 304 http://192.168.1.100:4873/detective
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/q
npm http 304 http://192.168.1.100:4873/mkdirp
npm http 304 http://192.168.1.100:4873/private
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
npm http 304 http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/foreach
npm http 304 http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/core-util-is
npm http request GET http://192.168.1.100:4873/string_decoder
npm http 304 http://192.168.1.100:4873/core-util-is
npm http 304 http://192.168.1.100:4873/string_decoder
npm http request GET http://192.168.1.100:4873/esmangle-evaluator
npm http 304 http://192.168.1.100:4873/esmangle-evaluator
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/bl
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
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 200 http://192.168.1.100:4873/forever-agent
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/isstream
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
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/ansi-styles
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http 304 http://192.168.1.100:4873/supports-color
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-function
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/boom
npm http 304 http://192.168.1.100:4873/hoek
npm http 304 http://192.168.1.100:4873/cryptiles
npm http 304 http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/boom
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
npm http 200 http://192.168.1.100:4873/binary
npm http 200 http://192.168.1.100:4873/setimmediate
npm http 200 http://192.168.1.100:4873/fstream
npm http 200 http://192.168.1.100:4873/pullstream
npm http 200 http://192.168.1.100:4873/match-stream
npm http request GET http://192.168.1.100:4873/chainsaw
npm http request GET http://192.168.1.100:4873/buffers
npm http 200 http://192.168.1.100:4873/buffers
npm http 200 http://192.168.1.100:4873/chainsaw
npm http request GET http://192.168.1.100:4873/traverse
npm http 200 http://192.168.1.100:4873/traverse
npm http fetch GET http://192.168.1.100:4873/graceful-fs/-/graceful-fs-3.0.9.tgz
npm http fetch 200 http://192.168.1.100:4873/graceful-fs/-/graceful-fs-3.0.9.tgz
npm http request GET http://192.168.1.100:4873/slice-stream
npm http request GET http://192.168.1.100:4873/over
npm http 200 http://192.168.1.100:4873/over
npm http 200 http://192.168.1.100:4873/slice-stream
npm WARN EPACKAGEJSON install@0.0.1 No repository field.
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/bn.js
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/forever-agent
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/express-pouchdb
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/leveldown-mobile
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/nock
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/proxyquire
npm http request GET http://192.168.1.100:4873/tape
npm http request GET http://192.168.1.100:4873/pouchdb-node
npm http request GET http://192.168.1.100:4873/supertest
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/sinon
npm http request GET http://192.168.1.100:4873/supertest-as-promised
npm http request GET http://192.168.1.100:4873/request-promise
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/tmp
npm http request GET http://192.168.1.100:4873/tape-catch
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/forever-agent
npm http 304 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 200 http://192.168.1.100:4873/bn.js
npm http 304 http://192.168.1.100:4873/inherits
npm http 200 http://192.168.1.100:4873/is-property
npm http 200 http://192.168.1.100:4873/js-extend
npm http 200 http://192.168.1.100:4873/express-pouchdb
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 200 http://192.168.1.100:4873/randomstring
npm http 304 http://192.168.1.100:4873/socket.io-client
npm http 304 http://192.168.1.100:4873/leveldown-mobile
npm http 200 http://192.168.1.100:4873/proxyquire
npm http 304 http://192.168.1.100:4873/tape
npm http 304 http://192.168.1.100:4873/pouchdb-node
npm http 200 http://192.168.1.100:4873/nock
npm http 304 http://192.168.1.100:4873/multiplex
npm http 200 http://192.168.1.100:4873/supertest
npm http 200 http://192.168.1.100:4873/supertest-as-promised
npm http 200 http://192.168.1.100:4873/long
npm http 200 http://192.168.1.100:4873/request-promise
npm http 200 http://192.168.1.100:4873/sinon
npm http 200 http://192.168.1.100:4873/uuid
npm http 304 http://192.168.1.100:4873/tmp
npm http 200 http://192.168.1.100:4873/tape-catch
npm http 304 http://192.168.1.100:4873/urlsafe-base64
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
npm http 304 http://192.168.1.100:4873/http-errors
npm http 200 http://192.168.1.100:4873/bytes
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/content-type
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
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/serve-static
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
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/compression
npm http request GET http://192.168.1.100:4873/basic-auth
npm http request GET http://192.168.1.100:4873/header-case-normalizer
npm http request GET http://192.168.1.100:4873/cookie-parser
npm http request GET http://192.168.1.100:4873/multiparty
npm http request GET http://192.168.1.100:4873/pouchdb-all-dbs
npm http request GET http://192.168.1.100:4873/pouchdb-list
npm http request GET http://192.168.1.100:4873/pouchdb-find
npm http request GET http://192.168.1.100:4873/pouchdb-rewrite
npm http request GET http://192.168.1.100:4873/pouchdb-replicator
npm http request GET http://192.168.1.100:4873/pouchdb-security
npm http request GET http://192.168.1.100:4873/pouchdb-show
npm http request GET http://192.168.1.100:4873/pouchdb-auth
npm http request GET http://192.168.1.100:4873/pouchdb-size
npm http request GET http://192.168.1.100:4873/pouchdb-update
npm http request GET http://192.168.1.100:4873/pouchdb-validation
npm http request GET http://192.168.1.100:4873/pouchdb-vhost
npm http request GET http://192.168.1.100:4873/pouchdb-wrappers
npm http 304 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/cookie-parser
npm http 200 http://192.168.1.100:4873/basic-auth
npm http 200 http://192.168.1.100:4873/compression
npm http 200 http://192.168.1.100:4873/multiparty
npm http 200 http://192.168.1.100:4873/pouchdb-find
npm http 200 http://192.168.1.100:4873/header-case-normalizer
npm http 200 http://192.168.1.100:4873/pouchdb-all-dbs
npm http 200 http://192.168.1.100:4873/pouchdb-security
npm http 200 http://192.168.1.100:4873/pouchdb-rewrite
npm http 200 http://192.168.1.100:4873/pouchdb-replicator
npm http 200 http://192.168.1.100:4873/pouchdb-list
npm http 200 http://192.168.1.100:4873/pouchdb-size
npm http 200 http://192.168.1.100:4873/pouchdb-auth
npm http 200 http://192.168.1.100:4873/pouchdb-update
npm http 200 http://192.168.1.100:4873/pouchdb-validation
npm http 200 http://192.168.1.100:4873/pouchdb-vhost
npm http 200 http://192.168.1.100:4873/pouchdb-wrappers
npm http 200 http://192.168.1.100:4873/pouchdb-show
npm http request GET http://192.168.1.100:4873/setprototypeof
npm http 200 http://192.168.1.100:4873/setprototypeof
npm http request GET http://192.168.1.100:4873/on-headers
npm http request GET http://192.168.1.100:4873/compressible
npm http 200 http://192.168.1.100:4873/compressible
npm http 200 http://192.168.1.100:4873/on-headers
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/stream-counter
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 200 http://192.168.1.100:4873/stream-counter
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/argsarray
npm http request GET http://192.168.1.100:4873/tiny-queue
npm http request GET http://192.168.1.100:4873/pouchdb-promise
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
npm http request GET http://192.168.1.100:4873/crypto-lite
npm http request GET http://192.168.1.100:4873/pouchdb-plugin-error
npm http request GET http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http request GET http://192.168.1.100:4873/pouchdb
npm http request GET http://192.168.1.100:4873/pouchdb-req-http-query
npm http request GET http://192.168.1.100:4873/pouchdb-system-db
npm http request GET http://192.168.1.100:4873/promise-nodify
npm http request GET http://192.168.1.100:4873/secure-random
npm http 200 http://192.168.1.100:4873/couchdb-calculate-session-id
npm http 200 http://192.168.1.100:4873/crypto-lite
npm http 200 http://192.168.1.100:4873/base64url
npm http 200 http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http 200 http://192.168.1.100:4873/pouchdb-plugin-error
npm http 200 http://192.168.1.100:4873/pouchdb-req-http-query
npm http 200 http://192.168.1.100:4873/promise-nodify
npm http 200 http://192.168.1.100:4873/pouchdb
npm http 200 http://192.168.1.100:4873/pouchdb-system-db
npm http 200 http://192.168.1.100:4873/secure-random
npm http request GET http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/meow
npm http 200 http://192.168.1.100:4873/concat-stream
npm http 200 http://192.168.1.100:4873/meow
npm http request GET http://192.168.1.100:4873/typedarray
npm http 200 http://192.168.1.100:4873/typedarray
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/camelcase-keys
npm http request GET http://192.168.1.100:4873/indent-string
npm http 304 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/camelcase-keys
npm http 200 http://192.168.1.100:4873/indent-string
npm http request GET http://192.168.1.100:4873/map-obj
npm http request GET http://192.168.1.100:4873/camelcase
npm http 200 http://192.168.1.100:4873/map-obj
npm http 200 http://192.168.1.100:4873/camelcase
npm http request GET http://192.168.1.100:4873/repeating
npm http request GET http://192.168.1.100:4873/get-stdin
npm http 200 http://192.168.1.100:4873/get-stdin
npm http 200 http://192.168.1.100:4873/repeating
npm http request GET http://192.168.1.100:4873/is-finite
npm http 200 http://192.168.1.100:4873/is-finite
npm http request GET http://192.168.1.100:4873/number-is-nan
npm http 200 http://192.168.1.100:4873/number-is-nan
npm http request GET http://192.168.1.100:4873/aproba
npm http 200 http://192.168.1.100:4873/aproba
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/pouchdb-collate
npm http request GET http://192.168.1.100:4873/scope-eval
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/vuvuzela
npm http request GET http://192.168.1.100:4873/memdown
npm http request GET http://192.168.1.100:4873/localstorage-down
npm http request GET http://192.168.1.100:4873/level-write-stream
npm http request GET http://192.168.1.100:4873/fruitdown
npm http request GET http://192.168.1.100:4873/es6-promise-pool
npm http request GET http://192.168.1.100:4873/levelup
npm http 200 http://192.168.1.100:4873/scope-eval
npm http 304 http://192.168.1.100:4873/through2
npm http 200 http://192.168.1.100:4873/sublevel-pouchdb
npm http 200 http://192.168.1.100:4873/pouchdb-collate
npm http 200 http://192.168.1.100:4873/vuvuzela
npm http 200 http://192.168.1.100:4873/double-ended-queue
npm http 200 http://192.168.1.100:4873/pouchdb-collections
npm http 200 http://192.168.1.100:4873/memdown
npm http 200 http://192.168.1.100:4873/level-write-stream
npm http 200 http://192.168.1.100:4873/spark-md5
npm http 200 http://192.168.1.100:4873/localstorage-down
npm http 200 http://192.168.1.100:4873/fruitdown
npm http 200 http://192.168.1.100:4873/es6-promise-pool
npm http 200 http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/d64
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http 200 http://192.168.1.100:4873/abstract-leveldown
npm http 200 http://192.168.1.100:4873/d64
npm http request GET http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/end-stream
npm http 200 http://192.168.1.100:4873/end-stream
npm http request GET http://192.168.1.100:4873/write-stream
npm http 200 http://192.168.1.100:4873/write-stream
npm http request GET http://192.168.1.100:4873/prr
npm http request GET http://192.168.1.100:4873/level-iterator-stream
npm http request GET http://192.168.1.100:4873/level-codec
npm http request GET http://192.168.1.100:4873/level-errors
npm http request GET http://192.168.1.100:4873/deferred-leveldown
npm http request GET http://192.168.1.100:4873/semver
npm http 200 http://192.168.1.100:4873/prr
npm http 200 http://192.168.1.100:4873/level-iterator-stream
npm http 200 http://192.168.1.100:4873/semver
npm http 200 http://192.168.1.100:4873/level-errors
npm http 200 http://192.168.1.100:4873/deferred-leveldown
npm http 200 http://192.168.1.100:4873/level-codec
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
npm http request GET http://192.168.1.100:4873/is-typedarray
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/aws4
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/har-validator
npm http 200 http://192.168.1.100:4873/is-typedarray
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 304 http://192.168.1.100:4873/qs
npm http 200 http://192.168.1.100:4873/aws4
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/extend
npm WARN deprecated tough-cookie@2.2.2: ReDoS vulnerability parsing Set-Cookie https://nodesecurity.io/advisories/130
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/readable-stream
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
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/pinkie-promise
npm http 304 http://192.168.1.100:4873/is-my-json-valid
npm http 200 http://192.168.1.100:4873/pinkie-promise
npm http 304 http://192.168.1.100:4873/chalk
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
npm http 304 http://192.168.1.100:4873/cryptiles
npm http 304 http://192.168.1.100:4873/hoek
npm http 304 http://192.168.1.100:4873/boom
npm http 304 http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/jsprim
npm http request GET http://192.168.1.100:4873/sshpk
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 200 http://192.168.1.100:4873/jsprim
npm http 200 http://192.168.1.100:4873/sshpk
npm http request GET http://192.168.1.100:4873/extsprintf
npm http request GET http://192.168.1.100:4873/json-schema
npm http request GET http://192.168.1.100:4873/verror
npm http 200 http://192.168.1.100:4873/extsprintf
npm http 200 http://192.168.1.100:4873/json-schema
npm http 200 http://192.168.1.100:4873/verror
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/getpass
npm http request GET http://192.168.1.100:4873/dashdash
npm http 200 http://192.168.1.100:4873/getpass
npm http 304 http://192.168.1.100:4873/asn1
npm http 200 http://192.168.1.100:4873/dashdash
npm http request GET http://192.168.1.100:4873/pull-stream
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
npm http 200 http://192.168.1.100:4873/xmlhttprequest-cookie
npm http request GET http://192.168.1.100:4873/xmlhttprequest
npm http 200 http://192.168.1.100:4873/xmlhttprequest
npm http request GET http://192.168.1.100:4873/pouchdb-changeslike-wrapper
npm http 200 http://192.168.1.100:4873/pouchdb-changeslike-wrapper
npm http request GET http://192.168.1.100:4873/couchdb-eval
npm http request GET http://192.168.1.100:4873/couchdb-objects
npm http request GET http://192.168.1.100:4873/random-uuid-v4
npm http 200 http://192.168.1.100:4873/couchdb-eval
npm http 200 http://192.168.1.100:4873/couchdb-objects
npm http 200 http://192.168.1.100:4873/random-uuid-v4
npm http request GET http://192.168.1.100:4873/is-empty
npm http 200 http://192.168.1.100:4873/is-empty
npm http request GET http://192.168.1.100:4873/is-array
npm http request GET http://192.168.1.100:4873/pouchdb-extend
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/pouchdb-upsert
npm http 304 http://192.168.1.100:4873/spark-md5
npm http 200 http://192.168.1.100:4873/is-array
npm http 200 http://192.168.1.100:4873/pouchdb-extend
npm http 200 http://192.168.1.100:4873/pouchdb-upsert
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 304 http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/couchdb-render
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
npm http request GET http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/fast-future
npm http 304 http://192.168.1.100:4873/bindings
npm http 304 http://192.168.1.100:4873/abstract-leveldown
npm http 200 http://192.168.1.100:4873/fast-future
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/varint
npm http 304 http://192.168.1.100:4873/duplexify
npm http 304 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/stream-shift
npm http 304 http://192.168.1.100:4873/stream-shift
npm http 304 http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http 304 http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/deep-equal
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/propagate
npm http request GET http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/chai
npm http 304 http://192.168.1.100:4873/deep-equal
npm http 304 http://192.168.1.100:4873/debug
npm http 200 http://192.168.1.100:4873/chai
npm http 200 http://192.168.1.100:4873/propagate
npm http 200 http://192.168.1.100:4873/lodash
npm WARN deprecated lodash@2.4.1: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
npm http request GET http://192.168.1.100:4873/assertion-error
npm http request GET http://192.168.1.100:4873/type-detect
npm http request GET http://192.168.1.100:4873/deep-eql
npm http 200 http://192.168.1.100:4873/assertion-error
npm http 200 http://192.168.1.100:4873/type-detect
npm http 200 http://192.168.1.100:4873/deep-eql
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/ip
npm http 304 http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/pouchdb-replication
npm http request GET http://192.168.1.100:4873/pouchdb-core
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-leveldb
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-http
npm http request GET http://192.168.1.100:4873/pouchdb-mapreduce
npm http 304 http://192.168.1.100:4873/pouchdb-mapreduce
npm http 304 http://192.168.1.100:4873/pouchdb-replication
npm http 304 http://192.168.1.100:4873/pouchdb-core
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-leveldb
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-http
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/pouchdb-ajax
npm http request GET http://192.168.1.100:4873/pouchdb-md5
npm http request GET http://192.168.1.100:4873/pouchdb-errors
npm http request GET http://192.168.1.100:4873/pouchdb-binary-utils
npm http request GET http://192.168.1.100:4873/pouchdb-utils
npm http 304 http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/pouchdb-ajax
npm http 304 http://192.168.1.100:4873/pouchdb-md5
npm http 304 http://192.168.1.100:4873/pouchdb-utils
npm http 304 http://192.168.1.100:4873/pouchdb-binary-utils
npm http 304 http://192.168.1.100:4873/pouchdb-errors
npm http request GET http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http 304 http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-leveldb-core
npm http request GET http://192.168.1.100:4873/leveldown
npm http 200 http://192.168.1.100:4873/leveldown
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-leveldb-core
npm http request GET http://192.168.1.100:4873/nan
npm http request GET http://192.168.1.100:4873/prebuild
npm http 304 http://192.168.1.100:4873/nan
npm http 200 http://192.168.1.100:4873/prebuild
npm http request GET http://192.168.1.100:4873/expand-template
npm http request GET http://192.168.1.100:4873/ghreleases
npm http request GET http://192.168.1.100:4873/github-from-package
npm http request GET http://192.168.1.100:4873/rc
npm http request GET http://192.168.1.100:4873/node-gyp
npm http request GET http://192.168.1.100:4873/simple-get
npm http request GET http://192.168.1.100:4873/os-homedir
npm http request GET http://192.168.1.100:4873/npmlog
npm http request GET http://192.168.1.100:4873/pump
npm http request GET http://192.168.1.100:4873/noop-logger
npm http request GET http://192.168.1.100:4873/node-ninja
npm http request GET http://192.168.1.100:4873/tar-fs
npm http request GET http://192.168.1.100:4873/tar-stream
npm http 200 http://192.168.1.100:4873/rc
npm http 200 http://192.168.1.100:4873/node-gyp
npm http 200 http://192.168.1.100:4873/expand-template
npm http 200 http://192.168.1.100:4873/os-homedir
npm http 200 http://192.168.1.100:4873/ghreleases
npm http 200 http://192.168.1.100:4873/npmlog
npm http 200 http://192.168.1.100:4873/pump
npm http 200 http://192.168.1.100:4873/tar-fs
npm http 200 http://192.168.1.100:4873/noop-logger
npm http 200 http://192.168.1.100:4873/simple-get
npm http 200 http://192.168.1.100:4873/tar-stream
npm http 200 http://192.168.1.100:4873/github-from-package
npm http 200 http://192.168.1.100:4873/node-ninja
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/simple-mime
npm http request GET http://192.168.1.100:4873/ghutils
npm http request GET http://192.168.1.100:4873/ghrepos
npm http request GET http://192.168.1.100:4873/url-template
npm http 304 http://192.168.1.100:4873/after
npm http fetch GET http://192.168.1.100:4873/after/-/after-0.8.2.tgz
npm http 200 http://192.168.1.100:4873/ghrepos
npm http 200 http://192.168.1.100:4873/simple-mime
npm http fetch 200 http://192.168.1.100:4873/after/-/after-0.8.2.tgz
npm http 200 http://192.168.1.100:4873/url-template
npm http 200 http://192.168.1.100:4873/ghutils
npm http request GET http://192.168.1.100:4873/jsonist
npm http 200 http://192.168.1.100:4873/jsonist
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/hyperquest
npm http 304 http://192.168.1.100:4873/bl
npm http 200 http://192.168.1.100:4873/hyperquest
npm http request GET http://192.168.1.100:4873/duplexer2
npm http 200 http://192.168.1.100:4873/duplexer2
npm http request GET http://192.168.1.100:4873/fstream
npm http request GET http://192.168.1.100:4873/nopt
npm http request GET http://192.168.1.100:4873/osenv
npm http request GET http://192.168.1.100:4873/tar
npm http request GET http://192.168.1.100:4873/path-array
npm http request GET http://192.168.1.100:4873/which
npm http 304 http://192.168.1.100:4873/fstream
npm http 200 http://192.168.1.100:4873/osenv
npm http 200 http://192.168.1.100:4873/path-array
npm http 200 http://192.168.1.100:4873/tar
npm http 200 http://192.168.1.100:4873/nopt
npm http 200 http://192.168.1.100:4873/which
npm http request GET http://192.168.1.100:4873/abbrev
npm http 200 http://192.168.1.100:4873/abbrev
npm http request GET http://192.168.1.100:4873/are-we-there-yet
npm http request GET http://192.168.1.100:4873/ansi
npm http request GET http://192.168.1.100:4873/gauge
npm http 200 http://192.168.1.100:4873/are-we-there-yet
npm http 200 http://192.168.1.100:4873/gauge
npm http 200 http://192.168.1.100:4873/ansi
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/delegates
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 200 http://192.168.1.100:4873/delegates
npm http request GET http://192.168.1.100:4873/has-unicode
npm http request GET http://192.168.1.100:4873/lodash.padend
npm http request GET http://192.168.1.100:4873/lodash.pad
npm http request GET http://192.168.1.100:4873/lodash.padstart
npm http 200 http://192.168.1.100:4873/has-unicode
npm http 200 http://192.168.1.100:4873/lodash.padend
npm http 200 http://192.168.1.100:4873/lodash.pad
npm http 200 http://192.168.1.100:4873/lodash.padstart
npm http fetch GET http://192.168.1.100:4873/lodash.padend/-/lodash.padend-4.6.1.tgz
npm http fetch 200 http://192.168.1.100:4873/lodash.padend/-/lodash.padend-4.6.1.tgz
npm http fetch GET http://192.168.1.100:4873/lodash.pad/-/lodash.pad-4.5.1.tgz
npm http fetch GET http://192.168.1.100:4873/lodash.padstart/-/lodash.padstart-4.6.1.tgz
npm http fetch 200 http://192.168.1.100:4873/lodash.pad/-/lodash.pad-4.5.1.tgz
npm http fetch 200 http://192.168.1.100:4873/lodash.padstart/-/lodash.padstart-4.6.1.tgz
npm http request GET http://192.168.1.100:4873/os-tmpdir
npm http 200 http://192.168.1.100:4873/os-tmpdir
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
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/http-signature
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
npm http 200 http://192.168.1.100:4873/block-stream
npm http request GET http://192.168.1.100:4873/isexe
npm http 200 http://192.168.1.100:4873/isexe
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http 304 http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/ini
npm http request GET http://192.168.1.100:4873/deep-extend
npm http 304 http://192.168.1.100:4873/strip-json-comments
npm http 200 http://192.168.1.100:4873/ini
npm http 200 http://192.168.1.100:4873/deep-extend
npm WARN engine deep-extend@0.4.1: wanted: {"node":">=0.12.0","iojs":">=1.0.0"} (current: {"node":"0.10.40","npm":"3.3.12"})
npm http request GET http://192.168.1.100:4873/unzip-response
npm http 200 http://192.168.1.100:4873/unzip-response
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-utils
npm http request GET http://192.168.1.100:4873/pouchdb-merge
npm http request GET http://192.168.1.100:4873/pouchdb-json
npm http 304 http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/sublevel-pouchdb
npm http 304 http://192.168.1.100:4873/pouchdb-collections
npm http 304 http://192.168.1.100:4873/pouchdb-merge
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-utils
npm http 304 http://192.168.1.100:4873/pouchdb-json
npm http request GET http://192.168.1.100:4873/ltgt
npm http 304 http://192.168.1.100:4873/ltgt
npm http request GET http://192.168.1.100:4873/pouchdb-mapreduce-utils
npm http 304 http://192.168.1.100:4873/pouchdb-mapreduce-utils
npm http request GET http://192.168.1.100:4873/pouchdb-checkpointer
npm http request GET http://192.168.1.100:4873/pouchdb-generate-replication-id
npm http 304 http://192.168.1.100:4873/pouchdb-generate-replication-id
npm http 304 http://192.168.1.100:4873/pouchdb-checkpointer
npm http request GET http://192.168.1.100:4873/module-not-found-error
npm http request GET http://192.168.1.100:4873/fill-keys
npm http 200 http://192.168.1.100:4873/module-not-found-error
npm http 200 http://192.168.1.100:4873/fill-keys
npm http request GET http://192.168.1.100:4873/is-object
npm http 200 http://192.168.1.100:4873/is-object
npm http request GET http://192.168.1.100:4873/array-uniq
npm http 200 http://192.168.1.100:4873/array-uniq
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/samsam
npm http request GET http://192.168.1.100:4873/util
npm http request GET http://192.168.1.100:4873/lolex
npm http request GET http://192.168.1.100:4873/formatio
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
npm http request GET http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/component-emitter
npm http 304 http://192.168.1.100:4873/socket.io-parser
npm http 304 http://192.168.1.100:4873/component-bind
npm http 304 http://192.168.1.100:4873/engine.io-client
npm http 304 http://192.168.1.100:4873/object-component
npm http 304 http://192.168.1.100:4873/has-binary
npm http 304 http://192.168.1.100:4873/to-array
npm http 304 http://192.168.1.100:4873/indexof
npm http 304 http://192.168.1.100:4873/parseuri
npm http 304 http://192.168.1.100:4873/backo2
npm http 304 http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/parseqs
npm http request GET http://192.168.1.100:4873/ws
npm http fetch GET https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http 304 http://192.168.1.100:4873/component-inherit
npm http 304 http://192.168.1.100:4873/has-cors
npm http 304 http://192.168.1.100:4873/parseqs
npm http 304 http://192.168.1.100:4873/parsejson
npm http 304 http://192.168.1.100:4873/engine.io-parser
npm http 304 http://192.168.1.100:4873/ws
npm http fetch 200 https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/utf8
npm http request GET http://192.168.1.100:4873/after
npm http 304 http://192.168.1.100:4873/arraybuffer.slice
npm http 304 http://192.168.1.100:4873/blob
npm http 304 http://192.168.1.100:4873/base64-arraybuffer
npm http 304 http://192.168.1.100:4873/utf8
npm http 200 http://192.168.1.100:4873/after
npm http fetch GET http://192.168.1.100:4873/after/-/after-0.8.1.tgz
npm http fetch 200 http://192.168.1.100:4873/after/-/after-0.8.1.tgz
npm http fetch GET https://github.com/component/global/archive/v2.0.1.tar.gz
npm http fetch 200 https://github.com/component/global/archive/v2.0.1.tar.gz
npm http request GET http://192.168.1.100:4873/better-assert
npm http 304 http://192.168.1.100:4873/better-assert
npm http request GET http://192.168.1.100:4873/callsite
npm http 304 http://192.168.1.100:4873/callsite
npm http request GET http://192.168.1.100:4873/options
npm http request GET http://192.168.1.100:4873/ultron
npm http 304 http://192.168.1.100:4873/options
npm http 200 http://192.168.1.100:4873/ultron
npm http request GET http://192.168.1.100:4873/json3
npm http request GET http://192.168.1.100:4873/benchmark
npm http 304 http://192.168.1.100:4873/json3
npm http 304 http://192.168.1.100:4873/benchmark
npm http request GET http://192.168.1.100:4873/superagent
npm http 200 http://192.168.1.100:4873/superagent
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/reduce-component
npm http request GET http://192.168.1.100:4873/cookiejar
npm http request GET http://192.168.1.100:4873/formidable
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 200 http://192.168.1.100:4873/cookiejar
npm http 200 http://192.168.1.100:4873/reduce-component
npm http 200 http://192.168.1.100:4873/formidable
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/combined-stream
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
npm http 200 http://192.168.1.100:4873/object-inspect
npm http 200 http://192.168.1.100:4873/resumer
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

```

Error: Command failed: npm http request GET http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/socket.io
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/fs-extra-promise
npm http request GET http://192.168.1.100:4873/express
npm http 200 http://192.168.1.100:4873/socket.io
npm http 200 http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/lie
npm http 200 http://192.168.1.100:4873/fs-extra-promise
npm http 200 http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/cookie-signature
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/accepts
npm http request GET http://192.168.1.100:4873/cookie
npm http request GET http://192.168.1.100:4873/escape-html
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/content-disposition
npm http request GET http://192.168.1.100:4873/array-flatten
npm http request GET http://192.168.1.100:4873/parseurl
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/range-parser
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/path-to-regexp
npm http request GET http://192.168.1.100:4873/proxy-addr
npm http request GET http://192.168.1.100:4873/merge-descriptors
npm http request GET http://192.168.1.100:4873/finalhandler
npm http request GET http://192.168.1.100:4873/fresh
npm http request GET http://192.168.1.100:4873/etag
npm http request GET http://192.168.1.100:4873/utils-merge
npm http request GET http://192.168.1.100:4873/send
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/vary
npm http request GET http://192.168.1.100:4873/serve-static
npm http 200 http://192.168.1.100:4873/cookie-signature
npm http 200 http://192.168.1.100:4873/depd
npm http 200 http://192.168.1.100:4873/debug
npm http 200 http://192.168.1.100:4873/cookie
npm http 200 http://192.168.1.100:4873/accepts
npm http 200 http://192.168.1.100:4873/escape-html
npm http 200 http://192.168.1.100:4873/content-type
npm http 200 http://192.168.1.100:4873/array-flatten
npm http 200 http://192.168.1.100:4873/content-disposition
npm http 200 http://192.168.1.100:4873/parseurl
npm http 200 http://192.168.1.100:4873/on-finished
npm http 200 http://192.168.1.100:4873/range-parser
npm http 200 http://192.168.1.100:4873/methods
npm http 200 http://192.168.1.100:4873/qs
npm http 200 http://192.168.1.100:4873/path-to-regexp
npm http 200 http://192.168.1.100:4873/proxy-addr
npm http 200 http://192.168.1.100:4873/merge-descriptors
npm http 200 http://192.168.1.100:4873/fresh
npm http 200 http://192.168.1.100:4873/finalhandler
npm http 200 http://192.168.1.100:4873/etag
npm http 200 http://192.168.1.100:4873/utils-merge
npm http 200 http://192.168.1.100:4873/send
npm http 200 http://192.168.1.100:4873/type-is
npm http 200 http://192.168.1.100:4873/vary
npm http 200 http://192.168.1.100:4873/serve-static
npm http request GET http://192.168.1.100:4873/negotiator
npm http request GET http://192.168.1.100:4873/mime-types
npm http 200 http://192.168.1.100:4873/negotiator
npm http 200 http://192.168.1.100:4873/mime-types
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
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/mime
npm http request GET http://192.168.1.100:4873/statuses
npm http 200 http://192.168.1.100:4873/destroy
npm http 200 http://192.168.1.100:4873/http-errors
npm http 200 http://192.168.1.100:4873/statuses
npm http 200 http://192.168.1.100:4873/mime
npm http request GET http://192.168.1.100:4873/inherits
npm http 200 http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/media-typer
npm http 200 http://192.168.1.100:4873/media-typer
npm http request GET http://192.168.1.100:4873/fs-extra
npm http request GET http://192.168.1.100:4873/bluebird
npm http 200 http://192.168.1.100:4873/fs-extra
npm http 200 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/jsonfile
npm http request GET http://192.168.1.100:4873/rimraf
npm http 200 http://192.168.1.100:4873/jsonfile
npm http 200 http://192.168.1.100:4873/graceful-fs
npm http 200 http://192.168.1.100:4873/rimraf
npm http request GET http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/fs.realpath
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/minimatch
npm http 200 http://192.168.1.100:4873/inflight
npm http 200 http://192.168.1.100:4873/once
npm http 200 http://192.168.1.100:4873/fs.realpath
npm http 200 http://192.168.1.100:4873/path-is-absolute
npm http 200 http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/wrappy
npm http 200 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 200 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/concat-map
npm http 200 http://192.168.1.100:4873/concat-map
npm http 200 http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/immediate
npm http 200 http://192.168.1.100:4873/inline-process-browser
npm http 200 http://192.168.1.100:4873/es3ify
npm http 200 http://192.168.1.100:4873/unreachable-branch-transform
npm http 200 http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/through
npm http request GET http://192.168.1.100:4873/jstransform
npm http 200 http://192.168.1.100:4873/jstransform
npm http 200 http://192.168.1.100:4873/esprima
npm http 200 http://192.168.1.100:4873/through
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/source-map
npm http 200 http://192.168.1.100:4873/base62
npm http 200 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/esprima-fb
npm http 200 http://192.168.1.100:4873/commoner
npm http 200 http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/recast
npm http 200 http://192.168.1.100:4873/private
npm http 200 http://192.168.1.100:4873/mkdirp
npm http 200 http://192.168.1.100:4873/commander
npm http 200 http://192.168.1.100:4873/iconv-lite
npm http 200 http://192.168.1.100:4873/detective
npm http 200 http://192.168.1.100:4873/q
npm http 200 http://192.168.1.100:4873/recast
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
npm http 200 http://192.168.1.100:4873/amdefine
npm http request GET http://192.168.1.100:4873/falafel
npm http request GET http://192.168.1.100:4873/through2
npm http 200 http://192.168.1.100:4873/falafel
npm http 200 http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/object-keys
npm http 200 http://192.168.1.100:4873/foreach
npm http 200 http://192.168.1.100:4873/isarray
npm http 200 http://192.168.1.100:4873/object-keys
npm http request GET http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 200 http://192.168.1.100:4873/xtend
npm http 200 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/core-util-is
npm http request GET http://192.168.1.100:4873/string_decoder
npm http 200 http://192.168.1.100:4873/string_decoder
npm http 200 http://192.168.1.100:4873/core-util-is
npm http request GET http://192.168.1.100:4873/esmangle-evaluator
npm http 200 http://192.168.1.100:4873/esmangle-evaluator
npm http request GET http://192.168.1.100:4873/socket.io-parser
npm http request GET http://192.168.1.100:4873/has-binary-data
npm http request GET http://192.168.1.100:4873/socket.io-adapter
npm http request GET http://192.168.1.100:4873/engine.io
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http 200 http://192.168.1.100:4873/socket.io-parser
npm http 200 http://192.168.1.100:4873/socket.io-adapter
npm http 200 http://192.168.1.100:4873/engine.io
npm http 200 http://192.168.1.100:4873/socket.io-client
npm http 200 http://192.168.1.100:4873/has-binary-data
npm http request GET http://192.168.1.100:4873/base64id
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/ws
npm http 200 http://192.168.1.100:4873/base64id
npm http 200 http://192.168.1.100:4873/engine.io-parser
npm http 200 http://192.168.1.100:4873/ws
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/has-binary
npm http request GET http://192.168.1.100:4873/utf8
npm http 200 http://192.168.1.100:4873/arraybuffer.slice
npm http 200 http://192.168.1.100:4873/after
npm http 200 http://192.168.1.100:4873/blob
npm http 200 http://192.168.1.100:4873/has-binary
npm http 200 http://192.168.1.100:4873/base64-arraybuffer
npm http 200 http://192.168.1.100:4873/utf8
npm http request GET http://192.168.1.100:4873/options
npm http request GET http://192.168.1.100:4873/ultron
npm http request GET http://192.168.1.100:4873/bufferutil
npm http request GET http://192.168.1.100:4873/utf-8-validate
npm http 200 http://192.168.1.100:4873/ultron
npm http 200 http://192.168.1.100:4873/options
npm http 200 http://192.168.1.100:4873/bufferutil
npm http 200 http://192.168.1.100:4873/utf-8-validate
npm http request GET http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/nan
npm http 200 http://192.168.1.100:4873/nan
npm http 200 http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/component-emitter
npm http request GET http://192.168.1.100:4873/json3
npm http request GET http://192.168.1.100:4873/benchmark
npm http 200 http://192.168.1.100:4873/component-emitter
npm http 200 http://192.168.1.100:4873/json3
npm http 200 http://192.168.1.100:4873/benchmark
npm http request GET http://192.168.1.100:4873/object-component
npm http request GET http://192.168.1.100:4873/component-bind
npm http request GET http://192.168.1.100:4873/indexof
npm http request GET http://192.168.1.100:4873/parseuri
npm http request GET http://192.168.1.100:4873/engine.io-client
npm http request GET http://192.168.1.100:4873/to-array
npm http request GET http://192.168.1.100:4873/backo2
npm http 200 http://192.168.1.100:4873/component-bind
npm http 200 http://192.168.1.100:4873/indexof
npm http 200 http://192.168.1.100:4873/parseuri
npm http 200 http://192.168.1.100:4873/object-component
npm http 200 http://192.168.1.100:4873/engine.io-client
npm http 200 http://192.168.1.100:4873/backo2
npm http 200 http://192.168.1.100:4873/to-array
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/parseqs
npm http fetch GET https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http 200 http://192.168.1.100:4873/parseqs
npm http 200 http://192.168.1.100:4873/component-inherit
npm http 200 http://192.168.1.100:4873/parsejson
npm http 200 http://192.168.1.100:4873/has-cors
npm http fetch 200 https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http fetch GET https://github.com/component/global/archive/v2.0.1.tar.gz
npm http fetch 200 https://github.com/component/global/archive/v2.0.1.tar.gz
npm http request GET http://192.168.1.100:4873/better-assert
npm http 200 http://192.168.1.100:4873/better-assert
npm http request GET http://192.168.1.100:4873/callsite
npm http 200 http://192.168.1.100:4873/callsite
npm http request GET http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/cycle
npm http request GET http://192.168.1.100:4873/colors
npm http request GET http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/pkginfo
npm http request GET http://192.168.1.100:4873/stack-trace
npm http 200 http://192.168.1.100:4873/eyes
npm http 200 http://192.168.1.100:4873/cycle
npm http 200 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/colors
npm http 200 http://192.168.1.100:4873/async
npm http 200 http://192.168.1.100:4873/pkginfo
npm http 200 http://192.168.1.100:4873/stack-trace
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/tape
npm http 200 http://192.168.1.100:4873/node-uuid
npm http 200 http://192.168.1.100:4873/tape
npm http request GET http://192.168.1.100:4873/deep-equal
npm http request GET http://192.168.1.100:4873/jsonify
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
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/forever-agent
npm http request GET http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/javascript-state-machine
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/salti
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/lie
npm http 200 http://192.168.1.100:4873/forever-agent
npm http 200 http://192.168.1.100:4873/ip
npm http 200 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/javascript-state-machine
npm http 200 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/salti
npm http 200 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/depd
npm http 200 http://192.168.1.100:4873/bytes
npm http 200 http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/ms
npm http 200 http://192.168.1.100:4873/ms
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
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 200 http://192.168.1.100:4873/methods
npm http 200 http://192.168.1.100:4873/path-to-regexp
npm http 200 http://192.168.1.100:4873/proxy-addr
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
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 304 http://192.168.1.100:4873/es3ify
npm http 304 http://192.168.1.100:4873/immediate
npm http 304 http://192.168.1.100:4873/inline-process-browser
npm http 304 http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/through
npm http 304 http://192.168.1.100:4873/through
npm http 304 http://192.168.1.100:4873/esprima
npm http 200 http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/base62
npm http 304 http://192.168.1.100:4873/commoner
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/detective
npm http 304 http://192.168.1.100:4873/private
npm http 304 http://192.168.1.100:4873/q
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http 304 http://192.168.1.100:4873/recast
npm http 200 http://192.168.1.100:4873/commander
npm http 200 http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/mkdirp
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
npm http 304 http://192.168.1.100:4873/minimatch
npm http 200 http://192.168.1.100:4873/inflight
npm http 304 http://192.168.1.100:4873/once
npm http 200 http://192.168.1.100:4873/path-is-absolute
npm http request GET http://192.168.1.100:4873/wrappy
npm http 304 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 304 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/minimist
npm http 200 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/ast-types
npm http 304 http://192.168.1.100:4873/ast-types
npm http request GET http://192.168.1.100:4873/amdefine
npm http 200 http://192.168.1.100:4873/amdefine
npm http request GET http://192.168.1.100:4873/falafel
npm http request GET http://192.168.1.100:4873/through2
npm http 304 http://192.168.1.100:4873/falafel
npm http 304 http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/foreach
npm http 304 http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/core-util-is
npm http request GET http://192.168.1.100:4873/string_decoder
npm http 304 http://192.168.1.100:4873/core-util-is
npm http 304 http://192.168.1.100:4873/string_decoder
npm http request GET http://192.168.1.100:4873/esmangle-evaluator
npm http 304 http://192.168.1.100:4873/esmangle-evaluator
npm http request GET http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/duplexify
npm http 200 http://192.168.1.100:4873/duplexify
npm http 200 http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/stream-shift
npm http 200 http://192.168.1.100:4873/end-of-stream
npm http 200 http://192.168.1.100:4873/stream-shift
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http 200 http://192.168.1.100:4873/process-nextick-args
npm http 200 http://192.168.1.100:4873/util-deprecate
npm http 200 http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/har-validator
npm http 200 http://192.168.1.100:4873/json-stringify-safe
npm http 200 http://192.168.1.100:4873/oauth-sign
npm http 200 http://192.168.1.100:4873/form-data
npm http 200 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/caseless
npm http 200 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/http-signature
npm http 200 http://192.168.1.100:4873/tunnel-agent
npm http 200 http://192.168.1.100:4873/bl
npm http 200 http://192.168.1.100:4873/stringstream
npm http 200 http://192.168.1.100:4873/combined-stream
npm http 200 http://192.168.1.100:4873/aws-sign2
npm http 200 http://192.168.1.100:4873/har-validator
npm http 200 http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 200 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http 304 http://192.168.1.100:4873/bluebird
npm http 200 http://192.168.1.100:4873/chalk
npm http 200 http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 200 http://192.168.1.100:4873/has-ansi
npm http 200 http://192.168.1.100:4873/escape-string-regexp
npm http 200 http://192.168.1.100:4873/ansi-styles
npm http 200 http://192.168.1.100:4873/strip-ansi
npm http 200 http://192.168.1.100:4873/supports-color
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 200 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http request GET http://192.168.1.100:4873/generate-function
npm http 200 http://192.168.1.100:4873/generate-function
npm http 200 http://192.168.1.100:4873/jsonpointer
npm http 200 http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/is-property
npm http 200 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/boom
npm http 200 http://192.168.1.100:4873/sntp
npm http 200 http://192.168.1.100:4873/boom
npm http 200 http://192.168.1.100:4873/hoek
npm http 200 http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/ctype
npm http 200 http://192.168.1.100:4873/asn1
npm http 200 http://192.168.1.100:4873/assert-plus
npm http 200 http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/colors
npm http request GET http://192.168.1.100:4873/cycle
npm http request GET http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/pkginfo
npm http request GET http://192.168.1.100:4873/stack-trace
npm http 304 http://192.168.1.100:4873/colors
npm http 304 http://192.168.1.100:4873/pkginfo
npm http 304 http://192.168.1.100:4873/cycle
npm http 304 http://192.168.1.100:4873/eyes
npm http 200 http://192.168.1.100:4873/stack-trace
npm http request GET http://192.168.1.100:4873/jsdoc
npm http 200 http://192.168.1.100:4873/jsdoc
npm http request GET http://192.168.1.100:4873/js2xmlparser
npm http request GET http://192.168.1.100:4873/catharsis
npm http request GET http://192.168.1.100:4873/marked
npm http request GET http://192.168.1.100:4873/requizzle
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/underscore
npm http request GET http://192.168.1.100:4873/wrench
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 200 http://192.168.1.100:4873/js2xmlparser
npm http 200 http://192.168.1.100:4873/strip-json-comments
npm http 200 http://192.168.1.100:4873/marked
npm http 200 http://192.168.1.100:4873/catharsis
npm http 200 http://192.168.1.100:4873/requizzle
npm http 200 http://192.168.1.100:4873/underscore
npm http 200 http://192.168.1.100:4873/wrench
npm WARN deprecated wrench@1.5.9: wrench.js is deprecated! You should check out fs-extra (https://github.com/jprichardson/node-fs-extra) for any operations you were using wrench for. Thanks for all the usage over the years.
npm http fetch 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http request GET http://192.168.1.100:4873/underscore-contrib
npm http 200 http://192.168.1.100:4873/underscore-contrib
npm WARN prefer global marked@0.3.6 should be installed with -g
npm http request GET http://192.168.1.100:4873/fs-extra-promise
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/jxc
npm http request GET http://192.168.1.100:4873/unzip
npm http 304 http://192.168.1.100:4873/lie
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/fs-extra-promise
npm http 200 http://192.168.1.100:4873/unzip
npm http 200 http://192.168.1.100:4873/jxc
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
npm http 304 http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/fs.realpath
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/fs.realpath
npm http 304 http://192.168.1.100:4873/inflight
npm http 304 http://192.168.1.100:4873/minimatch
npm http 304 http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/inherits
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
npm http 200 http://192.168.1.100:4873/adm-zip
npm http 200 http://192.168.1.100:4873/progress
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 304 http://192.168.1.100:4873/es3ify
npm http 304 http://192.168.1.100:4873/immediate
npm http 304 http://192.168.1.100:4873/inline-process-browser
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
npm http 304 http://192.168.1.100:4873/base62
npm http 304 http://192.168.1.100:4873/commoner
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/commander
npm http 304 http://192.168.1.100:4873/detective
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/q
npm http 304 http://192.168.1.100:4873/mkdirp
npm http 304 http://192.168.1.100:4873/private
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
npm http 304 http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/foreach
npm http 304 http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/core-util-is
npm http request GET http://192.168.1.100:4873/string_decoder
npm http 304 http://192.168.1.100:4873/core-util-is
npm http 304 http://192.168.1.100:4873/string_decoder
npm http request GET http://192.168.1.100:4873/esmangle-evaluator
npm http 304 http://192.168.1.100:4873/esmangle-evaluator
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/bl
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
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 200 http://192.168.1.100:4873/forever-agent
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/isstream
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
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/ansi-styles
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http 304 http://192.168.1.100:4873/supports-color
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-function
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/boom
npm http 304 http://192.168.1.100:4873/hoek
npm http 304 http://192.168.1.100:4873/cryptiles
npm http 304 http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/boom
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
npm http 200 http://192.168.1.100:4873/binary
npm http 200 http://192.168.1.100:4873/setimmediate
npm http 200 http://192.168.1.100:4873/fstream
npm http 200 http://192.168.1.100:4873/pullstream
npm http 200 http://192.168.1.100:4873/match-stream
npm http request GET http://192.168.1.100:4873/chainsaw
npm http request GET http://192.168.1.100:4873/buffers
npm http 200 http://192.168.1.100:4873/buffers
npm http 200 http://192.168.1.100:4873/chainsaw
npm http request GET http://192.168.1.100:4873/traverse
npm http 200 http://192.168.1.100:4873/traverse
npm http fetch GET http://192.168.1.100:4873/graceful-fs/-/graceful-fs-3.0.9.tgz
npm http fetch 200 http://192.168.1.100:4873/graceful-fs/-/graceful-fs-3.0.9.tgz
npm http request GET http://192.168.1.100:4873/slice-stream
npm http request GET http://192.168.1.100:4873/over
npm http 200 http://192.168.1.100:4873/over
npm http 200 http://192.168.1.100:4873/slice-stream
npm WARN EPACKAGEJSON install@0.0.1 No repository field.
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/bn.js
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/forever-agent
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/express-pouchdb
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/leveldown-mobile
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/nock
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/proxyquire
npm http request GET http://192.168.1.100:4873/tape
npm http request GET http://192.168.1.100:4873/pouchdb-node
npm http request GET http://192.168.1.100:4873/supertest
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/sinon
npm http request GET http://192.168.1.100:4873/supertest-as-promised
npm http request GET http://192.168.1.100:4873/request-promise
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/tmp
npm http request GET http://192.168.1.100:4873/tape-catch
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/forever-agent
npm http 304 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 200 http://192.168.1.100:4873/bn.js
npm http 304 http://192.168.1.100:4873/inherits
npm http 200 http://192.168.1.100:4873/is-property
npm http 200 http://192.168.1.100:4873/js-extend
npm http 200 http://192.168.1.100:4873/express-pouchdb
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 200 http://192.168.1.100:4873/randomstring
npm http 304 http://192.168.1.100:4873/socket.io-client
npm http 304 http://192.168.1.100:4873/leveldown-mobile
npm http 200 http://192.168.1.100:4873/proxyquire
npm http 304 http://192.168.1.100:4873/tape
npm http 304 http://192.168.1.100:4873/pouchdb-node
npm http 200 http://192.168.1.100:4873/nock
npm http 304 http://192.168.1.100:4873/multiplex
npm http 200 http://192.168.1.100:4873/supertest
npm http 200 http://192.168.1.100:4873/supertest-as-promised
npm http 200 http://192.168.1.100:4873/long
npm http 200 http://192.168.1.100:4873/request-promise
npm http 200 http://192.168.1.100:4873/sinon
npm http 200 http://192.168.1.100:4873/uuid
npm http 304 http://192.168.1.100:4873/tmp
npm http 200 http://192.168.1.100:4873/tape-catch
npm http 304 http://192.168.1.100:4873/urlsafe-base64
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
npm http 304 http://192.168.1.100:4873/http-errors
npm http 200 http://192.168.1.100:4873/bytes
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/content-type
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
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/serve-static
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
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/compression
npm http request GET http://192.168.1.100:4873/basic-auth
npm http request GET http://192.168.1.100:4873/header-case-normalizer
npm http request GET http://192.168.1.100:4873/cookie-parser
npm http request GET http://192.168.1.100:4873/multiparty
npm http request GET http://192.168.1.100:4873/pouchdb-all-dbs
npm http request GET http://192.168.1.100:4873/pouchdb-list
npm http request GET http://192.168.1.100:4873/pouchdb-find
npm http request GET http://192.168.1.100:4873/pouchdb-rewrite
npm http request GET http://192.168.1.100:4873/pouchdb-replicator
npm http request GET http://192.168.1.100:4873/pouchdb-security
npm http request GET http://192.168.1.100:4873/pouchdb-show
npm http request GET http://192.168.1.100:4873/pouchdb-auth
npm http request GET http://192.168.1.100:4873/pouchdb-size
npm http request GET http://192.168.1.100:4873/pouchdb-update
npm http request GET http://192.168.1.100:4873/pouchdb-validation
npm http request GET http://192.168.1.100:4873/pouchdb-vhost
npm http request GET http://192.168.1.100:4873/pouchdb-wrappers
npm http 304 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/cookie-parser
npm http 200 http://192.168.1.100:4873/basic-auth
npm http 200 http://192.168.1.100:4873/compression
npm http 200 http://192.168.1.100:4873/multiparty
npm http 200 http://192.168.1.100:4873/pouchdb-find
npm http 200 http://192.168.1.100:4873/header-case-normalizer
npm http 200 http://192.168.1.100:4873/pouchdb-all-dbs
npm http 200 http://192.168.1.100:4873/pouchdb-security
npm http 200 http://192.168.1.100:4873/pouchdb-rewrite
npm http 200 http://192.168.1.100:4873/pouchdb-replicator
npm http 200 http://192.168.1.100:4873/pouchdb-list
npm http 200 http://192.168.1.100:4873/pouchdb-size
npm http 200 http://192.168.1.100:4873/pouchdb-auth
npm http 200 http://192.168.1.100:4873/pouchdb-update
npm http 200 http://192.168.1.100:4873/pouchdb-validation
npm http 200 http://192.168.1.100:4873/pouchdb-vhost
npm http 200 http://192.168.1.100:4873/pouchdb-wrappers
npm http 200 http://192.168.1.100:4873/pouchdb-show
npm http request GET http://192.168.1.100:4873/setprototypeof
npm http 200 http://192.168.1.100:4873/setprototypeof
npm http request GET http://192.168.1.100:4873/on-headers
npm http request GET http://192.168.1.100:4873/compressible
npm http 200 http://192.168.1.100:4873/compressible
npm http 200 http://192.168.1.100:4873/on-headers
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/stream-counter
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 200 http://192.168.1.100:4873/stream-counter
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/argsarray
npm http request GET http://192.168.1.100:4873/tiny-queue
npm http request GET http://192.168.1.100:4873/pouchdb-promise
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
npm http request GET http://192.168.1.100:4873/crypto-lite
npm http request GET http://192.168.1.100:4873/pouchdb-plugin-error
npm http request GET http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http request GET http://192.168.1.100:4873/pouchdb
npm http request GET http://192.168.1.100:4873/pouchdb-req-http-query
npm http request GET http://192.168.1.100:4873/pouchdb-system-db
npm http request GET http://192.168.1.100:4873/promise-nodify
npm http request GET http://192.168.1.100:4873/secure-random
npm http 200 http://192.168.1.100:4873/couchdb-calculate-session-id
npm http 200 http://192.168.1.100:4873/crypto-lite
npm http 200 http://192.168.1.100:4873/base64url
npm http 200 http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http 200 http://192.168.1.100:4873/pouchdb-plugin-error
npm http 200 http://192.168.1.100:4873/pouchdb-req-http-query
npm http 200 http://192.168.1.100:4873/promise-nodify
npm http 200 http://192.168.1.100:4873/pouchdb
npm http 200 http://192.168.1.100:4873/pouchdb-system-db
npm http 200 http://192.168.1.100:4873/secure-random
npm http request GET http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/meow
npm http 200 http://192.168.1.100:4873/concat-stream
npm http 200 http://192.168.1.100:4873/meow
npm http request GET http://192.168.1.100:4873/typedarray
npm http 200 http://192.168.1.100:4873/typedarray
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/camelcase-keys
npm http request GET http://192.168.1.100:4873/indent-string
npm http 304 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/camelcase-keys
npm http 200 http://192.168.1.100:4873/indent-string
npm http request GET http://192.168.1.100:4873/map-obj
npm http request GET http://192.168.1.100:4873/camelcase
npm http 200 http://192.168.1.100:4873/map-obj
npm http 200 http://192.168.1.100:4873/camelcase
npm http request GET http://192.168.1.100:4873/repeating
npm http request GET http://192.168.1.100:4873/get-stdin
npm http 200 http://192.168.1.100:4873/get-stdin
npm http 200 http://192.168.1.100:4873/repeating
npm http request GET http://192.168.1.100:4873/is-finite
npm http 200 http://192.168.1.100:4873/is-finite
npm http request GET http://192.168.1.100:4873/number-is-nan
npm http 200 http://192.168.1.100:4873/number-is-nan
npm http request GET http://192.168.1.100:4873/aproba
npm http 200 http://192.168.1.100:4873/aproba
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/pouchdb-collate
npm http request GET http://192.168.1.100:4873/scope-eval
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/vuvuzela
npm http request GET http://192.168.1.100:4873/memdown
npm http request GET http://192.168.1.100:4873/localstorage-down
npm http request GET http://192.168.1.100:4873/level-write-stream
npm http request GET http://192.168.1.100:4873/fruitdown
npm http request GET http://192.168.1.100:4873/es6-promise-pool
npm http request GET http://192.168.1.100:4873/levelup
npm http 200 http://192.168.1.100:4873/scope-eval
npm http 304 http://192.168.1.100:4873/through2
npm http 200 http://192.168.1.100:4873/sublevel-pouchdb
npm http 200 http://192.168.1.100:4873/pouchdb-collate
npm http 200 http://192.168.1.100:4873/vuvuzela
npm http 200 http://192.168.1.100:4873/double-ended-queue
npm http 200 http://192.168.1.100:4873/pouchdb-collections
npm http 200 http://192.168.1.100:4873/memdown
npm http 200 http://192.168.1.100:4873/level-write-stream
npm http 200 http://192.168.1.100:4873/spark-md5
npm http 200 http://192.168.1.100:4873/localstorage-down
npm http 200 http://192.168.1.100:4873/fruitdown
npm http 200 http://192.168.1.100:4873/es6-promise-pool
npm http 200 http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/d64
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http 200 http://192.168.1.100:4873/abstract-leveldown
npm http 200 http://192.168.1.100:4873/d64
npm http request GET http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/end-stream
npm http 200 http://192.168.1.100:4873/end-stream
npm http request GET http://192.168.1.100:4873/write-stream
npm http 200 http://192.168.1.100:4873/write-stream
npm http request GET http://192.168.1.100:4873/prr
npm http request GET http://192.168.1.100:4873/level-iterator-stream
npm http request GET http://192.168.1.100:4873/level-codec
npm http request GET http://192.168.1.100:4873/level-errors
npm http request GET http://192.168.1.100:4873/deferred-leveldown
npm http request GET http://192.168.1.100:4873/semver
npm http 200 http://192.168.1.100:4873/prr
npm http 200 http://192.168.1.100:4873/level-iterator-stream
npm http 200 http://192.168.1.100:4873/semver
npm http 200 http://192.168.1.100:4873/level-errors
npm http 200 http://192.168.1.100:4873/deferred-leveldown
npm http 200 http://192.168.1.100:4873/level-codec
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
npm http request GET http://192.168.1.100:4873/is-typedarray
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/aws4
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/har-validator
npm http 200 http://192.168.1.100:4873/is-typedarray
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 304 http://192.168.1.100:4873/qs
npm http 200 http://192.168.1.100:4873/aws4
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/extend
npm WARN deprecated tough-cookie@2.2.2: ReDoS vulnerability parsing Set-Cookie https://nodesecurity.io/advisories/130
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/readable-stream
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
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/pinkie-promise
npm http 304 http://192.168.1.100:4873/is-my-json-valid
npm http 200 http://192.168.1.100:4873/pinkie-promise
npm http 304 http://192.168.1.100:4873/chalk
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
npm http 304 http://192.168.1.100:4873/cryptiles
npm http 304 http://192.168.1.100:4873/hoek
npm http 304 http://192.168.1.100:4873/boom
npm http 304 http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/jsprim
npm http request GET http://192.168.1.100:4873/sshpk
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 200 http://192.168.1.100:4873/jsprim
npm http 200 http://192.168.1.100:4873/sshpk
npm http request GET http://192.168.1.100:4873/extsprintf
npm http request GET http://192.168.1.100:4873/json-schema
npm http request GET http://192.168.1.100:4873/verror
npm http 200 http://192.168.1.100:4873/extsprintf
npm http 200 http://192.168.1.100:4873/json-schema
npm http 200 http://192.168.1.100:4873/verror
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/getpass
npm http request GET http://192.168.1.100:4873/dashdash
npm http 200 http://192.168.1.100:4873/getpass
npm http 304 http://192.168.1.100:4873/asn1
npm http 200 http://192.168.1.100:4873/dashdash
npm http request GET http://192.168.1.100:4873/pull-stream
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
npm http 200 http://192.168.1.100:4873/xmlhttprequest-cookie
npm http request GET http://192.168.1.100:4873/xmlhttprequest
npm http 200 http://192.168.1.100:4873/xmlhttprequest
npm http request GET http://192.168.1.100:4873/pouchdb-changeslike-wrapper
npm http 200 http://192.168.1.100:4873/pouchdb-changeslike-wrapper
npm http request GET http://192.168.1.100:4873/couchdb-eval
npm http request GET http://192.168.1.100:4873/couchdb-objects
npm http request GET http://192.168.1.100:4873/random-uuid-v4
npm http 200 http://192.168.1.100:4873/couchdb-eval
npm http 200 http://192.168.1.100:4873/couchdb-objects
npm http 200 http://192.168.1.100:4873/random-uuid-v4
npm http request GET http://192.168.1.100:4873/is-empty
npm http 200 http://192.168.1.100:4873/is-empty
npm http request GET http://192.168.1.100:4873/is-array
npm http request GET http://192.168.1.100:4873/pouchdb-extend
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/pouchdb-upsert
npm http 304 http://192.168.1.100:4873/spark-md5
npm http 200 http://192.168.1.100:4873/is-array
npm http 200 http://192.168.1.100:4873/pouchdb-extend
npm http 200 http://192.168.1.100:4873/pouchdb-upsert
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 304 http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/couchdb-render
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
npm http request GET http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/fast-future
npm http 304 http://192.168.1.100:4873/bindings
npm http 304 http://192.168.1.100:4873/abstract-leveldown
npm http 200 http://192.168.1.100:4873/fast-future
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/varint
npm http 304 http://192.168.1.100:4873/duplexify
npm http 304 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/stream-shift
npm http 304 http://192.168.1.100:4873/stream-shift
npm http 304 http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http 304 http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/deep-equal
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/propagate
npm http request GET http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/chai
npm http 304 http://192.168.1.100:4873/deep-equal
npm http 304 http://192.168.1.100:4873/debug
npm http 200 http://192.168.1.100:4873/chai
npm http 200 http://192.168.1.100:4873/propagate
npm http 200 http://192.168.1.100:4873/lodash
npm WARN deprecated lodash@2.4.1: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
npm http request GET http://192.168.1.100:4873/assertion-error
npm http request GET http://192.168.1.100:4873/type-detect
npm http request GET http://192.168.1.100:4873/deep-eql
npm http 200 http://192.168.1.100:4873/assertion-error
npm http 200 http://192.168.1.100:4873/type-detect
npm http 200 http://192.168.1.100:4873/deep-eql
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/ip
npm http 304 http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/pouchdb-replication
npm http request GET http://192.168.1.100:4873/pouchdb-core
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-leveldb
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-http
npm http request GET http://192.168.1.100:4873/pouchdb-mapreduce
npm http 304 http://192.168.1.100:4873/pouchdb-mapreduce
npm http 304 http://192.168.1.100:4873/pouchdb-replication
npm http 304 http://192.168.1.100:4873/pouchdb-core
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-leveldb
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-http
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/pouchdb-ajax
npm http request GET http://192.168.1.100:4873/pouchdb-md5
npm http request GET http://192.168.1.100:4873/pouchdb-errors
npm http request GET http://192.168.1.100:4873/pouchdb-binary-utils
npm http request GET http://192.168.1.100:4873/pouchdb-utils
npm http 304 http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/pouchdb-ajax
npm http 304 http://192.168.1.100:4873/pouchdb-md5
npm http 304 http://192.168.1.100:4873/pouchdb-utils
npm http 304 http://192.168.1.100:4873/pouchdb-binary-utils
npm http 304 http://192.168.1.100:4873/pouchdb-errors
npm http request GET http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http 304 http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-leveldb-core
npm http request GET http://192.168.1.100:4873/leveldown
npm http 200 http://192.168.1.100:4873/leveldown
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-leveldb-core
npm http request GET http://192.168.1.100:4873/nan
npm http request GET http://192.168.1.100:4873/prebuild
npm http 304 http://192.168.1.100:4873/nan
npm http 200 http://192.168.1.100:4873/prebuild
npm http request GET http://192.168.1.100:4873/expand-template
npm http request GET http://192.168.1.100:4873/ghreleases
npm http request GET http://192.168.1.100:4873/github-from-package
npm http request GET http://192.168.1.100:4873/rc
npm http request GET http://192.168.1.100:4873/node-gyp
npm http request GET http://192.168.1.100:4873/simple-get
npm http request GET http://192.168.1.100:4873/os-homedir
npm http request GET http://192.168.1.100:4873/npmlog
npm http request GET http://192.168.1.100:4873/pump
npm http request GET http://192.168.1.100:4873/noop-logger
npm http request GET http://192.168.1.100:4873/node-ninja
npm http request GET http://192.168.1.100:4873/tar-fs
npm http request GET http://192.168.1.100:4873/tar-stream
npm http 200 http://192.168.1.100:4873/rc
npm http 200 http://192.168.1.100:4873/node-gyp
npm http 200 http://192.168.1.100:4873/expand-template
npm http 200 http://192.168.1.100:4873/os-homedir
npm http 200 http://192.168.1.100:4873/ghreleases
npm http 200 http://192.168.1.100:4873/npmlog
npm http 200 http://192.168.1.100:4873/pump
npm http 200 http://192.168.1.100:4873/tar-fs
npm http 200 http://192.168.1.100:4873/noop-logger
npm http 200 http://192.168.1.100:4873/simple-get
npm http 200 http://192.168.1.100:4873/tar-stream
npm http 200 http://192.168.1.100:4873/github-from-package
npm http 200 http://192.168.1.100:4873/node-ninja
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/simple-mime
npm http request GET http://192.168.1.100:4873/ghutils
npm http request GET http://192.168.1.100:4873/ghrepos
npm http request GET http://192.168.1.100:4873/url-template
npm http 304 http://192.168.1.100:4873/after
npm http fetch GET http://192.168.1.100:4873/after/-/after-0.8.2.tgz
npm http 200 http://192.168.1.100:4873/ghrepos
npm http 200 http://192.168.1.100:4873/simple-mime
npm http fetch 200 http://192.168.1.100:4873/after/-/after-0.8.2.tgz
npm http 200 http://192.168.1.100:4873/url-template
npm http 200 http://192.168.1.100:4873/ghutils
npm http request GET http://192.168.1.100:4873/jsonist
npm http 200 http://192.168.1.100:4873/jsonist
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/hyperquest
npm http 304 http://192.168.1.100:4873/bl
npm http 200 http://192.168.1.100:4873/hyperquest
npm http request GET http://192.168.1.100:4873/duplexer2
npm http 200 http://192.168.1.100:4873/duplexer2
npm http request GET http://192.168.1.100:4873/fstream
npm http request GET http://192.168.1.100:4873/nopt
npm http request GET http://192.168.1.100:4873/osenv
npm http request GET http://192.168.1.100:4873/tar
npm http request GET http://192.168.1.100:4873/path-array
npm http request GET http://192.168.1.100:4873/which
npm http 304 http://192.168.1.100:4873/fstream
npm http 200 http://192.168.1.100:4873/osenv
npm http 200 http://192.168.1.100:4873/path-array
npm http 200 http://192.168.1.100:4873/tar
npm http 200 http://192.168.1.100:4873/nopt
npm http 200 http://192.168.1.100:4873/which
npm http request GET http://192.168.1.100:4873/abbrev
npm http 200 http://192.168.1.100:4873/abbrev
npm http request GET http://192.168.1.100:4873/are-we-there-yet
npm http request GET http://192.168.1.100:4873/ansi
npm http request GET http://192.168.1.100:4873/gauge
npm http 200 http://192.168.1.100:4873/are-we-there-yet
npm http 200 http://192.168.1.100:4873/gauge
npm http 200 http://192.168.1.100:4873/ansi
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/delegates
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 200 http://192.168.1.100:4873/delegates
npm http request GET http://192.168.1.100:4873/has-unicode
npm http request GET http://192.168.1.100:4873/lodash.padend
npm http request GET http://192.168.1.100:4873/lodash.pad
npm http request GET http://192.168.1.100:4873/lodash.padstart
npm http 200 http://192.168.1.100:4873/has-unicode
npm http 200 http://192.168.1.100:4873/lodash.padend
npm http 200 http://192.168.1.100:4873/lodash.pad
npm http 200 http://192.168.1.100:4873/lodash.padstart
npm http fetch GET http://192.168.1.100:4873/lodash.padend/-/lodash.padend-4.6.1.tgz
npm http fetch 200 http://192.168.1.100:4873/lodash.padend/-/lodash.padend-4.6.1.tgz
npm http fetch GET http://192.168.1.100:4873/lodash.pad/-/lodash.pad-4.5.1.tgz
npm http fetch GET http://192.168.1.100:4873/lodash.padstart/-/lodash.padstart-4.6.1.tgz
npm http fetch 200 http://192.168.1.100:4873/lodash.pad/-/lodash.pad-4.5.1.tgz
npm http fetch 200 http://192.168.1.100:4873/lodash.padstart/-/lodash.padstart-4.6.1.tgz
npm http request GET http://192.168.1.100:4873/os-tmpdir
npm http 200 http://192.168.1.100:4873/os-tmpdir
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
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/http-signature
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
npm http 200 http://192.168.1.100:4873/block-stream
npm http request GET http://192.168.1.100:4873/isexe
npm http 200 http://192.168.1.100:4873/isexe
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http 304 http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/ini
npm http request GET http://192.168.1.100:4873/deep-extend
npm http 304 http://192.168.1.100:4873/strip-json-comments
npm http 200 http://192.168.1.100:4873/ini
npm http 200 http://192.168.1.100:4873/deep-extend
npm WARN engine deep-extend@0.4.1: wanted: {"node":">=0.12.0","iojs":">=1.0.0"} (current: {"node":"0.10.40","npm":"3.3.12"})
npm http request GET http://192.168.1.100:4873/unzip-response
npm http 200 http://192.168.1.100:4873/unzip-response
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-utils
npm http request GET http://192.168.1.100:4873/pouchdb-merge
npm http request GET http://192.168.1.100:4873/pouchdb-json
npm http 304 http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/sublevel-pouchdb
npm http 304 http://192.168.1.100:4873/pouchdb-collections
npm http 304 http://192.168.1.100:4873/pouchdb-merge
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-utils
npm http 304 http://192.168.1.100:4873/pouchdb-json
npm http request GET http://192.168.1.100:4873/ltgt
npm http 304 http://192.168.1.100:4873/ltgt
npm http request GET http://192.168.1.100:4873/pouchdb-mapreduce-utils
npm http 304 http://192.168.1.100:4873/pouchdb-mapreduce-utils
npm http request GET http://192.168.1.100:4873/pouchdb-checkpointer
npm http request GET http://192.168.1.100:4873/pouchdb-generate-replication-id
npm http 304 http://192.168.1.100:4873/pouchdb-generate-replication-id
npm http 304 http://192.168.1.100:4873/pouchdb-checkpointer
npm http request GET http://192.168.1.100:4873/module-not-found-error
npm http request GET http://192.168.1.100:4873/fill-keys
npm http 200 http://192.168.1.100:4873/module-not-found-error
npm http 200 http://192.168.1.100:4873/fill-keys
npm http request GET http://192.168.1.100:4873/is-object
npm http 200 http://192.168.1.100:4873/is-object
npm http request GET http://192.168.1.100:4873/array-uniq
npm http 200 http://192.168.1.100:4873/array-uniq
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/samsam
npm http request GET http://192.168.1.100:4873/util
npm http request GET http://192.168.1.100:4873/lolex
npm http request GET http://192.168.1.100:4873/formatio
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
npm http request GET http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/component-emitter
npm http 304 http://192.168.1.100:4873/socket.io-parser
npm http 304 http://192.168.1.100:4873/component-bind
npm http 304 http://192.168.1.100:4873/engine.io-client
npm http 304 http://192.168.1.100:4873/object-component
npm http 304 http://192.168.1.100:4873/has-binary
npm http 304 http://192.168.1.100:4873/to-array
npm http 304 http://192.168.1.100:4873/indexof
npm http 304 http://192.168.1.100:4873/parseuri
npm http 304 http://192.168.1.100:4873/backo2
npm http 304 http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/parseqs
npm http request GET http://192.168.1.100:4873/ws
npm http fetch GET https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http 304 http://192.168.1.100:4873/component-inherit
npm http 304 http://192.168.1.100:4873/has-cors
npm http 304 http://192.168.1.100:4873/parseqs
npm http 304 http://192.168.1.100:4873/parsejson
npm http 304 http://192.168.1.100:4873/engine.io-parser
npm http 304 http://192.168.1.100:4873/ws
npm http fetch 200 https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/utf8
npm http request GET http://192.168.1.100:4873/after
npm http 304 http://192.168.1.100:4873/arraybuffer.slice
npm http 304 http://192.168.1.100:4873/blob
npm http 304 http://192.168.1.100:4873/base64-arraybuffer
npm http 304 http://192.168.1.100:4873/utf8
npm http 200 http://192.168.1.100:4873/after
npm http fetch GET http://192.168.1.100:4873/after/-/after-0.8.1.tgz
npm http fetch 200 http://192.168.1.100:4873/after/-/after-0.8.1.tgz
npm http fetch GET https://github.com/component/global/archive/v2.0.1.tar.gz
npm http fetch 200 https://github.com/component/global/archive/v2.0.1.tar.gz
npm http request GET http://192.168.1.100:4873/better-assert
npm http 304 http://192.168.1.100:4873/better-assert
npm http request GET http://192.168.1.100:4873/callsite
npm http 304 http://192.168.1.100:4873/callsite
npm http request GET http://192.168.1.100:4873/options
npm http request GET http://192.168.1.100:4873/ultron
npm http 304 http://192.168.1.100:4873/options
npm http 200 http://192.168.1.100:4873/ultron
npm http request GET http://192.168.1.100:4873/json3
npm http request GET http://192.168.1.100:4873/benchmark
npm http 304 http://192.168.1.100:4873/json3
npm http 304 http://192.168.1.100:4873/benchmark
npm http request GET http://192.168.1.100:4873/superagent
npm http 200 http://192.168.1.100:4873/superagent
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/reduce-component
npm http request GET http://192.168.1.100:4873/cookiejar
npm http request GET http://192.168.1.100:4873/formidable
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 200 http://192.168.1.100:4873/cookiejar
npm http 200 http://192.168.1.100:4873/reduce-component
npm http 200 http://192.168.1.100:4873/formidable
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/combined-stream
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
npm http 200 http://192.168.1.100:4873/object-inspect
npm http 200 http://192.168.1.100:4873/resumer
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
