#### Test (Fail) 80768856 Build Logs


```


```

```
Already up-to-date.

From https://github.com/thaliproject/Thali_CordovaPlugin
   3b560df..b4e5040  vNext_artemjackson_697 -> origin/vNext_artemjackson_697

```

```
Your branch is up-to-date with 'origin/master'.
Branch vNext_yarong_780 set up to track remote branch vNext_yarong_780 from origin.
Already up-to-date.

Already on 'master'
Switched to a new branch 'vNext_yarong_780'
Note: checking out 'b4e5040'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at b4e5040... Fixed function names for more convenient

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
DEBUG createNativeListener: listening 49853
ok 1 Should throw
# teardown
# setup
# emits incomingConnectionState
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49855
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
DEBUG createNativeListener: listening 49858
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
DEBUG createNativeListener: listening 49862
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
DEBUG createNativeListener: listening 49867
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
DEBUG createNativeListener: listening 49871
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
DEBUG createNativeListener: listening 49875
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
DEBUG createNativeListener: listening 49879
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
DEBUG createNativeListener: listening 49883
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
DEBUG createNativeListener: listening 49935
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
DEBUG createNativeListener: listening 49939
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
DEBUG createNativeListener: listening 49944
# teardown
# setup
# calling createPeerListener after calling stop produces error
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49947
# teardown
# setup
# can call createPeerListener (pleaseConnect === false)
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49950
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
ok 45 port must be in range
# teardown
# setup
# calling createPeerListener (pleaseConnect === true) with unknown peer is error
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49954
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
DEBUG createNativeListener: listening 49959
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
ok 47 port values should be the same
# teardown
# setup
# createPeerListener - closing connection to native listener closes everything and triggers new listener
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49963
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
DEBUG createNativeListener: listening 49972
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
DEBUG createNativeListener: listening 49981
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
DEBUG createNativeListener: listening 49987
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
DEBUG createNativeListener: listening 49994
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
DEBUG createNativeListener: listening 49999
DEBUG createPeerListener: pleaseConnect= false
ok 68 peerPort != nativePort
DEBUG createPeerListener: first connection
DEBUG createPeerListener: forward connection
ok 69 Should not get unexpected connection
# teardown
# setup
# peerListener - forwardConnection, pleaseConnect === false - with native server and data transfer
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50005
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
DEBUG createNativeListener: listening 50012
DEBUG createPeerListener: pleaseConnect= false
ok 74 Second call to existing peerListener returns existing port
# teardown
# setup
# createPeerListener - pleaseConnect === true, failed connection rejects promise
DEBUG createNativeListener: creating native server
ok 75 Can call startUpdateAdvertisingAndListening without error
ok 76 Can call startListeningForAdvertisements without error
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createNativeListener: listening 50016
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
DEBUG createNativeListener: listening 50021
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
DEBUG createNativeListener: listening 50026
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
DEBUG createNativeListener: listening 50031
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
DEBUG createNativeListener: listening 50037
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: first connection
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createPeerListener: looking up mux for client port:  50040
DEBUG createPeerListener: reverse connection
DEBUG createPeerListener: looking up mux for client port:  50040
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
DEBUG createNativeListener: listening 50043
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: first connection
DEBUG createPeerListener: looking up mux for client port:  50046
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createPeerListener: reverse connection
DEBUG createPeerListener: looking up mux for client port:  50046
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
DEBUG createNativeListener: listening 50050
# teardown
# setup
# createPeerListener - ask for a new peer when we are not at maximum peers and make sure we do not remove any existing listeners
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50053
# teardown
# setup
# createPeerListener - pleaseConnect = false - test timeout
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50056
# teardown
# setup
# createPeerListener - pleaseConnect = true - test timeout
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50059
# teardown
# setup
# createPeerListener - forward connection - wrong serverPort
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50062
# teardown
# setup
# createPeerListener - forward connection - wrong clientPort
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50065
# teardown
# setup
# createPeerListener - please connect = false, multiple connections out
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50068
# teardown
# setup
# createPeerListener - please connect = false, multiple bi-directional connections
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50071
# teardown
# setup
# createPeerListener - multiple parallel calls
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50074
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
DEBUG createNativeListener: listening 50151
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
DEBUG createNativeListener: listening 50153
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
DEBUG createNativeListener: listening 50155
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
DEBUG createNativeListener: listening 50160
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
DEBUG createNativeListener: listening 50162
ok 192 first call should succeed
ok 193 first call should succeed
ok 194 specific error should be returned
# teardown
ok 195 error should be null
ok 196 error should be null
# setup
# does not emit duplicate discoveryAdvertisingStateUpdate
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50164
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
DEBUG createNativeListener: listening 50169
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
DEBUG createNativeListener: listening 50171
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
DEBUG createNativeListener: listening 50176
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
DEBUG createNativeListener: listening 50178
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
DEBUG createNativeListener: listening 50184
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
DEBUG createNativeListener: listening 50186
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
DEBUG createNativeListener: listening 50188
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
DEBUG createNativeListener: listening 50192
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
DEBUG createNativeListener: listening 50194
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
DEBUG createNativeListener: listening 50202
INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":50201,"error":{}}
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
DEBUG createNativeListener: listening 50204
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
DEBUG createNativeListener: listening 50206
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG testUtils: We got a peer {"peerIdentifier":"foo","portNumber":50209,"hostAddress":"127.0.0.1"}
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
DEBUG createNativeListener: listening 50217
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
DEBUG createNativeListener: listening 50229
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
DEBUG createNativeListener: listening 50231
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: 50231
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
DEBUG createNativeListener: listening 50235
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 338 discoveryActive matches
ok 339 advertisingActive matches
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 340 discoveryActive matches
ok 341 advertisingActive matches
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50237
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 342 discoveryActive matches
ok 343 advertisingActive matches
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 344 discoveryActive matches
ok 345 advertisingActive matches
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50241
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
DEBUG createNativeListener: listening 50352
ok 690 port must be in range
# teardown
# setup
# starting twice resolves with listening port
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50353
ok 691 second start should return same port
# teardown
# setup
# terminateIncomingConnection will terminate a connection
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50355
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
DEBUG createNativeListener: listening 50357
# teardown
# setup
# terminate an Outgoing connection with wrong arguments is not harmful
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50358
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
Adding Thali Cordova plugin from: /var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/T/tmp-4535t4qxu8SxMW1x/TestApp/thaliDontCheckIn/Thali_CordovaPlugin-npmv2.1.0
Running jx npm install in: /var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/T/tmp-4535t4qxu8SxMW1x/TestApp/plugins/org.thaliproject.p2p/scripts
scripts@0.0.1 /private/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/T/tmp-4535t4qxu8SxMW1x/TestApp/plugins/org.thaliproject.p2p/scripts
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
npm http 200 http://192.168.1.100:4873/fs-extra-promise
npm http request GET http://192.168.1.100:4873/fs-extra
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/fs-extra
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http request GET http://192.168.1.100:4873/jsonfile
npm http request GET http://192.168.1.100:4873/rimraf
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http 304 http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/rimraf
npm http 200 http://192.168.1.100:4873/jsonfile
npm http request GET http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/fs.realpath
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/fs.realpath
npm http 304 http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/inflight
npm http 304 http://192.168.1.100:4873/inherits
npm http 200 http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/wrappy
npm http 304 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 304 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/concat-map
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
/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/T/tmp-4535t4qxu8SxMW1x
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

2016-08-10T13:13:39.395Z - info: Require 3 ios devices

2016-08-10T13:13:39.424Z - info: Require 0 android devices

2016-08-10T13:13:39.433Z - info: listening on *:3000

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
[33mMy device name is: 1f0fe313-c015-4773-bff6-8a2fb89a7056
[39m
[33mWARN testUtils: myNameCallback not set!
[39m
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
[32mMy device name is: 7a8e4c64-9460-4f1b-86a7-8929ff661cf1
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
[39m
[36mMy device name is: 964c1b4b-ccb7-459d-b34a-7c5d3cbf07bb
[39m
[36mWARN testUtils: myNameCallback not set!
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreateNativeListener.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreateNativeListener.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreateNativeListener.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPromiseQueue.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testTests.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNative.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotification.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationAction.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationBeacons.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationClient.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationLocal.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationServer.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPromiseQueue.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testTests.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerAction.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerDictionary.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
[39m
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
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliTcpServersManager.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
[39m
[33mConnected to the test server
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNative.js
[39m
2016-08-10T13:13:42.117Z - debug: Device presented: 1f0fe313-c015-4773-bff6-8a2fb89a7056 (a266af8d-3909-4155-a964-4854297c67cb) - ios dummy

[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPromiseQueue.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testTests.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotification.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationAction.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationBeacons.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationClient.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationLocal.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationServer.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerAction.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerDictionary.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
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
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNative.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotification.js
[39m
[32mConnected to the test server
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationAction.js
[39m
2016-08-10T13:13:42.222Z - debug: Device presented: 7a8e4c64-9460-4f1b-86a7-8929ff661cf1 (c151329e-6c29-47f2-94a1-0bcd6c746b9a) - ios dummy

[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationBeacons.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationClient.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationLocal.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationServer.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerAction.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerDictionary.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationUtilities.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliTcpServersManager.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
[39m
[36mConnected to the test server
[39m
2016-08-10T13:13:42.307Z - debug: Device presented: 964c1b4b-ccb7-459d-b34a-7c5d3cbf07bb (a5eaf94a-5576-4df5-97f3-297453e96205) - ios dummy

2016-08-10T13:13:42.307Z - info: All 3 ios devices are present

2016-08-10T13:13:42.308Z - info: Starting unit test run on 3 ios devices

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
2016-08-10T13:13:42.500Z - info: Running on ios test: 1. calling createNativeListener directly rejects

[33m# 1. calling createNativeListener directly rejects
[39m
[32m# 1. calling createNativeListener directly rejects
[39m
[36m# 1. calling createNativeListener directly rejects
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50401
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[33mok 1 Should throw
[39m
[32mDEBUG createNativeListener: listening 50402
[39m
[33m# teardown
[39m
[32mok 1 Should throw
# teardown
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: listening 50403
[39m
[36mok 1 Should throw
[39m
[36m# teardown
[39m
[33m# setup
[39m
[32m# setup
[39m
[36m# setup
[39m
2016-08-10T13:13:42.548Z - info: Running on ios test: 2. emits incomingConnectionState

[33m# 2. emits incomingConnectionState
[39m
[32m# 2. emits incomingConnectionState
[39m
[36m# 2. emits incomingConnectionState
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50407
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: listening 50408
[39m
[33mDEBUG createNativeListener: new incoming socket
[39m
[33mDEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[32mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
[39m
[33mok 2 initial connection state should be CONNECTED
[39m
[32mDEBUG createNativeListener: new mux
[39m
[32mok 2 initial connection state should be CONNECTED
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[33mok 3 final connection state should be DISCONNECTED
[39m
[33m# teardown
[39m
[32mDEBUG createNativeListener: incoming socket close
ok 3 final connection state should be DISCONNECTED
[39m
[32m# teardown
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: listening 50411
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[36mok 2 initial connection state should be CONNECTED
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[36mok 3 final connection state should be DISCONNECTED
[39m
[36m# teardown
[39m
[33m# setup
[39m
[32m# setup
[39m
[36m# setup
[39m
2016-08-10T13:13:42.624Z - info: Running on ios test: 3. emits routerPortConnectionFailed

[33m# 3. emits routerPortConnectionFailed
[39m
[32m# 3. emits routerPortConnectionFailed
[39m
[36m# 3. emits routerPortConnectionFailed
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50416
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: listening 50418
[39m
[32mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[33mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: 
ok 4 tried to connect to right port
ok 5 failed due to refused connection
ok 6 routerPortConnectionFailed is emitted
# teardown
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: listening 50421
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: 
[39m
[32mok 4 tried to connect to right port
ok 5 failed due to refused connection
ok 6 routerPortConnectionFailed is emitted
# teardown
DEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: 
[39m
[36mok 4 tried to connect to right port
[39m
[36mok 5 failed due to refused connection
ok 6 routerPortConnectionFailed is emitted
[39m
[36m# teardown
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createNativeListener: mux close
# setup
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createNativeListener: mux close
[39m
[36m# setup
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
2016-08-10T13:13:42.694Z - info: Running on ios test: 4. native server connections all up

[33m# 4. native server connections all up
[39m
[32m# 4. native server connections all up
[39m
[36m# 4. native server connections all up
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: listening 50428
[39m
[32mDEBUG createNativeListener: listening 50429
[39m
[33mDEBUG createNativeListener: new incoming socket
[39m
[33mDEBUG createNativeListener: creating incoming mux
[39m
[33mDEBUG createNativeListener: new mux
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mok 7 Send/recvd #1 should be equal length
ok 8 Send/recvd #1 should be same
ok 9 Send/recvd #2 should be equal length
ok 10 Send/recvd #2 should be same
ok 11 Should be exactly 2 client sockets
[39m
[32m# teardown
[39m
[33mok 7 Send/recvd #1 should be equal length
[39m
[33mok 8 Send/recvd #1 should be same
[39m
[33mok 9 Send/recvd #2 should be equal length
[39m
[33mok 10 Send/recvd #2 should be same
ok 11 Should be exactly 2 client sockets
[39m
[33m# teardown
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: listening 50436
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mok 7 Send/recvd #1 should be equal length
ok 8 Send/recvd #1 should be same
ok 9 Send/recvd #2 should be equal length
ok 10 Send/recvd #2 should be same
ok 11 Should be exactly 2 client sockets
[39m
[36m# teardown
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
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: mux close
[39m
[32m# setup
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: mux close
[39m
[36m# setup
DEBUG createNativeListener: incoming socket close
[39m
2016-08-10T13:13:42.868Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

[33m# 5. native server - closing incoming stream cleans outgoing socket
[39m
[32m# 5. native server - closing incoming stream cleans outgoing socket
[39m
[36m# 5. native server - closing incoming stream cleans outgoing socket
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: listening 50443
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: listening 50445
[39m
[33mDEBUG createNativeListener: creating incoming mux
[39m
[33mDEBUG createNativeListener: new mux
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: new mux
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[33mok 12 socket shouldn't close until after stream
[39m
[33mok 13 incoming remains open
[39m
[33m# teardown
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: listening 50449
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[32mok 12 socket shouldn't close until after stream
ok 13 incoming remains open
[39m
[36mDEBUG createNativeListener: new mux
[39m
[32m# teardown
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[36mok 12 socket shouldn't close until after stream
ok 13 incoming remains open
[39m
[36m# teardown
[39m
[33mDEBUG createNativeListener: mux close
[39m
[33m# setup
DEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createNativeListener: mux close
[39m
[32m# setup
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createNativeListener: mux close
[39m
[36m# setup
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
2016-08-10T13:13:42.921Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

[33m# 6. native server - closing incoming connection cleans outgoing socket
[39m
[32m# 6. native server - closing incoming connection cleans outgoing socket
[39m
[36m# 6. native server - closing incoming connection cleans outgoing socket
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: listening 50455
[39m
[33mDEBUG createNativeListener: new incoming socket
[39m
[33mDEBUG createNativeListener: creating incoming mux
[39m
[33mDEBUG createNativeListener: new mux
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: listening 50457
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
[32mDEBUG createNativeListener: new incoming socket
[39m
[33mok 15 socket shouldn't close until after incoming
[39m
[33mok 16 incoming is cleaned up
[39m
[33m# teardown
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[32mok 14 we should not have gotten an error
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createNativeListener: listening 50461
[39m
[32mok 15 socket shouldn't close until after incoming
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[32mok 16 incoming is cleaned up
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[32m# teardown
[39m
[36mDEBUG createNativeListener: new mux
[39m
[36mok 14 we should not have gotten an error
[39m
[36mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[36mok 15 socket shouldn't close until after incoming
[39m
[36mok 16 incoming is cleaned up
[39m
[36m# teardown
[39m
[33m# setup
[39m
[32m# setup
[39m
[36m# setup
[39m
2016-08-10T13:13:42.971Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

[33m# 7. native server - closing outgoing socket cleans associated mux stream
[39m
[32m# 7. native server - closing outgoing socket cleans associated mux stream
[39m
[36m# 7. native server - closing outgoing socket cleans associated mux stream
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50467
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: listening 50468
[39m
[33mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mok 17 stream was closed
ok 18 incoming should survive
ok 19 mux should have no streams
[39m
[33m# teardown
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: listening 50472
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[32mok 17 stream was closed
ok 18 incoming should survive
ok 19 mux should have no streams
[39m
[32m# teardown
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[36mok 17 stream was closed
[39m
[36mok 18 incoming should survive
ok 19 mux should have no streams
[39m
[36m# teardown
[39m
[33mDEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createNativeListener: mux close
[39m
[32m# setup
DEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
[39m
2016-08-10T13:13:43.020Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

[33m# 8. native server - closing the whole server cleans everything up
[39m
[32m# 8. native server - closing the whole server cleans everything up
[39m
[36m# 8. native server - closing the whole server cleans everything up
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50479
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50481
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50482
[39m
[33mDEBUG createNativeListener: new incoming socket
[39m
[33mDEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 20 we should not have gotten an error
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[33mok 21 Buffers are identical
[39m
[33mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
[39m
[33mok 22 native server is nulled out
ok 23 native server should be closed
[39m
[33mok 24 incoming has been removed
[39m
[33mok 25 Incoming should be done
[39m
[33mok 26 The mux object should be closed
ok 27 The mux stream should be closed
[39m
[33mDEBUG createNativeListener: incoming socket close
# teardown
[39m
[32mok 20 we should not have gotten an error
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mok 21 Buffers are identical
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: mux close
ok 22 native server is nulled out
ok 23 native server should be closed
ok 24 incoming has been removed
ok 25 Incoming should be done
ok 26 The mux object should be closed
ok 27 The mux stream should be closed
DEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[32m# teardown
[39m
[36mok 20 we should not have gotten an error
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
[36mok 22 native server is nulled out
ok 23 native server should be closed
[39m
[36mok 24 incoming has been removed
[39m
[36mok 25 Incoming should be done
ok 26 The mux object should be closed
[39m
[36mok 27 The mux stream should be closed
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[36m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T13:13:43.074Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

[33m# 9. native server - we can get a ton of connections and data through and still clean up the server completely
[39m
[32m# 9. native server - we can get a ton of connections and data through and still clean up the server completely
[39m
[36m# 9. native server - we can get a ton of connections and data through and still clean up the server completely
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50491
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50502
[39m
[33mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: listening 50504
[39m
[33mDEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[33mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
[39m
[33mDEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
[39m
[33mDEBUG createNativeListener: new mux
[39m
[33mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
[39m
[33mDEBUG createNativeListener: creating incoming mux
[39m
[33mDEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[33mDEBUG createNativeListener: new incoming socket
[39m
[33mDEBUG createNativeListener: creating incoming mux
[39m
[33mDEBUG createNativeListener: new mux
[39m
[32mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
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
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
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
DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
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
DEBUG createNativeListener: new outgoing socket
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
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
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
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[36mDEBUG createNativeListener: new incoming socket
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
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
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
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
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
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
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
[33mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: mux close
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: new outgoing socket
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
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: mux close
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: mux close
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: new stream: 
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
[39m
[36mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: mux close
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
ok 28 native server is nulled out
ok 29 native server should be closed
ok 30 incoming has been removed
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
[39m
[33mDEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
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
[36mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
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
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
[39m
[33m# teardown
[39m
[36mok 28 native server is nulled out
ok 29 native server should be closed
ok 30 incoming has been removed
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
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
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
[39m
[32mok 28 native server is nulled out
[39m
[32mok 29 native server should be closed
[39m
[32mok 30 incoming has been removed
[39m
[32mDEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
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
[36m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T13:13:43.392Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

[32m# 10. native server - simulate mux failure, make sure everything is cleaned up
[39m
[33m# 10. native server - simulate mux failure, make sure everything is cleaned up
[39m
[36m# 10. native server - simulate mux failure, make sure everything is cleaned up
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50647
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: new incoming socket
[39m
[33mDEBUG createNativeListener: creating incoming mux
[39m
[33mDEBUG createNativeListener: new mux
[39m
[32mDEBUG createNativeListener: listening 50649
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[32mok 31 we should not have gotten an error
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[33mok 31 we should not have gotten an error
[39m
[32mok 32 Buffers are identical
[39m
[32mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
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
[32mDEBUG createNativeListener: incoming socket close
ok 33 server should be fine
[39m
[32mok 34 server should be open
[39m
[32mok 35 incoming has been removed
[39m
[32mok 36 The mux object should be closed
[39m
[32mok 37 The mux stream should be closed
[39m
[32m# teardown
[39m
[33mDEBUG createNativeListener: incoming socket close
ok 33 server should be fine
ok 34 server should be open
ok 35 incoming has been removed
ok 36 The mux object should be closed
[39m
[33mok 37 The mux stream should be closed
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[33m# teardown
[39m
[36mDEBUG createNativeListener: listening 50653
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
[39m
[36mDEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[36mok 33 server should be fine
[39m
[36mok 34 server should be open
[39m
[36mok 35 incoming has been removed
ok 36 The mux object should be closed
[39m
[36mok 37 The mux stream should be closed
[39m
[36m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T13:13:43.438Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

[32m# 11. native server - timing out the incoming connection cleans everything up
[39m
[33m# 11. native server - timing out the incoming connection cleans everything up
[39m
[36m# 11. native server - timing out the incoming connection cleans everything up
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50659
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50660
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[32mok 38 we should not have gotten an error
[39m
[33mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
ok 39 Buffers are identical
[39m
[33mDEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[33mok 38 we should not have gotten an error
[39m
[33mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[33mok 39 Buffers are identical
[39m
[32mDEBUG createNativeListener: incoming socket timeout
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: listening 50664
[39m
[32mDEBUG createNativeListener: mux close
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[32mok 40 server should be fine
[39m
[32mok 41 server should be open
[39m
[32mok 42 incoming has been removed
ok 43 The mux object should be closed
[39m
[32mok 44 The mux stream should be closed
[39m
[36mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[33mDEBUG createNativeListener: incoming socket timeout
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[32m# teardown
[39m
[36mok 38 we should not have gotten an error
[39m
[33mDEBUG createNativeListener: mux close
[39m
[33mDEBUG createNativeListener: incoming socket close
ok 40 server should be fine
ok 41 server should be open
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[33mok 42 incoming has been removed
ok 43 The mux object should be closed
ok 44 The mux stream should be closed
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mok 39 Buffers are identical
[39m
[33m# teardown
[39m
[36mDEBUG createNativeListener: incoming socket timeout
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[36mok 40 server should be fine
ok 41 server should be open
[39m
[36mok 42 incoming has been removed
[39m
[36mok 43 The mux object should be closed
[39m
[36mok 44 The mux stream should be closed
[39m
[36m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:13:43.497Z - info: Running on ios test: 12. #_doImmediateSeqUpdate - server is not there

[33m# 12. #_doImmediateSeqUpdate - server is not there
[39m
[36m# 12. #_doImmediateSeqUpdate - server is not there
[39m
[32m# 12. #_doImmediateSeqUpdate - server is not there
[39m
[36mDEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}
ok 45 Got right error
[39m
[33mDEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}
ok 45 Got right error
# teardown
[39m
[36m# teardown
[39m
[32mDEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}
ok 45 Got right error
[39m
[32m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T13:13:43.568Z - info: Running on ios test: 13. #_doImmediateSeqUpdate - server accepts & closes connection

[33m# 13. #_doImmediateSeqUpdate - server accepts & closes connection
[39m
[36m# 13. #_doImmediateSeqUpdate - server accepts & closes connection
[39m
[32m# 13. #_doImmediateSeqUpdate - server accepts & closes connection
[39m
[33mDEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNRESET","status":500}
ok 46 Got socket hang up
# teardown
[39m
[36mDEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNRESET","status":500}
ok 46 Got socket hang up
# teardown
[39m
[32mDEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNRESET","status":500}
[39m
[32mok 46 Got socket hang up
[39m
[32m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T13:13:43.618Z - info: Running on ios test: 14. #_doImmediateSeqUpdate - server always returns 500

[33m# 14. #_doImmediateSeqUpdate - server always returns 500
[39m
[36m# 14. #_doImmediateSeqUpdate - server always returns 500
[39m
[32m# 14. #_doImmediateSeqUpdate - server always returns 500
[39m
[33mDEBUG localSeqManager: Got an error trying to update seq []
ok 47 Got 500 as expected
# teardown
[39m
[36mDEBUG localSeqManager: Got an error trying to update seq []
ok 47 Got 500 as expected
[39m
[36m# teardown
[39m
[32mDEBUG localSeqManager: Got an error trying to update seq []
ok 47 Got 500 as expected
[39m
[32m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T13:13:43.676Z - info: Running on ios test: 15. #_doImmediateSeqUpdate - create new seq doc

[36m# 15. #_doImmediateSeqUpdate - create new seq doc
[39m
[33m# 15. #_doImmediateSeqUpdate - create new seq doc
[39m
[32m# 15. #_doImmediateSeqUpdate - create new seq doc
[39m
[36mok 48 should be equal
ok 49 revs are equal
[39m
[36m# teardown
[39m
[33mok 48 should be equal
ok 49 revs are equal
[39m
[33m# teardown
[39m
[32mok 48 should be equal
[39m
[32mok 49 revs are equal
[39m
[32m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T13:13:44.172Z - info: Running on ios test: 16. #_doImmediateSeqUpdate - doc exists, need to get rev and update

[33m# 16. #_doImmediateSeqUpdate - doc exists, need to get rev and update
[39m
[36m# 16. #_doImmediateSeqUpdate - doc exists, need to get rev and update
[39m
[32m# 16. #_doImmediateSeqUpdate - doc exists, need to get rev and update
[39m
[33mok 50 should be equal
ok 51 revs are equal
[39m
[36mok 50 should be equal
[39m
[33m# teardown
[39m
[36mok 51 revs are equal
[39m
[36m# teardown
[39m
[32mok 50 should be equal
[39m
[32mok 51 revs are equal
[39m
[32m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T13:13:44.323Z - info: Running on ios test: 17. #_doImmediateSeqUpdate - update seq three times

[33m# 17. #_doImmediateSeqUpdate - update seq three times
[39m
[36m# 17. #_doImmediateSeqUpdate - update seq three times
[39m
[32m# 17. #_doImmediateSeqUpdate - update seq three times
[39m
[33mok 52 should be equal
ok 53 revs are equal
[39m
[36mok 52 should be equal
ok 53 revs are equal
[39m
[33mok 54 should be equal
[39m
[33mok 55 revs are equal
[39m
[36mok 54 should be equal
ok 55 revs are equal
[39m
[33mok 56 should be equal
[39m
[33mok 57 revs are equal
[39m
[33m# teardown
[39m
[36mok 56 should be equal
[39m
[36mok 57 revs are equal
[39m
[36m# teardown
[39m
[32mok 52 should be equal
[39m
[32mok 53 revs are equal
[39m
[32mok 54 should be equal
[39m
[32mok 55 revs are equal
[39m
[32mok 56 should be equal
[39m
[32mok 57 revs are equal
[39m
[32m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T13:13:44.513Z - info: Running on ios test: 18. #_doImmediateSeqUpdate - rev got changed under us

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
[33m# teardown
[39m
[36mDEBUG localSeqManager: Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}
[39m
[36mok 58 Our rev is old so we should fail
[39m
[36m# teardown
[39m
[32mDEBUG localSeqManager: Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}
[39m
[32mok 58 Our rev is old so we should fail
[39m
[32m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T13:13:44.665Z - info: Running on ios test: 19. #_doImmediateSeqUpdate - fail if stop is called

[32m# 19. #_doImmediateSeqUpdate - fail if stop is called
[39m
[36m# 19. #_doImmediateSeqUpdate - fail if stop is called
[39m
[33m# 19. #_doImmediateSeqUpdate - fail if stop is called
[39m
[36mok 59 confirm stop caused failure
[39m
[36m# teardown
[39m
[32mok 59 confirm stop caused failure
[39m
[32m# teardown
[39m
[33mok 59 confirm stop caused failure
[39m
[33m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T13:13:44.709Z - info: Running on ios test: 20. #_doImmediateSeqUpdate - stop after get but before put fails right

[36m# 20. #_doImmediateSeqUpdate - stop after get but before put fails right
[39m
[32m# 20. #_doImmediateSeqUpdate - stop after get but before put fails right
[39m
[33m# 20. #_doImmediateSeqUpdate - stop after get but before put fails right
[39m
[36mDEBUG localSeqManager: Got an error trying to update seq {"onPut":true}
[39m
[36mok 60 stop caused us to fail
ok 61 We specifically failed on a stop before put
[39m
[36m# teardown
[39m
[33mDEBUG localSeqManager: Got an error trying to update seq {"onPut":true}
ok 60 stop caused us to fail
ok 61 We specifically failed on a stop before put
[39m
[33m# teardown
[39m
[32mDEBUG localSeqManager: Got an error trying to update seq {"onPut":true}
[39m
[32mok 60 stop caused us to fail
[39m
[32mok 61 We specifically failed on a stop before put
[39m
[32m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T13:13:44.805Z - info: Running on ios test: 21. #update - fail if stop is called

[36m# 21. #update - fail if stop is called
[39m
[33m# 21. #update - fail if stop is called
[39m
[32m# 21. #update - fail if stop is called
[39m
[36mok 62 failed due to stop
ok 63 failed due to stop
[39m
[36m# teardown
[39m
[33mok 62 failed due to stop
[39m
[33mok 63 failed due to stop
[39m
[32mok 62 failed due to stop
[39m
[33m# teardown
[39m
[32mok 63 failed due to stop
[39m
[32m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:13:44.843Z - info: Running on ios test: 22. #update - set seq for first time

[33m# 22. #update - set seq for first time
[39m
[36m# 22. #update - set seq for first time
[39m
[32m# 22. #update - set seq for first time
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
2016-08-10T13:13:44.969Z - info: Running on ios test: 23. #update - Fail on bad seq value

[33m# 23. #update - Fail on bad seq value
[39m
[36m# 23. #update - Fail on bad seq value
[39m
[32m# 23. #update - Fail on bad seq value
[39m
[33mDEBUG localSeqManager: Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10
[39m
[33mok 65 Expected bad seq error
[39m
[33m# teardown
[39m
[36mDEBUG localSeqManager: Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10
[39m
[36mok 65 Expected bad seq error
[39m
[36m# teardown
[39m
[32mDEBUG localSeqManager: Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10
[39m
[32mok 65 Expected bad seq error
[39m
[32m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:13:45.085Z - info: Running on ios test: 24. #update - do we cancel timer properly on an immediate?

[36m# 24. #update - do we cancel timer properly on an immediate?
[39m
[33m# 24. #update - do we cancel timer properly on an immediate?
[39m
[32m# 24. #update - do we cancel timer properly on an immediate?
[39m
[36mok 66 Different promises
[39m
[36mok 67 Timer was cancelled
[39m
[36mok 68 should be equal
[39m
[36m# teardown
[39m
[32mok 66 Different promises
[39m
[32mok 67 Timer was cancelled
[39m
[32mok 68 should be equal
[39m
[32m# teardown
[39m
[33mok 66 Different promises
[39m
[33mok 67 Timer was cancelled
[39m
[33mok 68 should be equal
[39m
[33m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T13:13:45.220Z - info: Running on ios test: 25. #update - do we wait for blocked update

[36m# 25. #update - do we wait for blocked update
[39m
[32m# 25. #update - do we wait for blocked update
[39m
[33m# 25. #update - do we wait for blocked update
[39m
[36mok 69 One go and one blocked
[39m
[32mok 69 One go and one blocked
[39m
[36mok 70 All blocked
ok 71 Still blocked
[39m
[32mok 70 All blocked
[39m
[32mok 71 Still blocked
[39m
[36mok 72 should be equal
[39m
[36m# teardown
[39m
[33mok 69 One go and one blocked
[39m
[33mok 70 All blocked
[39m
[33mok 71 Still blocked
[39m
[32mok 72 should be equal
[39m
[32m# teardown
[39m
[33mok 72 should be equal
[39m
[33m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T13:13:45.336Z - info: Running on ios test: 26. #update - test that we wait long enough

[33m# 26. #update - test that we wait long enough
[39m
[36m# 26. #update - test that we wait long enough
[39m
[32m# 26. #update - test that we wait long enough
[39m
[36mok 73 We waited long enough
[39m
[36mok 74 should be equal
# teardown
[39m
[32mok 73 We waited long enough
[39m
[32mok 74 should be equal
[39m
[32m# teardown
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
2016-08-10T13:13:46.441Z - info: Running on ios test: 27. #update - test that we pick up new sequences while we wait

[33m# 27. #update - test that we pick up new sequences while we wait
[39m
[36m# 27. #update - test that we pick up new sequences while we wait
[39m
[32m# 27. #update - test that we pick up new sequences while we wait
[39m
[36mok 75 Should have gotten same timer promise
[39m
[36mok 76 Still same timer promise
[39m
[33mok 75 Should have gotten same timer promise
[39m
[33mok 76 Still same timer promise
[39m
[32mok 75 Should have gotten same timer promise
[39m
[32mok 76 Still same timer promise
[39m
[36mok 77 We waited long enough
[39m
[33mok 77 We waited long enough
[39m
[36mok 78 should be equal
# teardown
[39m
[32mok 77 We waited long enough
[39m
[33mok 78 should be equal
[39m
[32mok 78 should be equal
[39m
[32m# teardown
[39m
[33m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T13:13:47.500Z - info: Running on ios test: 28. Coordinated seq test

[36m# 28. Coordinated seq test
[39m
[32m# 28. Coordinated seq test
[39m
[33m# 28. Coordinated seq test
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: listening 50877
[39m
[32mDEBUG createNativeListener: listening 50878
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50884
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: first connection
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[32mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createPeerListener: first connection
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
DEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[32mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createPeerListener: forward connection
[39m
[33mDEBUG createPeerListener: forward connection
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: 
DEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: 
DEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: 
DEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: 
DEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: 
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: 
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mok 79 should be equal
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mok 79 should be equal
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[32mok 80 should be equal
[39m
[32m# teardown
[39m
[36mok 79 should be equal
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[33mok 80 should be equal
[39m
[33m# teardown
[39m
[36mok 80 should be equal
[39m
[36m# teardown
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[36mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[33mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mDEBUG createNativeListener: mux close
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: mux close
[39m
[33mDEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[33mDEBUG testUtils: Got an err - TypeError: Cannot call method 'stop' of undefined
[39m
[33m# setup
[39m
[36mDEBUG testUtils: Got an err - TypeError: Cannot call method 'stop' of undefined
[39m
[36m# setup
[39m
[32mDEBUG createPeerListener: Recreating listener
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: Recreating listener
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG testUtils: Got an err - TypeError: Cannot call method 'stop' of undefined
[39m
[32mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[32mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mWARN createPeerListener: 
[39m
2016-08-10T13:13:48.784Z - info: Running on ios test: 29. closeAll can close even when connections open

[32mDEBUG createPeerListener: failedConnection
[39m
[32mDEBUG createPeerListener: failed incoming connection because of mux promise failure - Error: Connection could not be established
[39m
[32mWARN createPeerListener: 
[39m
[32mDEBUG createPeerListener: failedConnection
[39m
[36m# 29. closeAll can close even when connections open
[39m
[33m# 29. closeAll can close even when connections open
[39m
[32mDEBUG createPeerListener: failed incoming connection because of mux promise failure - Error: Connection could not be established
[39m
[32m# setup
[39m
[32m# 29. closeAll can close even when connections open
[39m
[33mok 81 not possible to connect to the server anymore
[39m
[36mok 81 not possible to connect to the server anymore
[39m
[36m# teardown
[39m
[33m# teardown
[39m
[32mok 81 not possible to connect to the server anymore
[39m
[32m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T13:13:48.912Z - info: Running on ios test: 30. closeAll with promise

[36m# 30. closeAll with promise
[39m
[33m# 30. closeAll with promise
[39m
[32m# 30. closeAll with promise
[39m
[36mok 82 not possible to connect to the server anymore
[39m
[36m# teardown
[39m
[33mok 82 not possible to connect to the server anymore
[39m
[33m# teardown
[39m
[32mok 82 not possible to connect to the server anymore
[39m
[32m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:13:49.066Z - info: Running on ios test: 31. closeAll properly throws when closing a non open server with eatNotRunning set to false

[36m# 31. closeAll properly throws when closing a non open server with eatNotRunning set to false
[39m
[32m# 31. closeAll properly throws when closing a non open server with eatNotRunning set to false
[39m
[33m# 31. closeAll properly throws when closing a non open server with eatNotRunning set to false
[39m
[36mok 83 Got the right error
[39m
[32mok 83 Got the right error
[39m
[32m# teardown
[39m
[36m# teardown
[39m
[33mok 83 Got the right error
[39m
[33m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T13:13:49.193Z - info: Running on ios test: 32. closeAll works even with a server that is not listening yet witheatNotRunning set to true

[36m# 32. closeAll works even with a server that is not listening yet witheatNotRunning set to true
[39m
[33m# 32. closeAll works even with a server that is not listening yet witheatNotRunning set to true
[39m
[32m# 32. closeAll works even with a server that is not listening yet witheatNotRunning set to true
[39m
[33m# teardown
[39m
[32m# teardown
[39m
[36m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T13:13:49.313Z - info: Running on ios test: 33. enqueue and run in order

[36m# 33. enqueue and run in order
[39m
[33m# 33. enqueue and run in order
[39m
[32m# 33. enqueue and run in order
[39m
[36mok 84 firstPromise setTimeout
[39m
[36mok 85 firstPromise result
ok 86 firstPromise testValue
[39m
[33mok 84 firstPromise setTimeout
[39m
[33mok 85 firstPromise result
[39m
[33mok 86 firstPromise testValue
[39m
[32mok 84 firstPromise setTimeout
[39m
[32mok 85 firstPromise result
[39m
[32mok 86 firstPromise testValue
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
ok 91 thirdPromise result
ok 92 thirdPromise testValue
# teardown
[39m
[32mok 87 secondPromise setTimeout
ok 88 secondPromise result
ok 89 secondPromise testValue
ok 90 thirdPromise in promise
[39m
[32mok 91 thirdPromise result
[39m
[32mok 92 thirdPromise testValue
[39m
[32m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:13:49.538Z - info: Running on ios test: 34. enqueueAtTop and run backwards

[36m# 34. enqueueAtTop and run backwards
[39m
[33m# 34. enqueueAtTop and run backwards
[39m
[32m# 34. enqueueAtTop and run backwards
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
ok 98 firstPromise - in then
ok 99 testing promises
# teardown
[39m
[32mok 93 thirdPromise - first to run
ok 94 thirdPromise - in resolve
[39m
[32mok 95 secondPromise - second to run
ok 96 secondPromise - in catch
ok 97 firstPromise - third to run
[39m
[32mok 98 firstPromise - in then
ok 99 testing promises
# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:13:49.562Z - info: Running on ios test: 35. mix enqueue and enqueueAtTop

[36m# 35. mix enqueue and enqueueAtTop
[39m
[33m# 35. mix enqueue and enqueueAtTop
[39m
[32m# 35. mix enqueue and enqueueAtTop
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
[32mok 100 fourth
[39m
[32mok 101 fourth
[39m
[32mok 102 second
[39m
[32mok 103 secondPromise - in then
[39m
[33mok 104 first
[39m
[33mok 105 firstPromise - in catch
ok 106 third
[39m
[33mok 107 thirdPromise - in then
[39m
[33mok 108 testingPromises
[39m
[33m# teardown
[39m
[32mok 104 first
[39m
[32mok 105 firstPromise - in catch
[39m
[32mok 106 third
ok 107 thirdPromise - in then
[39m
[32mok 108 testingPromises
[39m
[36mok 104 first
[39m
[32m# teardown
[39m
[36mok 105 firstPromise - in catch
[39m
[36mok 106 third
[39m
[36mok 107 thirdPromise - in then
[39m
[36mok 108 testingPromises
[39m
[36m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:13:49.688Z - info: Running on ios test: 36. queues handled independently

[33m# 36. queues handled independently
[39m
[36m# 36. queues handled independently
[39m
[32m# 36. queues handled independently
[39m
[33mok 109 all short operations completed before the long resolves
# teardown
[39m
[36mok 109 all short operations completed before the long resolves
# teardown
[39m
[32mok 109 all short operations completed before the long resolves
[39m
[32m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:13:49.744Z - info: Running on ios test: 37. basic

[36m# 37. basic
[39m
[33m# 37. basic
[39m
[32m# 37. basic
[39m
[36mok 110 sane
# teardown
[39m
[33mok 110 sane
# teardown
[39m
[32mok 110 sane
[39m
[32m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:13:49.769Z - info: Running on ios test: 38. another

[33m# 38. another
[39m
[36m# 38. another
[39m
[32m# 38. another
[39m
[33mok 111 sane
[39m
[33m# teardown
[39m
[32mok 111 sane
[39m
[36mok 111 sane
[39m
[36m# teardown
[39m
[32m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:13:49.792Z - info: Running on ios test: 39. can pass data in setup

[36m# 39. can pass data in setup
[39m
[33m# 39. can pass data in setup
[39m
[32m# 39. can pass data in setup
[39m
[36m[{"uuid":"a5eaf94a-5576-4df5-97f3-297453e96205","data":"custom data"},{"uuid":"a266af8d-3909-4155-a964-4854297c67cb","data":"custom data"},{"uuid":"c151329e-6c29-47f2-94a1-0bcd6c746b9a","data":"custom data"}]
[39m
[33m[{"uuid":"a5eaf94a-5576-4df5-97f3-297453e96205","data":"custom data"},{"uuid":"a266af8d-3909-4155-a964-4854297c67cb","data":"custom data"},{"uuid":"c151329e-6c29-47f2-94a1-0bcd6c746b9a","data":"custom data"}]
[39m
[36mok 112 test participant has uuid
[39m
[36mok 113 participant data matches
ok 114 test participant has uuid
[39m
[33mok 112 test participant has uuid
[39m
[33mok 113 participant data matches
[39m
[36mok 115 participant data matches
[39m
[36mok 116 test participant has uuid
[39m
[33mok 114 test participant has uuid
[39m
[36mok 117 participant data matches
[39m
[33mok 115 participant data matches
[39m
[36mok 118 own UUID is found from the participants list
[39m
[33mok 116 test participant has uuid
ok 117 participant data matches
[39m
[33mok 118 own UUID is found from the participants list
[39m
[36m# teardown
[39m
[33m# teardown
[39m
[32m[{"uuid":"a5eaf94a-5576-4df5-97f3-297453e96205","data":"custom data"},{"uuid":"a266af8d-3909-4155-a964-4854297c67cb","data":"custom data"},{"uuid":"c151329e-6c29-47f2-94a1-0bcd6c746b9a","data":"custom data"}]
[39m
[32mok 112 test participant has uuid
[39m
[32mok 113 participant data matches
ok 114 test participant has uuid
ok 115 participant data matches
[39m
[32mok 116 test participant has uuid
[39m
[32mok 117 participant data matches
ok 118 own UUID is found from the participants list
[39m
[32m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:13:49.820Z - info: Running on ios test: 40. can continue after disconnect from server

[33m# 40. can continue after disconnect from server
[39m
[32m# 40. can continue after disconnect from server
[39m
[36m# 40. can continue after disconnect from server
[39m
[36mDisconnected from the test server
[39m
[33mDisconnected from the test server
[39m
[32mDisconnected from the test server
[39m
2016-08-10T13:13:49.836Z - info: Socket to device 964c1b4b-ccb7-459d-b34a-7c5d3cbf07bb disconnected: client namespace disconnect

2016-08-10T13:13:49.839Z - info: Socket to device 1f0fe313-c015-4773-bff6-8a2fb89a7056 disconnected: client namespace disconnect

2016-08-10T13:13:49.840Z - info: Socket to device 7a8e4c64-9460-4f1b-86a7-8929ff661cf1 disconnected: client namespace disconnect

[36mConnected to the test server
[39m
[33mConnected to the test server
[39m
[32mConnected to the test server
[39m
[33mok 119 got connect event
[39m
[33m# teardown
[39m
[32mok 119 got connect event
[39m
[32m# teardown
[39m
[36mok 119 got connect event
[39m
[36m# teardown
[39m
2016-08-10T13:13:50.357Z - debug: Device presented: 1f0fe313-c015-4773-bff6-8a2fb89a7056 (a266af8d-3909-4155-a964-4854297c67cb) - ios dummy

2016-08-10T13:13:50.357Z - info: Updating existing device: 1f0fe313-c015-4773-bff6-8a2fb89a7056 (a266af8d-3909-4155-a964-4854297c67cb)

2016-08-10T13:13:50.359Z - debug: Device presented: 7a8e4c64-9460-4f1b-86a7-8929ff661cf1 (c151329e-6c29-47f2-94a1-0bcd6c746b9a) - ios dummy
2016-08-10T13:13:50.359Z - info: Updating existing device: 7a8e4c64-9460-4f1b-86a7-8929ff661cf1 (c151329e-6c29-47f2-94a1-0bcd6c746b9a)

2016-08-10T13:13:50.360Z - debug: Device presented: 964c1b4b-ccb7-459d-b34a-7c5d3cbf07bb (a5eaf94a-5576-4df5-97f3-297453e96205) - ios dummy
2016-08-10T13:13:50.360Z - info: Updating existing device: 964c1b4b-ccb7-459d-b34a-7c5d3cbf07bb (a5eaf94a-5576-4df5-97f3-297453e96205)

[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-10T13:13:50.368Z - info: Running on ios test: 41. test after disconnect

[32m# 41. test after disconnect
[39m
[36m# 41. test after disconnect
[39m
[33m# 41. test after disconnect
[39m
[36mok 120 worked
[39m
[36m# teardown
[39m
[32mok 120 worked
[39m
[32m# teardown
[39m
[33mok 120 worked
[39m
[33m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T13:13:50.393Z - info: Running on ios test: 42. #startListeningForAdvertisements should fail if start not called

[36m# 42. #startListeningForAdvertisements should fail if start not called
[39m
[32m# 42. #startListeningForAdvertisements should fail if start not called
[39m
[33m# 42. #startListeningForAdvertisements should fail if start not called
[39m
[36mok 121 specific error should be returned
[39m
[36m# teardown
[39m
[32mok 121 specific error should be returned
[39m
[32m# teardown
[39m
[33mok 121 specific error should be returned
# teardown
[39m
[32mok 122 error should be null
ok 123 error should be null
# setup
[39m
[36mok 122 error should be null
[39m
[36mok 123 error should be null
[39m
[36m# setup
[39m
[33mok 122 error should be null
ok 123 error should be null
[39m
[33m# setup
[39m
2016-08-10T13:13:50.423Z - info: Running on ios test: 43. #startUpdateAdvertisingAndListening should fail if start not called

[36m# 43. #startUpdateAdvertisingAndListening should fail if start not called
[39m
[32m# 43. #startUpdateAdvertisingAndListening should fail if start not called
[39m
[33m# 43. #startUpdateAdvertisingAndListening should fail if start not called
[39m
[32mok 124 specific error should be returned
[39m
[32m# teardown
[39m
[33mok 124 specific error should be returned
[39m
[33m# teardown
[39m
[36mok 124 specific error should be returned
[39m
[36m# teardown
[39m
[36mok 125 error should be null
[39m
[36mok 126 error should be null
[39m
[36m# setup
[39m
[32mok 125 error should be null
ok 126 error should be null
[39m
[32m# setup
[39m
[33mok 125 error should be null
ok 126 error should be null
[39m
[33m# setup
[39m
2016-08-10T13:13:50.456Z - info: Running on ios test: 44. should be able to call #stopListeningForAdvertisements many times

[32m# 44. should be able to call #stopListeningForAdvertisements many times
[39m
[36m# 44. should be able to call #stopListeningForAdvertisements many times
[39m
[33m# 44. should be able to call #stopListeningForAdvertisements many times
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51007
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: listening 51008
[39m
[33mok 127 error should be null
[39m
[33mok 128 error should be null
[39m
[32mok 127 error should be null
[39m
[32mok 128 error should be null
[39m
[33mok 129 error should be null
[39m
[33mok 130 error should be null
[39m
[33m# teardown
[39m
[32mok 129 error should be null
[39m
[32mok 130 error should be null
[39m
[32m# teardown
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: listening 51010
[39m
[36mok 127 error should be null
[39m
[36mok 128 error should be null
[39m
[36mok 129 error should be null
[39m
[36mok 130 error should be null
[39m
[36m# teardown
[39m
[32mok 131 error should be null
[39m
[32mok 132 error should be null
[39m
[32m# setup
[39m
[33mok 131 error should be null
[39m
[33mok 132 error should be null
[39m
[33m# setup
[39m
[36mok 131 error should be null
[39m
[36mok 132 error should be null
[39m
[36m# setup
[39m
2016-08-10T13:13:50.497Z - info: Running on ios test: 45. should be able to call #startListeningForAdvertisements many times

[32m# 45. should be able to call #startListeningForAdvertisements many times
[39m
[33m# 45. should be able to call #startListeningForAdvertisements many times
[39m
[36m# 45. should be able to call #startListeningForAdvertisements many times
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: listening 51012
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[32mok 133 error should be null
[39m
[32mok 134 error should be null
[39m
[32mok 135 error should be null
ok 136 error should be null
# teardown
[39m
[33mDEBUG createNativeListener: listening 51014
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
[36mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: listening 51016
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[36mok 133 error should be null
[39m
[36mok 134 error should be null
[39m
[36mok 135 error should be null
ok 136 error should be null
[39m
[36m# teardown
[39m
[32mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
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
[36mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[36mok 137 error should be null
[39m
[36mok 138 error should be null
[39m
[36m# setup
[39m
2016-08-10T13:13:50.537Z - info: Running on ios test: 46. should be able to call #startUpdateAdvertisingAndListening many times

[36m# 46. should be able to call #startUpdateAdvertisingAndListening many times
[39m
[32m# 46. should be able to call #startUpdateAdvertisingAndListening many times
[39m
[33m# 46. should be able to call #startUpdateAdvertisingAndListening many times
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: listening 51020
[39m
[33mDEBUG createNativeListener: listening 51019
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[32mok 139 error should be null
ok 140 error should be null
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[32mok 141 error should be null
[39m
[32mok 142 error should be null
[39m
[32m# teardown
[39m
[33mok 139 error should be null
[39m
[33mok 140 error should be null
[39m
[33mok 141 error should be null
[39m
[33mok 142 error should be null
[39m
[33m# teardown
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: listening 51028
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[36mok 139 error should be null
[39m
[36mok 140 error should be null
[39m
[36mok 141 error should be null
[39m
[36mok 142 error should be null
[39m
[36m# teardown
[39m
[36mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[36mok 143 error should be null
[39m
[33mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[32mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 143 error should be null
ok 144 error should be null
# setup
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 143 error should be null
ok 144 error should be null
# setup
[39m
[36mok 144 error should be null
[39m
[36m# setup
[39m
2016-08-10T13:13:50.593Z - info: Running on ios test: 47. should be able to call #stopAdvertisingAndListening many times

[33m# 47. should be able to call #stopAdvertisingAndListening many times
[39m
[32m# 47. should be able to call #stopAdvertisingAndListening many times
[39m
[36m# 47. should be able to call #stopAdvertisingAndListening many times
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51033
ok 145 error should be null
ok 146 error should be null
ok 147 error should be null
ok 148 error should be null
# teardown
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51035
ok 145 error should be null
ok 146 error should be null
[39m
[33mok 147 error should be null
ok 148 error should be null
# teardown
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: listening 51037
[39m
[36mok 145 error should be null
ok 146 error should be null
[39m
[36mok 147 error should be null
[39m
[36mok 148 error should be null
[39m
[36m# teardown
[39m
[32mok 149 error should be null
ok 150 error should be null
# setup
[39m
[36mok 149 error should be null
ok 150 error should be null
# setup
[39m
[33mok 149 error should be null
[39m
[33mok 150 error should be null
[39m
[33m# setup
[39m
2016-08-10T13:13:50.633Z - info: Running on ios test: 48. #start should fail if called twice in a row

[32m# 48. #start should fail if called twice in a row
[39m
[33m# 48. #start should fail if called twice in a row
[39m
[36m# 48. #start should fail if called twice in a row
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51041
ok 151 first call should succeed
ok 152 first call should succeed
ok 153 specific error should be returned
# teardown
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51040
ok 151 first call should succeed
ok 152 first call should succeed
ok 153 specific error should be returned
# teardown
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: listening 51043
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
ok 155 error should be null
# setup
[39m
[33mok 154 error should be null
ok 155 error should be null
# setup
[39m
[36mok 154 error should be null
ok 155 error should be null
[39m
[36m# setup
[39m
2016-08-10T13:13:50.670Z - info: Running on ios test: 49. does not emit duplicate discoveryAdvertisingStateUpdate

[33m# 49. does not emit duplicate discoveryAdvertisingStateUpdate
[39m
[32m# 49. does not emit duplicate discoveryAdvertisingStateUpdate
[39m
[36m# 49. does not emit duplicate discoveryAdvertisingStateUpdate
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: listening 51045
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 156 called only once
ok 157 discovery state matches
ok 158 advertising state matches
# teardown
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51047
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[33mok 156 called only once
ok 157 discovery state matches
ok 158 advertising state matches
[39m
[33m# teardown
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: listening 51055
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[36mok 156 called only once
ok 157 discovery state matches
[39m
[36mok 158 advertising state matches
[39m
[36m# teardown
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mINFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[32mok 159 error should be null
ok 160 error should be null
# setup
[39m
[36mINFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[36mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 159 error should be null
ok 160 error should be null
# setup
[39m
[33mDEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
[39m
[33mDEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
[39m
[33mINFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
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
2016-08-10T13:13:50.743Z - info: Running on ios test: 50. does not send duplicate availability changes

[36m# 50. does not send duplicate availability changes
[39m
[32m# 50. does not send duplicate availability changes
[39m
[33m# 50. does not send duplicate availability changes
[39m
[32mok 161 should be called once
ok 162 should not have been called more than once
# teardown
[39m
[33mok 161 should be called once
ok 162 should not have been called more than once
# teardown
[39m
[36mok 161 should be called once
ok 162 should not have been called more than once
# teardown
[39m
[32mok 163 error should be null
ok 164 error should be null
[39m
[32m# setup
[39m
[36mok 163 error should be null
ok 164 error should be null
[39m
[36m# setup
[39m
[33mok 163 error should be null
[39m
[33mok 164 error should be null
[39m
[33m# setup
[39m
2016-08-10T13:13:50.779Z - info: Running on ios test: 51. can get the network status

[32m# 51. can get the network status
[39m
[36m# 51. can get the network status
[39m
[33m# 51. can get the network status
[39m
[36mok 165 network status should have certain non-empty properties
# teardown
[39m
[32mok 165 network status should have certain non-empty properties
# teardown
[39m
[33mok 165 network status should have certain non-empty properties
[39m
[33m# teardown
[39m
[32mok 166 error should be null
ok 167 error should be null
# setup
[39m
[36mok 166 error should be null
[39m
[36mok 167 error should be null
[39m
[36m# setup
[39m
[33mok 166 error should be null
[39m
[33mok 167 error should be null
[39m
[33m# setup
[39m
2016-08-10T13:13:50.804Z - info: Running on ios test: 52. wifi peer is marked unavailable if announcements stop

[32m# 52. wifi peer is marked unavailable if announcements stop
[39m
[33m# 52. wifi peer is marked unavailable if announcements stop
[39m
[36m# 52. wifi peer is marked unavailable if announcements stop
[39m
[32mERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
[39m
[33mERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
[39m
[32mok 168 host address should match
ok 169 port should match
[39m
[36mERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
[39m
[36mok 168 host address should match
ok 169 port should match
[39m
[33mok 168 host address should match
ok 169 port should match
[39m
[32mok 170 host address should be null
[39m
[32mok 171 port should should be null
[39m
[32m# teardown
[39m
[36mok 170 host address should be null
ok 171 port should should be null
[39m
[33mok 170 host address should be null
ok 171 port should should be null
[39m
[33m# teardown
[39m
[36m# teardown
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
[32mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 172 error should be null
ok 173 error should be null
# setup
[39m
2016-08-10T13:13:51.839Z - info: Running on ios test: 53. network changes emitted correctly

[33m# 53. network changes emitted correctly
[39m
[32m# 53. network changes emitted correctly
[39m
[36m# 53. network changes emitted correctly
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51066
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 174 wifi is off
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 175 wifi is on
# teardown
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51067
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 174 wifi is off
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 175 wifi is on
# teardown
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: listening 51069
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mok 174 wifi is off
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mok 175 wifi is on
[39m
[36m# teardown
[39m
[33mok 176 error should be null
ok 177 error should be null
# setup
[39m
[32mok 176 error should be null
ok 177 error should be null
# setup
[39m
[36mok 176 error should be null
[39m
[36mok 177 error should be null
[39m
[36m# setup
[39m
2016-08-10T13:13:51.874Z - info: Running on ios test: 54. network changes not emitted in stopped state

[32m# 54. network changes not emitted in stopped state
[39m
[33m# 54. network changes not emitted in stopped state
[39m
[36m# 54. network changes not emitted in stopped state
[39m
[32mok 178 event was not emitted
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
# teardown
[39m
[33mok 178 event was not emitted
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
# teardown
[39m
[36mok 178 event was not emitted
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36m# teardown
[39m
[32mok 179 error should be null
ok 180 error should be null
# setup
[39m
[33mok 179 error should be null
ok 180 error should be null
# setup
[39m
[36mok 179 error should be null
[39m
[36mok 180 error should be null
[39m
[36m# setup
[39m
2016-08-10T13:13:51.904Z - info: Running on ios test: 55. calls correct starts when network changes

[33m# 55. calls correct starts when network changes
[39m
[32m# 55. calls correct starts when network changes
[39m
[36m# 55. calls correct starts when network changes
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51072
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 181 specific error expected
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 182 specific error expected
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51073
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 181 specific error expected
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 182 specific error expected
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[32mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mINFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":true,"advertisingActive":true}
[39m
[32mINFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":true,"advertisingActive":true}
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51081
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[32mok 183 startListeningForAdvertisements should have been called
[39m
[36mok 181 specific error expected
[39m
[32mok 184 startUpdateAdvertisingAndListening should have been called
[39m
[32m# teardown
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[36mok 182 specific error expected
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mINFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":true,"advertisingActive":true}
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mok 183 startListeningForAdvertisements should have been called
[39m
[36mok 184 startUpdateAdvertisingAndListening should have been called
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[36m# teardown
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mok 183 startListeningForAdvertisements should have been called
[39m
[33mok 184 startUpdateAdvertisingAndListening should have been called
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33m# teardown
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mINFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
[39m
[36mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[36mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[33mDEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
[39m
[33mINFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[32mDEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[32mINFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[32mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[32mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[36mok 185 error should be null
ok 186 error should be null
# setup
[39m
[32mok 185 error should be null
[39m
[32mok 186 error should be null
[39m
[32m# setup
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mok 185 error should be null
[39m
[33mok 186 error should be null
[39m
[33m# setup
[39m
2016-08-10T13:13:51.979Z - info: Running on ios test: 56. peer is marked unavailable if port number changes

[32m# 56. peer is marked unavailable if port number changes
[39m
[33m# 56. peer is marked unavailable if port number changes
[39m
[36m# 56. peer is marked unavailable if port number changes
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51097
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51098
[39m
[32mok 187 peer should have a non-empty identifier
ok 188 peer should have a non-empty host address
ok 189 peer should have port number
ok 190 peer should have suggested timeout
[39m
[32mok 191 peer should have a connection type
[39m
[32mok 192 connection type should match one of the pre-defined types
[39m
[33mok 187 peer should have a non-empty identifier
[39m
[32mok 193 peer should have a non-empty identifier
[39m
[33mok 188 peer should have a non-empty host address
[39m
[32mok 194 host address should be null
ok 195 port number should be null
[39m
[32mok 196 peer should have suggested timeout
[39m
[32mok 197 peer should have a connection type
[39m
[32mok 198 connection type should match one of the pre-defined types
[39m
[33mok 189 peer should have port number
[39m
[33mok 190 peer should have suggested timeout
[39m
[33mok 191 peer should have a connection type
ok 192 connection type should match one of the pre-defined types
ok 193 peer should have a non-empty identifier
ok 194 host address should be null
ok 195 port number should be null
ok 196 peer should have suggested timeout
ok 197 peer should have a connection type
ok 198 connection type should match one of the pre-defined types
[39m
[32mok 199 port number must match
ok 200 peer should have a non-empty identifier
ok 201 peer should have a non-empty host address
ok 202 peer should have port number
ok 203 peer should have suggested timeout
ok 204 peer should have a connection type
ok 205 connection type should match one of the pre-defined types
# teardown
[39m
[33mok 199 port number must match
ok 200 peer should have a non-empty identifier
[39m
[33mok 201 peer should have a non-empty host address
ok 202 peer should have port number
[39m
[33mok 203 peer should have suggested timeout
[39m
[33mok 204 peer should have a connection type
[39m
[33mok 205 connection type should match one of the pre-defined types
[39m
[33m# teardown
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51100
[39m
[36mok 187 peer should have a non-empty identifier
ok 188 peer should have a non-empty host address
ok 189 peer should have port number
ok 190 peer should have suggested timeout
[39m
[36mok 191 peer should have a connection type
ok 192 connection type should match one of the pre-defined types
[39m
[36mok 193 peer should have a non-empty identifier
ok 194 host address should be null
[39m
[36mok 195 port number should be null
[39m
[36mok 196 peer should have suggested timeout
[39m
[36mok 197 peer should have a connection type
[39m
[36mok 198 connection type should match one of the pre-defined types
ok 199 port number must match
ok 200 peer should have a non-empty identifier
[39m
[36mok 201 peer should have a non-empty host address
[39m
[36mok 202 peer should have port number
ok 203 peer should have suggested timeout
[39m
[36mok 204 peer should have a connection type
[39m
[36mok 205 connection type should match one of the pre-defined types
[39m
[36m# teardown
[39m
[32mok 206 error should be null
ok 207 error should be null
# setup
[39m
[33mok 206 error should be null
[39m
[33mok 207 error should be null
[39m
[33m# setup
[39m
[36mok 206 error should be null
ok 207 error should be null
# setup
[39m
2016-08-10T13:13:52.030Z - info: Running on ios test: 57. when network connection is lost a peer should be marked unavailable

[32m# 57. when network connection is lost a peer should be marked unavailable
[39m
[33m# 57. when network connection is lost a peer should be marked unavailable
[39m
[36m# 57. when network connection is lost a peer should be marked unavailable
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51102
INFO testUtils: Toggling radios to: false
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[32mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[32mok 208 peer should have a non-empty identifier
ok 209 host address should be null
ok 210 port number should be null
ok 211 peer should have suggested timeout
ok 212 peer should have a connection type
[39m
[32mok 213 connection type should match one of the pre-defined types
[39m
[32mINFO testUtils: Toggling radios to: true
[39m
[32mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[32m# teardown
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG createNativeListener: listening 51104
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51106
[39m
[33mINFO testUtils: Toggling radios to: false
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mINFO testUtils: Toggling radios to: false
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 208 peer should have a non-empty identifier
ok 209 host address should be null
ok 210 port number should be null
ok 211 peer should have suggested timeout
ok 212 peer should have a connection type
ok 213 connection type should match one of the pre-defined types
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mINFO testUtils: Toggling radios to: true
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 208 peer should have a non-empty identifier
ok 209 host address should be null
ok 210 port number should be null
ok 211 peer should have suggested timeout
ok 212 peer should have a connection type
ok 213 connection type should match one of the pre-defined types
INFO testUtils: Toggling radios to: true
[39m
[33m# teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
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
[33mok 214 error should be null
ok 215 error should be null
# setup
[39m
[36mok 214 error should be null
[39m
[36mok 215 error should be null
[39m
[36m# setup
[39m
2016-08-10T13:13:52.072Z - info: Running on ios test: 58. peer should be found once after listening and discovery started

[32m# 58. peer should be found once after listening and discovery started
[39m
[33m# 58. peer should be found once after listening and discovery started
[39m
[36m# 58. peer should be found once after listening and discovery started
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51109
ok 216 error should be null
ok 217 error should be null
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 218 error should be null
ok 219 error should be null
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 220 error should be null
ok 221 error should be null
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51110
ok 216 error should be null
ok 217 error should be null
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51118
ok 216 error should be null
ok 217 error should be null
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 218 error should be null
ok 219 error should be null
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[33mok 220 error should be null
[39m
[33mok 221 error should be null
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
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
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
ok 222 peer should have a non-empty identifier
ok 223 peer should have a non-empty host address
ok 224 peer should have port number
[39m
[33mok 225 peer should have suggested timeout
ok 226 peer should have a connection type
ok 227 connection type should match one of the pre-defined types
[39m
[36mok 222 peer should have a non-empty identifier
[39m
[36mok 223 peer should have a non-empty host address
[39m
[36mok 224 peer should have port number
[39m
[36mok 225 peer should have suggested timeout
[39m
[36mok 226 peer should have a connection type
[39m
[36mok 227 connection type should match one of the pre-defined types
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mnot ok 228 must not receive too many peer availabilities
  ---
    operator: ok
    expected: true
    actual:   false
    at: null._onTimeout (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js:521:9)
  ...
[39m
[33mnot ok 228 must not receive too many peer availabilities
  ---
    operator: ok
    expected: true
    actual:   false
    at: null._onTimeout (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js:521:9)
  ...
# teardown
[39m
[32m# teardown
[39m
[36mnot ok 228 must not receive too many peer availabilities
  ---
    operator: ok
    expected: true
    actual:   false
    at: null._onTimeout (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js:521:9)
[39m
[36m  ...
# teardown
[39m
[32mINFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[36mINFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[32mok 229 error should be null
ok 230 error should be null
# setup
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
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
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mok 229 error should be null
ok 230 error should be null
# setup
[39m
2016-08-10T13:13:55.630Z - warn: Failed on ios test: 58. peer should be found once after listening and discovery started
2016-08-10T13:13:55.630Z - info: Running on ios test: 59. can get data from all participants

[36m# 59. can get data from all participants
[39m
[32m# 59. can get data from all participants
[39m
[33m# 59. can get data from all participants
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: listening 51129
[39m
[36mok 231 error should be null
ok 232 error should be null
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 233 error should be null
ok 234 error should be null
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51133
ok 231 error should be null
ok 232 error should be null
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 233 error should be null
ok 234 error should be null
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 235 error should be null
ok 236 error should be null
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: listening 51139
[39m
[33mok 231 error should be null
[39m
[33mok 232 error should be null
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[33mok 233 error should be null
[39m
[33mok 234 error should be null
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[33mok 235 error should be null
[39m
[33mok 236 error should be null
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[32mDEBUG createPeerListener: first connection
[39m
[36mok 235 error should be null
[39m
[36mok 236 error should be null
[39m
[33mDEBUG createNativeListener: new incoming socket
[39m
[33mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createNativeListener: new mux
[39m
[32mDEBUG createPeerListener: first connection
[39m
[33mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[32mok 237 received uuid must be in remaining list
[39m
[32mok 238 received uuid must be in remaining list
ok 239 received all uuids
[39m
[32m# teardown
[39m
[33mok 237 received uuid must be in remaining list
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: first connection
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
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
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
[36mDEBUG createPeerListener: forward connection
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mok 238 received uuid must be in remaining list
[39m
[33mok 239 received all uuids
[39m
[33m# teardown
[39m
[36mok 237 received uuid must be in remaining list
[39m
[36mok 238 received uuid must be in remaining list
[39m
[36mok 239 received all uuids
[39m
[36m# teardown
[39m
[32mINFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
[39m
[32mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[33mINFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
[39m
[32mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[33mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[33mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: mux close
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: mux close
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: mux close
[39m
[32mok 240 error should be null
[39m
[32mok 241 error should be null
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[33mDEBUG createNativeListener: mux close
[39m
[33mok 240 error should be null
[39m
[33mok 241 error should be null
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[32m# setup
[39m
[33m# setup
[39m
[36mDEBUG createPeerListener: Recreating listener
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createPeerListener: Recreating listener
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mINFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
[39m
[36mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[36mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: mux close
[39m
[36mok 240 error should be null
[39m
[36mok 241 error should be null
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[36m# setup
[39m
2016-08-10T13:13:56.333Z - info: Running on ios test: 60. Can call start/stopListeningForAdvertisements

[33m# 60. Can call start/stopListeningForAdvertisements
[39m
[32m# 60. Can call start/stopListeningForAdvertisements
[39m
[36m# 60. Can call start/stopListeningForAdvertisements
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[32mok 242 Can call startListeningForAdvertisements without error
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[32mok 243 Can call stopListeningForAdvertisements without error
[39m
[33mok 242 Can call startListeningForAdvertisements without error
[39m
[32m# teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mok 243 Can call stopListeningForAdvertisements without error
[39m
[33m# teardown
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 242 Can call startListeningForAdvertisements without error
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[36mok 243 Can call stopListeningForAdvertisements without error
[39m
[36m# teardown
[39m
[32mok 244 Should be able to call stopListeningForAdvertisements in teardown
[39m
[33mok 244 Should be able to call stopListeningForAdvertisements in teardown
ok 245 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[32mok 245 Should be able to call stopAdvertisingAndListening in teardown
[39m
[32m# setup
[39m
[36mok 244 Should be able to call stopListeningForAdvertisements in teardown
[39m
[36mok 245 Should be able to call stopAdvertisingAndListening in teardown
[39m
[36m# setup
[39m
2016-08-10T13:13:56.362Z - info: Running on ios test: 61. Calling startListeningForAdvertisements twice is NOT an error

[32m# 61. Calling startListeningForAdvertisements twice is NOT an error
[39m
[33m# 61. Calling startListeningForAdvertisements twice is NOT an error
[39m
[36m# 61. Calling startListeningForAdvertisements twice is NOT an error
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 246 Can call startListeningForAdvertisements without error
[39m
[32mok 247 Can call startListeningForAdvertisements twice without error
[39m
[32m# teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[33mok 246 Can call startListeningForAdvertisements without error
[39m
[33mok 247 Can call startListeningForAdvertisements twice without error
[39m
[33m# teardown
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[36mok 246 Can call startListeningForAdvertisements without error
[39m
[36mok 247 Can call startListeningForAdvertisements twice without error
[39m
[36m# teardown
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 248 Should be able to call stopListeningForAdvertisements in teardown
ok 249 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 248 Should be able to call stopListeningForAdvertisements in teardown
ok 249 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 248 Should be able to call stopListeningForAdvertisements in teardown
[39m
[36mok 249 Should be able to call stopAdvertisingAndListening in teardown
[39m
[36m# setup
[39m
2016-08-10T13:13:56.394Z - info: Running on ios test: 62. Calling stopListeningForAdvertisements without calling start is NOT an error

[32m# 62. Calling stopListeningForAdvertisements without calling start is NOT an error
[39m
[33m# 62. Calling stopListeningForAdvertisements without calling start is NOT an error
[39m
[36m# 62. Calling stopListeningForAdvertisements without calling start is NOT an error
[39m
[33mok 250 Can call stopListeningForAdvertisements without error
ok 251 Can call stopListeningForAdvertisements without error
# teardown
[39m
[32mok 250 Can call stopListeningForAdvertisements without error
ok 251 Can call stopListeningForAdvertisements without error
# teardown
[39m
[36mok 250 Can call stopListeningForAdvertisements without error
ok 251 Can call stopListeningForAdvertisements without error
# teardown
[39m
[32mok 252 Should be able to call stopListeningForAdvertisements in teardown
ok 253 Should be able to call stopAdvertisingAndListening in teardown
[39m
[32m# setup
[39m
[33mok 252 Should be able to call stopListeningForAdvertisements in teardown
ok 253 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[36mok 252 Should be able to call stopListeningForAdvertisements in teardown
[39m
[36mok 253 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
2016-08-10T13:13:56.425Z - info: Running on ios test: 63. Can call start/stopUpdateAdvertisingAndListening

[32m# 63. Can call start/stopUpdateAdvertisingAndListening
[39m
[33m# 63. Can call start/stopUpdateAdvertisingAndListening
[39m
[36m# 63. Can call start/stopUpdateAdvertisingAndListening
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 254 Can call startUpdateAdvertisingAndListening without error
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 255 Can call stopAdvertisingAndListening without error
# teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 254 Can call startUpdateAdvertisingAndListening without error
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mok 255 Can call stopAdvertisingAndListening without error
[39m
[33m# teardown
[39m
[36mok 254 Can call startUpdateAdvertisingAndListening without error
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 255 Can call stopAdvertisingAndListening without error
[39m
[36m# teardown
[39m
[32mok 256 Should be able to call stopListeningForAdvertisements in teardown
[39m
[32mok 257 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[33mok 256 Should be able to call stopListeningForAdvertisements in teardown
ok 257 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[36mok 256 Should be able to call stopListeningForAdvertisements in teardown
ok 257 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
2016-08-10T13:13:56.461Z - info: Running on ios test: 64. Calling startUpdateAdvertisingAndListening twice is NOT an error

[32m# 64. Calling startUpdateAdvertisingAndListening twice is NOT an error
[39m
[33m# 64. Calling startUpdateAdvertisingAndListening twice is NOT an error
[39m
[36m# 64. Calling startUpdateAdvertisingAndListening twice is NOT an error
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 258 Can call startUpdateAdvertisingAndListening without error
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 258 Can call startUpdateAdvertisingAndListening without error
[39m
[32mok 259 Can call startUpdateAdvertisingAndListening twice without error
# teardown
[39m
[36mok 259 Can call startUpdateAdvertisingAndListening twice without error
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
[32mok 260 Should be able to call stopListeningForAdvertisements in teardown
[39m
[36mok 260 Should be able to call stopListeningForAdvertisements in teardown
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 261 Should be able to call stopAdvertisingAndListening in teardown
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[32m# setup
[39m
[36mok 261 Should be able to call stopAdvertisingAndListening in teardown
[39m
[36m# setup
[39m
[33mok 260 Should be able to call stopListeningForAdvertisements in teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 261 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
2016-08-10T13:13:56.503Z - info: Running on ios test: 65. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error

[32m# 65. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
[39m
[36m# 65. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
[39m
[33m# 65. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
[39m
[36mok 262 Can call startUpdateAdvertisingAndListening without error
ok 263 Can call stopAdvertisingAndListening without error
# teardown
[39m
[32mok 262 Can call startUpdateAdvertisingAndListening without error
[39m
[32mok 263 Can call stopAdvertisingAndListening without error
[39m
[32m# teardown
[39m
[33mok 262 Can call startUpdateAdvertisingAndListening without error
ok 263 Can call stopAdvertisingAndListening without error
# teardown
[39m
[32mok 264 Should be able to call stopListeningForAdvertisements in teardown
ok 265 Should be able to call stopAdvertisingAndListening in teardown
[39m
[32m# setup
[39m
[36mok 264 Should be able to call stopListeningForAdvertisements in teardown
ok 265 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[33mok 264 Should be able to call stopListeningForAdvertisements in teardown
[39m
[33mok 265 Should be able to call stopAdvertisingAndListening in teardown
[39m
[33m# setup
[39m
2016-08-10T13:13:56.537Z - info: Running on ios test: 66. cannot call connect when start listening for advertisements is not active

[32m# 66. cannot call connect when start listening for advertisements is not active
[39m
[36m# 66. cannot call connect when start listening for advertisements is not active
[39m
[33m# 66. cannot call connect when start listening for advertisements is not active
[39m
[32mok 266 got right error
# teardown
[39m
[36mok 266 got right error
# teardown
[39m
[33mok 266 got right error
[39m
[33m# teardown
[39m
[33mok 267 Should be able to call stopListeningForAdvertisements in teardown
ok 268 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[32mok 267 Should be able to call stopListeningForAdvertisements in teardown
[39m
[32mok 268 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[36mok 267 Should be able to call stopListeningForAdvertisements in teardown
[39m
[36mok 268 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
2016-08-10T13:13:56.565Z - info: Running on ios test: 67. peerAvailabilityChange is called

[33m# 67. peerAvailabilityChange is called
[39m
[32m# 67. peerAvailabilityChange is called
[39m
[36m# 67. peerAvailabilityChange is called
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 269 Can call startUpdateAdvertisingAndListeningwithout error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 270 Can call startListeningForAdvertisements without error
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 269 Can call startUpdateAdvertisingAndListeningwithout error
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[36mok 270 Can call startListeningForAdvertisements without error
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[33mok 271 peers must be an array
ok 272 peers must not be zero-length
ok 273 peer must have peerIdentifier
ok 274 peerIdentifier must be a string
ok 275 peer must have peerAvailable
[39m
[33mok 276 peer must have pleaseConnect
[39m
[32mok 269 Can call startUpdateAdvertisingAndListeningwithout error
[39m
[33m# teardown
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 270 Can call startListeningForAdvertisements without error
[39m
[36mok 271 peers must be an array
ok 272 peers must not be zero-length
ok 273 peer must have peerIdentifier
ok 274 peerIdentifier must be a string
ok 275 peer must have peerAvailable
[39m
[36mok 276 peer must have pleaseConnect
[39m
[36m# teardown
[39m
[32mok 271 peers must be an array
[39m
[32mok 272 peers must not be zero-length
ok 273 peer must have peerIdentifier
ok 274 peerIdentifier must be a string
[39m
[32mok 275 peer must have peerAvailable
[39m
[32mok 276 peer must have pleaseConnect
[39m
[32m# teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 277 Should be able to call stopListeningForAdvertisements in teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mok 278 Should be able to call stopAdvertisingAndListening in teardown
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[36mok 277 Should be able to call stopListeningForAdvertisements in teardown
[39m
[33m# setup
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 278 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 277 Should be able to call stopListeningForAdvertisements in teardown
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 278 Should be able to call stopAdvertisingAndListening in teardown
[39m
[32m# setup
[39m
2016-08-10T13:13:57.095Z - info: Running on ios test: 68. Can connect to a remote peer

[33m# 68. Can connect to a remote peer
[39m
[36m# 68. Can connect to a remote peer
[39m
[32m# 68. Can connect to a remote peer
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 279 Can call startUpdateAdvertisingAndListening without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 280 Can call startListeningForAdvertisements without error
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 279 Can call startUpdateAdvertisingAndListening without error
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[33mok 280 Can call startListeningForAdvertisements without error
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:f9b1967e-a814-4893-8328-f8e0d15b2493","peerAvailable":true,"pleaseConnect":false}]
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[32mok 279 Can call startUpdateAdvertisingAndListening without error
[39m
[33mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 280 Can call startListeningForAdvertisements without error
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:f956b2eb-3898-4791-aeea-4f599ea3146c","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:f956b2eb-3898-4791-aeea-4f599ea3146c","peerAvailable":true,"pleaseConnect":false}]
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mINFO testThaliMobileNative: 
[39m
[36mok 281 Must have listeningPort
[39m
[36mok 282 listeningPort must be a number
ok 283 Connection must have clientPort
[39m
[36mok 284 clientPort must be a number
[39m
[36mok 285 Connection must have serverPort
ok 286 serverPort must be a number
ok 287 forward connection must have clientPort == 0
ok 288 forward connection must have serverPort == 0
[39m
[36m# teardown
[39m
[33mINFO testThaliMobileNative: 
ok 281 Must have listeningPort
[39m
[33mok 282 listeningPort must be a number
[39m
[33mok 283 Connection must have clientPort
ok 284 clientPort must be a number
[39m
[33mok 285 Connection must have serverPort
ok 286 serverPort must be a number
[39m
[33mok 287 forward connection must have clientPort == 0
ok 288 forward connection must have serverPort == 0
# teardown
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a790b0e0-7a0d-4b0f-8a60-4d6cb4e0d615","peerAvailable":true,"pleaseConnect":false}]
[39m
[32mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a790b0e0-7a0d-4b0f-8a60-4d6cb4e0d615","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:f9b1967e-a814-4893-8328-f8e0d15b2493","peerAvailable":true,"pleaseConnect":false}]
[39m
[32mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:f9b1967e-a814-4893-8328-f8e0d15b2493","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:f956b2eb-3898-4791-aeea-4f599ea3146c","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:f956b2eb-3898-4791-aeea-4f599ea3146c","peerAvailable":true,"pleaseConnect":false}]
[39m
[32mINFO testThaliMobileNative: 
ok 281 Must have listeningPort
[39m
[32mok 282 listeningPort must be a number
ok 283 Connection must have clientPort
ok 284 clientPort must be a number
ok 285 Connection must have serverPort
ok 286 serverPort must be a number
ok 287 forward connection must have clientPort == 0
ok 288 forward connection must have serverPort == 0
# teardown
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 289 Should be able to call stopListeningForAdvertisements in teardown
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 289 Should be able to call stopListeningForAdvertisements in teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[33mok 289 Should be able to call stopListeningForAdvertisements in teardown
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 290 Should be able to call stopAdvertisingAndListening in teardown
[39m
[32m# setup
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 290 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 290 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
2016-08-10T13:13:57.732Z - info: Running on ios test: 69. Get error when trying to double connect to a peer

[33m# 69. Get error when trying to double connect to a peer
[39m
[36m# 69. Get error when trying to double connect to a peer
[39m
[32m# 69. Get error when trying to double connect to a peer
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 291 Can call startUpdateAdvertisingAndListening without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 292 Can call startListeningForAdvertisements without error
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 291 Can call startUpdateAdvertisingAndListening without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 292 Can call startListeningForAdvertisements without error
[39m
[33mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[32mok 291 Can call startUpdateAdvertisingAndListening without error
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 292 Can call startListeningForAdvertisements without error
[39m
[33mok 293 Expected error
[39m
[33mok 294 Null connection as expected
[39m
[33mok 295 Expected error
ok 296 Null connection as expected
[39m
[33m# teardown
[39m
[36mok 293 Expected error
ok 294 Null connection as expected
ok 295 Expected error
ok 296 Null connection as expected
[39m
[36m# teardown
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mok 293 Expected error
ok 294 Null connection as expected
ok 295 Expected error
ok 296 Null connection as expected
# teardown
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 297 Should be able to call stopListeningForAdvertisements in teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 297 Should be able to call stopListeningForAdvertisements in teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 298 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 297 Should be able to call stopListeningForAdvertisements in teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 298 Should be able to call stopAdvertisingAndListening in teardown
[39m
[32m# setup
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 298 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
2016-08-10T13:13:58.362Z - info: Running on ios test: 70. Connect port dies if not connected to in time

[36m# 70. Connect port dies if not connected to in time
[39m
[33m# 70. Connect port dies if not connected to in time
[39m
[32m# 70. Connect port dies if not connected to in time
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
[33mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[32mok 299 Can call startUpdateAdvertisingAndListening without error
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 300 Can call startListeningForAdvertisements without error
[39m
[33mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mok 301 failed correctly due to refused connection
[39m
[33m# teardown
[39m
[36mok 301 failed correctly due to refused connection
[39m
[36m# teardown
[39m
[32mok 301 failed correctly due to refused connection
[39m
[32m# teardown
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 302 Should be able to call stopListeningForAdvertisements in teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 303 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 302 Should be able to call stopListeningForAdvertisements in teardown
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 303 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 302 Should be able to call stopListeningForAdvertisements in teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 303 Should be able to call stopAdvertisingAndListening in teardown
[39m
[33m# setup
[39m
2016-08-10T13:14:02.008Z - info: Running on ios test: 71. Can shift large amounts of data

[36m# 71. Can shift large amounts of data
[39m
[33m# 71. Can shift large amounts of data
[39m
[32m# 71. Can shift large amounts of data
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 304 Can call startUpdateAdvertisingAndListening without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 305 Can call startListeningForAdvertisements without error
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 304 Can call startUpdateAdvertisingAndListening without error
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 305 Can call startListeningForAdvertisements without error
[39m
[33mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[32mok 304 Can call startUpdateAdvertisingAndListening without error
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[32mok 305 Can call startListeningForAdvertisements without error
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mINFO testThaliMobileNative: 
INFO testThaliMobileNative: Forward connection
[39m
[33mINFO testThaliMobileNative: 
INFO testThaliMobileNative: Forward connection
[39m
[36mINFO testThaliMobileNative: forwardSend
[39m
[33mINFO testThaliMobileNative: forwardSend
[39m
[36mINFO testThaliMobileNative: forwardData
ok 306 received should match sent forward
# teardown
[39m
[33mINFO testThaliMobileNative: forwardData
ok 306 received should match sent forward
# teardown
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mINFO testThaliMobileNative: 
[39m
[32mINFO testThaliMobileNative: Forward connection
[39m
[32mINFO testThaliMobileNative: forwardSend
[39m
[32mINFO testThaliMobileNative: forwardData
[39m
[32mok 306 received should match sent forward
[39m
[32m# teardown
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 307 Should be able to call stopListeningForAdvertisements in teardown
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 307 Should be able to call stopListeningForAdvertisements in teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 307 Should be able to call stopListeningForAdvertisements in teardown
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 308 Should be able to call stopAdvertisingAndListening in teardown
[39m
[33m# setup
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[36mok 308 Should be able to call stopAdvertisingAndListening in teardown
[39m
[32mok 308 Should be able to call stopAdvertisingAndListening in teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:02.661Z - info: Running on ios test: 72. #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection

[33m# 72. #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
[39m
[36m# 72. #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
[39m
[32m# 72. #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[33mok 309 Can call startUpdateAdvertisingAndListening without error
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[36mok 309 Can call startUpdateAdvertisingAndListening without error
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[33mok 310 Can call startListeningForAdvertisements without error
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[36mok 310 Can call startListeningForAdvertisements without error
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:35a6eacb-38c7-4013-9a09-30a7b04086c7","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[32mok 309 Can call startUpdateAdvertisingAndListening without error
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[32mok 310 Can call startListeningForAdvertisements without error
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:8a8e48c0-7e90-4ed5-b7d2-1756a8791730","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:8a8e48c0-7e90-4ed5-b7d2-1756a8791730","peerAvailable":true,"pleaseConnect":false}]
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mINFO testThaliMobileNative: connection {"listeningPort":51292,"clientPort":0,"serverPort":0}
[39m
[33mINFO testThaliMobileNative: connection to listening port is made
[39m
[36mINFO testThaliMobileNative: connection {"listeningPort":51298,"clientPort":0,"serverPort":0}
[39m
[36mok 311 Data matches
[39m
[36mINFO testThaliMobileNative: connection to listening port is made
[39m
[33mok 311 Data matches
[39m
[32mok 311 Data matches
[39m
[33mok 312 We got the close message and we are closed
[39m
[36mok 312 Data matches
[39m
[33mok 313 We got an error which is what we wanted
[39m
[36mok 313 We got the close message and we are closed
[39m
[36mok 314 We got an error which is what we wanted
[39m
[36m# teardown
[39m
[33m# teardown
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:35a6eacb-38c7-4013-9a09-30a7b04086c7","peerAvailable":true,"pleaseConnect":false}]
[39m
[32mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:35a6eacb-38c7-4013-9a09-30a7b04086c7","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a1ac7977-297e-4c10-9c4c-88189444d358","peerAvailable":true,"pleaseConnect":false}]
[39m
[32mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a1ac7977-297e-4c10-9c4c-88189444d358","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:8a8e48c0-7e90-4ed5-b7d2-1756a8791730","peerAvailable":true,"pleaseConnect":false}]
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:8a8e48c0-7e90-4ed5-b7d2-1756a8791730","peerAvailable":true,"pleaseConnect":false}]
[39m
[32mINFO testThaliMobileNative: connection {"listeningPort":51305,"clientPort":0,"serverPort":0}
INFO testThaliMobileNative: connection to listening port is made
[39m
[36mok 315 Data matches
[39m
[32mok 312 Data matches
[39m
[32mok 313 We got the close message and we are closed
[39m
[32mok 314 We got an error which is what we wanted
[39m
[32m# teardown
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 316 Should be able to call stopListeningForAdvertisements in teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 314 Should be able to call stopListeningForAdvertisements in teardown
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 317 Should be able to call stopAdvertisingAndListening in teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 315 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[36m# setup
[39m
[32mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a1ac7977-297e-4c10-9c4c-88189444d358","peerAvailable":false,"pleaseConnect":false}]
[39m
[32mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:35a6eacb-38c7-4013-9a09-30a7b04086c7","peerAvailable":false,"pleaseConnect":false}]
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 315 Should be able to call stopListeningForAdvertisements in teardown
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[32mok 316 Should be able to call stopAdvertisingAndListening in teardown
[39m
[32m# setup
[39m
2016-08-10T13:14:03.301Z - info: Running on ios test: 73. #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection

[36m# 73. #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
[39m
[33m# 73. #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
[39m
[32m# 73. #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 318 Can call startUpdateAdvertisingAndListening without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 319 Can call startListeningForAdvertisements without error
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 316 Can call startUpdateAdvertisingAndListening without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 317 Can call startListeningForAdvertisements without error
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:6a678a77-0494-4aae-a3ae-0b2100f15df5","peerAvailable":true,"pleaseConnect":false}]
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:2666920a-1741-433c-a8c8-46940c70cac7","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[32mok 317 Can call startUpdateAdvertisingAndListening without error
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[32mok 318 Can call startListeningForAdvertisements without error
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:68243ca6-ec3d-4619-b6f9-0412f16e7d85","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:68243ca6-ec3d-4619-b6f9-0412f16e7d85","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: connection {"listeningPort":51316,"clientPort":0,"serverPort":0}
[39m
[36mINFO testThaliMobileNative: connection to listening port is made
[39m
[33mINFO testThaliMobileNative: connection {"listeningPort":51318,"clientPort":0,"serverPort":0}
[39m
[33mok 318 Data matches
INFO testThaliMobileNative: connection to listening port is made
[39m
[36mok 320 Data matches
[39m
[36mok 321 Data matches
[39m
[36mok 322 We got the close message and we are closed
[39m
[36mok 323 We got an error which is what we wanted
[39m
[33mok 319 Data matches
[39m
[36m# teardown
[39m
[33mok 320 We got the close message and we are closed
[39m
[33mok 321 We got an error which is what we wanted
[39m
[33m# teardown
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:2666920a-1741-433c-a8c8-46940c70cac7","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:6a678a77-0494-4aae-a3ae-0b2100f15df5","peerAvailable":true,"pleaseConnect":false}]
[39m
[32mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:2666920a-1741-433c-a8c8-46940c70cac7","peerAvailable":true,"pleaseConnect":false}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:6a678a77-0494-4aae-a3ae-0b2100f15df5","peerAvailable":true,"pleaseConnect":false}]
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:68243ca6-ec3d-4619-b6f9-0412f16e7d85","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:68243ca6-ec3d-4619-b6f9-0412f16e7d85","peerAvailable":true,"pleaseConnect":false}]
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mINFO testThaliMobileNative: connection {"listeningPort":51330,"clientPort":0,"serverPort":0}
[39m
[32mINFO testThaliMobileNative: connection to listening port is made
[39m
[36mok 324 Data matches
[39m
[32mok 319 Data matches
[39m
[32mok 320 We got the close message and we are closed
[39m
[32mok 321 We got an error which is what we wanted
[39m
[32m# teardown
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 325 Should be able to call stopListeningForAdvertisements in teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 326 Should be able to call stopAdvertisingAndListening in teardown
[39m
[36m# setup
[39m
[33mok 322 Should be able to call stopListeningForAdvertisements in teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 323 Should be able to call stopAdvertisingAndListening in teardown
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 322 Should be able to call stopListeningForAdvertisements in teardown
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 323 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[33m# setup
[39m
2016-08-10T13:14:03.945Z - info: Running on ios test: 74. #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer

[36m# 74. #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
[39m
[33m# 74. #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
[39m
[32m# 74. #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 327 Can call startUpdateAdvertisingAndListening without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 328 Can call startListeningForAdvertisements without error
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 324 Can call startUpdateAdvertisingAndListening without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 325 Can call startListeningForAdvertisements without error
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 324 Can call startUpdateAdvertisingAndListening without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 325 Can call startListeningForAdvertisements without error
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:ce64dbb3-67d1-4920-ad15-cf111badc301","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:ce64dbb3-67d1-4920-ad15-cf111badc301","peerAvailable":true,"pleaseConnect":false}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:28c1b5f2-c6d4-4b97-b50b-f79c733a822d","peerAvailable":true,"pleaseConnect":false}]
[39m
[32mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:28c1b5f2-c6d4-4b97-b50b-f79c733a822d","peerAvailable":true,"pleaseConnect":false}]
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mINFO testThaliMobileNative: connection {"listeningPort":51349,"clientPort":0,"serverPort":0}
INFO testThaliMobileNative: connection to listening port is made
[39m
[33mINFO testThaliMobileNative: connection {"listeningPort":51345,"clientPort":0,"serverPort":0}
[39m
[36mINFO testThaliMobileNative: connection {"listeningPort":51347,"clientPort":0,"serverPort":0}
[39m
[36mINFO testThaliMobileNative: connection to listening port is made
[39m
[33mINFO testThaliMobileNative: connection to listening port is made
[39m
[32mok 326 Data matches
[39m
[33mok 326 Data matches
[39m
[36mok 329 Data matches
[39m
[32mok 327 Data matches
ok 328 Data matches
[39m
[36mok 330 We got the close message and we are closed
[39m
[32mok 329 We got the close message and we are closed
[39m
[36mDEBUG wifiBasedNativeMock: got an end on peerProxySockets
[39m
[32mDEBUG wifiBasedNativeMock: got an end on peerProxySockets
[39m
[36mok 331 We got an error which is what we wanted
# teardown
[39m
[33mok 327 Data matches
ok 328 We got the close message and we are closed
[39m
[33mDEBUG wifiBasedNativeMock: got an end on peerProxySockets
[39m
[32mok 330 We got an error which is what we wanted
[39m
[33mok 329 We got an error which is what we wanted
[39m
[32m# teardown
[39m
[33m# teardown
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 332 Should be able to call stopListeningForAdvertisements in teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 330 Should be able to call stopListeningForAdvertisements in teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 331 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 331 Should be able to call stopListeningForAdvertisements in teardown
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[36mok 333 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 332 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
2016-08-10T13:14:04.096Z - info: Running on ios test: 75. #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer

[36m# 75. #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
[39m
[33m# 75. #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
[39m
[32m# 75. #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 334 Can call startUpdateAdvertisingAndListening without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 335 Can call startListeningForAdvertisements without error
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 332 Can call startUpdateAdvertisingAndListening without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 333 Can call startListeningForAdvertisements without error
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:09692bf9-f4ce-498c-97e6-9d84ead849e8","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:4e8a07f6-4a7b-48fe-b922-6805e044172f","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 333 Can call startUpdateAdvertisingAndListening without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 334 Can call startListeningForAdvertisements without error
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:b0244c10-faad-4448-ae18-033a4d874d64","peerAvailable":true,"pleaseConnect":false}]
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:b0244c10-faad-4448-ae18-033a4d874d64","peerAvailable":true,"pleaseConnect":false}]
[39m
[33mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mINFO testThaliMobileNative: connection {"listeningPort":51367,"clientPort":0,"serverPort":0}
[39m
[36mINFO testThaliMobileNative: connection {"listeningPort":51371,"clientPort":0,"serverPort":0}
[39m
[33mINFO testThaliMobileNative: connection to listening port is made
[39m
[36mINFO testThaliMobileNative: connection to listening port is made
[39m
[36mok 336 Data matches
[39m
[33mok 334 Data matches
[39m
[33mok 335 Data matches
[39m
[33mDEBUG wifiBasedNativeMock: got an end on peerProxySockets
[39m
[33mok 336 We got the close message and we are closed
[39m
[36mok 337 Data matches
[39m
[33mok 337 We got an error which is what we wanted
[39m
[33m# teardown
[39m
[36mDEBUG wifiBasedNativeMock: got an end on peerProxySockets
[39m
[36mok 338 We got the close message and we are closed
[39m
[36mok 339 We got an error which is what we wanted
[39m
[36m# teardown
[39m
[32mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:09692bf9-f4ce-498c-97e6-9d84ead849e8","peerAvailable":true,"pleaseConnect":false}]
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:09692bf9-f4ce-498c-97e6-9d84ead849e8","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:4e8a07f6-4a7b-48fe-b922-6805e044172f","peerAvailable":true,"pleaseConnect":false}]
[39m
[32mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:4e8a07f6-4a7b-48fe-b922-6805e044172f","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:b0244c10-faad-4448-ae18-033a4d874d64","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:b0244c10-faad-4448-ae18-033a4d874d64","peerAvailable":true,"pleaseConnect":false}]
[39m
[32mINFO testThaliMobileNative: connection {"listeningPort":51380,"clientPort":0,"serverPort":0}
[39m
[32mINFO testThaliMobileNative: connection to listening port is made
[39m
[36mok 340 Data matches
[39m
[32mok 335 Data matches
[39m
[32mDEBUG wifiBasedNativeMock: got an end on peerProxySockets
[39m
[32mok 336 We got the close message and we are closed
ok 337 We got an error which is what we wanted
# teardown
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 341 Should be able to call stopListeningForAdvertisements in teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 338 Should be able to call stopListeningForAdvertisements in teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 339 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[32mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:4e8a07f6-4a7b-48fe-b922-6805e044172f","peerAvailable":false,"pleaseConnect":false}]
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 338 Should be able to call stopListeningForAdvertisements in teardown
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 339 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 342 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
2016-08-10T13:14:04.732Z - info: Running on ios test: 76. We do not emit peerAvailabilityChanged events until one of the start methods is called

[36m# 76. We do not emit peerAvailabilityChanged events until one of the start methods is called
[39m
[33m# 76. We do not emit peerAvailabilityChanged events until one of the start methods is called
[39m
[32m# 76. We do not emit peerAvailabilityChanged events until one of the start methods is called
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 340 We should start listening fine
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 341 We should start updating fine
# teardown
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 343 We should start listening fine
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 344 We should start updating fine
# teardown
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bd2836f1-2fa0-4b6a-ab36-e360746cfe3a","peerAvailable":true,"pleaseConnect":false}]
[39m
[32mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:67927209-1db2-4911-90cf-322db5c62e2a","peerAvailable":true,"pleaseConnect":false}]
[39m
[32mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:67927209-1db2-4911-90cf-322db5c62e2a","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bd2836f1-2fa0-4b6a-ab36-e360746cfe3a","peerAvailable":true,"pleaseConnect":false}]
[39m
[32mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:67927209-1db2-4911-90cf-322db5c62e2a","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bd2836f1-2fa0-4b6a-ab36-e360746cfe3a","peerAvailable":true,"pleaseConnect":false}]
[39m
[32mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:67927209-1db2-4911-90cf-322db5c62e2a","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bd2836f1-2fa0-4b6a-ab36-e360746cfe3a","peerAvailable":true,"pleaseConnect":false}]
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 340 Ready to advertise
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 341 Ready to listen
[39m
[32mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:6af64b47-53b0-45a0-be80-78f82d0f2698","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:6af64b47-53b0-45a0-be80-78f82d0f2698","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bd2836f1-2fa0-4b6a-ab36-e360746cfe3a","peerAvailable":true,"pleaseConnect":false}]
[39m
[32mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:67927209-1db2-4911-90cf-322db5c62e2a","peerAvailable":true,"pleaseConnect":false}]
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 342 stop ads worked
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:6af64b47-53b0-45a0-be80-78f82d0f2698","peerAvailable":false,"pleaseConnect":false}]
[39m
[32mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:6af64b47-53b0-45a0-be80-78f82d0f2698","peerAvailable":false,"pleaseConnect":false}]
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 343 test stop worked
[39m
[32mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:67927209-1db2-4911-90cf-322db5c62e2a","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bd2836f1-2fa0-4b6a-ab36-e360746cfe3a","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bd2836f1-2fa0-4b6a-ab36-e360746cfe3a","peerAvailable":true,"pleaseConnect":false}]
[39m
[32mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:67927209-1db2-4911-90cf-322db5c62e2a","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bd2836f1-2fa0-4b6a-ab36-e360746cfe3a","peerAvailable":true,"pleaseConnect":false}]
[39m
[32mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:67927209-1db2-4911-90cf-322db5c62e2a","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bd2836f1-2fa0-4b6a-ab36-e360746cfe3a","peerAvailable":true,"pleaseConnect":false}]
[39m
[32mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:67927209-1db2-4911-90cf-322db5c62e2a","peerAvailable":true,"pleaseConnect":false}]
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bd2836f1-2fa0-4b6a-ab36-e360746cfe3a","peerAvailable":true,"pleaseConnect":false}]
[39m
[32mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:67927209-1db2-4911-90cf-322db5c62e2a","peerAvailable":true,"pleaseConnect":false}]
[39m
[33m# teardown
[39m
[36mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bd2836f1-2fa0-4b6a-ab36-e360746cfe3a","peerAvailable":true,"pleaseConnect":false}]
[39m
[32mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:67927209-1db2-4911-90cf-322db5c62e2a","peerAvailable":true,"pleaseConnect":false}]
[39m
[33mok 344 Should be able to call stopListeningForAdvertisements in teardown
ok 345 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 345 Should be able to call stopListeningForAdvertisements in teardown
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 346 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[32mINFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:67927209-1db2-4911-90cf-322db5c62e2a","peerAvailable":false,"pleaseConnect":false}]
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 342 Should be able to call stopListeningForAdvertisements in teardown
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[32mok 343 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
2016-08-10T13:14:09.769Z - info: Running on ios test: 77. Test updating advertising and parallel data transfer

[36m# 77. Test updating advertising and parallel data transfer
[39m
[33m# 77. Test updating advertising and parallel data transfer
[39m
[32m# 77. Test updating advertising and parallel data transfer
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 346 Can call startUpdateAdvertisingAndListening without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 347 Can call startListeningForAdvertisements without error
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 347 Can call startUpdateAdvertisingAndListening without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 348 Can call startListeningForAdvertisements without error
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 344 Can call startUpdateAdvertisingAndListening without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 345 Can call startListeningForAdvertisements without error
[39m
[33mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG testThaliMobileNative: serverRound: Message written, closing socket (calling socket.end)
[39m
[36mDEBUG testThaliMobileNative: serverRound: Message written, closing socket (calling socket.end)
[39m
[32mDEBUG testThaliMobileNative: serverRound: Message written, closing socket (calling socket.end)
[39m
[33mDEBUG testThaliMobileNative: Response validated, calling connection.end
[39m
[36mDEBUG testThaliMobileNative: Response validated, calling connection.end
[39m
[32mDEBUG testThaliMobileNative: serverRound: Message written, closing socket (calling socket.end)
[39m
[36mDEBUG testThaliMobileNative: Response validated, calling connection.end
[39m
[33mDEBUG testThaliMobileNative: Response validated, calling connection.end
[39m
[33mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG testThaliMobileNative: serverRound: Message written, closing socket (calling socket.end)
[39m
[36mDEBUG testThaliMobileNative: serverRound: Message written, closing socket (calling socket.end)
[39m
[33mDEBUG testThaliMobileNative: We made it through round one
[39m
[33mok 348 Round 1 ready
[39m
[36mDEBUG testThaliMobileNative: We made it through round one
[39m
[36mok 349 Round 1 ready
[39m
[33mDEBUG wifiBasedNativeMock: proxy socket connected
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG testThaliMobileNative: Response validated, calling connection.end
[39m
[32mDEBUG testThaliMobileNative: Response validated, calling connection.end
DEBUG testThaliMobileNative: We made it through round one
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mok 346 Round 1 ready
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG testThaliMobileNative: serverRound: Message written, closing socket (calling socket.end)
[39m
[32mDEBUG testThaliMobileNative: serverRound: Message written, closing socket (calling socket.end)
[39m
[33mDEBUG testThaliMobileNative: serverRound: Message written, closing socket (calling socket.end)
[39m
[32mDEBUG testThaliMobileNative: serverRound: Message written, closing socket (calling socket.end)
[39m
[33mDEBUG testThaliMobileNative: Response validated, calling connection.end
[39m
[36mDEBUG testThaliMobileNative: Response validated, calling connection.end
[39m
[36mDEBUG testThaliMobileNative: Response validated, calling connection.end
[39m
[33mDEBUG testThaliMobileNative: Response validated, calling connection.end
[39m
[32mINFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
[39m
[32mINFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
[39m
[33mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG testThaliMobileNative: serverRound: Message written, closing socket (calling socket.end)
[39m
[36mDEBUG testThaliMobileNative: serverRound: Message written, closing socket (calling socket.end)
[39m
[33m# teardown
[39m
[36m# teardown
[39m
[32mDEBUG testThaliMobileNative: Response validated, calling connection.end
[39m
[32mDEBUG testThaliMobileNative: Response validated, calling connection.end
[39m
[32m# teardown
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 350 Should be able to call stopListeningForAdvertisements in teardown
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 351 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[33mok 349 Should be able to call stopListeningForAdvertisements in teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mok 350 Should be able to call stopAdvertisingAndListening in teardown
[39m
[33m# setup
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[32mok 347 Should be able to call stopListeningForAdvertisements in teardown
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 348 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
2016-08-10T13:14:14.032Z - info: Running on ios test: 78. #startListeningForAdvertisements should fail if start not called

[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 78. #startListeningForAdvertisements should fail if start not called
[39m
[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 78. #startListeningForAdvertisements should fail if start not called
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
[32m# 78. #startListeningForAdvertisements should fail if start not called
[39m
[36mok 352 specific error should be returned
# teardown
[39m
[33mok 351 specific error should be returned
# teardown
[39m
[32mok 349 specific error should be returned
[39m
[32m# teardown
[39m
[36mok 353 must be stopped
# setup
[39m
[33mok 352 must be stopped
# setup
[39m
[32mok 350 must be stopped
[39m
[32m# setup
[39m
2016-08-10T13:14:14.059Z - info: Running on ios test: 79. #startUpdateAdvertisingAndListening should fail if start not called

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
[32m# 79. #startUpdateAdvertisingAndListening should fail if start not called
[39m
[33mok 353 specific error should be returned
# teardown
[39m
[36mok 354 specific error should be returned
# teardown
[39m
[32mok 351 specific error should be returned
[39m
[32m# teardown
[39m
[36mok 355 must be stopped
# setup
[39m
[33mok 354 must be stopped
# setup
[39m
[32mok 352 must be stopped
[39m
[32m# setup
[39m
2016-08-10T13:14:14.084Z - info: Running on ios test: 80. should be able to call #stopListeningForAdvertisements many times

[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 80. should be able to call #stopListeningForAdvertisements many times
[39m
[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 80. should be able to call #stopListeningForAdvertisements many times
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
[32m# 80. should be able to call #stopListeningForAdvertisements many times
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51455
ok 356 no errors
ok 357 still no errors
# teardown
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51457
[39m
[33mok 355 no errors
[39m
[33mok 356 still no errors
[39m
[33m# teardown
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: listening 51459
[39m
[32mok 353 no errors
[39m
[32mok 354 still no errors
[39m
[32m# teardown
[39m
[36mok 358 must be stopped
# setup
[39m
[33mok 357 must be stopped
# setup
[39m
[32mok 355 must be stopped
[39m
[32m# setup
[39m
2016-08-10T13:14:14.118Z - info: Running on ios test: 81. should be able to call #startListeningForAdvertisements many times

[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 81. should be able to call #startListeningForAdvertisements many times
[39m
[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 81. should be able to call #startListeningForAdvertisements many times
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
[32m# 81. should be able to call #startListeningForAdvertisements many times
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51463
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 359 no errors
ok 360 still no errors
# teardown
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51462
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 358 no errors
ok 359 still no errors
# teardown
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: listening 51465
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[32mok 356 no errors
[39m
[32mok 357 still no errors
[39m
[32m# teardown
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 361 must be stopped
[39m
[36m# setup
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mok 360 must be stopped
[39m
[33m# setup
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[32mok 358 must be stopped
# setup
[39m
2016-08-10T13:14:14.159Z - info: Running on ios test: 82. should be able to call #startUpdateAdvertisingAndListening many times

[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[33m# 82. should be able to call #startUpdateAdvertisingAndListening many times
[39m
[36mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 82. should be able to call #startUpdateAdvertisingAndListening many times
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
[32m# 82. should be able to call #startUpdateAdvertisingAndListening many times
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51468
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 362 no errors
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51469
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 361 no errors
[39m
[36mok 363 still no errors
# teardown
[39m
[33mok 362 still no errors
[39m
[33m# teardown
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: listening 51475
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[32mok 359 no errors
[39m
[32mok 360 still no errors
[39m
[32m# teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[36mok 364 must be stopped
[39m
[36m# setup
[39m
[33mok 363 must be stopped
[39m
[33m# setup
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[32mok 361 must be stopped
[39m
[32m# setup
[39m
2016-08-10T13:14:14.205Z - info: Running on ios test: 83. should be able to call #stopAdvertisingAndListening many times

[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[36m# 83. should be able to call #stopAdvertisingAndListening many times
[39m
[33mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[33m# 83. should be able to call #stopAdvertisingAndListening many times
[39m
[32mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[32mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[32m# 83. should be able to call #stopAdvertisingAndListening many times
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: listening 51480
[39m
[33mDEBUG createNativeListener: listening 51481
[39m
[33mok 364 no errors
[39m
[36mok 365 no errors
[39m
[33mok 365 still no errors
[39m
[33m# teardown
[39m
[36mok 366 still no errors
[39m
[36m# teardown
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: listening 51483
[39m
[32mok 362 no errors
[39m
[32mok 363 still no errors
[39m
[32m# teardown
[39m
[36mok 367 must be stopped
[39m
[36m# setup
[39m
[33mok 366 must be stopped
[39m
[33m# setup
[39m
[32mok 364 must be stopped
[39m
[32m# setup
[39m
2016-08-10T13:14:14.245Z - info: Running on ios test: 84. can get the network status before starting

[32mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[36m# 84. can get the network status before starting
[39m
[32mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[33m# 84. can get the network status before starting
[39m
[32mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[32mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[32m# 84. can get the network status before starting
[39m
[36mok 368 network status should have certain non-empty properties
[39m
[36m# teardown
[39m
[33mok 367 network status should have certain non-empty properties
[39m
[33m# teardown
[39m
[32mok 365 network status should have certain non-empty properties
[39m
[32m# teardown
[39m
[36mok 369 must be stopped
# setup
[39m
[33mok 368 must be stopped
# setup
[39m
[32mok 366 must be stopped
# setup
[39m
2016-08-10T13:14:14.274Z - info: Running on ios test: 85. error returned with bad router

[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 85. error returned with bad router
[39m
[36mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 85. error returned with bad router
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
# 85. error returned with bad router
[39m
[36mERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
ok 370 specific error expected
# teardown
[39m
[33mERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
ok 369 specific error expected
[39m
[33m# teardown
[39m
[32mERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
ok 367 specific error expected
# teardown
[39m
[36mok 371 must be stopped
# setup
[39m
[33mok 370 must be stopped
# setup
[39m
[32mok 368 must be stopped
[39m
[32m# setup
[39m
2016-08-10T13:14:14.304Z - info: Running on ios test: 86. all services are stopped when we call stop

[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 86. all services are stopped when we call stop
[39m
[33mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 86. all services are stopped when we call stop
[39m
[32mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[32mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 86. all services are stopped when we call stop
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51486
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51487
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[33mok 371 connection to servers manager should succeed after starting
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[33mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[36mDEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[36mok 372 connection to servers manager should succeed after starting
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[33mok 372 connection to router server should succeed after starting
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[36mok 373 connection to router server should succeed after starting
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[33mok 373 is stopped after calling stop
[39m
[36mDEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
[39m
[33mok 374 connection to servers manager should fail after stopping
[39m
[33mok 375 connection to router server should fail after stopping
[39m
[33m# teardown
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[36mok 374 is stopped after calling stop
[39m
[36mok 375 connection to servers manager should fail after stopping
ok 376 connection to router server should fail after stopping
[39m
[36m# teardown
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51503
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[32mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[32mok 369 connection to servers manager should succeed after starting
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[32mok 370 connection to router server should succeed after starting
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[32mok 371 is stopped after calling stop
[39m
[32mok 372 connection to servers manager should fail after stopping
[39m
[32mok 373 connection to router server should fail after stopping
[39m
[32m# teardown
[39m
[36mok 377 must be stopped
# setup
[39m
[33mok 376 must be stopped
# setup
[39m
[32mok 374 must be stopped
[39m
[32m# setup
[39m
2016-08-10T13:14:14.371Z - info: Running on ios test: 87. make sure terminateConnection is properly hooked up

[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 87. make sure terminateConnection is properly hooked up
[39m
[33mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 87. make sure terminateConnection is properly hooked up
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
# 87. make sure terminateConnection is properly hooked up
[39m
[36mok 378 called with right arguments
# teardown
[39m
[33mok 377 called with right arguments
[39m
[33m# teardown
[39m
[32mok 375 called with right arguments
# teardown
[39m
[36mok 379 must be stopped
[39m
[36m# setup
[39m
[33mok 378 must be stopped
# setup
[39m
[32mok 376 must be stopped
# setup
[39m
2016-08-10T13:14:14.402Z - info: Running on ios test: 88. make sure terminateListener is properly hooked up

[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 88. make sure terminateListener is properly hooked up
[39m
[36mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[36m# 88. make sure terminateListener is properly hooked up
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
# 88. make sure terminateListener is properly hooked up
[39m
[36mok 380 called with right arguments
# teardown
[39m
[32mok 377 called with right arguments
[39m
[32m# teardown
[39m
[33mok 379 called with right arguments
[39m
[33m# teardown
[39m
[33mok 380 must be stopped
# setup
[39m
[36mok 381 must be stopped
# setup
[39m
[32mok 378 must be stopped
# setup
[39m
2016-08-10T13:14:14.431Z - info: Running on ios test: 89. make sure we actually call kill connections properly

[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[33m# 89. make sure we actually call kill connections properly
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
# 89. make sure we actually call kill connections properly
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
[36m# 89. make sure we actually call kill connections properly
[39m
[33mok 381 specific error expected
# teardown
[39m
[32mok 379 specific error expected
# teardown
[39m
[36mok 382 specific error expected
[39m
[36m# teardown
[39m
[33mok 382 must be stopped
# setup
[39m
[32mok 380 must be stopped
[39m
[32m# setup
[39m
[36mok 383 must be stopped
# setup
[39m
2016-08-10T13:14:14.482Z - info: Running on ios test: 90. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received

[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[32mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 90. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
[39m
[32mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[32mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 90. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
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
# 90. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51512
INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":51511,"error":{}}
ok 381 failure reason is as expected
ok 382 error description is as expected
ok 383 must be stopped
# teardown
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51513
INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":51510,"error":{}}
ok 383 failure reason is as expected
ok 384 error description is as expected
ok 385 must be stopped
# teardown
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51515
INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":51514,"error":{}}
[39m
[36mok 384 failure reason is as expected
ok 385 error description is as expected
ok 386 must be stopped
[39m
[36m# teardown
[39m
[33mok 386 must be stopped
# setup
[39m
[36mok 387 must be stopped
# setup
[39m
[32mok 384 must be stopped
[39m
[32m# setup
[39m
2016-08-10T13:14:14.521Z - info: Running on ios test: 91. We repeat failedConnection event when we get it from thaliTcpServersManager

[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 91. We repeat failedConnection event when we get it from thaliTcpServersManager
[39m
[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[36m# 91. We repeat failedConnection event when we get it from thaliTcpServersManager
[39m
[32mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 91. We repeat failedConnection event when we get it from thaliTcpServersManager
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51518
ok 387 peerIdentifier matches
ok 388 error description matches
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51519
ok 388 peerIdentifier matches
[39m
[33m# teardown
[39m
[36mok 389 error description matches
[39m
[36m# teardown
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: listening 51521
[39m
[32mok 385 peerIdentifier matches
ok 386 error description matches
# teardown
[39m
[33mok 389 must be stopped
# setup
[39m
[36mok 390 must be stopped
[39m
[36m# setup
[39m
[32mok 387 must be stopped
[39m
[32m# setup
[39m
2016-08-10T13:14:14.554Z - info: Running on ios test: 92. can do HTTP requests between peers without coordinator

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
[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[33m# 92. can do HTTP requests between peers without coordinator
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
[32m# 92. can do HTTP requests between peers without coordinator
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51523
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG testUtils: We got a peer {"peerIdentifier":"foo","portNumber":51528,"hostAddress":"127.0.0.1"}
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51526
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[33mWARN testUtils: Retry count for getSamePeerWithRetry is 1
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: first connection
[39m
[36mDEBUG testUtils: We got a peer {"peerIdentifier":"foo","portNumber":51532,"hostAddress":"127.0.0.1"}
[39m
[36mWARN testUtils: Retry count for getSamePeerWithRetry is 1
[39m
[33mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: listening 51543
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
DEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG testUtils: We got a peer {"peerIdentifier":"foo","portNumber":51546,"hostAddress":"127.0.0.1"}
[39m
[32mWARN testUtils: Retry count for getSamePeerWithRetry is 1
[39m
[32mDEBUG createPeerListener: first connection
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG createPeerListener: forward connection
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mok 390 Should only get expected id
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[33mok 391 response body should match testData
[39m
[33m# teardown
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mok 391 Should only get expected id
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[36mok 392 response body should match testData
[39m
[36m# teardown
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mok 388 Should only get expected id
[39m
[32mok 389 response body should match testData
[39m
[32m# teardown
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: mux close
[39m
[33mDEBUG createNativeListener: mux close
[39m
[36mok 393 must be stopped
[39m
[33mok 392 must be stopped
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[36m# setup
[39m
[33m# setup
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: mux close
[39m
[32mok 390 must be stopped
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[32m# setup
[39m
2016-08-10T13:14:14.751Z - info: Running on ios test: 93. make sure bad PSK connections fail

[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[33m# 93. make sure bad PSK connections fail
[39m
[36m# 93. make sure bad PSK connections fail
[39m
[32mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 93. make sure bad PSK connections fail
[39m
[36mok 394 FIX ME, PLEASE!!!
[39m
[36m# teardown
[39m
[32mok 391 FIX ME, PLEASE!!!
[39m
[32m# teardown
[39m
[33mok 393 FIX ME, PLEASE!!!
# teardown
[39m
[36mok 395 must be stopped
# setup
[39m
[33mok 394 must be stopped
[39m
[33m# setup
[39m
[32mok 392 must be stopped
[39m
[32m# setup
[39m
2016-08-10T13:14:14.785Z - info: Running on ios test: 94. peer changes handled from a queue

[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[32mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[32mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[32m# 94. peer changes handled from a queue
[39m
[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[33m# 94. peer changes handled from a queue
[39m
[36mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[36m# 94. peer changes handled from a queue
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: listening 51561
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createNativeListener: listening 51563
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
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
[36mDEBUG createPeerListener: pleaseConnect= false
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
[33mok 395 peers were handled in the right order
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[33m# teardown
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createNativeListener: listening 51580
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
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
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mok 396 peers were handled in the right order
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36m# teardown
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mok 393 peers were handled in the right order
[39m
[32m# teardown
[39m
[36mok 397 must be stopped
[39m
[36m# setup
[39m
[33mok 396 must be stopped
[39m
[33m# setup
[39m
[32mok 394 must be stopped
[39m
[32m# setup
[39m
2016-08-10T13:14:14.854Z - info: Running on ios test: 95. relaying discoveryAdvertisingStateUpdateNonTCP

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
[33m# 95. relaying discoveryAdvertisingStateUpdateNonTCP
[39m
[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[32mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[36m# 95. relaying discoveryAdvertisingStateUpdateNonTCP
[39m
[32mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[32m# 95. relaying discoveryAdvertisingStateUpdateNonTCP
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: listening 51597
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[33mok 397 discovery is active
ok 398 advertising is active
[39m
[33m# teardown
[39m
[36mDEBUG createNativeListener: listening 51598
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[36mok 398 discovery is active
[39m
[36mok 399 advertising is active
[39m
[36m# teardown
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: listening 51600
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 395 discovery is active
ok 396 advertising is active
[39m
[32m# teardown
[39m
[36mok 400 must be stopped
# setup
[39m
[33mok 399 must be stopped
# setup
[39m
[32mok 397 must be stopped
# setup
[39m
2016-08-10T13:14:14.890Z - info: Running on ios test: 96. thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received

[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[36m# 96. thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
[39m
[33mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[33m# 96. thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
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
# 96. thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51603
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: 51603
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51604
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: 51604
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 401 right error reason
ok 402 Stop should be fine
ok 403 same port
ok 404 we should be off
# teardown
[39m
[33mok 400 right error reason
ok 401 Stop should be fine
ok 402 same port
ok 403 we should be off
[39m
[33m# teardown
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: listening 51610
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[32mINFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: 51610
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[32mok 398 right error reason
ok 399 Stop should be fine
ok 400 same port
ok 401 we should be off
# teardown
[39m
[33mok 404 must be stopped
# setup
[39m
[36mok 405 must be stopped
# setup
[39m
[32mok 402 must be stopped
# setup
[39m
2016-08-10T13:14:14.936Z - info: Running on ios test: 97. we successfully receive and replay discoveryAdvertisingStateUpdate

[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 97. we successfully receive and replay discoveryAdvertisingStateUpdate
[39m
[36mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[36m# 97. we successfully receive and replay discoveryAdvertisingStateUpdate
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
[32m# 97. we successfully receive and replay discoveryAdvertisingStateUpdate
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51615
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 406 discoveryActive matches
ok 407 advertisingActive matches
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 408 discoveryActive matches
ok 409 advertisingActive matches
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51618
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 410 discoveryActive matches
ok 411 advertisingActive matches
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51616
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 405 discoveryActive matches
ok 406 advertisingActive matches
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 407 discoveryActive matches
ok 408 advertisingActive matches
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51620
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 409 discoveryActive matches
ok 410 advertisingActive matches
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[36mok 412 discoveryActive matches
ok 413 advertisingActive matches
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 411 discoveryActive matches
ok 412 advertisingActive matches
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51626
[39m
[36m# teardown
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: listening 51628
# teardown
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: listening 51630
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[32mok 403 discoveryActive matches
ok 404 advertisingActive matches
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 405 discoveryActive matches
[39m
[32mok 406 advertisingActive matches
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51632
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 407 discoveryActive matches
[39m
[32mok 408 advertisingActive matches
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[32mok 409 discoveryActive matches
ok 410 advertisingActive matches
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: listening 51636
[39m
[32m# teardown
[39m
[36mok 414 must be stopped
# setup
[39m
[33mok 413 must be stopped
# setup
[39m
[32mok 411 must be stopped
[39m
[32m# setup
[39m
2016-08-10T13:14:14.998Z - info: Running on ios test: 98. can do HTTP requests between peers

[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[36m# 98. can do HTTP requests between peers
[39m
[33m# 98. can do HTTP requests between peers
[39m
[32mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 98. can do HTTP requests between peers
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51638
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51640
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG testUtils: We got a peer {"peerIdentifier":"urn:uuid:d98dc30c-c128-4028-aa7b-79b5dd653efe","portNumber":51645,"hostAddress":"127.0.0.1"}
WARN testUtils: Retry count for getSamePeerWithRetry is 1
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: listening 51648
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[33mDEBUG createPeerListener: first connection
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG testUtils: We got a peer {"peerIdentifier":"urn:uuid:18449f2a-435c-4260-ba4d-c1e3eda38583","portNumber":51654,"hostAddress":"127.0.0.1"}
[39m
[36mWARN testUtils: Retry count for getSamePeerWithRetry is 1
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
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
[39m
[33mDEBUG createNativeListener: new mux
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[36mok 415 Should only get expected id
[39m
[33mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[33mok 414 Should only get expected id
[39m
[33mok 415 response body should match testData
ok 416 must be started
[39m
[33m# teardown
[39m
[36mok 416 response body should match testData
[39m
[36mok 417 must be started
[39m
[36m# teardown
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG testUtils: We got a peer {"peerIdentifier":"urn:uuid:d98dc30c-c128-4028-aa7b-79b5dd653efe","portNumber":51665,"hostAddress":"127.0.0.1"}
[39m
[32mWARN testUtils: Retry count for getSamePeerWithRetry is 1
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
DEBUG createNativeListener: new outgoing socket
[39m
[36mok 418 Should only get expected id
[39m
[32mok 412 response body should match testData
ok 413 must be started
[39m
[32m# teardown
[39m
[33mDEBUG createPeerListener: Recreating listener
DEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
[39m
[36mok 419 must be stopped
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: mux close
[39m
[36m# setup
[39m
[33mok 417 must be stopped
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[33m# setup
[39m
[32mDEBUG createPeerListener: Recreating listener
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[32mok 414 must be stopped
# setup
[39m
2016-08-10T13:14:15.681Z - info: Running on ios test: 99. can still do HTTP requests between peers

[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[33m# 99. can still do HTTP requests between peers
[39m
[36mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[36m# 99. can still do HTTP requests between peers
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
[32m# 99. can still do HTTP requests between peers
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51677
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51678
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG testUtils: We got a peer {"peerIdentifier":"urn:uuid:369df199-f347-46ce-a2e5-f3463eb4f7bf","portNumber":51683,"hostAddress":"127.0.0.1"}
WARN testUtils: Retry count for getSamePeerWithRetry is 1
DEBUG createPeerListener: first connection
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG testUtils: We got a peer {"peerIdentifier":"urn:uuid:906c3b9a-cd2b-4ffd-a4d4-2f5c8a84b67a","portNumber":51685,"hostAddress":"127.0.0.1"}
WARN testUtils: Retry count for getSamePeerWithRetry is 1
DEBUG createPeerListener: first connection
[39m
[33mDEBUG createNativeListener: new incoming socket
[39m
[33mDEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: listening 51694
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mok 418 Should only get expected id
[39m
[36mok 420 Should only get expected id
[39m
[33mok 419 response body should match testData
ok 420 must be started
[39m
[36mok 421 response body should match testData
ok 422 must be started
[39m
[33m# teardown
[39m
[36m# teardown
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG testUtils: We got a peer {"peerIdentifier":"urn:uuid:369df199-f347-46ce-a2e5-f3463eb4f7bf","portNumber":51703,"hostAddress":"127.0.0.1"}
[39m
[32mWARN testUtils: Retry count for getSamePeerWithRetry is 1
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: first connection
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
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mok 421 Should only get expected id
[39m
[32mok 415 response body should match testData
[39m
[32mok 416 must be started
[39m
[32m# teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[32mDEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
[39m
[32mok 417 must be stopped
[39m
[32m# setup
[39m
[33mDEBUG createNativeListener: mux close
[39m
[36mok 423 must be stopped
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[33mok 422 must be stopped
[39m
[33mDEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-10T13:14:16.357Z - info: Running on ios test: 100. test to coordinate connection cut

[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
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
[32mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 100. test to coordinate connection cut
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
# teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
# teardown
[39m
[32mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[32m# teardown
[39m
[33mok 423 must be stopped
# setup
[39m
[36mok 424 must be stopped
# setup
[39m
[32mok 418 must be stopped
# setup
[39m
2016-08-10T13:14:16.380Z - info: Running on ios test: 101. can do HTTP requests after connections are cut

[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 101. can do HTTP requests after connections are cut
[39m
[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 101. can do HTTP requests after connections are cut
[39m
[32mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[32m# 101. can do HTTP requests after connections are cut
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51713
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51714
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG testUtils: We got a peer {"peerIdentifier":"urn:uuid:50f32d38-1803-47ee-a89e-2c945689db17","portNumber":51719,"hostAddress":"127.0.0.1"}
WARN testUtils: Retry count for getSamePeerWithRetry is 1
DEBUG createPeerListener: first connection
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG testUtils: We got a peer {"peerIdentifier":"urn:uuid:0b8e0b48-6d79-41ba-96fe-7c94f44b112e","portNumber":51720,"hostAddress":"127.0.0.1"}
WARN testUtils: Retry count for getSamePeerWithRetry is 1
[39m
[36mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: listening 51729
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[36mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[33mDEBUG createNativeListener: new incoming socket
[39m
[33mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createNativeListener: new mux
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[33mDEBUG createPeerListener: forward connection
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mok 425 Should only get expected id
[39m
[33mok 424 Should only get expected id
[39m
[33mok 425 response body should match testData
[39m
[33mok 426 must be started
[39m
[33m# teardown
[39m
[36mok 426 response body should match testData
[39m
[36mok 427 must be started
[39m
[36m# teardown
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG testUtils: We got a peer {"peerIdentifier":"urn:uuid:50f32d38-1803-47ee-a89e-2c945689db17","portNumber":51739,"hostAddress":"127.0.0.1"}
WARN testUtils: Retry count for getSamePeerWithRetry is 1
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
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[36mok 428 Should only get expected id
[39m
[32mok 419 response body should match testData
[39m
[32mok 420 must be started
[39m
[32m# teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 421 must be stopped
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
[39m
[33mok 427 must be stopped
[39m
[36mDEBUG createNativeListener: mux close
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[32m# setup
[39m
[36mok 429 must be stopped
[39m
[36mDEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T13:14:17.037Z - info: Running on ios test: 102. will fail bad PSK connection between peers

[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[32mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[32m# 102. will fail bad PSK connection between peers
[39m
[33mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 102. will fail bad PSK connection between peers
[39m
[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 102. will fail bad PSK connection between peers
[39m
[33mok 428 FIX ME, PLEASE!!!
# teardown
[39m
[32mok 422 FIX ME, PLEASE!!!
[39m
[32m# teardown
[39m
[36mok 430 FIX ME, PLEASE!!!
[39m
[36m# teardown
[39m
[33mok 429 must be stopped
# setup
[39m
[32mok 423 must be stopped
[39m
[32m# setup
[39m
[36mok 431 must be stopped
# setup
[39m
2016-08-10T13:14:17.066Z - info: Running on ios test: 103. We provide notification when a listener dies and we recreate it

[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[32mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[33m# 103. We provide notification when a listener dies and we recreate it
[39m
[32mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[32mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[32mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 103. We provide notification when a listener dies and we recreate it
[39m
[36mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[36mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[36m# 103. We provide notification when a listener dies and we recreate it
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51748
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51750
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG testUtils: We got a peer {"peerIdentifier":"urn:uuid:6c4f8b31-80ae-4ead-a7c4-e1cf1ccd1e4a","portNumber":51755,"hostAddress":"127.0.0.1"}
[39m
[32mWARN testUtils: Retry count for getSamePeerWithRetry is 1
[39m
[32mDEBUG createPeerListener: first connection
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG testUtils: We got a peer {"peerIdentifier":"urn:uuid:8fe52af8-6e69-4106-a405-fda65cf2c32a","portNumber":51760,"hostAddress":"127.0.0.1"}
[39m
[33mWARN testUtils: Retry count for getSamePeerWithRetry is 1
[39m
[36mDEBUG createNativeListener: listening 51761
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[33mDEBUG createPeerListener: first connection
[39m
[33mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[33mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG createNativeListener: new mux
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[33mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createPeerListener: forward connection
[39m
[33mok 430 Should only get expected id
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mok 424 Should only get expected id
[39m
[32mok 425 response body should match testData
[39m
[32mok 426 About to destroy connection to peer
[39m
[32mDEBUG wifiBasedNativeMock: got an end on peerProxySockets
DEBUG createPeerListener: Recreating listener
DEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG testUtils: We got a peer {"peerIdentifier":"urn:uuid:6c4f8b31-80ae-4ead-a7c4-e1cf1ccd1e4a","portNumber":51775,"hostAddress":"127.0.0.1"}
WARN testUtils: Retry count for getSamePeerWithRetry is 1
ok 427 same ids
[39m
[33mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createPeerListener: first connection
[39m
[33mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mok 431 response body should match testData
[39m
[33mok 432 About to destroy connection to peer
[39m
[33mDEBUG wifiBasedNativeMock: got an end on peerProxySockets
[39m
[33mDEBUG createPeerListener: Recreating listener
DEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
DEBUG testUtils: We got a peer {"peerIdentifier":"urn:uuid:8fe52af8-6e69-4106-a405-fda65cf2c32a","portNumber":51780,"hostAddress":"127.0.0.1"}
WARN testUtils: Retry count for getSamePeerWithRetry is 1
[39m
[32mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: incoming socket close
[39m
[33mok 433 same ids
[39m
[33mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[33mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[33mok 434 Should only get expected id
[39m
[33mDEBUG createPeerListener: forward connection
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mok 428 recreate - response body should match testData
[39m
[32m# teardown
[39m
[32mok 429 Should only get expected id
[39m
[33mok 435 recreate - response body should match testData
[39m
[33m# teardown
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG testUtils: We got a peer {"peerIdentifier":"urn:uuid:6c4f8b31-80ae-4ead-a7c4-e1cf1ccd1e4a","portNumber":51789,"hostAddress":"127.0.0.1"}
[39m
[36mWARN testUtils: Retry count for getSamePeerWithRetry is 1
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createPeerListener: first connection
[39m
[33mDEBUG wifiBasedNativeMock: proxy socket connected
DEBUG createNativeListener: new incoming socket
[39m
[33mDEBUG createNativeListener: creating incoming mux
[39m
[33mDEBUG createNativeListener: new mux
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[33mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[33mok 436 Should only get expected id
[39m
[36mok 432 response body should match testData
[39m
[36mok 433 About to destroy connection to peer
[39m
[36mDEBUG wifiBasedNativeMock: got an end on peerProxySockets
[39m
[36mDEBUG createPeerListener: Recreating listener
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG testUtils: We got a peer {"peerIdentifier":"urn:uuid:6c4f8b31-80ae-4ead-a7c4-e1cf1ccd1e4a","portNumber":51797,"hostAddress":"127.0.0.1"}
[39m
[36mWARN testUtils: Retry count for getSamePeerWithRetry is 1
[39m
[36mok 434 same ids
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
[36mDEBUG createPeerListener: forward connection
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mok 437 Should only get expected id
[39m
[36mok 435 recreate - response body should match testData
[39m
[36m# teardown
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: mux close
[39m
[36mDEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
[39m
[32mok 430 must be stopped
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[32m# setup
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[36mok 436 must be stopped
[39m
[36m# setup
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
[33mDEBUG createNativeListener: incoming socket close
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mok 438 must be stopped
# setup
[39m
2016-08-10T13:14:17.879Z - info: Running on ios test: 104. Client to server request coordinated

[32m# 104. Client to server request coordinated
[39m
[36m# 104. Client to server request coordinated
[39m
[33m# 104. Client to server request coordinated
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: listening 51807
[39m
[32mok 431 error should be null
ok 432 error should be null
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51808
ok 437 error should be null
ok 438 error should be null
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: listening 51812
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[33mok 439 error should be null
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[32mINFO testThaliNotification: startListeningForAdvertisements
[39m
[33mok 440 error should be null
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
INFO testThaliNotification: startListeningForAdvertisements
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
INFO testThaliNotification: startListeningForAdvertisements
[39m
[32mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
[39m
[33mDEBUG createNativeListener: new mux
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG createPeerListener: first connection
[39m
[32mINFO testThaliNotification: PeerAdvertisesDataForUs:tcp, 192.168.1.20, 192.168.1.20, 51817
[39m
[33mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[32mINFO testThaliNotification: PeerAdvertisesDataForUs:tcp, 192.168.1.20, 192.168.1.20, 51814
[39m
[36mINFO testThaliNotification: PeerAdvertisesDataForUs:tcp, 192.168.1.20, 192.168.1.20, 51817
[39m
[33mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[32mINFO testThaliNotification: PeerAdvertisesDataForUs:MPCF, 127.0.0.1, 127.0.0.1, 51827
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: 
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[32mINFO testThaliNotification: PeerAdvertisesDataForUs:MPCF, 127.0.0.1, 127.0.0.1, 51819
[39m
[36mINFO testThaliNotification: PeerAdvertisesDataForUs:MPCF, 127.0.0.1, 127.0.0.1, 51832
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createPeerListener: error on incoming stream - Error: Channel destroyed
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: 
DEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: 
DEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createPeerListener: error on incoming stream - Error: Channel destroyed
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createPeerListener: error on incoming stream - Error: Channel destroyed
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
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
[36mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
[39m
[33mINFO testThaliNotification: PeerAdvertisesDataForUs:tcp, 192.168.1.20, 192.168.1.20, 51809
[39m
[32mDEBUG createNativeListener: new mux
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: first connection
[39m
[36mINFO testThaliNotification: PeerAdvertisesDataForUs:tcp, 192.168.1.20, 192.168.1.20, 51809
[39m
[36mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mINFO testThaliNotification: PeerAdvertisesDataForUs:tcp, 192.168.1.20, 192.168.1.20, 51814
[39m
[33mDEBUG createPeerListener: forward connection
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[33mINFO testThaliNotification: PeerAdvertisesDataForUs:MPCF, 127.0.0.1, 127.0.0.1, 51855
[39m
[36mINFO testThaliNotification: PeerAdvertisesDataForUs:MPCF, 127.0.0.1, 127.0.0.1, 51853
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: 
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: 
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[33mINFO testThaliNotification: PeerAdvertisesDataForUs:MPCF, 127.0.0.1, 127.0.0.1, 51866
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: 
DEBUG createNativeListener: stream close:
DEBUG createPeerListener: error on incoming stream - Error: Channel destroyed
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createPeerListener: error on incoming stream - Error: Channel destroyed
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createPeerListener: error on incoming stream - Error: Channel destroyed
[39m
[32mINFO testThaliNotification: PeerAdvertisesDataForUs:tcp, 192.168.1.20, 192.168.1.20, 51814
[39m
[32mINFO testThaliNotification: PeerAdvertisesDataForUs:tcp, 192.168.1.20, 192.168.1.20, 51817
[39m
[36mINFO testThaliNotification: PeerAdvertisesDataForUs:tcp, 192.168.1.20, 192.168.1.20, 51809
[39m
[33mINFO testThaliNotification: PeerAdvertisesDataForUs:tcp, 192.168.1.20, 192.168.1.20, 51809
[39m
[36mINFO testThaliNotification: PeerAdvertisesDataForUs:tcp, 192.168.1.20, 192.168.1.20, 51817
[39m
[33mINFO testThaliNotification: PeerAdvertisesDataForUs:tcp, 192.168.1.20, 192.168.1.20, 51814
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 441 Peer made successful https requests to all peers
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mok 442 Peer received right amount of https requests
ok 443 HTTPS server received zero PSK Identities. Count:0
DEBUG createPeerListener: Recreating listener
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: Recreating listener
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
# teardown
[39m
[32mok 433 Peer made successful https requests to all peers
ok 434 Peer received right amount of https requests
ok 435 HTTPS server received zero PSK Identities. Count:0
DEBUG createPeerListener: Recreating listener
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: Recreating listener
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
# teardown
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[36mok 439 Peer made successful https requests to all peers
ok 440 Peer received right amount of https requests
ok 441 HTTPS server received zero PSK Identities. Count:0
[39m
[36mDEBUG createPeerListener: Recreating listener
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createPeerListener: Recreating listener
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[36m# teardown
[39m
[36mINFO testThaliNotification: Participants:3 Peers Replied to us:2 Peers requested to:2
[39m
[33mINFO testThaliNotification: Participants:3 Peers Replied to us:2 Peers requested to:2
DEBUG createNativeListener: mux close
DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
[39m
[32mINFO testThaliNotification: Participants:3 Peers Replied to us:2 Peers requested to:2
[39m
[36mDEBUG createNativeListener: mux close
DEBUG createNativeListener: mux close
[39m
[36m# setup
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createNativeListener: mux close
DEBUG createNativeListener: mux close
# setup
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
2016-08-10T13:14:22.939Z - info: Running on ios test: 105. Test BEACONS_RETRIEVED_AND_PARSED locally

[33m# 105. Test BEACONS_RETRIEVED_AND_PARSED locally
[39m
[32m# 105. Test BEACONS_RETRIEVED_AND_PARSED locally
[39m
[36m# 105. Test BEACONS_RETRIEVED_AND_PARSED locally
[39m
[36mok 442 peerIdentifier should be identifier
ok 443 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 444 good beacon
ok 445 good preAmble
ok 446 public keys match!
ok 447 must return null after successful call
ok 448 Once start returns the action should be in KILLED state
[39m
[32mok 436 peerIdentifier should be identifier
ok 437 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 438 good beacon
ok 439 good preAmble
ok 440 public keys match!
ok 441 must return null after successful call
ok 442 Once start returns the action should be in KILLED state
[39m
[32m# teardown
[39m
[36m# teardown
[39m
[33mok 444 peerIdentifier should be identifier
[39m
[33mok 445 Response should be BEACONS_RETRIEVED_AND_PARSED
[39m
[33mok 446 good beacon
[39m
[33mok 447 good preAmble
[39m
[33mok 448 public keys match!
[39m
[33mok 449 must return null after successful call
ok 450 Once start returns the action should be in KILLED state
[39m
[33m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T13:14:22.987Z - info: Running on ios test: 106. Test HTTP_BAD_RESPONSE locally

[32m# 106. Test HTTP_BAD_RESPONSE locally
[39m
[33m# 106. Test HTTP_BAD_RESPONSE locally
[39m
[36m# 106. Test HTTP_BAD_RESPONSE locally
[39m
[32mok 443 Response should be HTTP_BAD_RESPONSE
ok 444 must return null after successful call
[39m
[32m# teardown
[39m
[36mok 449 Response should be HTTP_BAD_RESPONSE
[39m
[36mok 450 must return null after successful call
[39m
[36m# teardown
[39m
[33mok 451 Response should be HTTP_BAD_RESPONSE
[39m
[33mok 452 must return null after successful call
[39m
[33m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T13:14:23.033Z - info: Running on ios test: 107. Test NETWORK_PROBLEM locally

[32m# 107. Test NETWORK_PROBLEM locally
[39m
[33m# 107. Test NETWORK_PROBLEM locally
[39m
[36m# 107. Test NETWORK_PROBLEM locally
[39m
[32mok 445 Response should be NETWORK_PROBLEM
ok 446 reject reason should be: Could not establish TCP connection
[39m
[32m# teardown
[39m
[33mok 453 Response should be NETWORK_PROBLEM
ok 454 reject reason should be: Could not establish TCP connection
[39m
[33m# teardown
[39m
[36mok 451 Response should be NETWORK_PROBLEM
ok 452 reject reason should be: Could not establish TCP connection
[39m
[36m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T13:14:23.072Z - info: Running on ios test: 108. Call the start two times

[32m# 108. Call the start two times
[39m
[36m# 108. Call the start two times
[39m
[33m# 108. Call the start two times
[39m
[33mok 455 Call start once
[39m
[36mok 453 Call start once
[39m
[32mok 447 Call start once
[39m
[33mok 456 Response should be BEACONS_RETRIEVED_AND_PARSED
[39m
[33mok 457 must return null after successful call.
[39m
[33m# teardown
[39m
[32mok 448 Response should be BEACONS_RETRIEVED_AND_PARSED
[39m
[32mok 449 must return null after successful call.
[39m
[36mok 454 Response should be BEACONS_RETRIEVED_AND_PARSED
[39m
[36mok 455 must return null after successful call.
[39m
[32m# teardown
[39m
[36m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T13:14:23.115Z - info: Running on ios test: 109. Call the kill before calling the start

[36m# 109. Call the kill before calling the start
[39m
[33m# 109. Call the kill before calling the start
[39m
[32m# 109. Call the kill before calling the start
[39m
[36mok 456 Should be Killed
[39m
[33mok 458 Should be Killed
ok 459 Start after killed
[39m
[33m# teardown
[39m
[36mok 457 Start after killed
[39m
[36m# teardown
[39m
[32mok 450 Should be Killed
[39m
[32mok 451 Start after killed
[39m
[32m# teardown
[39m
[33m# setup
[39m
[32m# setup
[39m
[36m# setup
[39m
2016-08-10T13:14:23.155Z - info: Running on ios test: 110. Call the kill immediately after the start

[32m# 110. Call the kill immediately after the start
[39m
[33m# 110. Call the kill immediately after the start
[39m
[36m# 110. Call the kill immediately after the start
[39m
[36mok 458 Should be KILLED
[39m
[32mok 452 Should be KILLED
[39m
[36mok 459 must return null after successful kill
[39m
[32mok 453 must return null after successful kill
[39m
[32m# teardown
[39m
[33mok 460 Should be KILLED
[39m
[33mok 461 must return null after successful kill
[39m
[36m# teardown
[39m
[33m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T13:14:23.193Z - info: Running on ios test: 111. Call the kill while waiting a response from the server

[32m# 111. Call the kill while waiting a response from the server
[39m
[33m# 111. Call the kill while waiting a response from the server
[39m
[36m# 111. Call the kill while waiting a response from the server
[39m
[33mok 462 Should be KILLED
ok 463 must return null after successful kill
[39m
[36mok 460 Should be KILLED
ok 461 must return null after successful kill
[39m
[32mok 454 Should be KILLED
ok 455 must return null after successful kill
[39m
[36m# teardown
[39m
[33m# teardown
[39m
[32m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:25.228Z - info: Running on ios test: 112. Test to exceed the max content size locally

[33m# 112. Test to exceed the max content size locally
[39m
[36m# 112. Test to exceed the max content size locally
[39m
[32m# 112. Test to exceed the max content size locally
[39m
[33mok 464 HTTP_BAD_RESPONSE should be response when content size is exceeded
[39m
[33mok 465 must return null after successful call
[39m
[33m# teardown
[39m
[36mok 462 HTTP_BAD_RESPONSE should be response when content size is exceeded
[39m
[36mok 463 must return null after successful call
[39m
[32mok 456 HTTP_BAD_RESPONSE should be response when content size is exceeded
[39m
[36m# teardown
[39m
[32mok 457 must return null after successful call
[39m
[32m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:25.273Z - info: Running on ios test: 113. Close the server socket while the client is waiting a response from the server. Local test.

[33m# 113. Close the server socket while the client is waiting a response from the server. Local test.
[39m
[36m# 113. Close the server socket while the client is waiting a response from the server. Local test.
[39m
[32m# 113. Close the server socket while the client is waiting a response from the server. Local test.
[39m
[33mok 466 Should be NETWORK_PROBLEM caused closing server socket
ok 467 Should be Could not establish TCP connection
# teardown
[39m
[36mok 464 Should be NETWORK_PROBLEM caused closing server socket
ok 465 Should be Could not establish TCP connection
# teardown
[39m
[32mok 458 Should be NETWORK_PROBLEM caused closing server socket
ok 459 Should be Could not establish TCP connection
# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:27.311Z - info: Running on ios test: 114. Close the client socket while the client is waiting a response from the server. Local test.

[36m# 114. Close the client socket while the client is waiting a response from the server. Local test.
[39m
[33m# 114. Close the client socket while the client is waiting a response from the server. Local test.
[39m
[32m# 114. Close the client socket while the client is waiting a response from the server. Local test.
[39m
[36mok 466 Should be NETWORK_PROBLEM caused closing client socket
ok 467 Should be Could not establish TCP connection
# teardown
[39m
[33mok 468 Should be NETWORK_PROBLEM caused closing client socket
ok 469 Should be Could not establish TCP connection
# teardown
[39m
[32mok 460 Should be NETWORK_PROBLEM caused closing client socket
ok 461 Should be Could not establish TCP connection
# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:29.348Z - info: Running on ios test: 115. #generatePreambleAndBeacons bad args

[36m# 115. #generatePreambleAndBeacons bad args
[39m
[33m# 115. #generatePreambleAndBeacons bad args
[39m
[32m# 115. #generatePreambleAndBeacons bad args
[39m
[33mok 470 publicKeysToNotify cannot be null
ok 471 ecdh for local device cannot be null
ok 472 milliseconds cannot be less than 0
ok 473 milliseconds cannot be 0
ok 474 milliseconds cannot be greater than one_day
# teardown
[39m
[36mok 468 publicKeysToNotify cannot be null
ok 469 ecdh for local device cannot be null
ok 470 milliseconds cannot be less than 0
ok 471 milliseconds cannot be 0
ok 472 milliseconds cannot be greater than one_day
# teardown
[39m
[32mok 462 publicKeysToNotify cannot be null
ok 463 ecdh for local device cannot be null
ok 464 milliseconds cannot be less than 0
ok 465 milliseconds cannot be 0
[39m
[32mok 466 milliseconds cannot be greater than one_day
[39m
[32m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:29.371Z - info: Running on ios test: 116. #generatePreambleAndBeacons empty keys to notify

[33m# 116. #generatePreambleAndBeacons empty keys to notify
[39m
[36m# 116. #generatePreambleAndBeacons empty keys to notify
[39m
[32m# 116. #generatePreambleAndBeacons empty keys to notify
[39m
[36mok 473 should be equal
# teardown
[39m
[32mok 467 should be equal
# teardown
[39m
[33mok 475 should be equal
# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T13:14:29.395Z - info: Running on ios test: 117. #generatePreambleAndBeacons multiple keys to notify

[36m# 117. #generatePreambleAndBeacons multiple keys to notify
[39m
[33m# 117. #generatePreambleAndBeacons multiple keys to notify
[39m
[32m# 117. #generatePreambleAndBeacons multiple keys to notify
[39m
[36mok 474 should be equal
ok 475 should be equal
ok 476 (unnamed assert)
ok 477 should be equal
# teardown
[39m
[33mok 476 should be equal
ok 477 should be equal
ok 478 (unnamed assert)
ok 479 should be equal
# teardown
[39m
[32mok 468 should be equal
[39m
[32mok 469 should be equal
ok 470 (unnamed assert)
ok 471 should be equal
# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:29.432Z - info: Running on ios test: 118. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

[36m# 118. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
[39m
[33m# 118. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
[39m
[32m# 118. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
[39m
[36mok 478 should throw
# teardown
[39m
[32mok 472 should throw
# teardown
[39m
[33mok 480 should throw
# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:29.458Z - info: Running on ios test: 119. #parseBeacons invalid expiration in beaconStreamWithPreAmble

[36m# 119. #parseBeacons invalid expiration in beaconStreamWithPreAmble
[39m
[33m# 119. #parseBeacons invalid expiration in beaconStreamWithPreAmble
[39m
[32m# 119. #parseBeacons invalid expiration in beaconStreamWithPreAmble
[39m
[33mok 481 Preamble expiration must be a 64 bit integer
[39m
[33m# teardown
[39m
[36mok 479 Preamble expiration must be a 64 bit integer
[39m
[36m# teardown
[39m
[32mok 473 Preamble expiration must be a 64 bit integer
[39m
[32m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:29.487Z - info: Running on ios test: 120. #parseBeacons expiration out of range lower

[33m# 120. #parseBeacons expiration out of range lower
[39m
[36m# 120. #parseBeacons expiration out of range lower
[39m
[32m# 120. #parseBeacons expiration out of range lower
[39m
[33mok 482 Expiration out of range
[39m
[33m# teardown
[39m
[36mok 480 Expiration out of range
[39m
[36m# teardown
[39m
[32mok 474 Expiration out of range
[39m
[32m# teardown
[39m
[33m# setup
[39m
[32m# setup
[39m
[36m# setup
[39m
2016-08-10T13:14:29.513Z - info: Running on ios test: 121. #parseBeacons expiration out of range lower

[36m# 121. #parseBeacons expiration out of range lower
[39m
[33m# 121. #parseBeacons expiration out of range lower
[39m
[32m# 121. #parseBeacons expiration out of range lower
[39m
[33mok 483 Expiration out of range
[39m
[33m# teardown
[39m
[36mok 481 Expiration out of range
[39m
[36m# teardown
[39m
[32mok 475 Expiration out of range
[39m
[32m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:29.539Z - info: Running on ios test: 122. #parseBeacons no beacons returns null

[33m# 122. #parseBeacons no beacons returns null
[39m
[36m# 122. #parseBeacons no beacons returns null
[39m
[32m# 122. #parseBeacons no beacons returns null
[39m
[33mok 484 should be equal
[39m
[33m# teardown
[39m
[32mok 476 should be equal
[39m
[32m# teardown
[39m
[36mok 482 should be equal
[39m
[36m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:29.561Z - info: Running on ios test: 123. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

[33m# 123. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
[39m
[36m# 123. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
[39m
[32m# 123. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
[39m
[33mok 485 Malformed encrypted beacon key ID
# teardown
[39m
[36mok 483 Malformed encrypted beacon key ID
# teardown
[39m
[32mok 477 Malformed encrypted beacon key ID
# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:29.584Z - info: Running on ios test: 124. #parseBeacons addressBookCallback fails decrypt

[36m# 124. #parseBeacons addressBookCallback fails decrypt
[39m
[33m# 124. #parseBeacons addressBookCallback fails decrypt
[39m
[32m# 124. #parseBeacons addressBookCallback fails decrypt
[39m
[33mok 486 should be equal
# teardown
[39m
[32mok 478 should be equal
[39m
[32m# teardown
[39m
[36mok 484 should be equal
# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:29.621Z - info: Running on ios test: 125. #parseBeacons addressBookCallback returns no matches

[33m# 125. #parseBeacons addressBookCallback returns no matches
[39m
[36m# 125. #parseBeacons addressBookCallback returns no matches
[39m
[32m# 125. #parseBeacons addressBookCallback returns no matches
[39m
[36mok 485 should be equal
ok 486 should be equal
# teardown
[39m
[33mok 487 should be equal
ok 488 should be equal
# teardown
[39m
[32mok 479 should be equal
[39m
[32mok 480 should be equal
[39m
[32m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:29.654Z - info: Running on ios test: 126. #parseBeacons addressBookCallback returns spurious match

[33m# 126. #parseBeacons addressBookCallback returns spurious match
[39m
[36m# 126. #parseBeacons addressBookCallback returns spurious match
[39m
[32m# 126. #parseBeacons addressBookCallback returns spurious match
[39m
[33mok 489 should be equal
ok 490 should be equal
# teardown
[39m
[36mok 487 should be equal
ok 488 should be equal
# teardown
[39m
[32mok 481 should be equal
ok 482 should be equal
[39m
[32m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:29.691Z - info: Running on ios test: 127. #parseBeacons addressBookCallback returns public key

[36m# 127. #parseBeacons addressBookCallback returns public key
[39m
[32m# 127. #parseBeacons addressBookCallback returns public key
[39m
[33m# 127. #parseBeacons addressBookCallback returns public key
[39m
[33mok 491 right number of calls to address book
ok 492 good preAmble
ok 493 good unencryptedKeyId
ok 494 good beacon
# teardown
[39m
[32mok 483 right number of calls to address book
ok 484 good preAmble
ok 485 good unencryptedKeyId
ok 486 good beacon
# teardown
[39m
[36mok 489 right number of calls to address book
ok 490 good preAmble
ok 491 good unencryptedKeyId
ok 492 good beacon
# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:29.728Z - info: Running on ios test: 128. validate generatePskIdentityField

[33m# 128. validate generatePskIdentityField
[39m
[36m# 128. validate generatePskIdentityField
[39m
[32m# 128. validate generatePskIdentityField
[39m
[33mok 495 decoded buffers match
# teardown
[39m
[32mok 487 decoded buffers match
[39m
[32m# teardown
[39m
[36mok 493 decoded buffers match
[39m
[36m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:29.752Z - info: Running on ios test: 129. validate generatePskSecret

[33m# 129. validate generatePskSecret
[39m
[32m# 129. validate generatePskSecret
[39m
[36m# 129. validate generatePskSecret
[39m
[33mok 496 secrets match
# teardown
[39m
[36mok 494 secrets match
# teardown
[39m
[32mok 488 secrets match
[39m
[32m# teardown
[39m
[33m# setup
[39m
[32m# setup
[39m
[36m# setup
[39m
2016-08-10T13:14:29.780Z - info: Running on ios test: 130. validate generatePskSecrets

[33m# 130. validate generatePskSecrets
[39m
[36m# 130. validate generatePskSecrets
[39m
[32m# 130. validate generatePskSecrets
[39m
[33mok 497 Matching numbers
[39m
[33mok 498 We have an entry!
ok 499 keys match
[39m
[33mok 500 secrets match
[39m
[33mok 501 We have an entry!
ok 502 keys match
ok 503 secrets match
[39m
[33mok 504 We have an entry!
ok 505 keys match
[39m
[33mok 506 secrets match
[39m
[33m# teardown
[39m
[36mok 495 Matching numbers
[39m
[36mok 496 We have an entry!
ok 497 keys match
ok 498 secrets match
[39m
[36mok 499 We have an entry!
[39m
[36mok 500 keys match
[39m
[36mok 501 secrets match
[39m
[36mok 502 We have an entry!
ok 503 keys match
ok 504 secrets match
# teardown
[39m
[32mok 489 Matching numbers
[39m
[32mok 490 We have an entry!
ok 491 keys match
ok 492 secrets match
[39m
[32mok 493 We have an entry!
[39m
[32mok 494 keys match
[39m
[32mok 495 secrets match
[39m
[32mok 496 We have an entry!
[39m
[32mok 497 keys match
ok 498 secrets match
# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T13:14:29.827Z - info: Running on ios test: 131. validate generateBeaconStreamAndSecrets

[36m# 131. validate generateBeaconStreamAndSecrets
[39m
[33m# 131. validate generateBeaconStreamAndSecrets
[39m
[32m# 131. validate generateBeaconStreamAndSecrets
[39m
[36mok 505 Streams have same length
ok 506 matching size
ok 507 keys match
ok 508 secrets match
# teardown
[39m
[33mok 507 Streams have same length
ok 508 matching size
ok 509 keys match
ok 510 secrets match
# teardown
[39m
[32mok 499 Streams have same length
ok 500 matching size
ok 501 keys match
[39m
[32mok 502 secrets match
[39m
[32m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:29.865Z - info: Running on ios test: 132. Add two Peers.

[33m# 132. Add two Peers.
[39m
[36m# 132. Add two Peers.
[39m
[32m# 132. Add two Peers.
[39m
[36mok 509 should be equal
ok 510 should be equal
ok 511 should be equal
ok 512 should be equal
ok 513 should be equal
# teardown
[39m
[33mok 511 should be equal
ok 512 should be equal
ok 513 should be equal
ok 514 should be equal
ok 515 should be equal
# teardown
[39m
[32mok 503 should be equal
ok 504 should be equal
ok 505 should be equal
[39m
[32mok 506 should be equal
ok 507 should be equal
# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:29.903Z - info: Running on ios test: 133. TCP_NATIVE peer loses DNS

[36m# 133. TCP_NATIVE peer loses DNS
[39m
[33m# 133. TCP_NATIVE peer loses DNS
[39m
[32m# 133. TCP_NATIVE peer loses DNS
[39m
[33mok 516 should be equal
ok 517 should be equal
[39m
[33m# teardown
[39m
[36mok 514 should be equal
[39m
[36mok 515 should be equal
[39m
[36m# teardown
[39m
[32mok 508 should be equal
[39m
[32mok 509 should be equal
[39m
[32m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:29.942Z - info: Running on ios test: 134. Received beacons with no values for us

[33m# 134. Received beacons with no values for us
[39m
[36m# 134. Received beacons with no values for us
[39m
[32m# 134. Received beacons with no values for us
[39m
[33mok 518 entry exists
ok 519 entry is resolved
[39m
[33m# teardown
[39m
[36mok 516 entry exists
ok 517 entry is resolved
[39m
[36m# teardown
[39m
[32mok 510 entry exists
ok 511 entry is resolved
[39m
[32m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:30.016Z - info: Running on ios test: 135. Resolves an action locally

[33m# 135. Resolves an action locally
[39m
[32m# 135. Resolves an action locally
[39m
[36m# 135. Resolves an action locally
[39m
[33mok 520 Host address must match
ok 521 suggestedTCPTimeout must match
[39m
[33mok 522 connectionType must match
ok 523 portNumber must match
[39m
[33m# teardown
[39m
[32mok 512 Host address must match
ok 513 suggestedTCPTimeout must match
ok 514 connectionType must match
[39m
[32mok 515 portNumber must match
[39m
[32m# teardown
[39m
[36mok 518 Host address must match
ok 519 suggestedTCPTimeout must match
ok 520 connectionType must match
ok 521 portNumber must match
[39m
[36m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:30.070Z - info: Running on ios test: 136. Resolves an action locally using ThaliPeerPoolDefault

[36m# 136. Resolves an action locally using ThaliPeerPoolDefault
[39m
[33m# 136. Resolves an action locally using ThaliPeerPoolDefault
[39m
[32m# 136. Resolves an action locally using ThaliPeerPoolDefault
[39m
[33mok 524 Host address must match
ok 525 suggestedTCPTimeout must match
ok 526 connectionType must match
ok 527 portNumber must match
[39m
[33m# teardown
[39m
[32mok 516 Host address must match
ok 517 suggestedTCPTimeout must match
ok 518 connectionType must match
ok 519 portNumber must match
[39m
[32m# teardown
[39m
[36mok 522 Host address must match
[39m
[36mok 523 suggestedTCPTimeout must match
ok 524 connectionType must match
[39m
[36mok 525 portNumber must match
[39m
[36m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:30.120Z - info: Running on ios test: 137. Action fails because of a bad hostname.

[33m# 137. Action fails because of a bad hostname.
[39m
[36m# 137. Action fails because of a bad hostname.
[39m
[32m# 137. Action fails because of a bad hostname.
[39m
[36mok 526 should be equal
ok 527 should be equal
ok 528 should be equal
[39m
[36m# teardown
[39m
[33mok 528 should be equal
ok 529 should be equal
ok 530 should be equal
[39m
[33m# teardown
[39m
[32mok 520 should be equal
[39m
[32mok 521 should be equal
ok 522 should be equal
[39m
[32m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:35.159Z - info: Running on ios test: 138. hostaddress is removed when the action is running. 

[36m# 138. hostaddress is removed when the action is running. 
[39m
[33m# 138. hostaddress is removed when the action is running. 
[39m
[32m# 138. hostaddress is removed when the action is running. 
[39m
[36mok 529 should be equal
[39m
[32mok 523 should be equal
# teardown
[39m
[33mok 531 should be equal
[39m
[33m# teardown
[39m
[36m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:37.200Z - info: Running on ios test: 139. Client to server request locally

[36m# 139. Client to server request locally
[39m
[32m# 139. Client to server request locally
[39m
[33m# 139. Client to server request locally
[39m
[33mok 532 secrets are equal
ok 533 Public key matches with the server key
ok 534 Host address must match
ok 535 suggestedTCPTimeout must match
ok 536 connectionType must match
ok 537 portNumber must match
# teardown
[39m
[36mok 530 secrets are equal
[39m
[36mok 531 Public key matches with the server key
[39m
[36mok 532 Host address must match
[39m
[36mok 533 suggestedTCPTimeout must match
ok 534 connectionType must match
ok 535 portNumber must match
[39m
[36m# teardown
[39m
[32mok 524 secrets are equal
[39m
[32mok 525 Public key matches with the server key
ok 526 Host address must match
ok 527 suggestedTCPTimeout must match
ok 528 connectionType must match
ok 529 portNumber must match
# teardown
[39m
[33m# setup
[39m
[32m# setup
[39m
[36m# setup
[39m
2016-08-10T13:14:37.252Z - info: Running on ios test: 140. Test ThaliPskMapCache clean and expiration

[33m# 140. Test ThaliPskMapCache clean and expiration
[39m
[32m# 140. Test ThaliPskMapCache clean and expiration
[39m
[36m# 140. Test ThaliPskMapCache clean and expiration
[39m
[36mok 536 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
[39m
[33mok 538 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
ok 539 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
[39m
[32mok 530 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
ok 531 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
[39m
[36mok 537 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
[39m
[36mok 538 All entries should be expired after 1 second
# teardown
[39m
[33mok 540 All entries should be expired after 1 second
# teardown
[39m
[32mok 532 All entries should be expired after 1 second
[39m
[32m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:38.280Z - info: Running on ios test: 141. Test ThaliPskMapCache getSecret and getPublic

[36m# 141. Test ThaliPskMapCache getSecret and getPublic
[39m
[33m# 141. Test ThaliPskMapCache getSecret and getPublic
[39m
[32m# 141. Test ThaliPskMapCache getSecret and getPublic
[39m
[36mok 539 All keys need to be available in the cache
[39m
[33mok 541 All keys need to be available in the cache
[39m
[32mok 533 All keys need to be available in the cache
[39m
[36mok 540 All entries should be expired after 1 second
[39m
[36m# teardown
[39m
[33mok 542 All entries should be expired after 1 second
# teardown
[39m
[32mok 534 All entries should be expired after 1 second
# teardown
[39m
[33m# setup
[39m
[32m# setup
[39m
[36m# setup
[39m
2016-08-10T13:14:39.322Z - info: Running on ios test: 142. Test ThaliPskMapCache multiple entries

[36m# 142. Test ThaliPskMapCache multiple entries
[39m
[33m# 142. Test ThaliPskMapCache multiple entries
[39m
[32m# 142. Test ThaliPskMapCache multiple entries
[39m
[36mok 541 Size of the cache should be 2
ok 542 Cache doesn't contain dictionary1
[39m
[33mok 543 Size of the cache should be 2
ok 544 Cache doesn't contain dictionary1
[39m
[32mok 535 Size of the cache should be 2
[39m
[32mok 536 Cache doesn't contain dictionary1
[39m
[36mok 543 Size of the cache should be 1
ok 544 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
[39m
[33mok 545 Size of the cache should be 1
ok 546 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
[39m
[32mok 537 Size of the cache should be 1
[39m
[32mok 538 Cache doesn't contain beaconStreamAndSecretDictionary2
[39m
[32m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:41.784Z - info: Running on ios test: 143. Start and stop ThaliNotificationServer

[36m# 143. Start and stop ThaliNotificationServer
[39m
[33m# 143. Start and stop ThaliNotificationServer
[39m
[32m# 143. Start and stop ThaliNotificationServer
[39m
[33mok 547 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
ok 548 ThaliMobile.StopAdvertisingAndListeningshould be called once
# teardown
[39m
[36mok 545 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
ok 546 ThaliMobile.StopAdvertisingAndListeningshould be called once
# teardown
[39m
[32mok 539 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
[39m
[32mok 540 ThaliMobile.StopAdvertisingAndListeningshould be called once
# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:41.825Z - info: Running on ios test: 144. Pass an empty array to ThaliNotificationServer.start

[33m# 144. Pass an empty array to ThaliNotificationServer.start
[39m
[36m# 144. Pass an empty array to ThaliNotificationServer.start
[39m
[32m# 144. Pass an empty array to ThaliNotificationServer.start
[39m
[36mok 547 StartUpdateAdvertisingAndListening should not be called
ok 548 ThaliMobile.StopAdvertisingAndListening should be called once
[39m
[33mok 549 StartUpdateAdvertisingAndListening should not be called
ok 550 ThaliMobile.StopAdvertisingAndListening should be called once
[39m
[32mok 541 StartUpdateAdvertisingAndListening should not be called
ok 542 ThaliMobile.StopAdvertisingAndListening should be called once
[39m
[33mok 551 no error
ok 552 should be 204
[39m
[33m# teardown
[39m
[36mok 549 no error
ok 550 should be 204
[39m
[36m# teardown
[39m
[32mok 543 no error
ok 544 should be 204
[39m
[32m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:41.874Z - info: Running on ios test: 145. Pass a string to ThaliNotificationServer.start

[36m# 145. Pass a string to ThaliNotificationServer.start
[39m
[33m# 145. Pass a string to ThaliNotificationServer.start
[39m
[32m# 145. Pass a string to ThaliNotificationServer.start
[39m
[36mok 551 StartUpdateAdvertisingAndListening should not be called
# teardown
[39m
[33mok 553 StartUpdateAdvertisingAndListening should not be called
# teardown
[39m
[32mok 545 StartUpdateAdvertisingAndListening should not be called
[39m
[32m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T13:14:41.904Z - info: Running on ios test: 146. Pass an empty parameter to ThaliNotificationServer.start

[33m# 146. Pass an empty parameter to ThaliNotificationServer.start
[39m
[36m# 146. Pass an empty parameter to ThaliNotificationServer.start
[39m
[32m# 146. Pass an empty parameter to ThaliNotificationServer.start
[39m
[33mok 554 StartUpdateAdvertisingAndListening should not be called
# teardown
[39m
[32mok 546 StartUpdateAdvertisingAndListening should not be called
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
2016-08-10T13:14:41.935Z - info: Running on ios test: 147. Make an HTTP request to /NotificationBeacons

[32m# 147. Make an HTTP request to /NotificationBeacons
[39m
[33m# 147. Make an HTTP request to /NotificationBeacons
[39m
[36m# 147. Make an HTTP request to /NotificationBeacons
[39m
[33mok 555 no error
ok 556 should be 200
ok 557 should be equal
ok 558 should be equal
ok 559 (unnamed assert)
[39m
[32mok 547 no error
ok 548 should be 200
ok 549 should be equal
ok 550 should be equal
[39m
[32mok 551 (unnamed assert)
[39m
[33mok 560 no error
ok 561 should be 204
# teardown
[39m
[32mok 552 no error
ok 553 should be 204
[39m
[36mok 553 no error
ok 554 should be 200
ok 555 should be equal
ok 556 should be equal
[39m
[32m# teardown
[39m
[36mok 557 (unnamed assert)
[39m
[36mok 558 no error
ok 559 should be 204
[39m
[36m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T13:14:41.989Z - info: Running on ios test: 148. Make an HTTP request to /NotificationBeacons (no keys)

[36m# 148. Make an HTTP request to /NotificationBeacons (no keys)
[39m
[33m# 148. Make an HTTP request to /NotificationBeacons (no keys)
[39m
[32m# 148. Make an HTTP request to /NotificationBeacons (no keys)
[39m
[33mok 562 error should be null
ok 563 should be 204
[39m
[33m# teardown
[39m
[32mok 554 error should be null
ok 555 should be 204
# teardown
[39m
[36mok 560 error should be null
ok 561 should be 204
[39m
[36m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:42.025Z - info: Running on ios test: 149. Make an HTTP request to /NotificationBeaconsbefore calling start

[33m# 149. Make an HTTP request to /NotificationBeaconsbefore calling start
[39m
[36m# 149. Make an HTTP request to /NotificationBeaconsbefore calling start
[39m
[32m# 149. Make an HTTP request to /NotificationBeaconsbefore calling start
[39m
[33mok 564 should be 404
[39m
[33m# teardown
[39m
[36mok 562 should be 404
[39m
[36m# teardown
[39m
[32mok 556 should be 404
[39m
[32m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:42.060Z - info: Running on ios test: 150. #testThaliPeerAction - test getters

[36m# 150. #testThaliPeerAction - test getters
[39m
[33m# 150. #testThaliPeerAction - test getters
[39m
[32m# 150. #testThaliPeerAction - test getters
[39m
[36mok 563 getPeerIdentifier
[39m
[33mok 565 getPeerIdentifier
[39m
[33mok 566 getConnectionType
[39m
[33mok 567 getActionType
ok 568 getActionState
[39m
[33mok 569 getPskIdentity
[39m
[33mok 570 getPskKey
[39m
[33m# teardown
[39m
[36mok 564 getConnectionType
[39m
[36mok 565 getActionType
[39m
[36mok 566 getActionState
[39m
[36mok 567 getPskIdentity
[39m
[36mok 568 getPskKey
[39m
[36m# teardown
[39m
[32mok 557 getPeerIdentifier
[39m
[32mok 558 getConnectionType
[39m
[32mok 559 getActionType
[39m
[32mok 560 getActionState
[39m
[32mok 561 getPskIdentity
ok 562 getPskKey
[39m
[32m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:42.085Z - info: Running on ios test: 151. #testThaliPeerAction - start and kill

[33m# 151. #testThaliPeerAction - start and kill
[39m
[36m# 151. #testThaliPeerAction - start and kill
[39m
[32m# 151. #testThaliPeerAction - start and kill
[39m
[33mok 571 initial state
[39m
[33mok 572 after start
ok 573 after kill
[39m
[33m# teardown
[39m
[36mok 569 initial state
[39m
[32mok 563 initial state
[39m
[36mok 570 after start
[39m
[36mok 571 after kill
[39m
[36m# teardown
[39m
[32mok 564 after start
[39m
[32mok 565 after kill
[39m
[32m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:42.108Z - info: Running on ios test: 152. #testThaliPeerAction - double start

[33m# 152. #testThaliPeerAction - double start
[39m
[36m# 152. #testThaliPeerAction - double start
[39m
[32m# 152. #testThaliPeerAction - double start
[39m
[33mok 574 should be equal
[39m
[33m# teardown
[39m
[36mok 572 should be equal
[39m
[36m# teardown
[39m
[32mok 566 should be equal
[39m
[32m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:42.131Z - info: Running on ios test: 153. #testThaliPeerAction - start after kill

[33m# 153. #testThaliPeerAction - start after kill
[39m
[36m# 153. #testThaliPeerAction - start after kill
[39m
[32m# 153. #testThaliPeerAction - start after kill
[39m
[33mok 575 clean kill
[39m
[33mok 576 should be equal
[39m
[33m# teardown
[39m
[36mok 573 clean kill
[39m
[36mok 574 should be equal
[39m
[36m# teardown
[39m
[32mok 567 clean kill
[39m
[32mok 568 should be equal
[39m
[32m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:42.154Z - info: Running on ios test: 154. #testThaliPeerAction - make sure ids are unique

[36m# 154. #testThaliPeerAction - make sure ids are unique
[39m
[32m# 154. #testThaliPeerAction - make sure ids are unique
[39m
[33m# 154. #testThaliPeerAction - make sure ids are unique
[39m
[33mok 577 should not be equal
# teardown
[39m
[32mok 569 should not be equal
# teardown
[39m
[36mok 575 should not be equal
[39m
[36m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:42.173Z - info: Running on ios test: 155. Test PeerConnectionInformation basics

[33m# 155. Test PeerConnectionInformation basics
[39m
[36m# 155. Test PeerConnectionInformation basics
[39m
[32m# 155. Test PeerConnectionInformation basics
[39m
[36mok 576 connection type works
ok 577 getHostAddress works
[39m
[33mok 578 connection type works
ok 579 getHostAddress works
ok 580 getPortNumber works
[39m
[36mok 578 getPortNumber works
ok 579 getSuggestedTCPTimeout works
[39m
[33mok 581 getSuggestedTCPTimeout works
[39m
[33m# teardown
[39m
[36m# teardown
[39m
[32mok 570 connection type works
ok 571 getHostAddress works
[39m
[32mok 572 getPortNumber works
ok 573 getSuggestedTCPTimeout works
[39m
[32m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:42.197Z - info: Running on ios test: 156. Test PeerDictionary basic functionality

[33m# 156. Test PeerDictionary basic functionality
[39m
[36m# 156. Test PeerDictionary basic functionality
[39m
[32m# 156. Test PeerDictionary basic functionality
[39m
[36mok 580 Entry counter must be 1
ok 581 Size must be 1
ok 582 Entry counter must be 2
ok 583 Size must be 2
ok 584 Entry2 should not be found
ok 585 Size must be 1
ok 586 Size must be 0
# teardown
[39m
[32mok 574 Entry counter must be 1
ok 575 Size must be 1
ok 576 Entry counter must be 2
ok 577 Size must be 2
ok 578 Entry2 should not be found
ok 579 Size must be 1
ok 580 Size must be 0
# teardown
[39m
[33mok 582 Entry counter must be 1
ok 583 Size must be 1
ok 584 Entry counter must be 2
ok 585 Size must be 2
ok 586 Entry2 should not be found
ok 587 Size must be 1
ok 588 Size must be 0
# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T13:14:42.231Z - info: Running on ios test: 157. Test PeerDictionary with multiple entries.

[33m# 157. Test PeerDictionary with multiple entries.
[39m
[32m# 157. Test PeerDictionary with multiple entries.
[39m
[36m# 157. Test PeerDictionary with multiple entries.
[39m
[32mok 581 Size must be100
[39m
[32mok 582 Entries between 20 and MAXSIZE + 20 should exist
[39m
[33mok 589 Size must be100
ok 590 Entries between 20 and MAXSIZE + 20 should exist
[39m
[36mok 587 Size must be100
ok 588 Entries between 20 and MAXSIZE + 20 should exist
[39m
[36mok 589 WAITING state entry should not be removed
# teardown
[39m
[33mok 591 WAITING state entry should not be removed
# teardown
[39m
[32mok 583 WAITING state entry should not be removed
# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:42.444Z - info: Running on ios test: 158. RESOLVED entries are removed before WAITING state entry.

[36m# 158. RESOLVED entries are removed before WAITING state entry.
[39m
[33m# 158. RESOLVED entries are removed before WAITING state entry.
[39m
[32m# 158. RESOLVED entries are removed before WAITING state entry.
[39m
[32mok 584 Entries between 6 and MAXSIZE + 4 should exist
ok 585 Size should be MAXSIZE
ok 586 Size should be MAXSIZE+6
# teardown
[39m
[36mok 590 Entries between 6 and MAXSIZE + 4 should exist
ok 591 Size should be MAXSIZE
ok 592 Size should be MAXSIZE+6
# teardown
[39m
[33mok 592 Entries between 6 and MAXSIZE + 4 should exist
[39m
[33mok 593 Size should be MAXSIZE
ok 594 Size should be MAXSIZE+6
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-10T13:14:42.569Z - info: Running on ios test: 159. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

[32m# 159. WAITING entries are removed before CONTROLLED_BY_POOL state entry.
[39m
[36m# 159. WAITING entries are removed before CONTROLLED_BY_POOL state entry.
[39m
[33m# 159. WAITING entries are removed before CONTROLLED_BY_POOL state entry.
[39m
[32mok 587 WAITING state entry should not be removed
[39m
[33mok 595 WAITING state entry should not be removed
[39m
[32mok 588 Waiting entries between 6 and MAXSIZE + 4 should exist
[39m
[33mok 596 Waiting entries between 6 and MAXSIZE + 4 should exist
[39m
[33mok 597 Size should be MAXSIZE
[39m
[33mok 598 entryCounter should be MAXSIZE+6
[39m
[33m# teardown
[39m
[32mok 589 Size should be MAXSIZE
[39m
[32mok 590 entryCounter should be MAXSIZE+6
[39m
[32m# teardown
[39m
[36mok 593 WAITING state entry should not be removed
[39m
[36mok 594 Waiting entries between 6 and MAXSIZE + 4 should exist
[39m
[36mok 595 Size should be MAXSIZE
[39m
[36mok 596 entryCounter should be MAXSIZE+6
[39m
[36m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:42.720Z - info: Running on ios test: 160. When CONTROLLED_BY_POOL entry is removed and kill is called.

[33m# 160. When CONTROLLED_BY_POOL entry is removed and kill is called.
[39m
[36m# 160. When CONTROLLED_BY_POOL entry is removed and kill is called.
[39m
[32m# 160. When CONTROLLED_BY_POOL entry is removed and kill is called.
[39m
[36mok 597 Kill should be called once
[39m
[36mok 598 Size should be 100
[39m
[36m# teardown
[39m
[32mok 591 Kill should be called once
[39m
[32mok 592 Size should be 100
[39m
[32m# teardown
[39m
[33mok 599 Kill should be called once
[39m
[33mok 600 Size should be 100
[39m
[33m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:42.832Z - info: Running on ios test: 161. #ThaliPeerPoolInterface - bad enqueues

[36m# 161. #ThaliPeerPoolInterface - bad enqueues
[39m
[33m# 161. #ThaliPeerPoolInterface - bad enqueues
[39m
[32m# 161. #ThaliPeerPoolInterface - bad enqueues
[39m
[33mok 601 null arg
[39m
[33mok 602 wrong arg type
[39m
[33mok 603 wrong state
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
[32mok 593 null arg
[39m
[32mok 594 wrong arg type
[39m
[32mok 595 wrong state
[39m
[32m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:42.868Z - info: Running on ios test: 162. #ThaliPeerPoolInterface - do not allow same object type

[36m# 162. #ThaliPeerPoolInterface - do not allow same object type
[39m
[33m# 162. #ThaliPeerPoolInterface - do not allow same object type
[39m
[32m# 162. #ThaliPeerPoolInterface - do not allow same object type
[39m
[36mok 602 good enqueue
[39m
[33mok 604 good enqueue
[39m
[36mok 603 should be equal
[39m
[36m# teardown
[39m
[33mok 605 should be equal
[39m
[33m# teardown
[39m
[32mok 596 good enqueue
[39m
[32mok 597 should be equal
# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:42.904Z - info: Running on ios test: 163. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

[36m# 163. #ThaliPeerPoolInterface - make sure we catch kill and dequeue
[39m
[33m# 163. #ThaliPeerPoolInterface - make sure we catch kill and dequeue
[39m
[32m# 163. #ThaliPeerPoolInterface - make sure we catch kill and dequeue
[39m
[33mok 606 good enqueue
ok 607 2nd good enqueue
ok 608 we are in the pool
ok 609 We are out of the pool
ok 610 Action was killed
ok 611 The original kill was called too
ok 612 second item is still in queue
# teardown
[39m
[36mok 604 good enqueue
ok 605 2nd good enqueue
ok 606 we are in the pool
[39m
[32mok 598 good enqueue
ok 599 2nd good enqueue
ok 600 we are in the pool
[39m
[36mok 607 We are out of the pool
ok 608 Action was killed
ok 609 The original kill was called too
ok 610 second item is still in queue
# teardown
[39m
[32mok 601 We are out of the pool
ok 602 Action was killed
ok 603 The original kill was called too
ok 604 second item is still in queue
# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:42.929Z - info: Running on ios test: 164. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent

[36m# 164. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
[39m
[33m# 164. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
[39m
[32m# 164. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
[39m
[36mok 611 good enqueue
ok 612 first kill
ok 613 second NOOP kill
[39m
[36m# teardown
[39m
[33mok 613 good enqueue
ok 614 first kill
ok 615 second NOOP kill
[39m
[33m# teardown
[39m
[32mok 605 good enqueue
ok 606 first kill
[39m
[32mok 607 second NOOP kill
[39m
[32m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:42.958Z - info: Running on ios test: 165. Make sure peerDictionaryKey is reasonable

[36m# 165. Make sure peerDictionaryKey is reasonable
[39m
[33m# 165. Make sure peerDictionaryKey is reasonable
[39m
[32m# 165. Make sure peerDictionaryKey is reasonable
[39m
[36mok 614 equal keys
[39m
[36mok 615 not equal connection type
ok 616 same connection type, different buffer
# teardown
[39m
[33mok 616 equal keys
ok 617 not equal connection type
ok 618 same connection type, different buffer
# teardown
[39m
[32mok 608 equal keys
ok 609 not equal connection type
ok 610 same connection type, different buffer
[39m
[32m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:42.983Z - info: Running on ios test: 166. Make sure start works

[33m# 166. Make sure start works
[39m
[32m# 166. Make sure start works
[39m
[36m# 166. Make sure start works
[39m
[36mok 617 First start and on called correctly
# teardown
[39m
[33mok 619 First start and on called correctly
# teardown
[39m
[32mok 611 First start and on called correctly
# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:43.020Z - info: Running on ios test: 167. Make sure stop works

[36m# 167. Make sure stop works
[39m
[32m# 167. Make sure stop works
[39m
[33m# 167. Make sure stop works
[39m
[36mok 618 second cleared dictionary
[39m
[33mok 620 second cleared dictionary
[39m
[36mok 619 First start and on called correctly
[39m
[33mok 621 First start and on called correctly
[39m
[36mok 620 First stop and removeListener called correctly
[39m
[36mok 621 first action kill called
[39m
[36mok 622 second action kill called
[39m
[36mok 623 first cleared dictionary
ok 624 second cleared dictionary
[39m
[36m# teardown
[39m
[33mok 622 First stop and removeListener called correctly
[39m
[33mok 623 first action kill called
[39m
[33mok 624 second action kill called
[39m
[33mok 625 first cleared dictionary
[39m
[33mok 626 second cleared dictionary
[39m
[32mok 612 second cleared dictionary
[39m
[33m# teardown
[39m
[32mok 613 First start and on called correctly
[39m
[32mok 614 First stop and removeListener called correctly
[39m
[32mok 615 first action kill called
[39m
[32mok 616 second action kill called
[39m
[32mok 617 first cleared dictionary
ok 618 second cleared dictionary
[39m
[32m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:43.067Z - info: Running on ios test: 168. Simple peer event

[36m# 168. Simple peer event
[39m
[32m# 168. Simple peer event
[39m
[33m# 168. Simple peer event
[39m
[36mok 625 listener has been set
[39m
[36mok 626 peer dictionary has expected number of entries
[39m
[36mok 627 Dictionary and pool have same action
[39m
[36mok 628 ads match
[39m
[36mok 629 PouchDB matches
[39m
[36mok 630 DB Names match
[39m
[36mok 631 public keys match
[39m
[36mok 632 peer dictionary has expected number of entries
[39m
[36mok 633 Dictionary and pool have same action
[39m
[36mok 634 ads match
[39m
[32mok 619 listener has been set
[39m
[36mok 635 PouchDB matches
ok 636 DB Names match
[39m
[36mok 637 public keys match
[39m
[36mok 638 start called once
[39m
[36mok 639 kill never called
[39m
[36mok 640 One entry left
[39m
[36mok 641 Dictionary and pool have same action
[39m
[33mok 627 listener has been set
[39m
[32mok 620 peer dictionary has expected number of entries
[39m
[36mok 642 Start never called
[39m
[36mok 643 Kill called once
ok 644 no entries left
[39m
[32mok 621 Dictionary and pool have same action
[39m
[32mok 622 ads match
[39m
[32mok 623 PouchDB matches
[39m
[32mok 624 DB Names match
[39m
[32mok 625 public keys match
[39m
[32mok 626 peer dictionary has expected number of entries
[39m
[32mok 627 Dictionary and pool have same action
[39m
[32mok 628 ads match
[39m
[32mok 629 PouchDB matches
[39m
[32mok 630 DB Names match
[39m
[32mok 631 public keys match
[39m
[36mok 645 Third action is dead
[39m
[36mok 646 peer dictionary has expected number of entries
[39m
[36mok 647 Dictionary and pool have same action
[39m
[36mok 648 ads match
ok 649 PouchDB matches
[39m
[36mok 650 DB Names match
[39m
[36mok 651 public keys match
[39m
[36m# teardown
[39m
[32mok 632 start called once
[39m
[32mok 633 kill never called
[39m
[32mok 634 One entry left
[39m
[32mok 635 Dictionary and pool have same action
[39m
[33mok 628 peer dictionary has expected number of entries
[39m
[33mok 629 Dictionary and pool have same action
[39m
[33mok 630 ads match
[39m
[33mok 631 PouchDB matches
[39m
[33mok 632 DB Names match
[39m
[33mok 633 public keys match
[39m
[32mok 636 Start never called
[39m
[32mok 637 Kill called once
[39m
[32mok 638 no entries left
[39m
[33mok 634 peer dictionary has expected number of entries
ok 635 Dictionary and pool have same action
ok 636 ads match
ok 637 PouchDB matches
ok 638 DB Names match
ok 639 public keys match
ok 640 start called once
[39m
[33mok 641 kill never called
[39m
[33mok 642 One entry left
[39m
[33mok 643 Dictionary and pool have same action
[39m
[32mok 639 Third action is dead
[39m
[32mok 640 peer dictionary has expected number of entries
[39m
[33mok 644 Start never called
[39m
[32mok 641 Dictionary and pool have same action
ok 642 ads match
[39m
[33mok 645 Kill called once
[39m
[33mok 646 no entries left
[39m
[32mok 643 PouchDB matches
[39m
[32mok 644 DB Names match
[39m
[32mok 645 public keys match
[39m
[32m# teardown
[39m
[33mok 647 Third action is dead
[39m
[33mok 648 peer dictionary has expected number of entries
[39m
[33mok 649 Dictionary and pool have same action
[39m
[33mok 650 ads match
ok 651 PouchDB matches
ok 652 DB Names match
[39m
[33mok 653 public keys match
[39m
[33m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:43.120Z - info: Running on ios test: 169. Coordinated pull replication from notification test

[33m# 169. Coordinated pull replication from notification test
[39m
[36m# 169. Coordinated pull replication from notification test
[39m
[32m# 169. Coordinated pull replication from notification test
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52040
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52045
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52050
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[33mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG createPeerListener: first connection
[39m
[33mDEBUG createPeerListener: first connection
[39m
[33mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[33mDEBUG wifiBasedNativeMock: proxy socket connected
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
[32mDEBUG wifiBasedNativeMock: proxy socket connected
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG thaliReplicationPeerAction: Replication resumed
[39m
[36mDEBUG thaliReplicationPeerAction: Replication resumed
[39m
[33mDEBUG thaliReplicationPeerAction: Replication resumed
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[33mDEBUG createPeerListener: forward connection
[39m
[32mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[36mok 652 all tests passed
[39m
[36m# teardown
[39m
[32mDEBUG createNativeListener: 
DEBUG createNativeListener: stream close:
[39m
[36mDEBUG localSeqManager: Got an error trying to update seq {"onPut":true}
DEBUG thaliReplicationPeerAction: Got error in update, waiting for main loop to detect and handle - Error: Stop Called
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
[32mDEBUG createNativeListener: 
DEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: 
DEBUG createNativeListener: stream close:
[39m
[32mDEBUG thaliReplicationPeerAction: Replication resumed
[39m
[33mDEBUG createNativeListener: 
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG localSeqManager: Got an error trying to update seq {"onPut":true}
DEBUG thaliReplicationPeerAction: Got error in update, waiting for main loop to detect and handle - Error: Stop Called
[39m
[33mDEBUG createNativeListener: 
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: 
DEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: 
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: 
DEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[36mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[32mDEBUG thaliReplicationPeerAction: Got paused with undefined
[39m
[36mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[32mDEBUG thaliReplicationPeerAction: Replication resumed
[39m
[33mDEBUG thaliReplicationPeerAction: Replication resumed
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG thaliReplicationPeerAction: Got paused with undefined
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG thaliReplicationPeerAction: Got paused with undefined
[39m
[33mDEBUG thaliReplicationPeerAction: Got paused with undefined
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
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
[33mDEBUG thaliReplicationPeerAction: Replication resumed
[39m
[32mDEBUG thaliReplicationPeerAction: Replication resumed
[39m
[33mok 654 all tests passed
[39m
[32mDEBUG thaliReplicationPeerAction: Replication resumed
[39m
[33mDEBUG localSeqManager: Got an error trying to update seq {"onPut":true}
[39m
[33mDEBUG thaliReplicationPeerAction: Got error in update, waiting for main loop to detect and handle - Error: Stop Called
[39m
[33m# teardown
[39m
[32mok 646 all tests passed
[39m
[32mDEBUG createNativeListener: 
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createPeerListener: error on incoming socket - Error: read ECONNRESET
[39m
[32mDEBUG localSeqManager: Got an error trying to update seq {"onPut":true}
[39m
[32mDEBUG thaliReplicationPeerAction: Got error in update, waiting for main loop to detect and handle - Error: Stop Called
[39m
[32m# teardown
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[36mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[36mDEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
[39m
[36m# setup
[39m
[33mDEBUG createNativeListener: 
DEBUG createNativeListener: stream close:
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[32mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[32mDEBUG createNativeListener: mux close
[39m
[33mWARN createPeerListener: 
[39m
[33mDEBUG createPeerListener: failedConnection
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createPeerListener: Recreating listener
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[33mWARN createPeerListener: 
[39m
[33mDEBUG createPeerListener: failedConnection
[39m
[32mDEBUG createNativeListener: mux close
[39m
[33mDEBUG createPeerListener: failed incoming connection because of mux promise failure - Error: Unspecified Error with Radio infrastructure
[39m
[33mDEBUG createPeerListener: failed incoming connection because of mux promise failure - Error: Unspecified Error with Radio infrastructure
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[33mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[32mWARN createPeerListener: 
[39m
[32mDEBUG createPeerListener: failedConnection
[39m
[32mWARN createPeerListener: 
[39m
[32mDEBUG createPeerListener: failedConnection
[39m
[32mDEBUG createPeerListener: failed incoming connection because of mux promise failure - Error: Unspecified Error with Radio infrastructure
[39m
[32mDEBUG createPeerListener: failed incoming connection because of mux promise failure - Error: Unspecified Error with Radio infrastructure
[39m
[32mDEBUG thaliReplicationPeerAction: Got error on replication - Error: connect ECONNREFUSED
[39m
[32m# setup
[39m
[33mDEBUG createPeerListener: first connection
[39m
[33mDEBUG createPeerListener: Recreating listener
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mWARN thaliNotificationClient: _createAndEnqueueAction: failed to enqueue an item: We are stopped
[39m
[33mDEBUG createNativeListener: incoming socket close
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
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[33mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mDEBUG thaliPeerPoolDefault: Got err Error: Could not establish TCP connection
[39m
[33mDEBUG thaliPeerPoolDefault: Got err Error: Could not establish TCP connection
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mWARN createPeerListener: 
DEBUG createPeerListener: failedConnection
DEBUG createPeerListener: failed incoming connection because of mux promise failure - Error: Connection could not be established
# setup
[39m
2016-08-10T13:14:43.830Z - info: Running on ios test: 170. Server is not there

[33m# 170. Server is not there
[39m
[36m# 170. Server is not there
[39m
[32m# 170. Server is not there
[39m
[33mDEBUG thaliReplicationPeerAction: Got error on replication - Error: connect ECONNREFUSED
[39m
[33mok 655 right error
[39m
[33m# teardown
[39m
[32mDEBUG thaliReplicationPeerAction: Got error on replication - Error: connect ECONNREFUSED
[39m
[36mDEBUG thaliReplicationPeerAction: Got error on replication - Error: connect ECONNREFUSED
[39m
[32mok 647 right error
[39m
[36mok 653 right error
[39m
[36m# teardown
[39m
[32m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:43.876Z - info: Running on ios test: 171. Server accepts & closes connection

[33m# 171. Server accepts & closes connection
[39m
[36m# 171. Server accepts & closes connection
[39m
[32m# 171. Server accepts & closes connection
[39m
[33mDEBUG thaliReplicationPeerAction: Got error on replication - Error: socket hang up
[39m
[36mDEBUG thaliReplicationPeerAction: Got error on replication - Error: socket hang up
[39m
[36mok 654 right error
[39m
[36m# teardown
[39m
[33mok 656 right error
[39m
[33m# teardown
[39m
[32mDEBUG thaliReplicationPeerAction: Got error on replication - Error: socket hang up
[39m
[32mok 648 right error
[39m
[32m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T13:14:43.928Z - info: Running on ios test: 172. Server always returns 500

[33m# 172. Server always returns 500
[39m
[36m# 172. Server always returns 500
[39m
[32m# 172. Server always returns 500
[39m
[36mDEBUG thaliReplicationPeerAction: Got error on replication - 
[39m
[36mok 655 Got error as expected
[39m
[33mDEBUG thaliReplicationPeerAction: Got error on replication - 
[39m
[33mok 657 Got error as expected
[39m
[33m# teardown
[39m
[36m# teardown
[39m
[32mDEBUG thaliReplicationPeerAction: Got error on replication - 
[39m
[32mok 649 Got error as expected
[39m
[32m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T13:14:43.975Z - info: Running on ios test: 173. Server always returns 401

[33m# 173. Server always returns 401
[39m
[32m# 173. Server always returns 401
[39m
[36m# 173. Server always returns 401
[39m
[36mDEBUG thaliReplicationPeerAction: Got error on replication - 
[39m
[36mok 656 Got error as expected
[39m
[36m# teardown
[39m
[33mDEBUG thaliReplicationPeerAction: Got error on replication - 
[39m
[33mok 658 Got error as expected
[39m
[33m# teardown
[39m
[33mDEBUG thaliPeerPoolDefault: Got err Error: Could not establish TCP connection
[39m
[32mDEBUG thaliReplicationPeerAction: Got error on replication - 
[39m
[32mok 650 Got error as expected
[39m
[32m# teardown
[39m
[33mDEBUG thaliPeerPoolDefault: Got err Error: Could not establish TCP connection
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T13:14:44.023Z - info: Running on ios test: 174. Server always returns 403

[36m# 174. Server always returns 403
[39m
[33m# 174. Server always returns 403
[39m
[32m# 174. Server always returns 403
[39m
[36mDEBUG thaliReplicationPeerAction: Got error on replication - 
ok 657 Got error as expected
[39m
[36m# teardown
[39m
[32mDEBUG thaliReplicationPeerAction: Got error on replication - 
ok 651 Got error as expected
[39m
[32m# teardown
[39m
[33mDEBUG thaliReplicationPeerAction: Got error on replication - 
[39m
[33mok 659 Got error as expected
[39m
[33m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T13:14:44.069Z - info: Running on ios test: 175. Make sure docs replicate

[36m# 175. Make sure docs replicate
[39m
[32m# 175. Make sure docs replicate
[39m
[33m# 175. Make sure docs replicate
[39m
[36mDEBUG thaliReplicationPeerAction: Replication resumed
[39m
[32mDEBUG thaliReplicationPeerAction: Replication resumed
[39m
[33mDEBUG thaliReplicationPeerAction: Replication resumed
[39m
[33mDEBUG thaliPeerPoolDefault: Got err Error: Could not establish TCP connection
[39m
[33mDEBUG thaliPeerPoolDefault: Got err Error: Could not establish TCP connection
[39m
[36mDEBUG thaliReplicationPeerAction: Got paused with undefined
[39m
[32mDEBUG thaliReplicationPeerAction: Got paused with undefined
[39m
[33mDEBUG thaliReplicationPeerAction: Got paused with undefined
[39m
[36mok 658 should be equal
[39m
[36mok 659 All tests passed!
[39m
[36m# teardown
[39m
[33mok 660 should be equal
[39m
[33mok 661 All tests passed!
[39m
[33m# teardown
[39m
[32mok 652 should be equal
[39m
[32mok 653 All tests passed!
[39m
[32m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:44.660Z - info: Running on ios test: 176. Do nothing and make sure we time out

[36m# 176. Do nothing and make sure we time out
[39m
[33m# 176. Do nothing and make sure we time out
[39m
[32m# 176. Do nothing and make sure we time out
[39m
[32mDEBUG thaliReplicationPeerAction: Got paused with undefined
[39m
[33mDEBUG thaliReplicationPeerAction: Got paused with undefined
[39m
[36mDEBUG thaliReplicationPeerAction: Got paused with undefined
[39m
[33mDEBUG thaliPeerPoolDefault: Got err Error: Could not establish TCP connection
[39m
[33mDEBUG thaliPeerPoolDefault: Got err Error: Could not establish TCP connection
[39m
[33mDEBUG thaliPeerPoolDefault: Got err Error: Could not establish TCP connection
[39m
[33mDEBUG thaliPeerPoolDefault: Got err Error: Could not establish TCP connection
[39m
[36mok 660 action should be killed
[39m
[36mok 661 Error should be timed out
[39m
[32mok 654 action should be killed
ok 655 Error should be timed out
[39m
[36mok 662 No doc found
# teardown
[39m
[32mok 656 No doc found
[39m
[32m# teardown
[39m
[33mok 662 action should be killed
ok 663 Error should be timed out
[39m
[33mok 664 No doc found
[39m
[33m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T13:14:46.719Z - info: Running on ios test: 177. Do something and make sure we time out

[36m# 177. Do something and make sure we time out
[39m
[33m# 177. Do something and make sure we time out
[39m
[32m# 177. Do something and make sure we time out
[39m
[36mDEBUG thaliReplicationPeerAction: Replication resumed
[39m
[32mDEBUG thaliReplicationPeerAction: Replication resumed
[39m
[33mDEBUG thaliReplicationPeerAction: Replication resumed
[39m
[32mDEBUG thaliReplicationPeerAction: Got paused with undefined
[39m
[36mDEBUG thaliReplicationPeerAction: Got paused with undefined
[39m
[33mDEBUG thaliReplicationPeerAction: Got paused with undefined
[39m
[32mok 657 should be equal
[39m
[36mok 663 should be equal
[39m
[33mok 665 should be equal
[39m
[33mDEBUG thaliPeerPoolDefault: Got err Error: Could not establish TCP connection
[39m
[33mDEBUG thaliPeerPoolDefault: Got err Error: Could not establish TCP connection
[39m
[32mok 658 action should be killed
[39m
[32mok 659 Error should be timed out
[39m
[32m# teardown
[39m
[36mok 664 action should be killed
[39m
[36mok 665 Error should be timed out
[39m
[36m# teardown
[39m
[33mok 666 action should be killed
[39m
[33mok 667 Error should be timed out
[39m
[33m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:49.075Z - info: Running on ios test: 178. Start replicating and then catch error when server goes

[36m# 178. Start replicating and then catch error when server goes
[39m
[33m# 178. Start replicating and then catch error when server goes
[39m
[32m# 178. Start replicating and then catch error when server goes
[39m
[36mok 666 socket hung up
[39m
[36m# teardown
[39m
[33mok 668 socket hung up
[39m
[33m# teardown
[39m
[32mok 660 socket hung up
[39m
[32m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T13:14:49.249Z - info: Running on ios test: 179. Coordinated replication action test

[36m# 179. Coordinated replication action test
[39m
[32m# 179. Coordinated replication action test
[39m
[33m# 179. Coordinated replication action test
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: listening 52362
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: listening 52367
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: listening 52375
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[36mDEBUG createPeerListener: first connection
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
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
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG thaliReplicationPeerAction: Replication resumed
[39m
[36mDEBUG localSeqManager: Got an error trying to update seq {"onPut":true}
[39m
[36mDEBUG thaliReplicationPeerAction: Got error in update, waiting for main loop to detect and handle - Error: Stop Called
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
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
[32mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG thaliReplicationPeerAction: Replication resumed
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG thaliReplicationPeerAction: Replication resumed
[39m
[33mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG thaliReplicationPeerAction: Replication resumed
[39m
[33m# teardown
[39m
[33mDEBUG createNativeListener: 
[39m
[33mDEBUG createNativeListener: stream close:
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
[36m# teardown
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG localSeqManager: Got an error trying to update seq {"onPut":true}
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG thaliReplicationPeerAction: Got error in update, waiting for main loop to detect and handle - Error: Stop Called
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG localSeqManager: Got an error trying to update seq {"onPut":true}
DEBUG thaliReplicationPeerAction: Got error in update, waiting for main loop to detect and handle - Error: Stop Called
[39m
[32mDEBUG createNativeListener: 
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: 
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: 
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: 
DEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: 
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: 
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG localSeqManager: Got an error trying to update seq {"onPut":true}
DEBUG thaliReplicationPeerAction: Got error in update, waiting for main loop to detect and handle - Error: Stop Called
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
[32m# teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[36mDEBUG createPeerListener: Recreating listener
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createNativeListener: mux close
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: mux close
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[33m# setup
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[36mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[36mDEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[36m# setup
[39m
[32mDEBUG createPeerListener: Recreating listener
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}
[39m
[32mDEBUG thaliReplicationPeerAction: Got error in update, waiting for main loop to detect and handle - Error: connect ECONNREFUSED
[39m
[32mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[32mWARN createPeerListener: 
[39m
[32mDEBUG createPeerListener: failedConnection
[39m
[32mDEBUG createPeerListener: Recreating listener
[39m
[32mDEBUG createPeerListener: failed incoming connection because of mux promise failure - Error: Connection could not be established
[39m
[32mDEBUG createPeerListener: failed incoming connection because of mux promise failure - Error: Connection could not be established
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[32mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[32mDEBUG thaliPeerPoolDefault: Got err Error: Could not establish TCP connection
[39m
[32mWARN createPeerListener: 
[39m
[32mDEBUG createPeerListener: failedConnection
[39m
[32mWARN createPeerListener: 
DEBUG createPeerListener: failedConnection
DEBUG createPeerListener: failed incoming connection because of mux promise failure - Error: Unspecified Error with Radio infrastructure
[39m
[32mDEBUG createPeerListener: failed incoming connection because of mux promise failure - Error: Unspecified Error with Radio infrastructure
[39m
[32m# setup
[39m
2016-08-10T13:14:49.908Z - info: Running on ios test: 180. compareBufferArrays

[33m# 180. compareBufferArrays
[39m
[36m# 180. compareBufferArrays
[39m
[32m# 180. compareBufferArrays
[39m
[33mok 669 should throw
[39m
[33mok 670 should throw
ok 671 (unnamed assert)
[39m
[33mok 672 (unnamed assert)
[39m
[33mok 673 (unnamed assert)
[39m
[33mok 674 (unnamed assert)
[39m
[33mok 675 (unnamed assert)
[39m
[33m# teardown
[39m
[36mok 667 should throw
ok 668 should throw
ok 669 (unnamed assert)
ok 670 (unnamed assert)
ok 671 (unnamed assert)
ok 672 (unnamed assert)
ok 673 (unnamed assert)
# teardown
[39m
[32mok 661 should throw
ok 662 should throw
ok 663 (unnamed assert)
ok 664 (unnamed assert)
ok 665 (unnamed assert)
ok 666 (unnamed assert)
ok 667 (unnamed assert)
[39m
[32m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:49.942Z - info: Running on ios test: 181. Call start twice and get error

[36m# 181. Call start twice and get error
[39m
[33m# 181. Call start twice and get error
[39m
[32m# 181. Call start twice and get error
[39m
[33mok 676 should throw
[39m
[33m# teardown
[39m
[36mok 674 should throw
# teardown
[39m
[32mok 668 should throw
[39m
[32m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:49.972Z - info: Running on ios test: 182. Start and make sure it runs

[33m# 182. Start and make sure it runs
[39m
[36m# 182. Start and make sure it runs
[39m
[32m# 182. Start and make sure it runs
[39m
[36m# teardown
[39m
[33m# teardown
[39m
[32m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:49.998Z - info: Running on ios test: 183. Make sure getTimeWhenRun is right after start

[33m# 183. Make sure getTimeWhenRun is right after start
[39m
[36m# 183. Make sure getTimeWhenRun is right after start
[39m
[32m# 183. Make sure getTimeWhenRun is right after start
[39m
[33mok 677 (unnamed assert)
[39m
[36mok 675 (unnamed assert)
[39m
[36m# teardown
[39m
[33m# teardown
[39m
[32mok 669 (unnamed assert)
[39m
[32m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:50.019Z - info: Running on ios test: 184. Make sure getTimeWhenRun is -1 after function is called

[33m# 184. Make sure getTimeWhenRun is -1 after function is called
[39m
[36m# 184. Make sure getTimeWhenRun is -1 after function is called
[39m
[32m# 184. Make sure getTimeWhenRun is -1 after function is called
[39m
[33mok 678 should be equal
[39m
[32mok 670 should be equal
[39m
[33m# teardown
[39m
[36mok 676 should be equal
[39m
[36m# teardown
[39m
[32m# teardown
[39m
[32mDEBUG thaliPeerPoolDefault: Got err Error: Could not establish TCP connection
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:50.045Z - info: Running on ios test: 185. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

[33m# 185. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
[39m
[36m# 185. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
[39m
[32m# 185. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
[39m
[36mok 677 should be equal
ok 678 should be equal
ok 679 should throw
[39m
[36m# teardown
[39m
[32mok 671 should be equal
ok 672 should be equal
ok 673 should throw
# teardown
[39m
[33mok 679 should be equal
ok 680 should be equal
ok 681 should throw
# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:50.082Z - info: Running on ios test: 186. Test TransientState

[33m# 186. Test TransientState
[39m
[36m# 186. Test TransientState
[39m
[32m# 186. Test TransientState
[39m
[36mok 680 should throw
ok 681 should throw
ok 682 should be equal
ok 683 should be equal
ok 684 should be equal
ok 685 should be equal
ok 686 (unnamed assert)
ok 687 (unnamed assert)
# teardown
[39m
[33mok 682 should throw
ok 683 should throw
ok 684 should be equal
ok 685 should be equal
ok 686 should be equal
ok 687 should be equal
ok 688 (unnamed assert)
ok 689 (unnamed assert)
[39m
[33m# teardown
[39m
[32mok 674 should throw
[39m
[32mok 675 should throw
[39m
[32mok 676 should be equal
ok 677 should be equal
ok 678 should be equal
[39m
[32mok 679 should be equal
[39m
[32mok 680 (unnamed assert)
ok 681 (unnamed assert)
[39m
[32m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:50.104Z - info: Running on ios test: 187. No peers and empty database

[36m# 187. No peers and empty database
[39m
[33m# 187. No peers and empty database
[39m
[32m# 187. No peers and empty database
[39m
[33mok 690 verify failed
ok 691 constructor called once
ok 692 constructor called with right args
ok 693 match start arg
ok 694 start called once
ok 695 stop called once
ok 696 stop after start
[39m
[36mok 688 verify failed
ok 689 constructor called once
ok 690 constructor called with right args
ok 691 match start arg
ok 692 start called once
ok 693 stop called once
[39m
[36mok 694 stop after start
[39m
[33m# teardown
[39m
[36m# teardown
[39m
[32mok 682 verify failed
[39m
[32mok 683 constructor called once
[39m
[32mok 684 constructor called with right args
[39m
[32mok 685 match start arg
[39m
[32mok 686 start called once
ok 687 stop called once
[39m
[32mok 688 stop after start
[39m
[32m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:50.168Z - info: Running on ios test: 188. One peer and empty DB

[33m# 188. One peer and empty DB
[39m
[36m# 188. One peer and empty DB
[39m
[32m# 188. One peer and empty DB
[39m
[33mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 697 verify failed
ok 698 constructor called once
ok 699 constructor called with right args
ok 700 match start arg
ok 701 start called once
ok 702 stop called once
ok 703 stop after start
[39m
[33m# teardown
[39m
[36mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 695 verify failed
ok 696 constructor called once
ok 697 constructor called with right args
ok 698 match start arg
ok 699 start called once
ok 700 stop called once
ok 701 stop after start
[39m
[36m# teardown
[39m
[32mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[32mok 689 verify failed
ok 690 constructor called once
[39m
[32mok 691 constructor called with right args
[39m
[32mok 692 match start arg
[39m
[32mok 693 start called once
ok 694 stop called once
[39m
[32mok 695 stop after start
[39m
[32m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:50.219Z - info: Running on ios test: 189. One peer with _Local set behind current seq

[36m# 189. One peer with _Local set behind current seq
[39m
[33m# 189. One peer with _Local set behind current seq
[39m
[32m# 189. One peer with _Local set behind current seq
[39m
[33mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 704 verify failed
ok 705 constructor called once
ok 706 constructor called with right args
ok 707 match start arg
ok 708 start called once
ok 709 stop called once
ok 710 stop after start
# teardown
[39m
[36mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[36mok 702 verify failed
ok 703 constructor called once
[39m
[36mok 704 constructor called with right args
ok 705 match start arg
[39m
[36mok 706 start called once
ok 707 stop called once
[39m
[36mok 708 stop after start
[39m
[36m# teardown
[39m
[32mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[32mok 696 verify failed
ok 697 constructor called once
[39m
[32mok 698 constructor called with right args
[39m
[32mok 699 match start arg
[39m
[32mok 700 start called once
[39m
[32mok 701 stop called once
ok 702 stop after start
[39m
[32m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:50.278Z - info: Running on ios test: 190. One peer with _Local set equal to current seq

[33m# 190. One peer with _Local set equal to current seq
[39m
[36m# 190. One peer with _Local set equal to current seq
[39m
[32m# 190. One peer with _Local set equal to current seq
[39m
[33mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 711 verify failed
ok 712 constructor called once
ok 713 constructor called with right args
ok 714 match start arg
ok 715 start called once
ok 716 stop called once
ok 717 stop after start
[39m
[33m# teardown
[39m
[36mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 709 verify failed
ok 710 constructor called once
ok 711 constructor called with right args
ok 712 match start arg
ok 713 start called once
ok 714 stop called once
ok 715 stop after start
[39m
[36m# teardown
[39m
[32mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[32mok 703 verify failed
ok 704 constructor called once
[39m
[32mok 705 constructor called with right args
[39m
[32mok 706 match start arg
[39m
[32mok 707 start called once
[39m
[32mok 708 stop called once
[39m
[32mok 709 stop after start
[39m
[32m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:50.333Z - info: Running on ios test: 191. One peer with _Local set ahead of current seq (and no this should not happen)

[33m# 191. One peer with _Local set ahead of current seq (and no this should not happen)
[39m
[36m# 191. One peer with _Local set ahead of current seq (and no this should not happen)
[39m
[32m# 191. One peer with _Local set ahead of current seq (and no this should not happen)
[39m
[33mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[33mok 718 verify failed
[39m
[33mok 719 constructor called once
[39m
[33mok 720 constructor called with right args
[39m
[33mok 721 match start arg
[39m
[33mok 722 start called once
ok 723 stop called once
[39m
[33mok 724 stop after start
[39m
[33m# teardown
[39m
[36mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[36mok 716 verify failed
[39m
[36mok 717 constructor called once
[39m
[36mok 718 constructor called with right args
[39m
[36mok 719 match start arg
[39m
[36mok 720 start called once
[39m
[36mok 721 stop called once
[39m
[36mok 722 stop after start
[39m
[36m# teardown
[39m
[32mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[32mok 710 verify failed
ok 711 constructor called once
[39m
[32mok 712 constructor called with right args
[39m
[32mok 713 match start arg
[39m
[32mok 714 start called once
[39m
[32mok 715 stop called once
[39m
[32mok 716 stop after start
[39m
[32m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:50.389Z - info: Running on ios test: 192. Three peers, one not in DB, one behind and one ahead

[33m# 192. Three peers, one not in DB, one behind and one ahead
[39m
[36m# 192. Three peers, one not in DB, one behind and one ahead
[39m
[32m# 192. Three peers, one not in DB, one behind and one ahead
[39m
[33mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 725 verify failed
ok 726 constructor called once
ok 727 constructor called with right args
ok 728 match start arg
ok 729 start called once
ok 730 stop called once
ok 731 stop after start
[39m
[33m# teardown
[39m
[36mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 723 verify failed
[39m
[36mok 724 constructor called once
ok 725 constructor called with right args
[39m
[36mok 726 match start arg
[39m
[36mok 727 start called once
ok 728 stop called once
[39m
[36mok 729 stop after start
[39m
[36m# teardown
[39m
[32mDEBUG thaliPeerPoolDefault: Got err Error: Could not establish TCP connection
[39m
[32mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[32mok 717 verify failed
ok 718 constructor called once
[39m
[32mok 719 constructor called with right args
[39m
[32mok 720 match start arg
ok 721 start called once
[39m
[32mok 722 stop called once
ok 723 stop after start
[39m
[32m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:50.459Z - info: Running on ios test: 193. More than maximum peers, make sure we only send maximum allowed

[33m# 193. More than maximum peers, make sure we only send maximum allowed
[39m
[36m# 193. More than maximum peers, make sure we only send maximum allowed
[39m
[32m# 193. More than maximum peers, make sure we only send maximum allowed
[39m
[33mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 732 verify failed
ok 733 constructor called once
ok 734 constructor called with right args
ok 735 match start arg
ok 736 start called once
ok 737 stop called once
ok 738 stop after start
# teardown
[39m
[36mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 730 verify failed
ok 731 constructor called once
ok 732 constructor called with right args
ok 733 match start arg
ok 734 start called once
ok 735 stop called once
ok 736 stop after start
[39m
[36m# teardown
[39m
[32mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[32mok 724 verify failed
[39m
[32mok 725 constructor called once
[39m
[32mok 726 constructor called with right args
[39m
[32mok 727 match start arg
[39m
[32mok 728 start called once
[39m
[32mok 729 stop called once
[39m
[32mok 730 stop after start
[39m
[32m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:50.582Z - info: Running on ios test: 194. two peers with empty DB, update the doc

[36m# 194. two peers with empty DB, update the doc
[39m
[33m# 194. two peers with empty DB, update the doc
[39m
[32m# 194. two peers with empty DB, update the doc
[39m
[32mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[33mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[36mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[33mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[32mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[32mok 731 verify failed
[39m
[32mok 732 constructor called once
[39m
[32mok 733 constructor called with right args
[39m
[33mok 739 verify failed
[39m
[32mok 734 last start before stop
[39m
[32mok 735 empty first start
[39m
[32mok 736 full second start
[39m
[32mok 737 only 2 timers
[39m
[33mok 740 constructor called once
[39m
[32m# teardown
[39m
[33mok 741 constructor called with right args
[39m
[33mok 742 last start before stop
[39m
[33mok 743 empty first start
[39m
[33mok 744 full second start
[39m
[33mok 745 only 2 timers
[39m
[33m# teardown
[39m
[36mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[36mok 737 verify failed
[39m
[36mok 738 constructor called once
ok 739 constructor called with right args
[39m
[36mok 740 last start before stop
[39m
[36mok 741 empty first start
[39m
[36mok 742 full second start
[39m
[36mok 743 only 2 timers
[39m
[36m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T13:14:50.704Z - info: Running on ios test: 195. add doc and make sure tokens refresh when they expire

[32m# 195. add doc and make sure tokens refresh when they expire
[39m
[33m# 195. add doc and make sure tokens refresh when they expire
[39m
[36m# 195. add doc and make sure tokens refresh when they expire
[39m
[33mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[32mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[36mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[32mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[33mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[36mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[32mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[33mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[32mok 738 verify failed
[39m
[32mok 739 constructor called once
[39m
[32mok 740 constructor called with right args
[39m
[32mok 741 start before stop
[39m
[32mok 742 We got at least 3 calls to start
[39m
[32mok 743 at least 3
[39m
[33mok 746 verify failed
[39m
[32mok 744 default 1
ok 745 1 run
[39m
[32mok 746 default 2
ok 747 2 run
[39m
[32mok 748 default 3
[39m
[33mok 747 constructor called once
[39m
[33mok 748 constructor called with right args
[39m
[32m# teardown
[39m
[33mok 749 start before stop
[39m
[33mok 750 We got at least 3 calls to start
[39m
[33mok 751 at least 3
[39m
[33mok 752 default 1
[39m
[33mok 753 1 run
[39m
[33mok 754 default 2
[39m
[33mok 755 2 run
ok 756 default 3
[39m
[33m# teardown
[39m
[36mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[36mok 744 verify failed
[39m
[36mok 745 constructor called once
[39m
[36mok 746 constructor called with right args
[39m
[36mok 747 start before stop
[39m
[36mok 748 We got at least 3 calls to start
ok 749 at least 3
[39m
[36mok 750 default 1
[39m
[36mok 751 1 run
[39m
[36mok 752 default 2
[39m
[36mok 753 2 run
[39m
[36mok 754 default 3
[39m
[36m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T13:14:51.072Z - info: Running on ios test: 196. start and stop and start and stop

[33m# 196. start and stop and start and stop
[39m
[32m# 196. start and stop and start and stop
[39m
[36m# 196. start and stop and start and stop
[39m
[33mok 757 start out null
[39m
[32mok 749 start out null
[39m
[33mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[33mok 758 back to null
[39m
[32mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[32mok 750 back to null
[39m
[33mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[33mok 759 still null
[39m
[33mok 760 verify failed
[39m
[33mok 761 constructor called once
[39m
[33mok 762 constructor called with right args
[39m
[33mok 763 first start before first stop
[39m
[32mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[33mok 764 first stop before second start
ok 765 second start before second stop
[39m
[32mok 751 still null
[39m
[32mok 752 verify failed
[39m
[32mok 753 constructor called once
[39m
[32mok 754 constructor called with right args
[39m
[33m# teardown
[39m
[32mok 755 first start before first stop
[39m
[32mok 756 first stop before second start
[39m
[32mok 757 second start before second stop
[39m
[32m# teardown
[39m
[32mDEBUG thaliPeerPoolDefault: Got err Error: Could not establish TCP connection
[39m
[36mok 755 start out null
[39m
[36mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[36mok 756 back to null
[39m
[36mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[36mok 757 still null
[39m
[36mok 758 verify failed
[39m
[36mok 759 constructor called once
[39m
[36mok 760 constructor called with right args
ok 761 first start before first stop
[39m
[36mok 762 first stop before second start
[39m
[36mok 763 second start before second stop
[39m
[36m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:51.146Z - info: Running on ios test: 197. two identical starts in a row

[32m# 197. two identical starts in a row
[39m
[33m# 197. two identical starts in a row
[39m
[36m# 197. two identical starts in a row
[39m
[33mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 766 verify failed
ok 767 constructor called once
ok 768 constructor called with right args
ok 769 (unnamed assert)
[39m
[33m# teardown
[39m
[32mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 758 verify failed
ok 759 constructor called once
ok 760 constructor called with right args
[39m
[32mok 761 (unnamed assert)
# teardown
[39m
[36mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 764 verify failed
[39m
[36mok 765 constructor called once
[39m
[36mok 766 constructor called with right args
[39m
[36mok 767 (unnamed assert)
[39m
[36m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:51.197Z - info: Running on ios test: 198. two different starts in a row

[33m# 198. two different starts in a row
[39m
[36m# 198. two different starts in a row
[39m
[32m# 198. two different starts in a row
[39m
[36mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[36mok 768 verify failed
ok 769 constructor called once
ok 770 constructor called with right args
ok 771 (unnamed assert)
[39m
[36mok 772 (unnamed assert)
[39m
[36m# teardown
[39m
[33mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[33mok 770 verify failed
[39m
[33mok 771 constructor called once
[39m
[33mok 772 constructor called with right args
[39m
[33mok 773 (unnamed assert)
[39m
[33mok 774 (unnamed assert)
[39m
[33m# teardown
[39m
[32mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[32mok 762 verify failed
[39m
[32mok 763 constructor called once
ok 764 constructor called with right args
[39m
[32mok 765 (unnamed assert)
[39m
[32mok 766 (unnamed assert)
[39m
[32m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:51.263Z - info: Running on ios test: 199. two stops and a start and two stops

[36m# 199. two stops and a start and two stops
[39m
[33m# 199. two stops and a start and two stops
[39m
[32m# 199. two stops and a start and two stops
[39m
[36mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[36mok 773 verify failed
[39m
[36mok 774 constructor called once
[39m
[36mok 775 constructor called with right args
[39m
[36mok 776 start before stop
[39m
[36m# teardown
[39m
[33mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[33mok 775 verify failed
ok 776 constructor called once
ok 777 constructor called with right args
ok 778 start before stop
[39m
[33m# teardown
[39m
[32mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[32mok 767 verify failed
ok 768 constructor called once
[39m
[32mok 769 constructor called with right args
[39m
[32mok 770 start before stop
[39m
[32m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-10T13:14:51.323Z - info: Running on ios test: 200. we properly enqueue requests so no then needed

[32m# 200. we properly enqueue requests so no then needed
[39m
[33m# 200. we properly enqueue requests so no then needed
[39m
[36m# 200. we properly enqueue requests so no then needed
[39m
[32mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 771 verify failed
ok 772 constructor called once
ok 773 constructor called with right args
ok 774 start before stop
# teardown
[39m
[36mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 777 verify failed
ok 778 constructor called once
[39m
[36mok 779 constructor called with right args
ok 780 start before stop
[39m
[36m# teardown
[39m
[33mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[33mok 779 verify failed
[39m
[33mok 780 constructor called once
[39m
[33mok 781 constructor called with right args
[39m
[33mok 782 start before stop
[39m
[33m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:51.379Z - info: Running on ios test: 201. test calculateSeqPointKeyId

[32m# 201. test calculateSeqPointKeyId
[39m
[36m# 201. test calculateSeqPointKeyId
[39m
[33m# 201. test calculateSeqPointKeyId
[39m
[32mok 775 should be equal
[39m
[36mok 781 should be equal
[39m
[32mok 776 should be equal
[39m
[32m# teardown
[39m
[36mok 782 should be equal
[39m
[36m# teardown
[39m
[33mok 783 should be equal
[39m
[33mok 784 should be equal
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-10T13:14:51.411Z - info: Running on ios test: 202. can create servers manager

[32m# 202. can create servers manager
[39m
[36m# 202. can create servers manager
[39m
[33m# 202. can create servers manager
[39m
[36mok 783 serversManager must not be null
ok 784 serversManager must be an object
# teardown
[39m
[33mok 785 serversManager must not be null
ok 786 serversManager must be an object
# teardown
[39m
[32mok 777 serversManager must not be null
[39m
[32mok 778 serversManager must be an object
[39m
[32m# teardown
[39m
[33m# setup
[39m
[32m# setup
[39m
[36m# setup
[39m
2016-08-10T13:14:51.434Z - info: Running on ios test: 203. calling stop without start causes error

[33m# 203. calling stop without start causes error
[39m
[32m# 203. calling stop without start causes error
[39m
[36m# 203. calling stop without start causes error
[39m
[36mok 785 We need to call start first
# teardown
[39m
[33mok 787 We need to call start first
# teardown
[39m
[32mok 779 We need to call start first
[39m
[32m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T13:14:51.459Z - info: Running on ios test: 204. can start/stop servers manager

[36m# 204. can start/stop servers manager
[39m
[33m# 204. can start/stop servers manager
[39m
[32m# 204. can start/stop servers manager
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: listening 52467
ok 780 port must be in range
[39m
[33mDEBUG createNativeListener: listening 52468
ok 788 port must be in range
# teardown
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[32m# teardown
[39m
[36mDEBUG createNativeListener: listening 52469
[39m
[36mok 786 port must be in range
[39m
[36m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:51.487Z - info: Running on ios test: 205. starting twice resolves with listening port

[36m# 205. starting twice resolves with listening port
[39m
[32m# 205. starting twice resolves with listening port
[39m
[33m# 205. starting twice resolves with listening port
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: listening 52472
ok 781 second start should return same port
# teardown
[39m
[33mDEBUG createNativeListener: listening 52470
ok 789 second start should return same port
# teardown
[39m
[36mDEBUG createNativeListener: listening 52471
[39m
[36mok 787 second start should return same port
[39m
[36m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T13:14:51.527Z - info: Running on ios test: 206. terminateIncomingConnection will terminate a connection

[32m# 206. terminateIncomingConnection will terminate a connection
[39m
[36m# 206. terminateIncomingConnection will terminate a connection
[39m
[33m# 206. terminateIncomingConnection will terminate a connection
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52475
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52476
DEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 782 we should be connected
[39m
[36mDEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 788 we should be connected
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[32mok 783 now we are disconnected
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[36mok 789 now we are disconnected
[39m
[32m# teardown
[39m
[36m# teardown
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52480
[39m
[33mDEBUG createNativeListener: new incoming socket
[39m
[33mDEBUG createNativeListener: creating incoming mux
[39m
[33mDEBUG createNativeListener: new mux
[39m
[33mok 790 we should be connected
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[33mok 791 now we are disconnected
[39m
[33m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T13:14:51.564Z - info: Running on ios test: 207. terminate an Outgoing connection will terminate the server

[36m# 207. terminate an Outgoing connection will terminate the server
[39m
[32m# 207. terminate an Outgoing connection will terminate the server
[39m
[33m# 207. terminate an Outgoing connection will terminate the server
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: listening 52482
# teardown
[39m
[36mDEBUG createNativeListener: listening 52483
[39m
[36m# teardown
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: listening 52484
[39m
[33m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T13:14:51.590Z - info: Running on ios test: 208. terminate an Outgoing connection with wrong arguments is not harmful

[36m# 208. terminate an Outgoing connection with wrong arguments is not harmful
[39m
[32m# 208. terminate an Outgoing connection with wrong arguments is not harmful
[39m
[33m# 208. terminate an Outgoing connection with wrong arguments is not harmful
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: listening 52485
# teardown
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52486
[39m
[36m# teardown
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: listening 52487
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-10T13:14:51.617Z - info: Running on ios test: 209. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

[36mok 790 should be in started state
# 209. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
[39m
[33mok 792 should be in started state
# 209. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
[39m
[32mok 784 should be in started state
[39m
[32m# 209. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
[39m
[36mok 791 peer identifier should match
[39m
[36mok 792 host address should match
[39m
[36mok 793 port should match
[39m
[36mok 794 host address should be null
ok 795 port should should be null
[39m
[36m# teardown
[39m
[33mok 793 peer identifier should match
ok 794 host address should match
ok 795 port should match
[39m
[33mok 796 host address should be null
ok 797 port should should be null
# teardown
[39m
[32mok 785 peer identifier should match
ok 786 host address should match
[39m
[32mok 787 port should match
[39m
[32mok 788 host address should be null
[39m
[32mok 789 port should should be null
[39m
[32m# teardown
[39m
[33mok 798 should not be in started state
# setup
[39m
[36mok 796 should not be in started state
# setup
[39m
[32mok 790 should not be in started state
[39m
[32m# setup
[39m
2016-08-10T13:14:51.663Z - info: Running on ios test: 210. #startUpdateAdvertisingAndListening should use different USN after every invocation

[36mok 797 should be in started state
# 210. #startUpdateAdvertisingAndListening should use different USN after every invocation
[39m
[33mok 799 should be in started state
# 210. #startUpdateAdvertisingAndListening should use different USN after every invocation
[39m
[32mok 791 should be in started state
# 210. #startUpdateAdvertisingAndListening should use different USN after every invocation
[39m
[36mok 798 USN should have changed from the first one
[39m
[36mok 799 when receiving the second byebye, the first USN should be already set
[39m
[36m# teardown
[39m
[32mok 792 USN should have changed from the first one
[39m
[32mok 793 when receiving the second byebye, the first USN should be already set
# teardown
[39m
[33mok 800 USN should have changed from the first one
[39m
[33mok 801 when receiving the second byebye, the first USN should be already set
[39m
[33m# teardown
[39m
[36mok 800 should not be in started state
# setup
[39m
[32mok 794 should not be in started state
[39m
[32m# setup
[39m
[33mok 802 should not be in started state
[39m
[33m# setup
[39m
2016-08-10T13:14:51.703Z - info: Running on ios test: 211. messages with invalid location or USN should be ignored

[36mok 801 should be in started state
# 211. messages with invalid location or USN should be ignored
[39m
[33mok 803 should be in started state
# 211. messages with invalid location or USN should be ignored
[39m
[32mok 795 should be in started state
[39m
[32m# 211. messages with invalid location or USN should be ignored
[39m
[36mWARN thaliWifiInfrastructure: Failed to parse a valid port number from location: http://foo.bar:90000
ok 802 should not have emitted with invalid port
WARN thaliWifiInfrastructure: Received an invalid USN value: 
ok 803 should not have emitted with invalid USN
[39m
[33mWARN thaliWifiInfrastructure: Failed to parse a valid port number from location: http://foo.bar:90000
ok 804 should not have emitted with invalid port
WARN thaliWifiInfrastructure: Received an invalid USN value: 
[39m
[33mok 805 should not have emitted with invalid USN
[39m
[36m# teardown
[39m
[33m# teardown
[39m
[32mWARN thaliWifiInfrastructure: Failed to parse a valid port number from location: http://foo.bar:90000
[39m
[32mok 796 should not have emitted with invalid port
[39m
[32mWARN thaliWifiInfrastructure: Received an invalid USN value: 
[39m
[32mok 797 should not have emitted with invalid USN
[39m
[32m# teardown
[39m
[36mok 804 should not be in started state
# setup
[39m
[32mok 798 should not be in started state
[39m
[32m# setup
[39m
[33mok 806 should not be in started state
[39m
[33m# setup
[39m
2016-08-10T13:14:51.732Z - info: Running on ios test: 212. verify that Thali-specific messages are filtered correctly

[36mok 805 should be in started state
[39m
[36m# 212. verify that Thali-specific messages are filtered correctly
[39m
[33mok 807 should be in started state
# 212. verify that Thali-specific messages are filtered correctly
[39m
[32mok 799 should be in started state
[39m
[32m# 212. verify that Thali-specific messages are filtered correctly
[39m
[32mok 800 irrelevant messages should be ignored
ok 801 relevant messages should not be ignored
ok 802 messages from this device should be ignored
# teardown
[39m
[36mok 806 irrelevant messages should be ignored
ok 807 relevant messages should not be ignored
ok 808 messages from this device should be ignored
# teardown
[39m
[33mok 808 irrelevant messages should be ignored
[39m
[33mok 809 relevant messages should not be ignored
[39m
[33mok 810 messages from this device should be ignored
[39m
[33m# teardown
[39m
[36mok 809 should not be in started state
# setup
[39m
[33mok 811 should not be in started state
# setup
[39m
[32mok 803 should not be in started state
[39m
[32m# setup
[39m
2016-08-10T13:14:51.756Z - info: Running on ios test: 213. #startListeningForAdvertisements should fail if start not called

[36mok 810 should be in started state
# 213. #startListeningForAdvertisements should fail if start not called
[39m
[33mok 812 should be in started state
[39m
[33m# 213. #startListeningForAdvertisements should fail if start not called
[39m
[32mok 804 should be in started state
[39m
[32m# 213. #startListeningForAdvertisements should fail if start not called
[39m
[36mok 811 specific error should be returned
# teardown
[39m
[33mok 813 specific error should be returned
[39m
[33m# teardown
[39m
[32mok 805 specific error should be returned
[39m
[32m# teardown
[39m
[36mok 812 should not be in started state
# setup
[39m
[33mok 814 should not be in started state
[39m
[33m# setup
[39m
[32mok 806 should not be in started state
[39m
[32m# setup
[39m
2016-08-10T13:14:51.783Z - info: Running on ios test: 214. #startUpdateAdvertisingAndListening should fail if start not called

[36mok 813 should be in started state
# 214. #startUpdateAdvertisingAndListening should fail if start not called
[39m
[33mok 815 should be in started state
[39m
[33m# 214. #startUpdateAdvertisingAndListening should fail if start not called
[39m
[32mok 807 should be in started state
[39m
[32m# 214. #startUpdateAdvertisingAndListening should fail if start not called
[39m
[36mok 814 specific error should be returned
# teardown
[39m
[32mok 808 specific error should be returned
[39m
[32m# teardown
[39m
[33mok 816 specific error should be returned
[39m
[33m# teardown
[39m
[36mok 815 should not be in started state
# setup
[39m
[33mok 817 should not be in started state
[39m
[33m# setup
[39m
[32mok 809 should not be in started state
[39m
[32m# setup
[39m
2016-08-10T13:14:51.807Z - info: Running on ios test: 215. #start should fail if called twice in a row

[36mok 816 should be in started state
# 215. #start should fail if called twice in a row
[39m
[33mok 818 should be in started state
[39m
[33m# 215. #start should fail if called twice in a row
[39m
[32mok 810 should be in started state
[39m
[32m# 215. #start should fail if called twice in a row
[39m
[36mok 817 specific error should be received
# teardown
[39m
[33mok 819 specific error should be received
[39m
[33m# teardown
[39m
[32mok 811 specific error should be received
# teardown
[39m
[36mok 818 should not be in started state
# setup
[39m
[33mok 820 should not be in started state
# setup
[39m
[32mok 812 should not be in started state
[39m
[32m# setup
[39m
2016-08-10T13:14:51.831Z - info: Running on ios test: 216. should not be started after stop is called

[36mok 819 should be in started state
# 216. should not be started after stop is called
[39m
[33mok 821 should be in started state
# 216. should not be started after stop is called
[39m
[32mok 813 should be in started state
[39m
[32m# 216. should not be started after stop is called
[39m
[32mok 814 should not be started
ok 815 should not be listening
ok 816 should not target listening
ok 817 should not be advertising
ok 818 should not target advertising
# teardown
[39m
[36mok 820 should not be started
ok 821 should not be listening
ok 822 should not target listening
ok 823 should not be advertising
ok 824 should not target advertising
# teardown
[39m
[33mok 822 should not be started
[39m
[33mok 823 should not be listening
ok 824 should not target listening
ok 825 should not be advertising
ok 826 should not target advertising
[39m
[33m# teardown
[39m
[36mok 825 should not be in started state
# setup
[39m
[32mok 819 should not be in started state
# setup
[39m
[33mok 827 should not be in started state
[39m
[33m# setup
[39m
2016-08-10T13:14:51.858Z - info: Running on ios test: 217. #startUpdateAdvertisingAndListening should fail invalid router has been passed

[32mok 820 should be in started state
# 217. #startUpdateAdvertisingAndListening should fail invalid router has been passed
[39m
[36mok 826 should be in started state
# 217. #startUpdateAdvertisingAndListening should fail invalid router has been passed
[39m
[33mok 828 should be in started state
[39m
[33m# 217. #startUpdateAdvertisingAndListening should fail invalid router has been passed
[39m
[36mERROR thaliWifiInfrastructure: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
ok 827 specific error should be received
# teardown
[39m
[32mERROR thaliWifiInfrastructure: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
ok 821 specific error should be received
# teardown
[39m
[33mERROR thaliWifiInfrastructure: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
[39m
[33mok 829 specific error should be received
[39m
[33m# teardown
[39m
[36mok 828 should not be in started state
# setup
[39m
[32mok 822 should not be in started state
# setup
[39m
[33mok 830 should not be in started state
[39m
[33m# setup
[39m
2016-08-10T13:14:51.885Z - info: Running on ios test: 218. #startUpdateAdvertisingAndListening should fail if router server starting fails

[32mok 823 should be in started state
# 218. #startUpdateAdvertisingAndListening should fail if router server starting fails
[39m
[36mok 829 should be in started state
# 218. #startUpdateAdvertisingAndListening should fail if router server starting fails
[39m
[33mok 831 should be in started state
[39m
[33m# 218. #startUpdateAdvertisingAndListening should fail if router server starting fails
[39m
[36mERROR thaliWifiInfrastructure: Router server emitted an error: Error: listen EADDRINUSE
ok 830 specific error expected
# teardown
[39m
[32mERROR thaliWifiInfrastructure: Router server emitted an error: Error: listen EADDRINUSE
ok 824 specific error expected
# teardown
[39m
[33mERROR thaliWifiInfrastructure: Router server emitted an error: Error: listen EADDRINUSE
[39m
[33mok 832 specific error expected
[39m
[33m# teardown
[39m
[32mok 825 should not be in started state
# setup
[39m
[36mok 831 should not be in started state
# setup
[39m
[33mok 833 should not be in started state
[39m
[33m# setup
[39m
2016-08-10T13:14:51.913Z - info: Running on ios test: 219. #startUpdateAdvertisingAndListening should start hosting given router object

[36mok 832 should be in started state
# 219. #startUpdateAdvertisingAndListening should start hosting given router object
[39m
[32mok 826 should be in started state
# 219. #startUpdateAdvertisingAndListening should start hosting given router object
[39m
[33mok 834 should be in started state
[39m
[33m# 219. #startUpdateAdvertisingAndListening should start hosting given router object
[39m
[36mok 833 server should respond with code 200
[39m
[36m# teardown
[39m
[33mok 835 server should respond with code 200
[39m
[33m# teardown
[39m
[32mok 827 server should respond with code 200
[39m
[32m# teardown
[39m
[36mok 834 should not be in started state
# setup
[39m
[33mok 836 should not be in started state
# setup
[39m
[32mok 828 should not be in started state
[39m
[32m# setup
[39m
2016-08-10T13:14:51.962Z - info: Running on ios test: 220. #startUpdateAdvertisingAndListening bad psk should be rejected object

[36mok 835 should be in started state
[39m
[36m# 220. #startUpdateAdvertisingAndListening bad psk should be rejected object
[39m
[33mok 837 should be in started state
# 220. #startUpdateAdvertisingAndListening bad psk should be rejected object
[39m
[32mok 829 should be in started state
# 220. #startUpdateAdvertisingAndListening bad psk should be rejected object
[39m
[36mok 836 Connection should be rejected
[39m
[36m# teardown
[39m
[33mok 838 Connection should be rejected
[39m
[33m# teardown
[39m
[32mok 830 Connection should be rejected
[39m
[32m# teardown
[39m
[36mok 837 should not be in started state
# setup
[39m
[33mok 839 should not be in started state
[39m
[33m# setup
[39m
[32mok 831 should not be in started state
[39m
[32m# setup
[39m
2016-08-10T13:14:52.005Z - info: Running on ios test: 221. #stop can be called multiple times in a row

[36mok 838 should be in started state
# 221. #stop can be called multiple times in a row
[39m
[32mok 832 should be in started state
[39m
[32m# 221. #stop can be called multiple times in a row
[39m
[33mok 840 should be in started state
# 221. #stop can be called multiple times in a row
[39m
[36mok 839 should be in stopped state
ok 840 should still be in stopped state
# teardown
[39m
[33mok 841 should be in stopped state
[39m
[33mok 842 should still be in stopped state
# teardown
[39m
[32mok 833 should be in stopped state
ok 834 should still be in stopped state
[39m
[32m# teardown
[39m
[36mok 841 should not be in started state
# setup
[39m
[33mok 843 should not be in started state
[39m
[33m# setup
[39m
[32mok 835 should not be in started state
[39m
[32m# setup
[39m
2016-08-10T13:14:52.031Z - info: Running on ios test: 222. #startListeningForAdvertisements can be called multiple times in a row

[36mok 842 should be in started state
# 222. #startListeningForAdvertisements can be called multiple times in a row
[39m
[32mok 836 should be in started state
# 222. #startListeningForAdvertisements can be called multiple times in a row
[39m
[33mok 844 should be in started state
[39m
[33m# 222. #startListeningForAdvertisements can be called multiple times in a row
[39m
[33mok 845 should be in listening state
[39m
[33mok 846 should still be in listening state
[39m
[36mok 843 should be in listening state
[39m
[33m# teardown
[39m
[36mok 844 should still be in listening state
[39m
[36m# teardown
[39m
[32mok 837 should be in listening state
[39m
[32mok 838 should still be in listening state
[39m
[32m# teardown
[39m
[36mok 845 should not be in started state
[39m
[33mok 847 should not be in started state
[39m
[36m# setup
[39m
[33m# setup
[39m
[32mok 839 should not be in started state
[39m
[32m# setup
[39m
2016-08-10T13:14:52.063Z - info: Running on ios test: 223. #stopListeningForAdvertisements can be called multiple times in a row

[36mok 846 should be in started state
[39m
[36m# 223. #stopListeningForAdvertisements can be called multiple times in a row
[39m
[32mok 840 should be in started state
[39m
[32m# 223. #stopListeningForAdvertisements can be called multiple times in a row
[39m
[33mok 848 should be in started state
[39m
[33m# 223. #stopListeningForAdvertisements can be called multiple times in a row
[39m
[33mok 849 should not be in listening state
[39m
[36mok 847 should not be in listening state
[39m
[36mok 848 should still not be in listening state
[39m
[33mok 850 should still not be in listening state
[39m
[33m# teardown
[39m
[36m# teardown
[39m
[32mok 841 should not be in listening state
[39m
[32mok 842 should still not be in listening state
[39m
[32m# teardown
[39m
[36mok 849 should not be in started state
[39m
[36m# setup
[39m
[33mok 851 should not be in started state
[39m
[33m# setup
[39m
[32mok 843 should not be in started state
[39m
[32m# setup
[39m
2016-08-10T13:14:52.094Z - info: Running on ios test: 224. #stopAdvertisingAndListening can be called multiple times in a row

[33mok 852 should be in started state
[39m
[33m# 224. #stopAdvertisingAndListening can be called multiple times in a row
[39m
[32mok 844 should be in started state
[39m
[36mok 850 should be in started state
[39m
[36m# 224. #stopAdvertisingAndListening can be called multiple times in a row
[39m
[32m# 224. #stopAdvertisingAndListening can be called multiple times in a row
[39m
[36mok 851 should not be in advertising state
[39m
[36mok 852 should still not be in advertising state
[39m
[36m# teardown
[39m
[33mok 853 should not be in advertising state
[39m
[33mok 854 should still not be in advertising state
[39m
[33m# teardown
[39m
[32mok 845 should not be in advertising state
[39m
[32mok 846 should still not be in advertising state
[39m
[32m# teardown
[39m
[36mok 853 should not be in started state
[39m
[33mok 855 should not be in started state
# setup
[39m
[36m# setup
[39m
[32mok 847 should not be in started state
[39m
[32m# setup
[39m
2016-08-10T13:14:52.120Z - info: Running on ios test: 225. functions are run from a queue in the right order

[36mok 854 should be in started state
[39m
[36m# 225. functions are run from a queue in the right order
[39m
[33mok 856 should be in started state
[39m
[33m# 225. functions are run from a queue in the right order
[39m
[32mok 848 should be in started state
[39m
[32m# 225. functions are run from a queue in the right order
[39m
[36mok 855 call order must match
[39m
[36m# teardown
[39m
[33mok 857 call order must match
[39m
[33m# teardown
[39m
[32mok 849 call order must match
[39m
[32m# teardown
[39m
[36mok 856 should not be in started state
[39m
[36m# setup
[39m
[33mok 858 should not be in started state
[39m
[33m# setup
[39m
[32mok 850 should not be in started state
[39m
[32m# setup
[39m
2016-08-10T13:14:52.155Z - info: Running on ios test: 226. does not get peer changes from self

[36mok 857 should be in started state
[39m
[33mok 859 should be in started state
[39m
[33m# 226. does not get peer changes from self
[39m
[36m# 226. does not get peer changes from self
[39m
[32mok 851 should be in started state
[39m
[32m# 226. does not get peer changes from self
[39m
[36mok 858 we should not get notified about any USN that we have used
[39m
[33mok 860 we should not get notified about any USN that we have used
[39m
[33mok 861 we should not get notified about any USN that we have used
[39m
[36mok 859 we should not get notified about any USN that we have used
[39m
[32mok 852 we should not get notified about any USN that we have used
ok 853 we should not get notified about any USN that we have used
[39m
[32mDEBUG thaliPeerPoolDefault: Got err Error: Could not establish TCP connection
[39m
[36mok 860 we should not get notified about any USN that we have used
[39m
[33mok 862 we should not get notified about any USN that we have used
[39m
[32mok 854 we should not get notified about any USN that we have used
[39m
[36mok 861 we should not get notified about any USN that we have used
[39m
[33mok 863 we should not get notified about any USN that we have used
[39m
[32mok 855 we should not get notified about any USN that we have used
[39m
[32mok 856 USN must have changed again
[39m
[36mok 862 we should not get notified about any USN that we have used
ok 863 we should not get notified about any USN that we have used
ok 864 USN must have changed again
[39m
[33mok 864 we should not get notified about any USN that we have used
ok 865 we should not get notified about any USN that we have used
ok 866 we should not get notified about any USN that we have used
[39m
[32mok 857 we should not get notified about any USN that we have used
[39m
[33mok 867 we should not get notified about any USN that we have used
[39m
[32mok 858 we should not get notified about any USN that we have used
[39m
[36mok 865 we should not get notified about any USN that we have used
[39m
[33mok 868 USN must have changed again
[39m
[32mok 859 we should not get notified about any USN that we have used
ok 860 we should not get notified about any USN that we have used
[39m
[36mok 866 we should not get notified about any USN that we have used
[39m
[36mDEBUG thaliReplicationPeerAction: Got error on replication - Error: ETIMEDOUT
[39m
[33mDEBUG thaliPeerPoolDefault: Got err Error: Could not establish TCP connection
[39m
[33mDEBUG thaliPeerPoolDefault: Got err Error: Could not establish TCP connection
[39m
[33mok 869 we should not get notified about any USN that we have used
[39m
[36mok 867 we should not get notified about any USN that we have used
[39m
[33mok 870 we should not get notified about any USN that we have used
[39m
[36mok 868 we should not get notified about any USN that we have used
[39m
[32mok 861 we should not get notified about any USN that we have used
ok 862 we should not get notified about any USN that we have used
[39m
[36m# teardown
[39m
[32m# teardown
[39m
[33m# teardown
[39m
[36mok 869 should not be in started state
# setup
[39m
[33mok 871 should not be in started state
[39m
[33m# setup
[39m
[32mok 863 should not be in started state
# setup
[39m
2016-08-10T13:14:54.188Z - info: Running on ios test: 227. network changes are ignored while stopping

[33mok 872 should be in started state
# 227. network changes are ignored while stopping
[39m
[36mok 870 should be in started state
# 227. network changes are ignored while stopping
[39m
[32mok 864 should be in started state
# 227. network changes are ignored while stopping
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 871 should not be called
# teardown
[39m
[32mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 865 should not be called
# teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mok 873 should not be called
[39m
[33m# teardown
[39m
[36mok 872 should not be in started state
# setup
[39m
[33mok 874 should not be in started state
# setup
[39m
[32mok 866 should not be in started state
# setup
[39m
2016-08-10T13:14:54.212Z - info: Running on ios test: 228. #startListeningForAdvertisements returns error if wifi is off and fires event when on

[36mok 873 should be in started state
# 228. #startListeningForAdvertisements returns error if wifi is off and fires event when on
[39m
[33mok 875 should be in started state
# 228. #startListeningForAdvertisements returns error if wifi is off and fires event when on
[39m
[32mok 867 should be in started state
# 228. #startListeningForAdvertisements returns error if wifi is off and fires event when on
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 874 wifi should be off
[39m
[36mok 875 specific error expected
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 876 discoveryActive should be true
# teardown
[39m
[32mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 868 wifi should be off
ok 869 specific error expected
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 870 discoveryActive should be true
# teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 876 wifi should be off
ok 877 specific error expected
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 878 discoveryActive should be true
[39m
[33m# teardown
[39m
[36mok 877 should not be in started state
# setup
[39m
[33mok 879 should not be in started state
# setup
[39m
[32mok 871 should not be in started state
# setup
[39m
2016-08-10T13:14:54.239Z - info: Running on ios test: 229. #startUpdateAdvertisingAndListening returns error if wifi is off and fires event when on

[36mok 878 should be in started state
[39m
[36m# 229. #startUpdateAdvertisingAndListening returns error if wifi is off and fires event when on
[39m
[33mok 880 should be in started state
# 229. #startUpdateAdvertisingAndListening returns error if wifi is off and fires event when on
[39m
[32mok 872 should be in started state
# 229. #startUpdateAdvertisingAndListening returns error if wifi is off and fires event when on
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 879 wifi should be off
ok 880 specific error expected
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 881 wifi should be off
ok 882 specific error expected
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 883 advertisingActive should be true
# teardown
[39m
[36mok 881 advertisingActive should be true
[39m
[36m# teardown
[39m
[32mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 873 wifi should be off
ok 874 specific error expected
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[32mok 875 advertisingActive should be true
[39m
[32m# teardown
[39m
[33mok 884 should not be in started state
# setup
[39m
[36mok 882 should not be in started state
[39m
[32mok 876 should not be in started state
# setup
[39m
[36m# setup
[39m
2016-08-10T13:14:54.271Z - info: Running on ios test: 230. when wifi is enabled discovery is activated and peers become available

[36mok 883 should be in started state
# 230. when wifi is enabled discovery is activated and peers become available
[39m
[33mok 885 should be in started state
# 230. when wifi is enabled discovery is activated and peers become available
[39m
[32mok 877 should be in started state
# 230. when wifi is enabled discovery is activated and peers become available
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 884 wifi should be off
ok 885 specific error expected
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 886 wifi should be off
ok 887 specific error expected
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[32mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[32mok 878 wifi should be off
[39m
[32mok 879 specific error expected
[39m
[32mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mok 886 peer identifier should match
ok 887 host address should match
ok 888 port should match
[39m
[36m# teardown
[39m
[33mok 888 peer identifier should match
ok 889 host address should match
ok 890 port should match
[39m
[33m# teardown
[39m
[32mok 880 peer identifier should match
[39m
[32mok 881 host address should match
ok 882 port should match
[39m
[32m# teardown
[39m
[33mok 891 should not be in started state
# setup
[39m
[36mok 889 should not be in started state
# setup
[39m
[32mok 883 should not be in started state
# setup
[39m
2016-08-10T13:14:54.800Z - info: Running on ios test: 231. #ThaliPeerPoolDefault - single action

[36m# 231. #ThaliPeerPoolDefault - single action
[39m
[33m# 231. #ThaliPeerPoolDefault - single action
[39m
[32m# 231. #ThaliPeerPoolDefault - single action
[39m
[36mok 890 is an agent
ok 891 enqueue is fine
ok 892 Everything should be off the queue
# teardown
[39m
[33mok 892 is an agent
ok 893 enqueue is fine
ok 894 Everything should be off the queue
# teardown
[39m
[32mok 884 is an agent
[39m
[32mok 885 enqueue is fine
ok 886 Everything should be off the queue
[39m
[32m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:54.825Z - info: Running on ios test: 232. #ThaliPeerPoolDefault - multiple actions

[36m# 232. #ThaliPeerPoolDefault - multiple actions
[39m
[32m# 232. #ThaliPeerPoolDefault - multiple actions
[39m
[33m# 232. #ThaliPeerPoolDefault - multiple actions
[39m
[36mok 893 is an agent
ok 894 first enqueue is fine
ok 895 is an agent
ok 896 second enqueue is fine
ok 897 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 898 Queue is empty
# teardown
[39m
[33mok 895 is an agent
ok 896 first enqueue is fine
ok 897 is an agent
ok 898 second enqueue is fine
ok 899 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 900 Queue is empty
# teardown
[39m
[32mok 887 is an agent
ok 888 first enqueue is fine
ok 889 is an agent
[39m
[32mok 890 second enqueue is fine
[39m
[32mok 891 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 892 Queue is empty
# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
[32mDEBUG thaliPeerPoolDefault: Got err Error: Could not establish TCP connection
[39m
2016-08-10T13:14:54.851Z - info: Running on ios test: 233. #ThaliPeerPoolDefault - PSK Pool works

[36m# 233. #ThaliPeerPoolDefault - PSK Pool works
[39m
[33m# 233. #ThaliPeerPoolDefault - PSK Pool works
[39m
[32m# 233. #ThaliPeerPoolDefault - PSK Pool works
[39m
[36mok 899 is an agent
ok 900 good enqueue
ok 901 Identity should match
ok 902 Got expected response
ok 903 Got psk call back
# teardown
[39m
[33mok 901 is an agent
ok 902 good enqueue
ok 903 Identity should match
ok 904 Got expected response
ok 905 Got psk call back
# teardown
[39m
[32mok 893 is an agent
ok 894 good enqueue
ok 895 Identity should match
ok 896 Got expected response
ok 897 Got psk call back
# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T13:14:54.888Z - info: Running on ios test: 234. #ThaliPeerPoolDefault - stop

[36m# 234. #ThaliPeerPoolDefault - stop
[39m
[33m# 234. #ThaliPeerPoolDefault - stop
[39m
[32m# 234. #ThaliPeerPoolDefault - stop
[39m
[36mok 904 is an agent
ok 905 enqueue worked
ok 906 is an agent
ok 907 enqueue 2 worked
ok 908 start action is killed
ok 909 killed action is still killed
ok 910 inQueue is empty
ok 911 Make sure we won enqueue after stopping
# teardown
[39m
[33mok 906 is an agent
ok 907 enqueue worked
ok 908 is an agent
ok 909 enqueue 2 worked
ok 910 start action is killed
ok 911 killed action is still killed
ok 912 inQueue is empty
ok 913 Make sure we won enqueue after stopping
# teardown
[39m
[32mok 898 is an agent
[39m
[32mok 899 enqueue worked
ok 900 is an agent
[39m
[32mok 901 enqueue 2 worked
[39m
[32mok 902 start action is killed
[39m
[32mok 903 killed action is still killed
ok 904 inQueue is empty
[39m
[32mok 905 Make sure we won enqueue after stopping
[39m
[32m# teardown
[39m
2016-08-10T13:14:54.911Z - info: Test run on ios complete

2016-08-10T13:14:54.911Z - info: 

-== UNIT TEST RESULTS ==-

2016-08-10T13:14:54.912Z - info: PLATFORM: ios

2016-08-10T13:14:54.912Z - info: RESULT: FAIL

2016-08-10T13:14:54.912Z - info: 234 of 234 tests completed

2016-08-10T13:14:54.912Z - info: 233/234 passed (1 failures)

2016-08-10T13:14:54.913Z - info: 

--- Failed tests ---

2016-08-10T13:14:54.913Z - warn: 58. peer should be found once after listening and discovery started - fail
2016-08-10T13:14:54.913Z - info: 

-== END ==-

TEST FAILED - SEE ABOVE FOR MORE DETAILS
[33mTests complete
[39m
[33m****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
[39m
[36mTests complete
****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
[39m
[32mTests complete
****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
[39m
-e [0;31mcompilation aborted
 [0m
build aborted
 [0m

npm http request GET http://192.168.1.100:4873/fs-extra-promise
npm http request GET http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/socket.io
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/express
npm http 200 http://192.168.1.100:4873/fs-extra-promise
npm http 200 http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/socket.io
npm http 200 http://192.168.1.100:4873/lie
npm http 200 http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/cookie
npm http request GET http://192.168.1.100:4873/cookie-signature
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/content-disposition
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/escape-html
npm http request GET http://192.168.1.100:4873/accepts
npm http request GET http://192.168.1.100:4873/array-flatten
npm http request GET http://192.168.1.100:4873/etag
npm http request GET http://192.168.1.100:4873/finalhandler
npm http request GET http://192.168.1.100:4873/parseurl
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/merge-descriptors
npm http request GET http://192.168.1.100:4873/fresh
npm http request GET http://192.168.1.100:4873/path-to-regexp
npm http request GET http://192.168.1.100:4873/vary
npm http request GET http://192.168.1.100:4873/utils-merge
npm http request GET http://192.168.1.100:4873/range-parser
npm http request GET http://192.168.1.100:4873/proxy-addr
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/serve-static
npm http request GET http://192.168.1.100:4873/send
npm http 200 http://192.168.1.100:4873/debug
npm http 200 http://192.168.1.100:4873/cookie
npm http 200 http://192.168.1.100:4873/content-disposition
npm http 200 http://192.168.1.100:4873/content-type
npm http 200 http://192.168.1.100:4873/cookie-signature
npm http 200 http://192.168.1.100:4873/depd
npm http 200 http://192.168.1.100:4873/escape-html
npm http 200 http://192.168.1.100:4873/accepts
npm http 200 http://192.168.1.100:4873/array-flatten
npm http 200 http://192.168.1.100:4873/etag
npm http 200 http://192.168.1.100:4873/finalhandler
npm http 200 http://192.168.1.100:4873/parseurl
npm http 200 http://192.168.1.100:4873/on-finished
npm http 200 http://192.168.1.100:4873/merge-descriptors
npm http 200 http://192.168.1.100:4873/methods
npm http 200 http://192.168.1.100:4873/fresh
npm http 200 http://192.168.1.100:4873/vary
npm http 200 http://192.168.1.100:4873/path-to-regexp
npm http 200 http://192.168.1.100:4873/range-parser
npm http 200 http://192.168.1.100:4873/utils-merge
npm http 200 http://192.168.1.100:4873/proxy-addr
npm http 200 http://192.168.1.100:4873/type-is
npm http 200 http://192.168.1.100:4873/qs
npm http 200 http://192.168.1.100:4873/send
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
npm http request GET http://192.168.1.100:4873/mime
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/statuses
npm http 200 http://192.168.1.100:4873/destroy
npm http 200 http://192.168.1.100:4873/mime
npm http 200 http://192.168.1.100:4873/statuses
npm http 200 http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/inherits
npm http 200 http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/media-typer
npm http 200 http://192.168.1.100:4873/media-typer
npm http request GET http://192.168.1.100:4873/fs-extra
npm http request GET http://192.168.1.100:4873/bluebird
npm http 200 http://192.168.1.100:4873/fs-extra
npm http 200 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/rimraf
npm http request GET http://192.168.1.100:4873/jsonfile
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http 200 http://192.168.1.100:4873/graceful-fs
npm http 200 http://192.168.1.100:4873/jsonfile
npm http 200 http://192.168.1.100:4873/rimraf
npm http request GET http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/fs.realpath
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http 200 http://192.168.1.100:4873/once
npm http 200 http://192.168.1.100:4873/path-is-absolute
npm http 200 http://192.168.1.100:4873/fs.realpath
npm http 200 http://192.168.1.100:4873/minimatch
npm http 200 http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/wrappy
npm http 200 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 200 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/balanced-match
npm http 200 http://192.168.1.100:4873/concat-map
npm http 200 http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/immediate
npm http 200 http://192.168.1.100:4873/immediate
npm http 200 http://192.168.1.100:4873/unreachable-branch-transform
npm http 200 http://192.168.1.100:4873/es3ify
npm http 200 http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/through
npm http 200 http://192.168.1.100:4873/jstransform
npm http 200 http://192.168.1.100:4873/through
npm http 200 http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/source-map
npm http 200 http://192.168.1.100:4873/base62
npm http 200 http://192.168.1.100:4873/source-map
npm http 200 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/esprima-fb
npm http 200 http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/recast
npm http 200 http://192.168.1.100:4873/commander
npm http 200 http://192.168.1.100:4873/private
npm http 200 http://192.168.1.100:4873/mkdirp
npm http 200 http://192.168.1.100:4873/detective
npm http 200 http://192.168.1.100:4873/iconv-lite
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
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/object-keys
npm http 200 http://192.168.1.100:4873/foreach
npm http 200 http://192.168.1.100:4873/isarray
npm http 200 http://192.168.1.100:4873/object-keys
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/xtend
npm http 200 http://192.168.1.100:4873/xtend
npm http 200 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/core-util-is
npm http request GET http://192.168.1.100:4873/string_decoder
npm http 200 http://192.168.1.100:4873/string_decoder
npm http 200 http://192.168.1.100:4873/core-util-is
npm http request GET http://192.168.1.100:4873/esmangle-evaluator
npm http 200 http://192.168.1.100:4873/esmangle-evaluator
npm http request GET http://192.168.1.100:4873/has-binary-data
npm http request GET http://192.168.1.100:4873/engine.io
npm http request GET http://192.168.1.100:4873/socket.io-adapter
npm http request GET http://192.168.1.100:4873/socket.io-parser
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http 200 http://192.168.1.100:4873/has-binary-data
npm http 200 http://192.168.1.100:4873/socket.io-adapter
npm http 200 http://192.168.1.100:4873/socket.io-parser
npm http 200 http://192.168.1.100:4873/socket.io-client
npm http 200 http://192.168.1.100:4873/engine.io
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/base64id
npm http request GET http://192.168.1.100:4873/ws
npm http 200 http://192.168.1.100:4873/engine.io-parser
npm http 200 http://192.168.1.100:4873/base64id
npm http 200 http://192.168.1.100:4873/ws
npm http request GET http://192.168.1.100:4873/has-binary
npm http request GET http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/utf8
npm http 200 http://192.168.1.100:4873/has-binary
npm http 200 http://192.168.1.100:4873/base64-arraybuffer
npm http 200 http://192.168.1.100:4873/blob
npm http 200 http://192.168.1.100:4873/arraybuffer.slice
npm http 200 http://192.168.1.100:4873/after
npm http 200 http://192.168.1.100:4873/utf8
npm http request GET http://192.168.1.100:4873/options
npm http request GET http://192.168.1.100:4873/bufferutil
npm http request GET http://192.168.1.100:4873/ultron
npm http request GET http://192.168.1.100:4873/utf-8-validate
npm http 200 http://192.168.1.100:4873/options
npm http 200 http://192.168.1.100:4873/bufferutil
npm http 200 http://192.168.1.100:4873/ultron
npm http 200 http://192.168.1.100:4873/utf-8-validate
npm http request GET http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/nan
npm http 200 http://192.168.1.100:4873/bindings
npm http 200 http://192.168.1.100:4873/nan
npm http request GET http://192.168.1.100:4873/json3
npm http request GET http://192.168.1.100:4873/component-emitter
npm http request GET http://192.168.1.100:4873/benchmark
npm http 200 http://192.168.1.100:4873/component-emitter
npm http 200 http://192.168.1.100:4873/benchmark
npm http 200 http://192.168.1.100:4873/json3
npm http request GET http://192.168.1.100:4873/backo2
npm http request GET http://192.168.1.100:4873/to-array
npm http request GET http://192.168.1.100:4873/parseuri
npm http request GET http://192.168.1.100:4873/indexof
npm http request GET http://192.168.1.100:4873/object-component
npm http request GET http://192.168.1.100:4873/component-bind
npm http request GET http://192.168.1.100:4873/engine.io-client
npm http 200 http://192.168.1.100:4873/to-array
npm http 200 http://192.168.1.100:4873/indexof
npm http 200 http://192.168.1.100:4873/backo2
npm http 200 http://192.168.1.100:4873/parseuri
npm http 200 http://192.168.1.100:4873/object-component
npm http 200 http://192.168.1.100:4873/component-bind
npm http 200 http://192.168.1.100:4873/engine.io-client
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/parseqs
npm http fetch GET https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http 200 http://192.168.1.100:4873/parsejson
npm http 200 http://192.168.1.100:4873/parseqs
npm http 200 http://192.168.1.100:4873/has-cors
npm http 200 http://192.168.1.100:4873/component-inherit
npm http fetch 200 https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
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
npm http request GET http://192.168.1.100:4873/pkginfo
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/colors
npm http request GET http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/stack-trace
npm http 200 http://192.168.1.100:4873/pkginfo
npm http 200 http://192.168.1.100:4873/cycle
npm http 200 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/colors
npm http 200 http://192.168.1.100:4873/async
npm http 200 http://192.168.1.100:4873/eyes
npm http 200 http://192.168.1.100:4873/stack-trace
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/tape
npm http 200 http://192.168.1.100:4873/node-uuid
npm http 200 http://192.168.1.100:4873/tape
npm http request GET http://192.168.1.100:4873/jsonify
npm http request GET http://192.168.1.100:4873/deep-equal
npm http 200 http://192.168.1.100:4873/deep-equal
npm http 200 http://192.168.1.100:4873/jsonify
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
npm http request GET http://192.168.1.100:4873/forever-agent
npm http request GET http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/javascript-state-machine
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/salti
npm http request GET http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/lie
npm http 304 http://192.168.1.100:4873/express
npm http 200 http://192.168.1.100:4873/forever-agent
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 200 http://192.168.1.100:4873/ip
npm http 200 http://192.168.1.100:4873/body-parser
npm http 200 http://192.168.1.100:4873/javascript-state-machine
npm http 200 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/multiplex
npm http 200 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/salti
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/type-is
npm http 200 http://192.168.1.100:4873/bytes
npm http 304 http://192.168.1.100:4873/qs
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
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/proxy-addr
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
npm http 304 http://192.168.1.100:4873/unreachable-branch-transform
npm http 304 http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/through
npm http 304 http://192.168.1.100:4873/esprima
npm http 304 http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/through
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/base62
npm http 304 http://192.168.1.100:4873/commoner
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
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http 304 http://192.168.1.100:4873/detective
npm http 304 http://192.168.1.100:4873/commander
npm http 304 http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/mkdirp
npm http 304 http://192.168.1.100:4873/q
npm http 304 http://192.168.1.100:4873/private
npm http 304 http://192.168.1.100:4873/recast
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http 304 http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/acorn
npm http request GET http://192.168.1.100:4873/defined
npm http 304 http://192.168.1.100:4873/defined
npm http 304 http://192.168.1.100:4873/acorn
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/inflight
npm http 304 http://192.168.1.100:4873/minimatch
npm http 304 http://192.168.1.100:4873/path-is-absolute
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
npm http 304 http://192.168.1.100:4873/falafel
npm http 304 http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/foreach
npm http 304 http://192.168.1.100:4873/object-keys
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/xtend
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
npm http 200 http://192.168.1.100:4873/duplexify
npm http 200 http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/stream-shift
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http 200 http://192.168.1.100:4873/end-of-stream
npm http 200 http://192.168.1.100:4873/stream-shift
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 200 http://192.168.1.100:4873/buffer-shims
npm http 200 http://192.168.1.100:4873/util-deprecate
npm http 200 http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/har-validator
npm http 200 http://192.168.1.100:4873/json-stringify-safe
npm http 200 http://192.168.1.100:4873/caseless
npm http 200 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/form-data
npm http 200 http://192.168.1.100:4873/bl
npm http 200 http://192.168.1.100:4873/aws-sign2
npm http 200 http://192.168.1.100:4873/oauth-sign
npm http 200 http://192.168.1.100:4873/http-signature
npm http 200 http://192.168.1.100:4873/tunnel-agent
npm http 200 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/stringstream
npm http 200 http://192.168.1.100:4873/combined-stream
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
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 200 http://192.168.1.100:4873/escape-string-regexp
npm http 200 http://192.168.1.100:4873/ansi-styles
npm http 200 http://192.168.1.100:4873/strip-ansi
npm http 200 http://192.168.1.100:4873/supports-color
npm http 200 http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 200 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 200 http://192.168.1.100:4873/jsonpointer
npm http 200 http://192.168.1.100:4873/generate-function
npm http 200 http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/is-property
npm http 200 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/boom
npm http 200 http://192.168.1.100:4873/hoek
npm http 200 http://192.168.1.100:4873/cryptiles
npm http 200 http://192.168.1.100:4873/sntp
npm http 200 http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/ctype
npm http 200 http://192.168.1.100:4873/ctype
npm http 200 http://192.168.1.100:4873/assert-plus
npm http 200 http://192.168.1.100:4873/asn1
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
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/marked
npm http request GET http://192.168.1.100:4873/requizzle
npm http request GET http://192.168.1.100:4873/underscore
npm http request GET http://192.168.1.100:4873/wrench
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 200 http://192.168.1.100:4873/js2xmlparser
npm http 200 http://192.168.1.100:4873/catharsis
npm http 200 http://192.168.1.100:4873/requizzle
npm http 200 http://192.168.1.100:4873/marked
npm http 200 http://192.168.1.100:4873/underscore
npm http 200 http://192.168.1.100:4873/wrench
npm WARN deprecated wrench@1.5.9: wrench.js is deprecated! You should check out fs-extra (https://github.com/jprichardson/node-fs-extra) for any operations you were using wrench for. Thanks for all the usage over the years.
npm http 200 http://192.168.1.100:4873/strip-json-comments
npm http fetch 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http request GET http://192.168.1.100:4873/underscore-contrib
npm http 200 http://192.168.1.100:4873/underscore-contrib
npm WARN prefer global marked@0.3.6 should be installed with -g
npm http request GET http://192.168.1.100:4873/fs-extra-promise
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/jxc
npm http request GET http://192.168.1.100:4873/unzip
npm http 304 http://192.168.1.100:4873/fs-extra-promise
npm http 304 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/unzip
npm http 200 http://192.168.1.100:4873/lie
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
npm http 200 http://192.168.1.100:4873/graceful-fs
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
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/minimatch
npm http 304 http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/path-is-absolute
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
npm http 304 http://192.168.1.100:4873/immediate
npm http 304 http://192.168.1.100:4873/unreachable-branch-transform
npm http 200 http://192.168.1.100:4873/inline-process-browser
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
npm http 304 http://192.168.1.100:4873/commoner
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/commander
npm http 304 http://192.168.1.100:4873/detective
npm http 304 http://192.168.1.100:4873/mkdirp
npm http 200 http://192.168.1.100:4873/private
npm http 304 http://192.168.1.100:4873/q
npm http 304 http://192.168.1.100:4873/recast
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http 304 http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/acorn
npm http request GET http://192.168.1.100:4873/defined
npm http 304 http://192.168.1.100:4873/defined
npm http 304 http://192.168.1.100:4873/acorn
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
npm http request GET http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/object-keys
npm http 200 http://192.168.1.100:4873/foreach
npm http 304 http://192.168.1.100:4873/isarray
npm http 200 http://192.168.1.100:4873/object-keys
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/core-util-is
npm http request GET http://192.168.1.100:4873/string_decoder
npm http 304 http://192.168.1.100:4873/string_decoder
npm http 304 http://192.168.1.100:4873/core-util-is
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
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/forever-agent
npm http 200 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 200 http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 200 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/mime-db
npm http 304 http://192.168.1.100:4873/mime-db
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http 304 http://192.168.1.100:4873/chalk
npm http 304 http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/ansi-styles
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 200 http://192.168.1.100:4873/supports-color
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-function
npm http 200 http://192.168.1.100:4873/jsonpointer
npm http 200 http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/boom
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
npm http 200 http://192.168.1.100:4873/pullstream
npm http 200 http://192.168.1.100:4873/match-stream
npm http 200 http://192.168.1.100:4873/fstream
npm http 200 http://192.168.1.100:4873/binary
npm http 200 http://192.168.1.100:4873/setimmediate
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
npm http request GET http://192.168.1.100:4873/bn.js
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/express-pouchdb
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/leveldown-mobile
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/pouchdb-node
npm http request GET http://192.168.1.100:4873/proxyquire
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/nock
npm http request GET http://192.168.1.100:4873/tape
npm http request GET http://192.168.1.100:4873/sinon
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/request-promise
npm http request GET http://192.168.1.100:4873/supertest
npm http request GET http://192.168.1.100:4873/tape-catch
npm http request GET http://192.168.1.100:4873/supertest-as-promised
npm http request GET http://192.168.1.100:4873/tmp
npm http request GET http://192.168.1.100:4873/uuid
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/express
npm http 200 http://192.168.1.100:4873/forever-agent
npm http 200 http://192.168.1.100:4873/express-pouchdb
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/long
npm http 200 http://192.168.1.100:4873/bn.js
npm http 200 http://192.168.1.100:4873/js-extend
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/pouchdb-node
npm http 304 http://192.168.1.100:4873/socket.io-client
npm http 200 http://192.168.1.100:4873/proxyquire
npm http 304 http://192.168.1.100:4873/leveldown-mobile
npm http 200 http://192.168.1.100:4873/randomstring
npm http 304 http://192.168.1.100:4873/tape
npm http 200 http://192.168.1.100:4873/sinon
npm http 200 http://192.168.1.100:4873/urlsafe-base64
npm http 304 http://192.168.1.100:4873/multiplex
npm http 200 http://192.168.1.100:4873/nock
npm http 200 http://192.168.1.100:4873/request-promise
npm http 200 http://192.168.1.100:4873/tape-catch
npm http 200 http://192.168.1.100:4873/supertest
npm http 200 http://192.168.1.100:4873/supertest-as-promised
npm http 200 http://192.168.1.100:4873/tmp
npm http 200 http://192.168.1.100:4873/uuid
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
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/on-finished
npm http 200 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/type-is
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/raw-body
npm http 200 http://192.168.1.100:4873/debug
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
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/send
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/serve-static
npm http 304 http://192.168.1.100:4873/vary
npm http 304 http://192.168.1.100:4873/utils-merge
npm http request GET http://192.168.1.100:4873/negotiator
npm http 304 http://192.168.1.100:4873/negotiator
npm http request GET http://192.168.1.100:4873/forwarded
npm http request GET http://192.168.1.100:4873/ipaddr.js
npm http 304 http://192.168.1.100:4873/ipaddr.js
npm http 304 http://192.168.1.100:4873/forwarded
npm http request GET http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/mime
npm http 200 http://192.168.1.100:4873/mime
npm http 304 http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/basic-auth
npm http request GET http://192.168.1.100:4873/cookie-parser
npm http request GET http://192.168.1.100:4873/compression
npm http request GET http://192.168.1.100:4873/header-case-normalizer
npm http request GET http://192.168.1.100:4873/multiparty
npm http request GET http://192.168.1.100:4873/pouchdb-all-dbs
npm http request GET http://192.168.1.100:4873/pouchdb-list
npm http request GET http://192.168.1.100:4873/pouchdb-find
npm http request GET http://192.168.1.100:4873/pouchdb-auth
npm http request GET http://192.168.1.100:4873/pouchdb-vhost
npm http request GET http://192.168.1.100:4873/pouchdb-validation
npm http request GET http://192.168.1.100:4873/pouchdb-update
npm http request GET http://192.168.1.100:4873/pouchdb-size
npm http request GET http://192.168.1.100:4873/pouchdb-show
npm http request GET http://192.168.1.100:4873/pouchdb-security
npm http request GET http://192.168.1.100:4873/pouchdb-rewrite
npm http request GET http://192.168.1.100:4873/pouchdb-replicator
npm http request GET http://192.168.1.100:4873/pouchdb-wrappers
npm http 304 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/multiparty
npm http 200 http://192.168.1.100:4873/basic-auth
npm http 200 http://192.168.1.100:4873/cookie-parser
npm http 200 http://192.168.1.100:4873/header-case-normalizer
npm http 200 http://192.168.1.100:4873/compression
npm http 200 http://192.168.1.100:4873/pouchdb-vhost
npm http 200 http://192.168.1.100:4873/pouchdb-list
npm http 200 http://192.168.1.100:4873/pouchdb-find
npm http 200 http://192.168.1.100:4873/pouchdb-auth
npm http 304 http://192.168.1.100:4873/pouchdb-all-dbs
npm http 200 http://192.168.1.100:4873/pouchdb-show
npm http 200 http://192.168.1.100:4873/pouchdb-size
npm http 200 http://192.168.1.100:4873/pouchdb-validation
npm http 304 http://192.168.1.100:4873/pouchdb-update
npm http 200 http://192.168.1.100:4873/pouchdb-security
npm http 200 http://192.168.1.100:4873/pouchdb-rewrite
npm http 200 http://192.168.1.100:4873/pouchdb-wrappers
npm http 304 http://192.168.1.100:4873/pouchdb-replicator
npm http request GET http://192.168.1.100:4873/setprototypeof
npm http 200 http://192.168.1.100:4873/setprototypeof
npm http request GET http://192.168.1.100:4873/compressible
npm http request GET http://192.168.1.100:4873/on-headers
npm http 200 http://192.168.1.100:4873/compressible
npm http 200 http://192.168.1.100:4873/on-headers
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/stream-counter
npm http 200 http://192.168.1.100:4873/stream-counter
npm http 304 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/argsarray
npm http request GET http://192.168.1.100:4873/tiny-queue
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/es3ify
npm http 200 http://192.168.1.100:4873/argsarray
npm http 200 http://192.168.1.100:4873/pouchdb-promise
npm http 200 http://192.168.1.100:4873/tiny-queue
npm http request GET http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/base62
npm http 304 http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/couchdb-calculate-session-id
npm http request GET http://192.168.1.100:4873/crypto-lite
npm http request GET http://192.168.1.100:4873/pouchdb
npm http request GET http://192.168.1.100:4873/base64url
npm http request GET http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http request GET http://192.168.1.100:4873/pouchdb-plugin-error
npm http request GET http://192.168.1.100:4873/pouchdb-req-http-query
npm http request GET http://192.168.1.100:4873/pouchdb-system-db
npm http request GET http://192.168.1.100:4873/promise-nodify
npm http request GET http://192.168.1.100:4873/secure-random
npm http 200 http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http 200 http://192.168.1.100:4873/pouchdb
npm http 200 http://192.168.1.100:4873/base64url
npm http 200 http://192.168.1.100:4873/couchdb-calculate-session-id
npm http 200 http://192.168.1.100:4873/pouchdb-req-http-query
npm http 200 http://192.168.1.100:4873/pouchdb-plugin-error
npm http 200 http://192.168.1.100:4873/crypto-lite
npm http 200 http://192.168.1.100:4873/pouchdb-system-db
npm http 200 http://192.168.1.100:4873/promise-nodify
npm http 200 http://192.168.1.100:4873/secure-random
npm http request GET http://192.168.1.100:4873/meow
npm http request GET http://192.168.1.100:4873/concat-stream
npm http 200 http://192.168.1.100:4873/meow
npm http 200 http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/typedarray
npm http 200 http://192.168.1.100:4873/typedarray
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/camelcase-keys
npm http request GET http://192.168.1.100:4873/indent-string
npm http 304 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/indent-string
npm http 200 http://192.168.1.100:4873/camelcase-keys
npm http request GET http://192.168.1.100:4873/map-obj
npm http request GET http://192.168.1.100:4873/camelcase
npm http 200 http://192.168.1.100:4873/camelcase
npm http 200 http://192.168.1.100:4873/map-obj
npm http request GET http://192.168.1.100:4873/get-stdin
npm http request GET http://192.168.1.100:4873/repeating
npm http 200 http://192.168.1.100:4873/repeating
npm http 200 http://192.168.1.100:4873/get-stdin
npm http request GET http://192.168.1.100:4873/is-finite
npm http 200 http://192.168.1.100:4873/is-finite
npm http request GET http://192.168.1.100:4873/number-is-nan
npm http 200 http://192.168.1.100:4873/number-is-nan
npm http request GET http://192.168.1.100:4873/aproba
npm http 200 http://192.168.1.100:4873/aproba
npm http request GET http://192.168.1.100:4873/level-write-stream
npm http request GET http://192.168.1.100:4873/es6-promise-pool
npm http request GET http://192.168.1.100:4873/fruitdown
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/localstorage-down
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/memdown
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/pouchdb-collate
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/scope-eval
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/vuvuzela
npm http 200 http://192.168.1.100:4873/level-write-stream
npm http 200 http://192.168.1.100:4873/fruitdown
npm http 200 http://192.168.1.100:4873/double-ended-queue
npm http 200 http://192.168.1.100:4873/es6-promise-pool
npm http 200 http://192.168.1.100:4873/localstorage-down
npm http 304 http://192.168.1.100:4873/through2
npm http 200 http://192.168.1.100:4873/scope-eval
npm http 200 http://192.168.1.100:4873/memdown
npm http 200 http://192.168.1.100:4873/spark-md5
npm http 200 http://192.168.1.100:4873/levelup
npm http 200 http://192.168.1.100:4873/pouchdb-collate
npm http 200 http://192.168.1.100:4873/sublevel-pouchdb
npm http 200 http://192.168.1.100:4873/vuvuzela
npm http 200 http://192.168.1.100:4873/pouchdb-collections
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
npm http request GET http://192.168.1.100:4873/deferred-leveldown
npm http request GET http://192.168.1.100:4873/level-codec
npm http request GET http://192.168.1.100:4873/level-errors
npm http request GET http://192.168.1.100:4873/level-iterator-stream
npm http request GET http://192.168.1.100:4873/prr
npm http request GET http://192.168.1.100:4873/semver
npm http 200 http://192.168.1.100:4873/deferred-leveldown
npm http 200 http://192.168.1.100:4873/prr
npm http 200 http://192.168.1.100:4873/level-codec
npm http 200 http://192.168.1.100:4873/level-iterator-stream
npm http 200 http://192.168.1.100:4873/level-errors
npm http 200 http://192.168.1.100:4873/semver
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
npm http 200 http://192.168.1.100:4873/functional-red-black-tree
npm http 200 http://192.168.1.100:4873/ltgt
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/aws4
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/is-typedarray
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/http-signature
npm http 200 http://192.168.1.100:4873/is-typedarray
npm http 304 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/aws4
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm WARN deprecated tough-cookie@2.2.2: ReDoS vulnerability parsing Set-Cookie https://nodesecurity.io/advisories/130
npm http 304 http://192.168.1.100:4873/qs
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
npm http 304 http://192.168.1.100:4873/chalk
npm http 304 http://192.168.1.100:4873/is-my-json-valid
npm http 200 http://192.168.1.100:4873/pinkie-promise
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http 200 http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-function
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
npm http 200 http://192.168.1.100:4873/sshpk
npm http 200 http://192.168.1.100:4873/jsprim
npm http request GET http://192.168.1.100:4873/json-schema
npm http request GET http://192.168.1.100:4873/verror
npm http request GET http://192.168.1.100:4873/extsprintf
npm http 200 http://192.168.1.100:4873/json-schema
npm http 200 http://192.168.1.100:4873/extsprintf
npm http 200 http://192.168.1.100:4873/verror
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/getpass
npm http request GET http://192.168.1.100:4873/dashdash
npm http 200 http://192.168.1.100:4873/dashdash
npm http 304 http://192.168.1.100:4873/asn1
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
npm http 200 http://192.168.1.100:4873/xmlhttprequest-cookie
npm http request GET http://192.168.1.100:4873/xmlhttprequest
npm http 200 http://192.168.1.100:4873/xmlhttprequest
npm http request GET http://192.168.1.100:4873/pouchdb-changeslike-wrapper
npm http 200 http://192.168.1.100:4873/pouchdb-changeslike-wrapper
npm http request GET http://192.168.1.100:4873/couchdb-eval
npm http request GET http://192.168.1.100:4873/couchdb-objects
npm http request GET http://192.168.1.100:4873/random-uuid-v4
npm http 200 http://192.168.1.100:4873/couchdb-objects
npm http 200 http://192.168.1.100:4873/random-uuid-v4
npm http 200 http://192.168.1.100:4873/couchdb-eval
npm http request GET http://192.168.1.100:4873/is-empty
npm http 200 http://192.168.1.100:4873/is-empty
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/is-array
npm http request GET http://192.168.1.100:4873/pouchdb-extend
npm http request GET http://192.168.1.100:4873/pouchdb-upsert
npm http 304 http://192.168.1.100:4873/spark-md5
npm http 200 http://192.168.1.100:4873/is-array
npm http 200 http://192.168.1.100:4873/pouchdb-upsert
npm http 200 http://192.168.1.100:4873/pouchdb-extend
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 304 http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/couchdb-render
npm http 304 http://192.168.1.100:4873/couchdb-render
npm http request GET http://192.168.1.100:4873/couchdb-resp-completer
npm http 304 http://192.168.1.100:4873/couchdb-resp-completer
npm http request GET http://192.168.1.100:4873/equals
npm http 304 http://192.168.1.100:4873/equals
npm http request GET http://192.168.1.100:4873/jkroso-type
npm http 200 http://192.168.1.100:4873/jkroso-type
npm http request GET http://192.168.1.100:4873/pouchdb-route
npm http 304 http://192.168.1.100:4873/pouchdb-route
npm http request GET http://192.168.1.100:4873/get-folder-size
npm http 200 http://192.168.1.100:4873/get-folder-size
npm http request GET http://192.168.1.100:4873/minimist
npm http 304 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/fast-future
npm http 304 http://192.168.1.100:4873/bindings
npm http 304 http://192.168.1.100:4873/abstract-leveldown
npm http 200 http://192.168.1.100:4873/fast-future
npm http request GET http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/duplexify
npm http 304 http://192.168.1.100:4873/duplexify
npm http 304 http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/stream-shift
npm http 304 http://192.168.1.100:4873/end-of-stream
npm http 304 http://192.168.1.100:4873/stream-shift
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http 304 http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/deep-equal
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/propagate
npm http request GET http://192.168.1.100:4873/chai
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/deep-equal
npm http 200 http://192.168.1.100:4873/lodash
npm http 200 http://192.168.1.100:4873/propagate
npm http 200 http://192.168.1.100:4873/chai
npm WARN deprecated lodash@2.4.1: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
npm http request GET http://192.168.1.100:4873/deep-eql
npm http request GET http://192.168.1.100:4873/assertion-error
npm http request GET http://192.168.1.100:4873/type-detect
npm http 200 http://192.168.1.100:4873/assertion-error
npm http 200 http://192.168.1.100:4873/type-detect
npm http 200 http://192.168.1.100:4873/deep-eql
npm http request GET http://192.168.1.100:4873/ms
npm http 200 http://192.168.1.100:4873/ms
npm http fetch GET http://192.168.1.100:4873/ms/-/ms-0.6.2.tgz
npm http fetch 200 http://192.168.1.100:4873/ms/-/ms-0.6.2.tgz
npm http request GET http://192.168.1.100:4873/ip
npm http 304 http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-leveldb
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-http
npm http request GET http://192.168.1.100:4873/pouchdb-core
npm http request GET http://192.168.1.100:4873/pouchdb-replication
npm http request GET http://192.168.1.100:4873/pouchdb-mapreduce
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-leveldb
npm http 304 http://192.168.1.100:4873/pouchdb-replication
npm http 304 http://192.168.1.100:4873/pouchdb-mapreduce
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-http
npm http 304 http://192.168.1.100:4873/pouchdb-core
npm http request GET http://192.168.1.100:4873/pouchdb-ajax
npm http request GET http://192.168.1.100:4873/pouchdb-binary-utils
npm http request GET http://192.168.1.100:4873/pouchdb-errors
npm http request GET http://192.168.1.100:4873/pouchdb-utils
npm http request GET http://192.168.1.100:4873/pouchdb-md5
npm http 304 http://192.168.1.100:4873/pouchdb-md5
npm http 304 http://192.168.1.100:4873/pouchdb-errors
npm http 304 http://192.168.1.100:4873/pouchdb-ajax
npm http 200 http://192.168.1.100:4873/pouchdb-utils
npm http 304 http://192.168.1.100:4873/pouchdb-binary-utils
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http 304 http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-leveldb-core
npm http request GET http://192.168.1.100:4873/leveldown
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-leveldb-core
npm http 200 http://192.168.1.100:4873/leveldown
npm http request GET http://192.168.1.100:4873/nan
npm http request GET http://192.168.1.100:4873/prebuild
npm http 304 http://192.168.1.100:4873/nan
npm http 200 http://192.168.1.100:4873/prebuild
npm http request GET http://192.168.1.100:4873/npmlog
npm http request GET http://192.168.1.100:4873/os-homedir
npm http request GET http://192.168.1.100:4873/node-ninja
npm http request GET http://192.168.1.100:4873/noop-logger
npm http request GET http://192.168.1.100:4873/github-from-package
npm http request GET http://192.168.1.100:4873/ghreleases
npm http request GET http://192.168.1.100:4873/expand-template
npm http request GET http://192.168.1.100:4873/rc
npm http request GET http://192.168.1.100:4873/pump
npm http request GET http://192.168.1.100:4873/node-gyp
npm http request GET http://192.168.1.100:4873/simple-get
npm http request GET http://192.168.1.100:4873/tar-fs
npm http request GET http://192.168.1.100:4873/tar-stream
npm http 200 http://192.168.1.100:4873/os-homedir
npm http 200 http://192.168.1.100:4873/noop-logger
npm http 200 http://192.168.1.100:4873/github-from-package
npm http 200 http://192.168.1.100:4873/npmlog
npm http 200 http://192.168.1.100:4873/node-ninja
npm http 200 http://192.168.1.100:4873/pump
npm http 200 http://192.168.1.100:4873/rc
npm http 200 http://192.168.1.100:4873/expand-template
npm http 200 http://192.168.1.100:4873/ghreleases
npm http 200 http://192.168.1.100:4873/node-gyp
npm http 200 http://192.168.1.100:4873/tar-fs
npm http 200 http://192.168.1.100:4873/simple-get
npm http 200 http://192.168.1.100:4873/tar-stream
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/simple-mime
npm http request GET http://192.168.1.100:4873/ghutils
npm http request GET http://192.168.1.100:4873/ghrepos
npm http request GET http://192.168.1.100:4873/url-template
npm http 304 http://192.168.1.100:4873/after
npm http 200 http://192.168.1.100:4873/ghrepos
npm http 200 http://192.168.1.100:4873/simple-mime
npm http 200 http://192.168.1.100:4873/url-template
npm http 200 http://192.168.1.100:4873/ghutils
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
npm http request GET http://192.168.1.100:4873/osenv
npm http request GET http://192.168.1.100:4873/nopt
npm http request GET http://192.168.1.100:4873/path-array
npm http request GET http://192.168.1.100:4873/tar
npm http request GET http://192.168.1.100:4873/which
npm http 304 http://192.168.1.100:4873/fstream
npm http 200 http://192.168.1.100:4873/tar
npm http 200 http://192.168.1.100:4873/osenv
npm http 200 http://192.168.1.100:4873/path-array
npm http 200 http://192.168.1.100:4873/nopt
npm http 200 http://192.168.1.100:4873/which
npm http request GET http://192.168.1.100:4873/abbrev
npm http 200 http://192.168.1.100:4873/abbrev
npm http request GET http://192.168.1.100:4873/ansi
npm http request GET http://192.168.1.100:4873/are-we-there-yet
npm http request GET http://192.168.1.100:4873/gauge
npm http 200 http://192.168.1.100:4873/are-we-there-yet
npm http 304 http://192.168.1.100:4873/ansi
npm http 200 http://192.168.1.100:4873/gauge
npm http request GET http://192.168.1.100:4873/delegates
npm http 200 http://192.168.1.100:4873/delegates
npm http request GET http://192.168.1.100:4873/has-unicode
npm http request GET http://192.168.1.100:4873/lodash.padstart
npm http request GET http://192.168.1.100:4873/lodash.pad
npm http request GET http://192.168.1.100:4873/lodash.padend
npm http 200 http://192.168.1.100:4873/has-unicode
npm http 200 http://192.168.1.100:4873/lodash.padend
npm http 200 http://192.168.1.100:4873/lodash.padstart
npm http 200 http://192.168.1.100:4873/lodash.pad
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
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/aws-sign2
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
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/deep-extend
npm http request GET http://192.168.1.100:4873/ini
npm http 304 http://192.168.1.100:4873/strip-json-comments
npm http 304 http://192.168.1.100:4873/deep-extend
npm http 200 http://192.168.1.100:4873/ini
npm WARN engine deep-extend@0.4.1: wanted: {"node":">=0.12.0","iojs":">=1.0.0"} (current: {"node":"0.10.40","npm":"3.3.12"})
npm http request GET http://192.168.1.100:4873/unzip-response
npm http 304 http://192.168.1.100:4873/unzip-response
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/pouchdb-json
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-utils
npm http request GET http://192.168.1.100:4873/pouchdb-merge
npm http 304 http://192.168.1.100:4873/sublevel-pouchdb
npm http 304 http://192.168.1.100:4873/pouchdb-json
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-utils
npm http 304 http://192.168.1.100:4873/pouchdb-merge
npm http request GET http://192.168.1.100:4873/ltgt
npm http 304 http://192.168.1.100:4873/ltgt
npm http request GET http://192.168.1.100:4873/pouchdb-mapreduce-utils
npm http 304 http://192.168.1.100:4873/pouchdb-mapreduce-utils
npm http request GET http://192.168.1.100:4873/pouchdb-checkpointer
npm http request GET http://192.168.1.100:4873/pouchdb-generate-replication-id
npm http 304 http://192.168.1.100:4873/pouchdb-generate-replication-id
npm http 304 http://192.168.1.100:4873/pouchdb-checkpointer
npm http request GET http://192.168.1.100:4873/fill-keys
npm http request GET http://192.168.1.100:4873/module-not-found-error
npm http 200 http://192.168.1.100:4873/module-not-found-error
npm http 200 http://192.168.1.100:4873/fill-keys
npm http request GET http://192.168.1.100:4873/is-object
npm http 200 http://192.168.1.100:4873/is-object
npm http request GET http://192.168.1.100:4873/array-uniq
npm http 200 http://192.168.1.100:4873/array-uniq
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/formatio
npm http request GET http://192.168.1.100:4873/lolex
npm http request GET http://192.168.1.100:4873/util
npm http request GET http://192.168.1.100:4873/samsam
npm http 200 http://192.168.1.100:4873/lolex
npm http 200 http://192.168.1.100:4873/formatio
npm http 200 http://192.168.1.100:4873/util
npm http 200 http://192.168.1.100:4873/samsam
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
npm http 304 http://192.168.1.100:4873/socket.io-parser
npm http 304 http://192.168.1.100:4873/component-bind
npm http 304 http://192.168.1.100:4873/engine.io-client
npm http 304 http://192.168.1.100:4873/has-binary
npm http 304 http://192.168.1.100:4873/parseuri
npm http 200 http://192.168.1.100:4873/indexof
npm http 304 http://192.168.1.100:4873/debug
npm http 200 http://192.168.1.100:4873/component-emitter
npm http 200 http://192.168.1.100:4873/object-component
npm http 304 http://192.168.1.100:4873/backo2
npm http 304 http://192.168.1.100:4873/to-array
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/parseqs
npm http request GET http://192.168.1.100:4873/ws
npm http fetch GET https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http 304 http://192.168.1.100:4873/has-cors
npm http 304 http://192.168.1.100:4873/component-inherit
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
npm http 304 http://192.168.1.100:4873/base64-arraybuffer
npm http 304 http://192.168.1.100:4873/utf8
npm http 304 http://192.168.1.100:4873/arraybuffer.slice
npm http 304 http://192.168.1.100:4873/blob
npm http fetch GET https://github.com/component/global/archive/v2.0.1.tar.gz
npm http fetch 200 https://github.com/component/global/archive/v2.0.1.tar.gz
npm http request GET http://192.168.1.100:4873/better-assert
npm http 200 http://192.168.1.100:4873/better-assert
npm http request GET http://192.168.1.100:4873/callsite
npm http 304 http://192.168.1.100:4873/callsite
npm http request GET http://192.168.1.100:4873/options
npm http request GET http://192.168.1.100:4873/ultron
npm http 304 http://192.168.1.100:4873/ultron
npm http 200 http://192.168.1.100:4873/options
npm http request GET http://192.168.1.100:4873/json3
npm http request GET http://192.168.1.100:4873/benchmark
npm http 304 http://192.168.1.100:4873/benchmark
npm http 304 http://192.168.1.100:4873/json3
npm http request GET http://192.168.1.100:4873/superagent
npm http 200 http://192.168.1.100:4873/superagent
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/formidable
npm http request GET http://192.168.1.100:4873/cookiejar
npm http request GET http://192.168.1.100:4873/reduce-component
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 200 http://192.168.1.100:4873/formidable
npm http 200 http://192.168.1.100:4873/reduce-component
npm http 200 http://192.168.1.100:4873/cookiejar
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/async
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
npm http 200 http://192.168.1.100:4873/resumer
npm http 200 http://192.168.1.100:4873/defined
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

npm ERR! Darwin 14.5.0
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

```

Error: Command failed: npm http request GET http://192.168.1.100:4873/fs-extra-promise
npm http request GET http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/socket.io
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/express
npm http 200 http://192.168.1.100:4873/fs-extra-promise
npm http 200 http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/socket.io
npm http 200 http://192.168.1.100:4873/lie
npm http 200 http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/cookie
npm http request GET http://192.168.1.100:4873/cookie-signature
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/content-disposition
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/escape-html
npm http request GET http://192.168.1.100:4873/accepts
npm http request GET http://192.168.1.100:4873/array-flatten
npm http request GET http://192.168.1.100:4873/etag
npm http request GET http://192.168.1.100:4873/finalhandler
npm http request GET http://192.168.1.100:4873/parseurl
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/merge-descriptors
npm http request GET http://192.168.1.100:4873/fresh
npm http request GET http://192.168.1.100:4873/path-to-regexp
npm http request GET http://192.168.1.100:4873/vary
npm http request GET http://192.168.1.100:4873/utils-merge
npm http request GET http://192.168.1.100:4873/range-parser
npm http request GET http://192.168.1.100:4873/proxy-addr
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/serve-static
npm http request GET http://192.168.1.100:4873/send
npm http 200 http://192.168.1.100:4873/debug
npm http 200 http://192.168.1.100:4873/cookie
npm http 200 http://192.168.1.100:4873/content-disposition
npm http 200 http://192.168.1.100:4873/content-type
npm http 200 http://192.168.1.100:4873/cookie-signature
npm http 200 http://192.168.1.100:4873/depd
npm http 200 http://192.168.1.100:4873/escape-html
npm http 200 http://192.168.1.100:4873/accepts
npm http 200 http://192.168.1.100:4873/array-flatten
npm http 200 http://192.168.1.100:4873/etag
npm http 200 http://192.168.1.100:4873/finalhandler
npm http 200 http://192.168.1.100:4873/parseurl
npm http 200 http://192.168.1.100:4873/on-finished
npm http 200 http://192.168.1.100:4873/merge-descriptors
npm http 200 http://192.168.1.100:4873/methods
npm http 200 http://192.168.1.100:4873/fresh
npm http 200 http://192.168.1.100:4873/vary
npm http 200 http://192.168.1.100:4873/path-to-regexp
npm http 200 http://192.168.1.100:4873/range-parser
npm http 200 http://192.168.1.100:4873/utils-merge
npm http 200 http://192.168.1.100:4873/proxy-addr
npm http 200 http://192.168.1.100:4873/type-is
npm http 200 http://192.168.1.100:4873/qs
npm http 200 http://192.168.1.100:4873/send
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
npm http request GET http://192.168.1.100:4873/mime
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/statuses
npm http 200 http://192.168.1.100:4873/destroy
npm http 200 http://192.168.1.100:4873/mime
npm http 200 http://192.168.1.100:4873/statuses
npm http 200 http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/inherits
npm http 200 http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/media-typer
npm http 200 http://192.168.1.100:4873/media-typer
npm http request GET http://192.168.1.100:4873/fs-extra
npm http request GET http://192.168.1.100:4873/bluebird
npm http 200 http://192.168.1.100:4873/fs-extra
npm http 200 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/rimraf
npm http request GET http://192.168.1.100:4873/jsonfile
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http 200 http://192.168.1.100:4873/graceful-fs
npm http 200 http://192.168.1.100:4873/jsonfile
npm http 200 http://192.168.1.100:4873/rimraf
npm http request GET http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/fs.realpath
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http 200 http://192.168.1.100:4873/once
npm http 200 http://192.168.1.100:4873/path-is-absolute
npm http 200 http://192.168.1.100:4873/fs.realpath
npm http 200 http://192.168.1.100:4873/minimatch
npm http 200 http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/wrappy
npm http 200 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 200 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/balanced-match
npm http 200 http://192.168.1.100:4873/concat-map
npm http 200 http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/immediate
npm http 200 http://192.168.1.100:4873/immediate
npm http 200 http://192.168.1.100:4873/unreachable-branch-transform
npm http 200 http://192.168.1.100:4873/es3ify
npm http 200 http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/through
npm http 200 http://192.168.1.100:4873/jstransform
npm http 200 http://192.168.1.100:4873/through
npm http 200 http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/source-map
npm http 200 http://192.168.1.100:4873/base62
npm http 200 http://192.168.1.100:4873/source-map
npm http 200 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/esprima-fb
npm http 200 http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/recast
npm http 200 http://192.168.1.100:4873/commander
npm http 200 http://192.168.1.100:4873/private
npm http 200 http://192.168.1.100:4873/mkdirp
npm http 200 http://192.168.1.100:4873/detective
npm http 200 http://192.168.1.100:4873/iconv-lite
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
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/object-keys
npm http 200 http://192.168.1.100:4873/foreach
npm http 200 http://192.168.1.100:4873/isarray
npm http 200 http://192.168.1.100:4873/object-keys
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/xtend
npm http 200 http://192.168.1.100:4873/xtend
npm http 200 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/core-util-is
npm http request GET http://192.168.1.100:4873/string_decoder
npm http 200 http://192.168.1.100:4873/string_decoder
npm http 200 http://192.168.1.100:4873/core-util-is
npm http request GET http://192.168.1.100:4873/esmangle-evaluator
npm http 200 http://192.168.1.100:4873/esmangle-evaluator
npm http request GET http://192.168.1.100:4873/has-binary-data
npm http request GET http://192.168.1.100:4873/engine.io
npm http request GET http://192.168.1.100:4873/socket.io-adapter
npm http request GET http://192.168.1.100:4873/socket.io-parser
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http 200 http://192.168.1.100:4873/has-binary-data
npm http 200 http://192.168.1.100:4873/socket.io-adapter
npm http 200 http://192.168.1.100:4873/socket.io-parser
npm http 200 http://192.168.1.100:4873/socket.io-client
npm http 200 http://192.168.1.100:4873/engine.io
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/base64id
npm http request GET http://192.168.1.100:4873/ws
npm http 200 http://192.168.1.100:4873/engine.io-parser
npm http 200 http://192.168.1.100:4873/base64id
npm http 200 http://192.168.1.100:4873/ws
npm http request GET http://192.168.1.100:4873/has-binary
npm http request GET http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/utf8
npm http 200 http://192.168.1.100:4873/has-binary
npm http 200 http://192.168.1.100:4873/base64-arraybuffer
npm http 200 http://192.168.1.100:4873/blob
npm http 200 http://192.168.1.100:4873/arraybuffer.slice
npm http 200 http://192.168.1.100:4873/after
npm http 200 http://192.168.1.100:4873/utf8
npm http request GET http://192.168.1.100:4873/options
npm http request GET http://192.168.1.100:4873/bufferutil
npm http request GET http://192.168.1.100:4873/ultron
npm http request GET http://192.168.1.100:4873/utf-8-validate
npm http 200 http://192.168.1.100:4873/options
npm http 200 http://192.168.1.100:4873/bufferutil
npm http 200 http://192.168.1.100:4873/ultron
npm http 200 http://192.168.1.100:4873/utf-8-validate
npm http request GET http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/nan
npm http 200 http://192.168.1.100:4873/bindings
npm http 200 http://192.168.1.100:4873/nan
npm http request GET http://192.168.1.100:4873/json3
npm http request GET http://192.168.1.100:4873/component-emitter
npm http request GET http://192.168.1.100:4873/benchmark
npm http 200 http://192.168.1.100:4873/component-emitter
npm http 200 http://192.168.1.100:4873/benchmark
npm http 200 http://192.168.1.100:4873/json3
npm http request GET http://192.168.1.100:4873/backo2
npm http request GET http://192.168.1.100:4873/to-array
npm http request GET http://192.168.1.100:4873/parseuri
npm http request GET http://192.168.1.100:4873/indexof
npm http request GET http://192.168.1.100:4873/object-component
npm http request GET http://192.168.1.100:4873/component-bind
npm http request GET http://192.168.1.100:4873/engine.io-client
npm http 200 http://192.168.1.100:4873/to-array
npm http 200 http://192.168.1.100:4873/indexof
npm http 200 http://192.168.1.100:4873/backo2
npm http 200 http://192.168.1.100:4873/parseuri
npm http 200 http://192.168.1.100:4873/object-component
npm http 200 http://192.168.1.100:4873/component-bind
npm http 200 http://192.168.1.100:4873/engine.io-client
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/parseqs
npm http fetch GET https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http 200 http://192.168.1.100:4873/parsejson
npm http 200 http://192.168.1.100:4873/parseqs
npm http 200 http://192.168.1.100:4873/has-cors
npm http 200 http://192.168.1.100:4873/component-inherit
npm http fetch 200 https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
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
npm http request GET http://192.168.1.100:4873/pkginfo
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/colors
npm http request GET http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/stack-trace
npm http 200 http://192.168.1.100:4873/pkginfo
npm http 200 http://192.168.1.100:4873/cycle
npm http 200 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/colors
npm http 200 http://192.168.1.100:4873/async
npm http 200 http://192.168.1.100:4873/eyes
npm http 200 http://192.168.1.100:4873/stack-trace
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/tape
npm http 200 http://192.168.1.100:4873/node-uuid
npm http 200 http://192.168.1.100:4873/tape
npm http request GET http://192.168.1.100:4873/jsonify
npm http request GET http://192.168.1.100:4873/deep-equal
npm http 200 http://192.168.1.100:4873/deep-equal
npm http 200 http://192.168.1.100:4873/jsonify
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
npm http request GET http://192.168.1.100:4873/forever-agent
npm http request GET http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/javascript-state-machine
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/salti
npm http request GET http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/lie
npm http 304 http://192.168.1.100:4873/express
npm http 200 http://192.168.1.100:4873/forever-agent
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 200 http://192.168.1.100:4873/ip
npm http 200 http://192.168.1.100:4873/body-parser
npm http 200 http://192.168.1.100:4873/javascript-state-machine
npm http 200 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/multiplex
npm http 200 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/salti
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/type-is
npm http 200 http://192.168.1.100:4873/bytes
npm http 304 http://192.168.1.100:4873/qs
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
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/proxy-addr
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
npm http 304 http://192.168.1.100:4873/unreachable-branch-transform
npm http 304 http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/through
npm http 304 http://192.168.1.100:4873/esprima
npm http 304 http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/through
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/base62
npm http 304 http://192.168.1.100:4873/commoner
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
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http 304 http://192.168.1.100:4873/detective
npm http 304 http://192.168.1.100:4873/commander
npm http 304 http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/mkdirp
npm http 304 http://192.168.1.100:4873/q
npm http 304 http://192.168.1.100:4873/private
npm http 304 http://192.168.1.100:4873/recast
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http 304 http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/acorn
npm http request GET http://192.168.1.100:4873/defined
npm http 304 http://192.168.1.100:4873/defined
npm http 304 http://192.168.1.100:4873/acorn
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/inflight
npm http 304 http://192.168.1.100:4873/minimatch
npm http 304 http://192.168.1.100:4873/path-is-absolute
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
npm http 304 http://192.168.1.100:4873/falafel
npm http 304 http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/foreach
npm http 304 http://192.168.1.100:4873/object-keys
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/xtend
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
npm http 200 http://192.168.1.100:4873/duplexify
npm http 200 http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/stream-shift
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http 200 http://192.168.1.100:4873/end-of-stream
npm http 200 http://192.168.1.100:4873/stream-shift
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 200 http://192.168.1.100:4873/buffer-shims
npm http 200 http://192.168.1.100:4873/util-deprecate
npm http 200 http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/har-validator
npm http 200 http://192.168.1.100:4873/json-stringify-safe
npm http 200 http://192.168.1.100:4873/caseless
npm http 200 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/form-data
npm http 200 http://192.168.1.100:4873/bl
npm http 200 http://192.168.1.100:4873/aws-sign2
npm http 200 http://192.168.1.100:4873/oauth-sign
npm http 200 http://192.168.1.100:4873/http-signature
npm http 200 http://192.168.1.100:4873/tunnel-agent
npm http 200 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/stringstream
npm http 200 http://192.168.1.100:4873/combined-stream
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
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 200 http://192.168.1.100:4873/escape-string-regexp
npm http 200 http://192.168.1.100:4873/ansi-styles
npm http 200 http://192.168.1.100:4873/strip-ansi
npm http 200 http://192.168.1.100:4873/supports-color
npm http 200 http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 200 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 200 http://192.168.1.100:4873/jsonpointer
npm http 200 http://192.168.1.100:4873/generate-function
npm http 200 http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/is-property
npm http 200 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/boom
npm http 200 http://192.168.1.100:4873/hoek
npm http 200 http://192.168.1.100:4873/cryptiles
npm http 200 http://192.168.1.100:4873/sntp
npm http 200 http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/ctype
npm http 200 http://192.168.1.100:4873/ctype
npm http 200 http://192.168.1.100:4873/assert-plus
npm http 200 http://192.168.1.100:4873/asn1
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
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/marked
npm http request GET http://192.168.1.100:4873/requizzle
npm http request GET http://192.168.1.100:4873/underscore
npm http request GET http://192.168.1.100:4873/wrench
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 200 http://192.168.1.100:4873/js2xmlparser
npm http 200 http://192.168.1.100:4873/catharsis
npm http 200 http://192.168.1.100:4873/requizzle
npm http 200 http://192.168.1.100:4873/marked
npm http 200 http://192.168.1.100:4873/underscore
npm http 200 http://192.168.1.100:4873/wrench
npm WARN deprecated wrench@1.5.9: wrench.js is deprecated! You should check out fs-extra (https://github.com/jprichardson/node-fs-extra) for any operations you were using wrench for. Thanks for all the usage over the years.
npm http 200 http://192.168.1.100:4873/strip-json-comments
npm http fetch 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http request GET http://192.168.1.100:4873/underscore-contrib
npm http 200 http://192.168.1.100:4873/underscore-contrib
npm WARN prefer global marked@0.3.6 should be installed with -g
npm http request GET http://192.168.1.100:4873/fs-extra-promise
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/jxc
npm http request GET http://192.168.1.100:4873/unzip
npm http 304 http://192.168.1.100:4873/fs-extra-promise
npm http 304 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/unzip
npm http 200 http://192.168.1.100:4873/lie
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
npm http 200 http://192.168.1.100:4873/graceful-fs
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
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/minimatch
npm http 304 http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/path-is-absolute
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
npm http 304 http://192.168.1.100:4873/immediate
npm http 304 http://192.168.1.100:4873/unreachable-branch-transform
npm http 200 http://192.168.1.100:4873/inline-process-browser
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
npm http 304 http://192.168.1.100:4873/commoner
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/commander
npm http 304 http://192.168.1.100:4873/detective
npm http 304 http://192.168.1.100:4873/mkdirp
npm http 200 http://192.168.1.100:4873/private
npm http 304 http://192.168.1.100:4873/q
npm http 304 http://192.168.1.100:4873/recast
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http 304 http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/acorn
npm http request GET http://192.168.1.100:4873/defined
npm http 304 http://192.168.1.100:4873/defined
npm http 304 http://192.168.1.100:4873/acorn
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
npm http request GET http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/object-keys
npm http 200 http://192.168.1.100:4873/foreach
npm http 304 http://192.168.1.100:4873/isarray
npm http 200 http://192.168.1.100:4873/object-keys
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/core-util-is
npm http request GET http://192.168.1.100:4873/string_decoder
npm http 304 http://192.168.1.100:4873/string_decoder
npm http 304 http://192.168.1.100:4873/core-util-is
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
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/forever-agent
npm http 200 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 200 http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 200 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/mime-db
npm http 304 http://192.168.1.100:4873/mime-db
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http 304 http://192.168.1.100:4873/chalk
npm http 304 http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/ansi-styles
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 200 http://192.168.1.100:4873/supports-color
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-function
npm http 200 http://192.168.1.100:4873/jsonpointer
npm http 200 http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/boom
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
npm http 200 http://192.168.1.100:4873/pullstream
npm http 200 http://192.168.1.100:4873/match-stream
npm http 200 http://192.168.1.100:4873/fstream
npm http 200 http://192.168.1.100:4873/binary
npm http 200 http://192.168.1.100:4873/setimmediate
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
npm http request GET http://192.168.1.100:4873/bn.js
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/express-pouchdb
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/leveldown-mobile
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/pouchdb-node
npm http request GET http://192.168.1.100:4873/proxyquire
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/nock
npm http request GET http://192.168.1.100:4873/tape
npm http request GET http://192.168.1.100:4873/sinon
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/request-promise
npm http request GET http://192.168.1.100:4873/supertest
npm http request GET http://192.168.1.100:4873/tape-catch
npm http request GET http://192.168.1.100:4873/supertest-as-promised
npm http request GET http://192.168.1.100:4873/tmp
npm http request GET http://192.168.1.100:4873/uuid
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/express
npm http 200 http://192.168.1.100:4873/forever-agent
npm http 200 http://192.168.1.100:4873/express-pouchdb
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/long
npm http 200 http://192.168.1.100:4873/bn.js
npm http 200 http://192.168.1.100:4873/js-extend
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/pouchdb-node
npm http 304 http://192.168.1.100:4873/socket.io-client
npm http 200 http://192.168.1.100:4873/proxyquire
npm http 304 http://192.168.1.100:4873/leveldown-mobile
npm http 200 http://192.168.1.100:4873/randomstring
npm http 304 http://192.168.1.100:4873/tape
npm http 200 http://192.168.1.100:4873/sinon
npm http 200 http://192.168.1.100:4873/urlsafe-base64
npm http 304 http://192.168.1.100:4873/multiplex
npm http 200 http://192.168.1.100:4873/nock
npm http 200 http://192.168.1.100:4873/request-promise
npm http 200 http://192.168.1.100:4873/tape-catch
npm http 200 http://192.168.1.100:4873/supertest
npm http 200 http://192.168.1.100:4873/supertest-as-promised
npm http 200 http://192.168.1.100:4873/tmp
npm http 200 http://192.168.1.100:4873/uuid
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
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/on-finished
npm http 200 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/type-is
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/raw-body
npm http 200 http://192.168.1.100:4873/debug
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
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/send
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/serve-static
npm http 304 http://192.168.1.100:4873/vary
npm http 304 http://192.168.1.100:4873/utils-merge
npm http request GET http://192.168.1.100:4873/negotiator
npm http 304 http://192.168.1.100:4873/negotiator
npm http request GET http://192.168.1.100:4873/forwarded
npm http request GET http://192.168.1.100:4873/ipaddr.js
npm http 304 http://192.168.1.100:4873/ipaddr.js
npm http 304 http://192.168.1.100:4873/forwarded
npm http request GET http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/mime
npm http 200 http://192.168.1.100:4873/mime
npm http 304 http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/basic-auth
npm http request GET http://192.168.1.100:4873/cookie-parser
npm http request GET http://192.168.1.100:4873/compression
npm http request GET http://192.168.1.100:4873/header-case-normalizer
npm http request GET http://192.168.1.100:4873/multiparty
npm http request GET http://192.168.1.100:4873/pouchdb-all-dbs
npm http request GET http://192.168.1.100:4873/pouchdb-list
npm http request GET http://192.168.1.100:4873/pouchdb-find
npm http request GET http://192.168.1.100:4873/pouchdb-auth
npm http request GET http://192.168.1.100:4873/pouchdb-vhost
npm http request GET http://192.168.1.100:4873/pouchdb-validation
npm http request GET http://192.168.1.100:4873/pouchdb-update
npm http request GET http://192.168.1.100:4873/pouchdb-size
npm http request GET http://192.168.1.100:4873/pouchdb-show
npm http request GET http://192.168.1.100:4873/pouchdb-security
npm http request GET http://192.168.1.100:4873/pouchdb-rewrite
npm http request GET http://192.168.1.100:4873/pouchdb-replicator
npm http request GET http://192.168.1.100:4873/pouchdb-wrappers
npm http 304 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/multiparty
npm http 200 http://192.168.1.100:4873/basic-auth
npm http 200 http://192.168.1.100:4873/cookie-parser
npm http 200 http://192.168.1.100:4873/header-case-normalizer
npm http 200 http://192.168.1.100:4873/compression
npm http 200 http://192.168.1.100:4873/pouchdb-vhost
npm http 200 http://192.168.1.100:4873/pouchdb-list
npm http 200 http://192.168.1.100:4873/pouchdb-find
npm http 200 http://192.168.1.100:4873/pouchdb-auth
npm http 304 http://192.168.1.100:4873/pouchdb-all-dbs
npm http 200 http://192.168.1.100:4873/pouchdb-show
npm http 200 http://192.168.1.100:4873/pouchdb-size
npm http 200 http://192.168.1.100:4873/pouchdb-validation
npm http 304 http://192.168.1.100:4873/pouchdb-update
npm http 200 http://192.168.1.100:4873/pouchdb-security
npm http 200 http://192.168.1.100:4873/pouchdb-rewrite
npm http 200 http://192.168.1.100:4873/pouchdb-wrappers
npm http 304 http://192.168.1.100:4873/pouchdb-replicator
npm http request GET http://192.168.1.100:4873/setprototypeof
npm http 200 http://192.168.1.100:4873/setprototypeof
npm http request GET http://192.168.1.100:4873/compressible
npm http request GET http://192.168.1.100:4873/on-headers
npm http 200 http://192.168.1.100:4873/compressible
npm http 200 http://192.168.1.100:4873/on-headers
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/stream-counter
npm http 200 http://192.168.1.100:4873/stream-counter
npm http 304 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/argsarray
npm http request GET http://192.168.1.100:4873/tiny-queue
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/es3ify
npm http 200 http://192.168.1.100:4873/argsarray
npm http 200 http://192.168.1.100:4873/pouchdb-promise
npm http 200 http://192.168.1.100:4873/tiny-queue
npm http request GET http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/base62
npm http 304 http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/couchdb-calculate-session-id
npm http request GET http://192.168.1.100:4873/crypto-lite
npm http request GET http://192.168.1.100:4873/pouchdb
npm http request GET http://192.168.1.100:4873/base64url
npm http request GET http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http request GET http://192.168.1.100:4873/pouchdb-plugin-error
npm http request GET http://192.168.1.100:4873/pouchdb-req-http-query
npm http request GET http://192.168.1.100:4873/pouchdb-system-db
npm http request GET http://192.168.1.100:4873/promise-nodify
npm http request GET http://192.168.1.100:4873/secure-random
npm http 200 http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http 200 http://192.168.1.100:4873/pouchdb
npm http 200 http://192.168.1.100:4873/base64url
npm http 200 http://192.168.1.100:4873/couchdb-calculate-session-id
npm http 200 http://192.168.1.100:4873/pouchdb-req-http-query
npm http 200 http://192.168.1.100:4873/pouchdb-plugin-error
npm http 200 http://192.168.1.100:4873/crypto-lite
npm http 200 http://192.168.1.100:4873/pouchdb-system-db
npm http 200 http://192.168.1.100:4873/promise-nodify
npm http 200 http://192.168.1.100:4873/secure-random
npm http request GET http://192.168.1.100:4873/meow
npm http request GET http://192.168.1.100:4873/concat-stream
npm http 200 http://192.168.1.100:4873/meow
npm http 200 http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/typedarray
npm http 200 http://192.168.1.100:4873/typedarray
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/camelcase-keys
npm http request GET http://192.168.1.100:4873/indent-string
npm http 304 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/indent-string
npm http 200 http://192.168.1.100:4873/camelcase-keys
npm http request GET http://192.168.1.100:4873/map-obj
npm http request GET http://192.168.1.100:4873/camelcase
npm http 200 http://192.168.1.100:4873/camelcase
npm http 200 http://192.168.1.100:4873/map-obj
npm http request GET http://192.168.1.100:4873/get-stdin
npm http request GET http://192.168.1.100:4873/repeating
npm http 200 http://192.168.1.100:4873/repeating
npm http 200 http://192.168.1.100:4873/get-stdin
npm http request GET http://192.168.1.100:4873/is-finite
npm http 200 http://192.168.1.100:4873/is-finite
npm http request GET http://192.168.1.100:4873/number-is-nan
npm http 200 http://192.168.1.100:4873/number-is-nan
npm http request GET http://192.168.1.100:4873/aproba
npm http 200 http://192.168.1.100:4873/aproba
npm http request GET http://192.168.1.100:4873/level-write-stream
npm http request GET http://192.168.1.100:4873/es6-promise-pool
npm http request GET http://192.168.1.100:4873/fruitdown
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/localstorage-down
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/memdown
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/pouchdb-collate
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/scope-eval
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/vuvuzela
npm http 200 http://192.168.1.100:4873/level-write-stream
npm http 200 http://192.168.1.100:4873/fruitdown
npm http 200 http://192.168.1.100:4873/double-ended-queue
npm http 200 http://192.168.1.100:4873/es6-promise-pool
npm http 200 http://192.168.1.100:4873/localstorage-down
npm http 304 http://192.168.1.100:4873/through2
npm http 200 http://192.168.1.100:4873/scope-eval
npm http 200 http://192.168.1.100:4873/memdown
npm http 200 http://192.168.1.100:4873/spark-md5
npm http 200 http://192.168.1.100:4873/levelup
npm http 200 http://192.168.1.100:4873/pouchdb-collate
npm http 200 http://192.168.1.100:4873/sublevel-pouchdb
npm http 200 http://192.168.1.100:4873/vuvuzela
npm http 200 http://192.168.1.100:4873/pouchdb-collections
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
npm http request GET http://192.168.1.100:4873/deferred-leveldown
npm http request GET http://192.168.1.100:4873/level-codec
npm http request GET http://192.168.1.100:4873/level-errors
npm http request GET http://192.168.1.100:4873/level-iterator-stream
npm http request GET http://192.168.1.100:4873/prr
npm http request GET http://192.168.1.100:4873/semver
npm http 200 http://192.168.1.100:4873/deferred-leveldown
npm http 200 http://192.168.1.100:4873/prr
npm http 200 http://192.168.1.100:4873/level-codec
npm http 200 http://192.168.1.100:4873/level-iterator-stream
npm http 200 http://192.168.1.100:4873/level-errors
npm http 200 http://192.168.1.100:4873/semver
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
npm http 200 http://192.168.1.100:4873/functional-red-black-tree
npm http 200 http://192.168.1.100:4873/ltgt
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/aws4
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/is-typedarray
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/http-signature
npm http 200 http://192.168.1.100:4873/is-typedarray
npm http 304 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/aws4
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm WARN deprecated tough-cookie@2.2.2: ReDoS vulnerability parsing Set-Cookie https://nodesecurity.io/advisories/130
npm http 304 http://192.168.1.100:4873/qs
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
npm http 304 http://192.168.1.100:4873/chalk
npm http 304 http://192.168.1.100:4873/is-my-json-valid
npm http 200 http://192.168.1.100:4873/pinkie-promise
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http 200 http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-function
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
npm http 200 http://192.168.1.100:4873/sshpk
npm http 200 http://192.168.1.100:4873/jsprim
npm http request GET http://192.168.1.100:4873/json-schema
npm http request GET http://192.168.1.100:4873/verror
npm http request GET http://192.168.1.100:4873/extsprintf
npm http 200 http://192.168.1.100:4873/json-schema
npm http 200 http://192.168.1.100:4873/extsprintf
npm http 200 http://192.168.1.100:4873/verror
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/getpass
npm http request GET http://192.168.1.100:4873/dashdash
npm http 200 http://192.168.1.100:4873/dashdash
npm http 304 http://192.168.1.100:4873/asn1
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
npm http 200 http://192.168.1.100:4873/xmlhttprequest-cookie
npm http request GET http://192.168.1.100:4873/xmlhttprequest
npm http 200 http://192.168.1.100:4873/xmlhttprequest
npm http request GET http://192.168.1.100:4873/pouchdb-changeslike-wrapper
npm http 200 http://192.168.1.100:4873/pouchdb-changeslike-wrapper
npm http request GET http://192.168.1.100:4873/couchdb-eval
npm http request GET http://192.168.1.100:4873/couchdb-objects
npm http request GET http://192.168.1.100:4873/random-uuid-v4
npm http 200 http://192.168.1.100:4873/couchdb-objects
npm http 200 http://192.168.1.100:4873/random-uuid-v4
npm http 200 http://192.168.1.100:4873/couchdb-eval
npm http request GET http://192.168.1.100:4873/is-empty
npm http 200 http://192.168.1.100:4873/is-empty
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/is-array
npm http request GET http://192.168.1.100:4873/pouchdb-extend
npm http request GET http://192.168.1.100:4873/pouchdb-upsert
npm http 304 http://192.168.1.100:4873/spark-md5
npm http 200 http://192.168.1.100:4873/is-array
npm http 200 http://192.168.1.100:4873/pouchdb-upsert
npm http 200 http://192.168.1.100:4873/pouchdb-extend
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 304 http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/couchdb-render
npm http 304 http://192.168.1.100:4873/couchdb-render
npm http request GET http://192.168.1.100:4873/couchdb-resp-completer
npm http 304 http://192.168.1.100:4873/couchdb-resp-completer
npm http request GET http://192.168.1.100:4873/equals
npm http 304 http://192.168.1.100:4873/equals
npm http request GET http://192.168.1.100:4873/jkroso-type
npm http 200 http://192.168.1.100:4873/jkroso-type
npm http request GET http://192.168.1.100:4873/pouchdb-route
npm http 304 http://192.168.1.100:4873/pouchdb-route
npm http request GET http://192.168.1.100:4873/get-folder-size
npm http 200 http://192.168.1.100:4873/get-folder-size
npm http request GET http://192.168.1.100:4873/minimist
npm http 304 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/fast-future
npm http 304 http://192.168.1.100:4873/bindings
npm http 304 http://192.168.1.100:4873/abstract-leveldown
npm http 200 http://192.168.1.100:4873/fast-future
npm http request GET http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/duplexify
npm http 304 http://192.168.1.100:4873/duplexify
npm http 304 http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/stream-shift
npm http 304 http://192.168.1.100:4873/end-of-stream
npm http 304 http://192.168.1.100:4873/stream-shift
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http 304 http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/deep-equal
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/propagate
npm http request GET http://192.168.1.100:4873/chai
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/deep-equal
npm http 200 http://192.168.1.100:4873/lodash
npm http 200 http://192.168.1.100:4873/propagate
npm http 200 http://192.168.1.100:4873/chai
npm WARN deprecated lodash@2.4.1: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
npm http request GET http://192.168.1.100:4873/deep-eql
npm http request GET http://192.168.1.100:4873/assertion-error
npm http request GET http://192.168.1.100:4873/type-detect
npm http 200 http://192.168.1.100:4873/assertion-error
npm http 200 http://192.168.1.100:4873/type-detect
npm http 200 http://192.168.1.100:4873/deep-eql
npm http request GET http://192.168.1.100:4873/ms
npm http 200 http://192.168.1.100:4873/ms
npm http fetch GET http://192.168.1.100:4873/ms/-/ms-0.6.2.tgz
npm http fetch 200 http://192.168.1.100:4873/ms/-/ms-0.6.2.tgz
npm http request GET http://192.168.1.100:4873/ip
npm http 304 http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-leveldb
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-http
npm http request GET http://192.168.1.100:4873/pouchdb-core
npm http request GET http://192.168.1.100:4873/pouchdb-replication
npm http request GET http://192.168.1.100:4873/pouchdb-mapreduce
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-leveldb
npm http 304 http://192.168.1.100:4873/pouchdb-replication
npm http 304 http://192.168.1.100:4873/pouchdb-mapreduce
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-http
npm http 304 http://192.168.1.100:4873/pouchdb-core
npm http request GET http://192.168.1.100:4873/pouchdb-ajax
npm http request GET http://192.168.1.100:4873/pouchdb-binary-utils
npm http request GET http://192.168.1.100:4873/pouchdb-errors
npm http request GET http://192.168.1.100:4873/pouchdb-utils
npm http request GET http://192.168.1.100:4873/pouchdb-md5
npm http 304 http://192.168.1.100:4873/pouchdb-md5
npm http 304 http://192.168.1.100:4873/pouchdb-errors
npm http 304 http://192.168.1.100:4873/pouchdb-ajax
npm http 200 http://192.168.1.100:4873/pouchdb-utils
npm http 304 http://192.168.1.100:4873/pouchdb-binary-utils
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http 304 http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-leveldb-core
npm http request GET http://192.168.1.100:4873/leveldown
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-leveldb-core
npm http 200 http://192.168.1.100:4873/leveldown
npm http request GET http://192.168.1.100:4873/nan
npm http request GET http://192.168.1.100:4873/prebuild
npm http 304 http://192.168.1.100:4873/nan
npm http 200 http://192.168.1.100:4873/prebuild
npm http request GET http://192.168.1.100:4873/npmlog
npm http request GET http://192.168.1.100:4873/os-homedir
npm http request GET http://192.168.1.100:4873/node-ninja
npm http request GET http://192.168.1.100:4873/noop-logger
npm http request GET http://192.168.1.100:4873/github-from-package
npm http request GET http://192.168.1.100:4873/ghreleases
npm http request GET http://192.168.1.100:4873/expand-template
npm http request GET http://192.168.1.100:4873/rc
npm http request GET http://192.168.1.100:4873/pump
npm http request GET http://192.168.1.100:4873/node-gyp
npm http request GET http://192.168.1.100:4873/simple-get
npm http request GET http://192.168.1.100:4873/tar-fs
npm http request GET http://192.168.1.100:4873/tar-stream
npm http 200 http://192.168.1.100:4873/os-homedir
npm http 200 http://192.168.1.100:4873/noop-logger
npm http 200 http://192.168.1.100:4873/github-from-package
npm http 200 http://192.168.1.100:4873/npmlog
npm http 200 http://192.168.1.100:4873/node-ninja
npm http 200 http://192.168.1.100:4873/pump
npm http 200 http://192.168.1.100:4873/rc
npm http 200 http://192.168.1.100:4873/expand-template
npm http 200 http://192.168.1.100:4873/ghreleases
npm http 200 http://192.168.1.100:4873/node-gyp
npm http 200 http://192.168.1.100:4873/tar-fs
npm http 200 http://192.168.1.100:4873/simple-get
npm http 200 http://192.168.1.100:4873/tar-stream
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/simple-mime
npm http request GET http://192.168.1.100:4873/ghutils
npm http request GET http://192.168.1.100:4873/ghrepos
npm http request GET http://192.168.1.100:4873/url-template
npm http 304 http://192.168.1.100:4873/after
npm http 200 http://192.168.1.100:4873/ghrepos
npm http 200 http://192.168.1.100:4873/simple-mime
npm http 200 http://192.168.1.100:4873/url-template
npm http 200 http://192.168.1.100:4873/ghutils
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
npm http request GET http://192.168.1.100:4873/osenv
npm http request GET http://192.168.1.100:4873/nopt
npm http request GET http://192.168.1.100:4873/path-array
npm http request GET http://192.168.1.100:4873/tar
npm http request GET http://192.168.1.100:4873/which
npm http 304 http://192.168.1.100:4873/fstream
npm http 200 http://192.168.1.100:4873/tar
npm http 200 http://192.168.1.100:4873/osenv
npm http 200 http://192.168.1.100:4873/path-array
npm http 200 http://192.168.1.100:4873/nopt
npm http 200 http://192.168.1.100:4873/which
npm http request GET http://192.168.1.100:4873/abbrev
npm http 200 http://192.168.1.100:4873/abbrev
npm http request GET http://192.168.1.100:4873/ansi
npm http request GET http://192.168.1.100:4873/are-we-there-yet
npm http request GET http://192.168.1.100:4873/gauge
npm http 200 http://192.168.1.100:4873/are-we-there-yet
npm http 304 http://192.168.1.100:4873/ansi
npm http 200 http://192.168.1.100:4873/gauge
npm http request GET http://192.168.1.100:4873/delegates
npm http 200 http://192.168.1.100:4873/delegates
npm http request GET http://192.168.1.100:4873/has-unicode
npm http request GET http://192.168.1.100:4873/lodash.padstart
npm http request GET http://192.168.1.100:4873/lodash.pad
npm http request GET http://192.168.1.100:4873/lodash.padend
npm http 200 http://192.168.1.100:4873/has-unicode
npm http 200 http://192.168.1.100:4873/lodash.padend
npm http 200 http://192.168.1.100:4873/lodash.padstart
npm http 200 http://192.168.1.100:4873/lodash.pad
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
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/aws-sign2
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
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/deep-extend
npm http request GET http://192.168.1.100:4873/ini
npm http 304 http://192.168.1.100:4873/strip-json-comments
npm http 304 http://192.168.1.100:4873/deep-extend
npm http 200 http://192.168.1.100:4873/ini
npm WARN engine deep-extend@0.4.1: wanted: {"node":">=0.12.0","iojs":">=1.0.0"} (current: {"node":"0.10.40","npm":"3.3.12"})
npm http request GET http://192.168.1.100:4873/unzip-response
npm http 304 http://192.168.1.100:4873/unzip-response
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/pouchdb-json
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-utils
npm http request GET http://192.168.1.100:4873/pouchdb-merge
npm http 304 http://192.168.1.100:4873/sublevel-pouchdb
npm http 304 http://192.168.1.100:4873/pouchdb-json
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-utils
npm http 304 http://192.168.1.100:4873/pouchdb-merge
npm http request GET http://192.168.1.100:4873/ltgt
npm http 304 http://192.168.1.100:4873/ltgt
npm http request GET http://192.168.1.100:4873/pouchdb-mapreduce-utils
npm http 304 http://192.168.1.100:4873/pouchdb-mapreduce-utils
npm http request GET http://192.168.1.100:4873/pouchdb-checkpointer
npm http request GET http://192.168.1.100:4873/pouchdb-generate-replication-id
npm http 304 http://192.168.1.100:4873/pouchdb-generate-replication-id
npm http 304 http://192.168.1.100:4873/pouchdb-checkpointer
npm http request GET http://192.168.1.100:4873/fill-keys
npm http request GET http://192.168.1.100:4873/module-not-found-error
npm http 200 http://192.168.1.100:4873/module-not-found-error
npm http 200 http://192.168.1.100:4873/fill-keys
npm http request GET http://192.168.1.100:4873/is-object
npm http 200 http://192.168.1.100:4873/is-object
npm http request GET http://192.168.1.100:4873/array-uniq
npm http 200 http://192.168.1.100:4873/array-uniq
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/formatio
npm http request GET http://192.168.1.100:4873/lolex
npm http request GET http://192.168.1.100:4873/util
npm http request GET http://192.168.1.100:4873/samsam
npm http 200 http://192.168.1.100:4873/lolex
npm http 200 http://192.168.1.100:4873/formatio
npm http 200 http://192.168.1.100:4873/util
npm http 200 http://192.168.1.100:4873/samsam
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
npm http 304 http://192.168.1.100:4873/socket.io-parser
npm http 304 http://192.168.1.100:4873/component-bind
npm http 304 http://192.168.1.100:4873/engine.io-client
npm http 304 http://192.168.1.100:4873/has-binary
npm http 304 http://192.168.1.100:4873/parseuri
npm http 200 http://192.168.1.100:4873/indexof
npm http 304 http://192.168.1.100:4873/debug
npm http 200 http://192.168.1.100:4873/component-emitter
npm http 200 http://192.168.1.100:4873/object-component
npm http 304 http://192.168.1.100:4873/backo2
npm http 304 http://192.168.1.100:4873/to-array
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/parseqs
npm http request GET http://192.168.1.100:4873/ws
npm http fetch GET https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http 304 http://192.168.1.100:4873/has-cors
npm http 304 http://192.168.1.100:4873/component-inherit
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
npm http 304 http://192.168.1.100:4873/base64-arraybuffer
npm http 304 http://192.168.1.100:4873/utf8
npm http 304 http://192.168.1.100:4873/arraybuffer.slice
npm http 304 http://192.168.1.100:4873/blob
npm http fetch GET https://github.com/component/global/archive/v2.0.1.tar.gz
npm http fetch 200 https://github.com/component/global/archive/v2.0.1.tar.gz
npm http request GET http://192.168.1.100:4873/better-assert
npm http 200 http://192.168.1.100:4873/better-assert
npm http request GET http://192.168.1.100:4873/callsite
npm http 304 http://192.168.1.100:4873/callsite
npm http request GET http://192.168.1.100:4873/options
npm http request GET http://192.168.1.100:4873/ultron
npm http 304 http://192.168.1.100:4873/ultron
npm http 200 http://192.168.1.100:4873/options
npm http request GET http://192.168.1.100:4873/json3
npm http request GET http://192.168.1.100:4873/benchmark
npm http 304 http://192.168.1.100:4873/benchmark
npm http 304 http://192.168.1.100:4873/json3
npm http request GET http://192.168.1.100:4873/superagent
npm http 200 http://192.168.1.100:4873/superagent
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/formidable
npm http request GET http://192.168.1.100:4873/cookiejar
npm http request GET http://192.168.1.100:4873/reduce-component
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 200 http://192.168.1.100:4873/formidable
npm http 200 http://192.168.1.100:4873/reduce-component
npm http 200 http://192.168.1.100:4873/cookiejar
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/async
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
npm http 200 http://192.168.1.100:4873/resumer
npm http 200 http://192.168.1.100:4873/defined
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

npm ERR! Darwin 14.5.0
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
