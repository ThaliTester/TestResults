#### Test (Fail) 79751015 Build Logs


```


```

```
Already up-to-date.

From https://github.com/thaliproject/Thali_CordovaPlugin
   c7ac8a6..ebd1fc8  vNext_aevsyuchenya_769 -> origin/vNext_aevsyuchenya_769
   05baaca..81c1e09  vNext_czyzm_780_temp -> origin/vNext_czyzm_780_temp
   24dd5eb..63ba677  vNext_ilya_771 -> origin/vNext_ilya_771

```

```
Your branch is up-to-date with 'origin/master'.
Branch vNext set up to track remote branch vNext from origin.
Merge made by the 'recursive' strategy.
 scripts/androidBeforeCompile.js | 1 -
 1 file changed, 1 deletion(-)

Already on 'master'
Switched to a new branch 'vNext'
Note: checking out '81c1e09'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at 81c1e09... Rerun
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
DEBUG createNativeListener: listening 49854
ok 1 Should throw
# teardown
# setup
# emits incomingConnectionState
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49856
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
DEBUG createNativeListener: listening 49859
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
DEBUG createNativeListener: listening 49863
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
DEBUG createNativeListener: listening 49868
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
DEBUG createNativeListener: listening 49872
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
DEBUG createNativeListener: listening 49876
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
DEBUG createNativeListener: listening 49880
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
DEBUG createNativeListener: listening 49884
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
DEBUG createNativeListener: listening 49936
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
DEBUG createNativeListener: listening 49940
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
DEBUG createNativeListener: listening 49945
# teardown
# setup
# calling createPeerListener after calling stop produces error
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49948
# teardown
# setup
# can call createPeerListener (pleaseConnect === false)
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49951
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
ok 45 port must be in range
# teardown
# setup
# calling createPeerListener (pleaseConnect === true) with unknown peer is error
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49955
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
DEBUG createNativeListener: listening 49960
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
ok 47 port values should be the same
# teardown
# setup
# createPeerListener - closing connection to native listener closes everything and triggers new listener
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49964
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
DEBUG createNativeListener: listening 49973
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
DEBUG createNativeListener: listening 49982
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
DEBUG createNativeListener: listening 49988
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
DEBUG createNativeListener: listening 49995
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
DEBUG createNativeListener: listening 50000
DEBUG createPeerListener: pleaseConnect= false
ok 68 peerPort != nativePort
DEBUG createPeerListener: first connection
DEBUG createPeerListener: forward connection
ok 69 Should not get unexpected connection
# teardown
# setup
# peerListener - forwardConnection, pleaseConnect === false - with native server and data transfer
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50006
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
DEBUG createNativeListener: listening 50013
DEBUG createPeerListener: pleaseConnect= false
ok 74 Second call to existing peerListener returns existing port
# teardown
# setup
# createPeerListener - pleaseConnect === true, failed connection rejects promise
DEBUG createNativeListener: creating native server
ok 75 Can call startUpdateAdvertisingAndListening without error
ok 76 Can call startListeningForAdvertisements without error
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createNativeListener: listening 50017
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
DEBUG createNativeListener: listening 50022
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
DEBUG createNativeListener: listening 50027
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
DEBUG createNativeListener: listening 50032
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
DEBUG createNativeListener: listening 50038
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: first connection
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createPeerListener: looking up mux for client port:  50041
DEBUG createPeerListener: reverse connection
DEBUG createPeerListener: looking up mux for client port:  50041
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
DEBUG createNativeListener: listening 50044
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: first connection
DEBUG createPeerListener: looking up mux for client port:  50047
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createPeerListener: reverse connection
DEBUG createPeerListener: looking up mux for client port:  50047
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
DEBUG createNativeListener: listening 50051
# teardown
# setup
# createPeerListener - ask for a new peer when we are not at maximum peers and make sure we do not remove any existing listeners
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50054
# teardown
# setup
# createPeerListener - pleaseConnect = false - test timeout
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50057
# teardown
# setup
# createPeerListener - pleaseConnect = true - test timeout
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50060
# teardown
# setup
# createPeerListener - forward connection - wrong serverPort
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50063
# teardown
# setup
# createPeerListener - forward connection - wrong clientPort
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50066
# teardown
# setup
# createPeerListener - please connect = false, multiple connections out
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50069
# teardown
# setup
# createPeerListener - please connect = false, multiple bi-directional connections
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50072
# teardown
# setup
# createPeerListener - multiple parallel calls
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50075
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
DEBUG createNativeListener: listening 50152
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
DEBUG createNativeListener: listening 50154
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
DEBUG createNativeListener: listening 50156
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
DEBUG createNativeListener: listening 50161
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
DEBUG createNativeListener: listening 50163
ok 192 first call should succeed
ok 193 first call should succeed
ok 194 specific error should be returned
# teardown
ok 195 error should be null
ok 196 error should be null
# setup
# does not emit duplicate discoveryAdvertisingStateUpdate
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50165
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
DEBUG createNativeListener: listening 50170
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
DEBUG createNativeListener: listening 50172
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
DEBUG createNativeListener: listening 50177
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
DEBUG createNativeListener: listening 50179
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
# Test BEACONS_RETRIEVED_AND_PARSED locally
ok 261 peerIdentifier should be identifier
ok 262 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 263 good beacon
ok 264 good preAmble
ok 265 public keys match!
ok 266 must return null after successful call
ok 267 Once start returns the action should be in KILLED state
# teardown
# setup
# Test HTTP_BAD_RESPONSE locally
ok 268 Response should be HTTP_BAD_RESPONSE
ok 269 must return null after successful call
# teardown
# setup
# Test NETWORK_PROBLEM locally
ok 270 Response should be NETWORK_PROBLEM
ok 271 reject reason should be: Could not establish TCP connection
# teardown
# setup
# Call the start two times
ok 272 Call start once
ok 273 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 274 must return null after successful call.
# teardown
# setup
# Call the kill before calling the start
ok 275 Should be Killed
ok 276 Start after killed
# teardown
# setup
# Call the kill immediately after the start
ok 277 Should be KILLED
ok 278 must return null after successful kill
# teardown
# setup
# Call the kill while waiting a response from the server
ok 279 Should be KILLED
ok 280 must return null after successful kill
# teardown
# setup
# Test to exceed the max content size locally
ok 281 HTTP_BAD_RESPONSE should be response when content size is exceeded
ok 282 must return null after successful call
# teardown
# setup
# Close the server socket while the client is waiting a response from the server. Local test.
ok 283 Should be NETWORK_PROBLEM caused closing server socket
ok 284 Should be Could not establish TCP connection
# teardown
# setup
# Close the client socket while the client is waiting a response from the server. Local test.
ok 285 Should be NETWORK_PROBLEM caused closing client socket
ok 286 Should be Could not establish TCP connection
# teardown
# setup
# #generatePreambleAndBeacons bad args
ok 287 publicKeysToNotify cannot be null
ok 288 ecdh for local device cannot be null
ok 289 milliseconds cannot be less than 0
ok 290 milliseconds cannot be 0
ok 291 milliseconds cannot be greater than one_day
# teardown
# setup
# #generatePreambleAndBeacons empty keys to notify
ok 292 should be equal
# teardown
# setup
# #generatePreambleAndBeacons multiple keys to notify
ok 293 should be equal
ok 294 should be equal
ok 295 (unnamed assert)
ok 296 should be equal
# teardown
# setup
# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
ok 297 should throw
# teardown
# setup
# #parseBeacons invalid expiration in beaconStreamWithPreAmble
ok 298 Preamble expiration must be a 64 bit integer
# teardown
# setup
# #parseBeacons expiration out of range lower
ok 299 Expiration out of range
# teardown
# setup
# #parseBeacons expiration out of range lower
ok 300 Expiration out of range
# teardown
# setup
# #parseBeacons no beacons returns null
ok 301 should be equal
# teardown
# setup
# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
ok 302 Malformed encrypted beacon key ID
# teardown
# setup
# #parseBeacons addressBookCallback fails decrypt
ok 303 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns no matches
ok 304 should be equal
ok 305 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns spurious match
ok 306 should be equal
ok 307 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns public key
ok 308 right number of calls to address book
ok 309 good preAmble
ok 310 good unencryptedKeyId
ok 311 good beacon
# teardown
# setup
# validate generatePskIdentityField
ok 312 decoded buffers match
# teardown
# setup
# validate generatePskSecret
ok 313 secrets match
# teardown
# setup
# validate generatePskSecrets
ok 314 Matching numbers
ok 315 We have an entry!
ok 316 keys match
ok 317 secrets match
ok 318 We have an entry!
ok 319 keys match
ok 320 secrets match
ok 321 We have an entry!
ok 322 keys match
ok 323 secrets match
# teardown
# setup
# validate generateBeaconStreamAndSecrets
ok 324 Streams have same length
ok 325 matching size
ok 326 keys match
ok 327 secrets match
# teardown
# setup
# Add two Peers.
ok 328 should be equal
ok 329 should be equal
ok 330 should be equal
ok 331 should be equal
ok 332 should be equal
# teardown
# setup
# TCP_NATIVE peer loses DNS
ok 333 should be equal
ok 334 should be equal
# teardown
# setup
# Received beacons with no values for us
ok 335 entry exists
ok 336 entry is resolved
# teardown
# setup
# Resolves an action locally
ok 337 Host address must match
ok 338 suggestedTCPTimeout must match
ok 339 connectionType must match
ok 340 portNumber must match
# teardown
# setup
# Resolves an action locally using ThaliPeerPoolDefault
ok 341 Host address must match
ok 342 suggestedTCPTimeout must match
ok 343 connectionType must match
ok 344 portNumber must match
# teardown
# setup
# Action fails because of a bad hostname.
ok 345 should be equal
ok 346 should be equal
ok 347 should be equal
# teardown
# setup
# hostaddress is removed when the action is running. 
ok 348 should be equal
# teardown
# setup
# Client to server request locally
ok 349 secrets are equal
ok 350 Public key matches with the server key
ok 351 Host address must match
ok 352 suggestedTCPTimeout must match
ok 353 connectionType must match
ok 354 portNumber must match
# teardown
# setup
# Test ThaliPskMapCache clean and expiration
ok 355 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
ok 356 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
ok 357 All entries should be expired after 1 second
# teardown
# setup
# Test ThaliPskMapCache getSecret and getPublic
ok 358 All keys need to be available in the cache
ok 359 All entries should be expired after 1 second
# teardown
# setup
# Test ThaliPskMapCache multiple entries
ok 360 Size of the cache should be 2
ok 361 Cache doesn't contain dictionary1
ok 362 Size of the cache should be 1
ok 363 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
# setup
# Start and stop ThaliNotificationServer
ok 364 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
ok 365 ThaliMobile.StopAdvertisingAndListeningshould be called once
# teardown
# setup
# Pass an empty array to ThaliNotificationServer.start
ok 366 StartUpdateAdvertisingAndListening should not be called
ok 367 ThaliMobile.StopAdvertisingAndListening should be called once
ok 368 no error
ok 369 should be 204
# teardown
# setup
# Pass a string to ThaliNotificationServer.start
ok 370 StartUpdateAdvertisingAndListening should not be called
# teardown
# setup
# Pass an empty parameter to ThaliNotificationServer.start
ok 371 StartUpdateAdvertisingAndListening should not be called
# teardown
# setup
# Make an HTTP request to /NotificationBeacons
ok 372 no error
ok 373 should be 200
ok 374 should be equal
ok 375 should be equal
ok 376 (unnamed assert)
ok 377 no error
ok 378 should be 204
# teardown
# setup
# Make an HTTP request to /NotificationBeacons (no keys)
ok 379 error should be null
ok 380 should be 204
# teardown
# setup
# Make an HTTP request to /NotificationBeaconsbefore calling start
ok 381 should be 404
# teardown
# setup
# #testThaliPeerAction - test getters
ok 382 getPeerIdentifier
ok 383 getConnectionType
ok 384 getActionType
ok 385 getActionState
ok 386 getPskIdentity
ok 387 getPskKey
# teardown
# setup
# #testThaliPeerAction - start and kill
ok 388 initial state
ok 389 after start
ok 390 after kill
# teardown
# setup
# #testThaliPeerAction - double start
ok 391 should be equal
# teardown
# setup
# #testThaliPeerAction - start after kill
ok 392 clean kill
ok 393 should be equal
# teardown
# setup
# #testThaliPeerAction - make sure ids are unique
ok 394 should not be equal
# teardown
# setup
# Test PeerConnectionInformation basics
ok 395 connection type works
ok 396 getHostAddress works
ok 397 getPortNumber works
ok 398 getSuggestedTCPTimeout works
# teardown
# setup
# Test PeerDictionary basic functionality
ok 399 Entry counter must be 1
ok 400 Size must be 1
ok 401 Entry counter must be 2
ok 402 Size must be 2
ok 403 Entry2 should not be found
ok 404 Size must be 1
ok 405 Size must be 0
# teardown
# setup
# Test PeerDictionary with multiple entries.
ok 406 Size must be100
ok 407 Entries between 20 and MAXSIZE + 20 should exist
ok 408 WAITING state entry should not be removed
# teardown
# setup
# RESOLVED entries are removed before WAITING state entry.
ok 409 Entries between 6 and MAXSIZE + 4 should exist
ok 410 Size should be MAXSIZE
ok 411 Size should be MAXSIZE+6
# teardown
# setup
# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
ok 412 WAITING state entry should not be removed
ok 413 Waiting entries between 6 and MAXSIZE + 4 should exist
ok 414 Size should be MAXSIZE
ok 415 entryCounter should be MAXSIZE+6
# teardown
# setup
# When CONTROLLED_BY_POOL entry is removed and kill is called.
ok 416 Kill should be called once
ok 417 Size should be 100
# teardown
# setup
# #ThaliPeerPoolInterface - bad enqueues
ok 418 null arg
ok 419 wrong arg type
ok 420 wrong state
# teardown
# setup
# #ThaliPeerPoolInterface - do not allow same object type
ok 421 good enqueue
ok 422 should be equal
# teardown
# setup
# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
ok 423 good enqueue
ok 424 2nd good enqueue
ok 425 we are in the pool
ok 426 We are out of the pool
ok 427 Action was killed
ok 428 The original kill was called too
ok 429 second item is still in queue
# teardown
# setup
# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
ok 430 good enqueue
ok 431 first kill
ok 432 second NOOP kill
# teardown
# setup
# Make sure peerDictionaryKey is reasonable
ok 433 equal keys
ok 434 not equal connection type
ok 435 same connection type, different buffer
# teardown
# setup
# Make sure start works
ok 436 First start and on called correctly
# teardown
# setup
# Make sure stop works
ok 437 second cleared dictionary
ok 438 First start and on called correctly
ok 439 First stop and removeListener called correctly
ok 440 first action kill called
ok 441 second action kill called
ok 442 first cleared dictionary
ok 443 second cleared dictionary
# teardown
# setup
# Simple peer event
ok 444 listener has been set
ok 445 peer dictionary has expected number of entries
ok 446 Dictionary and pool have same action
ok 447 ads match
ok 448 PouchDB matches
ok 449 DB Names match
ok 450 public keys match
ok 451 peer dictionary has expected number of entries
ok 452 Dictionary and pool have same action
ok 453 ads match
ok 454 PouchDB matches
ok 455 DB Names match
ok 456 public keys match
ok 457 start called once
ok 458 kill never called
ok 459 One entry left
ok 460 Dictionary and pool have same action
ok 461 Start never called
ok 462 Kill called once
ok 463 no entries left
ok 464 Third action is dead
ok 465 peer dictionary has expected number of entries
ok 466 Dictionary and pool have same action
ok 467 ads match
ok 468 PouchDB matches
ok 469 DB Names match
ok 470 public keys match
# teardown
# setup
# Server is not there
DEBUG thaliReplicationPeerAction: Got error on replication - Error: connect ECONNREFUSED
ok 471 right error
# teardown
# setup
# Server accepts & closes connection
DEBUG thaliReplicationPeerAction: Got error on replication - Error: socket hang up
ok 472 right error
# teardown
# setup
# Server always returns 500
DEBUG thaliReplicationPeerAction: Got error on replication - 
ok 473 Got error as expected
# teardown
# setup
# Server always returns 401
DEBUG thaliReplicationPeerAction: Got error on replication - 
ok 474 Got error as expected
# teardown
# setup
# Server always returns 403
DEBUG thaliReplicationPeerAction: Got error on replication - 
ok 475 Got error as expected
# teardown
# setup
# Make sure docs replicate
DEBUG thaliReplicationPeerAction: Replication resumed
DEBUG thaliReplicationPeerAction: Got paused with undefined
ok 476 should be equal
ok 477 All tests passed!
# teardown
# setup
# Do nothing and make sure we time out
DEBUG thaliReplicationPeerAction: Got paused with undefined
ok 478 action should be killed
ok 479 Error should be timed out
ok 480 No doc found
# teardown
# setup
# Do something and make sure we time out
DEBUG thaliReplicationPeerAction: Replication resumed
DEBUG thaliReplicationPeerAction: Got paused with undefined
ok 481 should be equal
ok 482 action should be killed
ok 483 Error should be timed out
# teardown
# setup
# Start replicating and then catch error when server goes
ok 484 socket hung up
# teardown
# setup
# compareBufferArrays
ok 485 should throw
ok 486 should throw
ok 487 (unnamed assert)
ok 488 (unnamed assert)
ok 489 (unnamed assert)
ok 490 (unnamed assert)
ok 491 (unnamed assert)
# teardown
# setup
# Call start twice and get error
ok 492 should throw
# teardown
# setup
# Start and make sure it runs
# teardown
# setup
# Make sure getTimeWhenRun is right after start
ok 493 (unnamed assert)
# teardown
# setup
# Make sure getTimeWhenRun is -1 after function is called
ok 494 should be equal
# teardown
# setup
# Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
ok 495 should be equal
ok 496 should be equal
ok 497 should throw
# teardown
# setup
# Test TransientState
ok 498 should throw
ok 499 should throw
ok 500 should be equal
ok 501 should be equal
ok 502 should be equal
ok 503 should be equal
ok 504 (unnamed assert)
ok 505 (unnamed assert)
# teardown
# setup
# No peers and empty database
ok 506 verify failed
ok 507 constructor called once
ok 508 constructor called with right args
ok 509 match start arg
ok 510 start called once
ok 511 stop called once
ok 512 stop after start
# teardown
# setup
# One peer and empty DB
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 513 verify failed
ok 514 constructor called once
ok 515 constructor called with right args
ok 516 match start arg
ok 517 start called once
ok 518 stop called once
ok 519 stop after start
# teardown
# setup
# One peer with _Local set behind current seq
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 520 verify failed
ok 521 constructor called once
ok 522 constructor called with right args
ok 523 match start arg
ok 524 start called once
ok 525 stop called once
ok 526 stop after start
# teardown
# setup
# One peer with _Local set equal to current seq
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 527 verify failed
ok 528 constructor called once
ok 529 constructor called with right args
ok 530 match start arg
ok 531 start called once
ok 532 stop called once
ok 533 stop after start
# teardown
# setup
# One peer with _Local set ahead of current seq (and no this should not happen)
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 534 verify failed
ok 535 constructor called once
ok 536 constructor called with right args
ok 537 match start arg
ok 538 start called once
ok 539 stop called once
ok 540 stop after start
# teardown
# setup
# Three peers, one not in DB, one behind and one ahead
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 541 verify failed
ok 542 constructor called once
ok 543 constructor called with right args
ok 544 match start arg
ok 545 start called once
ok 546 stop called once
ok 547 stop after start
# teardown
# setup
# More than maximum peers, make sure we only send maximum allowed
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 548 verify failed
ok 549 constructor called once
ok 550 constructor called with right args
ok 551 match start arg
ok 552 start called once
ok 553 stop called once
ok 554 stop after start
# teardown
# setup
# two peers with empty DB, update the doc
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 555 verify failed
ok 556 constructor called once
ok 557 constructor called with right args
ok 558 last start before stop
ok 559 empty first start
ok 560 full second start
ok 561 only 2 timers
# teardown
# setup
# add doc and make sure tokens refresh when they expire
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 562 verify failed
ok 563 constructor called once
ok 564 constructor called with right args
ok 565 start before stop
ok 566 We got at least 3 calls to start
ok 567 at least 3
ok 568 default 1
ok 569 1 run
ok 570 default 2
ok 571 2 run
ok 572 default 3
# teardown
# setup
# start and stop and start and stop
ok 573 start out null
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 574 back to null
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 575 still null
ok 576 verify failed
ok 577 constructor called once
ok 578 constructor called with right args
ok 579 first start before first stop
ok 580 first stop before second start
ok 581 second start before second stop
# teardown
# setup
# two identical starts in a row
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 582 verify failed
ok 583 constructor called once
ok 584 constructor called with right args
ok 585 (unnamed assert)
# teardown
# setup
# two different starts in a row
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 586 verify failed
ok 587 constructor called once
ok 588 constructor called with right args
ok 589 (unnamed assert)
ok 590 (unnamed assert)
# teardown
# setup
# two stops and a start and two stops
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 591 verify failed
ok 592 constructor called once
ok 593 constructor called with right args
ok 594 start before stop
# teardown
# setup
# we properly enqueue requests so no then needed
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 595 verify failed
ok 596 constructor called once
ok 597 constructor called with right args
ok 598 start before stop
# teardown
# setup
# test calculateSeqPointKeyId
ok 599 should be equal
ok 600 should be equal
# teardown
# setup
# can create servers manager
ok 601 serversManager must not be null
ok 602 serversManager must be an object
# teardown
# setup
# calling stop without start causes error
ok 603 We need to call start first
# teardown
# setup
# can start/stop servers manager
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50290
ok 604 port must be in range
# teardown
# setup
# starting twice resolves with listening port
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50291
ok 605 second start should return same port
# teardown
# setup
# terminateIncomingConnection will terminate a connection
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50293
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 606 we should be connected
DEBUG createNativeListener: incoming socket close
ok 607 now we are disconnected
# teardown
# setup
# terminate an Outgoing connection will terminate the server
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50295
# teardown
# setup
# terminate an Outgoing connection with wrong arguments is not harmful
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50296
# teardown
# setup
ok 608 should be in started state
# After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
ok 609 peer identifier should match
ok 610 host address should match
ok 611 port should match
ok 612 host address should be null
ok 613 port should should be null
# teardown
ok 614 should not be in started state
# setup
ok 615 should be in started state
# #startUpdateAdvertisingAndListening should use different USN after every invocation
ok 616 USN should have changed from the first one
ok 617 when receiving the second byebye, the first USN should be already set
# teardown
ok 618 should not be in started state
# setup
ok 619 should be in started state
# messages with invalid location or USN should be ignored
WARN thaliWifiInfrastructure: Failed to parse a valid port number from location: http://foo.bar:90000
ok 620 should not have emitted with invalid port
WARN thaliWifiInfrastructure: Received an invalid USN value: 
ok 621 should not have emitted with invalid USN
# teardown
ok 622 should not be in started state
# setup
ok 623 should be in started state
# verify that Thali-specific messages are filtered correctly
ok 624 irrelevant messages should be ignored
ok 625 relevant messages should not be ignored
ok 626 messages from this device should be ignored
# teardown
ok 627 should not be in started state
# setup
ok 628 should be in started state
# #startListeningForAdvertisements should fail if start not called
ok 629 specific error should be returned
# teardown
ok 630 should not be in started state
# setup
ok 631 should be in started state
# #startUpdateAdvertisingAndListening should fail if start not called
ok 632 specific error should be returned
# teardown
ok 633 should not be in started state
# setup
ok 634 should be in started state
# #start should fail if called twice in a row
ok 635 specific error should be received
# teardown
ok 636 should not be in started state
# setup
ok 637 should be in started state
# should not be started after stop is called
ok 638 should not be started
ok 639 should not be listening
ok 640 should not target listening
ok 641 should not be advertising
ok 642 should not target advertising
# teardown
ok 643 should not be in started state
# setup
ok 644 should be in started state
# #startUpdateAdvertisingAndListening should fail invalid router has been passed
ERROR thaliWifiInfrastructure: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
ok 645 specific error should be received
# teardown
ok 646 should not be in started state
# setup
ok 647 should be in started state
# #startUpdateAdvertisingAndListening should fail if router server starting fails
ERROR thaliWifiInfrastructure: Router server emitted an error: Error: listen EADDRINUSE
ok 648 specific error expected
# teardown
ok 649 should not be in started state
# setup
ok 650 should be in started state
# #startUpdateAdvertisingAndListening should start hosting given router object
ok 651 server should respond with code 200
# teardown
ok 652 should not be in started state
# setup
ok 653 should be in started state
# #startUpdateAdvertisingAndListening bad psk should be rejected object
ok 654 Connection should be rejected
# teardown
ok 655 should not be in started state
# setup
ok 656 should be in started state
# #stop can be called multiple times in a row
ok 657 should be in stopped state
ok 658 should still be in stopped state
# teardown
ok 659 should not be in started state
# setup
ok 660 should be in started state
# #startListeningForAdvertisements can be called multiple times in a row
ok 661 should be in listening state
ok 662 should still be in listening state
# teardown
ok 663 should not be in started state
# setup
ok 664 should be in started state
# #stopListeningForAdvertisements can be called multiple times in a row
ok 665 should not be in listening state
ok 666 should still not be in listening state
# teardown
ok 667 should not be in started state
# setup
ok 668 should be in started state
# #stopAdvertisingAndListening can be called multiple times in a row
ok 669 should not be in advertising state
ok 670 should still not be in advertising state
# teardown
ok 671 should not be in started state
# setup
ok 672 should be in started state
# functions are run from a queue in the right order
ok 673 call order must match
# teardown
ok 674 should not be in started state
# setup
ok 675 should be in started state
# does not get peer changes from self
ok 676 USN must have changed again
# teardown
ok 677 should not be in started state
# setup
ok 678 should be in started state
# network changes are ignored while stopping
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 679 should not be called
# teardown
ok 680 should not be in started state
# setup
ok 681 should be in started state
# #startListeningForAdvertisements returns error if wifi is off and fires event when on
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 682 wifi should be off
ok 683 specific error expected
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 684 discoveryActive should be true
# teardown
ok 685 should not be in started state
# setup
ok 686 should be in started state
# #startUpdateAdvertisingAndListening returns error if wifi is off and fires event when on
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 687 wifi should be off
ok 688 specific error expected
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 689 advertisingActive should be true
# teardown
ok 690 should not be in started state
# setup
ok 691 should be in started state
# when wifi is enabled discovery is activated and peers become available
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 692 wifi should be off
ok 693 specific error expected
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 694 peer identifier should match
ok 695 host address should match
ok 696 port should match
# teardown
ok 697 should not be in started state
# setup
# #ThaliPeerPoolDefault - single action
ok 698 is an agent
ok 699 enqueue is fine
ok 700 Everything should be off the queue
# teardown
# setup
# #ThaliPeerPoolDefault - multiple actions
ok 701 is an agent
ok 702 first enqueue is fine
ok 703 is an agent
ok 704 second enqueue is fine
ok 705 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 706 Queue is empty
# teardown
# setup
# #ThaliPeerPoolDefault - PSK Pool works
ok 707 is an agent
ok 708 good enqueue
ok 709 Identity should match
ok 710 Got expected response
ok 711 Got psk call back
# teardown
# setup
# #ThaliPeerPoolDefault - stop
ok 712 is an agent
ok 713 enqueue worked
ok 714 is an agent
ok 715 enqueue 2 worked
ok 716 start action is killed
ok 717 killed action is still killed
ok 718 inQueue is empty
ok 719 Make sure we won enqueue after stopping
# teardown

1..719
# tests 719
# pass  719

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
Adding Thali Cordova plugin from: /var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/T/tmp-4542ApHCf15UQvWO/TestApp/thaliDontCheckIn/Thali_CordovaPlugin-npmv2.1.0
Running jx npm install in: /var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/T/tmp-4542ApHCf15UQvWO/TestApp/plugins/org.thaliproject.p2p/scripts
scripts@0.0.1 /private/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/T/tmp-4542ApHCf15UQvWO/TestApp/plugins/org.thaliproject.p2p/scripts
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
npm http 304 http://192.168.1.100:4873/fs-extra
npm http 304 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/jsonfile
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http request GET http://192.168.1.100:4873/rimraf
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http 304 http://192.168.1.100:4873/rimraf
npm http 304 http://192.168.1.100:4873/jsonfile
npm http 304 http://192.168.1.100:4873/path-is-absolute
npm http request GET http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/fs.realpath
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/inflight
npm http 304 http://192.168.1.100:4873/fs.realpath
npm http 200 http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/wrappy
npm http 200 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 304 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/concat-map
npm http 200 http://192.168.1.100:4873/balanced-match
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
/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/T/tmp-4542ApHCf15UQvWO
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

2016-08-10T11:35:18.460Z - info: Require 3 ios devices

2016-08-10T11:35:18.462Z - info: Require 0 android devices
2016-08-10T11:35:18.467Z - info: listening on *:3000

[33mUnit Test app is loaded
[39m
[33mDEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mUnit Test app is loaded
[39m
[33mDEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
[39m
[33mDEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
[39m
[33mMy device name is: cb67c198-1978-45d5-827b-29e31b888e82
[39m
[33mWARN testUtils: myNameCallback not set!
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
[36mMy device name is: 0de6f033-0d5b-4a38-858a-5e7427564d61
WARN testUtils: myNameCallback not set!
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
[32mMy device name is: fd8b9080-5d5a-4d97-b1ba-c26493b882a7
[39m
[32mWARN testUtils: myNameCallback not set!
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreateNativeListener.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreateNativeListener.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreateNativeListener.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPromiseQueue.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testTests.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPromiseQueue.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testTests.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
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
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNative.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotification.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationAction.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotification.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationAction.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationBeacons.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationBeacons.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNative.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationClient.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationLocal.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotification.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationAction.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationServer.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationBeacons.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerAction.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerDictionary.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationClient.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationLocal.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationServer.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationUtilities.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerAction.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerDictionary.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliTcpServersManager.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationClient.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationLocal.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationServer.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerAction.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerDictionary.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationUtilities.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliTcpServersManager.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationUtilities.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
[39m
[33mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliTcpServersManager.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
[39m
[32mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
[39m
[36mTest runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
[39m
[33mConnected to the test server
[39m
[32mConnected to the test server
[39m
2016-08-10T11:35:21.589Z - debug: Device presented: fd8b9080-5d5a-4d97-b1ba-c26493b882a7 (45f9b620-5bad-4195-ac98-b70d4191ade4) - ios dummy

2016-08-10T11:35:21.590Z - debug: Device presented: cb67c198-1978-45d5-827b-29e31b888e82 (722a609a-612a-48ca-a7f1-c6cb3eb2e72b) - ios dummy

[36mConnected to the test server
[39m
2016-08-10T11:35:21.603Z - debug: Device presented: 0de6f033-0d5b-4a38-858a-5e7427564d61 (d67237d8-5320-4839-92c4-2f8e207b296c) - ios dummy

2016-08-10T11:35:21.603Z - info: All 3 ios devices are present

2016-08-10T11:35:21.604Z - info: Starting unit test run on 3 ios devices

[36mTAP version 13
[39m
[36m# setup
[39m
[33mTAP version 13
# setup
[39m
[32mTAP version 13
[39m
[32m# setup
[39m
2016-08-10T11:35:21.726Z - info: Running on ios test: 1. calling createNativeListener directly rejects

[36m# 1. calling createNativeListener directly rejects
[39m
[33m# 1. calling createNativeListener directly rejects
[39m
[32m# 1. calling createNativeListener directly rejects
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: listening 50339
[39m
[36mDEBUG createNativeListener: listening 50340
[39m
[33mok 1 Should throw
[39m
[33m# teardown
[39m
[36mok 1 Should throw
# teardown
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: listening 50341
[39m
[32mok 1 Should throw
[39m
[32m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T11:35:21.774Z - info: Running on ios test: 2. emits incomingConnectionState

[36m# 2. emits incomingConnectionState
[39m
[33m# 2. emits incomingConnectionState
[39m
[32m# 2. emits incomingConnectionState
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: listening 50345
[39m
[36mDEBUG createNativeListener: listening 50347
[39m
[33mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[33mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[33mDEBUG createNativeListener: new mux
[39m
[33mok 2 initial connection state should be CONNECTED
[39m
[36mok 2 initial connection state should be CONNECTED
[39m
[32mDEBUG createNativeListener: listening 50349
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[33mok 3 final connection state should be DISCONNECTED
[39m
[33m# teardown
[39m
[36mok 3 final connection state should be DISCONNECTED
[39m
[36m# teardown
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[32mok 2 initial connection state should be CONNECTED
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[32mok 3 final connection state should be DISCONNECTED
[39m
[32m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T11:35:21.830Z - info: Running on ios test: 3. emits routerPortConnectionFailed

[36m# 3. emits routerPortConnectionFailed
[39m
[33m# 3. emits routerPortConnectionFailed
[39m
[32m# 3. emits routerPortConnectionFailed
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: listening 50354
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: listening 50356
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[33mDEBUG createNativeListener: new incoming socket
[39m
[33mDEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: 
ok 4 tried to connect to right port
ok 5 failed due to refused connection
ok 6 routerPortConnectionFailed is emitted
# teardown
DEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: 
ok 4 tried to connect to right port
ok 5 failed due to refused connection
ok 6 routerPortConnectionFailed is emitted
# teardown
DEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: listening 50360
[39m
[32mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: 
[39m
[32mok 4 tried to connect to right port
ok 5 failed due to refused connection
[39m
[32mok 6 routerPortConnectionFailed is emitted
[39m
[32m# teardown
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
[39m
[33mDEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createNativeListener: mux close
[39m
[32m# setup
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
2016-08-10T11:35:21.899Z - info: Running on ios test: 4. native server connections all up

[33m# 4. native server connections all up
[39m
[36m# 4. native server connections all up
[39m
[32m# 4. native server connections all up
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50366
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50367
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[33mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
[39m
[33mDEBUG createNativeListener: new mux
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[33mok 7 Send/recvd #1 should be equal length
ok 8 Send/recvd #1 should be same
ok 9 Send/recvd #2 should be equal length
ok 10 Send/recvd #2 should be same
ok 11 Should be exactly 2 client sockets
[39m
[36mok 7 Send/recvd #1 should be equal length
ok 8 Send/recvd #1 should be same
ok 9 Send/recvd #2 should be equal length
ok 10 Send/recvd #2 should be same
ok 11 Should be exactly 2 client sockets
[39m
[33m# teardown
[39m
[36m# teardown
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: listening 50374
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
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
[39m
[32mok 9 Send/recvd #2 should be equal length
[39m
[32mok 10 Send/recvd #2 should be same
[39m
[32mok 11 Should be exactly 2 client sockets
[39m
[32m# teardown
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
[39m
[33m# setup
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[36m# setup
[39m
[36mDEBUG createNativeListener: incoming socket close
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
2016-08-10T11:35:21.978Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

[36m# 5. native server - closing incoming stream cleans outgoing socket
[39m
[33m# 5. native server - closing incoming stream cleans outgoing socket
[39m
[32m# 5. native server - closing incoming stream cleans outgoing socket
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: listening 50381
[39m
[32mDEBUG createNativeListener: listening 50382
[39m
[36mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new mux
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[36mok 12 socket shouldn't close until after stream
ok 13 incoming remains open
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[36m# teardown
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[32mok 12 socket shouldn't close until after stream
[39m
[32mok 13 incoming remains open
[39m
[32m# teardown
[39m
[33mDEBUG createNativeListener: listening 50387
[39m
[33mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
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
ok 13 incoming remains open
[39m
[33m# teardown
[39m
[36mDEBUG createNativeListener: mux close
[39m
[36m# setup
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[33mDEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createNativeListener: mux close
[39m
[32m# setup
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
2016-08-10T11:35:22.031Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

[36m# 6. native server - closing incoming connection cleans outgoing socket
[39m
[32m# 6. native server - closing incoming connection cleans outgoing socket
[39m
[33m# 6. native server - closing incoming connection cleans outgoing socket
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50393
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: listening 50395
[39m
[36mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[32mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[36mok 14 we should not have gotten an error
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[32mok 14 we should not have gotten an error
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[36mok 15 socket shouldn't close until after incoming
ok 16 incoming is cleaned up
[39m
[36m# teardown
[39m
[32mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: incoming socket close
[39m
[32mok 15 socket shouldn't close until after incoming
[39m
[32mok 16 incoming is cleaned up
[39m
[32m# teardown
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50399
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
DEBUG createNativeListener: incoming socket close
[39m
[33mok 15 socket shouldn't close until after incoming
ok 16 incoming is cleaned up
[39m
[33m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T11:35:22.081Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

[36m# 7. native server - closing outgoing socket cleans associated mux stream
[39m
[32m# 7. native server - closing outgoing socket cleans associated mux stream
[39m
[33m# 7. native server - closing outgoing socket cleans associated mux stream
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: listening 50405
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[32mDEBUG createNativeListener: listening 50407
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[36mok 17 stream was closed
[39m
[36mok 18 incoming should survive
[39m
[36mok 19 mux should have no streams
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[36m# teardown
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50411
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[32mok 17 stream was closed
ok 18 incoming should survive
[39m
[32mok 19 mux should have no streams
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[32m# teardown
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mok 17 stream was closed
ok 18 incoming should survive
ok 19 mux should have no streams
[39m
[33m# teardown
[39m
[36mDEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
[39m
[33mDEBUG createNativeListener: mux close
[39m
[33m# setup
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
2016-08-10T11:35:22.132Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

[36m# 8. native server - closing the whole server cleans everything up
[39m
[32m# 8. native server - closing the whole server cleans everything up
[39m
[33m# 8. native server - closing the whole server cleans everything up
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: listening 50417
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50419
[39m
[32mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[36mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
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
[36mok 22 native server is nulled out
ok 23 native server should be closed
ok 24 incoming has been removed
ok 25 Incoming should be done
ok 26 The mux object should be closed
ok 27 The mux stream should be closed
DEBUG createNativeListener: incoming socket close
[39m
[32mok 20 we should not have gotten an error
[39m
[36m# teardown
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mok 21 Buffers are identical
[39m
[32mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
ok 22 native server is nulled out
ok 23 native server should be closed
ok 24 incoming has been removed
ok 25 Incoming should be done
ok 26 The mux object should be closed
ok 27 The mux stream should be closed
DEBUG createNativeListener: incoming socket close
# teardown
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50423
[39m
[33mDEBUG createNativeListener: new incoming socket
[39m
[33mDEBUG createNativeListener: creating incoming mux
[39m
[33mDEBUG createNativeListener: new mux
[39m
[33mok 20 we should not have gotten an error
[39m
[33mDEBUG createNativeListener: new stream: 
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
[39m
[33mok 26 The mux object should be closed
ok 27 The mux stream should be closed
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[33m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T11:35:22.192Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

[36m# 9. native server - we can get a ton of connections and data through and still clean up the server completely
[39m
[32m# 9. native server - we can get a ton of connections and data through and still clean up the server completely
[39m
[33m# 9. native server - we can get a ton of connections and data through and still clean up the server completely
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: listening 50430
[39m
[36mDEBUG createNativeListener: listening 50429
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50451
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[36mDEBUG createNativeListener: creating incoming mux
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
[36mDEBUG createNativeListener: new mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[32mDEBUG createNativeListener: new incoming socket
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
[32mDEBUG createNativeListener: creating incoming mux
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
DEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[36mDEBUG createNativeListener: new mux
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
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
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
[33mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
[39m
[33mDEBUG createNativeListener: new mux
[39m
[33mDEBUG createNativeListener: new incoming socket
[39m
[33mDEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[33mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
[39m
[33mDEBUG createNativeListener: new mux
[39m
[33mDEBUG createNativeListener: new incoming socket
[39m
[33mDEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
[39m
[33mDEBUG createNativeListener: new mux
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
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
DEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
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
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new stream: 
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
[32mDEBUG createNativeListener: new outgoing socket
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
[32mDEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
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
[33mDEBUG createNativeListener: new stream: 
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
[32mDEBUG createNativeListener: new outgoing socket
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
[33mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: stream close:
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
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: stream close:
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
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
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
[32mDEBUG createNativeListener: new stream: 
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
[32mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: new stream: 
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
[32mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: mux close
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[36mok 28 native server is nulled out
[39m
[36mok 29 native server should be closed
[39m
[36mok 30 incoming has been removed
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createNativeListener: incoming socket close
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
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[36m# teardown
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
[39m
[33mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
[39m
[33mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
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
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: stream close:
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
[33mDEBUG createNativeListener: mux close
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: stream close:
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
[39m
[32mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: mux close
[39m
[33mDEBUG createNativeListener: mux close
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
ok 28 native server is nulled out
ok 29 native server should be closed
ok 30 incoming has been removed
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: mux close
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[32mok 28 native server is nulled out
[39m
[32mok 29 native server should be closed
ok 30 incoming has been removed
[39m
[32mDEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
[39m
[33mDEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
[39m
[33mDEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
[39m
[32m# teardown
[39m
[33m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T11:35:22.530Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

[32m# 10. native server - simulate mux failure, make sure everything is cleaned up
[39m
[36m# 10. native server - simulate mux failure, make sure everything is cleaned up
[39m
[33m# 10. native server - simulate mux failure, make sure everything is cleaned up
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50585
[39m
[33mDEBUG createNativeListener: listening 50586
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[32mok 31 we should not have gotten an error
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
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[32mok 32 Buffers are identical
[39m
[33mok 32 Buffers are identical
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: mux close
[39m
[33mDEBUG createNativeListener: mux close
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[32mok 33 server should be fine
[39m
[32mok 34 server should be open
ok 35 incoming has been removed
[39m
[32mok 36 The mux object should be closed
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[32mok 37 The mux stream should be closed
[39m
[33mok 33 server should be fine
ok 34 server should be open
[39m
[33mok 35 incoming has been removed
ok 36 The mux object should be closed
[39m
[33mok 37 The mux stream should be closed
[39m
[32m# teardown
[39m
[33m# teardown
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: listening 50591
[39m
[36mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
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
[39m
[36mDEBUG createNativeListener: stream close:
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
2016-08-10T11:35:22.582Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

[33m# 11. native server - timing out the incoming connection cleans everything up
[39m
[32m# 11. native server - timing out the incoming connection cleans everything up
[39m
[36m# 11. native server - timing out the incoming connection cleans everything up
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: listening 50597
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[33mDEBUG createNativeListener: listening 50599
[39m
[32mDEBUG createNativeListener: listening 50600
[39m
[33mDEBUG createNativeListener: new incoming socket
[39m
[33mDEBUG createNativeListener: creating incoming mux
[39m
[33mDEBUG createNativeListener: new mux
[39m
[33mok 38 we should not have gotten an error
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new mux
[39m
[32mok 38 we should not have gotten an error
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[32mok 39 Buffers are identical
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[33mok 39 Buffers are identical
[39m
[36mDEBUG createNativeListener: new mux
[39m
[36mok 38 we should not have gotten an error
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: incoming socket timeout
[39m
[33mDEBUG createNativeListener: incoming socket timeout
DEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: mux close
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[33mok 40 server should be fine
ok 41 server should be open
ok 42 incoming has been removed
ok 43 The mux object should be closed
ok 44 The mux stream should be closed
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[33m# teardown
[39m
[36mok 39 Buffers are identical
[39m
[32mDEBUG createNativeListener: mux close
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createNativeListener: incoming socket timeout
[39m
[32mok 40 server should be fine
ok 41 server should be open
ok 42 incoming has been removed
ok 43 The mux object should be closed
ok 44 The mux stream should be closed
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[32m# teardown
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
ok 44 The mux stream should be closed
[39m
[36m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T11:35:22.632Z - info: Running on ios test: 12. #_doImmediateSeqUpdate - server is not there

[33m# 12. #_doImmediateSeqUpdate - server is not there
[39m
[36m# 12. #_doImmediateSeqUpdate - server is not there
[39m
[32m# 12. #_doImmediateSeqUpdate - server is not there
[39m
[36mDEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}
ok 45 Got right error
[39m
[36m# teardown
[39m
[32mDEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}
ok 45 Got right error
# teardown
[39m
[33mDEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}
ok 45 Got right error
# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T11:35:22.700Z - info: Running on ios test: 13. #_doImmediateSeqUpdate - server accepts & closes connection

[36m# 13. #_doImmediateSeqUpdate - server accepts & closes connection
[39m
[33m# 13. #_doImmediateSeqUpdate - server accepts & closes connection
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
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T11:35:22.772Z - info: Running on ios test: 14. #_doImmediateSeqUpdate - server always returns 500

[36m# 14. #_doImmediateSeqUpdate - server always returns 500
[39m
[33m# 14. #_doImmediateSeqUpdate - server always returns 500
[39m
[32m# 14. #_doImmediateSeqUpdate - server always returns 500
[39m
[36mDEBUG localSeqManager: Got an error trying to update seq []
ok 47 Got 500 as expected
# teardown
[39m
[32mDEBUG localSeqManager: Got an error trying to update seq []
ok 47 Got 500 as expected
[39m
[32m# teardown
[39m
[33mDEBUG localSeqManager: Got an error trying to update seq []
ok 47 Got 500 as expected
[39m
[33m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T11:35:22.828Z - info: Running on ios test: 15. #_doImmediateSeqUpdate - create new seq doc

[32m# 15. #_doImmediateSeqUpdate - create new seq doc
[39m
[36m# 15. #_doImmediateSeqUpdate - create new seq doc
[39m
[33m# 15. #_doImmediateSeqUpdate - create new seq doc
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
[36mok 48 should be equal
[39m
[36mok 49 revs are equal
[39m
[36m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T11:35:23.261Z - info: Running on ios test: 16. #_doImmediateSeqUpdate - doc exists, need to get rev and update

[36m# 16. #_doImmediateSeqUpdate - doc exists, need to get rev and update
[39m
[32m# 16. #_doImmediateSeqUpdate - doc exists, need to get rev and update
[39m
[33m# 16. #_doImmediateSeqUpdate - doc exists, need to get rev and update
[39m
[36mok 50 should be equal
ok 51 revs are equal
[39m
[36m# teardown
[39m
[32mok 50 should be equal
[39m
[32mok 51 revs are equal
[39m
[32m# teardown
[39m
[33mok 50 should be equal
[39m
[33mok 51 revs are equal
[39m
[33m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T11:35:23.415Z - info: Running on ios test: 17. #_doImmediateSeqUpdate - update seq three times

[36m# 17. #_doImmediateSeqUpdate - update seq three times
[39m
[32m# 17. #_doImmediateSeqUpdate - update seq three times
[39m
[33m# 17. #_doImmediateSeqUpdate - update seq three times
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
[36mok 56 should be equal
[39m
[36mok 57 revs are equal
[39m
[36m# teardown
[39m
[32mok 54 should be equal
[39m
[32mok 55 revs are equal
[39m
[33mok 52 should be equal
[39m
[33mok 53 revs are equal
[39m
[32mok 56 should be equal
[39m
[32mok 57 revs are equal
[39m
[32m# teardown
[39m
[33mok 54 should be equal
[39m
[33mok 55 revs are equal
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
2016-08-10T11:35:23.582Z - info: Running on ios test: 18. #_doImmediateSeqUpdate - rev got changed under us

[32m# 18. #_doImmediateSeqUpdate - rev got changed under us
[39m
[36m# 18. #_doImmediateSeqUpdate - rev got changed under us
[39m
[33m# 18. #_doImmediateSeqUpdate - rev got changed under us
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
[33mDEBUG localSeqManager: Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}
[39m
[33mok 58 Our rev is old so we should fail
[39m
[33m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T11:35:23.728Z - info: Running on ios test: 19. #_doImmediateSeqUpdate - fail if stop is called

[36m# 19. #_doImmediateSeqUpdate - fail if stop is called
[39m
[32m# 19. #_doImmediateSeqUpdate - fail if stop is called
[39m
[33m# 19. #_doImmediateSeqUpdate - fail if stop is called
[39m
[36mok 59 confirm stop caused failure
# teardown
[39m
[33mok 59 confirm stop caused failure
[39m
[33m# teardown
[39m
[32mok 59 confirm stop caused failure
# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T11:35:23.767Z - info: Running on ios test: 20. #_doImmediateSeqUpdate - stop after get but before put fails right

[36m# 20. #_doImmediateSeqUpdate - stop after get but before put fails right
[39m
[32m# 20. #_doImmediateSeqUpdate - stop after get but before put fails right
[39m
[33m# 20. #_doImmediateSeqUpdate - stop after get but before put fails right
[39m
[36mDEBUG localSeqManager: Got an error trying to update seq {"onPut":true}
ok 60 stop caused us to fail
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
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T11:35:23.866Z - info: Running on ios test: 21. #update - fail if stop is called

[36m# 21. #update - fail if stop is called
[39m
[33m# 21. #update - fail if stop is called
[39m
[32m# 21. #update - fail if stop is called
[39m
[33mok 62 failed due to stop
[39m
[33mok 63 failed due to stop
[39m
[33m# teardown
[39m
[36mok 62 failed due to stop
[39m
[36mok 63 failed due to stop
[39m
[36m# teardown
[39m
[32mok 62 failed due to stop
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
2016-08-10T11:35:23.911Z - info: Running on ios test: 22. #update - set seq for first time

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
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T11:35:24.042Z - info: Running on ios test: 23. #update - Fail on bad seq value

[36m# 23. #update - Fail on bad seq value
[39m
[33m# 23. #update - Fail on bad seq value
[39m
[32m# 23. #update - Fail on bad seq value
[39m
[36mDEBUG localSeqManager: Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10
[39m
[36mok 65 Expected bad seq error
[39m
[36m# teardown
[39m
[32mDEBUG localSeqManager: Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10
ok 65 Expected bad seq error
# teardown
[39m
[33mDEBUG localSeqManager: Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10
[39m
[33mok 65 Expected bad seq error
[39m
[33m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T11:35:24.135Z - info: Running on ios test: 24. #update - do we cancel timer properly on an immediate?

[33m# 24. #update - do we cancel timer properly on an immediate?
[39m
[36m# 24. #update - do we cancel timer properly on an immediate?
[39m
[32m# 24. #update - do we cancel timer properly on an immediate?
[39m
[36mok 66 Different promises
ok 67 Timer was cancelled
[39m
[36mok 68 should be equal
[39m
[36m# teardown
[39m
[32mok 66 Different promises
ok 67 Timer was cancelled
[39m
[33mok 66 Different promises
ok 67 Timer was cancelled
[39m
[32mok 68 should be equal
[39m
[32m# teardown
[39m
[33mok 68 should be equal
[39m
[33m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T11:35:24.256Z - info: Running on ios test: 25. #update - do we wait for blocked update

[36m# 25. #update - do we wait for blocked update
[39m
[33m# 25. #update - do we wait for blocked update
[39m
[32m# 25. #update - do we wait for blocked update
[39m
[36mok 69 One go and one blocked
[39m
[36mok 70 All blocked
ok 71 Still blocked
[39m
[33mok 69 One go and one blocked
[39m
[33mok 70 All blocked
[39m
[33mok 71 Still blocked
[39m
[32mok 69 One go and one blocked
[39m
[32mok 70 All blocked
[39m
[32mok 71 Still blocked
[39m
[36mok 72 should be equal
[39m
[36m# teardown
[39m
[33mok 72 should be equal
[39m
[33m# teardown
[39m
[32mok 72 should be equal
[39m
[32m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T11:35:24.367Z - info: Running on ios test: 26. #update - test that we wait long enough

[36m# 26. #update - test that we wait long enough
[39m
[33m# 26. #update - test that we wait long enough
[39m
[32m# 26. #update - test that we wait long enough
[39m
[36mok 73 We waited long enough
[39m
[33mok 73 We waited long enough
[39m
[36mok 74 should be equal
# teardown
[39m
[33mok 74 should be equal
[39m
[33m# teardown
[39m
[32mok 73 We waited long enough
[39m
[32mok 74 should be equal
[39m
[32m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T11:35:25.473Z - info: Running on ios test: 27. #update - test that we pick up new sequences while we wait

[36m# 27. #update - test that we pick up new sequences while we wait
[39m
[32m# 27. #update - test that we pick up new sequences while we wait
[39m
[33m# 27. #update - test that we pick up new sequences while we wait
[39m
[36mok 75 Should have gotten same timer promise
ok 76 Still same timer promise
[39m
[33mok 75 Should have gotten same timer promise
ok 76 Still same timer promise
[39m
[32mok 75 Should have gotten same timer promise
ok 76 Still same timer promise
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
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T11:35:26.539Z - info: Running on ios test: 28. Coordinated seq test

[32m# 28. Coordinated seq test
[39m
[33m# 28. Coordinated seq test
[39m
[36m# 28. Coordinated seq test
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50814
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50818
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50820
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: first connection
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: first connection
DEBUG createPeerListener: first connection
[39m
[32mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[33mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
[39m
[33mDEBUG createNativeListener: new mux
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG wifiBasedNativeMock: proxy socket connected
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[32mDEBUG createPeerListener: first connection
[39m
[33mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG createPeerListener: forward connection
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
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createNativeListener: 
DEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: 
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: 
DEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: 
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: 
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: 
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mok 79 should be equal
[39m
[36mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[36mok 79 should be equal
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createPeerListener: error on incoming stream - Error: Channel destroyed
[39m
[36mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createPeerListener: error on incoming stream - Error: Channel destroyed
[39m
[33mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[32mok 79 should be equal
[39m
[36mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[33mok 80 should be equal
[39m
[33m# teardown
[39m
[32mok 80 should be equal
[39m
[32m# teardown
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[36mok 80 should be equal
[39m
[36m# teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[33mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: mux close
[39m
[33mDEBUG createNativeListener: mux close
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[33mDEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNRESET","status":500}
[39m
[33mDEBUG testUtils: Got an err - Error: socket hang up -1
[39m
[36mDEBUG createPeerListener: Recreating listener
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33m# setup
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNRESET","status":500}
[39m
[36mDEBUG testUtils: Got an err - Error: socket hang up -1
[39m
[36mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createPeerListener: Recreating listener
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG wifiBasedNativeMock: error on socket - Error: This socket is closed.
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[32mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[36mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[36mDEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: stream close:
WARN createPeerListener: 
DEBUG createPeerListener: failedConnection
[39m
[36mDEBUG createPeerListener: failed incoming connection because of mux promise failure - Error: Connection could not be established
[39m
[36m# setup
[39m
[32mDEBUG createPeerListener: Recreating listener
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[32mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[32mDEBUG createNativeListener: mux close
[39m
[32mWARN createPeerListener: 
[39m
[32mDEBUG createPeerListener: failedConnection
[39m
[32mDEBUG createPeerListener: failed incoming connection because of mux promise failure - Error: Connection could not be established
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
2016-08-10T11:35:27.868Z - info: Running on ios test: 29. closeAll can close even when connections open

[32mDEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}
[39m
[36m# 29. closeAll can close even when connections open
[39m
[33m# 29. closeAll can close even when connections open
[39m
[32mDEBUG testUtils: Got an err - Error: connect ECONNREFUSED
[39m
[32m# setup
[39m
[32m# 29. closeAll can close even when connections open
[39m
[33mok 81 not possible to connect to the server anymore
# teardown
[39m
[36mok 81 not possible to connect to the server anymore
# teardown
[39m
[32mok 81 not possible to connect to the server anymore
[39m
[32m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T11:35:27.998Z - info: Running on ios test: 30. closeAll with promise

[36m# 30. closeAll with promise
[39m
[33m# 30. closeAll with promise
[39m
[32m# 30. closeAll with promise
[39m
[33mok 82 not possible to connect to the server anymore
[39m
[33m# teardown
[39m
[32mok 82 not possible to connect to the server anymore
[39m
[32m# teardown
[39m
[36mok 82 not possible to connect to the server anymore
[39m
[36m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T11:35:28.126Z - info: Running on ios test: 31. closeAll properly throws when closing a non open server with eatNotRunning set to false

[36m# 31. closeAll properly throws when closing a non open server with eatNotRunning set to false
[39m
[32m# 31. closeAll properly throws when closing a non open server with eatNotRunning set to false
[39m
[33m# 31. closeAll properly throws when closing a non open server with eatNotRunning set to false
[39m
[36mok 83 Got the right error
# teardown
[39m
[32mok 83 Got the right error
# teardown
[39m
[33mok 83 Got the right error
# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-10T11:35:28.251Z - info: Running on ios test: 32. closeAll works even with a server that is not listening yet witheatNotRunning set to true

[36m# 32. closeAll works even with a server that is not listening yet witheatNotRunning set to true
[39m
[32m# 32. closeAll works even with a server that is not listening yet witheatNotRunning set to true
[39m
[33m# 32. closeAll works even with a server that is not listening yet witheatNotRunning set to true
[39m
[33m# teardown
[39m
[32m# teardown
[39m
[36m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-10T11:35:28.373Z - info: Running on ios test: 33. enqueue and run in order

[36m# 33. enqueue and run in order
[39m
[32m# 33. enqueue and run in order
[39m
[33m# 33. enqueue and run in order
[39m
[32mok 84 firstPromise setTimeout
[39m
[32mok 85 firstPromise result
ok 86 firstPromise testValue
[39m
[36mok 84 firstPromise setTimeout
[39m
[36mok 85 firstPromise result
[39m
[36mok 86 firstPromise testValue
[39m
[33mok 84 firstPromise setTimeout
[39m
[33mok 85 firstPromise result
[39m
[33mok 86 firstPromise testValue
[39m
[36mok 87 secondPromise setTimeout
[39m
[36mok 88 secondPromise result
ok 89 secondPromise testValue
[39m
[36mok 90 thirdPromise in promise
[39m
[36mok 91 thirdPromise result
[39m
[36mok 92 thirdPromise testValue
[39m
[36m# teardown
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
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T11:35:28.598Z - info: Running on ios test: 34. enqueueAtTop and run backwards

[32m# 34. enqueueAtTop and run backwards
[39m
[36m# 34. enqueueAtTop and run backwards
[39m
[33m# 34. enqueueAtTop and run backwards
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
[32mok 93 thirdPromise - first to run
ok 94 thirdPromise - in resolve
ok 95 secondPromise - second to run
ok 96 secondPromise - in catch
ok 97 firstPromise - third to run
ok 98 firstPromise - in then
ok 99 testing promises
# teardown
[39m
[33mok 93 thirdPromise - first to run
[39m
[33mok 94 thirdPromise - in resolve
[39m
[33mok 95 secondPromise - second to run
[39m
[33mok 96 secondPromise - in catch
ok 97 firstPromise - third to run
ok 98 firstPromise - in then
ok 99 testing promises
# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T11:35:28.619Z - info: Running on ios test: 35. mix enqueue and enqueueAtTop

[36m# 35. mix enqueue and enqueueAtTop
[39m
[32m# 35. mix enqueue and enqueueAtTop
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
[39m
[33mok 101 fourth
[39m
[33mok 102 second
[39m
[33mok 103 secondPromise - in then
[39m
[36mok 104 first
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
[33mok 104 first
ok 105 firstPromise - in catch
ok 106 third
[39m
[33mok 107 thirdPromise - in then
ok 108 testingPromises
[39m
[33m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T11:35:28.741Z - info: Running on ios test: 36. queues handled independently

[36m# 36. queues handled independently
[39m
[32m# 36. queues handled independently
[39m
[33m# 36. queues handled independently
[39m
[36mok 109 all short operations completed before the long resolves
[39m
[36m# teardown
[39m
[33mok 109 all short operations completed before the long resolves
[39m
[33m# teardown
[39m
[32mok 109 all short operations completed before the long resolves
[39m
[32m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-10T11:35:28.794Z - info: Running on ios test: 37. basic

[36m# 37. basic
[39m
[32m# 37. basic
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
2016-08-10T11:35:28.816Z - info: Running on ios test: 38. another

[32m# 38. another
[39m
[36m# 38. another
[39m
[33m# 38. another
[39m
[32mok 111 sane
# teardown
[39m
[33mok 111 sane
# teardown
[39m
[36mok 111 sane
[39m
[36m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T11:35:28.836Z - info: Running on ios test: 39. can pass data in setup

[33m# 39. can pass data in setup
[39m
[32m# 39. can pass data in setup
[39m
[36m# 39. can pass data in setup
[39m
[36m[{"uuid":"45f9b620-5bad-4195-ac98-b70d4191ade4","data":"custom data"},{"uuid":"d67237d8-5320-4839-92c4-2f8e207b296c","data":"custom data"},{"uuid":"722a609a-612a-48ca-a7f1-c6cb3eb2e72b","data":"custom data"}]
ok 112 test participant has uuid
ok 113 participant data matches
ok 114 test participant has uuid
ok 115 participant data matches
ok 116 test participant has uuid
ok 117 participant data matches
ok 118 own UUID is found from the participants list
# teardown
[39m
[32m[{"uuid":"45f9b620-5bad-4195-ac98-b70d4191ade4","data":"custom data"},{"uuid":"d67237d8-5320-4839-92c4-2f8e207b296c","data":"custom data"},{"uuid":"722a609a-612a-48ca-a7f1-c6cb3eb2e72b","data":"custom data"}]
ok 112 test participant has uuid
ok 113 participant data matches
ok 114 test participant has uuid
ok 115 participant data matches
ok 116 test participant has uuid
ok 117 participant data matches
ok 118 own UUID is found from the participants list
# teardown
[39m
[33m[{"uuid":"45f9b620-5bad-4195-ac98-b70d4191ade4","data":"custom data"},{"uuid":"d67237d8-5320-4839-92c4-2f8e207b296c","data":"custom data"},{"uuid":"722a609a-612a-48ca-a7f1-c6cb3eb2e72b","data":"custom data"}]
ok 112 test participant has uuid
ok 113 participant data matches
ok 114 test participant has uuid
ok 115 participant data matches
ok 116 test participant has uuid
ok 117 participant data matches
ok 118 own UUID is found from the participants list
# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T11:35:28.858Z - info: Running on ios test: 40. can continue after disconnect from server

[32m# 40. can continue after disconnect from server
[39m
[36m# 40. can continue after disconnect from server
[39m
[33m# 40. can continue after disconnect from server
[39m
[36mDisconnected from the test server
[39m
[32mDisconnected from the test server
[39m
[33mDisconnected from the test server
[39m
2016-08-10T11:35:28.871Z - info: Socket to device fd8b9080-5d5a-4d97-b1ba-c26493b882a7 disconnected: client namespace disconnect

2016-08-10T11:35:28.878Z - info: Socket to device 0de6f033-0d5b-4a38-858a-5e7427564d61 disconnected: client namespace disconnect

2016-08-10T11:35:28.880Z - info: Socket to device cb67c198-1978-45d5-827b-29e31b888e82 disconnected: client namespace disconnect

[36mConnected to the test server
[39m
[32mConnected to the test server
[39m
[36mok 119 got connect event
[39m
[36m# teardown
[39m
[32mok 119 got connect event
[39m
[32m# teardown
[39m
2016-08-10T11:35:29.391Z - debug: Device presented: 0de6f033-0d5b-4a38-858a-5e7427564d61 (d67237d8-5320-4839-92c4-2f8e207b296c) - ios dummy

2016-08-10T11:35:29.391Z - info: Updating existing device: 0de6f033-0d5b-4a38-858a-5e7427564d61 (d67237d8-5320-4839-92c4-2f8e207b296c)

2016-08-10T11:35:29.392Z - debug: Device presented: fd8b9080-5d5a-4d97-b1ba-c26493b882a7 (45f9b620-5bad-4195-ac98-b70d4191ade4) - ios dummy

2016-08-10T11:35:29.392Z - info: Updating existing device: fd8b9080-5d5a-4d97-b1ba-c26493b882a7 (45f9b620-5bad-4195-ac98-b70d4191ade4)

[33mConnected to the test server
[39m
[33mok 119 got connect event
[39m
[33m# teardown
[39m
2016-08-10T11:35:29.402Z - debug: Device presented: cb67c198-1978-45d5-827b-29e31b888e82 (722a609a-612a-48ca-a7f1-c6cb3eb2e72b) - ios dummy
2016-08-10T11:35:29.402Z - info: Updating existing device: cb67c198-1978-45d5-827b-29e31b888e82 (722a609a-612a-48ca-a7f1-c6cb3eb2e72b)

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T11:35:29.411Z - info: Running on ios test: 41. test after disconnect

[33m# 41. test after disconnect
[39m
[32m# 41. test after disconnect
[39m
[36m# 41. test after disconnect
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
2016-08-10T11:35:29.435Z - info: Running on ios test: 42. #startListeningForAdvertisements should fail if start not called

[36m# 42. #startListeningForAdvertisements should fail if start not called
[39m
[33m# 42. #startListeningForAdvertisements should fail if start not called
[39m
[32m# 42. #startListeningForAdvertisements should fail if start not called
[39m
[32mok 121 specific error should be returned
[39m
[32m# teardown
[39m
[36mok 121 specific error should be returned
[39m
[36m# teardown
[39m
[33mok 121 specific error should be returned
[39m
[33m# teardown
[39m
[32mok 122 error should be null
[39m
[36mok 122 error should be null
[39m
[32mok 123 error should be null
[39m
[32m# setup
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
2016-08-10T11:35:29.467Z - info: Running on ios test: 43. #startUpdateAdvertisingAndListening should fail if start not called

[36m# 43. #startUpdateAdvertisingAndListening should fail if start not called
[39m
[32m# 43. #startUpdateAdvertisingAndListening should fail if start not called
[39m
[33m# 43. #startUpdateAdvertisingAndListening should fail if start not called
[39m
[32mok 124 specific error should be returned
[39m
[36mok 124 specific error should be returned
[39m
[32m# teardown
[39m
[36m# teardown
[39m
[33mok 124 specific error should be returned
[39m
[33m# teardown
[39m
[36mok 125 error should be null
[39m
[36mok 126 error should be null
[39m
[36m# setup
[39m
[32mok 125 error should be null
[39m
[32mok 126 error should be null
[39m
[32m# setup
[39m
[33mok 125 error should be null
[39m
[33mok 126 error should be null
[39m
[33m# setup
[39m
2016-08-10T11:35:29.502Z - info: Running on ios test: 44. should be able to call #stopListeningForAdvertisements many times

[33m# 44. should be able to call #stopListeningForAdvertisements many times
[39m
[36m# 44. should be able to call #stopListeningForAdvertisements many times
[39m
[32m# 44. should be able to call #stopListeningForAdvertisements many times
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50960
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50961
[39m
[33mok 127 error should be null
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[33mok 128 error should be null
[39m
[32mDEBUG createNativeListener: listening 50963
[39m
[33mok 129 error should be null
[39m
[33mok 130 error should be null
[39m
[33m# teardown
[39m
[32mok 127 error should be null
[39m
[32mok 128 error should be null
[39m
[32mok 129 error should be null
[39m
[36mok 127 error should be null
[39m
[36mok 128 error should be null
[39m
[32mok 130 error should be null
[39m
[32m# teardown
[39m
[36mok 129 error should be null
ok 130 error should be null
# teardown
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
2016-08-10T11:35:29.541Z - info: Running on ios test: 45. should be able to call #startListeningForAdvertisements many times

[32m# 45. should be able to call #startListeningForAdvertisements many times
[39m
[36m# 45. should be able to call #startListeningForAdvertisements many times
[39m
[33m# 45. should be able to call #startListeningForAdvertisements many times
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50966
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50967
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 133 error should be null
ok 134 error should be null
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[36mok 133 error should be null
[39m
[32mok 135 error should be null
ok 136 error should be null
[39m
[32m# teardown
[39m
[36mok 134 error should be null
[39m
[36mok 135 error should be null
ok 136 error should be null
[39m
[36m# teardown
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: listening 50969
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 133 error should be null
ok 134 error should be null
[39m
[33mok 135 error should be null
[39m
[33mok 136 error should be null
[39m
[33m# teardown
[39m
[32mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 137 error should be null
ok 138 error should be null
# setup
[39m
[36mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 137 error should be null
ok 138 error should be null
# setup
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
2016-08-10T11:35:29.578Z - info: Running on ios test: 46. should be able to call #startUpdateAdvertisingAndListening many times

[36m# 46. should be able to call #startUpdateAdvertisingAndListening many times
[39m
[32m# 46. should be able to call #startUpdateAdvertisingAndListening many times
[39m
[33m# 46. should be able to call #startUpdateAdvertisingAndListening many times
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50972
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: listening 50973
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 139 error should be null
ok 140 error should be null
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 139 error should be null
ok 140 error should be null
[39m
[32mok 141 error should be null
ok 142 error should be null
# teardown
[39m
[36mok 141 error should be null
ok 142 error should be null
# teardown
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: listening 50981
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[33mok 139 error should be null
ok 140 error should be null
[39m
[33mok 141 error should be null
ok 142 error should be null
# teardown
[39m
[32mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[36mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[32mok 143 error should be null
ok 144 error should be null
[39m
[32m# setup
[39m
[36mok 143 error should be null
ok 144 error should be null
# setup
[39m
[33mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mok 143 error should be null
[39m
[33mok 144 error should be null
[39m
[33m# setup
[39m
2016-08-10T11:35:29.628Z - info: Running on ios test: 47. should be able to call #stopAdvertisingAndListening many times

[36m# 47. should be able to call #stopAdvertisingAndListening many times
[39m
[32m# 47. should be able to call #stopAdvertisingAndListening many times
[39m
[33m# 47. should be able to call #stopAdvertisingAndListening many times
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50987
ok 145 error should be null
ok 146 error should be null
ok 147 error should be null
ok 148 error should be null
# teardown
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50988
ok 145 error should be null
ok 146 error should be null
ok 147 error should be null
ok 148 error should be null
# teardown
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50990
[39m
[33mok 145 error should be null
[39m
[33mok 146 error should be null
ok 147 error should be null
ok 148 error should be null
# teardown
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
ok 150 error should be null
# setup
[39m
2016-08-10T11:35:29.662Z - info: Running on ios test: 48. #start should fail if called twice in a row

[32m# 48. #start should fail if called twice in a row
[39m
[33m# 48. #start should fail if called twice in a row
[39m
[36m# 48. #start should fail if called twice in a row
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50993
ok 151 first call should succeed
ok 152 first call should succeed
ok 153 specific error should be returned
# teardown
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50995
ok 151 first call should succeed
ok 152 first call should succeed
ok 153 specific error should be returned
# teardown
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50996
ok 151 first call should succeed
ok 152 first call should succeed
ok 153 specific error should be returned
# teardown
[39m
[36mok 154 error should be null
ok 155 error should be null
# setup
[39m
[32mok 154 error should be null
[39m
[32mok 155 error should be null
[39m
[32m# setup
[39m
[33mok 154 error should be null
ok 155 error should be null
[39m
[33m# setup
[39m
2016-08-10T11:35:29.692Z - info: Running on ios test: 49. does not emit duplicate discoveryAdvertisingStateUpdate

[32m# 49. does not emit duplicate discoveryAdvertisingStateUpdate
[39m
[36m# 49. does not emit duplicate discoveryAdvertisingStateUpdate
[39m
[33m# 49. does not emit duplicate discoveryAdvertisingStateUpdate
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50998
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 156 called only once
ok 157 discovery state matches
ok 158 advertising state matches
# teardown
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51004
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51003
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[33mok 156 called only once
ok 157 discovery state matches
ok 158 advertising state matches
# teardown
[39m
[32mok 156 called only once
ok 157 discovery state matches
ok 158 advertising state matches
# teardown
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
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
DEBUG createPeerListener: pleaseConnect= false
[39m
[33mINFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[32mINFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[32mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 159 error should be null
ok 160 error should be null
[39m
[32mok 159 error should be null
ok 160 error should be null
# setup
[39m
[33m# setup
[39m
[36mDEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[36mok 159 error should be null
[39m
[36mok 160 error should be null
[39m
[36m# setup
[39m
2016-08-10T11:35:29.754Z - info: Running on ios test: 50. does not send duplicate availability changes

[32m# 50. does not send duplicate availability changes
[39m
[33m# 50. does not send duplicate availability changes
[39m
[36m# 50. does not send duplicate availability changes
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
[39m
[36mok 162 should not have been called more than once
[39m
[36m# teardown
[39m
[36mok 163 error should be null
ok 164 error should be null
# setup
[39m
[33mok 163 error should be null
ok 164 error should be null
[39m
[32mok 163 error should be null
ok 164 error should be null
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T11:35:29.789Z - info: Running on ios test: 51. can get the network status

[36m# 51. can get the network status
[39m
[32m# 51. can get the network status
[39m
[33m# 51. can get the network status
[39m
[32mok 165 network status should have certain non-empty properties
[39m
[32m# teardown
[39m
[36mok 165 network status should have certain non-empty properties
[39m
[36m# teardown
[39m
[33mok 165 network status should have certain non-empty properties
[39m
[33m# teardown
[39m
[33mok 166 error should be null
ok 167 error should be null
# setup
[39m
[36mok 166 error should be null
ok 167 error should be null
# setup
[39m
[32mok 166 error should be null
ok 167 error should be null
# setup
[39m
2016-08-10T11:35:29.814Z - info: Running on ios test: 52. wifi peer is marked unavailable if announcements stop

[36m# 52. wifi peer is marked unavailable if announcements stop
[39m
[32m# 52. wifi peer is marked unavailable if announcements stop
[39m
[33m# 52. wifi peer is marked unavailable if announcements stop
[39m
[36mERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
[39m
[33mERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
[39m
[33mok 168 host address should match
ok 169 port should match
[39m
[36mok 168 host address should match
[39m
[32mERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
[39m
[36mok 169 port should match
[39m
[32mok 168 host address should match
ok 169 port should match
[39m
[33mok 170 host address should be null
ok 171 port should should be null
[39m
[33m# teardown
[39m
[36mok 170 host address should be null
[39m
[36mok 171 port should should be null
[39m
[36m# teardown
[39m
[32mok 170 host address should be null
ok 171 port should should be null
[39m
[32m# teardown
[39m
[36mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 172 error should be null
ok 173 error should be null
# setup
[39m
[32mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 172 error should be null
ok 173 error should be null
# setup
[39m
[33mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 172 error should be null
ok 173 error should be null
# setup
[39m
2016-08-10T11:35:31.846Z - info: Running on ios test: 53. network changes emitted correctly

[36m# 53. network changes emitted correctly
[39m
[33m# 53. network changes emitted correctly
[39m
[32m# 53. network changes emitted correctly
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51020
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 174 wifi is off
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 175 wifi is on
# teardown
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51021
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 174 wifi is off
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 175 wifi is on
# teardown
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51023
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
[36mok 176 error should be null
ok 177 error should be null
# setup
[39m
[32mok 176 error should be null
ok 177 error should be null
# setup
[39m
[33mok 176 error should be null
[39m
[33mok 177 error should be null
# setup
[39m
2016-08-10T11:35:31.877Z - info: Running on ios test: 54. network changes not emitted in stopped state

[32m# 54. network changes not emitted in stopped state
[39m
[33m# 54. network changes not emitted in stopped state
[39m
[36m# 54. network changes not emitted in stopped state
[39m
[36mok 178 event was not emitted
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
# teardown
[39m
[32mok 178 event was not emitted
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
# teardown
[39m
[33mok 178 event was not emitted
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
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
# setup
[39m
2016-08-10T11:35:31.901Z - info: Running on ios test: 55. calls correct starts when network changes

[36m# 55. calls correct starts when network changes
[39m
[33m# 55. calls correct starts when network changes
[39m
[32m# 55. calls correct starts when network changes
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: listening 51025
[39m
[32mDEBUG createNativeListener: listening 51027
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51029
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 181 specific error expected
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 181 specific error expected
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[33mok 182 specific error expected
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 182 specific error expected
[39m
[32mok 181 specific error expected
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":true,"advertisingActive":true}
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 182 specific error expected
[39m
[33mINFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":true,"advertisingActive":true}
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mok 183 startListeningForAdvertisements should have been called
ok 184 startUpdateAdvertisingAndListening should have been called
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36m# teardown
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[32mINFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":true,"advertisingActive":true}
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[33mok 183 startListeningForAdvertisements should have been called
ok 184 startUpdateAdvertisingAndListening should have been called
[39m
[32mok 183 startListeningForAdvertisements should have been called
ok 184 startUpdateAdvertisingAndListening should have been called
[39m
[33m# teardown
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32m# teardown
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mINFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
[39m
[32mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[32mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[32mok 185 error should be null
ok 186 error should be null
# setup
[39m
[36mINFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
[39m
[36mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[36mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 185 error should be null
ok 186 error should be null
[39m
[33mDEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
[39m
[33mINFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[36m# setup
[39m
[33mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mok 185 error should be null
ok 186 error should be null
# setup
[39m
2016-08-10T11:35:31.975Z - info: Running on ios test: 56. peer is marked unavailable if port number changes

[36m# 56. peer is marked unavailable if port number changes
[39m
[33m# 56. peer is marked unavailable if port number changes
[39m
[32m# 56. peer is marked unavailable if port number changes
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51055
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
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51054
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
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51056
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
[39m
[33mok 199 port number must match
[39m
[36mok 197 peer should have a connection type
[39m
[36mok 198 connection type should match one of the pre-defined types
[39m
[33mok 200 peer should have a non-empty identifier
ok 201 peer should have a non-empty host address
ok 202 peer should have port number
ok 203 peer should have suggested timeout
ok 204 peer should have a connection type
ok 205 connection type should match one of the pre-defined types
# teardown
[39m
[36mok 199 port number must match
ok 200 peer should have a non-empty identifier
ok 201 peer should have a non-empty host address
ok 202 peer should have port number
ok 203 peer should have suggested timeout
ok 204 peer should have a connection type
ok 205 connection type should match one of the pre-defined types
[39m
[36m# teardown
[39m
[36mok 206 error should be null
ok 207 error should be null
# setup
[39m
[32mok 206 error should be null
ok 207 error should be null
# setup
[39m
[33mok 206 error should be null
ok 207 error should be null
[39m
[33m# setup
[39m
2016-08-10T11:35:32.012Z - info: Running on ios test: 57. when network connection is lost a peer should be marked unavailable

[36m# 57. when network connection is lost a peer should be marked unavailable
[39m
[32m# 57. when network connection is lost a peer should be marked unavailable
[39m
[33m# 57. when network connection is lost a peer should be marked unavailable
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51059
INFO testUtils: Toggling radios to: false
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51060
INFO testUtils: Toggling radios to: false
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 208 peer should have a non-empty identifier
[39m
[36mok 209 host address should be null
ok 210 port number should be null
ok 211 peer should have suggested timeout
[39m
[36mok 212 peer should have a connection type
ok 213 connection type should match one of the pre-defined types
INFO testUtils: Toggling radios to: true
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: listening 51062
[39m
[32mINFO testUtils: Toggling radios to: false
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[32mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[32mok 208 peer should have a non-empty identifier
[39m
[32mok 209 host address should be null
[39m
[32mok 210 port number should be null
ok 211 peer should have suggested timeout
[39m
[32mok 212 peer should have a connection type
ok 213 connection type should match one of the pre-defined types
[39m
[32mINFO testUtils: Toggling radios to: true
[39m
[36m# teardown
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[32mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[32m# teardown
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mok 208 peer should have a non-empty identifier
ok 209 host address should be null
[39m
[33mok 210 port number should be null
[39m
[33mok 211 peer should have suggested timeout
ok 212 peer should have a connection type
[39m
[33mok 213 connection type should match one of the pre-defined types
[39m
[33mINFO testUtils: Toggling radios to: true
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33m# teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[32mok 214 error should be null
ok 215 error should be null
# setup
[39m
[36mok 214 error should be null
[39m
[36mok 215 error should be null
[39m
[36m# setup
[39m
[33mok 214 error should be null
ok 215 error should be null
[39m
[33m# setup
[39m
2016-08-10T11:35:32.053Z - info: Running on ios test: 58. peer should be found once after listening and discovery started

[32m# 58. peer should be found once after listening and discovery started
[39m
[36m# 58. peer should be found once after listening and discovery started
[39m
[33m# 58. peer should be found once after listening and discovery started
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[32mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: listening 51065
[39m
[36mok 216 error should be null
[39m
[36mok 217 error should be null
[39m
[32mDEBUG createNativeListener: listening 51066
[39m
[32mok 216 error should be null
ok 217 error should be null
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 218 error should be null
ok 219 error should be null
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 220 error should be null
ok 221 error should be null
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
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[36mok 222 peer should have a non-empty identifier
ok 223 peer should have a non-empty host address
ok 224 peer should have port number
ok 225 peer should have suggested timeout
[39m
[36mok 226 peer should have a connection type
[39m
[36mok 227 connection type should match one of the pre-defined types
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: listening 51076
[39m
[33mok 216 error should be null
ok 217 error should be null
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[33mok 218 error should be null
ok 219 error should be null
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[33mok 220 error should be null
ok 221 error should be null
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
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
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mnot ok 228 must not receive too many peer availabilities
  ---
    operator: ok
    expected: true
    actual:   false
    at: null._onTimeout (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js:521:9)
  ...
# teardown
[39m
[36mnot ok 228 must not receive too many peer availabilities
  ---
    operator: ok
    expected: true
    actual:   false
    at: null._onTimeout (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js:521:9)
  ...
[39m
[36m# teardown
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
[36mINFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
[39m
[36mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[36mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[32mDEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[36mok 229 error should be null
[39m
[36mok 230 error should be null
[39m
[36m# setup
[39m
[32mINFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
[39m
[32mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[32mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[32mok 229 error should be null
ok 230 error should be null
[39m
[32m# setup
[39m
2016-08-10T11:35:35.232Z - warn: Failed on ios test: 58. peer should be found once after listening and discovery started
2016-08-10T11:35:35.232Z - info: Running on ios test: 59. can get data from all participants

[33m# 59. can get data from all participants
[39m
[32m# 59. can get data from all participants
[39m
[36m# 59. can get data from all participants
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: listening 51085
ok 231 error should be null
ok 232 error should be null
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51087
ok 231 error should be null
ok 232 error should be null
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[33mok 233 error should be null
ok 234 error should be null
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 235 error should be null
ok 236 error should be null
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: listening 51094
[39m
[36mok 231 error should be null
[39m
[36mok 232 error should be null
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[36mok 233 error should be null
[39m
[36mok 234 error should be null
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[36mok 235 error should be null
[39m
[36mok 236 error should be null
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mok 233 error should be null
[39m
[32mok 234 error should be null
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 235 error should be null
ok 236 error should be null
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
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
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[33mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
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
[33mok 237 received uuid must be in remaining list
[39m
[33mok 238 received uuid must be in remaining list
ok 239 received all uuids
[39m
[33m# teardown
[39m
[36mok 237 received uuid must be in remaining list
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
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
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createNativeListener: new incoming socket
[39m
[33mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createNativeListener: new mux
[39m
[33mDEBUG wifiBasedNativeMock: proxy socket connected
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
[36mDEBUG createPeerListener: forward connection
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[36mok 238 received uuid must be in remaining list
[39m
[36mok 239 received all uuids
[39m
[36m# teardown
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[32mok 237 received uuid must be in remaining list
[39m
[32mok 238 received uuid must be in remaining list
[39m
[32mok 239 received all uuids
[39m
[32m# teardown
[39m
[33mINFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
[39m
[33mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[33mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[36mINFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
[39m
[36mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[36mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: mux close
[39m
[33mDEBUG createNativeListener: mux close
[39m
[33mok 240 error should be null
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[33mok 241 error should be null
[39m
[36mDEBUG createNativeListener: mux close
[39m
[36mok 240 error should be null
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[36mok 241 error should be null
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[33m# setup
[39m
[32mDEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
[39m
[32mDEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
[39m
[36m# setup
[39m
[32mDEBUG createPeerListener: Recreating listener
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
[39m
[32mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mINFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
[39m
[32mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[32mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: mux close
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createNativeListener: mux close
[39m
[32mok 240 error should be null
[39m
[32mok 241 error should be null
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[32m# setup
[39m
2016-08-10T11:35:35.924Z - info: Running on ios test: 60. Can call start/stopListeningForAdvertisements

[36m# 60. Can call start/stopListeningForAdvertisements
[39m
[32m# 60. Can call start/stopListeningForAdvertisements
[39m
[33m# 60. Can call start/stopListeningForAdvertisements
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 242 Can call startListeningForAdvertisements without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 243 Can call stopListeningForAdvertisements without error
# teardown
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[36mok 242 Can call startListeningForAdvertisements without error
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
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
[36mok 244 Should be able to call stopListeningForAdvertisements in teardown
ok 245 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[32mok 244 Should be able to call stopListeningForAdvertisements in teardown
ok 245 Should be able to call stopAdvertisingAndListening in teardown
# setup
[39m
[33mok 244 Should be able to call stopListeningForAdvertisements in teardown
ok 245 Should be able to call stopAdvertisingAndListening in teardown
[39m
[33m# setup
[39m
2016-08-10T11:35:35.953Z - info: Running on ios test: 61. Client to server request coordinated

[32m# 61. Client to server request coordinated
[39m
[36m# 61. Client to server request coordinated
[39m
[33m# 61. Client to server request coordinated
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51143
ok 246 error should be null
ok 247 error should be null
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51145
ok 246 error should be null
ok 247 error should be null
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51150
ok 246 error should be null
ok 247 error should be null
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
INFO testThaliNotification: startListeningForAdvertisements
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
INFO testThaliNotification: startListeningForAdvertisements
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[32mDEBUG createPeerListener: first connection
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[33mINFO testThaliNotification: startListeningForAdvertisements
[39m
[36mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
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
[36mINFO testThaliNotification: PeerAdvertisesDataForUs:tcp, 192.168.1.20, 192.168.1.20, 51156
[39m
[32mINFO testThaliNotification: PeerAdvertisesDataForUs:tcp, 192.168.1.20, 192.168.1.20, 51151
[39m
[32mINFO testThaliNotification: PeerAdvertisesDataForUs:tcp, 192.168.1.20, 192.168.1.20, 51156
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[36mINFO testThaliNotification: PeerAdvertisesDataForUs:MPCF, 127.0.0.1, 127.0.0.1, 51164
[39m
[33mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: 
DEBUG createNativeListener: stream close:
[39m
[32mINFO testThaliNotification: PeerAdvertisesDataForUs:MPCF, 127.0.0.1, 127.0.0.1, 51163
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[32mINFO testThaliNotification: PeerAdvertisesDataForUs:MPCF, 127.0.0.1, 127.0.0.1, 51154
[39m
[36mDEBUG createPeerListener: error on incoming stream - Error: Channel destroyed
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: 
DEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[32mDEBUG createPeerListener: error on incoming stream - Error: Channel destroyed
[39m
[32mDEBUG createPeerListener: error on incoming stream - Error: Channel destroyed
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: first connection
[39m
[33mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[33mINFO testThaliNotification: PeerAdvertisesDataForUs:tcp, 192.168.1.20, 192.168.1.20, 51146
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mINFO testThaliNotification: PeerAdvertisesDataForUs:tcp, 192.168.1.20, 192.168.1.20, 51151
[39m
[36mINFO testThaliNotification: PeerAdvertisesDataForUs:tcp, 192.168.1.20, 192.168.1.20, 51146
[39m
[33mDEBUG createPeerListener: forward connection
[39m
[33mDEBUG createPeerListener: forward connection
[39m
[32mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[32mDEBUG createNativeListener: new stream: 
[39m
[32mDEBUG createNativeListener: new outgoing socket
[39m
[33mINFO testThaliNotification: PeerAdvertisesDataForUs:MPCF, 127.0.0.1, 127.0.0.1, 51196
[39m
[36mINFO testThaliNotification: PeerAdvertisesDataForUs:MPCF, 127.0.0.1, 127.0.0.1, 51194
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
DEBUG createNativeListener: stream close:
[39m
[33mINFO testThaliNotification: PeerAdvertisesDataForUs:MPCF, 127.0.0.1, 127.0.0.1, 51193
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: 
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createPeerListener: error on incoming stream - Error: Channel destroyed
[39m
[32mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createPeerListener: error on incoming stream - Error: Channel destroyed
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createPeerListener: error on incoming stream - Error: Channel destroyed
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 248 Peer made successful https requests to all peers
ok 249 Peer received right amount of https requests
ok 250 HTTPS server received zero PSK Identities. Count:0
DEBUG createPeerListener: Recreating listener
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: Recreating listener
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
# teardown
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 248 Peer made successful https requests to all peers
ok 249 Peer received right amount of https requests
ok 250 HTTPS server received zero PSK Identities. Count:0
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
[33mok 248 Peer made successful https requests to all peers
[39m
[33mok 249 Peer received right amount of https requests
[39m
[33mok 250 HTTPS server received zero PSK Identities. Count:0
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
[33m# teardown
[39m
[36mINFO testThaliNotification: Participants:3 Peers Replied to us:2 Peers requested to:2
[39m
[32mINFO testThaliNotification: Participants:3 Peers Replied to us:2 Peers requested to:2
[39m
[32mDEBUG createNativeListener: mux close
DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
[39m
[33mINFO testThaliNotification: Participants:3 Peers Replied to us:2 Peers requested to:2
DEBUG createNativeListener: mux close
DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
[39m
[33mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createNativeListener: mux close
DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
[39m
2016-08-10T11:35:41.009Z - info: Running on ios test: 62. Test BEACONS_RETRIEVED_AND_PARSED locally

[32m# 62. Test BEACONS_RETRIEVED_AND_PARSED locally
[39m
[36m# 62. Test BEACONS_RETRIEVED_AND_PARSED locally
[39m
[33m# 62. Test BEACONS_RETRIEVED_AND_PARSED locally
[39m
[32mok 251 peerIdentifier should be identifier
ok 252 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 253 good beacon
ok 254 good preAmble
ok 255 public keys match!
ok 256 must return null after successful call
ok 257 Once start returns the action should be in KILLED state
[39m
[36mok 251 peerIdentifier should be identifier
ok 252 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 253 good beacon
ok 254 good preAmble
ok 255 public keys match!
ok 256 must return null after successful call
ok 257 Once start returns the action should be in KILLED state
[39m
[36m# teardown
[39m
[32m# teardown
[39m
[33mok 251 peerIdentifier should be identifier
[39m
[33mok 252 Response should be BEACONS_RETRIEVED_AND_PARSED
[39m
[33mok 253 good beacon
[39m
[33mok 254 good preAmble
[39m
[33mok 255 public keys match!
[39m
[33mok 256 must return null after successful call
[39m
[33mok 257 Once start returns the action should be in KILLED state
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-10T11:35:41.066Z - info: Running on ios test: 63. Test HTTP_BAD_RESPONSE locally

[32m# 63. Test HTTP_BAD_RESPONSE locally
[39m
[36m# 63. Test HTTP_BAD_RESPONSE locally
[39m
[33m# 63. Test HTTP_BAD_RESPONSE locally
[39m
[36mok 258 Response should be HTTP_BAD_RESPONSE
ok 259 must return null after successful call
# teardown
[39m
[32mok 258 Response should be HTTP_BAD_RESPONSE
ok 259 must return null after successful call
# teardown
[39m
[33mok 258 Response should be HTTP_BAD_RESPONSE
[39m
[33mok 259 must return null after successful call
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-10T11:35:41.114Z - info: Running on ios test: 64. Test NETWORK_PROBLEM locally

[32m# 64. Test NETWORK_PROBLEM locally
[39m
[36m# 64. Test NETWORK_PROBLEM locally
[39m
[33m# 64. Test NETWORK_PROBLEM locally
[39m
[36mok 260 Response should be NETWORK_PROBLEM
[39m
[36mok 261 reject reason should be: Could not establish TCP connection
[39m
[32mok 260 Response should be NETWORK_PROBLEM
[39m
[36m# teardown
[39m
[32mok 261 reject reason should be: Could not establish TCP connection
[39m
[32m# teardown
[39m
[33mok 260 Response should be NETWORK_PROBLEM
[39m
[33mok 261 reject reason should be: Could not establish TCP connection
[39m
[33m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T11:35:41.160Z - info: Running on ios test: 65. Call the start two times

[36m# 65. Call the start two times
[39m
[32m# 65. Call the start two times
[39m
[33m# 65. Call the start two times
[39m
[36mok 262 Call start once
[39m
[32mok 262 Call start once
[39m
[33mok 262 Call start once
[39m
[36mok 263 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 264 must return null after successful call.
[39m
[36m# teardown
[39m
[32mok 263 Response should be BEACONS_RETRIEVED_AND_PARSED
[39m
[32mok 264 must return null after successful call.
[39m
[32m# teardown
[39m
[33mok 263 Response should be BEACONS_RETRIEVED_AND_PARSED
[39m
[33mok 264 must return null after successful call.
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-10T11:35:41.223Z - info: Running on ios test: 66. Call the kill before calling the start

[36m# 66. Call the kill before calling the start
[39m
[32m# 66. Call the kill before calling the start
[39m
[33m# 66. Call the kill before calling the start
[39m
[32mok 265 Should be Killed
ok 266 Start after killed
# teardown
[39m
[36mok 265 Should be Killed
ok 266 Start after killed
[39m
[36m# teardown
[39m
[33mok 265 Should be Killed
[39m
[33mok 266 Start after killed
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-10T11:35:41.260Z - info: Running on ios test: 67. Call the kill immediately after the start

[36m# 67. Call the kill immediately after the start
[39m
[32m# 67. Call the kill immediately after the start
[39m
[33m# 67. Call the kill immediately after the start
[39m
[36mok 267 Should be KILLED
[39m
[36mok 268 must return null after successful kill
[39m
[32mok 267 Should be KILLED
ok 268 must return null after successful kill
[39m
[32m# teardown
[39m
[36m# teardown
[39m
[33mok 267 Should be KILLED
[39m
[33mok 268 must return null after successful kill
[39m
[33m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T11:35:41.296Z - info: Running on ios test: 68. Call the kill while waiting a response from the server

[36m# 68. Call the kill while waiting a response from the server
[39m
[32m# 68. Call the kill while waiting a response from the server
[39m
[33m# 68. Call the kill while waiting a response from the server
[39m
[32mok 269 Should be KILLED
ok 270 must return null after successful kill
[39m
[36mok 269 Should be KILLED
ok 270 must return null after successful kill
[39m
[32m# teardown
[39m
[36m# teardown
[39m
[33mok 269 Should be KILLED
ok 270 must return null after successful kill
[39m
[33m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T11:35:43.338Z - info: Running on ios test: 69. Test to exceed the max content size locally

[32m# 69. Test to exceed the max content size locally
[39m
[36m# 69. Test to exceed the max content size locally
[39m
[33m# 69. Test to exceed the max content size locally
[39m
[36mok 271 HTTP_BAD_RESPONSE should be response when content size is exceeded
ok 272 must return null after successful call
[39m
[32mok 271 HTTP_BAD_RESPONSE should be response when content size is exceeded
ok 272 must return null after successful call
[39m
[36m# teardown
[39m
[32m# teardown
[39m
[33mok 271 HTTP_BAD_RESPONSE should be response when content size is exceeded
[39m
[33mok 272 must return null after successful call
[39m
[33m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T11:35:43.385Z - info: Running on ios test: 70. Close the server socket while the client is waiting a response from the server. Local test.

[32m# 70. Close the server socket while the client is waiting a response from the server. Local test.
[39m
[36m# 70. Close the server socket while the client is waiting a response from the server. Local test.
[39m
[33m# 70. Close the server socket while the client is waiting a response from the server. Local test.
[39m
[33mok 273 Should be NETWORK_PROBLEM caused closing server socket
ok 274 Should be Could not establish TCP connection
# teardown
[39m
[36mok 273 Should be NETWORK_PROBLEM caused closing server socket
ok 274 Should be Could not establish TCP connection
# teardown
[39m
[32mok 273 Should be NETWORK_PROBLEM caused closing server socket
[39m
[32mok 274 Should be Could not establish TCP connection
# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T11:35:45.423Z - info: Running on ios test: 71. Close the client socket while the client is waiting a response from the server. Local test.

[32m# 71. Close the client socket while the client is waiting a response from the server. Local test.
[39m
[36m# 71. Close the client socket while the client is waiting a response from the server. Local test.
[39m
[33m# 71. Close the client socket while the client is waiting a response from the server. Local test.
[39m
[36mok 275 Should be NETWORK_PROBLEM caused closing client socket
ok 276 Should be Could not establish TCP connection
[39m
[36m# teardown
[39m
[32mok 275 Should be NETWORK_PROBLEM caused closing client socket
ok 276 Should be Could not establish TCP connection
# teardown
[39m
[33mok 275 Should be NETWORK_PROBLEM caused closing client socket
ok 276 Should be Could not establish TCP connection
[39m
[33m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T11:35:47.464Z - info: Running on ios test: 72. #generatePreambleAndBeacons bad args

[33m# 72. #generatePreambleAndBeacons bad args
[39m
[32m# 72. #generatePreambleAndBeacons bad args
[39m
[36m# 72. #generatePreambleAndBeacons bad args
[39m
[36mok 277 publicKeysToNotify cannot be null
ok 278 ecdh for local device cannot be null
ok 279 milliseconds cannot be less than 0
ok 280 milliseconds cannot be 0
ok 281 milliseconds cannot be greater than one_day
# teardown
[39m
[32mok 277 publicKeysToNotify cannot be null
ok 278 ecdh for local device cannot be null
ok 279 milliseconds cannot be less than 0
ok 280 milliseconds cannot be 0
ok 281 milliseconds cannot be greater than one_day
# teardown
[39m
[33mok 277 publicKeysToNotify cannot be null
ok 278 ecdh for local device cannot be null
ok 279 milliseconds cannot be less than 0
ok 280 milliseconds cannot be 0
ok 281 milliseconds cannot be greater than one_day
# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T11:35:47.491Z - info: Running on ios test: 73. #generatePreambleAndBeacons empty keys to notify

[32m# 73. #generatePreambleAndBeacons empty keys to notify
[39m
[36m# 73. #generatePreambleAndBeacons empty keys to notify
[39m
[33m# 73. #generatePreambleAndBeacons empty keys to notify
[39m
[36mok 282 should be equal
# teardown
[39m
[32mok 282 should be equal
# teardown
[39m
[33mok 282 should be equal
# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T11:35:47.516Z - info: Running on ios test: 74. #generatePreambleAndBeacons multiple keys to notify

[36m# 74. #generatePreambleAndBeacons multiple keys to notify
[39m
[32m# 74. #generatePreambleAndBeacons multiple keys to notify
[39m
[33m# 74. #generatePreambleAndBeacons multiple keys to notify
[39m
[32mok 283 should be equal
ok 284 should be equal
ok 285 (unnamed assert)
ok 286 should be equal
# teardown
[39m
[33mok 283 should be equal
ok 284 should be equal
ok 285 (unnamed assert)
ok 286 should be equal
# teardown
[39m
[36mok 283 should be equal
ok 284 should be equal
ok 285 (unnamed assert)
ok 286 should be equal
# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-10T11:35:47.551Z - info: Running on ios test: 75. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

[36m# 75. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
[39m
[33m# 75. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
[39m
[32m# 75. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
[39m
[32mok 287 should throw
[39m
[33mok 287 should throw
# teardown
[39m
[32m# teardown
[39m
[36mok 287 should throw
[39m
[36m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T11:35:47.582Z - info: Running on ios test: 76. #parseBeacons invalid expiration in beaconStreamWithPreAmble

[32m# 76. #parseBeacons invalid expiration in beaconStreamWithPreAmble
[39m
[33m# 76. #parseBeacons invalid expiration in beaconStreamWithPreAmble
[39m
[36m# 76. #parseBeacons invalid expiration in beaconStreamWithPreAmble
[39m
[32mok 288 Preamble expiration must be a 64 bit integer
# teardown
[39m
[33mok 288 Preamble expiration must be a 64 bit integer
# teardown
[39m
[36mok 288 Preamble expiration must be a 64 bit integer
[39m
[36m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T11:35:47.612Z - info: Running on ios test: 77. #parseBeacons expiration out of range lower

[33m# 77. #parseBeacons expiration out of range lower
[39m
[32m# 77. #parseBeacons expiration out of range lower
[39m
[36m# 77. #parseBeacons expiration out of range lower
[39m
[33mok 289 Expiration out of range
# teardown
[39m
[32mok 289 Expiration out of range
[39m
[32m# teardown
[39m
[36mok 289 Expiration out of range
[39m
[36m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-10T11:35:47.643Z - info: Running on ios test: 78. #parseBeacons expiration out of range lower

[33m# 78. #parseBeacons expiration out of range lower
[39m
[32m# 78. #parseBeacons expiration out of range lower
[39m
[36m# 78. #parseBeacons expiration out of range lower
[39m
[32mok 290 Expiration out of range
# teardown
[39m
[33mok 290 Expiration out of range
# teardown
[39m
[36mok 290 Expiration out of range
# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T11:35:47.672Z - info: Running on ios test: 79. #parseBeacons no beacons returns null

[32m# 79. #parseBeacons no beacons returns null
[39m
[33m# 79. #parseBeacons no beacons returns null
[39m
[36m# 79. #parseBeacons no beacons returns null
[39m
[33mok 291 should be equal
# teardown
[39m
[32mok 291 should be equal
# teardown
[39m
[36mok 291 should be equal
[39m
[36m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T11:35:47.701Z - info: Running on ios test: 80. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

[36m# 80. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
[39m
[32m# 80. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
[39m
[33m# 80. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
[39m
[32mok 292 Malformed encrypted beacon key ID
# teardown
[39m
[33mok 292 Malformed encrypted beacon key ID
[39m
[33m# teardown
[39m
[36mok 292 Malformed encrypted beacon key ID
[39m
[36m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T11:35:47.728Z - info: Running on ios test: 81. #parseBeacons addressBookCallback fails decrypt

[32m# 81. #parseBeacons addressBookCallback fails decrypt
[39m
[33m# 81. #parseBeacons addressBookCallback fails decrypt
[39m
[36m# 81. #parseBeacons addressBookCallback fails decrypt
[39m
[32mok 293 should be equal
# teardown
[39m
[33mok 293 should be equal
[39m
[33m# teardown
[39m
[36mok 293 should be equal
[39m
[36m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T11:35:47.771Z - info: Running on ios test: 82. #parseBeacons addressBookCallback returns no matches

[33m# 82. #parseBeacons addressBookCallback returns no matches
[39m
[32m# 82. #parseBeacons addressBookCallback returns no matches
[39m
[36m# 82. #parseBeacons addressBookCallback returns no matches
[39m
[32mok 294 should be equal
ok 295 should be equal
# teardown
[39m
[33mok 294 should be equal
[39m
[33mok 295 should be equal
[39m
[33m# teardown
[39m
[36mok 294 should be equal
[39m
[36mok 295 should be equal
[39m
[36m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T11:35:47.816Z - info: Running on ios test: 83. #parseBeacons addressBookCallback returns spurious match

[32m# 83. #parseBeacons addressBookCallback returns spurious match
[39m
[33m# 83. #parseBeacons addressBookCallback returns spurious match
[39m
[36m# 83. #parseBeacons addressBookCallback returns spurious match
[39m
[32mok 296 should be equal
ok 297 should be equal
# teardown
[39m
[33mok 296 should be equal
ok 297 should be equal
# teardown
[39m
[36mok 296 should be equal
ok 297 should be equal
[39m
[36m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T11:35:47.864Z - info: Running on ios test: 84. #parseBeacons addressBookCallback returns public key

[32m# 84. #parseBeacons addressBookCallback returns public key
[39m
[33m# 84. #parseBeacons addressBookCallback returns public key
[39m
[36m# 84. #parseBeacons addressBookCallback returns public key
[39m
[32mok 298 right number of calls to address book
ok 299 good preAmble
ok 300 good unencryptedKeyId
ok 301 good beacon
# teardown
[39m
[33mok 298 right number of calls to address book
[39m
[33mok 299 good preAmble
[39m
[33mok 300 good unencryptedKeyId
[39m
[33mok 301 good beacon
[39m
[33m# teardown
[39m
[36mok 298 right number of calls to address book
ok 299 good preAmble
[39m
[36mok 300 good unencryptedKeyId
ok 301 good beacon
[39m
[36m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T11:35:47.911Z - info: Running on ios test: 85. validate generatePskIdentityField

[32m# 85. validate generatePskIdentityField
[39m
[33m# 85. validate generatePskIdentityField
[39m
[36m# 85. validate generatePskIdentityField
[39m
[32mok 302 decoded buffers match
[39m
[33mok 302 decoded buffers match
[39m
[32m# teardown
[39m
[33m# teardown
[39m
[36mok 302 decoded buffers match
# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T11:35:47.949Z - info: Running on ios test: 86. validate generatePskSecret

[33m# 86. validate generatePskSecret
[39m
[32m# 86. validate generatePskSecret
[39m
[36m# 86. validate generatePskSecret
[39m
[32mok 303 secrets match
# teardown
[39m
[33mok 303 secrets match
[39m
[33m# teardown
[39m
[36mok 303 secrets match
# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-10T11:35:47.984Z - info: Running on ios test: 87. validate generatePskSecrets

[32m# 87. validate generatePskSecrets
[39m
[33m# 87. validate generatePskSecrets
[39m
[36m# 87. validate generatePskSecrets
[39m
[33mok 304 Matching numbers
ok 305 We have an entry!
ok 306 keys match
ok 307 secrets match
[39m
[32mok 304 Matching numbers
[39m
[32mok 305 We have an entry!
ok 306 keys match
ok 307 secrets match
[39m
[33mok 308 We have an entry!
ok 309 keys match
ok 310 secrets match
[39m
[32mok 308 We have an entry!
[39m
[32mok 309 keys match
[39m
[32mok 310 secrets match
[39m
[32mok 311 We have an entry!
ok 312 keys match
ok 313 secrets match
# teardown
[39m
[33mok 311 We have an entry!
ok 312 keys match
[39m
[33mok 313 secrets match
[39m
[33m# teardown
[39m
[36mok 304 Matching numbers
[39m
[36mok 305 We have an entry!
[39m
[36mok 306 keys match
ok 307 secrets match
[39m
[36mok 308 We have an entry!
ok 309 keys match
ok 310 secrets match
[39m
[36mok 311 We have an entry!
ok 312 keys match
ok 313 secrets match
[39m
[36m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-10T11:35:48.038Z - info: Running on ios test: 88. validate generateBeaconStreamAndSecrets

[36m# 88. validate generateBeaconStreamAndSecrets
[39m
[32m# 88. validate generateBeaconStreamAndSecrets
[39m
[33m# 88. validate generateBeaconStreamAndSecrets
[39m
[32mok 314 Streams have same length
ok 315 matching size
ok 316 keys match
ok 317 secrets match
# teardown
[39m
[36mok 314 Streams have same length
ok 315 matching size
ok 316 keys match
ok 317 secrets match
[39m
[36m# teardown
[39m
[33mok 314 Streams have same length
[39m
[33mok 315 matching size
[39m
[33mok 316 keys match
ok 317 secrets match
[39m
[33m# teardown
[39m
[33m# setup
[39m
[32m# setup
[39m
[36m# setup
[39m
2016-08-10T11:35:48.083Z - info: Running on ios test: 89. Add two Peers.

[32m# 89. Add two Peers.
[39m
[36m# 89. Add two Peers.
[39m
[33m# 89. Add two Peers.
[39m
[32mok 318 should be equal
ok 319 should be equal
ok 320 should be equal
ok 321 should be equal
ok 322 should be equal
# teardown
[39m
[36mok 318 should be equal
ok 319 should be equal
ok 320 should be equal
ok 321 should be equal
ok 322 should be equal
[39m
[36m# teardown
[39m
[33mok 318 should be equal
ok 319 should be equal
[39m
[33mok 320 should be equal
ok 321 should be equal
ok 322 should be equal
[39m
[33m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T11:35:48.216Z - info: Running on ios test: 90. TCP_NATIVE peer loses DNS

[32m# 90. TCP_NATIVE peer loses DNS
[39m
[36m# 90. TCP_NATIVE peer loses DNS
[39m
[33m# 90. TCP_NATIVE peer loses DNS
[39m
[32mok 323 should be equal
[39m
[32mok 324 should be equal
[39m
[32m# teardown
[39m
[36mok 323 should be equal
[39m
[36mok 324 should be equal
[39m
[33mok 323 should be equal
[39m
[36m# teardown
[39m
[33mok 324 should be equal
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-10T11:35:48.263Z - info: Running on ios test: 91. Received beacons with no values for us

[32m# 91. Received beacons with no values for us
[39m
[36m# 91. Received beacons with no values for us
[39m
[33m# 91. Received beacons with no values for us
[39m
[32mok 325 entry exists
ok 326 entry is resolved
[39m
[32m# teardown
[39m
[36mok 325 entry exists
ok 326 entry is resolved
[39m
[36m# teardown
[39m
[33mok 325 entry exists
ok 326 entry is resolved
[39m
[33m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T11:35:48.327Z - info: Running on ios test: 92. Resolves an action locally

[32m# 92. Resolves an action locally
[39m
[36m# 92. Resolves an action locally
[39m
[33m# 92. Resolves an action locally
[39m
[32mok 327 Host address must match
ok 328 suggestedTCPTimeout must match
ok 329 connectionType must match
ok 330 portNumber must match
[39m
[32m# teardown
[39m
[36mok 327 Host address must match
ok 328 suggestedTCPTimeout must match
ok 329 connectionType must match
[39m
[36mok 330 portNumber must match
[39m
[36m# teardown
[39m
[33mok 327 Host address must match
ok 328 suggestedTCPTimeout must match
[39m
[33mok 329 connectionType must match
ok 330 portNumber must match
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-10T11:35:48.389Z - info: Running on ios test: 93. Resolves an action locally using ThaliPeerPoolDefault

[32m# 93. Resolves an action locally using ThaliPeerPoolDefault
[39m
[36m# 93. Resolves an action locally using ThaliPeerPoolDefault
[39m
[33m# 93. Resolves an action locally using ThaliPeerPoolDefault
[39m
[32mok 331 Host address must match
ok 332 suggestedTCPTimeout must match
ok 333 connectionType must match
ok 334 portNumber must match
[39m
[32m# teardown
[39m
[36mok 331 Host address must match
ok 332 suggestedTCPTimeout must match
ok 333 connectionType must match
ok 334 portNumber must match
[39m
[36m# teardown
[39m
[33mok 331 Host address must match
ok 332 suggestedTCPTimeout must match
[39m
[33mok 333 connectionType must match
ok 334 portNumber must match
# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T11:35:48.448Z - info: Running on ios test: 94. Action fails because of a bad hostname.

[36m# 94. Action fails because of a bad hostname.
[39m
[32m# 94. Action fails because of a bad hostname.
[39m
[33m# 94. Action fails because of a bad hostname.
[39m
[32mok 335 should be equal
ok 336 should be equal
ok 337 should be equal
[39m
[32m# teardown
[39m
[36mok 335 should be equal
ok 336 should be equal
ok 337 should be equal
# teardown
[39m
[33mok 335 should be equal
ok 336 should be equal
ok 337 should be equal
# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T11:35:53.494Z - info: Running on ios test: 95. hostaddress is removed when the action is running. 

[36m# 95. hostaddress is removed when the action is running. 
[39m
[32m# 95. hostaddress is removed when the action is running. 
[39m
[33m# 95. hostaddress is removed when the action is running. 
[39m
[36mok 338 should be equal
# teardown
[39m
[32mok 338 should be equal
# teardown
[39m
[33mok 338 should be equal
# teardown
[39m
[33m# setup
[39m
[32m# setup
[39m
[36m# setup
[39m
2016-08-10T11:35:55.539Z - info: Running on ios test: 96. Client to server request locally

[33m# 96. Client to server request locally
[39m
[32m# 96. Client to server request locally
[39m
[36m# 96. Client to server request locally
[39m
[32mok 339 secrets are equal
ok 340 Public key matches with the server key
ok 341 Host address must match
ok 342 suggestedTCPTimeout must match
ok 343 connectionType must match
ok 344 portNumber must match
# teardown
[39m
[33mok 339 secrets are equal
[39m
[36mok 339 secrets are equal
[39m
[36mok 340 Public key matches with the server key
ok 341 Host address must match
[39m
[36mok 342 suggestedTCPTimeout must match
[39m
[36mok 343 connectionType must match
ok 344 portNumber must match
[39m
[33mok 340 Public key matches with the server key
[39m
[33mok 341 Host address must match
ok 342 suggestedTCPTimeout must match
ok 343 connectionType must match
ok 344 portNumber must match
[39m
[36m# teardown
[39m
[33m# teardown
[39m
[33m# setup
[39m
[32m# setup
[39m
[36m# setup
[39m
2016-08-10T11:35:55.598Z - info: Running on ios test: 97. Test ThaliPskMapCache clean and expiration

[36m# 97. Test ThaliPskMapCache clean and expiration
[39m
[32m# 97. Test ThaliPskMapCache clean and expiration
[39m
[33m# 97. Test ThaliPskMapCache clean and expiration
[39m
[36mok 345 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
ok 346 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
[39m
[33mok 345 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
ok 346 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
[39m
[32mok 345 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
ok 346 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
[39m
[36mok 347 All entries should be expired after 1 second
# teardown
[39m
[33mok 347 All entries should be expired after 1 second
# teardown
[39m
[32mok 347 All entries should be expired after 1 second
# teardown
[39m
[33m# setup
[39m
[32m# setup
[39m
[36m# setup
[39m
2016-08-10T11:35:56.635Z - info: Running on ios test: 98. Test ThaliPskMapCache getSecret and getPublic

[33m# 98. Test ThaliPskMapCache getSecret and getPublic
[39m
[32m# 98. Test ThaliPskMapCache getSecret and getPublic
[39m
[36m# 98. Test ThaliPskMapCache getSecret and getPublic
[39m
[33mok 348 All keys need to be available in the cache
[39m
[32mok 348 All keys need to be available in the cache
[39m
[36mok 348 All keys need to be available in the cache
[39m
[32mok 349 All entries should be expired after 1 second
# teardown
[39m
[33mok 349 All entries should be expired after 1 second
# teardown
[39m
[36mok 349 All entries should be expired after 1 second
[39m
[36m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T11:35:57.680Z - info: Running on ios test: 99. Test ThaliPskMapCache multiple entries

[32m# 99. Test ThaliPskMapCache multiple entries
[39m
[33m# 99. Test ThaliPskMapCache multiple entries
[39m
[36m# 99. Test ThaliPskMapCache multiple entries
[39m
[32mok 350 Size of the cache should be 2
ok 351 Cache doesn't contain dictionary1
[39m
[36mok 350 Size of the cache should be 2
[39m
[36mok 351 Cache doesn't contain dictionary1
[39m
[33mok 350 Size of the cache should be 2
[39m
[33mok 351 Cache doesn't contain dictionary1
[39m
[36mok 352 Size of the cache should be 1
ok 353 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
[39m
[32mok 352 Size of the cache should be 1
ok 353 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
[39m
[33mok 352 Size of the cache should be 1
ok 353 Cache doesn't contain beaconStreamAndSecretDictionary2
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-10T11:36:00.128Z - info: Running on ios test: 100. Start and stop ThaliNotificationServer

[36m# 100. Start and stop ThaliNotificationServer
[39m
[32m# 100. Start and stop ThaliNotificationServer
[39m
[33m# 100. Start and stop ThaliNotificationServer
[39m
[33mok 354 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
ok 355 ThaliMobile.StopAdvertisingAndListeningshould be called once
# teardown
[39m
[36mok 354 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
ok 355 ThaliMobile.StopAdvertisingAndListeningshould be called once
# teardown
[39m
[32mok 354 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
[39m
[32mok 355 ThaliMobile.StopAdvertisingAndListeningshould be called once
# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T11:36:00.174Z - info: Running on ios test: 101. Pass an empty array to ThaliNotificationServer.start

[33m# 101. Pass an empty array to ThaliNotificationServer.start
[39m
[36m# 101. Pass an empty array to ThaliNotificationServer.start
[39m
[32m# 101. Pass an empty array to ThaliNotificationServer.start
[39m
[33mok 356 StartUpdateAdvertisingAndListening should not be called
ok 357 ThaliMobile.StopAdvertisingAndListening should be called once
[39m
[32mok 356 StartUpdateAdvertisingAndListening should not be called
ok 357 ThaliMobile.StopAdvertisingAndListening should be called once
[39m
[36mok 356 StartUpdateAdvertisingAndListening should not be called
[39m
[36mok 357 ThaliMobile.StopAdvertisingAndListening should be called once
[39m
[36mok 358 no error
ok 359 should be 204
# teardown
[39m
[33mok 358 no error
ok 359 should be 204
[39m
[33m# teardown
[39m
[32mok 358 no error
ok 359 should be 204
[39m
[32m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T11:36:00.244Z - info: Running on ios test: 102. Pass a string to ThaliNotificationServer.start

[36m# 102. Pass a string to ThaliNotificationServer.start
[39m
[32m# 102. Pass a string to ThaliNotificationServer.start
[39m
[33m# 102. Pass a string to ThaliNotificationServer.start
[39m
[36mok 360 StartUpdateAdvertisingAndListening should not be called
# teardown
[39m
[32mok 360 StartUpdateAdvertisingAndListening should not be called
[39m
[32m# teardown
[39m
[33mok 360 StartUpdateAdvertisingAndListening should not be called
[39m
[33m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T11:36:00.281Z - info: Running on ios test: 103. Pass an empty parameter to ThaliNotificationServer.start

[32m# 103. Pass an empty parameter to ThaliNotificationServer.start
[39m
[36m# 103. Pass an empty parameter to ThaliNotificationServer.start
[39m
[33m# 103. Pass an empty parameter to ThaliNotificationServer.start
[39m
[36mok 361 StartUpdateAdvertisingAndListening should not be called
# teardown
[39m
[32mok 361 StartUpdateAdvertisingAndListening should not be called
[39m
[32m# teardown
[39m
[33mok 361 StartUpdateAdvertisingAndListening should not be called
[39m
[33m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T11:36:00.314Z - info: Running on ios test: 104. Make an HTTP request to /NotificationBeacons

[36m# 104. Make an HTTP request to /NotificationBeacons
[39m
[32m# 104. Make an HTTP request to /NotificationBeacons
[39m
[33m# 104. Make an HTTP request to /NotificationBeacons
[39m
[32mok 362 no error
[39m
[32mok 363 should be 200
[39m
[32mok 364 should be equal
[39m
[32mok 365 should be equal
[39m
[33mok 362 no error
[39m
[33mok 363 should be 200
[39m
[33mok 364 should be equal
[39m
[33mok 365 should be equal
[39m
[33mok 366 (unnamed assert)
[39m
[36mok 362 no error
[39m
[36mok 363 should be 200
[39m
[36mok 364 should be equal
[39m
[36mok 365 should be equal
[39m
[36mok 366 (unnamed assert)
[39m
[33mok 367 no error
[39m
[33mok 368 should be 204
[39m
[33m# teardown
[39m
[32mok 366 (unnamed assert)
[39m
[36mok 367 no error
[39m
[36mok 368 should be 204
[39m
[36m# teardown
[39m
[32mok 367 no error
[39m
[32mok 368 should be 204
[39m
[32m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-10T11:36:00.378Z - info: Running on ios test: 105. Make an HTTP request to /NotificationBeacons (no keys)

[36m# 105. Make an HTTP request to /NotificationBeacons (no keys)
[39m
[32m# 105. Make an HTTP request to /NotificationBeacons (no keys)
[39m
[33m# 105. Make an HTTP request to /NotificationBeacons (no keys)
[39m
[32mok 369 error should be null
[39m
[32mok 370 should be 204
[39m
[36mok 369 error should be null
[39m
[32m# teardown
[39m
[36mok 370 should be 204
[39m
[36m# teardown
[39m
[33mok 369 error should be null
[39m
[33mok 370 should be 204
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-10T11:36:00.421Z - info: Running on ios test: 106. Make an HTTP request to /NotificationBeaconsbefore calling start

[36m# 106. Make an HTTP request to /NotificationBeaconsbefore calling start
[39m
[32m# 106. Make an HTTP request to /NotificationBeaconsbefore calling start
[39m
[33m# 106. Make an HTTP request to /NotificationBeaconsbefore calling start
[39m
[33mok 371 should be 404
[39m
[33m# teardown
[39m
[36mok 371 should be 404
[39m
[32mok 371 should be 404
[39m
[36m# teardown
[39m
[32m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T11:36:00.461Z - info: Running on ios test: 107. #testThaliPeerAction - test getters

[33m# 107. #testThaliPeerAction - test getters
[39m
[32m# 107. #testThaliPeerAction - test getters
[39m
[36m# 107. #testThaliPeerAction - test getters
[39m
[32mok 372 getPeerIdentifier
ok 373 getConnectionType
ok 374 getActionType
ok 375 getActionState
ok 376 getPskIdentity
[39m
[33mok 372 getPeerIdentifier
ok 373 getConnectionType
ok 374 getActionType
ok 375 getActionState
ok 376 getPskIdentity
ok 377 getPskKey
# teardown
[39m
[36mok 372 getPeerIdentifier
ok 373 getConnectionType
[39m
[36mok 374 getActionType
[39m
[32mok 377 getPskKey
[39m
[32m# teardown
[39m
[36mok 375 getActionState
[39m
[36mok 376 getPskIdentity
[39m
[36mok 377 getPskKey
[39m
[36m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T11:36:00.487Z - info: Running on ios test: 108. #testThaliPeerAction - start and kill

[33m# 108. #testThaliPeerAction - start and kill
[39m
[32m# 108. #testThaliPeerAction - start and kill
[39m
[36m# 108. #testThaliPeerAction - start and kill
[39m
[32mok 378 initial state
ok 379 after start
ok 380 after kill
# teardown
[39m
[33mok 378 initial state
ok 379 after start
ok 380 after kill
# teardown
[39m
[36mok 378 initial state
[39m
[36mok 379 after start
[39m
[36mok 380 after kill
[39m
[36m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T11:36:00.510Z - info: Running on ios test: 109. #testThaliPeerAction - double start

[33m# 109. #testThaliPeerAction - double start
[39m
[32m# 109. #testThaliPeerAction - double start
[39m
[36m# 109. #testThaliPeerAction - double start
[39m
[32mok 381 should be equal
# teardown
[39m
[33mok 381 should be equal
# teardown
[39m
[36mok 381 should be equal
[39m
[36m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T11:36:00.536Z - info: Running on ios test: 110. #testThaliPeerAction - start after kill

[32m# 110. #testThaliPeerAction - start after kill
[39m
[33m# 110. #testThaliPeerAction - start after kill
[39m
[36m# 110. #testThaliPeerAction - start after kill
[39m
[32mok 382 clean kill
[39m
[32mok 383 should be equal
[39m
[32m# teardown
[39m
[33mok 382 clean kill
[39m
[33mok 383 should be equal
[39m
[33m# teardown
[39m
[36mok 382 clean kill
[39m
[36mok 383 should be equal
[39m
[36m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-10T11:36:00.561Z - info: Running on ios test: 111. #testThaliPeerAction - make sure ids are unique

[32m# 111. #testThaliPeerAction - make sure ids are unique
[39m
[33m# 111. #testThaliPeerAction - make sure ids are unique
[39m
[36m# 111. #testThaliPeerAction - make sure ids are unique
[39m
[32mok 384 should not be equal
[39m
[32m# teardown
[39m
[33mok 384 should not be equal
[39m
[33m# teardown
[39m
[36mok 384 should not be equal
[39m
[36m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T11:36:00.584Z - info: Running on ios test: 112. Test PeerConnectionInformation basics

[32m# 112. Test PeerConnectionInformation basics
[39m
[33m# 112. Test PeerConnectionInformation basics
[39m
[36m# 112. Test PeerConnectionInformation basics
[39m
[32mok 385 connection type works
[39m
[32mok 386 getHostAddress works
[39m
[33mok 385 connection type works
[39m
[32mok 387 getPortNumber works
ok 388 getSuggestedTCPTimeout works
[39m
[32m# teardown
[39m
[33mok 386 getHostAddress works
ok 387 getPortNumber works
[39m
[33mok 388 getSuggestedTCPTimeout works
[39m
[33m# teardown
[39m
[36mok 385 connection type works
ok 386 getHostAddress works
ok 387 getPortNumber works
ok 388 getSuggestedTCPTimeout works
[39m
[36m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T11:36:00.610Z - info: Running on ios test: 113. Test PeerDictionary basic functionality

[32m# 113. Test PeerDictionary basic functionality
[39m
[33m# 113. Test PeerDictionary basic functionality
[39m
[36m# 113. Test PeerDictionary basic functionality
[39m
[33mok 389 Entry counter must be 1
[39m
[33mok 390 Size must be 1
[39m
[33mok 391 Entry counter must be 2
ok 392 Size must be 2
[39m
[33mok 393 Entry2 should not be found
ok 394 Size must be 1
[39m
[33mok 395 Size must be 0
[39m
[33m# teardown
[39m
[32mok 389 Entry counter must be 1
[39m
[32mok 390 Size must be 1
[39m
[32mok 391 Entry counter must be 2
ok 392 Size must be 2
[39m
[32mok 393 Entry2 should not be found
[39m
[32mok 394 Size must be 1
[39m
[32mok 395 Size must be 0
[39m
[32m# teardown
[39m
[36mok 389 Entry counter must be 1
[39m
[36mok 390 Size must be 1
[39m
[36mok 391 Entry counter must be 2
[39m
[36mok 392 Size must be 2
[39m
[36mok 393 Entry2 should not be found
[39m
[36mok 394 Size must be 1
[39m
[36mok 395 Size must be 0
[39m
[36m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T11:36:00.639Z - info: Running on ios test: 114. Test PeerDictionary with multiple entries.

[33m# 114. Test PeerDictionary with multiple entries.
[39m
[32m# 114. Test PeerDictionary with multiple entries.
[39m
[36m# 114. Test PeerDictionary with multiple entries.
[39m
[32mok 396 Size must be100
[39m
[32mok 397 Entries between 20 and MAXSIZE + 20 should exist
[39m
[33mok 396 Size must be100
[39m
[33mok 397 Entries between 20 and MAXSIZE + 20 should exist
[39m
[36mok 396 Size must be100
ok 397 Entries between 20 and MAXSIZE + 20 should exist
[39m
[32mok 398 WAITING state entry should not be removed
# teardown
[39m
[33mok 398 WAITING state entry should not be removed
# teardown
[39m
[36mok 398 WAITING state entry should not be removed
# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T11:36:00.918Z - info: Running on ios test: 115. RESOLVED entries are removed before WAITING state entry.

[32m# 115. RESOLVED entries are removed before WAITING state entry.
[39m
[33m# 115. RESOLVED entries are removed before WAITING state entry.
[39m
[36m# 115. RESOLVED entries are removed before WAITING state entry.
[39m
[33mok 399 Entries between 6 and MAXSIZE + 4 should exist
[39m
[33mok 400 Size should be MAXSIZE
[39m
[33mok 401 Size should be MAXSIZE+6
[39m
[33m# teardown
[39m
[32mok 399 Entries between 6 and MAXSIZE + 4 should exist
[39m
[32mok 400 Size should be MAXSIZE
[39m
[32mok 401 Size should be MAXSIZE+6
[39m
[32m# teardown
[39m
[36mok 399 Entries between 6 and MAXSIZE + 4 should exist
[39m
[36mok 400 Size should be MAXSIZE
ok 401 Size should be MAXSIZE+6
[39m
[36m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T11:36:01.129Z - info: Running on ios test: 116. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

[33m# 116. WAITING entries are removed before CONTROLLED_BY_POOL state entry.
[39m
[32m# 116. WAITING entries are removed before CONTROLLED_BY_POOL state entry.
[39m
[36m# 116. WAITING entries are removed before CONTROLLED_BY_POOL state entry.
[39m
[32mok 402 WAITING state entry should not be removed
[39m
[32mok 403 Waiting entries between 6 and MAXSIZE + 4 should exist
[39m
[32mok 404 Size should be MAXSIZE
[39m
[32mok 405 entryCounter should be MAXSIZE+6
[39m
[32m# teardown
[39m
[33mok 402 WAITING state entry should not be removed
ok 403 Waiting entries between 6 and MAXSIZE + 4 should exist
[39m
[33mok 404 Size should be MAXSIZE
ok 405 entryCounter should be MAXSIZE+6
# teardown
[39m
[36mok 402 WAITING state entry should not be removed
[39m
[36mok 403 Waiting entries between 6 and MAXSIZE + 4 should exist
[39m
[36mok 404 Size should be MAXSIZE
[39m
[36mok 405 entryCounter should be MAXSIZE+6
# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T11:36:01.337Z - info: Running on ios test: 117. When CONTROLLED_BY_POOL entry is removed and kill is called.

[32m# 117. When CONTROLLED_BY_POOL entry is removed and kill is called.
[39m
[33m# 117. When CONTROLLED_BY_POOL entry is removed and kill is called.
[39m
[36m# 117. When CONTROLLED_BY_POOL entry is removed and kill is called.
[39m
[33mok 406 Kill should be called once
ok 407 Size should be 100
# teardown
[39m
[32mok 406 Kill should be called once
ok 407 Size should be 100
# teardown
[39m
[36mok 406 Kill should be called once
[39m
[36mok 407 Size should be 100
[39m
[36m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T11:36:01.454Z - info: Running on ios test: 118. #ThaliPeerPoolInterface - bad enqueues

[32m# 118. #ThaliPeerPoolInterface - bad enqueues
[39m
[33m# 118. #ThaliPeerPoolInterface - bad enqueues
[39m
[36m# 118. #ThaliPeerPoolInterface - bad enqueues
[39m
[32mok 408 null arg
ok 409 wrong arg type
ok 410 wrong state
# teardown
[39m
[33mok 408 null arg
[39m
[33mok 409 wrong arg type
[39m
[33mok 410 wrong state
[39m
[33m# teardown
[39m
[36mok 408 null arg
ok 409 wrong arg type
ok 410 wrong state
[39m
[36m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T11:36:01.476Z - info: Running on ios test: 119. #ThaliPeerPoolInterface - do not allow same object type

[32m# 119. #ThaliPeerPoolInterface - do not allow same object type
[39m
[33m# 119. #ThaliPeerPoolInterface - do not allow same object type
[39m
[36m# 119. #ThaliPeerPoolInterface - do not allow same object type
[39m
[32mok 411 good enqueue
[39m
[32mok 412 should be equal
[39m
[32m# teardown
[39m
[36mok 411 good enqueue
ok 412 should be equal
# teardown
[39m
[33mok 411 good enqueue
ok 412 should be equal
# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T11:36:01.498Z - info: Running on ios test: 120. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

[32m# 120. #ThaliPeerPoolInterface - make sure we catch kill and dequeue
[39m
[33m# 120. #ThaliPeerPoolInterface - make sure we catch kill and dequeue
[39m
[36m# 120. #ThaliPeerPoolInterface - make sure we catch kill and dequeue
[39m
[32mok 413 good enqueue
ok 414 2nd good enqueue
ok 415 we are in the pool
ok 416 We are out of the pool
ok 417 Action was killed
ok 418 The original kill was called too
ok 419 second item is still in queue
# teardown
[39m
[33mok 413 good enqueue
ok 414 2nd good enqueue
ok 415 we are in the pool
[39m
[33mok 416 We are out of the pool
ok 417 Action was killed
ok 418 The original kill was called too
ok 419 second item is still in queue
# teardown
[39m
[36mok 413 good enqueue
[39m
[36mok 414 2nd good enqueue
[39m
[36mok 415 we are in the pool
[39m
[36mok 416 We are out of the pool
ok 417 Action was killed
ok 418 The original kill was called too
ok 419 second item is still in queue
[39m
[36m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T11:36:01.525Z - info: Running on ios test: 121. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent

[36m# 121. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
[39m
[32m# 121. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
[39m
[33m# 121. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
[39m
[33mok 420 good enqueue
[39m
[32mok 420 good enqueue
ok 421 first kill
[39m
[32mok 422 second NOOP kill
[39m
[32m# teardown
[39m
[33mok 421 first kill
[39m
[33mok 422 second NOOP kill
[39m
[33m# teardown
[39m
[36mok 420 good enqueue
ok 421 first kill
ok 422 second NOOP kill
# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T11:36:01.551Z - info: Running on ios test: 122. Make sure peerDictionaryKey is reasonable

[32m# 122. Make sure peerDictionaryKey is reasonable
[39m
[33m# 122. Make sure peerDictionaryKey is reasonable
[39m
[36m# 122. Make sure peerDictionaryKey is reasonable
[39m
[32mok 423 equal keys
ok 424 not equal connection type
ok 425 same connection type, different buffer
# teardown
[39m
[33mok 423 equal keys
ok 424 not equal connection type
ok 425 same connection type, different buffer
# teardown
[39m
[36mok 423 equal keys
[39m
[36mok 424 not equal connection type
ok 425 same connection type, different buffer
# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T11:36:01.573Z - info: Running on ios test: 123. Make sure start works

[32m# 123. Make sure start works
[39m
[33m# 123. Make sure start works
[39m
[36m# 123. Make sure start works
[39m
[33mok 426 First start and on called correctly
# teardown
[39m
[32mok 426 First start and on called correctly
[39m
[32m# teardown
[39m
[36mok 426 First start and on called correctly
# teardown
[39m
[33m# setup
[39m
[32m# setup
[39m
[36m# setup
[39m
2016-08-10T11:36:01.603Z - info: Running on ios test: 124. Make sure stop works

[32m# 124. Make sure stop works
[39m
[33m# 124. Make sure stop works
[39m
[36m# 124. Make sure stop works
[39m
[32mok 427 second cleared dictionary
ok 428 First start and on called correctly
ok 429 First stop and removeListener called correctly
ok 430 first action kill called
ok 431 second action kill called
ok 432 first cleared dictionary
ok 433 second cleared dictionary
# teardown
[39m
[33mok 427 second cleared dictionary
[39m
[36mok 427 second cleared dictionary
ok 428 First start and on called correctly
[39m
[33mok 428 First start and on called correctly
[39m
[36mok 429 First stop and removeListener called correctly
[39m
[36mok 430 first action kill called
[39m
[36mok 431 second action kill called
[39m
[33mok 429 First stop and removeListener called correctly
ok 430 first action kill called
[39m
[33mok 431 second action kill called
[39m
[33mok 432 first cleared dictionary
[39m
[33mok 433 second cleared dictionary
[39m
[36mok 432 first cleared dictionary
[39m
[33m# teardown
[39m
[36mok 433 second cleared dictionary
[39m
[36m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T11:36:01.639Z - info: Running on ios test: 125. Simple peer event

[36m# 125. Simple peer event
[39m
[32m# 125. Simple peer event
[39m
[33m# 125. Simple peer event
[39m
[32mok 434 listener has been set
[39m
[33mok 434 listener has been set
[39m
[32mok 435 peer dictionary has expected number of entries
[39m
[32mok 436 Dictionary and pool have same action
[39m
[32mok 437 ads match
[39m
[32mok 438 PouchDB matches
[39m
[32mok 439 DB Names match
[39m
[32mok 440 public keys match
[39m
[33mok 435 peer dictionary has expected number of entries
[39m
[33mok 436 Dictionary and pool have same action
[39m
[33mok 437 ads match
[39m
[33mok 438 PouchDB matches
[39m
[33mok 439 DB Names match
[39m
[33mok 440 public keys match
[39m
[32mok 441 peer dictionary has expected number of entries
[39m
[32mok 442 Dictionary and pool have same action
[39m
[32mok 443 ads match
[39m
[32mok 444 PouchDB matches
[39m
[32mok 445 DB Names match
[39m
[32mok 446 public keys match
[39m
[33mok 441 peer dictionary has expected number of entries
[39m
[32mok 447 start called once
[39m
[33mok 442 Dictionary and pool have same action
[39m
[32mok 448 kill never called
ok 449 One entry left
ok 450 Dictionary and pool have same action
[39m
[33mok 443 ads match
[39m
[33mok 444 PouchDB matches
[39m
[32mok 451 Start never called
[39m
[32mok 452 Kill called once
[39m
[32mok 453 no entries left
[39m
[33mok 445 DB Names match
[39m
[33mok 446 public keys match
[39m
[33mok 447 start called once
[39m
[33mok 448 kill never called
[39m
[33mok 449 One entry left
[39m
[33mok 450 Dictionary and pool have same action
[39m
[32mok 454 Third action is dead
[39m
[32mok 455 peer dictionary has expected number of entries
[39m
[32mok 456 Dictionary and pool have same action
[39m
[32mok 457 ads match
ok 458 PouchDB matches
ok 459 DB Names match
[39m
[32mok 460 public keys match
[39m
[32m# teardown
[39m
[33mok 451 Start never called
[39m
[33mok 452 Kill called once
[39m
[33mok 453 no entries left
[39m
[36mok 434 listener has been set
[39m
[36mok 435 peer dictionary has expected number of entries
[39m
[36mok 436 Dictionary and pool have same action
[39m
[36mok 437 ads match
[39m
[36mok 438 PouchDB matches
[39m
[36mok 439 DB Names match
[39m
[36mok 440 public keys match
[39m
[33mok 454 Third action is dead
[39m
[33mok 455 peer dictionary has expected number of entries
[39m
[33mok 456 Dictionary and pool have same action
[39m
[33mok 457 ads match
ok 458 PouchDB matches
[39m
[33mok 459 DB Names match
[39m
[33mok 460 public keys match
[39m
[33m# teardown
[39m
[36mok 441 peer dictionary has expected number of entries
[39m
[36mok 442 Dictionary and pool have same action
[39m
[36mok 443 ads match
ok 444 PouchDB matches
[39m
[36mok 445 DB Names match
[39m
[36mok 446 public keys match
[39m
[36mok 447 start called once
[39m
[36mok 448 kill never called
[39m
[36mok 449 One entry left
[39m
[36mok 450 Dictionary and pool have same action
[39m
[36mok 451 Start never called
[39m
[36mok 452 Kill called once
[39m
[36mok 453 no entries left
[39m
[36mok 454 Third action is dead
[39m
[36mok 455 peer dictionary has expected number of entries
[39m
[36mok 456 Dictionary and pool have same action
[39m
[36mok 457 ads match
ok 458 PouchDB matches
[39m
[36mok 459 DB Names match
[39m
[36mok 460 public keys match
[39m
[36m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T11:36:01.690Z - info: Running on ios test: 126. Coordinated pull replication from notification test

[32m# 126. Coordinated pull replication from notification test
[39m
[33m# 126. Coordinated pull replication from notification test
[39m
[36m# 126. Coordinated pull replication from notification test
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51367
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51372
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51376
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[36mDEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
[39m
[33mDEBUG createPeerListener: pleaseConnect= false
[39m
[32mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createPeerListener: first connection
[39m
[36mDEBUG createPeerListener: first connection
[39m
[33mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[36mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
[39m
[36mDEBUG createNativeListener: new mux
[39m
[36mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[36mDEBUG wifiBasedNativeMock: proxy socket connected
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG thaliReplicationPeerAction: Replication resumed
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[32mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createPeerListener: forward connection
[39m
[33mDEBUG createPeerListener: forward connection
[39m
[36mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG thaliReplicationPeerAction: Replication resumed
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG thaliReplicationPeerAction: Replication resumed
[39m
[36mDEBUG createNativeListener: 
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: 
DEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG thaliReplicationPeerAction: Replication resumed
[39m
[32mok 461 all tests passed
[39m
[32m# teardown
[39m
[33mDEBUG createNativeListener: 
DEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: 
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[32mDEBUG localSeqManager: Got an error trying to update seq {"onPut":true}
DEBUG thaliReplicationPeerAction: Got error in update, waiting for main loop to detect and handle - Error: Stop Called
[39m
[36mDEBUG createNativeListener: 
DEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: 
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: 
[39m
[33mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: 
DEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG thaliReplicationPeerAction: Replication resumed
[39m
[33mDEBUG thaliReplicationPeerAction: Replication resumed
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG thaliReplicationPeerAction: Got paused with undefined
[39m
[33mDEBUG thaliReplicationPeerAction: Got paused with undefined
[39m
[33mDEBUG createNativeListener: new stream: 
[39m
[33mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG createNativeListener: new stream: 
[39m
[36mDEBUG createNativeListener: new outgoing socket
[39m
[36mDEBUG thaliReplicationPeerAction: Got paused with undefined
[39m
[33mDEBUG thaliReplicationPeerAction: Got paused with undefined
[39m
[33mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[36mDEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
[39m
[33mDEBUG createPeerListener: first connection
[39m
[32mDEBUG wifiBasedNativeMock: proxy socket connected
[39m
[32mDEBUG createNativeListener: new incoming socket
[39m
[32mDEBUG createNativeListener: creating incoming mux
[39m
[32mDEBUG createNativeListener: new mux
[39m
[36mDEBUG createPeerListener: first connection
[39m
[32mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG wifiBasedNativeMock: proxy socket connected
[39m
[33mDEBUG thaliReplicationPeerAction: Replication resumed
[39m
[36mDEBUG thaliReplicationPeerAction: Replication resumed
[39m
[33mok 461 all tests passed
[39m
[33mDEBUG localSeqManager: Got an error trying to update seq {"onPut":true}
DEBUG thaliReplicationPeerAction: Got error in update, waiting for main loop to detect and handle - Error: Stop Called
[39m
[33m# teardown
[39m
[36mDEBUG thaliReplicationPeerAction: Replication resumed
[39m
[36mDEBUG createNativeListener: 
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG thaliReplicationPeerAction: Replication resumed
[39m
[36mok 461 all tests passed
[39m
[36mDEBUG localSeqManager: Got an error trying to update seq {"onPut":true}
[39m
[36mDEBUG thaliReplicationPeerAction: Got error in update, waiting for main loop to detect and handle - Error: Stop Called
[39m
[36m# teardown
[39m
[32mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[32mDEBUG createNativeListener: mux close
DEBUG createNativeListener: mux close
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[32mDEBUG createNativeListener: incoming socket close
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[33mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[33mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[32m# setup
[39m
[33mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: stream close:
[39m
[33mDEBUG createNativeListener: mux close
[39m
[33mDEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
WARN createPeerListener: 
DEBUG createPeerListener: failedConnection
WARN createPeerListener: 
DEBUG createPeerListener: failedConnection
[39m
[33mDEBUG createPeerListener: failed incoming connection because of mux promise failure - Error: Unspecified Error with Radio infrastructure
[39m
[33mDEBUG createPeerListener: failed incoming connection because of mux promise failure - Error: Unspecified Error with Radio infrastructure
[39m
[33mDEBUG thaliPeerPoolDefault: Got err Error: Could not establish TCP connection
[39m
[33m# setup
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
[39m
[36mINFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
[39m
[36mDEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: stream close:
[39m
[36mDEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[36mDEBUG createNativeListener: incoming socket close
[39m
[36mWARN createPeerListener: 
[39m
[36mDEBUG createPeerListener: failedConnection
[39m
[36mWARN createPeerListener: 
DEBUG createPeerListener: failedConnection
DEBUG createPeerListener: failed incoming connection because of mux promise failure - Error: Unspecified Error with Radio infrastructure
DEBUG createPeerListener: failed incoming connection because of mux promise failure - Error: Unspecified Error with Radio infrastructure
[39m
[36mDEBUG thaliReplicationPeerAction: Got error on replication - Error: connect ECONNREFUSED
[39m
[36m# setup
[39m
2016-08-10T11:36:02.376Z - info: Running on ios test: 127. Server is not there

[33m# 127. Server is not there
[39m
[32m# 127. Server is not there
[39m
[36m# 127. Server is not there
[39m
[32mDEBUG thaliReplicationPeerAction: Got error on replication - Error: connect ECONNREFUSED
[39m
[32mok 462 right error
[39m
[32m# teardown
[39m
[33mDEBUG thaliReplicationPeerAction: Got error on replication - Error: connect ECONNREFUSED
[39m
[33mok 462 right error
[39m
[33m# teardown
[39m
[36mDEBUG thaliReplicationPeerAction: Got error on replication - Error: connect ECONNREFUSED
[39m
[36mok 462 right error
[39m
[36m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T11:36:02.418Z - info: Running on ios test: 128. Server accepts & closes connection

[32m# 128. Server accepts & closes connection
[39m
[33m# 128. Server accepts & closes connection
[39m
[36m# 128. Server accepts & closes connection
[39m
[32mDEBUG thaliReplicationPeerAction: Got error on replication - Error: socket hang up
[39m
[32mok 463 right error
[39m
[33mDEBUG thaliReplicationPeerAction: Got error on replication - Error: socket hang up
[39m
[33mok 463 right error
[39m
[33m# teardown
[39m
[32m# teardown
[39m
[36mDEBUG thaliReplicationPeerAction: Got error on replication - Error: socket hang up
[39m
[36mok 463 right error
[39m
[36m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T11:36:02.463Z - info: Running on ios test: 129. Server always returns 500

[32m# 129. Server always returns 500
[39m
[36m# 129. Server always returns 500
[39m
[33m# 129. Server always returns 500
[39m
[32mDEBUG thaliReplicationPeerAction: Got error on replication - 
[39m
[32mok 464 Got error as expected
# teardown
[39m
[33mDEBUG thaliReplicationPeerAction: Got error on replication - 
[39m
[33mok 464 Got error as expected
[39m
[33m# teardown
[39m
[36mDEBUG thaliReplicationPeerAction: Got error on replication - 
[39m
[36mok 464 Got error as expected
[39m
[36m# teardown
[39m
[33m# setup
[39m
[32m# setup
[39m
[36m# setup
[39m
2016-08-10T11:36:02.507Z - info: Running on ios test: 130. Server always returns 401

[33m# 130. Server always returns 401
[39m
[32m# 130. Server always returns 401
[39m
[36m# 130. Server always returns 401
[39m
[33mDEBUG thaliPeerPoolDefault: Got err Error: Could not establish TCP connection
[39m
[33mDEBUG thaliReplicationPeerAction: Got error on replication - 
ok 465 Got error as expected
# teardown
[39m
[32mDEBUG thaliReplicationPeerAction: Got error on replication - 
ok 465 Got error as expected
[39m
[36mDEBUG thaliReplicationPeerAction: Got error on replication - 
ok 465 Got error as expected
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
2016-08-10T11:36:02.552Z - info: Running on ios test: 131. Server always returns 403

[33m# 131. Server always returns 403
[39m
[36m# 131. Server always returns 403
[39m
[32m# 131. Server always returns 403
[39m
[33mDEBUG thaliReplicationPeerAction: Got error on replication - 
ok 466 Got error as expected
[39m
[36mDEBUG thaliReplicationPeerAction: Got error on replication - 
ok 466 Got error as expected
[39m
[33m# teardown
[39m
[36m# teardown
[39m
[32mDEBUG thaliReplicationPeerAction: Got error on replication - 
[39m
[32mok 466 Got error as expected
[39m
[32m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T11:36:02.598Z - info: Running on ios test: 132. Make sure docs replicate

[33m# 132. Make sure docs replicate
[39m
[36m# 132. Make sure docs replicate
[39m
[32m# 132. Make sure docs replicate
[39m
[33mDEBUG thaliReplicationPeerAction: Replication resumed
[39m
[33mDEBUG thaliReplicationPeerAction: Got paused with undefined
[39m
[32mDEBUG thaliReplicationPeerAction: Replication resumed
[39m
[36mDEBUG thaliReplicationPeerAction: Replication resumed
[39m
[33mDEBUG thaliPeerPoolDefault: Got err Error: Could not establish TCP connection
[39m
[36mDEBUG thaliReplicationPeerAction: Got paused with undefined
[39m
[32mDEBUG thaliReplicationPeerAction: Got paused with undefined
[39m
[33mok 467 should be equal
[39m
[33mok 468 All tests passed!
[39m
[33m# teardown
[39m
[36mok 467 should be equal
[39m
[36mok 468 All tests passed!
[39m
[36m# teardown
[39m
[32mok 467 should be equal
[39m
[32mok 468 All tests passed!
[39m
[32m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T11:36:03.136Z - info: Running on ios test: 133. Do nothing and make sure we time out

[33m# 133. Do nothing and make sure we time out
[39m
[36m# 133. Do nothing and make sure we time out
[39m
[32m# 133. Do nothing and make sure we time out
[39m
[33mDEBUG thaliReplicationPeerAction: Got paused with undefined
[39m
[36mDEBUG thaliReplicationPeerAction: Got paused with undefined
[39m
[32mDEBUG thaliReplicationPeerAction: Got paused with undefined
[39m
[33mDEBUG thaliPeerPoolDefault: Got err Error: Could not establish TCP connection
[39m
[33mDEBUG thaliPeerPoolDefault: Got err Error: Could not establish TCP connection
[39m
[33mok 469 action should be killed
[39m
[33mok 470 Error should be timed out
[39m
[36mok 469 action should be killed
ok 470 Error should be timed out
[39m
[33mok 471 No doc found
[39m
[33m# teardown
[39m
[36mok 471 No doc found
[39m
[36m# teardown
[39m
[32mok 469 action should be killed
[39m
[32mok 470 Error should be timed out
[39m
[32mok 471 No doc found
[39m
[32m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T11:36:05.196Z - info: Running on ios test: 134. Do something and make sure we time out

[36m# 134. Do something and make sure we time out
[39m
[32m# 134. Do something and make sure we time out
[39m
[33m# 134. Do something and make sure we time out
[39m
[32mDEBUG thaliReplicationPeerAction: Replication resumed
[39m
[36mDEBUG thaliReplicationPeerAction: Replication resumed
[39m
[33mDEBUG thaliReplicationPeerAction: Replication resumed
[39m
[32mDEBUG thaliReplicationPeerAction: Got paused with undefined
[39m
[33mDEBUG thaliReplicationPeerAction: Got paused with undefined
[39m
[36mDEBUG thaliReplicationPeerAction: Got paused with undefined
[39m
[32mok 472 should be equal
[39m
[33mok 472 should be equal
[39m
[36mok 472 should be equal
[39m
[33mDEBUG thaliPeerPoolDefault: Got err Error: Could not establish TCP connection
[39m
[32mok 473 action should be killed
[39m
[32mok 474 Error should be timed out
[39m
[32m# teardown
[39m
[33mok 473 action should be killed
ok 474 Error should be timed out
[39m
[33m# teardown
[39m
[36mok 473 action should be killed
[39m
[36mok 474 Error should be timed out
# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T11:36:07.529Z - info: Running on ios test: 135. Start replicating and then catch error when server goes

[36m# 135. Start replicating and then catch error when server goes
[39m
[33m# 135. Start replicating and then catch error when server goes
[39m
[32m# 135. Start replicating and then catch error when server goes
[39m
[36mok 475 socket hung up
[39m
[32mok 475 socket hung up
[39m
[36m# teardown
[39m
[32m# teardown
[39m
[33mok 475 socket hung up
[39m
[33m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T11:36:07.694Z - info: Running on ios test: 136. compareBufferArrays

[33m# 136. compareBufferArrays
[39m
[32m# 136. compareBufferArrays
[39m
[36m# 136. compareBufferArrays
[39m
[33mok 476 should throw
[39m
[33mok 477 should throw
[39m
[33mok 478 (unnamed assert)
[39m
[33mok 479 (unnamed assert)
[39m
[33mok 480 (unnamed assert)
[39m
[33mok 481 (unnamed assert)
[39m
[33mok 482 (unnamed assert)
[39m
[33m# teardown
[39m
[32mok 476 should throw
[39m
[32mok 477 should throw
[39m
[32mok 478 (unnamed assert)
[39m
[32mok 479 (unnamed assert)
[39m
[32mok 480 (unnamed assert)
ok 481 (unnamed assert)
[39m
[32mok 482 (unnamed assert)
[39m
[32m# teardown
[39m
[36mok 476 should throw
[39m
[36mok 477 should throw
ok 478 (unnamed assert)
[39m
[36mok 479 (unnamed assert)
[39m
[36mok 480 (unnamed assert)
ok 481 (unnamed assert)
[39m
[36mok 482 (unnamed assert)
[39m
[36m# teardown
[39m
[33m# setup
[39m
[32m# setup
[39m
[36m# setup
[39m
2016-08-10T11:36:07.723Z - info: Running on ios test: 137. Call start twice and get error

[32m# 137. Call start twice and get error
[39m
[33m# 137. Call start twice and get error
[39m
[36m# 137. Call start twice and get error
[39m
[33mok 483 should throw
[39m
[32mok 483 should throw
[39m
[33m# teardown
[39m
[32m# teardown
[39m
[36mok 483 should throw
[39m
[36m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T11:36:07.746Z - info: Running on ios test: 138. Start and make sure it runs

[33m# 138. Start and make sure it runs
[39m
[32m# 138. Start and make sure it runs
[39m
[36m# 138. Start and make sure it runs
[39m
[36m# teardown
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
2016-08-10T11:36:07.767Z - info: Running on ios test: 139. Make sure getTimeWhenRun is right after start

[32m# 139. Make sure getTimeWhenRun is right after start
[39m
[33m# 139. Make sure getTimeWhenRun is right after start
[39m
[36m# 139. Make sure getTimeWhenRun is right after start
[39m
[32mok 484 (unnamed assert)
[39m
[32m# teardown
[39m
[33mok 484 (unnamed assert)
[39m
[33m# teardown
[39m
[36mok 484 (unnamed assert)
[39m
[36m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T11:36:07.787Z - info: Running on ios test: 140. Make sure getTimeWhenRun is -1 after function is called

[32m# 140. Make sure getTimeWhenRun is -1 after function is called
[39m
[33m# 140. Make sure getTimeWhenRun is -1 after function is called
[39m
[36m# 140. Make sure getTimeWhenRun is -1 after function is called
[39m
[32mok 485 should be equal
[39m
[32m# teardown
[39m
[36mok 485 should be equal
[39m
[33mok 485 should be equal
[39m
[36m# teardown
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-10T11:36:07.808Z - info: Running on ios test: 141. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

[32m# 141. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
[39m
[33m# 141. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
[39m
[36m# 141. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
[39m
[32mok 486 should be equal
[39m
[36mok 486 should be equal
ok 487 should be equal
[39m
[32mok 487 should be equal
[39m
[32mok 488 should throw
[39m
[32m# teardown
[39m
[36mok 488 should throw
[39m
[36m# teardown
[39m
[33mok 486 should be equal
[39m
[33mok 487 should be equal
[39m
[33mok 488 should throw
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-10T11:36:07.830Z - info: Running on ios test: 142. Test TransientState

[32m# 142. Test TransientState
[39m
[33m# 142. Test TransientState
[39m
[36m# 142. Test TransientState
[39m
[32mok 489 should throw
[39m
[32mok 490 should throw
[39m
[32mok 491 should be equal
[39m
[32mok 492 should be equal
ok 493 should be equal
[39m
[32mok 494 should be equal
[39m
[32mok 495 (unnamed assert)
[39m
[32mok 496 (unnamed assert)
[39m
[32m# teardown
[39m
[33mok 489 should throw
[39m
[33mok 490 should throw
[39m
[33mok 491 should be equal
ok 492 should be equal
[39m
[33mok 493 should be equal
[39m
[33mok 494 should be equal
[39m
[36mok 489 should throw
[39m
[36mok 490 should throw
[39m
[36mok 491 should be equal
ok 492 should be equal
ok 493 should be equal
ok 494 should be equal
ok 495 (unnamed assert)
ok 496 (unnamed assert)
# teardown
[39m
[33mok 495 (unnamed assert)
ok 496 (unnamed assert)
# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-10T11:36:07.856Z - info: Running on ios test: 143. No peers and empty database

[36m# 143. No peers and empty database
[39m
[32m# 143. No peers and empty database
[39m
[33m# 143. No peers and empty database
[39m
[32mok 497 verify failed
[39m
[32mok 498 constructor called once
[39m
[32mok 499 constructor called with right args
[39m
[32mok 500 match start arg
[39m
[32mok 501 start called once
ok 502 stop called once
[39m
[32mok 503 stop after start
[39m
[32m# teardown
[39m
[36mok 497 verify failed
ok 498 constructor called once
ok 499 constructor called with right args
ok 500 match start arg
ok 501 start called once
ok 502 stop called once
ok 503 stop after start
[39m
[36m# teardown
[39m
[33mok 497 verify failed
ok 498 constructor called once
ok 499 constructor called with right args
ok 500 match start arg
ok 501 start called once
ok 502 stop called once
ok 503 stop after start
[39m
[33m# teardown
[39m
[33m# setup
[39m
[32m# setup
[39m
[36m# setup
[39m
2016-08-10T11:36:07.898Z - info: Running on ios test: 144. One peer and empty DB

[33m# 144. One peer and empty DB
[39m
[32m# 144. One peer and empty DB
[39m
[36m# 144. One peer and empty DB
[39m
[33mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 504 verify failed
ok 505 constructor called once
ok 506 constructor called with right args
ok 507 match start arg
ok 508 start called once
ok 509 stop called once
ok 510 stop after start
[39m
[33m# teardown
[39m
[32mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 504 verify failed
ok 505 constructor called once
ok 506 constructor called with right args
ok 507 match start arg
ok 508 start called once
ok 509 stop called once
ok 510 stop after start
[39m
[32m# teardown
[39m
[36mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[36mok 504 verify failed
ok 505 constructor called once
ok 506 constructor called with right args
[39m
[36mok 507 match start arg
[39m
[36mok 508 start called once
ok 509 stop called once
[39m
[36mok 510 stop after start
[39m
[36m# teardown
[39m
[33m# setup
[39m
[32m# setup
[39m
[36m# setup
[39m
2016-08-10T11:36:07.943Z - info: Running on ios test: 145. One peer with _Local set behind current seq

[33m# 145. One peer with _Local set behind current seq
[39m
[32m# 145. One peer with _Local set behind current seq
[39m
[36m# 145. One peer with _Local set behind current seq
[39m
[33mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 511 verify failed
ok 512 constructor called once
ok 513 constructor called with right args
ok 514 match start arg
ok 515 start called once
ok 516 stop called once
ok 517 stop after start
# teardown
[39m
[32mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 511 verify failed
ok 512 constructor called once
ok 513 constructor called with right args
ok 514 match start arg
ok 515 start called once
ok 516 stop called once
ok 517 stop after start
# teardown
[39m
[36mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[36mok 511 verify failed
ok 512 constructor called once
[39m
[36mok 513 constructor called with right args
[39m
[36mok 514 match start arg
ok 515 start called once
[39m
[36mok 516 stop called once
ok 517 stop after start
[39m
[36m# teardown
[39m
[33m# setup
[39m
[32m# setup
[39m
[36m# setup
[39m
2016-08-10T11:36:07.996Z - info: Running on ios test: 146. One peer with _Local set equal to current seq

[33m# 146. One peer with _Local set equal to current seq
[39m
[32m# 146. One peer with _Local set equal to current seq
[39m
[36m# 146. One peer with _Local set equal to current seq
[39m
[32mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 518 verify failed
ok 519 constructor called once
ok 520 constructor called with right args
ok 521 match start arg
ok 522 start called once
ok 523 stop called once
ok 524 stop after start
# teardown
[39m
[36mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 518 verify failed
ok 519 constructor called once
ok 520 constructor called with right args
ok 521 match start arg
ok 522 start called once
ok 523 stop called once
ok 524 stop after start
# teardown
[39m
[33mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[33mok 518 verify failed
ok 519 constructor called once
[39m
[33mok 520 constructor called with right args
ok 521 match start arg
[39m
[33mok 522 start called once
ok 523 stop called once
[39m
[33mok 524 stop after start
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-10T11:36:08.041Z - info: Running on ios test: 147. One peer with _Local set ahead of current seq (and no this should not happen)

[32m# 147. One peer with _Local set ahead of current seq (and no this should not happen)
[39m
[33m# 147. One peer with _Local set ahead of current seq (and no this should not happen)
[39m
[36m# 147. One peer with _Local set ahead of current seq (and no this should not happen)
[39m
[32mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 525 verify failed
ok 526 constructor called once
ok 527 constructor called with right args
ok 528 match start arg
ok 529 start called once
ok 530 stop called once
ok 531 stop after start
# teardown
[39m
[33mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 525 verify failed
ok 526 constructor called once
ok 527 constructor called with right args
ok 528 match start arg
ok 529 start called once
ok 530 stop called once
ok 531 stop after start
[39m
[33m# teardown
[39m
[36mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 525 verify failed
ok 526 constructor called once
ok 527 constructor called with right args
ok 528 match start arg
ok 529 start called once
ok 530 stop called once
ok 531 stop after start
[39m
[36m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-10T11:36:08.085Z - info: Running on ios test: 148. Three peers, one not in DB, one behind and one ahead

[36m# 148. Three peers, one not in DB, one behind and one ahead
[39m
[32m# 148. Three peers, one not in DB, one behind and one ahead
[39m
[33m# 148. Three peers, one not in DB, one behind and one ahead
[39m
[36mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 532 verify failed
ok 533 constructor called once
ok 534 constructor called with right args
ok 535 match start arg
ok 536 start called once
ok 537 stop called once
ok 538 stop after start
# teardown
[39m
[32mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 532 verify failed
ok 533 constructor called once
ok 534 constructor called with right args
ok 535 match start arg
ok 536 start called once
ok 537 stop called once
ok 538 stop after start
# teardown
[39m
[33mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 532 verify failed
[39m
[33mok 533 constructor called once
[39m
[33mok 534 constructor called with right args
[39m
[33mok 535 match start arg
[39m
[33mok 536 start called once
[39m
[33mok 537 stop called once
[39m
[33mok 538 stop after start
[39m
[33m# teardown
[39m
[33m# setup
[39m
[32m# setup
[39m
[36m# setup
[39m
2016-08-10T11:36:08.150Z - info: Running on ios test: 149. More than maximum peers, make sure we only send maximum allowed

[33m# 149. More than maximum peers, make sure we only send maximum allowed
[39m
[32m# 149. More than maximum peers, make sure we only send maximum allowed
[39m
[36m# 149. More than maximum peers, make sure we only send maximum allowed
[39m
[36mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[36mok 539 verify failed
[39m
[36mok 540 constructor called once
[39m
[36mok 541 constructor called with right args
[39m
[36mok 542 match start arg
[39m
[36mok 543 start called once
[39m
[36mok 544 stop called once
[39m
[36mok 545 stop after start
[39m
[32mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[32mok 539 verify failed
[39m
[32mok 540 constructor called once
[39m
[32mok 541 constructor called with right args
[39m
[32mok 542 match start arg
ok 543 start called once
[39m
[36m# teardown
[39m
[32mok 544 stop called once
ok 545 stop after start
[39m
[32m# teardown
[39m
[33mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 539 verify failed
ok 540 constructor called once
[39m
[33mok 541 constructor called with right args
ok 542 match start arg
[39m
[33mok 543 start called once
ok 544 stop called once
ok 545 stop after start
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-10T11:36:08.264Z - info: Running on ios test: 150. two peers with empty DB, update the doc

[32m# 150. two peers with empty DB, update the doc
[39m
[36m# 150. two peers with empty DB, update the doc
[39m
[33m# 150. two peers with empty DB, update the doc
[39m
[32mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[36mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[33mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[32mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[32mok 546 verify failed
ok 547 constructor called once
[39m
[32mok 548 constructor called with right args
[39m
[32mok 549 last start before stop
[39m
[32mok 550 empty first start
[39m
[32mok 551 full second start
[39m
[32mok 552 only 2 timers
[39m
[32m# teardown
[39m
[36mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 546 verify failed
ok 547 constructor called once
ok 548 constructor called with right args
[39m
[36mok 549 last start before stop
[39m
[36mok 550 empty first start
ok 551 full second start
[39m
[36mok 552 only 2 timers
[39m
[36m# teardown
[39m
[33mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 546 verify failed
ok 547 constructor called once
ok 548 constructor called with right args
ok 549 last start before stop
ok 550 empty first start
ok 551 full second start
[39m
[33mok 552 only 2 timers
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-10T11:36:08.381Z - info: Running on ios test: 151. add doc and make sure tokens refresh when they expire

[32m# 151. add doc and make sure tokens refresh when they expire
[39m
[36m# 151. add doc and make sure tokens refresh when they expire
[39m
[33m# 151. add doc and make sure tokens refresh when they expire
[39m
[32mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[36mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[33mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[36mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[32mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[33mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[32mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[32mok 553 verify failed
[39m
[33mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[32mok 554 constructor called once
[39m
[32mok 555 constructor called with right args
[39m
[33mok 553 verify failed
[39m
[33mok 554 constructor called once
[39m
[33mok 555 constructor called with right args
[39m
[33mok 556 start before stop
[39m
[33mok 557 We got at least 3 calls to start
ok 558 at least 3
[39m
[33mok 559 default 1
[39m
[33mok 560 1 run
ok 561 default 2
[39m
[32mok 556 start before stop
[39m
[32mok 557 We got at least 3 calls to start
[39m
[32mok 558 at least 3
[39m
[33mok 562 2 run
[39m
[32mok 559 default 1
[39m
[32mok 560 1 run
[39m
[32mok 561 default 2
[39m
[32mok 562 2 run
[39m
[32mok 563 default 3
[39m
[33mok 563 default 3
[39m
[32m# teardown
[39m
[36mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[36mok 553 verify failed
[39m
[36mok 554 constructor called once
[39m
[36mok 555 constructor called with right args
[39m
[36mok 556 start before stop
[39m
[36mok 557 We got at least 3 calls to start
[39m
[36mok 558 at least 3
[39m
[36mok 559 default 1
[39m
[36mok 560 1 run
[39m
[36mok 561 default 2
[39m
[36mok 562 2 run
ok 563 default 3
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
2016-08-10T11:36:08.746Z - info: Running on ios test: 152. start and stop and start and stop

[36m# 152. start and stop and start and stop
[39m
[32m# 152. start and stop and start and stop
[39m
[33m# 152. start and stop and start and stop
[39m
[36mok 564 start out null
[39m
[33mok 564 start out null
[39m
[36mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[36mok 565 back to null
[39m
[33mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[33mok 565 back to null
[39m
[36mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[36mok 566 still null
[39m
[36mok 567 verify failed
[39m
[36mok 568 constructor called once
[39m
[36mok 569 constructor called with right args
[39m
[36mok 570 first start before first stop
[39m
[36mok 571 first stop before second start
[39m
[36mok 572 second start before second stop
[39m
[36m# teardown
[39m
[33mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[33mok 566 still null
[39m
[33mok 567 verify failed
[39m
[33mok 568 constructor called once
[39m
[33mok 569 constructor called with right args
[39m
[33mok 570 first start before first stop
[39m
[33mok 571 first stop before second start
[39m
[33mok 572 second start before second stop
[39m
[33m# teardown
[39m
[32mok 564 start out null
[39m
[32mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[32mok 565 back to null
[39m
[32mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[32mok 566 still null
[39m
[32mok 567 verify failed
ok 568 constructor called once
[39m
[32mok 569 constructor called with right args
[39m
[32mok 570 first start before first stop
[39m
[32mok 571 first stop before second start
[39m
[32mok 572 second start before second stop
[39m
[32m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T11:36:08.812Z - info: Running on ios test: 153. two identical starts in a row

[36m# 153. two identical starts in a row
[39m
[32m# 153. two identical starts in a row
[39m
[33m# 153. two identical starts in a row
[39m
[36mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[36mok 573 verify failed
ok 574 constructor called once
[39m
[36mok 575 constructor called with right args
[39m
[36mok 576 (unnamed assert)
[39m
[36m# teardown
[39m
[32mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[32mok 573 verify failed
[39m
[32mok 574 constructor called once
ok 575 constructor called with right args
[39m
[32mok 576 (unnamed assert)
[39m
[32m# teardown
[39m
[33mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[33mok 573 verify failed
[39m
[33mok 574 constructor called once
ok 575 constructor called with right args
[39m
[33mok 576 (unnamed assert)
[39m
[33m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T11:36:08.872Z - info: Running on ios test: 154. two different starts in a row

[36m# 154. two different starts in a row
[39m
[33m# 154. two different starts in a row
[39m
[32m# 154. two different starts in a row
[39m
[32mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[32mok 577 verify failed
[39m
[36mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[32mok 578 constructor called once
[39m
[32mok 579 constructor called with right args
[39m
[32mok 580 (unnamed assert)
[39m
[32mok 581 (unnamed assert)
[39m
[32m# teardown
[39m
[36mok 577 verify failed
[39m
[36mok 578 constructor called once
[39m
[36mok 579 constructor called with right args
[39m
[36mok 580 (unnamed assert)
[39m
[36mok 581 (unnamed assert)
[39m
[36m# teardown
[39m
[33mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[33mok 577 verify failed
[39m
[33mok 578 constructor called once
[39m
[33mok 579 constructor called with right args
[39m
[33mok 580 (unnamed assert)
[39m
[33mok 581 (unnamed assert)
[39m
[33m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T11:36:08.947Z - info: Running on ios test: 155. two stops and a start and two stops

[32m# 155. two stops and a start and two stops
[39m
[36m# 155. two stops and a start and two stops
[39m
[33m# 155. two stops and a start and two stops
[39m
[32mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[32mok 582 verify failed
[39m
[32mok 583 constructor called once
[39m
[32mok 584 constructor called with right args
[39m
[32mok 585 start before stop
[39m
[32m# teardown
[39m
[33mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[33mok 582 verify failed
[39m
[33mok 583 constructor called once
[39m
[33mok 584 constructor called with right args
[39m
[33mok 585 start before stop
[39m
[33m# teardown
[39m
[36mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[36mok 582 verify failed
[39m
[36mok 583 constructor called once
[39m
[36mok 584 constructor called with right args
[39m
[36mok 585 start before stop
[39m
[36m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-10T11:36:09.019Z - info: Running on ios test: 156. we properly enqueue requests so no then needed

[32m# 156. we properly enqueue requests so no then needed
[39m
[36m# 156. we properly enqueue requests so no then needed
[39m
[33m# 156. we properly enqueue requests so no then needed
[39m
[32mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[32mok 586 verify failed
ok 587 constructor called once
[39m
[32mok 588 constructor called with right args
[39m
[32mok 589 start before stop
[39m
[32m# teardown
[39m
[36mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[36mok 586 verify failed
[39m
[36mok 587 constructor called once
[39m
[36mok 588 constructor called with right args
[39m
[36mok 589 start before stop
[39m
[36m# teardown
[39m
[33mDEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
[39m
[33mok 586 verify failed
[39m
[33mok 587 constructor called once
[39m
[33mok 588 constructor called with right args
[39m
[33mok 589 start before stop
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-10T11:36:09.076Z - info: Running on ios test: 157. test calculateSeqPointKeyId

[32m# 157. test calculateSeqPointKeyId
[39m
[36m# 157. test calculateSeqPointKeyId
[39m
[33m# 157. test calculateSeqPointKeyId
[39m
[32mok 590 should be equal
[39m
[32mok 591 should be equal
[39m
[32m# teardown
[39m
[36mok 590 should be equal
[39m
[36mok 591 should be equal
[39m
[36m# teardown
[39m
[33mok 590 should be equal
[39m
[33mok 591 should be equal
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-10T11:36:09.103Z - info: Running on ios test: 158. can create servers manager

[32m# 158. can create servers manager
[39m
[36m# 158. can create servers manager
[39m
[33m# 158. can create servers manager
[39m
[32mok 592 serversManager must not be null
[39m
[32mok 593 serversManager must be an object
# teardown
[39m
[36mok 592 serversManager must not be null
[39m
[36mok 593 serversManager must be an object
[39m
[36m# teardown
[39m
[33mok 592 serversManager must not be null
[39m
[33mok 593 serversManager must be an object
[39m
[33m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-08-10T11:36:09.128Z - info: Running on ios test: 159. calling stop without start causes error

[32m# 159. calling stop without start causes error
[39m
[36m# 159. calling stop without start causes error
[39m
[33m# 159. calling stop without start causes error
[39m
[32mok 594 We need to call start first
# teardown
[39m
[36mok 594 We need to call start first
# teardown
[39m
[33mok 594 We need to call start first
# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-10T11:36:09.152Z - info: Running on ios test: 160. can start/stop servers manager

[32m# 160. can start/stop servers manager
[39m
[33m# 160. can start/stop servers manager
[39m
[36m# 160. can start/stop servers manager
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51686
ok 595 port must be in range
# teardown
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51687
ok 595 port must be in range
# teardown
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: listening 51688
[39m
[33mok 595 port must be in range
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-10T11:36:09.175Z - info: Running on ios test: 161. starting twice resolves with listening port

[36m# 161. starting twice resolves with listening port
[39m
[32m# 161. starting twice resolves with listening port
[39m
[33m# 161. starting twice resolves with listening port
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51689
ok 596 second start should return same port
# teardown
[39m
[33mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51690
ok 596 second start should return same port
# teardown
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: listening 51691
ok 596 second start should return same port
# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T11:36:09.198Z - info: Running on ios test: 162. terminateIncomingConnection will terminate a connection

[32m# 162. terminateIncomingConnection will terminate a connection
[39m
[36m# 162. terminateIncomingConnection will terminate a connection
[39m
[33m# 162. terminateIncomingConnection will terminate a connection
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51694
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51695
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 597 we should be connected
DEBUG createNativeListener: incoming socket close
ok 598 now we are disconnected
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[32mok 597 we should be connected
[39m
[36m# teardown
[39m
[33mDEBUG createNativeListener: listening 51699
[39m
[32mDEBUG createNativeListener: incoming socket close
ok 598 now we are disconnected
[39m
[33mDEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
[39m
[32m# teardown
[39m
[33mok 597 we should be connected
[39m
[33mDEBUG createNativeListener: incoming socket close
ok 598 now we are disconnected
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-10T11:36:09.228Z - info: Running on ios test: 163. terminate an Outgoing connection will terminate the server

[32m# 163. terminate an Outgoing connection will terminate the server
[39m
[36m# 163. terminate an Outgoing connection will terminate the server
[39m
[33m# 163. terminate an Outgoing connection will terminate the server
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51701
# teardown
[39m
[36mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51702
# teardown
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: listening 51703
[39m
[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-10T11:36:09.252Z - info: Running on ios test: 164. terminate an Outgoing connection with wrong arguments is not harmful

[36m# 164. terminate an Outgoing connection with wrong arguments is not harmful
[39m
[32m# 164. terminate an Outgoing connection with wrong arguments is not harmful
[39m
[33m# 164. terminate an Outgoing connection with wrong arguments is not harmful
[39m
[32mDEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51704
# teardown
[39m
[36mDEBUG createNativeListener: creating native server
[39m
[36mDEBUG createNativeListener: listening 51705
[39m
[36m# teardown
[39m
[33mDEBUG createNativeListener: creating native server
[39m
[33mDEBUG createNativeListener: listening 51706
# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-08-10T11:36:09.276Z - info: Running on ios test: 165. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

[36mok 599 should be in started state
# 165. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
[39m
[32mok 599 should be in started state
# 165. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
[39m
[33mok 599 should be in started state
[39m
[33m# 165. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
[39m
[32mok 600 peer identifier should match
ok 601 host address should match
ok 602 port should match
ok 603 host address should be null
ok 604 port should should be null
[39m
[32m# teardown
[39m
[33mok 600 peer identifier should match
ok 601 host address should match
ok 602 port should match
[39m
[36mok 600 peer identifier should match
ok 601 host address should match
ok 602 port should match
[39m
[33mok 603 host address should be null
[39m
[33mok 604 port should should be null
[39m
[33m# teardown
[39m
[36mok 603 host address should be null
[39m
[36mok 604 port should should be null
[39m
[36m# teardown
[39m
[32mok 605 should not be in started state
# setup
[39m
[36mok 605 should not be in started state
[39m
[36m# setup
[39m
[33mok 605 should not be in started state
# setup
[39m
2016-08-10T11:36:09.308Z - info: Running on ios test: 166. #startUpdateAdvertisingAndListening should use different USN after every invocation

[32mok 606 should be in started state
# 166. #startUpdateAdvertisingAndListening should use different USN after every invocation
[39m
[33mok 606 should be in started state
[39m
[33m# 166. #startUpdateAdvertisingAndListening should use different USN after every invocation
[39m
[36mok 606 should be in started state
[39m
[36m# 166. #startUpdateAdvertisingAndListening should use different USN after every invocation
[39m
[32mok 607 USN should have changed from the first one
[39m
[32mok 608 when receiving the second byebye, the first USN should be already set
[39m
[32m# teardown
[39m
[36mok 607 USN should have changed from the first one
[39m
[36mok 608 when receiving the second byebye, the first USN should be already set
# teardown
[39m
[33mok 607 USN should have changed from the first one
[39m
[33mok 608 when receiving the second byebye, the first USN should be already set
[39m
[33m# teardown
[39m
[32mok 609 should not be in started state
# setup
[39m
[36mok 609 should not be in started state
# setup
[39m
[33mok 609 should not be in started state
# setup
[39m
2016-08-10T11:36:09.343Z - info: Running on ios test: 167. messages with invalid location or USN should be ignored

[32mok 610 should be in started state
# 167. messages with invalid location or USN should be ignored
[39m
[36mok 610 should be in started state
[39m
[36m# 167. messages with invalid location or USN should be ignored
[39m
[33mok 610 should be in started state
# 167. messages with invalid location or USN should be ignored
[39m
[32mWARN thaliWifiInfrastructure: Failed to parse a valid port number from location: http://foo.bar:90000
ok 611 should not have emitted with invalid port
WARN thaliWifiInfrastructure: Received an invalid USN value: 
ok 612 should not have emitted with invalid USN
# teardown
[39m
[36mWARN thaliWifiInfrastructure: Failed to parse a valid port number from location: http://foo.bar:90000
ok 611 should not have emitted with invalid port
[39m
[36mWARN thaliWifiInfrastructure: Received an invalid USN value: 
[39m
[36mok 612 should not have emitted with invalid USN
# teardown
[39m
[33mWARN thaliWifiInfrastructure: Failed to parse a valid port number from location: http://foo.bar:90000
ok 611 should not have emitted with invalid port
[39m
[33mWARN thaliWifiInfrastructure: Received an invalid USN value: 
[39m
[33mok 612 should not have emitted with invalid USN
[39m
[33m# teardown
[39m
[32mok 613 should not be in started state
# setup
[39m
[36mok 613 should not be in started state
[39m
[36m# setup
[39m
[33mok 613 should not be in started state
# setup
[39m
2016-08-10T11:36:09.370Z - info: Running on ios test: 168. verify that Thali-specific messages are filtered correctly

[32mok 614 should be in started state
# 168. verify that Thali-specific messages are filtered correctly
[39m
[36mok 614 should be in started state
[39m
[36m# 168. verify that Thali-specific messages are filtered correctly
[39m
[33mok 614 should be in started state
# 168. verify that Thali-specific messages are filtered correctly
[39m
[32mok 615 irrelevant messages should be ignored
ok 616 relevant messages should not be ignored
ok 617 messages from this device should be ignored
# teardown
[39m
[36mok 615 irrelevant messages should be ignored
ok 616 relevant messages should not be ignored
ok 617 messages from this device should be ignored
[39m
[36m# teardown
[39m
[33mok 615 irrelevant messages should be ignored
[39m
[33mok 616 relevant messages should not be ignored
[39m
[33mok 617 messages from this device should be ignored
[39m
[33m# teardown
[39m
[32mok 618 should not be in started state
# setup
[39m
[36mok 618 should not be in started state
[39m
[36m# setup
[39m
[33mok 618 should not be in started state
[39m
[33m# setup
[39m
2016-08-10T11:36:09.394Z - info: Running on ios test: 169. #startListeningForAdvertisements should fail if start not called

[32mok 619 should be in started state
# 169. #startListeningForAdvertisements should fail if start not called
[39m
[36mok 619 should be in started state
[39m
[36m# 169. #startListeningForAdvertisements should fail if start not called
[39m
[33mok 619 should be in started state
# 169. #startListeningForAdvertisements should fail if start not called
[39m
[32mok 620 specific error should be returned
# teardown
[39m
[36mok 620 specific error should be returned
# teardown
[39m
[33mok 620 specific error should be returned
# teardown
[39m
[32mok 621 should not be in started state
# setup
[39m
[36mok 621 should not be in started state
# setup
[39m
[33mok 621 should not be in started state
# setup
[39m
2016-08-10T11:36:09.421Z - info: Running on ios test: 170. #startUpdateAdvertisingAndListening should fail if start not called

[32mok 622 should be in started state
# 170. #startUpdateAdvertisingAndListening should fail if start not called
[39m
[36mok 622 should be in started state
# 170. #startUpdateAdvertisingAndListening should fail if start not called
[39m
[33mok 622 should be in started state
# 170. #startUpdateAdvertisingAndListening should fail if start not called
[39m
[32mok 623 specific error should be returned
# teardown
[39m
[36mok 623 specific error should be returned
[39m
[36m# teardown
[39m
[33mok 623 specific error should be returned
[39m
[33m# teardown
[39m
[32mok 624 should not be in started state
# setup
[39m
[36mok 624 should not be in started state
[39m
[36m# setup
[39m
[33mok 624 should not be in started state
[39m
[33m# setup
[39m
2016-08-10T11:36:09.445Z - info: Running on ios test: 171. #start should fail if called twice in a row

[32mok 625 should be in started state
# 171. #start should fail if called twice in a row
[39m
[36mok 625 should be in started state
[39m
[36m# 171. #start should fail if called twice in a row
[39m
[33mok 625 should be in started state
[39m
[33m# 171. #start should fail if called twice in a row
[39m
[32mok 626 specific error should be received
# teardown
[39m
[36mok 626 specific error should be received
[39m
[36m# teardown
[39m
[33mok 626 specific error should be received
# teardown
[39m
[36mok 627 should not be in started state
[39m
[36m# setup
[39m
[32mok 627 should not be in started state
# setup
[39m
[33mok 627 should not be in started state
[39m
[33m# setup
[39m
2016-08-10T11:36:09.469Z - info: Running on ios test: 172. should not be started after stop is called

[32mok 628 should be in started state
# 172. should not be started after stop is called
[39m
[36mok 628 should be in started state
[39m
[36m# 172. should not be started after stop is called
[39m
[33mok 628 should be in started state
[39m
[33m# 172. should not be started after stop is called
[39m
[32mok 629 should not be started
ok 630 should not be listening
ok 631 should not target listening
ok 632 should not be advertising
ok 633 should not target advertising
# teardown
[39m
[36mok 629 should not be started
ok 630 should not be listening
ok 631 should not target listening
ok 632 should not be advertising
[39m
[36mok 633 should not target advertising
[39m
[36m# teardown
[39m
[33mok 629 should not be started
[39m
[33mok 630 should not be listening
ok 631 should not target listening
[39m
[33mok 632 should not be advertising
ok 633 should not target advertising
[39m
[33m# teardown
[39m
[32mok 634 should not be in started state
# setup
[39m
[36mok 634 should not be in started state
[39m
[36m# setup
[39m
[33mok 634 should not be in started state
[39m
[33m# setup
[39m
2016-08-10T11:36:09.495Z - info: Running on ios test: 173. #startUpdateAdvertisingAndListening should fail invalid router has been passed

[32mok 635 should be in started state
# 173. #startUpdateAdvertisingAndListening should fail invalid router has been passed
[39m
[36mok 635 should be in started state
[39m
[36m# 173. #startUpdateAdvertisingAndListening should fail invalid router has been passed
[39m
[33mok 635 should be in started state
[39m
[33m# 173. #startUpdateAdvertisingAndListening should fail invalid router has been passed
[39m
[32mERROR thaliWifiInfrastructure: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
ok 636 specific error should be received
# teardown
[39m
[36mERROR thaliWifiInfrastructure: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
[39m
[36mok 636 specific error should be received
# teardown
[39m
[33mERROR thaliWifiInfrastructure: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
[39m
[33mok 636 specific error should be received
[39m
[33m# teardown
[39m
[36mok 637 should not be in started state
# setup
[39m
[32mok 637 should not be in started state
[39m
[32m# setup
[39m
[33mok 637 should not be in started state
[39m
[33m# setup
[39m
2016-08-10T11:36:09.525Z - info: Running on ios test: 174. #startUpdateAdvertisingAndListening should fail if router server starting fails

[32mok 638 should be in started state
# 174. #startUpdateAdvertisingAndListening should fail if router server starting fails
[39m
[36mok 638 should be in started state
# 174. #startUpdateAdvertisingAndListening should fail if router server starting fails
[39m
[33mok 638 should be in started state
# 174. #startUpdateAdvertisingAndListening should fail if router server starting fails
[39m
[32mERROR thaliWifiInfrastructure: Router server emitted an error: Error: listen EADDRINUSE
ok 639 specific error expected
# teardown
[39m
[36mERROR thaliWifiInfrastructure: Router server emitted an error: Error: listen EADDRINUSE
[39m
[36mok 639 specific error expected
[39m
[36m# teardown
[39m
[33mERROR thaliWifiInfrastructure: Router server emitted an error: Error: listen EADDRINUSE
[39m
[33mok 639 specific error expected
# teardown
[39m
[32mok 640 should not be in started state
# setup
[39m
[36mok 640 should not be in started state
# setup
[39m
[33mok 640 should not be in started state
# setup
[39m
2016-08-10T11:36:09.555Z - info: Running on ios test: 175. #startUpdateAdvertisingAndListening should start hosting given router object

[32mok 641 should be in started state
# 175. #startUpdateAdvertisingAndListening should start hosting given router object
[39m
[36mok 641 should be in started state
[39m
[36m# 175. #startUpdateAdvertisingAndListening should start hosting given router object
[39m
[33mok 641 should be in started state
[39m
[33m# 175. #startUpdateAdvertisingAndListening should start hosting given router object
[39m
[32mok 642 server should respond with code 200
[39m
[32m# teardown
[39m
[36mok 642 server should respond with code 200
[39m
[36m# teardown
[39m
[33mok 642 server should respond with code 200
[39m
[33m# teardown
[39m
[32mok 643 should not be in started state
[39m
[32m# setup
[39m
[36mok 643 should not be in started state
# setup
[39m
[33mok 643 should not be in started state
[39m
[33m# setup
[39m
2016-08-10T11:36:09.604Z - info: Running on ios test: 176. #startUpdateAdvertisingAndListening bad psk should be rejected object

[32mok 644 should be in started state
# 176. #startUpdateAdvertisingAndListening bad psk should be rejected object
[39m
[33mok 644 should be in started state
[39m
[36mok 644 should be in started state
# 176. #startUpdateAdvertisingAndListening bad psk should be rejected object
[39m
[33m# 176. #startUpdateAdvertisingAndListening bad psk should be rejected object
[39m
[32mok 645 Connection should be rejected
[39m
[32m# teardown
[39m
[36mok 645 Connection should be rejected
# teardown
[39m
[33mok 645 Connection should be rejected
# teardown
[39m
[32mok 646 should not be in started state
# setup
[39m
[36mok 646 should not be in started state
[39m
[36m# setup
[39m
[33mok 646 should not be in started state
# setup
[39m
2016-08-10T11:36:09.643Z - info: Running on ios test: 177. #stop can be called multiple times in a row

[32mok 647 should be in started state
# 177. #stop can be called multiple times in a row
[39m
[36mok 647 should be in started state
# 177. #stop can be called multiple times in a row
[39m
[33mok 647 should be in started state
[39m
[33m# 177. #stop can be called multiple times in a row
[39m
[32mok 648 should be in stopped state
ok 649 should still be in stopped state
# teardown
[39m
[36mok 648 should be in stopped state
[39m
[36mok 649 should still be in stopped state
[39m
[36m# teardown
[39m
[33mok 648 should be in stopped state
ok 649 should still be in stopped state
# teardown
[39m
[32mok 650 should not be in started state
# setup
[39m
[33mok 650 should not be in started state
[39m
[33m# setup
[39m
[36mok 650 should not be in started state
# setup
[39m
2016-08-10T11:36:09.666Z - info: Running on ios test: 178. #startListeningForAdvertisements can be called multiple times in a row

[32mok 651 should be in started state
# 178. #startListeningForAdvertisements can be called multiple times in a row
[39m
[36mok 651 should be in started state
[39m
[36m# 178. #startListeningForAdvertisements can be called multiple times in a row
[39m
[33mok 651 should be in started state
[39m
[33m# 178. #startListeningForAdvertisements can be called multiple times in a row
[39m
[32mok 652 should be in listening state
ok 653 should still be in listening state
# teardown
[39m
[36mok 652 should be in listening state
[39m
[36mok 653 should still be in listening state
[39m
[36m# teardown
[39m
[33mok 652 should be in listening state
ok 653 should still be in listening state
[39m
[33m# teardown
[39m
[32mok 654 should not be in started state
# setup
[39m
[36mok 654 should not be in started state
[39m
[36m# setup
[39m
[33mok 654 should not be in started state
[39m
[33m# setup
[39m
2016-08-10T11:36:09.693Z - info: Running on ios test: 179. #stopListeningForAdvertisements can be called multiple times in a row

[32mok 655 should be in started state
# 179. #stopListeningForAdvertisements can be called multiple times in a row
[39m
[36mok 655 should be in started state
# 179. #stopListeningForAdvertisements can be called multiple times in a row
[39m
[33mok 655 should be in started state
[39m
[33m# 179. #stopListeningForAdvertisements can be called multiple times in a row
[39m
[32mok 656 should not be in listening state
ok 657 should still not be in listening state
# teardown
[39m
[36mok 656 should not be in listening state
ok 657 should still not be in listening state
[39m
[36m# teardown
[39m
[33mok 656 should not be in listening state
[39m
[33mok 657 should still not be in listening state
[39m
[33m# teardown
[39m
[32mok 658 should not be in started state
# setup
[39m
[36mok 658 should not be in started state
[39m
[36m# setup
[39m
[33mok 658 should not be in started state
[39m
[33m# setup
[39m
2016-08-10T11:36:09.719Z - info: Running on ios test: 180. #stopAdvertisingAndListening can be called multiple times in a row

[36mok 659 should be in started state
# 180. #stopAdvertisingAndListening can be called multiple times in a row
[39m
[32mok 659 should be in started state
# 180. #stopAdvertisingAndListening can be called multiple times in a row
[39m
[33mok 659 should be in started state
[39m
[33m# 180. #stopAdvertisingAndListening can be called multiple times in a row
[39m
[32mok 660 should not be in advertising state
ok 661 should still not be in advertising state
# teardown
[39m
[33mok 660 should not be in advertising state
ok 661 should still not be in advertising state
# teardown
[39m
[36mok 660 should not be in advertising state
ok 661 should still not be in advertising state
# teardown
[39m
[32mok 662 should not be in started state
[39m
[32m# setup
[39m
[33mok 662 should not be in started state
# setup
[39m
[36mok 662 should not be in started state
# setup
[39m
2016-08-10T11:36:09.749Z - info: Running on ios test: 181. functions are run from a queue in the right order

[32mok 663 should be in started state
# 181. functions are run from a queue in the right order
[39m
[36mok 663 should be in started state
[39m
[36m# 181. functions are run from a queue in the right order
[39m
[33mok 663 should be in started state
[39m
[33m# 181. functions are run from a queue in the right order
[39m
[32mok 664 call order must match
# teardown
[39m
[33mok 664 call order must match
# teardown
[39m
[36mok 664 call order must match
# teardown
[39m
[32mok 665 should not be in started state
# setup
[39m
[36mok 665 should not be in started state
[39m
[36m# setup
[39m
[33mok 665 should not be in started state
[39m
[33m# setup
[39m
2016-08-10T11:36:09.781Z - info: Running on ios test: 182. does not get peer changes from self

[32mok 666 should be in started state
# 182. does not get peer changes from self
[39m
[36mok 666 should be in started state
# 182. does not get peer changes from self
[39m
[33mok 666 should be in started state
[39m
[33m# 182. does not get peer changes from self
[39m
[33mok 667 we should not get notified about any USN that we have used
[39m
[33mok 668 we should not get notified about any USN that we have used
[39m
[32mok 667 we should not get notified about any USN that we have used
[39m
[33mok 669 we should not get notified about any USN that we have used
[39m
[32mok 668 we should not get notified about any USN that we have used
[39m
[32mok 669 we should not get notified about any USN that we have used
[39m
[33mok 670 we should not get notified about any USN that we have used
[39m
[33mok 671 we should not get notified about any USN that we have used
[39m
[32mok 670 we should not get notified about any USN that we have used
[39m
[32mok 671 we should not get notified about any USN that we have used
[39m
[33mok 672 we should not get notified about any USN that we have used
[39m
[32mok 672 we should not get notified about any USN that we have used
[39m
[33mok 673 we should not get notified about any USN that we have used
[39m
[33mok 674 USN must have changed again
[39m
[36mok 667 we should not get notified about any USN that we have used
[39m
[36mok 668 we should not get notified about any USN that we have used
[39m
[32mok 673 we should not get notified about any USN that we have used
ok 674 we should not get notified about any USN that we have used
[39m
[32mok 675 USN must have changed again
[39m
[36mok 669 we should not get notified about any USN that we have used
ok 670 we should not get notified about any USN that we have used
[39m
[33mok 675 we should not get notified about any USN that we have used
ok 676 we should not get notified about any USN that we have used
[39m
[36mok 671 we should not get notified about any USN that we have used
[39m
[33mok 677 we should not get notified about any USN that we have used
[39m
[32mok 676 we should not get notified about any USN that we have used
[39m
[32mok 677 we should not get notified about any USN that we have used
[39m
[33mok 678 we should not get notified about any USN that we have used
[39m
[36mok 672 we should not get notified about any USN that we have used
[39m
[33mok 679 we should not get notified about any USN that we have used
[39m
[32mok 678 we should not get notified about any USN that we have used
[39m
[32mok 679 we should not get notified about any USN that we have used
[39m
[36mok 673 we should not get notified about any USN that we have used
[39m
[33mok 680 we should not get notified about any USN that we have used
[39m
[36mok 674 we should not get notified about any USN that we have used
[39m
[32mok 680 we should not get notified about any USN that we have used
[39m
[36mok 675 we should not get notified about any USN that we have used
[39m
[33mok 681 we should not get notified about any USN that we have used
[39m
[32mok 681 we should not get notified about any USN that we have used
[39m
[36mok 676 we should not get notified about any USN that we have used
[39m
[33mok 682 we should not get notified about any USN that we have used
[39m
[36mok 677 USN must have changed again
[39m
[32mok 682 we should not get notified about any USN that we have used
ok 683 we should not get notified about any USN that we have used
[39m
[33mok 683 we should not get notified about any USN that we have used
ok 684 we should not get notified about any USN that we have used
[39m
[33m# teardown
[39m
[36mok 678 we should not get notified about any USN that we have used
[39m
[32mok 684 we should not get notified about any USN that we have used
[39m
[32m# teardown
[39m
[36mok 679 we should not get notified about any USN that we have used
[39m
[36mok 680 we should not get notified about any USN that we have used
[39m
[36mok 681 we should not get notified about any USN that we have used
[39m
[33mDEBUG thaliPeerPoolDefault: Got err Error: Could not establish TCP connection
[39m
[36mok 682 we should not get notified about any USN that we have used
[39m
[36mok 683 we should not get notified about any USN that we have used
[39m
[36mok 684 we should not get notified about any USN that we have used
[39m
[36mok 685 we should not get notified about any USN that we have used
[39m
[36m# teardown
[39m
[36mok 686 should not be in started state
# setup
[39m
[33mok 685 should not be in started state
[39m
[32mok 685 should not be in started state
# setup
[39m
[33m# setup
[39m
2016-08-10T11:36:12.808Z - info: Running on ios test: 183. network changes are ignored while stopping

[32mok 686 should be in started state
# 183. network changes are ignored while stopping
[39m
[36mok 687 should be in started state
# 183. network changes are ignored while stopping
[39m
[33mok 686 should be in started state
[39m
[33m# 183. network changes are ignored while stopping
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 688 should not be called
# teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 687 should not be called
# teardown
[39m
[32mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 687 should not be called
# teardown
[39m
[36mok 689 should not be in started state
# setup
[39m
[33mok 688 should not be in started state
# setup
[39m
[32mok 688 should not be in started state
# setup
[39m
2016-08-10T11:36:12.835Z - info: Running on ios test: 184. #startListeningForAdvertisements returns error if wifi is off and fires event when on

[36mok 690 should be in started state
# 184. #startListeningForAdvertisements returns error if wifi is off and fires event when on
[39m
[32mok 689 should be in started state
# 184. #startListeningForAdvertisements returns error if wifi is off and fires event when on
[39m
[33mok 689 should be in started state
# 184. #startListeningForAdvertisements returns error if wifi is off and fires event when on
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 691 wifi should be off
ok 692 specific error expected
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 693 discoveryActive should be true
# teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 690 wifi should be off
ok 691 specific error expected
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 692 discoveryActive should be true
# teardown
[39m
[32mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 690 wifi should be off
ok 691 specific error expected
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 692 discoveryActive should be true
# teardown
[39m
[33mok 693 should not be in started state
# setup
[39m
[36mok 694 should not be in started state
[39m
[36m# setup
[39m
[32mok 693 should not be in started state
# setup
[39m
2016-08-10T11:36:12.863Z - info: Running on ios test: 185. #startUpdateAdvertisingAndListening returns error if wifi is off and fires event when on

[33mok 694 should be in started state
# 185. #startUpdateAdvertisingAndListening returns error if wifi is off and fires event when on
[39m
[32mok 694 should be in started state
# 185. #startUpdateAdvertisingAndListening returns error if wifi is off and fires event when on
[39m
[36mok 695 should be in started state
[39m
[36m# 185. #startUpdateAdvertisingAndListening returns error if wifi is off and fires event when on
[39m
[32mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 695 wifi should be off
ok 696 specific error expected
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 697 advertisingActive should be true
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 696 wifi should be off
ok 697 specific error expected
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[32m# teardown
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 695 wifi should be off
ok 696 specific error expected
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mok 698 advertisingActive should be true
# teardown
[39m
[33mok 697 advertisingActive should be true
[39m
[33m# teardown
[39m
[36mok 699 should not be in started state
# setup
[39m
[33mok 698 should not be in started state
# setup
[39m
[32mok 698 should not be in started state
[39m
[32m# setup
[39m
2016-08-10T11:36:12.894Z - info: Running on ios test: 186. when wifi is enabled discovery is activated and peers become available

[36mok 700 should be in started state
# 186. when wifi is enabled discovery is activated and peers become available
[39m
[32mok 699 should be in started state
# 186. when wifi is enabled discovery is activated and peers become available
[39m
[33mok 699 should be in started state
# 186. when wifi is enabled discovery is activated and peers become available
[39m
[32mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[32mok 700 wifi should be off
[39m
[32mok 701 specific error expected
[39m
[32mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[33mok 700 wifi should be off
[39m
[33mok 701 specific error expected
[39m
[33mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mDEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[36mok 701 wifi should be off
[39m
[36mok 702 specific error expected
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
[39m
[32mok 702 peer identifier should match
[39m
[32mok 703 host address should match
ok 704 port should match
[39m
[32m# teardown
[39m
[33mok 702 peer identifier should match
ok 703 host address should match
ok 704 port should match
[39m
[33m# teardown
[39m
[36mok 703 peer identifier should match
ok 704 host address should match
ok 705 port should match
[39m
[36m# teardown
[39m
[36mok 706 should not be in started state
# setup
[39m
[32mok 705 should not be in started state
# setup
[39m
[33mok 705 should not be in started state
# setup
[39m
2016-08-10T11:36:13.426Z - info: Running on ios test: 187. #ThaliPeerPoolDefault - single action

[36m# 187. #ThaliPeerPoolDefault - single action
[39m
[32m# 187. #ThaliPeerPoolDefault - single action
[39m
[33m# 187. #ThaliPeerPoolDefault - single action
[39m
[32mok 706 is an agent
ok 707 enqueue is fine
ok 708 Everything should be off the queue
# teardown
[39m
[36mok 707 is an agent
ok 708 enqueue is fine
ok 709 Everything should be off the queue
# teardown
[39m
[33mok 706 is an agent
ok 707 enqueue is fine
ok 708 Everything should be off the queue
[39m
[33m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-08-10T11:36:13.448Z - info: Running on ios test: 188. #ThaliPeerPoolDefault - multiple actions

[36m# 188. #ThaliPeerPoolDefault - multiple actions
[39m
[32m# 188. #ThaliPeerPoolDefault - multiple actions
[39m
[33m# 188. #ThaliPeerPoolDefault - multiple actions
[39m
[33mok 709 is an agent
ok 710 first enqueue is fine
ok 711 is an agent
ok 712 second enqueue is fine
ok 713 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 714 Queue is empty
# teardown
[39m
[36mok 710 is an agent
ok 711 first enqueue is fine
ok 712 is an agent
ok 713 second enqueue is fine
ok 714 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 715 Queue is empty
# teardown
[39m
[32mok 709 is an agent
[39m
[32mok 710 first enqueue is fine
[39m
[32mok 711 is an agent
[39m
[32mok 712 second enqueue is fine
[39m
[32mok 713 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 714 Queue is empty
# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-08-10T11:36:13.470Z - info: Running on ios test: 189. #ThaliPeerPoolDefault - PSK Pool works

[36m# 189. #ThaliPeerPoolDefault - PSK Pool works
[39m
[32m# 189. #ThaliPeerPoolDefault - PSK Pool works
[39m
[33m# 189. #ThaliPeerPoolDefault - PSK Pool works
[39m
[32mok 715 is an agent
ok 716 good enqueue
[39m
[36mok 716 is an agent
ok 717 good enqueue
[39m
[32mok 717 Identity should match
[39m
[36mok 718 Identity should match
[39m
[33mok 715 is an agent
ok 716 good enqueue
[39m
[36mok 719 Got expected response
[39m
[36mok 720 Got psk call back
# teardown
[39m
[32mok 718 Got expected response
ok 719 Got psk call back
# teardown
[39m
[33mok 717 Identity should match
[39m
[33mok 718 Got expected response
[39m
[33mok 719 Got psk call back
[39m
[33m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-08-10T11:36:13.514Z - info: Running on ios test: 190. #ThaliPeerPoolDefault - stop

[36m# 190. #ThaliPeerPoolDefault - stop
[39m
[32m# 190. #ThaliPeerPoolDefault - stop
[39m
[33m# 190. #ThaliPeerPoolDefault - stop
[39m
[32mok 720 is an agent
ok 721 enqueue worked
ok 722 is an agent
ok 723 enqueue 2 worked
ok 724 start action is killed
ok 725 killed action is still killed
ok 726 inQueue is empty
ok 727 Make sure we won enqueue after stopping
# teardown
[39m
[36mok 721 is an agent
ok 722 enqueue worked
ok 723 is an agent
ok 724 enqueue 2 worked
ok 725 start action is killed
ok 726 killed action is still killed
ok 727 inQueue is empty
ok 728 Make sure we won enqueue after stopping
# teardown
[39m
[33mok 720 is an agent
[39m
[33mok 721 enqueue worked
[39m
[33mok 722 is an agent
[39m
[33mok 723 enqueue 2 worked
[39m
[33mok 724 start action is killed
[39m
[33mok 725 killed action is still killed
[39m
[33mok 726 inQueue is empty
ok 727 Make sure we won enqueue after stopping
# teardown
[39m
2016-08-10T11:36:13.540Z - info: Test run on ios complete
2016-08-10T11:36:13.540Z - info: 

-== UNIT TEST RESULTS ==-
2016-08-10T11:36:13.541Z - info: PLATFORM: ios

2016-08-10T11:36:13.541Z - info: RESULT: FAIL

2016-08-10T11:36:13.542Z - info: 190 of 190 tests completed
2016-08-10T11:36:13.542Z - info: 189/190 passed (1 failures)
2016-08-10T11:36:13.542Z - info: 

--- Failed tests ---
2016-08-10T11:36:13.542Z - warn: 58. peer should be found once after listening and discovery started - fail
2016-08-10T11:36:13.542Z - info: 

-== END ==-

TEST FAILED - SEE ABOVE FOR MORE DETAILS
[33mTests complete
****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
[39m
[32mTests complete
****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
[39m
[36mTests complete
****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
[39m
-e [0;31mcompilation aborted
 [0m
build aborted
 [0m

cp: testBuildOrg//.git/objects/9f/85ee4e59a606752d8bee860a5610514b675385: No such file or directory
cp: testBuildOrg//.git/objects/9f/876eb7bc97447821e00e4cfe252b6a207452c7: No such file or directory
cp: testBuildOrg//.git/objects/9f/9c4df5ecc64efb2cfc5ad25c756949a4ea679d: No such file or directory
cp: testBuildOrg//.git/objects/9f/a1f7f67f777ca263bc0eeac27c3912f61c9c16: No such file or directory
cp: testBuildOrg//.git/objects/9f/a2a0b93b99e0751b1e9bd693c0e3bf66d76306: No such file or directory
cp: testBuildOrg//.git/objects/9f/a4d5843762753fd3e571d50b83c87d8b9bf05d: No such file or directory
cp: testBuildOrg//.git/objects/9f/a62a22407c60f5f5573dafe9addf98ee09e646: No such file or directory
cp: testBuildOrg//.git/objects/9f/acc7f94bda026a01dcf2ae89a73204df1bd475: No such file or directory
cp: testBuildOrg//.git/objects/9f/c662a6b21df83882cd2bbd0e33580966d0c766: No such file or directory
cp: testBuildOrg//.git/objects/9f/c7d66e312c0522049b164dc1ec16e408c698f3: No such file or directory
cp: testBuildOrg//.git/objects/9f/d7ad0b86902322d6e44ded39e7493e1e8108fa: No such file or directory
cp: testBuildOrg//.git/objects/9f/d9c529fbc5a9d1d5477d35ee3a59a27215fcbe: No such file or directory
cp: testBuildOrg//.git/objects/9f/da42331b72a404859ce587e66c3cb63d993ea7: No such file or directory
cp: testBuildOrg//.git/objects/9f/eb01458847db2b27edd8161e46f6a3dda12788: No such file or directory
cp: testBuildOrg//.git/objects/9f/eeaa84463ad5c9740d098a7fa2e095df8ffc69: No such file or directory
cp: testBuildOrg//.git/objects/9f/fd84ddc5f685030a0460db32a98b9fec823a5a: No such file or directory
cp: testBuildOrg//.git/objects/a5/eea73348af90f049d06c981e95fad57a589bd4: No such file or directory
cp: testBuildOrg//.git/objects/a5/f9640bae997850ccea2298d09ad1e3f41d0dcf: No such file or directory
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
cp: testBuildOrg//.git/objects/ae: unable to copy extended attributes to testBuild/.git/objects/ae: No such file or directory
cp: testBuildOrg//.git/objects/ae: No such file or directory
cp: testBuildOrg//.git/objects/b6/e65e780f2fdecf25f78a6571b4cffeeb7e2645: No such file or directory
cp: testBuildOrg//.git/objects/b6/e70d0892e9bcb549bf7da260f6372c477c837a: No such file or directory
cp: testBuildOrg//.git/objects/b6/e981d5bf1fce8267d69ced0ab1a46820091a13: No such file or directory
cp: testBuildOrg//.git/objects/b6/e9bbfb73ff439ee345819fae787fce1223e647: No such file or directory
cp: testBuildOrg//.git/objects/b6/f75d59f57a0bbb56dd1eff3faafab1f74b2ca1: No such file or directory
cp: testBuildOrg//.git/objects/b6/f825a053b74204b279026113359b140c56d083: No such file or directory
cp: testBuildOrg//.git/objects/b6/febee29148e2746e4352ed594989c815948e4a: No such file or directory
cp: testBuildOrg//.git/objects/b6/ff3b12c32a651030e5b5b4c2dace26f9c6931c: No such file or directory
cp: testBuildOrg//.git/objects/b6/ff514bc2dc6c639895a6a8f6b78c97b3910dda: No such file or directory
cp: testBuildOrg//.git/objects/b7/a71bbed68a26c2b0aebfa566a89eb457469a28: No such file or directory
cp: testBuildOrg//.git/objects/b7/b00f1f7daea3489edcee1c36ca071f77c8a36a: No such file or directory
cp: testBuildOrg//.git/objects/b7/b03457065b734c7f1b0d66e42e1b8e33d4ba49: No such file or directory
cp: testBuildOrg//.git/objects/b7/b44a6766efbc44a2463542171f32392c7fd2a8: No such file or directory
cp: testBuildOrg//.git/objects/b7/b501ac31a41ca263bc79d8a11149902b6ffd52: No such file or directory
cp: testBuildOrg//.git/objects/b7/d3db03642fab1cb63ceb45d268ad6382795d7d: No such file or directory
cp: testBuildOrg//.git/objects/b7/d43c894020b79ab715d029480ece8618c6e5cc: No such file or directory
cp: testBuildOrg//.git/objects/b7/d6d8e9721af5dce836bf79be1ff592eb1a63bb: No such file or directory
cp: testBuildOrg//.git/objects/b7/d9e525d0edbfde80534e0b7f1ea86818a82dfc: No such file or directory
cp: testBuildOrg//.git/objects/b7/ea81f0519c1181e41da5f2a9925bcd5ad32aec: No such file or directory
cp: testBuildOrg//.git/objects/b7/f3d175cede75fe5d1639d76ce4116205176f29: No such file or directory
cp: testBuildOrg//.git/objects/b7/f602434fe8e02f6aa76ab2964344e017fd6651: No such file or directory
cp: testBuildOrg//.git/objects/b7/ff6de7b1670adf1bef78a38a95835ee98ec52b: No such file or directory
cp: testBuildOrg//.git/objects/b8/53865a6bd9f8c25d10ef7ff982f5dc7e715615: No such file or directory
cp: testBuildOrg//.git/objects/b8/53deae203a660bae68d51367c1041473da4954: No such file or directory
cp: testBuildOrg//.git/objects/b8/5fd7103aeaac788eedab4b413d1ab712a1446e: No such file or directory
cp: testBuildOrg//.git/objects/b8/6327b0b98368253ecc493ec09f0817817a7b0a: No such file or directory
cp: testBuildOrg//.git/objects/b8/7fe5d0ddca2e7c119a3514041d92a174b2a5a0: No such file or directory
cp: testBuildOrg//.git/objects/b8/88650108b005f5f3ca99eea86f3edd8648ef70: No such file or directory
cp: testBuildOrg//.git/objects/b8/8a05f576bf8fb8c605debd5cc1fee657215f55: No such file or directory
cp: testBuildOrg//.git/objects/b8/9c3955111ecb0d16db584f9e2c075a4e8b6d88: No such file or directory
cp: testBuildOrg//.git/objects/b8/9ebe525fb0d959ba165219d326c7818de57e76: No such file or directory
cp: testBuildOrg//.git/objects/b8/a4982a63ce76efafc721ecc539d43ab9511229: No such file or directory
cp: testBuildOrg//.git/objects/b8/a4fff5cfa15daa7a155b86dc645bb3b98e5e64: No such file or directory
cp: testBuildOrg//.git/objects/b8/a821195486f4d356468c881da5539b82057a15: No such file or directory
cp: testBuildOrg//.git/objects/b8/a9768cd78a0fa2a32700ca09feeb0935e61004: No such file or directory
cp: testBuildOrg//.git/objects/b8/b49964b07dd4d84db0d55524444cc6cede4448: No such file or directory
cp: testBuildOrg//.git/objects/b8/ba588bb7101a20abaddc030f809f56b53b5ee4: No such file or directory
cp: testBuildOrg//.git/objects/b8/bb5b341c7062bb9b5fd42e41cd0194d941dc0b: No such file or directory
cp: testBuildOrg//.git/objects/b8/be062fafd2921957ca706ff1af234a7eb7881e: No such file or directory
cp: testBuildOrg//.git/objects/b8/c22a8dffdafe6106100eb2a8a65700e14fb2b4: No such file or directory
cp: testBuildOrg//.git/objects/b8/ccb9f7bfa8f766ea53a0374995f1cd91de805c: No such file or directory
cp: testBuildOrg//.git/objects/b8/d20aa8eaa9091a6891e65a49e12ae7cfdaee73: No such file or directory
cp: testBuildOrg//.git/objects/b8/ed845d6144f5f2edc645044cfb60a3c18b14f2: No such file or directory
cp: testBuildOrg//.git/objects/b8/efe62e34d308c561cf5ec49d40ef7a10296fe9: No such file or directory
cp: testBuildOrg//.git/objects/b8/f1913f739f23e802ef943707592f6b9ef331a8: No such file or directory
cp: testBuildOrg//.git/objects/b8/fef24b7082fe0d2a4fbb27763593dad0e842f5: No such file or directory
cp: testBuildOrg//.git/objects/b8/ff39ac18611fc5bab10137af7adc20e02b58ce: No such file or directory
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
cp: testBuildOrg//.git/objects/b9/d819c8f4ec6d240f2e0cda4d294ae18622c563: No such file or directory
cp: testBuildOrg//.git/objects/b9/d86523b12a383b9583388c1c059e465227817e: No such file or directory
cp: testBuildOrg//.git/objects/b9/dab625f5110803ac05855c1b2d1d33587e8a77: No such file or directory
cp: testBuildOrg//.git/objects/b9/dcf8a0d14e2ef54b43180b84826543c1725337: No such file or directory
cp: testBuildOrg//.git/objects/b9/df64211c6b6c4bce9b467fbe6759023f2c9fe2: No such file or directory
cp: testBuildOrg//.git/objects/b9/ea373db91bb2a5c0e0bcc6967a16380dbdf21b: No such file or directory
cp: testBuildOrg//.git/objects/b9/ec7d76913c7fc572ec8cdaae20338bd6d5fb84: No such file or directory
cp: testBuildOrg//.git/objects/b9/f5b8528e98ab8cbe332b4bc78af47f9bc076e1: No such file or directory
cp: testBuildOrg//.git/objects/ba/128588ece2bcf73991c936aad60d815382544e: No such file or directory
cp: testBuildOrg//.git/objects/ba/169e48097ae5d461453ad6396efdb66ab4ec12: No such file or directory
cp: testBuildOrg//.git/objects/ba/17c0cae8b61a4c1d2b0210258d762ac38bd511: No such file or directory
cp: testBuildOrg//.git/objects/ba/3107672a62f9f98edd4400b5495224ca406d90: No such file or directory
cp: testBuildOrg//.git/objects/ba/3acfdfb6e68542d38ffa77fa8571da9084b3c8: No such file or directory
cp: testBuildOrg//.git/objects/ba/3f7d71b28664e0b4c3c5ac2aae7cf1cce52f54: No such file or directory
cp: testBuildOrg//.git/objects/ba/43b4bf3a8f4e151211309cc2f0056b412deb9e: No such file or directory
cp: testBuildOrg//.git/objects/ba/4408e9fdda699c503a6e3faff0315137ff6ce0: No such file or directory
cp: testBuildOrg//.git/objects/ba/46c2d73eb5bc14aeb21e095dc2cb690c11eaa3: No such file or directory
cp: testBuildOrg//.git/objects/ba/584b544d5e7cb40c1fb96a251de7896cfe9c84: No such file or directory
cp: testBuildOrg//.git/objects/ba/72822e8728ef2951005e49b6c27a2f1da6572d: No such file or directory
cp: testBuildOrg//.git/objects/ba/80f79a88edb1fff57885ce5cb9026278108b24: No such file or directory
cp: testBuildOrg//.git/objects/ba/847d4c4e4eae4d87ea95d85f109db8cf3fa065: No such file or directory
cp: testBuildOrg//.git/objects/ba/89b9b7e42c2c120c0f62fa7f89945da03dee7a: No such file or directory
cp: testBuildOrg//.git/objects/ba/8a10517e73e213e4c649be18f2755485fba076: No such file or directory
cp: testBuildOrg//.git/objects/ba/8e1db34cdc5ae3227487f688661eaaa4a77bd5: No such file or directory
cp: testBuildOrg//.git/objects/ba/a16a3d36a20f2e97af417e535b3825bd00ddf6: No such file or directory
cp: testBuildOrg//.git/objects/ba/a330adf06b65a0155b1257fda391294cc125db: No such file or directory
cp: testBuildOrg//.git/objects/ba/a3f1de36e86ab443d7e5aa98c6215792549f28: No such file or directory
cp: testBuildOrg//.git/objects/ba/a8a671b13b582fb2b65524d2486bf2e43bf4b8: No such file or directory
cp: testBuildOrg//.git/objects/ba/abfeb08d4c3d366fc1730893da48e5c00c08a6: No such file or directory
cp: testBuildOrg//.git/objects/ba/aef6a284735d503fa193eb8aec9b6b0c38bb1f: No such file or directory
cp: testBuildOrg//.git/objects/ba/b3f0547208328cbbfaf3f903b9c258069993e0: No such file or directory
cp: testBuildOrg//.git/objects/ba/b421c55c2ffd48a4db64dd0fb86d144cb6c5ac: No such file or directory
cp: testBuildOrg//.git/objects/ba/c41c2add96cb1c6061a418a6a3e1a2c9f4ac09: No such file or directory
cp: testBuildOrg//.git/objects/ba/c4dc60b13e6a90c646a7a3485d4e24aa7b491e: No such file or directory
cp: testBuildOrg//.git/objects/ba/c7d2d8d8b65428b47ab520b921ba99afeb6d86: No such file or directory
cp: testBuildOrg//.git/objects/ba/d1a80811cfbe55c9d45c7afb8156f4b731cd01: No such file or directory
cp: testBuildOrg//.git/objects/ba/d4f6ac67d634274460aa25256c6479650dd56c: No such file or directory
cp: testBuildOrg//.git/objects/ba/d561e2ab6b453975cfe9f2eda6faba76bd62a6: No such file or directory
cp: testBuildOrg//.git/objects/ba/e0cc139e9e578076bb28fa9fd2779f7fb4d367: No such file or directory
cp: testBuildOrg//.git/objects/ba/e47c7af0ff802ccbd07c37124d066353c0917d: No such file or directory
cp: testBuildOrg//.git/objects/ba/fa2be5cf41faa7a92d28e5acf40b8a88637d63: No such file or directory
cp: testBuildOrg//.git/objects/ba/fbbef8910a63ecc4c6ccdd797f5a74a2ec2591: No such file or directory
cp: testBuildOrg//.git/objects/ba/fbd8d877a8ac8c95b1f72100c56035adfd6456: No such file or directory
cp: testBuildOrg//.git/objects/ba/fc3f68c4774444d9f54a30b282b2c0befe4a46: No such file or directory
cp: testBuildOrg//.git/objects/bb/4658c70fb47c91a08120d42f6be7d64f04a98d: No such file or directory
cp: testBuildOrg//.git/objects/bb/539ecfdfc7e3f44aad03018d093a3d461d47c1: No such file or directory
cp: testBuildOrg//.git/objects/bb/6009f9b1840b1a04eafd7419926d43beaeac37: No such file or directory
cp: testBuildOrg//.git/objects/bb/65c1e77e8286cb17af1614f9f018d20e570e4b: No such file or directory
cp: testBuildOrg//.git/objects/bb/6b81ba65892b8604520ba0153c3fc444f73257: No such file or directory
cp: testBuildOrg//.git/objects/bb/7529b1878026d14720a3df8e4c1a90aa957be2: No such file or directory
cp: testBuildOrg//.git/objects/bb/dab4715f693fad411f84e2f243b9d108fa2941: No such file or directory
cp: testBuildOrg//.git/objects/bb/e3f60c96cc7d450b352d640ba2bb8fa677f65e: No such file or directory
cp: testBuildOrg//.git/objects/bb/e63e76457e6004da2f5daab28ba8172780ed51: No such file or directory
cp: testBuildOrg//.git/objects/bb/f0d939085169046915c8faff7412422dc4eaec: No such file or directory
cp: testBuildOrg//.git/objects/bb/f0e399bb7a609827a9952f3820a1aae663910e: No such file or directory
cp: testBuildOrg//.git/objects/bc/2b56ae3f4af2db7212ba79a81a272ab1317861: No such file or directory
cp: testBuildOrg//.git/objects/bc/2b57e80f1a6ded7ba38a0ea95a43babeb5cb0a: No such file or directory
cp: testBuildOrg//.git/objects/bc/302f77347d295c6def84cda4e49234e8ff0054: No such file or directory
cp: testBuildOrg//.git/objects/bc/3e5d172b64ad5913e6d976dd1491562b4491ba: No such file or directory
cp: testBuildOrg//.git/objects/bc/4f2f5e942fa4170d44a92cbcac53607351482b: No such file or directory
cp: testBuildOrg//.git/objects/bc/536470681b43391d9477f80c71275df54ea85f: No such file or directory
cp: testBuildOrg//.git/objects/bc/5b63721152656af0b4af0337a106fc5d37a20d: No such file or directory
cp: testBuildOrg//.git/objects/bc/664c72b59842123e34e234628dd0c07c1a7530: No such file or directory
cp: testBuildOrg//.git/objects/bc/69dd583aaba15e6711ec1d5e552fa3b55282e2: No such file or directory
cp: testBuildOrg//.git/objects/bc/6b357e08a7e67fc63705250e995d961b219353: No such file or directory
cp: testBuildOrg//.git/objects/bc/80519d3588138c7ef0b8c1e344385cfc2216dd: No such file or directory
cp: testBuildOrg//.git/objects/bc/81153f7b0f7d3cb5824f5ba9e5ebb800620429: No such file or directory
cp: testBuildOrg//.git/objects/bc/87e56523754ffa3f192a0ce0e17361c24f6824: No such file or directory
cp: testBuildOrg//.git/objects/bc/89e2a04300ff11b5fcb79cfbb42c4fee057cf5: No such file or directory
cp: testBuildOrg//.git/objects/bc/8d5026d1c0f5185600c2f73f55715c95e16325: No such file or directory
cp: testBuildOrg//.git/objects/bc/8dec674ffa8f1c81fd0cb2cb9a7c8a1b7c4f2d: No such file or directory
cp: testBuildOrg//.git/objects/bc/a1aec166d5b91e62c70ed3d0c15b17297110e9: No such file or directory
cp: testBuildOrg//.git/objects/bc/ad1229856df887ed4c54bd9bd4cf806f2db2f2: No such file or directory
cp: testBuildOrg//.git/objects/bc/b0afc5a195ee85dc18d678bd8c659d07b0ac9a: No such file or directory
cp: testBuildOrg//.git/objects/bc/b545fe293b2dfec21ca0367a49b7c61233f07f: No such file or directory
cp: testBuildOrg//.git/objects/bc/df06b8cedbd3fdc1c33e9f978187c11a3beedf: No such file or directory
cp: testBuildOrg//.git/objects/bc/e2fef6f67e55b892566ae5f711927f84c61a5a: No such file or directory
cp: testBuildOrg//.git/objects/bc/e47214c81d829660c8cf374bc69422903a8208: No such file or directory
cp: testBuildOrg//.git/objects/bc/e79d0185e8d2762edd51a53bfe5c700a9678aa: No such file or directory
cp: testBuildOrg//.git/objects/bc/ecc5c6ffffe86a798f0672925e1d0b1ab467bd: No such file or directory
cp: testBuildOrg//.git/objects/bc/f258d878759df4196bea1fe01fa87c6c8d40e1: No such file or directory
cp: testBuildOrg//.git/objects/bc/f70a8fbe858db1971eab0db3ac3240e62b72d5: No such file or directory
cp: testBuildOrg//.git/objects/bc/f8b2d609b00a1e73f27ff52371a5eb8a6675ee: No such file or directory
cp: testBuildOrg//.git/objects/bc/ffa052bd59a79ee5ae8400bc613810e96ef784: No such file or directory
cp: testBuildOrg//.git/objects/c0/fcaf3fe36db3e42dba3fa2e89e89fc4a6dfec4: No such file or directory
cp: testBuildOrg//.git/objects/c1/72a344e5e85857077f14385af4edad995ee26f: No such file or directory
cp: testBuildOrg//.git/objects/c1/794c376296078013c8dd8d8677b062eb278707: No such file or directory
cp: testBuildOrg//.git/objects/c1/7965f765fe41d82a4b96535d69cb1d9b3ed74b: No such file or directory
cp: testBuildOrg//.git/objects/c1/7a6bd60163cc7189bbdb8087ad599c2260adad: No such file or directory
cp: testBuildOrg//.git/objects/c1/7c777583f38d72609b35782255c4a36289c96c: No such file or directory
cp: testBuildOrg//.git/objects/c1/8044360b0cbfc3cd0085b6c9c80a1a1e59c0b8: No such file or directory
cp: testBuildOrg//.git/objects/c1/81aaac7876b259f526e9ca506f97be52721628: No such file or directory
cp: testBuildOrg//.git/objects/c1/8583e1844471baab337525656d6efc6dfe934b: No such file or directory
cp: testBuildOrg//.git/objects/c1/8eec88807e2dd21af3e398c84445de8b816da8: No such file or directory
cp: testBuildOrg//.git/objects/c1/926237e43177bcd339d3a375115b8c46e6786d: No such file or directory
cp: testBuildOrg//.git/objects/c1/af5ad7f328c2578e7195bdce905a935e543505: No such file or directory
cp: testBuildOrg//.git/objects/c1/c172d42b21f02014c5d8e8d121b3e1959fdcdd: No such file or directory
cp: testBuildOrg//.git/objects/c1/c65d467609369f7b47494528d8843599a7a752: No such file or directory
cp: testBuildOrg//.git/objects/c1/c7ecc31df3e0e864d1b2f6431c0f3ab5b9ac19: No such file or directory
cp: testBuildOrg//.git/objects/c1/d1007f6d9fc8622e7ab434b2720a42fe3a43cc: No such file or directory
cp: testBuildOrg//.git/objects/c1/e201075fe5c7565e7914cc5cc92393d09779bf: No such file or directory
cp: testBuildOrg//.git/objects/c1/e6f5edf21a7cec36bb8744cc3fc6cda031e10a: No such file or directory
cp: testBuildOrg//.git/objects/c1/e9930b97bb3a7cfa2a0ee44fcbcee4f2c33c19: No such file or directory
cp: testBuildOrg//.git/objects/c1/f1271d3995688e1b2d40b0f92e854373519769: No such file or directory
cp: testBuildOrg//.git/objects/c2/362f3dbf24c15e1df8256ac0fea5ec2719daab: No such file or directory
cp: testBuildOrg//.git/objects/c2/3922db0265093229e9f435d028504c18daee3e: No such file or directory
cp: testBuildOrg//.git/objects/c2/3b194ea9b851bb6d49b52ad458eb3214cca734: No such file or directory
cp: testBuildOrg//.git/objects/c2/3bf7c0cfe69878964ec12d36b5b2e28d411cb4: No such file or directory
cp: testBuildOrg//.git/objects/c2/3c3c65beb22e8b21dea74ccd2ae4987e9a1f49: No such file or directory
cp: testBuildOrg//.git/objects/c2/3efd8eb7f99f36e2e856dda230e3d9cf4b5bcf: No such file or directory
cp: testBuildOrg//.git/objects/c2/418e5d39b7455973ddacced3190d2a655e9ad9: No such file or directory
cp: testBuildOrg//.git/objects/c2/49f8abff886536c147e5b4b6f28bfb55ff68a3: No such file or directory
cp: testBuildOrg//.git/objects/c2/4cf456decd29e64cfdc0d8257e7ab91368afd3: No such file or directory
cp: testBuildOrg//.git/objects/c2/5654987f8577a3e0a728c50b75df38cd6af260: No such file or directory
cp: testBuildOrg//.git/objects/c2/5750eaa2be5910eee98b0fd7fadc183159cba2: No such file or directory
cp: testBuildOrg//.git/objects/c2/5a5bd6cc49538d6b5ba4965635811072426ffb: No such file or directory
cp: testBuildOrg//.git/objects/c2/689ed84f67b73a74c734b9326b64096ea9a730: No such file or directory
cp: testBuildOrg//.git/objects/c2/6a9ef372af30d6a63d0dc797d7a7750a25d12f: No such file or directory
cp: testBuildOrg//.git/objects/c2/7a0025366084cb8af4e2aadabec4ae0b7a27ed: No such file or directory
cp: testBuildOrg//.git/objects/c2/7da76ad94ec0091ac8f7dbede53937aaa28714: No such file or directory
cp: testBuildOrg//.git/objects/c2/87417d77d401fc6f86e8647e7caa72964fc4da: No such file or directory
cp: testBuildOrg//.git/objects/c2/89374ff5a55829d22a4a436912d9aba3bb9774: No such file or directory
cp: testBuildOrg//.git/objects/c2/8cc77debae00a5508723fad86a0ab8fef59ec3: No such file or directory
cp: testBuildOrg//.git/objects/c2/f4c8d3cc872fc5b2ff8317fc2b3c96a9283ee0: No such file or directory
cp: testBuildOrg//.git/objects/c2/f88c8f809567bc03b71c83a11cffdafeaeb079: No such file or directory
cp: testBuildOrg//.git/objects/c2/fa0447e996c053e79eb42eda87422e084a5f67: No such file or directory
cp: testBuildOrg//.git/objects/c3/4f1393d37adb0ca3d124a84687e95b89362393: No such file or directory
cp: testBuildOrg//.git/objects/c3/55d2625e6cacff5905dc9d332b117fabc11591: No such file or directory
cp: testBuildOrg//.git/objects/c3/56c354f5f7347739cdf0225a6d7a8216c86e79: No such file or directory
cp: testBuildOrg//.git/objects/c3/680c86ef1102f8999875324a2beadbf2e05eda: No such file or directory
cp: testBuildOrg//.git/objects/c3/68d7d6ccb8f57c145b82dfe181ff9dbe1e847e: No such file or directory
cp: testBuildOrg//.git/objects/c3/6c3fe0201398cd23bb88fa54423b3115fe2a0f: No such file or directory
cp: testBuildOrg//.git/objects/c3/710eaad17b67d824edf803881426ae7959f88b: No such file or directory
cp: testBuildOrg//.git/objects/c3/7c30777c182d798e3ae94ea5af654925a67110: No such file or directory
cp: testBuildOrg//.git/objects/c3/7d0c004b159e5e1f10594518a1f807bc0efdb2: No such file or directory
cp: testBuildOrg//.git/objects/c3/873d1b0c1442aca4d19ae8cafb6a0f36a02044: No such file or directory
cp: testBuildOrg//.git/objects/c3/8c9a0b89a220c4981c5e895e231980b2594271: No such file or directory
cp: testBuildOrg//.git/objects/c3/966e08a29433127dfeda802de9f32fa29d1fb8: No such file or directory
cp: testBuildOrg//.git/objects/c3/994deff78d798db53a1cafb11097331c8acd8b: No such file or directory
cp: testBuildOrg//.git/objects/c3/9d7825ad5ae6d328ebda7301e8559a200cac0a: No such file or directory
cp: testBuildOrg//.git/objects/c3/a5ee833a3ca94409e94cbf1f5b8c799aa22758: No such file or directory
cp: testBuildOrg//.git/objects/c3/a6db56f41d18705af20d2a8f17157895a07679: No such file or directory
cp: testBuildOrg//.git/objects/c3/b74e026f6e24d9f572614bd8d54ca27446b3ca: No such file or directory
cp: testBuildOrg//.git/objects/c3/bd16977bcadb3ebb616d44a9a5880b9487683c: No such file or directory
cp: testBuildOrg//.git/objects/c3/be3667ebdb84f9242e0ef681f6ff5a2c071c85: No such file or directory
cp: testBuildOrg//.git/objects/c3/be6e515551f53c482ae62a3c8954ed5372f635: No such file or directory
cp: testBuildOrg//.git/objects/c3/c617ba70c0cdd9502b2495e5a9a1155c684081: No such file or directory
cp: testBuildOrg//.git/objects/c3/c61bf8b71a01f4fd9dded13ada92560445d957: No such file or directory
cp: testBuildOrg//.git/objects/c3/c99e3b47e7ff491e9f36a082160ebb88f9b398: No such file or directory
cp: testBuildOrg//.git/objects/c3/cde4ab8a8300fdd33aed2b2b321eda6fa6ed77: No such file or directory
cp: testBuildOrg//.git/objects/c3/d91a9baddc6883302474849ce016358f936b05: No such file or directory
cp: testBuildOrg//.git/objects/c3/db73722c0ba172ff5a71d90e5aa4a4d1e07335: No such file or directory
cp: testBuildOrg//.git/objects/c3/dd232667d674407d2944178f3066337dee9717: No such file or directory
cp: testBuildOrg//.git/objects/c3/e1efd3d82f3dffcc61521860bc71565ebf5e50: No such file or directory
cp: testBuildOrg//.git/objects/c3/e874f1ea0ae991dc2f9a4cb836df63dbef8918: No such file or directory
cp: testBuildOrg//.git/objects/c3/e96270a812326db71c596f7c5b0e4632565cc9: No such file or directory
cp: testBuildOrg//.git/objects/c3/ee53fe6bad37298ef97f3e7a9715fbabb36770: No such file or directory
cp: testBuildOrg//.git/objects/c3/f4640dc2bf517f77cd3670f73e38cd2981a844: No such file or directory
cp: testBuildOrg//.git/objects/c3/f68d4c82ec2e69d54a1742410b1caeea901b01: No such file or directory
cp: testBuildOrg//.git/objects/c3/fbe8be7d472b8658a5694069047b66ace9caaf: No such file or directory
cp: testBuildOrg//.git/objects/c4/942797bcd9fb1a194e37176684dfbb202b908c: No such file or directory
cp: testBuildOrg//.git/objects/c4/9dd0904c72b295450b360eebf3a4ce0dbb71fa: No such file or directory
cp: testBuildOrg//.git/objects/c4/a051e5c7b59d418acf47e7ffc32bc5197f2acf: No such file or directory
cp: testBuildOrg//.git/objects/c4/a3e11d7d3c016c413b28ad02aed5cc0cf4771d: No such file or directory
cp: testBuildOrg//.git/objects/c4/aa36441bb07b07b03279f7d943afef4fcd4562: No such file or directory
cp: testBuildOrg//.git/objects/c4/b221016c28ddf9d311ef7e5654eb15a1d6695a: No such file or directory
cp: testBuildOrg//.git/objects/c4/b53ae2f01156213d3f6c71d91c98628c965dc4: No such file or directory
cp: testBuildOrg//.git/objects/c4/befbd7c0af6ce4be43b3e7730ef3a4b8303942: No such file or directory
cp: testBuildOrg//.git/objects/c4/bfca7b4bb3e1f844549aeb6f7e0367edb9257d: No such file or directory
cp: testBuildOrg//.git/objects/c4/d5736ff86b76f1e418e7076e8cbbb7350342fc: No such file or directory
cp: testBuildOrg//.git/objects/c4/dc66861b5dfe36fa8fba7f2af43f44c979bd4c: No such file or directory
cp: testBuildOrg//.git/objects/c4/dccd07b7babca942ae1ee849b4ebe49c611fd1: No such file or directory
cp: testBuildOrg//.git/objects/c4/df4e3ae7930281bb55161190d519e5fefb293c: No such file or directory
cp: testBuildOrg//.git/objects/c4/e91218a476bb772c4a38988a08622700ea7a7c: No such file or directory
cp: testBuildOrg//.git/objects/c4/eae9c1b610c66c1779b91b4ca87e87c2815ad6: No such file or directory
cp: testBuildOrg//.git/objects/c4/f4684c001cda3e9534d928e13fff6f0549249a: No such file or directory
cp: testBuildOrg//.git/objects/c5/41d200d31fc2acc839c4be495665c853e55af0: No such file or directory
cp: testBuildOrg//.git/objects/c5/425bd451c32bef327aae015346551865c26652: No such file or directory
cp: testBuildOrg//.git/objects/c5/4c0d272a2c763fb10179471138243f48a74b01: No such file or directory
cp: testBuildOrg//.git/objects/c5/52aca6c83e4f60164c5ee7fcdc081bcbb4e91d: No such file or directory
cp: testBuildOrg//.git/objects/c5/55ef8aef053ac4c08b4c58c046555ea23d551b: No such file or directory
cp: testBuildOrg//.git/objects/c5/588d496b1a8309abbfb4f16080532b2f82983d: No such file or directory
cp: testBuildOrg//.git/objects/c5/5a7872585c20cb9b9f07f45e452eeeec0dcea1: No such file or directory
cp: testBuildOrg//.git/objects/c5/5b24a3b5644277a6f8481cce4390eeb3eefd92: No such file or directory
cp: testBuildOrg//.git/objects/c5/5cdcd25ad9767f2f9238941703c265432f6ce3: No such file or directory
cp: testBuildOrg//.git/objects/c5/6370531586f6eeeb58a76a1fd7a7bd433582ee: No such file or directory
cp: testBuildOrg//.git/objects/c5/6f6cdeba7c02fa2adec61d74c8eead035ad510: No such file or directory
cp: testBuildOrg//.git/objects/c5/7259d23c730341cb0dd5b7e037c7396f14efec: No such file or directory
cp: testBuildOrg//.git/objects/c5/76ace8c61cc8f7657cf8135d70d98670db5519: No such file or directory
cp: testBuildOrg//.git/objects/c5/7df7e8d6c5e022590ad753ea88e72ffb820733: No such file or directory
cp: testBuildOrg//.git/objects/c5/7fff09b6624e034064190e1e4fcfd4b1566ea1: No such file or directory
cp: testBuildOrg//.git/objects/c5/89e0d5f584560e369514bcb4551f5bf495010b: No such file or directory
cp: testBuildOrg//.git/objects/c5/967c47e0a4ba6c83b34054560c9538114d6449: No such file or directory
cp: testBuildOrg//.git/objects/c5/9eb5ac206adac72f40ced41d6b4e511f482425: No such file or directory
cp: testBuildOrg//.git/objects/c5/a0b0a7832627291665a544d96d8851eb237826: No such file or directory
cp: testBuildOrg//.git/objects/c5/a416bea5cdb8f822ea8037febe485e5382ce44: No such file or directory
cp: testBuildOrg//.git/objects/c5/a647f5c44b66a6cc5ae8c09e25b2e0acd2d104: No such file or directory
cp: testBuildOrg//.git/objects/c5/a843613dfaeebd6a10c0a88d8154d285573569: No such file or directory
cp: testBuildOrg//.git/objects/c5/aa6f2406771911cb4583736e397bff58267015: No such file or directory
cp: testBuildOrg//.git/objects/c5/da174c31ab794107eacfa4b5016fe608a1df5f: No such file or directory
cp: testBuildOrg//.git/objects/c5/de1fe0b94e141bea7f96af0abb6231e9e52dd8: No such file or directory
cp: testBuildOrg//.git/objects/c5/e4aaabbc400607399fcf6f6d376914b43c782e: No such file or directory
cp: testBuildOrg//.git/objects/c5/e7b4b006ae612cbaf97e000933d6579043752a: No such file or directory
cp: testBuildOrg//.git/objects/c5/fe209f61a31104f1600dea692e1cadc1c288af: No such file or directory
cp: testBuildOrg//.git/objects/c6/036b23b666c6cca26836225bc30bf3876f0768: No such file or directory
cp: testBuildOrg//.git/objects/c6/042bc85b24d695102f661a6df447a1a4270b10: No such file or directory
cp: testBuildOrg//.git/objects/c6/0c7234f621ee7f4c072cb9b4018d0f4ac1bbd5: No such file or directory
cp: testBuildOrg//.git/objects/c6/17d8b785f65eebe0c94332046c75546aeadeeb: No such file or directory
cp: testBuildOrg//.git/objects/c6/1906d892d607b3ca7062a9d4ecf9a1e3aed4fc: No such file or directory
cp: testBuildOrg//.git/objects/c6/1ccf399a5762045afa2bd4f7382718f3bacbee: No such file or directory
cp: testBuildOrg//.git/objects/c6/1cdfc1431af9e4653a81b453a897fa36c48f13: No such file or directory
cp: testBuildOrg//.git/objects/c6/2adac95098c0c953f16b501cca1667a7dbab41: No such file or directory
cp: testBuildOrg//.git/objects/c6/361f302d16e399b3d9b70a62d881a9e8375b00: No such file or directory
cp: testBuildOrg//.git/objects/c6/36bab2f2c727d30aca2d0c2131598c0966c237: No such file or directory
cp: testBuildOrg//.git/objects/c6/36be68c6fa5a15896d7b1955f5c8d3ab18220d: No such file or directory
cp: testBuildOrg//.git/objects/c6/3da8b8e784172324c629b1d7370f7cce95d3a6: No such file or directory
cp: testBuildOrg//.git/objects/c6/43965aa91f0d37b1d586a1c00b487ddd2e8f65: No such file or directory
cp: testBuildOrg//.git/objects/c6/4773f92afa479b182f7a44b26db48eb7949630: No such file or directory
cp: testBuildOrg//.git/objects/c6/4812b46a4483f7f569768a10a79347580a261e: No such file or directory
cp: testBuildOrg//.git/objects/c6/4863969d3e7e8421af9ff9f74b3cbe8aacda78: No such file or directory
cp: testBuildOrg//.git/objects/c6/53784c819219b8a80b770ecc623b3c247982f1: No such file or directory
cp: testBuildOrg//.git/objects/c6/62d330cdcdf85f17a6316f0ba714ab59640a17: No such file or directory
cp: testBuildOrg//.git/objects/c6/67539b5d82e32e633ad141c1a2d128c648e5a6: No such file or directory
cp: testBuildOrg//.git/objects/c6/730306014ca2de0bc7de6a3feab08d0acac526: No such file or directory
cp: testBuildOrg//.git/objects/c6/76940abb9db52bd86a8faed0a6ee10bb0bfd3b: No such file or directory
cp: testBuildOrg//.git/objects/c6/7dbf7ae74f24e489302054e9e90607b79e875e: No such file or directory
cp: testBuildOrg//.git/objects/c6/869ef794c36e1f55391166a946965a18fe42b5: No such file or directory
cp: testBuildOrg//.git/objects/c6/8b021486b1e9db70f65903034ad318f51e87f7: No such file or directory
cp: testBuildOrg//.git/objects/c6/905303257885c09145af5cf2d2533e76caffdc: No such file or directory
cp: testBuildOrg//.git/objects/c6/94a000e9f24b161ca7f77bb15d79eb18ec2f2d: No such file or directory
cp: testBuildOrg//.git/objects/c6/94c6e56529e05029a2d3c0cbf9aa2af84dc741: No such file or directory
cp: testBuildOrg//.git/objects/c6/a43ad0bcbcca298b51c77f8fda23d68bb02135: No such file or directory
cp: testBuildOrg//.git/objects/c6/ab6b9576dced07d0bea59ed5ab361e56dcea2e: No such file or directory
cp: testBuildOrg//.git/objects/c6/b08f18639495be9375a197aabbf246dbae0cac: No such file or directory
cp: testBuildOrg//.git/objects/c6/b9ee994465ece4c3b44d70f1e57dee978aa2ff: No such file or directory
cp: testBuildOrg//.git/objects/c6/bc46387f7b1083d237156369e251857307ae49: No such file or directory
cp: testBuildOrg//.git/objects/c6/c3292262a6dd3467fbd715bfb423493e60a829: No such file or directory
cp: testBuildOrg//.git/objects/c6/c5e7d900a7e62b3dba9ef1e6009ebc60288448: No such file or directory
cp: testBuildOrg//.git/objects/c6/cf894eb9f77a8dc4853fd2c3baf46841ff0b91: No such file or directory
cp: testBuildOrg//.git/objects/c6/dc4bddb37d786fece40029afd71bf25a4a35e0: No such file or directory
cp: testBuildOrg//.git/objects/c6/dcde4c598d6a416d657c296c1cef165d7af8c9: No such file or directory
cp: testBuildOrg//.git/objects/c6/df49199acc7b6a38fe30fb9a736082642f94bb: No such file or directory
cp: testBuildOrg//.git/objects/c6/e9414e0d7352f69db4215dbda3ae6b63a19527: No such file or directory
cp: testBuildOrg//.git/objects/c6/eb4ee94b5fe4d567fae11f5627be3b39392e5b: No such file or directory
cp: testBuildOrg//.git/objects/c6/f7a00b10bb6782303d2a1637fc34f3babb5864: No such file or directory
cp: testBuildOrg//.git/objects/c6/f9a6b727036a2358a47f9f41b5bdb3a983f7c1: No such file or directory
cp: testBuildOrg//.git/objects/d3/9b56691f7d3dfdd96028b870aa4ac030bef440: No such file or directory
cp: testBuildOrg//.git/objects/d3/9db2cd1e3538378b95e500fb91b9d523043874: No such file or directory
cp: testBuildOrg//.git/objects/d3/a2e669a64ca5fea712d7e6d3e8bf4e0ee3b31b: No such file or directory
cp: testBuildOrg//.git/objects/d3/a5bacf99dabd992d7e1887587981f98fe8be87: No such file or directory
cp: testBuildOrg//.git/objects/d3/ab385599034125be25fe56acd6073efdb5d44e: No such file or directory
cp: testBuildOrg//.git/objects/d3/af4e054307c6f5e27468ea0565f36655c2a8bd: No such file or directory
cp: testBuildOrg//.git/objects/d3/b8d6186ce24668c2ea453a7121b078c8644921: No such file or directory
cp: testBuildOrg//.git/objects/d3/c5b5051e2b02662eed7dda6836dce2a5977d7a: No such file or directory
cp: testBuildOrg//.git/objects/d3/cc455e95d42ce4a3463f521a99c914b064719b: No such file or directory
cp: testBuildOrg//.git/objects/d3/dc9dace894d50122cb3c536633a465b01be757: No such file or directory
cp: testBuildOrg//.git/objects/d3/e4a8f5115523a25eab632637efb02e2e5074f8: No such file or directory
cp: testBuildOrg//.git/objects/d3/e82d01ec9cac437547d2443ec399e65ce789c9: No such file or directory
cp: testBuildOrg//.git/objects/d3/ea6cd4efbedfb4e17794b03ca09c3610b350f5: No such file or directory
cp: testBuildOrg//.git/objects/d3/ee6f54e4ca9ed618b4117585cc7c76dfddc391: No such file or directory
cp: testBuildOrg//.git/objects/d3/f25e5321a153ed60f3be5ecd32fa45f946fb21: No such file or directory
cp: testBuildOrg//.git/objects/d3/f8238008d5ba71e6967aaa824834347bf792c5: No such file or directory
cp: testBuildOrg//.git/objects/d3/fab72dc273e1ea5da9eebd85e77af6ef718dc1: No such file or directory
cp: testBuildOrg//.git/objects/d3/fc1ce7f72c3d79712ec058fb96974e2aa43d33: No such file or directory
cp: testBuildOrg//.git/objects/d4/94dde308fbe676517433be5c49c3f25df07b39: No such file or directory
cp: testBuildOrg//.git/objects/d4/95afa8c055c150577d687cdb7bbd06a853a410: No such file or directory
cp: testBuildOrg//.git/objects/d4/9a9c0d5e69c4a93910113c24374937fa03cc39: No such file or directory
cp: testBuildOrg//.git/objects/d4/9b4b7d4628db4ddecccae16e72354bd2f77458: No such file or directory
cp: testBuildOrg//.git/objects/d4/9df7ff15a87c287f04708e3d6835c09da11a57: No such file or directory
cp: testBuildOrg//.git/objects/d4/9fca551b753380632af633f519a1dc6f410e89: No such file or directory
cp: testBuildOrg//.git/objects/d4/a094c70a3531c3f4ccefbbe6df6a1d1e0f51b5: No such file or directory
cp: testBuildOrg//.git/objects/d4/a798b6a73c442f2049a5db3545b982e497770e: No such file or directory
cp: testBuildOrg//.git/objects/d4/ab88c92aabecf1c546fcc08c7235864b19b46d: No such file or directory
cp: testBuildOrg//.git/objects/d4/b645ddb0fdede4fcf075bb92c2a14254f3a99b: No such file or directory
cp: testBuildOrg//.git/objects/d4/c5a5718530764bca83d3f3aea22fea8ec5efc9: No such file or directory
cp: testBuildOrg//.git/objects/d4/cb97447dbd23d423af6a1855f8367a2e347fa5: No such file or directory
cp: testBuildOrg//.git/objects/d4/cce0c773410d80aa3166015226f91de54d2235: No such file or directory
cp: testBuildOrg//.git/objects/d4/cdc9b56e84a89301495cb86d6d347220f0c979: No such file or directory
cp: testBuildOrg//.git/objects/d4/cf9eda8732dc2be6fff338d929354433f9fed8: No such file or directory
cp: testBuildOrg//.git/objects/d4/dc0736653255e35938bd5fcd944cb128be604c: No such file or directory
cp: testBuildOrg//.git/objects/d4/dc3c7cfd073743d2fd9d830cb24bba1ff82799: No such file or directory
cp: testBuildOrg//.git/objects/d4/dccb12dba9385ed7ce42fe874f5a5bd550adc0: No such file or directory
cp: testBuildOrg//.git/objects/d4/e1fc68473123fa040777b72580437a54518ee7: No such file or directory
cp: testBuildOrg//.git/objects/d4/e37ffd24c8f76f1edecf76f8095245a54a41e9: No such file or directory
cp: testBuildOrg//.git/objects/d4/eb264222ce76eb05af13ce973b23a548bb5d28: No such file or directory
cp: testBuildOrg//.git/objects/d4/ec4082b8ff33c675c834df8d375cd9ab3c0085: No such file or directory
cp: testBuildOrg//.git/objects/d4/ee0f60c30a5901e5997a9b05221066a3210c6b: No such file or directory
cp: testBuildOrg//.git/objects/d4/f1961835037abbb03fe811d4950ca5bc2b83c3: No such file or directory
cp: testBuildOrg//.git/objects/d4/f5b037c7ddbcd8829f8fc1379a3416e5a05eb8: No such file or directory
cp: testBuildOrg//.git/objects/d4/f7a53aee90bf608d01fd5c1701f70d4661cafc: No such file or directory
cp: testBuildOrg//.git/objects/d4/fb8d488988c2dff00fa115f781e619b506f77f: No such file or directory
cp: testBuildOrg//.git/objects/d4/fc5c3a6dafd7419974e0f54fa8e0b180478919: No such file or directory
cp: testBuildOrg//.git/objects/d4/ff1d021a047f3e919084df2446287f3914b544: No such file or directory
cp: testBuildOrg//.git/objects/d5/b325635efe8a46e02d33e0d67aa23edd545519: No such file or directory
cp: testBuildOrg//.git/objects/d5/ca498f733217b50cdf62a795eab3311270a7f3: No such file or directory
cp: testBuildOrg//.git/objects/d5/e0b14f63abd5c665a197dda4ce30590eb58fc5: No such file or directory
cp: testBuildOrg//.git/objects/d5/e8e5c25442965ba804e16428e41e154c926304: No such file or directory
cp: testBuildOrg//.git/objects/d5/f248daf71f3567dba1aa41df8017c8f84f7c68: No such file or directory
cp: testBuildOrg//.git/objects/d5/f75693cd46de2fae98e7d24b6833ddc898feb1: No such file or directory
cp: testBuildOrg//.git/objects/d5/f98e09923d32df13c90392c106939b1e222083: No such file or directory
cp: testBuildOrg//.git/objects/d5/fd83c02970a67b758e4aa405f284b3a41f1824: No such file or directory
cp: testBuildOrg//.git/objects/d6/29c7e2f49ecc6fbf9875961df67e10ad77954c: No such file or directory
cp: testBuildOrg//.git/objects/d6/328170e7303b55a777952f84f854792bb9f93e: No such file or directory
cp: testBuildOrg//.git/objects/d6/3405fefec01375cc9e857f8cbc1cb1383825ba: No such file or directory
cp: testBuildOrg//.git/objects/d6/3d89671d2364074b956866fac59c59406baac9: No such file or directory
cp: testBuildOrg//.git/objects/d6/4a56457e4449ba0fd04cbf8b0213c93ac59a4f: No such file or directory
cp: testBuildOrg//.git/objects/d6/4debc7fa98496b84fd6e7e97196fdef5d88089: No such file or directory
cp: testBuildOrg//.git/objects/d6/522e184fef4e6d820064e8b4d27b46fca0f5e3: No such file or directory
cp: testBuildOrg//.git/objects/d6/55ce5d9b3f6c013ca95ca66a5239fd35f42974: No such file or directory
cp: testBuildOrg//.git/objects/d6/55d1c1cf432ea4757f920a86df38d4b0f99132: No such file or directory
cp: testBuildOrg//.git/objects/d6/5b018a8f741cb92ac1f339600c5fc0ab36b903: No such file or directory
cp: testBuildOrg//.git/objects/d6/61f99b1d2c56cb4e520d11ada95c79010069b5: No such file or directory
cp: testBuildOrg//.git/objects/d6/6bbb514153575745913d5ba72cc06676783fa6: No such file or directory
cp: testBuildOrg//.git/objects/d6/6d77df97f9f43b402644fd328c04319150e785: No such file or directory
cp: testBuildOrg//.git/objects/d6/9287b8af7bc57bfc311a7c41693f878919edac: No such file or directory
cp: testBuildOrg//.git/objects/d6/9380cb9efa9588cffd6808cf4f8edc3e87ae6d: No such file or directory
cp: testBuildOrg//.git/objects/d6/a00ded6dc05e23df61f48ea1820067d113aa7b: No such file or directory
cp: testBuildOrg//.git/objects/d6/a403b19151125c6e1324cc12ac10eac89150d3: No such file or directory
cp: testBuildOrg//.git/objects/d6/b4d25c92b8a5221fc4138342418fd3f395b3df: No such file or directory
cp: testBuildOrg//.git/objects/d6/bb2e86f0284da725d180043dbe273bcafac64b: No such file or directory
cp: testBuildOrg//.git/objects/d6/c551ae0ee3887000cb922a4eeb708d757f4495: No such file or directory
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
cp: testBuildOrg//.git/objects/d8/2bf34dfd1aab22dfe01b9f0ec4e6f79e16f0f9: No such file or directory
cp: testBuildOrg//.git/objects/d8/435c7e05319baff175cc2b346183250b3eee30: No such file or directory
cp: testBuildOrg//.git/objects/d8/45dfbb7133f780bdc3323cd1a5cdc4a925fe6e: No such file or directory
cp: testBuildOrg//.git/objects/d8/53bdd2ccf767dec886071ff643a66c54e7325e: No such file or directory
cp: testBuildOrg//.git/objects/d8/549496a18aafcb360b227b57abd310bb57143d: No such file or directory
cp: testBuildOrg//.git/objects/d8/5699ec38302d8e3ff94d771d3cbd98d4c4f5b7: No such file or directory
cp: testBuildOrg//.git/objects/d8/56c79c23b431c4b1612e55e4532d48e57f86a2: No such file or directory
cp: testBuildOrg//.git/objects/d8/5efba7b9a9686bbf98d8108cfe3e74d35e76f1: No such file or directory
cp: testBuildOrg//.git/objects/d8/60751d54f9a6d5ca7e3066e5ccabaac0015eb8: No such file or directory
cp: testBuildOrg//.git/objects/d8/610c63bdde14817961e5237f9588c9dfff5230: No such file or directory
cp: testBuildOrg//.git/objects/d8/702f102ea570fa51c7f146bfa911fc5527c96b: No such file or directory
cp: testBuildOrg//.git/objects/d8/70626ec2731f2b501a2b8c939aa0f7b4b4ec5a: No such file or directory
cp: testBuildOrg//.git/objects/d8/807588af775c2dcd75c87b8ac01218a672ef26: No such file or directory
cp: testBuildOrg//.git/objects/d8/80bacaff7549c17b50d83f9662055f368468a9: No such file or directory
cp: testBuildOrg//.git/objects/d8/865d939b3ebc30494650d529c7b9912654633b: No such file or directory
cp: testBuildOrg//.git/objects/d8/87d2a7a1334d1c43989954d78919e1fe66498c: No such file or directory
cp: testBuildOrg//.git/objects/d8/9834080220d78bf4de757c70156385dd68f5f3: No such file or directory
cp: testBuildOrg//.git/objects/d8/9f914a4a702c7ea6d4c5b4576b35cb1f6d9b0a: No such file or directory
cp: testBuildOrg//.git/objects/d8/cbdc292a23e79b1981d286e907b99d95384b91: No such file or directory
cp: testBuildOrg//.git/objects/d8/d84a56e7df43727748500da26adcc4ab9b643f: No such file or directory
cp: testBuildOrg//.git/objects/d8/dcb62522a3854742827bd25538338c32d424fc: No such file or directory
cp: testBuildOrg//.git/objects/d9/565afb5822012c6e115cf8c9a6f0d7931ecc07: No such file or directory
cp: testBuildOrg//.git/objects/d9/5ca6cd99e14b51347f1f55669e47ed85f98c34: No such file or directory
cp: testBuildOrg//.git/objects/d9/5e1379329b786b854d87ab06c91fe997d90d1c: No such file or directory
cp: testBuildOrg//.git/objects/d9/6908219282f61f86ed3cd8ff5d58010f3816a2: No such file or directory
cp: testBuildOrg//.git/objects/d9/713b0b94c4188e732cb2911429df6fe881f5de: No such file or directory
cp: testBuildOrg//.git/objects/d9/74a5ee4aafdef4bd0e49c00839a9ea0cae6da7: No such file or directory
cp: testBuildOrg//.git/objects/d9/78993c6b0eeb5fba833fb795241f1c6a713824: No such file or directory
cp: testBuildOrg//.git/objects/d9/8c1bfbb2cab94280c0d8eb17267898cb68a039: No such file or directory
cp: testBuildOrg//.git/objects/d9/8ebf929e74b35e1644af3b048cd05a52b126b9: No such file or directory
cp: testBuildOrg//.git/objects/d9/91742e6dcccf7414022fd7604b7b4f0624a441: No such file or directory
cp: testBuildOrg//.git/objects/d9/a242614f0ce83b2ffd99329a2a634847773f1f: No such file or directory
cp: testBuildOrg//.git/objects/d9/a7a0289f87e874efe071473ea3c1f5e7b4d7a6: No such file or directory
cp: testBuildOrg//.git/objects/d9/a9ea6a64baf1dc68d32905ddec15e480fd1969: No such file or directory
cp: testBuildOrg//.git/objects/d9/af8fab9f8ff26726d2c72c46a755dc79981cd7: No such file or directory
cp: testBuildOrg//.git/objects/d9/b2f924de3a7e3a097fb0bae3a68f7bdbefdda3: No such file or directory
cp: testBuildOrg//.git/objects/d9/ba61ec66d2042c79c17a52feb8cc453fb29db0: No such file or directory
cp: testBuildOrg//.git/objects/d9/bc174da82306a04296600618a1c2713d68c97a: No such file or directory
cp: testBuildOrg//.git/objects/d9/c0fd98edc2b4bbe28a60d029143b258609f0ff: No such file or directory
cp: testBuildOrg//.git/objects/d9/c47a307b895c81c74c8efac7b57ad20dc5b7c1: No such file or directory
cp: testBuildOrg//.git/objects/d9/da9facaa214982276e4e8ea279b43c8fcd45f6: No such file or directory
cp: testBuildOrg//.git/objects/d9/e3cb5ca09052fafb9aa3439e38ab39c35cddb7: No such file or directory
cp: testBuildOrg//.git/objects/d9/e8089a3e758b71c6207691cbb8033a6b81740d: No such file or directory
cp: testBuildOrg//.git/objects/d9/e9c6925b1ab471202fe786fa4b7dadf3f38d22: No such file or directory
cp: testBuildOrg//.git/objects/d9/f0c2d1d2a36a7cfe291cfafd76732ef751343a: No such file or directory
cp: testBuildOrg//.git/objects/d9/fcfd4cd9efd7470d78a2d1d9df21e77c888c35: No such file or directory
cp: testBuildOrg//.git/objects/da/0ca6662665977c3182ed9b01fee40b1001cb4e: No such file or directory
cp: testBuildOrg//.git/objects/da/11a658f29d035d7d01a2a464a420f87bc86d52: No such file or directory
cp: testBuildOrg//.git/objects/da/13cead0cd00946f9c293250535370b2d587f8f: No such file or directory
cp: testBuildOrg//.git/objects/da/1550eff58628fe90da6faa214c03cc1f02b5bd: No such file or directory
cp: testBuildOrg//.git/objects/da/15660e02a666f0548833d76f9542d4ee42f016: No such file or directory
cp: testBuildOrg//.git/objects/da/1ad14a703907c9a934dd1d39099024b9cbccc0: No such file or directory
cp: testBuildOrg//.git/objects/da/20ab9487295efdf3767570019cc3ca7d424c78: No such file or directory
cp: testBuildOrg//.git/objects/da/2d2e24e20bd3892fb7bfad8fa6c620832aa0f4: No such file or directory
cp: testBuildOrg//.git/objects/da/2f398f240826178ad6af43da5631e2c0b15cc5: No such file or directory
cp: testBuildOrg//.git/objects/da/31180bce78e047d513757e817fd18fb28329b8: No such file or directory
cp: testBuildOrg//.git/objects/da/35147b6e96fda8847efd4a7bc797e28eaea92d: No such file or directory
cp: testBuildOrg//.git/objects/da/36bd138501ccbae279a537425fc7bd2975ec90: No such file or directory
cp: testBuildOrg//.git/objects/da/397594c6d2c188988e567aa0017fd2a8f3a290: No such file or directory
cp: testBuildOrg//.git/objects/da/3dfe2ced4aca1fda7ace26038ef3a6fd9b677d: No such file or directory
cp: testBuildOrg//.git/objects/da/4292227096c1fc7a60086bae03fc9876827a3b: No such file or directory
cp: testBuildOrg//.git/objects/da/464680fca1d469473c7b399d16c8ac11e45649: No such file or directory
cp: testBuildOrg//.git/objects/da/4b306d8fba99b58ab10872c44b683794696e7b: No such file or directory
cp: testBuildOrg//.git/objects/da/51a8409d2e3fb22e7a893b044fc0d504b4c4b7: No such file or directory
cp: testBuildOrg//.git/objects/da/5901fb4e12750f06aac80a708ae8073d662c1c: No such file or directory
cp: testBuildOrg//.git/objects/da/5b66a62470e510b14bf841e70b4dba8086bacb: No such file or directory
cp: testBuildOrg//.git/objects/da/5c4139e7c7b6c6a1de664de194704615feee78: No such file or directory
cp: testBuildOrg//.git/objects/da/5e5c0e2464561be49a8fe89c04bf5988b2e109: No such file or directory
cp: testBuildOrg//.git/objects/da/5fa6f80f4ba0d47345d5b428483fe36c57ccc2: No such file or directory
cp: testBuildOrg//.git/objects/da/705e01cad9d501f0ecf5f162e28a6bd11d9a1d: No such file or directory
cp: testBuildOrg//.git/objects/da/7d8125e24833f23d1c14f2c8ae055da9f8589d: No such file or directory
cp: testBuildOrg//.git/objects/da/8bde4d913e73b80ce7800a281b3c4cdac5cc07: No such file or directory
cp: testBuildOrg//.git/objects/da/928ee721c8395cf5bd8ff51c97ee3c04991555: No such file or directory
cp: testBuildOrg//.git/objects/da/95e86ad52dcead5b0f6a36de8a3ce30cb63500: No such file or directory
cp: testBuildOrg//.git/objects/da/967d722e0a21717bd27d12c7d0330cf6853819: No such file or directory
cp: testBuildOrg//.git/objects/da/9a3db5e12dc0b1687588fe5862216bf190fb2e: No such file or directory
cp: testBuildOrg//.git/objects/da/a3dc7c90dfcb1ad3b43c8835a7b310a7195cd4: No such file or directory
cp: testBuildOrg//.git/objects/da/aa6df6f85a1e52b28b35d468d4ebb834152d22: No such file or directory
cp: testBuildOrg//.git/objects/da/b827d2fa6d67add3e23053d399733878aa6d87: No such file or directory
cp: testBuildOrg//.git/objects/da/bc443fc95be32868ef6e75bdfd8c31b9e3360e: No such file or directory
cp: testBuildOrg//.git/objects/da/bd1431ea6a8d966afab48e320e31f090756217: No such file or directory
cp: testBuildOrg//.git/objects/da/bf17635382ce102555ab873c8476e3b7d62144: No such file or directory
cp: testBuildOrg//.git/objects/da/c64a60beb28563ed014d897d19f722d0d43fff: No such file or directory
cp: testBuildOrg//.git/objects/da/c956d156282bac83860b6b704ca35d2582fcf1: No such file or directory
cp: testBuildOrg//.git/objects/da/cf8b2a39afdd3146387f6c0259134279ae3a02: No such file or directory
cp: testBuildOrg//.git/objects/da/d2588dfc50b6e6f0b7b66687c4be6832505bd5: No such file or directory
cp: testBuildOrg//.git/objects/da/d2d1abfdbf4f6190337d19ea54f4423e534b5d: No such file or directory
cp: testBuildOrg//.git/objects/da/d8e777c31db941c3d3e9767b0f28817019058d: No such file or directory
cp: testBuildOrg//.git/objects/da/d90add640a1ee0cd6c79cff12a2091e901a90e: No such file or directory
cp: testBuildOrg//.git/objects/da/ddc4543b79f3ee5c9dcf459c2a883e8d4cb5fe: No such file or directory
cp: testBuildOrg//.git/objects/da/e3d12569c7c10fad9c47480b971ef2dd9759a4: No such file or directory
cp: testBuildOrg//.git/objects/da/e61b151ae56cdd953314b54503c472e9c97fb4: No such file or directory
cp: testBuildOrg//.git/objects/da/ed2f69a41170854691c3cece0ce6bec6886de0: No such file or directory
cp: testBuildOrg//.git/objects/da/f004ae9c04172299a9e2d3c935ab462d14f531: No such file or directory
cp: testBuildOrg//.git/objects/da/fc02cfc0df5321a99ac2d96477e2b910b2a8c8: No such file or directory
cp: testBuildOrg//.git/objects/db/2972d254b8578aad64e9a344374cf7752b6298: No such file or directory
cp: testBuildOrg//.git/objects/db/3a0b19ae8405f7c47fea63c81c1b4740862ef4: No such file or directory
cp: testBuildOrg//.git/objects/db/3b6c26020b7885fd4827c5aa489238264af79d: No such file or directory
cp: testBuildOrg//.git/objects/db/4595a1671ef7b317004387e638d5c274a4249f: No such file or directory
cp: testBuildOrg//.git/objects/db/487d4c2138385cb7955a5d42dc7e8419771d82: No such file or directory
cp: testBuildOrg//.git/objects/db/4d59f637061467c3d4ef33814d1c5f721f98c1: No such file or directory
cp: testBuildOrg//.git/objects/db/4ef9eeb49f28ded00ec35f103b7ba65b155136: No such file or directory
cp: testBuildOrg//.git/objects/db/54f3309759570f321770079ad75c116363d8f7: No such file or directory
cp: testBuildOrg//.git/objects/db/58256bc93a8fa03f7ef337d342d39e6e2ef930: No such file or directory
cp: testBuildOrg//.git/objects/db/5e95528143a41b805469c8271ad95fa2ff98bb: No such file or directory
cp: testBuildOrg//.git/objects/db/5e9b54d7851be9e1656c9f5c27305d4318a96c: No such file or directory
cp: testBuildOrg//.git/objects/db/63bb47979c565df3c526cca2922b0280784a40: No such file or directory
cp: testBuildOrg//.git/objects/db/6a1787faee977579e2b5623d0bcc7d739ab08d: No such file or directory
cp: testBuildOrg//.git/objects/db/705277a40576ba274eb271c5b9f83cf617e875: No such file or directory
cp: testBuildOrg//.git/objects/db/77e456c1993a9a087fea1e5fe249aba61b0e05: No such file or directory
cp: testBuildOrg//.git/objects/db/78ea6ceaee39664eb05ddd76a3993e0ca01b3b: No such file or directory
cp: testBuildOrg//.git/objects/db/7983afe09262c958425b01c3ceca4b1e4a709b: No such file or directory
cp: testBuildOrg//.git/objects/db/7d2b0d7e9342c1ff09d304f9b6d5d6d9d89da4: No such file or directory
cp: testBuildOrg//.git/objects/db/880429025dadd1f937255d25aad7101604bd1e: No such file or directory
cp: testBuildOrg//.git/objects/db/96a3de5f06f9b0d4cf1c1cf2f0942cde0e3856: No such file or directory
cp: testBuildOrg//.git/objects/db/993c0e5385b1d0b7e4bfe05981cf8677a51bb3: No such file or directory
cp: testBuildOrg//.git/objects/db/9a2b34f3951b4adc5940d3afad4eacee056375: No such file or directory
cp: testBuildOrg//.git/objects/db/a5cce727a529793fdbb103d25550b6bfc3973d: No such file or directory
cp: testBuildOrg//.git/objects/db/b75a76dbfb2e9cfb065996af3e614873a9de4e: No such file or directory
cp: testBuildOrg//.git/objects/db/bd5a8122c60bdbc05bed14d63ae734a6d456f5: No such file or directory
cp: testBuildOrg//.git/objects/db/c0f23d14f24f7b6cb4503dadac4c2b7a941736: No such file or directory
cp: testBuildOrg//.git/objects/db/cc44d5a899fed161bc54960b76b8e3be4326d9: No such file or directory
cp: testBuildOrg//.git/objects/db/d6e4879f893975a78d77c904b55e5065da0326: No such file or directory
cp: testBuildOrg//.git/objects/db/d76473a55944651c04ce1ebf74862db209f93c: No such file or directory
cp: testBuildOrg//.git/objects/db/da3c231347b5e7e4f03591e16ac0fa589a35cb: No such file or directory
cp: testBuildOrg//.git/objects/db/dc33057fe324eb590a2bc2f84e1add72fbf1a6: No such file or directory
cp: testBuildOrg//.git/objects/db/de953ccf85b9512e6476716a01d25000d1ef69: No such file or directory
cp: testBuildOrg//.git/objects/db/e4205979ede0b2a67e5301ba382543c0ad75b5: No such file or directory
cp: testBuildOrg//.git/objects/db/e49705397bf30a25f85c9c2f85af25a16f3f21: No such file or directory
cp: testBuildOrg//.git/objects/db/f0543cb4b52c6ef362bde4f2a28486a332b5f1: No such file or directory
cp: testBuildOrg//.git/objects/db/f8a2a8b611c1d0481d12f2b7882dcb8c5e37f7: No such file or directory
cp: testBuildOrg//.git/objects/db/f9ecef590a6aa6e3abb2e38a340b5f5f276e2f: No such file or directory
cp: testBuildOrg//.git/objects/db/fc29feba98abef599d2f146558140279b86db7: No such file or directory
cp: testBuildOrg//.git/objects/db/fc84e27438d1fdba4c7066ed5f662520e66451: No such file or directory
cp: testBuildOrg//.git/objects/db/fdde9d05c4142cdc6b7212dd0ea7fb02bf5ac9: No such file or directory
cp: testBuildOrg//.git/objects/dc/1e9cf1a65d11d994ba763225bead35ece6a2b6: No such file or directory
cp: testBuildOrg//.git/objects/dc/276751d544073f8f7c3381659cf2b18f991cf4: No such file or directory
cp: testBuildOrg//.git/objects/dc/28ffa9c75a00d8f2393775ca5761b1474f5fdf: No such file or directory
cp: testBuildOrg//.git/objects/dc/32d9ff7e682416aee60eff242c133ee5955f2f: No such file or directory
cp: testBuildOrg//.git/objects/dc/40973b52dd67220fbc87ad5b75c14c3bc382e4: No such file or directory
cp: testBuildOrg//.git/objects/dc/41c998cab8605a30f6a2ee1a30b81f25c8a3ad: No such file or directory
cp: testBuildOrg//.git/objects/dc/466a1910493405bd1f5199a1d829badfac0972: No such file or directory
cp: testBuildOrg//.git/objects/dc/5753c7264f40bd098b023513a8514a3cd41d82: No such file or directory
cp: testBuildOrg//.git/objects/dc/5c1577ad4e26182af437ae3860bd6d104a8bac: No such file or directory
cp: testBuildOrg//.git/objects/dc/5d449ad0be1211f8b16e224c1b76e884caf2cf: No such file or directory
cp: testBuildOrg//.git/objects/dc/5dfe5604b7553824b07b26bd524a8d545b3fa1: No such file or directory
cp: testBuildOrg//.git/objects/dc/60ee81e9d836c5b74c2b1498deb025544c9d79: No such file or directory
cp: testBuildOrg//.git/objects/dc/650e80583a7806304fe62ec3e9f2b821ac08ec: No such file or directory
cp: testBuildOrg//.git/objects/dc/6bdd3de11c43e039424bb59867723cf480f5de: No such file or directory
cp: testBuildOrg//.git/objects/dc/6dd83fbaf989514ad5309d80e7a5534e850783: No such file or directory
cp: testBuildOrg//.git/objects/dc/6f5113bd959769a51a2bf70034affbd3c5f9b4: No such file or directory
cp: testBuildOrg//.git/objects/dc/767481291db1cc078ec1fd99043260fc978dd1: No such file or directory
cp: testBuildOrg//.git/objects/dc/7f8ed3b287dc4f0f83d405929e4d3f9c861366: No such file or directory
cp: testBuildOrg//.git/objects/dc/87dab69db8e32d8dcfa8bc33d387ff603b0916: No such file or directory
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
cp: testBuildOrg//.git/objects/dc/cdeed448e2de77e1565fddf21eeb6718997314: No such file or directory
cp: testBuildOrg//.git/objects/dc/ce35e5980e7e5c7dbc724d103036dcc0fc173b: No such file or directory
cp: testBuildOrg//.git/objects/dc/cebd765a2458f594f8d4dca79ef45dc921b2c8: No such file or directory
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
cp: testBuildOrg//.git/objects/e6/f3e7f1ae6ef07093601a8db569fe539b2bfe53: No such file or directory
cp: testBuildOrg//.git/objects/e6/f5c3bb1b488e9d1693669cfe7236ff9a71edfb: No such file or directory
cp: testBuildOrg//.git/objects/e6/fc3fe46627a556dd4af03ceaf228cbfc897656: No such file or directory
cp: testBuildOrg//.git/objects/e7/55149fc30ebe4fe6427f050e31d44a3e706fcd: No such file or directory
cp: testBuildOrg//.git/objects/e7/68c36f31c71857235890ab13284b9e84da110a: No such file or directory
cp: testBuildOrg//.git/objects/e7/70cf534df05d2ca2a07d828bb672fc501cf4a1: No such file or directory
cp: testBuildOrg//.git/objects/e7/7e79b78cee1d5bf88803378942d3d392bf9707: No such file or directory
cp: testBuildOrg//.git/objects/e7/7f590d6a29418eacfc0bb3334381fbe293ab7d: No such file or directory
cp: testBuildOrg//.git/objects/e7/7feb90483b37a046bc9776037efd735bba4667: No such file or directory
cp: testBuildOrg//.git/objects/e7/827ed0f8c280c04423ef61f0959263c8ee351d: No such file or directory
cp: testBuildOrg//.git/objects/e7/8449732103171680e4d3a88cea122628905c3c: No such file or directory
cp: testBuildOrg//.git/objects/e7/851c77d5b24d3dfca7154eb9ecf8050d0287fc: No such file or directory
cp: testBuildOrg//.git/objects/e7/8531a7dbd05ab8cea0b5efd7c3c2e4534bda35: No such file or directory
cp: testBuildOrg//.git/objects/e7/887af3bc62eb3427099af8e88cf81f5d0f946a: No such file or directory
cp: testBuildOrg//.git/objects/e7/94d2c74aace0eb8f092b4ea22e9a3af0091d2d: No such file or directory
cp: testBuildOrg//.git/objects/e7/976687c8762538eb470608896b5a86d9620733: No such file or directory
cp: testBuildOrg//.git/objects/e7/9c63f6a2d6f0c23551b03f1ecdaf77c8c515df: No such file or directory
cp: testBuildOrg//.git/objects/e7/a39429928c356a6a1e682def02c196b9e5ac6b: No such file or directory
cp: testBuildOrg//.git/objects/e7/ac70748599202f2c6410567e524ac2cd2bc3cc: No such file or directory
cp: testBuildOrg//.git/objects/e7/ad4e9067beb24f99054e5601ae7d26f66e7e4c: No such file or directory
cp: testBuildOrg//.git/objects/e7/c7035793dc0b5ac4aca72564321cf16927f98b: No such file or directory
cp: testBuildOrg//.git/objects/e7/cbba2da5be2dd2daa207fce2414582049eb181: No such file or directory
cp: testBuildOrg//.git/objects/e7/cbcf4d664d76766b1a95c80ce6ec342fd71ba7: No such file or directory
cp: testBuildOrg//.git/objects/e7/d2ee98e7118fa55b0af4ac7c84dbc53c2f3429: No such file or directory
cp: testBuildOrg//.git/objects/e7/da16f10f61082504deff88a44ecf9a88be2d71: No such file or directory
cp: testBuildOrg//.git/objects/e7/dac66113de4d31c2e87fb7221656ac4fcc270d: No such file or directory
cp: testBuildOrg//.git/objects/e7/ddc82d5a2d6ba5f6de92238cb33af115f65be6: No such file or directory
cp: testBuildOrg//.git/objects/e7/e025821330fdc4dae4d0b1279211cc334ca0d2: No such file or directory
cp: testBuildOrg//.git/objects/e7/e4b31419ae5104e6b76d51fce7d36af3732e89: No such file or directory
cp: testBuildOrg//.git/objects/e7/ec47610023418495dc4a45af027f35b82a867d: No such file or directory
cp: testBuildOrg//.git/objects/e7/f12209897ce3ef5bdf2d99d711383e1b1c20a5: No such file or directory
cp: testBuildOrg//.git/objects/e7/f2087a3ce6b52c54b98a624c70fdac0e41f836: No such file or directory
cp: testBuildOrg//.git/objects/e7/f5ec9a0b1a97ead60a1e752dc19a284e1e8eac: No such file or directory
cp: testBuildOrg//.git/objects/e7/f82f51df0e39f29f05910675ec83165629420a: No such file or directory
cp: testBuildOrg//.git/objects/e7/f9a3d7c09d8c34404a37900d9cc66b07e37f86: No such file or directory
cp: testBuildOrg//.git/objects/e8/40bd5b3eabeea9fedb00de4d808245306c19d0: No such file or directory
cp: testBuildOrg//.git/objects/e8/40c08a0e8dcd252f634fbb49a8f3f51fa4e460: No such file or directory
cp: testBuildOrg//.git/objects/e8/52424495615734a30f9f392fa8785453975f42: No such file or directory
cp: testBuildOrg//.git/objects/e8/55954f265e203b4cb0b9b35684a8bb0713f65e: No such file or directory
cp: testBuildOrg//.git/objects/e8/5a29ff540d890e87b5d2fde805c35d8d51f39a: No such file or directory
cp: testBuildOrg//.git/objects/e8/5d8ffd8f593b7a92e2f83a03822ad431f028a6: No such file or directory
cp: testBuildOrg//.git/objects/e8/61f467ae34b23b51defda74cbe10a09afa7ea7: No such file or directory
cp: testBuildOrg//.git/objects/e8/628d8c8eb1a7e10bdbc58e2d85a9060c8e4392: No such file or directory
cp: testBuildOrg//.git/objects/e8/6945b29d7c2012b81293d40c01914c5180561d: No such file or directory
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
cp: testBuildOrg//.git/objects/eb/ccdad8a787693fe5e272160d8aad853a3acf2b: No such file or directory
cp: testBuildOrg//.git/objects/eb/cceaad83400c62f830a0d6ca19641cb26df176: No such file or directory
cp: testBuildOrg//.git/objects/eb/d1fc8fbe6656a13ee7f86ac51c2826228deb65: No such file or directory
cp: testBuildOrg//.git/objects/eb/d2d0cb22a4670a2c34fa990bfefa6ad4f8dea2: No such file or directory
cp: testBuildOrg//.git/objects/eb/e23a83d010af89d58fca6883791ef131065bdf: No such file or directory
cp: testBuildOrg//.git/objects/eb/f83383da5cad23614854a196622ccb20e6e866: No such file or directory
cp: testBuildOrg//.git/objects/eb/fa37ec52e457482fe740cdf8ef2c6a58b7ea2f: No such file or directory
cp: testBuildOrg//.git/objects/ec/6dd40bd1cb68bf3263431b78e2deb56f6c3dff: No such file or directory
cp: testBuildOrg//.git/objects/ec/711b89d6a8bec94a4b3c8492c5f70d3f39c317: No such file or directory
cp: testBuildOrg//.git/objects/ec/7c4335215f78f6fa2aeb1e2f6cb32ab139fb08: No such file or directory
cp: testBuildOrg//.git/objects/ec/85a0fe8a407d82853fdecac16c621de9f7ac38: No such file or directory
cp: testBuildOrg//.git/objects/ec/881029a569be5119e4b7f4ec123bb60cbbb087: No such file or directory
cp: testBuildOrg//.git/objects/ec/96559bf0a0ce761a916119892f67e6f2316674: No such file or directory
cp: testBuildOrg//.git/objects/ec/96726677f8623fcfb16bd4f56174d785caa852: No such file or directory
cp: testBuildOrg//.git/objects/ec/9a1bcfdc056ae711e970d6889b26821126eb1a: No such file or directory
cp: testBuildOrg//.git/objects/ec/9cdb198558a09eb59c00145bbb5845ba2ff4b4: No such file or directory
cp: testBuildOrg//.git/objects/ec/a0f5d3fe92df0ab0d821dc078afddc41c01085: No such file or directory
cp: testBuildOrg//.git/objects/ec/a6a3dd63f0afe9900073b78eac13fc8129faf7: No such file or directory
cp: testBuildOrg//.git/objects/ec/ab7e797e0581d1cc3c9dcdc6dc5cce6e5a363e: No such file or directory
cp: testBuildOrg//.git/objects/ec/abc6e36218d21f6a6489fb7c2975c753d257d8: No such file or directory
cp: testBuildOrg//.git/objects/ec/add4622ccf37ecf42828e63ba0724d992bfd67: No such file or directory
cp: testBuildOrg//.git/objects/ec/aeebfb96b45640953707f90afd7053afd16876: No such file or directory
cp: testBuildOrg//.git/objects/ec/b0a6c95e42fdeacce06fe5de762e6b73cf1f04: No such file or directory
cp: testBuildOrg//.git/objects/ec/b70559119858cb0c77c825307131ae106463e0: No such file or directory
cp: testBuildOrg//.git/objects/ec/c02ba818a50918ad50daf510a2267c7717692c: No such file or directory
cp: testBuildOrg//.git/objects/ec/c172f8accbd987a44ba7bd20653a7a5bf01243: No such file or directory
cp: testBuildOrg//.git/objects/ec/c292989308704d72a518182f8a884eb364ca1c: No such file or directory
cp: testBuildOrg//.git/objects/ec/ca6427c79821abe44d53277c60d501c37c0f6e: No such file or directory
cp: testBuildOrg//.git/objects/ec/d24ecc8b13397522d8bdedcd9604f761390562: No such file or directory
cp: testBuildOrg//.git/objects/ec/d2a50c41695a0cf51c1af9548288ddcf57236e: No such file or directory
cp: testBuildOrg//.git/objects/ec/e7d21a9d7a89e13084632eca1a16c47faf1901: No such file or directory
cp: testBuildOrg//.git/objects/ec/ef3767fb0c0f37f84e59277b74dc566083297c: No such file or directory
cp: testBuildOrg//.git/objects/ec/f0efe1969a23d2bc8bbf12f050808f28d6cbac: No such file or directory
cp: testBuildOrg//.git/objects/ec/fcff2da29aefab6833ca4145d3d5633511eab2: No such file or directory
cp: testBuildOrg//.git/objects/ec/fe20b9d80550038d1840d18bd900b1491d3994: No such file or directory
cp: testBuildOrg//.git/objects/ed/f7056a5093e7daae2fb8a5edf6d2276ef8354a: No such file or directory
cp: testBuildOrg//.git/objects/ed/fd02d385f599cba5015bd69c83bd08c7a9f86a: No such file or directory
cp: testBuildOrg//.git/objects/ed/fde8d764416569384e1ed57ac38e0c99c9a6af: No such file or directory
cp: testBuildOrg//.git/objects/ee/3d83f211d0c23900dda2d2bd0959113767ed85: No such file or directory
cp: testBuildOrg//.git/objects/ee/3e1ff2f2da382134fd5b9caf204fcd3638bfc0: No such file or directory
cp: testBuildOrg//.git/objects/ee/cc7bf6dba1dfe3c3cebca67afebe7ef31da0ee: No such file or directory
cp: testBuildOrg//.git/objects/ee/d202a70f2735184c61d4833c86db128adcd692: No such file or directory
cp: testBuildOrg//.git/objects/ee/d489d883ff27e0f197c8c9874e823e70457d20: No such file or directory
cp: testBuildOrg//.git/objects/ee/d9bf4e90a56680ea2e6515807c18fb159a01ae: No such file or directory
cp: testBuildOrg//.git/objects/ee/e2f55fbd017016faa5c10caed28534f522b798: No such file or directory
cp: testBuildOrg//.git/objects/ee/e3e379d73d47c6a54ffe3c031ddcc5733f9cdb: No such file or directory
cp: testBuildOrg//.git/objects/ee/e442fe337d962230fa442befac627905f7f1ae: No such file or directory
cp: testBuildOrg//.git/objects/ee/e947613402db996904d5f97ff15dab1186257f: No such file or directory
cp: testBuildOrg//.git/objects/ee/ecc562d2703fef2177778da61b36f9c6e53b3d: No such file or directory
cp: testBuildOrg//.git/objects/ee/eebf9c8a1fa2bf38c8c4a00f0cf85fc1da69bf: No such file or directory
cp: testBuildOrg//.git/objects/ee/f5698fd6b8160c3c73e8d13f8639f2456fb5d0: No such file or directory
cp: testBuildOrg//.git/objects/ee/f6357daa22deda4e2da7e41e9d36d61e380e2a: No such file or directory
cp: testBuildOrg//.git/objects/ee/f7ba6b83e480c496bfd0f99f7d8c1813dd6526: No such file or directory
cp: testBuildOrg//.git/objects/ee/fc425b829f8d83d5cb28c0127fa3afc1c0762c: No such file or directory
cp: testBuildOrg//.git/objects/ef/181391a39281f85860f50a0a3f16b211e06181: No such file or directory
cp: testBuildOrg//.git/objects/ef/2028f0e98fb93a0edcd83a1c7fee030788a8de: No such file or directory
cp: testBuildOrg//.git/objects/ef/25e7bbeabb78dfe15c84712dfb6e476998415f: No such file or directory
cp: testBuildOrg//.git/objects/ef/317fc2d800988ba1aad688683228982aed3300: No such file or directory
cp: testBuildOrg//.git/objects/ef/367727f57d42d193c7a8b27ce69b002e3094c1: No such file or directory
cp: testBuildOrg//.git/objects/ef/376cab69783c8588a09fefc135d1f4c3ec9822: No such file or directory
cp: testBuildOrg//.git/objects/ef/4b5cc3c9898966a9ca4cff21161211cbbb033f: No such file or directory
cp: testBuildOrg//.git/objects/ef/4c0440931f0cf5c2dcc20cb8b0f13172f95049: No such file or directory
cp: testBuildOrg//.git/objects/ef/585f95fea83ae938a7e8a80f7d0d16471ce328: No such file or directory
cp: testBuildOrg//.git/objects/ef/5a87546adbf4c9847b8363160a2f770a185d32: No such file or directory
cp: testBuildOrg//.git/objects/ef/5d5927d423581b53a4d238a4fcd80e627a9bdf: No such file or directory
cp: testBuildOrg//.git/objects/ef/5e07d7bbf79d06717b55f7d10b9c47fc0118fc: No such file or directory
cp: testBuildOrg//.git/objects/ef/6c11086078f8a30fa8fc82343f73c5e0f19b84: No such file or directory
cp: testBuildOrg//.git/objects/ef/6ce6b7405dbd0d124b51d0c7ff170487c4d69a: No such file or directory
cp: testBuildOrg//.git/objects/ef/7e01b63db7521236adb994f4af79d253aaeb21: No such file or directory
cp: testBuildOrg//.git/objects/ef/84b907870533469b527bc29d719b59daa499f7: No such file or directory
cp: testBuildOrg//.git/objects/ef/86cdf9eb1478614f0c52fefe33618438c4a51c: No such file or directory
cp: testBuildOrg//.git/objects/ef/86ce118a3d92aeafb6b88c523284610a956f08: No such file or directory
cp: testBuildOrg//.git/objects/ef/9d3028f803cc03166a74d3c0dd8f6802f6e1cf: No such file or directory
cp: testBuildOrg//.git/objects/ef/9f1b546d15087cf6215735ce9e385742322031: No such file or directory
cp: testBuildOrg//.git/objects/ef/a363933c63a6c25b7c50d190c34e8ddb347106: No such file or directory
cp: testBuildOrg//.git/objects/ef/a943f6e327dc6d4a635251b5dbc810987d9da6: No such file or directory
cp: testBuildOrg//.git/objects/ef/a97a0e6bd84a2292d4b502fb0232cd6d403ab6: No such file or directory
cp: testBuildOrg//.git/objects/ef/aeb79882188ac0b8b1b0779830da3b332cc476: No such file or directory
cp: testBuildOrg//.git/objects/ef/b53dc76bae70d6088235ddf44749273bfa1c3b: No such file or directory
cp: testBuildOrg//.git/objects/ef/b57c159a84808487eebcb8b7c13d09f197ff62: No such file or directory
cp: testBuildOrg//.git/objects/ef/d00e994553154b5203beaba0ba77795af68fc6: No such file or directory
cp: testBuildOrg//.git/objects/ef/d74e01608eb6f8467b9fbc7d1ddcdd12fc414b: No such file or directory
cp: testBuildOrg//.git/objects/ef/e3d97f01ad33749a29a13ae40f7fe5e27ccc35: No such file or directory
cp: testBuildOrg//.git/objects/ef/e9f818c2e872f552a76b7a012059353b32a7bc: No such file or directory
cp: testBuildOrg//.git/objects/ef/eb2bc5008b3cda814f52e6ccbb602438c43d95: No such file or directory
cp: testBuildOrg//.git/objects/ef/f301f60c0171fe39974ea615d020795789cb7f: No such file or directory
cp: testBuildOrg//.git/objects/f0/337cfb8f436375b87a5c507ecb80714f7f0b62: No such file or directory
cp: testBuildOrg//.git/objects/f0/38950613d6686bebb596b8312d5bb156914084: No such file or directory
cp: testBuildOrg//.git/objects/f0/4538c7b0eb93cb9dfc4180944c0865cb35e1aa: No such file or directory
cp: testBuildOrg//.git/objects/f0/49b2a6522e0c5951afb1ffe4cc6cc3b774fb1d: No such file or directory
cp: testBuildOrg//.git/objects/f0/540aea31fd2c9af6b5a4af5cd623d9d49fd7f6: No such file or directory
cp: testBuildOrg//.git/objects/f0/5f2384290d6cc9a705de909c37c220563caff8: No such file or directory
cp: testBuildOrg//.git/objects/f0/603635496d836370bcd264dcd85d802f333561: No such file or directory
cp: testBuildOrg//.git/objects/f0/6b65e154b1f85ff8336010f7bc070f45786665: No such file or directory
cp: testBuildOrg//.git/objects/f0/71f04a0882852ad6281c24970248c5ebb50172: No such file or directory
cp: testBuildOrg//.git/objects/f0/8e18774e95195cfd62b8014c332bc528679f9e: No such file or directory
cp: testBuildOrg//.git/objects/f0/9082b6c4057489f576aa6a76bd7d8749d39ff7: No such file or directory
cp: testBuildOrg//.git/objects/f0/90ed83dc4ae928269d58c89180ab819aa7c3d5: No such file or directory
cp: testBuildOrg//.git/objects/f0/a0fb8c99fc171ac3fefca55771ebdcd543af42: No such file or directory
cp: testBuildOrg//.git/objects/f0/a5bc26e6c59be8fd225c49c67b2faed46a790b: No such file or directory
cp: testBuildOrg//.git/objects/f0/ac1a845b63280d5f080949be7ab646c5c6253b: No such file or directory
cp: testBuildOrg//.git/objects/f0/af70021ee2b5e98bc90b9e741cf7259579af1a: No such file or directory
cp: testBuildOrg//.git/objects/f0/b07ac2146de4ab26df6cb5e7aa07e782fb1643: No such file or directory
cp: testBuildOrg//.git/objects/f0/bff81200feaeec3c4a95b97cbe66ca2cc3f821: No such file or directory
cp: testBuildOrg//.git/objects/f0/c00e2c2b29e966e4bbc8365f72fbaf16194943: No such file or directory
cp: testBuildOrg//.git/objects/f0/cb55f9fb8dc3b6af9caed33416b7bd3bc3936e: No such file or directory
cp: testBuildOrg//.git/objects/f0/d5e108b260dd103560c06cef1dde3bc0569742: No such file or directory
cp: testBuildOrg//.git/objects/f0/d6a2f5345e0372f70acc304a16918c9077d1bd: No such file or directory
cp: testBuildOrg//.git/objects/f0/e2ea38a6877f99f272cb8019ecc299a7dade2a: No such file or directory
cp: testBuildOrg//.git/objects/f0/f425de81f18b5f9ed822e02321c68f5ec81af0: No such file or directory
cp: testBuildOrg//.git/objects/f0/f681d8488b10b6189eaac5dc2f4445c2bca9ea: No such file or directory
cp: testBuildOrg//.git/objects/f1/d8232df68322ecdf811d61b1821a56451eef8a: No such file or directory
cp: testBuildOrg//.git/objects/f1/dc0cbc398d04f83838191fc2c8500d5f1e0f8c: No such file or directory
cp: testBuildOrg//.git/objects/f1/df648ee704b8121d66e9c445e60e3e44655920: No such file or directory
cp: testBuildOrg//.git/objects/f1/e5064e0c4e33d460362f2a267910949e334eb1: No such file or directory
cp: testBuildOrg//.git/objects/f1/e7a2ce515147197138986b60f422eaeeba9827: No such file or directory
cp: testBuildOrg//.git/objects/f1/ea61b5a37a0dab9f96c593a2e56c101d691e8f: No such file or directory
cp: testBuildOrg//.git/objects/f1/ec3f59af93d08fbe4a505f9f6c1d0560f82330: No such file or directory
cp: testBuildOrg//.git/objects/f1/f70df7ef6f411e6991a43f7802fbb477346ed3: No such file or directory
cp: testBuildOrg//.git/objects/f1/f7815698e88b38f9f70f148decc639af70681f: No such file or directory
cp: testBuildOrg//.git/objects/f1/ffea2d1906a9e63191b93849ffb51a641de933: No such file or directory
cp: testBuildOrg//.git/objects/f2/513ff43a7b98d51dc833ecf75c90847836ca53: No such file or directory
cp: testBuildOrg//.git/objects/f2/6416b34704af6ebc7ff345512c699882c96c06: No such file or directory
cp: testBuildOrg//.git/objects/f2/719316f1cd85f6f2d19a81a06cf7608bf9cd5b: No such file or directory
cp: testBuildOrg//.git/objects/f2/7ad279844b8679ea654d7fb84e403d5ca58b21: No such file or directory
cp: testBuildOrg//.git/objects/f2/7eba5869b9e0ca62f9eced33cc4e790443e19b: No such file or directory
cp: testBuildOrg//.git/objects/f2/8f905f7461c18b98fedadb9a0c224f42cf0811: No such file or directory
cp: testBuildOrg//.git/objects/f2/97fab3334c1e6ae4b90be64178f928da751bc7: No such file or directory
cp: testBuildOrg//.git/objects/f2/99686643370f126d03aa56de95e80b98f5041b: No such file or directory
cp: testBuildOrg//.git/objects/f2/9b73af4c1a7c1d4a5f12ec4572fd8504ae59c6: No such file or directory
cp: testBuildOrg//.git/objects/f2/9d96e24b0dce17d093db588a15da6c08caa71c: No such file or directory
cp: testBuildOrg//.git/objects/f2/a384e721fe22055c3e56b6ad649e35dbc399e2: No such file or directory
cp: testBuildOrg//.git/objects/f2/a963a063bbd4b26a6c61a2fd6e73e1dad0b8a8: No such file or directory
cp: testBuildOrg//.git/objects/f2/ad80316992ba8bb4b91909291faaba29bcb89f: No such file or directory
cp: testBuildOrg//.git/objects/f2/aec43f2f1700ef104fc338f6ea399e64b0410f: No such file or directory
cp: testBuildOrg//.git/objects/f2/af27fc9c3b1a3657eaa362d69dc4ac17cddef6: No such file or directory
cp: testBuildOrg//.git/objects/f2/b6f8f1632745b3ce394d09eb2838a961285f45: No such file or directory
cp: testBuildOrg//.git/objects/f2/bdcb8c43aeb8519975a25147b7c813e5479ec1: No such file or directory
cp: testBuildOrg//.git/objects/f2/bdfa9cf05c16f3091491abaed5de679cf1ef32: No such file or directory
cp: testBuildOrg//.git/objects/f2/c779ed936c1afbf3a0c86108befda6dfca213a: No such file or directory
cp: testBuildOrg//.git/objects/f2/c85d6c3243c2fe97a1da4bb98dc0d0a1456a64: No such file or directory
cp: testBuildOrg//.git/objects/f2/cbb1de723c6c5b4355568d72f8580142fb8505: No such file or directory
cp: testBuildOrg//.git/objects/f2/cef977a51fef85b5827a028b93177df469253b: No such file or directory
cp: testBuildOrg//.git/objects/f2/d2cacf93084db03b5c7a3755a53b24d0ab5f1b: No such file or directory
cp: testBuildOrg//.git/objects/f2/d7579b9037e634fbc35a9e6927b69e729cb536: No such file or directory
cp: testBuildOrg//.git/objects/f2/d766875e91c9870cdc857a2171c43c83675536: No such file or directory
cp: testBuildOrg//.git/objects/f2/dcab59ac856057b72508e748cafec5a359804e: No such file or directory
cp: testBuildOrg//.git/objects/f2/e9fe21aa2156a8243dbe82bed9a90322aba995: No such file or directory
cp: testBuildOrg//.git/objects/f2/ff55e3422afa27ee49dd5e52cf285232b2aae3: No such file or directory
cp: testBuildOrg//.git/objects/f3/1021502ee7c991c39e319dc0e91b850b1c46ba: No such file or directory
cp: testBuildOrg//.git/objects/f3/14898b6f797544f2fd0767cadc76e311bb891a: No such file or directory
cp: testBuildOrg//.git/objects/f3/15e9e72a62d202620d45f57217f39544996e65: No such file or directory
cp: testBuildOrg//.git/objects/f3/19bd9fb47518f47a31513fbfd64e11db9b809e: No such file or directory
cp: testBuildOrg//.git/objects/f3/1b0c1fc1c1c27d47a750ba622643a322695bda: No such file or directory
cp: testBuildOrg//.git/objects/f3/20eebe7a8bc761ffd60c308d63cb44673c734c: No such file or directory
cp: testBuildOrg//.git/objects/f3/698bc012f31fa8bf3bee6a38af501a2f1a38cb: No such file or directory
cp: testBuildOrg//.git/objects/f3/6d845e4a2357133340692462bd4678b988f2e2: No such file or directory
cp: testBuildOrg//.git/objects/f3/7c97dfa0c1c1e837709358a03402d8a9009774: No such file or directory
cp: testBuildOrg//.git/objects/f3/7cf2e60630243a383fff6393ff136c759dad97: No such file or directory
cp: testBuildOrg//.git/objects/f3/8c3e06d0777643537ea54acbdc623699656dce: No such file or directory
cp: testBuildOrg//.git/objects/f3/8d67516f9b13c8e7cea62c1df604618deccc76: No such file or directory
cp: testBuildOrg//.git/objects/f3/a3159087cd54deac32ccf7aebb3ec40542291f: No such file or directory
cp: testBuildOrg//.git/objects/f3/d4df6ebe6694da683e84878af8186f92d748f3: No such file or directory
cp: testBuildOrg//.git/objects/f3/e313f8f52b6d492bc2ab1dd199220da402d39a: No such file or directory
cp: testBuildOrg//.git/objects/f3/ebeea20ba4286007a8ee321b2ab80838b60639: No such file or directory
cp: testBuildOrg//.git/objects/f3/ed041ace7c97a4e47ba9bb7cff90a792bae611: No such file or directory
cp: testBuildOrg//.git/objects/f3/f054d4f707b0089c186774b3124fcdfc30b1b5: No such file or directory
cp: testBuildOrg//.git/objects/f3/f2c23efc34dcc7953aab8978ac88630ff4e323: No such file or directory
cp: testBuildOrg//.git/objects/f3/f3060ae4d37f2741198286e151b58cee04a5aa: No such file or directory
cp: testBuildOrg//.git/objects/f3/f8bbf4e7131feed6b808fd78183637910e75d1: No such file or directory
cp: testBuildOrg//.git/objects/f3/f9cde3739d9011a97a6cf81062833de9457c97: No such file or directory
cp: testBuildOrg//.git/objects/f3/fbfb2ccaa2d6cd9af976160a4a46cdc61fd28b: No such file or directory
cp: testBuildOrg//.git/objects/f4/3cb82ff4891759dc97520729d56ec11aaf5361: No such file or directory
cp: testBuildOrg//.git/objects/f4/4671b9465fad038756236a4cee13e5b2887aba: No such file or directory
cp: testBuildOrg//.git/objects/f4/4869228a99ddf1873f38a26bafd50a5c6a8a56: No such file or directory
cp: testBuildOrg//.git/objects/f4/4bf8494b8b415b8766b3e324345c05069c72ae: No such file or directory
cp: testBuildOrg//.git/objects/f4/52febda2a4e28833a8e005e4412a221a09f25d: No such file or directory
cp: testBuildOrg//.git/objects/f4/53c77a00662e322a6a27ab69d795b8a8177cd0: No such file or directory
cp: testBuildOrg//.git/objects/f4/554de56e9d04b85729f3a23c733b9040cb72e4: No such file or directory
cp: testBuildOrg//.git/objects/f4/5bd3c76e7b5553e4b2d5963206f92ae55a9fa8: No such file or directory
cp: testBuildOrg//.git/objects/f4/6df6af73a648b393e970480a3a49ac9af2badc: No such file or directory
cp: testBuildOrg//.git/objects/f4/7585ea4f04da1889e9f037df2b5743de3eb349: No such file or directory
cp: testBuildOrg//.git/objects/f4/7e52a35957051172a5c3265ffa392a53602810: No such file or directory
cp: testBuildOrg//.git/objects/f4/8eecccd7f4295cc4ec0420f6e48c2372928f71: No such file or directory
cp: testBuildOrg//.git/objects/f4/9ae0e114925980e7ec396a1764fa5ab886f480: No such file or directory
cp: testBuildOrg//.git/objects/f4/9b4c8ff0f264bbce62d9211fafe7f418e1ed1c: No such file or directory
cp: testBuildOrg//.git/objects/f4/9e9bf388a9b3513dae7bbe6f113c80352fb017: No such file or directory
cp: testBuildOrg//.git/objects/f4/b71db73364c68bc6b2ba6ecfeb24773f7db966: No such file or directory
cp: testBuildOrg//.git/objects/f4/b766bd324a8f0d75f2a38b96cafac96f3093ac: No such file or directory
cp: testBuildOrg//.git/objects/f4/b7bb8cdcae0e16950cb416d671208f18292e09: No such file or directory
cp: testBuildOrg//.git/objects/f4/c454c214a07af66c8e6f3909b96d41b3e280a1: No such file or directory
cp: testBuildOrg//.git/objects/f4/cad3fc05b2494e3cc1fc011ca93a8132239a2a: No such file or directory
cp: testBuildOrg//.git/objects/f4/cbe5189c2c183b9086abf261b34b71d9a542ee: No such file or directory
cp: testBuildOrg//.git/objects/f4/d276c4d03d7e3d0f0b47f92944d336b511bf3d: No such file or directory
cp: testBuildOrg//.git/objects/f4/d7954bd16f03a171738ce780c1b38f0773f7fc: No such file or directory
cp: testBuildOrg//.git/objects/f4/df09b13a47a69bd64f61a95b6538f201a86ffb: No such file or directory
cp: testBuildOrg//.git/objects/f4/ec31cf73bc4606853ecb2f9b66ddc14cae11e5: No such file or directory
cp: testBuildOrg//.git/objects/f4/f2ad8c2d249640205628184062e2424ad6141e: No such file or directory
cp: testBuildOrg//.git/objects/f4/f3c93010cd56f74f954801369078754b1eab41: No such file or directory
cp: testBuildOrg//.git/objects/f4/f9b901a167f72f33c0c803ceacb34a46ebad59: No such file or directory
cp: testBuildOrg//.git/objects/f4/fc200dd8aeee3767b6a9c95ee9ed3f1f17ea17: No such file or directory
cp: testBuildOrg//.git/objects/f4/fc2908620c6620c98c5740d61b8bc897d2f16e: No such file or directory
cp: testBuildOrg//.git/objects/f5/c88cd8aa316307d30ba0dfeee55558b6bc4b9d: No such file or directory
cp: testBuildOrg//.git/objects/f5/d2eedbf54a6e6f24da73f7e6c209c75aaddb0e: No such file or directory
cp: testBuildOrg//.git/objects/f5/d538da25507c23c6864e8644496f543f3cb897: No such file or directory
cp: testBuildOrg//.git/objects/f5/e8a9e9180e96ab80a039bd2308c42832c16ca3: No such file or directory
cp: testBuildOrg//.git/objects/f5/edd9f3c50ab992d4bcfb389cf16bbaeef83d02: No such file or directory
cp: testBuildOrg//.git/objects/f5/ee316d3d7078b3b79275906bc15471c413d6a9: No such file or directory
cp: testBuildOrg//.git/objects/f5/f28c795f3b4cc9605d3daa160f09ba5952e6f8: No such file or directory
cp: testBuildOrg//.git/objects/f5/f7075c7903a36e99be0aa98fa9c418806087b4: No such file or directory
cp: testBuildOrg//.git/objects/f5/f7bb579817ccae5c0ea6586ac040ebb2223826: No such file or directory
cp: testBuildOrg//.git/objects/f5/fc44177e9aa93444f412becc20aeb6ef09e739: No such file or directory
cp: testBuildOrg//.git/objects/f5/ffd6edf8a0812431e16fa60cfa505a36cb6637: No such file or directory
cp: testBuildOrg//.git/objects/f6/bada7df7f79f8404e75d9570f657f250743846: No such file or directory
cp: testBuildOrg//.git/objects/f6/c9ea2a135ec96cd37dd1d7970bcb26a3e11978: No such file or directory
cp: testBuildOrg//.git/objects/f6/cefdfe23a69726e3ff1782d89ee948a95f08c7: No such file or directory
cp: testBuildOrg//.git/objects/f6/d0cd4d690ca7d484317aa21261c8c4301e499b: No such file or directory
cp: testBuildOrg//.git/objects/f6/d2927d7da5b1eae7b5ef9e3ee578cbb6b745e7: No such file or directory
cp: testBuildOrg//.git/objects/f6/e24ff68f9839b946e78588aa226f3810a70d69: No such file or directory
cp: testBuildOrg//.git/objects/f6/e2e2ef8b2cc94ec489d316e56f78b9ebe490af: No such file or directory
cp: testBuildOrg//.git/objects/f6/e511f7d6b4ba5574e8e8aeacbe9e7fc72fe520: No such file or directory
cp: testBuildOrg//.git/objects/f6/e94d5ef8e4f14eae3925527d8d858535a1645a: No such file or directory
cp: testBuildOrg//.git/objects/f6/fd251dac83d59a6f8a0ba8a4f7237753ee36fe: No such file or directory
cp: testBuildOrg//.git/objects/f6/ff4da9d06d0a97d5d80008af5a10fb948a4952: No such file or directory
cp: testBuildOrg//.git/objects/f7/3255ae63e3c76960d1ca734a3e2bff24d1be2d: No such file or directory
cp: testBuildOrg//.git/objects/f7/3b376b53ba7d2178507b59f00be8634ed14949: No such file or directory
cp: testBuildOrg//.git/objects/f7/41b3e9ca9cbbac0a5546b1cd34e9e2fcdd8444: No such file or directory
cp: testBuildOrg//.git/objects/f7/420d4467e3ab61f45a8aaee4ba44ca52d8a4ce: No such file or directory
cp: testBuildOrg//.git/objects/f7/50512a534be30e3221a7ea989115806325bb90: No such file or directory
cp: testBuildOrg//.git/objects/f7/528af9dc4af598361fb3283034fc8790170260: No such file or directory
cp: testBuildOrg//.git/objects/f7/599c744b9d512ef52a5781c433f564828fa8e0: No such file or directory
cp: testBuildOrg//.git/objects/f7/5bd03f180ccf1149a8bf0baceb619d604d457e: No such file or directory
cp: testBuildOrg//.git/objects/f7/767e92944541842271ef02610dbba1da12f1cc: No such file or directory
cp: testBuildOrg//.git/objects/f7/8488d2e19f3c9ff1e7c6128553cd47ce855007: No such file or directory
cp: testBuildOrg//.git/objects/f7/8ed241a22a63465afb3596d5d4abdab52d1af3: No such file or directory
cp: testBuildOrg//.git/objects/f7/91f6f4ce365f30b4a28902078edd960399253c: No such file or directory
cp: testBuildOrg//.git/objects/f7/967ad12c3e7c2a642dda21e6b7649f7f290436: No such file or directory
cp: testBuildOrg//.git/objects/f7/98caa40b7a87a9e0d635ad956ef4cc1a50c7d9: No such file or directory
cp: testBuildOrg//.git/objects/f7/999a54baf53db66efef5c0602303448bdfebdb: No such file or directory
cp: testBuildOrg//.git/objects/f7/a1b07fa6cb6a12de5e3a91064f63deeef2fbb6: No such file or directory
cp: testBuildOrg//.git/objects/f7/a2f64f8592d8cfdb8e3085407d01072a07ac5b: No such file or directory
cp: testBuildOrg//.git/objects/f7/a3584e57ebb2eb046a2b4dcaddd175bb012049: No such file or directory
cp: testBuildOrg//.git/objects/f7/aae7ff555d25a05066b6fa7d4f23c2cb7284f8: No such file or directory
cp: testBuildOrg//.git/objects/f7/ab2298ab22d5bc8f51935552063ed140c73668: No such file or directory
cp: testBuildOrg//.git/objects/f7/b10a90515d4ce90fddc7ee6ac7cdff5c837674: No such file or directory
cp: testBuildOrg//.git/objects/f7/b75098e8b4def5fdefc056109e470e6f1c9600: No such file or directory
cp: testBuildOrg//.git/objects/f7/c6f29cb4b50773289e75b11ad782730c93b6da: No such file or directory
cp: testBuildOrg//.git/objects/f7/cb321c8413416d3ae483a78c76c0de0022f86d: No such file or directory
cp: testBuildOrg//.git/objects/f7/cfb82484f3cc436a758778a79a32e9a4c32ebd: No such file or directory
cp: testBuildOrg//.git/objects/f7/dc38d834695529f93164d2113b34107c66a51f: No such file or directory
cp: testBuildOrg//.git/objects/f7/e0019f31c407d037168e4cbb86ea6113ee5685: No such file or directory
cp: testBuildOrg//.git/objects/f7/e345619ea5e207fd838aa2315bb8c1307bdf01: No such file or directory
cp: testBuildOrg//.git/objects/f7/e5a7d692f1463d9990b48aa205d5a145b127eb: No such file or directory
cp: testBuildOrg//.git/objects/f7/e77b2e21ed7eb5e370e6331d301be4c81b07a2: No such file or directory
cp: testBuildOrg//.git/objects/f7/eb83380d0007591a056d8d3fe4357a30a67dd7: No such file or directory
cp: testBuildOrg//.git/objects/f7/edcf60e9937e57d6dd4e073982c0b803854fe1: No such file or directory
cp: testBuildOrg//.git/objects/f7/f382524467dfdb6baa9cd9b7c8157f3264d53c: No such file or directory
cp: testBuildOrg//.git/objects/f7/f95f792a97a81c01e5006cf5ead36ac174fe34: No such file or directory
cp: testBuildOrg//.git/objects/f7/fd3b695d234a5a9fd366c0e08c0407fdc3e701: No such file or directory
cp: testBuildOrg//.git/objects/f8/2081cfbd649ca88405e12c85dd15960add2aa5: No such file or directory
cp: testBuildOrg//.git/objects/f8/23fb2a459e3b574217882eced8d73ae997bd4b: No such file or directory
cp: testBuildOrg//.git/objects/f8/3386e75ec187a891966e8298d74b2dc3a82c67: No such file or directory
cp: testBuildOrg//.git/objects/f8/36a05c4979e51859cd25e41119384cd48522d5: No such file or directory
cp: testBuildOrg//.git/objects/f8/547f7e263b9b046c836ee1875f6b41a9f6dfa4: No such file or directory
cp: testBuildOrg//.git/objects/f8/5b614003b5309d128eff843348f4cb068bac47: No such file or directory
cp: testBuildOrg//.git/objects/f8/71917e142ad928dcaaf05286dcbb9428eae7c8: No such file or directory
cp: testBuildOrg//.git/objects/f8/7bf9aecf1c7f0d5a83b89202cb8fdac25ee4a2: No such file or directory
cp: testBuildOrg//.git/objects/f8/7c0266600e98e2cf6f8c3772930284ff6a0773: No such file or directory
cp: testBuildOrg//.git/objects/f8/7c8672248312ccbeabedeffe5a3d0ab7dc9299: No such file or directory
cp: testBuildOrg//.git/objects/f8/7d45c054bc709bd4a3252dbcb3fbad00969612: No such file or directory
cp: testBuildOrg//.git/objects/f8/7fef988ae7450e913f4f7e4b1a1cfd73bc6ed7: No such file or directory
cp: testBuildOrg//.git/objects/f8/807c8cc3c6fdda8c430efc3d32c5a3fe569bd5: No such file or directory
cp: testBuildOrg//.git/objects/f8/826d611708c24211718edc61e2ccb060af831a: No such file or directory
cp: testBuildOrg//.git/objects/f8/971a06d7e7d6fa1d0e6309ca01b224e8643bfc: No such file or directory
cp: testBuildOrg//.git/objects/f8/9731aaddacc82f34f3955569bca8bd0e628178: No such file or directory
cp: testBuildOrg//.git/objects/f8/9759dfe3fe30945d1f0e75330d15f697051c18: No such file or directory
cp: testBuildOrg//.git/objects/f8/a49ca90b6a63e22350f789e0e65901be194fc3: No such file or directory
cp: testBuildOrg//.git/objects/f8/a69f6b2c3498cf319815f41b8af021c1b661e9: No such file or directory
cp: testBuildOrg//.git/objects/f8/b41d14816b021ca55bfe82e08e5d774beea380: No such file or directory
cp: testBuildOrg//.git/objects/f8/b6720072f5932227166c44d40139becc689ae0: No such file or directory
cp: testBuildOrg//.git/objects/f8/b8354a214e861d0f8eb1eb6e17573c515acb93: No such file or directory
cp: testBuildOrg//.git/objects/f8/c1cad1a5f63901d1e0bd31f70260c5abf39738: No such file or directory
cp: testBuildOrg//.git/objects/f8/c4a2b6b52b6be78ddd3b6422c872892121a342: No such file or directory
cp: testBuildOrg//.git/objects/f8/de2eec5b88b561c16828a7c5fad3b69bd90c85: No such file or directory
cp: testBuildOrg//.git/objects/f9/328a6797ec3b5fd09e7ec81fb143e1e76b3019: No such file or directory
cp: testBuildOrg//.git/objects/f9/36bc2f0729289a40b3396d99ca8ec53e637c79: No such file or directory
cp: testBuildOrg//.git/objects/f9/39985ec113d80f2b565ead8483d988d8ada704: No such file or directory
cp: testBuildOrg//.git/objects/f9/4dd87fa581f6959fc479be639c482e39b1429c: No such file or directory
cp: testBuildOrg//.git/objects/f9/53e6e45f95868556bd216d3622da8330fcba28: No such file or directory
cp: testBuildOrg//.git/objects/f9/56cefe1a68d2a540e9b96ef9310f6134f70ee8: No such file or directory
cp: testBuildOrg//.git/objects/f9/595e121285dd3e532100866b2c0b123e065f98: No such file or directory
cp: testBuildOrg//.git/objects/f9/5decfae8f807fda6047fb504099632367afa0e: No such file or directory
cp: testBuildOrg//.git/objects/f9/60baa69fefbd64febb5c08a038f3245bb3953a: No such file or directory
cp: testBuildOrg//.git/objects/f9/6496c4084dbefe281fec5a5c9fa22617dc9585: No such file or directory
cp: testBuildOrg//.git/objects/f9/663e6df034b463541bbbcf6d8830be4fb67b0d: No such file or directory
cp: testBuildOrg//.git/objects/f9/6dd1f175e90ce4283f768cbf53b0adb924964f: No such file or directory
cp: testBuildOrg//.git/objects/f9/8e77e6805a6b77f943f9c2ca2471b440a89206: No such file or directory
cp: testBuildOrg//.git/objects/f9/91033ac9bace765659c6d479360db48cde2dce: No such file or directory
cp: testBuildOrg//.git/objects/f9/97eb5f504146f0225b4b29355017ea108449ff: No such file or directory
cp: testBuildOrg//.git/objects/f9/9cb8575d25c4d1a43fb1ee698b94ce4812aa8e: No such file or directory
cp: testBuildOrg//.git/objects/f9/abc32800f783863c86a7a0c067a897303758a6: No such file or directory
cp: testBuildOrg//.git/objects/f9/b26079b3313f70f43b5c7ae116032318810416: No such file or directory
cp: testBuildOrg//.git/objects/f9/b3b17921a70ae7865eb3558f145f1f923d37bb: No such file or directory
cp: testBuildOrg//.git/objects/f9/b4d964824473ee28760f7fb9f4d461e3db5c91: No such file or directory
cp: testBuildOrg//.git/objects/f9/b8069136e5e4dcf1c56c53141036ac39cd5418: No such file or directory
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
cp: testBuildOrg//.git/objects/fa/f5c06dee410eb74f265edf65d3cf6b1b8b244e: No such file or directory
cp: testBuildOrg//.git/objects/fa/f65e07f68f84be9cfc1a8355aa34b435f6f3c7: No such file or directory
cp: testBuildOrg//.git/objects/fa/fd3982709eaae8623e29fb76f2c9ab054e315b: No such file or directory
cp: testBuildOrg//.git/objects/fa/fe3d897fa180bc6e2c02543502dd22d58d61ed: No such file or directory
cp: testBuildOrg//.git/objects/fb/ab494773e49b31ca5734921b902d229f991d29: No such file or directory
cp: testBuildOrg//.git/objects/fb/b1b27a665ea42ed7c0aaef3fcc4e9711962196: No such file or directory
cp: testBuildOrg//.git/objects/fb/b22d25b2e4605fd40ec3c31c65b6c81ff2a572: No such file or directory
cp: testBuildOrg//.git/objects/fb/b488a9df299e648045089c16a420ca9862373e: No such file or directory
cp: testBuildOrg//.git/objects/fb/c6a5ebe451bb27de396c726ec3891f6690d299: No such file or directory
cp: testBuildOrg//.git/objects/fb/c720e48a3e1ae9cafd4ac74a27cd4f0c434e95: No such file or directory
cp: testBuildOrg//.git/objects/fb/ce2387518065de7a8dbcd20b6c3de014de8bae: No such file or directory
cp: testBuildOrg//.git/objects/fb/d53591136e4ef357ced951c1a78d8c8971212b: No such file or directory
cp: testBuildOrg//.git/objects/fb/ddcb489f229186b40c2858560d5c2b216b5c25: No such file or directory
cp: testBuildOrg//.git/objects/fb/e843926443d51e70223ab123f4e57917b570fc: No such file or directory
cp: testBuildOrg//.git/objects/fb/fed8f1d7df4495ded7cfff5aac4acaabd359ec: No such file or directory
cp: testBuildOrg//.git/objects/fc/8a2a7070cbf9a88b1f314472860e6372b4b019: No such file or directory
cp: testBuildOrg//.git/objects/fc/8c50feaab0573d3f060387afa9e51d763b7c20: No such file or directory
cp: testBuildOrg//.git/objects/fc/9972a2d20167e9e364cb3cc1daed8a50c8f8a1: No such file or directory
cp: testBuildOrg//.git/objects/fc/9f7d3fa55719c44b048f63e3f12be4c564aaa7: No such file or directory
cp: testBuildOrg//.git/objects/fc/9fa6f146b04765f20140e6c8b6afb5da277899: No such file or directory
cp: testBuildOrg//.git/objects/fc/b2e773f8da16b99972459a0be68fbef56f5ea9: No such file or directory
cp: testBuildOrg//.git/objects/fc/b3114927c194b051c714cab0fb29ff602ec306: No such file or directory
cp: testBuildOrg//.git/objects/fc/b904fd247e05224771a4153894850f3ef80581: No such file or directory
cp: testBuildOrg//.git/objects/fc/c251a5fe1db2bd7ea4904b8aff5ff66b5bfcdd: No such file or directory
cp: testBuildOrg//.git/objects/fc/c46903369ec497f9b777881a67060f5e2fce7f: No such file or directory
cp: testBuildOrg//.git/objects/fc/c7f1711f4e9b378fdd48c5f31a1278bd9e7c94: No such file or directory
cp: testBuildOrg//.git/objects/fc/cc2691b6095b3d7b9674b5d680bbe894ab3ee7: No such file or directory
cp: testBuildOrg//.git/objects/fc/cea7e88e56be399f07ec44c0d717ba4f438ee9: No such file or directory
cp: testBuildOrg//.git/objects/fc/dc31b81da2f98f626a7f15604b9935cee18e95: No such file or directory
cp: testBuildOrg//.git/objects/fc/f0eb996a97e16e9e7152077ffe0cdb9aaeb727: No such file or directory
cp: testBuildOrg//.git/objects/fc/f4b31ec06a85611d976b377fa38e6a9f2caa3a: No such file or directory
cp: testBuildOrg//.git/objects/fd/50bd4036c924fe3b52f6a5840424537d95cedf: No such file or directory
cp: testBuildOrg//.git/objects/fd/5e9ba414e376f1d19a3b8d762fd434e76db0da: No such file or directory
cp: testBuildOrg//.git/objects/fd/64960fe50e22f1ee65750ecae864737799c9c8: No such file or directory
cp: testBuildOrg//.git/objects/fd/68e1b3035feda2fa3051cab2de5a828a33eb0e: No such file or directory
cp: testBuildOrg//.git/objects/fd/6e67489fb668ae33790f29996aa60aa78625db: No such file or directory
cp: testBuildOrg//.git/objects/fd/786947f93abbb5002a745c2af6f4b20d9d7f6c: No such file or directory
cp: testBuildOrg//.git/objects/fd/7c8cddbfc7bd4692d97c4045ea095ddef91fc4: No such file or directory
cp: testBuildOrg//.git/objects/fd/7eafcb617794330ae8e966601f3802b476354e: No such file or directory
cp: testBuildOrg//.git/objects/fd/83edafc2d69c3cf3ee27f08b6b34d18d602de1: No such file or directory
cp: testBuildOrg//.git/objects/fd/8a85244b3b7c02bc487bc6ca5c1bd9f8a65e6a: No such file or directory
cp: testBuildOrg//.git/objects/fd/8d22b68c82dbfc27003698b132288710fea842: No such file or directory
cp: testBuildOrg//.git/objects/fd/a5ffe3156fc8e984575384970805c9c7f2fb14: No such file or directory
cp: testBuildOrg//.git/objects/fd/a7c0b5ec1d5a867275a2c189e4e4bb51091be4: No such file or directory
cp: testBuildOrg//.git/objects/fd/a9f42f245e48cc140537e86cde9cdc301a80ce: No such file or directory
cp: testBuildOrg//.git/objects/fd/ae11fa91338d087b439b3e8132da14f14b5ee3: No such file or directory
cp: testBuildOrg//.git/objects/fd/aee9708259df02140f3b9129f7fa0eccedc52f: No such file or directory
cp: testBuildOrg//.git/objects/fd/c174e40cae6b0a817476ca54fc8320d4eb354c: No such file or directory
cp: testBuildOrg//.git/objects/fd/d630afb5e2d9adf7e4349fe8f516a4987e0ea7: No such file or directory
cp: testBuildOrg//.git/objects/fd/e0215087e8b7de836d0ac6454d7c4bbc90bd37: No such file or directory
cp: testBuildOrg//.git/objects/fd/e119119b56346ab1c9b35d52769bf62bf3b15a: No such file or directory
cp: testBuildOrg//.git/objects/fd/ead750b81f05adb51b80cef180668436402394: No such file or directory
cp: testBuildOrg//.git/objects/fd/ed54dbf26ab1cf83c63e04075fc13989a92f43: No such file or directory
cp: testBuildOrg//.git/objects/fd/eec24b9ee162fabac137f2ca0def13cca35aa2: No such file or directory
cp: testBuildOrg//.git/objects/fd/ef387a0b162a06608dfc9bf2b8c957e4a027e1: No such file or directory
cp: testBuildOrg//.git/objects/fd/f1d3baaa5524b9b91430b325c0c0811f029c26: No such file or directory
cp: testBuildOrg//.git/objects/fd/fa90b74bbf0e211e2b0d93dc01224e50fdf75b: No such file or directory
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
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/socket.io
npm http request GET http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/fs-extra-promise
npm http 200 http://192.168.1.100:4873/lie
npm http 200 http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/socket.io
npm http 200 http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/cookie-signature
npm http request GET http://192.168.1.100:4873/escape-html
npm http request GET http://192.168.1.100:4873/cookie
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/content-disposition
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/accepts
npm http request GET http://192.168.1.100:4873/array-flatten
npm http request GET http://192.168.1.100:4873/merge-descriptors
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/parseurl
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/fresh
npm http request GET http://192.168.1.100:4873/finalhandler
npm http request GET http://192.168.1.100:4873/etag
npm http request GET http://192.168.1.100:4873/proxy-addr
npm http request GET http://192.168.1.100:4873/path-to-regexp
npm http request GET http://192.168.1.100:4873/range-parser
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/send
npm http request GET http://192.168.1.100:4873/utils-merge
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/vary
npm http request GET http://192.168.1.100:4873/serve-static
npm http 200 http://192.168.1.100:4873/escape-html
npm http 200 http://192.168.1.100:4873/depd
npm http 200 http://192.168.1.100:4873/debug
npm http 200 http://192.168.1.100:4873/cookie-signature
npm http 200 http://192.168.1.100:4873/cookie
npm http 200 http://192.168.1.100:4873/content-type
npm http 200 http://192.168.1.100:4873/merge-descriptors
npm http 200 http://192.168.1.100:4873/content-disposition
npm http 200 http://192.168.1.100:4873/accepts
npm http 200 http://192.168.1.100:4873/array-flatten
npm http 200 http://192.168.1.100:4873/methods
npm http 200 http://192.168.1.100:4873/on-finished
npm http 200 http://192.168.1.100:4873/fresh
npm http 200 http://192.168.1.100:4873/parseurl
npm http 200 http://192.168.1.100:4873/finalhandler
npm http 200 http://192.168.1.100:4873/etag
npm http 200 http://192.168.1.100:4873/proxy-addr
npm http 200 http://192.168.1.100:4873/range-parser
npm http 200 http://192.168.1.100:4873/path-to-regexp
npm http 200 http://192.168.1.100:4873/qs
npm http 200 http://192.168.1.100:4873/send
npm http 200 http://192.168.1.100:4873/utils-merge
npm http 200 http://192.168.1.100:4873/type-is
npm http 200 http://192.168.1.100:4873/serve-static
npm http 200 http://192.168.1.100:4873/vary
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
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/mime
npm http request GET http://192.168.1.100:4873/statuses
npm http 200 http://192.168.1.100:4873/http-errors
npm http 200 http://192.168.1.100:4873/destroy
npm http 200 http://192.168.1.100:4873/mime
npm http 200 http://192.168.1.100:4873/statuses
npm http request GET http://192.168.1.100:4873/inherits
npm http 200 http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/media-typer
npm http 200 http://192.168.1.100:4873/media-typer
npm http request GET http://192.168.1.100:4873/fs-extra
npm http request GET http://192.168.1.100:4873/bluebird
npm http 200 http://192.168.1.100:4873/bluebird
npm http 200 http://192.168.1.100:4873/fs-extra
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
npm http 200 http://192.168.1.100:4873/path-is-absolute
npm http 200 http://192.168.1.100:4873/inflight
npm http 200 http://192.168.1.100:4873/once
npm http 200 http://192.168.1.100:4873/fs.realpath
npm http 200 http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/wrappy
npm http 200 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 200 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/balanced-match
npm http 200 http://192.168.1.100:4873/concat-map
npm http 200 http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 200 http://192.168.1.100:4873/es3ify
npm http 200 http://192.168.1.100:4873/inline-process-browser
npm http 200 http://192.168.1.100:4873/unreachable-branch-transform
npm http 200 http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/through
npm http 200 http://192.168.1.100:4873/jstransform
npm http 200 http://192.168.1.100:4873/through
npm http 200 http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/source-map
npm http 200 http://192.168.1.100:4873/base62
npm http 200 http://192.168.1.100:4873/source-map
npm http 200 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/esprima-fb
npm http 200 http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/recast
npm http 200 http://192.168.1.100:4873/private
npm http 200 http://192.168.1.100:4873/commander
npm http 200 http://192.168.1.100:4873/q
npm http 200 http://192.168.1.100:4873/mkdirp
npm http 200 http://192.168.1.100:4873/iconv-lite
npm http 200 http://192.168.1.100:4873/detective
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
npm http 200 http://192.168.1.100:4873/through2
npm http 200 http://192.168.1.100:4873/falafel
npm http request GET http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/object-keys
npm http 200 http://192.168.1.100:4873/object-keys
npm http 200 http://192.168.1.100:4873/foreach
npm http 200 http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 200 http://192.168.1.100:4873/xtend
npm http 200 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/string_decoder
npm http request GET http://192.168.1.100:4873/core-util-is
npm http 200 http://192.168.1.100:4873/string_decoder
npm http 200 http://192.168.1.100:4873/core-util-is
npm http request GET http://192.168.1.100:4873/esmangle-evaluator
npm http 200 http://192.168.1.100:4873/esmangle-evaluator
npm http request GET http://192.168.1.100:4873/socket.io-parser
npm http request GET http://192.168.1.100:4873/has-binary-data
npm http request GET http://192.168.1.100:4873/socket.io-adapter
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/engine.io
npm http 200 http://192.168.1.100:4873/socket.io-parser
npm http 200 http://192.168.1.100:4873/has-binary-data
npm http 200 http://192.168.1.100:4873/socket.io-adapter
npm http 200 http://192.168.1.100:4873/engine.io
npm http 200 http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/base64id
npm http request GET http://192.168.1.100:4873/ws
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http 200 http://192.168.1.100:4873/base64id
npm http 200 http://192.168.1.100:4873/engine.io-parser
npm http 200 http://192.168.1.100:4873/ws
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/has-binary
npm http request GET http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/utf8
npm http 200 http://192.168.1.100:4873/base64-arraybuffer
npm http 200 http://192.168.1.100:4873/after
npm http 200 http://192.168.1.100:4873/blob
npm http 200 http://192.168.1.100:4873/arraybuffer.slice
npm http 200 http://192.168.1.100:4873/has-binary
npm http 200 http://192.168.1.100:4873/utf8
npm http request GET http://192.168.1.100:4873/options
npm http request GET http://192.168.1.100:4873/bufferutil
npm http request GET http://192.168.1.100:4873/ultron
npm http request GET http://192.168.1.100:4873/utf-8-validate
npm http 200 http://192.168.1.100:4873/ultron
npm http 200 http://192.168.1.100:4873/options
npm http 200 http://192.168.1.100:4873/utf-8-validate
npm http 200 http://192.168.1.100:4873/bufferutil
npm http request GET http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/nan
npm http 200 http://192.168.1.100:4873/bindings
npm http 200 http://192.168.1.100:4873/nan
npm http request GET http://192.168.1.100:4873/component-emitter
npm http request GET http://192.168.1.100:4873/json3
npm http request GET http://192.168.1.100:4873/benchmark
npm http 200 http://192.168.1.100:4873/component-emitter
npm http 200 http://192.168.1.100:4873/json3
npm http 200 http://192.168.1.100:4873/benchmark
npm http request GET http://192.168.1.100:4873/component-bind
npm http request GET http://192.168.1.100:4873/parseuri
npm http request GET http://192.168.1.100:4873/indexof
npm http request GET http://192.168.1.100:4873/object-component
npm http request GET http://192.168.1.100:4873/backo2
npm http request GET http://192.168.1.100:4873/to-array
npm http request GET http://192.168.1.100:4873/engine.io-client
npm http 200 http://192.168.1.100:4873/parseuri
npm http 200 http://192.168.1.100:4873/component-bind
npm http 200 http://192.168.1.100:4873/indexof
npm http 200 http://192.168.1.100:4873/object-component
npm http 200 http://192.168.1.100:4873/backo2
npm http 200 http://192.168.1.100:4873/to-array
npm http 200 http://192.168.1.100:4873/engine.io-client
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/parseqs
npm http fetch GET https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http 200 http://192.168.1.100:4873/has-cors
npm http 200 http://192.168.1.100:4873/component-inherit
npm http 200 http://192.168.1.100:4873/parsejson
npm http 200 http://192.168.1.100:4873/parseqs
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
npm http request GET http://192.168.1.100:4873/cycle
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/colors
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/eyes
npm http 200 http://192.168.1.100:4873/stack-trace
npm http 200 http://192.168.1.100:4873/colors
npm http 200 http://192.168.1.100:4873/pkginfo
npm http 200 http://192.168.1.100:4873/cycle
npm http 200 http://192.168.1.100:4873/async
npm http 200 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/eyes
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
npm http request GET http://192.168.1.100:4873/salti
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/ip
npm http 200 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/express
npm http 200 http://192.168.1.100:4873/forever-agent
npm http 200 http://192.168.1.100:4873/lie
npm http 200 http://192.168.1.100:4873/javascript-state-machine
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 200 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/winston
npm http 304 http://192.168.1.100:4873/salti
npm http 200 http://192.168.1.100:4873/multiplex
npm http 200 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/raw-body
npm http 200 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/http-errors
npm http 200 http://192.168.1.100:4873/bytes
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/depd
npm http 200 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/type-is
npm http 200 http://192.168.1.100:4873/raw-body
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/statuses
npm http 304 http://192.168.1.100:4873/inherits
npm http 200 http://192.168.1.100:4873/statuses
npm http request GET http://192.168.1.100:4873/ee-first
npm http 304 http://192.168.1.100:4873/ee-first
npm http request GET http://192.168.1.100:4873/unpipe
npm http 304 http://192.168.1.100:4873/unpipe
npm http request GET http://192.168.1.100:4873/media-typer
npm http request GET http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/media-typer
npm http 200 http://192.168.1.100:4873/mime-types
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
npm http 304 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/serve-static
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/send
npm http 304 http://192.168.1.100:4873/utils-merge
npm http 304 http://192.168.1.100:4873/vary
npm http request GET http://192.168.1.100:4873/negotiator
npm http 304 http://192.168.1.100:4873/negotiator
npm http request GET http://192.168.1.100:4873/forwarded
npm http request GET http://192.168.1.100:4873/ipaddr.js
npm http 304 http://192.168.1.100:4873/ipaddr.js
npm http 200 http://192.168.1.100:4873/forwarded
npm http request GET http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/mime
npm http 304 http://192.168.1.100:4873/destroy
npm http 200 http://192.168.1.100:4873/mime
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 200 http://192.168.1.100:4873/inline-process-browser
npm http 304 http://192.168.1.100:4873/es3ify
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
npm http 304 http://192.168.1.100:4873/commoner
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/base62
npm http 304 http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/mkdirp
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http 304 http://192.168.1.100:4873/detective
npm http 304 http://192.168.1.100:4873/commander
npm http 304 http://192.168.1.100:4873/private
npm http 304 http://192.168.1.100:4873/q
npm http 200 http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/recast
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
npm http 304 http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/inflight
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
npm http 200 http://192.168.1.100:4873/amdefine
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
npm http request GET http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/string_decoder
npm http request GET http://192.168.1.100:4873/core-util-is
npm http 304 http://192.168.1.100:4873/core-util-is
npm http 200 http://192.168.1.100:4873/string_decoder
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
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 200 http://192.168.1.100:4873/process-nextick-args
npm http 200 http://192.168.1.100:4873/util-deprecate
npm http 200 http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http 200 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/bl
npm http 200 http://192.168.1.100:4873/json-stringify-safe
npm http 200 http://192.168.1.100:4873/tunnel-agent
npm http 200 http://192.168.1.100:4873/caseless
npm http 200 http://192.168.1.100:4873/stringstream
npm http 200 http://192.168.1.100:4873/combined-stream
npm http 200 http://192.168.1.100:4873/aws-sign2
npm http 200 http://192.168.1.100:4873/form-data
npm http 200 http://192.168.1.100:4873/har-validator
npm http 200 http://192.168.1.100:4873/oauth-sign
npm http 200 http://192.168.1.100:4873/hawk
npm http 200 http://192.168.1.100:4873/http-signature
npm http 200 http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 200 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 200 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http 304 http://192.168.1.100:4873/bluebird
npm http 200 http://192.168.1.100:4873/chalk
npm http 200 http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 200 http://192.168.1.100:4873/strip-ansi
npm http 200 http://192.168.1.100:4873/supports-color
npm http 200 http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/ansi-styles
npm http 200 http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 200 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http request GET http://192.168.1.100:4873/generate-function
npm http 200 http://192.168.1.100:4873/generate-object-property
npm http 200 http://192.168.1.100:4873/generate-function
npm http 200 http://192.168.1.100:4873/jsonpointer
npm http request GET http://192.168.1.100:4873/is-property
npm http 200 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/boom
npm http 200 http://192.168.1.100:4873/cryptiles
npm http 200 http://192.168.1.100:4873/sntp
npm http 200 http://192.168.1.100:4873/boom
npm http 200 http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/assert-plus
npm http 200 http://192.168.1.100:4873/ctype
npm http 200 http://192.168.1.100:4873/asn1
npm http 200 http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/colors
npm http request GET http://192.168.1.100:4873/cycle
npm http request GET http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/pkginfo
npm http request GET http://192.168.1.100:4873/stack-trace
npm http 304 http://192.168.1.100:4873/cycle
npm http 304 http://192.168.1.100:4873/eyes
npm http 304 http://192.168.1.100:4873/stack-trace
npm http 200 http://192.168.1.100:4873/colors
npm http 304 http://192.168.1.100:4873/pkginfo
npm http request GET http://192.168.1.100:4873/jsdoc
npm http 200 http://192.168.1.100:4873/jsdoc
npm http request GET http://192.168.1.100:4873/catharsis
npm http request GET http://192.168.1.100:4873/js2xmlparser
npm http request GET http://192.168.1.100:4873/requizzle
npm http request GET http://192.168.1.100:4873/marked
npm http request GET http://192.168.1.100:4873/wrench
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/underscore
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 200 http://192.168.1.100:4873/catharsis
npm http 200 http://192.168.1.100:4873/marked
npm http 200 http://192.168.1.100:4873/requizzle
npm http 200 http://192.168.1.100:4873/js2xmlparser
npm http 200 http://192.168.1.100:4873/wrench
npm WARN deprecated wrench@1.5.9: wrench.js is deprecated! You should check out fs-extra (https://github.com/jprichardson/node-fs-extra) for any operations you were using wrench for. Thanks for all the usage over the years.
npm http 200 http://192.168.1.100:4873/strip-json-comments
npm http 200 http://192.168.1.100:4873/underscore
npm http fetch 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http request GET http://192.168.1.100:4873/underscore-contrib
npm http 200 http://192.168.1.100:4873/underscore-contrib
npm WARN prefer global marked@0.3.6 should be installed with -g
npm http request GET http://192.168.1.100:4873/fs-extra-promise
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/jxc
npm http request GET http://192.168.1.100:4873/unzip
npm http 304 http://192.168.1.100:4873/lie
npm http 304 http://192.168.1.100:4873/fs-extra-promise
npm http 304 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/unzip
npm http 200 http://192.168.1.100:4873/jxc
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
npm http 304 http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/fs.realpath
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/minimatch
npm http 304 http://192.168.1.100:4873/inflight
npm http 304 http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/fs.realpath
npm http request GET http://192.168.1.100:4873/wrappy
npm http 304 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 304 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/progress
npm http request GET http://192.168.1.100:4873/adm-zip
npm http 200 http://192.168.1.100:4873/adm-zip
npm http 200 http://192.168.1.100:4873/progress
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 304 http://192.168.1.100:4873/inline-process-browser
npm http 304 http://192.168.1.100:4873/es3ify
npm http 304 http://192.168.1.100:4873/immediate
npm http 304 http://192.168.1.100:4873/unreachable-branch-transform
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
npm http 304 http://192.168.1.100:4873/commoner
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/base62
npm http 304 http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/mkdirp
npm http 304 http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/commander
npm http 304 http://192.168.1.100:4873/private
npm http 304 http://192.168.1.100:4873/detective
npm http 304 http://192.168.1.100:4873/q
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
npm http request GET http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/foreach
npm http 304 http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/object-keys
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/readable-stream
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
npm http 304 http://192.168.1.100:4873/forever-agent
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 200 http://192.168.1.100:4873/util-deprecate
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
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/ansi-styles
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-function
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http request GET http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/hoek
npm http 304 http://192.168.1.100:4873/boom
npm http 304 http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 304 http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/fstream
npm http request GET http://192.168.1.100:4873/binary
npm http request GET http://192.168.1.100:4873/pullstream
npm http request GET http://192.168.1.100:4873/setimmediate
npm http request GET http://192.168.1.100:4873/match-stream
npm http 200 http://192.168.1.100:4873/pullstream
npm http 200 http://192.168.1.100:4873/setimmediate
npm http 200 http://192.168.1.100:4873/binary
npm http 200 http://192.168.1.100:4873/match-stream
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
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/tape
npm http request GET http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/nock
npm http request GET http://192.168.1.100:4873/pouchdb-node
npm http request GET http://192.168.1.100:4873/bn.js
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/express-pouchdb
npm http request GET http://192.168.1.100:4873/proxyquire
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/request-promise
npm http request GET http://192.168.1.100:4873/leveldown-mobile
npm http request GET http://192.168.1.100:4873/supertest-as-promised
npm http request GET http://192.168.1.100:4873/tape-catch
npm http request GET http://192.168.1.100:4873/sinon
npm http request GET http://192.168.1.100:4873/supertest
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/tmp
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/forever-agent
npm http 304 http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/tape
npm http 200 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/socket.io-client
npm http 304 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/randomstring
npm http 304 http://192.168.1.100:4873/multiplex
npm http 200 http://192.168.1.100:4873/nock
npm http 304 http://192.168.1.100:4873/pouchdb-node
npm http 304 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/bn.js
npm http 304 http://192.168.1.100:4873/express-pouchdb
npm http 200 http://192.168.1.100:4873/js-extend
npm http 200 http://192.168.1.100:4873/proxyquire
npm http 200 http://192.168.1.100:4873/request-promise
npm http 200 http://192.168.1.100:4873/sinon
npm http 304 http://192.168.1.100:4873/tape-catch
npm http 200 http://192.168.1.100:4873/supertest-as-promised
npm http 200 http://192.168.1.100:4873/supertest
npm http 200 http://192.168.1.100:4873/uuid
npm http 200 http://192.168.1.100:4873/tmp
npm http 304 http://192.168.1.100:4873/leveldown-mobile
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
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/on-finished
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
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/serve-static
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/send
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
npm http 304 http://192.168.1.100:4873/destroy
npm http 304 http://192.168.1.100:4873/mime
npm http request GET http://192.168.1.100:4873/basic-auth
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/pouchdb-list
npm http request GET http://192.168.1.100:4873/pouchdb-auth
npm http request GET http://192.168.1.100:4873/pouchdb-find
npm http request GET http://192.168.1.100:4873/multiparty
npm http request GET http://192.168.1.100:4873/pouchdb-all-dbs
npm http request GET http://192.168.1.100:4873/compression
npm http request GET http://192.168.1.100:4873/header-case-normalizer
npm http request GET http://192.168.1.100:4873/cookie-parser
npm http request GET http://192.168.1.100:4873/pouchdb-vhost
npm http request GET http://192.168.1.100:4873/pouchdb-validation
npm http request GET http://192.168.1.100:4873/pouchdb-update
npm http request GET http://192.168.1.100:4873/pouchdb-size
npm http request GET http://192.168.1.100:4873/pouchdb-show
npm http request GET http://192.168.1.100:4873/pouchdb-security
npm http request GET http://192.168.1.100:4873/pouchdb-replicator
npm http request GET http://192.168.1.100:4873/pouchdb-rewrite
npm http request GET http://192.168.1.100:4873/pouchdb-wrappers
npm http 200 http://192.168.1.100:4873/basic-auth
npm http 200 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/multiparty
npm http 304 http://192.168.1.100:4873/pouchdb-find
npm http 304 http://192.168.1.100:4873/pouchdb-list
npm http 304 http://192.168.1.100:4873/pouchdb-all-dbs
npm http 200 http://192.168.1.100:4873/compression
npm http 200 http://192.168.1.100:4873/cookie-parser
npm http 200 http://192.168.1.100:4873/pouchdb-auth
npm http 200 http://192.168.1.100:4873/header-case-normalizer
npm http 200 http://192.168.1.100:4873/pouchdb-validation
npm http 304 http://192.168.1.100:4873/pouchdb-size
npm http 304 http://192.168.1.100:4873/pouchdb-update
npm http 304 http://192.168.1.100:4873/pouchdb-vhost
npm http 304 http://192.168.1.100:4873/pouchdb-replicator
npm http 304 http://192.168.1.100:4873/pouchdb-rewrite
npm http 304 http://192.168.1.100:4873/pouchdb-show
npm http 200 http://192.168.1.100:4873/pouchdb-wrappers
npm http 200 http://192.168.1.100:4873/pouchdb-security
npm http request GET http://192.168.1.100:4873/setprototypeof
npm http 200 http://192.168.1.100:4873/setprototypeof
npm http request GET http://192.168.1.100:4873/compressible
npm http request GET http://192.168.1.100:4873/on-headers
npm http 200 http://192.168.1.100:4873/compressible
npm http 200 http://192.168.1.100:4873/on-headers
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/stream-counter
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 200 http://192.168.1.100:4873/stream-counter
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/tiny-queue
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/argsarray
npm http 304 http://192.168.1.100:4873/es3ify
npm http 200 http://192.168.1.100:4873/argsarray
npm http 200 http://192.168.1.100:4873/tiny-queue
npm http 200 http://192.168.1.100:4873/pouchdb-promise
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
npm http request GET http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http request GET http://192.168.1.100:4873/pouchdb-plugin-error
npm http request GET http://192.168.1.100:4873/pouchdb
npm http request GET http://192.168.1.100:4873/promise-nodify
npm http request GET http://192.168.1.100:4873/pouchdb-system-db
npm http request GET http://192.168.1.100:4873/pouchdb-req-http-query
npm http request GET http://192.168.1.100:4873/secure-random
npm http 200 http://192.168.1.100:4873/base64url
npm http 200 http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http 200 http://192.168.1.100:4873/couchdb-calculate-session-id
npm http 200 http://192.168.1.100:4873/pouchdb
npm http 200 http://192.168.1.100:4873/pouchdb-plugin-error
npm http 200 http://192.168.1.100:4873/promise-nodify
npm http 200 http://192.168.1.100:4873/pouchdb-system-db
npm http 200 http://192.168.1.100:4873/pouchdb-req-http-query
npm http 200 http://192.168.1.100:4873/crypto-lite
npm http 200 http://192.168.1.100:4873/secure-random
npm http request GET http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/meow
npm http 200 http://192.168.1.100:4873/meow
npm http 200 http://192.168.1.100:4873/concat-stream
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
npm http request GET http://192.168.1.100:4873/get-stdin
npm http request GET http://192.168.1.100:4873/repeating
npm http 200 http://192.168.1.100:4873/get-stdin
npm http 200 http://192.168.1.100:4873/repeating
npm http request GET http://192.168.1.100:4873/is-finite
npm http 200 http://192.168.1.100:4873/is-finite
npm http request GET http://192.168.1.100:4873/number-is-nan
npm http 200 http://192.168.1.100:4873/number-is-nan
npm http request GET http://192.168.1.100:4873/aproba
npm http 200 http://192.168.1.100:4873/aproba
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/fruitdown
npm http request GET http://192.168.1.100:4873/es6-promise-pool
npm http request GET http://192.168.1.100:4873/level-write-stream
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/memdown
npm http request GET http://192.168.1.100:4873/localstorage-down
npm http request GET http://192.168.1.100:4873/pouchdb-collate
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/scope-eval
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/vuvuzela
npm http request GET http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/es6-promise-pool
npm http 200 http://192.168.1.100:4873/level-write-stream
npm http 200 http://192.168.1.100:4873/double-ended-queue
npm http 200 http://192.168.1.100:4873/fruitdown
npm http 200 http://192.168.1.100:4873/localstorage-down
npm http 200 http://192.168.1.100:4873/pouchdb-collate
npm http 200 http://192.168.1.100:4873/pouchdb-collections
npm http 200 http://192.168.1.100:4873/memdown
npm http 200 http://192.168.1.100:4873/scope-eval
npm http 200 http://192.168.1.100:4873/sublevel-pouchdb
npm http 200 http://192.168.1.100:4873/spark-md5
npm http 304 http://192.168.1.100:4873/through2
npm http 200 http://192.168.1.100:4873/levelup
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/js-extend
npm http 200 http://192.168.1.100:4873/vuvuzela
npm http request GET http://192.168.1.100:4873/d64
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http 200 http://192.168.1.100:4873/d64
npm http 200 http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/end-stream
npm http 200 http://192.168.1.100:4873/end-stream
npm http request GET http://192.168.1.100:4873/write-stream
npm http 200 http://192.168.1.100:4873/write-stream
npm http request GET http://192.168.1.100:4873/deferred-leveldown
npm http request GET http://192.168.1.100:4873/level-errors
npm http request GET http://192.168.1.100:4873/level-codec
npm http request GET http://192.168.1.100:4873/prr
npm http request GET http://192.168.1.100:4873/level-iterator-stream
npm http request GET http://192.168.1.100:4873/semver
npm http 200 http://192.168.1.100:4873/prr
npm http 200 http://192.168.1.100:4873/level-iterator-stream
npm http 200 http://192.168.1.100:4873/semver
npm http 200 http://192.168.1.100:4873/level-codec
npm http 200 http://192.168.1.100:4873/deferred-leveldown
npm http 200 http://192.168.1.100:4873/level-errors
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
npm http request GET http://192.168.1.100:4873/aws4
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/is-typedarray
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/caseless
npm http 200 http://192.168.1.100:4873/aws4
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 304 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/qs
npm http 200 http://192.168.1.100:4873/is-typedarray
npm http 200 http://192.168.1.100:4873/tough-cookie
npm WARN deprecated tough-cookie@2.2.2: ReDoS vulnerability parsing Set-Cookie https://nodesecurity.io/advisories/130
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 200 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/pinkie-promise
npm http 304 http://192.168.1.100:4873/chalk
npm http 200 http://192.168.1.100:4873/pinkie-promise
npm http 200 http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-function
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http 304 http://192.168.1.100:4873/jsonpointer
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
npm http request GET http://192.168.1.100:4873/sshpk
npm http request GET http://192.168.1.100:4873/jsprim
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
npm http request GET http://192.168.1.100:4873/dashdash
npm http request GET http://192.168.1.100:4873/getpass
npm http 304 http://192.168.1.100:4873/asn1
npm http 200 http://192.168.1.100:4873/getpass
npm http 200 http://192.168.1.100:4873/dashdash
npm http request GET http://192.168.1.100:4873/pull-stream
npm http 200 http://192.168.1.100:4873/pull-stream
npm http request GET http://192.168.1.100:4873/pull-core
npm http 200 http://192.168.1.100:4873/pull-core
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/readable-stream
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
npm http 200 http://192.168.1.100:4873/couchdb-objects
npm http 200 http://192.168.1.100:4873/couchdb-eval
npm http 200 http://192.168.1.100:4873/random-uuid-v4
npm http request GET http://192.168.1.100:4873/is-empty
npm http 200 http://192.168.1.100:4873/is-empty
npm http request GET http://192.168.1.100:4873/is-array
npm http request GET http://192.168.1.100:4873/pouchdb-extend
npm http request GET http://192.168.1.100:4873/pouchdb-upsert
npm http 200 http://192.168.1.100:4873/is-array
npm http 200 http://192.168.1.100:4873/pouchdb-extend
npm http 200 http://192.168.1.100:4873/pouchdb-upsert
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 304 http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/couchdb-render
npm http 304 http://192.168.1.100:4873/extend
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
npm http 304 http://192.168.1.100:4873/abstract-leveldown
npm http 200 http://192.168.1.100:4873/bindings
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
npm http 200 http://192.168.1.100:4873/propagate
npm http 200 http://192.168.1.100:4873/chai
npm http 200 http://192.168.1.100:4873/lodash
npm WARN deprecated lodash@2.4.1: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
npm http request GET http://192.168.1.100:4873/deep-eql
npm http request GET http://192.168.1.100:4873/assertion-error
npm http request GET http://192.168.1.100:4873/type-detect
npm http 200 http://192.168.1.100:4873/deep-eql
npm http 200 http://192.168.1.100:4873/assertion-error
npm http 200 http://192.168.1.100:4873/type-detect
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/ip
npm http 304 http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-http
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-leveldb
npm http request GET http://192.168.1.100:4873/pouchdb-core
npm http request GET http://192.168.1.100:4873/pouchdb-mapreduce
npm http request GET http://192.168.1.100:4873/pouchdb-replication
npm http 304 http://192.168.1.100:4873/pouchdb-mapreduce
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-http
npm http 304 http://192.168.1.100:4873/pouchdb-replication
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-leveldb
npm http 304 http://192.168.1.100:4873/pouchdb-core
npm http request GET http://192.168.1.100:4873/pouchdb-ajax
npm http request GET http://192.168.1.100:4873/pouchdb-binary-utils
npm http request GET http://192.168.1.100:4873/pouchdb-errors
npm http request GET http://192.168.1.100:4873/pouchdb-md5
npm http request GET http://192.168.1.100:4873/pouchdb-utils
npm http 304 http://192.168.1.100:4873/pouchdb-binary-utils
npm http 304 http://192.168.1.100:4873/pouchdb-md5
npm http 304 http://192.168.1.100:4873/pouchdb-errors
npm http 200 http://192.168.1.100:4873/pouchdb-utils
npm http 304 http://192.168.1.100:4873/pouchdb-ajax
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http 304 http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-leveldb-core
npm http request GET http://192.168.1.100:4873/leveldown
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-leveldb-core
npm http 200 http://192.168.1.100:4873/leveldown
npm http request GET http://192.168.1.100:4873/nan
npm http request GET http://192.168.1.100:4873/prebuild
npm http 304 http://192.168.1.100:4873/nan
npm http 200 http://192.168.1.100:4873/prebuild
npm http request GET http://192.168.1.100:4873/github-from-package
npm http request GET http://192.168.1.100:4873/expand-template
npm http request GET http://192.168.1.100:4873/ghreleases
npm http request GET http://192.168.1.100:4873/rc
npm http request GET http://192.168.1.100:4873/pump
npm http request GET http://192.168.1.100:4873/node-gyp
npm http request GET http://192.168.1.100:4873/os-homedir
npm http request GET http://192.168.1.100:4873/npmlog
npm http request GET http://192.168.1.100:4873/node-ninja
npm http request GET http://192.168.1.100:4873/noop-logger
npm http request GET http://192.168.1.100:4873/tar-stream
npm http request GET http://192.168.1.100:4873/simple-get
npm http request GET http://192.168.1.100:4873/tar-fs
npm http 200 http://192.168.1.100:4873/pump
npm http 200 http://192.168.1.100:4873/rc
npm http 200 http://192.168.1.100:4873/github-from-package
npm http 200 http://192.168.1.100:4873/ghreleases
npm http 200 http://192.168.1.100:4873/os-homedir
npm http 200 http://192.168.1.100:4873/expand-template
npm http 200 http://192.168.1.100:4873/node-gyp
npm http 200 http://192.168.1.100:4873/npmlog
npm http 200 http://192.168.1.100:4873/tar-stream
npm http 200 http://192.168.1.100:4873/tar-fs
npm http 200 http://192.168.1.100:4873/node-ninja
npm http 200 http://192.168.1.100:4873/simple-get
npm http 200 http://192.168.1.100:4873/noop-logger
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/simple-mime
npm http request GET http://192.168.1.100:4873/ghutils
npm http request GET http://192.168.1.100:4873/ghrepos
npm http request GET http://192.168.1.100:4873/url-template
npm http 304 http://192.168.1.100:4873/after
npm http 200 http://192.168.1.100:4873/ghutils
npm http 200 http://192.168.1.100:4873/simple-mime
npm http 200 http://192.168.1.100:4873/ghrepos
npm http 200 http://192.168.1.100:4873/url-template
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
npm http request GET http://192.168.1.100:4873/tar
npm http request GET http://192.168.1.100:4873/nopt
npm http request GET http://192.168.1.100:4873/path-array
npm http request GET http://192.168.1.100:4873/osenv
npm http request GET http://192.168.1.100:4873/which
npm http 304 http://192.168.1.100:4873/fstream
npm http 200 http://192.168.1.100:4873/tar
npm http 200 http://192.168.1.100:4873/nopt
npm http 200 http://192.168.1.100:4873/osenv
npm http 200 http://192.168.1.100:4873/path-array
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
npm http request GET http://192.168.1.100:4873/lodash.pad
npm http request GET http://192.168.1.100:4873/lodash.padend
npm http request GET http://192.168.1.100:4873/lodash.padstart
npm http 200 http://192.168.1.100:4873/lodash.padstart
npm http 200 http://192.168.1.100:4873/has-unicode
npm http 200 http://192.168.1.100:4873/lodash.padend
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
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/http-signature
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
npm http 304 http://192.168.1.100:4873/deep-extend
npm http 304 http://192.168.1.100:4873/strip-json-comments
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
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http 304 http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/ltgt
npm http 304 http://192.168.1.100:4873/ltgt
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/pouchdb-promise
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
npm http request GET http://192.168.1.100:4873/samsam
npm http request GET http://192.168.1.100:4873/formatio
npm http request GET http://192.168.1.100:4873/util
npm http request GET http://192.168.1.100:4873/lolex
npm http 200 http://192.168.1.100:4873/util
npm http 200 http://192.168.1.100:4873/lolex
npm http 200 http://192.168.1.100:4873/formatio
npm http 200 http://192.168.1.100:4873/samsam
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
npm http 304 http://192.168.1.100:4873/component-bind
npm http 304 http://192.168.1.100:4873/engine.io-client
npm http 304 http://192.168.1.100:4873/component-emitter
npm http 304 http://192.168.1.100:4873/socket.io-parser
npm http 304 http://192.168.1.100:4873/object-component
npm http 304 http://192.168.1.100:4873/indexof
npm http 304 http://192.168.1.100:4873/has-binary
npm http 304 http://192.168.1.100:4873/to-array
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/parseuri
npm http 304 http://192.168.1.100:4873/backo2
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/parseqs
npm http request GET http://192.168.1.100:4873/ws
npm http fetch GET https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http 304 http://192.168.1.100:4873/engine.io-parser
npm http 304 http://192.168.1.100:4873/parseqs
npm http 304 http://192.168.1.100:4873/parsejson
npm http 200 http://192.168.1.100:4873/component-inherit
npm http 200 http://192.168.1.100:4873/has-cors
npm http 304 http://192.168.1.100:4873/ws
npm http fetch 200 https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/utf8
npm http 304 http://192.168.1.100:4873/base64-arraybuffer
npm http 304 http://192.168.1.100:4873/arraybuffer.slice
npm http 304 http://192.168.1.100:4873/utf8
npm http 304 http://192.168.1.100:4873/blob
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
npm http 304 http://192.168.1.100:4873/benchmark
npm http 304 http://192.168.1.100:4873/json3
npm http request GET http://192.168.1.100:4873/superagent
npm http 200 http://192.168.1.100:4873/superagent
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/formidable
npm http request GET http://192.168.1.100:4873/reduce-component
npm http request GET http://192.168.1.100:4873/cookiejar
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
npm http request GET http://192.168.1.100:4873/resumer
npm http request GET http://192.168.1.100:4873/object-inspect
npm http 304 http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/defined
npm http 200 http://192.168.1.100:4873/resumer
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

Error: Command failed: cp: testBuildOrg//.git/objects/9f/85ee4e59a606752d8bee860a5610514b675385: No such file or directory
cp: testBuildOrg//.git/objects/9f/876eb7bc97447821e00e4cfe252b6a207452c7: No such file or directory
cp: testBuildOrg//.git/objects/9f/9c4df5ecc64efb2cfc5ad25c756949a4ea679d: No such file or directory
cp: testBuildOrg//.git/objects/9f/a1f7f67f777ca263bc0eeac27c3912f61c9c16: No such file or directory
cp: testBuildOrg//.git/objects/9f/a2a0b93b99e0751b1e9bd693c0e3bf66d76306: No such file or directory
cp: testBuildOrg//.git/objects/9f/a4d5843762753fd3e571d50b83c87d8b9bf05d: No such file or directory
cp: testBuildOrg//.git/objects/9f/a62a22407c60f5f5573dafe9addf98ee09e646: No such file or directory
cp: testBuildOrg//.git/objects/9f/acc7f94bda026a01dcf2ae89a73204df1bd475: No such file or directory
cp: testBuildOrg//.git/objects/9f/c662a6b21df83882cd2bbd0e33580966d0c766: No such file or directory
cp: testBuildOrg//.git/objects/9f/c7d66e312c0522049b164dc1ec16e408c698f3: No such file or directory
cp: testBuildOrg//.git/objects/9f/d7ad0b86902322d6e44ded39e7493e1e8108fa: No such file or directory
cp: testBuildOrg//.git/objects/9f/d9c529fbc5a9d1d5477d35ee3a59a27215fcbe: No such file or directory
cp: testBuildOrg//.git/objects/9f/da42331b72a404859ce587e66c3cb63d993ea7: No such file or directory
cp: testBuildOrg//.git/objects/9f/eb01458847db2b27edd8161e46f6a3dda12788: No such file or directory
cp: testBuildOrg//.git/objects/9f/eeaa84463ad5c9740d098a7fa2e095df8ffc69: No such file or directory
cp: testBuildOrg//.git/objects/9f/fd84ddc5f685030a0460db32a98b9fec823a5a: No such file or directory
cp: testBuildOrg//.git/objects/a5/eea73348af90f049d06c981e95fad57a589bd4: No such file or directory
cp: testBuildOrg//.git/objects/a5/f9640bae997850ccea2298d09ad1e3f41d0dcf: No such file or directory
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
cp: testBuildOrg//.git/objects/ae: unable to copy extended attributes to testBuild/.git/objects/ae: No such file or directory
cp: testBuildOrg//.git/objects/ae: No such file or directory
cp: testBuildOrg//.git/objects/b6/e65e780f2fdecf25f78a6571b4cffeeb7e2645: No such file or directory
cp: testBuildOrg//.git/objects/b6/e70d0892e9bcb549bf7da260f6372c477c837a: No such file or directory
cp: testBuildOrg//.git/objects/b6/e981d5bf1fce8267d69ced0ab1a46820091a13: No such file or directory
cp: testBuildOrg//.git/objects/b6/e9bbfb73ff439ee345819fae787fce1223e647: No such file or directory
cp: testBuildOrg//.git/objects/b6/f75d59f57a0bbb56dd1eff3faafab1f74b2ca1: No such file or directory
cp: testBuildOrg//.git/objects/b6/f825a053b74204b279026113359b140c56d083: No such file or directory
cp: testBuildOrg//.git/objects/b6/febee29148e2746e4352ed594989c815948e4a: No such file or directory
cp: testBuildOrg//.git/objects/b6/ff3b12c32a651030e5b5b4c2dace26f9c6931c: No such file or directory
cp: testBuildOrg//.git/objects/b6/ff514bc2dc6c639895a6a8f6b78c97b3910dda: No such file or directory
cp: testBuildOrg//.git/objects/b7/a71bbed68a26c2b0aebfa566a89eb457469a28: No such file or directory
cp: testBuildOrg//.git/objects/b7/b00f1f7daea3489edcee1c36ca071f77c8a36a: No such file or directory
cp: testBuildOrg//.git/objects/b7/b03457065b734c7f1b0d66e42e1b8e33d4ba49: No such file or directory
cp: testBuildOrg//.git/objects/b7/b44a6766efbc44a2463542171f32392c7fd2a8: No such file or directory
cp: testBuildOrg//.git/objects/b7/b501ac31a41ca263bc79d8a11149902b6ffd52: No such file or directory
cp: testBuildOrg//.git/objects/b7/d3db03642fab1cb63ceb45d268ad6382795d7d: No such file or directory
cp: testBuildOrg//.git/objects/b7/d43c894020b79ab715d029480ece8618c6e5cc: No such file or directory
cp: testBuildOrg//.git/objects/b7/d6d8e9721af5dce836bf79be1ff592eb1a63bb: No such file or directory
cp: testBuildOrg//.git/objects/b7/d9e525d0edbfde80534e0b7f1ea86818a82dfc: No such file or directory
cp: testBuildOrg//.git/objects/b7/ea81f0519c1181e41da5f2a9925bcd5ad32aec: No such file or directory
cp: testBuildOrg//.git/objects/b7/f3d175cede75fe5d1639d76ce4116205176f29: No such file or directory
cp: testBuildOrg//.git/objects/b7/f602434fe8e02f6aa76ab2964344e017fd6651: No such file or directory
cp: testBuildOrg//.git/objects/b7/ff6de7b1670adf1bef78a38a95835ee98ec52b: No such file or directory
cp: testBuildOrg//.git/objects/b8/53865a6bd9f8c25d10ef7ff982f5dc7e715615: No such file or directory
cp: testBuildOrg//.git/objects/b8/53deae203a660bae68d51367c1041473da4954: No such file or directory
cp: testBuildOrg//.git/objects/b8/5fd7103aeaac788eedab4b413d1ab712a1446e: No such file or directory
cp: testBuildOrg//.git/objects/b8/6327b0b98368253ecc493ec09f0817817a7b0a: No such file or directory
cp: testBuildOrg//.git/objects/b8/7fe5d0ddca2e7c119a3514041d92a174b2a5a0: No such file or directory
cp: testBuildOrg//.git/objects/b8/88650108b005f5f3ca99eea86f3edd8648ef70: No such file or directory
cp: testBuildOrg//.git/objects/b8/8a05f576bf8fb8c605debd5cc1fee657215f55: No such file or directory
cp: testBuildOrg//.git/objects/b8/9c3955111ecb0d16db584f9e2c075a4e8b6d88: No such file or directory
cp: testBuildOrg//.git/objects/b8/9ebe525fb0d959ba165219d326c7818de57e76: No such file or directory
cp: testBuildOrg//.git/objects/b8/a4982a63ce76efafc721ecc539d43ab9511229: No such file or directory
cp: testBuildOrg//.git/objects/b8/a4fff5cfa15daa7a155b86dc645bb3b98e5e64: No such file or directory
cp: testBuildOrg//.git/objects/b8/a821195486f4d356468c881da5539b82057a15: No such file or directory
cp: testBuildOrg//.git/objects/b8/a9768cd78a0fa2a32700ca09feeb0935e61004: No such file or directory
cp: testBuildOrg//.git/objects/b8/b49964b07dd4d84db0d55524444cc6cede4448: No such file or directory
cp: testBuildOrg//.git/objects/b8/ba588bb7101a20abaddc030f809f56b53b5ee4: No such file or directory
cp: testBuildOrg//.git/objects/b8/bb5b341c7062bb9b5fd42e41cd0194d941dc0b: No such file or directory
cp: testBuildOrg//.git/objects/b8/be062fafd2921957ca706ff1af234a7eb7881e: No such file or directory
cp: testBuildOrg//.git/objects/b8/c22a8dffdafe6106100eb2a8a65700e14fb2b4: No such file or directory
cp: testBuildOrg//.git/objects/b8/ccb9f7bfa8f766ea53a0374995f1cd91de805c: No such file or directory
cp: testBuildOrg//.git/objects/b8/d20aa8eaa9091a6891e65a49e12ae7cfdaee73: No such file or directory
cp: testBuildOrg//.git/objects/b8/ed845d6144f5f2edc645044cfb60a3c18b14f2: No such file or directory
cp: testBuildOrg//.git/objects/b8/efe62e34d308c561cf5ec49d40ef7a10296fe9: No such file or directory
cp: testBuildOrg//.git/objects/b8/f1913f739f23e802ef943707592f6b9ef331a8: No such file or directory
cp: testBuildOrg//.git/objects/b8/fef24b7082fe0d2a4fbb27763593dad0e842f5: No such file or directory
cp: testBuildOrg//.git/objects/b8/ff39ac18611fc5bab10137af7adc20e02b58ce: No such file or directory
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
cp: testBuildOrg//.git/objects/b9/d819c8f4ec6d240f2e0cda4d294ae18622c563: No such file or directory
cp: testBuildOrg//.git/objects/b9/d86523b12a383b9583388c1c059e465227817e: No such file or directory
cp: testBuildOrg//.git/objects/b9/dab625f5110803ac05855c1b2d1d33587e8a77: No such file or directory
cp: testBuildOrg//.git/objects/b9/dcf8a0d14e2ef54b43180b84826543c1725337: No such file or directory
cp: testBuildOrg//.git/objects/b9/df64211c6b6c4bce9b467fbe6759023f2c9fe2: No such file or directory
cp: testBuildOrg//.git/objects/b9/ea373db91bb2a5c0e0bcc6967a16380dbdf21b: No such file or directory
cp: testBuildOrg//.git/objects/b9/ec7d76913c7fc572ec8cdaae20338bd6d5fb84: No such file or directory
cp: testBuildOrg//.git/objects/b9/f5b8528e98ab8cbe332b4bc78af47f9bc076e1: No such file or directory
cp: testBuildOrg//.git/objects/ba/128588ece2bcf73991c936aad60d815382544e: No such file or directory
cp: testBuildOrg//.git/objects/ba/169e48097ae5d461453ad6396efdb66ab4ec12: No such file or directory
cp: testBuildOrg//.git/objects/ba/17c0cae8b61a4c1d2b0210258d762ac38bd511: No such file or directory
cp: testBuildOrg//.git/objects/ba/3107672a62f9f98edd4400b5495224ca406d90: No such file or directory
cp: testBuildOrg//.git/objects/ba/3acfdfb6e68542d38ffa77fa8571da9084b3c8: No such file or directory
cp: testBuildOrg//.git/objects/ba/3f7d71b28664e0b4c3c5ac2aae7cf1cce52f54: No such file or directory
cp: testBuildOrg//.git/objects/ba/43b4bf3a8f4e151211309cc2f0056b412deb9e: No such file or directory
cp: testBuildOrg//.git/objects/ba/4408e9fdda699c503a6e3faff0315137ff6ce0: No such file or directory
cp: testBuildOrg//.git/objects/ba/46c2d73eb5bc14aeb21e095dc2cb690c11eaa3: No such file or directory
cp: testBuildOrg//.git/objects/ba/584b544d5e7cb40c1fb96a251de7896cfe9c84: No such file or directory
cp: testBuildOrg//.git/objects/ba/72822e8728ef2951005e49b6c27a2f1da6572d: No such file or directory
cp: testBuildOrg//.git/objects/ba/80f79a88edb1fff57885ce5cb9026278108b24: No such file or directory
cp: testBuildOrg//.git/objects/ba/847d4c4e4eae4d87ea95d85f109db8cf3fa065: No such file or directory
cp: testBuildOrg//.git/objects/ba/89b9b7e42c2c120c0f62fa7f89945da03dee7a: No such file or directory
cp: testBuildOrg//.git/objects/ba/8a10517e73e213e4c649be18f2755485fba076: No such file or directory
cp: testBuildOrg//.git/objects/ba/8e1db34cdc5ae3227487f688661eaaa4a77bd5: No such file or directory
cp: testBuildOrg//.git/objects/ba/a16a3d36a20f2e97af417e535b3825bd00ddf6: No such file or directory
cp: testBuildOrg//.git/objects/ba/a330adf06b65a0155b1257fda391294cc125db: No such file or directory
cp: testBuildOrg//.git/objects/ba/a3f1de36e86ab443d7e5aa98c6215792549f28: No such file or directory
cp: testBuildOrg//.git/objects/ba/a8a671b13b582fb2b65524d2486bf2e43bf4b8: No such file or directory
cp: testBuildOrg//.git/objects/ba/abfeb08d4c3d366fc1730893da48e5c00c08a6: No such file or directory
cp: testBuildOrg//.git/objects/ba/aef6a284735d503fa193eb8aec9b6b0c38bb1f: No such file or directory
cp: testBuildOrg//.git/objects/ba/b3f0547208328cbbfaf3f903b9c258069993e0: No such file or directory
cp: testBuildOrg//.git/objects/ba/b421c55c2ffd48a4db64dd0fb86d144cb6c5ac: No such file or directory
cp: testBuildOrg//.git/objects/ba/c41c2add96cb1c6061a418a6a3e1a2c9f4ac09: No such file or directory
cp: testBuildOrg//.git/objects/ba/c4dc60b13e6a90c646a7a3485d4e24aa7b491e: No such file or directory
cp: testBuildOrg//.git/objects/ba/c7d2d8d8b65428b47ab520b921ba99afeb6d86: No such file or directory
cp: testBuildOrg//.git/objects/ba/d1a80811cfbe55c9d45c7afb8156f4b731cd01: No such file or directory
cp: testBuildOrg//.git/objects/ba/d4f6ac67d634274460aa25256c6479650dd56c: No such file or directory
cp: testBuildOrg//.git/objects/ba/d561e2ab6b453975cfe9f2eda6faba76bd62a6: No such file or directory
cp: testBuildOrg//.git/objects/ba/e0cc139e9e578076bb28fa9fd2779f7fb4d367: No such file or directory
cp: testBuildOrg//.git/objects/ba/e47c7af0ff802ccbd07c37124d066353c0917d: No such file or directory
cp: testBuildOrg//.git/objects/ba/fa2be5cf41faa7a92d28e5acf40b8a88637d63: No such file or directory
cp: testBuildOrg//.git/objects/ba/fbbef8910a63ecc4c6ccdd797f5a74a2ec2591: No such file or directory
cp: testBuildOrg//.git/objects/ba/fbd8d877a8ac8c95b1f72100c56035adfd6456: No such file or directory
cp: testBuildOrg//.git/objects/ba/fc3f68c4774444d9f54a30b282b2c0befe4a46: No such file or directory
cp: testBuildOrg//.git/objects/bb/4658c70fb47c91a08120d42f6be7d64f04a98d: No such file or directory
cp: testBuildOrg//.git/objects/bb/539ecfdfc7e3f44aad03018d093a3d461d47c1: No such file or directory
cp: testBuildOrg//.git/objects/bb/6009f9b1840b1a04eafd7419926d43beaeac37: No such file or directory
cp: testBuildOrg//.git/objects/bb/65c1e77e8286cb17af1614f9f018d20e570e4b: No such file or directory
cp: testBuildOrg//.git/objects/bb/6b81ba65892b8604520ba0153c3fc444f73257: No such file or directory
cp: testBuildOrg//.git/objects/bb/7529b1878026d14720a3df8e4c1a90aa957be2: No such file or directory
cp: testBuildOrg//.git/objects/bb/dab4715f693fad411f84e2f243b9d108fa2941: No such file or directory
cp: testBuildOrg//.git/objects/bb/e3f60c96cc7d450b352d640ba2bb8fa677f65e: No such file or directory
cp: testBuildOrg//.git/objects/bb/e63e76457e6004da2f5daab28ba8172780ed51: No such file or directory
cp: testBuildOrg//.git/objects/bb/f0d939085169046915c8faff7412422dc4eaec: No such file or directory
cp: testBuildOrg//.git/objects/bb/f0e399bb7a609827a9952f3820a1aae663910e: No such file or directory
cp: testBuildOrg//.git/objects/bc/2b56ae3f4af2db7212ba79a81a272ab1317861: No such file or directory
cp: testBuildOrg//.git/objects/bc/2b57e80f1a6ded7ba38a0ea95a43babeb5cb0a: No such file or directory
cp: testBuildOrg//.git/objects/bc/302f77347d295c6def84cda4e49234e8ff0054: No such file or directory
cp: testBuildOrg//.git/objects/bc/3e5d172b64ad5913e6d976dd1491562b4491ba: No such file or directory
cp: testBuildOrg//.git/objects/bc/4f2f5e942fa4170d44a92cbcac53607351482b: No such file or directory
cp: testBuildOrg//.git/objects/bc/536470681b43391d9477f80c71275df54ea85f: No such file or directory
cp: testBuildOrg//.git/objects/bc/5b63721152656af0b4af0337a106fc5d37a20d: No such file or directory
cp: testBuildOrg//.git/objects/bc/664c72b59842123e34e234628dd0c07c1a7530: No such file or directory
cp: testBuildOrg//.git/objects/bc/69dd583aaba15e6711ec1d5e552fa3b55282e2: No such file or directory
cp: testBuildOrg//.git/objects/bc/6b357e08a7e67fc63705250e995d961b219353: No such file or directory
cp: testBuildOrg//.git/objects/bc/80519d3588138c7ef0b8c1e344385cfc2216dd: No such file or directory
cp: testBuildOrg//.git/objects/bc/81153f7b0f7d3cb5824f5ba9e5ebb800620429: No such file or directory
cp: testBuildOrg//.git/objects/bc/87e56523754ffa3f192a0ce0e17361c24f6824: No such file or directory
cp: testBuildOrg//.git/objects/bc/89e2a04300ff11b5fcb79cfbb42c4fee057cf5: No such file or directory
cp: testBuildOrg//.git/objects/bc/8d5026d1c0f5185600c2f73f55715c95e16325: No such file or directory
cp: testBuildOrg//.git/objects/bc/8dec674ffa8f1c81fd0cb2cb9a7c8a1b7c4f2d: No such file or directory
cp: testBuildOrg//.git/objects/bc/a1aec166d5b91e62c70ed3d0c15b17297110e9: No such file or directory
cp: testBuildOrg//.git/objects/bc/ad1229856df887ed4c54bd9bd4cf806f2db2f2: No such file or directory
cp: testBuildOrg//.git/objects/bc/b0afc5a195ee85dc18d678bd8c659d07b0ac9a: No such file or directory
cp: testBuildOrg//.git/objects/bc/b545fe293b2dfec21ca0367a49b7c61233f07f: No such file or directory
cp: testBuildOrg//.git/objects/bc/df06b8cedbd3fdc1c33e9f978187c11a3beedf: No such file or directory
cp: testBuildOrg//.git/objects/bc/e2fef6f67e55b892566ae5f711927f84c61a5a: No such file or directory
cp: testBuildOrg//.git/objects/bc/e47214c81d829660c8cf374bc69422903a8208: No such file or directory
cp: testBuildOrg//.git/objects/bc/e79d0185e8d2762edd51a53bfe5c700a9678aa: No such file or directory
cp: testBuildOrg//.git/objects/bc/ecc5c6ffffe86a798f0672925e1d0b1ab467bd: No such file or directory
cp: testBuildOrg//.git/objects/bc/f258d878759df4196bea1fe01fa87c6c8d40e1: No such file or directory
cp: testBuildOrg//.git/objects/bc/f70a8fbe858db1971eab0db3ac3240e62b72d5: No such file or directory
cp: testBuildOrg//.git/objects/bc/f8b2d609b00a1e73f27ff52371a5eb8a6675ee: No such file or directory
cp: testBuildOrg//.git/objects/bc/ffa052bd59a79ee5ae8400bc613810e96ef784: No such file or directory
cp: testBuildOrg//.git/objects/c0/fcaf3fe36db3e42dba3fa2e89e89fc4a6dfec4: No such file or directory
cp: testBuildOrg//.git/objects/c1/72a344e5e85857077f14385af4edad995ee26f: No such file or directory
cp: testBuildOrg//.git/objects/c1/794c376296078013c8dd8d8677b062eb278707: No such file or directory
cp: testBuildOrg//.git/objects/c1/7965f765fe41d82a4b96535d69cb1d9b3ed74b: No such file or directory
cp: testBuildOrg//.git/objects/c1/7a6bd60163cc7189bbdb8087ad599c2260adad: No such file or directory
cp: testBuildOrg//.git/objects/c1/7c777583f38d72609b35782255c4a36289c96c: No such file or directory
cp: testBuildOrg//.git/objects/c1/8044360b0cbfc3cd0085b6c9c80a1a1e59c0b8: No such file or directory
cp: testBuildOrg//.git/objects/c1/81aaac7876b259f526e9ca506f97be52721628: No such file or directory
cp: testBuildOrg//.git/objects/c1/8583e1844471baab337525656d6efc6dfe934b: No such file or directory
cp: testBuildOrg//.git/objects/c1/8eec88807e2dd21af3e398c84445de8b816da8: No such file or directory
cp: testBuildOrg//.git/objects/c1/926237e43177bcd339d3a375115b8c46e6786d: No such file or directory
cp: testBuildOrg//.git/objects/c1/af5ad7f328c2578e7195bdce905a935e543505: No such file or directory
cp: testBuildOrg//.git/objects/c1/c172d42b21f02014c5d8e8d121b3e1959fdcdd: No such file or directory
cp: testBuildOrg//.git/objects/c1/c65d467609369f7b47494528d8843599a7a752: No such file or directory
cp: testBuildOrg//.git/objects/c1/c7ecc31df3e0e864d1b2f6431c0f3ab5b9ac19: No such file or directory
cp: testBuildOrg//.git/objects/c1/d1007f6d9fc8622e7ab434b2720a42fe3a43cc: No such file or directory
cp: testBuildOrg//.git/objects/c1/e201075fe5c7565e7914cc5cc92393d09779bf: No such file or directory
cp: testBuildOrg//.git/objects/c1/e6f5edf21a7cec36bb8744cc3fc6cda031e10a: No such file or directory
cp: testBuildOrg//.git/objects/c1/e9930b97bb3a7cfa2a0ee44fcbcee4f2c33c19: No such file or directory
cp: testBuildOrg//.git/objects/c1/f1271d3995688e1b2d40b0f92e854373519769: No such file or directory
cp: testBuildOrg//.git/objects/c2/362f3dbf24c15e1df8256ac0fea5ec2719daab: No such file or directory
cp: testBuildOrg//.git/objects/c2/3922db0265093229e9f435d028504c18daee3e: No such file or directory
cp: testBuildOrg//.git/objects/c2/3b194ea9b851bb6d49b52ad458eb3214cca734: No such file or directory
cp: testBuildOrg//.git/objects/c2/3bf7c0cfe69878964ec12d36b5b2e28d411cb4: No such file or directory
cp: testBuildOrg//.git/objects/c2/3c3c65beb22e8b21dea74ccd2ae4987e9a1f49: No such file or directory
cp: testBuildOrg//.git/objects/c2/3efd8eb7f99f36e2e856dda230e3d9cf4b5bcf: No such file or directory
cp: testBuildOrg//.git/objects/c2/418e5d39b7455973ddacced3190d2a655e9ad9: No such file or directory
cp: testBuildOrg//.git/objects/c2/49f8abff886536c147e5b4b6f28bfb55ff68a3: No such file or directory
cp: testBuildOrg//.git/objects/c2/4cf456decd29e64cfdc0d8257e7ab91368afd3: No such file or directory
cp: testBuildOrg//.git/objects/c2/5654987f8577a3e0a728c50b75df38cd6af260: No such file or directory
cp: testBuildOrg//.git/objects/c2/5750eaa2be5910eee98b0fd7fadc183159cba2: No such file or directory
cp: testBuildOrg//.git/objects/c2/5a5bd6cc49538d6b5ba4965635811072426ffb: No such file or directory
cp: testBuildOrg//.git/objects/c2/689ed84f67b73a74c734b9326b64096ea9a730: No such file or directory
cp: testBuildOrg//.git/objects/c2/6a9ef372af30d6a63d0dc797d7a7750a25d12f: No such file or directory
cp: testBuildOrg//.git/objects/c2/7a0025366084cb8af4e2aadabec4ae0b7a27ed: No such file or directory
cp: testBuildOrg//.git/objects/c2/7da76ad94ec0091ac8f7dbede53937aaa28714: No such file or directory
cp: testBuildOrg//.git/objects/c2/87417d77d401fc6f86e8647e7caa72964fc4da: No such file or directory
cp: testBuildOrg//.git/objects/c2/89374ff5a55829d22a4a436912d9aba3bb9774: No such file or directory
cp: testBuildOrg//.git/objects/c2/8cc77debae00a5508723fad86a0ab8fef59ec3: No such file or directory
cp: testBuildOrg//.git/objects/c2/f4c8d3cc872fc5b2ff8317fc2b3c96a9283ee0: No such file or directory
cp: testBuildOrg//.git/objects/c2/f88c8f809567bc03b71c83a11cffdafeaeb079: No such file or directory
cp: testBuildOrg//.git/objects/c2/fa0447e996c053e79eb42eda87422e084a5f67: No such file or directory
cp: testBuildOrg//.git/objects/c3/4f1393d37adb0ca3d124a84687e95b89362393: No such file or directory
cp: testBuildOrg//.git/objects/c3/55d2625e6cacff5905dc9d332b117fabc11591: No such file or directory
cp: testBuildOrg//.git/objects/c3/56c354f5f7347739cdf0225a6d7a8216c86e79: No such file or directory
cp: testBuildOrg//.git/objects/c3/680c86ef1102f8999875324a2beadbf2e05eda: No such file or directory
cp: testBuildOrg//.git/objects/c3/68d7d6ccb8f57c145b82dfe181ff9dbe1e847e: No such file or directory
cp: testBuildOrg//.git/objects/c3/6c3fe0201398cd23bb88fa54423b3115fe2a0f: No such file or directory
cp: testBuildOrg//.git/objects/c3/710eaad17b67d824edf803881426ae7959f88b: No such file or directory
cp: testBuildOrg//.git/objects/c3/7c30777c182d798e3ae94ea5af654925a67110: No such file or directory
cp: testBuildOrg//.git/objects/c3/7d0c004b159e5e1f10594518a1f807bc0efdb2: No such file or directory
cp: testBuildOrg//.git/objects/c3/873d1b0c1442aca4d19ae8cafb6a0f36a02044: No such file or directory
cp: testBuildOrg//.git/objects/c3/8c9a0b89a220c4981c5e895e231980b2594271: No such file or directory
cp: testBuildOrg//.git/objects/c3/966e08a29433127dfeda802de9f32fa29d1fb8: No such file or directory
cp: testBuildOrg//.git/objects/c3/994deff78d798db53a1cafb11097331c8acd8b: No such file or directory
cp: testBuildOrg//.git/objects/c3/9d7825ad5ae6d328ebda7301e8559a200cac0a: No such file or directory
cp: testBuildOrg//.git/objects/c3/a5ee833a3ca94409e94cbf1f5b8c799aa22758: No such file or directory
cp: testBuildOrg//.git/objects/c3/a6db56f41d18705af20d2a8f17157895a07679: No such file or directory
cp: testBuildOrg//.git/objects/c3/b74e026f6e24d9f572614bd8d54ca27446b3ca: No such file or directory
cp: testBuildOrg//.git/objects/c3/bd16977bcadb3ebb616d44a9a5880b9487683c: No such file or directory
cp: testBuildOrg//.git/objects/c3/be3667ebdb84f9242e0ef681f6ff5a2c071c85: No such file or directory
cp: testBuildOrg//.git/objects/c3/be6e515551f53c482ae62a3c8954ed5372f635: No such file or directory
cp: testBuildOrg//.git/objects/c3/c617ba70c0cdd9502b2495e5a9a1155c684081: No such file or directory
cp: testBuildOrg//.git/objects/c3/c61bf8b71a01f4fd9dded13ada92560445d957: No such file or directory
cp: testBuildOrg//.git/objects/c3/c99e3b47e7ff491e9f36a082160ebb88f9b398: No such file or directory
cp: testBuildOrg//.git/objects/c3/cde4ab8a8300fdd33aed2b2b321eda6fa6ed77: No such file or directory
cp: testBuildOrg//.git/objects/c3/d91a9baddc6883302474849ce016358f936b05: No such file or directory
cp: testBuildOrg//.git/objects/c3/db73722c0ba172ff5a71d90e5aa4a4d1e07335: No such file or directory
cp: testBuildOrg//.git/objects/c3/dd232667d674407d2944178f3066337dee9717: No such file or directory
cp: testBuildOrg//.git/objects/c3/e1efd3d82f3dffcc61521860bc71565ebf5e50: No such file or directory
cp: testBuildOrg//.git/objects/c3/e874f1ea0ae991dc2f9a4cb836df63dbef8918: No such file or directory
cp: testBuildOrg//.git/objects/c3/e96270a812326db71c596f7c5b0e4632565cc9: No such file or directory
cp: testBuildOrg//.git/objects/c3/ee53fe6bad37298ef97f3e7a9715fbabb36770: No such file or directory
cp: testBuildOrg//.git/objects/c3/f4640dc2bf517f77cd3670f73e38cd2981a844: No such file or directory
cp: testBuildOrg//.git/objects/c3/f68d4c82ec2e69d54a1742410b1caeea901b01: No such file or directory
cp: testBuildOrg//.git/objects/c3/fbe8be7d472b8658a5694069047b66ace9caaf: No such file or directory
cp: testBuildOrg//.git/objects/c4/942797bcd9fb1a194e37176684dfbb202b908c: No such file or directory
cp: testBuildOrg//.git/objects/c4/9dd0904c72b295450b360eebf3a4ce0dbb71fa: No such file or directory
cp: testBuildOrg//.git/objects/c4/a051e5c7b59d418acf47e7ffc32bc5197f2acf: No such file or directory
cp: testBuildOrg//.git/objects/c4/a3e11d7d3c016c413b28ad02aed5cc0cf4771d: No such file or directory
cp: testBuildOrg//.git/objects/c4/aa36441bb07b07b03279f7d943afef4fcd4562: No such file or directory
cp: testBuildOrg//.git/objects/c4/b221016c28ddf9d311ef7e5654eb15a1d6695a: No such file or directory
cp: testBuildOrg//.git/objects/c4/b53ae2f01156213d3f6c71d91c98628c965dc4: No such file or directory
cp: testBuildOrg//.git/objects/c4/befbd7c0af6ce4be43b3e7730ef3a4b8303942: No such file or directory
cp: testBuildOrg//.git/objects/c4/bfca7b4bb3e1f844549aeb6f7e0367edb9257d: No such file or directory
cp: testBuildOrg//.git/objects/c4/d5736ff86b76f1e418e7076e8cbbb7350342fc: No such file or directory
cp: testBuildOrg//.git/objects/c4/dc66861b5dfe36fa8fba7f2af43f44c979bd4c: No such file or directory
cp: testBuildOrg//.git/objects/c4/dccd07b7babca942ae1ee849b4ebe49c611fd1: No such file or directory
cp: testBuildOrg//.git/objects/c4/df4e3ae7930281bb55161190d519e5fefb293c: No such file or directory
cp: testBuildOrg//.git/objects/c4/e91218a476bb772c4a38988a08622700ea7a7c: No such file or directory
cp: testBuildOrg//.git/objects/c4/eae9c1b610c66c1779b91b4ca87e87c2815ad6: No such file or directory
cp: testBuildOrg//.git/objects/c4/f4684c001cda3e9534d928e13fff6f0549249a: No such file or directory
cp: testBuildOrg//.git/objects/c5/41d200d31fc2acc839c4be495665c853e55af0: No such file or directory
cp: testBuildOrg//.git/objects/c5/425bd451c32bef327aae015346551865c26652: No such file or directory
cp: testBuildOrg//.git/objects/c5/4c0d272a2c763fb10179471138243f48a74b01: No such file or directory
cp: testBuildOrg//.git/objects/c5/52aca6c83e4f60164c5ee7fcdc081bcbb4e91d: No such file or directory
cp: testBuildOrg//.git/objects/c5/55ef8aef053ac4c08b4c58c046555ea23d551b: No such file or directory
cp: testBuildOrg//.git/objects/c5/588d496b1a8309abbfb4f16080532b2f82983d: No such file or directory
cp: testBuildOrg//.git/objects/c5/5a7872585c20cb9b9f07f45e452eeeec0dcea1: No such file or directory
cp: testBuildOrg//.git/objects/c5/5b24a3b5644277a6f8481cce4390eeb3eefd92: No such file or directory
cp: testBuildOrg//.git/objects/c5/5cdcd25ad9767f2f9238941703c265432f6ce3: No such file or directory
cp: testBuildOrg//.git/objects/c5/6370531586f6eeeb58a76a1fd7a7bd433582ee: No such file or directory
cp: testBuildOrg//.git/objects/c5/6f6cdeba7c02fa2adec61d74c8eead035ad510: No such file or directory
cp: testBuildOrg//.git/objects/c5/7259d23c730341cb0dd5b7e037c7396f14efec: No such file or directory
cp: testBuildOrg//.git/objects/c5/76ace8c61cc8f7657cf8135d70d98670db5519: No such file or directory
cp: testBuildOrg//.git/objects/c5/7df7e8d6c5e022590ad753ea88e72ffb820733: No such file or directory
cp: testBuildOrg//.git/objects/c5/7fff09b6624e034064190e1e4fcfd4b1566ea1: No such file or directory
cp: testBuildOrg//.git/objects/c5/89e0d5f584560e369514bcb4551f5bf495010b: No such file or directory
cp: testBuildOrg//.git/objects/c5/967c47e0a4ba6c83b34054560c9538114d6449: No such file or directory
cp: testBuildOrg//.git/objects/c5/9eb5ac206adac72f40ced41d6b4e511f482425: No such file or directory
cp: testBuildOrg//.git/objects/c5/a0b0a7832627291665a544d96d8851eb237826: No such file or directory
cp: testBuildOrg//.git/objects/c5/a416bea5cdb8f822ea8037febe485e5382ce44: No such file or directory
cp: testBuildOrg//.git/objects/c5/a647f5c44b66a6cc5ae8c09e25b2e0acd2d104: No such file or directory
cp: testBuildOrg//.git/objects/c5/a843613dfaeebd6a10c0a88d8154d285573569: No such file or directory
cp: testBuildOrg//.git/objects/c5/aa6f2406771911cb4583736e397bff58267015: No such file or directory
cp: testBuildOrg//.git/objects/c5/da174c31ab794107eacfa4b5016fe608a1df5f: No such file or directory
cp: testBuildOrg//.git/objects/c5/de1fe0b94e141bea7f96af0abb6231e9e52dd8: No such file or directory
cp: testBuildOrg//.git/objects/c5/e4aaabbc400607399fcf6f6d376914b43c782e: No such file or directory
cp: testBuildOrg//.git/objects/c5/e7b4b006ae612cbaf97e000933d6579043752a: No such file or directory
cp: testBuildOrg//.git/objects/c5/fe209f61a31104f1600dea692e1cadc1c288af: No such file or directory
cp: testBuildOrg//.git/objects/c6/036b23b666c6cca26836225bc30bf3876f0768: No such file or directory
cp: testBuildOrg//.git/objects/c6/042bc85b24d695102f661a6df447a1a4270b10: No such file or directory
cp: testBuildOrg//.git/objects/c6/0c7234f621ee7f4c072cb9b4018d0f4ac1bbd5: No such file or directory
cp: testBuildOrg//.git/objects/c6/17d8b785f65eebe0c94332046c75546aeadeeb: No such file or directory
cp: testBuildOrg//.git/objects/c6/1906d892d607b3ca7062a9d4ecf9a1e3aed4fc: No such file or directory
cp: testBuildOrg//.git/objects/c6/1ccf399a5762045afa2bd4f7382718f3bacbee: No such file or directory
cp: testBuildOrg//.git/objects/c6/1cdfc1431af9e4653a81b453a897fa36c48f13: No such file or directory
cp: testBuildOrg//.git/objects/c6/2adac95098c0c953f16b501cca1667a7dbab41: No such file or directory
cp: testBuildOrg//.git/objects/c6/361f302d16e399b3d9b70a62d881a9e8375b00: No such file or directory
cp: testBuildOrg//.git/objects/c6/36bab2f2c727d30aca2d0c2131598c0966c237: No such file or directory
cp: testBuildOrg//.git/objects/c6/36be68c6fa5a15896d7b1955f5c8d3ab18220d: No such file or directory
cp: testBuildOrg//.git/objects/c6/3da8b8e784172324c629b1d7370f7cce95d3a6: No such file or directory
cp: testBuildOrg//.git/objects/c6/43965aa91f0d37b1d586a1c00b487ddd2e8f65: No such file or directory
cp: testBuildOrg//.git/objects/c6/4773f92afa479b182f7a44b26db48eb7949630: No such file or directory
cp: testBuildOrg//.git/objects/c6/4812b46a4483f7f569768a10a79347580a261e: No such file or directory
cp: testBuildOrg//.git/objects/c6/4863969d3e7e8421af9ff9f74b3cbe8aacda78: No such file or directory
cp: testBuildOrg//.git/objects/c6/53784c819219b8a80b770ecc623b3c247982f1: No such file or directory
cp: testBuildOrg//.git/objects/c6/62d330cdcdf85f17a6316f0ba714ab59640a17: No such file or directory
cp: testBuildOrg//.git/objects/c6/67539b5d82e32e633ad141c1a2d128c648e5a6: No such file or directory
cp: testBuildOrg//.git/objects/c6/730306014ca2de0bc7de6a3feab08d0acac526: No such file or directory
cp: testBuildOrg//.git/objects/c6/76940abb9db52bd86a8faed0a6ee10bb0bfd3b: No such file or directory
cp: testBuildOrg//.git/objects/c6/7dbf7ae74f24e489302054e9e90607b79e875e: No such file or directory
cp: testBuildOrg//.git/objects/c6/869ef794c36e1f55391166a946965a18fe42b5: No such file or directory
cp: testBuildOrg//.git/objects/c6/8b021486b1e9db70f65903034ad318f51e87f7: No such file or directory
cp: testBuildOrg//.git/objects/c6/905303257885c09145af5cf2d2533e76caffdc: No such file or directory
cp: testBuildOrg//.git/objects/c6/94a000e9f24b161ca7f77bb15d79eb18ec2f2d: No such file or directory
cp: testBuildOrg//.git/objects/c6/94c6e56529e05029a2d3c0cbf9aa2af84dc741: No such file or directory
cp: testBuildOrg//.git/objects/c6/a43ad0bcbcca298b51c77f8fda23d68bb02135: No such file or directory
cp: testBuildOrg//.git/objects/c6/ab6b9576dced07d0bea59ed5ab361e56dcea2e: No such file or directory
cp: testBuildOrg//.git/objects/c6/b08f18639495be9375a197aabbf246dbae0cac: No such file or directory
cp: testBuildOrg//.git/objects/c6/b9ee994465ece4c3b44d70f1e57dee978aa2ff: No such file or directory
cp: testBuildOrg//.git/objects/c6/bc46387f7b1083d237156369e251857307ae49: No such file or directory
cp: testBuildOrg//.git/objects/c6/c3292262a6dd3467fbd715bfb423493e60a829: No such file or directory
cp: testBuildOrg//.git/objects/c6/c5e7d900a7e62b3dba9ef1e6009ebc60288448: No such file or directory
cp: testBuildOrg//.git/objects/c6/cf894eb9f77a8dc4853fd2c3baf46841ff0b91: No such file or directory
cp: testBuildOrg//.git/objects/c6/dc4bddb37d786fece40029afd71bf25a4a35e0: No such file or directory
cp: testBuildOrg//.git/objects/c6/dcde4c598d6a416d657c296c1cef165d7af8c9: No such file or directory
cp: testBuildOrg//.git/objects/c6/df49199acc7b6a38fe30fb9a736082642f94bb: No such file or directory
cp: testBuildOrg//.git/objects/c6/e9414e0d7352f69db4215dbda3ae6b63a19527: No such file or directory
cp: testBuildOrg//.git/objects/c6/eb4ee94b5fe4d567fae11f5627be3b39392e5b: No such file or directory
cp: testBuildOrg//.git/objects/c6/f7a00b10bb6782303d2a1637fc34f3babb5864: No such file or directory
cp: testBuildOrg//.git/objects/c6/f9a6b727036a2358a47f9f41b5bdb3a983f7c1: No such file or directory
cp: testBuildOrg//.git/objects/d3/9b56691f7d3dfdd96028b870aa4ac030bef440: No such file or directory
cp: testBuildOrg//.git/objects/d3/9db2cd1e3538378b95e500fb91b9d523043874: No such file or directory
cp: testBuildOrg//.git/objects/d3/a2e669a64ca5fea712d7e6d3e8bf4e0ee3b31b: No such file or directory
cp: testBuildOrg//.git/objects/d3/a5bacf99dabd992d7e1887587981f98fe8be87: No such file or directory
cp: testBuildOrg//.git/objects/d3/ab385599034125be25fe56acd6073efdb5d44e: No such file or directory
cp: testBuildOrg//.git/objects/d3/af4e054307c6f5e27468ea0565f36655c2a8bd: No such file or directory
cp: testBuildOrg//.git/objects/d3/b8d6186ce24668c2ea453a7121b078c8644921: No such file or directory
cp: testBuildOrg//.git/objects/d3/c5b5051e2b02662eed7dda6836dce2a5977d7a: No such file or directory
cp: testBuildOrg//.git/objects/d3/cc455e95d42ce4a3463f521a99c914b064719b: No such file or directory
cp: testBuildOrg//.git/objects/d3/dc9dace894d50122cb3c536633a465b01be757: No such file or directory
cp: testBuildOrg//.git/objects/d3/e4a8f5115523a25eab632637efb02e2e5074f8: No such file or directory
cp: testBuildOrg//.git/objects/d3/e82d01ec9cac437547d2443ec399e65ce789c9: No such file or directory
cp: testBuildOrg//.git/objects/d3/ea6cd4efbedfb4e17794b03ca09c3610b350f5: No such file or directory
cp: testBuildOrg//.git/objects/d3/ee6f54e4ca9ed618b4117585cc7c76dfddc391: No such file or directory
cp: testBuildOrg//.git/objects/d3/f25e5321a153ed60f3be5ecd32fa45f946fb21: No such file or directory
cp: testBuildOrg//.git/objects/d3/f8238008d5ba71e6967aaa824834347bf792c5: No such file or directory
cp: testBuildOrg//.git/objects/d3/fab72dc273e1ea5da9eebd85e77af6ef718dc1: No such file or directory
cp: testBuildOrg//.git/objects/d3/fc1ce7f72c3d79712ec058fb96974e2aa43d33: No such file or directory
cp: testBuildOrg//.git/objects/d4/94dde308fbe676517433be5c49c3f25df07b39: No such file or directory
cp: testBuildOrg//.git/objects/d4/95afa8c055c150577d687cdb7bbd06a853a410: No such file or directory
cp: testBuildOrg//.git/objects/d4/9a9c0d5e69c4a93910113c24374937fa03cc39: No such file or directory
cp: testBuildOrg//.git/objects/d4/9b4b7d4628db4ddecccae16e72354bd2f77458: No such file or directory
cp: testBuildOrg//.git/objects/d4/9df7ff15a87c287f04708e3d6835c09da11a57: No such file or directory
cp: testBuildOrg//.git/objects/d4/9fca551b753380632af633f519a1dc6f410e89: No such file or directory
cp: testBuildOrg//.git/objects/d4/a094c70a3531c3f4ccefbbe6df6a1d1e0f51b5: No such file or directory
cp: testBuildOrg//.git/objects/d4/a798b6a73c442f2049a5db3545b982e497770e: No such file or directory
cp: testBuildOrg//.git/objects/d4/ab88c92aabecf1c546fcc08c7235864b19b46d: No such file or directory
cp: testBuildOrg//.git/objects/d4/b645ddb0fdede4fcf075bb92c2a14254f3a99b: No such file or directory
cp: testBuildOrg//.git/objects/d4/c5a5718530764bca83d3f3aea22fea8ec5efc9: No such file or directory
cp: testBuildOrg//.git/objects/d4/cb97447dbd23d423af6a1855f8367a2e347fa5: No such file or directory
cp: testBuildOrg//.git/objects/d4/cce0c773410d80aa3166015226f91de54d2235: No such file or directory
cp: testBuildOrg//.git/objects/d4/cdc9b56e84a89301495cb86d6d347220f0c979: No such file or directory
cp: testBuildOrg//.git/objects/d4/cf9eda8732dc2be6fff338d929354433f9fed8: No such file or directory
cp: testBuildOrg//.git/objects/d4/dc0736653255e35938bd5fcd944cb128be604c: No such file or directory
cp: testBuildOrg//.git/objects/d4/dc3c7cfd073743d2fd9d830cb24bba1ff82799: No such file or directory
cp: testBuildOrg//.git/objects/d4/dccb12dba9385ed7ce42fe874f5a5bd550adc0: No such file or directory
cp: testBuildOrg//.git/objects/d4/e1fc68473123fa040777b72580437a54518ee7: No such file or directory
cp: testBuildOrg//.git/objects/d4/e37ffd24c8f76f1edecf76f8095245a54a41e9: No such file or directory
cp: testBuildOrg//.git/objects/d4/eb264222ce76eb05af13ce973b23a548bb5d28: No such file or directory
cp: testBuildOrg//.git/objects/d4/ec4082b8ff33c675c834df8d375cd9ab3c0085: No such file or directory
cp: testBuildOrg//.git/objects/d4/ee0f60c30a5901e5997a9b05221066a3210c6b: No such file or directory
cp: testBuildOrg//.git/objects/d4/f1961835037abbb03fe811d4950ca5bc2b83c3: No such file or directory
cp: testBuildOrg//.git/objects/d4/f5b037c7ddbcd8829f8fc1379a3416e5a05eb8: No such file or directory
cp: testBuildOrg//.git/objects/d4/f7a53aee90bf608d01fd5c1701f70d4661cafc: No such file or directory
cp: testBuildOrg//.git/objects/d4/fb8d488988c2dff00fa115f781e619b506f77f: No such file or directory
cp: testBuildOrg//.git/objects/d4/fc5c3a6dafd7419974e0f54fa8e0b180478919: No such file or directory
cp: testBuildOrg//.git/objects/d4/ff1d021a047f3e919084df2446287f3914b544: No such file or directory
cp: testBuildOrg//.git/objects/d5/b325635efe8a46e02d33e0d67aa23edd545519: No such file or directory
cp: testBuildOrg//.git/objects/d5/ca498f733217b50cdf62a795eab3311270a7f3: No such file or directory
cp: testBuildOrg//.git/objects/d5/e0b14f63abd5c665a197dda4ce30590eb58fc5: No such file or directory
cp: testBuildOrg//.git/objects/d5/e8e5c25442965ba804e16428e41e154c926304: No such file or directory
cp: testBuildOrg//.git/objects/d5/f248daf71f3567dba1aa41df8017c8f84f7c68: No such file or directory
cp: testBuildOrg//.git/objects/d5/f75693cd46de2fae98e7d24b6833ddc898feb1: No such file or directory
cp: testBuildOrg//.git/objects/d5/f98e09923d32df13c90392c106939b1e222083: No such file or directory
cp: testBuildOrg//.git/objects/d5/fd83c02970a67b758e4aa405f284b3a41f1824: No such file or directory
cp: testBuildOrg//.git/objects/d6/29c7e2f49ecc6fbf9875961df67e10ad77954c: No such file or directory
cp: testBuildOrg//.git/objects/d6/328170e7303b55a777952f84f854792bb9f93e: No such file or directory
cp: testBuildOrg//.git/objects/d6/3405fefec01375cc9e857f8cbc1cb1383825ba: No such file or directory
cp: testBuildOrg//.git/objects/d6/3d89671d2364074b956866fac59c59406baac9: No such file or directory
cp: testBuildOrg//.git/objects/d6/4a56457e4449ba0fd04cbf8b0213c93ac59a4f: No such file or directory
cp: testBuildOrg//.git/objects/d6/4debc7fa98496b84fd6e7e97196fdef5d88089: No such file or directory
cp: testBuildOrg//.git/objects/d6/522e184fef4e6d820064e8b4d27b46fca0f5e3: No such file or directory
cp: testBuildOrg//.git/objects/d6/55ce5d9b3f6c013ca95ca66a5239fd35f42974: No such file or directory
cp: testBuildOrg//.git/objects/d6/55d1c1cf432ea4757f920a86df38d4b0f99132: No such file or directory
cp: testBuildOrg//.git/objects/d6/5b018a8f741cb92ac1f339600c5fc0ab36b903: No such file or directory
cp: testBuildOrg//.git/objects/d6/61f99b1d2c56cb4e520d11ada95c79010069b5: No such file or directory
cp: testBuildOrg//.git/objects/d6/6bbb514153575745913d5ba72cc06676783fa6: No such file or directory
cp: testBuildOrg//.git/objects/d6/6d77df97f9f43b402644fd328c04319150e785: No such file or directory
cp: testBuildOrg//.git/objects/d6/9287b8af7bc57bfc311a7c41693f878919edac: No such file or directory
cp: testBuildOrg//.git/objects/d6/9380cb9efa9588cffd6808cf4f8edc3e87ae6d: No such file or directory
cp: testBuildOrg//.git/objects/d6/a00ded6dc05e23df61f48ea1820067d113aa7b: No such file or directory
cp: testBuildOrg//.git/objects/d6/a403b19151125c6e1324cc12ac10eac89150d3: No such file or directory
cp: testBuildOrg//.git/objects/d6/b4d25c92b8a5221fc4138342418fd3f395b3df: No such file or directory
cp: testBuildOrg//.git/objects/d6/bb2e86f0284da725d180043dbe273bcafac64b: No such file or directory
cp: testBuildOrg//.git/objects/d6/c551ae0ee3887000cb922a4eeb708d757f4495: No such file or directory
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
cp: testBuildOrg//.git/objects/d8/2bf34dfd1aab22dfe01b9f0ec4e6f79e16f0f9: No such file or directory
cp: testBuildOrg//.git/objects/d8/435c7e05319baff175cc2b346183250b3eee30: No such file or directory
cp: testBuildOrg//.git/objects/d8/45dfbb7133f780bdc3323cd1a5cdc4a925fe6e: No such file or directory
cp: testBuildOrg//.git/objects/d8/53bdd2ccf767dec886071ff643a66c54e7325e: No such file or directory
cp: testBuildOrg//.git/objects/d8/549496a18aafcb360b227b57abd310bb57143d: No such file or directory
cp: testBuildOrg//.git/objects/d8/5699ec38302d8e3ff94d771d3cbd98d4c4f5b7: No such file or directory
cp: testBuildOrg//.git/objects/d8/56c79c23b431c4b1612e55e4532d48e57f86a2: No such file or directory
cp: testBuildOrg//.git/objects/d8/5efba7b9a9686bbf98d8108cfe3e74d35e76f1: No such file or directory
cp: testBuildOrg//.git/objects/d8/60751d54f9a6d5ca7e3066e5ccabaac0015eb8: No such file or directory
cp: testBuildOrg//.git/objects/d8/610c63bdde14817961e5237f9588c9dfff5230: No such file or directory
cp: testBuildOrg//.git/objects/d8/702f102ea570fa51c7f146bfa911fc5527c96b: No such file or directory
cp: testBuildOrg//.git/objects/d8/70626ec2731f2b501a2b8c939aa0f7b4b4ec5a: No such file or directory
cp: testBuildOrg//.git/objects/d8/807588af775c2dcd75c87b8ac01218a672ef26: No such file or directory
cp: testBuildOrg//.git/objects/d8/80bacaff7549c17b50d83f9662055f368468a9: No such file or directory
cp: testBuildOrg//.git/objects/d8/865d939b3ebc30494650d529c7b9912654633b: No such file or directory
cp: testBuildOrg//.git/objects/d8/87d2a7a1334d1c43989954d78919e1fe66498c: No such file or directory
cp: testBuildOrg//.git/objects/d8/9834080220d78bf4de757c70156385dd68f5f3: No such file or directory
cp: testBuildOrg//.git/objects/d8/9f914a4a702c7ea6d4c5b4576b35cb1f6d9b0a: No such file or directory
cp: testBuildOrg//.git/objects/d8/cbdc292a23e79b1981d286e907b99d95384b91: No such file or directory
cp: testBuildOrg//.git/objects/d8/d84a56e7df43727748500da26adcc4ab9b643f: No such file or directory
cp: testBuildOrg//.git/objects/d8/dcb62522a3854742827bd25538338c32d424fc: No such file or directory
cp: testBuildOrg//.git/objects/d9/565afb5822012c6e115cf8c9a6f0d7931ecc07: No such file or directory
cp: testBuildOrg//.git/objects/d9/5ca6cd99e14b51347f1f55669e47ed85f98c34: No such file or directory
cp: testBuildOrg//.git/objects/d9/5e1379329b786b854d87ab06c91fe997d90d1c: No such file or directory
cp: testBuildOrg//.git/objects/d9/6908219282f61f86ed3cd8ff5d58010f3816a2: No such file or directory
cp: testBuildOrg//.git/objects/d9/713b0b94c4188e732cb2911429df6fe881f5de: No such file or directory
cp: testBuildOrg//.git/objects/d9/74a5ee4aafdef4bd0e49c00839a9ea0cae6da7: No such file or directory
cp: testBuildOrg//.git/objects/d9/78993c6b0eeb5fba833fb795241f1c6a713824: No such file or directory
cp: testBuildOrg//.git/objects/d9/8c1bfbb2cab94280c0d8eb17267898cb68a039: No such file or directory
cp: testBuildOrg//.git/objects/d9/8ebf929e74b35e1644af3b048cd05a52b126b9: No such file or directory
cp: testBuildOrg//.git/objects/d9/91742e6dcccf7414022fd7604b7b4f0624a441: No such file or directory
cp: testBuildOrg//.git/objects/d9/a242614f0ce83b2ffd99329a2a634847773f1f: No such file or directory
cp: testBuildOrg//.git/objects/d9/a7a0289f87e874efe071473ea3c1f5e7b4d7a6: No such file or directory
cp: testBuildOrg//.git/objects/d9/a9ea6a64baf1dc68d32905ddec15e480fd1969: No such file or directory
cp: testBuildOrg//.git/objects/d9/af8fab9f8ff26726d2c72c46a755dc79981cd7: No such file or directory
cp: testBuildOrg//.git/objects/d9/b2f924de3a7e3a097fb0bae3a68f7bdbefdda3: No such file or directory
cp: testBuildOrg//.git/objects/d9/ba61ec66d2042c79c17a52feb8cc453fb29db0: No such file or directory
cp: testBuildOrg//.git/objects/d9/bc174da82306a04296600618a1c2713d68c97a: No such file or directory
cp: testBuildOrg//.git/objects/d9/c0fd98edc2b4bbe28a60d029143b258609f0ff: No such file or directory
cp: testBuildOrg//.git/objects/d9/c47a307b895c81c74c8efac7b57ad20dc5b7c1: No such file or directory
cp: testBuildOrg//.git/objects/d9/da9facaa214982276e4e8ea279b43c8fcd45f6: No such file or directory
cp: testBuildOrg//.git/objects/d9/e3cb5ca09052fafb9aa3439e38ab39c35cddb7: No such file or directory
cp: testBuildOrg//.git/objects/d9/e8089a3e758b71c6207691cbb8033a6b81740d: No such file or directory
cp: testBuildOrg//.git/objects/d9/e9c6925b1ab471202fe786fa4b7dadf3f38d22: No such file or directory
cp: testBuildOrg//.git/objects/d9/f0c2d1d2a36a7cfe291cfafd76732ef751343a: No such file or directory
cp: testBuildOrg//.git/objects/d9/fcfd4cd9efd7470d78a2d1d9df21e77c888c35: No such file or directory
cp: testBuildOrg//.git/objects/da/0ca6662665977c3182ed9b01fee40b1001cb4e: No such file or directory
cp: testBuildOrg//.git/objects/da/11a658f29d035d7d01a2a464a420f87bc86d52: No such file or directory
cp: testBuildOrg//.git/objects/da/13cead0cd00946f9c293250535370b2d587f8f: No such file or directory
cp: testBuildOrg//.git/objects/da/1550eff58628fe90da6faa214c03cc1f02b5bd: No such file or directory
cp: testBuildOrg//.git/objects/da/15660e02a666f0548833d76f9542d4ee42f016: No such file or directory
cp: testBuildOrg//.git/objects/da/1ad14a703907c9a934dd1d39099024b9cbccc0: No such file or directory
cp: testBuildOrg//.git/objects/da/20ab9487295efdf3767570019cc3ca7d424c78: No such file or directory
cp: testBuildOrg//.git/objects/da/2d2e24e20bd3892fb7bfad8fa6c620832aa0f4: No such file or directory
cp: testBuildOrg//.git/objects/da/2f398f240826178ad6af43da5631e2c0b15cc5: No such file or directory
cp: testBuildOrg//.git/objects/da/31180bce78e047d513757e817fd18fb28329b8: No such file or directory
cp: testBuildOrg//.git/objects/da/35147b6e96fda8847efd4a7bc797e28eaea92d: No such file or directory
cp: testBuildOrg//.git/objects/da/36bd138501ccbae279a537425fc7bd2975ec90: No such file or directory
cp: testBuildOrg//.git/objects/da/397594c6d2c188988e567aa0017fd2a8f3a290: No such file or directory
cp: testBuildOrg//.git/objects/da/3dfe2ced4aca1fda7ace26038ef3a6fd9b677d: No such file or directory
cp: testBuildOrg//.git/objects/da/4292227096c1fc7a60086bae03fc9876827a3b: No such file or directory
cp: testBuildOrg//.git/objects/da/464680fca1d469473c7b399d16c8ac11e45649: No such file or directory
cp: testBuildOrg//.git/objects/da/4b306d8fba99b58ab10872c44b683794696e7b: No such file or directory
cp: testBuildOrg//.git/objects/da/51a8409d2e3fb22e7a893b044fc0d504b4c4b7: No such file or directory
cp: testBuildOrg//.git/objects/da/5901fb4e12750f06aac80a708ae8073d662c1c: No such file or directory
cp: testBuildOrg//.git/objects/da/5b66a62470e510b14bf841e70b4dba8086bacb: No such file or directory
cp: testBuildOrg//.git/objects/da/5c4139e7c7b6c6a1de664de194704615feee78: No such file or directory
cp: testBuildOrg//.git/objects/da/5e5c0e2464561be49a8fe89c04bf5988b2e109: No such file or directory
cp: testBuildOrg//.git/objects/da/5fa6f80f4ba0d47345d5b428483fe36c57ccc2: No such file or directory
cp: testBuildOrg//.git/objects/da/705e01cad9d501f0ecf5f162e28a6bd11d9a1d: No such file or directory
cp: testBuildOrg//.git/objects/da/7d8125e24833f23d1c14f2c8ae055da9f8589d: No such file or directory
cp: testBuildOrg//.git/objects/da/8bde4d913e73b80ce7800a281b3c4cdac5cc07: No such file or directory
cp: testBuildOrg//.git/objects/da/928ee721c8395cf5bd8ff51c97ee3c04991555: No such file or directory
cp: testBuildOrg//.git/objects/da/95e86ad52dcead5b0f6a36de8a3ce30cb63500: No such file or directory
cp: testBuildOrg//.git/objects/da/967d722e0a21717bd27d12c7d0330cf6853819: No such file or directory
cp: testBuildOrg//.git/objects/da/9a3db5e12dc0b1687588fe5862216bf190fb2e: No such file or directory
cp: testBuildOrg//.git/objects/da/a3dc7c90dfcb1ad3b43c8835a7b310a7195cd4: No such file or directory
cp: testBuildOrg//.git/objects/da/aa6df6f85a1e52b28b35d468d4ebb834152d22: No such file or directory
cp: testBuildOrg//.git/objects/da/b827d2fa6d67add3e23053d399733878aa6d87: No such file or directory
cp: testBuildOrg//.git/objects/da/bc443fc95be32868ef6e75bdfd8c31b9e3360e: No such file or directory
cp: testBuildOrg//.git/objects/da/bd1431ea6a8d966afab48e320e31f090756217: No such file or directory
cp: testBuildOrg//.git/objects/da/bf17635382ce102555ab873c8476e3b7d62144: No such file or directory
cp: testBuildOrg//.git/objects/da/c64a60beb28563ed014d897d19f722d0d43fff: No such file or directory
cp: testBuildOrg//.git/objects/da/c956d156282bac83860b6b704ca35d2582fcf1: No such file or directory
cp: testBuildOrg//.git/objects/da/cf8b2a39afdd3146387f6c0259134279ae3a02: No such file or directory
cp: testBuildOrg//.git/objects/da/d2588dfc50b6e6f0b7b66687c4be6832505bd5: No such file or directory
cp: testBuildOrg//.git/objects/da/d2d1abfdbf4f6190337d19ea54f4423e534b5d: No such file or directory
cp: testBuildOrg//.git/objects/da/d8e777c31db941c3d3e9767b0f28817019058d: No such file or directory
cp: testBuildOrg//.git/objects/da/d90add640a1ee0cd6c79cff12a2091e901a90e: No such file or directory
cp: testBuildOrg//.git/objects/da/ddc4543b79f3ee5c9dcf459c2a883e8d4cb5fe: No such file or directory
cp: testBuildOrg//.git/objects/da/e3d12569c7c10fad9c47480b971ef2dd9759a4: No such file or directory
cp: testBuildOrg//.git/objects/da/e61b151ae56cdd953314b54503c472e9c97fb4: No such file or directory
cp: testBuildOrg//.git/objects/da/ed2f69a41170854691c3cece0ce6bec6886de0: No such file or directory
cp: testBuildOrg//.git/objects/da/f004ae9c04172299a9e2d3c935ab462d14f531: No such file or directory
cp: testBuildOrg//.git/objects/da/fc02cfc0df5321a99ac2d96477e2b910b2a8c8: No such file or directory
cp: testBuildOrg//.git/objects/db/2972d254b8578aad64e9a344374cf7752b6298: No such file or directory
cp: testBuildOrg//.git/objects/db/3a0b19ae8405f7c47fea63c81c1b4740862ef4: No such file or directory
cp: testBuildOrg//.git/objects/db/3b6c26020b7885fd4827c5aa489238264af79d: No such file or directory
cp: testBuildOrg//.git/objects/db/4595a1671ef7b317004387e638d5c274a4249f: No such file or directory
cp: testBuildOrg//.git/objects/db/487d4c2138385cb7955a5d42dc7e8419771d82: No such file or directory
cp: testBuildOrg//.git/objects/db/4d59f637061467c3d4ef33814d1c5f721f98c1: No such file or directory
cp: testBuildOrg//.git/objects/db/4ef9eeb49f28ded00ec35f103b7ba65b155136: No such file or directory
cp: testBuildOrg//.git/objects/db/54f3309759570f321770079ad75c116363d8f7: No such file or directory
cp: testBuildOrg//.git/objects/db/58256bc93a8fa03f7ef337d342d39e6e2ef930: No such file or directory
cp: testBuildOrg//.git/objects/db/5e95528143a41b805469c8271ad95fa2ff98bb: No such file or directory
cp: testBuildOrg//.git/objects/db/5e9b54d7851be9e1656c9f5c27305d4318a96c: No such file or directory
cp: testBuildOrg//.git/objects/db/63bb47979c565df3c526cca2922b0280784a40: No such file or directory
cp: testBuildOrg//.git/objects/db/6a1787faee977579e2b5623d0bcc7d739ab08d: No such file or directory
cp: testBuildOrg//.git/objects/db/705277a40576ba274eb271c5b9f83cf617e875: No such file or directory
cp: testBuildOrg//.git/objects/db/77e456c1993a9a087fea1e5fe249aba61b0e05: No such file or directory
cp: testBuildOrg//.git/objects/db/78ea6ceaee39664eb05ddd76a3993e0ca01b3b: No such file or directory
cp: testBuildOrg//.git/objects/db/7983afe09262c958425b01c3ceca4b1e4a709b: No such file or directory
cp: testBuildOrg//.git/objects/db/7d2b0d7e9342c1ff09d304f9b6d5d6d9d89da4: No such file or directory
cp: testBuildOrg//.git/objects/db/880429025dadd1f937255d25aad7101604bd1e: No such file or directory
cp: testBuildOrg//.git/objects/db/96a3de5f06f9b0d4cf1c1cf2f0942cde0e3856: No such file or directory
cp: testBuildOrg//.git/objects/db/993c0e5385b1d0b7e4bfe05981cf8677a51bb3: No such file or directory
cp: testBuildOrg//.git/objects/db/9a2b34f3951b4adc5940d3afad4eacee056375: No such file or directory
cp: testBuildOrg//.git/objects/db/a5cce727a529793fdbb103d25550b6bfc3973d: No such file or directory
cp: testBuildOrg//.git/objects/db/b75a76dbfb2e9cfb065996af3e614873a9de4e: No such file or directory
cp: testBuildOrg//.git/objects/db/bd5a8122c60bdbc05bed14d63ae734a6d456f5: No such file or directory
cp: testBuildOrg//.git/objects/db/c0f23d14f24f7b6cb4503dadac4c2b7a941736: No such file or directory
cp: testBuildOrg//.git/objects/db/cc44d5a899fed161bc54960b76b8e3be4326d9: No such file or directory
cp: testBuildOrg//.git/objects/db/d6e4879f893975a78d77c904b55e5065da0326: No such file or directory
cp: testBuildOrg//.git/objects/db/d76473a55944651c04ce1ebf74862db209f93c: No such file or directory
cp: testBuildOrg//.git/objects/db/da3c231347b5e7e4f03591e16ac0fa589a35cb: No such file or directory
cp: testBuildOrg//.git/objects/db/dc33057fe324eb590a2bc2f84e1add72fbf1a6: No such file or directory
cp: testBuildOrg//.git/objects/db/de953ccf85b9512e6476716a01d25000d1ef69: No such file or directory
cp: testBuildOrg//.git/objects/db/e4205979ede0b2a67e5301ba382543c0ad75b5: No such file or directory
cp: testBuildOrg//.git/objects/db/e49705397bf30a25f85c9c2f85af25a16f3f21: No such file or directory
cp: testBuildOrg//.git/objects/db/f0543cb4b52c6ef362bde4f2a28486a332b5f1: No such file or directory
cp: testBuildOrg//.git/objects/db/f8a2a8b611c1d0481d12f2b7882dcb8c5e37f7: No such file or directory
cp: testBuildOrg//.git/objects/db/f9ecef590a6aa6e3abb2e38a340b5f5f276e2f: No such file or directory
cp: testBuildOrg//.git/objects/db/fc29feba98abef599d2f146558140279b86db7: No such file or directory
cp: testBuildOrg//.git/objects/db/fc84e27438d1fdba4c7066ed5f662520e66451: No such file or directory
cp: testBuildOrg//.git/objects/db/fdde9d05c4142cdc6b7212dd0ea7fb02bf5ac9: No such file or directory
cp: testBuildOrg//.git/objects/dc/1e9cf1a65d11d994ba763225bead35ece6a2b6: No such file or directory
cp: testBuildOrg//.git/objects/dc/276751d544073f8f7c3381659cf2b18f991cf4: No such file or directory
cp: testBuildOrg//.git/objects/dc/28ffa9c75a00d8f2393775ca5761b1474f5fdf: No such file or directory
cp: testBuildOrg//.git/objects/dc/32d9ff7e682416aee60eff242c133ee5955f2f: No such file or directory
cp: testBuildOrg//.git/objects/dc/40973b52dd67220fbc87ad5b75c14c3bc382e4: No such file or directory
cp: testBuildOrg//.git/objects/dc/41c998cab8605a30f6a2ee1a30b81f25c8a3ad: No such file or directory
cp: testBuildOrg//.git/objects/dc/466a1910493405bd1f5199a1d829badfac0972: No such file or directory
cp: testBuildOrg//.git/objects/dc/5753c7264f40bd098b023513a8514a3cd41d82: No such file or directory
cp: testBuildOrg//.git/objects/dc/5c1577ad4e26182af437ae3860bd6d104a8bac: No such file or directory
cp: testBuildOrg//.git/objects/dc/5d449ad0be1211f8b16e224c1b76e884caf2cf: No such file or directory
cp: testBuildOrg//.git/objects/dc/5dfe5604b7553824b07b26bd524a8d545b3fa1: No such file or directory
cp: testBuildOrg//.git/objects/dc/60ee81e9d836c5b74c2b1498deb025544c9d79: No such file or directory
cp: testBuildOrg//.git/objects/dc/650e80583a7806304fe62ec3e9f2b821ac08ec: No such file or directory
cp: testBuildOrg//.git/objects/dc/6bdd3de11c43e039424bb59867723cf480f5de: No such file or directory
cp: testBuildOrg//.git/objects/dc/6dd83fbaf989514ad5309d80e7a5534e850783: No such file or directory
cp: testBuildOrg//.git/objects/dc/6f5113bd959769a51a2bf70034affbd3c5f9b4: No such file or directory
cp: testBuildOrg//.git/objects/dc/767481291db1cc078ec1fd99043260fc978dd1: No such file or directory
cp: testBuildOrg//.git/objects/dc/7f8ed3b287dc4f0f83d405929e4d3f9c861366: No such file or directory
cp: testBuildOrg//.git/objects/dc/87dab69db8e32d8dcfa8bc33d387ff603b0916: No such file or directory
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
cp: testBuildOrg//.git/objects/dc/cdeed448e2de77e1565fddf21eeb6718997314: No such file or directory
cp: testBuildOrg//.git/objects/dc/ce35e5980e7e5c7dbc724d103036dcc0fc173b: No such file or directory
cp: testBuildOrg//.git/objects/dc/cebd765a2458f594f8d4dca79ef45dc921b2c8: No such file or directory
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
cp: testBuildOrg//.git/objects/e6/f3e7f1ae6ef07093601a8db569fe539b2bfe53: No such file or directory
cp: testBuildOrg//.git/objects/e6/f5c3bb1b488e9d1693669cfe7236ff9a71edfb: No such file or directory
cp: testBuildOrg//.git/objects/e6/fc3fe46627a556dd4af03ceaf228cbfc897656: No such file or directory
cp: testBuildOrg//.git/objects/e7/55149fc30ebe4fe6427f050e31d44a3e706fcd: No such file or directory
cp: testBuildOrg//.git/objects/e7/68c36f31c71857235890ab13284b9e84da110a: No such file or directory
cp: testBuildOrg//.git/objects/e7/70cf534df05d2ca2a07d828bb672fc501cf4a1: No such file or directory
cp: testBuildOrg//.git/objects/e7/7e79b78cee1d5bf88803378942d3d392bf9707: No such file or directory
cp: testBuildOrg//.git/objects/e7/7f590d6a29418eacfc0bb3334381fbe293ab7d: No such file or directory
cp: testBuildOrg//.git/objects/e7/7feb90483b37a046bc9776037efd735bba4667: No such file or directory
cp: testBuildOrg//.git/objects/e7/827ed0f8c280c04423ef61f0959263c8ee351d: No such file or directory
cp: testBuildOrg//.git/objects/e7/8449732103171680e4d3a88cea122628905c3c: No such file or directory
cp: testBuildOrg//.git/objects/e7/851c77d5b24d3dfca7154eb9ecf8050d0287fc: No such file or directory
cp: testBuildOrg//.git/objects/e7/8531a7dbd05ab8cea0b5efd7c3c2e4534bda35: No such file or directory
cp: testBuildOrg//.git/objects/e7/887af3bc62eb3427099af8e88cf81f5d0f946a: No such file or directory
cp: testBuildOrg//.git/objects/e7/94d2c74aace0eb8f092b4ea22e9a3af0091d2d: No such file or directory
cp: testBuildOrg//.git/objects/e7/976687c8762538eb470608896b5a86d9620733: No such file or directory
cp: testBuildOrg//.git/objects/e7/9c63f6a2d6f0c23551b03f1ecdaf77c8c515df: No such file or directory
cp: testBuildOrg//.git/objects/e7/a39429928c356a6a1e682def02c196b9e5ac6b: No such file or directory
cp: testBuildOrg//.git/objects/e7/ac70748599202f2c6410567e524ac2cd2bc3cc: No such file or directory
cp: testBuildOrg//.git/objects/e7/ad4e9067beb24f99054e5601ae7d26f66e7e4c: No such file or directory
cp: testBuildOrg//.git/objects/e7/c7035793dc0b5ac4aca72564321cf16927f98b: No such file or directory
cp: testBuildOrg//.git/objects/e7/cbba2da5be2dd2daa207fce2414582049eb181: No such file or directory
cp: testBuildOrg//.git/objects/e7/cbcf4d664d76766b1a95c80ce6ec342fd71ba7: No such file or directory
cp: testBuildOrg//.git/objects/e7/d2ee98e7118fa55b0af4ac7c84dbc53c2f3429: No such file or directory
cp: testBuildOrg//.git/objects/e7/da16f10f61082504deff88a44ecf9a88be2d71: No such file or directory
cp: testBuildOrg//.git/objects/e7/dac66113de4d31c2e87fb7221656ac4fcc270d: No such file or directory
cp: testBuildOrg//.git/objects/e7/ddc82d5a2d6ba5f6de92238cb33af115f65be6: No such file or directory
cp: testBuildOrg//.git/objects/e7/e025821330fdc4dae4d0b1279211cc334ca0d2: No such file or directory
cp: testBuildOrg//.git/objects/e7/e4b31419ae5104e6b76d51fce7d36af3732e89: No such file or directory
cp: testBuildOrg//.git/objects/e7/ec47610023418495dc4a45af027f35b82a867d: No such file or directory
cp: testBuildOrg//.git/objects/e7/f12209897ce3ef5bdf2d99d711383e1b1c20a5: No such file or directory
cp: testBuildOrg//.git/objects/e7/f2087a3ce6b52c54b98a624c70fdac0e41f836: No such file or directory
cp: testBuildOrg//.git/objects/e7/f5ec9a0b1a97ead60a1e752dc19a284e1e8eac: No such file or directory
cp: testBuildOrg//.git/objects/e7/f82f51df0e39f29f05910675ec83165629420a: No such file or directory
cp: testBuildOrg//.git/objects/e7/f9a3d7c09d8c34404a37900d9cc66b07e37f86: No such file or directory
cp: testBuildOrg//.git/objects/e8/40bd5b3eabeea9fedb00de4d808245306c19d0: No such file or directory
cp: testBuildOrg//.git/objects/e8/40c08a0e8dcd252f634fbb49a8f3f51fa4e460: No such file or directory
cp: testBuildOrg//.git/objects/e8/52424495615734a30f9f392fa8785453975f42: No such file or directory
cp: testBuildOrg//.git/objects/e8/55954f265e203b4cb0b9b35684a8bb0713f65e: No such file or directory
cp: testBuildOrg//.git/objects/e8/5a29ff540d890e87b5d2fde805c35d8d51f39a: No such file or directory
cp: testBuildOrg//.git/objects/e8/5d8ffd8f593b7a92e2f83a03822ad431f028a6: No such file or directory
cp: testBuildOrg//.git/objects/e8/61f467ae34b23b51defda74cbe10a09afa7ea7: No such file or directory
cp: testBuildOrg//.git/objects/e8/628d8c8eb1a7e10bdbc58e2d85a9060c8e4392: No such file or directory
cp: testBuildOrg//.git/objects/e8/6945b29d7c2012b81293d40c01914c5180561d: No such file or directory
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
cp: testBuildOrg//.git/objects/eb/ccdad8a787693fe5e272160d8aad853a3acf2b: No such file or directory
cp: testBuildOrg//.git/objects/eb/cceaad83400c62f830a0d6ca19641cb26df176: No such file or directory
cp: testBuildOrg//.git/objects/eb/d1fc8fbe6656a13ee7f86ac51c2826228deb65: No such file or directory
cp: testBuildOrg//.git/objects/eb/d2d0cb22a4670a2c34fa990bfefa6ad4f8dea2: No such file or directory
cp: testBuildOrg//.git/objects/eb/e23a83d010af89d58fca6883791ef131065bdf: No such file or directory
cp: testBuildOrg//.git/objects/eb/f83383da5cad23614854a196622ccb20e6e866: No such file or directory
cp: testBuildOrg//.git/objects/eb/fa37ec52e457482fe740cdf8ef2c6a58b7ea2f: No such file or directory
cp: testBuildOrg//.git/objects/ec/6dd40bd1cb68bf3263431b78e2deb56f6c3dff: No such file or directory
cp: testBuildOrg//.git/objects/ec/711b89d6a8bec94a4b3c8492c5f70d3f39c317: No such file or directory
cp: testBuildOrg//.git/objects/ec/7c4335215f78f6fa2aeb1e2f6cb32ab139fb08: No such file or directory
cp: testBuildOrg//.git/objects/ec/85a0fe8a407d82853fdecac16c621de9f7ac38: No such file or directory
cp: testBuildOrg//.git/objects/ec/881029a569be5119e4b7f4ec123bb60cbbb087: No such file or directory
cp: testBuildOrg//.git/objects/ec/96559bf0a0ce761a916119892f67e6f2316674: No such file or directory
cp: testBuildOrg//.git/objects/ec/96726677f8623fcfb16bd4f56174d785caa852: No such file or directory
cp: testBuildOrg//.git/objects/ec/9a1bcfdc056ae711e970d6889b26821126eb1a: No such file or directory
cp: testBuildOrg//.git/objects/ec/9cdb198558a09eb59c00145bbb5845ba2ff4b4: No such file or directory
cp: testBuildOrg//.git/objects/ec/a0f5d3fe92df0ab0d821dc078afddc41c01085: No such file or directory
cp: testBuildOrg//.git/objects/ec/a6a3dd63f0afe9900073b78eac13fc8129faf7: No such file or directory
cp: testBuildOrg//.git/objects/ec/ab7e797e0581d1cc3c9dcdc6dc5cce6e5a363e: No such file or directory
cp: testBuildOrg//.git/objects/ec/abc6e36218d21f6a6489fb7c2975c753d257d8: No such file or directory
cp: testBuildOrg//.git/objects/ec/add4622ccf37ecf42828e63ba0724d992bfd67: No such file or directory
cp: testBuildOrg//.git/objects/ec/aeebfb96b45640953707f90afd7053afd16876: No such file or directory
cp: testBuildOrg//.git/objects/ec/b0a6c95e42fdeacce06fe5de762e6b73cf1f04: No such file or directory
cp: testBuildOrg//.git/objects/ec/b70559119858cb0c77c825307131ae106463e0: No such file or directory
cp: testBuildOrg//.git/objects/ec/c02ba818a50918ad50daf510a2267c7717692c: No such file or directory
cp: testBuildOrg//.git/objects/ec/c172f8accbd987a44ba7bd20653a7a5bf01243: No such file or directory
cp: testBuildOrg//.git/objects/ec/c292989308704d72a518182f8a884eb364ca1c: No such file or directory
cp: testBuildOrg//.git/objects/ec/ca6427c79821abe44d53277c60d501c37c0f6e: No such file or directory
cp: testBuildOrg//.git/objects/ec/d24ecc8b13397522d8bdedcd9604f761390562: No such file or directory
cp: testBuildOrg//.git/objects/ec/d2a50c41695a0cf51c1af9548288ddcf57236e: No such file or directory
cp: testBuildOrg//.git/objects/ec/e7d21a9d7a89e13084632eca1a16c47faf1901: No such file or directory
cp: testBuildOrg//.git/objects/ec/ef3767fb0c0f37f84e59277b74dc566083297c: No such file or directory
cp: testBuildOrg//.git/objects/ec/f0efe1969a23d2bc8bbf12f050808f28d6cbac: No such file or directory
cp: testBuildOrg//.git/objects/ec/fcff2da29aefab6833ca4145d3d5633511eab2: No such file or directory
cp: testBuildOrg//.git/objects/ec/fe20b9d80550038d1840d18bd900b1491d3994: No such file or directory
cp: testBuildOrg//.git/objects/ed/f7056a5093e7daae2fb8a5edf6d2276ef8354a: No such file or directory
cp: testBuildOrg//.git/objects/ed/fd02d385f599cba5015bd69c83bd08c7a9f86a: No such file or directory
cp: testBuildOrg//.git/objects/ed/fde8d764416569384e1ed57ac38e0c99c9a6af: No such file or directory
cp: testBuildOrg//.git/objects/ee/3d83f211d0c23900dda2d2bd0959113767ed85: No such file or directory
cp: testBuildOrg//.git/objects/ee/3e1ff2f2da382134fd5b9caf204fcd3638bfc0: No such file or directory
cp: testBuildOrg//.git/objects/ee/cc7bf6dba1dfe3c3cebca67afebe7ef31da0ee: No such file or directory
cp: testBuildOrg//.git/objects/ee/d202a70f2735184c61d4833c86db128adcd692: No such file or directory
cp: testBuildOrg//.git/objects/ee/d489d883ff27e0f197c8c9874e823e70457d20: No such file or directory
cp: testBuildOrg//.git/objects/ee/d9bf4e90a56680ea2e6515807c18fb159a01ae: No such file or directory
cp: testBuildOrg//.git/objects/ee/e2f55fbd017016faa5c10caed28534f522b798: No such file or directory
cp: testBuildOrg//.git/objects/ee/e3e379d73d47c6a54ffe3c031ddcc5733f9cdb: No such file or directory
cp: testBuildOrg//.git/objects/ee/e442fe337d962230fa442befac627905f7f1ae: No such file or directory
cp: testBuildOrg//.git/objects/ee/e947613402db996904d5f97ff15dab1186257f: No such file or directory
cp: testBuildOrg//.git/objects/ee/ecc562d2703fef2177778da61b36f9c6e53b3d: No such file or directory
cp: testBuildOrg//.git/objects/ee/eebf9c8a1fa2bf38c8c4a00f0cf85fc1da69bf: No such file or directory
cp: testBuildOrg//.git/objects/ee/f5698fd6b8160c3c73e8d13f8639f2456fb5d0: No such file or directory
cp: testBuildOrg//.git/objects/ee/f6357daa22deda4e2da7e41e9d36d61e380e2a: No such file or directory
cp: testBuildOrg//.git/objects/ee/f7ba6b83e480c496bfd0f99f7d8c1813dd6526: No such file or directory
cp: testBuildOrg//.git/objects/ee/fc425b829f8d83d5cb28c0127fa3afc1c0762c: No such file or directory
cp: testBuildOrg//.git/objects/ef/181391a39281f85860f50a0a3f16b211e06181: No such file or directory
cp: testBuildOrg//.git/objects/ef/2028f0e98fb93a0edcd83a1c7fee030788a8de: No such file or directory
cp: testBuildOrg//.git/objects/ef/25e7bbeabb78dfe15c84712dfb6e476998415f: No such file or directory
cp: testBuildOrg//.git/objects/ef/317fc2d800988ba1aad688683228982aed3300: No such file or directory
cp: testBuildOrg//.git/objects/ef/367727f57d42d193c7a8b27ce69b002e3094c1: No such file or directory
cp: testBuildOrg//.git/objects/ef/376cab69783c8588a09fefc135d1f4c3ec9822: No such file or directory
cp: testBuildOrg//.git/objects/ef/4b5cc3c9898966a9ca4cff21161211cbbb033f: No such file or directory
cp: testBuildOrg//.git/objects/ef/4c0440931f0cf5c2dcc20cb8b0f13172f95049: No such file or directory
cp: testBuildOrg//.git/objects/ef/585f95fea83ae938a7e8a80f7d0d16471ce328: No such file or directory
cp: testBuildOrg//.git/objects/ef/5a87546adbf4c9847b8363160a2f770a185d32: No such file or directory
cp: testBuildOrg//.git/objects/ef/5d5927d423581b53a4d238a4fcd80e627a9bdf: No such file or directory
cp: testBuildOrg//.git/objects/ef/5e07d7bbf79d06717b55f7d10b9c47fc0118fc: No such file or directory
cp: testBuildOrg//.git/objects/ef/6c11086078f8a30fa8fc82343f73c5e0f19b84: No such file or directory
cp: testBuildOrg//.git/objects/ef/6ce6b7405dbd0d124b51d0c7ff170487c4d69a: No such file or directory
cp: testBuildOrg//.git/objects/ef/7e01b63db7521236adb994f4af79d253aaeb21: No such file or directory
cp: testBuildOrg//.git/objects/ef/84b907870533469b527bc29d719b59daa499f7: No such file or directory
cp: testBuildOrg//.git/objects/ef/86cdf9eb1478614f0c52fefe33618438c4a51c: No such file or directory
cp: testBuildOrg//.git/objects/ef/86ce118a3d92aeafb6b88c523284610a956f08: No such file or directory
cp: testBuildOrg//.git/objects/ef/9d3028f803cc03166a74d3c0dd8f6802f6e1cf: No such file or directory
cp: testBuildOrg//.git/objects/ef/9f1b546d15087cf6215735ce9e385742322031: No such file or directory
cp: testBuildOrg//.git/objects/ef/a363933c63a6c25b7c50d190c34e8ddb347106: No such file or directory
cp: testBuildOrg//.git/objects/ef/a943f6e327dc6d4a635251b5dbc810987d9da6: No such file or directory
cp: testBuildOrg//.git/objects/ef/a97a0e6bd84a2292d4b502fb0232cd6d403ab6: No such file or directory
cp: testBuildOrg//.git/objects/ef/aeb79882188ac0b8b1b0779830da3b332cc476: No such file or directory
cp: testBuildOrg//.git/objects/ef/b53dc76bae70d6088235ddf44749273bfa1c3b: No such file or directory
cp: testBuildOrg//.git/objects/ef/b57c159a84808487eebcb8b7c13d09f197ff62: No such file or directory
cp: testBuildOrg//.git/objects/ef/d00e994553154b5203beaba0ba77795af68fc6: No such file or directory
cp: testBuildOrg//.git/objects/ef/d74e01608eb6f8467b9fbc7d1ddcdd12fc414b: No such file or directory
cp: testBuildOrg//.git/objects/ef/e3d97f01ad33749a29a13ae40f7fe5e27ccc35: No such file or directory
cp: testBuildOrg//.git/objects/ef/e9f818c2e872f552a76b7a012059353b32a7bc: No such file or directory
cp: testBuildOrg//.git/objects/ef/eb2bc5008b3cda814f52e6ccbb602438c43d95: No such file or directory
cp: testBuildOrg//.git/objects/ef/f301f60c0171fe39974ea615d020795789cb7f: No such file or directory
cp: testBuildOrg//.git/objects/f0/337cfb8f436375b87a5c507ecb80714f7f0b62: No such file or directory
cp: testBuildOrg//.git/objects/f0/38950613d6686bebb596b8312d5bb156914084: No such file or directory
cp: testBuildOrg//.git/objects/f0/4538c7b0eb93cb9dfc4180944c0865cb35e1aa: No such file or directory
cp: testBuildOrg//.git/objects/f0/49b2a6522e0c5951afb1ffe4cc6cc3b774fb1d: No such file or directory
cp: testBuildOrg//.git/objects/f0/540aea31fd2c9af6b5a4af5cd623d9d49fd7f6: No such file or directory
cp: testBuildOrg//.git/objects/f0/5f2384290d6cc9a705de909c37c220563caff8: No such file or directory
cp: testBuildOrg//.git/objects/f0/603635496d836370bcd264dcd85d802f333561: No such file or directory
cp: testBuildOrg//.git/objects/f0/6b65e154b1f85ff8336010f7bc070f45786665: No such file or directory
cp: testBuildOrg//.git/objects/f0/71f04a0882852ad6281c24970248c5ebb50172: No such file or directory
cp: testBuildOrg//.git/objects/f0/8e18774e95195cfd62b8014c332bc528679f9e: No such file or directory
cp: testBuildOrg//.git/objects/f0/9082b6c4057489f576aa6a76bd7d8749d39ff7: No such file or directory
cp: testBuildOrg//.git/objects/f0/90ed83dc4ae928269d58c89180ab819aa7c3d5: No such file or directory
cp: testBuildOrg//.git/objects/f0/a0fb8c99fc171ac3fefca55771ebdcd543af42: No such file or directory
cp: testBuildOrg//.git/objects/f0/a5bc26e6c59be8fd225c49c67b2faed46a790b: No such file or directory
cp: testBuildOrg//.git/objects/f0/ac1a845b63280d5f080949be7ab646c5c6253b: No such file or directory
cp: testBuildOrg//.git/objects/f0/af70021ee2b5e98bc90b9e741cf7259579af1a: No such file or directory
cp: testBuildOrg//.git/objects/f0/b07ac2146de4ab26df6cb5e7aa07e782fb1643: No such file or directory
cp: testBuildOrg//.git/objects/f0/bff81200feaeec3c4a95b97cbe66ca2cc3f821: No such file or directory
cp: testBuildOrg//.git/objects/f0/c00e2c2b29e966e4bbc8365f72fbaf16194943: No such file or directory
cp: testBuildOrg//.git/objects/f0/cb55f9fb8dc3b6af9caed33416b7bd3bc3936e: No such file or directory
cp: testBuildOrg//.git/objects/f0/d5e108b260dd103560c06cef1dde3bc0569742: No such file or directory
cp: testBuildOrg//.git/objects/f0/d6a2f5345e0372f70acc304a16918c9077d1bd: No such file or directory
cp: testBuildOrg//.git/objects/f0/e2ea38a6877f99f272cb8019ecc299a7dade2a: No such file or directory
cp: testBuildOrg//.git/objects/f0/f425de81f18b5f9ed822e02321c68f5ec81af0: No such file or directory
cp: testBuildOrg//.git/objects/f0/f681d8488b10b6189eaac5dc2f4445c2bca9ea: No such file or directory
cp: testBuildOrg//.git/objects/f1/d8232df68322ecdf811d61b1821a56451eef8a: No such file or directory
cp: testBuildOrg//.git/objects/f1/dc0cbc398d04f83838191fc2c8500d5f1e0f8c: No such file or directory
cp: testBuildOrg//.git/objects/f1/df648ee704b8121d66e9c445e60e3e44655920: No such file or directory
cp: testBuildOrg//.git/objects/f1/e5064e0c4e33d460362f2a267910949e334eb1: No such file or directory
cp: testBuildOrg//.git/objects/f1/e7a2ce515147197138986b60f422eaeeba9827: No such file or directory
cp: testBuildOrg//.git/objects/f1/ea61b5a37a0dab9f96c593a2e56c101d691e8f: No such file or directory
cp: testBuildOrg//.git/objects/f1/ec3f59af93d08fbe4a505f9f6c1d0560f82330: No such file or directory
cp: testBuildOrg//.git/objects/f1/f70df7ef6f411e6991a43f7802fbb477346ed3: No such file or directory
cp: testBuildOrg//.git/objects/f1/f7815698e88b38f9f70f148decc639af70681f: No such file or directory
cp: testBuildOrg//.git/objects/f1/ffea2d1906a9e63191b93849ffb51a641de933: No such file or directory
cp: testBuildOrg//.git/objects/f2/513ff43a7b98d51dc833ecf75c90847836ca53: No such file or directory
cp: testBuildOrg//.git/objects/f2/6416b34704af6ebc7ff345512c699882c96c06: No such file or directory
cp: testBuildOrg//.git/objects/f2/719316f1cd85f6f2d19a81a06cf7608bf9cd5b: No such file or directory
cp: testBuildOrg//.git/objects/f2/7ad279844b8679ea654d7fb84e403d5ca58b21: No such file or directory
cp: testBuildOrg//.git/objects/f2/7eba5869b9e0ca62f9eced33cc4e790443e19b: No such file or directory
cp: testBuildOrg//.git/objects/f2/8f905f7461c18b98fedadb9a0c224f42cf0811: No such file or directory
cp: testBuildOrg//.git/objects/f2/97fab3334c1e6ae4b90be64178f928da751bc7: No such file or directory
cp: testBuildOrg//.git/objects/f2/99686643370f126d03aa56de95e80b98f5041b: No such file or directory
cp: testBuildOrg//.git/objects/f2/9b73af4c1a7c1d4a5f12ec4572fd8504ae59c6: No such file or directory
cp: testBuildOrg//.git/objects/f2/9d96e24b0dce17d093db588a15da6c08caa71c: No such file or directory
cp: testBuildOrg//.git/objects/f2/a384e721fe22055c3e56b6ad649e35dbc399e2: No such file or directory
cp: testBuildOrg//.git/objects/f2/a963a063bbd4b26a6c61a2fd6e73e1dad0b8a8: No such file or directory
cp: testBuildOrg//.git/objects/f2/ad80316992ba8bb4b91909291faaba29bcb89f: No such file or directory
cp: testBuildOrg//.git/objects/f2/aec43f2f1700ef104fc338f6ea399e64b0410f: No such file or directory
cp: testBuildOrg//.git/objects/f2/af27fc9c3b1a3657eaa362d69dc4ac17cddef6: No such file or directory
cp: testBuildOrg//.git/objects/f2/b6f8f1632745b3ce394d09eb2838a961285f45: No such file or directory
cp: testBuildOrg//.git/objects/f2/bdcb8c43aeb8519975a25147b7c813e5479ec1: No such file or directory
cp: testBuildOrg//.git/objects/f2/bdfa9cf05c16f3091491abaed5de679cf1ef32: No such file or directory
cp: testBuildOrg//.git/objects/f2/c779ed936c1afbf3a0c86108befda6dfca213a: No such file or directory
cp: testBuildOrg//.git/objects/f2/c85d6c3243c2fe97a1da4bb98dc0d0a1456a64: No such file or directory
cp: testBuildOrg//.git/objects/f2/cbb1de723c6c5b4355568d72f8580142fb8505: No such file or directory
cp: testBuildOrg//.git/objects/f2/cef977a51fef85b5827a028b93177df469253b: No such file or directory
cp: testBuildOrg//.git/objects/f2/d2cacf93084db03b5c7a3755a53b24d0ab5f1b: No such file or directory
cp: testBuildOrg//.git/objects/f2/d7579b9037e634fbc35a9e6927b69e729cb536: No such file or directory
cp: testBuildOrg//.git/objects/f2/d766875e91c9870cdc857a2171c43c83675536: No such file or directory
cp: testBuildOrg//.git/objects/f2/dcab59ac856057b72508e748cafec5a359804e: No such file or directory
cp: testBuildOrg//.git/objects/f2/e9fe21aa2156a8243dbe82bed9a90322aba995: No such file or directory
cp: testBuildOrg//.git/objects/f2/ff55e3422afa27ee49dd5e52cf285232b2aae3: No such file or directory
cp: testBuildOrg//.git/objects/f3/1021502ee7c991c39e319dc0e91b850b1c46ba: No such file or directory
cp: testBuildOrg//.git/objects/f3/14898b6f797544f2fd0767cadc76e311bb891a: No such file or directory
cp: testBuildOrg//.git/objects/f3/15e9e72a62d202620d45f57217f39544996e65: No such file or directory
cp: testBuildOrg//.git/objects/f3/19bd9fb47518f47a31513fbfd64e11db9b809e: No such file or directory
cp: testBuildOrg//.git/objects/f3/1b0c1fc1c1c27d47a750ba622643a322695bda: No such file or directory
cp: testBuildOrg//.git/objects/f3/20eebe7a8bc761ffd60c308d63cb44673c734c: No such file or directory
cp: testBuildOrg//.git/objects/f3/698bc012f31fa8bf3bee6a38af501a2f1a38cb: No such file or directory
cp: testBuildOrg//.git/objects/f3/6d845e4a2357133340692462bd4678b988f2e2: No such file or directory
cp: testBuildOrg//.git/objects/f3/7c97dfa0c1c1e837709358a03402d8a9009774: No such file or directory
cp: testBuildOrg//.git/objects/f3/7cf2e60630243a383fff6393ff136c759dad97: No such file or directory
cp: testBuildOrg//.git/objects/f3/8c3e06d0777643537ea54acbdc623699656dce: No such file or directory
cp: testBuildOrg//.git/objects/f3/8d67516f9b13c8e7cea62c1df604618deccc76: No such file or directory
cp: testBuildOrg//.git/objects/f3/a3159087cd54deac32ccf7aebb3ec40542291f: No such file or directory
cp: testBuildOrg//.git/objects/f3/d4df6ebe6694da683e84878af8186f92d748f3: No such file or directory
cp: testBuildOrg//.git/objects/f3/e313f8f52b6d492bc2ab1dd199220da402d39a: No such file or directory
cp: testBuildOrg//.git/objects/f3/ebeea20ba4286007a8ee321b2ab80838b60639: No such file or directory
cp: testBuildOrg//.git/objects/f3/ed041ace7c97a4e47ba9bb7cff90a792bae611: No such file or directory
cp: testBuildOrg//.git/objects/f3/f054d4f707b0089c186774b3124fcdfc30b1b5: No such file or directory
cp: testBuildOrg//.git/objects/f3/f2c23efc34dcc7953aab8978ac88630ff4e323: No such file or directory
cp: testBuildOrg//.git/objects/f3/f3060ae4d37f2741198286e151b58cee04a5aa: No such file or directory
cp: testBuildOrg//.git/objects/f3/f8bbf4e7131feed6b808fd78183637910e75d1: No such file or directory
cp: testBuildOrg//.git/objects/f3/f9cde3739d9011a97a6cf81062833de9457c97: No such file or directory
cp: testBuildOrg//.git/objects/f3/fbfb2ccaa2d6cd9af976160a4a46cdc61fd28b: No such file or directory
cp: testBuildOrg//.git/objects/f4/3cb82ff4891759dc97520729d56ec11aaf5361: No such file or directory
cp: testBuildOrg//.git/objects/f4/4671b9465fad038756236a4cee13e5b2887aba: No such file or directory
cp: testBuildOrg//.git/objects/f4/4869228a99ddf1873f38a26bafd50a5c6a8a56: No such file or directory
cp: testBuildOrg//.git/objects/f4/4bf8494b8b415b8766b3e324345c05069c72ae: No such file or directory
cp: testBuildOrg//.git/objects/f4/52febda2a4e28833a8e005e4412a221a09f25d: No such file or directory
cp: testBuildOrg//.git/objects/f4/53c77a00662e322a6a27ab69d795b8a8177cd0: No such file or directory
cp: testBuildOrg//.git/objects/f4/554de56e9d04b85729f3a23c733b9040cb72e4: No such file or directory
cp: testBuildOrg//.git/objects/f4/5bd3c76e7b5553e4b2d5963206f92ae55a9fa8: No such file or directory
cp: testBuildOrg//.git/objects/f4/6df6af73a648b393e970480a3a49ac9af2badc: No such file or directory
cp: testBuildOrg//.git/objects/f4/7585ea4f04da1889e9f037df2b5743de3eb349: No such file or directory
cp: testBuildOrg//.git/objects/f4/7e52a35957051172a5c3265ffa392a53602810: No such file or directory
cp: testBuildOrg//.git/objects/f4/8eecccd7f4295cc4ec0420f6e48c2372928f71: No such file or directory
cp: testBuildOrg//.git/objects/f4/9ae0e114925980e7ec396a1764fa5ab886f480: No such file or directory
cp: testBuildOrg//.git/objects/f4/9b4c8ff0f264bbce62d9211fafe7f418e1ed1c: No such file or directory
cp: testBuildOrg//.git/objects/f4/9e9bf388a9b3513dae7bbe6f113c80352fb017: No such file or directory
cp: testBuildOrg//.git/objects/f4/b71db73364c68bc6b2ba6ecfeb24773f7db966: No such file or directory
cp: testBuildOrg//.git/objects/f4/b766bd324a8f0d75f2a38b96cafac96f3093ac: No such file or directory
cp: testBuildOrg//.git/objects/f4/b7bb8cdcae0e16950cb416d671208f18292e09: No such file or directory
cp: testBuildOrg//.git/objects/f4/c454c214a07af66c8e6f3909b96d41b3e280a1: No such file or directory
cp: testBuildOrg//.git/objects/f4/cad3fc05b2494e3cc1fc011ca93a8132239a2a: No such file or directory
cp: testBuildOrg//.git/objects/f4/cbe5189c2c183b9086abf261b34b71d9a542ee: No such file or directory
cp: testBuildOrg//.git/objects/f4/d276c4d03d7e3d0f0b47f92944d336b511bf3d: No such file or directory
cp: testBuildOrg//.git/objects/f4/d7954bd16f03a171738ce780c1b38f0773f7fc: No such file or directory
cp: testBuildOrg//.git/objects/f4/df09b13a47a69bd64f61a95b6538f201a86ffb: No such file or directory
cp: testBuildOrg//.git/objects/f4/ec31cf73bc4606853ecb2f9b66ddc14cae11e5: No such file or directory
cp: testBuildOrg//.git/objects/f4/f2ad8c2d249640205628184062e2424ad6141e: No such file or directory
cp: testBuildOrg//.git/objects/f4/f3c93010cd56f74f954801369078754b1eab41: No such file or directory
cp: testBuildOrg//.git/objects/f4/f9b901a167f72f33c0c803ceacb34a46ebad59: No such file or directory
cp: testBuildOrg//.git/objects/f4/fc200dd8aeee3767b6a9c95ee9ed3f1f17ea17: No such file or directory
cp: testBuildOrg//.git/objects/f4/fc2908620c6620c98c5740d61b8bc897d2f16e: No such file or directory
cp: testBuildOrg//.git/objects/f5/c88cd8aa316307d30ba0dfeee55558b6bc4b9d: No such file or directory
cp: testBuildOrg//.git/objects/f5/d2eedbf54a6e6f24da73f7e6c209c75aaddb0e: No such file or directory
cp: testBuildOrg//.git/objects/f5/d538da25507c23c6864e8644496f543f3cb897: No such file or directory
cp: testBuildOrg//.git/objects/f5/e8a9e9180e96ab80a039bd2308c42832c16ca3: No such file or directory
cp: testBuildOrg//.git/objects/f5/edd9f3c50ab992d4bcfb389cf16bbaeef83d02: No such file or directory
cp: testBuildOrg//.git/objects/f5/ee316d3d7078b3b79275906bc15471c413d6a9: No such file or directory
cp: testBuildOrg//.git/objects/f5/f28c795f3b4cc9605d3daa160f09ba5952e6f8: No such file or directory
cp: testBuildOrg//.git/objects/f5/f7075c7903a36e99be0aa98fa9c418806087b4: No such file or directory
cp: testBuildOrg//.git/objects/f5/f7bb579817ccae5c0ea6586ac040ebb2223826: No such file or directory
cp: testBuildOrg//.git/objects/f5/fc44177e9aa93444f412becc20aeb6ef09e739: No such file or directory
cp: testBuildOrg//.git/objects/f5/ffd6edf8a0812431e16fa60cfa505a36cb6637: No such file or directory
cp: testBuildOrg//.git/objects/f6/bada7df7f79f8404e75d9570f657f250743846: No such file or directory
cp: testBuildOrg//.git/objects/f6/c9ea2a135ec96cd37dd1d7970bcb26a3e11978: No such file or directory
cp: testBuildOrg//.git/objects/f6/cefdfe23a69726e3ff1782d89ee948a95f08c7: No such file or directory
cp: testBuildOrg//.git/objects/f6/d0cd4d690ca7d484317aa21261c8c4301e499b: No such file or directory
cp: testBuildOrg//.git/objects/f6/d2927d7da5b1eae7b5ef9e3ee578cbb6b745e7: No such file or directory
cp: testBuildOrg//.git/objects/f6/e24ff68f9839b946e78588aa226f3810a70d69: No such file or directory
cp: testBuildOrg//.git/objects/f6/e2e2ef8b2cc94ec489d316e56f78b9ebe490af: No such file or directory
cp: testBuildOrg//.git/objects/f6/e511f7d6b4ba5574e8e8aeacbe9e7fc72fe520: No such file or directory
cp: testBuildOrg//.git/objects/f6/e94d5ef8e4f14eae3925527d8d858535a1645a: No such file or directory
cp: testBuildOrg//.git/objects/f6/fd251dac83d59a6f8a0ba8a4f7237753ee36fe: No such file or directory
cp: testBuildOrg//.git/objects/f6/ff4da9d06d0a97d5d80008af5a10fb948a4952: No such file or directory
cp: testBuildOrg//.git/objects/f7/3255ae63e3c76960d1ca734a3e2bff24d1be2d: No such file or directory
cp: testBuildOrg//.git/objects/f7/3b376b53ba7d2178507b59f00be8634ed14949: No such file or directory
cp: testBuildOrg//.git/objects/f7/41b3e9ca9cbbac0a5546b1cd34e9e2fcdd8444: No such file or directory
cp: testBuildOrg//.git/objects/f7/420d4467e3ab61f45a8aaee4ba44ca52d8a4ce: No such file or directory
cp: testBuildOrg//.git/objects/f7/50512a534be30e3221a7ea989115806325bb90: No such file or directory
cp: testBuildOrg//.git/objects/f7/528af9dc4af598361fb3283034fc8790170260: No such file or directory
cp: testBuildOrg//.git/objects/f7/599c744b9d512ef52a5781c433f564828fa8e0: No such file or directory
cp: testBuildOrg//.git/objects/f7/5bd03f180ccf1149a8bf0baceb619d604d457e: No such file or directory
cp: testBuildOrg//.git/objects/f7/767e92944541842271ef02610dbba1da12f1cc: No such file or directory
cp: testBuildOrg//.git/objects/f7/8488d2e19f3c9ff1e7c6128553cd47ce855007: No such file or directory
cp: testBuildOrg//.git/objects/f7/8ed241a22a63465afb3596d5d4abdab52d1af3: No such file or directory
cp: testBuildOrg//.git/objects/f7/91f6f4ce365f30b4a28902078edd960399253c: No such file or directory
cp: testBuildOrg//.git/objects/f7/967ad12c3e7c2a642dda21e6b7649f7f290436: No such file or directory
cp: testBuildOrg//.git/objects/f7/98caa40b7a87a9e0d635ad956ef4cc1a50c7d9: No such file or directory
cp: testBuildOrg//.git/objects/f7/999a54baf53db66efef5c0602303448bdfebdb: No such file or directory
cp: testBuildOrg//.git/objects/f7/a1b07fa6cb6a12de5e3a91064f63deeef2fbb6: No such file or directory
cp: testBuildOrg//.git/objects/f7/a2f64f8592d8cfdb8e3085407d01072a07ac5b: No such file or directory
cp: testBuildOrg//.git/objects/f7/a3584e57ebb2eb046a2b4dcaddd175bb012049: No such file or directory
cp: testBuildOrg//.git/objects/f7/aae7ff555d25a05066b6fa7d4f23c2cb7284f8: No such file or directory
cp: testBuildOrg//.git/objects/f7/ab2298ab22d5bc8f51935552063ed140c73668: No such file or directory
cp: testBuildOrg//.git/objects/f7/b10a90515d4ce90fddc7ee6ac7cdff5c837674: No such file or directory
cp: testBuildOrg//.git/objects/f7/b75098e8b4def5fdefc056109e470e6f1c9600: No such file or directory
cp: testBuildOrg//.git/objects/f7/c6f29cb4b50773289e75b11ad782730c93b6da: No such file or directory
cp: testBuildOrg//.git/objects/f7/cb321c8413416d3ae483a78c76c0de0022f86d: No such file or directory
cp: testBuildOrg//.git/objects/f7/cfb82484f3cc436a758778a79a32e9a4c32ebd: No such file or directory
cp: testBuildOrg//.git/objects/f7/dc38d834695529f93164d2113b34107c66a51f: No such file or directory
cp: testBuildOrg//.git/objects/f7/e0019f31c407d037168e4cbb86ea6113ee5685: No such file or directory
cp: testBuildOrg//.git/objects/f7/e345619ea5e207fd838aa2315bb8c1307bdf01: No such file or directory
cp: testBuildOrg//.git/objects/f7/e5a7d692f1463d9990b48aa205d5a145b127eb: No such file or directory
cp: testBuildOrg//.git/objects/f7/e77b2e21ed7eb5e370e6331d301be4c81b07a2: No such file or directory
cp: testBuildOrg//.git/objects/f7/eb83380d0007591a056d8d3fe4357a30a67dd7: No such file or directory
cp: testBuildOrg//.git/objects/f7/edcf60e9937e57d6dd4e073982c0b803854fe1: No such file or directory
cp: testBuildOrg//.git/objects/f7/f382524467dfdb6baa9cd9b7c8157f3264d53c: No such file or directory
cp: testBuildOrg//.git/objects/f7/f95f792a97a81c01e5006cf5ead36ac174fe34: No such file or directory
cp: testBuildOrg//.git/objects/f7/fd3b695d234a5a9fd366c0e08c0407fdc3e701: No such file or directory
cp: testBuildOrg//.git/objects/f8/2081cfbd649ca88405e12c85dd15960add2aa5: No such file or directory
cp: testBuildOrg//.git/objects/f8/23fb2a459e3b574217882eced8d73ae997bd4b: No such file or directory
cp: testBuildOrg//.git/objects/f8/3386e75ec187a891966e8298d74b2dc3a82c67: No such file or directory
cp: testBuildOrg//.git/objects/f8/36a05c4979e51859cd25e41119384cd48522d5: No such file or directory
cp: testBuildOrg//.git/objects/f8/547f7e263b9b046c836ee1875f6b41a9f6dfa4: No such file or directory
cp: testBuildOrg//.git/objects/f8/5b614003b5309d128eff843348f4cb068bac47: No such file or directory
cp: testBuildOrg//.git/objects/f8/71917e142ad928dcaaf05286dcbb9428eae7c8: No such file or directory
cp: testBuildOrg//.git/objects/f8/7bf9aecf1c7f0d5a83b89202cb8fdac25ee4a2: No such file or directory
cp: testBuildOrg//.git/objects/f8/7c0266600e98e2cf6f8c3772930284ff6a0773: No such file or directory
cp: testBuildOrg//.git/objects/f8/7c8672248312ccbeabedeffe5a3d0ab7dc9299: No such file or directory
cp: testBuildOrg//.git/objects/f8/7d45c054bc709bd4a3252dbcb3fbad00969612: No such file or directory
cp: testBuildOrg//.git/objects/f8/7fef988ae7450e913f4f7e4b1a1cfd73bc6ed7: No such file or directory
cp: testBuildOrg//.git/objects/f8/807c8cc3c6fdda8c430efc3d32c5a3fe569bd5: No such file or directory
cp: testBuildOrg//.git/objects/f8/826d611708c24211718edc61e2ccb060af831a: No such file or directory
cp: testBuildOrg//.git/objects/f8/971a06d7e7d6fa1d0e6309ca01b224e8643bfc: No such file or directory
cp: testBuildOrg//.git/objects/f8/9731aaddacc82f34f3955569bca8bd0e628178: No such file or directory
cp: testBuildOrg//.git/objects/f8/9759dfe3fe30945d1f0e75330d15f697051c18: No such file or directory
cp: testBuildOrg//.git/objects/f8/a49ca90b6a63e22350f789e0e65901be194fc3: No such file or directory
cp: testBuildOrg//.git/objects/f8/a69f6b2c3498cf319815f41b8af021c1b661e9: No such file or directory
cp: testBuildOrg//.git/objects/f8/b41d14816b021ca55bfe82e08e5d774beea380: No such file or directory
cp: testBuildOrg//.git/objects/f8/b6720072f5932227166c44d40139becc689ae0: No such file or directory
cp: testBuildOrg//.git/objects/f8/b8354a214e861d0f8eb1eb6e17573c515acb93: No such file or directory
cp: testBuildOrg//.git/objects/f8/c1cad1a5f63901d1e0bd31f70260c5abf39738: No such file or directory
cp: testBuildOrg//.git/objects/f8/c4a2b6b52b6be78ddd3b6422c872892121a342: No such file or directory
cp: testBuildOrg//.git/objects/f8/de2eec5b88b561c16828a7c5fad3b69bd90c85: No such file or directory
cp: testBuildOrg//.git/objects/f9/328a6797ec3b5fd09e7ec81fb143e1e76b3019: No such file or directory
cp: testBuildOrg//.git/objects/f9/36bc2f0729289a40b3396d99ca8ec53e637c79: No such file or directory
cp: testBuildOrg//.git/objects/f9/39985ec113d80f2b565ead8483d988d8ada704: No such file or directory
cp: testBuildOrg//.git/objects/f9/4dd87fa581f6959fc479be639c482e39b1429c: No such file or directory
cp: testBuildOrg//.git/objects/f9/53e6e45f95868556bd216d3622da8330fcba28: No such file or directory
cp: testBuildOrg//.git/objects/f9/56cefe1a68d2a540e9b96ef9310f6134f70ee8: No such file or directory
cp: testBuildOrg//.git/objects/f9/595e121285dd3e532100866b2c0b123e065f98: No such file or directory
cp: testBuildOrg//.git/objects/f9/5decfae8f807fda6047fb504099632367afa0e: No such file or directory
cp: testBuildOrg//.git/objects/f9/60baa69fefbd64febb5c08a038f3245bb3953a: No such file or directory
cp: testBuildOrg//.git/objects/f9/6496c4084dbefe281fec5a5c9fa22617dc9585: No such file or directory
cp: testBuildOrg//.git/objects/f9/663e6df034b463541bbbcf6d8830be4fb67b0d: No such file or directory
cp: testBuildOrg//.git/objects/f9/6dd1f175e90ce4283f768cbf53b0adb924964f: No such file or directory
cp: testBuildOrg//.git/objects/f9/8e77e6805a6b77f943f9c2ca2471b440a89206: No such file or directory
cp: testBuildOrg//.git/objects/f9/91033ac9bace765659c6d479360db48cde2dce: No such file or directory
cp: testBuildOrg//.git/objects/f9/97eb5f504146f0225b4b29355017ea108449ff: No such file or directory
cp: testBuildOrg//.git/objects/f9/9cb8575d25c4d1a43fb1ee698b94ce4812aa8e: No such file or directory
cp: testBuildOrg//.git/objects/f9/abc32800f783863c86a7a0c067a897303758a6: No such file or directory
cp: testBuildOrg//.git/objects/f9/b26079b3313f70f43b5c7ae116032318810416: No such file or directory
cp: testBuildOrg//.git/objects/f9/b3b17921a70ae7865eb3558f145f1f923d37bb: No such file or directory
cp: testBuildOrg//.git/objects/f9/b4d964824473ee28760f7fb9f4d461e3db5c91: No such file or directory
cp: testBuildOrg//.git/objects/f9/b8069136e5e4dcf1c56c53141036ac39cd5418: No such file or directory
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
cp: testBuildOrg//.git/objects/fa/f5c06dee410eb74f265edf65d3cf6b1b8b244e: No such file or directory
cp: testBuildOrg//.git/objects/fa/f65e07f68f84be9cfc1a8355aa34b435f6f3c7: No such file or directory
cp: testBuildOrg//.git/objects/fa/fd3982709eaae8623e29fb76f2c9ab054e315b: No such file or directory
cp: testBuildOrg//.git/objects/fa/fe3d897fa180bc6e2c02543502dd22d58d61ed: No such file or directory
cp: testBuildOrg//.git/objects/fb/ab494773e49b31ca5734921b902d229f991d29: No such file or directory
cp: testBuildOrg//.git/objects/fb/b1b27a665ea42ed7c0aaef3fcc4e9711962196: No such file or directory
cp: testBuildOrg//.git/objects/fb/b22d25b2e4605fd40ec3c31c65b6c81ff2a572: No such file or directory
cp: testBuildOrg//.git/objects/fb/b488a9df299e648045089c16a420ca9862373e: No such file or directory
cp: testBuildOrg//.git/objects/fb/c6a5ebe451bb27de396c726ec3891f6690d299: No such file or directory
cp: testBuildOrg//.git/objects/fb/c720e48a3e1ae9cafd4ac74a27cd4f0c434e95: No such file or directory
cp: testBuildOrg//.git/objects/fb/ce2387518065de7a8dbcd20b6c3de014de8bae: No such file or directory
cp: testBuildOrg//.git/objects/fb/d53591136e4ef357ced951c1a78d8c8971212b: No such file or directory
cp: testBuildOrg//.git/objects/fb/ddcb489f229186b40c2858560d5c2b216b5c25: No such file or directory
cp: testBuildOrg//.git/objects/fb/e843926443d51e70223ab123f4e57917b570fc: No such file or directory
cp: testBuildOrg//.git/objects/fb/fed8f1d7df4495ded7cfff5aac4acaabd359ec: No such file or directory
cp: testBuildOrg//.git/objects/fc/8a2a7070cbf9a88b1f314472860e6372b4b019: No such file or directory
cp: testBuildOrg//.git/objects/fc/8c50feaab0573d3f060387afa9e51d763b7c20: No such file or directory
cp: testBuildOrg//.git/objects/fc/9972a2d20167e9e364cb3cc1daed8a50c8f8a1: No such file or directory
cp: testBuildOrg//.git/objects/fc/9f7d3fa55719c44b048f63e3f12be4c564aaa7: No such file or directory
cp: testBuildOrg//.git/objects/fc/9fa6f146b04765f20140e6c8b6afb5da277899: No such file or directory
cp: testBuildOrg//.git/objects/fc/b2e773f8da16b99972459a0be68fbef56f5ea9: No such file or directory
cp: testBuildOrg//.git/objects/fc/b3114927c194b051c714cab0fb29ff602ec306: No such file or directory
cp: testBuildOrg//.git/objects/fc/b904fd247e05224771a4153894850f3ef80581: No such file or directory
cp: testBuildOrg//.git/objects/fc/c251a5fe1db2bd7ea4904b8aff5ff66b5bfcdd: No such file or directory
cp: testBuildOrg//.git/objects/fc/c46903369ec497f9b777881a67060f5e2fce7f: No such file or directory
cp: testBuildOrg//.git/objects/fc/c7f1711f4e9b378fdd48c5f31a1278bd9e7c94: No such file or directory
cp: testBuildOrg//.git/objects/fc/cc2691b6095b3d7b9674b5d680bbe894ab3ee7: No such file or directory
cp: testBuildOrg//.git/objects/fc/cea7e88e56be399f07ec44c0d717ba4f438ee9: No such file or directory
cp: testBuildOrg//.git/objects/fc/dc31b81da2f98f626a7f15604b9935cee18e95: No such file or directory
cp: testBuildOrg//.git/objects/fc/f0eb996a97e16e9e7152077ffe0cdb9aaeb727: No such file or directory
cp: testBuildOrg//.git/objects/fc/f4b31ec06a85611d976b377fa38e6a9f2caa3a: No such file or directory
cp: testBuildOrg//.git/objects/fd/50bd4036c924fe3b52f6a5840424537d95cedf: No such file or directory
cp: testBuildOrg//.git/objects/fd/5e9ba414e376f1d19a3b8d762fd434e76db0da: No such file or directory
cp: testBuildOrg//.git/objects/fd/64960fe50e22f1ee65750ecae864737799c9c8: No such file or directory
cp: testBuildOrg//.git/objects/fd/68e1b3035feda2fa3051cab2de5a828a33eb0e: No such file or directory
cp: testBuildOrg//.git/objects/fd/6e67489fb668ae33790f29996aa60aa78625db: No such file or directory
cp: testBuildOrg//.git/objects/fd/786947f93abbb5002a745c2af6f4b20d9d7f6c: No such file or directory
cp: testBuildOrg//.git/objects/fd/7c8cddbfc7bd4692d97c4045ea095ddef91fc4: No such file or directory
cp: testBuildOrg//.git/objects/fd/7eafcb617794330ae8e966601f3802b476354e: No such file or directory
cp: testBuildOrg//.git/objects/fd/83edafc2d69c3cf3ee27f08b6b34d18d602de1: No such file or directory
cp: testBuildOrg//.git/objects/fd/8a85244b3b7c02bc487bc6ca5c1bd9f8a65e6a: No such file or directory
cp: testBuildOrg//.git/objects/fd/8d22b68c82dbfc27003698b132288710fea842: No such file or directory
cp: testBuildOrg//.git/objects/fd/a5ffe3156fc8e984575384970805c9c7f2fb14: No such file or directory
cp: testBuildOrg//.git/objects/fd/a7c0b5ec1d5a867275a2c189e4e4bb51091be4: No such file or directory
cp: testBuildOrg//.git/objects/fd/a9f42f245e48cc140537e86cde9cdc301a80ce: No such file or directory
cp: testBuildOrg//.git/objects/fd/ae11fa91338d087b439b3e8132da14f14b5ee3: No such file or directory
cp: testBuildOrg//.git/objects/fd/aee9708259df02140f3b9129f7fa0eccedc52f: No such file or directory
cp: testBuildOrg//.git/objects/fd/c174e40cae6b0a817476ca54fc8320d4eb354c: No such file or directory
cp: testBuildOrg//.git/objects/fd/d630afb5e2d9adf7e4349fe8f516a4987e0ea7: No such file or directory
cp: testBuildOrg//.git/objects/fd/e0215087e8b7de836d0ac6454d7c4bbc90bd37: No such file or directory
cp: testBuildOrg//.git/objects/fd/e119119b56346ab1c9b35d52769bf62bf3b15a: No such file or directory
cp: testBuildOrg//.git/objects/fd/ead750b81f05adb51b80cef180668436402394: No such file or directory
cp: testBuildOrg//.git/objects/fd/ed54dbf26ab1cf83c63e04075fc13989a92f43: No such file or directory
cp: testBuildOrg//.git/objects/fd/eec24b9ee162fabac137f2ca0def13cca35aa2: No such file or directory
cp: testBuildOrg//.git/objects/fd/ef387a0b162a06608dfc9bf2b8c957e4a027e1: No such file or directory
cp: testBuildOrg//.git/objects/fd/f1d3baaa5524b9b91430b325c0c0811f029c26: No such file or directory
cp: testBuildOrg//.git/objects/fd/fa90b74bbf0e211e2b0d93dc01224e50fdf75b: No such file or directory
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
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/socket.io
npm http request GET http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/fs-extra-promise
npm http 200 http://192.168.1.100:4873/lie
npm http 200 http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/socket.io
npm http 200 http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/cookie-signature
npm http request GET http://192.168.1.100:4873/escape-html
npm http request GET http://192.168.1.100:4873/cookie
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/content-disposition
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/accepts
npm http request GET http://192.168.1.100:4873/array-flatten
npm http request GET http://192.168.1.100:4873/merge-descriptors
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/parseurl
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/fresh
npm http request GET http://192.168.1.100:4873/finalhandler
npm http request GET http://192.168.1.100:4873/etag
npm http request GET http://192.168.1.100:4873/proxy-addr
npm http request GET http://192.168.1.100:4873/path-to-regexp
npm http request GET http://192.168.1.100:4873/range-parser
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/send
npm http request GET http://192.168.1.100:4873/utils-merge
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/vary
npm http request GET http://192.168.1.100:4873/serve-static
npm http 200 http://192.168.1.100:4873/escape-html
npm http 200 http://192.168.1.100:4873/depd
npm http 200 http://192.168.1.100:4873/debug
npm http 200 http://192.168.1.100:4873/cookie-signature
npm http 200 http://192.168.1.100:4873/cookie
npm http 200 http://192.168.1.100:4873/content-type
npm http 200 http://192.168.1.100:4873/merge-descriptors
npm http 200 http://192.168.1.100:4873/content-disposition
npm http 200 http://192.168.1.100:4873/accepts
npm http 200 http://192.168.1.100:4873/array-flatten
npm http 200 http://192.168.1.100:4873/methods
npm http 200 http://192.168.1.100:4873/on-finished
npm http 200 http://192.168.1.100:4873/fresh
npm http 200 http://192.168.1.100:4873/parseurl
npm http 200 http://192.168.1.100:4873/finalhandler
npm http 200 http://192.168.1.100:4873/etag
npm http 200 http://192.168.1.100:4873/proxy-addr
npm http 200 http://192.168.1.100:4873/range-parser
npm http 200 http://192.168.1.100:4873/path-to-regexp
npm http 200 http://192.168.1.100:4873/qs
npm http 200 http://192.168.1.100:4873/send
npm http 200 http://192.168.1.100:4873/utils-merge
npm http 200 http://192.168.1.100:4873/type-is
npm http 200 http://192.168.1.100:4873/serve-static
npm http 200 http://192.168.1.100:4873/vary
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
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/mime
npm http request GET http://192.168.1.100:4873/statuses
npm http 200 http://192.168.1.100:4873/http-errors
npm http 200 http://192.168.1.100:4873/destroy
npm http 200 http://192.168.1.100:4873/mime
npm http 200 http://192.168.1.100:4873/statuses
npm http request GET http://192.168.1.100:4873/inherits
npm http 200 http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/media-typer
npm http 200 http://192.168.1.100:4873/media-typer
npm http request GET http://192.168.1.100:4873/fs-extra
npm http request GET http://192.168.1.100:4873/bluebird
npm http 200 http://192.168.1.100:4873/bluebird
npm http 200 http://192.168.1.100:4873/fs-extra
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
npm http 200 http://192.168.1.100:4873/path-is-absolute
npm http 200 http://192.168.1.100:4873/inflight
npm http 200 http://192.168.1.100:4873/once
npm http 200 http://192.168.1.100:4873/fs.realpath
npm http 200 http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/wrappy
npm http 200 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 200 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/balanced-match
npm http 200 http://192.168.1.100:4873/concat-map
npm http 200 http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 200 http://192.168.1.100:4873/es3ify
npm http 200 http://192.168.1.100:4873/inline-process-browser
npm http 200 http://192.168.1.100:4873/unreachable-branch-transform
npm http 200 http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/through
npm http 200 http://192.168.1.100:4873/jstransform
npm http 200 http://192.168.1.100:4873/through
npm http 200 http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/source-map
npm http 200 http://192.168.1.100:4873/base62
npm http 200 http://192.168.1.100:4873/source-map
npm http 200 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/esprima-fb
npm http 200 http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/recast
npm http 200 http://192.168.1.100:4873/private
npm http 200 http://192.168.1.100:4873/commander
npm http 200 http://192.168.1.100:4873/q
npm http 200 http://192.168.1.100:4873/mkdirp
npm http 200 http://192.168.1.100:4873/iconv-lite
npm http 200 http://192.168.1.100:4873/detective
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
npm http 200 http://192.168.1.100:4873/through2
npm http 200 http://192.168.1.100:4873/falafel
npm http request GET http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/object-keys
npm http 200 http://192.168.1.100:4873/object-keys
npm http 200 http://192.168.1.100:4873/foreach
npm http 200 http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 200 http://192.168.1.100:4873/xtend
npm http 200 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/string_decoder
npm http request GET http://192.168.1.100:4873/core-util-is
npm http 200 http://192.168.1.100:4873/string_decoder
npm http 200 http://192.168.1.100:4873/core-util-is
npm http request GET http://192.168.1.100:4873/esmangle-evaluator
npm http 200 http://192.168.1.100:4873/esmangle-evaluator
npm http request GET http://192.168.1.100:4873/socket.io-parser
npm http request GET http://192.168.1.100:4873/has-binary-data
npm http request GET http://192.168.1.100:4873/socket.io-adapter
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/engine.io
npm http 200 http://192.168.1.100:4873/socket.io-parser
npm http 200 http://192.168.1.100:4873/has-binary-data
npm http 200 http://192.168.1.100:4873/socket.io-adapter
npm http 200 http://192.168.1.100:4873/engine.io
npm http 200 http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/base64id
npm http request GET http://192.168.1.100:4873/ws
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http 200 http://192.168.1.100:4873/base64id
npm http 200 http://192.168.1.100:4873/engine.io-parser
npm http 200 http://192.168.1.100:4873/ws
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/has-binary
npm http request GET http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/utf8
npm http 200 http://192.168.1.100:4873/base64-arraybuffer
npm http 200 http://192.168.1.100:4873/after
npm http 200 http://192.168.1.100:4873/blob
npm http 200 http://192.168.1.100:4873/arraybuffer.slice
npm http 200 http://192.168.1.100:4873/has-binary
npm http 200 http://192.168.1.100:4873/utf8
npm http request GET http://192.168.1.100:4873/options
npm http request GET http://192.168.1.100:4873/bufferutil
npm http request GET http://192.168.1.100:4873/ultron
npm http request GET http://192.168.1.100:4873/utf-8-validate
npm http 200 http://192.168.1.100:4873/ultron
npm http 200 http://192.168.1.100:4873/options
npm http 200 http://192.168.1.100:4873/utf-8-validate
npm http 200 http://192.168.1.100:4873/bufferutil
npm http request GET http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/nan
npm http 200 http://192.168.1.100:4873/bindings
npm http 200 http://192.168.1.100:4873/nan
npm http request GET http://192.168.1.100:4873/component-emitter
npm http request GET http://192.168.1.100:4873/json3
npm http request GET http://192.168.1.100:4873/benchmark
npm http 200 http://192.168.1.100:4873/component-emitter
npm http 200 http://192.168.1.100:4873/json3
npm http 200 http://192.168.1.100:4873/benchmark
npm http request GET http://192.168.1.100:4873/component-bind
npm http request GET http://192.168.1.100:4873/parseuri
npm http request GET http://192.168.1.100:4873/indexof
npm http request GET http://192.168.1.100:4873/object-component
npm http request GET http://192.168.1.100:4873/backo2
npm http request GET http://192.168.1.100:4873/to-array
npm http request GET http://192.168.1.100:4873/engine.io-client
npm http 200 http://192.168.1.100:4873/parseuri
npm http 200 http://192.168.1.100:4873/component-bind
npm http 200 http://192.168.1.100:4873/indexof
npm http 200 http://192.168.1.100:4873/object-component
npm http 200 http://192.168.1.100:4873/backo2
npm http 200 http://192.168.1.100:4873/to-array
npm http 200 http://192.168.1.100:4873/engine.io-client
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/parseqs
npm http fetch GET https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http 200 http://192.168.1.100:4873/has-cors
npm http 200 http://192.168.1.100:4873/component-inherit
npm http 200 http://192.168.1.100:4873/parsejson
npm http 200 http://192.168.1.100:4873/parseqs
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
npm http request GET http://192.168.1.100:4873/cycle
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/colors
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/eyes
npm http 200 http://192.168.1.100:4873/stack-trace
npm http 200 http://192.168.1.100:4873/colors
npm http 200 http://192.168.1.100:4873/pkginfo
npm http 200 http://192.168.1.100:4873/cycle
npm http 200 http://192.168.1.100:4873/async
npm http 200 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/eyes
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
npm http request GET http://192.168.1.100:4873/salti
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/ip
npm http 200 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/express
npm http 200 http://192.168.1.100:4873/forever-agent
npm http 200 http://192.168.1.100:4873/lie
npm http 200 http://192.168.1.100:4873/javascript-state-machine
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 200 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/winston
npm http 304 http://192.168.1.100:4873/salti
npm http 200 http://192.168.1.100:4873/multiplex
npm http 200 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/raw-body
npm http 200 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/http-errors
npm http 200 http://192.168.1.100:4873/bytes
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/depd
npm http 200 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/type-is
npm http 200 http://192.168.1.100:4873/raw-body
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/statuses
npm http 304 http://192.168.1.100:4873/inherits
npm http 200 http://192.168.1.100:4873/statuses
npm http request GET http://192.168.1.100:4873/ee-first
npm http 304 http://192.168.1.100:4873/ee-first
npm http request GET http://192.168.1.100:4873/unpipe
npm http 304 http://192.168.1.100:4873/unpipe
npm http request GET http://192.168.1.100:4873/media-typer
npm http request GET http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/media-typer
npm http 200 http://192.168.1.100:4873/mime-types
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
npm http 304 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/serve-static
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/send
npm http 304 http://192.168.1.100:4873/utils-merge
npm http 304 http://192.168.1.100:4873/vary
npm http request GET http://192.168.1.100:4873/negotiator
npm http 304 http://192.168.1.100:4873/negotiator
npm http request GET http://192.168.1.100:4873/forwarded
npm http request GET http://192.168.1.100:4873/ipaddr.js
npm http 304 http://192.168.1.100:4873/ipaddr.js
npm http 200 http://192.168.1.100:4873/forwarded
npm http request GET http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/mime
npm http 304 http://192.168.1.100:4873/destroy
npm http 200 http://192.168.1.100:4873/mime
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 200 http://192.168.1.100:4873/inline-process-browser
npm http 304 http://192.168.1.100:4873/es3ify
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
npm http 304 http://192.168.1.100:4873/commoner
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/base62
npm http 304 http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/mkdirp
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http 304 http://192.168.1.100:4873/detective
npm http 304 http://192.168.1.100:4873/commander
npm http 304 http://192.168.1.100:4873/private
npm http 304 http://192.168.1.100:4873/q
npm http 200 http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/recast
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
npm http 304 http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/inflight
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
npm http 200 http://192.168.1.100:4873/amdefine
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
npm http request GET http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/string_decoder
npm http request GET http://192.168.1.100:4873/core-util-is
npm http 304 http://192.168.1.100:4873/core-util-is
npm http 200 http://192.168.1.100:4873/string_decoder
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
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 200 http://192.168.1.100:4873/process-nextick-args
npm http 200 http://192.168.1.100:4873/util-deprecate
npm http 200 http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http 200 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/bl
npm http 200 http://192.168.1.100:4873/json-stringify-safe
npm http 200 http://192.168.1.100:4873/tunnel-agent
npm http 200 http://192.168.1.100:4873/caseless
npm http 200 http://192.168.1.100:4873/stringstream
npm http 200 http://192.168.1.100:4873/combined-stream
npm http 200 http://192.168.1.100:4873/aws-sign2
npm http 200 http://192.168.1.100:4873/form-data
npm http 200 http://192.168.1.100:4873/har-validator
npm http 200 http://192.168.1.100:4873/oauth-sign
npm http 200 http://192.168.1.100:4873/hawk
npm http 200 http://192.168.1.100:4873/http-signature
npm http 200 http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 200 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 200 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http 304 http://192.168.1.100:4873/bluebird
npm http 200 http://192.168.1.100:4873/chalk
npm http 200 http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 200 http://192.168.1.100:4873/strip-ansi
npm http 200 http://192.168.1.100:4873/supports-color
npm http 200 http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/ansi-styles
npm http 200 http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 200 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http request GET http://192.168.1.100:4873/generate-function
npm http 200 http://192.168.1.100:4873/generate-object-property
npm http 200 http://192.168.1.100:4873/generate-function
npm http 200 http://192.168.1.100:4873/jsonpointer
npm http request GET http://192.168.1.100:4873/is-property
npm http 200 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/boom
npm http 200 http://192.168.1.100:4873/cryptiles
npm http 200 http://192.168.1.100:4873/sntp
npm http 200 http://192.168.1.100:4873/boom
npm http 200 http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/assert-plus
npm http 200 http://192.168.1.100:4873/ctype
npm http 200 http://192.168.1.100:4873/asn1
npm http 200 http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/colors
npm http request GET http://192.168.1.100:4873/cycle
npm http request GET http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/pkginfo
npm http request GET http://192.168.1.100:4873/stack-trace
npm http 304 http://192.168.1.100:4873/cycle
npm http 304 http://192.168.1.100:4873/eyes
npm http 304 http://192.168.1.100:4873/stack-trace
npm http 200 http://192.168.1.100:4873/colors
npm http 304 http://192.168.1.100:4873/pkginfo
npm http request GET http://192.168.1.100:4873/jsdoc
npm http 200 http://192.168.1.100:4873/jsdoc
npm http request GET http://192.168.1.100:4873/catharsis
npm http request GET http://192.168.1.100:4873/js2xmlparser
npm http request GET http://192.168.1.100:4873/requizzle
npm http request GET http://192.168.1.100:4873/marked
npm http request GET http://192.168.1.100:4873/wrench
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/underscore
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 200 http://192.168.1.100:4873/catharsis
npm http 200 http://192.168.1.100:4873/marked
npm http 200 http://192.168.1.100:4873/requizzle
npm http 200 http://192.168.1.100:4873/js2xmlparser
npm http 200 http://192.168.1.100:4873/wrench
npm WARN deprecated wrench@1.5.9: wrench.js is deprecated! You should check out fs-extra (https://github.com/jprichardson/node-fs-extra) for any operations you were using wrench for. Thanks for all the usage over the years.
npm http 200 http://192.168.1.100:4873/strip-json-comments
npm http 200 http://192.168.1.100:4873/underscore
npm http fetch 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http request GET http://192.168.1.100:4873/underscore-contrib
npm http 200 http://192.168.1.100:4873/underscore-contrib
npm WARN prefer global marked@0.3.6 should be installed with -g
npm http request GET http://192.168.1.100:4873/fs-extra-promise
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/jxc
npm http request GET http://192.168.1.100:4873/unzip
npm http 304 http://192.168.1.100:4873/lie
npm http 304 http://192.168.1.100:4873/fs-extra-promise
npm http 304 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/unzip
npm http 200 http://192.168.1.100:4873/jxc
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
npm http 304 http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/fs.realpath
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/minimatch
npm http 304 http://192.168.1.100:4873/inflight
npm http 304 http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/fs.realpath
npm http request GET http://192.168.1.100:4873/wrappy
npm http 304 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 304 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/progress
npm http request GET http://192.168.1.100:4873/adm-zip
npm http 200 http://192.168.1.100:4873/adm-zip
npm http 200 http://192.168.1.100:4873/progress
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 304 http://192.168.1.100:4873/inline-process-browser
npm http 304 http://192.168.1.100:4873/es3ify
npm http 304 http://192.168.1.100:4873/immediate
npm http 304 http://192.168.1.100:4873/unreachable-branch-transform
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
npm http 304 http://192.168.1.100:4873/commoner
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/base62
npm http 304 http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/mkdirp
npm http 304 http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/commander
npm http 304 http://192.168.1.100:4873/private
npm http 304 http://192.168.1.100:4873/detective
npm http 304 http://192.168.1.100:4873/q
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
npm http request GET http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/foreach
npm http 304 http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/object-keys
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/readable-stream
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
npm http 304 http://192.168.1.100:4873/forever-agent
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 200 http://192.168.1.100:4873/util-deprecate
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
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/ansi-styles
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-function
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http request GET http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/hoek
npm http 304 http://192.168.1.100:4873/boom
npm http 304 http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 304 http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/fstream
npm http request GET http://192.168.1.100:4873/binary
npm http request GET http://192.168.1.100:4873/pullstream
npm http request GET http://192.168.1.100:4873/setimmediate
npm http request GET http://192.168.1.100:4873/match-stream
npm http 200 http://192.168.1.100:4873/pullstream
npm http 200 http://192.168.1.100:4873/setimmediate
npm http 200 http://192.168.1.100:4873/binary
npm http 200 http://192.168.1.100:4873/match-stream
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
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/tape
npm http request GET http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/nock
npm http request GET http://192.168.1.100:4873/pouchdb-node
npm http request GET http://192.168.1.100:4873/bn.js
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/express-pouchdb
npm http request GET http://192.168.1.100:4873/proxyquire
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/request-promise
npm http request GET http://192.168.1.100:4873/leveldown-mobile
npm http request GET http://192.168.1.100:4873/supertest-as-promised
npm http request GET http://192.168.1.100:4873/tape-catch
npm http request GET http://192.168.1.100:4873/sinon
npm http request GET http://192.168.1.100:4873/supertest
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/tmp
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/forever-agent
npm http 304 http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/tape
npm http 200 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/socket.io-client
npm http 304 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/randomstring
npm http 304 http://192.168.1.100:4873/multiplex
npm http 200 http://192.168.1.100:4873/nock
npm http 304 http://192.168.1.100:4873/pouchdb-node
npm http 304 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/bn.js
npm http 304 http://192.168.1.100:4873/express-pouchdb
npm http 200 http://192.168.1.100:4873/js-extend
npm http 200 http://192.168.1.100:4873/proxyquire
npm http 200 http://192.168.1.100:4873/request-promise
npm http 200 http://192.168.1.100:4873/sinon
npm http 304 http://192.168.1.100:4873/tape-catch
npm http 200 http://192.168.1.100:4873/supertest-as-promised
npm http 200 http://192.168.1.100:4873/supertest
npm http 200 http://192.168.1.100:4873/uuid
npm http 200 http://192.168.1.100:4873/tmp
npm http 304 http://192.168.1.100:4873/leveldown-mobile
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
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/on-finished
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
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/serve-static
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/send
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
npm http 304 http://192.168.1.100:4873/destroy
npm http 304 http://192.168.1.100:4873/mime
npm http request GET http://192.168.1.100:4873/basic-auth
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/pouchdb-list
npm http request GET http://192.168.1.100:4873/pouchdb-auth
npm http request GET http://192.168.1.100:4873/pouchdb-find
npm http request GET http://192.168.1.100:4873/multiparty
npm http request GET http://192.168.1.100:4873/pouchdb-all-dbs
npm http request GET http://192.168.1.100:4873/compression
npm http request GET http://192.168.1.100:4873/header-case-normalizer
npm http request GET http://192.168.1.100:4873/cookie-parser
npm http request GET http://192.168.1.100:4873/pouchdb-vhost
npm http request GET http://192.168.1.100:4873/pouchdb-validation
npm http request GET http://192.168.1.100:4873/pouchdb-update
npm http request GET http://192.168.1.100:4873/pouchdb-size
npm http request GET http://192.168.1.100:4873/pouchdb-show
npm http request GET http://192.168.1.100:4873/pouchdb-security
npm http request GET http://192.168.1.100:4873/pouchdb-replicator
npm http request GET http://192.168.1.100:4873/pouchdb-rewrite
npm http request GET http://192.168.1.100:4873/pouchdb-wrappers
npm http 200 http://192.168.1.100:4873/basic-auth
npm http 200 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/multiparty
npm http 304 http://192.168.1.100:4873/pouchdb-find
npm http 304 http://192.168.1.100:4873/pouchdb-list
npm http 304 http://192.168.1.100:4873/pouchdb-all-dbs
npm http 200 http://192.168.1.100:4873/compression
npm http 200 http://192.168.1.100:4873/cookie-parser
npm http 200 http://192.168.1.100:4873/pouchdb-auth
npm http 200 http://192.168.1.100:4873/header-case-normalizer
npm http 200 http://192.168.1.100:4873/pouchdb-validation
npm http 304 http://192.168.1.100:4873/pouchdb-size
npm http 304 http://192.168.1.100:4873/pouchdb-update
npm http 304 http://192.168.1.100:4873/pouchdb-vhost
npm http 304 http://192.168.1.100:4873/pouchdb-replicator
npm http 304 http://192.168.1.100:4873/pouchdb-rewrite
npm http 304 http://192.168.1.100:4873/pouchdb-show
npm http 200 http://192.168.1.100:4873/pouchdb-wrappers
npm http 200 http://192.168.1.100:4873/pouchdb-security
npm http request GET http://192.168.1.100:4873/setprototypeof
npm http 200 http://192.168.1.100:4873/setprototypeof
npm http request GET http://192.168.1.100:4873/compressible
npm http request GET http://192.168.1.100:4873/on-headers
npm http 200 http://192.168.1.100:4873/compressible
npm http 200 http://192.168.1.100:4873/on-headers
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/stream-counter
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 200 http://192.168.1.100:4873/stream-counter
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/tiny-queue
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/argsarray
npm http 304 http://192.168.1.100:4873/es3ify
npm http 200 http://192.168.1.100:4873/argsarray
npm http 200 http://192.168.1.100:4873/tiny-queue
npm http 200 http://192.168.1.100:4873/pouchdb-promise
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
npm http request GET http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http request GET http://192.168.1.100:4873/pouchdb-plugin-error
npm http request GET http://192.168.1.100:4873/pouchdb
npm http request GET http://192.168.1.100:4873/promise-nodify
npm http request GET http://192.168.1.100:4873/pouchdb-system-db
npm http request GET http://192.168.1.100:4873/pouchdb-req-http-query
npm http request GET http://192.168.1.100:4873/secure-random
npm http 200 http://192.168.1.100:4873/base64url
npm http 200 http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http 200 http://192.168.1.100:4873/couchdb-calculate-session-id
npm http 200 http://192.168.1.100:4873/pouchdb
npm http 200 http://192.168.1.100:4873/pouchdb-plugin-error
npm http 200 http://192.168.1.100:4873/promise-nodify
npm http 200 http://192.168.1.100:4873/pouchdb-system-db
npm http 200 http://192.168.1.100:4873/pouchdb-req-http-query
npm http 200 http://192.168.1.100:4873/crypto-lite
npm http 200 http://192.168.1.100:4873/secure-random
npm http request GET http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/meow
npm http 200 http://192.168.1.100:4873/meow
npm http 200 http://192.168.1.100:4873/concat-stream
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
npm http request GET http://192.168.1.100:4873/get-stdin
npm http request GET http://192.168.1.100:4873/repeating
npm http 200 http://192.168.1.100:4873/get-stdin
npm http 200 http://192.168.1.100:4873/repeating
npm http request GET http://192.168.1.100:4873/is-finite
npm http 200 http://192.168.1.100:4873/is-finite
npm http request GET http://192.168.1.100:4873/number-is-nan
npm http 200 http://192.168.1.100:4873/number-is-nan
npm http request GET http://192.168.1.100:4873/aproba
npm http 200 http://192.168.1.100:4873/aproba
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/fruitdown
npm http request GET http://192.168.1.100:4873/es6-promise-pool
npm http request GET http://192.168.1.100:4873/level-write-stream
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/memdown
npm http request GET http://192.168.1.100:4873/localstorage-down
npm http request GET http://192.168.1.100:4873/pouchdb-collate
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/scope-eval
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/vuvuzela
npm http request GET http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/es6-promise-pool
npm http 200 http://192.168.1.100:4873/level-write-stream
npm http 200 http://192.168.1.100:4873/double-ended-queue
npm http 200 http://192.168.1.100:4873/fruitdown
npm http 200 http://192.168.1.100:4873/localstorage-down
npm http 200 http://192.168.1.100:4873/pouchdb-collate
npm http 200 http://192.168.1.100:4873/pouchdb-collections
npm http 200 http://192.168.1.100:4873/memdown
npm http 200 http://192.168.1.100:4873/scope-eval
npm http 200 http://192.168.1.100:4873/sublevel-pouchdb
npm http 200 http://192.168.1.100:4873/spark-md5
npm http 304 http://192.168.1.100:4873/through2
npm http 200 http://192.168.1.100:4873/levelup
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/js-extend
npm http 200 http://192.168.1.100:4873/vuvuzela
npm http request GET http://192.168.1.100:4873/d64
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http 200 http://192.168.1.100:4873/d64
npm http 200 http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/end-stream
npm http 200 http://192.168.1.100:4873/end-stream
npm http request GET http://192.168.1.100:4873/write-stream
npm http 200 http://192.168.1.100:4873/write-stream
npm http request GET http://192.168.1.100:4873/deferred-leveldown
npm http request GET http://192.168.1.100:4873/level-errors
npm http request GET http://192.168.1.100:4873/level-codec
npm http request GET http://192.168.1.100:4873/prr
npm http request GET http://192.168.1.100:4873/level-iterator-stream
npm http request GET http://192.168.1.100:4873/semver
npm http 200 http://192.168.1.100:4873/prr
npm http 200 http://192.168.1.100:4873/level-iterator-stream
npm http 200 http://192.168.1.100:4873/semver
npm http 200 http://192.168.1.100:4873/level-codec
npm http 200 http://192.168.1.100:4873/deferred-leveldown
npm http 200 http://192.168.1.100:4873/level-errors
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
npm http request GET http://192.168.1.100:4873/aws4
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/is-typedarray
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/caseless
npm http 200 http://192.168.1.100:4873/aws4
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 304 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/qs
npm http 200 http://192.168.1.100:4873/is-typedarray
npm http 200 http://192.168.1.100:4873/tough-cookie
npm WARN deprecated tough-cookie@2.2.2: ReDoS vulnerability parsing Set-Cookie https://nodesecurity.io/advisories/130
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 200 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/pinkie-promise
npm http 304 http://192.168.1.100:4873/chalk
npm http 200 http://192.168.1.100:4873/pinkie-promise
npm http 200 http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-function
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http 304 http://192.168.1.100:4873/jsonpointer
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
npm http request GET http://192.168.1.100:4873/sshpk
npm http request GET http://192.168.1.100:4873/jsprim
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
npm http request GET http://192.168.1.100:4873/dashdash
npm http request GET http://192.168.1.100:4873/getpass
npm http 304 http://192.168.1.100:4873/asn1
npm http 200 http://192.168.1.100:4873/getpass
npm http 200 http://192.168.1.100:4873/dashdash
npm http request GET http://192.168.1.100:4873/pull-stream
npm http 200 http://192.168.1.100:4873/pull-stream
npm http request GET http://192.168.1.100:4873/pull-core
npm http 200 http://192.168.1.100:4873/pull-core
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/readable-stream
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
npm http 200 http://192.168.1.100:4873/couchdb-objects
npm http 200 http://192.168.1.100:4873/couchdb-eval
npm http 200 http://192.168.1.100:4873/random-uuid-v4
npm http request GET http://192.168.1.100:4873/is-empty
npm http 200 http://192.168.1.100:4873/is-empty
npm http request GET http://192.168.1.100:4873/is-array
npm http request GET http://192.168.1.100:4873/pouchdb-extend
npm http request GET http://192.168.1.100:4873/pouchdb-upsert
npm http 200 http://192.168.1.100:4873/is-array
npm http 200 http://192.168.1.100:4873/pouchdb-extend
npm http 200 http://192.168.1.100:4873/pouchdb-upsert
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 304 http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/couchdb-render
npm http 304 http://192.168.1.100:4873/extend
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
npm http 304 http://192.168.1.100:4873/abstract-leveldown
npm http 200 http://192.168.1.100:4873/bindings
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
npm http 200 http://192.168.1.100:4873/propagate
npm http 200 http://192.168.1.100:4873/chai
npm http 200 http://192.168.1.100:4873/lodash
npm WARN deprecated lodash@2.4.1: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
npm http request GET http://192.168.1.100:4873/deep-eql
npm http request GET http://192.168.1.100:4873/assertion-error
npm http request GET http://192.168.1.100:4873/type-detect
npm http 200 http://192.168.1.100:4873/deep-eql
npm http 200 http://192.168.1.100:4873/assertion-error
npm http 200 http://192.168.1.100:4873/type-detect
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/ip
npm http 304 http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-http
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-leveldb
npm http request GET http://192.168.1.100:4873/pouchdb-core
npm http request GET http://192.168.1.100:4873/pouchdb-mapreduce
npm http request GET http://192.168.1.100:4873/pouchdb-replication
npm http 304 http://192.168.1.100:4873/pouchdb-mapreduce
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-http
npm http 304 http://192.168.1.100:4873/pouchdb-replication
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-leveldb
npm http 304 http://192.168.1.100:4873/pouchdb-core
npm http request GET http://192.168.1.100:4873/pouchdb-ajax
npm http request GET http://192.168.1.100:4873/pouchdb-binary-utils
npm http request GET http://192.168.1.100:4873/pouchdb-errors
npm http request GET http://192.168.1.100:4873/pouchdb-md5
npm http request GET http://192.168.1.100:4873/pouchdb-utils
npm http 304 http://192.168.1.100:4873/pouchdb-binary-utils
npm http 304 http://192.168.1.100:4873/pouchdb-md5
npm http 304 http://192.168.1.100:4873/pouchdb-errors
npm http 200 http://192.168.1.100:4873/pouchdb-utils
npm http 304 http://192.168.1.100:4873/pouchdb-ajax
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http 304 http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/pouchdb-adapter-leveldb-core
npm http request GET http://192.168.1.100:4873/leveldown
npm http 304 http://192.168.1.100:4873/pouchdb-adapter-leveldb-core
npm http 200 http://192.168.1.100:4873/leveldown
npm http request GET http://192.168.1.100:4873/nan
npm http request GET http://192.168.1.100:4873/prebuild
npm http 304 http://192.168.1.100:4873/nan
npm http 200 http://192.168.1.100:4873/prebuild
npm http request GET http://192.168.1.100:4873/github-from-package
npm http request GET http://192.168.1.100:4873/expand-template
npm http request GET http://192.168.1.100:4873/ghreleases
npm http request GET http://192.168.1.100:4873/rc
npm http request GET http://192.168.1.100:4873/pump
npm http request GET http://192.168.1.100:4873/node-gyp
npm http request GET http://192.168.1.100:4873/os-homedir
npm http request GET http://192.168.1.100:4873/npmlog
npm http request GET http://192.168.1.100:4873/node-ninja
npm http request GET http://192.168.1.100:4873/noop-logger
npm http request GET http://192.168.1.100:4873/tar-stream
npm http request GET http://192.168.1.100:4873/simple-get
npm http request GET http://192.168.1.100:4873/tar-fs
npm http 200 http://192.168.1.100:4873/pump
npm http 200 http://192.168.1.100:4873/rc
npm http 200 http://192.168.1.100:4873/github-from-package
npm http 200 http://192.168.1.100:4873/ghreleases
npm http 200 http://192.168.1.100:4873/os-homedir
npm http 200 http://192.168.1.100:4873/expand-template
npm http 200 http://192.168.1.100:4873/node-gyp
npm http 200 http://192.168.1.100:4873/npmlog
npm http 200 http://192.168.1.100:4873/tar-stream
npm http 200 http://192.168.1.100:4873/tar-fs
npm http 200 http://192.168.1.100:4873/node-ninja
npm http 200 http://192.168.1.100:4873/simple-get
npm http 200 http://192.168.1.100:4873/noop-logger
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/simple-mime
npm http request GET http://192.168.1.100:4873/ghutils
npm http request GET http://192.168.1.100:4873/ghrepos
npm http request GET http://192.168.1.100:4873/url-template
npm http 304 http://192.168.1.100:4873/after
npm http 200 http://192.168.1.100:4873/ghutils
npm http 200 http://192.168.1.100:4873/simple-mime
npm http 200 http://192.168.1.100:4873/ghrepos
npm http 200 http://192.168.1.100:4873/url-template
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
npm http request GET http://192.168.1.100:4873/tar
npm http request GET http://192.168.1.100:4873/nopt
npm http request GET http://192.168.1.100:4873/path-array
npm http request GET http://192.168.1.100:4873/osenv
npm http request GET http://192.168.1.100:4873/which
npm http 304 http://192.168.1.100:4873/fstream
npm http 200 http://192.168.1.100:4873/tar
npm http 200 http://192.168.1.100:4873/nopt
npm http 200 http://192.168.1.100:4873/osenv
npm http 200 http://192.168.1.100:4873/path-array
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
npm http request GET http://192.168.1.100:4873/lodash.pad
npm http request GET http://192.168.1.100:4873/lodash.padend
npm http request GET http://192.168.1.100:4873/lodash.padstart
npm http 200 http://192.168.1.100:4873/lodash.padstart
npm http 200 http://192.168.1.100:4873/has-unicode
npm http 200 http://192.168.1.100:4873/lodash.padend
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
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/http-signature
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
npm http 304 http://192.168.1.100:4873/deep-extend
npm http 304 http://192.168.1.100:4873/strip-json-comments
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
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http 304 http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/ltgt
npm http 304 http://192.168.1.100:4873/ltgt
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/pouchdb-promise
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
npm http request GET http://192.168.1.100:4873/samsam
npm http request GET http://192.168.1.100:4873/formatio
npm http request GET http://192.168.1.100:4873/util
npm http request GET http://192.168.1.100:4873/lolex
npm http 200 http://192.168.1.100:4873/util
npm http 200 http://192.168.1.100:4873/lolex
npm http 200 http://192.168.1.100:4873/formatio
npm http 200 http://192.168.1.100:4873/samsam
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
npm http 304 http://192.168.1.100:4873/component-bind
npm http 304 http://192.168.1.100:4873/engine.io-client
npm http 304 http://192.168.1.100:4873/component-emitter
npm http 304 http://192.168.1.100:4873/socket.io-parser
npm http 304 http://192.168.1.100:4873/object-component
npm http 304 http://192.168.1.100:4873/indexof
npm http 304 http://192.168.1.100:4873/has-binary
npm http 304 http://192.168.1.100:4873/to-array
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/parseuri
npm http 304 http://192.168.1.100:4873/backo2
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/parseqs
npm http request GET http://192.168.1.100:4873/ws
npm http fetch GET https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http 304 http://192.168.1.100:4873/engine.io-parser
npm http 304 http://192.168.1.100:4873/parseqs
npm http 304 http://192.168.1.100:4873/parsejson
npm http 200 http://192.168.1.100:4873/component-inherit
npm http 200 http://192.168.1.100:4873/has-cors
npm http 304 http://192.168.1.100:4873/ws
npm http fetch 200 https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/utf8
npm http 304 http://192.168.1.100:4873/base64-arraybuffer
npm http 304 http://192.168.1.100:4873/arraybuffer.slice
npm http 304 http://192.168.1.100:4873/utf8
npm http 304 http://192.168.1.100:4873/blob
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
npm http 304 http://192.168.1.100:4873/benchmark
npm http 304 http://192.168.1.100:4873/json3
npm http request GET http://192.168.1.100:4873/superagent
npm http 200 http://192.168.1.100:4873/superagent
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/formidable
npm http request GET http://192.168.1.100:4873/reduce-component
npm http request GET http://192.168.1.100:4873/cookiejar
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
npm http request GET http://192.168.1.100:4873/resumer
npm http request GET http://192.168.1.100:4873/object-inspect
npm http 304 http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/defined
npm http 200 http://192.168.1.100:4873/resumer
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
