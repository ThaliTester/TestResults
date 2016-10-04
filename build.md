#### Test (Fail) 86147834 Build Logs


```


```

```
Updating 0ac2938..40cdc94
Fast-forward
 readme.md                                       |  205 +++++++++++++++++++++++
 test/README.md                                  |   19 ++-
 thali/NextGeneration/thaliWifiInfrastructure.js |    2 +-
 3 files changed, 223 insertions(+), 3 deletions(-)

From https://github.com/thaliproject/Thali_CordovaPlugin
   0ac2938..40cdc94  master     -> origin/master
   e15a0bc..0d0f41a  vNext_yarong_417_812_chapko_898 -> origin/vNext_yarong_417_812_chapko_898

```

```
Your branch is up-to-date with 'origin/master'.
Branch vNext_yarong_417_812 set up to track remote branch vNext_yarong_417_812 from origin.
Already up-to-date.

Already on 'master'
Switched to a new branch 'vNext_yarong_417_812'
Note: checking out '0d0f41a'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at 0d0f41a... Merge remote-tracking branch 'origin/master' into vNext_yarong_417_812_chapko_898
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
│     └─┬ glob@7.1.0 
│       ├── fs.realpath@1.0.0 
│       ├─┬ inflight@1.0.5 
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
│ │ ├── esprima@2.7.3 
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
│ │ │ │ │ ├── once@1.4.0 
│ │ │ │ │ └── path-is-absolute@1.0.1 
│ │ │ │ ├── graceful-fs@4.1.9 
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
│ │ ├─┬ readable-stream@2.1.5 
│ │ │ └── isarray@1.0.0 
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
│ │ └─┬ readable-stream@2.0.6 
│ │   └── isarray@1.0.0 
│ ├── caseless@0.11.0 
│ ├─┬ combined-stream@1.0.5 
│ │ └── delayed-stream@1.0.0 
│ ├── extend@3.0.0 
│ ├─┬ form-data@1.0.1 
│ │ └─┬ async@2.0.1 
│ │   └── lodash@4.16.3 
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
> jx installCordovaPlugin.js

We believe we are in a clone of the GitHub Repo so we will not install Cordova dependencies

> thali@2.1.0 prepublish /Users/thali/Github/Thali_CordovaPlugin/thali
> jx install/prePublishThaliCordovaPlugin.js

/usr/local/lib/node_modules/thali -> /Users/thali/Github/Thali_CordovaPlugin/thali
install@0.0.1 /Users/thali/Github/Thali_CordovaPlugin/thali/install
├── bluebird@3.4.6 
├── end-with@1.0.2 
├── findit@2.0.0 
├─┬ fs-extra-promise@0.2.0 
│ ├── bluebird@2.11.0 
│ └─┬ fs-extra@0.21.0 
│   ├── graceful-fs@4.1.9 
│   ├── jsonfile@2.4.0 
│   └─┬ rimraf@2.5.4 
│     └─┬ glob@7.1.0 
│       ├── fs.realpath@1.0.0 
│       ├─┬ inflight@1.0.5 
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
├─┬ lie@3.0.4 
│ ├─┬ es3ify@0.2.2 
│ │ ├── esprima@2.7.3 
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
├── node-uuid@1.4.7 
├─┬ randomstring@1.1.5 
│ └── array-uniq@1.0.2 
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
│ ├─┬ form-data@1.0.1 
│ │ └─┬ async@2.0.1 
│ │   └── lodash@4.16.3 
│ ├─┬ har-validator@1.8.0 
│ │ ├── bluebird@2.11.0 
│ │ ├─┬ chalk@1.1.3 
│ │ │ ├── ansi-styles@2.2.1 
│ │ │ ├── escape-string-regexp@1.0.5 
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
  │ ├─┬ graceful-fs@3.0.11 
  │ │ └── natives@1.1.0 
  │ ├── inherits@2.0.3 
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
  └── setimmediate@1.0.5 

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
│ │ ├─┬ couchdb-calculate-session-id@1.1.0 
│ │ │ └── aproba@1.0.4 
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
│ ├─┬ duplexify@3.4.5 
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
│ │ ├── aws4@1.4.1 
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
│ │ └─┬ async@2.0.1 
│ │   └── lodash@4.16.3 
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
│ │ │ ├─┬ end-of-stream@1.0.0 
│ │ │ │ └── once@1.3.3 
│ │ │ ├─┬ readable-stream@2.1.5 
│ │ │ │ └── isarray@1.0.0 
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
│ │ │ └─┬ readable-stream@2.0.6 
│ │ │   └── isarray@1.0.0 
│ │ ├── caseless@0.11.0 
│ │ ├─┬ combined-stream@1.0.5 
│ │ │ └── delayed-stream@1.0.0 
│ │ ├── extend@3.0.0 
│ │ ├─┬ form-data@1.0.1 
│ │ │ └─┬ async@2.0.1 
│ │ │   └── lodash@4.16.3 
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

2016-10-04 22:55:10 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreateNativeListener.js'
2016-10-04 22:55:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js'
2016-10-04 22:55:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js'
2016-10-04 22:55:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
2016-10-04 22:55:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
2016-10-04 22:55:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testNativeMethod.js'
2016-10-04 22:55:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
2016-10-04 22:55:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBGenerator.js'
2016-10-04 22:55:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPromiseQueue.js'
2016-10-04 22:55:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testTests.js'
2016-10-04 22:55:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManager.js'
2016-10-04 22:55:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
2016-10-04 22:55:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js'
2016-10-04 22:55:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNative.js'
2016-10-04 22:55:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
2016-10-04 22:55:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
2016-10-04 22:55:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotification.js'
2016-10-04 22:55:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationAction.js'
2016-10-04 22:55:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
2016-10-04 22:55:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationClient.js'
2016-10-04 22:55:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationLocal.js'
2016-10-04 22:55:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationServer.js'
2016-10-04 22:55:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerAction.js'
2016-10-04 22:55:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerDictionary.js'
2016-10-04 22:55:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
2016-10-04 22:55:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
2016-10-04 22:55:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
2016-10-04 22:55:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
2016-10-04 22:55:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
2016-10-04 22:55:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
2016-10-04 22:55:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
2016-10-04 22:55:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
2016-10-04 22:55:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliTcpServersManager.js'
2016-10-04 22:55:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
2016-10-04 22:55:11 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testUsn.js'
2016-10-04 22:55:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-04 22:55:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-04 22:55:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-04 22:55:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-04 22:55:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
TAP version 13
# setup
# calling createNativeListener directly rejects
2016-10-04 22:55:11 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'listening 49826'
ok 1 Should throw
# teardown
# setup
# emits incomingConnectionState
2016-10-04 22:55:11 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'listening 49828'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new mux'
ok 2 initial connection state should be CONNECTED
2016-10-04 22:55:11 - DEBUG createNativeListener: 'incoming socket close'
ok 3 final connection state should be DISCONNECTED
# teardown
# setup
# emits routerPortConnectionFailed
2016-10-04 22:55:11 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'listening 49831'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new mux'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: ' Error: connect ECONNREFUSED
    at errnoException (net.js:837:11)
    at Object.afterConnect [as oncomplete] (net.js:829:19)'
ok 4 tried to connect to right port
ok 5 failed due to refused connection
ok 6 routerPortConnectionFailed is emitted
# teardown
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'mux close'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'incoming socket close'
# setup
# native server connections all up
2016-10-04 22:55:11 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'listening 49835'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new mux'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
ok 7 Send/recvd #1 should be equal length
ok 8 Send/recvd #1 should be same
ok 9 Send/recvd #2 should be equal length
ok 10 Send/recvd #2 should be same
ok 11 Should be exactly 2 client sockets
# teardown
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'mux close'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'incoming socket close'
# setup
# native server - closing incoming stream cleans outgoing socket
2016-10-04 22:55:11 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'listening 49840'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new mux'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
ok 12 socket shouldn't close until after stream
ok 13 incoming remains open
# teardown
2016-10-04 22:55:11 - DEBUG createNativeListener: 'mux close'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'incoming socket close'
# setup
# native server - closing incoming connection cleans outgoing socket
2016-10-04 22:55:11 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'listening 49844'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new mux'
ok 14 we should not have gotten an error
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'incoming socket close'
ok 15 socket shouldn't close until after incoming
ok 16 incoming is cleaned up
# teardown
# setup
# native server - closing outgoing socket cleans associated mux stream
2016-10-04 22:55:11 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'listening 49848'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new mux'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
ok 17 stream was closed
ok 18 incoming should survive
ok 19 mux should have no streams
# teardown
2016-10-04 22:55:11 - DEBUG createNativeListener: 'mux close'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'incoming socket close'
# setup
# native server - closing the whole server cleans everything up
2016-10-04 22:55:11 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'listening 49852'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new mux'
ok 20 we should not have gotten an error
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
ok 21 Buffers are identical
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'mux close'
ok 22 native server is nulled out
ok 23 native server should be closed
ok 24 incoming has been removed
ok 25 Incoming should be done
ok 26 The mux object should be closed
ok 27 The mux stream should be closed
2016-10-04 22:55:11 - DEBUG createNativeListener: 'incoming socket close'
# teardown
# setup
# native server - we can get a ton of connections and data through and still clean up the server completely
2016-10-04 22:55:11 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'listening 49856'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new mux'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new mux'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new mux'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new mux'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new mux'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new mux'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new mux'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new mux'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new mux'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new mux'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:11 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'mux close'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'mux close'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'mux close'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'mux close'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'mux close'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'mux close'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'mux close'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'mux close'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'mux close'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:11 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'mux close'
ok 28 native server is nulled out
ok 29 native server should be closed
ok 30 incoming has been removed
2016-10-04 22:55:12 - DEBUG createNativeListener: 'incoming socket close'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'incoming socket close'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'incoming socket close'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'incoming socket close'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'incoming socket close'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'incoming socket close'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'incoming socket close'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'incoming socket close'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'incoming socket close'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'incoming socket close'
# teardown
# setup
# native server - simulate mux failure, make sure everything is cleaned up
2016-10-04 22:55:12 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'listening 49908'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'new mux'
ok 31 we should not have gotten an error
2016-10-04 22:55:12 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:12 - DEBUG createNativeListener: 'new outgoing socket'
ok 32 Buffers are identical
2016-10-04 22:55:12 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'mux close'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'incoming socket close'
ok 33 server should be fine
ok 34 server should be open
ok 35 incoming has been removed
ok 36 The mux object should be closed
ok 37 The mux stream should be closed
# teardown
# setup
# native server - timing out the incoming connection cleans everything up
2016-10-04 22:55:12 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'listening 49912'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'new mux'
ok 38 we should not have gotten an error
2016-10-04 22:55:12 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:12 - DEBUG createNativeListener: 'new outgoing socket'
ok 39 Buffers are identical
2016-10-04 22:55:12 - DEBUG createNativeListener: 'incoming socket timeout'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'mux close'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'incoming socket close'
ok 40 server should be fine
ok 41 server should be open
ok 42 incoming has been removed
ok 43 The mux object should be closed
ok 44 The mux stream should be closed
# teardown
# setup
# calling createPeerListener without calling start produces error
2016-10-04 22:55:12 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'listening 49917'
# teardown
# setup
# calling createPeerListener after calling stop produces error
2016-10-04 22:55:12 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'listening 49920'
# teardown
# setup
# can call createPeerListener (pleaseConnect === false)
2016-10-04 22:55:12 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'listening 49923'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'listening 49924'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 45 port must be in range
# teardown
# setup
# calling createPeerListener (pleaseConnect === true) with unknown peer is error
2016-10-04 22:55:12 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'listening 49927'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'listening 49928'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'first connection'
2016-10-04 22:55:12 - WARN createPeerListener: ' Error: Unknown Peer
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
2016-10-04 22:55:12 - DEBUG createPeerListener: 'failedConnection'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'Recreating listener'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'createPeerListener creating new server'
ok 46 should get error
2016-10-04 22:55:12 - DEBUG createPeerListener: 'listening 49929'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'pleaseConnect= false'
# teardown
# setup
# calling createPeerListener twice with same peerIdentifier should return the same port
2016-10-04 22:55:12 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'listening 49932'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'listening 49933'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 47 port values should be the same
# teardown
# setup
# createPeerListener - closing connection to native listener closes everything and triggers new listener
2016-10-04 22:55:12 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'listening 49936'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'listening 49937'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'first connection'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'forward connection'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'new mux'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:12 - DEBUG createNativeListener: 'new outgoing socket'
ok 48 Data should be of same length and content
2016-10-04 22:55:12 - DEBUG createNativeListener: 'incoming socket close'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'Recreating listener'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'listening 49942'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 49 same peer ID
ok 50 different ports
2016-10-04 22:55:12 - DEBUG createNativeListener: 'stream close:'
# teardown
# setup
# createPeerListener - closing mux closes listener and triggers a new listener
2016-10-04 22:55:12 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'listening 49945'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'listening 49946'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'first connection'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'forward connection'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'new mux'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:12 - DEBUG createNativeListener: 'new outgoing socket'
ok 51 Data should be of same length and content
2016-10-04 22:55:12 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'incoming socket close'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'Recreating listener'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'listening 49951'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 52 same peer ID
ok 53 different ports
# teardown
# setup
# peerListener - forwardConnection, pleaseConnect === true - no native server
2016-10-04 22:55:12 - DEBUG createNativeListener: 'creating native server'
ok 54 Can call startUpdateAdvertisingAndListening without error
ok 55 Can call startListeningForAdvertisements without error
2016-10-04 22:55:12 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'listening 49954'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'listening 49955'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'first connection'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'forward connection'
2016-10-04 22:55:12 - WARN createPeerListener: ' Error: connect ECONNREFUSED
    at errnoException (net.js:837:11)
    at Object.afterConnect [as oncomplete] (net.js:829:19)'
ok 56 reason should be as expected
2016-10-04 22:55:12 - DEBUG createPeerListener: 'Recreating listener'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'listening 49957'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'pleaseConnect= false'
# teardown
# setup
# peerListener - forwardConnection, pleaseConnect === false - no native server
2016-10-04 22:55:12 - DEBUG createNativeListener: 'creating native server'
ok 57 Can call startUpdateAdvertisingAndListening without error
ok 58 Can call startListeningForAdvertisements without error
2016-10-04 22:55:12 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'listening 49960'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'listening 49961'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 59 peerPort should not be nativePort
2016-10-04 22:55:12 - DEBUG createPeerListener: 'first connection'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'forward connection'
2016-10-04 22:55:12 - WARN createPeerListener: ' Error: connect ECONNREFUSED
    at errnoException (net.js:837:11)
    at Object.afterConnect [as oncomplete] (net.js:829:19)'
ok 60 Should not get event until connection is made
ok 61 reason should be as expected
2016-10-04 22:55:12 - DEBUG createPeerListener: 'Recreating listener'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'failed incoming connection because of mux promise failure - undefined'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'listening 49964'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'pleaseConnect= false'
# teardown
# setup
# peerListener - forwardConnection, pleaseConnect === true - with native server
2016-10-04 22:55:12 - DEBUG createNativeListener: 'creating native server'
ok 62 Can call startUpdateAdvertisingAndListening without error
ok 63 Can call startListeningForAdvertisements without error
2016-10-04 22:55:12 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'listening 49967'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'listening 49968'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'first connection'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'forward connection'
ok 64 Should get spontaneous connection
ok 65 peerPort != nativePort
# teardown
# setup
# peerListener - forwardConnection, pleaseConnect === false - with native server
2016-10-04 22:55:12 - DEBUG createNativeListener: 'creating native server'
ok 66 Can call startUpdateAdvertisingAndListening without error
ok 67 Can call startListeningForAdvertisements without error
2016-10-04 22:55:12 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'listening 49972'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'listening 49973'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 68 peerPort != nativePort
2016-10-04 22:55:12 - DEBUG createPeerListener: 'first connection'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'forward connection'
ok 69 Should not get unexpected connection
# teardown
# setup
# peerListener - forwardConnection, pleaseConnect === false - with native server and data transfer
2016-10-04 22:55:12 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'listening 49978'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'listening 49979'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'first connection'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'forward connection'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'new mux'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:12 - DEBUG createNativeListener: 'new outgoing socket'
ok 70 Data should be of same length and content
ok 71 Data should be of same length and content
# teardown
2016-10-04 22:55:12 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'mux close'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'incoming socket close'
2016-10-04 22:55:12 - WARN createPeerListener: ' Error: read ECONNRESET
    at errnoException (net.js:837:11)
    at TCP.onread (net.js:519:19)'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'Got error on outgoing to native - Error: read ECONNRESET'
# setup
# createPeerListener is idempotent
2016-10-04 22:55:12 - DEBUG createNativeListener: 'creating native server'
ok 72 Can call startUpdateAdvertisingAndListening without error
ok 73 Can call startListeningForAdvertisements without error
2016-10-04 22:55:12 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'listening 49985'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'listening 49986'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 74 Second call to existing peerListener returns existing port
# teardown
# setup
# createPeerListener - pleaseConnect === true, failed connection rejects promise
2016-10-04 22:55:12 - DEBUG createNativeListener: 'creating native server'
ok 75 Can call startUpdateAdvertisingAndListening without error
ok 76 Can call startListeningForAdvertisements without error
2016-10-04 22:55:12 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'listening 49989'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'listening 49990'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'first connection'
2016-10-04 22:55:12 - WARN createPeerListener: ' Error: a nasty error
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
2016-10-04 22:55:12 - DEBUG createPeerListener: 'failedConnection'
ok 77 got our failed connection
2016-10-04 22:55:12 - DEBUG createPeerListener: 'Recreating listener'
ok 78 failed connection should reject with error
2016-10-04 22:55:12 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'listening 49991'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'pleaseConnect= false'
# teardown
# setup
# createPeerListener - pleaseConnect === true, connection resolves promise
2016-10-04 22:55:12 - DEBUG createNativeListener: 'creating native server'
ok 79 Can call startUpdateAdvertisingAndListening without error
ok 80 Can call startListeningForAdvertisements without error
2016-10-04 22:55:12 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'listening 49994'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'listening 49995'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'first connection'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'forward connection'
ok 81 Should get spontaneous connection
ok 82 promise should resolve
# teardown
# setup
# peerListener - reverseConnection, pleaseConnect === true
2016-10-04 22:55:12 - DEBUG createNativeListener: 'creating native server'
ok 83 Can call startUpdateAdvertisingAndListening without error
ok 84 Can call startListeningForAdvertisements without error
2016-10-04 22:55:12 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'listening 49999'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'listening 50000'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'first connection'
2016-10-04 22:55:12 - WARN createPeerListener: 'was expecting a forward connection to be made'
ok 85 reason should be as expected
2016-10-04 22:55:12 - DEBUG createPeerListener: 'Recreating listener'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'listening 50001'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'pleaseConnect= false'
# teardown
# setup
# peerListener - reverseConnection, pleaseConnect === false - no incoming
2016-10-04 22:55:12 - DEBUG createNativeListener: 'creating native server'
ok 86 Can call startUpdateAdvertisingAndListening without error
ok 87 Can call startListeningForAdvertisements without error
2016-10-04 22:55:12 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'listening 50004'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'listening 50005'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 88 peerPort should not be nativePort
2016-10-04 22:55:12 - DEBUG createPeerListener: 'first connection'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'looking up mux for client port:  0'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'timed out waiting for incoming connection'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'reverse connection'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'looking up mux for client port:  0'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'no mux found'
ok 89 should not get event until connection is made
ok 90 reason should be as expected
2016-10-04 22:55:12 - DEBUG createPeerListener: 'Recreating listener'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'failed incoming connection because of mux promise failure - AssertionError: server._mux must exist by now'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'listening 50007'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'pleaseConnect= false'
# teardown
# setup
# peerListener - reverseConnection, pleaseConnect === false - with incoming
2016-10-04 22:55:12 - DEBUG createNativeListener: 'creating native server'
ok 91 Can call startUpdateAdvertisingAndListening without error
ok 92 Can call startListeningForAdvertisements without error
2016-10-04 22:55:12 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'listening 50010'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'listening 50011'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'first connection'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'new mux'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'looking up mux for client port:  50013'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'reverse connection'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'looking up mux for client port:  50013'
ok 93 sent and received should be the same
# teardown
2016-10-04 22:55:12 - DEBUG createNativeListener: 'mux close'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'incoming socket close'
# setup
# peerListener - reverseConnection, pleaseConnect === false - no server
2016-10-04 22:55:12 - DEBUG createNativeListener: 'creating native server'
ok 94 Can call startUpdateAdvertisingAndListening without error
ok 95 Can call startListeningForAdvertisements without error
2016-10-04 22:55:12 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'listening 50016'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'listening 50017'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'first connection'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'new mux'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'looking up mux for client port:  50019'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'reverse connection'
2016-10-04 22:55:12 - DEBUG createPeerListener: 'looking up mux for client port:  50019'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:12 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:55:12 - DEBUG createNativeListener: ' Error: connect ECONNREFUSED
    at errnoException (net.js:837:11)
    at Object.afterConnect [as oncomplete] (net.js:829:19)'
ok 96 should get routerPortConnectionFailed
2016-10-04 22:55:12 - DEBUG createNativeListener: 'stream close:'
# teardown
2016-10-04 22:55:12 - DEBUG createNativeListener: 'mux close'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'incoming socket close'
# setup
# createPeerListener - ask for new peer when we are at maximum and make sure we remove the right existing listener
2016-10-04 22:55:12 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'listening 50023'
# teardown
# setup
# createPeerListener - ask for a new peer when we are not at maximum peers and make sure we do not remove any existing listeners
2016-10-04 22:55:12 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'listening 50026'
# teardown
# setup
# createPeerListener - pleaseConnect = false - test timeout
2016-10-04 22:55:12 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'listening 50029'
# teardown
# setup
# createPeerListener - pleaseConnect = true - test timeout
2016-10-04 22:55:12 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'listening 50032'
# teardown
# setup
# createPeerListener - forward connection - wrong serverPort
2016-10-04 22:55:12 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'listening 50035'
# teardown
# setup
# createPeerListener - forward connection - wrong clientPort
2016-10-04 22:55:12 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'listening 50038'
# teardown
# setup
# createPeerListener - please connect = false, multiple connections out
2016-10-04 22:55:12 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'listening 50041'
# teardown
# setup
# createPeerListener - please connect = false, multiple bi-directional connections
2016-10-04 22:55:12 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'listening 50044'
# teardown
# setup
# createPeerListener - multiple parallel calls
2016-10-04 22:55:12 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:12 - DEBUG createNativeListener: 'listening 50047'
# teardown
# setup
# #_doImmediateSeqUpdate - server is not there
2016-10-04 22:55:12 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
ok 97 Got right error
# teardown
# setup
# #_doImmediateSeqUpdate - server accepts & closes connection
2016-10-04 22:55:12 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
ok 98 Got socket hang up
# teardown
# setup
# #_doImmediateSeqUpdate - server always returns 500
2016-10-04 22:55:12 - DEBUG localSeqManager: 'Got an error trying to update seq []'
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
2016-10-04 22:55:12 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
ok 110 Our rev is old so we should fail
# teardown
# setup
# #_doImmediateSeqUpdate - fail if stop is called
ok 111 confirm stop caused failure
# teardown
# setup
# #_doImmediateSeqUpdate - stop after get but before put fails right
2016-10-04 22:55:12 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
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
2016-10-04 22:55:12 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
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
2016-10-04 22:55:18 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
2016-10-04 22:55:18 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
2016-10-04 22:55:18 - DEBUG thaliManager: 'creating express pouchdb instance'
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
2016-10-04 22:55:18 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-10-04 22:55:18 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-10-04 22:55:18 - DEBUG thaliManager: 'starting ThaliMobile'
2016-10-04 22:55:18 - DEBUG thaliMobileNativeWrapper: 'listening 50123'
2016-10-04 22:55:18 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:18 - DEBUG createNativeListener: 'listening 50124'
2016-10-04 22:55:18 - DEBUG thaliManager: 'start listening for advertisements'
2016-10-04 22:55:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-04 22:55:18 - DEBUG thaliManager: 'start update advertising and listening'
2016-10-04 22:55:18 - DEBUG thaliWifiInfrastructure: 'listening 50125'
2016-10-04 22:55:18 - DEBUG thaliWifiInfrastructure: 'listening 50127'
2016-10-04 22:55:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-10-04 22:55:18 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
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
2016-10-04 22:55:18 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-10-04 22:55:18 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-10-04 22:55:18 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-10-04 22:55:18 - DEBUG thaliManager: 'stopping advertising and listening'
2016-10-04 22:55:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-04 22:55:18 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-10-04 22:55:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-10-04 22:55:18 - DEBUG thaliManager: 'stopping ThaliMobile'
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
2016-10-04 22:55:18 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
2016-10-04 22:55:18 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
2016-10-04 22:55:18 - DEBUG thaliManager: 'creating express pouchdb instance'
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
2016-10-04 22:55:18 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-10-04 22:55:18 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-10-04 22:55:18 - DEBUG thaliManager: 'starting ThaliMobile'
2016-10-04 22:55:18 - DEBUG thaliMobileNativeWrapper: 'listening 50128'
2016-10-04 22:55:18 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:18 - DEBUG createNativeListener: 'listening 50129'
2016-10-04 22:55:18 - DEBUG thaliManager: 'start listening for advertisements'
2016-10-04 22:55:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-04 22:55:18 - DEBUG thaliManager: 'start update advertising and listening'
2016-10-04 22:55:18 - DEBUG thaliWifiInfrastructure: 'listening 50130'
2016-10-04 22:55:18 - DEBUG thaliWifiInfrastructure: 'listening 50132'
2016-10-04 22:55:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-10-04 22:55:18 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
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
2016-10-04 22:55:18 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-10-04 22:55:18 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-10-04 22:55:18 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-10-04 22:55:18 - DEBUG thaliManager: 'stopping advertising and listening'
2016-10-04 22:55:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-04 22:55:18 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-10-04 22:55:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-10-04 22:55:18 - DEBUG thaliManager: 'stopping ThaliMobile'
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
2016-10-04 22:55:18 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-10-04 22:55:18 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-10-04 22:55:18 - DEBUG thaliManager: 'starting ThaliMobile'
2016-10-04 22:55:18 - DEBUG thaliMobileNativeWrapper: 'listening 50133'
2016-10-04 22:55:18 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:18 - DEBUG createNativeListener: 'listening 50134'
2016-10-04 22:55:18 - DEBUG thaliManager: 'start listening for advertisements'
2016-10-04 22:55:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-04 22:55:18 - DEBUG thaliManager: 'start update advertising and listening'
2016-10-04 22:55:18 - DEBUG thaliWifiInfrastructure: 'listening 50135'
2016-10-04 22:55:18 - DEBUG thaliWifiInfrastructure: 'listening 50137'
2016-10-04 22:55:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-10-04 22:55:18 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
2016-10-04 22:55:18 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-10-04 22:55:18 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-10-04 22:55:18 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-10-04 22:55:18 - DEBUG thaliManager: 'stopping advertising and listening'
2016-10-04 22:55:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-04 22:55:18 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-10-04 22:55:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-10-04 22:55:18 - DEBUG thaliManager: 'stopping ThaliMobile'
2016-10-04 22:55:18 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-10-04 22:55:18 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-10-04 22:55:18 - DEBUG thaliManager: 'starting ThaliMobile'
2016-10-04 22:55:18 - DEBUG thaliMobileNativeWrapper: 'listening 50138'
2016-10-04 22:55:18 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:18 - DEBUG createNativeListener: 'listening 50139'
2016-10-04 22:55:18 - DEBUG thaliManager: 'start listening for advertisements'
2016-10-04 22:55:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-04 22:55:18 - DEBUG thaliManager: 'start update advertising and listening'
2016-10-04 22:55:18 - DEBUG thaliWifiInfrastructure: 'listening 50140'
2016-10-04 22:55:18 - DEBUG thaliWifiInfrastructure: 'listening 50142'
2016-10-04 22:55:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-10-04 22:55:18 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
2016-10-04 22:55:18 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-10-04 22:55:18 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-10-04 22:55:18 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-10-04 22:55:18 - DEBUG thaliManager: 'stopping advertising and listening'
2016-10-04 22:55:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-04 22:55:18 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-10-04 22:55:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-10-04 22:55:18 - DEBUG thaliManager: 'stopping ThaliMobile'
2016-10-04 22:55:18 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-10-04 22:55:18 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-10-04 22:55:18 - DEBUG thaliManager: 'starting ThaliMobile'
2016-10-04 22:55:18 - DEBUG thaliMobileNativeWrapper: 'listening 50143'
2016-10-04 22:55:18 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:18 - DEBUG createNativeListener: 'listening 50144'
2016-10-04 22:55:18 - DEBUG thaliManager: 'start listening for advertisements'
2016-10-04 22:55:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-04 22:55:18 - DEBUG thaliManager: 'start update advertising and listening'
2016-10-04 22:55:18 - DEBUG thaliWifiInfrastructure: 'listening 50145'
2016-10-04 22:55:18 - DEBUG thaliWifiInfrastructure: 'listening 50147'
2016-10-04 22:55:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-10-04 22:55:18 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
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
2016-10-04 22:55:18 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-10-04 22:55:18 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-10-04 22:55:18 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-10-04 22:55:18 - DEBUG thaliManager: 'stopping advertising and listening'
2016-10-04 22:55:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-04 22:55:18 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-10-04 22:55:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-10-04 22:55:18 - DEBUG thaliManager: 'stopping ThaliMobile'
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
2016-10-04 22:55:18 - DEBUG thaliMobileNativeWrapper: 'listening 50148'
2016-10-04 22:55:18 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:18 - DEBUG createNativeListener: 'listening 50149'
ok 295 error should be null
ok 296 error should be null
ok 297 error should be null
ok 298 error should be null
# teardown
ok 299 error should be null
ok 300 error should be null
# setup
# should be able to call #startListeningForAdvertisements many times
2016-10-04 22:55:18 - DEBUG thaliMobileNativeWrapper: 'listening 50150'
2016-10-04 22:55:18 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:18 - DEBUG createNativeListener: 'listening 50151'
2016-10-04 22:55:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 301 error should be null
ok 302 error should be null
ok 303 error should be null
ok 304 error should be null
# teardown
2016-10-04 22:55:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-10-04 22:55:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 305 error should be null
ok 306 error should be null
# setup
# should be able to call #startUpdateAdvertisingAndListening many times
2016-10-04 22:55:18 - DEBUG thaliMobileNativeWrapper: 'listening 50152'
2016-10-04 22:55:18 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:18 - DEBUG createNativeListener: 'listening 50153'
2016-10-04 22:55:18 - DEBUG thaliWifiInfrastructure: 'listening 50154'
2016-10-04 22:55:18 - DEBUG thaliWifiInfrastructure: 'listening 50156'
2016-10-04 22:55:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 307 error should be null
ok 308 error should be null
ok 309 error should be null
ok 310 error should be null
# teardown
2016-10-04 22:55:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-10-04 22:55:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 311 error should be null
ok 312 error should be null
# setup
# should be able to call #stopAdvertisingAndListening many times
2016-10-04 22:55:18 - DEBUG thaliMobileNativeWrapper: 'listening 50157'
2016-10-04 22:55:18 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:18 - DEBUG createNativeListener: 'listening 50158'
ok 313 error should be null
ok 314 error should be null
ok 315 error should be null
ok 316 error should be null
# teardown
ok 317 error should be null
ok 318 error should be null
# setup
# #start should fail if called twice in a row
2016-10-04 22:55:18 - DEBUG thaliMobileNativeWrapper: 'listening 50159'
2016-10-04 22:55:18 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:18 - DEBUG createNativeListener: 'listening 50160'
ok 319 first call should succeed
ok 320 first call should succeed
ok 321 specific error should be returned
# teardown
ok 322 error should be null
ok 323 error should be null
# setup
# does not emit duplicate discoveryAdvertisingStateUpdate
2016-10-04 22:55:18 - DEBUG thaliMobileNativeWrapper: 'listening 50161'
2016-10-04 22:55:18 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:18 - DEBUG createNativeListener: 'listening 50162'
2016-10-04 22:55:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-04 22:55:18 - DEBUG thaliWifiInfrastructure: 'listening 50163'
2016-10-04 22:55:18 - DEBUG thaliWifiInfrastructure: 'listening 50165'
2016-10-04 22:55:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-10-04 22:55:18 - INFO thaliMobile: 'Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":false,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}'
2016-10-04 22:55:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 324 called only once
ok 325 discovery state matches
ok 326 advertising state matches
2016-10-04 22:55:18 - INFO thaliMobile: 'Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":false,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}'
2016-10-04 22:55:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
# teardown
2016-10-04 22:55:18 - INFO thaliMobile: 'Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}'
2016-10-04 22:55:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-10-04 22:55:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-10-04 22:55:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-04 22:55:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 327 error should be null
ok 328 error should be null
# setup
# does not send duplicate availability changes
ok 329 should be called once
ok 330 should not have been called more than once
# teardown
ok 331 error should be null
ok 332 error should be null
# setup
# can get the network status
ok 333 network status should have certain non-empty properties
# teardown
ok 334 error should be null
ok 335 error should be null
# setup
# wifi peer is marked unavailable if announcements stop
2016-10-04 22:55:18 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined'
ok 336 host address should match
ok 337 port should match
ok 338 host address should be null
ok 339 port should should be null
# teardown
2016-10-04 22:55:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 340 error should be null
ok 341 error should be null
# setup
# network changes emitted correctly
2016-10-04 22:55:21 - DEBUG thaliMobileNativeWrapper: 'listening 50166'
2016-10-04 22:55:21 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:21 - DEBUG createNativeListener: 'listening 50167'
2016-10-04 22:55:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
ok 342 wifi is off
2016-10-04 22:55:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
ok 343 wifi is on
# teardown
ok 344 error should be null
ok 345 error should be null
# setup
# network changes not emitted in stopped state
ok 346 event was not emitted
2016-10-04 22:55:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-04 22:55:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
# teardown
ok 347 error should be null
ok 348 error should be null
# setup
# calls correct starts when network changes
2016-10-04 22:55:21 - DEBUG thaliMobileNativeWrapper: 'listening 50168'
2016-10-04 22:55:21 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:21 - DEBUG createNativeListener: 'listening 50169'
2016-10-04 22:55:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-04 22:55:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 349 specific error expected
2016-10-04 22:55:21 - DEBUG thaliWifiInfrastructure: 'listening 50171'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
ok 350 specific error expected
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-04 22:55:22 - INFO thaliMobile: 'Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":true,"advertisingActive":true}'
2016-10-04 22:55:22 - DEBUG thaliWifiInfrastructure: 'listening 50172'
ok 351 startListeningForAdvertisements should have been called
ok 352 startUpdateAdvertisingAndListening should have been called
# teardown
2016-10-04 22:55:22 - INFO thaliMobile: 'Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}'
2016-10-04 22:55:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-10-04 22:55:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 353 error should be null
ok 354 error should be null
# setup
# peer is marked unavailable if port number changes
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'listening 50173'
2016-10-04 22:55:22 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:22 - DEBUG createNativeListener: 'listening 50174'
ok 355 peer should have a non-empty identifier
ok 356 peer should have a non-empty host address
ok 357 peer should have port number
ok 358 peer should have suggested timeout
ok 359 peer should have a connection type
ok 360 connection type should match one of the pre-defined types
ok 361 peer should have a non-empty identifier
ok 362 host address should be null
ok 363 port number should be null
ok 364 peer should have suggested timeout
ok 365 peer should have a connection type
ok 366 connection type should match one of the pre-defined types
ok 367 port number must match
ok 368 peer should have a non-empty identifier
ok 369 peer should have a non-empty host address
ok 370 peer should have port number
ok 371 peer should have suggested timeout
ok 372 peer should have a connection type
ok 373 connection type should match one of the pre-defined types
# teardown
ok 374 error should be null
ok 375 error should be null
# setup
# when network connection is lost a peer should be marked unavailable
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'listening 50175'
2016-10-04 22:55:22 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:22 - DEBUG createNativeListener: 'listening 50176'
2016-10-04 22:55:22 - INFO testUtils: 'Toggling radios to: false'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
ok 376 peer should have a non-empty identifier
ok 377 host address should be null
ok 378 port number should be null
ok 379 peer should have suggested timeout
ok 380 peer should have a connection type
ok 381 connection type should match one of the pre-defined types
2016-10-04 22:55:22 - INFO testUtils: 'Toggling radios to: true'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
# teardown
ok 382 error should be null
ok 383 error should be null
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
# setup
# Can call start/stopListeningForAdvertisements
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 384 Can call startListeningForAdvertisements without error
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 385 Can call stopListeningForAdvertisements without error
# teardown
ok 386 Should be able to call stopListeningForAdvertisements in teardown
ok 387 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Calling startListeningForAdvertisements twice is NOT an error
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 388 Can call startListeningForAdvertisements without error
ok 389 Can call startListeningForAdvertisements twice without error
# teardown
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 390 Should be able to call stopListeningForAdvertisements in teardown
ok 391 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Calling stopListeningForAdvertisements without calling start is NOT an error
ok 392 Can call stopListeningForAdvertisements without error
ok 393 Can call stopListeningForAdvertisements without error
# teardown
ok 394 Should be able to call stopListeningForAdvertisements in teardown
ok 395 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Can call start/stopUpdateAdvertisingAndListening
2016-10-04 22:55:22 - DEBUG thaliWifiInfrastructure: 'listening 50178'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 396 Can call startUpdateAdvertisingAndListening without error
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 397 Can call stopAdvertisingAndListening without error
# teardown
ok 398 Should be able to call stopListeningForAdvertisements in teardown
ok 399 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Calling startUpdateAdvertisingAndListening twice is NOT an error
2016-10-04 22:55:22 - DEBUG thaliWifiInfrastructure: 'listening 50180'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 400 Can call startUpdateAdvertisingAndListening without error
ok 401 Can call startUpdateAdvertisingAndListening twice without error
# teardown
ok 402 Should be able to call stopListeningForAdvertisements in teardown
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 403 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
ok 404 Can call startUpdateAdvertisingAndListening without error
ok 405 Can call stopAdvertisingAndListening without error
# teardown
ok 406 Should be able to call stopListeningForAdvertisements in teardown
ok 407 Should be able to call stopAdvertisingAndListening in teardown
# setup
# cannot call connect when start listening for advertisements is not active
ok 408 got right error
# teardown
ok 409 Should be able to call stopListeningForAdvertisements in teardown
ok 410 Should be able to call stopAdvertisingAndListening in teardown
# setup
# #startListeningForAdvertisements should fail if start not called
ok 411 specific error should be returned
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 412 must be stopped
# setup
# #startUpdateAdvertisingAndListening should fail if start not called
ok 413 specific error should be returned
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 414 must be stopped
# setup
# should be able to call #stopListeningForAdvertisements many times
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'listening 50181'
2016-10-04 22:55:22 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:22 - DEBUG createNativeListener: 'listening 50182'
ok 415 no errors
ok 416 still no errors
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 417 must be stopped
# setup
# should be able to call #startListeningForAdvertisements many times
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'listening 50183'
2016-10-04 22:55:22 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:22 - DEBUG createNativeListener: 'listening 50184'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 418 no errors
ok 419 still no errors
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 420 must be stopped
# setup
# should be able to call #startUpdateAdvertisingAndListening many times
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'listening 50185'
2016-10-04 22:55:22 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:22 - DEBUG createNativeListener: 'listening 50186'
2016-10-04 22:55:22 - DEBUG thaliWifiInfrastructure: 'listening 50188'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 421 no errors
ok 422 still no errors
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 423 must be stopped
# setup
# should be able to call #stopAdvertisingAndListening many times
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'listening 50189'
2016-10-04 22:55:22 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:22 - DEBUG createNativeListener: 'listening 50190'
ok 424 no errors
ok 425 still no errors
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 426 must be stopped
# setup
# can get the network status before starting
ok 427 network status should have certain non-empty properties
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 428 must be stopped
# setup
# error returned with bad router
2016-10-04 22:55:22 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 429 specific error expected
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 430 must be stopped
# setup
# all services are stopped when we call stop
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'listening 50191'
2016-10-04 22:55:22 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:22 - DEBUG createNativeListener: 'listening 50192'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-04 22:55:22 - DEBUG thaliWifiInfrastructure: 'listening 50194'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
ok 431 connection to servers manager should succeed after starting
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-04 22:55:22 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:55:22 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:55:22 - DEBUG createNativeListener: 'new mux'
ok 432 connection to router server should succeed after starting
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-10-04 22:55:22 - DEBUG createNativeListener: 'mux close'
ok 433 is stopped after calling stop
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-04 22:55:22 - DEBUG createNativeListener: 'incoming socket close'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
ok 434 connection to servers manager should fail after stopping
ok 435 connection to router server should fail after stopping
# teardown
ok 436 must be stopped
# setup
# make sure terminateConnection is properly hooked up
ok 437 called with right arguments
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 438 must be stopped
# setup
# make sure terminateListener is properly hooked up
ok 439 called with right arguments
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 440 must be stopped
# setup
# make sure we actually call kill connections properly
ok 441 specific error expected
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 442 must be stopped
# setup
# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'listening 50199'
2016-10-04 22:55:22 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:22 - DEBUG createNativeListener: 'listening 50200'
2016-10-04 22:55:22 - INFO thaliMobileNativeWrapper: 'routerPortConnectionFailed - {"routerPort":50199,"error":{}}'
ok 443 failure reason is as expected
ok 444 error description is as expected
ok 445 must be stopped
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 446 must be stopped
# setup
# We repeat failedConnection event when we get it from thaliTcpServersManager
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'listening 50201'
2016-10-04 22:55:22 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:22 - DEBUG createNativeListener: 'listening 50202'
ok 447 peerIdentifier matches
ok 448 error description matches
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 449 must be stopped
# setup
# can do HTTP requests between peers without coordinator
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'listening 50203'
2016-10-04 22:55:22 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:22 - DEBUG createNativeListener: 'listening 50204'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-04 22:55:22 - DEBUG thaliWifiInfrastructure: 'listening 50206'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-10-04 22:55:22 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-04 22:55:22 - DEBUG createPeerListener: 'listening 50207'
2016-10-04 22:55:22 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-10-04 22:55:22 - DEBUG testUtils: 'We got a peer {"peerIdentifier":"foo","portNumber":50207,"hostAddress":"127.0.0.1"}'
2016-10-04 22:55:22 - WARN testUtils: 'Retry count for getSamePeerWithRetry is 1'
2016-10-04 22:55:22 - DEBUG createPeerListener: 'first connection'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-04 22:55:22 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:55:22 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:55:22 - DEBUG createNativeListener: 'new mux'
2016-10-04 22:55:22 - DEBUG wifiBasedNativeMock: 'proxy socket connected'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
2016-10-04 22:55:22 - DEBUG createPeerListener: 'forward connection'
2016-10-04 22:55:22 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:55:22 - DEBUG createNativeListener: 'new outgoing socket'
ok 450 Should only get expected id
ok 451 response body should match testData
# teardown
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-10-04 22:55:22 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:55:22 - DEBUG createNativeListener: 'mux close'
ok 452 must be stopped
2016-10-04 22:55:22 - DEBUG createNativeListener: 'incoming socket close'
# setup
# make sure bad PSK connections fail
ok 453 FIX ME, PLEASE!!!
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 454 must be stopped
# setup
# peer changes handled from a queue
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'listening 50214'
2016-10-04 22:55:22 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:22 - DEBUG createNativeListener: 'listening 50215'
2016-10-04 22:55:22 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-04 22:55:22 - DEBUG createPeerListener: 'listening 50216'
2016-10-04 22:55:22 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-10-04 22:55:22 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-04 22:55:22 - DEBUG createPeerListener: 'listening 50217'
2016-10-04 22:55:22 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-10-04 22:55:22 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-04 22:55:22 - DEBUG createPeerListener: 'listening 50218'
2016-10-04 22:55:22 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-10-04 22:55:22 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-04 22:55:22 - DEBUG createPeerListener: 'listening 50219'
2016-10-04 22:55:22 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-10-04 22:55:22 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-04 22:55:22 - DEBUG createPeerListener: 'listening 50220'
2016-10-04 22:55:22 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-10-04 22:55:22 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-04 22:55:22 - DEBUG createPeerListener: 'listening 50221'
2016-10-04 22:55:22 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-10-04 22:55:22 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-04 22:55:22 - DEBUG createPeerListener: 'listening 50222'
2016-10-04 22:55:22 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-10-04 22:55:22 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-04 22:55:22 - DEBUG createPeerListener: 'listening 50223'
2016-10-04 22:55:22 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-10-04 22:55:22 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-04 22:55:22 - DEBUG createPeerListener: 'listening 50224'
2016-10-04 22:55:22 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-10-04 22:55:22 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-04 22:55:22 - DEBUG createPeerListener: 'listening 50225'
2016-10-04 22:55:22 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 455 peers were handled in the right order
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 456 must be stopped
# setup
# relaying discoveryAdvertisingStateUpdateNonTCP
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'listening 50226'
2016-10-04 22:55:22 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:22 - DEBUG createNativeListener: 'listening 50227'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
ok 457 discovery is active
ok 458 advertising is active
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 459 must be stopped
# setup
# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'listening 50228'
2016-10-04 22:55:22 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:22 - DEBUG createNativeListener: 'listening 50229'
2016-10-04 22:55:22 - DEBUG thaliWifiInfrastructure: 'listening 50231'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2016-10-04 22:55:22 - INFO thaliMobileNativeWrapper: 'incomingConnectionToPortNumberFailed: 50229'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 460 right error reason
ok 461 Stop should be fine
ok 462 same port
ok 463 we should be off
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 464 must be stopped
# setup
# we successfully receive and replay discoveryAdvertisingStateUpdate
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'listening 50232'
2016-10-04 22:55:22 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:22 - DEBUG createNativeListener: 'listening 50233'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 465 discoveryActive matches
ok 466 advertisingActive matches
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 467 discoveryActive matches
ok 468 advertisingActive matches
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'listening 50234'
2016-10-04 22:55:22 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:22 - DEBUG createNativeListener: 'listening 50235'
2016-10-04 22:55:22 - DEBUG thaliWifiInfrastructure: 'listening 50237'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 469 discoveryActive matches
ok 470 advertisingActive matches
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 471 discoveryActive matches
ok 472 advertisingActive matches
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'listening 50238'
2016-10-04 22:55:22 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:22 - DEBUG createNativeListener: 'listening 50239'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-04 22:55:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 473 must be stopped
# setup
# Test BEACONS_RETRIEVED_AND_PARSED locally
ok 474 peerIdentifier should be identifier
ok 475 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 476 good beacon
ok 477 good preAmble
ok 478 public keys match!
ok 479 must return null after successful call
ok 480 Once start returns the action should be in KILLED state
# teardown
# setup
# Test HTTP_BAD_RESPONSE locally
ok 481 Response should be HTTP_BAD_RESPONSE
ok 482 must return null after successful call
# teardown
# setup
# Test NETWORK_PROBLEM locally
ok 483 Response should be NETWORK_PROBLEM
ok 484 reject reason should be: Could not establish TCP connection
# teardown
# setup
# Call the start two times
ok 485 Call start once
ok 486 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 487 must return null after successful call.
# teardown
# setup
# Call the kill before calling the start
ok 488 Should be Killed
ok 489 Start after killed
# teardown
# setup
# Call the kill immediately after the start
ok 490 Should be KILLED
ok 491 must return null after successful kill
# teardown
# setup
# Call the kill while waiting a response from the server
ok 492 Should be KILLED
ok 493 must return null after successful kill
# teardown
# setup
# Test to exceed the max content size locally
ok 494 HTTP_BAD_RESPONSE should be response when content size is exceeded
ok 495 must return null after successful call
# teardown
# setup
# Close the server socket while the client is waiting a response from the server. Local test.
ok 496 Should be NETWORK_PROBLEM caused closing server socket
ok 497 Should be Could not establish TCP connection
# teardown
# setup
# Close the client socket while the client is waiting a response from the server. Local test.
ok 498 Should be NETWORK_PROBLEM caused closing client socket
ok 499 Should be Could not establish TCP connection
# teardown
# setup
# #generatePreambleAndBeacons bad args
ok 500 publicKeysToNotify cannot be null
ok 501 ecdh for local device cannot be null
ok 502 milliseconds cannot be less than 0
ok 503 milliseconds cannot be 0
ok 504 milliseconds cannot be greater than one_day
# teardown
# setup
# #generatePreambleAndBeacons empty keys to notify
ok 505 should be equal
# teardown
# setup
# #generatePreambleAndBeacons multiple keys to notify
ok 506 should be equal
ok 507 should be equal
ok 508 (unnamed assert)
ok 509 should be equal
# teardown
# setup
# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
ok 510 should throw
# teardown
# setup
# #parseBeacons invalid expiration in beaconStreamWithPreAmble
ok 511 Preamble expiration must be a 64 bit integer
# teardown
# setup
# #parseBeacons expiration out of range lower
ok 512 Expiration out of range
# teardown
# setup
# #parseBeacons expiration out of range lower
ok 513 Expiration out of range
# teardown
# setup
# #parseBeacons no beacons returns null
ok 514 should be equal
# teardown
# setup
# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
ok 515 Malformed encrypted beacon key ID
# teardown
# setup
# #parseBeacons addressBookCallback fails decrypt
ok 516 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns no matches
ok 517 should be equal
ok 518 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns spurious match
ok 519 should be equal
ok 520 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns public key
ok 521 right number of calls to address book
ok 522 good preAmble
ok 523 good unencryptedKeyId
ok 524 good beacon
# teardown
# setup
# validate generatePskIdentityField
ok 525 decoded buffers match
# teardown
# setup
# validate generatePskSecret
ok 526 secrets match
# teardown
# setup
# validate generatePskSecrets
ok 527 Matching numbers
ok 528 We have an entry!
ok 529 keys match
ok 530 secrets match
ok 531 We have an entry!
ok 532 keys match
ok 533 secrets match
ok 534 We have an entry!
ok 535 keys match
ok 536 secrets match
# teardown
# setup
# validate generateBeaconStreamAndSecrets
ok 537 Streams have same length
ok 538 matching size
ok 539 keys match
ok 540 secrets match
# teardown
# setup
# Add two Peers.
ok 541 should be equal
ok 542 should be equal
ok 543 should be equal
ok 544 should be equal
ok 545 should be equal
# teardown
# setup
# TCP_NATIVE peer loses DNS
ok 546 should be equal
ok 547 should be equal
# teardown
# setup
# Received beacons with no values for us
ok 548 entry exists
ok 549 entry is resolved
# teardown
# setup
# Resolves an action locally
ok 550 Host address must match
ok 551 suggestedTCPTimeout must match
ok 552 connectionType must match
ok 553 portNumber must match
# teardown
# setup
# Resolves an action locally using ThaliPeerPoolDefault
ok 554 Host address must match
ok 555 suggestedTCPTimeout must match
ok 556 connectionType must match
ok 557 portNumber must match
# teardown
# setup
# Action fails because of a bad hostname.
ok 558 action should be resolved with NETWORK_PROBLEM error
ok 559 action should be resolved with NETWORK_PROBLEM error
ok 560 action should be resolved with NETWORK_PROBLEM error
ok 561 action should be resolved with NETWORK_PROBLEM error
ok 562 correct number of requests
ok 563 correct number of failures
ok 564 correct final peer state
# teardown
# setup
# hostaddress is removed when the action is running. 
ok 565 should be equal
# teardown
# setup
# Client to server request locally
ok 566 secrets are equal
ok 567 Public key matches with the server key
ok 568 Host address must match
ok 569 suggestedTCPTimeout must match
ok 570 connectionType must match
ok 571 portNumber must match
# teardown
# setup
# Test ThaliPskMapCache clean and expiration
ok 572 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
ok 573 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
ok 574 All entries should be expired after 1 second
# teardown
# setup
# Test ThaliPskMapCache getSecret and getPublic
ok 575 All keys need to be available in the cache
ok 576 All entries should be expired after 1 second
# teardown
# setup
# Test ThaliPskMapCache multiple entries
ok 577 Size of the cache should be 2
ok 578 Cache doesn't contain dictionary1
ok 579 Size of the cache should be 1
ok 580 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
# setup
# Start and stop ThaliNotificationServer
ok 581 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
ok 582 ThaliMobile.StopAdvertisingAndListeningshould be called once
# teardown
# setup
# Pass an empty array to ThaliNotificationServer.start
ok 583 StartUpdateAdvertisingAndListening should not be called
ok 584 ThaliMobile.StopAdvertisingAndListening should be called once
ok 585 no error
ok 586 should be 204
# teardown
# setup
# Pass a string to ThaliNotificationServer.start
ok 587 StartUpdateAdvertisingAndListening should not be called
# teardown
# setup
# Pass an empty parameter to ThaliNotificationServer.start
ok 588 StartUpdateAdvertisingAndListening should not be called
# teardown
# setup
# Make an HTTP request to /NotificationBeacons
ok 589 no error
ok 590 should be 200
ok 591 should be equal
ok 592 should be equal
ok 593 (unnamed assert)
ok 594 no error
ok 595 should be 204
# teardown
# setup
# Make an HTTP request to /NotificationBeacons (no keys)
ok 596 error should be null
ok 597 should be 204
# teardown
# setup
# Make an HTTP request to /NotificationBeaconsbefore calling start
ok 598 should be 404
# teardown
# setup
# #testThaliPeerAction - test getters
ok 599 getPeerIdentifier
ok 600 getConnectionType
ok 601 getActionType
ok 602 getActionState
ok 603 getPskIdentity
ok 604 getPskKey
# teardown
# setup
# #testThaliPeerAction - start and kill
ok 605 initial state
ok 606 after start
ok 607 after kill
# teardown
# setup
# #testThaliPeerAction - double start
ok 608 should be equal
# teardown
# setup
# #testThaliPeerAction - start after kill
ok 609 clean kill
ok 610 should be equal
# teardown
# setup
# #testThaliPeerAction - make sure ids are unique
ok 611 should not be equal
# teardown
# setup
# Test PeerConnectionInformation basics
ok 612 connection type works
ok 613 getHostAddress works
ok 614 getPortNumber works
ok 615 getSuggestedTCPTimeout works
# teardown
# setup
# Test PeerDictionary basic functionality
ok 616 Entry counter must be 1
ok 617 Size must be 1
ok 618 Entry counter must be 2
ok 619 Size must be 2
ok 620 Entry2 should not be found
ok 621 Size must be 1
ok 622 Size must be 0
# teardown
# setup
# Test PeerDictionary with multiple entries.
ok 623 Size must be100
ok 624 Entries between 20 and MAXSIZE + 20 should exist
ok 625 WAITING state entry should not be removed
# teardown
# setup
# RESOLVED entries are removed before WAITING state entry.
ok 626 Entries between 6 and MAXSIZE + 4 should exist
ok 627 Size should be MAXSIZE
ok 628 Size should be MAXSIZE+6
# teardown
# setup
# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
ok 629 WAITING state entry should not be removed
ok 630 Waiting entries between 6 and MAXSIZE + 4 should exist
ok 631 Size should be MAXSIZE
ok 632 entryCounter should be MAXSIZE+6
# teardown
# setup
# When CONTROLLED_BY_POOL entry is removed and kill is called.
ok 633 Kill should be called once
ok 634 Size should be 100
# teardown
# setup
# #ThaliPeerPoolDefault - single action
ok 635 is an agent
ok 636 enqueue is fine
ok 637 Everything should be off the queue
# teardown
# setup
# #ThaliPeerPoolDefault - multiple actions
ok 638 is an agent
ok 639 first enqueue is fine
ok 640 is an agent
ok 641 second enqueue is fine
ok 642 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 643 Queue is empty
# teardown
# setup
# #ThaliPeerPoolDefault - PSK Pool works
ok 644 is an agent
ok 645 good enqueue
ok 646 Identity should match
ok 647 Got expected response
ok 648 Got psk call back
# teardown
# setup
# #ThaliPeerPoolDefault - stop
ok 649 is an agent
ok 650 enqueue worked
ok 651 is an agent
ok 652 enqueue 2 worked
ok 653 enqueue is not available when stopped
ok 654 start action is killed
ok 655 killed action is still killed
ok 656 inQueue is empty
# teardown
# setup
# #ThaliPeerPoolInterface - make sure that start verifies queue length
ok 657 good start
ok 658 good enqueue
ok 659 queue is not empty
# teardown
# setup
# #ThaliPeerPoolInterface - bad enqueues
ok 660 null arg
ok 661 wrong arg type
ok 662 wrong arg type
# teardown
# setup
# #ThaliPeerPoolInterface - do not allow same object type
ok 663 good enqueue
ok 664 already enqueued
# teardown
# setup
# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
ok 665 good enqueue
ok 666 2nd good enqueue
ok 667 we are in the pool
ok 668 We are out of the pool
ok 669 Action was killed
ok 670 The original kill was called too
ok 671 second item is still in queue
# teardown
# setup
# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
ok 672 good enqueue
ok 673 first kill
ok 674 second NOOP kill
# teardown
# setup
# #ThaliPeerPoolInterface - make sure that stop removes all actions
ok 675 1st good enqueue
ok 676 2nd good enqueue
ok 677 1st action is in the pool
ok 678 2nd action is in the pool
ok 679 1st action is out of the pool
ok 680 2st action is out of the pool
ok 681 pool is empty
# teardown
# setup
# Make sure peerDictionaryKey is reasonable
ok 682 equal keys
ok 683 not equal connection type
ok 684 same connection type, different buffer
# teardown
# setup
# Make sure start works
2016-10-04 22:55:36 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 685 First start and on called correctly
# teardown
# setup
# Make sure stop works
ok 686 second cleared dictionary
2016-10-04 22:55:36 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 687 First start and on called correctly
ok 688 First stop and removeListener called correctly
ok 689 first action kill called
ok 690 second action kill called
ok 691 first cleared dictionary
ok 692 first cleared pool
ok 693 second cleared dictionary
ok 694 second cleared pool
# teardown
# setup
# Simple peer event
2016-10-04 22:55:36 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 695 listener has been set
ok 696 peer dictionary has expected number of entries
ok 697 Dictionary and pool have same action
ok 698 ads match
ok 699 PouchDB matches
ok 700 DB Names match
ok 701 public keys match
ok 702 peer dictionary has expected number of entries
ok 703 Dictionary and pool have same action
ok 704 ads match
ok 705 PouchDB matches
ok 706 DB Names match
ok 707 public keys match
ok 708 start called once
ok 709 One entry left
ok 710 Dictionary and pool have same action
ok 711 Start never called
ok 712 Kill called once
ok 713 no entries left
ok 714 Third action is dead
ok 715 peer dictionary has expected number of entries
ok 716 Dictionary and pool have same action
ok 717 ads match
ok 718 PouchDB matches
ok 719 DB Names match
ok 720 public keys match
# teardown
# setup
# Server is not there
2016-10-04 22:55:37 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
ok 721 right error
# teardown
# setup
# Server accepts & closes connection
2016-10-04 22:55:37 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
ok 722 right error
# teardown
# setup
# Server always returns 500
2016-10-04 22:55:37 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
ok 723 Got error as expected
# teardown
# setup
# Server always returns 401
2016-10-04 22:55:37 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
ok 724 Got error as expected
# teardown
# setup
# Server always returns 403
2016-10-04 22:55:37 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
ok 725 Got error as expected
# teardown
# setup
# Make sure docs replicate
2016-10-04 22:55:37 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
2016-10-04 22:55:37 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
ok 726 should be equal
ok 727 All tests passed!
# teardown
# setup
# Do nothing and make sure we time out
2016-10-04 22:55:37 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
ok 728 action should be killed
ok 729 Error should be timed out
ok 730 No doc found
# teardown
# setup
# Do something and make sure we time out
2016-10-04 22:55:39 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
2016-10-04 22:55:39 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
ok 731 should be equal
ok 732 action should be killed
ok 733 Error should be timed out
# teardown
# setup
# Start replicating and then catch error when server goes
ok 734 socket hung up
# teardown
# setup
# compareBufferArrays
ok 735 should throw
ok 736 should throw
ok 737 (unnamed assert)
ok 738 (unnamed assert)
ok 739 (unnamed assert)
ok 740 (unnamed assert)
ok 741 (unnamed assert)
# teardown
# setup
# Call start twice and get error
ok 742 should throw
# teardown
# setup
# Start and make sure it runs
# teardown
# setup
# Make sure getTimeWhenRun is right after start
ok 743 (unnamed assert)
# teardown
# setup
# Make sure getTimeWhenRun is -1 after function is called
ok 744 should be equal
# teardown
# setup
# Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
ok 745 should be equal
ok 746 should be equal
ok 747 should throw
# teardown
# setup
# Test TransientState
ok 748 should throw
ok 749 should throw
ok 750 should be equal
ok 751 should be equal
ok 752 should be equal
ok 753 should be equal
ok 754 (unnamed assert)
ok 755 (unnamed assert)
# teardown
# setup
# No peers and empty database
ok 756 verify failed
ok 757 constructor called once
ok 758 constructor called with right args
ok 759 match start arg
ok 760 start called once
ok 761 stop called once
ok 762 stop after start
# teardown
# setup
# One peer and empty DB
ok 763 verify failed
ok 764 constructor called once
ok 765 constructor called with right args
ok 766 match start arg
ok 767 start called once
ok 768 stop called once
ok 769 stop after start
2016-10-04 22:55:41 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# One peer with _Local set behind current seq
ok 770 verify failed
ok 771 constructor called once
ok 772 constructor called with right args
ok 773 match start arg
ok 774 start called once
ok 775 stop called once
ok 776 stop after start
2016-10-04 22:55:41 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# One peer with _Local set equal to current seq
ok 777 verify failed
ok 778 constructor called once
ok 779 constructor called with right args
ok 780 match start arg
ok 781 start called once
ok 782 stop called once
ok 783 stop after start
2016-10-04 22:55:41 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# One peer with _Local set ahead of current seq (and no this should not happen)
ok 784 verify failed
ok 785 constructor called once
ok 786 constructor called with right args
ok 787 match start arg
ok 788 start called once
ok 789 stop called once
ok 790 stop after start
2016-10-04 22:55:41 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# Three peers, one not in DB, one behind and one ahead
ok 791 verify failed
ok 792 constructor called once
ok 793 constructor called with right args
ok 794 match start arg
ok 795 start called once
ok 796 stop called once
ok 797 stop after start
2016-10-04 22:55:41 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# More than maximum peers, make sure we only send maximum allowed
ok 798 verify failed
ok 799 constructor called once
ok 800 constructor called with right args
ok 801 match start arg
ok 802 start called once
ok 803 stop called once
ok 804 stop after start
2016-10-04 22:55:42 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# two peers with empty DB, update the doc
2016-10-04 22:55:42 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 805 verify failed
ok 806 constructor called once
ok 807 constructor called with right args
ok 808 last start before stop
ok 809 empty first start
ok 810 full second start
ok 811 only 2 timers
2016-10-04 22:55:42 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# add doc and make sure tokens refresh when they expire
2016-10-04 22:55:42 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
2016-10-04 22:55:42 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 812 verify failed
ok 813 constructor called once
ok 814 constructor called with right args
ok 815 start before stop
ok 816 We got at least 3 calls to start
ok 817 at least 3
ok 818 default 1
ok 819 1 run
ok 820 default 2
ok 821 2 run
ok 822 default 3
2016-10-04 22:55:42 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# start and stop and start and stop
ok 823 start out null
ok 824 back to null
2016-10-04 22:55:42 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 825 still null
ok 826 verify failed
ok 827 constructor called once
ok 828 constructor called with right args
ok 829 first start before first stop
ok 830 first stop before second start
ok 831 second start before second stop
2016-10-04 22:55:42 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# two identical starts in a row
ok 832 verify failed
ok 833 constructor called once
ok 834 constructor called with right args
ok 835 (unnamed assert)
2016-10-04 22:55:42 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# two different starts in a row
2016-10-04 22:55:42 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 836 verify failed
ok 837 constructor called once
ok 838 constructor called with right args
ok 839 (unnamed assert)
ok 840 (unnamed assert)
# teardown
# setup
# two stops and a start and two stops
ok 841 verify failed
ok 842 constructor called once
ok 843 constructor called with right args
ok 844 start before stop
2016-10-04 22:55:42 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# we properly enqueue requests so no then needed
2016-10-04 22:55:42 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 845 verify failed
ok 846 constructor called once
ok 847 constructor called with right args
ok 848 start before stop
# teardown
# setup
# test calculateSeqPointKeyId
ok 849 should be equal
ok 850 should be equal
# teardown
# setup
# can create servers manager
ok 851 serversManager must not be null
ok 852 serversManager must be an object
# teardown
# setup
# calling stop without start causes error
ok 853 We need to call start first
# teardown
# setup
# can start/stop servers manager
2016-10-04 22:55:42 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:42 - DEBUG createNativeListener: 'listening 50354'
ok 854 port must be in range
# teardown
# setup
# starting twice resolves with listening port
2016-10-04 22:55:42 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:42 - DEBUG createNativeListener: 'listening 50355'
ok 855 second start should return same port
# teardown
# setup
# terminateIncomingConnection will terminate a connection
2016-10-04 22:55:42 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:42 - DEBUG createNativeListener: 'listening 50357'
2016-10-04 22:55:42 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:55:42 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:55:42 - DEBUG createNativeListener: 'new mux'
ok 856 we should be connected
2016-10-04 22:55:42 - DEBUG createNativeListener: 'incoming socket close'
ok 857 now we are disconnected
# teardown
# setup
# terminate an Outgoing connection will terminate the server
2016-10-04 22:55:42 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:42 - DEBUG createNativeListener: 'listening 50359'
# teardown
# setup
# terminate an Outgoing connection with wrong arguments is not harmful
2016-10-04 22:55:42 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:55:42 - DEBUG createNativeListener: 'listening 50360'
# teardown
# setup
ok 858 should be in started state
# After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
ok 859 peer identifier should match
ok 860 generation should be 0
ok 861 host address should match
ok 862 port should match
ok 863 generation should be 0
ok 864 host address should be null
ok 865 port should should be null
# teardown
ok 866 should not be in started state
# setup
ok 867 should be in started state
# #startUpdateAdvertisingAndListening correctly updates USN
2016-10-04 22:55:42 - DEBUG thaliWifiInfrastructure: 'listening 50361'
ok 868 first invocation sets 0 generation
ok 869 second invocation doesn’t change UUID but increments generation
ok 870 third invocation doesn’t change UUID but increments generation
# teardown
ok 871 should not be in started state
# setup
ok 872 should be in started state
# #startUpdateAdvertisingAndListening generates new peerIdentifier after #stopAdvertisingAndListening has been called
2016-10-04 22:55:42 - DEBUG thaliWifiInfrastructure: 'listening 50362'
2016-10-04 22:55:42 - DEBUG thaliWifiInfrastructure: 'listening 50363'
ok 873 new UUID after advertising is stopped
# teardown
ok 874 should not be in started state
# setup
ok 875 should be in started state
# #startUpdateAdvertisingAndListening sends correct requests
2016-10-04 22:55:42 - DEBUG thaliWifiInfrastructure: 'listening 50364'
ok 876 advertise-alive fired with expected usn
ok 877 advertise-bye fired with expected usn
# teardown
ok 878 should not be in started state
# setup
ok 879 should be in started state
# messages with invalid location or USN should be ignored
2016-10-04 22:55:42 - WARN thaliWifiInfrastructure: 'Failed to parse a valid port number from location: http://foo.bar:90000'
ok 880 should not have emitted with invalid port
2016-10-04 22:55:42 - WARN thaliWifiInfrastructure: 'Invalid USN (expected "data:" prefix): foobar'
ok 881 should not have emitted with invalid USN
# teardown
ok 882 should not be in started state
# setup
ok 883 should be in started state
# Delayed own message are still ignored after advertisement has been toggled on and off several times
2016-10-04 22:55:42 - DEBUG thaliWifiInfrastructure: 'listening 50365'
2016-10-04 22:55:42 - DEBUG thaliWifiInfrastructure: 'listening 50366'
2016-10-04 22:55:42 - DEBUG thaliWifiInfrastructure: 'listening 50367'
2016-10-04 22:55:42 - DEBUG thaliWifiInfrastructure: 'listening 50368'
ok 884 all captured messages are not handled
# teardown
ok 885 should not be in started state
# setup
ok 886 should be in started state
# verify that Thali-specific messages are filtered correctly
ok 887 messages with irrelevant NT should be ignored
ok 888 relevant messages should not be ignored
# teardown
ok 889 should not be in started state
# setup
ok 890 should be in started state
# #startListeningForAdvertisements should fail if start not called
ok 891 specific error should be returned
# teardown
ok 892 should not be in started state
# setup
ok 893 should be in started state
# #startUpdateAdvertisingAndListening should fail if start not called
ok 894 specific error should be returned
# teardown
ok 895 should not be in started state
# setup
ok 896 should be in started state
# #start should fail if called twice in a row
ok 897 specific error should be received
# teardown
ok 898 should not be in started state
# setup
ok 899 should be in started state
# should not be started after stop is called
ok 900 should not be started
ok 901 should not be listening
ok 902 should not target listening
ok 903 should not be advertising
ok 904 should not target advertising
# teardown
ok 905 should not be in started state
# setup
ok 906 should be in started state
# #startUpdateAdvertisingAndListening should fail invalid router has been passed
2016-10-04 22:55:42 - ERROR thaliWifiInfrastructure: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 907 specific error should be received
# teardown
ok 908 should not be in started state
# setup
ok 909 should be in started state
# #startUpdateAdvertisingAndListening should fail if router server starting fails
2016-10-04 22:55:42 - ERROR thaliWifiInfrastructure: 'Router server emitted an error: Error: listen EADDRINUSE'
ok 910 specific error expected
# teardown
ok 911 should not be in started state
# setup
ok 912 should be in started state
# #startUpdateAdvertisingAndListening should start hosting given router object
2016-10-04 22:55:42 - DEBUG thaliWifiInfrastructure: 'listening 50370'
ok 913 server should respond with code 200
# teardown
ok 914 should not be in started state
# setup
ok 915 should be in started state
# #startUpdateAdvertisingAndListening bad psk should be rejected object
2016-10-04 22:55:42 - DEBUG thaliWifiInfrastructure: 'listening 50372'
ok 916 Connection should be rejected
# teardown
ok 917 should not be in started state
# setup
ok 918 should be in started state
# #stop can be called multiple times in a row
ok 919 should be in stopped state
ok 920 should still be in stopped state
# teardown
ok 921 should not be in started state
# setup
ok 922 should be in started state
# #startListeningForAdvertisements can be called multiple times in a row
ok 923 should be in listening state
ok 924 should still be in listening state
# teardown
ok 925 should not be in started state
# setup
ok 926 should be in started state
# #stopListeningForAdvertisements can be called multiple times in a row
ok 927 should not be in listening state
ok 928 should still not be in listening state
# teardown
ok 929 should not be in started state
# setup
ok 930 should be in started state
# #stopAdvertisingAndListening can be called multiple times in a row
ok 931 should not be in advertising state
ok 932 should still not be in advertising state
# teardown
ok 933 should not be in started state
# setup
ok 934 should be in started state
# functions are run from a queue in the right order
2016-10-04 22:55:42 - DEBUG thaliWifiInfrastructure: 'listening 50374'
ok 935 call order must match
# teardown
ok 936 should not be in started state
# setup
ok 937 should be in started state
# does not get peer changes from self
2016-10-04 22:55:42 - DEBUG thaliWifiInfrastructure: 'listening 50375'
# teardown
ok 938 should not be in started state
# setup
ok 939 should be in started state
# network changes are ignored while stopping
2016-10-04 22:55:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-04 22:55:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
ok 940 should not be called
# teardown
ok 941 should not be in started state
# setup
ok 942 should be in started state
# #startListeningForAdvertisements returns error if wifi is off and fires event when on
2016-10-04 22:55:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
ok 943 wifi should be off
ok 944 specific error expected
2016-10-04 22:55:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
ok 945 discoveryActive should be true
# teardown
ok 946 should not be in started state
# setup
ok 947 should be in started state
# #startUpdateAdvertisingAndListening returns error if wifi is off and fires event when on
2016-10-04 22:55:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
ok 948 wifi should be off
ok 949 specific error expected
2016-10-04 22:55:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-04 22:55:44 - DEBUG thaliWifiInfrastructure: 'listening 50376'
ok 950 advertisingActive should be true
# teardown
ok 951 should not be in started state
# setup
ok 952 should be in started state
# when wifi is enabled discovery is activated and peers become available
2016-10-04 22:55:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
ok 953 wifi should be off
ok 954 specific error expected
2016-10-04 22:55:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
ok 955 peer identifier should match
ok 956 host address should match
ok 957 port should match
# teardown
ok 958 should not be in started state
# setup
# Correctly parses/stringifies USN
ok 959 correctly parses USN string
ok 960 throws if usn has invalid prefix
ok 961 throws if usn has invalid identifier format
ok 962 throws if usn has invalid generation
ok 963 correctly stringifies peer
# teardown
2016-10-04 22:55:45 - DEBUG SimpleThaliTape: 'all unit tests succeeded, platformName: 'desktop''
2016-10-04 22:55:45 - DEBUG SimpleThaliTape: 'skipped tests: '[]''
2016-10-04 22:55:45 - DEBUG SimpleThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'

1..963
# tests 963
# pass  963

# ok


> thali-cordova-plugin-jxcore@1.0.0 test-meta /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore
> jx runTests.js meta_tests

2016-10-04 22:55:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/meta_tests/testCanBeSkipped.js'
2016-10-04 22:55:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/meta_tests/testInstall.js'
2016-10-04 22:55:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/meta_tests/testResultsProcessor.js'
2016-10-04 22:55:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/meta_tests/testSync.js'
2016-10-04 22:55:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/meta_tests/testTestSendData.js'
2016-10-04 22:55:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/meta_tests/testTestUtils.js'
2016-10-04 22:55:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/meta_tests/testUnitTestFramework.js'
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
2016-10-04 22:55:48 - DEBUG SimpleThaliTape: 'test was skipped, name: 'we should skip test with 'canBeSkipped' returned true''
# teardown
# setup
# we should skip test with 'canBeSkipped' returned promise with true
2016-10-04 22:55:48 - DEBUG SimpleThaliTape: 'test was skipped, name: 'we should skip test with 'canBeSkipped' returned promise with true''
# teardown
# setup
# two required plugins should get installed
Trying to install jxcore-cordova version: 0.1.4
[36mDownloading:[39m [32mhttp://jxcore.azureedge.net/jxcore-cordova/0.1.4/release/io.jxcore.node.jx
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

Starting to download Thali Cordova plugin from: https://codeload.github.com/thaliproject/Thali_CordovaPlugin/zip/master
Adding Thali Cordova plugin from: /var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/T/tmp-3347vDAFNNyCcdIb/TestApp/thaliDontCheckIn/Thali_CordovaPlugin-master
Running jx npm install in: /var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/T/tmp-3347vDAFNNyCcdIb/TestApp/plugins/org.thaliproject.p2p/scripts
scripts@0.0.1 /private/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/T/tmp-3347vDAFNNyCcdIb/TestApp/plugins/org.thaliproject.p2p/scripts
└─┬ fs-extra-promise@0.2.1 
  ├── bluebird@2.11.0 
  └─┬ fs-extra@0.24.0 
    ├── graceful-fs@4.1.9 
    ├── jsonfile@2.4.0 
    ├── path-is-absolute@1.0.1 
    └─┬ rimraf@2.5.4 
      └─┬ glob@7.1.0 
        ├── fs.realpath@1.0.0 
        ├─┬ inflight@1.0.5 
        │ └── wrappy@1.0.2 
        ├── inherits@2.0.3 
        ├─┬ minimatch@3.0.3 
        │ └─┬ brace-expansion@1.1.6 
        │   ├── balanced-match@0.4.2 
        │   └── concat-map@0.0.1 
        └── once@1.4.0 


npm http request GET http://192.168.1.100:4873/fs-extra-promise
npm http 304 http://192.168.1.100:4873/fs-extra-promise
npm http request GET http://192.168.1.100:4873/fs-extra
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/fs-extra
npm http 200 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/jsonfile
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/rimraf
npm http 304 http://192.168.1.100:4873/jsonfile
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http 304 http://192.168.1.100:4873/path-is-absolute
npm http 200 http://192.168.1.100:4873/rimraf
npm http request GET http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/fs.realpath
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/inflight
npm http 200 http://192.168.1.100:4873/fs.realpath
npm http 304 http://192.168.1.100:4873/once
npm http 200 http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/wrappy
npm http 304 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 304 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/balanced-match
npm WARN EPACKAGEJSON scripts@0.0.1 No repository field.

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
/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/T/tmp-3347vDAFNNyCcdIb
ok 12 no error returned when creating a subfolder
# teardown
# setup
# can call hasRequiredHardware
ok 13 resolves with a boolean
# teardown
2016-10-04 22:56:42 - DEBUG SimpleThaliTape: 'all unit tests succeeded, platformName: 'desktop''
2016-10-04 22:56:42 - DEBUG SimpleThaliTape: 'skipped tests: '["we should skip test with 'canBeSkipped' returned true","we should skip test with 'canBeSkipped' returned promise with true"]''
2016-10-04 22:56:42 - DEBUG SimpleThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'

1..13
# tests 13
# pass  13

# ok


> thali-cordova-plugin-jxcore@1.0.0 test-coordinated /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore
> jx runCoordinatedTests.js

2016-10-04 22:56:44 - INFO HttpServer: 'listening on *:3000'

[36m2016-10-04 22:56:47 - DEBUG UnitTest_app: 'Unit Test app is loaded'
[39m
[36m2016-10-04 22:56:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-04 22:56:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-04 22:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
[39m
[36m2016-10-04 22:56:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
[39m
[36m2016-10-04 22:56:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
[39m
[36m2016-10-04 22:56:47 - DEBUG UnitTest_app: 'My device name is: bbbc781e-baac-4bef-9829-b74bb5736c8c'
[39m
[36m2016-10-04 22:56:47 - WARN testUtils: 'myNameCallback not set!'
[39m
[36m2016-10-04 22:56:47 - DEBUG UnitTest_app: 'Running for WIFI network type'
[39m
[32m2016-10-04 22:56:47 - DEBUG UnitTest_app: 'Unit Test app is loaded'
[39m
[32m2016-10-04 22:56:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
[39m
[32m2016-10-04 22:56:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
[39m
[32m2016-10-04 22:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
[39m
[32m2016-10-04 22:56:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
[39m
[32m2016-10-04 22:56:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
[39m
[32m2016-10-04 22:56:47 - DEBUG UnitTest_app: 'My device name is: cc986b1f-2d4e-4e5b-aa9a-d4cd6fe46e1b'
2016-10-04 22:56:47 - WARN testUtils: 'myNameCallback not set!'
[39m
[32m2016-10-04 22:56:47 - DEBUG UnitTest_app: 'Running for WIFI network type'
[39m
[33m2016-10-04 22:56:47 - DEBUG UnitTest_app: 'Unit Test app is loaded'
[39m
[33m2016-10-04 22:56:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
[39m
[33m2016-10-04 22:56:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
[39m
[33m2016-10-04 22:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
[39m
[33m2016-10-04 22:56:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
[39m
[33m2016-10-04 22:56:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
[39m
[33m2016-10-04 22:56:47 - DEBUG UnitTest_app: 'My device name is: 9528b46b-5705-40a0-9838-dff8f7e65e9b'
[39m
[33m2016-10-04 22:56:47 - WARN testUtils: 'myNameCallback not set!'
[39m
[33m2016-10-04 22:56:47 - DEBUG UnitTest_app: 'Running for WIFI network type'
[39m
[36m2016-10-04 22:56:47 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreateNativeListener.js'
[39m
[32m2016-10-04 22:56:47 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreateNativeListener.js'
[39m
[36m2016-10-04 22:56:47 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js'
[39m
[36m2016-10-04 22:56:47 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js'
[39m
[33m2016-10-04 22:56:47 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreateNativeListener.js'
[39m
[32m2016-10-04 22:56:47 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js'
[39m
[32m2016-10-04 22:56:47 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js'
[39m
[33m2016-10-04 22:56:47 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js'
[39m
[33m2016-10-04 22:56:47 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js'
[39m
[36m2016-10-04 22:56:47 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
[39m
[36m2016-10-04 22:56:47 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
[39m
[36m2016-10-04 22:56:47 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testNativeMethod.js'
[39m
[36m2016-10-04 22:56:47 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
[39m
[32m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
[39m
[32m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
[39m
[32m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testNativeMethod.js'
[39m
[32m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
[39m
[36m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBGenerator.js'
[39m
[36m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPromiseQueue.js'
[39m
[36m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testTests.js'
[39m
[36m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManager.js'
[39m
[36m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
[39m
[33m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
[39m
[36m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js'
[39m
[33m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
[39m
[33m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testNativeMethod.js'
[39m
[33m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
[39m
[36m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNative.js'
[39m
[36m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
[39m
[36m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
[39m
[32m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBGenerator.js'
[39m
[36m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotification.js'
[39m
[36m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationAction.js'
[39m
[36m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
[39m
[32m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPromiseQueue.js'
[39m
[36m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationClient.js'
[39m
[36m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationLocal.js'
[39m
[36m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationServer.js'
[39m
[36m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerAction.js'
[39m
[32m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testTests.js'
[39m
[36m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerDictionary.js'
[39m
[32m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManager.js'
[39m
[36m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
[39m
[36m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
[39m
[36m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
[39m
[36m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
[39m
[36m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
[39m
[36m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
[39m
[36m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
[39m
[36m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
[39m
[36m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliTcpServersManager.js'
[39m
[36m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
[39m
[32m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
[39m
[36m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testUsn.js'
[39m
[32m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js'
[39m
[36mWarning: a promise was created in a handler at node.js:917:13 but was not returned from it, see http://goo.gl/rRqMUw
    at new Promise (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/bluebird/js/release/promise.js:77:14)
    at Object.module.exports.hasRequiredHardware (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/testUtils.js:143:10)
    at Object.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/runTests.js:72:11)
    at Module._compile (module.js:619:26)
    at Object.Module._extensions..js (module.js:649:10)
    at Module.load (module.js:440:36)
    at Function.Module._load (module.js:405:12)
    at Module.require (module.js:475:17)
    at require (module.js:493:17)
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/UnitTest_app.js:76:13
    at process._tickCallback (node.js:917:13)
From previous event:
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/UnitTest_app.js:73:12
    at Array.reduce (native)
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/UnitTest_app.js:71:20
    at Object._onImmediate (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/wifiBasedNativeMock.js:705:5)
    at processImmediate [as _immediateCallback] (timers.js:370:15)
[39m
[32m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNative.js'
[39m
[33m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBGenerator.js'
[39m
[32m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
[39m
[32m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
[39m
[32m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotification.js'
[39m
[32m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationAction.js'
[39m
[33m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPromiseQueue.js'
[39m
[33m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testTests.js'
[39m
[33m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManager.js'
[39m
[32m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
[39m
[32m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationClient.js'
[39m
[32m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationLocal.js'
[39m
[32m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationServer.js'
[39m
[32m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerAction.js'
[39m
[32m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerDictionary.js'
[39m
[32m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
[39m
[32m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
[39m
[32m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
[39m
[32m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
[39m
[36m2016-10-04 22:56:48 - DEBUG CoordinatedClient: 'connected to the test server'
[39m
[33m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
[39m
2016-10-04 22:56:48 - DEBUG HttpServer: 'device presented, name: 'bbbc781e-baac-4bef-9829-b74bb5736c8c', uuid: 'bcc38c3f-77e2-4e2b-8261-4091cb6b455b', platformName: 'desktop', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-04 22:56:48 - DEBUG TestFramework: 'device added, name: 'bbbc781e-baac-4bef-9829-b74bb5736c8c''

[32m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
[39m
[32m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
[39m
[32m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
[39m
[32m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
[39m
[32m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliTcpServersManager.js'
[39m
[32m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
[39m
[33m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js'
[39m
[32m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testUsn.js'
[39m
[32mWarning: a promise was created in a handler at node.js:917:13 but was not returned from it, see http://goo.gl/rRqMUw
    at new Promise (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/bluebird/js/release/promise.js:77:14)
    at Object.module.exports.hasRequiredHardware (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/testUtils.js:143:10)
    at Object.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/runTests.js:72:11)
    at Module._compile (module.js:619:26)
    at Object.Module._extensions..js (module.js:649:10)
    at Module.load (module.js:440:36)
    at Function.Module._load (module.js:405:12)
    at Module.require (module.js:475:17)
    at require (module.js:493:17)
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/UnitTest_app.js:76:13
    at process._tickCallback (node.js:917:13)
From previous event:
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/UnitTest_app.js:73:12
    at Array.reduce (native)
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/UnitTest_app.js:71:20
    at Object._onImmediate (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/wifiBasedNativeMock.js:705:5)
    at processImmediate [as _immediateCallback] (timers.js:370:15)
[39m
[33m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNative.js'
[39m
[33m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
[39m
[33m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
[39m
[33m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotification.js'
[39m
[33m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationAction.js'
[39m
[33m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
[39m
[32m2016-10-04 22:56:48 - DEBUG CoordinatedClient: 'connected to the test server'
[39m
[33m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationClient.js'
[39m
[33m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationLocal.js'
[39m
[33m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationServer.js'
[39m
2016-10-04 22:56:48 - DEBUG HttpServer: 'device presented, name: 'cc986b1f-2d4e-4e5b-aa9a-d4cd6fe46e1b', uuid: '474d998a-c1f3-41fb-ac9d-ce41ac380a42', platformName: 'desktop', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-04 22:56:48 - DEBUG TestFramework: 'device added, name: 'cc986b1f-2d4e-4e5b-aa9a-d4cd6fe46e1b''

[33m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerAction.js'
[39m
[33m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerDictionary.js'
[39m
[33m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
[39m
[33m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
[39m
[33m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
[39m
[33m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
[39m
[33m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
[39m
[33m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
[39m
[33m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
[39m
[33m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
[39m
[33m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliTcpServersManager.js'
[39m
[33m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
[39m
[33m2016-10-04 22:56:48 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testUsn.js'
[39m
[33mWarning: a promise was created in a handler at node.js:917:13 but was not returned from it, see http://goo.gl/rRqMUw
    at new Promise (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/bluebird/js/release/promise.js:77:14)
    at Object.module.exports.hasRequiredHardware (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/testUtils.js:143:10)
    at Object.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/runTests.js:72:11)
    at Module._compile (module.js:619:26)
    at Object.Module._extensions..js (module.js:649:10)
    at Module.load (module.js:440:36)
    at Function.Module._load (module.js:405:12)
    at Module.require (module.js:475:17)
    at require (module.js:493:17)
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/UnitTest_app.js:76:13
    at process._tickCallback (node.js:917:13)
From previous event:
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/UnitTest_app.js:73:12
    at Array.reduce (native)
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/UnitTest_app.js:71:20
    at Object._onImmediate (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/wifiBasedNativeMock.js:705:5)
    at processImmediate [as _immediateCallback] (timers.js:370:15)
[39m
[33m2016-10-04 22:56:48 - DEBUG CoordinatedClient: 'connected to the test server'
[39m
2016-10-04 22:56:48 - DEBUG HttpServer: 'device presented, name: '9528b46b-5705-40a0-9838-dff8f7e65e9b', uuid: 'e29be1cd-6598-4159-9efd-3b0ae002eb58', platformName: 'desktop', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-04 22:56:48 - DEBUG TestFramework: 'device added, name: '9528b46b-5705-40a0-9838-dff8f7e65e9b''
2016-10-04 22:56:48 - INFO TestFramework: 'all required 3 devices are present for platformName: 'desktop''

2016-10-04 22:56:48 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'desktop''

2016-10-04 22:56:48 - DEBUG UnitTestFramework: 'scheduling tests'

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
2016-10-04 22:56:49 - DEBUG UnitTestFramework: 'tests scheduled'

2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#setup: 'calling createNativeListener directly rejects''

[36m# calling createNativeListener directly rejects
[39m
[32m# calling createNativeListener directly rejects
[39m
[33m# calling createNativeListener directly rejects
[39m
2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#setup ok: 'calling createNativeListener directly rejects''

2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#run: 'calling createNativeListener directly rejects''

[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating native server'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'listening 50409'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating native server'
[39m
[36mok 1 Should throw
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'listening 50410'
[39m
[36m# teardown
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating native server'
[39m
[32mok 1 Should throw
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'listening 50411'
[39m
[32m# teardown
[39m
[33mok 1 Should throw
[39m
[33m# teardown
[39m
2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#run ok: 'calling createNativeListener directly rejects''

2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#teardown: 'calling createNativeListener directly rejects''

[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#teardown ok: 'calling createNativeListener directly rejects''

2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#setup: 'emits incomingConnectionState''

[36m# emits incomingConnectionState
[39m
[32m# emits incomingConnectionState
[39m
[33m# emits incomingConnectionState
[39m
2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#setup ok: 'emits incomingConnectionState''

2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#run: 'emits incomingConnectionState''

[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating native server'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'listening 50415'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating native server'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'listening 50417'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
[39m
[36mok 2 initial connection state should be CONNECTED
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
[39m
[36mok 3 final connection state should be DISCONNECTED
[39m
[32mok 2 initial connection state should be CONNECTED
[39m
[36m# teardown
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating native server'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'listening 50419'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
[39m
[32mok 3 final connection state should be DISCONNECTED
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
[39m
[32m# teardown
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
[39m
[33mok 2 initial connection state should be CONNECTED
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
[39m
[33mok 3 final connection state should be DISCONNECTED
[39m
2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#run ok: 'emits incomingConnectionState''

[33m# teardown
[39m
2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#teardown: 'emits incomingConnectionState''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#teardown ok: 'emits incomingConnectionState''

2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#setup: 'emits routerPortConnectionFailed''

[36m# emits routerPortConnectionFailed
[39m
[32m# emits routerPortConnectionFailed
[39m
[33m# emits routerPortConnectionFailed
[39m
2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#setup ok: 'emits routerPortConnectionFailed''

2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#run: 'emits routerPortConnectionFailed''

[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating native server'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'listening 50424'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating native server'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'listening 50426'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: ' Error: connect ECONNREFUSED
    at errnoException (net.js:837:11)
    at Object.afterConnect [as oncomplete] (net.js:829:19)'
[39m
[36mok 4 tried to connect to right port
[39m
[36mok 5 failed due to refused connection
[39m
[36mok 6 routerPortConnectionFailed is emitted
[39m
[36m# teardown
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: ' Error: connect ECONNREFUSED
    at errnoException (net.js:837:11)
    at Object.afterConnect [as oncomplete] (net.js:829:19)'
ok 4 tried to connect to right port
ok 5 failed due to refused connection
ok 6 routerPortConnectionFailed is emitted
# teardown
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'listening 50430'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: ' Error: connect ECONNREFUSED
    at errnoException (net.js:837:11)
    at Object.afterConnect [as oncomplete] (net.js:829:19)'
[39m
[33mok 4 tried to connect to right port
[39m
[33mok 5 failed due to refused connection
[39m
[33mok 6 routerPortConnectionFailed is emitted
[39m
2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#run ok: 'emits routerPortConnectionFailed''
2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#teardown: 'emits routerPortConnectionFailed''

[33m# teardown
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
[39m
[36m# setup
2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
[39m
[32m# setup
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
[39m
[33m# setup
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
[39m
2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#teardown ok: 'emits routerPortConnectionFailed''
2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#setup: 'native server connections all up''

[36m# native server connections all up
[39m
[32m# native server connections all up
[39m
[33m# native server connections all up
[39m
2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#setup ok: 'native server connections all up''
2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#run: 'native server connections all up''

[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating native server'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'listening 50436'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating native server'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'listening 50438'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'listening 50442'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[36mok 7 Send/recvd #1 should be equal length
ok 8 Send/recvd #1 should be same
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36mok 9 Send/recvd #2 should be equal length
ok 10 Send/recvd #2 should be same
ok 11 Should be exactly 2 client sockets
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[36m# teardown
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[32mok 7 Send/recvd #1 should be equal length
[39m
[32mok 8 Send/recvd #1 should be same
[39m
[32mok 9 Send/recvd #2 should be equal length
[39m
[32mok 10 Send/recvd #2 should be same
ok 11 Should be exactly 2 client sockets
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
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
2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#run ok: 'native server connections all up''
2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#teardown: 'native server connections all up''

[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
[39m
[36m# setup
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
[39m
[32m# setup
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
[39m
[33m# setup
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
[39m
2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#teardown ok: 'native server connections all up''

2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming stream cleans outgoing socket''

[33m# native server - closing incoming stream cleans outgoing socket
[39m
[36m# native server - closing incoming stream cleans outgoing socket
[39m
[32m# native server - closing incoming stream cleans outgoing socket
[39m
2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming stream cleans outgoing socket''

2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming stream cleans outgoing socket''

[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating native server'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'listening 50451'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating native server'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'listening 50454'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
[39m
[33mok 12 socket shouldn't close until after stream
[39m
[33mok 13 incoming remains open
[39m
[33m# teardown
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating native server'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'listening 50457'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[36mok 12 socket shouldn't close until after stream
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
[39m
[36mok 13 incoming remains open
[39m
[36m# teardown
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[32mok 12 socket shouldn't close until after stream
[39m
[32mok 13 incoming remains open
[39m
[32m# teardown
[39m
2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming stream cleans outgoing socket''
2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming stream cleans outgoing socket''

[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
[39m
[36m# setup
2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
[39m
[32m# setup
2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
[39m
[33m# setup
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
[39m
2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming stream cleans outgoing socket''
2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming connection cleans outgoing socket''

[36m# native server - closing incoming connection cleans outgoing socket
[39m
[32m# native server - closing incoming connection cleans outgoing socket
[39m
[33m# native server - closing incoming connection cleans outgoing socket
[39m
2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming connection cleans outgoing socket''

2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming connection cleans outgoing socket''

[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'listening 50463'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating native server'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'listening 50465'
[39m
[36mok 14 we should not have gotten an error
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
[39m
[36mok 15 socket shouldn't close until after incoming
[39m
[36mok 16 incoming is cleaned up
[39m
[36m# teardown
[39m
[32mok 14 we should not have gotten an error
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating native server'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'listening 50469'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
[39m
[32mok 15 socket shouldn't close until after incoming
[39m
[32mok 16 incoming is cleaned up
[39m
[32m# teardown
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
ok 14 we should not have gotten an error
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
[39m
[33mok 15 socket shouldn't close until after incoming
[39m
[33mok 16 incoming is cleaned up
[39m
[33m# teardown
[39m
2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming connection cleans outgoing socket''

2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming connection cleans outgoing socket''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming connection cleans outgoing socket''

2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#setup: 'native server - closing outgoing socket cleans associated mux stream''

[36m# native server - closing outgoing socket cleans associated mux stream
[39m
[32m# native server - closing outgoing socket cleans associated mux stream
[39m
[33m# native server - closing outgoing socket cleans associated mux stream
[39m
2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#run: 'native server - closing outgoing socket cleans associated mux stream''

[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating native server'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'listening 50475'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating native server'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'listening 50478'
[39m
[36mok 17 stream was closed
[39m
[36mok 18 incoming should survive
[39m
[36mok 19 mux should have no streams
[39m
[36m# teardown
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating native server'
[39m
[32mok 17 stream was closed
[39m
[32mok 18 incoming should survive
[39m
[32mok 19 mux should have no streams
[39m
[32m# teardown
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'listening 50481'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[33mok 17 stream was closed
[39m
[33mok 18 incoming should survive
[39m
[33mok 19 mux should have no streams
[39m
[33m# teardown
[39m
2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#run ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#teardown: 'native server - closing outgoing socket cleans associated mux stream''

[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
[39m
[36m# setup
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
[39m
[32m# setup
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
[39m
[33m# setup
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
[39m
2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#setup: 'native server - closing the whole server cleans everything up''

[36m# native server - closing the whole server cleans everything up
[39m
[32m# native server - closing the whole server cleans everything up
[39m
[33m# native server - closing the whole server cleans everything up
[39m
2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing the whole server cleans everything up''

2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#run: 'native server - closing the whole server cleans everything up''

[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating native server'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'listening 50487'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'listening 50489'
[39m
[36mok 20 we should not have gotten an error
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
ok 21 Buffers are identical
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
[39m
[36mok 22 native server is nulled out
[39m
[36mok 23 native server should be closed
ok 24 incoming has been removed
ok 25 Incoming should be done
[39m
[36mok 26 The mux object should be closed
[39m
[36mok 27 The mux stream should be closed
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
[39m
[32mok 20 we should not have gotten an error
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[36m# teardown
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32mok 21 Buffers are identical
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
ok 22 native server is nulled out
ok 23 native server should be closed
ok 24 incoming has been removed
ok 25 Incoming should be done
ok 26 The mux object should be closed
ok 27 The mux stream should be closed
2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'listening 50493'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
[39m
[32m# teardown
[39m
[33mok 20 we should not have gotten an error
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33mok 21 Buffers are identical
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
[39m
[33mok 22 native server is nulled out
[39m
[33mok 23 native server should be closed
ok 24 incoming has been removed
[39m
[33mok 25 Incoming should be done
[39m
[33mok 26 The mux object should be closed
[39m
[33mok 27 The mux stream should be closed
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
[39m
[33m# teardown
[39m
2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#run ok: 'native server - closing the whole server cleans everything up''
2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#teardown: 'native server - closing the whole server cleans everything up''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing the whole server cleans everything up''

2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#setup: 'native server - we can get a ton of connections and data through and still clean up the server completely''

[36m# native server - we can get a ton of connections and data through and still clean up the server completely
[39m
[32m# native server - we can get a ton of connections and data through and still clean up the server completely
[39m
[33m# native server - we can get a ton of connections and data through and still clean up the server completely
[39m
2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#setup ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#run: 'native server - we can get a ton of connections and data through and still clean up the server completely''

[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating native server'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'listening 50499'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'listening 50510'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating native server'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'listening 50539'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new mux'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new stream: '
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[36m2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[36mok 28 native server is nulled out
ok 29 native server should be closed
ok 30 incoming has been removed
2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'stream close:'
[39m
[33mok 28 native server is nulled out
[39m
[33mok 29 native server should be closed
[39m
[33mok 30 incoming has been removed
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'mux close'
[39m
[32mok 28 native server is nulled out
ok 29 native server should be closed
ok 30 incoming has been removed
2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
[39m
[32m2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
[39m
[36m# teardown
[39m
[33m2016-10-04 22:56:49 - DEBUG createNativeListener: 'incoming socket close'
[39m
[32m# teardown
[39m
2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#run ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''
2016-10-04 22:56:49 - DEBUG UnitTestFramework: '#teardown: 'native server - we can get a ton of connections and data through and still clean up the server completely''

[32m# setup
[39m
[36m# setup
[39m
[33m# teardown
[39m
[33m# setup
[39m
2016-10-04 22:56:50 - DEBUG UnitTestFramework: '#teardown ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-10-04 22:56:50 - DEBUG UnitTestFramework: '#setup: 'native server - simulate mux failure, make sure everything is cleaned up''

[36m# native server - simulate mux failure, make sure everything is cleaned up
[39m
[33m# native server - simulate mux failure, make sure everything is cleaned up
[39m
[32m# native server - simulate mux failure, make sure everything is cleaned up
[39m
2016-10-04 22:56:50 - DEBUG UnitTestFramework: '#setup ok: 'native server - simulate mux failure, make sure everything is cleaned up''
2016-10-04 22:56:50 - DEBUG UnitTestFramework: '#run: 'native server - simulate mux failure, make sure everything is cleaned up''

[36m2016-10-04 22:56:50 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:56:50 - DEBUG createNativeListener: 'listening 50655'
2016-10-04 22:56:50 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:56:50 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:56:50 - DEBUG createNativeListener: 'new mux'
ok 31 we should not have gotten an error
2016-10-04 22:56:50 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:56:50 - DEBUG createNativeListener: 'new outgoing socket'
ok 32 Buffers are identical
2016-10-04 22:56:50 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:50 - DEBUG createNativeListener: 'mux close'
2016-10-04 22:56:50 - DEBUG createNativeListener: 'incoming socket close'
ok 33 server should be fine
ok 34 server should be open
ok 35 incoming has been removed
ok 36 The mux object should be closed
ok 37 The mux stream should be closed
# teardown
[39m
[32m2016-10-04 22:56:50 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:56:50 - DEBUG createNativeListener: 'listening 50657'
2016-10-04 22:56:50 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:56:50 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:56:50 - DEBUG createNativeListener: 'new mux'
ok 31 we should not have gotten an error
2016-10-04 22:56:50 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:56:50 - DEBUG createNativeListener: 'new outgoing socket'
ok 32 Buffers are identical
2016-10-04 22:56:50 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:50 - DEBUG createNativeListener: 'mux close'
2016-10-04 22:56:50 - DEBUG createNativeListener: 'incoming socket close'
ok 33 server should be fine
ok 34 server should be open
ok 35 incoming has been removed
ok 36 The mux object should be closed
ok 37 The mux stream should be closed
# teardown
[39m
[33m2016-10-04 22:56:50 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:56:50 - DEBUG createNativeListener: 'listening 50661'
[39m
[33m2016-10-04 22:56:50 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:56:50 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[33m2016-10-04 22:56:50 - DEBUG createNativeListener: 'new mux'
[39m
[33mok 31 we should not have gotten an error
[39m
[33m2016-10-04 22:56:50 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-04 22:56:50 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33mok 32 Buffers are identical
2016-10-04 22:56:50 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:50 - DEBUG createNativeListener: 'mux close'
[39m
[33m2016-10-04 22:56:50 - DEBUG createNativeListener: 'incoming socket close'
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
2016-10-04 22:56:50 - DEBUG UnitTestFramework: '#run ok: 'native server - simulate mux failure, make sure everything is cleaned up''
2016-10-04 22:56:50 - DEBUG UnitTestFramework: '#teardown: 'native server - simulate mux failure, make sure everything is cleaned up''

[33m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-10-04 22:56:50 - DEBUG UnitTestFramework: '#teardown ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-10-04 22:56:50 - DEBUG UnitTestFramework: '#setup: 'native server - timing out the incoming connection cleans everything up''

[36m# native server - timing out the incoming connection cleans everything up
[39m
[32m# native server - timing out the incoming connection cleans everything up
[39m
[33m# native server - timing out the incoming connection cleans everything up
[39m
2016-10-04 22:56:50 - DEBUG UnitTestFramework: '#setup ok: 'native server - timing out the incoming connection cleans everything up''

2016-10-04 22:56:50 - DEBUG UnitTestFramework: '#run: 'native server - timing out the incoming connection cleans everything up''

[36m2016-10-04 22:56:50 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:56:50 - DEBUG createNativeListener: 'listening 50667'
2016-10-04 22:56:50 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:56:50 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:56:50 - DEBUG createNativeListener: 'new mux'
ok 38 we should not have gotten an error
2016-10-04 22:56:50 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:56:50 - DEBUG createNativeListener: 'new outgoing socket'
ok 39 Buffers are identical
[39m
[32m2016-10-04 22:56:50 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:56:50 - DEBUG createNativeListener: 'listening 50669'
2016-10-04 22:56:50 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:56:50 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-04 22:56:50 - DEBUG createNativeListener: 'new mux'
ok 38 we should not have gotten an error
2016-10-04 22:56:50 - DEBUG createNativeListener: 'new stream: '
2016-10-04 22:56:50 - DEBUG createNativeListener: 'new outgoing socket'
ok 39 Buffers are identical
[39m
[33m2016-10-04 22:56:50 - DEBUG createNativeListener: 'creating native server'
2016-10-04 22:56:50 - DEBUG createNativeListener: 'listening 50673'
[39m
[36m2016-10-04 22:56:50 - DEBUG createNativeListener: 'incoming socket timeout'
2016-10-04 22:56:50 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:50 - DEBUG createNativeListener: 'mux close'
[39m
[32m2016-10-04 22:56:50 - DEBUG createNativeListener: 'incoming socket timeout'
2016-10-04 22:56:50 - DEBUG createNativeListener: 'stream close:'
2016-10-04 22:56:50 - DEBUG createNativeListener: 'mux close'
[39m
[36m2016-10-04 22:56:50 - DEBUG createNativeListener: 'incoming socket close'
ok 40 server should be fine
ok 41 server should be open
[39m
[33m2016-10-04 22:56:50 - DEBUG createNativeListener: 'new incoming socket'
2016-10-04 22:56:50 - DEBUG createNativeListener: 'creating incoming mux'
[39m
[36mok 42 incoming has been removed
ok 43 The mux object should be closed
ok 44 The mux stream should be closed
[39m
[33m2016-10-04 22:56:50 - DEBUG createNativeListener: 'new mux'
[39m
[33mok 38 we should not have gotten an error
[39m
[33m2016-10-04 22:56:50 - DEBUG createNativeListener: 'new stream: '
[39m
[33m2016-10-04 22:56:50 - DEBUG createNativeListener: 'new outgoing socket'
[39m
[33mok 39 Buffers are identical
[39m
[36m# teardown
[39m
[32m2016-10-04 22:56:50 - DEBUG createNativeListener: 'incoming socket close'
ok 40 server should be fine
ok 41 server should be open
ok 42 incoming has been removed
[39m
[32mok 43 The mux object should be closed
ok 44 The mux stream should be closed
[39m
[33m2016-10-04 22:56:50 - DEBUG createNativeListener: 'incoming socket timeout'
[39m
[33m2016-10-04 22:56:50 - DEBUG createNativeListener: 'stream close:'
[39m
[32m# teardown
[39m
[33m2016-10-04 22:56:50 - DEBUG createNativeListener: 'mux close'
[39m
[33m2016-10-04 22:56:50 - DEBUG createNativeListener: 'incoming socket close'
ok 40 server should be fine
ok 41 server should be open
[39m
[33mok 42 incoming has been removed
[39m
[33mok 43 The mux object should be closed
[39m
[33mok 44 The mux stream should be closed
[39m
2016-10-04 22:56:50 - DEBUG UnitTestFramework: '#run ok: 'native server - timing out the incoming connection cleans everything up''

2016-10-04 22:56:50 - DEBUG UnitTestFramework: '#teardown: 'native server - timing out the incoming connection cleans everything up''

[33m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-10-04 22:56:50 - DEBUG UnitTestFramework: '#teardown ok: 'native server - timing out the incoming connection cleans everything up''

2016-10-04 22:56:50 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server is not there''

[36m# #_doImmediateSeqUpdate - server is not there
[39m
[33m# #_doImmediateSeqUpdate - server is not there
[39m
[32m# #_doImmediateSeqUpdate - server is not there
[39m
2016-10-04 22:56:50 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server is not there''

2016-10-04 22:56:50 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server is not there''

[33m2016-10-04 22:56:50 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
[39m
[33mok 45 Got right error
[39m
[33m# teardown
[39m
[32m2016-10-04 22:56:50 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
[39m
[32mok 45 Got right error
[39m
[32m# teardown
[39m
[36m2016-10-04 22:56:50 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
[39m
[36mok 45 Got right error
[39m
[36m# teardown
[39m
2016-10-04 22:56:50 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server is not there''

2016-10-04 22:56:50 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server is not there''

[33m# setup
[39m
[32m# setup
[39m
[36m# setup
[39m
2016-10-04 22:56:50 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server is not there''

2016-10-04 22:56:50 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server accepts & closes connection''

[33m# #_doImmediateSeqUpdate - server accepts & closes connection
[39m
[32m# #_doImmediateSeqUpdate - server accepts & closes connection
[39m
[36m# #_doImmediateSeqUpdate - server accepts & closes connection
[39m
2016-10-04 22:56:50 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-04 22:56:50 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server accepts & closes connection''

[33m2016-10-04 22:56:50 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
[39m
[33mok 46 Got socket hang up
[39m
[33m# teardown
[39m
[32m2016-10-04 22:56:50 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
[39m
[36m2016-10-04 22:56:50 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
[39m
[36mok 46 Got socket hang up
[39m
[32mok 46 Got socket hang up
[39m
[36m# teardown
[39m
[32m# teardown
[39m
2016-10-04 22:56:50 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server accepts & closes connection''
2016-10-04 22:56:50 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server accepts & closes connection''

[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-10-04 22:56:50 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-04 22:56:50 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server always returns 500''

[36m# #_doImmediateSeqUpdate - server always returns 500
[39m
[32m# #_doImmediateSeqUpdate - server always returns 500
[39m
[33m# #_doImmediateSeqUpdate - server always returns 500
[39m
2016-10-04 22:56:51 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-04 22:56:51 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server always returns 500''

[36m2016-10-04 22:56:51 - DEBUG localSeqManager: 'Got an error trying to update seq []'
[39m
[36mok 47 Got 500 as expected
[39m
[36m# teardown
[39m
[32m2016-10-04 22:56:51 - DEBUG localSeqManager: 'Got an error trying to update seq []'
[39m
[32mok 47 Got 500 as expected
[39m
[32m# teardown
[39m
[33m2016-10-04 22:56:51 - DEBUG localSeqManager: 'Got an error trying to update seq []'
[39m
[33mok 47 Got 500 as expected
[39m
[33m# teardown
[39m
2016-10-04 22:56:51 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-04 22:56:51 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server always returns 500''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:56:51 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-04 22:56:51 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - create new seq doc''

[36m# #_doImmediateSeqUpdate - create new seq doc
[39m
[33m# #_doImmediateSeqUpdate - create new seq doc
[39m
[32m# #_doImmediateSeqUpdate - create new seq doc
[39m
2016-10-04 22:56:51 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-04 22:56:51 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - create new seq doc''

[32mok 48 should be equal
[39m
[32mok 49 revs are equal
[39m
[32m# teardown
[39m
[33mok 48 should be equal
[39m
[33mok 49 revs are equal
[39m
[33m# teardown
[39m
[36mok 48 should be equal
[39m
[36mok 49 revs are equal
[39m
[36m# teardown
[39m
2016-10-04 22:56:51 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-04 22:56:51 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - create new seq doc''

[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-10-04 22:56:51 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-04 22:56:51 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

[32m# #_doImmediateSeqUpdate - doc exists, need to get rev and update
[39m
[36m# #_doImmediateSeqUpdate - doc exists, need to get rev and update
[39m
[33m# #_doImmediateSeqUpdate - doc exists, need to get rev and update
[39m
2016-10-04 22:56:51 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-04 22:56:51 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

[32mok 50 should be equal
[39m
[32mok 51 revs are equal
[39m
[32m# teardown
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
2016-10-04 22:56:51 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-04 22:56:51 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

[33m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:56:51 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''
2016-10-04 22:56:51 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - update seq three times''

[36m# #_doImmediateSeqUpdate - update seq three times
[39m
[32m# #_doImmediateSeqUpdate - update seq three times
[39m
[33m# #_doImmediateSeqUpdate - update seq three times
[39m
2016-10-04 22:56:51 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - update seq three times''

2016-10-04 22:56:51 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - update seq three times''

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
[32mok 56 should be equal
[39m
[32mok 57 revs are equal
[39m
[32m# teardown
[39m
[33mok 52 should be equal
[39m
[33mok 53 revs are equal
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
2016-10-04 22:56:52 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - update seq three times''

2016-10-04 22:56:52 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - update seq three times''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:56:52 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - update seq three times''

2016-10-04 22:56:52 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - rev got changed under us''

[36m# #_doImmediateSeqUpdate - rev got changed under us
[39m
[32m# #_doImmediateSeqUpdate - rev got changed under us
[39m
[33m# #_doImmediateSeqUpdate - rev got changed under us
[39m
2016-10-04 22:56:52 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-04 22:56:52 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - rev got changed under us''

[36m2016-10-04 22:56:52 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
ok 58 Our rev is old so we should fail
[39m
[36m# teardown
[39m
[32m2016-10-04 22:56:52 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
ok 58 Our rev is old so we should fail
[39m
[32m# teardown
[39m
[33m2016-10-04 22:56:52 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
[39m
[33mok 58 Our rev is old so we should fail
[39m
[33m# teardown
[39m
2016-10-04 22:56:52 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-04 22:56:52 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - rev got changed under us''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:56:52 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-04 22:56:52 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - fail if stop is called''

[36m# #_doImmediateSeqUpdate - fail if stop is called
[39m
[32m# #_doImmediateSeqUpdate - fail if stop is called
[39m
[33m# #_doImmediateSeqUpdate - fail if stop is called
[39m
2016-10-04 22:56:52 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-04 22:56:52 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - fail if stop is called''

[36mok 59 confirm stop caused failure
[39m
[36m# teardown
[39m
[33mok 59 confirm stop caused failure
[39m
[32mok 59 confirm stop caused failure
[39m
2016-10-04 22:56:52 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-04 22:56:52 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - fail if stop is called''

[36m# setup
[39m
[32m# teardown
[39m
[33m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:56:53 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-04 22:56:53 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - stop after get but before put fails right''

[36m# #_doImmediateSeqUpdate - stop after get but before put fails right
[39m
[33m# #_doImmediateSeqUpdate - stop after get but before put fails right
[39m
[32m# #_doImmediateSeqUpdate - stop after get but before put fails right
[39m
2016-10-04 22:56:53 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-04 22:56:53 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - stop after get but before put fails right''

[36m2016-10-04 22:56:53 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
ok 60 stop caused us to fail
ok 61 We specifically failed on a stop before put
# teardown
[39m
[33m2016-10-04 22:56:53 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
[39m
[33mok 60 stop caused us to fail
[39m
[33mok 61 We specifically failed on a stop before put
[39m
[33m# teardown
[39m
[32m2016-10-04 22:56:53 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
[39m
[32mok 60 stop caused us to fail
[39m
[32mok 61 We specifically failed on a stop before put
[39m
[32m# teardown
[39m
2016-10-04 22:56:53 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-04 22:56:53 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - stop after get but before put fails right''

[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-10-04 22:56:53 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-04 22:56:53 - DEBUG UnitTestFramework: '#setup: '#update - fail if stop is called''

[36m# #update - fail if stop is called
[39m
[33m# #update - fail if stop is called
[39m
[32m# #update - fail if stop is called
[39m
2016-10-04 22:56:53 - DEBUG UnitTestFramework: '#setup ok: '#update - fail if stop is called''

2016-10-04 22:56:53 - DEBUG UnitTestFramework: '#run: '#update - fail if stop is called''

[36mok 62 failed due to stop
ok 63 failed due to stop
# teardown
[39m
[33mok 62 failed due to stop
ok 63 failed due to stop
# teardown
[39m
[32mok 62 failed due to stop
[39m
[32mok 63 failed due to stop
[39m
[32m# teardown
[39m
2016-10-04 22:56:53 - DEBUG UnitTestFramework: '#run ok: '#update - fail if stop is called''

2016-10-04 22:56:53 - DEBUG UnitTestFramework: '#teardown: '#update - fail if stop is called''

[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-10-04 22:56:53 - DEBUG UnitTestFramework: '#teardown ok: '#update - fail if stop is called''
2016-10-04 22:56:53 - DEBUG UnitTestFramework: '#setup: '#update - set seq for first time''

[36m# #update - set seq for first time
[39m
[33m# #update - set seq for first time
[39m
[32m# #update - set seq for first time
[39m
2016-10-04 22:56:53 - DEBUG UnitTestFramework: '#setup ok: '#update - set seq for first time''

2016-10-04 22:56:53 - DEBUG UnitTestFramework: '#run: '#update - set seq for first time''

[36mok 64 should be equal
[39m
[36m# teardown
[39m
[32mok 64 should be equal
[39m
[32m# teardown
[39m
[33mok 64 should be equal
[39m
[33m# teardown
[39m
2016-10-04 22:56:53 - DEBUG UnitTestFramework: '#run ok: '#update - set seq for first time''
2016-10-04 22:56:53 - DEBUG UnitTestFramework: '#teardown: '#update - set seq for first time''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:56:53 - DEBUG UnitTestFramework: '#teardown ok: '#update - set seq for first time''

2016-10-04 22:56:53 - DEBUG UnitTestFramework: '#setup: '#update - Fail on bad seq value''

[36m# #update - Fail on bad seq value
[39m
[32m# #update - Fail on bad seq value
[39m
[33m# #update - Fail on bad seq value
[39m
2016-10-04 22:56:53 - DEBUG UnitTestFramework: '#setup ok: '#update - Fail on bad seq value''

2016-10-04 22:56:53 - DEBUG UnitTestFramework: '#run: '#update - Fail on bad seq value''

[33m2016-10-04 22:56:53 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
ok 65 Expected bad seq error
[39m
[33m# teardown
[39m
[36m2016-10-04 22:56:53 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
ok 65 Expected bad seq error
# teardown
[39m
[32m2016-10-04 22:56:53 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
[39m
[32mok 65 Expected bad seq error
[39m
[32m# teardown
[39m
2016-10-04 22:56:53 - DEBUG UnitTestFramework: '#run ok: '#update - Fail on bad seq value''

2016-10-04 22:56:53 - DEBUG UnitTestFramework: '#teardown: '#update - Fail on bad seq value''

[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-10-04 22:56:53 - DEBUG UnitTestFramework: '#teardown ok: '#update - Fail on bad seq value''

2016-10-04 22:56:53 - DEBUG UnitTestFramework: '#setup: '#update - do we cancel timer properly on an immediate?''

[36m# #update - do we cancel timer properly on an immediate?
[39m
[33m# #update - do we cancel timer properly on an immediate?
[39m
[32m# #update - do we cancel timer properly on an immediate?
[39m
2016-10-04 22:56:53 - DEBUG UnitTestFramework: '#setup ok: '#update - do we cancel timer properly on an immediate?''

2016-10-04 22:56:53 - DEBUG UnitTestFramework: '#run: '#update - do we cancel timer properly on an immediate?''

[36mok 66 Different promises
[39m
[36mok 67 Timer was cancelled
[39m
[33mok 66 Different promises
ok 67 Timer was cancelled
[39m
[36mok 68 should be equal
[39m
[33mok 68 should be equal
[39m
[33m# teardown
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
2016-10-04 22:56:53 - DEBUG UnitTestFramework: '#run ok: '#update - do we cancel timer properly on an immediate?''

2016-10-04 22:56:53 - DEBUG UnitTestFramework: '#teardown: '#update - do we cancel timer properly on an immediate?''

[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-10-04 22:56:53 - DEBUG UnitTestFramework: '#teardown ok: '#update - do we cancel timer properly on an immediate?''

2016-10-04 22:56:53 - DEBUG UnitTestFramework: '#setup: '#update - do we wait for blocked update''

[33m# #update - do we wait for blocked update
[39m
[36m# #update - do we wait for blocked update
[39m
[32m# #update - do we wait for blocked update
[39m
2016-10-04 22:56:53 - DEBUG UnitTestFramework: '#setup ok: '#update - do we wait for blocked update''

2016-10-04 22:56:53 - DEBUG UnitTestFramework: '#run: '#update - do we wait for blocked update''

[36mok 69 One go and one blocked
[39m
[36mok 70 All blocked
ok 71 Still blocked
[39m
[32mok 69 One go and one blocked
[39m
[32mok 70 All blocked
[39m
[32mok 71 Still blocked
[39m
[33mok 69 One go and one blocked
ok 70 All blocked
ok 71 Still blocked
[39m
[33mok 72 should be equal
[39m
[33m# teardown
[39m
[36mok 72 should be equal
[39m
[36m# teardown
[39m
[32mok 72 should be equal
[39m
2016-10-04 22:56:54 - DEBUG UnitTestFramework: '#run ok: '#update - do we wait for blocked update''

2016-10-04 22:56:54 - DEBUG UnitTestFramework: '#teardown: '#update - do we wait for blocked update''

[32m# teardown
[39m
[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-10-04 22:56:54 - DEBUG UnitTestFramework: '#teardown ok: '#update - do we wait for blocked update''
2016-10-04 22:56:54 - DEBUG UnitTestFramework: '#setup: '#update - test that we wait long enough''

[32m# #update - test that we wait long enough
[39m
[33m# #update - test that we wait long enough
[39m
[36m# #update - test that we wait long enough
[39m
2016-10-04 22:56:54 - DEBUG UnitTestFramework: '#setup ok: '#update - test that we wait long enough''

2016-10-04 22:56:54 - DEBUG UnitTestFramework: '#run: '#update - test that we wait long enough''

[32mok 73 We waited long enough
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
[36mok 73 We waited long enough
[39m
[36mok 74 should be equal
[39m
[36m# teardown
[39m
2016-10-04 22:56:55 - DEBUG UnitTestFramework: '#run ok: '#update - test that we wait long enough''
2016-10-04 22:56:55 - DEBUG UnitTestFramework: '#teardown: '#update - test that we wait long enough''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:56:55 - DEBUG UnitTestFramework: '#teardown ok: '#update - test that we wait long enough''
2016-10-04 22:56:55 - DEBUG UnitTestFramework: '#setup: '#update - test that we pick up new sequences while we wait''

[36m# #update - test that we pick up new sequences while we wait
[39m
[32m# #update - test that we pick up new sequences while we wait
[39m
[33m# #update - test that we pick up new sequences while we wait
[39m
2016-10-04 22:56:55 - DEBUG UnitTestFramework: '#setup ok: '#update - test that we pick up new sequences while we wait''

2016-10-04 22:56:55 - DEBUG UnitTestFramework: '#run: '#update - test that we pick up new sequences while we wait''

[32mok 75 Should have gotten same timer promise
[39m
[32mok 76 Still same timer promise
[39m
[36mok 75 Should have gotten same timer promise
[39m
[36mok 76 Still same timer promise
[39m
[33mok 75 Should have gotten same timer promise
ok 76 Still same timer promise
[39m
[36mok 77 We waited long enough
[39m
[32mok 77 We waited long enough
[39m
[36mok 78 should be equal
# teardown
[39m
[33mok 77 We waited long enough
[39m
[32mok 78 should be equal
# teardown
[39m
[33mok 78 should be equal
[39m
[33m# teardown
[39m
2016-10-04 22:56:56 - DEBUG UnitTestFramework: '#run ok: '#update - test that we pick up new sequences while we wait''
2016-10-04 22:56:56 - DEBUG UnitTestFramework: '#teardown: '#update - test that we pick up new sequences while we wait''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:56:56 - DEBUG UnitTestFramework: '#teardown ok: '#update - test that we pick up new sequences while we wait''

2016-10-04 22:56:56 - DEBUG UnitTestFramework: '#setup: 'Coordinated seq test''

[36m# Coordinated seq test
[39m
[32m# Coordinated seq test
[39m
[33m# Coordinated seq test
[39m
2016-10-04 22:56:56 - DEBUG UnitTestFramework: '#setup ok: 'Coordinated seq test''

2016-10-04 22:56:56 - DEBUG UnitTestFramework: '#run: 'Coordinated seq test''

[32m2016-10-04 22:56:56 - DEBUG thaliWifiInfrastructure: 'listening 50883'
[39m
[36m2016-10-04 22:56:56 - DEBUG thaliWifiInfrastructure: 'listening 50884'
[39m
[33m2016-10-04 22:56:56 - DEBUG thaliWifiInfrastructure: 'listening 50885'
[39m
[32mok 79 should be equal
[39m
[32mok 80 should be equal
[39m
[32m# teardown
[39m
[36mok 79 should be equal
[39m
[33mok 79 should be equal
[39m
[36mok 80 should be equal
[39m
[36m# teardown
[39m
[33mok 80 should be equal
[39m
2016-10-04 22:56:57 - DEBUG UnitTestFramework: '#run ok: 'Coordinated seq test''
2016-10-04 22:56:57 - DEBUG UnitTestFramework: '#teardown: 'Coordinated seq test''

[33m# teardown
[39m
[36m2016-10-04 22:56:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
# setup
[39m
[32m2016-10-04 22:56:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
# setup
[39m
[33m2016-10-04 22:56:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[39m
[33m# setup
[39m
2016-10-04 22:56:57 - DEBUG UnitTestFramework: '#teardown ok: 'Coordinated seq test''

2016-10-04 22:56:57 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

[36m# closeAll can close even when connections open
[39m
[32m# closeAll can close even when connections open
[39m
[33m# closeAll can close even when connections open
[39m
2016-10-04 22:56:57 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2016-10-04 22:56:57 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

[32mok 81 not possible to connect to the server anymore
[39m
[33mok 81 not possible to connect to the server anymore
[39m
[33m# teardown
[39m
[32m# teardown
[39m
[36mok 81 not possible to connect to the server anymore
[39m
2016-10-04 22:56:57 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2016-10-04 22:56:57 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

[36m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-10-04 22:56:57 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2016-10-04 22:56:57 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

[36m# closeAll with promise
[39m
[32m# closeAll with promise
[39m
[33m# closeAll with promise
[39m
2016-10-04 22:56:57 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2016-10-04 22:56:57 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

[36mok 82 not possible to connect to the server anymore
[39m
[36m# teardown
[39m
[32mok 82 not possible to connect to the server anymore
[39m
[32m# teardown
[39m
[33mok 82 not possible to connect to the server anymore
[39m
[33m# teardown
[39m
2016-10-04 22:56:58 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2016-10-04 22:56:58 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:56:58 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2016-10-04 22:56:58 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

[36m# closeAll properly throws when closing a non open server with eatNotRunning set to false
[39m
[33m# closeAll properly throws when closing a non open server with eatNotRunning set to false
[39m
[32m# closeAll properly throws when closing a non open server with eatNotRunning set to false
[39m
2016-10-04 22:56:58 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2016-10-04 22:56:58 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

[36mok 83 Got the right error
[39m
[36m# teardown
[39m
[33mok 83 Got the right error
# teardown
[39m
[32mok 83 Got the right error
# teardown
[39m
2016-10-04 22:56:58 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2016-10-04 22:56:58 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:56:58 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2016-10-04 22:56:58 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

[36m# closeAll works even with a server that is not listening yet witheatNotRunning set to true
[39m
[33m# closeAll works even with a server that is not listening yet witheatNotRunning set to true
[39m
[32m# closeAll works even with a server that is not listening yet witheatNotRunning set to true
[39m
2016-10-04 22:56:58 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2016-10-04 22:56:58 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

[36m# teardown
[39m
[33m# teardown
[39m
[32m# teardown
[39m
2016-10-04 22:56:58 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''
2016-10-04 22:56:58 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:56:58 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2016-10-04 22:56:58 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

[36m# Call of onCheckpointReached handler on a single db change
[39m
[32m# Call of onCheckpointReached handler on a single db change
[39m
[33m# Call of onCheckpointReached handler on a single db change
[39m
2016-10-04 22:56:58 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''
2016-10-04 22:56:58 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

[32m# teardown
[39m
[36m# teardown
[39m
[33m# teardown
[39m
2016-10-04 22:56:58 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''
2016-10-04 22:56:58 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-10-04 22:56:58 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2016-10-04 22:56:58 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

[33m# Call of multiple onCheckpointReached handlers on a single db change
[39m
[32m# Call of multiple onCheckpointReached handlers on a single db change
[39m
[36m# Call of multiple onCheckpointReached handlers on a single db change
[39m
2016-10-04 22:56:58 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2016-10-04 22:56:58 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

[33m# teardown
[39m
[32m# teardown
[39m
[36m# teardown
[39m
2016-10-04 22:56:58 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''
2016-10-04 22:56:58 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-10-04 22:56:58 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''
2016-10-04 22:56:58 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

[33m# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
[39m
[36m# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
[39m
[32m# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
[39m
2016-10-04 22:56:58 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2016-10-04 22:56:58 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

[32mok 84 the checkpointReached handler should be called once. Called 1 time(s)
[39m
[32m# teardown
[39m
[36mok 84 the checkpointReached handler should be called once. Called 1 time(s)
# teardown
[39m
[33mok 84 the checkpointReached handler should be called once. Called 1 time(s)
# teardown
[39m
2016-10-04 22:57:00 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2016-10-04 22:57:00 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:00 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
2016-10-04 22:57:00 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

[33m# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
[39m
[36m# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
[39m
[32m# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
[39m
2016-10-04 22:57:00 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
2016-10-04 22:57:00 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

[33m# teardown
[39m
[36m# teardown
[39m
[32m# teardown
[39m
2016-10-04 22:57:00 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
2016-10-04 22:57:00 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:00 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
2016-10-04 22:57:00 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

[36m# test defaultDirectory
[39m
[32m# test defaultDirectory
[39m
[33m# test defaultDirectory
[39m
2016-10-04 22:57:00 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2016-10-04 22:57:00 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

[36mok 85 should be equal
ok 86 should be equal
ok 87 should be equal
# teardown
[39m
[32mok 85 should be equal
ok 86 should be equal
ok 87 should be equal
# teardown
[39m
[33mok 85 should be equal
ok 86 should be equal
ok 87 should be equal
# teardown
[39m
2016-10-04 22:57:00 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''
2016-10-04 22:57:00 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-10-04 22:57:00 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2016-10-04 22:57:00 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

[36m# test defaultAdapter
[39m
[32m# test defaultAdapter
[39m
[33m# test defaultAdapter
[39m
2016-10-04 22:57:00 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2016-10-04 22:57:00 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

[36mok 88 should be equal
ok 89 should be equal
ok 90 should be equal
ok 91 should be equal
ok 92 should be equal
ok 93 should be equal
[39m
[32mok 88 should be equal
ok 89 should be equal
ok 90 should be equal
ok 91 should be equal
ok 92 should be equal
ok 93 should be equal
[39m
[33mok 88 should be equal
ok 89 should be equal
ok 90 should be equal
[39m
[33mok 91 should be equal
[39m
[33mok 92 should be equal
ok 93 should be equal
[39m
[36mok 94 should be equal
ok 95 should be equal
# teardown
[39m
[32mok 94 should be equal
[39m
[32mok 95 should be equal
[39m
[32m# teardown
[39m
[33mok 94 should be equal
[39m
[33mok 95 should be equal
[39m
[33m# teardown
[39m
2016-10-04 22:57:00 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2016-10-04 22:57:00 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-10-04 22:57:00 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2016-10-04 22:57:00 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

[36m# enqueue and run in order
[39m
[32m# enqueue and run in order
[39m
[33m# enqueue and run in order
[39m
2016-10-04 22:57:00 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2016-10-04 22:57:00 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

[36mok 96 firstPromise setTimeout
[39m
[36mok 97 firstPromise result
ok 98 firstPromise testValue
[39m
[32mok 96 firstPromise setTimeout
ok 97 firstPromise result
ok 98 firstPromise testValue
[39m
[33mok 96 firstPromise setTimeout
ok 97 firstPromise result
ok 98 firstPromise testValue
[39m
[33mok 99 secondPromise setTimeout
ok 100 secondPromise result
ok 101 secondPromise testValue
ok 102 thirdPromise in promise
ok 103 thirdPromise result
ok 104 thirdPromise testValue
# teardown
[39m
[36mok 99 secondPromise setTimeout
ok 100 secondPromise result
ok 101 secondPromise testValue
ok 102 thirdPromise in promise
ok 103 thirdPromise result
ok 104 thirdPromise testValue
# teardown
[39m
[32mok 99 secondPromise setTimeout
[39m
[32mok 100 secondPromise result
[39m
[32mok 101 secondPromise testValue
[39m
[32mok 102 thirdPromise in promise
[39m
[32mok 103 thirdPromise result
[39m
[32mok 104 thirdPromise testValue
[39m
[32m# teardown
[39m
2016-10-04 22:57:00 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2016-10-04 22:57:00 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:00 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2016-10-04 22:57:00 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

[36m# enqueueAtTop and run backwards
[39m
[33m# enqueueAtTop and run backwards
[39m
[32m# enqueueAtTop and run backwards
[39m
2016-10-04 22:57:00 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2016-10-04 22:57:00 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

[36mok 105 thirdPromise - first to run
[39m
[36mok 106 thirdPromise - in resolve
ok 107 secondPromise - second to run
[39m
[36mok 108 secondPromise - in catch
[39m
[36mok 109 firstPromise - third to run
[39m
[36mok 110 firstPromise - in then
[39m
[36mok 111 testing promises
[39m
[36m# teardown
[39m
[32mok 105 thirdPromise - first to run
[39m
[32mok 106 thirdPromise - in resolve
[39m
[32mok 107 secondPromise - second to run
[39m
[32mok 108 secondPromise - in catch
[39m
[32mok 109 firstPromise - third to run
[39m
[32mok 110 firstPromise - in then
[39m
[32mok 111 testing promises
[39m
[32m# teardown
[39m
[33mok 105 thirdPromise - first to run
[39m
[33mok 106 thirdPromise - in resolve
[39m
[33mok 107 secondPromise - second to run
[39m
[33mok 108 secondPromise - in catch
[39m
[33mok 109 firstPromise - third to run
[39m
[33mok 110 firstPromise - in then
[39m
[33mok 111 testing promises
[39m
[33m# teardown
[39m
2016-10-04 22:57:00 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2016-10-04 22:57:00 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:00 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2016-10-04 22:57:00 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

[36m# mix enqueue and enqueueAtTop
[39m
[32m# mix enqueue and enqueueAtTop
[39m
[33m# mix enqueue and enqueueAtTop
[39m
2016-10-04 22:57:00 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2016-10-04 22:57:00 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

[36mok 112 fourth
[39m
[36mok 113 fourth
ok 114 second
[39m
[36mok 115 secondPromise - in then
[39m
[32mok 112 fourth
[39m
[32mok 113 fourth
[39m
[33mok 112 fourth
[39m
[33mok 113 fourth
[39m
[32mok 114 second
[39m
[33mok 114 second
[39m
[33mok 115 secondPromise - in then
[39m
[32mok 115 secondPromise - in then
[39m
[36mok 116 first
ok 117 firstPromise - in catch
ok 118 third
ok 119 thirdPromise - in then
ok 120 testingPromises
# teardown
[39m
[33mok 116 first
ok 117 firstPromise - in catch
ok 118 third
ok 119 thirdPromise - in then
ok 120 testingPromises
# teardown
[39m
[32mok 116 first
ok 117 firstPromise - in catch
ok 118 third
ok 119 thirdPromise - in then
ok 120 testingPromises
[39m
[32m# teardown
[39m
2016-10-04 22:57:00 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''
2016-10-04 22:57:00 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:00 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2016-10-04 22:57:00 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

[36m# queues handled independently
[39m
[33m# queues handled independently
[39m
[32m# queues handled independently
[39m
2016-10-04 22:57:00 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2016-10-04 22:57:00 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

[32mok 121 all short operations completed before the long resolves
# teardown
[39m
[33mok 121 all short operations completed before the long resolves
# teardown
[39m
[36mok 121 all short operations completed before the long resolves
# teardown
[39m
2016-10-04 22:57:01 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''
2016-10-04 22:57:01 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-10-04 22:57:01 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''
2016-10-04 22:57:01 - DEBUG UnitTestFramework: '#setup: 'basic''

[36m# basic
[39m
[32m# basic
[39m
[33m# basic
[39m
2016-10-04 22:57:01 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2016-10-04 22:57:01 - DEBUG UnitTestFramework: '#run: 'basic''

[36mok 122 sane
[39m
[36m# teardown
[39m
[33mok 122 sane
# teardown
[39m
[32mok 122 sane
[39m
[32m# teardown
[39m
2016-10-04 22:57:01 - DEBUG UnitTestFramework: '#run ok: 'basic''

2016-10-04 22:57:01 - DEBUG UnitTestFramework: '#teardown: 'basic''

[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:01 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2016-10-04 22:57:01 - DEBUG UnitTestFramework: '#setup: 'another''

[36m# another
[39m
[33m# another
[39m
[32m# another
[39m
2016-10-04 22:57:01 - DEBUG UnitTestFramework: '#setup ok: 'another''

2016-10-04 22:57:01 - DEBUG UnitTestFramework: '#run: 'another''

[36mok 123 sane
# teardown
[39m
[32mok 123 sane
[39m
[32m# teardown
[39m
[33mok 123 sane
[39m
[33m# teardown
[39m
2016-10-04 22:57:01 - DEBUG UnitTestFramework: '#run ok: 'another''

2016-10-04 22:57:01 - DEBUG UnitTestFramework: '#teardown: 'another''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:01 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2016-10-04 22:57:01 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

[36m# can pass data in setup
[39m
[33m# can pass data in setup
[39m
[32m# can pass data in setup
[39m
2016-10-04 22:57:01 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''
2016-10-04 22:57:01 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

[36mok 124 test participant has uuid
ok 125 participant data matches
ok 126 test participant has uuid
ok 127 participant data matches
ok 128 test participant has uuid
ok 129 participant data matches
ok 130 own UUID is found from the participants list
[39m
[33mok 124 test participant has uuid
ok 125 participant data matches
ok 126 test participant has uuid
ok 127 participant data matches
ok 128 test participant has uuid
ok 129 participant data matches
ok 130 own UUID is found from the participants list
# teardown
[39m
[36m# teardown
[39m
[32mok 124 test participant has uuid
ok 125 participant data matches
[39m
[32mok 126 test participant has uuid
ok 127 participant data matches
[39m
[32mok 128 test participant has uuid
[39m
[32mok 129 participant data matches
[39m
[32mok 130 own UUID is found from the participants list
[39m
[32m# teardown
[39m
2016-10-04 22:57:01 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''
2016-10-04 22:57:01 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:01 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2016-10-04 22:57:01 - DEBUG UnitTestFramework: '#setup: 'can continue after disconnect from server''

[36m# can continue after disconnect from server
[39m
[33m# can continue after disconnect from server
[39m
[32m# can continue after disconnect from server
[39m
2016-10-04 22:57:01 - DEBUG UnitTestFramework: '#setup ok: 'can continue after disconnect from server''

2016-10-04 22:57:01 - DEBUG UnitTestFramework: '#run: 'can continue after disconnect from server''

[32m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'device disconnected from the test server'
[39m
[36m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'device disconnected from the test server'
[39m
[33m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'device disconnected from the test server'
[39m
2016-10-04 22:57:01 - INFO HttpServer: 'Socket to device name: 'cc986b1f-2d4e-4e5b-aa9a-d4cd6fe46e1b' disconnected, reason: 'client namespace disconnect''

2016-10-04 22:57:01 - INFO HttpServer: 'Socket to device name: 'bbbc781e-baac-4bef-9829-b74bb5736c8c' disconnected, reason: 'client namespace disconnect''

2016-10-04 22:57:01 - INFO HttpServer: 'Socket to device name: '9528b46b-5705-40a0-9838-dff8f7e65e9b' disconnected, reason: 'client namespace disconnect''

[33m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'connected to the test server'
ok 131 got connect event
[39m
[36m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'connected to the test server'
ok 131 got connect event
[39m
[32m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'connected to the test server'
ok 131 got connect event
[39m
2016-10-04 22:57:01 - DEBUG HttpServer: 'device presented, name: '9528b46b-5705-40a0-9838-dff8f7e65e9b', uuid: 'e29be1cd-6598-4159-9efd-3b0ae002eb58', platformName: 'desktop', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-04 22:57:01 - INFO TestFramework: 'updating existing device, name: '9528b46b-5705-40a0-9838-dff8f7e65e9b', uuid: 'e29be1cd-6598-4159-9efd-3b0ae002eb58', platformName: 'desktop''

2016-10-04 22:57:01 - DEBUG HttpServer: 'device presented, name: 'bbbc781e-baac-4bef-9829-b74bb5736c8c', uuid: 'bcc38c3f-77e2-4e2b-8261-4091cb6b455b', platformName: 'desktop', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-04 22:57:01 - INFO TestFramework: 'updating existing device, name: 'bbbc781e-baac-4bef-9829-b74bb5736c8c', uuid: 'bcc38c3f-77e2-4e2b-8261-4091cb6b455b', platformName: 'desktop''

2016-10-04 22:57:01 - DEBUG HttpServer: 'device presented, name: 'cc986b1f-2d4e-4e5b-aa9a-d4cd6fe46e1b', uuid: '474d998a-c1f3-41fb-ac9d-ce41ac380a42', platformName: 'desktop', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-04 22:57:01 - INFO TestFramework: 'updating existing device, name: 'cc986b1f-2d4e-4e5b-aa9a-d4cd6fe46e1b', uuid: '474d998a-c1f3-41fb-ac9d-ce41ac380a42', platformName: 'desktop''

[33m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'device disconnected from the test server'
[39m
2016-10-04 22:57:01 - INFO HttpServer: 'Socket to device name: '9528b46b-5705-40a0-9838-dff8f7e65e9b' disconnected, reason: 'client namespace disconnect''

[36m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'device disconnected from the test server'
[39m
2016-10-04 22:57:01 - INFO HttpServer: 'Socket to device name: 'bbbc781e-baac-4bef-9829-b74bb5736c8c' disconnected, reason: 'client namespace disconnect''

[32m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'device disconnected from the test server'
[39m
2016-10-04 22:57:01 - INFO HttpServer: 'Socket to device name: 'cc986b1f-2d4e-4e5b-aa9a-d4cd6fe46e1b' disconnected, reason: 'client namespace disconnect''

[33m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'connected to the test server'
[39m
[33mok 132 got connect event
[39m
[36m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'connected to the test server'
ok 132 got connect event
[39m
2016-10-04 22:57:01 - DEBUG HttpServer: 'device presented, name: '9528b46b-5705-40a0-9838-dff8f7e65e9b', uuid: 'e29be1cd-6598-4159-9efd-3b0ae002eb58', platformName: 'desktop', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-04 22:57:01 - INFO TestFramework: 'updating existing device, name: '9528b46b-5705-40a0-9838-dff8f7e65e9b', uuid: 'e29be1cd-6598-4159-9efd-3b0ae002eb58', platformName: 'desktop''
2016-10-04 22:57:01 - DEBUG HttpServer: 'device presented, name: 'bbbc781e-baac-4bef-9829-b74bb5736c8c', uuid: 'bcc38c3f-77e2-4e2b-8261-4091cb6b455b', platformName: 'desktop', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''
2016-10-04 22:57:01 - INFO TestFramework: 'updating existing device, name: 'bbbc781e-baac-4bef-9829-b74bb5736c8c', uuid: 'bcc38c3f-77e2-4e2b-8261-4091cb6b455b', platformName: 'desktop''

[32m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'connected to the test server'
[39m
[32mok 132 got connect event
[39m
2016-10-04 22:57:01 - DEBUG HttpServer: 'device presented, name: 'cc986b1f-2d4e-4e5b-aa9a-d4cd6fe46e1b', uuid: '474d998a-c1f3-41fb-ac9d-ce41ac380a42', platformName: 'desktop', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-04 22:57:01 - INFO TestFramework: 'updating existing device, name: 'cc986b1f-2d4e-4e5b-aa9a-d4cd6fe46e1b', uuid: '474d998a-c1f3-41fb-ac9d-ce41ac380a42', platformName: 'desktop''

[33m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'device disconnected from the test server'
[39m
2016-10-04 22:57:01 - INFO HttpServer: 'Socket to device name: '9528b46b-5705-40a0-9838-dff8f7e65e9b' disconnected, reason: 'client namespace disconnect''

[32m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'device disconnected from the test server'
[39m
[36m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'device disconnected from the test server'
[39m
2016-10-04 22:57:01 - INFO HttpServer: 'Socket to device name: 'bbbc781e-baac-4bef-9829-b74bb5736c8c' disconnected, reason: 'client namespace disconnect''

2016-10-04 22:57:01 - INFO HttpServer: 'Socket to device name: 'cc986b1f-2d4e-4e5b-aa9a-d4cd6fe46e1b' disconnected, reason: 'client namespace disconnect''

[33m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'connected to the test server'
[39m
[33mok 133 got connect event
[39m
2016-10-04 22:57:01 - DEBUG HttpServer: 'device presented, name: '9528b46b-5705-40a0-9838-dff8f7e65e9b', uuid: 'e29be1cd-6598-4159-9efd-3b0ae002eb58', platformName: 'desktop', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-04 22:57:01 - INFO TestFramework: 'updating existing device, name: '9528b46b-5705-40a0-9838-dff8f7e65e9b', uuid: 'e29be1cd-6598-4159-9efd-3b0ae002eb58', platformName: 'desktop''

[36m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'connected to the test server'
ok 133 got connect event
[39m
[32m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'connected to the test server'
[39m
[32mok 133 got connect event
[39m
2016-10-04 22:57:01 - DEBUG HttpServer: 'device presented, name: 'bbbc781e-baac-4bef-9829-b74bb5736c8c', uuid: 'bcc38c3f-77e2-4e2b-8261-4091cb6b455b', platformName: 'desktop', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-04 22:57:01 - INFO TestFramework: 'updating existing device, name: 'bbbc781e-baac-4bef-9829-b74bb5736c8c', uuid: 'bcc38c3f-77e2-4e2b-8261-4091cb6b455b', platformName: 'desktop''

2016-10-04 22:57:01 - DEBUG HttpServer: 'device presented, name: 'cc986b1f-2d4e-4e5b-aa9a-d4cd6fe46e1b', uuid: '474d998a-c1f3-41fb-ac9d-ce41ac380a42', platformName: 'desktop', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-04 22:57:01 - INFO TestFramework: 'updating existing device, name: 'cc986b1f-2d4e-4e5b-aa9a-d4cd6fe46e1b', uuid: '474d998a-c1f3-41fb-ac9d-ce41ac380a42', platformName: 'desktop''

[33m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'device disconnected from the test server'
[39m
2016-10-04 22:57:01 - INFO HttpServer: 'Socket to device name: '9528b46b-5705-40a0-9838-dff8f7e65e9b' disconnected, reason: 'client namespace disconnect''

[32m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'device disconnected from the test server'
[39m
[36m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'device disconnected from the test server'
[39m
2016-10-04 22:57:01 - INFO HttpServer: 'Socket to device name: 'cc986b1f-2d4e-4e5b-aa9a-d4cd6fe46e1b' disconnected, reason: 'client namespace disconnect''
2016-10-04 22:57:01 - INFO HttpServer: 'Socket to device name: 'bbbc781e-baac-4bef-9829-b74bb5736c8c' disconnected, reason: 'client namespace disconnect''

[33m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'connected to the test server'
[39m
[33mok 134 got connect event
[39m
[32m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'connected to the test server'
ok 134 got connect event
[39m
[36m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'connected to the test server'
[39m
2016-10-04 22:57:01 - DEBUG HttpServer: 'device presented, name: '9528b46b-5705-40a0-9838-dff8f7e65e9b', uuid: 'e29be1cd-6598-4159-9efd-3b0ae002eb58', platformName: 'desktop', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''
2016-10-04 22:57:01 - INFO TestFramework: 'updating existing device, name: '9528b46b-5705-40a0-9838-dff8f7e65e9b', uuid: 'e29be1cd-6598-4159-9efd-3b0ae002eb58', platformName: 'desktop''

[36mok 134 got connect event
[39m
2016-10-04 22:57:01 - DEBUG HttpServer: 'device presented, name: 'cc986b1f-2d4e-4e5b-aa9a-d4cd6fe46e1b', uuid: '474d998a-c1f3-41fb-ac9d-ce41ac380a42', platformName: 'desktop', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-04 22:57:01 - INFO TestFramework: 'updating existing device, name: 'cc986b1f-2d4e-4e5b-aa9a-d4cd6fe46e1b', uuid: '474d998a-c1f3-41fb-ac9d-ce41ac380a42', platformName: 'desktop''

2016-10-04 22:57:01 - DEBUG HttpServer: 'device presented, name: 'bbbc781e-baac-4bef-9829-b74bb5736c8c', uuid: 'bcc38c3f-77e2-4e2b-8261-4091cb6b455b', platformName: 'desktop', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-04 22:57:01 - INFO TestFramework: 'updating existing device, name: 'bbbc781e-baac-4bef-9829-b74bb5736c8c', uuid: 'bcc38c3f-77e2-4e2b-8261-4091cb6b455b', platformName: 'desktop''

[33m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'device disconnected from the test server'
[39m
2016-10-04 22:57:01 - INFO HttpServer: 'Socket to device name: '9528b46b-5705-40a0-9838-dff8f7e65e9b' disconnected, reason: 'client namespace disconnect''

[32m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'device disconnected from the test server'
[39m
2016-10-04 22:57:01 - INFO HttpServer: 'Socket to device name: 'cc986b1f-2d4e-4e5b-aa9a-d4cd6fe46e1b' disconnected, reason: 'client namespace disconnect''

[36m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'device disconnected from the test server'
[39m
2016-10-04 22:57:01 - INFO HttpServer: 'Socket to device name: 'bbbc781e-baac-4bef-9829-b74bb5736c8c' disconnected, reason: 'client namespace disconnect''

[33m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'connected to the test server'
[39m
[33mok 135 got connect event
[39m
[32m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'connected to the test server'
[39m
[32mok 135 got connect event
[39m
[36m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'connected to the test server'
[39m
[36mok 135 got connect event
[39m
2016-10-04 22:57:01 - DEBUG HttpServer: 'device presented, name: '9528b46b-5705-40a0-9838-dff8f7e65e9b', uuid: 'e29be1cd-6598-4159-9efd-3b0ae002eb58', platformName: 'desktop', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-04 22:57:01 - INFO TestFramework: 'updating existing device, name: '9528b46b-5705-40a0-9838-dff8f7e65e9b', uuid: 'e29be1cd-6598-4159-9efd-3b0ae002eb58', platformName: 'desktop''

2016-10-04 22:57:01 - DEBUG HttpServer: 'device presented, name: 'cc986b1f-2d4e-4e5b-aa9a-d4cd6fe46e1b', uuid: '474d998a-c1f3-41fb-ac9d-ce41ac380a42', platformName: 'desktop', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-04 22:57:01 - INFO TestFramework: 'updating existing device, name: 'cc986b1f-2d4e-4e5b-aa9a-d4cd6fe46e1b', uuid: '474d998a-c1f3-41fb-ac9d-ce41ac380a42', platformName: 'desktop''

2016-10-04 22:57:01 - DEBUG HttpServer: 'device presented, name: 'bbbc781e-baac-4bef-9829-b74bb5736c8c', uuid: 'bcc38c3f-77e2-4e2b-8261-4091cb6b455b', platformName: 'desktop', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-04 22:57:01 - INFO TestFramework: 'updating existing device, name: 'bbbc781e-baac-4bef-9829-b74bb5736c8c', uuid: 'bcc38c3f-77e2-4e2b-8261-4091cb6b455b', platformName: 'desktop''

[33m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'device disconnected from the test server'
[39m
2016-10-04 22:57:01 - INFO HttpServer: 'Socket to device name: '9528b46b-5705-40a0-9838-dff8f7e65e9b' disconnected, reason: 'client namespace disconnect''

[32m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'device disconnected from the test server'
[39m
2016-10-04 22:57:01 - INFO HttpServer: 'Socket to device name: 'cc986b1f-2d4e-4e5b-aa9a-d4cd6fe46e1b' disconnected, reason: 'client namespace disconnect''

[36m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'device disconnected from the test server'
[39m
2016-10-04 22:57:01 - INFO HttpServer: 'Socket to device name: 'bbbc781e-baac-4bef-9829-b74bb5736c8c' disconnected, reason: 'client namespace disconnect''

[33m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'connected to the test server'
[39m
[33mok 136 got connect event
[39m
2016-10-04 22:57:01 - DEBUG HttpServer: 'device presented, name: '9528b46b-5705-40a0-9838-dff8f7e65e9b', uuid: 'e29be1cd-6598-4159-9efd-3b0ae002eb58', platformName: 'desktop', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-04 22:57:01 - INFO TestFramework: 'updating existing device, name: '9528b46b-5705-40a0-9838-dff8f7e65e9b', uuid: 'e29be1cd-6598-4159-9efd-3b0ae002eb58', platformName: 'desktop''

[32m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'connected to the test server'
ok 136 got connect event
[39m
[36m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'connected to the test server'
[39m
[36mok 136 got connect event
[39m
2016-10-04 22:57:01 - DEBUG HttpServer: 'device presented, name: 'cc986b1f-2d4e-4e5b-aa9a-d4cd6fe46e1b', uuid: '474d998a-c1f3-41fb-ac9d-ce41ac380a42', platformName: 'desktop', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-04 22:57:01 - INFO TestFramework: 'updating existing device, name: 'cc986b1f-2d4e-4e5b-aa9a-d4cd6fe46e1b', uuid: '474d998a-c1f3-41fb-ac9d-ce41ac380a42', platformName: 'desktop''

2016-10-04 22:57:01 - DEBUG HttpServer: 'device presented, name: 'bbbc781e-baac-4bef-9829-b74bb5736c8c', uuid: 'bcc38c3f-77e2-4e2b-8261-4091cb6b455b', platformName: 'desktop', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-04 22:57:01 - INFO TestFramework: 'updating existing device, name: 'bbbc781e-baac-4bef-9829-b74bb5736c8c', uuid: 'bcc38c3f-77e2-4e2b-8261-4091cb6b455b', platformName: 'desktop''

[33m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'device disconnected from the test server'
[39m
2016-10-04 22:57:01 - INFO HttpServer: 'Socket to device name: '9528b46b-5705-40a0-9838-dff8f7e65e9b' disconnected, reason: 'client namespace disconnect''

[32m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'device disconnected from the test server'
[39m
2016-10-04 22:57:01 - INFO HttpServer: 'Socket to device name: 'cc986b1f-2d4e-4e5b-aa9a-d4cd6fe46e1b' disconnected, reason: 'client namespace disconnect''

[36m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'device disconnected from the test server'
[39m
2016-10-04 22:57:01 - INFO HttpServer: 'Socket to device name: 'bbbc781e-baac-4bef-9829-b74bb5736c8c' disconnected, reason: 'client namespace disconnect''

[33m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'connected to the test server'
[39m
[33mok 137 got connect event
[39m
2016-10-04 22:57:01 - DEBUG HttpServer: 'device presented, name: '9528b46b-5705-40a0-9838-dff8f7e65e9b', uuid: 'e29be1cd-6598-4159-9efd-3b0ae002eb58', platformName: 'desktop', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-04 22:57:01 - INFO TestFramework: 'updating existing device, name: '9528b46b-5705-40a0-9838-dff8f7e65e9b', uuid: 'e29be1cd-6598-4159-9efd-3b0ae002eb58', platformName: 'desktop''

[32m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'connected to the test server'
[39m
[32mok 137 got connect event
[39m
[36m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'connected to the test server'
[39m
[36mok 137 got connect event
[39m
2016-10-04 22:57:01 - DEBUG HttpServer: 'device presented, name: 'cc986b1f-2d4e-4e5b-aa9a-d4cd6fe46e1b', uuid: '474d998a-c1f3-41fb-ac9d-ce41ac380a42', platformName: 'desktop', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-04 22:57:01 - INFO TestFramework: 'updating existing device, name: 'cc986b1f-2d4e-4e5b-aa9a-d4cd6fe46e1b', uuid: '474d998a-c1f3-41fb-ac9d-ce41ac380a42', platformName: 'desktop''

2016-10-04 22:57:01 - DEBUG HttpServer: 'device presented, name: 'bbbc781e-baac-4bef-9829-b74bb5736c8c', uuid: 'bcc38c3f-77e2-4e2b-8261-4091cb6b455b', platformName: 'desktop', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-04 22:57:01 - INFO TestFramework: 'updating existing device, name: 'bbbc781e-baac-4bef-9829-b74bb5736c8c', uuid: 'bcc38c3f-77e2-4e2b-8261-4091cb6b455b', platformName: 'desktop''

[33m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'device disconnected from the test server'
[39m
2016-10-04 22:57:01 - INFO HttpServer: 'Socket to device name: '9528b46b-5705-40a0-9838-dff8f7e65e9b' disconnected, reason: 'client namespace disconnect''

[32m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'device disconnected from the test server'
[39m
2016-10-04 22:57:01 - INFO HttpServer: 'Socket to device name: 'cc986b1f-2d4e-4e5b-aa9a-d4cd6fe46e1b' disconnected, reason: 'client namespace disconnect''

[36m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'device disconnected from the test server'
[39m
2016-10-04 22:57:01 - INFO HttpServer: 'Socket to device name: 'bbbc781e-baac-4bef-9829-b74bb5736c8c' disconnected, reason: 'client namespace disconnect''

[33m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'connected to the test server'
[39m
[33mok 138 got connect event
[39m
2016-10-04 22:57:01 - DEBUG HttpServer: 'device presented, name: '9528b46b-5705-40a0-9838-dff8f7e65e9b', uuid: 'e29be1cd-6598-4159-9efd-3b0ae002eb58', platformName: 'desktop', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-04 22:57:01 - INFO TestFramework: 'updating existing device, name: '9528b46b-5705-40a0-9838-dff8f7e65e9b', uuid: 'e29be1cd-6598-4159-9efd-3b0ae002eb58', platformName: 'desktop''

[32m2016-10-04 22:57:01 - DEBUG CoordinatedClient: 'connected to the test server'
[39m
[32mok 138 got connect event
[39m
2016-10-04 22:57:01 - DEBUG HttpServer: 'device presented, name: 'cc986b1f-2d4e-4e5b-aa9a-d4cd6fe46e1b', uuid: '474d998a-c1f3-41fb-ac9d-ce41ac380a42', platformName: 'desktop', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-04 22:57:01 - INFO TestFramework: 'updating existing device, name: 'cc986b1f-2d4e-4e5b-aa9a-d4cd6fe46e1b', uuid: '474d998a-c1f3-41fb-ac9d-ce41ac380a42', platformName: 'desktop''

[36m2016-10-04 22:57:02 - DEBUG CoordinatedClient: 'connected to the test server'
[39m
[36mok 138 got connect event
[39m
2016-10-04 22:57:02 - DEBUG HttpServer: 'device presented, name: 'bbbc781e-baac-4bef-9829-b74bb5736c8c', uuid: 'bcc38c3f-77e2-4e2b-8261-4091cb6b455b', platformName: 'desktop', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''
2016-10-04 22:57:02 - INFO TestFramework: 'updating existing device, name: 'bbbc781e-baac-4bef-9829-b74bb5736c8c', uuid: 'bcc38c3f-77e2-4e2b-8261-4091cb6b455b', platformName: 'desktop''

[33m2016-10-04 22:57:02 - DEBUG CoordinatedClient: 'device disconnected from the test server'
[39m
2016-10-04 22:57:02 - INFO HttpServer: 'Socket to device name: '9528b46b-5705-40a0-9838-dff8f7e65e9b' disconnected, reason: 'client namespace disconnect''

[32m2016-10-04 22:57:02 - DEBUG CoordinatedClient: 'device disconnected from the test server'
[39m
2016-10-04 22:57:02 - INFO HttpServer: 'Socket to device name: 'cc986b1f-2d4e-4e5b-aa9a-d4cd6fe46e1b' disconnected, reason: 'client namespace disconnect''

[36m2016-10-04 22:57:02 - DEBUG CoordinatedClient: 'device disconnected from the test server'
[39m
2016-10-04 22:57:02 - INFO HttpServer: 'Socket to device name: 'bbbc781e-baac-4bef-9829-b74bb5736c8c' disconnected, reason: 'client namespace disconnect''

[33m2016-10-04 22:57:02 - DEBUG CoordinatedClient: 'connected to the test server'
[39m
[33mok 139 got connect event
[39m
[33m# teardown
[39m
2016-10-04 22:57:02 - DEBUG HttpServer: 'device presented, name: '9528b46b-5705-40a0-9838-dff8f7e65e9b', uuid: 'e29be1cd-6598-4159-9efd-3b0ae002eb58', platformName: 'desktop', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-04 22:57:02 - INFO TestFramework: 'updating existing device, name: '9528b46b-5705-40a0-9838-dff8f7e65e9b', uuid: 'e29be1cd-6598-4159-9efd-3b0ae002eb58', platformName: 'desktop''

[32m2016-10-04 22:57:02 - DEBUG CoordinatedClient: 'connected to the test server'
[39m
[32mok 139 got connect event
[39m
[32m# teardown
[39m
2016-10-04 22:57:02 - DEBUG HttpServer: 'device presented, name: 'cc986b1f-2d4e-4e5b-aa9a-d4cd6fe46e1b', uuid: '474d998a-c1f3-41fb-ac9d-ce41ac380a42', platformName: 'desktop', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-04 22:57:02 - INFO TestFramework: 'updating existing device, name: 'cc986b1f-2d4e-4e5b-aa9a-d4cd6fe46e1b', uuid: '474d998a-c1f3-41fb-ac9d-ce41ac380a42', platformName: 'desktop''

[36m2016-10-04 22:57:02 - DEBUG CoordinatedClient: 'connected to the test server'
[39m
[36mok 139 got connect event
[39m
[36m# teardown
[39m
2016-10-04 22:57:02 - DEBUG HttpServer: 'device presented, name: 'bbbc781e-baac-4bef-9829-b74bb5736c8c', uuid: 'bcc38c3f-77e2-4e2b-8261-4091cb6b455b', platformName: 'desktop', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-04 22:57:02 - INFO TestFramework: 'updating existing device, name: 'bbbc781e-baac-4bef-9829-b74bb5736c8c', uuid: 'bcc38c3f-77e2-4e2b-8261-4091cb6b455b', platformName: 'desktop''

2016-10-04 22:57:02 - DEBUG UnitTestFramework: '#run ok: 'can continue after disconnect from server''
2016-10-04 22:57:02 - DEBUG UnitTestFramework: '#teardown: 'can continue after disconnect from server''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:02 - DEBUG UnitTestFramework: '#teardown ok: 'can continue after disconnect from server''

2016-10-04 22:57:02 - DEBUG UnitTestFramework: '#setup: 'test after disconnect''

[36m# test after disconnect
[39m
[32m# test after disconnect
[39m
[33m# test after disconnect
[39m
2016-10-04 22:57:02 - DEBUG UnitTestFramework: '#setup ok: 'test after disconnect''
2016-10-04 22:57:02 - DEBUG UnitTestFramework: '#run: 'test after disconnect''

[36mok 140 worked
# teardown
[39m
[32mok 140 worked
# teardown
[39m
[33mok 140 worked
# teardown
[39m
2016-10-04 22:57:02 - DEBUG UnitTestFramework: '#run ok: 'test after disconnect''

2016-10-04 22:57:02 - DEBUG UnitTestFramework: '#teardown: 'test after disconnect''

[33m2016-10-04 22:57:02 - DEBUG CoordinatedClient: 'device disconnected from the test server'
[39m
2016-10-04 22:57:02 - INFO HttpServer: 'Socket to device name: '9528b46b-5705-40a0-9838-dff8f7e65e9b' disconnected, reason: 'client namespace disconnect''

[32m# setup
[39m
[36m# setup
[39m
[32m2016-10-04 22:57:02 - DEBUG CoordinatedClient: 'device disconnected from the test server'
[39m
2016-10-04 22:57:02 - INFO HttpServer: 'Socket to device name: 'cc986b1f-2d4e-4e5b-aa9a-d4cd6fe46e1b' disconnected, reason: 'client namespace disconnect''

[36m2016-10-04 22:57:02 - DEBUG CoordinatedClient: 'device disconnected from the test server'
[39m
2016-10-04 22:57:02 - INFO HttpServer: 'Socket to device name: 'bbbc781e-baac-4bef-9829-b74bb5736c8c' disconnected, reason: 'client namespace disconnect''

[33m2016-10-04 22:57:02 - DEBUG CoordinatedClient: 'connected to the test server'
[39m
2016-10-04 22:57:02 - DEBUG HttpServer: 'device presented, name: '9528b46b-5705-40a0-9838-dff8f7e65e9b', uuid: 'e29be1cd-6598-4159-9efd-3b0ae002eb58', platformName: 'desktop', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-04 22:57:02 - INFO TestFramework: 'updating existing device, name: '9528b46b-5705-40a0-9838-dff8f7e65e9b', uuid: 'e29be1cd-6598-4159-9efd-3b0ae002eb58', platformName: 'desktop''

[33m# setup
[39m
2016-10-04 22:57:02 - DEBUG UnitTestFramework: '#teardown ok: 'test after disconnect''
2016-10-04 22:57:02 - DEBUG UnitTestFramework: '#setup: 'test thali manager spies''

[33m# test thali manager spies
[39m
[32m2016-10-04 22:57:02 - DEBUG CoordinatedClient: 'connected to the test server'
[39m
2016-10-04 22:57:02 - DEBUG HttpServer: 'device presented, name: 'cc986b1f-2d4e-4e5b-aa9a-d4cd6fe46e1b', uuid: '474d998a-c1f3-41fb-ac9d-ce41ac380a42', platformName: 'desktop', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-04 22:57:02 - INFO TestFramework: 'updating existing device, name: 'cc986b1f-2d4e-4e5b-aa9a-d4cd6fe46e1b', uuid: '474d998a-c1f3-41fb-ac9d-ce41ac380a42', platformName: 'desktop''

[32m# test thali manager spies
[39m
[36m2016-10-04 22:57:02 - DEBUG CoordinatedClient: 'connected to the test server'
[39m
2016-10-04 22:57:02 - DEBUG HttpServer: 'device presented, name: 'bbbc781e-baac-4bef-9829-b74bb5736c8c', uuid: 'bcc38c3f-77e2-4e2b-8261-4091cb6b455b', platformName: 'desktop', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-04 22:57:02 - INFO TestFramework: 'updating existing device, name: 'bbbc781e-baac-4bef-9829-b74bb5736c8c', uuid: 'bcc38c3f-77e2-4e2b-8261-4091cb6b455b', platformName: 'desktop''

[36m# test thali manager spies
[39m
2016-10-04 22:57:02 - DEBUG UnitTestFramework: '#setup ok: 'test thali manager spies''

2016-10-04 22:57:02 - DEBUG UnitTestFramework: '#run: 'test thali manager spies''

[36m2016-10-04 22:57:02 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
2016-10-04 22:57:02 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
2016-10-04 22:57:02 - DEBUG thaliManager: 'creating express pouchdb instance'
[39m
[36mok 141 expressPouchDB was called once
ok 142 expressPouchDB was called with 2 arguments
ok 143 expressPouchDB was called with 'PouchDB' as 1-st argument
ok 144 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
ok 145 PouchDB was called once
ok 146 PouchDB was called with 1 arguments
ok 147 PouchDB was called with 'dbName' as 1-st argument
ok 148 ThaliSendNotificationBasedOnReplication was called once
ok 149 ThaliSendNotificationBasedOnReplication was called with 4 arguments
ok 150 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
ok 151 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
ok 152 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
ok 153 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
ok 154 ThaliPullReplicationFromNotification was called once
ok 155 ThaliPullReplicationFromNotification was called with 4 arguments
ok 156 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
ok 157 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
ok 158 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
ok 159 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
ok 160 Salti was called once
ok 161 Salti was called with 4 arguments
ok 162 Salti was called with 'dbName' as 1-st argument
ok 163 Salti was called with 'acl' as 2-st argument
ok 164 Salti was called with 'thaliIdCallback' as 3-st argument
ok 165 Salti was called with 'options' as 4-st argument
2016-10-04 22:57:02 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-10-04 22:57:02 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-10-04 22:57:02 - DEBUG thaliManager: 'starting ThaliMobile'
2016-10-04 22:57:02 - DEBUG thaliManager: 'start listening for advertisements'
2016-10-04 22:57:02 - DEBUG thaliManager: 'start update advertising and listening'
2016-10-04 22:57:02 - DEBUG thaliWifiInfrastructure: 'listening 50974'
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
2016-10-04 22:57:02 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
2016-10-04 22:57:02 - DEBUG thaliManager: 'creating express pouchdb instance'
ok 141 expressPouchDB was called once
ok 142 expressPouchDB was called with 2 arguments
ok 143 expressPouchDB was called with 'PouchDB' as 1-st argument
ok 144 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
ok 145 PouchDB was called once
ok 146 PouchDB was called with 1 arguments
ok 147 PouchDB was called with 'dbName' as 1-st argument
ok 148 ThaliSendNotificationBasedOnReplication was called once
ok 149 ThaliSendNotificationBasedOnReplication was called with 4 arguments
ok 150 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
ok 151 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
ok 152 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
ok 153 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
[39m
[33m2016-10-04 22:57:02 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
2016-10-04 22:57:02 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
2016-10-04 22:57:02 - DEBUG thaliManager: 'creating express pouchdb instance'
ok 141 expressPouchDB was called once
ok 142 expressPouchDB was called with 2 arguments
ok 143 expressPouchDB was called with 'PouchDB' as 1-st argument
ok 144 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
ok 145 PouchDB was called once
ok 146 PouchDB was called with 1 arguments
ok 147 PouchDB was called with 'dbName' as 1-st argument
ok 148 ThaliSendNotificationBasedOnReplication was called once
ok 149 ThaliSendNotificationBasedOnReplication was called with 4 arguments
ok 150 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
ok 151 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
ok 152 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
ok 153 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
ok 154 ThaliPullReplicationFromNotification was called once
ok 155 ThaliPullReplicationFromNotification was called with 4 arguments
ok 156 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
ok 157 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
ok 158 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
ok 159 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
ok 160 Salti was called once
ok 161 Salti was called with 4 arguments
ok 162 Salti was called with 'dbName' as 1-st argument
ok 163 Salti was called with 'acl' as 2-st argument
ok 164 Salti was called with 'thaliIdCallback' as 3-st argument
ok 165 Salti was called with 'options' as 4-st argument
2016-10-04 22:57:02 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-10-04 22:57:02 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
[39m
[36m2016-10-04 22:57:02 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
ok 166 ThaliMobile.start was called once
ok 167 ThaliMobile.start was called with 3 arguments
ok 168 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
ok 169 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
ok 170 ThaliMobile.start was called with 'networkType' as 3-st argument
ok 171 ThaliMobile.startListeningForAdvertisements was called once
ok 172 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
ok 173 ThaliMobile.startUpdateAdvertisingAndListening was called once
ok 174 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
ok 175 ThaliSendNotificationBasedOnReplication.prototype.start was called once
ok 176 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
ok 177 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
ok 178 ThaliPullReplicationFromNotification.prototype.start was called once
ok 179 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
ok 180 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping advertising and listening'
2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping ThaliMobile'
ok 181 ThaliMobile.stop was called once
ok 182 ThaliMobile.stop was called with 0 arguments
ok 183 ThaliMobile.stopListeningForAdvertisements was called once
ok 184 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
ok 185 ThaliMobile.stopAdvertisingAndListening was called once
ok 186 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
ok 187 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
ok 188 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
ok 189 ThaliPullReplicationFromNotification.prototype.stop was called once
ok 190 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
[39m
[33m2016-10-04 22:57:02 - DEBUG thaliManager: 'starting ThaliMobile'
[39m
[36m# teardown
[39m
[32mok 154 ThaliPullReplicationFromNotification was called once
ok 155 ThaliPullReplicationFromNotification was called with 4 arguments
ok 156 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
ok 157 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
ok 158 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
[39m
[33m2016-10-04 22:57:02 - DEBUG thaliManager: 'start listening for advertisements'
[39m
[32mok 159 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
[39m
[32mok 160 Salti was called once
ok 161 Salti was called with 4 arguments
ok 162 Salti was called with 'dbName' as 1-st argument
ok 163 Salti was called with 'acl' as 2-st argument
ok 164 Salti was called with 'thaliIdCallback' as 3-st argument
ok 165 Salti was called with 'options' as 4-st argument
2016-10-04 22:57:02 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-10-04 22:57:02 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
[39m
[33m2016-10-04 22:57:02 - DEBUG thaliManager: 'start update advertising and listening'
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliManager: 'starting ThaliMobile'
[39m
[33m2016-10-04 22:57:02 - DEBUG thaliWifiInfrastructure: 'listening 50975'
[39m
[33m2016-10-04 22:57:02 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
[39m
[33mok 166 ThaliMobile.start was called once
ok 167 ThaliMobile.start was called with 3 arguments
ok 168 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
[39m
[33mok 169 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
[39m
[33mok 170 ThaliMobile.start was called with 'networkType' as 3-st argument
[39m
[33mok 171 ThaliMobile.startListeningForAdvertisements was called once
[39m
[33mok 172 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
[39m
[33mok 173 ThaliMobile.startUpdateAdvertisingAndListening was called once
[39m
[33mok 174 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
[39m
[33mok 175 ThaliSendNotificationBasedOnReplication.prototype.start was called once
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliManager: 'start listening for advertisements'
[39m
[33mok 176 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
[39m
[33mok 177 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
[39m
[33mok 178 ThaliPullReplicationFromNotification.prototype.start was called once
[39m
[33mok 179 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
[39m
[33mok 180 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
[39m
[33m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliManager: 'start update advertising and listening'
[39m
[33m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping advertising and listening'
[39m
[33m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping listening for advertisements'
[39m
[33m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping ThaliMobile'
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliWifiInfrastructure: 'listening 50976'
[39m
[33mok 181 ThaliMobile.stop was called once
[39m
[33mok 182 ThaliMobile.stop was called with 0 arguments
[39m
[33mok 183 ThaliMobile.stopListeningForAdvertisements was called once
[39m
[33mok 184 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
[39m
[33mok 185 ThaliMobile.stopAdvertisingAndListening was called once
ok 186 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
ok 187 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
ok 188 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
ok 189 ThaliPullReplicationFromNotification.prototype.stop was called once
ok 190 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
[39m
[33m# teardown
[39m
[32mok 166 ThaliMobile.start was called once
ok 167 ThaliMobile.start was called with 3 arguments
ok 168 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
[39m
[32mok 169 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
[39m
[32mok 170 ThaliMobile.start was called with 'networkType' as 3-st argument
[39m
[32mok 171 ThaliMobile.startListeningForAdvertisements was called once
[39m
[32mok 172 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
[39m
[32mok 173 ThaliMobile.startUpdateAdvertisingAndListening was called once
[39m
[32mok 174 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
[39m
[32mok 175 ThaliSendNotificationBasedOnReplication.prototype.start was called once
[39m
[32mok 176 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
[39m
[32mok 177 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
[39m
[32mok 178 ThaliPullReplicationFromNotification.prototype.start was called once
[39m
[32mok 179 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
[39m
[32mok 180 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping advertising and listening'
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping listening for advertisements'
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping ThaliMobile'
[39m
[32mok 181 ThaliMobile.stop was called once
[39m
[32mok 182 ThaliMobile.stop was called with 0 arguments
[39m
[32mok 183 ThaliMobile.stopListeningForAdvertisements was called once
[39m
[32mok 184 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
[39m
[32mok 185 ThaliMobile.stopAdvertisingAndListening was called once
[39m
[32mok 186 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
[39m
[32mok 187 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
[39m
[32mok 188 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
[39m
[32mok 189 ThaliPullReplicationFromNotification.prototype.stop was called once
[39m
[32mok 190 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
[39m
2016-10-04 22:57:02 - DEBUG UnitTestFramework: '#run ok: 'test thali manager spies''
2016-10-04 22:57:02 - DEBUG UnitTestFramework: '#teardown: 'test thali manager spies''

[32m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-10-04 22:57:02 - DEBUG UnitTestFramework: '#teardown ok: 'test thali manager spies''
2016-10-04 22:57:02 - DEBUG UnitTestFramework: '#setup: 'test thali manager multiple starts and stops''

[33m# test thali manager multiple starts and stops
[39m
[32m# test thali manager multiple starts and stops
[39m
[36m# test thali manager multiple starts and stops
[39m
2016-10-04 22:57:02 - DEBUG UnitTestFramework: '#setup ok: 'test thali manager multiple starts and stops''

2016-10-04 22:57:02 - DEBUG UnitTestFramework: '#run: 'test thali manager multiple starts and stops''

[33m2016-10-04 22:57:02 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
[39m
[36m2016-10-04 22:57:02 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
[39m
[36m2016-10-04 22:57:02 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
[39m
[36m2016-10-04 22:57:02 - DEBUG thaliManager: 'creating express pouchdb instance'
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
[39m
[36mok 191 expressPouchDB was called once
ok 192 expressPouchDB was called with 2 arguments
ok 193 expressPouchDB was called with 'PouchDB' as 1-st argument
ok 194 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
ok 195 PouchDB was called once
ok 196 PouchDB was called with 1 arguments
ok 197 PouchDB was called with 'dbName' as 1-st argument
ok 198 ThaliSendNotificationBasedOnReplication was called once
ok 199 ThaliSendNotificationBasedOnReplication was called with 4 arguments
ok 200 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
ok 201 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
ok 202 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
ok 203 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
ok 204 ThaliPullReplicationFromNotification was called once
ok 205 ThaliPullReplicationFromNotification was called with 4 arguments
ok 206 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
[39m
[36mok 207 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
ok 208 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
ok 209 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
[39m
[36mok 210 Salti was called once
ok 211 Salti was called with 4 arguments
[39m
[36mok 212 Salti was called with 'dbName' as 1-st argument
[39m
[36mok 213 Salti was called with 'acl' as 2-st argument
ok 214 Salti was called with 'thaliIdCallback' as 3-st argument
ok 215 Salti was called with 'options' as 4-st argument
[39m
[36m2016-10-04 22:57:02 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-10-04 22:57:02 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-10-04 22:57:02 - DEBUG thaliManager: 'starting ThaliMobile'
2016-10-04 22:57:02 - DEBUG thaliManager: 'start listening for advertisements'
2016-10-04 22:57:02 - DEBUG thaliManager: 'start update advertising and listening'
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
2016-10-04 22:57:02 - DEBUG thaliManager: 'creating express pouchdb instance'
[39m
[36m2016-10-04 22:57:02 - DEBUG thaliWifiInfrastructure: 'listening 50977'
[39m
[36m2016-10-04 22:57:02 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
[39m
[36mok 216 ThaliMobile.start was called once
ok 217 ThaliMobile.start was called with 3 arguments
ok 218 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
ok 219 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
ok 220 ThaliMobile.start was called with 'networkType' as 3-st argument
ok 221 ThaliMobile.startListeningForAdvertisements was called once
ok 222 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
ok 223 ThaliMobile.startUpdateAdvertisingAndListening was called once
ok 224 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
ok 225 ThaliSendNotificationBasedOnReplication.prototype.start was called once
ok 226 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
ok 227 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
ok 228 ThaliPullReplicationFromNotification.prototype.start was called once
ok 229 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
ok 230 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
[39m
[32mok 191 expressPouchDB was called once
ok 192 expressPouchDB was called with 2 arguments
ok 193 expressPouchDB was called with 'PouchDB' as 1-st argument
ok 194 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
ok 195 PouchDB was called once
ok 196 PouchDB was called with 1 arguments
ok 197 PouchDB was called with 'dbName' as 1-st argument
ok 198 ThaliSendNotificationBasedOnReplication was called once
ok 199 ThaliSendNotificationBasedOnReplication was called with 4 arguments
ok 200 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
ok 201 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
ok 202 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
ok 203 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
ok 204 ThaliPullReplicationFromNotification was called once
ok 205 ThaliPullReplicationFromNotification was called with 4 arguments
ok 206 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
ok 207 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
ok 208 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
ok 209 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
ok 210 Salti was called once
ok 211 Salti was called with 4 arguments
ok 212 Salti was called with 'dbName' as 1-st argument
ok 213 Salti was called with 'acl' as 2-st argument
ok 214 Salti was called with 'thaliIdCallback' as 3-st argument
ok 215 Salti was called with 'options' as 4-st argument
2016-10-04 22:57:02 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-10-04 22:57:02 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
[39m
[36m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping advertising and listening'
2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping listening for advertisements'
[39m
[36m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping ThaliMobile'
[39m
[36mok 231 ThaliMobile.stop was called once
[39m
[36mok 232 ThaliMobile.stop was called with 0 arguments
[39m
[36mok 233 ThaliMobile.stopListeningForAdvertisements was called once
[39m
[36mok 234 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
ok 235 ThaliMobile.stopAdvertisingAndListening was called once
[39m
[36mok 236 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
[39m
[36mok 237 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
[39m
[36mok 238 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
ok 239 ThaliPullReplicationFromNotification.prototype.stop was called once
[39m
[36mok 240 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
[39m
[36m2016-10-04 22:57:02 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
[39m
[36m2016-10-04 22:57:02 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
[39m
[36m2016-10-04 22:57:02 - DEBUG thaliManager: 'starting ThaliMobile'
[39m
[36m2016-10-04 22:57:02 - DEBUG thaliManager: 'start listening for advertisements'
[39m
[36m2016-10-04 22:57:02 - DEBUG thaliManager: 'start update advertising and listening'
[39m
[36m2016-10-04 22:57:02 - DEBUG thaliWifiInfrastructure: 'listening 50978'
2016-10-04 22:57:02 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
[39m
[36m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
[39m
[36m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
[39m
[36m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping advertising and listening'
[39m
[36m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping listening for advertisements'
[39m
[36m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping ThaliMobile'
[39m
[36m2016-10-04 22:57:02 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-10-04 22:57:02 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
[39m
[36m2016-10-04 22:57:02 - DEBUG thaliManager: 'starting ThaliMobile'
2016-10-04 22:57:02 - DEBUG thaliManager: 'start listening for advertisements'
2016-10-04 22:57:02 - DEBUG thaliManager: 'start update advertising and listening'
2016-10-04 22:57:02 - DEBUG thaliWifiInfrastructure: 'listening 50979'
2016-10-04 22:57:02 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
[39m
[33m2016-10-04 22:57:02 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
2016-10-04 22:57:02 - DEBUG thaliManager: 'creating express pouchdb instance'
[39m
[33mok 191 expressPouchDB was called once
ok 192 expressPouchDB was called with 2 arguments
ok 193 expressPouchDB was called with 'PouchDB' as 1-st argument
ok 194 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
ok 195 PouchDB was called once
ok 196 PouchDB was called with 1 arguments
ok 197 PouchDB was called with 'dbName' as 1-st argument
ok 198 ThaliSendNotificationBasedOnReplication was called once
ok 199 ThaliSendNotificationBasedOnReplication was called with 4 arguments
ok 200 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
ok 201 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
ok 202 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
ok 203 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
ok 204 ThaliPullReplicationFromNotification was called once
ok 205 ThaliPullReplicationFromNotification was called with 4 arguments
ok 206 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
ok 207 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
ok 208 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
ok 209 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
ok 210 Salti was called once
ok 211 Salti was called with 4 arguments
ok 212 Salti was called with 'dbName' as 1-st argument
ok 213 Salti was called with 'acl' as 2-st argument
ok 214 Salti was called with 'thaliIdCallback' as 3-st argument
ok 215 Salti was called with 'options' as 4-st argument
2016-10-04 22:57:02 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-10-04 22:57:02 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
[39m
[36m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping advertising and listening'
[39m
[33m2016-10-04 22:57:02 - DEBUG thaliManager: 'starting ThaliMobile'
2016-10-04 22:57:02 - DEBUG thaliManager: 'start listening for advertisements'
2016-10-04 22:57:02 - DEBUG thaliManager: 'start update advertising and listening'
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliManager: 'starting ThaliMobile'
2016-10-04 22:57:02 - DEBUG thaliManager: 'start listening for advertisements'
2016-10-04 22:57:02 - DEBUG thaliManager: 'start update advertising and listening'
2016-10-04 22:57:02 - DEBUG thaliWifiInfrastructure: 'listening 50980'
2016-10-04 22:57:02 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
[39m
[32mok 216 ThaliMobile.start was called once
ok 217 ThaliMobile.start was called with 3 arguments
ok 218 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
ok 219 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
ok 220 ThaliMobile.start was called with 'networkType' as 3-st argument
ok 221 ThaliMobile.startListeningForAdvertisements was called once
ok 222 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
ok 223 ThaliMobile.startUpdateAdvertisingAndListening was called once
ok 224 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
ok 225 ThaliSendNotificationBasedOnReplication.prototype.start was called once
ok 226 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
ok 227 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
ok 228 ThaliPullReplicationFromNotification.prototype.start was called once
ok 229 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
ok 230 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping advertising and listening'
[39m
[33m2016-10-04 22:57:02 - DEBUG thaliWifiInfrastructure: 'listening 50981'
[39m
[33m2016-10-04 22:57:02 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping ThaliMobile'
[39m
[32mok 231 ThaliMobile.stop was called once
ok 232 ThaliMobile.stop was called with 0 arguments
ok 233 ThaliMobile.stopListeningForAdvertisements was called once
ok 234 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
ok 235 ThaliMobile.stopAdvertisingAndListening was called once
[39m
[32mok 236 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
ok 237 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
[39m
[32mok 238 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
[39m
[32mok 239 ThaliPullReplicationFromNotification.prototype.stop was called once
ok 240 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
2016-10-04 22:57:02 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-10-04 22:57:02 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliManager: 'starting ThaliMobile'
2016-10-04 22:57:02 - DEBUG thaliManager: 'start listening for advertisements'
2016-10-04 22:57:02 - DEBUG thaliManager: 'start update advertising and listening'
[39m
[33mok 216 ThaliMobile.start was called once
ok 217 ThaliMobile.start was called with 3 arguments
ok 218 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
ok 219 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
ok 220 ThaliMobile.start was called with 'networkType' as 3-st argument
ok 221 ThaliMobile.startListeningForAdvertisements was called once
ok 222 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
ok 223 ThaliMobile.startUpdateAdvertisingAndListening was called once
ok 224 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
ok 225 ThaliSendNotificationBasedOnReplication.prototype.start was called once
ok 226 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
ok 227 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
ok 228 ThaliPullReplicationFromNotification.prototype.start was called once
ok 229 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
ok 230 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping advertising and listening'
2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping ThaliMobile'
[39m
[36m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping ThaliMobile'
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliWifiInfrastructure: 'listening 50983'
[39m
[33mok 231 ThaliMobile.stop was called once
ok 232 ThaliMobile.stop was called with 0 arguments
ok 233 ThaliMobile.stopListeningForAdvertisements was called once
ok 234 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
ok 235 ThaliMobile.stopAdvertisingAndListening was called once
ok 236 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
ok 237 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
ok 238 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
ok 239 ThaliPullReplicationFromNotification.prototype.stop was called once
ok 240 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
2016-10-04 22:57:02 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-10-04 22:57:02 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-10-04 22:57:02 - DEBUG thaliManager: 'starting ThaliMobile'
2016-10-04 22:57:02 - DEBUG thaliManager: 'start listening for advertisements'
2016-10-04 22:57:02 - DEBUG thaliManager: 'start update advertising and listening'
2016-10-04 22:57:02 - DEBUG thaliWifiInfrastructure: 'listening 50984'
2016-10-04 22:57:02 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping advertising and listening'
[39m
[36m2016-10-04 22:57:02 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-10-04 22:57:02 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-10-04 22:57:02 - DEBUG thaliManager: 'starting ThaliMobile'
2016-10-04 22:57:02 - DEBUG thaliManager: 'start listening for advertisements'
2016-10-04 22:57:02 - DEBUG thaliManager: 'start update advertising and listening'
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping advertising and listening'
[39m
[33m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping listening for advertisements'
[39m
[33m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping ThaliMobile'
2016-10-04 22:57:02 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-10-04 22:57:02 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-10-04 22:57:02 - DEBUG thaliManager: 'starting ThaliMobile'
2016-10-04 22:57:02 - DEBUG thaliManager: 'start listening for advertisements'
2016-10-04 22:57:02 - DEBUG thaliManager: 'start update advertising and listening'
[39m
[36m2016-10-04 22:57:02 - DEBUG thaliWifiInfrastructure: 'listening 50985'
2016-10-04 22:57:02 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
ok 241 ThaliMobile.start was called once
ok 242 ThaliMobile.start was called with 3 arguments
ok 243 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
ok 244 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
ok 245 ThaliMobile.start was called with 'networkType' as 3-st argument
ok 246 ThaliMobile.startListeningForAdvertisements was called once
ok 247 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
ok 248 ThaliMobile.startUpdateAdvertisingAndListening was called once
ok 249 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
ok 250 ThaliSendNotificationBasedOnReplication.prototype.start was called once
ok 251 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
ok 252 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
ok 253 ThaliPullReplicationFromNotification.prototype.start was called once
ok 254 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
ok 255 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping advertising and listening'
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping listening for advertisements'
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping ThaliMobile'
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-10-04 22:57:02 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-10-04 22:57:02 - DEBUG thaliManager: 'starting ThaliMobile'
[39m
[36m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping ThaliMobile'
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliManager: 'start listening for advertisements'
2016-10-04 22:57:02 - DEBUG thaliManager: 'start update advertising and listening'
[39m
[36m# teardown
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliWifiInfrastructure: 'listening 50986'
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
[39m
[33m2016-10-04 22:57:02 - DEBUG thaliWifiInfrastructure: 'listening 50987'
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
[39m
[33m2016-10-04 22:57:02 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping advertising and listening'
[39m
[33m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping listening for advertisements'
[39m
[33m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
[39m
[33m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping ThaliMobile'
[39m
[33m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping advertising and listening'
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliManager: 'starting ThaliMobile'
[39m
[33m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping listening for advertisements'
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliManager: 'start listening for advertisements'
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliManager: 'start update advertising and listening'
[39m
[33m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping ThaliMobile'
[39m
[33m2016-10-04 22:57:02 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliWifiInfrastructure: 'listening 50988'
[39m
[33m2016-10-04 22:57:02 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
[39m
[32mok 241 ThaliMobile.start was called once
[39m
[32mok 242 ThaliMobile.start was called with 3 arguments
[39m
[32mok 243 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
[39m
[32mok 244 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
[39m
[33m2016-10-04 22:57:02 - DEBUG thaliManager: 'starting ThaliMobile'
[39m
[32mok 245 ThaliMobile.start was called with 'networkType' as 3-st argument
[39m
[32mok 246 ThaliMobile.startListeningForAdvertisements was called once
[39m
[32mok 247 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
[39m
[32mok 248 ThaliMobile.startUpdateAdvertisingAndListening was called once
[39m
[32mok 249 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
ok 250 ThaliSendNotificationBasedOnReplication.prototype.start was called once
[39m
[32mok 251 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
[39m
[32mok 252 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
[39m
[32mok 253 ThaliPullReplicationFromNotification.prototype.start was called once
[39m
[32mok 254 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
[39m
[32mok 255 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
[39m
[33m2016-10-04 22:57:02 - DEBUG thaliManager: 'start listening for advertisements'
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping advertising and listening'
[39m
[33m2016-10-04 22:57:02 - DEBUG thaliManager: 'start update advertising and listening'
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping listening for advertisements'
[39m
[32m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping ThaliMobile'
[39m
[33m2016-10-04 22:57:02 - DEBUG thaliWifiInfrastructure: 'listening 50989'
[39m
[33m2016-10-04 22:57:02 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
[39m
[33mok 241 ThaliMobile.start was called once
[39m
[32m# teardown
[39m
[33mok 242 ThaliMobile.start was called with 3 arguments
[39m
[33mok 243 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
[39m
[33mok 244 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
[39m
[33mok 245 ThaliMobile.start was called with 'networkType' as 3-st argument
[39m
[33mok 246 ThaliMobile.startListeningForAdvertisements was called once
[39m
[33mok 247 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
[39m
[33mok 248 ThaliMobile.startUpdateAdvertisingAndListening was called once
[39m
[33mok 249 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
[39m
[33mok 250 ThaliSendNotificationBasedOnReplication.prototype.start was called once
[39m
[33mok 251 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
[39m
[33mok 252 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
[39m
[33mok 253 ThaliPullReplicationFromNotification.prototype.start was called once
[39m
[33mok 254 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
[39m
[33mok 255 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
[39m
[33m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
[39m
[33m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
[39m
[33m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
[39m
[33m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping advertising and listening'
[39m
[33m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping listening for advertisements'
[39m
[33m2016-10-04 22:57:02 - DEBUG thaliManager: 'stopping ThaliMobile'
[39m
2016-10-04 22:57:02 - DEBUG UnitTestFramework: '#run ok: 'test thali manager multiple starts and stops''

2016-10-04 22:57:02 - DEBUG UnitTestFramework: '#teardown: 'test thali manager multiple starts and stops''

[32m# setup
[39m
[36m# setup
[39m
[33m# teardown
[39m
[33m# setup
[39m
2016-10-04 22:57:03 - DEBUG UnitTestFramework: '#teardown ok: 'test thali manager multiple starts and stops''

2016-10-04 22:57:03 - DEBUG UnitTestFramework: '#setup: 'test write''

[36m# test write
[39m
[33m# test write
[39m
[32m# test write
[39m
2016-10-04 22:57:03 - DEBUG UnitTestFramework: '#setup ok: 'test write''

2016-10-04 22:57:03 - DEBUG UnitTestFramework: '#run: 'test write''

[32m2016-10-04 22:57:03 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
[39m
[32m2016-10-04 22:57:03 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
[39m
[32m2016-10-04 22:57:03 - DEBUG thaliManager: 'creating express pouchdb instance'
[39m
[32m2016-10-04 22:57:03 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
[39m
[32m2016-10-04 22:57:03 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
[39m
[32m2016-10-04 22:57:03 - DEBUG thaliManager: 'starting ThaliMobile'
[39m
[36m2016-10-04 22:57:03 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
[39m
[36m2016-10-04 22:57:03 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
[39m
[36m2016-10-04 22:57:03 - DEBUG thaliManager: 'creating express pouchdb instance'
[39m
[32m2016-10-04 22:57:03 - DEBUG thaliManager: 'start listening for advertisements'
[39m
[32m2016-10-04 22:57:03 - DEBUG thaliManager: 'start update advertising and listening'
[39m
[32m2016-10-04 22:57:03 - DEBUG thaliWifiInfrastructure: 'listening 50990'
[39m
[32m2016-10-04 22:57:03 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
[39m
[36m2016-10-04 22:57:03 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
[39m
[32m{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
[39m
[36m2016-10-04 22:57:03 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
[39m
[36m2016-10-04 22:57:03 - DEBUG thaliManager: 'starting ThaliMobile'
[39m
[36m2016-10-04 22:57:03 - DEBUG thaliManager: 'start listening for advertisements'
[39m
[36m2016-10-04 22:57:03 - DEBUG thaliManager: 'start update advertising and listening'
[39m
[36m2016-10-04 22:57:03 - DEBUG thaliWifiInfrastructure: 'listening 50991'
[39m
[36m2016-10-04 22:57:03 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
[39m
[36m{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
[39m
[33m2016-10-04 22:57:03 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
[39m
[33m2016-10-04 22:57:03 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
[39m
[33m2016-10-04 22:57:03 - DEBUG thaliManager: 'creating express pouchdb instance'
[39m
[33m2016-10-04 22:57:03 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
[39m
[32m2016-10-04 22:57:03 - DEBUG thaliManager: 'connected pskIdentity Beacon Please for path /NotificationBeacons'
[39m
[33m2016-10-04 22:57:03 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
[39m
[33m2016-10-04 22:57:03 - DEBUG thaliManager: 'starting ThaliMobile'
[39m
[33m2016-10-04 22:57:03 - DEBUG thaliManager: 'start listening for advertisements'
[39m
[33m2016-10-04 22:57:03 - DEBUG thaliManager: 'start update advertising and listening'
[39m
[33m2016-10-04 22:57:03 - DEBUG thaliWifiInfrastructure: 'listening 50995'
[39m
[33m2016-10-04 22:57:03 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
[39m
[33m{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
[39m
[33m2016-10-04 22:57:03 - DEBUG thaliManager: 'connected pskIdentity Beacon Please for path /NotificationBeacons'
[39m
[36m2016-10-04 22:57:03 - DEBUG thaliManager: 'connected pskIdentity Beacon Please for path /NotificationBeacons'
[39m
[33m2016-10-04 22:57:03 - DEBUG thaliManager: 'connected pskIdentity Beacon Please for path /NotificationBeacons'
[39m
[33m2016-10-04 22:57:03 - DEBUG thaliManager: 'connected pskIdentity Beacon Please for path /NotificationBeacons'
[39m
[33m2016-10-04 22:57:03 - DEBUG thaliManager: 'connected pskIdentity ovQaCAnTYIC4YL-e_ZlkbTTNx5tAvPD4r-ybRcU_KFQ for path /db/'
[39m
[32m2016-10-04 22:57:03 - DEBUG thaliManager: 'connected pskIdentity McmJF9foNzjtxqO-d1ZF6tc3Bf3_RYSTSg6ZKNF4MnM for path /db/'
[39m
[33m2016-10-04 22:57:03 - DEBUG thaliManager: 'connected pskIdentity ovQaCAnTYIC4YL-e_ZlkbTTNx5tAvPD4r-ybRcU_KFQ for path /db/ThaliManagerCoordinated/_changes'
[39m
[36m2016-10-04 22:57:03 - DEBUG thaliManager: 'connected pskIdentity wJU4hpiwHEzt-xPXounzMaeLzP5lKafWyWRgg_Jmawg for path /db/'
[39m
[32m2016-10-04 22:57:03 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
[33m2016-10-04 22:57:03 - DEBUG thaliManager: 'connected pskIdentity ovQaCAnTYIC4YL-e_ZlkbTTNx5tAvPD4r-ybRcU_KFQ for path /db/ThaliManagerCoordinated/_changes'
[39m
[33m2016-10-04 22:57:03 - DEBUG thaliManager: 'connected pskIdentity ovQaCAnTYIC4YL-e_ZlkbTTNx5tAvPD4r-ybRcU_KFQ for path /db/ThaliManagerCoordinated/'
[39m
[36m2016-10-04 22:57:03 - DEBUG thaliManager: 'connected pskIdentity wJU4hpiwHEzt-xPXounzMaeLzP5lKafWyWRgg_Jmawg for path /db/ThaliManagerCoordinated/_changes'
[39m
[33m2016-10-04 22:57:03 - DEBUG thaliManager: 'connected pskIdentity ovQaCAnTYIC4YL-e_ZlkbTTNx5tAvPD4r-ybRcU_KFQ for path /db/ThaliManagerCoordinated/_all_docs'
[39m
[32m2016-10-04 22:57:03 - DEBUG thaliManager: 'connected pskIdentity McmJF9foNzjtxqO-d1ZF6tc3Bf3_RYSTSg6ZKNF4MnM for path /db/ThaliManagerCoordinated/_changes'
[39m
[33m2016-10-04 22:57:03 - DEBUG thaliManager: 'connected pskIdentity ovQaCAnTYIC4YL-e_ZlkbTTNx5tAvPD4r-ybRcU_KFQ for path /db/ThaliManagerCoordinated/_changes'
[39m
[36m2016-10-04 22:57:03 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
[33m2016-10-04 22:57:03 - DEBUG thaliManager: 'connected pskIdentity ovQaCAnTYIC4YL-e_ZlkbTTNx5tAvPD4r-ybRcU_KFQ for path /db/ThaliManagerCoordinated/_local/thali_BB9Mol5eF-r2JGmVl7pCUArPHhlNwWBR80uePbfm6cYKA1xwAqk0KfC8ZRcPN4v06sCroPMylMN_XI4goZ8fuHM'
[39m
[33m2016-10-04 22:57:03 - DEBUG thaliManager: 'connected pskIdentity ovQaCAnTYIC4YL-e_ZlkbTTNx5tAvPD4r-ybRcU_KFQ for path /db/ThaliManagerCoordinated/_local/ofKdIBaFKe3Bhxjpw_r59g%3D%3D'
[39m
[33m2016-10-04 22:57:03 - DEBUG thaliManager: 'connected pskIdentity WP9PTkroJZYh3y23-6HLzN00giGm49V29izK_GSjjzI for path /db/'
[39m
[32m2016-10-04 22:57:03 - DEBUG thaliManager: 'connected pskIdentity McmJF9foNzjtxqO-d1ZF6tc3Bf3_RYSTSg6ZKNF4MnM for path /db/ThaliManagerCoordinated/_changes'
[39m
[33m2016-10-04 22:57:03 - DEBUG thaliManager: 'connected pskIdentity ovQaCAnTYIC4YL-e_ZlkbTTNx5tAvPD4r-ybRcU_KFQ for path /db/ThaliManagerCoordinated/_bulk_docs'
[39m
[32m2016-10-04 22:57:03 - DEBUG thaliManager: 'connected pskIdentity McmJF9foNzjtxqO-d1ZF6tc3Bf3_RYSTSg6ZKNF4MnM for path /db/ThaliManagerCoordinated/_all_docs'
[39m
[32m2016-10-04 22:57:03 - DEBUG thaliManager: 'connected pskIdentity McmJF9foNzjtxqO-d1ZF6tc3Bf3_RYSTSg6ZKNF4MnM for path /db/ThaliManagerCoordinated/_changes'
[39m
[33m2016-10-04 22:57:03 - DEBUG thaliManager: 'connected pskIdentity WP9PTkroJZYh3y23-6HLzN00giGm49V29izK_GSjjzI for path /db/ThaliManagerCoordinated/_changes'
[39m
[33m2016-10-04 22:57:03 - DEBUG thaliManager: 'connected pskIdentity ovQaCAnTYIC4YL-e_ZlkbTTNx5tAvPD4r-ybRcU_KFQ for path /db/ThaliManagerCoordinated/_bulk_docs'
[39m
[32m2016-10-04 22:57:03 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
[36m2016-10-04 22:57:03 - DEBUG thaliManager: 'connected pskIdentity wJU4hpiwHEzt-xPXounzMaeLzP5lKafWyWRgg_Jmawg for path /db/ThaliManagerCoordinated/_changes'
[39m
[36m2016-10-04 22:57:03 - DEBUG thaliManager: 'connected pskIdentity wJU4hpiwHEzt-xPXounzMaeLzP5lKafWyWRgg_Jmawg for path /db/ThaliManagerCoordinated/_all_docs'
[39m
[36m2016-10-04 22:57:03 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
[32m2016-10-04 22:57:03 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
[39m
[36m2016-10-04 22:57:03 - DEBUG thaliManager: 'connected pskIdentity wJU4hpiwHEzt-xPXounzMaeLzP5lKafWyWRgg_Jmawg for path /db/ThaliManagerCoordinated/'
[39m
[33m2016-10-04 22:57:03 - DEBUG thaliManager: 'connected pskIdentity WP9PTkroJZYh3y23-6HLzN00giGm49V29izK_GSjjzI for path /db/ThaliManagerCoordinated/_changes'
[39m
[32m2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity McmJF9foNzjtxqO-d1ZF6tc3Bf3_RYSTSg6ZKNF4MnM for path /db/ThaliManagerCoordinated/_local/thali_BL1wKS0PSSxMPtLbT4-F7YCUqo3AGAafyyZxnyRXp76Jlu34oqZSnFTV1RI-9qUrv05WQqRuJNdxBoyV_Q2iS48'
[39m
[33m2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity WP9PTkroJZYh3y23-6HLzN00giGm49V29izK_GSjjzI for path /db/ThaliManagerCoordinated/_all_docs'
[39m
[36m2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity wJU4hpiwHEzt-xPXounzMaeLzP5lKafWyWRgg_Jmawg for path /db/ThaliManagerCoordinated/_changes'
[39m
[32m2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity McmJF9foNzjtxqO-d1ZF6tc3Bf3_RYSTSg6ZKNF4MnM for path /db/ThaliManagerCoordinated/'
[39m
[33m2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity WP9PTkroJZYh3y23-6HLzN00giGm49V29izK_GSjjzI for path /db/ThaliManagerCoordinated/_local/thali_BL1wKS0PSSxMPtLbT4-F7YCUqo3AGAafyyZxnyRXp76Jlu34oqZSnFTV1RI-9qUrv05WQqRuJNdxBoyV_Q2iS48'
[39m
[33m2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity WP9PTkroJZYh3y23-6HLzN00giGm49V29izK_GSjjzI for path /db/ThaliManagerCoordinated/'
[39m
[36m# teardown
[39m
[33m2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity WP9PTkroJZYh3y23-6HLzN00giGm49V29izK_GSjjzI for path /db/ThaliManagerCoordinated/_local/4ABRBhShKjrP5pOW6DK24Q%3D%3D'
[39m
[32m2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity McmJF9foNzjtxqO-d1ZF6tc3Bf3_RYSTSg6ZKNF4MnM for path /db/ThaliManagerCoordinated/_local/jz1Vlci3szwlzSJj0nt7Cg%3D%3D'
[39m
[32m# teardown
[39m
[36m2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity wJU4hpiwHEzt-xPXounzMaeLzP5lKafWyWRgg_Jmawg for path /db/ThaliManagerCoordinated/_local/thali_BB9Mol5eF-r2JGmVl7pCUArPHhlNwWBR80uePbfm6cYKA1xwAqk0KfC8ZRcPN4v06sCroPMylMN_XI4goZ8fuHM'
[39m
[36m2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity wJU4hpiwHEzt-xPXounzMaeLzP5lKafWyWRgg_Jmawg for path /db/ThaliManagerCoordinated/_local/1IlvMKaZBI1r3lbuLPaacQ%3D%3D'
[39m
[36m2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity wJU4hpiwHEzt-xPXounzMaeLzP5lKafWyWRgg_Jmawg for path /db/ThaliManagerCoordinated/_changes'
[39m
[33m2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity WP9PTkroJZYh3y23-6HLzN00giGm49V29izK_GSjjzI for path /db/ThaliManagerCoordinated/_changes'
[39m
[32m2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity McmJF9foNzjtxqO-d1ZF6tc3Bf3_RYSTSg6ZKNF4MnM for path /db/ThaliManagerCoordinated/_changes'
[39m
[33m2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity WP9PTkroJZYh3y23-6HLzN00giGm49V29izK_GSjjzI for path /db/ThaliManagerCoordinated/_bulk_docs'
[39m
[33m2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity WP9PTkroJZYh3y23-6HLzN00giGm49V29izK_GSjjzI for path /db/ThaliManagerCoordinated/_bulk_docs'
[39m
[32m2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity McmJF9foNzjtxqO-d1ZF6tc3Bf3_RYSTSg6ZKNF4MnM for path /db/ThaliManagerCoordinated/_bulk_docs'
[39m
[33m(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
[39m
[33mTrace
    at PouchAlt.addListener (events.js:140:15)
    at PouchAlt.PouchDBGenerator.PouchAlt.on.PouchAlt.addListener (/Users/thali/Github/Thali_CordovaPlugin/thali/NextGeneration/utils/pouchDBGenerator.js:99:50)
    at PouchAlt.once (events.js:165:8)
    at new Changes (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/pouchdb/lib/index.js:1442:6)
    at PouchAlt.AbstractPouchDB.changes (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/pouchdb/lib/index.js:2373:10)
    at PouchAlt.PouchDBGenerator.PouchAlt.changes (/Users/thali/Github/Thali_CordovaPlugin/thali/NextGeneration/utils/pouchDBGenerator.js:112:53)
    at eventFunction (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/pouchdb/lib/index.js:420:8)
    at null._onTimeout (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/pouchdb/lib/index.js:428:11)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)
[39m
[32m2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity McmJF9foNzjtxqO-d1ZF6tc3Bf3_RYSTSg6ZKNF4MnM for path /db/ThaliManagerCoordinated/_changes'
[39m
[32m2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity McmJF9foNzjtxqO-d1ZF6tc3Bf3_RYSTSg6ZKNF4MnM for path /db/ThaliManagerCoordinated/_bulk_docs'
[39m
[36m2016-10-04 22:57:04 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
[39m
[32m2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity McmJF9foNzjtxqO-d1ZF6tc3Bf3_RYSTSg6ZKNF4MnM for path /db/ThaliManagerCoordinated/_local/jz1Vlci3szwlzSJj0nt7Cg%3D%3D'
[39m
[36m2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity wJU4hpiwHEzt-xPXounzMaeLzP5lKafWyWRgg_Jmawg for path /db/ThaliManagerCoordinated/_bulk_docs'
[39m
[36m2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity wJU4hpiwHEzt-xPXounzMaeLzP5lKafWyWRgg_Jmawg for path /db/ThaliManagerCoordinated/_changes'
[39m
[36m2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity wJU4hpiwHEzt-xPXounzMaeLzP5lKafWyWRgg_Jmawg for path /db/ThaliManagerCoordinated/_bulk_docs'
[39m
[32m2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity McmJF9foNzjtxqO-d1ZF6tc3Bf3_RYSTSg6ZKNF4MnM for path /db/ThaliManagerCoordinated/_bulk_docs'
[39m
[32m2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity McmJF9foNzjtxqO-d1ZF6tc3Bf3_RYSTSg6ZKNF4MnM for path /db/ThaliManagerCoordinated/_local/jz1Vlci3szwlzSJj0nt7Cg%3D%3D'
[39m
[36m2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity wJU4hpiwHEzt-xPXounzMaeLzP5lKafWyWRgg_Jmawg for path /db/ThaliManagerCoordinated/_local/1IlvMKaZBI1r3lbuLPaacQ%3D%3D'
[39m
[32m2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity McmJF9foNzjtxqO-d1ZF6tc3Bf3_RYSTSg6ZKNF4MnM for path /db/ThaliManagerCoordinated/_bulk_docs'
[39m
[36m2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity wJU4hpiwHEzt-xPXounzMaeLzP5lKafWyWRgg_Jmawg for path /db/ThaliManagerCoordinated/_bulk_docs'
[39m
[32m(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
[39m
[32mTrace
    at PouchAlt.addListener (events.js:140:15)
    at PouchAlt.PouchDBGenerator.PouchAlt.on.PouchAlt.addListener (/Users/thali/Github/Thali_CordovaPlugin/thali/NextGeneration/utils/pouchDBGenerator.js:99:50)
    at PouchAlt.once (events.js:165:8)
    at new Changes (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/pouchdb/lib/index.js:1442:6)
    at PouchAlt.AbstractPouchDB.changes (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/pouchdb/lib/index.js:2373:10)
    at PouchAlt.PouchDBGenerator.PouchAlt.changes (/Users/thali/Github/Thali_CordovaPlugin/thali/NextGeneration/utils/pouchDBGenerator.js:112:53)
    at Changes$1.eventFunction (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/pouchdb/lib/index.js:420:8)
    at Changes$1.emit (events.js:98:20)
    at Changes$1.notify (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/pouchdb/lib/index.js:460:8)
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/pouchdb/lib/index.js:4303:22
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/sublevel-pouchdb/lib/shell.js:77:46
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/sublevel-pouchdb/lib/nut.js:90:13
[39m
[36m2016-10-04 22:57:04 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
[39m
[36m2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity wJU4hpiwHEzt-xPXounzMaeLzP5lKafWyWRgg_Jmawg for path /db/ThaliManagerCoordinated/_local/1IlvMKaZBI1r3lbuLPaacQ%3D%3D'
[39m
[36m2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity wJU4hpiwHEzt-xPXounzMaeLzP5lKafWyWRgg_Jmawg for path /db/ThaliManagerCoordinated/_bulk_docs'
[39m
[36m(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
[39m
[36mTrace
    at PouchAlt.addListener (events.js:140:15)
    at PouchAlt.PouchDBGenerator.PouchAlt.on.PouchAlt.addListener (/Users/thali/Github/Thali_CordovaPlugin/thali/NextGeneration/utils/pouchDBGenerator.js:99:50)
    at PouchAlt.once (events.js:165:8)
    at new Changes (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/pouchdb/lib/index.js:1442:6)
    at PouchAlt.AbstractPouchDB.changes (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/pouchdb/lib/index.js:2373:10)
    at PouchAlt.PouchDBGenerator.PouchAlt.changes (/Users/thali/Github/Thali_CordovaPlugin/thali/NextGeneration/utils/pouchDBGenerator.js:112:53)
    at Changes$1.eventFunction (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/pouchdb/lib/index.js:420:8)
    at Changes$1.emit (events.js:98:20)
    at Changes$1.notify (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/pouchdb/lib/index.js:460:8)
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/pouchdb/lib/index.js:4303:22
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/sublevel-pouchdb/lib/shell.js:77:46
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/sublevel-pouchdb/lib/nut.js:90:13
[39m
[32m2016-10-04 22:57:04 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
[39m
[32m2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity Beacon Please for path /NotificationBeacons'
[39m
[32m2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity dKMxvsjBGjE6QpG62nE7CrusDYTDts-4lkP1YQ4qVhs for path /db/'
[39m
[36m2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity Beacon Please for path /NotificationBeacons'
[39m
[32m2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity dKMxvsjBGjE6QpG62nE7CrusDYTDts-4lkP1YQ4qVhs for path /db/ThaliManagerCoordinated/_changes'
[39m
[36m2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity plKThG5tqGLzmJDwmMPtL-vliRTL0SSwjuccUpICrRA for path /db/'
[39m
[33m2016-10-04 22:57:04 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
[32m2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity dKMxvsjBGjE6QpG62nE7CrusDYTDts-4lkP1YQ4qVhs for path /db/ThaliManagerCoordinated/_changes'
[39m
[36m2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity plKThG5tqGLzmJDwmMPtL-vliRTL0SSwjuccUpICrRA for path /db/ThaliManagerCoordinated/_changes'
[39m
[32m2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity dKMxvsjBGjE6QpG62nE7CrusDYTDts-4lkP1YQ4qVhs for path /db/ThaliManagerCoordinated/_all_docs'
[39m
[32m2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity dKMxvsjBGjE6QpG62nE7CrusDYTDts-4lkP1YQ4qVhs for path /db/ThaliManagerCoordinated/'
[39m
[33m(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
Trace
    at PouchAlt.addListener (events.js:140:15)
    at PouchAlt.PouchDBGenerator.PouchAlt.on.PouchAlt.addListener (/Users/thali/Github/Thali_CordovaPlugin/thali/NextGeneration/utils/pouchDBGenerator.js:99:50)
    at PouchAlt.once (events.js:165:8)
    at new Changes (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/pouchdb/lib/index.js:1442:6)
    at PouchAlt.AbstractPouchDB.changes (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/pouchdb/lib/index.js:2373:10)
    at PouchAlt.PouchDBGenerator.PouchAlt.changes (/Users/thali/Github/Thali_CordovaPlugin/thali/NextGeneration/utils/pouchDBGenerator.js:112:53)
    at Changes$1.eventFunction (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/pouchdb/lib/index.js:420:8)
    at Changes$1.emit (events.js:98:20)
    at Changes$1.notify (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/pouchdb/lib/index.js:460:8)
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/pouchdb/lib/index.js:4303:22
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/sublevel-pouchdb/lib/shell.js:77:46
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/sublevel-pouchdb/lib/nut.js:90:13
[39m
[33m2016-10-04 22:57:04 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
[32m2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity dKMxvsjBGjE6QpG62nE7CrusDYTDts-4lkP1YQ4qVhs for path /db/ThaliManagerCoordinated/_local/thali_BLnTZaH1swfxGEQhKiBEZXsFLnIb2CgUujZTuTyXVFASQ5Kb3RXLFDHeuiF-QreXt8WPIL9d4iAgYu-op2xt4zU'
[39m
[32m2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity dKMxvsjBGjE6QpG62nE7CrusDYTDts-4lkP1YQ4qVhs for path /db/ThaliManagerCoordinated/_changes'
[39m
[36m2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity plKThG5tqGLzmJDwmMPtL-vliRTL0SSwjuccUpICrRA for path /db/ThaliManagerCoordinated/_changes'
[39m
[32m2016-10-04 22:57:04 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
[36m2016-10-04 22:57:04 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
2016-10-04 22:57:04 - DEBUG UnitTestFramework: '#run ok: 'test write''
2016-10-04 22:57:04 - DEBUG UnitTestFramework: '#teardown: 'test write''

[32m2016-10-04 22:57:04 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-10-04 22:57:04 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-10-04 22:57:04 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-10-04 22:57:04 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
[39m
[36m2016-10-04 22:57:04 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-10-04 22:57:04 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
[39m
[33m2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity ovQaCAnTYIC4YL-e_ZlkbTTNx5tAvPD4r-ybRcU_KFQ for path /db/ThaliManagerCoordinated/_changes'
2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity ovQaCAnTYIC4YL-e_ZlkbTTNx5tAvPD4r-ybRcU_KFQ for path /db/ThaliManagerCoordinated/_local/ofKdIBaFKe3Bhxjpw_r59g%3D%3D'
2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity WP9PTkroJZYh3y23-6HLzN00giGm49V29izK_GSjjzI for path /db/ThaliManagerCoordinated/_changes'
[39m
[36m2016-10-04 22:57:04 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-10-04 22:57:04 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
[39m
[33m2016-10-04 22:57:04 - DEBUG thaliManager: 'connected pskIdentity WP9PTkroJZYh3y23-6HLzN00giGm49V29izK_GSjjzI for path /db/ThaliManagerCoordinated/_local/4ABRBhShKjrP5pOW6DK24Q%3D%3D'
[39m
[33m2016-10-04 22:57:04 - DEBUG thaliReplicationPeerAction: 'Got error on replication -   Unexpected end of input'
[39m
[33m2016-10-04 22:57:04 - DEBUG thaliPeerPoolDefault: 'Got err   Unexpected end of input'
[39m
[33m2016-10-04 22:57:04 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
2016-10-04 22:57:04 - DEBUG thaliReplicationPeerAction: 'Got error in update, waiting for main loop to detect and handle -  500 connect ECONNREFUSED'
# teardown
[39m
[33m2016-10-04 22:57:04 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
[39m
[33m2016-10-04 22:57:04 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
[39m
[32m2016-10-04 22:57:04 - DEBUG thaliManager: 'stopping advertising and listening'
[39m
[32m2016-10-04 22:57:04 - DEBUG thaliManager: 'stopping listening for advertisements'
[39m
[32m2016-10-04 22:57:04 - DEBUG thaliManager: 'stopping ThaliMobile'
[39m
[32m# setup
[39m
[36m2016-10-04 22:57:04 - DEBUG thaliManager: 'stopping advertising and listening'
2016-10-04 22:57:04 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-10-04 22:57:04 - DEBUG thaliManager: 'stopping ThaliMobile'
[39m
[36m# setup
[39m
[33m2016-10-04 22:57:04 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
[39m
[33m2016-10-04 22:57:05 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
[39m
[33m2016-10-04 22:57:05 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
[39m
[33m2016-10-04 22:57:05 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
[39m
[33m2016-10-04 22:57:05 - DEBUG thaliManager: 'stopping advertising and listening'
[39m
[33m2016-10-04 22:57:05 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
[39m
[33m2016-10-04 22:57:05 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-10-04 22:57:05 - DEBUG thaliManager: 'stopping ThaliMobile'
# setup
[39m
2016-10-04 22:57:05 - DEBUG UnitTestFramework: '#teardown ok: 'test write''
2016-10-04 22:57:05 - DEBUG UnitTestFramework: '#setup: 'test repeat write 1''

[36m# test repeat write 1
[39m
[32m# test repeat write 1
[39m
[33m# test repeat write 1
[39m
2016-10-04 22:57:05 - DEBUG UnitTestFramework: '#setup ok: 'test repeat write 1''

2016-10-04 22:57:05 - DEBUG UnitTestFramework: '#run: 'test repeat write 1''

[36m2016-10-04 22:57:05 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-10-04 22:57:05 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-10-04 22:57:05 - DEBUG thaliManager: 'starting ThaliMobile'
2016-10-04 22:57:05 - DEBUG thaliManager: 'start listening for advertisements'
2016-10-04 22:57:05 - DEBUG thaliManager: 'start update advertising and listening'
2016-10-04 22:57:05 - DEBUG thaliWifiInfrastructure: 'listening 51035'
2016-10-04 22:57:05 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
[39m
[33m2016-10-04 22:57:05 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-10-04 22:57:05 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-10-04 22:57:05 - DEBUG thaliManager: 'starting ThaliMobile'
2016-10-04 22:57:05 - DEBUG thaliManager: 'start listening for advertisements'
2016-10-04 22:57:05 - DEBUG thaliManager: 'start update advertising and listening'
2016-10-04 22:57:05 - DEBUG thaliWifiInfrastructure: 'listening 51036'
2016-10-04 22:57:05 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
[39m
[32m2016-10-04 22:57:05 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-10-04 22:57:05 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-10-04 22:57:05 - DEBUG thaliManager: 'starting ThaliMobile'
2016-10-04 22:57:05 - DEBUG thaliManager: 'start listening for advertisements'
2016-10-04 22:57:05 - DEBUG thaliManager: 'start update advertising and listening'
2016-10-04 22:57:05 - DEBUG thaliWifiInfrastructure: 'listening 51038'
2016-10-04 22:57:05 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
[39m
[36m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity Beacon Please for path /NotificationBeacons'
[39m
[36m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity Beacon Please for path /NotificationBeacons'
[39m
[32m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity Beacon Please for path /NotificationBeacons'
[39m
[32m(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
Trace
    at PouchAlt.addListener (events.js:140:15)
    at PouchAlt.PouchDBGenerator.PouchAlt.on.PouchAlt.addListener (/Users/thali/Github/Thali_CordovaPlugin/thali/NextGeneration/utils/pouchDBGenerator.js:99:50)
    at PouchAlt.once (events.js:165:8)
    at new Changes (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/pouchdb/lib/index.js:1442:6)
    at PouchAlt.AbstractPouchDB.changes (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/pouchdb/lib/index.js:2373:10)
    at PouchAlt.PouchDBGenerator.PouchAlt.changes (/Users/thali/Github/Thali_CordovaPlugin/thali/NextGeneration/utils/pouchDBGenerator.js:112:53)
    at eventFunction (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/pouchdb/lib/index.js:420:8)
    at null._onTimeout (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/pouchdb/lib/index.js:428:11)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)
[39m
[33m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity Beacon Please for path /NotificationBeacons'
[39m
[36m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity pZgEz3fr8xw4rMNloK8WA5-w_hJn2Mj-xhcXdsIp8qE for path /db/'
[39m
[33m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity Beacon Please for path /NotificationBeacons'
[39m
[36m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity pZgEz3fr8xw4rMNloK8WA5-w_hJn2Mj-xhcXdsIp8qE for path /db/ThaliManagerCoordinated/_changes'
[39m
[33m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity HRp19gyx-gkNAyu3KBtnmZUd5UInyCGedDVb_EIpZoI for path /db/'
[39m
[32m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity Beacon Please for path /NotificationBeacons'
[39m
[32m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity tT44onzPRxKO8_THS43gXerDKgx3eKeoLK8p2RUTipY for path /db/'
[39m
[32m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity xH2yWW-lvVIZm7QBC4PBw8kw6PBBs6x1m0F_ctmLnCE for path /db/'
[39m
[33m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity HRp19gyx-gkNAyu3KBtnmZUd5UInyCGedDVb_EIpZoI for path /db/ThaliManagerCoordinated/_changes'
[39m
[36m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity 1sQiDKNRnASRB6RUAcv0TLRksf0kGclb3To6VENtEy4 for path /db/'
[39m
[33m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity j6ba2eX52spsGkm5cW31I7nAAmVOavn9Ur-nD_glXlI for path /db/'
[39m
[32m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity xH2yWW-lvVIZm7QBC4PBw8kw6PBBs6x1m0F_ctmLnCE for path /db/ThaliManagerCoordinated/_changes'
[39m
[36m2016-10-04 22:57:05 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
[32m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity tT44onzPRxKO8_THS43gXerDKgx3eKeoLK8p2RUTipY for path /db/ThaliManagerCoordinated/_changes'
[39m
[33m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity j6ba2eX52spsGkm5cW31I7nAAmVOavn9Ur-nD_glXlI for path /db/ThaliManagerCoordinated/_changes'
[39m
[36m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity 1sQiDKNRnASRB6RUAcv0TLRksf0kGclb3To6VENtEy4 for path /db/ThaliManagerCoordinated/_changes'
[39m
[32m2016-10-04 22:57:05 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
[33m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity HRp19gyx-gkNAyu3KBtnmZUd5UInyCGedDVb_EIpZoI for path /db/ThaliManagerCoordinated/_changes'
[39m
[33m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity j6ba2eX52spsGkm5cW31I7nAAmVOavn9Ur-nD_glXlI for path /db/ThaliManagerCoordinated/_changes'
[39m
[33m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity j6ba2eX52spsGkm5cW31I7nAAmVOavn9Ur-nD_glXlI for path /db/ThaliManagerCoordinated/_bulk_get'
[39m
[33m2016-10-04 22:57:05 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
[32m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity xH2yWW-lvVIZm7QBC4PBw8kw6PBBs6x1m0F_ctmLnCE for path /db/ThaliManagerCoordinated/_changes'
[39m
[36m2016-10-04 22:57:05 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
[33m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity j6ba2eX52spsGkm5cW31I7nAAmVOavn9Ur-nD_glXlI for path /db/ThaliManagerCoordinated/'
2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity HRp19gyx-gkNAyu3KBtnmZUd5UInyCGedDVb_EIpZoI for path /db/ThaliManagerCoordinated/'
[39m
[32m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity tT44onzPRxKO8_THS43gXerDKgx3eKeoLK8p2RUTipY for path /db/ThaliManagerCoordinated/_changes'
[39m
[32m2016-10-04 22:57:05 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
[33m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity HRp19gyx-gkNAyu3KBtnmZUd5UInyCGedDVb_EIpZoI for path /db/ThaliManagerCoordinated/_bulk_get'
[39m
[33m2016-10-04 22:57:05 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
[32m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity tT44onzPRxKO8_THS43gXerDKgx3eKeoLK8p2RUTipY for path /db/ThaliManagerCoordinated/_bulk_get'
[39m
[36m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity 1sQiDKNRnASRB6RUAcv0TLRksf0kGclb3To6VENtEy4 for path /db/ThaliManagerCoordinated/_changes'
2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity pZgEz3fr8xw4rMNloK8WA5-w_hJn2Mj-xhcXdsIp8qE for path /db/ThaliManagerCoordinated/_changes'
[39m
[33m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity HRp19gyx-gkNAyu3KBtnmZUd5UInyCGedDVb_EIpZoI for path /db/ThaliManagerCoordinated/_changes'
[39m
[36m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity pZgEz3fr8xw4rMNloK8WA5-w_hJn2Mj-xhcXdsIp8qE for path /db/ThaliManagerCoordinated/_bulk_get'
[39m
[36m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity pZgEz3fr8xw4rMNloK8WA5-w_hJn2Mj-xhcXdsIp8qE for path /db/ThaliManagerCoordinated/'
[39m
[33m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity j6ba2eX52spsGkm5cW31I7nAAmVOavn9Ur-nD_glXlI for path /db/ThaliManagerCoordinated/_changes'
[39m
[36m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity 1sQiDKNRnASRB6RUAcv0TLRksf0kGclb3To6VENtEy4 for path /db/ThaliManagerCoordinated/'
[39m
[36m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity 1sQiDKNRnASRB6RUAcv0TLRksf0kGclb3To6VENtEy4 for path /db/ThaliManagerCoordinated/_bulk_get'
[39m
[36m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity pZgEz3fr8xw4rMNloK8WA5-w_hJn2Mj-xhcXdsIp8qE for path /db/ThaliManagerCoordinated/_changes'
[39m
[36m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity pZgEz3fr8xw4rMNloK8WA5-w_hJn2Mj-xhcXdsIp8qE for path /db/ThaliManagerCoordinated/_local/thali_BLnTZaH1swfxGEQhKiBEZXsFLnIb2CgUujZTuTyXVFASQ5Kb3RXLFDHeuiF-QreXt8WPIL9d4iAgYu-op2xt4zU'
[39m
[32m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity xH2yWW-lvVIZm7QBC4PBw8kw6PBBs6x1m0F_ctmLnCE for path /db/ThaliManagerCoordinated/_bulk_get'
[39m
[36m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity pZgEz3fr8xw4rMNloK8WA5-w_hJn2Mj-xhcXdsIp8qE for path /db/ThaliManagerCoordinated/_local/n2Ssgv1r1k0vHATIRb5oSg%3D%3D'
[39m
[36m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity 1sQiDKNRnASRB6RUAcv0TLRksf0kGclb3To6VENtEy4 for path /db/ThaliManagerCoordinated/_changes'
[39m
[33m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity j6ba2eX52spsGkm5cW31I7nAAmVOavn9Ur-nD_glXlI for path /db/ThaliManagerCoordinated/_local/thali_BB9Mol5eF-r2JGmVl7pCUArPHhlNwWBR80uePbfm6cYKA1xwAqk0KfC8ZRcPN4v06sCroPMylMN_XI4goZ8fuHM'
[39m
[32m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity xH2yWW-lvVIZm7QBC4PBw8kw6PBBs6x1m0F_ctmLnCE for path /db/ThaliManagerCoordinated/_changes'
[39m
[33m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity HRp19gyx-gkNAyu3KBtnmZUd5UInyCGedDVb_EIpZoI for path /db/ThaliManagerCoordinated/_local/thali_BL1wKS0PSSxMPtLbT4-F7YCUqo3AGAafyyZxnyRXp76Jlu34oqZSnFTV1RI-9qUrv05WQqRuJNdxBoyV_Q2iS48'
[39m
[32m# teardown
[39m
[33m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity j6ba2eX52spsGkm5cW31I7nAAmVOavn9Ur-nD_glXlI for path /db/ThaliManagerCoordinated/_local/dW3XMEqRt8Np9oJOIxbKhQ%3D%3D'
[39m
[36m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity 1sQiDKNRnASRB6RUAcv0TLRksf0kGclb3To6VENtEy4 for path /db/ThaliManagerCoordinated/_local/thali_BB9Mol5eF-r2JGmVl7pCUArPHhlNwWBR80uePbfm6cYKA1xwAqk0KfC8ZRcPN4v06sCroPMylMN_XI4goZ8fuHM'
[39m
[36m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity 1sQiDKNRnASRB6RUAcv0TLRksf0kGclb3To6VENtEy4 for path /db/ThaliManagerCoordinated/_local/V3NSbaocH.T.lLL2JHiRDw%3D%3D'
[39m
[32m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity xH2yWW-lvVIZm7QBC4PBw8kw6PBBs6x1m0F_ctmLnCE for path /db/ThaliManagerCoordinated/_local/thali_BLnTZaH1swfxGEQhKiBEZXsFLnIb2CgUujZTuTyXVFASQ5Kb3RXLFDHeuiF-QreXt8WPIL9d4iAgYu-op2xt4zU'
[39m
[36m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity pZgEz3fr8xw4rMNloK8WA5-w_hJn2Mj-xhcXdsIp8qE for path /db/ThaliManagerCoordinated/_bulk_docs'
[39m
[36m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity 1sQiDKNRnASRB6RUAcv0TLRksf0kGclb3To6VENtEy4 for path /db/ThaliManagerCoordinated/_changes'
[39m
[33m# teardown
[39m
[32m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity tT44onzPRxKO8_THS43gXerDKgx3eKeoLK8p2RUTipY for path /db/ThaliManagerCoordinated/_changes'
[39m
2016-10-04 22:57:05 - DEBUG UnitTestFramework: '#run ok: 'test repeat write 1''
2016-10-04 22:57:05 - DEBUG UnitTestFramework: '#teardown: 'test repeat write 1''

[33m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity j6ba2eX52spsGkm5cW31I7nAAmVOavn9Ur-nD_glXlI for path /db/ThaliManagerCoordinated/_changes'
[39m
[32m2016-10-04 22:57:05 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
[39m
[32m2016-10-04 22:57:05 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
[39m
[32m2016-10-04 22:57:05 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
[39m
[32m2016-10-04 22:57:05 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
[39m
[36m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity pZgEz3fr8xw4rMNloK8WA5-w_hJn2Mj-xhcXdsIp8qE for path /db/ThaliManagerCoordinated/_bulk_docs'
[39m
[33m2016-10-04 22:57:05 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-10-04 22:57:05 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-10-04 22:57:05 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-10-04 22:57:05 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
[39m
[33m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity HRp19gyx-gkNAyu3KBtnmZUd5UInyCGedDVb_EIpZoI for path /db/ThaliManagerCoordinated/_changes'
[39m
[33m2016-10-04 22:57:05 - DEBUG thaliManager: 'connected pskIdentity HRp19gyx-gkNAyu3KBtnmZUd5UInyCGedDVb_EIpZoI for path /db/ThaliManagerCoordinated/_local/80cdtMrzCEf5fQSvxmss0A%3D%3D'
[39m
[32m2016-10-04 22:57:05 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
2016-10-04 22:57:05 - DEBUG thaliReplicationPeerAction: 'Got error in update, waiting for main loop to detect and handle -  500 connect ECONNREFUSED'
[39m
[32m2016-10-04 22:57:05 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up -1'
2016-10-04 22:57:05 - DEBUG thaliPeerPoolDefault: 'Got err   Could establish TCP connection but couldn't keep it running'
[39m
[33m2016-10-04 22:57:05 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
[39m
[33m2016-10-04 22:57:05 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
[39m
[36m2016-10-04 22:57:05 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
[39m
[33m2016-10-04 22:57:05 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
2016-10-04 22:57:05 - DEBUG thaliReplicationPeerAction: 'Got error in update, waiting for main loop to detect and handle -  500 connect ECONNREFUSED'
[39m
[36m2016-10-04 22:57:05 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
[39m
[36m2016-10-04 22:57:05 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
[39m
[36m2016-10-04 22:57:05 - DEBUG thaliReplicationPeerAction: 'Got error in update, waiting for main loop to detect and handle -  500 connect ECONNREFUSED'
[39m
[36m2016-10-04 22:57:05 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 Unauthorized'
[39m
[36m2016-10-04 22:57:05 - DEBUG thaliPeerPoolDefault: 'Got err  401 Unauthorized'
[39m
[36m2016-10-04 22:57:05 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
[39m
[36m2016-10-04 22:57:05 - DEBUG thaliReplicationPeerAction: 'Got error in update, waiting for main loop to detect and handle -  500 connect ECONNREFUSED'
[39m
[36m# teardown
[39m
[32m2016-10-04 22:57:05 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
[39m
[32m2016-10-04 22:57:05 - DEBUG thaliReplicationPeerAction: 'Got error in update, waiting for main loop to detect and handle -   Stop Called'
[39m
[32m2016-10-04 22:57:05 - DEBUG thaliManager: 'stopping advertising and listening'
[39m
[32m2016-10-04 22:57:05 - DEBUG thaliManager: 'stopping listening for advertisements'
[39m
[32m2016-10-04 22:57:05 - DEBUG thaliManager: 'stopping ThaliMobile'
[39m
[32m# setup
[39m
[33m2016-10-04 22:57:05 - DEBUG thaliManager: 'stopping advertising and listening'
[39m
[33m2016-10-04 22:57:05 - DEBUG thaliManager: 'stopping listening for advertisements'
[39m
[33m2016-10-04 22:57:05 - DEBUG thaliManager: 'stopping ThaliMobile'
[39m
[33m# setup
[39m
[36m2016-10-04 22:57:06 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
[39m
[36m2016-10-04 22:57:06 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
[39m
[36m2016-10-04 22:57:06 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
[39m
[36m2016-10-04 22:57:06 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
[39m
[36m2016-10-04 22:57:06 - DEBUG thaliManager: 'stopping advertising and listening'
[39m
[36m2016-10-04 22:57:06 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
[39m
[36m2016-10-04 22:57:06 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-10-04 22:57:06 - DEBUG thaliManager: 'stopping ThaliMobile'
[39m
2016-10-04 22:57:06 - DEBUG UnitTestFramework: '#teardown ok: 'test repeat write 1''
2016-10-04 22:57:06 - DEBUG UnitTestFramework: '#setup: 'test repeat write 2''

[36m# setup
[39m
[36m# test repeat write 2
[39m
[32m# test repeat write 2
[39m
[33m# test repeat write 2
[39m
2016-10-04 22:57:06 - DEBUG UnitTestFramework: '#setup ok: 'test repeat write 2''

2016-10-04 22:57:06 - DEBUG UnitTestFramework: '#run: 'test repeat write 2''

[36m2016-10-04 22:57:06 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-10-04 22:57:06 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-10-04 22:57:06 - DEBUG thaliManager: 'starting ThaliMobile'
2016-10-04 22:57:06 - DEBUG thaliManager: 'start listening for advertisements'
2016-10-04 22:57:06 - DEBUG thaliManager: 'start update advertising and listening'
2016-10-04 22:57:06 - DEBUG thaliWifiInfrastructure: 'listening 51075'
2016-10-04 22:57:06 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
[39m
[33m2016-10-04 22:57:06 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-10-04 22:57:06 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-10-04 22:57:06 - DEBUG thaliManager: 'starting ThaliMobile'
2016-10-04 22:57:06 - DEBUG thaliManager: 'start listening for advertisements'
2016-10-04 22:57:06 - DEBUG thaliManager: 'start update advertising and listening'
2016-10-04 22:57:06 - DEBUG thaliWifiInfrastructure: 'listening 51076'
2016-10-04 22:57:06 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
[39m
[32m2016-10-04 22:57:06 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-10-04 22:57:06 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-10-04 22:57:06 - DEBUG thaliManager: 'starting ThaliMobile'
[39m
[32m2016-10-04 22:57:06 - DEBUG thaliManager: 'start listening for advertisements'
[39m
[32m2016-10-04 22:57:06 - DEBUG thaliManager: 'start update advertising and listening'
2016-10-04 22:57:06 - DEBUG thaliWifiInfrastructure: 'listening 51079'
2016-10-04 22:57:06 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
[39m
[36m2016-10-04 22:57:06 - DEBUG thaliManager: 'connected pskIdentity Beacon Please for path /NotificationBeacons'
2016-10-04 22:57:06 - DEBUG thaliManager: 'connected pskIdentity Beacon Please for path /NotificationBeacons'
[39m
[32m2016-10-04 22:57:06 - DEBUG thaliManager: 'connected pskIdentity Beacon Please for path /NotificationBeacons'
[39m
[33m2016-10-04 22:57:06 - DEBUG thaliManager: 'connected pskIdentity Beacon Please for path /NotificationBeacons'
[39m
[32m2016-10-04 22:57:06 - DEBUG thaliManager: 'connected pskIdentity Beacon Please for path /NotificationBeacons'
[39m
[32m2016-10-04 22:57:06 - DEBUG thaliManager: 'connected pskIdentity M1cIKIMo-CG6ya5oULkfIZ0Alqnp84afflI8ZnyXPGE for path /db/'
2016-10-04 22:57:06 - DEBUG thaliManager: 'connected pskIdentity M1cIKIMo-CG6ya5oULkfIZ0Alqnp84afflI8ZnyXPGE for path /db/ThaliManagerCoordinated/_changes'
[39m
[36m2016-10-04 22:57:06 - DEBUG thaliManager: 'connected pskIdentity 8sSxvMjvsdedQmhfOTY91D3xWgf5suCDGiVZndsiuNw for path /db/'
2016-10-04 22:57:06 - DEBUG thaliManager: 'connected pskIdentity 8sSxvMjvsdedQmhfOTY91D3xWgf5suCDGiVZndsiuNw for path /db/ThaliManagerCoordinated/_changes'
[39m
[32m2016-10-04 22:57:06 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
[36m2016-10-04 22:57:06 - DEBUG thaliManager: 'connected pskIdentity 8sSxvMjvsdedQmhfOTY91D3xWgf5suCDGiVZndsiuNw for path /db/ThaliManagerCoordinated/_changes'
[39m
[36m2016-10-04 22:57:06 - DEBUG thaliManager: 'connected pskIdentity 8sSxvMjvsdedQmhfOTY91D3xWgf5suCDGiVZndsiuNw for path /db/ThaliManagerCoordinated/_bulk_get'
[39m
[33m2016-10-04 22:57:06 - DEBUG thaliManager: 'connected pskIdentity Beacon Please for path /NotificationBeacons'
[39m
[36m2016-10-04 22:57:06 - DEBUG thaliManager: 'connected pskIdentity Tz0YymY8AKnnva7dTNARbrYBlSkqaosOc-AaLpSkIy8 for path /db/'
[39m
[33m2016-10-04 22:57:06 - DEBUG thaliManager: 'connected pskIdentity Eh3qSnO46ukxMcBUWSp244ltodWfthHoJ2DaXpgJhWA for path /db/'
[39m
[36m2016-10-04 22:57:06 - DEBUG thaliManager: 'connected pskIdentity Tz0YymY8AKnnva7dTNARbrYBlSkqaosOc-AaLpSkIy8 for path /db/ThaliManagerCoordinated/_changes'
[39m
[36m2016-10-04 22:57:06 - DEBUG thaliManager: 'connected pskIdentity 8sSxvMjvsdedQmhfOTY91D3xWgf5suCDGiVZndsiuNw for path /db/ThaliManagerCoordinated/'
[39m
[32m2016-10-04 22:57:06 - DEBUG thaliManager: 'connected pskIdentity b5Cf-2jXmwlnXHqr4rzMLxEQOHN-3XjDohY1hA24tWw for path /db/'
[39m
[33m2016-10-04 22:57:06 - DEBUG thaliManager: 'connected pskIdentity Eh3qSnO46ukxMcBUWSp244ltodWfthHoJ2DaXpgJhWA for path /db/ThaliManagerCoordinated/_changes'
[39m
[32m2016-10-04 22:57:06 - DEBUG thaliManager: 'connected pskIdentity b5Cf-2jXmwlnXHqr4rzMLxEQOHN-3XjDohY1hA24tWw for path /db/ThaliManagerCoordinated/_changes'
[39m
[33m2016-10-04 22:57:06 - DEBUG thaliManager: 'connected pskIdentity EJ_oKVTiPKuUY8n8ozneev1reT8XW1i2j0o3zBU4smU for path /db/'
[39m
[36m2016-10-04 22:57:06 - DEBUG thaliManager: 'connected pskIdentity 8sSxvMjvsdedQmhfOTY91D3xWgf5suCDGiVZndsiuNw for path /db/ThaliManagerCoordinated/_changes'
[39m
[33m2016-10-04 22:57:06 - DEBUG thaliManager: 'connected pskIdentity EJ_oKVTiPKuUY8n8ozneev1reT8XW1i2j0o3zBU4smU for path /db/ThaliManagerCoordinated/_changes'
[39m
[36m2016-10-04 22:57:06 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
[32m2016-10-04 22:57:06 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
[36m2016-10-04 22:57:07 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
[33m2016-10-04 22:57:07 - DEBUG thaliManager: 'connected pskIdentity EJ_oKVTiPKuUY8n8ozneev1reT8XW1i2j0o3zBU4smU for path /db/ThaliManagerCoordinated/_changes'
[39m
[33m2016-10-04 22:57:07 - DEBUG thaliManager: 'connected pskIdentity EJ_oKVTiPKuUY8n8ozneev1reT8XW1i2j0o3zBU4smU for path /db/ThaliManagerCoordinated/_bulk_get'
[39m
[32m2016-10-04 22:57:07 - DEBUG thaliManager: 'connected pskIdentity M1cIKIMo-CG6ya5oULkfIZ0Alqnp84afflI8ZnyXPGE for path /db/ThaliManagerCoordinated/_changes'
[39m
[33m2016-10-04 22:57:07 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
[32m2016-10-04 22:57:07 - DEBUG thaliManager: 'connected pskIdentity b5Cf-2jXmwlnXHqr4rzMLxEQOHN-3XjDohY1hA24tWw for path /db/ThaliManagerCoordinated/_changes'
[39m
[33m2016-10-04 22:57:07 - DEBUG thaliManager: 'connected pskIdentity EJ_oKVTiPKuUY8n8ozneev1reT8XW1i2j0o3zBU4smU for path /db/ThaliManagerCoordinated/'
[39m
[33m2016-10-04 22:57:07 - DEBUG thaliManager: 'connected pskIdentity EJ_oKVTiPKuUY8n8ozneev1reT8XW1i2j0o3zBU4smU for path /db/ThaliManagerCoordinated/_changes'
[39m
[36m2016-10-04 22:57:07 - DEBUG thaliManager: 'connected pskIdentity 8sSxvMjvsdedQmhfOTY91D3xWgf5suCDGiVZndsiuNw for path /db/ThaliManagerCoordinated/_local/thali_BB9Mol5eF-r2JGmVl7pCUArPHhlNwWBR80uePbfm6cYKA1xwAqk0KfC8ZRcPN4v06sCroPMylMN_XI4goZ8fuHM'
[39m
[36m2016-10-04 22:57:07 - DEBUG thaliManager: 'connected pskIdentity 8sSxvMjvsdedQmhfOTY91D3xWgf5suCDGiVZndsiuNw for path /db/ThaliManagerCoordinated/_local/M4yEHcZZ0oRPWZbaFsIwiA%3D%3D'
[39m
[32m# teardown
[39m
[32m2016-10-04 22:57:07 - DEBUG thaliManager: 'connected pskIdentity M1cIKIMo-CG6ya5oULkfIZ0Alqnp84afflI8ZnyXPGE for path /db/ThaliManagerCoordinated/_bulk_get'
[39m
[32m2016-10-04 22:57:07 - DEBUG thaliManager: 'connected pskIdentity b5Cf-2jXmwlnXHqr4rzMLxEQOHN-3XjDohY1hA24tWw for path /db/ThaliManagerCoordinated/_bulk_get'
[39m
[32m2016-10-04 22:57:07 - DEBUG thaliManager: 'connected pskIdentity M1cIKIMo-CG6ya5oULkfIZ0Alqnp84afflI8ZnyXPGE for path /db/ThaliManagerCoordinated/_changes'
[39m
[33m2016-10-04 22:57:07 - DEBUG thaliManager: 'connected pskIdentity Eh3qSnO46ukxMcBUWSp244ltodWfthHoJ2DaXpgJhWA for path /db/ThaliManagerCoordinated/_changes'
[39m
[33m2016-10-04 22:57:07 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
[36m2016-10-04 22:57:07 - DEBUG thaliManager: 'connected pskIdentity Tz0YymY8AKnnva7dTNARbrYBlSkqaosOc-AaLpSkIy8 for path /db/ThaliManagerCoordinated/_changes'
[39m
[33m2016-10-04 22:57:07 - DEBUG thaliManager: 'connected pskIdentity Eh3qSnO46ukxMcBUWSp244ltodWfthHoJ2DaXpgJhWA for path /db/ThaliManagerCoordinated/_bulk_get'
[39m
[32m2016-10-04 22:57:07 - DEBUG thaliManager: 'connected pskIdentity M1cIKIMo-CG6ya5oULkfIZ0Alqnp84afflI8ZnyXPGE for path /db/ThaliManagerCoordinated/_local/thali_BL1wKS0PSSxMPtLbT4-F7YCUqo3AGAafyyZxnyRXp76Jlu34oqZSnFTV1RI-9qUrv05WQqRuJNdxBoyV_Q2iS48'
[39m
[32m2016-10-04 22:57:07 - DEBUG thaliManager: 'connected pskIdentity M1cIKIMo-CG6ya5oULkfIZ0Alqnp84afflI8ZnyXPGE for path /db/ThaliManagerCoordinated/_local/Dkvh6kvMUmwvfJzrIxELvA%3D%3D'
[39m
[32m2016-10-04 22:57:07 - DEBUG thaliManager: 'connected pskIdentity b5Cf-2jXmwlnXHqr4rzMLxEQOHN-3XjDohY1hA24tWw for path /db/ThaliManagerCoordinated/_changes'
[39m
[33m# teardown
[39m
[33m2016-10-04 22:57:07 - DEBUG thaliManager: 'connected pskIdentity EJ_oKVTiPKuUY8n8ozneev1reT8XW1i2j0o3zBU4smU for path /db/ThaliManagerCoordinated/_local/thali_BB9Mol5eF-r2JGmVl7pCUArPHhlNwWBR80uePbfm6cYKA1xwAqk0KfC8ZRcPN4v06sCroPMylMN_XI4goZ8fuHM'
[39m
[32m2016-10-04 22:57:07 - DEBUG thaliManager: 'connected pskIdentity b5Cf-2jXmwlnXHqr4rzMLxEQOHN-3XjDohY1hA24tWw for path /db/ThaliManagerCoordinated/_local/thali_BLnTZaH1swfxGEQhKiBEZXsFLnIb2CgUujZTuTyXVFASQ5Kb3RXLFDHeuiF-QreXt8WPIL9d4iAgYu-op2xt4zU'
[39m
[33m2016-10-04 22:57:07 - DEBUG thaliManager: 'connected pskIdentity EJ_oKVTiPKuUY8n8ozneev1reT8XW1i2j0o3zBU4smU for path /db/ThaliManagerCoordinated/_local/u4raXcB_BIRfR3efHvIGDg%3D%3D'
[39m
[33m2016-10-04 22:57:07 - DEBUG thaliManager: 'connected pskIdentity EJ_oKVTiPKuUY8n8ozneev1reT8XW1i2j0o3zBU4smU for path /db/ThaliManagerCoordinated/_changes'
[39m
[32m2016-10-04 22:57:07 - DEBUG thaliManager: 'connected pskIdentity b5Cf-2jXmwlnXHqr4rzMLxEQOHN-3XjDohY1hA24tWw for path /db/ThaliManagerCoordinated/_local/K4KZUYcWUop5Hp1CbWd_Jw%3D%3D'
[39m
[36m2016-10-04 22:57:07 - DEBUG thaliManager: 'connected pskIdentity 8sSxvMjvsdedQmhfOTY91D3xWgf5suCDGiVZndsiuNw for path /db/ThaliManagerCoordinated/_changes'
[39m
[32m2016-10-04 22:57:07 - DEBUG thaliManager: 'connected pskIdentity b5Cf-2jXmwlnXHqr4rzMLxEQOHN-3XjDohY1hA24tWw for path /db/ThaliManagerCoordinated/'
2016-10-04 22:57:07 - DEBUG thaliManager: 'connected pskIdentity b5Cf-2jXmwlnXHqr4rzMLxEQOHN-3XjDohY1hA24tWw for path /db/ThaliManagerCoordinated/_changes'
[39m
[33m2016-10-04 22:57:07 - DEBUG thaliManager: 'connected pskIdentity Eh3qSnO46ukxMcBUWSp244ltodWfthHoJ2DaXpgJhWA for path /db/ThaliManagerCoordinated/_changes'
[39m
2016-10-04 22:57:07 - DEBUG UnitTestFramework: '#run ok: 'test repeat write 2''

2016-10-04 22:57:07 - DEBUG UnitTestFramework: '#teardown: 'test repeat write 2''

[36m2016-10-04 22:57:07 - DEBUG thaliManager: 'connected pskIdentity Tz0YymY8AKnnva7dTNARbrYBlSkqaosOc-AaLpSkIy8 for path /db/ThaliManagerCoordinated/_bulk_get'
[39m
[33m2016-10-04 22:57:07 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
[39m
[33m2016-10-04 22:57:07 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
[39m
[33m2016-10-04 22:57:07 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
[39m
[32m2016-10-04 22:57:07 - DEBUG thaliManager: 'connected pskIdentity b5Cf-2jXmwlnXHqr4rzMLxEQOHN-3XjDohY1hA24tWw for path /db/ThaliManagerCoordinated/_bulk_docs'
[39m
[33m2016-10-04 22:57:07 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
[39m
[32m2016-10-04 22:57:07 - DEBUG thaliManager: 'connected pskIdentity M1cIKIMo-CG6ya5oULkfIZ0Alqnp84afflI8ZnyXPGE for path /db/ThaliManagerCoordinated/'
[39m
[32m2016-10-04 22:57:07 - DEBUG thaliManager: 'connected pskIdentity M1cIKIMo-CG6ya5oULkfIZ0Alqnp84afflI8ZnyXPGE for path /db/ThaliManagerCoordinated/_changes'
[39m
[36m2016-10-04 22:57:07 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
[39m
[36m2016-10-04 22:57:07 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
[39m
[36m2016-10-04 22:57:07 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
[39m
[36m2016-10-04 22:57:07 - DEBUG thaliReplicationPeerAction: 'Got error in update, waiting for main loop to detect and handle -  500 connect ECONNREFUSED'
[39m
[36m# teardown
[39m
[32m2016-10-04 22:57:07 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","errno":"ECONNRESET","syscall":"read","status":500}'
[39m
[32m2016-10-04 22:57:07 - DEBUG thaliReplicationPeerAction: 'Got error in update, waiting for main loop to detect and handle -  500 read ECONNRESET'
[39m
[32m2016-10-04 22:57:07 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
[39m
[32m2016-10-04 22:57:07 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
[39m
[32m2016-10-04 22:57:07 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
[39m
[32m2016-10-04 22:57:07 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
[39m
[32m2016-10-04 22:57:07 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
[39m
[32m2016-10-04 22:57:07 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
[39m
[36m2016-10-04 22:57:07 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up -1'
[39m
[36m2016-10-04 22:57:07 - DEBUG thaliPeerPoolDefault: 'Got err   Could establish TCP connection but couldn't keep it running'
[39m
[33m2016-10-04 22:57:07 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up -1'
[39m
[33m2016-10-04 22:57:07 - DEBUG thaliPeerPoolDefault: 'Got err   Could establish TCP connection but couldn't keep it running'
[39m
[33m2016-10-04 22:57:07 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
[39m
[33m2016-10-04 22:57:07 - DEBUG thaliReplicationPeerAction: 'Got error in update, waiting for main loop to detect and handle -  500 socket hang up -1'
[39m
[33m2016-10-04 22:57:07 - DEBUG thaliManager: 'stopping advertising and listening'
[39m
[33m2016-10-04 22:57:07 - DEBUG thaliManager: 'stopping listening for advertisements'
[39m
[33m2016-10-04 22:57:07 - DEBUG thaliManager: 'stopping ThaliMobile'
[39m
[36m2016-10-04 22:57:07 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
[39m
[36m2016-10-04 22:57:07 - DEBUG thaliReplicationPeerAction: 'Got error in update, waiting for main loop to detect and handle -  500 socket hang up'
[39m
[33m# setup
[39m
[36m2016-10-04 22:57:07 - DEBUG thaliManager: 'connected pskIdentity 8sSxvMjvsdedQmhfOTY91D3xWgf5suCDGiVZndsiuNw for path /db/ThaliManagerCoordinated/_bulk_docs'
[39m
[32m2016-10-04 22:57:07 - DEBUG thaliManager: 'stopping advertising and listening'
[39m
[32m2016-10-04 22:57:07 - DEBUG thaliManager: 'stopping listening for advertisements'
[39m
[32m2016-10-04 22:57:07 - DEBUG thaliManager: 'stopping ThaliMobile'
[39m
[32m# setup
[39m
[36m2016-10-04 22:57:07 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
[39m
[36m2016-10-04 22:57:08 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
[39m
[36m2016-10-04 22:57:08 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
[39m
[36m2016-10-04 22:57:08 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
[39m
[36m2016-10-04 22:57:08 - DEBUG thaliManager: 'stopping advertising and listening'
[39m
[36m2016-10-04 22:57:08 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
[39m
[36m2016-10-04 22:57:08 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-10-04 22:57:08 - DEBUG thaliManager: 'stopping ThaliMobile'
# setup
[39m
2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#teardown ok: 'test repeat write 2''

2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#setup: '#startListeningForAdvertisements should fail if start not called''

[36m# #startListeningForAdvertisements should fail if start not called
[39m
[32m# #startListeningForAdvertisements should fail if start not called
[39m
[33m# #startListeningForAdvertisements should fail if start not called
[39m
2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#setup ok: '#startListeningForAdvertisements should fail if start not called''

2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#run: '#startListeningForAdvertisements should fail if start not called''

[36mok 256 specific error should be returned
# teardown
[39m
[33mok 256 specific error should be returned
# teardown
[39m
[32mok 256 specific error should be returned
# teardown
[39m
2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#run ok: '#startListeningForAdvertisements should fail if start not called''

2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#teardown: '#startListeningForAdvertisements should fail if start not called''

[36mok 257 error should be null
ok 258 error should be null
# setup
[39m
[32mok 257 error should be null
ok 258 error should be null
# setup
[39m
[33mok 257 error should be null
ok 258 error should be null
[39m
[33m# setup
[39m
2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#teardown ok: '#startListeningForAdvertisements should fail if start not called''

2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening should fail if start not called''

[36m# #startUpdateAdvertisingAndListening should fail if start not called
[39m
[32m# #startUpdateAdvertisingAndListening should fail if start not called
[39m
[33m# #startUpdateAdvertisingAndListening should fail if start not called
[39m
2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening should fail if start not called''
2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening should fail if start not called''

[36mok 259 specific error should be returned
# teardown
[39m
[33mok 259 specific error should be returned
# teardown
[39m
[32mok 259 specific error should be returned
# teardown
[39m
2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening should fail if start not called''

2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening should fail if start not called''

[36mok 260 error should be null
ok 261 error should be null
# setup
[39m
[32mok 260 error should be null
ok 261 error should be null
# setup
[39m
[33mok 260 error should be null
ok 261 error should be null
[39m
[33m# setup
[39m
2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening should fail if start not called''

2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#setup: 'should be able to call #stopListeningForAdvertisements many times''

[36m# should be able to call #stopListeningForAdvertisements many times
[39m
[32m# should be able to call #stopListeningForAdvertisements many times
[39m
[33m# should be able to call #stopListeningForAdvertisements many times
[39m
2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #stopListeningForAdvertisements many times''

2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#run: 'should be able to call #stopListeningForAdvertisements many times''

[36mok 262 error should be null
ok 263 error should be null
ok 264 error should be null
ok 265 error should be null
# teardown
[39m
[32mok 262 error should be null
ok 263 error should be null
ok 264 error should be null
ok 265 error should be null
# teardown
[39m
[33mok 262 error should be null
[39m
[33mok 263 error should be null
[39m
[33mok 264 error should be null
[39m
[33mok 265 error should be null
[39m
[33m# teardown
[39m
2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #stopListeningForAdvertisements many times''

2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #stopListeningForAdvertisements many times''

[36mok 266 error should be null
ok 267 error should be null
# setup
[39m
[33mok 266 error should be null
ok 267 error should be null
# setup
[39m
[32mok 266 error should be null
ok 267 error should be null
# setup
[39m
2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #stopListeningForAdvertisements many times''

2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#setup: 'should be able to call #startListeningForAdvertisements many times''

[36m# should be able to call #startListeningForAdvertisements many times
[39m
[32m# should be able to call #startListeningForAdvertisements many times
[39m
[33m# should be able to call #startListeningForAdvertisements many times
[39m
2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #startListeningForAdvertisements many times''

2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#run: 'should be able to call #startListeningForAdvertisements many times''

[36mok 268 error should be null
ok 269 error should be null
ok 270 error should be null
ok 271 error should be null
# teardown
[39m
[33mok 268 error should be null
ok 269 error should be null
ok 270 error should be null
ok 271 error should be null
# teardown
[39m
[32mok 268 error should be null
ok 269 error should be null
ok 270 error should be null
ok 271 error should be null
[39m
[32m# teardown
[39m
2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #startListeningForAdvertisements many times''

2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #startListeningForAdvertisements many times''

[36m2016-10-04 22:57:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 272 error should be null
ok 273 error should be null
# setup
[39m
[32m2016-10-04 22:57:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 272 error should be null
ok 273 error should be null
# setup
[39m
[33m2016-10-04 22:57:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[39m
[33mok 272 error should be null
ok 273 error should be null
[39m
[33m# setup
[39m
2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #startListeningForAdvertisements many times''

2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#setup: 'should be able to call #startUpdateAdvertisingAndListening many times''

[36m# should be able to call #startUpdateAdvertisingAndListening many times
[39m
[32m# should be able to call #startUpdateAdvertisingAndListening many times
[39m
[33m# should be able to call #startUpdateAdvertisingAndListening many times
[39m
2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #startUpdateAdvertisingAndListening many times''

2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#run: 'should be able to call #startUpdateAdvertisingAndListening many times''

[33m2016-10-04 22:57:08 - DEBUG thaliWifiInfrastructure: 'listening 51117'
ok 274 error should be null
ok 275 error should be null
[39m
[33mok 276 error should be null
ok 277 error should be null
[39m
[36m2016-10-04 22:57:08 - DEBUG thaliWifiInfrastructure: 'listening 51118'
ok 274 error should be null
ok 275 error should be null
[39m
[32m2016-10-04 22:57:08 - DEBUG thaliWifiInfrastructure: 'listening 51119'
ok 274 error should be null
[39m
[33m# teardown
[39m
[32mok 275 error should be null
[39m
[32mok 276 error should be null
ok 277 error should be null
[39m
[36mok 276 error should be null
ok 277 error should be null
[39m
[32m# teardown
[39m
[36m# teardown
[39m
2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #startUpdateAdvertisingAndListening many times''

2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #startUpdateAdvertisingAndListening many times''

[36m2016-10-04 22:57:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[39m
[36mok 278 error should be null
ok 279 error should be null
[39m
[33m2016-10-04 22:57:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 278 error should be null
[39m
[33mok 279 error should be null
# setup
[39m
[32m2016-10-04 22:57:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 278 error should be null
ok 279 error should be null
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #startUpdateAdvertisingAndListening many times''

2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#setup: 'should be able to call #stopAdvertisingAndListening many times''

[36m# should be able to call #stopAdvertisingAndListening many times
[39m
[32m# should be able to call #stopAdvertisingAndListening many times
[39m
[33m# should be able to call #stopAdvertisingAndListening many times
[39m
2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #stopAdvertisingAndListening many times''
2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#run: 'should be able to call #stopAdvertisingAndListening many times''

[36mok 280 error should be null
ok 281 error should be null
ok 282 error should be null
ok 283 error should be null
# teardown
[39m
[32mok 280 error should be null
ok 281 error should be null
ok 282 error should be null
ok 283 error should be null
[39m
[33mok 280 error should be null
ok 281 error should be null
ok 282 error should be null
ok 283 error should be null
# teardown
[39m
[32m# teardown
[39m
2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #stopAdvertisingAndListening many times''

2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #stopAdvertisingAndListening many times''

[36mok 284 error should be null
ok 285 error should be null
# setup
[39m
[32mok 284 error should be null
ok 285 error should be null
[39m
[33mok 284 error should be null
ok 285 error should be null
# setup
[39m
[32m# setup
[39m
2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #stopAdvertisingAndListening many times''

2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#setup: '#start should fail if called twice in a row''

[36m# #start should fail if called twice in a row
[39m
[32m# #start should fail if called twice in a row
[39m
[33m# #start should fail if called twice in a row
[39m
2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#setup ok: '#start should fail if called twice in a row''
2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#run: '#start should fail if called twice in a row''

[32mok 286 first call should succeed
ok 287 first call should succeed
ok 288 specific error should be returned
[39m
[33mok 286 first call should succeed
[39m
[33mok 287 first call should succeed
[39m
[33mok 288 specific error should be returned
[39m
[33m# teardown
[39m
[32m# teardown
[39m
[36mok 286 first call should succeed
ok 287 first call should succeed
ok 288 specific error should be returned
[39m
[36m# teardown
[39m
2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#run ok: '#start should fail if called twice in a row''

2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#teardown: '#start should fail if called twice in a row''

[36mok 289 error should be null
ok 290 error should be null
# setup
[39m
[32mok 289 error should be null
ok 290 error should be null
# setup
[39m
[33mok 289 error should be null
[39m
[33mok 290 error should be null
[39m
[33m# setup
[39m
2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#teardown ok: '#start should fail if called twice in a row''

2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#setup: 'does not emit duplicate discoveryAdvertisingStateUpdate''

[36m# does not emit duplicate discoveryAdvertisingStateUpdate
[39m
[33m# does not emit duplicate discoveryAdvertisingStateUpdate
[39m
[32m# does not emit duplicate discoveryAdvertisingStateUpdate
[39m
2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#setup ok: 'does not emit duplicate discoveryAdvertisingStateUpdate''

2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#run: 'does not emit duplicate discoveryAdvertisingStateUpdate''

[33m2016-10-04 22:57:08 - DEBUG thaliWifiInfrastructure: 'listening 51120'
[39m
[33m2016-10-04 22:57:08 - INFO thaliMobile: 'Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":false,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}'
[39m
[33m2016-10-04 22:57:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[39m
[33mok 291 called only once
[39m
[33mok 292 discovery state matches
ok 293 advertising state matches
[39m
[33m2016-10-04 22:57:08 - INFO thaliMobile: 'Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":false,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}'
[39m
[33m2016-10-04 22:57:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[39m
[32m2016-10-04 22:57:08 - DEBUG thaliWifiInfrastructure: 'listening 51122'
[39m
[33m# teardown
[39m
[32m2016-10-04 22:57:08 - INFO thaliMobile: 'Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":false,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}'
[39m
[36m2016-10-04 22:57:08 - DEBUG thaliWifiInfrastructure: 'listening 51121'
[39m
[32m2016-10-04 22:57:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 291 called only once
ok 292 discovery state matches
ok 293 advertising state matches
2016-10-04 22:57:08 - INFO thaliMobile: 'Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":false,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}'
2016-10-04 22:57:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[39m
[32m# teardown
[39m
[36m2016-10-04 22:57:08 - INFO thaliMobile: 'Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":false,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}'
[39m
[36m2016-10-04 22:57:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[39m
[36mok 291 called only once
[39m
[36mok 292 discovery state matches
[39m
[36mok 293 advertising state matches
[39m
[36m2016-10-04 22:57:08 - INFO thaliMobile: 'Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":false,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}'
[39m
[36m2016-10-04 22:57:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[39m
[36m# teardown
[39m
2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#run ok: 'does not emit duplicate discoveryAdvertisingStateUpdate''

2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#teardown: 'does not emit duplicate discoveryAdvertisingStateUpdate''

[33m2016-10-04 22:57:08 - INFO thaliMobile: 'Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}'
[39m
[33m2016-10-04 22:57:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[39m
[33m2016-10-04 22:57:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[39m
[33mok 294 error should be null
[39m
[33mok 295 error should be null
[39m
[33m# setup
[39m
[36m2016-10-04 22:57:08 - INFO thaliMobile: 'Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}'
[39m
[36m2016-10-04 22:57:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[39m
[32m2016-10-04 22:57:08 - INFO thaliMobile: 'Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}'
[39m
[32m2016-10-04 22:57:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[39m
[32m2016-10-04 22:57:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[39m
[32mok 294 error should be null
[39m
[36m2016-10-04 22:57:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[39m
[32mok 295 error should be null
[39m
[36mok 294 error should be null
ok 295 error should be null
[39m
[32m# setup
[39m
[36m# setup
[39m
2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#teardown ok: 'does not emit duplicate discoveryAdvertisingStateUpdate''
2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#setup: 'does not send duplicate availability changes''

[36m# does not send duplicate availability changes
[39m
[33m# does not send duplicate availability changes
[39m
[32m# does not send duplicate availability changes
[39m
2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#setup ok: 'does not send duplicate availability changes''

2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#run: 'does not send duplicate availability changes''

[33mok 296 should be called once
ok 297 should not have been called more than once
# teardown
[39m
[36mok 296 should be called once
ok 297 should not have been called more than once
[39m
[36m# teardown
[39m
[32mok 296 should be called once
[39m
[32mok 297 should not have been called more than once
[39m
[32m# teardown
[39m
2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#run ok: 'does not send duplicate availability changes''

2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#teardown: 'does not send duplicate availability changes''

[36mok 298 error should be null
ok 299 error should be null
# setup
[39m
[33mok 298 error should be null
ok 299 error should be null
[39m
[33m# setup
[39m
[32mok 298 error should be null
[39m
[32mok 299 error should be null
[39m
[32m# setup
[39m
2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#teardown ok: 'does not send duplicate availability changes''

2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#setup: 'can get the network status''

[36m# can get the network status
[39m
[33m# can get the network status
[39m
[32m# can get the network status
[39m
2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#setup ok: 'can get the network status''

2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#run: 'can get the network status''

[36mok 300 network status should have certain non-empty properties
# teardown
[39m
[32mok 300 network status should have certain non-empty properties
[39m
[33mok 300 network status should have certain non-empty properties
[39m
[32m# teardown
[39m
[33m# teardown
[39m
2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#run ok: 'can get the network status''

2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#teardown: 'can get the network status''

[36mok 301 error should be null
[39m
[36mok 302 error should be null
[39m
[36m# setup
[39m
[33mok 301 error should be null
ok 302 error should be null
# setup
[39m
[32mok 301 error should be null
[39m
[32mok 302 error should be null
[39m
[32m# setup
[39m
2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#teardown ok: 'can get the network status''
2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#setup: 'wifi peer is marked unavailable if announcements stop''

[36m# wifi peer is marked unavailable if announcements stop
[39m
[32m# wifi peer is marked unavailable if announcements stop
[39m
[33m# wifi peer is marked unavailable if announcements stop
[39m
2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#setup ok: 'wifi peer is marked unavailable if announcements stop''

2016-10-04 22:57:08 - DEBUG UnitTestFramework: '#run: 'wifi peer is marked unavailable if announcements stop''

[33mok 303 host address should match
ok 304 port should match
[39m
[36mok 303 host address should match
ok 304 port should match
[39m
[32mok 303 host address should match
[39m
[32mok 304 port should match
[39m
[33mok 305 host address should be null
[39m
[33mok 306 port should should be null
[39m
[33m# teardown
[39m
[36mok 305 host address should be null
ok 306 port should should be null
[39m
[36m# teardown
[39m
[32mok 305 host address should be null
[39m
[32mok 306 port should should be null
[39m
[32m# teardown
[39m
2016-10-04 22:57:13 - DEBUG UnitTestFramework: '#run ok: 'wifi peer is marked unavailable if announcements stop''
2016-10-04 22:57:13 - DEBUG UnitTestFramework: '#teardown: 'wifi peer is marked unavailable if announcements stop''

[36m2016-10-04 22:57:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 307 error should be null
ok 308 error should be null
# setup
[39m
[32m2016-10-04 22:57:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 307 error should be null
ok 308 error should be null
# setup
[39m
[33m2016-10-04 22:57:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 307 error should be null
ok 308 error should be null
# setup
[39m
2016-10-04 22:57:13 - DEBUG UnitTestFramework: '#teardown ok: 'wifi peer is marked unavailable if announcements stop''

2016-10-04 22:57:13 - DEBUG UnitTestFramework: '#setup: 'network changes emitted correctly''

[36m# network changes emitted correctly
[39m
[33m# network changes emitted correctly
[39m
[32m# network changes emitted correctly
[39m
2016-10-04 22:57:13 - DEBUG UnitTestFramework: '#setup ok: 'network changes emitted correctly''

2016-10-04 22:57:13 - DEBUG UnitTestFramework: '#run: 'network changes emitted correctly''

[36m2016-10-04 22:57:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
ok 309 wifi is off
2016-10-04 22:57:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
ok 310 wifi is on
# teardown
[39m
[32m2016-10-04 22:57:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
ok 309 wifi is off
2016-10-04 22:57:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
ok 310 wifi is on
# teardown
[39m
[33m2016-10-04 22:57:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
ok 309 wifi is off
[39m
[33m2016-10-04 22:57:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
ok 310 wifi is on
# teardown
[39m
2016-10-04 22:57:13 - DEBUG UnitTestFramework: '#run ok: 'network changes emitted correctly''
2016-10-04 22:57:13 - DEBUG UnitTestFramework: '#teardown: 'network changes emitted correctly''

[36mok 311 error should be null
ok 312 error should be null
# setup
[39m
[32mok 311 error should be null
ok 312 error should be null
# setup
[39m
[33mok 311 error should be null
ok 312 error should be null
# setup
[39m
2016-10-04 22:57:13 - DEBUG UnitTestFramework: '#teardown ok: 'network changes emitted correctly''

2016-10-04 22:57:13 - DEBUG UnitTestFramework: '#setup: 'network changes not emitted in stopped state''

[36m# network changes not emitted in stopped state
[39m
[32m# network changes not emitted in stopped state
[39m
[33m# network changes not emitted in stopped state
[39m
2016-10-04 22:57:13 - DEBUG UnitTestFramework: '#setup ok: 'network changes not emitted in stopped state''

2016-10-04 22:57:13 - DEBUG UnitTestFramework: '#run: 'network changes not emitted in stopped state''

[36mok 313 event was not emitted
2016-10-04 22:57:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-04 22:57:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
# teardown
[39m
[32mok 313 event was not emitted
2016-10-04 22:57:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-04 22:57:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
# teardown
[39m
[33mok 313 event was not emitted
2016-10-04 22:57:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-04 22:57:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
[39m
[33m# teardown
[39m
2016-10-04 22:57:13 - DEBUG UnitTestFramework: '#run ok: 'network changes not emitted in stopped state''

2016-10-04 22:57:13 - DEBUG UnitTestFramework: '#teardown: 'network changes not emitted in stopped state''

[36mok 314 error should be null
[39m
[36mok 315 error should be null
[39m
[36m# setup
[39m
[33mok 314 error should be null
[39m
[33mok 315 error should be null
[39m
[33m# setup
[39m
[32mok 314 error should be null
[39m
[32mok 315 error should be null
[39m
[32m# setup
[39m
2016-10-04 22:57:13 - DEBUG UnitTestFramework: '#teardown ok: 'network changes not emitted in stopped state''

2016-10-04 22:57:13 - DEBUG UnitTestFramework: '#setup: 'calls correct starts when network changes''

[36m# calls correct starts when network changes
[39m
[32m# calls correct starts when network changes
[39m
[33m# calls correct starts when network changes
[39m
2016-10-04 22:57:13 - DEBUG UnitTestFramework: '#setup ok: 'calls correct starts when network changes''

2016-10-04 22:57:13 - DEBUG UnitTestFramework: '#run: 'calls correct starts when network changes''

[36m2016-10-04 22:57:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
[39m
[32m2016-10-04 22:57:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
[39m
[36mok 316 specific error expected
[39m
[36mok 317 specific error expected
[39m
[32mok 316 specific error expected
[39m
[32mok 317 specific error expected
[39m
[36m2016-10-04 22:57:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
[39m
[32m2016-10-04 22:57:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
[39m
[36m2016-10-04 22:57:13 - INFO thaliMobile: 'Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":true,"advertisingActive":true}'
[39m
[32m2016-10-04 22:57:13 - INFO thaliMobile: 'Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":true,"advertisingActive":true}'
[39m
[32m2016-10-04 22:57:13 - DEBUG thaliWifiInfrastructure: 'listening 51123'
[39m
[36m2016-10-04 22:57:13 - DEBUG thaliWifiInfrastructure: 'listening 51124'
[39m
[32mok 318 startListeningForAdvertisements should have been called
[39m
[32mok 319 startUpdateAdvertisingAndListening should have been called
[39m
[32m# teardown
[39m
[33m2016-10-04 22:57:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
[39m
[36mok 318 startListeningForAdvertisements should have been called
[39m
[36mok 319 startUpdateAdvertisingAndListening should have been called
[39m
[33mok 316 specific error expected
[39m
[33mok 317 specific error expected
[39m
[33m2016-10-04 22:57:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
[39m
[36m# teardown
[39m
[33m2016-10-04 22:57:13 - INFO thaliMobile: 'Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":true,"advertisingActive":true}'
[39m
[33m2016-10-04 22:57:13 - DEBUG thaliWifiInfrastructure: 'listening 51125'
[39m
[33mok 318 startListeningForAdvertisements should have been called
[39m
[33mok 319 startUpdateAdvertisingAndListening should have been called
[39m
[33m# teardown
[39m
2016-10-04 22:57:13 - DEBUG UnitTestFramework: '#run ok: 'calls correct starts when network changes''

2016-10-04 22:57:13 - DEBUG UnitTestFramework: '#teardown: 'calls correct starts when network changes''

[32m2016-10-04 22:57:13 - INFO thaliMobile: 'Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}'
[39m
[36m2016-10-04 22:57:13 - INFO thaliMobile: 'Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}'
[39m
[32m2016-10-04 22:57:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[39m
[32m2016-10-04 22:57:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[39m
[32mok 320 error should be null
[39m
[32mok 321 error should be null
[39m
[36m2016-10-04 22:57:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[39m
[36m2016-10-04 22:57:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[39m
[36mok 320 error should be null
[39m
[36mok 321 error should be null
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m2016-10-04 22:57:13 - INFO thaliMobile: 'Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}'
[39m
[33m2016-10-04 22:57:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-10-04 22:57:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[39m
[33mok 320 error should be null
[39m
[33mok 321 error should be null
[39m
[33m# setup
[39m
2016-10-04 22:57:13 - DEBUG UnitTestFramework: '#teardown ok: 'calls correct starts when network changes''

2016-10-04 22:57:13 - DEBUG UnitTestFramework: '#setup: 'peer is marked unavailable if port number changes''

[36m# peer is marked unavailable if port number changes
[39m
[32m# peer is marked unavailable if port number changes
[39m
[33m# peer is marked unavailable if port number changes
[39m
2016-10-04 22:57:13 - DEBUG UnitTestFramework: '#setup ok: 'peer is marked unavailable if port number changes''

2016-10-04 22:57:13 - DEBUG UnitTestFramework: '#run: 'peer is marked unavailable if port number changes''

[32mok 322 peer should have a non-empty identifier
[39m
[32mok 323 peer should have a non-empty host address
ok 324 peer should have port number
[39m
[36mok 322 peer should have a non-empty identifier
[39m
[36mok 323 peer should have a non-empty host address
[39m
[36mok 324 peer should have port number
[39m
[32mok 325 peer should have suggested timeout
[39m
[36mok 325 peer should have suggested timeout
[39m
[36mok 326 peer should have a connection type
[39m
[36mok 327 connection type should match one of the pre-defined types
[39m
[32mok 326 peer should have a connection type
[39m
[32mok 327 connection type should match one of the pre-defined types
[39m
[32mok 328 peer should have a non-empty identifier
[39m
[32mok 329 host address should be null
[39m
[32mok 330 port number should be null
[39m
[32mok 331 peer should have suggested timeout
[39m
[32mok 332 peer should have a connection type
[39m
[32mok 333 connection type should match one of the pre-defined types
[39m
[36mok 328 peer should have a non-empty identifier
[39m
[36mok 329 host address should be null
[39m
[36mok 330 port number should be null
[39m
[32mok 334 port number must match
[39m
[32mok 335 peer should have a non-empty identifier
ok 336 peer should have a non-empty host address
[39m
[32mok 337 peer should have port number
[39m
[32mok 338 peer should have suggested timeout
[39m
[36mok 331 peer should have suggested timeout
[39m
[32mok 339 peer should have a connection type
[39m
[32mok 340 connection type should match one of the pre-defined types
[39m
[36mok 332 peer should have a connection type
[39m
[32m# teardown
[39m
[36mok 333 connection type should match one of the pre-defined types
[39m
[36mok 334 port number must match
[39m
[36mok 335 peer should have a non-empty identifier
[39m
[36mok 336 peer should have a non-empty host address
[39m
[36mok 337 peer should have port number
[39m
[36mok 338 peer should have suggested timeout
[39m
[36mok 339 peer should have a connection type
[39m
[36mok 340 connection type should match one of the pre-defined types
[39m
[36m# teardown
[39m
[33mok 322 peer should have a non-empty identifier
[39m
[33mok 323 peer should have a non-empty host address
ok 324 peer should have port number
[39m
[33mok 325 peer should have suggested timeout
[39m
[33mok 326 peer should have a connection type
[39m
[33mok 327 connection type should match one of the pre-defined types
[39m
[33mok 328 peer should have a non-empty identifier
[39m
[33mok 329 host address should be null
ok 330 port number should be null
[39m
[33mok 331 peer should have suggested timeout
[39m
[33mok 332 peer should have a connection type
[39m
[33mok 333 connection type should match one of the pre-defined types
[39m
[33mok 334 port number must match
[39m
[33mok 335 peer should have a non-empty identifier
ok 336 peer should have a non-empty host address
[39m
[33mok 337 peer should have port number
[39m
[33mok 338 peer should have suggested timeout
[39m
[33mok 339 peer should have a connection type
[39m
[33mok 340 connection type should match one of the pre-defined types
[39m
[33m# teardown
[39m
2016-10-04 22:57:13 - DEBUG UnitTestFramework: '#run ok: 'peer is marked unavailable if port number changes''

2016-10-04 22:57:13 - DEBUG UnitTestFramework: '#teardown: 'peer is marked unavailable if port number changes''

[36mok 341 error should be null
[39m
[36mok 342 error should be null
[39m
[32mok 341 error should be null
ok 342 error should be null
[39m
[32m# setup
[39m
[36m# setup
[39m
[33mok 341 error should be null
ok 342 error should be null
[39m
[33m# setup
[39m
2016-10-04 22:57:13 - DEBUG UnitTestFramework: '#teardown ok: 'peer is marked unavailable if port number changes''

2016-10-04 22:57:13 - DEBUG UnitTestFramework: '#setup: 'when network connection is lost a peer should be marked unavailable''

[36m# when network connection is lost a peer should be marked unavailable
[39m
[32m# when network connection is lost a peer should be marked unavailable
[39m
[33m# when network connection is lost a peer should be marked unavailable
[39m
2016-10-04 22:57:13 - DEBUG UnitTestFramework: '#setup ok: 'when network connection is lost a peer should be marked unavailable''

2016-10-04 22:57:13 - DEBUG UnitTestFramework: '#run: 'when network connection is lost a peer should be marked unavailable''

[36m2016-10-04 22:57:13 - INFO testUtils: 'Toggling radios to: false'
[39m
[32m2016-10-04 22:57:13 - INFO testUtils: 'Toggling radios to: false'
[39m
[32m2016-10-04 22:57:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
[39m
[36m2016-10-04 22:57:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
[39m
[36m2016-10-04 22:57:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
[39m
[32m2016-10-04 22:57:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
[39m
[36mok 343 peer should have a non-empty identifier
[39m
[36mok 344 host address should be null
[39m
[36mok 345 port number should be null
[39m
[36mok 346 peer should have suggested timeout
[39m
[32mok 343 peer should have a non-empty identifier
ok 344 host address should be null
[39m
[32mok 345 port number should be null
[39m
[36mok 347 peer should have a connection type
[39m
[36mok 348 connection type should match one of the pre-defined types
[39m
[36m2016-10-04 22:57:13 - INFO testUtils: 'Toggling radios to: true'
[39m
[32mok 346 peer should have suggested timeout
[39m
[32mok 347 peer should have a connection type
[39m
[32mok 348 connection type should match one of the pre-defined types
[39m
[32m2016-10-04 22:57:13 - INFO testUtils: 'Toggling radios to: true'
[39m
[36m2016-10-04 22:57:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
[39m
[36m# teardown
[39m
[32m2016-10-04 22:57:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
[39m
[32m# teardown
[39m
[36m2016-10-04 22:57:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
[39m
[32m2016-10-04 22:57:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
[39m
[33m2016-10-04 22:57:13 - INFO testUtils: 'Toggling radios to: false'
[39m
[33m2016-10-04 22:57:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
[39m
[33m2016-10-04 22:57:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
[39m
[33mok 343 peer should have a non-empty identifier
[39m
[33mok 344 host address should be null
ok 345 port number should be null
ok 346 peer should have suggested timeout
[39m
[33mok 347 peer should have a connection type
ok 348 connection type should match one of the pre-defined types
[39m
[33m2016-10-04 22:57:13 - INFO testUtils: 'Toggling radios to: true'
[39m
[33m2016-10-04 22:57:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
[39m
[33m# teardown
[39m
[33m2016-10-04 22:57:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
[39m
2016-10-04 22:57:13 - DEBUG UnitTestFramework: '#run ok: 'when network connection is lost a peer should be marked unavailable''

2016-10-04 22:57:13 - DEBUG UnitTestFramework: '#teardown: 'when network connection is lost a peer should be marked unavailable''

[36mok 349 error should be null
[39m
[36mok 350 error should be null
[39m
[36m# setup
[39m
[32mok 349 error should be null
[39m
[32mok 350 error should be null
[39m
[32m# setup
[39m
[33mok 349 error should be null
ok 350 error should be null
[39m
[33m# setup
[39m
2016-10-04 22:57:13 - DEBUG UnitTestFramework: '#teardown ok: 'when network connection is lost a peer should be marked unavailable''

2016-10-04 22:57:13 - DEBUG UnitTestFramework: '#setup: 'peer should be found once after listening and discovery started''

[36m# peer should be found once after listening and discovery started
[39m
[33m# peer should be found once after listening and discovery started
[39m
[32m# peer should be found once after listening and discovery started
[39m
2016-10-04 22:57:13 - DEBUG UnitTestFramework: '#setup ok: 'peer should be found once after listening and discovery started''

2016-10-04 22:57:13 - DEBUG UnitTestFramework: '#run: 'peer should be found once after listening and discovery started''

[36mok 351 error should be null
ok 352 error should be null
[39m
[33mok 351 error should be null
ok 352 error should be null
[39m
[36m2016-10-04 22:57:13 - DEBUG thaliWifiInfrastructure: 'listening 51126'
[39m
[33m2016-10-04 22:57:13 - DEBUG thaliWifiInfrastructure: 'listening 51127'
[39m
[33mok 353 error should be null
ok 354 error should be null
[39m
[33mok 355 error should be null
ok 356 error should be null
[39m
[36mok 353 error should be null
ok 354 error should be null
ok 355 error should be null
ok 356 error should be null
[39m
[33mok 357 peer should have a non-empty identifier
ok 358 peer should have a non-empty host address
ok 359 peer should have port number
ok 360 peer should have suggested timeout
ok 361 peer should have a connection type
ok 362 connection type should match one of the pre-defined types
[39m
[32mok 351 error should be null
ok 352 error should be null
[39m
[32m2016-10-04 22:57:13 - DEBUG thaliWifiInfrastructure: 'listening 51128'
[39m
[32mok 353 error should be null
[39m
[32mok 354 error should be null
[39m
[32mok 355 error should be null
[39m
[32mok 356 error should be null
[39m
[36mok 357 peer should have a non-empty identifier
[39m
[36mok 358 peer should have a non-empty host address
ok 359 peer should have port number
ok 360 peer should have suggested timeout
[39m
[36mok 361 peer should have a connection type
[39m
[36mok 362 connection type should match one of the pre-defined types
[39m
[32mok 357 peer should have a non-empty identifier
ok 358 peer should have a non-empty host address
[39m
[32mok 359 peer should have port number
ok 360 peer should have suggested timeout
ok 361 peer should have a connection type
ok 362 connection type should match one of the pre-defined types
[39m
[33mok 363 must not receive too many peer availabilities
[39m
[33m# teardown
[39m
[36mok 363 must not receive too many peer availabilities
[39m
[36m# teardown
[39m
[32mok 363 must not receive too many peer availabilities
[39m
[32m# teardown
[39m
2016-10-04 22:57:17 - DEBUG UnitTestFramework: '#run ok: 'peer should be found once after listening and discovery started''
2016-10-04 22:57:17 - DEBUG UnitTestFramework: '#teardown: 'peer should be found once after listening and discovery started''

[36m2016-10-04 22:57:17 - INFO thaliMobile: 'Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}'
2016-10-04 22:57:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-10-04 22:57:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 364 error should be null
ok 365 error should be null
# setup
[39m
[32m2016-10-04 22:57:17 - INFO thaliMobile: 'Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}'
2016-10-04 22:57:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-10-04 22:57:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 364 error should be null
ok 365 error should be null
# setup
[39m
[33m2016-10-04 22:57:17 - INFO thaliMobile: 'Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}'
2016-10-04 22:57:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-10-04 22:57:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 364 error should be null
ok 365 error should be null
# setup
[39m
2016-10-04 22:57:17 - DEBUG UnitTestFramework: '#teardown ok: 'peer should be found once after listening and discovery started''
2016-10-04 22:57:17 - DEBUG UnitTestFramework: '#setup: 'Discovered peer should be removed if no availability updates were received during availability timeout''

[36m# Discovered peer should be removed if no availability updates were received during availability timeout
[39m
[32m# Discovered peer should be removed if no availability updates were received during availability timeout
[39m
[33m# Discovered peer should be removed if no availability updates were received during availability timeout
[39m
2016-10-04 22:57:17 - DEBUG UnitTestFramework: '#setup ok: 'Discovered peer should be removed if no availability updates were received during availability timeout''

2016-10-04 22:57:17 - DEBUG UnitTestFramework: '#run: 'Discovered peer should be removed if no availability updates were received during availability timeout''

[36m# teardown
[39m
[32m# teardown
[39m
[33m# teardown
[39m
2016-10-04 22:57:17 - DEBUG UnitTestFramework: '#run ok: 'Discovered peer should be removed if no availability updates were received during availability timeout''
2016-10-04 22:57:17 - DEBUG UnitTestFramework: '#teardown: 'Discovered peer should be removed if no availability updates were received during availability timeout''

[36mok 366 error should be null
ok 367 error should be null
# setup
[39m
[33mok 366 error should be null
ok 367 error should be null
# setup
[39m
[32mok 366 error should be null
ok 367 error should be null
# setup
[39m
2016-10-04 22:57:17 - DEBUG UnitTestFramework: '#teardown ok: 'Discovered peer should be removed if no availability updates were received during availability timeout''

2016-10-04 22:57:17 - DEBUG UnitTestFramework: '#setup: 'Client to server request coordinated''

[36m# Client to server request coordinated
[39m
[32m# Client to server request coordinated
[39m
[33m# Client to server request coordinated
[39m
2016-10-04 22:57:17 - DEBUG UnitTestFramework: '#setup ok: 'Client to server request coordinated''

2016-10-04 22:57:17 - DEBUG UnitTestFramework: '#run: 'Client to server request coordinated''

[36mok 368 error should be null
ok 369 error should be null
2016-10-04 22:57:17 - DEBUG thaliWifiInfrastructure: 'listening 51129'
2016-10-04 22:57:17 - INFO testThaliNotification: 'startListeningForAdvertisements'
[39m
[33mok 368 error should be null
ok 369 error should be null
[39m
[32mok 368 error should be null
[39m
[32mok 369 error should be null
[39m
[33m2016-10-04 22:57:17 - DEBUG thaliWifiInfrastructure: 'listening 51130'
[39m
[33m2016-10-04 22:57:17 - INFO testThaliNotification: 'startListeningForAdvertisements'
[39m
[32m2016-10-04 22:57:17 - DEBUG thaliWifiInfrastructure: 'listening 51132'
[39m
[32m2016-10-04 22:57:17 - INFO testThaliNotification: 'startListeningForAdvertisements'
[39m
[36m2016-10-04 22:57:17 - INFO testThaliNotification: 'PeerAdvertisesDataForUs:tcp, 192.168.1.20, 192.168.1.20, 51130'
[39m
[33m2016-10-04 22:57:17 - INFO testThaliNotification: 'PeerAdvertisesDataForUs:tcp, 192.168.1.20, 192.168.1.20, 51132'
[39m
[36m2016-10-04 22:57:17 - INFO testThaliNotification: 'PeerAdvertisesDataForUs:tcp, 192.168.1.20, 192.168.1.20, 51132'
[39m
[33m2016-10-04 22:57:18 - INFO testThaliNotification: 'PeerAdvertisesDataForUs:tcp, 192.168.1.20, 192.168.1.20, 51129'
[39m
[32m2016-10-04 22:57:18 - INFO testThaliNotification: 'PeerAdvertisesDataForUs:tcp, 192.168.1.20, 192.168.1.20, 51129'
[39m
[32m2016-10-04 22:57:18 - INFO testThaliNotification: 'PeerAdvertisesDataForUs:tcp, 192.168.1.20, 192.168.1.20, 51130'
[39m
[33mok 370 Peer made successful https requests to all peers
ok 371 Peer received right amount of https requests
ok 372 HTTPS server received zero PSK Identities. Count:0
# teardown
[39m
[36mok 370 Peer made successful https requests to all peers
ok 371 Peer received right amount of https requests
ok 372 HTTPS server received zero PSK Identities. Count:0
# teardown
[39m
[32mok 370 Peer made successful https requests to all peers
ok 371 Peer received right amount of https requests
ok 372 HTTPS server received zero PSK Identities. Count:0
[39m
[32m# teardown
[39m
2016-10-04 22:57:22 - DEBUG UnitTestFramework: '#run ok: 'Client to server request coordinated''

2016-10-04 22:57:22 - DEBUG UnitTestFramework: '#teardown: 'Client to server request coordinated''

[36m2016-10-04 22:57:22 - INFO testThaliNotification: 'Participants:3 Peers Replied to us:2 Peers requested to:2'
# setup
[39m
[32m2016-10-04 22:57:22 - INFO testThaliNotification: 'Participants:3 Peers Replied to us:2 Peers requested to:2'
# setup
[39m
[33m2016-10-04 22:57:22 - INFO testThaliNotification: 'Participants:3 Peers Replied to us:2 Peers requested to:2'
[39m
[33m# setup
[39m
2016-10-04 22:57:22 - DEBUG UnitTestFramework: '#teardown ok: 'Client to server request coordinated''

2016-10-04 22:57:22 - DEBUG UnitTestFramework: '#setup: 'Test BEACONS_RETRIEVED_AND_PARSED locally''

[36mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[36m# Test BEACONS_RETRIEVED_AND_PARSED locally
[39m
[33mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[33m# Test BEACONS_RETRIEVED_AND_PARSED locally
[39m
[32mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[32m# Test BEACONS_RETRIEVED_AND_PARSED locally
[39m
2016-10-04 22:57:22 - DEBUG UnitTestFramework: '#setup ok: 'Test BEACONS_RETRIEVED_AND_PARSED locally''

2016-10-04 22:57:22 - DEBUG UnitTestFramework: '#run: 'Test BEACONS_RETRIEVED_AND_PARSED locally''

[36mok 373 peerIdentifier should be identifier
ok 374 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 375 good beacon
ok 376 good preAmble
ok 377 public keys match!
ok 378 must return null after successful call
ok 379 Once start returns the action should be in KILLED state
# teardown
[39m
[32mok 373 peerIdentifier should be identifier
ok 374 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 375 good beacon
ok 376 good preAmble
ok 377 public keys match!
ok 378 must return null after successful call
ok 379 Once start returns the action should be in KILLED state
# teardown
[39m
[33mok 373 peerIdentifier should be identifier
ok 374 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 375 good beacon
[39m
[33mok 376 good preAmble
ok 377 public keys match!
[39m
[33mok 378 must return null after successful call
ok 379 Once start returns the action should be in KILLED state
[39m
2016-10-04 22:57:22 - DEBUG UnitTestFramework: '#run ok: 'Test BEACONS_RETRIEVED_AND_PARSED locally''
2016-10-04 22:57:22 - DEBUG UnitTestFramework: '#teardown: 'Test BEACONS_RETRIEVED_AND_PARSED locally''

[33m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-10-04 22:57:22 - DEBUG UnitTestFramework: '#teardown ok: 'Test BEACONS_RETRIEVED_AND_PARSED locally''

2016-10-04 22:57:22 - DEBUG UnitTestFramework: '#setup: 'Test HTTP_BAD_RESPONSE locally''

[32mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[32m# Test HTTP_BAD_RESPONSE locally
[39m
[36mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[36m# Test HTTP_BAD_RESPONSE locally
[39m
[33mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[33m# Test HTTP_BAD_RESPONSE locally
[39m
2016-10-04 22:57:22 - DEBUG UnitTestFramework: '#setup ok: 'Test HTTP_BAD_RESPONSE locally''

2016-10-04 22:57:22 - DEBUG UnitTestFramework: '#run: 'Test HTTP_BAD_RESPONSE locally''

[36mok 380 Response should be HTTP_BAD_RESPONSE
ok 381 must return null after successful call
# teardown
[39m
[33mok 380 Response should be HTTP_BAD_RESPONSE
ok 381 must return null after successful call
# teardown
[39m
[32mok 380 Response should be HTTP_BAD_RESPONSE
ok 381 must return null after successful call
[39m
[32m# teardown
[39m
2016-10-04 22:57:22 - DEBUG UnitTestFramework: '#run ok: 'Test HTTP_BAD_RESPONSE locally''

2016-10-04 22:57:22 - DEBUG UnitTestFramework: '#teardown: 'Test HTTP_BAD_RESPONSE locally''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:22 - DEBUG UnitTestFramework: '#teardown ok: 'Test HTTP_BAD_RESPONSE locally''

2016-10-04 22:57:22 - DEBUG UnitTestFramework: '#setup: 'Test NETWORK_PROBLEM locally''

[36mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[36m# Test NETWORK_PROBLEM locally
[39m
[32mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[32m# Test NETWORK_PROBLEM locally
[39m
[33mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[33m# Test NETWORK_PROBLEM locally
[39m
2016-10-04 22:57:22 - DEBUG UnitTestFramework: '#setup ok: 'Test NETWORK_PROBLEM locally''

2016-10-04 22:57:22 - DEBUG UnitTestFramework: '#run: 'Test NETWORK_PROBLEM locally''

[36mok 382 Response should be NETWORK_PROBLEM
ok 383 reject reason should be: Could not establish TCP connection
[39m
[32mok 382 Response should be NETWORK_PROBLEM
ok 383 reject reason should be: Could not establish TCP connection
[39m
[32m# teardown
[39m
[36m# teardown
[39m
[33mok 382 Response should be NETWORK_PROBLEM
[39m
[33mok 383 reject reason should be: Could not establish TCP connection
[39m
[33m# teardown
[39m
2016-10-04 22:57:22 - DEBUG UnitTestFramework: '#run ok: 'Test NETWORK_PROBLEM locally''
2016-10-04 22:57:22 - DEBUG UnitTestFramework: '#teardown: 'Test NETWORK_PROBLEM locally''

[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:22 - DEBUG UnitTestFramework: '#teardown ok: 'Test NETWORK_PROBLEM locally''

2016-10-04 22:57:22 - DEBUG UnitTestFramework: '#setup: 'Call the start two times''

[32mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[32m# Call the start two times
[39m
[36mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[36m# Call the start two times
[39m
[33mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[33m# Call the start two times
[39m
2016-10-04 22:57:22 - DEBUG UnitTestFramework: '#setup ok: 'Call the start two times''

2016-10-04 22:57:22 - DEBUG UnitTestFramework: '#run: 'Call the start two times''

[32mok 384 Call start once
[39m
[36mok 384 Call start once
[39m
[32mok 385 Response should be BEACONS_RETRIEVED_AND_PARSED
[39m
[32mok 386 must return null after successful call.
[39m
[32m# teardown
[39m
[33mok 384 Call start once
[39m
[36mok 385 Response should be BEACONS_RETRIEVED_AND_PARSED
[39m
[36mok 386 must return null after successful call.
[39m
[36m# teardown
[39m
[33mok 385 Response should be BEACONS_RETRIEVED_AND_PARSED
[39m
[33mok 386 must return null after successful call.
[39m
2016-10-04 22:57:22 - DEBUG UnitTestFramework: '#run ok: 'Call the start two times''

2016-10-04 22:57:22 - DEBUG UnitTestFramework: '#teardown: 'Call the start two times''

[33m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:22 - DEBUG UnitTestFramework: '#teardown ok: 'Call the start two times''

2016-10-04 22:57:22 - DEBUG UnitTestFramework: '#setup: 'Call the kill before calling the start''

[32mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[32m# Call the kill before calling the start
[39m
[36mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[36m# Call the kill before calling the start
[39m
[33mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[33m# Call the kill before calling the start
[39m
2016-10-04 22:57:22 - DEBUG UnitTestFramework: '#setup ok: 'Call the kill before calling the start''

2016-10-04 22:57:22 - DEBUG UnitTestFramework: '#run: 'Call the kill before calling the start''

[36mok 387 Should be Killed
[39m
[32mok 387 Should be Killed
[39m
[32mok 388 Start after killed
[39m
[36mok 388 Start after killed
[39m
[32m# teardown
[39m
[36m# teardown
[39m
[33mok 387 Should be Killed
[39m
[33mok 388 Start after killed
[39m
[33m# teardown
[39m
2016-10-04 22:57:22 - DEBUG UnitTestFramework: '#run ok: 'Call the kill before calling the start''

2016-10-04 22:57:22 - DEBUG UnitTestFramework: '#teardown: 'Call the kill before calling the start''

[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:23 - DEBUG UnitTestFramework: '#teardown ok: 'Call the kill before calling the start''

2016-10-04 22:57:23 - DEBUG UnitTestFramework: '#setup: 'Call the kill immediately after the start''

[32mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[32m# Call the kill immediately after the start
[39m
[36mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[36m# Call the kill immediately after the start
[39m
[33mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[33m# Call the kill immediately after the start
[39m
2016-10-04 22:57:23 - DEBUG UnitTestFramework: '#setup ok: 'Call the kill immediately after the start''

2016-10-04 22:57:23 - DEBUG UnitTestFramework: '#run: 'Call the kill immediately after the start''

[36mok 389 Should be KILLED
[39m
[36mok 390 must return null after successful kill
[39m
[36m# teardown
[39m
[32mok 389 Should be KILLED
[39m
[32mok 390 must return null after successful kill
[39m
[32m# teardown
[39m
[33mok 389 Should be KILLED
[39m
[33mok 390 must return null after successful kill
[39m
[33m# teardown
[39m
2016-10-04 22:57:23 - DEBUG UnitTestFramework: '#run ok: 'Call the kill immediately after the start''
2016-10-04 22:57:23 - DEBUG UnitTestFramework: '#teardown: 'Call the kill immediately after the start''

[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-10-04 22:57:23 - DEBUG UnitTestFramework: '#teardown ok: 'Call the kill immediately after the start''

2016-10-04 22:57:23 - DEBUG UnitTestFramework: '#setup: 'Call the kill while waiting a response from the server''

[36mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[36m# Call the kill while waiting a response from the server
[39m
[32mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[32m# Call the kill while waiting a response from the server
[39m
[33mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[33m# Call the kill while waiting a response from the server
[39m
2016-10-04 22:57:23 - DEBUG UnitTestFramework: '#setup ok: 'Call the kill while waiting a response from the server''

2016-10-04 22:57:23 - DEBUG UnitTestFramework: '#run: 'Call the kill while waiting a response from the server''

[36mok 391 Should be KILLED
ok 392 must return null after successful kill
# teardown
[39m
[33mok 391 Should be KILLED
ok 392 must return null after successful kill
# teardown
[39m
[32mok 391 Should be KILLED
ok 392 must return null after successful kill
[39m
[32m# teardown
[39m
2016-10-04 22:57:25 - DEBUG UnitTestFramework: '#run ok: 'Call the kill while waiting a response from the server''
2016-10-04 22:57:25 - DEBUG UnitTestFramework: '#teardown: 'Call the kill while waiting a response from the server''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:25 - DEBUG UnitTestFramework: '#teardown ok: 'Call the kill while waiting a response from the server''
2016-10-04 22:57:25 - DEBUG UnitTestFramework: '#setup: 'Test to exceed the max content size locally''

[36mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[36m# Test to exceed the max content size locally
[39m
[33mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[33m# Test to exceed the max content size locally
[39m
[32mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[32m# Test to exceed the max content size locally
[39m
2016-10-04 22:57:25 - DEBUG UnitTestFramework: '#setup ok: 'Test to exceed the max content size locally''

2016-10-04 22:57:25 - DEBUG UnitTestFramework: '#run: 'Test to exceed the max content size locally''

[32mok 393 HTTP_BAD_RESPONSE should be response when content size is exceeded
ok 394 must return null after successful call
# teardown
[39m
[36mok 393 HTTP_BAD_RESPONSE should be response when content size is exceeded
ok 394 must return null after successful call
[39m
[33mok 393 HTTP_BAD_RESPONSE should be response when content size is exceeded
[39m
[33mok 394 must return null after successful call
[39m
2016-10-04 22:57:25 - DEBUG UnitTestFramework: '#run ok: 'Test to exceed the max content size locally''

2016-10-04 22:57:25 - DEBUG UnitTestFramework: '#teardown: 'Test to exceed the max content size locally''

[33m# teardown
[39m
[36m# teardown
[39m
[33m# setup
[39m
[32m# setup
[39m
[36m# setup
[39m
2016-10-04 22:57:26 - DEBUG UnitTestFramework: '#teardown ok: 'Test to exceed the max content size locally''

2016-10-04 22:57:26 - DEBUG UnitTestFramework: '#setup: 'Close the server socket while the client is waiting a response from the server. Local test.''

[36mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[36m# Close the server socket while the client is waiting a response from the server. Local test.
[39m
[32mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[32m# Close the server socket while the client is waiting a response from the server. Local test.
[39m
[33mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[33m# Close the server socket while the client is waiting a response from the server. Local test.
[39m
2016-10-04 22:57:26 - DEBUG UnitTestFramework: '#setup ok: 'Close the server socket while the client is waiting a response from the server. Local test.''

2016-10-04 22:57:26 - DEBUG UnitTestFramework: '#run: 'Close the server socket while the client is waiting a response from the server. Local test.''

[32mok 395 Should be NETWORK_PROBLEM caused closing server socket
[39m
[32mok 396 Should be Could not establish TCP connection
[39m
[32m# teardown
[39m
[36mok 395 Should be NETWORK_PROBLEM caused closing server socket
ok 396 Should be Could not establish TCP connection
# teardown
[39m
[33mok 395 Should be NETWORK_PROBLEM caused closing server socket
ok 396 Should be Could not establish TCP connection
# teardown
[39m
2016-10-04 22:57:28 - DEBUG UnitTestFramework: '#run ok: 'Close the server socket while the client is waiting a response from the server. Local test.''

2016-10-04 22:57:28 - DEBUG UnitTestFramework: '#teardown: 'Close the server socket while the client is waiting a response from the server. Local test.''

[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-10-04 22:57:28 - DEBUG UnitTestFramework: '#teardown ok: 'Close the server socket while the client is waiting a response from the server. Local test.''

2016-10-04 22:57:28 - DEBUG UnitTestFramework: '#setup: 'Close the client socket while the client is waiting a response from the server. Local test.''

[36mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[36m# Close the client socket while the client is waiting a response from the server. Local test.
[39m
[32mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[32m# Close the client socket while the client is waiting a response from the server. Local test.
[39m
[33mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[33m# Close the client socket while the client is waiting a response from the server. Local test.
[39m
2016-10-04 22:57:28 - DEBUG UnitTestFramework: '#setup ok: 'Close the client socket while the client is waiting a response from the server. Local test.''

2016-10-04 22:57:28 - DEBUG UnitTestFramework: '#run: 'Close the client socket while the client is waiting a response from the server. Local test.''

[32mok 397 Should be NETWORK_PROBLEM caused closing client socket
ok 398 Should be Could not establish TCP connection
# teardown
[39m
[36mok 397 Should be NETWORK_PROBLEM caused closing client socket
ok 398 Should be Could not establish TCP connection
# teardown
[39m
[33mok 397 Should be NETWORK_PROBLEM caused closing client socket
[39m
[33mok 398 Should be Could not establish TCP connection
# teardown
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run ok: 'Close the client socket while the client is waiting a response from the server. Local test.''
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown: 'Close the client socket while the client is waiting a response from the server. Local test.''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown ok: 'Close the client socket while the client is waiting a response from the server. Local test.''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup: '#generatePreambleAndBeacons bad args''

[36m# #generatePreambleAndBeacons bad args
[39m
[32m# #generatePreambleAndBeacons bad args
[39m
[33m# #generatePreambleAndBeacons bad args
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup ok: '#generatePreambleAndBeacons bad args''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run: '#generatePreambleAndBeacons bad args''

[32mok 399 publicKeysToNotify cannot be null
ok 400 ecdh for local device cannot be null
ok 401 milliseconds cannot be less than 0
ok 402 milliseconds cannot be 0
ok 403 milliseconds cannot be greater than one_day
# teardown
[39m
[36mok 399 publicKeysToNotify cannot be null
ok 400 ecdh for local device cannot be null
ok 401 milliseconds cannot be less than 0
ok 402 milliseconds cannot be 0
ok 403 milliseconds cannot be greater than one_day
# teardown
[39m
[33mok 399 publicKeysToNotify cannot be null
[39m
[33mok 400 ecdh for local device cannot be null
[39m
[33mok 401 milliseconds cannot be less than 0
[39m
[33mok 402 milliseconds cannot be 0
[39m
[33mok 403 milliseconds cannot be greater than one_day
[39m
[33m# teardown
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run ok: '#generatePreambleAndBeacons bad args''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown: '#generatePreambleAndBeacons bad args''

[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown ok: '#generatePreambleAndBeacons bad args''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup: '#generatePreambleAndBeacons empty keys to notify''

[36m# #generatePreambleAndBeacons empty keys to notify
[39m
[32m# #generatePreambleAndBeacons empty keys to notify
[39m
[33m# #generatePreambleAndBeacons empty keys to notify
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup ok: '#generatePreambleAndBeacons empty keys to notify''
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run: '#generatePreambleAndBeacons empty keys to notify''

[36mok 404 should be equal
# teardown
[39m
[32mok 404 should be equal
# teardown
[39m
[33mok 404 should be equal
# teardown
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run ok: '#generatePreambleAndBeacons empty keys to notify''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown: '#generatePreambleAndBeacons empty keys to notify''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown ok: '#generatePreambleAndBeacons empty keys to notify''
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup: '#generatePreambleAndBeacons multiple keys to notify''

[36m# #generatePreambleAndBeacons multiple keys to notify
[39m
[33m# #generatePreambleAndBeacons multiple keys to notify
[39m
[32m# #generatePreambleAndBeacons multiple keys to notify
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup ok: '#generatePreambleAndBeacons multiple keys to notify''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run: '#generatePreambleAndBeacons multiple keys to notify''

[36mok 405 should be equal
ok 406 should be equal
ok 407 (unnamed assert)
ok 408 should be equal
# teardown
[39m
[32mok 405 should be equal
ok 406 should be equal
ok 407 (unnamed assert)
ok 408 should be equal
# teardown
[39m
[33mok 405 should be equal
[39m
[33mok 406 should be equal
[39m
[33mok 407 (unnamed assert)
ok 408 should be equal
[39m
[33m# teardown
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run ok: '#generatePreambleAndBeacons multiple keys to notify''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown: '#generatePreambleAndBeacons multiple keys to notify''

[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown ok: '#generatePreambleAndBeacons multiple keys to notify''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup: '#parseBeacons invalid ECDH public key in beaconStreamWithPreAmble''

[36m# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
[39m
[32m# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
[39m
[33m# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup ok: '#parseBeacons invalid ECDH public key in beaconStreamWithPreAmble''
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run: '#parseBeacons invalid ECDH public key in beaconStreamWithPreAmble''

[36mok 409 should throw
# teardown
[39m
[32mok 409 should throw
# teardown
[39m
[33mok 409 should throw
# teardown
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run ok: '#parseBeacons invalid ECDH public key in beaconStreamWithPreAmble''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown: '#parseBeacons invalid ECDH public key in beaconStreamWithPreAmble''

[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown ok: '#parseBeacons invalid ECDH public key in beaconStreamWithPreAmble''
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup: '#parseBeacons invalid expiration in beaconStreamWithPreAmble''

[36m# #parseBeacons invalid expiration in beaconStreamWithPreAmble
[39m
[32m# #parseBeacons invalid expiration in beaconStreamWithPreAmble
[39m
[33m# #parseBeacons invalid expiration in beaconStreamWithPreAmble
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup ok: '#parseBeacons invalid expiration in beaconStreamWithPreAmble''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run: '#parseBeacons invalid expiration in beaconStreamWithPreAmble''

[36mok 410 Preamble expiration must be a 64 bit integer
# teardown
[39m
[33mok 410 Preamble expiration must be a 64 bit integer
# teardown
[39m
[32mok 410 Preamble expiration must be a 64 bit integer
[39m
[32m# teardown
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run ok: '#parseBeacons invalid expiration in beaconStreamWithPreAmble''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown: '#parseBeacons invalid expiration in beaconStreamWithPreAmble''

[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown ok: '#parseBeacons invalid expiration in beaconStreamWithPreAmble''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup: '#parseBeacons expiration out of range lower''

[36m# #parseBeacons expiration out of range lower
[39m
[32m# #parseBeacons expiration out of range lower
[39m
[33m# #parseBeacons expiration out of range lower
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup ok: '#parseBeacons expiration out of range lower''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run: '#parseBeacons expiration out of range lower''

[36mok 411 Expiration out of range
# teardown
[39m
[32mok 411 Expiration out of range
# teardown
[39m
[33mok 411 Expiration out of range
[39m
[33m# teardown
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run ok: '#parseBeacons expiration out of range lower''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown: '#parseBeacons expiration out of range lower''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown ok: '#parseBeacons expiration out of range lower''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup: '#parseBeacons expiration out of range lower''

[36m# #parseBeacons expiration out of range lower
[39m
[32m# #parseBeacons expiration out of range lower
[39m
[33m# #parseBeacons expiration out of range lower
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup ok: '#parseBeacons expiration out of range lower''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run: '#parseBeacons expiration out of range lower''

[32mok 412 Expiration out of range
[39m
[32m# teardown
[39m
[36mok 412 Expiration out of range
# teardown
[39m
[33mok 412 Expiration out of range
# teardown
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run ok: '#parseBeacons expiration out of range lower''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown: '#parseBeacons expiration out of range lower''

[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown ok: '#parseBeacons expiration out of range lower''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup: '#parseBeacons no beacons returns null''

[36m# #parseBeacons no beacons returns null
[39m
[32m# #parseBeacons no beacons returns null
[39m
[33m# #parseBeacons no beacons returns null
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup ok: '#parseBeacons no beacons returns null''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run: '#parseBeacons no beacons returns null''

[32mok 413 should be equal
# teardown
[39m
[36mok 413 should be equal
[39m
[36m# teardown
[39m
[33mok 413 should be equal
[39m
[33m# teardown
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run ok: '#parseBeacons no beacons returns null''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown: '#parseBeacons no beacons returns null''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown ok: '#parseBeacons no beacons returns null''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup: '#parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble''

[36m# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
[39m
[32m# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
[39m
[33m# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup ok: '#parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run: '#parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble''

[32mok 414 Malformed encrypted beacon key ID
# teardown
[39m
[36mok 414 Malformed encrypted beacon key ID
# teardown
[39m
[33mok 414 Malformed encrypted beacon key ID
[39m
[33m# teardown
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run ok: '#parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown: '#parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown ok: '#parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup: '#parseBeacons addressBookCallback fails decrypt''

[36m# #parseBeacons addressBookCallback fails decrypt
[39m
[32m# #parseBeacons addressBookCallback fails decrypt
[39m
[33m# #parseBeacons addressBookCallback fails decrypt
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup ok: '#parseBeacons addressBookCallback fails decrypt''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run: '#parseBeacons addressBookCallback fails decrypt''

[36mok 415 should be equal
# teardown
[39m
[32mok 415 should be equal
[39m
[32m# teardown
[39m
[33mok 415 should be equal
[39m
[33m# teardown
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run ok: '#parseBeacons addressBookCallback fails decrypt''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown: '#parseBeacons addressBookCallback fails decrypt''

[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown ok: '#parseBeacons addressBookCallback fails decrypt''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup: '#parseBeacons addressBookCallback returns no matches''

[36m# #parseBeacons addressBookCallback returns no matches
[39m
[33m# #parseBeacons addressBookCallback returns no matches
[39m
[32m# #parseBeacons addressBookCallback returns no matches
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup ok: '#parseBeacons addressBookCallback returns no matches''
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run: '#parseBeacons addressBookCallback returns no matches''

[36mok 416 should be equal
ok 417 should be equal
# teardown
[39m
[33mok 416 should be equal
ok 417 should be equal
[39m
[33m# teardown
[39m
[32mok 416 should be equal
[39m
[32mok 417 should be equal
[39m
[32m# teardown
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run ok: '#parseBeacons addressBookCallback returns no matches''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown: '#parseBeacons addressBookCallback returns no matches''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown ok: '#parseBeacons addressBookCallback returns no matches''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup: '#parseBeacons addressBookCallback returns spurious match''

[36m# #parseBeacons addressBookCallback returns spurious match
[39m
[32m# #parseBeacons addressBookCallback returns spurious match
[39m
[33m# #parseBeacons addressBookCallback returns spurious match
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup ok: '#parseBeacons addressBookCallback returns spurious match''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run: '#parseBeacons addressBookCallback returns spurious match''

[36mok 418 should be equal
ok 419 should be equal
# teardown
[39m
[33mok 418 should be equal
ok 419 should be equal
[39m
[33m# teardown
[39m
[32mok 418 should be equal
[39m
[32mok 419 should be equal
[39m
[32m# teardown
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run ok: '#parseBeacons addressBookCallback returns spurious match''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown: '#parseBeacons addressBookCallback returns spurious match''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown ok: '#parseBeacons addressBookCallback returns spurious match''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup: '#parseBeacons addressBookCallback returns public key''

[36m# #parseBeacons addressBookCallback returns public key
[39m
[32m# #parseBeacons addressBookCallback returns public key
[39m
[33m# #parseBeacons addressBookCallback returns public key
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup ok: '#parseBeacons addressBookCallback returns public key''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run: '#parseBeacons addressBookCallback returns public key''

[36mok 420 right number of calls to address book
ok 421 good preAmble
ok 422 good unencryptedKeyId
ok 423 good beacon
# teardown
[39m
[32mok 420 right number of calls to address book
[39m
[32mok 421 good preAmble
ok 422 good unencryptedKeyId
[39m
[32mok 423 good beacon
[39m
[32m# teardown
[39m
[33mok 420 right number of calls to address book
[39m
[33mok 421 good preAmble
ok 422 good unencryptedKeyId
[39m
[33mok 423 good beacon
[39m
[33m# teardown
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run ok: '#parseBeacons addressBookCallback returns public key''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown: '#parseBeacons addressBookCallback returns public key''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown ok: '#parseBeacons addressBookCallback returns public key''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup: 'validate generatePskIdentityField''

[36m# validate generatePskIdentityField
[39m
[32m# validate generatePskIdentityField
[39m
[33m# validate generatePskIdentityField
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup ok: 'validate generatePskIdentityField''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run: 'validate generatePskIdentityField''

[36mok 424 decoded buffers match
[39m
[36m# teardown
[39m
[32mok 424 decoded buffers match
[39m
[32m# teardown
[39m
[33mok 424 decoded buffers match
[39m
[33m# teardown
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run ok: 'validate generatePskIdentityField''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown: 'validate generatePskIdentityField''

[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown ok: 'validate generatePskIdentityField''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup: 'validate generatePskSecret''

[36m# validate generatePskSecret
[39m
[32m# validate generatePskSecret
[39m
[33m# validate generatePskSecret
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup ok: 'validate generatePskSecret''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run: 'validate generatePskSecret''

[32mok 425 secrets match
[39m
[32m# teardown
[39m
[36mok 425 secrets match
# teardown
[39m
[33mok 425 secrets match
[39m
[33m# teardown
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run ok: 'validate generatePskSecret''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown: 'validate generatePskSecret''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown ok: 'validate generatePskSecret''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup: 'validate generatePskSecrets''

[32m# validate generatePskSecrets
[39m
[36m# validate generatePskSecrets
[39m
[33m# validate generatePskSecrets
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup ok: 'validate generatePskSecrets''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run: 'validate generatePskSecrets''

[36mok 426 Matching numbers
[39m
[36mok 427 We have an entry!
[39m
[32mok 426 Matching numbers
ok 427 We have an entry!
ok 428 keys match
ok 429 secrets match
ok 430 We have an entry!
ok 431 keys match
ok 432 secrets match
ok 433 We have an entry!
ok 434 keys match
ok 435 secrets match
# teardown
[39m
[36mok 428 keys match
ok 429 secrets match
ok 430 We have an entry!
ok 431 keys match
ok 432 secrets match
ok 433 We have an entry!
ok 434 keys match
ok 435 secrets match
# teardown
[39m
[33mok 426 Matching numbers
[39m
[33mok 427 We have an entry!
ok 428 keys match
[39m
[33mok 429 secrets match
[39m
[33mok 430 We have an entry!
[39m
[33mok 431 keys match
ok 432 secrets match
[39m
[33mok 433 We have an entry!
[39m
[33mok 434 keys match
ok 435 secrets match
[39m
[33m# teardown
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run ok: 'validate generatePskSecrets''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown: 'validate generatePskSecrets''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown ok: 'validate generatePskSecrets''
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup: 'validate generateBeaconStreamAndSecrets''

[36m# validate generateBeaconStreamAndSecrets
[39m
[32m# validate generateBeaconStreamAndSecrets
[39m
[33m# validate generateBeaconStreamAndSecrets
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup ok: 'validate generateBeaconStreamAndSecrets''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run: 'validate generateBeaconStreamAndSecrets''

[36mok 436 Streams have same length
ok 437 matching size
ok 438 keys match
ok 439 secrets match
# teardown
[39m
[32mok 436 Streams have same length
ok 437 matching size
ok 438 keys match
ok 439 secrets match
# teardown
[39m
[33mok 436 Streams have same length
[39m
[33mok 437 matching size
[39m
[33mok 438 keys match
[39m
[33mok 439 secrets match
[39m
[33m# teardown
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run ok: 'validate generateBeaconStreamAndSecrets''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown: 'validate generateBeaconStreamAndSecrets''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown ok: 'validate generateBeaconStreamAndSecrets''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup: 'Add two Peers.''

[36mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[36m# Add two Peers.
[39m
[33mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[33m# Add two Peers.
[39m
[32mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[32m# Add two Peers.
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup ok: 'Add two Peers.''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run: 'Add two Peers.''

[36mok 440 should be equal
[39m
[36mok 441 should be equal
[39m
[36mok 442 should be equal
ok 443 should be equal
ok 444 should be equal
# teardown
[39m
[32mok 440 should be equal
[39m
[32mok 441 should be equal
ok 442 should be equal
ok 443 should be equal
[39m
[32mok 444 should be equal
[39m
[32m# teardown
[39m
[33mok 440 should be equal
[39m
[33mok 441 should be equal
ok 442 should be equal
[39m
[33mok 443 should be equal
[39m
[33mok 444 should be equal
[39m
[33m# teardown
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run ok: 'Add two Peers.''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown: 'Add two Peers.''

[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown ok: 'Add two Peers.''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup: 'TCP_NATIVE peer loses DNS''

[36mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[36m# TCP_NATIVE peer loses DNS
[39m
[33mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[33m# TCP_NATIVE peer loses DNS
[39m
[32mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[32m# TCP_NATIVE peer loses DNS
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup ok: 'TCP_NATIVE peer loses DNS''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run: 'TCP_NATIVE peer loses DNS''

[36mok 445 should be equal
ok 446 should be equal
[39m
[36m# teardown
[39m
[32mok 445 should be equal
[39m
[32mok 446 should be equal
[39m
[32m# teardown
[39m
[33mok 445 should be equal
[39m
[33mok 446 should be equal
[39m
[33m# teardown
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run ok: 'TCP_NATIVE peer loses DNS''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown: 'TCP_NATIVE peer loses DNS''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown ok: 'TCP_NATIVE peer loses DNS''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup: 'Received beacons with no values for us''

[33mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[36mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[33m# Received beacons with no values for us
[39m
[36m# Received beacons with no values for us
[39m
[32mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[32m# Received beacons with no values for us
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup ok: 'Received beacons with no values for us''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run: 'Received beacons with no values for us''

[36mok 447 entry exists
ok 448 entry is resolved
[39m
[36m# teardown
[39m
[32mok 447 entry exists
ok 448 entry is resolved
[39m
[32m# teardown
[39m
[33mok 447 entry exists
[39m
[33mok 448 entry is resolved
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run ok: 'Received beacons with no values for us''
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown: 'Received beacons with no values for us''

[33m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown ok: 'Received beacons with no values for us''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup: 'Resolves an action locally''

[36mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[36m# Resolves an action locally
[39m
[32mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[32m# Resolves an action locally
[39m
[33mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[33m# Resolves an action locally
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup ok: 'Resolves an action locally''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run: 'Resolves an action locally''

[33mok 449 Host address must match
ok 450 suggestedTCPTimeout must match
ok 451 connectionType must match
ok 452 portNumber must match
[39m
[36mok 449 Host address must match
[39m
[36mok 450 suggestedTCPTimeout must match
[39m
[36mok 451 connectionType must match
[39m
[36mok 452 portNumber must match
[39m
[33m# teardown
[39m
[36m# teardown
[39m
[32mok 449 Host address must match
[39m
[32mok 450 suggestedTCPTimeout must match
ok 451 connectionType must match
ok 452 portNumber must match
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run ok: 'Resolves an action locally''

[32m# teardown
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown: 'Resolves an action locally''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown ok: 'Resolves an action locally''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup: 'Resolves an action locally using ThaliPeerPoolDefault''

[36mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[36m# Resolves an action locally using ThaliPeerPoolDefault
[39m
[32mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[32m# Resolves an action locally using ThaliPeerPoolDefault
[39m
[33mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[33m# Resolves an action locally using ThaliPeerPoolDefault
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup ok: 'Resolves an action locally using ThaliPeerPoolDefault''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run: 'Resolves an action locally using ThaliPeerPoolDefault''

[33mok 453 Host address must match
ok 454 suggestedTCPTimeout must match
ok 455 connectionType must match
ok 456 portNumber must match
[39m
[33m# teardown
[39m
[36mok 453 Host address must match
ok 454 suggestedTCPTimeout must match
ok 455 connectionType must match
[39m
[36mok 456 portNumber must match
[39m
[36m# teardown
[39m
[32mok 453 Host address must match
[39m
[32mok 454 suggestedTCPTimeout must match
ok 455 connectionType must match
[39m
[32mok 456 portNumber must match
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run ok: 'Resolves an action locally using ThaliPeerPoolDefault''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown: 'Resolves an action locally using ThaliPeerPoolDefault''

[32m# teardown
[39m
[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#teardown ok: 'Resolves an action locally using ThaliPeerPoolDefault''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup: 'Action fails because of a bad hostname.''

[33mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[33m# Action fails because of a bad hostname.
[39m
[36mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[36m# Action fails because of a bad hostname.
[39m
[32mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[32m# Action fails because of a bad hostname.
[39m
2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#setup ok: 'Action fails because of a bad hostname.''

2016-10-04 22:57:30 - DEBUG UnitTestFramework: '#run: 'Action fails because of a bad hostname.''

[32mok 457 action should be resolved with NETWORK_PROBLEM error
[39m
[36mok 457 action should be resolved with NETWORK_PROBLEM error
[39m
[33mok 457 action should be resolved with NETWORK_PROBLEM error
[39m
[36mok 458 action should be resolved with NETWORK_PROBLEM error
[39m
[33mok 458 action should be resolved with NETWORK_PROBLEM error
[39m
[32mok 458 action should be resolved with NETWORK_PROBLEM error
[39m
[36mok 459 action should be resolved with NETWORK_PROBLEM error
[39m
[33mok 459 action should be resolved with NETWORK_PROBLEM error
[39m
[32mok 459 action should be resolved with NETWORK_PROBLEM error
[39m
[36mok 460 action should be resolved with NETWORK_PROBLEM error
ok 461 correct number of requests
ok 462 correct number of failures
ok 463 correct final peer state
# teardown
[39m
[32mok 460 action should be resolved with NETWORK_PROBLEM error
ok 461 correct number of requests
ok 462 correct number of failures
ok 463 correct final peer state
# teardown
[39m
[33mok 460 action should be resolved with NETWORK_PROBLEM error
ok 461 correct number of requests
ok 462 correct number of failures
[39m
[33mok 463 correct final peer state
[39m
[33m# teardown
[39m
2016-10-04 22:57:32 - DEBUG UnitTestFramework: '#run ok: 'Action fails because of a bad hostname.''
2016-10-04 22:57:32 - DEBUG UnitTestFramework: '#teardown: 'Action fails because of a bad hostname.''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:32 - DEBUG UnitTestFramework: '#teardown ok: 'Action fails because of a bad hostname.''

2016-10-04 22:57:32 - DEBUG UnitTestFramework: '#setup: 'hostaddress is removed when the action is running. ''

[33mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[36mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[33m# hostaddress is removed when the action is running. 
[39m
[36m# hostaddress is removed when the action is running. 
[39m
[32mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[32m# hostaddress is removed when the action is running. 
[39m
2016-10-04 22:57:32 - DEBUG UnitTestFramework: '#setup ok: 'hostaddress is removed when the action is running. ''

2016-10-04 22:57:32 - DEBUG UnitTestFramework: '#run: 'hostaddress is removed when the action is running. ''

[32mok 464 should be equal
# teardown
[39m
[36mok 464 should be equal
# teardown
[39m
[33mok 464 should be equal
[39m
[33m# teardown
[39m
2016-10-04 22:57:34 - DEBUG UnitTestFramework: '#run ok: 'hostaddress is removed when the action is running. ''
2016-10-04 22:57:34 - DEBUG UnitTestFramework: '#teardown: 'hostaddress is removed when the action is running. ''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:34 - DEBUG UnitTestFramework: '#teardown ok: 'hostaddress is removed when the action is running. ''
2016-10-04 22:57:34 - DEBUG UnitTestFramework: '#setup: 'Client to server request locally''

[36mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[36m# Client to server request locally
[39m
[32mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[32m# Client to server request locally
[39m
[33mWarning: a promise was created in a handler but was not returned from it, see http://goo.gl/rRqMUw
    at process._tickCallback (node.js:917:13)
[39m
[33m# Client to server request locally
[39m
2016-10-04 22:57:34 - DEBUG UnitTestFramework: '#setup ok: 'Client to server request locally''

2016-10-04 22:57:34 - DEBUG UnitTestFramework: '#run: 'Client to server request locally''

[36mok 465 secrets are equal
ok 466 Public key matches with the server key
ok 467 Host address must match
ok 468 suggestedTCPTimeout must match
ok 469 connectionType must match
ok 470 portNumber must match
# teardown
[39m
[33mok 465 secrets are equal
ok 466 Public key matches with the server key
ok 467 Host address must match
ok 468 suggestedTCPTimeout must match
ok 469 connectionType must match
ok 470 portNumber must match
# teardown
[39m
[32mok 465 secrets are equal
[39m
[32mok 466 Public key matches with the server key
ok 467 Host address must match
ok 468 suggestedTCPTimeout must match
[39m
[32mok 469 connectionType must match
ok 470 portNumber must match
[39m
[32m# teardown
[39m
2016-10-04 22:57:34 - DEBUG UnitTestFramework: '#run ok: 'Client to server request locally''
2016-10-04 22:57:34 - DEBUG UnitTestFramework: '#teardown: 'Client to server request locally''

[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:34 - DEBUG UnitTestFramework: '#teardown ok: 'Client to server request locally''

2016-10-04 22:57:34 - DEBUG UnitTestFramework: '#setup: 'Test ThaliPskMapCache clean and expiration''

[33m# Test ThaliPskMapCache clean and expiration
[39m
[36m# Test ThaliPskMapCache clean and expiration
[39m
[32m# Test ThaliPskMapCache clean and expiration
[39m
2016-10-04 22:57:34 - DEBUG UnitTestFramework: '#setup ok: 'Test ThaliPskMapCache clean and expiration''

2016-10-04 22:57:34 - DEBUG UnitTestFramework: '#run: 'Test ThaliPskMapCache clean and expiration''

[32mok 471 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
ok 472 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
[39m
[36mok 471 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
ok 472 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
[39m
[33mok 471 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
[39m
[33mok 472 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
[39m
[32mok 473 All entries should be expired after 1 second
[39m
[32m# teardown
[39m
[36mok 473 All entries should be expired after 1 second
# teardown
[39m
[33mok 473 All entries should be expired after 1 second
# teardown
[39m
2016-10-04 22:57:35 - DEBUG UnitTestFramework: '#run ok: 'Test ThaliPskMapCache clean and expiration''

2016-10-04 22:57:35 - DEBUG UnitTestFramework: '#teardown: 'Test ThaliPskMapCache clean and expiration''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:35 - DEBUG UnitTestFramework: '#teardown ok: 'Test ThaliPskMapCache clean and expiration''

2016-10-04 22:57:35 - DEBUG UnitTestFramework: '#setup: 'Test ThaliPskMapCache getSecret and getPublic''

[36m# Test ThaliPskMapCache getSecret and getPublic
[39m
[32m# Test ThaliPskMapCache getSecret and getPublic
[39m
[33m# Test ThaliPskMapCache getSecret and getPublic
[39m
2016-10-04 22:57:35 - DEBUG UnitTestFramework: '#setup ok: 'Test ThaliPskMapCache getSecret and getPublic''

2016-10-04 22:57:35 - DEBUG UnitTestFramework: '#run: 'Test ThaliPskMapCache getSecret and getPublic''

[36mok 474 All keys need to be available in the cache
[39m
[33mok 474 All keys need to be available in the cache
[39m
[32mok 474 All keys need to be available in the cache
[39m
[36mok 475 All entries should be expired after 1 second
# teardown
[39m
[33mok 475 All entries should be expired after 1 second
# teardown
[39m
[32mok 475 All entries should be expired after 1 second
[39m
[32m# teardown
[39m
2016-10-04 22:57:36 - DEBUG UnitTestFramework: '#run ok: 'Test ThaliPskMapCache getSecret and getPublic''
2016-10-04 22:57:36 - DEBUG UnitTestFramework: '#teardown: 'Test ThaliPskMapCache getSecret and getPublic''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:36 - DEBUG UnitTestFramework: '#teardown ok: 'Test ThaliPskMapCache getSecret and getPublic''

2016-10-04 22:57:36 - DEBUG UnitTestFramework: '#setup: 'Test ThaliPskMapCache multiple entries''

[36m# Test ThaliPskMapCache multiple entries
[39m
[33m# Test ThaliPskMapCache multiple entries
[39m
[32m# Test ThaliPskMapCache multiple entries
[39m
2016-10-04 22:57:36 - DEBUG UnitTestFramework: '#setup ok: 'Test ThaliPskMapCache multiple entries''

2016-10-04 22:57:36 - DEBUG UnitTestFramework: '#run: 'Test ThaliPskMapCache multiple entries''

[36mok 476 Size of the cache should be 2
[39m
[36mok 477 Cache doesn't contain dictionary1
[39m
[32mok 476 Size of the cache should be 2
[39m
[32mok 477 Cache doesn't contain dictionary1
[39m
[33mok 476 Size of the cache should be 2
[39m
[33mok 477 Cache doesn't contain dictionary1
[39m
[36mok 478 Size of the cache should be 1
ok 479 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
[39m
[32mok 478 Size of the cache should be 1
ok 479 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
[39m
[33mok 478 Size of the cache should be 1
[39m
[33mok 479 Cache doesn't contain beaconStreamAndSecretDictionary2
[39m
[33m# teardown
[39m
2016-10-04 22:57:38 - DEBUG UnitTestFramework: '#run ok: 'Test ThaliPskMapCache multiple entries''

2016-10-04 22:57:38 - DEBUG UnitTestFramework: '#teardown: 'Test ThaliPskMapCache multiple entries''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:38 - DEBUG UnitTestFramework: '#teardown ok: 'Test ThaliPskMapCache multiple entries''
2016-10-04 22:57:38 - DEBUG UnitTestFramework: '#setup: 'Start and stop ThaliNotificationServer''

[36m# Start and stop ThaliNotificationServer
[39m
[32m# Start and stop ThaliNotificationServer
[39m
[33m# Start and stop ThaliNotificationServer
[39m
2016-10-04 22:57:38 - DEBUG UnitTestFramework: '#setup ok: 'Start and stop ThaliNotificationServer''

2016-10-04 22:57:38 - DEBUG UnitTestFramework: '#run: 'Start and stop ThaliNotificationServer''

[36mok 480 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
ok 481 ThaliMobile.StopAdvertisingAndListeningshould be called once
# teardown
[39m
[33mok 480 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
ok 481 ThaliMobile.StopAdvertisingAndListeningshould be called once
# teardown
[39m
[32mok 480 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
[39m
[32mok 481 ThaliMobile.StopAdvertisingAndListeningshould be called once
[39m
[32m# teardown
[39m
2016-10-04 22:57:38 - DEBUG UnitTestFramework: '#run ok: 'Start and stop ThaliNotificationServer''

2016-10-04 22:57:38 - DEBUG UnitTestFramework: '#teardown: 'Start and stop ThaliNotificationServer''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:38 - DEBUG UnitTestFramework: '#teardown ok: 'Start and stop ThaliNotificationServer''
2016-10-04 22:57:38 - DEBUG UnitTestFramework: '#setup: 'Pass an empty array to ThaliNotificationServer.start''

[36m# Pass an empty array to ThaliNotificationServer.start
[39m
[32m# Pass an empty array to ThaliNotificationServer.start
[39m
[33m# Pass an empty array to ThaliNotificationServer.start
[39m
2016-10-04 22:57:38 - DEBUG UnitTestFramework: '#setup ok: 'Pass an empty array to ThaliNotificationServer.start''

2016-10-04 22:57:38 - DEBUG UnitTestFramework: '#run: 'Pass an empty array to ThaliNotificationServer.start''

[36mok 482 StartUpdateAdvertisingAndListening should not be called
ok 483 ThaliMobile.StopAdvertisingAndListening should be called once
ok 484 no error
ok 485 should be 204
# teardown
[39m
[33mok 482 StartUpdateAdvertisingAndListening should not be called
ok 483 ThaliMobile.StopAdvertisingAndListening should be called once
ok 484 no error
ok 485 should be 204
# teardown
[39m
[32mok 482 StartUpdateAdvertisingAndListening should not be called
[39m
[32mok 483 ThaliMobile.StopAdvertisingAndListening should be called once
[39m
[32mok 484 no error
[39m
[32mok 485 should be 204
[39m
[32m# teardown
[39m
2016-10-04 22:57:38 - DEBUG UnitTestFramework: '#run ok: 'Pass an empty array to ThaliNotificationServer.start''
2016-10-04 22:57:38 - DEBUG UnitTestFramework: '#teardown: 'Pass an empty array to ThaliNotificationServer.start''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:38 - DEBUG UnitTestFramework: '#teardown ok: 'Pass an empty array to ThaliNotificationServer.start''

2016-10-04 22:57:38 - DEBUG UnitTestFramework: '#setup: 'Pass a string to ThaliNotificationServer.start''

[33m# Pass a string to ThaliNotificationServer.start
[39m
[36m# Pass a string to ThaliNotificationServer.start
[39m
[32m# Pass a string to ThaliNotificationServer.start
[39m
2016-10-04 22:57:38 - DEBUG UnitTestFramework: '#setup ok: 'Pass a string to ThaliNotificationServer.start''

2016-10-04 22:57:38 - DEBUG UnitTestFramework: '#run: 'Pass a string to ThaliNotificationServer.start''

[36mok 486 StartUpdateAdvertisingAndListening should not be called
[39m
[36m# teardown
[39m
[32mok 486 StartUpdateAdvertisingAndListening should not be called
[39m
[32m# teardown
[39m
[33mok 486 StartUpdateAdvertisingAndListening should not be called
[39m
[33m# teardown
[39m
2016-10-04 22:57:38 - DEBUG UnitTestFramework: '#run ok: 'Pass a string to ThaliNotificationServer.start''

2016-10-04 22:57:38 - DEBUG UnitTestFramework: '#teardown: 'Pass a string to ThaliNotificationServer.start''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:38 - DEBUG UnitTestFramework: '#teardown ok: 'Pass a string to ThaliNotificationServer.start''

2016-10-04 22:57:38 - DEBUG UnitTestFramework: '#setup: 'Pass an empty parameter to ThaliNotificationServer.start''

[36m# Pass an empty parameter to ThaliNotificationServer.start
[39m
[33m# Pass an empty parameter to ThaliNotificationServer.start
[39m
[32m# Pass an empty parameter to ThaliNotificationServer.start
[39m
2016-10-04 22:57:38 - DEBUG UnitTestFramework: '#setup ok: 'Pass an empty parameter to ThaliNotificationServer.start''

2016-10-04 22:57:38 - DEBUG UnitTestFramework: '#run: 'Pass an empty parameter to ThaliNotificationServer.start''

[36mok 487 StartUpdateAdvertisingAndListening should not be called
[39m
[36m# teardown
[39m
[32mok 487 StartUpdateAdvertisingAndListening should not be called
[39m
[32m# teardown
[39m
[33mok 487 StartUpdateAdvertisingAndListening should not be called
[39m
[33m# teardown
[39m
2016-10-04 22:57:38 - DEBUG UnitTestFramework: '#run ok: 'Pass an empty parameter to ThaliNotificationServer.start''

2016-10-04 22:57:38 - DEBUG UnitTestFramework: '#teardown: 'Pass an empty parameter to ThaliNotificationServer.start''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:38 - DEBUG UnitTestFramework: '#teardown ok: 'Pass an empty parameter to ThaliNotificationServer.start''

2016-10-04 22:57:38 - DEBUG UnitTestFramework: '#setup: 'Make an HTTP request to /NotificationBeacons''

[32m# Make an HTTP request to /NotificationBeacons
[39m
[33m# Make an HTTP request to /NotificationBeacons
[39m
[36m# Make an HTTP request to /NotificationBeacons
[39m
2016-10-04 22:57:38 - DEBUG UnitTestFramework: '#setup ok: 'Make an HTTP request to /NotificationBeacons''

2016-10-04 22:57:38 - DEBUG UnitTestFramework: '#run: 'Make an HTTP request to /NotificationBeacons''

[32mok 488 no error
[39m
[32mok 489 should be 200
ok 490 should be equal
ok 491 should be equal
[39m
[32mok 492 (unnamed assert)
[39m
[32mok 493 no error
[39m
[32mok 494 should be 204
[39m
[32m# teardown
[39m
[33mok 488 no error
[39m
[36mok 488 no error
ok 489 should be 200
ok 490 should be equal
ok 491 should be equal
[39m
[33mok 489 should be 200
[39m
[33mok 490 should be equal
[39m
[33mok 491 should be equal
[39m
[36mok 492 (unnamed assert)
[39m
[33mok 492 (unnamed assert)
[39m
[36mok 493 no error
[39m
[36mok 494 should be 204
[39m
[36m# teardown
[39m
[33mok 493 no error
[39m
[33mok 494 should be 204
[39m
2016-10-04 22:57:38 - DEBUG UnitTestFramework: '#run ok: 'Make an HTTP request to /NotificationBeacons''

2016-10-04 22:57:38 - DEBUG UnitTestFramework: '#teardown: 'Make an HTTP request to /NotificationBeacons''

[33m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#teardown ok: 'Make an HTTP request to /NotificationBeacons''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#setup: 'Make an HTTP request to /NotificationBeacons (no keys)''

[32m# Make an HTTP request to /NotificationBeacons (no keys)
[39m
[33m# Make an HTTP request to /NotificationBeacons (no keys)
[39m
[36m# Make an HTTP request to /NotificationBeacons (no keys)
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#setup ok: 'Make an HTTP request to /NotificationBeacons (no keys)''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#run: 'Make an HTTP request to /NotificationBeacons (no keys)''

[32mok 495 error should be null
ok 496 should be 204
[39m
[33mok 495 error should be null
ok 496 should be 204
[39m
[32m# teardown
[39m
[33m# teardown
[39m
[36mok 495 error should be null
ok 496 should be 204
[39m
[36m# teardown
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#run ok: 'Make an HTTP request to /NotificationBeacons (no keys)''
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#teardown: 'Make an HTTP request to /NotificationBeacons (no keys)''

[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#teardown ok: 'Make an HTTP request to /NotificationBeacons (no keys)''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#setup: 'Make an HTTP request to /NotificationBeaconsbefore calling start''

[33m# Make an HTTP request to /NotificationBeaconsbefore calling start
[39m
[32m# Make an HTTP request to /NotificationBeaconsbefore calling start
[39m
[36m# Make an HTTP request to /NotificationBeaconsbefore calling start
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#setup ok: 'Make an HTTP request to /NotificationBeaconsbefore calling start''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#run: 'Make an HTTP request to /NotificationBeaconsbefore calling start''

[33mok 497 should be 404
[39m
[33m# teardown
[39m
[32mok 497 should be 404
[39m
[32m# teardown
[39m
[36mok 497 should be 404
[39m
[36m# teardown
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#run ok: 'Make an HTTP request to /NotificationBeaconsbefore calling start''
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#teardown: 'Make an HTTP request to /NotificationBeaconsbefore calling start''

[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#teardown ok: 'Make an HTTP request to /NotificationBeaconsbefore calling start''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#setup: '#testThaliPeerAction - test getters''

[33m# #testThaliPeerAction - test getters
[39m
[36m# #testThaliPeerAction - test getters
[39m
[32m# #testThaliPeerAction - test getters
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#setup ok: '#testThaliPeerAction - test getters''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#run: '#testThaliPeerAction - test getters''

[32mok 498 getPeerIdentifier
ok 499 getConnectionType
ok 500 getActionType
ok 501 getActionState
ok 502 getPskIdentity
ok 503 getPskKey
# teardown
[39m
[36mok 498 getPeerIdentifier
ok 499 getConnectionType
ok 500 getActionType
ok 501 getActionState
ok 502 getPskIdentity
[39m
[36mok 503 getPskKey
# teardown
[39m
[33mok 498 getPeerIdentifier
ok 499 getConnectionType
ok 500 getActionType
ok 501 getActionState
ok 502 getPskIdentity
ok 503 getPskKey
[39m
[33m# teardown
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#run ok: '#testThaliPeerAction - test getters''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#teardown: '#testThaliPeerAction - test getters''

[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#teardown ok: '#testThaliPeerAction - test getters''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#setup: '#testThaliPeerAction - start and kill''

[33m# #testThaliPeerAction - start and kill
[39m
[32m# #testThaliPeerAction - start and kill
[39m
[36m# #testThaliPeerAction - start and kill
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#setup ok: '#testThaliPeerAction - start and kill''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#run: '#testThaliPeerAction - start and kill''

[32mok 504 initial state
ok 505 after start
ok 506 after kill
[39m
[33mok 504 initial state
ok 505 after start
[39m
[33mok 506 after kill
[39m
[32m# teardown
[39m
[33m# teardown
[39m
[36mok 504 initial state
[39m
[36mok 505 after start
[39m
[36mok 506 after kill
[39m
[36m# teardown
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#run ok: '#testThaliPeerAction - start and kill''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#teardown: '#testThaliPeerAction - start and kill''

[32m# setup
[39m
[33m# setup
[39m
[36m# setup
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#teardown ok: '#testThaliPeerAction - start and kill''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#setup: '#testThaliPeerAction - double start''

[36m# #testThaliPeerAction - double start
[39m
[32m# #testThaliPeerAction - double start
[39m
[33m# #testThaliPeerAction - double start
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#setup ok: '#testThaliPeerAction - double start''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#run: '#testThaliPeerAction - double start''

[36mok 507 should be equal
[39m
[36m# teardown
[39m
[33mok 507 should be equal
[39m
[33m# teardown
[39m
[32mok 507 should be equal
[39m
[32m# teardown
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#run ok: '#testThaliPeerAction - double start''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#teardown: '#testThaliPeerAction - double start''

[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#teardown ok: '#testThaliPeerAction - double start''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#setup: '#testThaliPeerAction - start after kill''

[36m# #testThaliPeerAction - start after kill
[39m
[33m# #testThaliPeerAction - start after kill
[39m
[32m# #testThaliPeerAction - start after kill
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#setup ok: '#testThaliPeerAction - start after kill''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#run: '#testThaliPeerAction - start after kill''

[36mok 508 clean kill
[39m
[36mok 509 should be equal
[39m
[36m# teardown
[39m
[33mok 508 clean kill
[39m
[33mok 509 should be equal
[39m
[33m# teardown
[39m
[32mok 508 clean kill
[39m
[32mok 509 should be equal
[39m
[32m# teardown
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#run ok: '#testThaliPeerAction - start after kill''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#teardown: '#testThaliPeerAction - start after kill''

[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#teardown ok: '#testThaliPeerAction - start after kill''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#setup: '#testThaliPeerAction - make sure ids are unique''

[36m# #testThaliPeerAction - make sure ids are unique
[39m
[33m# #testThaliPeerAction - make sure ids are unique
[39m
[32m# #testThaliPeerAction - make sure ids are unique
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#setup ok: '#testThaliPeerAction - make sure ids are unique''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#run: '#testThaliPeerAction - make sure ids are unique''

[36mok 510 should not be equal
[39m
[36m# teardown
[39m
[33mok 510 should not be equal
[39m
[33m# teardown
[39m
[32mok 510 should not be equal
[39m
[32m# teardown
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#run ok: '#testThaliPeerAction - make sure ids are unique''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#teardown: '#testThaliPeerAction - make sure ids are unique''

[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#teardown ok: '#testThaliPeerAction - make sure ids are unique''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#setup: 'Test PeerConnectionInformation basics''

[36m# Test PeerConnectionInformation basics
[39m
[33m# Test PeerConnectionInformation basics
[39m
[32m# Test PeerConnectionInformation basics
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#setup ok: 'Test PeerConnectionInformation basics''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#run: 'Test PeerConnectionInformation basics''

[36mok 511 connection type works
[39m
[36mok 512 getHostAddress works
[39m
[36mok 513 getPortNumber works
ok 514 getSuggestedTCPTimeout works
[39m
[36m# teardown
[39m
[33mok 511 connection type works
[39m
[33mok 512 getHostAddress works
ok 513 getPortNumber works
[39m
[33mok 514 getSuggestedTCPTimeout works
[39m
[33m# teardown
[39m
[32mok 511 connection type works
[39m
[32mok 512 getHostAddress works
ok 513 getPortNumber works
ok 514 getSuggestedTCPTimeout works
[39m
[32m# teardown
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#run ok: 'Test PeerConnectionInformation basics''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#teardown: 'Test PeerConnectionInformation basics''

[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#teardown ok: 'Test PeerConnectionInformation basics''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#setup: 'Test PeerDictionary basic functionality''

[36m# Test PeerDictionary basic functionality
[39m
[33m# Test PeerDictionary basic functionality
[39m
[32m# Test PeerDictionary basic functionality
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#setup ok: 'Test PeerDictionary basic functionality''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#run: 'Test PeerDictionary basic functionality''

[36mok 515 Entry counter must be 1
[39m
[36mok 516 Size must be 1
ok 517 Entry counter must be 2
ok 518 Size must be 2
[39m
[36mok 519 Entry2 should not be found
[39m
[36mok 520 Size must be 1
ok 521 Size must be 0
[39m
[36m# teardown
[39m
[33mok 515 Entry counter must be 1
[39m
[33mok 516 Size must be 1
[39m
[33mok 517 Entry counter must be 2
[39m
[33mok 518 Size must be 2
[39m
[33mok 519 Entry2 should not be found
[39m
[33mok 520 Size must be 1
[39m
[33mok 521 Size must be 0
[39m
[33m# teardown
[39m
[32mok 515 Entry counter must be 1
[39m
[32mok 516 Size must be 1
[39m
[32mok 517 Entry counter must be 2
ok 518 Size must be 2
[39m
[32mok 519 Entry2 should not be found
[39m
[32mok 520 Size must be 1
[39m
[32mok 521 Size must be 0
[39m
[32m# teardown
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#run ok: 'Test PeerDictionary basic functionality''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#teardown: 'Test PeerDictionary basic functionality''

[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#teardown ok: 'Test PeerDictionary basic functionality''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#setup: 'Test PeerDictionary with multiple entries.''

[36m# Test PeerDictionary with multiple entries.
[39m
[33m# Test PeerDictionary with multiple entries.
[39m
[32m# Test PeerDictionary with multiple entries.
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#setup ok: 'Test PeerDictionary with multiple entries.''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#run: 'Test PeerDictionary with multiple entries.''

[36mok 522 Size must be100
ok 523 Entries between 20 and MAXSIZE + 20 should exist
[39m
[33mok 522 Size must be100
ok 523 Entries between 20 and MAXSIZE + 20 should exist
[39m
[32mok 522 Size must be100
[39m
[32mok 523 Entries between 20 and MAXSIZE + 20 should exist
[39m
[36mok 524 WAITING state entry should not be removed
# teardown
[39m
[33mok 524 WAITING state entry should not be removed
# teardown
[39m
[32mok 524 WAITING state entry should not be removed
[39m
[32m# teardown
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#run ok: 'Test PeerDictionary with multiple entries.''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#teardown: 'Test PeerDictionary with multiple entries.''

[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#teardown ok: 'Test PeerDictionary with multiple entries.''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#setup: 'RESOLVED entries are removed before WAITING state entry.''

[36m# RESOLVED entries are removed before WAITING state entry.
[39m
[33m# RESOLVED entries are removed before WAITING state entry.
[39m
[32m# RESOLVED entries are removed before WAITING state entry.
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#setup ok: 'RESOLVED entries are removed before WAITING state entry.''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#run: 'RESOLVED entries are removed before WAITING state entry.''

[36mok 525 Entries between 6 and MAXSIZE + 4 should exist
ok 526 Size should be MAXSIZE
ok 527 Size should be MAXSIZE+6
[39m
[36m# teardown
[39m
[33mok 525 Entries between 6 and MAXSIZE + 4 should exist
ok 526 Size should be MAXSIZE
ok 527 Size should be MAXSIZE+6
[39m
[33m# teardown
[39m
[32mok 525 Entries between 6 and MAXSIZE + 4 should exist
[39m
[32mok 526 Size should be MAXSIZE
ok 527 Size should be MAXSIZE+6
[39m
[32m# teardown
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#run ok: 'RESOLVED entries are removed before WAITING state entry.''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#teardown: 'RESOLVED entries are removed before WAITING state entry.''

[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#teardown ok: 'RESOLVED entries are removed before WAITING state entry.''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#setup: 'WAITING entries are removed before CONTROLLED_BY_POOL state entry.''

[36m# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
[39m
[33m# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
[39m
[32m# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#setup ok: 'WAITING entries are removed before CONTROLLED_BY_POOL state entry.''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#run: 'WAITING entries are removed before CONTROLLED_BY_POOL state entry.''

[36mok 528 WAITING state entry should not be removed
[39m
[36mok 529 Waiting entries between 6 and MAXSIZE + 4 should exist
ok 530 Size should be MAXSIZE
ok 531 entryCounter should be MAXSIZE+6
# teardown
[39m
[33mok 528 WAITING state entry should not be removed
[39m
[33mok 529 Waiting entries between 6 and MAXSIZE + 4 should exist
ok 530 Size should be MAXSIZE
ok 531 entryCounter should be MAXSIZE+6
# teardown
[39m
[32mok 528 WAITING state entry should not be removed
[39m
[32mok 529 Waiting entries between 6 and MAXSIZE + 4 should exist
ok 530 Size should be MAXSIZE
[39m
[32mok 531 entryCounter should be MAXSIZE+6
[39m
[32m# teardown
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#run ok: 'WAITING entries are removed before CONTROLLED_BY_POOL state entry.''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#teardown: 'WAITING entries are removed before CONTROLLED_BY_POOL state entry.''

[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#teardown ok: 'WAITING entries are removed before CONTROLLED_BY_POOL state entry.''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#setup: 'When CONTROLLED_BY_POOL entry is removed and kill is called.''

[32m# When CONTROLLED_BY_POOL entry is removed and kill is called.
[39m
[33m# When CONTROLLED_BY_POOL entry is removed and kill is called.
[39m
[36m# When CONTROLLED_BY_POOL entry is removed and kill is called.
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#setup ok: 'When CONTROLLED_BY_POOL entry is removed and kill is called.''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#run: 'When CONTROLLED_BY_POOL entry is removed and kill is called.''

[36mok 532 Kill should be called once
[39m
[36mok 533 Size should be 100
[39m
[36m# teardown
[39m
[33mok 532 Kill should be called once
[39m
[33mok 533 Size should be 100
[39m
[33m# teardown
[39m
[32mok 532 Kill should be called once
[39m
[32mok 533 Size should be 100
[39m
[32m# teardown
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#run ok: 'When CONTROLLED_BY_POOL entry is removed and kill is called.''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#teardown: 'When CONTROLLED_BY_POOL entry is removed and kill is called.''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#teardown ok: 'When CONTROLLED_BY_POOL entry is removed and kill is called.''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolDefault - single action''

[36m# #ThaliPeerPoolDefault - single action
[39m
[33m# #ThaliPeerPoolDefault - single action
[39m
[32m# #ThaliPeerPoolDefault - single action
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolDefault - single action''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolDefault - single action''

[36mok 534 is an agent
[39m
[36mok 535 enqueue is fine
[39m
[36mok 536 Everything should be off the queue
[39m
[36m# teardown
[39m
[32mok 534 is an agent
[39m
[32mok 535 enqueue is fine
[39m
[32mok 536 Everything should be off the queue
[39m
[32m# teardown
[39m
[33mok 534 is an agent
[39m
[33mok 535 enqueue is fine
[39m
[33mok 536 Everything should be off the queue
[39m
[33m# teardown
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolDefault - single action''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolDefault - single action''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolDefault - single action''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolDefault - multiple actions''

[36m# #ThaliPeerPoolDefault - multiple actions
[39m
[32m# #ThaliPeerPoolDefault - multiple actions
[39m
[33m# #ThaliPeerPoolDefault - multiple actions
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolDefault - multiple actions''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolDefault - multiple actions''

[36mok 537 is an agent
ok 538 first enqueue is fine
[39m
[36mok 539 is an agent
[39m
[36mok 540 second enqueue is fine
[39m
[36mok 541 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
[39m
[36mok 542 Queue is empty
[39m
[36m# teardown
[39m
[32mok 537 is an agent
[39m
[32mok 538 first enqueue is fine
[39m
[32mok 539 is an agent
[39m
[32mok 540 second enqueue is fine
[39m
[32mok 541 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
[39m
[33mok 537 is an agent
[39m
[33mok 538 first enqueue is fine
[39m
[32mok 542 Queue is empty
[39m
[33mok 539 is an agent
[39m
[33mok 540 second enqueue is fine
[39m
[32m# teardown
[39m
[33mok 541 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 542 Queue is empty
[39m
[33m# teardown
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolDefault - multiple actions''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolDefault - multiple actions''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolDefault - multiple actions''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolDefault - PSK Pool works''

[36m# #ThaliPeerPoolDefault - PSK Pool works
[39m
[33m# #ThaliPeerPoolDefault - PSK Pool works
[39m
[32m# #ThaliPeerPoolDefault - PSK Pool works
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolDefault - PSK Pool works''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolDefault - PSK Pool works''

[36mok 543 is an agent
[39m
[36mok 544 good enqueue
[39m
[32mok 543 is an agent
[39m
[32mok 544 good enqueue
[39m
[36mok 545 Identity should match
[39m
[32mok 545 Identity should match
[39m
[36mok 546 Got expected response
[39m
[36mok 547 Got psk call back
[39m
[36m# teardown
[39m
[32mok 546 Got expected response
[39m
[32mok 547 Got psk call back
[39m
[32m# teardown
[39m
[33mok 543 is an agent
[39m
[33mok 544 good enqueue
[39m
[33mok 545 Identity should match
[39m
[33mok 546 Got expected response
[39m
[33mok 547 Got psk call back
[39m
[33m# teardown
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolDefault - PSK Pool works''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolDefault - PSK Pool works''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolDefault - PSK Pool works''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolDefault - stop''

[36m# #ThaliPeerPoolDefault - stop
[39m
[32m# #ThaliPeerPoolDefault - stop
[39m
[33m# #ThaliPeerPoolDefault - stop
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolDefault - stop''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolDefault - stop''

[36mok 548 is an agent
[39m
[36mok 549 enqueue worked
[39m
[36mok 550 is an agent
[39m
[36mok 551 enqueue 2 worked
[39m
[36mok 552 enqueue is not available when stopped
[39m
[36mok 553 start action is killed
[39m
[36mok 554 killed action is still killed
ok 555 inQueue is empty
# teardown
[39m
[32mok 548 is an agent
ok 549 enqueue worked
ok 550 is an agent
ok 551 enqueue 2 worked
[39m
[32mok 552 enqueue is not available when stopped
[39m
[32mok 553 start action is killed
ok 554 killed action is still killed
ok 555 inQueue is empty
[39m
[32m# teardown
[39m
[33mok 548 is an agent
[39m
[33mok 549 enqueue worked
ok 550 is an agent
[39m
[33mok 551 enqueue 2 worked
[39m
[33mok 552 enqueue is not available when stopped
[39m
[33mok 553 start action is killed
ok 554 killed action is still killed
[39m
[33mok 555 inQueue is empty
[39m
[33m# teardown
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolDefault - stop''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolDefault - stop''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolDefault - stop''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolInterface - make sure that start verifies queue length''

[36m# #ThaliPeerPoolInterface - make sure that start verifies queue length
[39m
[33m# #ThaliPeerPoolInterface - make sure that start verifies queue length
[39m
[32m# #ThaliPeerPoolInterface - make sure that start verifies queue length
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolInterface - make sure that start verifies queue length''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolInterface - make sure that start verifies queue length''

[36mok 556 good start
[39m
[36mok 557 good enqueue
[39m
[36mok 558 queue is not empty
[39m
[32mok 556 good start
[39m
[36m# teardown
[39m
[32mok 557 good enqueue
[39m
[33mok 556 good start
[39m
[32mok 558 queue is not empty
[39m
[33mok 557 good enqueue
[39m
[32m# teardown
[39m
[33mok 558 queue is not empty
[39m
[33m# teardown
[39m
2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolInterface - make sure that start verifies queue length''

2016-10-04 22:57:39 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolInterface - make sure that start verifies queue length''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolInterface - make sure that start verifies queue length''

2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolInterface - bad enqueues''

[36m# #ThaliPeerPoolInterface - bad enqueues
[39m
[32m# #ThaliPeerPoolInterface - bad enqueues
[39m
[33m# #ThaliPeerPoolInterface - bad enqueues
[39m
2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolInterface - bad enqueues''

2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolInterface - bad enqueues''

[36mok 559 null arg
ok 560 wrong arg type
ok 561 wrong arg type
# teardown
[39m
[33mok 559 null arg
ok 560 wrong arg type
ok 561 wrong arg type
[39m
[33m# teardown
[39m
[32mok 559 null arg
ok 560 wrong arg type
ok 561 wrong arg type
[39m
[32m# teardown
[39m
2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolInterface - bad enqueues''

2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolInterface - bad enqueues''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolInterface - bad enqueues''

2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolInterface - do not allow same object type''

[36m# #ThaliPeerPoolInterface - do not allow same object type
[39m
[33m# #ThaliPeerPoolInterface - do not allow same object type
[39m
[32m# #ThaliPeerPoolInterface - do not allow same object type
[39m
2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolInterface - do not allow same object type''

2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolInterface - do not allow same object type''

[36mok 562 good enqueue
ok 563 already enqueued
[39m
[36m# teardown
[39m
[32mok 562 good enqueue
[39m
[32mok 563 already enqueued
[39m
[32m# teardown
[39m
[33mok 562 good enqueue
[39m
[33mok 563 already enqueued
[39m
[33m# teardown
[39m
2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolInterface - do not allow same object type''

2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolInterface - do not allow same object type''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolInterface - do not allow same object type''

2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolInterface - make sure we catch kill and dequeue''

[36m# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
[39m
[33m# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
[39m
[32m# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
[39m
2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolInterface - make sure we catch kill and dequeue''

2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolInterface - make sure we catch kill and dequeue''

[36mok 564 good enqueue
ok 565 2nd good enqueue
ok 566 we are in the pool
[39m
[36mok 567 We are out of the pool
ok 568 Action was killed
ok 569 The original kill was called too
ok 570 second item is still in queue
# teardown
[39m
[32mok 564 good enqueue
[39m
[32mok 565 2nd good enqueue
ok 566 we are in the pool
[39m
[33mok 564 good enqueue
ok 565 2nd good enqueue
ok 566 we are in the pool
[39m
[33mok 567 We are out of the pool
ok 568 Action was killed
ok 569 The original kill was called too
ok 570 second item is still in queue
[39m
[32mok 567 We are out of the pool
ok 568 Action was killed
ok 569 The original kill was called too
ok 570 second item is still in queue
[39m
[33m# teardown
[39m
[32m# teardown
[39m
2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolInterface - make sure we catch kill and dequeue''

2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolInterface - make sure we catch kill and dequeue''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolInterface - make sure we catch kill and dequeue''

2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent''

[36m# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
[39m
[33m# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
[39m
[32m# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
[39m
2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent''

2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent''

[36mok 571 good enqueue
ok 572 first kill
[39m
[36mok 573 second NOOP kill
[39m
[36m# teardown
[39m
[32mok 571 good enqueue
[39m
[32mok 572 first kill
ok 573 second NOOP kill
[39m
[32m# teardown
[39m
[33mok 571 good enqueue
[39m
[33mok 572 first kill
[39m
[33mok 573 second NOOP kill
[39m
[33m# teardown
[39m
2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent''

2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent''

[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent''

2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolInterface - make sure that stop removes all actions''

[36m# #ThaliPeerPoolInterface - make sure that stop removes all actions
[39m
[33m# #ThaliPeerPoolInterface - make sure that stop removes all actions
[39m
[32m# #ThaliPeerPoolInterface - make sure that stop removes all actions
[39m
2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolInterface - make sure that stop removes all actions''

2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolInterface - make sure that stop removes all actions''

[36mok 574 1st good enqueue
ok 575 2nd good enqueue
[39m
[36mok 576 1st action is in the pool
ok 577 2nd action is in the pool
[39m
[36mok 578 1st action is out of the pool
[39m
[36mok 579 2st action is out of the pool
ok 580 pool is empty
[39m
[36m# teardown
[39m
[32mok 574 1st good enqueue
[39m
[32mok 575 2nd good enqueue
[39m
[32mok 576 1st action is in the pool
[39m
[32mok 577 2nd action is in the pool
[39m
[33mok 574 1st good enqueue
[39m
[32mok 578 1st action is out of the pool
[39m
[33mok 575 2nd good enqueue
[39m
[33mok 576 1st action is in the pool
ok 577 2nd action is in the pool
[39m
[32mok 579 2st action is out of the pool
[39m
[32mok 580 pool is empty
[39m
[33mok 578 1st action is out of the pool
ok 579 2st action is out of the pool
ok 580 pool is empty
# teardown
[39m
[32m# teardown
[39m
2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolInterface - make sure that stop removes all actions''

2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolInterface - make sure that stop removes all actions''

[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolInterface - make sure that stop removes all actions''

2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#setup: 'Make sure peerDictionaryKey is reasonable''

[36m# Make sure peerDictionaryKey is reasonable
[39m
[32m# Make sure peerDictionaryKey is reasonable
[39m
[33m# Make sure peerDictionaryKey is reasonable
[39m
2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#setup ok: 'Make sure peerDictionaryKey is reasonable''

2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#run: 'Make sure peerDictionaryKey is reasonable''

[36mok 581 equal keys
[39m
[36mok 582 not equal connection type
ok 583 same connection type, different buffer
[39m
[36m# teardown
[39m
[32mok 581 equal keys
ok 582 not equal connection type
ok 583 same connection type, different buffer
[39m
[32m# teardown
[39m
[33mok 581 equal keys
ok 582 not equal connection type
ok 583 same connection type, different buffer
[39m
[33m# teardown
[39m
2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#run ok: 'Make sure peerDictionaryKey is reasonable''

2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#teardown: 'Make sure peerDictionaryKey is reasonable''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#teardown ok: 'Make sure peerDictionaryKey is reasonable''

2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#setup: 'Make sure start works''

[36m# Make sure start works
[39m
[32m# Make sure start works
[39m
[33m# Make sure start works
[39m
2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#setup ok: 'Make sure start works''

2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#run: 'Make sure start works''

[36m2016-10-04 22:57:40 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
[39m
[36mok 584 First start and on called correctly
# teardown
[39m
[32m2016-10-04 22:57:40 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
[39m
[32mok 584 First start and on called correctly
# teardown
[39m
[33m2016-10-04 22:57:40 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
[39m
[33mok 584 First start and on called correctly
[39m
[33m# teardown
[39m
2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#run ok: 'Make sure start works''

2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#teardown: 'Make sure start works''

[36m# setup
[39m
[33m# setup
[39m
[32m# setup
[39m
2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#teardown ok: 'Make sure start works''

2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#setup: 'Make sure stop works''

[36m# Make sure stop works
[39m
[32m# Make sure stop works
[39m
[33m# Make sure stop works
[39m
2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#setup ok: 'Make sure stop works''

2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#run: 'Make sure stop works''

[36mok 585 second cleared dictionary
[39m
[32mok 585 second cleared dictionary
[39m
[36m2016-10-04 22:57:40 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 586 First start and on called correctly
[39m
[32m2016-10-04 22:57:40 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
[39m
[32mok 586 First start and on called correctly
[39m
[36mok 587 First stop and removeListener called correctly
ok 588 first action kill called
ok 589 second action kill called
ok 590 first cleared dictionary
ok 591 first cleared pool
ok 592 second cleared dictionary
ok 593 second cleared pool
# teardown
[39m
[33mok 585 second cleared dictionary
[39m
[32mok 587 First stop and removeListener called correctly
ok 588 first action kill called
[39m
[32mok 589 second action kill called
[39m
[32mok 590 first cleared dictionary
[39m
[32mok 591 first cleared pool
ok 592 second cleared dictionary
[39m
[32mok 593 second cleared pool
[39m
[32m# teardown
[39m
[33m2016-10-04 22:57:40 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
[39m
[33mok 586 First start and on called correctly
[39m
[33mok 587 First stop and removeListener called correctly
[39m
[33mok 588 first action kill called
ok 589 second action kill called
ok 590 first cleared dictionary
[39m
[33mok 591 first cleared pool
ok 592 second cleared dictionary
[39m
[33mok 593 second cleared pool
[39m
[33m# teardown
[39m
2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#run ok: 'Make sure stop works''

2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#teardown: 'Make sure stop works''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#teardown ok: 'Make sure stop works''

2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#setup: 'Simple peer event''

[36m# Simple peer event
[39m
[32m# Simple peer event
[39m
[33m# Simple peer event
[39m
2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#setup ok: 'Simple peer event''

2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#run: 'Simple peer event''

[36m2016-10-04 22:57:40 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
[39m
[36mok 594 listener has been set
[39m
[32m2016-10-04 22:57:40 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
[39m
[32mok 594 listener has been set
[39m
[36mok 595 peer dictionary has expected number of entries
ok 596 Dictionary and pool have same action
ok 597 ads match
ok 598 PouchDB matches
ok 599 DB Names match
ok 600 public keys match
[39m
[32mok 595 peer dictionary has expected number of entries
ok 596 Dictionary and pool have same action
[39m
[32mok 597 ads match
ok 598 PouchDB matches
ok 599 DB Names match
ok 600 public keys match
ok 601 peer dictionary has expected number of entries
ok 602 Dictionary and pool have same action
ok 603 ads match
ok 604 PouchDB matches
ok 605 DB Names match
ok 606 public keys match
[39m
[36mok 601 peer dictionary has expected number of entries
ok 602 Dictionary and pool have same action
ok 603 ads match
ok 604 PouchDB matches
ok 605 DB Names match
ok 606 public keys match
ok 607 start called once
ok 608 One entry left
ok 609 Dictionary and pool have same action
ok 610 Start never called
ok 611 Kill called once
ok 612 no entries left
[39m
[32mok 607 start called once
ok 608 One entry left
ok 609 Dictionary and pool have same action
[39m
[32mok 610 Start never called
ok 611 Kill called once
[39m
[32mok 612 no entries left
[39m
[32mok 613 Third action is dead
ok 614 peer dictionary has expected number of entries
ok 615 Dictionary and pool have same action
ok 616 ads match
ok 617 PouchDB matches
ok 618 DB Names match
ok 619 public keys match
[39m
[33m2016-10-04 22:57:40 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
[39m
[32m# teardown
[39m
[33mok 594 listener has been set
[39m
[36mok 613 Third action is dead
ok 614 peer dictionary has expected number of entries
ok 615 Dictionary and pool have same action
ok 616 ads match
ok 617 PouchDB matches
ok 618 DB Names match
ok 619 public keys match
[39m
[36m# teardown
[39m
[33mok 595 peer dictionary has expected number of entries
[39m
[33mok 596 Dictionary and pool have same action
[39m
[33mok 597 ads match
ok 598 PouchDB matches
[39m
[33mok 599 DB Names match
[39m
[33mok 600 public keys match
[39m
[33mok 601 peer dictionary has expected number of entries
[39m
[33mok 602 Dictionary and pool have same action
ok 603 ads match
[39m
[33mok 604 PouchDB matches
[39m
[33mok 605 DB Names match
[39m
[33mok 606 public keys match
[39m
[33mok 607 start called once
[39m
[33mok 608 One entry left
ok 609 Dictionary and pool have same action
[39m
[33mok 610 Start never called
[39m
[33mok 611 Kill called once
ok 612 no entries left
[39m
[33mok 613 Third action is dead
[39m
[33mok 614 peer dictionary has expected number of entries
ok 615 Dictionary and pool have same action
[39m
[33mok 616 ads match
ok 617 PouchDB matches
[39m
[33mok 618 DB Names match
[39m
[33mok 619 public keys match
[39m
[33m# teardown
[39m
2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#run ok: 'Simple peer event''

2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#teardown: 'Simple peer event''

[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#teardown ok: 'Simple peer event''

2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#setup: 'Coordinated pull replication from notification test''

[33m# Coordinated pull replication from notification test
[39m
[36m# Coordinated pull replication from notification test
[39m
[32m# Coordinated pull replication from notification test
[39m
2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#setup ok: 'Coordinated pull replication from notification test''

2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#run: 'Coordinated pull replication from notification test''

[33m2016-10-04 22:57:40 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
[39m
[36m2016-10-04 22:57:40 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
[39m
[33m2016-10-04 22:57:40 - DEBUG thaliWifiInfrastructure: 'listening 51285'
[39m
[36m2016-10-04 22:57:40 - DEBUG thaliWifiInfrastructure: 'listening 51286'
[39m
[33m{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
[39m
[32m2016-10-04 22:57:40 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
[39m
[32m2016-10-04 22:57:40 - DEBUG thaliWifiInfrastructure: 'listening 51290'
[39m
[33m2016-10-04 22:57:40 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
[33m2016-10-04 22:57:40 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
[36m2016-10-04 22:57:40 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
[33m2016-10-04 22:57:40 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
[39m
2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#sync'

[33m2016-10-04 22:57:40 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
[33m2016-10-04 22:57:40 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
[39m
[33m2016-10-04 22:57:40 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
[39m
[36m2016-10-04 22:57:40 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
[39m
[32m2016-10-04 22:57:40 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
[36m2016-10-04 22:57:40 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
[32m2016-10-04 22:57:40 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
[33m2016-10-04 22:57:40 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#sync'

[36m2016-10-04 22:57:40 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#sync'

2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#sync ok'

2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#sync'

[32m2016-10-04 22:57:40 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
[39m
[32m2016-10-04 22:57:40 - DEBUG thaliReplicationPeerAction: 'Got error in update, waiting for main loop to detect and handle -   Stop Called'
[39m
2016-10-04 22:57:40 - DEBUG UnitTestFramework: '#sync'

[36m2016-10-04 22:57:50 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 ETIMEDOUT'
[39m
[36m2016-10-04 22:57:50 - DEBUG thaliPeerPoolDefault: 'Got err  500 ETIMEDOUT'
[39m
2016-10-04 22:57:50 - DEBUG UnitTestFramework: '#sync'

2016-10-04 22:57:50 - DEBUG UnitTestFramework: '#sync ok'

[36m2016-10-04 22:57:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 620 passed
# teardown
[39m
[32m2016-10-04 22:57:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 620 passed
# teardown
[39m
[33m2016-10-04 22:57:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 620 passed
# teardown
[39m
2016-10-04 22:57:50 - DEBUG UnitTestFramework: '#run ok: 'Coordinated pull replication from notification test''

2016-10-04 22:57:50 - DEBUG UnitTestFramework: '#teardown: 'Coordinated pull replication from notification test''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:51 - DEBUG UnitTestFramework: '#teardown ok: 'Coordinated pull replication from notification test''

2016-10-04 22:57:51 - DEBUG UnitTestFramework: '#setup: 'Server is not there''

[36m# Server is not there
[39m
[32m# Server is not there
[39m
[33m# Server is not there
[39m
2016-10-04 22:57:51 - DEBUG UnitTestFramework: '#setup ok: 'Server is not there''

2016-10-04 22:57:51 - DEBUG UnitTestFramework: '#run: 'Server is not there''

[36m2016-10-04 22:57:51 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
ok 621 right error
# teardown
[39m
[36m{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
[39m
[32m2016-10-04 22:57:51 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
ok 621 right error
# teardown
[39m
[32m{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
[39m
[33m2016-10-04 22:57:51 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
ok 621 right error
[39m
[33m# teardown
[39m
2016-10-04 22:57:51 - DEBUG UnitTestFramework: '#run ok: 'Server is not there''
2016-10-04 22:57:51 - DEBUG UnitTestFramework: '#teardown: 'Server is not there''

[33m# setup
[39m
[36m# setup
[39m
[33m{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
[39m
[32m# setup
[39m
2016-10-04 22:57:51 - DEBUG UnitTestFramework: '#teardown ok: 'Server is not there''

2016-10-04 22:57:51 - DEBUG UnitTestFramework: '#setup: 'Server accepts & closes connection''

[36m# Server accepts & closes connection
[39m
[32m# Server accepts & closes connection
[39m
[33m# Server accepts & closes connection
[39m
2016-10-04 22:57:51 - DEBUG UnitTestFramework: '#setup ok: 'Server accepts & closes connection''

2016-10-04 22:57:51 - DEBUG UnitTestFramework: '#run: 'Server accepts & closes connection''

[36m2016-10-04 22:57:51 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
ok 622 right error
# teardown
[39m
[33m2016-10-04 22:57:51 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
ok 622 right error
# teardown
[39m
[32m2016-10-04 22:57:51 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
[39m
[32mok 622 right error
[39m
[32m# teardown
[39m
2016-10-04 22:57:51 - DEBUG UnitTestFramework: '#run ok: 'Server accepts & closes connection''
2016-10-04 22:57:51 - DEBUG UnitTestFramework: '#teardown: 'Server accepts & closes connection''

[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:51 - DEBUG UnitTestFramework: '#teardown ok: 'Server accepts & closes connection''

2016-10-04 22:57:51 - DEBUG UnitTestFramework: '#setup: 'Server always returns 500''

[36m# Server always returns 500
[39m
[32m# Server always returns 500
[39m
[33m# Server always returns 500
[39m
2016-10-04 22:57:51 - DEBUG UnitTestFramework: '#setup ok: 'Server always returns 500''

2016-10-04 22:57:51 - DEBUG UnitTestFramework: '#run: 'Server always returns 500''

[33m2016-10-04 22:57:51 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
ok 623 Got error as expected
# teardown
[39m
[36m2016-10-04 22:57:51 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
[39m
[36mok 623 Got error as expected
[39m
[36m# teardown
[39m
[32m2016-10-04 22:57:51 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
[39m
[32mok 623 Got error as expected
[39m
2016-10-04 22:57:51 - DEBUG UnitTestFramework: '#run ok: 'Server always returns 500''

[32m# teardown
[39m
2016-10-04 22:57:51 - DEBUG UnitTestFramework: '#teardown: 'Server always returns 500''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:51 - DEBUG UnitTestFramework: '#teardown ok: 'Server always returns 500''

2016-10-04 22:57:51 - DEBUG UnitTestFramework: '#setup: 'Server always returns 401''

[36m# Server always returns 401
[39m
[32m# Server always returns 401
[39m
[33m# Server always returns 401
[39m
2016-10-04 22:57:51 - DEBUG UnitTestFramework: '#setup ok: 'Server always returns 401''

2016-10-04 22:57:51 - DEBUG UnitTestFramework: '#run: 'Server always returns 401''

[36m2016-10-04 22:57:51 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
ok 624 Got error as expected
[39m
[36m# teardown
[39m
[33m2016-10-04 22:57:51 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
[39m
[33mok 624 Got error as expected
[39m
[33m# teardown
[39m
[32m2016-10-04 22:57:51 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
[39m
[32mok 624 Got error as expected
[39m
[32m# teardown
[39m
2016-10-04 22:57:51 - DEBUG UnitTestFramework: '#run ok: 'Server always returns 401''

2016-10-04 22:57:51 - DEBUG UnitTestFramework: '#teardown: 'Server always returns 401''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:51 - DEBUG UnitTestFramework: '#teardown ok: 'Server always returns 401''

2016-10-04 22:57:51 - DEBUG UnitTestFramework: '#setup: 'Server always returns 403''

[32m# Server always returns 403
[39m
[36m# Server always returns 403
[39m
[33m# Server always returns 403
[39m
2016-10-04 22:57:51 - DEBUG UnitTestFramework: '#setup ok: 'Server always returns 403''

2016-10-04 22:57:51 - DEBUG UnitTestFramework: '#run: 'Server always returns 403''

[36m2016-10-04 22:57:51 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
ok 625 Got error as expected
[39m
[36m# teardown
[39m
[32m2016-10-04 22:57:51 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
ok 625 Got error as expected
[39m
[32m# teardown
[39m
[33m2016-10-04 22:57:51 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
[39m
[33mok 625 Got error as expected
[39m
[33m# teardown
[39m
2016-10-04 22:57:51 - DEBUG UnitTestFramework: '#run ok: 'Server always returns 403''

2016-10-04 22:57:51 - DEBUG UnitTestFramework: '#teardown: 'Server always returns 403''

[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:51 - DEBUG UnitTestFramework: '#teardown ok: 'Server always returns 403''

2016-10-04 22:57:51 - DEBUG UnitTestFramework: '#setup: 'Make sure docs replicate''

[36m# Make sure docs replicate
[39m
[32m# Make sure docs replicate
[39m
[33m# Make sure docs replicate
[39m
2016-10-04 22:57:51 - DEBUG UnitTestFramework: '#setup ok: 'Make sure docs replicate''

2016-10-04 22:57:51 - DEBUG UnitTestFramework: '#run: 'Make sure docs replicate''

[36m2016-10-04 22:57:51 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
[33m2016-10-04 22:57:51 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
[32m2016-10-04 22:57:51 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
[33m2016-10-04 22:57:51 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
[39m
[36m2016-10-04 22:57:51 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
[39m
[32m2016-10-04 22:57:51 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
[39m
[36mok 626 should be equal
[39m
[36mok 627 All tests passed!
[39m
[36m# teardown
[39m
[33mok 626 should be equal
[39m
[33mok 627 All tests passed!
[39m
[33m# teardown
[39m
[32mok 626 should be equal
[39m
[32mok 627 All tests passed!
[39m
2016-10-04 22:57:51 - DEBUG UnitTestFramework: '#run ok: 'Make sure docs replicate''

2016-10-04 22:57:51 - DEBUG UnitTestFramework: '#teardown: 'Make sure docs replicate''

[32m# teardown
[39m
[33m# setup
[39m
[36m# setup
[39m
[32m# setup
[39m
2016-10-04 22:57:52 - DEBUG UnitTestFramework: '#teardown ok: 'Make sure docs replicate''
2016-10-04 22:57:52 - DEBUG UnitTestFramework: '#setup: 'Do nothing and make sure we time out''

[36m# Do nothing and make sure we time out
[39m
[32m# Do nothing and make sure we time out
[39m
[33m# Do nothing and make sure we time out
[39m
2016-10-04 22:57:52 - DEBUG UnitTestFramework: '#setup ok: 'Do nothing and make sure we time out''

2016-10-04 22:57:52 - DEBUG UnitTestFramework: '#run: 'Do nothing and make sure we time out''

[33m{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
[39m
[36m{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
[39m
[32m{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
[39m
[33m2016-10-04 22:57:52 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
[39m
[32m2016-10-04 22:57:52 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
[39m
[36m2016-10-04 22:57:52 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
[39m
[33mok 628 action should be killed
ok 629 Error should be timed out
[39m
[36mok 628 action should be killed
ok 629 Error should be timed out
[39m
[32mok 628 action should be killed
[39m
[32mok 629 Error should be timed out
[39m
[33mok 630 No doc found
# teardown
[39m
[36mok 630 No doc found
# teardown
[39m
[32mok 630 No doc found
# teardown
[39m
2016-10-04 22:57:54 - DEBUG UnitTestFramework: '#run ok: 'Do nothing and make sure we time out''

2016-10-04 22:57:54 - DEBUG UnitTestFramework: '#teardown: 'Do nothing and make sure we time out''

[32m# setup
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:54 - DEBUG UnitTestFramework: '#teardown ok: 'Do nothing and make sure we time out''

2016-10-04 22:57:54 - DEBUG UnitTestFramework: '#setup: 'Do something and make sure we time out''

[36m# Do something and make sure we time out
[39m
[32m# Do something and make sure we time out
[39m
[33m# Do something and make sure we time out
[39m
2016-10-04 22:57:54 - DEBUG UnitTestFramework: '#setup ok: 'Do something and make sure we time out''

2016-10-04 22:57:54 - DEBUG UnitTestFramework: '#run: 'Do something and make sure we time out''

[33m{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
[39m
[32m2016-10-04 22:57:55 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
[33m2016-10-04 22:57:55 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
[36m2016-10-04 22:57:55 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
[33m2016-10-04 22:57:55 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
[39m
[36m2016-10-04 22:57:55 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
[39m
[32m2016-10-04 22:57:55 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
[39m
[32mok 631 should be equal
[39m
[33mok 631 should be equal
[39m
[36mok 631 should be equal
[39m
[32mok 632 action should be killed
[39m
[32mok 633 Error should be timed out
[39m
[32m# teardown
[39m
[33mok 632 action should be killed
[39m
[33mok 633 Error should be timed out
[39m
[33m# teardown
[39m
[36mok 632 action should be killed
[39m
[36mok 633 Error should be timed out
[39m
2016-10-04 22:57:57 - DEBUG UnitTestFramework: '#run ok: 'Do something and make sure we time out''
2016-10-04 22:57:57 - DEBUG UnitTestFramework: '#teardown: 'Do something and make sure we time out''

[36m# teardown
[39m
[36m# setup
[39m
[32m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:57 - DEBUG UnitTestFramework: '#teardown ok: 'Do something and make sure we time out''
2016-10-04 22:57:57 - DEBUG UnitTestFramework: '#setup: 'Start replicating and then catch error when server goes''

[36m# Start replicating and then catch error when server goes
[39m
[33m# Start replicating and then catch error when server goes
[39m
[32m# Start replicating and then catch error when server goes
[39m
2016-10-04 22:57:57 - DEBUG UnitTestFramework: '#setup ok: 'Start replicating and then catch error when server goes''

2016-10-04 22:57:57 - DEBUG UnitTestFramework: '#run: 'Start replicating and then catch error when server goes''

[32mok 634 socket hung up
[39m
[36mok 634 socket hung up
[39m
[32m# teardown
[39m
[33mok 634 socket hung up
[39m
2016-10-04 22:57:57 - DEBUG UnitTestFramework: '#run ok: 'Start replicating and then catch error when server goes''

2016-10-04 22:57:57 - DEBUG UnitTestFramework: '#teardown: 'Start replicating and then catch error when server goes''

[32m# setup
[39m
[33m# teardown
[39m
[36m# teardown
[39m
[36m# setup
[39m
[33m# setup
[39m
2016-10-04 22:57:58 - DEBUG UnitTestFramework: '#teardown ok: 'Start replicating and then catch error when server goes''
2016-10-04 22:57:58 - DEBUG UnitTestFramework: '#setup: 'Coordinated replication action test''

[36m# Coordinated replication action test
[39m
[32m# Coordinated replication action test
[39m
[33m# Coordinated replication action test
[39m
2016-10-04 22:57:58 - DEBUG UnitTestFramework: '#setup ok: 'Coordinated replication action test''

2016-10-04 22:57:58 - DEBUG UnitTestFramework: '#run: 'Coordinated replication action test''

[32m2016-10-04 22:57:58 - DEBUG thaliWifiInfrastructure: 'listening 51529'
[39m
[33m2016-10-04 22:57:58 - DEBUG thaliWifiInfrastructure: 'listening 51530'
[39m
[36m2016-10-04 22:57:58 - DEBUG thaliWifiInfrastructure: 'listening 51531'
[39m
[32m2016-10-04 22:57:58 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
[32m2016-10-04 22:57:58 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
[36m2016-10-04 22:57:58 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
[33m2016-10-04 22:57:58 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
2016-10-04 22:57:58 - DEBUG UnitTestFramework: '#sync'

[32m2016-10-04 22:57:58 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
[39m
[32m2016-10-04 22:57:58 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
[39m
[36m2016-10-04 22:57:58 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
[39m
[33m2016-10-04 22:57:58 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
[39m
[33m2016-10-04 22:57:59 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
[36m2016-10-04 22:57:59 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
2016-10-04 22:57:59 - DEBUG UnitTestFramework: '#sync'

2016-10-04 22:57:59 - DEBUG UnitTestFramework: '#sync'

2016-10-04 22:57:59 - DEBUG UnitTestFramework: '#sync ok'

[33m2016-10-04 22:57:59 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
[36m2016-10-04 22:57:59 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
[32m2016-10-04 22:57:59 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
[32m2016-10-04 22:57:59 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[39m
2016-10-04 22:57:59 - DEBUG UnitTestFramework: '#sync'

[36m2016-10-04 22:57:59 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
[39m
[36m2016-10-04 22:57:59 - DEBUG thaliReplicationPeerAction: 'Got error in update, waiting for main loop to detect and handle -   Stop Called'
[39m
[33m2016-10-04 22:57:59 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
[39m
[33m2016-10-04 22:57:59 - DEBUG thaliReplicationPeerAction: 'Got error in update, waiting for main loop to detect and handle -   Stop Called'
[39m
2016-10-04 22:57:59 - DEBUG UnitTestFramework: '#sync'

2016-10-04 22:57:59 - DEBUG UnitTestFramework: '#sync'

2016-10-04 22:57:59 - DEBUG UnitTestFramework: '#sync ok'

[36m2016-10-04 22:57:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[39m
[36mok 635 passed
[39m
[36m# teardown
[39m
[32m2016-10-04 22:57:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[39m
[32mok 635 passed
[39m
[36m2016-10-04 22:57:59 - ERROR TestsProcess: 'uncaught promise rejection, error: 'Error: connect ECONNREFUSED', stack: 'Error: connect ECONNREFUSED
    at errnoException (net.js:837:11)
    at Object.afterConnect [as oncomplete] (net.js:829:19)''
[39m
[36m2016-10-04 22:57:59 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
[39m
[32m# teardown
[39m
[33m2016-10-04 22:57:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[39m
[33mok 635 passed
[39m
[33m# teardown
[39m
2016-10-04 22:57:59 - DEBUG UnitTestFramework: '#run ok: 'Coordinated replication action test''

2016-10-04 22:57:59 - DEBUG UnitTestFramework: '#teardown: 'Coordinated replication action test''

[33m# setup
[39m
[32m# setup
[39m
[36mExit code: 2. Exit signal: null[39m
2016-10-04 22:57:59 - INFO HttpServer: 'Socket to device name: 'bbbc781e-baac-4bef-9829-b74bb5736c8c' disconnected, reason: 'transport close''

-e [0;31mcompilation aborted
 [0m
build aborted
 [0m

npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/fs-extra-promise
npm http request GET http://192.168.1.100:4873/socket.io
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/node-uuid
npm http 200 http://192.168.1.100:4873/fs-extra-promise
npm http 200 http://192.168.1.100:4873/socket.io
npm http 200 http://192.168.1.100:4873/bluebird
npm http 200 http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/express
npm http 200 http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/cookie-signature
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/cookie
npm http request GET http://192.168.1.100:4873/accepts
npm http request GET http://192.168.1.100:4873/escape-html
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/etag
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/content-disposition
npm http request GET http://192.168.1.100:4873/array-flatten
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/parseurl
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/fresh
npm http request GET http://192.168.1.100:4873/merge-descriptors
npm http request GET http://192.168.1.100:4873/finalhandler
npm http request GET http://192.168.1.100:4873/serve-static
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/utils-merge
npm http request GET http://192.168.1.100:4873/send
npm http request GET http://192.168.1.100:4873/path-to-regexp
npm http request GET http://192.168.1.100:4873/range-parser
npm http request GET http://192.168.1.100:4873/proxy-addr
npm http request GET http://192.168.1.100:4873/vary
npm http request GET http://192.168.1.100:4873/qs
npm http 200 http://192.168.1.100:4873/cookie-signature
npm http 200 http://192.168.1.100:4873/content-type
npm http 200 http://192.168.1.100:4873/escape-html
npm http 200 http://192.168.1.100:4873/cookie
npm http 200 http://192.168.1.100:4873/accepts
npm http 200 http://192.168.1.100:4873/depd
npm http 200 http://192.168.1.100:4873/etag
npm http 200 http://192.168.1.100:4873/array-flatten
npm http 200 http://192.168.1.100:4873/debug
npm http 200 http://192.168.1.100:4873/content-disposition
npm http 200 http://192.168.1.100:4873/on-finished
npm http 200 http://192.168.1.100:4873/methods
npm http 200 http://192.168.1.100:4873/fresh
npm http 200 http://192.168.1.100:4873/merge-descriptors
npm http 200 http://192.168.1.100:4873/parseurl
npm http 200 http://192.168.1.100:4873/finalhandler
npm http 200 http://192.168.1.100:4873/serve-static
npm http 200 http://192.168.1.100:4873/utils-merge
npm http 200 http://192.168.1.100:4873/type-is
npm http 200 http://192.168.1.100:4873/send
npm http 200 http://192.168.1.100:4873/path-to-regexp
npm http 200 http://192.168.1.100:4873/range-parser
npm http 200 http://192.168.1.100:4873/proxy-addr
npm http 200 http://192.168.1.100:4873/vary
npm http 200 http://192.168.1.100:4873/qs
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
npm http request GET http://192.168.1.100:4873/statuses
npm http request GET http://192.168.1.100:4873/mime
npm http 200 http://192.168.1.100:4873/statuses
npm http 200 http://192.168.1.100:4873/http-errors
npm http 200 http://192.168.1.100:4873/destroy
npm http 200 http://192.168.1.100:4873/mime
npm http request GET http://192.168.1.100:4873/inherits
npm http 200 http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/media-typer
npm http 200 http://192.168.1.100:4873/media-typer
npm http request GET http://192.168.1.100:4873/fs-extra
npm http 200 http://192.168.1.100:4873/fs-extra
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/jsonfile
npm http request GET http://192.168.1.100:4873/rimraf
npm http 200 http://192.168.1.100:4873/rimraf
npm http 200 http://192.168.1.100:4873/graceful-fs
npm http 200 http://192.168.1.100:4873/jsonfile
npm http fetch GET http://192.168.1.100:4873/graceful-fs/-/graceful-fs-4.1.9.tgz
npm http fetch 200 http://192.168.1.100:4873/graceful-fs/-/graceful-fs-4.1.9.tgz
npm http request GET http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/fs.realpath
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http 200 http://192.168.1.100:4873/fs.realpath
npm http 200 http://192.168.1.100:4873/inflight
npm http 200 http://192.168.1.100:4873/once
npm http 200 http://192.168.1.100:4873/path-is-absolute
npm http 200 http://192.168.1.100:4873/minimatch
npm http fetch GET http://192.168.1.100:4873/path-is-absolute/-/path-is-absolute-1.0.1.tgz
npm http fetch 200 http://192.168.1.100:4873/path-is-absolute/-/path-is-absolute-1.0.1.tgz
npm http request GET http://192.168.1.100:4873/wrappy
npm http 200 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 200 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/concat-map
npm http 200 http://192.168.1.100:4873/balanced-match
npm http 200 http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/engine.io
npm http request GET http://192.168.1.100:4873/socket.io-adapter
npm http request GET http://192.168.1.100:4873/socket.io-parser
npm http request GET http://192.168.1.100:4873/has-binary
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http 200 http://192.168.1.100:4873/socket.io-parser
npm http 200 http://192.168.1.100:4873/socket.io-adapter
npm http 200 http://192.168.1.100:4873/engine.io
npm http 200 http://192.168.1.100:4873/has-binary
npm http 200 http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/base64id
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/ws
npm http 200 http://192.168.1.100:4873/base64id
npm http 200 http://192.168.1.100:4873/ws
npm http 200 http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/utf8
npm http request GET http://192.168.1.100:4873/blob
npm http 200 http://192.168.1.100:4873/base64-arraybuffer
npm http 200 http://192.168.1.100:4873/after
npm http 200 http://192.168.1.100:4873/blob
npm http 200 http://192.168.1.100:4873/utf8
npm http 200 http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/isarray
npm http 200 http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/options
npm http request GET http://192.168.1.100:4873/ultron
npm http 200 http://192.168.1.100:4873/options
npm http 200 http://192.168.1.100:4873/ultron
npm http request GET http://192.168.1.100:4873/json3
npm http request GET http://192.168.1.100:4873/component-emitter
npm http request GET http://192.168.1.100:4873/benchmark
npm http 200 http://192.168.1.100:4873/component-emitter
npm http 200 http://192.168.1.100:4873/json3
npm http 200 http://192.168.1.100:4873/benchmark
npm http request GET http://192.168.1.100:4873/component-bind
npm http request GET http://192.168.1.100:4873/parseuri
npm http request GET http://192.168.1.100:4873/indexof
npm http request GET http://192.168.1.100:4873/object-component
npm http request GET http://192.168.1.100:4873/to-array
npm http request GET http://192.168.1.100:4873/backo2
npm http request GET http://192.168.1.100:4873/engine.io-client
npm http 200 http://192.168.1.100:4873/indexof
npm http 200 http://192.168.1.100:4873/component-bind
npm http 200 http://192.168.1.100:4873/object-component
npm http 200 http://192.168.1.100:4873/to-array
npm http 200 http://192.168.1.100:4873/parseuri
npm http 200 http://192.168.1.100:4873/backo2
npm http 200 http://192.168.1.100:4873/engine.io-client
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/xmlhttprequest-ssl
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/parseqs
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/yeast
npm http 200 http://192.168.1.100:4873/has-cors
npm http 200 http://192.168.1.100:4873/xmlhttprequest-ssl
npm http 200 http://192.168.1.100:4873/parseqs
npm http 200 http://192.168.1.100:4873/parsejson
npm http 200 http://192.168.1.100:4873/component-inherit
npm http 200 http://192.168.1.100:4873/yeast
npm http request GET http://192.168.1.100:4873/better-assert
npm http 200 http://192.168.1.100:4873/better-assert
npm http request GET http://192.168.1.100:4873/callsite
npm http 200 http://192.168.1.100:4873/callsite
npm http request GET http://192.168.1.100:4873/stack-trace
npm http request GET http://192.168.1.100:4873/pkginfo
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/cycle
npm http request GET http://192.168.1.100:4873/colors
npm http request GET http://192.168.1.100:4873/async
npm http 200 http://192.168.1.100:4873/eyes
npm http 200 http://192.168.1.100:4873/cycle
npm http 200 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/pkginfo
npm http 200 http://192.168.1.100:4873/colors
npm http 200 http://192.168.1.100:4873/async
npm http 200 http://192.168.1.100:4873/stack-trace
npm WARN EPACKAGEJSON thali-test-server@0.0.1 No repository field.
npm WARN EPACKAGEJSON thali-test-server@0.0.1 No license field.
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/javascript-state-machine
npm http request GET http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/forever-agent
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/uuid
npm http 304 http://192.168.1.100:4873/express
npm http 200 http://192.168.1.100:4873/forever-agent
npm http 200 http://192.168.1.100:4873/ip
npm http 200 http://192.168.1.100:4873/body-parser
npm http 200 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/multiplex
npm http 200 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/lie
npm http 200 http://192.168.1.100:4873/js-extend
npm http 200 http://192.168.1.100:4873/javascript-state-machine
npm http 200 http://192.168.1.100:4873/uuid
npm http 200 http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/on-finished
npm http 200 http://192.168.1.100:4873/bytes
npm http 200 http://192.168.1.100:4873/type-is
npm http 200 http://192.168.1.100:4873/raw-body
npm http 200 http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/statuses
npm http 304 http://192.168.1.100:4873/statuses
npm http 304 http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/ee-first
npm http 200 http://192.168.1.100:4873/ee-first
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
npm http request GET http://192.168.1.100:4873/proxy-addr
npm http request GET http://192.168.1.100:4873/range-parser
npm http request GET http://192.168.1.100:4873/path-to-regexp
npm http request GET http://192.168.1.100:4873/serve-static
npm http request GET http://192.168.1.100:4873/utils-merge
npm http request GET http://192.168.1.100:4873/vary
npm http request GET http://192.168.1.100:4873/send
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 200 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/vary
npm http 304 http://192.168.1.100:4873/utils-merge
npm http 304 http://192.168.1.100:4873/send
npm http 304 http://192.168.1.100:4873/serve-static
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
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/immediate
npm http 200 http://192.168.1.100:4873/immediate
npm http 200 http://192.168.1.100:4873/unreachable-branch-transform
npm http 200 http://192.168.1.100:4873/es3ify
npm http 200 http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/through
npm http 200 http://192.168.1.100:4873/through
npm http 200 http://192.168.1.100:4873/jstransform
npm http 200 http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http 200 http://192.168.1.100:4873/commoner
npm http 200 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/source-map
npm http 200 http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http 200 http://192.168.1.100:4873/mkdirp
npm http 200 http://192.168.1.100:4873/private
npm http 200 http://192.168.1.100:4873/commander
npm http 304 http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/detective
npm http 200 http://192.168.1.100:4873/q
npm http 200 http://192.168.1.100:4873/recast
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http 200 http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/defined
npm http request GET http://192.168.1.100:4873/acorn
npm http 200 http://192.168.1.100:4873/defined
npm http 200 http://192.168.1.100:4873/acorn
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/inflight
npm http 304 http://192.168.1.100:4873/minimatch
npm http 304 http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/once
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
npm http 304 http://192.168.1.100:4873/isarray
npm http 200 http://192.168.1.100:4873/foreach
npm http 200 http://192.168.1.100:4873/object-keys
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
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/varint
npm http 200 http://192.168.1.100:4873/duplexify
npm http 200 http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/stream-shift
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http 200 http://192.168.1.100:4873/stream-shift
npm http 200 http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 200 http://192.168.1.100:4873/process-nextick-args
npm http 200 http://192.168.1.100:4873/buffer-shims
npm http 200 http://192.168.1.100:4873/util-deprecate
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/har-validator
npm http 200 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 200 http://192.168.1.100:4873/bl
npm http 200 http://192.168.1.100:4873/aws-sign2
npm http 200 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/oauth-sign
npm http 200 http://192.168.1.100:4873/tunnel-agent
npm http 200 http://192.168.1.100:4873/form-data
npm http 200 http://192.168.1.100:4873/http-signature
npm http 200 http://192.168.1.100:4873/json-stringify-safe
npm http 200 http://192.168.1.100:4873/stringstream
npm http 200 http://192.168.1.100:4873/combined-stream
npm http 200 http://192.168.1.100:4873/tough-cookie
npm http 200 http://192.168.1.100:4873/hawk
npm http 200 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 200 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/lodash
npm http 200 http://192.168.1.100:4873/lodash
npm http fetch GET http://192.168.1.100:4873/lodash/-/lodash-4.16.3.tgz
npm http fetch 200 http://192.168.1.100:4873/lodash/-/lodash-4.16.3.tgz
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http 304 http://192.168.1.100:4873/bluebird
npm http 200 http://192.168.1.100:4873/chalk
npm http 200 http://192.168.1.100:4873/is-my-json-valid
npm http fetch GET http://192.168.1.100:4873/is-my-json-valid/-/is-my-json-valid-2.15.0.tgz
npm http fetch 200 http://192.168.1.100:4873/is-my-json-valid/-/is-my-json-valid-2.15.0.tgz
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 200 http://192.168.1.100:4873/has-ansi
npm http 200 http://192.168.1.100:4873/strip-ansi
npm http 200 http://192.168.1.100:4873/supports-color
npm http 200 http://192.168.1.100:4873/ansi-styles
npm http 200 http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 200 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 200 http://192.168.1.100:4873/generate-function
npm http 200 http://192.168.1.100:4873/jsonpointer
npm http 200 http://192.168.1.100:4873/generate-object-property
npm http fetch GET http://192.168.1.100:4873/jsonpointer/-/jsonpointer-4.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/jsonpointer/-/jsonpointer-4.0.0.tgz
npm http request GET http://192.168.1.100:4873/is-property
npm http 200 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/sntp
npm http 200 http://192.168.1.100:4873/sntp
npm http 200 http://192.168.1.100:4873/cryptiles
npm http 200 http://192.168.1.100:4873/boom
npm http 200 http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/ctype
npm http 200 http://192.168.1.100:4873/assert-plus
npm http 200 http://192.168.1.100:4873/ctype
npm http 200 http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/jsonschema
npm http 200 http://192.168.1.100:4873/jsonschema
npm http fetch GET http://192.168.1.100:4873/jsonschema/-/jsonschema-1.1.0.tgz
npm http fetch 200 http://192.168.1.100:4873/jsonschema/-/jsonschema-1.1.0.tgz
npm http request GET http://192.168.1.100:4873/colors
npm http request GET http://192.168.1.100:4873/cycle
npm http request GET http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/pkginfo
npm http request GET http://192.168.1.100:4873/stack-trace
npm http 304 http://192.168.1.100:4873/pkginfo
npm http 304 http://192.168.1.100:4873/cycle
npm http 304 http://192.168.1.100:4873/stack-trace
npm http 304 http://192.168.1.100:4873/colors
npm http 304 http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/jsdoc
npm http 200 http://192.168.1.100:4873/jsdoc
npm http request GET http://192.168.1.100:4873/js2xmlparser
npm http request GET http://192.168.1.100:4873/catharsis
npm http request GET http://192.168.1.100:4873/underscore
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/requizzle
npm http request GET http://192.168.1.100:4873/marked
npm http request GET http://192.168.1.100:4873/wrench
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 200 http://192.168.1.100:4873/underscore
npm http 200 http://192.168.1.100:4873/strip-json-comments
npm http 200 http://192.168.1.100:4873/js2xmlparser
npm http 200 http://192.168.1.100:4873/marked
npm http 200 http://192.168.1.100:4873/wrench
npm WARN deprecated wrench@1.5.9: wrench.js is deprecated! You should check out fs-extra (https://github.com/jprichardson/node-fs-extra) for any operations you were using wrench for. Thanks for all the usage over the years.
npm http 200 http://192.168.1.100:4873/requizzle
npm http 200 http://192.168.1.100:4873/catharsis
npm http fetch 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http request GET http://192.168.1.100:4873/underscore-contrib
npm http 200 http://192.168.1.100:4873/underscore-contrib
npm WARN prefer global marked@0.3.6 should be installed with -g
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/end-with
npm http request GET http://192.168.1.100:4873/findit
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/fs-extra-promise
npm http request GET http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/jxc
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/unzip
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 200 http://192.168.1.100:4873/findit
npm http 304 http://192.168.1.100:4873/bluebird
npm http 200 http://192.168.1.100:4873/end-with
npm http 304 http://192.168.1.100:4873/lie
npm http 304 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/randomstring
npm http 200 http://192.168.1.100:4873/jxc
npm http 200 http://192.168.1.100:4873/unzip
npm http 304 http://192.168.1.100:4873/fs-extra-promise
npm http request GET http://192.168.1.100:4873/fs-extra
npm http 304 http://192.168.1.100:4873/fs-extra
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/jsonfile
npm http request GET http://192.168.1.100:4873/rimraf
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http 304 http://192.168.1.100:4873/jsonfile
npm http 304 http://192.168.1.100:4873/rimraf
npm http request GET http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/fs.realpath
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/inflight
npm http 304 http://192.168.1.100:4873/minimatch
npm http 304 http://192.168.1.100:4873/fs.realpath
npm http 304 http://192.168.1.100:4873/inherits
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
npm http request GET http://192.168.1.100:4873/progress
npm http request GET http://192.168.1.100:4873/adm-zip
npm http 200 http://192.168.1.100:4873/progress
npm http 200 http://192.168.1.100:4873/adm-zip
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 304 http://192.168.1.100:4873/immediate
npm http 304 http://192.168.1.100:4873/inline-process-browser
npm http 304 http://192.168.1.100:4873/es3ify
npm http 304 http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/through
npm http 304 http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/through
npm http 304 http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/base62
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/commoner
npm http 304 http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/detective
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/commander
npm http 304 http://192.168.1.100:4873/private
npm http 304 http://192.168.1.100:4873/mkdirp
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
npm http 304 http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/foreach
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
npm http request GET http://192.168.1.100:4873/array-uniq
npm http 200 http://192.168.1.100:4873/array-uniq
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/forever-agent
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/mime-types
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
npm http 304 http://192.168.1.100:4873/forever-agent
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/process-nextick-args
npm http 304 http://192.168.1.100:4873/util-deprecate
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/lodash
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
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/ansi-styles
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/strip-ansi
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
npm http 304 http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/cryptiles
npm http 304 http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 304 http://192.168.1.100:4873/asn1
npm http 200 http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/pullstream
npm http request GET http://192.168.1.100:4873/fstream
npm http request GET http://192.168.1.100:4873/binary
npm http request GET http://192.168.1.100:4873/setimmediate
npm http request GET http://192.168.1.100:4873/match-stream
npm http 200 http://192.168.1.100:4873/fstream
npm http 200 http://192.168.1.100:4873/binary
npm http 200 http://192.168.1.100:4873/setimmediate
npm http 200 http://192.168.1.100:4873/pullstream
npm http 200 http://192.168.1.100:4873/match-stream
npm http request GET http://192.168.1.100:4873/buffers
npm http request GET http://192.168.1.100:4873/chainsaw
npm http 200 http://192.168.1.100:4873/chainsaw
npm http 200 http://192.168.1.100:4873/buffers
npm http request GET http://192.168.1.100:4873/traverse
npm http 200 http://192.168.1.100:4873/traverse
npm http request GET http://192.168.1.100:4873/natives
npm http 200 http://192.168.1.100:4873/natives
npm http request GET http://192.168.1.100:4873/slice-stream
npm http request GET http://192.168.1.100:4873/over
npm http 200 http://192.168.1.100:4873/slice-stream
npm http 200 http://192.168.1.100:4873/over
npm WARN EPACKAGEJSON install@0.0.1 No repository field.
npm http request GET http://192.168.1.100:4873/uuid-validate
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/bn.js
npm http request GET http://192.168.1.100:4873/forever-agent
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/express-pouchdb
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/leveldown-mobile
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/proxyquire
npm http request GET http://192.168.1.100:4873/nock
npm http request GET http://192.168.1.100:4873/request-promise
npm http request GET http://192.168.1.100:4873/supertest-as-promised
npm http request GET http://192.168.1.100:4873/tape-catch
npm http request GET http://192.168.1.100:4873/sinon
npm http request GET http://192.168.1.100:4873/tmp
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/tape
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/supertest
npm http request GET http://192.168.1.100:4873/pouchdb-size
npm http request GET http://192.168.1.100:4873/pouchdb
npm http 304 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/forever-agent
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/js-extend
npm http 200 http://192.168.1.100:4873/bn.js
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/long
npm http 200 http://192.168.1.100:4873/uuid-validate
npm http 200 http://192.168.1.100:4873/express-pouchdb
npm http fetch GET http://192.168.1.100:4873/uuid-validate/-/uuid-validate-0.0.2.tgz
npm http fetch GET http://192.168.1.100:4873/express-pouchdb/-/express-pouchdb-1.0.5-thali.tgz
npm http 200 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/multiplex
npm http 304 http://192.168.1.100:4873/randomstring
npm http 304 http://192.168.1.100:4873/socket.io-client
npm http 200 http://192.168.1.100:4873/proxyquire
npm http 304 http://192.168.1.100:4873/leveldown-mobile
npm http 304 http://192.168.1.100:4873/uuid
npm http 200 http://192.168.1.100:4873/supertest-as-promised
npm http 200 http://192.168.1.100:4873/request-promise
npm http 304 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/nock
npm http 304 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/tmp
npm http 200 http://192.168.1.100:4873/sinon
npm http 200 http://192.168.1.100:4873/pouchdb-size
npm http fetch 200 http://192.168.1.100:4873/uuid-validate/-/uuid-validate-0.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/express-pouchdb/-/express-pouchdb-1.0.5-thali.tgz
npm http 200 http://192.168.1.100:4873/tape-catch
npm http 200 http://192.168.1.100:4873/tape
npm http 200 http://192.168.1.100:4873/pouchdb
npm http 200 http://192.168.1.100:4873/supertest
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
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/bytes
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/type-is
npm http 304 http://192.168.1.100:4873/on-finished
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
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/vary
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/serve-static
npm http 304 http://192.168.1.100:4873/send
npm http 304 http://192.168.1.100:4873/utils-merge
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
npm http request GET http://192.168.1.100:4873/basic-auth
npm http request GET http://192.168.1.100:4873/cookie-parser
npm http request GET http://192.168.1.100:4873/compression
npm http request GET http://192.168.1.100:4873/multiparty
npm http request GET http://192.168.1.100:4873/header-case-normalizer
npm http request GET http://192.168.1.100:4873/pouchdb-all-dbs
npm http request GET http://192.168.1.100:4873/pouchdb-find
npm http request GET http://192.168.1.100:4873/pouchdb-auth
npm http request GET http://192.168.1.100:4873/pouchdb-list
npm http request GET http://192.168.1.100:4873/pouchdb-update
npm http request GET http://192.168.1.100:4873/pouchdb-show
npm http request GET http://192.168.1.100:4873/pouchdb-security
npm http request GET http://192.168.1.100:4873/pouchdb-replicator
npm http request GET http://192.168.1.100:4873/pouchdb-rewrite
npm http request GET http://192.168.1.100:4873/pouchdb-validation
npm http request GET http://192.168.1.100:4873/pouchdb-vhost
npm http request GET http://192.168.1.100:4873/pouchdb-wrappers
npm http 304 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/basic-auth
npm http 200 http://192.168.1.100:4873/compression
npm http 200 http://192.168.1.100:4873/cookie-parser
npm http 200 http://192.168.1.100:4873/multiparty
npm http 200 http://192.168.1.100:4873/pouchdb-all-dbs
npm http 200 http://192.168.1.100:4873/pouchdb-auth
npm http 200 http://192.168.1.100:4873/pouchdb-update
npm http 200 http://192.168.1.100:4873/header-case-normalizer
npm http 200 http://192.168.1.100:4873/pouchdb-list
npm http 200 http://192.168.1.100:4873/pouchdb-show
npm http 200 http://192.168.1.100:4873/pouchdb-find
npm http 200 http://192.168.1.100:4873/pouchdb-validation
npm http 200 http://192.168.1.100:4873/pouchdb-vhost
npm http 200 http://192.168.1.100:4873/pouchdb-replicator
npm http 200 http://192.168.1.100:4873/pouchdb-rewrite
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
npm http request GET http://192.168.1.100:4873/argsarray
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/tiny-queue
npm http 304 http://192.168.1.100:4873/es3ify
npm http 200 http://192.168.1.100:4873/tiny-queue
npm http 200 http://192.168.1.100:4873/pouchdb-promise
npm http 200 http://192.168.1.100:4873/argsarray
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
npm http request GET http://192.168.1.100:4873/promise-nodify
npm http request GET http://192.168.1.100:4873/crypto-lite
npm http request GET http://192.168.1.100:4873/pouchdb-system-db
npm http request GET http://192.168.1.100:4873/secure-random
npm http request GET http://192.168.1.100:4873/pouchdb-req-http-query
npm http request GET http://192.168.1.100:4873/pouchdb-plugin-error
npm http request GET http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http 200 http://192.168.1.100:4873/base64url
npm http 200 http://192.168.1.100:4873/promise-nodify
npm http 200 http://192.168.1.100:4873/pouchdb-req-http-query
npm http 200 http://192.168.1.100:4873/pouchdb-system-db
npm http 200 http://192.168.1.100:4873/couchdb-calculate-session-id
npm http 200 http://192.168.1.100:4873/crypto-lite
npm http 200 http://192.168.1.100:4873/secure-random
npm http 200 http://192.168.1.100:4873/pouchdb-plugin-error
npm http 200 http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http request GET http://192.168.1.100:4873/meow
npm http request GET http://192.168.1.100:4873/concat-stream
npm http 200 http://192.168.1.100:4873/meow
npm http 200 http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/typedarray
npm http 200 http://192.168.1.100:4873/typedarray
npm http request GET http://192.168.1.100:4873/camelcase-keys
npm http request GET http://192.168.1.100:4873/indent-string
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
npm http fetch GET http://192.168.1.100:4873/is-finite/-/is-finite-1.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/is-finite/-/is-finite-1.0.2.tgz
npm http request GET http://192.168.1.100:4873/number-is-nan
npm http 200 http://192.168.1.100:4873/number-is-nan
npm http fetch GET http://192.168.1.100:4873/number-is-nan/-/number-is-nan-1.0.1.tgz
npm http fetch 200 http://192.168.1.100:4873/number-is-nan/-/number-is-nan-1.0.1.tgz
npm http request GET http://192.168.1.100:4873/aproba
npm http 200 http://192.168.1.100:4873/aproba
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/fruitdown
npm http request GET http://192.168.1.100:4873/es6-promise-pool
npm http request GET http://192.168.1.100:4873/level-write-stream
npm http request GET http://192.168.1.100:4873/pouchdb-collate
npm http request GET http://192.168.1.100:4873/memdown
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/localstorage-down
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/scope-eval
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/vuvuzela
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/js-extend
npm http 200 http://192.168.1.100:4873/double-ended-queue
npm http 200 http://192.168.1.100:4873/level-write-stream
npm http 200 http://192.168.1.100:4873/es6-promise-pool
npm http 200 http://192.168.1.100:4873/fruitdown
npm http 200 http://192.168.1.100:4873/pouchdb-collate
npm http 200 http://192.168.1.100:4873/memdown
npm http 304 http://192.168.1.100:4873/through2
npm http 200 http://192.168.1.100:4873/localstorage-down
npm http 200 http://192.168.1.100:4873/spark-md5
npm http 200 http://192.168.1.100:4873/scope-eval
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/js-extend
npm http 200 http://192.168.1.100:4873/sublevel-pouchdb
npm http 200 http://192.168.1.100:4873/levelup
npm http 200 http://192.168.1.100:4873/pouchdb-collections
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
npm http request GET http://192.168.1.100:4873/level-iterator-stream
npm http request GET http://192.168.1.100:4873/prr
npm http request GET http://192.168.1.100:4873/level-errors
npm http request GET http://192.168.1.100:4873/deferred-leveldown
npm http request GET http://192.168.1.100:4873/level-codec
npm http request GET http://192.168.1.100:4873/semver
npm http 200 http://192.168.1.100:4873/prr
npm http 200 http://192.168.1.100:4873/level-iterator-stream
npm http 200 http://192.168.1.100:4873/deferred-leveldown
npm http 200 http://192.168.1.100:4873/level-codec
npm http 200 http://192.168.1.100:4873/semver
npm http 200 http://192.168.1.100:4873/level-errors
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
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/aws4
npm http request GET http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/is-typedarray
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/har-validator
npm http 200 http://192.168.1.100:4873/aws4
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/stringstream
npm WARN deprecated tough-cookie@2.2.2: ReDoS vulnerability parsing Set-Cookie https://nodesecurity.io/advisories/130
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 200 http://192.168.1.100:4873/is-typedarray
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/readable-stream
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
npm http 200 http://192.168.1.100:4873/pinkie-promise
npm http 304 http://192.168.1.100:4873/chalk
npm http 304 http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/ansi-styles
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http 304 http://192.168.1.100:4873/supports-color
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http 304 http://192.168.1.100:4873/generate-function
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http request GET http://192.168.1.100:4873/pinkie
npm http 200 http://192.168.1.100:4873/pinkie
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/cryptiles
npm http 304 http://192.168.1.100:4873/boom
npm http 304 http://192.168.1.100:4873/hoek
npm http 304 http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/jsprim
npm http request GET http://192.168.1.100:4873/sshpk
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 200 http://192.168.1.100:4873/jsprim
npm http 200 http://192.168.1.100:4873/sshpk
npm http fetch GET http://192.168.1.100:4873/sshpk/-/sshpk-1.10.1.tgz
npm http fetch 200 http://192.168.1.100:4873/sshpk/-/sshpk-1.10.1.tgz
npm http request GET http://192.168.1.100:4873/json-schema
npm http request GET http://192.168.1.100:4873/extsprintf
npm http request GET http://192.168.1.100:4873/verror
npm http 200 http://192.168.1.100:4873/extsprintf
npm http 200 http://192.168.1.100:4873/json-schema
npm http 200 http://192.168.1.100:4873/verror
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/getpass
npm http request GET http://192.168.1.100:4873/dashdash
npm http 304 http://192.168.1.100:4873/asn1
npm http 200 http://192.168.1.100:4873/getpass
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
npm http 200 http://192.168.1.100:4873/bluebird
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
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/pouchdb-extend
npm http request GET http://192.168.1.100:4873/is-array
npm http request GET http://192.168.1.100:4873/pouchdb-upsert
npm http 304 http://192.168.1.100:4873/spark-md5
npm http 200 http://192.168.1.100:4873/pouchdb-upsert
npm http 200 http://192.168.1.100:4873/is-array
npm http 200 http://192.168.1.100:4873/pouchdb-extend
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 304 http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/couchdb-render
npm http request GET http://192.168.1.100:4873/extend
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
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/get-folder-size
npm http 200 http://192.168.1.100:4873/get-folder-size
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/minimist
npm http 304 http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/fast-future
npm http 304 http://192.168.1.100:4873/abstract-leveldown
npm http 200 http://192.168.1.100:4873/fast-future
npm http 200 http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/duplexify
npm http 304 http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/stream-shift
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http 304 http://192.168.1.100:4873/stream-shift
npm http 304 http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http 304 http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/propagate
npm http request GET http://192.168.1.100:4873/deep-equal
npm http request GET http://192.168.1.100:4873/chai
npm http 304 http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/debug
npm WARN deprecated lodash@2.4.1: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
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
npm http request GET http://192.168.1.100:4873/module-not-found-error
npm http request GET http://192.168.1.100:4873/fill-keys
npm http 200 http://192.168.1.100:4873/module-not-found-error
npm http 200 http://192.168.1.100:4873/fill-keys
npm http request GET http://192.168.1.100:4873/is-object
npm http 200 http://192.168.1.100:4873/is-object
npm http request GET http://192.168.1.100:4873/array-uniq
npm http 304 http://192.168.1.100:4873/array-uniq
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/har-validator
npm http 200 http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/jsonschema
npm http 200 http://192.168.1.100:4873/jsonschema
npm http request GET http://192.168.1.100:4873/samsam
npm http request GET http://192.168.1.100:4873/util
npm http request GET http://192.168.1.100:4873/formatio
npm http request GET http://192.168.1.100:4873/lolex
npm http 200 http://192.168.1.100:4873/util
npm http 200 http://192.168.1.100:4873/samsam
npm http 200 http://192.168.1.100:4873/formatio
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
npm http 304 http://192.168.1.100:4873/component-bind
npm http 304 http://192.168.1.100:4873/engine.io-client
npm http 304 http://192.168.1.100:4873/component-emitter
npm http 304 http://192.168.1.100:4873/object-component
npm http 304 http://192.168.1.100:4873/socket.io-parser
npm http 304 http://192.168.1.100:4873/parseuri
npm http 304 http://192.168.1.100:4873/backo2
npm http 200 http://192.168.1.100:4873/indexof
npm http 304 http://192.168.1.100:4873/to-array
npm http 200 http://192.168.1.100:4873/has-binary
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/ws
npm http request GET http://192.168.1.100:4873/xmlhttprequest-ssl
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/parseqs
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/yeast
npm http 304 http://192.168.1.100:4873/ws
npm http 304 http://192.168.1.100:4873/has-cors
npm http 304 http://192.168.1.100:4873/engine.io-parser
npm http 304 http://192.168.1.100:4873/parsejson
npm http 304 http://192.168.1.100:4873/xmlhttprequest-ssl
npm http 304 http://192.168.1.100:4873/component-inherit
npm http 304 http://192.168.1.100:4873/parseqs
npm http 304 http://192.168.1.100:4873/yeast
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/utf8
npm http 304 http://192.168.1.100:4873/after
npm http 304 http://192.168.1.100:4873/utf8
npm http 304 http://192.168.1.100:4873/blob
npm http 304 http://192.168.1.100:4873/arraybuffer.slice
npm http 304 http://192.168.1.100:4873/base64-arraybuffer
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
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/formidable
npm http request GET http://192.168.1.100:4873/cookiejar
npm http request GET http://192.168.1.100:4873/reduce-component
npm http 304 http://192.168.1.100:4873/methods
npm http 200 http://192.168.1.100:4873/reduce-component
npm http 304 http://192.168.1.100:4873/form-data
npm http 200 http://192.168.1.100:4873/formidable
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
npm http 304 http://192.168.1.100:4873/defined
npm http 200 http://192.168.1.100:4873/resumer
npm http 304 http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/object-inspect
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
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }

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

Error: Command failed: npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/fs-extra-promise
npm http request GET http://192.168.1.100:4873/socket.io
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/node-uuid
npm http 200 http://192.168.1.100:4873/fs-extra-promise
npm http 200 http://192.168.1.100:4873/socket.io
npm http 200 http://192.168.1.100:4873/bluebird
npm http 200 http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/express
npm http 200 http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/cookie-signature
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/cookie
npm http request GET http://192.168.1.100:4873/accepts
npm http request GET http://192.168.1.100:4873/escape-html
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/etag
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/content-disposition
npm http request GET http://192.168.1.100:4873/array-flatten
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/parseurl
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/fresh
npm http request GET http://192.168.1.100:4873/merge-descriptors
npm http request GET http://192.168.1.100:4873/finalhandler
npm http request GET http://192.168.1.100:4873/serve-static
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/utils-merge
npm http request GET http://192.168.1.100:4873/send
npm http request GET http://192.168.1.100:4873/path-to-regexp
npm http request GET http://192.168.1.100:4873/range-parser
npm http request GET http://192.168.1.100:4873/proxy-addr
npm http request GET http://192.168.1.100:4873/vary
npm http request GET http://192.168.1.100:4873/qs
npm http 200 http://192.168.1.100:4873/cookie-signature
npm http 200 http://192.168.1.100:4873/content-type
npm http 200 http://192.168.1.100:4873/escape-html
npm http 200 http://192.168.1.100:4873/cookie
npm http 200 http://192.168.1.100:4873/accepts
npm http 200 http://192.168.1.100:4873/depd
npm http 200 http://192.168.1.100:4873/etag
npm http 200 http://192.168.1.100:4873/array-flatten
npm http 200 http://192.168.1.100:4873/debug
npm http 200 http://192.168.1.100:4873/content-disposition
npm http 200 http://192.168.1.100:4873/on-finished
npm http 200 http://192.168.1.100:4873/methods
npm http 200 http://192.168.1.100:4873/fresh
npm http 200 http://192.168.1.100:4873/merge-descriptors
npm http 200 http://192.168.1.100:4873/parseurl
npm http 200 http://192.168.1.100:4873/finalhandler
npm http 200 http://192.168.1.100:4873/serve-static
npm http 200 http://192.168.1.100:4873/utils-merge
npm http 200 http://192.168.1.100:4873/type-is
npm http 200 http://192.168.1.100:4873/send
npm http 200 http://192.168.1.100:4873/path-to-regexp
npm http 200 http://192.168.1.100:4873/range-parser
npm http 200 http://192.168.1.100:4873/proxy-addr
npm http 200 http://192.168.1.100:4873/vary
npm http 200 http://192.168.1.100:4873/qs
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
npm http request GET http://192.168.1.100:4873/statuses
npm http request GET http://192.168.1.100:4873/mime
npm http 200 http://192.168.1.100:4873/statuses
npm http 200 http://192.168.1.100:4873/http-errors
npm http 200 http://192.168.1.100:4873/destroy
npm http 200 http://192.168.1.100:4873/mime
npm http request GET http://192.168.1.100:4873/inherits
npm http 200 http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/media-typer
npm http 200 http://192.168.1.100:4873/media-typer
npm http request GET http://192.168.1.100:4873/fs-extra
npm http 200 http://192.168.1.100:4873/fs-extra
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/jsonfile
npm http request GET http://192.168.1.100:4873/rimraf
npm http 200 http://192.168.1.100:4873/rimraf
npm http 200 http://192.168.1.100:4873/graceful-fs
npm http 200 http://192.168.1.100:4873/jsonfile
npm http fetch GET http://192.168.1.100:4873/graceful-fs/-/graceful-fs-4.1.9.tgz
npm http fetch 200 http://192.168.1.100:4873/graceful-fs/-/graceful-fs-4.1.9.tgz
npm http request GET http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/fs.realpath
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http 200 http://192.168.1.100:4873/fs.realpath
npm http 200 http://192.168.1.100:4873/inflight
npm http 200 http://192.168.1.100:4873/once
npm http 200 http://192.168.1.100:4873/path-is-absolute
npm http 200 http://192.168.1.100:4873/minimatch
npm http fetch GET http://192.168.1.100:4873/path-is-absolute/-/path-is-absolute-1.0.1.tgz
npm http fetch 200 http://192.168.1.100:4873/path-is-absolute/-/path-is-absolute-1.0.1.tgz
npm http request GET http://192.168.1.100:4873/wrappy
npm http 200 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 200 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/concat-map
npm http 200 http://192.168.1.100:4873/balanced-match
npm http 200 http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/engine.io
npm http request GET http://192.168.1.100:4873/socket.io-adapter
npm http request GET http://192.168.1.100:4873/socket.io-parser
npm http request GET http://192.168.1.100:4873/has-binary
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http 200 http://192.168.1.100:4873/socket.io-parser
npm http 200 http://192.168.1.100:4873/socket.io-adapter
npm http 200 http://192.168.1.100:4873/engine.io
npm http 200 http://192.168.1.100:4873/has-binary
npm http 200 http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/base64id
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/ws
npm http 200 http://192.168.1.100:4873/base64id
npm http 200 http://192.168.1.100:4873/ws
npm http 200 http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/utf8
npm http request GET http://192.168.1.100:4873/blob
npm http 200 http://192.168.1.100:4873/base64-arraybuffer
npm http 200 http://192.168.1.100:4873/after
npm http 200 http://192.168.1.100:4873/blob
npm http 200 http://192.168.1.100:4873/utf8
npm http 200 http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/isarray
npm http 200 http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/options
npm http request GET http://192.168.1.100:4873/ultron
npm http 200 http://192.168.1.100:4873/options
npm http 200 http://192.168.1.100:4873/ultron
npm http request GET http://192.168.1.100:4873/json3
npm http request GET http://192.168.1.100:4873/component-emitter
npm http request GET http://192.168.1.100:4873/benchmark
npm http 200 http://192.168.1.100:4873/component-emitter
npm http 200 http://192.168.1.100:4873/json3
npm http 200 http://192.168.1.100:4873/benchmark
npm http request GET http://192.168.1.100:4873/component-bind
npm http request GET http://192.168.1.100:4873/parseuri
npm http request GET http://192.168.1.100:4873/indexof
npm http request GET http://192.168.1.100:4873/object-component
npm http request GET http://192.168.1.100:4873/to-array
npm http request GET http://192.168.1.100:4873/backo2
npm http request GET http://192.168.1.100:4873/engine.io-client
npm http 200 http://192.168.1.100:4873/indexof
npm http 200 http://192.168.1.100:4873/component-bind
npm http 200 http://192.168.1.100:4873/object-component
npm http 200 http://192.168.1.100:4873/to-array
npm http 200 http://192.168.1.100:4873/parseuri
npm http 200 http://192.168.1.100:4873/backo2
npm http 200 http://192.168.1.100:4873/engine.io-client
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/xmlhttprequest-ssl
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/parseqs
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/yeast
npm http 200 http://192.168.1.100:4873/has-cors
npm http 200 http://192.168.1.100:4873/xmlhttprequest-ssl
npm http 200 http://192.168.1.100:4873/parseqs
npm http 200 http://192.168.1.100:4873/parsejson
npm http 200 http://192.168.1.100:4873/component-inherit
npm http 200 http://192.168.1.100:4873/yeast
npm http request GET http://192.168.1.100:4873/better-assert
npm http 200 http://192.168.1.100:4873/better-assert
npm http request GET http://192.168.1.100:4873/callsite
npm http 200 http://192.168.1.100:4873/callsite
npm http request GET http://192.168.1.100:4873/stack-trace
npm http request GET http://192.168.1.100:4873/pkginfo
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/cycle
npm http request GET http://192.168.1.100:4873/colors
npm http request GET http://192.168.1.100:4873/async
npm http 200 http://192.168.1.100:4873/eyes
npm http 200 http://192.168.1.100:4873/cycle
npm http 200 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/pkginfo
npm http 200 http://192.168.1.100:4873/colors
npm http 200 http://192.168.1.100:4873/async
npm http 200 http://192.168.1.100:4873/stack-trace
npm WARN EPACKAGEJSON thali-test-server@0.0.1 No repository field.
npm WARN EPACKAGEJSON thali-test-server@0.0.1 No license field.
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/javascript-state-machine
npm http request GET http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/forever-agent
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/uuid
npm http 304 http://192.168.1.100:4873/express
npm http 200 http://192.168.1.100:4873/forever-agent
npm http 200 http://192.168.1.100:4873/ip
npm http 200 http://192.168.1.100:4873/body-parser
npm http 200 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/multiplex
npm http 200 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/lie
npm http 200 http://192.168.1.100:4873/js-extend
npm http 200 http://192.168.1.100:4873/javascript-state-machine
npm http 200 http://192.168.1.100:4873/uuid
npm http 200 http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/on-finished
npm http 200 http://192.168.1.100:4873/bytes
npm http 200 http://192.168.1.100:4873/type-is
npm http 200 http://192.168.1.100:4873/raw-body
npm http 200 http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/statuses
npm http 304 http://192.168.1.100:4873/statuses
npm http 304 http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/ee-first
npm http 200 http://192.168.1.100:4873/ee-first
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
npm http request GET http://192.168.1.100:4873/proxy-addr
npm http request GET http://192.168.1.100:4873/range-parser
npm http request GET http://192.168.1.100:4873/path-to-regexp
npm http request GET http://192.168.1.100:4873/serve-static
npm http request GET http://192.168.1.100:4873/utils-merge
npm http request GET http://192.168.1.100:4873/vary
npm http request GET http://192.168.1.100:4873/send
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 200 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/vary
npm http 304 http://192.168.1.100:4873/utils-merge
npm http 304 http://192.168.1.100:4873/send
npm http 304 http://192.168.1.100:4873/serve-static
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
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/immediate
npm http 200 http://192.168.1.100:4873/immediate
npm http 200 http://192.168.1.100:4873/unreachable-branch-transform
npm http 200 http://192.168.1.100:4873/es3ify
npm http 200 http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/through
npm http 200 http://192.168.1.100:4873/through
npm http 200 http://192.168.1.100:4873/jstransform
npm http 200 http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http 200 http://192.168.1.100:4873/commoner
npm http 200 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/source-map
npm http 200 http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http 200 http://192.168.1.100:4873/mkdirp
npm http 200 http://192.168.1.100:4873/private
npm http 200 http://192.168.1.100:4873/commander
npm http 304 http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/detective
npm http 200 http://192.168.1.100:4873/q
npm http 200 http://192.168.1.100:4873/recast
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http 200 http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/defined
npm http request GET http://192.168.1.100:4873/acorn
npm http 200 http://192.168.1.100:4873/defined
npm http 200 http://192.168.1.100:4873/acorn
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/inflight
npm http 304 http://192.168.1.100:4873/minimatch
npm http 304 http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/once
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
npm http 304 http://192.168.1.100:4873/isarray
npm http 200 http://192.168.1.100:4873/foreach
npm http 200 http://192.168.1.100:4873/object-keys
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
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/varint
npm http 200 http://192.168.1.100:4873/duplexify
npm http 200 http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/stream-shift
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http 200 http://192.168.1.100:4873/stream-shift
npm http 200 http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 200 http://192.168.1.100:4873/process-nextick-args
npm http 200 http://192.168.1.100:4873/buffer-shims
npm http 200 http://192.168.1.100:4873/util-deprecate
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/har-validator
npm http 200 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 200 http://192.168.1.100:4873/bl
npm http 200 http://192.168.1.100:4873/aws-sign2
npm http 200 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/oauth-sign
npm http 200 http://192.168.1.100:4873/tunnel-agent
npm http 200 http://192.168.1.100:4873/form-data
npm http 200 http://192.168.1.100:4873/http-signature
npm http 200 http://192.168.1.100:4873/json-stringify-safe
npm http 200 http://192.168.1.100:4873/stringstream
npm http 200 http://192.168.1.100:4873/combined-stream
npm http 200 http://192.168.1.100:4873/tough-cookie
npm http 200 http://192.168.1.100:4873/hawk
npm http 200 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 200 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/lodash
npm http 200 http://192.168.1.100:4873/lodash
npm http fetch GET http://192.168.1.100:4873/lodash/-/lodash-4.16.3.tgz
npm http fetch 200 http://192.168.1.100:4873/lodash/-/lodash-4.16.3.tgz
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http 304 http://192.168.1.100:4873/bluebird
npm http 200 http://192.168.1.100:4873/chalk
npm http 200 http://192.168.1.100:4873/is-my-json-valid
npm http fetch GET http://192.168.1.100:4873/is-my-json-valid/-/is-my-json-valid-2.15.0.tgz
npm http fetch 200 http://192.168.1.100:4873/is-my-json-valid/-/is-my-json-valid-2.15.0.tgz
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 200 http://192.168.1.100:4873/has-ansi
npm http 200 http://192.168.1.100:4873/strip-ansi
npm http 200 http://192.168.1.100:4873/supports-color
npm http 200 http://192.168.1.100:4873/ansi-styles
npm http 200 http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 200 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 200 http://192.168.1.100:4873/generate-function
npm http 200 http://192.168.1.100:4873/jsonpointer
npm http 200 http://192.168.1.100:4873/generate-object-property
npm http fetch GET http://192.168.1.100:4873/jsonpointer/-/jsonpointer-4.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/jsonpointer/-/jsonpointer-4.0.0.tgz
npm http request GET http://192.168.1.100:4873/is-property
npm http 200 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/sntp
npm http 200 http://192.168.1.100:4873/sntp
npm http 200 http://192.168.1.100:4873/cryptiles
npm http 200 http://192.168.1.100:4873/boom
npm http 200 http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/ctype
npm http 200 http://192.168.1.100:4873/assert-plus
npm http 200 http://192.168.1.100:4873/ctype
npm http 200 http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/jsonschema
npm http 200 http://192.168.1.100:4873/jsonschema
npm http fetch GET http://192.168.1.100:4873/jsonschema/-/jsonschema-1.1.0.tgz
npm http fetch 200 http://192.168.1.100:4873/jsonschema/-/jsonschema-1.1.0.tgz
npm http request GET http://192.168.1.100:4873/colors
npm http request GET http://192.168.1.100:4873/cycle
npm http request GET http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/pkginfo
npm http request GET http://192.168.1.100:4873/stack-trace
npm http 304 http://192.168.1.100:4873/pkginfo
npm http 304 http://192.168.1.100:4873/cycle
npm http 304 http://192.168.1.100:4873/stack-trace
npm http 304 http://192.168.1.100:4873/colors
npm http 304 http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/jsdoc
npm http 200 http://192.168.1.100:4873/jsdoc
npm http request GET http://192.168.1.100:4873/js2xmlparser
npm http request GET http://192.168.1.100:4873/catharsis
npm http request GET http://192.168.1.100:4873/underscore
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/requizzle
npm http request GET http://192.168.1.100:4873/marked
npm http request GET http://192.168.1.100:4873/wrench
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 200 http://192.168.1.100:4873/underscore
npm http 200 http://192.168.1.100:4873/strip-json-comments
npm http 200 http://192.168.1.100:4873/js2xmlparser
npm http 200 http://192.168.1.100:4873/marked
npm http 200 http://192.168.1.100:4873/wrench
npm WARN deprecated wrench@1.5.9: wrench.js is deprecated! You should check out fs-extra (https://github.com/jprichardson/node-fs-extra) for any operations you were using wrench for. Thanks for all the usage over the years.
npm http 200 http://192.168.1.100:4873/requizzle
npm http 200 http://192.168.1.100:4873/catharsis
npm http fetch 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http request GET http://192.168.1.100:4873/underscore-contrib
npm http 200 http://192.168.1.100:4873/underscore-contrib
npm WARN prefer global marked@0.3.6 should be installed with -g
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/end-with
npm http request GET http://192.168.1.100:4873/findit
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/fs-extra-promise
npm http request GET http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/jxc
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/unzip
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 200 http://192.168.1.100:4873/findit
npm http 304 http://192.168.1.100:4873/bluebird
npm http 200 http://192.168.1.100:4873/end-with
npm http 304 http://192.168.1.100:4873/lie
npm http 304 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/randomstring
npm http 200 http://192.168.1.100:4873/jxc
npm http 200 http://192.168.1.100:4873/unzip
npm http 304 http://192.168.1.100:4873/fs-extra-promise
npm http request GET http://192.168.1.100:4873/fs-extra
npm http 304 http://192.168.1.100:4873/fs-extra
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/jsonfile
npm http request GET http://192.168.1.100:4873/rimraf
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http 304 http://192.168.1.100:4873/jsonfile
npm http 304 http://192.168.1.100:4873/rimraf
npm http request GET http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/fs.realpath
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/inflight
npm http 304 http://192.168.1.100:4873/minimatch
npm http 304 http://192.168.1.100:4873/fs.realpath
npm http 304 http://192.168.1.100:4873/inherits
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
npm http request GET http://192.168.1.100:4873/progress
npm http request GET http://192.168.1.100:4873/adm-zip
npm http 200 http://192.168.1.100:4873/progress
npm http 200 http://192.168.1.100:4873/adm-zip
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 304 http://192.168.1.100:4873/immediate
npm http 304 http://192.168.1.100:4873/inline-process-browser
npm http 304 http://192.168.1.100:4873/es3ify
npm http 304 http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/through
npm http 304 http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/through
npm http 304 http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/base62
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/commoner
npm http 304 http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/detective
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/commander
npm http 304 http://192.168.1.100:4873/private
npm http 304 http://192.168.1.100:4873/mkdirp
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
npm http 304 http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/foreach
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
npm http request GET http://192.168.1.100:4873/array-uniq
npm http 200 http://192.168.1.100:4873/array-uniq
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/forever-agent
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/mime-types
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
npm http 304 http://192.168.1.100:4873/forever-agent
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/process-nextick-args
npm http 304 http://192.168.1.100:4873/util-deprecate
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/lodash
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
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/ansi-styles
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/strip-ansi
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
npm http 304 http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/cryptiles
npm http 304 http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 304 http://192.168.1.100:4873/asn1
npm http 200 http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/pullstream
npm http request GET http://192.168.1.100:4873/fstream
npm http request GET http://192.168.1.100:4873/binary
npm http request GET http://192.168.1.100:4873/setimmediate
npm http request GET http://192.168.1.100:4873/match-stream
npm http 200 http://192.168.1.100:4873/fstream
npm http 200 http://192.168.1.100:4873/binary
npm http 200 http://192.168.1.100:4873/setimmediate
npm http 200 http://192.168.1.100:4873/pullstream
npm http 200 http://192.168.1.100:4873/match-stream
npm http request GET http://192.168.1.100:4873/buffers
npm http request GET http://192.168.1.100:4873/chainsaw
npm http 200 http://192.168.1.100:4873/chainsaw
npm http 200 http://192.168.1.100:4873/buffers
npm http request GET http://192.168.1.100:4873/traverse
npm http 200 http://192.168.1.100:4873/traverse
npm http request GET http://192.168.1.100:4873/natives
npm http 200 http://192.168.1.100:4873/natives
npm http request GET http://192.168.1.100:4873/slice-stream
npm http request GET http://192.168.1.100:4873/over
npm http 200 http://192.168.1.100:4873/slice-stream
npm http 200 http://192.168.1.100:4873/over
npm WARN EPACKAGEJSON install@0.0.1 No repository field.
npm http request GET http://192.168.1.100:4873/uuid-validate
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/bn.js
npm http request GET http://192.168.1.100:4873/forever-agent
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/express-pouchdb
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/leveldown-mobile
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/proxyquire
npm http request GET http://192.168.1.100:4873/nock
npm http request GET http://192.168.1.100:4873/request-promise
npm http request GET http://192.168.1.100:4873/supertest-as-promised
npm http request GET http://192.168.1.100:4873/tape-catch
npm http request GET http://192.168.1.100:4873/sinon
npm http request GET http://192.168.1.100:4873/tmp
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/tape
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/supertest
npm http request GET http://192.168.1.100:4873/pouchdb-size
npm http request GET http://192.168.1.100:4873/pouchdb
npm http 304 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/forever-agent
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/js-extend
npm http 200 http://192.168.1.100:4873/bn.js
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/long
npm http 200 http://192.168.1.100:4873/uuid-validate
npm http 200 http://192.168.1.100:4873/express-pouchdb
npm http fetch GET http://192.168.1.100:4873/uuid-validate/-/uuid-validate-0.0.2.tgz
npm http fetch GET http://192.168.1.100:4873/express-pouchdb/-/express-pouchdb-1.0.5-thali.tgz
npm http 200 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/multiplex
npm http 304 http://192.168.1.100:4873/randomstring
npm http 304 http://192.168.1.100:4873/socket.io-client
npm http 200 http://192.168.1.100:4873/proxyquire
npm http 304 http://192.168.1.100:4873/leveldown-mobile
npm http 304 http://192.168.1.100:4873/uuid
npm http 200 http://192.168.1.100:4873/supertest-as-promised
npm http 200 http://192.168.1.100:4873/request-promise
npm http 304 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/nock
npm http 304 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/tmp
npm http 200 http://192.168.1.100:4873/sinon
npm http 200 http://192.168.1.100:4873/pouchdb-size
npm http fetch 200 http://192.168.1.100:4873/uuid-validate/-/uuid-validate-0.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/express-pouchdb/-/express-pouchdb-1.0.5-thali.tgz
npm http 200 http://192.168.1.100:4873/tape-catch
npm http 200 http://192.168.1.100:4873/tape
npm http 200 http://192.168.1.100:4873/pouchdb
npm http 200 http://192.168.1.100:4873/supertest
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
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/bytes
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/type-is
npm http 304 http://192.168.1.100:4873/on-finished
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
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/vary
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/serve-static
npm http 304 http://192.168.1.100:4873/send
npm http 304 http://192.168.1.100:4873/utils-merge
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
npm http request GET http://192.168.1.100:4873/basic-auth
npm http request GET http://192.168.1.100:4873/cookie-parser
npm http request GET http://192.168.1.100:4873/compression
npm http request GET http://192.168.1.100:4873/multiparty
npm http request GET http://192.168.1.100:4873/header-case-normalizer
npm http request GET http://192.168.1.100:4873/pouchdb-all-dbs
npm http request GET http://192.168.1.100:4873/pouchdb-find
npm http request GET http://192.168.1.100:4873/pouchdb-auth
npm http request GET http://192.168.1.100:4873/pouchdb-list
npm http request GET http://192.168.1.100:4873/pouchdb-update
npm http request GET http://192.168.1.100:4873/pouchdb-show
npm http request GET http://192.168.1.100:4873/pouchdb-security
npm http request GET http://192.168.1.100:4873/pouchdb-replicator
npm http request GET http://192.168.1.100:4873/pouchdb-rewrite
npm http request GET http://192.168.1.100:4873/pouchdb-validation
npm http request GET http://192.168.1.100:4873/pouchdb-vhost
npm http request GET http://192.168.1.100:4873/pouchdb-wrappers
npm http 304 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/basic-auth
npm http 200 http://192.168.1.100:4873/compression
npm http 200 http://192.168.1.100:4873/cookie-parser
npm http 200 http://192.168.1.100:4873/multiparty
npm http 200 http://192.168.1.100:4873/pouchdb-all-dbs
npm http 200 http://192.168.1.100:4873/pouchdb-auth
npm http 200 http://192.168.1.100:4873/pouchdb-update
npm http 200 http://192.168.1.100:4873/header-case-normalizer
npm http 200 http://192.168.1.100:4873/pouchdb-list
npm http 200 http://192.168.1.100:4873/pouchdb-show
npm http 200 http://192.168.1.100:4873/pouchdb-find
npm http 200 http://192.168.1.100:4873/pouchdb-validation
npm http 200 http://192.168.1.100:4873/pouchdb-vhost
npm http 200 http://192.168.1.100:4873/pouchdb-replicator
npm http 200 http://192.168.1.100:4873/pouchdb-rewrite
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
npm http request GET http://192.168.1.100:4873/argsarray
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/tiny-queue
npm http 304 http://192.168.1.100:4873/es3ify
npm http 200 http://192.168.1.100:4873/tiny-queue
npm http 200 http://192.168.1.100:4873/pouchdb-promise
npm http 200 http://192.168.1.100:4873/argsarray
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
npm http request GET http://192.168.1.100:4873/promise-nodify
npm http request GET http://192.168.1.100:4873/crypto-lite
npm http request GET http://192.168.1.100:4873/pouchdb-system-db
npm http request GET http://192.168.1.100:4873/secure-random
npm http request GET http://192.168.1.100:4873/pouchdb-req-http-query
npm http request GET http://192.168.1.100:4873/pouchdb-plugin-error
npm http request GET http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http 200 http://192.168.1.100:4873/base64url
npm http 200 http://192.168.1.100:4873/promise-nodify
npm http 200 http://192.168.1.100:4873/pouchdb-req-http-query
npm http 200 http://192.168.1.100:4873/pouchdb-system-db
npm http 200 http://192.168.1.100:4873/couchdb-calculate-session-id
npm http 200 http://192.168.1.100:4873/crypto-lite
npm http 200 http://192.168.1.100:4873/secure-random
npm http 200 http://192.168.1.100:4873/pouchdb-plugin-error
npm http 200 http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http request GET http://192.168.1.100:4873/meow
npm http request GET http://192.168.1.100:4873/concat-stream
npm http 200 http://192.168.1.100:4873/meow
npm http 200 http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/typedarray
npm http 200 http://192.168.1.100:4873/typedarray
npm http request GET http://192.168.1.100:4873/camelcase-keys
npm http request GET http://192.168.1.100:4873/indent-string
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
npm http fetch GET http://192.168.1.100:4873/is-finite/-/is-finite-1.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/is-finite/-/is-finite-1.0.2.tgz
npm http request GET http://192.168.1.100:4873/number-is-nan
npm http 200 http://192.168.1.100:4873/number-is-nan
npm http fetch GET http://192.168.1.100:4873/number-is-nan/-/number-is-nan-1.0.1.tgz
npm http fetch 200 http://192.168.1.100:4873/number-is-nan/-/number-is-nan-1.0.1.tgz
npm http request GET http://192.168.1.100:4873/aproba
npm http 200 http://192.168.1.100:4873/aproba
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/fruitdown
npm http request GET http://192.168.1.100:4873/es6-promise-pool
npm http request GET http://192.168.1.100:4873/level-write-stream
npm http request GET http://192.168.1.100:4873/pouchdb-collate
npm http request GET http://192.168.1.100:4873/memdown
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/localstorage-down
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/scope-eval
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/vuvuzela
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/js-extend
npm http 200 http://192.168.1.100:4873/double-ended-queue
npm http 200 http://192.168.1.100:4873/level-write-stream
npm http 200 http://192.168.1.100:4873/es6-promise-pool
npm http 200 http://192.168.1.100:4873/fruitdown
npm http 200 http://192.168.1.100:4873/pouchdb-collate
npm http 200 http://192.168.1.100:4873/memdown
npm http 304 http://192.168.1.100:4873/through2
npm http 200 http://192.168.1.100:4873/localstorage-down
npm http 200 http://192.168.1.100:4873/spark-md5
npm http 200 http://192.168.1.100:4873/scope-eval
npm http 304 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/js-extend
npm http 200 http://192.168.1.100:4873/sublevel-pouchdb
npm http 200 http://192.168.1.100:4873/levelup
npm http 200 http://192.168.1.100:4873/pouchdb-collections
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
npm http request GET http://192.168.1.100:4873/level-iterator-stream
npm http request GET http://192.168.1.100:4873/prr
npm http request GET http://192.168.1.100:4873/level-errors
npm http request GET http://192.168.1.100:4873/deferred-leveldown
npm http request GET http://192.168.1.100:4873/level-codec
npm http request GET http://192.168.1.100:4873/semver
npm http 200 http://192.168.1.100:4873/prr
npm http 200 http://192.168.1.100:4873/level-iterator-stream
npm http 200 http://192.168.1.100:4873/deferred-leveldown
npm http 200 http://192.168.1.100:4873/level-codec
npm http 200 http://192.168.1.100:4873/semver
npm http 200 http://192.168.1.100:4873/level-errors
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
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/aws4
npm http request GET http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/is-typedarray
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/har-validator
npm http 200 http://192.168.1.100:4873/aws4
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/stringstream
npm WARN deprecated tough-cookie@2.2.2: ReDoS vulnerability parsing Set-Cookie https://nodesecurity.io/advisories/130
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 200 http://192.168.1.100:4873/is-typedarray
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/readable-stream
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
npm http 200 http://192.168.1.100:4873/pinkie-promise
npm http 304 http://192.168.1.100:4873/chalk
npm http 304 http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/ansi-styles
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http 304 http://192.168.1.100:4873/supports-color
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http 304 http://192.168.1.100:4873/generate-function
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http request GET http://192.168.1.100:4873/pinkie
npm http 200 http://192.168.1.100:4873/pinkie
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/cryptiles
npm http 304 http://192.168.1.100:4873/boom
npm http 304 http://192.168.1.100:4873/hoek
npm http 304 http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/jsprim
npm http request GET http://192.168.1.100:4873/sshpk
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 200 http://192.168.1.100:4873/jsprim
npm http 200 http://192.168.1.100:4873/sshpk
npm http fetch GET http://192.168.1.100:4873/sshpk/-/sshpk-1.10.1.tgz
npm http fetch 200 http://192.168.1.100:4873/sshpk/-/sshpk-1.10.1.tgz
npm http request GET http://192.168.1.100:4873/json-schema
npm http request GET http://192.168.1.100:4873/extsprintf
npm http request GET http://192.168.1.100:4873/verror
npm http 200 http://192.168.1.100:4873/extsprintf
npm http 200 http://192.168.1.100:4873/json-schema
npm http 200 http://192.168.1.100:4873/verror
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/getpass
npm http request GET http://192.168.1.100:4873/dashdash
npm http 304 http://192.168.1.100:4873/asn1
npm http 200 http://192.168.1.100:4873/getpass
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
npm http 200 http://192.168.1.100:4873/bluebird
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
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/pouchdb-extend
npm http request GET http://192.168.1.100:4873/is-array
npm http request GET http://192.168.1.100:4873/pouchdb-upsert
npm http 304 http://192.168.1.100:4873/spark-md5
npm http 200 http://192.168.1.100:4873/pouchdb-upsert
npm http 200 http://192.168.1.100:4873/is-array
npm http 200 http://192.168.1.100:4873/pouchdb-extend
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 304 http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/couchdb-render
npm http request GET http://192.168.1.100:4873/extend
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
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/get-folder-size
npm http 200 http://192.168.1.100:4873/get-folder-size
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/minimist
npm http 304 http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/fast-future
npm http 304 http://192.168.1.100:4873/abstract-leveldown
npm http 200 http://192.168.1.100:4873/fast-future
npm http 200 http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/duplexify
npm http 304 http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/stream-shift
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http 304 http://192.168.1.100:4873/stream-shift
npm http 304 http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http 304 http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/propagate
npm http request GET http://192.168.1.100:4873/deep-equal
npm http request GET http://192.168.1.100:4873/chai
npm http 304 http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/debug
npm WARN deprecated lodash@2.4.1: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
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
npm http request GET http://192.168.1.100:4873/module-not-found-error
npm http request GET http://192.168.1.100:4873/fill-keys
npm http 200 http://192.168.1.100:4873/module-not-found-error
npm http 200 http://192.168.1.100:4873/fill-keys
npm http request GET http://192.168.1.100:4873/is-object
npm http 200 http://192.168.1.100:4873/is-object
npm http request GET http://192.168.1.100:4873/array-uniq
npm http 304 http://192.168.1.100:4873/array-uniq
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/har-validator
npm http 200 http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/jsonschema
npm http 200 http://192.168.1.100:4873/jsonschema
npm http request GET http://192.168.1.100:4873/samsam
npm http request GET http://192.168.1.100:4873/util
npm http request GET http://192.168.1.100:4873/formatio
npm http request GET http://192.168.1.100:4873/lolex
npm http 200 http://192.168.1.100:4873/util
npm http 200 http://192.168.1.100:4873/samsam
npm http 200 http://192.168.1.100:4873/formatio
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
npm http 304 http://192.168.1.100:4873/component-bind
npm http 304 http://192.168.1.100:4873/engine.io-client
npm http 304 http://192.168.1.100:4873/component-emitter
npm http 304 http://192.168.1.100:4873/object-component
npm http 304 http://192.168.1.100:4873/socket.io-parser
npm http 304 http://192.168.1.100:4873/parseuri
npm http 304 http://192.168.1.100:4873/backo2
npm http 200 http://192.168.1.100:4873/indexof
npm http 304 http://192.168.1.100:4873/to-array
npm http 200 http://192.168.1.100:4873/has-binary
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/ws
npm http request GET http://192.168.1.100:4873/xmlhttprequest-ssl
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/parseqs
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/yeast
npm http 304 http://192.168.1.100:4873/ws
npm http 304 http://192.168.1.100:4873/has-cors
npm http 304 http://192.168.1.100:4873/engine.io-parser
npm http 304 http://192.168.1.100:4873/parsejson
npm http 304 http://192.168.1.100:4873/xmlhttprequest-ssl
npm http 304 http://192.168.1.100:4873/component-inherit
npm http 304 http://192.168.1.100:4873/parseqs
npm http 304 http://192.168.1.100:4873/yeast
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/utf8
npm http 304 http://192.168.1.100:4873/after
npm http 304 http://192.168.1.100:4873/utf8
npm http 304 http://192.168.1.100:4873/blob
npm http 304 http://192.168.1.100:4873/arraybuffer.slice
npm http 304 http://192.168.1.100:4873/base64-arraybuffer
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
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/formidable
npm http request GET http://192.168.1.100:4873/cookiejar
npm http request GET http://192.168.1.100:4873/reduce-component
npm http 304 http://192.168.1.100:4873/methods
npm http 200 http://192.168.1.100:4873/reduce-component
npm http 304 http://192.168.1.100:4873/form-data
npm http 200 http://192.168.1.100:4873/formidable
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
npm http 304 http://192.168.1.100:4873/defined
npm http 200 http://192.168.1.100:4873/resumer
npm http 304 http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/object-inspect
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
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }

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
